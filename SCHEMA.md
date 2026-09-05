# The data file, field by field

`iter.json` is built from `iter.md` and `library.md` by the site's build,
and nothing in it is written by hand. This page says what each part of it means,
so that a reader of the file does not have to infer the meaning from the pages
that are built from the same data. Where a rule is stated here it is the rule the
build applies; where the build and this page disagree, the build is wrong and
this page is the specification.

## Top level

| key | what it holds |
|---|---|
| `generated_from` | the two source files the build read |
| `version` | `schema`, the version of this specification; `record`, the date of the last reading anywhere in the record; `source_commit`, the last commit that touched the record's text, so a data file can be traced to the text it was built from |
| `types` | the five event types, as definitions |
| `acts` | every row of the record that is not a type, a case, a body, a national act, an instrument or an equivalent: the reporting acts, the moment every term runs from, and the prescriptions on detection |
| `calibration` | the decided cases, and the block that says what the cases did to the taxonomy |
| `authorities` | the bodies a report is owed to, one row per role and jurisdiction |
| `transpositions` | one row per national act that transposes NIS2, or per jurisdiction where none is read |
| `instruments` | the four Union instruments, with what each reaches and whom it reports to |
| `equivalents` | what binds instead of a Union instrument in a state outside the Union, one row per instrument and state |
| `sources` | the library, keyed by source id |
| `counts` | totals the pages print, computed here so they cannot drift |

## An item

Every entry in `types`, `acts`, `calibration`, `authorities`, `transpositions`,
`instruments` and `equivalents` has the same shape.

| key | meaning |
|---|---|
| `name` | the heading of the block in the record |
| `section` | the heading of the section the block sits under. For an act, the section names the types it is written for, before the middle dot, and the instrument it is written under |
| `fields` | the record's `Key: value` lines, verbatim, keyed by the key. The keys are listed below |
| `note` | the prose under the heading that is not a field |
| `sources` | the ids of the sources the block cites, in its `Source` field |
| `read` | whether every cited source carries a reading date |
| `evidence` | what holds the row up, computed; see below |
| `layer` | for an act, which of three things it is; see below |
| `id` | for an act under an instrument, its identifier; see below |

## The fields of an act

| field | meaning |
|---|---|
| `Do` | the act, as an imperative. What the page prints as the act's title |
| `Applies` | the organizations the act reaches: all, or a financial entity, or an essential or important entity, or a listed issuer |
| `Term` | the interval the instrument states, in the instrument's own unit. `Gate` marks a determination no term runs from, and every term below runs from it |
| `At` | the term in hours, where the instrument states one. A bare number is the instrument's; a number followed by a middle dot and an explanation is a position computed from two stated terms, and the explanation says how |
| `From` | the point the term runs from |
| `Anchor` | the point the term runs from in the act's own words, where `From` alone would not say enough |
| `After` | for an act with no stated hour, the act it follows on the timeline; `T0` where it follows nothing, `each term` where it stands before every term |
| `Owed to` | whom the act is owed to: a role (`dpa`, `csirt`, `financial`, `market`) the jurisdiction resolves to a body, or a body named in the act |
| `Establish` | what has to be established for the act to be performed |
| `Unless` | the condition on which the duty does not arise, in the instrument's words |
| `Public` | whether performing the act makes the matter public |
| `Implication` | a consequence the source itself states |
| `Reading` | a conclusion ITER draws from the source, marked as such on the page and not attributed to the source |
| `Effect` | for a row that is not an act but a rule about other acts, what it does; a displacement row |
| `Requires` | for a prescription on detection, what it requires |
| `Source` | the sources cited, as `[id]`, followed where useful by the provisions read |
| `Read` | the date the row was last checked against its sources |

`Term`, `At` and `From` are the instrument's. Nothing is computed from them
except the position of an act on the timeline, and a computed position says so
in `At`.

## The fields of the other items

A **type** carries `What it is`, `Rows`, `Added` and `Updated`. A type is a
definition and not an assertion about any instrument, so it cites no source and
its evidence is `definition`.

A **case** carries `Case`, who decided it; `Facts`; `Alert` and `Notified`
where the dates are known; `Held` or `Held on risk`; `Outcome`; `Documented`,
`Authority told` and `People told`, what followed as three answers; `Moves the
outcome`, what would have changed it; `Followed by`; `Actor`, where the actor
is not an insider; and `Applies to Tn`, which limb of which type the case
decides, and which it does not.

A **body** carries `Role`, `Country`, `Name`, `URL`, and for the CSIRT
`Portal`, the reporting address, `Channel`, how the report is sent, and
`Checked`, the date the address answered.

A **national act** carries `Country`, `Act`, `In force`, `Recipient`,
`Divergence`, what it does with the Directive's terms, `Moves`, whether it moves
a term or an anchor (`yes`, `no`, `unsettled`, `none`), `Stage`, where its
clock attaches on the scale below, and `Standing`, what was read and what was
not.

An **equivalent** carries `Country`, `Instead of`, the Union instrument it stands
in for, `Act`, `Term`, `From`, `At`, `Owed to`, `In force` and `Standing`.

An **instrument** carries `Full name`, `What`, `Reaches`, `Reports to` and
`Anchor`.

## Evidence

`evidence` is computed by the build from the kinds of the sources a row cites,
never written by hand.

| mark | rule |
|---|---|
| `binding` | every source is the act itself or a decided case |
| `reported` | the weakest source is a register or guidance |
| `provisional` | the weakest source is an announcement |
| `unresolved` | the row's `Moves` field records no settled position |
| `unread` | a cited source carries no reading date, or the row cites none |
| `stale` | a source is past the interval after which its kind has to be read again |
| `definition` | the row asserts nothing about an instrument: a type, or the block on the taxonomy |

Where a row cites more than one source the weakest governs. The order, from
weakest to strongest, is announcement, guidance, register, case, act. A row
that rests on an act and on guidance is `reported`, not `binding`.

## Layer

An act is one of three things. An **obligation** is a Union instrument, the
same everywhere. An **implementation** is what one Member State did with it,
and may move a term or the point it runs from. A **procedure** is the machinery
for discharging it, which body, which portal, which credential, and is national
in every case. The build assigns the layer from the section an act sits in.

## Stage

Every term runs from a moment, and the moments fall on one scale:
**occurrence**, when the event happened; **detection**, when something was
noticed; **awareness**, when the organization is taken to know, which is where
the Directive attaches; **determination**, when someone inside decides the
event qualifies. `Stage` on a national act says where that act attaches its
clock. It is assigned by this record from the wording quoted in the row, and
can be argued with against that wording.

Awareness is a standard, not a declaration: the organization is taken to know
when it has a reasonable degree of certainty that a breach has occurred, and
that is a fact about what it knew. The record of that moment is the
organization's evidence of when the standard was met. It does not create the
moment, and a record made late is a late record: the term has run from the
standard.

## Identifiers

An act under an instrument carries an identifier, citable as a control is:
`GDPR-1` is the first act under the GDPR in the order the record writes them,
and where the section is written for one type the type leads, `T1/GDPR-1`. The
sections written once for every type, DORA, NIS2 and MAR, carry no prefix, since
the row is the same row wherever it is met. An `ID` field in the record
overrides the computed one.

## Sources

`sources` is keyed by id. Each carries `title`, `url`, `issuer`, the issuing
body, jurisdiction and date on one line, `establishes`, what the record takes
from it, `kind` (`act`, `case`, `register`, `guidance`, `announcement`,
`channel`) and `read`, the date it was read. The kind sets the interval after
which the source has to be read again, and the build refuses to run once one is
overdue.

## Calibration

Where an instrument leaves a test open, the record carries the case in which a
body applied it, and supplies no threshold of its own. A case says which limb
of which type it decides; a case whose actor is external calibrates the limb
and not the actor, and the page says so.

## What is not here

Durations are not here: an interval this record has not read is an interval it
does not state. Whether the purpose of an access can be established is not
here either. And no field in this file weighs an obligation against a
recommendation, or records one as the other.
