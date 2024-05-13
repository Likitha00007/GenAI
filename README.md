# Financial Data Chatbot

This Python-based financial data chatbot allows users to easily access financial information about specific companies for selected fiscal years. Utilizing a user-friendly command-line interface, this chatbot provides immediate responses to queries regarding various financial metrics.

## Project Overview

The chatbot is capable of fetching and displaying data for Apple, Microsoft, and Tesla for the fiscal years 2021 through 2023. It can answer questions related to total revenue, net income, total assets, total liabilities, and cash flow from operations, including their respective growth rates over the previous year.

## Data Analysis

The chatbot leverages data from a CSV file named `Finstatements_Final.csv`, which contains detailed financial statements of the covered companies. Each query processed by the chatbot performs data retrieval and analysis operations to fetch the requested metric. 

### Metrics Analyzed
- **Total Revenue**: Analyzes the total sales and other revenue for the year.
- **Net Income**: Determines profit after all expenses, taxes, and costs have been subtracted from total revenue.
- **Total Assets**: Summarizes the total value of assets owned by the company.
- **Total Liabilities**: Computes the total of all legal debts and obligations.
- **Cash Flow from Operations**: Focuses on the cash inflows and outflows from the company's core business operations.

For growth metrics, the chatbot calculates the percentage change from the previous year's data, providing insights into the financial health and trajectory of the company.

## Features

- **Data Scope**: Query financial metrics for major companies like Apple, Microsoft, and Tesla.
- **Time Range**: Access financial data from the years 2021 to 2023.
- **Metrics Supported**:
  - Total Revenue and Revenue Growth
  - Net Income and Net Income Growth
  - Total Assets and Assets Growth
  - Total Liabilities and Liabilities Growth
  - Cash Flow from Operations and Growth in Cash Flow from Operations
- **User-Friendly Interface**: Simple command-line interactions to receive data promptly.
- **Growth Metrics**: In addition to absolute figures, users can query for growth percentages to analyze year-over-year developments.

