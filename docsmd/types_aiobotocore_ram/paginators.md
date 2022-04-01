# Paginators

> [Index](../README.md) > [RAM](./README.md) > Paginators

!!! note ""

    Auto-generated documentation for [RAM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
    type annotations stubs module [types-aiobotocore-ram](https://pypi.org/project/types-aiobotocore-ram/).

## GetResourcePoliciesPaginator

Type annotations and code completion for `#!python session.create_client("ram").get_paginator("get_resource_policies")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourcePolicies)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ram.paginator import GetResourcePoliciesPaginator

session = get_session()
async with session.create_client("ram") as client:
    client: RAMClient
    paginator: GetResourcePoliciesPaginator = client.get_paginator("get_resource_policies")
```


### paginate

Type annotations and code completion for `#!python GetResourcePoliciesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    resourceArns: Sequence[str],
    principal: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[GetResourcePoliciesResponseTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: GetResourcePoliciesResponseTypeDef](./type_defs.md#getresourcepoliciesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = {  # (1)
    "resourceArns": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef](./type_defs.md#getresourcepoliciesrequestgetresourcepoliciespaginatetypedef) 
## GetResourceShareAssociationsPaginator

Type annotations and code completion for `#!python session.create_client("ram").get_paginator("get_resource_share_associations")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShareAssociations)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ram.paginator import GetResourceShareAssociationsPaginator

session = get_session()
async with session.create_client("ram") as client:
    client: RAMClient
    paginator: GetResourceShareAssociationsPaginator = client.get_paginator("get_resource_share_associations")
```


### paginate

Type annotations and code completion for `#!python GetResourceShareAssociationsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    associationType: ResourceShareAssociationTypeType,  # (1)
    resourceShareArns: Sequence[str] = ...,
    resourceArn: str = ...,
    principal: str = ...,
    associationStatus: ResourceShareAssociationStatusType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[GetResourceShareAssociationsResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: ResourceShareAssociationTypeType](./literals.md#resourceshareassociationtypetype) 
2. See [:material-code-brackets: ResourceShareAssociationStatusType](./literals.md#resourceshareassociationstatustype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: GetResourceShareAssociationsResponseTypeDef](./type_defs.md#getresourceshareassociationsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = {  # (1)
    "associationType": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef](./type_defs.md#getresourceshareassociationsrequestgetresourceshareassociationspaginatetypedef) 
## GetResourceShareInvitationsPaginator

Type annotations and code completion for `#!python session.create_client("ram").get_paginator("get_resource_share_invitations")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShareInvitations)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ram.paginator import GetResourceShareInvitationsPaginator

session = get_session()
async with session.create_client("ram") as client:
    client: RAMClient
    paginator: GetResourceShareInvitationsPaginator = client.get_paginator("get_resource_share_invitations")
```


### paginate

Type annotations and code completion for `#!python GetResourceShareInvitationsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    resourceShareInvitationArns: Sequence[str] = ...,
    resourceShareArns: Sequence[str] = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[GetResourceShareInvitationsResponseTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: GetResourceShareInvitationsResponseTypeDef](./type_defs.md#getresourceshareinvitationsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef = {  # (1)
    "resourceShareInvitationArns": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef](./type_defs.md#getresourceshareinvitationsrequestgetresourceshareinvitationspaginatetypedef) 
## GetResourceSharesPaginator

Type annotations and code completion for `#!python session.create_client("ram").get_paginator("get_resource_shares")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShares)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ram.paginator import GetResourceSharesPaginator

session = get_session()
async with session.create_client("ram") as client:
    client: RAMClient
    paginator: GetResourceSharesPaginator = client.get_paginator("get_resource_shares")
```


### paginate

Type annotations and code completion for `#!python GetResourceSharesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    resourceOwner: ResourceOwnerType,  # (1)
    resourceShareArns: Sequence[str] = ...,
    resourceShareStatus: ResourceShareStatusType = ...,  # (2)
    name: str = ...,
    tagFilters: Sequence[TagFilterTypeDef] = ...,  # (3)
    permissionArn: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (4)
) -> AsyncIterator[GetResourceSharesResponseTypeDef]:  # (5)
    ...
```

1. See [:material-code-brackets: ResourceOwnerType](./literals.md#resourceownertype) 
2. See [:material-code-brackets: ResourceShareStatusType](./literals.md#resourcesharestatustype) 
3. See [:material-code-braces: TagFilterTypeDef](./type_defs.md#tagfiltertypedef) 
4. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
5. See [:material-code-braces: GetResourceSharesResponseTypeDef](./type_defs.md#getresourcesharesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: GetResourceSharesRequestGetResourceSharesPaginateTypeDef = {  # (1)
    "resourceOwner": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: GetResourceSharesRequestGetResourceSharesPaginateTypeDef](./type_defs.md#getresourcesharesrequestgetresourcesharespaginatetypedef) 
## ListPrincipalsPaginator

Type annotations and code completion for `#!python session.create_client("ram").get_paginator("list_principals")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.ListPrincipals)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ram.paginator import ListPrincipalsPaginator

session = get_session()
async with session.create_client("ram") as client:
    client: RAMClient
    paginator: ListPrincipalsPaginator = client.get_paginator("list_principals")
```


### paginate

Type annotations and code completion for `#!python ListPrincipalsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    resourceOwner: ResourceOwnerType,  # (1)
    resourceArn: str = ...,
    principals: Sequence[str] = ...,
    resourceType: str = ...,
    resourceShareArns: Sequence[str] = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[ListPrincipalsResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-brackets: ResourceOwnerType](./literals.md#resourceownertype) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: ListPrincipalsResponseTypeDef](./type_defs.md#listprincipalsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListPrincipalsRequestListPrincipalsPaginateTypeDef = {  # (1)
    "resourceOwner": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListPrincipalsRequestListPrincipalsPaginateTypeDef](./type_defs.md#listprincipalsrequestlistprincipalspaginatetypedef) 
## ListResourcesPaginator

Type annotations and code completion for `#!python session.create_client("ram").get_paginator("list_resources")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.ListResources)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ram.paginator import ListResourcesPaginator

session = get_session()
async with session.create_client("ram") as client:
    client: RAMClient
    paginator: ListResourcesPaginator = client.get_paginator("list_resources")
```


### paginate

Type annotations and code completion for `#!python ListResourcesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    resourceOwner: ResourceOwnerType,  # (1)
    principal: str = ...,
    resourceType: str = ...,
    resourceArns: Sequence[str] = ...,
    resourceShareArns: Sequence[str] = ...,
    resourceRegionScope: ResourceRegionScopeFilterType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[ListResourcesResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: ResourceOwnerType](./literals.md#resourceownertype) 
2. See [:material-code-brackets: ResourceRegionScopeFilterType](./literals.md#resourceregionscopefiltertype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: ListResourcesResponseTypeDef](./type_defs.md#listresourcesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListResourcesRequestListResourcesPaginateTypeDef = {  # (1)
    "resourceOwner": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListResourcesRequestListResourcesPaginateTypeDef](./type_defs.md#listresourcesrequestlistresourcespaginatetypedef) 
