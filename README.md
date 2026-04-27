# AI Triage & Intake Assistant for Small Clinics

## Canada-Centric Healthcare Analytics Prototype

This project is a Canada-focused healthcare analytics prototype that simulates patient intake and triage workflows for small clinics.

Using synthetic patient records, the notebook classifies patients by urgency level, visit type, and recommended clinic action using rule-based logic. The project demonstrates practical skills in Python, pandas, data visualization, healthcare operations thinking, and analytics storytelling.

---

# Project Objective

Small clinics often need a fast and structured way to prioritize incoming patients while managing limited appointment capacity.

This project was designed to simulate a patient intake workflow where incoming records are assessed using multiple factors such as:

- Age
- Symptom type
- Pain level
- Breathing issues

The goal is to recommend an appropriate next action such as:

- Send Immediately
- Nurse Review
- Priority Booking
- Same Day Appointment
- Routine Appointment

---

# Tools & Technologies Used

- Python
- pandas
- matplotlib
- Jupyter Notebook
- CSV Export
- GitHub

Future planned tools:

- Tableau
- Streamlit
- SQL
- Machine Learning

---

# Dataset Overview

This project uses a synthetic dataset of 50 simulated patient records.

Each record includes:

- Patient_ID
- Intake_Date
- Age
- Province
- Symptom
- Pain_Level
- Breathing_Issue

No real patient information was used.

---

# Canadian Scope

The simulation includes multiple Canadian provinces, including:

- Ontario
- Quebec
- British Columbia
- Alberta
- Manitoba
- Saskatchewan
- Nova Scotia
- New Brunswick
- Newfoundland and Labrador
- Prince Edward Island

---

# Feature Engineering & Triage Logic

The notebook creates three key decision-support fields:

## 1. Risk_Group

Patients are categorized as:

- Critical
- Higher Risk
- Standard Risk

Based on pain level, age, symptoms, and breathing issues.

## 2. Visit_Type

Patients are classified into:

- Urgent Visit
- Same Day Visit
- Routine Visit

## 3. Clinic_Action

Final recommended next step:

- Send Immediately
- Nurse Review
- Priority Booking
- Same Day Appointment
- Routine Appointment

---

# Dashboard Charts Included

The notebook contains multiple visualizations:

- Clinic Action Distribution
- Risk Group Distribution
- Patient Distribution by Province
- Most Common Symptoms
- Patient Age Distribution
- Risk Group by Province
- Patient Volume by Intake Date

---

# Key Insights

- Send Immediately became the most common clinic action after upgrading triage rules.
- Critical was the largest patient risk category in the updated simulation.
- Multi-factor triage logic increased urgent classifications.
- Patient demand was distributed across multiple Canadian provinces.
- The upgraded logic better reflects realistic clinic prioritization workflows.

---

# Limitations

- Uses synthetic (simulated) data only.
- Rule-based logic is simplified and not clinical guidance.
- Results are not medical advice, diagnosis, or treatment recommendations.
- Real healthcare systems would require clinician oversight and validated protocols.
- Additional variables such as vital signs and medical history were not included.

---

# Future Improvements

- Expand to all Canadian provinces and territories
- Add vital signs and more health indicators
- Build interactive Tableau dashboards
- Create a Streamlit web application
- Add SQL database storage
- Develop machine learning prediction models
- Add authentication and privacy controls

---

# Export / Business Intelligence Ready

The final dataset can be exported to CSV for use in:

- Tableau
- Power BI
- Excel
- SQL systems

---

# Repository Contents

- `AI_Triage_Intake_Assistant_Canada.ipynb`
- `README.md`

---

# Author

Created as part of a data analytics learning and portfolio development journey.
