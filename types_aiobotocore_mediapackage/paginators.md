<a id="paginators-for-aiobotocore-mediapackage-module"></a>

# Paginators for aiobotocore MediaPackage module

> [Index](..) > [MediaPackage](.) > Paginators

Auto-generated documentation for
[MediaPackage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage)
type annotations stubs module
[types-aiobotocore-mediapackage](https://pypi.org/project/types-aiobotocore-mediapackage/).

- [Paginators for aiobotocore MediaPackage module](#paginators-for-aiobotocore-mediapackage-module)
  - [ListChannelsPaginator](#listchannelspaginator)
  - [ListHarvestJobsPaginator](#listharvestjobspaginator)
  - [ListOriginEndpointsPaginator](#listoriginendpointspaginator)

<a id="listchannelspaginator"></a>

## ListChannelsPaginator

Type annotations for
`aiobotocore.create_client("mediapackage").get_paginator("list_channels")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_mediapackage.paginator import ListChannelsPaginator

def get_list_channels_paginator() -> ListChannelsPaginator:
    return Session().create_client("mediapackage").get_paginator("list_channels")
```

Boto3 documentation:
[MediaPackage.Paginator.ListChannels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListChannels)

Arguments for `ListChannelsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListChannelsPaginator.paginate` returns
`_PageIterator`\[[ListChannelsResponseTypeDef](./type_defs.md#listchannelsresponsetypedef)\].

<a id="listharvestjobspaginator"></a>

## ListHarvestJobsPaginator

Type annotations for
`aiobotocore.create_client("mediapackage").get_paginator("list_harvest_jobs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_mediapackage.paginator import ListHarvestJobsPaginator

def get_list_harvest_jobs_paginator() -> ListHarvestJobsPaginator:
    return Session().create_client("mediapackage").get_paginator("list_harvest_jobs")
```

Boto3 documentation:
[MediaPackage.Paginator.ListHarvestJobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListHarvestJobs)

Arguments for `ListHarvestJobsPaginator.paginate` method:

- `IncludeChannelId`: `str`
- `IncludeStatus`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListHarvestJobsPaginator.paginate` returns
`_PageIterator`\[[ListHarvestJobsResponseTypeDef](./type_defs.md#listharvestjobsresponsetypedef)\].

<a id="listoriginendpointspaginator"></a>

## ListOriginEndpointsPaginator

Type annotations for
`aiobotocore.create_client("mediapackage").get_paginator("list_origin_endpoints")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_mediapackage.paginator import ListOriginEndpointsPaginator

def get_list_origin_endpoints_paginator() -> ListOriginEndpointsPaginator:
    return Session().create_client("mediapackage").get_paginator("list_origin_endpoints")
```

Boto3 documentation:
[MediaPackage.Paginator.ListOriginEndpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListOriginEndpoints)

Arguments for `ListOriginEndpointsPaginator.paginate` method:

- `ChannelId`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListOriginEndpointsPaginator.paginate` returns
`_PageIterator`\[[ListOriginEndpointsResponseTypeDef](./type_defs.md#listoriginendpointsresponsetypedef)\].
