# Insurance Claims Analytics Dashboard

## Overview

The Insurance Claims Analytics Dashboard is an interactive business intelligence project developed using Power BI to analyze insurance operations, policy performance, claims activity, customer demographics, and customer feedback trends.

This dashboard transforms raw insurance data into meaningful visual insights that help understand premium collection, coverage exposure, claims processing efficiency, and policy activity.

The project was designed to simulate a real-world insurance reporting environment where management requires quick KPI monitoring and decision-support visuals.

---

## Business Objective

The main objective of this project is to provide an analytical reporting solution for insurance data that answers important business questions such as:

* Which insurance policy type generates the highest premium revenue
* What is the total claim amount across all policies
* What percentage of claims are approved, rejected, or pending
* Which customer age group contributes the highest claim amount
* How many policies are active versus inactive
* What customer feedback reveals about service quality

The dashboard enables business users to identify operational trends and performance gaps quickly.

---

## Tools and Technologies Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Relationships
* Excel Dataset
* CSV Dataset
* Power BI Service

---

## Dataset Information

The project uses structured insurance data containing policy records, customer records, claim records, and feedback records.

### Main fields included in dataset

* PolicyNumber
* CustomerID
* ClaimNumber
* Age
* Gender
* CoverageAmount
* PremiumAmount
* PolicyStartDate
* PolicyEndDate
* PolicyType
* ClaimStatus
* ClaimDate
* ClaimAmount
* Active / Inactive Status

A separate feedback dataset was also included for customer sentiment analysis.

---

## Dashboard Pages

The dashboard contains multiple report pages for different analytical purposes.

---

## 1. Overview Dashboard

This page provides the main business summary through KPI cards and analytical visuals.

### KPI Cards

* Premium Amount
* Coverage Amount
* Claim Amount
* Approval Rate
* Rejection Rate
* Active Policies

### Visual Analysis Included

* Premium Amount by Policy Type
* Active vs Inactive Policies
* Claim Amount by Age Group
* Monthly Claim Status Trend
* Business Insights Section

---

## 2. Table View

This page provides transaction-level detailed records.

### Includes columns such as

* Policy Number
* Customer ID
* Claim Number
* Age
* Gender
* Coverage Amount
* Premium Amount
* Policy Type
* Claim Status
* Claim Amount

This helps detailed business review and filtering.

---

## 3. Feedback Analysis Page

This page analyzes customer feedback using sentiment-based visuals.

### Includes

* Word Cloud Visualization
* Sentiment Score Table
* Feedback Distribution Chart

This helps understand customer satisfaction trends.

---

## DAX Measures Used

Several DAX measures were created to calculate dynamic KPIs.

### Major measures include

* Total Premium Amount
* Total Coverage Amount
* Total Claim Amount
* Approval Rate
* Rejection Rate
* Active Policies Count

These measures allow visuals to respond dynamically to filters and slicers.

---

## Data Modeling

Relationships were created between insurance tables using common keys.

### Relationship logic used

* CustomerID
* PolicyNumber

The model enables accurate aggregation across visuals.

---

## Key Business Insights

The dashboard generated several important business insights.

* Travel policy contributes highest premium revenue
* Active policies dominate overall portfolio
* Adult age group files highest claims
* Claim rejection requires operational review

These insights improve business understanding and reporting value.

---

## Dashboard Design Approach

The dashboard follows executive reporting design principles.

### Layout used

* Top KPI row
* Middle business analysis visuals
* Bottom trend analysis and insight section

Dark theme with teal highlights was used for professional readability.

---

## Power BI Service Publication

The dashboard was published to Power BI Service for cloud-based reporting and online access.

This enables:

* browser access
* report sharing
* cloud presentation


Live Dashboard
Power BI Service Link : https://app.powerbi.com/groups/5c58b448-32db-4206-88e0-26feabb4c199/reports/f6e87635-2a32-4a21-89f7-b8f75a8e3e63/c530120a1399b16044ae?experience=power-bi

---

📸 Screenshots :

![insurance-claims-dashboard-powerbi](screenshots)


## Project Folder Structure

insurance-claims-dashboard/
│── dataset/
│── dax_measures/
│── screenshots/
│── README.md
│── Insurance_Dashboard.pbix
│── Insurance_Project_Documentation.docx

---

## Project Outcome

This project demonstrates practical business intelligence skills including:

* KPI dashboard development
* DAX calculations
* data modeling
* business insight generation
* sentiment analytics

It can be extended further using SQL integration, Python automation, and cloud deployment.

---

## Author

Abhishek Kumar
