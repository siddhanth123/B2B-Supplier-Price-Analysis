# Supplier Price Analysis for Strategic Procurement

## Project Overview

This project focuses on analyzing tiered pricing data from multiple suppliers to identify which offer the best prices across different purchase volumes. The analysis aims to aid strategic procurement decisions by evaluating suppliers based on their pricing strategies and their ability to supply a broad range of products.

## Objectives

- Identify suppliers offering the best prices for small and bulk quantities.
- Evaluate suppliers based on the breadth of their product offerings.
- Develop insights into how volume discounts affect pricing.

## Data Description

The dataset includes pricing information from 9 suppliers for 777 different products, detailing prices at various quantities.

### Attributes

- **Product**: Identifier for each product.
- **Supplier**: Identifier for each supplier.
- **Tier**: Quantity threshold that influences unit price.
- **Price**: Cost per unit at each tier.

## Methodology

1. **Data Preparation**: Clean and standardize the data for analysis.
2. **Price Analysis**:
   - Calculate minimum prices for standard quantities (1, 10, 50, 100 units, etc).
   - Identify which suppliers offer the lowest prices consistently across different tiers.
3. **Visualizations**:
   - Generate line plots and bar charts to visualize pricing trends and supplier coverage.

## Tools Used

- **Python**: For data manipulation and analysis.
- **Pandas**: For handling dataframes.
- **Matplotlib/Seaborn**: For generating visualizations.

## Results

The analysis revealed key suppliers who consistently offer competitive prices and those with the best volume discounts. Insights from the data suggest strategies for future procurement and supplier negotiations.

## Conclusion

This project provides valuable insights that can help shape strategic procurement practices by highlighting key suppliers and pricing strategies beneficial for cost management and supply chain optimization.
