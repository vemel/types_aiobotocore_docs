<a id="cloudwatchrumclient-for-aiobotocore-cloudwatchrum-module"></a>

# CloudWatchRUMClient for aiobotocore CloudWatchRUM module

> [Index](..) > [CloudWatchRUM](.) > CloudWatchRUMClient

Auto-generated documentation for
[CloudWatchRUM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM)
type annotations stubs module
[types-aiobotocore-rum](https://pypi.org/project/types-aiobotocore-rum/).

- [CloudWatchRUMClient for aiobotocore CloudWatchRUM module](#cloudwatchrumclient-for-aiobotocore-cloudwatchrum-module)
  - [CloudWatchRUMClient](#cloudwatchrumclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_app_monitor](#create_app_monitor)
    - [delete_app_monitor](#delete_app_monitor)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_app_monitor](#get_app_monitor)
    - [get_app_monitor_data](#get_app_monitor_data)
    - [list_app_monitors](#list_app_monitors)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_rum_events](#put_rum_events)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_app_monitor](#update_app_monitor)
    - [get_paginator](#get_paginator)

<a id="cloudwatchrumclient"></a>

## CloudWatchRUMClient

Type annotations for `aiobotocore.create_client("rum")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_rum.client import CloudWatchRUMClient

def get_rum_client() -> CloudWatchRUMClient:
    return Session().client("rum")
```

Boto3 documentation:
[CloudWatchRUM.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_rum.client import Exceptions

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
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

CloudWatchRUMClient exceptions.

Type annotations for `aiobotocore.create_client("rum").exceptions` method.

Boto3 documentation:
[CloudWatchRUM.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("rum").can_paginate` method.

Boto3 documentation:
[CloudWatchRUM.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_app_monitor"></a>

### create_app_monitor

Creates a Amazon CloudWatch RUM app monitor, which collects telemetry data from
your application and sends that data to RUM.

Type annotations for `aiobotocore.create_client("rum").create_app_monitor`
method.

Boto3 documentation:
[CloudWatchRUM.Client.create_app_monitor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.create_app_monitor)

Asynchronous method. Use `await create_app_monitor(...)` for a synchronous
call.

Arguments mapping described in
[CreateAppMonitorRequestRequestTypeDef](./type_defs.md#createappmonitorrequestrequesttypedef).

Keyword-only arguments:

- `Domain`: `str` *(required)*
- `Name`: `str` *(required)*
- `AppMonitorConfiguration`:
  [AppMonitorConfigurationTypeDef](./type_defs.md#appmonitorconfigurationtypedef)
- `CwLogEnabled`: `bool`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateAppMonitorResponseTypeDef](./type_defs.md#createappmonitorresponsetypedef).

<a id="delete_app_monitor"></a>

### delete_app_monitor

Deletes an existing app monitor.

Type annotations for `aiobotocore.create_client("rum").delete_app_monitor`
method.

Boto3 documentation:
[CloudWatchRUM.Client.delete_app_monitor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.delete_app_monitor)

Asynchronous method. Use `await delete_app_monitor(...)` for a synchronous
call.

Arguments mapping described in
[DeleteAppMonitorRequestRequestTypeDef](./type_defs.md#deleteappmonitorrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("rum").generate_presigned_url`
method.

Boto3 documentation:
[CloudWatchRUM.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_app_monitor"></a>

### get_app_monitor

Retrieves the complete configuration information for one app monitor.

Type annotations for `aiobotocore.create_client("rum").get_app_monitor` method.

Boto3 documentation:
[CloudWatchRUM.Client.get_app_monitor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.get_app_monitor)

Asynchronous method. Use `await get_app_monitor(...)` for a synchronous call.

Arguments mapping described in
[GetAppMonitorRequestRequestTypeDef](./type_defs.md#getappmonitorrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAppMonitorResponseTypeDef](./type_defs.md#getappmonitorresponsetypedef).

<a id="get_app_monitor_data"></a>

### get_app_monitor_data

Retrieves the raw performance events that RUM has collected from your web
application, so that you can do your own processing or analysis of this data.

Type annotations for `aiobotocore.create_client("rum").get_app_monitor_data`
method.

Boto3 documentation:
[CloudWatchRUM.Client.get_app_monitor_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.get_app_monitor_data)

Asynchronous method. Use `await get_app_monitor_data(...)` for a synchronous
call.

Arguments mapping described in
[GetAppMonitorDataRequestRequestTypeDef](./type_defs.md#getappmonitordatarequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `TimeRange`: [TimeRangeTypeDef](./type_defs.md#timerangetypedef) *(required)*
- `Filters`:
  `Sequence`\[[QueryFilterTypeDef](./type_defs.md#queryfiltertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetAppMonitorDataResponseTypeDef](./type_defs.md#getappmonitordataresponsetypedef).

<a id="list_app_monitors"></a>

### list_app_monitors

Returns a list of the Amazon CloudWatch RUM app monitors in the account.

Type annotations for `aiobotocore.create_client("rum").list_app_monitors`
method.

Boto3 documentation:
[CloudWatchRUM.Client.list_app_monitors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.list_app_monitors)

Asynchronous method. Use `await list_app_monitors(...)` for a synchronous call.

Arguments mapping described in
[ListAppMonitorsRequestRequestTypeDef](./type_defs.md#listappmonitorsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAppMonitorsResponseTypeDef](./type_defs.md#listappmonitorsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Displays the tags associated with a CloudWatch RUM resource.

Type annotations for `aiobotocore.create_client("rum").list_tags_for_resource`
method.

Boto3 documentation:
[CloudWatchRUM.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_rum_events"></a>

### put_rum_events

Sends telemetry events about your application performance and user behavior to
CloudWatch RUM.

Type annotations for `aiobotocore.create_client("rum").put_rum_events` method.

Boto3 documentation:
[CloudWatchRUM.Client.put_rum_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.put_rum_events)

Asynchronous method. Use `await put_rum_events(...)` for a synchronous call.

Arguments mapping described in
[PutRumEventsRequestRequestTypeDef](./type_defs.md#putrumeventsrequestrequesttypedef).

Keyword-only arguments:

- `AppMonitorDetails`:
  [AppMonitorDetailsTypeDef](./type_defs.md#appmonitordetailstypedef)
  *(required)*
- `BatchId`: `str` *(required)*
- `Id`: `str` *(required)*
- `RumEvents`: `Sequence`\[[RumEventTypeDef](./type_defs.md#rumeventtypedef)\]
  *(required)*
- `UserDetails`: [UserDetailsTypeDef](./type_defs.md#userdetailstypedef)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Assigns one or more tags (key-value pairs) to the specified CloudWatch RUM
resource.

Type annotations for `aiobotocore.create_client("rum").tag_resource` method.

Boto3 documentation:
[CloudWatchRUM.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes one or more tags from the specified resource.

Type annotations for `aiobotocore.create_client("rum").untag_resource` method.

Boto3 documentation:
[CloudWatchRUM.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_app_monitor"></a>

### update_app_monitor

Updates the configuration of an existing app monitor.

Type annotations for `aiobotocore.create_client("rum").update_app_monitor`
method.

Boto3 documentation:
[CloudWatchRUM.Client.update_app_monitor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.update_app_monitor)

Asynchronous method. Use `await update_app_monitor(...)` for a synchronous
call.

Arguments mapping described in
[UpdateAppMonitorRequestRequestTypeDef](./type_defs.md#updateappmonitorrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `AppMonitorConfiguration`:
  [AppMonitorConfigurationTypeDef](./type_defs.md#appmonitorconfigurationtypedef)
- `CwLogEnabled`: `bool`
- `Domain`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("rum").get_paginator` method
with overloads.

- `client.get_paginator("get_app_monitor_data")` ->
  [GetAppMonitorDataPaginator](./paginators.md#getappmonitordatapaginator)
- `client.get_paginator("list_app_monitors")` ->
  [ListAppMonitorsPaginator](./paginators.md#listappmonitorspaginator)
