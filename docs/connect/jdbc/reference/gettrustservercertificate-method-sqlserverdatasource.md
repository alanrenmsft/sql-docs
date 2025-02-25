---
description: "getTrustServerCertificate Method (SQLServerDataSource)"
title: "getTrustServerCertificate Method (SQLServerDataSource) | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ""
ms.technology: connectivity
ms.topic: reference
apiname: 
  - "getTrustServerCertificate Method (SQLServerDataSource)"
apilocation: 
  - "getTrustServerCertificate Method (SQLServerDataSource)"
apitype: "Assembly"
ms.assetid: e4f443cc-b5d7-4859-81df-836a8642ed07
author: David-Engel
ms.author: v-davidengel
---
# getTrustServerCertificate Method (SQLServerDataSource)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Returns a **Boolean** value that indicates if the trustServerCertificate property is enabled.  
  
## Syntax  
  
```  
  
public boolean getTrustServerCertificate()  
```  
  
## Return Value  
 **true** if trustServerCertificate is enabled. Otherwise, **false**.  
  
## Remarks  
 If the trustServerCertificate property is set to **true**, the [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] Transport Layer Security (TLS), previously known as Secure Sockets Layer (SSL), certificate is automatically trusted when the communication layer is encrypted using TLS. In other words, the [!INCLUDE[jdbcNoVersion](../../../includes/jdbcnoversion_md.md)] will not validate the [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] TLS/SSL certificate. The default value is **false**.  
  
 If the trustServerCertificate property is set to **false**, the [!INCLUDE[jdbcNoVersion](../../../includes/jdbcnoversion_md.md)] will validate the server TLS/SSL certificate.  
  
## See Also  
 [SQLServerDataSource Members](../../../connect/jdbc/reference/sqlserverdatasource-members.md)   
 [SQLServerDataSource Class](../../../connect/jdbc/reference/sqlserverdatasource-class.md)  
  
  
