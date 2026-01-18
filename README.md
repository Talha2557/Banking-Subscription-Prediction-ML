# Banking Subscription Prediction (From Scratch)

## Project Overview
This project predicts whether a customer will subscribe to a bank term deposit. It is built strictly from scratch for the MS-AI program at Superior University.

**Student:** Abdul Wahab  
**Roll No:** SU92-MSAIW-S25-031  
**Target SDG:** SDG 9 (Industry, Innovation, and Infrastructure)

## About the Model
A Machine Learning project built from scratch to predict bank term deposit subscriptions using the UCI Bank Marketing Dataset. Implemented using a **Single-Layer Perceptron (Logistic Regression)** with custom Gradient Descent, featuring manual forward/backward propagation, sigmoid activation, and binary cross-entropy loss.

## Key Features
- **No Pretrained Models:** All algorithms are implemented manually using NumPy.
- **Data Preprocessing:** Manual Label Encoding and Z-score normalization.
- **Evaluation:** Using F1-Score and AUC-ROC to handle class imbalance.

---

## 📈 Week 1: Foundation & Planning (Completed)
- **Data Ingestion:** Successfully mounted Google Drive and loaded the `bank-full.csv` dataset using Pandas.
- **Exploratory Data Analysis (EDA):** - Verified that the dataset contains **45,211 records** and **17 features**.
    - Checked for missing values (None found in the UCI dataset).
    - **Class Imbalance Identified:** Visualized the target variable `y`. Only about 11% of customers subscribed, which means I will need to use stratified splits in Week 2.
- **Baseline Metrics:** Established that F1-Score will be the primary success metric.

---

## 4-Week Plan
- [x] **Week 1:** Data Ingestion & EDA (Done)
- [ ] **Week 2:** Model Development from Zero (Sigmoid, Loss, and Training Loop)
- [ ] **Week 3:** Refinement & Metric Evaluation
- [ ] **Week 4:** Documentation & Demo Video
