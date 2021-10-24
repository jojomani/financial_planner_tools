# Financial_Planner_Tools
Financial Planner for Emergencies and Retirement

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years using Alpaca API call to get historical price data for use in Monte Carlo simulations.

Please be sure to install all the prerequisites (libraries) before running the program:

- `pip install pandas`
- `pip install dotenv`
- `pip install alpaca_trade_api`
- `pip install MCForecastTools`

The other libraries, **json, requests, and os** should be installed by default. If not, run the same *pip install "libraby name"* command.

After completing the prereq, run the [financial_planning_tools.ipynb](financial_planning_tools.ipynb) notebook. See following screenshots as example outputs of the Monte Carlo simulations:

![500 Simulations Monte Carlo](images/5-4-monte-carlo-line-plot.png)

Below is an example output of the Distribution of Final Cumulative returs of all 500 Simulations:

![Distribution of Final Cumulative returs of all 500 Simulations](images/5-4-monte-carlo-histogram.png)

----

@jojomani - by Johann Maiga