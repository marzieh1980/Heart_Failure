Heart Failure Prediction


Project Overview

This project aims to predict heart failure events using clinical data. The analysis includes comprehensive Exploratory Data Analysis (EDA), feature selection, and benchmarking of several machine learning classification models.

Dataset
The dataset contains 299 clinical observations with 13 features, including clinical markers like serum_creatinine, ejection_fraction, and age.

Analysis Workflow
Exploratory Data Analysis (EDA): Visualizing feature distributions and mortality correlations using Seaborn and Matplotlib.
Feature Selection: Identifying key predictors using Correlation Matrices, Univariate Selection (SelectKBest), and Tree-based Feature Importance.
Model Development: Comparing performance across multiple algorithms:
Logistic Regression
Support Vector Classifier (SVC)
Decision Tree Classifier
Random Forest Classifier
ExtraTrees Classifier
K-Nearest Neighbors (KNN)

🚀 Project Highlights
Exploratory Data Analysis: Visualized clinical features like serum_creatinine and ejection_fraction using Seaborn and Plotly.
Feature Selection: Compared three techniques (Correlation Heatmaps, Univariate Selection, and Tree-based Importance) to identify key predictors.
Model Benchmarking: Implemented and evaluated Logistic Regression, SVC, Decision Trees, Random Forest, and KNN.
Performance Metrics: Detailed breakdowns of Accuracy and Error Rates using Confusion Matrices.

📊 Key Results
Top Performers: Logistic Regression achieved the highest test accuracies.
Critical Indicators: serum_creatinine and ejection_fraction were identified as the most significant clinical predictors of heart failure events.
Class Imbalance: The dataset's imbalance towards survived patients significantly influenced model specificity.

🛠️ Tech Stack
Language: Python
Libraries: Pandas, Scikit-Learn, Seaborn, Matplotlib, Plotly, mlxtend
Environment: Google Colab / Jupyter Notebook

📂 How to use and run
1. Clone the repository.
2. Install dependencies: pip install -r requirements.txt
3. Open Heart_Failure_Prediction.ipynb in Google Colab or Jupyter Notebook.
4. Run all cells to reproduce the analysis.
