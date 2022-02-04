<a id="paginators-for-aiobotocore-appsync-module"></a>

# Paginators for aiobotocore AppSync module

> [Index](..) > [AppSync](.) > Paginators

Auto-generated documentation for
[AppSync](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
type annotations stubs module
[types-aiobotocore-appsync](https://pypi.org/project/types-aiobotocore-appsync/).

- [Paginators for aiobotocore AppSync module](#paginators-for-aiobotocore-appsync-module)
  - [ListApiKeysPaginator](#listapikeyspaginator)
  - [ListDataSourcesPaginator](#listdatasourcespaginator)
  - [ListFunctionsPaginator](#listfunctionspaginator)
  - [ListGraphqlApisPaginator](#listgraphqlapispaginator)
  - [ListResolversPaginator](#listresolverspaginator)
  - [ListResolversByFunctionPaginator](#listresolversbyfunctionpaginator)
  - [ListTypesPaginator](#listtypespaginator)

<a id="listapikeyspaginator"></a>

## ListApiKeysPaginator

Type annotations for
`aiobotocore.create_client("appsync").get_paginator("list_api_keys")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_appsync.paginator import ListApiKeysPaginator

def get_list_api_keys_paginator() -> ListApiKeysPaginator:
    return Session().create_client("appsync").get_paginator("list_api_keys")
```

Boto3 documentation:
[AppSync.Paginator.ListApiKeys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListApiKeys)

Arguments for `ListApiKeysPaginator.paginate` method:

- `apiId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListApiKeysPaginator.paginate` returns
`_PageIterator`\[[ListApiKeysResponseTypeDef](./type_defs.md#listapikeysresponsetypedef)\].

<a id="listdatasourcespaginator"></a>

## ListDataSourcesPaginator

Type annotations for
`aiobotocore.create_client("appsync").get_paginator("list_data_sources")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_appsync.paginator import ListDataSourcesPaginator

def get_list_data_sources_paginator() -> ListDataSourcesPaginator:
    return Session().create_client("appsync").get_paginator("list_data_sources")
```

Boto3 documentation:
[AppSync.Paginator.ListDataSources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListDataSources)

Arguments for `ListDataSourcesPaginator.paginate` method:

- `apiId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDataSourcesPaginator.paginate` returns
`_PageIterator`\[[ListDataSourcesResponseTypeDef](./type_defs.md#listdatasourcesresponsetypedef)\].

<a id="listfunctionspaginator"></a>

## ListFunctionsPaginator

Type annotations for
`aiobotocore.create_client("appsync").get_paginator("list_functions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_appsync.paginator import ListFunctionsPaginator

def get_list_functions_paginator() -> ListFunctionsPaginator:
    return Session().create_client("appsync").get_paginator("list_functions")
```

Boto3 documentation:
[AppSync.Paginator.ListFunctions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListFunctions)

Arguments for `ListFunctionsPaginator.paginate` method:

- `apiId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListFunctionsPaginator.paginate` returns
`_PageIterator`\[[ListFunctionsResponseTypeDef](./type_defs.md#listfunctionsresponsetypedef)\].

<a id="listgraphqlapispaginator"></a>

## ListGraphqlApisPaginator

Type annotations for
`aiobotocore.create_client("appsync").get_paginator("list_graphql_apis")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_appsync.paginator import ListGraphqlApisPaginator

def get_list_graphql_apis_paginator() -> ListGraphqlApisPaginator:
    return Session().create_client("appsync").get_paginator("list_graphql_apis")
```

Boto3 documentation:
[AppSync.Paginator.ListGraphqlApis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListGraphqlApis)

Arguments for `ListGraphqlApisPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGraphqlApisPaginator.paginate` returns
`_PageIterator`\[[ListGraphqlApisResponseTypeDef](./type_defs.md#listgraphqlapisresponsetypedef)\].

<a id="listresolverspaginator"></a>

## ListResolversPaginator

Type annotations for
`aiobotocore.create_client("appsync").get_paginator("list_resolvers")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_appsync.paginator import ListResolversPaginator

def get_list_resolvers_paginator() -> ListResolversPaginator:
    return Session().create_client("appsync").get_paginator("list_resolvers")
```

Boto3 documentation:
[AppSync.Paginator.ListResolvers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolvers)

Arguments for `ListResolversPaginator.paginate` method:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListResolversPaginator.paginate` returns
`_PageIterator`\[[ListResolversResponseTypeDef](./type_defs.md#listresolversresponsetypedef)\].

<a id="listresolversbyfunctionpaginator"></a>

## ListResolversByFunctionPaginator

Type annotations for
`aiobotocore.create_client("appsync").get_paginator("list_resolvers_by_function")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_appsync.paginator import ListResolversByFunctionPaginator

def get_list_resolvers_by_function_paginator() -> ListResolversByFunctionPaginator:
    return Session().create_client("appsync").get_paginator("list_resolvers_by_function")
```

Boto3 documentation:
[AppSync.Paginator.ListResolversByFunction](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolversByFunction)

Arguments for `ListResolversByFunctionPaginator.paginate` method:

- `apiId`: `str` *(required)*
- `functionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListResolversByFunctionPaginator.paginate` returns
`_PageIterator`\[[ListResolversByFunctionResponseTypeDef](./type_defs.md#listresolversbyfunctionresponsetypedef)\].

<a id="listtypespaginator"></a>

## ListTypesPaginator

Type annotations for
`aiobotocore.create_client("appsync").get_paginator("list_types")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_appsync.paginator import ListTypesPaginator

def get_list_types_paginator() -> ListTypesPaginator:
    return Session().create_client("appsync").get_paginator("list_types")
```

Boto3 documentation:
[AppSync.Paginator.ListTypes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListTypes)

Arguments for `ListTypesPaginator.paginate` method:

- `apiId`: `str` *(required)*
- `format`: [TypeDefinitionFormatType](./literals.md#typedefinitionformattype)
  *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTypesPaginator.paginate` returns
`_PageIterator`\[[ListTypesResponseTypeDef](./type_defs.md#listtypesresponsetypedef)\].
