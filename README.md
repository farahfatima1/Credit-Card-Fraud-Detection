**Credit Card Fraud Detection Using Machine Learning**



A machine learning project that detects fraudulent credit card transactions using the Random Forest classification algorithm.



&#x20;**Dataset**

\- Total transactions: 284,807

\- Normal transactions: 284,315

\- Fraudulent transactions: 492

\- Features: 30

\- Missing values: 0



**Technologies Used**

\- Python

\- Google Colab

\- Pandas

\- NumPy

\- Scikit-learn

\- Imbalanced-learn

\- Matplotlib

\- Seaborn



&#x20;**Methodology**

1\. Dataset loading and exploration

2\. Data preprocessing and feature scaling

3\. Train-test splitting

4\. Handling class imbalance using SMOTE on training data

5\. Random Forest model training

6\. Model evaluation



**Model Performance**



| Metric | Score |

|---|---:|

| Accuracy | 99.95% |

| Precision | 84.54% |

| Recall | 83.67% |

| F1-Score | 84.10% |

| ROC-AUC | 97.31% |



&#x20;**Confusion Matrix**



| | Predicted Normal | Predicted Fraud |

|---|---:|---:|

| Actual Normal | 56,849 | 15 |

| Actual Fraud | 16 | 82 |



**Feature Importance**



The ten most important features include V14, V10, V4, V12, V17, V3, V11, V16, V2, and V9.



**Project Files**



\- `Credit\_Card\_Fraud\_Detection\_.ipynb` – Complete Google Colab notebook.





&#x20;**Disclaimer**



This project is developed for educational and research purposes. It is not intended for real-world financial fraud prevention without further validation.

