# Vending Machine Inventory Analysis

## Business Problem

The company needs to understand inventory trends, product demand patterns, device utilization, and replenishment activity across its vending machine network.

Without this understanding, inventory planning becomes more difficult, increasing the risk of stockouts, inefficient replenishment decisions, and unnecessary operational costs.

These challenges can negatively impact business performance and reduce the accuracy of future demand forecasting efforts.


## Project Objectives

- Analyze demand trends over time.
- Evaluate replenishment frequency and spending patterns across vending devices.
- Identify top-performing products based on quantity dispensed.
- Investigate potential seasonal demand patterns using monthly sales activity.
- Generate business recommendations to support inventory planning and reduce stockout risk.


## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Visual Studio Code

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Time-Series Analysis
- Demand Forecasting
- Inventory Analysis
- Data Visualization
- Business Recommendations

## Key Findings

- Overall demand increased throughout the observed period despite periodic fluctuations.
- Device utilization was relatively balanced across machines.
- Restock frequency and utilization were not perfectly aligned, suggesting operational factors influence replenishment activity.
- Replenishment spending varied by device despite similar utilization patterns.
- Demand was concentrated among a small number of high-performing SKUs, with the top SKU significantly outperforming the rest of the catalog.

## Business Recommendations

- Monitor top-performing SKUs closely, as demand is concentrated among a small number of products.
- Review replenishment schedules for devices with high restock frequency but moderate utilization to identify operational inefficiencies.
- Continue tracking monthly demand trends to validate potential seasonality patterns.
- Consider expanding inventory planning efforts around top-demand products to reduce stockout risk.
- Investigate whether seasonal demand changes are driven by specific SKUs or broader customer purchasing behavior.

## Repository Contents

- `vending_analysis.ipynb` – Editable Jupyter Notebook containing the complete analysis workflow, code, visualizations, and business insights.
- `vending_analysis.html` – Read-only report version of the completed project for easy viewing without requiring Jupyter Notebook.
- `Inventory_Turnover.csv` – Source dataset containing inventory activity used throughout the analysis.
- `Restock_data.csv` – Source dataset containing replenishment and restocking activity used to evaluate inventory operations.

## How to View This Project

1. Open `vending_analysis.html` for the quickest review of the completed analysis.
2. Open `vending_analysis.ipynb` to inspect the code, workflow, and visualizations.
3. Review the source datasets to understand the underlying inventory and replenishment activity.
