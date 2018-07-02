[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

>> REPLACE THIS TEXT WITH YOUR RESPONSE

import scipy.stats

mu = 178
sigma = 7.7
dist = scipy.stats.norm(loc=mu, scale=sigma)
type(dist)

dist.mean(), dist.std()

dist.cdf(mu-sigma)

import brfss
df = brfss.ReadBrfss()
mu = 178
sigma = 7.7


belowmean = dist.cdf(177.8)
abovemean = dist.cdf(185.7)
abovemean - belowmean



