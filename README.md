# Airfare Price Prediction
## Overview
The **Airfare Price Prediction** project focuses on predicting airline ticket prices using machine learning. By analyzing factors such as airline type, departure time, arrival time, flight duration, and more, the goal is to estimate airfare for various flights. This can help travelers find the best times to book flights, and assist airlines in optimizing their pricing strategies based on market trends.

## Key Components
### 1. Data Collection
Data was sourced from online travel portals, flight APIs, or publicly available datasets, and includes:
- **Airline Name**
- **Flight Number**
- **Source and Destination Cities**
- **Date of Travel**
- **Departure and Arrival Times**
- **Flight Duration**
- **Ticket Price**

### 2. Data Preprocessing
Steps were taken to clean and prepare the data:
- Handling missing data and outliers
- Converting date and time fields into useful features (e.g., extracting the month, day of the week)
- Encoding categorical variables (e.g., airline names and cities)

### 3. Feature Engineering
New features were created to improve model performance:
- Travel duration
- Departure time buckets (morning, afternoon, evening)
- Layover and stop counts

### 4. Model Building
Multiple models were trained and tested, including:
- **Linear Regression**
- **Random Forest**
- **XGBoost**

After experimentation, **Random Forest** provided the best performance in terms of accuracy and error metrics. Hyperparameter tuning and cross-validation were applied to improve the model's robustness.

### 5. Evaluation and Prediction
The **Random Forest** model was evaluated using:
- **RMSE (Root Mean Squared Error)**
- **R² Score**

The Random Forest model outperformed others, making it the best choice for predicting airfare prices.

## Conclusion
This project demonstrates how machine learning, particularly using the **Random Forest** model, can be applied to predict airline ticket prices. The insights can help travelers make more informed booking decisions, and allow airlines to adjust pricing strategies based on predicted trends.
