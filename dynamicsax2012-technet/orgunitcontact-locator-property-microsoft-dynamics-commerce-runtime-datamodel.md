﻿---
title: OrgUnitContact.Locator Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Locator Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.Locator
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitcontact.locator(v=AX.60)
ms:contentKeyID: 62202061
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.Locator
dev_langs:
- CSharp
- C++
- VB
---

# Locator Property

Gets the address value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property Locator As String
    Get
    Friend Set
'Usage
Dim instance As OrgUnitContact
Dim value As String

value = instance.Locator
```

``` csharp
public string Locator { get; internal set; }
```

``` c++
public:
property String^ Locator {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitContact Class](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
