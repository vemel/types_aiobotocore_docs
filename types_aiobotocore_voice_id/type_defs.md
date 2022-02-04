<a id="typed-dictionaries-for-aiobotocore-voiceid-module"></a>

# Typed dictionaries for aiobotocore VoiceID module

> [Index](..) > [VoiceID](.) > Typed dictionaries

Auto-generated documentation for
[VoiceID](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID)
type annotations stubs module
[types-aiobotocore-voice-id](https://pypi.org/project/types-aiobotocore-voice-id/).

- [Typed dictionaries for aiobotocore VoiceID module](#typed-dictionaries-for-aiobotocore-voiceid-module)
  - [AuthenticationConfigurationTypeDef](#authenticationconfigurationtypedef)
  - [AuthenticationResultTypeDef](#authenticationresulttypedef)
  - [CreateDomainRequestRequestTypeDef](#createdomainrequestrequesttypedef)
  - [CreateDomainResponseTypeDef](#createdomainresponsetypedef)
  - [DeleteDomainRequestRequestTypeDef](#deletedomainrequestrequesttypedef)
  - [DeleteFraudsterRequestRequestTypeDef](#deletefraudsterrequestrequesttypedef)
  - [DeleteSpeakerRequestRequestTypeDef](#deletespeakerrequestrequesttypedef)
  - [DescribeDomainRequestRequestTypeDef](#describedomainrequestrequesttypedef)
  - [DescribeDomainResponseTypeDef](#describedomainresponsetypedef)
  - [DescribeFraudsterRegistrationJobRequestRequestTypeDef](#describefraudsterregistrationjobrequestrequesttypedef)
  - [DescribeFraudsterRegistrationJobResponseTypeDef](#describefraudsterregistrationjobresponsetypedef)
  - [DescribeFraudsterRequestRequestTypeDef](#describefraudsterrequestrequesttypedef)
  - [DescribeFraudsterResponseTypeDef](#describefraudsterresponsetypedef)
  - [DescribeSpeakerEnrollmentJobRequestRequestTypeDef](#describespeakerenrollmentjobrequestrequesttypedef)
  - [DescribeSpeakerEnrollmentJobResponseTypeDef](#describespeakerenrollmentjobresponsetypedef)
  - [DescribeSpeakerRequestRequestTypeDef](#describespeakerrequestrequesttypedef)
  - [DescribeSpeakerResponseTypeDef](#describespeakerresponsetypedef)
  - [DomainSummaryTypeDef](#domainsummarytypedef)
  - [DomainTypeDef](#domaintypedef)
  - [EnrollmentConfigTypeDef](#enrollmentconfigtypedef)
  - [EnrollmentJobFraudDetectionConfigTypeDef](#enrollmentjobfrauddetectionconfigtypedef)
  - [EvaluateSessionRequestRequestTypeDef](#evaluatesessionrequestrequesttypedef)
  - [EvaluateSessionResponseTypeDef](#evaluatesessionresponsetypedef)
  - [FailureDetailsTypeDef](#failuredetailstypedef)
  - [FraudDetectionConfigurationTypeDef](#frauddetectionconfigurationtypedef)
  - [FraudDetectionResultTypeDef](#frauddetectionresulttypedef)
  - [FraudRiskDetailsTypeDef](#fraudriskdetailstypedef)
  - [FraudsterRegistrationJobSummaryTypeDef](#fraudsterregistrationjobsummarytypedef)
  - [FraudsterRegistrationJobTypeDef](#fraudsterregistrationjobtypedef)
  - [FraudsterTypeDef](#fraudstertypedef)
  - [InputDataConfigTypeDef](#inputdataconfigtypedef)
  - [JobProgressTypeDef](#jobprogresstypedef)
  - [KnownFraudsterRiskTypeDef](#knownfraudsterrisktypedef)
  - [ListDomainsRequestRequestTypeDef](#listdomainsrequestrequesttypedef)
  - [ListDomainsResponseTypeDef](#listdomainsresponsetypedef)
  - [ListFraudsterRegistrationJobsRequestRequestTypeDef](#listfraudsterregistrationjobsrequestrequesttypedef)
  - [ListFraudsterRegistrationJobsResponseTypeDef](#listfraudsterregistrationjobsresponsetypedef)
  - [ListSpeakerEnrollmentJobsRequestRequestTypeDef](#listspeakerenrollmentjobsrequestrequesttypedef)
  - [ListSpeakerEnrollmentJobsResponseTypeDef](#listspeakerenrollmentjobsresponsetypedef)
  - [ListSpeakersRequestRequestTypeDef](#listspeakersrequestrequesttypedef)
  - [ListSpeakersResponseTypeDef](#listspeakersresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [OptOutSpeakerRequestRequestTypeDef](#optoutspeakerrequestrequesttypedef)
  - [OptOutSpeakerResponseTypeDef](#optoutspeakerresponsetypedef)
  - [OutputDataConfigTypeDef](#outputdataconfigtypedef)
  - [RegistrationConfigTypeDef](#registrationconfigtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ServerSideEncryptionConfigurationTypeDef](#serversideencryptionconfigurationtypedef)
  - [SpeakerEnrollmentJobSummaryTypeDef](#speakerenrollmentjobsummarytypedef)
  - [SpeakerEnrollmentJobTypeDef](#speakerenrollmentjobtypedef)
  - [SpeakerSummaryTypeDef](#speakersummarytypedef)
  - [SpeakerTypeDef](#speakertypedef)
  - [StartFraudsterRegistrationJobRequestRequestTypeDef](#startfraudsterregistrationjobrequestrequesttypedef)
  - [StartFraudsterRegistrationJobResponseTypeDef](#startfraudsterregistrationjobresponsetypedef)
  - [StartSpeakerEnrollmentJobRequestRequestTypeDef](#startspeakerenrollmentjobrequestrequesttypedef)
  - [StartSpeakerEnrollmentJobResponseTypeDef](#startspeakerenrollmentjobresponsetypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateDomainRequestRequestTypeDef](#updatedomainrequestrequesttypedef)
  - [UpdateDomainResponseTypeDef](#updatedomainresponsetypedef)

<a id="authenticationconfigurationtypedef"></a>

## AuthenticationConfigurationTypeDef

```python
from types_aiobotocore_voice_id.type_defs import AuthenticationConfigurationTypeDef
```

Required fields:

- `AcceptanceThreshold`: `int`

<a id="authenticationresulttypedef"></a>

## AuthenticationResultTypeDef

```python
from types_aiobotocore_voice_id.type_defs import AuthenticationResultTypeDef
```

Optional fields:

- `AudioAggregationEndedAt`: `datetime`
- `AudioAggregationStartedAt`: `datetime`
- `AuthenticationResultId`: `str`
- `Configuration`:
  [AuthenticationConfigurationTypeDef](./type_defs.md#authenticationconfigurationtypedef)
- `CustomerSpeakerId`: `str`
- `Decision`:
  [AuthenticationDecisionType](./literals.md#authenticationdecisiontype)
- `GeneratedSpeakerId`: `str`
- `Score`: `int`

<a id="createdomainrequestrequesttypedef"></a>

## CreateDomainRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import CreateDomainRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `ServerSideEncryptionConfiguration`:
  [ServerSideEncryptionConfigurationTypeDef](./type_defs.md#serversideencryptionconfigurationtypedef)

Optional fields:

- `ClientToken`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdomainresponsetypedef"></a>

## CreateDomainResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import CreateDomainResponseTypeDef
```

Required fields:

- `Domain`: [DomainTypeDef](./type_defs.md#domaintypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletedomainrequestrequesttypedef"></a>

## DeleteDomainRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DeleteDomainRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

<a id="deletefraudsterrequestrequesttypedef"></a>

## DeleteFraudsterRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DeleteFraudsterRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `FraudsterId`: `str`

<a id="deletespeakerrequestrequesttypedef"></a>

## DeleteSpeakerRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DeleteSpeakerRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `SpeakerId`: `str`

<a id="describedomainrequestrequesttypedef"></a>

## DescribeDomainRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeDomainRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

<a id="describedomainresponsetypedef"></a>

## DescribeDomainResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeDomainResponseTypeDef
```

Required fields:

- `Domain`: [DomainTypeDef](./type_defs.md#domaintypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describefraudsterregistrationjobrequestrequesttypedef"></a>

## DescribeFraudsterRegistrationJobRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeFraudsterRegistrationJobRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `JobId`: `str`

<a id="describefraudsterregistrationjobresponsetypedef"></a>

## DescribeFraudsterRegistrationJobResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeFraudsterRegistrationJobResponseTypeDef
```

Required fields:

- `Job`:
  [FraudsterRegistrationJobTypeDef](./type_defs.md#fraudsterregistrationjobtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describefraudsterrequestrequesttypedef"></a>

## DescribeFraudsterRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeFraudsterRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `FraudsterId`: `str`

<a id="describefraudsterresponsetypedef"></a>

## DescribeFraudsterResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeFraudsterResponseTypeDef
```

Required fields:

- `Fraudster`: [FraudsterTypeDef](./type_defs.md#fraudstertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describespeakerenrollmentjobrequestrequesttypedef"></a>

## DescribeSpeakerEnrollmentJobRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeSpeakerEnrollmentJobRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `JobId`: `str`

<a id="describespeakerenrollmentjobresponsetypedef"></a>

## DescribeSpeakerEnrollmentJobResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeSpeakerEnrollmentJobResponseTypeDef
```

Required fields:

- `Job`:
  [SpeakerEnrollmentJobTypeDef](./type_defs.md#speakerenrollmentjobtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describespeakerrequestrequesttypedef"></a>

## DescribeSpeakerRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeSpeakerRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `SpeakerId`: `str`

<a id="describespeakerresponsetypedef"></a>

## DescribeSpeakerResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DescribeSpeakerResponseTypeDef
```

Required fields:

- `Speaker`: [SpeakerTypeDef](./type_defs.md#speakertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="domainsummarytypedef"></a>

## DomainSummaryTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DomainSummaryTypeDef
```

Optional fields:

- `Arn`: `str`
- `CreatedAt`: `datetime`
- `Description`: `str`
- `DomainId`: `str`
- `DomainStatus`: [DomainStatusType](./literals.md#domainstatustype)
- `Name`: `str`
- `ServerSideEncryptionConfiguration`:
  [ServerSideEncryptionConfigurationTypeDef](./type_defs.md#serversideencryptionconfigurationtypedef)
- `UpdatedAt`: `datetime`

<a id="domaintypedef"></a>

## DomainTypeDef

```python
from types_aiobotocore_voice_id.type_defs import DomainTypeDef
```

Optional fields:

- `Arn`: `str`
- `CreatedAt`: `datetime`
- `Description`: `str`
- `DomainId`: `str`
- `DomainStatus`: [DomainStatusType](./literals.md#domainstatustype)
- `Name`: `str`
- `ServerSideEncryptionConfiguration`:
  [ServerSideEncryptionConfigurationTypeDef](./type_defs.md#serversideencryptionconfigurationtypedef)
- `UpdatedAt`: `datetime`

<a id="enrollmentconfigtypedef"></a>

## EnrollmentConfigTypeDef

```python
from types_aiobotocore_voice_id.type_defs import EnrollmentConfigTypeDef
```

Optional fields:

- `ExistingEnrollmentAction`:
  [ExistingEnrollmentActionType](./literals.md#existingenrollmentactiontype)
- `FraudDetectionConfig`:
  [EnrollmentJobFraudDetectionConfigTypeDef](./type_defs.md#enrollmentjobfrauddetectionconfigtypedef)

<a id="enrollmentjobfrauddetectionconfigtypedef"></a>

## EnrollmentJobFraudDetectionConfigTypeDef

```python
from types_aiobotocore_voice_id.type_defs import EnrollmentJobFraudDetectionConfigTypeDef
```

Optional fields:

- `FraudDetectionAction`:
  [FraudDetectionActionType](./literals.md#frauddetectionactiontype)
- `RiskThreshold`: `int`

<a id="evaluatesessionrequestrequesttypedef"></a>

## EvaluateSessionRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import EvaluateSessionRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `SessionNameOrId`: `str`

<a id="evaluatesessionresponsetypedef"></a>

## EvaluateSessionResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import EvaluateSessionResponseTypeDef
```

Required fields:

- `AuthenticationResult`:
  [AuthenticationResultTypeDef](./type_defs.md#authenticationresulttypedef)
- `DomainId`: `str`
- `FraudDetectionResult`:
  [FraudDetectionResultTypeDef](./type_defs.md#frauddetectionresulttypedef)
- `SessionId`: `str`
- `SessionName`: `str`
- `StreamingStatus`: [StreamingStatusType](./literals.md#streamingstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="failuredetailstypedef"></a>

## FailureDetailsTypeDef

```python
from types_aiobotocore_voice_id.type_defs import FailureDetailsTypeDef
```

Optional fields:

- `Message`: `str`
- `StatusCode`: `int`

<a id="frauddetectionconfigurationtypedef"></a>

## FraudDetectionConfigurationTypeDef

```python
from types_aiobotocore_voice_id.type_defs import FraudDetectionConfigurationTypeDef
```

Required fields:

- `RiskThreshold`: `int`

<a id="frauddetectionresulttypedef"></a>

## FraudDetectionResultTypeDef

```python
from types_aiobotocore_voice_id.type_defs import FraudDetectionResultTypeDef
```

Optional fields:

- `AudioAggregationEndedAt`: `datetime`
- `AudioAggregationStartedAt`: `datetime`
- `Configuration`:
  [FraudDetectionConfigurationTypeDef](./type_defs.md#frauddetectionconfigurationtypedef)
- `Decision`:
  [FraudDetectionDecisionType](./literals.md#frauddetectiondecisiontype)
- `FraudDetectionResultId`: `str`
- `Reasons`: `List`\[`Literal['KNOWN_FRAUDSTER']` (see
  [FraudDetectionReasonType](./literals.md#frauddetectionreasontype))\]
- `RiskDetails`:
  [FraudRiskDetailsTypeDef](./type_defs.md#fraudriskdetailstypedef)

<a id="fraudriskdetailstypedef"></a>

## FraudRiskDetailsTypeDef

```python
from types_aiobotocore_voice_id.type_defs import FraudRiskDetailsTypeDef
```

Required fields:

- `KnownFraudsterRisk`:
  [KnownFraudsterRiskTypeDef](./type_defs.md#knownfraudsterrisktypedef)

<a id="fraudsterregistrationjobsummarytypedef"></a>

## FraudsterRegistrationJobSummaryTypeDef

```python
from types_aiobotocore_voice_id.type_defs import FraudsterRegistrationJobSummaryTypeDef
```

Optional fields:

- `CreatedAt`: `datetime`
- `DomainId`: `str`
- `EndedAt`: `datetime`
- `FailureDetails`:
  [FailureDetailsTypeDef](./type_defs.md#failuredetailstypedef)
- `JobId`: `str`
- `JobName`: `str`
- `JobProgress`: [JobProgressTypeDef](./type_defs.md#jobprogresstypedef)
- `JobStatus`:
  [FraudsterRegistrationJobStatusType](./literals.md#fraudsterregistrationjobstatustype)

<a id="fraudsterregistrationjobtypedef"></a>

## FraudsterRegistrationJobTypeDef

```python
from types_aiobotocore_voice_id.type_defs import FraudsterRegistrationJobTypeDef
```

Optional fields:

- `CreatedAt`: `datetime`
- `DataAccessRoleArn`: `str`
- `DomainId`: `str`
- `EndedAt`: `datetime`
- `FailureDetails`:
  [FailureDetailsTypeDef](./type_defs.md#failuredetailstypedef)
- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef)
- `JobId`: `str`
- `JobName`: `str`
- `JobProgress`: [JobProgressTypeDef](./type_defs.md#jobprogresstypedef)
- `JobStatus`:
  [FraudsterRegistrationJobStatusType](./literals.md#fraudsterregistrationjobstatustype)
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
- `RegistrationConfig`:
  [RegistrationConfigTypeDef](./type_defs.md#registrationconfigtypedef)

<a id="fraudstertypedef"></a>

## FraudsterTypeDef

```python
from types_aiobotocore_voice_id.type_defs import FraudsterTypeDef
```

Optional fields:

- `CreatedAt`: `datetime`
- `DomainId`: `str`
- `GeneratedFraudsterId`: `str`

<a id="inputdataconfigtypedef"></a>

## InputDataConfigTypeDef

```python
from types_aiobotocore_voice_id.type_defs import InputDataConfigTypeDef
```

Required fields:

- `S3Uri`: `str`

<a id="jobprogresstypedef"></a>

## JobProgressTypeDef

```python
from types_aiobotocore_voice_id.type_defs import JobProgressTypeDef
```

Optional fields:

- `PercentComplete`: `int`

<a id="knownfraudsterrisktypedef"></a>

## KnownFraudsterRiskTypeDef

```python
from types_aiobotocore_voice_id.type_defs import KnownFraudsterRiskTypeDef
```

Required fields:

- `RiskScore`: `int`

Optional fields:

- `GeneratedFraudsterId`: `str`

<a id="listdomainsrequestrequesttypedef"></a>

## ListDomainsRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListDomainsRequestRequestTypeDef
```

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listdomainsresponsetypedef"></a>

## ListDomainsResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListDomainsResponseTypeDef
```

Required fields:

- `DomainSummaries`:
  `List`\[[DomainSummaryTypeDef](./type_defs.md#domainsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listfraudsterregistrationjobsrequestrequesttypedef"></a>

## ListFraudsterRegistrationJobsRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListFraudsterRegistrationJobsRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

Optional fields:

- `JobStatus`:
  [FraudsterRegistrationJobStatusType](./literals.md#fraudsterregistrationjobstatustype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listfraudsterregistrationjobsresponsetypedef"></a>

## ListFraudsterRegistrationJobsResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListFraudsterRegistrationJobsResponseTypeDef
```

Required fields:

- `JobSummaries`:
  `List`\[[FraudsterRegistrationJobSummaryTypeDef](./type_defs.md#fraudsterregistrationjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listspeakerenrollmentjobsrequestrequesttypedef"></a>

## ListSpeakerEnrollmentJobsRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListSpeakerEnrollmentJobsRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

Optional fields:

- `JobStatus`:
  [SpeakerEnrollmentJobStatusType](./literals.md#speakerenrollmentjobstatustype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listspeakerenrollmentjobsresponsetypedef"></a>

## ListSpeakerEnrollmentJobsResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListSpeakerEnrollmentJobsResponseTypeDef
```

Required fields:

- `JobSummaries`:
  `List`\[[SpeakerEnrollmentJobSummaryTypeDef](./type_defs.md#speakerenrollmentjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listspeakersrequestrequesttypedef"></a>

## ListSpeakersRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListSpeakersRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listspeakersresponsetypedef"></a>

## ListSpeakersResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListSpeakersResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `SpeakerSummaries`:
  `List`\[[SpeakerSummaryTypeDef](./type_defs.md#speakersummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="optoutspeakerrequestrequesttypedef"></a>

## OptOutSpeakerRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import OptOutSpeakerRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `SpeakerId`: `str`

<a id="optoutspeakerresponsetypedef"></a>

## OptOutSpeakerResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import OptOutSpeakerResponseTypeDef
```

Required fields:

- `Speaker`: [SpeakerTypeDef](./type_defs.md#speakertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="outputdataconfigtypedef"></a>

## OutputDataConfigTypeDef

```python
from types_aiobotocore_voice_id.type_defs import OutputDataConfigTypeDef
```

Required fields:

- `S3Uri`: `str`

Optional fields:

- `KmsKeyId`: `str`

<a id="registrationconfigtypedef"></a>

## RegistrationConfigTypeDef

```python
from types_aiobotocore_voice_id.type_defs import RegistrationConfigTypeDef
```

Optional fields:

- `DuplicateRegistrationAction`:
  [DuplicateRegistrationActionType](./literals.md#duplicateregistrationactiontype)
- `FraudsterSimilarityThreshold`: `int`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="serversideencryptionconfigurationtypedef"></a>

## ServerSideEncryptionConfigurationTypeDef

```python
from types_aiobotocore_voice_id.type_defs import ServerSideEncryptionConfigurationTypeDef
```

Required fields:

- `KmsKeyId`: `str`

<a id="speakerenrollmentjobsummarytypedef"></a>

## SpeakerEnrollmentJobSummaryTypeDef

```python
from types_aiobotocore_voice_id.type_defs import SpeakerEnrollmentJobSummaryTypeDef
```

Optional fields:

- `CreatedAt`: `datetime`
- `DomainId`: `str`
- `EndedAt`: `datetime`
- `FailureDetails`:
  [FailureDetailsTypeDef](./type_defs.md#failuredetailstypedef)
- `JobId`: `str`
- `JobName`: `str`
- `JobProgress`: [JobProgressTypeDef](./type_defs.md#jobprogresstypedef)
- `JobStatus`:
  [SpeakerEnrollmentJobStatusType](./literals.md#speakerenrollmentjobstatustype)

<a id="speakerenrollmentjobtypedef"></a>

## SpeakerEnrollmentJobTypeDef

```python
from types_aiobotocore_voice_id.type_defs import SpeakerEnrollmentJobTypeDef
```

Optional fields:

- `CreatedAt`: `datetime`
- `DataAccessRoleArn`: `str`
- `DomainId`: `str`
- `EndedAt`: `datetime`
- `EnrollmentConfig`:
  [EnrollmentConfigTypeDef](./type_defs.md#enrollmentconfigtypedef)
- `FailureDetails`:
  [FailureDetailsTypeDef](./type_defs.md#failuredetailstypedef)
- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef)
- `JobId`: `str`
- `JobName`: `str`
- `JobProgress`: [JobProgressTypeDef](./type_defs.md#jobprogresstypedef)
- `JobStatus`:
  [SpeakerEnrollmentJobStatusType](./literals.md#speakerenrollmentjobstatustype)
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)

<a id="speakersummarytypedef"></a>

## SpeakerSummaryTypeDef

```python
from types_aiobotocore_voice_id.type_defs import SpeakerSummaryTypeDef
```

Optional fields:

- `CreatedAt`: `datetime`
- `CustomerSpeakerId`: `str`
- `DomainId`: `str`
- `GeneratedSpeakerId`: `str`
- `Status`: [SpeakerStatusType](./literals.md#speakerstatustype)
- `UpdatedAt`: `datetime`

<a id="speakertypedef"></a>

## SpeakerTypeDef

```python
from types_aiobotocore_voice_id.type_defs import SpeakerTypeDef
```

Optional fields:

- `CreatedAt`: `datetime`
- `CustomerSpeakerId`: `str`
- `DomainId`: `str`
- `GeneratedSpeakerId`: `str`
- `Status`: [SpeakerStatusType](./literals.md#speakerstatustype)
- `UpdatedAt`: `datetime`

<a id="startfraudsterregistrationjobrequestrequesttypedef"></a>

## StartFraudsterRegistrationJobRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import StartFraudsterRegistrationJobRequestRequestTypeDef
```

Required fields:

- `DataAccessRoleArn`: `str`
- `DomainId`: `str`
- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef)
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)

Optional fields:

- `ClientToken`: `str`
- `JobName`: `str`
- `RegistrationConfig`:
  [RegistrationConfigTypeDef](./type_defs.md#registrationconfigtypedef)

<a id="startfraudsterregistrationjobresponsetypedef"></a>

## StartFraudsterRegistrationJobResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import StartFraudsterRegistrationJobResponseTypeDef
```

Required fields:

- `Job`:
  [FraudsterRegistrationJobTypeDef](./type_defs.md#fraudsterregistrationjobtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startspeakerenrollmentjobrequestrequesttypedef"></a>

## StartSpeakerEnrollmentJobRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import StartSpeakerEnrollmentJobRequestRequestTypeDef
```

Required fields:

- `DataAccessRoleArn`: `str`
- `DomainId`: `str`
- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef)
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)

Optional fields:

- `ClientToken`: `str`
- `EnrollmentConfig`:
  [EnrollmentConfigTypeDef](./type_defs.md#enrollmentconfigtypedef)
- `JobName`: `str`

<a id="startspeakerenrollmentjobresponsetypedef"></a>

## StartSpeakerEnrollmentJobResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import StartSpeakerEnrollmentJobResponseTypeDef
```

Required fields:

- `Job`:
  [SpeakerEnrollmentJobTypeDef](./type_defs.md#speakerenrollmentjobtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_voice_id.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updatedomainrequestrequesttypedef"></a>

## UpdateDomainRequestRequestTypeDef

```python
from types_aiobotocore_voice_id.type_defs import UpdateDomainRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `Name`: `str`
- `ServerSideEncryptionConfiguration`:
  [ServerSideEncryptionConfigurationTypeDef](./type_defs.md#serversideencryptionconfigurationtypedef)

Optional fields:

- `Description`: `str`

<a id="updatedomainresponsetypedef"></a>

## UpdateDomainResponseTypeDef

```python
from types_aiobotocore_voice_id.type_defs import UpdateDomainResponseTypeDef
```

Required fields:

- `Domain`: [DomainTypeDef](./type_defs.md#domaintypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
