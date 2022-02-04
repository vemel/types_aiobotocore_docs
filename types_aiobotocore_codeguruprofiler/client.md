<a id="codeguruprofilerclient-for-aiobotocore-codeguruprofiler-module"></a>

# CodeGuruProfilerClient for aiobotocore CodeGuruProfiler module

> [Index](..) > [CodeGuruProfiler](.) > CodeGuruProfilerClient

Auto-generated documentation for
[CodeGuruProfiler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler)
type annotations stubs module
[types-aiobotocore-codeguruprofiler](https://pypi.org/project/types-aiobotocore-codeguruprofiler/).

- [CodeGuruProfilerClient for aiobotocore CodeGuruProfiler module](#codeguruprofilerclient-for-aiobotocore-codeguruprofiler-module)
  - [CodeGuruProfilerClient](#codeguruprofilerclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_notification_channels](#add_notification_channels)
    - [batch_get_frame_metric_data](#batch_get_frame_metric_data)
    - [can_paginate](#can_paginate)
    - [configure_agent](#configure_agent)
    - [create_profiling_group](#create_profiling_group)
    - [delete_profiling_group](#delete_profiling_group)
    - [describe_profiling_group](#describe_profiling_group)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_findings_report_account_summary](#get_findings_report_account_summary)
    - [get_notification_configuration](#get_notification_configuration)
    - [get_policy](#get_policy)
    - [get_profile](#get_profile)
    - [get_recommendations](#get_recommendations)
    - [list_findings_reports](#list_findings_reports)
    - [list_profile_times](#list_profile_times)
    - [list_profiling_groups](#list_profiling_groups)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [post_agent_profile](#post_agent_profile)
    - [put_permission](#put_permission)
    - [remove_notification_channel](#remove_notification_channel)
    - [remove_permission](#remove_permission)
    - [submit_feedback](#submit_feedback)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_profiling_group](#update_profiling_group)
    - [get_paginator](#get_paginator)

<a id="codeguruprofilerclient"></a>

## CodeGuruProfilerClient

Type annotations for `aiobotocore.create_client("codeguruprofiler")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_codeguruprofiler.client import CodeGuruProfilerClient

def get_codeguruprofiler_client() -> CodeGuruProfilerClient:
    return Session().client("codeguruprofiler")
```

Boto3 documentation:
[CodeGuruProfiler.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_codeguruprofiler.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

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

CodeGuruProfilerClient exceptions.

Type annotations for `aiobotocore.create_client("codeguruprofiler").exceptions`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add_notification_channels"></a>

### add_notification_channels

Add up to 2 anomaly notifications channels for a profiling group.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").add_notification_channels`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.add_notification_channels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.add_notification_channels)

Asynchronous method. Use `await add_notification_channels(...)` for a
synchronous call.

Arguments mapping described in
[AddNotificationChannelsRequestRequestTypeDef](./type_defs.md#addnotificationchannelsrequestrequesttypedef).

Keyword-only arguments:

- `channels`: `Sequence`\[[ChannelTypeDef](./type_defs.md#channeltypedef)\]
  *(required)*
- `profilingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[AddNotificationChannelsResponseTypeDef](./type_defs.md#addnotificationchannelsresponsetypedef).

<a id="batch_get_frame_metric_data"></a>

### batch_get_frame_metric_data

Returns the time series of values for a requested list of frame metrics from a
time period.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").batch_get_frame_metric_data`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.batch_get_frame_metric_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.batch_get_frame_metric_data)

Asynchronous method. Use `await batch_get_frame_metric_data(...)` for a
synchronous call.

Arguments mapping described in
[BatchGetFrameMetricDataRequestRequestTypeDef](./type_defs.md#batchgetframemetricdatarequestrequesttypedef).

Keyword-only arguments:

- `profilingGroupName`: `str` *(required)*
- `endTime`: `Union`\[`datetime`, `str`\]
- `frameMetrics`:
  `Sequence`\[[FrameMetricTypeDef](./type_defs.md#framemetrictypedef)\]
- `period`: `str`
- `startTime`: `Union`\[`datetime`, `str`\]
- `targetResolution`:
  [AggregationPeriodType](./literals.md#aggregationperiodtype)

Returns a `Coroutine` for
[BatchGetFrameMetricDataResponseTypeDef](./type_defs.md#batchgetframemetricdataresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").can_paginate` method.

Boto3 documentation:
[CodeGuruProfiler.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="configure_agent"></a>

### configure_agent

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").configure_agent` method.

Boto3 documentation:
[CodeGuruProfiler.Client.configure_agent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.configure_agent)

Asynchronous method. Use `await configure_agent(...)` for a synchronous call.

Arguments mapping described in
[ConfigureAgentRequestRequestTypeDef](./type_defs.md#configureagentrequestrequesttypedef).

Keyword-only arguments:

- `profilingGroupName`: `str` *(required)*
- `fleetInstanceId`: `str`
- `metadata`: `Mapping`\[[MetadataFieldType](./literals.md#metadatafieldtype),
  `str`\]

Returns a `Coroutine` for
[ConfigureAgentResponseTypeDef](./type_defs.md#configureagentresponsetypedef).

<a id="create_profiling_group"></a>

### create_profiling_group

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").create_profiling_group` method.

Boto3 documentation:
[CodeGuruProfiler.Client.create_profiling_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.create_profiling_group)

Asynchronous method. Use `await create_profiling_group(...)` for a synchronous
call.

Arguments mapping described in
[CreateProfilingGroupRequestRequestTypeDef](./type_defs.md#createprofilinggrouprequestrequesttypedef).

Keyword-only arguments:

- `clientToken`: `str` *(required)*
- `profilingGroupName`: `str` *(required)*
- `agentOrchestrationConfig`:
  [AgentOrchestrationConfigTypeDef](./type_defs.md#agentorchestrationconfigtypedef)
- `computePlatform`: [ComputePlatformType](./literals.md#computeplatformtype)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateProfilingGroupResponseTypeDef](./type_defs.md#createprofilinggroupresponsetypedef).

<a id="delete_profiling_group"></a>

### delete_profiling_group

Deletes a profiling group.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").delete_profiling_group` method.

Boto3 documentation:
[CodeGuruProfiler.Client.delete_profiling_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.delete_profiling_group)

Asynchronous method. Use `await delete_profiling_group(...)` for a synchronous
call.

Arguments mapping described in
[DeleteProfilingGroupRequestRequestTypeDef](./type_defs.md#deleteprofilinggrouprequestrequesttypedef).

Keyword-only arguments:

- `profilingGroupName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_profiling_group"></a>

### describe_profiling_group

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").describe_profiling_group`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.describe_profiling_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.describe_profiling_group)

Asynchronous method. Use `await describe_profiling_group(...)` for a
synchronous call.

Arguments mapping described in
[DescribeProfilingGroupRequestRequestTypeDef](./type_defs.md#describeprofilinggrouprequestrequesttypedef).

Keyword-only arguments:

- `profilingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeProfilingGroupResponseTypeDef](./type_defs.md#describeprofilinggroupresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").generate_presigned_url` method.

Boto3 documentation:
[CodeGuruProfiler.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_findings_report_account_summary"></a>

### get_findings_report_account_summary

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").get_findings_report_account_summary`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.get_findings_report_account_summary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.get_findings_report_account_summary)

Asynchronous method. Use `await get_findings_report_account_summary(...)` for a
synchronous call.

Arguments mapping described in
[GetFindingsReportAccountSummaryRequestRequestTypeDef](./type_defs.md#getfindingsreportaccountsummaryrequestrequesttypedef).

Keyword-only arguments:

- `dailyReportsOnly`: `bool`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[GetFindingsReportAccountSummaryResponseTypeDef](./type_defs.md#getfindingsreportaccountsummaryresponsetypedef).

<a id="get_notification_configuration"></a>

### get_notification_configuration

Get the current configuration for anomaly notifications for a profiling group.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").get_notification_configuration`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.get_notification_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.get_notification_configuration)

Asynchronous method. Use `await get_notification_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetNotificationConfigurationRequestRequestTypeDef](./type_defs.md#getnotificationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `profilingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[GetNotificationConfigurationResponseTypeDef](./type_defs.md#getnotificationconfigurationresponsetypedef).

<a id="get_policy"></a>

### get_policy

Returns the JSON-formatted resource-based policy on a profiling group.

Type annotations for `aiobotocore.create_client("codeguruprofiler").get_policy`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.get_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.get_policy)

Asynchronous method. Use `await get_policy(...)` for a synchronous call.

Arguments mapping described in
[GetPolicyRequestRequestTypeDef](./type_defs.md#getpolicyrequestrequesttypedef).

Keyword-only arguments:

- `profilingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[GetPolicyResponseTypeDef](./type_defs.md#getpolicyresponsetypedef).

<a id="get_profile"></a>

### get_profile

Gets the aggregated profile of a profiling group for a specified time range.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").get_profile` method.

Boto3 documentation:
[CodeGuruProfiler.Client.get_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.get_profile)

Asynchronous method. Use `await get_profile(...)` for a synchronous call.

Arguments mapping described in
[GetProfileRequestRequestTypeDef](./type_defs.md#getprofilerequestrequesttypedef).

Keyword-only arguments:

- `profilingGroupName`: `str` *(required)*
- `accept`: `str`
- `endTime`: `Union`\[`datetime`, `str`\]
- `maxDepth`: `int`
- `period`: `str`
- `startTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[GetProfileResponseTypeDef](./type_defs.md#getprofileresponsetypedef).

<a id="get_recommendations"></a>

### get_recommendations

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").get_recommendations` method.

Boto3 documentation:
[CodeGuruProfiler.Client.get_recommendations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.get_recommendations)

Asynchronous method. Use `await get_recommendations(...)` for a synchronous
call.

Arguments mapping described in
[GetRecommendationsRequestRequestTypeDef](./type_defs.md#getrecommendationsrequestrequesttypedef).

Keyword-only arguments:

- `endTime`: `Union`\[`datetime`, `str`\] *(required)*
- `profilingGroupName`: `str` *(required)*
- `startTime`: `Union`\[`datetime`, `str`\] *(required)*
- `locale`: `str`

Returns a `Coroutine` for
[GetRecommendationsResponseTypeDef](./type_defs.md#getrecommendationsresponsetypedef).

<a id="list_findings_reports"></a>

### list_findings_reports

List the available reports for a given profiling group and time range.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").list_findings_reports` method.

Boto3 documentation:
[CodeGuruProfiler.Client.list_findings_reports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.list_findings_reports)

Asynchronous method. Use `await list_findings_reports(...)` for a synchronous
call.

Arguments mapping described in
[ListFindingsReportsRequestRequestTypeDef](./type_defs.md#listfindingsreportsrequestrequesttypedef).

Keyword-only arguments:

- `endTime`: `Union`\[`datetime`, `str`\] *(required)*
- `profilingGroupName`: `str` *(required)*
- `startTime`: `Union`\[`datetime`, `str`\] *(required)*
- `dailyReportsOnly`: `bool`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListFindingsReportsResponseTypeDef](./type_defs.md#listfindingsreportsresponsetypedef).

<a id="list_profile_times"></a>

### list_profile_times

Lists the start times of the available aggregated profiles of a profiling group
for an aggregation period within the specified time range.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").list_profile_times` method.

Boto3 documentation:
[CodeGuruProfiler.Client.list_profile_times](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.list_profile_times)

Asynchronous method. Use `await list_profile_times(...)` for a synchronous
call.

Arguments mapping described in
[ListProfileTimesRequestRequestTypeDef](./type_defs.md#listprofiletimesrequestrequesttypedef).

Keyword-only arguments:

- `endTime`: `Union`\[`datetime`, `str`\] *(required)*
- `period`: [AggregationPeriodType](./literals.md#aggregationperiodtype)
  *(required)*
- `profilingGroupName`: `str` *(required)*
- `startTime`: `Union`\[`datetime`, `str`\] *(required)*
- `maxResults`: `int`
- `nextToken`: `str`
- `orderBy`: [OrderByType](./literals.md#orderbytype)

Returns a `Coroutine` for
[ListProfileTimesResponseTypeDef](./type_defs.md#listprofiletimesresponsetypedef).

<a id="list_profiling_groups"></a>

### list_profiling_groups

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").list_profiling_groups` method.

Boto3 documentation:
[CodeGuruProfiler.Client.list_profiling_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.list_profiling_groups)

Asynchronous method. Use `await list_profiling_groups(...)` for a synchronous
call.

Arguments mapping described in
[ListProfilingGroupsRequestRequestTypeDef](./type_defs.md#listprofilinggroupsrequestrequesttypedef).

Keyword-only arguments:

- `includeDescription`: `bool`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListProfilingGroupsResponseTypeDef](./type_defs.md#listprofilinggroupsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Returns a list of the tags that are assigned to a specified resource.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").list_tags_for_resource` method.

Boto3 documentation:
[CodeGuruProfiler.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="post_agent_profile"></a>

### post_agent_profile

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").post_agent_profile` method.

Boto3 documentation:
[CodeGuruProfiler.Client.post_agent_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.post_agent_profile)

Asynchronous method. Use `await post_agent_profile(...)` for a synchronous
call.

Arguments mapping described in
[PostAgentProfileRequestRequestTypeDef](./type_defs.md#postagentprofilerequestrequesttypedef).

Keyword-only arguments:

- `agentProfile`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `contentType`: `str` *(required)*
- `profilingGroupName`: `str` *(required)*
- `profileToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_permission"></a>

### put_permission

Adds permissions to a profiling group's resource-based policy that are provided
using an action group.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").put_permission` method.

Boto3 documentation:
[CodeGuruProfiler.Client.put_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.put_permission)

Asynchronous method. Use `await put_permission(...)` for a synchronous call.

Arguments mapping described in
[PutPermissionRequestRequestTypeDef](./type_defs.md#putpermissionrequestrequesttypedef).

Keyword-only arguments:

- `actionGroup`: `Literal['agentPermissions']` (see
  [ActionGroupType](./literals.md#actiongrouptype)) *(required)*
- `principals`: `Sequence`\[`str`\] *(required)*
- `profilingGroupName`: `str` *(required)*
- `revisionId`: `str`

Returns a `Coroutine` for
[PutPermissionResponseTypeDef](./type_defs.md#putpermissionresponsetypedef).

<a id="remove_notification_channel"></a>

### remove_notification_channel

Remove one anomaly notifications channel for a profiling group.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").remove_notification_channel`
method.

Boto3 documentation:
[CodeGuruProfiler.Client.remove_notification_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.remove_notification_channel)

Asynchronous method. Use `await remove_notification_channel(...)` for a
synchronous call.

Arguments mapping described in
[RemoveNotificationChannelRequestRequestTypeDef](./type_defs.md#removenotificationchannelrequestrequesttypedef).

Keyword-only arguments:

- `channelId`: `str` *(required)*
- `profilingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[RemoveNotificationChannelResponseTypeDef](./type_defs.md#removenotificationchannelresponsetypedef).

<a id="remove_permission"></a>

### remove_permission

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").remove_permission` method.

Boto3 documentation:
[CodeGuruProfiler.Client.remove_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.remove_permission)

Asynchronous method. Use `await remove_permission(...)` for a synchronous call.

Arguments mapping described in
[RemovePermissionRequestRequestTypeDef](./type_defs.md#removepermissionrequestrequesttypedef).

Keyword-only arguments:

- `actionGroup`: `Literal['agentPermissions']` (see
  [ActionGroupType](./literals.md#actiongrouptype)) *(required)*
- `profilingGroupName`: `str` *(required)*
- `revisionId`: `str` *(required)*

Returns a `Coroutine` for
[RemovePermissionResponseTypeDef](./type_defs.md#removepermissionresponsetypedef).

<a id="submit_feedback"></a>

### submit_feedback

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").submit_feedback` method.

Boto3 documentation:
[CodeGuruProfiler.Client.submit_feedback](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.submit_feedback)

Asynchronous method. Use `await submit_feedback(...)` for a synchronous call.

Arguments mapping described in
[SubmitFeedbackRequestRequestTypeDef](./type_defs.md#submitfeedbackrequestrequesttypedef).

Keyword-only arguments:

- `anomalyInstanceId`: `str` *(required)*
- `profilingGroupName`: `str` *(required)*
- `type`: [FeedbackTypeType](./literals.md#feedbacktypetype) *(required)*
- `comment`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Use to assign one or more tags to a resource.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").tag_resource` method.

Boto3 documentation:
[CodeGuruProfiler.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Use to remove one or more tags from a resource.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").untag_resource` method.

Boto3 documentation:
[CodeGuruProfiler.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_profiling_group"></a>

### update_profiling_group

.

Type annotations for
`aiobotocore.create_client("codeguruprofiler").update_profiling_group` method.

Boto3 documentation:
[CodeGuruProfiler.Client.update_profiling_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Client.update_profiling_group)

Asynchronous method. Use `await update_profiling_group(...)` for a synchronous
call.

Arguments mapping described in
[UpdateProfilingGroupRequestRequestTypeDef](./type_defs.md#updateprofilinggrouprequestrequesttypedef).

Keyword-only arguments:

- `agentOrchestrationConfig`:
  [AgentOrchestrationConfigTypeDef](./type_defs.md#agentorchestrationconfigtypedef)
  *(required)*
- `profilingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[UpdateProfilingGroupResponseTypeDef](./type_defs.md#updateprofilinggroupresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("codeguruprofiler").get_paginator` method with
overloads.

- `client.get_paginator("list_profile_times")` ->
  [ListProfileTimesPaginator](./paginators.md#listprofiletimespaginator)
