# AI Trading Bot Optimisation

Bitcoin trading bot using GA, PSO, DE, and SA to optimise moving-average crossover strategies with backtesting and statistical comparison.

## Project Overview

This project builds and evaluates an AI-based Bitcoin trading bot using historical Bitcoin price data. The bot uses moving-average crossover signals to generate buy and sell decisions, then applies optimisation algorithms to improve trading strategy parameters.

The main aim was to compare how different optimisation algorithms perform when tuning trading strategy parameters and to evaluate whether the optimised strategies generalise well to unseen market data.

## Algorithms Used

- Genetic Algorithm
- Particle Swarm Optimisation
- Differential Evolution
- Simulated Annealing

## Key Features

- Historical Bitcoin data analysis
- Moving-average crossover trading strategy
- Train-test split for model evaluation
- Backtesting with transaction fees
- Portfolio performance comparison
- Convergence analysis
- Statistical comparison of optimisation algorithms

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Machine Learning
- Backtesting
- Optimisation Algorithms
- Data Analysis

## Files

- `ai-trading-bot-optimisation.ipynb` - Main Jupyter Notebook containing the implementation and analysis
- `bitcoin_data.csv` - Bitcoin historical price dataset used for backtesting

## How to Run

1. Download or clone this repository.
2. Open `ai-trading-bot-optimisation.ipynb` in Jupyter Notebook or Google Colab.
3. Make sure `bitcoin_data.csv` is in the same folder as the notebook.
4. Run the notebook cells from top to bottom.

## Results Summary

The optimisation algorithms improved training performance and showed the ability to search the trading strategy parameter space effectively. However, the results also showed that strong backtesting performance on training data does not always guarantee strong performance on unseen market data.

This highlights the importance of testing trading models carefully using unseen data, transaction fees, and realistic evaluation methods.

## Note

This project is for academic and educational purposes only. It is not financial advice or a real trading recommendation.
