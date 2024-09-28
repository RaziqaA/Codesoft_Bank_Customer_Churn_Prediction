# Bank Customer Churn Prediction

## Overview
The Bank Customer Churn Prediction project aims to identify customers who are likely to leave the bank using machine learning techniques. By predicting customer churn, banks can proactively engage with at-risk customers and implement retention strategies that enhance customer satisfaction and loyalty.

### Dataset
The dataset consists of **10,000 rows** and the following columns:

- **RowNumber**: Index of the customer
- **CustomerId**: Unique identifier for each customer
- **Surname**: Customer's surname
- **CreditScore**: Credit score of the customer
- **Geography**: Customer's geographical location
- **Gender**: Customer's gender
- **Age**: Age of the customer
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance of the customer
- **NumOfProducts**: Number of banking products used by the customer
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Indicates if the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated annual salary of the customer
- **Exited**: Churn indicator (1 = Customer has exited, 0 = Customer is still with the bank)

## Methodology

### Data Preprocessing
1. **Encoding**: Categorical variables were converted into numerical format using one-hot encoding to prepare them for model training.
2. **Scaling**: Features were scaled to standardize the range of independent variables, improving model performance and convergence.
3. **SMOTE (Synthetic Minority Over-sampling Technique)**: To address class imbalance in the dataset, SMOTE was employed to generate synthetic samples for the minority class (customers who exited).
4. **Saving**: The processed dataset was saved for efficient loading during model training.

### Algorithms Used
Various machine learning algorithms were employed to predict customer churn, including:

- **Logistic Regression (LR)**
- **Support Vector Machine (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree (DT)**
- **Random Forest (RF)**
- **Gradient Boosting Classifier (GBC)**

### Performance
The Random Forest model demonstrated exceptional accuracy and precision, outperforming other algorithms in predicting customer churn. This model's robustness makes it a reliable choice for real-world applications in customer retention strategies.

## Conclusion
The Bank Customer Churn Prediction project showcases the application of machine learning to tackle a significant business problem in the banking industry. By leveraging data-driven insights, banks can enhance customer experiences and ultimately improve retention rates.

## Getting Started
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bank-customer-churn-prediction.git
   cd bank-customer-churn-prediction
# Bank Customer Churn Prediction

## Overview
The Bank Customer Churn Prediction project aims to identify customers who are likely to leave the bank using machine learning techniques. By predicting customer churn, banks can proactively engage with at-risk customers and implement retention strategies that enhance customer satisfaction and loyalty.

### Dataset
The dataset consists of **10,000 rows** and the following columns:

- **RowNumber**: Index of the customer
- **CustomerId**: Unique identifier for each customer
- **Surname**: Customer's surname
- **CreditScore**: Credit score of the customer
- **Geography**: Customer's geographical location
- **Gender**: Customer's gender
- **Age**: Age of the customer
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance of the customer
- **NumOfProducts**: Number of banking products used by the customer
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Indicates if the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated annual salary of the customer
- **Exited**: Churn indicator (1 = Customer has exited, 0 = Customer is still with the bank)

## Methodology

### Data Preprocessing
1. **Encoding**: Categorical variables were converted into numerical format using one-hot encoding to prepare them for model training.
2. **Scaling**: Features were scaled to standardize the range of independent variables, improving model performance and convergence.
3. **SMOTE (Synthetic Minority Over-sampling Technique)**: To address class imbalance in the dataset, SMOTE was employed to generate synthetic samples for the minority class (customers who exited).
4. **Saving**: The processed dataset was saved for efficient loading during model training.

### Algorithms Used
Various machine learning algorithms were employed to predict customer churn, including:

- **Logistic Regression (LR)**
- **Support Vector Machine (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree (DT)**
- **Random Forest (RF)**
- **Gradient Boosting Classifier (GBC)**

### Performance
The Random Forest model demonstrated exceptional accuracy and precision, outperforming other algorithms in predicting customer churn. This model's robustness makes it a reliable choice for real-world applications in customer retention strategies.

## Conclusion
The Bank Customer Churn Prediction project showcases the application of machine learning to tackle a significant business problem in the banking industry. By leveraging data-driven insights, banks can enhance customer experiences and ultimately improve retention rates.

## Getting Started
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bank-customer-churn-prediction.git
   cd bank-customer-churn-prediction

### Contributions

Contributions are welcome! Feel free to submit a pull request or open an issue if you have suggestions for improvements or additional features.

### Contact
For any questions or inquiries, please reach out to:

Name: Syeda Raziqa


Email: syedaraziqa01@gmail.com 

LinkedIn: https://www.linkedin.com/in/syedaraziqa07/


