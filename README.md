# Inventory Forecasting Simulation

**Project:** Does a forecast-based inventory policy beat a simple rule?

**Scenario:** A hypothetical inventory planner for a UK-based online gift-ware retailer, using about two years of real transaction data from the public UCI Online Retail II dataset. Results are backtest results on public data with assumed costs, not real savings.

**Question:** Compared with a simple baseline ordering rule, does a forecast-driven policy reduce stockouts and total cost?

**Method:** SQL for data storage and cleaning, Python for forecasting and inventory simulation, and a dashboard for results. Demand is aggregated to weekly units per product (top 30 to 50 products). Policies are tested on a held-out final 6 months.

**Assumptions:** Holding cost, stockout cost, and lead time are assumed values.

**Data:** [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii), UCI Machine Learning Repository, licensed CC BY 4.0. Raw files are not included in this repo; download them from the link above. Changes made: cancellations and non-product lines removed, data aggregated to weekly units per product.

**Status:** In progress.
