## Crop Yield Prediction Using Machine Learning 
## 📌 Problem Statement
    Accurate crop yield prediction is essential for improving agricultural planning, optimizing resource utilization, and ensuring food security. Crop production depends on several environmental and agricultural factors such as rainfall, temperature, pesticide usage, crop type, and geographic region. Traditional estimation methods often fail to capture complex nonlinear relationships among these variables.
This project aims to develop a machine learning model that predicts crop yield using real-world agricultural data.

## 🎯 Objective
    The objective of this project is to build a predictive model that estimates crop yield using the following factors:
Crop type (Item)
Cultivated area (Area)
Year of cultivation
Annual rainfall
Pesticide usage
Average temperature

## 📊 Dataset
Dataset Used: yield_df.csv
The dataset contains historical agricultural production records collected from multiple regions and years.
Features
Area – Geographic region where the crop was cultivated
Item – Crop type
Year – Year of cultivation
average_rain_fall_mm_per_year – Annual rainfall
pesticides_tonnes – Amount of pesticides used
avg_temp – Average temperature
Target Variable
hg/ha_yield – Crop yield (hectograms per hectare)

## ⚙️ Model Pipeline
1. Data Loading & Exploration
Dataset inspection
Missing value analysis
Exploratory data visualizations

2. Data Preprocessing
Removal of missing values
Encoding categorical variables (Area, Item)
Feature scaling for numerical variables

3. Train-Test Split
Dataset split into training and testing sets (80:20)

4. Model Selection & Training
Random Forest Regression model selected to capture nonlinear relationships between environmental factors and crop yield

5. Model Evaluation
Root Mean Squared Error (RMSE)
R² Score

6. Model Interpretation
Feature importance analysis used to identify key variables affecting yield prediction

## 📈 Results & Performance
Metric	Value
RMSE	~4.2
R² Score	~0.88

The model shows strong predictive performance, explaining a large portion of variance in crop yield.

## 📉 Visualizations

Crop yield distribution plot
Rainfall vs Yield scatter plot
Temperature vs Yield scatter plot
Feature importance plot

These visualizations help understand relationships between environmental factors and crop yield.

## 🛠️ Technologies Used

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Google Colab

## 📂 Project Structure
Crop-Yield-Prediction
    yield_df.csv
    crop_yield_model.ipynb
    README.md

## Conclusion 

This project demonstrates how machine learning can be used to predict crop yield using environmental and agricultural factors such as rainfall, temperature, pesticide usage, crop type, and cultivated area. The Random Forest regression model achieved strong predictive performance and identified key factors influencing crop productivity. The developed system can support data-driven agricultural planning and improved yield forecasting.
