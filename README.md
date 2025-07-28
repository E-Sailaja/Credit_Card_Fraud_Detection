# Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions using logistic regression. It uses the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), which is highly imbalanced.

## 📂 Dataset

- Features: 30 numerical features (PCA transformed)
- Target: 0 (genuine), 1 (fraud)
- Highly imbalanced: ~0.17% fraud cases

## 📊 Approach

- Exploratory data analysis
- Data balancing observation
- Logistic Regression Model
- Train-test split evaluation

## ⚙ Requirements

- numpy
- pandas
- scikit-learn

## 📈 Results

- High training and testing accuracy with basic logistic regression.
- Accuracy Score on Train: ~99.4%
- Accuracy Score on Test: ~99.4%

> Note: Accuracy may be misleading in imbalanced datasets.

## 🔚 Conclusion

Logistic Regression performs well but might not be optimal for detecting rare fraud cases. Future work can include techniques like SMOTE, Random Forest, or XGBoost.
