# Visualization
# Introduction:
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


## Use Doccument for the visualization

Violine plot: https://seaborn.pydata.org/generated/seaborn.violinplot.html

Categrical dtype in pandas: https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.api.types.CategoricalDtype.html

Explanation of categorical dtype in terms of memory, It's very nice doccumnet to understand this:

https://pandas.pydata.org/pandas-docs/stable/user_guide/categorical.html

boxplot: https://seaborn.pydata.org/generated/seaborn.boxplot.html

axes object: https://matplotlib.org/stable/api/axes_api.html


