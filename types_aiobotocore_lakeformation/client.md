<a id="lakeformationclient-for-aiobotocore-lakeformation-module"></a>

# LakeFormationClient for aiobotocore LakeFormation module

> [Index](..) > [LakeFormation](.) > LakeFormationClient

Auto-generated documentation for
[LakeFormation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
type annotations stubs module
[types-aiobotocore-lakeformation](https://pypi.org/project/types-aiobotocore-lakeformation/).

- [LakeFormationClient for aiobotocore LakeFormation module](#lakeformationclient-for-aiobotocore-lakeformation-module)
  - [LakeFormationClient](#lakeformationclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_lf_tags_to_resource](#add_lf_tags_to_resource)
    - [batch_grant_permissions](#batch_grant_permissions)
    - [batch_revoke_permissions](#batch_revoke_permissions)
    - [can_paginate](#can_paginate)
    - [cancel_transaction](#cancel_transaction)
    - [commit_transaction](#commit_transaction)
    - [create_data_cells_filter](#create_data_cells_filter)
    - [create_lf_tag](#create_lf_tag)
    - [delete_data_cells_filter](#delete_data_cells_filter)
    - [delete_lf_tag](#delete_lf_tag)
    - [delete_objects_on_cancel](#delete_objects_on_cancel)
    - [deregister_resource](#deregister_resource)
    - [describe_resource](#describe_resource)
    - [describe_transaction](#describe_transaction)
    - [extend_transaction](#extend_transaction)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_data_lake_settings](#get_data_lake_settings)
    - [get_effective_permissions_for_path](#get_effective_permissions_for_path)
    - [get_lf_tag](#get_lf_tag)
    - [get_query_state](#get_query_state)
    - [get_query_statistics](#get_query_statistics)
    - [get_resource_lf_tags](#get_resource_lf_tags)
    - [get_table_objects](#get_table_objects)
    - [get_work_unit_results](#get_work_unit_results)
    - [get_work_units](#get_work_units)
    - [grant_permissions](#grant_permissions)
    - [list_data_cells_filter](#list_data_cells_filter)
    - [list_lf_tags](#list_lf_tags)
    - [list_permissions](#list_permissions)
    - [list_resources](#list_resources)
    - [list_table_storage_optimizers](#list_table_storage_optimizers)
    - [list_transactions](#list_transactions)
    - [put_data_lake_settings](#put_data_lake_settings)
    - [register_resource](#register_resource)
    - [remove_lf_tags_from_resource](#remove_lf_tags_from_resource)
    - [revoke_permissions](#revoke_permissions)
    - [search_databases_by_lf_tags](#search_databases_by_lf_tags)
    - [search_tables_by_lf_tags](#search_tables_by_lf_tags)
    - [start_query_planning](#start_query_planning)
    - [start_transaction](#start_transaction)
    - [update_lf_tag](#update_lf_tag)
    - [update_resource](#update_resource)
    - [update_table_objects](#update_table_objects)
    - [update_table_storage_optimizer](#update_table_storage_optimizer)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="lakeformationclient"></a>

## LakeFormationClient

Type annotations for `session.create_client("lakeformation")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_lakeformation.client import LakeFormationClient

session = get_session()
async with session.create_client("lakeformation") as client:
    client: LakeFormationClient
```

Boto3 documentation:
[LakeFormation.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_lakeformation.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.AlreadyExistsException`
- `Exceptions.ClientError`
- `Exceptions.ConcurrentModificationException`
- `Exceptions.EntityNotFoundException`
- `Exceptions.ExpiredException`
- `Exceptions.GlueEncryptionException`
- `Exceptions.InternalServiceException`
- `Exceptions.InvalidInputException`
- `Exceptions.OperationTimeoutException`
- `Exceptions.ResourceNotReadyException`
- `Exceptions.ResourceNumberLimitExceededException`
- `Exceptions.StatisticsNotReadyYetException`
- `Exceptions.ThrottledException`
- `Exceptions.TransactionCanceledException`
- `Exceptions.TransactionCommitInProgressException`
- `Exceptions.TransactionCommittedException`
- `Exceptions.WorkUnitsNotReadyYetException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

LakeFormationClient exceptions.

Type annotations for `session.create_client("lakeformation").exceptions`
method.

Boto3 documentation:
[LakeFormation.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add_lf_tags_to_resource"></a>

### add_lf_tags_to_resource

Attaches one or more LF-tags to an existing resource.

Type annotations for
`session.create_client("lakeformation").add_lf_tags_to_resource` method.

Boto3 documentation:
[LakeFormation.Client.add_lf_tags_to_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.add_lf_tags_to_resource)

Asynchronous method. Use `await add_lf_tags_to_resource(...)` for a synchronous
call.

Arguments mapping described in
[AddLFTagsToResourceRequestRequestTypeDef](./type_defs.md#addlftagstoresourcerequestrequesttypedef).

Keyword-only arguments:

- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef) *(required)*
- `LFTags`: `Sequence`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[AddLFTagsToResourceResponseTypeDef](./type_defs.md#addlftagstoresourceresponsetypedef).

<a id="batch_grant_permissions"></a>

### batch_grant_permissions

Batch operation to grant permissions to the principal.

Type annotations for
`session.create_client("lakeformation").batch_grant_permissions` method.

Boto3 documentation:
[LakeFormation.Client.batch_grant_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.batch_grant_permissions)

Asynchronous method. Use `await batch_grant_permissions(...)` for a synchronous
call.

Arguments mapping described in
[BatchGrantPermissionsRequestRequestTypeDef](./type_defs.md#batchgrantpermissionsrequestrequesttypedef).

Keyword-only arguments:

- `Entries`:
  `Sequence`\[[BatchPermissionsRequestEntryTypeDef](./type_defs.md#batchpermissionsrequestentrytypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchGrantPermissionsResponseTypeDef](./type_defs.md#batchgrantpermissionsresponsetypedef).

<a id="batch_revoke_permissions"></a>

### batch_revoke_permissions

Batch operation to revoke permissions from the principal.

Type annotations for
`session.create_client("lakeformation").batch_revoke_permissions` method.

Boto3 documentation:
[LakeFormation.Client.batch_revoke_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.batch_revoke_permissions)

Asynchronous method. Use `await batch_revoke_permissions(...)` for a
synchronous call.

Arguments mapping described in
[BatchRevokePermissionsRequestRequestTypeDef](./type_defs.md#batchrevokepermissionsrequestrequesttypedef).

Keyword-only arguments:

- `Entries`:
  `Sequence`\[[BatchPermissionsRequestEntryTypeDef](./type_defs.md#batchpermissionsrequestentrytypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchRevokePermissionsResponseTypeDef](./type_defs.md#batchrevokepermissionsresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("lakeformation").can_paginate`
method.

Boto3 documentation:
[LakeFormation.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="cancel_transaction"></a>

### cancel_transaction

Attempts to cancel the specified transaction.

Type annotations for
`session.create_client("lakeformation").cancel_transaction` method.

Boto3 documentation:
[LakeFormation.Client.cancel_transaction](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.cancel_transaction)

Asynchronous method. Use `await cancel_transaction(...)` for a synchronous
call.

Arguments mapping described in
[CancelTransactionRequestRequestTypeDef](./type_defs.md#canceltransactionrequestrequesttypedef).

Keyword-only arguments:

- `TransactionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="commit_transaction"></a>

### commit_transaction

Attempts to commit the specified transaction.

Type annotations for
`session.create_client("lakeformation").commit_transaction` method.

Boto3 documentation:
[LakeFormation.Client.commit_transaction](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.commit_transaction)

Asynchronous method. Use `await commit_transaction(...)` for a synchronous
call.

Arguments mapping described in
[CommitTransactionRequestRequestTypeDef](./type_defs.md#committransactionrequestrequesttypedef).

Keyword-only arguments:

- `TransactionId`: `str` *(required)*

Returns a `Coroutine` for
[CommitTransactionResponseTypeDef](./type_defs.md#committransactionresponsetypedef).

<a id="create_data_cells_filter"></a>

### create_data_cells_filter

Creates a data cell filter to allow one to grant access to certain columns on
certain rows.

Type annotations for
`session.create_client("lakeformation").create_data_cells_filter` method.

Boto3 documentation:
[LakeFormation.Client.create_data_cells_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.create_data_cells_filter)

Asynchronous method. Use `await create_data_cells_filter(...)` for a
synchronous call.

Arguments mapping described in
[CreateDataCellsFilterRequestRequestTypeDef](./type_defs.md#createdatacellsfilterrequestrequesttypedef).

Keyword-only arguments:

- `TableData`: [DataCellsFilterTypeDef](./type_defs.md#datacellsfiltertypedef)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_lf_tag"></a>

### create_lf_tag

Creates an LF-tag with the specified name and values.

Type annotations for `session.create_client("lakeformation").create_lf_tag`
method.

Boto3 documentation:
[LakeFormation.Client.create_lf_tag](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.create_lf_tag)

Asynchronous method. Use `await create_lf_tag(...)` for a synchronous call.

Arguments mapping described in
[CreateLFTagRequestRequestTypeDef](./type_defs.md#createlftagrequestrequesttypedef).

Keyword-only arguments:

- `TagKey`: `str` *(required)*
- `TagValues`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_data_cells_filter"></a>

### delete_data_cells_filter

Deletes a data cell filter.

Type annotations for
`session.create_client("lakeformation").delete_data_cells_filter` method.

Boto3 documentation:
[LakeFormation.Client.delete_data_cells_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.delete_data_cells_filter)

Asynchronous method. Use `await delete_data_cells_filter(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDataCellsFilterRequestRequestTypeDef](./type_defs.md#deletedatacellsfilterrequestrequesttypedef).

Keyword-only arguments:

- `TableCatalogId`: `str`
- `DatabaseName`: `str`
- `TableName`: `str`
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_lf_tag"></a>

### delete_lf_tag

Deletes the specified LF-tag key name.

Type annotations for `session.create_client("lakeformation").delete_lf_tag`
method.

Boto3 documentation:
[LakeFormation.Client.delete_lf_tag](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.delete_lf_tag)

Asynchronous method. Use `await delete_lf_tag(...)` for a synchronous call.

Arguments mapping described in
[DeleteLFTagRequestRequestTypeDef](./type_defs.md#deletelftagrequestrequesttypedef).

Keyword-only arguments:

- `TagKey`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_objects_on_cancel"></a>

### delete_objects_on_cancel

For a specific governed table, provides a list of Amazon S3 objects that will
be written during the current transaction and that can be automatically deleted
if the transaction is canceled.

Type annotations for
`session.create_client("lakeformation").delete_objects_on_cancel` method.

Boto3 documentation:
[LakeFormation.Client.delete_objects_on_cancel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.delete_objects_on_cancel)

Asynchronous method. Use `await delete_objects_on_cancel(...)` for a
synchronous call.

Arguments mapping described in
[DeleteObjectsOnCancelRequestRequestTypeDef](./type_defs.md#deleteobjectsoncancelrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `TransactionId`: `str` *(required)*
- `Objects`:
  `Sequence`\[[VirtualObjectTypeDef](./type_defs.md#virtualobjecttypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deregister_resource"></a>

### deregister_resource

Deregisters the resource as managed by the Data Catalog.

Type annotations for
`session.create_client("lakeformation").deregister_resource` method.

Boto3 documentation:
[LakeFormation.Client.deregister_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.deregister_resource)

Asynchronous method. Use `await deregister_resource(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterResourceRequestRequestTypeDef](./type_defs.md#deregisterresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_resource"></a>

### describe_resource

Retrieves the current data access role for the given resource registered in
Lake Formation.

Type annotations for `session.create_client("lakeformation").describe_resource`
method.

Boto3 documentation:
[LakeFormation.Client.describe_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.describe_resource)

Asynchronous method. Use `await describe_resource(...)` for a synchronous call.

Arguments mapping described in
[DescribeResourceRequestRequestTypeDef](./type_defs.md#describeresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeResourceResponseTypeDef](./type_defs.md#describeresourceresponsetypedef).

<a id="describe_transaction"></a>

### describe_transaction

Returns the details of a single transaction.

Type annotations for
`session.create_client("lakeformation").describe_transaction` method.

Boto3 documentation:
[LakeFormation.Client.describe_transaction](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.describe_transaction)

Asynchronous method. Use `await describe_transaction(...)` for a synchronous
call.

Arguments mapping described in
[DescribeTransactionRequestRequestTypeDef](./type_defs.md#describetransactionrequestrequesttypedef).

Keyword-only arguments:

- `TransactionId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTransactionResponseTypeDef](./type_defs.md#describetransactionresponsetypedef).

<a id="extend_transaction"></a>

### extend_transaction

Indicates to the service that the specified transaction is still active and
should not be treated as idle and aborted.

Type annotations for
`session.create_client("lakeformation").extend_transaction` method.

Boto3 documentation:
[LakeFormation.Client.extend_transaction](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.extend_transaction)

Asynchronous method. Use `await extend_transaction(...)` for a synchronous
call.

Arguments mapping described in
[ExtendTransactionRequestRequestTypeDef](./type_defs.md#extendtransactionrequestrequesttypedef).

Keyword-only arguments:

- `TransactionId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("lakeformation").generate_presigned_url` method.

Boto3 documentation:
[LakeFormation.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_data_lake_settings"></a>

### get_data_lake_settings

Retrieves the list of the data lake administrators of a Lake Formation-managed
data lake.

Type annotations for
`session.create_client("lakeformation").get_data_lake_settings` method.

Boto3 documentation:
[LakeFormation.Client.get_data_lake_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_data_lake_settings)

Asynchronous method. Use `await get_data_lake_settings(...)` for a synchronous
call.

Arguments mapping described in
[GetDataLakeSettingsRequestRequestTypeDef](./type_defs.md#getdatalakesettingsrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`

Returns a `Coroutine` for
[GetDataLakeSettingsResponseTypeDef](./type_defs.md#getdatalakesettingsresponsetypedef).

<a id="get_effective_permissions_for_path"></a>

### get_effective_permissions_for_path

Returns the Lake Formation permissions for a specified table or database
resource located at a path in Amazon S3.

Type annotations for
`session.create_client("lakeformation").get_effective_permissions_for_path`
method.

Boto3 documentation:
[LakeFormation.Client.get_effective_permissions_for_path](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_effective_permissions_for_path)

Asynchronous method. Use `await get_effective_permissions_for_path(...)` for a
synchronous call.

Arguments mapping described in
[GetEffectivePermissionsForPathRequestRequestTypeDef](./type_defs.md#geteffectivepermissionsforpathrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `CatalogId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetEffectivePermissionsForPathResponseTypeDef](./type_defs.md#geteffectivepermissionsforpathresponsetypedef).

<a id="get_lf_tag"></a>

### get_lf_tag

Returns an LF-tag definition.

Type annotations for `session.create_client("lakeformation").get_lf_tag`
method.

Boto3 documentation:
[LakeFormation.Client.get_lf_tag](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_lf_tag)

Asynchronous method. Use `await get_lf_tag(...)` for a synchronous call.

Arguments mapping described in
[GetLFTagRequestRequestTypeDef](./type_defs.md#getlftagrequestrequesttypedef).

Keyword-only arguments:

- `TagKey`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[GetLFTagResponseTypeDef](./type_defs.md#getlftagresponsetypedef).

<a id="get_query_state"></a>

### get_query_state

Returns the state of a query previously submitted.

Type annotations for `session.create_client("lakeformation").get_query_state`
method.

Boto3 documentation:
[LakeFormation.Client.get_query_state](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_query_state)

Asynchronous method. Use `await get_query_state(...)` for a synchronous call.

Arguments mapping described in
[GetQueryStateRequestRequestTypeDef](./type_defs.md#getquerystaterequestrequesttypedef).

Keyword-only arguments:

- `QueryId`: `str` *(required)*

Returns a `Coroutine` for
[GetQueryStateResponseTypeDef](./type_defs.md#getquerystateresponsetypedef).

<a id="get_query_statistics"></a>

### get_query_statistics

Retrieves statistics on the planning and execution of a query.

Type annotations for
`session.create_client("lakeformation").get_query_statistics` method.

Boto3 documentation:
[LakeFormation.Client.get_query_statistics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_query_statistics)

Asynchronous method. Use `await get_query_statistics(...)` for a synchronous
call.

Arguments mapping described in
[GetQueryStatisticsRequestRequestTypeDef](./type_defs.md#getquerystatisticsrequestrequesttypedef).

Keyword-only arguments:

- `QueryId`: `str` *(required)*

Returns a `Coroutine` for
[GetQueryStatisticsResponseTypeDef](./type_defs.md#getquerystatisticsresponsetypedef).

<a id="get_resource_lf_tags"></a>

### get_resource_lf_tags

Returns the LF-tags applied to a resource.

Type annotations for
`session.create_client("lakeformation").get_resource_lf_tags` method.

Boto3 documentation:
[LakeFormation.Client.get_resource_lf_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_resource_lf_tags)

Asynchronous method. Use `await get_resource_lf_tags(...)` for a synchronous
call.

Arguments mapping described in
[GetResourceLFTagsRequestRequestTypeDef](./type_defs.md#getresourcelftagsrequestrequesttypedef).

Keyword-only arguments:

- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef) *(required)*
- `CatalogId`: `str`
- `ShowAssignedLFTags`: `bool`

Returns a `Coroutine` for
[GetResourceLFTagsResponseTypeDef](./type_defs.md#getresourcelftagsresponsetypedef).

<a id="get_table_objects"></a>

### get_table_objects

Returns the set of Amazon S3 objects that make up the specified governed table.

Type annotations for `session.create_client("lakeformation").get_table_objects`
method.

Boto3 documentation:
[LakeFormation.Client.get_table_objects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_table_objects)

Asynchronous method. Use `await get_table_objects(...)` for a synchronous call.

Arguments mapping described in
[GetTableObjectsRequestRequestTypeDef](./type_defs.md#gettableobjectsrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `CatalogId`: `str`
- `TransactionId`: `str`
- `QueryAsOfTime`: `Union`\[`datetime`, `str`\]
- `PartitionPredicate`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetTableObjectsResponseTypeDef](./type_defs.md#gettableobjectsresponsetypedef).

<a id="get_work_unit_results"></a>

### get_work_unit_results

Returns the work units resulting from the query.

Type annotations for
`session.create_client("lakeformation").get_work_unit_results` method.

Boto3 documentation:
[LakeFormation.Client.get_work_unit_results](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_work_unit_results)

Asynchronous method. Use `await get_work_unit_results(...)` for a synchronous
call.

Arguments mapping described in
[GetWorkUnitResultsRequestRequestTypeDef](./type_defs.md#getworkunitresultsrequestrequesttypedef).

Keyword-only arguments:

- `QueryId`: `str` *(required)*
- `WorkUnitId`: `int` *(required)*
- `WorkUnitToken`: `str` *(required)*

Returns a `Coroutine` for
[GetWorkUnitResultsResponseTypeDef](./type_defs.md#getworkunitresultsresponsetypedef).

<a id="get_work_units"></a>

### get_work_units

Retrieves the work units generated by the `StartQueryPlanning` operation.

Type annotations for `session.create_client("lakeformation").get_work_units`
method.

Boto3 documentation:
[LakeFormation.Client.get_work_units](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_work_units)

Asynchronous method. Use `await get_work_units(...)` for a synchronous call.

Arguments mapping described in
[GetWorkUnitsRequestRequestTypeDef](./type_defs.md#getworkunitsrequestrequesttypedef).

Keyword-only arguments:

- `QueryId`: `str` *(required)*
- `NextToken`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[GetWorkUnitsResponseTypeDef](./type_defs.md#getworkunitsresponsetypedef).

<a id="grant_permissions"></a>

### grant_permissions

Grants permissions to the principal to access metadata in the Data Catalog and
data organized in underlying data storage such as Amazon S3.

Type annotations for `session.create_client("lakeformation").grant_permissions`
method.

Boto3 documentation:
[LakeFormation.Client.grant_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.grant_permissions)

Asynchronous method. Use `await grant_permissions(...)` for a synchronous call.

Arguments mapping described in
[GrantPermissionsRequestRequestTypeDef](./type_defs.md#grantpermissionsrequestrequesttypedef).

Keyword-only arguments:

- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
  *(required)*
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef) *(required)*
- `Permissions`: `Sequence`\[[PermissionType](./literals.md#permissiontype)\]
  *(required)*
- `CatalogId`: `str`
- `PermissionsWithGrantOption`:
  `Sequence`\[[PermissionType](./literals.md#permissiontype)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="list_data_cells_filter"></a>

### list_data_cells_filter

Lists all the data cell filters on a table.

Type annotations for
`session.create_client("lakeformation").list_data_cells_filter` method.

Boto3 documentation:
[LakeFormation.Client.list_data_cells_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.list_data_cells_filter)

Asynchronous method. Use `await list_data_cells_filter(...)` for a synchronous
call.

Arguments mapping described in
[ListDataCellsFilterRequestRequestTypeDef](./type_defs.md#listdatacellsfilterrequestrequesttypedef).

Keyword-only arguments:

- `Table`: [TableResourceTypeDef](./type_defs.md#tableresourcetypedef)
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListDataCellsFilterResponseTypeDef](./type_defs.md#listdatacellsfilterresponsetypedef).

<a id="list_lf_tags"></a>

### list_lf_tags

Lists LF-tags that the requester has permission to view.

Type annotations for `session.create_client("lakeformation").list_lf_tags`
method.

Boto3 documentation:
[LakeFormation.Client.list_lf_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.list_lf_tags)

Asynchronous method. Use `await list_lf_tags(...)` for a synchronous call.

Arguments mapping described in
[ListLFTagsRequestRequestTypeDef](./type_defs.md#listlftagsrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`
- `ResourceShareType`:
  [ResourceShareTypeType](./literals.md#resourcesharetypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListLFTagsResponseTypeDef](./type_defs.md#listlftagsresponsetypedef).

<a id="list_permissions"></a>

### list_permissions

Returns a list of the principal permissions on the resource, filtered by the
permissions of the caller.

Type annotations for `session.create_client("lakeformation").list_permissions`
method.

Boto3 documentation:
[LakeFormation.Client.list_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.list_permissions)

Asynchronous method. Use `await list_permissions(...)` for a synchronous call.

Arguments mapping described in
[ListPermissionsRequestRequestTypeDef](./type_defs.md#listpermissionsrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`
- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
- `ResourceType`:
  [DataLakeResourceTypeType](./literals.md#datalakeresourcetypetype)
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef)
- `NextToken`: `str`
- `MaxResults`: `int`
- `IncludeRelated`: `str`

Returns a `Coroutine` for
[ListPermissionsResponseTypeDef](./type_defs.md#listpermissionsresponsetypedef).

<a id="list_resources"></a>

### list_resources

Lists the resources registered to be managed by the Data Catalog.

Type annotations for `session.create_client("lakeformation").list_resources`
method.

Boto3 documentation:
[LakeFormation.Client.list_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.list_resources)

Asynchronous method. Use `await list_resources(...)` for a synchronous call.

Arguments mapping described in
[ListResourcesRequestRequestTypeDef](./type_defs.md#listresourcesrequestrequesttypedef).

Keyword-only arguments:

- `FilterConditionList`:
  `Sequence`\[[FilterConditionTypeDef](./type_defs.md#filterconditiontypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListResourcesResponseTypeDef](./type_defs.md#listresourcesresponsetypedef).

<a id="list_table_storage_optimizers"></a>

### list_table_storage_optimizers

Returns the configuration of all storage optimizers associated with a specified
table.

Type annotations for
`session.create_client("lakeformation").list_table_storage_optimizers` method.

Boto3 documentation:
[LakeFormation.Client.list_table_storage_optimizers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.list_table_storage_optimizers)

Asynchronous method. Use `await list_table_storage_optimizers(...)` for a
synchronous call.

Arguments mapping described in
[ListTableStorageOptimizersRequestRequestTypeDef](./type_defs.md#listtablestorageoptimizersrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `CatalogId`: `str`
- `StorageOptimizerType`: [OptimizerTypeType](./literals.md#optimizertypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTableStorageOptimizersResponseTypeDef](./type_defs.md#listtablestorageoptimizersresponsetypedef).

<a id="list_transactions"></a>

### list_transactions

Returns metadata about transactions and their status.

Type annotations for `session.create_client("lakeformation").list_transactions`
method.

Boto3 documentation:
[LakeFormation.Client.list_transactions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.list_transactions)

Asynchronous method. Use `await list_transactions(...)` for a synchronous call.

Arguments mapping described in
[ListTransactionsRequestRequestTypeDef](./type_defs.md#listtransactionsrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`
- `StatusFilter`:
  [TransactionStatusFilterType](./literals.md#transactionstatusfiltertype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTransactionsResponseTypeDef](./type_defs.md#listtransactionsresponsetypedef).

<a id="put_data_lake_settings"></a>

### put_data_lake_settings

Sets the list of data lake administrators who have admin privileges on all
resources managed by Lake Formation.

Type annotations for
`session.create_client("lakeformation").put_data_lake_settings` method.

Boto3 documentation:
[LakeFormation.Client.put_data_lake_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.put_data_lake_settings)

Asynchronous method. Use `await put_data_lake_settings(...)` for a synchronous
call.

Arguments mapping described in
[PutDataLakeSettingsRequestRequestTypeDef](./type_defs.md#putdatalakesettingsrequestrequesttypedef).

Keyword-only arguments:

- `DataLakeSettings`:
  [DataLakeSettingsTypeDef](./type_defs.md#datalakesettingstypedef)
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="register_resource"></a>

### register_resource

Registers the resource as managed by the Data Catalog.

Type annotations for `session.create_client("lakeformation").register_resource`
method.

Boto3 documentation:
[LakeFormation.Client.register_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.register_resource)

Asynchronous method. Use `await register_resource(...)` for a synchronous call.

Arguments mapping described in
[RegisterResourceRequestRequestTypeDef](./type_defs.md#registerresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `UseServiceLinkedRole`: `bool`
- `RoleArn`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="remove_lf_tags_from_resource"></a>

### remove_lf_tags_from_resource

Removes an LF-tag from the resource.

Type annotations for
`session.create_client("lakeformation").remove_lf_tags_from_resource` method.

Boto3 documentation:
[LakeFormation.Client.remove_lf_tags_from_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.remove_lf_tags_from_resource)

Asynchronous method. Use `await remove_lf_tags_from_resource(...)` for a
synchronous call.

Arguments mapping described in
[RemoveLFTagsFromResourceRequestRequestTypeDef](./type_defs.md#removelftagsfromresourcerequestrequesttypedef).

Keyword-only arguments:

- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef) *(required)*
- `LFTags`: `Sequence`\[[LFTagPairTypeDef](./type_defs.md#lftagpairtypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[RemoveLFTagsFromResourceResponseTypeDef](./type_defs.md#removelftagsfromresourceresponsetypedef).

<a id="revoke_permissions"></a>

### revoke_permissions

Revokes permissions to the principal to access metadata in the Data Catalog and
data organized in underlying data storage such as Amazon S3.

Type annotations for
`session.create_client("lakeformation").revoke_permissions` method.

Boto3 documentation:
[LakeFormation.Client.revoke_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.revoke_permissions)

Asynchronous method. Use `await revoke_permissions(...)` for a synchronous
call.

Arguments mapping described in
[RevokePermissionsRequestRequestTypeDef](./type_defs.md#revokepermissionsrequestrequesttypedef).

Keyword-only arguments:

- `Principal`:
  [DataLakePrincipalTypeDef](./type_defs.md#datalakeprincipaltypedef)
  *(required)*
- `Resource`: [ResourceTypeDef](./type_defs.md#resourcetypedef) *(required)*
- `Permissions`: `Sequence`\[[PermissionType](./literals.md#permissiontype)\]
  *(required)*
- `CatalogId`: `str`
- `PermissionsWithGrantOption`:
  `Sequence`\[[PermissionType](./literals.md#permissiontype)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="search_databases_by_lf_tags"></a>

### search_databases_by_lf_tags

This operation allows a search on `DATABASE` resources by `TagCondition`.

Type annotations for
`session.create_client("lakeformation").search_databases_by_lf_tags` method.

Boto3 documentation:
[LakeFormation.Client.search_databases_by_lf_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.search_databases_by_lf_tags)

Asynchronous method. Use `await search_databases_by_lf_tags(...)` for a
synchronous call.

Arguments mapping described in
[SearchDatabasesByLFTagsRequestRequestTypeDef](./type_defs.md#searchdatabasesbylftagsrequestrequesttypedef).

Keyword-only arguments:

- `Expression`: `Sequence`\[[LFTagTypeDef](./type_defs.md#lftagtypedef)\]
  *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `CatalogId`: `str`

Returns a `Coroutine` for
[SearchDatabasesByLFTagsResponseTypeDef](./type_defs.md#searchdatabasesbylftagsresponsetypedef).

<a id="search_tables_by_lf_tags"></a>

### search_tables_by_lf_tags

This operation allows a search on `TABLE` resources by `LFTag` s.

Type annotations for
`session.create_client("lakeformation").search_tables_by_lf_tags` method.

Boto3 documentation:
[LakeFormation.Client.search_tables_by_lf_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.search_tables_by_lf_tags)

Asynchronous method. Use `await search_tables_by_lf_tags(...)` for a
synchronous call.

Arguments mapping described in
[SearchTablesByLFTagsRequestRequestTypeDef](./type_defs.md#searchtablesbylftagsrequestrequesttypedef).

Keyword-only arguments:

- `Expression`: `Sequence`\[[LFTagTypeDef](./type_defs.md#lftagtypedef)\]
  *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `CatalogId`: `str`

Returns a `Coroutine` for
[SearchTablesByLFTagsResponseTypeDef](./type_defs.md#searchtablesbylftagsresponsetypedef).

<a id="start_query_planning"></a>

### start_query_planning

Submits a request to process a query statement.

Type annotations for
`session.create_client("lakeformation").start_query_planning` method.

Boto3 documentation:
[LakeFormation.Client.start_query_planning](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.start_query_planning)

Asynchronous method. Use `await start_query_planning(...)` for a synchronous
call.

Arguments mapping described in
[StartQueryPlanningRequestRequestTypeDef](./type_defs.md#startqueryplanningrequestrequesttypedef).

Keyword-only arguments:

- `QueryPlanningContext`:
  [QueryPlanningContextTypeDef](./type_defs.md#queryplanningcontexttypedef)
  *(required)*
- `QueryString`: `str` *(required)*

Returns a `Coroutine` for
[StartQueryPlanningResponseTypeDef](./type_defs.md#startqueryplanningresponsetypedef).

<a id="start_transaction"></a>

### start_transaction

Starts a new transaction and returns its transaction ID.

Type annotations for `session.create_client("lakeformation").start_transaction`
method.

Boto3 documentation:
[LakeFormation.Client.start_transaction](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.start_transaction)

Asynchronous method. Use `await start_transaction(...)` for a synchronous call.

Arguments mapping described in
[StartTransactionRequestRequestTypeDef](./type_defs.md#starttransactionrequestrequesttypedef).

Keyword-only arguments:

- `TransactionType`: [TransactionTypeType](./literals.md#transactiontypetype)

Returns a `Coroutine` for
[StartTransactionResponseTypeDef](./type_defs.md#starttransactionresponsetypedef).

<a id="update_lf_tag"></a>

### update_lf_tag

Updates the list of possible values for the specified LF-tag key.

Type annotations for `session.create_client("lakeformation").update_lf_tag`
method.

Boto3 documentation:
[LakeFormation.Client.update_lf_tag](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_lf_tag)

Asynchronous method. Use `await update_lf_tag(...)` for a synchronous call.

Arguments mapping described in
[UpdateLFTagRequestRequestTypeDef](./type_defs.md#updatelftagrequestrequesttypedef).

Keyword-only arguments:

- `TagKey`: `str` *(required)*
- `CatalogId`: `str`
- `TagValuesToDelete`: `Sequence`\[`str`\]
- `TagValuesToAdd`: `Sequence`\[`str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_resource"></a>

### update_resource

Updates the data access role used for vending access to the given (registered)
resource in Lake Formation.

Type annotations for `session.create_client("lakeformation").update_resource`
method.

Boto3 documentation:
[LakeFormation.Client.update_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_resource)

Asynchronous method. Use `await update_resource(...)` for a synchronous call.

Arguments mapping described in
[UpdateResourceRequestRequestTypeDef](./type_defs.md#updateresourcerequestrequesttypedef).

Keyword-only arguments:

- `RoleArn`: `str` *(required)*
- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_table_objects"></a>

### update_table_objects

Updates the manifest of Amazon S3 objects that make up the specified governed
table.

Type annotations for
`session.create_client("lakeformation").update_table_objects` method.

Boto3 documentation:
[LakeFormation.Client.update_table_objects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_table_objects)

Asynchronous method. Use `await update_table_objects(...)` for a synchronous
call.

Arguments mapping described in
[UpdateTableObjectsRequestRequestTypeDef](./type_defs.md#updatetableobjectsrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `TransactionId`: `str` *(required)*
- `WriteOperations`:
  `Sequence`\[[WriteOperationTypeDef](./type_defs.md#writeoperationtypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_table_storage_optimizer"></a>

### update_table_storage_optimizer

Updates the configuration of the storage optimizers for a table.

Type annotations for
`session.create_client("lakeformation").update_table_storage_optimizer` method.

Boto3 documentation:
[LakeFormation.Client.update_table_storage_optimizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_table_storage_optimizer)

Asynchronous method. Use `await update_table_storage_optimizer(...)` for a
synchronous call.

Arguments mapping described in
[UpdateTableStorageOptimizerRequestRequestTypeDef](./type_defs.md#updatetablestorageoptimizerrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `StorageOptimizerConfig`:
  `Mapping`\[[OptimizerTypeType](./literals.md#optimizertypetype),
  `Mapping`\[`str`, `str`\]\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[UpdateTableStorageOptimizerResponseTypeDef](./type_defs.md#updatetablestorageoptimizerresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("lakeformation").__aenter__`
method.

Boto3 documentation:
[LakeFormation.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [LakeFormationClient](#lakeformationclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("lakeformation").__aexit__` method.

Boto3 documentation:
[LakeFormation.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("lakeformation").get_paginator`
method with overloads.

- `client.get_paginator("get_work_units")` ->
  [GetWorkUnitsPaginator](./paginators.md#getworkunitspaginator)
- `client.get_paginator("list_data_cells_filter")` ->
  [ListDataCellsFilterPaginator](./paginators.md#listdatacellsfilterpaginator)
- `client.get_paginator("list_lf_tags")` ->
  [ListLFTagsPaginator](./paginators.md#listlftagspaginator)
- `client.get_paginator("search_databases_by_lf_tags")` ->
  [SearchDatabasesByLFTagsPaginator](./paginators.md#searchdatabasesbylftagspaginator)
- `client.get_paginator("search_tables_by_lf_tags")` ->
  [SearchTablesByLFTagsPaginator](./paginators.md#searchtablesbylftagspaginator)
