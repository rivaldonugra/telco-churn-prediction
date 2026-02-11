## Telco Churn Prediction
## Background

The telecommunications industry is highly competitive, making customer churn a major challenge. Customers can easily switch providers due to factors such as pricing, contract terms, or service quality. Therefore, companies need to understand the characteristics of customers who are likely to churn so they can implement effective and targeted retention strategies.

## Dataset

The Telco Customer Churn dataset contains information about customer demographics, services used, contract details, and payment methods. The target variable is customer churn status (0: Not Churn, 1: Churn).

### Attribute Information

| Attribute        | Data Type | Description                                         |
| ---------------- | --------- | --------------------------------------------------- |
| Dependents       | object    | Whether the customer has dependents                 |
| tenure           | int       | Total number of months the customer has subscribed  |
| OnlineSecurity   | object    | Whether the customer has online security service    |
| OnlineBackup     | object    | Whether the customer has online backup service      |
| InternetService  | object    | Type of internet service used                       |
| DeviceProtection | object    | Whether the customer has device protection service  |
| TechSupport      | object    | Whether the customer has tech support service       |
| Contract         | object    | Type of contract based on duration                  |
| PaperlessBilling | object    | Whether the customer uses paperless billing         |
| MonthlyCharges   | float     | Monthly subscription fee                            |
| Churn            | object    | Whether the customer has stopped subscribing or not |

## Analysis Process

The analysis begins with EDA to understand churn patterns, followed by data preprocessing and classification model development. Model evaluation prioritizes recall to minimize undetected churn customers. The final model is saved in pickle format for future use.

