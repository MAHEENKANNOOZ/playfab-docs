---
author: jasonsandlin
title: "PFAccountManagementClientGetPlayerCombinedInfoGetResultSize"
description: "Get the size in bytes needed to store the result of a ClientGetPlayerCombinedInfo call."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFAccountManagementClientGetPlayerCombinedInfoGetResultSize  

Get the size in bytes needed to store the result of a ClientGetPlayerCombinedInfo call.  

## Syntax  
  
```cpp
HRESULT PFAccountManagementClientGetPlayerCombinedInfoGetResultSize(  
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
  
Result code for this API operation. If the service call is unsuccessful, the result will be E_PF_REQUEST_VIEW_CONSTRAINT_PARAMS_NOT_ALLOWED or any of the global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
  
## Requirements  
  
**Header:** PFAccountManagement.h
  
## See also  
[PFAccountManagement members](../pfaccountmanagement_members.md)  

  
  
