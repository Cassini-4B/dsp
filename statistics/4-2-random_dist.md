[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> REPLACE THIS TEXT WITH YOUR RESPONSE

numbers = np.random.random(1000)

pmf = thinkstats2.Pmf(numbers)
thinkplot.Pmf(pmf)
thinkplot.Config(xlabel='numbers', ylabel='Pmf')

cdf = thinkstats2.Cdf(numbers, label='numbers')
thinkplot.Cdf(cdf)
thinkplot.Config(xlabel='numbers', ylabel='CDF', loc='upper left')



