# PPEGC Governance

**Platform for Exceptional Genomic Cancer Cases**

*Last updated: February 15, 2026*

---

## Mission Statement

PPEGC is dedicated to advancing precision oncology by collecting, curating, and sharing exceptional cancer cases associated with genomic alterations. Our mission is to transform isolated clinical observations into actionable scientific knowledge that benefits patients worldwide.

---

## 1. Organizational Structure

### 1.1 Steering Committee

The PPEGC Steering Committee provides strategic direction and oversight for the platform.

**Composition:**
- **Chair:** [Name], [Title], [Institution]
- **Vice-Chair:** [Name], [Title], [Institution]
- **Members:**
  - [Name], [Specialty], [Institution]
  - [Name], [Specialty], [Institution]
  - [Name], [Specialty], [Institution]
  - [Name], [Specialty], [Institution]

**Responsibilities:**
- Define strategic priorities and research focus areas
- Approve major policy changes
- Review annual performance and impact metrics
- Ensure ethical compliance and data protection
- Foster international collaboration

**Meetings:** Quarterly (minimum), with additional ad hoc meetings as needed

**Term:** 3 years, renewable once

---

### 1.2 Scientific Curation Team

The Curation Team is responsible for reviewing, validating, and publishing submitted cases.

**Composition:**
- **Lead Curator:** [Name], Medical Oncologist, [Institution]
- **Co-Curators:**
  - [Name], Molecular Biologist
  - [Name], Clinical Geneticist
  - [Name], Bioinformatician
  - [Name], Pathologist

**Responsibilities:**
- Review submitted cases within 7-15 business days
- Validate clinical and genomic data quality
- Ensure scientific rigor and relevance
- Request additional information when needed
- Approve or reject submissions with justification
- Monitor for duplicate submissions

**Decision-making:** Consensus-based; disputed cases escalated to Steering Committee

---

### 1.3 Data Protection Officer (DPO)

**DPO:** [Name], [Contact: dpo@gustaveroussy.fr]

**Responsibilities:**
- Ensure GDPR and data protection compliance
- Monitor pseudonymization processes
- Handle data subject requests (access, erasure, objection)
- Conduct privacy impact assessments
- Liaise with supervisory authorities (CNIL)
- Investigate data breaches and incidents

---

### 1.4 Technical Team

**Lead Developer:** [Name], [Institution]

**Responsibilities:**
- Maintain platform infrastructure (REDCap, website)
- Ensure HDS-certified hosting compliance
- Implement security measures (encryption, access controls)
- Develop data export and API functionalities
- Monitor system performance and uptime
- Provide technical support to contributors

---

## 2. Case Submission and Curation Process

### 2.1 Submission Workflow

```
Contributor Submission
        ↓
Automated Validation (completeness, pseudonymization)
        ↓
Manual Curation (scientific review)
        ↓
Decision: Accept / Reject / Request More Info
        ↓
If Accepted: Anonymization & Publication
        ↓
Public Case Page on PPEGC.org
```

### 2.2 Acceptance Criteria

Cases are evaluated based on:

**Scientific Exceptionality:**
- Unexpected therapeutic response (exceptional responder)
- Unexpected resistance without known mechanisms
- Unusual toxicity potentially linked to genomic variants
- Novel genotype-phenotype associations

**Data Quality:**
- Complete clinical context (cancer type, stage, treatment)
- Genomic data in standardized format (HGVS nomenclature)
- Clear description of exceptional phenotype
- Supporting evidence (imaging, lab results)

**Ethical Compliance:**
- Proper pseudonymization (no direct identifiers)
- Patient informed or deceased/unreachable with legal compliance
- Contributor attestation of local regulatory compliance

### 2.3 Rejection Criteria

Cases may be rejected for:
- Insufficient documentation or missing key data
- Inadequate pseudonymization (identifiable information present)
- Case does not meet exceptionality threshold
- Duplicate submission (already published or under review)
- Suspected data fabrication or scientific misconduct

**Contributors receive detailed feedback** explaining the rejection and may resubmit after addressing deficiencies.

---

## 3. Data Management and Security

### 3.1 Data Lifecycle

**Phase 1: Submission (Day 0)**
- Data arrives at Gustave Roussy secure servers (France, EU)
- Encrypted in transit (TLS 1.3) and at rest (AES-256)
- Stored in HDS-certified infrastructure

**Phase 2: Curation (Days 1-15)**
- Access restricted to Curation Team (multi-factor authentication)
- Data remains pseudonymized
- Audit logs track all access and modifications

**Phase 3: Publication (Day 15+)**
- Further anonymization (remove submitting center details, exact dates)
- Published case includes: cancer type, age range, genomic variant(s), phenotype
- Link to original patient is permanently severed

**Phase 4: Long-term Storage**
- Anonymized cases retained indefinitely for scientific archive
- Quarterly backups to geographically distributed locations
- Annual security audits

### 3.2 Access Control

**Internal Access (Curation Phase):**
- Curation Team: Read/Write access to pseudonymized data
- Technical Team: System administration, no case content access
- Steering Committee: Aggregate statistics only

**Public Access (Post-Publication):**
- Anyone can view published cases on PPEGC.org
- Data available under Creative Commons CC BY 4.0 license
- No registration required for viewing

**Restricted Access (Future):**
- Researchers may request bulk data exports (approved by Steering Committee)
- Industry partners may access aggregated analytics (partnership agreements required)

### 3.3 Security Measures

- **Infrastructure:** HDS-certified hosting at Gustave Roussy
- **Network:** Firewall, intrusion detection/prevention systems
- **Application:** Penetration testing (annual), vulnerability scanning (monthly)
- **Personnel:** Background checks, confidentiality agreements, annual training
- **Incident Response:** 24-hour breach notification protocol, forensic investigation capability

---

## 4. Ethical Framework

### 4.1 Core Principles

**Respect for Persons:**
- Patient autonomy: right to be informed and object to data sharing
- Vulnerable populations: additional safeguards for minors, cognitively impaired

**Beneficence:**
- Maximize scientific benefit while minimizing risks
- Contribute to advancement of precision oncology

**Justice:**
- Equitable access to platform (no submission fees)
- Open publication model (no paywalls)

**Transparency:**
- Public governance documentation
- Open methodology and curation criteria
- Attribution to original contributors

### 4.2 Informed Consent / Non-Opposition

**Living Patients:**
- Patient must be informed of pseudonymized data sharing for research
- Patient has right to object at any time before publication
- Objection does not affect quality of care

**Deceased Patients:**
- Data sharing permitted if no prior objection recorded
- Complies with local laws regarding posthumous data use

**Unreachable Patients:**
- Reasonable efforts made to contact
- Use justified under legitimate scientific interest (GDPR Art. 89)

### 4.3 Conflict of Interest Policy

**Disclosure Required:**
All Steering Committee and Curation Team members must disclose:
- Financial relationships with pharmaceutical/biotech companies
- Equity holdings in relevant companies
- Consulting agreements
- Research funding sources

**Recusal:**
Members with conflicts of interest must recuse themselves from decisions involving:
- Cases related to drugs they have financial interests in
- Submissions from their own institutions (when substantial)

**Annual Review:**
Conflicts of interest reviewed annually and published on PPEGC website

---

## 5. Intellectual Property and Data Sharing

### 5.1 Contributor Rights

Contributors retain ownership of their original data but grant PPEGC:
- Non-exclusive, worldwide, royalty-free license
- Right to publish in anonymized form
- Right to use for scientific research and education

### 5.2 Public License

Published cases are licensed under **Creative Commons Attribution 4.0 (CC BY 4.0):**
- Anyone may use, share, adapt the data
- Must give appropriate credit to PPEGC and original contributor
- Commercial use permitted

### 5.3 Citation and Attribution

**Published Cases Include:**
- Contributor name(s) and institutional affiliation
- Date of publication
- Unique case identifier (e.g., PPEGC-2026-0042)
- DOI (Digital Object Identifier) for citability

**Recommended Citation Format:**
```
[Contributor Name(s)]. [Year]. [Cancer Type] with [Variant] and [Phenotype]. 
Platform for Exceptional Genomic Cancer Cases (PPEGC). 
DOI: 10.ppegc/[case-id]
```

### 5.4 Use by Third Parties

**Academic Researchers:**
- Free use of published data
- Must cite PPEGC and original contributors in publications

**Industry Partners:**
- Free use of published data
- Partnership agreements available for bulk access, custom analytics, or embedded API

**No Restrictions on:**
- Hypothesis generation
- Replication studies
- Meta-analyses
- Educational use

---

## 6. Quality Assurance

### 6.1 Curation Metrics

**Tracked Annually:**
- Number of submissions received
- Acceptance rate
- Median time to decision
- Reasons for rejection (categorized)
- Geographic distribution of contributors
- Disease types represented

**Quality Indicators:**
- Percentage of cases requiring additional information
- Percentage of cases with complete genomic annotation
- Contributor satisfaction scores (annual survey)

### 6.2 Scientific Advisory Board (Future)

PPEGC plans to establish a Scientific Advisory Board comprising:
- International oncology thought leaders
- Patient advocacy representatives
- Bioethics experts
- Data science specialists

**Role:** Provide independent evaluation of PPEGC's scientific impact and strategic direction

---

## 7. Financial Sustainability

### 7.1 Funding Model

**Current Funding (2026):**
- Gustave Roussy Institute operational support
- [Grant/Foundation name if applicable]

**Future Funding Strategy:**
- Public research grants (ANR, European Innovation Council)
- Philanthropic foundations (cancer research, precision medicine)
- Industry partnerships (data analytics, API access)
- Institutional memberships (academic centers)

**Commitment:**
- Core public access to published cases will **always remain free**
- No submission fees for contributors

### 7.2 Budget Transparency

Annual financial report published on PPEGC website, including:
- Revenue sources
- Operating expenses (infrastructure, personnel, curation)
- Reserve fund status

---

## 8. Community Engagement

### 8.1 Contributor Recognition

- **Top Contributors:** Annual recognition on website (with permission)
- **Impact Stories:** Featured case studies highlighting scientific discoveries
- **Webinars:** Quarterly webinars on precision oncology topics
- **Newsletters:** Monthly updates on new cases, research using PPEGC data

### 8.2 Patient Involvement

- **Patient Advisory Council (Future):** Input on governance, communication, priorities
- **Public-Facing Materials:** Lay summaries of published cases
- **Impact Reporting:** How PPEGC contributes to better treatments

---

## 9. Amendments to Governance

### 9.1 Modification Process

**Minor Changes (procedures, clarifications):**
- Approved by Steering Committee
- Posted on website with 30-day notice

**Major Changes (structure, mission, ethical policies):**
- Proposed by Steering Committee
- Open comment period (60 days)
- Approval requires 2/3 majority vote
- Effective 90 days after approval

### 9.2 Version Control

All governance document versions archived and publicly accessible. Each version includes:
- Date of adoption
- Summary of changes
- Rationale for modifications

---

## 10. Contact and Accountability

### For Contributors:
- **Technical Support:** support@ppegc.org
- **Submission Questions:** curation@ppegc.org

### For Data Subjects (Patients):
- **Data Protection Officer:** dpo@gustaveroussy.fr
- **Exercise Rights (access, erasure, objection):** Contact DPO

### For Researchers:
- **Collaboration Inquiries:** research@ppegc.org
- **Data Access Requests:** data-access@ppegc.org

### For Media and Press:
- **Press Inquiries:** press@ppegc.org

### Supervisory Authority (France):
**CNIL (Commission Nationale de l'Informatique et des Libertés)**
- Website: www.cnil.fr
- Phone: +33 1 53 73 22 22

---

## Appendix A: Key Documents

- [Privacy Policy](link-to-privacy-policy)
- [Terms of Submission](link-to-terms)
- [Patient Information Notice (EN)](link-to-patient-notice-en)
- [Patient Information Notice (FR)](link-to-patient-notice-fr)
- [Curation Guidelines (Internal)](link-for-curators-only)

---

## Appendix B: Revision History

| Version | Date | Changes | Approved By |
|---------|------|---------|-------------|
| 1.0 | February 15, 2026 | Initial publication | Steering Committee |
| | | | |

---

**Platform for Exceptional Genomic Cancer Cases (PPEGC)**  
Hosted at Gustave Roussy Institute, Villejuif, France  
Website: www.ppegc.org  
Email: contact@ppegc.org

© 2026 PPEGC. This governance document is licensed under CC BY 4.0.
