# E-Commerce-Dimensional-Modelling-And-Data-Analysis
This project presents a comprehensive analysis and data modeling workflow to understand and optimize the order management processes of an E-Commerce business. Leveraging the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), the study evaluates operational performance across five core business functions and builds an efficient Power BI data model to support data-driven decision-making.

## Project Overview
E-commerce operations involve multiple interconnected processes—from order placement to customer feedback. This project aims to uncover performance patterns, identify bottlenecks, and propose actionable improvements by analyzing real-world data.

The analysis is centered around the following business processes:

- Order Placement
- Order Fulfillment & Shipment
- Invoicing & Payments
- Exchanges & Returns
- Customer Reviews & Feedback

A scalable Power BI semantic model was designed to support these analyses using industry-standard modeling practices.

## Methodology
This project used a structured workflow to convert raw e-commerce data into meaningful business insights:

**Data Evaluation and Acquisition**: Reviewed all available datasets and identified the key metrics needed to address business goals. Gathered information from various systems such as CRM, ERP, and web analytics tools.

**Data Preparation and Transformation**: Utilized Power Query to clean and standardize data, remove duplicates, and manage missing entries. Developed a reliable ETL pipeline to maintain data accuracy and consistency throughout the model.

**Dimensional Data Modeling**: Built a star schema model featuring well-defined fact and dimension tables to enhance analytical performance. Configured relationships and hierarchies to support detailed, multi-layered analysis.

**Measure Creation**: Developed advanced DAX measures to compute essential KPIs, basket analysis indicators, and year-over-year comparison metrics.

**Dashboard & Visualization Development**: Followed visualization best practices to design clear, user-friendly dashboards. Selected appropriate chart types and applied strong visual structure to ensure insights are easy to interpret.

## Tools and Technologies

**Power BI Desktop**:  Data modeling and visualization

**DAX**: Measures and calculations

**Power Query (M Language)**: Data cleaning and transformations

## Data Modeling in Power BI

The data model was developed in Microsoft Power BI, focusing on clean schema design, optimized relationships, and analytical flexibility.

**Data Modeling Highlights**

- Used consistent naming conventions for surrogate keys (e.g., SK_OrderID, SK_CustomerID).

- Designed a centralized Calendar Table, enabling accurate date-driven analysis across all facts.

- Built optimized Star Schema structures separating Fact and Dimension tables.

- Ensured model efficiency through:

  - proper column data types

  - reduction of cardinality

  - removal of unused columns

  - performance-oriented DAX calculations

## Observations


