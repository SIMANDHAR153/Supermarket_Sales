# Supermarket Sales Data Analysis

## Project Overview
This project focuses on analyzing and visualizing supermarket sales data using Python and Power BI. The objective is to clean the dataset, perform exploratory data analysis (EDA), and create an interactive Power BI dashboard to derive actionable insights.

## Dataset Information
The dataset contains transactional information for a supermarket, including details such as customer segments, geographic location, product categories, and sales figures.

## Data Cleaning Process
1. **Initial Data Exploration:**
   - `head()` - Displays the first five rows of the dataset.
   - `shape` - Provides the dimensions (number of rows and columns).
   - `columns` - Lists all column names.
   - `info()` - Summarizes data types and missing values.

2. **Handling Missing Values:**
   - `isnull()` - Identifies missing values in the dataset.
   - `isnull().sum()` - Counts the number of missing values in each column.
   - Missing postal codes were filled with appropriate values.

3. **Duplicate Check:**
   - Checked for duplicate records and removed them if found.

4. **Data Type Conversion:**
   - Converted relevant columns (e.g., date columns) to `datetime` format for proper analysis.

## Exploratory Data Analysis (EDA)

### Univariate Analysis
- Analyzed the distribution of:
  - **Segment**: Different customer segments.
  - **City**: Number of transactions by city.
  - **Region**: Sales distribution across regions.
  - **Category & Sub-category**: Sales and count by product categories.
  - **Sales**: Distribution of sales amounts.

### Bivariate Analysis
- **Sales vs. Ship Mode**: Analyzed how different shipping modes affect sales.
- **Sales vs. Segment**: Examined sales performance across customer segments.
- **Top 10 Cities by Sales**: Identified cities contributing the most to total sales.
- **Top 10 States by Sales**: Ranked the top-performing states by sales revenue.
- **Sales Percentage by Region**: Calculated the contribution of each region to total sales.
- **Sales Percentage by Category**: Measured the proportion of total sales for each product category.
- **Total Sales by Sub-category**: Analyzed sales volume and revenue by sub-category.

## Power BI Dashboard
An interactive Power BI dashboard was created to visualize the following insights:
1. Sales distribution across customer segments, cities, and regions.
2. Performance comparison by shipping mode and customer segment.
3. Top-performing cities and states by total sales.
4. Sales contribution percentages by region and product category.
5. Detailed view of sales across sub-categories.

## How to Run the Project
1. Ensure Python and Power BI Desktop are installed.
2. Clean and preprocess the dataset using the provided Python code.
3. Load the cleaned data into Power BI.
4. Open the Power BI dashboard file (.pbix) to explore insights.

## Tools and Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn (for data cleaning and EDA)
- **Power BI**: For interactive dashboard visualization

## Conclusion
This project provides a comprehensive analysis of supermarket sales data, offering valuable insights through both Python-based EDA and an interactive Power BI dashboard.
