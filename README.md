# Micro_Price Notebooks

## 1. data_collection
Collect 5 hours of SH and SDS data (frequency was 10 seconds, now updated to shorter interval) from Interactive Broker.

## 2. data_exploration
Explore the states of cointegration residual and imbalances.

## 3. Markov_estimation
Construct the transition matrix given residual and imbalance states.

## 4. Micro_price
Compute the micro price of SH and SDS.

## 5. simulations
1. 1st simulation: simulate prices given the transition matrix.
2. 2nd simulation: simulate expected price movement for each state.

## 6. compare_micro_and_simulation
1. Plot the difference between Markov adjustment and simulated price movement.
2. Plot imbalance vs exp price movement for Markov estimation and simulation, given or averaging the other imbalance state.

## 7. trading_in_simulation
A simulated trading based on artificially defined trasition matrices. Can be used as a toy model.

## 8. Execution_Algos_train_DATE_test_DATE
Four execution algos with training and testing results.
