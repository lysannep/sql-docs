---
title: "Creating an OLE DB Driver for SQL Server Application | Microsoft Docs"
description: Learn about the steps necessary to create an OLE DB Driver for SQL Server application and find additional resources.
ms.custom: ""
ms.date: "06/14/2018"
ms.prod: sql
ms.prod_service: "database-engine, sql-database, synapse-analytics, pdw"
ms.reviewer: ""
ms.technology: connectivity
ms.topic: "reference"
helpviewer_keywords: 
  - "OLE DB Driver for SQL Server, application creation"
  - "applications [OLE DB Driver for SQL Server]"
  - "OLE DB, creating applications"
author: David-Engel
ms.author: v-daenge
---
# Creating an OLE DB Driver for SQL Server Application
[!INCLUDE [SQL Server](../../../includes/applies-to-version/sql-asdb-asdbmi-asa-pdw.md)]

[!INCLUDE[Driver_OLEDB_Download](../../../includes/driver_oledb_download.md)]

  Creating an OLE DB Driver for SQL Server application involves these steps:  
  
1.  Establishing a connection to a data source.  
  
2.  Executing a command.  
  
3.  Processing the results.  
  
> [!NOTE]  
>  When possible, use Windows Authentication. If Windows Authentication is not available, prompt users to enter their credentials at run time. Avoid storing credentials in a file. If you must persist credentials, you should encrypt them with [the Win32 cryptoAPI](/windows/win32/seccng/cng-portal).  
  
## In This Section  
  
-   [Establishing a Connection to a Data Source](../../oledb/ole-db-driver/establishing-a-connection-to-a-data-source.md)  
  
-   [Executing a Command](../../oledb/ole-db-driver/executing-a-command.md)  
  
-   [Processing Results](../../oledb/ole-db-driver/processing-results.md)  
  
-   [About OLE DB Properties](../../oledb/ole-db-driver/about-ole-db-properties.md)  
  
-   [Using the OUTPUT Clause with OLE DB in OLE DB Driver for SQL Server](../../oledb/ole-db-driver/using-the-output-clause-with-ole-db-in-oledb-driver-for-sql-server.md)  
  
## See Also  
 [OLE DB Driver for SQL Server Programming](../../oledb/ole-db/oledb-driver-for-sql-server-programming.md)  
  
