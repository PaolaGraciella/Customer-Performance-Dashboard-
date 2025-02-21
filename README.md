# Customer-Performance-Dashboard-

## Introduction

This project consists of a Power BI dashboard designed to analyze patient data, optimize healthcare management, and enhance decision-making in the medical field. Through advanced analytics and key indicators, it provides insights into patient demographics, health trends, and the impact of various factors on medical outcomes.

## ❓ Key Questions Answered

✅ How to calculate the average age of patients?
✅ How to determine the total number of patients?
✅ How to categorize patients based on their medical history and visit frequency?

Identification of high-risk patients, regular patients, and occasional patients.
✅ How to analyze the impact of parenthood on healthcare costs and patient preferences?
✅ How to implement a dynamic ranking system to identify patients who require priority follow-up?
✅ What are the cost trends in healthcare based on patient gender?

💡Solving Healthcare Challenges
Implemented Solutions:
Patient Segmentation: Classifying patients based on medical history and visit frequency.
Healthcare Cost Analysis: Comparing medical expenses by age, gender, and parenthood status.
Medical Resource Optimization: Identifying hospitalization trends to anticipate staffing and equipment needs.
Priority Patient Monitoring: Implementing a dynamic scoring system to identify high-risk patients.

---

## Data Model
The dataset follows a star schema architecture, consisting of:

### Fact Table (Transactional Data)
FactPatientVisits: Contains patient visit data (dates, type of care, costs, diagnosis, etc.).

### Dimension Tables
DimPatient: Patient demographic information (age, gender, parental status, etc.).
DimDate: Medical calendar and analysis periods.
DimHospital: Information on healthcare facilities.
DimGeography: Location data for patients and healthcare institutions.

### Objective
The primary goal of this project is to showcase the advanced use of Power BI for healthcare data analysis, including:

### Exploring medical trends
Optimizing care management and resource allocation
Segmenting and identifying high-risk patients
Analyzing costs and factors influencing medical expenses

## Learning Outcomes
This project has allowed me to:

Master healthcare data modeling and the creation of interactive reports in Power BI.
Design and optimize a relational data model for patient analysis.
Implement advanced DAX measures for patient tracking and segmentation.
Effectively visualize medical trends to support decision-making.

## Conclusion

This project highlights the use of Power BI to improve healthcare data management. By providing clear insights into patients and medical trends, it helps optimize resources and enhance patient care.

---

## **Database Setup & Design**

## **Schema Structure**
- The database contains **9 tables**: 'DimProduct', 'DimSalesTerritory', 'DimCustomer', 'DimGeography', 'DimDates', 'FactInternetSales', 'All Measures', 'Customers Masures' and 'Dynamic Customers'.
- These tables are designed with **primary keys**, **foreign key constraints**, and proper indexing to maintain data integrity and optimize query perfromance.
- You can find the databse schema ![image](https://github.com/user-attachments/assets/34e096fa-48ff-4618-8701-feec0b90d4cc)

## Customers Measures 

The Table that contructed this all dashboard is the Customers Measures table, she puts in highlight the more than 15 Measures. The most complex are : 

### Avg Caption 
![image](https://github.com/user-attachments/assets/55d9b1e4-5cfd-4bb0-95af-2584e3dcade7)

![image](https://github.com/user-attachments/assets/95f2b6b3-e459-4f36-9ce7-f6c0aa8a2b0d)

### Caption Customers whith Children 

![image](https://github.com/user-attachments/assets/ba8cde85-a8c4-4c0d-b95f-b3e568ca129c)

![image](https://github.com/user-attachments/assets/66b2070b-eddd-4956-a61c-9ae6401c84b2)

![image](https://github.com/user-attachments/assets/51bc1761-0d51-4821-be51-363ef0de862d)



