﻿---
title: SaveDropAndDeclareServiceRequest.ShiftTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShiftTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest.ShiftTerminalId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.savedropanddeclareservicerequest.shiftterminalid(v=AX.60)
ms:contentKeyID: 62203446
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest.ShiftTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftTerminalId Property

Gets or sets the shift terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftTerminalId As String
    Get
    Set
'Usage
Dim instance As SaveDropAndDeclareServiceRequest
Dim value As String

value = instance.ShiftTerminalId

instance.ShiftTerminalId = value
```

``` csharp
[DataMemberAttribute]
public string ShiftTerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShiftTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SaveDropAndDeclareServiceRequest Class](savedropanddeclareservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)
