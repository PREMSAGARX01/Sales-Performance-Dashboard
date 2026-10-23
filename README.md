# Superstore Sales Performance Dashboard — Power BI PR1

## Project Overview
This project is a Power BI Desktop report built using the Sample Superstore sales dataset. It explores sales, profit, quantity, discounts, product categories, regional performance, and order details.

## Objectives
- Summarize performance using KPI cards.
- Compare sales by product category.
- Compare profit by region.
- Show the top five sub-categories by sales.
- Explore the report using slicers, filters, and cross-filtering.
- Provide a separate page with detailed order information.

## Tools Used
- Microsoft Power BI Desktop
- Power Query Editor
- CSV dataset
- GitHub for project sharing

## Dataset
**Dataset:** Sample Superstore Sales Dataset  
**Source:** Kaggle  
**Format:** CSV

The original dataset contains approximately 9,994 rows. The Home Office segment was excluded during Power Query transformation, leaving approximately 8,211 rows.

## Data Preparation
The following steps were performed in Power Query:
1. Renamed columns for readability.
2. Checked and assigned appropriate data types.
3. Checked key columns for null values and removed rows with nulls if present.
4. Filtered out the Home Office segment, retaining Consumer and Corporate.
5. Split the Order ID column using the hyphen delimiter.
6. Removed Row ID, Country, and Postal Code.
7. Applied the transformations and loaded the prepared data into Power BI.

## Dashboard Features
### KPI Cards
- Total Sales
- Total Profit
- Total Quantity
- Average Discount

### Charts
- Sales by Category
- Profit by Region
- Top 5 Sub-Categories by Sales

### Interactive Controls
- Region slicer
- Category slicer
- Page-level Shipping Mode filter for Standard Class and Second Class
- Cross-filtering between visuals

### Report Pages
- **Page 1 — Sales Performance Dashboard:** KPI cards, charts, slicers, and filters.
- **Page 2 — Order Details:** A table containing detailed order-related information.

## Key Figures
With the report's current Shipping Mode filter applied, the dashboard shows approximately:
- **Total Sales:** 1.50 million
- **Total Profit:** 178.57 thousand
- **Total Quantity:** 24,936
- **Average Discount:** 15.70%

Figures may change when slicers or filters are changed.

## Screenshots

### Sales Performance Dashboard
![Sales Performance Dashboard](screenshots/Dashboard.png)

### Order Details Page
![Order Details Page](screenshots/Order details.png)

## Files to Include
- `Superstore_Sales_Dashboard.pbix` — saved Power BI report
- `Sample - Superstore.csv` — source dataset, if permitted by the assignment
- `README.md` — project documentation
- `screenshots/dashboard.png` — dashboard screenshot
- `screenshots/order-details.png` — detail page screenshot

## How to Open
1. Download or clone this repository.
2. Open the `.pbix` file in Microsoft Power BI Desktop.
3. Use the Region and Category slicers to explore the data.
4. Select chart elements to test cross-filtering.
5. Open the Order Details page to inspect the table.

## Conclusion
This project demonstrates data preparation in Power Query and interactive reporting in Power BI. The report provides an overview of sales and profit performance by category and region, along with detailed order information.


