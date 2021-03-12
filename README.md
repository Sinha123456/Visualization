# Visualization
# Introduction:
Visualization is useful for quick assessing your data. fuel efficeincy and pokemon data used for visualization, data is available for download.

clone: https://github.com/Sinha123456/Visualization.git

## Scatter plot
If we want to inspect the relationship between two numeric variables, the standard choice of plot is the scatterplot.
In a scatterplot, each data point is plotted individually as a point, its x-position corresponding to one feature value 
and its y-position corresponding to the second. 

If we want to inspect the relationship between two numeric variables, the standard choice of plot is the scatterplot. 
In a scatterplot, each data point is plotted individually as a point, its x-position corresponding to one feature value
and its y-position corresponding to the second. 

## Heat maps are useful in the following cases:

To represent a plot for discrete vs. another discrete variable
As an alternative to transparency when the data points are enormous

Default heat plot using Matplotlib.pyplot.hist2d() function

## Violine plot

Violin plot for a Quantitative variable versus Qualitative variable

For each level of the categorical variable, a distribution of the values on the numeric variable is plotted. The distribution is plotted as a kernel
density estimate, something like a smoothed histogram.

## Box Plots

A box plot is another way of showing the relationship between a numeric variable and a categorical variable. Compared to the violin plot, 
the box plot leans more on the summarization of the data.

## Cluster Plot

To depict the relationship between two categorical variables, In a clustered bar chart, bars are organized into clusters based on levels of the first variable, and then bars are ordered consistently across the second variable within each cluster. 

## Faceting

n faceting, the data is divided into disjoint subsets, most often by different levels of a categorical variable. For each of these subsets of the data, the same plot type is rendered on other variables. Faceting is a way of comparing distributions or relationships across levels of additional variables, faceting is most useful in multivariate visualization.

## Pointplot

A point plot represents an estimate of central tendency for a numeric variable by the position of scatter plot points and provides some indication of the uncertainty around that estimate using error bars.

## Adapted bar plot

Histograms and bar charts were introduced in the previous lesson as depicting the distribution of numeric and categorical variables, respectively, with the height (or length) of bars indicating the number of data points that fell within each bar's range of values. These plots can be adapted for use as bivariate plots by, instead of indicating count by height, indicating a mean or other statistic on a second variable.

## Use Doccuments for the visualization

Violine plot: https://seaborn.pydata.org/generated/seaborn.violinplot.html

Categrical dtype in pandas: https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.api.types.CategoricalDtype.html

Explanation of categorical dtype in terms of memory, It's very nice doccumnet to understand this:

https://pandas.pydata.org/pandas-docs/stable/user_guide/categorical.html

boxplot: https://seaborn.pydata.org/generated/seaborn.boxplot.html

axes object: https://matplotlib.org/stable/api/axes_api.html

pivot(reshape data): https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.pivot.html

pointplot https://seaborn.pydata.org/generated/seaborn.pointplot

matplotlib usage guide https://matplotlib.org/stable/tutorials/introductory/usage.html


## Libraries

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

%matplotlib inline

## License

Sinha123456

Licensed under the MIT License





