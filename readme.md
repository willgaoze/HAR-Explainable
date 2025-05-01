# Human Activity Recognition with Random Forest and SHAP

This project implements a lightweight, interpretable Human Activity Recognition (HAR) system using smartphone sensor data. It combines Random Forest classifiers with SHAP explanations for global and local interpretability.

## 📁 Project Structure

project/ ├── main.ipynb ├── README.md ├── requirements.txt ├── shap_summary_plot.png ├── shap_waterfall_plot.png ├── confusion_matrix.png ├── feature_importance_top50.png ├── baseline_result.png ├── cv_boxplot.png ├── optimization.png └── UCI HAR Dataset/  ← or provide download link

```
markdown


复制编辑
```

## 📊 Features

- Trains and evaluates Random Forest, SVM, and Decision Tree classifiers.
- Uses SHAP to visualize feature importance and explain predictions.
- Includes robustness testing (e.g., Gaussian noise).
- Includes model compression via top-100 features.
- Cross-validation results and confusion matrix analysis.

## 📦 Setup Instructions

### 1. Clone and Install

```bash
pip install -r requirements.txt
```

### 2. Dataset(already contained)

Download the UCI HAR Dataset:

[UCI HAR Link](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

Unzip and place it in the root directory as `UCI HAR Dataset`.

### 3. Run

Open `main.ipynb` and run all cells.