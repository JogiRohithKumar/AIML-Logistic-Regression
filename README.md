# AIML-Logistic-Regression

# 📄 Breast Cancer Analysis using Logistic Regression
This project uses Logistic Regression to classify tumors as malignant or benign using the Breast Cancer Wisconsin dataset. It includes data preprocessing, model training, and evaluation using metrics such as the confusion matrix, classification report, and ROC-AUC curve. The project also explores the sigmoid function and decision threshold tuning to better understand classification behavior.

## 📁 Dataset
- **Source:** Breast Cancer Wisconsin Dataset
- **Target Column:** `diagnosis` (M = Malignant, B = Benign)

## 🔧 Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## ✅ Steps Followed
1. Loaded and explored the dataset.
2. Dropped unnecessary columns (`id`, `Unnamed: 32`).
3. Encoded target labels (`diagnosis`: M → 1, B → 0).
4. Standardized the features.
5. Split dataset into train and test sets.
6. Built Logistic Regression model.
7. Evaluated model using:
   - Confusion Matrix
   - Classification Report
   - ROC Curve and AUC Score

## 📈 Output Highlights
- Accuracy, Precision, Recall, F1-score
- ROC-AUC Score
- Confusion Matrix Heatmap
- ROC Curve
