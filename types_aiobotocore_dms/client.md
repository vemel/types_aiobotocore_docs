<a id="databasemigrationserviceclient-for-aiobotocore-databasemigrationservice-module"></a>

# DatabaseMigrationServiceClient for aiobotocore DatabaseMigrationService module

> [Index](..) > [DatabaseMigrationService](.) > DatabaseMigrationServiceClient

Auto-generated documentation for
[DatabaseMigrationService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
type annotations stubs module
[types-aiobotocore-dms](https://pypi.org/project/types-aiobotocore-dms/).

- [DatabaseMigrationServiceClient for aiobotocore DatabaseMigrationService module](#databasemigrationserviceclient-for-aiobotocore-databasemigrationservice-module)
  - [DatabaseMigrationServiceClient](#databasemigrationserviceclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_tags_to_resource](#add_tags_to_resource)
    - [apply_pending_maintenance_action](#apply_pending_maintenance_action)
    - [can_paginate](#can_paginate)
    - [cancel_replication_task_assessment_run](#cancel_replication_task_assessment_run)
    - [create_endpoint](#create_endpoint)
    - [create_event_subscription](#create_event_subscription)
    - [create_replication_instance](#create_replication_instance)
    - [create_replication_subnet_group](#create_replication_subnet_group)
    - [create_replication_task](#create_replication_task)
    - [delete_certificate](#delete_certificate)
    - [delete_connection](#delete_connection)
    - [delete_endpoint](#delete_endpoint)
    - [delete_event_subscription](#delete_event_subscription)
    - [delete_replication_instance](#delete_replication_instance)
    - [delete_replication_subnet_group](#delete_replication_subnet_group)
    - [delete_replication_task](#delete_replication_task)
    - [delete_replication_task_assessment_run](#delete_replication_task_assessment_run)
    - [describe_account_attributes](#describe_account_attributes)
    - [describe_applicable_individual_assessments](#describe_applicable_individual_assessments)
    - [describe_certificates](#describe_certificates)
    - [describe_connections](#describe_connections)
    - [describe_endpoint_settings](#describe_endpoint_settings)
    - [describe_endpoint_types](#describe_endpoint_types)
    - [describe_endpoints](#describe_endpoints)
    - [describe_event_categories](#describe_event_categories)
    - [describe_event_subscriptions](#describe_event_subscriptions)
    - [describe_events](#describe_events)
    - [describe_orderable_replication_instances](#describe_orderable_replication_instances)
    - [describe_pending_maintenance_actions](#describe_pending_maintenance_actions)
    - [describe_refresh_schemas_status](#describe_refresh_schemas_status)
    - [describe_replication_instance_task_logs](#describe_replication_instance_task_logs)
    - [describe_replication_instances](#describe_replication_instances)
    - [describe_replication_subnet_groups](#describe_replication_subnet_groups)
    - [describe_replication_task_assessment_results](#describe_replication_task_assessment_results)
    - [describe_replication_task_assessment_runs](#describe_replication_task_assessment_runs)
    - [describe_replication_task_individual_assessments](#describe_replication_task_individual_assessments)
    - [describe_replication_tasks](#describe_replication_tasks)
    - [describe_schemas](#describe_schemas)
    - [describe_table_statistics](#describe_table_statistics)
    - [generate_presigned_url](#generate_presigned_url)
    - [import_certificate](#import_certificate)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [modify_endpoint](#modify_endpoint)
    - [modify_event_subscription](#modify_event_subscription)
    - [modify_replication_instance](#modify_replication_instance)
    - [modify_replication_subnet_group](#modify_replication_subnet_group)
    - [modify_replication_task](#modify_replication_task)
    - [move_replication_task](#move_replication_task)
    - [reboot_replication_instance](#reboot_replication_instance)
    - [refresh_schemas](#refresh_schemas)
    - [reload_tables](#reload_tables)
    - [remove_tags_from_resource](#remove_tags_from_resource)
    - [start_replication_task](#start_replication_task)
    - [start_replication_task_assessment](#start_replication_task_assessment)
    - [start_replication_task_assessment_run](#start_replication_task_assessment_run)
    - [stop_replication_task](#stop_replication_task)
    - [test_connection](#test_connection)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="databasemigrationserviceclient"></a>

## DatabaseMigrationServiceClient

Type annotations for `aiobotocore.create_client("dms")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_dms.client import DatabaseMigrationServiceClient

def get_dms_client() -> DatabaseMigrationServiceClient:
    return Session().client("dms")
```

Boto3 documentation:
[DatabaseMigrationService.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_dms.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedFault) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedFault`
- `Exceptions.ClientError`
- `Exceptions.InsufficientResourceCapacityFault`
- `Exceptions.InvalidCertificateFault`
- `Exceptions.InvalidResourceStateFault`
- `Exceptions.InvalidSubnet`
- `Exceptions.KMSAccessDeniedFault`
- `Exceptions.KMSDisabledFault`
- `Exceptions.KMSFault`
- `Exceptions.KMSInvalidStateFault`
- `Exceptions.KMSKeyNotAccessibleFault`
- `Exceptions.KMSNotFoundFault`
- `Exceptions.KMSThrottlingFault`
- `Exceptions.ReplicationSubnetGroupDoesNotCoverEnoughAZs`
- `Exceptions.ResourceAlreadyExistsFault`
- `Exceptions.ResourceNotFoundFault`
- `Exceptions.ResourceQuotaExceededFault`
- `Exceptions.S3AccessDeniedFault`
- `Exceptions.S3ResourceNotFoundFault`
- `Exceptions.SNSInvalidTopicFault`
- `Exceptions.SNSNoAuthorizationFault`
- `Exceptions.StorageQuotaExceededFault`
- `Exceptions.SubnetAlreadyInUse`
- `Exceptions.UpgradeDependencyFailureFault`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

DatabaseMigrationServiceClient exceptions.

Type annotations for `aiobotocore.create_client("dms").exceptions` method.

Boto3 documentation:
[DatabaseMigrationService.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add_tags_to_resource"></a>

### add_tags_to_resource

.

Type annotations for `aiobotocore.create_client("dms").add_tags_to_resource`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.add_tags_to_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.add_tags_to_resource)

Asynchronous method. Use `await add_tags_to_resource(...)` for a synchronous
call.

Arguments mapping described in
[AddTagsToResourceMessageRequestTypeDef](./type_defs.md#addtagstoresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="apply_pending_maintenance_action"></a>

### apply_pending_maintenance_action

Applies a pending maintenance action to a resource (for example, to a
replication instance).

Type annotations for
`aiobotocore.create_client("dms").apply_pending_maintenance_action` method.

Boto3 documentation:
[DatabaseMigrationService.Client.apply_pending_maintenance_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.apply_pending_maintenance_action)

Asynchronous method. Use `await apply_pending_maintenance_action(...)` for a
synchronous call.

Arguments mapping described in
[ApplyPendingMaintenanceActionMessageRequestTypeDef](./type_defs.md#applypendingmaintenanceactionmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceArn`: `str` *(required)*
- `ApplyAction`: `str` *(required)*
- `OptInType`: `str` *(required)*

Returns a `Coroutine` for
[ApplyPendingMaintenanceActionResponseTypeDef](./type_defs.md#applypendingmaintenanceactionresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("dms").can_paginate` method.

Boto3 documentation:
[DatabaseMigrationService.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_replication_task_assessment_run"></a>

### cancel_replication_task_assessment_run

Cancels a single premigration assessment run.

Type annotations for
`aiobotocore.create_client("dms").cancel_replication_task_assessment_run`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.cancel_replication_task_assessment_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.cancel_replication_task_assessment_run)

Asynchronous method. Use `await cancel_replication_task_assessment_run(...)`
for a synchronous call.

Arguments mapping described in
[CancelReplicationTaskAssessmentRunMessageRequestTypeDef](./type_defs.md#cancelreplicationtaskassessmentrunmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskAssessmentRunArn`: `str` *(required)*

Returns a `Coroutine` for
[CancelReplicationTaskAssessmentRunResponseTypeDef](./type_defs.md#cancelreplicationtaskassessmentrunresponsetypedef).

<a id="create_endpoint"></a>

### create_endpoint

.

Type annotations for `aiobotocore.create_client("dms").create_endpoint` method.

Boto3 documentation:
[DatabaseMigrationService.Client.create_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.create_endpoint)

Asynchronous method. Use `await create_endpoint(...)` for a synchronous call.

Arguments mapping described in
[CreateEndpointMessageRequestTypeDef](./type_defs.md#createendpointmessagerequesttypedef).

Keyword-only arguments:

- `EndpointIdentifier`: `str` *(required)*
- `EndpointType`:
  [ReplicationEndpointTypeValueType](./literals.md#replicationendpointtypevaluetype)
  *(required)*
- `EngineName`: `str` *(required)*
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

Returns a `Coroutine` for
[CreateEndpointResponseTypeDef](./type_defs.md#createendpointresponsetypedef).

<a id="create_event_subscription"></a>

### create_event_subscription

Creates an DMS event notification subscription.

Type annotations for
`aiobotocore.create_client("dms").create_event_subscription` method.

Boto3 documentation:
[DatabaseMigrationService.Client.create_event_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.create_event_subscription)

Asynchronous method. Use `await create_event_subscription(...)` for a
synchronous call.

Arguments mapping described in
[CreateEventSubscriptionMessageRequestTypeDef](./type_defs.md#createeventsubscriptionmessagerequesttypedef).

Keyword-only arguments:

- `SubscriptionName`: `str` *(required)*
- `SnsTopicArn`: `str` *(required)*
- `SourceType`: `str`
- `EventCategories`: `Sequence`\[`str`\]
- `SourceIds`: `Sequence`\[`str`\]
- `Enabled`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateEventSubscriptionResponseTypeDef](./type_defs.md#createeventsubscriptionresponsetypedef).

<a id="create_replication_instance"></a>

### create_replication_instance

Creates the replication instance using the specified parameters.

Type annotations for
`aiobotocore.create_client("dms").create_replication_instance` method.

Boto3 documentation:
[DatabaseMigrationService.Client.create_replication_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.create_replication_instance)

Asynchronous method. Use `await create_replication_instance(...)` for a
synchronous call.

Arguments mapping described in
[CreateReplicationInstanceMessageRequestTypeDef](./type_defs.md#createreplicationinstancemessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceIdentifier`: `str` *(required)*
- `ReplicationInstanceClass`: `str` *(required)*
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

Returns a `Coroutine` for
[CreateReplicationInstanceResponseTypeDef](./type_defs.md#createreplicationinstanceresponsetypedef).

<a id="create_replication_subnet_group"></a>

### create_replication_subnet_group

Creates a replication subnet group given a list of the subnet IDs in a VPC.

Type annotations for
`aiobotocore.create_client("dms").create_replication_subnet_group` method.

Boto3 documentation:
[DatabaseMigrationService.Client.create_replication_subnet_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.create_replication_subnet_group)

Asynchronous method. Use `await create_replication_subnet_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateReplicationSubnetGroupMessageRequestTypeDef](./type_defs.md#createreplicationsubnetgroupmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationSubnetGroupIdentifier`: `str` *(required)*
- `ReplicationSubnetGroupDescription`: `str` *(required)*
- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateReplicationSubnetGroupResponseTypeDef](./type_defs.md#createreplicationsubnetgroupresponsetypedef).

<a id="create_replication_task"></a>

### create_replication_task

.

Type annotations for `aiobotocore.create_client("dms").create_replication_task`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.create_replication_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.create_replication_task)

Asynchronous method. Use `await create_replication_task(...)` for a synchronous
call.

Arguments mapping described in
[CreateReplicationTaskMessageRequestTypeDef](./type_defs.md#createreplicationtaskmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskIdentifier`: `str` *(required)*
- `SourceEndpointArn`: `str` *(required)*
- `TargetEndpointArn`: `str` *(required)*
- `ReplicationInstanceArn`: `str` *(required)*
- `MigrationType`:
  [MigrationTypeValueType](./literals.md#migrationtypevaluetype) *(required)*
- `TableMappings`: `str` *(required)*
- `ReplicationTaskSettings`: `str`
- `CdcStartTime`: `Union`\[`datetime`, `str`\]
- `CdcStartPosition`: `str`
- `CdcStopPosition`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `TaskData`: `str`
- `ResourceIdentifier`: `str`

Returns a `Coroutine` for
[CreateReplicationTaskResponseTypeDef](./type_defs.md#createreplicationtaskresponsetypedef).

<a id="delete_certificate"></a>

### delete_certificate

Deletes the specified certificate.

Type annotations for `aiobotocore.create_client("dms").delete_certificate`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_certificate)

Asynchronous method. Use `await delete_certificate(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCertificateMessageRequestTypeDef](./type_defs.md#deletecertificatemessagerequesttypedef).

Keyword-only arguments:

- `CertificateArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteCertificateResponseTypeDef](./type_defs.md#deletecertificateresponsetypedef).

<a id="delete_connection"></a>

### delete_connection

Deletes the connection between a replication instance and an endpoint.

Type annotations for `aiobotocore.create_client("dms").delete_connection`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_connection)

Asynchronous method. Use `await delete_connection(...)` for a synchronous call.

Arguments mapping described in
[DeleteConnectionMessageRequestTypeDef](./type_defs.md#deleteconnectionmessagerequesttypedef).

Keyword-only arguments:

- `EndpointArn`: `str` *(required)*
- `ReplicationInstanceArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteConnectionResponseTypeDef](./type_defs.md#deleteconnectionresponsetypedef).

<a id="delete_endpoint"></a>

### delete_endpoint

.

Type annotations for `aiobotocore.create_client("dms").delete_endpoint` method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_endpoint)

Asynchronous method. Use `await delete_endpoint(...)` for a synchronous call.

Arguments mapping described in
[DeleteEndpointMessageRequestTypeDef](./type_defs.md#deleteendpointmessagerequesttypedef).

Keyword-only arguments:

- `EndpointArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteEndpointResponseTypeDef](./type_defs.md#deleteendpointresponsetypedef).

<a id="delete_event_subscription"></a>

### delete_event_subscription

Deletes an DMS event subscription.

Type annotations for
`aiobotocore.create_client("dms").delete_event_subscription` method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_event_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_event_subscription)

Asynchronous method. Use `await delete_event_subscription(...)` for a
synchronous call.

Arguments mapping described in
[DeleteEventSubscriptionMessageRequestTypeDef](./type_defs.md#deleteeventsubscriptionmessagerequesttypedef).

Keyword-only arguments:

- `SubscriptionName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteEventSubscriptionResponseTypeDef](./type_defs.md#deleteeventsubscriptionresponsetypedef).

<a id="delete_replication_instance"></a>

### delete_replication_instance

Deletes the specified replication instance.

Type annotations for
`aiobotocore.create_client("dms").delete_replication_instance` method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_replication_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_replication_instance)

Asynchronous method. Use `await delete_replication_instance(...)` for a
synchronous call.

Arguments mapping described in
[DeleteReplicationInstanceMessageRequestTypeDef](./type_defs.md#deletereplicationinstancemessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteReplicationInstanceResponseTypeDef](./type_defs.md#deletereplicationinstanceresponsetypedef).

<a id="delete_replication_subnet_group"></a>

### delete_replication_subnet_group

Deletes a subnet group.

Type annotations for
`aiobotocore.create_client("dms").delete_replication_subnet_group` method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_replication_subnet_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_replication_subnet_group)

Asynchronous method. Use `await delete_replication_subnet_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteReplicationSubnetGroupMessageRequestTypeDef](./type_defs.md#deletereplicationsubnetgroupmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationSubnetGroupIdentifier`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_replication_task"></a>

### delete_replication_task

.

Type annotations for `aiobotocore.create_client("dms").delete_replication_task`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_replication_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_replication_task)

Asynchronous method. Use `await delete_replication_task(...)` for a synchronous
call.

Arguments mapping described in
[DeleteReplicationTaskMessageRequestTypeDef](./type_defs.md#deletereplicationtaskmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteReplicationTaskResponseTypeDef](./type_defs.md#deletereplicationtaskresponsetypedef).

<a id="delete_replication_task_assessment_run"></a>

### delete_replication_task_assessment_run

Deletes the record of a single premigration assessment run.

Type annotations for
`aiobotocore.create_client("dms").delete_replication_task_assessment_run`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.delete_replication_task_assessment_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.delete_replication_task_assessment_run)

Asynchronous method. Use `await delete_replication_task_assessment_run(...)`
for a synchronous call.

Arguments mapping described in
[DeleteReplicationTaskAssessmentRunMessageRequestTypeDef](./type_defs.md#deletereplicationtaskassessmentrunmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskAssessmentRunArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteReplicationTaskAssessmentRunResponseTypeDef](./type_defs.md#deletereplicationtaskassessmentrunresponsetypedef).

<a id="describe_account_attributes"></a>

### describe_account_attributes

Lists all of the DMS attributes for a customer account.

Type annotations for
`aiobotocore.create_client("dms").describe_account_attributes` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_account_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_account_attributes)

Asynchronous method. Use `await describe_account_attributes(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeAccountAttributesResponseTypeDef](./type_defs.md#describeaccountattributesresponsetypedef).

<a id="describe_applicable_individual_assessments"></a>

### describe_applicable_individual_assessments

Provides a list of individual assessments that you can specify for a new
premigration assessment run, given one or more parameters.

Type annotations for
`aiobotocore.create_client("dms").describe_applicable_individual_assessments`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_applicable_individual_assessments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_applicable_individual_assessments)

Asynchronous method. Use
`await describe_applicable_individual_assessments(...)` for a synchronous call.

Arguments mapping described in
[DescribeApplicableIndividualAssessmentsMessageRequestTypeDef](./type_defs.md#describeapplicableindividualassessmentsmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str`
- `ReplicationInstanceArn`: `str`
- `SourceEngineName`: `str`
- `TargetEngineName`: `str`
- `MigrationType`:
  [MigrationTypeValueType](./literals.md#migrationtypevaluetype)
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeApplicableIndividualAssessmentsResponseTypeDef](./type_defs.md#describeapplicableindividualassessmentsresponsetypedef).

<a id="describe_certificates"></a>

### describe_certificates

Provides a description of the certificate.

Type annotations for `aiobotocore.create_client("dms").describe_certificates`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_certificates)

Asynchronous method. Use `await describe_certificates(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCertificatesMessageRequestTypeDef](./type_defs.md#describecertificatesmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeCertificatesResponseTypeDef](./type_defs.md#describecertificatesresponsetypedef).

<a id="describe_connections"></a>

### describe_connections

Describes the status of the connections that have been made between the
replication instance and an endpoint.

Type annotations for `aiobotocore.create_client("dms").describe_connections`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_connections)

Asynchronous method. Use `await describe_connections(...)` for a synchronous
call.

Arguments mapping described in
[DescribeConnectionsMessageRequestTypeDef](./type_defs.md#describeconnectionsmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeConnectionsResponseTypeDef](./type_defs.md#describeconnectionsresponsetypedef).

<a id="describe_endpoint_settings"></a>

### describe_endpoint_settings

Returns information about the possible endpoint settings available when you
create an endpoint for a specific database engine.

Type annotations for
`aiobotocore.create_client("dms").describe_endpoint_settings` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_endpoint_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_endpoint_settings)

Asynchronous method. Use `await describe_endpoint_settings(...)` for a
synchronous call.

Arguments mapping described in
[DescribeEndpointSettingsMessageRequestTypeDef](./type_defs.md#describeendpointsettingsmessagerequesttypedef).

Keyword-only arguments:

- `EngineName`: `str` *(required)*
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeEndpointSettingsResponseTypeDef](./type_defs.md#describeendpointsettingsresponsetypedef).

<a id="describe_endpoint_types"></a>

### describe_endpoint_types

Returns information about the type of endpoints available.

Type annotations for `aiobotocore.create_client("dms").describe_endpoint_types`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_endpoint_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_endpoint_types)

Asynchronous method. Use `await describe_endpoint_types(...)` for a synchronous
call.

Arguments mapping described in
[DescribeEndpointTypesMessageRequestTypeDef](./type_defs.md#describeendpointtypesmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeEndpointTypesResponseTypeDef](./type_defs.md#describeendpointtypesresponsetypedef).

<a id="describe_endpoints"></a>

### describe_endpoints

.

Type annotations for `aiobotocore.create_client("dms").describe_endpoints`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_endpoints)

Asynchronous method. Use `await describe_endpoints(...)` for a synchronous
call.

Arguments mapping described in
[DescribeEndpointsMessageRequestTypeDef](./type_defs.md#describeendpointsmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeEndpointsResponseTypeDef](./type_defs.md#describeendpointsresponsetypedef).

<a id="describe_event_categories"></a>

### describe_event_categories

.

Type annotations for
`aiobotocore.create_client("dms").describe_event_categories` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_event_categories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_event_categories)

Asynchronous method. Use `await describe_event_categories(...)` for a
synchronous call.

Arguments mapping described in
[DescribeEventCategoriesMessageRequestTypeDef](./type_defs.md#describeeventcategoriesmessagerequesttypedef).

Keyword-only arguments:

- `SourceType`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeEventCategoriesResponseTypeDef](./type_defs.md#describeeventcategoriesresponsetypedef).

<a id="describe_event_subscriptions"></a>

### describe_event_subscriptions

Lists all the event subscriptions for a customer account.

Type annotations for
`aiobotocore.create_client("dms").describe_event_subscriptions` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_event_subscriptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_event_subscriptions)

Asynchronous method. Use `await describe_event_subscriptions(...)` for a
synchronous call.

Arguments mapping described in
[DescribeEventSubscriptionsMessageRequestTypeDef](./type_defs.md#describeeventsubscriptionsmessagerequesttypedef).

Keyword-only arguments:

- `SubscriptionName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeEventSubscriptionsResponseTypeDef](./type_defs.md#describeeventsubscriptionsresponsetypedef).

<a id="describe_events"></a>

### describe_events

Lists events for a given source identifier and source type.

Type annotations for `aiobotocore.create_client("dms").describe_events` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_events)

Asynchronous method. Use `await describe_events(...)` for a synchronous call.

Arguments mapping described in
[DescribeEventsMessageRequestTypeDef](./type_defs.md#describeeventsmessagerequesttypedef).

Keyword-only arguments:

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

Returns a `Coroutine` for
[DescribeEventsResponseTypeDef](./type_defs.md#describeeventsresponsetypedef).

<a id="describe_orderable_replication_instances"></a>

### describe_orderable_replication_instances

Returns information about the replication instance types that can be created in
the specified region.

Type annotations for
`aiobotocore.create_client("dms").describe_orderable_replication_instances`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_orderable_replication_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_orderable_replication_instances)

Asynchronous method. Use `await describe_orderable_replication_instances(...)`
for a synchronous call.

Arguments mapping described in
[DescribeOrderableReplicationInstancesMessageRequestTypeDef](./type_defs.md#describeorderablereplicationinstancesmessagerequesttypedef).

Keyword-only arguments:

- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeOrderableReplicationInstancesResponseTypeDef](./type_defs.md#describeorderablereplicationinstancesresponsetypedef).

<a id="describe_pending_maintenance_actions"></a>

### describe_pending_maintenance_actions

For internal use only See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/dms-2016-01-01/DescribePendingMaintenanceActions).

Type annotations for
`aiobotocore.create_client("dms").describe_pending_maintenance_actions` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_pending_maintenance_actions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_pending_maintenance_actions)

Asynchronous method. Use `await describe_pending_maintenance_actions(...)` for
a synchronous call.

Arguments mapping described in
[DescribePendingMaintenanceActionsMessageRequestTypeDef](./type_defs.md#describependingmaintenanceactionsmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceArn`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `Marker`: `str`
- `MaxRecords`: `int`

Returns a `Coroutine` for
[DescribePendingMaintenanceActionsResponseTypeDef](./type_defs.md#describependingmaintenanceactionsresponsetypedef).

<a id="describe_refresh_schemas_status"></a>

### describe_refresh_schemas_status

Returns the status of the RefreshSchemas operation.

Type annotations for
`aiobotocore.create_client("dms").describe_refresh_schemas_status` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_refresh_schemas_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_refresh_schemas_status)

Asynchronous method. Use `await describe_refresh_schemas_status(...)` for a
synchronous call.

Arguments mapping described in
[DescribeRefreshSchemasStatusMessageRequestTypeDef](./type_defs.md#describerefreshschemasstatusmessagerequesttypedef).

Keyword-only arguments:

- `EndpointArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeRefreshSchemasStatusResponseTypeDef](./type_defs.md#describerefreshschemasstatusresponsetypedef).

<a id="describe_replication_instance_task_logs"></a>

### describe_replication_instance_task_logs

Returns information about the task logs for the specified task.

Type annotations for
`aiobotocore.create_client("dms").describe_replication_instance_task_logs`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_replication_instance_task_logs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_replication_instance_task_logs)

Asynchronous method. Use `await describe_replication_instance_task_logs(...)`
for a synchronous call.

Arguments mapping described in
[DescribeReplicationInstanceTaskLogsMessageRequestTypeDef](./type_defs.md#describereplicationinstancetasklogsmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceArn`: `str` *(required)*
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeReplicationInstanceTaskLogsResponseTypeDef](./type_defs.md#describereplicationinstancetasklogsresponsetypedef).

<a id="describe_replication_instances"></a>

### describe_replication_instances

Returns information about replication instances for your account in the current
region.

Type annotations for
`aiobotocore.create_client("dms").describe_replication_instances` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_replication_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_replication_instances)

Asynchronous method. Use `await describe_replication_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeReplicationInstancesMessageRequestTypeDef](./type_defs.md#describereplicationinstancesmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeReplicationInstancesResponseTypeDef](./type_defs.md#describereplicationinstancesresponsetypedef).

<a id="describe_replication_subnet_groups"></a>

### describe_replication_subnet_groups

Returns information about the replication subnet groups.

Type annotations for
`aiobotocore.create_client("dms").describe_replication_subnet_groups` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_replication_subnet_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_replication_subnet_groups)

Asynchronous method. Use `await describe_replication_subnet_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeReplicationSubnetGroupsMessageRequestTypeDef](./type_defs.md#describereplicationsubnetgroupsmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeReplicationSubnetGroupsResponseTypeDef](./type_defs.md#describereplicationsubnetgroupsresponsetypedef).

<a id="describe_replication_task_assessment_results"></a>

### describe_replication_task_assessment_results

Returns the task assessment results from the Amazon S3 bucket that DMS creates
in your Amazon Web Services account.

Type annotations for
`aiobotocore.create_client("dms").describe_replication_task_assessment_results`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_replication_task_assessment_results](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_replication_task_assessment_results)

Asynchronous method. Use
`await describe_replication_task_assessment_results(...)` for a synchronous
call.

Arguments mapping described in
[DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef](./type_defs.md#describereplicationtaskassessmentresultsmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str`
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeReplicationTaskAssessmentResultsResponseTypeDef](./type_defs.md#describereplicationtaskassessmentresultsresponsetypedef).

<a id="describe_replication_task_assessment_runs"></a>

### describe_replication_task_assessment_runs

Returns a paginated list of premigration assessment runs based on filter
settings.

Type annotations for
`aiobotocore.create_client("dms").describe_replication_task_assessment_runs`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_replication_task_assessment_runs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_replication_task_assessment_runs)

Asynchronous method. Use `await describe_replication_task_assessment_runs(...)`
for a synchronous call.

Arguments mapping described in
[DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef](./type_defs.md#describereplicationtaskassessmentrunsmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeReplicationTaskAssessmentRunsResponseTypeDef](./type_defs.md#describereplicationtaskassessmentrunsresponsetypedef).

<a id="describe_replication_task_individual_assessments"></a>

### describe_replication_task_individual_assessments

Returns a paginated list of individual assessments based on filter settings.

Type annotations for
`aiobotocore.create_client("dms").describe_replication_task_individual_assessments`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_replication_task_individual_assessments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_replication_task_individual_assessments)

Asynchronous method. Use
`await describe_replication_task_individual_assessments(...)` for a synchronous
call.

Arguments mapping described in
[DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef](./type_defs.md#describereplicationtaskindividualassessmentsmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeReplicationTaskIndividualAssessmentsResponseTypeDef](./type_defs.md#describereplicationtaskindividualassessmentsresponsetypedef).

<a id="describe_replication_tasks"></a>

### describe_replication_tasks

.

Type annotations for
`aiobotocore.create_client("dms").describe_replication_tasks` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_replication_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_replication_tasks)

Asynchronous method. Use `await describe_replication_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeReplicationTasksMessageRequestTypeDef](./type_defs.md#describereplicationtasksmessagerequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxRecords`: `int`
- `Marker`: `str`
- `WithoutSettings`: `bool`

Returns a `Coroutine` for
[DescribeReplicationTasksResponseTypeDef](./type_defs.md#describereplicationtasksresponsetypedef).

<a id="describe_schemas"></a>

### describe_schemas

Returns information about the schema for the specified endpoint.

Type annotations for `aiobotocore.create_client("dms").describe_schemas`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_schemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_schemas)

Asynchronous method. Use `await describe_schemas(...)` for a synchronous call.

Arguments mapping described in
[DescribeSchemasMessageRequestTypeDef](./type_defs.md#describeschemasmessagerequesttypedef).

Keyword-only arguments:

- `EndpointArn`: `str` *(required)*
- `MaxRecords`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeSchemasResponseTypeDef](./type_defs.md#describeschemasresponsetypedef).

<a id="describe_table_statistics"></a>

### describe_table_statistics

Returns table statistics on the database migration task, including table name,
rows inserted, rows updated, and rows deleted.

Type annotations for
`aiobotocore.create_client("dms").describe_table_statistics` method.

Boto3 documentation:
[DatabaseMigrationService.Client.describe_table_statistics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_table_statistics)

Asynchronous method. Use `await describe_table_statistics(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTableStatisticsMessageRequestTypeDef](./type_defs.md#describetablestatisticsmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*
- `MaxRecords`: `int`
- `Marker`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeTableStatisticsResponseTypeDef](./type_defs.md#describetablestatisticsresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("dms").generate_presigned_url`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="import_certificate"></a>

### import_certificate

Uploads the specified certificate.

Type annotations for `aiobotocore.create_client("dms").import_certificate`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.import_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.import_certificate)

Asynchronous method. Use `await import_certificate(...)` for a synchronous
call.

Arguments mapping described in
[ImportCertificateMessageRequestTypeDef](./type_defs.md#importcertificatemessagerequesttypedef).

Keyword-only arguments:

- `CertificateIdentifier`: `str` *(required)*
- `CertificatePem`: `str`
- `CertificateWallet`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[ImportCertificateResponseTypeDef](./type_defs.md#importcertificateresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

.

Type annotations for `aiobotocore.create_client("dms").list_tags_for_resource`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceMessageRequestTypeDef](./type_defs.md#listtagsforresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str`
- `ResourceArnList`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="modify_endpoint"></a>

### modify_endpoint

.

Type annotations for `aiobotocore.create_client("dms").modify_endpoint` method.

Boto3 documentation:
[DatabaseMigrationService.Client.modify_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.modify_endpoint)

Asynchronous method. Use `await modify_endpoint(...)` for a synchronous call.

Arguments mapping described in
[ModifyEndpointMessageRequestTypeDef](./type_defs.md#modifyendpointmessagerequesttypedef).

Keyword-only arguments:

- `EndpointArn`: `str` *(required)*
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

Returns a `Coroutine` for
[ModifyEndpointResponseTypeDef](./type_defs.md#modifyendpointresponsetypedef).

<a id="modify_event_subscription"></a>

### modify_event_subscription

Modifies an existing DMS event notification subscription.

Type annotations for
`aiobotocore.create_client("dms").modify_event_subscription` method.

Boto3 documentation:
[DatabaseMigrationService.Client.modify_event_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.modify_event_subscription)

Asynchronous method. Use `await modify_event_subscription(...)` for a
synchronous call.

Arguments mapping described in
[ModifyEventSubscriptionMessageRequestTypeDef](./type_defs.md#modifyeventsubscriptionmessagerequesttypedef).

Keyword-only arguments:

- `SubscriptionName`: `str` *(required)*
- `SnsTopicArn`: `str`
- `SourceType`: `str`
- `EventCategories`: `Sequence`\[`str`\]
- `Enabled`: `bool`

Returns a `Coroutine` for
[ModifyEventSubscriptionResponseTypeDef](./type_defs.md#modifyeventsubscriptionresponsetypedef).

<a id="modify_replication_instance"></a>

### modify_replication_instance

Modifies the replication instance to apply new settings.

Type annotations for
`aiobotocore.create_client("dms").modify_replication_instance` method.

Boto3 documentation:
[DatabaseMigrationService.Client.modify_replication_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.modify_replication_instance)

Asynchronous method. Use `await modify_replication_instance(...)` for a
synchronous call.

Arguments mapping described in
[ModifyReplicationInstanceMessageRequestTypeDef](./type_defs.md#modifyreplicationinstancemessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceArn`: `str` *(required)*
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

Returns a `Coroutine` for
[ModifyReplicationInstanceResponseTypeDef](./type_defs.md#modifyreplicationinstanceresponsetypedef).

<a id="modify_replication_subnet_group"></a>

### modify_replication_subnet_group

Modifies the settings for the specified replication subnet group.

Type annotations for
`aiobotocore.create_client("dms").modify_replication_subnet_group` method.

Boto3 documentation:
[DatabaseMigrationService.Client.modify_replication_subnet_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.modify_replication_subnet_group)

Asynchronous method. Use `await modify_replication_subnet_group(...)` for a
synchronous call.

Arguments mapping described in
[ModifyReplicationSubnetGroupMessageRequestTypeDef](./type_defs.md#modifyreplicationsubnetgroupmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationSubnetGroupIdentifier`: `str` *(required)*
- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `ReplicationSubnetGroupDescription`: `str`

Returns a `Coroutine` for
[ModifyReplicationSubnetGroupResponseTypeDef](./type_defs.md#modifyreplicationsubnetgroupresponsetypedef).

<a id="modify_replication_task"></a>

### modify_replication_task

.

Type annotations for `aiobotocore.create_client("dms").modify_replication_task`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.modify_replication_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.modify_replication_task)

Asynchronous method. Use `await modify_replication_task(...)` for a synchronous
call.

Arguments mapping described in
[ModifyReplicationTaskMessageRequestTypeDef](./type_defs.md#modifyreplicationtaskmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*
- `ReplicationTaskIdentifier`: `str`
- `MigrationType`:
  [MigrationTypeValueType](./literals.md#migrationtypevaluetype)
- `TableMappings`: `str`
- `ReplicationTaskSettings`: `str`
- `CdcStartTime`: `Union`\[`datetime`, `str`\]
- `CdcStartPosition`: `str`
- `CdcStopPosition`: `str`
- `TaskData`: `str`

Returns a `Coroutine` for
[ModifyReplicationTaskResponseTypeDef](./type_defs.md#modifyreplicationtaskresponsetypedef).

<a id="move_replication_task"></a>

### move_replication_task

.

Type annotations for `aiobotocore.create_client("dms").move_replication_task`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.move_replication_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.move_replication_task)

Asynchronous method. Use `await move_replication_task(...)` for a synchronous
call.

Arguments mapping described in
[MoveReplicationTaskMessageRequestTypeDef](./type_defs.md#movereplicationtaskmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*
- `TargetReplicationInstanceArn`: `str` *(required)*

Returns a `Coroutine` for
[MoveReplicationTaskResponseTypeDef](./type_defs.md#movereplicationtaskresponsetypedef).

<a id="reboot_replication_instance"></a>

### reboot_replication_instance

Reboots a replication instance.

Type annotations for
`aiobotocore.create_client("dms").reboot_replication_instance` method.

Boto3 documentation:
[DatabaseMigrationService.Client.reboot_replication_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.reboot_replication_instance)

Asynchronous method. Use `await reboot_replication_instance(...)` for a
synchronous call.

Arguments mapping described in
[RebootReplicationInstanceMessageRequestTypeDef](./type_defs.md#rebootreplicationinstancemessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceArn`: `str` *(required)*
- `ForceFailover`: `bool`
- `ForcePlannedFailover`: `bool`

Returns a `Coroutine` for
[RebootReplicationInstanceResponseTypeDef](./type_defs.md#rebootreplicationinstanceresponsetypedef).

<a id="refresh_schemas"></a>

### refresh_schemas

Populates the schema for the specified endpoint.

Type annotations for `aiobotocore.create_client("dms").refresh_schemas` method.

Boto3 documentation:
[DatabaseMigrationService.Client.refresh_schemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.refresh_schemas)

Asynchronous method. Use `await refresh_schemas(...)` for a synchronous call.

Arguments mapping described in
[RefreshSchemasMessageRequestTypeDef](./type_defs.md#refreshschemasmessagerequesttypedef).

Keyword-only arguments:

- `EndpointArn`: `str` *(required)*
- `ReplicationInstanceArn`: `str` *(required)*

Returns a `Coroutine` for
[RefreshSchemasResponseTypeDef](./type_defs.md#refreshschemasresponsetypedef).

<a id="reload_tables"></a>

### reload_tables

Reloads the target database table with the source data.

Type annotations for `aiobotocore.create_client("dms").reload_tables` method.

Boto3 documentation:
[DatabaseMigrationService.Client.reload_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.reload_tables)

Asynchronous method. Use `await reload_tables(...)` for a synchronous call.

Arguments mapping described in
[ReloadTablesMessageRequestTypeDef](./type_defs.md#reloadtablesmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*
- `TablesToReload`:
  `Sequence`\[[TableToReloadTypeDef](./type_defs.md#tabletoreloadtypedef)\]
  *(required)*
- `ReloadOption`: [ReloadOptionValueType](./literals.md#reloadoptionvaluetype)

Returns a `Coroutine` for
[ReloadTablesResponseTypeDef](./type_defs.md#reloadtablesresponsetypedef).

<a id="remove_tags_from_resource"></a>

### remove_tags_from_resource

.

Type annotations for
`aiobotocore.create_client("dms").remove_tags_from_resource` method.

Boto3 documentation:
[DatabaseMigrationService.Client.remove_tags_from_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.remove_tags_from_resource)

Asynchronous method. Use `await remove_tags_from_resource(...)` for a
synchronous call.

Arguments mapping described in
[RemoveTagsFromResourceMessageRequestTypeDef](./type_defs.md#removetagsfromresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="start_replication_task"></a>

### start_replication_task

.

Type annotations for `aiobotocore.create_client("dms").start_replication_task`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.start_replication_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.start_replication_task)

Asynchronous method. Use `await start_replication_task(...)` for a synchronous
call.

Arguments mapping described in
[StartReplicationTaskMessageRequestTypeDef](./type_defs.md#startreplicationtaskmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*
- `StartReplicationTaskType`:
  [StartReplicationTaskTypeValueType](./literals.md#startreplicationtasktypevaluetype)
  *(required)*
- `CdcStartTime`: `Union`\[`datetime`, `str`\]
- `CdcStartPosition`: `str`
- `CdcStopPosition`: `str`

Returns a `Coroutine` for
[StartReplicationTaskResponseTypeDef](./type_defs.md#startreplicationtaskresponsetypedef).

<a id="start_replication_task_assessment"></a>

### start_replication_task_assessment

.

Type annotations for
`aiobotocore.create_client("dms").start_replication_task_assessment` method.

Boto3 documentation:
[DatabaseMigrationService.Client.start_replication_task_assessment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.start_replication_task_assessment)

Asynchronous method. Use `await start_replication_task_assessment(...)` for a
synchronous call.

Arguments mapping described in
[StartReplicationTaskAssessmentMessageRequestTypeDef](./type_defs.md#startreplicationtaskassessmentmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*

Returns a `Coroutine` for
[StartReplicationTaskAssessmentResponseTypeDef](./type_defs.md#startreplicationtaskassessmentresponsetypedef).

<a id="start_replication_task_assessment_run"></a>

### start_replication_task_assessment_run

Starts a new premigration assessment run for one or more individual assessments
of a migration task.

Type annotations for
`aiobotocore.create_client("dms").start_replication_task_assessment_run`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.start_replication_task_assessment_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.start_replication_task_assessment_run)

Asynchronous method. Use `await start_replication_task_assessment_run(...)` for
a synchronous call.

Arguments mapping described in
[StartReplicationTaskAssessmentRunMessageRequestTypeDef](./type_defs.md#startreplicationtaskassessmentrunmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*
- `ServiceAccessRoleArn`: `str` *(required)*
- `ResultLocationBucket`: `str` *(required)*
- `AssessmentRunName`: `str` *(required)*
- `ResultLocationFolder`: `str`
- `ResultEncryptionMode`: `str`
- `ResultKmsKeyArn`: `str`
- `IncludeOnly`: `Sequence`\[`str`\]
- `Exclude`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[StartReplicationTaskAssessmentRunResponseTypeDef](./type_defs.md#startreplicationtaskassessmentrunresponsetypedef).

<a id="stop_replication_task"></a>

### stop_replication_task

.

Type annotations for `aiobotocore.create_client("dms").stop_replication_task`
method.

Boto3 documentation:
[DatabaseMigrationService.Client.stop_replication_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.stop_replication_task)

Asynchronous method. Use `await stop_replication_task(...)` for a synchronous
call.

Arguments mapping described in
[StopReplicationTaskMessageRequestTypeDef](./type_defs.md#stopreplicationtaskmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationTaskArn`: `str` *(required)*

Returns a `Coroutine` for
[StopReplicationTaskResponseTypeDef](./type_defs.md#stopreplicationtaskresponsetypedef).

<a id="test_connection"></a>

### test_connection

Tests the connection between the replication instance and the endpoint.

Type annotations for `aiobotocore.create_client("dms").test_connection` method.

Boto3 documentation:
[DatabaseMigrationService.Client.test_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.test_connection)

Asynchronous method. Use `await test_connection(...)` for a synchronous call.

Arguments mapping described in
[TestConnectionMessageRequestTypeDef](./type_defs.md#testconnectionmessagerequesttypedef).

Keyword-only arguments:

- `ReplicationInstanceArn`: `str` *(required)*
- `EndpointArn`: `str` *(required)*

Returns a `Coroutine` for
[TestConnectionResponseTypeDef](./type_defs.md#testconnectionresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("dms").get_paginator` method
with overloads.

- `client.get_paginator("describe_certificates")` ->
  [DescribeCertificatesPaginator](./paginators.md#describecertificatespaginator)
- `client.get_paginator("describe_connections")` ->
  [DescribeConnectionsPaginator](./paginators.md#describeconnectionspaginator)
- `client.get_paginator("describe_endpoint_types")` ->
  [DescribeEndpointTypesPaginator](./paginators.md#describeendpointtypespaginator)
- `client.get_paginator("describe_endpoints")` ->
  [DescribeEndpointsPaginator](./paginators.md#describeendpointspaginator)
- `client.get_paginator("describe_event_subscriptions")` ->
  [DescribeEventSubscriptionsPaginator](./paginators.md#describeeventsubscriptionspaginator)
- `client.get_paginator("describe_events")` ->
  [DescribeEventsPaginator](./paginators.md#describeeventspaginator)
- `client.get_paginator("describe_orderable_replication_instances")` ->
  [DescribeOrderableReplicationInstancesPaginator](./paginators.md#describeorderablereplicationinstancespaginator)
- `client.get_paginator("describe_replication_instances")` ->
  [DescribeReplicationInstancesPaginator](./paginators.md#describereplicationinstancespaginator)
- `client.get_paginator("describe_replication_subnet_groups")` ->
  [DescribeReplicationSubnetGroupsPaginator](./paginators.md#describereplicationsubnetgroupspaginator)
- `client.get_paginator("describe_replication_task_assessment_results")` ->
  [DescribeReplicationTaskAssessmentResultsPaginator](./paginators.md#describereplicationtaskassessmentresultspaginator)
- `client.get_paginator("describe_replication_tasks")` ->
  [DescribeReplicationTasksPaginator](./paginators.md#describereplicationtaskspaginator)
- `client.get_paginator("describe_schemas")` ->
  [DescribeSchemasPaginator](./paginators.md#describeschemaspaginator)
- `client.get_paginator("describe_table_statistics")` ->
  [DescribeTableStatisticsPaginator](./paginators.md#describetablestatisticspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `aiobotocore.create_client("dms").get_waiter` method with
overloads.

- `client.get_waiter("endpoint_deleted")` ->
  [EndpointDeletedWaiter](./waiters.md#endpointdeletedwaiter)
- `client.get_waiter("replication_instance_available")` ->
  [ReplicationInstanceAvailableWaiter](./waiters.md#replicationinstanceavailablewaiter)
- `client.get_waiter("replication_instance_deleted")` ->
  [ReplicationInstanceDeletedWaiter](./waiters.md#replicationinstancedeletedwaiter)
- `client.get_waiter("replication_task_deleted")` ->
  [ReplicationTaskDeletedWaiter](./waiters.md#replicationtaskdeletedwaiter)
- `client.get_waiter("replication_task_ready")` ->
  [ReplicationTaskReadyWaiter](./waiters.md#replicationtaskreadywaiter)
- `client.get_waiter("replication_task_running")` ->
  [ReplicationTaskRunningWaiter](./waiters.md#replicationtaskrunningwaiter)
- `client.get_waiter("replication_task_stopped")` ->
  [ReplicationTaskStoppedWaiter](./waiters.md#replicationtaskstoppedwaiter)
- `client.get_waiter("test_connection_succeeds")` ->
  [TestConnectionSucceedsWaiter](./waiters.md#testconnectionsucceedswaiter)
