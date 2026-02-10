# HEARTS Baseline Reproduction & Hate-Speech Adaptation

## Key Files for Review

| File | Description |
|------|------------|
| `Adapted-HateSpeech.ipynb` | Reproducible notebook of adapted model applied to hate-speech dataset with evaluation |
| `Reproduced_HEARTS_Baseline.ipynb` | Notebook for baseline model reproduction |
| `Exploratory_GOVUK_Baseline_Failed.ipynb` | Early experimental notebook showing unsuccessful baseline attempt (included for transparency) |
| `README.md` | Project overview and instructions |


## Overview

This repository contains coursework exploring the **reproduction and adaptation of the HEARTS Text Stereotype Detection baseline models** for hate-speech classification tasks.  

The project focuses on:
- Reproducing original baseline performance  
- Adapting the model to a hate-speech dataset  
- Evaluating results using standard NLP classification metrics  
- Ensuring notebooks are **reproducible** and runnable top-to-bottom  

---
## Repository Structure

```
.
├── Reproduced_HEARTS_Baseline.ipynb
├── Adapted-HateSpeech.ipynb
├── Exploratory_GOVUK_Baseline_Failed.ipynb
│
├── cleanedData.csv
├── rawData.csv
│
├── y_true.npy
├── y_pred_baseline.npy
├── y_pred_adapted.npy
│
├── eval_results.json
├── eval_results_hatespeech.json
├── govuk_eval_results.json
├── govuk_train_results.json
│
├── albert_hatespeech_model.zip (optional – large file)
│
└── README.md
```

---

## Notebooks

### `Reproduced_HEARTS_Baseline.ipynb`
- Reproduces outputs from the original HEARTS baseline models  
- Loads saved model results  
- Generates classification reports and confusion matrices  
- Designed for **Kernel → Restart & Run All**

### `Adapted-HateSpeech.ipynb`
- Applies the baseline architecture to a hate-speech dataset  
- Compares baseline vs adapted predictions  
- Produces performance metrics and visualisations  

### `Exploratory_GOVUK_Baseline_Failed.ipynb`
- Early experimentation notebook  
- Included for transparency of development process  

---

## Reproducibility

The primary notebooks are structured to allow:

**Kernel → Restart & Run All**

Reproducibility features include:
- Relative file paths  
- Deterministic random seeds  
- Optional GPU independence  
- Guarded repository cloning where applicable  
- No machine-specific directories  

---

## Requirements

Python **3.10+** recommended.

Core libraries:
- numpy  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  
- transformers  

Install manually if needed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn transformers
```

## How to Run

1. Clone the repository  
2. Open a notebook in Jupyter or VS Code  
3. Select a Python kernel  
4. Click **Kernel → Restart & Run All**


## Author
Abby Reynolds
