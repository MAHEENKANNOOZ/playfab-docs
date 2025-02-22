---
author: jasonsandlin
title: "PFAuthenticationLoginWithCustomIDAsync"
description: "Signs the user in using a custom unique identifier generated by the title, returning a session identifier that can subsequently be used for API calls which require an authenticated user"
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 06/20/2023
---

# PFAuthenticationLoginWithCustomIDAsync  

Signs the user in using a custom unique identifier generated by the title, returning a session identifier that can subsequently be used for API calls which require an authenticated user  

## Syntax  
  
```cpp
HRESULT PFAuthenticationLoginWithCustomIDAsync(  
    PFServiceConfigHandle serviceConfigHandle,  
    const PFAuthenticationLoginWithCustomIDRequest* request,  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`serviceConfigHandle`** &nbsp; PFServiceConfigHandle  
  
PFServiceConfigHandle returned from PFServiceConfigCreateHandle call.  
  
**`request`** &nbsp; [PFAuthenticationLoginWithCustomIDRequest*](../../pfauthenticationtypes/structs/pfauthenticationloginwithcustomidrequest.md)  
  
Populated request object.  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
This API is available on all platforms. It is highly recommended that developers ensure that it is extremely unlikely that a customer could generate an ID which is already in use by another customer. If this is the first time a user has signed in with the Custom ID and CreateAccount is set to true, a new PlayFab account will be created and linked to the Custom ID. In this case, no email or username will be associated with the PlayFab account. Otherwise, if no PlayFab account is linked to the Custom ID, an error indicating this will be returned, so that the title can guide the user through creation of a PlayFab account. See also ClientLinkCustomIDAsync, ClientUnlinkCustomIDAsync. When the asynchronous task is complete, call [PFAuthenticationLoginWithCustomIDGetResult](pfauthenticationloginwithcustomidgetresult.md) to get the result.
  
## Requirements  
  
**Header:** PFAuthentication.h
  
## See also  
[PFAuthentication members](../pfauthentication_members.md)  

  
  
