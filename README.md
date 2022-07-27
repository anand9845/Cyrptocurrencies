# Cyrptocurrencies

We are applying clustering algorithm Kmeans on a crypto currencies dataset.
We start by droping all the crypto currencies that are not being traded.
Followed by only keeping the crypto currencies with working algorithms and
dropping the NaN values. Then we drop the columns that are irrelevant for 
the kmeans algorithm and split the columns with text values into dummies.
Then we break the data into 3 principal components.
	To determine the best value for k. We use Kmeans algoorthm for
different k-values and plot a line for corresponding Sum of Squared errors.
Then we make clusters using the best k value. Add the cluster number to 
a data frame along with other data. and do some visual analysis on it
	In visual analysis we make different kind of scatter plots based
on Principal Components and Coins mined and supplied respectively.
