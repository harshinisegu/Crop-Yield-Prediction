# Crop-Yield-Prediction
Crop Yield Prediction using Machine Learning
# Project Overview:
    This project focuses on building a machine learning model to predict crop yield using environmental and agricultural factors. Accurate crop yield prediction helps farmers and policymakers make informed decisions related to crop planning, resource allocation, and production forecasting.
# Dataset
  The dataset contains historical agricultural records with the following features:
Area
Crop Type
Year
Average Rainfall
Pesticides Usage
Average Temperature
Crop Yield (Target Variable)
# Methodology
The project follows a complete machine learning pipeline:
1.Data preprocessing
    Handling missing values
    Encoding categorical variables
    Feature scaling

2.Model training
    Random Forest Regression model used for prediction

3.Model evaluation
    Root Mean Square Error (RMSE)
    R² Score

4.Model interpretation
    Feature importance analysis used to understand key factors affecting crop yield

# Results

The trained model successfully predicts crop yield with strong performance. Feature importance analysis shows that rainfall, temperature, and pesticide usage are among the most influential variables affecting crop productivity.

# Project Structure
    Crop-Yield-Prediction
        yield_df.csv
        crop_yield_model.ipynb
        README.md

# Technologies Used
Python
Pandas
Scikit-learn
Matplotlib
Google Colab 

# Conclusion
    This project demonstrates how machine learning can be applied to real-world agricultural datasets to generate predictive insights that support data-driven decision-making.
