# Basic ML algorithms

## Overview

This notebook provides an overview of ML model selection for binary classification tasks. It demonstrates hyperparameter optimization via 'for' loops, utilizing graphs and DataFrames to analyze performance metrics.
We assume that the data has already been preprocessed and we will mostly focus on training, evaluating and comparing different models.
Our goal is to identify users with the plan Ultra, based on their consumptions.

## Features
- **Modeling:** Implementation and comparison of machine learning models including Decision Tree, Random Forest, and Logistic Regression.
- **Evaluation:** Use of accuracy score, TPR and FPR.

## How to Use
1. Clone this repository or download the notebook.
2. Ensure you have the required dependencies (see below).
3. Open `basic_ml.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells sequentially to reproduce the analysis and results.


## Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Data
The notebook uses the `users_behavior.csv` dataset, which contains internet, calls, and messages consumption of costumers of a phone company. The data is located in the `data/` directory.

## Project Structure
```
basic_ml_algorithms/
├── basic_ml.ipynb
├── data/
│   └── users_behavior.csv
├── README.md
└── requirements.txt
```


## Results
- Achieved significant predictive performance using Random Forest.
- Explored the effect of hyperparameter optimization with plots and DataFrames.


## Notes on Class Imbalance Handling
This project includes a detailed comparison of upsampling, downsampling, and SMOTE for class imbalance, using the `imbalanced-learn` library. The notebook demonstrates how these techniques affect model performance and threshold selection for business objectives.

## COMING CHANGES:
- Plots and graphs improved.
- Deep analysis of hyperparameter optimization effect.

---


