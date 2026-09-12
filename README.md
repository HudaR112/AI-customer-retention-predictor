**AI Customer Retention Predictor** 
# Customer Retention & Repeat Purchase Prediction

A machine learning project focused on analyzing customer purchasing behavior and predicting whether a customer is likely to make a repeat purchase within the next 30 days.

### What We Did

* Performed exploratory data analysis (EDA) on the Online Retail transactional dataset.
* Cleaned the data by handling missing `CustomerID` values and removing cancellation/return-type transactions.
* Transformed transaction-level data into customer-level behavioral data.
* Applied feature engineering using customer purchasing patterns, including:

  * Recency
  * Frequency
  * Monetary Value
  * Unique Products
  * Average Order Value
  * Unique Purchase Days
  * Customer Lifespan
  * Orders in Last 30 Days
* Created a 30-day repeat-purchase target variable.
* Split the data into training and testing sets using stratified sampling.
* Standardized numerical features using `StandardScaler`.
* Built a Logistic Regression model as the baseline classification model.
* Evaluated the model using Accuracy, Precision, Recall, F1 Score, and a Confusion Matrix.
* Compared the baseline model with a Random Forest model.



