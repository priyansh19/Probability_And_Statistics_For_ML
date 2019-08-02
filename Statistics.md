
# Mean:

Also known as the average of the given series. 

Formula: Sum of the numbers / Total numbers of samples.  

# Median:

Sort the values, and taking the value in the middle.
Median is less susceptible to outliers than mean
 
Formula: If no is odd then simply the value at the middle will be the median and if the no. of values are even then you have to sum the values at the center and divide it by 2.
 
# Mode:

The common value in a dataset and it is not relevant to continuous data distribution

Formula: the most occurring value in the dataset is the mode of the data

# Standard deviation and variance :

Outlier is numerical values that are far away from the other dataset values.

They are all about the shape of the distribution of data

Variance (sigma)^2 is simply the **average of the squared differences from the mean**.

Standard deviation (sigma) is just the square root of the variance term. It is the most important variable as it is used to identify the outliers in the dataset
  
You can talk about standard deviation in such a way that how extreme a data points is by talking about "how many standard deviations  " away from the mean it is


# Normal Distribution :

In Sample Variance, the only difference is when we finally divide the sum of squares of the differences by the **total no of datapoints - 1** this is the only difference between S^2 and sigma^2.

As the presence of the outliers affect the mean of the data set by a huge amount of magnitude hence it also affects the standard deviation     

Normal distribution curve is also known as the probability density curve. It gives you the probability of the data points falling within some given range of values.

probability mass function is used for visualizing the discrete values occurring in the dataset
 
# Uniform Distribution 

It is a flat constant probability of an event occurring. Every range of values has an equal chance of occurring as another range of value is.

There are various kinds of probability distribution/mass functions listed in the ipython notebook [Distribution.ipynb](https://github.com/priyansh19/Probability_And_Statistics_For_Data_Science/blob/master/Distributions.ipynb)

# Covariance and Corelation: 

It is a measure how two variables vary from thier tandem from thier names.

Measuring Covariance is basically a dot product between two hihg dimensional vectors i.e measuring the cosine angle between the two vectors.

Large covariance impleis that the covariance does have some relationship between the tow vectors.But how large is the "Large" ?

Here is the Correlation comes into the scope.. To calculate it .. just Divide the covariance by the standard deviation.

Correlation if = 0 No Correlation between vectors, if = -1 Perfect inverse correlation, if =1 then perfect correlation.

Remember that correlation does not implies causation ! means that if there is a very high correlation then it is not compulsory that one thing causes another thing.

You can take help from the [CorrelationandCovariance.ipynb file](https://github.com/priyansh19/Probability_And_Statistics_For_ML/blob/master/CovarianceCorrelation.ipynb) to get familiar with code.

Rough python code for finding covariance and corelation 
![ss1](https://user-images.githubusercontent.com/33621094/62338955-ff05c200-b4f7-11e9-8301-2bbaf25f9f05.png)

Here de_mean function is finding the value of each deviation from the mean to the point and the covariance function is baiscaly finding the dot product of the deviations from the mean points 

Covariance is sensitive to the data points hence it doesnot tells us anything about the relationship between data points here comes the corelation which ranges from 1 to -1 and hence it tells the relationship

# Bayes Theroem :
