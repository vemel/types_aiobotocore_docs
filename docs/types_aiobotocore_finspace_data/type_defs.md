<a id="typed-dictionaries-for-aiobotocore-finspacedata-module"></a>

# Typed dictionaries for aiobotocore FinSpaceData module

> [Index](../README.md) > [FinSpaceData](./README.md) > Typed dictionaries

Auto-generated documentation for
[FinSpaceData](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
type annotations stubs module
[types-aiobotocore-finspace-data](https://pypi.org/project/types-aiobotocore-finspace-data/).

- [Typed dictionaries for aiobotocore FinSpaceData module](#typed-dictionaries-for-aiobotocore-finspacedata-module)
  - [ChangesetErrorInfoTypeDef](#changeseterrorinfotypedef)
  - [ChangesetSummaryTypeDef](#changesetsummarytypedef)
  - [ColumnDefinitionTypeDef](#columndefinitiontypedef)
  - [CreateChangesetRequestRequestTypeDef](#createchangesetrequestrequesttypedef)
  - [CreateChangesetResponseTypeDef](#createchangesetresponsetypedef)
  - [CreateDataViewRequestRequestTypeDef](#createdataviewrequestrequesttypedef)
  - [CreateDataViewResponseTypeDef](#createdataviewresponsetypedef)
  - [CreateDatasetRequestRequestTypeDef](#createdatasetrequestrequesttypedef)
  - [CreateDatasetResponseTypeDef](#createdatasetresponsetypedef)
  - [CreatePermissionGroupRequestRequestTypeDef](#createpermissiongrouprequestrequesttypedef)
  - [CreatePermissionGroupResponseTypeDef](#createpermissiongroupresponsetypedef)
  - [CreateUserRequestRequestTypeDef](#createuserrequestrequesttypedef)
  - [CreateUserResponseTypeDef](#createuserresponsetypedef)
  - [CredentialsTypeDef](#credentialstypedef)
  - [DataViewDestinationTypeParamsTypeDef](#dataviewdestinationtypeparamstypedef)
  - [DataViewErrorInfoTypeDef](#dataviewerrorinfotypedef)
  - [DataViewSummaryTypeDef](#dataviewsummarytypedef)
  - [DatasetOwnerInfoTypeDef](#datasetownerinfotypedef)
  - [DatasetTypeDef](#datasettypedef)
  - [DeleteDatasetRequestRequestTypeDef](#deletedatasetrequestrequesttypedef)
  - [DeleteDatasetResponseTypeDef](#deletedatasetresponsetypedef)
  - [DeletePermissionGroupRequestRequestTypeDef](#deletepermissiongrouprequestrequesttypedef)
  - [DeletePermissionGroupResponseTypeDef](#deletepermissiongroupresponsetypedef)
  - [DisableUserRequestRequestTypeDef](#disableuserrequestrequesttypedef)
  - [DisableUserResponseTypeDef](#disableuserresponsetypedef)
  - [EnableUserRequestRequestTypeDef](#enableuserrequestrequesttypedef)
  - [EnableUserResponseTypeDef](#enableuserresponsetypedef)
  - [GetChangesetRequestRequestTypeDef](#getchangesetrequestrequesttypedef)
  - [GetChangesetResponseTypeDef](#getchangesetresponsetypedef)
  - [GetDataViewRequestRequestTypeDef](#getdataviewrequestrequesttypedef)
  - [GetDataViewResponseTypeDef](#getdataviewresponsetypedef)
  - [GetDatasetRequestRequestTypeDef](#getdatasetrequestrequesttypedef)
  - [GetDatasetResponseTypeDef](#getdatasetresponsetypedef)
  - [GetProgrammaticAccessCredentialsRequestRequestTypeDef](#getprogrammaticaccesscredentialsrequestrequesttypedef)
  - [GetProgrammaticAccessCredentialsResponseTypeDef](#getprogrammaticaccesscredentialsresponsetypedef)
  - [GetUserRequestRequestTypeDef](#getuserrequestrequesttypedef)
  - [GetUserResponseTypeDef](#getuserresponsetypedef)
  - [GetWorkingLocationRequestRequestTypeDef](#getworkinglocationrequestrequesttypedef)
  - [GetWorkingLocationResponseTypeDef](#getworkinglocationresponsetypedef)
  - [ListChangesetsRequestRequestTypeDef](#listchangesetsrequestrequesttypedef)
  - [ListChangesetsResponseTypeDef](#listchangesetsresponsetypedef)
  - [ListDataViewsRequestRequestTypeDef](#listdataviewsrequestrequesttypedef)
  - [ListDataViewsResponseTypeDef](#listdataviewsresponsetypedef)
  - [ListDatasetsRequestRequestTypeDef](#listdatasetsrequestrequesttypedef)
  - [ListDatasetsResponseTypeDef](#listdatasetsresponsetypedef)
  - [ListPermissionGroupsRequestRequestTypeDef](#listpermissiongroupsrequestrequesttypedef)
  - [ListPermissionGroupsResponseTypeDef](#listpermissiongroupsresponsetypedef)
  - [ListUsersRequestRequestTypeDef](#listusersrequestrequesttypedef)
  - [ListUsersResponseTypeDef](#listusersresponsetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PermissionGroupParamsTypeDef](#permissiongroupparamstypedef)
  - [PermissionGroupTypeDef](#permissiongrouptypedef)
  - [ResetUserPasswordRequestRequestTypeDef](#resetuserpasswordrequestrequesttypedef)
  - [ResetUserPasswordResponseTypeDef](#resetuserpasswordresponsetypedef)
  - [ResourcePermissionTypeDef](#resourcepermissiontypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SchemaDefinitionTypeDef](#schemadefinitiontypedef)
  - [SchemaUnionTypeDef](#schemauniontypedef)
  - [UpdateChangesetRequestRequestTypeDef](#updatechangesetrequestrequesttypedef)
  - [UpdateChangesetResponseTypeDef](#updatechangesetresponsetypedef)
  - [UpdateDatasetRequestRequestTypeDef](#updatedatasetrequestrequesttypedef)
  - [UpdateDatasetResponseTypeDef](#updatedatasetresponsetypedef)
  - [UpdatePermissionGroupRequestRequestTypeDef](#updatepermissiongrouprequestrequesttypedef)
  - [UpdatePermissionGroupResponseTypeDef](#updatepermissiongroupresponsetypedef)
  - [UpdateUserRequestRequestTypeDef](#updateuserrequestrequesttypedef)
  - [UpdateUserResponseTypeDef](#updateuserresponsetypedef)
  - [UserTypeDef](#usertypedef)

<a id="changeseterrorinfotypedef"></a>

## ChangesetErrorInfoTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ChangesetErrorInfoTypeDef
```

Optional fields:

- `errorMessage`: `str`
- `errorCategory`: [ErrorCategoryType](./literals.md#errorcategorytype)

<a id="changesetsummarytypedef"></a>

## ChangesetSummaryTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ChangesetSummaryTypeDef
```

Optional fields:

- `changesetId`: `str`
- `changesetArn`: `str`
- `datasetId`: `str`
- `changeType`: [ChangeTypeType](./literals.md#changetypetype)
- `sourceParams`: `Dict`\[`str`, `str`\]
- `formatParams`: `Dict`\[`str`, `str`\]
- `createTime`: `int`
- `status`: [IngestionStatusType](./literals.md#ingestionstatustype)
- `errorInfo`:
  [ChangesetErrorInfoTypeDef](./type_defs.md#changeseterrorinfotypedef)
- `activeUntilTimestamp`: `int`
- `activeFromTimestamp`: `int`
- `updatesChangesetId`: `str`
- `updatedByChangesetId`: `str`

<a id="columndefinitiontypedef"></a>

## ColumnDefinitionTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ColumnDefinitionTypeDef
```

Optional fields:

- `dataType`: [ColumnDataTypeType](./literals.md#columndatatypetype)
- `columnName`: `str`
- `columnDescription`: `str`

<a id="createchangesetrequestrequesttypedef"></a>

## CreateChangesetRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateChangesetRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`
- `changeType`: [ChangeTypeType](./literals.md#changetypetype)
- `sourceParams`: `Mapping`\[`str`, `str`\]
- `formatParams`: `Mapping`\[`str`, `str`\]

Optional fields:

- `clientToken`: `str`

<a id="createchangesetresponsetypedef"></a>

## CreateChangesetResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateChangesetResponseTypeDef
```

Required fields:

- `datasetId`: `str`
- `changesetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdataviewrequestrequesttypedef"></a>

## CreateDataViewRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateDataViewRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`
- `destinationTypeParams`:
  [DataViewDestinationTypeParamsTypeDef](./type_defs.md#dataviewdestinationtypeparamstypedef)

Optional fields:

- `clientToken`: `str`
- `autoUpdate`: `bool`
- `sortColumns`: `Sequence`\[`str`\]
- `partitionColumns`: `Sequence`\[`str`\]
- `asOfTimestamp`: `int`

<a id="createdataviewresponsetypedef"></a>

## CreateDataViewResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateDataViewResponseTypeDef
```

Required fields:

- `datasetId`: `str`
- `dataViewId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdatasetrequestrequesttypedef"></a>

## CreateDatasetRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateDatasetRequestRequestTypeDef
```

Required fields:

- `datasetTitle`: `str`
- `kind`: [DatasetKindType](./literals.md#datasetkindtype)
- `permissionGroupParams`:
  [PermissionGroupParamsTypeDef](./type_defs.md#permissiongroupparamstypedef)

Optional fields:

- `clientToken`: `str`
- `datasetDescription`: `str`
- `ownerInfo`:
  [DatasetOwnerInfoTypeDef](./type_defs.md#datasetownerinfotypedef)
- `alias`: `str`
- `schemaDefinition`: [SchemaUnionTypeDef](./type_defs.md#schemauniontypedef)

<a id="createdatasetresponsetypedef"></a>

## CreateDatasetResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateDatasetResponseTypeDef
```

Required fields:

- `datasetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpermissiongrouprequestrequesttypedef"></a>

## CreatePermissionGroupRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreatePermissionGroupRequestRequestTypeDef
```

Required fields:

- `name`: `str`
- `applicationPermissions`:
  `Sequence`\[[ApplicationPermissionType](./literals.md#applicationpermissiontype)\]

Optional fields:

- `description`: `str`
- `clientToken`: `str`

<a id="createpermissiongroupresponsetypedef"></a>

## CreatePermissionGroupResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreatePermissionGroupResponseTypeDef
```

Required fields:

- `permissionGroupId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createuserrequestrequesttypedef"></a>

## CreateUserRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateUserRequestRequestTypeDef
```

Required fields:

- `emailAddress`: `str`
- `type`: [UserTypeType](./literals.md#usertypetype)

Optional fields:

- `firstName`: `str`
- `lastName`: `str`
- `ApiAccess`: [ApiAccessType](./literals.md#apiaccesstype)
- `apiAccessPrincipalArn`: `str`
- `clientToken`: `str`

<a id="createuserresponsetypedef"></a>

## CreateUserResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CreateUserResponseTypeDef
```

Required fields:

- `userId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="credentialstypedef"></a>

## CredentialsTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import CredentialsTypeDef
```

Optional fields:

- `accessKeyId`: `str`
- `secretAccessKey`: `str`
- `sessionToken`: `str`

<a id="dataviewdestinationtypeparamstypedef"></a>

## DataViewDestinationTypeParamsTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DataViewDestinationTypeParamsTypeDef
```

Required fields:

- `destinationType`: `str`

Optional fields:

- `s3DestinationExportFileFormat`:
  [ExportFileFormatType](./literals.md#exportfileformattype)
- `s3DestinationExportFileFormatOptions`: `Mapping`\[`str`, `str`\]

<a id="dataviewerrorinfotypedef"></a>

## DataViewErrorInfoTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DataViewErrorInfoTypeDef
```

Optional fields:

- `errorMessage`: `str`
- `errorCategory`: [ErrorCategoryType](./literals.md#errorcategorytype)

<a id="dataviewsummarytypedef"></a>

## DataViewSummaryTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DataViewSummaryTypeDef
```

Optional fields:

- `dataViewId`: `str`
- `dataViewArn`: `str`
- `datasetId`: `str`
- `asOfTimestamp`: `int`
- `partitionColumns`: `List`\[`str`\]
- `sortColumns`: `List`\[`str`\]
- `status`: [DataViewStatusType](./literals.md#dataviewstatustype)
- `errorInfo`:
  [DataViewErrorInfoTypeDef](./type_defs.md#dataviewerrorinfotypedef)
- `destinationTypeProperties`:
  [DataViewDestinationTypeParamsTypeDef](./type_defs.md#dataviewdestinationtypeparamstypedef)
- `autoUpdate`: `bool`
- `createTime`: `int`
- `lastModifiedTime`: `int`

<a id="datasetownerinfotypedef"></a>

## DatasetOwnerInfoTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DatasetOwnerInfoTypeDef
```

Optional fields:

- `name`: `str`
- `phoneNumber`: `str`
- `email`: `str`

<a id="datasettypedef"></a>

## DatasetTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DatasetTypeDef
```

Optional fields:

- `datasetId`: `str`
- `datasetArn`: `str`
- `datasetTitle`: `str`
- `kind`: [DatasetKindType](./literals.md#datasetkindtype)
- `datasetDescription`: `str`
- `ownerInfo`:
  [DatasetOwnerInfoTypeDef](./type_defs.md#datasetownerinfotypedef)
- `createTime`: `int`
- `lastModifiedTime`: `int`
- `schemaDefinition`: [SchemaUnionTypeDef](./type_defs.md#schemauniontypedef)
- `alias`: `str`

<a id="deletedatasetrequestrequesttypedef"></a>

## DeleteDatasetRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DeleteDatasetRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`

Optional fields:

- `clientToken`: `str`

<a id="deletedatasetresponsetypedef"></a>

## DeleteDatasetResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DeleteDatasetResponseTypeDef
```

Required fields:

- `datasetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletepermissiongrouprequestrequesttypedef"></a>

## DeletePermissionGroupRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DeletePermissionGroupRequestRequestTypeDef
```

Required fields:

- `permissionGroupId`: `str`

Optional fields:

- `clientToken`: `str`

<a id="deletepermissiongroupresponsetypedef"></a>

## DeletePermissionGroupResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DeletePermissionGroupResponseTypeDef
```

Required fields:

- `permissionGroupId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disableuserrequestrequesttypedef"></a>

## DisableUserRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DisableUserRequestRequestTypeDef
```

Required fields:

- `userId`: `str`

Optional fields:

- `clientToken`: `str`

<a id="disableuserresponsetypedef"></a>

## DisableUserResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import DisableUserResponseTypeDef
```

Required fields:

- `userId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="enableuserrequestrequesttypedef"></a>

## EnableUserRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import EnableUserRequestRequestTypeDef
```

Required fields:

- `userId`: `str`

Optional fields:

- `clientToken`: `str`

<a id="enableuserresponsetypedef"></a>

## EnableUserResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import EnableUserResponseTypeDef
```

Required fields:

- `userId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getchangesetrequestrequesttypedef"></a>

## GetChangesetRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetChangesetRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`
- `changesetId`: `str`

<a id="getchangesetresponsetypedef"></a>

## GetChangesetResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetChangesetResponseTypeDef
```

Required fields:

- `changesetId`: `str`
- `changesetArn`: `str`
- `datasetId`: `str`
- `changeType`: [ChangeTypeType](./literals.md#changetypetype)
- `sourceParams`: `Dict`\[`str`, `str`\]
- `formatParams`: `Dict`\[`str`, `str`\]
- `createTime`: `int`
- `status`: [IngestionStatusType](./literals.md#ingestionstatustype)
- `errorInfo`:
  [ChangesetErrorInfoTypeDef](./type_defs.md#changeseterrorinfotypedef)
- `activeUntilTimestamp`: `int`
- `activeFromTimestamp`: `int`
- `updatesChangesetId`: `str`
- `updatedByChangesetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdataviewrequestrequesttypedef"></a>

## GetDataViewRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetDataViewRequestRequestTypeDef
```

Required fields:

- `dataViewId`: `str`
- `datasetId`: `str`

<a id="getdataviewresponsetypedef"></a>

## GetDataViewResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetDataViewResponseTypeDef
```

Required fields:

- `autoUpdate`: `bool`
- `partitionColumns`: `List`\[`str`\]
- `datasetId`: `str`
- `asOfTimestamp`: `int`
- `errorInfo`:
  [DataViewErrorInfoTypeDef](./type_defs.md#dataviewerrorinfotypedef)
- `lastModifiedTime`: `int`
- `createTime`: `int`
- `sortColumns`: `List`\[`str`\]
- `dataViewId`: `str`
- `dataViewArn`: `str`
- `destinationTypeParams`:
  [DataViewDestinationTypeParamsTypeDef](./type_defs.md#dataviewdestinationtypeparamstypedef)
- `status`: [DataViewStatusType](./literals.md#dataviewstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdatasetrequestrequesttypedef"></a>

## GetDatasetRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetDatasetRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`

<a id="getdatasetresponsetypedef"></a>

## GetDatasetResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetDatasetResponseTypeDef
```

Required fields:

- `datasetId`: `str`
- `datasetArn`: `str`
- `datasetTitle`: `str`
- `kind`: [DatasetKindType](./literals.md#datasetkindtype)
- `datasetDescription`: `str`
- `createTime`: `int`
- `lastModifiedTime`: `int`
- `schemaDefinition`: [SchemaUnionTypeDef](./type_defs.md#schemauniontypedef)
- `alias`: `str`
- `status`: [DatasetStatusType](./literals.md#datasetstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getprogrammaticaccesscredentialsrequestrequesttypedef"></a>

## GetProgrammaticAccessCredentialsRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetProgrammaticAccessCredentialsRequestRequestTypeDef
```

Required fields:

- `environmentId`: `str`

Optional fields:

- `durationInMinutes`: `int`

<a id="getprogrammaticaccesscredentialsresponsetypedef"></a>

## GetProgrammaticAccessCredentialsResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetProgrammaticAccessCredentialsResponseTypeDef
```

Required fields:

- `credentials`: [CredentialsTypeDef](./type_defs.md#credentialstypedef)
- `durationInMinutes`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getuserrequestrequesttypedef"></a>

## GetUserRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetUserRequestRequestTypeDef
```

Required fields:

- `userId`: `str`

<a id="getuserresponsetypedef"></a>

## GetUserResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetUserResponseTypeDef
```

Required fields:

- `userId`: `str`
- `status`: [UserStatusType](./literals.md#userstatustype)
- `firstName`: `str`
- `lastName`: `str`
- `emailAddress`: `str`
- `type`: [UserTypeType](./literals.md#usertypetype)
- `apiAccess`: [ApiAccessType](./literals.md#apiaccesstype)
- `apiAccessPrincipalArn`: `str`
- `createTime`: `int`
- `lastEnabledTime`: `int`
- `lastDisabledTime`: `int`
- `lastModifiedTime`: `int`
- `lastLoginTime`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getworkinglocationrequestrequesttypedef"></a>

## GetWorkingLocationRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetWorkingLocationRequestRequestTypeDef
```

Optional fields:

- `locationType`: [locationTypeType](./literals.md#locationtypetype)

<a id="getworkinglocationresponsetypedef"></a>

## GetWorkingLocationResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import GetWorkingLocationResponseTypeDef
```

Required fields:

- `s3Uri`: `str`
- `s3Path`: `str`
- `s3Bucket`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listchangesetsrequestrequesttypedef"></a>

## ListChangesetsRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListChangesetsRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listchangesetsresponsetypedef"></a>

## ListChangesetsResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListChangesetsResponseTypeDef
```

Required fields:

- `changesets`:
  `List`\[[ChangesetSummaryTypeDef](./type_defs.md#changesetsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdataviewsrequestrequesttypedef"></a>

## ListDataViewsRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListDataViewsRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listdataviewsresponsetypedef"></a>

## ListDataViewsResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListDataViewsResponseTypeDef
```

Required fields:

- `nextToken`: `str`
- `dataViews`:
  `List`\[[DataViewSummaryTypeDef](./type_defs.md#dataviewsummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdatasetsrequestrequesttypedef"></a>

## ListDatasetsRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListDatasetsRequestRequestTypeDef
```

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listdatasetsresponsetypedef"></a>

## ListDatasetsResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListDatasetsResponseTypeDef
```

Required fields:

- `datasets`: `List`\[[DatasetTypeDef](./type_defs.md#datasettypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpermissiongroupsrequestrequesttypedef"></a>

## ListPermissionGroupsRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListPermissionGroupsRequestRequestTypeDef
```

Required fields:

- `maxResults`: `int`

Optional fields:

- `nextToken`: `str`

<a id="listpermissiongroupsresponsetypedef"></a>

## ListPermissionGroupsResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListPermissionGroupsResponseTypeDef
```

Required fields:

- `permissionGroups`:
  `List`\[[PermissionGroupTypeDef](./type_defs.md#permissiongrouptypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listusersrequestrequesttypedef"></a>

## ListUsersRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListUsersRequestRequestTypeDef
```

Required fields:

- `maxResults`: `int`

Optional fields:

- `nextToken`: `str`

<a id="listusersresponsetypedef"></a>

## ListUsersResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ListUsersResponseTypeDef
```

Required fields:

- `users`: `List`\[[UserTypeDef](./type_defs.md#usertypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="permissiongroupparamstypedef"></a>

## PermissionGroupParamsTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import PermissionGroupParamsTypeDef
```

Optional fields:

- `permissionGroupId`: `str`
- `datasetPermissions`:
  `Sequence`\[[ResourcePermissionTypeDef](./type_defs.md#resourcepermissiontypedef)\]

<a id="permissiongrouptypedef"></a>

## PermissionGroupTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import PermissionGroupTypeDef
```

Optional fields:

- `permissionGroupId`: `str`
- `name`: `str`
- `description`: `str`
- `applicationPermissions`:
  `List`\[[ApplicationPermissionType](./literals.md#applicationpermissiontype)\]
- `createTime`: `int`
- `lastModifiedTime`: `int`

<a id="resetuserpasswordrequestrequesttypedef"></a>

## ResetUserPasswordRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ResetUserPasswordRequestRequestTypeDef
```

Required fields:

- `userId`: `str`

Optional fields:

- `clientToken`: `str`

<a id="resetuserpasswordresponsetypedef"></a>

## ResetUserPasswordResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ResetUserPasswordResponseTypeDef
```

Required fields:

- `userId`: `str`
- `temporaryPassword`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="resourcepermissiontypedef"></a>

## ResourcePermissionTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ResourcePermissionTypeDef
```

Optional fields:

- `permission`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="schemadefinitiontypedef"></a>

## SchemaDefinitionTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import SchemaDefinitionTypeDef
```

Optional fields:

- `columns`:
  `Sequence`\[[ColumnDefinitionTypeDef](./type_defs.md#columndefinitiontypedef)\]
- `primaryKeyColumns`: `Sequence`\[`str`\]

<a id="schemauniontypedef"></a>

## SchemaUnionTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import SchemaUnionTypeDef
```

Optional fields:

- `tabularSchemaConfig`:
  [SchemaDefinitionTypeDef](./type_defs.md#schemadefinitiontypedef)

<a id="updatechangesetrequestrequesttypedef"></a>

## UpdateChangesetRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdateChangesetRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`
- `changesetId`: `str`
- `sourceParams`: `Mapping`\[`str`, `str`\]
- `formatParams`: `Mapping`\[`str`, `str`\]

Optional fields:

- `clientToken`: `str`

<a id="updatechangesetresponsetypedef"></a>

## UpdateChangesetResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdateChangesetResponseTypeDef
```

Required fields:

- `changesetId`: `str`
- `datasetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatedatasetrequestrequesttypedef"></a>

## UpdateDatasetRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdateDatasetRequestRequestTypeDef
```

Required fields:

- `datasetId`: `str`
- `datasetTitle`: `str`
- `kind`: [DatasetKindType](./literals.md#datasetkindtype)

Optional fields:

- `clientToken`: `str`
- `datasetDescription`: `str`
- `alias`: `str`
- `schemaDefinition`: [SchemaUnionTypeDef](./type_defs.md#schemauniontypedef)

<a id="updatedatasetresponsetypedef"></a>

## UpdateDatasetResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdateDatasetResponseTypeDef
```

Required fields:

- `datasetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatepermissiongrouprequestrequesttypedef"></a>

## UpdatePermissionGroupRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdatePermissionGroupRequestRequestTypeDef
```

Required fields:

- `permissionGroupId`: `str`

Optional fields:

- `name`: `str`
- `description`: `str`
- `applicationPermissions`:
  `Sequence`\[[ApplicationPermissionType](./literals.md#applicationpermissiontype)\]
- `clientToken`: `str`

<a id="updatepermissiongroupresponsetypedef"></a>

## UpdatePermissionGroupResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdatePermissionGroupResponseTypeDef
```

Required fields:

- `permissionGroupId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateuserrequestrequesttypedef"></a>

## UpdateUserRequestRequestTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdateUserRequestRequestTypeDef
```

Required fields:

- `userId`: `str`

Optional fields:

- `type`: [UserTypeType](./literals.md#usertypetype)
- `firstName`: `str`
- `lastName`: `str`
- `apiAccess`: [ApiAccessType](./literals.md#apiaccesstype)
- `apiAccessPrincipalArn`: `str`
- `clientToken`: `str`

<a id="updateuserresponsetypedef"></a>

## UpdateUserResponseTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UpdateUserResponseTypeDef
```

Required fields:

- `userId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="usertypedef"></a>

## UserTypeDef

```python
from types_aiobotocore_finspace_data.type_defs import UserTypeDef
```

Optional fields:

- `userId`: `str`
- `status`: [UserStatusType](./literals.md#userstatustype)
- `firstName`: `str`
- `lastName`: `str`
- `emailAddress`: `str`
- `type`: [UserTypeType](./literals.md#usertypetype)
- `apiAccess`: [ApiAccessType](./literals.md#apiaccesstype)
- `apiAccessPrincipalArn`: `str`
- `createTime`: `int`
- `lastEnabledTime`: `int`
- `lastDisabledTime`: `int`
- `lastModifiedTime`: `int`
- `lastLoginTime`: `int`
