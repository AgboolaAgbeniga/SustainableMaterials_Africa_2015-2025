# Component Wiki: 02_SearchLogs

**Component URL:** [https://osf.io/dvukp/files/osfstorage](https://osf.io/dvukp/) (Target Folder: `02_SearchLogs`)  
**Lead Author:** Agbeniga Agboola ([ORCID: 0009-0005-6878-1661](https://orcid.org/0009-0005-6878-1661))  
**Total Raw Citations Captured:** 9,112 records  
**Duplicates Eliminated:** 1,829 records  
**Net Unique Records:** 7,283 records  

---

## 1. Scope & Multi-Database Architecture
This component documents the complete literature search strategy across international and regional scholarly indexes. To minimize indexing and geographic bias, electronic searches were conducted across four primary databases:

| Database / Information Source | Citations Captured | Search Methodology & Target Scope | Output File |
| :--- | :---: | :--- | :--- |
| **Google Scholar** | 5,747 | Automated scraping using 5 thematic Boolean queries covering grey literature, African institutional repositories, and university theses. | `SearchLog_Master.csv` |
| **OpenAlex Scholarly API** | 2,802 | 6 standardized queries combining materials taxonomy, civil engineering terms, and African sovereign country ISO codes across 250M+ global scholarly works. | `OpenAlex_Results_2026-09-15.csv` |
| **Directory of Open Access Journals (DOAJ)** | 419 | Querying open-access, peer-reviewed engineering journals under rigorous quality control standards. | `DOAJ_Results_2026-09-15.csv` |
| **African Journals Online (AJOL)** | 144 | Filtered corpus of 123,571 publications published in peer-reviewed African national and university journals (Alonso-Álvarez, 2025). | `AJOL_Results_2026-09-15.csv` |
| **Total Raw Identification** | **9,112** | **Exhaustive Decadal Search Base (2015–2025)** | **`SearchLog_Master.csv`** |

---

## 2. Master Search Log Structure
The master log (`SearchLog_Master.csv`) contains the aggregated raw bibliographic records with the following standardized column schema:
- `ID`: Unique numeric citation identifier.
- `Database`: Source engine (Google Scholar, OpenAlex, DOAJ, AJOL).
- `Query_String`: Specific Boolean search string utilized.
- `Title`: Full scholarly title of the publication.
- `Authors`: Complete author string as indexed in the source engine.
- `Year`: Publication year (restricted to 2015–2025).
- `Venue`: Journal name, conference proceeding title, or institutional repository monograph.
- `DOI`: Digital Object Identifier (where available).
- `URL`: Direct permanent web link to publication record.
- `Abstract`: Full author abstract.

---

## 3. Algorithmic Deduplication Pipeline (`Deduplication_Summary_2026-09-15.xlsx`)
Because citations were harvested across overlapping multi-database sources, an automated Python deduplication script was executed:
1. **Stage 1 (Exact Deduplication):** Identical matching on digital object identifiers (DOIs), standardized title strings (lowercased, punctuation stripped, whitespace collapsed), and matching author-year pairs.
2. **Stage 2 (Fuzzy Levenshtein Deduplication):** For records lacking DOIs, title strings were evaluated using normalized Levenshtein edit distance. Pairs achieving a similarity score $\ge$ 0.90 combined with matching publication years and overlapping author surnames were audited and merged.

**Deduplication Results:**
- Raw Citations Identified: **9,112**
- Duplicate Records Removed: **1,829**
  - *Google Scholar duplicates:* 1,180
  - *OpenAlex duplicates:* 542
  - *DOAJ duplicates:* 87
  - *AJOL duplicates:* 20
- Net Unique Records Advancing to Screening: **7,283**
