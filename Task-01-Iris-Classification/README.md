# Multi-Class Benchmark Classification Pipeline

## Project Overview

This project implements a multi-class classification pipeline using the Iris dataset. It compares two machine learning algorithms: Logistic Regression and Decision Tree.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The Iris dataset contains 150 samples, 4 numerical features, and 3 flower species:

- Setosa
- Versicolor
- Virginica

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Scaling using StandardScaler
5. Train-Test Split (80:20)
6. Model Training
   - Logistic Regression
   - Decision Tree
7. Model Evaluation
   - Accuracy
   - Precision
   - Recall
   - F1-Score
8. Confusion Matrix Visualization
9. Model Performance Comparison
10. Decision Boundary Visualization

## Project Structure

```text
Task-01-Iris-Classification/
├── data/
│   └── iris.csv
├── notebooks/
│   └── iris_classification.ipynb
├── results/
│   ├── confusion_matrix.png
│   ├── model_comparison.png
│   └── decision_boundary.png
└── README.md
```

## How to Run

1. Clone this repository.
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `notebooks/iris_classification.ipynb` and run the cells.

## Evaluation

The two classification models are compared using Accuracy, Precision, Recall, and F1-Score. Confusion matrices and decision boundaries are also visualized to analyze their performance."# 4Tasks" 
