<a id="ssmcontactsclient-for-aiobotocore-ssmcontacts-module"></a>

# SSMContactsClient for aiobotocore SSMContacts module

> [Index](..) > [SSMContacts](.) > SSMContactsClient

Auto-generated documentation for
[SSMContacts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
type annotations stubs module
[types-aiobotocore-ssm-contacts](https://pypi.org/project/types-aiobotocore-ssm-contacts/).

- [SSMContactsClient for aiobotocore SSMContacts module](#ssmcontactsclient-for-aiobotocore-ssmcontacts-module)
  - [SSMContactsClient](#ssmcontactsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_page](#accept_page)
    - [activate_contact_channel](#activate_contact_channel)
    - [can_paginate](#can_paginate)
    - [create_contact](#create_contact)
    - [create_contact_channel](#create_contact_channel)
    - [deactivate_contact_channel](#deactivate_contact_channel)
    - [delete_contact](#delete_contact)
    - [delete_contact_channel](#delete_contact_channel)
    - [describe_engagement](#describe_engagement)
    - [describe_page](#describe_page)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_contact](#get_contact)
    - [get_contact_channel](#get_contact_channel)
    - [get_contact_policy](#get_contact_policy)
    - [list_contact_channels](#list_contact_channels)
    - [list_contacts](#list_contacts)
    - [list_engagements](#list_engagements)
    - [list_page_receipts](#list_page_receipts)
    - [list_pages_by_contact](#list_pages_by_contact)
    - [list_pages_by_engagement](#list_pages_by_engagement)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_contact_policy](#put_contact_policy)
    - [send_activation_code](#send_activation_code)
    - [start_engagement](#start_engagement)
    - [stop_engagement](#stop_engagement)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_contact](#update_contact)
    - [update_contact_channel](#update_contact_channel)
    - [get_paginator](#get_paginator)

<a id="ssmcontactsclient"></a>

## SSMContactsClient

Type annotations for `aiobotocore.create_client("ssm-contacts")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_ssm_contacts.client import SSMContactsClient

def get_ssm-contacts_client() -> SSMContactsClient:
    return Session().client("ssm-contacts")
```

Boto3 documentation:
[SSMContacts.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ssm_contacts.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.DataEncryptionException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

SSMContactsClient exceptions.

Type annotations for `aiobotocore.create_client("ssm-contacts").exceptions`
method.

Boto3 documentation:
[SSMContacts.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept_page"></a>

### accept_page

Used to acknowledge an engagement to a contact channel during an incident.

Type annotations for `aiobotocore.create_client("ssm-contacts").accept_page`
method.

Boto3 documentation:
[SSMContacts.Client.accept_page](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.accept_page)

Asynchronous method. Use `await accept_page(...)` for a synchronous call.

Arguments mapping described in
[AcceptPageRequestRequestTypeDef](./type_defs.md#acceptpagerequestrequesttypedef).

Keyword-only arguments:

- `PageId`: `str` *(required)*
- `AcceptType`: [AcceptTypeType](./literals.md#accepttypetype) *(required)*
- `AcceptCode`: `str` *(required)*
- `ContactChannelId`: `str`
- `Note`: `str`
- `AcceptCodeValidation`:
  [AcceptCodeValidationType](./literals.md#acceptcodevalidationtype)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="activate_contact_channel"></a>

### activate_contact_channel

Activates a contact's contact channel.

Type annotations for
`aiobotocore.create_client("ssm-contacts").activate_contact_channel` method.

Boto3 documentation:
[SSMContacts.Client.activate_contact_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.activate_contact_channel)

Asynchronous method. Use `await activate_contact_channel(...)` for a
synchronous call.

Arguments mapping described in
[ActivateContactChannelRequestRequestTypeDef](./type_defs.md#activatecontactchannelrequestrequesttypedef).

Keyword-only arguments:

- `ContactChannelId`: `str` *(required)*
- `ActivationCode`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("ssm-contacts").can_paginate`
method.

Boto3 documentation:
[SSMContacts.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_contact"></a>

### create_contact

Contacts are either the contacts that Incident Manager engages during an
incident or the escalation plans that Incident Manager uses to engage contacts
in phases during an incident.

Type annotations for `aiobotocore.create_client("ssm-contacts").create_contact`
method.

Boto3 documentation:
[SSMContacts.Client.create_contact](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_contact)

Asynchronous method. Use `await create_contact(...)` for a synchronous call.

Arguments mapping described in
[CreateContactRequestRequestTypeDef](./type_defs.md#createcontactrequestrequesttypedef).

Keyword-only arguments:

- `Alias`: `str` *(required)*
- `Type`: [ContactTypeType](./literals.md#contacttypetype) *(required)*
- `Plan`: [PlanTypeDef](./type_defs.md#plantypedef) *(required)*
- `DisplayName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IdempotencyToken`: `str`

Returns a `Coroutine` for
[CreateContactResultTypeDef](./type_defs.md#createcontactresulttypedef).

<a id="create_contact_channel"></a>

### create_contact_channel

A contact channel is the method that Incident Manager uses to engage your
contact.

Type annotations for
`aiobotocore.create_client("ssm-contacts").create_contact_channel` method.

Boto3 documentation:
[SSMContacts.Client.create_contact_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_contact_channel)

Asynchronous method. Use `await create_contact_channel(...)` for a synchronous
call.

Arguments mapping described in
[CreateContactChannelRequestRequestTypeDef](./type_defs.md#createcontactchannelrequestrequesttypedef).

Keyword-only arguments:

- `ContactId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Type`: [ChannelTypeType](./literals.md#channeltypetype) *(required)*
- `DeliveryAddress`:
  [ContactChannelAddressTypeDef](./type_defs.md#contactchanneladdresstypedef)
  *(required)*
- `DeferActivation`: `bool`
- `IdempotencyToken`: `str`

Returns a `Coroutine` for
[CreateContactChannelResultTypeDef](./type_defs.md#createcontactchannelresulttypedef).

<a id="deactivate_contact_channel"></a>

### deactivate_contact_channel

To no longer receive Incident Manager engagements to a contact channel, you can
deactivate the channel.

Type annotations for
`aiobotocore.create_client("ssm-contacts").deactivate_contact_channel` method.

Boto3 documentation:
[SSMContacts.Client.deactivate_contact_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.deactivate_contact_channel)

Asynchronous method. Use `await deactivate_contact_channel(...)` for a
synchronous call.

Arguments mapping described in
[DeactivateContactChannelRequestRequestTypeDef](./type_defs.md#deactivatecontactchannelrequestrequesttypedef).

Keyword-only arguments:

- `ContactChannelId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_contact"></a>

### delete_contact

To remove a contact from Incident Manager, you can delete the contact.

Type annotations for `aiobotocore.create_client("ssm-contacts").delete_contact`
method.

Boto3 documentation:
[SSMContacts.Client.delete_contact](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_contact)

Asynchronous method. Use `await delete_contact(...)` for a synchronous call.

Arguments mapping described in
[DeleteContactRequestRequestTypeDef](./type_defs.md#deletecontactrequestrequesttypedef).

Keyword-only arguments:

- `ContactId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_contact_channel"></a>

### delete_contact_channel

To no longer receive engagements on a contact channel, you can delete the
channel from a contact.

Type annotations for
`aiobotocore.create_client("ssm-contacts").delete_contact_channel` method.

Boto3 documentation:
[SSMContacts.Client.delete_contact_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_contact_channel)

Asynchronous method. Use `await delete_contact_channel(...)` for a synchronous
call.

Arguments mapping described in
[DeleteContactChannelRequestRequestTypeDef](./type_defs.md#deletecontactchannelrequestrequesttypedef).

Keyword-only arguments:

- `ContactChannelId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_engagement"></a>

### describe_engagement

Incident Manager uses engagements to engage contacts and escalation plans
during an incident.

Type annotations for
`aiobotocore.create_client("ssm-contacts").describe_engagement` method.

Boto3 documentation:
[SSMContacts.Client.describe_engagement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.describe_engagement)

Asynchronous method. Use `await describe_engagement(...)` for a synchronous
call.

Arguments mapping described in
[DescribeEngagementRequestRequestTypeDef](./type_defs.md#describeengagementrequestrequesttypedef).

Keyword-only arguments:

- `EngagementId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeEngagementResultTypeDef](./type_defs.md#describeengagementresulttypedef).

<a id="describe_page"></a>

### describe_page

Lists details of the engagement to a contact channel.

Type annotations for `aiobotocore.create_client("ssm-contacts").describe_page`
method.

Boto3 documentation:
[SSMContacts.Client.describe_page](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.describe_page)

Asynchronous method. Use `await describe_page(...)` for a synchronous call.

Arguments mapping described in
[DescribePageRequestRequestTypeDef](./type_defs.md#describepagerequestrequesttypedef).

Keyword-only arguments:

- `PageId`: `str` *(required)*

Returns a `Coroutine` for
[DescribePageResultTypeDef](./type_defs.md#describepageresulttypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("ssm-contacts").generate_presigned_url` method.

Boto3 documentation:
[SSMContacts.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_contact"></a>

### get_contact

Retrieves information about the specified contact or escalation plan.

Type annotations for `aiobotocore.create_client("ssm-contacts").get_contact`
method.

Boto3 documentation:
[SSMContacts.Client.get_contact](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact)

Asynchronous method. Use `await get_contact(...)` for a synchronous call.

Arguments mapping described in
[GetContactRequestRequestTypeDef](./type_defs.md#getcontactrequestrequesttypedef).

Keyword-only arguments:

- `ContactId`: `str` *(required)*

Returns a `Coroutine` for
[GetContactResultTypeDef](./type_defs.md#getcontactresulttypedef).

<a id="get_contact_channel"></a>

### get_contact_channel

List details about a specific contact channel.

Type annotations for
`aiobotocore.create_client("ssm-contacts").get_contact_channel` method.

Boto3 documentation:
[SSMContacts.Client.get_contact_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact_channel)

Asynchronous method. Use `await get_contact_channel(...)` for a synchronous
call.

Arguments mapping described in
[GetContactChannelRequestRequestTypeDef](./type_defs.md#getcontactchannelrequestrequesttypedef).

Keyword-only arguments:

- `ContactChannelId`: `str` *(required)*

Returns a `Coroutine` for
[GetContactChannelResultTypeDef](./type_defs.md#getcontactchannelresulttypedef).

<a id="get_contact_policy"></a>

### get_contact_policy

Retrieves the resource policies attached to the specified contact or escalation
plan.

Type annotations for
`aiobotocore.create_client("ssm-contacts").get_contact_policy` method.

Boto3 documentation:
[SSMContacts.Client.get_contact_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact_policy)

Asynchronous method. Use `await get_contact_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetContactPolicyRequestRequestTypeDef](./type_defs.md#getcontactpolicyrequestrequesttypedef).

Keyword-only arguments:

- `ContactArn`: `str` *(required)*

Returns a `Coroutine` for
[GetContactPolicyResultTypeDef](./type_defs.md#getcontactpolicyresulttypedef).

<a id="list_contact_channels"></a>

### list_contact_channels

Lists all contact channels for the specified contact.

Type annotations for
`aiobotocore.create_client("ssm-contacts").list_contact_channels` method.

Boto3 documentation:
[SSMContacts.Client.list_contact_channels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_contact_channels)

Asynchronous method. Use `await list_contact_channels(...)` for a synchronous
call.

Arguments mapping described in
[ListContactChannelsRequestRequestTypeDef](./type_defs.md#listcontactchannelsrequestrequesttypedef).

Keyword-only arguments:

- `ContactId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListContactChannelsResultTypeDef](./type_defs.md#listcontactchannelsresulttypedef).

<a id="list_contacts"></a>

### list_contacts

Lists all contacts and escalation plans in Incident Manager.

Type annotations for `aiobotocore.create_client("ssm-contacts").list_contacts`
method.

Boto3 documentation:
[SSMContacts.Client.list_contacts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_contacts)

Asynchronous method. Use `await list_contacts(...)` for a synchronous call.

Arguments mapping described in
[ListContactsRequestRequestTypeDef](./type_defs.md#listcontactsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `AliasPrefix`: `str`
- `Type`: [ContactTypeType](./literals.md#contacttypetype)

Returns a `Coroutine` for
[ListContactsResultTypeDef](./type_defs.md#listcontactsresulttypedef).

<a id="list_engagements"></a>

### list_engagements

Lists all engagements that have happened in an incident.

Type annotations for
`aiobotocore.create_client("ssm-contacts").list_engagements` method.

Boto3 documentation:
[SSMContacts.Client.list_engagements](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_engagements)

Asynchronous method. Use `await list_engagements(...)` for a synchronous call.

Arguments mapping described in
[ListEngagementsRequestRequestTypeDef](./type_defs.md#listengagementsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `IncidentId`: `str`
- `TimeRangeValue`: [TimeRangeTypeDef](./type_defs.md#timerangetypedef)

Returns a `Coroutine` for
[ListEngagementsResultTypeDef](./type_defs.md#listengagementsresulttypedef).

<a id="list_page_receipts"></a>

### list_page_receipts

Lists all of the engagements to contact channels that have been acknowledged.

Type annotations for
`aiobotocore.create_client("ssm-contacts").list_page_receipts` method.

Boto3 documentation:
[SSMContacts.Client.list_page_receipts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_page_receipts)

Asynchronous method. Use `await list_page_receipts(...)` for a synchronous
call.

Arguments mapping described in
[ListPageReceiptsRequestRequestTypeDef](./type_defs.md#listpagereceiptsrequestrequesttypedef).

Keyword-only arguments:

- `PageId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListPageReceiptsResultTypeDef](./type_defs.md#listpagereceiptsresulttypedef).

<a id="list_pages_by_contact"></a>

### list_pages_by_contact

Lists the engagements to a contact's contact channels.

Type annotations for
`aiobotocore.create_client("ssm-contacts").list_pages_by_contact` method.

Boto3 documentation:
[SSMContacts.Client.list_pages_by_contact](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_pages_by_contact)

Asynchronous method. Use `await list_pages_by_contact(...)` for a synchronous
call.

Arguments mapping described in
[ListPagesByContactRequestRequestTypeDef](./type_defs.md#listpagesbycontactrequestrequesttypedef).

Keyword-only arguments:

- `ContactId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListPagesByContactResultTypeDef](./type_defs.md#listpagesbycontactresulttypedef).

<a id="list_pages_by_engagement"></a>

### list_pages_by_engagement

Lists the engagements to contact channels that occurred by engaging a contact.

Type annotations for
`aiobotocore.create_client("ssm-contacts").list_pages_by_engagement` method.

Boto3 documentation:
[SSMContacts.Client.list_pages_by_engagement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_pages_by_engagement)

Asynchronous method. Use `await list_pages_by_engagement(...)` for a
synchronous call.

Arguments mapping described in
[ListPagesByEngagementRequestRequestTypeDef](./type_defs.md#listpagesbyengagementrequestrequesttypedef).

Keyword-only arguments:

- `EngagementId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListPagesByEngagementResultTypeDef](./type_defs.md#listpagesbyengagementresulttypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags of an escalation plan or contact.

Type annotations for
`aiobotocore.create_client("ssm-contacts").list_tags_for_resource` method.

Boto3 documentation:
[SSMContacts.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResultTypeDef](./type_defs.md#listtagsforresourceresulttypedef).

<a id="put_contact_policy"></a>

### put_contact_policy

Adds a resource to the specified contact or escalation plan.

Type annotations for
`aiobotocore.create_client("ssm-contacts").put_contact_policy` method.

Boto3 documentation:
[SSMContacts.Client.put_contact_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.put_contact_policy)

Asynchronous method. Use `await put_contact_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutContactPolicyRequestRequestTypeDef](./type_defs.md#putcontactpolicyrequestrequesttypedef).

Keyword-only arguments:

- `ContactArn`: `str` *(required)*
- `Policy`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="send_activation_code"></a>

### send_activation_code

Sends an activation code to a contact channel.

Type annotations for
`aiobotocore.create_client("ssm-contacts").send_activation_code` method.

Boto3 documentation:
[SSMContacts.Client.send_activation_code](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.send_activation_code)

Asynchronous method. Use `await send_activation_code(...)` for a synchronous
call.

Arguments mapping described in
[SendActivationCodeRequestRequestTypeDef](./type_defs.md#sendactivationcoderequestrequesttypedef).

Keyword-only arguments:

- `ContactChannelId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="start_engagement"></a>

### start_engagement

Starts an engagement to a contact or escalation plan.

Type annotations for
`aiobotocore.create_client("ssm-contacts").start_engagement` method.

Boto3 documentation:
[SSMContacts.Client.start_engagement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.start_engagement)

Asynchronous method. Use `await start_engagement(...)` for a synchronous call.

Arguments mapping described in
[StartEngagementRequestRequestTypeDef](./type_defs.md#startengagementrequestrequesttypedef).

Keyword-only arguments:

- `ContactId`: `str` *(required)*
- `Sender`: `str` *(required)*
- `Subject`: `str` *(required)*
- `Content`: `str` *(required)*
- `PublicSubject`: `str`
- `PublicContent`: `str`
- `IncidentId`: `str`
- `IdempotencyToken`: `str`

Returns a `Coroutine` for
[StartEngagementResultTypeDef](./type_defs.md#startengagementresulttypedef).

<a id="stop_engagement"></a>

### stop_engagement

Stops an engagement before it finishes the final stage of the escalation plan
or engagement plan.

Type annotations for
`aiobotocore.create_client("ssm-contacts").stop_engagement` method.

Boto3 documentation:
[SSMContacts.Client.stop_engagement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.stop_engagement)

Asynchronous method. Use `await stop_engagement(...)` for a synchronous call.

Arguments mapping described in
[StopEngagementRequestRequestTypeDef](./type_defs.md#stopengagementrequestrequesttypedef).

Keyword-only arguments:

- `EngagementId`: `str` *(required)*
- `Reason`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Tags a contact or escalation plan.

Type annotations for `aiobotocore.create_client("ssm-contacts").tag_resource`
method.

Boto3 documentation:
[SSMContacts.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from the specified resource.

Type annotations for `aiobotocore.create_client("ssm-contacts").untag_resource`
method.

Boto3 documentation:
[SSMContacts.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_contact"></a>

### update_contact

Updates the contact or escalation plan specified.

Type annotations for `aiobotocore.create_client("ssm-contacts").update_contact`
method.

Boto3 documentation:
[SSMContacts.Client.update_contact](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_contact)

Asynchronous method. Use `await update_contact(...)` for a synchronous call.

Arguments mapping described in
[UpdateContactRequestRequestTypeDef](./type_defs.md#updatecontactrequestrequesttypedef).

Keyword-only arguments:

- `ContactId`: `str` *(required)*
- `DisplayName`: `str`
- `Plan`: [PlanTypeDef](./type_defs.md#plantypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_contact_channel"></a>

### update_contact_channel

Updates a contact's contact channel.

Type annotations for
`aiobotocore.create_client("ssm-contacts").update_contact_channel` method.

Boto3 documentation:
[SSMContacts.Client.update_contact_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_contact_channel)

Asynchronous method. Use `await update_contact_channel(...)` for a synchronous
call.

Arguments mapping described in
[UpdateContactChannelRequestRequestTypeDef](./type_defs.md#updatecontactchannelrequestrequesttypedef).

Keyword-only arguments:

- `ContactChannelId`: `str` *(required)*
- `Name`: `str`
- `DeliveryAddress`:
  [ContactChannelAddressTypeDef](./type_defs.md#contactchanneladdresstypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("ssm-contacts").get_paginator`
method with overloads.

- `client.get_paginator("list_contact_channels")` ->
  [ListContactChannelsPaginator](./paginators.md#listcontactchannelspaginator)
- `client.get_paginator("list_contacts")` ->
  [ListContactsPaginator](./paginators.md#listcontactspaginator)
- `client.get_paginator("list_engagements")` ->
  [ListEngagementsPaginator](./paginators.md#listengagementspaginator)
- `client.get_paginator("list_page_receipts")` ->
  [ListPageReceiptsPaginator](./paginators.md#listpagereceiptspaginator)
- `client.get_paginator("list_pages_by_contact")` ->
  [ListPagesByContactPaginator](./paginators.md#listpagesbycontactpaginator)
- `client.get_paginator("list_pages_by_engagement")` ->
  [ListPagesByEngagementPaginator](./paginators.md#listpagesbyengagementpaginator)
