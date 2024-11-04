
# Customer Churn Prediction

## Introduction
Customer attrition or churn is a critical issue for businesses, as it can have a significant impact on revenue. This project aims to build a model that can predict which customers are likely to churn, allowing the business to implement targeted retention strategies.

## Dataset
The project uses the Telco Customer Churn dataset, which contains information about customer demographics, services, and churning behavior. The dataset includes the following features:

- `customerID`: Unique identifier for each customer
- `gender`: Gender of the customer
- `SeniorCitizen`: Whether the customer is a senior citizen or not
- `Partner`: Whether the customer has a partner or not
- `Dependents`: Whether the customer has dependents or not
- `tenure`: Number of months the customer has stayed with the company
- `PhoneService`: Whether the customer has a phone service or not
- `MultipleLines`: Whether the customer has multiple lines or not
- `InternetService`: Customer's internet service provider
- `OnlineSecurity`: Whether the customer has online security or not
- `OnlineBackup`: Whether the customer has online backup or not
- `DeviceProtection`: Whether the customer has device protection or not
- `TechSupport`: Whether the customer has tech support or not
- `StreamingTV`: Whether the customer has streaming TV or not
- `StreamingMovies`: Whether the customer has streaming movies or not
- `Contract`: The contract term of the customer
- `PaperlessBilling`: Whether the customer has paperless billing or not
- `PaymentMethod`: The payment method of the customer
- `MonthlyCharges`: The monthly charges for the customer
- `TotalCharges`: The total charges for the customer
- `Churn`: Whether the customer churned or not

## Methodology
The project follows these steps:

1. **Exploratory Data Analysis**: Analyze the dataset to understand the distribution of features and their relationship with the target variable (Churn).
2. **Data Preprocessing**: Clean and transform the data, handle missing values, and encode categorical features.
3. **Feature Selection**: Select the most important features that contribute to the prediction of customer churn.
4. **Model Training**: Train several classification models, including Logistic Regression, Decision Tree, SVM, KNN, Random Forest, and Gradient Boosting.
5. **Model Evaluation**: Evaluate the performance of the models using metrics such as accuracy, precision, recall, and F1-score.
6. **Hyperparameter Tuning**: Tune the hyperparameters of the best-performing models to further improve their performance.
7. **Final Model Selection**: Choose the final model based on the evaluation results and deploy it for real-world use.

## Results
The best-performing model was the Random Forest Classifier, which achieved an accuracy of 0.77 on the test set. The Gradient Boosting Classifier also performed well, with an accuracy of 0.78.

## Usage
To run the project, you will need to have the following dependencies installed:

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can then clone the repository, navigate to the project directory, and run the Jupyter Notebook or Python script containing the code.

## Contribution
If you would like to contribute to this project, feel free to submit a pull request. Contributions can include, but are not limited to, the following:

- Implementing additional preprocessing steps or feature engineering techniques
- Experimenting with different machine learning models or hyperparameter tuning strategies
- Improving the code structure or documentation
- Suggesting new ideas or use cases for the project

## License
This project is licensed under the [MIT License](LICENSE).
