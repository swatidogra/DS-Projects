# Credit Card Fraud Detection Model 

## Overview
The project aims to address the critical issue of credit card fraud, which results in significant financial 
losses for banks and customers. The research will explore various machine learning models to identify 
patterns and anomalies in transaction data to flag potential fraudulent activities. The goal is to develop a 
reliable and efficient fraud detection system to enhance the security of credit card transactions.


## Project Details
- **Project Title**: Credit Card Fraud Detection Model
- **Author**: Swati Dogra
- **Date**: 3/1/2025

## Objectives
 Developing a robust model to detect fraudulent credit card transactions to minimize 
financial losses.


## Data Source
The primary dataset for this project will be sourced from Kaggle, specifically the "Credit Card Fraud 
Detection" dataset. This dataset contains transaction records with features such as transaction amount, 
time, and anonymized variables, along with a label indicating whether each transaction is fraudulent. 

## Dataset Description:  
The dataset contains 284,807 transactions made by credit cards in September 2013 by European 
cardholders. It is highly imbalanced, with only 492 fraudulent transactions. Each transaction has 30 
features, which are the result of a PCA transformation, as the original features are anonymized due to 
confidentiality issues. The features include the following: 
 Time: The seconds elapsed between this transaction and the first transaction in the dataset. 
 V1 to V28: The principal components obtained with PCA. 
 Amount: The transaction amount. 
 Class: The response variable, where 1 represents a fraudulent transaction and 0 represents a 
legitimate transaction.


## Tools and Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
- Seaborn

## Methodology
The analysis will include the following methods: 
1. Exploratory Data Analysis (EDA) to understand the dataset and identify key features. 
2. Data preprocessing, including handling missing values, scaling, and balancing the dataset. 
3. Implementation of various machine learning algorithms such as Logistic Regression, Decision 
Trees, Random Forest, and Gradient Boosting. 
4. Model evaluation using metrics like accuracy, precision, recall, F1-score, and ROC-AUC. 
5. Hyperparameter tuning to optimize model performance.


## Results
The analysis involves evaluating the performance of various machine learning models on the dataset. The 
models are evaluated based on accuracy, precision, recall, F1-score, and ROC-AUC. Additionally, confusion 
matrices are plotted to visualize the true positive, false positive, true negative, and false negative rates. 

1. Logistic Regression: 
 Precision: 97.41% (good precision indicates most flagged transactions are indeed fraud). 
 Recall: 92.19% (good recall but misses some fraudulent transactions). 
 The confusion matrix shows it correctly identified 78,769 fraudulent transactions but missed 
6,671 (false negatives). 

2. Decision Tree: 
 Precision: 99.69% (very high, meaning very few false alarms). 
 Recall: 99.90% (excellent recall, very few fraudulent transactions missed). 
 The confusion matrix shows only 89 missed fraud cases (false negatives). 

3. Random Forest: 
 Precision: 99.98% (extremely high precision, almost no false positives). 
 Recall: 100% (perfect recall, no fraudulent transactions missed). 
 The confusion matrix indicates all fraudulent transactions were correctly identified with almost 
no false alarms. 

4. Gradient Boosting: 
 Precision: 98.72% (high precision, few false alarms). 
 Recall: 96.76% (good recall, though some fraud cases are missed). 
 The confusion matrix shows it missed 2,764 fraudulent transactions but correctly identified 
82,676.


## Conclusion
When dealing with highly imbalanced datasets like this one, the evaluation metrics take on added 
significance: 
1. Precision becomes crucial in this context. Since only a small fraction of transactions are 
fraudulent, a high precision indicates that the model is very accurate in identifying fraud. This is 
important as false positives (non-fraudulent transactions incorrectly classified as fraudulent) can 
be costly and inconvenient for customers. 
2. Recall is equally important. A high recall means the model effectively identifies most of the actual 
fraud cases. Since missing a fraudulent transaction can have severe consequences, a high recall is 
critical to ensure that few fraudulent transactions are missed. 
3. F1-Score balances both precision and recall. Given the imbalanced nature, this score helps ensure 
the model maintains a good balance between identifying fraudulent transactions and minimizing 
false positives. 
4. ROC-AUC provides an aggregate measure of the model's performance across all classification 
thresholds. A high ROC-AUC score indicates that the model is good at distinguishing between 
fraudulent and non-fraudulent transactions. 
5. Confusion Matrix is crucial in understanding the distribution of true positives (correctly identified 
fraud), false positives (incorrectly flagged as fraud), true negatives (correctly identified non
fraud), and false negatives (missed fraud). 

The study demonstrates that machine learning models can effectively detect fraudulent credit card 
transactions. Among the models evaluated, the Random Forest model exhibited the highest performance 
with near-perfect precision and recall, indicating its potential for deployment in real-world scenarios. 
However, it is crucial to address the imbalanced nature of the dataset and ensure the models generalize 
well to new data. 



## Future Work
1. Integration with real-time transaction monitoring systems. 
2. Application to other types of financial fraud detection. 
3. Expansion to include other forms of anomaly detection in financial systems. 


## Contact
For questions or support, please open an issue on this repository or contact [sdogra@my365.bellevue.edu].

