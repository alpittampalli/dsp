[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

pmf2=thinkstats2.Pmf(resp.numkdhh)
thinkplot.Pmf(pmf2)
pmf2.Mean()
#Answer=1.024205155043831

thinkplot.Pmf(BiasPmf2(pmf2))
BiasPmf2(pmf2).Mean()
#Answer=2.403679100664282
