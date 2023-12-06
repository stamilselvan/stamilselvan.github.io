+++
title = "Index Compare"
date = 2023-11-05T00:09:47+01:00
description = ""
draft = false
subtitle = ""
header_img = ""
toc = false
tags = ["IndexFund",]
categories = []
series = ["finance"]
comment = true
+++

Investing in an index fund is a good strategy for beginners.

# What is an index fund?
Take all the companies in the market, invest money according to their market share. E.g: Nasdaq100 index is the combination of top 100 US tech companies, according to their market proportion. Their weight can be found [here](https://www.slickcharts.com/nasdaq100).

# Advantages:
1. Since it comprises of many companies, the likelihood of falling down is reduced.
1. The management cost is very low compared to the actively manage funds. This is called *Expense Ratio*. 
Even 1% management fee, compounded over 40 years would accumulate a huge sum.
1. The index is expected to raise after an economic downfall. How long would it take to raise is hard to predict. Exception here is that if the whole industry goes out of business, then the index would not come back. 

## Comparison:
The following chart compares the S&P500, Berkshire Hathaway and Nasdaq100 index funds. The graph is interactive, feel free to play around.

{{< load-plotly >}}
{{< plotly json="StockCompare.json" height="700px" modebar="false">}}

Download the excel [here](https://docs.google.com/spreadsheets/d/1sMtksaHFq1aCA8g-sdRfO35RzYHQ2CQ1/edit?usp=sharing&ouid=104770753270265639557&rtpof=true&sd=true).

Sources:  
[Berkshire Hathaway Returns by Year](https://www.slickcharts.com/berkshire-hathaway/returns)  
[S&P 500 Total Returns by Year](https://www.slickcharts.com/sp500/returns)  
[Nasdaq Returns by Year](https://www.slickcharts.com/nasdaq100/returns)  

## How to read the graph?
It is drawn as a [box plot](https://en.wikipedia.org/wiki/Box_plot). To summarize, the vertical rectangle box tells the returns over the period of 5/10/... years. 
The box contains 50% of the value. The box which is high in the y-axis means it gave a better returns most of the times.

## Conclusions
### Stabilizing returns
Focus only one index fund in the above chart, it can be observed that the returns are diminishing in both min and max directions. 
This means, over the long period, returns are stabilizing.

### Nasdaq-100
It underwent volatility compared to the other stocks, yielding -9% returns once and +58% return another time. It can be categorized as risky.

### Berkshire Hathaway
Buffet seems to aim for stability over aggressive growth. In any period of time (5/10/…), it performed much better that S&P500 and at least slightly better than Nasdaq100.

### Warning
These are only the past records, thus can’t guarantee anything about the future returns. 
Just we should know how much the impact will be and be ready for the worst case as well.

