<a id="elasticacheclient-for-aiobotocore-elasticache-module"></a>

# ElastiCacheClient for aiobotocore ElastiCache module

> [Index](../README.md) > [ElastiCache](./README.md) > ElastiCacheClient

Auto-generated documentation for
[ElastiCache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
type annotations stubs module
[types-aiobotocore-elasticache](https://pypi.org/project/types-aiobotocore-elasticache/).

- [ElastiCacheClient for aiobotocore ElastiCache module](#elasticacheclient-for-aiobotocore-elasticache-module)
  - [ElastiCacheClient](#elasticacheclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_tags_to_resource](#add_tags_to_resource)
    - [authorize_cache_security_group_ingress](#authorize_cache_security_group_ingress)
    - [batch_apply_update_action](#batch_apply_update_action)
    - [batch_stop_update_action](#batch_stop_update_action)
    - [can_paginate](#can_paginate)
    - [complete_migration](#complete_migration)
    - [copy_snapshot](#copy_snapshot)
    - [create_cache_cluster](#create_cache_cluster)
    - [create_cache_parameter_group](#create_cache_parameter_group)
    - [create_cache_security_group](#create_cache_security_group)
    - [create_cache_subnet_group](#create_cache_subnet_group)
    - [create_global_replication_group](#create_global_replication_group)
    - [create_replication_group](#create_replication_group)
    - [create_snapshot](#create_snapshot)
    - [create_user](#create_user)
    - [create_user_group](#create_user_group)
    - [decrease_node_groups_in_global_replication_group](#decrease_node_groups_in_global_replication_group)
    - [decrease_replica_count](#decrease_replica_count)
    - [delete_cache_cluster](#delete_cache_cluster)
    - [delete_cache_parameter_group](#delete_cache_parameter_group)
    - [delete_cache_security_group](#delete_cache_security_group)
    - [delete_cache_subnet_group](#delete_cache_subnet_group)
    - [delete_global_replication_group](#delete_global_replication_group)
    - [delete_replication_group](#delete_replication_group)
    - [delete_snapshot](#delete_snapshot)
    - [delete_user](#delete_user)
    - [delete_user_group](#delete_user_group)
    - [describe_cache_clusters](#describe_cache_clusters)
    - [describe_cache_engine_versions](#describe_cache_engine_versions)
    - [describe_cache_parameter_groups](#describe_cache_parameter_groups)
    - [describe_cache_parameters](#describe_cache_parameters)
    - [describe_cache_security_groups](#describe_cache_security_groups)
    - [describe_cache_subnet_groups](#describe_cache_subnet_groups)
    - [describe_engine_default_parameters](#describe_engine_default_parameters)
    - [describe_events](#describe_events)
    - [describe_global_replication_groups](#describe_global_replication_groups)
    - [describe_replication_groups](#describe_replication_groups)
    - [describe_reserved_cache_nodes](#describe_reserved_cache_nodes)
    - [describe_reserved_cache_nodes_offerings](#describe_reserved_cache_nodes_offerings)
    - [describe_service_updates](#describe_service_updates)
    - [describe_snapshots](#describe_snapshots)
    - [describe_update_actions](#describe_update_actions)
    - [describe_user_groups](#describe_user_groups)
    - [describe_users](#describe_users)
    - [disassociate_global_replication_group](#disassociate_global_replication_group)
    - [failover_global_replication_group](#failover_global_replication_group)
    - [generate_presigned_url](#generate_presigned_url)
    - [increase_node_groups_in_global_replication_group](#increase_node_groups_in_global_replication_group)
    - [increase_replica_count](#increase_replica_count)
    - [list_allowed_node_type_modifications](#list_allowed_node_type_modifications)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [modify_cache_cluster](#modify_cache_cluster)
    - [modify_cache_parameter_group](#modify_cache_parameter_group)
    - [modify_cache_subnet_group](#modify_cache_subnet_group)
    - [modify_global_replication_group](#modify_global_replication_group)
    - [modify_replication_group](#modify_replication_group)
    - [modify_replication_group_shard_configuration](#modify_replication_group_shard_configuration)
    - [modify_user](#modify_user)
    - [modify_user_group](#modify_user_group)
    - [purchase_reserved_cache_nodes_offering](#purchase_reserved_cache_nodes_offering)
    - [rebalance_slots_in_global_replication_group](#rebalance_slots_in_global_replication_group)
    - [reboot_cache_cluster](#reboot_cache_cluster)
    - [remove_tags_from_resource](#remove_tags_from_resource)
    - [reset_cache_parameter_group](#reset_cache_parameter_group)
    - [revoke_cache_security_group_ingress](#revoke_cache_security_group_ingress)
    - [start_migration](#start_migration)
    - [test_failover](#test_failover)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="elasticacheclient"></a>

## ElastiCacheClient

Type annotations for `session.create_client("elasticache")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_elasticache.client import ElastiCacheClient

session = get_session()
async with session.create_client("elasticache") as client:
    client: ElastiCacheClient
```

Boto3 documentation:
[ElastiCache.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_elasticache.client import Exceptions

def handle_error(exc: Exceptions.APICallRateForCustomerExceededFault) -> None:
    ...
```

Exceptions:

- `Exceptions.APICallRateForCustomerExceededFault`
- `Exceptions.AuthorizationAlreadyExistsFault`
- `Exceptions.AuthorizationNotFoundFault`
- `Exceptions.CacheClusterAlreadyExistsFault`
- `Exceptions.CacheClusterNotFoundFault`
- `Exceptions.CacheParameterGroupAlreadyExistsFault`
- `Exceptions.CacheParameterGroupNotFoundFault`
- `Exceptions.CacheParameterGroupQuotaExceededFault`
- `Exceptions.CacheSecurityGroupAlreadyExistsFault`
- `Exceptions.CacheSecurityGroupNotFoundFault`
- `Exceptions.CacheSecurityGroupQuotaExceededFault`
- `Exceptions.CacheSubnetGroupAlreadyExistsFault`
- `Exceptions.CacheSubnetGroupInUse`
- `Exceptions.CacheSubnetGroupNotFoundFault`
- `Exceptions.CacheSubnetGroupQuotaExceededFault`
- `Exceptions.CacheSubnetQuotaExceededFault`
- `Exceptions.ClientError`
- `Exceptions.ClusterQuotaForCustomerExceededFault`
- `Exceptions.DefaultUserAssociatedToUserGroupFault`
- `Exceptions.DefaultUserRequired`
- `Exceptions.DuplicateUserNameFault`
- `Exceptions.GlobalReplicationGroupAlreadyExistsFault`
- `Exceptions.GlobalReplicationGroupNotFoundFault`
- `Exceptions.InsufficientCacheClusterCapacityFault`
- `Exceptions.InvalidARNFault`
- `Exceptions.InvalidCacheClusterStateFault`
- `Exceptions.InvalidCacheParameterGroupStateFault`
- `Exceptions.InvalidCacheSecurityGroupStateFault`
- `Exceptions.InvalidGlobalReplicationGroupStateFault`
- `Exceptions.InvalidKMSKeyFault`
- `Exceptions.InvalidParameterCombinationException`
- `Exceptions.InvalidParameterValueException`
- `Exceptions.InvalidReplicationGroupStateFault`
- `Exceptions.InvalidSnapshotStateFault`
- `Exceptions.InvalidSubnet`
- `Exceptions.InvalidUserGroupStateFault`
- `Exceptions.InvalidUserStateFault`
- `Exceptions.InvalidVPCNetworkStateFault`
- `Exceptions.NoOperationFault`
- `Exceptions.NodeGroupNotFoundFault`
- `Exceptions.NodeGroupsPerReplicationGroupQuotaExceededFault`
- `Exceptions.NodeQuotaForClusterExceededFault`
- `Exceptions.NodeQuotaForCustomerExceededFault`
- `Exceptions.ReplicationGroupAlreadyExistsFault`
- `Exceptions.ReplicationGroupAlreadyUnderMigrationFault`
- `Exceptions.ReplicationGroupNotFoundFault`
- `Exceptions.ReplicationGroupNotUnderMigrationFault`
- `Exceptions.ReservedCacheNodeAlreadyExistsFault`
- `Exceptions.ReservedCacheNodeNotFoundFault`
- `Exceptions.ReservedCacheNodeQuotaExceededFault`
- `Exceptions.ReservedCacheNodesOfferingNotFoundFault`
- `Exceptions.ServiceLinkedRoleNotFoundFault`
- `Exceptions.ServiceUpdateNotFoundFault`
- `Exceptions.SnapshotAlreadyExistsFault`
- `Exceptions.SnapshotFeatureNotSupportedFault`
- `Exceptions.SnapshotNotFoundFault`
- `Exceptions.SnapshotQuotaExceededFault`
- `Exceptions.SubnetInUse`
- `Exceptions.SubnetNotAllowedFault`
- `Exceptions.TagNotFoundFault`
- `Exceptions.TagQuotaPerResourceExceeded`
- `Exceptions.TestFailoverNotAvailableFault`
- `Exceptions.UserAlreadyExistsFault`
- `Exceptions.UserGroupAlreadyExistsFault`
- `Exceptions.UserGroupNotFoundFault`
- `Exceptions.UserGroupQuotaExceededFault`
- `Exceptions.UserNotFoundFault`
- `Exceptions.UserQuotaExceededFault`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ElastiCacheClient exceptions.

Type annotations for `session.create_client("elasticache").exceptions` method.

Boto3 documentation:
[ElastiCache.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add\_tags\_to\_resource"></a>

### add_tags_to_resource

A tag is a key-value pair where the key and value are case-sensitive.

Type annotations for
`session.create_client("elasticache").add_tags_to_resource` method.

Boto3 documentation:
[ElastiCache.Client.add_tags_to_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.add_tags_to_resource)

Asynchronous method. Use `await add_tags_to_resource(...)` for a synchronous
call.

Arguments mapping described in
[AddTagsToResourceMessageRequestTypeDef](./type_defs.md#addtagstoresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceName`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for
[TagListMessageTypeDef](./type_defs.md#taglistmessagetypedef).

<a id="authorize\_cache\_security\_group\_ingress"></a>

### authorize_cache_security_group_ingress

Allows network ingress to a cache security group.

Type annotations for
`session.create_client("elasticache").authorize_cache_security_group_ingress`
method.

Boto3 documentation:
[ElastiCache.Client.authorize_cache_security_group_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.authorize_cache_security_group_ingress)

Asynchronous method. Use `await authorize_cache_security_group_ingress(...)`
for a synchronous call.

Arguments mapping described in
[AuthorizeCacheSecurityGroupIngressMessageRequestTypeDef](./type_defs.md#authorizecachesecuritygroupingressmessagerequesttypedef).

Keyword-only arguments:

- `CacheSecurityGroupName`: `str` *(required)*
- `EC2SecurityGroupName`: `str` *(required)*
- `EC2SecurityGroupOwnerId`: `str` *(required)*

Returns a `Coroutine` for
[AuthorizeCacheSecurityGroupIngressResultTypeDef](./type_defs.md#authorizecachesecuritygroupingressresulttypedef).

<a id="batch\_apply\_update\_action"></a>

### batch_apply_update_action

Apply the service update.

Type annotations for
`session.create_client("elasticache").batch_apply_update_action` method.

Boto3 documentation:
[ElastiCache.Client.batch_apply_update_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.batch_apply_update_action)

Asynchronous method. Use `await batch_apply_update_action(...)` for a
synchronous call.

Arguments mapping described in
[BatchApplyUpdateActionMessageRequestTypeDef](./type_defs.md#batchapplyupdateactionmessagerequesttypedef).

Keyword-only arguments:

- `ServiceUpdateName`: `str` *(required)*
- `ReplicationGroupIds`: `Sequence`\[`str`\]
- `CacheClusterIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[UpdateActionResultsMessageTypeDef](./type_defs.md#updateactionresultsmessagetypedef).

<a id="batch\_stop\_update\_action"></a>

### batch_stop_update_action

Stop the service update.

Type annotations for
`session.create_client("elasticache").batch_stop_update_action` method.

Boto3 documentation:
[ElastiCache.Client.batch_stop_update_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.batch_stop_update_action)

Asynchronous method. Use `await batch_stop_update_action(...)` for a
synchronous call.

Arguments mapping described in
[BatchStopUpdateActionMessageRequestTypeDef](./type_defs.md#batchstopupdateactionmessagerequesttypedef).

Keyword-only arguments:

- `ServiceUpdateName`: `str` *(required)*
- `ReplicationGroupIds`: `Sequence`\[`str`\]
- `CacheClusterIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[UpdateActionResultsMessageTypeDef](./type_defs.md#updateactionresultsmessagetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("elasticache").can_paginate`
method.

Boto3 documentation:
[ElastiCache.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="complete\_migration"></a>

### complete_migration

Complete the migration of data.

Type annotations for `session.create_client("elasticache").complete_migration`
method.

Boto3 documentation:
[ElastiCache.Client.complete_migration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.complete_migration)

Asynchronous method. Use `await complete_migration(...)` for a synchronous
call.

Arguments mapping described in
[CompleteMigrationMessageRequestTypeDef](./type_defs.md#completemigrationmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `Force`: `bool`

Returns a `Coroutine` for
[CompleteMigrationResponseTypeDef](./type_defs.md#completemigrationresponsetypedef).

<a id="copy\_snapshot"></a>

### copy_snapshot

Makes a copy of an existing snapshot.

Type annotations for `session.create_client("elasticache").copy_snapshot`
method.

Boto3 documentation:
[ElastiCache.Client.copy_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.copy_snapshot)

Asynchronous method. Use `await copy_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CopySnapshotMessageRequestTypeDef](./type_defs.md#copysnapshotmessagerequesttypedef).

Keyword-only arguments:

- `SourceSnapshotName`: `str` *(required)*
- `TargetSnapshotName`: `str` *(required)*
- `TargetBucket`: `str`
- `KmsKeyId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CopySnapshotResultTypeDef](./type_defs.md#copysnapshotresulttypedef).

<a id="create\_cache\_cluster"></a>

### create_cache_cluster

Creates a cluster.

Type annotations for
`session.create_client("elasticache").create_cache_cluster` method.

Boto3 documentation:
[ElastiCache.Client.create_cache_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_cache_cluster)

Asynchronous method. Use `await create_cache_cluster(...)` for a synchronous
call.

Arguments mapping described in
[CreateCacheClusterMessageRequestTypeDef](./type_defs.md#createcacheclustermessagerequesttypedef).

Keyword-only arguments:

- `CacheClusterId`: `str` *(required)*
- `ReplicationGroupId`: `str`
- `AZMode`: [AZModeType](./literals.md#azmodetype)
- `PreferredAvailabilityZone`: `str`
- `PreferredAvailabilityZones`: `Sequence`\[`str`\]
- `NumCacheNodes`: `int`
- `CacheNodeType`: `str`
- `Engine`: `str`
- `EngineVersion`: `str`
- `CacheParameterGroupName`: `str`
- `CacheSubnetGroupName`: `str`
- `CacheSecurityGroupNames`: `Sequence`\[`str`\]
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `SnapshotArns`: `Sequence`\[`str`\]
- `SnapshotName`: `str`
- `PreferredMaintenanceWindow`: `str`
- `Port`: `int`
- `NotificationTopicArn`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `SnapshotRetentionLimit`: `int`
- `SnapshotWindow`: `str`
- `AuthToken`: `str`
- `OutpostMode`: [OutpostModeType](./literals.md#outpostmodetype)
- `PreferredOutpostArn`: `str`
- `PreferredOutpostArns`: `Sequence`\[`str`\]
- `LogDeliveryConfigurations`:
  `Sequence`\[[LogDeliveryConfigurationRequestTypeDef](./type_defs.md#logdeliveryconfigurationrequesttypedef)\]

Returns a `Coroutine` for
[CreateCacheClusterResultTypeDef](./type_defs.md#createcacheclusterresulttypedef).

<a id="create\_cache\_parameter\_group"></a>

### create_cache_parameter_group

Creates a new Amazon ElastiCache cache parameter group.

Type annotations for
`session.create_client("elasticache").create_cache_parameter_group` method.

Boto3 documentation:
[ElastiCache.Client.create_cache_parameter_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_cache_parameter_group)

Asynchronous method. Use `await create_cache_parameter_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateCacheParameterGroupMessageRequestTypeDef](./type_defs.md#createcacheparametergroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheParameterGroupName`: `str` *(required)*
- `CacheParameterGroupFamily`: `str` *(required)*
- `Description`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateCacheParameterGroupResultTypeDef](./type_defs.md#createcacheparametergroupresulttypedef).

<a id="create\_cache\_security\_group"></a>

### create_cache_security_group

Creates a new cache security group.

Type annotations for
`session.create_client("elasticache").create_cache_security_group` method.

Boto3 documentation:
[ElastiCache.Client.create_cache_security_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_cache_security_group)

Asynchronous method. Use `await create_cache_security_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateCacheSecurityGroupMessageRequestTypeDef](./type_defs.md#createcachesecuritygroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheSecurityGroupName`: `str` *(required)*
- `Description`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateCacheSecurityGroupResultTypeDef](./type_defs.md#createcachesecuritygroupresulttypedef).

<a id="create\_cache\_subnet\_group"></a>

### create_cache_subnet_group

Creates a new cache subnet group.

Type annotations for
`session.create_client("elasticache").create_cache_subnet_group` method.

Boto3 documentation:
[ElastiCache.Client.create_cache_subnet_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_cache_subnet_group)

Asynchronous method. Use `await create_cache_subnet_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateCacheSubnetGroupMessageRequestTypeDef](./type_defs.md#createcachesubnetgroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheSubnetGroupName`: `str` *(required)*
- `CacheSubnetGroupDescription`: `str` *(required)*
- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateCacheSubnetGroupResultTypeDef](./type_defs.md#createcachesubnetgroupresulttypedef).

<a id="create\_global\_replication\_group"></a>

### create_global_replication_group

Global Datastore for Redis offers fully managed, fast, reliable and secure
cross-region replication.

Type annotations for
`session.create_client("elasticache").create_global_replication_group` method.

Boto3 documentation:
[ElastiCache.Client.create_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_global_replication_group)

Asynchronous method. Use `await create_global_replication_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#createglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupIdSuffix`: `str` *(required)*
- `PrimaryReplicationGroupId`: `str` *(required)*
- `GlobalReplicationGroupDescription`: `str`

Returns a `Coroutine` for
[CreateGlobalReplicationGroupResultTypeDef](./type_defs.md#createglobalreplicationgroupresulttypedef).

<a id="create\_replication\_group"></a>

### create_replication_group

Creates a Redis (cluster mode disabled) or a Redis (cluster mode enabled)
replication group.

Type annotations for
`session.create_client("elasticache").create_replication_group` method.

Boto3 documentation:
[ElastiCache.Client.create_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_replication_group)

Asynchronous method. Use `await create_replication_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateReplicationGroupMessageRequestTypeDef](./type_defs.md#createreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `ReplicationGroupDescription`: `str` *(required)*
- `GlobalReplicationGroupId`: `str`
- `PrimaryClusterId`: `str`
- `AutomaticFailoverEnabled`: `bool`
- `MultiAZEnabled`: `bool`
- `NumCacheClusters`: `int`
- `PreferredCacheClusterAZs`: `Sequence`\[`str`\]
- `NumNodeGroups`: `int`
- `ReplicasPerNodeGroup`: `int`
- `NodeGroupConfiguration`:
  `Sequence`\[[NodeGroupConfigurationTypeDef](./type_defs.md#nodegroupconfigurationtypedef)\]
- `CacheNodeType`: `str`
- `Engine`: `str`
- `EngineVersion`: `str`
- `CacheParameterGroupName`: `str`
- `CacheSubnetGroupName`: `str`
- `CacheSecurityGroupNames`: `Sequence`\[`str`\]
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `SnapshotArns`: `Sequence`\[`str`\]
- `SnapshotName`: `str`
- `PreferredMaintenanceWindow`: `str`
- `Port`: `int`
- `NotificationTopicArn`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `SnapshotRetentionLimit`: `int`
- `SnapshotWindow`: `str`
- `AuthToken`: `str`
- `TransitEncryptionEnabled`: `bool`
- `AtRestEncryptionEnabled`: `bool`
- `KmsKeyId`: `str`
- `UserGroupIds`: `Sequence`\[`str`\]
- `LogDeliveryConfigurations`:
  `Sequence`\[[LogDeliveryConfigurationRequestTypeDef](./type_defs.md#logdeliveryconfigurationrequesttypedef)\]
- `DataTieringEnabled`: `bool`

Returns a `Coroutine` for
[CreateReplicationGroupResultTypeDef](./type_defs.md#createreplicationgroupresulttypedef).

<a id="create\_snapshot"></a>

### create_snapshot

Creates a copy of an entire cluster or replication group at a specific moment
in time.

Type annotations for `session.create_client("elasticache").create_snapshot`
method.

Boto3 documentation:
[ElastiCache.Client.create_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_snapshot)

Asynchronous method. Use `await create_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CreateSnapshotMessageRequestTypeDef](./type_defs.md#createsnapshotmessagerequesttypedef).

Keyword-only arguments:

- `SnapshotName`: `str` *(required)*
- `ReplicationGroupId`: `str`
- `CacheClusterId`: `str`
- `KmsKeyId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateSnapshotResultTypeDef](./type_defs.md#createsnapshotresulttypedef).

<a id="create\_user"></a>

### create_user

For Redis engine version 6.0 onwards: Creates a Redis user.

Type annotations for `session.create_client("elasticache").create_user` method.

Boto3 documentation:
[ElastiCache.Client.create_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_user)

Asynchronous method. Use `await create_user(...)` for a synchronous call.

Arguments mapping described in
[CreateUserMessageRequestTypeDef](./type_defs.md#createusermessagerequesttypedef).

Keyword-only arguments:

- `UserId`: `str` *(required)*
- `UserName`: `str` *(required)*
- `Engine`: `str` *(required)*
- `AccessString`: `str` *(required)*
- `Passwords`: `Sequence`\[`str`\]
- `NoPasswordRequired`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[UserResponseMetadataTypeDef](./type_defs.md#userresponsemetadatatypedef).

<a id="create\_user\_group"></a>

### create_user_group

For Redis engine version 6.0 onwards: Creates a Redis user group.

Type annotations for `session.create_client("elasticache").create_user_group`
method.

Boto3 documentation:
[ElastiCache.Client.create_user_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_user_group)

Asynchronous method. Use `await create_user_group(...)` for a synchronous call.

Arguments mapping described in
[CreateUserGroupMessageRequestTypeDef](./type_defs.md#createusergroupmessagerequesttypedef).

Keyword-only arguments:

- `UserGroupId`: `str` *(required)*
- `Engine`: `str` *(required)*
- `UserIds`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[UserGroupResponseMetadataTypeDef](./type_defs.md#usergroupresponsemetadatatypedef).

<a id="decrease\_node\_groups\_in\_global\_replication\_group"></a>

### decrease_node_groups_in_global_replication_group

Decreases the number of node groups in a Global datastore See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/elasticache-2015-02-02/DecreaseNodeGroupsInGlobalReplicationGroup).

Type annotations for
`session.create_client("elasticache").decrease_node_groups_in_global_replication_group`
method.

Boto3 documentation:
[ElastiCache.Client.decrease_node_groups_in_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.decrease_node_groups_in_global_replication_group)

Asynchronous method. Use
`await decrease_node_groups_in_global_replication_group(...)` for a synchronous
call.

Arguments mapping described in
[DecreaseNodeGroupsInGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#decreasenodegroupsinglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str` *(required)*
- `NodeGroupCount`: `int` *(required)*
- `ApplyImmediately`: `bool` *(required)*
- `GlobalNodeGroupsToRemove`: `Sequence`\[`str`\]
- `GlobalNodeGroupsToRetain`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DecreaseNodeGroupsInGlobalReplicationGroupResultTypeDef](./type_defs.md#decreasenodegroupsinglobalreplicationgroupresulttypedef).

<a id="decrease\_replica\_count"></a>

### decrease_replica_count

Dynamically decreases the number of replicas in a Redis (cluster mode disabled)
replication group or the number of replica nodes in one or more node groups
(shards) of a Redis (cluster mode enabled) replication group.

Type annotations for
`session.create_client("elasticache").decrease_replica_count` method.

Boto3 documentation:
[ElastiCache.Client.decrease_replica_count](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.decrease_replica_count)

Asynchronous method. Use `await decrease_replica_count(...)` for a synchronous
call.

Arguments mapping described in
[DecreaseReplicaCountMessageRequestTypeDef](./type_defs.md#decreasereplicacountmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `ApplyImmediately`: `bool` *(required)*
- `NewReplicaCount`: `int`
- `ReplicaConfiguration`:
  `Sequence`\[[ConfigureShardTypeDef](./type_defs.md#configureshardtypedef)\]
- `ReplicasToRemove`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DecreaseReplicaCountResultTypeDef](./type_defs.md#decreasereplicacountresulttypedef).

<a id="delete\_cache\_cluster"></a>

### delete_cache_cluster

Deletes a previously provisioned cluster.

Type annotations for
`session.create_client("elasticache").delete_cache_cluster` method.

Boto3 documentation:
[ElastiCache.Client.delete_cache_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_cache_cluster)

Asynchronous method. Use `await delete_cache_cluster(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCacheClusterMessageRequestTypeDef](./type_defs.md#deletecacheclustermessagerequesttypedef).

Keyword-only arguments:

- `CacheClusterId`: `str` *(required)*
- `FinalSnapshotIdentifier`: `str`

Returns a `Coroutine` for
[DeleteCacheClusterResultTypeDef](./type_defs.md#deletecacheclusterresulttypedef).

<a id="delete\_cache\_parameter\_group"></a>

### delete_cache_parameter_group

Deletes the specified cache parameter group.

Type annotations for
`session.create_client("elasticache").delete_cache_parameter_group` method.

Boto3 documentation:
[ElastiCache.Client.delete_cache_parameter_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_cache_parameter_group)

Asynchronous method. Use `await delete_cache_parameter_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCacheParameterGroupMessageRequestTypeDef](./type_defs.md#deletecacheparametergroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheParameterGroupName`: `str` *(required)*

<a id="delete\_cache\_security\_group"></a>

### delete_cache_security_group

Deletes a cache security group.

Type annotations for
`session.create_client("elasticache").delete_cache_security_group` method.

Boto3 documentation:
[ElastiCache.Client.delete_cache_security_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_cache_security_group)

Asynchronous method. Use `await delete_cache_security_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCacheSecurityGroupMessageRequestTypeDef](./type_defs.md#deletecachesecuritygroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheSecurityGroupName`: `str` *(required)*

<a id="delete\_cache\_subnet\_group"></a>

### delete_cache_subnet_group

Deletes a cache subnet group.

Type annotations for
`session.create_client("elasticache").delete_cache_subnet_group` method.

Boto3 documentation:
[ElastiCache.Client.delete_cache_subnet_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_cache_subnet_group)

Asynchronous method. Use `await delete_cache_subnet_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCacheSubnetGroupMessageRequestTypeDef](./type_defs.md#deletecachesubnetgroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheSubnetGroupName`: `str` *(required)*

<a id="delete\_global\_replication\_group"></a>

### delete_global_replication_group

Deleting a Global datastore is a two-step process * First, you must
DisassociateGlobalReplicationGroup to remove the secondary clusters in the
Global datastore.

Type annotations for
`session.create_client("elasticache").delete_global_replication_group` method.

Boto3 documentation:
[ElastiCache.Client.delete_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_global_replication_group)

Asynchronous method. Use `await delete_global_replication_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#deleteglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str` *(required)*
- `RetainPrimaryReplicationGroup`: `bool` *(required)*

Returns a `Coroutine` for
[DeleteGlobalReplicationGroupResultTypeDef](./type_defs.md#deleteglobalreplicationgroupresulttypedef).

<a id="delete\_replication\_group"></a>

### delete_replication_group

Deletes an existing replication group.

Type annotations for
`session.create_client("elasticache").delete_replication_group` method.

Boto3 documentation:
[ElastiCache.Client.delete_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_replication_group)

Asynchronous method. Use `await delete_replication_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteReplicationGroupMessageRequestTypeDef](./type_defs.md#deletereplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `RetainPrimaryCluster`: `bool`
- `FinalSnapshotIdentifier`: `str`

Returns a `Coroutine` for
[DeleteReplicationGroupResultTypeDef](./type_defs.md#deletereplicationgroupresulttypedef).

<a id="delete\_snapshot"></a>

### delete_snapshot

Deletes an existing snapshot.

Type annotations for `session.create_client("elasticache").delete_snapshot`
method.

Boto3 documentation:
[ElastiCache.Client.delete_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_snapshot)

Asynchronous method. Use `await delete_snapshot(...)` for a synchronous call.

Arguments mapping described in
[DeleteSnapshotMessageRequestTypeDef](./type_defs.md#deletesnapshotmessagerequesttypedef).

Keyword-only arguments:

- `SnapshotName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteSnapshotResultTypeDef](./type_defs.md#deletesnapshotresulttypedef).

<a id="delete\_user"></a>

### delete_user

For Redis engine version 6.0 onwards: Deletes a user.

Type annotations for `session.create_client("elasticache").delete_user` method.

Boto3 documentation:
[ElastiCache.Client.delete_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_user)

Asynchronous method. Use `await delete_user(...)` for a synchronous call.

Arguments mapping described in
[DeleteUserMessageRequestTypeDef](./type_defs.md#deleteusermessagerequesttypedef).

Keyword-only arguments:

- `UserId`: `str` *(required)*

Returns a `Coroutine` for
[UserResponseMetadataTypeDef](./type_defs.md#userresponsemetadatatypedef).

<a id="delete\_user\_group"></a>

### delete_user_group

For Redis engine version 6.0 onwards: Deletes a user group.

Type annotations for `session.create_client("elasticache").delete_user_group`
method.

Boto3 documentation:
[ElastiCache.Client.delete_user_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_user_group)

Asynchronous method. Use `await delete_user_group(...)` for a synchronous call.

Arguments mapping described in
[DeleteUserGroupMessageRequestTypeDef](./type_defs.md#deleteusergroupmessagerequesttypedef).

Keyword-only arguments:

- `UserGroupId`: `str` *(required)*

Returns a `Coroutine` for
[UserGroupResponseMetadataTypeDef](./type_defs.md#usergroupresponsemetadatatypedef).

<a id="describe\_cache\_clusters"></a>

### describe_cache_clusters

Returns information about all provisioned clusters if no cluster identifier is
specified, or about a specific cache cluster if a cluster identifier is
supplied.

Type annotations for
`session.create_client("elasticache").describe_cache_clusters` method.

Boto3 documentation:
[ElastiCache.Client.describe_cache_clusters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_cache_clusters)

Asynchronous method. Use `await describe_cache_clusters(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCacheClustersMessageRequestTypeDef](./type_defs.md#describecacheclustersmessagerequesttypedef).

Keyword-only arguments:

- `CacheClusterId`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`
- `ShowCacheNodeInfo`: `bool`
- `ShowCacheClustersNotInReplicationGroups`: `bool`

Returns a `Coroutine` for
[CacheClusterMessageTypeDef](./type_defs.md#cacheclustermessagetypedef).

<a id="describe\_cache\_engine\_versions"></a>

### describe_cache_engine_versions

Returns a list of the available cache engines and their versions.

Type annotations for
`session.create_client("elasticache").describe_cache_engine_versions` method.

Boto3 documentation:
[ElastiCache.Client.describe_cache_engine_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_cache_engine_versions)

Asynchronous method. Use `await describe_cache_engine_versions(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCacheEngineVersionsMessageRequestTypeDef](./type_defs.md#describecacheengineversionsmessagerequesttypedef).

Keyword-only arguments:

- `Engine`: `str`
- `EngineVersion`: `str`
- `CacheParameterGroupFamily`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`
- `DefaultOnly`: `bool`

Returns a `Coroutine` for
[CacheEngineVersionMessageTypeDef](./type_defs.md#cacheengineversionmessagetypedef).

<a id="describe\_cache\_parameter\_groups"></a>

### describe_cache_parameter_groups

Returns a list of cache parameter group descriptions.

Type annotations for
`session.create_client("elasticache").describe_cache_parameter_groups` method.

Boto3 documentation:
[ElastiCache.Client.describe_cache_parameter_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_cache_parameter_groups)

Asynchronous method. Use `await describe_cache_parameter_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCacheParameterGroupsMessageRequestTypeDef](./type_defs.md#describecacheparametergroupsmessagerequesttypedef).

Keyword-only arguments:

- `CacheParameterGroupName`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[CacheParameterGroupsMessageTypeDef](./type_defs.md#cacheparametergroupsmessagetypedef).

<a id="describe\_cache\_parameters"></a>

### describe_cache_parameters

Returns the detailed parameter list for a particular cache parameter group.

Type annotations for
`session.create_client("elasticache").describe_cache_parameters` method.

Boto3 documentation:
[ElastiCache.Client.describe_cache_parameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_cache_parameters)

Asynchronous method. Use `await describe_cache_parameters(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCacheParametersMessageRequestTypeDef](./type_defs.md#describecacheparametersmessagerequesttypedef).

Keyword-only arguments:

- `CacheParameterGroupName`: `str` *(required)*
- `Source`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[CacheParameterGroupDetailsTypeDef](./type_defs.md#cacheparametergroupdetailstypedef).

<a id="describe\_cache\_security\_groups"></a>

### describe_cache_security_groups

Returns a list of cache security group descriptions.

Type annotations for
`session.create_client("elasticache").describe_cache_security_groups` method.

Boto3 documentation:
[ElastiCache.Client.describe_cache_security_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_cache_security_groups)

Asynchronous method. Use `await describe_cache_security_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCacheSecurityGroupsMessageRequestTypeDef](./type_defs.md#describecachesecuritygroupsmessagerequesttypedef).

Keyword-only arguments:

- `CacheSecurityGroupName`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[CacheSecurityGroupMessageTypeDef](./type_defs.md#cachesecuritygroupmessagetypedef).

<a id="describe\_cache\_subnet\_groups"></a>

### describe_cache_subnet_groups

Returns a list of cache subnet group descriptions.

Type annotations for
`session.create_client("elasticache").describe_cache_subnet_groups` method.

Boto3 documentation:
[ElastiCache.Client.describe_cache_subnet_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_cache_subnet_groups)

Asynchronous method. Use `await describe_cache_subnet_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCacheSubnetGroupsMessageRequestTypeDef](./type_defs.md#describecachesubnetgroupsmessagerequesttypedef).

Keyword-only arguments:

- `CacheSubnetGroupName`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[CacheSubnetGroupMessageTypeDef](./type_defs.md#cachesubnetgroupmessagetypedef).

<a id="describe\_engine\_default\_parameters"></a>

### describe_engine_default_parameters

Returns the default engine and system parameter information for the specified
cache engine.

Type annotations for
`session.create_client("elasticache").describe_engine_default_parameters`
method.

Boto3 documentation:
[ElastiCache.Client.describe_engine_default_parameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_engine_default_parameters)

Asynchronous method. Use `await describe_engine_default_parameters(...)` for a
synchronous call.

Arguments mapping described in
[DescribeEngineDefaultParametersMessageRequestTypeDef](./type_defs.md#describeenginedefaultparametersmessagerequesttypedef).

Keyword-only arguments:

- `CacheParameterGroupFamily`: `str` *(required)*
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeEngineDefaultParametersResultTypeDef](./type_defs.md#describeenginedefaultparametersresulttypedef).

<a id="describe\_events"></a>

### describe_events

Returns events related to clusters, cache security groups, and cache parameter
groups.

Type annotations for `session.create_client("elasticache").describe_events`
method.

Boto3 documentation:
[ElastiCache.Client.describe_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_events)

Asynchronous method. Use `await describe_events(...)` for a synchronous call.

Arguments mapping described in
[DescribeEventsMessageRequestTypeDef](./type_defs.md#describeeventsmessagerequesttypedef).

Keyword-only arguments:

- `SourceIdentifier`: `str`
- `SourceType`: [SourceTypeType](./literals.md#sourcetypetype)
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `Duration`: `int`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[EventsMessageTypeDef](./type_defs.md#eventsmessagetypedef).

<a id="describe\_global\_replication\_groups"></a>

### describe_global_replication_groups

Returns information about a particular global replication group.

Type annotations for
`session.create_client("elasticache").describe_global_replication_groups`
method.

Boto3 documentation:
[ElastiCache.Client.describe_global_replication_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_global_replication_groups)

Asynchronous method. Use `await describe_global_replication_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeGlobalReplicationGroupsMessageRequestTypeDef](./type_defs.md#describeglobalreplicationgroupsmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`
- `ShowMemberInfo`: `bool`

Returns a `Coroutine` for
[DescribeGlobalReplicationGroupsResultTypeDef](./type_defs.md#describeglobalreplicationgroupsresulttypedef).

<a id="describe\_replication\_groups"></a>

### describe_replication_groups

Returns information about a particular replication group.

Type annotations for
`session.create_client("elasticache").describe_replication_groups` method.

Boto3 documentation:
[ElastiCache.Client.describe_replication_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_replication_groups)

Asynchronous method. Use `await describe_replication_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeReplicationGroupsMessageRequestTypeDef](./type_defs.md#describereplicationgroupsmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ReplicationGroupMessageTypeDef](./type_defs.md#replicationgroupmessagetypedef).

<a id="describe\_reserved\_cache\_nodes"></a>

### describe_reserved_cache_nodes

Returns information about reserved cache nodes for this account, or about a
specified reserved cache node.

Type annotations for
`session.create_client("elasticache").describe_reserved_cache_nodes` method.

Boto3 documentation:
[ElastiCache.Client.describe_reserved_cache_nodes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_reserved_cache_nodes)

Asynchronous method. Use `await describe_reserved_cache_nodes(...)` for a
synchronous call.

Arguments mapping described in
[DescribeReservedCacheNodesMessageRequestTypeDef](./type_defs.md#describereservedcachenodesmessagerequesttypedef).

Keyword-only arguments:

- `ReservedCacheNodeId`: `str`
- `ReservedCacheNodesOfferingId`: `str`
- `CacheNodeType`: `str`
- `Duration`: `str`
- `ProductDescription`: `str`
- `OfferingType`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ReservedCacheNodeMessageTypeDef](./type_defs.md#reservedcachenodemessagetypedef).

<a id="describe\_reserved\_cache\_nodes\_offerings"></a>

### describe_reserved_cache_nodes_offerings

Lists available reserved cache node offerings.

Type annotations for
`session.create_client("elasticache").describe_reserved_cache_nodes_offerings`
method.

Boto3 documentation:
[ElastiCache.Client.describe_reserved_cache_nodes_offerings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_reserved_cache_nodes_offerings)

Asynchronous method. Use `await describe_reserved_cache_nodes_offerings(...)`
for a synchronous call.

Arguments mapping described in
[DescribeReservedCacheNodesOfferingsMessageRequestTypeDef](./type_defs.md#describereservedcachenodesofferingsmessagerequesttypedef).

Keyword-only arguments:

- `ReservedCacheNodesOfferingId`: `str`
- `CacheNodeType`: `str`
- `Duration`: `str`
- `ProductDescription`: `str`
- `OfferingType`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ReservedCacheNodesOfferingMessageTypeDef](./type_defs.md#reservedcachenodesofferingmessagetypedef).

<a id="describe\_service\_updates"></a>

### describe_service_updates

Returns details of the service updates See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/elasticache-2015-02-02/DescribeServiceUpdates).

Type annotations for
`session.create_client("elasticache").describe_service_updates` method.

Boto3 documentation:
[ElastiCache.Client.describe_service_updates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_service_updates)

Asynchronous method. Use `await describe_service_updates(...)` for a
synchronous call.

Arguments mapping described in
[DescribeServiceUpdatesMessageRequestTypeDef](./type_defs.md#describeserviceupdatesmessagerequesttypedef).

Keyword-only arguments:

- `ServiceUpdateName`: `str`
- `ServiceUpdateStatus`:
  `Sequence`\[[ServiceUpdateStatusType](./literals.md#serviceupdatestatustype)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ServiceUpdatesMessageTypeDef](./type_defs.md#serviceupdatesmessagetypedef).

<a id="describe\_snapshots"></a>

### describe_snapshots

Returns information about cluster or replication group snapshots.

Type annotations for `session.create_client("elasticache").describe_snapshots`
method.

Boto3 documentation:
[ElastiCache.Client.describe_snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_snapshots)

Asynchronous method. Use `await describe_snapshots(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSnapshotsMessageRequestTypeDef](./type_defs.md#describesnapshotsmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str`
- `CacheClusterId`: `str`
- `SnapshotName`: `str`
- `SnapshotSource`: `str`
- `Marker`: `str`
- `MaxRecords`: `int`
- `ShowNodeGroupConfig`: `bool`

Returns a `Coroutine` for
[DescribeSnapshotsListMessageTypeDef](./type_defs.md#describesnapshotslistmessagetypedef).

<a id="describe\_update\_actions"></a>

### describe_update_actions

Returns details of the update actions See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/elasticache-2015-02-02/DescribeUpdateActions).

Type annotations for
`session.create_client("elasticache").describe_update_actions` method.

Boto3 documentation:
[ElastiCache.Client.describe_update_actions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_update_actions)

Asynchronous method. Use `await describe_update_actions(...)` for a synchronous
call.

Arguments mapping described in
[DescribeUpdateActionsMessageRequestTypeDef](./type_defs.md#describeupdateactionsmessagerequesttypedef).

Keyword-only arguments:

- `ServiceUpdateName`: `str`
- `ReplicationGroupIds`: `Sequence`\[`str`\]
- `CacheClusterIds`: `Sequence`\[`str`\]
- `Engine`: `str`
- `ServiceUpdateStatus`:
  `Sequence`\[[ServiceUpdateStatusType](./literals.md#serviceupdatestatustype)\]
- `ServiceUpdateTimeRange`:
  [TimeRangeFilterTypeDef](./type_defs.md#timerangefiltertypedef)
- `UpdateActionStatus`:
  `Sequence`\[[UpdateActionStatusType](./literals.md#updateactionstatustype)\]
- `ShowNodeLevelUpdateStatus`: `bool`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[UpdateActionsMessageTypeDef](./type_defs.md#updateactionsmessagetypedef).

<a id="describe\_user\_groups"></a>

### describe_user_groups

Returns a list of user groups.

Type annotations for
`session.create_client("elasticache").describe_user_groups` method.

Boto3 documentation:
[ElastiCache.Client.describe_user_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_user_groups)

Asynchronous method. Use `await describe_user_groups(...)` for a synchronous
call.

Arguments mapping described in
[DescribeUserGroupsMessageRequestTypeDef](./type_defs.md#describeusergroupsmessagerequesttypedef).

Keyword-only arguments:

- `UserGroupId`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeUserGroupsResultTypeDef](./type_defs.md#describeusergroupsresulttypedef).

<a id="describe\_users"></a>

### describe_users

Returns a list of users.

Type annotations for `session.create_client("elasticache").describe_users`
method.

Boto3 documentation:
[ElastiCache.Client.describe_users](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.describe_users)

Asynchronous method. Use `await describe_users(...)` for a synchronous call.

Arguments mapping described in
[DescribeUsersMessageRequestTypeDef](./type_defs.md#describeusersmessagerequesttypedef).

Keyword-only arguments:

- `Engine`: `str`
- `UserId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeUsersResultTypeDef](./type_defs.md#describeusersresulttypedef).

<a id="disassociate\_global\_replication\_group"></a>

### disassociate_global_replication_group

Remove a secondary cluster from the Global datastore using the Global datastore
name.

Type annotations for
`session.create_client("elasticache").disassociate_global_replication_group`
method.

Boto3 documentation:
[ElastiCache.Client.disassociate_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.disassociate_global_replication_group)

Asynchronous method. Use `await disassociate_global_replication_group(...)` for
a synchronous call.

Arguments mapping described in
[DisassociateGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#disassociateglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str` *(required)*
- `ReplicationGroupId`: `str` *(required)*
- `ReplicationGroupRegion`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateGlobalReplicationGroupResultTypeDef](./type_defs.md#disassociateglobalreplicationgroupresulttypedef).

<a id="failover\_global\_replication\_group"></a>

### failover_global_replication_group

Used to failover the primary region to a selected secondary region.

Type annotations for
`session.create_client("elasticache").failover_global_replication_group`
method.

Boto3 documentation:
[ElastiCache.Client.failover_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.failover_global_replication_group)

Asynchronous method. Use `await failover_global_replication_group(...)` for a
synchronous call.

Arguments mapping described in
[FailoverGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#failoverglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str` *(required)*
- `PrimaryRegion`: `str` *(required)*
- `PrimaryReplicationGroupId`: `str` *(required)*

Returns a `Coroutine` for
[FailoverGlobalReplicationGroupResultTypeDef](./type_defs.md#failoverglobalreplicationgroupresulttypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("elasticache").generate_presigned_url` method.

Boto3 documentation:
[ElastiCache.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="increase\_node\_groups\_in\_global\_replication\_group"></a>

### increase_node_groups_in_global_replication_group

Increase the number of node groups in the Global datastore See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/elasticache-2015-02-02/IncreaseNodeGroupsInGlobalReplicationGroup).

Type annotations for
`session.create_client("elasticache").increase_node_groups_in_global_replication_group`
method.

Boto3 documentation:
[ElastiCache.Client.increase_node_groups_in_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.increase_node_groups_in_global_replication_group)

Asynchronous method. Use
`await increase_node_groups_in_global_replication_group(...)` for a synchronous
call.

Arguments mapping described in
[IncreaseNodeGroupsInGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#increasenodegroupsinglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str` *(required)*
- `NodeGroupCount`: `int` *(required)*
- `ApplyImmediately`: `bool` *(required)*
- `RegionalConfigurations`:
  `Sequence`\[[RegionalConfigurationTypeDef](./type_defs.md#regionalconfigurationtypedef)\]

Returns a `Coroutine` for
[IncreaseNodeGroupsInGlobalReplicationGroupResultTypeDef](./type_defs.md#increasenodegroupsinglobalreplicationgroupresulttypedef).

<a id="increase\_replica\_count"></a>

### increase_replica_count

Dynamically increases the number of replicas in a Redis (cluster mode disabled)
replication group or the number of replica nodes in one or more node groups
(shards) of a Redis (cluster mode enabled) replication group.

Type annotations for
`session.create_client("elasticache").increase_replica_count` method.

Boto3 documentation:
[ElastiCache.Client.increase_replica_count](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.increase_replica_count)

Asynchronous method. Use `await increase_replica_count(...)` for a synchronous
call.

Arguments mapping described in
[IncreaseReplicaCountMessageRequestTypeDef](./type_defs.md#increasereplicacountmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `ApplyImmediately`: `bool` *(required)*
- `NewReplicaCount`: `int`
- `ReplicaConfiguration`:
  `Sequence`\[[ConfigureShardTypeDef](./type_defs.md#configureshardtypedef)\]

Returns a `Coroutine` for
[IncreaseReplicaCountResultTypeDef](./type_defs.md#increasereplicacountresulttypedef).

<a id="list\_allowed\_node\_type\_modifications"></a>

### list_allowed_node_type_modifications

Lists all available node types that you can scale your Redis cluster's or
replication group's current node type.

Type annotations for
`session.create_client("elasticache").list_allowed_node_type_modifications`
method.

Boto3 documentation:
[ElastiCache.Client.list_allowed_node_type_modifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.list_allowed_node_type_modifications)

Asynchronous method. Use `await list_allowed_node_type_modifications(...)` for
a synchronous call.

Arguments mapping described in
[ListAllowedNodeTypeModificationsMessageRequestTypeDef](./type_defs.md#listallowednodetypemodificationsmessagerequesttypedef).

Keyword-only arguments:

- `CacheClusterId`: `str`
- `ReplicationGroupId`: `str`

Returns a `Coroutine` for
[AllowedNodeTypeModificationsMessageTypeDef](./type_defs.md#allowednodetypemodificationsmessagetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Lists all tags currently on a named resource.

Type annotations for
`session.create_client("elasticache").list_tags_for_resource` method.

Boto3 documentation:
[ElastiCache.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceMessageRequestTypeDef](./type_defs.md#listtagsforresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceName`: `str` *(required)*

Returns a `Coroutine` for
[TagListMessageTypeDef](./type_defs.md#taglistmessagetypedef).

<a id="modify\_cache\_cluster"></a>

### modify_cache_cluster

Modifies the settings for a cluster.

Type annotations for
`session.create_client("elasticache").modify_cache_cluster` method.

Boto3 documentation:
[ElastiCache.Client.modify_cache_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_cache_cluster)

Asynchronous method. Use `await modify_cache_cluster(...)` for a synchronous
call.

Arguments mapping described in
[ModifyCacheClusterMessageRequestTypeDef](./type_defs.md#modifycacheclustermessagerequesttypedef).

Keyword-only arguments:

- `CacheClusterId`: `str` *(required)*
- `NumCacheNodes`: `int`
- `CacheNodeIdsToRemove`: `Sequence`\[`str`\]
- `AZMode`: [AZModeType](./literals.md#azmodetype)
- `NewAvailabilityZones`: `Sequence`\[`str`\]
- `CacheSecurityGroupNames`: `Sequence`\[`str`\]
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `PreferredMaintenanceWindow`: `str`
- `NotificationTopicArn`: `str`
- `CacheParameterGroupName`: `str`
- `NotificationTopicStatus`: `str`
- `ApplyImmediately`: `bool`
- `EngineVersion`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `SnapshotRetentionLimit`: `int`
- `SnapshotWindow`: `str`
- `CacheNodeType`: `str`
- `AuthToken`: `str`
- `AuthTokenUpdateStrategy`:
  [AuthTokenUpdateStrategyTypeType](./literals.md#authtokenupdatestrategytypetype)
- `LogDeliveryConfigurations`:
  `Sequence`\[[LogDeliveryConfigurationRequestTypeDef](./type_defs.md#logdeliveryconfigurationrequesttypedef)\]

Returns a `Coroutine` for
[ModifyCacheClusterResultTypeDef](./type_defs.md#modifycacheclusterresulttypedef).

<a id="modify\_cache\_parameter\_group"></a>

### modify_cache_parameter_group

Modifies the parameters of a cache parameter group.

Type annotations for
`session.create_client("elasticache").modify_cache_parameter_group` method.

Boto3 documentation:
[ElastiCache.Client.modify_cache_parameter_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_cache_parameter_group)

Asynchronous method. Use `await modify_cache_parameter_group(...)` for a
synchronous call.

Arguments mapping described in
[ModifyCacheParameterGroupMessageRequestTypeDef](./type_defs.md#modifycacheparametergroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheParameterGroupName`: `str` *(required)*
- `ParameterNameValues`:
  `Sequence`\[[ParameterNameValueTypeDef](./type_defs.md#parameternamevaluetypedef)\]
  *(required)*

Returns a `Coroutine` for
[CacheParameterGroupNameMessageTypeDef](./type_defs.md#cacheparametergroupnamemessagetypedef).

<a id="modify\_cache\_subnet\_group"></a>

### modify_cache_subnet_group

Modifies an existing cache subnet group.

Type annotations for
`session.create_client("elasticache").modify_cache_subnet_group` method.

Boto3 documentation:
[ElastiCache.Client.modify_cache_subnet_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_cache_subnet_group)

Asynchronous method. Use `await modify_cache_subnet_group(...)` for a
synchronous call.

Arguments mapping described in
[ModifyCacheSubnetGroupMessageRequestTypeDef](./type_defs.md#modifycachesubnetgroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheSubnetGroupName`: `str` *(required)*
- `CacheSubnetGroupDescription`: `str`
- `SubnetIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ModifyCacheSubnetGroupResultTypeDef](./type_defs.md#modifycachesubnetgroupresulttypedef).

<a id="modify\_global\_replication\_group"></a>

### modify_global_replication_group

Modifies the settings for a Global datastore.

Type annotations for
`session.create_client("elasticache").modify_global_replication_group` method.

Boto3 documentation:
[ElastiCache.Client.modify_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_global_replication_group)

Asynchronous method. Use `await modify_global_replication_group(...)` for a
synchronous call.

Arguments mapping described in
[ModifyGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#modifyglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str` *(required)*
- `ApplyImmediately`: `bool` *(required)*
- `CacheNodeType`: `str`
- `EngineVersion`: `str`
- `CacheParameterGroupName`: `str`
- `GlobalReplicationGroupDescription`: `str`
- `AutomaticFailoverEnabled`: `bool`

Returns a `Coroutine` for
[ModifyGlobalReplicationGroupResultTypeDef](./type_defs.md#modifyglobalreplicationgroupresulttypedef).

<a id="modify\_replication\_group"></a>

### modify_replication_group

Modifies the settings for a replication group.

Type annotations for
`session.create_client("elasticache").modify_replication_group` method.

Boto3 documentation:
[ElastiCache.Client.modify_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_replication_group)

Asynchronous method. Use `await modify_replication_group(...)` for a
synchronous call.

Arguments mapping described in
[ModifyReplicationGroupMessageRequestTypeDef](./type_defs.md#modifyreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `ReplicationGroupDescription`: `str`
- `PrimaryClusterId`: `str`
- `SnapshottingClusterId`: `str`
- `AutomaticFailoverEnabled`: `bool`
- `MultiAZEnabled`: `bool`
- `NodeGroupId`: `str`
- `CacheSecurityGroupNames`: `Sequence`\[`str`\]
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `PreferredMaintenanceWindow`: `str`
- `NotificationTopicArn`: `str`
- `CacheParameterGroupName`: `str`
- `NotificationTopicStatus`: `str`
- `ApplyImmediately`: `bool`
- `EngineVersion`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `SnapshotRetentionLimit`: `int`
- `SnapshotWindow`: `str`
- `CacheNodeType`: `str`
- `AuthToken`: `str`
- `AuthTokenUpdateStrategy`:
  [AuthTokenUpdateStrategyTypeType](./literals.md#authtokenupdatestrategytypetype)
- `UserGroupIdsToAdd`: `Sequence`\[`str`\]
- `UserGroupIdsToRemove`: `Sequence`\[`str`\]
- `RemoveUserGroups`: `bool`
- `LogDeliveryConfigurations`:
  `Sequence`\[[LogDeliveryConfigurationRequestTypeDef](./type_defs.md#logdeliveryconfigurationrequesttypedef)\]

Returns a `Coroutine` for
[ModifyReplicationGroupResultTypeDef](./type_defs.md#modifyreplicationgroupresulttypedef).

<a id="modify\_replication\_group\_shard\_configuration"></a>

### modify_replication_group_shard_configuration

Modifies a replication group's shards (node groups) by allowing you to add
shards, remove shards, or rebalance the keyspaces among existing shards.

Type annotations for
`session.create_client("elasticache").modify_replication_group_shard_configuration`
method.

Boto3 documentation:
[ElastiCache.Client.modify_replication_group_shard_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_replication_group_shard_configuration)

Asynchronous method. Use
`await modify_replication_group_shard_configuration(...)` for a synchronous
call.

Arguments mapping described in
[ModifyReplicationGroupShardConfigurationMessageRequestTypeDef](./type_defs.md#modifyreplicationgroupshardconfigurationmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `NodeGroupCount`: `int` *(required)*
- `ApplyImmediately`: `bool` *(required)*
- `ReshardingConfiguration`:
  `Sequence`\[[ReshardingConfigurationTypeDef](./type_defs.md#reshardingconfigurationtypedef)\]
- `NodeGroupsToRemove`: `Sequence`\[`str`\]
- `NodeGroupsToRetain`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ModifyReplicationGroupShardConfigurationResultTypeDef](./type_defs.md#modifyreplicationgroupshardconfigurationresulttypedef).

<a id="modify\_user"></a>

### modify_user

Changes user password(s) and/or access string.

Type annotations for `session.create_client("elasticache").modify_user` method.

Boto3 documentation:
[ElastiCache.Client.modify_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_user)

Asynchronous method. Use `await modify_user(...)` for a synchronous call.

Arguments mapping described in
[ModifyUserMessageRequestTypeDef](./type_defs.md#modifyusermessagerequesttypedef).

Keyword-only arguments:

- `UserId`: `str` *(required)*
- `AccessString`: `str`
- `AppendAccessString`: `str`
- `Passwords`: `Sequence`\[`str`\]
- `NoPasswordRequired`: `bool`

Returns a `Coroutine` for
[UserResponseMetadataTypeDef](./type_defs.md#userresponsemetadatatypedef).

<a id="modify\_user\_group"></a>

### modify_user_group

Changes the list of users that belong to the user group.

Type annotations for `session.create_client("elasticache").modify_user_group`
method.

Boto3 documentation:
[ElastiCache.Client.modify_user_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_user_group)

Asynchronous method. Use `await modify_user_group(...)` for a synchronous call.

Arguments mapping described in
[ModifyUserGroupMessageRequestTypeDef](./type_defs.md#modifyusergroupmessagerequesttypedef).

Keyword-only arguments:

- `UserGroupId`: `str` *(required)*
- `UserIdsToAdd`: `Sequence`\[`str`\]
- `UserIdsToRemove`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[UserGroupResponseMetadataTypeDef](./type_defs.md#usergroupresponsemetadatatypedef).

<a id="purchase\_reserved\_cache\_nodes\_offering"></a>

### purchase_reserved_cache_nodes_offering

Allows you to purchase a reserved cache node offering.

Type annotations for
`session.create_client("elasticache").purchase_reserved_cache_nodes_offering`
method.

Boto3 documentation:
[ElastiCache.Client.purchase_reserved_cache_nodes_offering](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.purchase_reserved_cache_nodes_offering)

Asynchronous method. Use `await purchase_reserved_cache_nodes_offering(...)`
for a synchronous call.

Arguments mapping described in
[PurchaseReservedCacheNodesOfferingMessageRequestTypeDef](./type_defs.md#purchasereservedcachenodesofferingmessagerequesttypedef).

Keyword-only arguments:

- `ReservedCacheNodesOfferingId`: `str` *(required)*
- `ReservedCacheNodeId`: `str`
- `CacheNodeCount`: `int`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[PurchaseReservedCacheNodesOfferingResultTypeDef](./type_defs.md#purchasereservedcachenodesofferingresulttypedef).

<a id="rebalance\_slots\_in\_global\_replication\_group"></a>

### rebalance_slots_in_global_replication_group

Redistribute slots to ensure uniform distribution across existing shards in the
cluster.

Type annotations for
`session.create_client("elasticache").rebalance_slots_in_global_replication_group`
method.

Boto3 documentation:
[ElastiCache.Client.rebalance_slots_in_global_replication_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.rebalance_slots_in_global_replication_group)

Asynchronous method. Use
`await rebalance_slots_in_global_replication_group(...)` for a synchronous
call.

Arguments mapping described in
[RebalanceSlotsInGlobalReplicationGroupMessageRequestTypeDef](./type_defs.md#rebalanceslotsinglobalreplicationgroupmessagerequesttypedef).

Keyword-only arguments:

- `GlobalReplicationGroupId`: `str` *(required)*
- `ApplyImmediately`: `bool` *(required)*

Returns a `Coroutine` for
[RebalanceSlotsInGlobalReplicationGroupResultTypeDef](./type_defs.md#rebalanceslotsinglobalreplicationgroupresulttypedef).

<a id="reboot\_cache\_cluster"></a>

### reboot_cache_cluster

Reboots some, or all, of the cache nodes within a provisioned cluster.

Type annotations for
`session.create_client("elasticache").reboot_cache_cluster` method.

Boto3 documentation:
[ElastiCache.Client.reboot_cache_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.reboot_cache_cluster)

Asynchronous method. Use `await reboot_cache_cluster(...)` for a synchronous
call.

Arguments mapping described in
[RebootCacheClusterMessageRequestTypeDef](./type_defs.md#rebootcacheclustermessagerequesttypedef).

Keyword-only arguments:

- `CacheClusterId`: `str` *(required)*
- `CacheNodeIdsToReboot`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[RebootCacheClusterResultTypeDef](./type_defs.md#rebootcacheclusterresulttypedef).

<a id="remove\_tags\_from\_resource"></a>

### remove_tags_from_resource

Removes the tags identified by the `TagKeys` list from the named resource.

Type annotations for
`session.create_client("elasticache").remove_tags_from_resource` method.

Boto3 documentation:
[ElastiCache.Client.remove_tags_from_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.remove_tags_from_resource)

Asynchronous method. Use `await remove_tags_from_resource(...)` for a
synchronous call.

Arguments mapping described in
[RemoveTagsFromResourceMessageRequestTypeDef](./type_defs.md#removetagsfromresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceName`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[TagListMessageTypeDef](./type_defs.md#taglistmessagetypedef).

<a id="reset\_cache\_parameter\_group"></a>

### reset_cache_parameter_group

Modifies the parameters of a cache parameter group to the engine or system
default value.

Type annotations for
`session.create_client("elasticache").reset_cache_parameter_group` method.

Boto3 documentation:
[ElastiCache.Client.reset_cache_parameter_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.reset_cache_parameter_group)

Asynchronous method. Use `await reset_cache_parameter_group(...)` for a
synchronous call.

Arguments mapping described in
[ResetCacheParameterGroupMessageRequestTypeDef](./type_defs.md#resetcacheparametergroupmessagerequesttypedef).

Keyword-only arguments:

- `CacheParameterGroupName`: `str` *(required)*
- `ResetAllParameters`: `bool`
- `ParameterNameValues`:
  `Sequence`\[[ParameterNameValueTypeDef](./type_defs.md#parameternamevaluetypedef)\]

Returns a `Coroutine` for
[CacheParameterGroupNameMessageTypeDef](./type_defs.md#cacheparametergroupnamemessagetypedef).

<a id="revoke\_cache\_security\_group\_ingress"></a>

### revoke_cache_security_group_ingress

Revokes ingress from a cache security group.

Type annotations for
`session.create_client("elasticache").revoke_cache_security_group_ingress`
method.

Boto3 documentation:
[ElastiCache.Client.revoke_cache_security_group_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.revoke_cache_security_group_ingress)

Asynchronous method. Use `await revoke_cache_security_group_ingress(...)` for a
synchronous call.

Arguments mapping described in
[RevokeCacheSecurityGroupIngressMessageRequestTypeDef](./type_defs.md#revokecachesecuritygroupingressmessagerequesttypedef).

Keyword-only arguments:

- `CacheSecurityGroupName`: `str` *(required)*
- `EC2SecurityGroupName`: `str` *(required)*
- `EC2SecurityGroupOwnerId`: `str` *(required)*

Returns a `Coroutine` for
[RevokeCacheSecurityGroupIngressResultTypeDef](./type_defs.md#revokecachesecuritygroupingressresulttypedef).

<a id="start\_migration"></a>

### start_migration

Start the migration of data.

Type annotations for `session.create_client("elasticache").start_migration`
method.

Boto3 documentation:
[ElastiCache.Client.start_migration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.start_migration)

Asynchronous method. Use `await start_migration(...)` for a synchronous call.

Arguments mapping described in
[StartMigrationMessageRequestTypeDef](./type_defs.md#startmigrationmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `CustomerNodeEndpointList`:
  `Sequence`\[[CustomerNodeEndpointTypeDef](./type_defs.md#customernodeendpointtypedef)\]
  *(required)*

Returns a `Coroutine` for
[StartMigrationResponseTypeDef](./type_defs.md#startmigrationresponsetypedef).

<a id="test\_failover"></a>

### test_failover

Represents the input of a `TestFailover` operation which test automatic
failover on a specified node group (called shard in the console) in a
replication group (called cluster in the console).

Type annotations for `session.create_client("elasticache").test_failover`
method.

Boto3 documentation:
[ElastiCache.Client.test_failover](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.test_failover)

Asynchronous method. Use `await test_failover(...)` for a synchronous call.

Arguments mapping described in
[TestFailoverMessageRequestTypeDef](./type_defs.md#testfailovermessagerequesttypedef).

Keyword-only arguments:

- `ReplicationGroupId`: `str` *(required)*
- `NodeGroupId`: `str` *(required)*

Returns a `Coroutine` for
[TestFailoverResultTypeDef](./type_defs.md#testfailoverresulttypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("elasticache").__aenter__` method.

Boto3 documentation:
[ElastiCache.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [ElastiCacheClient](#elasticacheclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("elasticache").__aexit__` method.

Boto3 documentation:
[ElastiCache.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("elasticache").get_paginator`
method with overloads.

- `client.get_paginator("describe_cache_clusters")` ->
  [DescribeCacheClustersPaginator](./paginators.md#describecacheclusterspaginator)
- `client.get_paginator("describe_cache_engine_versions")` ->
  [DescribeCacheEngineVersionsPaginator](./paginators.md#describecacheengineversionspaginator)
- `client.get_paginator("describe_cache_parameter_groups")` ->
  [DescribeCacheParameterGroupsPaginator](./paginators.md#describecacheparametergroupspaginator)
- `client.get_paginator("describe_cache_parameters")` ->
  [DescribeCacheParametersPaginator](./paginators.md#describecacheparameterspaginator)
- `client.get_paginator("describe_cache_security_groups")` ->
  [DescribeCacheSecurityGroupsPaginator](./paginators.md#describecachesecuritygroupspaginator)
- `client.get_paginator("describe_cache_subnet_groups")` ->
  [DescribeCacheSubnetGroupsPaginator](./paginators.md#describecachesubnetgroupspaginator)
- `client.get_paginator("describe_engine_default_parameters")` ->
  [DescribeEngineDefaultParametersPaginator](./paginators.md#describeenginedefaultparameterspaginator)
- `client.get_paginator("describe_events")` ->
  [DescribeEventsPaginator](./paginators.md#describeeventspaginator)
- `client.get_paginator("describe_global_replication_groups")` ->
  [DescribeGlobalReplicationGroupsPaginator](./paginators.md#describeglobalreplicationgroupspaginator)
- `client.get_paginator("describe_replication_groups")` ->
  [DescribeReplicationGroupsPaginator](./paginators.md#describereplicationgroupspaginator)
- `client.get_paginator("describe_reserved_cache_nodes")` ->
  [DescribeReservedCacheNodesPaginator](./paginators.md#describereservedcachenodespaginator)
- `client.get_paginator("describe_reserved_cache_nodes_offerings")` ->
  [DescribeReservedCacheNodesOfferingsPaginator](./paginators.md#describereservedcachenodesofferingspaginator)
- `client.get_paginator("describe_service_updates")` ->
  [DescribeServiceUpdatesPaginator](./paginators.md#describeserviceupdatespaginator)
- `client.get_paginator("describe_snapshots")` ->
  [DescribeSnapshotsPaginator](./paginators.md#describesnapshotspaginator)
- `client.get_paginator("describe_update_actions")` ->
  [DescribeUpdateActionsPaginator](./paginators.md#describeupdateactionspaginator)
- `client.get_paginator("describe_user_groups")` ->
  [DescribeUserGroupsPaginator](./paginators.md#describeusergroupspaginator)
- `client.get_paginator("describe_users")` ->
  [DescribeUsersPaginator](./paginators.md#describeuserspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("elasticache").get_waiter` method
with overloads.

- `client.get_waiter("cache_cluster_available")` ->
  [CacheClusterAvailableWaiter](./waiters.md#cacheclusteravailablewaiter)
- `client.get_waiter("cache_cluster_deleted")` ->
  [CacheClusterDeletedWaiter](./waiters.md#cacheclusterdeletedwaiter)
- `client.get_waiter("replication_group_available")` ->
  [ReplicationGroupAvailableWaiter](./waiters.md#replicationgroupavailablewaiter)
- `client.get_waiter("replication_group_deleted")` ->
  [ReplicationGroupDeletedWaiter](./waiters.md#replicationgroupdeletedwaiter)
