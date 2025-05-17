# strategic-summary-powerBI-report


Power BI Project:

Download the dataset (3 CSV files) from the Drive folder linked here:
https://drive.google.com/drive/folders/1oLTNQo4d-1QfzlwXHzdIJrDsyrunaKtk



Use 3 strategy CSVs. Each file has:
symbol, entry_datetime, exit_datetime, entry_type, pnl


Combine all 3 files into one table


Add a column strategy_name to track which strategy the trade came from


Page 1: Strategy Summary (Main Page)



Table with:
strategy_name, Total PnL, Win Count (pnl>0), Loss Count (pnl<0)


Add drillthrough to Page 2 using strategy_name


Page 2: Detailed Report (Drillthrough Page)



Show data only for selected strategy


Add cumulative_pnl (running total by entry_datetime)


Add entry hour column (hour of entry_datetime)


KPI cards: Total PnL, Win Count, Loss Count


Line chart: Cumulative PnL vs entry_datetime


Bar chart: PnL by Hour of day (from entry_datetime))


Table: All trade details (Columns: symbol, entry_datetime, exit_datetime, entry_type, pnl, cumulative_pnl)


Add a slicer to filter trades by entry_datetime (date range)


