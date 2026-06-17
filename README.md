# Customer Segmentation with RFM Analysis | BigQuery PowerBI
A fully automated, behaviour-based customer segmentation pipeline built on Google BigQuery and visualised in Power BI. This project uses RFM (Recency, Frequency, Monetary) analysis to score and rank customers into meaningful segments — helping businesses identify their most valuable customers, at-risk churners, and everyone in between.

## What it does:

Consolidates monthly sales tables into a single unified dataset using BigQuery
Calculates RFM values per customer (recency in days, purchase frequency, total spend)
Assigns decile scores (1–10) per dimension using NTILE() window functions
Combines scores into a single RFM composite score (range: 3–30)
Maps scores to named customer segments (Champions, Loyal, At Risk, Lost, etc.)
Connects to Power BI for interactive reporting and visual exploration

Tech Stack: Google BigQuery · SQL · Power BI
