### Data Connections in Power BI
The first step in the development lifecycle of Power BI is to connect to different data sources. In Power BI, there are mainly 2 ways in which the data source is connected.
**Import mode**
**Direct query**
## Import connection:
  * In import mode, data from the source system is imported into Power BI's internal data model. This means that Power BI stores a copy of the data locally, within the PBIX file or in the Power BI Service (if published). The data is loaded into memory, allowing for fast analysis and visualization.

# Advantages:
* Performance: Since the data is stored locally, querying and visualization are typically faster because there's no need to query the source system repeatedly.
* Offline Access: Once the data is imported, users can analyze and visualize it without needing a connection to the source system.
* Data Transformation: Import mode allows for extensive data transformation and modeling within Power BI using Power Query Editor.

# Considerations:
* Data Refresh: Data in import mode needs to be refreshed periodically to ensure it reflects the latest data from the source system.
* Data Volume: Import mode is suitable for moderate to large datasets that can fit comfortably into memory. Extremely large datasets may cause performance issues or require additional resources.



