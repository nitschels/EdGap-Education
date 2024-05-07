# EdGap-Education
EdGap data analysis project for DATA 3320

In this project, we will explore the disparities in education based on multiple columns using machine learning algorithms to analyze the data.

Source of data:
https://github.com/galenegan/DATA-3320/tree/main
Education Data Initiative: https://educationdata.org/public-education-spending-statistics

To get the training and test data, the data was first split into a test and training split, the test data being 20% of the data. It was then normalized and imputed to get rid of NaN values. 
Education Data Initiative data and EdGap data were joined based on State, looking at a local level would have taken data from multiple sources.


In the analysis section, I made plots with a regression line going through both the training and test data, with an RMSE value to see how accurate the regression line was. Beta values were found using NumPy linear algebra functions.
