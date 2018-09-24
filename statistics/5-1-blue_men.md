[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

import scipy

#These are the given values for u and sigma

mu = 178
sigma = 7.7

#These are the cm values of the range of acceptable male heights for the group

lower = 177.8 #5'10
upper = 185.42 #6'1

#Calculating the normalized cdf for the upper and lower ranges

percentlower = scipy.stats.norm.cdf(lower, mu, sigma)
percentupper = scipy.stats.norm.cdf(upper, mu, sigma)

#Calculating the percentage in between

bluemen = percentupper - percentlower

print(bluemen)

0.343 == 34.3% are eligable to audition.
