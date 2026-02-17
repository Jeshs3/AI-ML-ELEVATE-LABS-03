# AI-ML-ELEVATE-LABS-03

# House Price Prediction 

This project builds a Linear Regression model to predict house prices based on various property features such as area, bedrooms, bathrooms, parking, and furnishing status.

The objective is to understand:

1. How different features influence house prices

2. How well a linear model can approximate real-world pricing

3. How to evaluate regression performance using standard metrics

# Dataset
Target: price
Input features: 
1. area
2. bedrooms
3. bathrooms
4. stories
5. mainroad
6. guestroom
7. basement
8. hotwaterheating
9. airconditioning
10. parking
11. prefarea
12. furnishingstatus

#Tasks Performed
a. Data Import & Preprocessing
b. Train-Test Split
c. Model Training using Linear regression
d. Model Evaluation
  - MAE, MSE, R^2

# Model Evaluation
Mean Absolute Error: 29.2283
Mean Squared Error: 1304.4085
R-squared: 0.6793

*Evaluation*
🔹 Mean Absolute Error (29.23)
On average, predictions are off by about 29 units from the actual price.
This gives a practical sense of the average prediction error.

🔹 Mean Squared Error (1304.41)
Errors are squared before averaging, which penalizes large mistakes more heavily.
This indicates some moderate outliers in predictions.

🔹 R-squared (0.6793)
The model explains 67.93% of the variance in house prices.
This means:
- The model captures major pricing patterns
- Around 32% of variability remains unexplained
- The model has moderate predictive strength

# Regression Line
*Performance is acceptable for a baseline regression model*
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/46126773-f76e-42e6-a186-49aca65f0e90" />



