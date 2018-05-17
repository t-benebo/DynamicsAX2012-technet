﻿---
title: SalesInvoice.TotalManualDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalManualDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.TotalManualDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.totalmanualdiscountamount(v=AX.60)
ms:contentKeyID: 62214805
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.TotalManualDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# TotalManualDiscountAmount Property

Gets or sets the manual total amount off value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOTALMANUALDISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property TotalManualDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As Decimal

value = instance.TotalManualDiscountAmount

instance.TotalManualDiscountAmount = value
```

``` csharp
[ColumnAttribute("TOTALMANUALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal TotalManualDiscountAmount { get; set; }
```

``` c++
[ColumnAttribute(L"TOTALMANUALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal TotalManualDiscountAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
