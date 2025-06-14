# Health Data Analysis

This project analyzes synthetic health data to understand patterns and risk factors associated with diabetes. The dataset includes biometric and lifestyle data such as age, BMI, blood pressure, gender, and smoking status.

## Objective

To explore the relationships between age, BMI, blood pressure, smoking habits, and diabetes prevalence. The goal is to uncover insights that could support preventive healthcare strategies and early detection efforts.

## Key Insights
- ### **Diabetes Prevalence by Age Group**
  
  The analysis of diabetes prevalence across age groups reveals a clear upward trend with age. Ranked from lowest to highest prevalence:
  - Age 30–39: Lowest prevalence  
  - Age 20–29  
  - Age 40–49  
  - Age 50–59  
  - Age 60–69  
  - Age 70–79: Highest prevalence

  This pattern underscores the strong association between increasing age and diabetes risk.

- ### **BMI Distribution by Diabetes Status**

  Box plot analysis was used to compare Body Mass Index (BMI) between individuals with and without diabetes:

  - **Non-diabetic individuals**:  
    - BMI range: approximately 21 to 29  
    - Median BMI: around 23

  - **Diabetic individuals**:  
    - BMI range: approximately 24 to 35  
    - Median BMI: around 32

  The findings show a higher BMI distribution among diabetic individuals, suggesting a strong correlation between obesity and diabetes prevalence.

- ### **Average Blood Pressure by Smoking Status**

  A side-by-side bar plot comparison was used to assess systolic and diastolic blood pressure based on smoking status:

  | Smoking Status | Systolic BP (mmHg) | Diastolic BP (mmHg) |
  |----------------|--------------------|----------------------|
  | Current        | ~121               | ~82                  |
  | Former         | ~121               | ~80                  |
  | Never          | ~120               | ~78                  |

  Results indicate slightly higher average blood pressure among individuals who currently smoke or have smoked in the past, compared to non-smokers.

- ### **Average Blood Pressure by Gender**

  Average blood pressure was also analyzed by gender:

  - **Females**:  
    - Systolic BP: approximately 124 mmHg  
    - Diastolic BP: approximately 80 mmHg

  - **Males**:  
    - Systolic and diastolic BP values were similar to those of females, with minimal variation observed.

- ### **Diabetic Patients with Elevated Blood Pressure**

  After filtering for diabetic individuals with elevated blood pressure, it was observed that:

  - **88.89%** of diabetic patients had elevated blood pressure levels.

  This finding highlights the frequent co-occurrence of hypertension among diabetic individuals and suggests the importance of integrated care strategies in clinical settings.
  


## Recommendations
Based on the findings, the following recommendations are proposed:

- **Age-Based Screening**: Since diabetes prevalence increases with age, implement targeted screening programs for individuals aged 50 and above.
  
- **Obesity Interventions**: With higher BMI among diabetic individuals, promote weight management programs, nutritional education, and physical activity initiatives.

- **Gender-Sensitive Care**: Although differences in blood pressure by gender were minimal, ensure that health communication materials are inclusive and representative.

- **Blood Pressure Monitoring for Diabetics**: With 88.89% of diabetic patients having elevated BP, prioritize hypertension screening and treatment in diabetic care protocols.

