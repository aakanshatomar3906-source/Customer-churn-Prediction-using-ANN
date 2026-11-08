# 📊 Customer Churn Prediction Using Artificial Neural Network (ANN)

### Predicting Customer Churn with Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Neural%20Network-red?logo=keras)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikitlearn)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Overview

Customer churn is one of the major challenges faced by businesses, particularly in the telecommunications industry.

This project uses an **Artificial Neural Network (ANN)** to predict whether a customer is likely to leave a company based on historical customer information and service-related attributes.

The model learns patterns from customer data and classifies customers into two categories:

- **0 – No Churn:** Customer continues using the service.
- **1 – Churn:** Customer is likely to leave the service.

The primary objective is to demonstrate how deep learning can support customer retention strategies through predictive analytics.

## 🎯 Project Objectives

- Understand and preprocess customer churn data.
- Perform exploratory data analysis (EDA).
- Apply feature encoding and feature scaling.
- Build an Artificial Neural Network using TensorFlow and Keras.
- Train and evaluate the neural network.
- Analyze model performance using classification metrics.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical computations |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Seaborn | Exploratory data analysis |
| Scikit-learn | Preprocessing and evaluation |
| TensorFlow | Deep learning framework |
| Keras | ANN architecture |



## ⚙️ Project Workflow

### 1. Data Collection
Loaded the customer churn dataset containing customer demographics, account information, subscribed services, and churn labels.

### 2. Exploratory Data Analysis (EDA)
- Analyzed the distribution of churn and non-churn customers.
- Examined relationships between customer attributes and churn.
- Identified patterns and trends in customer behavior.

### 3. Data Preprocessing
- Handled missing or inconsistent values.
- Encoded categorical variables.
- Separated independent and dependent variables.
- Split the dataset into training and testing sets.
- Applied feature scaling.

### 4. ANN Model Architecture

Designed an Artificial Neural Network consisting of:

- **Input Layer:** Accepts preprocessed customer features.
- **Hidden Layers:** Learn complex relationships and patterns.
- **ReLU Activation:** Introduces non-linearity.
- **Output Layer:** Uses Sigmoid activation for binary classification.

### 5. Model Training

Trained the ANN using:
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy

*These settings should match your actual implementation.*

### 6. Model Evaluation

Evaluated the model using:

- Accuracy
- Confusion Matrix

## 🧠 ANN Architecture

```text
Customer Dataset
       |
       v
 Data Preprocessing
       |
       v
 Feature Scaling
       |
       v
   Input Layer
       |
       v
  Hidden Layer 1
    (ReLU)
       |
       v
  Hidden Layer 2
    (ReLU)
       |
       v
  Output Layer
   (Sigmoid)
       |
       v
 Churn Prediction
       |
       v
  0 = No Churn
  1 = Churn
```

## 📈 Results

The model's performance can be evaluated using the following metrics:

| Evaluation Metric | Result |
|---|---|
| Accuracy | Add your result |



## 🚀 Installation and Usage

**1. Clone the repository**

```bash
git clone https://github.com/aakanshatomar3906-source/Customer-Churn-Prediction-ANN.git
```

**2. Navigate to the project directory**

```bash
cd Customer-Churn-Prediction-ANN
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open the notebook and execute the cells to train and evaluate the model.

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Understanding Artificial Neural Networks.
- Working with TensorFlow and Keras.
- Building deep learning models for binary classification.
- Data preprocessing and feature engineering.
- Understanding activation functions and loss functions.
- Evaluating classification models.

## 🔮 Future Improvements

- Hyperparameter tuning for improved performance.
- Experimenting with different ANN architectures.
- Handling class imbalance using appropriate techniques.
- Applying SMOTE where appropriate.
- Building an interactive prediction interface using Streamlit.
- Deploying the trained model using Flask or FastAPI.

## 👩‍💻 Author

**Aakansha Tomar**

B.Tech | Artificial Intelligence & Data Science

Interested in Machine Learning, Deep Learning, and AI Engineering.

- 💼 [LinkedIn](https://www.linkedin.com/in/aakanshatomar/)
- 💻 [GitHub](https://github.com/aakanshatomar3906-source)

---

⭐ If you find this project useful, consider giving this repository a star!

**Built with Python, TensorFlow & Deep Learning.**
