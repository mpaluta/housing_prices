# housing_prices

## Summary
This repo is where I am keeping track of inflation-adjusted house prices.

Over the past century, house prices have dipped due to the World Wars and the Great Depression and spiked during the '08 bubble. But when all was said and done, prices have roughly ended up tracking inflation in the long run. See below.

![housing prices past 100 years](https://github.com/mpaluta/housing_prices/blob/main/images/100_year_home_values.png)

## Extending data through present
I wanted to extend this series out to include recent price spikes and see what is up. I found an Excel sheet hosted at [http://housingbubble.jparsons.net](http://housingbubble.jparsons.net) to help easily extend the time series a couple years ago. Unfortunately, I can no longer find it hosted on the original website. All I can find is this related [blog post](http://blog.jparsons.net/2011/04/housing-bubble-graph-fail.html).

When I extend out using Shiller's methodology, here is what I get.

![series to present](https://github.com/mpaluta/housing_prices/blob/main/images/series_to_present.png)

## Underlying data

Shiller home price index can be found [here](https://fred.stlouisfed.org/series/CSUSHPINSA).

Inflation-adjusted prices are adjusted by the [CPI-U-RS](https://www.bls.gov/cpi/research-series/r-cpi-u-rs-home.htm). Prior to Q4 1977 they are adjusted by the [CPI - All items less shelter](http://data.bls.gov/cgi-bin/srgate) -- enter series id CUUR0000SA0L2.

## TODO

link my Google sheet
