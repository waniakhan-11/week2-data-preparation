# Bank Marketing Data Preparation

## Dataset
- **Name:** Bank Marketing
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- **Target:** `y` (yes/no term deposit subscription)
- **Problem type:** Binary classification

## Project Summary
This project prepares the Bank Marketing dataset for machine learning. It includes exploratory data analysis, duplicate checking, missing-value handling, and feature engineering. The data is split into training and testing sets, then numeric features are imputed and scaled while categorical features are imputed and one-hot encoded. The preprocessing pipeline is fitted only on training data to prevent data leakage.

## How to Run
1. Open `Bank_Marketing_Data_Preparation.ipynb` in Google Colab or Jupyter Notebook.
2. Run the cells from top to bottom.
3. Ensure internet access is available to download the dataset from UCI.
4. The final outputs are `X_train`, `X_test`, `y_train`, and `y_test`.

## Files
- `Bank_Marketing_Data_Preparation.ipynb` — notebook
- `README.md` — project overview and instructions
- `requirements.txt` — required Python packages
