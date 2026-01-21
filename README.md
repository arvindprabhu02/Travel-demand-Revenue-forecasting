# Travel-demand-Revenue-forecasting
Project Overview

This project analyzes real hotel booking data to forecast travel demand and revenue for a platform business and translate forecasts into capacity, cost, and margin insights for planning and budgeting decisions.

Business Objective

To build a forecasting-driven decision framework that helps a travel platform:

Anticipate seasonal demand

Align pricing and capacity

Evaluate revenue and margin sensitivity under uncertainty

Dataset

The analysis uses real, anonymized hotel booking data released for academic research, containing multi-year booking records from a city hotel and a resort hotel in Portugal. The dataset captures booking demand, pricing (ADR), cancellations, stay duration, and customer origin, making it suitable for demand and revenue forecasting in a travel platform context.

Demand analyzed at a weekly level, segmented by City vs Resort hotels.

Methodology

Exploratory Analysis

Seasonality, volatility, cancellations, and pricing behavior

Demand Forecasting

Weekly net bookings using seasonal time-series models

Revenue Modeling

Demand × ADR scenarios

Capacity & Margin Analysis

Utilization, break-even, and profitability

Scenario Testing

Base, peak demand, and demand shock cases

Finance Translation Layer

Operational analytics are performed in dataset currency units.
An additional finance layer translates results into INR using conservative assumptions to illustrate budgeting, cost, and margin implications.

Key Outputs

Weekly demand and revenue forecasts

Capacity utilization insights

Margin and break-even analysis

Executive-ready dashboard with operational vs finance views

Tools Used

Python (pandas, statsmodels)

SQL-style aggregation

Tableau

Excel-style financial modeling

Key Takeaway

Forecasting is valuable only when it enables decisions. This project demonstrates how analytics can be translated into finance and operational actions for platform businesses.
