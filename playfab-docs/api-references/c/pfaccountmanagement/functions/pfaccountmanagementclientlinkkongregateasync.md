---
author: jasonsandlin
title: "PFAccountManagementClientLinkKongregateAsync"
description: "Links the Kongregate identifier to the user's PlayFab account"
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 09/25/2023
---

# PFAccountManagementClientLinkKongregateAsync  

Links the Kongregate identifier to the user's PlayFab account  

## Syntax  
  
```cpp
HRESULT PFAccountManagementClientLinkKongregateAsync(  
    PFEntityHandle entityHandle,  
    const PFAccountManagementLinkKongregateAccountRequest* request,  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`entityHandle`** &nbsp; PFEntityHandle  
  
PFEntityHandle to use for authentication.  
  
**`request`** &nbsp; [PFAccountManagementLinkKongregateAccountRequest*](../../pfaccountmanagementtypes/structs/pfaccountmanagementlinkkongregateaccountrequest.md)  
  
Populated request object.  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
This API is available on Win32. See also ClientLoginWithKongregateAsync, ClientUnlinkKongregateAsync. Call XAsyncGetStatus to get the status of the operation. If the service call is unsuccessful, the async result will be E_PF_FEATURE_NOT_CONFIGURED_FOR_TITLE, E_PF_INVALID_KONGREGATE_TOKEN, E_PF_LINKED_ACCOUNT_ALREADY_CLAIMED or any of the global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
## Requirements  
  
**Header:** PFAccountManagement.h
  
## See also  
[PFAccountManagement members](../pfaccountmanagement_members.md)  

  
  
