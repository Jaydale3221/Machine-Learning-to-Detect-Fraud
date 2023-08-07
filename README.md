# 🏥 Healthcare Provider Fraud Detection using Machine Learning

## Introduction

Healthcare provider fraud has become a significant challenge for the healthcare industry. Fraudulent activities by healthcare providers such as unnecessary medical procedures, false diagnoses, and billing for services not rendered result in the loss of billions of dollars annually. This project aims to tackle this issue by developing efficient and effective fraud detection systems using Machine Learning (ML) techniques.

## Motivation

The negative effects of healthcare fraud on programs like Medicare ultimately diminish the affordability and effectiveness of healthcare. Studies indicate that fraudulent claims account for 15% of all Medicare expenses. By utilizing machine learning algorithms, fraudulent activities can be identified, perpetrators can be removed, and healthcare costs can be reduced. Detecting and preventing healthcare fraud can lead to improved patient safety by preventing unnecessary medical treatments and interventions that may pose risks to patients.

## Data Preparation

- 📊 **Acquire the Data:** The dataset was obtained from the Kaggle data repository, containing information about healthcare provider claims and beneficiary details.

- 🧹 **Data Cleaning:** Duplicate records, incorrect or missing data, and irrelevant columns were removed to ensure data quality.

- ✅ **Feature Selection:** Relevant features that are likely to have a strong influence on fraudulent activity were identified.

- 🔄 **Data Transformation:** Missing values were handled by filling them with the median, and the data was normalized to a common scale.

- 🧮 **Categorical Encoding:** Categorical variables were encoded into numerical format to enable the use of machine learning algorithms.

- 🎯 **Train-Test Split:** The data was divided into training and testing sets for model training and evaluation.

- ⚖️ **Handling Imbalance:** To address the class imbalance issue, resampling techniques were applied to balance the number of fraudulent and non-fraudulent claims.

- 🔍 **Outlier Detection:** Outliers were identified and removed to ensure robust model performance.

- 📈 **Normalization and Scaling:** Data normalization and scaling were performed to ensure features contribute equally to the learning process.

- 🛠️ **Feature Engineering:** New features were generated through the combination or modification of existing features to enhance model performance.

## Model Building and Evaluation

Various machine learning algorithms were explored, including Random Forest, Logistic Regression, Decision Tree, and XG Boost, to build fraudulent activity detection models. The models were evaluated using precision, recall, F1 score, and confusion matrix to assess their performance in identifying potential fraudulent providers while minimizing false positives.

## Conclusion

Our model successfully predicts potential fraudulent healthcare providers based on claims filed by them, using features such as diagnosis codes, procedure codes, reimbursement amounts, and beneficiary information. Our model can be useful to insurance companies and governments in detecting and preventing healthcare fraud, reducing costs, and ensuring that legitimate customers receive timely claims.

## Visualizations and Report

For detailed visualizations and further insights, refer to the attached 📄 [PDF Report](Fraud.pptx.pdf).

Feel free to explore the 📓 Jupyter Notebook files in this repository for detailed code implementations and visualizations.

**Author:** Jay Dale
