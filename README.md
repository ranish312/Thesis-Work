Machine Learning-Based DDoS Attack Detection in Cloud Networks
Author: Ranish Ghimire
Institution: Gisma University of Applied Sciences, Berlin
Programme: M.Sc. Data Science, AI & Digital Business

Overview
This notebook implements and evaluates three supervised machine learning classifiers — Decision Tree, Random Forest, and XGBoost — for detecting DDoS attacks in cloud network traffic using the CIC-IDS2017 dataset.

Dataset
Source: Canadian Institute for Cybersecurity — CIC-IDS2017
File used: Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv
Download: https://huggingface.co/datasets/c01dsnap/CIC-IDS2017/blob/main/Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv
How to Run
Download the dataset from the link above and place the CSV file in the same directory as this notebook.
Install dependencies: pip install pandas numpy scikit-learn xgboost matplotlib
Run all cells in order from top to bottom.
Pipeline Summary
Data loading and exploratory analysis
Preprocessing (null removal, deduplication, encoding, scaling)
Dimensionality reduction (PCA)
Model training (Decision Tree, Random Forest, XGBoost)
Model evaluation (Accuracy, Classification Report, Confusion Matrix, ROC-AUC)
Feature importance visualisation
