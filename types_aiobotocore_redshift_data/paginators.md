<a id="paginators-for-aiobotocore-redshiftdataapiservice-module"></a>

# Paginators for aiobotocore RedshiftDataAPIService module

> [Index](..) > [RedshiftDataAPIService](.) > Paginators

Auto-generated documentation for
[RedshiftDataAPIService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
type annotations stubs module
[types-aiobotocore-redshift-data](https://pypi.org/project/types-aiobotocore-redshift-data/).

- [Paginators for aiobotocore RedshiftDataAPIService module](#paginators-for-aiobotocore-redshiftdataapiservice-module)
  - [DescribeTablePaginator](#describetablepaginator)
  - [GetStatementResultPaginator](#getstatementresultpaginator)
  - [ListDatabasesPaginator](#listdatabasespaginator)
  - [ListSchemasPaginator](#listschemaspaginator)
  - [ListStatementsPaginator](#liststatementspaginator)
  - [ListTablesPaginator](#listtablespaginator)

<a id="describetablepaginator"></a>

## DescribeTablePaginator

Type annotations for
`session.create_client("redshift-data").get_paginator("describe_table")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_redshift_data.paginator import DescribeTablePaginator

session = get_session()
async with session.create_client("redshift-data") as client:
    client: RedshiftDataAPIServiceClient
    paginator: DescribeTablePaginator = client.get_paginator("describe_table")
```

Boto3 documentation:
[RedshiftDataAPIService.Paginator.DescribeTable](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.DescribeTable)

Arguments for `DescribeTablePaginator.paginate` method:

- `Database`: `str` *(required)*
- `ClusterIdentifier`: `str`
- `ConnectedDatabase`: `str`
- `DbUser`: `str`
- `Schema`: `str`
- `SecretArn`: `str`
- `Table`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTablePaginator.paginate` returns
`_PageIterator`\[[DescribeTableResponseTypeDef](./type_defs.md#describetableresponsetypedef)\].

<a id="getstatementresultpaginator"></a>

## GetStatementResultPaginator

Type annotations for
`session.create_client("redshift-data").get_paginator("get_statement_result")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_redshift_data.paginator import GetStatementResultPaginator

session = get_session()
async with session.create_client("redshift-data") as client:
    client: RedshiftDataAPIServiceClient
    paginator: GetStatementResultPaginator = client.get_paginator("get_statement_result")
```

Boto3 documentation:
[RedshiftDataAPIService.Paginator.GetStatementResult](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.GetStatementResult)

Arguments for `GetStatementResultPaginator.paginate` method:

- `Id`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetStatementResultPaginator.paginate` returns
`_PageIterator`\[[GetStatementResultResponseTypeDef](./type_defs.md#getstatementresultresponsetypedef)\].

<a id="listdatabasespaginator"></a>

## ListDatabasesPaginator

Type annotations for
`session.create_client("redshift-data").get_paginator("list_databases")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_redshift_data.paginator import ListDatabasesPaginator

session = get_session()
async with session.create_client("redshift-data") as client:
    client: RedshiftDataAPIServiceClient
    paginator: ListDatabasesPaginator = client.get_paginator("list_databases")
```

Boto3 documentation:
[RedshiftDataAPIService.Paginator.ListDatabases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListDatabases)

Arguments for `ListDatabasesPaginator.paginate` method:

- `Database`: `str` *(required)*
- `ClusterIdentifier`: `str`
- `DbUser`: `str`
- `SecretArn`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDatabasesPaginator.paginate` returns
`_PageIterator`\[[ListDatabasesResponseTypeDef](./type_defs.md#listdatabasesresponsetypedef)\].

<a id="listschemaspaginator"></a>

## ListSchemasPaginator

Type annotations for
`session.create_client("redshift-data").get_paginator("list_schemas")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_redshift_data.paginator import ListSchemasPaginator

session = get_session()
async with session.create_client("redshift-data") as client:
    client: RedshiftDataAPIServiceClient
    paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
```

Boto3 documentation:
[RedshiftDataAPIService.Paginator.ListSchemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListSchemas)

Arguments for `ListSchemasPaginator.paginate` method:

- `Database`: `str` *(required)*
- `ClusterIdentifier`: `str`
- `ConnectedDatabase`: `str`
- `DbUser`: `str`
- `SchemaPattern`: `str`
- `SecretArn`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSchemasPaginator.paginate` returns
`_PageIterator`\[[ListSchemasResponseTypeDef](./type_defs.md#listschemasresponsetypedef)\].

<a id="liststatementspaginator"></a>

## ListStatementsPaginator

Type annotations for
`session.create_client("redshift-data").get_paginator("list_statements")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_redshift_data.paginator import ListStatementsPaginator

session = get_session()
async with session.create_client("redshift-data") as client:
    client: RedshiftDataAPIServiceClient
    paginator: ListStatementsPaginator = client.get_paginator("list_statements")
```

Boto3 documentation:
[RedshiftDataAPIService.Paginator.ListStatements](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListStatements)

Arguments for `ListStatementsPaginator.paginate` method:

- `RoleLevel`: `bool`
- `StatementName`: `str`
- `Status`: [StatusStringType](./literals.md#statusstringtype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListStatementsPaginator.paginate` returns
`_PageIterator`\[[ListStatementsResponseTypeDef](./type_defs.md#liststatementsresponsetypedef)\].

<a id="listtablespaginator"></a>

## ListTablesPaginator

Type annotations for
`session.create_client("redshift-data").get_paginator("list_tables")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_redshift_data.paginator import ListTablesPaginator

session = get_session()
async with session.create_client("redshift-data") as client:
    client: RedshiftDataAPIServiceClient
    paginator: ListTablesPaginator = client.get_paginator("list_tables")
```

Boto3 documentation:
[RedshiftDataAPIService.Paginator.ListTables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListTables)

Arguments for `ListTablesPaginator.paginate` method:

- `Database`: `str` *(required)*
- `ClusterIdentifier`: `str`
- `ConnectedDatabase`: `str`
- `DbUser`: `str`
- `SchemaPattern`: `str`
- `SecretArn`: `str`
- `TablePattern`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTablesPaginator.paginate` returns
`_PageIterator`\[[ListTablesResponseTypeDef](./type_defs.md#listtablesresponsetypedef)\].
