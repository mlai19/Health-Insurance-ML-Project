# Health-Insurance-ML-Project

<img width="1393" height="980" alt="image" src="https://github.com/user-attachments/assets/45c392c7-a06b-4cb5-afc0-aab7d1c968ac" />


Project Overview
--

This project applies machine learning to predict insurance claims using customer and policy data. The workflow includes cleaning the dataset, exploring relationships between variables, engineering features, and building models to classify claim outcomes.

The goal was to demonstrate the complete machine learning pipeline and highlight how predictive models can be used in the insurance industry.

Objectives
--
- Load and explore the insurance dataset
- Perform preprocessing, including handling missing values and encoding categorical data
- Analyze variable distributions and correlations with claims
- Engineer new features to improve prediction accuracy
- Train models such as Logistic Regression, Random Forest, and Gradient Boosting
- Evaluate results with accuracy, precision, recall, and F1-score

Project Structure
--
1. Data Loading
- Read the dataset (insurance.csv) with pandas

2. Exploratory Data Analysis
- Examined distributions of key features such as smoker status, age, sex, and charges
- Visualized patterns using matplotlib and seaborn

3. Preprocessing
- Converted categorical columns into numeric format
- Scaled numerical features where needed

4. Model Training
- Built baseline models for classification
- Trained ensemble models to improve predictive performance

5. Evaluation
- Compared models using standard metrics
- Identified features with the highest predictive power

Results and Insights
--
- Smoking status and bmi were the strongest predictors of claims
- Ensemble models such as Random Forest performed better than simpler models
- Preprocessing and feature engineering significantly improved accuracy

About
--
Python-based machine learning project built in Jupyter Notebook with pandas, NumPy, scikit-learn, matplotlib, and seaborn.
