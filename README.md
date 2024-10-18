# Freqtrade Strategies Repository

This repository is created for **Freqtrade strategies**, focusing on **backtesting**, **hyperoptimization**, and **FreqAI** modes. It includes various strategies developed for both **Binance** and **Bybit** futures and spot trading.

## Key Features:
- **Backtesting**: Test strategies against historical data to evaluate performance.
- **Hyperopt**: Tune strategy parameters to optimize results.
- **FreqAI**: Integrate AI and machine learning models to improve trading decisions.

## Strategies Included:
- **FollowTrendFutures**: A trend-following strategy for futures trading, compatible with Binance and Bybit. Uses 20-period SMAs for entry signals and incorporates trailing stop-loss and take-profit for risk management.

## Getting Started:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Install Freqtrade and dependencies following the [Freqtrade documentation](https://www.freqtrade.io/en/stable/).
3. Copy the strategy files into your Freqtrade `user_data/strategies` folder.
4. Run backtesting, hyperopt, or FreqAI as needed.

## Contributions:
Feel free to contribute new strategies or improve existing ones by creating a pull request!


