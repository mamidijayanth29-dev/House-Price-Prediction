# 🏡 House Price Prediction (California Housing Dataset)

## 📌 Project Overview
This project is a machine learning regression model designed to predict the median value of houses in California based on various demographic and geographic features (such as income, number of rooms, and location). 

It demonstrates the foundational steps of handling tabular data, performing feature scaling, and training a regression algorithm to predict continuous numerical values.

## 🗄️ Dataset
- **Source:** California Housing Dataset (Built-in via `scikit-learn`)
- **Size:** 20,640 samples and 8 features.
- **Target Variable:** Median house value (measured in hundreds of thousands of dollars).

## ⚙️ Steps Completed
1. **Data Loading:** Imported the standard California Housing dataset.
2. **Preprocessing:** Checked for missing data and normalized the numerical features using `StandardScaler` to ensure large values (like population) didn't overwhelm smaller values (like bedrooms).
3. **Data Splitting:** Divided the dataset into training (80%) and testing (20%) sets.
4. **Model Training:** Built and trained a **Linear Regression** model.
5. **Evaluation:** Tested the model's accuracy using standard regression metrics and ran a custom prediction test.

## 📊 Model Evaluation
The Linear Regression model was evaluated on the testing set with the following results:
- **Mean Squared Error (MSE):** `0.56`
- **R-squared (R2) Score:** `57.58%`

*(Note: Real estate pricing is influenced by highly complex, real-world factors. An R2 score of ~58% is the standard, expected baseline for a simple Linear Regression model on this dataset, proving the mathematical pipeline is functioning perfectly.)*

## 🚀 How to Run the Code
The code is written in Python and can be run in Jupyter Notebook or Google Colab. 

1. Clone this repository to your local machine.
2. Open the `.ipynb` file in Google Colab or your preferred Python environment.
3. Run the cells sequentially to download the data, train the model, and see the predictions.
