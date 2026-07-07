# CAPSTONE PROJECT
Urban Health Analytics: Medical Insurance Charges Prediction

For this project, we worked as a team of Junior Data Scientists for a healthcare-focused analytics consulting management. The company works with insurance providers to help them better understand how patient characteristics influence insurance costs.
The team's responsibility was to build a linear regression model that predicts insurance charges based on patient attributes, the **insurance.csv** dataset in this reppository was used for this project. The dataset contained the following information about patients: age, gender, BMI, number of children, smoking status, region, and insurance charges. 

# Project Overview
UrbanNest Health Analytics currently lacks a standardized method for estimating insurance premiums, resulting in reliance on outdated heuristics instead of statistical patterns.

Goal: Develop a data-driven system to predict charges using objective customer characteristics.

The project covers:
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Correlation Analysis
- Visualizations using matplotlib and seaborn

# Tools and Libraries

- Google Colab
- Python
- Pandas
- Matplotlib & Seaborn
- Scikit learn

# Dataset 
- [GitHub Repository](https://github.com/JustusAkuku/CAPSTONE-PROJECT/raw/main/insurance.csv)
- [Download insurance.csv](https://github.com/JustusAkuku/CAPSTONE-PROJECT/raw/main/insurance.csv)

# How to Run
[Open in Google Colab](https://colab.research.google.com/github/JustusAkuku/CAPSTONE-PROJECT/blob/main/CAPSTONE PROJECT GROUP 13.ipynb)






- 
  




Features:

age – Age of the insured person

sex – Gender
ith my 
bmi – Body Mass Index

children – Number of dependents

smoker – Smoking status (yes/no)

region – Residential area (northeast, southeast, southwest, northwest)

charges – Insurance cost (target variable)


## :bulb: KEY INSIGHTS
*Smoking  status drives the insurance charges, accompanied by factors such as BMI and age*.

**Scatterplot Analysis**

***smoking is the dominant cost driver***
Smokers (blue) cluster well above non-smokers (orange) across every age, with charges typically $15K-$50K+ versus $2K-$15K. The smoker premium far exceeds the effect of age alone.

***Age has a positive but modest effect***
The trend line rises steadily from roughly $27K at age 20 to about $42K ata age 65, confirming a positive age-cost relationship, though the slope is gradual relative to the spread within each group.

***Distinct sub-bands suggest a third factor***
The smoker group splits into two visible bands ($15K-$30K and $30K-$65K), pointing to an additional driver, the Body Mass Index (BMI).

***BMI amplifies the smoker charges sharply***
- **Strong Interaction effect**. Smoker charges climb steeply with BMI, rising from $20K at BMI 20 to over $50K at BMI 45, a near 2.5x escalation driven by the compounding of two risk factors.
- **Flat non-smoker curve**. Non-smoker charges hold steady in the $5K-$12K band regardless of BMI, signaling a low-variance, high predictable risk pool.
- **Obesity threshold matters**. Smoker charges accelerate noticeably past BMI 30, where most high-cost outliers ($55K- $65K) concetrate, making the obese-smoker segment the dominant cost driver.
- Smoking status accounts for the highest medical insurance charges, Body Mass Index and age also act as the dominant financial drivers in predicting total insurance claims.
- Number of dependent children exerts a secondary, modest linear upward force on final healthcare premium pricing.
- Sex and geographical location yield minimal statistical correlation.
- These findings align with real‑world expectations: smoking significantly increases health risks and costs, while BMI and age correlate with long‑term medical expenses.
- **Key Takeaway**: Focus premium pricing on lifestyle factors and physical health indices.




