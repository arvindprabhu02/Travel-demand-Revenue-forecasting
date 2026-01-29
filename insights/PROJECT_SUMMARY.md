**Integrated Project Summary: Hotel Demand Forecasting & Financial Scenario Analysis**

This project develops an end-to-end analytical framework that connects hotel booking data to demand forecasting, capacity utilization, and financial decision-making for travel and platform-based businesses. The work is structured across four notebooks, each building logically on the previous stage to move from raw data to actionable business insights.

**1. Data Cleaning and Feature Preparation**

The analysis begins with rigorous data cleaning to ensure analytical validity. Invalid observations such as negative ADR values, zero-night stays, and inconsistent booking records are removed or corrected. Key variables including net bookings, stay duration, weekly room nights, and utilization metrics are engineered to align operational and financial interpretations. The cleaned dataset is aggregated to a weekly level to support time-series modeling and capacity analysis.

**Outcome:** A reliable, analysis-ready dataset that reflects realized demand rather than noisy gross bookings.

**2. Exploratory Demand and Booking Behavior Analysis**

Exploratory analysis identifies structural differences between City and Resort Hotels. Resort demand shows strong, stable seasonality, while City demand is more volatile and sensitive to external shocks. Cancellation rates materially affect realized demand, reinforcing the need to focus on net bookings. Lead-time distributions are heavily right-skewed, revealing a trade-off between early demand visibility and cancellation risk. ADR patterns exhibit clear seasonality, highlighting revenue volatility and pricing leverage.

**Outcome:** Clear justification for forecasting net demand, incorporating seasonality, and separating operational and financial risk profiles by hotel type.

**3. Demand Forecasting and Scenario Modeling**

Multiple forecasting approaches are evaluated. A flat benchmark model is used for validation, while STL-based decomposition combined with ETS forecasting captures evolving trends and seasonality more effectively. Rolling one-step-ahead validation is applied to assess short-term accuracy and avoid overfitting. Forecasts are translated into base, upside, and downside demand scenarios to reflect uncertainty rather than relying on point estimates.

**Outcome:** Robust demand forecasts that balance realism and uncertainty, suitable for operational planning rather than purely statistical accuracy.

**4. Financial Impact and Capacity Scenario Analysis**

Demand forecasts are mapped to capacity utilization, revenue, and profit using transparent cost assumptions. Utilization analysis highlights frequent stress periods for City Hotels and structurally lower utilization for Resort Hotels. Scenario-based profit modeling reveals strong sensitivity to demand fluctuations, particularly on the downside. Break-even analysis and profit distributions emphasize the financial risks of fixed capacity decisions under uncertain demand.

**Outcome:** A direct link between forecasting uncertainty, capacity risk, and financial outcomes, enabling scenario-aware decision-making.

**Integrated Business Takeaways**

City Hotels face higher capacity stress and require proactive operational risk management.
Resort Hotels exhibit lower utilization but higher profit volatility driven by seasonality.
Scenario-based planning materially outperforms point forecasts for both operations and finance.
Demand forecasting delivers maximum value when embedded into capacity and financial models, not viewed in isolation.

**Final Deliverables**

The analysis culminates in two role-specific Tableau dashboards:
1) Operations Capacity & Demand Risk Dashboard for utilization and stress monitoring
2) Financial Performance & Scenario Sensitivity Dashboard for profitability and risk assessment

Together, these components demonstrate how data-driven forecasting can inform both operational resilience and financial strategy in travel and platform services.
