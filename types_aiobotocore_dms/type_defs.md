<a id="typed-dictionaries-for-aiobotocore-databasemigrationservice-module"></a>

# Typed dictionaries for aiobotocore DatabaseMigrationService module

> [Index](..) > [DatabaseMigrationService](.) > Typed dictionaries

Auto-generated documentation for
[DatabaseMigrationService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
type annotations stubs module
[types-aiobotocore-dms](https://pypi.org/project/types-aiobotocore-dms/).

- [Typed dictionaries for aiobotocore DatabaseMigrationService module](#typed-dictionaries-for-aiobotocore-databasemigrationservice-module)
  - [AccountQuotaTypeDef](#accountquotatypedef)
  - [AddTagsToResourceMessageRequestTypeDef](#addtagstoresourcemessagerequesttypedef)
  - [ApplyPendingMaintenanceActionMessageRequestTypeDef](#applypendingmaintenanceactionmessagerequesttypedef)
  - [ApplyPendingMaintenanceActionResponseTypeDef](#applypendingmaintenanceactionresponsetypedef)
  - [AvailabilityZoneTypeDef](#availabilityzonetypedef)
  - [CancelReplicationTaskAssessmentRunMessageRequestTypeDef](#cancelreplicationtaskassessmentrunmessagerequesttypedef)
  - [CancelReplicationTaskAssessmentRunResponseTypeDef](#cancelreplicationtaskassessmentrunresponsetypedef)
  - [CertificateTypeDef](#certificatetypedef)
  - [ConnectionTypeDef](#connectiontypedef)
  - [CreateEndpointMessageRequestTypeDef](#createendpointmessagerequesttypedef)
  - [CreateEndpointResponseTypeDef](#createendpointresponsetypedef)
  - [CreateEventSubscriptionMessageRequestTypeDef](#createeventsubscriptionmessagerequesttypedef)
  - [CreateEventSubscriptionResponseTypeDef](#createeventsubscriptionresponsetypedef)
  - [CreateReplicationInstanceMessageRequestTypeDef](#createreplicationinstancemessagerequesttypedef)
  - [CreateReplicationInstanceResponseTypeDef](#createreplicationinstanceresponsetypedef)
  - [CreateReplicationSubnetGroupMessageRequestTypeDef](#createreplicationsubnetgroupmessagerequesttypedef)
  - [CreateReplicationSubnetGroupResponseTypeDef](#createreplicationsubnetgroupresponsetypedef)
  - [CreateReplicationTaskMessageRequestTypeDef](#createreplicationtaskmessagerequesttypedef)
  - [CreateReplicationTaskResponseTypeDef](#createreplicationtaskresponsetypedef)
  - [DeleteCertificateMessageRequestTypeDef](#deletecertificatemessagerequesttypedef)
  - [DeleteCertificateResponseTypeDef](#deletecertificateresponsetypedef)
  - [DeleteConnectionMessageRequestTypeDef](#deleteconnectionmessagerequesttypedef)
  - [DeleteConnectionResponseTypeDef](#deleteconnectionresponsetypedef)
  - [DeleteEndpointMessageRequestTypeDef](#deleteendpointmessagerequesttypedef)
  - [DeleteEndpointResponseTypeDef](#deleteendpointresponsetypedef)
  - [DeleteEventSubscriptionMessageRequestTypeDef](#deleteeventsubscriptionmessagerequesttypedef)
  - [DeleteEventSubscriptionResponseTypeDef](#deleteeventsubscriptionresponsetypedef)
  - [DeleteReplicationInstanceMessageRequestTypeDef](#deletereplicationinstancemessagerequesttypedef)
  - [DeleteReplicationInstanceResponseTypeDef](#deletereplicationinstanceresponsetypedef)
  - [DeleteReplicationSubnetGroupMessageRequestTypeDef](#deletereplicationsubnetgroupmessagerequesttypedef)
  - [DeleteReplicationTaskAssessmentRunMessageRequestTypeDef](#deletereplicationtaskassessmentrunmessagerequesttypedef)
  - [DeleteReplicationTaskAssessmentRunResponseTypeDef](#deletereplicationtaskassessmentrunresponsetypedef)
  - [DeleteReplicationTaskMessageRequestTypeDef](#deletereplicationtaskmessagerequesttypedef)
  - [DeleteReplicationTaskResponseTypeDef](#deletereplicationtaskresponsetypedef)
  - [DescribeAccountAttributesResponseTypeDef](#describeaccountattributesresponsetypedef)
  - [DescribeApplicableIndividualAssessmentsMessageRequestTypeDef](#describeapplicableindividualassessmentsmessagerequesttypedef)
  - [DescribeApplicableIndividualAssessmentsResponseTypeDef](#describeapplicableindividualassessmentsresponsetypedef)
  - [DescribeCertificatesMessageRequestTypeDef](#describecertificatesmessagerequesttypedef)
  - [DescribeCertificatesResponseTypeDef](#describecertificatesresponsetypedef)
  - [DescribeConnectionsMessageRequestTypeDef](#describeconnectionsmessagerequesttypedef)
  - [DescribeConnectionsResponseTypeDef](#describeconnectionsresponsetypedef)
  - [DescribeEndpointSettingsMessageRequestTypeDef](#describeendpointsettingsmessagerequesttypedef)
  - [DescribeEndpointSettingsResponseTypeDef](#describeendpointsettingsresponsetypedef)
  - [DescribeEndpointTypesMessageRequestTypeDef](#describeendpointtypesmessagerequesttypedef)
  - [DescribeEndpointTypesResponseTypeDef](#describeendpointtypesresponsetypedef)
  - [DescribeEndpointsMessageRequestTypeDef](#describeendpointsmessagerequesttypedef)
  - [DescribeEndpointsResponseTypeDef](#describeendpointsresponsetypedef)
  - [DescribeEventCategoriesMessageRequestTypeDef](#describeeventcategoriesmessagerequesttypedef)
  - [DescribeEventCategoriesResponseTypeDef](#describeeventcategoriesresponsetypedef)
  - [DescribeEventSubscriptionsMessageRequestTypeDef](#describeeventsubscriptionsmessagerequesttypedef)
  - [DescribeEventSubscriptionsResponseTypeDef](#describeeventsubscriptionsresponsetypedef)
  - [DescribeEventsMessageRequestTypeDef](#describeeventsmessagerequesttypedef)
  - [DescribeEventsResponseTypeDef](#describeeventsresponsetypedef)
  - [DescribeOrderableReplicationInstancesMessageRequestTypeDef](#describeorderablereplicationinstancesmessagerequesttypedef)
  - [DescribeOrderableReplicationInstancesResponseTypeDef](#describeorderablereplicationinstancesresponsetypedef)
  - [DescribePendingMaintenanceActionsMessageRequestTypeDef](#describependingmaintenanceactionsmessagerequesttypedef)
  - [DescribePendingMaintenanceActionsResponseTypeDef](#describependingmaintenanceactionsresponsetypedef)
  - [DescribeRefreshSchemasStatusMessageRequestTypeDef](#describerefreshschemasstatusmessagerequesttypedef)
  - [DescribeRefreshSchemasStatusResponseTypeDef](#describerefreshschemasstatusresponsetypedef)
  - [DescribeReplicationInstanceTaskLogsMessageRequestTypeDef](#describereplicationinstancetasklogsmessagerequesttypedef)
  - [DescribeReplicationInstanceTaskLogsResponseTypeDef](#describereplicationinstancetasklogsresponsetypedef)
  - [DescribeReplicationInstancesMessageRequestTypeDef](#describereplicationinstancesmessagerequesttypedef)
  - [DescribeReplicationInstancesResponseTypeDef](#describereplicationinstancesresponsetypedef)
  - [DescribeReplicationSubnetGroupsMessageRequestTypeDef](#describereplicationsubnetgroupsmessagerequesttypedef)
  - [DescribeReplicationSubnetGroupsResponseTypeDef](#describereplicationsubnetgroupsresponsetypedef)
  - [DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef](#describereplicationtaskassessmentresultsmessagerequesttypedef)
  - [DescribeReplicationTaskAssessmentResultsResponseTypeDef](#describereplicationtaskassessmentresultsresponsetypedef)
  - [DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef](#describereplicationtaskassessmentrunsmessagerequesttypedef)
  - [DescribeReplicationTaskAssessmentRunsResponseTypeDef](#describereplicationtaskassessmentrunsresponsetypedef)
  - [DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef](#describereplicationtaskindividualassessmentsmessagerequesttypedef)
  - [DescribeReplicationTaskIndividualAssessmentsResponseTypeDef](#describereplicationtaskindividualassessmentsresponsetypedef)
  - [DescribeReplicationTasksMessageRequestTypeDef](#describereplicationtasksmessagerequesttypedef)
  - [DescribeReplicationTasksResponseTypeDef](#describereplicationtasksresponsetypedef)
  - [DescribeSchemasMessageRequestTypeDef](#describeschemasmessagerequesttypedef)
  - [DescribeSchemasResponseTypeDef](#describeschemasresponsetypedef)
  - [DescribeTableStatisticsMessageRequestTypeDef](#describetablestatisticsmessagerequesttypedef)
  - [DescribeTableStatisticsResponseTypeDef](#describetablestatisticsresponsetypedef)
  - [DmsTransferSettingsTypeDef](#dmstransfersettingstypedef)
  - [DocDbSettingsTypeDef](#docdbsettingstypedef)
  - [DynamoDbSettingsTypeDef](#dynamodbsettingstypedef)
  - [ElasticsearchSettingsTypeDef](#elasticsearchsettingstypedef)
  - [EndpointSettingTypeDef](#endpointsettingtypedef)
  - [EndpointTypeDef](#endpointtypedef)
  - [EventCategoryGroupTypeDef](#eventcategorygrouptypedef)
  - [EventSubscriptionTypeDef](#eventsubscriptiontypedef)
  - [EventTypeDef](#eventtypedef)
  - [FilterTypeDef](#filtertypedef)
  - [GcpMySQLSettingsTypeDef](#gcpmysqlsettingstypedef)
  - [IBMDb2SettingsTypeDef](#ibmdb2settingstypedef)
  - [ImportCertificateMessageRequestTypeDef](#importcertificatemessagerequesttypedef)
  - [ImportCertificateResponseTypeDef](#importcertificateresponsetypedef)
  - [KafkaSettingsTypeDef](#kafkasettingstypedef)
  - [KinesisSettingsTypeDef](#kinesissettingstypedef)
  - [ListTagsForResourceMessageRequestTypeDef](#listtagsforresourcemessagerequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [MicrosoftSQLServerSettingsTypeDef](#microsoftsqlserversettingstypedef)
  - [ModifyEndpointMessageRequestTypeDef](#modifyendpointmessagerequesttypedef)
  - [ModifyEndpointResponseTypeDef](#modifyendpointresponsetypedef)
  - [ModifyEventSubscriptionMessageRequestTypeDef](#modifyeventsubscriptionmessagerequesttypedef)
  - [ModifyEventSubscriptionResponseTypeDef](#modifyeventsubscriptionresponsetypedef)
  - [ModifyReplicationInstanceMessageRequestTypeDef](#modifyreplicationinstancemessagerequesttypedef)
  - [ModifyReplicationInstanceResponseTypeDef](#modifyreplicationinstanceresponsetypedef)
  - [ModifyReplicationSubnetGroupMessageRequestTypeDef](#modifyreplicationsubnetgroupmessagerequesttypedef)
  - [ModifyReplicationSubnetGroupResponseTypeDef](#modifyreplicationsubnetgroupresponsetypedef)
  - [ModifyReplicationTaskMessageRequestTypeDef](#modifyreplicationtaskmessagerequesttypedef)
  - [ModifyReplicationTaskResponseTypeDef](#modifyreplicationtaskresponsetypedef)
  - [MongoDbSettingsTypeDef](#mongodbsettingstypedef)
  - [MoveReplicationTaskMessageRequestTypeDef](#movereplicationtaskmessagerequesttypedef)
  - [MoveReplicationTaskResponseTypeDef](#movereplicationtaskresponsetypedef)
  - [MySQLSettingsTypeDef](#mysqlsettingstypedef)
  - [NeptuneSettingsTypeDef](#neptunesettingstypedef)
  - [OracleSettingsTypeDef](#oraclesettingstypedef)
  - [OrderableReplicationInstanceTypeDef](#orderablereplicationinstancetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PendingMaintenanceActionTypeDef](#pendingmaintenanceactiontypedef)
  - [PostgreSQLSettingsTypeDef](#postgresqlsettingstypedef)
  - [RebootReplicationInstanceMessageRequestTypeDef](#rebootreplicationinstancemessagerequesttypedef)
  - [RebootReplicationInstanceResponseTypeDef](#rebootreplicationinstanceresponsetypedef)
  - [RedisSettingsTypeDef](#redissettingstypedef)
  - [RedshiftSettingsTypeDef](#redshiftsettingstypedef)
  - [RefreshSchemasMessageRequestTypeDef](#refreshschemasmessagerequesttypedef)
  - [RefreshSchemasResponseTypeDef](#refreshschemasresponsetypedef)
  - [RefreshSchemasStatusTypeDef](#refreshschemasstatustypedef)
  - [ReloadTablesMessageRequestTypeDef](#reloadtablesmessagerequesttypedef)
  - [ReloadTablesResponseTypeDef](#reloadtablesresponsetypedef)
  - [RemoveTagsFromResourceMessageRequestTypeDef](#removetagsfromresourcemessagerequesttypedef)
  - [ReplicationInstanceTaskLogTypeDef](#replicationinstancetasklogtypedef)
  - [ReplicationInstanceTypeDef](#replicationinstancetypedef)
  - [ReplicationPendingModifiedValuesTypeDef](#replicationpendingmodifiedvaluestypedef)
  - [ReplicationSubnetGroupTypeDef](#replicationsubnetgrouptypedef)
  - [ReplicationTaskAssessmentResultTypeDef](#replicationtaskassessmentresulttypedef)
  - [ReplicationTaskAssessmentRunProgressTypeDef](#replicationtaskassessmentrunprogresstypedef)
  - [ReplicationTaskAssessmentRunTypeDef](#replicationtaskassessmentruntypedef)
  - [ReplicationTaskIndividualAssessmentTypeDef](#replicationtaskindividualassessmenttypedef)
  - [ReplicationTaskStatsTypeDef](#replicationtaskstatstypedef)
  - [ReplicationTaskTypeDef](#replicationtasktypedef)
  - [ResourcePendingMaintenanceActionsTypeDef](#resourcependingmaintenanceactionstypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3SettingsTypeDef](#s3settingstypedef)
  - [StartReplicationTaskAssessmentMessageRequestTypeDef](#startreplicationtaskassessmentmessagerequesttypedef)
  - [StartReplicationTaskAssessmentResponseTypeDef](#startreplicationtaskassessmentresponsetypedef)
  - [StartReplicationTaskAssessmentRunMessageRequestTypeDef](#startreplicationtaskassessmentrunmessagerequesttypedef)
  - [StartReplicationTaskAssessmentRunResponseTypeDef](#startreplicationtaskassessmentrunresponsetypedef)
  - [StartReplicationTaskMessageRequestTypeDef](#startreplicationtaskmessagerequesttypedef)
  - [StartReplicationTaskResponseTypeDef](#startreplicationtaskresponsetypedef)
  - [StopReplicationTaskMessageRequestTypeDef](#stopreplicationtaskmessagerequesttypedef)
  - [StopReplicationTaskResponseTypeDef](#stopreplicationtaskresponsetypedef)
  - [SubnetTypeDef](#subnettypedef)
  - [SupportedEndpointTypeTypeDef](#supportedendpointtypetypedef)
  - [SybaseSettingsTypeDef](#sybasesettingstypedef)
  - [TableStatisticsTypeDef](#tablestatisticstypedef)
  - [TableToReloadTypeDef](#tabletoreloadtypedef)
  - [TagTypeDef](#tagtypedef)
  - [TestConnectionMessageRequestTypeDef](#testconnectionmessagerequesttypedef)
  - [TestConnectionResponseTypeDef](#testconnectionresponsetypedef)
  - [VpcSecurityGroupMembershipTypeDef](#vpcsecuritygroupmembershiptypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)

<a id="accountquotatypedef"></a>

## AccountQuotaTypeDef

```python
from types_aiobotocore_dms.type_defs import AccountQuotaTypeDef
```

Optional fields:

- `AccountQuotaName`: `str`
- `Used`: `int`
- `Max`: `int`

<a id="addtagstoresourcemessagerequesttypedef"></a>

## AddTagsToResourceMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import AddTagsToResourceMessageRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="applypendingmaintenanceactionmessagerequesttypedef"></a>

## ApplyPendingMaintenanceActionMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ApplyPendingMaintenanceActionMessageRequestTypeDef
```

Required fields:

- `ReplicationInstanceArn`: `str`
- `ApplyAction`: `str`
- `OptInType`: `str`

<a id="applypendingmaintenanceactionresponsetypedef"></a>

## ApplyPendingMaintenanceActionResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ApplyPendingMaintenanceActionResponseTypeDef
```

Required fields:

- `ResourcePendingMaintenanceActions`:
  [ResourcePendingMaintenanceActionsTypeDef](./type_defs.md#resourcependingmaintenanceactionstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="availabilityzonetypedef"></a>

## AvailabilityZoneTypeDef

```python
from types_aiobotocore_dms.type_defs import AvailabilityZoneTypeDef
```

Optional fields:

- `Name`: `str`

<a id="cancelreplicationtaskassessmentrunmessagerequesttypedef"></a>

## CancelReplicationTaskAssessmentRunMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import CancelReplicationTaskAssessmentRunMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskAssessmentRunArn`: `str`

<a id="cancelreplicationtaskassessmentrunresponsetypedef"></a>

## CancelReplicationTaskAssessmentRunResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import CancelReplicationTaskAssessmentRunResponseTypeDef
```

Required fields:

- `ReplicationTaskAssessmentRun`:
  [ReplicationTaskAssessmentRunTypeDef](./type_defs.md#replicationtaskassessmentruntypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="certificatetypedef"></a>

## CertificateTypeDef

```python
from types_aiobotocore_dms.type_defs import CertificateTypeDef
```

Optional fields:

- `CertificateIdentifier`: `str`
- `CertificateCreationDate`: `datetime`
- `CertificatePem`: `str`
- `CertificateWallet`: `bytes`
- `CertificateArn`: `str`
- `CertificateOwner`: `str`
- `ValidFromDate`: `datetime`
- `ValidToDate`: `datetime`
- `SigningAlgorithm`: `str`
- `KeyLength`: `int`

<a id="connectiontypedef"></a>

## ConnectionTypeDef

```python
from types_aiobotocore_dms.type_defs import ConnectionTypeDef
```

Optional fields:

- `ReplicationInstanceArn`: `str`
- `EndpointArn`: `str`
- `Status`: `str`
- `LastFailureMessage`: `str`
- `EndpointIdentifier`: `str`
- `ReplicationInstanceIdentifier`: `str`

<a id="createendpointmessagerequesttypedef"></a>

## CreateEndpointMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateEndpointMessageRequestTypeDef
```

Required fields:

- `EndpointIdentifier`: `str`
- `EndpointType`:
  [ReplicationEndpointTypeValueType](./literals.md#replicationendpointtypevaluetype)
- `EngineName`: `str`

Optional fields:

- `Username`: `str`
- `Password`: `str`
- `ServerName`: `str`
- `Port`: `int`
- `DatabaseName`: `str`
- `ExtraConnectionAttributes`: `str`
- `KmsKeyId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `CertificateArn`: `str`
- `SslMode`: [DmsSslModeValueType](./literals.md#dmssslmodevaluetype)
- `ServiceAccessRoleArn`: `str`
- `ExternalTableDefinition`: `str`
- `DynamoDbSettings`:
  [DynamoDbSettingsTypeDef](./type_defs.md#dynamodbsettingstypedef)
- `S3Settings`: [S3SettingsTypeDef](./type_defs.md#s3settingstypedef)
- `DmsTransferSettings`:
  [DmsTransferSettingsTypeDef](./type_defs.md#dmstransfersettingstypedef)
- `MongoDbSettings`:
  [MongoDbSettingsTypeDef](./type_defs.md#mongodbsettingstypedef)
- `KinesisSettings`:
  [KinesisSettingsTypeDef](./type_defs.md#kinesissettingstypedef)
- `KafkaSettings`: [KafkaSettingsTypeDef](./type_defs.md#kafkasettingstypedef)
- `ElasticsearchSettings`:
  [ElasticsearchSettingsTypeDef](./type_defs.md#elasticsearchsettingstypedef)
- `NeptuneSettings`:
  [NeptuneSettingsTypeDef](./type_defs.md#neptunesettingstypedef)
- `RedshiftSettings`:
  [RedshiftSettingsTypeDef](./type_defs.md#redshiftsettingstypedef)
- `PostgreSQLSettings`:
  [PostgreSQLSettingsTypeDef](./type_defs.md#postgresqlsettingstypedef)
- `MySQLSettings`: [MySQLSettingsTypeDef](./type_defs.md#mysqlsettingstypedef)
- `OracleSettings`:
  [OracleSettingsTypeDef](./type_defs.md#oraclesettingstypedef)
- `SybaseSettings`:
  [SybaseSettingsTypeDef](./type_defs.md#sybasesettingstypedef)
- `MicrosoftSQLServerSettings`:
  [MicrosoftSQLServerSettingsTypeDef](./type_defs.md#microsoftsqlserversettingstypedef)
- `IBMDb2Settings`:
  [IBMDb2SettingsTypeDef](./type_defs.md#ibmdb2settingstypedef)
- `ResourceIdentifier`: `str`
- `DocDbSettings`: [DocDbSettingsTypeDef](./type_defs.md#docdbsettingstypedef)
- `RedisSettings`: [RedisSettingsTypeDef](./type_defs.md#redissettingstypedef)
- `GcpMySQLSettings`:
  [GcpMySQLSettingsTypeDef](./type_defs.md#gcpmysqlsettingstypedef)

<a id="createendpointresponsetypedef"></a>

## CreateEndpointResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateEndpointResponseTypeDef
```

Required fields:

- `Endpoint`: [EndpointTypeDef](./type_defs.md#endpointtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createeventsubscriptionmessagerequesttypedef"></a>

## CreateEventSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateEventSubscriptionMessageRequestTypeDef
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

<a id="createeventsubscriptionresponsetypedef"></a>

## CreateEventSubscriptionResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateEventSubscriptionResponseTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createreplicationinstancemessagerequesttypedef"></a>

## CreateReplicationInstanceMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateReplicationInstanceMessageRequestTypeDef
```

Required fields:

- `ReplicationInstanceIdentifier`: `str`
- `ReplicationInstanceClass`: `str`

Optional fields:

- `AllocatedStorage`: `int`
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `AvailabilityZone`: `str`
- `ReplicationSubnetGroupIdentifier`: `str`
- `PreferredMaintenanceWindow`: `str`
- `MultiAZ`: `bool`
- `EngineVersion`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `KmsKeyId`: `str`
- `PubliclyAccessible`: `bool`
- `DnsNameServers`: `str`
- `ResourceIdentifier`: `str`

<a id="createreplicationinstanceresponsetypedef"></a>

## CreateReplicationInstanceResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateReplicationInstanceResponseTypeDef
```

Required fields:

- `ReplicationInstance`:
  [ReplicationInstanceTypeDef](./type_defs.md#replicationinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createreplicationsubnetgroupmessagerequesttypedef"></a>

## CreateReplicationSubnetGroupMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateReplicationSubnetGroupMessageRequestTypeDef
```

Required fields:

- `ReplicationSubnetGroupIdentifier`: `str`
- `ReplicationSubnetGroupDescription`: `str`
- `SubnetIds`: `Sequence`\[`str`\]

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createreplicationsubnetgroupresponsetypedef"></a>

## CreateReplicationSubnetGroupResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateReplicationSubnetGroupResponseTypeDef
```

Required fields:

- `ReplicationSubnetGroup`:
  [ReplicationSubnetGroupTypeDef](./type_defs.md#replicationsubnetgrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createreplicationtaskmessagerequesttypedef"></a>

## CreateReplicationTaskMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateReplicationTaskMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskIdentifier`: `str`
- `SourceEndpointArn`: `str`
- `TargetEndpointArn`: `str`
- `ReplicationInstanceArn`: `str`
- `MigrationType`:
  [MigrationTypeValueType](./literals.md#migrationtypevaluetype)
- `TableMappings`: `str`

Optional fields:

- `ReplicationTaskSettings`: `str`
- `CdcStartTime`: `Union`\[`datetime`, `str`\]
- `CdcStartPosition`: `str`
- `CdcStopPosition`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `TaskData`: `str`
- `ResourceIdentifier`: `str`

<a id="createreplicationtaskresponsetypedef"></a>

## CreateReplicationTaskResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import CreateReplicationTaskResponseTypeDef
```

Required fields:

- `ReplicationTask`:
  [ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletecertificatemessagerequesttypedef"></a>

## DeleteCertificateMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteCertificateMessageRequestTypeDef
```

Required fields:

- `CertificateArn`: `str`

<a id="deletecertificateresponsetypedef"></a>

## DeleteCertificateResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteCertificateResponseTypeDef
```

Required fields:

- `Certificate`: [CertificateTypeDef](./type_defs.md#certificatetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteconnectionmessagerequesttypedef"></a>

## DeleteConnectionMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteConnectionMessageRequestTypeDef
```

Required fields:

- `EndpointArn`: `str`
- `ReplicationInstanceArn`: `str`

<a id="deleteconnectionresponsetypedef"></a>

## DeleteConnectionResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteConnectionResponseTypeDef
```

Required fields:

- `Connection`: [ConnectionTypeDef](./type_defs.md#connectiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteendpointmessagerequesttypedef"></a>

## DeleteEndpointMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteEndpointMessageRequestTypeDef
```

Required fields:

- `EndpointArn`: `str`

<a id="deleteendpointresponsetypedef"></a>

## DeleteEndpointResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteEndpointResponseTypeDef
```

Required fields:

- `Endpoint`: [EndpointTypeDef](./type_defs.md#endpointtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteeventsubscriptionmessagerequesttypedef"></a>

## DeleteEventSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteEventSubscriptionMessageRequestTypeDef
```

Required fields:

- `SubscriptionName`: `str`

<a id="deleteeventsubscriptionresponsetypedef"></a>

## DeleteEventSubscriptionResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteEventSubscriptionResponseTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletereplicationinstancemessagerequesttypedef"></a>

## DeleteReplicationInstanceMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteReplicationInstanceMessageRequestTypeDef
```

Required fields:

- `ReplicationInstanceArn`: `str`

<a id="deletereplicationinstanceresponsetypedef"></a>

## DeleteReplicationInstanceResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteReplicationInstanceResponseTypeDef
```

Required fields:

- `ReplicationInstance`:
  [ReplicationInstanceTypeDef](./type_defs.md#replicationinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletereplicationsubnetgroupmessagerequesttypedef"></a>

## DeleteReplicationSubnetGroupMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteReplicationSubnetGroupMessageRequestTypeDef
```

Required fields:

- `ReplicationSubnetGroupIdentifier`: `str`

<a id="deletereplicationtaskassessmentrunmessagerequesttypedef"></a>

## DeleteReplicationTaskAssessmentRunMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteReplicationTaskAssessmentRunMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskAssessmentRunArn`: `str`

<a id="deletereplicationtaskassessmentrunresponsetypedef"></a>

## DeleteReplicationTaskAssessmentRunResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteReplicationTaskAssessmentRunResponseTypeDef
```

Required fields:

- `ReplicationTaskAssessmentRun`:
  [ReplicationTaskAssessmentRunTypeDef](./type_defs.md#replicationtaskassessmentruntypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletereplicationtaskmessagerequesttypedef"></a>

## DeleteReplicationTaskMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteReplicationTaskMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`

<a id="deletereplicationtaskresponsetypedef"></a>

## DeleteReplicationTaskResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DeleteReplicationTaskResponseTypeDef
```

Required fields:

- `ReplicationTask`:
  [ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeaccountattributesresponsetypedef"></a>

## DescribeAccountAttributesResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeAccountAttributesResponseTypeDef
```

Required fields:

- `AccountQuotas`:
  `List`\[[AccountQuotaTypeDef](./type_defs.md#accountquotatypedef)\]
- `UniqueAccountIdentifier`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeapplicableindividualassessmentsmessagerequesttypedef"></a>

## DescribeApplicableIndividualAssessmentsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeApplicableIndividualAssessmentsMessageRequestTypeDef
```

Optional fields:

- `ReplicationTaskArn`: `str`
- `ReplicationInstanceArn`: `str`
- `SourceEngineName`: `str`
- `TargetEngineName`: `str`
- `MigrationType`:
  [MigrationTypeValueType](./literals.md#migrationtypevaluetype)
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeapplicableindividualassessmentsresponsetypedef"></a>

## DescribeApplicableIndividualAssessmentsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeApplicableIndividualAssessmentsResponseTypeDef
```

Required fields:

- `IndividualAssessmentNames`: `List`\[`str`\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describecertificatesmessagerequesttypedef"></a>

## DescribeCertificatesMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeCertificatesMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describecertificatesresponsetypedef"></a>

## DescribeCertificatesResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeCertificatesResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `Certificates`:
  `List`\[[CertificateTypeDef](./type_defs.md#certificatetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeconnectionsmessagerequesttypedef"></a>

## DescribeConnectionsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeConnectionsMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeconnectionsresponsetypedef"></a>

## DescribeConnectionsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeConnectionsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `Connections`:
  `List`\[[ConnectionTypeDef](./type_defs.md#connectiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeendpointsettingsmessagerequesttypedef"></a>

## DescribeEndpointSettingsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEndpointSettingsMessageRequestTypeDef
```

Required fields:

- `EngineName`: `str`

Optional fields:

- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeendpointsettingsresponsetypedef"></a>

## DescribeEndpointSettingsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEndpointSettingsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `EndpointSettings`:
  `List`\[[EndpointSettingTypeDef](./type_defs.md#endpointsettingtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeendpointtypesmessagerequesttypedef"></a>

## DescribeEndpointTypesMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEndpointTypesMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeendpointtypesresponsetypedef"></a>

## DescribeEndpointTypesResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEndpointTypesResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `SupportedEndpointTypes`:
  `List`\[[SupportedEndpointTypeTypeDef](./type_defs.md#supportedendpointtypetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeendpointsmessagerequesttypedef"></a>

## DescribeEndpointsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEndpointsMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeendpointsresponsetypedef"></a>

## DescribeEndpointsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEndpointsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `Endpoints`: `List`\[[EndpointTypeDef](./type_defs.md#endpointtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeeventcategoriesmessagerequesttypedef"></a>

## DescribeEventCategoriesMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEventCategoriesMessageRequestTypeDef
```

Optional fields:

- `SourceType`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="describeeventcategoriesresponsetypedef"></a>

## DescribeEventCategoriesResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEventCategoriesResponseTypeDef
```

Required fields:

- `EventCategoryGroupList`:
  `List`\[[EventCategoryGroupTypeDef](./type_defs.md#eventcategorygrouptypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeeventsubscriptionsmessagerequesttypedef"></a>

## DescribeEventSubscriptionsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEventSubscriptionsMessageRequestTypeDef
```

Optional fields:

- `SubscriptionName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeeventsubscriptionsresponsetypedef"></a>

## DescribeEventSubscriptionsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEventSubscriptionsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `EventSubscriptionsList`:
  `List`\[[EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeeventsmessagerequesttypedef"></a>

## DescribeEventsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEventsMessageRequestTypeDef
```

Optional fields:

- `SourceIdentifier`: `str`
- `SourceType`: `Literal['replication-instance']` (see
  [SourceTypeType](./literals.md#sourcetypetype))
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `Duration`: `int`
- `EventCategories`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeeventsresponsetypedef"></a>

## DescribeEventsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeEventsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `Events`: `List`\[[EventTypeDef](./type_defs.md#eventtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeorderablereplicationinstancesmessagerequesttypedef"></a>

## DescribeOrderableReplicationInstancesMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeOrderableReplicationInstancesMessageRequestTypeDef
```

Optional fields:

- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeorderablereplicationinstancesresponsetypedef"></a>

## DescribeOrderableReplicationInstancesResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeOrderableReplicationInstancesResponseTypeDef
```

Required fields:

- `OrderableReplicationInstances`:
  `List`\[[OrderableReplicationInstanceTypeDef](./type_defs.md#orderablereplicationinstancetypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describependingmaintenanceactionsmessagerequesttypedef"></a>

## DescribePendingMaintenanceActionsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribePendingMaintenanceActionsMessageRequestTypeDef
```

Optional fields:

- `ReplicationInstanceArn`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `Marker`: `str`
- `MaxRecords`: `int`

<a id="describependingmaintenanceactionsresponsetypedef"></a>

## DescribePendingMaintenanceActionsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribePendingMaintenanceActionsResponseTypeDef
```

Required fields:

- `PendingMaintenanceActions`:
  `List`\[[ResourcePendingMaintenanceActionsTypeDef](./type_defs.md#resourcependingmaintenanceactionstypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describerefreshschemasstatusmessagerequesttypedef"></a>

## DescribeRefreshSchemasStatusMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeRefreshSchemasStatusMessageRequestTypeDef
```

Required fields:

- `EndpointArn`: `str`

<a id="describerefreshschemasstatusresponsetypedef"></a>

## DescribeRefreshSchemasStatusResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeRefreshSchemasStatusResponseTypeDef
```

Required fields:

- `RefreshSchemasStatus`:
  [RefreshSchemasStatusTypeDef](./type_defs.md#refreshschemasstatustypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describereplicationinstancetasklogsmessagerequesttypedef"></a>

## DescribeReplicationInstanceTaskLogsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationInstanceTaskLogsMessageRequestTypeDef
```

Required fields:

- `ReplicationInstanceArn`: `str`

Optional fields:

- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describereplicationinstancetasklogsresponsetypedef"></a>

## DescribeReplicationInstanceTaskLogsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationInstanceTaskLogsResponseTypeDef
```

Required fields:

- `ReplicationInstanceArn`: `str`
- `ReplicationInstanceTaskLogs`:
  `List`\[[ReplicationInstanceTaskLogTypeDef](./type_defs.md#replicationinstancetasklogtypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describereplicationinstancesmessagerequesttypedef"></a>

## DescribeReplicationInstancesMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationInstancesMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describereplicationinstancesresponsetypedef"></a>

## DescribeReplicationInstancesResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationInstancesResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `ReplicationInstances`:
  `List`\[[ReplicationInstanceTypeDef](./type_defs.md#replicationinstancetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describereplicationsubnetgroupsmessagerequesttypedef"></a>

## DescribeReplicationSubnetGroupsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationSubnetGroupsMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describereplicationsubnetgroupsresponsetypedef"></a>

## DescribeReplicationSubnetGroupsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationSubnetGroupsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `ReplicationSubnetGroups`:
  `List`\[[ReplicationSubnetGroupTypeDef](./type_defs.md#replicationsubnetgrouptypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describereplicationtaskassessmentresultsmessagerequesttypedef"></a>

## DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef
```

Optional fields:

- `ReplicationTaskArn`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describereplicationtaskassessmentresultsresponsetypedef"></a>

## DescribeReplicationTaskAssessmentResultsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTaskAssessmentResultsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `BucketName`: `str`
- `ReplicationTaskAssessmentResults`:
  `List`\[[ReplicationTaskAssessmentResultTypeDef](./type_defs.md#replicationtaskassessmentresulttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describereplicationtaskassessmentrunsmessagerequesttypedef"></a>

## DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describereplicationtaskassessmentrunsresponsetypedef"></a>

## DescribeReplicationTaskAssessmentRunsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTaskAssessmentRunsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `ReplicationTaskAssessmentRuns`:
  `List`\[[ReplicationTaskAssessmentRunTypeDef](./type_defs.md#replicationtaskassessmentruntypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describereplicationtaskindividualassessmentsmessagerequesttypedef"></a>

## DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describereplicationtaskindividualassessmentsresponsetypedef"></a>

## DescribeReplicationTaskIndividualAssessmentsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTaskIndividualAssessmentsResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `ReplicationTaskIndividualAssessments`:
  `List`\[[ReplicationTaskIndividualAssessmentTypeDef](./type_defs.md#replicationtaskindividualassessmenttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describereplicationtasksmessagerequesttypedef"></a>

## DescribeReplicationTasksMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTasksMessageRequestTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`
- `WithoutSettings`: `bool`

<a id="describereplicationtasksresponsetypedef"></a>

## DescribeReplicationTasksResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeReplicationTasksResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `ReplicationTasks`:
  `List`\[[ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeschemasmessagerequesttypedef"></a>

## DescribeSchemasMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeSchemasMessageRequestTypeDef
```

Required fields:

- `EndpointArn`: `str`

Optional fields:

- `MaxRecords`: `int`
- `Marker`: `str`

<a id="describeschemasresponsetypedef"></a>

## DescribeSchemasResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeSchemasResponseTypeDef
```

Required fields:

- `Marker`: `str`
- `Schemas`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetablestatisticsmessagerequesttypedef"></a>

## DescribeTableStatisticsMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeTableStatisticsMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`

Optional fields:

- `MaxRecords`: `int`
- `Marker`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="describetablestatisticsresponsetypedef"></a>

## DescribeTableStatisticsResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import DescribeTableStatisticsResponseTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`
- `TableStatistics`:
  `List`\[[TableStatisticsTypeDef](./type_defs.md#tablestatisticstypedef)\]
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dmstransfersettingstypedef"></a>

## DmsTransferSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import DmsTransferSettingsTypeDef
```

Optional fields:

- `ServiceAccessRoleArn`: `str`
- `BucketName`: `str`

<a id="docdbsettingstypedef"></a>

## DocDbSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import DocDbSettingsTypeDef
```

Optional fields:

- `Username`: `str`
- `Password`: `str`
- `ServerName`: `str`
- `Port`: `int`
- `DatabaseName`: `str`
- `NestingLevel`: [NestingLevelValueType](./literals.md#nestinglevelvaluetype)
- `ExtractDocId`: `bool`
- `DocsToInvestigate`: `int`
- `KmsKeyId`: `str`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="dynamodbsettingstypedef"></a>

## DynamoDbSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import DynamoDbSettingsTypeDef
```

Required fields:

- `ServiceAccessRoleArn`: `str`

<a id="elasticsearchsettingstypedef"></a>

## ElasticsearchSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import ElasticsearchSettingsTypeDef
```

Required fields:

- `ServiceAccessRoleArn`: `str`
- `EndpointUri`: `str`

Optional fields:

- `FullLoadErrorPercentage`: `int`
- `ErrorRetryDuration`: `int`

<a id="endpointsettingtypedef"></a>

## EndpointSettingTypeDef

```python
from types_aiobotocore_dms.type_defs import EndpointSettingTypeDef
```

Optional fields:

- `Name`: `str`
- `Type`:
  [EndpointSettingTypeValueType](./literals.md#endpointsettingtypevaluetype)
- `EnumValues`: `List`\[`str`\]
- `Sensitive`: `bool`
- `Units`: `str`
- `Applicability`: `str`
- `IntValueMin`: `int`
- `IntValueMax`: `int`
- `DefaultValue`: `str`

<a id="endpointtypedef"></a>

## EndpointTypeDef

```python
from types_aiobotocore_dms.type_defs import EndpointTypeDef
```

Optional fields:

- `EndpointIdentifier`: `str`
- `EndpointType`:
  [ReplicationEndpointTypeValueType](./literals.md#replicationendpointtypevaluetype)
- `EngineName`: `str`
- `EngineDisplayName`: `str`
- `Username`: `str`
- `ServerName`: `str`
- `Port`: `int`
- `DatabaseName`: `str`
- `ExtraConnectionAttributes`: `str`
- `Status`: `str`
- `KmsKeyId`: `str`
- `EndpointArn`: `str`
- `CertificateArn`: `str`
- `SslMode`: [DmsSslModeValueType](./literals.md#dmssslmodevaluetype)
- `ServiceAccessRoleArn`: `str`
- `ExternalTableDefinition`: `str`
- `ExternalId`: `str`
- `DynamoDbSettings`:
  [DynamoDbSettingsTypeDef](./type_defs.md#dynamodbsettingstypedef)
- `S3Settings`: [S3SettingsTypeDef](./type_defs.md#s3settingstypedef)
- `DmsTransferSettings`:
  [DmsTransferSettingsTypeDef](./type_defs.md#dmstransfersettingstypedef)
- `MongoDbSettings`:
  [MongoDbSettingsTypeDef](./type_defs.md#mongodbsettingstypedef)
- `KinesisSettings`:
  [KinesisSettingsTypeDef](./type_defs.md#kinesissettingstypedef)
- `KafkaSettings`: [KafkaSettingsTypeDef](./type_defs.md#kafkasettingstypedef)
- `ElasticsearchSettings`:
  [ElasticsearchSettingsTypeDef](./type_defs.md#elasticsearchsettingstypedef)
- `NeptuneSettings`:
  [NeptuneSettingsTypeDef](./type_defs.md#neptunesettingstypedef)
- `RedshiftSettings`:
  [RedshiftSettingsTypeDef](./type_defs.md#redshiftsettingstypedef)
- `PostgreSQLSettings`:
  [PostgreSQLSettingsTypeDef](./type_defs.md#postgresqlsettingstypedef)
- `MySQLSettings`: [MySQLSettingsTypeDef](./type_defs.md#mysqlsettingstypedef)
- `OracleSettings`:
  [OracleSettingsTypeDef](./type_defs.md#oraclesettingstypedef)
- `SybaseSettings`:
  [SybaseSettingsTypeDef](./type_defs.md#sybasesettingstypedef)
- `MicrosoftSQLServerSettings`:
  [MicrosoftSQLServerSettingsTypeDef](./type_defs.md#microsoftsqlserversettingstypedef)
- `IBMDb2Settings`:
  [IBMDb2SettingsTypeDef](./type_defs.md#ibmdb2settingstypedef)
- `DocDbSettings`: [DocDbSettingsTypeDef](./type_defs.md#docdbsettingstypedef)
- `RedisSettings`: [RedisSettingsTypeDef](./type_defs.md#redissettingstypedef)
- `GcpMySQLSettings`:
  [GcpMySQLSettingsTypeDef](./type_defs.md#gcpmysqlsettingstypedef)

<a id="eventcategorygrouptypedef"></a>

## EventCategoryGroupTypeDef

```python
from types_aiobotocore_dms.type_defs import EventCategoryGroupTypeDef
```

Optional fields:

- `SourceType`: `str`
- `EventCategories`: `List`\[`str`\]

<a id="eventsubscriptiontypedef"></a>

## EventSubscriptionTypeDef

```python
from types_aiobotocore_dms.type_defs import EventSubscriptionTypeDef
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

<a id="eventtypedef"></a>

## EventTypeDef

```python
from types_aiobotocore_dms.type_defs import EventTypeDef
```

Optional fields:

- `SourceIdentifier`: `str`
- `SourceType`: `Literal['replication-instance']` (see
  [SourceTypeType](./literals.md#sourcetypetype))
- `Message`: `str`
- `EventCategories`: `List`\[`str`\]
- `Date`: `datetime`

<a id="filtertypedef"></a>

## FilterTypeDef

```python
from types_aiobotocore_dms.type_defs import FilterTypeDef
```

Required fields:

- `Name`: `str`
- `Values`: `Sequence`\[`str`\]

<a id="gcpmysqlsettingstypedef"></a>

## GcpMySQLSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import GcpMySQLSettingsTypeDef
```

Optional fields:

- `AfterConnectScript`: `str`
- `CleanSourceMetadataOnMismatch`: `bool`
- `DatabaseName`: `str`
- `EventsPollInterval`: `int`
- `TargetDbType`: [TargetDbTypeType](./literals.md#targetdbtypetype)
- `MaxFileSize`: `int`
- `ParallelLoadThreads`: `int`
- `Password`: `str`
- `Port`: `int`
- `ServerName`: `str`
- `ServerTimezone`: `str`
- `Username`: `str`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="ibmdb2settingstypedef"></a>

## IBMDb2SettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import IBMDb2SettingsTypeDef
```

Optional fields:

- `DatabaseName`: `str`
- `Password`: `str`
- `Port`: `int`
- `ServerName`: `str`
- `SetDataCaptureChanges`: `bool`
- `CurrentLsn`: `str`
- `MaxKBytesPerRead`: `int`
- `Username`: `str`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="importcertificatemessagerequesttypedef"></a>

## ImportCertificateMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ImportCertificateMessageRequestTypeDef
```

Required fields:

- `CertificateIdentifier`: `str`

Optional fields:

- `CertificatePem`: `str`
- `CertificateWallet`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="importcertificateresponsetypedef"></a>

## ImportCertificateResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ImportCertificateResponseTypeDef
```

Required fields:

- `Certificate`: [CertificateTypeDef](./type_defs.md#certificatetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="kafkasettingstypedef"></a>

## KafkaSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import KafkaSettingsTypeDef
```

Optional fields:

- `Broker`: `str`
- `Topic`: `str`
- `MessageFormat`:
  [MessageFormatValueType](./literals.md#messageformatvaluetype)
- `IncludeTransactionDetails`: `bool`
- `IncludePartitionValue`: `bool`
- `PartitionIncludeSchemaTable`: `bool`
- `IncludeTableAlterOperations`: `bool`
- `IncludeControlDetails`: `bool`
- `MessageMaxBytes`: `int`
- `IncludeNullAndEmpty`: `bool`
- `SecurityProtocol`:
  [KafkaSecurityProtocolType](./literals.md#kafkasecurityprotocoltype)
- `SslClientCertificateArn`: `str`
- `SslClientKeyArn`: `str`
- `SslClientKeyPassword`: `str`
- `SslCaCertificateArn`: `str`
- `SaslUsername`: `str`
- `SaslPassword`: `str`
- `NoHexPrefix`: `bool`

<a id="kinesissettingstypedef"></a>

## KinesisSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import KinesisSettingsTypeDef
```

Optional fields:

- `StreamArn`: `str`
- `MessageFormat`:
  [MessageFormatValueType](./literals.md#messageformatvaluetype)
- `ServiceAccessRoleArn`: `str`
- `IncludeTransactionDetails`: `bool`
- `IncludePartitionValue`: `bool`
- `PartitionIncludeSchemaTable`: `bool`
- `IncludeTableAlterOperations`: `bool`
- `IncludeControlDetails`: `bool`
- `IncludeNullAndEmpty`: `bool`
- `NoHexPrefix`: `bool`

<a id="listtagsforresourcemessagerequesttypedef"></a>

## ListTagsForResourceMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ListTagsForResourceMessageRequestTypeDef
```

Optional fields:

- `ResourceArn`: `str`
- `ResourceArnList`: `Sequence`\[`str`\]

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `TagList`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="microsoftsqlserversettingstypedef"></a>

## MicrosoftSQLServerSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import MicrosoftSQLServerSettingsTypeDef
```

Optional fields:

- `Port`: `int`
- `BcpPacketSize`: `int`
- `DatabaseName`: `str`
- `ControlTablesFileGroup`: `str`
- `Password`: `str`
- `QuerySingleAlwaysOnNode`: `bool`
- `ReadBackupOnly`: `bool`
- `SafeguardPolicy`: [SafeguardPolicyType](./literals.md#safeguardpolicytype)
- `ServerName`: `str`
- `Username`: `str`
- `UseBcpFullLoad`: `bool`
- `UseThirdPartyBackupDevice`: `bool`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="modifyendpointmessagerequesttypedef"></a>

## ModifyEndpointMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyEndpointMessageRequestTypeDef
```

Required fields:

- `EndpointArn`: `str`

Optional fields:

- `EndpointIdentifier`: `str`
- `EndpointType`:
  [ReplicationEndpointTypeValueType](./literals.md#replicationendpointtypevaluetype)
- `EngineName`: `str`
- `Username`: `str`
- `Password`: `str`
- `ServerName`: `str`
- `Port`: `int`
- `DatabaseName`: `str`
- `ExtraConnectionAttributes`: `str`
- `CertificateArn`: `str`
- `SslMode`: [DmsSslModeValueType](./literals.md#dmssslmodevaluetype)
- `ServiceAccessRoleArn`: `str`
- `ExternalTableDefinition`: `str`
- `DynamoDbSettings`:
  [DynamoDbSettingsTypeDef](./type_defs.md#dynamodbsettingstypedef)
- `S3Settings`: [S3SettingsTypeDef](./type_defs.md#s3settingstypedef)
- `DmsTransferSettings`:
  [DmsTransferSettingsTypeDef](./type_defs.md#dmstransfersettingstypedef)
- `MongoDbSettings`:
  [MongoDbSettingsTypeDef](./type_defs.md#mongodbsettingstypedef)
- `KinesisSettings`:
  [KinesisSettingsTypeDef](./type_defs.md#kinesissettingstypedef)
- `KafkaSettings`: [KafkaSettingsTypeDef](./type_defs.md#kafkasettingstypedef)
- `ElasticsearchSettings`:
  [ElasticsearchSettingsTypeDef](./type_defs.md#elasticsearchsettingstypedef)
- `NeptuneSettings`:
  [NeptuneSettingsTypeDef](./type_defs.md#neptunesettingstypedef)
- `RedshiftSettings`:
  [RedshiftSettingsTypeDef](./type_defs.md#redshiftsettingstypedef)
- `PostgreSQLSettings`:
  [PostgreSQLSettingsTypeDef](./type_defs.md#postgresqlsettingstypedef)
- `MySQLSettings`: [MySQLSettingsTypeDef](./type_defs.md#mysqlsettingstypedef)
- `OracleSettings`:
  [OracleSettingsTypeDef](./type_defs.md#oraclesettingstypedef)
- `SybaseSettings`:
  [SybaseSettingsTypeDef](./type_defs.md#sybasesettingstypedef)
- `MicrosoftSQLServerSettings`:
  [MicrosoftSQLServerSettingsTypeDef](./type_defs.md#microsoftsqlserversettingstypedef)
- `IBMDb2Settings`:
  [IBMDb2SettingsTypeDef](./type_defs.md#ibmdb2settingstypedef)
- `DocDbSettings`: [DocDbSettingsTypeDef](./type_defs.md#docdbsettingstypedef)
- `RedisSettings`: [RedisSettingsTypeDef](./type_defs.md#redissettingstypedef)
- `ExactSettings`: `bool`
- `GcpMySQLSettings`:
  [GcpMySQLSettingsTypeDef](./type_defs.md#gcpmysqlsettingstypedef)

<a id="modifyendpointresponsetypedef"></a>

## ModifyEndpointResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyEndpointResponseTypeDef
```

Required fields:

- `Endpoint`: [EndpointTypeDef](./type_defs.md#endpointtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifyeventsubscriptionmessagerequesttypedef"></a>

## ModifyEventSubscriptionMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyEventSubscriptionMessageRequestTypeDef
```

Required fields:

- `SubscriptionName`: `str`

Optional fields:

- `SnsTopicArn`: `str`
- `SourceType`: `str`
- `EventCategories`: `Sequence`\[`str`\]
- `Enabled`: `bool`

<a id="modifyeventsubscriptionresponsetypedef"></a>

## ModifyEventSubscriptionResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyEventSubscriptionResponseTypeDef
```

Required fields:

- `EventSubscription`:
  [EventSubscriptionTypeDef](./type_defs.md#eventsubscriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifyreplicationinstancemessagerequesttypedef"></a>

## ModifyReplicationInstanceMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyReplicationInstanceMessageRequestTypeDef
```

Required fields:

- `ReplicationInstanceArn`: `str`

Optional fields:

- `AllocatedStorage`: `int`
- `ApplyImmediately`: `bool`
- `ReplicationInstanceClass`: `str`
- `VpcSecurityGroupIds`: `Sequence`\[`str`\]
- `PreferredMaintenanceWindow`: `str`
- `MultiAZ`: `bool`
- `EngineVersion`: `str`
- `AllowMajorVersionUpgrade`: `bool`
- `AutoMinorVersionUpgrade`: `bool`
- `ReplicationInstanceIdentifier`: `str`

<a id="modifyreplicationinstanceresponsetypedef"></a>

## ModifyReplicationInstanceResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyReplicationInstanceResponseTypeDef
```

Required fields:

- `ReplicationInstance`:
  [ReplicationInstanceTypeDef](./type_defs.md#replicationinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifyreplicationsubnetgroupmessagerequesttypedef"></a>

## ModifyReplicationSubnetGroupMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyReplicationSubnetGroupMessageRequestTypeDef
```

Required fields:

- `ReplicationSubnetGroupIdentifier`: `str`
- `SubnetIds`: `Sequence`\[`str`\]

Optional fields:

- `ReplicationSubnetGroupDescription`: `str`

<a id="modifyreplicationsubnetgroupresponsetypedef"></a>

## ModifyReplicationSubnetGroupResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyReplicationSubnetGroupResponseTypeDef
```

Required fields:

- `ReplicationSubnetGroup`:
  [ReplicationSubnetGroupTypeDef](./type_defs.md#replicationsubnetgrouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modifyreplicationtaskmessagerequesttypedef"></a>

## ModifyReplicationTaskMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyReplicationTaskMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`

Optional fields:

- `ReplicationTaskIdentifier`: `str`
- `MigrationType`:
  [MigrationTypeValueType](./literals.md#migrationtypevaluetype)
- `TableMappings`: `str`
- `ReplicationTaskSettings`: `str`
- `CdcStartTime`: `Union`\[`datetime`, `str`\]
- `CdcStartPosition`: `str`
- `CdcStopPosition`: `str`
- `TaskData`: `str`

<a id="modifyreplicationtaskresponsetypedef"></a>

## ModifyReplicationTaskResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ModifyReplicationTaskResponseTypeDef
```

Required fields:

- `ReplicationTask`:
  [ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="mongodbsettingstypedef"></a>

## MongoDbSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import MongoDbSettingsTypeDef
```

Optional fields:

- `Username`: `str`
- `Password`: `str`
- `ServerName`: `str`
- `Port`: `int`
- `DatabaseName`: `str`
- `AuthType`: [AuthTypeValueType](./literals.md#authtypevaluetype)
- `AuthMechanism`:
  [AuthMechanismValueType](./literals.md#authmechanismvaluetype)
- `NestingLevel`: [NestingLevelValueType](./literals.md#nestinglevelvaluetype)
- `ExtractDocId`: `str`
- `DocsToInvestigate`: `str`
- `AuthSource`: `str`
- `KmsKeyId`: `str`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="movereplicationtaskmessagerequesttypedef"></a>

## MoveReplicationTaskMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import MoveReplicationTaskMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`
- `TargetReplicationInstanceArn`: `str`

<a id="movereplicationtaskresponsetypedef"></a>

## MoveReplicationTaskResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import MoveReplicationTaskResponseTypeDef
```

Required fields:

- `ReplicationTask`:
  [ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="mysqlsettingstypedef"></a>

## MySQLSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import MySQLSettingsTypeDef
```

Optional fields:

- `AfterConnectScript`: `str`
- `CleanSourceMetadataOnMismatch`: `bool`
- `DatabaseName`: `str`
- `EventsPollInterval`: `int`
- `TargetDbType`: [TargetDbTypeType](./literals.md#targetdbtypetype)
- `MaxFileSize`: `int`
- `ParallelLoadThreads`: `int`
- `Password`: `str`
- `Port`: `int`
- `ServerName`: `str`
- `ServerTimezone`: `str`
- `Username`: `str`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="neptunesettingstypedef"></a>

## NeptuneSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import NeptuneSettingsTypeDef
```

Required fields:

- `S3BucketName`: `str`
- `S3BucketFolder`: `str`

Optional fields:

- `ServiceAccessRoleArn`: `str`
- `ErrorRetryDuration`: `int`
- `MaxFileSize`: `int`
- `MaxRetryCount`: `int`
- `IamAuthEnabled`: `bool`

<a id="oraclesettingstypedef"></a>

## OracleSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import OracleSettingsTypeDef
```

Optional fields:

- `AddSupplementalLogging`: `bool`
- `ArchivedLogDestId`: `int`
- `AdditionalArchivedLogDestId`: `int`
- `ExtraArchivedLogDestIds`: `Sequence`\[`int`\]
- `AllowSelectNestedTables`: `bool`
- `ParallelAsmReadThreads`: `int`
- `ReadAheadBlocks`: `int`
- `AccessAlternateDirectly`: `bool`
- `UseAlternateFolderForOnline`: `bool`
- `OraclePathPrefix`: `str`
- `UsePathPrefix`: `str`
- `ReplacePathPrefix`: `bool`
- `EnableHomogenousTablespace`: `bool`
- `DirectPathNoLog`: `bool`
- `ArchivedLogsOnly`: `bool`
- `AsmPassword`: `str`
- `AsmServer`: `str`
- `AsmUser`: `str`
- `CharLengthSemantics`:
  [CharLengthSemanticsType](./literals.md#charlengthsemanticstype)
- `DatabaseName`: `str`
- `DirectPathParallelLoad`: `bool`
- `FailTasksOnLobTruncation`: `bool`
- `NumberDatatypeScale`: `int`
- `Password`: `str`
- `Port`: `int`
- `ReadTableSpaceName`: `bool`
- `RetryInterval`: `int`
- `SecurityDbEncryption`: `str`
- `SecurityDbEncryptionName`: `str`
- `ServerName`: `str`
- `SpatialDataOptionToGeoJsonFunctionName`: `str`
- `StandbyDelayTime`: `int`
- `Username`: `str`
- `UseBFile`: `bool`
- `UseDirectPathFullLoad`: `bool`
- `UseLogminerReader`: `bool`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`
- `SecretsManagerOracleAsmAccessRoleArn`: `str`
- `SecretsManagerOracleAsmSecretId`: `str`

<a id="orderablereplicationinstancetypedef"></a>

## OrderableReplicationInstanceTypeDef

```python
from types_aiobotocore_dms.type_defs import OrderableReplicationInstanceTypeDef
```

Optional fields:

- `EngineVersion`: `str`
- `ReplicationInstanceClass`: `str`
- `StorageType`: `str`
- `MinAllocatedStorage`: `int`
- `MaxAllocatedStorage`: `int`
- `DefaultAllocatedStorage`: `int`
- `IncludedAllocatedStorage`: `int`
- `AvailabilityZones`: `List`\[`str`\]
- `ReleaseStatus`: `Literal['beta']` (see
  [ReleaseStatusValuesType](./literals.md#releasestatusvaluestype))

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_dms.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="pendingmaintenanceactiontypedef"></a>

## PendingMaintenanceActionTypeDef

```python
from types_aiobotocore_dms.type_defs import PendingMaintenanceActionTypeDef
```

Optional fields:

- `Action`: `str`
- `AutoAppliedAfterDate`: `datetime`
- `ForcedApplyDate`: `datetime`
- `OptInStatus`: `str`
- `CurrentApplyDate`: `datetime`
- `Description`: `str`

<a id="postgresqlsettingstypedef"></a>

## PostgreSQLSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import PostgreSQLSettingsTypeDef
```

Optional fields:

- `AfterConnectScript`: `str`
- `CaptureDdls`: `bool`
- `MaxFileSize`: `int`
- `DatabaseName`: `str`
- `DdlArtifactsSchema`: `str`
- `ExecuteTimeout`: `int`
- `FailTasksOnLobTruncation`: `bool`
- `HeartbeatEnable`: `bool`
- `HeartbeatSchema`: `str`
- `HeartbeatFrequency`: `int`
- `Password`: `str`
- `Port`: `int`
- `ServerName`: `str`
- `Username`: `str`
- `SlotName`: `str`
- `PluginName`: [PluginNameValueType](./literals.md#pluginnamevaluetype)
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="rebootreplicationinstancemessagerequesttypedef"></a>

## RebootReplicationInstanceMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import RebootReplicationInstanceMessageRequestTypeDef
```

Required fields:

- `ReplicationInstanceArn`: `str`

Optional fields:

- `ForceFailover`: `bool`
- `ForcePlannedFailover`: `bool`

<a id="rebootreplicationinstanceresponsetypedef"></a>

## RebootReplicationInstanceResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import RebootReplicationInstanceResponseTypeDef
```

Required fields:

- `ReplicationInstance`:
  [ReplicationInstanceTypeDef](./type_defs.md#replicationinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="redissettingstypedef"></a>

## RedisSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import RedisSettingsTypeDef
```

Required fields:

- `ServerName`: `str`
- `Port`: `int`

Optional fields:

- `SslSecurityProtocol`:
  [SslSecurityProtocolValueType](./literals.md#sslsecurityprotocolvaluetype)
- `AuthType`: [RedisAuthTypeValueType](./literals.md#redisauthtypevaluetype)
- `AuthUserName`: `str`
- `AuthPassword`: `str`
- `SslCaCertificateArn`: `str`

<a id="redshiftsettingstypedef"></a>

## RedshiftSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import RedshiftSettingsTypeDef
```

Optional fields:

- `AcceptAnyDate`: `bool`
- `AfterConnectScript`: `str`
- `BucketFolder`: `str`
- `BucketName`: `str`
- `CaseSensitiveNames`: `bool`
- `CompUpdate`: `bool`
- `ConnectionTimeout`: `int`
- `DatabaseName`: `str`
- `DateFormat`: `str`
- `EmptyAsNull`: `bool`
- `EncryptionMode`:
  [EncryptionModeValueType](./literals.md#encryptionmodevaluetype)
- `ExplicitIds`: `bool`
- `FileTransferUploadStreams`: `int`
- `LoadTimeout`: `int`
- `MaxFileSize`: `int`
- `Password`: `str`
- `Port`: `int`
- `RemoveQuotes`: `bool`
- `ReplaceInvalidChars`: `str`
- `ReplaceChars`: `str`
- `ServerName`: `str`
- `ServiceAccessRoleArn`: `str`
- `ServerSideEncryptionKmsKeyId`: `str`
- `TimeFormat`: `str`
- `TrimBlanks`: `bool`
- `TruncateColumns`: `bool`
- `Username`: `str`
- `WriteBufferSize`: `int`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="refreshschemasmessagerequesttypedef"></a>

## RefreshSchemasMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import RefreshSchemasMessageRequestTypeDef
```

Required fields:

- `EndpointArn`: `str`
- `ReplicationInstanceArn`: `str`

<a id="refreshschemasresponsetypedef"></a>

## RefreshSchemasResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import RefreshSchemasResponseTypeDef
```

Required fields:

- `RefreshSchemasStatus`:
  [RefreshSchemasStatusTypeDef](./type_defs.md#refreshschemasstatustypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="refreshschemasstatustypedef"></a>

## RefreshSchemasStatusTypeDef

```python
from types_aiobotocore_dms.type_defs import RefreshSchemasStatusTypeDef
```

Optional fields:

- `EndpointArn`: `str`
- `ReplicationInstanceArn`: `str`
- `Status`:
  [RefreshSchemasStatusTypeValueType](./literals.md#refreshschemasstatustypevaluetype)
- `LastRefreshDate`: `datetime`
- `LastFailureMessage`: `str`

<a id="reloadtablesmessagerequesttypedef"></a>

## ReloadTablesMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import ReloadTablesMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`
- `TablesToReload`:
  `Sequence`\[[TableToReloadTypeDef](./type_defs.md#tabletoreloadtypedef)\]

Optional fields:

- `ReloadOption`: [ReloadOptionValueType](./literals.md#reloadoptionvaluetype)

<a id="reloadtablesresponsetypedef"></a>

## ReloadTablesResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import ReloadTablesResponseTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="removetagsfromresourcemessagerequesttypedef"></a>

## RemoveTagsFromResourceMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import RemoveTagsFromResourceMessageRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="replicationinstancetasklogtypedef"></a>

## ReplicationInstanceTaskLogTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationInstanceTaskLogTypeDef
```

Optional fields:

- `ReplicationTaskName`: `str`
- `ReplicationTaskArn`: `str`
- `ReplicationInstanceTaskLogSize`: `int`

<a id="replicationinstancetypedef"></a>

## ReplicationInstanceTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationInstanceTypeDef
```

Optional fields:

- `ReplicationInstanceIdentifier`: `str`
- `ReplicationInstanceClass`: `str`
- `ReplicationInstanceStatus`: `str`
- `AllocatedStorage`: `int`
- `InstanceCreateTime`: `datetime`
- `VpcSecurityGroups`:
  `List`\[[VpcSecurityGroupMembershipTypeDef](./type_defs.md#vpcsecuritygroupmembershiptypedef)\]
- `AvailabilityZone`: `str`
- `ReplicationSubnetGroup`:
  [ReplicationSubnetGroupTypeDef](./type_defs.md#replicationsubnetgrouptypedef)
- `PreferredMaintenanceWindow`: `str`
- `PendingModifiedValues`:
  [ReplicationPendingModifiedValuesTypeDef](./type_defs.md#replicationpendingmodifiedvaluestypedef)
- `MultiAZ`: `bool`
- `EngineVersion`: `str`
- `AutoMinorVersionUpgrade`: `bool`
- `KmsKeyId`: `str`
- `ReplicationInstanceArn`: `str`
- `ReplicationInstancePublicIpAddress`: `str`
- `ReplicationInstancePrivateIpAddress`: `str`
- `ReplicationInstancePublicIpAddresses`: `List`\[`str`\]
- `ReplicationInstancePrivateIpAddresses`: `List`\[`str`\]
- `PubliclyAccessible`: `bool`
- `SecondaryAvailabilityZone`: `str`
- `FreeUntil`: `datetime`
- `DnsNameServers`: `str`

<a id="replicationpendingmodifiedvaluestypedef"></a>

## ReplicationPendingModifiedValuesTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationPendingModifiedValuesTypeDef
```

Optional fields:

- `ReplicationInstanceClass`: `str`
- `AllocatedStorage`: `int`
- `MultiAZ`: `bool`
- `EngineVersion`: `str`

<a id="replicationsubnetgrouptypedef"></a>

## ReplicationSubnetGroupTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationSubnetGroupTypeDef
```

Optional fields:

- `ReplicationSubnetGroupIdentifier`: `str`
- `ReplicationSubnetGroupDescription`: `str`
- `VpcId`: `str`
- `SubnetGroupStatus`: `str`
- `Subnets`: `List`\[[SubnetTypeDef](./type_defs.md#subnettypedef)\]

<a id="replicationtaskassessmentresulttypedef"></a>

## ReplicationTaskAssessmentResultTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationTaskAssessmentResultTypeDef
```

Optional fields:

- `ReplicationTaskIdentifier`: `str`
- `ReplicationTaskArn`: `str`
- `ReplicationTaskLastAssessmentDate`: `datetime`
- `AssessmentStatus`: `str`
- `AssessmentResultsFile`: `str`
- `AssessmentResults`: `str`
- `S3ObjectUrl`: `str`

<a id="replicationtaskassessmentrunprogresstypedef"></a>

## ReplicationTaskAssessmentRunProgressTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationTaskAssessmentRunProgressTypeDef
```

Optional fields:

- `IndividualAssessmentCount`: `int`
- `IndividualAssessmentCompletedCount`: `int`

<a id="replicationtaskassessmentruntypedef"></a>

## ReplicationTaskAssessmentRunTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationTaskAssessmentRunTypeDef
```

Optional fields:

- `ReplicationTaskAssessmentRunArn`: `str`
- `ReplicationTaskArn`: `str`
- `Status`: `str`
- `ReplicationTaskAssessmentRunCreationDate`: `datetime`
- `AssessmentProgress`:
  [ReplicationTaskAssessmentRunProgressTypeDef](./type_defs.md#replicationtaskassessmentrunprogresstypedef)
- `LastFailureMessage`: `str`
- `ServiceAccessRoleArn`: `str`
- `ResultLocationBucket`: `str`
- `ResultLocationFolder`: `str`
- `ResultEncryptionMode`: `str`
- `ResultKmsKeyArn`: `str`
- `AssessmentRunName`: `str`

<a id="replicationtaskindividualassessmenttypedef"></a>

## ReplicationTaskIndividualAssessmentTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationTaskIndividualAssessmentTypeDef
```

Optional fields:

- `ReplicationTaskIndividualAssessmentArn`: `str`
- `ReplicationTaskAssessmentRunArn`: `str`
- `IndividualAssessmentName`: `str`
- `Status`: `str`
- `ReplicationTaskIndividualAssessmentStartDate`: `datetime`

<a id="replicationtaskstatstypedef"></a>

## ReplicationTaskStatsTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationTaskStatsTypeDef
```

Optional fields:

- `FullLoadProgressPercent`: `int`
- `ElapsedTimeMillis`: `int`
- `TablesLoaded`: `int`
- `TablesLoading`: `int`
- `TablesQueued`: `int`
- `TablesErrored`: `int`
- `FreshStartDate`: `datetime`
- `StartDate`: `datetime`
- `StopDate`: `datetime`
- `FullLoadStartDate`: `datetime`
- `FullLoadFinishDate`: `datetime`

<a id="replicationtasktypedef"></a>

## ReplicationTaskTypeDef

```python
from types_aiobotocore_dms.type_defs import ReplicationTaskTypeDef
```

Optional fields:

- `ReplicationTaskIdentifier`: `str`
- `SourceEndpointArn`: `str`
- `TargetEndpointArn`: `str`
- `ReplicationInstanceArn`: `str`
- `MigrationType`:
  [MigrationTypeValueType](./literals.md#migrationtypevaluetype)
- `TableMappings`: `str`
- `ReplicationTaskSettings`: `str`
- `Status`: `str`
- `LastFailureMessage`: `str`
- `StopReason`: `str`
- `ReplicationTaskCreationDate`: `datetime`
- `ReplicationTaskStartDate`: `datetime`
- `CdcStartPosition`: `str`
- `CdcStopPosition`: `str`
- `RecoveryCheckpoint`: `str`
- `ReplicationTaskArn`: `str`
- `ReplicationTaskStats`:
  [ReplicationTaskStatsTypeDef](./type_defs.md#replicationtaskstatstypedef)
- `TaskData`: `str`
- `TargetReplicationInstanceArn`: `str`

<a id="resourcependingmaintenanceactionstypedef"></a>

## ResourcePendingMaintenanceActionsTypeDef

```python
from types_aiobotocore_dms.type_defs import ResourcePendingMaintenanceActionsTypeDef
```

Optional fields:

- `ResourceIdentifier`: `str`
- `PendingMaintenanceActionDetails`:
  `List`\[[PendingMaintenanceActionTypeDef](./type_defs.md#pendingmaintenanceactiontypedef)\]

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_dms.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3settingstypedef"></a>

## S3SettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import S3SettingsTypeDef
```

Optional fields:

- `ServiceAccessRoleArn`: `str`
- `ExternalTableDefinition`: `str`
- `CsvRowDelimiter`: `str`
- `CsvDelimiter`: `str`
- `BucketFolder`: `str`
- `BucketName`: `str`
- `CompressionType`:
  [CompressionTypeValueType](./literals.md#compressiontypevaluetype)
- `EncryptionMode`:
  [EncryptionModeValueType](./literals.md#encryptionmodevaluetype)
- `ServerSideEncryptionKmsKeyId`: `str`
- `DataFormat`: [DataFormatValueType](./literals.md#dataformatvaluetype)
- `EncodingType`: [EncodingTypeValueType](./literals.md#encodingtypevaluetype)
- `DictPageSizeLimit`: `int`
- `RowGroupLength`: `int`
- `DataPageSize`: `int`
- `ParquetVersion`:
  [ParquetVersionValueType](./literals.md#parquetversionvaluetype)
- `EnableStatistics`: `bool`
- `IncludeOpForFullLoad`: `bool`
- `CdcInsertsOnly`: `bool`
- `TimestampColumnName`: `str`
- `ParquetTimestampInMillisecond`: `bool`
- `CdcInsertsAndUpdates`: `bool`
- `DatePartitionEnabled`: `bool`
- `DatePartitionSequence`:
  [DatePartitionSequenceValueType](./literals.md#datepartitionsequencevaluetype)
- `DatePartitionDelimiter`:
  [DatePartitionDelimiterValueType](./literals.md#datepartitiondelimitervaluetype)
- `UseCsvNoSupValue`: `bool`
- `CsvNoSupValue`: `str`
- `PreserveTransactions`: `bool`
- `CdcPath`: `str`
- `UseTaskStartTimeForFullLoadTimestamp`: `bool`
- `CannedAclForObjects`:
  [CannedAclForObjectsValueType](./literals.md#cannedaclforobjectsvaluetype)
- `AddColumnName`: `bool`
- `CdcMaxBatchInterval`: `int`
- `CdcMinFileSize`: `int`
- `CsvNullValue`: `str`
- `IgnoreHeaderRows`: `int`
- `MaxFileSize`: `int`
- `Rfc4180`: `bool`
- `DatePartitionTimezone`: `str`

<a id="startreplicationtaskassessmentmessagerequesttypedef"></a>

## StartReplicationTaskAssessmentMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import StartReplicationTaskAssessmentMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`

<a id="startreplicationtaskassessmentresponsetypedef"></a>

## StartReplicationTaskAssessmentResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import StartReplicationTaskAssessmentResponseTypeDef
```

Required fields:

- `ReplicationTask`:
  [ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startreplicationtaskassessmentrunmessagerequesttypedef"></a>

## StartReplicationTaskAssessmentRunMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import StartReplicationTaskAssessmentRunMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`
- `ServiceAccessRoleArn`: `str`
- `ResultLocationBucket`: `str`
- `AssessmentRunName`: `str`

Optional fields:

- `ResultLocationFolder`: `str`
- `ResultEncryptionMode`: `str`
- `ResultKmsKeyArn`: `str`
- `IncludeOnly`: `Sequence`\[`str`\]
- `Exclude`: `Sequence`\[`str`\]

<a id="startreplicationtaskassessmentrunresponsetypedef"></a>

## StartReplicationTaskAssessmentRunResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import StartReplicationTaskAssessmentRunResponseTypeDef
```

Required fields:

- `ReplicationTaskAssessmentRun`:
  [ReplicationTaskAssessmentRunTypeDef](./type_defs.md#replicationtaskassessmentruntypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startreplicationtaskmessagerequesttypedef"></a>

## StartReplicationTaskMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import StartReplicationTaskMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`
- `StartReplicationTaskType`:
  [StartReplicationTaskTypeValueType](./literals.md#startreplicationtasktypevaluetype)

Optional fields:

- `CdcStartTime`: `Union`\[`datetime`, `str`\]
- `CdcStartPosition`: `str`
- `CdcStopPosition`: `str`

<a id="startreplicationtaskresponsetypedef"></a>

## StartReplicationTaskResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import StartReplicationTaskResponseTypeDef
```

Required fields:

- `ReplicationTask`:
  [ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopreplicationtaskmessagerequesttypedef"></a>

## StopReplicationTaskMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import StopReplicationTaskMessageRequestTypeDef
```

Required fields:

- `ReplicationTaskArn`: `str`

<a id="stopreplicationtaskresponsetypedef"></a>

## StopReplicationTaskResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import StopReplicationTaskResponseTypeDef
```

Required fields:

- `ReplicationTask`:
  [ReplicationTaskTypeDef](./type_defs.md#replicationtasktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="subnettypedef"></a>

## SubnetTypeDef

```python
from types_aiobotocore_dms.type_defs import SubnetTypeDef
```

Optional fields:

- `SubnetIdentifier`: `str`
- `SubnetAvailabilityZone`:
  [AvailabilityZoneTypeDef](./type_defs.md#availabilityzonetypedef)
- `SubnetStatus`: `str`

<a id="supportedendpointtypetypedef"></a>

## SupportedEndpointTypeTypeDef

```python
from types_aiobotocore_dms.type_defs import SupportedEndpointTypeTypeDef
```

Optional fields:

- `EngineName`: `str`
- `SupportsCDC`: `bool`
- `EndpointType`:
  [ReplicationEndpointTypeValueType](./literals.md#replicationendpointtypevaluetype)
- `ReplicationInstanceEngineMinimumVersion`: `str`
- `EngineDisplayName`: `str`

<a id="sybasesettingstypedef"></a>

## SybaseSettingsTypeDef

```python
from types_aiobotocore_dms.type_defs import SybaseSettingsTypeDef
```

Optional fields:

- `DatabaseName`: `str`
- `Password`: `str`
- `Port`: `int`
- `ServerName`: `str`
- `Username`: `str`
- `SecretsManagerAccessRoleArn`: `str`
- `SecretsManagerSecretId`: `str`

<a id="tablestatisticstypedef"></a>

## TableStatisticsTypeDef

```python
from types_aiobotocore_dms.type_defs import TableStatisticsTypeDef
```

Optional fields:

- `SchemaName`: `str`
- `TableName`: `str`
- `Inserts`: `int`
- `Deletes`: `int`
- `Updates`: `int`
- `Ddls`: `int`
- `FullLoadRows`: `int`
- `FullLoadCondtnlChkFailedRows`: `int`
- `FullLoadErrorRows`: `int`
- `FullLoadStartTime`: `datetime`
- `FullLoadEndTime`: `datetime`
- `FullLoadReloaded`: `bool`
- `LastUpdateTime`: `datetime`
- `TableState`: `str`
- `ValidationPendingRecords`: `int`
- `ValidationFailedRecords`: `int`
- `ValidationSuspendedRecords`: `int`
- `ValidationState`: `str`
- `ValidationStateDetails`: `str`

<a id="tabletoreloadtypedef"></a>

## TableToReloadTypeDef

```python
from types_aiobotocore_dms.type_defs import TableToReloadTypeDef
```

Required fields:

- `SchemaName`: `str`
- `TableName`: `str`

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_dms.type_defs import TagTypeDef
```

Optional fields:

- `Key`: `str`
- `Value`: `str`
- `ResourceArn`: `str`

<a id="testconnectionmessagerequesttypedef"></a>

## TestConnectionMessageRequestTypeDef

```python
from types_aiobotocore_dms.type_defs import TestConnectionMessageRequestTypeDef
```

Required fields:

- `ReplicationInstanceArn`: `str`
- `EndpointArn`: `str`

<a id="testconnectionresponsetypedef"></a>

## TestConnectionResponseTypeDef

```python
from types_aiobotocore_dms.type_defs import TestConnectionResponseTypeDef
```

Required fields:

- `Connection`: [ConnectionTypeDef](./type_defs.md#connectiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="vpcsecuritygroupmembershiptypedef"></a>

## VpcSecurityGroupMembershipTypeDef

```python
from types_aiobotocore_dms.type_defs import VpcSecurityGroupMembershipTypeDef
```

Optional fields:

- `VpcSecurityGroupId`: `str`
- `Status`: `str`

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_dms.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`
