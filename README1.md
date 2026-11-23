# Nigeria Electricity Sector Performance Dashboard (2025)

An interactive dashboard analysing the financial and operational performance of Nigeria's electricity distribution companies (DisCos), using data extracted from quarterly reports published by the Nigerian Electricity Regulatory Commission (NERC).

## Live Dashboard

[View the Interactive Looker Studio Dashboard](https://datastudio.google.com/reporting/44e86982-a065-416a-8a99-8b7f2355af0c)

## Dashboard Pages

### 01 — Executive Overview
Provides a high-level view of electricity distribution performance through:
- Total electricity billings
- Revenue collected
- Overall collection efficiency
- Overall customer metering rate
- Revenue collection by DisCo
- Billing versus revenue comparison
- Customer complaints by DisCo
- ATC&C losses
- Registered versus metered customers

### 02 — Quarterly Performance Analysis
Examines performance across the four quarters of 2025 through:
- Quarterly billing and revenue trends
- Collection efficiency trends
- National metering rate trends
- Quarterly customer complaints
- ATC&C loss trends
- DisCo quarterly performance breakdown table

Interactive Quarter and DisCo filters allow users to explore the data.

## Data Source

- Nigerian Electricity Regulatory Commission (NERC) quarterly reports
- Reporting period: Q1–Q4 2025
- Workbook: `NERC_ELECTRICITY_ANALYTICS`
- Consolidated worksheet: `Cleaned Data`

## Key Metrics and Methodology

**Overall Collection Efficiency**

Revenue Collected ÷ Total Billings × 100

**Overall Metering Rate**

Total Metered Customers ÷ Total Registered Customers × 100

Percentage metrics are calculated using the underlying totals or averages as appropriate. They should not be summed.

## Data Quality Considerations

The extracted data may contain missing or inconsistent values. These should be checked against the original NERC reports before being used for definitive conclusions.

Missing values are not automatically treated as zero. Some reported figures may require further reconciliation.

## Tools

- Google Sheets — data preparation and consolidation
- Looker Studio — interactive dashboard and visualisation
- Microsoft Excel — data inspection and validation
- GitHub — project documentation and version control

## Project Purpose

To transform electricity-sector reporting data into accessible insights that support performance monitoring, comparison across DisCos, and evidence-based decision-making.
