# 🩺 Disease Prediction from Medical Data

## 📌 Project Overview

This project is developed as part of the **CodeAlpha Machine Learning Internship**. The objective is to predict whether a patient is likely to have diabetes based on medical information using Machine Learning classification algorithms.

The model is trained on the **Pima Indians Diabetes Dataset** and uses patient health attributes such as glucose level, blood pressure, BMI, age, and insulin level to make predictions.

---

## 🎯 Objective

* Predict the presence of diabetes using patient medical data.
* Perform data preprocessing and exploratory data analysis (EDA).
* Train and evaluate a Machine Learning classification model.
* Understand the complete Machine Learning workflow from data preparation to prediction.

---

## 📂 Dataset

**Dataset:** Pima Indians Diabetes Dataset

**Source:** UCI Machine Learning Repository / Kaggle

### Features

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Target Variable

* **Outcome**

  * 0 → No Diabetes
  * 1 → Diabetes

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 📊 Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Data preprocessing
4. Exploratory Data Analysis (EDA)
5. Split the dataset into training and testing sets
6. Train the Logistic Regression model
7. Make predictions
8. Evaluate model performance
9. Save the trained model

---

## 🤖 Machine Learning Algorithm

* Logistic Regression

---

## 📈 Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📁 Project Structure

```
CodeAlpha_DiseasePrediction/
│
├── DiseasePrediction.ipynb
├── diabetes.csv
├── disease_prediction.pkl
├── requirements.txt
├── README.md
└── images/
```

---

## ▶️ How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/CodeAlpha_DiseasePrediction.git
```

### Navigate to the Project Folder

```bash
cd CodeAlpha_DiseasePrediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open `DiseasePrediction.ipynb` in Jupyter Notebook or Google Colab and execute all cells.

---

## 📷 Sample Output

The model predicts whether a patient is diabetic based on the provided medical information.

Example:

```
Input:
Age = 45
Glucose = 150
BMI = 31.5

Prediction:
Diabetic
```

---

## 🚀 Future Improvements

* Improve prediction accuracy using Random Forest or XGBoost.
* Hyperparameter tuning using GridSearchCV.
* Build a web application using Streamlit or Flask.
* Deploy the model on the cloud.
* Support predictions for multiple diseases.

---

## 📚 Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Exploratory Data Analysis (EDA)
* Machine Learning model training
* Model evaluation
* Classification algorithms
* Python libraries for Machine Learning

---

## 👩‍💻 Author

**NAVEEN KUMAR V**

B.E. Computer Science and Engineering

Machine Learning Intern – CodeAlpha

---

## ⭐ Acknowledgements

* CodeAlpha Machine Learning Internship
* UCI Machine Learning Repository
* Scikit-learn Documentation
* Kaggle Community
