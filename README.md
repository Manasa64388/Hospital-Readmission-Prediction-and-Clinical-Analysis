# Hospital Readmission Prediction & Clinical Analysis 🏥📈

## 📌 Project Overview
This project addresses a critical challenge in healthcare: **30-day hospital readmissions**. By analyzing over 100,000 clinical records of diabetic patients, I developed a machine learning solution to predict readmission risk with high accuracy. This allows healthcare providers to prioritize high-risk patients for comprehensive discharge planning, ultimately reducing costs and improving patient outcomes.

## 🚀 Key Features
* **End-to-End Data Pipeline:** Cleaned and preprocessed a dataset of 101k+ records, handling high-nullity features and encoding 700+ unique diagnosis codes into meaningful categories.
* **Predictive Modeling:** Implemented a **Random Forest Classifier** that achieved a **91% overall accuracy** in classifying patient readmission risk.
* **Feature Importance:** Identified key clinical drivers for readmission, including the number of lab procedures, medication count, and time spent in the hospital.
* **Interactive Dashboard:** Developed a **Power BI Dashboard** to provide clinical staff with visual insights into patient demographics and risk distributions.

## 🛠️ Tech Stack
* **Language:** Python (Pandas, NumPy, Scikit-learn, Seaborn)
* **Database:** SQLite3
* **Visualization:** Power BI
* **Environment:** Google Colab / Jupyter Notebook

## 📊 Model Performance
The Random Forest model was evaluated using a 20% test split:
* **Accuracy:** 91%
* **Precision:** 0.83
* **Recall:** 0.91
* **F1-Score:** 0.87



## 💡 Actionable Insights
1.  **High-Risk Profiling:** Patients aged 70-80 and those on more than 20 medications show significantly higher readmission rates.
2.  **Diagnosis Focus:** Patients with 'Circulatory' issues are primary candidates for extended care protocols.
3.  **Proactive Intervention:** The model can be integrated into hospital EMS systems to flag high-risk admissions in real-time.

## 📂 Repository Structure
```text
├── data/                   
│   ├── diabetic_data.csv          # Original raw clinical dataset
│   └── cleaned_hospital_data.csv  # Preprocessed data for ML modeling
├── notebooks/              
│   └── Analysis_Script.ipynb      # Python code for EDA and Random Forest model
├── dashboard/              
│   └── dashboard_preview.png      # High-resolution preview of the report
├── presentation/           
│   └── Project_Summary.pptx       # Executive summary for stakeholders
└── README.md               # Project documentation and setup guide
