# Calories Burned Prediction Project

Description
This project uses machine learning to predict the number of calories burned based on various features such as age, height, weight, heart rate, and more. We use regression models to predict the calories burned from workout data.

Project Overview
The main steps in this project include:
1. Data Loading: Importing the dataset containing features like age, height, weight, heart rate, etc.
2. Data Preprocessing: Cleaning the data by handling missing values and scaling numerical features.
3. Model Training: Training a machine learning regression model (Random Forest Regressor) on the data.
4. Model Evaluation: Evaluating the model’s performance using metrics like Mean Squared Error (MSE) and R-squared.
5. Feature Importance: Analyzing which features have the greatest impact on the predicted calories burned.

Dataset
The dataset contains the following columns:
- User_ID: Unique identifier for each user.
- Gender: Gender of the individual (encoded as 0 for male, 1 for female).
- Age: Age of the individual.
- Height: Height of the individual in cm.
- Weight: Weight of the individual in kg.
- Duration: Duration of the workout in minutes.
- Heart_Rate: Heart rate during the workout.
- Body_Temp: Body temperature during the workout.
- Calories: Actual calories burned during the workout (target variable).

Installation
To run this project locally, follow these steps:

Clone the repository:
   ```bash
   git clone https://github.com/biruk34/calories-burned-prediction.git

Results
After training the Random Forest Regressor model, the following performance metrics were evaluated:

Mean Squared Error (MSE): 131.99
(Lower MSE indicates a better fit of the model to the data.)

R-squared: 0.967
(The R-squared value indicates that approximately 96.7% of the variance in the target variable (Calories burned) is explained by the features.)

Additionally, I conducted an analysis of feature importance, where the top features affecting the model's predictions were identified:
Top Feature: Duration of the workout (most important feature)
Other Important Features: Heart rate, Age, Weight, etc.

Conclusion
This project demonstrates the use of machine learning techniques, specifically Random Forest regression, to predict the number of calories burned during a workout based on various personal and workout features. The model performed well with a high R-squared value, indicating strong predictive power.
