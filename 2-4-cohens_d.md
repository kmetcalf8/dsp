[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> 
""" Question1 
In terms of frequency, 38 weeks of pregnancy is the most common for both first born babies and all other babies after the first. The average pregnancy for all babies is 38.56 weeks which compares to 38.60 weeks for first babies and 38.52 weeks for all other babies. At first glance, this would suggest that there is minimal difference in the length of pregnancies between first babies and others. However, looking more closely at the data, the variance for all pregnancies is 7.30 which compares to 7.79 for first babies and 6.62 for all other pregnancies, meaning that other pregnancies are more likely to cluster around the average of 38 weeks while first pregnancies are more spread out. Further, the standard deviation of all pregnancies is 2.70 which compares to 2.79 and 2.61 for first and other pregnancies, respectively, with the higher standard deviation of first pregnancies suggesting that there is more variability in pregnancy for first babies.

For the evening news, the data does suggest that it is more likely that first babies will have a longer gestation period than other babies, it is also more likely that first born babies will be born earlier. When speaking to first time parents, while there is a higher chance that a first baby will be born earlier or later than 38 weeks compared to other babies, the average gestation is still 38 weeks, in line with the overall average while the standard deviation (variability) is not much greater than the standard deviation for overall births. """

"""Question 3
def Mode(hist):
    k, v = max([(k, v) for v, k in hist.Items()])
    return v
    
    from operator import itemgetter
def AllModes(hist):
    return sorted(hist.Items(), key = itemgetter(1), reverse = True)

"""


