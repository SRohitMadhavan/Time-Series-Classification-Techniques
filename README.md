# Exploring techniques for unsupervised and supervised time series classification

#### Notebook 1

-In notebook 1 we generate our own time series dataset.

-Time series generation functions:

1.sin(2 *pi * variable * list of required no. of data points between 0 and 1) + random gaussian noise

2.cos(2 * pi * variale * list of required no. of data points between 0 and 1) + random gaussian noise

-Lag is found to be the main metric to cluster the time series based on data analysis

-We then cluster the time series using k means clustering and hierarchical clustering in an unsupervised manner.

#### Notebook 2

-The FordA dataset is analyzed.
-The classification problem is to diagnose whether a certain sympton exists or does ont exist in an automotive subsystem.
-Each case consists of 500 time step univariate time series.
-Classification done using a CNN model build with the help of pytorch in a supervised manner.
