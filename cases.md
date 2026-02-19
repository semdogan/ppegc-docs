---
layout: default
title: Published Cases - PPEGC
---

<style>
/* Page Header */
.page-header {
  background: linear-gradient(135deg, #2E75B6 0%, #1a4d7a 100%);
  color: white;
  padding: 50px 20px;
  margin: -40px -40px 30px -40px;
  text-align: center;
}

.page-header h1 {
  color: white;
  border: none;
  margin-bottom: 15px;
}

/* Filter Bar */
.filter-bar {
  background: #f8f9fa;
  padding: 20px;
  border-radius: 8px;
  margin-bottom: 30px;
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
  align-items: center;
}

.filter-btn {
  padding: 10px 20px;
  border: 2px solid #dee2e6;
  background: white;
  border-radius: 20px;
  cursor: pointer;
  transition: all 0.3s;
  font-weight: 600;
  color: #666;
}

.filter-btn:hover,
.filter-btn.active {
  border-color: #2E75B6;
  background: #2E75B6;
  color: white;
}

/* Case Cards */
.case-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
  gap: 25px;
  margin: 30px 0;
}

.case-card {
  background: white;
  border: 1px solid #dee2e6;
  border-radius: 12px;
  padding: 25px;
  transition: all 0.3s;
  position: relative;
  overflow: hidden;
}

.case-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 4px;
  height: 100%;
  background: #2E75B6;
  transform: scaleY(0);
  transition: transform 0.3s;
}

.case-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.12);
}

.case-card:hover::before {
  transform: scaleY(1);
}

.case-header {
  display: flex;
  justify-content: space-between;
  align-items: start;
  margin-bottom: 15px;
}

.case-id {
  font-weight: bold;
  color: #2E75B6;
  font-size: 1.1em;
}

.case-date {
  font-size: 0.85em;
  color: #999;
}

.case-title {
  font-weight: 600;
  margin-bottom: 12px;
  color: #333;
  font-size: 1.05em;
  line-height: 1.4;
}

.case-meta {
  display: flex;
  gap: 15px;
  font-size: 0.9em;
  color: #666;
  margin-bottom: 12px;
  flex-wrap: wrap;
}

.case-meta-item {
  display: flex;
  align-items: center;
  gap: 5px;
}

.case-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 15px;
}

.case-tag {
  display: inline-block;
  padding: 5px 12px;
  border-radius: 12px;
  font-size: 0.8em;
  font-weight: 600;
}

.tag-response {
  background: #d4edda;
  color: #155724;
}

.tag-resistance {
  background: #fff3cd;
  color: #856404;
}

.tag-toxicity {
  background: #f8d7da;
  color: #721c24;
}

.case-description {
  color: #666;
  font-size: 0.95em;
  line-height: 1.5;
  margin-bottom: 15px;
}

.case-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 15px;
  border-top: 1px solid #e9ecef;
}

.case-region {
  font-size: 0.9em;
  color: #999;
}

.btn-view {
  color: #2E75B6;
  text-decoration: none;
  font-weight: 600;
  display: flex;
  align-items: center;
  gap: 5px;
}

.btn-view:hover {
  text-decoration: underline;
}

/* Stats Bar */
.stats-bar {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 20px;
  margin-bottom: 40px;
}

.stat-box {
  background: white;
  border: 2px solid #e9ecef;
  border-radius: 8px;
  padding: 20px;
  text-align: center;
}

.stat-number {
  font-size: 2em;
  font-weight: bold;
  color: #2E75B6;
}

.stat-label {
  color: #666;
  font-size: 0.9em;
  margin-top: 5px;
}

/* Responsive */
@media (max-width: 768px) {
  .case-grid {
    grid-template-columns: 1fr;
  }
  
  .filter-bar {
    flex-direction: column;
    align-items: stretch;
  }
  
  .filter-btn {
    text-align: center;
  }
}
</style>

<div class="page-header">
  <h1>Published Cases</h1>
  <p>Browse exceptional cancer cases curated by the PPEGC scientific team</p>
</div>

<!-- Stats Bar -->
<div class="stats-bar">
  <div class="stat-box">
    <div class="stat-number">3</div>
    <div class="stat-label">Total Cases</div>
  </div>
  <div class="stat-box">
    <div class="stat-number">3</div>
    <div class="stat-label">Cancer Types</div>
  </div>
  <div class="stat-box">
    <div class="stat-number">3</div>
    <div class="stat-label">Countries</div>
  </div>
  <div class="stat-box">
    <div class="stat-number">100%</div>
    <div class="stat-label">Open Access</div>
  </div>
</div>

<!-- Filter Bar -->
<div class="filter-bar">
  <strong>Filter by:</strong>
  <button class="filter-btn active">All Cases</button>
  <button class="filter-btn">Exceptional Response</button>
  <button class="filter-btn">Resistance</button>
  <button class="filter-btn">Toxicity</button>
  <button class="filter-btn">Lung Cancer</button>
  <button class="filter-btn">Melanoma</button>
  <button class="filter-btn">Colorectal</button>
</div>

<!-- Cases Grid -->
<div class="case-grid">
  
  <!-- Case 1 -->
  <div class="case-card">
    <div class="case-header">
      <div class="case-id">PPEGC-2025-0001</div>
      <div class="case-date">Feb 15, 2025</div>
    </div>
    
    <div class="case-title">
      NSCLC with EGFR L858R+T790M: Exceptional Osimertinib Response
    </div>
    
    <div class="case-meta">
      <div class="case-meta-item">
        <span>🧬</span> EGFR
      </div>
      <div class="case-meta-item">
        <span>💊</span> Osimertinib
      </div>
    </div>
    
    <div class="case-tags">
      <span class="case-tag tag-response">Exceptional Response</span>
      <span class="case-tag" style="background: #e3f2fd; color: #1565c0;">Lung Cancer</span>
    </div>
    
    <div class="case-description">
      Complete response at 8 weeks maintained >24 months. Despite extensive disease burden, patient achieved complete metabolic resolution with minimal toxicity.
    </div>
    
    <div class="case-footer">
      <div class="case-region">🇫🇷 EUR-047</div>
      <a href="cases/PPEGC-2025-0001.html" class="btn-view">
        View Case <span>→</span>
      </a>
    </div>
  </div>
  
  <!-- Case 2 -->
  <div class="case-card">
    <div class="case-header">
      <div class="case-id">PPEGC-2025-0002</div>
      <div class="case-date">Feb 16, 2025</div>
    </div>
    
    <div class="case-title">
      BRAF V600E Melanoma with PTEN Loss: Primary Vemurafenib Resistance
    </div>
    
    <div class="case-meta">
      <div class="case-meta-item">
        <span>🧬</span> BRAF, PTEN
      </div>
      <div class="case-meta-item">
        <span>💊</span> Vemurafenib
      </div>
    </div>
    
    <div class="case-tags">
      <span class="case-tag tag-resistance">Primary Resistance</span>
      <span class="case-tag" style="background: #fce4ec; color: #880e4f;">Melanoma</span>
    </div>
    
    <div class="case-description">
      Progressive disease despite canonical V600E mutation. Concurrent PTEN nonsense mutation detected at baseline, suggesting novel resistance mechanism.
    </div>
    
    <div class="case-footer">
      <div class="case-region">🇺🇸 NAM-023</div>
      <a href="cases/PPEGC-2025-0002.html" class="btn-view">
        View Case <span>→</span>
      </a>
    </div>
  </div>
  
  <!-- Case 3 -->
  <div class="case-card">
    <div class="case-header">
      <div class="case-id">PPEGC-2025-0003</div>
      <div class="case-date">Feb 17, 2025</div>
    </div>
    
    <div class="case-title">
      Colorectal Cancer: Severe FOLFIRI Toxicity with UGT1A1/DPYD Variants
    </div>
    
    <div class="case-meta">
      <div class="case-meta-item">
        <span>🧬</span> UGT1A1, DPYD
      </div>
      <div class="case-meta-item">
        <span>💊</span> FOLFIRI
      </div>
    </div>
    
    <div class="case-tags">
      <span class="case-tag tag-toxicity">Severe Toxicity</span>
      <span class="case-tag" style="background: #fff9c4; color: #f57f17;">Colorectal</span>
    </div>
    
    <div class="case-description">
      Grade 4 toxicity requiring ICU admission. Compound pharmacogenomic variants (*28/*28 + IVS14+1G>A) identified retrospectively, highlighting importance of pre-treatment screening.
    </div>
    
    <div class="case-footer">
      <div class="case-region">🇯🇵 ASI-091</div>
      <a href="cases/PPEGC-2025-0003.html" class="btn-view">
        View Case <span>→</span>
      </a>
    </div>
  </div>
  
</div>

---

## Browse by Category

### Cancer Type
- [Lung Cancer](#) (1 case)
- [Melanoma](#) (1 case)
- [Colorectal Cancer](#) (1 case)

### Phenotype
- [Exceptional Response](#) (1 case)
- [Unexpected Resistance](#) (1 case)
- [Unusual Toxicity](#) (1 case)

### Gene
- [EGFR](#) (1 case)
- [BRAF](#) (1 case)
- [PTEN](#) (1 case)
- [UGT1A1](#) (1 case)
- [DPYD](#) (1 case)

---

<div style="background: #f8f9fa; padding: 40px; border-radius: 8px; text-align: center; margin: 40px 0;">
  <h2 style="color: #2E75B6; margin-top: 0;">Have an Exceptional Case?</h2>
  <p style="font-size: 1.1em; margin-bottom: 25px;">Share your observation with the international oncology community</p>
  <a href="https://redcap.link/2flknzfs" style="display: inline-block; background: #2E75B6; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: bold;">Submit Your Case</a>
  <p style="margin-top: 20px; color: #666; font-size: 0.9em;">Fast review (7-15 days) • Full attribution • Open access publication</p>
</div>

---

[← Back to Home](index.html) | [About PPEGC](ABOUT.html) | [FAQ](FAQ.html)
