---
layout: post
title:  "Semester Project -- EDA and Report"
author: Yuexi Zeng
description: This is the second part of my semester project, we will go through the exploratory data analysis process"
image: "assets/images/Tesla-carback.jpg"
---

## Introduction
In the fast-paced world of electric vehicles, Tesla stands out as a beacon of innovation and ambition. Yet, with its rapid growth and technological advances come questions about safety and market performance. This blog post is the second installment in my journey to understand Tesla better, this time through the lens of Exploratory Data Analysis (EDA).




## The Data Tells a Story

My EDA began with Tesla's fatality data. Using a dataset sourced from Kaggle, I meticulously analyzed each incident involving Tesla vehicles that led to fatalities. The data, detailed and sobering, provided not just statistics but also stories that needed to be told with sensitivity. I charted the number of deaths over time and across different countries, revealing patterns and raising questions about the factors contributing to these unfortunate events.


![Tesla Number of Death per Year](https://github.com/zyuexi2/yuexizeng.github.io/blob/main/assets/images/death-year.png?raw=true)

The bars represent the number of deaths each year, with a visible increase over time. Starting from a few deaths in 2013, there is a fluctuating pattern with a notable rise in deaths starting in 2019, peaking in 2021 with the highest number of fatalities represented by the tallest bar on the chart. The year 2022 shows a slight decrease from 2021 but remains high compared to the earlier years. 

![Tesla Number of Death by Country](https://github.com/zyuexi2/yuexizeng.github.io/blob/main/assets/images/death-country.png?raw=true)

The graph lists various countries along the vertical axis and the corresponding number of deaths on the horizontal axis. The United States is depicted with the highest number of deaths, indicated by the longest bar, which suggests a significant lead over the other countries. Following the USA are China and Germany, with notably shorter bars than the USA but still substantial compared to the rest. Other countries such as Canada, the Netherlands, and Norway show smaller numbers of deaths. The rest of the countries listed—including the UK, Taiwan, France, and several others—have increasingly smaller bars, indicating fewer fatalities. This graph provides an overview of the distribution of deaths attributed to Tesla incidents across different nations, highlighting geographical differences in such incidents.

![Tesla Number of Incidents by Models](https://github.com/zyuexi2/yuexizeng.github.io/blob/main/assets/images/model-incidents.png?raw=true)

The next piece of the puzzle was Tesla's stock performance. Leveraging financial databases and APIs, I plotted the company's stock prices, capturing the highs and lows of Tesla's market journey. I observed the stock's volatility, its meteoric rises, and the dips that followed major incidents or announcements.


![High & Low Price of Tesla](https://github.com/zyuexi2/yuexizeng.github.io/blob/main/assets/images/stock1.png?raw=true)

The two lines indicate the highest price (in blue) and the lowest price (in red) of the stock at various points in time. From the start of the graph to around 2020, both lines track closely together, showing relatively modest fluctuations in the stock's price. However, starting in 2020, there is a significant increase in both the high and low values, indicating a period of substantial growth and volatility. The high price line reaches its peak in late 2021 or early 2022, where it surpasses a value of 1200. After this peak, there's a noticeable decline, but the prices remain at a much higher level than in the years preceding 2020. The graph displays the dynamic nature of Tesla's stock prices, with a marked upturn in the latter part of the decade shown.


## The Subtleties of Correlation

![Correlation number](https://github.com/zyuexi2/yuexizeng.github.io/blob/main/assets/images/correlation%20number.png?raw=true)

![Scatter Plot](https://github.com/zyuexi2/yuexizeng.github.io/blob/main/assets/images/correlation.png?raw=true)


### Weak Positive Linear Relationship: 
This coefficient indicates a weak positive linear relationship between Tesla's stock price and the number of fatalities. This suggests that there is a slight tendency for the stock price and fatalities to increase together, albeit weakly.

### Correlation ≠ Causation: 
A fundamental principle in data analysis is that correlation does not equate to causation. Therefore, while the stock prices and reported fatalities move together to a small extent, we cannot assert that one causes the other.

### A Multitude of Influencing Factors: 
Tesla's stock price is subject to a vast array of factors ranging from market trends and investor sentiment to company performance and broader economic indicators. Similarly, the number of reported deaths is a multifaceted issue, influenced by numerous variables beyond the company's stock valuation.

### Statistical Significance: 
The correlation coefficient by itself does not confirm if the relationship observed is statistically significant. 

In essence, the correlation coefficient revealed a slight positive relationship between the stock price and fatalities, yet this is a weak link and should be interpreted with caution. The stock market is a complex ecosystem, and Tesla's valuation is contingent upon a host of factors, just as the occurrence of fatalities has its independent determinants.






## Final Thoughts


As I conclude this phase of our data-driven exploration into Tesla's stock performance and reported fatalities, my journey has been as enlightening as it has been intricate. I've unearthed a tenuous connection between stock prices and safety incidents, a relationship that speaks to the multifaceted nature of market forces and public perception. 

Moving forward, my experience paves the way to investigate wider questions. For instance, how do similar correlations play out in other high-innovation industries? Could a comparative study across different companies reveal common patterns, or would it highlight the uniqueness of each firm's situation?








