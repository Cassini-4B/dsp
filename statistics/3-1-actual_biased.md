[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> REPLACE THIS TEXT WITH YOUR RESPONSE

resp['numkdhh']

hist_children = thinkstats2.Hist(resp['numkdhh'], label='number of children under 18')
thinkplot.Hist(hist_children)
thinkplot.Config(xlabel='Number of children under 18', ylabel='Count')

n_children = hist_children.Total()
pmf_children = hist_children.Copy()
for x, freq in hist_children.Items():
    pmf[x] = freq / n
    
thinkplot.Hist(pmf_children)
thinkplot.Config(xlabel='Number of Children under 18', ylabel='PMF')

pmf_child2 = thinkstats2.Pmf(resp['numkdhh'], label='actual number')

biased_pmf_child = BiasPmf(pmf_child2, label='response number')
thinkplot.PrePlot(2)
thinkplot.Pmfs([pmf_child2, biased_pmf_child])
thinkplot.Config(xlabel='Number of children', ylabel='PMF')

print('Actual mean', pmf_child2.Mean())
print('Observed mean', biased_pmf_child.Mean())
