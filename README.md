# etl-pipeline-for-data-analysis-and-visualization
This project turns the Brazilian E‑Commerce Public Dataset by Olist into a clean, analytics‑ready star schema and ships ready‑made dashboards/KPIs. The pipeline: Downloads Olist CSVs via Kaggle CLI. Loads them into Microsoft SQL Server (read‑only source → stg schema).. Analyzes &amp; Visualizes with Power BI/Tableau;

End-to-end ETL/ELT for the Kaggle Olist dataset → MS SQL Server.
Scripts download the CSVs, bulk-load them into stg tables, build a star schema in wh with dbt-sqlserver, and power dashboards (Power BI/Tableau) plus an optional Streamlit app for quick KPIs.
