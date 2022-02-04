<a id="paginators-for-aiobotocore-schemas-module"></a>

# Paginators for aiobotocore Schemas module

> [Index](..) > [Schemas](.) > Paginators

Auto-generated documentation for
[Schemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
type annotations stubs module
[types-aiobotocore-schemas](https://pypi.org/project/types-aiobotocore-schemas/).

- [Paginators for aiobotocore Schemas module](#paginators-for-aiobotocore-schemas-module)
  - [ListDiscoverersPaginator](#listdiscovererspaginator)
  - [ListRegistriesPaginator](#listregistriespaginator)
  - [ListSchemaVersionsPaginator](#listschemaversionspaginator)
  - [ListSchemasPaginator](#listschemaspaginator)
  - [SearchSchemasPaginator](#searchschemaspaginator)

<a id="listdiscovererspaginator"></a>

## ListDiscoverersPaginator

Type annotations for
`aiobotocore.create_client("schemas").get_paginator("list_discoverers")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_schemas.paginator import ListDiscoverersPaginator

def get_list_discoverers_paginator() -> ListDiscoverersPaginator:
    return Session().create_client("schemas").get_paginator("list_discoverers")
```

Boto3 documentation:
[Schemas.Paginator.ListDiscoverers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListDiscoverers)

Arguments for `ListDiscoverersPaginator.paginate` method:

- `DiscovererIdPrefix`: `str`
- `SourceArnPrefix`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDiscoverersPaginator.paginate` returns
`_PageIterator`\[[ListDiscoverersResponseTypeDef](./type_defs.md#listdiscoverersresponsetypedef)\].

<a id="listregistriespaginator"></a>

## ListRegistriesPaginator

Type annotations for
`aiobotocore.create_client("schemas").get_paginator("list_registries")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_schemas.paginator import ListRegistriesPaginator

def get_list_registries_paginator() -> ListRegistriesPaginator:
    return Session().create_client("schemas").get_paginator("list_registries")
```

Boto3 documentation:
[Schemas.Paginator.ListRegistries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListRegistries)

Arguments for `ListRegistriesPaginator.paginate` method:

- `RegistryNamePrefix`: `str`
- `Scope`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRegistriesPaginator.paginate` returns
`_PageIterator`\[[ListRegistriesResponseTypeDef](./type_defs.md#listregistriesresponsetypedef)\].

<a id="listschemaversionspaginator"></a>

## ListSchemaVersionsPaginator

Type annotations for
`aiobotocore.create_client("schemas").get_paginator("list_schema_versions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_schemas.paginator import ListSchemaVersionsPaginator

def get_list_schema_versions_paginator() -> ListSchemaVersionsPaginator:
    return Session().create_client("schemas").get_paginator("list_schema_versions")
```

Boto3 documentation:
[Schemas.Paginator.ListSchemaVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemaVersions)

Arguments for `ListSchemaVersionsPaginator.paginate` method:

- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSchemaVersionsPaginator.paginate` returns
`_PageIterator`\[[ListSchemaVersionsResponseTypeDef](./type_defs.md#listschemaversionsresponsetypedef)\].

<a id="listschemaspaginator"></a>

## ListSchemasPaginator

Type annotations for
`aiobotocore.create_client("schemas").get_paginator("list_schemas")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_schemas.paginator import ListSchemasPaginator

def get_list_schemas_paginator() -> ListSchemasPaginator:
    return Session().create_client("schemas").get_paginator("list_schemas")
```

Boto3 documentation:
[Schemas.Paginator.ListSchemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemas)

Arguments for `ListSchemasPaginator.paginate` method:

- `RegistryName`: `str` *(required)*
- `SchemaNamePrefix`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSchemasPaginator.paginate` returns
`_PageIterator`\[[ListSchemasResponseTypeDef](./type_defs.md#listschemasresponsetypedef)\].

<a id="searchschemaspaginator"></a>

## SearchSchemasPaginator

Type annotations for
`aiobotocore.create_client("schemas").get_paginator("search_schemas")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_schemas.paginator import SearchSchemasPaginator

def get_search_schemas_paginator() -> SearchSchemasPaginator:
    return Session().create_client("schemas").get_paginator("search_schemas")
```

Boto3 documentation:
[Schemas.Paginator.SearchSchemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.SearchSchemas)

Arguments for `SearchSchemasPaginator.paginate` method:

- `Keywords`: `str` *(required)*
- `RegistryName`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`SearchSchemasPaginator.paginate` returns
`_PageIterator`\[[SearchSchemasResponseTypeDef](./type_defs.md#searchschemasresponsetypedef)\].
