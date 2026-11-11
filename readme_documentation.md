# Udai Pareek Socioeconomic Status (SES) Scale Calculator (2021 Update)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24131761.svg)](https://doi.org/10.5281/zenodo.24131761)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/Version-2026.1-blue.svg)](https://github.com/)

An interactive, responsive single-page web application and companion automated Excel model for computing household socioeconomic status using the **Udai Pareek Scale for Rural Communities**, updated for 2021 norms.

---

## 🌟 Key Features

* **Complete 9-Dimension Scoring:** Implements all dimensions from the Udai Pareek framework:
  1. Caste
  2. Occupation
  3. Social Participation
  4. House Type
  5. Farm Power
  6. Education of Head of Household
  7. Landholding
  8. Material Possessions
  9. Family Members (Household Size)
* **2021 Classification Norms:** Automatic grading into the 5 standard socioeconomic classes based on raw scores (Max: 47):
  * **Class I (Upper):** $> 42$ (43–47)
  * **Class II (Upper Middle):** $33 - 42$
  * **Class III (Middle):** $24 - 32$
  * **Class IV (Lower Middle):** $13 - 23$
  * **Class V (Lower):** $< 13$ (0–12)
* **Privacy & Client-Side Execution:** Zero tracking, cookies, or remote server transmission. All scoring executes locally inside the browser.
* **Dual Deliverables:** Includes both the standalone browser application (`index.html`) and an automated Microsoft Excel workbook (`Udai_Pareek_SES_Calculator_2021.xlsx`) with batch data validation and survey scoring.

---

## 🚀 Live Demo & Usage

Open `index.html` in any modern web browser or visit the live deployment hosted via GitHub Pages:
`https://<your-username>.github.io/udai-pareek-ses-calculator/`

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| `index.html` | Interactive browser application with live score calculation, printable reports, and citation copy tools. |
| `Udai_Pareek_SES_Calculator_2021.xlsx` | Multi-sheet Excel calculator featuring single-case and batch entry lookup forms. |
| `CITATION.cff` | Machine-readable citation metadata for automated GitHub and Zenodo attribution. |
| `LICENSE` | Creative Commons Attribution 4.0 International (`CC BY 4.0`) license terms. |
| `.gitignore` | Ignores temporary operating system and Excel lock files. |

---

## 📖 How to Cite

If you use this calculator, dataset template, or software code in your research, community field survey, or publications, please cite both the software tool and the background research paper:

### 1. Software Tool Citation
> Alphonso, R. (2026). *Udai Pareek Socioeconomic Status Scale Automated Calculator* (Version 2026.1) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.24131761

```bibtex
@software{alphonso2026udaipareek,
  author       = {Alphonso, Rachael},
  title        = {Udai Pareek Socioeconomic Status Scale Automated Calculator},
  version      = {2026.1},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.24131761},
  url          = {https://doi.org/10.5281/zenodo.24131761}
}
```

### 2. Foundational Research Citations
* **2021 Revision:**
  > Majumder, S. (2021). Socioeconomic status scales: Revised Kuppuswamy, BG Prasad, and Udai Pareek’s scale updated for 2021. *Journal of Family Medicine and Primary Care*, 10(11), 3964–3967. https://doi.org/10.4103/jfmpc.jfmpc_600_21
* **Original Scale:**
  > Pareek, U., & Trivedi, G. (1965). Factor Analysis of Socioeconomic Status of Farmers in India. *Rural Sociology*, 30(3), 311–321.

---

## 📄 License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. You are free to share and adapt the material, provided appropriate credit is given to the author.