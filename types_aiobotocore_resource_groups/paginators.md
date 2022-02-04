<a id="paginators-for-aiobotocore-resourcegroups-module"></a>

# Paginators for aiobotocore ResourceGroups module

> [Index](..) > [ResourceGroups](.) > Paginators

Auto-generated documentation for
[ResourceGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups)
type annotations stubs module
[types-aiobotocore-resource-groups](https://pypi.org/project/types-aiobotocore-resource-groups/).

- [Paginators for aiobotocore ResourceGroups module](#paginators-for-aiobotocore-resourcegroups-module)
  - [ListGroupResourcesPaginator](#listgroupresourcespaginator)
  - [ListGroupsPaginator](#listgroupspaginator)
  - [SearchResourcesPaginator](#searchresourcespaginator)

<a id="listgroupresourcespaginator"></a>

## ListGroupResourcesPaginator

Type annotations for
`aiobotocore.create_client("resource-groups").get_paginator("list_group_resources")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_resource_groups.paginator import ListGroupResourcesPaginator

def get_list_group_resources_paginator() -> ListGroupResourcesPaginator:
    return Session().create_client("resource-groups").get_paginator("list_group_resources")
```

Boto3 documentation:
[ResourceGroups.Paginator.ListGroupResources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.ListGroupResources)

Arguments for `ListGroupResourcesPaginator.paginate` method:

- `GroupName`: `str`
- `Group`: `str`
- `Filters`:
  `Sequence`\[[ResourceFilterTypeDef](./type_defs.md#resourcefiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGroupResourcesPaginator.paginate` returns
`_PageIterator`\[[ListGroupResourcesOutputTypeDef](./type_defs.md#listgroupresourcesoutputtypedef)\].

<a id="listgroupspaginator"></a>

## ListGroupsPaginator

Type annotations for
`aiobotocore.create_client("resource-groups").get_paginator("list_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_resource_groups.paginator import ListGroupsPaginator

def get_list_groups_paginator() -> ListGroupsPaginator:
    return Session().create_client("resource-groups").get_paginator("list_groups")
```

Boto3 documentation:
[ResourceGroups.Paginator.ListGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.ListGroups)

Arguments for `ListGroupsPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[GroupFilterTypeDef](./type_defs.md#groupfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGroupsPaginator.paginate` returns
`_PageIterator`\[[ListGroupsOutputTypeDef](./type_defs.md#listgroupsoutputtypedef)\].

<a id="searchresourcespaginator"></a>

## SearchResourcesPaginator

Type annotations for
`aiobotocore.create_client("resource-groups").get_paginator("search_resources")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_resource_groups.paginator import SearchResourcesPaginator

def get_search_resources_paginator() -> SearchResourcesPaginator:
    return Session().create_client("resource-groups").get_paginator("search_resources")
```

Boto3 documentation:
[ResourceGroups.Paginator.SearchResources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.SearchResources)

Arguments for `SearchResourcesPaginator.paginate` method:

- `ResourceQuery`: [ResourceQueryTypeDef](./type_defs.md#resourcequerytypedef)
  *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`SearchResourcesPaginator.paginate` returns
`_PageIterator`\[[SearchResourcesOutputTypeDef](./type_defs.md#searchresourcesoutputtypedef)\].
