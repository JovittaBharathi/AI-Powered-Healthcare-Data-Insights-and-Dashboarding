# 🏥 Healthcare Data Analysis Dashboard using Microsoft Excel

> An Excel capstone project focused on analyzing customer healthcare information, hospitalization charges, medical conditions, and lifestyle-related health factors using formulas, PivotTables, charts, and an interactive dashboard.

---

## 📌 Project Overview

This project analyzes healthcare and hospitalization data using Microsoft Excel. The workbook combines customer information, hospitalization details, and medical examination records to identify patterns in healthcare charges, age, BMI, diabetes status, smoking habits, weight status, and other medical factors.

The project demonstrates the use of Excel for data cleaning, data transformation, PivotTable analysis, data visualization, and dashboard development.

---

## 🎯 Project Objectives

- Organize and combine healthcare data from multiple worksheets.
- Clean and transform raw customer and medical records.
- Calculate customer age using date-based Excel formulas.
- Classify customers based on BMI and HBA1C values.
- Analyze hospitalization charges across different health categories.
- Compare healthcare indicators such as smoking, diabetes, and weight status.
- Create PivotTables and charts for visual analysis.
- Build an interactive healthcare dashboard in Excel.

---

## 📂 Dataset Description

The workbook contains information related to:

- Customer details
- Date of birth and age
- Number of children
- Hospitalization charges
- Hospital tier
- City tier
- State
- BMI
- HBA1C levels
- Heart issues
- Transplant history
- Cancer history
- Number of major surgeries
- Smoking status
- Weight status
- Diabetes status

---

## 🗂️ Workbook Structure

### 1. Customer Names

Contains the basic personal information of customers.

**Important columns:**

- Customer ID
- Title
- First Name
- Last Name

### 2. Hospitalisation Details

Contains demographic and hospitalization-related information.

**Important columns:**

- Customer ID
- Year
- Month
- Date
- Children
- Charges
- Hospital Tier
- City Tier
- State ID
- Date of Birth
- Age

### 3. Medical Examinations

Contains medical examination details and health indicators.

**Important columns:**

- Customer ID
- BMI
- HBA1C
- Heart Issues
- Any Transplants
- Cancer History
- Number of Major Surgeries
- Smoker
- Weight Status
- Diabetes Status

### 4. Healthcare

Contains the consolidated healthcare dataset used for analysis.

### 5. Pivot Table

Contains summary reports created using Excel PivotTables.

### 6. Column Chart

Contains column-chart visualizations created from the summarized data.

### 7. Pie Chart

Contains pie-chart visualizations showing category distributions.

### 8. QA Pivot using AI

Contains AI-assisted questions, PivotTables, and supporting charts used to analyze healthcare data.

### 9. Healthcare Dashboard

Contains the final dashboard presenting the main healthcare findings and visualizations.

---

## 🧹 Data Cleaning and Transformation

The following data-cleaning and transformation activities were performed:

- Combined customer, hospitalization, and medical examination data.
- Created valid dates from separate year, month, and date fields.
- Calculated customer age from the date of birth.
- Classified customers into different weight-status categories.
- Classified customers based on HBA1C results.
- Standardized categorical values for analysis.
- Prepared structured data for PivotTables and charts.

---

## 🧮 Excel Formulas Used

### Age Calculation

Customer age was calculated using the `DATEDIF` function.

```excel
=DATEDIF(Date_of_Birth,Reference_Date,"Y")
```

### Diabetes Status Classification

Diabetes status was classified using HBA1C values.

```excel
=IF(HBA1C<5.7,"Normal",IF(HBA1C<6.5,"Prediabetes","Diabetes"))
```

### Weight Status Classification

BMI values were used to classify customers into:

- Under Weight
- Normal Weight
- Over Weight
- Obesity

---

## 📊 Analysis Performed

The project includes analysis of:

- Total hospitalization charges
- Average customer age
- Customer distribution by smoking status
- Healthcare charges by weight status
- HBA1C and diabetes-status distribution
- Relationship between smoking and healthcare charges
- Hospitalization charges across health categories
- Distribution of customers across BMI groups
- Medical conditions and major surgery history

---

## ❓ Business Questions Answered

- What is the total hospitalization charge?
- What is the average age of the customers?
- How many customers are smokers and non-smokers?
- Which weight category has the highest hospitalization charges?
- How are customers distributed across normal, prediabetes, and diabetes categories?
- Do smokers have higher hospitalization charges?
- How does BMI affect hospitalization expenses?
- What relationship exists between age and healthcare charges?
- How do heart issues, cancer history, and transplant history affect healthcare costs?

---

## 📈 Dashboard Features

The healthcare dashboard includes:

- Key healthcare indicators
- PivotTable-based summaries
- Column-chart visualizations
- Pie-chart visualizations
- Comparisons by smoking status
- Comparisons by weight status
- Healthcare-charge analysis
- HBA1C and diabetes analysis
- Interactive Excel filtering

---

## 🛠️ Excel Features Used

- Excel Formulas
- IF Function
- DATEVALUE Function
- DATEDIF Function
- Lookup and Reference Functions
- Data Cleaning
- Data Transformation
- PivotTables
- PivotCharts
- Column Charts
- Pie Charts
- Slicers
- Conditional Formatting
- Dashboard Design

---

## 📁 Project File

```text
Excel-Capstone-Project
│
├── Excel Capstone Project.xlsx
└── README.md
```

---

## 🔍 Key Observations

- Hospitalization charges vary across customer health and lifestyle categories.
- BMI and weight status can be used to compare differences in healthcare expenses.
- HBA1C values help classify customers into normal, prediabetes, and diabetes groups.
- Smoking status is an important category for healthcare-cost analysis.
- PivotTables provide a clear summary of large healthcare datasets.
- Charts and dashboard visuals make the results easier to understand.

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Cleaning and organizing healthcare data in Excel
- Combining data from multiple worksheets
- Applying logical and date-based formulas
- Creating calculated health categories
- Building PivotTables and PivotCharts
- Designing column charts and pie charts
- Analyzing healthcare charges and medical indicators
- Creating an interactive Excel dashboard
- Presenting analytical findings clearly

---

## ✅ Conclusion

This project demonstrates how Microsoft Excel can be used to clean, transform, analyze, and visualize healthcare data. Excel formulas were used to derive important fields such as age, weight status, and diabetes status.

PivotTables and charts were then used to summarize healthcare charges, demographic information, lifestyle factors, and medical conditions. The final healthcare dashboard presents these findings in a clear and interactive format.

---

## 👩‍💻 Author

**Jovitta Bharathi**

---

## 📚 Project Type

**Excel Capstone Project**

---

## 💻 Tool Used

**Microsoft Excel**
