
# 🏢 Employee Attrition Prediction (LightGBM Model)

## 📌 Project Overview
The **Employee Attrition Prediction** project uses **Machine Learning** to identify employees who are most likely to leave a company.  
After experimenting with multiple algorithms, the **LightGBM Classifier** was found to be the best performing model in terms of **accuracy, speed, and handling of categorical features**.

By analyzing employee demographics, job satisfaction, salary, tenure, and other HR metrics, the model enables HR teams to make **data-driven retention strategies**.

---

## 🎯 Features
- 📊 **Data Preprocessing**: Cleans and prepares HR datasets for analysis.
- ⚡ **Best Model - LightGBM**: Fast, accurate, and efficient for large datasets.
- 📈 **Performance Evaluation**: Includes accuracy, precision, recall, and F1-score.
- 🔍 **Key Insights**: Highlights the most important factors influencing employee turnover.
- 🛠 **Easy-to-Run Notebooks**: For training, evaluation, and prediction.

---

## 📂 Dataset
The dataset contains the following types of features:
- **Demographics**: Age, Gender, Marital Status
- **Work Information**: Job Role, Department, Years at Company
- **Compensation**: Monthly Income, Overtime
- **Satisfaction Scores**: Job Satisfaction, Environment Satisfaction
- **Performance Metrics**: Performance Rating, Work-Life Balance

> **Dataset Reference**:  
> IBM HR Analytics Employee Attrition Dataset – [Kaggle Link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---



## 📊 Models Tested

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* **LightGBM (Selected as Final Model)** ✅

---

## 🚀 Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Amuthini-P/Employee_Attrition.git
   cd Employee_Attrition
   ```

2. **Install Required Libraries**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run Notebooks**

   * `attrition_preprocess.ipynb` – Preprocess data.
   * `Attrition_prediction_model.ipynb` – Train models, evaluate, and predict.

---

## 📈 Example Outputs

* **Best Model:** LightGBM Classifier
* **Metrics Example**:

  * Accuracy: 96%
  * Precision: 95%
  * Recall: 94%
* **Feature Importance Chart** showing top factors influencing attrition.

---

## 📌 Why LightGBM?

* **Speed** – Faster than traditional gradient boosting methods.
* **Accuracy** – Outperformed other tested models in predicting attrition.
* **Efficiency** – Handles large datasets and categorical variables well.
* **Interpretability** – Easy to visualize feature importance for HR insights.

---

## 📌 Future Improvements

* 🌐 Deploy model as an interactive HR dashboard
* 📡 Integrate with real-time HR data
* 🤖 Experiment with deep learning models

---


