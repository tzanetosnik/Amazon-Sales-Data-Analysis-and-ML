# Amazon Sales Analysis & Price Prediction 📊🛒

This project performs a comprehensive Exploratory Data Analysis (EDA) and builds a Machine Learning model to predict discounted prices of products listed on Amazon. The analysis is performed using Python on Google Colab.

## 🚀 Project Overview
The goal of this project is to understand the pricing strategies on Amazon and develop a predictive model that estimates the `discounted_price` based on the product's original price and user ratings.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Environment:** Google Colab
- **Libraries:** - `Pandas`: Data manipulation and cleaning
  - `NumPy`: Numerical operations
  - `Matplotlib` & `Seaborn`: Data visualization
  - `Scikit-Learn`: Machine Learning modeling

## 📊 Dataset Description
The dataset contains information on various products from Amazon, including:
- **Product Details:** Name, Category, and Description.
- **Pricing:** Actual Price, Discounted Price, and Discount Percentage.
- **Customer Feedback:** Ratings and Rating Counts.

## 🧹 Key Data Processing Steps
1. **Currency Cleaning:** Stripped currency symbols (₹) and commas from price columns to convert them into float format.
2. **Type Conversion:** Converted percentages and rating strings into numerical values for analysis.
3. **Handling Missing Values:** Identified and managed null values to ensure model stability.
4. **Feature Selection:** Selected `actual_price` and `rating` as key predictors for the regression model.

## 📈 Machine Learning Model
I implemented a **Linear Regression** model to predict the final discounted price.
- **Training/Test Split:** 80/20 ratio.
- **Evaluation Metrics:** Used R-squared ($R^2$) and Mean Squared Error (MSE) to validate the model's accuracy.

## 💡 Key Insights
- There is a strong linear correlation between the actual price and the discounted price.
- Higher-rated products tend to maintain more stable pricing with specific discount patterns.
- The model demonstrates high predictive power, explaining a significant portion of the price variance.

## 💻 How to Run
1. Clone this repository.
2. Upload the `amazon.csv` file to your Google Colab environment.
3. Open the `.ipynb` notebook and run the cells sequentially.

---
**Author:** Nikos Tzanetos/Tzanetosnik
**Project Date:** March 2026
