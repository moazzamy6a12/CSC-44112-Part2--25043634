# CSC-44112-Part2--25043634
Driver Behaviour Classification Using Smartphone Sensor Data With AI and ML
Module: CSC-44112 — Advanced Applications of AI and ML
Student: Muhammad Moazzam Kiani | ID: 25043634
Academic Year: 2025–2026

dataset link:
https://www.kaggle.com/datasets/outofskills/driving-behavior


Project Overview
This project develops a machine learning pipeline to classify driver behaviour as Normal, Aggressive, or Slow using smartphone accelerometer and gyroscope data. Four models are compared: Random Forest, Logistic Regression, KNN, and ANN.

| File | Description |
|------|-------------|
| `25043634_Part2.ipynb` | Main Jupyter Notebook (full pipeline) |
| `train_motion_data.csv` | Training dataset |
| `test_motion_data.csv` | Test dataset |

| Model | Accuracy | Macro AUC |
|-------|----------|-----------|
| Random Forest | 92.94% | 0.989 |
| ANN | 85.96% | 0.965 |
| KNN (k=1) | 73.63% | 0.799 |
| Logistic Regression | 54.75% | 0.743 |

Dataset
Outofskills (2021) — Driving Behavior Dataset

How to Run

1. Clone the repository
2. Ensure train_motion_data.csv and test_motion_data.csv are in the same folder as the notebook
3. Run all cells in 25043634_Part2.ipynb
