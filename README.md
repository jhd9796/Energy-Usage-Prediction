# Energy Usage Prediction

This project, developed by Hyeondeok Cho, focuses on predicting daily energy usage based on weather conditions. Utilizing Python with libraries such as Pandas, NumPy, Scikit-learn, Seaborn, and Matplotlib, it showcases the power of machine learning in interpreting and forecasting energy consumption patterns.

## Overview

The objective was to merge energy usage data with weather conditions to predict the energy usage of a household. The analysis involved data cleaning, feature engineering, and merging datasets for a comprehensive analysis. Predictive modeling was then applied to forecast daily energy usage.

## Data

The dataset comprises two main components:
- **Energy Data**: Detailed electricity usage in kW.
- **Weather Data**: Weather conditions including temperature, humidity, visibility, and more.

## Methodology

1. **Data Preprocessing**: Time fields parsing, summing daily energy usage, and merging with weather data.
2. **Exploratory Data Analysis**: Identifying patterns, correlations, and insights from the combined dataset.
3. **Predictive Modeling**:
   - **Linear Regression**: For predicting daily energy usage based on weather data.
   - **Logistic Regression**: For classifying days as having high or low temperatures.
4. **Results Evaluation**: Utilizing metrics like RMSE and F1-score to assess model performance.
5. **Device Usage Analysis**: Investigating the usage patterns of appliances like AC and washers, categorized into day and night usage.

## Results

The linear regression model provided insights into energy usage patterns, though with a notable root mean squared error indicating room for model improvement. The logistic regression model successfully classified temperature with a decent F1-score, highlighting its effectiveness in temperature-based classification.

Device usage analysis revealed:
- AC usage is significantly higher during the night, contrary to initial assumptions.
- The washer is predominantly used during the day, with minimal usage at night.

## Conclusion

This project illuminates the intricate relationship between weather conditions and household energy usage. While predictive models offer valuable forecasts, further refinement and additional data could enhance accuracy and insights.
