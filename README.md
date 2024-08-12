# HealthMetrix-Diabetes-Insights-and-Analysis
![Frontpage](https://github.com/user-attachments/assets/bdbc10a0-fea9-4833-843c-62b5539a1d5f)
Analyze diabetes-related data to identify trends and provide actionable insights for healthcare stakeholders, aiding in prevention and management strategies.

## Introduction

Diabetes is a chronic disease that significantly impacts public health globally. The prevalence of diabetes and its complications necessitates continuous monitoring and analysis of related health metrics. The purpose of this report is to analyze diabetes-related data, identify key trends and patterns, and provide actionable insights for healthcare stakeholders. The analysis will assist in better understanding the factors influencing diabetes and help design effective strategies for prevention and management.

## Objective

The primary objective of this analysis is to assess the health metrics related to diabetes within a population of 100,000 patients. The goal is to identify significant patterns, correlations, and trends that can help in understanding the distribution of diabetes and its associated risk factors such as hypertension, heart disease, BMI, and smoking habits. This analysis aims to support healthcare providers in making informed decisions and implementing data-driven interventions to manage and prevent diabetes.

## Stakeholders

### 1. Healthcare Providers: 
Doctors, nurses, and healthcare professionals who are directly involved in patient care and diabetes management.
2. Public Health Officials: Government and non-governmental organizations involved in designing public health policies and initiatives related to diabetes.
3. Patients: Individuals diagnosed with diabetes or at risk of developing diabetes.
4. Researchers: Scientists and researchers studying diabetes to develop better treatments and preventive measures.
5. Insurance Companies: Entities involved in providing health insurance and assessing the risks associated with diabetes.

## Data Processing

The data used for this analysis comprises 100,000 patient records, including key variables such as patient ID, age, gender, hypertension status, heart disease status, smoking history, BMI, HbA1c levels, and blood glucose levels. The data was processed and cleaned to handle missing values, outliers, and ensure consistency across all records.

## Key steps involved in data processing:

1. Data Cleaning: Removal of duplicate records, handling missing values, and correcting inconsistent data entries.
2. Data Transformation: Calculating derived metrics such as the percentage of patients with controlled diabetes, average BMI, and others.
3. Data Validation: Ensuring the accuracy and validity of the data before analysis.

## Analysis and Visualization

The analysis was conducted using Tableau to visualize key health metrics and gain insights into the distribution of diabetes among the patient population. The following KPIs were created and visualized:

1. Total Number of Patients: Count of all patients.
2. Number of Patients with Diabetes: Count of patients diagnosed with diabetes.
3. Percentage of Patients with Diabetes: (Number of Patients with Diabetes / Total Number of Patients) * 100.
4. Average Age of Patients: Mean age of all patients.
5. Average BMI of Patients: Mean BMI of all patients.
6. Distribution of Blood Glucose Levels: Visualization using a histogram to show the spread of blood glucose levels.
7. Percentage of Patients with Hypertension: (Number of Patients with Hypertension / Total Number of Patients) * 100.
8. Percentage of Patients with Heart Disease: (Number of Patients with Heart Disease / Total Number of Patients) * 100.
9. Smoking History Distribution: Visualization of smoking history (e.g., never, current, ex-smoker) using a bubble chart.
10. Patients with BMI Greater Than Average BMI: Count of patients with a BMI greater than the average BMI.
11. Patients with Hypertension and Diabetes: Count of patients with both hypertension and diabetes.
12. Patients with Heart Disease and Diabetes: Count of patients with both heart disease and diabetes.
13. Patients with Heart Disease and Hypertension: Count of patients with both heart disease and hypertension.
14. Gender Distribution of Patients with Diabetes: Visualization using a donut chart to show the gender distribution.
15. HbA1c Levels Distribution: Visualization using a bar chart to show the distribution of HbA1c levels.

## Tableau Dashboard
   
![Tableau Dashboard](https://github.com/user-attachments/assets/2cff11f6-f50c-4c79-81cd-ed4412070b04)

## SQL Queries
Check the SQL work done for this project.

## Insights

1. Controlled Diabetes: 61.73% of the patients with diabetes have their condition under control, which is a positive indicator but still leaves a significant portion of patients at risk.
2. Age and Diabetes: The average age of patients is 27.48 years, which suggests that diabetes affects a relatively young population in this dataset.
3. BMI and Blood Glucose: A correlation between BMI and blood glucose levels was observed, indicating that higher BMI is often associated with elevated blood glucose levels.
4. Hypertension and Heart Disease: A considerable percentage of patients with diabetes also suffer from hypertension (7.49%) and heart disease (3.94%), highlighting the need for integrated care approaches.

## Findings

1. Prevalence of Diabetes: 8.5% of the patient population is diagnosed with diabetes, indicating a significant public health concern.
2. Gender Differences: The gender distribution analysis shows a slightly higher prevalence of diabetes among females compared to males.
3. Smoking History: A large proportion of patients (35,095) have never smoked, which may have a protective effect against developing diabetes.

## Recommendations

1. Targeted Interventions: Focus on younger populations who are at risk of developing diabetes, with personalized interventions based on BMI and blood glucose levels.
2. Integrated Care Programs: Develop care programs that address both diabetes and associated conditions like hypertension and heart disease.
3. Smoking Cessation Programs: Promote smoking cessation programs to reduce the risk of diabetes and related complications.
4. Education and Awareness: Increase patient awareness about the importance of maintaining a healthy BMI and regular monitoring of blood glucose levels.

## Challenges

1. Data Quality: Ensuring the accuracy and completeness of the data was a challenge, especially with missing or inconsistent entries.
2. Patient Privacy: Handling sensitive patient information while maintaining confidentiality and adhering to data protection regulations.
3. Complexity of Disease Management: Diabetes management requires addressing multiple comorbidities, making it complex to analyze and provide comprehensive care recommendations.

## Conclusion

This analysis provides a comprehensive overview of the diabetes landscape within the patient population. The findings highlight the need for targeted interventions, particularly for younger individuals and those with associated risk factors like hypertension and obesity. By leveraging the insights gained from this analysis, stakeholders can develop more effective strategies for managing diabetes and improving patient outcomes.
