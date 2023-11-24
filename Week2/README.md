## Solution to Assignment 2
- Used `pandas.read_csv()` to get the data from CSV files.  
- In the *startups.csv*, one-hot encoded *State* column.  
- Used Numpy to create arrays of features and label for both data
- Split the data using `sklearn.model_selection.train_test_split()`
- Created two LinearRegression objects, trained the model on training data, calculated scores
- Used `matplotlib.pyplot.plot()` to plot predicted salary and actual salaries with years of experience of the testing data.
- Proceeded to calculate the sum of squared residuals and R2 score.
