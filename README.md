# Predicting Power Plant Energy Output
## Project Overview
This project involves building a machine learning model to predict the energy output of a power plant based on various environmental factors. The dataset used for this project contains multiple environmental variables that influence power output, such as **Ambient Temperature (AT)**, **Exhaust Vacuum (V), Ambient Pressure (AP),** and **Relative Humidity (RH)**. Various regression models are applied to predict the **Power Output (PE)**, and the results are evaluated and visualized.

## Table of Contents
+ Project Overview
+ Dataset Information
+ Regression Models
+ Feature Scaling
+ Evaluation Metrics
+ Results and Insights
+ Data Visualization
+ Installation
+ Contributing

## Dataset Information
The dataset contains the following features:

+ **AT - Ambient Temperature (°C)**
+ **V - Exhaust Vacuum (cm Hg)**
+ **AP - Ambient Pressure (millibar)**
+ **RH - Relative Humidity (%)**
+ **PE - Net Hourly Electrical Energy Output (MW)**

The target variable is _PE (Power Output)_, which we aim to predict using various regression models.

## Regression Models
The following regression models were implemented:

+ **Linear Regression:** A simple baseline model.
+ **Support Vector Regression (SVR):** Used to capture complex relationships.
+ **Decision Tree Regression:** Applied for non-linear data splitting.
+ **Random Forest Regression:** An ensemble model that averages multiple decision trees.

## Feature Scaling

Feature scaling was applied using StandardScaler to normalize features. This step is crucial for regression models like SVR and Polynomial Regression, where the model performance can improve significantly after scaling.

## Evaluation Metrics
The models were evaluated using the following metrics:

+ R-squared (R²)

These metric helped evaluate how well the models fit the data and their prediction accuracy.

## Results and Insights
After training and testing the models, the Random Forest Regression model performed the best with highest accuracy. Here are some key results:

+ Random Forest Regression had an R² of **0.963**.
+ Support Vector Regression performed well but required significant computational resources.

## Visualization Insights
Several visualizations were created to interpret the model performance and data:

+ **Line Chart:** Comparing the actual vs. predicted power output.

![image](https://github.com/user-attachments/assets/2162e61a-65f6-4467-8375-55788684a730)

![image](https://github.com/user-attachments/assets/e3b5bbff-e660-4139-be8d-44b92e8e214f)

+ **Scatter Plot:** Visualizing the correlation between actual and predicted values.

![image](https://github.com/user-attachments/assets/5f42b5bc-2e7e-461b-9176-ff4ae46276bd)

![image](https://github.com/user-attachments/assets/915a1887-6c45-4cc9-9353-9e6f7e65fc85)


These visualizations were created using **Tableau**, providing an interactive way to explore the relationships between variables and the model’s predictions.

## Data Visualization
The predicted results and actual values were exported into a CSV file and visualized using Tableau. The following visualizations were created:

Line Chart: Actual vs. predicted power output.
Scatter Plot: Visual comparison of actual vs. predicted values.

You can access the Tableau visualizations or replicate them using your own dataset.

## Installation
**Requirements**

The project was implemented in Python with the following libraries:

+ numpy
+ pandas
+ scikit-learn
+ matplotlib
+ Tableau for visualizations


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.
