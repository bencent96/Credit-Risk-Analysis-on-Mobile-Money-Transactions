# Credit-Risk-Analysis-on-Mobile-Money-Transactions
Credit risk analysis based on mobile money transaction data, evaluating user cash flows through inflows and outflows. The project includes exploratory data analysis, cash flow metrics, and delinquency risk assessment to inform lending decisions. Implemented in R with visualizations and statistical analysis.

Overview

This project analyzes credit risk based on mobile money transaction data. The goal is to evaluate user cash flow by examining inflows (deposits) and outflows (expenditures) and provide insights into potential credit risk factors.
Contents

    Introduction: Overview of the analysis objectives and the significance of evaluating credit risk in mobile money transactions.
    Data Preparation: Steps to load, clean, and structure the transaction dataset.
    Exploratory Data Analysis (EDA): Summary statistics and visualizations of transaction trends.
    Credit Risk Metrics: Analysis of cash flow and delinquency risk, including net cash flow calculations.
    Conclusion: Key findings and recommendations based on the analysis.

Requirements

This analysis is implemented in R and requires the following libraries:

    tidyverse
    lubridate
    ggplot2
    knitr

You can install the necessary packages using the following command:

R

install.packages(c("tidyverse", "lubridate", "ggplot2", "knitr"))

Usage

    Clone this repository to your local machine:

    bash

    git clone https://github.com/yourusername/mobile_money_credit_risk_analysis.git

    Ensure the transactions.csv file is in the same directory as your R script.

    Open the R script and run the analysis to explore the data and view the results.

Results

The analysis includes:

    Summary statistics for inflows and outflows.
    Visualization of daily inflows and outflows.
    Calculation of net cash flow over time.
    Identification of days with negative net cash flow as potential credit risks.
    Lending decisions based on total net cash flow.

Acknowledgments

    Data Source: Mobile Money Transaction Data
    Special thanks to the R community for their invaluable tools and resources.
