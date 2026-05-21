# SenseOrPass - Proteomic Cancer Classifier

This project implements a deep learning classifier trained on proteomic biomarker data filtered by a predefined protein list. It includes model evaluation using ROC/AUC and SHAP interpretability.

## 📂 Structure

- `Scripts/` – Jupyter notebook with complete pipeline
- `Data/` – Selected protein list and input data
- `Output/` – Generated plots, evaluation results, and model outputs

## 📥 Data Access

Test data for this study:
- Proteomics for the selected proteins given in the list 

Please note that trained model weight files are not included in this repository due to data access restrictions associated with UK Biobank (UKB) data. The model can be retrained using the provided pipeline, subject to appropriate data access permissions.

## 🧪 Setup

```bash
pip install -r requirements.txt
