# SenseOrPass - Proteomic Cancer Classifier

This project implements a deep learning classifier trained on proteomic biomarker data filtered by a predefined protein list. It includes model evaluation using ROC/AUC and SHAP interpretability.

## 📂 Structure

- `notebooks/` – Jupyter notebook with complete pipeline
- `src/` – Modular Python scripts for preprocessing, modeling, and evaluation
- `data/` – Selected protein list and input data
- `outputs/` – Trained models and plots

## 📥 Data Access

Data for this study is available through the following portals:
- [Head and Neck 5000](https://headandneck5000.org.uk/information-for-researchers/)
- [Exeter 10,000](https://exetercrfnihr.org/about/exeter-10000/)

## 🧪 Setup

```bash
pip install -r requirements.txt
