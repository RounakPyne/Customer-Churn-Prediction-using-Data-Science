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
[Categorical Analysis]
(![Untitled](https://github.com/user-attachments/assets/1e0aa4b6-f221-4df3-bad9-3e5e8d127e03)
- ![Untitled](https://github.com/user-attachments/assets/27240e70-5dbc-4efb-bc7b-1d914c36c330)
- ![Untitled](https://github.com/user-attachments/assets/e8478c96-77a9-4bf4-80dc-f983b6ccc74a)
- ![Untitled](https://github.com/user-attachments/assets/e991fc72-0aec-4d32-bac7-2b12c75baecc)
- ![Untitled](https://github.com/user-attachments/assets/33bce883-1144-49ab-b136-21bc8a7659cc)
- ![Untitled](https://github.com/user-attachments/assets/4ae9011d-8991-4e15-99fc-f846a4cf6f4c)
- ![Untitled](https://github.com/user-attachments/assets/3f5fac36-a44b-41b3-aa3d-3bcac526673a)
- ![Untitled](https://github.com/user-attachments/assets/4bf4e2c8-564e-4b77-aa74-38242f7d02e4)
- ![image](https://github.com/user-attachments/assets/1e65cbec-5514-4746-bb75-cc9ca48ac038)
- ![Untitled](https://github.com/user-attachments/assets/f03357ef-2bdb-4c64-9b96-4767709b8328)
- ![Untitled](https://github.com/user-attachments/assets/e3ba6112-5251-4089-b7b6-7f112bee88b9)
- ![Untitled](https://github.com/user-attachments/assets/c2fb2381-1690-4993-bcc8-09135b0b577f)
- ![Untitled](https://github.com/user-attachments/assets/df6cc944-8f35-4480-b9fa-32feeb1a64e4)
- ![Untitled](https://github.com/user-attachments/assets/4ef9bc86-0818-4c4c-8ba6-3a91959df0b6)
- ![Untitled](https://github.com/user-attachments/assets/73618285-6915-43e5-882c-30fbea3a4374)
- ![Untitled](https://github.com/user-attachments/assets/a4af592a-5964-43a7-bf3d-9ff7744ea91c)
- ![Untitled](https://github.com/user-attachments/assets/34c2f2f6-5759-47b2-8ec6-b8b0f2eea41c)

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
