<a id="fmsclient-for-aiobotocore-fms-module"></a>

# FMSClient for aiobotocore FMS module

> [Index](../README.md) > [FMS](./README.md) > FMSClient

Auto-generated documentation for
[FMS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
type annotations stubs module
[types-aiobotocore-fms](https://pypi.org/project/types-aiobotocore-fms/).

- [FMSClient for aiobotocore FMS module](#fmsclient-for-aiobotocore-fms-module)
  - [FMSClient](#fmsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_admin_account](#associate_admin_account)
    - [can_paginate](#can_paginate)
    - [delete_apps_list](#delete_apps_list)
    - [delete_notification_channel](#delete_notification_channel)
    - [delete_policy](#delete_policy)
    - [delete_protocols_list](#delete_protocols_list)
    - [disassociate_admin_account](#disassociate_admin_account)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_admin_account](#get_admin_account)
    - [get_apps_list](#get_apps_list)
    - [get_compliance_detail](#get_compliance_detail)
    - [get_notification_channel](#get_notification_channel)
    - [get_policy](#get_policy)
    - [get_protection_status](#get_protection_status)
    - [get_protocols_list](#get_protocols_list)
    - [get_violation_details](#get_violation_details)
    - [list_apps_lists](#list_apps_lists)
    - [list_compliance_status](#list_compliance_status)
    - [list_member_accounts](#list_member_accounts)
    - [list_policies](#list_policies)
    - [list_protocols_lists](#list_protocols_lists)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_apps_list](#put_apps_list)
    - [put_notification_channel](#put_notification_channel)
    - [put_policy](#put_policy)
    - [put_protocols_list](#put_protocols_list)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="fmsclient"></a>

## FMSClient

Type annotations for `session.create_client("fms")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_fms.client import FMSClient

session = get_session()
async with session.create_client("fms") as client:
    client: FMSClient
```

Boto3 documentation:
[FMS.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_fms.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InternalErrorException`
- `Exceptions.InvalidInputException`
- `Exceptions.InvalidOperationException`
- `Exceptions.InvalidTypeException`
- `Exceptions.LimitExceededException`
- `Exceptions.ResourceNotFoundException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

FMSClient exceptions.

Type annotations for `session.create_client("fms").exceptions` method.

Boto3 documentation:
[FMS.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate\_admin\_account"></a>

### associate_admin_account

Sets the Firewall Manager administrator account.

Type annotations for `session.create_client("fms").associate_admin_account`
method.

Boto3 documentation:
[FMS.Client.associate_admin_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.associate_admin_account)

Asynchronous method. Use `await associate_admin_account(...)` for a synchronous
call.

Arguments mapping described in
[AssociateAdminAccountRequestRequestTypeDef](./type_defs.md#associateadminaccountrequestrequesttypedef).

Keyword-only arguments:

- `AdminAccount`: `str` *(required)*

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("fms").can_paginate` method.

Boto3 documentation:
[FMS.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="delete\_apps\_list"></a>

### delete_apps_list

Permanently deletes an Firewall Manager applications list.

Type annotations for `session.create_client("fms").delete_apps_list` method.

Boto3 documentation:
[FMS.Client.delete_apps_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.delete_apps_list)

Asynchronous method. Use `await delete_apps_list(...)` for a synchronous call.

Arguments mapping described in
[DeleteAppsListRequestRequestTypeDef](./type_defs.md#deleteappslistrequestrequesttypedef).

Keyword-only arguments:

- `ListId`: `str` *(required)*

<a id="delete\_notification\_channel"></a>

### delete_notification_channel

Deletes an Firewall Manager association with the IAM role and the Amazon Simple
Notification Service (SNS) topic that is used to record Firewall Manager SNS
logs.

Type annotations for `session.create_client("fms").delete_notification_channel`
method.

Boto3 documentation:
[FMS.Client.delete_notification_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.delete_notification_channel)

Asynchronous method. Use `await delete_notification_channel(...)` for a
synchronous call.

<a id="delete\_policy"></a>

### delete_policy

Permanently deletes an Firewall Manager policy.

Type annotations for `session.create_client("fms").delete_policy` method.

Boto3 documentation:
[FMS.Client.delete_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.delete_policy)

Asynchronous method. Use `await delete_policy(...)` for a synchronous call.

Arguments mapping described in
[DeletePolicyRequestRequestTypeDef](./type_defs.md#deletepolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*
- `DeleteAllPolicyResources`: `bool`

<a id="delete\_protocols\_list"></a>

### delete_protocols_list

Permanently deletes an Firewall Manager protocols list.

Type annotations for `session.create_client("fms").delete_protocols_list`
method.

Boto3 documentation:
[FMS.Client.delete_protocols_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.delete_protocols_list)

Asynchronous method. Use `await delete_protocols_list(...)` for a synchronous
call.

Arguments mapping described in
[DeleteProtocolsListRequestRequestTypeDef](./type_defs.md#deleteprotocolslistrequestrequesttypedef).

Keyword-only arguments:

- `ListId`: `str` *(required)*

<a id="disassociate\_admin\_account"></a>

### disassociate_admin_account

Disassociates the account that has been set as the Firewall Manager
administrator account.

Type annotations for `session.create_client("fms").disassociate_admin_account`
method.

Boto3 documentation:
[FMS.Client.disassociate_admin_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.disassociate_admin_account)

Asynchronous method. Use `await disassociate_admin_account(...)` for a
synchronous call.

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("fms").generate_presigned_url`
method.

Boto3 documentation:
[FMS.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_admin\_account"></a>

### get_admin_account

Returns the Organizations account that is associated with Firewall Manager as
the Firewall Manager administrator.

Type annotations for `session.create_client("fms").get_admin_account` method.

Boto3 documentation:
[FMS.Client.get_admin_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_admin_account)

Asynchronous method. Use `await get_admin_account(...)` for a synchronous call.

Returns a `Coroutine` for
[GetAdminAccountResponseTypeDef](./type_defs.md#getadminaccountresponsetypedef).

<a id="get\_apps\_list"></a>

### get_apps_list

Returns information about the specified Firewall Manager applications list.

Type annotations for `session.create_client("fms").get_apps_list` method.

Boto3 documentation:
[FMS.Client.get_apps_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_apps_list)

Asynchronous method. Use `await get_apps_list(...)` for a synchronous call.

Arguments mapping described in
[GetAppsListRequestRequestTypeDef](./type_defs.md#getappslistrequestrequesttypedef).

Keyword-only arguments:

- `ListId`: `str` *(required)*
- `DefaultList`: `bool`

Returns a `Coroutine` for
[GetAppsListResponseTypeDef](./type_defs.md#getappslistresponsetypedef).

<a id="get\_compliance\_detail"></a>

### get_compliance_detail

Returns detailed compliance information about the specified member account.

Type annotations for `session.create_client("fms").get_compliance_detail`
method.

Boto3 documentation:
[FMS.Client.get_compliance_detail](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_compliance_detail)

Asynchronous method. Use `await get_compliance_detail(...)` for a synchronous
call.

Arguments mapping described in
[GetComplianceDetailRequestRequestTypeDef](./type_defs.md#getcompliancedetailrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*
- `MemberAccount`: `str` *(required)*

Returns a `Coroutine` for
[GetComplianceDetailResponseTypeDef](./type_defs.md#getcompliancedetailresponsetypedef).

<a id="get\_notification\_channel"></a>

### get_notification_channel

Information about the Amazon Simple Notification Service (SNS) topic that is
used to record Firewall Manager SNS logs.

Type annotations for `session.create_client("fms").get_notification_channel`
method.

Boto3 documentation:
[FMS.Client.get_notification_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_notification_channel)

Asynchronous method. Use `await get_notification_channel(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetNotificationChannelResponseTypeDef](./type_defs.md#getnotificationchannelresponsetypedef).

<a id="get\_policy"></a>

### get_policy

Returns information about the specified Firewall Manager policy.

Type annotations for `session.create_client("fms").get_policy` method.

Boto3 documentation:
[FMS.Client.get_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_policy)

Asynchronous method. Use `await get_policy(...)` for a synchronous call.

Arguments mapping described in
[GetPolicyRequestRequestTypeDef](./type_defs.md#getpolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*

Returns a `Coroutine` for
[GetPolicyResponseTypeDef](./type_defs.md#getpolicyresponsetypedef).

<a id="get\_protection\_status"></a>

### get_protection_status

If you created a Shield Advanced policy, returns policy-level attack summary
information in the event of a potential DDoS attack.

Type annotations for `session.create_client("fms").get_protection_status`
method.

Boto3 documentation:
[FMS.Client.get_protection_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_protection_status)

Asynchronous method. Use `await get_protection_status(...)` for a synchronous
call.

Arguments mapping described in
[GetProtectionStatusRequestRequestTypeDef](./type_defs.md#getprotectionstatusrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*
- `MemberAccountId`: `str`
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetProtectionStatusResponseTypeDef](./type_defs.md#getprotectionstatusresponsetypedef).

<a id="get\_protocols\_list"></a>

### get_protocols_list

Returns information about the specified Firewall Manager protocols list.

Type annotations for `session.create_client("fms").get_protocols_list` method.

Boto3 documentation:
[FMS.Client.get_protocols_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_protocols_list)

Asynchronous method. Use `await get_protocols_list(...)` for a synchronous
call.

Arguments mapping described in
[GetProtocolsListRequestRequestTypeDef](./type_defs.md#getprotocolslistrequestrequesttypedef).

Keyword-only arguments:

- `ListId`: `str` *(required)*
- `DefaultList`: `bool`

Returns a `Coroutine` for
[GetProtocolsListResponseTypeDef](./type_defs.md#getprotocolslistresponsetypedef).

<a id="get\_violation\_details"></a>

### get_violation_details

Retrieves violations for a resource based on the specified Firewall Manager
policy and Amazon Web Services account.

Type annotations for `session.create_client("fms").get_violation_details`
method.

Boto3 documentation:
[FMS.Client.get_violation_details](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_violation_details)

Asynchronous method. Use `await get_violation_details(...)` for a synchronous
call.

Arguments mapping described in
[GetViolationDetailsRequestRequestTypeDef](./type_defs.md#getviolationdetailsrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*
- `MemberAccount`: `str` *(required)*
- `ResourceId`: `str` *(required)*
- `ResourceType`: `str` *(required)*

Returns a `Coroutine` for
[GetViolationDetailsResponseTypeDef](./type_defs.md#getviolationdetailsresponsetypedef).

<a id="list\_apps\_lists"></a>

### list_apps_lists

Returns an array of `AppsListDataSummary` objects.

Type annotations for `session.create_client("fms").list_apps_lists` method.

Boto3 documentation:
[FMS.Client.list_apps_lists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_apps_lists)

Asynchronous method. Use `await list_apps_lists(...)` for a synchronous call.

Arguments mapping described in
[ListAppsListsRequestRequestTypeDef](./type_defs.md#listappslistsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int` *(required)*
- `DefaultLists`: `bool`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAppsListsResponseTypeDef](./type_defs.md#listappslistsresponsetypedef).

<a id="list\_compliance\_status"></a>

### list_compliance_status

Returns an array of `PolicyComplianceStatus` objects.

Type annotations for `session.create_client("fms").list_compliance_status`
method.

Boto3 documentation:
[FMS.Client.list_compliance_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_compliance_status)

Asynchronous method. Use `await list_compliance_status(...)` for a synchronous
call.

Arguments mapping described in
[ListComplianceStatusRequestRequestTypeDef](./type_defs.md#listcompliancestatusrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListComplianceStatusResponseTypeDef](./type_defs.md#listcompliancestatusresponsetypedef).

<a id="list\_member\_accounts"></a>

### list_member_accounts

Returns a `MemberAccounts` object that lists the member accounts in the
administrator's Amazon Web Services organization.

Type annotations for `session.create_client("fms").list_member_accounts`
method.

Boto3 documentation:
[FMS.Client.list_member_accounts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_member_accounts)

Asynchronous method. Use `await list_member_accounts(...)` for a synchronous
call.

Arguments mapping described in
[ListMemberAccountsRequestRequestTypeDef](./type_defs.md#listmemberaccountsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListMemberAccountsResponseTypeDef](./type_defs.md#listmemberaccountsresponsetypedef).

<a id="list\_policies"></a>

### list_policies

Returns an array of `PolicySummary` objects.

Type annotations for `session.create_client("fms").list_policies` method.

Boto3 documentation:
[FMS.Client.list_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_policies)

Asynchronous method. Use `await list_policies(...)` for a synchronous call.

Arguments mapping described in
[ListPoliciesRequestRequestTypeDef](./type_defs.md#listpoliciesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListPoliciesResponseTypeDef](./type_defs.md#listpoliciesresponsetypedef).

<a id="list\_protocols\_lists"></a>

### list_protocols_lists

Returns an array of `ProtocolsListDataSummary` objects.

Type annotations for `session.create_client("fms").list_protocols_lists`
method.

Boto3 documentation:
[FMS.Client.list_protocols_lists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_protocols_lists)

Asynchronous method. Use `await list_protocols_lists(...)` for a synchronous
call.

Arguments mapping described in
[ListProtocolsListsRequestRequestTypeDef](./type_defs.md#listprotocolslistsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int` *(required)*
- `DefaultLists`: `bool`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListProtocolsListsResponseTypeDef](./type_defs.md#listprotocolslistsresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Retrieves the list of tags for the specified Amazon Web Services resource.

Type annotations for `session.create_client("fms").list_tags_for_resource`
method.

Boto3 documentation:
[FMS.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put\_apps\_list"></a>

### put_apps_list

Creates an Firewall Manager applications list.

Type annotations for `session.create_client("fms").put_apps_list` method.

Boto3 documentation:
[FMS.Client.put_apps_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_apps_list)

Asynchronous method. Use `await put_apps_list(...)` for a synchronous call.

Arguments mapping described in
[PutAppsListRequestRequestTypeDef](./type_defs.md#putappslistrequestrequesttypedef).

Keyword-only arguments:

- `AppsList`: [AppsListDataTypeDef](./type_defs.md#appslistdatatypedef)
  *(required)*
- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[PutAppsListResponseTypeDef](./type_defs.md#putappslistresponsetypedef).

<a id="put\_notification\_channel"></a>

### put_notification_channel

Designates the IAM role and Amazon Simple Notification Service (SNS) topic that
Firewall Manager uses to record SNS logs.

Type annotations for `session.create_client("fms").put_notification_channel`
method.

Boto3 documentation:
[FMS.Client.put_notification_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_notification_channel)

Asynchronous method. Use `await put_notification_channel(...)` for a
synchronous call.

Arguments mapping described in
[PutNotificationChannelRequestRequestTypeDef](./type_defs.md#putnotificationchannelrequestrequesttypedef).

Keyword-only arguments:

- `SnsTopicArn`: `str` *(required)*
- `SnsRoleName`: `str` *(required)*

<a id="put\_policy"></a>

### put_policy

Creates an Firewall Manager policy.

Type annotations for `session.create_client("fms").put_policy` method.

Boto3 documentation:
[FMS.Client.put_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_policy)

Asynchronous method. Use `await put_policy(...)` for a synchronous call.

Arguments mapping described in
[PutPolicyRequestRequestTypeDef](./type_defs.md#putpolicyrequestrequesttypedef).

Keyword-only arguments:

- `Policy`: [PolicyTypeDef](./type_defs.md#policytypedef) *(required)*
- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[PutPolicyResponseTypeDef](./type_defs.md#putpolicyresponsetypedef).

<a id="put\_protocols\_list"></a>

### put_protocols_list

Creates an Firewall Manager protocols list.

Type annotations for `session.create_client("fms").put_protocols_list` method.

Boto3 documentation:
[FMS.Client.put_protocols_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_protocols_list)

Asynchronous method. Use `await put_protocols_list(...)` for a synchronous
call.

Arguments mapping described in
[PutProtocolsListRequestRequestTypeDef](./type_defs.md#putprotocolslistrequestrequesttypedef).

Keyword-only arguments:

- `ProtocolsList`:
  [ProtocolsListDataTypeDef](./type_defs.md#protocolslistdatatypedef)
  *(required)*
- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[PutProtocolsListResponseTypeDef](./type_defs.md#putprotocolslistresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Adds one or more tags to an Amazon Web Services resource.

Type annotations for `session.create_client("fms").tag_resource` method.

Boto3 documentation:
[FMS.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Removes one or more tags from an Amazon Web Services resource.

Type annotations for `session.create_client("fms").untag_resource` method.

Boto3 documentation:
[FMS.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("fms").__aenter__` method.

Boto3 documentation:
[FMS.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [FMSClient](#fmsclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("fms").__aexit__` method.

Boto3 documentation:
[FMS.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("fms").get_paginator` method with
overloads.

- `client.get_paginator("list_apps_lists")` ->
  [ListAppsListsPaginator](./paginators.md#listappslistspaginator)
- `client.get_paginator("list_compliance_status")` ->
  [ListComplianceStatusPaginator](./paginators.md#listcompliancestatuspaginator)
- `client.get_paginator("list_member_accounts")` ->
  [ListMemberAccountsPaginator](./paginators.md#listmemberaccountspaginator)
- `client.get_paginator("list_policies")` ->
  [ListPoliciesPaginator](./paginators.md#listpoliciespaginator)
- `client.get_paginator("list_protocols_lists")` ->
  [ListProtocolsListsPaginator](./paginators.md#listprotocolslistspaginator)
