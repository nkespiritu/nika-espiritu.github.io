---
title: "Comparing travel behavior during 2019 and 2020 in the New York City Taxi and Limousine Commission trip records"
date: 2020-11-30
tags: [data wrangling, data science, exploratory data analysis, big data]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Data Wrangling, Data Science, Messy Data"
mathjax: "true"
---

by Nika Espiritu and [Jasper Pangan](https://www.linkedin.com/in/jasperkristianpangan/)

## Purpose

This mini project was submitted for our Big Data and Cloud Computing class held from September 2020 to January 2021. In this class, we were tasked to do an exploratory data analysis on 15 GB worth of data. We were required to use Dask, a Python library specifically for wrangling big data.

## About the data

Data of trips taken by taxis and vehicles in New York City were retrieved from the NYC Taxi and Limousine Commission (TLC) Trip Record Data found in the Registry of Open Data on Amazon Web Services (AWS) S3 bucket.

As of writing this, data available was only from January 1, 2019 to June 30, 2020. This corresponds to  9.36  GB worth of data. After preprocessing, this corresponds to  80,810,133  transactions in 2019 and  15,859,906  transactions in 2020.

## Methodology

<img src="{{ site.url }}{{ site.baseurl }}/images/workflow.png" alt="Methodology">

## Insights

1. We found little change in routes and in travel times of New Yorkers, but instead we found that New Yorkers strictly complied with the stay-at-home measures enacted by the government, thus signifying a drop in the volume of taxi transactions. 
2. People usually travelled alone in pre-pandemic times, but this phenomenon increased during the pandemic. 
3. We also found that cashless transactions were banned by legislators, and people are experiencing the impacts of this legislation. 
4. With the reopening of New York, we are now seeing a small increase in volume of transactions, and this should help NYC taxi drivers.

For the full report, click [here](../_pages/nyctlc_eda/"Technical Report MP2.html").

Here's some basic text.

And here's some *italics*

Here's some **bold** text.

What about a [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item


Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$
