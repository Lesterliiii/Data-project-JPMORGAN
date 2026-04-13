# Retail ML Project

## Overview
This project builds two machine learning solutions for a retail marketing use case:

1. **Classification Model**  
Predict whether a person earns **> $50K or ≤ $50K** using demographic and employment data.

2. **Segmentation Model**  
Group customers into segments to support targeted marketing strategies.

## Files
- `retail_business_ML_project.ipynb` — main notebook (data processing, modeling, results)
- `census-bureau.data` — dataset
- `census-bureau.columns` — column names
- `ML-TakehomeProject.pdf` — project requirements

## How to Run

### Option 1: Google Colab
1. Upload the notebook to Colab
2. Upload data files to Google Drive
3. Update file paths if needed
4. Run all cells

### Option 2: Local (Jupyter)
1. Place all files in one folder
2. Install dependencies:
```bash
pip install numpy pandas scikit-learn xgboost lightgbm
