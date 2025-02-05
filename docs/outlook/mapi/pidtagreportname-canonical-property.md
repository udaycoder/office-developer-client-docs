---
title: "PidTagReportName Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- MAPI.PidTagReportName
api_type:
- COM
ms.assetid: 4ec3100f-7cf1-4702-b326-e6da586a7bb2
description: "Contains the display name for the recipient that should get reports for this message. A client application should set this property at submission time."
---

# PidTagReportName Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains the display name for the recipient that should get reports for this message.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_REPORT_NAME, PR_REPORT_NAME_A, PR_REPORT_NAME_W  <br/> |
|Identifier:  <br/> |0x003A  <br/> |
|Data type:  <br/> |PT_STRING8, PT_UNICODE  <br/> |
|Area:  <br/> |MAPI envelope  <br/> |
   
## Remarks

These properties are examples of the address properties for the recipient that the sender has delegated to receive any reports generated for this message.
  
A client application that must route reports to another user should set these properties at message submission time. If they are not set, the reports are sent to the message sender.
  
## Related resources

### Header files

Mapidefs.h
  
> Provides data type definitions.
    
Mapitags.h
  
> Contains definitions of properties listed as alternate names.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

