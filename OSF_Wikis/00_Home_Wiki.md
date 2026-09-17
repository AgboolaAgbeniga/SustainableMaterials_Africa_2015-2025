# Sustainable Building Materials in Africa (2015–2025): A Systematic Review

**Lead Author:** Agbeniga Agboola ([ORCID: 0009-0005-6878-1661](https://orcid.org/0009-0005-6878-1661) | [emmanuelagbeniga@gmail.com](mailto:emmanuelagbeniga@gmail.com))  
**Affiliation:** Independent Researcher and Civil / Site Engineer  
**Registered OSF Project:** [https://osf.io/dvukp/](https://osf.io/dvukp/)  
**Permanent Repository DOI:** [10.5281/zenodo.22771539](https://doi.org/10.5281/zenodo.22771539)  
**License:** Creative Commons Attribution 4.0 International (CC-BY 4.0)  
**Standard Compliance:** PRISMA 2020 Statement | Joanna Briggs Institute (JBI) Critical Appraisal  

---

## Project Overview

Sub-Saharan Africa is confronting the fastest urban demographic transformation on Earth, projected to double its population by 2050 and requiring an estimated 250 million new housing units. Historically and contemporarily, this urban expansion has relied on carbon-intensive Ordinary Portland Cement (OPC) concrete and sandcrete masonry blocks. This dependency generates approximately 8% of global greenhouse emissions, depletes scarce national foreign exchange reserves through clinker importation, drives severe environmental degradation through illegal river sand dredging, and precipitates frequent catastrophic building collapses due to substandard artisanal block casting (frequently yielding only 1.0–1.8 MPa against the 2.5 MPa Nigerian NIS 87 standard).

This repository contains the complete computational workflow, bibliographic search logs, screening decisions, extraction databases, quality appraisal forms, synthesis tables, high-resolution figures, and manuscript deliverables for the comprehensive systematic review of sustainable building materials across Africa over the 2015–2025 decadal window.

Synthesizing **9,112 raw bibliographic records** across four academic databases (Google Scholar, OpenAlex, DOAJ, and AJOL), the review rigorously extracts and appraises **2,492 primary empirical laboratory and field studies** across 31 standardized bibliographic, mechanical, chemical, and life-cycle assessment parameters.

---

## Component Architecture & Navigation

This OSF project is structured into eight modular child components designed to provide 100% transparent reproducibility under Open Science standards:

| Component | Component Title | Primary Artifacts & Data Files | Scope & Methodological Role |
| :--- | :--- | :--- | :--- |
| **01_Protocol** | Review Protocol & Registration | `Protocol_SR_SBM_Africa_v1_2025-09-24.pdf` | Formally registered systematic review protocol (872.2 kB) establishing PICO/CCo criteria. |
| **02_SearchLogs** | Multi-Database Search Logs | `SearchLog_Master.csv`, `AJOL_Results_2026-09-15.csv`, `OpenAlex_Results_2026-09-15.csv`, `DOAJ_Results_2026-09-15.csv`, `Deduplication_Summary_2026-09-15.xlsx` | 9,112 raw citations across 4 database engines + algorithmic deduplication (1,829 duplicates eliminated $\to$ 7,283 net unique records). |
| **03_Screening** | Two-Stage Screening Registers | `TitleAbstract_ScreeningLog.xlsx`, `FullText_ScreeningLog.xlsx`, `Intra_Rater_Audit_Log.xlsx`, `Screening_Audit_Summary_2026-09-15.xlsx` | Two-stage screening protocol (4,461 excluded at Title/Abstract; 2,822 assessed at full text with 330 excluded; 2,492 primary studies included; reproducible 10% re-screening audit kappa = 0.95). |
| **04_DataExtraction** | 31-Field Extraction Master | `Extraction_Completed_Master.xlsx` | Granular 31-parameter relational database for all 2,492 primary empirical studies across 5 material classes. |
| **05_QualityAppraisal** | Multi-Tool Quality Appraisal | `Appraisal_Summary.xlsx` | Design-appropriate quality appraisal across 5 study designs (JBI Quasi-Experimental [n=2,251], JBI Cross-Sectional [n=137], ISO 14040/44 [n=104]; 24.7% Low Risk, 75.3% Moderate Risk). |
| **06_Analysis** | Synthesis Tables & Figures | `Synthesis_Tables.xlsx`, `Fig1_PRISMA_2020_Flow_Diagram.png`, `Fig2_Geographic_Distribution.png`, `Fig3_Material_Class_Taxonomy_Distribution.png`, `Fig4_Compressive_Strength_Benchmark_Boxplot.png`, `Fig5_Barriers_Enablers_Taxonomy_Radar.png` | 8 comprehensive synthesis sheets + 5 publication-ready 300-DPI academic figures. |
| **07_Manuscript** | Publication Deliverables | `Manuscript_Draft_v1.docx`, `Manuscript_Draft_v1.md`, `Cover_Letter_and_Highlights.docx`, `Cover_Letter_and_Highlights.md` | Full APA 7th Edition manuscript (10,782 words, 54 verified references, 10 embedded tables, Appendix 1) + companion submission package. |
| **08_Supplements** | Supplementary Documentation | `PRISMA_2020_Checklist.docx`, `PRISMA_2020_Checklist.md`, `PRISMA_2020_Flow_Diagram_Completed.docx` | Item-by-item 27-item PRISMA 2020 checklist mapped to manuscript sections and verified flow chart. |

---

## Core Empirical Findings

1. **Structural Reliability of Compressed Stabilized Earth Blocks (CSEBs):**
   * Incorporating 5% to 8% Portland cement or lime elevates 28-day dry compressive strengths to **3.5–9.2 MPa**, with water absorption reduced to 7.0–11.5%.
   * Certified CSEBs deliver 2 to 3 times the load-bearing strength of commercial sandcrete blocks sold in informal African markets (1.0–1.8 MPa) and comfortably exceed the Nigerian NIS 87 standard (min 2.5 MPa) while utilizing 50–70% less cement.
2. **Industrial Viability of Low-Carbon Binders (LC3 & Agro-Waste Pozzolans):**
   * Limestone Calcined Clay Cement (LC3-50) concrete achieves structural grades of **28.0–52.0 MPa**, while mitigating embodied carbon by 30% to 42% relative to Ordinary Portland Cement (OPC).
   * Agricultural pozzolanic ashes (rice husk ash, sugarcane bagasse ash, palm oil fuel ash) achieve structural concretes of **22.0–44.0 MPa** at 15–25% cement replacement, while refining capillary pores and enhancing marine chloride resistance.
3. **Carbon Sequestration in Bio-Based Materials:**
   * Indigenous structural bamboo (*Oxytenanthera abyssinica* and *Bambusa vulgaris*) exhibits axial tensile capacities of **120–240 MPa** (surpassing structural mild steel on a strength-to-weight basis).
   * Structural bamboo culms sequester approximately 45–50% elemental carbon by dry weight, demonstrating substantial biogenic carbon storage potential, though net cradle-to-gate greenhouse gas balances depend strictly on preservative chemical treatments, transportation distances, and end-of-life disposal routes.
4. **The Sandcrete Paradox & Systemic Adoption Barriers:**
   * Commercial uptake of sustainable materials is held back not by structural deficits, but by prescriptive building codes (78.1%), fragmented agro-waste supply chains (71.5%), testing infrastructure deficits (63.5%), and social stigmas associating earth with poverty (60.6%). Categories were not mutually exclusive across the 137 barrier studies.

---

## Computational Replication & Verification

To replicate the data processing, deduplication, and screening audit locally:

```bash
# Clone the verified repository
git clone https://github.com/AgboolaAgbeniga/SustainableMaterials_Africa_2015-2025.git
cd SustainableMaterials_Africa_2015-2025

# Verify environment dependencies (Python 3.10+)
pip install pandas openpyxl python-docx matplotlib

# Execute automated manuscript and audit verification
python scratch/verify_manuscript_expansion.py
```

---

## How to Cite This Research

### APA 7th Edition:
> Agboola, A. (2026). *Sustainable Building Materials in Africa (2015–2025): A Systematic Review*. Open Science Framework. https://doi.org/10.5281/zenodo.22771539 (Project repository: https://osf.io/dvukp/).

### BibTeX:
```bibtex
@article{Agboola2026_SustainableMaterialsAfrica,
  author    = {Agboola, Agbeniga},
  title     = {Sustainable Building Materials in Africa (2015--2025): A Systematic Review},
  year      = {2026},
  publisher = {Open Science Framework},
  doi       = {10.5281/zenodo.22771539},
  url       = {https://osf.io/dvukp/},
  note      = {PRISMA 2020 Compliant Decadal Systematic Review}
}
```
