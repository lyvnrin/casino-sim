# casino-sim

A Python-based simulation and data analysis project exploring casino game economics.

## Research Question

1. Would casinos generate more profit by running single-player tables instead of multi-player ones?

2. And as an extension: does investing in automated dealing and shuffling improve that margin further?

## Approach

Each game (blackjack, baccarat, poker) is simulated at scale across varying player counts.

The key variables are house edge, hands per hour, and throughput - and how they interact when you remove the friction of multi-player rounds.

**Extension**: The AI/automation extension models faster shuffle and deal speeds as a throughput multiplier, then estimates ROI against a hypothetical capital investment.

## Games

- Blackjack
- Baccarat
- Casino Hold'em (house-banked poker variant)

## Stack

- Python (numpy, pandas, matplotlib, seaborn)
- Jupyter notebooks

## Structure
```
simulations/   # game logic and simulation runners
notebooks/     # analysis per game + comparative notebook
data/          # generated CSVs (gitignored)
figures/       # saved plots
```

## Status

Work in progress. Starting with blackjack.
