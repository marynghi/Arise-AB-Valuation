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
    <img width="166" alt="image" src="https://github.com/user-attachments/assets/c757d17c-e434-4fb9-a1ca-c07cd609a688" />
     where \(Z\) represents random values from a standard normal distribution.
4. **Scenario Analysis**:
   - Ran thousands of iterations to create a range of potential outcomes.
   - Visualized results to identify potential price distributions and risks.

## Key Results

###Best & Worst Cases
1. Worst Case: SEK 8.85 per share
2. Average Case: SEK 40.01 per share
3. Best Case: SEK 148.06 per share
###Confidence Intervals
1 Sigma (1 S.D.): 68% confidence that the price after 250 days will fall between SEK 24.13 and SEK 55.88.
2 Sigma (2 S.D.): 95% confidence that the price after 250 days will fall between SEK 8.26 and SEK 71.76.
###Latest Price and Probabilities
Latest Price (S₀): SEK 37.10 per share
Probability of Price > Latest Price at Day 250: 50.35%
These results provide a robust framework for assessing potential future price movements, highlighting key risks and opportunities.

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
