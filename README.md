# Food Delivery Time Prediction

## Project Overview
This project predicts the **estimated delivery time (in minutes)** for food orders using machine learning.  
The model uses delivery partner details, order characteristics, and geographic information to estimate delivery time before the order is delivered.

Accurate delivery time prediction helps improve **customer satisfaction**, **delivery planning**, and **operational efficiency** for food delivery platforms.

---

## Problem Statement
Given order and delivery-related attributes, predict how long a food order will take to reach the customer.

This is a **supervised regression problem**, where the target variable is delivery time.

---

## Dataset Description
The dataset consists of structured tabular data with the following types of features:
- Delivery partner age and ratings  
- Restaurant and customer latitude and longitude  
- Order type and vehicle type  
- Actual delivery time (target variable)

---

## Project Workflow
1. **Data Exploration**
   - Understanding feature distributions and data types  
   - Identifying relevant attributes for prediction  

2. **Data Cleaning**
   - Handling missing values  
   - Removing or correcting inconsistent data  

3. **Feature Engineering**
   - Encoding categorical variables  
   - Preparing numerical features for model training  

4. **Model Building**
   - Splitting data into training and testing sets  
   - Training regression models to predict delivery time  

5. **Model Evaluation**
   - Comparing predicted and actual delivery times  
   - Evaluating model performance using error-based metrics  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## Results
The trained model predicts food delivery time with reasonable accuracy based on delivery partner details, order information, and location data.  
This can be used to provide realistic delivery estimates to customers.

---

## How to Run the Project
1. Clone the repository  
2. Open the Jupyter Notebook  
3. Install the required dependencies  
4. Run the notebook cells sequentially  

---

## Use Cases
- Real-time food delivery time estimation  
- Logistics and delivery planning  
- Improving customer experience on food delivery platforms  

---

## Future Enhancements
- Distance calculation using the Haversine formula  
- Using advanced models like Random Forest or XGBoost  
- Hyperparameter tuning for better accuracy  
- Deploying the model as an API  

---

## Author
**Kishan Chandaluri**
