---
title: "InstantiateFilters Action| MicrosoftDocs"
ms.date: "2017-07-10"
ms.service: "crm-online"
ms.topic: "reference"
applies_to:
  - "Dynamics 365 (online)"
ms.assetid: ae67b785-71a1-4a1c-a9b2-22e6fb9092c6
author: "jimdaly"
ms.author: "jdaly"
manager: "jdaly"
---
# InstantiateFilters Action
[!INCLUDE[./descriptions/instantiatefilters.md](./descriptions/instantiatefilters.md)]

The InstantiateFilters action does not return a value.

## Bound Entities 
Bound actions are invoked by appending the action name to the URI representing an entity or collection.
|EntityType|Binding Type|
|----------|-----------------|
|[systemuser Entitytype](../entitytypes/systemuser.md)|entity|

## Parameters 
Parameters allow for data to be passed to the action.
|Name|Type|Nullable|Unicode|Description|
|----------|-----------------|----------|-----------------|-----------------|  
|TemplateCollection|Collection([savedquery EntityType](../entitytypes/savedquery.md))|false|true|Collection of templates. |



## Entities
Use the InstantiateFilters action with this entity type:
|EntityType |Description| 
|----------|-----------------|    
|[savedquery Entitytype](../entitytypes/savedquery.md)|[!INCLUDE[../entitytypes/descriptions/savedquery.md](../entitytypes/descriptions/savedquery.md)]|

[!INCLUDE[./remarks/instantiatefilters.md](./remarks/instantiatefilters.md)]

### See also  
 [Use the Microsoft Dynamics CRM Web API](https://msdn.microsoft.com/library/mt593051.aspx)<br />
 [Web API EntityType Reference](../entitytypereference.md)<br />
 [Web API Action Reference](../actionreference.md)<br />
 [Web API Function Reference](../functionreference.md)<br />
 [Web API Query Function Reference](../queryfunctionreference.md)<br />
 [Web API EnumType Reference](../enumtypereference.md)<br />
 [Web API ComplexType Reference](../complextypereference.md)<br />
 [Web API Metadata EntityType Reference](../entitytypereference.md)<br />
 [Web API Solutions Reference](../solutionreference.md)<br />