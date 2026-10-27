---
title: "COGS 108 Data Science Project"
collection: talks
type: "Talk"
permalink: /talks/COGS108
venue: "UC San Diego, COGS 108 Course"
date: 2022-01-01
location: "San Diego, CA"
---

COGS108 Data Science Project (2022)
======

[PROJECT LINK](https://github.com/BellaIngenue/SienaRivera_COGS108)

* Conducted an in-depth analysis of the correlation between the Air Quality Index (AQI) and changes in driving patterns during the COVID-19 pandemic, leveraging Python, Pandas, NumPy, and Jupyter Notebooks
* Collected and meticulously cleaned large datasets on AQI and traffic patterns from multiple sources, ensuring accuracy and consistency over a 3-month period
* Applied statistical and data science techniques to uncover significant trends and insights, demonstrating the impact of reduced vehicular traffic on air quality


Overivew of this Project:
======

**Research Question**

Did California Air Quality significantly improve in different areas due to the COVID-19 Pandemic and the change in car traffic volume?

**Hypothesis**

We hypothesize that COVID-19 has had an overall good effect from 2020-2022 on Air Quality based on AQI (Air Quality Index). We think that the pandemic has led to more WFH (work-from-home) and remote opportunities for the general population of California, thus changing the amount of air pollution caused by a reduction in car traffic via commuting. We acknowledge that there may be some confounding variables including regional industries, population per capita, and lockdown restrictions

**Conclusion**

Our goal of this project was to describe the potential correlation between California Air Quality and the COVID-19 pandemic with the subsequent change in car traffic volume. We hypothesized that the pandemic had an overall good effect on Air Quality in California due to a decrease in car traffic volume. Through our exploratory data analysis, we have come to reject our original hypothesis.

We used Air Quality data from 2010-2021 across all counties in California, but we picked a few counties that represented different regions to focus on. These counties included Los Angeles, San Diego, Shasta, Santa Cruz, Mariposa, and Sacramento. When looking at the overall trends in the changes of AQI in these counties, we could not see a significant differences from year-to-year measures. We also could not identify meaningful changes in the relationship between traffic volume and air quality, especially during the time period of the COVID-19 pandemic (2020-2021).

We also investigated a potential relationship between gasoline sales in California with changes in air quality, but once again were unable to find a significant relationship between the two variables. Although there was a noticable drop in gasoline sales during the time period of the COVID-19 pandemic, there was no effect on the relationship with air quality according to our data. In conclusion, with the data that we were able to gather for the air quality, traffic volume, and gasoline sales in California, we were unable to find any statistically significant relationships between these variables.

**Discussion**

We first decided to create a multitude of graphs and illustrations to help us and the reader understand the Datasets. This allowed us to see a better picture of how the different Datasets related to one another. Starting with our Air Quality (Measured by AQI), we used several graphs and included a Heat Map as well. The results showed that there was definitely an outlier when it came to some Southern California Counties. Specifically Los Angeles, which had a worsened AQI compared to the other chosen Counties. In terms of Traffic Volumes (Measured by AADT), we also used several graphs and included another two Heat Maps to help illustrate the effects. Interestingly, we noted that several Counties had a huge fall in Traffic Volumes in the year 2016. Our group wanted to investigate this anomoly further, but we were not able to find any information to conclude our findings. Lastly, in terms of Gasoline Sales, we used several graphs and looked at individual Counties to further provide a big picture of what happened throughout our chosen years. It again peaked out interest, when we found a large fall in Gasoline Sales around the year of 2014. We also tried to investigate this further, but were unable to find anything.

In terms of our further analysis of our Data, we decided to find the outliers of each Dataset and attempt to do OLS (Ordinary least squares). When it came to our outliers, we found the Data quite intruiging. While Median AQI had hardly any outliers, the other two Data did. Traffic Mean AADT showed many outliers, as did Gasoline Mean Sales, this could be because of places like Los Angeles, and San Francisco, which have a large amount of traffic and gasoline sales per year. It was just interesting to see, and helped us to understand the relationships given. As for OLS, we attempted to look into the relationship between Median AQI and Traffic Mean AADT. We first used the Raw Data, and then Normalized the Data in the second OLS attempt. Both showed a smaller p-Value than our Alpha level, which is good. However, our r-squared were both too low and indicated both models were not a good fit. When it came to both of our Scatter Matrixes (one of Raw Data, one of Normalized Data), we did not find a signficiant relationship between AQI and Traffic.

Although we rejected our initial hypothesis that there was a positive relationship between the air quality and decrease in traffic volume due to the COVID-19 pandemic, this does not necessarily indicate that no such relationship actually exists. We think that the reason we were unable to establish a statistically significant relationship between the two variables of investigation was due to the limitations we had with the data. As discussed above, there are multiple confounding variables which we believe contribute to us not being able to draw a clear conclusion that reliably demonstrates a positive relationship. If we were able to continue our work in investigating this topic, we would take greater steps to find more extensive and detailed data about the air quality measures across California. We would also be highly interested to see what conclusions other researchers and analysts are able to draw in the future, with air quality data that is more up-to-date and reflective of the actual time period of the COVID-19 pandemic. As the world returns slowly to a sense of normalcy, we feel that this topic of our impact on the environment around us is important to recognize and we wish to see further attention dedicated towards this field.

**DATA PHOTOS**

![AQI](/images/data/aqi.png)
![AQI HeatMap](/images/data/aqi_map.png)
![Max AQI](/images/data/max_aqi.png)
![Traffic](/images/data/traffic.png)
![Traffic HeatMap](/images/data/traffic_map.png)
![ScatterMatrix](/images/data/scattermatrix.png)