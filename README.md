# Bitcoin-Bull-Call-Spread-Payoff
In this notebook, we will build the payoff graph for long 17400 strike call and short 17860 strike call on Bitcoin.
A bull call spread strategy is built by going long on call option with strike price X1 and simultaneously selling a call option with a higher strike price X2; options with same underlying and maturity. This strategy aims to benefit from small positive movements in the underlying asset. It limits the upside potential as well as the downside risk.

### 1. Import libraries
First, we will import the necessary libraries.

### 2. Call payoff
We define a function that calculates the payoff from buying a call option. The function takes St which is a range of possible values of Bitcoin price at expiration, the strike price of the call option and the premium of the call option as input. It returns the call option payoff.

### 3. Define parameters
We define various parameters required to calculate the call payoff. One of the parameters is the range of Bitcoin price at expiry.
To calculate the Bitcoin price range at the call's expiration, we define a range for the Bitcoin price at expiry from -5% to +10% from the spot price. That is from 95% or 0.95 to 110% or 1.1 from the spot price. These range values are for illustration purposes and can be changed.

### 4. Long 17400 strike call payoff
We plot the payoff of the long 17400 strike call option. 

### 5. Short 17860 strike call payoff
We plot the payoff of the short 17860 strike call option.

### 6. Bull call sread payoff
The max profit is capped at USD 445 and the max loss is limited to USD 15. Therefore, this strategy is suitable when your outlook is moderately bullish on the underlying asset.
