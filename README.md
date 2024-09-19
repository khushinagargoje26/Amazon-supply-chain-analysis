Based on the provided code and dataset, here's a professional **README** file for the **Amazon Supply Chain Analysis** project, formatted for GitHub:

---

# Amazon Supply Chain Analysis

## Overview

This project focuses on analyzing the supply chain of Amazon using a dataset that includes various factors such as warehouse capacity, regional zones, workers, and logistics. The analysis provides insights into warehouse operations, storage issues, government certifications, transport issues, and refill requests across different zones. 

The project is written in Python and utilizes popular libraries like `NumPy`, `Pandas`, `Matplotlib`, and `Seaborn` for data analysis and visualization.

## Dataset

The dataset used in this project is named `FMCG_data.csv`, which contains the following columns:
- `Ware_house_ID`: Unique identifier for each warehouse.
- `WH_capacity_size`: The capacity size of the warehouse.
- `Location_type`: Urban or rural classification.
- `zone`: The geographical zone of the warehouse.
- `WH_regional_zone`: The regional zone of the warehouse.
- `retail_shop_num`: Number of retail shops served by the warehouse.
- `workers_num`: Number of workers in the warehouse.
- `electric_supply`: Whether the warehouse has electric supply.
- `dist_from_hub`: Distance of the warehouse from the central distribution hub.
- `storage_issue_reported_l3m`: Storage issues reported in the last 3 months.
- `num_refill_req_l3m`: Refill requests in the last 3 months.
- `govt_check_l3m`: Government checks in the last 3 months.
- `approved_wh_govt_certificate`: Government certification approval status.
- `transport_issue_l1y`: Transport issues in the last year.
- `product_wg_ton`: Average product weight per ton.
- `temp_reg_mach`: Whether the warehouse has temperature regulation machinery.
- `wh_est_year`: Year of warehouse establishment.
- `wh_breakdown_l3m`: Number of breakdowns reported in the last 3 months.
- `Competitor_in_mkt`: Whether a competitor is present in the market.

## Analysis Questions and Key Insights

1. **Average Warehouse Capacity**: What is the average capacity size of the warehouses?
2. **Urban vs. Rural Warehouses**: How many warehouses are located in urban areas versus rural areas?
3. **Retail Shops per Zone**: Total number of retail shops served by each zone.
4. **Average Workers per Warehouse**: What is the average number of workers per warehouse, including based on the size of the warehouse?
5. **Electric Supply in Warehouses**: Determine the percentage of warehouses with electric supply.
6. **Distance from Distribution Hub**: Analyze the average distance of warehouses from the central hub.
7. **Storage Issues in Last 3 Months**: How many warehouses have reported storage issues?
8. **Refill Requests in Last 3 Months**: Identify the top 3 zones with the highest number of refill requests.
9. **Government Checks**: Calculate the average number of government checks per warehouse.
10. **Government Certifications**: What is the most common type of government certification?
11. **Workers vs. Storage Issues Correlation**: Analyze the correlation between the number of workers and reported storage issues.
12. **Warehouse Capacity vs. Refill Requests**: Examine the relationship between warehouse capacity and refill requests.
13. **Transport Issues**: Which geographical zone has the highest average number of transport issues?
14. **Product Weight and Temperature Regulation**: What is the average product weight per ton for warehouses with temperature regulation machinery?
15. **Top Warehouses by Government Checks**: Identify the top 5 warehouses with the highest number of government checks and analyze their storage issue reports.
16. **Urban vs. Rural Workers**: Compare the average number of workers in urban versus rural warehouses.
17. **Distance from Hub and Transport Issues**: What is the impact of distance from the hub on transport issues?
18. **Competitor Presence and Refill Requests**: Analyze the effect of competitor presence on the number of refill requests.
19. **Government Certification and Storage Issues**: Is there a significant difference in storage issues between warehouses with and without government certification?
20. **Warehouse Establishment Year and Breakdown Reports**: Investigate the relationship between the warehouse establishment year and breakdown reports.

## Visualizations

- Bar plots for the number of warehouses in urban vs rural areas.
- Scatter plots analyzing transport issues vs. distance from the hub.
- Regression plot showing the relationship between warehouse establishment year and breakdown reports.

## Code

The main analysis script performs the following operations:
1. **Data Cleaning**: Missing values in key columns like `workers_num` are handled by filling them with the average values from similar groups.
2. **Descriptive Statistics**: The dataset's statistical summary is exported to an Excel file.
3. **Data Analysis**: Key insights about warehouse operations, regional trends, and logistical issues are derived through grouped analysis.
4. **Correlation Analysis**: Relationships between various factors like number of workers and storage issues, distance from hub and transport issues, etc., are explored.
5. **Visualization**: Matplotlib and Seaborn are used to create informative visualizations that summarize the dataset findings.

## Requirements

To run the project, you'll need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `openpyxl`

Install the libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn openpyxl
```

## How to Run

1. Download the dataset (`FMCG_data.csv`) and place it in your working directory.
2. Run the Python script `amazon_supply_chain_analysis.py` to generate the analysis and visualizations.
3. The output, including statistical summaries and graphs, will be displayed in the terminal and saved in an Excel file named `Amazon_supplychain_analysis.xlsx`.

## Conclusion

This project provides a comprehensive analysis of the supply chain data for Amazon, including operational insights, potential challenges like storage issues, and performance metrics for different warehouse zones. It demonstrates effective use of Python's data science libraries for supply chain analysis.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Feel free to modify any sections of this README according to your preferences!
