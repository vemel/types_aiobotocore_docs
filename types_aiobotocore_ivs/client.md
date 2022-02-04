<a id="ivsclient-for-aiobotocore-ivs-module"></a>

# IVSClient for aiobotocore IVS module

> [Index](..) > [IVS](.) > IVSClient

Auto-generated documentation for
[IVS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS)
type annotations stubs module
[types-aiobotocore-ivs](https://pypi.org/project/types-aiobotocore-ivs/).

- [IVSClient for aiobotocore IVS module](#ivsclient-for-aiobotocore-ivs-module)
  - [IVSClient](#ivsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [batch_get_channel](#batch_get_channel)
    - [batch_get_stream_key](#batch_get_stream_key)
    - [can_paginate](#can_paginate)
    - [create_channel](#create_channel)
    - [create_recording_configuration](#create_recording_configuration)
    - [create_stream_key](#create_stream_key)
    - [delete_channel](#delete_channel)
    - [delete_playback_key_pair](#delete_playback_key_pair)
    - [delete_recording_configuration](#delete_recording_configuration)
    - [delete_stream_key](#delete_stream_key)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_channel](#get_channel)
    - [get_playback_key_pair](#get_playback_key_pair)
    - [get_recording_configuration](#get_recording_configuration)
    - [get_stream](#get_stream)
    - [get_stream_key](#get_stream_key)
    - [get_stream_session](#get_stream_session)
    - [import_playback_key_pair](#import_playback_key_pair)
    - [list_channels](#list_channels)
    - [list_playback_key_pairs](#list_playback_key_pairs)
    - [list_recording_configurations](#list_recording_configurations)
    - [list_stream_keys](#list_stream_keys)
    - [list_stream_sessions](#list_stream_sessions)
    - [list_streams](#list_streams)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_metadata](#put_metadata)
    - [stop_stream](#stop_stream)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_channel](#update_channel)
    - [get_paginator](#get_paginator)

<a id="ivsclient"></a>

## IVSClient

Type annotations for `aiobotocore.create_client("ivs")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_ivs.client import IVSClient

def get_ivs_client() -> IVSClient:
    return Session().client("ivs")
```

Boto3 documentation:
[IVS.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ivs.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ChannelNotBroadcasting`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.PendingVerification`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.StreamUnavailable`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

IVSClient exceptions.

Type annotations for `aiobotocore.create_client("ivs").exceptions` method.

Boto3 documentation:
[IVS.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="batch_get_channel"></a>

### batch_get_channel

Performs GetChannel on multiple ARNs simultaneously.

Type annotations for `aiobotocore.create_client("ivs").batch_get_channel`
method.

Boto3 documentation:
[IVS.Client.batch_get_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.batch_get_channel)

Asynchronous method. Use `await batch_get_channel(...)` for a synchronous call.

Arguments mapping described in
[BatchGetChannelRequestRequestTypeDef](./type_defs.md#batchgetchannelrequestrequesttypedef).

Keyword-only arguments:

- `arns`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetChannelResponseTypeDef](./type_defs.md#batchgetchannelresponsetypedef).

<a id="batch_get_stream_key"></a>

### batch_get_stream_key

Performs GetStreamKey on multiple ARNs simultaneously.

Type annotations for `aiobotocore.create_client("ivs").batch_get_stream_key`
method.

Boto3 documentation:
[IVS.Client.batch_get_stream_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.batch_get_stream_key)

Asynchronous method. Use `await batch_get_stream_key(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetStreamKeyRequestRequestTypeDef](./type_defs.md#batchgetstreamkeyrequestrequesttypedef).

Keyword-only arguments:

- `arns`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetStreamKeyResponseTypeDef](./type_defs.md#batchgetstreamkeyresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("ivs").can_paginate` method.

Boto3 documentation:
[IVS.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_channel"></a>

### create_channel

Creates a new channel and an associated stream key to start streaming.

Type annotations for `aiobotocore.create_client("ivs").create_channel` method.

Boto3 documentation:
[IVS.Client.create_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_channel)

Asynchronous method. Use `await create_channel(...)` for a synchronous call.

Arguments mapping described in
[CreateChannelRequestRequestTypeDef](./type_defs.md#createchannelrequestrequesttypedef).

Keyword-only arguments:

- `authorized`: `bool`
- `latencyMode`: [ChannelLatencyModeType](./literals.md#channellatencymodetype)
- `name`: `str`
- `recordingConfigurationArn`: `str`
- `tags`: `Mapping`\[`str`, `str`\]
- `type`: [ChannelTypeType](./literals.md#channeltypetype)

Returns a `Coroutine` for
[CreateChannelResponseTypeDef](./type_defs.md#createchannelresponsetypedef).

<a id="create_recording_configuration"></a>

### create_recording_configuration

Creates a new recording configuration, used to enable recording to Amazon S3.

Type annotations for
`aiobotocore.create_client("ivs").create_recording_configuration` method.

Boto3 documentation:
[IVS.Client.create_recording_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_recording_configuration)

Asynchronous method. Use `await create_recording_configuration(...)` for a
synchronous call.

Arguments mapping described in
[CreateRecordingConfigurationRequestRequestTypeDef](./type_defs.md#createrecordingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `destinationConfiguration`:
  [DestinationConfigurationTypeDef](./type_defs.md#destinationconfigurationtypedef)
  *(required)*
- `name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateRecordingConfigurationResponseTypeDef](./type_defs.md#createrecordingconfigurationresponsetypedef).

<a id="create_stream_key"></a>

### create_stream_key

Creates a stream key, used to initiate a stream, for the specified channel ARN.

Type annotations for `aiobotocore.create_client("ivs").create_stream_key`
method.

Boto3 documentation:
[IVS.Client.create_stream_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_stream_key)

Asynchronous method. Use `await create_stream_key(...)` for a synchronous call.

Arguments mapping described in
[CreateStreamKeyRequestRequestTypeDef](./type_defs.md#createstreamkeyrequestrequesttypedef).

Keyword-only arguments:

- `channelArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateStreamKeyResponseTypeDef](./type_defs.md#createstreamkeyresponsetypedef).

<a id="delete_channel"></a>

### delete_channel

Deletes the specified channel and its associated stream keys.

Type annotations for `aiobotocore.create_client("ivs").delete_channel` method.

Boto3 documentation:
[IVS.Client.delete_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_channel)

Asynchronous method. Use `await delete_channel(...)` for a synchronous call.

Arguments mapping described in
[DeleteChannelRequestRequestTypeDef](./type_defs.md#deletechannelrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

<a id="delete_playback_key_pair"></a>

### delete_playback_key_pair

Deletes a specified authorization key pair.

Type annotations for
`aiobotocore.create_client("ivs").delete_playback_key_pair` method.

Boto3 documentation:
[IVS.Client.delete_playback_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_playback_key_pair)

Asynchronous method. Use `await delete_playback_key_pair(...)` for a
synchronous call.

Arguments mapping described in
[DeletePlaybackKeyPairRequestRequestTypeDef](./type_defs.md#deleteplaybackkeypairrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_recording_configuration"></a>

### delete_recording_configuration

Deletes the recording configuration for the specified ARN.

Type annotations for
`aiobotocore.create_client("ivs").delete_recording_configuration` method.

Boto3 documentation:
[IVS.Client.delete_recording_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_recording_configuration)

Asynchronous method. Use `await delete_recording_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteRecordingConfigurationRequestRequestTypeDef](./type_defs.md#deleterecordingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

<a id="delete_stream_key"></a>

### delete_stream_key

Deletes the stream key for the specified ARN, so it can no longer be used to
stream.

Type annotations for `aiobotocore.create_client("ivs").delete_stream_key`
method.

Boto3 documentation:
[IVS.Client.delete_stream_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_stream_key)

Asynchronous method. Use `await delete_stream_key(...)` for a synchronous call.

Arguments mapping described in
[DeleteStreamKeyRequestRequestTypeDef](./type_defs.md#deletestreamkeyrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("ivs").generate_presigned_url`
method.

Boto3 documentation:
[IVS.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_channel"></a>

### get_channel

Gets the channel configuration for the specified channel ARN.

Type annotations for `aiobotocore.create_client("ivs").get_channel` method.

Boto3 documentation:
[IVS.Client.get_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_channel)

Asynchronous method. Use `await get_channel(...)` for a synchronous call.

Arguments mapping described in
[GetChannelRequestRequestTypeDef](./type_defs.md#getchannelrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetChannelResponseTypeDef](./type_defs.md#getchannelresponsetypedef).

<a id="get_playback_key_pair"></a>

### get_playback_key_pair

Gets a specified playback authorization key pair and returns the `arn` and
`fingerprint`.

Type annotations for `aiobotocore.create_client("ivs").get_playback_key_pair`
method.

Boto3 documentation:
[IVS.Client.get_playback_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_playback_key_pair)

Asynchronous method. Use `await get_playback_key_pair(...)` for a synchronous
call.

Arguments mapping described in
[GetPlaybackKeyPairRequestRequestTypeDef](./type_defs.md#getplaybackkeypairrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetPlaybackKeyPairResponseTypeDef](./type_defs.md#getplaybackkeypairresponsetypedef).

<a id="get_recording_configuration"></a>

### get_recording_configuration

Gets the recording configuration for the specified ARN.

Type annotations for
`aiobotocore.create_client("ivs").get_recording_configuration` method.

Boto3 documentation:
[IVS.Client.get_recording_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_recording_configuration)

Asynchronous method. Use `await get_recording_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetRecordingConfigurationRequestRequestTypeDef](./type_defs.md#getrecordingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetRecordingConfigurationResponseTypeDef](./type_defs.md#getrecordingconfigurationresponsetypedef).

<a id="get_stream"></a>

### get_stream

Gets information about the active (live) stream on a specified channel.

Type annotations for `aiobotocore.create_client("ivs").get_stream` method.

Boto3 documentation:
[IVS.Client.get_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream)

Asynchronous method. Use `await get_stream(...)` for a synchronous call.

Arguments mapping described in
[GetStreamRequestRequestTypeDef](./type_defs.md#getstreamrequestrequesttypedef).

Keyword-only arguments:

- `channelArn`: `str` *(required)*

Returns a `Coroutine` for
[GetStreamResponseTypeDef](./type_defs.md#getstreamresponsetypedef).

<a id="get_stream_key"></a>

### get_stream_key

Gets stream-key information for a specified ARN.

Type annotations for `aiobotocore.create_client("ivs").get_stream_key` method.

Boto3 documentation:
[IVS.Client.get_stream_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream_key)

Asynchronous method. Use `await get_stream_key(...)` for a synchronous call.

Arguments mapping described in
[GetStreamKeyRequestRequestTypeDef](./type_defs.md#getstreamkeyrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetStreamKeyResponseTypeDef](./type_defs.md#getstreamkeyresponsetypedef).

<a id="get_stream_session"></a>

### get_stream_session

Gets metadata on a specified stream.

Type annotations for `aiobotocore.create_client("ivs").get_stream_session`
method.

Boto3 documentation:
[IVS.Client.get_stream_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream_session)

Asynchronous method. Use `await get_stream_session(...)` for a synchronous
call.

Arguments mapping described in
[GetStreamSessionRequestRequestTypeDef](./type_defs.md#getstreamsessionrequestrequesttypedef).

Keyword-only arguments:

- `channelArn`: `str` *(required)*
- `streamId`: `str`

Returns a `Coroutine` for
[GetStreamSessionResponseTypeDef](./type_defs.md#getstreamsessionresponsetypedef).

<a id="import_playback_key_pair"></a>

### import_playback_key_pair

Imports the public portion of a new key pair and returns its `arn` and
`fingerprint`.

Type annotations for
`aiobotocore.create_client("ivs").import_playback_key_pair` method.

Boto3 documentation:
[IVS.Client.import_playback_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.import_playback_key_pair)

Asynchronous method. Use `await import_playback_key_pair(...)` for a
synchronous call.

Arguments mapping described in
[ImportPlaybackKeyPairRequestRequestTypeDef](./type_defs.md#importplaybackkeypairrequestrequesttypedef).

Keyword-only arguments:

- `publicKeyMaterial`: `str` *(required)*
- `name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ImportPlaybackKeyPairResponseTypeDef](./type_defs.md#importplaybackkeypairresponsetypedef).

<a id="list_channels"></a>

### list_channels

Gets summary information about all channels in your account, in the Amazon Web
Services region where the API request is processed.

Type annotations for `aiobotocore.create_client("ivs").list_channels` method.

Boto3 documentation:
[IVS.Client.list_channels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_channels)

Asynchronous method. Use `await list_channels(...)` for a synchronous call.

Arguments mapping described in
[ListChannelsRequestRequestTypeDef](./type_defs.md#listchannelsrequestrequesttypedef).

Keyword-only arguments:

- `filterByName`: `str`
- `filterByRecordingConfigurationArn`: `str`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListChannelsResponseTypeDef](./type_defs.md#listchannelsresponsetypedef).

<a id="list_playback_key_pairs"></a>

### list_playback_key_pairs

Gets summary information about playback key pairs.

Type annotations for `aiobotocore.create_client("ivs").list_playback_key_pairs`
method.

Boto3 documentation:
[IVS.Client.list_playback_key_pairs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_playback_key_pairs)

Asynchronous method. Use `await list_playback_key_pairs(...)` for a synchronous
call.

Arguments mapping described in
[ListPlaybackKeyPairsRequestRequestTypeDef](./type_defs.md#listplaybackkeypairsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListPlaybackKeyPairsResponseTypeDef](./type_defs.md#listplaybackkeypairsresponsetypedef).

<a id="list_recording_configurations"></a>

### list_recording_configurations

Gets summary information about all recording configurations in your account, in
the Amazon Web Services region where the API request is processed.

Type annotations for
`aiobotocore.create_client("ivs").list_recording_configurations` method.

Boto3 documentation:
[IVS.Client.list_recording_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_recording_configurations)

Asynchronous method. Use `await list_recording_configurations(...)` for a
synchronous call.

Arguments mapping described in
[ListRecordingConfigurationsRequestRequestTypeDef](./type_defs.md#listrecordingconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListRecordingConfigurationsResponseTypeDef](./type_defs.md#listrecordingconfigurationsresponsetypedef).

<a id="list_stream_keys"></a>

### list_stream_keys

Gets summary information about stream keys for the specified channel.

Type annotations for `aiobotocore.create_client("ivs").list_stream_keys`
method.

Boto3 documentation:
[IVS.Client.list_stream_keys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_stream_keys)

Asynchronous method. Use `await list_stream_keys(...)` for a synchronous call.

Arguments mapping described in
[ListStreamKeysRequestRequestTypeDef](./type_defs.md#liststreamkeysrequestrequesttypedef).

Keyword-only arguments:

- `channelArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListStreamKeysResponseTypeDef](./type_defs.md#liststreamkeysresponsetypedef).

<a id="list_stream_sessions"></a>

### list_stream_sessions

Gets a summary of current and previous streams for a specified channel in your
account, in the AWS region where the API request is processed.

Type annotations for `aiobotocore.create_client("ivs").list_stream_sessions`
method.

Boto3 documentation:
[IVS.Client.list_stream_sessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_stream_sessions)

Asynchronous method. Use `await list_stream_sessions(...)` for a synchronous
call.

Arguments mapping described in
[ListStreamSessionsRequestRequestTypeDef](./type_defs.md#liststreamsessionsrequestrequesttypedef).

Keyword-only arguments:

- `channelArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListStreamSessionsResponseTypeDef](./type_defs.md#liststreamsessionsresponsetypedef).

<a id="list_streams"></a>

### list_streams

Gets summary information about live streams in your account, in the Amazon Web
Services region where the API request is processed.

Type annotations for `aiobotocore.create_client("ivs").list_streams` method.

Boto3 documentation:
[IVS.Client.list_streams](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_streams)

Asynchronous method. Use `await list_streams(...)` for a synchronous call.

Arguments mapping described in
[ListStreamsRequestRequestTypeDef](./type_defs.md#liststreamsrequestrequesttypedef).

Keyword-only arguments:

- `filterBy`: [StreamFiltersTypeDef](./type_defs.md#streamfilterstypedef)
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListStreamsResponseTypeDef](./type_defs.md#liststreamsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Gets information about Amazon Web Services tags for the specified ARN.

Type annotations for `aiobotocore.create_client("ivs").list_tags_for_resource`
method.

Boto3 documentation:
[IVS.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_metadata"></a>

### put_metadata

Inserts metadata into the active stream of the specified channel.

Type annotations for `aiobotocore.create_client("ivs").put_metadata` method.

Boto3 documentation:
[IVS.Client.put_metadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.put_metadata)

Asynchronous method. Use `await put_metadata(...)` for a synchronous call.

Arguments mapping described in
[PutMetadataRequestRequestTypeDef](./type_defs.md#putmetadatarequestrequesttypedef).

Keyword-only arguments:

- `channelArn`: `str` *(required)*
- `metadata`: `str` *(required)*

<a id="stop_stream"></a>

### stop_stream

Disconnects the incoming RTMPS stream for the specified channel.

Type annotations for `aiobotocore.create_client("ivs").stop_stream` method.

Boto3 documentation:
[IVS.Client.stop_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.stop_stream)

Asynchronous method. Use `await stop_stream(...)` for a synchronous call.

Arguments mapping described in
[StopStreamRequestRequestTypeDef](./type_defs.md#stopstreamrequestrequesttypedef).

Keyword-only arguments:

- `channelArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Adds or updates tags for the Amazon Web Services resource with the specified
ARN.

Type annotations for `aiobotocore.create_client("ivs").tag_resource` method.

Boto3 documentation:
[IVS.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from the resource with the specified ARN.

Type annotations for `aiobotocore.create_client("ivs").untag_resource` method.

Boto3 documentation:
[IVS.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_channel"></a>

### update_channel

Updates a channel's configuration.

Type annotations for `aiobotocore.create_client("ivs").update_channel` method.

Boto3 documentation:
[IVS.Client.update_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.update_channel)

Asynchronous method. Use `await update_channel(...)` for a synchronous call.

Arguments mapping described in
[UpdateChannelRequestRequestTypeDef](./type_defs.md#updatechannelrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*
- `authorized`: `bool`
- `latencyMode`: [ChannelLatencyModeType](./literals.md#channellatencymodetype)
- `name`: `str`
- `recordingConfigurationArn`: `str`
- `type`: [ChannelTypeType](./literals.md#channeltypetype)

Returns a `Coroutine` for
[UpdateChannelResponseTypeDef](./type_defs.md#updatechannelresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("ivs").get_paginator` method
with overloads.

- `client.get_paginator("list_channels")` ->
  [ListChannelsPaginator](./paginators.md#listchannelspaginator)
- `client.get_paginator("list_playback_key_pairs")` ->
  [ListPlaybackKeyPairsPaginator](./paginators.md#listplaybackkeypairspaginator)
- `client.get_paginator("list_recording_configurations")` ->
  [ListRecordingConfigurationsPaginator](./paginators.md#listrecordingconfigurationspaginator)
- `client.get_paginator("list_stream_keys")` ->
  [ListStreamKeysPaginator](./paginators.md#liststreamkeyspaginator)
- `client.get_paginator("list_streams")` ->
  [ListStreamsPaginator](./paginators.md#liststreamspaginator)
