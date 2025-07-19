# SN-Crop Dashboard Analyst Project 

This project creates a comprehensive agricultural analytics dashboard using crop sales and performance data. The dashboard provides insights into sales performance, cost analysis, profitability metrics, and regional distribution patterns using advanced data visualization techniques and interactive filtering capabilities.

## Project Overview

This dashboard analyzes agricultural crop sales data focusing on customer performance, regional distribution, product profitability, and seasonal trends. The platform includes multiple interconnected visualizations designed to provide actionable insights for agricultural business decision-making.

## Business Questions Addressed

1. Performance Metrics: Display key performance indicators including total sales (1.3M), costs (639.7K), and profit (623.8K) with trend analysis
2. Customer Analysis: Identify top-performing customers and their contribution to overall sales and profitability
3. Regional Distribution: Analyze sales patterns across different geographical regions (Central, North, South)
4. Product Categories: Determine sales performance and quantity distribution by sub-categories
5. Seasonal Trends: Track order patterns and performance trends over time (2017-2020)
6. Shipping Analysis: Compare performance across different shipping modes (Economy, Economy Plus, Immediate)

## Technical Implementation

###  Data Architecture
 - Primary Dataset: Agricultural sales transaction data
 - Date Range: 2017-2020 with quarterly breakdowns
 - Geographic Coverage: Multi-regional analysis with country-level mapping
 - Customer Segmentation: Individual customer performance tracking

 ### Data Modeling
 - Integrated sales, cost, and profit calculations
 - Created relationships between customer, regional, and temporal data
 - Implemented geographic mapping for country-level analysis
 -Built hierarchical time structures for quarterly and yearly analysis

### Key Calculated Measures
 - Total Sales: 1,263,537 (aggregated sales performance)
 - Total Cost: 639,730 (operational cost analysis)
 - Total Profit: 623,807 (profitability calculation)
 - Regional Distribution: Quantity analysis by geographic regions
 - Customer Performance: Individual customer sales, cost, and profit metrics
 - Time-based Analysis: Year-over-year and quarterly performance tracking

## Dashboard Components

### KPI Section

- Large metric cards displaying total sales, costs, and profits
- Color-coded performance indicators
- Interactive filtering capabilities

### Customer Performance Table

- Detailed customer-wise breakdown showing:
  - Customer Name
  -Sum of Sales
  -Sum of Cost
  -Sum of Profit

- Sortable columns for performance ranking

### Geographic Analysis

- Interactive map visualization showing sales distribution by country
- Regional pie chart breaking down quantity by regions:
- Central: 55.14%
- South: 22.67%
- North: 22.19%

### Product Analysis

- Horizontal bar chart showing sales and profit by sub-categories
- Performance ranking from highest to lowest performing products
- Quantity distribution analysis

### Temporal Trends

- Line chart tracking order count by year and quarter
- Trend analysis showing performance evolution from 2017-2020
- Seasonal pattern identification

### Interactive Controls

- Date range selector (12-01-2017 to 31-12-2020)
- Shipping mode filters (Economy, Economy Plus, Immediate)
- Cross-filtering capabilities across all visualizations

## Technical Features

###Data Preparation

 - Comprehensive data cleaning and transformation
 - Date standardization and hierarchy creation
 -  Geographic data normalization
 - Customer and product categorization

### Visualization Techniques

- Responsive design with optimized layout
- Color-coded performance indicators
- Interactive tooltips and drill-down capabilities
- Cross-filtering between visualizations
- Professional styling with consistent color scheme

### Performance Optimization

- Efficient data model relationships
- Optimized DAX calculations
- Responsive filtering mechanisms
- Clean, clutter-free interface design

## Setup Instructions

### Data Requirements:

- Agricultural sales transaction dataset
- Customer information database
- Geographic reference data
- Date dimension table


### Installation Steps:

- Import the crop sales dataset into your BI platform
- Configure data relationships and hierarchies
- Implement calculated measures and KPIs
- Design and configure visualizations
- Set up interactive filtering controls


### Configuration:

- Establish date range parameters
- Configure geographic mapping
- Set up customer performance calculations
- Implement cross-filtering logic



## Key Insights Delivered

- Customer Performance: Identification of top revenue-generating customers
- Regional Opportunities: Geographic areas with highest sales potential
- Product Optimization: Best and worst performing product categories
- Seasonal Patterns: Understanding of sales cycles and trends
- Profitability Analysis: Cost vs. profit relationship across segments
- Operational Efficiency: Shipping mode performance comparison


## Technologies Used

- Business Intelligence Platform (Power BI/Tableau)
- Data modeling and DAX/calculated fields
- Geographic visualization capabilities
- Interactive filtering and cross-filtering
- Responsive dashboard design
- Data transformation and cleaning tools


