<a id="mediatailorclient-for-aiobotocore-mediatailor-module"></a>

# MediaTailorClient for aiobotocore MediaTailor module

> [Index](../README.md) > [MediaTailor](./README.md) > MediaTailorClient

Auto-generated documentation for
[MediaTailor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
type annotations stubs module
[types-aiobotocore-mediatailor](https://pypi.org/project/types-aiobotocore-mediatailor/).

- [MediaTailorClient for aiobotocore MediaTailor module](#mediatailorclient-for-aiobotocore-mediatailor-module)
  - [MediaTailorClient](#mediatailorclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [configure_logs_for_playback_configuration](#configure_logs_for_playback_configuration)
    - [create_channel](#create_channel)
    - [create_prefetch_schedule](#create_prefetch_schedule)
    - [create_program](#create_program)
    - [create_source_location](#create_source_location)
    - [create_vod_source](#create_vod_source)
    - [delete_channel](#delete_channel)
    - [delete_channel_policy](#delete_channel_policy)
    - [delete_playback_configuration](#delete_playback_configuration)
    - [delete_prefetch_schedule](#delete_prefetch_schedule)
    - [delete_program](#delete_program)
    - [delete_source_location](#delete_source_location)
    - [delete_vod_source](#delete_vod_source)
    - [describe_channel](#describe_channel)
    - [describe_program](#describe_program)
    - [describe_source_location](#describe_source_location)
    - [describe_vod_source](#describe_vod_source)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_channel_policy](#get_channel_policy)
    - [get_channel_schedule](#get_channel_schedule)
    - [get_playback_configuration](#get_playback_configuration)
    - [get_prefetch_schedule](#get_prefetch_schedule)
    - [list_alerts](#list_alerts)
    - [list_channels](#list_channels)
    - [list_playback_configurations](#list_playback_configurations)
    - [list_prefetch_schedules](#list_prefetch_schedules)
    - [list_source_locations](#list_source_locations)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_vod_sources](#list_vod_sources)
    - [put_channel_policy](#put_channel_policy)
    - [put_playback_configuration](#put_playback_configuration)
    - [start_channel](#start_channel)
    - [stop_channel](#stop_channel)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_channel](#update_channel)
    - [update_source_location](#update_source_location)
    - [update_vod_source](#update_vod_source)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="mediatailorclient"></a>

## MediaTailorClient

Type annotations for `session.create_client("mediatailor")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_mediatailor.client import MediaTailorClient

session = get_session()
async with session.create_client("mediatailor") as client:
    client: MediaTailorClient
```

Boto3 documentation:
[MediaTailor.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_mediatailor.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.ClientError`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

MediaTailorClient exceptions.

Type annotations for `session.create_client("mediatailor").exceptions` method.

Boto3 documentation:
[MediaTailor.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("mediatailor").can_paginate`
method.

Boto3 documentation:
[MediaTailor.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="configure\_logs\_for\_playback\_configuration"></a>

### configure_logs_for_playback_configuration

Configures Amazon CloudWatch log settings for a playback configuration.

Type annotations for
`session.create_client("mediatailor").configure_logs_for_playback_configuration`
method.

Boto3 documentation:
[MediaTailor.Client.configure_logs_for_playback_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.configure_logs_for_playback_configuration)

Asynchronous method. Use `await configure_logs_for_playback_configuration(...)`
for a synchronous call.

Arguments mapping described in
[ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef](./type_defs.md#configurelogsforplaybackconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `PercentEnabled`: `int` *(required)*
- `PlaybackConfigurationName`: `str` *(required)*

Returns a `Coroutine` for
[ConfigureLogsForPlaybackConfigurationResponseTypeDef](./type_defs.md#configurelogsforplaybackconfigurationresponsetypedef).

<a id="create\_channel"></a>

### create_channel

Creates a channel.

Type annotations for `session.create_client("mediatailor").create_channel`
method.

Boto3 documentation:
[MediaTailor.Client.create_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.create_channel)

Asynchronous method. Use `await create_channel(...)` for a synchronous call.

Arguments mapping described in
[CreateChannelRequestRequestTypeDef](./type_defs.md#createchannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*
- `Outputs`:
  `Sequence`\[[RequestOutputItemTypeDef](./type_defs.md#requestoutputitemtypedef)\]
  *(required)*
- `PlaybackMode`: [PlaybackModeType](./literals.md#playbackmodetype)
  *(required)*
- `FillerSlate`: [SlateSourceTypeDef](./type_defs.md#slatesourcetypedef)
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateChannelResponseTypeDef](./type_defs.md#createchannelresponsetypedef).

<a id="create\_prefetch\_schedule"></a>

### create_prefetch_schedule

Creates a new prefetch schedule for the specified playback configuration.

Type annotations for
`session.create_client("mediatailor").create_prefetch_schedule` method.

Boto3 documentation:
[MediaTailor.Client.create_prefetch_schedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.create_prefetch_schedule)

Asynchronous method. Use `await create_prefetch_schedule(...)` for a
synchronous call.

Arguments mapping described in
[CreatePrefetchScheduleRequestRequestTypeDef](./type_defs.md#createprefetchschedulerequestrequesttypedef).

Keyword-only arguments:

- `Consumption`:
  [PrefetchConsumptionTypeDef](./type_defs.md#prefetchconsumptiontypedef)
  *(required)*
- `Name`: `str` *(required)*
- `PlaybackConfigurationName`: `str` *(required)*
- `Retrieval`:
  [PrefetchRetrievalTypeDef](./type_defs.md#prefetchretrievaltypedef)
  *(required)*
- `StreamId`: `str`

Returns a `Coroutine` for
[CreatePrefetchScheduleResponseTypeDef](./type_defs.md#createprefetchscheduleresponsetypedef).

<a id="create\_program"></a>

### create_program

Creates a program.

Type annotations for `session.create_client("mediatailor").create_program`
method.

Boto3 documentation:
[MediaTailor.Client.create_program](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.create_program)

Asynchronous method. Use `await create_program(...)` for a synchronous call.

Arguments mapping described in
[CreateProgramRequestRequestTypeDef](./type_defs.md#createprogramrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*
- `ProgramName`: `str` *(required)*
- `ScheduleConfiguration`:
  [ScheduleConfigurationTypeDef](./type_defs.md#scheduleconfigurationtypedef)
  *(required)*
- `SourceLocationName`: `str` *(required)*
- `VodSourceName`: `str` *(required)*
- `AdBreaks`: `Sequence`\[[AdBreakTypeDef](./type_defs.md#adbreaktypedef)\]

Returns a `Coroutine` for
[CreateProgramResponseTypeDef](./type_defs.md#createprogramresponsetypedef).

<a id="create\_source\_location"></a>

### create_source_location

Creates a source location on a specific channel.

Type annotations for
`session.create_client("mediatailor").create_source_location` method.

Boto3 documentation:
[MediaTailor.Client.create_source_location](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.create_source_location)

Asynchronous method. Use `await create_source_location(...)` for a synchronous
call.

Arguments mapping described in
[CreateSourceLocationRequestRequestTypeDef](./type_defs.md#createsourcelocationrequestrequesttypedef).

Keyword-only arguments:

- `HttpConfiguration`:
  [HttpConfigurationTypeDef](./type_defs.md#httpconfigurationtypedef)
  *(required)*
- `SourceLocationName`: `str` *(required)*
- `AccessConfiguration`:
  [AccessConfigurationTypeDef](./type_defs.md#accessconfigurationtypedef)
- `DefaultSegmentDeliveryConfiguration`:
  [DefaultSegmentDeliveryConfigurationTypeDef](./type_defs.md#defaultsegmentdeliveryconfigurationtypedef)
- `SegmentDeliveryConfigurations`:
  `Sequence`\[[SegmentDeliveryConfigurationTypeDef](./type_defs.md#segmentdeliveryconfigurationtypedef)\]
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateSourceLocationResponseTypeDef](./type_defs.md#createsourcelocationresponsetypedef).

<a id="create\_vod\_source"></a>

### create_vod_source

Creates name for a specific VOD source in a source location.

Type annotations for `session.create_client("mediatailor").create_vod_source`
method.

Boto3 documentation:
[MediaTailor.Client.create_vod_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.create_vod_source)

Asynchronous method. Use `await create_vod_source(...)` for a synchronous call.

Arguments mapping described in
[CreateVodSourceRequestRequestTypeDef](./type_defs.md#createvodsourcerequestrequesttypedef).

Keyword-only arguments:

- `HttpPackageConfigurations`:
  `Sequence`\[[HttpPackageConfigurationTypeDef](./type_defs.md#httppackageconfigurationtypedef)\]
  *(required)*
- `SourceLocationName`: `str` *(required)*
- `VodSourceName`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateVodSourceResponseTypeDef](./type_defs.md#createvodsourceresponsetypedef).

<a id="delete\_channel"></a>

### delete_channel

Deletes a channel.

Type annotations for `session.create_client("mediatailor").delete_channel`
method.

Boto3 documentation:
[MediaTailor.Client.delete_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.delete_channel)

Asynchronous method. Use `await delete_channel(...)` for a synchronous call.

Arguments mapping described in
[DeleteChannelRequestRequestTypeDef](./type_defs.md#deletechannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_channel\_policy"></a>

### delete_channel_policy

Deletes a channel's IAM policy.

Type annotations for
`session.create_client("mediatailor").delete_channel_policy` method.

Boto3 documentation:
[MediaTailor.Client.delete_channel_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.delete_channel_policy)

Asynchronous method. Use `await delete_channel_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteChannelPolicyRequestRequestTypeDef](./type_defs.md#deletechannelpolicyrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_playback\_configuration"></a>

### delete_playback_configuration

Deletes the playback configuration for the specified name.

Type annotations for
`session.create_client("mediatailor").delete_playback_configuration` method.

Boto3 documentation:
[MediaTailor.Client.delete_playback_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.delete_playback_configuration)

Asynchronous method. Use `await delete_playback_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeletePlaybackConfigurationRequestRequestTypeDef](./type_defs.md#deleteplaybackconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_prefetch\_schedule"></a>

### delete_prefetch_schedule

Deletes a prefetch schedule for a specific playback configuration.

Type annotations for
`session.create_client("mediatailor").delete_prefetch_schedule` method.

Boto3 documentation:
[MediaTailor.Client.delete_prefetch_schedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.delete_prefetch_schedule)

Asynchronous method. Use `await delete_prefetch_schedule(...)` for a
synchronous call.

Arguments mapping described in
[DeletePrefetchScheduleRequestRequestTypeDef](./type_defs.md#deleteprefetchschedulerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `PlaybackConfigurationName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_program"></a>

### delete_program

Deletes a specific program on a specific channel.

Type annotations for `session.create_client("mediatailor").delete_program`
method.

Boto3 documentation:
[MediaTailor.Client.delete_program](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.delete_program)

Asynchronous method. Use `await delete_program(...)` for a synchronous call.

Arguments mapping described in
[DeleteProgramRequestRequestTypeDef](./type_defs.md#deleteprogramrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*
- `ProgramName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_source\_location"></a>

### delete_source_location

Deletes a source location on a specific channel.

Type annotations for
`session.create_client("mediatailor").delete_source_location` method.

Boto3 documentation:
[MediaTailor.Client.delete_source_location](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.delete_source_location)

Asynchronous method. Use `await delete_source_location(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSourceLocationRequestRequestTypeDef](./type_defs.md#deletesourcelocationrequestrequesttypedef).

Keyword-only arguments:

- `SourceLocationName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_vod\_source"></a>

### delete_vod_source

Deletes a specific VOD source in a specific source location.

Type annotations for `session.create_client("mediatailor").delete_vod_source`
method.

Boto3 documentation:
[MediaTailor.Client.delete_vod_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.delete_vod_source)

Asynchronous method. Use `await delete_vod_source(...)` for a synchronous call.

Arguments mapping described in
[DeleteVodSourceRequestRequestTypeDef](./type_defs.md#deletevodsourcerequestrequesttypedef).

Keyword-only arguments:

- `SourceLocationName`: `str` *(required)*
- `VodSourceName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe\_channel"></a>

### describe_channel

Describes the properties of a specific channel.

Type annotations for `session.create_client("mediatailor").describe_channel`
method.

Boto3 documentation:
[MediaTailor.Client.describe_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.describe_channel)

Asynchronous method. Use `await describe_channel(...)` for a synchronous call.

Arguments mapping described in
[DescribeChannelRequestRequestTypeDef](./type_defs.md#describechannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelResponseTypeDef](./type_defs.md#describechannelresponsetypedef).

<a id="describe\_program"></a>

### describe_program

Retrieves the properties of the requested program.

Type annotations for `session.create_client("mediatailor").describe_program`
method.

Boto3 documentation:
[MediaTailor.Client.describe_program](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.describe_program)

Asynchronous method. Use `await describe_program(...)` for a synchronous call.

Arguments mapping described in
[DescribeProgramRequestRequestTypeDef](./type_defs.md#describeprogramrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*
- `ProgramName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeProgramResponseTypeDef](./type_defs.md#describeprogramresponsetypedef).

<a id="describe\_source\_location"></a>

### describe_source_location

Retrieves the properties of the requested source location.

Type annotations for
`session.create_client("mediatailor").describe_source_location` method.

Boto3 documentation:
[MediaTailor.Client.describe_source_location](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.describe_source_location)

Asynchronous method. Use `await describe_source_location(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSourceLocationRequestRequestTypeDef](./type_defs.md#describesourcelocationrequestrequesttypedef).

Keyword-only arguments:

- `SourceLocationName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeSourceLocationResponseTypeDef](./type_defs.md#describesourcelocationresponsetypedef).

<a id="describe\_vod\_source"></a>

### describe_vod_source

Provides details about a specific VOD source in a specific source location.

Type annotations for `session.create_client("mediatailor").describe_vod_source`
method.

Boto3 documentation:
[MediaTailor.Client.describe_vod_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.describe_vod_source)

Asynchronous method. Use `await describe_vod_source(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVodSourceRequestRequestTypeDef](./type_defs.md#describevodsourcerequestrequesttypedef).

Keyword-only arguments:

- `SourceLocationName`: `str` *(required)*
- `VodSourceName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeVodSourceResponseTypeDef](./type_defs.md#describevodsourceresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("mediatailor").generate_presigned_url` method.

Boto3 documentation:
[MediaTailor.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_channel\_policy"></a>

### get_channel_policy

Retrieves information about a channel's IAM policy.

Type annotations for `session.create_client("mediatailor").get_channel_policy`
method.

Boto3 documentation:
[MediaTailor.Client.get_channel_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.get_channel_policy)

Asynchronous method. Use `await get_channel_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetChannelPolicyRequestRequestTypeDef](./type_defs.md#getchannelpolicyrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*

Returns a `Coroutine` for
[GetChannelPolicyResponseTypeDef](./type_defs.md#getchannelpolicyresponsetypedef).

<a id="get\_channel\_schedule"></a>

### get_channel_schedule

Retrieves information about your channel's schedule.

Type annotations for
`session.create_client("mediatailor").get_channel_schedule` method.

Boto3 documentation:
[MediaTailor.Client.get_channel_schedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.get_channel_schedule)

Asynchronous method. Use `await get_channel_schedule(...)` for a synchronous
call.

Arguments mapping described in
[GetChannelScheduleRequestRequestTypeDef](./type_defs.md#getchannelschedulerequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*
- `DurationMinutes`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetChannelScheduleResponseTypeDef](./type_defs.md#getchannelscheduleresponsetypedef).

<a id="get\_playback\_configuration"></a>

### get_playback_configuration

Returns the playback configuration for the specified name.

Type annotations for
`session.create_client("mediatailor").get_playback_configuration` method.

Boto3 documentation:
[MediaTailor.Client.get_playback_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.get_playback_configuration)

Asynchronous method. Use `await get_playback_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetPlaybackConfigurationRequestRequestTypeDef](./type_defs.md#getplaybackconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetPlaybackConfigurationResponseTypeDef](./type_defs.md#getplaybackconfigurationresponsetypedef).

<a id="get\_prefetch\_schedule"></a>

### get_prefetch_schedule

Returns information about the prefetch schedule for a specific playback
configuration.

Type annotations for
`session.create_client("mediatailor").get_prefetch_schedule` method.

Boto3 documentation:
[MediaTailor.Client.get_prefetch_schedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.get_prefetch_schedule)

Asynchronous method. Use `await get_prefetch_schedule(...)` for a synchronous
call.

Arguments mapping described in
[GetPrefetchScheduleRequestRequestTypeDef](./type_defs.md#getprefetchschedulerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `PlaybackConfigurationName`: `str` *(required)*

Returns a `Coroutine` for
[GetPrefetchScheduleResponseTypeDef](./type_defs.md#getprefetchscheduleresponsetypedef).

<a id="list\_alerts"></a>

### list_alerts

Returns a list of alerts for the given resource.

Type annotations for `session.create_client("mediatailor").list_alerts` method.

Boto3 documentation:
[MediaTailor.Client.list_alerts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.list_alerts)

Asynchronous method. Use `await list_alerts(...)` for a synchronous call.

Arguments mapping described in
[ListAlertsRequestRequestTypeDef](./type_defs.md#listalertsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAlertsResponseTypeDef](./type_defs.md#listalertsresponsetypedef).

<a id="list\_channels"></a>

### list_channels

Retrieves a list of channels that are associated with this account.

Type annotations for `session.create_client("mediatailor").list_channels`
method.

Boto3 documentation:
[MediaTailor.Client.list_channels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.list_channels)

Asynchronous method. Use `await list_channels(...)` for a synchronous call.

Arguments mapping described in
[ListChannelsRequestRequestTypeDef](./type_defs.md#listchannelsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelsResponseTypeDef](./type_defs.md#listchannelsresponsetypedef).

<a id="list\_playback\_configurations"></a>

### list_playback_configurations

Returns a list of the playback configurations defined in AWS Elemental
MediaTailor.

Type annotations for
`session.create_client("mediatailor").list_playback_configurations` method.

Boto3 documentation:
[MediaTailor.Client.list_playback_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.list_playback_configurations)

Asynchronous method. Use `await list_playback_configurations(...)` for a
synchronous call.

Arguments mapping described in
[ListPlaybackConfigurationsRequestRequestTypeDef](./type_defs.md#listplaybackconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListPlaybackConfigurationsResponseTypeDef](./type_defs.md#listplaybackconfigurationsresponsetypedef).

<a id="list\_prefetch\_schedules"></a>

### list_prefetch_schedules

Creates a new prefetch schedule.

Type annotations for
`session.create_client("mediatailor").list_prefetch_schedules` method.

Boto3 documentation:
[MediaTailor.Client.list_prefetch_schedules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.list_prefetch_schedules)

Asynchronous method. Use `await list_prefetch_schedules(...)` for a synchronous
call.

Arguments mapping described in
[ListPrefetchSchedulesRequestRequestTypeDef](./type_defs.md#listprefetchschedulesrequestrequesttypedef).

Keyword-only arguments:

- `PlaybackConfigurationName`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`
- `StreamId`: `str`

Returns a `Coroutine` for
[ListPrefetchSchedulesResponseTypeDef](./type_defs.md#listprefetchschedulesresponsetypedef).

<a id="list\_source\_locations"></a>

### list_source_locations

Retrieves a list of source locations.

Type annotations for
`session.create_client("mediatailor").list_source_locations` method.

Boto3 documentation:
[MediaTailor.Client.list_source_locations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.list_source_locations)

Asynchronous method. Use `await list_source_locations(...)` for a synchronous
call.

Arguments mapping described in
[ListSourceLocationsRequestRequestTypeDef](./type_defs.md#listsourcelocationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListSourceLocationsResponseTypeDef](./type_defs.md#listsourcelocationsresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Returns a list of the tags assigned to the specified playback configuration
resource.

Type annotations for
`session.create_client("mediatailor").list_tags_for_resource` method.

Boto3 documentation:
[MediaTailor.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list\_vod\_sources"></a>

### list_vod_sources

Lists all the VOD sources in a source location.

Type annotations for `session.create_client("mediatailor").list_vod_sources`
method.

Boto3 documentation:
[MediaTailor.Client.list_vod_sources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.list_vod_sources)

Asynchronous method. Use `await list_vod_sources(...)` for a synchronous call.

Arguments mapping described in
[ListVodSourcesRequestRequestTypeDef](./type_defs.md#listvodsourcesrequestrequesttypedef).

Keyword-only arguments:

- `SourceLocationName`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListVodSourcesResponseTypeDef](./type_defs.md#listvodsourcesresponsetypedef).

<a id="put\_channel\_policy"></a>

### put_channel_policy

Creates an IAM policy for the channel.

Type annotations for `session.create_client("mediatailor").put_channel_policy`
method.

Boto3 documentation:
[MediaTailor.Client.put_channel_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.put_channel_policy)

Asynchronous method. Use `await put_channel_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutChannelPolicyRequestRequestTypeDef](./type_defs.md#putchannelpolicyrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*
- `Policy`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put\_playback\_configuration"></a>

### put_playback_configuration

Adds a new playback configuration to AWS Elemental MediaTailor.

Type annotations for
`session.create_client("mediatailor").put_playback_configuration` method.

Boto3 documentation:
[MediaTailor.Client.put_playback_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.put_playback_configuration)

Asynchronous method. Use `await put_playback_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutPlaybackConfigurationRequestRequestTypeDef](./type_defs.md#putplaybackconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `AdDecisionServerUrl`: `str`
- `AvailSuppression`:
  [AvailSuppressionTypeDef](./type_defs.md#availsuppressiontypedef)
- `Bumper`: [BumperTypeDef](./type_defs.md#bumpertypedef)
- `CdnConfiguration`:
  [CdnConfigurationTypeDef](./type_defs.md#cdnconfigurationtypedef)
- `ConfigurationAliases`: `Mapping`\[`str`, `Mapping`\[`str`, `str`\]\]
- `DashConfiguration`:
  [DashConfigurationForPutTypeDef](./type_defs.md#dashconfigurationforputtypedef)
- `LivePreRollConfiguration`:
  [LivePreRollConfigurationTypeDef](./type_defs.md#liveprerollconfigurationtypedef)
- `ManifestProcessingRules`:
  [ManifestProcessingRulesTypeDef](./type_defs.md#manifestprocessingrulestypedef)
- `Name`: `str`
- `PersonalizationThresholdSeconds`: `int`
- `SlateAdUrl`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `TranscodeProfileName`: `str`
- `VideoContentSourceUrl`: `str`

Returns a `Coroutine` for
[PutPlaybackConfigurationResponseTypeDef](./type_defs.md#putplaybackconfigurationresponsetypedef).

<a id="start\_channel"></a>

### start_channel

Starts a specific channel.

Type annotations for `session.create_client("mediatailor").start_channel`
method.

Boto3 documentation:
[MediaTailor.Client.start_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.start_channel)

Asynchronous method. Use `await start_channel(...)` for a synchronous call.

Arguments mapping described in
[StartChannelRequestRequestTypeDef](./type_defs.md#startchannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="stop\_channel"></a>

### stop_channel

Stops a specific channel.

Type annotations for `session.create_client("mediatailor").stop_channel`
method.

Boto3 documentation:
[MediaTailor.Client.stop_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.stop_channel)

Asynchronous method. Use `await stop_channel(...)` for a synchronous call.

Arguments mapping described in
[StopChannelRequestRequestTypeDef](./type_defs.md#stopchannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag\_resource"></a>

### tag_resource

Adds tags to the specified playback configuration resource.

Type annotations for `session.create_client("mediatailor").tag_resource`
method.

Boto3 documentation:
[MediaTailor.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="untag\_resource"></a>

### untag_resource

Removes tags from the specified playback configuration resource.

Type annotations for `session.create_client("mediatailor").untag_resource`
method.

Boto3 documentation:
[MediaTailor.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update\_channel"></a>

### update_channel

Updates an existing channel.

Type annotations for `session.create_client("mediatailor").update_channel`
method.

Boto3 documentation:
[MediaTailor.Client.update_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.update_channel)

Asynchronous method. Use `await update_channel(...)` for a synchronous call.

Arguments mapping described in
[UpdateChannelRequestRequestTypeDef](./type_defs.md#updatechannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelName`: `str` *(required)*
- `Outputs`:
  `Sequence`\[[RequestOutputItemTypeDef](./type_defs.md#requestoutputitemtypedef)\]
  *(required)*
- `FillerSlate`: [SlateSourceTypeDef](./type_defs.md#slatesourcetypedef)

Returns a `Coroutine` for
[UpdateChannelResponseTypeDef](./type_defs.md#updatechannelresponsetypedef).

<a id="update\_source\_location"></a>

### update_source_location

Updates a source location on a specific channel.

Type annotations for
`session.create_client("mediatailor").update_source_location` method.

Boto3 documentation:
[MediaTailor.Client.update_source_location](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.update_source_location)

Asynchronous method. Use `await update_source_location(...)` for a synchronous
call.

Arguments mapping described in
[UpdateSourceLocationRequestRequestTypeDef](./type_defs.md#updatesourcelocationrequestrequesttypedef).

Keyword-only arguments:

- `HttpConfiguration`:
  [HttpConfigurationTypeDef](./type_defs.md#httpconfigurationtypedef)
  *(required)*
- `SourceLocationName`: `str` *(required)*
- `AccessConfiguration`:
  [AccessConfigurationTypeDef](./type_defs.md#accessconfigurationtypedef)
- `DefaultSegmentDeliveryConfiguration`:
  [DefaultSegmentDeliveryConfigurationTypeDef](./type_defs.md#defaultsegmentdeliveryconfigurationtypedef)
- `SegmentDeliveryConfigurations`:
  `Sequence`\[[SegmentDeliveryConfigurationTypeDef](./type_defs.md#segmentdeliveryconfigurationtypedef)\]

Returns a `Coroutine` for
[UpdateSourceLocationResponseTypeDef](./type_defs.md#updatesourcelocationresponsetypedef).

<a id="update\_vod\_source"></a>

### update_vod_source

Updates a specific VOD source in a specific source location.

Type annotations for `session.create_client("mediatailor").update_vod_source`
method.

Boto3 documentation:
[MediaTailor.Client.update_vod_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.update_vod_source)

Asynchronous method. Use `await update_vod_source(...)` for a synchronous call.

Arguments mapping described in
[UpdateVodSourceRequestRequestTypeDef](./type_defs.md#updatevodsourcerequestrequesttypedef).

Keyword-only arguments:

- `HttpPackageConfigurations`:
  `Sequence`\[[HttpPackageConfigurationTypeDef](./type_defs.md#httppackageconfigurationtypedef)\]
  *(required)*
- `SourceLocationName`: `str` *(required)*
- `VodSourceName`: `str` *(required)*

Returns a `Coroutine` for
[UpdateVodSourceResponseTypeDef](./type_defs.md#updatevodsourceresponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("mediatailor").__aenter__` method.

Boto3 documentation:
[MediaTailor.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [MediaTailorClient](#mediatailorclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("mediatailor").__aexit__` method.

Boto3 documentation:
[MediaTailor.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("mediatailor").get_paginator`
method with overloads.

- `client.get_paginator("get_channel_schedule")` ->
  [GetChannelSchedulePaginator](./paginators.md#getchannelschedulepaginator)
- `client.get_paginator("list_alerts")` ->
  [ListAlertsPaginator](./paginators.md#listalertspaginator)
- `client.get_paginator("list_channels")` ->
  [ListChannelsPaginator](./paginators.md#listchannelspaginator)
- `client.get_paginator("list_playback_configurations")` ->
  [ListPlaybackConfigurationsPaginator](./paginators.md#listplaybackconfigurationspaginator)
- `client.get_paginator("list_prefetch_schedules")` ->
  [ListPrefetchSchedulesPaginator](./paginators.md#listprefetchschedulespaginator)
- `client.get_paginator("list_source_locations")` ->
  [ListSourceLocationsPaginator](./paginators.md#listsourcelocationspaginator)
- `client.get_paginator("list_vod_sources")` ->
  [ListVodSourcesPaginator](./paginators.md#listvodsourcespaginator)
