<a id="transcribeserviceclient-for-aiobotocore-transcribeservice-module"></a>

# TranscribeServiceClient for aiobotocore TranscribeService module

> [Index](..) > [TranscribeService](.) > TranscribeServiceClient

Auto-generated documentation for
[TranscribeService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService)
type annotations stubs module
[types-aiobotocore-transcribe](https://pypi.org/project/types-aiobotocore-transcribe/).

- [TranscribeServiceClient for aiobotocore TranscribeService module](#transcribeserviceclient-for-aiobotocore-transcribeservice-module)
  - [TranscribeServiceClient](#transcribeserviceclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_call_analytics_category](#create_call_analytics_category)
    - [create_language_model](#create_language_model)
    - [create_medical_vocabulary](#create_medical_vocabulary)
    - [create_vocabulary](#create_vocabulary)
    - [create_vocabulary_filter](#create_vocabulary_filter)
    - [delete_call_analytics_category](#delete_call_analytics_category)
    - [delete_call_analytics_job](#delete_call_analytics_job)
    - [delete_language_model](#delete_language_model)
    - [delete_medical_transcription_job](#delete_medical_transcription_job)
    - [delete_medical_vocabulary](#delete_medical_vocabulary)
    - [delete_transcription_job](#delete_transcription_job)
    - [delete_vocabulary](#delete_vocabulary)
    - [delete_vocabulary_filter](#delete_vocabulary_filter)
    - [describe_language_model](#describe_language_model)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_call_analytics_category](#get_call_analytics_category)
    - [get_call_analytics_job](#get_call_analytics_job)
    - [get_medical_transcription_job](#get_medical_transcription_job)
    - [get_medical_vocabulary](#get_medical_vocabulary)
    - [get_transcription_job](#get_transcription_job)
    - [get_vocabulary](#get_vocabulary)
    - [get_vocabulary_filter](#get_vocabulary_filter)
    - [list_call_analytics_categories](#list_call_analytics_categories)
    - [list_call_analytics_jobs](#list_call_analytics_jobs)
    - [list_language_models](#list_language_models)
    - [list_medical_transcription_jobs](#list_medical_transcription_jobs)
    - [list_medical_vocabularies](#list_medical_vocabularies)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_transcription_jobs](#list_transcription_jobs)
    - [list_vocabularies](#list_vocabularies)
    - [list_vocabulary_filters](#list_vocabulary_filters)
    - [start_call_analytics_job](#start_call_analytics_job)
    - [start_medical_transcription_job](#start_medical_transcription_job)
    - [start_transcription_job](#start_transcription_job)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_call_analytics_category](#update_call_analytics_category)
    - [update_medical_vocabulary](#update_medical_vocabulary)
    - [update_vocabulary](#update_vocabulary)
    - [update_vocabulary_filter](#update_vocabulary_filter)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)

<a id="transcribeserviceclient"></a>

## TranscribeServiceClient

Type annotations for `session.create_client("transcribe")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_transcribe.client import TranscribeServiceClient

session = get_session()
async with session.create_client("transcribe") as client:
    client: TranscribeServiceClient
```

Boto3 documentation:
[TranscribeService.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_transcribe.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalFailureException`
- `Exceptions.LimitExceededException`
- `Exceptions.NotFoundException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

TranscribeServiceClient exceptions.

Type annotations for `session.create_client("transcribe").exceptions` method.

Boto3 documentation:
[TranscribeService.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("transcribe").can_paginate` method.

Boto3 documentation:
[TranscribeService.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_call_analytics_category"></a>

### create_call_analytics_category

Creates an analytics category.

Type annotations for
`session.create_client("transcribe").create_call_analytics_category` method.

Boto3 documentation:
[TranscribeService.Client.create_call_analytics_category](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_call_analytics_category)

Asynchronous method. Use `await create_call_analytics_category(...)` for a
synchronous call.

Arguments mapping described in
[CreateCallAnalyticsCategoryRequestRequestTypeDef](./type_defs.md#createcallanalyticscategoryrequestrequesttypedef).

Keyword-only arguments:

- `CategoryName`: `str` *(required)*
- `Rules`: `Sequence`\[[RuleTypeDef](./type_defs.md#ruletypedef)\] *(required)*

Returns a `Coroutine` for
[CreateCallAnalyticsCategoryResponseTypeDef](./type_defs.md#createcallanalyticscategoryresponsetypedef).

<a id="create_language_model"></a>

### create_language_model

Creates a new custom language model.

Type annotations for
`session.create_client("transcribe").create_language_model` method.

Boto3 documentation:
[TranscribeService.Client.create_language_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_language_model)

Asynchronous method. Use `await create_language_model(...)` for a synchronous
call.

Arguments mapping described in
[CreateLanguageModelRequestRequestTypeDef](./type_defs.md#createlanguagemodelrequestrequesttypedef).

Keyword-only arguments:

- `LanguageCode`: [CLMLanguageCodeType](./literals.md#clmlanguagecodetype)
  *(required)*
- `BaseModelName`: [BaseModelNameType](./literals.md#basemodelnametype)
  *(required)*
- `ModelName`: `str` *(required)*
- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef) *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateLanguageModelResponseTypeDef](./type_defs.md#createlanguagemodelresponsetypedef).

<a id="create_medical_vocabulary"></a>

### create_medical_vocabulary

Creates a new custom vocabulary that you can use to modify how Amazon
Transcribe Medical transcribes your audio file.

Type annotations for
`session.create_client("transcribe").create_medical_vocabulary` method.

Boto3 documentation:
[TranscribeService.Client.create_medical_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_medical_vocabulary)

Asynchronous method. Use `await create_medical_vocabulary(...)` for a
synchronous call.

Arguments mapping described in
[CreateMedicalVocabularyRequestRequestTypeDef](./type_defs.md#createmedicalvocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*
- `LanguageCode`: [LanguageCodeType](./literals.md#languagecodetype)
  *(required)*
- `VocabularyFileUri`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateMedicalVocabularyResponseTypeDef](./type_defs.md#createmedicalvocabularyresponsetypedef).

<a id="create_vocabulary"></a>

### create_vocabulary

Creates a new custom vocabulary that you can use to change the way Amazon
Transcribe handles transcription of an audio file.

Type annotations for `session.create_client("transcribe").create_vocabulary`
method.

Boto3 documentation:
[TranscribeService.Client.create_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_vocabulary)

Asynchronous method. Use `await create_vocabulary(...)` for a synchronous call.

Arguments mapping described in
[CreateVocabularyRequestRequestTypeDef](./type_defs.md#createvocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*
- `LanguageCode`: [LanguageCodeType](./literals.md#languagecodetype)
  *(required)*
- `Phrases`: `Sequence`\[`str`\]
- `VocabularyFileUri`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateVocabularyResponseTypeDef](./type_defs.md#createvocabularyresponsetypedef).

<a id="create_vocabulary_filter"></a>

### create_vocabulary_filter

Creates a new vocabulary filter that you can use to filter words, such as
profane words, from the output of a transcription job.

Type annotations for
`session.create_client("transcribe").create_vocabulary_filter` method.

Boto3 documentation:
[TranscribeService.Client.create_vocabulary_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_vocabulary_filter)

Asynchronous method. Use `await create_vocabulary_filter(...)` for a
synchronous call.

Arguments mapping described in
[CreateVocabularyFilterRequestRequestTypeDef](./type_defs.md#createvocabularyfilterrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyFilterName`: `str` *(required)*
- `LanguageCode`: [LanguageCodeType](./literals.md#languagecodetype)
  *(required)*
- `Words`: `Sequence`\[`str`\]
- `VocabularyFilterFileUri`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateVocabularyFilterResponseTypeDef](./type_defs.md#createvocabularyfilterresponsetypedef).

<a id="delete_call_analytics_category"></a>

### delete_call_analytics_category

Deletes a call analytics category using its name.

Type annotations for
`session.create_client("transcribe").delete_call_analytics_category` method.

Boto3 documentation:
[TranscribeService.Client.delete_call_analytics_category](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_call_analytics_category)

Asynchronous method. Use `await delete_call_analytics_category(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCallAnalyticsCategoryRequestRequestTypeDef](./type_defs.md#deletecallanalyticscategoryrequestrequesttypedef).

Keyword-only arguments:

- `CategoryName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_call_analytics_job"></a>

### delete_call_analytics_job

Deletes a call analytics job using its name.

Type annotations for
`session.create_client("transcribe").delete_call_analytics_job` method.

Boto3 documentation:
[TranscribeService.Client.delete_call_analytics_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_call_analytics_job)

Asynchronous method. Use `await delete_call_analytics_job(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCallAnalyticsJobRequestRequestTypeDef](./type_defs.md#deletecallanalyticsjobrequestrequesttypedef).

Keyword-only arguments:

- `CallAnalyticsJobName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_language_model"></a>

### delete_language_model

Deletes a custom language model using its name.

Type annotations for
`session.create_client("transcribe").delete_language_model` method.

Boto3 documentation:
[TranscribeService.Client.delete_language_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_language_model)

Asynchronous method. Use `await delete_language_model(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLanguageModelRequestRequestTypeDef](./type_defs.md#deletelanguagemodelrequestrequesttypedef).

Keyword-only arguments:

- `ModelName`: `str` *(required)*

<a id="delete_medical_transcription_job"></a>

### delete_medical_transcription_job

Deletes a transcription job generated by Amazon Transcribe Medical and any
related information.

Type annotations for
`session.create_client("transcribe").delete_medical_transcription_job` method.

Boto3 documentation:
[TranscribeService.Client.delete_medical_transcription_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_medical_transcription_job)

Asynchronous method. Use `await delete_medical_transcription_job(...)` for a
synchronous call.

Arguments mapping described in
[DeleteMedicalTranscriptionJobRequestRequestTypeDef](./type_defs.md#deletemedicaltranscriptionjobrequestrequesttypedef).

Keyword-only arguments:

- `MedicalTranscriptionJobName`: `str` *(required)*

<a id="delete_medical_vocabulary"></a>

### delete_medical_vocabulary

Deletes a vocabulary from Amazon Transcribe Medical.

Type annotations for
`session.create_client("transcribe").delete_medical_vocabulary` method.

Boto3 documentation:
[TranscribeService.Client.delete_medical_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_medical_vocabulary)

Asynchronous method. Use `await delete_medical_vocabulary(...)` for a
synchronous call.

Arguments mapping described in
[DeleteMedicalVocabularyRequestRequestTypeDef](./type_defs.md#deletemedicalvocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*

<a id="delete_transcription_job"></a>

### delete_transcription_job

Deletes a previously submitted transcription job along with any other generated
results such as the transcription, models, and so on.

Type annotations for
`session.create_client("transcribe").delete_transcription_job` method.

Boto3 documentation:
[TranscribeService.Client.delete_transcription_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_transcription_job)

Asynchronous method. Use `await delete_transcription_job(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTranscriptionJobRequestRequestTypeDef](./type_defs.md#deletetranscriptionjobrequestrequesttypedef).

Keyword-only arguments:

- `TranscriptionJobName`: `str` *(required)*

<a id="delete_vocabulary"></a>

### delete_vocabulary

Deletes a vocabulary from Amazon Transcribe.

Type annotations for `session.create_client("transcribe").delete_vocabulary`
method.

Boto3 documentation:
[TranscribeService.Client.delete_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_vocabulary)

Asynchronous method. Use `await delete_vocabulary(...)` for a synchronous call.

Arguments mapping described in
[DeleteVocabularyRequestRequestTypeDef](./type_defs.md#deletevocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*

<a id="delete_vocabulary_filter"></a>

### delete_vocabulary_filter

Removes a vocabulary filter.

Type annotations for
`session.create_client("transcribe").delete_vocabulary_filter` method.

Boto3 documentation:
[TranscribeService.Client.delete_vocabulary_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.delete_vocabulary_filter)

Asynchronous method. Use `await delete_vocabulary_filter(...)` for a
synchronous call.

Arguments mapping described in
[DeleteVocabularyFilterRequestRequestTypeDef](./type_defs.md#deletevocabularyfilterrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyFilterName`: `str` *(required)*

<a id="describe_language_model"></a>

### describe_language_model

Gets information about a single custom language model.

Type annotations for
`session.create_client("transcribe").describe_language_model` method.

Boto3 documentation:
[TranscribeService.Client.describe_language_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.describe_language_model)

Asynchronous method. Use `await describe_language_model(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLanguageModelRequestRequestTypeDef](./type_defs.md#describelanguagemodelrequestrequesttypedef).

Keyword-only arguments:

- `ModelName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLanguageModelResponseTypeDef](./type_defs.md#describelanguagemodelresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("transcribe").generate_presigned_url` method.

Boto3 documentation:
[TranscribeService.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_call_analytics_category"></a>

### get_call_analytics_category

Retrieves information about a call analytics category.

Type annotations for
`session.create_client("transcribe").get_call_analytics_category` method.

Boto3 documentation:
[TranscribeService.Client.get_call_analytics_category](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.get_call_analytics_category)

Asynchronous method. Use `await get_call_analytics_category(...)` for a
synchronous call.

Arguments mapping described in
[GetCallAnalyticsCategoryRequestRequestTypeDef](./type_defs.md#getcallanalyticscategoryrequestrequesttypedef).

Keyword-only arguments:

- `CategoryName`: `str` *(required)*

Returns a `Coroutine` for
[GetCallAnalyticsCategoryResponseTypeDef](./type_defs.md#getcallanalyticscategoryresponsetypedef).

<a id="get_call_analytics_job"></a>

### get_call_analytics_job

Returns information about a call analytics job.

Type annotations for
`session.create_client("transcribe").get_call_analytics_job` method.

Boto3 documentation:
[TranscribeService.Client.get_call_analytics_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.get_call_analytics_job)

Asynchronous method. Use `await get_call_analytics_job(...)` for a synchronous
call.

Arguments mapping described in
[GetCallAnalyticsJobRequestRequestTypeDef](./type_defs.md#getcallanalyticsjobrequestrequesttypedef).

Keyword-only arguments:

- `CallAnalyticsJobName`: `str` *(required)*

Returns a `Coroutine` for
[GetCallAnalyticsJobResponseTypeDef](./type_defs.md#getcallanalyticsjobresponsetypedef).

<a id="get_medical_transcription_job"></a>

### get_medical_transcription_job

Returns information about a transcription job from Amazon Transcribe Medical.

Type annotations for
`session.create_client("transcribe").get_medical_transcription_job` method.

Boto3 documentation:
[TranscribeService.Client.get_medical_transcription_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.get_medical_transcription_job)

Asynchronous method. Use `await get_medical_transcription_job(...)` for a
synchronous call.

Arguments mapping described in
[GetMedicalTranscriptionJobRequestRequestTypeDef](./type_defs.md#getmedicaltranscriptionjobrequestrequesttypedef).

Keyword-only arguments:

- `MedicalTranscriptionJobName`: `str` *(required)*

Returns a `Coroutine` for
[GetMedicalTranscriptionJobResponseTypeDef](./type_defs.md#getmedicaltranscriptionjobresponsetypedef).

<a id="get_medical_vocabulary"></a>

### get_medical_vocabulary

Retrieves information about a medical vocabulary.

Type annotations for
`session.create_client("transcribe").get_medical_vocabulary` method.

Boto3 documentation:
[TranscribeService.Client.get_medical_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.get_medical_vocabulary)

Asynchronous method. Use `await get_medical_vocabulary(...)` for a synchronous
call.

Arguments mapping described in
[GetMedicalVocabularyRequestRequestTypeDef](./type_defs.md#getmedicalvocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*

Returns a `Coroutine` for
[GetMedicalVocabularyResponseTypeDef](./type_defs.md#getmedicalvocabularyresponsetypedef).

<a id="get_transcription_job"></a>

### get_transcription_job

Returns information about a transcription job.

Type annotations for
`session.create_client("transcribe").get_transcription_job` method.

Boto3 documentation:
[TranscribeService.Client.get_transcription_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.get_transcription_job)

Asynchronous method. Use `await get_transcription_job(...)` for a synchronous
call.

Arguments mapping described in
[GetTranscriptionJobRequestRequestTypeDef](./type_defs.md#gettranscriptionjobrequestrequesttypedef).

Keyword-only arguments:

- `TranscriptionJobName`: `str` *(required)*

Returns a `Coroutine` for
[GetTranscriptionJobResponseTypeDef](./type_defs.md#gettranscriptionjobresponsetypedef).

<a id="get_vocabulary"></a>

### get_vocabulary

Gets information about a vocabulary.

Type annotations for `session.create_client("transcribe").get_vocabulary`
method.

Boto3 documentation:
[TranscribeService.Client.get_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.get_vocabulary)

Asynchronous method. Use `await get_vocabulary(...)` for a synchronous call.

Arguments mapping described in
[GetVocabularyRequestRequestTypeDef](./type_defs.md#getvocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*

Returns a `Coroutine` for
[GetVocabularyResponseTypeDef](./type_defs.md#getvocabularyresponsetypedef).

<a id="get_vocabulary_filter"></a>

### get_vocabulary_filter

Returns information about a vocabulary filter.

Type annotations for
`session.create_client("transcribe").get_vocabulary_filter` method.

Boto3 documentation:
[TranscribeService.Client.get_vocabulary_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.get_vocabulary_filter)

Asynchronous method. Use `await get_vocabulary_filter(...)` for a synchronous
call.

Arguments mapping described in
[GetVocabularyFilterRequestRequestTypeDef](./type_defs.md#getvocabularyfilterrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyFilterName`: `str` *(required)*

Returns a `Coroutine` for
[GetVocabularyFilterResponseTypeDef](./type_defs.md#getvocabularyfilterresponsetypedef).

<a id="list_call_analytics_categories"></a>

### list_call_analytics_categories

Provides more information about the call analytics categories that you've
created.

Type annotations for
`session.create_client("transcribe").list_call_analytics_categories` method.

Boto3 documentation:
[TranscribeService.Client.list_call_analytics_categories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_call_analytics_categories)

Asynchronous method. Use `await list_call_analytics_categories(...)` for a
synchronous call.

Arguments mapping described in
[ListCallAnalyticsCategoriesRequestRequestTypeDef](./type_defs.md#listcallanalyticscategoriesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListCallAnalyticsCategoriesResponseTypeDef](./type_defs.md#listcallanalyticscategoriesresponsetypedef).

<a id="list_call_analytics_jobs"></a>

### list_call_analytics_jobs

List call analytics jobs with a specified status or substring that matches
their names.

Type annotations for
`session.create_client("transcribe").list_call_analytics_jobs` method.

Boto3 documentation:
[TranscribeService.Client.list_call_analytics_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_call_analytics_jobs)

Asynchronous method. Use `await list_call_analytics_jobs(...)` for a
synchronous call.

Arguments mapping described in
[ListCallAnalyticsJobsRequestRequestTypeDef](./type_defs.md#listcallanalyticsjobsrequestrequesttypedef).

Keyword-only arguments:

- `Status`:
  [CallAnalyticsJobStatusType](./literals.md#callanalyticsjobstatustype)
- `JobNameContains`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListCallAnalyticsJobsResponseTypeDef](./type_defs.md#listcallanalyticsjobsresponsetypedef).

<a id="list_language_models"></a>

### list_language_models

Provides more information about the custom language models you've created.

Type annotations for `session.create_client("transcribe").list_language_models`
method.

Boto3 documentation:
[TranscribeService.Client.list_language_models](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_language_models)

Asynchronous method. Use `await list_language_models(...)` for a synchronous
call.

Arguments mapping described in
[ListLanguageModelsRequestRequestTypeDef](./type_defs.md#listlanguagemodelsrequestrequesttypedef).

Keyword-only arguments:

- `StatusEquals`: [ModelStatusType](./literals.md#modelstatustype)
- `NameContains`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListLanguageModelsResponseTypeDef](./type_defs.md#listlanguagemodelsresponsetypedef).

<a id="list_medical_transcription_jobs"></a>

### list_medical_transcription_jobs

Lists medical transcription jobs with a specified status or substring that
matches their names.

Type annotations for
`session.create_client("transcribe").list_medical_transcription_jobs` method.

Boto3 documentation:
[TranscribeService.Client.list_medical_transcription_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_medical_transcription_jobs)

Asynchronous method. Use `await list_medical_transcription_jobs(...)` for a
synchronous call.

Arguments mapping described in
[ListMedicalTranscriptionJobsRequestRequestTypeDef](./type_defs.md#listmedicaltranscriptionjobsrequestrequesttypedef).

Keyword-only arguments:

- `Status`:
  [TranscriptionJobStatusType](./literals.md#transcriptionjobstatustype)
- `JobNameContains`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListMedicalTranscriptionJobsResponseTypeDef](./type_defs.md#listmedicaltranscriptionjobsresponsetypedef).

<a id="list_medical_vocabularies"></a>

### list_medical_vocabularies

Returns a list of vocabularies that match the specified criteria.

Type annotations for
`session.create_client("transcribe").list_medical_vocabularies` method.

Boto3 documentation:
[TranscribeService.Client.list_medical_vocabularies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_medical_vocabularies)

Asynchronous method. Use `await list_medical_vocabularies(...)` for a
synchronous call.

Arguments mapping described in
[ListMedicalVocabulariesRequestRequestTypeDef](./type_defs.md#listmedicalvocabulariesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `StateEquals`: [VocabularyStateType](./literals.md#vocabularystatetype)
- `NameContains`: `str`

Returns a `Coroutine` for
[ListMedicalVocabulariesResponseTypeDef](./type_defs.md#listmedicalvocabulariesresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists all tags associated with a given transcription job, vocabulary, or
resource.

Type annotations for
`session.create_client("transcribe").list_tags_for_resource` method.

Boto3 documentation:
[TranscribeService.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list_transcription_jobs"></a>

### list_transcription_jobs

Lists transcription jobs with the specified status.

Type annotations for
`session.create_client("transcribe").list_transcription_jobs` method.

Boto3 documentation:
[TranscribeService.Client.list_transcription_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_transcription_jobs)

Asynchronous method. Use `await list_transcription_jobs(...)` for a synchronous
call.

Arguments mapping described in
[ListTranscriptionJobsRequestRequestTypeDef](./type_defs.md#listtranscriptionjobsrequestrequesttypedef).

Keyword-only arguments:

- `Status`:
  [TranscriptionJobStatusType](./literals.md#transcriptionjobstatustype)
- `JobNameContains`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListTranscriptionJobsResponseTypeDef](./type_defs.md#listtranscriptionjobsresponsetypedef).

<a id="list_vocabularies"></a>

### list_vocabularies

Returns a list of vocabularies that match the specified criteria.

Type annotations for `session.create_client("transcribe").list_vocabularies`
method.

Boto3 documentation:
[TranscribeService.Client.list_vocabularies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_vocabularies)

Asynchronous method. Use `await list_vocabularies(...)` for a synchronous call.

Arguments mapping described in
[ListVocabulariesRequestRequestTypeDef](./type_defs.md#listvocabulariesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `StateEquals`: [VocabularyStateType](./literals.md#vocabularystatetype)
- `NameContains`: `str`

Returns a `Coroutine` for
[ListVocabulariesResponseTypeDef](./type_defs.md#listvocabulariesresponsetypedef).

<a id="list_vocabulary_filters"></a>

### list_vocabulary_filters

Gets information about vocabulary filters.

Type annotations for
`session.create_client("transcribe").list_vocabulary_filters` method.

Boto3 documentation:
[TranscribeService.Client.list_vocabulary_filters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.list_vocabulary_filters)

Asynchronous method. Use `await list_vocabulary_filters(...)` for a synchronous
call.

Arguments mapping described in
[ListVocabularyFiltersRequestRequestTypeDef](./type_defs.md#listvocabularyfiltersrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`

Returns a `Coroutine` for
[ListVocabularyFiltersResponseTypeDef](./type_defs.md#listvocabularyfiltersresponsetypedef).

<a id="start_call_analytics_job"></a>

### start_call_analytics_job

Starts an asynchronous analytics job that not only transcribes the audio
recording of a caller and agent, but also returns additional insights.

Type annotations for
`session.create_client("transcribe").start_call_analytics_job` method.

Boto3 documentation:
[TranscribeService.Client.start_call_analytics_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.start_call_analytics_job)

Asynchronous method. Use `await start_call_analytics_job(...)` for a
synchronous call.

Arguments mapping described in
[StartCallAnalyticsJobRequestRequestTypeDef](./type_defs.md#startcallanalyticsjobrequestrequesttypedef).

Keyword-only arguments:

- `CallAnalyticsJobName`: `str` *(required)*
- `Media`: [MediaTypeDef](./type_defs.md#mediatypedef) *(required)*
- `DataAccessRoleArn`: `str` *(required)*
- `OutputLocation`: `str`
- `OutputEncryptionKMSKeyId`: `str`
- `Settings`:
  [CallAnalyticsJobSettingsTypeDef](./type_defs.md#callanalyticsjobsettingstypedef)
- `ChannelDefinitions`:
  `Sequence`\[[ChannelDefinitionTypeDef](./type_defs.md#channeldefinitiontypedef)\]

Returns a `Coroutine` for
[StartCallAnalyticsJobResponseTypeDef](./type_defs.md#startcallanalyticsjobresponsetypedef).

<a id="start_medical_transcription_job"></a>

### start_medical_transcription_job

Starts a batch job to transcribe medical speech to text.

Type annotations for
`session.create_client("transcribe").start_medical_transcription_job` method.

Boto3 documentation:
[TranscribeService.Client.start_medical_transcription_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.start_medical_transcription_job)

Asynchronous method. Use `await start_medical_transcription_job(...)` for a
synchronous call.

Arguments mapping described in
[StartMedicalTranscriptionJobRequestRequestTypeDef](./type_defs.md#startmedicaltranscriptionjobrequestrequesttypedef).

Keyword-only arguments:

- `MedicalTranscriptionJobName`: `str` *(required)*
- `LanguageCode`: [LanguageCodeType](./literals.md#languagecodetype)
  *(required)*
- `Media`: [MediaTypeDef](./type_defs.md#mediatypedef) *(required)*
- `OutputBucketName`: `str` *(required)*
- `Specialty`: `Literal['PRIMARYCARE']` (see
  [SpecialtyType](./literals.md#specialtytype)) *(required)*
- `Type`: [TypeType](./literals.md#typetype) *(required)*
- `MediaSampleRateHertz`: `int`
- `MediaFormat`: [MediaFormatType](./literals.md#mediaformattype)
- `OutputKey`: `str`
- `OutputEncryptionKMSKeyId`: `str`
- `KMSEncryptionContext`: `Mapping`\[`str`, `str`\]
- `Settings`:
  [MedicalTranscriptionSettingTypeDef](./type_defs.md#medicaltranscriptionsettingtypedef)
- `ContentIdentificationType`: `Literal['PHI']` (see
  [MedicalContentIdentificationTypeType](./literals.md#medicalcontentidentificationtypetype))
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[StartMedicalTranscriptionJobResponseTypeDef](./type_defs.md#startmedicaltranscriptionjobresponsetypedef).

<a id="start_transcription_job"></a>

### start_transcription_job

Starts an asynchronous job to transcribe speech to text.

Type annotations for
`session.create_client("transcribe").start_transcription_job` method.

Boto3 documentation:
[TranscribeService.Client.start_transcription_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.start_transcription_job)

Asynchronous method. Use `await start_transcription_job(...)` for a synchronous
call.

Arguments mapping described in
[StartTranscriptionJobRequestRequestTypeDef](./type_defs.md#starttranscriptionjobrequestrequesttypedef).

Keyword-only arguments:

- `TranscriptionJobName`: `str` *(required)*
- `Media`: [MediaTypeDef](./type_defs.md#mediatypedef) *(required)*
- `LanguageCode`: [LanguageCodeType](./literals.md#languagecodetype)
- `MediaSampleRateHertz`: `int`
- `MediaFormat`: [MediaFormatType](./literals.md#mediaformattype)
- `OutputBucketName`: `str`
- `OutputKey`: `str`
- `OutputEncryptionKMSKeyId`: `str`
- `KMSEncryptionContext`: `Mapping`\[`str`, `str`\]
- `Settings`: [SettingsTypeDef](./type_defs.md#settingstypedef)
- `ModelSettings`: [ModelSettingsTypeDef](./type_defs.md#modelsettingstypedef)
- `JobExecutionSettings`:
  [JobExecutionSettingsTypeDef](./type_defs.md#jobexecutionsettingstypedef)
- `ContentRedaction`:
  [ContentRedactionTypeDef](./type_defs.md#contentredactiontypedef)
- `IdentifyLanguage`: `bool`
- `LanguageOptions`:
  `Sequence`\[[LanguageCodeType](./literals.md#languagecodetype)\]
- `Subtitles`: [SubtitlesTypeDef](./type_defs.md#subtitlestypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `LanguageIdSettings`:
  `Mapping`\[[LanguageCodeType](./literals.md#languagecodetype),
  [LanguageIdSettingsTypeDef](./type_defs.md#languageidsettingstypedef)\]

Returns a `Coroutine` for
[StartTranscriptionJobResponseTypeDef](./type_defs.md#starttranscriptionjobresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Tags an Amazon Transcribe resource with the given list of tags.

Type annotations for `session.create_client("transcribe").tag_resource` method.

Boto3 documentation:
[TranscribeService.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes specified tags from a specified Amazon Transcribe resource.

Type annotations for `session.create_client("transcribe").untag_resource`
method.

Boto3 documentation:
[TranscribeService.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_call_analytics_category"></a>

### update_call_analytics_category

Updates the call analytics category with new values.

Type annotations for
`session.create_client("transcribe").update_call_analytics_category` method.

Boto3 documentation:
[TranscribeService.Client.update_call_analytics_category](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_call_analytics_category)

Asynchronous method. Use `await update_call_analytics_category(...)` for a
synchronous call.

Arguments mapping described in
[UpdateCallAnalyticsCategoryRequestRequestTypeDef](./type_defs.md#updatecallanalyticscategoryrequestrequesttypedef).

Keyword-only arguments:

- `CategoryName`: `str` *(required)*
- `Rules`: `Sequence`\[[RuleTypeDef](./type_defs.md#ruletypedef)\] *(required)*

Returns a `Coroutine` for
[UpdateCallAnalyticsCategoryResponseTypeDef](./type_defs.md#updatecallanalyticscategoryresponsetypedef).

<a id="update_medical_vocabulary"></a>

### update_medical_vocabulary

Updates a vocabulary with new values that you provide in a different text file
from the one you used to create the vocabulary.

Type annotations for
`session.create_client("transcribe").update_medical_vocabulary` method.

Boto3 documentation:
[TranscribeService.Client.update_medical_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_medical_vocabulary)

Asynchronous method. Use `await update_medical_vocabulary(...)` for a
synchronous call.

Arguments mapping described in
[UpdateMedicalVocabularyRequestRequestTypeDef](./type_defs.md#updatemedicalvocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*
- `LanguageCode`: [LanguageCodeType](./literals.md#languagecodetype)
  *(required)*
- `VocabularyFileUri`: `str`

Returns a `Coroutine` for
[UpdateMedicalVocabularyResponseTypeDef](./type_defs.md#updatemedicalvocabularyresponsetypedef).

<a id="update_vocabulary"></a>

### update_vocabulary

Updates an existing vocabulary with new values.

Type annotations for `session.create_client("transcribe").update_vocabulary`
method.

Boto3 documentation:
[TranscribeService.Client.update_vocabulary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_vocabulary)

Asynchronous method. Use `await update_vocabulary(...)` for a synchronous call.

Arguments mapping described in
[UpdateVocabularyRequestRequestTypeDef](./type_defs.md#updatevocabularyrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyName`: `str` *(required)*
- `LanguageCode`: [LanguageCodeType](./literals.md#languagecodetype)
  *(required)*
- `Phrases`: `Sequence`\[`str`\]
- `VocabularyFileUri`: `str`

Returns a `Coroutine` for
[UpdateVocabularyResponseTypeDef](./type_defs.md#updatevocabularyresponsetypedef).

<a id="update_vocabulary_filter"></a>

### update_vocabulary_filter

Updates a vocabulary filter with a new list of filtered words.

Type annotations for
`session.create_client("transcribe").update_vocabulary_filter` method.

Boto3 documentation:
[TranscribeService.Client.update_vocabulary_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_vocabulary_filter)

Asynchronous method. Use `await update_vocabulary_filter(...)` for a
synchronous call.

Arguments mapping described in
[UpdateVocabularyFilterRequestRequestTypeDef](./type_defs.md#updatevocabularyfilterrequestrequesttypedef).

Keyword-only arguments:

- `VocabularyFilterName`: `str` *(required)*
- `Words`: `Sequence`\[`str`\]
- `VocabularyFilterFileUri`: `str`

Returns a `Coroutine` for
[UpdateVocabularyFilterResponseTypeDef](./type_defs.md#updatevocabularyfilterresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("transcribe").__aenter__` method.

Boto3 documentation:
[TranscribeService.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [TranscribeServiceClient](#transcribeserviceclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("transcribe").__aexit__` method.

Boto3 documentation:
[TranscribeService.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
