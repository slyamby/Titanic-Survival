# 🚢 Titanic Survival Prediction - Machine Learning Project

This project applies machine learning to predict passenger survival in the Titanic disaster, based on features like age, sex, ticket class, and more.

## 🎯 Objective

Predict whether a passenger survived based on structured data from the Titanic dataset. This is a classic binary classification problem and a great benchmark for understanding real-world ML pipelines.

## 📦 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Features include: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, and `Embarked`.

## 🔧 Tools Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for EDA)

## ⚙️ ML Workflow

1. **Exploratory Data Analysis (EDA)**: Visualized patterns and missing values
2. **Data Cleaning**:
   - Filled missing values (e.g., median age)
   - Converted categorical to numeric (e.g., `Sex`, `Embarked`)
3. **Feature Engineering**:
   - Selected most important features based on correlation
4. **Model Training**:
   - Used Logistic Regression and Random Forest
   - Evaluated using accuracy, confusion matrix, and cross-validation
5. **Prediction**:
   - Generated survival predictions on test data
   - Saved to CSV for submission or further analysis

## 📁 Project Structure

titanic-survival-prediction/
├── titanic_model.ipynb # Jupyter notebook with full workflow
├── titanic.csv # Original dataset (or link to Kaggle)
├── predictions.csv # Output file with predicted survival
└── README.md
