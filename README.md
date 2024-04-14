# Sales and Goals - Business Intelligence

📊 Sales and Goals Business Intelligence is a comprehensive project designed to provide actionable insights into sales performance and goals achievement. Leveraging Microsoft SQL BI tools, this project offers a robust framework for data analysis and visualization, enabling businesses to make informed decisions and drive growth.

![Sales and Goals Dashboard](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/Power%20BI%20-%20Dashboard.PNG)

Delving deeper into the project, various platforms and tools were utilized to ensure its effectiveness:

## Platforms and Tools

- **Visual Studio 2019:** Development environment for building BI solutions.
- **SQL Server 15.0:** Database management system for storing and processing data.
- **SQL Server Integration Services (SSIS):** ETL (Extract, Transform, Load) tool for data integration and migration.
- **SQL Server Analysis Services (SSAS):** OLAP (Online Analytical Processing) tool for creating multidimensional data models.
- **SQL Server Reporting Services (SSRS):** Reporting tool for generating and delivering interactive reports.
- **Power BI:** Business analytics tool for creating interactive visualizations and dashboards.
- **T-SQL and MDX queries:** Languages for querying and manipulating data in SQL Server and SSAS.

## Features

The Sales and Goals BI project offers a range of features tailored to meet the needs of sales analysis and goal tracking:

- **Data Extraction and Staging:** Extraction of data from Excel sheets followed by staging in a RAW database.
- **Data Warehousing:** Loading staged data into a data warehouse using a star schema for optimized querying.
- **OLAP Cube Development:** Creation of OLAP cubes with key performance indicators (KPIs), hierarchies, calculated fields, and partitions for in-depth analysis.
- **Comprehensive Reports:** Generation of reports focusing on products, sellers, and customers, providing insights into sales performance and goal achievements.
- **Interactive Dashboards:** Development of Power BI dashboards featuring KPIs, rankings, maps, and tooltip windows for intuitive data exploration.

## Installation 

Setting up the Sales and Goals BI project involves the following steps:

1. Open the Sales-Business-Intelligence Visual Studio solution.
2. Ensure the Sales.xlsx file is located in the DataSource directory.
3. Publish both databases: DB_Staging and DW_Sales.
4. Run SSIS projects to execute data integration tasks.
5. Execute SSAS Cube_Sales to build the OLAP cube.
6. Publish SSRS project to deploy interactive reports.
7. Open the .pbix file in Power BI for dashboard visualization.

## Screenshots

Explore snapshots of the Sales and Goals BI project:

![Data source](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/Data%20source.PNG)
![ER Diagram](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/Datawarehouse%20-%20ER%20diagram.PNG)
![SSIS - Staging - Control Flow](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSIS%20-%20Staging%20-%20Control%20Flow.PNG)
![SSIS - Staging - Data Flow](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSIS%20-%20Staging%20-%20Data%20flow.PNG)
![SSIS - Loading - Control Flow](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSIS%20-%20Loading%20-%20Control%20Flow.PNG)
![SSAS - Cube Structure](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSAS%20-%20Cube%20structure.PNG)
![SSAS - Calculations](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSAS%20-%20Calculations.PNG)
![SSAS - KPI](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSAS%20-%20KPI.PNG)
![SSRS - Reports](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSRS%20-%20Reports.PNG)
![SSRS - Report - MDX query](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/SSRS%20-%20Report%20-%20MDX%20query.PNG)
![Power BI - Dashboard](https://github.com/DE-romane/Sales-Business-Intelligence/blob/main/Images/Power%20BI%20-%20Dashboard.PNG)
