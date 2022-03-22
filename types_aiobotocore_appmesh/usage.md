<a id="examples-for-aiobotocore-appmesh-module"></a>

# Examples for aiobotocore AppMesh module

> [Index](../README.md) > [AppMesh](./README.md) > Examples

- [Examples for aiobotocore AppMesh module](#examples-for-aiobotocore-appmesh-module)
  - [Client](#client)
    - [Implicit type annotations](#implicit-type-annotations)
    - [Explicit type annotations](#explicit-type-annotations)

<a id="client"></a>

## Client

<a id="implicit-type-annotations"></a>

### Implicit type annotations

Can be used with `types-aiobotocore[appmesh]` package installed.

Write your `AppMesh` code as usual, type checking and code completion should
work out of the box.

```python
from aiobotocore.session import get_session


session = get_session()

# client has type AppMeshClient
# and provides type checking and code completion
async with session.create_client("appmesh") as client:
    
    # result has type bool
    # and provides type checking and code completion
    # IDE should show a hint with argument names and types
    result = await client.can_paginate()
    

    
    # paginator has type ListGatewayRoutesPaginator and provides type checking
    # and code completion for paginate method
    paginator = client.get_paginator("list_gateway_routes")
    async for item in paginator.paginate(...):
        # item has type ListGatewayRoutesOutputTypeDef
        print(item)
    

    
```

<a id="explicit-type-annotations"></a>

### Explicit type annotations

With `types-aiobotocore-lite[appmesh]` or a standalone
`types_aiobotocore_appmesh` package, you have to explicitly specify
`client: AppMeshClient` type annotation.

All other type annotations are optional, as types should be discovered
automatically. However, these type annotations can be helpful in your functions
and methods.

```python
from aiobotocore.session import get_session

from types_aiobotocore_appmesh.client import AppMeshClient
from types_aiobotocore_appmesh.type_defs import bool
from types_aiobotocore_appmesh.paginator import ListGatewayRoutesPaginator

from types_aiobotocore_appmesh.literals import PaginatorName



session = get_session()

async with session.create_client("appmesh") as client:
    client: AppMeshClient

    
    result: bool = client.can_paginate()
    

    
    paginator_name: PaginatorName = "list_gateway_routes"
    paginator: ListGatewayRoutesPaginator = client.get_paginator(paginator_name)
    async for item in paginator.paginate(...):
        item: ListGatewayRoutesOutputTypeDef
        print(item)
    

    
```
