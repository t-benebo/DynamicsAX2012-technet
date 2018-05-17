﻿---
title: NonSalesTransaction.AmountInCompanyCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountInCompanyCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.AmountInCompanyCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestransaction.amountincompanycurrency(v=AX.60)
ms:contentKeyID: 65321024
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.AmountInCompanyCurrency
dev_langs:
- CSharp
- C++
- VB
---

# AmountInCompanyCurrency Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("AMOUNTMST")> _
Public Property AmountInCompanyCurrency As Decimal
    Get
    Set
'Usage
Dim instance As NonSalesTransaction
Dim value As Decimal

value = instance.AmountInCompanyCurrency

instance.AmountInCompanyCurrency = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("AMOUNTMST")]
public decimal AmountInCompanyCurrency { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"AMOUNTMST")]
public:
property Decimal AmountInCompanyCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[NonSalesTransaction Class](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
