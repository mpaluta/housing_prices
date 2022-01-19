# housing_prices

## Summary
This repo is where I am keeping track of inflation-adjusted house prices.

Over the past century, house prices have had a few dips and booms, and of course the '08 bubble. But when all was said and done, prices have only slightly outpaced inflation in the long run. See below.

![housing prices past 100 years](https://github.com/mpaluta/housing_prices/blob/main/images/100_year_home_values.png)

## Extending data through present
I wanted to extend this series out to include recent price spikes and see what is up. A couple years ago I found an [Excel sheet](http://housingbubble.jparsons.net) to help easily extend the time series. Unfortunately, that URL no longer works for me, and all I can find from the original author is this related [blog post](http://blog.jparsons.net/2011/04/housing-bubble-graph-fail.html). Fortunately, I cached a version of the sheet, so I created [my own Google sheet](https://docs.google.com/spreadsheets/d/1_5ndt0OvipKKxQwwBkM79xNm9HIDBij9Zl-GEPOSPkY/edit?usp=sharing) using the same methodology to extend the series out to the present. Here is the plot I get:

![series to present](https://github.com/mpaluta/housing_prices/blob/main/images/series_to_present.png)

## Commentary

Does this suggest there is another housing bubble? I'm not really sure. Prices are about 60% higher than the pre-08-bubble trend would put them at, which is staggering.

Ben Carlson makes a good case [against a bubble](https://awealthofcommonsense.com/2021/04/why-this-is-not-another-housing-bubble/). These seem to me like reasonable points, although that was written back in April, and prices have continued going bonkers since then.

The limited supply angle makes a lot of sense to me given the data. But I would expect this shortage to rectify eventually and prices to lower as a result. When there is a supply shortage, there is good money to be made by producing.

There also might be other reasons prices increase. For example developing large homes instead of starter homes, in which case the index is comparing apples to larger apples. But I don't know much about those inputs and housing fundamentals in general.

It also seems plausible that the utility of a home has truly increased in a world with more remote work. If some of us are going to be spending twice as much time in the home, we increasingly value owning our own place that we can configure for work and comfort. We likely want ownership, larger homes, or more desirable locations, and those reflect higher prices, especially in desirable geographies. I don't see any reason this trend would stop as long as we can work remotely, log off, and be on a trail in the mountains 15 minutes later.

If I had to bet, I would bet that the 60% increase is partially here to stay due to increased utility of home ownership, and partially attributable to transient effects that will resolve as the economy stabilizes toward a more reasonable equilibrium.

## Source data

Shiller home price index can be found [here](https://fred.stlouisfed.org/series/CSUSHPINSA).

Inflation-adjusted prices are adjusted by the [CPI-U-RS](https://www.bls.gov/cpi/research-series/r-cpi-u-rs-home.htm). Prior to Q4 1977 they are adjusted by the CPI - All items less shelter found [here](http://data.bls.gov/cgi-bin/srgate), series id CUUR0000SA0L2.
