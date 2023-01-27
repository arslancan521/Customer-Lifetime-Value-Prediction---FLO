# Customer-Lifetime-Value-Prediction---FLO
Customer Lifetime Value Prediction - FLO

CLTV = Conditional Expected Number of Transaction * Conditional Expected Average Profit

First, the whole customers' behaviours are applied to a model and then make prediction the expected transaction for each customer.

CLTV = BG/NBD MODEL * GAMMA GAMMA SUBMODEL

BG/NBD MODEL for expected number of transaction GAMMA GAMMA SUBMODEL for expected average profit

BG/NBD MODEL : Beta Geometric / Negative Binomial Distribution

Transaction Process(buy)

Possion distribution for the expected number of transaction and transaction rate
Gamma distribution in whole customers
Dropout Process(till you die)

All customers have their dropout probability as p.
Beta distribution for dropout rates
