# AIxGRC Project: Breast Cancer Classifier

This project is part of **AIxGRC** — a governance-first initiative to demonstrate how artificial intelligence systems can be developed responsibly with embedded governance, risk, and compliance practices.

##  Project Overview

We use a Random Forest classifier to predict whether a breast tumor is malignant or benign using 30 numerical features from scikit-learn’s `load_breast_cancer` dataset.

While technically simple, this project is designed to show how even baseline ML models can include:

- Ethical and governance documentation
- Transparent model behavior
- Basic risk evaluation
- Reproducible artifacts

---

## 🔍 Governance, Risk & Compliance (GRC) Integration

| Component                  | Status |
|---------------------------|--------|
| Model Card                | Included inside notebook |
| Risk Register             | Documented in notebook |
| Explainability            | Feature importance + class balance |
| Fairness Evaluation       | Class distribution assessed |
| Intended Use Clarified    | For educational purposes only |
| Deployment Readiness      | Not production-grade; no live system |
| Audit Logging             | Planned in future version |

---

##  Technical Summary

- **Model**: Random Forest Classifier
- **Data**: Breast cancer dataset from scikit-learn
- **Accuracy**: ~95% on test set
- **Key Evaluation**: Accuracy, precision, recall, F1-score

---

##  Responsible Use Disclaimer

This project is for **educational and demonstration purposes only**. It is **not** intended for clinical or diagnostic use. Any model intended for medical deployment would require clinical validation, FDA compliance, and extensive real-world testing.

---

##  Project Files

| File | Purpose |
|------|---------|
| `breast_cancer_classifier.ipynb` | Core notebook with model + AIxGRC documentation |
| `ai-risk-register.md` (optional) | Standalone risk register |
| `README.md` | This file |

---

## 🧩 Part of the AIxGRC Portfolio

This project was developed by **Olivia Athelus** as part of the growing **AIxGRC portfolio**, where AI governance and GRC meet practical, hands-on development.
