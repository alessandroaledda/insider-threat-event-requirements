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
`Source`, `Read`. A `Term` is written as the instrument writes it. Where an
instrument states a term in words, the words are the term.

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
No instrument defines it. The Board reads it as a reasonable degree of certainty
that a security incident has occurred that has led to personal data being
compromised. A short period of investigation may precede it, during which the
controller may not be regarded as aware, and that period is expected to be
short. Where it is left open and a breach did occur, the delay can be treated as
a failure to notify.

Source: [edpb-9-2022] §31, §34, §36, §40 · guidance, not law
Read: 2026-09-02

## T5 · Acts under the General Data Protection Regulation

### GDPR art. 33(1)
Applies: All organisations
Term: 72 hours
From: Declared awareness
Owed to: The supervisory authority. IT — Garante per la protezione dei dati personali
Establish: Which records were opened; whose they were; how many people they concern; whether risk to those people can be ruled out
Unless: The breach is unlikely to result in a risk to the rights and freedoms of natural persons
Public: No. The authority publishes its own decisions
Source: [gdpr]
Read: 2026-09-02

### GDPR art. 33(4)
Applies: All organisations
Term: Without undue further delay
From: The notification it completes
Owed to: The same authority
Establish: Nothing further. This is the provision that allows the notification to go out incomplete
Public: No
Source: [gdpr]
Read: 2026-09-02

### GDPR art. 34(1)
Applies: All organisations
Term: Without undue delay
From: Declared awareness
Owed to: Each person whose records were opened
Establish: That the risk to those people is high, which turns on why the records were opened
Unless: The risk is not high
Public: In practice yes, at any scale
Source: [gdpr]
Read: 2026-09-02

### GDPR art. 33(5)
Applies: All organisations
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
Term: Gate. No term of its own, and every term below runs from it
From: —
Owed to: —
Establish: Whether critical services were affected, and whether the reputational threshold is met or two or more of the other materiality thresholds are
Source: [dora-rts-class]
Read: 2026-09-02

### DORA art. 19(4)(a)
Applies: Financial entity
Term: Four hours from classification, and no later than 24 hours from awareness. Where classified as major only later, four hours from that classification
From: Classification, capped from declared awareness
Owed to: The competent authority. IT — Banca d'Italia. A significant credit institution reports to the national authority, which transmits to the ECB immediately
Establish: Whether the incident is major
Public: No
Source: [dora] [dora-rts-terms] [ssm]
Read: 2026-09-02

### DORA art. 19(4)(b)
Applies: Financial entity
Term: 72 hours, and again without undue delay once regular activities have been recovered
From: The initial notification
Owed to: The same authority
Establish: Nothing further is required for the term to run. It is due whether or not the status has changed
Public: No
Source: [dora] [dora-rts-terms]
Read: 2026-09-02

### DORA art. 19(4)(c)
Applies: Financial entity
Term: One month
From: The intermediate report, or the latest updated one
Owed to: The same authority
Establish: The root cause, and the actual impact figures in place of estimates
Public: No
Source: [dora] [dora-rts-terms]
Read: 2026-09-02

### DORA art. 19(3)
Applies: Financial entity
Term: Without undue delay
From: Declared awareness
Owed to: Clients
Establish: That the incident has an impact on their financial interests
Public: Partly. It reaches everyone told
Source: [dora]
Read: 2026-09-02

### DORA RTS art. 5(3)
Applies: Financial entity
Term: Before the term it will miss expires
From: Knowing the term will be missed
Owed to: The competent authority
Establish: The reasons for the delay
Public: No
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
Term: 24 hours
From: Declared awareness
Owed to: The CSIRT or competent authority. IT — CSIRT Italia
Establish: Whether the incident is significant; whether it is suspected of being caused by unlawful or malicious acts; whether it could have cross-border impact
Public: No
Source: [nis2]
Read: 2026-09-02

### NIS2 art. 23(4)(b)
Applies: Essential or important entity, not displaced
Term: 72 hours
From: Declared awareness
Owed to: The same body
Establish: An initial assessment of severity and impact, and indicators of compromise where available
Public: No
Source: [nis2]
Read: 2026-09-02

### NIS2 art. 23(4)(d)
Applies: Essential or important entity, not displaced
Term: One month
From: The incident notification
Owed to: The same body
Establish: The type of threat or root cause, the mitigation applied, and any cross-border impact
Public: No
Source: [nis2]
Read: 2026-09-02

## T5 · Acts under the Market Abuse Regulation

### MAR art. 17(1)
Applies: Listed issuer
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
- No decided case exists for T5. Italian supervisory decisions on employees
  consulting records they had no business opening are the place to look.
