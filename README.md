# Supervised-Machine-Learning-Model

## Project Overview
This project demonstrates the implementation of supervised machine learning algorithms using Python and Scikit-learn.

The main objective is to understand how regression and classification models work, train different algorithms, make predictions, and compare their performance using evaluation metrics.

## Technologies Used
- Python
- Google Colab
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Joblib

## Datasets Used

### 1. Regression Dataset
- **Dataset:** Diabetes Dataset (Scikit-learn)
- **Records:** 442
- **Features:** 10
- **Target:** Numerical disease-progression measure

### 2. Classification Dataset
- **Dataset:** Breast Cancer Wisconsin Dataset (Scikit-learn)
- **Records:** 569
- **Features:** 30
- **Target:** Malignant or Benign
- **Label 0:** Malignant
- **Label 1:** Benign

*Note: These datasets are used only for educational machine learning experiments, not for medical diagnosis.*

## Machine Learning Algorithms Implemented

### Regression
1. Linear Regression
2. Decision Tree Regressor

### Classification
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors (KNN)

## Project Workflow
1. Import required Python libraries.
2. Load the datasets.
3. Explore the datasets and check missing values and duplicate records.
4. Split the data into training and testing sets (80:20).
5. Apply feature scaling where required.
6. Train the machine learning models.
7. Make predictions using trained models.
8. Evaluate model performance.
9. Compare the results using tables and graphs.
10. Save trained models and comparison results.

## Model Evaluation Results

### Regression Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 42.79 | 53.85 | 0.45 |
| Decision Tree | 53.92 | 69.91 | 0.08 |

**Observation:** Linear Regression performed better than the Decision Tree Regressor because it achieved lower prediction errors and a higher R² score on the test dataset.

### Classification Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 98.25% | 97.62% | 97.62% | 97.62% |
| Decision Tree | 91.23% | 84.78% | 92.86% | 88.64% |
| Random Forest | 95.61% | 95.12% | 92.86% | 93.98% |
| KNN | 95.61% | 95.12% | 92.86% | 93.98% |

**Observation:** Logistic Regression achieved the highest accuracy and F1 score among the tested classification models on this train-test split.

## Files Included
- Jupyter Notebook (`.ipynb`) – Complete implementation and execution.
- `regression_model_comparison.csv` – Regression model results.
- `classification_model_comparison.csv` – Classification model results.
- `.pkl` files – Saved trained machine learning models and feature scalers.

## How to Run the Project
1. Download or clone this GitHub repository.
2. Open Google Colab: https://colab.research.google.com/
3. Upload the Jupyter Notebook.
4. Run the notebook cells from top to bottom.
5. Review the model evaluation tables and comparison graphs.

## Conclusion
In this project, I implemented and compared different supervised machine learning algorithms for regression and classification tasks.

I learned how to load and preprocess datasets, split data into training and testing sets, apply feature scaling, train machine learning models, evaluate their performance, and save trained models.

The results showed that different algorithms perform differently depending on the dataset and task. Model comparison helped me understand the importance of selecting an appropriate algorithm based on evaluation metrics.

---
**Project:** Supervised Machine Learning Models  
**Language:** Python  
**Library:** Scikit-learn
