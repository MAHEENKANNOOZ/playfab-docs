---
author: jasonsandlin
title: "PFPlayerDataManagementServerUpdateUserPublisherReadOnlyDataGetResult"
description: "Gets the result of a successful PFPlayerDataManagementServerUpdateUserPublisherReadOnlyDataAsync call."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 09/25/2023
---

# PFPlayerDataManagementServerUpdateUserPublisherReadOnlyDataGetResult  

Gets the result of a successful PFPlayerDataManagementServerUpdateUserPublisherReadOnlyDataAsync call.  

## Syntax  
  
```cpp
HRESULT PFPlayerDataManagementServerUpdateUserPublisherReadOnlyDataGetResult(  
    XAsyncBlock* async,  
    PFPlayerDataManagementUpdateUserDataResult* result  
)  
```  
  
### Parameters  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
**`result`** &nbsp; [PFPlayerDataManagementUpdateUserDataResult*](../../pfplayerdatamanagementtypes/structs/pfplayerdatamanagementupdateuserdataresult.md)  
*output*  
  
PFPlayerDataManagementUpdateUserDataResult object that will be populated with the result.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation. If the service call is unsuccessful, the result will be E_PF_PUBLISHER_NOT_SET or any of the global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
  
## Requirements  
  
**Header:** PFPlayerDataManagement.h
  
## See also  
[PFPlayerDataManagement members](../pfplayerdatamanagement_members.md)  

  
  
