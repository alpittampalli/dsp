[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

def CohenEffectSize(group1,group2):
    import math
    diff=group1.mean()-group2.mean()
    var1=group1.var()
    var2=group2.var()
    n1,n2=len(group1),len(group2)
    pooled_var=(n1*var1+n2*var2)/(n1+n2)
    d=diff/math.sqrt(pooled_var)
    return d
    
CohenEffectSize(firsts["totalwgt_lb"],others["totalwgt_lb"])

#Output = -0.088672927072602, more of an effect size than preg length, but still relatilvely small 
