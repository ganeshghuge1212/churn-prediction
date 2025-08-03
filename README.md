# Customer Churn Prediction using Machine Learning

This project focuses on predicting customer churn in the telecom sector using supervised machine learning techniques. It includes complete steps from data preprocessing, visualization, to model building.

---

## 📊 Dataset

- **Source**: [Kaggle / Telco Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Rows**: 7043  
- **Features**: Customer details like tenure, services used, billing, and churn label

---

## 🔧 Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook

---

## 📈 Project Workflow

1. **Data Cleaning**
   - Handled missing values in `TotalCharges`
   - Converted data types and dropped irrelevant columns like `customerID`

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution
   - Correlation heatmap, countplots, boxplots for insights

3. **Data Preprocessing**
   - Label Encoding for categorical features
   - Feature scaling if required

4. **Model Building**
   - Used `RandomForestClassifier`
   - Train-test split with 80/20 ratio
   - Evaluated using confusion matrix and accuracy score

5. **Model Accuracy**
   - Achieved ~80% accuracy

---

## 📌 Output Sample

