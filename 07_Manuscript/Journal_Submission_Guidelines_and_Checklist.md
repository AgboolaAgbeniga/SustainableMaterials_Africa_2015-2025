# Journal Submission Strategy & Peer-Review Management Manual

**Manuscript Title:** Sustainable Building Materials in Africa (2015–2025): A Systematic Evidence Synthesis of Material Classes, Technical Performance, and Implementation Contexts  
**Lead Author:** Agbeniga Agboola ([ORCID: 0009-0005-6878-1661](https://orcid.org/0009-0005-6878-1661) | [emmanuelagbeniga@gmail.com](mailto:emmanuelagbeniga@gmail.com))  
**Affiliation:** Independent Researcher and Civil / Site Engineer  
**Registered Protocol (OSF):** [https://osf.io/dvukp/](https://osf.io/dvukp/)  
**Permanent Repository DOI:** [10.5281/zenodo.22771539](https://doi.org/10.5281/zenodo.22771539)  

---

## 1. Target Journal Strategic Evaluation

Selecting the appropriate journal is a critical editorial decision. Submitting an unsolicited review to an invitation-only journal guarantees immediate administrative desk rejection, regardless of scientific quality.

### Journal Comparison Matrix

| Journal Name | Publisher | Impact Factor / CiteScore | Editorial Policy on Review Articles | Scope Alignment with This Review | Recommended Submission Status |
| :--- | :---: | :---: | :--- | :--- | :---: |
| ***Journal of Building Engineering* (JOBE)** | Elsevier | **IF: 6.4**<br>CiteScore: 11.2 | **Accepts unsolicited review articles** demonstrating significant scientific novelty in building engineering. | Explicitly covers sustainable building materials, durability, smart materials, and whole life-cycle performance. | **PRIMARY TARGET (Recommended)** |
| ***Sustainable Materials and Technologies* (SMT)** | Elsevier | **IF: 8.6**<br>CiteScore: 17.5 | **Accepts unsolicited comprehensive reviews** on sustainable materials, circular economy, and low-carbon cementitious systems. | High alignment with our LC3, agro-waste pozzolan, and life-cycle assessment (LCA) datasets. | **STRONG ALTERNATIVE** |
| ***Cleaner Materials*** | Elsevier | **IF: 5.2**<br>CiteScore: 6.8 | Open Access sister journal to *Journal of Cleaner Production*. Fast peer review for circular construction materials. | Direct match for waste-derived composites, earth blocks, and decarbonization roadmaps. | **FAST-TRACK ALTERNATIVE** |
| ***Construction and Building Materials* (CBM)** | Elsevier | **IF: 8.0**<br>CiteScore: 14.2 | **INVITATION ONLY:** *"Construction and Building Materials only publishes review articles on priority topics invited by the editors."* | High technical match, but **unsolicited submissions risk immediate desk rejection**. | **REQUIRES PRE-SUBMISSION INQUIRY** (Do not submit directly without editor invitation) |

### Key Strategic Recommendation:
1. **Primary Target:** Submit directly to **_Journal of Building Engineering_ (Elsevier)** as an unsolicited Review Article. Emphasize in the cover letter how the manuscript delivers a novel continental synthesis across physical, mechanical, life-cycle, and regulatory dimensions rather than merely summarizing counts.
2. **If targeting CBM:** Send a formal **Pre-Submission Editorial Inquiry** to the Editor-in-Chief proposing the review topic and citing our registered OSF protocol before submitting through Editorial Manager.

---

## 2. Research Architecture & Evidence Traceability Audit

To withstand rigorous peer review, every numerical claim in the manuscript must be directly verifiable through an unbroken audit trail:

```
[OSF Open-Ended Registration] (Protocol baseline; Sept 24, 2025)
       │
       ▼
[02_SearchLogs/] ──> Raw Identification: 9,112 citations (Google Scholar, OpenAlex, DOAJ, AJOL)
       │
       ▼
[Deduplication Pipeline] ──> 1,829 duplicates eliminated (514 exact DOI + 1,315 Levenshtein distance >= 0.90)
       │
       ▼
[03_Screening/Stage 1] ──> 7,283 unique records screened
       │                   └── 4,461 excluded (EX-MAT: 4,311; EX-GEO: 148; EX-TYPE: 2)
       ▼
[03_Screening/Stage 2] ──> 2,822 candidate records retrieved for full text
       │                   └── 330 excluded (EX-DOCTYPE: 231; EX-GEO: 84; EX-MAT: 13; EX-LANG: 2)
       ▼
[04_DataExtraction/] ──> 2,492 primary empirical studies extracted across 31 relational variables
       │
       ▼
[05_QualityAppraisal/] ──> Multi-tool quality appraisal across 5 study designs:
       │                   ├── JBI Quasi-Experimental (n = 2,251: 2,062 lab + 168 microstructural + 21 prototype)
       │                   ├── JBI Analytical Cross-Sectional (n = 137 surveys)
       │                   └── ISO 14040/14044 (n = 104 LCA studies)
       │                   └── 24.7% Low Risk (n = 615); 75.3% Moderate Risk (n = 1,877)
       ▼
[06_Analysis/] ──> 8 Synthesis Tables & 5 High-Resolution Publication Figures (300 DPI)
       │
       ▼
[07_Manuscript/] ──> Publication Draft (10,782 words, 10 tables, 54 verified references, Appendix 1)
       │
       ▼
[Zenodo / GitHub Archive] ──> Permanent DataCite preservation (DOI: 10.5281/zenodo.22771539)
```

---

## 3. Elsevier Editorial Manager Step-by-Step Submission Protocol

### A. Pre-Submission Checklist

Before logging into Elsevier Editorial Manager for *Journal of Building Engineering*:

1. **Primary Files Prepared:**
   - [x] **Manuscript File:** `07_Manuscript/Manuscript_Draft_v1.docx` (Single Word document containing title, abstract, body, tables, declarations, references, and Appendix 1).
   - [x] **Cover Letter:** `07_Manuscript/Cover_Letter_and_Highlights.docx` (Addressed to Editor-in-Chief of JOBE).
   - [x] **Highlights:** 5 bullet points ($\le$ 85 characters each, formatted in `Cover_Letter_and_Highlights.docx`).
   - [x] **CRediT Author Statement:** Embedded in manuscript and cover letter.
   - [x] **Standalone High-Resolution Figures:**
     - `06_Analysis/Figure1_PRISMA2020_FlowDiagram.png` (300 DPI)
     - `06_Analysis/Figure2_Geographic_Distribution_Heatmap.png` (300 DPI)
     - `06_Analysis/Figure3_Material_Taxonomy_Distribution.png` (300 DPI)
     - `06_Analysis/Figure4_Compressive_Strength_Benchmarks.png` (300 DPI)
     - `06_Analysis/Figure5_Embodied_Carbon_Decarbonization.png` (300 DPI)
   - [x] **Supplementary Materials:** `08_Supplements/PRISMA_2020_Checklist.docx`.

2. **Metadata Fields Required during Portal Entry:**
   - **Article Type:** Select `Review Article` (or `Full Length Review`).
   - **Section / Category:** Select `Sustainable Building Materials` or `Cement and Concrete Technology`.
   - **Title:** `Sustainable Building Materials in Africa (2015–2025): A Systematic Evidence Synthesis of Material Classes, Technical Performance, and Implementation Contexts`
   - **Abstract:** Copy-paste the 300-word structured abstract from `07_Manuscript/Manuscript_Draft_v1.md`.
   - **Keywords:** `Sustainable building materials; Africa; PRISMA 2020; Compressed stabilized earth blocks; LC3 cement; Agro-waste pozzolans; Structural bamboo; Life cycle assessment; JBI quality appraisal; Implementation barriers.`
   - **Author Details:**
     - First Name: `Agbeniga`
     - Last Name: `Agboola`
     - Affiliation: `Independent Researcher and Civil / Site Engineer`
     - E-mail: `emmanuelagbeniga@gmail.com`
     - ORCID: `0009-0005-6878-1661`

3. **Data Availability Statement:**
   Select: *"The data that support the findings of this study are openly available in the Open Science Framework at https://osf.io/dvukp/ and permanently archived on Zenodo at https://doi.org/10.5281/zenodo.22771539."*

---

## 4. Peer-Review Defense & Rebuttal Strategy

To ensure rapid passage through peer review, the manuscript has been structured to address the four most common critiques in civil engineering systematic reviews:

1. **Critique: "Why was a single-reviewer screening workflow used?"**
   - *Pre-emptive defense in Section 2.5:* Disclosed transparently in accordance with PRISMA 2020 Item 8. Screening utilized explicit, predefined decision rules, automated Python deduplication scripts, and a blinded 10% re-screening audit achieving $\kappa = 0.95$ ($P_o = 98.4\%$).
2. **Critique: "Why was the search conducted in Scholar, OpenAlex, DOAJ, and AJOL rather than Scopus/WoS?"**
   - *Pre-emptive defense in Section 2.1 & Appendix 1:* Disclosed as an intentional protocol adjustment. The search was operationalized using open and regional information sources to increase coverage of African and openly accessible scholarly literature. Utilizing AJOL, DOAJ, and OpenAlex ensured capturing peer-reviewed African scholarship and institutional repositories across all 54 African countries.
3. **Critique: "How was Risk of Bias evaluated across disparate study designs?"**
   - *Pre-emptive defense in Section 2.7 & 4.1:* Explaining why design-appropriate tools were deployed across 5 explicit study designs: the JBI Quasi-Experimental tool for physical engineering studies (n = 2,251: 2,062 lab + 168 microstructural + 21 prototype), the JBI Analytical Cross-Sectional tool for surveys (n = 137), and ISO 14040/14044 for LCA studies (n = 104), acknowledging the high prevalence of statistical variance under-reporting (only 51.7% weighted overall reporting standard deviations or ANOVA).
4. **Critique: "Why are bamboo and earth blocks not widely used if they perform well in tests?"**
   - *Pre-emptive defense in Section 4.2 & 4.3:* Grounded in data from 137 adoption studies, analyzing the socio-technical realities, informal market economics, and prescriptive building codes that create barriers to adoption.
