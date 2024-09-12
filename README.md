# Fraud Detection Project

This repository contains a machine learning model to predict fraudulent transactions for a financial company. The goal of the project is to build a predictive model that detects fraudulent transactions and generate insights to create a proactive fraud prevention strategy.

## Project Overview

The dataset provided consists of 6,362,620 rows and 10 columns, including various features related to customer transactions. The goal is to identify which transactions are fraudulent based on historical data and design preventive measures for future fraud detection.

### Key Steps in the Project:
1. **Data Cleaning:**
   - Handle missing values, outliers, and multi-collinearity.
   
2. **Model Development:**
   - Use models like Random Forest, Logistic Regression, and XGBoost to predict fraud.

3. **Performance Evaluation:**
   - Use accuracy, precision, recall, F1-score, and ROC AUC to evaluate model performance.

4. **Insights and Recommendations:**
   - Key features for fraud prediction include transaction amount, type, and account balances.
   - Suggest preventive measures such as real-time monitoring, two-factor authentication, and transaction limits.

## Project Structure

```
│── Task.ipynb          # Jupyter Notebook containing the entire analysis and model
│── README.md           # Project overview and instructions
│── Fraud.csv           # Dataset used for the project
│── Data Dictionary.txt # Description of the dataset variables
│── Task Details.pdf    # Detailed instructions and context for the project
```

## Installation

To get started with this project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/Darth-Vader-The-Dark-Side-Coder/fraud-detection-project.git
cd fraud-detection-project
pip install -r requirements.txt
```

## Usage

Open the Jupyter notebook to explore the analysis and models:

```bash
jupyter notebook Task.ipynb
```

Run the cells step-by-step to see the data cleaning, feature selection, model building, and performance evaluation.

## Model Description

The project explores multiple models for fraud detection:
- **Random Forest**: Used for its interpretability and ability to handle imbalanced datasets.
- **XGBoost**: A powerful gradient-boosting technique that improves accuracy and minimizes errors.
- **Logistic Regression**: A simple, baseline model for binary classification.

## Results

The final model was evaluated using the following metrics:
- **Precision**: High precision to minimize false positives.
- **Recall**: Ensures that most fraudulent transactions are detected.
- **ROC AUC**: A measure of the model’s ability to distinguish between classes.

## Insights and Recommendations

Key factors that contribute to fraudulent transactions include:
- Large transaction amounts.
- Frequent transfers to new or suspicious accounts.
- Unusual changes in account balances.

### Suggested Preventive Measures:
- Real-time monitoring for large transactions.
- Implementation of two-factor authentication for high-value transfers.
- Setting thresholds for transaction limits to flag suspicious behavior.

## Contributing

Feel free to fork this repository and submit pull requests for improvements or new ideas. All contributions are welcome.


---

You can add or modify details to fit your project better.
