# Classification Model: Heart Disease Prediction using KNN & Naive Bayes 

This project is a **Machine Learning** model that predicts whether a person is at risk of heart disease based on their lifestyle factors (e.g., smoking, blood pressure) and demographic information. 
The model uses **K-Nearest Neighbors (KNN)** and **Naive Bayes** algorithms to classify individuals as either **heart disease patients** or **non-patients**.

---

### 🛠️ **Technologies & Libraries**:
- **Programming Language**: Python
- **Libraries**: 
  - **scikit-learn** for machine learning algorithms (KNN, Naive Bayes)
  - **Pandas** for data manipulation
  - **NumPy** for numerical operations
  - **Matplotlib** and **Seaborn** for data visualization

---

### ✨ **Dataset Description**:
The dataset consists of various features related to individuals’ health, including:
- Age
- Gender
- Blood Pressure Levels
- Smoking Status
- Cholesterol Levels
- Physical Activity

These features are used to predict the likelihood of a person having heart disease.

---
### **preprocessing**:
Data Cleaning:

 **missing values**: Any rows with missing or incomplete information were either filled using imputation techniques or removed to avoid skewing the model’s predictions.

**Feature Encoding**:Since some features (such as Gender) were categorical, they were converted into numerical representations using techniques like One-Hot Encoding or Label Encoding. This allows machine learning models to interpret the data efficiently.

**Scaling & Normalization**:Some features like Blood Pressure and Cholesterol had different scales and ranges. To ensure the model treated all features equally, Min-Max Scaling was applied to normalize the data into a uniform range (0-1), especially for models like KNN which are sensitive to feature scale.

**Splitting the Data**:The dataset was divided into two parts: a training set (80%) used to train the models, and a testing set (20%) used to evaluate the performance of the trained models.

**Handling Imbalanced Data**:Since heart disease cases were imbalanced (fewer cases of heart disease), techniques like SMOTE (Synthetic Minority Over-sampling Technique) or undersampling were applied to balance the classes and improve model generalization.

These preprocessing steps helped ensure that the models could learn from the data effectively, leading to better accuracy and prediction reliabilit

### 🔍 **Main Features & Algorithms**:
- **K-Nearest Neighbors (KNN)**: A simple and effective algorithm used for classification by finding the closest neighbors of a data point.
- **Naive Bayes**: A probabilistic classifier based on Bayes' Theorem, which is particularly useful when features are independent.
- **Data Preprocessing**: Includes data cleaning, feature selection, and splitting data into training and testing sets.
- **Model Evaluation**: The performance of both algorithms was evaluated using metrics like accuracy, precision, recall, and F1-score.

---

### 🚀 **How It Works**:
1. **Data Loading & Preprocessing**:
   - Load the dataset and clean any missing or incorrect values.
   - Normalize and scale features for better model performance.
2. **Model Training**:
   - Train the **KNN** and **Naive Bayes** models on the dataset.
3. **Model Evaluation**:
   - Evaluate both models on the testing dataset and compare their performance.
4. **Prediction**:
   - Use the trained models to predict whether an individual is likely to have heart disease based on input features.

---
