# TEAM ONE - PROJECT TWO "ALGO-TRADING MODEL"

![image](https://user-images.githubusercontent.com/108433370/196785794-1f9f88d8-44bf-47f6-9a6c-0ddb95b1e069.png)

Team Members:

Adam Cooke

Nia Robinson

Ros Tiamzon

================================================================================================================

# PROJECT GOAL

We want to create an Algo-Trading model/platform that individuals can have access to (via subscription, etc.) at an affordable price, where they can choose a specific type of asset (stocks, funds, bonds, digital assets, derivatives, swaps, options, futures, forwards, etc), and match with or explore trading strategies they like, and make profit with their excess cash.

================================================================================================================

# MODEL, TOOLS, LIBRARIES

SK-Learn

PyTorcj

Panda

Numpy

YFinance

Finta

hvplot

matplotlib

================================================================================================================

# ABOUT THE PROJECT

Our project is to create a profitable trading algorithm - model that anyone can use or subscribe to.

Users can choose a specific type of asset, match with a trading strategy, predict prices and make a profit using our trading algo - model/platform.  

For this project, we used the momentum trading strategy for an exchange traded fund (SPY), bollinger bands for a cryptocurrency (bitcoin), and pullback strategy for futures contracts (commodity - orange juice). 

We calculated standard deviations, sharpe ratios and cumulative returns for each type of asset. 

We used SK-Learn and PyTorch libraries to create prediction models for future prices.


================================================================================================================

# DATA PREPARATION - MODEL TRAINING 

Step 1:

Take in the data via the Yfinance library and turn it into a data frame, calculate the necessary information based on the specific strategy used. PMAVG/VMAVG vs BB Lower-Upper

Step 2:

Determine  entry and exit points based on the calculations used (trading signals) and make a plot to help visualize the trading patterns.

Step 3: 

Use a for loop along with the entry and exit points to make an algorithmic trading process that also keeps track of profits and losses over time.

Step 4: 

COLLECT > SCALE > TRAIN - TEST- SPLIT > PREDICT

Step 5: 

Use a for loop to run the model and have it so that every 1000 epochs it prints out the model loss. Then plot the results of the model that compare the actual price vs the model’s predicted price.


================================================================================================================

# RESULTS





