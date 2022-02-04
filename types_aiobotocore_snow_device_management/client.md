<a id="snowdevicemanagementclient-for-aiobotocore-snowdevicemanagement-module"></a>

# SnowDeviceManagementClient for aiobotocore SnowDeviceManagement module

> [Index](..) > [SnowDeviceManagement](.) > SnowDeviceManagementClient

Auto-generated documentation for
[SnowDeviceManagement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement)
type annotations stubs module
[types-aiobotocore-snow-device-management](https://pypi.org/project/types-aiobotocore-snow-device-management/).

- [SnowDeviceManagementClient for aiobotocore SnowDeviceManagement module](#snowdevicemanagementclient-for-aiobotocore-snowdevicemanagement-module)
  - [SnowDeviceManagementClient](#snowdevicemanagementclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [cancel_task](#cancel_task)
    - [create_task](#create_task)
    - [describe_device](#describe_device)
    - [describe_device_ec2_instances](#describe_device_ec2_instances)
    - [describe_execution](#describe_execution)
    - [describe_task](#describe_task)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_device_resources](#list_device_resources)
    - [list_devices](#list_devices)
    - [list_executions](#list_executions)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_tasks](#list_tasks)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [get_paginator](#get_paginator)

<a id="snowdevicemanagementclient"></a>

## SnowDeviceManagementClient

Type annotations for `aiobotocore.create_client("snow-device-management")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_snow_device_management.client import SnowDeviceManagementClient

def get_snow-device-management_client() -> SnowDeviceManagementClient:
    return Session().client("snow-device-management")
```

Boto3 documentation:
[SnowDeviceManagement.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_snow_device_management.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

SnowDeviceManagementClient exceptions.

Type annotations for
`aiobotocore.create_client("snow-device-management").exceptions` method.

Boto3 documentation:
[SnowDeviceManagement.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("snow-device-management").can_paginate` method.

Boto3 documentation:
[SnowDeviceManagement.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_task"></a>

### cancel_task

Sends a cancel request for a specified task.

Type annotations for
`aiobotocore.create_client("snow-device-management").cancel_task` method.

Boto3 documentation:
[SnowDeviceManagement.Client.cancel_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.cancel_task)

Asynchronous method. Use `await cancel_task(...)` for a synchronous call.

Arguments mapping described in
[CancelTaskInputRequestTypeDef](./type_defs.md#canceltaskinputrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for
[CancelTaskOutputTypeDef](./type_defs.md#canceltaskoutputtypedef).

<a id="create_task"></a>

### create_task

Instructs one or more devices to start a task, such as unlocking or rebooting.

Type annotations for
`aiobotocore.create_client("snow-device-management").create_task` method.

Boto3 documentation:
[SnowDeviceManagement.Client.create_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.create_task)

Asynchronous method. Use `await create_task(...)` for a synchronous call.

Arguments mapping described in
[CreateTaskInputRequestTypeDef](./type_defs.md#createtaskinputrequesttypedef).

Keyword-only arguments:

- `command`: [CommandTypeDef](./type_defs.md#commandtypedef) *(required)*
- `targets`: `Sequence`\[`str`\] *(required)*
- `clientToken`: `str`
- `description`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateTaskOutputTypeDef](./type_defs.md#createtaskoutputtypedef).

<a id="describe_device"></a>

### describe_device

Checks device-specific information, such as the device type, software version,
IP addresses, and lock status.

Type annotations for
`aiobotocore.create_client("snow-device-management").describe_device` method.

Boto3 documentation:
[SnowDeviceManagement.Client.describe_device](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.describe_device)

Asynchronous method. Use `await describe_device(...)` for a synchronous call.

Arguments mapping described in
[DescribeDeviceInputRequestTypeDef](./type_defs.md#describedeviceinputrequesttypedef).

Keyword-only arguments:

- `managedDeviceId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDeviceOutputTypeDef](./type_defs.md#describedeviceoutputtypedef).

<a id="describe_device_ec2_instances"></a>

### describe_device_ec2_instances

Checks the current state of the Amazon EC2 instances.

Type annotations for
`aiobotocore.create_client("snow-device-management").describe_device_ec2_instances`
method.

Boto3 documentation:
[SnowDeviceManagement.Client.describe_device_ec2_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.describe_device_ec2_instances)

Asynchronous method. Use `await describe_device_ec2_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeDeviceEc2InputRequestTypeDef](./type_defs.md#describedeviceec2inputrequesttypedef).

Keyword-only arguments:

- `instanceIds`: `Sequence`\[`str`\] *(required)*
- `managedDeviceId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDeviceEc2OutputTypeDef](./type_defs.md#describedeviceec2outputtypedef).

<a id="describe_execution"></a>

### describe_execution

Checks the status of a remote task running on one or more target devices.

Type annotations for
`aiobotocore.create_client("snow-device-management").describe_execution`
method.

Boto3 documentation:
[SnowDeviceManagement.Client.describe_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.describe_execution)

Asynchronous method. Use `await describe_execution(...)` for a synchronous
call.

Arguments mapping described in
[DescribeExecutionInputRequestTypeDef](./type_defs.md#describeexecutioninputrequesttypedef).

Keyword-only arguments:

- `managedDeviceId`: `str` *(required)*
- `taskId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeExecutionOutputTypeDef](./type_defs.md#describeexecutionoutputtypedef).

<a id="describe_task"></a>

### describe_task

Checks the metadata for a given task on a device.

Type annotations for
`aiobotocore.create_client("snow-device-management").describe_task` method.

Boto3 documentation:
[SnowDeviceManagement.Client.describe_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.describe_task)

Asynchronous method. Use `await describe_task(...)` for a synchronous call.

Arguments mapping described in
[DescribeTaskInputRequestTypeDef](./type_defs.md#describetaskinputrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTaskOutputTypeDef](./type_defs.md#describetaskoutputtypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("snow-device-management").generate_presigned_url`
method.

Boto3 documentation:
[SnowDeviceManagement.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_device_resources"></a>

### list_device_resources

Returns a list of the Amazon Web Services resources available for a device.

Type annotations for
`aiobotocore.create_client("snow-device-management").list_device_resources`
method.

Boto3 documentation:
[SnowDeviceManagement.Client.list_device_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.list_device_resources)

Asynchronous method. Use `await list_device_resources(...)` for a synchronous
call.

Arguments mapping described in
[ListDeviceResourcesInputRequestTypeDef](./type_defs.md#listdeviceresourcesinputrequesttypedef).

Keyword-only arguments:

- `managedDeviceId`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`
- `type`: `str`

Returns a `Coroutine` for
[ListDeviceResourcesOutputTypeDef](./type_defs.md#listdeviceresourcesoutputtypedef).

<a id="list_devices"></a>

### list_devices

Returns a list of all devices on your Amazon Web Services account that have
Amazon Web Services Snow Device Management enabled in the Amazon Web Services
Region where the command is run.

Type annotations for
`aiobotocore.create_client("snow-device-management").list_devices` method.

Boto3 documentation:
[SnowDeviceManagement.Client.list_devices](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.list_devices)

Asynchronous method. Use `await list_devices(...)` for a synchronous call.

Arguments mapping described in
[ListDevicesInputRequestTypeDef](./type_defs.md#listdevicesinputrequesttypedef).

Keyword-only arguments:

- `jobId`: `str`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListDevicesOutputTypeDef](./type_defs.md#listdevicesoutputtypedef).

<a id="list_executions"></a>

### list_executions

Returns the status of tasks for one or more target devices.

Type annotations for
`aiobotocore.create_client("snow-device-management").list_executions` method.

Boto3 documentation:
[SnowDeviceManagement.Client.list_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.list_executions)

Asynchronous method. Use `await list_executions(...)` for a synchronous call.

Arguments mapping described in
[ListExecutionsInputRequestTypeDef](./type_defs.md#listexecutionsinputrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`
- `state`: [ExecutionStateType](./literals.md#executionstatetype)

Returns a `Coroutine` for
[ListExecutionsOutputTypeDef](./type_defs.md#listexecutionsoutputtypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Returns a list of tags for a managed device or task.

Type annotations for
`aiobotocore.create_client("snow-device-management").list_tags_for_resource`
method.

Boto3 documentation:
[SnowDeviceManagement.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef).

<a id="list_tasks"></a>

### list_tasks

Returns a list of tasks that can be filtered by state.

Type annotations for
`aiobotocore.create_client("snow-device-management").list_tasks` method.

Boto3 documentation:
[SnowDeviceManagement.Client.list_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.list_tasks)

Asynchronous method. Use `await list_tasks(...)` for a synchronous call.

Arguments mapping described in
[ListTasksInputRequestTypeDef](./type_defs.md#listtasksinputrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`
- `state`: [TaskStateType](./literals.md#taskstatetype)

Returns a `Coroutine` for
[ListTasksOutputTypeDef](./type_defs.md#listtasksoutputtypedef).

<a id="tag_resource"></a>

### tag_resource

Adds or replaces tags on a device or task.

Type annotations for
`aiobotocore.create_client("snow-device-management").tag_resource` method.

Boto3 documentation:
[SnowDeviceManagement.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="untag_resource"></a>

### untag_resource

Removes a tag from a device or task.

Type annotations for
`aiobotocore.create_client("snow-device-management").untag_resource` method.

Boto3 documentation:
[SnowDeviceManagement.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("snow-device-management").get_paginator` method with
overloads.

- `client.get_paginator("list_device_resources")` ->
  [ListDeviceResourcesPaginator](./paginators.md#listdeviceresourcespaginator)
- `client.get_paginator("list_devices")` ->
  [ListDevicesPaginator](./paginators.md#listdevicespaginator)
- `client.get_paginator("list_executions")` ->
  [ListExecutionsPaginator](./paginators.md#listexecutionspaginator)
- `client.get_paginator("list_tasks")` ->
  [ListTasksPaginator](./paginators.md#listtaskspaginator)
