# Monte Carlo Engine -- Probability & Simulation

## Objective

I used Monte Carlo simulation to estimate probabilities and portfolio risk, and to check how the error of a simulation shrinks as the number of samples grows.

## Methodology

- I simulated 10,000 coin flips and plotted the running share of heads to watch it settle toward one half.
- I simulated 10,000 Monty Hall games and counted how many were won by switching.
- I simulated a disease screening test on 100,000 people, using a prevalence of 1%, a sensitivity of 95% and a specificity of 90%, then measured what share of positive tests were actually sick people.
- I computed Monte Carlo Value at Risk (VaR) and Expected Shortfall (ES) for a $1M portfolio at the 95% level.
- I estimated pi by simulation at increasing sample sizes and checked that the error shrinks like 1/sqrt(n).

## Key Findings

- Coin flips: the running share of heads moved toward one half as the number of flips grew.
- Monty Hall: switching won [YOUR VALUE] of the 10,000 games.
- Disease screening: [YOUR VALUE]% of positive tests were sick people, even though the test has 95% sensitivity and 90% specificity. The low prevalence of 1% is the reason.
- Portfolio risk ($1M portfolio): 95% VaR = $[YOUR VALUE] and 95% ES = $[YOUR VALUE].
- Pi estimate: the Monte Carlo error shrank like 1/sqrt(n), so cutting the error in half takes about four times as many samples.
