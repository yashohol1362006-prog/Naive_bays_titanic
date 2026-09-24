# 🚢 Titanic Survival Prediction using Naive Bayes

This project uses the **Titanic dataset** to predict whether a passenger survived using the **Naive Bayes classification algorithm**.

## 📌 Project Overview

The notebook follows a complete Machine Learning workflow:

- Data Loading
- Exploratory Data Analysis (EDA)
- Feature Selection
- Train-Test Split
- Missing Value Handling
- Categorical Feature Encoding
- Naive Bayes Model Training
- Prediction
- Model Evaluation

## 🤖 Machine Learning Algorithm

### Naive Bayes

Naive Bayes is a probabilistic classification algorithm based on **Bayes' Theorem**. It assumes that the features are conditionally independent given the target class.

The model predicts:

- `0` → Did not survive
- `1` → Survived

## 📊 Dataset

The project uses the **Titanic dataset** available through the Seaborn library.

python
import seaborn as sns

df = sns.load_dataset("titanic")
Selected Features
sex
age
fare
class
embark_town
Target Variable
survived
🔄 Machine Learning Workflow
Titanic Dataset
      ↓
Exploratory Data Analysis
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Missing Value Handling
      ↓
Categorical Feature Encoding
      ↓
Naive Bayes Model Training
      ↓
Prediction
      ↓
Model Evaluation
🧹 Data Preprocessing

The dataset was checked for missing values and categorical features.

Missing Values
Missing age values were handled using the median of the training data.
Missing embark_town values were handled using the mode of the training data.
Categorical Encoding

Categorical features such as:

sex
class
embark_town

were converted into numerical representations before training the model.

📈 Model Evaluation

The trained model is evaluated using:

Accuracy
Confusion Matrix
Precision
Recall
F1-Score
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
🎯 Learning Objectives

This project was created to practice:

Exploratory Data Analysis
Data preprocessing
Handling missing values
Categorical encoding
Train-test splitting
Classification
Naive Bayes
Model evaluation
End-to-end Machine Learning workflow
📁 Project Structure
titanic-naive-bayes/
│
├── Titanic_Naive_Bayes.ipynb
└── README.md
🚀 Future Improvements

Possible improvements to this project include:

Feature engineering
Cross-validation
Hyperparameter experimentation
Comparing Naive Bayes with Logistic Regression, KNN, Decision Tree, and Random Forest
Model deployment
👨‍💻 Author

Yash Ohol
