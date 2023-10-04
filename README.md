# uber_project
The Uber Safety Score Predictor: A data-driven model that analyzes and predicts driver safety scores in real-time based on their driving behaviors, aiming to enhance road safety and improve the Uber experience for both drivers and passengers.

# Enhancing Driver Safety Through Behavior Analysis

This project aims to predict and enhance driver safety scores based on their driving behaviors for Uber. By analyzing various driving behaviors and patterns, I have developed a model to assign a safety score to drivers which can be used for various proactive measures.

## Files in the Repository:

1. **mock_driver_data.csv**: This CSV file contains mock data that mimics real-time driver monitoring data from Uber. The dataset includes various parameters like hard brakes, sharp turns, time exceeded speed limit, time spent in high-risk zones, and the use of indicators.

2. **Uber_Project.ipynb**: This Jupyter notebook contains all the Python code, ranging from data preprocessing, exploratory data analysis, feature engineering, modeling, and evaluation.

## Project Structure:

- **Data Collection**: The mock data for the project is collected from Uber's real-time driver monitoring system.

- **Data Processing & Exploratory Data Analysis**: Analyzed the distributions of different driving behaviors and established a scoring system for drivers.

- **Modeling**: Utilized a linear regression model to predict the safety score of drivers based on their behaviors. 

- **Evaluation**: The model's efficiency was gauged using metrics like R-squared values. Further insights were drawn by interpreting model coefficients.

- **Recommendations**: Based on the insights and model evaluations, future recommendations were proposed to further enhance driver safety and improve the prediction model.

## How to Run:

1. Ensure you have Jupyter Notebook installed, along with Python libraries such as pandas, numpy, sklearn, and matplotlib/seaborn.
   
2. Clone this repository to your local machine.
   
3. Open the `Uber_Project.ipynb` file in Jupyter Notebook.
   
4. Execute the cells in sequence from top to bottom to see the complete analysis and results.

## Conclusion:

Through this project, we have successfully developed a model that can predict a driver's safety score with high accuracy. This model, combined with the insights from the data, can significantly help in making the roads safer for both drivers and passengers by identifying and mitigating unsafe driving behaviors.


Remember to adjust paths, prerequisites, or any other specifics that you might have in your setup that aren't covered here!
