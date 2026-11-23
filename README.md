# CV Job Matching — NLP Project

## Overview

An NLP-based system designed to extract relevant information from CVs, normalize candidate skills, and evaluate the compatibility between candidates and job offers.

The project combines Named Entity Recognition (NER), semantic similarity, explainable matching, robustness evaluation, and fairness auditing.

## Objectives

- Extract entities from CVs: skills, organizations, degrees, dates, and job positions.
- Compare spaCy and fine-tuned CamemBERT for Named Entity Recognition.
- Normalize extracted skills using semantic embeddings.
- Calculate explainable CV-job matching scores.
- Evaluate ranking quality.
- Test robustness to multilingual content and textual noise.
- Audit and mitigate potential fairness biases.

## Technologies

- Python
- spaCy
- Hugging Face Transformers
- CamemBERT
- Sentence Transformers
- Scikit-learn
- Pandas / NumPy
- Label Studio
- Jupyter Notebook

## Project Structure

```text
cv-job-matching-nlp/
├── data/
├── notebooks/
├── src/
├── models/
├── reports/
├── README.md
└── .gitignore
```

## Project Status

In development — Academic NLP project.

## Dataset

The project uses fictional CVs generated with Python and fictional job offers. All personal information is synthetic.

## Evaluation

NER performance: Precision, Recall and Entity-level F1-score.

Skill normalization: Accuracy@1 and Accuracy@3.

Ranking: Spearman correlation, Kendall Tau and NDCG.

Fairness and robustness: comparative experiments and sensitivity analysis.

## Authors

Academic project — 5th-year engineering students.