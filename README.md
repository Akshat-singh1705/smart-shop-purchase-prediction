# 🛒 Smart Shop E-Commerce Purchase Prediction using Decision Tree

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

# 📖 Project Overview

This project was developed as part of a **Supervised Machine Learning Assignment**. The objective is to predict whether a visitor to an e-commerce website is likely to make a purchase based on their browsing behaviour.

A complete machine learning workflow was followed, including data exploration, preprocessing, model development, pruning, hyperparameter tuning, and evaluation using a Decision Tree Classifier.

---

# 🎯 Problem Statement

The goal is to build a machine learning model capable of predicting whether a customer will complete a purchase based on their browsing session.

The dataset contains visitor behaviour collected from over **12,000 user sessions** and includes both numerical and categorical features describing interactions with the website.

Since the dataset is imbalanced, model performance is evaluated primarily using the **F1 Score**.

---

# 📊 Dataset Features

The dataset includes various customer behaviour attributes, including:

- Administrative Pages
- Informational Pages
- Product Related Pages
- Bounce Rate
- Exit Rate
- Page Value
- Visitor Type
- Month
- Weekend
- Traffic Type

### Target Variable

**Revenue**

- 1 → Purchase
- 0 → No Purchase

---

# 🚀 Project Workflow

### 1. Data Loading

- Imported dataset using Pandas
- Inspected dataset structure
- Checked data types and dimensions

---

### 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to better understand the dataset.

Included:

- Dataset overview
- Missing value analysis
- Statistical summary
- Class distribution
- Correlation heatmap
- Feature distribution
- Pairplot visualization

---

### 3. Data Preprocessing

- Encoded categorical variables
- Selected input and target variables
- Split dataset into training and testing sets

---

### 4. Model Building

Built a **Decision Tree Classifier** for predicting customer purchases.

---

### 5. Hyperparameter Tuning & Pruning

Improved model performance by experimenting with:

- Maximum Tree Depth
- Minimum Samples Split
- Cost Complexity Pruning (`ccp_alpha`)

The best-performing model was selected based on evaluation metrics.

---

### 6. Model Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

The F1 Score was used as the primary evaluation metric because of the imbalanced dataset.

---

# 📈 Results

✔ Successfully explored and preprocessed the dataset.

✔ Built a Decision Tree classification model.

✔ Applied pruning techniques to reduce overfitting.

✔ Improved model performance through hyperparameter tuning.

✔ Successfully achieved the required F1 Score benchmark.

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```text
Smart-Shop-Ecommerce-Purchase-Prediction/
│
├── dataset/
│   └── shop_smart_ecommerse.csv
│
├── smart_shop_ecommerce.ipynb
├── README.md
├── requirements.txt
├── .gitignore
```

# 🔮 Future Improvements

- Compare the Decision Tree model with ensemble algorithms such as Random Forest and Gradient Boosting.
- Apply cross-validation for more robust performance evaluation.
- Perform additional feature engineering to further improve prediction accuracy.

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Decision Tree Classification
- Hyperparameter tuning
- Cost Complexity Pruning
- Model evaluation using multiple performance metrics
- Building an end-to-end supervised machine learning pipeline

---

## 👨‍💻 Author

**Kishan Singh**

Second-Year B.Tech CSE (AI & ML)

KIIT University

Passionate about Artificial Intelligence, Machine Learning, Data Science, and Software Development.

---

⭐ If you found this project interesting, feel free to **Star** this repository!
