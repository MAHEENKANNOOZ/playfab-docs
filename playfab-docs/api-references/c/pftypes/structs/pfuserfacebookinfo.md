---
author: jasonsandlin
title: "PFUserFacebookInfo"
description: "PFUserFacebookInfo data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFUserFacebookInfo  

PFUserFacebookInfo data model.  

## Syntax  
  
```cpp
typedef struct PFUserFacebookInfo {  
    const char* facebookId;  
    const char* fullName;  
} PFUserFacebookInfo;  
```
  
### Members  
  
**`facebookId`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Facebook identifier.
  
**`fullName`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Facebook full name.
  
  
## Requirements  
  
**Header:** PFTypes.h
  
## See also  
[PFTypes members](../pftypes_members.md)  

  
  
