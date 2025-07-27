# Blockhouse Work Trial Task

This repo contains my submission for the Blockhouse trading task.

## 📄 Files
- `blockhouse_task.ipynb`: All code for modeling slippage `gₜ(x)` and allocating trades
- `writeup_model.pdf`: Description of the slippage model
- `writeup_optimization.pdf`: Explanation of the allocation strategy

## ✅ Instructions
Run the notebook cell-by-cell. It will:
1. Load MBP-10 order book data
2. Model temporary slippage `gₜ(x)`
3. Optimize a 10,000-share order using greedy cost-minimization
