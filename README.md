# PyBer_Analysis

### Overview of the analysis
This analysis was undertaken to look at PyBer's data through the lens of the city type, in order to learn more about the company's results, uncover trends, and mitigate performance disparities between the city types. Using Pandas, PyBer's ride-sharing data was summarized by city type (urban, suburban, or rural). Then, using Matplotlib, a multi-line graph was created to illustrate the trends in total weekly fares for each city type.

#### Results

##### Analyzing the PyBer Summary DataFrame
Urban cities have 13x the amount of total rides as rural cities, and over 2.5x as much as suburban cities. Similarly, they lead in total drivers, with over 30x the total drivers as rural cities, and nearly 5x as much as suburban cities. Although urban cities also lead in total fares, the difference is less stark. In that category, urban cities have over 9x as much as rural cities, and just over 2x as much as suburban cities.

Here's a look at the summary statistics for all three city types:

![image](https://user-images.githubusercontent.com/107162310/178087366-0bfaf254-583e-440e-86d3-5213080a87c0.png)

Rural cities lead in both average fare per ride & average fare per driver. Notably, the average fare per driver in rural cities is over 3x as much as it is in urban cities.

##### Total Fares per Week by City Type (Jan. 2019 - Apr. 2019)

![PyBer_fare_summary](https://user-images.githubusercontent.com/107162310/178088095-7fe7771f-bedf-4ce0-9036-f15fde1f91ee.png)

There are a few notable differences between the city types when analyzing this time period by the sum of total fares. While urban and rural cities saw their total fares decline after the first week of April, suburban cities saw two straight weeks of dramatic increases. Another notable difference in weekly fares can be seen at the start of the timeframe, where urban and suburban cities each had strong upticks right away, but rural cities declined to their lowest totals. Lastly, from mid-to-late February through the end of March, suburban and rural cities had similar trends in total fares, but urban cities showed weekly peaks and valleys.

#### Summary
Based on the the summary statistics of the three city types and the weekly total fares sample, I would make the following recommendations for addressing the discrepancies:

1. Reduce the overall number of drivers in urban cities. With 5x as many drivers as suburban cities but only 2.5x as many total rides, and 30x as many drivers in rural cities but only 13x as many total rides, the number of urban drivers can be reduced without impacting service. This can also help increase the average fare per driver so that urban drivers are not seeing 3x lower fares than their rural counterparts.
2. Provide rural cities with more drivers. More drivers should help reduce fare cost, which may increase total rides. If willing, drivers reduced from the urban cities can instead be used in rural cities.
3. Divert some drivers operating in urban cities into the suburban ones in the month of April. Suburban cities have shown a surge in fares during this timeframe, whereas urban cities have shown a steady decline, so drivers who would stand to make less in urban cities can instead help meet demand in nearby suburban cities.
