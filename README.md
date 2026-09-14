# Customer Churn Prediction using Logistic Regression

## Objective

The objective of this project is to develop a Logistic Regression model to predict whether a customer is likely to churn based on demographic and service-related attributes. The project demonstrates the complete machine learning workflow, including data preprocessing, feature encoding, model training, prediction, and performance evaluation.

---

## Dataset Link

**Telco Customer Churn Dataset (Kaggle):**

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

> Note: The dataset is not included in this repository. It is downloaded directly from Kaggle using the Kaggle API in Google Colab.

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle API

---

## Methodology

1. Downloaded the Telco Customer Churn dataset using the Kaggle API.
2. Loaded the dataset into Google Colab.
3. Performed data preprocessing by handling missing values and encoding categorical variables.
4. Selected relevant features and defined **Churn** as the target variable.
5. Split the dataset into training and testing sets using an 80:20 ratio.
6. Built a Logistic Regression model using Scikit-learn.
7. Predicted customer churn on the test dataset.
8. Evaluated the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## Results

The Logistic Regression model produced the following performance metrics:

| Metric | Value |
|---------|-------|
| Accuracy | **79.21%** |
| Precision | **62.54%** |
| Recall | **54.01%** |
| F1-Score | **57.96%** |

The confusion matrix showed that the model correctly classified most non-churn customers while identifying a significant number of churn cases. However, some churn customers were still misclassified, indicating room for further improvement.

---

## Conclusion

The Logistic Regression model achieved an overall accuracy of **79.21%**, making it effective for predicting customer churn. The results indicate that customer attributes such as contract type, tenure, monthly charges, and payment method play an important role in determining churn. Although the model performs well overall, it has a comparatively lower recall, meaning some customers who actually churn are not identified correctly. Logistic Regression serves as a strong baseline model for binary classification, but more advanced machine learning algorithms and additional feature engineering could further improve prediction accuracy.
