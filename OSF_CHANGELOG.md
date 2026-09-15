# OSF Project Change Log & Component Audit

**Project Title:** Sustainable Building Materials in Africa (2015–2025): A Rapid Systematic Review  
**Lead Researcher:** Agbeniga Agboola  
**Frameworks:** PRISMA 2020 Statement | Open Science Framework (OSF)  
**Date of Log:** 2025-10-15  

---

## Summary of Modifications & Component Updates

This log provides an audit trail of all repository structures, search expansions, protocol standardizations, and data registers established for OSF synchronization.

---

### 1. Component: 01_Protocol
- **Standardization:** Consolidated the registered protocol PDF (`Protocol_Sustainable_Materials_Africa_2015-2025_v1.pdf`) into `01_Protocol/` to ensure all protocol revisions remain centralized.
- **Protocol Fidelity:** Confirmed inclusion/exclusion criteria (PICO/CCo): peer-reviewed empirical studies published in English between 2015 and 2025 focusing on sustainable/alternative building materials in African nations.

---

### 2. Component: 02_SearchLogs (Multi-Database Expansion)
- **Search Expansion (AJOL):**
  - **Source:** African Journals Online (AJOL) structured database (Alonso-Álvarez, 2025, Zenodo DOI: `10.5281/zenodo.14899380`).
  - **Scope:** Parsed 123,571 publication records (2015–2025) across peer-reviewed African national and university journals.
  - **Filtering:** Applied materials taxonomy filter (laterite, compressed earth, rammed earth, bamboo, low-carbon cement, agro-waste pozzolanic ashes, recycled aggregate, plastic waste in concrete) and civil engineering/construction context filtering.
  - **Output:** Exported 144 curated empirical records into `02_SearchLogs/AJOL_Results_2025-10-15.csv`.
- **Search Log Consolidation:**
  - Standardized search documentation into `02_SearchLogs/SearchLog_Master.csv` (and `.xlsx`), indexing Strings 1 to 6 (Google Scholar, 5,747 hits) and String 7 (AJOL, 144 hits), totaling **5,891 raw citations identified**.

---

### 3. Component: Repository Structure & Version Control
- **Git Architecture:** Initialized Git version control on branch `main` with detailed, structured commit history.
- **Data Hygiene (.gitignore):**
  - Excluded external raw 75 MB reference database dumps (`resources/`) from Git tracking to preserve a lightweight, fast-cloning repository (< 5 MB) that strictly reflects the 8-folder OSF structure.
  - Excluded Microsoft Office temporary lock files (`~$*`), Python runtime caches, and IDE artifacts.
- **Documentation:**
  - Created root `README.md` with PRISMA 2020 and OSF badges, directory navigation, and citation metadata.
  - Created `IMPLEMENTATION_PLAN.md` detailing the complete phase-by-phase execution roadmap.
  - Created `architecture.md` and `index.json` representing the project's structural data flow.

---

### 4. Current State in the PRISMA 2020 Flow Pipeline
```
[Phase 1: Information Sources]
  ├── Google Scholar (Strings 1-6): 5,747 hits (Completed)
  ├── AJOL (African Journals Online):   144 hits (Completed)
  ├── OpenAlex (Global Open Scholarly): PENDING EXECUTION
  └── DOAJ (Directory of Open Access):  PENDING EXECUTION

[Phase 2: Master Deduplication]
  └── Scheduled to run immediately upon conclusion of OpenAlex & DOAJ searches.

[Phase 3: Two-Stage Screening]
  ├── Stage 1: Title & Abstract Screening (Pending)
  └── Stage 2: Full-Text Retrieval & Reason-Coded Exclusion (Pending)
```

---

## Instructions for OSF Web Interface Update
1. Open your OSF Project Dashboard.
2. In the **`02_SearchLogs`** component:
   - Upload `SearchLog_Master.csv` (or replace the existing search log).
   - Upload `AJOL_Results_2025-10-15.csv`.
3. In the project root / wiki:
   - Upload or paste this `OSF_CHANGELOG.md` to document the update for public transparency.
