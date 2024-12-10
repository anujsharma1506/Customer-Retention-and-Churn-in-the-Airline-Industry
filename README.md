# Customer-Retention-and-Churn-in-the-Airline-Industry
This project predicts customer churn in the airline industry using machine learning models like Random Forest and Gradient Boosting. By analyzing key factors such as travel type and loyalty points, it provides actionable insights to help airlines improve retention strategies and enhance customer satisfaction.
### **README: Customer Retention and Churn in the Airline Industry**

---

## **Project Overview**
This project aims to predict customer churn in the airline industry and identify the factors influencing customer retention. Using machine learning models such as Random Forest, Logistic Regression, and Gradient Boosting, the project provides actionable insights to enhance retention strategies and improve customer satisfaction.

---

## **Table of Contents**
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Key Insights](#key-insights)
- [Results](#results)
- [Future Scope](#future-scope)
- [Limitations](#limitations)
- [Installation and Usage](#installation-and-usage)
- [Contributors](#contributors)
- [License](#license)

---

## **Introduction**
Customer churn is a significant challenge in the airline industry. This project leverages machine learning to predict churn, analyze its drivers, and help airlines design better strategies to retain customers.

---

## **Dataset Description**
The dataset contains **10,282 rows** and **32 columns** with information on:
- **Demographics**: Age, Gender
- **Travel details**: Type of Travel, Loyalty Points, Class
- **Flight details**: Delays, Flight Distance, Cancellation
- **Customer feedback**: Likelihood to Recommend

---

## **Objectives**
- Predict customer churn using machine learning models.
- Identify key factors influencing churn.
- Provide actionable insights to improve customer retention strategies.

---

## **Methodology**
1. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions and relationships among features.
   - Examined patterns influencing churn.

2. **Data Preprocessing**:
   - Handled missing values and encoded categorical variables.
   - Scaled numerical features for better model performance.

3. **Modeling**:
   - Trained models: Random Forest, Logistic Regression, Gradient Boosting.
   - Evaluated using metrics like accuracy, precision, recall, and F1-score.

4. **Evaluation and Comparison**:
   - Plotted ROC-AUC curves for model comparison.
   - Analyzed feature importance to understand churn drivers.

---

## **Key Insights**
- **Travel type**, **loyalty points**, and **delays** are significant churn predictors.
- **Random Forest** achieved the best balance of metrics.
- **Gradient Boosting** excelled in recall, identifying churn cases more effectively.

---

## **Results**
- **Random Forest**:
  - Accuracy: 81.32%
  - F1-Score: 69.81%
  - AUC: 0.67
- **Gradient Boosting**:
  - Accuracy: 80.88%
  - F1-Score: 70%
  - AUC: 0.88
- **Logistic Regression**:
  - Accuracy: 78.05%
  - F1-Score: 64.97%
  - AUC: 0.80

Gradient Boosting proved to be the most reliable for identifying churn cases.

---

## **Future Scope**
- Integrate real-time churn prediction for dynamic monitoring.
- Enhance feature engineering with customer sentiment and lifetime value.
- Expand the model to other industries or broader airline datasets.

---

## **Limitations**
- Imbalanced classes may affect recall for churn cases.
- Performance depends on the availability and quality of dataset features.
- Ensemble models like Random Forest and Gradient Boosting lack interpretability compared to Logistic Regression.

---

## **Installation and Usage**
### Prerequisites:
- Python 3.8 or later
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/customer-retention-airline.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-retention-airline
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook or Python script:
   ```bash
   jupyter notebook customer_churn_analysis.ipynb
   ```

---

## **Contributors**
- **Anuj Sharma**: Data analysis, modeling, and project development

---

Feel free to use or extend this project for your own predictive analytics use cases. Contributions and feedback are welcome! 😊
