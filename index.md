---
layout: default
title: PPEGC - Platform for Exceptional Genomic Cancer Cases
---

<style>
/* Hero Section */
.hero {
  background: linear-gradient(135deg, #2E75B6 0%, #1a4d7a 100%);
  color: white;
  padding: 80px 20px;
  text-align: center;
  margin: -40px -40px 40px -40px;
  border-radius: 0;
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 20px;
  color: white;
  border: none;
}

.hero-subtitle {
  font-size: 1.4em;
  margin-bottom: 30px;
  opacity: 0.95;
}

.hero-cta {
  display: inline-block;
  background: white;
  color: #2E75B6;
  padding: 15px 40px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  font-size: 1.1em;
  margin: 10px;
  transition: transform 0.2s, box-shadow 0.2s;
}

.hero-cta:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(0,0,0,0.2);
  text-decoration: none;
}

.hero-cta.secondary {
  background: transparent;
  color: white;
  border: 2px solid white;
}

/* Stats Section */
.stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 30px;
  margin: 40px 0;
  text-align: center;
}

.stat-card {
  background: #f8f9fa;
  padding: 30px;
  border-radius: 8px;
  border-left: 4px solid #2E75B6;
}

.stat-number {
  font-size: 2.5em;
  font-weight: bold;
  color: #2E75B6;
  margin-bottom: 10px;
}

.stat-label {
  color: #666;
  font-size: 1em;
}

/* Feature Cards */
.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.feature-card {
  background: white;
  padding: 30px;
  border-radius: 8px;
  border: 1px solid #dee2e6;
  transition: box-shadow 0.3s;
}

.feature-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.feature-icon {
  font-size: 2.5em;
  margin-bottom: 15px;
}

.feature-card h3 {
  color: #2E75B6;
  margin-top: 0;
}

/* Case Highlights */
.case-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 25px;
  margin: 30px 0;
}

.case-card {
  background: white;
  border: 1px solid #dee2e6;
  border-radius: 8px;
  padding: 25px;
  transition: transform 0.2s, box-shadow 0.2s;
}

.case-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(0,0,0,0.15);
}

.case-id {
  font-weight: bold;
  color: #2E75B6;
  font-size: 1.1em;
  margin-bottom: 10px;
}

.case-title {
  font-weight: 600;
  margin-bottom: 10px;
  color: #333;
}

.case-meta {
  font-size: 0.9em;
  color: #666;
  margin-bottom: 15px;
}

.case-meta span {
  display: inline-block;
  margin-right: 15px;
}

.case-tag {
  display: inline-block;
  background: #e7f3ff;
  color: #2E75B6;
  padding: 4px 12px;
  border-radius: 12px;
  font-size: 0.85em;
  margin-right: 8px;
  margin-bottom: 8px;
}

.btn-view-case {
  display: inline-block;
  color: #2E75B6;
  text-decoration: none;
  font-weight: 600;
  margin-top: 10px;
}

.btn-view-case:hover {
  text-decoration: underline;
}

/* Call to Action Box */
.cta-box {
  background: linear-gradient(135deg, #e7f3ff 0%, #d4e9ff 100%);
  padding: 40px;
  border-radius: 8px;
  text-align: center;
  margin: 50px 0;
  border: 2px solid #2E75B6;
}

.cta-box h2 {
  color: #2E75B6;
  margin-top: 0;
}

/* Responsive */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 2em;
  }
  
  .hero-subtitle {
    font-size: 1.1em;
  }
  
  .stats {
    grid-template-columns: 1fr;
  }
  
  .features {
    grid-template-columns: 1fr;
  }
  
  .case-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<!-- Hero Section -->
<div class="hero">
  <h1>PPEGC</h1>
  <p class="hero-subtitle">Platform for Exceptional Genomic Cancer Cases</p>
  <p style="font-size: 1.1em; margin-bottom: 30px;">Transforming isolated clinical observations into actionable scientific knowledge</p>
  <a href="cases.html" class="hero-cta">Browse Cases</a>
  <a href="https://redcap.gustaveroussy.fr/redcap/surveys/?s=T3WP4X834N" class="hero-cta secondary">Submit a Case</a>
</div>

<!-- Stats Section -->
<div class="stats">
  <div class="stat-card">
    <div class="stat-number">3</div>
    <div class="stat-label">Published Cases</div>
  </div>
  <div class="stat-card">
    <div class="stat-number">3</div>
    <div class="stat-label">Contributing Centers</div>
  </div>
  <div class="stat-card">
    <div class="stat-number">3</div>
    <div class="stat-label">Countries</div>
  </div>
  <div class="stat-card">
    <div class="stat-number">100%</div>
    <div class="stat-label">Open Access</div>
  </div>
</div>

## What is PPEGC?

PPEGC is an **international collaborative platform** dedicated to collecting, curating, and sharing exceptional cancer cases associated with genomic alterations. We focus on cases showing:

- 🎯 **Unexpected therapeutic responses** (exceptional responders)
- 🔬 **Unusual resistance patterns** without known mechanisms
- ⚠️ **Atypical toxicities** potentially linked to genomic variants
- 💡 **Novel genotype-phenotype associations**

---

## Why PPEGC Matters

<div class="features">
  <div class="feature-card">
    <div class="feature-icon">🔍</div>
    <h3>Capture Weak Signals</h3>
    <p>Exceptional cases are often isolated within institutions. PPEGC systematically captures these valuable observations for the scientific community.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">⚡</div>
    <h3>Rapid Sharing</h3>
    <p>Cases reviewed within 7-15 days and immediately published. No more waiting 12-24 months for traditional publication.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">🌍</div>
    <h3>Global Collaboration</h3>
    <p>Connect with clinicians worldwide facing similar cases. Foster international research partnerships.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">🔓</div>
    <h3>Open Science</h3>
    <p>All published cases freely accessible under CC BY 4.0 license. No paywalls, no registration required to view.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">🔐</div>
    <h3>Privacy Protected</h3>
    <p>Rigorous pseudonymization and anonymization. GDPR-compliant infrastructure on HDS-certified servers.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">📊</div>
    <h3>Structured Data</h3>
    <p>Standardized format with HGVS nomenclature, searchable fields, and machine-readable data for computational analysis.</p>
  </div>
</div>

---

## Featured Cases

<div class="case-grid">
  <div class="case-card">
    <div class="case-id">PPEGC-2025-0001</div>
    <div class="case-title">NSCLC with EGFR L858R+T790M: Exceptional Osimertinib Response</div>
    <div class="case-meta">
      <span>🇫🇷 Europe</span>
      <span>📅 Feb 2025</span>
    </div>
    <div class="case-tag">Exceptional Response</div>
    <div class="case-tag">Lung Cancer</div>
    <p>Complete response at 8 weeks, maintained >24 months with minimal toxicity. Suggests subgroup with exceptionally favorable prognosis.</p>
    <a href="cases/PPEGC-2025-0001.html" class="btn-view-case">View Case →</a>
  </div>
  
  <div class="case-card">
    <div class="case-id">PPEGC-2025-0002</div>
    <div class="case-title">BRAF V600E Melanoma with PTEN Loss: Primary Vemurafenib Resistance</div>
    <div class="case-meta">
      <span>🇺🇸 North America</span>
      <span>📅 Feb 2025</span>
    </div>
    <div class="case-tag">Primary Resistance</div>
    <div class="case-tag">Melanoma</div>
    <p>Progressive disease despite canonical V600E mutation. Concurrent PTEN nonsense mutation detected at baseline, suggesting mechanism of resistance.</p>
    <a href="cases/PPEGC-2025-0002.html" class="btn-view-case">View Case →</a>
  </div>
  
  <div class="case-card">
    <div class="case-id">PPEGC-2025-0003</div>
    <div class="case-title">Colorectal Cancer: Severe FOLFIRI Toxicity with UGT1A1/DPYD Variants</div>
    <div class="case-meta">
      <span>🇯🇵 Asia</span>
      <span>📅 Feb 2025</span>
    </div>
    <div class="case-tag">Severe Toxicity</div>
    <div class="case-tag">Colorectal</div>
    <p>Grade 4 toxicity requiring ICU admission. Compound pharmacogenomic variants (*28/*28 + IVS14+1G>A) identified retrospectively.</p>
    <a href="cases/PPEGC-2025-0003.html" class="btn-view-case">View Case →</a>
  </div>
</div>

<div style="text-align: center; margin-top: 30px;">
  <a href="cases.html" class="hero-cta">View All Cases →</a>
</div>

---

## How It Works

### For Contributors

1. **Submit** your exceptional case via our simple REDCap form (5-8 minutes)
2. **Curation** by our scientific team within 7-15 business days
3. **Publication** with your name and institution credited (anonymized)
4. **Recognition** via DOI for academic citation

### For Researchers

1. **Browse** published cases by cancer type, gene, or phenotype
2. **Access** full clinical and genomic data under CC BY 4.0
3. **Connect** with submitting clinicians for collaboration
4. **Cite** cases in your publications using provided DOI

---

<div class="cta-box" id="submit">
  <h2>Have an Exceptional Case to Share?</h2>
  <p style="font-size: 1.1em; margin-bottom: 25px;">Join our international community of clinicians advancing precision oncology</p>
  <a href="https://redcap.link/ppegc-submit" class="hero-cta" style="background: #2E75B6; color: white;">Submit Your Case</a>
  <p style="margin-top: 20px; font-size: 0.9em; color: #666;">Free to submit • Fast review (7-15 days) • Full attribution</p>
</div>

---

## Learn More

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin: 40px 0;">
  <a href="ABOUT.html" style="display: block; padding: 20px; background: #f8f9fa; border-radius: 8px; text-align: center; text-decoration: none; color: #2E75B6; font-weight: 600; border: 2px solid transparent; transition: border-color 0.3s;">
    📖 About PPEGC
  </a>
  <a href="GOVERNANCE.html" style="display: block; padding: 20px; background: #f8f9fa; border-radius: 8px; text-align: center; text-decoration: none; color: #2E75B6; font-weight: 600; border: 2px solid transparent; transition: border-color 0.3s;">
    ⚖️ Governance
  </a>
  <a href="FAQ.html" style="display: block; padding: 20px; background: #f8f9fa; border-radius: 8px; text-align: center; text-decoration: none; color: #2E75B6; font-weight: 600; border: 2px solid transparent; transition: border-color 0.3s;">
    ❓ FAQ
  </a>
  <a href="PRIVACY.html" style="display: block; padding: 20px; background: #f8f9fa; border-radius: 8px; text-align: center; text-decoration: none; color: #2E75B6; font-weight: 600; border: 2px solid transparent; transition: border-color 0.3s;">
    🔒 Privacy Policy
  </a>
</div>

---

## Partners & Supporters

<div style="text-align: center; padding: 40px 20px; background: #f8f9fa; border-radius: 8px; margin: 40px 0;">
  <p style="font-size: 1.1em; color: #666; margin-bottom: 20px;">Hosted at</p>
  <p style="font-size: 1.5em; font-weight: bold; color: #2E75B6;">Gustave Roussy Institute</p>
  <p style="color: #666;">Europe's Leading Comprehensive Cancer Center<br>Villejuif, France</p>
</div>

---

## Contact

**General Inquiries:** [contact@ppegc.org](mailto:contact@ppegc.org)  
**Technical Support:** [support@ppegc.org](mailto:support@ppegc.org)  
**Data Protection:** [dpo@gustaveroussy.fr](mailto:dpo@gustaveroussy.fr)

---

<div style="text-align: center; padding: 30px 0; color: #666; font-size: 0.9em;">
  <p>© 2026 PPEGC. Platform for Exceptional Genomic Cancer Cases.</p>
  <p>Licensed under <a href="https://creativecommons.org/licenses/by/4.0/" style="color: #2E75B6;">CC BY 4.0</a></p>
</div>
