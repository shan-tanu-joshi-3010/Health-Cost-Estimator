# Health-Cost-Estimator

This project implements a machine learning model to predict **health insurance costs** based on various patient attributes such as age, BMI, smoking status, and other factors. The model is built using regression techniques to analyze the relationship between medical costs and these independent variables.

## Features
- **Regression-Based Prediction** – Uses machine learning regression to estimate insurance costs.
- **Data Preprocessing** – Handles missing values, encodes categorical data, and normalizes numerical features.
- **Model Training & Evaluation** – Implements linear regression and other regression models.
- **Visualization** – Provides insights into the impact of different features on health costs.
- **Dataset Handling** – Uses publicly available medical insurance datasets.

## Installation & Usage
1. Clone the repository:
   git clone https://github.com/yourusername/health-cost-prediction.git
2. Install dependencies:
   pip install -r requirements.txt
3. Run the training script:
   python train.py
4. Predict health costs for a new patient:
   python predict.py --age 30 --bmi 25.3 --smoker yes
