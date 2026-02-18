# Session 2: Numpy and Pandas

## Installation
Python has libraries that offer standard solutions to problems that programmers encounter regularly. These libraries are broad and offer a wide range of facilities to make programming easier and faster for the programmer. There are libraries for mathematics, visualisations, data analysis and manipulation, machine learning and many more.
To use these packages, you have to install them first, and then import them into your runtime on Colab. 

Once you install the packages using pip (Python’s package installer), you do not need to run the command again.

### Numpy 
Numpy is a library that offers useful mathematical functions and computing tools with an easy to understand syntax for programmers from any background or with any experience level to benefit from. It is already available in Colab and doesn’t need to be installed.
```
!pip install numpy

#you have to import the library to use it
import numpy as np #np is a common abbreviation for numpy
```
### Pandas 
Pandas is a powerful and user friendly library used to study, explore and exercise control over data. It doesn’t come pre-installed in Colab so it needs to be installed first.
```
!pip install pandas 

#you have to import the library to use it
import pandas as pd  #pd is a common abbreviation for pandas
```
#### Working with Pandas
- Series: the basic object of a pandas dataframe is a Series (a column of indexed elements). The Series method is called off pandas (pd) by using `pd.Series`
- Dataframes: a dataframe is a collection of Series (columns) identified by an index. 
- Missing values: often times, data contains missing values. Missing values are converted to None or NaN by Pandas. These must be handled with before proceeding to further data analysis. The two most common options for dealing with missing values are: 
  - Eliminating rows or columns with missing values 
  - Imputing the null values (an educated guess of the real value, for example the mean, of the column)
- Working with large dataframes: to work with large dataframes, you have to import the dataset. 
- Exporting data: Data can be exported as csv, excel (xlsx) or html files.
