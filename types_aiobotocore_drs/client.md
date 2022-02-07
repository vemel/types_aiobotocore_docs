<a id="drsclient-for-aiobotocore-drs-module"></a>

# drsClient for aiobotocore drs module

> [Index](..) > [drs](.) > drsClient

Auto-generated documentation for
[drs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs)
type annotations stubs module
[types-aiobotocore-drs](https://pypi.org/project/types-aiobotocore-drs/).

- [drsClient for aiobotocore drs module](#drsclient-for-aiobotocore-drs-module)
  - [drsClient](#drsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_replication_configuration_template](#create_replication_configuration_template)
    - [delete_job](#delete_job)
    - [delete_recovery_instance](#delete_recovery_instance)
    - [delete_replication_configuration_template](#delete_replication_configuration_template)
    - [delete_source_server](#delete_source_server)
    - [describe_job_log_items](#describe_job_log_items)
    - [describe_jobs](#describe_jobs)
    - [describe_recovery_instances](#describe_recovery_instances)
    - [describe_recovery_snapshots](#describe_recovery_snapshots)
    - [describe_replication_configuration_templates](#describe_replication_configuration_templates)
    - [describe_source_servers](#describe_source_servers)
    - [disconnect_recovery_instance](#disconnect_recovery_instance)
    - [disconnect_source_server](#disconnect_source_server)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_failback_replication_configuration](#get_failback_replication_configuration)
    - [get_launch_configuration](#get_launch_configuration)
    - [get_replication_configuration](#get_replication_configuration)
    - [initialize_service](#initialize_service)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [retry_data_replication](#retry_data_replication)
    - [start_failback_launch](#start_failback_launch)
    - [start_recovery](#start_recovery)
    - [stop_failback](#stop_failback)
    - [tag_resource](#tag_resource)
    - [terminate_recovery_instances](#terminate_recovery_instances)
    - [untag_resource](#untag_resource)
    - [update_failback_replication_configuration](#update_failback_replication_configuration)
    - [update_launch_configuration](#update_launch_configuration)
    - [update_replication_configuration](#update_replication_configuration)
    - [update_replication_configuration_template](#update_replication_configuration_template)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="drsclient"></a>

## drsClient

Type annotations for `session.create_client("drs")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_drs.client import drsClient

session = get_session()
async with session.create_client("drs") as client:
    client: drsClient
```

Boto3 documentation:
[drs.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_drs.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.UninitializedAccountException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

drsClient exceptions.

Type annotations for `session.create_client("drs").exceptions` method.

Boto3 documentation:
[drs.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("drs").can_paginate` method.

Boto3 documentation:
[drs.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_replication_configuration_template"></a>

### create_replication_configuration_template

Creates a new ReplicationConfigurationTemplate.

Type annotations for
`session.create_client("drs").create_replication_configuration_template`
method.

Boto3 documentation:
[drs.Client.create_replication_configuration_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_replication_configuration_template)

Asynchronous method. Use `await create_replication_configuration_template(...)`
for a synchronous call.

Arguments mapping described in
[CreateReplicationConfigurationTemplateRequestRequestTypeDef](./type_defs.md#createreplicationconfigurationtemplaterequestrequesttypedef).

Keyword-only arguments:

- `associateDefaultSecurityGroup`: `bool` *(required)*
- `bandwidthThrottling`: `int` *(required)*
- `createPublicIP`: `bool` *(required)*
- `dataPlaneRouting`:
  [ReplicationConfigurationDataPlaneRoutingType](./literals.md#replicationconfigurationdataplaneroutingtype)
  *(required)*
- `defaultLargeStagingDiskType`:
  [ReplicationConfigurationDefaultLargeStagingDiskTypeType](./literals.md#replicationconfigurationdefaultlargestagingdisktypetype)
  *(required)*
- `ebsEncryption`:
  [ReplicationConfigurationEbsEncryptionType](./literals.md#replicationconfigurationebsencryptiontype)
  *(required)*
- `pitPolicy`:
  `Sequence`\[[PITPolicyRuleTypeDef](./type_defs.md#pitpolicyruletypedef)\]
  *(required)*
- `replicationServerInstanceType`: `str` *(required)*
- `replicationServersSecurityGroupsIDs`: `Sequence`\[`str`\] *(required)*
- `stagingAreaSubnetId`: `str` *(required)*
- `stagingAreaTags`: `Mapping`\[`str`, `str`\] *(required)*
- `useDedicatedReplicationServer`: `bool` *(required)*
- `ebsEncryptionKeyArn`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ReplicationConfigurationTemplateResponseMetadataTypeDef](./type_defs.md#replicationconfigurationtemplateresponsemetadatatypedef).

<a id="delete_job"></a>

### delete_job

Deletes a single Job by ID.

Type annotations for `session.create_client("drs").delete_job` method.

Boto3 documentation:
[drs.Client.delete_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_job)

Asynchronous method. Use `await delete_job(...)` for a synchronous call.

Arguments mapping described in
[DeleteJobRequestRequestTypeDef](./type_defs.md#deletejobrequestrequesttypedef).

Keyword-only arguments:

- `jobID`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_recovery_instance"></a>

### delete_recovery_instance

Deletes a single Recovery Instance by ID.

Type annotations for `session.create_client("drs").delete_recovery_instance`
method.

Boto3 documentation:
[drs.Client.delete_recovery_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_recovery_instance)

Asynchronous method. Use `await delete_recovery_instance(...)` for a
synchronous call.

Arguments mapping described in
[DeleteRecoveryInstanceRequestRequestTypeDef](./type_defs.md#deleterecoveryinstancerequestrequesttypedef).

Keyword-only arguments:

- `recoveryInstanceID`: `str` *(required)*

<a id="delete_replication_configuration_template"></a>

### delete_replication_configuration_template

Deletes a single Replication Configuration Template by ID See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/drs-2020-02-26/DeleteReplicationConfigurationTemplate).

Type annotations for
`session.create_client("drs").delete_replication_configuration_template`
method.

Boto3 documentation:
[drs.Client.delete_replication_configuration_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_replication_configuration_template)

Asynchronous method. Use `await delete_replication_configuration_template(...)`
for a synchronous call.

Arguments mapping described in
[DeleteReplicationConfigurationTemplateRequestRequestTypeDef](./type_defs.md#deletereplicationconfigurationtemplaterequestrequesttypedef).

Keyword-only arguments:

- `replicationConfigurationTemplateID`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_source_server"></a>

### delete_source_server

Deletes a single Source Server by ID.

Type annotations for `session.create_client("drs").delete_source_server`
method.

Boto3 documentation:
[drs.Client.delete_source_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_source_server)

Asynchronous method. Use `await delete_source_server(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSourceServerRequestRequestTypeDef](./type_defs.md#deletesourceserverrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_job_log_items"></a>

### describe_job_log_items

Retrieves a detailed Job log with pagination.

Type annotations for `session.create_client("drs").describe_job_log_items`
method.

Boto3 documentation:
[drs.Client.describe_job_log_items](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_job_log_items)

Asynchronous method. Use `await describe_job_log_items(...)` for a synchronous
call.

Arguments mapping described in
[DescribeJobLogItemsRequestRequestTypeDef](./type_defs.md#describejoblogitemsrequestrequesttypedef).

Keyword-only arguments:

- `jobID`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeJobLogItemsResponseTypeDef](./type_defs.md#describejoblogitemsresponsetypedef).

<a id="describe_jobs"></a>

### describe_jobs

Returns a list of Jobs.

Type annotations for `session.create_client("drs").describe_jobs` method.

Boto3 documentation:
[drs.Client.describe_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_jobs)

Asynchronous method. Use `await describe_jobs(...)` for a synchronous call.

Arguments mapping described in
[DescribeJobsRequestRequestTypeDef](./type_defs.md#describejobsrequestrequesttypedef).

Keyword-only arguments:

- `filters`:
  [DescribeJobsRequestFiltersTypeDef](./type_defs.md#describejobsrequestfilterstypedef)
  *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeJobsResponseTypeDef](./type_defs.md#describejobsresponsetypedef).

<a id="describe_recovery_instances"></a>

### describe_recovery_instances

Lists all Recovery Instances or multiple Recovery Instances by ID.

Type annotations for `session.create_client("drs").describe_recovery_instances`
method.

Boto3 documentation:
[drs.Client.describe_recovery_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_recovery_instances)

Asynchronous method. Use `await describe_recovery_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeRecoveryInstancesRequestRequestTypeDef](./type_defs.md#describerecoveryinstancesrequestrequesttypedef).

Keyword-only arguments:

- `filters`:
  [DescribeRecoveryInstancesRequestFiltersTypeDef](./type_defs.md#describerecoveryinstancesrequestfilterstypedef)
  *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeRecoveryInstancesResponseTypeDef](./type_defs.md#describerecoveryinstancesresponsetypedef).

<a id="describe_recovery_snapshots"></a>

### describe_recovery_snapshots

Lists all Recovery Snapshots for a single Source Server.

Type annotations for `session.create_client("drs").describe_recovery_snapshots`
method.

Boto3 documentation:
[drs.Client.describe_recovery_snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_recovery_snapshots)

Asynchronous method. Use `await describe_recovery_snapshots(...)` for a
synchronous call.

Arguments mapping described in
[DescribeRecoverySnapshotsRequestRequestTypeDef](./type_defs.md#describerecoverysnapshotsrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*
- `filters`:
  [DescribeRecoverySnapshotsRequestFiltersTypeDef](./type_defs.md#describerecoverysnapshotsrequestfilterstypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `order`:
  [RecoverySnapshotsOrderType](./literals.md#recoverysnapshotsordertype)

Returns a `Coroutine` for
[DescribeRecoverySnapshotsResponseTypeDef](./type_defs.md#describerecoverysnapshotsresponsetypedef).

<a id="describe_replication_configuration_templates"></a>

### describe_replication_configuration_templates

Lists all ReplicationConfigurationTemplates, filtered by Source Server IDs.

Type annotations for
`session.create_client("drs").describe_replication_configuration_templates`
method.

Boto3 documentation:
[drs.Client.describe_replication_configuration_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_replication_configuration_templates)

Asynchronous method. Use
`await describe_replication_configuration_templates(...)` for a synchronous
call.

Arguments mapping described in
[DescribeReplicationConfigurationTemplatesRequestRequestTypeDef](./type_defs.md#describereplicationconfigurationtemplatesrequestrequesttypedef).

Keyword-only arguments:

- `replicationConfigurationTemplateIDs`: `Sequence`\[`str`\] *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeReplicationConfigurationTemplatesResponseTypeDef](./type_defs.md#describereplicationconfigurationtemplatesresponsetypedef).

<a id="describe_source_servers"></a>

### describe_source_servers

Lists all Source Servers or multiple Source Servers filtered by ID.

Type annotations for `session.create_client("drs").describe_source_servers`
method.

Boto3 documentation:
[drs.Client.describe_source_servers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_source_servers)

Asynchronous method. Use `await describe_source_servers(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSourceServersRequestRequestTypeDef](./type_defs.md#describesourceserversrequestrequesttypedef).

Keyword-only arguments:

- `filters`:
  [DescribeSourceServersRequestFiltersTypeDef](./type_defs.md#describesourceserversrequestfilterstypedef)
  *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeSourceServersResponseTypeDef](./type_defs.md#describesourceserversresponsetypedef).

<a id="disconnect_recovery_instance"></a>

### disconnect_recovery_instance

Disconnect a Recovery Instance from Elastic Disaster Recovery.

Type annotations for
`session.create_client("drs").disconnect_recovery_instance` method.

Boto3 documentation:
[drs.Client.disconnect_recovery_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.disconnect_recovery_instance)

Asynchronous method. Use `await disconnect_recovery_instance(...)` for a
synchronous call.

Arguments mapping described in
[DisconnectRecoveryInstanceRequestRequestTypeDef](./type_defs.md#disconnectrecoveryinstancerequestrequesttypedef).

Keyword-only arguments:

- `recoveryInstanceID`: `str` *(required)*

<a id="disconnect_source_server"></a>

### disconnect_source_server

Disconnects a specific Source Server from Elastic Disaster Recovery.

Type annotations for `session.create_client("drs").disconnect_source_server`
method.

Boto3 documentation:
[drs.Client.disconnect_source_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.disconnect_source_server)

Asynchronous method. Use `await disconnect_source_server(...)` for a
synchronous call.

Arguments mapping described in
[DisconnectSourceServerRequestRequestTypeDef](./type_defs.md#disconnectsourceserverrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*

Returns a `Coroutine` for
[SourceServerResponseMetadataTypeDef](./type_defs.md#sourceserverresponsemetadatatypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("drs").generate_presigned_url`
method.

Boto3 documentation:
[drs.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_failback_replication_configuration"></a>

### get_failback_replication_configuration

Lists all Failback ReplicationConfigurations, filtered by Recovery Instance ID.

Type annotations for
`session.create_client("drs").get_failback_replication_configuration` method.

Boto3 documentation:
[drs.Client.get_failback_replication_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_failback_replication_configuration)

Asynchronous method. Use `await get_failback_replication_configuration(...)`
for a synchronous call.

Arguments mapping described in
[GetFailbackReplicationConfigurationRequestRequestTypeDef](./type_defs.md#getfailbackreplicationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `recoveryInstanceID`: `str` *(required)*

Returns a `Coroutine` for
[GetFailbackReplicationConfigurationResponseTypeDef](./type_defs.md#getfailbackreplicationconfigurationresponsetypedef).

<a id="get_launch_configuration"></a>

### get_launch_configuration

Gets a LaunchConfiguration, filtered by Source Server IDs.

Type annotations for `session.create_client("drs").get_launch_configuration`
method.

Boto3 documentation:
[drs.Client.get_launch_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_launch_configuration)

Asynchronous method. Use `await get_launch_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetLaunchConfigurationRequestRequestTypeDef](./type_defs.md#getlaunchconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*

Returns a `Coroutine` for
[LaunchConfigurationTypeDef](./type_defs.md#launchconfigurationtypedef).

<a id="get_replication_configuration"></a>

### get_replication_configuration

Gets a ReplicationConfiguration, filtered by Source Server ID.

Type annotations for
`session.create_client("drs").get_replication_configuration` method.

Boto3 documentation:
[drs.Client.get_replication_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_replication_configuration)

Asynchronous method. Use `await get_replication_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetReplicationConfigurationRequestRequestTypeDef](./type_defs.md#getreplicationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*

Returns a `Coroutine` for
[ReplicationConfigurationTypeDef](./type_defs.md#replicationconfigurationtypedef).

<a id="initialize_service"></a>

### initialize_service

Initialize Elastic Disaster Recovery.

Type annotations for `session.create_client("drs").initialize_service` method.

Boto3 documentation:
[drs.Client.initialize_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.initialize_service)

Asynchronous method. Use `await initialize_service(...)` for a synchronous
call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

List all tags for your Elastic Disaster Recovery resources.

Type annotations for `session.create_client("drs").list_tags_for_resource`
method.

Boto3 documentation:
[drs.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="retry_data_replication"></a>

### retry_data_replication

Causes the data replication initiation sequence to begin immediately upon next
Handshake for the specified Source Server ID, regardless of when the previous
initiation started.

Type annotations for `session.create_client("drs").retry_data_replication`
method.

Boto3 documentation:
[drs.Client.retry_data_replication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.retry_data_replication)

Asynchronous method. Use `await retry_data_replication(...)` for a synchronous
call.

Arguments mapping described in
[RetryDataReplicationRequestRequestTypeDef](./type_defs.md#retrydatareplicationrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*

Returns a `Coroutine` for
[SourceServerResponseMetadataTypeDef](./type_defs.md#sourceserverresponsemetadatatypedef).

<a id="start_failback_launch"></a>

### start_failback_launch

Initiates a Job for launching the machine that is being failed back to from the
specified Recovery Instance.

Type annotations for `session.create_client("drs").start_failback_launch`
method.

Boto3 documentation:
[drs.Client.start_failback_launch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_failback_launch)

Asynchronous method. Use `await start_failback_launch(...)` for a synchronous
call.

Arguments mapping described in
[StartFailbackLaunchRequestRequestTypeDef](./type_defs.md#startfailbacklaunchrequestrequesttypedef).

Keyword-only arguments:

- `recoveryInstanceIDs`: `Sequence`\[`str`\] *(required)*
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[StartFailbackLaunchResponseTypeDef](./type_defs.md#startfailbacklaunchresponsetypedef).

<a id="start_recovery"></a>

### start_recovery

Launches Recovery Instances for the specified Source Servers.

Type annotations for `session.create_client("drs").start_recovery` method.

Boto3 documentation:
[drs.Client.start_recovery](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_recovery)

Asynchronous method. Use `await start_recovery(...)` for a synchronous call.

Arguments mapping described in
[StartRecoveryRequestRequestTypeDef](./type_defs.md#startrecoveryrequestrequesttypedef).

Keyword-only arguments:

- `sourceServers`:
  `Sequence`\[[StartRecoveryRequestSourceServerTypeDef](./type_defs.md#startrecoveryrequestsourceservertypedef)\]
  *(required)*
- `isDrill`: `bool`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[StartRecoveryResponseTypeDef](./type_defs.md#startrecoveryresponsetypedef).

<a id="stop_failback"></a>

### stop_failback

Stops the failback process for a specified Recovery Instance.

Type annotations for `session.create_client("drs").stop_failback` method.

Boto3 documentation:
[drs.Client.stop_failback](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.stop_failback)

Asynchronous method. Use `await stop_failback(...)` for a synchronous call.

Arguments mapping described in
[StopFailbackRequestRequestTypeDef](./type_defs.md#stopfailbackrequestrequesttypedef).

Keyword-only arguments:

- `recoveryInstanceID`: `str` *(required)*

<a id="tag_resource"></a>

### tag_resource

Adds or overwrites only the specified tags for the specified Elastic Disaster
Recovery resource or resources.

Type annotations for `session.create_client("drs").tag_resource` method.

Boto3 documentation:
[drs.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="terminate_recovery_instances"></a>

### terminate_recovery_instances

Initiates a Job for terminating the EC2 resources associated with the specified
Recovery Instances, and then will delete the Recovery Instances from the
Elastic Disaster Recovery service.

Type annotations for
`session.create_client("drs").terminate_recovery_instances` method.

Boto3 documentation:
[drs.Client.terminate_recovery_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.terminate_recovery_instances)

Asynchronous method. Use `await terminate_recovery_instances(...)` for a
synchronous call.

Arguments mapping described in
[TerminateRecoveryInstancesRequestRequestTypeDef](./type_defs.md#terminaterecoveryinstancesrequestrequesttypedef).

Keyword-only arguments:

- `recoveryInstanceIDs`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[TerminateRecoveryInstancesResponseTypeDef](./type_defs.md#terminaterecoveryinstancesresponsetypedef).

<a id="untag_resource"></a>

### untag_resource

Deletes the specified set of tags from the specified set of Elastic Disaster
Recovery resources.

Type annotations for `session.create_client("drs").untag_resource` method.

Boto3 documentation:
[drs.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update_failback_replication_configuration"></a>

### update_failback_replication_configuration

Allows you to update the failback replication configuration of a Recovery
Instance by ID.

Type annotations for
`session.create_client("drs").update_failback_replication_configuration`
method.

Boto3 documentation:
[drs.Client.update_failback_replication_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_failback_replication_configuration)

Asynchronous method. Use `await update_failback_replication_configuration(...)`
for a synchronous call.

Arguments mapping described in
[UpdateFailbackReplicationConfigurationRequestRequestTypeDef](./type_defs.md#updatefailbackreplicationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `recoveryInstanceID`: `str` *(required)*
- `bandwidthThrottling`: `int`
- `name`: `str`
- `usePrivateIP`: `bool`

<a id="update_launch_configuration"></a>

### update_launch_configuration

Updates a LaunchConfiguration by Source Server ID.

Type annotations for `session.create_client("drs").update_launch_configuration`
method.

Boto3 documentation:
[drs.Client.update_launch_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_launch_configuration)

Asynchronous method. Use `await update_launch_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateLaunchConfigurationRequestRequestTypeDef](./type_defs.md#updatelaunchconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*
- `copyPrivateIp`: `bool`
- `copyTags`: `bool`
- `launchDisposition`:
  [LaunchDispositionType](./literals.md#launchdispositiontype)
- `licensing`: [LicensingTypeDef](./type_defs.md#licensingtypedef)
- `name`: `str`
- `targetInstanceTypeRightSizingMethod`:
  [TargetInstanceTypeRightSizingMethodType](./literals.md#targetinstancetyperightsizingmethodtype)

Returns a `Coroutine` for
[LaunchConfigurationTypeDef](./type_defs.md#launchconfigurationtypedef).

<a id="update_replication_configuration"></a>

### update_replication_configuration

Allows you to update a ReplicationConfiguration by Source Server ID.

Type annotations for
`session.create_client("drs").update_replication_configuration` method.

Boto3 documentation:
[drs.Client.update_replication_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_replication_configuration)

Asynchronous method. Use `await update_replication_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateReplicationConfigurationRequestRequestTypeDef](./type_defs.md#updatereplicationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `sourceServerID`: `str` *(required)*
- `associateDefaultSecurityGroup`: `bool`
- `bandwidthThrottling`: `int`
- `createPublicIP`: `bool`
- `dataPlaneRouting`:
  [ReplicationConfigurationDataPlaneRoutingType](./literals.md#replicationconfigurationdataplaneroutingtype)
- `defaultLargeStagingDiskType`:
  [ReplicationConfigurationDefaultLargeStagingDiskTypeType](./literals.md#replicationconfigurationdefaultlargestagingdisktypetype)
- `ebsEncryption`:
  [ReplicationConfigurationEbsEncryptionType](./literals.md#replicationconfigurationebsencryptiontype)
- `ebsEncryptionKeyArn`: `str`
- `name`: `str`
- `pitPolicy`:
  `Sequence`\[[PITPolicyRuleTypeDef](./type_defs.md#pitpolicyruletypedef)\]
- `replicatedDisks`:
  `Sequence`\[[ReplicationConfigurationReplicatedDiskTypeDef](./type_defs.md#replicationconfigurationreplicateddisktypedef)\]
- `replicationServerInstanceType`: `str`
- `replicationServersSecurityGroupsIDs`: `Sequence`\[`str`\]
- `stagingAreaSubnetId`: `str`
- `stagingAreaTags`: `Mapping`\[`str`, `str`\]
- `useDedicatedReplicationServer`: `bool`

Returns a `Coroutine` for
[ReplicationConfigurationTypeDef](./type_defs.md#replicationconfigurationtypedef).

<a id="update_replication_configuration_template"></a>

### update_replication_configuration_template

Updates a ReplicationConfigurationTemplate by ID.

Type annotations for
`session.create_client("drs").update_replication_configuration_template`
method.

Boto3 documentation:
[drs.Client.update_replication_configuration_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_replication_configuration_template)

Asynchronous method. Use `await update_replication_configuration_template(...)`
for a synchronous call.

Arguments mapping described in
[UpdateReplicationConfigurationTemplateRequestRequestTypeDef](./type_defs.md#updatereplicationconfigurationtemplaterequestrequesttypedef).

Keyword-only arguments:

- `replicationConfigurationTemplateID`: `str` *(required)*
- `arn`: `str`
- `associateDefaultSecurityGroup`: `bool`
- `bandwidthThrottling`: `int`
- `createPublicIP`: `bool`
- `dataPlaneRouting`:
  [ReplicationConfigurationDataPlaneRoutingType](./literals.md#replicationconfigurationdataplaneroutingtype)
- `defaultLargeStagingDiskType`:
  [ReplicationConfigurationDefaultLargeStagingDiskTypeType](./literals.md#replicationconfigurationdefaultlargestagingdisktypetype)
- `ebsEncryption`:
  [ReplicationConfigurationEbsEncryptionType](./literals.md#replicationconfigurationebsencryptiontype)
- `ebsEncryptionKeyArn`: `str`
- `pitPolicy`:
  `Sequence`\[[PITPolicyRuleTypeDef](./type_defs.md#pitpolicyruletypedef)\]
- `replicationServerInstanceType`: `str`
- `replicationServersSecurityGroupsIDs`: `Sequence`\[`str`\]
- `stagingAreaSubnetId`: `str`
- `stagingAreaTags`: `Mapping`\[`str`, `str`\]
- `useDedicatedReplicationServer`: `bool`

Returns a `Coroutine` for
[ReplicationConfigurationTemplateResponseMetadataTypeDef](./type_defs.md#replicationconfigurationtemplateresponsemetadatatypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("drs").__aenter__` method.

Boto3 documentation:
[drs.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [drsClient](#drsclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("drs").__aexit__` method.

Boto3 documentation:
[drs.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("drs").get_paginator` method with
overloads.

- `client.get_paginator("describe_job_log_items")` ->
  [DescribeJobLogItemsPaginator](./paginators.md#describejoblogitemspaginator)
- `client.get_paginator("describe_jobs")` ->
  [DescribeJobsPaginator](./paginators.md#describejobspaginator)
- `client.get_paginator("describe_recovery_instances")` ->
  [DescribeRecoveryInstancesPaginator](./paginators.md#describerecoveryinstancespaginator)
- `client.get_paginator("describe_recovery_snapshots")` ->
  [DescribeRecoverySnapshotsPaginator](./paginators.md#describerecoverysnapshotspaginator)
- `client.get_paginator("describe_replication_configuration_templates")` ->
  [DescribeReplicationConfigurationTemplatesPaginator](./paginators.md#describereplicationconfigurationtemplatespaginator)
- `client.get_paginator("describe_source_servers")` ->
  [DescribeSourceServersPaginator](./paginators.md#describesourceserverspaginator)
