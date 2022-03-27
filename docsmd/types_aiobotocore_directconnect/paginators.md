# Paginators

> [Index](../README.md) > [DirectConnect](./README.md) > Paginators

!!! note ""

    Auto-generated documentation for [DirectConnect](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect)
    type annotations stubs module [types-aiobotocore-directconnect](https://pypi.org/project/types-aiobotocore-directconnect/).

## DescribeDirectConnectGatewayAssociationsPaginator

Type annotations and code completion for `#!python session.create_client("directconnect").get_paginator("describe_direct_connect_gateway_associations")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGatewayAssociations)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_directconnect.paginator import DescribeDirectConnectGatewayAssociationsPaginator

session = get_session()
async with session.create_client("directconnect") as client:
    client: DirectConnectClient
    paginator: DescribeDirectConnectGatewayAssociationsPaginator = client.get_paginator("describe_direct_connect_gateway_associations")
```


### paginate

Type annotations and code completion for `#!python DescribeDirectConnectGatewayAssociationsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    associationId: str = ...,
    associatedGatewayId: str = ...,
    directConnectGatewayId: str = ...,
    virtualGatewayId: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeDirectConnectGatewayAssociationsResultTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeDirectConnectGatewayAssociationsResultTypeDef](./type_defs.md#describedirectconnectgatewayassociationsresulttypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef = {  # (1)
    "associationId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef](./type_defs.md#describedirectconnectgatewayassociationsrequestdescribedirectconnectgatewayassociationspaginatetypedef) 
## DescribeDirectConnectGatewayAttachmentsPaginator

Type annotations and code completion for `#!python session.create_client("directconnect").get_paginator("describe_direct_connect_gateway_attachments")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGatewayAttachments)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_directconnect.paginator import DescribeDirectConnectGatewayAttachmentsPaginator

session = get_session()
async with session.create_client("directconnect") as client:
    client: DirectConnectClient
    paginator: DescribeDirectConnectGatewayAttachmentsPaginator = client.get_paginator("describe_direct_connect_gateway_attachments")
```


### paginate

Type annotations and code completion for `#!python DescribeDirectConnectGatewayAttachmentsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    directConnectGatewayId: str = ...,
    virtualInterfaceId: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeDirectConnectGatewayAttachmentsResultTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeDirectConnectGatewayAttachmentsResultTypeDef](./type_defs.md#describedirectconnectgatewayattachmentsresulttypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef = {  # (1)
    "directConnectGatewayId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef](./type_defs.md#describedirectconnectgatewayattachmentsrequestdescribedirectconnectgatewayattachmentspaginatetypedef) 
## DescribeDirectConnectGatewaysPaginator

Type annotations and code completion for `#!python session.create_client("directconnect").get_paginator("describe_direct_connect_gateways")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGateways)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_directconnect.paginator import DescribeDirectConnectGatewaysPaginator

session = get_session()
async with session.create_client("directconnect") as client:
    client: DirectConnectClient
    paginator: DescribeDirectConnectGatewaysPaginator = client.get_paginator("describe_direct_connect_gateways")
```


### paginate

Type annotations and code completion for `#!python DescribeDirectConnectGatewaysPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    directConnectGatewayId: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeDirectConnectGatewaysResultTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeDirectConnectGatewaysResultTypeDef](./type_defs.md#describedirectconnectgatewaysresulttypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef = {  # (1)
    "directConnectGatewayId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef](./type_defs.md#describedirectconnectgatewaysrequestdescribedirectconnectgatewayspaginatetypedef) 
