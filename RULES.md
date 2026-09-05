---
title: How this record is kept
reviewed: 2026-09-02
---

These rules came out of building the first version of the instrument. Each one
is here because breaking it produced something that looked finished and was
wrong. They are written before the first row on purpose: they are the part that
gets eroded quietly, one reasonable exception at a time.

## What separates one event type from another

Two events are different types when they trigger different obligations, **or**
when the facts those obligations require are established by materially different
means.

The second limb was added after reading. Under the instruments mapped so far,
disclosure of personal data and unauthorized consultation of personal data
trigger the same obligations, and the first limb alone collapsed them into one.
What separates them is that one is established from logs and the other from a
reading of intent. This record exists to expose the distance between what is
owed and what can be established, so a taxonomy blind to establishment is the
wrong taxonomy for it.

An event can be more than one type, and the record carries the union of their
obligations. This was not in the first version of the rule. Reading the Board's
worked cases produced one event that is an interruption and a disclosure at
once, which the rule as written could not hold.

## Never invent a duration

Where an instrument states a term in words rather than in hours, the record
carries the words. It does not convert them, and a drawing of them gets no
fixed length.

This applies to pictures as much as to text. A bar drawn to a chosen length is
an assertion about duration, and it is harder to catch than a sentence because a
chart does not look like a claim. The first version drew "without undue delay"
as seventy-two hours and "as soon as possible" as twelve, for no reason except
that they had to fit.

Where a term is referred elsewhere, the record says so and stops until the
elsewhere is read. DORA sets no hours in Article 19; it refers them to technical
standards. Writing twenty-four hours there was inventing a figure the regulation
does not contain.

## The record supplies terms. The organization supplies durations.

How long an organization takes to do anything is not in any source and never
will be. It is asked of the reader, and the page does arithmetic on it.

No default value, no typical value, no benchmark, no peer comparison, no
maturity score. A prefilled number is a suggestion, and a suggestion about how
long a triage should take is exactly the assertion this record cannot make. The
moment a page says what is typical it stops being a reading of the law.

## On amounts

A sanction is carried as the decision states it, with the conduct and the
jurisdiction. Never an average, never a range, never a total. Averages are the
point at which this becomes a vendor report.

## If you cannot cite it, it is not an item

Every line in a checklist restates a provision and carries its address. An item
that cannot be cited does not appear, however sensible it is.

"Submit the early warning to the CSIRT within twenty-four hours" is the
obligation written as a check. "Set up an out-of-hours rota" is good practice
and belongs to somebody else's document. Both are reasonable. Only one is a
record of what a source establishes.

## Inference is marked, and looks different

Where the record says what something means rather than what a source
establishes, it says so on its own line, marked as inference, and drawn
differently. A reader must be able to see where the sources stop without
reading carefully.

## Standing

What binds and what a body says about how it reads what binds are two different
things, and they never appear as one row. Seventy-two hours is the Regulation.
"A reasonable degree of certainty" is how the Board reads it. A record that
flattens the second into the first is asserting an obligation nobody imposed.

## Nothing enters that has not been read

Every claim carries the address it came from and the date it was read there. A
row whose source has not been opened at its own address says so, in the row and
not in a footnote. A page that says what it has not read is worth more than a
page that looks finished.

## Say which jurisdiction

The instruments are European and the terms are the same across the Union. The
body each report is owed to is not. A page that names an authority without
naming the country is describing one country and implying all of them.

## How it is written

Definitions, not narration. State what a thing is, not why it matters. The
result of a computation is a figure and the name of an instrument, not a
sentence about what the figure means for the reader.

Plain, current English. Short sentences, active voice. No inversions, no asides
inside asides, no rhetorical questions. The register that persuades is the one
that sounds like it is reporting rather than arguing.

## What the instrument may not do

It may not tell an organization what to do. It sets out what has been
established, by whom, from when, and what the organization has not yet decided.
The difference between that and advice is the whole reason it can be taken into
a boardroom.

## A channel is checked, not read

An instrument is read once and stays read until it is amended. An address is not
like that. It resolves until an agency reorganises its site, and nothing
announces the change.

So a channel carries `Checked`, a date separate from `Read`. `Read` says when
the source that establishes the recipient was read. `Checked` says when the
address was last confirmed to resolve. A row whose `Checked` date is old is not
wrong; it is unverified, and the difference matters more for a channel than for
anything else in the record, because the channel is the one field consulted
under time pressure.

The rule comes from the Italian row. It named csirt.gov.it/segnalazione. That
address still works, and the Agency now names segnalazioni.acn.gov.it, which
serves the same page. No law changed. Had the redirect not been kept, the record
would have carried a dead address with a confident date beside it.

## A source is due to be read again

Every source declares what kind of thing it is, and the kind sets how long it
may go unread. An act is amended in public and the amendment is published; an
agency's guidance is rewritten without notice; an announcement about a bill is
overtaken by the bill. The intervals differ by an order of magnitude and the
build computes them: twenty-four months for an act or a decided case, six for a
register or for guidance, three for an announcement or for a channel.

The build warns at the interval and stops at twice it. Stopping at the interval
would halt work over something merely worth checking. Twice the interval is the
point at which the rows resting on that source can no longer be relied on, and
that is where a wall belongs rather than a note.

A row with no date is reported as undated, not assumed fresh. On the day this
was written that was true of every channel but one.

## No page is written by hand

INTRA has none, and ITER should not have had one. A record is parsed, a
template is filled, and the build emits a file per item. The pages in the
repository are output; they are committed because Pages serves them, not
because anyone edits them.

The rule exists because it was broken. The instrument page was written by hand
and then copied once per type: four byte-identical files differing in a single
line. Three bugs were fixed on that page in one sitting, and one of them had to
be carried across to the copies by hand, which is exactly the drift the record's
whole design is meant to prevent.

Which pages exist is a fact about the record, not about the directories. A type
with acts gets an instrument page; a type without one does not.

## A patch is a file, not a heredoc

Every script that edits the record or the template is written to a file and run
from there. None is piped through a shell heredoc, because a backslash does not
survive the trip: it arrives as the character it names.

This cost three bugs in one sitting. A probe's `[^\n]` became a class
containing a real newline, so the probe reported one MAR row where the page had
five. A regex's `\b` became a literal backspace byte, so a pattern that could
never match left a sentence reading "Unless The breach". Both looked like
failures of the page and were failures of the tooling around it, which is the
expensive kind: the first instinct is to go and change working code.

## Awareness is a standard, not a declaration

The organization is taken to know when it has a reasonable degree of certainty
that a breach has occurred. That is a fact about what it knew, fixed by the
standard. The record it makes of the moment is evidence of it and does not
create it; a record made late is a late record, and the term has run from the
standard. Nothing on these pages may say, or let a reader infer, that an
organization chooses when it is aware. What it chooses is the evidence at which
it will treat the standard as met, and who establishes that it has been.

**The error:** "declared awareness" read as a moment the organization declares
at will. One word did it, and a regulator would have started there.

## A reading is a field, not a sentence

What a source states goes in `Implication`. What ITER concludes from it goes in
`Reading`, and the page marks it as ITER's reading, apart from the source. A
sentence that mixes the two is split. A reading is never attributed to the
source it is drawn from, and never printed in the source's voice.

**The error:** "the default posture is notification, not silence" printed in
the same breath as what the EDPB says, so a reader could not tell which was
which.

## The data file has a schema, and the schema has a version

`SCHEMA.md` says what every key and field means, and the build writes the
version of that page into the file, with the commit the record's text came
from. A field that is not in the schema is not added to the record until the
schema says what it means. A count printed on a page comes from one function
and one definition, so no two pages can disagree.

**The error:** a homepage that said thirty jurisdictions beside a map that
said thirty-two, with the difference in the reader's lap.

