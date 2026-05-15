# Momentum Strategy

Small research notebook for testing a weekly TAO momentum idea.

The notebook loads `TAO-1w.csv`, builds log-return and lagged-direction
features, uses the previous week's return direction as a trading signal, and
plots cumulative strategy performance with fee assumptions.

## Files

- `momentum_strategy.ipynb` - exploratory analysis and backtest.
- `TAO-1w.csv` - weekly OHLCV data used by the notebook.

## Running

Install the notebook dependencies, then open the notebook:

```bash
pip install jupyter pandas numpy matplotlib
jupyter notebook momentum_strategy.ipynb
```

The notebook expects `TAO-1w.csv` to stay in the project root.
