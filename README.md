# Predicting-Credit-Card-Approvals

## Description
This project from [DataCamp](https://app.datacamp.com/learn/projects/1908) taught me to build an automatic credit card approval predictor using machine learning techniques, just like real banks do.

![Credit card being held in hand](credit_card.jpg)

Commercial banks receive _a lot_ of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!).


The data used is a small subset of the Credit Card Approval dataset from the UCI Machine Learning Repository showing the credit card applications a bank receives. 

## Installation Instructions
1. Clone the repository:
    git clone https://github.com/A-n-i-e/Predicting-Credit-Card-Approvals.git

2. Navigate to the project directory:
    cd Predicting-Credit-Card-Approvals

3. Install the required dependencies:
    pip install -r requirements.txt

4. Launch the Jupyter notebook:
    jupyter notebook notebooks/transaction_analysis.ipynb


## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Results
Model trained with Logistic Regression

Accuracy: 84.78296478296479% and Parameters used: {'C': 0.01, 'penalty': 'l2'}