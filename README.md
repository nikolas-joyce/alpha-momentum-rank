# alpha-momentum-rank

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-momentum-rank/blob/main/notebooks/alpha_momentum_rank.ipynb)

> Cross-sectional momentum rank alpha signal

> Ranks each ticker by its 1-month / 12-month return relative to the universe. The top 30% by rank (≥70th percentile) enter long; the bottom 30% (≤30th percentile) enter short. This cross-sectional approach is robust to market-wide moves and captures relative strength across asset classes.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | L3/S3 signal generation |
| 4 | Returns & performance |
| 5 | Per-ticker breakdown |
| 6 | Parameter sensitivity (formation period, rank threshold) |
| 7 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

