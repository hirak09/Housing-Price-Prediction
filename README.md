# Housing Price Prediction using Linear Regression 
This project predicts house prices based on various features like area, number of bedrooms, bathrooms, location, furnishing status, etc.
It uses Linear Regression (a supervised machine learning algorithm) to model the relationship between house features and their prices.

# Features 
1.Clean and well-structured Jupyter Notebook
2.Data preprocessing (handling categorical variables with one-hot encoding)
3.Train/test split for fair model evaluation
4.Linear Regression model for price prediction
5.Model evaluation using:
  a.Mean Squared Error (MSE)
  b.R² Score
  c.Custom Accuracy (within ±10% of actual price)
6.Visualization of Actual vs Predicted Prices
7.Interactive: Predict price for a new custom house

# Tech Stack
1.Python 3
2.Pandas → data manipulation
3.NumPy → numerical computations
4.Matplotlib & Seaborn → data visualization
5.Scikit-learn → machine learning (Linear Regression, train/test split, evaluation metrics)

# Project Workflow
1.Import required libraries
2.Load dataset (housing.csv)
3.Explore dataset (shape, info, head)
4.Encode categorical variables (One-Hot Encoding)
5.Split features and target (X, y)
6.Train/test split (80% train, 20% test)
7.Train Linear Regression model
8.Evaluate performance (MSE, R², Custom Accuracy)
9.Visualize results (Actual vs Predicted Prices)
10.Predict price for a new house

# How to Run
1.Clone this repository:
git clone https://github.com/your-username/housing-price-prediction.git
cd housing-price-prediction
2.Install dependencies:
pip install -r requirements.txt
3.Run the Jupyter Notebook:
jupyter notebook
4.Open housing_price_prediction.ipynb and run all cells.

# Example Output: 
a.Model Evaluation:
Mean Squared Error (MSE): 1.23e+06
R² Score: 0.85
Custom Accuracy (±10%): 78.4%

b.Visualization:
A scatter plot showing actual vs predicted house prices with a perfect prediction line.

c.Prediction Example:
Predicted Price for this New House: 4,500,000
