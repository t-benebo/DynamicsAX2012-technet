﻿---
title: SalesTransactionConverter.ConvertFromData Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConvertFromData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionConverter.ConvertFromData(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.salestransactionconverter.convertfromdata(v=AX.60)
ms:contentKeyID: 62205331
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionConverter.ConvertFromData
dev_langs:
- CSharp
- C++
- VB
---

# ConvertFromData Method

Converts from sales transaction database representation to a sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertFromData ( _
    salesTransactionData As SalesTransactionData _
) As SalesTransaction
'Usage
Dim salesTransactionData As SalesTransactionData
Dim returnValue As SalesTransaction

returnValue = SalesTransactionConverter.ConvertFromData(salesTransactionData)
```

``` csharp
public static SalesTransaction ConvertFromData(
    SalesTransactionData salesTransactionData
)
```

``` c++
public:
static SalesTransaction^ ConvertFromData(
    SalesTransactionData^ salesTransactionData
)
```

#### Parameters

  - salesTransactionData  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales transaction.  

## See Also

#### Reference

[SalesTransactionConverter Class](salestransactionconverter-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)
