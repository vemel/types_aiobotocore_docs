<a id="typed-dictionaries-for-aiobotocore-lakeformation-module"></a>

# Typed dictionaries for aiobotocore LakeFormation module

> [Index](..) > [LakeFormation](.) > Typed dictionaries

Auto-generated documentation for
[LakeFormation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
type annotations stubs module
[types-aiobotocore-lakeformation](https://pypi.org/project/types-aiobotocore-lakeformation/).

- [Typed dictionaries for aiobotocore LakeFormation module](#typed-dictionaries-for-aiobotocore-lakeformation-module)
  - [AddLFTagsToResourceRequestRequestTypeDef](#addlftagstoresourcerequestrequesttypedef)
  - [AddLFTagsToResourceResponseTypeDef](#addlftagstoresourceresponsetypedef)
  - [AddObjectInputTypeDef](#addobjectinputtypedef)
  - [BatchGrantPermissionsRequestRequestTypeDef](#batchgrantpermissionsrequestrequesttypedef)
  - [BatchGrantPermissionsResponseTypeDef](#batchgrantpermissionsresponsetypedef)
  - [BatchPermissionsFailureEntryTypeDef](#batchpermissionsfailureentrytypedef)
  - [BatchPermissionsRequestEntryTypeDef](#batchpermissionsrequestentrytypedef)
  - [BatchRevokePermissionsRequestRequestTypeDef](#batchrevokepermissionsrequestrequesttypedef)
  - [BatchRevokePermissionsResponseTypeDef](#batchrevokepermissionsresponsetypedef)
  - [CancelTransactionRequestRequestTypeDef](#canceltransactionrequestrequesttypedef)
  - [ColumnLFTagTypeDef](#columnlftagtypedef)
  - [ColumnWildcardTypeDef](#columnwildcardtypedef)
  - [CommitTransactionRequestRequestTypeDef](#committransactionrequestrequesttypedef)
  - [CommitTransactionResponseTypeDef](#committransactionresponsetypedef)
  - [CreateDataCellsFilterRequestRequestTypeDef](#createdatacellsfilterrequestrequesttypedef)
  - [CreateLFTagRequestRequestTypeDef](#createlftagrequestrequesttypedef)
  - [DataCellsFilterResourceTypeDef](#datacellsfilterresourcetypedef)
  - [DataCellsFilterTypeDef](#datacellsfiltertypedef)
  - [DataLakePrincipalTypeDef](#datalakeprincipaltypedef)
  - [DataLakeSettingsTypeDef](#datalakesettingstypedef)
  - [DataLocationResourceTypeDef](#datalocationresourcetypedef)
  - [DatabaseResourceTypeDef](#databaseresourcetypedef)
  - [DeleteDataCellsFilterRequestRequestTypeDef](#deletedatacellsfilterrequestrequesttypedef)
  - [DeleteLFTagRequestRequestTypeDef](#deletelftagrequestrequesttypedef)
  - [DeleteObjectInputTypeDef](#deleteobjectinputtypedef)
  - [DeleteObjectsOnCancelRequestRequestTypeDef](#deleteobjectsoncancelrequestrequesttypedef)
  - [DeregisterResourceRequestRequestTypeDef](#deregisterresourcerequestrequesttypedef)
  - [DescribeResourceRequestRequestTypeDef](#describeresourcerequestrequesttypedef)
  - [DescribeResourceResponseTypeDef](#describeresourceresponsetypedef)
  - [DescribeTransactionRequestRequestTypeDef](#describetransactionrequestrequesttypedef)
  - [DescribeTransactionResponseTypeDef](#describetransactionresponsetypedef)
  - [DetailsMapTypeDef](#detailsmaptypedef)
  - [ErrorDetailTypeDef](#errordetailtypedef)
  - [ExecutionStatisticsTypeDef](#executionstatisticstypedef)
  - [ExtendTransactionRequestRequestTypeDef](#extendtransactionrequestrequesttypedef)
  - [FilterConditionTypeDef](#filterconditiontypedef)
  - [GetDataLakeSettingsRequestRequestTypeDef](#getdatalakesettingsrequestrequesttypedef)
  - [GetDataLakeSettingsResponseTypeDef](#getdatalakesettingsresponsetypedef)
  - [GetEffectivePermissionsForPathRequestRequestTypeDef](#geteffectivepermissionsforpathrequestrequesttypedef)
  - [GetEffectivePermissionsForPathResponseTypeDef](#geteffectivepermissionsforpathresponsetypedef)
  - [GetLFTagRequestRequestTypeDef](#getlftagrequestrequesttypedef)
  - [GetLFTagResponseTypeDef](#getlftagresponsetypedef)
  - [GetQueryStateRequestRequestTypeDef](#getquerystaterequestrequesttypedef)
  - [GetQueryStateResponseTypeDef](#getquerystateresponsetypedef)
  - [GetQueryStatisticsRequestRequestTypeDef](#getquerystatisticsrequestrequesttypedef)
  - [GetQueryStatisticsResponseTypeDef](#getquerystatisticsresponsetypedef)
  - [GetResourceLFTagsRequestRequestTypeDef](#getresourcelftagsrequestrequesttypedef)
  - [GetResourceLFTagsResponseTypeDef](#getresourcelftagsresponsetypedef)
  - [GetTableObjectsRequestRequestTypeDef](#gettableobjectsrequestrequesttypedef)
  - [GetTableObjectsResponseTypeDef](#gettableobjectsresponsetypedef)
  - [GetWorkUnitResultsRequestRequestTypeDef](#getworkunitresultsrequestrequesttypedef)
  - [GetWorkUnitResultsResponseTypeDef](#getworkunitresultsresponsetypedef)
  - [GetWorkUnitsRequestRequestTypeDef](#getworkunitsrequestrequesttypedef)
  - [GetWorkUnitsResponseTypeDef](#getworkunitsresponsetypedef)
  - [GrantPermissionsRequestRequestTypeDef](#grantpermissionsrequestrequesttypedef)
  - [LFTagErrorTypeDef](#lftagerrortypedef)
  - [LFTagKeyResourceTypeDef](#lftagkeyresourcetypedef)
  - [LFTagPairTypeDef](#lftagpairtypedef)
  - [LFTagPolicyResourceTypeDef](#lftagpolicyresourcetypedef)
  - [LFTagTypeDef](#lftagtypedef)
  - [ListDataCellsFilterRequestRequestTypeDef](#listdatacellsfilterrequestrequesttypedef)
  - [ListDataCellsFilterResponseTypeDef](#listdatacellsfilterresponsetypedef)
  - [ListLFTagsRequestRequestTypeDef](#listlftagsrequestrequesttypedef)
  - [ListLFTagsResponseTypeDef](#listlftagsresponsetypedef)
  - [ListPermissionsRequestRequestTypeDef](#listpermissionsrequestrequesttypedef)
  - [ListPermissionsResponseTypeDef](#listpermissionsresponsetypedef)
  - [ListResourcesRequestRequestTypeDef](#listresourcesrequestrequesttypedef)
  - [ListResourcesResponseTypeDef](#listresourcesresponsetypedef)
  - [ListTableStorageOptimizersRequestRequestTypeDef](#listtablestorageoptimizersrequestrequesttypedef)
  - [ListTableStorageOptimizersResponseTypeDef](#listtablestorageoptimizersresponsetypedef)
  - [ListTransactionsRequestRequestTypeDef](#listtransactionsrequestrequesttypedef)
  - [ListTransactionsResponseTypeDef](#listtransactionsresponsetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PartitionObjectsTypeDef](#partitionobjectstypedef)
  - [PlanningStatisticsTypeDef](#planningstatisticstypedef)
  - [PrincipalPermissionsTypeDef](#principalpermissionstypedef)
  - [PrincipalResourcePermissionsTypeDef](#principalresourcepermissionstypedef)
  - [PutDataLakeSettingsRequestRequestTypeDef](#putdatalakesettingsrequestrequesttypedef)
  - [QueryPlanningContextTypeDef](#queryplanningcontexttypedef)
  - [RegisterResourceRequestRequestTypeDef](#registerresourcerequestrequesttypedef)
  - [RemoveLFTagsFromResourceRequestRequestTypeDef](#removelftagsfromresourcerequestrequesttypedef)
  - [RemoveLFTagsFromResourceResponseTypeDef](#removelftagsfromresourceresponsetypedef)
  - [ResourceInfoTypeDef](#resourceinfotypedef)
  - [ResourceTypeDef](#resourcetypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RevokePermissionsRequestRequestTypeDef](#revokepermissionsrequestrequesttypedef)
  - [RowFilterTypeDef](#rowfiltertypedef)
  - [SearchDatabasesByLFTagsRequestRequestTypeDef](#searchdatabasesbylftagsrequestrequesttypedef)
  - [SearchDatabasesByLFTagsResponseTypeDef](#searchdatabasesbylftagsresponsetypedef)
  - [SearchTablesByLFTagsRequestRequestTypeDef](#searchtablesbylftagsrequestrequesttypedef)
  - [SearchTablesByLFTagsResponseTypeDef](#searchtablesbylftagsresponsetypedef)
  - [StartQueryPlanningRequestRequestTypeDef](#startqueryplanningrequestrequesttypedef)
  - [StartQueryPlanningResponseTypeDef](#startqueryplanningresponsetypedef)
  - [StartTransactionRequestRequestTypeDef](#starttransactionrequestrequesttypedef)
  - [StartTransactionResponseTypeDef](#starttransactionresponsetypedef)
  - [StorageOptimizerTypeDef](#storageoptimizertypedef)
  - [TableObjectTypeDef](#tableobjecttypedef)
  - [TableResourceTypeDef](#tableresourcetypedef)
  - [TableWithColumnsResourceTypeDef](#tablewithcolumnsresourcetypedef)
  - [TaggedDatabaseTypeDef](#taggeddatabasetypedef)
  - [TaggedTableTypeDef](#taggedtabletypedef)
  - [TransactionDescriptionTypeDef](#transactiondescriptiontypedef)
  - [UpdateLFTagRequestRequestTypeDef](#updatelftagrequestrequesttypedef)
  - [UpdateResourceRequestRequestTypeDef](#updateresourcerequestrequesttypedef)
  - [UpdateTableObjectsRequestRequestTypeDef](#updatetableobjectsrequestrequesttypedef)
  - [UpdateTableStorageOptimizerRequestRequestTypeDef](#updatetablestorageoptimizerrequestrequesttypedef)
  - [UpdateTableStorageOptimizerResponseTypeDef](#updatetablestorageoptimizerresponsetypedef)
  - [VirtualObjectTypeDef](#virtualobjecttypedef)
  - [WorkUnitRangeTypeDef](#workunitrangetypedef)
  - [WriteOperationTypeDef](#writeoperationtypedef)

<a id="addlftagstoresourcerequestrequesttypedef"></a>

## AddLFTagsToResourceRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import AddLFTagsToResourceRequestRequestTypeDef
```

Required fields:

- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `LFTags`: `Sequence`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]

Optional fields:

- `CatalogId`: `str`

<a id="addlftagstoresourceresponsetypedef"></a>

## AddLFTagsToResourceResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import AddLFTagsToResourceResponseTypeDef
```

Required fields:

- `Failures`: `List`\[[LFTagErrorTypeDef](./type_defs.md#lftagerrortypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="addobjectinputtypedef"></a>

## AddObjectInputTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import AddObjectInputTypeDef
```

Required fields:

- `Uri`: `str`
- `ETag`: `str`
- `Size`: `int`

Optional fields:

- `PartitionValues`: `Sequence`\[`str`\]

<a id="batchgrantpermissionsrequestrequesttypedef"></a>

## BatchGrantPermissionsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import BatchGrantPermissionsRequestRequestTypeDef
```

Required fields:

- `Entries`:
  `Sequence`\[[BatchPermissionsRequestEntryTypeDef](./type_defs.md#batchpermissionsrequestentrytypedef)\]

Optional fields:

- `CatalogId`: `str`

<a id="batchgrantpermissionsresponsetypedef"></a>

## BatchGrantPermissionsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import BatchGrantPermissionsResponseTypeDef
```

Required fields:

- `Failures`:
  `List`\[[BatchPermissionsFailureEntryTypeDef](./type_defs.md#batchpermissionsfailureentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="batchpermissionsfailureentrytypedef"></a>

## BatchPermissionsFailureEntryTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import BatchPermissionsFailureEntryTypeDef
```

Optional fields:

- `RequestEntry`:
  [BatchPermissionsRequestEntryTypeDef](./type_defs.md#batchpermissionsrequestentrytypedef)
- `Error`: [ErrorDetailTypeDef](./type_defs.md#errordetailtypedef)

<a id="batchpermissionsrequestentrytypedef"></a>

## BatchPermissionsRequestEntryTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import BatchPermissionsRequestEntryTypeDef
```

Required fields:

- `Id`: `str`

Optional fields:

- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `Permissions`: `Sequence`\[[PermissionType](./literals.md#permissiontype)\]
- `PermissionsWithGrantOption`:
  `Sequence`\[[PermissionType](./literals.md#permissiontype)\]

<a id="batchrevokepermissionsrequestrequesttypedef"></a>

## BatchRevokePermissionsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import BatchRevokePermissionsRequestRequestTypeDef
```

Required fields:

- `Entries`:
  `Sequence`\[[BatchPermissionsRequestEntryTypeDef](./type_defs.md#batchpermissionsrequestentrytypedef)\]

Optional fields:

- `CatalogId`: `str`

<a id="batchrevokepermissionsresponsetypedef"></a>

## BatchRevokePermissionsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import BatchRevokePermissionsResponseTypeDef
```

Required fields:

- `Failures`:
  `List`\[[BatchPermissionsFailureEntryTypeDef](./type_defs.md#batchpermissionsfailureentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="canceltransactionrequestrequesttypedef"></a>

## CancelTransactionRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import CancelTransactionRequestRequestTypeDef
```

Required fields:

- `TransactionId`: `str`

<a id="columnlftagtypedef"></a>

## ColumnLFTagTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ColumnLFTagTypeDef
```

Optional fields:

- `Name`: `str`
- `LFTags`: `List`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]

<a id="columnwildcardtypedef"></a>

## ColumnWildcardTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ColumnWildcardTypeDef
```

Optional fields:

- `ExcludedColumnNames`: `Sequence`\[`str`\]

<a id="committransactionrequestrequesttypedef"></a>

## CommitTransactionRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import CommitTransactionRequestRequestTypeDef
```

Required fields:

- `TransactionId`: `str`

<a id="committransactionresponsetypedef"></a>

## CommitTransactionResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import CommitTransactionResponseTypeDef
```

Required fields:

- `TransactionStatus`:
  [TransactionStatusType](./literals.md#transactionstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdatacellsfilterrequestrequesttypedef"></a>

## CreateDataCellsFilterRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import CreateDataCellsFilterRequestRequestTypeDef
```

Required fields:

- `TableData`: [DataCellsFilterTypeDef](./type_defs.md#datacellsfiltertypedef)

<a id="createlftagrequestrequesttypedef"></a>

## CreateLFTagRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import CreateLFTagRequestRequestTypeDef
```

Required fields:

- `TagKey`: `str`
- `TagValues`: `Sequence`\[`str`\]

Optional fields:

- `CatalogId`: `str`

<a id="datacellsfilterresourcetypedef"></a>

## DataCellsFilterResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DataCellsFilterResourceTypeDef
```

Optional fields:

- `TableCatalogId`: `str`
- `DatabaseName`: `str`
- `TableName`: `str`
- `Name`: `str`

<a id="datacellsfiltertypedef"></a>

## DataCellsFilterTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DataCellsFilterTypeDef
```

Required fields:

- `TableCatalogId`: `str`
- `DatabaseName`: `str`
- `TableName`: `str`
- `Name`: `str`

Optional fields:

- `RowFilter`: [RowFilterTypeDef](./type_defs.md#rowfiltertypedef)
- `ColumnNames`: `Sequence`\[`str`\]
- `ColumnWildcard`:
  [ColumnWildcardTypeDef](./type_defs.md#columnwildcardtypedef)

<a id="datalakeprincipaltypedef"></a>

## DataLakePrincipalTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DataLakePrincipalTypeDef
```

Optional fields:

- `DataLakePrincipalIdentifier`: `str`

<a id="datalakesettingstypedef"></a>

## DataLakeSettingsTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DataLakeSettingsTypeDef
```

Optional fields:

- `DataLakeAdmins`:
  `List`\[[DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)\]
- `CreateDatabaseDefaultPermissions`:
  `List`\[[PrincipalPermissionsTypeDef](./type_defs.md#principalpermissionstypedef)\]
- `CreateTableDefaultPermissions`:
  `List`\[[PrincipalPermissionsTypeDef](./type_defs.md#principalpermissionstypedef)\]
- `TrustedResourceOwners`: `List`\[`str`\]

<a id="datalocationresourcetypedef"></a>

## DataLocationResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DataLocationResourceTypeDef
```

Required fields:

- `ResourceArn`: `str`

Optional fields:

- `CatalogId`: `str`

<a id="databaseresourcetypedef"></a>

## DatabaseResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DatabaseResourceTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `CatalogId`: `str`

<a id="deletedatacellsfilterrequestrequesttypedef"></a>

## DeleteDataCellsFilterRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DeleteDataCellsFilterRequestRequestTypeDef
```

Optional fields:

- `TableCatalogId`: `str`
- `DatabaseName`: `str`
- `TableName`: `str`
- `Name`: `str`

<a id="deletelftagrequestrequesttypedef"></a>

## DeleteLFTagRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DeleteLFTagRequestRequestTypeDef
```

Required fields:

- `TagKey`: `str`

Optional fields:

- `CatalogId`: `str`

<a id="deleteobjectinputtypedef"></a>

## DeleteObjectInputTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DeleteObjectInputTypeDef
```

Required fields:

- `Uri`: `str`

Optional fields:

- `ETag`: `str`
- `PartitionValues`: `Sequence`\[`str`\]

<a id="deleteobjectsoncancelrequestrequesttypedef"></a>

## DeleteObjectsOnCancelRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DeleteObjectsOnCancelRequestRequestTypeDef
```

Required fields:

- `DatabaseName`: `str`
- `TableName`: `str`
- `TransactionId`: `str`
- `Objects`:
  `Sequence`\[[VirtualObjectTypeDef](./type_defs.md#virtualobjecttypedef)\]

Optional fields:

- `CatalogId`: `str`

<a id="deregisterresourcerequestrequesttypedef"></a>

## DeregisterResourceRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DeregisterResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="describeresourcerequestrequesttypedef"></a>

## DescribeResourceRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DescribeResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="describeresourceresponsetypedef"></a>

## DescribeResourceResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DescribeResourceResponseTypeDef
```

Required fields:

- `ResourceInfo`: [ResourceInfoTypeDef](./type_defs.md#resourceinfotypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetransactionrequestrequesttypedef"></a>

## DescribeTransactionRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DescribeTransactionRequestRequestTypeDef
```

Required fields:

- `TransactionId`: `str`

<a id="describetransactionresponsetypedef"></a>

## DescribeTransactionResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DescribeTransactionResponseTypeDef
```

Required fields:

- `TransactionDescription`:
  [TransactionDescriptionTypeDef](./type_defs.md#transactiondescriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="detailsmaptypedef"></a>

## DetailsMapTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import DetailsMapTypeDef
```

Optional fields:

- `ResourceShare`: `List`\[`str`\]

<a id="errordetailtypedef"></a>

## ErrorDetailTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ErrorDetailTypeDef
```

Optional fields:

- `ErrorCode`: `str`
- `ErrorMessage`: `str`

<a id="executionstatisticstypedef"></a>

## ExecutionStatisticsTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ExecutionStatisticsTypeDef
```

Optional fields:

- `AverageExecutionTimeMillis`: `int`
- `DataScannedBytes`: `int`
- `WorkUnitsExecutedCount`: `int`

<a id="extendtransactionrequestrequesttypedef"></a>

## ExtendTransactionRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ExtendTransactionRequestRequestTypeDef
```

Optional fields:

- `TransactionId`: `str`

<a id="filterconditiontypedef"></a>

## FilterConditionTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import FilterConditionTypeDef
```

Optional fields:

- `Field`: [FieldNameStringType](./literals.md#fieldnamestringtype)
- `ComparisonOperator`:
  [ComparisonOperatorType](./literals.md#comparisonoperatortype)
- `StringValueList`: `Sequence`\[`str`\]

<a id="getdatalakesettingsrequestrequesttypedef"></a>

## GetDataLakeSettingsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetDataLakeSettingsRequestRequestTypeDef
```

Optional fields:

- `CatalogId`: `str`

<a id="getdatalakesettingsresponsetypedef"></a>

## GetDataLakeSettingsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetDataLakeSettingsResponseTypeDef
```

Required fields:

- `DataLakeSettings`:
  [DataLakeSettingsTypeDef](./type_defs.md#datalakesettingstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="geteffectivepermissionsforpathrequestrequesttypedef"></a>

## GetEffectivePermissionsForPathRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetEffectivePermissionsForPathRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

Optional fields:

- `CatalogId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="geteffectivepermissionsforpathresponsetypedef"></a>

## GetEffectivePermissionsForPathResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetEffectivePermissionsForPathResponseTypeDef
```

Required fields:

- `Permissions`:
  `List`\[[PrincipalResourcePermissionsTypeDef](./type_defs.md#principalresourcepermissionstypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getlftagrequestrequesttypedef"></a>

## GetLFTagRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetLFTagRequestRequestTypeDef
```

Required fields:

- `TagKey`: `str`

Optional fields:

- `CatalogId`: `str`

<a id="getlftagresponsetypedef"></a>

## GetLFTagResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetLFTagResponseTypeDef
```

Required fields:

- `CatalogId`: `str`
- `TagKey`: `str`
- `TagValues`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getquerystaterequestrequesttypedef"></a>

## GetQueryStateRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetQueryStateRequestRequestTypeDef
```

Required fields:

- `QueryId`: `str`

<a id="getquerystateresponsetypedef"></a>

## GetQueryStateResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetQueryStateResponseTypeDef
```

Required fields:

- `Error`: `str`
- `State`: [QueryStateStringType](./literals.md#querystatestringtype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getquerystatisticsrequestrequesttypedef"></a>

## GetQueryStatisticsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetQueryStatisticsRequestRequestTypeDef
```

Required fields:

- `QueryId`: `str`

<a id="getquerystatisticsresponsetypedef"></a>

## GetQueryStatisticsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetQueryStatisticsResponseTypeDef
```

Required fields:

- `ExecutionStatistics`:
  [ExecutionStatisticsTypeDef](./type_defs.md#executionstatisticstypedef)
- `PlanningStatistics`:
  [PlanningStatisticsTypeDef](./type_defs.md#planningstatisticstypedef)
- `QuerySubmissionTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getresourcelftagsrequestrequesttypedef"></a>

## GetResourceLFTagsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetResourceLFTagsRequestRequestTypeDef
```

Required fields:

- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)

Optional fields:

- `CatalogId`: `str`
- `ShowAssignedLFTags`: `bool`

<a id="getresourcelftagsresponsetypedef"></a>

## GetResourceLFTagsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetResourceLFTagsResponseTypeDef
```

Required fields:

- `LFTagOnDatabase`:
  `List`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]
- `LFTagsOnTable`:
  `List`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]
- `LFTagsOnColumns`:
  `List`\[[ColumnLFTagTypeDef](./type_defs.md#columnlftagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="gettableobjectsrequestrequesttypedef"></a>

## GetTableObjectsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetTableObjectsRequestRequestTypeDef
```

Required fields:

- `DatabaseName`: `str`
- `TableName`: `str`

Optional fields:

- `CatalogId`: `str`
- `TransactionId`: `str`
- `QueryAsOfTime`: `Union`\[`datetime`, `str`\]
- `PartitionPredicate`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="gettableobjectsresponsetypedef"></a>

## GetTableObjectsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetTableObjectsResponseTypeDef
```

Required fields:

- `Objects`:
  `List`\[[PartitionObjectsTypeDef](./type_defs.md#partitionobjectstypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getworkunitresultsrequestrequesttypedef"></a>

## GetWorkUnitResultsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetWorkUnitResultsRequestRequestTypeDef
```

Required fields:

- `QueryId`: `str`
- `WorkUnitId`: `int`
- `WorkUnitToken`: `str`

<a id="getworkunitresultsresponsetypedef"></a>

## GetWorkUnitResultsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetWorkUnitResultsResponseTypeDef
```

Required fields:

- `ResultStream`: `StreamingBody`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getworkunitsrequestrequesttypedef"></a>

## GetWorkUnitsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetWorkUnitsRequestRequestTypeDef
```

Required fields:

- `QueryId`: `str`

Optional fields:

- `NextToken`: `str`
- `PageSize`: `int`

<a id="getworkunitsresponsetypedef"></a>

## GetWorkUnitsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GetWorkUnitsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `QueryId`: `str`
- `WorkUnitRanges`:
  `List`\[[WorkUnitRangeTypeDef](./type_defs.md#workunitrangetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="grantpermissionsrequestrequesttypedef"></a>

## GrantPermissionsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import GrantPermissionsRequestRequestTypeDef
```

Required fields:

- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `Permissions`: `Sequence`\[[PermissionType](./literals.md#permissiontype)\]

Optional fields:

- `CatalogId`: `str`
- `PermissionsWithGrantOption`:
  `Sequence`\[[PermissionType](./literals.md#permissiontype)\]

<a id="lftagerrortypedef"></a>

## LFTagErrorTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import LFTagErrorTypeDef
```

Optional fields:

- `LFTag`: [LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)
- `Error`: [ErrorDetailTypeDef](./type_defs.md#errordetailtypedef)

<a id="lftagkeyresourcetypedef"></a>

## LFTagKeyResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import LFTagKeyResourceTypeDef
```

Required fields:

- `TagKey`: `str`
- `TagValues`: `Sequence`\[`str`\]

Optional fields:

- `CatalogId`: `str`

<a id="lftagpairtypedef"></a>

## LFTagPairTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import LFTagPairTypeDef
```

Required fields:

- `TagKey`: `str`
- `TagValues`: `Sequence`\[`str`\]

Optional fields:

- `CatalogId`: `str`

<a id="lftagpolicyresourcetypedef"></a>

## LFTagPolicyResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import LFTagPolicyResourceTypeDef
```

Required fields:

- `ResourceType`: [ResourceTypeType](./literals.md#resourcetypetype)
- `Expression`: `Sequence`\[[LFTagTypeDef](./type_defs.md#lftagtypedef)\]

Optional fields:

- `CatalogId`: `str`

<a id="lftagtypedef"></a>

## LFTagTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import LFTagTypeDef
```

Required fields:

- `TagKey`: `str`
- `TagValues`: `Sequence`\[`str`\]

<a id="listdatacellsfilterrequestrequesttypedef"></a>

## ListDataCellsFilterRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListDataCellsFilterRequestRequestTypeDef
```

Optional fields:

- `Table`: [TableResourceTypeDef](./type_defs.md#tableresourcetypedef)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listdatacellsfilterresponsetypedef"></a>

## ListDataCellsFilterResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListDataCellsFilterResponseTypeDef
```

Required fields:

- `DataCellsFilters`:
  `List`\[[DataCellsFilterTypeDef](./type_defs.md#datacellsfiltertypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listlftagsrequestrequesttypedef"></a>

## ListLFTagsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListLFTagsRequestRequestTypeDef
```

Optional fields:

- `CatalogId`: `str`
- `ResourceShareType`:
  [ResourceShareTypeType](./literals.md#resourcesharetypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listlftagsresponsetypedef"></a>

## ListLFTagsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListLFTagsResponseTypeDef
```

Required fields:

- `LFTags`: `List`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpermissionsrequestrequesttypedef"></a>

## ListPermissionsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListPermissionsRequestRequestTypeDef
```

Optional fields:

- `CatalogId`: `str`
- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
- `ResourceType`:
  [DataLakeResourceTypeType](./literals.md#datalakeresourcetypetype)
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `NextToken`: `str`
- `MaxResults`: `int`
- `IncludeRelated`: `str`

<a id="listpermissionsresponsetypedef"></a>

## ListPermissionsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListPermissionsResponseTypeDef
```

Required fields:

- `PrincipalResourcePermissions`:
  `List`\[[PrincipalResourcePermissionsTypeDef](./type_defs.md#principalresourcepermissionstypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listresourcesrequestrequesttypedef"></a>

## ListResourcesRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListResourcesRequestRequestTypeDef
```

Optional fields:

- `FilterConditionList`:
  `Sequence`\[[FilterConditionTypeDef](./type_defs.md#filterconditiontypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listresourcesresponsetypedef"></a>

## ListResourcesResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListResourcesResponseTypeDef
```

Required fields:

- `ResourceInfoList`:
  `List`\[[ResourceInfoTypeDef](./type_defs.md#resourceinfotypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtablestorageoptimizersrequestrequesttypedef"></a>

## ListTableStorageOptimizersRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListTableStorageOptimizersRequestRequestTypeDef
```

Required fields:

- `DatabaseName`: `str`
- `TableName`: `str`

Optional fields:

- `CatalogId`: `str`
- `StorageOptimizerType`: [OptimizerTypeType](./literals.md#optimizertypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtablestorageoptimizersresponsetypedef"></a>

## ListTableStorageOptimizersResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListTableStorageOptimizersResponseTypeDef
```

Required fields:

- `StorageOptimizerList`:
  `List`\[[StorageOptimizerTypeDef](./type_defs.md#storageoptimizertypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtransactionsrequestrequesttypedef"></a>

## ListTransactionsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListTransactionsRequestRequestTypeDef
```

Optional fields:

- `CatalogId`: `str`
- `StatusFilter`:
  [TransactionStatusFilterType](./literals.md#transactionstatusfiltertype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtransactionsresponsetypedef"></a>

## ListTransactionsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ListTransactionsResponseTypeDef
```

Required fields:

- `Transactions`:
  `List`\[[TransactionDescriptionTypeDef](./type_defs.md#transactiondescriptiontypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="partitionobjectstypedef"></a>

## PartitionObjectsTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import PartitionObjectsTypeDef
```

Optional fields:

- `PartitionValues`: `List`\[`str`\]
- `Objects`: `List`\[[TableObjectTypeDef](./type_defs.md#tableobjecttypedef)\]

<a id="planningstatisticstypedef"></a>

## PlanningStatisticsTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import PlanningStatisticsTypeDef
```

Optional fields:

- `EstimatedDataToScanBytes`: `int`
- `PlanningTimeMillis`: `int`
- `QueueTimeMillis`: `int`
- `WorkUnitsGeneratedCount`: `int`

<a id="principalpermissionstypedef"></a>

## PrincipalPermissionsTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import PrincipalPermissionsTypeDef
```

Optional fields:

- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
- `Permissions`: `List`\[[PermissionType](./literals.md#permissiontype)\]

<a id="principalresourcepermissionstypedef"></a>

## PrincipalResourcePermissionsTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import PrincipalResourcePermissionsTypeDef
```

Optional fields:

- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `Permissions`: `List`\[[PermissionType](./literals.md#permissiontype)\]
- `PermissionsWithGrantOption`:
  `List`\[[PermissionType](./literals.md#permissiontype)\]
- `AdditionalDetails`: [DetailsMapTypeDef](./type_defs.md#detailsmaptypedef)

<a id="putdatalakesettingsrequestrequesttypedef"></a>

## PutDataLakeSettingsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import PutDataLakeSettingsRequestRequestTypeDef
```

Required fields:

- `DataLakeSettings`:
  [DataLakeSettingsTypeDef](./type_defs.md#datalakesettingstypedef)

Optional fields:

- `CatalogId`: `str`

<a id="queryplanningcontexttypedef"></a>

## QueryPlanningContextTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import QueryPlanningContextTypeDef
```

Required fields:

- `DatabaseName`: `str`

Optional fields:

- `CatalogId`: `str`
- `QueryAsOfTime`: `Union`\[`datetime`, `str`\]
- `QueryParameters`: `Mapping`\[`str`, `str`\]
- `TransactionId`: `str`

<a id="registerresourcerequestrequesttypedef"></a>

## RegisterResourceRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import RegisterResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

Optional fields:

- `UseServiceLinkedRole`: `bool`
- `RoleArn`: `str`

<a id="removelftagsfromresourcerequestrequesttypedef"></a>

## RemoveLFTagsFromResourceRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import RemoveLFTagsFromResourceRequestRequestTypeDef
```

Required fields:

- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `LFTags`: `Sequence`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]

Optional fields:

- `CatalogId`: `str`

<a id="removelftagsfromresourceresponsetypedef"></a>

## RemoveLFTagsFromResourceResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import RemoveLFTagsFromResourceResponseTypeDef
```

Required fields:

- `Failures`: `List`\[[LFTagErrorTypeDef](./type_defs.md#lftagerrortypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="resourceinfotypedef"></a>

## ResourceInfoTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ResourceInfoTypeDef
```

Optional fields:

- `ResourceArn`: `str`
- `RoleArn`: `str`
- `LastModified`: `datetime`

<a id="resourcetypedef"></a>

## ResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ResourceTypeDef
```

Optional fields:

- `Catalog`: `Mapping`\[`str`, `Any`\]
- `Database`: [DatabaseResourceTypeDef](./type_defs.md#databaseresourcetypedef)
- `Table`: [TableResourceTypeDef](./type_defs.md#tableresourcetypedef)
- `TableWithColumns`:
  [TableWithColumnsResourceTypeDef](./type_defs.md#tablewithcolumnsresourcetypedef)
- `DataLocation`:
  [DataLocationResourceTypeDef](./type_defs.md#datalocationresourcetypedef)
- `DataCellsFilter`:
  [DataCellsFilterResourceTypeDef](./type_defs.md#datacellsfilterresourcetypedef)
- `LFTag`: [LFTagKeyResourceTypeDef](./type_defs.md#lftagkeyresourcetypedef)
- `LFTagPolicy`:
  [LFTagPolicyResourceTypeDef](./type_defs.md#lftagpolicyresourcetypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="revokepermissionsrequestrequesttypedef"></a>

## RevokePermissionsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import RevokePermissionsRequestRequestTypeDef
```

Required fields:

- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `Permissions`: `Sequence`\[[PermissionType](./literals.md#permissiontype)\]

Optional fields:

- `CatalogId`: `str`
- `PermissionsWithGrantOption`:
  `Sequence`\[[PermissionType](./literals.md#permissiontype)\]

<a id="rowfiltertypedef"></a>

## RowFilterTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import RowFilterTypeDef
```

Optional fields:

- `FilterExpression`: `str`
- `AllRowsWildcard`: `Mapping`\[`str`, `Any`\]

<a id="searchdatabasesbylftagsrequestrequesttypedef"></a>

## SearchDatabasesByLFTagsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import SearchDatabasesByLFTagsRequestRequestTypeDef
```

Required fields:

- `Expression`: `Sequence`\[[LFTagTypeDef](./type_defs.md#lftagtypedef)\]

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CatalogId`: `str`

<a id="searchdatabasesbylftagsresponsetypedef"></a>

## SearchDatabasesByLFTagsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import SearchDatabasesByLFTagsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `DatabaseList`:
  `List`\[[TaggedDatabaseTypeDef](./type_defs.md#taggeddatabasetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="searchtablesbylftagsrequestrequesttypedef"></a>

## SearchTablesByLFTagsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import SearchTablesByLFTagsRequestRequestTypeDef
```

Required fields:

- `Expression`: `Sequence`\[[LFTagTypeDef](./type_defs.md#lftagtypedef)\]

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CatalogId`: `str`

<a id="searchtablesbylftagsresponsetypedef"></a>

## SearchTablesByLFTagsResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import SearchTablesByLFTagsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `TableList`:
  `List`\[[TaggedTableTypeDef](./type_defs.md#taggedtabletypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startqueryplanningrequestrequesttypedef"></a>

## StartQueryPlanningRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import StartQueryPlanningRequestRequestTypeDef
```

Required fields:

- `QueryPlanningContext`:
  [QueryPlanningContextTypeDef](./type_defs.md#queryplanningcontexttypedef)
- `QueryString`: `str`

<a id="startqueryplanningresponsetypedef"></a>

## StartQueryPlanningResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import StartQueryPlanningResponseTypeDef
```

Required fields:

- `QueryId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="starttransactionrequestrequesttypedef"></a>

## StartTransactionRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import StartTransactionRequestRequestTypeDef
```

Optional fields:

- `TransactionType`: [TransactionTypeType](./literals.md#transactiontypetype)

<a id="starttransactionresponsetypedef"></a>

## StartTransactionResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import StartTransactionResponseTypeDef
```

Required fields:

- `TransactionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="storageoptimizertypedef"></a>

## StorageOptimizerTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import StorageOptimizerTypeDef
```

Optional fields:

- `StorageOptimizerType`: [OptimizerTypeType](./literals.md#optimizertypetype)
- `Config`: `Dict`\[`str`, `str`\]
- `ErrorMessage`: `str`
- `Warnings`: `str`
- `LastRunDetails`: `str`

<a id="tableobjecttypedef"></a>

## TableObjectTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import TableObjectTypeDef
```

Optional fields:

- `Uri`: `str`
- `ETag`: `str`
- `Size`: `int`

<a id="tableresourcetypedef"></a>

## TableResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import TableResourceTypeDef
```

Required fields:

- `DatabaseName`: `str`

Optional fields:

- `CatalogId`: `str`
- `Name`: `str`
- `TableWildcard`: `Mapping`\[`str`, `Any`\]

<a id="tablewithcolumnsresourcetypedef"></a>

## TableWithColumnsResourceTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import TableWithColumnsResourceTypeDef
```

Required fields:

- `DatabaseName`: `str`
- `Name`: `str`

Optional fields:

- `CatalogId`: `str`
- `ColumnNames`: `Sequence`\[`str`\]
- `ColumnWildcard`:
  [ColumnWildcardTypeDef](./type_defs.md#columnwildcardtypedef)

<a id="taggeddatabasetypedef"></a>

## TaggedDatabaseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import TaggedDatabaseTypeDef
```

Optional fields:

- `Database`: [DatabaseResourceTypeDef](./type_defs.md#databaseresourcetypedef)
- `LFTags`: `List`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]

<a id="taggedtabletypedef"></a>

## TaggedTableTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import TaggedTableTypeDef
```

Optional fields:

- `Table`: [TableResourceTypeDef](./type_defs.md#tableresourcetypedef)
- `LFTagOnDatabase`:
  `List`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]
- `LFTagsOnTable`:
  `List`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]
- `LFTagsOnColumns`:
  `List`\[[ColumnLFTagTypeDef](./type_defs.md#columnlftagtypedef)\]

<a id="transactiondescriptiontypedef"></a>

## TransactionDescriptionTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import TransactionDescriptionTypeDef
```

Optional fields:

- `TransactionId`: `str`
- `TransactionStatus`:
  [TransactionStatusType](./literals.md#transactionstatustype)
- `TransactionStartTime`: `datetime`
- `TransactionEndTime`: `datetime`

<a id="updatelftagrequestrequesttypedef"></a>

## UpdateLFTagRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import UpdateLFTagRequestRequestTypeDef
```

Required fields:

- `TagKey`: `str`

Optional fields:

- `CatalogId`: `str`
- `TagValuesToDelete`: `Sequence`\[`str`\]
- `TagValuesToAdd`: `Sequence`\[`str`\]

<a id="updateresourcerequestrequesttypedef"></a>

## UpdateResourceRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import UpdateResourceRequestRequestTypeDef
```

Required fields:

- `RoleArn`: `str`
- `ResourceArn`: `str`

<a id="updatetableobjectsrequestrequesttypedef"></a>

## UpdateTableObjectsRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import UpdateTableObjectsRequestRequestTypeDef
```

Required fields:

- `DatabaseName`: `str`
- `TableName`: `str`
- `TransactionId`: `str`
- `WriteOperations`:
  `Sequence`\[[WriteOperationTypeDef](./type_defs.md#writeoperationtypedef)\]

Optional fields:

- `CatalogId`: `str`

<a id="updatetablestorageoptimizerrequestrequesttypedef"></a>

## UpdateTableStorageOptimizerRequestRequestTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import UpdateTableStorageOptimizerRequestRequestTypeDef
```

Required fields:

- `DatabaseName`: `str`
- `TableName`: `str`
- `StorageOptimizerConfig`:
  `Mapping`\[[OptimizerTypeType](./literals.md#optimizertypetype),
  `Mapping`\[`str`, `str`\]\]

Optional fields:

- `CatalogId`: `str`

<a id="updatetablestorageoptimizerresponsetypedef"></a>

## UpdateTableStorageOptimizerResponseTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import UpdateTableStorageOptimizerResponseTypeDef
```

Required fields:

- `Result`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="virtualobjecttypedef"></a>

## VirtualObjectTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import VirtualObjectTypeDef
```

Required fields:

- `Uri`: `str`

Optional fields:

- `ETag`: `str`

<a id="workunitrangetypedef"></a>

## WorkUnitRangeTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import WorkUnitRangeTypeDef
```

Required fields:

- `WorkUnitIdMax`: `int`
- `WorkUnitIdMin`: `int`
- `WorkUnitToken`: `str`

<a id="writeoperationtypedef"></a>

## WriteOperationTypeDef

```python
from types_aiobotocore_lakeformation.type_defs import WriteOperationTypeDef
```

Optional fields:

- `AddObject`: [AddObjectInputTypeDef](./type_defs.md#addobjectinputtypedef)
- `DeleteObject`:
  [DeleteObjectInputTypeDef](./type_defs.md#deleteobjectinputtypedef)
