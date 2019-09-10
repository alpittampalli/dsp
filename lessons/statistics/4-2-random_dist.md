[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

numbers=np.random.random(1000)
numbers_pmf=thinkstats2.Pmf(numbers)
numbers_cdf=thinkstats2.Cdf(numbers)
thinkplot.Pmf(numbers_pmf)
thinkplot.Cdf(numbers_cdf)

both plots seem to show uniform distributions. 
