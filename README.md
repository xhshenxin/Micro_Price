# Micro_Price Notebooks

## data_collection
Collect 5 hours of SH and SDS data (frequency was 10 seconds, now updated to shorter interval) from Interactive Broker

## data_exploration
Explore the states of cointegration residual and imbalances

## Markov_estimation
Construct the transition matrix given residual and imbalance states

## Micro_price
Compute the micro price of SH and SDS

## simulations
1. 1st simulation: simulate prices given the transition matrix
2. 2nd simulation: simulate expected price movement for each state

## compare_micro_and_simulation
1. Plot the difference between Markov adjustment and simulated price movement
2. Plot imbalance vs exp price movement for Markov estimation and simulation, given or averaging the other imbalance state
