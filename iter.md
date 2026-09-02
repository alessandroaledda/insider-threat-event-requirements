---
title: The record
subtitle: Event types, and the reporting acts each one obliges. Every act carries what it is measured from.
reviewed: 2026-09-02
---

An **event type** is a set of obligations. Two events are the same type when
they trigger the same obligations, or when the facts those obligations require
are established by materially different means.

**An event can be more than one type.** Ransomware that also exfiltrates is an
interruption and a disclosure at once, and it obliges the union of both. The
record carries the union; it does not pick a winner.

A **condition** is a circumstance that switches obligations on. Conditions cut
across all types. One of them switches obligations *off*: a sector-specific
Union act can displace a general one.

Each act states what it is measured from. This matters: within one regime the
terms run from one another rather than all from the moment of knowledge.

Fields are `Applies`, `Term`, `From`, `Owed to`, `Establish`, `Public`,
`Source`, `Read`, `At`, `Implication`, and `Do`.

`Do` is the act in the imperative, and it is the only field a reader has to
act on. It restates what the provision requires in a form a person can carry
out. It is not advice: nothing appears there that the provision does not ask
for.

`Implication` holds the consequence the source itself states, not advice and not
a reading. Where a consequence is reasoned rather than stated, it does not go in
this field: it goes in the inference lane, marked, where a reader can see that
the sources stopped and somebody started. A `Term` is written as the instrument writes it.
Where an instrument states a term in words, the words are the term.

`At` is hours from declared awareness, reached by arithmetic on terms the
instruments state. It exists so a timeline has something to sort on. Where a
term is stated in words, or runs from something with no fixed position, the
field is absent and the act is drawn outside the ordered part. Where the
arithmetic rests on an assumption, the assumption is written in the field.

## Types

### T1 · Disclosure of personal data
What it is: Personal data leaves the organisation's control.
Added: 2026-09-02
Rows: none written.

### T2 · Disclosure of proprietary information
What it is: Non-personal information of value leaves the organisation's control. Trade secrets, plans, strategy.
Added: 2026-09-02
Rows: none written.

### T3 · Alteration or destruction of records
What it is: Integrity rather than confidentiality. What was changed is also the evidence of the change.
Added: 2026-09-02
Rows: none written.

### T4 · Interruption of an operational service
What it is: Availability. The regime with the tightest terms and the most staged reporting.
Added: 2026-09-02
Rows: none written.

### T5 · Unauthorised consultation, without extraction
What it is: An employee opens records they had no business opening. Nothing leaves the organisation. Under article 4(12) GDPR this is a breach on its own, because unauthorised access is in the definition.
Added: 2026-09-02
Updated: 2026-09-02

Why it is not T1: under the instruments read so far it triggers the same
obligations. It is a separate type on the second limb of the cutting rule. The
facts are established by different means: a disclosure is traced to where the
data went, a consultation is established by reading why it was made, and no
instrument sets a term for that.

## The moment every term runs from

### Declared awareness
Do: Declare and record the moment you are taken to know
No instrument defines it. The Board reads it as a reasonable degree of certainty
that a security incident has occurred that has led to personal data being
compromised. A short period of investigation may precede it, during which the
controller may not be regarded as aware, and that period is expected to be
short. Where it is left open and a breach did occur, the delay can be treated as
a failure to notify.

Source: [edpb-9-2022] §31, §34, §36, §40 · guidance, not law
Implication: Where the period before it is left open and a breach did occur, the delay can be treated as a failure to notify. An unbounded triage is not neutral.
Read: 2026-09-02

## Detection, where it is prescribed rather than advised

### Garante Provvedimento 192/2011
Applies: Banks, Italy
Do: Trace inquiries into customer data, keep the logs, and run the alerts
Requires: Tracing of inquiry operations on customer data; retention of those logs for not less than twenty-four months from the date the operation was recorded; alerts to detect intrusions or anomalous access to banking data capable of amounting to unlawful processing
Why the retention: So that the people concerned can learn that their data was accessed, and on what grounds
Implication: For an Italian bank the alert is not a control it chose. Its absence is a failure against a prescription, before any question of the breach itself.
Bears on: The moment of declared awareness. An alert required by this provision is what produced the first knowledge in the decided case below
Source: [garante-192-2011]
Read: 2026-09-02

Everywhere else on this record, the ability to detect is reached indirectly:
article 32 requires appropriate measures, and the Board treats the ability to
detect, address and report a breach in good time as one of them. For an Italian
bank it is stated directly, with a retention period and a requirement to alert.

## T5 · Acts under the General Data Protection Regulation

### GDPR art. 33(1)
Applies: All organisations
Do: Notify the supervisory authority of the breach
Term: 72 hours
At: 72
From: Declared awareness
Owed to: The supervisory authority. IT — Garante per la protezione dei dati personali
Establish: Which records were opened; whose they were; how many people they concern; whether risk to those people can be ruled out
Unless: The breach is unlikely to result in a risk to the rights and freedoms of natural persons
Public: No. The authority publishes its own decisions
Implication: A notification made after 72 hours is not refused. It has to arrive carrying the reasons for the delay, which puts the length of the triage on the record in the organisation's own words.
Source: [gdpr]
Read: 2026-09-02

### GDPR art. 33(4)
Applies: All organisations
Do: Complete an earlier notification with what you did not yet have
Term: Without undue further delay
From: The notification it completes
Owed to: The same authority
Establish: Nothing further. This is the provision that allows the notification to go out incomplete
Public: No
Source: [gdpr]
Read: 2026-09-02

### GDPR art. 34(1)
Applies: All organisations
Do: Tell each person whose records were opened
Term: Without undue delay
From: Declared awareness
Owed to: Each person whose records were opened
Establish: That the risk to those people is high, which turns on why the records were opened
Unless: The risk is not high
Public: In practice yes, at any scale
Implication: Deciding the risk is not high does not discharge this. Under article 34(4) the authority can require the communication afterwards, and it then goes out under order.
Source: [gdpr]
Read: 2026-09-02

### GDPR art. 33(5)
Applies: All organisations
Do: Record the breach, its effects, and what was done about it
Term: No term
From: —
Owed to: Nobody, until asked
Establish: The facts, the effects, the remedial action
Public: No
Source: [gdpr]
Read: 2026-09-02

## T5 · Acts under DORA, where the organisation is a financial entity

### DORA classification
Applies: Financial entity
Do: Classify the incident as major, or record why it is not
Term: Gate. No term of its own, and every term below runs from it
From: —
Owed to: —
Establish: Whether critical services were affected, and whether the reputational threshold is met or two or more of the other materiality thresholds are
Source: [dora-rts-class]
Read: 2026-09-02

### DORA art. 19(4)(a)
Applies: Financial entity
Do: Submit the initial notification
Term: Four hours from classification, and no later than 24 hours from awareness. Where classified as major only later, four hours from that classification
From: Classification, capped from declared awareness
At: 24 · the cap. Earlier where the incident is classified as major sooner
Owed to: The competent authority. IT — Banca d'Italia. A significant credit institution reports to the national authority, which transmits to the ECB immediately
Establish: Whether the incident is major
Public: No
Source: [dora] [dora-rts-terms] [ssm]
Read: 2026-09-02

### DORA art. 19(4)(b)
Applies: Financial entity
Do: Submit the intermediate report
Term: 72 hours, and again without undue delay once regular activities have been recovered
From: The initial notification
At: 96 · computed from the latest moment the initial notification may be made
Owed to: The same authority
Establish: Nothing further is required for the term to run. It is due whether or not the status has changed
Public: No
Source: [dora] [dora-rts-terms]
Read: 2026-09-02

### DORA art. 19(4)(c)
Applies: Financial entity
Do: Submit the final report
Term: One month
From: The intermediate report, or the latest updated one
At: 816 · computed on the same assumption
Owed to: The same authority
Establish: The root cause, and the actual impact figures in place of estimates
Public: No
Source: [dora] [dora-rts-terms]
Read: 2026-09-02

### DORA art. 19(3)
Applies: Financial entity
Do: Inform the clients whose financial interests are affected
Term: Without undue delay
From: Declared awareness
Owed to: Clients
Establish: That the incident has an impact on their financial interests
Public: Partly. It reaches everyone told
Source: [dora]
Read: 2026-09-02

### DORA RTS art. 5(3)
Applies: Financial entity
Do: Tell the authority you will miss the term, before it expires
Term: Before the term it will miss expires
From: Knowing the term will be missed
Owed to: The competent authority
Establish: The reasons for the delay
Public: No
Implication: There is no silent overrun. Missing the term and not saying so before it expires are two separate failures.
Source: [dora-rts-terms]
Read: 2026-09-02

## T5 · Acts under NIS2, where the organisation is essential or important

### NIS2 displacement
Applies: Financial entity
Effect: The incident reporting in this Directive does not apply. A sector-specific Union act covers the same ground and its requirements are at least equivalent in effect
Source: [nis2]
Read: 2026-09-02

### NIS2 art. 23(4)(a)
Applies: Essential or important entity, not displaced
Do: Submit the early warning
Term: 24 hours
At: 24
From: Declared awareness
Owed to: The CSIRT or competent authority. IT — CSIRT Italia
Establish: Whether the incident is significant; whether it is suspected of being caused by unlawful or malicious acts; whether it could have cross-border impact
Public: No
Source: [nis2]
Read: 2026-09-02

### NIS2 art. 23(4)(b)
Applies: Essential or important entity, not displaced
Do: Submit the incident notification
Term: 72 hours
At: 72
From: Declared awareness
Owed to: The same body
Establish: An initial assessment of severity and impact, and indicators of compromise where available
Public: No
Source: [nis2]
Read: 2026-09-02

### NIS2 art. 23(4)(d)
Applies: Essential or important entity, not displaced
Do: Submit the final report
Term: One month
From: The incident notification
At: 720 · computed from the incident notification at its own term
Owed to: The same body
Establish: The type of threat or root cause, the mitigation applied, and any cross-border impact
Public: No
Source: [nis2]
Read: 2026-09-02

## T5 · Acts under the Market Abuse Regulation

### MAR art. 17(1)
Applies: Listed issuer
Do: Disclose the inside information to the public
Term: As soon as possible
From: Declared awareness
Owed to: The public, and the national authority. IT — Consob
Establish: That the information is precise and price-sensitive
Public: Yes. This is the only act on the record that is public by design
Source: not read
Read: no

## Calibration

Where an instrument leaves a test open, the record carries the case in which a
body applied it. It does not supply a threshold of its own.

The Board decided eighteen cases in Guidelines 01/2021. Each reached three
outcomes: whether to document, whether to tell the authority, whether to tell
the people concerned. Documentation was required in all eighteen, which is the
Article 33(5) obligation behaving as written.

Type is assigned by this record, not by the Board.

| # | Case | Type | Document | Authority | People |
|---|---|---|---|---|---|
| 1 | Ransomware, backup held, no exfiltration | T4 | yes | no | no |
| 2 | Ransomware, no proper backup | T4 | yes | yes | no |
| 3 | Ransomware in a hospital, backup held | T4 | yes | yes | yes |
| 4 | Ransomware, no backup, with exfiltration | T4 + T1 | yes | yes | yes |
| 5 | Exfiltration of job application data | T1 | yes | yes | yes |
| 6 | Exfiltration of hashed passwords | T1 | yes | no | no |
| 7 | Credential stuffing on a banking website | T1 | yes | yes | yes |
| 8 | **Exfiltration of business data by an employee** | T1 | yes | yes | **no** |
| 9 | Accidental transmission to a trusted third party | T1 | yes | no | no |
| 10 | Stolen device, data encrypted | T1 | yes | no | no |
| 11 | Stolen device, data not encrypted | T1 | yes | yes | yes |
| 12 | Stolen paper files, sensitive data | T1 | yes | yes | yes |
| 13 | Postal mail mistake | T1 | yes | no | no |
| 14 | Highly confidential data sent by mail in error | T1 | yes | yes | yes |
| 15 | Personal data sent by mail in error | T1 | yes | no | no |
| 16 | Postal mail mistake | T1 | yes | yes | no |
| 17 | Identity theft | T1 | yes | yes | yes |
| 18 | Email exfiltration | T1 | yes | yes | yes |

Source: [edpb-1-2021] · Read: 2026-09-02

### What the cases did to the taxonomy

**Types are not exclusive.** Case 4 is ransomware without backup and with
exfiltration. It is an interruption and a disclosure at once, and it obliges the
union of both. The cutting rule assumed one type per event. It has to allow an
event to carry more than one, and the instrument has to show the union rather
than pick a winner.

**T5 has no decided case.** Not one of the eighteen is a consultation without
extraction. Case 8 is the nearest and the data still leaves: the employee copies
it and uses it later. The type this record is built around is calibrated by
borrowing from its neighbour, and every row that does so says it.

That is a gap to fill rather than a flaw to hide. National authorities decide
these. An employee looking up an account they had no business opening is among
the most common matters an Italian supervisory authority handles, and those
decisions are published.

### T5, decided: an employee consulting customer records
Facts: An employee made some 6,637 inquiries into the accounts of about 3,572 customers outside their own portfolio, over roughly twenty-six months. The records were consulted. Nothing is recorded as having been copied out.
Alert: The bank first learned of an anomalous access on 9 October 2023, through an alert operated under Provvedimento 192/2011.
Notified: The definitive article 33 notification reached the Authority on 17 July 2024.
Held on risk: The controller assessed the breach as not likely to present a high risk and did not communicate it. The Authority disagreed.
Outcome: Communication to the people concerned ordered under articles 34(4) and 58(2)(e), within twenty days, with the article 34(2) information. A documented account of the steps taken within thirty days. No pecuniary sanction in the operative part.
Source: [garante-659-2024]
Read: 2026-09-02

This is the case the eighteen worked examples did not contain, and it settles
for T5 what case 8 could only suggest for T1. Two things carry.

**The controller's own view of the risk does not close the question.** Article
34(4) lets the authority require the communication after the fact. An
organisation that decides the risk is not high has not disposed of the
obligation; it has taken a position that may be reversed, and the communication
then goes out under order.

**The distance between the alert and the notification is the whole subject of
this record.** The alert fired on 9 October 2023. The definitive notification is
dated 17 July 2024. The decision does not characterise that interval, and this
record does not either: what it shows is that the interval exists, that it is
measured in months rather than hours, and that nothing in the instruments fixes
where inside it awareness fell.

### Borrowed calibration: risk, on an employee taking client data
Facts: An employee copies business data during his notice period and uses the contact data months later to approach the clients for his own business. No special categories. Low to medium volume. The database left intact.
Held: The controller is not in a position to consider the risk to the data subjects low, because it has no reassurance about the intentions of the employee, and more serious abuse is not ruled out.
Outcome: Documentation required. Notification to the authority required. Communication to the people concerned not required.
Moves the outcome: Special categories, large volume, or evidence of onward sale.
Applies to T5: By analogy only. The case is a T1. What carries across is the reasoning on intent, not the outcome.
Source: [edpb-1-2021] §72, §74, §77
Read: 2026-09-02

## Open

- MAR art. 17 is cited and unread.
- The channel each authority requires — portal, form, identifiers — is published
  by the authorities rather than by the instruments. It is a different kind of
  source and needs its own section and its own rule about how long it stays true.
- Only Italy is worked. The terms are the same across the Union; the recipients
  are not.
- T1 to T4 have no rows, though fourteen of the eighteen decided cases are T1.
- The cutting rule assumes one type per event. Case 4 shows an event can be two.
- One decided case now exists for T5, from Italy. No other jurisdiction has one
  on this record.
- Detection is prescribed for Italian banks and reached only indirectly
  everywhere else. Whether other jurisdictions prescribe it is unread.
