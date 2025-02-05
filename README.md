# Hotel-Booking-Cancellation-Assistant

The Hotel Booking Cancellation Assistant is a powerful AI-powered tool that predicts the probability of a hotel booking being canceled based on historical data. It allows users to interact with booking data through natural language queries and receive real-time insights.

How Does It Work?

 Data Processing & Model Training
Loads historical hotel booking data (booking.csv).
Cleans and prepares the data by:
Removing unnecessary columns (e.g., date of reservation).
Converting categorical features into machine-readable format.
Handling missing values.
Uses XGBoost (Extreme Gradient Boosting):
Splits data into training (80%) and testing (20%).
Trains a machine learning model to predict whether a booking will be canceled.
Optimizes the model using Optuna (an automated hyperparameter tuning library).

![image alt](https://github.com/boprosv/Hotel-Booking-Cancellation-Assistant/blob/main/Screenshot%202025-02-05%20123408.png?raw=true)
Here is the glimps of the Data:

