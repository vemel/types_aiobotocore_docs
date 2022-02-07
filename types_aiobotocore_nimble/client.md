<a id="nimblestudioclient-for-aiobotocore-nimblestudio-module"></a>

# NimbleStudioClient for aiobotocore NimbleStudio module

> [Index](..) > [NimbleStudio](.) > NimbleStudioClient

Auto-generated documentation for
[NimbleStudio](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio)
type annotations stubs module
[types-aiobotocore-nimble](https://pypi.org/project/types-aiobotocore-nimble/).

- [NimbleStudioClient for aiobotocore NimbleStudio module](#nimblestudioclient-for-aiobotocore-nimblestudio-module)
  - [NimbleStudioClient](#nimblestudioclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_eulas](#accept_eulas)
    - [can_paginate](#can_paginate)
    - [create_launch_profile](#create_launch_profile)
    - [create_streaming_image](#create_streaming_image)
    - [create_streaming_session](#create_streaming_session)
    - [create_streaming_session_stream](#create_streaming_session_stream)
    - [create_studio](#create_studio)
    - [create_studio_component](#create_studio_component)
    - [delete_launch_profile](#delete_launch_profile)
    - [delete_launch_profile_member](#delete_launch_profile_member)
    - [delete_streaming_image](#delete_streaming_image)
    - [delete_streaming_session](#delete_streaming_session)
    - [delete_studio](#delete_studio)
    - [delete_studio_component](#delete_studio_component)
    - [delete_studio_member](#delete_studio_member)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_eula](#get_eula)
    - [get_launch_profile](#get_launch_profile)
    - [get_launch_profile_details](#get_launch_profile_details)
    - [get_launch_profile_initialization](#get_launch_profile_initialization)
    - [get_launch_profile_member](#get_launch_profile_member)
    - [get_streaming_image](#get_streaming_image)
    - [get_streaming_session](#get_streaming_session)
    - [get_streaming_session_stream](#get_streaming_session_stream)
    - [get_studio](#get_studio)
    - [get_studio_component](#get_studio_component)
    - [get_studio_member](#get_studio_member)
    - [list_eula_acceptances](#list_eula_acceptances)
    - [list_eulas](#list_eulas)
    - [list_launch_profile_members](#list_launch_profile_members)
    - [list_launch_profiles](#list_launch_profiles)
    - [list_streaming_images](#list_streaming_images)
    - [list_streaming_sessions](#list_streaming_sessions)
    - [list_studio_components](#list_studio_components)
    - [list_studio_members](#list_studio_members)
    - [list_studios](#list_studios)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_launch_profile_members](#put_launch_profile_members)
    - [put_studio_members](#put_studio_members)
    - [start_streaming_session](#start_streaming_session)
    - [start_studio_sso_configuration_repair](#start_studio_sso_configuration_repair)
    - [stop_streaming_session](#stop_streaming_session)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_launch_profile](#update_launch_profile)
    - [update_launch_profile_member](#update_launch_profile_member)
    - [update_streaming_image](#update_streaming_image)
    - [update_studio](#update_studio)
    - [update_studio_component](#update_studio_component)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="nimblestudioclient"></a>

## NimbleStudioClient

Type annotations for `session.create_client("nimble")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_nimble.client import NimbleStudioClient

session = get_session()
async with session.create_client("nimble") as client:
    client: NimbleStudioClient
```

Boto3 documentation:
[NimbleStudio.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_nimble.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerErrorException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

NimbleStudioClient exceptions.

Type annotations for `session.create_client("nimble").exceptions` method.

Boto3 documentation:
[NimbleStudio.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept_eulas"></a>

### accept_eulas

Accept EULAs.

Type annotations for `session.create_client("nimble").accept_eulas` method.

Boto3 documentation:
[NimbleStudio.Client.accept_eulas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.accept_eulas)

Asynchronous method. Use `await accept_eulas(...)` for a synchronous call.

Arguments mapping described in
[AcceptEulasRequestRequestTypeDef](./type_defs.md#accepteulasrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `eulaIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[AcceptEulasResponseTypeDef](./type_defs.md#accepteulasresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("nimble").can_paginate` method.

Boto3 documentation:
[NimbleStudio.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_launch_profile"></a>

### create_launch_profile

Create a launch profile.

Type annotations for `session.create_client("nimble").create_launch_profile`
method.

Boto3 documentation:
[NimbleStudio.Client.create_launch_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.create_launch_profile)

Asynchronous method. Use `await create_launch_profile(...)` for a synchronous
call.

Arguments mapping described in
[CreateLaunchProfileRequestRequestTypeDef](./type_defs.md#createlaunchprofilerequestrequesttypedef).

Keyword-only arguments:

- `ec2SubnetIds`: `Sequence`\[`str`\] *(required)*
- `launchProfileProtocolVersions`: `Sequence`\[`str`\] *(required)*
- `name`: `str` *(required)*
- `streamConfiguration`:
  [StreamConfigurationCreateTypeDef](./type_defs.md#streamconfigurationcreatetypedef)
  *(required)*
- `studioComponentIds`: `Sequence`\[`str`\] *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `description`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateLaunchProfileResponseTypeDef](./type_defs.md#createlaunchprofileresponsetypedef).

<a id="create_streaming_image"></a>

### create_streaming_image

Creates a streaming image resource in a studio.

Type annotations for `session.create_client("nimble").create_streaming_image`
method.

Boto3 documentation:
[NimbleStudio.Client.create_streaming_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.create_streaming_image)

Asynchronous method. Use `await create_streaming_image(...)` for a synchronous
call.

Arguments mapping described in
[CreateStreamingImageRequestRequestTypeDef](./type_defs.md#createstreamingimagerequestrequesttypedef).

Keyword-only arguments:

- `ec2ImageId`: `str` *(required)*
- `name`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `description`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateStreamingImageResponseTypeDef](./type_defs.md#createstreamingimageresponsetypedef).

<a id="create_streaming_session"></a>

### create_streaming_session

Creates a streaming session in a studio.

Type annotations for `session.create_client("nimble").create_streaming_session`
method.

Boto3 documentation:
[NimbleStudio.Client.create_streaming_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.create_streaming_session)

Asynchronous method. Use `await create_streaming_session(...)` for a
synchronous call.

Arguments mapping described in
[CreateStreamingSessionRequestRequestTypeDef](./type_defs.md#createstreamingsessionrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `ec2InstanceType`:
  [StreamingInstanceTypeType](./literals.md#streaminginstancetypetype)
- `launchProfileId`: `str`
- `ownedBy`: `str`
- `streamingImageId`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateStreamingSessionResponseTypeDef](./type_defs.md#createstreamingsessionresponsetypedef).

<a id="create_streaming_session_stream"></a>

### create_streaming_session_stream

Creates a streaming session stream for a streaming session.

Type annotations for
`session.create_client("nimble").create_streaming_session_stream` method.

Boto3 documentation:
[NimbleStudio.Client.create_streaming_session_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.create_streaming_session_stream)

Asynchronous method. Use `await create_streaming_session_stream(...)` for a
synchronous call.

Arguments mapping described in
[CreateStreamingSessionStreamRequestRequestTypeDef](./type_defs.md#createstreamingsessionstreamrequestrequesttypedef).

Keyword-only arguments:

- `sessionId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `expirationInSeconds`: `int`

Returns a `Coroutine` for
[CreateStreamingSessionStreamResponseTypeDef](./type_defs.md#createstreamingsessionstreamresponsetypedef).

<a id="create_studio"></a>

### create_studio

Create a new Studio.

Type annotations for `session.create_client("nimble").create_studio` method.

Boto3 documentation:
[NimbleStudio.Client.create_studio](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.create_studio)

Asynchronous method. Use `await create_studio(...)` for a synchronous call.

Arguments mapping described in
[CreateStudioRequestRequestTypeDef](./type_defs.md#createstudiorequestrequesttypedef).

Keyword-only arguments:

- `adminRoleArn`: `str` *(required)*
- `displayName`: `str` *(required)*
- `studioName`: `str` *(required)*
- `userRoleArn`: `str` *(required)*
- `clientToken`: `str`
- `studioEncryptionConfiguration`:
  [StudioEncryptionConfigurationTypeDef](./type_defs.md#studioencryptionconfigurationtypedef)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateStudioResponseTypeDef](./type_defs.md#createstudioresponsetypedef).

<a id="create_studio_component"></a>

### create_studio_component

Creates a studio component resource.

Type annotations for `session.create_client("nimble").create_studio_component`
method.

Boto3 documentation:
[NimbleStudio.Client.create_studio_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.create_studio_component)

Asynchronous method. Use `await create_studio_component(...)` for a synchronous
call.

Arguments mapping described in
[CreateStudioComponentRequestRequestTypeDef](./type_defs.md#createstudiocomponentrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `studioId`: `str` *(required)*
- `type`: [StudioComponentTypeType](./literals.md#studiocomponenttypetype)
  *(required)*
- `clientToken`: `str`
- `configuration`:
  [StudioComponentConfigurationTypeDef](./type_defs.md#studiocomponentconfigurationtypedef)
- `description`: `str`
- `ec2SecurityGroupIds`: `Sequence`\[`str`\]
- `initializationScripts`:
  `Sequence`\[[StudioComponentInitializationScriptTypeDef](./type_defs.md#studiocomponentinitializationscripttypedef)\]
- `scriptParameters`:
  `Sequence`\[[ScriptParameterKeyValueTypeDef](./type_defs.md#scriptparameterkeyvaluetypedef)\]
- `subtype`:
  [StudioComponentSubtypeType](./literals.md#studiocomponentsubtypetype)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateStudioComponentResponseTypeDef](./type_defs.md#createstudiocomponentresponsetypedef).

<a id="delete_launch_profile"></a>

### delete_launch_profile

Permanently delete a launch profile.

Type annotations for `session.create_client("nimble").delete_launch_profile`
method.

Boto3 documentation:
[NimbleStudio.Client.delete_launch_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.delete_launch_profile)

Asynchronous method. Use `await delete_launch_profile(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLaunchProfileRequestRequestTypeDef](./type_defs.md#deletelaunchprofilerequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[DeleteLaunchProfileResponseTypeDef](./type_defs.md#deletelaunchprofileresponsetypedef).

<a id="delete_launch_profile_member"></a>

### delete_launch_profile_member

Delete a user from launch profile membership.

Type annotations for
`session.create_client("nimble").delete_launch_profile_member` method.

Boto3 documentation:
[NimbleStudio.Client.delete_launch_profile_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.delete_launch_profile_member)

Asynchronous method. Use `await delete_launch_profile_member(...)` for a
synchronous call.

Arguments mapping described in
[DeleteLaunchProfileMemberRequestRequestTypeDef](./type_defs.md#deletelaunchprofilememberrequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `principalId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_streaming_image"></a>

### delete_streaming_image

Delete streaming image.

Type annotations for `session.create_client("nimble").delete_streaming_image`
method.

Boto3 documentation:
[NimbleStudio.Client.delete_streaming_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.delete_streaming_image)

Asynchronous method. Use `await delete_streaming_image(...)` for a synchronous
call.

Arguments mapping described in
[DeleteStreamingImageRequestRequestTypeDef](./type_defs.md#deletestreamingimagerequestrequesttypedef).

Keyword-only arguments:

- `streamingImageId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[DeleteStreamingImageResponseTypeDef](./type_defs.md#deletestreamingimageresponsetypedef).

<a id="delete_streaming_session"></a>

### delete_streaming_session

Deletes streaming session resource.

Type annotations for `session.create_client("nimble").delete_streaming_session`
method.

Boto3 documentation:
[NimbleStudio.Client.delete_streaming_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.delete_streaming_session)

Asynchronous method. Use `await delete_streaming_session(...)` for a
synchronous call.

Arguments mapping described in
[DeleteStreamingSessionRequestRequestTypeDef](./type_defs.md#deletestreamingsessionrequestrequesttypedef).

Keyword-only arguments:

- `sessionId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[DeleteStreamingSessionResponseTypeDef](./type_defs.md#deletestreamingsessionresponsetypedef).

<a id="delete_studio"></a>

### delete_studio

Delete a studio resource.

Type annotations for `session.create_client("nimble").delete_studio` method.

Boto3 documentation:
[NimbleStudio.Client.delete_studio](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.delete_studio)

Asynchronous method. Use `await delete_studio(...)` for a synchronous call.

Arguments mapping described in
[DeleteStudioRequestRequestTypeDef](./type_defs.md#deletestudiorequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[DeleteStudioResponseTypeDef](./type_defs.md#deletestudioresponsetypedef).

<a id="delete_studio_component"></a>

### delete_studio_component

Deletes a studio component resource.

Type annotations for `session.create_client("nimble").delete_studio_component`
method.

Boto3 documentation:
[NimbleStudio.Client.delete_studio_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.delete_studio_component)

Asynchronous method. Use `await delete_studio_component(...)` for a synchronous
call.

Arguments mapping described in
[DeleteStudioComponentRequestRequestTypeDef](./type_defs.md#deletestudiocomponentrequestrequesttypedef).

Keyword-only arguments:

- `studioComponentId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[DeleteStudioComponentResponseTypeDef](./type_defs.md#deletestudiocomponentresponsetypedef).

<a id="delete_studio_member"></a>

### delete_studio_member

Delete a user from studio membership.

Type annotations for `session.create_client("nimble").delete_studio_member`
method.

Boto3 documentation:
[NimbleStudio.Client.delete_studio_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.delete_studio_member)

Asynchronous method. Use `await delete_studio_member(...)` for a synchronous
call.

Arguments mapping described in
[DeleteStudioMemberRequestRequestTypeDef](./type_defs.md#deletestudiomemberrequestrequesttypedef).

Keyword-only arguments:

- `principalId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("nimble").generate_presigned_url`
method.

Boto3 documentation:
[NimbleStudio.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_eula"></a>

### get_eula

Get Eula.

Type annotations for `session.create_client("nimble").get_eula` method.

Boto3 documentation:
[NimbleStudio.Client.get_eula](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_eula)

Asynchronous method. Use `await get_eula(...)` for a synchronous call.

Arguments mapping described in
[GetEulaRequestRequestTypeDef](./type_defs.md#geteularequestrequesttypedef).

Keyword-only arguments:

- `eulaId`: `str` *(required)*

Returns a `Coroutine` for
[GetEulaResponseTypeDef](./type_defs.md#geteularesponsetypedef).

<a id="get_launch_profile"></a>

### get_launch_profile

Get a launch profile.

Type annotations for `session.create_client("nimble").get_launch_profile`
method.

Boto3 documentation:
[NimbleStudio.Client.get_launch_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_launch_profile)

Asynchronous method. Use `await get_launch_profile(...)` for a synchronous
call.

Arguments mapping described in
[GetLaunchProfileRequestRequestTypeDef](./type_defs.md#getlaunchprofilerequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetLaunchProfileResponseTypeDef](./type_defs.md#getlaunchprofileresponsetypedef).

<a id="get_launch_profile_details"></a>

### get_launch_profile_details

Launch profile details include the launch profile resource and summary
information of resources that are used by, or available to, the launch profile.

Type annotations for
`session.create_client("nimble").get_launch_profile_details` method.

Boto3 documentation:
[NimbleStudio.Client.get_launch_profile_details](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_launch_profile_details)

Asynchronous method. Use `await get_launch_profile_details(...)` for a
synchronous call.

Arguments mapping described in
[GetLaunchProfileDetailsRequestRequestTypeDef](./type_defs.md#getlaunchprofiledetailsrequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetLaunchProfileDetailsResponseTypeDef](./type_defs.md#getlaunchprofiledetailsresponsetypedef).

<a id="get_launch_profile_initialization"></a>

### get_launch_profile_initialization

Get a launch profile initialization.

Type annotations for
`session.create_client("nimble").get_launch_profile_initialization` method.

Boto3 documentation:
[NimbleStudio.Client.get_launch_profile_initialization](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_launch_profile_initialization)

Asynchronous method. Use `await get_launch_profile_initialization(...)` for a
synchronous call.

Arguments mapping described in
[GetLaunchProfileInitializationRequestRequestTypeDef](./type_defs.md#getlaunchprofileinitializationrequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `launchProfileProtocolVersions`: `Sequence`\[`str`\] *(required)*
- `launchPurpose`: `str` *(required)*
- `platform`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetLaunchProfileInitializationResponseTypeDef](./type_defs.md#getlaunchprofileinitializationresponsetypedef).

<a id="get_launch_profile_member"></a>

### get_launch_profile_member

Get a user persona in launch profile membership.

Type annotations for
`session.create_client("nimble").get_launch_profile_member` method.

Boto3 documentation:
[NimbleStudio.Client.get_launch_profile_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_launch_profile_member)

Asynchronous method. Use `await get_launch_profile_member(...)` for a
synchronous call.

Arguments mapping described in
[GetLaunchProfileMemberRequestRequestTypeDef](./type_defs.md#getlaunchprofilememberrequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `principalId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetLaunchProfileMemberResponseTypeDef](./type_defs.md#getlaunchprofilememberresponsetypedef).

<a id="get_streaming_image"></a>

### get_streaming_image

Get streaming image.

Type annotations for `session.create_client("nimble").get_streaming_image`
method.

Boto3 documentation:
[NimbleStudio.Client.get_streaming_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_streaming_image)

Asynchronous method. Use `await get_streaming_image(...)` for a synchronous
call.

Arguments mapping described in
[GetStreamingImageRequestRequestTypeDef](./type_defs.md#getstreamingimagerequestrequesttypedef).

Keyword-only arguments:

- `streamingImageId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetStreamingImageResponseTypeDef](./type_defs.md#getstreamingimageresponsetypedef).

<a id="get_streaming_session"></a>

### get_streaming_session

Gets StreamingSession resource.

Type annotations for `session.create_client("nimble").get_streaming_session`
method.

Boto3 documentation:
[NimbleStudio.Client.get_streaming_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_streaming_session)

Asynchronous method. Use `await get_streaming_session(...)` for a synchronous
call.

Arguments mapping described in
[GetStreamingSessionRequestRequestTypeDef](./type_defs.md#getstreamingsessionrequestrequesttypedef).

Keyword-only arguments:

- `sessionId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetStreamingSessionResponseTypeDef](./type_defs.md#getstreamingsessionresponsetypedef).

<a id="get_streaming_session_stream"></a>

### get_streaming_session_stream

Gets a StreamingSessionStream for a streaming session.

Type annotations for
`session.create_client("nimble").get_streaming_session_stream` method.

Boto3 documentation:
[NimbleStudio.Client.get_streaming_session_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_streaming_session_stream)

Asynchronous method. Use `await get_streaming_session_stream(...)` for a
synchronous call.

Arguments mapping described in
[GetStreamingSessionStreamRequestRequestTypeDef](./type_defs.md#getstreamingsessionstreamrequestrequesttypedef).

Keyword-only arguments:

- `sessionId`: `str` *(required)*
- `streamId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetStreamingSessionStreamResponseTypeDef](./type_defs.md#getstreamingsessionstreamresponsetypedef).

<a id="get_studio"></a>

### get_studio

Get a Studio resource.

Type annotations for `session.create_client("nimble").get_studio` method.

Boto3 documentation:
[NimbleStudio.Client.get_studio](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_studio)

Asynchronous method. Use `await get_studio(...)` for a synchronous call.

Arguments mapping described in
[GetStudioRequestRequestTypeDef](./type_defs.md#getstudiorequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetStudioResponseTypeDef](./type_defs.md#getstudioresponsetypedef).

<a id="get_studio_component"></a>

### get_studio_component

Gets a studio component resource.

Type annotations for `session.create_client("nimble").get_studio_component`
method.

Boto3 documentation:
[NimbleStudio.Client.get_studio_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_studio_component)

Asynchronous method. Use `await get_studio_component(...)` for a synchronous
call.

Arguments mapping described in
[GetStudioComponentRequestRequestTypeDef](./type_defs.md#getstudiocomponentrequestrequesttypedef).

Keyword-only arguments:

- `studioComponentId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetStudioComponentResponseTypeDef](./type_defs.md#getstudiocomponentresponsetypedef).

<a id="get_studio_member"></a>

### get_studio_member

Get a user's membership in a studio.

Type annotations for `session.create_client("nimble").get_studio_member`
method.

Boto3 documentation:
[NimbleStudio.Client.get_studio_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.get_studio_member)

Asynchronous method. Use `await get_studio_member(...)` for a synchronous call.

Arguments mapping described in
[GetStudioMemberRequestRequestTypeDef](./type_defs.md#getstudiomemberrequestrequesttypedef).

Keyword-only arguments:

- `principalId`: `str` *(required)*
- `studioId`: `str` *(required)*

Returns a `Coroutine` for
[GetStudioMemberResponseTypeDef](./type_defs.md#getstudiomemberresponsetypedef).

<a id="list_eula_acceptances"></a>

### list_eula_acceptances

List Eula Acceptances.

Type annotations for `session.create_client("nimble").list_eula_acceptances`
method.

Boto3 documentation:
[NimbleStudio.Client.list_eula_acceptances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_eula_acceptances)

Asynchronous method. Use `await list_eula_acceptances(...)` for a synchronous
call.

Arguments mapping described in
[ListEulaAcceptancesRequestRequestTypeDef](./type_defs.md#listeulaacceptancesrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `eulaIds`: `Sequence`\[`str`\]
- `nextToken`: `str`

Returns a `Coroutine` for
[ListEulaAcceptancesResponseTypeDef](./type_defs.md#listeulaacceptancesresponsetypedef).

<a id="list_eulas"></a>

### list_eulas

List Eulas.

Type annotations for `session.create_client("nimble").list_eulas` method.

Boto3 documentation:
[NimbleStudio.Client.list_eulas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_eulas)

Asynchronous method. Use `await list_eulas(...)` for a synchronous call.

Arguments mapping described in
[ListEulasRequestRequestTypeDef](./type_defs.md#listeulasrequestrequesttypedef).

Keyword-only arguments:

- `eulaIds`: `Sequence`\[`str`\]
- `nextToken`: `str`

Returns a `Coroutine` for
[ListEulasResponseTypeDef](./type_defs.md#listeulasresponsetypedef).

<a id="list_launch_profile_members"></a>

### list_launch_profile_members

Get all users in a given launch profile membership.

Type annotations for
`session.create_client("nimble").list_launch_profile_members` method.

Boto3 documentation:
[NimbleStudio.Client.list_launch_profile_members](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_launch_profile_members)

Asynchronous method. Use `await list_launch_profile_members(...)` for a
synchronous call.

Arguments mapping described in
[ListLaunchProfileMembersRequestRequestTypeDef](./type_defs.md#listlaunchprofilemembersrequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListLaunchProfileMembersResponseTypeDef](./type_defs.md#listlaunchprofilemembersresponsetypedef).

<a id="list_launch_profiles"></a>

### list_launch_profiles

List all the launch profiles a studio.

Type annotations for `session.create_client("nimble").list_launch_profiles`
method.

Boto3 documentation:
[NimbleStudio.Client.list_launch_profiles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_launch_profiles)

Asynchronous method. Use `await list_launch_profiles(...)` for a synchronous
call.

Arguments mapping described in
[ListLaunchProfilesRequestRequestTypeDef](./type_defs.md#listlaunchprofilesrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`
- `principalId`: `str`
- `states`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ListLaunchProfilesResponseTypeDef](./type_defs.md#listlaunchprofilesresponsetypedef).

<a id="list_streaming_images"></a>

### list_streaming_images

List the streaming image resources available to this studio.

Type annotations for `session.create_client("nimble").list_streaming_images`
method.

Boto3 documentation:
[NimbleStudio.Client.list_streaming_images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_streaming_images)

Asynchronous method. Use `await list_streaming_images(...)` for a synchronous
call.

Arguments mapping described in
[ListStreamingImagesRequestRequestTypeDef](./type_defs.md#liststreamingimagesrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `nextToken`: `str`
- `owner`: `str`

Returns a `Coroutine` for
[ListStreamingImagesResponseTypeDef](./type_defs.md#liststreamingimagesresponsetypedef).

<a id="list_streaming_sessions"></a>

### list_streaming_sessions

Lists the streaming image resources in a studio.

Type annotations for `session.create_client("nimble").list_streaming_sessions`
method.

Boto3 documentation:
[NimbleStudio.Client.list_streaming_sessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_streaming_sessions)

Asynchronous method. Use `await list_streaming_sessions(...)` for a synchronous
call.

Arguments mapping described in
[ListStreamingSessionsRequestRequestTypeDef](./type_defs.md#liststreamingsessionsrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `createdBy`: `str`
- `nextToken`: `str`
- `ownedBy`: `str`
- `sessionIds`: `str`

Returns a `Coroutine` for
[ListStreamingSessionsResponseTypeDef](./type_defs.md#liststreamingsessionsresponsetypedef).

<a id="list_studio_components"></a>

### list_studio_components

Lists the StudioComponents in a studio.

Type annotations for `session.create_client("nimble").list_studio_components`
method.

Boto3 documentation:
[NimbleStudio.Client.list_studio_components](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_studio_components)

Asynchronous method. Use `await list_studio_components(...)` for a synchronous
call.

Arguments mapping described in
[ListStudioComponentsRequestRequestTypeDef](./type_defs.md#liststudiocomponentsrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`
- `states`: `Sequence`\[`str`\]
- `types`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ListStudioComponentsResponseTypeDef](./type_defs.md#liststudiocomponentsresponsetypedef).

<a id="list_studio_members"></a>

### list_studio_members

Get all users in a given studio membership.

Type annotations for `session.create_client("nimble").list_studio_members`
method.

Boto3 documentation:
[NimbleStudio.Client.list_studio_members](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_studio_members)

Asynchronous method. Use `await list_studio_members(...)` for a synchronous
call.

Arguments mapping described in
[ListStudioMembersRequestRequestTypeDef](./type_defs.md#liststudiomembersrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListStudioMembersResponseTypeDef](./type_defs.md#liststudiomembersresponsetypedef).

<a id="list_studios"></a>

### list_studios

List studios in your Amazon Web Services account in the requested Amazon Web
Services Region.

Type annotations for `session.create_client("nimble").list_studios` method.

Boto3 documentation:
[NimbleStudio.Client.list_studios](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_studios)

Asynchronous method. Use `await list_studios(...)` for a synchronous call.

Arguments mapping described in
[ListStudiosRequestRequestTypeDef](./type_defs.md#liststudiosrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`

Returns a `Coroutine` for
[ListStudiosResponseTypeDef](./type_defs.md#liststudiosresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Gets the tags for a resource, given its Amazon Resource Names (ARN).

Type annotations for `session.create_client("nimble").list_tags_for_resource`
method.

Boto3 documentation:
[NimbleStudio.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_launch_profile_members"></a>

### put_launch_profile_members

Add/update users with given persona to launch profile membership.

Type annotations for
`session.create_client("nimble").put_launch_profile_members` method.

Boto3 documentation:
[NimbleStudio.Client.put_launch_profile_members](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.put_launch_profile_members)

Asynchronous method. Use `await put_launch_profile_members(...)` for a
synchronous call.

Arguments mapping described in
[PutLaunchProfileMembersRequestRequestTypeDef](./type_defs.md#putlaunchprofilemembersrequestrequesttypedef).

Keyword-only arguments:

- `identityStoreId`: `str` *(required)*
- `launchProfileId`: `str` *(required)*
- `members`:
  `Sequence`\[[NewLaunchProfileMemberTypeDef](./type_defs.md#newlaunchprofilemembertypedef)\]
  *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_studio_members"></a>

### put_studio_members

Add/update users with given persona to studio membership.

Type annotations for `session.create_client("nimble").put_studio_members`
method.

Boto3 documentation:
[NimbleStudio.Client.put_studio_members](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.put_studio_members)

Asynchronous method. Use `await put_studio_members(...)` for a synchronous
call.

Arguments mapping described in
[PutStudioMembersRequestRequestTypeDef](./type_defs.md#putstudiomembersrequestrequesttypedef).

Keyword-only arguments:

- `identityStoreId`: `str` *(required)*
- `members`:
  `Sequence`\[[NewStudioMemberTypeDef](./type_defs.md#newstudiomembertypedef)\]
  *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="start_streaming_session"></a>

### start_streaming_session

Transitions sessions from the STOPPED state into the READY state.

Type annotations for `session.create_client("nimble").start_streaming_session`
method.

Boto3 documentation:
[NimbleStudio.Client.start_streaming_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.start_streaming_session)

Asynchronous method. Use `await start_streaming_session(...)` for a synchronous
call.

Arguments mapping described in
[StartStreamingSessionRequestRequestTypeDef](./type_defs.md#startstreamingsessionrequestrequesttypedef).

Keyword-only arguments:

- `sessionId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[StartStreamingSessionResponseTypeDef](./type_defs.md#startstreamingsessionresponsetypedef).

<a id="start_studio_sso_configuration_repair"></a>

### start_studio_sso_configuration_repair

Repairs the Amazon Web Services SSO configuration for a given studio.

Type annotations for
`session.create_client("nimble").start_studio_sso_configuration_repair` method.

Boto3 documentation:
[NimbleStudio.Client.start_studio_sso_configuration_repair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.start_studio_sso_configuration_repair)

Asynchronous method. Use `await start_studio_sso_configuration_repair(...)` for
a synchronous call.

Arguments mapping described in
[StartStudioSSOConfigurationRepairRequestRequestTypeDef](./type_defs.md#startstudiossoconfigurationrepairrequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[StartStudioSSOConfigurationRepairResponseTypeDef](./type_defs.md#startstudiossoconfigurationrepairresponsetypedef).

<a id="stop_streaming_session"></a>

### stop_streaming_session

Transitions sessions from the READY state into the STOPPED state.

Type annotations for `session.create_client("nimble").stop_streaming_session`
method.

Boto3 documentation:
[NimbleStudio.Client.stop_streaming_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.stop_streaming_session)

Asynchronous method. Use `await stop_streaming_session(...)` for a synchronous
call.

Arguments mapping described in
[StopStreamingSessionRequestRequestTypeDef](./type_defs.md#stopstreamingsessionrequestrequesttypedef).

Keyword-only arguments:

- `sessionId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[StopStreamingSessionResponseTypeDef](./type_defs.md#stopstreamingsessionresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Creates tags for a resource, given its ARN.

Type annotations for `session.create_client("nimble").tag_resource` method.

Boto3 documentation:
[NimbleStudio.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Deletes the tags for a resource.

Type annotations for `session.create_client("nimble").untag_resource` method.

Boto3 documentation:
[NimbleStudio.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_launch_profile"></a>

### update_launch_profile

Update a launch profile.

Type annotations for `session.create_client("nimble").update_launch_profile`
method.

Boto3 documentation:
[NimbleStudio.Client.update_launch_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.update_launch_profile)

Asynchronous method. Use `await update_launch_profile(...)` for a synchronous
call.

Arguments mapping described in
[UpdateLaunchProfileRequestRequestTypeDef](./type_defs.md#updatelaunchprofilerequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `description`: `str`
- `launchProfileProtocolVersions`: `Sequence`\[`str`\]
- `name`: `str`
- `streamConfiguration`:
  [StreamConfigurationCreateTypeDef](./type_defs.md#streamconfigurationcreatetypedef)
- `studioComponentIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[UpdateLaunchProfileResponseTypeDef](./type_defs.md#updatelaunchprofileresponsetypedef).

<a id="update_launch_profile_member"></a>

### update_launch_profile_member

Update a user persona in launch profile membership.

Type annotations for
`session.create_client("nimble").update_launch_profile_member` method.

Boto3 documentation:
[NimbleStudio.Client.update_launch_profile_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.update_launch_profile_member)

Asynchronous method. Use `await update_launch_profile_member(...)` for a
synchronous call.

Arguments mapping described in
[UpdateLaunchProfileMemberRequestRequestTypeDef](./type_defs.md#updatelaunchprofilememberrequestrequesttypedef).

Keyword-only arguments:

- `launchProfileId`: `str` *(required)*
- `persona`: `Literal['USER']` (see
  [LaunchProfilePersonaType](./literals.md#launchprofilepersonatype))
  *(required)*
- `principalId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[UpdateLaunchProfileMemberResponseTypeDef](./type_defs.md#updatelaunchprofilememberresponsetypedef).

<a id="update_streaming_image"></a>

### update_streaming_image

Update streaming image.

Type annotations for `session.create_client("nimble").update_streaming_image`
method.

Boto3 documentation:
[NimbleStudio.Client.update_streaming_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.update_streaming_image)

Asynchronous method. Use `await update_streaming_image(...)` for a synchronous
call.

Arguments mapping described in
[UpdateStreamingImageRequestRequestTypeDef](./type_defs.md#updatestreamingimagerequestrequesttypedef).

Keyword-only arguments:

- `streamingImageId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `description`: `str`
- `name`: `str`

Returns a `Coroutine` for
[UpdateStreamingImageResponseTypeDef](./type_defs.md#updatestreamingimageresponsetypedef).

<a id="update_studio"></a>

### update_studio

Update a Studio resource.

Type annotations for `session.create_client("nimble").update_studio` method.

Boto3 documentation:
[NimbleStudio.Client.update_studio](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.update_studio)

Asynchronous method. Use `await update_studio(...)` for a synchronous call.

Arguments mapping described in
[UpdateStudioRequestRequestTypeDef](./type_defs.md#updatestudiorequestrequesttypedef).

Keyword-only arguments:

- `studioId`: `str` *(required)*
- `adminRoleArn`: `str`
- `clientToken`: `str`
- `displayName`: `str`
- `userRoleArn`: `str`

Returns a `Coroutine` for
[UpdateStudioResponseTypeDef](./type_defs.md#updatestudioresponsetypedef).

<a id="update_studio_component"></a>

### update_studio_component

Updates a studio component resource.

Type annotations for `session.create_client("nimble").update_studio_component`
method.

Boto3 documentation:
[NimbleStudio.Client.update_studio_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.update_studio_component)

Asynchronous method. Use `await update_studio_component(...)` for a synchronous
call.

Arguments mapping described in
[UpdateStudioComponentRequestRequestTypeDef](./type_defs.md#updatestudiocomponentrequestrequesttypedef).

Keyword-only arguments:

- `studioComponentId`: `str` *(required)*
- `studioId`: `str` *(required)*
- `clientToken`: `str`
- `configuration`:
  [StudioComponentConfigurationTypeDef](./type_defs.md#studiocomponentconfigurationtypedef)
- `description`: `str`
- `ec2SecurityGroupIds`: `Sequence`\[`str`\]
- `initializationScripts`:
  `Sequence`\[[StudioComponentInitializationScriptTypeDef](./type_defs.md#studiocomponentinitializationscripttypedef)\]
- `name`: `str`
- `scriptParameters`:
  `Sequence`\[[ScriptParameterKeyValueTypeDef](./type_defs.md#scriptparameterkeyvaluetypedef)\]
- `subtype`:
  [StudioComponentSubtypeType](./literals.md#studiocomponentsubtypetype)
- `type`: [StudioComponentTypeType](./literals.md#studiocomponenttypetype)

Returns a `Coroutine` for
[UpdateStudioComponentResponseTypeDef](./type_defs.md#updatestudiocomponentresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("nimble").__aenter__` method.

Boto3 documentation:
[NimbleStudio.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [NimbleStudioClient](#nimblestudioclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("nimble").__aexit__` method.

Boto3 documentation:
[NimbleStudio.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("nimble").get_paginator` method
with overloads.

- `client.get_paginator("list_eula_acceptances")` ->
  [ListEulaAcceptancesPaginator](./paginators.md#listeulaacceptancespaginator)
- `client.get_paginator("list_eulas")` ->
  [ListEulasPaginator](./paginators.md#listeulaspaginator)
- `client.get_paginator("list_launch_profile_members")` ->
  [ListLaunchProfileMembersPaginator](./paginators.md#listlaunchprofilememberspaginator)
- `client.get_paginator("list_launch_profiles")` ->
  [ListLaunchProfilesPaginator](./paginators.md#listlaunchprofilespaginator)
- `client.get_paginator("list_streaming_images")` ->
  [ListStreamingImagesPaginator](./paginators.md#liststreamingimagespaginator)
- `client.get_paginator("list_streaming_sessions")` ->
  [ListStreamingSessionsPaginator](./paginators.md#liststreamingsessionspaginator)
- `client.get_paginator("list_studio_components")` ->
  [ListStudioComponentsPaginator](./paginators.md#liststudiocomponentspaginator)
- `client.get_paginator("list_studio_members")` ->
  [ListStudioMembersPaginator](./paginators.md#liststudiomemberspaginator)
- `client.get_paginator("list_studios")` ->
  [ListStudiosPaginator](./paginators.md#liststudiospaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("nimble").get_waiter` method with
overloads.

- `client.get_waiter("launch_profile_deleted")` ->
  [LaunchProfileDeletedWaiter](./waiters.md#launchprofiledeletedwaiter)
- `client.get_waiter("launch_profile_ready")` ->
  [LaunchProfileReadyWaiter](./waiters.md#launchprofilereadywaiter)
- `client.get_waiter("streaming_image_deleted")` ->
  [StreamingImageDeletedWaiter](./waiters.md#streamingimagedeletedwaiter)
- `client.get_waiter("streaming_image_ready")` ->
  [StreamingImageReadyWaiter](./waiters.md#streamingimagereadywaiter)
- `client.get_waiter("streaming_session_deleted")` ->
  [StreamingSessionDeletedWaiter](./waiters.md#streamingsessiondeletedwaiter)
- `client.get_waiter("streaming_session_ready")` ->
  [StreamingSessionReadyWaiter](./waiters.md#streamingsessionreadywaiter)
- `client.get_waiter("streaming_session_stopped")` ->
  [StreamingSessionStoppedWaiter](./waiters.md#streamingsessionstoppedwaiter)
- `client.get_waiter("streaming_session_stream_ready")` ->
  [StreamingSessionStreamReadyWaiter](./waiters.md#streamingsessionstreamreadywaiter)
- `client.get_waiter("studio_component_deleted")` ->
  [StudioComponentDeletedWaiter](./waiters.md#studiocomponentdeletedwaiter)
- `client.get_waiter("studio_component_ready")` ->
  [StudioComponentReadyWaiter](./waiters.md#studiocomponentreadywaiter)
- `client.get_waiter("studio_deleted")` ->
  [StudioDeletedWaiter](./waiters.md#studiodeletedwaiter)
- `client.get_waiter("studio_ready")` ->
  [StudioReadyWaiter](./waiters.md#studioreadywaiter)
