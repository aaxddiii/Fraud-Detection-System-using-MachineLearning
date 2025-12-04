Fraud Detection System Using Machine Learning
Logistic Regression | Random Forest | XGBoost

This project is a Machine Learning–based Fraud Detection System developed as part of our academic submission for JECRC University – 7th Semester, CSE.
We compare three ML models:
Logistic Regression
Random Forest Classifier
XGBoost Classifier

To handle extreme class imbalance (0.17% fraud cases), we apply SMOTE oversampling.

👥 Team Members
Name	                   Roll No
Darshan Jain	           22BCON533
Aaditya Mathur	         22BCON520
Deepak Kumar	           22BCON1383
Kriti Jain	             22BCON390

📂 Dataset
Kaggle – Credit Card Fraud Detection Dataset
(284,807 transactions, 492 fraud cases)

Features:
V1 – V28: PCA-transformed features
Time, Amount
Class: 0 = legitimate, 1 = fraud
Dataset is not included due to Kaggle policy.

🔧 Technology Stack
Python
Scikit-Learn
XGBoost
Pandas, NumPy
Imbalanced-Learn (SMOTE)
Matplotlib / Seaborn

📌 Project Workflow
Dataset → Preprocessing → Scaling → SMOTE → Train Models 
        → Compare Metrics → Best Model Output
        
🧠 Models Implemented
✔ Logistic Regression
Baseline linear classifier.
✔ Random Forest
Ensemble trees → good for non-linear patterns.
✔ XGBoost (Best Performer)
Handles imbalanced data and captures complex relations.

📈 Evaluation Metrics
Metric	   Logistic	  Random Forest  	XGBoost
Accuracy	  96–98%	     98–99%	       99%+
Precision	   0.92	        0.97	       0.99
Recall	     0.85	        0.95	       0.98
F1-score	   0.88	        0.96	       0.98
ROC-AUC	     0.97       	0.99	      >0.99

🚀 XGBoost gives maximum recall → best at catching fraud.
(Fewer false negatives = lower financial loss)
