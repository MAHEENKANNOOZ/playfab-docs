---
author: jasonsandlin
title: "PFCatalogCreateDraftItemResponse"
description: "PFCatalogCreateDraftItemResponse data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFCatalogCreateDraftItemResponse  

PFCatalogCreateDraftItemResponse data model.  

## Syntax  
  
```cpp
typedef struct PFCatalogCreateDraftItemResponse {  
    PFCatalogCatalogItem const* item;  
} PFCatalogCreateDraftItemResponse;  
```
  
### Members  
  
**`item`** &nbsp; [PFCatalogCatalogItem](pfcatalogcatalogitem.md) const*  
*may be nullptr*  
  
(Optional) Updated metadata describing the catalog item just created.
  
  
## Requirements  
  
**Header:** PFCatalogTypes.h
  
## See also  
[PFCatalogTypes members](../pfcatalogtypes_members.md)  

  
  
