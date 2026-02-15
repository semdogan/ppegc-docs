# Frequently Asked Questions (FAQ)

**Platform for Exceptional Genomic Cancer Cases**

*Last updated: February 15, 2026*

---

## General Questions

### What is PPEGC?

PPEGC (Platform for Exceptional Genomic Cancer Cases) is an international collaborative platform dedicated to collecting, curating, and sharing exceptional oncological cases associated with genomic alterations. We focus on cases showing unexpected therapeutic responses, unusual resistance patterns, or atypical toxicities.

### Why was PPEGC created?

Exceptional cancer cases are often isolated within individual institutions and rarely shared systematically. PPEGC was created to:
- Capture these valuable "weak signals" in precision oncology
- Generate biological hypotheses from rare clinical observations
- Facilitate international clinical networking
- Advance precision medicine through shared knowledge

### Who runs PPEGC?

PPEGC is hosted at Gustave Roussy Institute (France) and governed by a Steering Committee of international oncology experts. See our [Governance page](GOVERNANCE.md) for details on organizational structure.

### Is PPEGC free to use?

Yes! Both submitting cases and accessing published data are completely free. PPEGC operates as a non-profit platform dedicated to advancing cancer research.

---

## For Contributors

### Who can submit cases?

Any qualified healthcare professional can submit cases, including:
- Medical oncologists
- Radiation oncologists and surgical oncologists
- Pathologists
- Molecular biologists and clinical geneticists
- Clinical pharmacists with oncology expertise
- Academic researchers with access to clinical data

### What qualifies as an "exceptional" case?

An exceptional case presents one or more of the following:

**Unexpected Therapeutic Response:**
- Complete or durable response in a context where such outcome is rare
- Exceptional responder to a therapy where most patients don't respond

**Unexpected Resistance:**
- Primary or acquired resistance without known mechanisms
- Resistance to targeted therapy despite confirmed biomarker presence

**Unusual Toxicity:**
- Severe or atypical adverse events potentially linked to genomic variants
- Toxicity patterns not explained by standard pharmacology

**Novel Findings:**
- Previously unreported genotype-phenotype associations

### How long does the review process take?

Cases are reviewed within **7-15 business days** of submission. You will receive an email notification with the outcome (acceptance, rejection, or request for additional information).

### What happens if my case is rejected?

You will receive detailed feedback explaining why the case was rejected. Common reasons include:
- Insufficient clinical or genomic documentation
- Case doesn't meet exceptionality criteria
- Inadequate pseudonymization

You may revise and resubmit after addressing the identified issues.

### Will I be credited for my submission?

Yes! Published cases include your name and institutional affiliation. Each case receives a DOI (Digital Object Identifier) for academic citation.

### Can I update a case after publication?

Yes. If you have follow-up data or new findings related to a published case, contact us at support@ppegc.org. We can publish an updated version with versioning information.

### How do I cite a PPEGC case?

Use this format:
```
[Your Name]. [Year]. [Cancer Type] with [Variant] and [Phenotype]. 
Platform for Exceptional Genomic Cancer Cases (PPEGC). 
DOI: 10.ppegc/[case-id]
```

---

## Data and Privacy

### How is patient privacy protected?

**Multiple layers of protection:**

1. **Pseudonymization:** All direct identifiers (name, date of birth, medical record number, precise address) must be removed before submission

2. **Anonymization:** Before publication, we further anonymize data by removing exact dates, institution names, and other potentially identifying details

3. **Minimal data:** We only publish essential information (cancer type, age range, genomic variant, clinical phenotype)

4. **Secure infrastructure:** Data is hosted on HDS-certified servers at Gustave Roussy (France, EU)

See our [Privacy Policy](PRIVACY.md) for complete details.

### Is patient consent required?

The requirement depends on patient status:

**Living Patients:**
- Patient must be informed of pseudonymized data sharing for research
- Patient has the right to object (non-opposition model)
- Alternatively, explicit consent can be obtained

**Deceased Patients:**
- Data sharing permitted if no prior objection was recorded
- Complies with local laws regarding posthumous data use

**Unreachable Patients:**
- Reasonable efforts must be made to contact
- Submission justified under legitimate scientific interest (GDPR Article 89)

See our [Terms of Submission](TERMS.md) for legal framework details.

### Can patients request removal of their data?

Yes. Patients can exercise their right to erasure:
- **Before publication:** Contact the submitting institution or our DPO (dpo@gustaveroussy.fr) — data will be deleted
- **After publication:** Once anonymized and published, it becomes technically impossible to identify and remove specific cases (GDPR Article 11)

### Where is data stored?

All data is stored on secure, HDS-certified infrastructure at Gustave Roussy Institute in Villejuif, France (European Union). Data **never** leaves the EU.

### What about HIPAA (for US contributors)?

US contributors must ensure HIPAA compliance when submitting cases. Since data is pseudonymized and does not include direct identifiers, it generally qualifies as a "limited dataset" under HIPAA. However, contributors are responsible for compliance with their institutional policies.

---

## Using PPEGC Data

### Who can access published cases?

Anyone! Published cases are freely accessible on the PPEGC website. No registration is required for viewing.

### What license applies to published data?

Published cases are licensed under **Creative Commons Attribution 4.0 (CC BY 4.0)**. This means:
- ✅ You can use, share, and adapt the data
- ✅ Commercial use is permitted
- ⚠️ You must give appropriate credit to PPEGC and the original contributor

### Can I use PPEGC data in my research publication?

Absolutely! That's exactly what we encourage. Just make sure to:
1. Cite PPEGC and the original case contributor(s)
2. Include the case DOI in your references
3. Acknowledge PPEGC in your acknowledgments section

### Can pharmaceutical companies use PPEGC data?

Yes. The CC BY 4.0 license permits commercial use. Industry partners can:
- Access published cases freely
- Use data for drug development research
- Include cases in regulatory submissions (with proper citation)

For bulk data access, custom analytics, or API integration, contact us about partnership agreements.

### Is there an API for programmatic access?

Not yet, but it's on our roadmap. If you're interested in API access, contact research@ppegc.org to express your interest and help shape the feature.

---

## Technical Questions

### What data format is used for genomic variants?

We require **HGVS nomenclature** (Human Genome Variation Society standard) for all genomic variants.

Example: `NM_004333.4:c.2369C>T (p.Thr790Met)`

### What if I don't know the HGVS format?

Many variant calling tools output HGVS format automatically. If you need help converting your variant data:
- Use tools like [Mutalyzer](https://mutalyzer.nl/) or [VariantValidator](https://variantvalidator.org/)
- Contact our support team (support@ppegc.org) for assistance

### Can I submit whole genome/exome data?

Currently, we collect only **specific variants** (not whole genome files). We accept 1-3 key variants per case. 

Future versions may support VCF file uploads for researchers requesting deeper access.

### What file formats are supported for supplementary documents?

For optional supporting files (imaging, lab results), we accept:
- PDF
- PNG, JPG (for images)
- Maximum file size: 10MB per file

---

## Collaboration and Partnerships

### Can my institution become a formal partner?

Yes! We welcome institutional partnerships. Benefits may include:
- Recognition on our website and materials
- Collaborative research projects
- Priority support for contributors
- Custom data analytics

Contact us at partnerships@ppegc.org to discuss.

### Can I organize a PPEGC workshop at my institution?

Absolutely! We're happy to support educational events about precision oncology and exceptional cases. Contact us for speaker availability and materials.

### How can I get involved beyond submitting cases?

Opportunities include:
- **Scientific Advisory Board:** We're forming an international board (expressions of interest welcome)
- **Curation Team:** Volunteer reviewers with expertise in specific cancer types
- **Patient Advocacy:** Representatives for our planned Patient Advisory Council
- **Technical Contributors:** Help improve our platform (GitHub contributors welcome)

Email contact@ppegc.org with your area of interest.

---

## Troubleshooting

### I can't access the submission form

Common solutions:
- Clear your browser cache and cookies
- Try a different browser (Chrome, Firefox, Safari)
- Disable browser extensions that might block forms
- Check if your institution's firewall blocks REDCap

If problems persist, contact support@ppegc.org with details about your browser and error messages.

### My submission was rejected — can I appeal?

While formal appeals are not part of our process, you can:
1. Review the detailed feedback provided
2. Revise your submission to address the concerns
3. Resubmit with improvements
4. Contact curation@ppegc.org if you believe the rejection was in error

### I submitted a case weeks ago but haven't heard back

Please check:
- Your spam/junk folder for our notification email
- The email address you provided is correct

If it's been more than 15 business days, contact support@ppegc.org with your submission details (contributor name, approximate submission date).

### The website is down or showing errors

We monitor uptime continuously, but if you encounter issues:
- Try refreshing the page
- Check [status.ppegc.org](https://status.ppegc.org) for service status *(future)*
- Report issues to support@ppegc.org

---

## Contact

**Can't find your answer?**

- **General questions:** contact@ppegc.org
- **Technical support:** support@ppegc.org
- **Curation inquiries:** curation@ppegc.org
- **Data protection:** dpo@gustaveroussy.fr
- **Partnerships:** partnerships@ppegc.org

We typically respond within 2 business days.

---

*Last updated: February 15, 2026*  
[Back to Home](index.md) | [Governance](GOVERNANCE.md) | [Privacy Policy](PRIVACY.md) | [Terms](TERMS.md)
