# Machine Learning-Based DDoS Attack Detection in Cloud Networks

**Author:** Ranish Ghimire
**Institution:** Gisma University of Applied Sciences, Potsdam
**Programme:** M.Sc. Data Science, AI & Digital Business

---

## Overview

This project implements and evaluates three supervised machine learning classifiers — Decision Tree, Random Forest, and XGBoost — for detecting DDoS attacks in cloud network traffic using the CIC-IDS2017 dataset.

---

## Dataset

* Source: Canadian Institute for Cybersecurity (CIC-IDS2017)
* File: Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv
* Download: https://huggingface.co/datasets/c01dsnap/CIC-IDS2017/blob/main/Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv

---

## How to Run

1. Download the dataset from the link above

2. Place the CSV file in the same folder as the notebook

3. Install dependencies:

   pip install pandas numpy scikit-learn xgboost matplotlib

4. Run all cells from top to bottom

---

## Pipeline

* Data loading and exploration
* Data preprocessing (null removal, duplicates, encoding, scaling)
* Dimensionality reduction (PCA)
* Model training (Decision Tree, Random Forest, XGBoost)
* Model evaluation (Accuracy, Confusion Matrix, ROC-AUC)
* Feature importance visualization

---

## Models

* Decision Tree
* Random Forest
* XGBoost

---

## Objective

To build a machine learning model that can accurately detect DDoS attacks in cloud environments.
