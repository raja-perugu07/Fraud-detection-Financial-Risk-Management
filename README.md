# Fraud-detection-Financial-Risk-Management
End-to-end machine learning project for financial fraud detection using large-scale transaction data, feature engineering, class imbalance techniques, Random Forest, XGBoost, and model evaluation focused on real-world fraud risk.

## Dataset

This project uses the **Online Payments Fraud Detection Dataset** from Kaggle.

Dataset link:  
https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset

The dataset contains approximately 6.36 million financial transactions and includes both legitimate and fraudulent transactions.

The dataset file is not included in this repository because of its large size.

## Project Files

- `FD.ipynb` — Main Jupyter Notebook containing the project code and analysis
- `F837G868-RAJA PERUGU.pptx` — Weekly project presentation
- `F837G868_PROJECT_PROPOSAL.pdf` — Project proposal

## Work Completed

The notebook currently includes:

- Data loading and initial data understanding
- Exploratory Data Analysis
- Feature Engineering
- Data splitting
- Class imbalance handling
- Class weighting
- Random undersampling
- Random oversampling
- Random Forest model
- XGBoost model
- Model evaluation using Precision, Recall, F1-score, AUPRC, and Confusion Matrix
- False-positive and false-negative analysis
- Initial time-based validation setup

## How to Run the Project

1. Download or clone this repository.

2. Download the dataset from the Kaggle link provided above.

3. Place the dataset CSV file in the same working directory used by the notebook.

4. Install the required Python packages:

```bash
pip install pandas numpy matplotlib scipy statsmodels wquantiles scikit-learn imbalanced-learn xgboost
```

5. Open the Jupyter Notebook:

```text
FD.ipynb
```

6. Run the notebook cells from top to bottom.

If the dataset is stored in a different folder, update the dataset file path in the notebook before running the cells.
