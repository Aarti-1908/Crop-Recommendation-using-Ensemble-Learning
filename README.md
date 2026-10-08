# Crop-Recommendation-Using-Ensemble-Learning

# Project Overview

This project recommends the most suitable crop based on soil and environmental conditions using Machine Learning and Ensemble Learning techniques.

The project compares different classification models and combines them using a Soft Voting Ensemble to improve crop recommendation performance.

# Dataset

The dataset contains **1,000 records** and 8 columns:

##### N – Nitrogen content in soil

##### P – Phosphorus content in soil

##### K – Potassium content in soil

##### temperature – Temperature

##### humidity – Humidity

##### ph – Soil pH value

##### rainfall – Rainfall

##### label – Recommended crop (Target)

# Machine Learning Models

The following models are used:

##### Random Forest Classifier

##### Extra Trees Classifier

##### Gradient Boosting Classifier

##### Soft Voting Ensemble

# Technologies Used

Python,
Pandas,
NumPy,
Scikit-learn,
Matplotlib,
Seaborn,
Jupyter Notebook,
Joblib

# Evaluation Metrics

The models are evaluated using:

##### Accuracy – Measures the percentage of correct crop predictions.

##### Classification Report – Shows precision, recall, and F1-score for each crop.

##### Confusion Matrix – Shows the correct and incorrect predictions for each crop.

# Results

The performance of the different models is compared based on their prediction accuracy.

The **Soft Voting Ensemble** combines the predictions of Random Forest, Extra Trees, and Gradient Boosting to provide reliable crop recommendations.

Feature importance and confusion matrix visualizations are also generated to understand model performance.

# Conclusion

This project demonstrates how Machine Learning and Ensemble Learning techniques can be used to recommend suitable crops based on soil and environmental conditions.

The ensemble approach combines multiple models to improve the reliability of crop predictions.

# Future Scope

##### Use real-world agricultural datasets

##### Collect larger datasets from different regions

##### Apply hyperparameter tuning

##### Use advanced ensemble techniques

##### Add real-time weather and soil data

##### Develop a web or mobile application for crop recommendation
