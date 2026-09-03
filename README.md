# metals-auction-model
``model-en.xlsx`` - English
``model-es.xlsx`` - Español

Valuation model for metals auctions. Considers:
- Lot weight (g), purity (k)
- Physical delivery lag of underlying asset (t days)
- Risk-free rate, to control for opportunity cost (6M treasury yields)
- Underlying price volatility (2-yr annualized XAU/COP volatility)
- FX risk
- Auction and resale transaction fees
- Debt financing (margin), if any

Outputs:
- Maximum bid (zero-NPV of investment), non-risk adjusted.
- Maximum bid, risk-adjusted

