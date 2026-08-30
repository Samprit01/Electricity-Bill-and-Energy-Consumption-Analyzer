# Electricity Bill & Energy Consumption Analyzer

## Project Overview
This project is an Excel-based data analysis and interactive dashboard designed to evaluate electricity billing and energy consumption data. The analysis covers 180 electricity bill records spanning from 03 January 2025 to 27 December 2025. By leveraging formulas, PivotTables, and dynamic charts, the dashboard provides a centralized view of energy usage patterns, cost breakdowns, and payment statuses.

---

## Key Insights & Findings
* **Total Records Analyzed**: 180 billing records.
* **Total Energy Consumed**: 38,333 kWh.
* **Total Estimated Bill**: ₹324,958.00.
* **Peak Month**: October recorded the highest energy consumption at 4,791 kWh and the highest total bill at ₹41,116.50.
* **Highest Consuming City**: Bengaluru leads the dataset with 9,375 kWh consumed and a total bill of ₹77,661.50.
* **Top Consuming Appliance**: Air Conditioners (AC) account for the largest share of consumption at 18,153 kWh, making up 47.4% of the total.
* **Consumer Profile**: Residential consumers represent 58.4% of energy usage (22,381 kWh), while Commercial consumers account for 41.6% (15,952 kWh).

---

## Dashboard Features
The interactive dashboard includes various components to facilitate deep-dive analysis:
* **KPI Cards**: Displays critical summary metrics such as total energy consumed, total estimated bill, and average daily consumption.
* **Trend Analysis**: Visualizes monthly consumption and cost trends over the year.
* **City & Consumer Insights**: Compares consumption across five cities and maps out consumer-type distribution.
* **Appliance Breakdown**: Highlights the top appliances driving electricity usage.
* **Payment Monitoring**: Tracks bill collection ratios, noting 154 paid records and 26 pending records.
* **Interactivity**: Includes slicers and filters for dynamic analysis by month, city, and consumer type.

---

## Data Structure & Key Calculations
The source data is maintained in a clean tabular structure, structured at the transaction level using a unique `Bill ID`. The primary calculated fields include:
* **Total Bill (₹)**: Calculated automatically using the formula: `Units Consumed (kWh) × Rate per Unit (₹) + Fixed Charge (₹)`.
* **Consumption Category**: Automatically classifies records as Low (Below 150 kWh), Medium (150–300 kWh), or High (Above 300 kWh).

---

## Recommendations for Ongoing Use
* Keep the source data formatted as an Excel Table so that formulas, PivotTables, and dashboard objects can be easily refreshed when new records are added.
* Utilize the Payment Status dashboard to actively track and follow up on outstanding pending bills.
* Monitor high-consumption appliances, particularly AC usage, and use monthly trend charts to identify unusual spikes in energy usage or costs.
