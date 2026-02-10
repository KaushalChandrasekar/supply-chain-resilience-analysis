# Supply Chain Resilience Analysis

## Project Overview

This project presents an end-to-end data analytics study focused on supply chain resilience.
Using a transactional supply chain dataset, the analysis explores order delays, disruption patterns, logistics modes, and risk exposure to uncover actionable insights that support operational decision-making.

The goal of this project is to demonstrate a complete data analytics workflow, from raw data cleaning to insight generation.

---

## Objectives

- Analyze delivery delays across different shipping modes

- Understand disruption types and their impact on supply chain performance

- Identify risk indicators using historical disruption data

- Explore supplier and logistics behavior affecting resilience

- Communicate findings using clear visualizations and interpretations

---

## Dataset Description

The dataset contains transactional and operational records from a multi-actor supply chain.

### Key Features

| Column Name | Description |
|------------|------------|
| Order_ID | Unique identifier for each order |
| Order_Date | Date when the order was placed |
| Dispatch_Date | Date when the order was dispatched |
| Delivery_Date | Final delivery date |
| Quantity_Ordered | Number of units ordered |
| Order_Value_USD | Monetary value of the order |
| Shipping_Mode | Mode of transport (Air, Sea, Road, etc.) |
| Product_Category | Type of product |
| Supplier_ID | Encoded supplier identifier |
| Buyer_ID | Encoded buyer identifier |
| Delay_Days | Number of days delivery was delayed |
| Historical_Disruption_Count | Past disruption frequency |
| Disruption_Type | Nature of disruption encountered |

---

## Analytical Approach

The project follows a structured analytics workflow:

1. **Data Cleaning & Preprocessing**

- Handling missing values

- Date conversions

- Feature consistency checks

2. **Exploratory Data Analysis (EDA)**

- Delay distribution analysis

- Shipping mode comparison

- Disruption frequency trends

3. **Descriptive & Diagnostic Analytics**

- What caused delivery delays?

- Which logistics modes are more risk-prone?

- How past disruptions influence future delays?

4. **Visualization & Interpretation**

- Bar charts, distributions, and comparative plots

- Business-focused interpretation of results

---

## Tools & Technologies

1. **Python**

2. **Pandas** – data manipulation

3. **NumPy** – numerical analysis

4. **Matplotlib & Seaborn** – data visualization

5. **Jupyter Notebook** – analysis & documentation

---

## Key Insights (Sample)

- Certain **shipping modes consistently experience higher delays**
  
- Orders with **higher historical disruption counts** show increased risk
  
- Specific **disruption types** significantly affect delivery timelines
  
- Logistics strategy plays a crucial role in **supply chain resilience**

*(Detailed insights are available inside the notebook)*

---

## Repository Structure

├── LICENSE

├── README.md

├── Supply_Chain_Resilience_Analysis.ipynb

├── supply_chain_resilience_dataset.csv

---

## How to Run the Project

1. Clone the repository:

    git clone https://github.com/KaushalChandrasekar/supply-chain-resilience-analysis.git


2. Open the notebook:

    jupyter notebook Supply_Chain_Resilience_Analysis.ipynb

3. Run all cells to reproduce the analysis.

---

## Skills Demonstrated

- Data Cleaning & Wrangling

- Exploratory Data Analysis

- Risk & Disruption Analysis

- Business-oriented Insight Generation

- Visualization & Storytelling

- Python for Data Analytics

## License

This project is open source and available under the MIT License.
