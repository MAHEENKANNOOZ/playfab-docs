---
author: jasonsandlin
title: "PFCatalogGetCatalogConfigResponse"
description: "PFCatalogGetCatalogConfigResponse data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 06/26/2023
---

# PFCatalogGetCatalogConfigResponse  

PFCatalogGetCatalogConfigResponse data model.  

## Syntax  
  
```cpp
typedef struct PFCatalogGetCatalogConfigResponse {  
    PFCatalogCatalogConfig const* config;  
} PFCatalogGetCatalogConfigResponse;  
```
  
### Members  
  
**`config`** &nbsp; [PFCatalogCatalogConfig](pfcatalogcatalogconfig.md) const*  
*may be nullptr*  
  
(Optional) The catalog configuration.
  
  
## Requirements  
  
**Header:** PFCatalogTypes.h
  
## See also  
[PFCatalogTypes members](../pfcatalogtypes_members.md)  

  
  
