# Trader Performance vs Market Sentiment Analysis

This project analyzes how trader performance changes across Fear and Greed market conditions.

## Key Findings

- Fear days show highest average trader profitability.
- Extreme Greed produces highest win rate.
- Extreme Fear reduces consistency and increases risk.

## Methodology

- Cleaned and standardized column names
- Converted timestamps to daily level
- Merged trader data with sentiment data
- Calculated daily PnL, win rate, and trade frequency per trader
- Compared metrics across Fear, Greed, Extreme Fear, and Extreme Greed
- Identified trader segments and behavioral patterns
  
## Strategy Recommendations

- Increase exposure during Fear periods.
- Reduce risk during Extreme Fear.
- Increase trading frequency only for consistent traders during Extreme Greed.

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab

## How to run

Open the notebook in Google Colab and run all cells.

## Data Note

The historical_data.csv file is large and not included in this repository due to GitHub size limits.

To run the notebook, download the dataset and place it in the data/ folder, or update the file path accordingly.
