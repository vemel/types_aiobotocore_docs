<a id="type-annotations-for-aiobotocore-chimesdkmeetings-module"></a>

# Type annotations for aiobotocore ChimeSDKMeetings module

> [Index](..) > ChimeSDKMeetings

Auto-generated documentation for
[ChimeSDKMeetings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
type annotations stubs module
[types-aiobotocore-chime-sdk-meetings](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[chime-sdk-meetings]'

# install as a standalone
pip install types-aiobotocore-chime-sdk-meetings
```

- [Type annotations for aiobotocore ChimeSDKMeetings module](#type-annotations-for-aiobotocore-chimesdkmeetings-module)
  - [ChimeSDKMeetingsClient](#chimesdkmeetingsclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="chimesdkmeetingsclient"></a>

## ChimeSDKMeetingsClient

Type annotations for `aiobotocore.create_client("chime-sdk-meetings")` as
[ChimeSDKMeetingsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_chime_sdk_meetings.client import ChimeSDKMeetingsClient
```

<a id="methods"></a>

### Methods

- [batch_create_attendee](./client.md#batch_create_attendee)
- [can_paginate](./client.md#can_paginate)
- [create_attendee](./client.md#create_attendee)
- [create_meeting](./client.md#create_meeting)
- [create_meeting_with_attendees](./client.md#create_meeting_with_attendees)
- [delete_attendee](./client.md#delete_attendee)
- [delete_meeting](./client.md#delete_meeting)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_attendee](./client.md#get_attendee)
- [get_meeting](./client.md#get_meeting)
- [list_attendees](./client.md#list_attendees)
- [start_meeting_transcription](./client.md#start_meeting_transcription)
- [stop_meeting_transcription](./client.md#stop_meeting_transcription)

<a id="exceptions"></a>

### Exceptions

ChimeSDKMeetingsClient [exceptions](./client.md#exceptions)

- BadRequestException
- ClientError
- ForbiddenException
- LimitExceededException
- NotFoundException
- ServiceUnavailableException
- UnauthorizedException
- UnprocessableEntityException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_chime_sdk_meetings.literals import MeetingFeatureStatusType, ...
```

- [MeetingFeatureStatusType](./literals.md#meetingfeaturestatustype)
- [TranscribeContentIdentificationTypeType](./literals.md#transcribecontentidentificationtypetype)
- [TranscribeContentRedactionTypeType](./literals.md#transcribecontentredactiontypetype)
- [TranscribeLanguageCodeType](./literals.md#transcribelanguagecodetype)
- [TranscribeMedicalContentIdentificationTypeType](./literals.md#transcribemedicalcontentidentificationtypetype)
- [TranscribeMedicalLanguageCodeType](./literals.md#transcribemedicallanguagecodetype)
- [TranscribeMedicalRegionType](./literals.md#transcribemedicalregiontype)
- [TranscribeMedicalSpecialtyType](./literals.md#transcribemedicalspecialtytype)
- [TranscribeMedicalTypeType](./literals.md#transcribemedicaltypetype)
- [TranscribePartialResultsStabilityType](./literals.md#transcribepartialresultsstabilitytype)
- [TranscribeRegionType](./literals.md#transcriberegiontype)
- [TranscribeVocabularyFilterMethodType](./literals.md#transcribevocabularyfiltermethodtype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_chime_sdk_meetings.type_defs import AttendeeTypeDef, ...
```

- [AttendeeTypeDef](./type_defs.md#attendeetypedef)
- [AudioFeaturesTypeDef](./type_defs.md#audiofeaturestypedef)
- [BatchCreateAttendeeRequestRequestTypeDef](./type_defs.md#batchcreateattendeerequestrequesttypedef)
- [BatchCreateAttendeeResponseTypeDef](./type_defs.md#batchcreateattendeeresponsetypedef)
- [CreateAttendeeErrorTypeDef](./type_defs.md#createattendeeerrortypedef)
- [CreateAttendeeRequestItemTypeDef](./type_defs.md#createattendeerequestitemtypedef)
- [CreateAttendeeRequestRequestTypeDef](./type_defs.md#createattendeerequestrequesttypedef)
- [CreateAttendeeResponseTypeDef](./type_defs.md#createattendeeresponsetypedef)
- [CreateMeetingRequestRequestTypeDef](./type_defs.md#createmeetingrequestrequesttypedef)
- [CreateMeetingResponseTypeDef](./type_defs.md#createmeetingresponsetypedef)
- [CreateMeetingWithAttendeesRequestRequestTypeDef](./type_defs.md#createmeetingwithattendeesrequestrequesttypedef)
- [CreateMeetingWithAttendeesResponseTypeDef](./type_defs.md#createmeetingwithattendeesresponsetypedef)
- [DeleteAttendeeRequestRequestTypeDef](./type_defs.md#deleteattendeerequestrequesttypedef)
- [DeleteMeetingRequestRequestTypeDef](./type_defs.md#deletemeetingrequestrequesttypedef)
- [EngineTranscribeMedicalSettingsTypeDef](./type_defs.md#enginetranscribemedicalsettingstypedef)
- [EngineTranscribeSettingsTypeDef](./type_defs.md#enginetranscribesettingstypedef)
- [GetAttendeeRequestRequestTypeDef](./type_defs.md#getattendeerequestrequesttypedef)
- [GetAttendeeResponseTypeDef](./type_defs.md#getattendeeresponsetypedef)
- [GetMeetingRequestRequestTypeDef](./type_defs.md#getmeetingrequestrequesttypedef)
- [GetMeetingResponseTypeDef](./type_defs.md#getmeetingresponsetypedef)
- [ListAttendeesRequestRequestTypeDef](./type_defs.md#listattendeesrequestrequesttypedef)
- [ListAttendeesResponseTypeDef](./type_defs.md#listattendeesresponsetypedef)
- [MediaPlacementTypeDef](./type_defs.md#mediaplacementtypedef)
- [MeetingFeaturesConfigurationTypeDef](./type_defs.md#meetingfeaturesconfigurationtypedef)
- [MeetingTypeDef](./type_defs.md#meetingtypedef)
- [NotificationsConfigurationTypeDef](./type_defs.md#notificationsconfigurationtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartMeetingTranscriptionRequestRequestTypeDef](./type_defs.md#startmeetingtranscriptionrequestrequesttypedef)
- [StopMeetingTranscriptionRequestRequestTypeDef](./type_defs.md#stopmeetingtranscriptionrequestrequesttypedef)
- [TranscriptionConfigurationTypeDef](./type_defs.md#transcriptionconfigurationtypedef)
