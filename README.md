# put-away-pallet-report

DC PUT AWAY PALLET REPORT

Overview:
This report tracks the daily Goods Receipt Notes (GRN) and Put Away Pallet activities in the distribution center (DC). It provides clear visibility into items that have been received and their current put-away status.

Technical Summary:

Data Source: Amazon Redshift (single table source)

Transformations: All logic handled within Power BI using DAX and calculated columns (no Power Query / M code).

Model: No relationships — all logic derived directly from the imported dataset.

Key Metrics:

Total GRN Count

Items with Pallet ID (Put Away / Not Put Away)

Items without Pallet ID

Report Features:

Dynamic date filtering (via slicers for GRN Confirm Date).

Visual indicators for total and incomplete pallet activities.

Auto-refresh note and data refresh timestamp for transparency.

Streamlined layout for control room / big screen monitoring.

Example Remark (below the title):
Records will appear when there are entries in the given date range.
Report auto-refreshes daily at 10 AM.
