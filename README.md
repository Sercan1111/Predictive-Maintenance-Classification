# Electrical Fault Detection Classification

## Overview
This project aims to perform predictive maintenance classification using a dataset that includes various features related to machine performance and conditions. The project applies binary classification to detect whether maintenance is required and multi-class classification to identify the type of fault. The solution utilizes Python libraries such as pandas, scikit-learn, TensorFlow, Keras Tuner, and matplotlib for preprocessing, analysis, modeling, and visualization.

## Dataset
- predictive_maintenance.csv: Contains features and target variables related to machine performance and failure types.
- Features: Includes sensor readings and other relevant data.
- Target Variables: Binary target for maintenance required and multi-class target for fault types.

## Preprocessing Steps
1. Data Loading:
2. Data Cleaning:
3. Feature Scaling:
4. Feature Engineering:


## Visualization
- Bar Plots: Visualize the relationship between independent and dependent features.
- Histograms: Show the distribution of continuous variables.
- Boxplots: Display the spread and outliers in continuous variables.
- Correlation Matrix: Visualize the correlation between different features using a heatmap.
## Classification Model
--------Binary Classification
-Model: Gaussian Naive Bayes
- Performance Metrics:
- Confusion Matrix
- Classification Report
- Accuracy Score
- Cross-Validation:
Perform 10-fold cross-validation to evaluate model performance.

## Files in the Repository
- predictive_maintenance_classification.py: The main Python script with all the preprocessing, modeling, and evaluation steps.
- requirements.txt: Lists all the dependencies to run the script.
- predictive_maintenance.csv: The dataset used for this project.
## Results
--------Binary Classification
- The model achieved a significant accuracy in predicting whether maintenance is required.
- Evaluated using confusion matrix, classification report, and accuracy score.
- Cross-validation showed consistent performance across different folds.
--------Multi-Class Classification
- The model successfully classified different types of faults.
- Evaluated using confusion matrix, classification report, and accuracy score.
## Future Work
- Explore more complex models and architectures for improved performance.
- Implement additional feature engineering techniques.
- Integrate the models into a real-time maintenance prediction system.
## Contributions
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
