Title: Introduction to stats-primer-numpy
Date: 2016-12-27 1:00
Category: stats



## Introduction to stats-primer-numpy.

There are two field of statistics:
1)Descriptive statistics used to describe, summarize, and understand the data;
2)Inferential statistics makes inferences and predictions about a population based on a sample of data taken from the population in question.

The distribution of a statistical dataset (or a population) is a list or function showing all the possible values (or intervals) of the data and how often they occur.

The Central Tendency provides descriptive information about the single numerical value that is considered to be the most typical of the values of a quantitative variable like mean, median, and mode.

## How to calculate mean, median, and mode?

from numpy import mean, median
from scipy.stats import mode
mean(n)
median(n)
mode(n)
where n is a list of float number.


## What is skewness?
Skewness is lack of symmetry in a distribution of data.
A positive-skewed distribution means the right side tail of the distribution is longer or fatter than the left.

Likewise a negative-skewed distribution means the left side tail is longer or fatter than the right.

Symmetric distributions have no skewness!

Negative skew: mean < median < mode
Positive skew: mode < median < mean

OR

If the mean < median, the data are skewed left.
If the mean > median, the data are skewed right.


## Introduction to Range, Variance and Standard Deviation

1) The range is the difference between the lowest and highest values of a distribution and can be calculated with:

n_range = np.ptp(n)

2) The variance is a numeric value used to describe how widely the numbers distribution vary and can be calculated with:

variance = np.var(n)

3) The standard deviation is the square root of the variance.

std = np.std(n)

which is the average of the sum of the squared distances of each number from the mean of the numbers.
