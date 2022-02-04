<a id="chimesdkmeetingsclient-for-aiobotocore-chimesdkmeetings-module"></a>

# ChimeSDKMeetingsClient for aiobotocore ChimeSDKMeetings module

> [Index](..) > [ChimeSDKMeetings](.) > ChimeSDKMeetingsClient

Auto-generated documentation for
[ChimeSDKMeetings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
type annotations stubs module
[types-aiobotocore-chime-sdk-meetings](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings/).

- [ChimeSDKMeetingsClient for aiobotocore ChimeSDKMeetings module](#chimesdkmeetingsclient-for-aiobotocore-chimesdkmeetings-module)
  - [ChimeSDKMeetingsClient](#chimesdkmeetingsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [batch_create_attendee](#batch_create_attendee)
    - [can_paginate](#can_paginate)
    - [create_attendee](#create_attendee)
    - [create_meeting](#create_meeting)
    - [create_meeting_with_attendees](#create_meeting_with_attendees)
    - [delete_attendee](#delete_attendee)
    - [delete_meeting](#delete_meeting)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_attendee](#get_attendee)
    - [get_meeting](#get_meeting)
    - [list_attendees](#list_attendees)
    - [start_meeting_transcription](#start_meeting_transcription)
    - [stop_meeting_transcription](#stop_meeting_transcription)

<a id="chimesdkmeetingsclient"></a>

## ChimeSDKMeetingsClient

Type annotations for `aiobotocore.create_client("chime-sdk-meetings")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_chime_sdk_meetings.client import ChimeSDKMeetingsClient

def get_chime-sdk-meetings_client() -> ChimeSDKMeetingsClient:
    return Session().client("chime-sdk-meetings")
```

Boto3 documentation:
[ChimeSDKMeetings.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_chime_sdk_meetings.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ForbiddenException`
- `Exceptions.LimitExceededException`
- `Exceptions.NotFoundException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.UnauthorizedException`
- `Exceptions.UnprocessableEntityException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ChimeSDKMeetingsClient exceptions.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").exceptions` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="batch_create_attendee"></a>

### batch_create_attendee

Creates up to 100 attendees for an active Amazon Chime SDK meeting.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").batch_create_attendee` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.batch_create_attendee](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.batch_create_attendee)

Asynchronous method. Use `await batch_create_attendee(...)` for a synchronous
call.

Arguments mapping described in
[BatchCreateAttendeeRequestRequestTypeDef](./type_defs.md#batchcreateattendeerequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*
- `Attendees`:
  `Sequence`\[[CreateAttendeeRequestItemTypeDef](./type_defs.md#createattendeerequestitemtypedef)\]
  *(required)*

Returns a `Coroutine` for
[BatchCreateAttendeeResponseTypeDef](./type_defs.md#batchcreateattendeeresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").can_paginate` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_attendee"></a>

### create_attendee

Creates a new attendee for an active Amazon Chime SDK meeting.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").create_attendee` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.create_attendee](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.create_attendee)

Asynchronous method. Use `await create_attendee(...)` for a synchronous call.

Arguments mapping described in
[CreateAttendeeRequestRequestTypeDef](./type_defs.md#createattendeerequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*
- `ExternalUserId`: `str` *(required)*

Returns a `Coroutine` for
[CreateAttendeeResponseTypeDef](./type_defs.md#createattendeeresponsetypedef).

<a id="create_meeting"></a>

### create_meeting

Creates a new Amazon Chime SDK meeting in the specified media Region with no
initial attendees.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").create_meeting` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.create_meeting](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.create_meeting)

Asynchronous method. Use `await create_meeting(...)` for a synchronous call.

Arguments mapping described in
[CreateMeetingRequestRequestTypeDef](./type_defs.md#createmeetingrequestrequesttypedef).

Keyword-only arguments:

- `ClientRequestToken`: `str` *(required)*
- `MediaRegion`: `str` *(required)*
- `ExternalMeetingId`: `str` *(required)*
- `MeetingHostId`: `str`
- `NotificationsConfiguration`:
  [NotificationsConfigurationTypeDef](./type_defs.md#notificationsconfigurationtypedef)
- `MeetingFeatures`:
  [MeetingFeaturesConfigurationTypeDef](./type_defs.md#meetingfeaturesconfigurationtypedef)

Returns a `Coroutine` for
[CreateMeetingResponseTypeDef](./type_defs.md#createmeetingresponsetypedef).

<a id="create_meeting_with_attendees"></a>

### create_meeting_with_attendees

Creates a new Amazon Chime SDK meeting in the specified media Region, with
attendees.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").create_meeting_with_attendees`
method.

Boto3 documentation:
[ChimeSDKMeetings.Client.create_meeting_with_attendees](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.create_meeting_with_attendees)

Asynchronous method. Use `await create_meeting_with_attendees(...)` for a
synchronous call.

Arguments mapping described in
[CreateMeetingWithAttendeesRequestRequestTypeDef](./type_defs.md#createmeetingwithattendeesrequestrequesttypedef).

Keyword-only arguments:

- `ClientRequestToken`: `str` *(required)*
- `MediaRegion`: `str` *(required)*
- `ExternalMeetingId`: `str` *(required)*
- `Attendees`:
  `Sequence`\[[CreateAttendeeRequestItemTypeDef](./type_defs.md#createattendeerequestitemtypedef)\]
  *(required)*
- `MeetingHostId`: `str`
- `MeetingFeatures`:
  [MeetingFeaturesConfigurationTypeDef](./type_defs.md#meetingfeaturesconfigurationtypedef)
- `NotificationsConfiguration`:
  [NotificationsConfigurationTypeDef](./type_defs.md#notificationsconfigurationtypedef)

Returns a `Coroutine` for
[CreateMeetingWithAttendeesResponseTypeDef](./type_defs.md#createmeetingwithattendeesresponsetypedef).

<a id="delete_attendee"></a>

### delete_attendee

Deletes an attendee from the specified Amazon Chime SDK meeting and deletes
their `JoinToken`.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").delete_attendee` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.delete_attendee](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.delete_attendee)

Asynchronous method. Use `await delete_attendee(...)` for a synchronous call.

Arguments mapping described in
[DeleteAttendeeRequestRequestTypeDef](./type_defs.md#deleteattendeerequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*
- `AttendeeId`: `str` *(required)*

<a id="delete_meeting"></a>

### delete_meeting

Deletes the specified Amazon Chime SDK meeting.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").delete_meeting` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.delete_meeting](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.delete_meeting)

Asynchronous method. Use `await delete_meeting(...)` for a synchronous call.

Arguments mapping described in
[DeleteMeetingRequestRequestTypeDef](./type_defs.md#deletemeetingrequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").generate_presigned_url`
method.

Boto3 documentation:
[ChimeSDKMeetings.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_attendee"></a>

### get_attendee

Gets the Amazon Chime SDK attendee details for a specified meeting ID and
attendee ID.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").get_attendee` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.get_attendee](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.get_attendee)

Asynchronous method. Use `await get_attendee(...)` for a synchronous call.

Arguments mapping described in
[GetAttendeeRequestRequestTypeDef](./type_defs.md#getattendeerequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*
- `AttendeeId`: `str` *(required)*

Returns a `Coroutine` for
[GetAttendeeResponseTypeDef](./type_defs.md#getattendeeresponsetypedef).

<a id="get_meeting"></a>

### get_meeting

Gets the Amazon Chime SDK meeting details for the specified meeting ID.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").get_meeting` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.get_meeting](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.get_meeting)

Asynchronous method. Use `await get_meeting(...)` for a synchronous call.

Arguments mapping described in
[GetMeetingRequestRequestTypeDef](./type_defs.md#getmeetingrequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*

Returns a `Coroutine` for
[GetMeetingResponseTypeDef](./type_defs.md#getmeetingresponsetypedef).

<a id="list_attendees"></a>

### list_attendees

Lists the attendees for the specified Amazon Chime SDK meeting.

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").list_attendees` method.

Boto3 documentation:
[ChimeSDKMeetings.Client.list_attendees](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.list_attendees)

Asynchronous method. Use `await list_attendees(...)` for a synchronous call.

Arguments mapping described in
[ListAttendeesRequestRequestTypeDef](./type_defs.md#listattendeesrequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListAttendeesResponseTypeDef](./type_defs.md#listattendeesresponsetypedef).

<a id="start_meeting_transcription"></a>

### start_meeting_transcription

Starts transcription for the specified `meetingId` .

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").start_meeting_transcription`
method.

Boto3 documentation:
[ChimeSDKMeetings.Client.start_meeting_transcription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.start_meeting_transcription)

Asynchronous method. Use `await start_meeting_transcription(...)` for a
synchronous call.

Arguments mapping described in
[StartMeetingTranscriptionRequestRequestTypeDef](./type_defs.md#startmeetingtranscriptionrequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*
- `TranscriptionConfiguration`:
  [TranscriptionConfigurationTypeDef](./type_defs.md#transcriptionconfigurationtypedef)
  *(required)*

<a id="stop_meeting_transcription"></a>

### stop_meeting_transcription

Stops transcription for the specified `meetingId` .

Type annotations for
`aiobotocore.create_client("chime-sdk-meetings").stop_meeting_transcription`
method.

Boto3 documentation:
[ChimeSDKMeetings.Client.stop_meeting_transcription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.stop_meeting_transcription)

Asynchronous method. Use `await stop_meeting_transcription(...)` for a
synchronous call.

Arguments mapping described in
[StopMeetingTranscriptionRequestRequestTypeDef](./type_defs.md#stopmeetingtranscriptionrequestrequesttypedef).

Keyword-only arguments:

- `MeetingId`: `str` *(required)*
