# SSIS_DTSX_Examples
SQL Integrations Services

1.- CDC (Change Data Capture): move data between database source and target (stage database) using CDC to detect changes when in the resposity is Inserting, Updating or Deleting. This project segregate from a datasource to a stage database in 3 tables (Updating, Inserting and Deleting). This project show you how retrieve only modifications that have occurred after the last load to the data warehouse.  CDC can be implemented in the Enterprise Edition of SQL Server 2008 or later version. We need enable CDC in the involved tables. 
