---
layout: page
title: Quantitative Research
description: Commodity storage contract, Credit risk analysis
img: assets/img/quant.png
importance: 1
category: work
related_publications: false
---

# Project Overview

The goal of this project is to develop a **prototype pricing model** for a natural gas storage contract. This model will allow users to evaluate the financial viability of storing gas by calculating the net value of a contract based on injection and withdrawal schedules, gas prices, storage costs, and operational constraints. Initially, the model will be used manually by analysts with oversight to explore options with clients. Eventually, it may evolve into a fully automated quoting system.

---

## Objectives

1. **Develop a Pricing Framework**: Create a robust function to calculate the net value of a gas storage contract, accounting for cash flows related to gas injection, storage, and withdrawal.
2. **Incorporate Market Dynamics**: Use historical and forecasted gas price data to provide accurate and realistic pricing.
3. **Ensure Generalization**: Design the model to handle multiple injection and withdrawal schedules while respecting operational constraints like maximum storage capacity and rates.
4. **Prototype Validation**: Test the prototype with sample inputs to ensure accuracy and reliability before scaling for production use.
5. **Enable Future Automation**: Build a foundation for transitioning the prototype into a fully automated system.

---

## Key Components

1. **Data Processing and Visualization**:
   - Load and preprocess historical natural gas price data.
   - Visualize historical prices and their autocorrelation to identify patterns and trends.

2. **Price Forecasting**:
   - Use an ARIMA model to predict future gas prices based on historical data.
   - Provide a forecast for a specified period to inform contract pricing decisions.

3. **Pricing Function**:
   - **Inputs**:
     - Injection dates and rates.
     - Withdrawal dates and rates.
     - Maximum storage capacity.
     - Storage costs per unit.
     - Prices on specified dates.
   - **Outputs**:
     - Net value of the storage contract, calculated as:
       \[
       \text{Net Value} = \text{Total Withdrawal Revenue} - \text{Total Injection Cost} - \text{Total Storage Cost}
       \]

4. **Validation and Testing**:
   - Use sample inputs to test the function.
   - Verify results against expected outputs for edge cases (e.g., exceeding storage capacity, missing price data).

---

## Technology Used

1. **Programming Language**: Python
   - Chosen for its rich ecosystem of libraries for data analysis, visualization, and machine learning.

2. **Libraries**:
   - **Pandas**: For data manipulation and analysis.
   - **NumPy**: For numerical computations.
   - **Matplotlib**: For data visualization.
   - **Statsmodels**: For time series modeling (ARIMA).
   - **Datetime**: For handling and processing date inputs.

3. **Modeling Approach**:
   - ARIMA (AutoRegressive Integrated Moving Average) for time series forecasting.
   - Simple linear calculations for cash flow analysis in the pricing function.

4. **Visualization Tools**:
   - Historical price trends.
   - Forecasted prices with confidence intervals.

5. **Github Link**:
    - https://github.com/washwin/Quantitative_research
---

## Sample Workflow

1. **Data Preparation**:
   - Load historical price data from a CSV file.
   - Process dates and sort data chronologically.

2. **Price Forecasting**:
   - Fit an ARIMA model to historical prices.
   - Generate a 12-month price forecast.

3. **Contract Pricing**:
   - Input injection/withdrawal schedules, rates, storage constraints, and forecasted prices.
   - Calculate total injection costs, storage costs, and withdrawal revenues.
   - Output the net value of the contract.

4. **Testing**:
   - Use predefined scenarios to validate the function.
   - Ensure the function handles edge cases (e.g., missing price data, exceeding storage limits).

---

## Deliverables

1. **Pricing Function**:
   - A Python function that calculates the net value of a storage contract based on user inputs.

2. **Data Visualizations**:
   - Historical and forecasted price trends.
   - Confidence intervals for forecasted prices.

3. **Documentation**:
   - Detailed explanation of the pricing methodology.
   - Instructions for using the function and interpreting results.

4. **Validation Report**:
   - Test cases with sample inputs and outputs.
   - Analysis of the function’s performance and accuracy.

---

