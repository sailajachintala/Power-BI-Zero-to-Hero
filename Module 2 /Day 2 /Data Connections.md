## Data Connections in Power BI
The first step in the development lifecycle of Power BI is to connect to different data sources. In Power BI, there are mainly 2 ways in which the data source can be connected.
**Import mode** and
**Direct query**
### Import connection:
  * In import mode, data from the source system is imported into Power BI's internal data model. This means that Power BI stores a copy of the data locally, within the PBIX file or in the Power BI Service (if published). The data is loaded into memory, allowing for fast analysis and visualization.
    
**Advantages:**
* Performance: Since the data is stored locally, querying and visualization are typically faster because there's no need to query the source system repeatedly.
* Offline Access: Once the data is imported, users can analyze and visualize it without needing a connection to the source system.
* Data Transformation: Import mode allows for extensive data transformation and modeling within Power BI using Power Query Editor.
**Considerations:**
* Data Refresh: Data in import mode needs to be refreshed periodically to ensure it reflects the latest data from the source system.
* Data Volume: Import mode is suitable for moderate to large datasets that can fit comfortably into memory. Extremely large datasets may cause performance issues or require additional resources.

### Direct query:
In direct query mode, Power BI does not import data into its internal data model. Instead, it sends queries directly to the source system in real-time whenever a user interacts with visualizations or data. The data displayed in Power BI visuals is always live and reflects the current state of the data in the source system.

**Advantages:**
* Real-Time Data: Direct query mode provides access to real-time data from the source system, ensuring users always see the most up-to-date information.
* Scalability: Direct query mode allows Power BI to handle large datasets without concerns about memory limitations.
* Reduced Data Redundancy: Since data isn't duplicated in Power BI, there's no risk of inconsistencies between the data in Power BI and the source system.

**Considerations:**
* Performance: Direct query mode may result in slower query response times compared to import mode, especially for complex queries or large datasets.
* Limited Transformations: Power Query Editor capabilities are limited in direct query mode since transformations are performed directly on the source system.
* Compatibility: Not all data sources support direct query mode, so compatibility with the source system needs to be verified.

