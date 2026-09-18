# ✈️ Flight Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting flight ticket prices using machine learning regression techniques.

The project was developed as part of a Kaggle competition and includes exploratory data analysis, data preprocessing, feature engineering, multiple regression models, hyperparameter tuning, model comparison, and generation of the final Kaggle submission.

---

## 🎯 Objective

The objective of this project is to predict flight ticket prices based on available flight-related features.

**Problem Type:** Regression

**Target Variable:** `price`

---

## 🔎 Exploratory Data Analysis

The project includes the following exploratory analysis:

* Dataset structure and data types
* Descriptive statistics
* Missing-value analysis
* Duplicate-value analysis
* Outlier analysis
* Target variable distribution
* Categorical feature analysis
* Correlation analysis

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Missing-value treatment
* Duplicate-value checking
* Outlier analysis
* Removal of identifier columns where appropriate
* Categorical feature encoding
* Numerical feature scaling
* Separation of features and target variable

---

## 🤖 Machine Learning Models

The following regression models were evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Extra Trees Regressor
6. K-Nearest Neighbors Regressor
7. AdaBoost Regressor

---

## 📈 Model Performance

The validation results obtained during the project were:

| Model             |   R² Score |
| ----------------- | ---------: |
| Random Forest     | **0.9755** |
| Extra Trees       |     0.9719 |
| Decision Tree     |     0.9593 |
| Gradient Boosting |     0.9490 |
| AdaBoost          |     0.9272 |
| Linear Regression |     0.9213 |
| KNN               |     0.7916 |

Among the evaluated models, Random Forest achieved the highest validation R² score of **0.9755**.

---

## ⚙️ Hyperparameter Tuning

Hyperparameter optimization was performed on selected tree-based regression models using cross-validation.

The notebook includes hyperparameter search using:

* `GridSearchCV`
* `RandomizedSearchCV`

---

## 🏆 Kaggle Submission

Predictions were generated for the competition test dataset and prepared in the required Kaggle submission format.

The submission file is stored in the `submission/` directory.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Kaggle

---

## 📁 Project Structure

```text
flight-price-prediction-ml/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── flight_price_prediction.ipynb
│
├── data/
│   └── README.md
│
├── images/
│   └── model_comparison.png
│
└── submission/
    └── submission.csv
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project directory

```bash
cd flight-price-prediction-ml
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/flight_price_prediction.ipynb
```

### 5. Add the Kaggle dataset

Download the required dataset from the corresponding Kaggle competition and update the dataset path in the notebook according to your local environment.

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Exploratory Data Analysis
* Data cleaning and preprocessing
* Missing-value handling
* Outlier analysis
* Categorical feature encoding
* Feature scaling
* Regression modelling
* Model comparison
* Hyperparameter tuning
* Cross-validation
* Kaggle submission generation

---

## 📌 Future Improvements

Possible future improvements include:

* Additional feature engineering
* More extensive hyperparameter optimization
* Additional ensemble methods
* More detailed error analysis
* Cross-validation based model comparison
* Model deployment as a web application

---

## 👤 Author

**Palak Rawat**

GitHub: `Add your GitHub profile link here`

LinkedIn: `Add your LinkedIn profile link here`
