DASHBOARD CREATED USING POWER-BI

# Real Estate Sales Performance Dashboard

This repository contains the project **Real Estate Sales Performance Dashboard**, which is designed to analyze and visualize real estate data spanning 2020 to 2022. The project focuses on transforming, cleaning, and analyzing real estate data to provide actionable insights for performance evaluation and decision-making.

## Features

### Dataset Overview
- **Timeframe**: Data covers 3 years (2020, 2021, and 2022).
- **Attributes**: Includes 21 features such as:
  - Property ID, Sector, Construction Date
  - Stage Name, Sales Agent, Revenue
  - Project Name, City, Property Status, Payment Details, etc.
- **Data Preparation**: 
  - Removed null values and blank rows.
  - Used the first row as headers.
  - Cleaned and transformed the dataset for analysis.

### Dim Date Table
- Introduced a **DimDate table** to manage date-related inconsistencies.
- Ensured continuous, gap-free, and non-duplicate values for better sorting and analysis.
- Established a one-to-one relationship between date columns.

### Key Performance Indicators (KPIs)
- Created KPI cards to visualize core metrics, such as:
  - Properties: Vacant, Occupied, and Unlisted.
- Utilized DAX measures with the `CALCULATE` function for flexible filtering and expressions.

### Visualizations
- **Stacked Bar Chart**: Compare sold vs. new properties.
- **Line Chart**: Show trends over time.
- **Pie & Donut Charts**: Analyze categorical data for monthly targets.
- **Aster Plot & Column Chart**: Provide additional visual insights.
- **Multi-Row Card**: Determine agent contributions to total sales.

### Key Insights
- Steady inflow of new properties as older ones are sold.
- Sales agents consistently achieve targets.
- Maximum revenue observed from six projects averaging $30K each.
- Top-performing agent, "Richard," contributed 44% of the total sales, generating $778K.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/awwal-9/Real-Estate-Sales-Performance-Dashboard.git
   ```
2. Ensure your environment supports data visualization tools (e.g., Power BI, Tableau, or Python visualization libraries).
3. Load the dataset and follow the analysis steps outlined in the project.

## Requirements
- **Tools**: Power BI (recommended) or any other data visualization software.
- **Skills**: Familiarity with data cleaning, DAX (Data Analysis Expressions), and visualization techniques.

## Usage
1. Open the dataset in your preferred tool.
2. Apply the transformations and measures as described.
3. Utilize the pre-configured visuals and KPIs to explore insights.

## License
This project uses a free template provided by [FPPT.com](https://www.free-power-point-templates.com).

## Acknowledgments
Special thanks to Abdul Awwal Choudhari for developing the project and sharing insights.
