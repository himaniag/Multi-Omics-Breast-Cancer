# Submission package — SN Computer Science

**Multi-Omics Breast Cancer Subtype Classification Using TRIAD-BRCA+: A Leakage-Aware Ensemble Learning Framework**
Himani Agrawal (corresponding author, agrawal.himani1010@gmail.com) and Megha Rathi
Department of CSE & IT, Jaypee Institute of Information Technology, Noida, India

Code and data: https://github.com/himaniag/Multi-Omics-Breast-Cancer · DOI: https://doi.org/10.5281/zenodo.23756025

## Contents

| Folder | Contents | Where it goes |
|---|---|---|
| `01_Manuscript` | Manuscript as Word (`.docx`) and PDF — identical content | Upload the Word file (or the LaTeX source) as the manuscript; the PDF is the reference copy |
| `02_Title_Page` | Title page (`.docx`) with authors, affiliations and all declarations | "Title page" |
| `03_Cover_Letter` | Cover letter to the Editor-in-Chief (`.docx`) | "Cover letter" |
| `04_Online_Resource_1` | Online Resource 1 (`.pdf`): Supplementary Tables S1–S15 and Figures S1–S11 | "Electronic supplementary material" |
| `05_Figures/Main` | Figs. 1–6 as separate high-resolution PNG files | One "Figure" item per file, if figures are requested separately |
| `05_Figures/Supplementary` | Figs. S1–S11 (already inside Online Resource 1) | Repository / reviewers |
| `06_Tables/Main` | Tables 1–10 as CSV, with `Table_captions_and_notes.csv` | Data copies; the tables themselves are inside the manuscript |
| `06_Tables/Supplementary` | Tables S1–S15 as CSV, with `Table_captions_and_notes.csv` | Data copies of the tables in Online Resource 1 |
| `06_Tables/All_Tables_Multi-Omics_Breast_Cancer.xlsx` | All 25 tables in one workbook (index sheet + one sheet per table, with captions and notes) | Repository / reviewers |
| `07_LaTeX_Source` | LaTeX source of the manuscript (`manuscript.tex`, `body.tex`, `refs.tex`, `tables/`, `figs/`); tables also as CSV in `tables/csv/` | Compile with `pdflatex manuscript.tex` (run twice) |
| `08_GitHub_Repository_Updates` | Updated README, CITATION.cff, licences, figure/table index and folder READMEs for the GitHub repository | Upload into the GitHub repository (keep folder paths) |

## Notes

- Tables in the manuscript are editable tables (Word) / LaTeX tables; the CSV and Excel files contain exactly the same values.
- References: 90, numbered in order of citation. Eight dated references were replaced by verified 2024–2026 publications ([5], [6], [8], [15], [16], [18], [52], [56]); citation numbers in the text are unchanged.
- Equations in the Word file are native Word equations, numbered (1)–(11).
- GitHub: after uploading the files in `08_GitHub_Repository_Updates`, rename `data/Breast Cancer METABRIC.csv` to `data/Breast_Cancer_METABRIC.csv` in the repository so that the notebook finds it.
