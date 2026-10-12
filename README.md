# econ3916-lab05-monte-carlo
# Monte Carlo Engine -- Probability & Simulation

## Objective

I used Monte Carlo simulation to study probability, conditional probability, financial risk, and how simulation accuracy changes with sample size.

## Methodology

- I simulated 10,000 coin flips and plotted the running share of heads.
- I simulated 10,000 Monty Hall games and compared staying with switching.
- I simulated a disease screening test for 100,000 people using a 1% prevalence rate, 95% sensitivity, and 90% specificity.
- I calculated Value at Risk and Expected Shortfall for a $1M portfolio.
- I estimated pi and checked whether Monte Carlo error decreased according to `1/sqrt(n)`.

## Key Findings

Switching doors won 6,694 of the 10,000 Monty Hall games. In the disease screening simulation, 9.2% of positive tests came from people who were sick. For the $1M portfolio, the 95% VaR was $19,494 and the 95% Expected Shortfall was $24,230. These results showed me how repeated simulation can estimate probabilities and measure financial risk.
