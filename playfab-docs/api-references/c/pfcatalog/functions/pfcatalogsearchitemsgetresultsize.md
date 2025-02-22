---
author: jasonsandlin
title: "PFCatalogSearchItemsGetResultSize"
description: "Get the size in bytes needed to store the result of a SearchItems call."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFCatalogSearchItemsGetResultSize  

Get the size in bytes needed to store the result of a SearchItems call.  

## Syntax  
  
```cpp
HRESULT PFCatalogSearchItemsGetResultSize(  
    XAsyncBlock* async,  
    size_t* bufferSize  
)  
```  
  
### Parameters  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
**`bufferSize`** &nbsp; size_t*  
*output*  
  
The buffer size in bytes required for the result.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation. If the service call is unsuccessful, the result will be E_PF_DATABASE_THROUGHPUT_EXCEEDED, E_PF_ITEM_NOT_FOUND, E_PF_NOT_IMPLEMENTED or any of the global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
  
## Requirements  
  
**Header:** PFCatalog.h
  
## See also  
[PFCatalog members](../pfcatalog_members.md)  

  
  
