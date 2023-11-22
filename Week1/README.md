## Solution to Assignment 1
Used csv.reader() store data from the data.csv file in the form of a list of records.  
Then asked the user to input what field do they want to plot against price.  
I then used matplotlib.pyplot.plot() to plot the field with price (blue dots), and used scipy.stats.linregress() to find the slope, intercept, r value, p value & standard deviation of the data.  
Next, I used matplotlib.pyplot.plot() to plot a line with the calculated slope and intercept. Finally asked user for a value for the inputted field, to predict the price using the line plotted.  
