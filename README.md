# Linear-regression

This is a Python class called AnalysisDataAndFitLinearRegression which has a method called analyse_and_fit_lrm that performs data analysis and linear regression on a real estate dataset. The dataset is loaded from a CSV file specified by the path path.

The method performs the following tasks:

    Reads in the CSV file into a Pandas DataFrame.
    Selects data where the number of bathrooms is equal to 2 and the number of bedrooms is equal to 4.
    Calculates summary statistics (mean, standard deviation, median, minimum, maximum) for the 'Tax' column.
    Selects data where the space is greater than 800 square feet and sorts by price in descending order.
    Selects data where the lot size is greater than or equal to the median lot size.
    Drops any rows with missing values.
    Fits a linear regression model using the remaining columns as predictors and the 'Price' column as the target variable.
    Predicts the price for a new observation with the predictor values [3,1500,8,40,1000,2,1,0].
    Returns a dictionary containing two keys, 'summary_dict' and 'regression_dict', which contain the summary statistics, data frame, number of observations, model parameters, and predicted price.

The class has two attributes: version and path, which is the path to the real estate dataset CSV file.
