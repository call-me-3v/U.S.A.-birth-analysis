# U.S.A.-birth-analysis
 United State of America birth analysis from 2000 to 2014

`US_births_2000-2014_SSA.csv` contains U.S. births data for the years 2000 to 2014, as provided by the Social Security Administration.

The file has the following structure:

Header | Definition
---|---------
`year` | Year
`month` | Month
`date_of_month` | Day number of the month
`day_of_week` | Day of week, where 1 is Monday and 7 is Sunday
`births` | Number of births

Some Analysis has been performed on the data on Google Colaboratory.
To perform the analysis on any python environment the following libraries should be installed and imported.

import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn; seaborn.set()

After importing the libraries use 

pd.read_csv(file path goes in here) to import the data
