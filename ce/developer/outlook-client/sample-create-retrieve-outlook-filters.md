---
title: "Sample: Create and retrieve Outlook filters (Developer Guide for Dynamics 365 Customer Engagement)| MicrosoftDocs"
ms.custom: ""
ms.date: 10/31/2017
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "samples"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 72fd6888-2e5d-47a2-a1d3-f391e4d9f086
caps.latest.revision: 21
author: "JimDaly"
ms.author: "jdaly"
manager: "jdaly"
---
# Sample: Create and retrieve Outlook filters

> [!NOTE]
> Dynamics 365 for Outlook (Outlook client) is deprecated with the [!INCLUDE[pn-crm-9-0-0-online](../../includes/pn-crm-9-0-0-online.md)] release and will be removed in a future major release. Dynamics 365 App for Outlook, introduced with Dynamics CRM 2016 (version 8.0), is our most up-to-date offering for pairing Dynamics 365 with Microsoft Outlook.


This sample code is for [!INCLUDE[pn_dynamics_crm_online](../../includes/pn-dynamics-crm-online.md)] Customer Engagement. To download the sample, refer [Sample: Create and retrieve Outlook filters](https://msdn.microsoft.com/en-us/library/gg309283.aspx).

## Prerequisites
[!INCLUDE[sdk-prerequisite](../../includes/sdk-prerequisite.md)]
  
## Requirements  
[!INCLUDE[sdk_SeeConnectionHelper](../../includes/sdk-seeconnectionhelper.md)]
  
## Demonstrates  
 This sample shows how to retrieve filters for [!INCLUDE[pn_microsoft_dynamics_crm_for_outlook](../../includes/pn-microsoft-dynamics-crm-for-outlook.md)].  
  
## Example  
 [!code-csharp[Outlook#RetrieveDataFilters1](../../snippets/csharp/CRMV8/outlook/cs/retrievedatafilters1.cs#retrievedatafilters1)]  
  
### See also  
 [Extend Dynamics 365 for Outlook](../extend-customer-engagement-outlook.md)   
 [Sample: Use Outlook Methods](sample-outlook-methods.md)   
 [Offline and Outlook Filters and Templates](offline-outlook-filters-templates.md)   
 [SavedQuery Entity](../entities/savedquery.md)   
<xref:Microsoft.Xrm.Sdk.IOrganizationService>