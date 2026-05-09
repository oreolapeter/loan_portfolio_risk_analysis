# Loan Portfolio Risk Analysis

## Project Overview

This project presents an end-to-end credit risk analytics solution developed to analyze the health and performance of a financial institution’s loan portfolio. 
The solution was designed to provide visibility into portfolio exposure, non-performing loans, default trends, and risk concentration 
across customer and loan segments.

The project integrates Excel, SQL, and Power BI to simulate a real-world analytics workflow used within financial institutions 
for portfolio monitoring and risk assessment.

The final solution enables stakeholders to:

- Monitor portfolio risk exposure
- Identify high-risk loan segments
- Track non-performing loans (NPL)
- Analyze default trends across customer demographics
- Support data-driven risk management decisions

---

## Business Problem

Financial institutions face increasing challenges in managing loan portfolio quality and controlling credit risk exposure. Without proper visibility into high-risk customer segments, loan performance, and geographic concentration, institutions may experience rising default rates and deteriorating portfolio health.

This project was developed to provide an analytical framework capable of monitoring key portfolio risk indicators and uncovering areas requiring immediate management attention.

---

## Project Objectives

The primary objectives of this project are:

- to Analyze the overall health of the loan portfolio
- to Measure portfolio exposure and loan-at-risk levels
- to Calculate non-performing loan (NPL) ratios
- to Identify default-prone customer segments
- to Analyze portfolio risk by:
  - Location
  - Employment type
  - Loan type
  - Age group
- to Develop an interactive dashboard for executive reporting and decision-making



---

## Tools & Technologies Used

    Tool                           Purpose 

   Microsoft Excel          Data cleaning and preprocessing 
   MySQL                    Data querying and KPI calculations 
   Power BI                 Data visualization and dashboard development
   Git & GitHub             Version control and project documentation

---

## Project Workflow

The project followed a structured analytics workflow consisting of the following stages:

### 1. Data Cleaning & Preparation (Excel)
The raw loan portfolio dataset was cleaned and transformed using Microsoft Excel. Data preprocessing activities included:

- Handling missing values
- Standardizing categorical fields
- Correcting inconsistent records
- Formatting data types
- Preparing the dataset for SQL analysis

### 2. Risk Analysis & KPI Computation (SQL)
SQL was used to perform portfolio analysis and calculate key risk metrics, including:

- Total Exposure
- Loan at Risk
- Non-Performing Loan (NPL) Ratio
- Default Rate
- Portfolio Risk Mix
- Segment-level risk exposure

Additional segmentation analysis was performed across:

- Location
- Loan Type
- Employment Type
- Age Group

### 3. Dashboard Development (Power BI)
Power BI was used to develop an interactive analytical dashboard for monitoring portfolio performance and identifying risk concentration areas.

The dashboard includes:

- KPI summary cards
- Portfolio risk distribution
- Geographic risk analysis
- Customer segmentation analysis
- Loan-type risk assessment
- Interactive filtering and drill-down capabilities

---

## Key Performance Indicators (KPIs)

The following KPIs were developed within the project:

        KPI                                 Description 
 Total Exposure-            Total outstanding loan amount 
 Loan at Risk-              Total active, delinquent, and defaulted loan exposure 
 NPL Ratio-                 Percentage of defaulted exposure relative to total outstanding exposure 
 Default Rate-              Percentage of defaulted loans relative to total active portfolio 
 High Risk Rate-            Percentage of high-risk loans within the portfolio 
 Portfolio Risk Mix-        Distribution of low, medium, and high-risk exposure 

---

## Key Insights

The analysis revealed several important portfolio risk patterns:

- Medium-risk loans accounted for the largest share of portfolio exposure, indicating elevated future default potential within the portfolio.
- High-risk loans represented a significant portion of total exposure and require closer monitoring and stricter credit control measures.
- Certain geographic locations showed higher concentrations of high-risk exposure, suggesting uneven regional portfolio performance.
- Specific loan products demonstrated increased default tendencies compared to others.
- Younger customer segments exhibited relatively higher high-risk exposure levels.
- Employment categories with unstable income structures displayed increased portfolio risk concentration.

These findings provide management with actionable insights for improving credit risk management and portfolio monitoring strategies.

---

## Recommendations

Based on the analysis, the following recommendations were proposed:

- Strengthen monitoring procedures for medium-risk and high-risk loan categories.
- Review underwriting policies for high-default loan products.
- Increase risk-based monitoring across high-risk geographic regions.
- Introduce early warning systems for delinquent accounts.
- Improve customer risk segmentation during loan approval processes.
- Enhance portfolio diversification to reduce concentration risk.
- Conduct periodic portfolio stress-testing and performance reviews.

---

## Dashboard Features

The Power BI dashboard provides the following capabilities:

- Interactive filtering and drill-down analysis
- Portfolio exposure monitoring
- Risk segmentation analysis
- Geographic risk visualization
- Loan product risk assessment
- Customer demographic risk analysis
- Executive-level KPI reporting

---

## Repository Structure
loan_portfolio_risk_analysis/
│
├── data/
├── docs/
├── excel/
├── images/
├── powerbi/
├── sql/
└── README.md



## Dashboard Preview

### Portfolio Overview Dashboard

dashboard_overview.png

---

## Conclusion

This project demonstrates the application of data analytics techniques in evaluating credit risk exposure within a retail loan portfolio. By integrating Excel, SQL, and Power BI, the solution provides a structured analytical framework for monitoring portfolio performance, identifying high-risk segments, and supporting data-driven decision-making.

The project reflects a real-world analytics workflow involving:

- Data preparation
- KPI development
- Risk analysis
- Interactive dashboard reporting
- Business insight generation

---

## Author

Developed by Olalekan Adepoju  
Data Analyst | Risk Analytics Enthusiast




