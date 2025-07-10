# Lung-Cancer-Analysis-Dashboard-in-Power-BI
## Table of Content
  - [Project Overview](#project-overview)
  - [Data Sources](#data-sources)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Recommendation](#recommendation)
  - [Conclusion](#conclusion)
---
## **Project Overview**
To analyze lung cancer patient data and uncover key insights around survival rates, patient demographics, treatment factors, and trends that can support healthcare decisions.
![lung1](https://github.com/user-attachments/assets/8cfb5747-5f4e-420b-8b60-e915cd234176)
![lung2](https://github.com/user-attachments/assets/5582480d-ca82-457f-b813-78e6b1816fea)
![lung3](https://github.com/user-attachments/assets/d6a1867f-84eb-4f50-9de1-ee78427b4a9c)


---

### **Data Sources**
Lung Cancer Dataset: The dataset was sourced from Kaggle, specifically designed to analyze lung cancer patient records. It includes detailed information on patient demographics, smoking history, body mass index (BMI), Cancer Stages, Treatment Types, and Survival Outcomes.
[Download here](https://www.kaggle.com/datasets/khwaishsaxena/lung-cancer-dataset)

Total Records: ~8,000+

Key Columns: Age, Gender, BMI, Smoking Status, Cancer Stage, Treatment Type, Survival Status, Family History,Country

Use Case: To explore survival patterns and highlight risk factors in lung cancer patients using visual analytics in Power BI.

---
### **Tools**
- Power BI for analysis and visualization
- Power BI/Power Query for Data cleaning

---

### **Data Cleaning/Preparation**
1. Removed duplicates
2. Created a BMI Group column by categorizing BMI values
  - Underweight, Normal, Overweight, Obese
4. Standardized “Yes/No” and date formats
5.  Standardized columns (e.g., converted "Yes/No" responses to consistent format)
6. Grouped patient age into Age Group categories:
- 21–40, 41–60, 61–80, 81+
7. Created a custom Date Table to support time-based analysis
  - Added columns such as Year, Month, Quarter, Month Name, Day of Week
8. Ensured consistent data types for proper relationships and measures

---
### **Exploratory Data Analysis**
1. Survival Analysis across Age Groups, Cancer Stage, and Smoking Status
2. BMI vs Survival Outcome using scatter plots and average calculations
3. Treatment Type vs Survival rates and Not survived
4. Year-over-Year (YoY) Comparisons on:
  - Total Number of Patients
  - Average BMI
  - Survival Rates
  - Average Treatment Duration
  - Total Survived vs Not Survived

---
### Key Insight and Findings
1. **Low Overall Survival Rate**
- Only 22% of total patients survived, while 78% did not. This indicates a critical issue that could be tied to late diagnosis, treatment effectiveness, or patient health profiles.
2. **BMI and Duration Insights**
- The average BMI is 30.49, falling into the obese category, suggesting a risk factor.Average treatment duration is quite long  459 days  hinting at the chronic nature of lung cancer care.
3. **Smoking Status**
- Majority of patients are passive and former smokers.
High number of passive smokers (5,087) shows exposure risk even without active smoking.
4. **Geographical Distribution**
- Patients are spread across Europe, but some countries (e.g., Poland, Germany, Lithuania) show higher counts, which could warrant more targeted health education or early screening in those areas.

5. **Treatment Effectiveness**
- Survival rate by treatment type is consistently 22%, regardless of method (surgery, radiation, combined, chemo).
- This uniform rate may indicate:
- Late detection stages
- Ineffective matching of treatment to patient profile
6. **Prevalence of Risk Factors**
- 75% of patients have hypertension
- 50% have family history
These are major underlying health conditions impacting survival.

7. **BMI vs Survival**
- Higher BMI groups tend to have slightly lower survival trends. Overweight and obese patients might have additional health burdens.

---
### **Recommendation**
1. **Early Detection Campaigns**
- With a low survival rate and many patients being passive smokers, awareness campaigns on early symptoms and risk factors are essential.
2. **Integrated Lifestyle Interventions**
- Encourage weight management and hypertension control as part of lung cancer treatment plans.
3. Country-Specific Focus
- Target public health interventions in high-incidence countries based on map distribution (e.g., Poland, Germany, Lithuania).
4. **Tailor Treatment Plans**
- Despite equal survival rates across treatments, investigate further with additional data (e.g., stage of cancer at treatment start) to better personalize therapies.
5. **Strengthen Screening for Passive Smokers**
- Since passive smokers make up the largest group, screening programs should not be limited to active smokers only.

---
### **Conclusion** 
This Lung Cancer Analysis Dashboard provided deep insights into the survival patterns, treatment outcomes, and risk factors affecting lung cancer patients. The analysis revealed a concerningly low survival rate of 22%, with passive and former smokers making up the largest patient groups. Risk factors such as obesity, hypertension, and family history were highly prevalent, indicating a need for more proactive preventive care.
Despite the availability of multiple treatment types, survival outcomes remained consistently low across all, highlighting the importance of early detection and personalized treatment planning. The analysis also emphasized the significance of geographic patterns, suggesting that public health efforts should be tailored to regions with higher incidence.
In conclusion, this dashboard supports data-driven healthcare interventions and encourages stronger prevention, screening, and treatment strategies to improve lung cancer outcomes.







