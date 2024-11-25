# Business-Insights-360
Project Overview
AtliQ Hardware has been growing rapidly in recent years and is now stepping into data analytics with Power BI to stay ahead of its competitors. This project aims to help stakeholders make smarter, data-driven decisions by answering key questions across areas like finance, sales, marketing, and supply chain. With this initiative, AtliQ aims to unlock new growth opportunities and strengthen its position in the market.

𝐓𝐞𝐜𝐡 𝐬𝐤𝐢𝐥𝐥𝐬 𝐈 𝐚𝐜𝐪𝐮𝐢𝐫𝐞𝐝 𝐦𝐞𝐧𝐭𝐢𝐨𝐧𝐞𝐝: 

✔ SQL
✔ PowerBI Desktop
✔ Excel
✔ DAX language
✔ DAX Studio (for optimizing the report)
✔ Referred Project charter file


𝐏𝐨𝐰𝐞𝐫𝐁𝐈 𝐓𝐞𝐜𝐡𝐧𝐢𝐪𝐮𝐞𝐬:

✔ Creating calculated columns
✔ Creating measures using the DAX language
✔ Data Modelling
✔ Using Bookmarks to switch between two visuals 
✔ Page navigation with buttons
✔ Creating date tables using M language
✔ Dynamic titles based on the applied filters
✔ Using KPI indicators
✔ Conditional formatting of the values in visuals
✔ Techniques of Data Validation
✔ PowerBI services
✔ Publishing reports to the PowerBI services
✔ Setting up the personal gateway to set the auto-refresh of data

𝐃𝐢𝐟𝐟𝐞𝐫𝐞𝐧𝐭 𝐭𝐞𝐫𝐦𝐬 𝐮𝐬𝐞𝐝 𝐢𝐧 𝐅𝐢𝐧𝐚𝐧𝐜𝐞 𝐕𝐢𝐞𝐰, 𝐒𝐚𝐥𝐞𝐬 𝐕𝐢𝐞𝐰, 𝐌𝐚𝐫𝐤𝐞𝐭𝐢𝐧𝐠 𝐕𝐢𝐞𝐰, 𝐒𝐮𝐩𝐩𝐥𝐲 𝐂𝐡𝐚𝐢𝐧 𝐕𝐢𝐞𝐰:

✔ Gross price
✔ Pre-invoice deductions
✔ Post-invoice deductions
✔ Net Invoice sale
✔ Gross Margin
✔ Net Sales 
✔ Net profit
✔ COGS: [The Cost of Goods Sold]
✔ Net Invoice sale
✔ YTD: Year to Date
✔ YTG: Year to Go

**Company Background**

AtliQ Hardware has rapidly expanded over the past few years, establishing its presence globally. The company specializes in selling computers and computer accessories through three main channels: 
•	Retailers
•	Direct Sales 
•	Distributors

However, a recent setback occurred when a new store in America failed to perform as expected. This decision was based on surveys, intuition, and basic Excel analysis, which proved insufficient in the face of growing competition. AtliQ’s competitors, equipped with strong analytics teams, have been leveraging data-driven strategies to gain a competitive edge.
To stay competitive and make informed decisions in the future, AtliQ Hardware has decided to build its own analytics team. The goal is to use advanced tools like Power BI to uncover insights and support smarter decision-making across key areas like sales, finance, marketing, and supply chain.

**Project Kick-Off**
During the kick-off session, it’s essential to clarify the purpose of the project and address any uncertainties. Key questions should focus on:
•	Why this project is critical for the company.
•	What specific goals and insights are expected.
•	How the data analytics team will support business growth.
•	This step ensures alignment and sets the foundation for a successful analytics journey

**Questions to Ask Before Starting the Dashboard**
1.	Objective: What is the main goal of creating this Power BI dashboard?
2.	Success Metrics: How will we measure the success of this project?
3.	Deadline: What is the timeline for completing the dashboard?
4.	Stakeholder Feedback: Do stakeholders expect a preview before the final release?
5.	Expectations: What outcomes are stakeholders hoping to achieve with this dashboard?
6.	Concerns: What concerns do stakeholders have about building this dashboard?
7.	Audience: Who will use this dashboard, and what decisions will it help them make?
8.	Completion Goals: What do stakeholders expect from the completed project?
9.	Potential Challenges: What could go wrong during the development process?
10.	Resources Needed: What data or resources are required to build the dashboard?
11.	Design Inputs: Do stakeholders have specific design or visualization preferences?
Moving Forward
Once the kick-off meeting is complete, and the data engineering team provides the requested data, it’s time to dive into the dataset. Exploring and understanding the data will set the stage for creating a dashboard that meets business goals and delivers actionable insights.


**Understanding the Dataset for Analysis**

Before diving into analysis, it's essential to have a clear understanding of the data available. This helps in making informed decisions and identifying the right tools and techniques for analysis.
Dimension Tables:

•	These tables contain static information such as customer and product details.

o	dim_customer: Includes details about 75 customers spread across 27 markets (e.g., India, USA, Spain), covering 2 types of platforms (Brick & Mortar stores and E-commerce platforms like Amazon and Flipkart), and 3 sales channels (Retailers, Direct, Distributors).
o	dim_market: Contains information on 27 markets and their regions and sub-zones, such as APAC, EU, and LATAM.
o	dim_product: Details about product divisions, categories (e.g., Internal HDD, keyboard), and variants.

Fact Tables:
•	These tables store transactional data such as sales and forecasted quantities.
o	fact_forecast_monthly: Provides forecasts on customer needs (helping with inventory and customer satisfaction).
o	fact_sales_monthly: Contains actual sales data, similar to the forecast table, but instead of forecasted quantities, it has sold quantities.

Other Tables:
•	gdb041: Includes essential data for understanding sales operations across different markets.
•	gdb056: Includes tables like freight_cost, gross_price, manufacturing_cost, pre_invoice_deductions, and post_invoice_deductions, which provide financial and operational insights.

**Importing Data into Power BI**

Since the data is stored in MySQL, to bring it into Power BI, you'll need to connect Power BI to the MySQL database by entering the database credentials (username, password, etc.) to import the necessary datasets. This allows you to work directly with the data in Power BI to create insights.
By understanding the dataset, you'll be well-prepared to create dashboards and reports that address business needs and enhance decision-making.

**Data Model**

In data analysis and reporting, data modeling is essential as it serves as the foundation for creating accurate and efficient reports. A strong data model ensures that the visuals you build are based on well-structured, reliable data. Without good data modeling, the performance and functionality of your reports can suffer.

To make sure our reports run smoothly, we follow best practices in data modeling. These practices help ensure data is organized and easy to work with, improving both performance and usability. For this project, we’ve implemented the Snowflake Schema data modeling method, which helps break down data into smaller, more manageable pieces and minimizes redundancy.

By following these practices, we ensure that our reports are optimized and ready to deliver insightful, high-performing visuals.

<img width="720" alt="Project_Screenshot2_updated" src="https://github.com/user-attachments/assets/602627aa-4adc-4a9b-8de4-3b7638929889">


**Dashboard Designing**

When building the dashboard, we begin by referencing the mock-ups received as part of the requirements. The team will design each visual and create necessary measures step by step, ensuring that each component serves its purpose.

**Home View**

The Home View will feature buttons for easy navigation. Users can click on a specific button to access different areas of the dashboard:

•	Info
•	Finance View
•	Sales View
•	Marketing View
•	Supply Chain View
•	Executive View
•	Products
•	Support

Each button will direct users to its respective detailed view, ensuring they can quickly access the information they need.
