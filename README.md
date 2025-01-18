# Zomato Sales Report - Power BI Project

## Project Overview
This Power BI project focuses on analyzing sales performance and regional KPIs for Zomato across multiple continents. The datasets represent sales data from **Asia, Africa, Oceania, South America, Europe, and North America**, along with a **Country Master** and **KPIs** table. The analysis is structured to provide actionable insights on regional sales and key performance indicators.

---

## Datasets Used
1. **Asia.csv**: Sales data for Asian regions.
2. **Africa.csv**: Sales data for African regions.
3. **Oceania.csv**: Sales data for Oceania regions.
4. **South_America.csv**: Sales data for South America.
5. **Europe.csv**: Sales data for European regions.
6. **North_America.csv**: Sales data for North America.
7. **Country_Master.csv**: Metadata for country-level details.
8. **KPIs.csv**: Key performance indicators.

---

## Data Modeling and Measures
- **Data Modeling**: Established relationships between datasets using **Country Master** as the central linking table. Ensured proper connections between regions and KPIs.
- **Measures**:
  - Total Sales by Region
  - Average Sales per Country
  - Year-over-Year Sales Growth
  - Percentage Contribution to Global Sales (with variables)
- **Calculated Columns**:
  - Region Classification (e.g., Emerging vs. Developed)
  - Sales Performance Category (e.g., High, Medium, Low)
  - Sales per Capita

---

## Workspace and Report Details
### Power BI Service Workspace
1. **Workspace Name**: Zomato Sales Analysis
2. **Description**: 
   - **Team Members**: (Your Full Names)
   - **Project Research**: This analysis focuses on understanding Zomato's global sales performance, identifying top-performing regions, and uncovering opportunities for expansion.
3. **Team Collaboration**: Added participants, including team members and instructor email for collaboration.

---

## Key Pages and Visualizations
### 1. **Summary Page**
   - **Purpose**: High-level overview of Zomato's global sales performance.
   - **Visuals**:
     - Bar Chart: Sales by Region
     - Pie Chart: Percentage Contribution of Each Region
     - KPI Cards: Global Total Sales, Highest Selling Region, Lowest Selling Region
   - **Filters**: Global filters for year and product categories.
   - **Navigation**: Contains buttons to navigate to detailed pages.

---

### 2. **Region-Level Analysis**
   - **Purpose**: Provides a breakdown of sales and performance by region.
   - **Visuals**:
     - Table: Region-wise Total Sales and Average Sales
     - Map: Sales distribution across continents.
     - Conditional Formatting: Highlighted top-performing and underperforming regions in the table.
   - **Filters**: Slicers for year, product type, and region.

---

### 3. **Detailed KPI Analysis**
   - **Purpose**: Deep dive into regional KPIs and sales performance.
   - **Visuals**:
     - Line Chart: Year-over-Year Sales Trends for each region.
     - Clustered Column Chart: Sales Contribution by Country within each region.
     - KPI Cards: Regional performance summary.
   - **Navigation**: Buttons to navigate back to the summary or other pages.

---

## Features Implemented
1. **Calculated Measures and Columns**:
   - Created 4 unique measures, including one with variables for percentage contribution.
   - Added 3 calculated columns for region classification and sales performance.
2. **Navigation**:
   - Custom navigation buttons for easy movement between pages.
3. **Conditional Formatting**:
   - Applied formatting to highlight top and bottom regions in tabular data.
4. **Data Visualizations**:
   - Used at least 3 different visuals, including bar charts, pie charts, and tables.
   - Ensured readability with appropriate font sizes and clear labels.
5. **Filters**:
   - Incorporated slicers and filters for interactive analysis.

---

## Additional Steps
1. **Exported Report**:
   - The completed report was exported to **PowerPoint** from Power BI Service for presentation purposes.

---

## Repository Structure
