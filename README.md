**Travel Platform Demand, Revenue & Capacity Forecasting**
**Project Overview**

This project analyzes real hotel booking data to forecast travel demand and revenue for a platform-style business and translate forecasts into capacity utilization, cost, and margin insights. The objective is to demonstrate how forecasting can be used not just for prediction, but for planning, budgeting, and decision-making in travel and platform services.

**Business Objective**

To build a forecasting-driven decision framework that helps a travel platform:
1) Anticipate seasonal and volatile booking demand
2) Align pricing and capacity with expected demand
3) Translate operational forecasts into finance-ready insights such as revenue, margins, and break-even analysis
4) Evaluate business outcomes under multiple demand scenarios

**Dataset Description**

The analysis uses a real, anonymized hotel booking dataset for studies in revenue management and demand forecasting.

Data Source: Real booking records from two hotels in Portugal:
One City Hotel
One Resort Hotel

**Data Characteristics**

Booking-level transactional data
Multi-year time span suitable for time-series analysis
Captures real-world travel dynamics such as:
Seasonality
Cancellations
Pricing variation
International demand mix

**Key Variables Used**

Arrival dates and stay duration (weekday and weekend nights)
Average Daily Rate (ADR)
Booking cancellation status
Lead time
Hotel type (City vs Resort)
Customer country of origin

The country variable represents the origin country of the traveler, reflecting inbound international demand rather than hotel location. Country information is used for diagnostic analysis only, not for forecasting.

**Analytical Scope**

Unit of Analysis: Weekly aggregation
Segmented by hotel type: City Hotel, Resort Hotel

**Core Metrics**

1)Gross bookings and net (non-cancelled) bookings
2)Room nights
3)Revenue proxy derived from ADR and room nights
4)Capacity utilization (based on clearly stated assumptions)

**Methodology**

**1. Exploratory Data Analysis**

i) Seasonality and trend analysis of bookings
ii) Cancellation behavior and demand volatility
iii) Pricing (ADR) behavior across peak and off-peak periods
iv) Diagnostic analysis of customer origin mix and lead times

**2. Demand Forecasting**

i) Weekly demand forecasting using seasonal time-series models
ii) Separate forecasts for City and Resort hotels
iii) Emphasis on interpretability and stability rather than model complexity

**3. Revenue Modeling**

i) Revenue derived from forecasted demand and ADR scenarios
ii) Volume vs price sensitivity analysis

**4. Capacity, Cost, and Margin Analysis**

i) Capacity utilization analysis using transparent assumptions
ii) Variable and fixed cost modeling
iii) Contribution margin and break-even analysis

**5. Scenario Analysis**

Three business scenarios are evaluated:
i) Base case forecast
ii) Peak demand scenario
iii) Demand shock scenario

Each scenario is traced through revenue, utilization, and margin impact.

**Finance Translation Layer**

Operational analytics are performed in dataset currency units to preserve methodological integrity.
A separate finance translation layer converts results into INR using conservative, clearly documented assumptions to illustrate:

**Budgeting implications**

1) Cost structures
2) Margin sensitivity
3) Break-even thresholds

Operational analytics and finance assumptions are intentionally kept separate.

**Dashboard Design**

An executive-style dashboard is designed with two distinct views:

1) Operational View:
Demand, revenue trends, and utilization in dataset currency

2) Finance View (INR):
Revenue, costs, margins, and scenario impact based on assumptions

This separation mirrors how operational and finance teams consume analytics in real organizations.

**Tools and Technologies**

Python (pandas, numpy, statsmodels)
SQL-style aggregation logic
Tableau for executive dashboards
Spreadsheet-style financial modeling concepts

**Key Takeaway**

Forecasting creates value only when it informs decisions.
This project demonstrates how demand forecasting can be translated into actionable financial and operational insights for a travel platform operating under seasonality and uncertainty.
