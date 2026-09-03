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
`Source`, `Read`, `At`, `Implication`, `Do`, and `Anchor`.

`Owed to` holds a **role** where the recipient is an authority, and the
authorities table resolves it for the country selected. Where the recipient is
not an authority — the people concerned, the clients, the organisation's own
register — it is written out, because it does not vary by country.

`Anchor` is for an act whose term is not stated in hours. It says what the
act attaches to on the sequence, so that a reader can see when it is
reasonable to complete it without an hour being invented for it.

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

## Authorities

An act names a **role**. This table gives the body that holds the role in each
country. Where the table has no entry, the act says so rather than naming a
plausible body.

Only one role is filled. The Board publishes the list of its members, so the
data protection authority is known for thirty countries. The other three are
not published as a list that could be read: DORA, NIS2 and MAR do not name a
body, they name a mechanism by which a Member State designates one, and the
result has to be looked up country by country.

Fields are `Role`, `Country`, `Name`, `URL`, `Source`, `Read`.

### Supervisory authority
Role: dpa
Bears on: GDPR art. 33(1), and every communication ordered under art. 34(4)
Source: [edpb-members]
Read: 2026-09-03

### dpa · Austria
Role: dpa
Country: AT
Name: Österreichische Datenschutzbehörde
URL: http://www.dsb.gv.at/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Belgium
Role: dpa
Country: BE
Name: Autorité de la protection des données — Gegevensbeschermingsautoriteit
URL: https://www.autoriteprotectiondonnees.be
Source: [edpb-members]
Read: 2026-09-03

### dpa · Bulgaria
Role: dpa
Country: BG
Name: Commission for Personal Data Protection
URL: https://www.cpdp.bg/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Croatia
Role: dpa
Country: HR
Name: Agencija za zaštitu osobnih podataka
URL: http://www.azop.hr/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Cyprus
Role: dpa
Country: CY
Name: Office of the Commissioner for Personal Data Protection
URL: http://www.dataprotection.gov.cy/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Czechia
Role: dpa
Country: CZ
Name: Office for Personal Data Protection
URL: https://uoou.gov.cz/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Denmark
Role: dpa
Country: DK
Name: Datatilsynet
URL: http://www.datatilsynet.dk/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Estonia
Role: dpa
Country: EE
Name: Andmekaitse Inspektsioon
URL: http://www.aki.ee/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Finland
Role: dpa
Country: FI
Name: Office of the Data Protection Ombudsman
URL: http://www.tietosuoja.fi/en/
Source: [edpb-members]
Read: 2026-09-03

### dpa · France
Role: dpa
Country: FR
Name: Commission Nationale de l'Informatique et des Libertés
URL: http://www.cnil.fr/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Germany
Role: dpa
Country: DE
Name: Die Bundesbeauftragte für den Datenschutz und die Informationsfreiheit
URL: http://www.bfdi.bund.de/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Greece
Role: dpa
Country: GR
Name: Hellenic Data Protection Authority
URL: http://www.dpa.gr/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Hungary
Role: dpa
Country: HU
Name: Hungarian National Authority for Data Protection and Freedom of Information
URL: http://www.naih.hu/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Iceland
Role: dpa
Country: IS
Name: Persónuvernd
URL: https://www.personuvernd.is
Source: [edpb-members]
Read: 2026-09-03

### dpa · Ireland
Role: dpa
Country: IE
Name: Data Protection Commission
URL: http://www.dataprotection.ie/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Italy
Role: dpa
Country: IT
Name: Garante per la protezione dei dati personali
URL: http://www.garanteprivacy.it/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Latvia
Role: dpa
Country: LV
Name: Data State Inspectorate
URL: https://www.dvi.gov.lv/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Liechtenstein
Role: dpa
Country: LI
Name: Data Protection Authority, Principality of Liechtenstein
URL: https://www.datenschutzstelle.li
Source: [edpb-members]
Read: 2026-09-03

### dpa · Lithuania
Role: dpa
Country: LT
Name: State Data Protection Inspectorate
URL: https://vdai.lrv.lt/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Luxembourg
Role: dpa
Country: LU
Name: Commission Nationale pour la Protection des Données
URL: http://www.cnpd.lu/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Malta
Role: dpa
Country: MT
Name: Office of the Information and Data Protection Commissioner
URL: http://www.idpc.org.mt/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Netherlands
Role: dpa
Country: NL
Name: Autoriteit Persoonsgegevens
URL: https://autoriteitpersoonsgegevens.nl/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Norway
Role: dpa
Country: NO
Name: Datatilsynet
URL: https://www.datatilsynet.no
Source: [edpb-members]
Read: 2026-09-03

### dpa · Poland
Role: dpa
Country: PL
Name: Urząd Ochrony Danych Osobowych
URL: https://uodo.gov.pl/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Portugal
Role: dpa
Country: PT
Name: Comissão Nacional de Proteção de Dados
URL: http://www.cnpd.pt/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Romania
Role: dpa
Country: RO
Name: National Supervisory Authority for Personal Data Processing
URL: http://www.dataprotection.ro/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Slovakia
Role: dpa
Country: SK
Name: Úrad na ochranu osobných údajov Slovenskej republiky
URL: http://www.dataprotection.gov.sk/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Slovenia
Role: dpa
Country: SI
Name: Information Commissioner of the Republic of Slovenia
URL: https://www.ip-rs.si/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Spain
Role: dpa
Country: ES
Name: Agencia Española de Protección de Datos
URL: https://www.aepd.es/
Source: [edpb-members]
Read: 2026-09-03

### dpa · Sweden
Role: dpa
Country: SE
Name: Integritetsskyddsmyndigheten
URL: https://www.imy.se/
Source: [edpb-members]
Read: 2026-09-03

### Financial competent authority
Role: financial
Bears on: DORA art. 19(4), where the organisation is a financial entity
Scope: The bodies below are the designation for **credit institutions**, under article 4 of Directive 2013/36/EU. Article 46 designates by sector: a payment institution, an investment firm and an insurer are designated under other acts and resolve to other bodies, which this record has not read.
Note: A significant credit institution reports to the national authority below, which transmits the report to the ECB immediately. Supervision moves under the Single Supervisory Mechanism; the report does not.
Source: [eba-competent-authorities] · [dora]
Read: 2026-09-03

### financial · Austria
Role: financial
Country: AT
Name: Finanzmarktaufsicht (FMA)
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Belgium
Role: financial
Country: BE
Name: Nationale Bank van België / Banque Nationale de Belgique
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Bulgaria
Role: financial
Country: BG
Name: Bulgarian National Bank
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Croatia
Role: financial
Country: HR
Name: Hrvatska narodna banka
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Cyprus
Role: financial
Country: CY
Name: Central Bank of Cyprus
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Czechia
Role: financial
Country: CZ
Name: Česká národní banka
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Denmark
Role: financial
Country: DK
Name: Finanstilsynet
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Estonia
Role: financial
Country: EE
Name: Finantsinspektsioon
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Finland
Role: financial
Country: FI
Name: Finanssivalvonta
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · France
Role: financial
Country: FR
Name: Autorité de contrôle prudentiel et de résolution
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Germany
Role: financial
Country: DE
Name: BaFin, with the Deutsche Bundesbank
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Greece
Role: financial
Country: GR
Name: Bank of Greece
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Hungary
Role: financial
Country: HU
Name: Magyar Nemzeti Bank
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Iceland
Role: financial
Country: IS
Name: Central Bank of Iceland
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Ireland
Role: financial
Country: IE
Name: Central Bank of Ireland
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Italy
Role: financial
Country: IT
Name: Banca d'Italia
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Latvia
Role: financial
Country: LV
Name: Latvijas Banka
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Liechtenstein
Role: financial
Country: LI
Name: Finanzmarktaufsicht Liechtenstein
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Lithuania
Role: financial
Country: LT
Name: Lietuvos bankas
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Luxembourg
Role: financial
Country: LU
Name: Commission de Surveillance du Secteur Financier
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Malta
Role: financial
Country: MT
Name: Malta Financial Services Authority
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Netherlands
Role: financial
Country: NL
Name: De Nederlandsche Bank
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Norway
Role: financial
Country: NO
Name: Finanstilsynet
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Poland
Role: financial
Country: PL
Name: Komisja Nadzoru Finansowego
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Portugal
Role: financial
Country: PT
Name: Banco de Portugal
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Romania
Role: financial
Country: RO
Name: Banca Naţională a României
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Slovakia
Role: financial
Country: SK
Name: Národná banka Slovenska
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Slovenia
Role: financial
Country: SI
Name: Banka Slovenije
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Spain
Role: financial
Country: ES
Name: Banco de España
Source: [eba-competent-authorities]
Read: 2026-09-03

### financial · Sweden
Role: financial
Country: SE
Name: Finansinspektionen
Source: [eba-competent-authorities]
Read: 2026-09-03

### CSIRT or competent authority
Role: csirt
Bears on: NIS2 art. 23(4), where the organisation is an essential or important entity not displaced
Note: The Directive leaves the designation to each Member State, so there is no single text to read. Tried on 3 September 2026 and not reached: the CSIRTs Network site, whose members are drawn on a map fed by a script rather than listed, and which renders no team names into the page; its front-end bundle, which carries the shape of the data and not the data; and two ENISA inventory addresses, both gone. What would settle it is each Member State's own notification of its CSIRT and single point of contact, which is made to the Commission and published nationally.
Source: [acn-nis-faq]
Read: 2026-09-03

### csirt · Italy
Role: csirt
Country: IT
Name: CSIRT Italia, within the Agenzia per la Cybersicurezza Nazionale
URL: https://www.csirt.gov.it/segnalazione
Channel: A form on the Agency's reporting portal. Named here because it is the one channel this record has read; the others are not.
Source: [acn-nis-faq]
Read: 2026-09-03

### csirt · Germany
Role: csirt
Country: DE
Name: Bundesamt für Sicherheit in der Informationstechnik, which is the competent authority, the CSIRT and the single point of contact at once
URL: https://www.bsi.bund.de/DE/Themen/Regulierte-Wirtschaft/NIS-2-regulierte-Unternehmen/NIS-2-Infopakete/NIS-2-Meldepflicht/NIS-2-Meldepflicht.html
Channel: A central reporting and registration platform operated by the BSI.
Source: [bsi-nis2-meldepflicht]
Read: 2026-09-03

### csirt · France
Role: csirt
Country: FR
Name: The competent national authority, which is the Agence nationale de la sécurité des systèmes d'information
URL: https://aide.monespacenis2.cyber.gouv.fr/fr/category/declaration-dincident-6bpkdp/
Channel: MonEspaceNIS2, the Agency's own space for regulated entities.
Source: [anssi-nis2-declaration]
Read: 2026-09-03

### csirt · Netherlands
Role: csirt
Country: NL
Name: The sectoral CSIRT and the supervisory authority, both reached by one report
URL: https://www.ncsc.nl/cyberbeveiligingswet-nis2/meldplicht
Channel: MijnNCSC, the central reporting point. One report reaches the sectoral CSIRT and the supervisory authority at once.
Source: [ncsc-nl-meldplicht]
Read: 2026-09-03

### csirt · Austria
Role: csirt
Country: AT
Name: The NIS-Behörde, within the Bundesministerium für Inneres
URL: https://www.nis.gv.at/fragen-und-antworten/nis-2-richtlinie/allgemeine-informationen-zu-nis-2.html
Channel: Not read. The page names the authority and not the channel.
Source: [nisg-at-faq]
Read: 2026-09-03

### csirt · Ireland
Role: csirt
Country: IE
Name: The National Cyber Security Centre, Ireland's national cyber security authority and national CSIRT
URL: https://www.ncsc.gov.ie/nis2/FAQ/
Channel: Not open. The reporting portal is not available while the legislation is not enacted.
Source: [ncsc-ie-nis2-faq]
Read: 2026-09-03

### csirt · Portugal
Role: csirt
Country: PT
Name: The competent cybersecurity authority, which article 2 defines as the Centro Nacional de Cibersegurança or, where one applies, the sectoral national authority under article 15(2)(a)
URL: https://diariodarepublica.pt/dr/detalhe/decreto-lei/125-2025-962603401
Channel: Not read here. Article 41(4) leaves the format and procedure to a technical instruction of the CNCS.
Source: [pt-dl-125-2025]
Read: 2026-09-03

### csirt · Belgium
Role: csirt
Country: BE
Name: The national CSIRT, which article 1, 46° defines functionally as the national computer security incident response centre without naming the body
URL: https://www.ejustice.just.fgov.be/eli/loi/2024/04/26/2024202344/justel
Channel: Article 34 §1 leaves the arrangements to a protocol between the national CSIRT and the NCCN. The act does not set them out.
Source: [be-loi-26-04-2024]
Read: 2026-09-03

### csirt · Czechia
Role: csirt
Country: CZ
Name: Národní úřad pro kybernetickou a informační bezpečnost
URL: https://portal.nukib.gov.cz/
Channel: Portál NÚKIB. Where the portal is unavailable the guidance allows e-mail or a datová schránka.
Source: [nukib-hlaseni-incidentu]
Read: 2026-09-03

### csirt · Denmark
Role: csirt
Country: DK
Name: The relevant authority and the CSIRT, both of them, under § 12(1)
URL: https://www.retsinformation.dk/eli/lta/2025/434
Channel: Not set by the act.
Source: [dk-lov-434-2025]
Read: 2026-09-03

### csirt · Sweden
Role: csirt
Country: SE
Name: The authority the Government designates, which the act itself does not name
URL: https://www.riksdagen.se/sv/dokument-och-lagar/dokument/svensk-forfattningssamling/cybersakerhetslag-20251506_sfs-2025-1506/
Channel: Not set by the act.
Source: [se-cybersakerhetslag-2025]
Read: 2026-09-03

### csirt · Finland
Role: csirt
Country: FI
Name: The supervising authority, which is sectoral under § 43. Traficom's Kyberturvallisuuskeskus is the single point of contact under § 18.
URL: https://www.finlex.fi/fi/lainsaadanto/2025/124
Channel: Not set by the act.
Source: [fi-kyberturvallisuuslaki-124-2025]
Read: 2026-09-03

### csirt · Romania
Role: csirt
Country: RO
Name: The national cyber security incident response team
URL: https://legislatie.just.ro/Public/DetaliiDocumentAfis/293121
Channel: Not set by the ordinance.
Source: [ro-oug-155-2024]
Read: 2026-09-03

### csirt · Croatia
Role: csirt
Country: HR
Name: The competent CSIRT, under article 37 of the Act
URL: https://narodne-novine.nn.hr/clanci/sluzbeni/2024_02_14_254.html
Channel: The Act does not set one. The national platform PiXi is named outside the sources read here.
Source: [hr-zks-uredba]
Read: 2026-09-03

### csirt · Latvia
Role: csirt
Country: LV
Name: The competent cyber incident prevention institution, which article 34 names by function
URL: https://likumi.lv/ta/id/353390-nacionalas-kiberdrosibas-likums
Channel: Electronically, under article 34(2) and (3). The Cabinet of Ministers sets the form.
Source: [lv-nacionalas-kiberdrosibas-likums]
Read: 2026-09-03

### csirt · Estonia
Role: csirt
Country: EE
Name: Riigi Infosüsteemi Amet, the State Information System Authority
URL: https://www.riigiteataja.ee/akt/K%C3%BCTS
Channel: Not set by the act.
Source: [ee-kuberturvalisuse-seadus]
Read: 2026-09-03

### csirt · Slovakia
Role: csirt
Country: SK
Name: The Národný bezpečnostný úrad, through the single cybersecurity information system
URL: https://static.slov-lex.sk/static/SK/ZZ/2024/366/20250101.html
Channel: The jednotný informačný systém kybernetickej bezpečnosti, named in § 24(3) itself.
Source: [sk-zakon-366-2024]
Read: 2026-09-03

### csirt · Slovenia
Role: csirt
Country: SI
Name: The competent CSIRT group, under article 30(1)
URL: https://www.uradni-list.si/glasilo-uradni-list-rs/vsebina/2025-01-1571
Channel: Not set by the act.
Source: [si-zinfv-1]
Read: 2026-09-03

### csirt · Luxembourg
Role: csirt
Country: LU
Name: The Institut Luxembourgeois de Régulation, which organises the regime and receives the notifications
URL: https://gouvernement.lu/fr/actualites/toutes_actualites/communiques/2026/07-juillet/06-cybersecurite-nis-2.html
Channel: Not established. The government's communiqué names a self-registration form and does not name the channel for incident notifications.
Source: [lu-communique-nis2]
Read: 2026-09-03

### csirt · Malta
Role: csirt
Country: MT
Name: CSIRTMalta, in the order as drafted
URL: https://maltacip.gov.mt/wp-content/uploads/2024/09/Measures-for-A-High-Common-Level-of-Cybersecurity-Across-The-European-Union-Malta-Order-2024.pdf
Channel: Not set by the order.
Source: [mt-cybersecurity-order-draft]
Read: 2026-09-03

### csirt · Norway
Role: csirt
Country: NO
Name: The sectoral supervisory authority, with a copy to the National Contact Point, under section 17 of the regulation
URL: https://lovdata.no/dokument/SF/forskrift/2025-06-20-1131/KAPITTEL_2
Channel: Not set by the regulation.
Source: [no-digitalsikkerhetsforskriften]
Read: 2026-09-03

### csirt · Cyprus
Role: csirt
Country: CY
Name: The relevant competent authority or the National CSIRT, as the guide puts it
URL: https://dsa.cy/images/pdf-upload/nis2-guide.pdf
Channel: Not set out in the document read.
Source: [cy-dsa-nis2-guide]
Read: 2026-09-03

### csirt · Iceland
Role: csirt
Country: IS
Name: The cybersecurity team, netöryggissveit, operated by the telecommunications authority
URL: https://www.althingi.is/lagas/nuna/2019078.html
Channel: Not set by the act. A reporting portal exists outside the sources read here.
Source: [is-log-78-2019]
Read: 2026-09-03

### csirt · Liechtenstein
Role: csirt
Country: LI
Name: The National Cyber Security Unit
URL: https://www.regierung.li/files/attachments/2025111000-csg-en.pdf
Channel: Not set by the act.
Source: [li-csg]
Read: 2026-09-03

### csirt · Hungary
Role: csirt
Country: HU
Name: The national cybersecurity incident handling centre, the Központ, with the SZTFH as the supervisory authority
URL: https://njt.jog.gov.hu/jogszabaly/2024-418-20-22
Channel: Not set out in the sources read.
Source: [hu-418-2024-korm-rendelet]
Read: 2026-09-03

### Market authority
Role: market
Bears on: MAR art. 17(1), where the organisation is a listed issuer
Note: The body is recorded for thirty countries. The article it reports under, MAR art. 17, has still not been opened for this record, and the act says so.
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Belgium
Role: market
Country: BE
Name: Autoriteit voor Financiële Diensten en Markten / Autorité des services et marchés financiers (FSMA)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Bulgaria
Role: market
Country: BG
Name: Комисия за финансов надзор (FSC)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Czechia
Role: market
Country: CZ
Name: Česká národní banka (CNB)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Denmark
Role: market
Country: DK
Name: Finanstilsynet
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Germany
Role: market
Country: DE
Name: Bundesanstalt für Finanzdienstleistungsaufsicht (BaFIN)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Estonia
Role: market
Country: EE
Name: Finantsinspektsioon (FSA)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Ireland
Role: market
Country: IE
Name: Central Bank of Ireland
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Greece
Role: market
Country: GR
Name: Επιτροπή Κεφαλαιαγοράς (HCMC)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Spain
Role: market
Country: ES
Name: Comisión Nacional del Mercado de Valores (CNMV)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · France
Role: market
Country: FR
Name: Autorité des Marchés Financiers (AMF)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Croatia
Role: market
Country: HR
Name: Hrvatska agencija za nadzor financijskih usluga (HANFA)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Italy
Role: market
Country: IT
Name: Commissione Nazionale per le Società e la Borsa (CONSOB)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Cyprus
Role: market
Country: CY
Name: Επιτροπή Κεφαλαιαγοράς (CySEC)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Latvia
Role: market
Country: LV
Name: Latvijas Banka
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Lithuania
Role: market
Country: LT
Name: Lietuvos bankas (LB)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Luxembourg
Role: market
Country: LU
Name: Commission de Surveillance du Secteur Financier (CSSF)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Hungary
Role: market
Country: HU
Name: Magyar Nemzeti Bank (MNB)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Malta
Role: market
Country: MT
Name: Awtorita' ghas-Servizzi Finanzjari ta' Malta (MFSA)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Netherlands
Role: market
Country: NL
Name: Autoriteit Financiële Markten (AFM)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Austria
Role: market
Country: AT
Name: Österreichische Finanzmarktaufsicht (FMA)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Poland
Role: market
Country: PL
Name: Komisja Nadzoru Finansowego (KNF)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Portugal
Role: market
Country: PT
Name: Comissão do Mercado de Valores Mobiliários (CMVM)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Romania
Role: market
Country: RO
Name: Autoritatea de Supraveghere Financiara (ASF)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Slovenia
Role: market
Country: SI
Name: Agencija za trg Vrednostnih Papirjev (A-TVP)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Slovakia
Role: market
Country: SK
Name: Národná Banka Slovenska (NBS)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Finland
Role: market
Country: FI
Name: Finanssivalvonta (FIN-FSA)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Sweden
Role: market
Country: SE
Name: Finansinspektionen (FI)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Iceland
Role: market
Country: IS
Name: Central Bank of Iceland
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Liechtenstein
Role: market
Country: LI
Name: Finanzmarktaufsicht Liechtenstein (FMA)
Source: [esma-mar-nca]
Read: 2026-09-03

### market · Norway
Role: market
Country: NO
Name: Finanstilsynet
Source: [esma-mar-nca]
Read: 2026-09-03

## Transpositions

NIS2 is a Directive. The text that binds is the national act, and a Member State
may go further than the Directive does. An entry here records the act, when it
took effect, and the only thing that changes an ITER row: whether it moves a
term, or moves the point a term runs from.

Where a country has no entry, no national act has been read for it, and the
rows for that country carry the Directive's own terms.

Fields are `Country`, `Act`, `In force`, `Divergence`, `Source`, `Read`.

### NIS2 · Italy
Country: IT
Act: Decreto legislativo 4 settembre 2024, n. 138
In force: 16 October 2024
Recipient: CSIRT Italia, under article 25 of the decree
Divergence: The national authority describes the complete notification as due within 72 hours **of the pre-notification**, where the Directive puts it within 72 hours of becoming aware. The pre-notification is itself due within 24 hours of becoming aware. Read that way the complete notification falls at 96 hours from awareness rather than at 72, and an organisation working from the Directive alone would hold the wrong date.
Moves: yes
Standing: This is how the Agency describes the obligation, not the wording of the decree. Article 25 has not been read.
Source: [acn-nis-faq]
Read: 2026-09-03

### NIS2 · Germany
Country: DE
Act: Gesetz über das Bundesamt für Sicherheit in der Informationstechnik, in the 2025 version (BSIG 2025)
In force: 2025. The date has not been read.
Recipient: Bundesamt für Sicherheit in der Informationstechnik, which is the competent authority, the CSIRT and the single point of contact at once
Divergence: None found on the anchor. The early initial report is due within 24 hours **nach Kenntniserlangung**, and the detailed report within 72 hours on the same footing, so both run from becoming aware as the Directive has them. This is the opposite of the Italian reading, where the 72 hours run from the pre-notification.
Moves: no
Standing: This is the BSI's own account of the duty. The BSIG article has not been read.
Source: [bsi-nis2-meldepflicht]
Read: 2026-09-03

### NIS2 · France
Country: FR
Act: Not read. The French transposing act has not been opened for this record.
In force: not read
Recipient: The competent national authority, which is the Agence nationale de la sécurité des systèmes d'information
Divergence: None found on the first stage. The declaration is due *«sans retard injustifié ou dans les 24 heures après avoir eu connaissance de l'incident important»*, which is the Directive's own anchor. The later stages are not stated on the page read, so nothing is recorded about them.
Moves: no
Standing: This is the Agency's operational guidance for regulated entities, not the transposing act. Whether the recipient is the Agency as competent authority or a separately designated CSIRT is not settled here.
Source: [anssi-nis2-declaration]
Read: 2026-09-03

### NIS2 · Netherlands
Country: NL
Act: Cyberbeveiligingswet
In force: 15 August 2026
Recipient: The sectoral CSIRT and the supervisory authority, both reached by one report
Divergence: None found. The three stages are the Directive's own — *«Vroegtijdige waarschuwing binnen 24 uur»*, *«Melding binnen 72 uur»*, *«Eindverslag binnen 1 maand na je melding»* — and the page states the anchor plainly: *«De termijnen tellen vanaf het moment dat je kennis krijgt van het incident»*.
Moves: no
Standing: This is the NCSC's guidance on the act, not the act. What it adds to the Directive is the channel and the fact that one report discharges the duty to two bodies.
Source: [ncsc-nl-meldplicht]
Read: 2026-09-03

### NIS2 · Spain
Country: ES
Act: Not complete. Read on the date below, the Spanish CSIRT's own guidance still describes the recipients as something the transposition will settle.
In force: not settled
Recipient: not recorded, see Divergence
Divergence: None found in the terms. The FAQ gives the Directive's three stages — *«una alerta temprana en las primeras 24 h»*, *«antes de 72 h ... una notificación del incidente»*, *«informe final, a más tardar un mes después de presentar la notificación del incidente»* — all *«desde el conocimiento del mismo»*. The divergence is elsewhere: the page does not say who receives them. *«Tanto los CSIRT de referencia y las autoridades competentes como el punto de contacto único se conocerán con la trasposición de la norma a la legislación española.»*
Moves: unsettled
Standing: An organisation in Spain therefore holds the terms and not the recipient. This record leaves the Spanish recipient unwritten rather than naming a body the source does not name.
Source: [incibe-faq-nis2]
Read: 2026-09-03

### NIS2 · Austria
Country: AT
Act: Netz- und Informationssystemsicherheitsgesetz 2024, NISG 2024, named on the authority's own page without a date of entry into force.
In force: not stated on the page read
Recipient: The NIS-Behörde, within the Bundesministerium für Inneres
Divergence: None found. The three stages are the Directive's: a *«24-Stunden-Zeitfenster»* for the early warning, *«binnen 72 Stunden»* for the assessment, and the final report *«ein Monat nach der Meldung»*.
Moves: no
Standing: The page names the NIS-Behörde as the authority and does not name a CSIRT, so this record does not name one either. Whether a designated team receives the report alongside the authority is not settled here.
Source: [nisg-at-faq]
Read: 2026-09-03

### NIS2 · Ireland
Country: IE
Act: None. The National Cyber Security Bill has not been enacted.
In force: not in force
Recipient: The National Cyber Security Centre, Ireland's national cyber security authority and national CSIRT
Divergence: The whole of it. On the date below the authority's own page states that *«the NIS2 directive has not yet been transposed into Irish law»* and that *«the transposition deadline of 17th October 2024 was not met»*. It adds that *«there is currently no requirement for entities to register under NIS2, until such time as the legislation is enacted»*, and that guidance on reporting will follow.
Moves: none
Standing: The recipient is named because the page names it: the Centre holds the lead competent authority role and is the national CSIRT. The duty to report to it under NIS2 does not yet arise in Irish law. An ITER row that rests on NIS2 alone has, in Ireland, no national instrument under it.
Source: [ncsc-ie-nis2-faq]
Read: 2026-09-03

### NIS2 · Portugal
Country: PT
Act: Decreto-Lei n.º 125/2025, de 4 de dezembro
In force: Article 11 sets it at 120 days after publication. Published 4 December 2025, that falls on 3 April 2026. The date is arithmetic on the act's own wording, not a date the act prints.
Recipient: The competent cybersecurity authority, which article 2 defines as the Centro Nacional de Cibersegurança or, where one applies, the sectoral national authority under article 15(2)(a)
Divergence: Substantial, and in four places. **The anchor is not awareness.** Article 42(1) starts the twenty-four hours when the entity *«concluir que existe, ou possa vir a existir, um incidente significativo»* and runs them *«até 24 horas após essa verificação»* — from that determination, and reaching forward to an incident that may yet come to exist. **The seventy-two hour stage is conditional and is an update.** Article 42(3) owes it *«quando necessário»*, as *«uma atualização da notificação inicial»*, where the Directive's second stage is owed in every case. **There is a stage the Directive does not have.** Article 43 requires a notification of the *end* of significant impact, within twenty-four hours of that end. **The final report is measured differently and in a different unit.** Article 44(1) gives *«30 dias úteis a contar da data da notificação do fim de impacto significativo»* — thirty working days from that new stage, where the Directive gives one month from the incident notification.
Moves: yes
Standing: Read in the act itself, in the Diário da República, and not in guidance, which is why it is stated this firmly. One consequence worth holding: article 41(2) provides that where the incident is resolved within two hours of detection, only the end-of-impact notification is owed. An organisation working from the Directive alone would hold the wrong anchor, the wrong final deadline, and would not know the third stage exists.
Source: [pt-dl-125-2025]
Read: 2026-09-03

### NIS2 · Belgium
Country: BE
Act: Loi du 26 avril 2024 établissant un cadre pour la cybersécurité des réseaux et des systèmes d'information d'intérêt général pour la sécurité publique
In force: 18 October 2024, by article 98
Recipient: The national CSIRT, which article 1, 46° defines functionally as the national computer security incident response centre without naming the body
Divergence: None. Article 35 §1 transposes the cascade term for term and anchor for anchor: the early warning *«dans les vingt-quatre heures après avoir eu connaissance de l'incident significatif»*, the incident notification *«dans les septante-deux heures»* on the same footing, and the final report *«au plus tard un mois après la présentation de la notification d'incident»*. Trust service providers get twenty-four hours for the second stage under §2. Where an incident is still running when the final report falls due, §1, 5° gives a progress report then and the final report within one month of the incident's definitive handling.
Moves: no
Standing: Read in the act, in the Justel database of the Moniteur belge, and not in guidance. One thing the act does not settle: it defines the national CSIRT by what it does rather than by name, so this record does not name it either. Article 34 §1 adds that the CSIRT passes each notification to any sectoral authority immediately, and that notifications from essential entities also go to the NCCN.
Source: [be-loi-26-04-2024]
Read: 2026-09-03

### NIS2 · Czechia
Country: CZ
Act: Zákon č. 264/2025 Sb., o kybernetické bezpečnosti
In force: not stated in the material read
Recipient: Národní úřad pro kybernetickou a informační bezpečnost
Divergence: In three places, and one of them changes who decides. **The anchor is an internal determination.** The initial report is due *«bez zbytečného odkladu, nejpozději do 24 hodin»*, and the guidance says plainly what starts it: *«tato lhůta se počítá od okamžiku, kdy u konkrétního subjektu osoba k tomu pověřená (například manažer kybernetické bezpečnosti) vyhodnotí zjištěnou událost jako kybernetický bezpečnostní incident»* — from the moment a designated person inside the organisation classifies the event, not from the organisation becoming aware of a significant incident. **The authority decides significance, not the entity.** After the initial report the Úřad tells the provider whether the incident has significant impact; where it does not, the guidance says the reporting ends there. The Directive leaves that assessment with the entity. **The final report is measured from resolution.** *«Po jeho vyřešení nejpozději do 30 dnů závěrečnou zprávu»* — thirty days from the incident being resolved, where the Directive gives one month from the incident notification, with an interim report in the meantime if the incident is still running.
Moves: yes
Standing: This is the Úřad's own supporting material on the ZKB and its implementing decrees, not the act. Two things it does not contain: any seventy-two hour stage, and the date from which the act binds. Neither is recorded here as a result. It also states a threshold of its own — the duty reaches incidents where intentional causation cannot be excluded without undue delay and within twenty-four hours, so operational incidents that can be ruled out are not reportable.
Source: [nukib-hlaseni-incidentu]
Read: 2026-09-03

### NIS2 · Denmark
Country: DK
Act: Lov nr. 434 af 6. maj 2025 om foranstaltninger til sikring af et højt cybersikkerhedsniveau
In force: 1 July 2025, by § 33
Recipient: The relevant authority and the CSIRT, both of them, under § 12(1)
Divergence: None. Paragraph 13 keeps every term and every anchor: the early warning *«senest inden for 24 timer efter at enheden har fået kendskab til den væsentlige hændelse»*, the incident notification *«inden for 72 timer»* on the same footing, an interim report on the CSIRT's request, and the final report *«senest 1 måned efter fremsendelsen af den hændelsesunderretning»*. Trust service providers give the second stage within twenty-four hours. Where the incident is still running when the final report falls due, a status report goes then and the final report within one month of the incident being handled.
Moves: no
Standing: Read in the act as published by Retsinformation. Two things it settles that the Directive leaves to the Member State: the report is owed to the competent authority **and** the CSIRT, not to one of them, and § 13(3) obliges the CSIRT to answer within twenty-four hours of the early warning. The act does not name the channel.
Source: [dk-lov-434-2025]
Read: 2026-09-03

### NIS2 · Sweden
Country: SE
Act: Cybersäkerhetslag (2025:1506)
In force: 15 January 2026, by the transitional provisions
Recipient: The authority the Government designates, which the act itself does not name
Divergence: None in the terms. Section 5 owes the first notice *«så snart det kan ske, dock senast 24 timmar efter det att verksamhetsutövaren har fått kännedom om incidenten»*; section 6 gives trust service providers twenty-four hours and everyone else *«senast 72 timmar efter sådan kännedom»*; section 8 puts the final report *«senast en månad efter incidentanmälan»*, with a situation report instead where the incident is still running. What the act does not do is name the recipient: sections 5 and 6 owe the report to *«den myndighet som regeringen bestämmer»*.
Moves: no
Standing: Read in the act as published in Svensk författningssamling. Because the act designates the recipient by reference rather than by name, this record does not name one for Sweden either. The act also repeals the 2018 act on information security for essential and digital services.
Source: [se-cybersakerhetslag-2025]
Read: 2026-09-03

### NIS2 · Finland
Country: FI
Act: Kyberturvallisuuslaki 124/2025
In force: 8 April 2025, by § 47. Given 4 April 2025, published 7 April 2025.
Recipient: The supervising authority, which is sectoral under § 43. Traficom's Kyberturvallisuuskeskus is the single point of contact under § 18.
Divergence: The anchor is detection, not awareness. Section 11 reads *«Ensi-ilmoitus on tehtävä 24 tunnin kuluessa merkittävän poikkeaman havaitsemisesta ja jatkoilmoitus 72 tunnin kuluessa merkittävän poikkeaman havaitsemisesta»* — both stages run from *havaitseminen*, the detecting of the significant incident, where the Directive runs them from having become aware of it. The phrase for coming to know, *tuli tietoon*, does not appear in the act at all. The final report keeps the Directive's shape: within a month of the follow-up report, or for a long-running incident within a month of the end of its handling, with an interim report at the latest a month after the follow-up.
Moves: yes
Standing: Read in the act as published by Finlex, which serves it through a script and had to be rendered rather than fetched. Whether *havaitseminen* is read in Finnish administrative practice as earlier than awareness is not settled here. What is settled is that the act does not use the Directive's word.
Source: [fi-kyberturvallisuuslaki-124-2025]
Read: 2026-09-03

### NIS2 · Poland
Country: PL
Act: An amendment to the ustawa o krajowym systemie cyberbezpieczeństwa, passed by the Sejm and reported by the Ministry on 23 January 2026.
In force: not stated in the source read
Recipient: not recorded, see Divergence
Divergence: Not established. The Ministry's own announcement does not give a date of entry into force, and does not give the notification deadlines. What it does say is where the reports will go: *«Usprawnione zostanie też zgłaszanie incydentów – informacje będą przekazywane bezpośrednio do zespołów CSIRT przez system S46.»* It also says administrative fines may first be imposed two years after the act enters into force, which is the only interval the page gives.
Moves: unsettled
Standing: A ministerial announcement about a bill the Sejm has passed, which is not the same as an act in force. This record therefore names no Polish recipient and no Polish terms. Poland's existing national system rests on the earlier act, which has not been read here.
Source: [pl-mc-ksc-nowelizacja]
Read: 2026-09-03

### NIS2 · Romania
Country: RO
Act: Ordonanța de urgență nr. 155/2024
In force: Published in Monitorul Oficial on 31 December 2024. Articles 60 and 61 take effect thirty days after publication.
Recipient: The national cyber security incident response team
Divergence: None. The cascade is the Directive's, anchor included: the early warning *«nu mai târziu de 24 de ore de la data la care au luat cunoștință de incidentul semnificativ»*, the incident report *«nu mai târziu de 72 de ore din momentul în care au luat cunoștință»*, an interim report at the team's request, and the final report *«în termen de cel mult o lună de la transmiterea notificării incidentului»*.
Moves: no
Standing: Read in the ordinance on the legislative portal. It names the recipient by function — the national incident response team — rather than by name, and does not set the channel.
Source: [ro-oug-155-2024]
Read: 2026-09-03

### NIS2 · Croatia
Country: HR
Act: Zakon o kibernetičkoj sigurnosti, NN 14/2024
In force: The Act takes effect on the eighth day after publication, by article 116. The exact date is not printed in the Act.
Recipient: The competent CSIRT, under article 37 of the Act
Divergence: In three ways, and the first one is where to look. **The Act sets no deadline at all.** Article 37 states the duty to notify the competent CSIRT and the threshold, and stops. Every term is in the Uredba. **There the anchors hold**: the early warning within *«24 sata od trenutka saznanja za značajan incident»* and the initial notification within *«72 sata»* on the same footing, with trust service providers at twenty-four hours. **The final report is thirty days, not one month.** Article 70 of the Uredba gives *«najkasnije u roku od 30 dana od dana dostave početne obavijesti»*. **The interim report has a window the Directive does not set**: article 69 lets the CSIRT fix the deadline, but *«ne može biti kraći od 48 sati niti duži od sedam dana»*.
Moves: yes
Standing: Both instruments were read: the Act, and the Uredba o kibernetičkoj sigurnosti, NN 135/2024, which is where the cascade actually is. The point worth carrying is structural rather than numerical: an organisation that reads the Croatian act and stops has the duty, the recipient and the threshold, and not one hour of the cascade. The thirty days are a real difference from a month, in the months that are longer.
Source: [hr-zks-uredba]
Read: 2026-09-03

### NIS2 · Latvia
Country: LV
Act: Nacionālās kiberdrošības likums
In force: 1 September 2024, by article 64. Adopted by the Saeima on 20 June 2024, and amended on 4 June 2026 with effect from 18 June 2026.
Recipient: The competent cyber incident prevention institution, which article 34 names by function
Divergence: The hours are the Directive's. The point they run from is not stated. Article 34(2) reads *«Nozīmīga kiberincidenta gadījumā subjekts nekavējoties, bet ne vēlāk kā 24 stundu laikā ... iesniedz ... agrīno brīdinājumu»*, and 34(3) puts the initial report at seventy-two hours, twenty-four for a trust service provider, in the same construction. Neither names an anchor. The nearest thing to one is 34(1), which speaks of *«Konstatējot kiberincidentu»* — on establishing a cyber incident. The final report keeps the Directive's measure: *«mēneša laikā pēc šā panta trešajā daļā minētā ziņojuma iesniegšanas»*, one month after the initial report, with a progress report where the incident cannot be resolved in time and the final report after it is.
Moves: yes
Standing: Read in the act on Likumi.lv, in the version in force. An organisation in Latvia holds the intervals and has to supply the starting point from somewhere else. Whether *konstatējot* in 34(1) carries into 34(2) is a question of Latvian construction that this record does not answer.
Source: [lv-nacionalas-kiberdrosibas-likums]
Read: 2026-09-03

### NIS2 · Estonia
Country: EE
Act: Küberturvalisuse seadus
In force: The act dates from 2018. The provisions read here are those in force from 1 January 2026, as amended by RT I, 30.12.2025, 4.
Recipient: Riigi Infosüsteemi Amet, the State Information System Authority
Divergence: Not in the terms. Section 8(1) owes the first notice *«viivitamata, kuid hiljemalt 24 tundi pärast teada saamist küberintsidendist»*, section 8(4¹) the incident notice *«hiljemalt 72 tundi pärast olulise mõjuga küberintsidendist teada saamist»*, section 8(4²) twenty-four hours for a trust service provider, and section 8(7) the final report one month from the incident notice. All of it runs from learning of the incident, as the Directive has it. What is wider is the trigger: section 8(1) reaches not only an incident with significant impact but one *«mille oluline mõju ... ei ole ilmne, kuid seda võib»* — where the significant impact is not evident but may arise.
Moves: no
Standing: Read in the consolidated act on Riigi Teataja, which serves it through a script and had to be rendered. Section 12(3¹) puts a deadline on the authority as Denmark's does: the Amet answers within twenty-four hours where possible. The act does not set the channel.
Source: [ee-kuberturvalisuse-seadus]
Read: 2026-09-03

### NIS2 · Slovakia
Country: SK
Act: Zákon č. 366/2024 Z. z., amending zákon č. 69/2018 Z. z.
In force: 1 January 2025, by article VII
Recipient: The Národný bezpečnostný úrad, through the single cybersecurity information system
Divergence: The anchor is detection. Both stages run *«od jeho zistenia»* — from the ascertaining of the significant incident: the early warning *«najneskôr do 24 hodín od jeho zistenia»*, the notification *«najneskôr do 72 hodín od jeho zistenia»*, twenty-four hours for a trust service provider. The Directive runs both from becoming aware. The final report keeps the month: *«najneskôr jeden mesiac po nahlásení oznámenia»*. What follows it does not: where a cross-border incident is still running, letter (e) requires an updated final report within **thirty days** of normal operation being restored, and where the incident is still running when the final report is due, further information and an updated final report within thirty days of its resolution.
Moves: yes
Standing: Read in the amending act as published by Slov-Lex, in the version in force from 1 January 2025. Slovakia is the third country in this record to replace awareness with a word of its own, after Finland's *havaitseminen* and Czechia's internal classification.
Source: [sk-zakon-366-2024]
Read: 2026-09-03

### NIS2 · Slovenia
Country: SI
Act: Zakon o informacijski varnosti, ZInfV-1, Uradni list RS št. 40/25
In force: Article 70 puts it on the fifteenth day after publication in the Uradni list. Passed by the Državni zbor on 23 May 2025.
Recipient: The competent CSIRT group, under article 30(1)
Divergence: The anchor is detection. Article 30(1) owes the early message *«najpozneje pa v 24 urah po zaznavi pomembnega incidenta»* and the incident notification *«najpozneje pa v 72 urah po zaznavi pomembnega incidenta»* — after the *detection* of the significant incident, where the Directive measures from becoming aware. Trust service providers report within twenty-four hours on the same footing. Everything after the anchor is the Directive's: an interim report on request, the final report within one month of the incident notification, and where the incident is still running, a progress report and the final report within one month of its resolution.
Moves: yes
Standing: Read in the act as published in the Uradni list. Article 30(3) also puts a deadline on the authority — the CSIRT answers within twenty-four hours of the early message where possible — which Denmark and Estonia do too.
Source: [si-zinfv-1]
Read: 2026-09-03

### NIS2 · Luxembourg
Country: LU
Act: Loi du 5 mai 2026 concernant des mesures destinées à assurer un niveau élevé de cybersécurité
In force: not stated in the source read
Recipient: The Institut Luxembourgeois de Régulation, which organises the regime and receives the notifications
Divergence: Nothing recorded moves a term, and only one term is recorded. The government's own announcement gives the first stage — *«tout incident ayant un impact important dans un délai de 24 heures»* as a preliminary notification — and stops there. It does not say what the twenty-four hours run from, and it does not give the stages after the first.
Moves: no
Standing: A government communiqué about the law, not the law. This record therefore holds one interval for Luxembourg and neither the anchor nor the rest of the cascade. The same position as France, and recorded the same way.
Source: [lu-communique-nis2]
Read: 2026-09-03

### NIS2 · Malta
Country: MT
Act: Measures for a High Common Level of Cybersecurity Across the European Union (Malta) Order, 2024 — read in a public consultation draft, not as a made Legal Notice.
In force: Not fixed. Article 1(3) leaves it to *«such a date as the Prime Minister may by notice in the Gazette establish»*, and different dates may be set for different provisions.
Recipient: CSIRTMalta, in the order as drafted
Divergence: The draft moves nothing. Sub-article (6) reproduces the cascade exactly: the early warning *«within twenty-four (24) hours of becoming aware of the significant incident»*, the incident notification *«within seventy-two (72) hours of becoming aware»*, an intermediate report on request, the final report *«not later than one (1) month after the submission of the incident notification»*, and where the incident is still running, a progress report then and a final report within one month of its handling. Trust service providers get twenty-four hours. CSIRTMalta owes a response within twenty-four hours of the early warning. What is unsettled is not the content but the standing: every page of the document read carries the footer *Public Consultation*, and the citation reads *«L.N. of 2024»* with no number.
Moves: unsettled
Standing: A consultation draft, published by the Ministry responsible. Whether the order has since been made, and on what date it was brought into force, is not established by this source. The terms are recorded because they were read; the instrument is not recorded as binding, because this document does not show that it is.
Source: [mt-cybersecurity-order-draft]
Read: 2026-09-03

### NIS2 · Norway
Country: NO
Act: Digitalsikkerhetsloven, with the digitalsikkerhetsforskriften of 20 June 2025
In force: 1 October 2025
Recipient: The sectoral supervisory authority, with a copy to the National Contact Point, under section 17 of the regulation
Divergence: Norway is not running the same cascade. **The law implements the first NIS Directive, not NIS2.** Neither the regulation nor the authority's guidance page mentions NIS2 at all. **The final report is measured from the first warning, not from the second stage.** Section 17 reads *«Innen en måned fra varsel som nevnt i første ledd er sendt, skal tilbyderen gi tilsynsmyndigheten en hendelsesrapport»* — one month from the *first* warning, where the Directive measures its final report from the incident notification. **The seventy-two hours have no anchor in the regulation**: it says only *«Informasjonen i varselet skal oppdateres innen 72 timer»*. **And the regulation and the guidance use different words for the moment.** The regulation runs the twenty-four hours *«etter at en tilbyder ... fikk kjennskap til hendelsen»*, from obtaining knowledge; the authority's own page says *«innen 24 timer etter at dere oppdaget hendelsen»*, after you discovered it.
Moves: yes
Standing: Read in the regulation on Lovdata and in the National Security Authority's guidance, which is where the second wording comes from. The recipient also differs in kind: the warning goes to the sectoral supervisory authority with a copy to the National Contact Point, not to a CSIRT.
Source: [no-digitalsikkerhetsforskriften]
Read: 2026-09-03

### NIS2 · Cyprus
Country: CY
Act: Not read. The document read is the Authority's summary guide to the Directive, not the Cypriot transposing law.
In force: not established
Recipient: The relevant competent authority or the National CSIRT, as the guide puts it
Divergence: The document read states one deadline that the Directive does not. Its notification timeline gives the stages as **6 h** *ΕΓΚΑΙΡΗ ΠΡΟΕΙΔΟΠΟΙΗΣΗ (EARLY WARNING)*, **72 h** *ΚΟΙΝΟΠΟΙΗΣΗ ΠΕΡΙΣΤΑΤΙΚΟΥ*, an intermediate progress report *όπως απαιτείται*, and **1 μήνας** for the *ΤΕΛΙΚΗ ΕΚΘΕΣΗ*, which it explains as due *«το αργότερο ένα μήνα μετά την κοινοποίηση του συμβάντος»*. Article 23(4)(a) of the Directive gives twenty-four hours for the early warning, not six. The other three stages match.
Moves: unsettled
Standing: This is the Digital Security Authority's own summary guide **to the Directive**, and the six hours appear in its timeline graphic. This record does not conclude that Cypriot law requires six hours: it records that the national authority's published guide states six where the instrument it summarises states twenty-four. The Cypriot transposing law has not been read, so no Cypriot term is recorded from it, and the recipient is given in the guide's own words rather than named.
Source: [cy-dsa-nis2-guide]
Read: 2026-09-03

### NIS2 · Iceland
Country: IS
Act: Lög nr. 78/2019 um öryggi net- og upplýsingakerfa mikilvægra innviða
In force: 1 September 2020
Recipient: The cybersecurity team, netöryggissveit, operated by the telecommunications authority
Divergence: There are no hours. Article 8 requires notification *«svo fljótt sem verða má»* — as soon as may be — for serious incidents or risks threatening the security of network and information systems, and sets no interval at all. There is no early warning at twenty-four hours, no notification at seventy-two, and no final report at one month. The act does not cite Directive (EU) 2022/2555 anywhere.
Moves: yes
Standing: Read in the consolidated act on the Althingi's site. Iceland is in the EEA and the NIS2 Directive is not what this act implements; the regime in force is the earlier one. An organisation applying the ITER cascade in Iceland is applying terms that Icelandic law does not contain.
Source: [is-log-78-2019]
Read: 2026-09-03

### NIS2 · Liechtenstein
Country: LI
Act: Cyber Security Act (CSG), 355.13
In force: Not established. The translation read does not carry a commencement article; it repeals the Cyber Security Act of 4 May 2023, LGBl. 2023 no. 269, and gives entities four weeks from entry into force to register.
Recipient: The National Cyber Security Unit
Divergence: None. The cascade is transposed as it stands: the early warning *«without undue delay, and in any event within 24 hours of becoming aware of the significant security incident»*, the incident notification *«within 72 hours of becoming aware»*, an intermediate report at the Unit's request, and *«a final report no later than one month after the submission of the incident notification»*.
Moves: no
Standing: Read in the Government's own English translation, which carries a disclaimer; the binding text is the German. Liechtenstein is the one EEA state in this record that has transposed NIS2 — Norway's regime implements the earlier Directive and Iceland's sets no interval at all.
Source: [li-csg]
Read: 2026-09-03

### NIS2 · Hungary
Country: HU
Act: 2024. évi LXIX. törvény Magyarország kiberbiztonságáról
In force: 1 January 2025, by § 82(1), with § 120(1) a day later. The implementing decree is 418/2024. (XII. 23.) Korm. rendelet.
Recipient: The national cybersecurity incident handling centre, the Központ, with the SZTFH as the supervisory authority
Divergence: None in the terms, but they are not where an organisation would look. **The act contains no hour at all** — a search of its whole text returns no expression of hours for notification, because § 66 states the duty and leaves the detail to a government decree. The terms are in § 77 of decree 418/2024: a first notification *«a kiberbiztonsági incidensről való tudomásszerzéstől számított 24 órán belül»*, an event notification *«72 órán belül»* on the same anchor, an interim situation report at the Centre's request, and a closing report *«legkésőbb a 3. pont szerinti eseménybejelentés benyújtását követő egy hónapon belül»*. All of it runs from becoming aware, as the Directive has it.
Moves: no
Standing: Both instruments were read: the act, and the decree that carries the cascade. Hungary is the second country in this record built this way, after Croatia. In both, reading the transposing act and stopping produces the conclusion that there are no deadlines.
Source: [hu-418-2024-korm-rendelet]
Read: 2026-09-03

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
Owed to: dpa
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
Anchor: After the notification it completes, which is the 72 hour one above
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
Anchor: The same point as the 72 hour notification. In the decided case below the authority ordered it within twenty days of its own decision
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
Anchor: Throughout. The Board expects the documentation to be made as the incident develops
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
Owed to: financial
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
Anchor: The same point as the initial notification
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
Anchor: Before each of the terms above, whichever one is about to be missed
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
Owed to: csirt
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
Owed to: market
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
