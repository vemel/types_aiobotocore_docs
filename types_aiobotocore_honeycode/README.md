<a id="type-annotations-for-aiobotocore-honeycode-module"></a>

# Type annotations for aiobotocore Honeycode module

> [Index](..) > Honeycode

Auto-generated documentation for
[Honeycode](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
type annotations stubs module
[types-aiobotocore-honeycode](https://pypi.org/project/types-aiobotocore-honeycode/).

- [Type annotations for aiobotocore Honeycode module](#type-annotations-for-aiobotocore-honeycode-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [HoneycodeClient](#honeycodeclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `Honeycode`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `Honeycode` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[honeycode]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[honeycode]'

# standalone installation
python -m pip install types-aiobotocore-honeycode
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-honeycode
```

<a id="honeycodeclient"></a>

## HoneycodeClient

Type annotations for `session.create_client("honeycode")` as
[HoneycodeClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_honeycode.client import HoneycodeClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [batch_create_table_rows](./client.md#batch_create_table_rows)
- [batch_delete_table_rows](./client.md#batch_delete_table_rows)
- [batch_update_table_rows](./client.md#batch_update_table_rows)
- [batch_upsert_table_rows](./client.md#batch_upsert_table_rows)
- [can_paginate](./client.md#can_paginate)
- [describe_table_data_import_job](./client.md#describe_table_data_import_job)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_screen_data](./client.md#get_screen_data)
- [invoke_screen_automation](./client.md#invoke_screen_automation)
- [list_table_columns](./client.md#list_table_columns)
- [list_table_rows](./client.md#list_table_rows)
- [list_tables](./client.md#list_tables)
- [query_table_rows](./client.md#query_table_rows)
- [start_table_data_import_job](./client.md#start_table_data_import_job)

<a id="exceptions"></a>

### Exceptions

HoneycodeClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- AutomationExecutionException
- AutomationExecutionTimeoutException
- ClientError
- InternalServerException
- RequestTimeoutException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ServiceUnavailableException
- ThrottlingException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("honeycode").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_honeycode.paginator import ListTableColumnsPaginator, ...
```

- [ListTableColumnsPaginator](./paginators.md#listtablecolumnspaginator)
- [ListTableRowsPaginator](./paginators.md#listtablerowspaginator)
- [ListTablesPaginator](./paginators.md#listtablespaginator)
- [QueryTableRowsPaginator](./paginators.md#querytablerowspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_honeycode.literals import FormatType, ...
```

- [FormatType](./literals.md#formattype)
- [ImportDataCharacterEncodingType](./literals.md#importdatacharacterencodingtype)
- [ImportSourceDataFormatType](./literals.md#importsourcedataformattype)
- [ListTableColumnsPaginatorName](./literals.md#listtablecolumnspaginatorname)
- [ListTableRowsPaginatorName](./literals.md#listtablerowspaginatorname)
- [ListTablesPaginatorName](./literals.md#listtablespaginatorname)
- [QueryTableRowsPaginatorName](./literals.md#querytablerowspaginatorname)
- [TableDataImportJobStatusType](./literals.md#tabledataimportjobstatustype)
- [UpsertActionType](./literals.md#upsertactiontype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_honeycode.type_defs import BatchCreateTableRowsRequestRequestTypeDef, ...
```

- [BatchCreateTableRowsRequestRequestTypeDef](./type_defs.md#batchcreatetablerowsrequestrequesttypedef)
- [BatchCreateTableRowsResultTypeDef](./type_defs.md#batchcreatetablerowsresulttypedef)
- [BatchDeleteTableRowsRequestRequestTypeDef](./type_defs.md#batchdeletetablerowsrequestrequesttypedef)
- [BatchDeleteTableRowsResultTypeDef](./type_defs.md#batchdeletetablerowsresulttypedef)
- [BatchUpdateTableRowsRequestRequestTypeDef](./type_defs.md#batchupdatetablerowsrequestrequesttypedef)
- [BatchUpdateTableRowsResultTypeDef](./type_defs.md#batchupdatetablerowsresulttypedef)
- [BatchUpsertTableRowsRequestRequestTypeDef](./type_defs.md#batchupserttablerowsrequestrequesttypedef)
- [BatchUpsertTableRowsResultTypeDef](./type_defs.md#batchupserttablerowsresulttypedef)
- [CellInputTypeDef](./type_defs.md#cellinputtypedef)
- [CellTypeDef](./type_defs.md#celltypedef)
- [ColumnMetadataTypeDef](./type_defs.md#columnmetadatatypedef)
- [CreateRowDataTypeDef](./type_defs.md#createrowdatatypedef)
- [DataItemTypeDef](./type_defs.md#dataitemtypedef)
- [DelimitedTextImportOptionsTypeDef](./type_defs.md#delimitedtextimportoptionstypedef)
- [DescribeTableDataImportJobRequestRequestTypeDef](./type_defs.md#describetabledataimportjobrequestrequesttypedef)
- [DescribeTableDataImportJobResultTypeDef](./type_defs.md#describetabledataimportjobresulttypedef)
- [DestinationOptionsTypeDef](./type_defs.md#destinationoptionstypedef)
- [FailedBatchItemTypeDef](./type_defs.md#failedbatchitemtypedef)
- [FilterTypeDef](./type_defs.md#filtertypedef)
- [GetScreenDataRequestRequestTypeDef](./type_defs.md#getscreendatarequestrequesttypedef)
- [GetScreenDataResultTypeDef](./type_defs.md#getscreendataresulttypedef)
- [ImportDataSourceConfigTypeDef](./type_defs.md#importdatasourceconfigtypedef)
- [ImportDataSourceTypeDef](./type_defs.md#importdatasourcetypedef)
- [ImportJobSubmitterTypeDef](./type_defs.md#importjobsubmittertypedef)
- [ImportOptionsTypeDef](./type_defs.md#importoptionstypedef)
- [InvokeScreenAutomationRequestRequestTypeDef](./type_defs.md#invokescreenautomationrequestrequesttypedef)
- [InvokeScreenAutomationResultTypeDef](./type_defs.md#invokescreenautomationresulttypedef)
- [ListTableColumnsRequestRequestTypeDef](./type_defs.md#listtablecolumnsrequestrequesttypedef)
- [ListTableColumnsResultTypeDef](./type_defs.md#listtablecolumnsresulttypedef)
- [ListTableRowsRequestRequestTypeDef](./type_defs.md#listtablerowsrequestrequesttypedef)
- [ListTableRowsResultTypeDef](./type_defs.md#listtablerowsresulttypedef)
- [ListTablesRequestRequestTypeDef](./type_defs.md#listtablesrequestrequesttypedef)
- [ListTablesResultTypeDef](./type_defs.md#listtablesresulttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [QueryTableRowsRequestRequestTypeDef](./type_defs.md#querytablerowsrequestrequesttypedef)
- [QueryTableRowsResultTypeDef](./type_defs.md#querytablerowsresulttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ResultRowTypeDef](./type_defs.md#resultrowtypedef)
- [ResultSetTypeDef](./type_defs.md#resultsettypedef)
- [SourceDataColumnPropertiesTypeDef](./type_defs.md#sourcedatacolumnpropertiestypedef)
- [StartTableDataImportJobRequestRequestTypeDef](./type_defs.md#starttabledataimportjobrequestrequesttypedef)
- [StartTableDataImportJobResultTypeDef](./type_defs.md#starttabledataimportjobresulttypedef)
- [TableColumnTypeDef](./type_defs.md#tablecolumntypedef)
- [TableDataImportJobMetadataTypeDef](./type_defs.md#tabledataimportjobmetadatatypedef)
- [TableRowTypeDef](./type_defs.md#tablerowtypedef)
- [TableTypeDef](./type_defs.md#tabletypedef)
- [UpdateRowDataTypeDef](./type_defs.md#updaterowdatatypedef)
- [UpsertRowDataTypeDef](./type_defs.md#upsertrowdatatypedef)
- [UpsertRowsResultTypeDef](./type_defs.md#upsertrowsresulttypedef)
- [VariableValueTypeDef](./type_defs.md#variablevaluetypedef)
