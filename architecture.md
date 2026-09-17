# Project Architecture & Methodology: Sustainable Building Materials in Africa (2015–2025)

## Overview
This repository contains the complete systematic review entitled:
**"Sustainable Building Materials in Africa (2015–2025): A Systematic Evidence Synthesis of Material Classes, Technical Performance, and Implementation Contexts"** (Lead Author: Agbeniga Agboola, ORCID: 0009-0005-6878-1661), registered on the Open Science Framework (OSF Project: https://osf.io/dvukp/) and archived on Zenodo (DOI: 10.5281/zenodo.22771539) according to PRISMA 2020 guidelines.

## Research Objectives
To synthesize the decadal empirical evidence on sustainable building materials (SBMs) studied or applied in Africa over 2015–2025 across:
1. **Context & Geographic Distribution:** Sub-regional distribution across North, West, Central, East, and Southern Africa.
2. **Taxonomy & Material Benchmarks:** Reported 28-day compressive strength, flexural/tensile capacity, density, and water absorption across 5 material classes (Low-Carbon Binders, Earth-Based Masonry, Recycled Composites, Bio-Based Systems, Smart Systems).
3. **Environmental Profiles:** Embodied carbon (kg CO₂-eq/m³) and energy reductions relative to standardized baselines (OPC concrete: 350 kg CO₂-eq/m³; Fired brick: 280 kg CO₂-eq/m³), distinguishing biogenic storage from life-cycle emissions.
4. **Methodological Quality & Risk of Bias:** Design-appropriate appraisal across 5 study designs: physical engineering studies (n = 2,251: 2,062 lab + 168 microstructural + 21 prototype) using JBI Quasi-Experimental, socio-technical surveys (n = 137) using JBI Cross-Sectional, and environmental assessments (n = 104) using ISO 14040/44.
5. **Implementation Barriers & Enablers:** Empirical synthesis across 137 adoption studies evaluating regulatory, economic, infrastructure, and perceptual factors (non-mutually exclusive).

## Pipeline & Directory Structure
1. **`01_Protocol/`**: Protocol documentation registered on OSF (`Protocol_SR_SBM_Africa_v1_2025-09-24.pdf`).
2. **`02_SearchLogs/`**: Search strategies, query strings, execution dates (2025–2026), and raw exported citations across Google Scholar (5,747), OpenAlex (2,802), DOAJ (419), and AJOL (144) totaling 9,112 hits. Master deduplication audit eliminating 1,829 duplicates (514 DOI, 1,315 title/author) yielding 7,283 unique records.
3. **`03_Screening/`**: Stage 1 title/abstract screening (4,461 excluded: EX-MAT 4,311; EX-GEO 148; EX-TYPE 2). Stage 2 full-text eligibility screening of 2,822 candidate records (330 excluded: EX-DOCTYPE 231; EX-GEO 84; EX-MAT 13; EX-LANG 2), yielding 2,492 primary empirical studies. Reproducible 10% intra-rater re-screening audit log (`Intra_Rater_Audit_Log.xlsx`) confirming $\kappa = 0.95$ ($P_o = 98.4\%$).
4. **`04_DataExtraction/`**: Master 31-parameter extraction database (`Extraction_Completed_Master.xlsx`) for all 2,492 included primary empirical studies.
5. **`05_QualityAppraisal/`**: Multi-tool quality appraisal matrix (`Appraisal_Summary.xlsx`) reflecting 24.7% Low Risk of Bias (n = 615) and 75.3% Moderate Risk of Bias (n = 1,877).
6. **`06_Analysis/`**: 8 comprehensive synthesis tables (`Synthesis_Tables.xlsx`) and 5 high-resolution 300-DPI publication figures.
7. **`07_Manuscript/`**: Full APA 7th Edition manuscript (`Manuscript_Draft_v1.docx` and `.md`; 10,782 words, 10 tables, 54 references, Appendix 1), cover letter, and submission guidelines targeted for *Journal of Building Engineering* (Elsevier).
8. **`08_Supplements/`**: PRISMA 2020 item-by-item verification checklist and completed flow diagrams.

## Methodological Standards & Tools
- **Reporting Standard:** PRISMA 2020 Statement.
- **Quality Appraisal:** Joanna Briggs Institute (JBI) Critical Appraisal Checklists and ISO 14040/44 LCA reporting framework.
- **Data Provenance:** Open Science Framework (OSF) & Zenodo (CERN).
- **Target Journal:** *Journal of Building Engineering* (Elsevier, IF 6.4, unsolicited review articles accepted).
