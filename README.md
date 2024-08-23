# Exploring techniques for unsupervised and supervised time series classification


### Problem statement:

Take a dataset of 3-4 time series of similar nature. Compare the time series for similarity between them.

Write a python code which will check for similarity between them and group them into two clusters.

### Goal of the repository:

Address the problem statement and explore other techniques to solve similar and more complex problems.<br>


### Notebook 1 overview

-In notebook 1 try to cluster time series in an unsupervised manner (labels are not present for the data points, the models learns patterns from the data on its own).

-We generate our own time series dataset.

-Time series generation functions:

1.sin(2 *pi * variable * list of required no. of data points between 0 and 1) + random gaussian noise
2.cos(2 * pi * variale * list of required no. of data points between 0 and 1) + random gaussian noise

-For the given time series, lag is found to be the main metric to cluster the time series based on data analysis

-We then cluster the time series using k means clustering and hierarchical clustering.

-We briefy discuss other techniques which can be used to solve this problem.

### Notebook 2 overview

-The [FordA dataset](https://www.timeseriesclassification.com/description.php?Dataset=FordA) is analyzed.

-The classification problem is to diagnose whether a certain sympton exists or does ont exist in an automotive subsystem.

-Each case consists of 500 time step univariate time series.

-Classification done using a CNN model build with the help of pytorch in a supervised manner.

