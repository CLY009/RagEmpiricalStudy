# Demystifying Configuration Issues in Retrieval-Augmented Generation Systems: A Taxonomy and Empirical Study

This repository contains dataset for the empirical study on **Demystifying Configuration Issues in Retrieval-Augmented Generation Systems: A Taxonomy and Empirical Study**.

The dataset includes **654 real-world configuration issues** collected from 10 representative open-source RAG systems. It provides a comprehensive dataset of how configuration issues manifest (Symptoms), where they originate (Root Causes), how they propagate (Diagnosis Gap), and how they are resolved (Fix Patterns).

## 📂 Repository Structure

To align directly with the Research Questions in our paper, the dataset is organized as follows:

```text
.
├── rag_configuration_issues.csv   # The master dataset containing all 654 issues and full annotations.
│
├── rq1_symptoms/                  # [N=654] Data for RQ1 (Symptom manifestation and stages).
├── rq2_root_causes/               # [N=654] Data for RQ2 (Root cause and stages).
├── rq3_impact/                    # [N=654] Data for RQ3 (Stage Gap and Resolving Costs).
└── rq4_solutions/                 # [N=345] Data for RQ4 (Fix Patterns). Filtered to only include issues with Pull Requests.
```
