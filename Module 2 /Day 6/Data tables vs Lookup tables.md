### Data Tables
Data tables, also known as fact tables, are central to the data model. They contain the core business data with metrics that users want to analyze. These tables usually have a large number of records and store transactional or event data.

Typically contains a large number of rows, reflecting individual transactions or events.

### Lookup Tables
Lookup tables, also known as dimension tables, contain descriptive attributes that provide context to the data in fact tables. They define the dimensions by which data can be filtered, grouped, or sliced.

Usually contain fewer rows compared to fact tables, representing distinct categories or entities.

### Relationships and Modeling
# Relationships: 
Data tables and lookup tables are often connected through relationships, typically using primary keys from lookup tables and foreign keys in data tables. This relationship is usually one-to-many, where each record in the lookup table can relate to multiple records in the data table.

For example, a single ProductID in the product lookup table may be associated with multiple entries in the sales data table.

# Modeling: 
In a typical star schema, the fact table (data table) is at the center, surrounded by several dimension tables (lookup tables). This schema is efficient for queries and analysis in Power BI.

### Summary
Data Tables are for storing detailed, metric-focused data points, ideal for deep analysis and reporting of business metrics.
Lookup Tables provide descriptive context and categorical data, enabling filtering, grouping, and summarization of the metrics from the data tables.
