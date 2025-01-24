# Monte Carlo Simulation: Arise AB Stock Price

## Project Overview

This project implements a Monte Carlo simulation to model and forecast the future stock price of **Arise AB**, a renewable energy company. The analysis was conducted by me in contribution to the Natural Resources Sector at **SSIF (Student-Managed Sustainable Investment Fund)** to evaluate the stock's potential price behavior under uncertainty.

## Objective

To simulate the potential future price movements of Arise AB stock based on historical data, enabling a better understanding of its risk and return profile and supporting investment decision-making.

## Methodology

1. **Data Collection**: 
   - Historical stock price data for Arise AB was obtained from a Yahoo Finance.
2. **Log Returns**:
   - Calculated daily log returns to model the price changes.
3. **Monte Carlo Simulation**:
   - Generated multiple simulations of future price movements using:
     - Drift: Derived from the average historical return.
     - Volatility: Estimated from the standard deviation of historical returns.
   - Modeled stock prices using the equation:
     \[
     S_t = S_0 \cdot e^{(drift + \sigma \cdot Z)}
     \]
     where \(Z\) represents random values from a standard normal distribution.
4. **Scenario Analysis**:
   - Ran thousands of iterations to create a range of potential outcomes.
   - Visualized results to identify potential price distributions and risks.

## Key Results

- Simulated stock price distributions highlight the potential range of outcomes over the chosen time horizon.
- Risk metrics such as **Value at Risk (VaR)** and **Expected Shortfall (ES)** were derived from the simulated results.
- Insights were provided to the team for making informed decisions regarding Arise AB as an investment option.

## Tools & Libraries

- **Python**: Core programming language
- **NumPy**: For numerical computations
- **Pandas**: For data manipulation
- **Matplotlib & Seaborn**: For visualizations

## Insights for SSIF

1. The Monte Carlo simulation provides a probabilistic framework for assessing potential risks and returns.
2. The methodology is scalable and can be applied to other stocks or assets in the portfolio.
3. Findings aid in making data-driven investment decisions in line with SSIF's sustainability goals.

## Authors

- Mary Nghi Le, **Analyst, Natural Resources Sector**

## Acknowledgments

This is not a full equity research on Arise AB. Natural Resources Sector owns the complete report.
