# Customer Churn Analysis

## Overview
This project analyzes customer churn in the telecommunications industry using a dataset containing customer information. The goal is to identify factors influencing churn and provide actionable insights for customer retention strategies.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [Next Steps](#next-steps)
- [License](#license)

## Introduction
Customer churn is a significant challenge for telecom companies, affecting revenue and growth. This analysis leverages data to uncover trends and insights that can help mitigate churn.

## Dataset
The dataset used in this analysis is sourced from [Kaggle]. It contains information on 7,043 customers with 21 features, including:

- **CustomerID**: Unique identifier for each customer
- **Churn**: Indicates if the customer has churned (Yes/No)
- **Tenure**: Duration of the customer relationship in months
- **MonthlyCharges**: Monthly fee charged to the customer
- **TotalCharges**: Total charges incurred by the customer

### Sample Data
![Sample Data](![image](https://github.com/user-attachments/assets/a3a4d4fd-b5c5-441d-92e9-4fcb7c417601)
)

## Exploratory Data Analysis
### Data Cleaning
- Handled missing values in the `TotalCharges` column.
- Converted data types for analysis.

### Churn Distribution
- Visualizing churn rates.
![Churn Distribution](![Untitled](https://github.com/user-attachments/assets/96e2ee50-a6ab-4ced-84f4-e51fedc7af71)
)

### Tenure Analysis
- Grouped customers by tenure and analyzed churn rates.
![Tenure Analysis](![Untitled](https://github.com/user-attachments/assets/0abff0bc-0616-4fef-8659-2539a4a68467)
)

### Categorical Variables
- Analyzed categorical variables affecting churn.
![Categorical Analysis](![Untitled](https://github.com/user-attachments/assets/1e0aa4b6-f221-4df3-bad9-3e5e8d127e03)

### Checking the total charges by monthly charges
- Checeking the relation between monthly and total charges relationship
- ![Untitled](https://github.com/user-attachments/assets/c03108fe-54db-464a-89ed-6a6460de8eb4)

### Effect of Monthly charges on Churning
- Lets See if monthly charges effect the customer to churn or not
- ![Untitled](https://github.com/user-attachments/assets/0be35d9f-92f8-4ffc-9e0f-36503035ba50)

### Effect of Total charges on Churning
- Lets See if monthly charges effect the customer to churn or not
- ![Untitled](https://github.com/user-attachments/assets/eb14cf0d-8bf4-4b68-a772-b4fb028ff003)

### Insight
**Surprising insight ** as higher Churn at lower Total Charges
However if we combine the insights of 3 parameters i.e. Tenure, 
Monthly Charges & Total Charges then the picture is bit clear :- Higher Monthly Charge at lower tenure results into lower Total Charge. 
Hence, all these 3 factors viz Higher Monthly Charge, Lower tenure and Lower Total Charge are linkd to High Churn.

### Checking Correlation 
![Untitled](https://github.com/user-attachments/assets/534c786e-cb19-4cfa-a602-c6600770e5d5)

### Conclusion
- These are some of the quick insights from this exercise:

    * Electronic check medium are the highest churners
    * Contract Type - Monthly customers are more likely to churn because of no contract terms, as they are free to go customers.
    * No Online security, No Tech Support category are high churners
    * Non senior Citizens are high churners

### Predictive Model using SMOTE
- Using SMOTE Analysis we have made a predictive model.
- ![image](https://github.com/user-attachments/assets/61bdd29b-118a-4f97-b293-57a2792c2a3c)

### Confusion Metrics
- ![image](https://github.com/user-attachments/assets/23ca95e1-7e4a-43eb-9481-40edafb221f8)


## Results
- Key factors influencing churn include tenure, having a partner, and the type of internet service.
- Customers with shorter tenure have a higher churn rate.

## Next Steps
- Conduct further analyses to identify additional retention strategies.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
