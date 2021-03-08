# Geodatabase Encoding Rule for INSPIRE Environmental Managemment Facilities

`Version: 0.2`
`Date: 2021-03-08`

The Simple EnvironmentalManagemmentFacility encoding can be used as an *alternative encoding* for Environmental Managemment Facilities data that fulfills the following requirements:

* It is sufficient to provide the `activity` for the `Function` in function. 
* It is sufficient to provide the `activity` for the `Capacity` in physicalCapacity.  
* There is no information on permittedCapacity for Permissions.


## Normative References

* [INSPIRE UML-to-Geodatabase encoding rule version 0.2](/gdb-encoding/geodatabse encoding.md)
* [Data Specification - INSPIRE Utility and governmental services version 3.1](https://inspire.ec.europa.eu/Themes/136/2892)

## Conformance Class Environmental Managemment Facilities

The Utility and governmental services theme has 3 application schema. This application schema-specific encoding rule defines a conformance class for the schema Environmental Managemment Facilities.

### Model Transformation

This section describes which transformation rules with which parameters are applied to the Environmental Managemment Facilities conceptual model before applying the general rules of this encoding rule:
 

1. Subsitute all attributes that have a property type with a Codelist Sterotype through a inline codelist reference using `MT008()`. (works in GDB)
2. Use Simplified Contact for all occurences `MT012()`. 
3. Use Simplified Related Party for all occurences `MT013()`. 
4. Create seperate Tables for each Geometry Type, add suffix for P for Points, L for Lines and S for Areas `MT014()`.
5. Create seperate Tables for the remaining one-to-many relationships `MT015()`.
6. Apply the General Flattening rule to simplify the remaining properties: `MT001(separator: '_')` (works in GDB as ong as not to long)
7. Apply Attribute shortening rules for EnvironmentalManagemmentFacility:

    |Replace|With|
    |----|----|
    |`facilityDescription_`|`'' `|
    |`relatedParty_`|`'related_' `|
    |`permittedFunction_`|`'permitted_' `|




ToDO: 
5. References to Objects by URL (String)






#### EnvironmentalManagementFacilityL

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
||id|featureId|Long|
|inspireId|Identifier|inspireId_localId|Text|
|||inspireId_namespace|Text|
|||inspireId_versionId|Text|
|||name|Text|
|||geometry||
|validFrom|DateTime|validFrom|Date|
|validTo|DateTime|validTo|Date|
|beginLifespanVersion|DateTime|beginLifespanVersion|Date|
|endLifespanVersion|DateTime|endLifespanVersion|Date|
|serviceHours|PT_FreeText|serviceHours|Text|
|facilityDescription|ActivityComplexDescription|description|Text|
||AddressRepresentation|address|Text|
||AddressRepresentation|contact_address|Text|
||Contact|contact_contactInstructions|Text|
|||contact_electronicMailAddress|Text|
|||contact_hoursOfService|Text|
|||contact_telephoneFacsimile|Text|
|||contact_telephoneVoice|Text|
|||contact_website|Text|
||RelatedParty|related_individualName|Text|
|||related_organisationName|Text|
|||related_positionName|Text|
|||related_address|Text|
|||related_contactInstructions|Text|
|||related_electronicMailAddress|Text|
|||related_hoursOfService|Text|
|||related_telephoneFacsimile|Text|
|||related_telephoneVoice|Text|
|||related_website|Text|
|||related_role|Text|
||ConditionOfFacilityValue|status|Text|
|||status_href|Text|

#### EnvironmentalManagementFacilityP

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
||id|featureId|Long|
|inspireId|Identifier|inspireId_localId|Text|
|||inspireId_namespace|Text|
|||inspireId_versionId|Text|
|||name|Text|
|||geometry||
|validFrom|DateTime|validFrom|Date|
|validTo|DateTime|validTo|Date|
|beginLifespanVersion|DateTime|beginLifespanVersion|Date|
|endLifespanVersion|DateTime|endLifespanVersion|Date|
|serviceHours|PT_FreeText|serviceHours|Text|
|facilityDescription|ActivityComplexDescription|description|Text|
||AddressRepresentation|address|Text|
||AddressRepresentation|contact_address|Text|
||Contact|contact_contactInstructions|Text|
|||contact_electronicMailAddress|Text|
|||contact_hoursOfService|Text|
|||contact_telephoneFacsimile|Text|
|||contact_telephoneVoice|Text|
|||contact_website|Text|
||RelatedParty|related_individualName|Text|
|||related_organisationName|Text|
|||related_positionName|Text|
|||related_address|Text|
|||related_contactInstructions|Text|
|||related_electronicMailAddress|Text|
|||related_hoursOfService|Text|
|||related_telephoneFacsimile|Text|
|||related_telephoneVoice|Text|
|||related_website|Text|
|||related_role|Text|
||ConditionOfFacilityValue|status|Text|
|||status_href|Text|

#### EnvironmentalManagementFacilityS

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
||id|featureId|Long|
|inspireId|Identifier|inspireId_localId|Text|
|||inspireId_namespace|Text|
|||inspireId_versionId|Text|
|||name|Text|
|||geometry||
|validFrom|DateTime|validFrom|Date|
|validTo|DateTime|validTo|Date|
|beginLifespanVersion|DateTime|beginLifespanVersion|Date|
|endLifespanVersion|DateTime|endLifespanVersion|Date|
|serviceHours|PT_FreeText|serviceHours|Text|
|facilityDescription|ActivityComplexDescription|description|Text|
||AddressRepresentation|address|Text|
||AddressRepresentation|contact_address|Text|
||Contact|contact_contactInstructions|Text|
|||contact_electronicMailAddress|Text|
|||contact_hoursOfService|Text|
|||contact_telephoneFacsimile|Text|
|||contact_telephoneVoice|Text|
|||contact_website|Text|
||RelatedParty|related_individualName|Text|
|||related_organisationName|Text|
|||related_positionName|Text|
|||related_address|Text|
|||related_contactInstructions|Text|
|||related_electronicMailAddress|Text|
|||related_hoursOfService|Text|
|||related_telephoneFacsimile|Text|
|||related_telephoneVoice|Text|
|||related_website|Text|
|||related_role|Text|
||ConditionOfFacilityValue|status|Text|
|||status_href|Text|

#### EnvironmentalManagementFacility_capacity

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
|||RID|Long|
|||activity_href|Text|
|||activity|Text|
|||description|Text|

#### EnvironmentalManagementFacility_function

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
|||activity_href|Text|
|||RID|Long|
|||activity|Text|
|||description||

#### EnvironmentalManagementFacility_parentFacility

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
|||RID|Long|
|||parentFacility|Text|

#### EnvironmentalManagementFacility_permission

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
|||RID|Long|
|||permissionId|Long|
|permission|Permission|thematicId_identifier|Text|
|||thematicId_identifierScheme|Text|
||RelatedParty|related_individualName|Text|
|||related_organisationName|Text|
|||related_positionName|Text|
|||related_address|Text|
|||related_contactInstructions|Text|
|||related_electronicMailAddress|Text|
|||related_hoursOfService|Text|
|||related_telephoneFacsimile|Text|
|||related_telephoneVoice|Text|
|||related_website|Text|
|||related_role|Text|
|||relatedParty*|Text|
|||decisionDate|Date|
|||dateFrom|Date|
|||dateTo|Date|
|||description|Text|
||EconomicActivityValue|permitted_activity_href|Text|
|||permitted_activity|Text|
|||RID|Long|

#### EnvironmentalManagementFacility_thematicId

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
|||RID|Long|
|thematicId|ThematicIdentifier|thematicId_identifier|Text|
|||thematicId_identifierScheme|Text|

#### EnvironmentalManagementFacility_type

|Name|Type|Simplified Name|GDB Type|
|------|------|------|------|
|type|EnvironmentalManagementFacilityTypeValue|type_href|Text|
|||type||
|||RID||