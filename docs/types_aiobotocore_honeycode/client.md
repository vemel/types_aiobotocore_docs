<a id="honeycodeclient-for-aiobotocore-honeycode-module"></a>

# HoneycodeClient for aiobotocore Honeycode module

> [Index](../README.md) > [Honeycode](./README.md) > HoneycodeClient

Auto-generated documentation for
[Honeycode](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
type annotations stubs module
[types-aiobotocore-honeycode](https://pypi.org/project/types-aiobotocore-honeycode/).

- [HoneycodeClient for aiobotocore Honeycode module](#honeycodeclient-for-aiobotocore-honeycode-module)
  - [HoneycodeClient](#honeycodeclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [batch_create_table_rows](#batch_create_table_rows)
    - [batch_delete_table_rows](#batch_delete_table_rows)
    - [batch_update_table_rows](#batch_update_table_rows)
    - [batch_upsert_table_rows](#batch_upsert_table_rows)
    - [can_paginate](#can_paginate)
    - [describe_table_data_import_job](#describe_table_data_import_job)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_screen_data](#get_screen_data)
    - [invoke_screen_automation](#invoke_screen_automation)
    - [list_table_columns](#list_table_columns)
    - [list_table_rows](#list_table_rows)
    - [list_tables](#list_tables)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [query_table_rows](#query_table_rows)
    - [start_table_data_import_job](#start_table_data_import_job)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="honeycodeclient"></a>

## HoneycodeClient

Type annotations for `session.create_client("honeycode")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_honeycode.client import HoneycodeClient

session = get_session()
async with session.create_client("honeycode") as client:
    client: HoneycodeClient
```

Boto3 documentation:
[Honeycode.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_honeycode.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.AutomationExecutionException`
- `Exceptions.AutomationExecutionTimeoutException`
- `Exceptions.ClientError`
- `Exceptions.InternalServerException`
- `Exceptions.RequestTimeoutException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

HoneycodeClient exceptions.

Type annotations for `session.create_client("honeycode").exceptions` method.

Boto3 documentation:
[Honeycode.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="batch\_create\_table\_rows"></a>

### batch_create_table_rows

The BatchCreateTableRows API allows you to create one or more rows at the end
of a table in a workbook.

Type annotations for
`session.create_client("honeycode").batch_create_table_rows` method.

Boto3 documentation:
[Honeycode.Client.batch_create_table_rows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.batch_create_table_rows)

Asynchronous method. Use `await batch_create_table_rows(...)` for a synchronous
call.

Arguments mapping described in
[BatchCreateTableRowsRequestRequestTypeDef](./type_defs.md#batchcreatetablerowsrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `rowsToCreate`:
  `Sequence`\[[CreateRowDataTypeDef](./type_defs.md#createrowdatatypedef)\]
  *(required)*
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[BatchCreateTableRowsResultTypeDef](./type_defs.md#batchcreatetablerowsresulttypedef).

<a id="batch\_delete\_table\_rows"></a>

### batch_delete_table_rows

The BatchDeleteTableRows API allows you to delete one or more rows from a table
in a workbook.

Type annotations for
`session.create_client("honeycode").batch_delete_table_rows` method.

Boto3 documentation:
[Honeycode.Client.batch_delete_table_rows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.batch_delete_table_rows)

Asynchronous method. Use `await batch_delete_table_rows(...)` for a synchronous
call.

Arguments mapping described in
[BatchDeleteTableRowsRequestRequestTypeDef](./type_defs.md#batchdeletetablerowsrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `rowIds`: `Sequence`\[`str`\] *(required)*
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[BatchDeleteTableRowsResultTypeDef](./type_defs.md#batchdeletetablerowsresulttypedef).

<a id="batch\_update\_table\_rows"></a>

### batch_update_table_rows

The BatchUpdateTableRows API allows you to update one or more rows in a table
in a workbook.

Type annotations for
`session.create_client("honeycode").batch_update_table_rows` method.

Boto3 documentation:
[Honeycode.Client.batch_update_table_rows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.batch_update_table_rows)

Asynchronous method. Use `await batch_update_table_rows(...)` for a synchronous
call.

Arguments mapping described in
[BatchUpdateTableRowsRequestRequestTypeDef](./type_defs.md#batchupdatetablerowsrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `rowsToUpdate`:
  `Sequence`\[[UpdateRowDataTypeDef](./type_defs.md#updaterowdatatypedef)\]
  *(required)*
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[BatchUpdateTableRowsResultTypeDef](./type_defs.md#batchupdatetablerowsresulttypedef).

<a id="batch\_upsert\_table\_rows"></a>

### batch_upsert_table_rows

The BatchUpsertTableRows API allows you to upsert one or more rows in a table.

Type annotations for
`session.create_client("honeycode").batch_upsert_table_rows` method.

Boto3 documentation:
[Honeycode.Client.batch_upsert_table_rows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.batch_upsert_table_rows)

Asynchronous method. Use `await batch_upsert_table_rows(...)` for a synchronous
call.

Arguments mapping described in
[BatchUpsertTableRowsRequestRequestTypeDef](./type_defs.md#batchupserttablerowsrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `rowsToUpsert`:
  `Sequence`\[[UpsertRowDataTypeDef](./type_defs.md#upsertrowdatatypedef)\]
  *(required)*
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[BatchUpsertTableRowsResultTypeDef](./type_defs.md#batchupserttablerowsresulttypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("honeycode").can_paginate` method.

Boto3 documentation:
[Honeycode.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="describe\_table\_data\_import\_job"></a>

### describe_table_data_import_job

The DescribeTableDataImportJob API allows you to retrieve the status and
details of a table data import job.

Type annotations for
`session.create_client("honeycode").describe_table_data_import_job` method.

Boto3 documentation:
[Honeycode.Client.describe_table_data_import_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.describe_table_data_import_job)

Asynchronous method. Use `await describe_table_data_import_job(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTableDataImportJobRequestRequestTypeDef](./type_defs.md#describetabledataimportjobrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `jobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTableDataImportJobResultTypeDef](./type_defs.md#describetabledataimportjobresulttypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("honeycode").generate_presigned_url` method.

Boto3 documentation:
[Honeycode.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_screen\_data"></a>

### get_screen_data

The GetScreenData API allows retrieval of data from a screen in a Honeycode
app.

Type annotations for `session.create_client("honeycode").get_screen_data`
method.

Boto3 documentation:
[Honeycode.Client.get_screen_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.get_screen_data)

Asynchronous method. Use `await get_screen_data(...)` for a synchronous call.

Arguments mapping described in
[GetScreenDataRequestRequestTypeDef](./type_defs.md#getscreendatarequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `appId`: `str` *(required)*
- `screenId`: `str` *(required)*
- `variables`: `Mapping`\[`str`,
  [VariableValueTypeDef](./type_defs.md#variablevaluetypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[GetScreenDataResultTypeDef](./type_defs.md#getscreendataresulttypedef).

<a id="invoke\_screen\_automation"></a>

### invoke_screen_automation

The InvokeScreenAutomation API allows invoking an action defined in a screen in
a Honeycode app.

Type annotations for
`session.create_client("honeycode").invoke_screen_automation` method.

Boto3 documentation:
[Honeycode.Client.invoke_screen_automation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.invoke_screen_automation)

Asynchronous method. Use `await invoke_screen_automation(...)` for a
synchronous call.

Arguments mapping described in
[InvokeScreenAutomationRequestRequestTypeDef](./type_defs.md#invokescreenautomationrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `appId`: `str` *(required)*
- `screenId`: `str` *(required)*
- `screenAutomationId`: `str` *(required)*
- `variables`: `Mapping`\[`str`,
  [VariableValueTypeDef](./type_defs.md#variablevaluetypedef)\]
- `rowId`: `str`
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[InvokeScreenAutomationResultTypeDef](./type_defs.md#invokescreenautomationresulttypedef).

<a id="list\_table\_columns"></a>

### list_table_columns

The ListTableColumns API allows you to retrieve a list of all the columns in a
table in a workbook.

Type annotations for `session.create_client("honeycode").list_table_columns`
method.

Boto3 documentation:
[Honeycode.Client.list_table_columns](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.list_table_columns)

Asynchronous method. Use `await list_table_columns(...)` for a synchronous
call.

Arguments mapping described in
[ListTableColumnsRequestRequestTypeDef](./type_defs.md#listtablecolumnsrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `nextToken`: `str`

Returns a `Coroutine` for
[ListTableColumnsResultTypeDef](./type_defs.md#listtablecolumnsresulttypedef).

<a id="list\_table\_rows"></a>

### list_table_rows

The ListTableRows API allows you to retrieve a list of all the rows in a table
in a workbook.

Type annotations for `session.create_client("honeycode").list_table_rows`
method.

Boto3 documentation:
[Honeycode.Client.list_table_rows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.list_table_rows)

Asynchronous method. Use `await list_table_rows(...)` for a synchronous call.

Arguments mapping described in
[ListTableRowsRequestRequestTypeDef](./type_defs.md#listtablerowsrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `rowIds`: `Sequence`\[`str`\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListTableRowsResultTypeDef](./type_defs.md#listtablerowsresulttypedef).

<a id="list\_tables"></a>

### list_tables

The ListTables API allows you to retrieve a list of all the tables in a
workbook.

Type annotations for `session.create_client("honeycode").list_tables` method.

Boto3 documentation:
[Honeycode.Client.list_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.list_tables)

Asynchronous method. Use `await list_tables(...)` for a synchronous call.

Arguments mapping described in
[ListTablesRequestRequestTypeDef](./type_defs.md#listtablesrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListTablesResultTypeDef](./type_defs.md#listtablesresulttypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

The ListTagsForResource API allows you to return a resource's tags.

Type annotations for
`session.create_client("honeycode").list_tags_for_resource` method.

Boto3 documentation:
[Honeycode.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResultTypeDef](./type_defs.md#listtagsforresourceresulttypedef).

<a id="query\_table\_rows"></a>

### query_table_rows

The QueryTableRows API allows you to use a filter formula to query for specific
rows in a table.

Type annotations for `session.create_client("honeycode").query_table_rows`
method.

Boto3 documentation:
[Honeycode.Client.query_table_rows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.query_table_rows)

Asynchronous method. Use `await query_table_rows(...)` for a synchronous call.

Arguments mapping described in
[QueryTableRowsRequestRequestTypeDef](./type_defs.md#querytablerowsrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `tableId`: `str` *(required)*
- `filterFormula`: [FilterTypeDef](./type_defs.md#filtertypedef) *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[QueryTableRowsResultTypeDef](./type_defs.md#querytablerowsresulttypedef).

<a id="start\_table\_data\_import\_job"></a>

### start_table_data_import_job

The StartTableDataImportJob API allows you to start an import job on a table.

Type annotations for
`session.create_client("honeycode").start_table_data_import_job` method.

Boto3 documentation:
[Honeycode.Client.start_table_data_import_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.start_table_data_import_job)

Asynchronous method. Use `await start_table_data_import_job(...)` for a
synchronous call.

Arguments mapping described in
[StartTableDataImportJobRequestRequestTypeDef](./type_defs.md#starttabledataimportjobrequestrequesttypedef).

Keyword-only arguments:

- `workbookId`: `str` *(required)*
- `dataSource`:
  [ImportDataSourceTypeDef](./type_defs.md#importdatasourcetypedef)
  *(required)*
- `dataFormat`: `Literal['DELIMITED_TEXT']` (see
  [ImportSourceDataFormatType](./literals.md#importsourcedataformattype))
  *(required)*
- `destinationTableId`: `str` *(required)*
- `importOptions`: [ImportOptionsTypeDef](./type_defs.md#importoptionstypedef)
  *(required)*
- `clientRequestToken`: `str` *(required)*

Returns a `Coroutine` for
[StartTableDataImportJobResultTypeDef](./type_defs.md#starttabledataimportjobresulttypedef).

<a id="tag\_resource"></a>

### tag_resource

The TagResource API allows you to add tags to an ARN-able resource.

Type annotations for `session.create_client("honeycode").tag_resource` method.

Boto3 documentation:
[Honeycode.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

The UntagResource API allows you to removes tags from an ARN-able resource.

Type annotations for `session.create_client("honeycode").untag_resource`
method.

Boto3 documentation:
[Honeycode.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("honeycode").__aenter__` method.

Boto3 documentation:
[Honeycode.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [HoneycodeClient](#honeycodeclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("honeycode").__aexit__` method.

Boto3 documentation:
[Honeycode.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("honeycode").get_paginator` method
with overloads.

- `client.get_paginator("list_table_columns")` ->
  [ListTableColumnsPaginator](./paginators.md#listtablecolumnspaginator)
- `client.get_paginator("list_table_rows")` ->
  [ListTableRowsPaginator](./paginators.md#listtablerowspaginator)
- `client.get_paginator("list_tables")` ->
  [ListTablesPaginator](./paginators.md#listtablespaginator)
- `client.get_paginator("query_table_rows")` ->
  [QueryTableRowsPaginator](./paginators.md#querytablerowspaginator)
