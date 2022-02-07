<a id="chimesdkmessagingclient-for-aiobotocore-chimesdkmessaging-module"></a>

# ChimeSDKMessagingClient for aiobotocore ChimeSDKMessaging module

> [Index](..) > [ChimeSDKMessaging](.) > ChimeSDKMessagingClient

Auto-generated documentation for
[ChimeSDKMessaging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging)
type annotations stubs module
[types-aiobotocore-chime-sdk-messaging](https://pypi.org/project/types-aiobotocore-chime-sdk-messaging/).

- [ChimeSDKMessagingClient for aiobotocore ChimeSDKMessaging module](#chimesdkmessagingclient-for-aiobotocore-chimesdkmessaging-module)
  - [ChimeSDKMessagingClient](#chimesdkmessagingclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_channel_flow](#associate_channel_flow)
    - [batch_create_channel_membership](#batch_create_channel_membership)
    - [can_paginate](#can_paginate)
    - [channel_flow_callback](#channel_flow_callback)
    - [create_channel](#create_channel)
    - [create_channel_ban](#create_channel_ban)
    - [create_channel_flow](#create_channel_flow)
    - [create_channel_membership](#create_channel_membership)
    - [create_channel_moderator](#create_channel_moderator)
    - [delete_channel](#delete_channel)
    - [delete_channel_ban](#delete_channel_ban)
    - [delete_channel_flow](#delete_channel_flow)
    - [delete_channel_membership](#delete_channel_membership)
    - [delete_channel_message](#delete_channel_message)
    - [delete_channel_moderator](#delete_channel_moderator)
    - [describe_channel](#describe_channel)
    - [describe_channel_ban](#describe_channel_ban)
    - [describe_channel_flow](#describe_channel_flow)
    - [describe_channel_membership](#describe_channel_membership)
    - [describe_channel_membership_for_app_instance_user](#describe_channel_membership_for_app_instance_user)
    - [describe_channel_moderated_by_app_instance_user](#describe_channel_moderated_by_app_instance_user)
    - [describe_channel_moderator](#describe_channel_moderator)
    - [disassociate_channel_flow](#disassociate_channel_flow)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_channel_membership_preferences](#get_channel_membership_preferences)
    - [get_channel_message](#get_channel_message)
    - [get_channel_message_status](#get_channel_message_status)
    - [get_messaging_session_endpoint](#get_messaging_session_endpoint)
    - [list_channel_bans](#list_channel_bans)
    - [list_channel_flows](#list_channel_flows)
    - [list_channel_memberships](#list_channel_memberships)
    - [list_channel_memberships_for_app_instance_user](#list_channel_memberships_for_app_instance_user)
    - [list_channel_messages](#list_channel_messages)
    - [list_channel_moderators](#list_channel_moderators)
    - [list_channels](#list_channels)
    - [list_channels_associated_with_channel_flow](#list_channels_associated_with_channel_flow)
    - [list_channels_moderated_by_app_instance_user](#list_channels_moderated_by_app_instance_user)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_channel_membership_preferences](#put_channel_membership_preferences)
    - [redact_channel_message](#redact_channel_message)
    - [send_channel_message](#send_channel_message)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_channel](#update_channel)
    - [update_channel_flow](#update_channel_flow)
    - [update_channel_message](#update_channel_message)
    - [update_channel_read_marker](#update_channel_read_marker)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)

<a id="chimesdkmessagingclient"></a>

## ChimeSDKMessagingClient

Type annotations for `session.create_client("chime-sdk-messaging")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_chime_sdk_messaging.client import ChimeSDKMessagingClient

session = get_session()
async with session.create_client("chime-sdk-messaging") as client:
    client: ChimeSDKMessagingClient
```

Boto3 documentation:
[ChimeSDKMessaging.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_chime_sdk_messaging.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.ForbiddenException`
- `Exceptions.NotFoundException`
- `Exceptions.ResourceLimitExceededException`
- `Exceptions.ServiceFailureException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.ThrottledClientException`
- `Exceptions.UnauthorizedClientException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ChimeSDKMessagingClient exceptions.

Type annotations for `session.create_client("chime-sdk-messaging").exceptions`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate_channel_flow"></a>

### associate_channel_flow

Associates a channel flow with a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").associate_channel_flow` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.associate_channel_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.associate_channel_flow)

Asynchronous method. Use `await associate_channel_flow(...)` for a synchronous
call.

Arguments mapping described in
[AssociateChannelFlowRequestRequestTypeDef](./type_defs.md#associatechannelflowrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChannelFlowArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

<a id="batch_create_channel_membership"></a>

### batch_create_channel_membership

Adds a specified number of users to a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").batch_create_channel_membership`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.batch_create_channel_membership](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.batch_create_channel_membership)

Asynchronous method. Use `await batch_create_channel_membership(...)` for a
synchronous call.

Arguments mapping described in
[BatchCreateChannelMembershipRequestRequestTypeDef](./type_defs.md#batchcreatechannelmembershiprequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArns`: `Sequence`\[`str`\] *(required)*
- `ChimeBearer`: `str` *(required)*
- `Type`: [ChannelMembershipTypeType](./literals.md#channelmembershiptypetype)

Returns a `Coroutine` for
[BatchCreateChannelMembershipResponseTypeDef](./type_defs.md#batchcreatechannelmembershipresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`session.create_client("chime-sdk-messaging").can_paginate` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="channel_flow_callback"></a>

### channel_flow_callback

Calls back Chime SDK Messaging with a processing response message.

Type annotations for
`session.create_client("chime-sdk-messaging").channel_flow_callback` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.channel_flow_callback](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.channel_flow_callback)

Asynchronous method. Use `await channel_flow_callback(...)` for a synchronous
call.

Arguments mapping described in
[ChannelFlowCallbackRequestRequestTypeDef](./type_defs.md#channelflowcallbackrequestrequesttypedef).

Keyword-only arguments:

- `CallbackId`: `str` *(required)*
- `ChannelArn`: `str` *(required)*
- `ChannelMessage`:
  [ChannelMessageCallbackTypeDef](./type_defs.md#channelmessagecallbacktypedef)
  *(required)*
- `DeleteResource`: `bool`

Returns a `Coroutine` for
[ChannelFlowCallbackResponseTypeDef](./type_defs.md#channelflowcallbackresponsetypedef).

<a id="create_channel"></a>

### create_channel

Creates a channel to which you can add users and send messages.

Type annotations for
`session.create_client("chime-sdk-messaging").create_channel` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.create_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel)

Asynchronous method. Use `await create_channel(...)` for a synchronous call.

Arguments mapping described in
[CreateChannelRequestRequestTypeDef](./type_defs.md#createchannelrequestrequesttypedef).

Keyword-only arguments:

- `AppInstanceArn`: `str` *(required)*
- `Name`: `str` *(required)*
- `ClientRequestToken`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `Mode`: [ChannelModeType](./literals.md#channelmodetype)
- `Privacy`: [ChannelPrivacyType](./literals.md#channelprivacytype)
- `Metadata`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateChannelResponseTypeDef](./type_defs.md#createchannelresponsetypedef).

<a id="create_channel_ban"></a>

### create_channel_ban

Permanently bans a member from a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").create_channel_ban` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.create_channel_ban](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_ban)

Asynchronous method. Use `await create_channel_ban(...)` for a synchronous
call.

Arguments mapping described in
[CreateChannelBanRequestRequestTypeDef](./type_defs.md#createchannelbanrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[CreateChannelBanResponseTypeDef](./type_defs.md#createchannelbanresponsetypedef).

<a id="create_channel_flow"></a>

### create_channel_flow

Creates a channel flow, a container for processors.

Type annotations for
`session.create_client("chime-sdk-messaging").create_channel_flow` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.create_channel_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_flow)

Asynchronous method. Use `await create_channel_flow(...)` for a synchronous
call.

Arguments mapping described in
[CreateChannelFlowRequestRequestTypeDef](./type_defs.md#createchannelflowrequestrequesttypedef).

Keyword-only arguments:

- `AppInstanceArn`: `str` *(required)*
- `Processors`:
  `Sequence`\[[ProcessorTypeDef](./type_defs.md#processortypedef)\]
  *(required)*
- `Name`: `str` *(required)*
- `ClientRequestToken`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateChannelFlowResponseTypeDef](./type_defs.md#createchannelflowresponsetypedef).

<a id="create_channel_membership"></a>

### create_channel_membership

Adds a user to a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").create_channel_membership`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.create_channel_membership](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_membership)

Asynchronous method. Use `await create_channel_membership(...)` for a
synchronous call.

Arguments mapping described in
[CreateChannelMembershipRequestRequestTypeDef](./type_defs.md#createchannelmembershiprequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `Type`: [ChannelMembershipTypeType](./literals.md#channelmembershiptypetype)
  *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[CreateChannelMembershipResponseTypeDef](./type_defs.md#createchannelmembershipresponsetypedef).

<a id="create_channel_moderator"></a>

### create_channel_moderator

Creates a new `ChannelModerator`.

Type annotations for
`session.create_client("chime-sdk-messaging").create_channel_moderator` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.create_channel_moderator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_moderator)

Asynchronous method. Use `await create_channel_moderator(...)` for a
synchronous call.

Arguments mapping described in
[CreateChannelModeratorRequestRequestTypeDef](./type_defs.md#createchannelmoderatorrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChannelModeratorArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[CreateChannelModeratorResponseTypeDef](./type_defs.md#createchannelmoderatorresponsetypedef).

<a id="delete_channel"></a>

### delete_channel

Immediately makes a channel and its memberships inaccessible and marks them for
deletion.

Type annotations for
`session.create_client("chime-sdk-messaging").delete_channel` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.delete_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel)

Asynchronous method. Use `await delete_channel(...)` for a synchronous call.

Arguments mapping described in
[DeleteChannelRequestRequestTypeDef](./type_defs.md#deletechannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

<a id="delete_channel_ban"></a>

### delete_channel_ban

Removes a user from a channel's ban list.

Type annotations for
`session.create_client("chime-sdk-messaging").delete_channel_ban` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.delete_channel_ban](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_ban)

Asynchronous method. Use `await delete_channel_ban(...)` for a synchronous
call.

Arguments mapping described in
[DeleteChannelBanRequestRequestTypeDef](./type_defs.md#deletechannelbanrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

<a id="delete_channel_flow"></a>

### delete_channel_flow

Deletes a channel flow, an irreversible process.

Type annotations for
`session.create_client("chime-sdk-messaging").delete_channel_flow` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.delete_channel_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_flow)

Asynchronous method. Use `await delete_channel_flow(...)` for a synchronous
call.

Arguments mapping described in
[DeleteChannelFlowRequestRequestTypeDef](./type_defs.md#deletechannelflowrequestrequesttypedef).

Keyword-only arguments:

- `ChannelFlowArn`: `str` *(required)*

<a id="delete_channel_membership"></a>

### delete_channel_membership

Removes a member from a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").delete_channel_membership`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.delete_channel_membership](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_membership)

Asynchronous method. Use `await delete_channel_membership(...)` for a
synchronous call.

Arguments mapping described in
[DeleteChannelMembershipRequestRequestTypeDef](./type_defs.md#deletechannelmembershiprequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

<a id="delete_channel_message"></a>

### delete_channel_message

Deletes a channel message.

Type annotations for
`session.create_client("chime-sdk-messaging").delete_channel_message` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.delete_channel_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_message)

Asynchronous method. Use `await delete_channel_message(...)` for a synchronous
call.

Arguments mapping described in
[DeleteChannelMessageRequestRequestTypeDef](./type_defs.md#deletechannelmessagerequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MessageId`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

<a id="delete_channel_moderator"></a>

### delete_channel_moderator

Deletes a channel moderator.

Type annotations for
`session.create_client("chime-sdk-messaging").delete_channel_moderator` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.delete_channel_moderator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_moderator)

Asynchronous method. Use `await delete_channel_moderator(...)` for a
synchronous call.

Arguments mapping described in
[DeleteChannelModeratorRequestRequestTypeDef](./type_defs.md#deletechannelmoderatorrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChannelModeratorArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

<a id="describe_channel"></a>

### describe_channel

Returns the full details of a channel in an Amazon Chime `AppInstance` .

Type annotations for
`session.create_client("chime-sdk-messaging").describe_channel` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.describe_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel)

Asynchronous method. Use `await describe_channel(...)` for a synchronous call.

Arguments mapping described in
[DescribeChannelRequestRequestTypeDef](./type_defs.md#describechannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelResponseTypeDef](./type_defs.md#describechannelresponsetypedef).

<a id="describe_channel_ban"></a>

### describe_channel_ban

Returns the full details of a channel ban.

Type annotations for
`session.create_client("chime-sdk-messaging").describe_channel_ban` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.describe_channel_ban](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_ban)

Asynchronous method. Use `await describe_channel_ban(...)` for a synchronous
call.

Arguments mapping described in
[DescribeChannelBanRequestRequestTypeDef](./type_defs.md#describechannelbanrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelBanResponseTypeDef](./type_defs.md#describechannelbanresponsetypedef).

<a id="describe_channel_flow"></a>

### describe_channel_flow

Returns the full details of a channel flow in an Amazon Chime `AppInstance`.

Type annotations for
`session.create_client("chime-sdk-messaging").describe_channel_flow` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.describe_channel_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_flow)

Asynchronous method. Use `await describe_channel_flow(...)` for a synchronous
call.

Arguments mapping described in
[DescribeChannelFlowRequestRequestTypeDef](./type_defs.md#describechannelflowrequestrequesttypedef).

Keyword-only arguments:

- `ChannelFlowArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelFlowResponseTypeDef](./type_defs.md#describechannelflowresponsetypedef).

<a id="describe_channel_membership"></a>

### describe_channel_membership

Returns the full details of a user's channel membership.

Type annotations for
`session.create_client("chime-sdk-messaging").describe_channel_membership`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.describe_channel_membership](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_membership)

Asynchronous method. Use `await describe_channel_membership(...)` for a
synchronous call.

Arguments mapping described in
[DescribeChannelMembershipRequestRequestTypeDef](./type_defs.md#describechannelmembershiprequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelMembershipResponseTypeDef](./type_defs.md#describechannelmembershipresponsetypedef).

<a id="describe_channel_membership_for_app_instance_user"></a>

### describe_channel_membership_for_app_instance_user

Returns the details of a channel based on the membership of the specified
`AppInstanceUser` .

Type annotations for
`session.create_client("chime-sdk-messaging").describe_channel_membership_for_app_instance_user`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.describe_channel_membership_for_app_instance_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_membership_for_app_instance_user)

Asynchronous method. Use
`await describe_channel_membership_for_app_instance_user(...)` for a
synchronous call.

Arguments mapping described in
[DescribeChannelMembershipForAppInstanceUserRequestRequestTypeDef](./type_defs.md#describechannelmembershipforappinstanceuserrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `AppInstanceUserArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelMembershipForAppInstanceUserResponseTypeDef](./type_defs.md#describechannelmembershipforappinstanceuserresponsetypedef).

<a id="describe_channel_moderated_by_app_instance_user"></a>

### describe_channel_moderated_by_app_instance_user

Returns the full details of a channel moderated by the specified
`AppInstanceUser` .

Type annotations for
`session.create_client("chime-sdk-messaging").describe_channel_moderated_by_app_instance_user`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.describe_channel_moderated_by_app_instance_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_moderated_by_app_instance_user)

Asynchronous method. Use
`await describe_channel_moderated_by_app_instance_user(...)` for a synchronous
call.

Arguments mapping described in
[DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef](./type_defs.md#describechannelmoderatedbyappinstanceuserrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `AppInstanceUserArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelModeratedByAppInstanceUserResponseTypeDef](./type_defs.md#describechannelmoderatedbyappinstanceuserresponsetypedef).

<a id="describe_channel_moderator"></a>

### describe_channel_moderator

Returns the full details of a single ChannelModerator.

Type annotations for
`session.create_client("chime-sdk-messaging").describe_channel_moderator`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.describe_channel_moderator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_moderator)

Asynchronous method. Use `await describe_channel_moderator(...)` for a
synchronous call.

Arguments mapping described in
[DescribeChannelModeratorRequestRequestTypeDef](./type_defs.md#describechannelmoderatorrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChannelModeratorArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[DescribeChannelModeratorResponseTypeDef](./type_defs.md#describechannelmoderatorresponsetypedef).

<a id="disassociate_channel_flow"></a>

### disassociate_channel_flow

Disassociates a channel flow from all its channels.

Type annotations for
`session.create_client("chime-sdk-messaging").disassociate_channel_flow`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.disassociate_channel_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.disassociate_channel_flow)

Asynchronous method. Use `await disassociate_channel_flow(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateChannelFlowRequestRequestTypeDef](./type_defs.md#disassociatechannelflowrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChannelFlowArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("chime-sdk-messaging").generate_presigned_url` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_channel_membership_preferences"></a>

### get_channel_membership_preferences

Gets the membership preferences of an `AppInstanceUser` for the specified
channel.

Type annotations for
`session.create_client("chime-sdk-messaging").get_channel_membership_preferences`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.get_channel_membership_preferences](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_channel_membership_preferences)

Asynchronous method. Use `await get_channel_membership_preferences(...)` for a
synchronous call.

Arguments mapping described in
[GetChannelMembershipPreferencesRequestRequestTypeDef](./type_defs.md#getchannelmembershippreferencesrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[GetChannelMembershipPreferencesResponseTypeDef](./type_defs.md#getchannelmembershippreferencesresponsetypedef).

<a id="get_channel_message"></a>

### get_channel_message

Gets the full details of a channel message.

Type annotations for
`session.create_client("chime-sdk-messaging").get_channel_message` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.get_channel_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_channel_message)

Asynchronous method. Use `await get_channel_message(...)` for a synchronous
call.

Arguments mapping described in
[GetChannelMessageRequestRequestTypeDef](./type_defs.md#getchannelmessagerequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MessageId`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[GetChannelMessageResponseTypeDef](./type_defs.md#getchannelmessageresponsetypedef).

<a id="get_channel_message_status"></a>

### get_channel_message_status

Gets message status for a specified `messageId`.

Type annotations for
`session.create_client("chime-sdk-messaging").get_channel_message_status`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.get_channel_message_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_channel_message_status)

Asynchronous method. Use `await get_channel_message_status(...)` for a
synchronous call.

Arguments mapping described in
[GetChannelMessageStatusRequestRequestTypeDef](./type_defs.md#getchannelmessagestatusrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MessageId`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[GetChannelMessageStatusResponseTypeDef](./type_defs.md#getchannelmessagestatusresponsetypedef).

<a id="get_messaging_session_endpoint"></a>

### get_messaging_session_endpoint

The details of the endpoint for the messaging session.

Type annotations for
`session.create_client("chime-sdk-messaging").get_messaging_session_endpoint`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.get_messaging_session_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_messaging_session_endpoint)

Asynchronous method. Use `await get_messaging_session_endpoint(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetMessagingSessionEndpointResponseTypeDef](./type_defs.md#getmessagingsessionendpointresponsetypedef).

<a id="list_channel_bans"></a>

### list_channel_bans

Lists all the users banned from a particular channel.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channel_bans` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channel_bans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_bans)

Asynchronous method. Use `await list_channel_bans(...)` for a synchronous call.

Arguments mapping described in
[ListChannelBansRequestRequestTypeDef](./type_defs.md#listchannelbansrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelBansResponseTypeDef](./type_defs.md#listchannelbansresponsetypedef).

<a id="list_channel_flows"></a>

### list_channel_flows

Returns a paginated lists of all the channel flows created under a single
Chime.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channel_flows` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channel_flows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_flows)

Asynchronous method. Use `await list_channel_flows(...)` for a synchronous
call.

Arguments mapping described in
[ListChannelFlowsRequestRequestTypeDef](./type_defs.md#listchannelflowsrequestrequesttypedef).

Keyword-only arguments:

- `AppInstanceArn`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelFlowsResponseTypeDef](./type_defs.md#listchannelflowsresponsetypedef).

<a id="list_channel_memberships"></a>

### list_channel_memberships

Lists all channel memberships in a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channel_memberships` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channel_memberships](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_memberships)

Asynchronous method. Use `await list_channel_memberships(...)` for a
synchronous call.

Arguments mapping described in
[ListChannelMembershipsRequestRequestTypeDef](./type_defs.md#listchannelmembershipsrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `Type`: [ChannelMembershipTypeType](./literals.md#channelmembershiptypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelMembershipsResponseTypeDef](./type_defs.md#listchannelmembershipsresponsetypedef).

<a id="list_channel_memberships_for_app_instance_user"></a>

### list_channel_memberships_for_app_instance_user

Lists all channels that a particular `AppInstanceUser` is a part of.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channel_memberships_for_app_instance_user`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channel_memberships_for_app_instance_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_memberships_for_app_instance_user)

Asynchronous method. Use
`await list_channel_memberships_for_app_instance_user(...)` for a synchronous
call.

Arguments mapping described in
[ListChannelMembershipsForAppInstanceUserRequestRequestTypeDef](./type_defs.md#listchannelmembershipsforappinstanceuserrequestrequesttypedef).

Keyword-only arguments:

- `ChimeBearer`: `str` *(required)*
- `AppInstanceUserArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelMembershipsForAppInstanceUserResponseTypeDef](./type_defs.md#listchannelmembershipsforappinstanceuserresponsetypedef).

<a id="list_channel_messages"></a>

### list_channel_messages

List all the messages in a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channel_messages` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channel_messages](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_messages)

Asynchronous method. Use `await list_channel_messages(...)` for a synchronous
call.

Arguments mapping described in
[ListChannelMessagesRequestRequestTypeDef](./type_defs.md#listchannelmessagesrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NotBefore`: `Union`\[`datetime`, `str`\]
- `NotAfter`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelMessagesResponseTypeDef](./type_defs.md#listchannelmessagesresponsetypedef).

<a id="list_channel_moderators"></a>

### list_channel_moderators

Lists all the moderators for a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channel_moderators` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channel_moderators](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_moderators)

Asynchronous method. Use `await list_channel_moderators(...)` for a synchronous
call.

Arguments mapping described in
[ListChannelModeratorsRequestRequestTypeDef](./type_defs.md#listchannelmoderatorsrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelModeratorsResponseTypeDef](./type_defs.md#listchannelmoderatorsresponsetypedef).

<a id="list_channels"></a>

### list_channels

Lists all Channels created under a single Chime App as a paginated list.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channels` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channels)

Asynchronous method. Use `await list_channels(...)` for a synchronous call.

Arguments mapping described in
[ListChannelsRequestRequestTypeDef](./type_defs.md#listchannelsrequestrequesttypedef).

Keyword-only arguments:

- `AppInstanceArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `Privacy`: [ChannelPrivacyType](./literals.md#channelprivacytype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelsResponseTypeDef](./type_defs.md#listchannelsresponsetypedef).

<a id="list_channels_associated_with_channel_flow"></a>

### list_channels_associated_with_channel_flow

Lists all channels associated with a specified channel flow.

Type annotations for
`session.create_client("chime-sdk-messaging").list_channels_associated_with_channel_flow`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channels_associated_with_channel_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channels_associated_with_channel_flow)

Asynchronous method. Use
`await list_channels_associated_with_channel_flow(...)` for a synchronous call.

Arguments mapping described in
[ListChannelsAssociatedWithChannelFlowRequestRequestTypeDef](./type_defs.md#listchannelsassociatedwithchannelflowrequestrequesttypedef).

Keyword-only arguments:

- `ChannelFlowArn`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelsAssociatedWithChannelFlowResponseTypeDef](./type_defs.md#listchannelsassociatedwithchannelflowresponsetypedef).

<a id="list_channels_moderated_by_app_instance_user"></a>

### list_channels_moderated_by_app_instance_user

A list of the channels moderated by an `AppInstanceUser` .

Type annotations for
`session.create_client("chime-sdk-messaging").list_channels_moderated_by_app_instance_user`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_channels_moderated_by_app_instance_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channels_moderated_by_app_instance_user)

Asynchronous method. Use
`await list_channels_moderated_by_app_instance_user(...)` for a synchronous
call.

Arguments mapping described in
[ListChannelsModeratedByAppInstanceUserRequestRequestTypeDef](./type_defs.md#listchannelsmoderatedbyappinstanceuserrequestrequesttypedef).

Keyword-only arguments:

- `ChimeBearer`: `str` *(required)*
- `AppInstanceUserArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChannelsModeratedByAppInstanceUserResponseTypeDef](./type_defs.md#listchannelsmoderatedbyappinstanceuserresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags applied to an Amazon Chime SDK messaging resource.

Type annotations for
`session.create_client("chime-sdk-messaging").list_tags_for_resource` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_channel_membership_preferences"></a>

### put_channel_membership_preferences

Sets the membership preferences of an `AppInstanceUser` for the specified
channel.

Type annotations for
`session.create_client("chime-sdk-messaging").put_channel_membership_preferences`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.put_channel_membership_preferences](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.put_channel_membership_preferences)

Asynchronous method. Use `await put_channel_membership_preferences(...)` for a
synchronous call.

Arguments mapping described in
[PutChannelMembershipPreferencesRequestRequestTypeDef](./type_defs.md#putchannelmembershippreferencesrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MemberArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `Preferences`:
  [ChannelMembershipPreferencesTypeDef](./type_defs.md#channelmembershippreferencestypedef)
  *(required)*

Returns a `Coroutine` for
[PutChannelMembershipPreferencesResponseTypeDef](./type_defs.md#putchannelmembershippreferencesresponsetypedef).

<a id="redact_channel_message"></a>

### redact_channel_message

Redacts message content, but not metadata.

Type annotations for
`session.create_client("chime-sdk-messaging").redact_channel_message` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.redact_channel_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.redact_channel_message)

Asynchronous method. Use `await redact_channel_message(...)` for a synchronous
call.

Arguments mapping described in
[RedactChannelMessageRequestRequestTypeDef](./type_defs.md#redactchannelmessagerequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MessageId`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[RedactChannelMessageResponseTypeDef](./type_defs.md#redactchannelmessageresponsetypedef).

<a id="send_channel_message"></a>

### send_channel_message

Sends a message to a particular channel that the member is a part of.

Type annotations for
`session.create_client("chime-sdk-messaging").send_channel_message` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.send_channel_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.send_channel_message)

Asynchronous method. Use `await send_channel_message(...)` for a synchronous
call.

Arguments mapping described in
[SendChannelMessageRequestRequestTypeDef](./type_defs.md#sendchannelmessagerequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `Content`: `str` *(required)*
- `Type`: [ChannelMessageTypeType](./literals.md#channelmessagetypetype)
  *(required)*
- `Persistence`:
  [ChannelMessagePersistenceTypeType](./literals.md#channelmessagepersistencetypetype)
  *(required)*
- `ClientRequestToken`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `Metadata`: `str`
- `PushNotification`:
  [PushNotificationConfigurationTypeDef](./type_defs.md#pushnotificationconfigurationtypedef)
- `MessageAttributes`: `Mapping`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]

Returns a `Coroutine` for
[SendChannelMessageResponseTypeDef](./type_defs.md#sendchannelmessageresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Applies the specified tags to the specified Amazon Chime SDK messaging
resource.

Type annotations for
`session.create_client("chime-sdk-messaging").tag_resource` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

<a id="untag_resource"></a>

### untag_resource

Removes the specified tags from the specified Amazon Chime SDK messaging
resource.

Type annotations for
`session.create_client("chime-sdk-messaging").untag_resource` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update_channel"></a>

### update_channel

Update a channel's attributes.

Type annotations for
`session.create_client("chime-sdk-messaging").update_channel` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.update_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel)

Asynchronous method. Use `await update_channel(...)` for a synchronous call.

Arguments mapping described in
[UpdateChannelRequestRequestTypeDef](./type_defs.md#updatechannelrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `Name`: `str` *(required)*
- `Mode`: [ChannelModeType](./literals.md#channelmodetype) *(required)*
- `ChimeBearer`: `str` *(required)*
- `Metadata`: `str`

Returns a `Coroutine` for
[UpdateChannelResponseTypeDef](./type_defs.md#updatechannelresponsetypedef).

<a id="update_channel_flow"></a>

### update_channel_flow

Updates channel flow attributes.

Type annotations for
`session.create_client("chime-sdk-messaging").update_channel_flow` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.update_channel_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel_flow)

Asynchronous method. Use `await update_channel_flow(...)` for a synchronous
call.

Arguments mapping described in
[UpdateChannelFlowRequestRequestTypeDef](./type_defs.md#updatechannelflowrequestrequesttypedef).

Keyword-only arguments:

- `ChannelFlowArn`: `str` *(required)*
- `Processors`:
  `Sequence`\[[ProcessorTypeDef](./type_defs.md#processortypedef)\]
  *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[UpdateChannelFlowResponseTypeDef](./type_defs.md#updatechannelflowresponsetypedef).

<a id="update_channel_message"></a>

### update_channel_message

Updates the content of a message.

Type annotations for
`session.create_client("chime-sdk-messaging").update_channel_message` method.

Boto3 documentation:
[ChimeSDKMessaging.Client.update_channel_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel_message)

Asynchronous method. Use `await update_channel_message(...)` for a synchronous
call.

Arguments mapping described in
[UpdateChannelMessageRequestRequestTypeDef](./type_defs.md#updatechannelmessagerequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `MessageId`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*
- `Content`: `str`
- `Metadata`: `str`

Returns a `Coroutine` for
[UpdateChannelMessageResponseTypeDef](./type_defs.md#updatechannelmessageresponsetypedef).

<a id="update_channel_read_marker"></a>

### update_channel_read_marker

The details of the time when a user last read messages in a channel.

Type annotations for
`session.create_client("chime-sdk-messaging").update_channel_read_marker`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.update_channel_read_marker](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel_read_marker)

Asynchronous method. Use `await update_channel_read_marker(...)` for a
synchronous call.

Arguments mapping described in
[UpdateChannelReadMarkerRequestRequestTypeDef](./type_defs.md#updatechannelreadmarkerrequestrequesttypedef).

Keyword-only arguments:

- `ChannelArn`: `str` *(required)*
- `ChimeBearer`: `str` *(required)*

Returns a `Coroutine` for
[UpdateChannelReadMarkerResponseTypeDef](./type_defs.md#updatechannelreadmarkerresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("chime-sdk-messaging").__aenter__`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [ChimeSDKMessagingClient](#chimesdkmessagingclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("chime-sdk-messaging").__aexit__`
method.

Boto3 documentation:
[ChimeSDKMessaging.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
