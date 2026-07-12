# Premier League Transfer Spending vs Club Financials

## Overview
This project investigates whether Premier League and European clubs that generate more revenue also spend more on player transfers, and explores how transfer spending is distributed across playing positions.

## The Question
Does a club's revenue predict how much it spends on transfers? And where does transfer money actually go by position?

## Data
- **transfers_history.csv** — ~15,000 individual transfers (2010–2026), including player, position, fee, and clubs involved
- **club_financials.csv** — revenue, wage bill, and net transfer spend per club per season

Source: Kaggle — Global Football Transfer Market 2010–2026

## Tools Used
- **Python** (pandas, matplotlib) — data cleaning, analysis, visualisation
- **SQL** (via DuckDB) — grouping and aggregation queries

## Key Findings
1. **Revenue and transfer spend are weakly-to-moderately correlated** (r = 0.34) — higher revenue clubs tend to spend more, but it's far from a strict rule.
2. **Some clubs spend far more than their revenue suggests** — Saudi Pro League clubs (Al-Nassr, Al-Hilal, Al-Ittihad) spend over 50% of revenue on transfers, more than Premier League giants.
3. **Some clubs are consistent net sellers** — Benfica, RB Leipzig, and Ajax show negative net spend relative to revenue, reflecting their reputations as talent-development clubs.
4. **Centre-backs and central midfielders account for the highest total spend**, but right-backs command the highest average fee per transfer.

## How to Run
1. Open the notebook in Google Colab
2. Upload `transfers_history.csv` and `club_financials.csv` when prompted
3. Run all cells

## Author
Harry



