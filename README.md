# Proletariats

## Project Summary

Exploring real estate prices in Phoenix, Arizona using Zillow research data available at Quandl and Consumer Price Index and employment  data from US Bureau of Labor Statistics.

The final presentation is available at:

https://github.com/jgoldpac/Proletariats/blob/master/Presentation/Analysis%20of%20Phoenix%20AZ%20Real%20Estate%20Trends.pptx?raw=true

## Quandl API Key
Sign up for a Quandl account, then the API key will be available in your account settings: https://www.quandl.com/account/profile 

### Save API Key

import quandl

quandl.save_key("YOUR_KEY_HERE")

### Use Quandl API key

quandl.read_key()

api_key = quandl.ApiConfig.api_key

