<properties
   pageTitle="What's New in Azure Data Catalog"
   description="Overview of new capabilities in the Azure Data Catalog preview."
   services="data-catalog"
   documentationCenter=""
   authors="steelanddata"
   manager="NA"
   editor=""
   tags=""/>
<tags
   ms.service="data-catalog"
   ms.devlang="NA"
   ms.topic="article"
   ms.tgt_pltfrm="NA"
   ms.workload="data-catalog"
   ms.date="01/29/2016"
   ms.author="maroche"/>

# What's new in Azure Data Catalog

Updates to **Azure Data Catalog** are released on a regular basis. Not every release will include new user-facing features, as some releases are focused on back-end service capabilities. This page will highlight new user-facing capabilities added to the **Azure Data Catalog** service.

## What's new for the week of January 29, 2016 release

As of the week of January 29, 2016, the following capabilities have been added to **Azure Data Catalog**:

- Support for manually registering additional data sources. Users can now use "Create Manual Entry" in the **Azure Data Catalog** portal, or use the **Azure Data Catalog** REST API to register the following data sources:
   + OData - Function, Entity Set, and Entity Container
   + HTTP - File, Endpoint, Report, and Site
   + File System - File
   + SharePoint - List
   + FTP - File and Directory
   + Salesforce.com - Object
   + DB2 - Table, View, and Database
   + PostgreSQL - Table, View, and Database
- Support for "Open in SQL Server Data Tools" for SQL Server (including Azure SQL DB and Azure SQL Data Warehouse) data sources.  

> [AZURE.NOTE] "Open in SQL Server Data Tools" requires Visual Studio 2013 with Update 4 and SQL Server Tooling to be installed. To install the latest version of SQL Server Data Tools, visit [Download SQL Server Data Tools (SSDT)](https://msdn.microsoft.com/library/mt204009.aspx).

## What's new for the week of January 22, 2016 release

As of the week of January 22, 2016, the following capabilities have been added to **Azure Data Catalog**:

- Support for registering and discovering SAP HANA views and packages. Users can register SAP HANA data sources using the **Azure Data Catalog** data source registration tool, and can annotate and discover registered SAP HANA data sources using the **Azure Data Catalog** portal.

## What's new for the week of January 8, 2016 release

As of the week of January 8, 2016, the following capabilities have been added to **Azure Data Catalog**:

- The ability to pin and unpin data assets in the **Azure Data Catalog** portal. Users can choose to pin data assets to make them easier to re-discover and re-use.
- A newly redesigned home page in the **Azure Data Catalog** portal. The new home page includes insight into the current users activity - including recently published assets, pinned assets, and saved searches - as well as insight into the activity in the Catalog as a whole.
- Support for persistent user settings in the **Azure Data Catalog** portal. User experience settings - including grid or tile view, the number of results per page, and hit highlighting on or off - are persisted between user sessions.
- **Azure Data Catalog** is now available in two new Azure regions. Customers can provision the **Azure Data Catalog** in the North Europe and Southeast Asia regions, in addition to East US, West US, West Europe, and Australia East. For more information, see [Azure Regions](https://azure.microsoft.com/regions/).

## What's new for the week of December 18, 2015 release

As of the week of December 18, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for data profiles for Azure SQL Data Warehouse data sources. When registering Azure SQL Data Warehouse tables and views, users can choose to include data profile metrics with the metadata extracted from the data source.
- Support for registering and discovering MySQL objects and databases. Users can register MySQL data sources using the **Azure Data Catalog** data source registration tool, and can annotate and discover registered MySQL data sources using the **Azure Data Catalog** portal.

## What's new for the week of December 4, 2015 release

As of the week of December 4, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for SPNEGO and Windows authentication for Teradata data sources. When registering Teradata tables and views, users can choose to connect to Teradata using SPNEGO and Windows as well as LDAP and TD2 authentication.
- Support for Azure Data Lake Store data sources. Users can now register and discover Azure Data Lake Store data sources using Azure Data Catalog.
- Support for manually specifying network proxy settings in the Azure Data Catalog data source registration tool. Users can select "Modify proxy settings" from the tool's welcome page, and can specify the proxy address and port to be used by the tool.


## What's new for the week of November 20, 2015 release

As of the week of November 20, 2015, the following capabilities have been added to **Azure Data Catalog**:

- The ability to view and copy connection strings from within the **Azure Data Catalog** portal for SQL Server (including Azure SQL Database) and Oracle data sources. Users can click on the "View Connection Strings" link in the connection information for a SQL Server or Oracle table, view, or database, to see the connection strings used to connect to the data source. ADO.NET, ODBC, OLEDB and JDBC connection strings are provided for SQL Server data sources. ODBC and OLEDB connection strings are provided for Oracle data sources.
- Support for including data profiles when registering Teradata tables and views.
- Support for "Open in Power BI Desktop" for SQL Server (including Azure SQL DB and Azure SQL Data Warehouse), SQL Server Analysis Services, Azure Storage, and HDFS sources.  

> [AZURE.NOTE] "Open in Power BI Desktop" requires a current version of the Power BI Desktop application to be installed. If you encounter problems or errors using this feature, please ensure that you have the latest version of Power BI Desktop from [PowerBI.com](https://powerbi.com).

## What's new for the week of November 13, 2015 release

As of the week of November 13, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for LDAP authentication for Teradata data sources. When registering Teradata tables and views, users can choose to connect to Teradata using LDAP as well as TD2 authentication.
- Support for "Open in Excel" for Teradata data sources.
- Support for recent search terms in the **Azure Data Catalog** portal. When searching in the portal, users can select from recently used search terms to accelerate the discovery experience.

## What's new for the week of November 6, 2015 release

As of the week of November 6, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for preview for Teradata data sources. When registering Teradata tables and views, users can choose to include snapshot records with the metadata extracted from the data source.
- Support for "Open in Excel" for Azure SQL Data Warehouse data sources.
- Support for defining and editing column-level schemas for manually registered data assets. After manually creating a data asset using the **Azure Data Catalog** portal, users can add column definitions in the data asset properties.
- Support for "has" queries when searching **Azure Data Catalog**, to enable the discovery of registered data assets that possess specific metadata. **Azure Data Catalog** query syntax now includes:

| Query syntax            | Purpose |
|-------------------------|---------|
| has:previews             | Finds data assets that include a preview  |
| has:documentation       | Finds data assets for which documentation has been provided |
| has:tableDataProfiles   | Finds data assets with table-level data profile information |
| has:columnsDataProfiles | Finds data assets with column-level data profile information |


## What's new for the week of October 30, 2015 release

As of the week of October 30, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for encryption at rest of data previews and data profiles for registered data sources. **Azure Data Catalog** will transparently encrypt any preview records and data profiles data sources registered with the service, without any need for key management by Catalog administrators.

## What's new for the week of October 23, 2015 release

As of the week of October 23, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for Teradata data sources. Users can now register and discover Teradata tables and views.

> [AZURE.NOTE] For the current release, only Teradata TD2 authentication is supported. Additional authentication mechanisms will be supported in future releases.

## What's new for the week of October 16, 2015 release

As of the week of October 16, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for on-premises Hive data sources. Users can now register and discover Hive tables for Apache Hive in Hadoop on-premises data sources.
- Support for saved searches in the **Azure Data Catalog** portal. Users can save search terms and filter selections to easily repeat previous searches and define useful views of the Catalog's contents. User can also mark a saved search as their default search. When a user clicks the "magnifying glass" search icon from the **Azure Data Catalog** portal home page or from the "getting started" page, the user will be taken directly to the saved search flagged as default.


## What's new for the week of October 9, 2015 release

As of the week of October 9, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for rich text documentation for registered data assets and containers in the Azure Data Catalog portal. Users can now provide documentation for data assets such as tables, views, and reports, and for containers such as databases and models, for scenarios where tags and descriptions are not sufficient.

## What's new for the week of October 2, 2015 release

As of the week of October 2, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for manually registering known data source types. Users can manually enter data source information using the **Azure Data Catalog** portal for all data source types supported by **Azure Data Catalog**.
- Support for authorizing Azure Active Directory security groups. Catalog administrators can enable catalog access to security groups as well as to user accounts, making it easier to manage access to **Azure Data Catalog**.
- Support for opening Hive data sources in Excel from the **Azure Data Catalog** portal.

> [AZURE.NOTE] To use the "Open in Excel" feature for Hive data sources, users must have installed the ODBC driver for Hive.

## What's new for the week of September 25, 2015 release

As of the week of September 25, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for including data profiles when registering Hive data sources.
- Support for programmatically discovering the Catalog API, making it easier for applications to integrate with **Azure Data Catalog**.

## What's new for the week of September 18, 2015 release

As of the week of September 18, 2015, the following capabilities have been added to **Azure Data Catalog**:

- A new "getting started" data source discovery experience in the **Azure Data Catalog** portal. When users enter the "discover" page of the  **Azure Data Catalog** portal without entering a search term, they will be presented with an overview of the catalog contents including the most frequently used tags, as well as experts, data source types and object types.
- Support for registering and discovering Azure SQL Data Warehouse objects and databases. For additional information on Azure SQL Data Warehouse, see [SQL Data Warehouse](https://azure.microsoft.com/services/sql-data-warehouse/).
- Support for registering and discovering SQL Server Analysis Services models and SQL Server Reporting Services servers as containers. When registering SSAS and SSRS objects, **Azure Data Catalog** will create an entry for the SSAS model and SSRS server as well as for the reports and other objects. The containers can be discovered and annotated using the **Azure Data Catalog** portal. Users can also search and filter the contents of a model or server in addition to searching and filtering the contents of the catalog.

> [AZURE.NOTE] SSAS and SSRS objects that have been registered prior to the September 18 release must be re-registered using the data source registration tool before the model or server entry will be added to the catalog. Re-registering a data source does not affect any annotations that have been added by users in the **Azure Data Catalog** portal.

## What's new for the week of September 11, 2015 release

As of the week of September 11, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for registering and discovering SQL Server Analysis Services objects via HTTP/HTTPS. Users can now connect to SSAS servers using a URL (such as https://servername/olap/msmdpump.dll) rather than a server name, and can use Basic authentication and Anonymous connections in addition to Windows authentication. For additional information on HTTP/HTTPS connections to SSAS, see [Configure HTTP Access to Analysis Services](https://msdn.microsoft.com/library/gg492140.aspx).
- Support for Hive data sources on HDInsight. Users can now register and discover Hive tables for Apache Hive in Hadoop on HDInsight data sources. For additional information on Hive on HDInsight, see the [HDInsight documentation center](../hdinsight-use-hive/).
- Support for registering and discovering Oracle databases and HDFS clusters as containers. When registering Oracle tables and views or HDFS , **Azure Data Catalog** will create an entry for the database as well as for the tables and views. The database can be discovered and annotated using the **Azure Data Catalog** portal. Users can also search and filter the contents of a database or cluster in addition to searching and filtering the contents of the catalog.


> [AZURE.NOTE] Oracle tables and views and HDFS files and directories that have been registered prior to the September 11 release must be re-registered using the data source registration tool before the database or cluster entry will be added to the catalog. Re-registering a data source does not affect any annotations that have been added by users in the **Azure Data Catalog** portal.

## What's new for the week of September 4, 2015 release

As of the week of September 4, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for manually registering unknown data source types. Users can manually enter data source information using the **Azure Data Catalog** portal, so that data sources not explicitly supported by the data source registration tool can be annotated and discovered.
- Support for registering and discovering SQL Server databases as containers. When registering SQL Server tables and views, **Azure Data Catalog** will create an entry for the database as well as for the tables and views. The database can be discovered and annotated using the **Azure Data Catalog** portal. Users can also search and filter the contents of a database in addition to searching and filtering the contents of the catalog.

> [AZURE.NOTE] SQL Server tables and views that have been registered prior to the September 4 release must be re-registered using the data source registration tool before the database entry will be added to the catalog. Re-registering a data source does not affect any annotations that have been added by users in the **Azure Data Catalog** portal.

## What's new for the week of August 28, 2015 release

As of the week of August 28, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for data profiling of SQL Server and Oracle data sources. When registering SQL Server and Oracle tables and views, users can choose to include data profile information for the objects being registered. The data profile includes object-level and column-level statistics.
- Support for Hadoop HDFS data sources. Users can now register and discover HDFS files and directories.

## What's new for the week of August 21, 2015 release

As of the week of August 21, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for providing access request information for registered data sources. For any registered data asset, users can now provide instructions for requesting access, including email links or URLs, to easily integrate with existing tools and processes.
- Tool tips for tags and experts, to make it easier to discover what users have provided what metadata for registered data assets.
- We’ve added a new “User” button and menu to our top navigation bar. This menu lets the user see the account used to log on to **Azure Data Catalog**, and to sign out if desired. This menu also displays the catalog name, which is valuable to developers using the **Azure Data Catalog** REST API.
- Standard Edition Only: When adding owners to data assets, **Azure Data Catalog** now supports both user accounts and security groups as owners. To add a security group as an owner for selected data assets, you can enter either the group’s display name or the group’s UPN email address, if it has one.
- Support for Azure Blob Storage data sources. Users can now register and discover Azure Storage blobs and directories.
