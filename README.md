# JP_Morgan_Project
## Task 1 - Investigate and analyze price data



* AIM: pricing the natural gas storage contract
* OBJ1: extrapolate external data to increase granularity (Data preparation)
* OBJ2: analyse seasonality & annual trends 
* OBJ3: price the contract using historical data to make future gas price prediction


**Background info:**
Commodity storage contract: an agreement (between warehouse owners and participants in the supply chain) to store an agreed quality of any physical commodity in a warehouse for specified amount of time.

**Key terms of such contracts:** 
*  periodic storage fees, withdraws/injections limits.
*  Injection date: is the time when the commodity is purchased and stored
*  Withdraw date: the commodity is withdrawn from the storage.

**Data source:** monthly snapshot of prices which represents the market price of natural gas delivered at the end of each calendar month.
Data available for next 18mo + historical

**Task:** EDA historical data and an extrapolation for an extra year.
Estimate purchase price at any date in the past and extrapolate for one year into the future.

**Model input:** date

**Model output:** estimated price
