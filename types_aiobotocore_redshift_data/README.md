<a id="type-annotations-for-aiobotocore-redshiftdataapiservice-module"></a>

# Type annotations for aiobotocore RedshiftDataAPIService module

> [Index](..) > RedshiftDataAPIService

Auto-generated documentation for
[RedshiftDataAPIService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
type annotations stubs module
[types-aiobotocore-redshift-data](https://pypi.org/project/types-aiobotocore-redshift-data/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[redshift-data]'

# install as a standalone
pip install types-aiobotocore-redshift-data
```

- [Type annotations for aiobotocore RedshiftDataAPIService module](#type-annotations-for-aiobotocore-redshiftdataapiservice-module)
  - [RedshiftDataAPIServiceClient](#redshiftdataapiserviceclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="redshiftdataapiserviceclient"></a>

## RedshiftDataAPIServiceClient

Type annotations for `aiobotocore.create_client("redshift-data")` as
[RedshiftDataAPIServiceClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_redshift_data.client import RedshiftDataAPIServiceClient
```

<a id="methods"></a>

### Methods

- [batch_execute_statement](./client.md#batch_execute_statement)
- [can_paginate](./client.md#can_paginate)
- [cancel_statement](./client.md#cancel_statement)
- [describe_statement](./client.md#describe_statement)
- [describe_table](./client.md#describe_table)
- [exceptions](./client.md#exceptions)
- [execute_statement](./client.md#execute_statement)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_statement_result](./client.md#get_statement_result)
- [list_databases](./client.md#list_databases)
- [list_schemas](./client.md#list_schemas)
- [list_statements](./client.md#list_statements)
- [list_tables](./client.md#list_tables)

<a id="exceptions"></a>

### Exceptions

RedshiftDataAPIServiceClient [exceptions](./client.md#exceptions)

- ActiveStatementsExceededException
- BatchExecuteStatementException
- ClientError
- DatabaseConnectionException
- ExecuteStatementException
- InternalServerException
- ResourceNotFoundException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("redshift-data").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_redshift_data.paginators import DescribeTablePaginator, ...
```

- [DescribeTablePaginator](./paginators.md#describetablepaginator)
- [GetStatementResultPaginator](./paginators.md#getstatementresultpaginator)
- [ListDatabasesPaginator](./paginators.md#listdatabasespaginator)
- [ListSchemasPaginator](./paginators.md#listschemaspaginator)
- [ListStatementsPaginator](./paginators.md#liststatementspaginator)
- [ListTablesPaginator](./paginators.md#listtablespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_redshift_data.literals import DescribeTablePaginatorName, ...
```

- [DescribeTablePaginatorName](./literals.md#describetablepaginatorname)
- [GetStatementResultPaginatorName](./literals.md#getstatementresultpaginatorname)
- [ListDatabasesPaginatorName](./literals.md#listdatabasespaginatorname)
- [ListSchemasPaginatorName](./literals.md#listschemaspaginatorname)
- [ListStatementsPaginatorName](./literals.md#liststatementspaginatorname)
- [ListTablesPaginatorName](./literals.md#listtablespaginatorname)
- [StatementStatusStringType](./literals.md#statementstatusstringtype)
- [StatusStringType](./literals.md#statusstringtype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_redshift_data.type_defs import BatchExecuteStatementInputRequestTypeDef, ...
```

- [BatchExecuteStatementInputRequestTypeDef](./type_defs.md#batchexecutestatementinputrequesttypedef)
- [BatchExecuteStatementOutputTypeDef](./type_defs.md#batchexecutestatementoutputtypedef)
- [CancelStatementRequestRequestTypeDef](./type_defs.md#cancelstatementrequestrequesttypedef)
- [CancelStatementResponseTypeDef](./type_defs.md#cancelstatementresponsetypedef)
- [ColumnMetadataTypeDef](./type_defs.md#columnmetadatatypedef)
- [DescribeStatementRequestRequestTypeDef](./type_defs.md#describestatementrequestrequesttypedef)
- [DescribeStatementResponseTypeDef](./type_defs.md#describestatementresponsetypedef)
- [DescribeTableRequestRequestTypeDef](./type_defs.md#describetablerequestrequesttypedef)
- [DescribeTableResponseTypeDef](./type_defs.md#describetableresponsetypedef)
- [ExecuteStatementInputRequestTypeDef](./type_defs.md#executestatementinputrequesttypedef)
- [ExecuteStatementOutputTypeDef](./type_defs.md#executestatementoutputtypedef)
- [FieldTypeDef](./type_defs.md#fieldtypedef)
- [GetStatementResultRequestRequestTypeDef](./type_defs.md#getstatementresultrequestrequesttypedef)
- [GetStatementResultResponseTypeDef](./type_defs.md#getstatementresultresponsetypedef)
- [ListDatabasesRequestRequestTypeDef](./type_defs.md#listdatabasesrequestrequesttypedef)
- [ListDatabasesResponseTypeDef](./type_defs.md#listdatabasesresponsetypedef)
- [ListSchemasRequestRequestTypeDef](./type_defs.md#listschemasrequestrequesttypedef)
- [ListSchemasResponseTypeDef](./type_defs.md#listschemasresponsetypedef)
- [ListStatementsRequestRequestTypeDef](./type_defs.md#liststatementsrequestrequesttypedef)
- [ListStatementsResponseTypeDef](./type_defs.md#liststatementsresponsetypedef)
- [ListTablesRequestRequestTypeDef](./type_defs.md#listtablesrequestrequesttypedef)
- [ListTablesResponseTypeDef](./type_defs.md#listtablesresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SqlParameterTypeDef](./type_defs.md#sqlparametertypedef)
- [StatementDataTypeDef](./type_defs.md#statementdatatypedef)
- [SubStatementDataTypeDef](./type_defs.md#substatementdatatypedef)
- [TableMemberTypeDef](./type_defs.md#tablemembertypedef)
