# Hospital Readmission Prediction & Clinical Analysis 🏥📈

> **Quick Summary:**
> * **Problem:** Reducing 30-day readmissions to improve patient health and hospital efficiency.
> * **Data:** Processed **71,510 unique patient records** from an initial 101k+ encounter dataset.
> * **Model:** Trained a **Random Forest Classifier** achieving **91% accuracy** in risk prediction.
> * **Tech Stack:** Python (Pandas, Scikit-learn), SQLite3, and Power BI.
> * **Result:** Identified high-risk profiles (Ages 70-80, >20 medications) for proactive clinical intervention.

---

## 📌 Project Overview
**Capstone Project** | **Team Lead**
**Collaborators:** Shivani B V, Samanvita Raju Bagewadi, Yashitha N P.

This project addresses a critical challenge in healthcare: 30-day hospital readmissions. By analyzing clinical records of diabetic patients, our team developed a machine learning solution to predict readmission risk. This allows healthcare providers to prioritize high-risk patients for comprehensive discharge planning, ultimately reducing costs and improving patient outcomes.

## 🚀 Key Features
* **End-to-End Data Pipeline:** Cleaned and preprocessed a dataset of 101k+ records, handling high-nullity features and encoding 700+ unique diagnosis codes into meaningful categories.
* **Predictive Modeling:** Implemented a **Random Forest Classifier** that achieved a **91% training accuracy** in classifying patient readmission risk.
* **Feature Importance:** Identified key clinical drivers: number of lab procedures, medication count, and hospital stay duration.
* **Interactive Dashboard:** Developed a **Power BI Dashboard** to provide clinical staff with visual insights into patient demographics and risk distributions.

## 🛠️ Tech Stack
* **Language:** Python (Pandas, NumPy, Scikit-learn, Seaborn)
* **Database:** SQLite3
* **Visualization:** Power BI
* **Environment:** Google Colab / Jupyter Notebook

## 📊 Model Performance
The Random Forest model was evaluated on the training dataset:
* **Accuracy:** 91%
* **Precision:** 0.83
* **Recall:** 0.91
* **F1-Score:** 0.87

## 💡 Actionable Insights
* **High-Risk Profiling:** Patients aged 70-80 and those on more than 20 medications show significantly higher readmission rates.
* **Diagnosis Focus:** Patients with 'Circulatory' issues are primary candidates for extended care protocols.
* **Proactive Intervention:** The model can be integrated into hospital systems to flag high-risk admissions in real-time.

## 📂 Repository Structure
```text
├── data/                   
│   ├── diabetic_data.csv          # Original raw clinical dataset
│   └── cleaned_hospital_data.csv  # Preprocessed data (71,510 records)
├── notebooks/              
│   └── Analysis_Script.ipynb      # Python code for EDA and Random Forest model
├── dashboard/              
│   └── dashboard_preview.png      # High-resolution preview of the report
├── presentation/           
│   └── Project_Summary.pptx       # Executive summary for stakeholders
└── README.md               # Project documentation
