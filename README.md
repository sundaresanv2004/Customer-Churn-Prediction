# Customer-Churn-Prediction
This project focuses on predicting customer churn for a telecom company using synthetic customer data. Customer churn prediction is a critical task for businesses to identify which customers are likely to discontinue their services, allowing for proactive retention strategies.

###  For more info read Documentation
### **Project Overview**

- **Objective**: Develop a predictive model to identify customers at high risk of churn based on various features.
- **Dataset**: Synthetic data with attributes such as `CustomerID`, `Age`, `Gender`, `ContractType`, `MonthlyCharges`, `TotalCharges`, `TechSupport`, `InternetService`, `Tenure`, `PaperlessBilling`, `PaymentMethod`, and `Churn`.
- **Techniques**: Utilizes classification algorithms such as Logistic Regression and Decision Trees. Focuses on handling imbalanced data through techniques such as class weighting and resampling.
- **Preprocessing**: Includes handling missing values, encoding categorical variables, and splitting the data into training, validation, and testing sets.
- **Evaluation**: Assesses model performance using metrics like precision, recall, F1-score, and ROC-AUC.

### **Features**

- **Data Generation**: Synthetic data generation with realistic distributions, correlations, and outliers.
- **Exploratory Data Analysis (EDA)**: Summary statistics, visualizations, and correlations.
- **Data Preprocessing**: Missing value handling, encoding, splitting, and balancing the dataset.
- **Model Building**: Experimentation with different classification algorithms and hyperparameter tuning.
- **Model Evaluation**: Detailed evaluation of model performance with focus on precision and recall due to imbalanced classes.

### **Getting Started**

1. **Clone the Repository**: `git clone https://github.com/sundaresanv/customer-churn-prediction.git`
2. **Install Dependencies**: `pip install -r requirements.txt`
3. **Run the Project**: Follow the instructions in `README.md` to generate data, train models, and evaluate results.

### **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
