<a id="datasyncclient-for-aiobotocore-datasync-module"></a>

# DataSyncClient for aiobotocore DataSync module

> [Index](../README.md) > [DataSync](./README.md) > DataSyncClient

Auto-generated documentation for
[DataSync](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync)
type annotations stubs module
[types-aiobotocore-datasync](https://pypi.org/project/types-aiobotocore-datasync/).

- [DataSyncClient for aiobotocore DataSync module](#datasyncclient-for-aiobotocore-datasync-module)
  - [DataSyncClient](#datasyncclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [cancel_task_execution](#cancel_task_execution)
    - [create_agent](#create_agent)
    - [create_location_efs](#create_location_efs)
    - [create_location_fsx_lustre](#create_location_fsx_lustre)
    - [create_location_fsx_windows](#create_location_fsx_windows)
    - [create_location_hdfs](#create_location_hdfs)
    - [create_location_nfs](#create_location_nfs)
    - [create_location_object_storage](#create_location_object_storage)
    - [create_location_s3](#create_location_s3)
    - [create_location_smb](#create_location_smb)
    - [create_task](#create_task)
    - [delete_agent](#delete_agent)
    - [delete_location](#delete_location)
    - [delete_task](#delete_task)
    - [describe_agent](#describe_agent)
    - [describe_location_efs](#describe_location_efs)
    - [describe_location_fsx_lustre](#describe_location_fsx_lustre)
    - [describe_location_fsx_windows](#describe_location_fsx_windows)
    - [describe_location_hdfs](#describe_location_hdfs)
    - [describe_location_nfs](#describe_location_nfs)
    - [describe_location_object_storage](#describe_location_object_storage)
    - [describe_location_s3](#describe_location_s3)
    - [describe_location_smb](#describe_location_smb)
    - [describe_task](#describe_task)
    - [describe_task_execution](#describe_task_execution)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_agents](#list_agents)
    - [list_locations](#list_locations)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_task_executions](#list_task_executions)
    - [list_tasks](#list_tasks)
    - [start_task_execution](#start_task_execution)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_agent](#update_agent)
    - [update_location_hdfs](#update_location_hdfs)
    - [update_location_nfs](#update_location_nfs)
    - [update_location_object_storage](#update_location_object_storage)
    - [update_location_smb](#update_location_smb)
    - [update_task](#update_task)
    - [update_task_execution](#update_task_execution)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="datasyncclient"></a>

## DataSyncClient

Type annotations for `session.create_client("datasync")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_datasync.client import DataSyncClient

session = get_session()
async with session.create_client("datasync") as client:
    client: DataSyncClient
```

Boto3 documentation:
[DataSync.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_datasync.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InternalException`
- `Exceptions.InvalidRequestException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

DataSyncClient exceptions.

Type annotations for `session.create_client("datasync").exceptions` method.

Boto3 documentation:
[DataSync.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("datasync").can_paginate` method.

Boto3 documentation:
[DataSync.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="cancel\_task\_execution"></a>

### cancel_task_execution

Cancels execution of a task.

Type annotations for `session.create_client("datasync").cancel_task_execution`
method.

Boto3 documentation:
[DataSync.Client.cancel_task_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.cancel_task_execution)

Asynchronous method. Use `await cancel_task_execution(...)` for a synchronous
call.

Arguments mapping described in
[CancelTaskExecutionRequestRequestTypeDef](./type_defs.md#canceltaskexecutionrequestrequesttypedef).

Keyword-only arguments:

- `TaskExecutionArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create\_agent"></a>

### create_agent

Activates an DataSync agent that you have deployed on your host.

Type annotations for `session.create_client("datasync").create_agent` method.

Boto3 documentation:
[DataSync.Client.create_agent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_agent)

Asynchronous method. Use `await create_agent(...)` for a synchronous call.

Arguments mapping described in
[CreateAgentRequestRequestTypeDef](./type_defs.md#createagentrequestrequesttypedef).

Keyword-only arguments:

- `ActivationKey`: `str` *(required)*
- `AgentName`: `str`
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]
- `VpcEndpointId`: `str`
- `SubnetArns`: `Sequence`\[`str`\]
- `SecurityGroupArns`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[CreateAgentResponseTypeDef](./type_defs.md#createagentresponsetypedef).

<a id="create\_location\_efs"></a>

### create_location_efs

Creates an endpoint for an Amazon EFS file system.

Type annotations for `session.create_client("datasync").create_location_efs`
method.

Boto3 documentation:
[DataSync.Client.create_location_efs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_efs)

Asynchronous method. Use `await create_location_efs(...)` for a synchronous
call.

Arguments mapping described in
[CreateLocationEfsRequestRequestTypeDef](./type_defs.md#createlocationefsrequestrequesttypedef).

Keyword-only arguments:

- `EfsFilesystemArn`: `str` *(required)*
- `Ec2Config`: [Ec2ConfigTypeDef](./type_defs.md#ec2configtypedef) *(required)*
- `Subdirectory`: `str`
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]

Returns a `Coroutine` for
[CreateLocationEfsResponseTypeDef](./type_defs.md#createlocationefsresponsetypedef).

<a id="create\_location\_fsx\_lustre"></a>

### create_location_fsx_lustre

Creates an endpoint for an Amazon FSx for Lustre file system.

Type annotations for
`session.create_client("datasync").create_location_fsx_lustre` method.

Boto3 documentation:
[DataSync.Client.create_location_fsx_lustre](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_fsx_lustre)

Asynchronous method. Use `await create_location_fsx_lustre(...)` for a
synchronous call.

Arguments mapping described in
[CreateLocationFsxLustreRequestRequestTypeDef](./type_defs.md#createlocationfsxlustrerequestrequesttypedef).

Keyword-only arguments:

- `FsxFilesystemArn`: `str` *(required)*
- `SecurityGroupArns`: `Sequence`\[`str`\] *(required)*
- `Subdirectory`: `str`
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]

Returns a `Coroutine` for
[CreateLocationFsxLustreResponseTypeDef](./type_defs.md#createlocationfsxlustreresponsetypedef).

<a id="create\_location\_fsx\_windows"></a>

### create_location_fsx_windows

Creates an endpoint for an Amazon FSx for Windows File Server file system.

Type annotations for
`session.create_client("datasync").create_location_fsx_windows` method.

Boto3 documentation:
[DataSync.Client.create_location_fsx_windows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_fsx_windows)

Asynchronous method. Use `await create_location_fsx_windows(...)` for a
synchronous call.

Arguments mapping described in
[CreateLocationFsxWindowsRequestRequestTypeDef](./type_defs.md#createlocationfsxwindowsrequestrequesttypedef).

Keyword-only arguments:

- `FsxFilesystemArn`: `str` *(required)*
- `SecurityGroupArns`: `Sequence`\[`str`\] *(required)*
- `User`: `str` *(required)*
- `Password`: `str` *(required)*
- `Subdirectory`: `str`
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]
- `Domain`: `str`

Returns a `Coroutine` for
[CreateLocationFsxWindowsResponseTypeDef](./type_defs.md#createlocationfsxwindowsresponsetypedef).

<a id="create\_location\_hdfs"></a>

### create_location_hdfs

Creates an endpoint for a Hadoop Distributed File System (HDFS).

Type annotations for `session.create_client("datasync").create_location_hdfs`
method.

Boto3 documentation:
[DataSync.Client.create_location_hdfs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_hdfs)

Asynchronous method. Use `await create_location_hdfs(...)` for a synchronous
call.

Arguments mapping described in
[CreateLocationHdfsRequestRequestTypeDef](./type_defs.md#createlocationhdfsrequestrequesttypedef).

Keyword-only arguments:

- `NameNodes`:
  `Sequence`\[[HdfsNameNodeTypeDef](./type_defs.md#hdfsnamenodetypedef)\]
  *(required)*
- `AuthenticationType`:
  [HdfsAuthenticationTypeType](./literals.md#hdfsauthenticationtypetype)
  *(required)*
- `AgentArns`: `Sequence`\[`str`\] *(required)*
- `Subdirectory`: `str`
- `BlockSize`: `int`
- `ReplicationFactor`: `int`
- `KmsKeyProviderUri`: `str`
- `QopConfiguration`:
  [QopConfigurationTypeDef](./type_defs.md#qopconfigurationtypedef)
- `SimpleUser`: `str`
- `KerberosPrincipal`: `str`
- `KerberosKeytab`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `KerberosKrb5Conf`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]

Returns a `Coroutine` for
[CreateLocationHdfsResponseTypeDef](./type_defs.md#createlocationhdfsresponsetypedef).

<a id="create\_location\_nfs"></a>

### create_location_nfs

Defines a file system on a Network File System (NFS) server that can be read
from or written to.

Type annotations for `session.create_client("datasync").create_location_nfs`
method.

Boto3 documentation:
[DataSync.Client.create_location_nfs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_nfs)

Asynchronous method. Use `await create_location_nfs(...)` for a synchronous
call.

Arguments mapping described in
[CreateLocationNfsRequestRequestTypeDef](./type_defs.md#createlocationnfsrequestrequesttypedef).

Keyword-only arguments:

- `Subdirectory`: `str` *(required)*
- `ServerHostname`: `str` *(required)*
- `OnPremConfig`: [OnPremConfigTypeDef](./type_defs.md#onpremconfigtypedef)
  *(required)*
- `MountOptions`:
  [NfsMountOptionsTypeDef](./type_defs.md#nfsmountoptionstypedef)
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]

Returns a `Coroutine` for
[CreateLocationNfsResponseTypeDef](./type_defs.md#createlocationnfsresponsetypedef).

<a id="create\_location\_object\_storage"></a>

### create_location_object_storage

Creates an endpoint for a self-managed object storage bucket.

Type annotations for
`session.create_client("datasync").create_location_object_storage` method.

Boto3 documentation:
[DataSync.Client.create_location_object_storage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_object_storage)

Asynchronous method. Use `await create_location_object_storage(...)` for a
synchronous call.

Arguments mapping described in
[CreateLocationObjectStorageRequestRequestTypeDef](./type_defs.md#createlocationobjectstoragerequestrequesttypedef).

Keyword-only arguments:

- `ServerHostname`: `str` *(required)*
- `BucketName`: `str` *(required)*
- `AgentArns`: `Sequence`\[`str`\] *(required)*
- `ServerPort`: `int`
- `ServerProtocol`:
  [ObjectStorageServerProtocolType](./literals.md#objectstorageserverprotocoltype)
- `Subdirectory`: `str`
- `AccessKey`: `str`
- `SecretKey`: `str`
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]

Returns a `Coroutine` for
[CreateLocationObjectStorageResponseTypeDef](./type_defs.md#createlocationobjectstorageresponsetypedef).

<a id="create\_location\_s3"></a>

### create_location_s3

Creates an endpoint for an Amazon S3 bucket.

Type annotations for `session.create_client("datasync").create_location_s3`
method.

Boto3 documentation:
[DataSync.Client.create_location_s3](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_s3)

Asynchronous method. Use `await create_location_s3(...)` for a synchronous
call.

Arguments mapping described in
[CreateLocationS3RequestRequestTypeDef](./type_defs.md#createlocations3requestrequesttypedef).

Keyword-only arguments:

- `S3BucketArn`: `str` *(required)*
- `S3Config`: [S3ConfigTypeDef](./type_defs.md#s3configtypedef) *(required)*
- `Subdirectory`: `str`
- `S3StorageClass`: [S3StorageClassType](./literals.md#s3storageclasstype)
- `AgentArns`: `Sequence`\[`str`\]
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]

Returns a `Coroutine` for
[CreateLocationS3ResponseTypeDef](./type_defs.md#createlocations3responsetypedef).

<a id="create\_location\_smb"></a>

### create_location_smb

Defines a file system on a Server Message Block (SMB) server that can be read
from or written to.

Type annotations for `session.create_client("datasync").create_location_smb`
method.

Boto3 documentation:
[DataSync.Client.create_location_smb](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_location_smb)

Asynchronous method. Use `await create_location_smb(...)` for a synchronous
call.

Arguments mapping described in
[CreateLocationSmbRequestRequestTypeDef](./type_defs.md#createlocationsmbrequestrequesttypedef).

Keyword-only arguments:

- `Subdirectory`: `str` *(required)*
- `ServerHostname`: `str` *(required)*
- `User`: `str` *(required)*
- `Password`: `str` *(required)*
- `AgentArns`: `Sequence`\[`str`\] *(required)*
- `Domain`: `str`
- `MountOptions`:
  [SmbMountOptionsTypeDef](./type_defs.md#smbmountoptionstypedef)
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]

Returns a `Coroutine` for
[CreateLocationSmbResponseTypeDef](./type_defs.md#createlocationsmbresponsetypedef).

<a id="create\_task"></a>

### create_task

Creates a task.

Type annotations for `session.create_client("datasync").create_task` method.

Boto3 documentation:
[DataSync.Client.create_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.create_task)

Asynchronous method. Use `await create_task(...)` for a synchronous call.

Arguments mapping described in
[CreateTaskRequestRequestTypeDef](./type_defs.md#createtaskrequestrequesttypedef).

Keyword-only arguments:

- `SourceLocationArn`: `str` *(required)*
- `DestinationLocationArn`: `str` *(required)*
- `CloudWatchLogGroupArn`: `str`
- `Name`: `str`
- `Options`: [OptionsTypeDef](./type_defs.md#optionstypedef)
- `Excludes`:
  `Sequence`\[[FilterRuleTypeDef](./type_defs.md#filterruletypedef)\]
- `Schedule`: [TaskScheduleTypeDef](./type_defs.md#taskscheduletypedef)
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]
- `Includes`:
  `Sequence`\[[FilterRuleTypeDef](./type_defs.md#filterruletypedef)\]

Returns a `Coroutine` for
[CreateTaskResponseTypeDef](./type_defs.md#createtaskresponsetypedef).

<a id="delete\_agent"></a>

### delete_agent

Deletes an agent.

Type annotations for `session.create_client("datasync").delete_agent` method.

Boto3 documentation:
[DataSync.Client.delete_agent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.delete_agent)

Asynchronous method. Use `await delete_agent(...)` for a synchronous call.

Arguments mapping described in
[DeleteAgentRequestRequestTypeDef](./type_defs.md#deleteagentrequestrequesttypedef).

Keyword-only arguments:

- `AgentArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_location"></a>

### delete_location

Deletes the configuration of a location used by DataSync.

Type annotations for `session.create_client("datasync").delete_location`
method.

Boto3 documentation:
[DataSync.Client.delete_location](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.delete_location)

Asynchronous method. Use `await delete_location(...)` for a synchronous call.

Arguments mapping described in
[DeleteLocationRequestRequestTypeDef](./type_defs.md#deletelocationrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_task"></a>

### delete_task

Deletes a task.

Type annotations for `session.create_client("datasync").delete_task` method.

Boto3 documentation:
[DataSync.Client.delete_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.delete_task)

Asynchronous method. Use `await delete_task(...)` for a synchronous call.

Arguments mapping described in
[DeleteTaskRequestRequestTypeDef](./type_defs.md#deletetaskrequestrequesttypedef).

Keyword-only arguments:

- `TaskArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe\_agent"></a>

### describe_agent

Returns metadata such as the name, the network interfaces, and the status (that
is, whether the agent is running or not) for an agent.

Type annotations for `session.create_client("datasync").describe_agent` method.

Boto3 documentation:
[DataSync.Client.describe_agent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_agent)

Asynchronous method. Use `await describe_agent(...)` for a synchronous call.

Arguments mapping described in
[DescribeAgentRequestRequestTypeDef](./type_defs.md#describeagentrequestrequesttypedef).

Keyword-only arguments:

- `AgentArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAgentResponseTypeDef](./type_defs.md#describeagentresponsetypedef).

<a id="describe\_location\_efs"></a>

### describe_location_efs

Returns metadata, such as the path information about an Amazon EFS location.

Type annotations for `session.create_client("datasync").describe_location_efs`
method.

Boto3 documentation:
[DataSync.Client.describe_location_efs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_efs)

Asynchronous method. Use `await describe_location_efs(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLocationEfsRequestRequestTypeDef](./type_defs.md#describelocationefsrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationEfsResponseTypeDef](./type_defs.md#describelocationefsresponsetypedef).

<a id="describe\_location\_fsx\_lustre"></a>

### describe_location_fsx_lustre

Returns metadata, such as the path information about an Amazon FSx for Lustre
location.

Type annotations for
`session.create_client("datasync").describe_location_fsx_lustre` method.

Boto3 documentation:
[DataSync.Client.describe_location_fsx_lustre](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_fsx_lustre)

Asynchronous method. Use `await describe_location_fsx_lustre(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLocationFsxLustreRequestRequestTypeDef](./type_defs.md#describelocationfsxlustrerequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationFsxLustreResponseTypeDef](./type_defs.md#describelocationfsxlustreresponsetypedef).

<a id="describe\_location\_fsx\_windows"></a>

### describe_location_fsx_windows

Returns metadata, such as the path information about an Amazon FSx for Windows
File Server location.

Type annotations for
`session.create_client("datasync").describe_location_fsx_windows` method.

Boto3 documentation:
[DataSync.Client.describe_location_fsx_windows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_fsx_windows)

Asynchronous method. Use `await describe_location_fsx_windows(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLocationFsxWindowsRequestRequestTypeDef](./type_defs.md#describelocationfsxwindowsrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationFsxWindowsResponseTypeDef](./type_defs.md#describelocationfsxwindowsresponsetypedef).

<a id="describe\_location\_hdfs"></a>

### describe_location_hdfs

Returns metadata, such as the authentication information about the Hadoop
Distributed File System (HDFS) location.

Type annotations for `session.create_client("datasync").describe_location_hdfs`
method.

Boto3 documentation:
[DataSync.Client.describe_location_hdfs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_hdfs)

Asynchronous method. Use `await describe_location_hdfs(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLocationHdfsRequestRequestTypeDef](./type_defs.md#describelocationhdfsrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationHdfsResponseTypeDef](./type_defs.md#describelocationhdfsresponsetypedef).

<a id="describe\_location\_nfs"></a>

### describe_location_nfs

Returns metadata, such as the path information, about an NFS location.

Type annotations for `session.create_client("datasync").describe_location_nfs`
method.

Boto3 documentation:
[DataSync.Client.describe_location_nfs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_nfs)

Asynchronous method. Use `await describe_location_nfs(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLocationNfsRequestRequestTypeDef](./type_defs.md#describelocationnfsrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationNfsResponseTypeDef](./type_defs.md#describelocationnfsresponsetypedef).

<a id="describe\_location\_object\_storage"></a>

### describe_location_object_storage

Returns metadata about a self-managed object storage server location.

Type annotations for
`session.create_client("datasync").describe_location_object_storage` method.

Boto3 documentation:
[DataSync.Client.describe_location_object_storage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_object_storage)

Asynchronous method. Use `await describe_location_object_storage(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLocationObjectStorageRequestRequestTypeDef](./type_defs.md#describelocationobjectstoragerequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationObjectStorageResponseTypeDef](./type_defs.md#describelocationobjectstorageresponsetypedef).

<a id="describe\_location\_s3"></a>

### describe_location_s3

Returns metadata, such as bucket name, about an Amazon S3 bucket location.

Type annotations for `session.create_client("datasync").describe_location_s3`
method.

Boto3 documentation:
[DataSync.Client.describe_location_s3](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_s3)

Asynchronous method. Use `await describe_location_s3(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLocationS3RequestRequestTypeDef](./type_defs.md#describelocations3requestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationS3ResponseTypeDef](./type_defs.md#describelocations3responsetypedef).

<a id="describe\_location\_smb"></a>

### describe_location_smb

Returns metadata, such as the path and user information about an SMB location.

Type annotations for `session.create_client("datasync").describe_location_smb`
method.

Boto3 documentation:
[DataSync.Client.describe_location_smb](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_location_smb)

Asynchronous method. Use `await describe_location_smb(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLocationSmbRequestRequestTypeDef](./type_defs.md#describelocationsmbrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLocationSmbResponseTypeDef](./type_defs.md#describelocationsmbresponsetypedef).

<a id="describe\_task"></a>

### describe_task

Returns metadata about a task.

Type annotations for `session.create_client("datasync").describe_task` method.

Boto3 documentation:
[DataSync.Client.describe_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_task)

Asynchronous method. Use `await describe_task(...)` for a synchronous call.

Arguments mapping described in
[DescribeTaskRequestRequestTypeDef](./type_defs.md#describetaskrequestrequesttypedef).

Keyword-only arguments:

- `TaskArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTaskResponseTypeDef](./type_defs.md#describetaskresponsetypedef).

<a id="describe\_task\_execution"></a>

### describe_task_execution

Returns detailed metadata about a task that is being executed.

Type annotations for
`session.create_client("datasync").describe_task_execution` method.

Boto3 documentation:
[DataSync.Client.describe_task_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.describe_task_execution)

Asynchronous method. Use `await describe_task_execution(...)` for a synchronous
call.

Arguments mapping described in
[DescribeTaskExecutionRequestRequestTypeDef](./type_defs.md#describetaskexecutionrequestrequesttypedef).

Keyword-only arguments:

- `TaskExecutionArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTaskExecutionResponseTypeDef](./type_defs.md#describetaskexecutionresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("datasync").generate_presigned_url`
method.

Boto3 documentation:
[DataSync.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list\_agents"></a>

### list_agents

Returns a list of agents owned by an Amazon Web Services account in the Amazon
Web Services Region specified in the request.

Type annotations for `session.create_client("datasync").list_agents` method.

Boto3 documentation:
[DataSync.Client.list_agents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.list_agents)

Asynchronous method. Use `await list_agents(...)` for a synchronous call.

Arguments mapping described in
[ListAgentsRequestRequestTypeDef](./type_defs.md#listagentsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAgentsResponseTypeDef](./type_defs.md#listagentsresponsetypedef).

<a id="list\_locations"></a>

### list_locations

Returns a list of source and destination locations.

Type annotations for `session.create_client("datasync").list_locations` method.

Boto3 documentation:
[DataSync.Client.list_locations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.list_locations)

Asynchronous method. Use `await list_locations(...)` for a synchronous call.

Arguments mapping described in
[ListLocationsRequestRequestTypeDef](./type_defs.md#listlocationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`:
  `Sequence`\[[LocationFilterTypeDef](./type_defs.md#locationfiltertypedef)\]

Returns a `Coroutine` for
[ListLocationsResponseTypeDef](./type_defs.md#listlocationsresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Returns all the tags associated with a specified resource.

Type annotations for `session.create_client("datasync").list_tags_for_resource`
method.

Boto3 documentation:
[DataSync.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list\_task\_executions"></a>

### list_task_executions

Returns a list of executed tasks.

Type annotations for `session.create_client("datasync").list_task_executions`
method.

Boto3 documentation:
[DataSync.Client.list_task_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.list_task_executions)

Asynchronous method. Use `await list_task_executions(...)` for a synchronous
call.

Arguments mapping described in
[ListTaskExecutionsRequestRequestTypeDef](./type_defs.md#listtaskexecutionsrequestrequesttypedef).

Keyword-only arguments:

- `TaskArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTaskExecutionsResponseTypeDef](./type_defs.md#listtaskexecutionsresponsetypedef).

<a id="list\_tasks"></a>

### list_tasks

Returns a list of all the tasks.

Type annotations for `session.create_client("datasync").list_tasks` method.

Boto3 documentation:
[DataSync.Client.list_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.list_tasks)

Asynchronous method. Use `await list_tasks(...)` for a synchronous call.

Arguments mapping described in
[ListTasksRequestRequestTypeDef](./type_defs.md#listtasksrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`:
  `Sequence`\[[TaskFilterTypeDef](./type_defs.md#taskfiltertypedef)\]

Returns a `Coroutine` for
[ListTasksResponseTypeDef](./type_defs.md#listtasksresponsetypedef).

<a id="start\_task\_execution"></a>

### start_task_execution

Starts a specific invocation of a task.

Type annotations for `session.create_client("datasync").start_task_execution`
method.

Boto3 documentation:
[DataSync.Client.start_task_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.start_task_execution)

Asynchronous method. Use `await start_task_execution(...)` for a synchronous
call.

Arguments mapping described in
[StartTaskExecutionRequestRequestTypeDef](./type_defs.md#starttaskexecutionrequestrequesttypedef).

Keyword-only arguments:

- `TaskArn`: `str` *(required)*
- `OverrideOptions`: [OptionsTypeDef](./type_defs.md#optionstypedef)
- `Includes`:
  `Sequence`\[[FilterRuleTypeDef](./type_defs.md#filterruletypedef)\]
- `Excludes`:
  `Sequence`\[[FilterRuleTypeDef](./type_defs.md#filterruletypedef)\]

Returns a `Coroutine` for
[StartTaskExecutionResponseTypeDef](./type_defs.md#starttaskexecutionresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Applies a key-value pair to an Amazon Web Services resource.

Type annotations for `session.create_client("datasync").tag_resource` method.

Boto3 documentation:
[DataSync.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`:
  `Sequence`\[[TagListEntryTypeDef](./type_defs.md#taglistentrytypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Removes a tag from an Amazon Web Services resource.

Type annotations for `session.create_client("datasync").untag_resource` method.

Boto3 documentation:
[DataSync.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Keys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_agent"></a>

### update_agent

Updates the name of an agent.

Type annotations for `session.create_client("datasync").update_agent` method.

Boto3 documentation:
[DataSync.Client.update_agent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.update_agent)

Asynchronous method. Use `await update_agent(...)` for a synchronous call.

Arguments mapping described in
[UpdateAgentRequestRequestTypeDef](./type_defs.md#updateagentrequestrequesttypedef).

Keyword-only arguments:

- `AgentArn`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_location\_hdfs"></a>

### update_location_hdfs

Updates some parameters of a previously created location for a Hadoop
Distributed File System cluster.

Type annotations for `session.create_client("datasync").update_location_hdfs`
method.

Boto3 documentation:
[DataSync.Client.update_location_hdfs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.update_location_hdfs)

Asynchronous method. Use `await update_location_hdfs(...)` for a synchronous
call.

Arguments mapping described in
[UpdateLocationHdfsRequestRequestTypeDef](./type_defs.md#updatelocationhdfsrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*
- `Subdirectory`: `str`
- `NameNodes`:
  `Sequence`\[[HdfsNameNodeTypeDef](./type_defs.md#hdfsnamenodetypedef)\]
- `BlockSize`: `int`
- `ReplicationFactor`: `int`
- `KmsKeyProviderUri`: `str`
- `QopConfiguration`:
  [QopConfigurationTypeDef](./type_defs.md#qopconfigurationtypedef)
- `AuthenticationType`:
  [HdfsAuthenticationTypeType](./literals.md#hdfsauthenticationtypetype)
- `SimpleUser`: `str`
- `KerberosPrincipal`: `str`
- `KerberosKeytab`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `KerberosKrb5Conf`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `AgentArns`: `Sequence`\[`str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_location\_nfs"></a>

### update_location_nfs

Updates some of the parameters of a previously created location for Network
File System (NFS) access.

Type annotations for `session.create_client("datasync").update_location_nfs`
method.

Boto3 documentation:
[DataSync.Client.update_location_nfs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.update_location_nfs)

Asynchronous method. Use `await update_location_nfs(...)` for a synchronous
call.

Arguments mapping described in
[UpdateLocationNfsRequestRequestTypeDef](./type_defs.md#updatelocationnfsrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*
- `Subdirectory`: `str`
- `OnPremConfig`: [OnPremConfigTypeDef](./type_defs.md#onpremconfigtypedef)
- `MountOptions`:
  [NfsMountOptionsTypeDef](./type_defs.md#nfsmountoptionstypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_location\_object\_storage"></a>

### update_location_object_storage

Updates some of the parameters of a previously created location for
self-managed object storage server access.

Type annotations for
`session.create_client("datasync").update_location_object_storage` method.

Boto3 documentation:
[DataSync.Client.update_location_object_storage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.update_location_object_storage)

Asynchronous method. Use `await update_location_object_storage(...)` for a
synchronous call.

Arguments mapping described in
[UpdateLocationObjectStorageRequestRequestTypeDef](./type_defs.md#updatelocationobjectstoragerequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*
- `ServerPort`: `int`
- `ServerProtocol`:
  [ObjectStorageServerProtocolType](./literals.md#objectstorageserverprotocoltype)
- `Subdirectory`: `str`
- `AccessKey`: `str`
- `SecretKey`: `str`
- `AgentArns`: `Sequence`\[`str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_location\_smb"></a>

### update_location_smb

Updates some of the parameters of a previously created location for Server
Message Block (SMB) file system access.

Type annotations for `session.create_client("datasync").update_location_smb`
method.

Boto3 documentation:
[DataSync.Client.update_location_smb](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.update_location_smb)

Asynchronous method. Use `await update_location_smb(...)` for a synchronous
call.

Arguments mapping described in
[UpdateLocationSmbRequestRequestTypeDef](./type_defs.md#updatelocationsmbrequestrequesttypedef).

Keyword-only arguments:

- `LocationArn`: `str` *(required)*
- `Subdirectory`: `str`
- `User`: `str`
- `Domain`: `str`
- `Password`: `str`
- `AgentArns`: `Sequence`\[`str`\]
- `MountOptions`:
  [SmbMountOptionsTypeDef](./type_defs.md#smbmountoptionstypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_task"></a>

### update_task

Updates the metadata associated with a task.

Type annotations for `session.create_client("datasync").update_task` method.

Boto3 documentation:
[DataSync.Client.update_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.update_task)

Asynchronous method. Use `await update_task(...)` for a synchronous call.

Arguments mapping described in
[UpdateTaskRequestRequestTypeDef](./type_defs.md#updatetaskrequestrequesttypedef).

Keyword-only arguments:

- `TaskArn`: `str` *(required)*
- `Options`: [OptionsTypeDef](./type_defs.md#optionstypedef)
- `Excludes`:
  `Sequence`\[[FilterRuleTypeDef](./type_defs.md#filterruletypedef)\]
- `Schedule`: [TaskScheduleTypeDef](./type_defs.md#taskscheduletypedef)
- `Name`: `str`
- `CloudWatchLogGroupArn`: `str`
- `Includes`:
  `Sequence`\[[FilterRuleTypeDef](./type_defs.md#filterruletypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_task\_execution"></a>

### update_task_execution

Updates execution of a task.

Type annotations for `session.create_client("datasync").update_task_execution`
method.

Boto3 documentation:
[DataSync.Client.update_task_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.update_task_execution)

Asynchronous method. Use `await update_task_execution(...)` for a synchronous
call.

Arguments mapping described in
[UpdateTaskExecutionRequestRequestTypeDef](./type_defs.md#updatetaskexecutionrequestrequesttypedef).

Keyword-only arguments:

- `TaskExecutionArn`: `str` *(required)*
- `Options`: [OptionsTypeDef](./type_defs.md#optionstypedef) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("datasync").__aenter__` method.

Boto3 documentation:
[DataSync.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [DataSyncClient](#datasyncclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("datasync").__aexit__` method.

Boto3 documentation:
[DataSync.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datasync.html#DataSync.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("datasync").get_paginator` method
with overloads.

- `client.get_paginator("list_agents")` ->
  [ListAgentsPaginator](./paginators.md#listagentspaginator)
- `client.get_paginator("list_locations")` ->
  [ListLocationsPaginator](./paginators.md#listlocationspaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- `client.get_paginator("list_task_executions")` ->
  [ListTaskExecutionsPaginator](./paginators.md#listtaskexecutionspaginator)
- `client.get_paginator("list_tasks")` ->
  [ListTasksPaginator](./paginators.md#listtaskspaginator)
