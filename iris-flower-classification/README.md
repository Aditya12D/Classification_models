# Iris Flower Classification using KNN
This project classifies Iris flowers into Setosa, Versicolor, and Virginica species using the K-Nearest Neighbors (KNN) algorithm. It includes detailed exploratory data analysis (EDA) and model evaluation.
## 📊 Dataset
- Source: scikit-learn's built-in Iris dataset
- Shape: 150 samples, 4 features + target
- Features:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- Target: Iris species (Setosa, Versicolor, Virginica)

## ❓ Problem Statement
Classify the species of Iris flower based on given sepal and petal measurements.

## 🛠️ Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 🔍 EDA Summary
- No missing values in the dataset.
- Pairplots show Setosa is linearly separable from other classes.
- Petal length and width are strong distinguishing features.
- Correlation heatmap shows high correlation between petal length and width.

## 🤖 Model
- **Algorithm:** K-Nearest Neighbors (KNN)
- **Reason:** Simple, effective for small datasets and works well with distance-based classification.
- **Scaler:** StandardScaler used to standardise feature ranges.

## 📝 Evaluation
- **Accuracy:** 95.5% on test set
- **Confusion Matrix:** Minor misclassifications between Versicolor and Virginica.
- **Classification Report:** Precision, recall, and f1-score included in notebook.

## ✅ Conclusion
KNN performed well on the Iris dataset, achieving high accuracy with clear class separability. This reinforces the importance of distance-based models for well-structured datasets like Iris.

