# 🧠 Customer Churn Prediction using Artificial Neural Network (ANN)

This project predicts whether a bank customer is likely to leave the bank (churn) using an Artificial Neural Network (ANN) built with TensorFlow/Keras. The application is deployed using Streamlit, allowing users to enter customer information and get real-time churn predictions.

---

## 📌 Project Overview

Customer churn prediction is an important business problem in the banking industry. This project uses customer information such as geography, age, balance, tenure, salary, and credit score to predict whether a customer is likely to leave the bank.

---

## 🚀 Features

- Customer churn prediction using ANN
- Interactive Streamlit web application
- Data preprocessing using Scikit-learn
- One-Hot Encoding for Geography
- Label Encoding for Gender
- Feature Scaling using StandardScaler
- Pre-trained ANN model for instant predictions

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Streamlit
- Pandas
- NumPy
- Pickle

---

## 📂 Project Structure

```
ANN_CLASSIFICATION/
│
├── app.py                      # Streamlit application
├── Churn_Modelling.csv         # Dataset
├── experiments.ipynb           # Model training notebook
├── prediction.ipynb            # Prediction notebook
├── model.h5                    # Trained ANN model
├── scaler.pkl                  # StandardScaler
├── label_encoder_gender.pkl    # Label Encoder
├── one_hot_encoder_geo.pkl     # One Hot Encoder
├── requirements.txt            # Required libraries
├── logs/                       # TensorBoard logs
└── README.md
```

---

## 📊 Dataset Features

The model uses the following customer information:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

### Target

- Exited
  - 0 → Customer stays
  - 1 → Customer leaves

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/customer_churn_prediction.git
```

### Navigate into the project

```bash
cd customer_churn_prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🧠 Model Architecture

- Input Layer
- Hidden Dense Layer (ReLU)
- Hidden Dense Layer (ReLU)
- Output Layer (Sigmoid)

Loss Function:

```
Binary Crossentropy
```

Optimizer:

```
Adam
```

Evaluation Metric:

```
Accuracy
```

---

## 📈 Workflow

1. Load customer information
2. Encode categorical variables
3. Scale numerical features
4. Load trained ANN model
5. Predict churn probability
6. Display prediction on Streamlit

---

## 📷 Application Preview

Add screenshots of your Streamlit application here.

---

## 📚 Future Improvements

- Deploy on Streamlit Cloud
- Hyperparameter tuning
- Improve model accuracy
- Add SHAP explainability
- Docker support
- CI/CD pipeline

---

## 👨‍💻 Author

**Anurag Sanjeev Kumar**

- GitHub: https://github.com/anuragsanjeevkumar-cmyk

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
