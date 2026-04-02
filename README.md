# Blood Pressure Estimation from PPG Signals
## Overview
This project focuses on estimating systolic and diastolic blood pressure using Photoplethysmography (PPG) signals.
It simulates real-world biomedical data challenges like noise, artifacts, and variability across subjects, and builds robust deep learning models for prediction.

## Key Highlights
Processed 100,000+ PPG/ABP signal windows from physiological datasets
Improved data quality by ~30% using Signal Quality Index (SQI)-based filtering
Built BiLSTM + Attention models for time-series prediction
Achieved Mean Absolute Error (MAE) < 5 mmHg for BP estimation

## Pipeline
- Data Preprocessing
- Signal normalization & segmentation (sliding windows)
- SQI-based filtering to remove noisy/artifact signals
- Feature Engineering
- Temporal sequence creation
- Physiological signal alignment (PPG ↔ ABP)
- Modeling
- BiLSTM for sequence learning
- Attention mechanism for capturing important temporal features
- Evaluation
- Metrics: MAE, prediction stability
- Subject-wise data split for generalization

## Tech Stack
Languages: Python
Libraries: NumPy, Pandas, PyTorch, Matplotlib
Concepts: Time-Series Modeling, Signal Processing, Deep Learning
