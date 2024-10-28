# Employee Attrition Analysis Using Pyspark

## Overview

This project focuses on analyzing the attrition analysis dataset from Kaggle to find out the reason for the attrition rate in the company. By finding more insights on the reason of attrition rate, the company can take further steps to reduce the attrition rate. The dataset contains the attrition status and various other features of the employees.

## Dataset

The dataset used is from Kaggle : [Attrition Analysis](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Methodology

- Pyspark
- DataBricks

## Analysis Queries

 - `Filtering Attrition Data` :
     To find out the total employees who have actually left the company. It can be seen that about 16.1% employees have left the company
   ![newplot (1)](https://github.com/user-attachments/assets/4b3390b1-8c1d-4808-8b4a-b2d364049ca6)

 - `Attrition Analysis Based on Age Groups`:
     This analysis identifies the age ranges of employees who left the company, revealing that 35% of attrition occurred within the 26-32 age group
   ![newplot](https://github.com/user-attachments/assets/aa1b2911-e7fb-44ad-a8fd-c6685e3e0674)

 - `Attrition Analysis Based on Department`:
     This analysis reveals that 133 employees from the Research Department have left the company
   ![newplot (1)](https://github.com/user-attachments/assets/1d2ff780-a107-43b7-a389-63b15b281488)

 - `Attrition Analysis Based on Education`:
     This analysis identifies the age ranges of employees who left the company, revealing that 41% of attrition occurred within the bachelor's education group
   ![newplot (2)](https://github.com/user-attachments/assets/a6d636c0-3b29-444d-9707-3475b9245d59)

 - `Attrition Analysis Based on Environment Satisfaction`:
     This analysis reveals that employees who left the company had Low Environment Satisfaction Level
   ![newplot](https://github.com/user-attachments/assets/dd4b85ca-6531-469f-b3ea-35ce0ab56adc)

 - `Attrition Analysis Based on Business Travel`:
     This analysis reveals that employees who left the company had travelled rarely for business purposes
   ![newplot (1)](https://github.com/user-attachments/assets/8b8974e5-d461-4f93-a140-7620220d9686)

 - `Attrition Analysis Based on Years At Company`:
     This analysis reveals that employees with 1 years of experience i.e 24.9% are the ones mostly who have left the company.
   ![newplot (2)](https://github.com/user-attachments/assets/b4e7d399-0e6b-4f9d-a7da-d6ec78f0fec9)

 - `Attrition Analysis Based on Years Since Last Promotion`:
     This analysis reveals that the employees who have left the company where not promoted since last year
   ![newplot](https://github.com/user-attachments/assets/127972d2-2385-42b7-8845-5706f2268aca)

 - `Attrition Analysis Based on Average monthly income, education and attrition`:
     This analysis reveals that attrition rate is high for the ones whose average monthly income is low. And the difference between the average monthly income and attrition rate is in         the doctor education group.
   ![newplot (2)](https://github.com/user-attachments/assets/a22c7a99-7612-460f-b84e-05757824d5fe)

  - `Attrition Analysis Based on distance from home, job role and attrition`:
     This analysis reveals that the employees who have left the company were staying far from office.
    ![newplot (3)](https://github.com/user-attachments/assets/21012de0-b819-4db5-89fb-5d95fd93c78b)

  ## Business Insights
  +  16.1% of employees have left the company, highlighting a significant turnover rate that needs further investigation.
  +  35% of attrition is from the 26-32 age group, suggesting a need for targeted retention programs for younger employees.
  +  133 employees from the Research Department have left, indicating a critical need for evaluation and potential improvement in this area.
  +  41% of departing employees held a bachelor’s degree, pointing to the need for better career development and advancement opportunities.
  +  Employees with low environment satisfaction are more likely to leave, highlighting the need for enhanced workplace conditions.
  +  Employees who rarely traveled for business are among those who left, suggesting a review of travel policies and consideration for remote work options.
  +  24.9% of employees left after just one year, indicating the importance of onboarding and support for new hires.
  +  Employees not promoted in the past year are more likely to leave, signaling the need for more frequent performance evaluations.
  +  High attrition among employees with lower average incomes suggests a need for salary reviews to remain competitive.
  +  Employees living farther from the office are more likely to leave, indicating potential benefits from flexible work arrangements or relocation assistance.
  
  ## Conclusion

  Overall, these insights emphasize the need for a comprehensive retention strategy that addresses various factors influencing employee turnover. By focusing on engagement, career     development, compensation, and work-life balance, the company can create a more positive work environment that encourages employees to stay long-term.

