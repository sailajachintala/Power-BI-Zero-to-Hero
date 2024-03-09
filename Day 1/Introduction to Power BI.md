## Datawarehouse Architecture
**Scenario**: Lets consider a real time example of banking system to understand Datawarehouse architecture. SBI bank is located in different locations across the globe with several branches in each location. For this understanding, lets consider that this bank is operating in the US, UK, and India. 
Now the top management of SBI bank would like to know their business across different locations to identify in which location the business is doing good and where they need to focus to increase the running business. 

![R](https://github.com/sailajachintala/Power-BI-Zero-to-Hero/assets/65940748/4bdd9fca-3425-476e-9b08-21ad41761d8e)

**Components of Datawarehouse(DWH):**
1. OLTP (Online Transactional Processing System)
2. ETL (Extract Transform Loading)
3. OLAP (Online Analytical Processing System)/DWH
4. BI (Business Intelligence)

1. OLTP: It holds day to day transactions. Example: any transaction performed at an ATM is updated and reflected immediately
2. ETL: It is the process of extracting data from multiple sources and transforming the data into required format and finally loading the information to DWH for business analysis
3. OLAP/DWH: It is the permanent location that holds the transformed information which is then used for performing Business analysis and reporting.It stores historical information.
4. BI: It is the process of incorporating Intelligence to the information stored in the DWH by performing analysis and reporting.

**OLTP vs OLAP:**

<img width="482" alt="OLTP vs OLAP" src="https://github.com/sailajachintala/Power-BI-Zero-to-Hero/assets/65940748/829e2721-5b07-42bc-94e1-6e347fc4a4f4">

## What is Power BI?
Power BI is a business analytics tool developed by Microsoft. It allows users to visualize and analyze data from various sources in order to gain insights and make data-driven decisions. With Power BI, users can connect to a wide range of data sources, including databases, Excel files, cloud services, and web APIs, to create interactive reports and dashboards.

**Key Features of Power BI:**
1.  **Data Connectivity**: Power BI can connect to a wide range of data sources, including databases (SQL Server, Oracle, MySQL, etc.), cloud services (Azure, Google Analytics, Salesforce, etc.), files (Excel, CSV, XML, etc.), and even web sources (REST APIs, HTML, OData feeds, etc.).

2.  **Data Preparation**: Users can transform and shape data using Power Query, a powerful data transformation tool integrated into Power BI. This allows for cleaning, filtering, and structuring data before analysis.

3. **Data Modeling**: Power BI provides robust data modeling capabilities through its Data Model. Users can create relationships between tables, define calculated columns and measures using DAX (Data Analysis Expressions), and enrich the data model to support complex analytics.

4.  **Visualization**: Power BI offers a vast array of visualization options, including various charts, graphs, maps, tables, and custom visuals. Users can create interactive and compelling reports and dashboards to visualize insights and trends.

5.  **Advanced Analytics**: Power BI incorporates advanced analytics features such as forecasting, clustering, and sentiment analysis, enabling users to uncover deeper insights and trends within their data.

6.  **Natural Language Processing (Q&A)**: Users can ask questions about their data using natural language queries, and Power BI generates visualizations and insights based on the query, making data exploration more intuitive.

7.  **Sharing and Collaboration**: Power BI allows users to share reports and dashboards with colleagues and stakeholders securely. Collaboration features enable real-time collaboration, annotations, and discussions around data.

8.  **Security and Governance**: Power BI provides robust security features, including role-based access control (RBAC), row-level security (RLS), and encryption of data at rest and in transit, ensuring data protection and compliance with regulatory requirements.

9.  **Mobile Access**: Power BI offers native mobile apps for iOS, Android, and Windows devices, allowing users to access and interact with reports and dashboards on the go, ensuring data-driven decision-making anytime, anywhere.

10.  **Integration with Microsoft Ecosystem**: Power BI seamlessly integrates with other Microsoft products and services such as Azure, Office 365, Dynamics 365, and Excel, providing a unified experience for data analysis and reporting within the Microsoft ecosystem.

## Power BI Ecosystem:
<img width="706" alt="Ecosystem" src="https://github.com/sailajachintala/Power-BI-Zero-to-Hero/assets/65940748/4ab21327-261c-485f-bc65-337adea92b6e">



