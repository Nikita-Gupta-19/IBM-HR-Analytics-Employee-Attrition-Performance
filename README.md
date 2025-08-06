# 🧑‍💼 IBM HR Analytics: Employee Attrition & Performance Analysis

A complete Data Science project focusing on HR attrition patterns using IBM's open HR dataset. The project applies EDA, machine learning, and model interpretability techniques to uncover insights about employee turnover and performance in a corporate setting.

---

## 📌 Objective

To identify the key factors contributing to employee attrition and to build a predictive model that classifies whether an employee is likely to leave the company, based on their profile and performance metrics.

---

## 🧰 Tools & Technologies Used

- **Python** – Data Cleaning, Preprocessing, EDA, and Modeling
- **Google Colab** – Development Environment
- **Pandas, NumPy** – Data Manipulation
- **Matplotlib, Seaborn** – Data Visualization
- **Scikit-learn** – Model Building and Evaluation
- **SHAP** – Model Explainability and Interpretability
- **CSV** – Dataset Handling and Exporting Results

---

## 📁 Dataset

- Source: IBM HR Analytics Employee Attrition & Performance dataset
- Total Rows: 1470  
- Features include:
  - Demographic: `Age`, `Gender`, `MaritalStatus`
  - Job Role & Satisfaction: `JobRole`, `JobSatisfaction`, `EnvironmentSatisfaction`
  - Compensation: `MonthlyIncome`, `PercentSalaryHike`, `StockOptionLevel`
  - Performance: `PerformanceRating`, `YearsAtCompany`, `WorkLifeBalance`
  - Target Variable: `Attrition` (Yes/No)

---

## 📊 Visualizations Created

1. **Countplot** – Attrition count
2. **Gender vs Attrition** – Grouped bar plot
3. **Job Role vs Attrition** – Horizontal bar chart
4. **Monthly Income Distribution** – KDE histogram by Attrition
5. **Correlation Heatmap** – With feature-level insights
6. **SHAP Summary Plot** – Feature impact on attrition prediction
7. **SHAP Waterfall Plot** – Individual employee explanation
8. **SHAP Dependence Plot** – Top influencing features
9. **SHAP Interaction Plot** – Top feature interaction insights

---

## 🧠 Key Insights

- Employees with **low income**, **low satisfaction**, or **short tenure** are more likely to leave.
- **Job role**, **age**, and **work-life balance** play significant roles in predicting attrition.
- The predictive model is interpretable, thanks to SHAP, and highlights top drivers of attrition in each case.

---

## 📈 Model Building

- Model Used: **Random Forest Classifier**
- Metrics Evaluated: **Accuracy**, **Precision**, **Recall**, **F1-Score**, **ROC-AUC**
- Target Class: `Attrition = Yes`
- Model Interpretation: SHAP used to explain global & local feature importance

---

## 🧾 Output & Export

- Cleaned dataset exported as: `HR_analytics_data_final.csv`
- SHAP visuals and EDA charts generated and saved during execution
- Can be extended to create an HR dashboard for real-time attrition monitoring

---

## 🔮 Future Scope

- Deploy this model as an **HR prediction app** using Streamlit or Flask
- Integrate external datasets like employee feedback or exit interviews
- Apply **NLP** on open-ended survey responses for deeper sentiment analysis
- Use **Time-Series** analysis for attrition over tenure or by monthly trends

---

## 🙌 Acknowledgements

- **Dataset**: IBM HR Analytics (available publicly via Kaggle/IBM)
- **Tools**: Google Colab, SHAP, scikit-learn
- **Inspired by**: Real-world HR analytics use cases in corporate strategy

---

## 📬 Contact

**Nikita Gupta**  
📧 [Email](mailto:nikitagpt06@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/nikita-gupta-790a54284/)  
💻 [GitHub](https://github.com/Nikita-Gupta-19)
