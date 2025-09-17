# Titanic Survival Prediction using Logistic Regression

## 📌 Project Overview
This project predicts the survival of passengers on the Titanic using **Logistic Regression**.  
The dataset used is the famous [Titanic dataset from Kaggle](https://www.kaggle.com/c/titanic/data).

## 🗂️ Dataset
- **train.csv**: Training dataset with passenger details and survival status.  
- Features include:
  - `Pclass`: Passenger class (1st, 2nd, 3rd)
  - `Sex`: Gender
  - `Age`: Age of passenger
  - `SibSp`: Number of siblings/spouses aboard
  - `Parch`: Number of parents/children aboard
  - `Fare`: Ticket fare
  - `Embarked`: Port of Embarkation
  - `Survived`: Target variable (0 = No, 1 = Yes)

Download dataset: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

## ⚙️ Steps Performed
1. Data loading and exploration
2. Handling missing values
3. Encoding categorical variables
4. Splitting data into train/test sets
5. Training Logistic Regression model
6. Model evaluation (accuracy, confusion matrix, classification report)

## 📊 Results
- Logistic Regression achieved around **77-80% accuracy** on the test set.
- Gender, class, and age were key predictors of survival.

## 🚀 How to Run
1. Clone this repository or download the files.
2. Place the `train.csv` dataset in the same folder as the notebook.
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Run all cells to reproduce results.

## 📂 Files in Repository
- `Titanic_Logistic_Regression.ipynb` → Main project notebook
- `README.md` → Project documentation

## ✨ Future Improvements
- Try other models (Random Forest, SVM, XGBoost)
- Perform hyperparameter tuning
- Feature engineering for better accuracy

---
👩‍💻 Author: Palak Gupta
📅 Year: 2025
