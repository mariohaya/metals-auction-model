# metals-auction-model

Valuation model for metals (gold) auctions. Considers:
- Lot weight, purity
- Physical delivery lag of underlying asset
- Risk-free rate, to control for opportunity cost
- Underlying price volatility
- FX risk
- Auction and resale transaction fees
- Debt financing (margin), if any

Outputs:
- Maximum bid (zero-NPV of investment), non-risk adjusted.
- Maximum bid, risk-adjusted
