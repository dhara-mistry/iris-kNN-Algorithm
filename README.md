# iris-kNN-Algorithm
The purpose of this project was to practice using the kNN (k-Nearest Neighbors) algorithm to solve a classification problem. 

The Iris dataset was used for this project. The dataset was first introduced by statistician R. Fisher and consists of 50 observations from each of three species Iris (Iris setosa_, _Iris virginica and _Iris versicolor_). For each sample, 4 features are given: the sepal length and width, and the petal length and width.

The goal was to train kNN algorithm to distinguish the species from one another.

The dataset can be downloaded from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/machine-learning-databases/iris/.

Download iris.data file from the Data Folder. The Data Set description with the definitions of all the columns can be found on the dataset page - https://archive.ics.uci.edu/ml/datasets/Iris.

The following number of neighbors, k, were used to explore the results: 1, 3, 5, 7, 10, 20, 30, 40, and 50. Generated 10 random train/test splits for each value of k and
fit the model for each split and generate predictions. Calculated the average the accuracy score for each k; and plotted the accuracy score for different values of k. This drew some conclusions of the overall model.
