---
author: jasonsandlin
title: "PFDataInitiateFileUploadMetadata"
description: "PFDataInitiateFileUploadMetadata data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFDataInitiateFileUploadMetadata  

PFDataInitiateFileUploadMetadata data model.  

## Syntax  
  
```cpp
typedef struct PFDataInitiateFileUploadMetadata {  
    const char* fileName;  
    const char* uploadUrl;  
} PFDataInitiateFileUploadMetadata;  
```
  
### Members  
  
**`fileName`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Name of the file.
  
**`uploadUrl`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Location the data should be sent to via an HTTP PUT operation.
  
  
## Requirements  
  
**Header:** PFDataTypes.h
  
## See also  
[PFDataTypes members](../pfdatatypes_members.md)  

  
  
