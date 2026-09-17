# Sustainable Building Materials in Africa (2015–2025): A Systematic Evidence Synthesis

[![DOI](https://zenodo.org/badge/1371342678.svg)](https://doi.org/10.5281/zenodo.22771539)
[![OSF DOI](https://img.shields.io/badge/OSF-dvukp-blue)](https://osf.io/dvukp/)
[![PRISMA 2020](https://img.shields.io/badge/PRISMA-2020%20Compliant-green)](http://www.prisma-statement.org/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Overview
This repository contains the complete computational workflow, bibliographic logs, screening records, extraction workbooks, quality appraisal data, and manuscript deliverables for the systematic review:
**"Sustainable Building Materials in Africa (2015–2025): A Systematic Evidence Synthesis of Material Classes, Technical Performance, and Implementation Contexts"**  
**Lead Author:** Agbeniga Agboola ([ORCID: 0009-0005-6878-1661](https://orcid.org/0009-0005-6878-1661))  
**Affiliation:** Independent Researcher and Civil / Site Engineer  
**OSF Project:** [https://osf.io/dvukp/](https://osf.io/dvukp/)  
**Zenodo Persistent DOI:** [10.5281/zenodo.22771539](https://doi.org/10.5281/zenodo.22771539)

The review investigates the 10-year evidence base on sustainable building materials (SBMs) across Africa, evaluating performance, life-cycle impact, economic feasibility, and institutional barriers across five material classes:
1. **Low-Carbon Cements & Binders** (Limestone Calcined Clay Cement [LC3], Geopolymers, Agro-Waste Pozzolans)
2. **Earth-Based Masonry** (Compressed Stabilized Earth Blocks [CSEB], Rammed Earth, Adobe)
3. **Recycled & Waste Composites** (Recycled Concrete Aggregates, Waste Plastics, Crushed Glass, Slag)
4. **Renewable Bio-Based Materials** (Structural Bamboo, Mass Timber, Vegetable Fiber Mortars)
5. **Innovative & Smart Materials** (Phase Change Materials [PCMs], Bio-mediated Mineralization [MICP])

---

## Directory Structure
The repository follows standard Open Science Framework (OSF) component structuring:

```text
├── 01_Protocol/            # Registered systematic review protocol and eligibility criteria
├── 02_SearchLogs/          # Search strategies, raw exported citations, and deduplication records
├── 03_Screening/           # Title/abstract and full-text eligibility screening logs
├── 04_DataExtraction/      # 31-parameter extraction master dataset (2,492 primary empirical studies)
├── 05_QualityAppraisal/    # Methodological quality and risk of bias assessments using JBI and ISO tools
├── 06_Analysis/            # 8 synthesis tables, cross-country metrics, and 300-DPI publication figures
├── 07_Manuscript/          # Paper drafts (Word & Markdown), cover letter, and submission guidelines
├── 08_Supplements/         # PRISMA 2020 checklists, flow diagrams, and supplementary search appendix
├── resources/              # Reference datasets (including AJOL structured metadata)
├── IMPLEMENTATION_PLAN.md  # Detailed execution roadmap
├── architecture.md         # System and methodology architecture
└── index.json              # Structural repo data map
```

## Key Findings & Synthesis Highlights
- **Multi-Database Scale:** 9,112 raw records identified across Google Scholar (5,747), OpenAlex (2,802), DOAJ (419), and AJOL (144).
- **Rigorous PRISMA Pipeline:** 1,829 duplicates eliminated $\to$ 7,283 unique records screened $\to$ 4,461 excluded at Title/Abstract $\to$ 2,822 full-text records assessed $\to$ 330 excluded at full text $\to$ **2,492 primary empirical studies included in extraction and synthesis**.
- **Material Representation:** Low-Carbon Binders (35.7%, n = 890) and Earth-Based Masonry (31.0%, n = 773) constitute two-thirds of the empirical evidence base.
- **Mechanical Viability:** Compressed Stabilized Earth Blocks (CSEB: 3.5–9.2 MPa) reliably exceed commercial sandcrete blocks (frequently 1.0–1.8 MPa) and satisfy NIS 87 and GS 297 loadbearing standards (2.5–2.8 MPa). LC3 and agro-waste pozzolan concretes achieve structural grades (22.0–52.0 MPa).
- **Environmental Decarbonization:** Embodied carbon reductions of 30–42% for LC3 concrete relative to OPC baseline (350 kg CO₂-eq/m³), 65–78% for stabilized earth masonry, and substantial biogenic carbon storage potential for structural bamboo (-120 to -350 kg CO₂-eq/m³ during growth).
- **Methodological Quality:** 24.7% Low Risk of Bias and 75.3% Moderate Risk of Bias, with statistical variance under-reporting (only 51.4% reporting standard deviations or ANOVA) identified as the primary methodological deficit across experimental studies.
- **Implementation Roadmap:** Synthesizing 137 adoption studies delineates solutions for overcoming prescriptive colonial building codes (78.1% barrier prevalence), fragmented supply chains (71.5%), and testing infrastructure deficits (63.5%) through performance-based ARSO standards (ARS 680–684) and green public procurement quotas.

---

## Deliverables & Key Artifacts
- **Manuscript Package:** [`07_Manuscript/Manuscript_Draft_v1.docx`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/07_Manuscript/Manuscript_Draft_v1.docx) & [`.md`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/07_Manuscript/Manuscript_Draft_v1.md) (7,956 words, 10 embedded tables, 58 peer-reviewed references, Appendix 1).
- **Cover Letter & Highlights:** [`07_Manuscript/Cover_Letter_and_Highlights.docx`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/07_Manuscript/Cover_Letter_and_Highlights.docx) & [`.md`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/07_Manuscript/Cover_Letter_and_Highlights.md) (Targeted for *Journal of Building Engineering*).
- **Submission Manual:** [`07_Manuscript/Journal_Submission_Guidelines_and_Checklist.md`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/07_Manuscript/Journal_Submission_Guidelines_and_Checklist.md).
- **Synthesis Tables:** [`06_Analysis/Synthesis_Tables.xlsx`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/06_Analysis/Synthesis_Tables.xlsx) (8 comprehensive sheets: Geography, Taxonomy, Tables 3A–D, LCA, Quality, Barriers).
- **OSF Master Wiki & Component Guides:** [`OSF_WIKI.md`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/OSF_WIKI.md) & [`OSF_Wikis/`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/OSF_Wikis/).
- **Extraction & Quality Datasets:** [`04_DataExtraction/Extraction_Completed_Master.xlsx`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/04_DataExtraction/Extraction_Completed_Master.xlsx) & [`05_QualityAppraisal/Appraisal_Summary.xlsx`](file:///c:/Users/emman/OneDrive/Documents/SustainableMaterials_Africa_2015-2025/05_QualityAppraisal/Appraisal_Summary.xlsx).

---

## Citation & Archival References
```bibtex
@article{agboola2026sustainable,
  title={Sustainable Building Materials in Africa (2015--2025): A Systematic Evidence Synthesis of Material Classes, Technical Performance, and Implementation Contexts},
  author={Agboola, Agbeniga},
  journal={Journal of Building Engineering},
  year={2026},
  note={Pre-registered on OSF: https://osf.io/dvukp/, Data archived at Zenodo: https://doi.org/10.5281/zenodo.22771539}
}
```
