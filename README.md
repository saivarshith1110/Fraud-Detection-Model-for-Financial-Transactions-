# Fraud Detection Model for Financial Transactions

## Overview
This project is a solution for an internship task focused on building a machine learning model to predict fraudulent financial transactions. The objective is to identify patterns in transaction data to build a proactive fraud detection system and provide actionable business insights.

The project workflow includes:
- Data cleaning and preprocessing.
- Building and evaluating a Logistic Regression model.
- Interpreting model results to identify key factors of fraud.
- Developing prevention strategies and methods for measuring their success.

For a full breakdown of the task requirements and data dictionary, you can view the original task details here: [Task Details PDF](https://drive.google.com/file/d/1PKvat79FMYhNuJZgWga4mEV9OC__WZxq/view)

## Key Findings
- **Data Cleaning:** The dataset had no missing values. Multicollinearity was handled by dropping highly correlated columns, and a log transformation was applied to the transaction amount to manage outliers.
- **Model:** A Logistic Regression model was developed, which showed high precision (0.84) but low recall (0.47) for fraudulent transactions, indicating that it missed over half of the actual fraud cases.
- **Key Factors:** The model identified transaction `amount` and `type` as the most significant predictors of fraudulent activity.
- **Prevention Strategies:** Based on the model, strategies were proposed, such as implementing rule-based flagging for high-risk transaction types and amounts, and developing a behavioral monitoring system.
- **Measuring Success:** The effectiveness of these strategies would be measured by a reduction in fraud rate and financial loss.

## How to Run the Project
1.  Clone this repository to your local machine.
2.  Install the necessary libraries (`pandas`, `numpy`, `scikit-learn`, `seaborn`) by running:
    ```bash
    pip install pandas numpy scikit-learn seaborn
    ```
3.  Ensure the dataset (`Task Details.pdf`) is in the same directory as the notebook. You can download the data source by clicking the link in the provided PDF.
4.  Open the `Fraud_Detection.ipynb` file in Jupyter Notebook to view and run the code.

## Contact
If you have any questions or feedback, feel free to reach out.

https://drive.google.com/file/d/1PKvat79FMYhNuJZgWga4mEV9OC__WZxq/view
