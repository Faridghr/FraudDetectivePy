# FraudDetectivePy
Python-based supervised machine learning project developed as the final project for INFO 6105 (Data Science Eng Methods).

## Overview
The goal of this project is twofold: first, to understand how an imbalanced dataset can impact the analysis and results of credit card fraud detection; and second, to evaluate the effectiveness of different classification models and techniques aimed at enhancing the accuracy and reliability of fraud detection systems.

## Key Objectives
- Understand the effects of imbalanced datasets on fraud detection analysis.
- Compare Undersampling and Oversampling techniques for addressing data imbalance.
- Benchmark the performance of different classification models.
- Address outliers and normalize features to refine analysis and predictions.

## Project Structure
- **dataset/**: Contains dataset used for the project.
- **src/**: Contains Python scripts for data preprocessing, model training, and evaluation.
- **report/**: Stores [Report](report) files.

## Dependencies
- Python
- NumPy
- Pandas
- Scikit-learn
- xgboost
- Matplotlib
- Seaborn

## Usage
1. Clone the repository: `git clone https://github.com/Faridghr/FraudDetectivePy.git`
2. Navigate to the project directory: `cd FraudDetectivePy`
3. Install dependencies: `pip install -r requirements.txt`
4. Download the dataset and extract it to the `dataset` folder.
5. Run the main script to preprocess data, train models, and evaluate performance: `src/FraudDetectivePy.ipynb`

## Acknowledgements
The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?select=creditcard.csv).

