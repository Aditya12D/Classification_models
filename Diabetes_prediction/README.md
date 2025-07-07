# Diabetes Prediction using Machine Learning

This project predicts the likelihood of diabetes in patients using machine learning models trained on the **Pima Indians Diabetes dataset**. It demonstrates end-to-end implementation including data analysis, preprocessing, model building, evaluation, comparison and insights.

## 📁 Dataset

- **Source:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Description:** Contains diagnostic measurements for females aged 21 years and above of Pima Indian heritage.
- **Features:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (Target: 1 = diabetic, 0 = non-diabetic)

## 🛠️ Project Steps

1. **Data Loading & Exploration**
   - Checked for null values and data types
   - Performed statistical analysis and visualisations

2. **Data Preprocessing**
   - Feature scaling using StandardScaler

3. **Model Building**
   - Logistic Regression
   - KNN
   - Decision Tree Classifier

4. **Model Comparison**
   - Accuracy scores of all three models.
  
5. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report

## ✅ Results

| Model               | Accuracy |
|---------------------|----------|
| KNN                 | 73.3%    |
| Logistic Regression | 75.3%    |
| Decision Tree       | 76.6%    |

## 💡 Conclusion

Machine learning models like Decision Tree and Logistic Regression provided reasonable accuracy for diabetes prediction. Such models can assist healthcare professionals in early detection and intervention planning. Further improvements can be achieved by:
- Overfitting should be taken care of
- Hyperparameter tuning
- Using ensemble methods
- Testing on larger and diverse datasets
