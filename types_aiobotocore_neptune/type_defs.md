<a id="typed-dictionaries-for-aiobotocore-neptune-module"></a>

# Typed dictionaries for aiobotocore Neptune module

> [Index](..) > [Neptune](.) > Typed dictionaries

Auto-generated documentation for
[Neptune](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune)
type annotations stubs module
[types-aiobotocore-neptune](https://pypi.org/project/types-aiobotocore-neptune/).

- [Typed dictionaries for aiobotocore Neptune module](#typed-dictionaries-for-aiobotocore-neptune-module)
  - [AddRoleToDBClusterMessageRequestTypeDef](#addroletodbclustermessagerequesttypedef)
  - [AddSourceIdentifierToSubscriptionMessageRequestTypeDef](#addsourceidentifiertosubscriptionmessagerequesttypedef)
  - [AddSourceIdentifierToSubscriptionResultTypeDef](#addsourceidentifiertosubscriptionresulttypedef)
  - [AddTagsToResourceMessageRequestTypeDef](#addtagstoresourcemessagerequesttypedef)
  - [ApplyPendingMaintenanceActionMessageRequestTypeDef](#applypendingmaintenanceactionmessagerequesttypedef)
  - [ApplyPendingMaintenanceActionResultTypeDef](#applypendingmaintenanceactionresulttypedef)
  - [AvailabilityZoneTypeDef](#availabilityzonetypedef)
  - [CharacterSetTypeDef](#charactersettypedef)
  - [CloudwatchLogsExportConfigurationTypeDef](#cloudwatchlogsexportconfigurationtypedef)
  - [CopyDBClusterParameterGroupMessageRequestTypeDef](#copydbclusterparametergroupmessagerequesttypedef)
  - [CopyDBClusterParameterGroupResultTypeDef](#copydbclusterparametergroupresulttypedef)
  - [CopyDBClusterSnapshotMessageRequestTypeDef](#copydbclustersnapshotmessagerequesttypedef)
  - [CopyDBClusterSnapshotResultTypeDef](#copydbclustersnapshotresulttypedef)
  - [CopyDBParameterGroupMessageRequestTypeDef](#copydbparametergroupmessagerequesttypedef)
  - [CopyDBParameterGroupResultTypeDef](#copydbparametergroupresulttypedef)
  - [CreateDBClusterEndpointMessageRequestTypeDef](#createdbclusterendpointmessagerequesttypedef)
  - [CreateDBClusterEndpointOutputTypeDef](#createdbclusterendpointoutputtypedef)
  - [CreateDBClusterMessageRequestTypeDef](#createdbclustermessagerequesttypedef)
  - [CreateDBClusterParameterGroupMessageRequestTypeDef](#createdbclusterparametergroupmessagerequesttypedef)
  - [CreateDBClusterParameterGroupResultTypeDef](#createdbclusterparametergroupresulttypedef)
  - [CreateDBClusterResultTypeDef](#createdbclusterresulttypedef)
  - [CreateDBClusterSnapshotMessageRequestTypeDef](#createdbclustersnapshotmessagerequesttypedef)
  - [CreateDBClusterSnapshotResultTypeDef](#createdbclustersnapshotresulttypedef)
  - [CreateDBInstanceMessageRequestTypeDef](#createdbinstancemessagerequesttypedef)
  - [CreateDBInstanceResultTypeDef](#createdbinstanceresulttypedef)
  - [CreateDBParameterGroupMessageRequestTypeDef](#createdbparametergroupmessagerequesttypedef)
  - [CreateDBParameterGroupResultTypeDef](#createdbparametergroupresulttypedef)
  - [CreateDBSubnetGroupMessageRequestTypeDef](#createdbsubnetgroupmessagerequesttypedef)
  - [CreateDBSubnetGroupResultTypeDef](#createdbsubnetgroupresulttypedef)
  - [CreateEventSubscriptionMessageRequestTypeDef](#createeventsubscriptionmessagerequesttypedef)
  - [CreateEventSubscriptionResultTypeDef](#createeventsubscriptionresulttypedef)
  - [DBClusterEndpointMessageTypeDef](#dbclusterendpointmessagetypedef)
  - [DBClusterEndpointTypeDef](#dbclusterendpointtypedef)
  - [DBClusterMemberTypeDef](#dbclustermembertypedef)
  - [DBClusterMessageTypeDef](#dbclustermessagetypedef)
  - [DBClusterOptionGroupStatusTypeDef](#dbclusteroptiongroupstatustypedef)
  - [DBClusterParameterGroupDetailsTypeDef](#dbclusterparametergroupdetailstypedef)
  - [DBClusterParameterGroupNameMessageTypeDef](#dbclusterparametergroupnamemessagetypedef)
  - [DBClusterParameterGroupTypeDef](#dbclusterparametergrouptypedef)
  - [DBClusterParameterGroupsMessageTypeDef](#dbclusterparametergroupsmessagetypedef)
  - [DBClusterRoleTypeDef](#dbclusterroletypedef)
  - [DBClusterSnapshotAttributeTypeDef](#dbclustersnapshotattributetypedef)
  - [DBClusterSnapshotAttributesResultTypeDef](#dbclustersnapshotattributesresulttypedef)
  - [DBClusterSnapshotMessageTypeDef](#dbclustersnapshotmessagetypedef)
  - [DBClusterSnapshotTypeDef](#dbclustersnapshottypedef)
  - [DBClusterTypeDef](#dbclustertypedef)
  - [DBEngineVersionMessageTypeDef](#dbengineversionmessagetypedef)
  - [DBEngineVersionTypeDef](#dbengineversiontypedef)
  - [DBInstanceMessageTypeDef](#dbinstancemessagetypedef)
  - [DBInstanceStatusInfoTypeDef](#dbinstancestatusinfotypedef)
  - [DBInstanceTypeDef](#dbinstancetypedef)
  - [DBParameterGroupDetailsTypeDef](#dbparametergroupdetailstypedef)
  - [DBParameterGroupNameMessageTypeDef](#dbparametergroupnamemessagetypedef)
  - [DBParameterGroupStatusTypeDef](#dbparametergroupstatustypedef)
  - [DBParameterGroupTypeDef](#dbparametergrouptypedef)
  - [DBParameterGroupsMessageTypeDef](#dbparametergroupsmessagetypedef)
  - [DBSecurityGroupMembershipTypeDef](#dbsecuritygroupmembershiptypedef)
  - [DBSubnetGroupMessageTypeDef](#dbsubnetgroupmessagetypedef)
  - [DBSubnetGroupTypeDef](#dbsubnetgrouptypedef)
  - [DeleteDBClusterEndpointMessageRequestTypeDef](#deletedbclusterendpointmessagerequesttypedef)
  - [DeleteDBClusterEndpointOutputTypeDef](#deletedbclusterendpointoutputtypedef)
  - [DeleteDBClusterMessageRequestTypeDef](#deletedbclustermessagerequesttypedef)
  - [DeleteDBClusterParameterGroupMessageRequestTypeDef](#deletedbclusterparametergroupmessagerequesttypedef)
  - [DeleteDBClusterResultTypeDef](#deletedbclusterresulttypedef)
  - [DeleteDBClusterSnapshotMessageRequestTypeDef](#deletedbclustersnapshotmessagerequesttypedef)
  - [DeleteDBClusterSnapshotResultTypeDef](#deletedbclustersnapshotresulttypedef)
  - [DeleteDBInstanceMessageRequestTypeDef](#deletedbinstancemessagerequesttypedef)
  - [DeleteDBInstanceResultTypeDef](#deletedbinstanceresulttypedef)
  - [DeleteDBParameterGroupMessageRequestTypeDef](#deletedbparametergroupmessagerequesttypedef)
  - [DeleteDBSubnetGroupMessageRequestTypeDef](#deletedbsubnetgroupmessagerequesttypedef)
  - [DeleteEventSubscriptionMessageRequestTypeDef](#deleteeventsubscriptionmessagerequesttypedef)
  - [DeleteEventSubscriptionResultTypeDef](#deleteeventsubscriptionresulttypedef)
  - [DescribeDBClusterEndpointsMessageRequestTypeDef](#describedbclusterendpointsmessagerequesttypedef)
  - [DescribeDBClusterParameterGroupsMessageRequestTypeDef](#describedbclusterparametergroupsmessagerequesttypedef)
  - [DescribeDBClusterParametersMessageRequestTypeDef](#describedbclusterparametersmessagerequesttypedef)
  - [DescribeDBClusterSnapshotAttributesMessageRequestTypeDef](#describedbclustersnapshotattributesmessagerequesttypedef)
  - [DescribeDBClusterSnapshotAttributesResultTypeDef](#describedbclustersnapshotattributesresulttypedef)
  - [DescribeDBClusterSnapshotsMessageRequestTypeDef](#describedbclustersnapshotsmessagerequesttypedef)
  - [DescribeDBClustersMessageRequestTypeDef](#describedbclustersmessagerequesttypedef)
  - [DescribeDBEngineVersionsMessageRequestTypeDef](#describedbengineversionsmessagerequesttypedef)
  - [DescribeDBInstancesMessageRequestTypeDef](#describedbinstancesmessagerequesttypedef)
  - [DescribeDBParameterGroupsMessageRequestTypeDef](#describedbparametergroupsmessagerequesttypedef)
  - [DescribeDBParametersMessageRequestTypeDef](#describedbparametersmessagerequesttypedef)
  - [DescribeDBSubnetGroupsMessageRequestTypeDef](#describedbsubnetgroupsmessagerequesttypedef)
  - [DescribeEngineDefaultClusterParametersMessageRequestTypeDef](#describeenginedefaultclusterparametersmessagerequesttypedef)
  - [DescribeEngineDefaultClusterParametersResultTypeDef](#describeenginedefaultclusterparametersresulttypedef)
  - [DescribeEngineDefaultParametersMessageRequestTypeDef](#describeenginedefaultparametersmessagerequesttypedef)
  - [DescribeEngineDefaultParametersResultTypeDef](#describeenginedefaultparametersresulttypedef)
  - [DescribeEventCategoriesMessageRequestTypeDef](#describeeventcategoriesmessagerequesttypedef)
  - [DescribeEventSubscriptionsMessageRequestTypeDef](#describeeventsubscriptionsmessagerequesttypedef)
  - [DescribeEventsMessageRequestTypeDef](#describeeventsmessagerequesttypedef)
  - [DescribeOrderableDBInstanceOptionsMessageRequestTypeDef](#describeorderabledbinstanceoptionsmessagerequesttypedef)
  - [DescribePendingMaintenanceActionsMessageRequestTypeDef](#describependingmaintenanceactionsmessagerequesttypedef)
  - [DescribeValidDBInstanceModificationsMessageRequestTypeDef](#describevaliddbinstancemodificationsmessagerequesttypedef)
  - [DescribeValidDBInstanceModificationsResultTypeDef](#describevaliddbinstancemodificationsresulttypedef)
  - [DomainMembershipTypeDef](#domainmembershiptypedef)
  - [DoubleRangeTypeDef](#doublerangetypedef)
  - [EndpointTypeDef](#endpointtypedef)
  - [EngineDefaultsTypeDef](#enginedefaultstypedef)
  - [EventCategoriesMapTypeDef](#eventcategoriesmaptypedef)
  - [EventCategoriesMessageTypeDef](#eventcategoriesmessagetypedef)
  - [EventSubscriptionTypeDef](#eventsubscriptiontypedef)
  - [EventSubscriptionsMessageTypeDef](#eventsubscriptionsmessagetypedef)
  - [EventTypeDef](#eventtypedef)
  - [EventsMessageTypeDef](#eventsmessagetypedef)
  - [FailoverDBClusterMessageRequestTypeDef](#failoverdbclustermessagerequesttypedef)
  - [FailoverDBClusterResultTypeDef](#failoverdbclusterresulttypedef)
  - [FilterTypeDef](#filtertypedef)
  - [ListTagsForResourceMessageRequestTypeDef](#listtagsforresourcemessagerequesttypedef)
  - [ModifyDBClusterEndpointMessageRequestTypeDef](#modifydbclusterendpointmessagerequesttypedef)
  - [ModifyDBClusterEndpointOutputTypeDef](#modifydbclusterendpointoutputtypedef)
  - [ModifyDBClusterMessageRequestTypeDef](#modifydbclustermessagerequesttypedef)
  - [ModifyDBClusterParameterGroupMessageRequestTypeDef](#modifydbclusterparametergroupmessagerequesttypedef)
  - [ModifyDBClusterResultTypeDef](#modifydbclusterresulttypedef)
  - [ModifyDBClusterSnapshotAttributeMessageRequestTypeDef](#modifydbclustersnapshotattributemessagerequesttypedef)
  - [ModifyDBClusterSnapshotAttributeResultTypeDef](#modifydbclustersnapshotattributeresulttypedef)
  - [ModifyDBInstanceMessageRequestTypeDef](#modifydbinstancemessagerequesttypedef)
  - [ModifyDBInstanceResultTypeDef](#modifydbinstanceresulttypedef)
  - [ModifyDBParameterGroupMessageRequestTypeDef](#modifydbparametergroupmessagerequesttypedef)
  - [ModifyDBSubnetGroupMessageRequestTypeDef](#modifydbsubnetgroupmessagerequesttypedef)
  - [ModifyDBSubnetGroupResultTypeDef](#modifydbsubnetgroupresulttypedef)
  - [ModifyEventSubscriptionMessageRequestTypeDef](#modifyeventsubscriptionmessagerequesttypedef)
  - [ModifyEventSubscriptionResultTypeDef](#modifyeventsubscriptionresulttypedef)
  - [OptionGroupMembershipTypeDef](#optiongroupmembershiptypedef)
  - [OrderableDBInstanceOptionTypeDef](#orderabledbinstanceoptiontypedef)
  - [OrderableDBInstanceOptionsMessageTypeDef](#orderabledbinstanceoptionsmessagetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ParameterTypeDef](#parametertypedef)
  - [PendingCloudwatchLogsExportsTypeDef](#pendingcloudwatchlogsexportstypedef)
  - [PendingMaintenanceActionTypeDef](#pendingmaintenanceactiontypedef)
  - [PendingMaintenanceActionsMessageTypeDef](#pendingmaintenanceactionsmessagetypedef)
  - [PendingModifiedValuesTypeDef](#pendingmodifiedvaluestypedef)
  - [PromoteReadReplicaDBClusterMessageRequestTypeDef](#promotereadreplicadbclustermessagerequesttypedef)
  - [PromoteReadReplicaDBClusterResultTypeDef](#promotereadreplicadbclusterresulttypedef)
  - [RangeTypeDef](#rangetypedef)
  - [RebootDBInstanceMessageRequestTypeDef](#rebootdbinstancemessagerequesttypedef)
  - [RebootDBInstanceResultTypeDef](#rebootdbinstanceresulttypedef)
  - [RemoveRoleFromDBClusterMessageRequestTypeDef](#removerolefromdbclustermessagerequesttypedef)
  - [RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef](#removesourceidentifierfromsubscriptionmessagerequesttypedef)
  - [RemoveSourceIdentifierFromSubscriptionResultTypeDef](#removesourceidentifierfromsubscriptionresulttypedef)
  - [RemoveTagsFromResourceMessageRequestTypeDef](#removetagsfromresourcemessagerequesttypedef)
  - [ResetDBClusterParameterGroupMessageRequestTypeDef](#resetdbclusterparametergroupmessagerequesttypedef)
  - [ResetDBParameterGroupMessageRequestTypeDef](#resetdbparametergroupmessagerequesttypedef)
  - [ResourcePendingMaintenanceActionsTypeDef](#resourcependingmaintenanceactionstypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RestoreDBClusterFromSnapshotMessageRequestTypeDef](#restoredbclusterfromsnapshotmessagerequesttypedef)
  - [RestoreDBClusterFromSnapshotResultTypeDef](#restoredbclusterfromsnapshotresulttypedef)
  - [RestoreDBClusterToPointInTimeMessageRequestTypeDef](#restoredbclustertopointintimemessagerequesttypedef)
  - [RestoreDBClusterToPointInTimeResultTypeDef](#restoredbclustertopointintimeresulttypedef)
  - [StartDBClusterMessageRequestTypeDef](#startdbclustermessagerequesttypedef)
  - [StartDBClusterResultTypeDef](#startdbclusterresulttypedef)
  - [StopDBClusterMessageRequestTypeDef](#stopdbclustermessagerequesttypedef)
  - [StopDBClusterResultTypeDef](#stopdbclusterresulttypedef)
  - [SubnetTypeDef](#subnettypedef)
  - [TagListMessageTypeDef](#taglistmessagetypedef)
  - [TagTypeDef](#tagtypedef)
  - [TimezoneTypeDef](#timezonetypedef)
  - [UpgradeTargetTypeDef](#upgradetargettypedef)
  - [ValidDBInstanceModificationsMessageTypeDef](#validdbinstancemodificationsmessagetypedef)
  - [ValidStorageOptionsTypeDef](#validstorageoptionstypedef)
  - [VpcSecurityGroupMembershipTypeDef](#vpcsecuritygroupmembershiptypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)

<a id="addroletodbclustermessagerequesttypedef"></a>

## AddRoleToDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import AddRoleToDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`
- `RoleArn`: `str`

Optional fields:

- `FeatureName`: `str`

<a id="addsourceidentifiertosubscriptionmessagerequesttypedef"></a>

## AddSourceIdentifierToSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import AddSourceIdentifierToSubscriptionMessageRequestTypeDef
```

Required fields:

- `SubscriptionName`: `str`
- `SourceIdentifier`: `str`

<a id="addsourceidentifiertosubscriptionresulttypedef"></a>

## AddSourceIdentifierToSubscriptionResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import AddSourceIdentifierToSubscriptionResultTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="addtagstoresourcemessagerequesttypedef"></a>

## AddTagsToResourceMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import AddTagsToResourceMessageRequestTypeDef
```

Required fields:

- `ResourceName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="applypendingmaintenanceactionmessagerequesttypedef"></a>

## ApplyPendingMaintenanceActionMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ApplyPendingMaintenanceActionMessageRequestTypeDef
```

Required fields:

- `ResourceIdentifier`: `str`
- `ApplyAction`: `str`
- `OptInType`: `str`

<a id="applypendingmaintenanceactionresulttypedef"></a>

## ApplyPendingMaintenanceActionResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import ApplyPendingMaintenanceActionResultTypeDef
```

Required fields:

- `ResourcePendingMaintenanceActions`:
  [ResourcePendingMaintenanceActionsTypeDef](./type_defs.md#resourcependingmaintenanceactionstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="availabilityzonetypedef"></a>

## AvailabilityZoneTypeDef

```python
from types_aiobotocore_neptune.type_defs import AvailabilityZoneTypeDef
```

Optional fields:

- `Name`: `str`

<a id="charactersettypedef"></a>

## CharacterSetTypeDef

```python
from types_aiobotocore_neptune.type_defs import CharacterSetTypeDef
```

Optional fields:

- `CharacterSetName`: `str`
- `CharacterSetDescription`: `str`

<a id="cloudwatchlogsexportconfigurationtypedef"></a>

## CloudwatchLogsExportConfigurationTypeDef

```python
from types_aiobotocore_neptune.type_defs import CloudwatchLogsExportConfigurationTypeDef
```

Optional fields:

- `EnableLogTypes`: `Sequence`\[`str`\]
- `DisableLogTypes`: `Sequence`\[`str`\]

<a id="copydbclusterparametergroupmessagerequesttypedef"></a>

## CopyDBClusterParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CopyDBClusterParameterGroupMessageRequestTypeDef
```

Required fields:

- `SourceDBClusterParameterGroupIdentifier`: `str`
- `TargetDBClusterParameterGroupIdentifier`: `str`
- `TargetDBClusterParameterGroupDescription`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="copydbclusterparametergroupresulttypedef"></a>

## CopyDBClusterParameterGroupResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CopyDBClusterParameterGroupResultTypeDef
```

Required fields:

- `DBClusterParameterGroup`:
  [DBClusterParameterGroupTypeDef](./type_defs.md#dbclusterparametergrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="copydbclustersnapshotmessagerequesttypedef"></a>

## CopyDBClusterSnapshotMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CopyDBClusterSnapshotMessageRequestTypeDef
```

Required fields:

- `SourceDBClusterSnapshotIdentifier`: `str`
- `TargetDBClusterSnapshotIdentifier`: `str`

Optional fields:

- `KmsKeyId`: `str`
- `PreSignedUrl`: `str`
- `CopyTags`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `SourceRegion`: `str`

<a id="copydbclustersnapshotresulttypedef"></a>

## CopyDBClusterSnapshotResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CopyDBClusterSnapshotResultTypeDef
```

Required fields:

- `DBClusterSnapshot`:
  [DBClusterSnapshotTypeDef](./type_defs.md#dbclustersnapshottypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="copydbparametergroupmessagerequesttypedef"></a>

## CopyDBParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CopyDBParameterGroupMessageRequestTypeDef
```

Required fields:

- `SourceDBParameterGroupIdentifier`: `str`
- `TargetDBParameterGroupIdentifier`: `str`
- `TargetDBParameterGroupDescription`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="copydbparametergroupresulttypedef"></a>

## CopyDBParameterGroupResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CopyDBParameterGroupResultTypeDef
```

Required fields:

- `DBParameterGroup`:
  [DBParameterGroupTypeDef](./type_defs.md#dbparametergrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdbclusterendpointmessagerequesttypedef"></a>

## CreateDBClusterEndpointMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterEndpointMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`
- `DBClusterEndpointIdentifier`: `str`
- `EndpointType`: `str`

Optional fields:

- `StaticMembers`: `Sequence`\[`str`\]
- `ExcludedMembers`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdbclusterendpointoutputtypedef"></a>

## CreateDBClusterEndpointOutputTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterEndpointOutputTypeDef
```

Required fields:

- `DBClusterEndpointIdentifier`: `str`
- `DBClusterIdentifier`: `str`
- `DBClusterEndpointResourceIdentifier`: `str`
- `Endpoint`: `str`
- `Status`: `str`
- `EndpointType`: `str`
- `CustomEndpointType`: `str`
- `StaticMembers`: `List`\[`str`\]
- `ExcludedMembers`: `List`\[`str`\]
- `DBClusterEndpointArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdbclustermessagerequesttypedef"></a>

## CreateDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`
- `Engine`: `str`

Optional fields:

- `AvailabilityZones`: `Sequence`\[`str`\]
- `BackupRetentionPeriod`: `int`
- `CharacterSetName`: `str`
- `CopyTagsToSnapshot`: `bool`
- `DatabaseName`: `str`
- `DBClusterParameterGroupName`: `str`
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `DBSubnetGroupName`: `str`
- `EngineVersion`: `str`
- `Port`: `int`
- `MasterUsername`: `str`
- `MasterUserPassword`: `str`
- `OptionGroupName`: `str`
- `PreferredBackupWindow`: `str`
- `PreferredMaintenanceWindow`: `str`
- `ReplicationSourceIdentifier`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `StorageEncrypted`: `bool`
- `KmsKeyId`: `str`
- `PreSignedUrl`: `str`
- `EnableIAMDatabaseAuthentication`: `bool`
- `EnableCloudwatchLogsExports`: `Sequence`\[`str`\]
- `DeletionProtection`: `bool`
- `SourceRegion`: `str`

<a id="createdbclusterparametergroupmessagerequesttypedef"></a>

## CreateDBClusterParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBClusterParameterGroupName`: `str`
- `DBParameterGroupFamily`: `str`
- `Description`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdbclusterparametergroupresulttypedef"></a>

## CreateDBClusterParameterGroupResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterParameterGroupResultTypeDef
```

Required fields:

- `DBClusterParameterGroup`:
  [DBClusterParameterGroupTypeDef](./type_defs.md#dbclusterparametergrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdbclusterresulttypedef"></a>

## CreateDBClusterResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdbclustersnapshotmessagerequesttypedef"></a>

## CreateDBClusterSnapshotMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterSnapshotMessageRequestTypeDef
```

Required fields:

- `DBClusterSnapshotIdentifier`: `str`
- `DBClusterIdentifier`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdbclustersnapshotresulttypedef"></a>

## CreateDBClusterSnapshotResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBClusterSnapshotResultTypeDef
```

Required fields:

- `DBClusterSnapshot`:
  [DBClusterSnapshotTypeDef](./type_defs.md#dbclustersnapshottypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdbinstancemessagerequesttypedef"></a>

## CreateDBInstanceMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBInstanceMessageRequestTypeDef
```

Required fields:

- `DBInstanceIdentifier`: `str`
- `DBInstanceClass`: `str`
- `Engine`: `str`

Optional fields:

- `DBName`: `str`
- `AllocatedStorage`: `int`
- `MasterUsername`: `str`
- `MasterUserPassword`: `str`
- `DBSecurityGroups`: `Sequence`\[`str`\]
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `AvailabilityZone`: `str`
- `DBSubnetGroupName`: `str`
- `PreferredMaintenanceWindow`: `str`
- `DBParameterGroupName`: `str`
- `BackupRetentionPeriod`: `int`
- `PreferredBackupWindow`: `str`
- `Port`: `int`
- `MultiAZ`: `bool`
- `EngineVersion`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `LicenseModel`: `str`
- `Iops`: `int`
- `OptionGroupName`: `str`
- `CharacterSetName`: `str`
- `PubliclyAccessible`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `DBClusterIdentifier`: `str`
- `StorageType`: `str`
- `TdeCredentialArn`: `str`
- `TdeCredentialPassword`: `str`
- `StorageEncrypted`: `bool`
- `KmsKeyId`: `str`
- `Domain`: `str`
- `CopyTagsToSnapshot`: `bool`
- `MonitoringInterval`: `int`
- `MonitoringRoleArn`: `str`
- `DomainIAMRoleName`: `str`
- `PromotionTier`: `int`
- `Timezone`: `str`
- `EnableIAMDatabaseAuthentication`: `bool`
- `EnablePerformanceInsights`: `bool`
- `PerformanceInsightsKMSKeyId`: `str`
- `EnableCloudwatchLogsExports`: `Sequence`\[`str`\]
- `DeletionProtection`: `bool`

<a id="createdbinstanceresulttypedef"></a>

## CreateDBInstanceResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBInstanceResultTypeDef
```

Required fields:

- `DBInstance`: [DBInstanceTypeDef](./type_defs.md#dbinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdbparametergroupmessagerequesttypedef"></a>

## CreateDBParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBParameterGroupName`: `str`
- `DBParameterGroupFamily`: `str`
- `Description`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdbparametergroupresulttypedef"></a>

## CreateDBParameterGroupResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBParameterGroupResultTypeDef
```

Required fields:

- `DBParameterGroup`:
  [DBParameterGroupTypeDef](./type_defs.md#dbparametergrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdbsubnetgroupmessagerequesttypedef"></a>

## CreateDBSubnetGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBSubnetGroupMessageRequestTypeDef
```

Required fields:

- `DBSubnetGroupName`: `str`
- `DBSubnetGroupDescription`: `str`
- `SubnetIds`: `Sequence`\[`str`\]

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdbsubnetgroupresulttypedef"></a>

## CreateDBSubnetGroupResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateDBSubnetGroupResultTypeDef
```

Required fields:

- `DBSubnetGroup`: [DBSubnetGroupTypeDef](./type_defs.md#dbsubnetgrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createeventsubscriptionmessagerequesttypedef"></a>

## CreateEventSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateEventSubscriptionMessageRequestTypeDef
```

Required fields:

- `SubscriptionName`: `str`
- `SnsTopicArn`: `str`

Optional fields:

- `SourceType`: `str`
- `EventCategories`: `Sequence`\[`str`\]
- `SourceIds`: `Sequence`\[`str`\]
- `Enabled`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createeventsubscriptionresulttypedef"></a>

## CreateEventSubscriptionResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import CreateEventSubscriptionResultTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbclusterendpointmessagetypedef"></a>

## DBClusterEndpointMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterEndpointMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBClusterEndpoints`:
  `List`\[[DBClusterEndpointTypeDef](./type_defs.md#dbclusterendpointtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbclusterendpointtypedef"></a>

## DBClusterEndpointTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterEndpointTypeDef
```

Optional fields:

- `DBClusterEndpointIdentifier`: `str`
- `DBClusterIdentifier`: `str`
- `DBClusterEndpointResourceIdentifier`: `str`
- `Endpoint`: `str`
- `Status`: `str`
- `EndpointType`: `str`
- `CustomEndpointType`: `str`
- `StaticMembers`: `List`\[`str`\]
- `ExcludedMembers`: `List`\[`str`\]
- `DBClusterEndpointArn`: `str`

<a id="dbclustermembertypedef"></a>

## DBClusterMemberTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterMemberTypeDef
```

Optional fields:

- `DBInstanceIdentifier`: `str`
- `IsClusterWriter`: `bool`
- `DBClusterParameterGroupStatus`: `str`
- `PromotionTier`: `int`

<a id="dbclustermessagetypedef"></a>

## DBClusterMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBClusters`: `List`\[[DBClusterTypeDef](./type_defs.md#dbclustertypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbclusteroptiongroupstatustypedef"></a>

## DBClusterOptionGroupStatusTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterOptionGroupStatusTypeDef
```

Optional fields:

- `DBClusterOptionGroupName`: `str`
- `Status`: `str`

<a id="dbclusterparametergroupdetailstypedef"></a>

## DBClusterParameterGroupDetailsTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterParameterGroupDetailsTypeDef
```

Required fields:

- `Parameters`: `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbclusterparametergroupnamemessagetypedef"></a>

## DBClusterParameterGroupNameMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterParameterGroupNameMessageTypeDef
```

Required fields:

- `DBClusterParameterGroupName`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbclusterparametergrouptypedef"></a>

## DBClusterParameterGroupTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterParameterGroupTypeDef
```

Optional fields:

- `DBClusterParameterGroupName`: `str`
- `DBParameterGroupFamily`: `str`
- `Description`: `str`
- `DBClusterParameterGroupArn`: `str`

<a id="dbclusterparametergroupsmessagetypedef"></a>

## DBClusterParameterGroupsMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterParameterGroupsMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBClusterParameterGroups`:
  `List`\[[DBClusterParameterGroupTypeDef](./type_defs.md#dbclusterparametergrouptypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbclusterroletypedef"></a>

## DBClusterRoleTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterRoleTypeDef
```

Optional fields:

- `RoleArn`: `str`
- `Status`: `str`
- `FeatureName`: `str`

<a id="dbclustersnapshotattributetypedef"></a>

## DBClusterSnapshotAttributeTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterSnapshotAttributeTypeDef
```

Optional fields:

- `AttributeName`: `str`
- `AttributeValues`: `List`\[`str`\]

<a id="dbclustersnapshotattributesresulttypedef"></a>

## DBClusterSnapshotAttributesResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterSnapshotAttributesResultTypeDef
```

Optional fields:

- `DBClusterSnapshotIdentifier`: `str`
- `DBClusterSnapshotAttributes`:
  `List`\[[DBClusterSnapshotAttributeTypeDef](./type_defs.md#dbclustersnapshotattributetypedef)\]

<a id="dbclustersnapshotmessagetypedef"></a>

## DBClusterSnapshotMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterSnapshotMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBClusterSnapshots`:
  `List`\[[DBClusterSnapshotTypeDef](./type_defs.md#dbclustersnapshottypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbclustersnapshottypedef"></a>

## DBClusterSnapshotTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterSnapshotTypeDef
```

Optional fields:

- `AvailabilityZones`: `List`\[`str`\]
- `DBClusterSnapshotIdentifier`: `str`
- `DBClusterIdentifier`: `str`
- `SnapshotCreateTime`: `datetime`
- `Engine`: `str`
- `AllocatedStorage`: `int`
- `Status`: `str`
- `Port`: `int`
- `VpcId`: `str`
- `ClusterCreateTime`: `datetime`
- `MasterUsername`: `str`
- `EngineVersion`: `str`
- `LicenseModel`: `str`
- `SnapshotType`: `str`
- `PercentProgress`: `int`
- `StorageEncrypted`: `bool`
- `KmsKeyId`: `str`
- `DBClusterSnapshotArn`: `str`
- `SourceDBClusterSnapshotArn`: `str`
- `IAMDatabaseAuthenticationEnabled`: `bool`

<a id="dbclustertypedef"></a>

## DBClusterTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBClusterTypeDef
```

Optional fields:

- `AllocatedStorage`: `int`
- `AvailabilityZones`: `List`\[`str`\]
- `BackupRetentionPeriod`: `int`
- `CharacterSetName`: `str`
- `DatabaseName`: `str`
- `DBClusterIdentifier`: `str`
- `DBClusterParameterGroup`: `str`
- `DBSubnetGroup`: `str`
- `Status`: `str`
- `PercentProgress`: `str`
- `EarliestRestorableTime`: `datetime`
- `Endpoint`: `str`
- `ReaderEndpoint`: `str`
- `MultiAZ`: `bool`
- `Engine`: `str`
- `EngineVersion`: `str`
- `LatestRestorableTime`: `datetime`
- `Port`: `int`
- `MasterUsername`: `str`
- `DBClusterOptionGroupMemberships`:
  `List`\[[DBClusterOptionGroupStatusTypeDef](./type_defs.md#dbclusteroptiongroupstatustypedef)\]
- `PreferredBackupWindow`: `str`
- `PreferredMaintenanceWindow`: `str`
- `ReplicationSourceIdentifier`: `str`
- `ReadReplicaIdentifiers`: `List`\[`str`\]
- `DBClusterMembers`:
  `List`\[[DBClusterMemberTypeDef](./type_defs.md#dbclustermembertypedef)\]
- `VpcSecurityGroups`:
  `List`\[[VpcSecurityGroupMembershipTypeDef](./type_defs.md#vpcsecuritygroupmembershiptypedef)\]
- `HostedZoneId`: `str`
- `StorageEncrypted`: `bool`
- `KmsKeyId`: `str`
- `DbClusterResourceId`: `str`
- `DBClusterArn`: `str`
- `AssociatedRoles`:
  `List`\[[DBClusterRoleTypeDef](./type_defs.md#dbclusterroletypedef)\]
- `IAMDatabaseAuthenticationEnabled`: `bool`
- `CloneGroupId`: `str`
- `ClusterCreateTime`: `datetime`
- `CopyTagsToSnapshot`: `bool`
- `EnabledCloudwatchLogsExports`: `List`\[`str`\]
- `DeletionProtection`: `bool`
- `CrossAccountClone`: `bool`
- `AutomaticRestartTime`: `datetime`

<a id="dbengineversionmessagetypedef"></a>

## DBEngineVersionMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBEngineVersionMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBEngineVersions`:
  `List`\[[DBEngineVersionTypeDef](./type_defs.md#dbengineversiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbengineversiontypedef"></a>

## DBEngineVersionTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBEngineVersionTypeDef
```

Optional fields:

- `Engine`: `str`
- `EngineVersion`: `str`
- `DBParameterGroupFamily`: `str`
- `DBEngineDescription`: `str`
- `DBEngineVersionDescription`: `str`
- `DefaultCharacterSet`:
  [CharacterSetTypeDef](./type_defs.md#charactersettypedef)
- `SupportedCharacterSets`:
  `List`\[[CharacterSetTypeDef](./type_defs.md#charactersettypedef)\]
- `ValidUpgradeTarget`:
  `List`\[[UpgradeTargetTypeDef](./type_defs.md#upgradetargettypedef)\]
- `SupportedTimezones`:
  `List`\[[TimezoneTypeDef](./type_defs.md#timezonetypedef)\]
- `ExportableLogTypes`: `List`\[`str`\]
- `SupportsLogExportsToCloudwatchLogs`: `bool`
- `SupportsReadReplica`: `bool`

<a id="dbinstancemessagetypedef"></a>

## DBInstanceMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBInstanceMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBInstances`:
  `List`\[[DBInstanceTypeDef](./type_defs.md#dbinstancetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbinstancestatusinfotypedef"></a>

## DBInstanceStatusInfoTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBInstanceStatusInfoTypeDef
```

Optional fields:

- `StatusType`: `str`
- `Normal`: `bool`
- `Status`: `str`
- `Message`: `str`

<a id="dbinstancetypedef"></a>

## DBInstanceTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBInstanceTypeDef
```

Optional fields:

- `DBInstanceIdentifier`: `str`
- `DBInstanceClass`: `str`
- `Engine`: `str`
- `DBInstanceStatus`: `str`
- `MasterUsername`: `str`
- `DBName`: `str`
- `Endpoint`: [EndpointTypeDef](./type_defs.md#endpointtypedef)
- `AllocatedStorage`: `int`
- `InstanceCreateTime`: `datetime`
- `PreferredBackupWindow`: `str`
- `BackupRetentionPeriod`: `int`
- `DBSecurityGroups`:
  `List`\[[DBSecurityGroupMembershipTypeDef](./type_defs.md#dbsecuritygroupmembershiptypedef)\]
- `VpcSecurityGroups`:
  `List`\[[VpcSecurityGroupMembershipTypeDef](./type_defs.md#vpcsecuritygroupmembershiptypedef)\]
- `DBParameterGroups`:
  `List`\[[DBParameterGroupStatusTypeDef](./type_defs.md#dbparametergroupstatustypedef)\]
- `AvailabilityZone`: `str`
- `DBSubnetGroup`: [DBSubnetGroupTypeDef](./type_defs.md#dbsubnetgrouptypedef)
- `PreferredMaintenanceWindow`: `str`
- `PendingModifiedValues`:
  [PendingModifiedValuesTypeDef](./type_defs.md#pendingmodifiedvaluestypedef)
- `LatestRestorableTime`: `datetime`
- `MultiAZ`: `bool`
- `EngineVersion`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `ReadReplicaSourceDBInstanceIdentifier`: `str`
- `ReadReplicaDBInstanceIdentifiers`: `List`\[`str`\]
- `ReadReplicaDBClusterIdentifiers`: `List`\[`str`\]
- `LicenseModel`: `str`
- `Iops`: `int`
- `OptionGroupMemberships`:
  `List`\[[OptionGroupMembershipTypeDef](./type_defs.md#optiongroupmembershiptypedef)\]
- `CharacterSetName`: `str`
- `SecondaryAvailabilityZone`: `str`
- `PubliclyAccessible`: `bool`
- `StatusInfos`:
  `List`\[[DBInstanceStatusInfoTypeDef](./type_defs.md#dbinstancestatusinfotypedef)\]
- `StorageType`: `str`
- `TdeCredentialArn`: `str`
- `DbInstancePort`: `int`
- `DBClusterIdentifier`: `str`
- `StorageEncrypted`: `bool`
- `KmsKeyId`: `str`
- `DbiResourceId`: `str`
- `CACertificateIdentifier`: `str`
- `DomainMemberships`:
  `List`\[[DomainMembershipTypeDef](./type_defs.md#domainmembershiptypedef)\]
- `CopyTagsToSnapshot`: `bool`
- `MonitoringInterval`: `int`
- `EnhancedMonitoringResourceArn`: `str`
- `MonitoringRoleArn`: `str`
- `PromotionTier`: `int`
- `DBInstanceArn`: `str`
- `Timezone`: `str`
- `IAMDatabaseAuthenticationEnabled`: `bool`
- `PerformanceInsightsEnabled`: `bool`
- `PerformanceInsightsKMSKeyId`: `str`
- `EnabledCloudwatchLogsExports`: `List`\[`str`\]
- `DeletionProtection`: `bool`

<a id="dbparametergroupdetailstypedef"></a>

## DBParameterGroupDetailsTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBParameterGroupDetailsTypeDef
```

Required fields:

- `Parameters`: `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbparametergroupnamemessagetypedef"></a>

## DBParameterGroupNameMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBParameterGroupNameMessageTypeDef
```

Required fields:

- `DBParameterGroupName`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbparametergroupstatustypedef"></a>

## DBParameterGroupStatusTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBParameterGroupStatusTypeDef
```

Optional fields:

- `DBParameterGroupName`: `str`
- `ParameterApplyStatus`: `str`

<a id="dbparametergrouptypedef"></a>

## DBParameterGroupTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBParameterGroupTypeDef
```

Optional fields:

- `DBParameterGroupName`: `str`
- `DBParameterGroupFamily`: `str`
- `Description`: `str`
- `DBParameterGroupArn`: `str`

<a id="dbparametergroupsmessagetypedef"></a>

## DBParameterGroupsMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBParameterGroupsMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBParameterGroups`:
  `List`\[[DBParameterGroupTypeDef](./type_defs.md#dbparametergrouptypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbsecuritygroupmembershiptypedef"></a>

## DBSecurityGroupMembershipTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBSecurityGroupMembershipTypeDef
```

Optional fields:

- `DBSecurityGroupName`: `str`
- `Status`: `str`

<a id="dbsubnetgroupmessagetypedef"></a>

## DBSubnetGroupMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBSubnetGroupMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `DBSubnetGroups`:
  `List`\[[DBSubnetGroupTypeDef](./type_defs.md#dbsubnetgrouptypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dbsubnetgrouptypedef"></a>

## DBSubnetGroupTypeDef

```python
from types_aiobotocore_neptune.type_defs import DBSubnetGroupTypeDef
```

Optional fields:

- `DBSubnetGroupName`: `str`
- `DBSubnetGroupDescription`: `str`
- `VpcId`: `str`
- `SubnetGroupStatus`: `str`
- `Subnets`: `List`\[[SubnetTypeDef](./type_defs.md#subnettypedef)\]
- `DBSubnetGroupArn`: `str`

<a id="deletedbclusterendpointmessagerequesttypedef"></a>

## DeleteDBClusterEndpointMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBClusterEndpointMessageRequestTypeDef
```

Required fields:

- `DBClusterEndpointIdentifier`: `str`

<a id="deletedbclusterendpointoutputtypedef"></a>

## DeleteDBClusterEndpointOutputTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBClusterEndpointOutputTypeDef
```

Required fields:

- `DBClusterEndpointIdentifier`: `str`
- `DBClusterIdentifier`: `str`
- `DBClusterEndpointResourceIdentifier`: `str`
- `Endpoint`: `str`
- `Status`: `str`
- `EndpointType`: `str`
- `CustomEndpointType`: `str`
- `StaticMembers`: `List`\[`str`\]
- `ExcludedMembers`: `List`\[`str`\]
- `DBClusterEndpointArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletedbclustermessagerequesttypedef"></a>

## DeleteDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`

Optional fields:

- `SkipFinalSnapshot`: `bool`
- `FinalDBSnapshotIdentifier`: `str`

<a id="deletedbclusterparametergroupmessagerequesttypedef"></a>

## DeleteDBClusterParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBClusterParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBClusterParameterGroupName`: `str`

<a id="deletedbclusterresulttypedef"></a>

## DeleteDBClusterResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBClusterResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletedbclustersnapshotmessagerequesttypedef"></a>

## DeleteDBClusterSnapshotMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBClusterSnapshotMessageRequestTypeDef
```

Required fields:

- `DBClusterSnapshotIdentifier`: `str`

<a id="deletedbclustersnapshotresulttypedef"></a>

## DeleteDBClusterSnapshotResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBClusterSnapshotResultTypeDef
```

Required fields:

- `DBClusterSnapshot`:
  [DBClusterSnapshotTypeDef](./type_defs.md#dbclustersnapshottypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletedbinstancemessagerequesttypedef"></a>

## DeleteDBInstanceMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBInstanceMessageRequestTypeDef
```

Required fields:

- `DBInstanceIdentifier`: `str`

Optional fields:

- `SkipFinalSnapshot`: `bool`
- `FinalDBSnapshotIdentifier`: `str`

<a id="deletedbinstanceresulttypedef"></a>

## DeleteDBInstanceResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBInstanceResultTypeDef
```

Required fields:

- `DBInstance`: [DBInstanceTypeDef](./type_defs.md#dbinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletedbparametergroupmessagerequesttypedef"></a>

## DeleteDBParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBParameterGroupName`: `str`

<a id="deletedbsubnetgroupmessagerequesttypedef"></a>

## DeleteDBSubnetGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteDBSubnetGroupMessageRequestTypeDef
```

Required fields:

- `DBSubnetGroupName`: `str`

<a id="deleteeventsubscriptionmessagerequesttypedef"></a>

## DeleteEventSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteEventSubscriptionMessageRequestTypeDef
```

Required fields:

- `SubscriptionName`: `str`

<a id="deleteeventsubscriptionresulttypedef"></a>

## DeleteEventSubscriptionResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DeleteEventSubscriptionResultTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedbclusterendpointsmessagerequesttypedef"></a>

## DescribeDBClusterEndpointsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBClusterEndpointsMessageRequestTypeDef
```

Optional fields:

- `DBClusterIdentifier`: `str`
- `DBClusterEndpointIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describedbclusterparametergroupsmessagerequesttypedef"></a>

## DescribeDBClusterParameterGroupsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBClusterParameterGroupsMessageRequestTypeDef
```

Optional fields:

- `DBClusterParameterGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describedbclusterparametersmessagerequesttypedef"></a>

## DescribeDBClusterParametersMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBClusterParametersMessageRequestTypeDef
```

Required fields:

- `DBClusterParameterGroupName`: `str`

Optional fields:

- `Source`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describedbclustersnapshotattributesmessagerequesttypedef"></a>

## DescribeDBClusterSnapshotAttributesMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBClusterSnapshotAttributesMessageRequestTypeDef
```

Required fields:

- `DBClusterSnapshotIdentifier`: `str`

<a id="describedbclustersnapshotattributesresulttypedef"></a>

## DescribeDBClusterSnapshotAttributesResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBClusterSnapshotAttributesResultTypeDef
```

Required fields:

- `DBClusterSnapshotAttributesResult`:
  [DBClusterSnapshotAttributesResultTypeDef](./type_defs.md#dbclustersnapshotattributesresulttypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedbclustersnapshotsmessagerequesttypedef"></a>

## DescribeDBClusterSnapshotsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBClusterSnapshotsMessageRequestTypeDef
```

Optional fields:

- `DBClusterIdentifier`: `str`
- `DBClusterSnapshotIdentifier`: `str`
- `SnapshotType`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`
- `IncludeShared`: `bool`
- `IncludePublic`: `bool`

<a id="describedbclustersmessagerequesttypedef"></a>

## DescribeDBClustersMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBClustersMessageRequestTypeDef
```

Optional fields:

- `DBClusterIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describedbengineversionsmessagerequesttypedef"></a>

## DescribeDBEngineVersionsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBEngineVersionsMessageRequestTypeDef
```

Optional fields:

- `Engine`: `str`
- `EngineVersion`: `str`
- `DBParameterGroupFamily`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`
- `DefaultOnly`: `bool`
- `ListSupportedCharacterSets`: `bool`
- `ListSupportedTimezones`: `bool`

<a id="describedbinstancesmessagerequesttypedef"></a>

## DescribeDBInstancesMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBInstancesMessageRequestTypeDef
```

Optional fields:

- `DBInstanceIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describedbparametergroupsmessagerequesttypedef"></a>

## DescribeDBParameterGroupsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBParameterGroupsMessageRequestTypeDef
```

Optional fields:

- `DBParameterGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describedbparametersmessagerequesttypedef"></a>

## DescribeDBParametersMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBParametersMessageRequestTypeDef
```

Required fields:

- `DBParameterGroupName`: `str`

Optional fields:

- `Source`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describedbsubnetgroupsmessagerequesttypedef"></a>

## DescribeDBSubnetGroupsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeDBSubnetGroupsMessageRequestTypeDef
```

Optional fields:

- `DBSubnetGroupName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeenginedefaultclusterparametersmessagerequesttypedef"></a>

## DescribeEngineDefaultClusterParametersMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeEngineDefaultClusterParametersMessageRequestTypeDef
```

Required fields:

- `DBParameterGroupFamily`: `str`

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeenginedefaultclusterparametersresulttypedef"></a>

## DescribeEngineDefaultClusterParametersResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeEngineDefaultClusterParametersResultTypeDef
```

Required fields:

- `EngineDefaults`:
  [EngineDefaultsTypeDef](./type_defs.md#enginedefaultstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeenginedefaultparametersmessagerequesttypedef"></a>

## DescribeEngineDefaultParametersMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeEngineDefaultParametersMessageRequestTypeDef
```

Required fields:

- `DBParameterGroupFamily`: `str`

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeenginedefaultparametersresulttypedef"></a>

## DescribeEngineDefaultParametersResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeEngineDefaultParametersResultTypeDef
```

Required fields:

- `EngineDefaults`:
  [EngineDefaultsTypeDef](./type_defs.md#enginedefaultstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeeventcategoriesmessagerequesttypedef"></a>

## DescribeEventCategoriesMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeEventCategoriesMessageRequestTypeDef
```

Optional fields:

- `SourceType`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="describeeventsubscriptionsmessagerequesttypedef"></a>

## DescribeEventSubscriptionsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeEventSubscriptionsMessageRequestTypeDef
```

Optional fields:

- `SubscriptionName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeeventsmessagerequesttypedef"></a>

## DescribeEventsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeEventsMessageRequestTypeDef
```

Optional fields:

- `SourceIdentifier`: `str`
- `SourceType`: [SourceTypeType](./literals.md#sourcetypetype)
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `Duration`: `int`
- `EventCategories`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeorderabledbinstanceoptionsmessagerequesttypedef"></a>

## DescribeOrderableDBInstanceOptionsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeOrderableDBInstanceOptionsMessageRequestTypeDef
```

Required fields:

- `Engine`: `str`

Optional fields:

- `EngineVersion`: `str`
- `DBInstanceClass`: `str`
- `LicenseModel`: `str`
- `Vpc`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describependingmaintenanceactionsmessagerequesttypedef"></a>

## DescribePendingMaintenanceActionsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribePendingMaintenanceActionsMessageRequestTypeDef
```

Optional fields:

- `ResourceIdentifier`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `Marker`: `str`
- `MaxRecords`: `int`

<a id="describevaliddbinstancemodificationsmessagerequesttypedef"></a>

## DescribeValidDBInstanceModificationsMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeValidDBInstanceModificationsMessageRequestTypeDef
```

Required fields:

- `DBInstanceIdentifier`: `str`

<a id="describevaliddbinstancemodificationsresulttypedef"></a>

## DescribeValidDBInstanceModificationsResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import DescribeValidDBInstanceModificationsResultTypeDef
```

Required fields:

- `ValidDBInstanceModificationsMessage`:
  [ValidDBInstanceModificationsMessageTypeDef](./type_defs.md#validdbinstancemodificationsmessagetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="domainmembershiptypedef"></a>

## DomainMembershipTypeDef

```python
from types_aiobotocore_neptune.type_defs import DomainMembershipTypeDef
```

Optional fields:

- `Domain`: `str`
- `Status`: `str`
- `FQDN`: `str`
- `IAMRoleName`: `str`

<a id="doublerangetypedef"></a>

## DoubleRangeTypeDef

```python
from types_aiobotocore_neptune.type_defs import DoubleRangeTypeDef
```

Optional fields:

- `From`: `float`
- `To`: `float`

<a id="endpointtypedef"></a>

## EndpointTypeDef

```python
from types_aiobotocore_neptune.type_defs import EndpointTypeDef
```

Optional fields:

- `Address`: `str`
- `Port`: `int`
- `HostedZoneId`: `str`

<a id="enginedefaultstypedef"></a>

## EngineDefaultsTypeDef

```python
from types_aiobotocore_neptune.type_defs import EngineDefaultsTypeDef
```

Optional fields:

- `DBParameterGroupFamily`: `str`
- `Marker`: `str`
- `Parameters`: `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

<a id="eventcategoriesmaptypedef"></a>

## EventCategoriesMapTypeDef

```python
from types_aiobotocore_neptune.type_defs import EventCategoriesMapTypeDef
```

Optional fields:

- `SourceType`: `str`
- `EventCategories`: `List`\[`str`\]

<a id="eventcategoriesmessagetypedef"></a>

## EventCategoriesMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import EventCategoriesMessageTypeDef
```

Required fields:

- `EventCategoriesMapList`:
  `List`\[[EventCategoriesMapTypeDef](./type_defs.md#eventcategoriesmaptypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="eventsubscriptiontypedef"></a>

## EventSubscriptionTypeDef

```python
from types_aiobotocore_neptune.type_defs import EventSubscriptionTypeDef
```

Optional fields:

- `CustomerAwsId`: `str`
- `CustSubscriptionId`: `str`
- `SnsTopicArn`: `str`
- `Status`: `str`
- `SubscriptionCreationTime`: `str`
- `SourceType`: `str`
- `SourceIdsList`: `List`\[`str`\]
- `EventCategoriesList`: `List`\[`str`\]
- `Enabled`: `bool`
- `EventSubscriptionArn`: `str`

<a id="eventsubscriptionsmessagetypedef"></a>

## EventSubscriptionsMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import EventSubscriptionsMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `EventSubscriptionsList`:
  `List`\[[EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="eventtypedef"></a>

## EventTypeDef

```python
from types_aiobotocore_neptune.type_defs import EventTypeDef
```

Optional fields:

- `SourceIdentifier`: `str`
- `SourceType`: [SourceTypeType](./literals.md#sourcetypetype)
- `Message`: `str`
- `EventCategories`: `List`\[`str`\]
- `Date`: `datetime`
- `SourceArn`: `str`

<a id="eventsmessagetypedef"></a>

## EventsMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import EventsMessageTypeDef
```

Required fields:

- `Marker`: `str`
- `Events`: `List`\[[EventTypeDef](./type_defs.md#eventtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="failoverdbclustermessagerequesttypedef"></a>

## FailoverDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import FailoverDBClusterMessageRequestTypeDef
```

Optional fields:

- `DBClusterIdentifier`: `str`
- `TargetDBInstanceIdentifier`: `str`

<a id="failoverdbclusterresulttypedef"></a>

## FailoverDBClusterResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import FailoverDBClusterResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="filtertypedef"></a>

## FilterTypeDef

```python
from types_aiobotocore_neptune.type_defs import FilterTypeDef
```

Required fields:

- `Name`: `str`
- `Values`: `Sequence`\[`str`\]

<a id="listtagsforresourcemessagerequesttypedef"></a>

## ListTagsForResourceMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ListTagsForResourceMessageRequestTypeDef
```

Required fields:

- `ResourceName`: `str`

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="modifydbclusterendpointmessagerequesttypedef"></a>

## ModifyDBClusterEndpointMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBClusterEndpointMessageRequestTypeDef
```

Required fields:

- `DBClusterEndpointIdentifier`: `str`

Optional fields:

- `EndpointType`: `str`
- `StaticMembers`: `Sequence`\[`str`\]
- `ExcludedMembers`: `Sequence`\[`str`\]

<a id="modifydbclusterendpointoutputtypedef"></a>

## ModifyDBClusterEndpointOutputTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBClusterEndpointOutputTypeDef
```

Required fields:

- `DBClusterEndpointIdentifier`: `str`
- `DBClusterIdentifier`: `str`
- `DBClusterEndpointResourceIdentifier`: `str`
- `Endpoint`: `str`
- `Status`: `str`
- `EndpointType`: `str`
- `CustomEndpointType`: `str`
- `StaticMembers`: `List`\[`str`\]
- `ExcludedMembers`: `List`\[`str`\]
- `DBClusterEndpointArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifydbclustermessagerequesttypedef"></a>

## ModifyDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`

Optional fields:

- `NewDBClusterIdentifier`: `str`
- `ApplyImmediately`: `bool`
- `BackupRetentionPeriod`: `int`
- `DBClusterParameterGroupName`: `str`
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `Port`: `int`
- `MasterUserPassword`: `str`
- `OptionGroupName`: `str`
- `PreferredBackupWindow`: `str`
- `PreferredMaintenanceWindow`: `str`
- `EnableIAMDatabaseAuthentication`: `bool`
- `CloudwatchLogsExportConfiguration`:
  [CloudwatchLogsExportConfigurationTypeDef](./type_defs.md#cloudwatchlogsexportconfigurationtypedef)
- `EngineVersion`: `str`
- `AllowMajorVersionUpgrade`: `bool`
- `DBInstanceParameterGroupName`: `str`
- `DeletionProtection`: `bool`
- `CopyTagsToSnapshot`: `bool`

<a id="modifydbclusterparametergroupmessagerequesttypedef"></a>

## ModifyDBClusterParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBClusterParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBClusterParameterGroupName`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

<a id="modifydbclusterresulttypedef"></a>

## ModifyDBClusterResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBClusterResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifydbclustersnapshotattributemessagerequesttypedef"></a>

## ModifyDBClusterSnapshotAttributeMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBClusterSnapshotAttributeMessageRequestTypeDef
```

Required fields:

- `DBClusterSnapshotIdentifier`: `str`
- `AttributeName`: `str`

Optional fields:

- `ValuesToAdd`: `Sequence`\[`str`\]
- `ValuesToRemove`: `Sequence`\[`str`\]

<a id="modifydbclustersnapshotattributeresulttypedef"></a>

## ModifyDBClusterSnapshotAttributeResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBClusterSnapshotAttributeResultTypeDef
```

Required fields:

- `DBClusterSnapshotAttributesResult`:
  [DBClusterSnapshotAttributesResultTypeDef](./type_defs.md#dbclustersnapshotattributesresulttypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifydbinstancemessagerequesttypedef"></a>

## ModifyDBInstanceMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBInstanceMessageRequestTypeDef
```

Required fields:

- `DBInstanceIdentifier`: `str`

Optional fields:

- `AllocatedStorage`: `int`
- `DBInstanceClass`: `str`
- `DBSubnetGroupName`: `str`
- `DBSecurityGroups`: `Sequence`\[`str`\]
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `ApplyImmediately`: `bool`
- `MasterUserPassword`: `str`
- `DBParameterGroupName`: `str`
- `BackupRetentionPeriod`: `int`
- `PreferredBackupWindow`: `str`
- `PreferredMaintenanceWindow`: `str`
- `MultiAZ`: `bool`
- `EngineVersion`: `str`
- `AllowMajorVersionUpgrade`: `bool`
- `AutoMinorVersionUpgrade`: `bool`
- `LicenseModel`: `str`
- `Iops`: `int`
- `OptionGroupName`: `str`
- `NewDBInstanceIdentifier`: `str`
- `StorageType`: `str`
- `TdeCredentialArn`: `str`
- `TdeCredentialPassword`: `str`
- `CACertificateIdentifier`: `str`
- `Domain`: `str`
- `CopyTagsToSnapshot`: `bool`
- `MonitoringInterval`: `int`
- `DBPortNumber`: `int`
- `PubliclyAccessible`: `bool`
- `MonitoringRoleArn`: `str`
- `DomainIAMRoleName`: `str`
- `PromotionTier`: `int`
- `EnableIAMDatabaseAuthentication`: `bool`
- `EnablePerformanceInsights`: `bool`
- `PerformanceInsightsKMSKeyId`: `str`
- `CloudwatchLogsExportConfiguration`:
  [CloudwatchLogsExportConfigurationTypeDef](./type_defs.md#cloudwatchlogsexportconfigurationtypedef)
- `DeletionProtection`: `bool`

<a id="modifydbinstanceresulttypedef"></a>

## ModifyDBInstanceResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBInstanceResultTypeDef
```

Required fields:

- `DBInstance`: [DBInstanceTypeDef](./type_defs.md#dbinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifydbparametergroupmessagerequesttypedef"></a>

## ModifyDBParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBParameterGroupName`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

<a id="modifydbsubnetgroupmessagerequesttypedef"></a>

## ModifyDBSubnetGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBSubnetGroupMessageRequestTypeDef
```

Required fields:

- `DBSubnetGroupName`: `str`
- `SubnetIds`: `Sequence`\[`str`\]

Optional fields:

- `DBSubnetGroupDescription`: `str`

<a id="modifydbsubnetgroupresulttypedef"></a>

## ModifyDBSubnetGroupResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyDBSubnetGroupResultTypeDef
```

Required fields:

- `DBSubnetGroup`: [DBSubnetGroupTypeDef](./type_defs.md#dbsubnetgrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifyeventsubscriptionmessagerequesttypedef"></a>

## ModifyEventSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyEventSubscriptionMessageRequestTypeDef
```

Required fields:

- `SubscriptionName`: `str`

Optional fields:

- `SnsTopicArn`: `str`
- `SourceType`: `str`
- `EventCategories`: `Sequence`\[`str`\]
- `Enabled`: `bool`

<a id="modifyeventsubscriptionresulttypedef"></a>

## ModifyEventSubscriptionResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import ModifyEventSubscriptionResultTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="optiongroupmembershiptypedef"></a>

## OptionGroupMembershipTypeDef

```python
from types_aiobotocore_neptune.type_defs import OptionGroupMembershipTypeDef
```

Optional fields:

- `OptionGroupName`: `str`
- `Status`: `str`

<a id="orderabledbinstanceoptiontypedef"></a>

## OrderableDBInstanceOptionTypeDef

```python
from types_aiobotocore_neptune.type_defs import OrderableDBInstanceOptionTypeDef
```

Optional fields:

- `Engine`: `str`
- `EngineVersion`: `str`
- `DBInstanceClass`: `str`
- `LicenseModel`: `str`
- `AvailabilityZones`:
  `List`\[[AvailabilityZoneTypeDef](./type_defs.md#availabilityzonetypedef)\]
- `MultiAZCapable`: `bool`
- `ReadReplicaCapable`: `bool`
- `Vpc`: `bool`
- `SupportsStorageEncryption`: `bool`
- `StorageType`: `str`
- `SupportsIops`: `bool`
- `SupportsEnhancedMonitoring`: `bool`
- `SupportsIAMDatabaseAuthentication`: `bool`
- `SupportsPerformanceInsights`: `bool`
- `MinStorageSize`: `int`
- `MaxStorageSize`: `int`
- `MinIopsPerDbInstance`: `int`
- `MaxIopsPerDbInstance`: `int`
- `MinIopsPerGib`: `float`
- `MaxIopsPerGib`: `float`

<a id="orderabledbinstanceoptionsmessagetypedef"></a>

## OrderableDBInstanceOptionsMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import OrderableDBInstanceOptionsMessageTypeDef
```

Required fields:

- `OrderableDBInstanceOptions`:
  `List`\[[OrderableDBInstanceOptionTypeDef](./type_defs.md#orderabledbinstanceoptiontypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_neptune.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="parametertypedef"></a>

## ParameterTypeDef

```python
from types_aiobotocore_neptune.type_defs import ParameterTypeDef
```

Optional fields:

- `ParameterName`: `str`
- `ParameterValue`: `str`
- `Description`: `str`
- `Source`: `str`
- `ApplyType`: `str`
- `DataType`: `str`
- `AllowedValues`: `str`
- `IsModifiable`: `bool`
- `MinimumEngineVersion`: `str`
- `ApplyMethod`: [ApplyMethodType](./literals.md#applymethodtype)

<a id="pendingcloudwatchlogsexportstypedef"></a>

## PendingCloudwatchLogsExportsTypeDef

```python
from types_aiobotocore_neptune.type_defs import PendingCloudwatchLogsExportsTypeDef
```

Optional fields:

- `LogTypesToEnable`: `List`\[`str`\]
- `LogTypesToDisable`: `List`\[`str`\]

<a id="pendingmaintenanceactiontypedef"></a>

## PendingMaintenanceActionTypeDef

```python
from types_aiobotocore_neptune.type_defs import PendingMaintenanceActionTypeDef
```

Optional fields:

- `Action`: `str`
- `AutoAppliedAfterDate`: `datetime`
- `ForcedApplyDate`: `datetime`
- `OptInStatus`: `str`
- `CurrentApplyDate`: `datetime`
- `Description`: `str`

<a id="pendingmaintenanceactionsmessagetypedef"></a>

## PendingMaintenanceActionsMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import PendingMaintenanceActionsMessageTypeDef
```

Required fields:

- `PendingMaintenanceActions`:
  `List`\[[ResourcePendingMaintenanceActionsTypeDef](./type_defs.md#resourcependingmaintenanceactionstypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="pendingmodifiedvaluestypedef"></a>

## PendingModifiedValuesTypeDef

```python
from types_aiobotocore_neptune.type_defs import PendingModifiedValuesTypeDef
```

Optional fields:

- `DBInstanceClass`: `str`
- `AllocatedStorage`: `int`
- `MasterUserPassword`: `str`
- `Port`: `int`
- `BackupRetentionPeriod`: `int`
- `MultiAZ`: `bool`
- `EngineVersion`: `str`
- `LicenseModel`: `str`
- `Iops`: `int`
- `DBInstanceIdentifier`: `str`
- `StorageType`: `str`
- `CACertificateIdentifier`: `str`
- `DBSubnetGroupName`: `str`
- `PendingCloudwatchLogsExports`:
  [PendingCloudwatchLogsExportsTypeDef](./type_defs.md#pendingcloudwatchlogsexportstypedef)

<a id="promotereadreplicadbclustermessagerequesttypedef"></a>

## PromoteReadReplicaDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import PromoteReadReplicaDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`

<a id="promotereadreplicadbclusterresulttypedef"></a>

## PromoteReadReplicaDBClusterResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import PromoteReadReplicaDBClusterResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="rangetypedef"></a>

## RangeTypeDef

```python
from types_aiobotocore_neptune.type_defs import RangeTypeDef
```

Optional fields:

- `From`: `int`
- `To`: `int`
- `Step`: `int`

<a id="rebootdbinstancemessagerequesttypedef"></a>

## RebootDBInstanceMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import RebootDBInstanceMessageRequestTypeDef
```

Required fields:

- `DBInstanceIdentifier`: `str`

Optional fields:

- `ForceFailover`: `bool`

<a id="rebootdbinstanceresulttypedef"></a>

## RebootDBInstanceResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import RebootDBInstanceResultTypeDef
```

Required fields:

- `DBInstance`: [DBInstanceTypeDef](./type_defs.md#dbinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="removerolefromdbclustermessagerequesttypedef"></a>

## RemoveRoleFromDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import RemoveRoleFromDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`
- `RoleArn`: `str`

Optional fields:

- `FeatureName`: `str`

<a id="removesourceidentifierfromsubscriptionmessagerequesttypedef"></a>

## RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef
```

Required fields:

- `SubscriptionName`: `str`
- `SourceIdentifier`: `str`

<a id="removesourceidentifierfromsubscriptionresulttypedef"></a>

## RemoveSourceIdentifierFromSubscriptionResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import RemoveSourceIdentifierFromSubscriptionResultTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="removetagsfromresourcemessagerequesttypedef"></a>

## RemoveTagsFromResourceMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import RemoveTagsFromResourceMessageRequestTypeDef
```

Required fields:

- `ResourceName`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="resetdbclusterparametergroupmessagerequesttypedef"></a>

## ResetDBClusterParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ResetDBClusterParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBClusterParameterGroupName`: `str`

Optional fields:

- `ResetAllParameters`: `bool`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

<a id="resetdbparametergroupmessagerequesttypedef"></a>

## ResetDBParameterGroupMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import ResetDBParameterGroupMessageRequestTypeDef
```

Required fields:

- `DBParameterGroupName`: `str`

Optional fields:

- `ResetAllParameters`: `bool`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

<a id="resourcependingmaintenanceactionstypedef"></a>

## ResourcePendingMaintenanceActionsTypeDef

```python
from types_aiobotocore_neptune.type_defs import ResourcePendingMaintenanceActionsTypeDef
```

Optional fields:

- `ResourceIdentifier`: `str`
- `PendingMaintenanceActionDetails`:
  `List`\[[PendingMaintenanceActionTypeDef](./type_defs.md#pendingmaintenanceactiontypedef)\]

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_neptune.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="restoredbclusterfromsnapshotmessagerequesttypedef"></a>

## RestoreDBClusterFromSnapshotMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import RestoreDBClusterFromSnapshotMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`
- `SnapshotIdentifier`: `str`
- `Engine`: `str`

Optional fields:

- `AvailabilityZones`: `Sequence`\[`str`\]
- `EngineVersion`: `str`
- `Port`: `int`
- `DBSubnetGroupName`: `str`
- `DatabaseName`: `str`
- `OptionGroupName`: `str`
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `KmsKeyId`: `str`
- `EnableIAMDatabaseAuthentication`: `bool`
- `EnableCloudwatchLogsExports`: `Sequence`\[`str`\]
- `DBClusterParameterGroupName`: `str`
- `DeletionProtection`: `bool`
- `CopyTagsToSnapshot`: `bool`

<a id="restoredbclusterfromsnapshotresulttypedef"></a>

## RestoreDBClusterFromSnapshotResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import RestoreDBClusterFromSnapshotResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="restoredbclustertopointintimemessagerequesttypedef"></a>

## RestoreDBClusterToPointInTimeMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import RestoreDBClusterToPointInTimeMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`
- `SourceDBClusterIdentifier`: `str`

Optional fields:

- `RestoreType`: `str`
- `RestoreToTime`: `Union`\[`datetime`, `str`\]
- `UseLatestRestorableTime`: `bool`
- `Port`: `int`
- `DBSubnetGroupName`: `str`
- `OptionGroupName`: `str`
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `KmsKeyId`: `str`
- `EnableIAMDatabaseAuthentication`: `bool`
- `EnableCloudwatchLogsExports`: `Sequence`\[`str`\]
- `DBClusterParameterGroupName`: `str`
- `DeletionProtection`: `bool`

<a id="restoredbclustertopointintimeresulttypedef"></a>

## RestoreDBClusterToPointInTimeResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import RestoreDBClusterToPointInTimeResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startdbclustermessagerequesttypedef"></a>

## StartDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import StartDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`

<a id="startdbclusterresulttypedef"></a>

## StartDBClusterResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import StartDBClusterResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopdbclustermessagerequesttypedef"></a>

## StopDBClusterMessageRequestTypeDef

```python
from types_aiobotocore_neptune.type_defs import StopDBClusterMessageRequestTypeDef
```

Required fields:

- `DBClusterIdentifier`: `str`

<a id="stopdbclusterresulttypedef"></a>

## StopDBClusterResultTypeDef

```python
from types_aiobotocore_neptune.type_defs import StopDBClusterResultTypeDef
```

Required fields:

- `DBCluster`: [DBClusterTypeDef](./type_defs.md#dbclustertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="subnettypedef"></a>

## SubnetTypeDef

```python
from types_aiobotocore_neptune.type_defs import SubnetTypeDef
```

Optional fields:

- `SubnetIdentifier`: `str`
- `SubnetAvailabilityZone`:
  [AvailabilityZoneTypeDef](./type_defs.md#availabilityzonetypedef)
- `SubnetStatus`: `str`

<a id="taglistmessagetypedef"></a>

## TagListMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import TagListMessageTypeDef
```

Required fields:

- `TagList`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_neptune.type_defs import TagTypeDef
```

Optional fields:

- `Key`: `str`
- `Value`: `str`

<a id="timezonetypedef"></a>

## TimezoneTypeDef

```python
from types_aiobotocore_neptune.type_defs import TimezoneTypeDef
```

Optional fields:

- `TimezoneName`: `str`

<a id="upgradetargettypedef"></a>

## UpgradeTargetTypeDef

```python
from types_aiobotocore_neptune.type_defs import UpgradeTargetTypeDef
```

Optional fields:

- `Engine`: `str`
- `EngineVersion`: `str`
- `Description`: `str`
- `AutoUpgrade`: `bool`
- `IsMajorVersionUpgrade`: `bool`

<a id="validdbinstancemodificationsmessagetypedef"></a>

## ValidDBInstanceModificationsMessageTypeDef

```python
from types_aiobotocore_neptune.type_defs import ValidDBInstanceModificationsMessageTypeDef
```

Optional fields:

- `Storage`:
  `List`\[[ValidStorageOptionsTypeDef](./type_defs.md#validstorageoptionstypedef)\]

<a id="validstorageoptionstypedef"></a>

## ValidStorageOptionsTypeDef

```python
from types_aiobotocore_neptune.type_defs import ValidStorageOptionsTypeDef
```

Optional fields:

- `StorageType`: `str`
- `StorageSize`: `List`\[[RangeTypeDef](./type_defs.md#rangetypedef)\]
- `ProvisionedIops`: `List`\[[RangeTypeDef](./type_defs.md#rangetypedef)\]
- `IopsToStorageRatio`:
  `List`\[[DoubleRangeTypeDef](./type_defs.md#doublerangetypedef)\]

<a id="vpcsecuritygroupmembershiptypedef"></a>

## VpcSecurityGroupMembershipTypeDef

```python
from types_aiobotocore_neptune.type_defs import VpcSecurityGroupMembershipTypeDef
```

Optional fields:

- `VpcSecurityGroupId`: `str`
- `Status`: `str`

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_neptune.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`
