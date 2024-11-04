# Instacart Grocery Basket Analysis with Python

This project leverages Python to analyze Instacart’s grocery transaction data, aiming to uncover meaningful insights into customer buying behaviors. The insights derived from this analysis provide recommendations to Instacart’s marketing and sales teams, enhancing their ability to target specific customer segments effectively. This analysis is documented through Jupyter notebooks, culminating in a detailed report.

## Project Purpose

Instacart, a popular online grocery platform, wants to explore patterns in customer purchase data to refine its marketing strategy. As a data analyst, the objective is to conduct an in-depth exploratory analysis that supports Instacart in understanding customer segments and aligning marketing efforts accordingly.

## Key Business Questions

1. **Order Timing**:
   - What are the peak days and times for customer orders? Identifying these will aid in scheduling promotions for quieter periods.
   - Are there times when customer spending is highest? This can guide product-focused marketing during peak spending hours.

2. **Product Popularity & Pricing**:
   - How can products be grouped by price to streamline targeting?
   - Which product categories or departments show the highest order volumes?

3. **Customer Segmentation**:
   - What is the distribution of customers based on loyalty (i.e., frequency of returns)?
   - How do purchasing habits vary by customer loyalty level or region?
   - What are the relationships between age, family structure, and purchasing behaviors?
   - How can demographic information like age, income, and family status guide customer segmentation?
   - What distinct patterns emerge in purchasing across different customer segments (e.g., order values, order frequency, popular product types)?

## Data Sources

This project uses the following datasets:

  - **Orders**
  - **Orders_Products_Prior**
  - **Products**
  - **Customers**
  - **Departments**

*Note*: The `customers` dataset and `prices` column were created specifically for educational purposes as part of the CareerFoundry course.

## Tools & Libraries

The data analysis was performed using Python and the following libraries:

  - **Pandas**: for data cleaning and manipulation
  - **NumPy**: for numerical computations
  - **Seaborn**: for creating visualizations
  - **Matplotlib**: for additional data visualization
  - **SciPy**: for statistical analysis
  - **Warnings**: to suppress non-critical warnings

## Project Organization

The project files are organized into the following folders:

  1. **Project Management**: Contains project documentation, including the Project Brief and Data Dictionary.
  2. **Data**: Split into `Original Data` and `Prepared Data` subfolders, holding the raw and processed datasets, respectively. *(Data files are not uploaded to GitHub due to size constraints.)*
  3. **Scripts**: Contains Jupyter notebooks detailing each step of the analysis.
  4. **Analysis**: Includes the `Visualizations` folder with charts and graphs generated for insight development.
  5. **Client Deliverables**: Contains the final report provided in Excel format.

## Additional Notes

*Note*: This project is based on publicly available Instacart data, supplemented with fictional data for analysis. The brief and tasks were created by CareerFoundry for educational purposes.

