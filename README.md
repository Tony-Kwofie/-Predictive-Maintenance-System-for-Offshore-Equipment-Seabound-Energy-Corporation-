# ⚙️ Predictive Maintenance System for Offshore Equipment  
**Seabound Energy Corporation**

---

## 📖 Project Summary

This project is a machine learning solution developed to **predict failures in offshore oil and gas equipment**, such as pumps, compressors, and valves. The goal is to help **Seabound Energy Corporation** detect early signs of mechanical failure and schedule preventive maintenance — reducing downtime, improving safety, and saving costs.

We use simulated but realistic sensor data, including temperature, pressure, vibration, and runtime readings, to train a predictive model that can flag potential equipment failures before they occur.

---

## 🎯 Objectives

- Build a model to **predict machine failure** using historical sensor data.
- Understand the key factors that cause offshore equipment to fail.
- Help offshore operators schedule **preventive maintenance** instead of reactive repairs.

---

## 🧰 Tools & Technologies

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn for machine learning
- Jupyter Notebook for development
- Dataset: Simulated offshore maintenance data (1,000 records)

---

## 📊 Dataset Features

Each row in the dataset represents one hour of equipment monitoring. It includes:

| Column Name         | Description |
|---------------------|-------------|
| `timestamp`         | Date and time of the reading |
| `equipment_id`      | Unique ID of the equipment |
| `equipment_type`    | Type (Pump, Compressor, Valve) |
| `pressure_psi`      | Measured pressure (PSI) |
| `temperature_c`     | Temperature in Celsius |
| `vibration_mm_s`    | Vibration level (mm/s) |
| `runtime_hours`     | Hours since last maintenance |
| `maintenance_flag`  | Whether recent maintenance was done |
| `failure`           | Target — Yes/No if equipment failed |

---

## ✅ What This Project Covers

- Data loading and exploration
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature selection and label encoding
- Machine learning model (Logistic Regression / Random Forest)
- Model evaluation (accuracy, confusion matrix)
- Interpretation of results

---

## 🚀 Outcomes

- Developed a basic failure prediction model with high accuracy
- Identified that **high vibration**, **long runtime**, and **high pressure** increase failure risk
- Demonstrated how machine learning can improve offshore safety and reliability

---

## 📁 File Structure

