---
author: jasonsandlin
title: "PFAuthenticationReLoginWithOpenIdConnectAsync"
description: "Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFAuthenticationReLoginWithOpenIdConnectAsync  

Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it.  

## Syntax  
  
```cpp
HRESULT PFAuthenticationReLoginWithOpenIdConnectAsync(  
    PFEntityHandle entityHandle,  
    const PFAuthenticationLoginWithOpenIdConnectRequest* request,  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`entityHandle`** &nbsp; PFEntityHandle  
  
PFEntityHandle to re-login.  
  
**`request`** &nbsp; [PFAuthenticationLoginWithOpenIdConnectRequest*](../../pfauthenticationtypes/structs/pfauthenticationloginwithopenidconnectrequest.md)  
  
Populated request object.  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
Call XAsyncGetStatus to get the status of the operation. If successful, the cached EntityToken for the PFEntityHandle will be updated in place.
  
## Requirements  
  
**Header:** PFAuthentication.h
  
## See also  
[PFAuthentication members](../pfauthentication_members.md)  

  
  
