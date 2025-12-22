#  Credit Card Fraud Detection Using Machine Learning

##  Project Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques.
Due to the highly imbalanced nature of the dataset, special attention is given to evaluation metrics
such as Precision, Recall, and F1-score.

##  Objective
To build a reliable classification model that identifies fraudulent transactions while minimizing
false positives and false negatives.

##  Dataset
- Source: Kaggle – Credit Card Fraud Detection
- Transactions by European cardholders
- Highly imbalanced dataset (fraud vs non-fraud)

##  Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

##  Workflow
1. Load and explore the dataset
2. Preprocess and normalize transaction data
3. Handle class imbalance
4. Split data into training and testing sets
5. Train classification models
6. Evaluate models using Precision, Recall, and F1-score
7. Predict on New Transaction
##  Models Used
- Logistic Regression
  
- Note : Logistic Regression is used as a baseline model.
Random Forest is selected as the final model due to better Recall and F1-score.

- Random Forest Classifier

##  Evaluation Metrics
- Precision
- Recall
- F1-score

##  How to Run

1. Download the Credit_Card_Fraud_Detection.ipynb and Dataset(creditcard.csv)
   
2. Place the Credit_Card_Fraud_Detection.ipynb and creditcard.csv in the same folder.

3. Open jupyter notebook
     
5. pip install pandas numpy matplotlib seaborn scikit-learn
     
7. Open Credit_Card_Fraud_Detection.ipynb and run all cells.

## Learning

Handling imbalanced datasets

Fraud detection using ML

Model evaluation beyond accuracy

Practical classification pipeline

# Important Note:
“I used Logistic Regression as a baseline model for comparison.
However, due to the highly imbalanced nature of the fraud detection problem and the presence of complex non-linear patterns, Random Forest performed better in terms of Recall and F1-score. Therefore, Random Forest was selected as the final model.”
