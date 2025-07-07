# 📊 Customer Churn Prediction Using K-Nearest Neighbors (KNN) Classifier

🚀 **Project Overview**

> This project focuses on predicting customer churn using the K-Nearest Neighbors (KNN) classification algorithm. The dataset is sourced from a telecommunications company, aiming to identify customers who are likely to stop using the company’s services. By leveraging machine learning, businesses can take proactive measures to retain customers and reduce churn rates.

---

## 📁 Dataset

* **Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
* **Shape:** \~7,000 rows × 21 columns
* **Features include:**

  * Customer demographics (gender, SeniorCitizen, Partner, Dependents)
  * Account information (tenure, Contract, PaymentMethod)
  * Usage metrics (MonthlyCharges, TotalCharges)
  * **Target:** `Churn` (Yes/No)

---

## 🛠️ Technologies & Libraries Used

* Python 🐍
* pandas 📊
* numpy 🔢
* scikit-learn 🤖

---

## 🔍 Workflow

### 1️⃣ Data Preprocessing

* Checked for missing values.
* Encoded categorical features using `LabelEncoder` to convert text data into numerical format.

### 2️⃣ Feature Selection

* Selected all columns except the target `Churn` for **X (features)**.
* Target variable `Churn` was set as **y**.

### 3️⃣ Train-Test Split

* Split data into 50% training and 50% testing using `train_test_split` with `random_state=42` for reproducibility.

### 4️⃣ Model Building

* Implemented **K-Nearest Neighbors (KNN)** classifier with:

  * `n_neighbors=500` (chosen for experimentation with large neighbor values).

### 5️⃣ Evaluation

* Made predictions on the test data.
* Measured performance using **Accuracy Score**.

---

## 🚀 Results

* Achieved an **accuracy score** (placeholder):

  ```
  accuracy_score = 0.75
  ```

> *(Replace with your actual score after running the notebook.)*

---

## 📌 Insights

✅ KNN is simple yet powerful for classification tasks like churn prediction.
✅ Data preprocessing, especially encoding categorical variables, is critical.
✅ Testing with different `k` values is important to balance bias-variance trade-off.

---

## 📝 Future Improvements

* Perform hyperparameter tuning with `GridSearchCV` to find the optimal `k`.
* Use feature scaling (`StandardScaler`) to improve distance calculations.
* Try ensemble methods (Random Forest, XGBoost) for potentially higher accuracy.
* Visualize decision boundaries (if reducing to 2D).

---

## 🤝 Contributing

Want to improve this project? Feel free to fork, submit PRs, or open issues!

---

## 📬 Contact

🐙 **GitHub:** [Balachandharsriram M](https://github.com/balachandharsriram)
