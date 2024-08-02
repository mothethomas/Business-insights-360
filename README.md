# Implementing Data Analytics with Power BI at AtliQ Hardware

## Project Overview
AtliQ Hardware, experiencing rapid growth, is integrating data analytics through Power BI to gain a competitive edge and foster a culture of data-driven decision-making.

## Objectives
The primary goal is to provide stakeholders in finance, sales, marketing, and supply chain functions with actionable insights from robust data analytics. Power BI will enhance decision-making and optimize performance across the business.

## Scope
The project involves a detailed analysis of finance, sales, marketing, and supply chain dynamics. Using Power BI, data from various internal and external sources will be integrated to offer a comprehensive understanding of the business environment.

## Guidance
This project was undertaken with guidance from the Codebasics Power BI Course.

## Technology Stack
- SQL
- Power BI Desktop
- Excel
- DAX language
- DAX Studio (for report optimization)
- Project Charter File

## Power BI Techniques Learned
- Understanding project prerequisites
- Formulating key project questions
- Utilizing calculated columns
- Implementing measures with DAX
- Data modeling
- Using Bookmarks for visual switching
- Navigating pages with buttons
- Preventing zero division errors with the divide function
- Generating date tables using M language
- Creating dynamic titles based on filters
- Incorporating KPI indicators
- Implementing data validation techniques
- Exploring Power BI services
- Publishing reports to Power BI services
- Configuring personal gateway for data auto-refresh
- Creating Power BI Apps
- Collaborating on workspaces and managing access permissions

## Business Terminology
- Gross Price
- Gross Margin
- Net Sales
- Net Invoice Sale
- Net Profit
- COGS (Cost of Goods Sold)
- Pre-invoice Deductions
- Post-invoice Deductions
- YTD (Year to Date)
- YTG (Year to Go)
- Direct Sales
- Retailers
- Distributors
- Consumers

## Company Overview
AtliQ Hardware has grown significantly, specializing in computers and accessories, and operates through retailers, direct sales, and distributors. The company faced challenges, including losses from a new store in America, highlighting the need for data-driven insights. AtliQ Hardware is now establishing an analytics team to enhance its competitive position.

## Project Kickoff Considerations
Before developing the dashboard, several key questions need addressing during the project kickoff:

1. What are the primary objectives for the Power BI dashboard?
2. How will project success be measured?
3. What is the expected project timeline?
4. Do stakeholders require a preview before the official release?
5. What are stakeholders' expectations and desired outcomes?
6. What concerns do stakeholders have?
7. Who will use the dashboard, and for what purposes?
8. What specific deliverables are expected?
9. What potential challenges or risks might arise?
10. What data sources and resources are required?
11. Have stakeholders provided input on dashboard design preferences?

## Dataset Overview
A thorough understanding of the dataset is crucial for effective analysis.

### Dimension Tables:
- **dim_customer:** Contains customer and product details, with 27 distinct markets and 75 customers. Includes platforms like Brick & Mortar and E-commerce, and channels such as Retailer, Direct, and Distributors.
- **dim_market:** Covers 27 distinct markets with 7 sub-zones and 4 regions (APAC, EU, LATAM).
- **dim_product:** Divisions include P&A (Peripherals & Accessories), PC (Personal Computer), N&S (Networking & Storage), and 14 categories like Internal HDD and Keyboard.

### Fact Tables:
- **fact_forecast_monthly:** Contains forecasted customer needs.
- **fact_sales_monthly:** Contains actual sales data.

### Additional Tables:
- **gdb056_freight_cost:** Travel and other costs per market.
- **gdb056_gross_price:** Gross prices with product codes.
- **gdb056_manufacturing_cost:** Manufacturing costs with product codes.
- **gdb056_Pre_invoice_deductions:** Pre-invoice deductions per customer.
- **gdb056_Post_invoice_deductions:** Post-invoice and other deductions.

## Data Model
The data model forms the foundation of Power BI reports. This project uses the Snowflake data modeling method, organizing data into normalized tables connected by foreign key relationships for efficient querying and analysis.

## Dashboard Design
Once mock-ups are approved, the design phase will begin, creating visuals and implementing necessary measures.

### Views:
- **Home:** Central navigation to other sections.
- **Info:** General updates and information.
- **Finance View:** Financial insights and key metrics.
- **Sales View:** Sales data, trends, and analytics.
- **Marketing View:** Marketing campaign analytics and ROI.
- **Supply Chain View:** Supply chain operations and inventory management.
- **Executive View:** High-level KPIs and strategic insights.
- **Support:** Access to support resources.

This structure enables users to access relevant information easily, enhancing decision-making and user experience.

### Dashboards
# Finance View
![Demographic Insights](https://github.com/mothethomas/Business-insights-360/blob/main/Dashboards/Finance.jpg)

# Supply Chain
![Demographic Insights](https://github.com/mothethomas/Business-insights-360/blob/main/Dashboards/Supply_chain.jpg)

# Marketing View

![Demographic Insights](https://github.com/mothethomas/Business-insights-360/blob/main/Dashboards/marketing.jpg)

# Sales

![Demographic Insights](https://github.com/mothethomas/Business-insights-360/blob/main/Dashboards/sales.jpg)
