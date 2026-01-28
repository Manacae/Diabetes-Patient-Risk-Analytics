# Diabetes Patient Risk Analytics
> Identifying clinical drivers for hospital readmissions in diabetic patients to improve patient outcomes using Python and Tableau.

---

## 📊 Project Overview
This project analyzes a dataset representing 10 years (1999-2008) of clinical care at 130 US hospitals. The goal is to identify factors that lead to high 30-day readmission rates among diabetic patients, providing actionable insights for hospital administrators to improve transition-of-care protocols.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas (Data Wrangling), Seaborn/Matplotlib (Visualization), NumPy
* **Business Intelligence:** Tableau (Interactive Dashboard)

## 📈 Key Insights (Work in Progress)
* *Insight 1: [e.g., Patients aged 70+ show a 15% higher readmission rate]*
* *Insight 2: [e.g., Specific medication changes correlate with lower bounce-back rates]*

## 🧹 Data Processing Highlights
To ensure high-quality analysis, the following steps were taken:
1. **Handling Missing Values:** Replaced `?` placeholders with `NaN` and assessed column integrity.
2. **De-duplication:** Filtered for the first encounter per patient to prevent data leakage.
3. **Feature Categorization:** Grouped ICD-9 diagnosis codes into clinical categories (e.g., Circulatory, Respiratory).

## 🚀 How to Use
1. Clone the repository.
2. Install dependencies: `pip install pandas matplotlib seaborn`.
3. Open `analysis.ipynb` to view the step-by-step EDA.

## ⚖️ Ethical Considerations
This project uses an anonymized, public dataset. In a real-world setting, this analysis would be performed in compliance with HIPAA regulations to ensure patient privacy.

## 🤝 Acknowledgements
This project was developed with the assistance of **Gemini (Google AI)**, which served as a technical collaborator for:
* Architecting the repository structure and documentation.
* Refining data cleaning strategies for healthcare-specific datasets.
* Debugging and optimizing Python analysis workflows.
