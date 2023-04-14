# central_limit_theorem_simplified
The most simplified explanation of the Central Limit Theorem

The Central Limit Theorem (CLT) is the corner stone of statistics! Without it there would be no statistics as we have it today! The normal distribution, with its well known special properties, is what developers are more comfortable working with. Most design software is programmed using the normal distribution. Almost all the machine learning algorithms assume that data are normally distributed. And thanks to CLT we can transform any "hunch back" distribution into a normal distribution.

The Central Limit Theorem (CLT) states that given data from a distribution, irrespective of whether the underlying population is normally distribution or not, if we draw sufficiently large number of samples from the data and compute the mean each time, the distribution of these sample means (known as sample distribution) would approach normal (or gaussian). The size of the samples should be large enough with a theoretical minimum cited in literature as 35. This is based on the theory of large numbers. The larger the sample size the smaller the standard error (difference between one sample mean and another) which is due to chance (no two samples are the same and as such the means would be slight different). This is also one of the most important applications of the mean!

The notebook include demos of what I have been explaining above applied on: 
-	A uniform distribution and 
-	A binomial distribution.
