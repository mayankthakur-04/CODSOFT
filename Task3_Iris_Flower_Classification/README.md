#  Iris Flower Classification using Machine Learning

##  Project Overview
This project demonstrates a **machine learning classification task** using the famous **Iris Flower Dataset**.  
The goal is to build a model that can accurately classify iris flowers into one of the three species based on their physical measurements.

### Species Classified
- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

##  Dataset
- **Source:** Kaggle – Iris Flower Dataset  
- **Link:** https://www.kaggle.com/datasets/arshid/iris-flower-dataset  
- **Total Samples:** 150  
- **Features:**
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- **Target:**
  - Species

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

##  Machine Learning Model
- **Algorithm:** Logistic Regression  
- **Type:** Supervised Classification  
- **Train-Test Split:** 80% Training, 20% Testing  

---

##  Model Performance
The trained model achieved excellent performance on the test dataset:

- **Accuracy:** 100%
- **Precision:** 1.00
- **Recall:** 1.00
- **F1-Score:** 1.00

> Note: High accuracy is expected because the Iris dataset is clean and linearly separable.

---

##  Project Structure

Iris-Flower-Classification/

│

├── Iris_Flower_Classification.ipynb # Jupyter Notebook

├── Iris.csv # Dataset

├── README.md # Project documentation

##  How to Run the Project

1. Download or clone the repository
   
2. Install required libraries:
   
pip install pandas numpy scikit-learn

4. Place `IRIS.csv` in the same directory as the notebook
    
6. Open Jupyter Notebook
    
8. Run all cells sequentially  

---

##  Sample Prediction

The model can predict the species of a new Iris flower:

```python
sample = pd.DataFrame([[5.1, 3.5, 1.4, 0.2]], columns=X.columns)
model.predict(sample)

Output:

Iris-setosa
```
## Learnings:

Understand supervised classification

Hands-on experience with Pandas & Scikit-learn

Model training, testing, and evaluation

Handling real-world warnings and best practices
