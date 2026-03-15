# Global Cancer Data Analysis & Severity Prediction

## Project Overview

This project analyzes a **Global Cancer Patients Dataset (2015--2024)**
to understand patterns in cancer diagnosis, risk factors, treatment
costs, and survival outcomes.

The goal is to use **data analysis and machine learning** to identify
important factors that influence **cancer severity and patient
survival**.

The project includes **exploratory data analysis (EDA), visualization,
statistical analysis, and predictive modeling**.

------------------------------------------------------------------------

## Dataset

The dataset includes global patient information such as:

-   Age
-   Gender
-   Country / Region
-   Cancer Type
-   Cancer Stage
-   Genetic Risk
-   Smoking and Alcohol Usage
-   Air Pollution Exposure
-   Obesity Level
-   Treatment Cost
-   Survival Years
-   Severity Score (Target Variable)

These variables help analyze **health, environmental, and lifestyle
factors** affecting cancer outcomes.

------------------------------------------------------------------------

## Key Findings

### Cancer Stage Distribution

-   The dataset includes **8 cancer types** with balanced
    representation.
-   **Stage II** is one of the most common diagnosis stages.

### Risk Factor Impact

Lifestyle and environmental variables such as **genetic risk, smoking,
alcohol consumption, air pollution, and obesity** show noticeable
relationships with **cancer severity**.

### Early Diagnosis

-   Around **38% -- 40% of cancers are detected in early stages (Stage 0
    or Stage I)**.
-   **Liver cancer** shows higher early detection rates.
-   **Lung cancer** has lower early detection rates.

### Treatment Cost Insights

-   Treatment costs tend to be **higher in developed countries**.
-   Costs generally **increase with patient age**.
-   Gender differences in treatment cost are minimal.

### Survival vs Treatment Cost

The analysis shows **no strong correlation between higher treatment cost
and longer survival**, suggesting that survival outcomes depend more on
**medical and biological factors**.

### Cancer Stage Impact

Later cancer stages are associated with: - **Higher treatment costs** -
**Lower survival years**

This highlights the importance of **early detection and screening**.

------------------------------------------------------------------------

## Machine Learning Model

A **Random Forest Regressor** was used to predict the **Cancer Severity
Score**.

Steps performed: - Data preprocessing - Encoding categorical variables -
Train-test split - Feature scaling - Hyperparameter tuning using
**GridSearchCV**

Evaluation Metric: - **R² Score**

The model helps identify **important predictors influencing cancer
severity**.

------------------------------------------------------------------------

## Conclusion

This project demonstrates how **data science and machine learning** can
be applied to healthcare datasets to identify **risk factors, cost
patterns, and severity predictors** in cancer patients. The insights
highlight the critical role of **early detection and preventive
healthcare strategies**.
