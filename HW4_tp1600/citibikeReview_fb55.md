# Idea
good

# Null hypothesis
The average number of daily trips using 24 hour passes or 3 day passes on weekends (E) in NYC during August 2018 is the same or lower than the average amount on weekdays (D) during the same time period with a significance level of .10. (Weekends=Saturday and Sunday)
However, you really want the Average 

# Formula
good

# Data

you have counted the rides, but what you want is to take the average of the multiple weeks (weekdays) and multiple weekends

You cannot do statistical tests on absolute numbers. You need to measure "statistics" to do statistical tests - here you want to measure the mean, and also the standard deviation, over multiple weekends and multiple weeks, to compare. 

# Test

this is a difference between means of samples, so the t test would work. however the distributions are not Gaussian. the t-test assumes Gaussianity and your distributions are not Gaussian. a non parametric test for difference of means is the Mann-Whitney U test (https://www.healthknowledge.org.uk/public-health-textbook/research-methods/1b-statistical-methods/parametric-nonparametric-tests) since the samples is large, the t-test may be ok
here is a list of assumptions the t-test makes https://www.investopedia.com/ask/answers/073115/what-assumptions-are-made-when-conducting-ttest.asp

