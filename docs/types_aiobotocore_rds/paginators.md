<a id="paginators-for-aiobotocore-rds-module"></a>

# Paginators for aiobotocore RDS module

> [Index](../README.md) > [RDS](./README.md) > Paginators

Auto-generated documentation for
[RDS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS)
type annotations stubs module
[types-aiobotocore-rds](https://pypi.org/project/types-aiobotocore-rds/).

- [Paginators for aiobotocore RDS module](#paginators-for-aiobotocore-rds-module)
  - [DescribeCertificatesPaginator](#describecertificatespaginator)
  - [DescribeCustomAvailabilityZonesPaginator](#describecustomavailabilityzonespaginator)
  - [DescribeDBClusterBacktracksPaginator](#describedbclusterbacktrackspaginator)
  - [DescribeDBClusterEndpointsPaginator](#describedbclusterendpointspaginator)
  - [DescribeDBClusterParameterGroupsPaginator](#describedbclusterparametergroupspaginator)
  - [DescribeDBClusterParametersPaginator](#describedbclusterparameterspaginator)
  - [DescribeDBClusterSnapshotsPaginator](#describedbclustersnapshotspaginator)
  - [DescribeDBClustersPaginator](#describedbclusterspaginator)
  - [DescribeDBEngineVersionsPaginator](#describedbengineversionspaginator)
  - [DescribeDBInstanceAutomatedBackupsPaginator](#describedbinstanceautomatedbackupspaginator)
  - [DescribeDBInstancesPaginator](#describedbinstancespaginator)
  - [DescribeDBLogFilesPaginator](#describedblogfilespaginator)
  - [DescribeDBParameterGroupsPaginator](#describedbparametergroupspaginator)
  - [DescribeDBParametersPaginator](#describedbparameterspaginator)
  - [DescribeDBProxiesPaginator](#describedbproxiespaginator)
  - [DescribeDBProxyEndpointsPaginator](#describedbproxyendpointspaginator)
  - [DescribeDBProxyTargetGroupsPaginator](#describedbproxytargetgroupspaginator)
  - [DescribeDBProxyTargetsPaginator](#describedbproxytargetspaginator)
  - [DescribeDBSecurityGroupsPaginator](#describedbsecuritygroupspaginator)
  - [DescribeDBSnapshotsPaginator](#describedbsnapshotspaginator)
  - [DescribeDBSubnetGroupsPaginator](#describedbsubnetgroupspaginator)
  - [DescribeEngineDefaultClusterParametersPaginator](#describeenginedefaultclusterparameterspaginator)
  - [DescribeEngineDefaultParametersPaginator](#describeenginedefaultparameterspaginator)
  - [DescribeEventSubscriptionsPaginator](#describeeventsubscriptionspaginator)
  - [DescribeEventsPaginator](#describeeventspaginator)
  - [DescribeExportTasksPaginator](#describeexporttaskspaginator)
  - [DescribeGlobalClustersPaginator](#describeglobalclusterspaginator)
  - [DescribeInstallationMediaPaginator](#describeinstallationmediapaginator)
  - [DescribeOptionGroupOptionsPaginator](#describeoptiongroupoptionspaginator)
  - [DescribeOptionGroupsPaginator](#describeoptiongroupspaginator)
  - [DescribeOrderableDBInstanceOptionsPaginator](#describeorderabledbinstanceoptionspaginator)
  - [DescribePendingMaintenanceActionsPaginator](#describependingmaintenanceactionspaginator)
  - [DescribeReservedDBInstancesPaginator](#describereserveddbinstancespaginator)
  - [DescribeReservedDBInstancesOfferingsPaginator](#describereserveddbinstancesofferingspaginator)
  - [DescribeSourceRegionsPaginator](#describesourceregionspaginator)
  - [DownloadDBLogFilePortionPaginator](#downloaddblogfileportionpaginator)

<a id="describecertificatespaginator"></a>

## DescribeCertificatesPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_certificates")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeCertificatesPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeCertificatesPaginator = client.get_paginator("describe_certificates")
```

Boto3 documentation:
[RDS.Paginator.DescribeCertificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeCertificates)

Arguments for `DescribeCertificatesPaginator.paginate` method:

- `CertificateIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeCertificatesPaginator.paginate` returns
`AsyncIterator`\[[CertificateMessageTypeDef](./type_defs.md#certificatemessagetypedef)\].

<a id="describecustomavailabilityzonespaginator"></a>

## DescribeCustomAvailabilityZonesPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_custom_availability_zones")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeCustomAvailabilityZonesPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeCustomAvailabilityZonesPaginator = client.get_paginator("describe_custom_availability_zones")
```

Boto3 documentation:
[RDS.Paginator.DescribeCustomAvailabilityZones](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeCustomAvailabilityZones)

Arguments for `DescribeCustomAvailabilityZonesPaginator.paginate` method:

- `CustomAvailabilityZoneId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeCustomAvailabilityZonesPaginator.paginate` returns
`AsyncIterator`\[[CustomAvailabilityZoneMessageTypeDef](./type_defs.md#customavailabilityzonemessagetypedef)\].

<a id="describedbclusterbacktrackspaginator"></a>

## DescribeDBClusterBacktracksPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_cluster_backtracks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBClusterBacktracksPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBClusterBacktracksPaginator = client.get_paginator("describe_db_cluster_backtracks")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBClusterBacktracks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterBacktracks)

Arguments for `DescribeDBClusterBacktracksPaginator.paginate` method:

- `DBClusterIdentifier`: `str` *(required)*
- `BacktrackIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClusterBacktracksPaginator.paginate` returns
`AsyncIterator`\[[DBClusterBacktrackMessageTypeDef](./type_defs.md#dbclusterbacktrackmessagetypedef)\].

<a id="describedbclusterendpointspaginator"></a>

## DescribeDBClusterEndpointsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_cluster_endpoints")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBClusterEndpointsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBClusterEndpointsPaginator = client.get_paginator("describe_db_cluster_endpoints")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBClusterEndpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterEndpoints)

Arguments for `DescribeDBClusterEndpointsPaginator.paginate` method:

- `DBClusterIdentifier`: `str`
- `DBClusterEndpointIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClusterEndpointsPaginator.paginate` returns
`AsyncIterator`\[[DBClusterEndpointMessageTypeDef](./type_defs.md#dbclusterendpointmessagetypedef)\].

<a id="describedbclusterparametergroupspaginator"></a>

## DescribeDBClusterParameterGroupsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_cluster_parameter_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBClusterParameterGroupsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBClusterParameterGroupsPaginator = client.get_paginator("describe_db_cluster_parameter_groups")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBClusterParameterGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterParameterGroups)

Arguments for `DescribeDBClusterParameterGroupsPaginator.paginate` method:

- `DBClusterParameterGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClusterParameterGroupsPaginator.paginate` returns
`AsyncIterator`\[[DBClusterParameterGroupsMessageTypeDef](./type_defs.md#dbclusterparametergroupsmessagetypedef)\].

<a id="describedbclusterparameterspaginator"></a>

## DescribeDBClusterParametersPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_cluster_parameters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBClusterParametersPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBClusterParametersPaginator = client.get_paginator("describe_db_cluster_parameters")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBClusterParameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterParameters)

Arguments for `DescribeDBClusterParametersPaginator.paginate` method:

- `DBClusterParameterGroupName`: `str` *(required)*
- `Source`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClusterParametersPaginator.paginate` returns
`AsyncIterator`\[[DBClusterParameterGroupDetailsTypeDef](./type_defs.md#dbclusterparametergroupdetailstypedef)\].

<a id="describedbclustersnapshotspaginator"></a>

## DescribeDBClusterSnapshotsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_cluster_snapshots")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBClusterSnapshotsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBClusterSnapshotsPaginator = client.get_paginator("describe_db_cluster_snapshots")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBClusterSnapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterSnapshots)

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
`AsyncIterator`\[[DBClusterSnapshotMessageTypeDef](./type_defs.md#dbclustersnapshotmessagetypedef)\].

<a id="describedbclusterspaginator"></a>

## DescribeDBClustersPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_clusters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBClustersPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBClustersPaginator = client.get_paginator("describe_db_clusters")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBClusters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusters)

Arguments for `DescribeDBClustersPaginator.paginate` method:

- `DBClusterIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IncludeShared`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBClustersPaginator.paginate` returns
`AsyncIterator`\[[DBClusterMessageTypeDef](./type_defs.md#dbclustermessagetypedef)\].

<a id="describedbengineversionspaginator"></a>

## DescribeDBEngineVersionsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_engine_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBEngineVersionsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBEngineVersionsPaginator = client.get_paginator("describe_db_engine_versions")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBEngineVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBEngineVersions)

Arguments for `DescribeDBEngineVersionsPaginator.paginate` method:

- `Engine`: `str`
- `EngineVersion`: `str`
- `DBParameterGroupFamily`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DefaultOnly`: `bool`
- `ListSupportedCharacterSets`: `bool`
- `ListSupportedTimezones`: `bool`
- `IncludeAll`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBEngineVersionsPaginator.paginate` returns
`AsyncIterator`\[[DBEngineVersionMessageTypeDef](./type_defs.md#dbengineversionmessagetypedef)\].

<a id="describedbinstanceautomatedbackupspaginator"></a>

## DescribeDBInstanceAutomatedBackupsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_instance_automated_backups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBInstanceAutomatedBackupsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBInstanceAutomatedBackupsPaginator = client.get_paginator("describe_db_instance_automated_backups")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBInstanceAutomatedBackups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBInstanceAutomatedBackups)

Arguments for `DescribeDBInstanceAutomatedBackupsPaginator.paginate` method:

- `DbiResourceId`: `str`
- `DBInstanceIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DBInstanceAutomatedBackupsArn`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBInstanceAutomatedBackupsPaginator.paginate` returns
`AsyncIterator`\[[DBInstanceAutomatedBackupMessageTypeDef](./type_defs.md#dbinstanceautomatedbackupmessagetypedef)\].

<a id="describedbinstancespaginator"></a>

## DescribeDBInstancesPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_instances")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBInstancesPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBInstancesPaginator = client.get_paginator("describe_db_instances")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBInstances)

Arguments for `DescribeDBInstancesPaginator.paginate` method:

- `DBInstanceIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBInstancesPaginator.paginate` returns
`AsyncIterator`\[[DBInstanceMessageTypeDef](./type_defs.md#dbinstancemessagetypedef)\].

<a id="describedblogfilespaginator"></a>

## DescribeDBLogFilesPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_log_files")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBLogFilesPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBLogFilesPaginator = client.get_paginator("describe_db_log_files")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBLogFiles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBLogFiles)

Arguments for `DescribeDBLogFilesPaginator.paginate` method:

- `DBInstanceIdentifier`: `str` *(required)*
- `FilenameContains`: `str`
- `FileLastWritten`: `int`
- `FileSize`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBLogFilesPaginator.paginate` returns
`AsyncIterator`\[[DescribeDBLogFilesResponseTypeDef](./type_defs.md#describedblogfilesresponsetypedef)\].

<a id="describedbparametergroupspaginator"></a>

## DescribeDBParameterGroupsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_parameter_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBParameterGroupsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBParameterGroupsPaginator = client.get_paginator("describe_db_parameter_groups")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBParameterGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBParameterGroups)

Arguments for `DescribeDBParameterGroupsPaginator.paginate` method:

- `DBParameterGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBParameterGroupsPaginator.paginate` returns
`AsyncIterator`\[[DBParameterGroupsMessageTypeDef](./type_defs.md#dbparametergroupsmessagetypedef)\].

<a id="describedbparameterspaginator"></a>

## DescribeDBParametersPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_parameters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBParametersPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBParametersPaginator = client.get_paginator("describe_db_parameters")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBParameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBParameters)

Arguments for `DescribeDBParametersPaginator.paginate` method:

- `DBParameterGroupName`: `str` *(required)*
- `Source`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBParametersPaginator.paginate` returns
`AsyncIterator`\[[DBParameterGroupDetailsTypeDef](./type_defs.md#dbparametergroupdetailstypedef)\].

<a id="describedbproxiespaginator"></a>

## DescribeDBProxiesPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_proxies")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBProxiesPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBProxiesPaginator = client.get_paginator("describe_db_proxies")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBProxies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxies)

Arguments for `DescribeDBProxiesPaginator.paginate` method:

- `DBProxyName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBProxiesPaginator.paginate` returns
`AsyncIterator`\[[DescribeDBProxiesResponseTypeDef](./type_defs.md#describedbproxiesresponsetypedef)\].

<a id="describedbproxyendpointspaginator"></a>

## DescribeDBProxyEndpointsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_proxy_endpoints")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBProxyEndpointsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBProxyEndpointsPaginator = client.get_paginator("describe_db_proxy_endpoints")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBProxyEndpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyEndpoints)

Arguments for `DescribeDBProxyEndpointsPaginator.paginate` method:

- `DBProxyName`: `str`
- `DBProxyEndpointName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBProxyEndpointsPaginator.paginate` returns
`AsyncIterator`\[[DescribeDBProxyEndpointsResponseTypeDef](./type_defs.md#describedbproxyendpointsresponsetypedef)\].

<a id="describedbproxytargetgroupspaginator"></a>

## DescribeDBProxyTargetGroupsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_proxy_target_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBProxyTargetGroupsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBProxyTargetGroupsPaginator = client.get_paginator("describe_db_proxy_target_groups")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBProxyTargetGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyTargetGroups)

Arguments for `DescribeDBProxyTargetGroupsPaginator.paginate` method:

- `DBProxyName`: `str` *(required)*
- `TargetGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBProxyTargetGroupsPaginator.paginate` returns
`AsyncIterator`\[[DescribeDBProxyTargetGroupsResponseTypeDef](./type_defs.md#describedbproxytargetgroupsresponsetypedef)\].

<a id="describedbproxytargetspaginator"></a>

## DescribeDBProxyTargetsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_proxy_targets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBProxyTargetsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBProxyTargetsPaginator = client.get_paginator("describe_db_proxy_targets")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBProxyTargets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyTargets)

Arguments for `DescribeDBProxyTargetsPaginator.paginate` method:

- `DBProxyName`: `str` *(required)*
- `TargetGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBProxyTargetsPaginator.paginate` returns
`AsyncIterator`\[[DescribeDBProxyTargetsResponseTypeDef](./type_defs.md#describedbproxytargetsresponsetypedef)\].

<a id="describedbsecuritygroupspaginator"></a>

## DescribeDBSecurityGroupsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_security_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBSecurityGroupsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBSecurityGroupsPaginator = client.get_paginator("describe_db_security_groups")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBSecurityGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSecurityGroups)

Arguments for `DescribeDBSecurityGroupsPaginator.paginate` method:

- `DBSecurityGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBSecurityGroupsPaginator.paginate` returns
`AsyncIterator`\[[DBSecurityGroupMessageTypeDef](./type_defs.md#dbsecuritygroupmessagetypedef)\].

<a id="describedbsnapshotspaginator"></a>

## DescribeDBSnapshotsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_snapshots")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBSnapshotsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBSnapshotsPaginator = client.get_paginator("describe_db_snapshots")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBSnapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSnapshots)

Arguments for `DescribeDBSnapshotsPaginator.paginate` method:

- `DBInstanceIdentifier`: `str`
- `DBSnapshotIdentifier`: `str`
- `SnapshotType`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IncludeShared`: `bool`
- `IncludePublic`: `bool`
- `DbiResourceId`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBSnapshotsPaginator.paginate` returns
`AsyncIterator`\[[DBSnapshotMessageTypeDef](./type_defs.md#dbsnapshotmessagetypedef)\].

<a id="describedbsubnetgroupspaginator"></a>

## DescribeDBSubnetGroupsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_db_subnet_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeDBSubnetGroupsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeDBSubnetGroupsPaginator = client.get_paginator("describe_db_subnet_groups")
```

Boto3 documentation:
[RDS.Paginator.DescribeDBSubnetGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSubnetGroups)

Arguments for `DescribeDBSubnetGroupsPaginator.paginate` method:

- `DBSubnetGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDBSubnetGroupsPaginator.paginate` returns
`AsyncIterator`\[[DBSubnetGroupMessageTypeDef](./type_defs.md#dbsubnetgroupmessagetypedef)\].

<a id="describeenginedefaultclusterparameterspaginator"></a>

## DescribeEngineDefaultClusterParametersPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_engine_default_cluster_parameters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeEngineDefaultClusterParametersPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeEngineDefaultClusterParametersPaginator = client.get_paginator("describe_engine_default_cluster_parameters")
```

Boto3 documentation:
[RDS.Paginator.DescribeEngineDefaultClusterParameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEngineDefaultClusterParameters)

Arguments for `DescribeEngineDefaultClusterParametersPaginator.paginate`
method:

- `DBParameterGroupFamily`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEngineDefaultClusterParametersPaginator.paginate` returns
`AsyncIterator`\[[DescribeEngineDefaultClusterParametersResultTypeDef](./type_defs.md#describeenginedefaultclusterparametersresulttypedef)\].

<a id="describeenginedefaultparameterspaginator"></a>

## DescribeEngineDefaultParametersPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_engine_default_parameters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeEngineDefaultParametersPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeEngineDefaultParametersPaginator = client.get_paginator("describe_engine_default_parameters")
```

Boto3 documentation:
[RDS.Paginator.DescribeEngineDefaultParameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEngineDefaultParameters)

Arguments for `DescribeEngineDefaultParametersPaginator.paginate` method:

- `DBParameterGroupFamily`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEngineDefaultParametersPaginator.paginate` returns
`AsyncIterator`\[[DescribeEngineDefaultParametersResultTypeDef](./type_defs.md#describeenginedefaultparametersresulttypedef)\].

<a id="describeeventsubscriptionspaginator"></a>

## DescribeEventSubscriptionsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_event_subscriptions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeEventSubscriptionsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeEventSubscriptionsPaginator = client.get_paginator("describe_event_subscriptions")
```

Boto3 documentation:
[RDS.Paginator.DescribeEventSubscriptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEventSubscriptions)

Arguments for `DescribeEventSubscriptionsPaginator.paginate` method:

- `SubscriptionName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEventSubscriptionsPaginator.paginate` returns
`AsyncIterator`\[[EventSubscriptionsMessageTypeDef](./type_defs.md#eventsubscriptionsmessagetypedef)\].

<a id="describeeventspaginator"></a>

## DescribeEventsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_events")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeEventsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
```

Boto3 documentation:
[RDS.Paginator.DescribeEvents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEvents)

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
`AsyncIterator`\[[EventsMessageTypeDef](./type_defs.md#eventsmessagetypedef)\].

<a id="describeexporttaskspaginator"></a>

## DescribeExportTasksPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_export_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeExportTasksPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeExportTasksPaginator = client.get_paginator("describe_export_tasks")
```

Boto3 documentation:
[RDS.Paginator.DescribeExportTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeExportTasks)

Arguments for `DescribeExportTasksPaginator.paginate` method:

- `ExportTaskIdentifier`: `str`
- `SourceArn`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeExportTasksPaginator.paginate` returns
`AsyncIterator`\[[ExportTasksMessageTypeDef](./type_defs.md#exporttasksmessagetypedef)\].

<a id="describeglobalclusterspaginator"></a>

## DescribeGlobalClustersPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_global_clusters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeGlobalClustersPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeGlobalClustersPaginator = client.get_paginator("describe_global_clusters")
```

Boto3 documentation:
[RDS.Paginator.DescribeGlobalClusters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeGlobalClusters)

Arguments for `DescribeGlobalClustersPaginator.paginate` method:

- `GlobalClusterIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeGlobalClustersPaginator.paginate` returns
`AsyncIterator`\[[GlobalClustersMessageTypeDef](./type_defs.md#globalclustersmessagetypedef)\].

<a id="describeinstallationmediapaginator"></a>

## DescribeInstallationMediaPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_installation_media")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeInstallationMediaPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeInstallationMediaPaginator = client.get_paginator("describe_installation_media")
```

Boto3 documentation:
[RDS.Paginator.DescribeInstallationMedia](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeInstallationMedia)

Arguments for `DescribeInstallationMediaPaginator.paginate` method:

- `InstallationMediaId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstallationMediaPaginator.paginate` returns
`AsyncIterator`\[[InstallationMediaMessageTypeDef](./type_defs.md#installationmediamessagetypedef)\].

<a id="describeoptiongroupoptionspaginator"></a>

## DescribeOptionGroupOptionsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_option_group_options")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeOptionGroupOptionsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeOptionGroupOptionsPaginator = client.get_paginator("describe_option_group_options")
```

Boto3 documentation:
[RDS.Paginator.DescribeOptionGroupOptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOptionGroupOptions)

Arguments for `DescribeOptionGroupOptionsPaginator.paginate` method:

- `EngineName`: `str` *(required)*
- `MajorEngineVersion`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeOptionGroupOptionsPaginator.paginate` returns
`AsyncIterator`\[[OptionGroupOptionsMessageTypeDef](./type_defs.md#optiongroupoptionsmessagetypedef)\].

<a id="describeoptiongroupspaginator"></a>

## DescribeOptionGroupsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_option_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeOptionGroupsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeOptionGroupsPaginator = client.get_paginator("describe_option_groups")
```

Boto3 documentation:
[RDS.Paginator.DescribeOptionGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOptionGroups)

Arguments for `DescribeOptionGroupsPaginator.paginate` method:

- `OptionGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `EngineName`: `str`
- `MajorEngineVersion`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeOptionGroupsPaginator.paginate` returns
`AsyncIterator`\[[OptionGroupsTypeDef](./type_defs.md#optiongroupstypedef)\].

<a id="describeorderabledbinstanceoptionspaginator"></a>

## DescribeOrderableDBInstanceOptionsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_orderable_db_instance_options")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeOrderableDBInstanceOptionsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeOrderableDBInstanceOptionsPaginator = client.get_paginator("describe_orderable_db_instance_options")
```

Boto3 documentation:
[RDS.Paginator.DescribeOrderableDBInstanceOptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOrderableDBInstanceOptions)

Arguments for `DescribeOrderableDBInstanceOptionsPaginator.paginate` method:

- `Engine`: `str` *(required)*
- `EngineVersion`: `str`
- `DBInstanceClass`: `str`
- `LicenseModel`: `str`
- `AvailabilityZoneGroup`: `str`
- `Vpc`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeOrderableDBInstanceOptionsPaginator.paginate` returns
`AsyncIterator`\[[OrderableDBInstanceOptionsMessageTypeDef](./type_defs.md#orderabledbinstanceoptionsmessagetypedef)\].

<a id="describependingmaintenanceactionspaginator"></a>

## DescribePendingMaintenanceActionsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_pending_maintenance_actions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribePendingMaintenanceActionsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribePendingMaintenanceActionsPaginator = client.get_paginator("describe_pending_maintenance_actions")
```

Boto3 documentation:
[RDS.Paginator.DescribePendingMaintenanceActions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribePendingMaintenanceActions)

Arguments for `DescribePendingMaintenanceActionsPaginator.paginate` method:

- `ResourceIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePendingMaintenanceActionsPaginator.paginate` returns
`AsyncIterator`\[[PendingMaintenanceActionsMessageTypeDef](./type_defs.md#pendingmaintenanceactionsmessagetypedef)\].

<a id="describereserveddbinstancespaginator"></a>

## DescribeReservedDBInstancesPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_reserved_db_instances")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeReservedDBInstancesPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeReservedDBInstancesPaginator = client.get_paginator("describe_reserved_db_instances")
```

Boto3 documentation:
[RDS.Paginator.DescribeReservedDBInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeReservedDBInstances)

Arguments for `DescribeReservedDBInstancesPaginator.paginate` method:

- `ReservedDBInstanceId`: `str`
- `ReservedDBInstancesOfferingId`: `str`
- `DBInstanceClass`: `str`
- `Duration`: `str`
- `ProductDescription`: `str`
- `OfferingType`: `str`
- `MultiAZ`: `bool`
- `LeaseId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeReservedDBInstancesPaginator.paginate` returns
`AsyncIterator`\[[ReservedDBInstanceMessageTypeDef](./type_defs.md#reserveddbinstancemessagetypedef)\].

<a id="describereserveddbinstancesofferingspaginator"></a>

## DescribeReservedDBInstancesOfferingsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_reserved_db_instances_offerings")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeReservedDBInstancesOfferingsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeReservedDBInstancesOfferingsPaginator = client.get_paginator("describe_reserved_db_instances_offerings")
```

Boto3 documentation:
[RDS.Paginator.DescribeReservedDBInstancesOfferings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeReservedDBInstancesOfferings)

Arguments for `DescribeReservedDBInstancesOfferingsPaginator.paginate` method:

- `ReservedDBInstancesOfferingId`: `str`
- `DBInstanceClass`: `str`
- `Duration`: `str`
- `ProductDescription`: `str`
- `OfferingType`: `str`
- `MultiAZ`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeReservedDBInstancesOfferingsPaginator.paginate` returns
`AsyncIterator`\[[ReservedDBInstancesOfferingMessageTypeDef](./type_defs.md#reserveddbinstancesofferingmessagetypedef)\].

<a id="describesourceregionspaginator"></a>

## DescribeSourceRegionsPaginator

Type annotations for
`session.create_client("rds").get_paginator("describe_source_regions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DescribeSourceRegionsPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DescribeSourceRegionsPaginator = client.get_paginator("describe_source_regions")
```

Boto3 documentation:
[RDS.Paginator.DescribeSourceRegions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeSourceRegions)

Arguments for `DescribeSourceRegionsPaginator.paginate` method:

- `RegionName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSourceRegionsPaginator.paginate` returns
`AsyncIterator`\[[SourceRegionMessageTypeDef](./type_defs.md#sourceregionmessagetypedef)\].

<a id="downloaddblogfileportionpaginator"></a>

## DownloadDBLogFilePortionPaginator

Type annotations for
`session.create_client("rds").get_paginator("download_db_log_file_portion")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_rds.paginator import DownloadDBLogFilePortionPaginator

session = get_session()
async with session.create_client("rds") as client:
    client: RDSClient
    paginator: DownloadDBLogFilePortionPaginator = client.get_paginator("download_db_log_file_portion")
```

Boto3 documentation:
[RDS.Paginator.DownloadDBLogFilePortion](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DownloadDBLogFilePortion)

Arguments for `DownloadDBLogFilePortionPaginator.paginate` method:

- `DBInstanceIdentifier`: `str` *(required)*
- `LogFileName`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DownloadDBLogFilePortionPaginator.paginate` returns
`AsyncIterator`\[[DownloadDBLogFilePortionDetailsTypeDef](./type_defs.md#downloaddblogfileportiondetailstypedef)\].
