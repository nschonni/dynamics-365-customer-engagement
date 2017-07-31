---
title: "Microsoft Dynamics 365 Customer Engagement msdyn_agreementbookingservicetask EntityType Reference | MicrosoftDocs"
ms.date: "2017-07-10"
ms.service: "crm-online"
ms.topic: "reference"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: a0967e80-fddb-4f62-8a9c-586b83829e60
author: "jimdaly"
ms.author: "jdaly"
manager: "jdaly"
meta-description: "Reference information about the Web API msdyn_agreementbookingservicetask entitytype."
---
# msdyn_agreementbookingservicetask EntityType
<table>
<tr><td><b>Description:</b></td><td>[!INCLUDE[./descriptions/msdyn_agreementbookingservicetask.md](./descriptions/msdyn_agreementbookingservicetask.md)]</td></tr>
<tr><td><b>Entity Set path:</b></td><td>[!include[current-web-api-base-uri.md](../../includes/current-web-api-base-uri.md)]msdyn_agreementbookingservicetasks </td></tr>
<tr><td><b>Base Type:</b></td><td>[crmbaseentity EntityType](crmbaseentity.md)</td></tr>
<tr><td><b>Display Name:</b></td><td>Agreement Booking Service Task</td></tr>
<tr><td><b>Primary Key:</b></td><td>msdyn_agreementbookingservicetaskid</td></tr>
<tr><td><b>Primary Name Attribute:</b></td><td>msdyn_name</td></tr>
<tr><td><b>Operations supported:</b></td><td>POST,GET,PATCH,DELETE</td></tr>
</table>
  
The msdyn_agreementbookingservicetask entitytype has no functions or actions bound to it.

## Properties
Properties represent fields of data stored in the entity. Some properties are read-only. 


|Name|Type|Details|  
|----|----|-------|  
|createdon|Edm.DateTimeOffset|**Display Name**: Created On<br />**Description**: Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.<br />Read-only<br />|
|importsequencenumber|Edm.Int32|**Display Name**: Import Sequence Number<br />**Description**: Shows the sequence number of the import that created this record.<br />|
|modifiedon|Edm.DateTimeOffset|**Display Name**: Modified On<br />**Description**: Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.<br />Read-only<br />|
|msdyn_agreementbookingservicetaskid|Edm.Guid|**Display Name**: Agreement Booking Service Task<br />**Description**: Shows the entity instances.<br />|
|msdyn_description|Edm.String|**Display Name**: Description<br />|
|msdyn_estimatedduration|Edm.Int32|**Display Name**: Estimated Duration<br />|
|msdyn_internalflags|Edm.String|**Display Name**: Internal Flags<br />|
|msdyn_iscopied|Edm.Boolean|**Display Name**: Is Copied<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Yes</td></tr><tr><td>0</td><td>No</td></tr><tbody></table>|
|msdyn_lineorder|Edm.Int32|**Display Name**: Line Order<br />|
|msdyn_name|Edm.String|**Display Name**: Name<br />**Description**: Enter the name of the custom entity.<br />|
|overriddencreatedon|Edm.DateTimeOffset|**Display Name**: Record Created On<br />**Description**: Shows the date and time that the record was migrated.<br />|
|statecode|Edm.Int32|**Display Name**: Status<br />**Description**: Status of the Agreement Booking Service Task<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>0</td><td>Active</td></tr><tr><td>1</td><td>Inactive</td></tr><tbody></table>|
|statuscode|Edm.Int32|**Display Name**: Status Reason<br />**Description**: Reason for the status of the Agreement Booking Service Task<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Active</td></tr><tr><td>2</td><td>Inactive</td></tr><tbody></table>|
|timezoneruleversionnumber|Edm.Int32|**Display Name**: Time Zone Rule Version Number<br />**Description**: For internal use only.<br />|
|utcconversiontimezonecode|Edm.Int32|**Display Name**: UTC Conversion Time Zone Code<br />**Description**: Shows the time zone code that was in use when the record was created.<br />|
|versionnumber|Edm.Int64|**Display Name**: Version Number<br />**Description**: Version Number<br />Read-only<br />|

## Lookup Properties
Lookup properties are read-only, computed properties which contain entity primary key Edm.Guid data for one or more corresponding single-valued navigation properties. More information: [Lookup properties](https://msdn.microsoft.com/library/mt607990.aspx#bkmk_lookupProperties) and [Retrieve data about lookup properties](https://msdn.microsoft.com/library/gg334767.aspx#bkmk_lookupProperty).


|Name|Single-valued navigation property|Description|  
|----|---------------------------------|-----------|  
|_createdby_value|createdby<br />|Unique identifier of the user who created the record.|
|_createdonbehalfby_value|createdonbehalfby<br />|Shows who created the record on behalf of another user.|
|_modifiedby_value|modifiedby<br />|Unique identifier of the user who modified the record.|
|_modifiedonbehalfby_value|modifiedonbehalfby<br />|Shows who last updated the record on behalf of another user.|
|_msdyn_agreement_value|msdyn_agreement<br />|Unique identifier for Agreement associated with Agreement Booking Service Task.|
|_msdyn_agreementbookingincident_value|msdyn_agreementbookingincident<br />|Shows the agreement booking incident associated with the agreement booking service task.|
|_msdyn_agreementbookingsetup_value|msdyn_agreementbookingsetup<br />|Unique identifier for Agreement Booking Setup associated with Agreement Booking Service Task.|
|_msdyn_customerasset_value|msdyn_customerasset<br />|Unique identifier for Customer Asset associated with Agreement Booking Service Task.|
|_msdyn_tasktype_value|msdyn_tasktype<br />|Unique identifier for Service Task Type associated with Agreement Booking Service Task.|
|_ownerid_value|ownerid<br />|Owner Id|
|_owningbusinessunit_value|owningbusinessunit<br />|Unique identifier for the business unit that owns the record|
|_owningteam_value|owningteam<br />|Unique identifier for the team that owns the record.|
|_owninguser_value|owninguser<br />|Unique identifier for the user that owns the record.|


## Single-valued navigation properties
Single-valued navigation properties represent lookup fields where a single entity can be referenced. Each single-valued navigation property has a corresponding partner collection-valued navigation property on the related entity.


|Name|Type|Partner|  
|----|----|-------|  
|createdby|[systemuser EntityType](systemuser.md)|lk_msdyn_agreementbookingservicetask_createdby|
|createdonbehalfby|[systemuser EntityType](systemuser.md)|lk_msdyn_agreementbookingservicetask_createdonbehalfby|
|modifiedby|[systemuser EntityType](systemuser.md)|lk_msdyn_agreementbookingservicetask_modifiedby|
|modifiedonbehalfby|[systemuser EntityType](systemuser.md)|lk_msdyn_agreementbookingservicetask_modifiedonbehalfby|
|msdyn_agreement|[msdyn_agreement EntityType](msdyn_agreement.md)|msdyn_msdyn_agreement_msdyn_agreementbookingservicetask_Agreement|
|msdyn_agreementbookingincident|[msdyn_agreementbookingincident EntityType](msdyn_agreementbookingincident.md)|msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident|
|msdyn_agreementbookingsetup|[msdyn_agreementbookingsetup EntityType](msdyn_agreementbookingsetup.md)|msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingservicetask_AgreementBookingSetup|
|msdyn_customerasset|[msdyn_customerasset EntityType](msdyn_customerasset.md)|msdyn_msdyn_customerasset_msdyn_agreementbookingservicetask_CustomerAsset|
|msdyn_tasktype|[msdyn_servicetasktype EntityType](msdyn_servicetasktype.md)|msdyn_msdyn_servicetasktype_msdyn_agreementbookingservicetask_TaskType|
|ownerid|[principal EntityType](principal.md)|owner_msdyn_agreementbookingservicetask|
|owningbusinessunit|[businessunit EntityType](businessunit.md)|business_unit_msdyn_agreementbookingservicetask|
|owningteam|[team EntityType](team.md)|team_msdyn_agreementbookingservicetask|
|owninguser|[systemuser EntityType](systemuser.md)|user_msdyn_agreementbookingservicetask|

## Collection-valued navigation properties
Collection-valued navigation properties represent collections of entities which may represent either a one-to-many (1:N) or many-to-many (N:N) relationship between the entities.


|Name|Type|Partner|  
|----|----|-------|  
|msdyn_agreementbookingservicetask_ActivityPointers|[activitypointer EntityType](activitypointer.md)|regardingobjectid_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_adx_alertsubscriptions|[adx_alertsubscription EntityType](adx_alertsubscription.md)|regardingobjectid_msdyn_agreementbookingservicetask_adx_alertsubscription|  
|msdyn_agreementbookingservicetask_adx_inviteredemptions|[adx_inviteredemption EntityType](adx_inviteredemption.md)|regardingobjectid_msdyn_agreementbookingservicetask_adx_inviteredemption|  
|msdyn_agreementbookingservicetask_adx_portalcomments|[adx_portalcomment EntityType](adx_portalcomment.md)|regardingobjectid_msdyn_agreementbookingservicetask_adx_portalcomment|  
|msdyn_agreementbookingservicetask_Annotations|[annotation EntityType](annotation.md)|objectid_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_Appointments|[appointment EntityType](appointment.md)|regardingobjectid_msdyn_agreementbookingservicetask_appointment|  
|msdyn_agreementbookingservicetask_AsyncOperations|[asyncoperation EntityType](asyncoperation.md)|regardingobjectid_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_BulkDeleteFailures|[bulkdeletefailure EntityType](bulkdeletefailure.md)|regardingobjectid_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_connections1|[connection EntityType](connection.md)|record1id_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_connections2|[connection EntityType](connection.md)|record2id_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_DuplicateBaseRecord|[duplicaterecord EntityType](duplicaterecord.md)|baserecordid_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_DuplicateMatchingRecord|[duplicaterecord EntityType](duplicaterecord.md)|duplicaterecordid_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_Emails|[email EntityType](email.md)|regardingobjectid_msdyn_agreementbookingservicetask_email|  
|msdyn_agreementbookingservicetask_Faxes|[fax EntityType](fax.md)|regardingobjectid_msdyn_agreementbookingservicetask_fax|  
|msdyn_agreementbookingservicetask_Letters|[letter EntityType](letter.md)|regardingobjectid_msdyn_agreementbookingservicetask_letter|  
|msdyn_agreementbookingservicetask_msdyn_approvals|[msdyn_approval EntityType](msdyn_approval.md)|regardingobjectid_msdyn_agreementbookingservicetask_msdyn_approval|  
|msdyn_agreementbookingservicetask_msdyn_bookingalerts|[msdyn_bookingalert EntityType](msdyn_bookingalert.md)|regardingobjectid_msdyn_agreementbookingservicetask_msdyn_bookingalert|  
|msdyn_agreementbookingservicetask_msdyn_surveyinvites|[msdyn_surveyinvite EntityType](msdyn_surveyinvite.md)|regardingobjectid_msdyn_agreementbookingservicetask_msdyn_surveyinvite|  
|msdyn_agreementbookingservicetask_PhoneCalls|[phonecall EntityType](phonecall.md)|regardingobjectid_msdyn_agreementbookingservicetask_phonecall|  
|msdyn_agreementbookingservicetask_RecurringAppointmentMasters|[recurringappointmentmaster EntityType](recurringappointmentmaster.md)|regardingobjectid_msdyn_agreementbookingservicetask_recurringappointmentmaster|  
|msdyn_agreementbookingservicetask_ServiceAppointments|[serviceappointment EntityType](serviceappointment.md)|regardingobjectid_msdyn_agreementbookingservicetask_serviceappointment|  
|msdyn_agreementbookingservicetask_SocialActivities|[socialactivity EntityType](socialactivity.md)|regardingobjectid_msdyn_agreementbookingservicetask_socialactivity|  
|msdyn_agreementbookingservicetask_SyncErrors|[syncerror EntityType](syncerror.md)|regardingobjectid_msdyn_agreementbookingservicetask|  
|msdyn_agreementbookingservicetask_Tasks|[task EntityType](task.md)|regardingobjectid_msdyn_agreementbookingservicetask_task|  
|msdyn_msdyn_agreementbookingservicetask_msdyn_workorderservicetask_AgreementBookingServiceTask|[msdyn_workorderservicetask EntityType](msdyn_workorderservicetask.md)|msdyn_agreementbookingservicetask|  

## Operations
The following operations can be used with the msdyn_agreementbookingservicetask entity type.


|Name|Binding|Description|  
|----|-------|-----------|  
|[GrantAccess Action](../actions/grantaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/grantaccess.md](../actions/descriptions/grantaccess.md)]|  
|[IsValidStateTransition Function](../functions/isvalidstatetransition.md)|Not Bound|[!INCLUDE[../functions/descriptions/isvalidstatetransition.md](../functions/descriptions/isvalidstatetransition.md)]|  
|[ModifyAccess Action](../actions/modifyaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/modifyaccess.md](../actions/descriptions/modifyaccess.md)]|  
|[RetrievePrincipalAccess Function](../functions/retrieveprincipalaccess.md)|Not Bound|[!INCLUDE[../functions/descriptions/retrieveprincipalaccess.md](../functions/descriptions/retrieveprincipalaccess.md)]|  
|[RetrieveSharedPrincipalsAndAccess Function](../functions/retrievesharedprincipalsandaccess.md)|Not Bound|[!INCLUDE[../functions/descriptions/retrievesharedprincipalsandaccess.md](../functions/descriptions/retrievesharedprincipalsandaccess.md)]|  
|[RevokeAccess Action](../actions/revokeaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/revokeaccess.md](../actions/descriptions/revokeaccess.md)]|  

## Solutions
The following solutions include the msdyn_agreementbookingservicetask entity type.


|Name|Description |  
|----|------------|  
|[Field Service Solution](../solutions/fieldservice.md)|[!INCLUDE[../solutions/descriptions/fieldservice.md](../solutions/descriptions/fieldservice.md)]|    

[!INCLUDE[./remarks/msdyn_agreementbookingservicetask.md](./remarks/msdyn_agreementbookingservicetask.md)]

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