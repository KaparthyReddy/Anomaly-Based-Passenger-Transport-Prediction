# Anomaly-Based Passenger Transport Prediction 🚀

This repository contains a machine learning solution for predicting whether spaceship passengers were transported by a mysterious spatial anomaly during an interstellar journey. The problem is derived from the [Spaceship Titanic Kaggle competition](https://www.kaggle.com/competitions/spaceship-titanic/overview), which simulates partial data recovery from a lost vessel.

Using robust preprocessing, feature engineering, and classification modeling techniques, this project attempts to uncover the patterns behind who was affected by the anomaly.

---

## 🧠 Problem Statement

Following a space anomaly incident, rescue crews are tasked with identifying which passengers were mysteriously transported. Due to data corruption, only partial logs remain. Your objective is to build a model that predicts whether a passenger was **transported** based on fragmented information.

---

## 📊 Dataset

The dataset includes the following types of data:
- Group and passenger IDs
- Home planet origin
- Cryo-sleep status
- Age and VIP status
- Spending on various services (RoomService, FoodCourt, etc.)
- Cabin information
- Destination
- Transported status (target)

📥 Source: [Spaceship Titanic - Kaggle](https://www.kaggle.com/competitions/spaceship-titanic)

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 🧪 Features & Workflow

1. **Data Preprocessing**
   - Null value imputation with intelligent heuristics
   - Feature extraction from cabin, name, and group fields
   - Encoding categorical features using Label Encoding and One-Hot Encoding

2. **Exploratory Data Analysis**
   - Visualizations of age distribution, correlations, spending behavior, etc.
   - Insightful plots to uncover relationships with the target variable

3. **Modeling**
   - Tried multiple models: Logistic Regression, Random Forest, XGBoost
   - Final model: XGBoostClassifier
   - Hyperparameter tuning with GridSearchCV

4. **Evaluation**
   - Accuracy, F1-score, confusion matrix
   - Kaggle-style submission file creation

---

## 🚀 Getting Started

### 1. Clone the repository


git clone https://github.com/yourusername/Passenger-Transport-Prediction-Anomaly.git
cd Passenger-Transport-Prediction-Anomaly

### 2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
Alternatively, run the notebook directly on Kaggle or Google Colab.

### 3. Launch Jupyter Notebook
bash
Copy
Edit
jupyter notebook

🏁 Results
The final XGBoost model achieved an accuracy of XX.XX% on the test set (Kaggle public score). Further gains are possible through ensemble modeling, deep learning, and advanced feature synthesis.

📄 License
This project is licensed under the MIT License.
