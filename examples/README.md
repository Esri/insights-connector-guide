# Example connector configuration files
This folder contains examples of the database connectors that have been tested with Insights. Each type of database connector has one sub-folder. 

There are two files for each connector:
* `properties.yml`: Defines the connection properties for the databaselists.
* `dialect.yml`: Defines the supported functions, capabilities, and expressions used for the database.

> **Note**: A Properties file (properties.yml), SQL dialect file (dialect.yml), and JDBC driver are required to add a connector in Insights. The JDBC driver must be downloaded separately from the database vendor’s website. For more information, see [Create a connector type bundle](https://github.com/ArcGIS/insights-connector-guide/wiki/Create-a-connector-type-bundle) and [Manage connector types](https://doc.arcgis.com/en/insights/latest/administer/manage-connector-types.htm).
