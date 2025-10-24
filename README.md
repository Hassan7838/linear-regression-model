# linear-regression-model
"Predictive Modeling: Linear Regression for Continuous Target Variable"

This project demonstrates the **development, training, and evaluation of a Linear Regression model** for predicting a continuous target variable using a benchmark regression dataset (e.g., Boston Housing dataset or a similar alternative).  

It was developed as part of my **Machine Learning internship** to strengthen my understanding of regression modeling, model evaluation metrics, and visualization of predictive performance.

# Project Goals

To build and evaluate a **Linear Regression model** that:
- Predicts a continuous target variable.
- Calculates key performance metrics (RMSE, MAE, R²).
- Visualizes the relationship between actual and predicted values.

# Project Workflow

### 1. Dataset Acquisition and Preparation
- Loaded a benchmark regression dataset (Boston Housing or comparable alternative).
- Performed data inspection and cleaning for model readiness.

### 2. Data Splitting
- Split dataset into **80% training** and **20% testing** sets using `train_test_split()`.

### 3. Model Training and Evaluation
- Trained a **Linear Regression** model using `LinearRegression()` from Scikit-learn.  
- Generated predictions on the test set.  
- Evaluated the model using:
  - **Root Mean Squared Error (RMSE)**
  - **Mean Absolute Error (MAE)**
  - **R-squared (R²)**

### 4. Results Visualization
- Created a scatter plot comparing **actual vs. predicted values**.
- Included a reference line (*y = x*) to visualize prediction accuracy.

# Tools and Libraries
- **Python 3.x**
- **NumPy** – for numerical operations  
- **Pandas** – for data handling  
- **Scikit-learn** – for model building and evaluation  
- **Matplotlib / Seaborn** – for visualization  

# How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/linear-regression-model.git
