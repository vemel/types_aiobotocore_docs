<a id="ramclient-for-aiobotocore-ram-module"></a>

# RAMClient for aiobotocore RAM module

> [Index](../README.md) > [RAM](./README.md) > RAMClient

Auto-generated documentation for
[RAM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
type annotations stubs module
[types-aiobotocore-ram](https://pypi.org/project/types-aiobotocore-ram/).

- [RAMClient for aiobotocore RAM module](#ramclient-for-aiobotocore-ram-module)
  - [RAMClient](#ramclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_resource_share_invitation](#accept_resource_share_invitation)
    - [associate_resource_share](#associate_resource_share)
    - [associate_resource_share_permission](#associate_resource_share_permission)
    - [can_paginate](#can_paginate)
    - [create_resource_share](#create_resource_share)
    - [delete_resource_share](#delete_resource_share)
    - [disassociate_resource_share](#disassociate_resource_share)
    - [disassociate_resource_share_permission](#disassociate_resource_share_permission)
    - [enable_sharing_with_aws_organization](#enable_sharing_with_aws_organization)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_permission](#get_permission)
    - [get_resource_policies](#get_resource_policies)
    - [get_resource_share_associations](#get_resource_share_associations)
    - [get_resource_share_invitations](#get_resource_share_invitations)
    - [get_resource_shares](#get_resource_shares)
    - [list_pending_invitation_resources](#list_pending_invitation_resources)
    - [list_permission_versions](#list_permission_versions)
    - [list_permissions](#list_permissions)
    - [list_principals](#list_principals)
    - [list_resource_share_permissions](#list_resource_share_permissions)
    - [list_resource_types](#list_resource_types)
    - [list_resources](#list_resources)
    - [promote_resource_share_created_from_policy](#promote_resource_share_created_from_policy)
    - [reject_resource_share_invitation](#reject_resource_share_invitation)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_resource_share](#update_resource_share)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="ramclient"></a>

## RAMClient

Type annotations for `session.create_client("ram")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_ram.client import RAMClient

session = get_session()
async with session.create_client("ram") as client:
    client: RAMClient
```

Boto3 documentation:
[RAM.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ram.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.IdempotentParameterMismatchException`
- `Exceptions.InvalidClientTokenException`
- `Exceptions.InvalidMaxResultsException`
- `Exceptions.InvalidNextTokenException`
- `Exceptions.InvalidParameterException`
- `Exceptions.InvalidResourceTypeException`
- `Exceptions.InvalidStateTransitionException`
- `Exceptions.MalformedArnException`
- `Exceptions.MissingRequiredParameterException`
- `Exceptions.OperationNotPermittedException`
- `Exceptions.ResourceArnNotFoundException`
- `Exceptions.ResourceShareInvitationAlreadyAcceptedException`
- `Exceptions.ResourceShareInvitationAlreadyRejectedException`
- `Exceptions.ResourceShareInvitationArnNotFoundException`
- `Exceptions.ResourceShareInvitationExpiredException`
- `Exceptions.ResourceShareLimitExceededException`
- `Exceptions.ServerInternalException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.TagLimitExceededException`
- `Exceptions.TagPolicyViolationException`
- `Exceptions.ThrottlingException`
- `Exceptions.UnknownResourceException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

RAMClient exceptions.

Type annotations for `session.create_client("ram").exceptions` method.

Boto3 documentation:
[RAM.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept\_resource\_share\_invitation"></a>

### accept_resource_share_invitation

Accepts an invitation to a resource share from another Amazon Web Services
account.

Type annotations for
`session.create_client("ram").accept_resource_share_invitation` method.

Boto3 documentation:
[RAM.Client.accept_resource_share_invitation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.accept_resource_share_invitation)

Asynchronous method. Use `await accept_resource_share_invitation(...)` for a
synchronous call.

Arguments mapping described in
[AcceptResourceShareInvitationRequestRequestTypeDef](./type_defs.md#acceptresourceshareinvitationrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareInvitationArn`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[AcceptResourceShareInvitationResponseTypeDef](./type_defs.md#acceptresourceshareinvitationresponsetypedef).

<a id="associate\_resource\_share"></a>

### associate_resource_share

Adds the specified list of principals and list of resources to a resource
share.

Type annotations for `session.create_client("ram").associate_resource_share`
method.

Boto3 documentation:
[RAM.Client.associate_resource_share](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.associate_resource_share)

Asynchronous method. Use `await associate_resource_share(...)` for a
synchronous call.

Arguments mapping described in
[AssociateResourceShareRequestRequestTypeDef](./type_defs.md#associateresourcesharerequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `resourceArns`: `Sequence`\[`str`\]
- `principals`: `Sequence`\[`str`\]
- `clientToken`: `str`

Returns a `Coroutine` for
[AssociateResourceShareResponseTypeDef](./type_defs.md#associateresourceshareresponsetypedef).

<a id="associate\_resource\_share\_permission"></a>

### associate_resource_share_permission

Adds or replaces the RAM permission for a resource type included in a resource
share.

Type annotations for
`session.create_client("ram").associate_resource_share_permission` method.

Boto3 documentation:
[RAM.Client.associate_resource_share_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.associate_resource_share_permission)

Asynchronous method. Use `await associate_resource_share_permission(...)` for a
synchronous call.

Arguments mapping described in
[AssociateResourceSharePermissionRequestRequestTypeDef](./type_defs.md#associateresourcesharepermissionrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `permissionArn`: `str` *(required)*
- `replace`: `bool`
- `clientToken`: `str`
- `permissionVersion`: `int`

Returns a `Coroutine` for
[AssociateResourceSharePermissionResponseTypeDef](./type_defs.md#associateresourcesharepermissionresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("ram").can_paginate` method.

Boto3 documentation:
[RAM.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_resource\_share"></a>

### create_resource_share

Creates a resource share.

Type annotations for `session.create_client("ram").create_resource_share`
method.

Boto3 documentation:
[RAM.Client.create_resource_share](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.create_resource_share)

Asynchronous method. Use `await create_resource_share(...)` for a synchronous
call.

Arguments mapping described in
[CreateResourceShareRequestRequestTypeDef](./type_defs.md#createresourcesharerequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `resourceArns`: `Sequence`\[`str`\]
- `principals`: `Sequence`\[`str`\]
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `allowExternalPrincipals`: `bool`
- `clientToken`: `str`
- `permissionArns`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[CreateResourceShareResponseTypeDef](./type_defs.md#createresourceshareresponsetypedef).

<a id="delete\_resource\_share"></a>

### delete_resource_share

Deletes the specified resource share.

Type annotations for `session.create_client("ram").delete_resource_share`
method.

Boto3 documentation:
[RAM.Client.delete_resource_share](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.delete_resource_share)

Asynchronous method. Use `await delete_resource_share(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResourceShareRequestRequestTypeDef](./type_defs.md#deleteresourcesharerequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[DeleteResourceShareResponseTypeDef](./type_defs.md#deleteresourceshareresponsetypedef).

<a id="disassociate\_resource\_share"></a>

### disassociate_resource_share

Disassociates the specified principals or resources from the specified resource
share.

Type annotations for `session.create_client("ram").disassociate_resource_share`
method.

Boto3 documentation:
[RAM.Client.disassociate_resource_share](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.disassociate_resource_share)

Asynchronous method. Use `await disassociate_resource_share(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateResourceShareRequestRequestTypeDef](./type_defs.md#disassociateresourcesharerequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `resourceArns`: `Sequence`\[`str`\]
- `principals`: `Sequence`\[`str`\]
- `clientToken`: `str`

Returns a `Coroutine` for
[DisassociateResourceShareResponseTypeDef](./type_defs.md#disassociateresourceshareresponsetypedef).

<a id="disassociate\_resource\_share\_permission"></a>

### disassociate_resource_share_permission

Disassociates an RAM permission from a resource share.

Type annotations for
`session.create_client("ram").disassociate_resource_share_permission` method.

Boto3 documentation:
[RAM.Client.disassociate_resource_share_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.disassociate_resource_share_permission)

Asynchronous method. Use `await disassociate_resource_share_permission(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateResourceSharePermissionRequestRequestTypeDef](./type_defs.md#disassociateresourcesharepermissionrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `permissionArn`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[DisassociateResourceSharePermissionResponseTypeDef](./type_defs.md#disassociateresourcesharepermissionresponsetypedef).

<a id="enable\_sharing\_with\_aws\_organization"></a>

### enable_sharing_with_aws_organization

Enables resource sharing within your organization in Organizations.

Type annotations for
`session.create_client("ram").enable_sharing_with_aws_organization` method.

Boto3 documentation:
[RAM.Client.enable_sharing_with_aws_organization](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.enable_sharing_with_aws_organization)

Asynchronous method. Use `await enable_sharing_with_aws_organization(...)` for
a synchronous call.

Returns a `Coroutine` for
[EnableSharingWithAwsOrganizationResponseTypeDef](./type_defs.md#enablesharingwithawsorganizationresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("ram").generate_presigned_url`
method.

Boto3 documentation:
[RAM.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_permission"></a>

### get_permission

Gets the contents of an RAM permission in JSON format.

Type annotations for `session.create_client("ram").get_permission` method.

Boto3 documentation:
[RAM.Client.get_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_permission)

Asynchronous method. Use `await get_permission(...)` for a synchronous call.

Arguments mapping described in
[GetPermissionRequestRequestTypeDef](./type_defs.md#getpermissionrequestrequesttypedef).

Keyword-only arguments:

- `permissionArn`: `str` *(required)*
- `permissionVersion`: `int`

Returns a `Coroutine` for
[GetPermissionResponseTypeDef](./type_defs.md#getpermissionresponsetypedef).

<a id="get\_resource\_policies"></a>

### get_resource_policies

Retrieves the resource policies for the specified resources that you own and
have shared.

Type annotations for `session.create_client("ram").get_resource_policies`
method.

Boto3 documentation:
[RAM.Client.get_resource_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_policies)

Asynchronous method. Use `await get_resource_policies(...)` for a synchronous
call.

Arguments mapping described in
[GetResourcePoliciesRequestRequestTypeDef](./type_defs.md#getresourcepoliciesrequestrequesttypedef).

Keyword-only arguments:

- `resourceArns`: `Sequence`\[`str`\] *(required)*
- `principal`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetResourcePoliciesResponseTypeDef](./type_defs.md#getresourcepoliciesresponsetypedef).

<a id="get\_resource\_share\_associations"></a>

### get_resource_share_associations

Retrieves the resource and principal associations for resource shares that you
own.

Type annotations for
`session.create_client("ram").get_resource_share_associations` method.

Boto3 documentation:
[RAM.Client.get_resource_share_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_share_associations)

Asynchronous method. Use `await get_resource_share_associations(...)` for a
synchronous call.

Arguments mapping described in
[GetResourceShareAssociationsRequestRequestTypeDef](./type_defs.md#getresourceshareassociationsrequestrequesttypedef).

Keyword-only arguments:

- `associationType`:
  [ResourceShareAssociationTypeType](./literals.md#resourceshareassociationtypetype)
  *(required)*
- `resourceShareArns`: `Sequence`\[`str`\]
- `resourceArn`: `str`
- `principal`: `str`
- `associationStatus`:
  [ResourceShareAssociationStatusType](./literals.md#resourceshareassociationstatustype)
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetResourceShareAssociationsResponseTypeDef](./type_defs.md#getresourceshareassociationsresponsetypedef).

<a id="get\_resource\_share\_invitations"></a>

### get_resource_share_invitations

Retrieves details about invitations that you have received for resource shares.

Type annotations for
`session.create_client("ram").get_resource_share_invitations` method.

Boto3 documentation:
[RAM.Client.get_resource_share_invitations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_share_invitations)

Asynchronous method. Use `await get_resource_share_invitations(...)` for a
synchronous call.

Arguments mapping described in
[GetResourceShareInvitationsRequestRequestTypeDef](./type_defs.md#getresourceshareinvitationsrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareInvitationArns`: `Sequence`\[`str`\]
- `resourceShareArns`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetResourceShareInvitationsResponseTypeDef](./type_defs.md#getresourceshareinvitationsresponsetypedef).

<a id="get\_resource\_shares"></a>

### get_resource_shares

Retrieves details about the resource shares that you own or that are shared
with you.

Type annotations for `session.create_client("ram").get_resource_shares` method.

Boto3 documentation:
[RAM.Client.get_resource_shares](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_shares)

Asynchronous method. Use `await get_resource_shares(...)` for a synchronous
call.

Arguments mapping described in
[GetResourceSharesRequestRequestTypeDef](./type_defs.md#getresourcesharesrequestrequesttypedef).

Keyword-only arguments:

- `resourceOwner`: [ResourceOwnerType](./literals.md#resourceownertype)
  *(required)*
- `resourceShareArns`: `Sequence`\[`str`\]
- `resourceShareStatus`:
  [ResourceShareStatusType](./literals.md#resourcesharestatustype)
- `name`: `str`
- `tagFilters`:
  `Sequence`\[[TagFilterTypeDef](./type_defs.md#tagfiltertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`
- `permissionArn`: `str`

Returns a `Coroutine` for
[GetResourceSharesResponseTypeDef](./type_defs.md#getresourcesharesresponsetypedef).

<a id="list\_pending\_invitation\_resources"></a>

### list_pending_invitation_resources

Lists the resources in a resource share that is shared with you but for which
the invitation is still `PENDING`.

Type annotations for
`session.create_client("ram").list_pending_invitation_resources` method.

Boto3 documentation:
[RAM.Client.list_pending_invitation_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_pending_invitation_resources)

Asynchronous method. Use `await list_pending_invitation_resources(...)` for a
synchronous call.

Arguments mapping described in
[ListPendingInvitationResourcesRequestRequestTypeDef](./type_defs.md#listpendinginvitationresourcesrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareInvitationArn`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`
- `resourceRegionScope`:
  [ResourceRegionScopeFilterType](./literals.md#resourceregionscopefiltertype)

Returns a `Coroutine` for
[ListPendingInvitationResourcesResponseTypeDef](./type_defs.md#listpendinginvitationresourcesresponsetypedef).

<a id="list\_permission\_versions"></a>

### list_permission_versions

Lists the available versions of the specified RAM permission.

Type annotations for `session.create_client("ram").list_permission_versions`
method.

Boto3 documentation:
[RAM.Client.list_permission_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permission_versions)

Asynchronous method. Use `await list_permission_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListPermissionVersionsRequestRequestTypeDef](./type_defs.md#listpermissionversionsrequestrequesttypedef).

Keyword-only arguments:

- `permissionArn`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListPermissionVersionsResponseTypeDef](./type_defs.md#listpermissionversionsresponsetypedef).

<a id="list\_permissions"></a>

### list_permissions

Retrieves a list of available RAM permissions that you can use for the
supported resource types.

Type annotations for `session.create_client("ram").list_permissions` method.

Boto3 documentation:
[RAM.Client.list_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permissions)

Asynchronous method. Use `await list_permissions(...)` for a synchronous call.

Arguments mapping described in
[ListPermissionsRequestRequestTypeDef](./type_defs.md#listpermissionsrequestrequesttypedef).

Keyword-only arguments:

- `resourceType`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListPermissionsResponseTypeDef](./type_defs.md#listpermissionsresponsetypedef).

<a id="list\_principals"></a>

### list_principals

Lists the principals that you are sharing resources with or that are sharing
resources with you.

Type annotations for `session.create_client("ram").list_principals` method.

Boto3 documentation:
[RAM.Client.list_principals](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_principals)

Asynchronous method. Use `await list_principals(...)` for a synchronous call.

Arguments mapping described in
[ListPrincipalsRequestRequestTypeDef](./type_defs.md#listprincipalsrequestrequesttypedef).

Keyword-only arguments:

- `resourceOwner`: [ResourceOwnerType](./literals.md#resourceownertype)
  *(required)*
- `resourceArn`: `str`
- `principals`: `Sequence`\[`str`\]
- `resourceType`: `str`
- `resourceShareArns`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListPrincipalsResponseTypeDef](./type_defs.md#listprincipalsresponsetypedef).

<a id="list\_resource\_share\_permissions"></a>

### list_resource_share_permissions

Lists the RAM permissions that are associated with a resource share.

Type annotations for
`session.create_client("ram").list_resource_share_permissions` method.

Boto3 documentation:
[RAM.Client.list_resource_share_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_resource_share_permissions)

Asynchronous method. Use `await list_resource_share_permissions(...)` for a
synchronous call.

Arguments mapping described in
[ListResourceSharePermissionsRequestRequestTypeDef](./type_defs.md#listresourcesharepermissionsrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListResourceSharePermissionsResponseTypeDef](./type_defs.md#listresourcesharepermissionsresponsetypedef).

<a id="list\_resource\_types"></a>

### list_resource_types

Lists the resource types that can be shared by RAM.

Type annotations for `session.create_client("ram").list_resource_types` method.

Boto3 documentation:
[RAM.Client.list_resource_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_resource_types)

Asynchronous method. Use `await list_resource_types(...)` for a synchronous
call.

Arguments mapping described in
[ListResourceTypesRequestRequestTypeDef](./type_defs.md#listresourcetypesrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `resourceRegionScope`:
  [ResourceRegionScopeFilterType](./literals.md#resourceregionscopefiltertype)

Returns a `Coroutine` for
[ListResourceTypesResponseTypeDef](./type_defs.md#listresourcetypesresponsetypedef).

<a id="list\_resources"></a>

### list_resources

Lists the resources that you added to a resource shares or the resources that
are shared with you.

Type annotations for `session.create_client("ram").list_resources` method.

Boto3 documentation:
[RAM.Client.list_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_resources)

Asynchronous method. Use `await list_resources(...)` for a synchronous call.

Arguments mapping described in
[ListResourcesRequestRequestTypeDef](./type_defs.md#listresourcesrequestrequesttypedef).

Keyword-only arguments:

- `resourceOwner`: [ResourceOwnerType](./literals.md#resourceownertype)
  *(required)*
- `principal`: `str`
- `resourceType`: `str`
- `resourceArns`: `Sequence`\[`str`\]
- `resourceShareArns`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`
- `resourceRegionScope`:
  [ResourceRegionScopeFilterType](./literals.md#resourceregionscopefiltertype)

Returns a `Coroutine` for
[ListResourcesResponseTypeDef](./type_defs.md#listresourcesresponsetypedef).

<a id="promote\_resource\_share\_created\_from\_policy"></a>

### promote_resource_share_created_from_policy

When you attach a resource-based permission policy to a resource, it
automatically creates a resource share.

Type annotations for
`session.create_client("ram").promote_resource_share_created_from_policy`
method.

Boto3 documentation:
[RAM.Client.promote_resource_share_created_from_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.promote_resource_share_created_from_policy)

Asynchronous method. Use
`await promote_resource_share_created_from_policy(...)` for a synchronous call.

Arguments mapping described in
[PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef](./type_defs.md#promoteresourcesharecreatedfrompolicyrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*

Returns a `Coroutine` for
[PromoteResourceShareCreatedFromPolicyResponseTypeDef](./type_defs.md#promoteresourcesharecreatedfrompolicyresponsetypedef).

<a id="reject\_resource\_share\_invitation"></a>

### reject_resource_share_invitation

Rejects an invitation to a resource share from another Amazon Web Services
account.

Type annotations for
`session.create_client("ram").reject_resource_share_invitation` method.

Boto3 documentation:
[RAM.Client.reject_resource_share_invitation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.reject_resource_share_invitation)

Asynchronous method. Use `await reject_resource_share_invitation(...)` for a
synchronous call.

Arguments mapping described in
[RejectResourceShareInvitationRequestRequestTypeDef](./type_defs.md#rejectresourceshareinvitationrequestrequesttypedef).

Keyword-only arguments:

- `resourceShareInvitationArn`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[RejectResourceShareInvitationResponseTypeDef](./type_defs.md#rejectresourceshareinvitationresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Adds the specified tag keys and values to the specified resource share.

Type annotations for `session.create_client("ram").tag_resource` method.

Boto3 documentation:
[RAM.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Removes the specified tag key and value pairs from the specified resource
share.

Type annotations for `session.create_client("ram").untag_resource` method.

Boto3 documentation:
[RAM.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_resource\_share"></a>

### update_resource_share

Modifies some of the properties of the specified resource share.

Type annotations for `session.create_client("ram").update_resource_share`
method.

Boto3 documentation:
[RAM.Client.update_resource_share](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.update_resource_share)

Asynchronous method. Use `await update_resource_share(...)` for a synchronous
call.

Arguments mapping described in
[UpdateResourceShareRequestRequestTypeDef](./type_defs.md#updateresourcesharerequestrequesttypedef).

Keyword-only arguments:

- `resourceShareArn`: `str` *(required)*
- `name`: `str`
- `allowExternalPrincipals`: `bool`
- `clientToken`: `str`

Returns a `Coroutine` for
[UpdateResourceShareResponseTypeDef](./type_defs.md#updateresourceshareresponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("ram").__aenter__` method.

Boto3 documentation:
[RAM.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [RAMClient](#ramclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("ram").__aexit__` method.

Boto3 documentation:
[RAM.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("ram").get_paginator` method with
overloads.

- `client.get_paginator("get_resource_policies")` ->
  [GetResourcePoliciesPaginator](./paginators.md#getresourcepoliciespaginator)
- `client.get_paginator("get_resource_share_associations")` ->
  [GetResourceShareAssociationsPaginator](./paginators.md#getresourceshareassociationspaginator)
- `client.get_paginator("get_resource_share_invitations")` ->
  [GetResourceShareInvitationsPaginator](./paginators.md#getresourceshareinvitationspaginator)
- `client.get_paginator("get_resource_shares")` ->
  [GetResourceSharesPaginator](./paginators.md#getresourcesharespaginator)
- `client.get_paginator("list_principals")` ->
  [ListPrincipalsPaginator](./paginators.md#listprincipalspaginator)
- `client.get_paginator("list_resources")` ->
  [ListResourcesPaginator](./paginators.md#listresourcespaginator)
