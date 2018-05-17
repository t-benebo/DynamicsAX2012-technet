﻿---
title: HardwareProfile.ScaleDeviceTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScaleDeviceTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleDeviceTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.scaledevicetypevalue(v=AX.60)
ms:contentKeyID: 62211885
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleDeviceTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# ScaleDeviceTypeValue Property

Gets or sets the value of the scale device type enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ScaleDeviceTypeValue As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.ScaleDeviceTypeValue

instance.ScaleDeviceTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int ScaleDeviceTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ScaleDeviceTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
