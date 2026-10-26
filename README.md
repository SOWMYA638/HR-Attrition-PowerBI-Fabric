# 👥 HR Attrition Analysis | Microsoft Fabric & Power BI

An end-to-end HR analytics solution built using Microsoft Fabric and Power BI to analyze employee attrition, identify workforce trends, and uncover the factors associated with employee turnover.

The dashboard transforms employee data into actionable insights across departments, salary bands, age groups, job roles, and other workforce attributes.

## 🛠️ Tech Stack

The project uses the following tools and technologies:

- ☁️ **Microsoft Fabric** — Data ingestion and analytics workflow.
- 📂 **Dataflows Gen2** — Data ingestion and transformation.
- 📊 **Power BI** — Interactive dashboards and data visualization.
- 🧠 **DAX** — Measures, attrition calculations, and dynamic analytics.
- 🔐 **Row-Level Security (RLS)** — Department-level data access using `USERPRINCIPALNAME()`.
- 🏷️ **Microsoft Purview sensitivity labels** — Confidentiality classification and data protection.
- 📁 **File Format** — `.pbix` for the Power BI report.

## 📊 Data Source

**Dataset:** IBM HR Analytics Employee Attrition & Performance dataset.

The project uses employee records covering workforce demographics, job characteristics, compensation, and attrition.

- **Employee records:** 1,470
- **Business domain:** Human Resources Analytics
- **Key dimensions:** Department, job role, age group, gender, salary band, education field, marital status, business travel, and overtime.
- **Key metrics:** Headcount, employees who left, attrition rate, average monthly income, and average tenure of employees who left.

## 🎯 Business Problem

Employee attrition can increase recruitment costs, disrupt team productivity, and result in the loss of organizational knowledge.

However, employee turnover data alone does not explain which workforce segments experience higher attrition or which characteristics are associated with employees leaving.

HR teams and department leaders need an interactive way to explore attrition patterns and identify areas that may require further investigation.

## 🚀 Goal of the Dashboard

To build an interactive HR analytics solution that:

- Monitors overall headcount and employee attrition.
- Identifies departments and job roles with higher attrition.
- Analyzes attrition across salary bands, age groups, and gender.
- Explores relationships between attrition and overtime, business travel, marital status, and education.
- Enables department-level access to workforce information through dynamic row-level security.
- Protects sensitive employee information through data classification.

## 📈 Dashboard Features & Highlights

### 1. Workforce Overview

The Overview page provides a high-level snapshot of employee attrition and workforce composition.

Key KPIs include:

- 👥 **Headcount** — Total employees represented in the dataset.
- 📉 **Employees Left** — Number of employees who have left.
- 📊 **Attrition Rate** — Percentage of employees who left.
- 💰 **Average Monthly Income** — Average employee monthly income.
- ⏳ **Average Tenure of Leavers** — Average tenure of employees who left.

**Business value:** Helps HR teams monitor workforce stability and understand the overall scale of employee turnover.

### 2. Attrition by Department

Analyzes attrition rates across departments and supports comparisons between workforce segments.

**Business value:** Helps identify departments that may require deeper investigation into employee retention.

### 3. Attrition Drivers — Decomposition Tree

Uses a decomposition tree to explore employee exits across dimensions such as:

- Department
- Job role
- Salary band

**Business value:** Enables interactive drill-down into workforce segments associated with employee attrition.

### 4. Salary & Workforce Segmentation

Examines headcount, employee exits, and attrition rates across salary bands and job roles.

**Business value:** Helps HR teams investigate whether attrition patterns differ across compensation levels and job categories.

### 5. Demographic & Employment Analysis

The Deep Dive page explores attrition across multiple employee dimensions:

- Age groups
- Gender
- Education field
- Marital status
- Business travel
- Overtime
- Department

**Business value:** Helps uncover workforce patterns that can inform further retention analysis and HR investigations.

### 6. Interactive Filtering

The dashboard includes slicers for dimensions such as department, gender, and salary band.

**Business value:** Enables users to focus on specific employee groups and compare attrition patterns across segments.

## 🔐 Data Security & Governance

Security and responsible handling of employee information are important parts of this project.

- **Dynamic Row-Level Security:** Implemented using DAX and `USERPRINCIPALNAME()` to restrict department heads to their authorized department's data.
- **Confidential Sensitivity Label:** Applied to classify the report and support the protection of sensitive workforce information.

**Business value:** Demonstrates how analytics can be combined with access controls and data classification to support responsible HR reporting.

*Note: RLS must be configured and tested with the appropriate user-to-department mapping and permissions. A sensitivity label supports information protection but does not independently guarantee that all underlying data is secured.*

## 💡 Business Impact

The dashboard provides a foundation for data-driven workforce analysis:

- **Retention Analysis:** Identifies employee segments with comparatively high attrition.
- **Workforce Planning:** Supports monitoring of employee exits across departments and job roles.
- **Compensation Analysis:** Enables investigation of attrition across salary bands.
- **Targeted Investigation:** Helps HR teams explore demographic and employment characteristics associated with attrition.
- **Secure Reporting:** Demonstrates department-level access control and confidentiality classification.

The dashboard identifies patterns and associations; further investigation is required before attributing attrition to specific causes.



## 🌱 Key Learnings

- Building an end-to-end analytics workflow with Microsoft Fabric.
- Transforming HR data into meaningful business metrics.
- Developing interactive Power BI dashboards using DAX.
- Exploring employee attrition across multiple workforce dimensions.
- Implementing dynamic row-level security.
- Applying sensitivity labels for data classification.

---

<div align="center">

### ✨ Turning workforce data into meaningful insights.

*Explore. Analyze. Understand. Improve.* 📊

</div>
