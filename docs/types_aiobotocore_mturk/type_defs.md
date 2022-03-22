<a id="typed-dictionaries-for-aiobotocore-mturk-module"></a>

# Typed dictionaries for aiobotocore MTurk module

> [Index](../README.md) > [MTurk](./README.md) > Typed dictionaries

Auto-generated documentation for
[MTurk](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk)
type annotations stubs module
[types-aiobotocore-mturk](https://pypi.org/project/types-aiobotocore-mturk/).

- [Typed dictionaries for aiobotocore MTurk module](#typed-dictionaries-for-aiobotocore-mturk-module)
  - [AcceptQualificationRequestRequestRequestTypeDef](#acceptqualificationrequestrequestrequesttypedef)
  - [ApproveAssignmentRequestRequestTypeDef](#approveassignmentrequestrequesttypedef)
  - [AssignmentTypeDef](#assignmenttypedef)
  - [AssociateQualificationWithWorkerRequestRequestTypeDef](#associatequalificationwithworkerrequestrequesttypedef)
  - [BonusPaymentTypeDef](#bonuspaymenttypedef)
  - [CreateAdditionalAssignmentsForHITRequestRequestTypeDef](#createadditionalassignmentsforhitrequestrequesttypedef)
  - [CreateHITRequestRequestTypeDef](#createhitrequestrequesttypedef)
  - [CreateHITResponseTypeDef](#createhitresponsetypedef)
  - [CreateHITTypeRequestRequestTypeDef](#createhittyperequestrequesttypedef)
  - [CreateHITTypeResponseTypeDef](#createhittyperesponsetypedef)
  - [CreateHITWithHITTypeRequestRequestTypeDef](#createhitwithhittyperequestrequesttypedef)
  - [CreateHITWithHITTypeResponseTypeDef](#createhitwithhittyperesponsetypedef)
  - [CreateQualificationTypeRequestRequestTypeDef](#createqualificationtyperequestrequesttypedef)
  - [CreateQualificationTypeResponseTypeDef](#createqualificationtyperesponsetypedef)
  - [CreateWorkerBlockRequestRequestTypeDef](#createworkerblockrequestrequesttypedef)
  - [DeleteHITRequestRequestTypeDef](#deletehitrequestrequesttypedef)
  - [DeleteQualificationTypeRequestRequestTypeDef](#deletequalificationtyperequestrequesttypedef)
  - [DeleteWorkerBlockRequestRequestTypeDef](#deleteworkerblockrequestrequesttypedef)
  - [DisassociateQualificationFromWorkerRequestRequestTypeDef](#disassociatequalificationfromworkerrequestrequesttypedef)
  - [GetAccountBalanceResponseTypeDef](#getaccountbalanceresponsetypedef)
  - [GetAssignmentRequestRequestTypeDef](#getassignmentrequestrequesttypedef)
  - [GetAssignmentResponseTypeDef](#getassignmentresponsetypedef)
  - [GetFileUploadURLRequestRequestTypeDef](#getfileuploadurlrequestrequesttypedef)
  - [GetFileUploadURLResponseTypeDef](#getfileuploadurlresponsetypedef)
  - [GetHITRequestRequestTypeDef](#gethitrequestrequesttypedef)
  - [GetHITResponseTypeDef](#gethitresponsetypedef)
  - [GetQualificationScoreRequestRequestTypeDef](#getqualificationscorerequestrequesttypedef)
  - [GetQualificationScoreResponseTypeDef](#getqualificationscoreresponsetypedef)
  - [GetQualificationTypeRequestRequestTypeDef](#getqualificationtyperequestrequesttypedef)
  - [GetQualificationTypeResponseTypeDef](#getqualificationtyperesponsetypedef)
  - [HITLayoutParameterTypeDef](#hitlayoutparametertypedef)
  - [HITTypeDef](#hittypedef)
  - [ListAssignmentsForHITRequestRequestTypeDef](#listassignmentsforhitrequestrequesttypedef)
  - [ListAssignmentsForHITResponseTypeDef](#listassignmentsforhitresponsetypedef)
  - [ListBonusPaymentsRequestRequestTypeDef](#listbonuspaymentsrequestrequesttypedef)
  - [ListBonusPaymentsResponseTypeDef](#listbonuspaymentsresponsetypedef)
  - [ListHITsForQualificationTypeRequestRequestTypeDef](#listhitsforqualificationtyperequestrequesttypedef)
  - [ListHITsForQualificationTypeResponseTypeDef](#listhitsforqualificationtyperesponsetypedef)
  - [ListHITsRequestRequestTypeDef](#listhitsrequestrequesttypedef)
  - [ListHITsResponseTypeDef](#listhitsresponsetypedef)
  - [ListQualificationRequestsRequestRequestTypeDef](#listqualificationrequestsrequestrequesttypedef)
  - [ListQualificationRequestsResponseTypeDef](#listqualificationrequestsresponsetypedef)
  - [ListQualificationTypesRequestRequestTypeDef](#listqualificationtypesrequestrequesttypedef)
  - [ListQualificationTypesResponseTypeDef](#listqualificationtypesresponsetypedef)
  - [ListReviewPolicyResultsForHITRequestRequestTypeDef](#listreviewpolicyresultsforhitrequestrequesttypedef)
  - [ListReviewPolicyResultsForHITResponseTypeDef](#listreviewpolicyresultsforhitresponsetypedef)
  - [ListReviewableHITsRequestRequestTypeDef](#listreviewablehitsrequestrequesttypedef)
  - [ListReviewableHITsResponseTypeDef](#listreviewablehitsresponsetypedef)
  - [ListWorkerBlocksRequestRequestTypeDef](#listworkerblocksrequestrequesttypedef)
  - [ListWorkerBlocksResponseTypeDef](#listworkerblocksresponsetypedef)
  - [ListWorkersWithQualificationTypeRequestRequestTypeDef](#listworkerswithqualificationtyperequestrequesttypedef)
  - [ListWorkersWithQualificationTypeResponseTypeDef](#listworkerswithqualificationtyperesponsetypedef)
  - [LocaleTypeDef](#localetypedef)
  - [NotificationSpecificationTypeDef](#notificationspecificationtypedef)
  - [NotifyWorkersFailureStatusTypeDef](#notifyworkersfailurestatustypedef)
  - [NotifyWorkersRequestRequestTypeDef](#notifyworkersrequestrequesttypedef)
  - [NotifyWorkersResponseTypeDef](#notifyworkersresponsetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ParameterMapEntryTypeDef](#parametermapentrytypedef)
  - [PolicyParameterTypeDef](#policyparametertypedef)
  - [QualificationRequestTypeDef](#qualificationrequesttypedef)
  - [QualificationRequirementTypeDef](#qualificationrequirementtypedef)
  - [QualificationTypeDef](#qualificationtypedef)
  - [QualificationTypeTypeDef](#qualificationtypetypedef)
  - [RejectAssignmentRequestRequestTypeDef](#rejectassignmentrequestrequesttypedef)
  - [RejectQualificationRequestRequestRequestTypeDef](#rejectqualificationrequestrequestrequesttypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ReviewActionDetailTypeDef](#reviewactiondetailtypedef)
  - [ReviewPolicyTypeDef](#reviewpolicytypedef)
  - [ReviewReportTypeDef](#reviewreporttypedef)
  - [ReviewResultDetailTypeDef](#reviewresultdetailtypedef)
  - [SendBonusRequestRequestTypeDef](#sendbonusrequestrequesttypedef)
  - [SendTestEventNotificationRequestRequestTypeDef](#sendtesteventnotificationrequestrequesttypedef)
  - [UpdateExpirationForHITRequestRequestTypeDef](#updateexpirationforhitrequestrequesttypedef)
  - [UpdateHITReviewStatusRequestRequestTypeDef](#updatehitreviewstatusrequestrequesttypedef)
  - [UpdateHITTypeOfHITRequestRequestTypeDef](#updatehittypeofhitrequestrequesttypedef)
  - [UpdateNotificationSettingsRequestRequestTypeDef](#updatenotificationsettingsrequestrequesttypedef)
  - [UpdateQualificationTypeRequestRequestTypeDef](#updatequalificationtyperequestrequesttypedef)
  - [UpdateQualificationTypeResponseTypeDef](#updatequalificationtyperesponsetypedef)
  - [WorkerBlockTypeDef](#workerblocktypedef)

<a id="acceptqualificationrequestrequestrequesttypedef"></a>

## AcceptQualificationRequestRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import AcceptQualificationRequestRequestRequestTypeDef
```

Required fields:

- `QualificationRequestId`: `str`

Optional fields:

- `IntegerValue`: `int`

<a id="approveassignmentrequestrequesttypedef"></a>

## ApproveAssignmentRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ApproveAssignmentRequestRequestTypeDef
```

Required fields:

- `AssignmentId`: `str`

Optional fields:

- `RequesterFeedback`: `str`
- `OverrideRejection`: `bool`

<a id="assignmenttypedef"></a>

## AssignmentTypeDef

```python
from types_aiobotocore_mturk.type_defs import AssignmentTypeDef
```

Optional fields:

- `AssignmentId`: `str`
- `WorkerId`: `str`
- `HITId`: `str`
- `AssignmentStatus`:
  [AssignmentStatusType](./literals.md#assignmentstatustype)
- `AutoApprovalTime`: `datetime`
- `AcceptTime`: `datetime`
- `SubmitTime`: `datetime`
- `ApprovalTime`: `datetime`
- `RejectionTime`: `datetime`
- `Deadline`: `datetime`
- `Answer`: `str`
- `RequesterFeedback`: `str`

<a id="associatequalificationwithworkerrequestrequesttypedef"></a>

## AssociateQualificationWithWorkerRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import AssociateQualificationWithWorkerRequestRequestTypeDef
```

Required fields:

- `QualificationTypeId`: `str`
- `WorkerId`: `str`

Optional fields:

- `IntegerValue`: `int`
- `SendNotification`: `bool`

<a id="bonuspaymenttypedef"></a>

## BonusPaymentTypeDef

```python
from types_aiobotocore_mturk.type_defs import BonusPaymentTypeDef
```

Optional fields:

- `WorkerId`: `str`
- `BonusAmount`: `str`
- `AssignmentId`: `str`
- `Reason`: `str`
- `GrantTime`: `datetime`

<a id="createadditionalassignmentsforhitrequestrequesttypedef"></a>

## CreateAdditionalAssignmentsForHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateAdditionalAssignmentsForHITRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`
- `NumberOfAdditionalAssignments`: `int`

Optional fields:

- `UniqueRequestToken`: `str`

<a id="createhitrequestrequesttypedef"></a>

## CreateHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateHITRequestRequestTypeDef
```

Required fields:

- `LifetimeInSeconds`: `int`
- `AssignmentDurationInSeconds`: `int`
- `Reward`: `str`
- `Title`: `str`
- `Description`: `str`

Optional fields:

- `MaxAssignments`: `int`
- `AutoApprovalDelayInSeconds`: `int`
- `Keywords`: `str`
- `Question`: `str`
- `RequesterAnnotation`: `str`
- `QualificationRequirements`:
  `Sequence`\[[QualificationRequirementTypeDef](./type_defs.md#qualificationrequirementtypedef)\]
- `UniqueRequestToken`: `str`
- `AssignmentReviewPolicy`:
  [ReviewPolicyTypeDef](./type_defs.md#reviewpolicytypedef)
- `HITReviewPolicy`: [ReviewPolicyTypeDef](./type_defs.md#reviewpolicytypedef)
- `HITLayoutId`: `str`
- `HITLayoutParameters`:
  `Sequence`\[[HITLayoutParameterTypeDef](./type_defs.md#hitlayoutparametertypedef)\]

<a id="createhitresponsetypedef"></a>

## CreateHITResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateHITResponseTypeDef
```

Required fields:

- `HIT`: [HITTypeDef](./type_defs.md#hittypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createhittyperequestrequesttypedef"></a>

## CreateHITTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateHITTypeRequestRequestTypeDef
```

Required fields:

- `AssignmentDurationInSeconds`: `int`
- `Reward`: `str`
- `Title`: `str`
- `Description`: `str`

Optional fields:

- `AutoApprovalDelayInSeconds`: `int`
- `Keywords`: `str`
- `QualificationRequirements`:
  `Sequence`\[[QualificationRequirementTypeDef](./type_defs.md#qualificationrequirementtypedef)\]

<a id="createhittyperesponsetypedef"></a>

## CreateHITTypeResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateHITTypeResponseTypeDef
```

Required fields:

- `HITTypeId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createhitwithhittyperequestrequesttypedef"></a>

## CreateHITWithHITTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateHITWithHITTypeRequestRequestTypeDef
```

Required fields:

- `HITTypeId`: `str`
- `LifetimeInSeconds`: `int`

Optional fields:

- `MaxAssignments`: `int`
- `Question`: `str`
- `RequesterAnnotation`: `str`
- `UniqueRequestToken`: `str`
- `AssignmentReviewPolicy`:
  [ReviewPolicyTypeDef](./type_defs.md#reviewpolicytypedef)
- `HITReviewPolicy`: [ReviewPolicyTypeDef](./type_defs.md#reviewpolicytypedef)
- `HITLayoutId`: `str`
- `HITLayoutParameters`:
  `Sequence`\[[HITLayoutParameterTypeDef](./type_defs.md#hitlayoutparametertypedef)\]

<a id="createhitwithhittyperesponsetypedef"></a>

## CreateHITWithHITTypeResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateHITWithHITTypeResponseTypeDef
```

Required fields:

- `HIT`: [HITTypeDef](./type_defs.md#hittypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createqualificationtyperequestrequesttypedef"></a>

## CreateQualificationTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateQualificationTypeRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `Description`: `str`
- `QualificationTypeStatus`:
  [QualificationTypeStatusType](./literals.md#qualificationtypestatustype)

Optional fields:

- `Keywords`: `str`
- `RetryDelayInSeconds`: `int`
- `Test`: `str`
- `AnswerKey`: `str`
- `TestDurationInSeconds`: `int`
- `AutoGranted`: `bool`
- `AutoGrantedValue`: `int`

<a id="createqualificationtyperesponsetypedef"></a>

## CreateQualificationTypeResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateQualificationTypeResponseTypeDef
```

Required fields:

- `QualificationType`:
  [QualificationTypeTypeDef](./type_defs.md#qualificationtypetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createworkerblockrequestrequesttypedef"></a>

## CreateWorkerBlockRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import CreateWorkerBlockRequestRequestTypeDef
```

Required fields:

- `WorkerId`: `str`
- `Reason`: `str`

<a id="deletehitrequestrequesttypedef"></a>

## DeleteHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import DeleteHITRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`

<a id="deletequalificationtyperequestrequesttypedef"></a>

## DeleteQualificationTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import DeleteQualificationTypeRequestRequestTypeDef
```

Required fields:

- `QualificationTypeId`: `str`

<a id="deleteworkerblockrequestrequesttypedef"></a>

## DeleteWorkerBlockRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import DeleteWorkerBlockRequestRequestTypeDef
```

Required fields:

- `WorkerId`: `str`

Optional fields:

- `Reason`: `str`

<a id="disassociatequalificationfromworkerrequestrequesttypedef"></a>

## DisassociateQualificationFromWorkerRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import DisassociateQualificationFromWorkerRequestRequestTypeDef
```

Required fields:

- `WorkerId`: `str`
- `QualificationTypeId`: `str`

Optional fields:

- `Reason`: `str`

<a id="getaccountbalanceresponsetypedef"></a>

## GetAccountBalanceResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetAccountBalanceResponseTypeDef
```

Required fields:

- `AvailableBalance`: `str`
- `OnHoldBalance`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getassignmentrequestrequesttypedef"></a>

## GetAssignmentRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetAssignmentRequestRequestTypeDef
```

Required fields:

- `AssignmentId`: `str`

<a id="getassignmentresponsetypedef"></a>

## GetAssignmentResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetAssignmentResponseTypeDef
```

Required fields:

- `Assignment`: [AssignmentTypeDef](./type_defs.md#assignmenttypedef)
- `HIT`: [HITTypeDef](./type_defs.md#hittypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getfileuploadurlrequestrequesttypedef"></a>

## GetFileUploadURLRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetFileUploadURLRequestRequestTypeDef
```

Required fields:

- `AssignmentId`: `str`
- `QuestionIdentifier`: `str`

<a id="getfileuploadurlresponsetypedef"></a>

## GetFileUploadURLResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetFileUploadURLResponseTypeDef
```

Required fields:

- `FileUploadURL`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="gethitrequestrequesttypedef"></a>

## GetHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetHITRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`

<a id="gethitresponsetypedef"></a>

## GetHITResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetHITResponseTypeDef
```

Required fields:

- `HIT`: [HITTypeDef](./type_defs.md#hittypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getqualificationscorerequestrequesttypedef"></a>

## GetQualificationScoreRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetQualificationScoreRequestRequestTypeDef
```

Required fields:

- `QualificationTypeId`: `str`
- `WorkerId`: `str`

<a id="getqualificationscoreresponsetypedef"></a>

## GetQualificationScoreResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetQualificationScoreResponseTypeDef
```

Required fields:

- `Qualification`: [QualificationTypeDef](./type_defs.md#qualificationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getqualificationtyperequestrequesttypedef"></a>

## GetQualificationTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetQualificationTypeRequestRequestTypeDef
```

Required fields:

- `QualificationTypeId`: `str`

<a id="getqualificationtyperesponsetypedef"></a>

## GetQualificationTypeResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import GetQualificationTypeResponseTypeDef
```

Required fields:

- `QualificationType`:
  [QualificationTypeTypeDef](./type_defs.md#qualificationtypetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="hitlayoutparametertypedef"></a>

## HITLayoutParameterTypeDef

```python
from types_aiobotocore_mturk.type_defs import HITLayoutParameterTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

<a id="hittypedef"></a>

## HITTypeDef

```python
from types_aiobotocore_mturk.type_defs import HITTypeDef
```

Optional fields:

- `HITId`: `str`
- `HITTypeId`: `str`
- `HITGroupId`: `str`
- `HITLayoutId`: `str`
- `CreationTime`: `datetime`
- `Title`: `str`
- `Description`: `str`
- `Question`: `str`
- `Keywords`: `str`
- `HITStatus`: [HITStatusType](./literals.md#hitstatustype)
- `MaxAssignments`: `int`
- `Reward`: `str`
- `AutoApprovalDelayInSeconds`: `int`
- `Expiration`: `datetime`
- `AssignmentDurationInSeconds`: `int`
- `RequesterAnnotation`: `str`
- `QualificationRequirements`:
  `List`\[[QualificationRequirementTypeDef](./type_defs.md#qualificationrequirementtypedef)\]
- `HITReviewStatus`: [HITReviewStatusType](./literals.md#hitreviewstatustype)
- `NumberOfAssignmentsPending`: `int`
- `NumberOfAssignmentsAvailable`: `int`
- `NumberOfAssignmentsCompleted`: `int`

<a id="listassignmentsforhitrequestrequesttypedef"></a>

## ListAssignmentsForHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListAssignmentsForHITRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `AssignmentStatuses`:
  `Sequence`\[[AssignmentStatusType](./literals.md#assignmentstatustype)\]

<a id="listassignmentsforhitresponsetypedef"></a>

## ListAssignmentsForHITResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListAssignmentsForHITResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `NumResults`: `int`
- `Assignments`:
  `List`\[[AssignmentTypeDef](./type_defs.md#assignmenttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbonuspaymentsrequestrequesttypedef"></a>

## ListBonusPaymentsRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListBonusPaymentsRequestRequestTypeDef
```

Optional fields:

- `HITId`: `str`
- `AssignmentId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listbonuspaymentsresponsetypedef"></a>

## ListBonusPaymentsResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListBonusPaymentsResponseTypeDef
```

Required fields:

- `NumResults`: `int`
- `NextToken`: `str`
- `BonusPayments`:
  `List`\[[BonusPaymentTypeDef](./type_defs.md#bonuspaymenttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listhitsforqualificationtyperequestrequesttypedef"></a>

## ListHITsForQualificationTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListHITsForQualificationTypeRequestRequestTypeDef
```

Required fields:

- `QualificationTypeId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listhitsforqualificationtyperesponsetypedef"></a>

## ListHITsForQualificationTypeResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListHITsForQualificationTypeResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `NumResults`: `int`
- `HITs`: `List`\[[HITTypeDef](./type_defs.md#hittypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listhitsrequestrequesttypedef"></a>

## ListHITsRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListHITsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listhitsresponsetypedef"></a>

## ListHITsResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListHITsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `NumResults`: `int`
- `HITs`: `List`\[[HITTypeDef](./type_defs.md#hittypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listqualificationrequestsrequestrequesttypedef"></a>

## ListQualificationRequestsRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListQualificationRequestsRequestRequestTypeDef
```

Optional fields:

- `QualificationTypeId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listqualificationrequestsresponsetypedef"></a>

## ListQualificationRequestsResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListQualificationRequestsResponseTypeDef
```

Required fields:

- `NumResults`: `int`
- `NextToken`: `str`
- `QualificationRequests`:
  `List`\[[QualificationRequestTypeDef](./type_defs.md#qualificationrequesttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listqualificationtypesrequestrequesttypedef"></a>

## ListQualificationTypesRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListQualificationTypesRequestRequestTypeDef
```

Required fields:

- `MustBeRequestable`: `bool`

Optional fields:

- `Query`: `str`
- `MustBeOwnedByCaller`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listqualificationtypesresponsetypedef"></a>

## ListQualificationTypesResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListQualificationTypesResponseTypeDef
```

Required fields:

- `NumResults`: `int`
- `NextToken`: `str`
- `QualificationTypes`:
  `List`\[[QualificationTypeTypeDef](./type_defs.md#qualificationtypetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listreviewpolicyresultsforhitrequestrequesttypedef"></a>

## ListReviewPolicyResultsForHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListReviewPolicyResultsForHITRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`

Optional fields:

- `PolicyLevels`:
  `Sequence`\[[ReviewPolicyLevelType](./literals.md#reviewpolicyleveltype)\]
- `RetrieveActions`: `bool`
- `RetrieveResults`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listreviewpolicyresultsforhitresponsetypedef"></a>

## ListReviewPolicyResultsForHITResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListReviewPolicyResultsForHITResponseTypeDef
```

Required fields:

- `HITId`: `str`
- `AssignmentReviewPolicy`:
  [ReviewPolicyTypeDef](./type_defs.md#reviewpolicytypedef)
- `HITReviewPolicy`: [ReviewPolicyTypeDef](./type_defs.md#reviewpolicytypedef)
- `AssignmentReviewReport`:
  [ReviewReportTypeDef](./type_defs.md#reviewreporttypedef)
- `HITReviewReport`: [ReviewReportTypeDef](./type_defs.md#reviewreporttypedef)
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listreviewablehitsrequestrequesttypedef"></a>

## ListReviewableHITsRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListReviewableHITsRequestRequestTypeDef
```

Optional fields:

- `HITTypeId`: `str`
- `Status`: [ReviewableHITStatusType](./literals.md#reviewablehitstatustype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listreviewablehitsresponsetypedef"></a>

## ListReviewableHITsResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListReviewableHITsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `NumResults`: `int`
- `HITs`: `List`\[[HITTypeDef](./type_defs.md#hittypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listworkerblocksrequestrequesttypedef"></a>

## ListWorkerBlocksRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListWorkerBlocksRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listworkerblocksresponsetypedef"></a>

## ListWorkerBlocksResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListWorkerBlocksResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `NumResults`: `int`
- `WorkerBlocks`:
  `List`\[[WorkerBlockTypeDef](./type_defs.md#workerblocktypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listworkerswithqualificationtyperequestrequesttypedef"></a>

## ListWorkersWithQualificationTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListWorkersWithQualificationTypeRequestRequestTypeDef
```

Required fields:

- `QualificationTypeId`: `str`

Optional fields:

- `Status`: [QualificationStatusType](./literals.md#qualificationstatustype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listworkerswithqualificationtyperesponsetypedef"></a>

## ListWorkersWithQualificationTypeResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import ListWorkersWithQualificationTypeResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `NumResults`: `int`
- `Qualifications`:
  `List`\[[QualificationTypeDef](./type_defs.md#qualificationtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="localetypedef"></a>

## LocaleTypeDef

```python
from types_aiobotocore_mturk.type_defs import LocaleTypeDef
```

Required fields:

- `Country`: `str`

Optional fields:

- `Subdivision`: `str`

<a id="notificationspecificationtypedef"></a>

## NotificationSpecificationTypeDef

```python
from types_aiobotocore_mturk.type_defs import NotificationSpecificationTypeDef
```

Required fields:

- `Destination`: `str`
- `Transport`:
  [NotificationTransportType](./literals.md#notificationtransporttype)
- `Version`: `str`
- `EventTypes`: `Sequence`\[[EventTypeType](./literals.md#eventtypetype)\]

<a id="notifyworkersfailurestatustypedef"></a>

## NotifyWorkersFailureStatusTypeDef

```python
from types_aiobotocore_mturk.type_defs import NotifyWorkersFailureStatusTypeDef
```

Optional fields:

- `NotifyWorkersFailureCode`:
  [NotifyWorkersFailureCodeType](./literals.md#notifyworkersfailurecodetype)
- `NotifyWorkersFailureMessage`: `str`
- `WorkerId`: `str`

<a id="notifyworkersrequestrequesttypedef"></a>

## NotifyWorkersRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import NotifyWorkersRequestRequestTypeDef
```

Required fields:

- `Subject`: `str`
- `MessageText`: `str`
- `WorkerIds`: `Sequence`\[`str`\]

<a id="notifyworkersresponsetypedef"></a>

## NotifyWorkersResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import NotifyWorkersResponseTypeDef
```

Required fields:

- `NotifyWorkersFailureStatuses`:
  `List`\[[NotifyWorkersFailureStatusTypeDef](./type_defs.md#notifyworkersfailurestatustypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_mturk.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="parametermapentrytypedef"></a>

## ParameterMapEntryTypeDef

```python
from types_aiobotocore_mturk.type_defs import ParameterMapEntryTypeDef
```

Optional fields:

- `Key`: `str`
- `Values`: `Sequence`\[`str`\]

<a id="policyparametertypedef"></a>

## PolicyParameterTypeDef

```python
from types_aiobotocore_mturk.type_defs import PolicyParameterTypeDef
```

Optional fields:

- `Key`: `str`
- `Values`: `Sequence`\[`str`\]
- `MapEntries`:
  `Sequence`\[[ParameterMapEntryTypeDef](./type_defs.md#parametermapentrytypedef)\]

<a id="qualificationrequesttypedef"></a>

## QualificationRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import QualificationRequestTypeDef
```

Optional fields:

- `QualificationRequestId`: `str`
- `QualificationTypeId`: `str`
- `WorkerId`: `str`
- `Test`: `str`
- `Answer`: `str`
- `SubmitTime`: `datetime`

<a id="qualificationrequirementtypedef"></a>

## QualificationRequirementTypeDef

```python
from types_aiobotocore_mturk.type_defs import QualificationRequirementTypeDef
```

Required fields:

- `QualificationTypeId`: `str`
- `Comparator`: [ComparatorType](./literals.md#comparatortype)

Optional fields:

- `IntegerValues`: `Sequence`\[`int`\]
- `LocaleValues`: `Sequence`\[[LocaleTypeDef](./type_defs.md#localetypedef)\]
- `RequiredToPreview`: `bool`
- `ActionsGuarded`: [HITAccessActionsType](./literals.md#hitaccessactionstype)

<a id="qualificationtypedef"></a>

## QualificationTypeDef

```python
from types_aiobotocore_mturk.type_defs import QualificationTypeDef
```

Optional fields:

- `QualificationTypeId`: `str`
- `WorkerId`: `str`
- `GrantTime`: `datetime`
- `IntegerValue`: `int`
- `LocaleValue`: [LocaleTypeDef](./type_defs.md#localetypedef)
- `Status`: [QualificationStatusType](./literals.md#qualificationstatustype)

<a id="qualificationtypetypedef"></a>

## QualificationTypeTypeDef

```python
from types_aiobotocore_mturk.type_defs import QualificationTypeTypeDef
```

Optional fields:

- `QualificationTypeId`: `str`
- `CreationTime`: `datetime`
- `Name`: `str`
- `Description`: `str`
- `Keywords`: `str`
- `QualificationTypeStatus`:
  [QualificationTypeStatusType](./literals.md#qualificationtypestatustype)
- `Test`: `str`
- `TestDurationInSeconds`: `int`
- `AnswerKey`: `str`
- `RetryDelayInSeconds`: `int`
- `IsRequestable`: `bool`
- `AutoGranted`: `bool`
- `AutoGrantedValue`: `int`

<a id="rejectassignmentrequestrequesttypedef"></a>

## RejectAssignmentRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import RejectAssignmentRequestRequestTypeDef
```

Required fields:

- `AssignmentId`: `str`
- `RequesterFeedback`: `str`

<a id="rejectqualificationrequestrequestrequesttypedef"></a>

## RejectQualificationRequestRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import RejectQualificationRequestRequestRequestTypeDef
```

Required fields:

- `QualificationRequestId`: `str`

Optional fields:

- `Reason`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_mturk.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="reviewactiondetailtypedef"></a>

## ReviewActionDetailTypeDef

```python
from types_aiobotocore_mturk.type_defs import ReviewActionDetailTypeDef
```

Optional fields:

- `ActionId`: `str`
- `ActionName`: `str`
- `TargetId`: `str`
- `TargetType`: `str`
- `Status`: [ReviewActionStatusType](./literals.md#reviewactionstatustype)
- `CompleteTime`: `datetime`
- `Result`: `str`
- `ErrorCode`: `str`

<a id="reviewpolicytypedef"></a>

## ReviewPolicyTypeDef

```python
from types_aiobotocore_mturk.type_defs import ReviewPolicyTypeDef
```

Required fields:

- `PolicyName`: `str`

Optional fields:

- `Parameters`:
  `Sequence`\[[PolicyParameterTypeDef](./type_defs.md#policyparametertypedef)\]

<a id="reviewreporttypedef"></a>

## ReviewReportTypeDef

```python
from types_aiobotocore_mturk.type_defs import ReviewReportTypeDef
```

Optional fields:

- `ReviewResults`:
  `List`\[[ReviewResultDetailTypeDef](./type_defs.md#reviewresultdetailtypedef)\]
- `ReviewActions`:
  `List`\[[ReviewActionDetailTypeDef](./type_defs.md#reviewactiondetailtypedef)\]

<a id="reviewresultdetailtypedef"></a>

## ReviewResultDetailTypeDef

```python
from types_aiobotocore_mturk.type_defs import ReviewResultDetailTypeDef
```

Optional fields:

- `ActionId`: `str`
- `SubjectId`: `str`
- `SubjectType`: `str`
- `QuestionId`: `str`
- `Key`: `str`
- `Value`: `str`

<a id="sendbonusrequestrequesttypedef"></a>

## SendBonusRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import SendBonusRequestRequestTypeDef
```

Required fields:

- `WorkerId`: `str`
- `BonusAmount`: `str`
- `AssignmentId`: `str`
- `Reason`: `str`

Optional fields:

- `UniqueRequestToken`: `str`

<a id="sendtesteventnotificationrequestrequesttypedef"></a>

## SendTestEventNotificationRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import SendTestEventNotificationRequestRequestTypeDef
```

Required fields:

- `Notification`:
  [NotificationSpecificationTypeDef](./type_defs.md#notificationspecificationtypedef)
- `TestEventType`: [EventTypeType](./literals.md#eventtypetype)

<a id="updateexpirationforhitrequestrequesttypedef"></a>

## UpdateExpirationForHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import UpdateExpirationForHITRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`
- `ExpireAt`: `Union`\[`datetime`, `str`\]

<a id="updatehitreviewstatusrequestrequesttypedef"></a>

## UpdateHITReviewStatusRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import UpdateHITReviewStatusRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`

Optional fields:

- `Revert`: `bool`

<a id="updatehittypeofhitrequestrequesttypedef"></a>

## UpdateHITTypeOfHITRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import UpdateHITTypeOfHITRequestRequestTypeDef
```

Required fields:

- `HITId`: `str`
- `HITTypeId`: `str`

<a id="updatenotificationsettingsrequestrequesttypedef"></a>

## UpdateNotificationSettingsRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import UpdateNotificationSettingsRequestRequestTypeDef
```

Required fields:

- `HITTypeId`: `str`

Optional fields:

- `Notification`:
  [NotificationSpecificationTypeDef](./type_defs.md#notificationspecificationtypedef)
- `Active`: `bool`

<a id="updatequalificationtyperequestrequesttypedef"></a>

## UpdateQualificationTypeRequestRequestTypeDef

```python
from types_aiobotocore_mturk.type_defs import UpdateQualificationTypeRequestRequestTypeDef
```

Required fields:

- `QualificationTypeId`: `str`

Optional fields:

- `Description`: `str`
- `QualificationTypeStatus`:
  [QualificationTypeStatusType](./literals.md#qualificationtypestatustype)
- `Test`: `str`
- `AnswerKey`: `str`
- `TestDurationInSeconds`: `int`
- `RetryDelayInSeconds`: `int`
- `AutoGranted`: `bool`
- `AutoGrantedValue`: `int`

<a id="updatequalificationtyperesponsetypedef"></a>

## UpdateQualificationTypeResponseTypeDef

```python
from types_aiobotocore_mturk.type_defs import UpdateQualificationTypeResponseTypeDef
```

Required fields:

- `QualificationType`:
  [QualificationTypeTypeDef](./type_defs.md#qualificationtypetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="workerblocktypedef"></a>

## WorkerBlockTypeDef

```python
from types_aiobotocore_mturk.type_defs import WorkerBlockTypeDef
```

Optional fields:

- `WorkerId`: `str`
- `Reason`: `str`
