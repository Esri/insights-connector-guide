# Examples of connector configuration files
This folder contains examples of the database connectors that have been tested with Insights. Each type of database connectors has one sub-folder. 

There are two files in each connector (sub-folder):
* **properties.yml**: lists connection properties for connecting to this type of databases
* **dialect.yml**: defines relevent database settings, mostly consisting of definition of capabilities and a list of supported SQL functions

## Notes:
1. The required files for adding a new connector to Insights are:
   * properties.yml
   * dialect.yml
   * Vendor's JDBC driver
2. The JDBC driver is not included. You need to get the jdbc driver from vendor's website.
3. Zip all files in a one bundle.
4. Upload the zip file when you add the connector.
