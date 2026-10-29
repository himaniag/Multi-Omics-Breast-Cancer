# Data

All datasets used in this study are public. The five files below are included in this folder and in the Zenodo record (https://doi.org/10.5281/zenodo.23756025) so that the analysis can be re-run directly. They are the exports listed in Table 1 of the manuscript and cited there as references [67]–[71].

| File | Source | Content | Role in the study |
|---|---|---|---|
| `METABRIC_RNA_Mutation.csv` | [Kaggle: Breast Cancer Gene Expression Profiles (METABRIC)](https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric) | 1,904 patients × 693 columns: 489 mRNA z-scores, 173 somatic-mutation genes, 31 clinical fields | Primary modelling cohort (core-4 PAM50, n = 1,559) |
| `Breast_Cancer_METABRIC.csv` | [Kaggle: Breast Cancer (METABRIC)](https://www.kaggle.com/datasets/gunesevitan/breast-cancer-metabric) | 1,985 patients × 34 columns: clinical export including relapse-free survival | Linked by patient ID (1,904 matched); relapse-free survival endpoint; PAM50 label concordance 100.0% |
| `brca_metabric_clinical_data.csv` | [cBioPortal: Breast Cancer (METABRIC)](https://www.cbioportal.org/study/summary?id=brca_metabric) | 1,540 patients × 39 columns: cBioPortal clinical export including TMB | Linked (1,500 matched); label cross-check (concordance 100.0%) |
| `brca_data_w_subtypes_tcga.csv` | [Kaggle: BRCA Multi-Omics (TCGA)](https://www.kaggle.com/datasets/samdemharter/brca-multiomics-tcga) | 705 patients × 1,941 columns: RNA-seq (604 genes), mutation (249), CNV (860), RPPA (223), ER/PR/HER2 IHC | Independent external cohort (IHC-surrogate labels, n = 506) |
| `clinical - clinical_tcga.csv` | [NCI Genomic Data Commons: TCGA-BRCA](https://portal.gdc.cancer.gov/projects/TCGA-BRCA) | 5,546 rows / 1,098 cases: GDC clinical, demographic and treatment records | External-cohort characterisation (not patient-linked) |

**File names matter.** The notebook finds each file by these name patterns: `METABRIC_RNA_Mutation`, `Breast_Cancer_METABRIC`, `brca_metabric_clinical_data`, `brca_data_w_subtypes_tcga` and `clinical_tcga`. Keep the underscores, for example `Breast_Cancer_METABRIC.csv` and not `Breast Cancer METABRIC.csv`.

Original studies: METABRIC — Curtis et al., *Nature* 2012; Pereira et al., *Nature Communications* 2016. TCGA-BRCA — Cancer Genome Atlas Network, *Nature* 2012.

Use of each dataset is subject to the terms of its provider.
