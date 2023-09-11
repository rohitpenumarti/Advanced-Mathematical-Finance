# Advanced-Mathematical-Finance

1. [Binomial Option Pricing of Exotic Options Using Basic Monte Carlo Methods](#binomial-option-pricing-of-exotic-options-using-basic-monte-carlo-methods-link)
2. [Binomial and Black Scholes Option Pricing using Basic Monte Carlo Methods](#binomial-and-black-scholes-option-pricing-using-basic-monte-carlo-methods-link)
3. [Variance Reduction Analysis and Markowitz Mean-Variance Portfolio Optimization](#variance-reduction-analysis-and-markowitz-mean-variance-portfolio-optimization-link)
4. [CAPM](#capm-link)
5. [American Option Pricing](#american-option-pricing-link)

### Binomial Option Pricing of Exotic Options Using Basic Monte Carlo Methods ([link](https://github.com/rohitpenumarti/University-Projects/blob/master/Undergrad/PSTAT%20176/Homeworks/Homework%201/Penumarti.Rohit.HW1.ipynb))
This assignment had a few problems involving option pricing of exotic options using monte carlo methods.

The first problem asked to price an up and in barrier call using an 8-period binomial model with given parameters for the option. This option is only exercised when the maximum value during the path exceeds a certain predetermined value, B, at which point the option is 'knocked in'. I had to find number of scenarios for non-zero payoff, risk-neutral probability of being knocked in, and no arbitrage price of the call.

The second problem asked to price a Mountain Altiplano Call with given parameters, using a 3-period binomial option pricing model. The Mountain Altiplano call is a vanilla option combined with a compensatory coupon payment if the underlying security never reaches the strike price during a given period.

The final problem asked to price a Hit and Miss Box option given parameters, using a 4-period binomial option pricing model. This option has payoff of 1 if in a given time period, the stock price is within the expectant range of values and zero otherwise, for the hit box case. It is the opposite for the miss box case.

### Binomial and Black Scholes Option Pricing using Basic Monte Carlo Methods ([link](https://github.com/rohitpenumarti/University-Projects/blob/master/Undergrad/PSTAT%20176/Homeworks/Homework%202/Penumarti.Rohit.HW2.ipynb))
This assignment had a few problems involving option pricing under the binomial and Black-Scholes models using monte carlo methods.

The first problem asked to price a 26-period european put and call with given parameters using the binomial model. This process was repeated 10 times to achieve the average estimate and variance in the measurement.

The second problem asked to price a 30-period lookback option with given parameters using the binomial model. The final answer was calculated with a 99% confidence interval and antithetic variates to reduce variance in the estimate.

The next problem asked to price european call with maturity of half a year, using the Black-Scholes model with given parameters. Using 25 sample paths, an estimate was calculated with a 95% confidence interval. Then quasi-monte carlo was also used to calculate a deterministic estimate for the option price.

The last problem asked to price a basket option with one year maturity under the Black-Scholes model with given parameters. Estimate was made with 98% confidence interval.

### Variance Reduction Analysis and Markowitz Mean-Variance Portfolio Optimization ([link](https://github.com/rohitpenumarti/University-Projects/blob/master/Undergrad/PSTAT%20176/Homeworks/Homework%203/Penumarti.Rohit.HW3.ipynb))
This assignment had a few problems involving variance reduction techniques and monte carlo methods, Markowitz Mean-Variance portfolio optimization.

The first problem asked to use stratified sampling to reduce variance in the estimate for the price of an out of the money call with given parameters under the Black-Scholes model. Strata were given and estimate was calculated along with standard error.

The second problem asked to price a stop-loss contract like those used in medical insurance. Parameters of the contract were given probability that insurer would incur cost, expected cost to insurer, and probability of insurer cost greater than $100 was calculated.

The next three problems involved a mix of a few problems involved mean-variance portfolio optimization. These mix of problems included generating plots of the efficient frontier for a given set of data, calculating weights for maximum portfolios, finding minimum variance for a given target return, and market portfolio calculation.

### CAPM ([link](https://github.com/rohitpenumarti/University-Projects/blob/master/Undergrad/PSTAT%20176/Homeworks/Homework%204/Penumarti.Rohit.HW4.ipynb))
This assignment involved one coded problem on CAPM. It provided daily closing prices for Microsoft, IBM, and Hasbro over the past year. With these market data, the task was to obtain the monthly average return, variance and covariance among the three assets over the last six months. Then, the next task was to calculate the weights of the market portfolio along with its risk and return. These were then repeated for the first six months and then for the whole year.

### American Option Pricing ([link](https://github.com/rohitpenumarti/University-Projects/blob/master/Undergrad/PSTAT%20176/Final%20Project%20Report.ipynb))
For this project, we had to choose a stock to price an option with a set strike and expiration. We chose Google and chose to price an American put option with strike 1440 and expiration of one year. Using data from the past year, calculated the volatility in the stock price, then simulated stock paths, and then calculated the european option price for reference. Next, to estimate the option price for the American put, we used the Longstaff-Schwartz method for American option pricing. To do so, we used a polynomial regression model to fit continuation values at the nodes. From that we are able to calculate the price and variance in the estimate. Finally, to create a more accurate solution, we introduced control variates and applied it to the algorithm to reduce variance in our estimate.
