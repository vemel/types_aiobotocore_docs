<a id="type-annotations-for-aiobotocore-translate-module"></a>

# Type annotations for aiobotocore Translate module

> [Index](..) > Translate

Auto-generated documentation for
[Translate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate)
type annotations stubs module
[types-aiobotocore-translate](https://pypi.org/project/types-aiobotocore-translate/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[translate]'

# install as a standalone
pip install types-aiobotocore-translate
```

- [Type annotations for aiobotocore Translate module](#type-annotations-for-aiobotocore-translate-module)
  - [TranslateClient](#translateclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="translateclient"></a>

## TranslateClient

Type annotations for `aiobotocore.create_client("translate")` as
[TranslateClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_translate.client import TranslateClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_parallel_data](./client.md#create_parallel_data)
- [delete_parallel_data](./client.md#delete_parallel_data)
- [delete_terminology](./client.md#delete_terminology)
- [describe_text_translation_job](./client.md#describe_text_translation_job)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_parallel_data](./client.md#get_parallel_data)
- [get_terminology](./client.md#get_terminology)
- [import_terminology](./client.md#import_terminology)
- [list_parallel_data](./client.md#list_parallel_data)
- [list_terminologies](./client.md#list_terminologies)
- [list_text_translation_jobs](./client.md#list_text_translation_jobs)
- [start_text_translation_job](./client.md#start_text_translation_job)
- [stop_text_translation_job](./client.md#stop_text_translation_job)
- [translate_text](./client.md#translate_text)
- [update_parallel_data](./client.md#update_parallel_data)

<a id="exceptions"></a>

### Exceptions

TranslateClient [exceptions](./client.md#exceptions)

- ClientError
- ConcurrentModificationException
- ConflictException
- DetectedLanguageLowConfidenceException
- InternalServerException
- InvalidFilterException
- InvalidParameterValueException
- InvalidRequestException
- LimitExceededException
- ResourceNotFoundException
- ServiceUnavailableException
- TextSizeLimitExceededException
- TooManyRequestsException
- UnsupportedLanguagePairException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("translate").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_translate.paginators import ListTerminologiesPaginator, ...
```

- [ListTerminologiesPaginator](./paginators.md#listterminologiespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_translate.literals import DirectionalityType, ...
```

- [DirectionalityType](./literals.md#directionalitytype)
- [EncryptionKeyTypeType](./literals.md#encryptionkeytypetype)
- [JobStatusType](./literals.md#jobstatustype)
- [ListTerminologiesPaginatorName](./literals.md#listterminologiespaginatorname)
- [MergeStrategyType](./literals.md#mergestrategytype)
- [ParallelDataFormatType](./literals.md#paralleldataformattype)
- [ParallelDataStatusType](./literals.md#paralleldatastatustype)
- [ProfanityType](./literals.md#profanitytype)
- [TerminologyDataFormatType](./literals.md#terminologydataformattype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_translate.type_defs import AppliedTerminologyTypeDef, ...
```

- [AppliedTerminologyTypeDef](./type_defs.md#appliedterminologytypedef)
- [CreateParallelDataRequestRequestTypeDef](./type_defs.md#createparalleldatarequestrequesttypedef)
- [CreateParallelDataResponseTypeDef](./type_defs.md#createparalleldataresponsetypedef)
- [DeleteParallelDataRequestRequestTypeDef](./type_defs.md#deleteparalleldatarequestrequesttypedef)
- [DeleteParallelDataResponseTypeDef](./type_defs.md#deleteparalleldataresponsetypedef)
- [DeleteTerminologyRequestRequestTypeDef](./type_defs.md#deleteterminologyrequestrequesttypedef)
- [DescribeTextTranslationJobRequestRequestTypeDef](./type_defs.md#describetexttranslationjobrequestrequesttypedef)
- [DescribeTextTranslationJobResponseTypeDef](./type_defs.md#describetexttranslationjobresponsetypedef)
- [EncryptionKeyTypeDef](./type_defs.md#encryptionkeytypedef)
- [GetParallelDataRequestRequestTypeDef](./type_defs.md#getparalleldatarequestrequesttypedef)
- [GetParallelDataResponseTypeDef](./type_defs.md#getparalleldataresponsetypedef)
- [GetTerminologyRequestRequestTypeDef](./type_defs.md#getterminologyrequestrequesttypedef)
- [GetTerminologyResponseTypeDef](./type_defs.md#getterminologyresponsetypedef)
- [ImportTerminologyRequestRequestTypeDef](./type_defs.md#importterminologyrequestrequesttypedef)
- [ImportTerminologyResponseTypeDef](./type_defs.md#importterminologyresponsetypedef)
- [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef)
- [JobDetailsTypeDef](./type_defs.md#jobdetailstypedef)
- [ListParallelDataRequestRequestTypeDef](./type_defs.md#listparalleldatarequestrequesttypedef)
- [ListParallelDataResponseTypeDef](./type_defs.md#listparalleldataresponsetypedef)
- [ListTerminologiesRequestRequestTypeDef](./type_defs.md#listterminologiesrequestrequesttypedef)
- [ListTerminologiesResponseTypeDef](./type_defs.md#listterminologiesresponsetypedef)
- [ListTextTranslationJobsRequestRequestTypeDef](./type_defs.md#listtexttranslationjobsrequestrequesttypedef)
- [ListTextTranslationJobsResponseTypeDef](./type_defs.md#listtexttranslationjobsresponsetypedef)
- [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ParallelDataConfigTypeDef](./type_defs.md#paralleldataconfigtypedef)
- [ParallelDataDataLocationTypeDef](./type_defs.md#paralleldatadatalocationtypedef)
- [ParallelDataPropertiesTypeDef](./type_defs.md#paralleldatapropertiestypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartTextTranslationJobRequestRequestTypeDef](./type_defs.md#starttexttranslationjobrequestrequesttypedef)
- [StartTextTranslationJobResponseTypeDef](./type_defs.md#starttexttranslationjobresponsetypedef)
- [StopTextTranslationJobRequestRequestTypeDef](./type_defs.md#stoptexttranslationjobrequestrequesttypedef)
- [StopTextTranslationJobResponseTypeDef](./type_defs.md#stoptexttranslationjobresponsetypedef)
- [TermTypeDef](./type_defs.md#termtypedef)
- [TerminologyDataLocationTypeDef](./type_defs.md#terminologydatalocationtypedef)
- [TerminologyDataTypeDef](./type_defs.md#terminologydatatypedef)
- [TerminologyPropertiesTypeDef](./type_defs.md#terminologypropertiestypedef)
- [TextTranslationJobFilterTypeDef](./type_defs.md#texttranslationjobfiltertypedef)
- [TextTranslationJobPropertiesTypeDef](./type_defs.md#texttranslationjobpropertiestypedef)
- [TranslateTextRequestRequestTypeDef](./type_defs.md#translatetextrequestrequesttypedef)
- [TranslateTextResponseTypeDef](./type_defs.md#translatetextresponsetypedef)
- [TranslationSettingsTypeDef](./type_defs.md#translationsettingstypedef)
- [UpdateParallelDataRequestRequestTypeDef](./type_defs.md#updateparalleldatarequestrequesttypedef)
- [UpdateParallelDataResponseTypeDef](./type_defs.md#updateparalleldataresponsetypedef)
