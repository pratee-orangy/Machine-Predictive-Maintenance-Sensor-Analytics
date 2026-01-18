# Machine-Predictive-Maintenance-Sensor-Analytics

## 📌 Overview

This project focuses on analyzing machine sensor data to support predictive maintenance analysis. The objective is to understand operating conditions, sensor behavior, and failure patterns using structured data analytics and statistical techniques, and to prepare analytics-ready outputs for reporting and visualization.

The project follows an end-to-end analytics workflow commonly used in industry, starting with initial data validation in Excel, detailed analysis using Python, and final visualization through BI tools.

---

## 📂 Dataset

The dataset consists of machine-level operational and sensor measurements, including:
- Unique machine and product identifiers
- Air and process temperature readings
- Rotational speed and torque values
- Tool wear duration
- Failure indicator and failure classification

This type of dataset is widely used in machine predictive maintenance and reliability analysis scenarios.

---

## 🧰 Tools & Technologies

- **Python** (Pandas, NumPy)
- **Excel** (PivotTables for initial data sanity checks)
- **Power BI** (dashboard creation)
- **Tableau** (visual analytics)

---

## 🔄 Project Workflow

### 📊 1. Excel – Initial Data Validation

- Performed preliminary sanity checks using PivotTables
- Reviewed machine type distribution, average sensor readings, and failure counts
- Used Excel only for early validation before deeper analysis

### 🐍 2. Python – Data Analysis & Preparation

Using Pandas and NumPy, the following steps were carried out:
- Data loading and schema inspection
- Handling missing values and duplicate records
- Descriptive statistical analysis of sensor data
- Outlier detection using IQR-based methods
- Feature engineering such as tool wear categorization and temperature difference calculation
- Failure rate analysis across machine types
- Group-based calculations for comparative analysis
- Correlation analysis among numerical features

### 📈 3. Analytics-Ready Outputs

- Generated cleaned and aggregated datasets
- Prepared structured outputs for Power BI and Tableau dashboards

---

## 🔍 Key Insights

- Higher tool wear and larger temperature differences are associated with increased failure rates
- Machine types exhibit variation in operating conditions and likelihood of failure
- Statistical validation and normalization help improve comparability of sensor readings
- Aggregated datasets enable effective visualization of predictive maintenance trends

---

## 📁 Outputs

The project produces:
- Cleaned machine sensor dataset
- Machine type–level summary metrics
- Failure rate analysis datasets

-then used for dashboarding and reporting.

---

## ✅ Conclusion

This project demonstrates an end-to-end data analytics approach for machine predictive maintenance using sensor data. It highlights practical data validation, statistical analysis, and preparation of insights to support monitoring and decision-making.

---

## 👤 Author
Prateeksha P Hegde

