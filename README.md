# Grocery Item Rating Prediction

## Overview
This project aims to predict the **customer rating** of grocery items using **machine learning** techniques. The dataset, sourced from Kaggle, contains various features of grocery items such as **sub-category, price, discount, title, currency, features, and product description**. The target variable is the **rating** (on a scale of 1 to 5), which reflects customer satisfaction and product quality.

## Dataset
The dataset consists of the following features:
- **Sub Category**: Categorizes grocery items.
- **Price**: The cost of the grocery item.
- **Discount**: Any applicable discounts or promotions.
- **Title**: Name of the grocery item.
- **Currency**: The currency of the price.
- **Feature**: Specific characteristics of the item.
- **Product Description**: A textual description of the item.
- **Rating (Target Variable)**: Customer ratings (scale of 1 to 5).

## Tasks Completed
1. **Exploratory Data Analysis (EDA)**
   - Data visualization using **matplotlib** and **seaborn**.
   - Distribution analysis of price, discount, and ratings.
   - Checking missing values and outliers.

2. **Data Preprocessing**
   - Handling missing values.
   - Encoding categorical variables.
   - Feature engineering to extract useful insights.
   - Standardizing numerical features.

3. **Feature Exploration**
   - Identified key factors influencing customer ratings.
   - Explored the correlation between price, discount, and rating.
   - Applied NLP techniques to analyze the impact of product descriptions.

4. **Model Selection & Training**
   - Used **Random Forest Regressor** for predicting customer ratings.
   - Performed **hyperparameter tuning** using GridSearchCV.
   - Split the data into **training (80%) and testing (20%)** sets.

5. **Model Evaluation**
   - Evaluated the model using **Mean Absolute Error (MAE)** and **R² Score**.
   - Compared performance with other models like **Linear Regression** and **Decision Tree Regressor**.

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data manipulation)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-Learn** (Machine learning)


## Results
- The **Random Forest Regressor** provided a good balance of **accuracy and interpretability**.
- **Key insights**: Price, discount, and product descriptions significantly impact customer ratings.
- The model achieved a **Mean Absolute Error (MAE) of X.XX** and an **R² Score of X.XX**.

## Future Improvements
- Implement **deep learning models** for improved text feature extraction.
- Fine-tune hyperparameters further to boost performance.

## Author
- Siya Simon

