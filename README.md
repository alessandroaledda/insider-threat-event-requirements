# Insider Threat Event Requirements

ITER&trade; is a living record of what an insider event obliges in Europe:
the reporting acts, the term on each, whom it is owed to, and the point the
term runs from.

- A **type** is a kind of insider event, and each kind sets off its own
  timeline: the obligations that run from the moment the organization is
  taken to know. Two events are the same type when they trigger the same
  obligations, or when the facts those obligations require are established by
  materially different means. An event can be more than one type; the record
  then carries the obligations of each, rather than choosing one.
- An **act** is one reporting act that a regulation or directive obliges:
  what to do, whom it is owed to, the term, and the point the term runs from.
  Four Union instruments oblige the acts on this record, the General Data
  Protection Regulation (GDPR), the NIS2 Directive, the Digital Operational
  Resilience Act (DORA) and the Market Abuse Regulation (MAR), together with
  the national acts that transpose or apply them. Every act carries an
  identifier and the source it rests on, and a national act that moves a term
  or its anchor is recorded beside it.
- A **premise** is a fact about the organization that every term depends on
  and no regulation states: whether the moment of knowledge is defined, who
  establishes it, and whether the investigation before it has a limit. The
  record sets the premises out ahead of the timeline, as they stand; what to
  do about them is the organization's own decision.

Set the event, the country and the kind of organization, and the page returns
the acts that reach it. It states what the regulations oblige an organization
to do. It does not state what an organization should do with its own
processes to meet them, it does not compare one jurisdiction with another, it
does not grade an organization's readiness, and it is not advice on
compliance.

## Where the record stands

| | |
|---|---|
| Event types | 5 |
| Reporting acts | 33 |
| Union instruments | 4 |
| Jurisdictions | 32 |
| National acts read, in the Union and the EEA | 30 |
| Of them moving a term or its anchor | 12 |
| Reporting addresses recorded | 15 of 32 |
| Decided cases | 3 |
| Sources read | 70 |
| Last reading | 2026-09-05 |

## What is here

| file | what it holds |
|---|---|
| `iter.md` | the record: the types, the acts under each, the bodies a report is owed to, the national acts, and the decided cases |
| `library.md` | the sources, each with what it establishes and the date it was read |
| `iter.json` | the record as data, with its checksum beside it |
| `SCHEMA.md` | what every key and field of the data file means, and the rules the build applies |
| `RULES.md` | how the record is kept, and the error behind each rule |

The site at <https://alessandroaledda.com/iter/> is built from these files by
the site's own build, and this repository is where they are published. The
pages that used to be served here, at intrasecurity.eu, forward there.

## The rules the record is kept by

The method both records are kept by is written once, at <https://alessandroaledda.com/method/>.

- Nothing enters that has not been read. A row whose source has not been
  opened at its own address says so.
- Every source carries the interval after which it has to be read again, and
  the build refuses to run once one is overdue.
- Never invent a duration. The record supplies terms; the organization
  supplies durations. An interval this record has not read is an interval it
  does not state.
- Awareness is a standard, not a declaration. The organization is taken to
  know when it has a reasonable degree of certainty that a breach has
  occurred; the record it makes of that moment is evidence of it and does not
  create it.
- What a source states and what ITER concludes from it are two fields, and
  the page marks the second as ITER's reading.
- Where an instrument leaves a test open, the record carries the case in
  which a body applied it, and supplies no threshold of its own.

## Checking a citation

```
sha256sum iter.json
```

against `iter.json.sha256`. The file carries `version.schema`, the version of
`SCHEMA.md` it is built to, `version.record`, the date of the last reading
anywhere in the record, and `version.source_commit`, the commit its text came
from.

## The name

ITER&trade; and Insider Threat Event Requirements are unregistered trade marks
of Alessandro Aledda. The record is free to use under CC BY 4.0; the name is
not part of what is given away. See `TRADEMARK.md`.
