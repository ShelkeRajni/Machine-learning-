# Machine-learning-
# Electricity Bill Prediction Simple Linear Regression

### Predicting Monthly Electricity Costs Based on Average Temperature

This project explores the relationship between climate and utility costs. By using a custom built dataset of 36 months of data, I built a Simple Linear Regression model to predict a household monthly electricity bill in Indian Rupees based on the average daily temperature for that month[cite: 1].

## Project Objective
The main goal was to verify the intuitive assumption that hotter months lead to higher electricity bills due to increased AC usage[cite: 1]. I walked through the full data science pipeline:
1. Data Generation: Creating a realistic dataset with random noise[cite: 1].
2. Exploratory Data Analysis: Visualizing distributions and correlations[cite: 1].
3. Model Building: Training a Scikit-Learn LinearRegression model[cite: 1].
4. Evaluation: Assessing performance using MAE, RMSE, and R squared scores[cite: 1].

## The Dataset
The data represents a single household in a warm city over a 3 year period from 2022 to 2024[cite: 1].
- Feature X: Average Daily Temperature in Celsius[cite: 1].
- Target y: Monthly Electricity Bill in Indian Rupees[cite: 1].
- Size: 36 records[cite: 1].

Key Finding from EDA: 
A strong positive correlation of approximately 0.96 exists between temperature and the bill amount[cite: 1].

## Tech Stack
- Language: Python
- Libraries:
    - Pandas for data manipulation[cite: 1].
    - NumPy for numerical operations[cite: 1].
    - Matplotlib and Seaborn for data visualization[cite: 1].
    - Scikit-Learn for model training and evaluation[cite: 1].

## Model Performance
The model was trained on 80 percent of the data and tested on the remaining 20 percent[cite: 1].

Result Metrics:
- R squared Score: Approximately 90.1 percent. The model explains 90 percent of the variance[cite: 1].
- MAE: 78.65 Indian Rupees[cite: 1].
- RMSE: 89.52 Indian Rupees[cite: 1].

Regression Equation:
Based on the trained parameters[cite: 1]:
Electricity Bill is approximately 31.20 multiplied by Temperature minus 320.40.

## Visualizations
The project includes:
- Histograms to check the frequency of temperatures and bill amounts[cite: 1].
- Scatter Plot showing the raw relationship between variables[cite: 1].
- Regression Line Plot illustrating how well the model fits both training and test data[cite: 1].
- Residual Analysis confirming that prediction errors are randomly distributed[cite: 1].

## How to Run
1. Clone the repository:
   git clone (https://github.com/ShelkeRajni/Machine-learning-)
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Run the simple_linear_regression (1).ipynb notebook or Python script to see the analysis and plots[cite: 1].

## Conclusion
The model successfully identifies a linear trend where every 1 degree Celsius increase in temperature roughly adds 31 Indian Rupees to the monthly bill[cite: 1]. While this simple model performs exceptionally well, future improvements could include features like the number of holidays in a month or peak hour pricing rates[cite: 1].
