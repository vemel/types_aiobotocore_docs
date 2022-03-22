<a id="type-annotations-for-aiobotocore-mediatailor-module"></a>

# Type annotations for aiobotocore MediaTailor module

> [Index](../README.md) > MediaTailor

Auto-generated documentation for
[MediaTailor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
type annotations stubs module
[types-aiobotocore-mediatailor](https://pypi.org/project/types-aiobotocore-mediatailor/).

- [Type annotations for aiobotocore MediaTailor module](#type-annotations-for-aiobotocore-mediatailor-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [MediaTailorClient](#mediatailorclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `MediaTailor`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `MediaTailor` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[mediatailor]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[mediatailor]'


# standalone installation
python -m pip install types-aiobotocore-mediatailor
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-mediatailor
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="mediatailorclient"></a>

## MediaTailorClient

Type annotations for `session.create_client("mediatailor")` as
[MediaTailorClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_mediatailor.client import MediaTailorClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [configure_logs_for_playback_configuration](./client.md#configure_logs_for_playback_configuration)
- [create_channel](./client.md#create_channel)
- [create_prefetch_schedule](./client.md#create_prefetch_schedule)
- [create_program](./client.md#create_program)
- [create_source_location](./client.md#create_source_location)
- [create_vod_source](./client.md#create_vod_source)
- [delete_channel](./client.md#delete_channel)
- [delete_channel_policy](./client.md#delete_channel_policy)
- [delete_playback_configuration](./client.md#delete_playback_configuration)
- [delete_prefetch_schedule](./client.md#delete_prefetch_schedule)
- [delete_program](./client.md#delete_program)
- [delete_source_location](./client.md#delete_source_location)
- [delete_vod_source](./client.md#delete_vod_source)
- [describe_channel](./client.md#describe_channel)
- [describe_program](./client.md#describe_program)
- [describe_source_location](./client.md#describe_source_location)
- [describe_vod_source](./client.md#describe_vod_source)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_channel_policy](./client.md#get_channel_policy)
- [get_channel_schedule](./client.md#get_channel_schedule)
- [get_paginator](./client.md#get_paginator)
- [get_playback_configuration](./client.md#get_playback_configuration)
- [get_prefetch_schedule](./client.md#get_prefetch_schedule)
- [list_alerts](./client.md#list_alerts)
- [list_channels](./client.md#list_channels)
- [list_playback_configurations](./client.md#list_playback_configurations)
- [list_prefetch_schedules](./client.md#list_prefetch_schedules)
- [list_source_locations](./client.md#list_source_locations)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [list_vod_sources](./client.md#list_vod_sources)
- [put_channel_policy](./client.md#put_channel_policy)
- [put_playback_configuration](./client.md#put_playback_configuration)
- [start_channel](./client.md#start_channel)
- [stop_channel](./client.md#stop_channel)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_channel](./client.md#update_channel)
- [update_source_location](./client.md#update_source_location)
- [update_vod_source](./client.md#update_vod_source)

<a id="exceptions"></a>

### Exceptions

MediaTailorClient [exceptions](./client.md#exceptions)

- BadRequestException
- ClientError

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("mediatailor").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_mediatailor.paginator import GetChannelSchedulePaginator, ...
```

- [GetChannelSchedulePaginator](./paginators.md#getchannelschedulepaginator)
- [ListAlertsPaginator](./paginators.md#listalertspaginator)
- [ListChannelsPaginator](./paginators.md#listchannelspaginator)
- [ListPlaybackConfigurationsPaginator](./paginators.md#listplaybackconfigurationspaginator)
- [ListPrefetchSchedulesPaginator](./paginators.md#listprefetchschedulespaginator)
- [ListSourceLocationsPaginator](./paginators.md#listsourcelocationspaginator)
- [ListVodSourcesPaginator](./paginators.md#listvodsourcespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_mediatailor.literals import AccessTypeType, ...
```

- [AccessTypeType](./literals.md#accesstypetype)
- [ChannelStateType](./literals.md#channelstatetype)
- [GetChannelSchedulePaginatorName](./literals.md#getchannelschedulepaginatorname)
- [ListAlertsPaginatorName](./literals.md#listalertspaginatorname)
- [ListChannelsPaginatorName](./literals.md#listchannelspaginatorname)
- [ListPlaybackConfigurationsPaginatorName](./literals.md#listplaybackconfigurationspaginatorname)
- [ListPrefetchSchedulesPaginatorName](./literals.md#listprefetchschedulespaginatorname)
- [ListSourceLocationsPaginatorName](./literals.md#listsourcelocationspaginatorname)
- [ListVodSourcesPaginatorName](./literals.md#listvodsourcespaginatorname)
- [MessageTypeType](./literals.md#messagetypetype)
- [ModeType](./literals.md#modetype)
- [OperatorType](./literals.md#operatortype)
- [OriginManifestTypeType](./literals.md#originmanifesttypetype)
- [PlaybackModeType](./literals.md#playbackmodetype)
- [RelativePositionType](./literals.md#relativepositiontype)
- [ScheduleEntryTypeType](./literals.md#scheduleentrytypetype)
- [TypeType](./literals.md#typetype)
- [MediaTailorServiceName](./literals.md#mediatailorservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_mediatailor.type_defs import AccessConfigurationTypeDef, ...
```

- [AccessConfigurationTypeDef](./type_defs.md#accessconfigurationtypedef)
- [AdBreakTypeDef](./type_defs.md#adbreaktypedef)
- [AdMarkerPassthroughTypeDef](./type_defs.md#admarkerpassthroughtypedef)
- [AlertTypeDef](./type_defs.md#alerttypedef)
- [AvailMatchingCriteriaTypeDef](./type_defs.md#availmatchingcriteriatypedef)
- [AvailSuppressionTypeDef](./type_defs.md#availsuppressiontypedef)
- [BumperTypeDef](./type_defs.md#bumpertypedef)
- [CdnConfigurationTypeDef](./type_defs.md#cdnconfigurationtypedef)
- [ChannelTypeDef](./type_defs.md#channeltypedef)
- [ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef](./type_defs.md#configurelogsforplaybackconfigurationrequestrequesttypedef)
- [ConfigureLogsForPlaybackConfigurationResponseTypeDef](./type_defs.md#configurelogsforplaybackconfigurationresponsetypedef)
- [CreateChannelRequestRequestTypeDef](./type_defs.md#createchannelrequestrequesttypedef)
- [CreateChannelResponseTypeDef](./type_defs.md#createchannelresponsetypedef)
- [CreatePrefetchScheduleRequestRequestTypeDef](./type_defs.md#createprefetchschedulerequestrequesttypedef)
- [CreatePrefetchScheduleResponseTypeDef](./type_defs.md#createprefetchscheduleresponsetypedef)
- [CreateProgramRequestRequestTypeDef](./type_defs.md#createprogramrequestrequesttypedef)
- [CreateProgramResponseTypeDef](./type_defs.md#createprogramresponsetypedef)
- [CreateSourceLocationRequestRequestTypeDef](./type_defs.md#createsourcelocationrequestrequesttypedef)
- [CreateSourceLocationResponseTypeDef](./type_defs.md#createsourcelocationresponsetypedef)
- [CreateVodSourceRequestRequestTypeDef](./type_defs.md#createvodsourcerequestrequesttypedef)
- [CreateVodSourceResponseTypeDef](./type_defs.md#createvodsourceresponsetypedef)
- [DashConfigurationForPutTypeDef](./type_defs.md#dashconfigurationforputtypedef)
- [DashConfigurationTypeDef](./type_defs.md#dashconfigurationtypedef)
- [DashPlaylistSettingsTypeDef](./type_defs.md#dashplaylistsettingstypedef)
- [DefaultSegmentDeliveryConfigurationTypeDef](./type_defs.md#defaultsegmentdeliveryconfigurationtypedef)
- [DeleteChannelPolicyRequestRequestTypeDef](./type_defs.md#deletechannelpolicyrequestrequesttypedef)
- [DeleteChannelRequestRequestTypeDef](./type_defs.md#deletechannelrequestrequesttypedef)
- [DeletePlaybackConfigurationRequestRequestTypeDef](./type_defs.md#deleteplaybackconfigurationrequestrequesttypedef)
- [DeletePrefetchScheduleRequestRequestTypeDef](./type_defs.md#deleteprefetchschedulerequestrequesttypedef)
- [DeleteProgramRequestRequestTypeDef](./type_defs.md#deleteprogramrequestrequesttypedef)
- [DeleteSourceLocationRequestRequestTypeDef](./type_defs.md#deletesourcelocationrequestrequesttypedef)
- [DeleteVodSourceRequestRequestTypeDef](./type_defs.md#deletevodsourcerequestrequesttypedef)
- [DescribeChannelRequestRequestTypeDef](./type_defs.md#describechannelrequestrequesttypedef)
- [DescribeChannelResponseTypeDef](./type_defs.md#describechannelresponsetypedef)
- [DescribeProgramRequestRequestTypeDef](./type_defs.md#describeprogramrequestrequesttypedef)
- [DescribeProgramResponseTypeDef](./type_defs.md#describeprogramresponsetypedef)
- [DescribeSourceLocationRequestRequestTypeDef](./type_defs.md#describesourcelocationrequestrequesttypedef)
- [DescribeSourceLocationResponseTypeDef](./type_defs.md#describesourcelocationresponsetypedef)
- [DescribeVodSourceRequestRequestTypeDef](./type_defs.md#describevodsourcerequestrequesttypedef)
- [DescribeVodSourceResponseTypeDef](./type_defs.md#describevodsourceresponsetypedef)
- [GetChannelPolicyRequestRequestTypeDef](./type_defs.md#getchannelpolicyrequestrequesttypedef)
- [GetChannelPolicyResponseTypeDef](./type_defs.md#getchannelpolicyresponsetypedef)
- [GetChannelScheduleRequestRequestTypeDef](./type_defs.md#getchannelschedulerequestrequesttypedef)
- [GetChannelScheduleResponseTypeDef](./type_defs.md#getchannelscheduleresponsetypedef)
- [GetPlaybackConfigurationRequestRequestTypeDef](./type_defs.md#getplaybackconfigurationrequestrequesttypedef)
- [GetPlaybackConfigurationResponseTypeDef](./type_defs.md#getplaybackconfigurationresponsetypedef)
- [GetPrefetchScheduleRequestRequestTypeDef](./type_defs.md#getprefetchschedulerequestrequesttypedef)
- [GetPrefetchScheduleResponseTypeDef](./type_defs.md#getprefetchscheduleresponsetypedef)
- [HlsConfigurationTypeDef](./type_defs.md#hlsconfigurationtypedef)
- [HlsPlaylistSettingsTypeDef](./type_defs.md#hlsplaylistsettingstypedef)
- [HttpConfigurationTypeDef](./type_defs.md#httpconfigurationtypedef)
- [HttpPackageConfigurationTypeDef](./type_defs.md#httppackageconfigurationtypedef)
- [ListAlertsRequestRequestTypeDef](./type_defs.md#listalertsrequestrequesttypedef)
- [ListAlertsResponseTypeDef](./type_defs.md#listalertsresponsetypedef)
- [ListChannelsRequestRequestTypeDef](./type_defs.md#listchannelsrequestrequesttypedef)
- [ListChannelsResponseTypeDef](./type_defs.md#listchannelsresponsetypedef)
- [ListPlaybackConfigurationsRequestRequestTypeDef](./type_defs.md#listplaybackconfigurationsrequestrequesttypedef)
- [ListPlaybackConfigurationsResponseTypeDef](./type_defs.md#listplaybackconfigurationsresponsetypedef)
- [ListPrefetchSchedulesRequestRequestTypeDef](./type_defs.md#listprefetchschedulesrequestrequesttypedef)
- [ListPrefetchSchedulesResponseTypeDef](./type_defs.md#listprefetchschedulesresponsetypedef)
- [ListSourceLocationsRequestRequestTypeDef](./type_defs.md#listsourcelocationsrequestrequesttypedef)
- [ListSourceLocationsResponseTypeDef](./type_defs.md#listsourcelocationsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListVodSourcesRequestRequestTypeDef](./type_defs.md#listvodsourcesrequestrequesttypedef)
- [ListVodSourcesResponseTypeDef](./type_defs.md#listvodsourcesresponsetypedef)
- [LivePreRollConfigurationTypeDef](./type_defs.md#liveprerollconfigurationtypedef)
- [LogConfigurationTypeDef](./type_defs.md#logconfigurationtypedef)
- [ManifestProcessingRulesTypeDef](./type_defs.md#manifestprocessingrulestypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PlaybackConfigurationTypeDef](./type_defs.md#playbackconfigurationtypedef)
- [PrefetchConsumptionTypeDef](./type_defs.md#prefetchconsumptiontypedef)
- [PrefetchRetrievalTypeDef](./type_defs.md#prefetchretrievaltypedef)
- [PrefetchScheduleTypeDef](./type_defs.md#prefetchscheduletypedef)
- [PutChannelPolicyRequestRequestTypeDef](./type_defs.md#putchannelpolicyrequestrequesttypedef)
- [PutPlaybackConfigurationRequestRequestTypeDef](./type_defs.md#putplaybackconfigurationrequestrequesttypedef)
- [PutPlaybackConfigurationResponseTypeDef](./type_defs.md#putplaybackconfigurationresponsetypedef)
- [RequestOutputItemTypeDef](./type_defs.md#requestoutputitemtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ResponseOutputItemTypeDef](./type_defs.md#responseoutputitemtypedef)
- [ScheduleAdBreakTypeDef](./type_defs.md#scheduleadbreaktypedef)
- [ScheduleConfigurationTypeDef](./type_defs.md#scheduleconfigurationtypedef)
- [ScheduleEntryTypeDef](./type_defs.md#scheduleentrytypedef)
- [SecretsManagerAccessTokenConfigurationTypeDef](./type_defs.md#secretsmanageraccesstokenconfigurationtypedef)
- [SegmentDeliveryConfigurationTypeDef](./type_defs.md#segmentdeliveryconfigurationtypedef)
- [SlateSourceTypeDef](./type_defs.md#slatesourcetypedef)
- [SourceLocationTypeDef](./type_defs.md#sourcelocationtypedef)
- [SpliceInsertMessageTypeDef](./type_defs.md#spliceinsertmessagetypedef)
- [StartChannelRequestRequestTypeDef](./type_defs.md#startchannelrequestrequesttypedef)
- [StopChannelRequestRequestTypeDef](./type_defs.md#stopchannelrequestrequesttypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TransitionTypeDef](./type_defs.md#transitiontypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateChannelRequestRequestTypeDef](./type_defs.md#updatechannelrequestrequesttypedef)
- [UpdateChannelResponseTypeDef](./type_defs.md#updatechannelresponsetypedef)
- [UpdateSourceLocationRequestRequestTypeDef](./type_defs.md#updatesourcelocationrequestrequesttypedef)
- [UpdateSourceLocationResponseTypeDef](./type_defs.md#updatesourcelocationresponsetypedef)
- [UpdateVodSourceRequestRequestTypeDef](./type_defs.md#updatevodsourcerequestrequesttypedef)
- [UpdateVodSourceResponseTypeDef](./type_defs.md#updatevodsourceresponsetypedef)
- [VodSourceTypeDef](./type_defs.md#vodsourcetypedef)
