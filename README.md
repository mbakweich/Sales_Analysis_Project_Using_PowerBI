### Sales Analysis Project Using PowerBI Desktop

## Global sales data analysis using PowerBI Desktop

### Project Overview

The objective is to develop a comprehensive system for tracking key performance indicators (KPIs) including sales, profit, and profit margin. Additionally, the project aims to compare regional performance, analyze product-level trends and forecasts, and identify high-value customers.

### Data Source

The data originates from a collection of raw CSV files containing transactional, product, customer, and territory information. The raw data files are stored in a folder for easy access [FOLDER]()

### Tools Utilized

PowerBI Desktop is the primary tool utilized for Extract, Transform, Load (ETL) processes, data modeling, implementing DAX calculations, conducting analysis, and creating visualizations.

### Data Preparation

Initially, the raw CSV files are imported into PowerBI Desktop as a folder. Subsequently, the data is transformed and combined using Power Query Editor. During this transformation phase, data types are standardized, tables are renamed, and columns are organized into a star schema structure comprising dimension and fact tables. Relationships between these tables are established to facilitate efficient querying and analysis.

### Exploratory Data Analysis

The analysis phase involves delving deeper into the provided insights, identifying trends, outliers, and potential areas for improvement.

1. Creation of a Calendar Dimension: A new table is generated to represent the calendar dimension, essential for time-based analysis.
2. Calculation of Key Performance Indicators (KPIs): Using DAX expressions, measures for total sales, total profit, and profit margin are computed and stored in a separate table named "calculations."
3. Addressing Exploratory Questions:
   * Total Sales, Total Profit, and Profit Margin: These KPIs are visualized to provide insights into overall performance.
     
     ![image](https://github.com/mbakweich/Sales_Analysis_Project_Using_PowerBI/assets/147742980/5c196a76-bd1a-4066-afbf-cf684ca999cb)
     
   * Profit/Loss Analysis by Month: The project displays the profit or loss trends from January to December to identify seasonal variations.
     
     ![image](https://github.com/mbakweich/Sales_Analysis_Project_Using_PowerBI/assets/147742980/9e5202c2-07d1-4ea2-ace8-15674136d9d2)

   * City-wise Sales and Profit Margin Visualization: A visual representation of sales and profit margin across all cities where sales occurred is created.
   
     ![image](https://github.com/mbakweich/Sales_Analysis_Project_Using_PowerBI/assets/147742980/c4e32e5e-494b-49ef-97d8-edf2d4585eb1)

   * State-wise Profit/Loss Map: A map visual is utilized to depict the profit or loss across the United States.
   
     ![image](https://github.com/mbakweich/Sales_Analysis_Project_Using_PowerBI/assets/147742980/72c8a75e-d52c-44d4-a6b4-43cd21d2980b)

   * Profit/Loss Analysis by Product Category and Sub-category: Visuals are generated to illustrate the profit or loss per product category and sub-category.
   
     ![image](https://github.com/mbakweich/Sales_Analysis_Project_Using_PowerBI/assets/147742980/f03219f9-7c5f-468c-82d1-4056d494e5a8)


### Dashboard Created

![image](https://github.com/mbakweich/Sales_Analysis_Project_Using_PowerBI/assets/147742980/8dcdfb71-929d-4a57-8276-57cdddccadc8)


### Recommendations

- Explore factors contributing to variations in sales and profit margin among different cities, optimizing marketing strategies and distribution channels accordingly.
- Identify states with consistently high profits or significant losses, investigating underlying causes and adapting regional strategies accordingly.
- Focus resources on high-profit product categories and consider adjustments to underperforming ones, such as price optimization or targeted marketing efforts.

### Conclusion

By leveraging the insights gained from this analysis, stakeholders can optimize sales strategies, improve profitability, and enhance customer satisfaction. Continuous monitoring and refinement of these recommendations will ensure sustained success in the global sales landscape.
