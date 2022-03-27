# Paginators

> [Index](../README.md) > [ElastiCache](./README.md) > Paginators

!!! note ""

    Auto-generated documentation for [ElastiCache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
    type annotations stubs module [types-aiobotocore-elasticache](https://pypi.org/project/types-aiobotocore-elasticache/).

## DescribeCacheClustersPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_cache_clusters")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheClusters)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeCacheClustersPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeCacheClustersPaginator = client.get_paginator("describe_cache_clusters")
```


### paginate

Type annotations and code completion for `#!python DescribeCacheClustersPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    CacheClusterId: str = ...,
    ShowCacheNodeInfo: bool = ...,
    ShowCacheClustersNotInReplicationGroups: bool = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[CacheClusterMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: CacheClusterMessageTypeDef](./type_defs.md#cacheclustermessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef = {  # (1)
    "CacheClusterId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef](./type_defs.md#describecacheclustersmessagedescribecacheclusterspaginatetypedef) 
## DescribeCacheEngineVersionsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_cache_engine_versions")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheEngineVersions)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeCacheEngineVersionsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeCacheEngineVersionsPaginator = client.get_paginator("describe_cache_engine_versions")
```


### paginate

Type annotations and code completion for `#!python DescribeCacheEngineVersionsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    Engine: str = ...,
    EngineVersion: str = ...,
    CacheParameterGroupFamily: str = ...,
    DefaultOnly: bool = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[CacheEngineVersionMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: CacheEngineVersionMessageTypeDef](./type_defs.md#cacheengineversionmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef = {  # (1)
    "Engine": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef](./type_defs.md#describecacheengineversionsmessagedescribecacheengineversionspaginatetypedef) 
## DescribeCacheParameterGroupsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_cache_parameter_groups")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameterGroups)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeCacheParameterGroupsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeCacheParameterGroupsPaginator = client.get_paginator("describe_cache_parameter_groups")
```


### paginate

Type annotations and code completion for `#!python DescribeCacheParameterGroupsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    CacheParameterGroupName: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[CacheParameterGroupsMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: CacheParameterGroupsMessageTypeDef](./type_defs.md#cacheparametergroupsmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef = {  # (1)
    "CacheParameterGroupName": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef](./type_defs.md#describecacheparametergroupsmessagedescribecacheparametergroupspaginatetypedef) 
## DescribeCacheParametersPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_cache_parameters")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameters)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeCacheParametersPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeCacheParametersPaginator = client.get_paginator("describe_cache_parameters")
```


### paginate

Type annotations and code completion for `#!python DescribeCacheParametersPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    CacheParameterGroupName: str,
    Source: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[CacheParameterGroupDetailsTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: CacheParameterGroupDetailsTypeDef](./type_defs.md#cacheparametergroupdetailstypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = {  # (1)
    "CacheParameterGroupName": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef](./type_defs.md#describecacheparametersmessagedescribecacheparameterspaginatetypedef) 
## DescribeCacheSecurityGroupsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_cache_security_groups")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSecurityGroups)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeCacheSecurityGroupsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeCacheSecurityGroupsPaginator = client.get_paginator("describe_cache_security_groups")
```


### paginate

Type annotations and code completion for `#!python DescribeCacheSecurityGroupsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    CacheSecurityGroupName: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[CacheSecurityGroupMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: CacheSecurityGroupMessageTypeDef](./type_defs.md#cachesecuritygroupmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef = {  # (1)
    "CacheSecurityGroupName": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef](./type_defs.md#describecachesecuritygroupsmessagedescribecachesecuritygroupspaginatetypedef) 
## DescribeCacheSubnetGroupsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_cache_subnet_groups")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSubnetGroups)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeCacheSubnetGroupsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeCacheSubnetGroupsPaginator = client.get_paginator("describe_cache_subnet_groups")
```


### paginate

Type annotations and code completion for `#!python DescribeCacheSubnetGroupsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    CacheSubnetGroupName: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[CacheSubnetGroupMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: CacheSubnetGroupMessageTypeDef](./type_defs.md#cachesubnetgroupmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef = {  # (1)
    "CacheSubnetGroupName": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef](./type_defs.md#describecachesubnetgroupsmessagedescribecachesubnetgroupspaginatetypedef) 
## DescribeEngineDefaultParametersPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_engine_default_parameters")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEngineDefaultParameters)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeEngineDefaultParametersPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeEngineDefaultParametersPaginator = client.get_paginator("describe_engine_default_parameters")
```


### paginate

Type annotations and code completion for `#!python DescribeEngineDefaultParametersPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    CacheParameterGroupFamily: str,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeEngineDefaultParametersResultTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeEngineDefaultParametersResultTypeDef](./type_defs.md#describeenginedefaultparametersresulttypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = {  # (1)
    "CacheParameterGroupFamily": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef](./type_defs.md#describeenginedefaultparametersmessagedescribeenginedefaultparameterspaginatetypedef) 
## DescribeEventsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_events")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEvents)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeEventsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
```


### paginate

Type annotations and code completion for `#!python DescribeEventsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    SourceIdentifier: str = ...,
    SourceType: SourceTypeType = ...,  # (1)
    StartTime: Union[datetime, str] = ...,
    EndTime: Union[datetime, str] = ...,
    Duration: int = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[EventsMessageTypeDef]:  # (3)
    ...
```

1. See [:material-code-brackets: SourceTypeType](./literals.md#sourcetypetype) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: EventsMessageTypeDef](./type_defs.md#eventsmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeEventsMessageDescribeEventsPaginateTypeDef = {  # (1)
    "SourceIdentifier": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeEventsMessageDescribeEventsPaginateTypeDef](./type_defs.md#describeeventsmessagedescribeeventspaginatetypedef) 
## DescribeGlobalReplicationGroupsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_global_replication_groups")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeGlobalReplicationGroups)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeGlobalReplicationGroupsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeGlobalReplicationGroupsPaginator = client.get_paginator("describe_global_replication_groups")
```


### paginate

Type annotations and code completion for `#!python DescribeGlobalReplicationGroupsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    GlobalReplicationGroupId: str = ...,
    ShowMemberInfo: bool = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeGlobalReplicationGroupsResultTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeGlobalReplicationGroupsResultTypeDef](./type_defs.md#describeglobalreplicationgroupsresulttypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef = {  # (1)
    "GlobalReplicationGroupId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef](./type_defs.md#describeglobalreplicationgroupsmessagedescribeglobalreplicationgroupspaginatetypedef) 
## DescribeReplicationGroupsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_replication_groups")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReplicationGroups)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeReplicationGroupsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeReplicationGroupsPaginator = client.get_paginator("describe_replication_groups")
```


### paginate

Type annotations and code completion for `#!python DescribeReplicationGroupsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ReplicationGroupId: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[ReplicationGroupMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: ReplicationGroupMessageTypeDef](./type_defs.md#replicationgroupmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef = {  # (1)
    "ReplicationGroupId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef](./type_defs.md#describereplicationgroupsmessagedescribereplicationgroupspaginatetypedef) 
## DescribeReservedCacheNodesPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_reserved_cache_nodes")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodes)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeReservedCacheNodesPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeReservedCacheNodesPaginator = client.get_paginator("describe_reserved_cache_nodes")
```


### paginate

Type annotations and code completion for `#!python DescribeReservedCacheNodesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ReservedCacheNodeId: str = ...,
    ReservedCacheNodesOfferingId: str = ...,
    CacheNodeType: str = ...,
    Duration: str = ...,
    ProductDescription: str = ...,
    OfferingType: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[ReservedCacheNodeMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: ReservedCacheNodeMessageTypeDef](./type_defs.md#reservedcachenodemessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef = {  # (1)
    "ReservedCacheNodeId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef](./type_defs.md#describereservedcachenodesmessagedescribereservedcachenodespaginatetypedef) 
## DescribeReservedCacheNodesOfferingsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_reserved_cache_nodes_offerings")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodesOfferings)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeReservedCacheNodesOfferingsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeReservedCacheNodesOfferingsPaginator = client.get_paginator("describe_reserved_cache_nodes_offerings")
```


### paginate

Type annotations and code completion for `#!python DescribeReservedCacheNodesOfferingsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ReservedCacheNodesOfferingId: str = ...,
    CacheNodeType: str = ...,
    Duration: str = ...,
    ProductDescription: str = ...,
    OfferingType: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[ReservedCacheNodesOfferingMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: ReservedCacheNodesOfferingMessageTypeDef](./type_defs.md#reservedcachenodesofferingmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef = {  # (1)
    "ReservedCacheNodesOfferingId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef](./type_defs.md#describereservedcachenodesofferingsmessagedescribereservedcachenodesofferingspaginatetypedef) 
## DescribeServiceUpdatesPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_service_updates")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeServiceUpdates)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeServiceUpdatesPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeServiceUpdatesPaginator = client.get_paginator("describe_service_updates")
```


### paginate

Type annotations and code completion for `#!python DescribeServiceUpdatesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ServiceUpdateName: str = ...,
    ServiceUpdateStatus: Sequence[ServiceUpdateStatusType] = ...,  # (1)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[ServiceUpdatesMessageTypeDef]:  # (3)
    ...
```

1. See [:material-code-brackets: ServiceUpdateStatusType](./literals.md#serviceupdatestatustype) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: ServiceUpdatesMessageTypeDef](./type_defs.md#serviceupdatesmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef = {  # (1)
    "ServiceUpdateName": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef](./type_defs.md#describeserviceupdatesmessagedescribeserviceupdatespaginatetypedef) 
## DescribeSnapshotsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_snapshots")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeSnapshots)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeSnapshotsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeSnapshotsPaginator = client.get_paginator("describe_snapshots")
```


### paginate

Type annotations and code completion for `#!python DescribeSnapshotsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ReplicationGroupId: str = ...,
    CacheClusterId: str = ...,
    SnapshotName: str = ...,
    SnapshotSource: str = ...,
    ShowNodeGroupConfig: bool = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeSnapshotsListMessageTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeSnapshotsListMessageTypeDef](./type_defs.md#describesnapshotslistmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef = {  # (1)
    "ReplicationGroupId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef](./type_defs.md#describesnapshotsmessagedescribesnapshotspaginatetypedef) 
## DescribeUpdateActionsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_update_actions")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUpdateActions)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeUpdateActionsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeUpdateActionsPaginator = client.get_paginator("describe_update_actions")
```


### paginate

Type annotations and code completion for `#!python DescribeUpdateActionsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ServiceUpdateName: str = ...,
    ReplicationGroupIds: Sequence[str] = ...,
    CacheClusterIds: Sequence[str] = ...,
    Engine: str = ...,
    ServiceUpdateStatus: Sequence[ServiceUpdateStatusType] = ...,  # (1)
    ServiceUpdateTimeRange: TimeRangeFilterTypeDef = ...,  # (2)
    UpdateActionStatus: Sequence[UpdateActionStatusType] = ...,  # (3)
    ShowNodeLevelUpdateStatus: bool = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (4)
) -> AsyncIterator[UpdateActionsMessageTypeDef]:  # (5)
    ...
```

1. See [:material-code-brackets: ServiceUpdateStatusType](./literals.md#serviceupdatestatustype) 
2. See [:material-code-braces: TimeRangeFilterTypeDef](./type_defs.md#timerangefiltertypedef) 
3. See [:material-code-brackets: UpdateActionStatusType](./literals.md#updateactionstatustype) 
4. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
5. See [:material-code-braces: UpdateActionsMessageTypeDef](./type_defs.md#updateactionsmessagetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef = {  # (1)
    "ServiceUpdateName": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef](./type_defs.md#describeupdateactionsmessagedescribeupdateactionspaginatetypedef) 
## DescribeUserGroupsPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_user_groups")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUserGroups)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeUserGroupsPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeUserGroupsPaginator = client.get_paginator("describe_user_groups")
```


### paginate

Type annotations and code completion for `#!python DescribeUserGroupsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    UserGroupId: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeUserGroupsResultTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeUserGroupsResultTypeDef](./type_defs.md#describeusergroupsresulttypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef = {  # (1)
    "UserGroupId": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef](./type_defs.md#describeusergroupsmessagedescribeusergroupspaginatetypedef) 
## DescribeUsersPaginator

Type annotations and code completion for `#!python session.create_client("elasticache").get_paginator("describe_users")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUsers)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_elasticache.paginator import DescribeUsersPaginator

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
    paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
```


### paginate

Type annotations and code completion for `#!python DescribeUsersPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    Engine: str = ...,
    UserId: str = ...,
    Filters: Sequence[FilterTypeDef] = ...,  # (1)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[DescribeUsersResultTypeDef]:  # (3)
    ...
```

1. See [:material-code-braces: FilterTypeDef](./type_defs.md#filtertypedef) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: DescribeUsersResultTypeDef](./type_defs.md#describeusersresulttypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeUsersMessageDescribeUsersPaginateTypeDef = {  # (1)
    "Engine": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeUsersMessageDescribeUsersPaginateTypeDef](./type_defs.md#describeusersmessagedescribeuserspaginatetypedef) 
