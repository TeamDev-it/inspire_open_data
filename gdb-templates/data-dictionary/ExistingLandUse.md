
#ExistingLandUse


<br/>
<strong>Geodatabase Documentation</strong>
<hr/>
<strong>Date: </strong>20210526173956.3006201<br/>
<hr/>
<p><strong>Summary Information and Links</strong><br/><br/><a href="#FeatureDatasets">0 Feature Datasets and 2
Feature Classes</a><br/>No Topology Datasets<br/>No Geometric Networks<br/>No Rasters<br/><a href="#ObjectClasses">5 Tables (Object Classes)</a><br/><a href="#RelationshipClasses">1 Relationship
Classes</a><br/><a href="#Domains">1 Domain</a><br/></p>
<hr/>
<p><a name="FeatureDatasets"/><strong>Feature Datasets and Child Classes</strong></p><a name="Raster"/>
<p><strong>Rasters</strong></p><br/>
<hr/><a name="ObjectClasses"/>
<p><strong>Workspace-Level Tables and Feature Classes</strong></p>
    <a href="#FeatureClassExistingLandUseDataSet">ExistingLandUseDataSet - FeatureClass</a><br/><a href="#TableExistingLandUseDataSet_member">ExistingLandUseDataSet_member - Table</a><br/><a href="#FeatureClassExistingLandUseObject">ExistingLandUseObject - FeatureClass</a><br/><a href="#TableExistingLandUseObject_hilucsLandUse">ExistingLandUseObject_hilucsLandUse - Table</a><br/><a href="#TableExistingLandUseObject_hilucsPresence">ExistingLandUseObject_hilucsPresence - Table</a><br/><a href="#TableExistingLandUseObject_specificLandUse">ExistingLandUseObject_specificLandUse - Table</a><br/><a href="#TableExistingLandUseObject_specificPresence">ExistingLandUseObject_specificPresence - Table</a><br/>
<p/><br/>
<hr/><a name="RelationshipClasses"/>
<p><strong>Relationship Classes</strong></p>
    <a href="#RelationshipClassRelELUDS_ELUDS_member">RelELUDS_ELUDS_member</a><br/>
<p/>
<hr/><br/><a name="Domains"/>
<p><strong>Domains</strong></p><a href="#DomainDomainExample">DomainExample</a><br/>
<p/>
    <p><hr/><br/><a name="FeatureClassExistingLandUseDataSet"/>
<p><strong>ExistingLandUseDataSet - FeatureClass</strong></p>
<p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>ShapeType</strong></td>
<td width="*" style="border-color: white">Polyline</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>FeatureType</strong></td>
<td width="*" style="border-color: white">Simple</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>AliasName</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasM</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasZ</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasAttachments</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border:0px">
<td width="8%" style="border:0px"><strong>Field</strong></td>
<td width="8%" style="border:0px"><strong>DataType</strong></td>
<td width="5%" style="border:0px"><strong>Length</strong></td>
<td width="8%" style="border:0px"><strong>AliasName</strong></td>
<td width="8%" style="border:0px"><strong>Description</strong></td>
<td width="8%" style="border:0px"><strong>Domain</strong></td>
<td width="8%" style="border:0px"><strong>DefaultValue</strong></td>
<td width="8%" style="border:0px"><strong>IsNullable</strong></td>
<td width="5%" style="border:0px"><strong>Precision</strong></td>
<td width="5%" style="border:0px"><strong>Scale</strong></td>
</tr>
<tr>
<td width="8%">OBJECTID</td>
<td width="8%">OID</td>
<td width="3%">4</td>
<td width="8%">OBJECTID</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">SHAPE</td>
<td width="8%">Geometry</td>
<td width="3%">0</td>
<td width="8%">SHAPE</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">SHAPE_Length</td>
<td width="8%">Double</td>
<td width="3%">8</td>
<td width="8%">SHAPE_Length</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">SHAPE_Area</td>
<td width="8%">Double</td>
<td width="3%">8</td>
<td width="8%">SHAPE_Area</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">beginLifespanVersion</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">beginLifespanVersion</td>
<td width="8%">Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">endLifespanVersion</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">endLifespanVersion</td>
<td width="8%">Date and time at which this version of the spatial object was superseded or retired in the spatial data set.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">featureId</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">featureId</td>
<td width="8%">Identifier, used in references to this object</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">inspireId_localId</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">inspireId_localId</td>
<td width="8%">A local identifier, assigned by the data provider. The local identifier is unique within the namespace, that is no other spatial object carries the same unique identifier.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">inspireId_namespace</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">inspireId_namespace</td>
<td width="8%">Namespace uniquely identifying the data source of the spatial object.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">inspireId_versionId</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">inspireId_versionId</td>
<td width="8%">The identifier of the particular version of the spatial object, with a maximum length of 25 characters. If the specification of a spatial object type with an external object identifier includes life-cycle information, the version identifier is used to distinguish between the different versions of a spatial object. Within the set of all versions of a spatial object, the version identifier is unique</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">name</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">name</td>
<td width="8%">Human readable name of the data set.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">validFrom</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">validFrom</td>
<td width="8%">Date and time of which this version of the address component was or will be valid in the real world.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">validTo</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">validTo</td>
<td width="8%">Date and time at which the address component ceased or will cease to exist in the real world.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr>
</tbody>
</table>
</p></p><p><hr/><br/><a name="FeatureClassExistingLandUseObject"/>
<p><strong>ExistingLandUseObject - FeatureClass</strong></p>
<p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>ShapeType</strong></td>
<td width="*" style="border-color: white">Polyline</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>FeatureType</strong></td>
<td width="*" style="border-color: white">Simple</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>AliasName</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasM</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasZ</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasAttachments</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border:0px">
<td width="8%" style="border:0px"><strong>Field</strong></td>
<td width="8%" style="border:0px"><strong>DataType</strong></td>
<td width="5%" style="border:0px"><strong>Length</strong></td>
<td width="8%" style="border:0px"><strong>AliasName</strong></td>
<td width="8%" style="border:0px"><strong>Description</strong></td>
<td width="8%" style="border:0px"><strong>Domain</strong></td>
<td width="8%" style="border:0px"><strong>DefaultValue</strong></td>
<td width="8%" style="border:0px"><strong>IsNullable</strong></td>
<td width="5%" style="border:0px"><strong>Precision</strong></td>
<td width="5%" style="border:0px"><strong>Scale</strong></td>
</tr>
<tr>
<td width="8%">OBJECTID</td>
<td width="8%">OID</td>
<td width="3%">4</td>
<td width="8%">OBJECTID</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">SHAPE</td>
<td width="8%">Geometry</td>
<td width="3%">0</td>
<td width="8%">SHAPE</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">inspireId_localId</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">inspireId_localId</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">SHAPE_Length</td>
<td width="8%">Double</td>
<td width="3%">8</td>
<td width="8%">SHAPE_Length</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">SHAPE_Area</td>
<td width="8%">Double</td>
<td width="3%">8</td>
<td width="8%">SHAPE_Area</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">beginLifespanVersion</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">beginLifespanVersion</td>
<td width="8%">Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">dataset</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">dataset</td>
<td width="8%">featureId of the Existing land use data set to which this land use object belongs.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">endLifespanVersion</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">endLifespanVersion</td>
<td width="8%">Date and time at which this version of the spatial object was superseded or retired in the spatial data set.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">featureId</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">featureId</td>
<td width="8%">Identifier, used in references to this object</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">inspireId_namespace</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">inspireId_namespace</td>
<td width="8%">Namespace uniquely identifying the data source of the spatial object.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">inspireId_versionId</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">inspireId_versionId</td>
<td width="8%">The identifier of the particular version of the spatial object, with a maximum length of 25 characters. If the specification of a spatial object type with an external object identifier includes life-cycle information, the version identifier is used to distinguish between the different versions of a spatial object. Within the set of all versions of a spatial object, the version identifier is unique</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">observationDate</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">observationDate</td>
<td width="8%">Defines the observation date of the description. It could be the date of an aerial/satellital acquisition or a field survey. The observation date allows the user to have accurate date of when the description was made in the real word. In a database, not all object informations are necessarily captured at the same time.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">validFrom</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">validFrom</td>
<td width="8%">Date and time of which this version of the address component was or will be valid in the real world.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">validTo</td>
<td width="8%">Date</td>
<td width="3%">8</td>
<td width="8%">validTo</td>
<td width="8%">Date and time at which the address component ceased or will cease to exist in the real world.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr>
</tbody>
</table>
</p></p>
<p><hr/><a name="TableExistingLandUseDataSet_member"/>
<p><strong>ExistingLandUseDataSet_member - Table</strong></p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet_member</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>AliasName</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet_member</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasAttachments</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet_member</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border:0px">
<td width="8%" style="border:0px"><strong>Field</strong></td>
<td width="8%" style="border:0px"><strong>DataType</strong></td>
<td width="5%" style="border:0px"><strong>Length</strong></td>
<td width="8%" style="border:0px"><strong>AliasName</strong></td>
<td width="8%" style="border:0px"><strong>Description</strong></td>
<td width="8%" style="border:0px"><strong>Domain</strong></td>
<td width="8%" style="border:0px"><strong>DefaultValue</strong></td>
<td width="8%" style="border:0px"><strong>IsNullable</strong></td>
<td width="5%" style="border:0px"><strong>Precision</strong></td>
<td width="5%" style="border:0px"><strong>Scale</strong></td>
</tr>
<tr>
<td width="8%">OBJECTID</td>
<td width="8%">OID</td>
<td width="3%">4</td>
<td width="8%">OBJECTID</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">member</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">member</td>
<td width="8%">featureId of Existing land use objects that belong to this existing land use data set.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">RID</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">RID</td>
<td width="8%">Reference to featureId field in parent 'ExistingLandUseDataSet'.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr>
</tbody>
</table>
</p><p><hr/><a name="TableExistingLandUseObject_hilucsLandUse"/>
<p><strong>ExistingLandUseObject_hilucsLandUse - Table</strong></p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_hilucsLandUse</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>AliasName</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_hilucsLandUse</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasAttachments</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_hilucsLandUse</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border:0px">
<td width="8%" style="border:0px"><strong>Field</strong></td>
<td width="8%" style="border:0px"><strong>DataType</strong></td>
<td width="5%" style="border:0px"><strong>Length</strong></td>
<td width="8%" style="border:0px"><strong>AliasName</strong></td>
<td width="8%" style="border:0px"><strong>Description</strong></td>
<td width="8%" style="border:0px"><strong>Domain</strong></td>
<td width="8%" style="border:0px"><strong>DefaultValue</strong></td>
<td width="8%" style="border:0px"><strong>IsNullable</strong></td>
<td width="5%" style="border:0px"><strong>Precision</strong></td>
<td width="5%" style="border:0px"><strong>Scale</strong></td>
</tr>
<tr>
<td width="8%">OBJECTID</td>
<td width="8%">OID</td>
<td width="3%">4</td>
<td width="8%">OBJECTID</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">hilucsLandUse</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">hilucsLandUse</td>
<td width="8%">Land use HILUCS classes that are present in this existing land use sample.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">hilucsLandUse_href</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">hilucsLandUse_href</td>
<td width="8%">URI from the HILUCSValue Codelist.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">RID</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">RID</td>
<td width="8%">Reference to featureId field in parent 'ExistingLandUseObject'.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr>
</tbody>
</table>
</p><p><hr/><a name="TableExistingLandUseObject_hilucsPresence"/>
<p><strong>ExistingLandUseObject_hilucsPresence - Table</strong></p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_hilucsPresence</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>AliasName</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_hilucsPresence</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasAttachments</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_hilucsPresence</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border:0px">
<td width="8%" style="border:0px"><strong>Field</strong></td>
<td width="8%" style="border:0px"><strong>DataType</strong></td>
<td width="5%" style="border:0px"><strong>Length</strong></td>
<td width="8%" style="border:0px"><strong>AliasName</strong></td>
<td width="8%" style="border:0px"><strong>Description</strong></td>
<td width="8%" style="border:0px"><strong>Domain</strong></td>
<td width="8%" style="border:0px"><strong>DefaultValue</strong></td>
<td width="8%" style="border:0px"><strong>IsNullable</strong></td>
<td width="5%" style="border:0px"><strong>Precision</strong></td>
<td width="5%" style="border:0px"><strong>Scale</strong></td>
</tr>
<tr>
<td width="8%">OBJECTID</td>
<td width="8%">OID</td>
<td width="3%">4</td>
<td width="8%">OBJECTID</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">orderedList</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">orderedList</td>
<td width="8%">Land use HILUCS classes that are present in this existing land use object.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">orderedList_href</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">orderedList_href</td>
<td width="8%">URI from the HILUCSValue Codelist.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">percentage_hilucsValue</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">percentage_hilucsValue</td>
<td width="8%">Land use HILUCS classes that are present in this existing land use object.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">percentage_hilucsValue_href</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">percentage_hilucsValue_href</td>
<td width="8%">URI from the HILUCSValue Codelist.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">percentage_percentage</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">percentage_percentage</td>
<td width="8%">Percentage of land use object that is covered by this specific presence.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">RID</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">RID</td>
<td width="8%">Reference to featureId field in parent 'ExistingLandUseObject'.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr>
</tbody>
</table>
</p><p><hr/><a name="TableExistingLandUseObject_specificLandUse"/>
<p><strong>ExistingLandUseObject_specificLandUse - Table</strong></p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_specificLandUse</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>AliasName</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_specificLandUse</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasAttachments</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_specificLandUse</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border:0px">
<td width="8%" style="border:0px"><strong>Field</strong></td>
<td width="8%" style="border:0px"><strong>DataType</strong></td>
<td width="5%" style="border:0px"><strong>Length</strong></td>
<td width="8%" style="border:0px"><strong>AliasName</strong></td>
<td width="8%" style="border:0px"><strong>Description</strong></td>
<td width="8%" style="border:0px"><strong>Domain</strong></td>
<td width="8%" style="border:0px"><strong>DefaultValue</strong></td>
<td width="8%" style="border:0px"><strong>IsNullable</strong></td>
<td width="5%" style="border:0px"><strong>Precision</strong></td>
<td width="5%" style="border:0px"><strong>Scale</strong></td>
</tr>
<tr>
<td width="8%">OBJECTID</td>
<td width="8%">OID</td>
<td width="3%">4</td>
<td width="8%">OBJECTID</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">RID</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">RID</td>
<td width="8%">Reference to featureId field in parent 'ExistingLandUseObject'.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">specificLandUse</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">specificLandUse</td>
<td width="8%">Specific value category for this specific percentage. Value from the LandUseClassificationValue Codelist.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">specificLandUse_href</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">specificLandUse_href</td>
<td width="8%">Specific value category for this specific percentage. Value from the LandUseClassificationValue Codelist.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr>
</tbody>
</table>
</p><p><hr/><a name="TableExistingLandUseObject_specificPresence"/>
<p><strong>ExistingLandUseObject_specificPresence - Table</strong></p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_specificPresence</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>AliasName</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_specificPresence</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>HasAttachments</strong></td>
<td width="*" style="border-color: white">false</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">ExistingLandUseObject_specificPresence</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border:0px">
<td width="8%" style="border:0px"><strong>Field</strong></td>
<td width="8%" style="border:0px"><strong>DataType</strong></td>
<td width="5%" style="border:0px"><strong>Length</strong></td>
<td width="8%" style="border:0px"><strong>AliasName</strong></td>
<td width="8%" style="border:0px"><strong>Description</strong></td>
<td width="8%" style="border:0px"><strong>Domain</strong></td>
<td width="8%" style="border:0px"><strong>DefaultValue</strong></td>
<td width="8%" style="border:0px"><strong>IsNullable</strong></td>
<td width="5%" style="border:0px"><strong>Precision</strong></td>
<td width="5%" style="border:0px"><strong>Scale</strong></td>
</tr>
<tr>
<td width="8%">OBJECTID</td>
<td width="8%">OID</td>
<td width="3%">4</td>
<td width="8%">OBJECTID</td>
<td width="8%"/>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">orderedList</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">orderedList</td>
<td width="8%">LandUseClassificationValue</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">orderedList_href</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">orderedList_href</td>
<td width="8%">LandUseClassificationValue</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">percentage_specificPercentage</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">percentage_specificPercentage</td>
<td width="8%">Percentage of land use object that is covered by a specific presence.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">percentage_specificValue</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">percentage_specificValue</td>
<td width="8%">LandUseClassificationValue</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">percentage_specificValue_href</td>
<td width="8%">String</td>
<td width="3%">254</td>
<td width="8%">percentage_specificValue_href</td>
<td width="8%">LandUseClassificationValue</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr><tr>
<td width="8%">RID</td>
<td width="8%">Integer</td>
<td width="3%">4</td>
<td width="8%">RID</td>
<td width="8%">Reference to featureId field in parent 'ExistingLandUseObject'.</td>
<td width="8%"><a href="#Domain"/></td>
<td width="8%"/>
<td width="8%">true</td>
<td/>
<td/>
</tr>
</tbody>
</table>
</p>
    <p><hr/><a name="RelationshipClassRelELUDS_ELUDS_member"/>
<p><strong>RelELUDS_ELUDS_member - RelationshipClass</strong></p>
<table width="100%">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Name</strong></td>
<td width="*" style="border-color: white">RelELUDS_ELUDS_member</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>Cardinality</strong></td>
<td width="*" style="border-color: white">OneToMany</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>IsAttributed</strong></td>
<td width="*" style="border-color: white">False</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>IsComposite</strong></td>
<td width="*" style="border-color: white">False</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>ForwardPathLabel</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet_member</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>BackwardPathLabel</strong></td>
<td width="*" style="border-color: white">ExistingLandUseDataSet</td>
</tr>
</tbody>
</table>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>Description</strong></td>
<td width="*" style="border-color: white">RelELUDS_ELUDS_member</td>
</tr>
</tbody>
</table>
<table width="50%">
<tbody>
<tr style="border:0px">
<td width="30%" style="border:0px"><strong>Origin Class Name</strong></td>
<td width="30%" style="border:0px"><strong>Origin Primary Key</strong></td>
<td width="30%" style="border:0px"><strong>Origin Foreign Key</strong></td>
</tr><br/>
<tr>
<td width="30%">ExistingLandUseDataSet</td>
<td width="30%">featureId</td>
<td width="30%">RID</td>
</tr>
</tbody>
</table><br/>
<table width="50%">
<tbody>
<tr style="border:0px">
<td width="30%" style="border:0px"><strong>Destination Class Name</strong></td>
<td width="30%" style="border:0px"><strong>Destination Primary Key</strong></td>
<td width="30%" style="border:0px"><strong>Destination Foreign Key</strong></td>
</tr>
<tr>
<td width="30%">ExistingLandUseDataSet_member</td>
<td width="30%"/>
<td width="30%"/>
</tr>
</tbody>
</table></p>
<hr/><a name="DomainDomainExample"/>
<p><strong>DomainExample - Domain</strong></p>
<p>
<table width="100%" style="border-color: white">
<tbody>
<tr>
<td width="12%" style="border-color: white"><strong>DomainName</strong></td>
<td width="*" style="border-color: white">DomainExample</td>
</tr>
<tr>
<td width="12%" style="border-color: white"><strong>FieldType</strong></td>
<td width="*" style="border-color: white">String</td>
</tr>
<tr>
<td width="20%" style="border-color: white"><strong>Domain Type</strong></td>
<td width="*%" style="border-color: white">CodedValue</td>
</tr>
</tbody>
</table><br/>
<table width="100%">
<tbody>
<tr style="border-width:0px"><strong>
<td width="10%" style="border-width:0px"><strong>Code</strong></td>
</strong>
<td width="20%" style="border-width:0px"><strong>Name</strong></td>
</tr>
<tr>
<tr>
<td width="20%">Val1</td>
<td width="20%">Val1</td>
</tr>
<tr>
<td width="20%">Val2</td>
<td width="20%">Val2</td>
</tr>
</tr>
</tbody>
</table>
</p>
<hr/>