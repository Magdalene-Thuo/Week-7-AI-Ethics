# Week-7-AI-Ethics
# Ethical AI Assignment - Comprehensive Report

## 📘 Overview

This repository contains a comprehensive submission for an academic assignment on **Ethical AI** practices. It covers theoretical foundations, real-world case study analyses, dataset bias auditing using AI Fairness 360 (IBM toolkit), and a personal ethical reflection. The bonus section includes a healthcare-specific AI ethics policy.

---

## 🧩 Assignment Structure

### ✅ Part 1: Theoretical Understanding (30%)
- **Algorithmic Bias** definition with examples.
- **Transparency vs Explainability** in AI.
- **GDPR’s Impact on AI** development.
- **Ethical Principles Matching** activity.

---

### ✅ Part 2: Case Study Analysis (40%)
- **Case 1**: Amazon’s Biased Hiring Tool
  - Source of bias, proposed solutions, fairness metrics.
- **Case 2**: Facial Recognition in Policing
  - Ethical risks and policy recommendations.

---

### ✅ Part 3: Practical Audit (25%)
- **Dataset Used**: COMPAS Recidivism Dataset.
- **Tools**: Python, IBM AI Fairness 360 (`aif360`), `matplotlib`.
- **Objective**: Identify and visualize racial bias in predictive risk scores.
- **Bias Metrics**:
  - Disparate Impact
  - False Positive Rate Difference
- **Outputs**:
  - Visual bar chart
  - 300-word summary report with remediation strategies.

---

### ✅ Part 4: Ethical Reflection (5%)
- Personal commitment to ethical AI principles in future projects, especially on education access bots for rural Kenya.

---

### 🎯 Bonus Task (Extra 10%)
- **1-Page Ethical AI Policy for Healthcare**:
  - Consent protocols
  - Bias mitigation strategies
  - Transparency requirements
  - Governance recommendations

---

## 📂 Folder Structure

Ethical-AI-Assignment/
│
├── part1_theory.md
├── part2_case_studies.md
├── part3_bias_audit/
│ ├── compas_bias_audit.ipynb
│ ├── compas_bias_visualization.png
│ └── bias_audit_summary_report.md
│
├── part4_ethics_reflection.md
├── bonus_healthcare_policy.md
└── README.md


---

## 🛠️ Setup Instructions

> To replicate the COMPAS dataset audit:

1. Install dependencies:
   ```bash
   pip install aif360 matplotlib scikit-learn pandas
Run the Jupyter Notebook:


jupyter notebook compas_bias_audit.ipynb
The script will output bias metrics and save a PNG chart:
compas_bias_visualization.png

📌 Notes
The aif360 library requires Python ≥ 3.6 and might require additional setup like tensorflow for advanced functionality.

The COMPAS dataset is sensitive and should be handled in line with ethical data use guidelines.

✍️ Author
Magdalene Thuo
Digital Trainer | Ethical AI Advocate
LinkedIn | GitHub
