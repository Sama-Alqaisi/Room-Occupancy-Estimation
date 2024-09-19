# Room-Occupancy-Estimation
# Introduction
This project aims to estimate room occupancy levels using various sensor data collected from environmental sensors. By applying machine learning models, the project seeks to accurately predict whether a room is occupied or not based on sensor readings like temperature, light levels, sound, CO2 concentration, and PIR sensor data. The repository includes code, datasets, and documentation to facilitate the analysis and modeling process.

# Dataset Overview
The dataset consists of sensor readings captured over time and includes the following features:
- Temperature: Ambient temperature in the room.
- Light: Light intensity measured in the room.
- Sound: Noise levels recorded by the sensors.
- CO2: CO2 concentration in the room.
- PIR Sensor Readings: Passive Infrared Sensor data indicating movement.
- Occupancy: Binary label indicating whether the room is occupied (1) or not (0).
This dataset serves as the foundation for modeling and predicting room occupancy patterns.

# Project Objectives
- Data Preprocessing: Clean the dataset by handling missing values, outliers, and normalizing features.
- Feature Engineering: Create new features that enhance model performance based on initial data analysis.
- Modeling: Develop and evaluate various machine learning models (Random Forest, Gradient Boosting, XGBoost, SVM) to predict room occupancy.
- Evaluation: Compare model performance using metrics such as accuracy, precision, recall, F1-score, and ROC AUC to select the best-performing model.

# Core Components
- Exploratory Data Analysis (EDA): Visualize sensor data trends and relationships to gain insights into factors influencing room occupancy.
- Machine Learning: Build, train, and validate multiple models to estimate room occupancy effectively.
- Result Analysis: Provide a comparative analysis of the models to determine the most effective approach for predicting room occupancy.

# Tools & Libraries Used
- Python: The programming language used for data processing and modeling.
- Pandas, NumPy: Libraries for data manipulation and numerical operations.
- Scikit-learn: For building and evaluating machine learning models.
- Matplotlib, Seaborn: For creating visualizations and graphical representations of data.

# Documentation
The project includes:
- A detailed report outlining the data preprocessing steps, modeling approaches, and evaluation results.
- Python notebooks with code for data exploration, feature engineering, model implementation, and performance evaluation.
- The Dataset.
