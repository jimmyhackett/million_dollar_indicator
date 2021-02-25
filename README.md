# The Million Dollar Indicator

## Is it possible to predict future macro economic levels based on population growth with internal consumption in the US reaching 70%?

## Is there a strong correlation between the GDP growth and population growth?

First we compared annual percent change of GDP and Population, but did not find a strong correlation.

### Show Annual percent change correlation graphic - shows annual population change is not a good short term indicator

We then decided to see if the long term growth rate had any correlation with the long term growth rate of GDP, which we did find to have a strong correlation. This implicated population growth as a possible indicator of future economic growth.

### Show overall population Growth and GDP Correlation

### Show working population Growth and GDP Correlation

Next we decided to see if there was a particular demographic which might have a greater impact on GDP, which potentially could then be used as an indicator of future economic growth.

We chose to compare age groups with 10 year differences and their average income levels from 1967 to 2019 to see if any particular group had a consistently higher earnings than the others.

### Show graphics of historic Income level comparisons. = 45-54 yr old consistently beat other demos

### Show graphic correlations for each demo:  (45-54 should be the strongest until 2008)

### Accompany with Correlations presented numerically

### Possibly show: graphic of covariances for demographics and populations

### Graphic to illustrate historic make up of GDP= C + I + G + ( X - M ) (<https://share.getcloudapp.com/12uozBGo>)

## Installation

### Download csv's

#### (<https://www2.census.gov/programs-surveys/cps/tables/time-series/historical-income-people/p09ar.xlsx>)
#### (<https://data.census.gov/cedsci/table?q=consumer%20expenditure%20survey%201990&tid=ABSCS2017.AB1700CSA01&hidePreview=true>)
#### (<https://www.census.gov/data/tables/time-series/demo/income-poverty/historical-income-people.html>)
#### (<https://data.worldbank.org/indicator/SP.POP.TOTL?end=2019&start=1969&view=chart>)
#### (<https://www.multpl.com/us-real-gdp-growth-rate/table/by-year>)
#### (<https://www.multpl.com/inflation-adjusted-s-p-500/table/by-year>)
#### (<https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fblogs-images.forbes.com%2Fmikepatton%2Ffiles%2F2014%2F12%2FUS-GDP-Components-from-1929-to-2011.jpg>)
#### (<https://www.multpl.com/us-gdp-inflation-adjusted/table/by-year>)
#### (<https://www.multpl.com/us-real-gdp-growth-rate/table/by-year>)
#### (<https://www2.census.gov/programs-surveys/cps/tables/time-series/historical-income-people/p09ar.xlsx>)

### Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pandas, numpy, matplotlib, seaborn, panel, pandas, hvplot, os, and tablescraper

### If pip package manager does not work, use anaconda with the syntax conda activate <package_name>

PC: open bash
Apple: open terminal window

enter command prompt (C:)

```bash
pip install pandas
pip install numpy
pimp install matplotlib
pip install seaborn
pip install panel
pip install pandas
pip install hvplot
pip install os
pip install tablescraper
```

## Usage

```python
import pandas as pd 
import numpy as np
import datetime as dt
from pathlib import Path
import matplotlib.pyplot as plt
import seaborn as sns
import panel as pn
pn.extension(‘plotly’)
import plotly.express as px
import pandas as pd
import hvplot.pandas
import matplotlib.pyplot as plt
import os
from pathlib import Path
from dotenv import load_dotenv
import tablescraper as ts
```

## Contributing

Contributing to this project: Taylor Tucker, Jeff Scott, and Jimmy Hackett

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change
