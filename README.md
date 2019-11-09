# day-ahead-market-price-prediction
Objective
We want to predict the day ahead price for each hour. When participating to the DAM market, LSEs (Load Serving Entities) have to make their bids (consisting of a quantity in MW and a marginal price in $ per MW). The total demand is something known by the LSE when making this bid (CAISO provides it). Predicting the price is of prime importance for the LSE for two reasons:

make sure price bid is lower than the clearing price
Adjust quantities wisely along the different hours
This problem of price prediction is non trivial regarding demand. As it can be seen, there is not a simple link between price and demand. Price formation is complex. First, technically, the DAM price of electricity depends on prices of some commodities (e.g. natural gas), it depends on the moment of the day (e.g. solar production at noon with zero marginal cost) and on some technical aspect of production means (e.g. a nuclear plant have limited power ramping constraints). But DAM prices also depend on the bidding strategies (ENRON and the California Electricity Crisis of the 2000s is an example of market power/price distortion).
