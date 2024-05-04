Open Azure portal and sign in.
Create a target instance of Azure SQL Database.(Resource group, Database, and Server)
When creating the server use SQL Authentication, and set username and password.
Launch Azure data studio.
In Azure Data Studio, go to Connections. Select and connect to your on-premises instance of SQL Server.
Install the Azure SQL Migration extension from Azure Data Studio Marketplace.
Right-click the server connection and select Manage.
In the server menu under General, select Azure SQL Migration. Then select Migrate to Azure SQL to open the migration wizard.
In the Migrate to Azure SQL wizard, select the databases you want to assess. Click next
Select Azure SQL Database. Click next.
Select the database, and then review the assessment report. Click next.
Select your Azure account, Azure subscription, the Azure region or location, and the resource group that contains the Azure SQL Database deployment.
For Azure SQL Database Server, select the target Azure SQL Database server. Enter a username and password for the target database deployment. Then, select Connect.
Map the source database and the target database for the migration. For Target database, select the Azure SQL Database target. Click next.
Select Offline migration. Click next
Under Source credentials, enter the source SQL Server credentials.
Under Select tables, select the Edit pencil icon.
Select the schema to migrate to the target.
Update tables and input values before you start migration.
In Resource group, select the resource group that contains an existing instance of Database Migration Service.
Under the Azure Database Migration Service, create a new Database Migration Service in the selected resource group.
Download and install Integration Runtime via the link.
In the Authentication key table, copy one of the authentication keys that are provided in the wizard and paste it in Azure Data Studio.
Select Test connection to validate that the newly created Database Migration Service.
Select start migration and allow migration to be completed successfully.
