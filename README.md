# Heart Disease Detection

This project explores the application of machine learning techniques to detect the presence of heart disease from clinical data. The goal is to build a robust and accurate predictive model that can aid healthcare professionals in identifying individuals at high risk.

## Project Overview
The project follows a comprehensive data science methodology, from exploratory data analysis to model building and evaluation. Several supervised learning algorithms are compared to find the most effective approach for this classification task.

## Key Features
- **Exploratory Data Analysis (EDA):** In-depth analysis and visualization of the dataset to identify patterns, relationships, and key clinical indicators influencing heart disease.  
- **Data Preprocessing:** A complete pipeline for handling missing values, feature engineering, normalization, and managing class imbalance to ensure clean and reliable data for model training.  
- **Model Building:** Development and evaluation of various machine learning models, including:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine (SVM)  
  - XGBoost  
  - LightGBM  
- **Performance Metrics:** The models are evaluated using a range of metrics, including accuracy, precision, recall, F1 score, and AUC-ROC, to provide a balanced assessment of their performance.

## Dataset
The project utilizes the **Cleveland Heart Disease dataset**, which contains various clinical and physiological attributes.

## Methodology
1. **Data Acquisition:** The dataset is loaded and prepared for analysis.  
2. **EDA:** Performed to understand the data distribution and feature correlations.  
3. **Preprocessing:** Data is cleaned, transformed, and split into training and testing sets.  
4. **Model Training:** Each machine learning algorithm is trained on the preprocessed data.  
5. **Evaluation:** Models are assessed based on the predefined performance metrics.  
6. **Results:** A comparison of all models is provided, with a discussion of the most promising results.

## Results
The report found that **Logistic Regression**, while not always the highest in raw accuracy, provided the most balanced and interpretable performance, making it a strong candidate for real-world deployment. The project achieved a **notable accuracy of 82.4% with high recall**, demonstrating its potential for minimizing missed diagnoses.

## How to Run
1. Clone this repository.  
2. Install the required dependencies (e.g., **NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn**).  
3. Execute the provided Jupyter notebook or Python script to reproduce the analysis and model results.
