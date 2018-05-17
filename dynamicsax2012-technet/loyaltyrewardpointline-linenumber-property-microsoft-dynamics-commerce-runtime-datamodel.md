﻿---
title: LoyaltyRewardPointLine.LineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.LineNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.linenumber(v=AX.60)
ms:contentKeyID: 62211900
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.LineNumber
dev_langs:
- CSharp
- C++
- VB
---

# LineNumber Property

Gets or sets the line number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINENUM")> _
Public Property LineNumber As Decimal
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Decimal

value = instance.LineNumber

instance.LineNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINENUM")]
public decimal LineNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINENUM")]
public:
property Decimal LineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
