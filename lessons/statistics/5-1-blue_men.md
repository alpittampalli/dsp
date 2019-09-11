[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

mu = 178
sigma = 7.7
dist = scipy.stats.norm(loc=mu, scale=sigma)

min_height = (5*12+10)*2.54
max_height = (6*12+1)*2.54

dist.cdf(max_height)-dist.cdf(min_height)

#Output= 34.27%
