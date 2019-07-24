-# Percentiles :

A percentile is a measure used in statistics indicating the value below which a given percentage of observations in a group of observations falls. 
Percentiles can be visualised by various types of plots i.e Box and Whiskers Plot , Normal distribution plot ..etc

# Moments :

It is basically a quantitative measure of the shape of a probability density function or a data distribution 

It is a lot simpler as it seems to be :

> The **First** Moment is the mean of distribution

> The **Second** Moment is the variance of distribution

> The **Third** Moment is "skew" : It can be easily identified using graph if it has a longer tail on its left side then it left skewed and is negatively skewed and voce versa.

> The **Fourth** Moment is kurtosis of the graph : All this is How thick is the tail and How sharp is the peak, Compared to a normal distribution  

Syntax for finding third and fourth value of moments - 

Import scipy.stats as sp

sp.skew(variable) ## Skewness of graph

sp.kurtosis(variable) ## Kurtosis value of the graph
