# Proletariats

## Quandle API Key
Sign up for a Quandl account, then the API key will be available in your account settings: https://www.quandl.com/account/profile 

### Save API Key
import quandl
quandl.save_key("YOUR_KEY_HERE")

### Use Quandl API key
quandl.read_key()
api_key = quandl.ApiConfig.api_key
