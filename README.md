# Project README

## Business Problem and Stakeholders

**Business Problem:** Predicting the likelihood of a customer filing an insurance claim based on various customer attributes.

**Stakeholders:**
- Insurance Company
- Marketing Team
- Underwriting Team

## Data Source

**Data Source:** The dataset used for this analysis was obtained from [(https://www.kaggle.com/datasets/sagnik1511/car-insurance-data)]. It contains information about customer demographics, driving history, and past insurance claim outcomes.

## Data Description

The dataset comprises the following columns:

- `isfemale`: Binary variable indicating gender (1 for female, 0 for male).
- `ismajority`: Binary variable indicating race (1 for majority, 0 for minority).
- `CREDIT_SCORE`: Customer's credit score.
- 'VEHICLE_OWNERSHIP': Binary variable indicating vehicle ownership (1 for yes, 0 for no).
- 'isafter2015': Binary variable indicating the year the vehicle was manufactured (1 for after 2015, 0 for before 2015).
- 'MARRIED': Binary variable indicating marital status (1 for married, 0 for unmarried).
- 'CHILDREN': Binary variable indicating the presence of children (1 for yes, 0 for no).
- 'ANNUAL_MILEAGE': Customer's annual mileage.
- 'issedan': Binary variable indicating vehicle type (1 for sedan, 0 for sports car).
- 'SPEEDING_VIOLATIONS': Number of speeding violations.
- 'DUIS': Number of DUIs (Driving Under the Influence).
- 'PAST_ACCIDENT'S: Number of past accidents.
- 'OUTCOME': Binary variable indicating insurance claim outcome (1 for filed a claim, 0 for no claim).
- 'AGE': Customer's age group (categories: '65+', '16-25', '26-39', '40-64').
- 'GENDER': Customer's gender (categories: 'female', 'male').
- 'RACE': Customer's race (categories: 'majority', 'minority').
- 'DRIVING_EXPERIENCE': Customer's years of driving experience (categories: '0-9y', '10-19y', '20-29y', '30y+').
- 'EDUCATION': Customer's education level (categories: 'high school', 'none', 'university').
- 'INCOME': Customer's income level (categories: 'upper class', 'poverty', 'working class', 'middle class').
- 'VEHICLE_YEAR': Vehicle manufacturing year (categories: 'after 2015', 'before 2015').
- 'POSTAL_CODE': Customer's postal code.
- 'VEHICLE_TYPE': Vehicle type (categories: 'sedan', 'sports car').

[Include a description of all dataset columns]

## Analytical Insights

**Insight 1:** 

![Insert Visualization Here](https://github.com/Lidivinekeng/-insurance-outcome-Project-02/blob/b5c51d0d3fd3c074b8898ab4227d086d1d6b415e/age%20vs%20outcome.png)

This visualization shows the distribution of customer ages. We can see that the majority of customers fall into the '26-39' and '40-64' age groups. This information can help the marketing team target specific age groups with tailored insurance offers.

**Insight 2:**

![Insert Visualization Here](https://github.com/Lidivinekeng/-insurance-outcome-Project-02/blob/7c438d84bbfbdc7d885deb0b469141b5a9a4429d/credit%20score%20vs%20outcome.png)

This visualization illustrates the relationship between credit score and the likelihood of filing an insurance claim. Customers with lower credit scores appear to be more likely to file claims. This insight can be valuable for the underwriting team in assessing risk.

## Model Metrics

The best model for predicting insurance claim likelihood achieved the following metrics:
- Accuracy: XX%
- Precision: XX%
- Recall: XX%
- F1-Score: XX%
- ROC-AUC: XX%

## Model Performance and Business Problem Solving

The predictive model provides a valuable tool for the insurance company to assess the likelihood of a customer filing a claim. By identifying high-risk customers, the company can take proactive measures to manage risk and optimize insurance pricing.

## Recommendations

1. **Targeted Marketing:** Use the insights from age distribution to tailor marketing campaigns for specific age groups, offering incentives or discounts to customers in the '26-39' and '40-64' age brackets.

2. **Underwriting Guidelines:** Share the insights regarding the relationship between credit scores and claim likelihood with the underwriting team. Consider adjusting underwriting guidelines to account for credit score as a risk factor.

3. **Claim Prevention:** Develop strategies to engage with high-risk customers and offer services or resources that could help prevent accidents or claims, ultimately reducing the company's claim payout.

4. **Continuous Monitoring:** Regularly update and retrain the predictive model with new data to ensure its accuracy and relevance in assessing customer risk.

By implementing these recommendations and leveraging the predictive model, the insurance company can improve its risk management, customer targeting, and overall business performance.

