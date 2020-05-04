# PyBer_Analysis

## Overview
The purpose of this analysis was to better understand ride share data and how it compares for rural, suburban, and urban areas of service. In this project we utilized Python, Jupyter Notebook, Pandas, and MatPlotLib to clean, organize, and visualize the data. The summary dataframe and the multiple-line graph shows that, in general, Urban areas have higher volume of rides, drivers, and total fares. However, rural and suburban areas have a higher average fare per ride and per driver.  In summary:
  - Rural Cities
    * Had the highest average fares per ride and per driver, $34.62 and $55.49, respectfully.
    * Had the lowest number of rides (125), drivers (78), and total fares ($4,327.93).
  - Suburban Cities
    * Had average fares per ride of $30.97 and per driver of $39.50.
    * Had 625 rides, 490 drivers, and $19,356.33 in total fares.
  - Urban Cities
    * Had the highest number of rides (1,625), drivers (2,405), and total fares ($39,854.38).
    * Had the lowest average fares per ride and per driver, $24.53 and $16.57, respectfully.

![](https://github.com/davidwcampbell/PyBer_Analysis/blob/master/analysis/Challenge.png)

## Challenges
This analysis was very challenging. Combining and summarizing data from two different data sets took some time and consideration so that the data integrity could be preserved. Many of these challenges could be resolved by using the 'groupby' function. Resampling the data by week was also a challenge as it was a new function that I had not used before. The matplotlib graphing and charting functions also aided in summarizing and visualizing the data.

## Recommendations
As a result of this analysis, I would recommend that PyBer take a look at their pricing. It is possible that Urban rides are underpriced based on the averages per ride and per driver. It is also possible that rural fares are too high and limiting the number of total rides being taken. PyBer should also look at the number of drivers in each city type. There could be too few in rural areas and too many in urban cities. Additional analysis on the drivers per city and the rides per city could provide additional insight to answer these questions. In order to perform these additional analyses, I would utilize many of the same technical procedures used in the initial analysis--groupby, charts, graphs, and creating new dataframes.
