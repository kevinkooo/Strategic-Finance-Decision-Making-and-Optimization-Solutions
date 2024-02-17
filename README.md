# Strategic Finance Decision-Making and Optimization Solutions

In this project, we will address two financial optimization problems, short-term financing for the company and currency arbitrage trading, by turning the business problems into linear programming problems and applying Julia JuMP solver to find the optimal solutions.

Author: [Sally Lee](https://github.com/sallylee0801), [Kevin Ko](https://github.com/kevinkooo)

Affiliation: The University of Chicago

The README contains only a brief overview of our goals, investigation process, analysis, and recommendations.

For detailed documentation/analysis/findings, please refer to the [report](https://github.com/sallylee0801/Strategic-Finance-Decision-Making-and-Optimization-Solutions/blob/main/Strategic%20Finance%20Decision-Making%20and%20Optimization%20Solutions.pdf).

## Business Objective
We aim to provide optimal financial solutions for companies to make strategic decisions in short-term financing and currency arbitrage trading. By maximizing cash flow and profitability, companies can improve financial performance through making informed decisions.

## Data Source
We utilized the data and constraints described in the [Data Source](https://github.com/sallylee0801/Strategic-Finance-Decision-Making-and-Optimization-Solutions/blob/main/01.%20Raw%20Data%20Set/Data%20Source.pdf).

## Approach
We formulated both financial decision problems as LP models to determine optimal solutions. For short-term financing, we determined optimal borrowing amounts between two financing instruments to maximize cash flow. For currency arbitrage trading, we identified opportunities to buy and sell currencies to maximize profit within specified constraints.

## Insights: We identified optimal solutions for the short-term financing and currency trading problems respectively:
1. We identified optimal borrowing amounts between bonds and credits for each month to maximize cash flow. The analysis revealed strategic borrowing decisions to navigate negative cash flows while minimizing borrowing costs during positive cash flow periods.

![image](https://github.com/sallylee0801/Strategic-Finance-Decision-Making-and-Optimization-Solutions/assets/121594845/d292afd3-9e8d-4fc3-b7ae-818e51d044b1)

2. We identified the optimal arbitrage amount and trade executions involving leveraging available funds to buy and sell currencies cyclically to achieve maximum profit.

![image](https://github.com/sallylee0801/Strategic-Finance-Decision-Making-and-Optimization-Solutions/assets/121594845/f76d7a86-c00c-4011-b0f5-dbc9c7a73b96)

## Recommendations
Based on our insights, we recommend adopting dynamic cash management strategies and exploiting opportunities to cyclically buy and sell currencies to reach our intended goal of maximizing cash flow and profitability for the company.

## Limitations
Transaction costs were not considered in currency arbitrage trading analysis, which may affect the feasibility of the proposed solutions in real-world scenarios.
