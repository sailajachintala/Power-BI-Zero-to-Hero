## Datawarehouse Architecture
**Scenario**: Lets consider a real time example of banking system to understand Datawarehouse architecture. SBI bank is located in different locations across the globe with several branches in each location. For this understanding, lets consider that this bank is operating in the US, UK, and India. 
Now the top management of SBI bank would like to know their business across different locations to identify in which location the business is doing good and where they need to focus to increase the running business. 

![R](https://github.com/sailajachintala/Power-BI-Zero-to-Hero/assets/65940748/4bdd9fca-3425-476e-9b08-21ad41761d8e)

**Components of Datawarehouse(DWH):**
1. OLTP (Online Transactional Processing System)
2. ETL (Extract Transform Loading)
3. OLAP (Online Analytical Processing System)/DWH
4. BI (Business Intelligence)

OLTP: It holds day to day transactions. Example: any transaction performed at an ATM is updated and reflected immediately
ETL: It is the process of extracting data from multiple sources and transforming the data into required format and finally loading the information to DWH for business analysis
OLAP/DWH: It is the permanent location that holds the transformed information which is then used for performing Business analysis and reporting.It stores historical information.
BI: It is the process of incorporating Intelligence to the information stored in the DWH by performing analysis and reporting.



