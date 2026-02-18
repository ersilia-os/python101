# Matplotlib 
Matplotlib is a comprehensive library used to create interactive visualisations, create publication quality plots, export to many file formats all in Python. It has a module called Pyplot that makes plotting a graph easy and fun. Matplotlib has to be installed as well before you import matplotlib and the pyplot module.
```
!pip install matplotlib

import matplotlib.pyplot as plt  #plt is a common alias for matplotlib.pyplot
```
Plots:
- Categorical plots: these plots are used to visualise categorical data (data that can be classified into groups). They include boxplots, barplots and violin plots
- Distribution plots: these plots are used to display how data is distributed or spread. They include lineplots, scatterplots and histograms. 
# Seaborn 
Seaborn is a package built on Matplotlib that produces nicer plots. Its structure is based off Matplotlib, but you should now call the plot functions off Seaborn (sns) instead of Matplotlib (plt). You have to install the Seaborn package as well.

```
!pip install seaborn

import seaborn as sns #sns is a common abbreviation for seaborn
```


_Geographical maps_ this is a very specific function to plot data in a geographical map. You can read more about [Choropleth maps](https://plotly.com/python/choropleth-maps/#reference) and the plotly library in its documentation.
