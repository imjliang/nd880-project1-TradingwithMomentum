# Trading with Momentum Project

In this project, we will implement a trading strategy on your own, and test to see if it has the potential to be profitable. We will be supplied with a universe of stocks and time range. We will then compute the signal for the time range given and apply it to the dataset to produce projected returns. Finally, We will perform a statistical test on the mean of the returns to conclude if there is alpha in the signal. For the dataset, we'll be using the end of day from Quotemedia.

Momentum trading is the practice of buying and selling assets according to the recent strength of price trends. It is based on the idea that if there is enough force behind a price move, it will continue to move in the same direction.

When an asset reaches a higher price, it usually attracts more attention from traders and investors, which pushes the market price even higher. This continues until a large number of sellers enter the market – for example, when an unforeseen event causes them to rethink the asset’s price. Once enough sellers are in the market, the momentum changes direction and will force an asset’s price lower.

### Main Files: Jupyter Structure

```
├── Resample adjusted prices from daily to monthly
├── Compute log returns
├── Shift to get previous or future returns in the time series
├── Generate trading signals by rank of returns, i.e., long top performing stocks and short bottom performing stocks
├── Compute net returns of portfolio
└── Comute T-test on returns to see if it's profitable
```

### Authors

Jinjin Liang authored the main functions in `project_1.ipynb`, and this README. All other project files were created by [Udacity](https://www.udacity.com/).
