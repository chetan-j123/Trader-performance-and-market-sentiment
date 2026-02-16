# Trader Performance vs Market Sentiment

This notebook analyzes how Bitcoin Fear & Greed Index sentiment relates to trader behavior and performance on Hyperliquid. It covers:
- Data cleaning & merging
- Performance comparison across sentiment regimes
- Behavioral changes (trade frequency, position size, long/short bias)
- Trader segmentation (frequent, high‑risk, consistent winners)
- Actionable trading rules
- Bonus: XGBoost model to predict next‑day profitability (with focus on detecting losing days)
- whole about project is listed with code in notebook 
## Run on Google Colab (Recommended)

1. **Download the notebook** from this repository.
2. Go to [Google Colab](https://colab.research.google.com/).
3. Click **File → Upload notebook** and select the downloaded file.
4. **Runtime → Run all** (or run cells one by one).

The notebook automatically downloads both datasets using `gdown` – no manual data download needed.

## Local Setup (Optional)

If you prefer to run locally:

type command -pip install -r requirements.txt on terminal
jupyter notebook
