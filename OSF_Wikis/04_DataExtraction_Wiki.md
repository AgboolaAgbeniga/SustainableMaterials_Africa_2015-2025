# Component Wiki: 04_DataExtraction

**Component URL:** [https://osf.io/dvukp/files/osfstorage](https://osf.io/dvukp/) (Target Folder: `04_DataExtraction`)  
**Lead Author:** Agbeniga Agboola ([ORCID: 0009-0005-6878-1661](https://orcid.org/0009-0005-6878-1661))  
**Master Extraction File:** `Extraction_Completed_Master.xlsx`  
**Dataset Scale:** 2,492 primary empirical studies $\times$ 31 standardized fields  

---

## 1. Scope & Relational Database Architecture
This component houses the core empirical database of the systematic review. Data from all 2,492 eligible peer-reviewed studies were extracted into a structured 31-parameter relational matrix, capturing bibliographic metadata, geographic and climatic context, material taxonomy, laboratory experimental designs, physical/mechanical benchmarks, environmental indicators, and socio-economic adoption barriers.

---

## 2. The 29 Standardized Extraction Fields

The master spreadsheet `Extraction_Completed_Master.xlsx` contains the following 29 data columns:

### Section A: Bibliographic Identifiers
1. `ID`: Unique numeric study identifier (1 to 2,492).
2. `Author`: Primary author(s) string.
3. `Year`: Publication year (2015 to 2025).
4. `Title`: Full scholarly title.
5. `Journal/Source`: Publishing journal, conference venue, or institutional repository.
6. `DOI`: Digital Object Identifier with active hyperlink.

### Section B: Geographic & Environmental Context
7. `Country`: Sovereign African territory of the study or raw material feedstock.
8. `Region`: African geographical sub-region (West, East, Southern, North, Central, or Pan-African).
9. `Climate Context`: Köppen-Geiger climatic zone (Tropical Wet, Semi-Arid Sahelian, Mediterranean, Subtropical Highland).

### Section C: Material Taxonomy & Processing
10. `Material Class`: Primary classification (Earth-based, Low-carbon binder, Recycled/Waste, Bio-based, Smart/Innovative).
11. `Material Specification`: Granular material description (e.g., CSEB with 6% OPC, LC3-50 Concrete, RHA-modified mortar, structural bamboo culm).
12. `Study Aim`: Core research hypothesis or engineering objective.
13. `Study Design`: Experimental laboratory trial, prototype field testing, LCA, or microstructural investigation.
14. `Methods Summary`: Batching ratios, water-binder ratios, compaction pressures, and curing regimes.
15. `Sample Size`: Number of replicate specimens tested per experimental variable.
16. `Duration`: Curing duration and testing time points (e.g., 7, 14, 28, 56, 90 days).
17. `Scale`: Production scale (manual hand compaction, semi-automated hydraulic press, ready-mix batching).

### Section D: Quantitative Performance Metrics
18. `Technical Metrics`: 28-day Compressive Strength (MPa), Flexural/Tensile Strength (MPa), Dry Density (kg/m³), Water Absorption (%), and Thermal Conductivity (W/m·K).
19. `Environmental Metrics`: Embodied carbon (kg CO₂-eq/m³ or % reduction), Embodied Energy (MJ/m³), LCA system boundary (cradle-to-gate, cradle-to-site).
20. `Economic Metrics`: Unit material cost per m² or m³, relative cost savings versus conventional baselines.
21. `Social/Practical Notes`: Documented artisan workability, local material availability, social acceptance notes.
22. `Comparator`: Baseline reference material (e.g., 100% Ordinary Portland Cement concrete, artisanal sandcrete hollow blocks).
23. `Standards Referenced`: Engineering testing standards followed (e.g., ASTM C618, BS EN 197-1, ARS 680–684, NIS 87).

### Section E: Synthesis, Rigor & Quality
24. `Key Findings`: Primary quantitative empirical conclusions.
25. `Limitations`: Declared experimental constraints (e.g., absence of long-term durability testing, small specimen sizes).
26. `Funding Declared`: Declared funding agencies, university grants, or zero-funding declarations.
27. `Data Availability`: Statement indicating whether raw experimental datasets were made openly accessible.
28. `Ethics Approval`: Institutional laboratory safety and ethical compliance declarations.
29. `Quality Tool Used`: Joanna Briggs Institute (JBI) Critical Appraisal tool identifier.

---

## 3. Dataset Distribution Summary
- **Low-Carbon Binders & SCMs:** 995 studies (35.3%)
- **Earth-Based Masonry:** 884 studies (31.3%)
- **Recycled & Industrial Waste Composites:** 444 studies (15.7%)
- **Renewable Bio-Based Materials:** 358 studies (12.7%)
- **Smart & Innovative Building Systems:** 141 studies (5.0%)
- **Total Validated Studies:** **2,492 studies (100.0%)**
