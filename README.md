# Iris-Flower-Data-Set
This repository contains solutions to the [jupyter, pyplot and numpy problem sheet](https://emerging-technologies.github.io/problems/jupyter.html) completed as part of my course work for the module [Emerging Technologies](https://emerging-technologies.github.io/). The data set used for this problem sheet is [Fisher's Iris data set](https://en.wikipedia.org/wiki/Iris_flower_data_set).
The module is taught to undergraduate students at [GMIT](http://www.gmit.ie/) in the Department of Computer Science and Applied Physics for the course [B.S.c. (Hons) in Software Developement.](https://www.gmit.ie/software-development/bachelor-science-honours-software-development) The lecturer is  [Dr. Ian McLoughlin](https://ianmcloughlin.github.io/).

## Exercises:
## 01. Get and load the data
Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also. Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.
## 02. Write a note about the data set
In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.
## 03. Create a simple plot
The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis. Add axis labels and a title to the plot.
## 04. Create a more complex plot
Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue. Setosa, versicolor, and virginica are the three possible values of the species variable. Add a legend to the plot showing which species is in which colour.
## 05. Use seaborn
Use the [seaborn](http://seaborn.pydata.org/examples/scatterplot_matrix.html) library to create a scatterplot matrix of all five variables.
## 06. Fit a line
Fit a straight line to the variables petal length and petal width for the whole data set. Plot the data points in a scatter plot with the best fit line shown.
## 07. Calculate the R-squared value
Calculate the R-squared value for your line above.
## 08. Fit another line
Use numpy to select only the data points where species is setosa. Fit a straight line to the variables petal length and petal width. Plot the data points in a scatter plot with the best fit line shown.
## 09. Calculate the R-squared value
Calculate the R-squared value for your line above.
## 10. Use gradient descent
Use gradient descent to approximate the best fit line for the petal length and petal width setosa values. Compare the outputs to your calculations above.
