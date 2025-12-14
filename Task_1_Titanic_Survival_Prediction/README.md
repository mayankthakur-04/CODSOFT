# Titanic Survival Prediction

## 📌 Project Overview
This project aims to build a machine learning model that predicts whether a passenger survived the Titanic disaster based on demographic and travel-related information.  
It is a classic beginner-level data science project that demonstrates the complete machine learning workflow.

---

## 📊 Dataset
The dataset contains information about Titanic passengers, including:
- Passenger Class (Pclass)
- Sex
- Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Fare
- Port of Embarkation (Embarked)
- Survival status (target variable)

**Target Variable:**  
- `Survived` (0 = Did Not Survive, 1 = Survived)

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

---

## 🔍 Project Workflow
1. **Data Loading**
   - Loaded the Titanic dataset using Pandas.

2. **Data Preprocessing**
   - Dropped irrelevant columns (Name, Ticket, Cabin).
   - Encoded categorical variables (`Sex`, `Embarked`).
   - Handled missing values using median imputation.

3. **Train-Test Split**
   - Split the data into training and testing sets.

4. **Model Training**
   - Trained a **Random Forest Classifier** to predict survival.

5. **Model Evaluation**
   - Evaluated model performance using accuracy score and classification report.

6. **Prediction**
   - Tested the trained model on new passenger data.

---

## 📈 Model Performance
- **Accuracy:** ~82%
- The model performs well in distinguishing between survivors and non-survivors.

---

## ▶️ How to Run the Project
1. Clone the repository or download the project folder.
2. Open the Jupyter Notebook
   ```bash
   jupyter notebook
3. Open titanic_analysis.ipynb.

4. Run all cells to see the results.

## 🎯Learning Outcomes

Understanding data preprocessing techniques

Handling categorical and missing data

Building and evaluating a machine learning model

Applying classification algorithms to real-world data
