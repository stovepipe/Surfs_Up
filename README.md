# Surfs_Up
SQLite Weather Data Analysis to aid in determining new business's initial location.

## Overview of the Analysis
The Surfs_Up analysis was developed to review weather data for a specific location in Hawaii. A startup that is seeking investors has been tasked with reviewing the weather data for Oahu, identifying trends and communicating the results through various types of data visualizations, in hopes of finalizing the deal with a potential investor.

## Results
* Although the average temperature difference is only 4 degrees between June and December, the assumption maintains that December will be colder than June.
* There is a higher degree of temperature variance in December as compared to June. Larger temperature differences from day-to-day may impact sales.
* Notice the Minimum temperature in December is 8 degrees lower when compared to June, whereas the Maximum temperature is only 2 degrees lower in December. The December minimum temperature is nearly 4 standard deviations south of mean, making it an outlier and potentially skewing the December data. Eliminating outliers may give a more accurate picture of the monthly temperature variance.

### June Temperature Summary Statistics
![June_Summary_Stats.png](https://github.com/stovepipe/Surfs_Up/blob/main/Resources/June_Summary_Stats.png)

### December Temperature Summary Statistics
![Dec_Summary_Stats.png](https://github.com/stovepipe/Surfs_Up/blob/main/Resources/Dec_Summary_Stats.png)

## Summary
As a result of the analysis, the conclusion can be drawn that Oahu is a suitable location for the startup's first location. As a surf shop and ice cream shop combo, sales will be heavily dependant on weather conditions that permit these two activities to occur. We determined that precipitation and average temperature will not impact the opportunity for this startup to be a thriving year-round business. For the potential investor, providing analysis from real weather data is critical to the commitment as they had a similar venture fail before as a result of less than ideal weather trends. Oahu has shown to be a suitable year-round location for the first store launch after reviewing weather data.

### Future Recommendations
* Recommend diving deeper into precipitation data to determine rainy seasons and peak times of the year as this could have an impact on sales. Similar to the temperature query, one could filter the annual data to present day parecipitation data to identify trends in rainfall.

* While the weather data indicates that Oahu is an ideal location for the store's concept, there are more environmental factors to consider when thinking of good surf conditions. Reviewing ocean temperature data, tide charts, and swell conditions will prove very beneficial to the planning. This analysis reviewed air temperature data, whereas, water temperature data may be more relevant to determine the surfing "seasons" as that population will be a critical customer base.



