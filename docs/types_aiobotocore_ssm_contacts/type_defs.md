<a id="typed-dictionaries-for-aiobotocore-ssmcontacts-module"></a>

# Typed dictionaries for aiobotocore SSMContacts module

> [Index](../README.md) > [SSMContacts](./README.md) > Typed dictionaries

Auto-generated documentation for
[SSMContacts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
type annotations stubs module
[types-aiobotocore-ssm-contacts](https://pypi.org/project/types-aiobotocore-ssm-contacts/).

- [Typed dictionaries for aiobotocore SSMContacts module](#typed-dictionaries-for-aiobotocore-ssmcontacts-module)
  - [AcceptPageRequestRequestTypeDef](#acceptpagerequestrequesttypedef)
  - [ActivateContactChannelRequestRequestTypeDef](#activatecontactchannelrequestrequesttypedef)
  - [ChannelTargetInfoTypeDef](#channeltargetinfotypedef)
  - [ContactChannelAddressTypeDef](#contactchanneladdresstypedef)
  - [ContactChannelTypeDef](#contactchanneltypedef)
  - [ContactTargetInfoTypeDef](#contacttargetinfotypedef)
  - [ContactTypeDef](#contacttypedef)
  - [CreateContactChannelRequestRequestTypeDef](#createcontactchannelrequestrequesttypedef)
  - [CreateContactChannelResultTypeDef](#createcontactchannelresulttypedef)
  - [CreateContactRequestRequestTypeDef](#createcontactrequestrequesttypedef)
  - [CreateContactResultTypeDef](#createcontactresulttypedef)
  - [DeactivateContactChannelRequestRequestTypeDef](#deactivatecontactchannelrequestrequesttypedef)
  - [DeleteContactChannelRequestRequestTypeDef](#deletecontactchannelrequestrequesttypedef)
  - [DeleteContactRequestRequestTypeDef](#deletecontactrequestrequesttypedef)
  - [DescribeEngagementRequestRequestTypeDef](#describeengagementrequestrequesttypedef)
  - [DescribeEngagementResultTypeDef](#describeengagementresulttypedef)
  - [DescribePageRequestRequestTypeDef](#describepagerequestrequesttypedef)
  - [DescribePageResultTypeDef](#describepageresulttypedef)
  - [EngagementTypeDef](#engagementtypedef)
  - [GetContactChannelRequestRequestTypeDef](#getcontactchannelrequestrequesttypedef)
  - [GetContactChannelResultTypeDef](#getcontactchannelresulttypedef)
  - [GetContactPolicyRequestRequestTypeDef](#getcontactpolicyrequestrequesttypedef)
  - [GetContactPolicyResultTypeDef](#getcontactpolicyresulttypedef)
  - [GetContactRequestRequestTypeDef](#getcontactrequestrequesttypedef)
  - [GetContactResultTypeDef](#getcontactresulttypedef)
  - [ListContactChannelsRequestRequestTypeDef](#listcontactchannelsrequestrequesttypedef)
  - [ListContactChannelsResultTypeDef](#listcontactchannelsresulttypedef)
  - [ListContactsRequestRequestTypeDef](#listcontactsrequestrequesttypedef)
  - [ListContactsResultTypeDef](#listcontactsresulttypedef)
  - [ListEngagementsRequestRequestTypeDef](#listengagementsrequestrequesttypedef)
  - [ListEngagementsResultTypeDef](#listengagementsresulttypedef)
  - [ListPageReceiptsRequestRequestTypeDef](#listpagereceiptsrequestrequesttypedef)
  - [ListPageReceiptsResultTypeDef](#listpagereceiptsresulttypedef)
  - [ListPagesByContactRequestRequestTypeDef](#listpagesbycontactrequestrequesttypedef)
  - [ListPagesByContactResultTypeDef](#listpagesbycontactresulttypedef)
  - [ListPagesByEngagementRequestRequestTypeDef](#listpagesbyengagementrequestrequesttypedef)
  - [ListPagesByEngagementResultTypeDef](#listpagesbyengagementresulttypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResultTypeDef](#listtagsforresourceresulttypedef)
  - [PageTypeDef](#pagetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PlanTypeDef](#plantypedef)
  - [PutContactPolicyRequestRequestTypeDef](#putcontactpolicyrequestrequesttypedef)
  - [ReceiptTypeDef](#receipttypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SendActivationCodeRequestRequestTypeDef](#sendactivationcoderequestrequesttypedef)
  - [StageTypeDef](#stagetypedef)
  - [StartEngagementRequestRequestTypeDef](#startengagementrequestrequesttypedef)
  - [StartEngagementResultTypeDef](#startengagementresulttypedef)
  - [StopEngagementRequestRequestTypeDef](#stopengagementrequestrequesttypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TargetTypeDef](#targettypedef)
  - [TimeRangeTypeDef](#timerangetypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateContactChannelRequestRequestTypeDef](#updatecontactchannelrequestrequesttypedef)
  - [UpdateContactRequestRequestTypeDef](#updatecontactrequestrequesttypedef)

<a id="acceptpagerequestrequesttypedef"></a>

## AcceptPageRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import AcceptPageRequestRequestTypeDef
```

Required fields:

- `PageId`: `str`
- `AcceptType`: [AcceptTypeType](./literals.md#accepttypetype)
- `AcceptCode`: `str`

Optional fields:

- `ContactChannelId`: `str`
- `Note`: `str`
- `AcceptCodeValidation`:
  [AcceptCodeValidationType](./literals.md#acceptcodevalidationtype)

<a id="activatecontactchannelrequestrequesttypedef"></a>

## ActivateContactChannelRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ActivateContactChannelRequestRequestTypeDef
```

Required fields:

- `ContactChannelId`: `str`
- `ActivationCode`: `str`

<a id="channeltargetinfotypedef"></a>

## ChannelTargetInfoTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ChannelTargetInfoTypeDef
```

Required fields:

- `ContactChannelId`: `str`

Optional fields:

- `RetryIntervalInMinutes`: `int`

<a id="contactchanneladdresstypedef"></a>

## ContactChannelAddressTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ContactChannelAddressTypeDef
```

Optional fields:

- `SimpleAddress`: `str`

<a id="contactchanneltypedef"></a>

## ContactChannelTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ContactChannelTypeDef
```

Required fields:

- `ContactChannelArn`: `str`
- `ContactArn`: `str`
- `Name`: `str`
- `DeliveryAddress`:
  [ContactChannelAddressTypeDef](./type_defs.md#contactchanneladdresstypedef)
- `ActivationStatus`:
  [ActivationStatusType](./literals.md#activationstatustype)

Optional fields:

- `Type`: [ChannelTypeType](./literals.md#channeltypetype)

<a id="contacttargetinfotypedef"></a>

## ContactTargetInfoTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ContactTargetInfoTypeDef
```

Required fields:

- `IsEssential`: `bool`

Optional fields:

- `ContactId`: `str`

<a id="contacttypedef"></a>

## ContactTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ContactTypeDef
```

Required fields:

- `ContactArn`: `str`
- `Alias`: `str`
- `Type`: [ContactTypeType](./literals.md#contacttypetype)

Optional fields:

- `DisplayName`: `str`

<a id="createcontactchannelrequestrequesttypedef"></a>

## CreateContactChannelRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import CreateContactChannelRequestRequestTypeDef
```

Required fields:

- `ContactId`: `str`
- `Name`: `str`
- `Type`: [ChannelTypeType](./literals.md#channeltypetype)
- `DeliveryAddress`:
  [ContactChannelAddressTypeDef](./type_defs.md#contactchanneladdresstypedef)

Optional fields:

- `DeferActivation`: `bool`
- `IdempotencyToken`: `str`

<a id="createcontactchannelresulttypedef"></a>

## CreateContactChannelResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import CreateContactChannelResultTypeDef
```

Required fields:

- `ContactChannelArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createcontactrequestrequesttypedef"></a>

## CreateContactRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import CreateContactRequestRequestTypeDef
```

Required fields:

- `Alias`: `str`
- `Type`: [ContactTypeType](./literals.md#contacttypetype)
- `Plan`: [PlanTypeDef](./type_defs.md#plantypedef)

Optional fields:

- `DisplayName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IdempotencyToken`: `str`

<a id="createcontactresulttypedef"></a>

## CreateContactResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import CreateContactResultTypeDef
```

Required fields:

- `ContactArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deactivatecontactchannelrequestrequesttypedef"></a>

## DeactivateContactChannelRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import DeactivateContactChannelRequestRequestTypeDef
```

Required fields:

- `ContactChannelId`: `str`

<a id="deletecontactchannelrequestrequesttypedef"></a>

## DeleteContactChannelRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import DeleteContactChannelRequestRequestTypeDef
```

Required fields:

- `ContactChannelId`: `str`

<a id="deletecontactrequestrequesttypedef"></a>

## DeleteContactRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import DeleteContactRequestRequestTypeDef
```

Required fields:

- `ContactId`: `str`

<a id="describeengagementrequestrequesttypedef"></a>

## DescribeEngagementRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import DescribeEngagementRequestRequestTypeDef
```

Required fields:

- `EngagementId`: `str`

<a id="describeengagementresulttypedef"></a>

## DescribeEngagementResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import DescribeEngagementResultTypeDef
```

Required fields:

- `ContactArn`: `str`
- `EngagementArn`: `str`
- `Sender`: `str`
- `Subject`: `str`
- `Content`: `str`
- `PublicSubject`: `str`
- `PublicContent`: `str`
- `IncidentId`: `str`
- `StartTime`: `datetime`
- `StopTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describepagerequestrequesttypedef"></a>

## DescribePageRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import DescribePageRequestRequestTypeDef
```

Required fields:

- `PageId`: `str`

<a id="describepageresulttypedef"></a>

## DescribePageResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import DescribePageResultTypeDef
```

Required fields:

- `PageArn`: `str`
- `EngagementArn`: `str`
- `ContactArn`: `str`
- `Sender`: `str`
- `Subject`: `str`
- `Content`: `str`
- `PublicSubject`: `str`
- `PublicContent`: `str`
- `IncidentId`: `str`
- `SentTime`: `datetime`
- `ReadTime`: `datetime`
- `DeliveryTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="engagementtypedef"></a>

## EngagementTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import EngagementTypeDef
```

Required fields:

- `EngagementArn`: `str`
- `ContactArn`: `str`
- `Sender`: `str`

Optional fields:

- `IncidentId`: `str`
- `StartTime`: `datetime`
- `StopTime`: `datetime`

<a id="getcontactchannelrequestrequesttypedef"></a>

## GetContactChannelRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import GetContactChannelRequestRequestTypeDef
```

Required fields:

- `ContactChannelId`: `str`

<a id="getcontactchannelresulttypedef"></a>

## GetContactChannelResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import GetContactChannelResultTypeDef
```

Required fields:

- `ContactArn`: `str`
- `ContactChannelArn`: `str`
- `Name`: `str`
- `Type`: [ChannelTypeType](./literals.md#channeltypetype)
- `DeliveryAddress`:
  [ContactChannelAddressTypeDef](./type_defs.md#contactchanneladdresstypedef)
- `ActivationStatus`:
  [ActivationStatusType](./literals.md#activationstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcontactpolicyrequestrequesttypedef"></a>

## GetContactPolicyRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import GetContactPolicyRequestRequestTypeDef
```

Required fields:

- `ContactArn`: `str`

<a id="getcontactpolicyresulttypedef"></a>

## GetContactPolicyResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import GetContactPolicyResultTypeDef
```

Required fields:

- `ContactArn`: `str`
- `Policy`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcontactrequestrequesttypedef"></a>

## GetContactRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import GetContactRequestRequestTypeDef
```

Required fields:

- `ContactId`: `str`

<a id="getcontactresulttypedef"></a>

## GetContactResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import GetContactResultTypeDef
```

Required fields:

- `ContactArn`: `str`
- `Alias`: `str`
- `DisplayName`: `str`
- `Type`: [ContactTypeType](./literals.md#contacttypetype)
- `Plan`: [PlanTypeDef](./type_defs.md#plantypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcontactchannelsrequestrequesttypedef"></a>

## ListContactChannelsRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListContactChannelsRequestRequestTypeDef
```

Required fields:

- `ContactId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listcontactchannelsresulttypedef"></a>

## ListContactChannelsResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListContactChannelsResultTypeDef
```

Required fields:

- `NextToken`: `str`
- `ContactChannels`:
  `List`\[[ContactChannelTypeDef](./type_defs.md#contactchanneltypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcontactsrequestrequesttypedef"></a>

## ListContactsRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListContactsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `AliasPrefix`: `str`
- `Type`: [ContactTypeType](./literals.md#contacttypetype)

<a id="listcontactsresulttypedef"></a>

## ListContactsResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListContactsResultTypeDef
```

Required fields:

- `NextToken`: `str`
- `Contacts`: `List`\[[ContactTypeDef](./type_defs.md#contacttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listengagementsrequestrequesttypedef"></a>

## ListEngagementsRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListEngagementsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `IncidentId`: `str`
- `TimeRangeValue`: [TimeRangeTypeDef](./type_defs.md#timerangetypedef)

<a id="listengagementsresulttypedef"></a>

## ListEngagementsResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListEngagementsResultTypeDef
```

Required fields:

- `NextToken`: `str`
- `Engagements`:
  `List`\[[EngagementTypeDef](./type_defs.md#engagementtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpagereceiptsrequestrequesttypedef"></a>

## ListPageReceiptsRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListPageReceiptsRequestRequestTypeDef
```

Required fields:

- `PageId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listpagereceiptsresulttypedef"></a>

## ListPageReceiptsResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListPageReceiptsResultTypeDef
```

Required fields:

- `NextToken`: `str`
- `Receipts`: `List`\[[ReceiptTypeDef](./type_defs.md#receipttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpagesbycontactrequestrequesttypedef"></a>

## ListPagesByContactRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListPagesByContactRequestRequestTypeDef
```

Required fields:

- `ContactId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listpagesbycontactresulttypedef"></a>

## ListPagesByContactResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListPagesByContactResultTypeDef
```

Required fields:

- `NextToken`: `str`
- `Pages`: `List`\[[PageTypeDef](./type_defs.md#pagetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpagesbyengagementrequestrequesttypedef"></a>

## ListPagesByEngagementRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListPagesByEngagementRequestRequestTypeDef
```

Required fields:

- `EngagementId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listpagesbyengagementresulttypedef"></a>

## ListPagesByEngagementResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListPagesByEngagementResultTypeDef
```

Required fields:

- `NextToken`: `str`
- `Pages`: `List`\[[PageTypeDef](./type_defs.md#pagetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`

<a id="listtagsforresourceresulttypedef"></a>

## ListTagsForResourceResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ListTagsForResourceResultTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="pagetypedef"></a>

## PageTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import PageTypeDef
```

Required fields:

- `PageArn`: `str`
- `EngagementArn`: `str`
- `ContactArn`: `str`
- `Sender`: `str`

Optional fields:

- `IncidentId`: `str`
- `SentTime`: `datetime`
- `DeliveryTime`: `datetime`
- `ReadTime`: `datetime`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="plantypedef"></a>

## PlanTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import PlanTypeDef
```

Required fields:

- `Stages`: `Sequence`\[[StageTypeDef](./type_defs.md#stagetypedef)\]

<a id="putcontactpolicyrequestrequesttypedef"></a>

## PutContactPolicyRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import PutContactPolicyRequestRequestTypeDef
```

Required fields:

- `ContactArn`: `str`
- `Policy`: `str`

<a id="receipttypedef"></a>

## ReceiptTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ReceiptTypeDef
```

Required fields:

- `ReceiptType`: [ReceiptTypeType](./literals.md#receipttypetype)
- `ReceiptTime`: `datetime`

Optional fields:

- `ContactChannelArn`: `str`
- `ReceiptInfo`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="sendactivationcoderequestrequesttypedef"></a>

## SendActivationCodeRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import SendActivationCodeRequestRequestTypeDef
```

Required fields:

- `ContactChannelId`: `str`

<a id="stagetypedef"></a>

## StageTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import StageTypeDef
```

Required fields:

- `DurationInMinutes`: `int`
- `Targets`: `Sequence`\[[TargetTypeDef](./type_defs.md#targettypedef)\]

<a id="startengagementrequestrequesttypedef"></a>

## StartEngagementRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import StartEngagementRequestRequestTypeDef
```

Required fields:

- `ContactId`: `str`
- `Sender`: `str`
- `Subject`: `str`
- `Content`: `str`

Optional fields:

- `PublicSubject`: `str`
- `PublicContent`: `str`
- `IncidentId`: `str`
- `IdempotencyToken`: `str`

<a id="startengagementresulttypedef"></a>

## StartEngagementResultTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import StartEngagementResultTypeDef
```

Required fields:

- `EngagementArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopengagementrequestrequesttypedef"></a>

## StopEngagementRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import StopEngagementRequestRequestTypeDef
```

Required fields:

- `EngagementId`: `str`

Optional fields:

- `Reason`: `str`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import TagTypeDef
```

Optional fields:

- `Key`: `str`
- `Value`: `str`

<a id="targettypedef"></a>

## TargetTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import TargetTypeDef
```

Optional fields:

- `ChannelTargetInfo`:
  [ChannelTargetInfoTypeDef](./type_defs.md#channeltargetinfotypedef)
- `ContactTargetInfo`:
  [ContactTargetInfoTypeDef](./type_defs.md#contacttargetinfotypedef)

<a id="timerangetypedef"></a>

## TimeRangeTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import TimeRangeTypeDef
```

Optional fields:

- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updatecontactchannelrequestrequesttypedef"></a>

## UpdateContactChannelRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import UpdateContactChannelRequestRequestTypeDef
```

Required fields:

- `ContactChannelId`: `str`

Optional fields:

- `Name`: `str`
- `DeliveryAddress`:
  [ContactChannelAddressTypeDef](./type_defs.md#contactchanneladdresstypedef)

<a id="updatecontactrequestrequesttypedef"></a>

## UpdateContactRequestRequestTypeDef

```python
from types_aiobotocore_ssm_contacts.type_defs import UpdateContactRequestRequestTypeDef
```

Required fields:

- `ContactId`: `str`

Optional fields:

- `DisplayName`: `str`
- `Plan`: [PlanTypeDef](./type_defs.md#plantypedef)
