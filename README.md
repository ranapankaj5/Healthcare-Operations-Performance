# Healthcare Operations Performance

## 📊 Project Overview

Healthcare Operations Performance is an interactive Power BI dashboard designed to analyze healthcare operational data and provide insights into patient activity, hospital performance, departments, doctors, procedures, processes, and teams.

The project uses Excel datasets, Power Query for data transformation, DAX for KPI calculations, and a Star Schema data model for analytical reporting.

---

## 🎯 Business Objectives

- Monitor overall healthcare operational performance
- Analyze patient and operational activity
- Compare hospital performance
- Analyze department-level performance
- Evaluate doctor and procedure activity
- Monitor process and team performance
- Track operational KPIs and trends
- Support data-driven decision making

---

## 📌 Key KPIs

- Total Patients
- Total Operations
- Total Hospitals
- Total Doctors
- Total Departments
- Total Procedures
- Total Processes
- Total Teams
- Average Billing Amount
- Hospital Performance
- Department Performance
- Process Performance
- Team Performance

---

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling
- Star Schema
- Data Visualization

---

## 📊 Dashboard Features

### Healthcare Overview

- Overall operational KPIs
- Patient activity
- Healthcare operation trends
- Hospital performance
- Department performance

### Hospital Analysis

- Hospital-wise operations
- Patient distribution
- Hospital performance comparison

### Department Analysis

- Department-wise activity
- Department performance
- Comparative analysis

### Doctor & Procedure Analysis

- Doctor-level activity
- Doctor performance
- Procedure-wise analysis
- Procedure trends

### Process & Team Analysis

- Process-wise performance
- Team-wise activity
- Process comparison
- Team performance comparison

---

## 🗂️ Data Model

The project follows a Star Schema consisting of one central fact table and multiple dimension tables.

### Fact Table

`Fact_Healthcare_Operations`

### Dimension Tables

- `Dim_Patient`
- `Dim_Doctor`
- `Dim_Hospital`
- `Dim_Department`
- `Dim_Date`
- `Dim_Diagnosis`
- `Dim_Procedure`
- `Dim_Payer`
- `Dim_Employee`
- `Dim_Process`
- `Dim_Team`

---

## 🔄 Data Preparation

Data was prepared and transformed using Power Query.

The transformation process included:

- Data cleaning
- Data type correction
- Handling missing values
- Column transformation
- Data standardization
- Duplicate handling
- Preparing data for Power BI modeling

---

## 🔗 Data Modeling

The Power BI model uses a Star Schema approach.

The central fact table contains healthcare operational records, while dimension tables provide descriptive information for analysis.

The model allows analysis across:

- Patients
- Doctors
- Hospitals
- Departments
- Dates
- Diagnoses
- Procedures
- Payers
- Employees
- Processes
- Teams

---

## 📈 DAX Analysis

DAX measures were created to calculate dynamic KPIs and analytical metrics.

Examples include:

- Total Patients
- Total Operations
- Total Hospitals
- Total Doctors
- Total Departments
- Total Procedures
- Total Processes
- Total Teams
- Average Billing Amount
- Hospital Performance
- Department Performance
- Process Performance
- Team Performance

---

## 🎛️ Interactive Filters

The dashboard provides interactive filtering by:

- Date
- Hospital
- Department
- Doctor
- Diagnosis
- Procedure
- Payer
- Process
- Team
- Employee

---

## 📸 Dashboard Preview

![Healthcare Operations Dashboard](Screenshots/Healthcare_Operations_Dashboard.png)

---

## 🚀 Project Workflow

Excel Data  
↓  
Power Query  
↓  
Data Cleaning & Transformation  
↓  
Data Modeling  
↓  
Star Schema  
↓  
DAX Measures  
↓  
Power BI Dashboard  
↓  
Healthcare Operational Insights

---

## 📁 Project Structure

```text
Healthcare-Operations-Performance/
│
├── Data/
│   ├── Fact_Healthcare_Operations.xlsx
│   ├── Dim_Patient.xlsx
│   ├── Dim_Doctor.xlsx
│   ├── Dim_Hospital.xlsx
│   ├── Dim_Department.xlsx
│   ├── Dim_Date.xlsx
│   ├── Dim_Diagnosis.xlsx
│   ├── Dim_Procedure.xlsx
│   ├── Dim_Payer.xlsx
│   ├── Dim_Employee.xlsx
│   ├── Dim_Process.xlsx
│   └── Dim_Team.xlsx
│
├── PowerBI/
│   └── Healthcare_Operations_Performance.pbix
│
├── Screenshots/
│   └── Healthcare_Operations_Dashboard.png
│
└── README.md
