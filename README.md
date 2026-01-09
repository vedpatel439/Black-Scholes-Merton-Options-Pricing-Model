This Project is an options modelling program based on the Black-Scholes-Merton Model. The 3 of whom were accredited the noble piece prize for their discovery. 
Often dubbed the 'trillion dollar equation', this model is used to accurately price financial derivatives known as European Style put options and call options. These derivatives provide mechanical leverage and are used by traders to speculate on the price of equities.
Puts tend to increase in value if the equity goes down, calls tend to increase in value if the equity goes up. However its price is subject to a lot more than the underlying equity movement. https://www.investopedia.com/terms/o/option.asp - Reference this article for more info!

They are priced through the input of relevant market data and given option data, the 5 variables (after inputting whether it's a put or a call) are the following:

- the strike/exercise price of the option (strike and exercise are used interchangeably, this model uses 'strike')
- current price of the underlying equity
- time till expiry on the option
- Implied Volatility (referred to as 'IV' for short)
- Risk Free Return rate (usually government bonds)

With this information the Program returns a price for the option.
It also return the values of the Option's Greeks which are the following:

- Delta: How much the options price changes relative to movement of the Underlying Equity (eg; a Delta of +0.80 means for a $1 increase in the equity, the options price increases by $0.80)
- Gamma: How much the Delta changes relative to movement of the Underlying Equity (eg; a gamma of 0.03 means for a $1 move in the equity, the delta value changes by 0.03)
- Theta: Time Decay (this model returns the daily time decay value)
- Vega: How the Options price reacts change in IV (this model shows the value for a 1% change in IV)
- Rho: How the Options price reacts change in Risk Free Return rate

*Puts have a negative delta value whereas Calls have a positive delta Value


