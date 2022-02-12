<a id="paginators-for-aiobotocore-appmesh-module"></a>

# Paginators for aiobotocore AppMesh module

> [Index](..) > [AppMesh](.) > Paginators

Auto-generated documentation for
[AppMesh](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh)
type annotations stubs module
[types-aiobotocore-appmesh](https://pypi.org/project/types-aiobotocore-appmesh/).

- [Paginators for aiobotocore AppMesh module](#paginators-for-aiobotocore-appmesh-module)
  - [ListGatewayRoutesPaginator](#listgatewayroutespaginator)
  - [ListMeshesPaginator](#listmeshespaginator)
  - [ListRoutesPaginator](#listroutespaginator)
  - [ListTagsForResourcePaginator](#listtagsforresourcepaginator)
  - [ListVirtualGatewaysPaginator](#listvirtualgatewayspaginator)
  - [ListVirtualNodesPaginator](#listvirtualnodespaginator)
  - [ListVirtualRoutersPaginator](#listvirtualrouterspaginator)
  - [ListVirtualServicesPaginator](#listvirtualservicespaginator)

<a id="listgatewayroutespaginator"></a>

## ListGatewayRoutesPaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_gateway_routes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListGatewayRoutesPaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListGatewayRoutesPaginator = client.get_paginator("list_gateway_routes")
```

Boto3 documentation:
[AppMesh.Paginator.ListGatewayRoutes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListGatewayRoutes)

Arguments for `ListGatewayRoutesPaginator.paginate` method:

- `meshName`: `str` *(required)*
- `virtualGatewayName`: `str` *(required)*
- `meshOwner`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGatewayRoutesPaginator.paginate` returns
`AsyncIterable`\[[ListGatewayRoutesOutputTypeDef](./type_defs.md#listgatewayroutesoutputtypedef)\].

<a id="listmeshespaginator"></a>

## ListMeshesPaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_meshes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListMeshesPaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListMeshesPaginator = client.get_paginator("list_meshes")
```

Boto3 documentation:
[AppMesh.Paginator.ListMeshes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListMeshes)

Arguments for `ListMeshesPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListMeshesPaginator.paginate` returns
`AsyncIterable`\[[ListMeshesOutputTypeDef](./type_defs.md#listmeshesoutputtypedef)\].

<a id="listroutespaginator"></a>

## ListRoutesPaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_routes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListRoutesPaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListRoutesPaginator = client.get_paginator("list_routes")
```

Boto3 documentation:
[AppMesh.Paginator.ListRoutes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListRoutes)

Arguments for `ListRoutesPaginator.paginate` method:

- `meshName`: `str` *(required)*
- `virtualRouterName`: `str` *(required)*
- `meshOwner`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRoutesPaginator.paginate` returns
`AsyncIterable`\[[ListRoutesOutputTypeDef](./type_defs.md#listroutesoutputtypedef)\].

<a id="listtagsforresourcepaginator"></a>

## ListTagsForResourcePaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_tags_for_resource")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListTagsForResourcePaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
```

Boto3 documentation:
[AppMesh.Paginator.ListTagsForResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListTagsForResource)

Arguments for `ListTagsForResourcePaginator.paginate` method:

- `resourceArn`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTagsForResourcePaginator.paginate` returns
`AsyncIterable`\[[ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef)\].

<a id="listvirtualgatewayspaginator"></a>

## ListVirtualGatewaysPaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_virtual_gateways")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListVirtualGatewaysPaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListVirtualGatewaysPaginator = client.get_paginator("list_virtual_gateways")
```

Boto3 documentation:
[AppMesh.Paginator.ListVirtualGateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualGateways)

Arguments for `ListVirtualGatewaysPaginator.paginate` method:

- `meshName`: `str` *(required)*
- `meshOwner`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListVirtualGatewaysPaginator.paginate` returns
`AsyncIterable`\[[ListVirtualGatewaysOutputTypeDef](./type_defs.md#listvirtualgatewaysoutputtypedef)\].

<a id="listvirtualnodespaginator"></a>

## ListVirtualNodesPaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_virtual_nodes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListVirtualNodesPaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListVirtualNodesPaginator = client.get_paginator("list_virtual_nodes")
```

Boto3 documentation:
[AppMesh.Paginator.ListVirtualNodes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualNodes)

Arguments for `ListVirtualNodesPaginator.paginate` method:

- `meshName`: `str` *(required)*
- `meshOwner`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListVirtualNodesPaginator.paginate` returns
`AsyncIterable`\[[ListVirtualNodesOutputTypeDef](./type_defs.md#listvirtualnodesoutputtypedef)\].

<a id="listvirtualrouterspaginator"></a>

## ListVirtualRoutersPaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_virtual_routers")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListVirtualRoutersPaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListVirtualRoutersPaginator = client.get_paginator("list_virtual_routers")
```

Boto3 documentation:
[AppMesh.Paginator.ListVirtualRouters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualRouters)

Arguments for `ListVirtualRoutersPaginator.paginate` method:

- `meshName`: `str` *(required)*
- `meshOwner`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListVirtualRoutersPaginator.paginate` returns
`AsyncIterable`\[[ListVirtualRoutersOutputTypeDef](./type_defs.md#listvirtualroutersoutputtypedef)\].

<a id="listvirtualservicespaginator"></a>

## ListVirtualServicesPaginator

Type annotations for
`session.create_client("appmesh").get_paginator("list_virtual_services")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.paginator import ListVirtualServicesPaginator

session = get_session()
async with session.create_client("appmesh") as client:
    client: AppMeshClient
    paginator: ListVirtualServicesPaginator = client.get_paginator("list_virtual_services")
```

Boto3 documentation:
[AppMesh.Paginator.ListVirtualServices](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualServices)

Arguments for `ListVirtualServicesPaginator.paginate` method:

- `meshName`: `str` *(required)*
- `meshOwner`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListVirtualServicesPaginator.paginate` returns
`AsyncIterable`\[[ListVirtualServicesOutputTypeDef](./type_defs.md#listvirtualservicesoutputtypedef)\].
