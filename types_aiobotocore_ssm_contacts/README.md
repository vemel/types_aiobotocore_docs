<a id="type-annotations-for-aiobotocore-ssmcontacts-module"></a>

# Type annotations for aiobotocore SSMContacts module

> [Index](..) > SSMContacts

Auto-generated documentation for
[SSMContacts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
type annotations stubs module
[types-aiobotocore-ssm-contacts](https://pypi.org/project/types-aiobotocore-ssm-contacts/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[ssm-contacts]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[ssm-contacts]'

# standalone installation
pip install types-aiobotocore-ssm-contacts
```

- [Type annotations for aiobotocore SSMContacts module](#type-annotations-for-aiobotocore-ssmcontacts-module)
  - [SSMContactsClient](#ssmcontactsclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="ssmcontactsclient"></a>

## SSMContactsClient

Type annotations for `session.create_client("ssm-contacts")` as
[SSMContactsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_ssm_contacts.client import SSMContactsClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [accept_page](./client.md#accept_page)
- [activate_contact_channel](./client.md#activate_contact_channel)
- [can_paginate](./client.md#can_paginate)
- [create_contact](./client.md#create_contact)
- [create_contact_channel](./client.md#create_contact_channel)
- [deactivate_contact_channel](./client.md#deactivate_contact_channel)
- [delete_contact](./client.md#delete_contact)
- [delete_contact_channel](./client.md#delete_contact_channel)
- [describe_engagement](./client.md#describe_engagement)
- [describe_page](./client.md#describe_page)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_contact](./client.md#get_contact)
- [get_contact_channel](./client.md#get_contact_channel)
- [get_contact_policy](./client.md#get_contact_policy)
- [get_paginator](./client.md#get_paginator)
- [list_contact_channels](./client.md#list_contact_channels)
- [list_contacts](./client.md#list_contacts)
- [list_engagements](./client.md#list_engagements)
- [list_page_receipts](./client.md#list_page_receipts)
- [list_pages_by_contact](./client.md#list_pages_by_contact)
- [list_pages_by_engagement](./client.md#list_pages_by_engagement)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [put_contact_policy](./client.md#put_contact_policy)
- [send_activation_code](./client.md#send_activation_code)
- [start_engagement](./client.md#start_engagement)
- [stop_engagement](./client.md#stop_engagement)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_contact](./client.md#update_contact)
- [update_contact_channel](./client.md#update_contact_channel)

<a id="exceptions"></a>

### Exceptions

SSMContactsClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- ConflictException
- DataEncryptionException
- InternalServerException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ThrottlingException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("ssm-contacts").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_ssm_contacts.paginator import ListContactChannelsPaginator, ...
```

- [ListContactChannelsPaginator](./paginators.md#listcontactchannelspaginator)
- [ListContactsPaginator](./paginators.md#listcontactspaginator)
- [ListEngagementsPaginator](./paginators.md#listengagementspaginator)
- [ListPageReceiptsPaginator](./paginators.md#listpagereceiptspaginator)
- [ListPagesByContactPaginator](./paginators.md#listpagesbycontactpaginator)
- [ListPagesByEngagementPaginator](./paginators.md#listpagesbyengagementpaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_ssm_contacts.literals import AcceptCodeValidationType, ...
```

- [AcceptCodeValidationType](./literals.md#acceptcodevalidationtype)
- [AcceptTypeType](./literals.md#accepttypetype)
- [ActivationStatusType](./literals.md#activationstatustype)
- [ChannelTypeType](./literals.md#channeltypetype)
- [ContactTypeType](./literals.md#contacttypetype)
- [ListContactChannelsPaginatorName](./literals.md#listcontactchannelspaginatorname)
- [ListContactsPaginatorName](./literals.md#listcontactspaginatorname)
- [ListEngagementsPaginatorName](./literals.md#listengagementspaginatorname)
- [ListPageReceiptsPaginatorName](./literals.md#listpagereceiptspaginatorname)
- [ListPagesByContactPaginatorName](./literals.md#listpagesbycontactpaginatorname)
- [ListPagesByEngagementPaginatorName](./literals.md#listpagesbyengagementpaginatorname)
- [ReceiptTypeType](./literals.md#receipttypetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_ssm_contacts.type_defs import AcceptPageRequestRequestTypeDef, ...
```

- [AcceptPageRequestRequestTypeDef](./type_defs.md#acceptpagerequestrequesttypedef)
- [ActivateContactChannelRequestRequestTypeDef](./type_defs.md#activatecontactchannelrequestrequesttypedef)
- [ChannelTargetInfoTypeDef](./type_defs.md#channeltargetinfotypedef)
- [ContactChannelAddressTypeDef](./type_defs.md#contactchanneladdresstypedef)
- [ContactChannelTypeDef](./type_defs.md#contactchanneltypedef)
- [ContactTargetInfoTypeDef](./type_defs.md#contacttargetinfotypedef)
- [ContactTypeDef](./type_defs.md#contacttypedef)
- [CreateContactChannelRequestRequestTypeDef](./type_defs.md#createcontactchannelrequestrequesttypedef)
- [CreateContactChannelResultTypeDef](./type_defs.md#createcontactchannelresulttypedef)
- [CreateContactRequestRequestTypeDef](./type_defs.md#createcontactrequestrequesttypedef)
- [CreateContactResultTypeDef](./type_defs.md#createcontactresulttypedef)
- [DeactivateContactChannelRequestRequestTypeDef](./type_defs.md#deactivatecontactchannelrequestrequesttypedef)
- [DeleteContactChannelRequestRequestTypeDef](./type_defs.md#deletecontactchannelrequestrequesttypedef)
- [DeleteContactRequestRequestTypeDef](./type_defs.md#deletecontactrequestrequesttypedef)
- [DescribeEngagementRequestRequestTypeDef](./type_defs.md#describeengagementrequestrequesttypedef)
- [DescribeEngagementResultTypeDef](./type_defs.md#describeengagementresulttypedef)
- [DescribePageRequestRequestTypeDef](./type_defs.md#describepagerequestrequesttypedef)
- [DescribePageResultTypeDef](./type_defs.md#describepageresulttypedef)
- [EngagementTypeDef](./type_defs.md#engagementtypedef)
- [GetContactChannelRequestRequestTypeDef](./type_defs.md#getcontactchannelrequestrequesttypedef)
- [GetContactChannelResultTypeDef](./type_defs.md#getcontactchannelresulttypedef)
- [GetContactPolicyRequestRequestTypeDef](./type_defs.md#getcontactpolicyrequestrequesttypedef)
- [GetContactPolicyResultTypeDef](./type_defs.md#getcontactpolicyresulttypedef)
- [GetContactRequestRequestTypeDef](./type_defs.md#getcontactrequestrequesttypedef)
- [GetContactResultTypeDef](./type_defs.md#getcontactresulttypedef)
- [ListContactChannelsRequestRequestTypeDef](./type_defs.md#listcontactchannelsrequestrequesttypedef)
- [ListContactChannelsResultTypeDef](./type_defs.md#listcontactchannelsresulttypedef)
- [ListContactsRequestRequestTypeDef](./type_defs.md#listcontactsrequestrequesttypedef)
- [ListContactsResultTypeDef](./type_defs.md#listcontactsresulttypedef)
- [ListEngagementsRequestRequestTypeDef](./type_defs.md#listengagementsrequestrequesttypedef)
- [ListEngagementsResultTypeDef](./type_defs.md#listengagementsresulttypedef)
- [ListPageReceiptsRequestRequestTypeDef](./type_defs.md#listpagereceiptsrequestrequesttypedef)
- [ListPageReceiptsResultTypeDef](./type_defs.md#listpagereceiptsresulttypedef)
- [ListPagesByContactRequestRequestTypeDef](./type_defs.md#listpagesbycontactrequestrequesttypedef)
- [ListPagesByContactResultTypeDef](./type_defs.md#listpagesbycontactresulttypedef)
- [ListPagesByEngagementRequestRequestTypeDef](./type_defs.md#listpagesbyengagementrequestrequesttypedef)
- [ListPagesByEngagementResultTypeDef](./type_defs.md#listpagesbyengagementresulttypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResultTypeDef](./type_defs.md#listtagsforresourceresulttypedef)
- [PageTypeDef](./type_defs.md#pagetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PlanTypeDef](./type_defs.md#plantypedef)
- [PutContactPolicyRequestRequestTypeDef](./type_defs.md#putcontactpolicyrequestrequesttypedef)
- [ReceiptTypeDef](./type_defs.md#receipttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SendActivationCodeRequestRequestTypeDef](./type_defs.md#sendactivationcoderequestrequesttypedef)
- [StageTypeDef](./type_defs.md#stagetypedef)
- [StartEngagementRequestRequestTypeDef](./type_defs.md#startengagementrequestrequesttypedef)
- [StartEngagementResultTypeDef](./type_defs.md#startengagementresulttypedef)
- [StopEngagementRequestRequestTypeDef](./type_defs.md#stopengagementrequestrequesttypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TargetTypeDef](./type_defs.md#targettypedef)
- [TimeRangeTypeDef](./type_defs.md#timerangetypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateContactChannelRequestRequestTypeDef](./type_defs.md#updatecontactchannelrequestrequesttypedef)
- [UpdateContactRequestRequestTypeDef](./type_defs.md#updatecontactrequestrequesttypedef)
