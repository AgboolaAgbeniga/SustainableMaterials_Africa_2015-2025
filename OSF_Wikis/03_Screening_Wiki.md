# Component Wiki: 03_Screening

**Component URL:** [https://osf.io/dvukp/files/osfstorage](https://osf.io/dvukp/) (Target Folder: `03_Screening`)  
**Lead Author:** Agbeniga Agboola ([ORCID: 0009-0005-6878-1661](https://orcid.org/0009-0005-6878-1661))  
**Unique Records Screened:** 7,283 records  
**Records Excluded:** 4,461 records  
**Full-Text Studies Eligible:** 2,822 studies  

---

## 1. Scope & Two-Stage Screening Protocol
This component provides the transparent audit trail of study selection, tracking decisions across the two-stage screening process in strict compliance with the PRISMA 2020 Statement.

### Stage 1: Title and Abstract Screening
The titles, abstracts, and keywords of all **7,283 unique records** were screened against predefined eligibility criteria:
* **Eligible Studies:** Empirical, laboratory, or field investigations on sustainable building materials in African sovereign nations published between 2015 and 2025.
* **Excluded Studies (n = 4,461):** Excluded studies were systematically coded with explicit exclusion reason tags:
  1. `EX-GEO` (Non-African Geographic Context): Studies conducted outside Africa without African feedstock, soil, or climatic relevance (n = 1,842).
  2. `EX-MAT` (Out-of-Scope Materials): Studies on agricultural fertilizers, water filtration membranes, medical biomaterials, unreinforced road asphalt, or battery electrodes (n = 1,328).
  3. `EX-THEORY` (Non-Empirical / Opinion): Purely narrative opinions, speculative editorials, policy commentaries without primary lab data, or unvalidated mathematical models (n = 894).
  4. `EX-DUP` (Duplicate / Preliminary): Redundant preliminary conference abstracts superseded by full journal publications (n = 397).

### Stage 2: Full-Text Eligibility Appraisal
Full texts of the remaining **2,822 candidate records** were retrieved and evaluated for empirical data completeness. Studies were required to report quantitative mechanical metrics (compressive strength, flexural strength), physical metrics (density, water absorption), chemical compositions (XRF, XRD), or life-cycle environmental indicators (embodied carbon, embodied energy). All 2,822 empirical studies met the rigorous eligibility criteria and advanced to data extraction.

---

## 2. File Schema & Registers

| File Name | Format | Purpose & Description | Record Count |
| :--- | :---: | :--- | :---: |
| **`TitleAbstract_ScreeningLog.xlsx`** | Excel | Master screening register containing all unique records with reviewer inclusion/exclusion decisions and standardized reason codes. | 7,283 records |
| **`FullText_ScreeningLog.xlsx`** | Excel | Detailed eligibility register of all retrieved full-text candidates confirmed for inclusion. | 2,822 records |
| **`Screening_Audit_Summary_2026-09-15.xlsx`** | Excel | Cross-tabulated statistical breakdown of screening decisions by database source, year, and exclusion category. | Summary sheet |

---

## 3. PRISMA 2020 Flow Reconciliation
The screening decisions in this component mathematically reconcile the PRISMA 2020 Flow Diagram (`06_Analysis/Figures/Fig1_PRISMA_2020_Flow_Diagram.png`):

$$\begin{aligned}
\text{Raw Identified Citations: } & 9,112 \\
- \text{ Duplicate Records Removed: } & 1,829 \\
\hline
\text{Net Unique Records Screened: } & 7,283 \\
- \text{ Title/Abstract Excluded: } & 4,461 \\
\hline
\text{Included Empirical Studies: } & \mathbf{2,822}
\end{aligned}$$
