---
author: jasonsandlin
title: "PFInventoryRedemptionFailure"
description: "PFInventoryRedemptionFailure data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFInventoryRedemptionFailure  

PFInventoryRedemptionFailure data model.  

## Syntax  
  
```cpp
typedef struct PFInventoryRedemptionFailure {  
    const char* failureCode;  
    const char* failureDetails;  
    const char* marketplaceTransactionId;  
    const char* offerId;  
} PFInventoryRedemptionFailure;  
```
  
### Members  
  
**`failureCode`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) The marketplace failure code.
  
**`failureDetails`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) The marketplace error details explaining why the offer failed to redeem.
  
**`marketplaceTransactionId`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) The transaction id in the external marketplace.
  
**`offerId`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) The ID of the offer being redeemed.
  
  
## Requirements  
  
**Header:** PFInventoryTypes.h
  
## See also  
[PFInventoryTypes members](../pfinventorytypes_members.md)  

  
  
