House Price Prediction using Linear Regression
Faculty Submission Details
  Particulars                         Details
  Student Name                        Sanskar Santosh Randive

  College Name                        Zeal College of Engineering, Narhe, Pune

  Department / Branch                 Artificial Intelligence and Data Science (AI&DS)

  Class                               Third Year B.Tech

  Subject Name                        RCA

  Practical / Activity No.            RCA Activity 1

1. Project Title
House Price Prediction using Simple and Multiple Linear Regression
2. Aim
To develop and evaluate Simple Linear Regression and Multiple Linear
Regression models for predicting house prices using housing dataset
features.
3. Objectives
- Load and understand the housing dataset.
- Inspect dataset information, descriptive statistics, missing values,
  and duplicate records.
- Clean the data by removing duplicate rows and rows with missing
  values in the selected columns.
- Explore relationships between housing features and price using
  visualizations and correlation.
- Understand the manual calculation of multiple linear regression
  coefficients.
- Build Simple Linear Regression and Multiple Linear Regression
  models.
- Predict house prices and compare model performance using regression
  metrics.
- Analyze residuals and multicollinearity using VIF.
4. Dataset Information
- Dataset file: Housing.csv
- Target variable: price
- Input features:
  - area
  - bedrooms
  - bathrooms
  - stories
  - parking
The notebook loads the dataset using pd.read_csv("Housing.csv"). Keep
Housing.csv in the same working directory as the notebook, or update
the file path in the first code cell.
5. Tools and Libraries Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
6. Methodology / Steps Performed
1. Import the required Python libraries.
2. Load Housing.csv and display the dataset shape and first few
   records.
3. Inspect data types, descriptive statistics, missing values, and
   duplicate rows.
4. Remove duplicate records and rows with missing values in the
   selected input features or target.
5. Select area, bedrooms, bathrooms, stories, and parking as
   input features (X), and price as the target (y).
6. Plot each selected feature against house price and create a
   correlation heatmap.
7. Demonstrate manual multiple linear regression coefficient
   calculation using a six-row sample with area and bedrooms, using
   the normal equation.
8. Split the dataset into 80% training data and 20% testing data using
   random_state=42.
9. Train a Simple Linear Regression model using area and a Multiple
   Linear Regression model using all five selected features.
10. Display model intercepts, coefficients, and the multiple regression
    equation.
11. Standardize the training features and display the coefficients from
    a regression model trained on the scaled features.
12. Predict house prices for the test dataset and display actual values,
    predicted values, and residuals.
13. Compare the models using MAE, MSE, RMSE, R², and Adjusted R².
14. Visualize residuals, residual distribution, and actual versus
    predicted prices.
15. Calculate Variance Inflation Factor (VIF) for the input features.
16. Predict the price of a sample house using the median values of the
    training features.
7. Regression Evaluation Metrics
  Metric                              Meaning
  MAE                                 Mean Absolute Error; average
absolute difference between actual
and predicted values

  MSE                                 Mean Squared Error; average squared
prediction error

  RMSE                                Root Mean Squared Error; square
root of MSE

  R² Score                            Measures how much variation in the
target is explained by the model
Adjusted R²                         R² adjusted according to the number
of input features and observations
Lower MAE, MSE, and RMSE generally indicate smaller prediction errors.
Higher R² and Adjusted R² generally indicate a better fit.
8. Visualizations and Analysis
The notebook includes: - Scatter plots of each selected feature against
house price - Correlation heatmap - Residual plot - Residual histogram -
Actual versus predicted price plot - Training-feature correlation matrix

It also calculates VIF values to help examine multicollinearity among
the input features.
9. How to Run the Notebook
1. Open ActivityRCA1.ipynb in Google Colab or Jupyter Notebook.
2. Upload Housing.csv to the notebook environment.
3. Make sure the CSV file path in the first cell is correct.
4. Run all cells in order, from top to bottom.
5. Review the displayed dataset information, coefficients, predictions,
   evaluation metrics, and plots.
10. Expected Outcome
The notebook trains Simple Linear Regression and Multiple Linear
Regression models to estimate house prices. It compares their
performance using regression evaluation metrics and visual analysis. The
actual metric values and prediction results are generated when the
notebook is executed.
11. Files Required
- ActivityRCA1.ipynb -- Notebook containing the complete
  implementation.
- Housing.csv -- Dataset required to run the notebook.
- README.md -- Project details and faculty submission information.
12. Conclusion
Simple and Multiple Linear Regression models were implemented using the
housing dataset to predict house prices. The data was inspected and
cleaned, selected features were explored using visualizations, and the
models were trained and evaluated using MAE, MSE, RMSE, R², and Adjusted
R². Residual analysis and VIF were also used to examine model errors and
multicollinearity.
Submitted by: Sanskar Santosh Randive
Branch: Artificial Intelligence and Data Science (AI&DS)
College: Zeal College of Engineering, Narhe, Pune
