# PyBer_Analysis

# PyBer Analysis Report

## Background and Results

### Purpose

The original data work done throughout the start of the project gathered valuable data about the differences between Urban, Suburban, and Rural rides. By taking a look at fare totals over time, we're better able to analyze the impact to the business that these three units represent. From there, we're also better able to know where to focus future investments in business growth and driver support.

### Technical Analysis

By performing sum calculations on the data grouped by both "type" and "date", we were able to chart the results in a way that visually demonstrates the impact of each business unit on the organization as a whole.

### Results and Summary

While the Urban rides contribute more to the total revenue, the Rural rides have a higher average fare. Depending on other factors that we'll dive into later in the analysis, this data suggests that the Rural section may be a better opportunity for future investment.

Additionally, the line graph demonstrates spikes across the board at the end of February. That could be a good indication of additional areas of study. In elimination business-related factors, it could reveal that to be the most lucrative time in rideshare.

![Summary DataFrame](https://github.com/travgreenfield/PyBer_Analysis/blob/master/analysis/PyBerSummaryDF.png?raw=true)

![Fare Total Over Time -- Line Chart](https://github.com/travgreenfield/PyBer_Analysis/blob/master/analysis/TotalFareOverTime.png?raw=true)

## Challenges Encountered and Overcome

### Challenges and Difficulties Encountered

In manipulating and pulling data from multiple DataFrames, it took debugging to recognize that some operations are better performed where the data lives most cleanly and not necessarily on the current DataFrame being used.

## Recommendations and Next Steps

### Recommendations for Future Analysis

### Additional Analysis 1

As noted in the original summary, the Urban rides contribute more to the business as a whole but have a lower average fare ride. The first ask for additional analysis would be about the Rural market. 
1) Analysis of the overhead of adding new business and supporting drivers would give us a more clear picutre about how much the business makes per ride.
2) An analysis of the current market saturation of both riders and drivers in the Rural market would indicate how much opportunity exists to grow the business in that area. 

### Additional Analysis 2

The second analysis I would ask for is a deeper dive into the company practices (whether marketing or technical) that may have led to the spike in business in the end of February. It's the only time period where there's a noticable, consistent bump in all 3 business sectors. That ammount of similarity may lead to a successful business practice previously unknown. 
