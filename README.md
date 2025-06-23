## **Overview:**

This project focuses on detecting warranty claim fraud using a structured machine learning pipeline. It aims to classify customer warranty claims as either genuine or fraudulent based on various behavioral, demographic, and product-related features.

## **Key Features:**

* Comprehensive preprocessing of product service claim data
* Feature analysis across geographical, categorical, and numerical domains
* Label encoding and transformation of categorical variables
* Correlation analysis to identify important features
* Balanced model training using undersampling techniques
* Evaluation using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC

## **Data Sources:**

* Customer and product data with service claim history (`train.csv`)
* Features include region, state, city, product type, service center, product age, and more
* Target variable: `Fraud` (binary classification)

## **Modeling Approaches:**

1. Exploratory Data Analysis (EDA) for understanding patterns in fraudulent behavior
2. Feature engineering including encoding of categorical values and outlier handling
3. Class imbalance handling using RandomUnderSampler from `imblearn`
4. Classification models including:

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * Gradient Boosting Classifier
5. Hyperparameter tuning using GridSearchCV
6. Performance metrics visualized with confusion matrix and ROC curves

## **Tools and Libraries:**

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Scikit-learn (classification models, metrics, preprocessing)
* Imbalanced-learn (RandomUnderSampler)
* Jupyter Notebook for interactive development

## **Evaluation Results:**

* Models compared based on accuracy and ability to correctly detect fraud
* Random Forest and Gradient Boosting yielded the best F1 and ROC-AUC scores
* Feature importance revealed key indicators like product age, service center ID, and claim value

## **Usage:**

This project can be extended to:

* Real-time fraud detection systems in warranty or insurance sectors
* Risk scoring of claims for manual investigation
* Integration with CRM or ERP systems for automation

