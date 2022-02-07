<a id="paginators-for-aiobotocore-docdb-module"></a>

# Paginators for aiobotocore DocDB module

> [Index](..) > [DocDB](.) > Paginators

Auto-generated documentation for
[DocDB](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB)
type annotations stubs module
[types-aiobotocore-docdb](https://pypi.org/project/types-aiobotocore-docdb/).

- [Paginators for aiobotocore DocDB module](#paginators-for-aiobotocore-docdb-module)
  - [DescribeCertificatesPaginator](#describecertificatespaginator)
  - [DescribeDBClusterParameterGroupsPaginator](#describedbclusterparametergroupspaginator)
  - [DescribeDBClusterParametersPaginator](#describedbclusterparameterspaginator)
  - [DescribeDBClusterSnapshotsPaginator](#describedbclustersnapshotspaginator)
  - [DescribeDBClustersPaginator](#describedbclusterspaginator)
  - [DescribeDBEngineVersionsPaginator](#describedbengineversionspaginator)
  - [DescribeDBInstancesPaginator](#describedbinstancespaginator)
  - [DescribeDBSubnetGroupsPaginator](#describedbsubnetgroupspaginator)
  - [DescribeEventSubscriptionsPaginator](#describeeventsubscriptionspaginator)
  - [DescribeEventsPaginator](#describeeventspaginator)
  - [DescribeGlobalClustersPaginator](#describeglobalclusterspaginator)
  - [DescribeOrderableDBInstanceOptionsPaginator](#describeorderabledbinstanceoptionspaginator)
  - [DescribePendingMaintenanceActionsPaginator](#describependingmaintenanceactionspaginator)

<a id="describecertificatespaginator"></a>

## DescribeCertificatesPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_certificates")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeCertificatesPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeCertificatesPaginator = client.get_paginator("describe_certificates")
```

Boto3 documentation:
[DocDB.Paginator.DescribeCertificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeCertificates)

Arguments for `DescribeCertificatesPaginator.paginate` method:

- `CertificateIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeCertificatesPaginator.paginate` returns
`_PageIterator`\[[CertificateMessageTypeDef](./type_defs.md#certificatemessagetypedef)\].

<a id="describedbclusterparametergroupspaginator"></a>

## DescribeDBClusterParameterGroupsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_db_cluster_parameter_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeDBClusterParameterGroupsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeDBClusterParameterGroupsPaginator = client.get_paginator("describe_db_cluster_parameter_groups")
```

Boto3 documentation:
[DocDB.Paginator.DescribeDBClusterParameterGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterParameterGroups)

Arguments for `DescribeDBClusterParameterGroupsPaginator.paginate` method:

- `DBClusterParameterGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClusterParameterGroupsPaginator.paginate` returns
`_PageIterator`\[[DBClusterParameterGroupsMessageTypeDef](./type_defs.md#dbclusterparametergroupsmessagetypedef)\].

<a id="describedbclusterparameterspaginator"></a>

## DescribeDBClusterParametersPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_db_cluster_parameters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeDBClusterParametersPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeDBClusterParametersPaginator = client.get_paginator("describe_db_cluster_parameters")
```

Boto3 documentation:
[DocDB.Paginator.DescribeDBClusterParameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterParameters)

Arguments for `DescribeDBClusterParametersPaginator.paginate` method:

- `DBClusterParameterGroupName`: `str` *(required)*
- `Source`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClusterParametersPaginator.paginate` returns
`_PageIterator`\[[DBClusterParameterGroupDetailsTypeDef](./type_defs.md#dbclusterparametergroupdetailstypedef)\].

<a id="describedbclustersnapshotspaginator"></a>

## DescribeDBClusterSnapshotsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_db_cluster_snapshots")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeDBClusterSnapshotsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeDBClusterSnapshotsPaginator = client.get_paginator("describe_db_cluster_snapshots")
```

Boto3 documentation:
[DocDB.Paginator.DescribeDBClusterSnapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterSnapshots)

Arguments for `DescribeDBClusterSnapshotsPaginator.paginate` method:

- `DBClusterIdentifier`: `str`
- `DBClusterSnapshotIdentifier`: `str`
- `SnapshotType`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IncludeShared`: `bool`
- `IncludePublic`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClusterSnapshotsPaginator.paginate` returns
`_PageIterator`\[[DBClusterSnapshotMessageTypeDef](./type_defs.md#dbclustersnapshotmessagetypedef)\].

<a id="describedbclusterspaginator"></a>

## DescribeDBClustersPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_db_clusters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeDBClustersPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeDBClustersPaginator = client.get_paginator("describe_db_clusters")
```

Boto3 documentation:
[DocDB.Paginator.DescribeDBClusters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusters)

Arguments for `DescribeDBClustersPaginator.paginate` method:

- `DBClusterIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClustersPaginator.paginate` returns
`_PageIterator`\[[DBClusterMessageTypeDef](./type_defs.md#dbclustermessagetypedef)\].

<a id="describedbengineversionspaginator"></a>

## DescribeDBEngineVersionsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_db_engine_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeDBEngineVersionsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeDBEngineVersionsPaginator = client.get_paginator("describe_db_engine_versions")
```

Boto3 documentation:
[DocDB.Paginator.DescribeDBEngineVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBEngineVersions)

Arguments for `DescribeDBEngineVersionsPaginator.paginate` method:

- `Engine`: `str`
- `EngineVersion`: `str`
- `DBParameterGroupFamily`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DefaultOnly`: `bool`
- `ListSupportedCharacterSets`: `bool`
- `ListSupportedTimezones`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBEngineVersionsPaginator.paginate` returns
`_PageIterator`\[[DBEngineVersionMessageTypeDef](./type_defs.md#dbengineversionmessagetypedef)\].

<a id="describedbinstancespaginator"></a>

## DescribeDBInstancesPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_db_instances")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeDBInstancesPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeDBInstancesPaginator = client.get_paginator("describe_db_instances")
```

Boto3 documentation:
[DocDB.Paginator.DescribeDBInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBInstances)

Arguments for `DescribeDBInstancesPaginator.paginate` method:

- `DBInstanceIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBInstancesPaginator.paginate` returns
`_PageIterator`\[[DBInstanceMessageTypeDef](./type_defs.md#dbinstancemessagetypedef)\].

<a id="describedbsubnetgroupspaginator"></a>

## DescribeDBSubnetGroupsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_db_subnet_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeDBSubnetGroupsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeDBSubnetGroupsPaginator = client.get_paginator("describe_db_subnet_groups")
```

Boto3 documentation:
[DocDB.Paginator.DescribeDBSubnetGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBSubnetGroups)

Arguments for `DescribeDBSubnetGroupsPaginator.paginate` method:

- `DBSubnetGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBSubnetGroupsPaginator.paginate` returns
`_PageIterator`\[[DBSubnetGroupMessageTypeDef](./type_defs.md#dbsubnetgroupmessagetypedef)\].

<a id="describeeventsubscriptionspaginator"></a>

## DescribeEventSubscriptionsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_event_subscriptions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeEventSubscriptionsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeEventSubscriptionsPaginator = client.get_paginator("describe_event_subscriptions")
```

Boto3 documentation:
[DocDB.Paginator.DescribeEventSubscriptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeEventSubscriptions)

Arguments for `DescribeEventSubscriptionsPaginator.paginate` method:

- `SubscriptionName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEventSubscriptionsPaginator.paginate` returns
`_PageIterator`\[[EventSubscriptionsMessageTypeDef](./type_defs.md#eventsubscriptionsmessagetypedef)\].

<a id="describeeventspaginator"></a>

## DescribeEventsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_events")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeEventsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
```

Boto3 documentation:
[DocDB.Paginator.DescribeEvents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeEvents)

Arguments for `DescribeEventsPaginator.paginate` method:

- `SourceIdentifier`: `str`
- `SourceType`: [SourceTypeType](./literals.md#sourcetypetype)
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `Duration`: `int`
- `EventCategories`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEventsPaginator.paginate` returns
`_PageIterator`\[[EventsMessageTypeDef](./type_defs.md#eventsmessagetypedef)\].

<a id="describeglobalclusterspaginator"></a>

## DescribeGlobalClustersPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_global_clusters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeGlobalClustersPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeGlobalClustersPaginator = client.get_paginator("describe_global_clusters")
```

Boto3 documentation:
[DocDB.Paginator.DescribeGlobalClusters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeGlobalClusters)

Arguments for `DescribeGlobalClustersPaginator.paginate` method:

- `GlobalClusterIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeGlobalClustersPaginator.paginate` returns
`_PageIterator`\[[GlobalClustersMessageTypeDef](./type_defs.md#globalclustersmessagetypedef)\].

<a id="describeorderabledbinstanceoptionspaginator"></a>

## DescribeOrderableDBInstanceOptionsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_orderable_db_instance_options")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribeOrderableDBInstanceOptionsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribeOrderableDBInstanceOptionsPaginator = client.get_paginator("describe_orderable_db_instance_options")
```

Boto3 documentation:
[DocDB.Paginator.DescribeOrderableDBInstanceOptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeOrderableDBInstanceOptions)

Arguments for `DescribeOrderableDBInstanceOptionsPaginator.paginate` method:

- `Engine`: `str` *(required)*
- `EngineVersion`: `str`
- `DBInstanceClass`: `str`
- `LicenseModel`: `str`
- `Vpc`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeOrderableDBInstanceOptionsPaginator.paginate` returns
`_PageIterator`\[[OrderableDBInstanceOptionsMessageTypeDef](./type_defs.md#orderabledbinstanceoptionsmessagetypedef)\].

<a id="describependingmaintenanceactionspaginator"></a>

## DescribePendingMaintenanceActionsPaginator

Type annotations for
`session.create_client("docdb").get_paginator("describe_pending_maintenance_actions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_docdb.paginator import DescribePendingMaintenanceActionsPaginator

session = get_session()
async with session.create_client("docdb") as client:
    client: DocDBClient
    paginator: DescribePendingMaintenanceActionsPaginator = client.get_paginator("describe_pending_maintenance_actions")
```

Boto3 documentation:
[DocDB.Paginator.DescribePendingMaintenanceActions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribePendingMaintenanceActions)

Arguments for `DescribePendingMaintenanceActionsPaginator.paginate` method:

- `ResourceIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePendingMaintenanceActionsPaginator.paginate` returns
`_PageIterator`\[[PendingMaintenanceActionsMessageTypeDef](./type_defs.md#pendingmaintenanceactionsmessagetypedef)\].
