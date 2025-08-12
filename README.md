# Deep-Learning-Models-for-Early-Detection-of-Diabetes-Mellitus
"Early detection of diabetes using machine learning and deep learning. Built ANN (94% accuracy) and CatBoost (91%) models on 2000+ patient records with data preprocessing, feature engineering, and tuning to classify diabetes types, aiming to support preventive healthcare."         
📌 Project Overview
This project implements machine learning and deep learning models to detect and classify different types of diabetes at an early stage using patient clinical data. It aims to assist in preventive healthcare by providing accurate and timely predictions.

🛠 Technologies & Tools Used
Languages: Python

Libraries: Pandas, NumPy, CatBoost, TensorFlow/Keras, Scikit-learn, Matplotlib

IDE & Tools: Jupyter Notebook, VS Code, GitHub

Techniques: Data preprocessing, feature engineering, model training, hyperparameter tuning

📊 Dataset
Dataset contains 2000+ patient records with features such as glucose level, blood pressure, BMI, and other health parameters.

Data cleaning and handling of missing values performed using Pandas.

🚀 Implementation Details
Model 1: Artificial Neural Network (ANN) – Achieved 94% accuracy

Model 2: CatBoost Classifier – Achieved 91% accuracy

Preprocessing involved normalization, categorical encoding, and feature selection.

Used train-test split and cross-validation to ensure model generalization.

🎯 Key Features
Multi-class classification to detect Type 1, Type 2, and gestational diabetes.

High accuracy and robustness with minimal overfitting.

Modular code structure for easy model replacement and scaling.

📈 Results & Insights
ANN model performed better for complex feature interactions.

Feature importance analysis showed glucose level, BMI, and age as key predictors.

🔗 How to Run
Clone the repository

Install dependencies:


pip install -r requirements.txt
Run the notebook or Python script to train and evaluate the model
