# Bank Customer Churn Prediction
**MDA512 Data Science — Assignment 2 (T1 2026)**

## Team Members
- Aravind Duggani (MIT251477)
- Preethi Mothe   (MIT252989)
- Prasan Rana     (MIT254245)
- Rohan Thapa     (MIT255815)
- Rhiddhi Chakma  (MIT251478)

## Project Overview
This project predicts which bank customers are likely to leave (churn)
so the bank can target retention campaigns. We compare three machine
learning algorithms on a dataset of 10,000 customers from France,
Spain, and Germany.

## Dataset
- **Source:** Kaggle — Churn Modelling Dataset
- **Size:** 10,000 rows × 14 columns
- **Target:** `Exited` (1 = customer left, 0 = stayed)

## Methods
- Logistic Regression (baseline)
- Random Forest
- Gradient Boosting

## How to Run
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/churn_analysis.ipynb` in Jupyter

## Folder Structure
- `data/` — raw dataset
- `notebooks/` — Jupyter notebook with full analysis
- `src/` — Python script version
- `figures/` — generated plots
- `report/` — final Word report

## Unit Information
- **Unit:** MDA512 Data Science
- **Lecturer:** Dr. Samar Shailendra
- **Institution:** Melbourne Institute of Technology
