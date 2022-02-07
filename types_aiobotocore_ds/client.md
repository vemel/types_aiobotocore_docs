<a id="directoryserviceclient-for-aiobotocore-directoryservice-module"></a>

# DirectoryServiceClient for aiobotocore DirectoryService module

> [Index](..) > [DirectoryService](.) > DirectoryServiceClient

Auto-generated documentation for
[DirectoryService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService)
type annotations stubs module
[types-aiobotocore-ds](https://pypi.org/project/types-aiobotocore-ds/).

- [DirectoryServiceClient for aiobotocore DirectoryService module](#directoryserviceclient-for-aiobotocore-directoryservice-module)
  - [DirectoryServiceClient](#directoryserviceclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_shared_directory](#accept_shared_directory)
    - [add_ip_routes](#add_ip_routes)
    - [add_region](#add_region)
    - [add_tags_to_resource](#add_tags_to_resource)
    - [can_paginate](#can_paginate)
    - [cancel_schema_extension](#cancel_schema_extension)
    - [connect_directory](#connect_directory)
    - [create_alias](#create_alias)
    - [create_computer](#create_computer)
    - [create_conditional_forwarder](#create_conditional_forwarder)
    - [create_directory](#create_directory)
    - [create_log_subscription](#create_log_subscription)
    - [create_microsoft_ad](#create_microsoft_ad)
    - [create_snapshot](#create_snapshot)
    - [create_trust](#create_trust)
    - [delete_conditional_forwarder](#delete_conditional_forwarder)
    - [delete_directory](#delete_directory)
    - [delete_log_subscription](#delete_log_subscription)
    - [delete_snapshot](#delete_snapshot)
    - [delete_trust](#delete_trust)
    - [deregister_certificate](#deregister_certificate)
    - [deregister_event_topic](#deregister_event_topic)
    - [describe_certificate](#describe_certificate)
    - [describe_client_authentication_settings](#describe_client_authentication_settings)
    - [describe_conditional_forwarders](#describe_conditional_forwarders)
    - [describe_directories](#describe_directories)
    - [describe_domain_controllers](#describe_domain_controllers)
    - [describe_event_topics](#describe_event_topics)
    - [describe_ldaps_settings](#describe_ldaps_settings)
    - [describe_regions](#describe_regions)
    - [describe_shared_directories](#describe_shared_directories)
    - [describe_snapshots](#describe_snapshots)
    - [describe_trusts](#describe_trusts)
    - [disable_client_authentication](#disable_client_authentication)
    - [disable_ldaps](#disable_ldaps)
    - [disable_radius](#disable_radius)
    - [disable_sso](#disable_sso)
    - [enable_client_authentication](#enable_client_authentication)
    - [enable_ldaps](#enable_ldaps)
    - [enable_radius](#enable_radius)
    - [enable_sso](#enable_sso)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_directory_limits](#get_directory_limits)
    - [get_snapshot_limits](#get_snapshot_limits)
    - [list_certificates](#list_certificates)
    - [list_ip_routes](#list_ip_routes)
    - [list_log_subscriptions](#list_log_subscriptions)
    - [list_schema_extensions](#list_schema_extensions)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [register_certificate](#register_certificate)
    - [register_event_topic](#register_event_topic)
    - [reject_shared_directory](#reject_shared_directory)
    - [remove_ip_routes](#remove_ip_routes)
    - [remove_region](#remove_region)
    - [remove_tags_from_resource](#remove_tags_from_resource)
    - [reset_user_password](#reset_user_password)
    - [restore_from_snapshot](#restore_from_snapshot)
    - [share_directory](#share_directory)
    - [start_schema_extension](#start_schema_extension)
    - [unshare_directory](#unshare_directory)
    - [update_conditional_forwarder](#update_conditional_forwarder)
    - [update_number_of_domain_controllers](#update_number_of_domain_controllers)
    - [update_radius](#update_radius)
    - [update_trust](#update_trust)
    - [verify_trust](#verify_trust)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="directoryserviceclient"></a>

## DirectoryServiceClient

Type annotations for `session.create_client("ds")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_ds.client import DirectoryServiceClient

session = get_session()
async with session.create_client("ds") as client:
    client: DirectoryServiceClient
```

Boto3 documentation:
[DirectoryService.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ds.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.AuthenticationFailedException`
- `Exceptions.CertificateAlreadyExistsException`
- `Exceptions.CertificateDoesNotExistException`
- `Exceptions.CertificateInUseException`
- `Exceptions.CertificateLimitExceededException`
- `Exceptions.ClientError`
- `Exceptions.ClientException`
- `Exceptions.DirectoryAlreadyInRegionException`
- `Exceptions.DirectoryAlreadySharedException`
- `Exceptions.DirectoryDoesNotExistException`
- `Exceptions.DirectoryLimitExceededException`
- `Exceptions.DirectoryNotSharedException`
- `Exceptions.DirectoryUnavailableException`
- `Exceptions.DomainControllerLimitExceededException`
- `Exceptions.EntityAlreadyExistsException`
- `Exceptions.EntityDoesNotExistException`
- `Exceptions.InsufficientPermissionsException`
- `Exceptions.InvalidCertificateException`
- `Exceptions.InvalidClientAuthStatusException`
- `Exceptions.InvalidLDAPSStatusException`
- `Exceptions.InvalidNextTokenException`
- `Exceptions.InvalidParameterException`
- `Exceptions.InvalidPasswordException`
- `Exceptions.InvalidTargetException`
- `Exceptions.IpRouteLimitExceededException`
- `Exceptions.NoAvailableCertificateException`
- `Exceptions.OrganizationsException`
- `Exceptions.RegionLimitExceededException`
- `Exceptions.ServiceException`
- `Exceptions.ShareLimitExceededException`
- `Exceptions.SnapshotLimitExceededException`
- `Exceptions.TagLimitExceededException`
- `Exceptions.UnsupportedOperationException`
- `Exceptions.UserDoesNotExistException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

DirectoryServiceClient exceptions.

Type annotations for `session.create_client("ds").exceptions` method.

Boto3 documentation:
[DirectoryService.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept_shared_directory"></a>

### accept_shared_directory

Accepts a directory sharing request that was sent from the directory owner
account.

Type annotations for `session.create_client("ds").accept_shared_directory`
method.

Boto3 documentation:
[DirectoryService.Client.accept_shared_directory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.accept_shared_directory)

Asynchronous method. Use `await accept_shared_directory(...)` for a synchronous
call.

Arguments mapping described in
[AcceptSharedDirectoryRequestRequestTypeDef](./type_defs.md#acceptshareddirectoryrequestrequesttypedef).

Keyword-only arguments:

- `SharedDirectoryId`: `str` *(required)*

Returns a `Coroutine` for
[AcceptSharedDirectoryResultTypeDef](./type_defs.md#acceptshareddirectoryresulttypedef).

<a id="add_ip_routes"></a>

### add_ip_routes

If the DNS server for your self-managed domain uses a publicly addressable IP
address, you must add a CIDR address block to correctly route traffic to and
from your Microsoft AD on Amazon Web Services.

Type annotations for `session.create_client("ds").add_ip_routes` method.

Boto3 documentation:
[DirectoryService.Client.add_ip_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.add_ip_routes)

Asynchronous method. Use `await add_ip_routes(...)` for a synchronous call.

Arguments mapping described in
[AddIpRoutesRequestRequestTypeDef](./type_defs.md#addiproutesrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `IpRoutes`: `Sequence`\[[IpRouteTypeDef](./type_defs.md#iproutetypedef)\]
  *(required)*
- `UpdateSecurityGroupForDirectoryControllers`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="add_region"></a>

### add_region

Adds two domain controllers in the specified Region for the specified
directory.

Type annotations for `session.create_client("ds").add_region` method.

Boto3 documentation:
[DirectoryService.Client.add_region](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.add_region)

Asynchronous method. Use `await add_region(...)` for a synchronous call.

Arguments mapping described in
[AddRegionRequestRequestTypeDef](./type_defs.md#addregionrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RegionName`: `str` *(required)*
- `VPCSettings`:
  [DirectoryVpcSettingsTypeDef](./type_defs.md#directoryvpcsettingstypedef)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="add_tags_to_resource"></a>

### add_tags_to_resource

Adds or overwrites one or more tags for the specified directory.

Type annotations for `session.create_client("ds").add_tags_to_resource` method.

Boto3 documentation:
[DirectoryService.Client.add_tags_to_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.add_tags_to_resource)

Asynchronous method. Use `await add_tags_to_resource(...)` for a synchronous
call.

Arguments mapping described in
[AddTagsToResourceRequestRequestTypeDef](./type_defs.md#addtagstoresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("ds").can_paginate` method.

Boto3 documentation:
[DirectoryService.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="cancel_schema_extension"></a>

### cancel_schema_extension

Cancels an in-progress schema extension to a Microsoft AD directory.

Type annotations for `session.create_client("ds").cancel_schema_extension`
method.

Boto3 documentation:
[DirectoryService.Client.cancel_schema_extension](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.cancel_schema_extension)

Asynchronous method. Use `await cancel_schema_extension(...)` for a synchronous
call.

Arguments mapping described in
[CancelSchemaExtensionRequestRequestTypeDef](./type_defs.md#cancelschemaextensionrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `SchemaExtensionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="connect_directory"></a>

### connect_directory

Creates an AD Connector to connect to a self-managed directory.

Type annotations for `session.create_client("ds").connect_directory` method.

Boto3 documentation:
[DirectoryService.Client.connect_directory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.connect_directory)

Asynchronous method. Use `await connect_directory(...)` for a synchronous call.

Arguments mapping described in
[ConnectDirectoryRequestRequestTypeDef](./type_defs.md#connectdirectoryrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Password`: `str` *(required)*
- `Size`: [DirectorySizeType](./literals.md#directorysizetype) *(required)*
- `ConnectSettings`:
  [DirectoryConnectSettingsTypeDef](./type_defs.md#directoryconnectsettingstypedef)
  *(required)*
- `ShortName`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[ConnectDirectoryResultTypeDef](./type_defs.md#connectdirectoryresulttypedef).

<a id="create_alias"></a>

### create_alias

Creates an alias for a directory and assigns the alias to the directory.

Type annotations for `session.create_client("ds").create_alias` method.

Boto3 documentation:
[DirectoryService.Client.create_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_alias)

Asynchronous method. Use `await create_alias(...)` for a synchronous call.

Arguments mapping described in
[CreateAliasRequestRequestTypeDef](./type_defs.md#createaliasrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Alias`: `str` *(required)*

Returns a `Coroutine` for
[CreateAliasResultTypeDef](./type_defs.md#createaliasresulttypedef).

<a id="create_computer"></a>

### create_computer

Creates an Active Directory computer object in the specified directory.

Type annotations for `session.create_client("ds").create_computer` method.

Boto3 documentation:
[DirectoryService.Client.create_computer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_computer)

Asynchronous method. Use `await create_computer(...)` for a synchronous call.

Arguments mapping described in
[CreateComputerRequestRequestTypeDef](./type_defs.md#createcomputerrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `ComputerName`: `str` *(required)*
- `Password`: `str` *(required)*
- `OrganizationalUnitDistinguishedName`: `str`
- `ComputerAttributes`:
  `Sequence`\[[AttributeTypeDef](./type_defs.md#attributetypedef)\]

Returns a `Coroutine` for
[CreateComputerResultTypeDef](./type_defs.md#createcomputerresulttypedef).

<a id="create_conditional_forwarder"></a>

### create_conditional_forwarder

Creates a conditional forwarder associated with your Amazon Web Services
directory.

Type annotations for `session.create_client("ds").create_conditional_forwarder`
method.

Boto3 documentation:
[DirectoryService.Client.create_conditional_forwarder](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_conditional_forwarder)

Asynchronous method. Use `await create_conditional_forwarder(...)` for a
synchronous call.

Arguments mapping described in
[CreateConditionalForwarderRequestRequestTypeDef](./type_defs.md#createconditionalforwarderrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RemoteDomainName`: `str` *(required)*
- `DnsIpAddrs`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_directory"></a>

### create_directory

Creates a Simple AD directory.

Type annotations for `session.create_client("ds").create_directory` method.

Boto3 documentation:
[DirectoryService.Client.create_directory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_directory)

Asynchronous method. Use `await create_directory(...)` for a synchronous call.

Arguments mapping described in
[CreateDirectoryRequestRequestTypeDef](./type_defs.md#createdirectoryrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Password`: `str` *(required)*
- `Size`: [DirectorySizeType](./literals.md#directorysizetype) *(required)*
- `ShortName`: `str`
- `Description`: `str`
- `VpcSettings`:
  [DirectoryVpcSettingsTypeDef](./type_defs.md#directoryvpcsettingstypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDirectoryResultTypeDef](./type_defs.md#createdirectoryresulttypedef).

<a id="create_log_subscription"></a>

### create_log_subscription

Creates a subscription to forward real-time Directory Service domain controller
security logs to the specified Amazon CloudWatch log group in your Amazon Web
Services account.

Type annotations for `session.create_client("ds").create_log_subscription`
method.

Boto3 documentation:
[DirectoryService.Client.create_log_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_log_subscription)

Asynchronous method. Use `await create_log_subscription(...)` for a synchronous
call.

Arguments mapping described in
[CreateLogSubscriptionRequestRequestTypeDef](./type_defs.md#createlogsubscriptionrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `LogGroupName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_microsoft_ad"></a>

### create_microsoft_ad

Creates a Microsoft AD directory in the Amazon Web Services Cloud.

Type annotations for `session.create_client("ds").create_microsoft_ad` method.

Boto3 documentation:
[DirectoryService.Client.create_microsoft_ad](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_microsoft_ad)

Asynchronous method. Use `await create_microsoft_ad(...)` for a synchronous
call.

Arguments mapping described in
[CreateMicrosoftADRequestRequestTypeDef](./type_defs.md#createmicrosoftadrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Password`: `str` *(required)*
- `VpcSettings`:
  [DirectoryVpcSettingsTypeDef](./type_defs.md#directoryvpcsettingstypedef)
  *(required)*
- `ShortName`: `str`
- `Description`: `str`
- `Edition`: [DirectoryEditionType](./literals.md#directoryeditiontype)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateMicrosoftADResultTypeDef](./type_defs.md#createmicrosoftadresulttypedef).

<a id="create_snapshot"></a>

### create_snapshot

Creates a snapshot of a Simple AD or Microsoft AD directory in the Amazon Web
Services cloud.

Type annotations for `session.create_client("ds").create_snapshot` method.

Boto3 documentation:
[DirectoryService.Client.create_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_snapshot)

Asynchronous method. Use `await create_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CreateSnapshotRequestRequestTypeDef](./type_defs.md#createsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for
[CreateSnapshotResultTypeDef](./type_defs.md#createsnapshotresulttypedef).

<a id="create_trust"></a>

### create_trust

Directory Service for Microsoft Active Directory allows you to configure trust
relationships.

Type annotations for `session.create_client("ds").create_trust` method.

Boto3 documentation:
[DirectoryService.Client.create_trust](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.create_trust)

Asynchronous method. Use `await create_trust(...)` for a synchronous call.

Arguments mapping described in
[CreateTrustRequestRequestTypeDef](./type_defs.md#createtrustrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RemoteDomainName`: `str` *(required)*
- `TrustPassword`: `str` *(required)*
- `TrustDirection`: [TrustDirectionType](./literals.md#trustdirectiontype)
  *(required)*
- `TrustType`: [TrustTypeType](./literals.md#trusttypetype)
- `ConditionalForwarderIpAddrs`: `Sequence`\[`str`\]
- `SelectiveAuth`: [SelectiveAuthType](./literals.md#selectiveauthtype)

Returns a `Coroutine` for
[CreateTrustResultTypeDef](./type_defs.md#createtrustresulttypedef).

<a id="delete_conditional_forwarder"></a>

### delete_conditional_forwarder

Deletes a conditional forwarder that has been set up for your Amazon Web
Services directory.

Type annotations for `session.create_client("ds").delete_conditional_forwarder`
method.

Boto3 documentation:
[DirectoryService.Client.delete_conditional_forwarder](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.delete_conditional_forwarder)

Asynchronous method. Use `await delete_conditional_forwarder(...)` for a
synchronous call.

Arguments mapping described in
[DeleteConditionalForwarderRequestRequestTypeDef](./type_defs.md#deleteconditionalforwarderrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RemoteDomainName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_directory"></a>

### delete_directory

Deletes an Directory Service directory.

Type annotations for `session.create_client("ds").delete_directory` method.

Boto3 documentation:
[DirectoryService.Client.delete_directory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.delete_directory)

Asynchronous method. Use `await delete_directory(...)` for a synchronous call.

Arguments mapping described in
[DeleteDirectoryRequestRequestTypeDef](./type_defs.md#deletedirectoryrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteDirectoryResultTypeDef](./type_defs.md#deletedirectoryresulttypedef).

<a id="delete_log_subscription"></a>

### delete_log_subscription

Deletes the specified log subscription.

Type annotations for `session.create_client("ds").delete_log_subscription`
method.

Boto3 documentation:
[DirectoryService.Client.delete_log_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.delete_log_subscription)

Asynchronous method. Use `await delete_log_subscription(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLogSubscriptionRequestRequestTypeDef](./type_defs.md#deletelogsubscriptionrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_snapshot"></a>

### delete_snapshot

Deletes a directory snapshot.

Type annotations for `session.create_client("ds").delete_snapshot` method.

Boto3 documentation:
[DirectoryService.Client.delete_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.delete_snapshot)

Asynchronous method. Use `await delete_snapshot(...)` for a synchronous call.

Arguments mapping described in
[DeleteSnapshotRequestRequestTypeDef](./type_defs.md#deletesnapshotrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteSnapshotResultTypeDef](./type_defs.md#deletesnapshotresulttypedef).

<a id="delete_trust"></a>

### delete_trust

Deletes an existing trust relationship between your Managed Microsoft AD
directory and an external domain.

Type annotations for `session.create_client("ds").delete_trust` method.

Boto3 documentation:
[DirectoryService.Client.delete_trust](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.delete_trust)

Asynchronous method. Use `await delete_trust(...)` for a synchronous call.

Arguments mapping described in
[DeleteTrustRequestRequestTypeDef](./type_defs.md#deletetrustrequestrequesttypedef).

Keyword-only arguments:

- `TrustId`: `str` *(required)*
- `DeleteAssociatedConditionalForwarder`: `bool`

Returns a `Coroutine` for
[DeleteTrustResultTypeDef](./type_defs.md#deletetrustresulttypedef).

<a id="deregister_certificate"></a>

### deregister_certificate

Deletes from the system the certificate that was registered for secure LDAP or
client certificate authentication.

Type annotations for `session.create_client("ds").deregister_certificate`
method.

Boto3 documentation:
[DirectoryService.Client.deregister_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.deregister_certificate)

Asynchronous method. Use `await deregister_certificate(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterCertificateRequestRequestTypeDef](./type_defs.md#deregistercertificaterequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `CertificateId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deregister_event_topic"></a>

### deregister_event_topic

Removes the specified directory as a publisher to the specified Amazon SNS
topic.

Type annotations for `session.create_client("ds").deregister_event_topic`
method.

Boto3 documentation:
[DirectoryService.Client.deregister_event_topic](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.deregister_event_topic)

Asynchronous method. Use `await deregister_event_topic(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterEventTopicRequestRequestTypeDef](./type_defs.md#deregistereventtopicrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `TopicName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_certificate"></a>

### describe_certificate

Displays information about the certificate registered for secure LDAP or client
certificate authentication.

Type annotations for `session.create_client("ds").describe_certificate` method.

Boto3 documentation:
[DirectoryService.Client.describe_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_certificate)

Asynchronous method. Use `await describe_certificate(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCertificateRequestRequestTypeDef](./type_defs.md#describecertificaterequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `CertificateId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeCertificateResultTypeDef](./type_defs.md#describecertificateresulttypedef).

<a id="describe_client_authentication_settings"></a>

### describe_client_authentication_settings

Retrieves information about the type of client authentication for the specified
directory, if the type is specified.

Type annotations for
`session.create_client("ds").describe_client_authentication_settings` method.

Boto3 documentation:
[DirectoryService.Client.describe_client_authentication_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_client_authentication_settings)

Asynchronous method. Use `await describe_client_authentication_settings(...)`
for a synchronous call.

Arguments mapping described in
[DescribeClientAuthenticationSettingsRequestRequestTypeDef](./type_defs.md#describeclientauthenticationsettingsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Type`: `Literal['SmartCard']` (see
  [ClientAuthenticationTypeType](./literals.md#clientauthenticationtypetype))
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[DescribeClientAuthenticationSettingsResultTypeDef](./type_defs.md#describeclientauthenticationsettingsresulttypedef).

<a id="describe_conditional_forwarders"></a>

### describe_conditional_forwarders

Obtains information about the conditional forwarders for this account.

Type annotations for
`session.create_client("ds").describe_conditional_forwarders` method.

Boto3 documentation:
[DirectoryService.Client.describe_conditional_forwarders](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_conditional_forwarders)

Asynchronous method. Use `await describe_conditional_forwarders(...)` for a
synchronous call.

Arguments mapping described in
[DescribeConditionalForwardersRequestRequestTypeDef](./type_defs.md#describeconditionalforwardersrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RemoteDomainNames`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeConditionalForwardersResultTypeDef](./type_defs.md#describeconditionalforwardersresulttypedef).

<a id="describe_directories"></a>

### describe_directories

Obtains information about the directories that belong to this account.

Type annotations for `session.create_client("ds").describe_directories` method.

Boto3 documentation:
[DirectoryService.Client.describe_directories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_directories)

Asynchronous method. Use `await describe_directories(...)` for a synchronous
call.

Arguments mapping described in
[DescribeDirectoriesRequestRequestTypeDef](./type_defs.md#describedirectoriesrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[DescribeDirectoriesResultTypeDef](./type_defs.md#describedirectoriesresulttypedef).

<a id="describe_domain_controllers"></a>

### describe_domain_controllers

Provides information about any domain controllers in your directory.

Type annotations for `session.create_client("ds").describe_domain_controllers`
method.

Boto3 documentation:
[DirectoryService.Client.describe_domain_controllers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_domain_controllers)

Asynchronous method. Use `await describe_domain_controllers(...)` for a
synchronous call.

Arguments mapping described in
[DescribeDomainControllersRequestRequestTypeDef](./type_defs.md#describedomaincontrollersrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `DomainControllerIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[DescribeDomainControllersResultTypeDef](./type_defs.md#describedomaincontrollersresulttypedef).

<a id="describe_event_topics"></a>

### describe_event_topics

Obtains information about which Amazon SNS topics receive status messages from
the specified directory.

Type annotations for `session.create_client("ds").describe_event_topics`
method.

Boto3 documentation:
[DirectoryService.Client.describe_event_topics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_event_topics)

Asynchronous method. Use `await describe_event_topics(...)` for a synchronous
call.

Arguments mapping described in
[DescribeEventTopicsRequestRequestTypeDef](./type_defs.md#describeeventtopicsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str`
- `TopicNames`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeEventTopicsResultTypeDef](./type_defs.md#describeeventtopicsresulttypedef).

<a id="describe_ldaps_settings"></a>

### describe_ldaps_settings

Describes the status of LDAP security for the specified directory.

Type annotations for `session.create_client("ds").describe_ldaps_settings`
method.

Boto3 documentation:
[DirectoryService.Client.describe_ldaps_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_ldaps_settings)

Asynchronous method. Use `await describe_ldaps_settings(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLDAPSSettingsRequestRequestTypeDef](./type_defs.md#describeldapssettingsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Type`: `Literal['Client']` (see
  [LDAPSTypeType](./literals.md#ldapstypetype))
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[DescribeLDAPSSettingsResultTypeDef](./type_defs.md#describeldapssettingsresulttypedef).

<a id="describe_regions"></a>

### describe_regions

Provides information about the Regions that are configured for multi-Region
replication.

Type annotations for `session.create_client("ds").describe_regions` method.

Boto3 documentation:
[DirectoryService.Client.describe_regions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_regions)

Asynchronous method. Use `await describe_regions(...)` for a synchronous call.

Arguments mapping described in
[DescribeRegionsRequestRequestTypeDef](./type_defs.md#describeregionsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RegionName`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeRegionsResultTypeDef](./type_defs.md#describeregionsresulttypedef).

<a id="describe_shared_directories"></a>

### describe_shared_directories

Returns the shared directories in your account.

Type annotations for `session.create_client("ds").describe_shared_directories`
method.

Boto3 documentation:
[DirectoryService.Client.describe_shared_directories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_shared_directories)

Asynchronous method. Use `await describe_shared_directories(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSharedDirectoriesRequestRequestTypeDef](./type_defs.md#describeshareddirectoriesrequestrequesttypedef).

Keyword-only arguments:

- `OwnerDirectoryId`: `str` *(required)*
- `SharedDirectoryIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[DescribeSharedDirectoriesResultTypeDef](./type_defs.md#describeshareddirectoriesresulttypedef).

<a id="describe_snapshots"></a>

### describe_snapshots

Obtains information about the directory snapshots that belong to this account.

Type annotations for `session.create_client("ds").describe_snapshots` method.

Boto3 documentation:
[DirectoryService.Client.describe_snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_snapshots)

Asynchronous method. Use `await describe_snapshots(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSnapshotsRequestRequestTypeDef](./type_defs.md#describesnapshotsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str`
- `SnapshotIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[DescribeSnapshotsResultTypeDef](./type_defs.md#describesnapshotsresulttypedef).

<a id="describe_trusts"></a>

### describe_trusts

Obtains information about the trust relationships for this account.

Type annotations for `session.create_client("ds").describe_trusts` method.

Boto3 documentation:
[DirectoryService.Client.describe_trusts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.describe_trusts)

Asynchronous method. Use `await describe_trusts(...)` for a synchronous call.

Arguments mapping described in
[DescribeTrustsRequestRequestTypeDef](./type_defs.md#describetrustsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str`
- `TrustIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[DescribeTrustsResultTypeDef](./type_defs.md#describetrustsresulttypedef).

<a id="disable_client_authentication"></a>

### disable_client_authentication

Disables alternative client authentication methods for the specified directory.

Type annotations for
`session.create_client("ds").disable_client_authentication` method.

Boto3 documentation:
[DirectoryService.Client.disable_client_authentication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.disable_client_authentication)

Asynchronous method. Use `await disable_client_authentication(...)` for a
synchronous call.

Arguments mapping described in
[DisableClientAuthenticationRequestRequestTypeDef](./type_defs.md#disableclientauthenticationrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Type`: `Literal['SmartCard']` (see
  [ClientAuthenticationTypeType](./literals.md#clientauthenticationtypetype))
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disable_ldaps"></a>

### disable_ldaps

Deactivates LDAP secure calls for the specified directory.

Type annotations for `session.create_client("ds").disable_ldaps` method.

Boto3 documentation:
[DirectoryService.Client.disable_ldaps](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.disable_ldaps)

Asynchronous method. Use `await disable_ldaps(...)` for a synchronous call.

Arguments mapping described in
[DisableLDAPSRequestRequestTypeDef](./type_defs.md#disableldapsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Type`: `Literal['Client']` (see
  [LDAPSTypeType](./literals.md#ldapstypetype)) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disable_radius"></a>

### disable_radius

Disables multi-factor authentication (MFA) with the Remote Authentication Dial
In User Service (RADIUS) server for an AD Connector or Microsoft AD directory.

Type annotations for `session.create_client("ds").disable_radius` method.

Boto3 documentation:
[DirectoryService.Client.disable_radius](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.disable_radius)

Asynchronous method. Use `await disable_radius(...)` for a synchronous call.

Arguments mapping described in
[DisableRadiusRequestRequestTypeDef](./type_defs.md#disableradiusrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disable_sso"></a>

### disable_sso

Disables single-sign on for a directory.

Type annotations for `session.create_client("ds").disable_sso` method.

Boto3 documentation:
[DirectoryService.Client.disable_sso](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.disable_sso)

Asynchronous method. Use `await disable_sso(...)` for a synchronous call.

Arguments mapping described in
[DisableSsoRequestRequestTypeDef](./type_defs.md#disablessorequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `UserName`: `str`
- `Password`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="enable_client_authentication"></a>

### enable_client_authentication

Enables alternative client authentication methods for the specified directory.

Type annotations for `session.create_client("ds").enable_client_authentication`
method.

Boto3 documentation:
[DirectoryService.Client.enable_client_authentication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.enable_client_authentication)

Asynchronous method. Use `await enable_client_authentication(...)` for a
synchronous call.

Arguments mapping described in
[EnableClientAuthenticationRequestRequestTypeDef](./type_defs.md#enableclientauthenticationrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Type`: `Literal['SmartCard']` (see
  [ClientAuthenticationTypeType](./literals.md#clientauthenticationtypetype))
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="enable_ldaps"></a>

### enable_ldaps

Activates the switch for the specific directory to always use LDAP secure
calls.

Type annotations for `session.create_client("ds").enable_ldaps` method.

Boto3 documentation:
[DirectoryService.Client.enable_ldaps](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.enable_ldaps)

Asynchronous method. Use `await enable_ldaps(...)` for a synchronous call.

Arguments mapping described in
[EnableLDAPSRequestRequestTypeDef](./type_defs.md#enableldapsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `Type`: `Literal['Client']` (see
  [LDAPSTypeType](./literals.md#ldapstypetype)) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="enable_radius"></a>

### enable_radius

Enables multi-factor authentication (MFA) with the Remote Authentication Dial
In User Service (RADIUS) server for an AD Connector or Microsoft AD directory.

Type annotations for `session.create_client("ds").enable_radius` method.

Boto3 documentation:
[DirectoryService.Client.enable_radius](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.enable_radius)

Asynchronous method. Use `await enable_radius(...)` for a synchronous call.

Arguments mapping described in
[EnableRadiusRequestRequestTypeDef](./type_defs.md#enableradiusrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RadiusSettings`:
  [RadiusSettingsTypeDef](./type_defs.md#radiussettingstypedef) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="enable_sso"></a>

### enable_sso

Enables single sign-on for a directory.

Type annotations for `session.create_client("ds").enable_sso` method.

Boto3 documentation:
[DirectoryService.Client.enable_sso](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.enable_sso)

Asynchronous method. Use `await enable_sso(...)` for a synchronous call.

Arguments mapping described in
[EnableSsoRequestRequestTypeDef](./type_defs.md#enablessorequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `UserName`: `str`
- `Password`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("ds").generate_presigned_url`
method.

Boto3 documentation:
[DirectoryService.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_directory_limits"></a>

### get_directory_limits

Obtains directory limit information for the current Region.

Type annotations for `session.create_client("ds").get_directory_limits` method.

Boto3 documentation:
[DirectoryService.Client.get_directory_limits](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.get_directory_limits)

Asynchronous method. Use `await get_directory_limits(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetDirectoryLimitsResultTypeDef](./type_defs.md#getdirectorylimitsresulttypedef).

<a id="get_snapshot_limits"></a>

### get_snapshot_limits

Obtains the manual snapshot limits for a directory.

Type annotations for `session.create_client("ds").get_snapshot_limits` method.

Boto3 documentation:
[DirectoryService.Client.get_snapshot_limits](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.get_snapshot_limits)

Asynchronous method. Use `await get_snapshot_limits(...)` for a synchronous
call.

Arguments mapping described in
[GetSnapshotLimitsRequestRequestTypeDef](./type_defs.md#getsnapshotlimitsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*

Returns a `Coroutine` for
[GetSnapshotLimitsResultTypeDef](./type_defs.md#getsnapshotlimitsresulttypedef).

<a id="list_certificates"></a>

### list_certificates

For the specified directory, lists all the certificates registered for a secure
LDAP or client certificate authentication.

Type annotations for `session.create_client("ds").list_certificates` method.

Boto3 documentation:
[DirectoryService.Client.list_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.list_certificates)

Asynchronous method. Use `await list_certificates(...)` for a synchronous call.

Arguments mapping described in
[ListCertificatesRequestRequestTypeDef](./type_defs.md#listcertificatesrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[ListCertificatesResultTypeDef](./type_defs.md#listcertificatesresulttypedef).

<a id="list_ip_routes"></a>

### list_ip_routes

Lists the address blocks that you have added to a directory.

Type annotations for `session.create_client("ds").list_ip_routes` method.

Boto3 documentation:
[DirectoryService.Client.list_ip_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.list_ip_routes)

Asynchronous method. Use `await list_ip_routes(...)` for a synchronous call.

Arguments mapping described in
[ListIpRoutesRequestRequestTypeDef](./type_defs.md#listiproutesrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[ListIpRoutesResultTypeDef](./type_defs.md#listiproutesresulttypedef).

<a id="list_log_subscriptions"></a>

### list_log_subscriptions

Lists the active log subscriptions for the Amazon Web Services account.

Type annotations for `session.create_client("ds").list_log_subscriptions`
method.

Boto3 documentation:
[DirectoryService.Client.list_log_subscriptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.list_log_subscriptions)

Asynchronous method. Use `await list_log_subscriptions(...)` for a synchronous
call.

Arguments mapping described in
[ListLogSubscriptionsRequestRequestTypeDef](./type_defs.md#listlogsubscriptionsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str`
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[ListLogSubscriptionsResultTypeDef](./type_defs.md#listlogsubscriptionsresulttypedef).

<a id="list_schema_extensions"></a>

### list_schema_extensions

Lists all schema extensions applied to a Microsoft AD Directory.

Type annotations for `session.create_client("ds").list_schema_extensions`
method.

Boto3 documentation:
[DirectoryService.Client.list_schema_extensions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.list_schema_extensions)

Asynchronous method. Use `await list_schema_extensions(...)` for a synchronous
call.

Arguments mapping described in
[ListSchemaExtensionsRequestRequestTypeDef](./type_defs.md#listschemaextensionsrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[ListSchemaExtensionsResultTypeDef](./type_defs.md#listschemaextensionsresulttypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists all tags on a directory.

Type annotations for `session.create_client("ds").list_tags_for_resource`
method.

Boto3 documentation:
[DirectoryService.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*
- `NextToken`: `str`
- `Limit`: `int`

Returns a `Coroutine` for
[ListTagsForResourceResultTypeDef](./type_defs.md#listtagsforresourceresulttypedef).

<a id="register_certificate"></a>

### register_certificate

Registers a certificate for a secure LDAP or client certificate authentication.

Type annotations for `session.create_client("ds").register_certificate` method.

Boto3 documentation:
[DirectoryService.Client.register_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.register_certificate)

Asynchronous method. Use `await register_certificate(...)` for a synchronous
call.

Arguments mapping described in
[RegisterCertificateRequestRequestTypeDef](./type_defs.md#registercertificaterequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `CertificateData`: `str` *(required)*
- `Type`: [CertificateTypeType](./literals.md#certificatetypetype)
- `ClientCertAuthSettings`:
  [ClientCertAuthSettingsTypeDef](./type_defs.md#clientcertauthsettingstypedef)

Returns a `Coroutine` for
[RegisterCertificateResultTypeDef](./type_defs.md#registercertificateresulttypedef).

<a id="register_event_topic"></a>

### register_event_topic

Associates a directory with an Amazon SNS topic.

Type annotations for `session.create_client("ds").register_event_topic` method.

Boto3 documentation:
[DirectoryService.Client.register_event_topic](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.register_event_topic)

Asynchronous method. Use `await register_event_topic(...)` for a synchronous
call.

Arguments mapping described in
[RegisterEventTopicRequestRequestTypeDef](./type_defs.md#registereventtopicrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `TopicName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="reject_shared_directory"></a>

### reject_shared_directory

Rejects a directory sharing request that was sent from the directory owner
account.

Type annotations for `session.create_client("ds").reject_shared_directory`
method.

Boto3 documentation:
[DirectoryService.Client.reject_shared_directory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.reject_shared_directory)

Asynchronous method. Use `await reject_shared_directory(...)` for a synchronous
call.

Arguments mapping described in
[RejectSharedDirectoryRequestRequestTypeDef](./type_defs.md#rejectshareddirectoryrequestrequesttypedef).

Keyword-only arguments:

- `SharedDirectoryId`: `str` *(required)*

Returns a `Coroutine` for
[RejectSharedDirectoryResultTypeDef](./type_defs.md#rejectshareddirectoryresulttypedef).

<a id="remove_ip_routes"></a>

### remove_ip_routes

Removes IP address blocks from a directory.

Type annotations for `session.create_client("ds").remove_ip_routes` method.

Boto3 documentation:
[DirectoryService.Client.remove_ip_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.remove_ip_routes)

Asynchronous method. Use `await remove_ip_routes(...)` for a synchronous call.

Arguments mapping described in
[RemoveIpRoutesRequestRequestTypeDef](./type_defs.md#removeiproutesrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `CidrIps`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="remove_region"></a>

### remove_region

Stops all replication and removes the domain controllers from the specified
Region.

Type annotations for `session.create_client("ds").remove_region` method.

Boto3 documentation:
[DirectoryService.Client.remove_region](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.remove_region)

Asynchronous method. Use `await remove_region(...)` for a synchronous call.

Arguments mapping described in
[RemoveRegionRequestRequestTypeDef](./type_defs.md#removeregionrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="remove_tags_from_resource"></a>

### remove_tags_from_resource

Removes tags from a directory.

Type annotations for `session.create_client("ds").remove_tags_from_resource`
method.

Boto3 documentation:
[DirectoryService.Client.remove_tags_from_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.remove_tags_from_resource)

Asynchronous method. Use `await remove_tags_from_resource(...)` for a
synchronous call.

Arguments mapping described in
[RemoveTagsFromResourceRequestRequestTypeDef](./type_defs.md#removetagsfromresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="reset_user_password"></a>

### reset_user_password

Resets the password for any user in your Managed Microsoft AD or Simple AD
directory.

Type annotations for `session.create_client("ds").reset_user_password` method.

Boto3 documentation:
[DirectoryService.Client.reset_user_password](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.reset_user_password)

Asynchronous method. Use `await reset_user_password(...)` for a synchronous
call.

Arguments mapping described in
[ResetUserPasswordRequestRequestTypeDef](./type_defs.md#resetuserpasswordrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `UserName`: `str` *(required)*
- `NewPassword`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="restore_from_snapshot"></a>

### restore_from_snapshot

Restores a directory using an existing directory snapshot.

Type annotations for `session.create_client("ds").restore_from_snapshot`
method.

Boto3 documentation:
[DirectoryService.Client.restore_from_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.restore_from_snapshot)

Asynchronous method. Use `await restore_from_snapshot(...)` for a synchronous
call.

Arguments mapping described in
[RestoreFromSnapshotRequestRequestTypeDef](./type_defs.md#restorefromsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="share_directory"></a>

### share_directory

Shares a specified directory (`DirectoryId` ) in your Amazon Web Services
account (directory owner) with another Amazon Web Services account (directory
consumer).

Type annotations for `session.create_client("ds").share_directory` method.

Boto3 documentation:
[DirectoryService.Client.share_directory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.share_directory)

Asynchronous method. Use `await share_directory(...)` for a synchronous call.

Arguments mapping described in
[ShareDirectoryRequestRequestTypeDef](./type_defs.md#sharedirectoryrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `ShareTarget`: [ShareTargetTypeDef](./type_defs.md#sharetargettypedef)
  *(required)*
- `ShareMethod`: [ShareMethodType](./literals.md#sharemethodtype) *(required)*
- `ShareNotes`: `str`

Returns a `Coroutine` for
[ShareDirectoryResultTypeDef](./type_defs.md#sharedirectoryresulttypedef).

<a id="start_schema_extension"></a>

### start_schema_extension

Applies a schema extension to a Microsoft AD directory.

Type annotations for `session.create_client("ds").start_schema_extension`
method.

Boto3 documentation:
[DirectoryService.Client.start_schema_extension](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.start_schema_extension)

Asynchronous method. Use `await start_schema_extension(...)` for a synchronous
call.

Arguments mapping described in
[StartSchemaExtensionRequestRequestTypeDef](./type_defs.md#startschemaextensionrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `CreateSnapshotBeforeSchemaExtension`: `bool` *(required)*
- `LdifContent`: `str` *(required)*
- `Description`: `str` *(required)*

Returns a `Coroutine` for
[StartSchemaExtensionResultTypeDef](./type_defs.md#startschemaextensionresulttypedef).

<a id="unshare_directory"></a>

### unshare_directory

Stops the directory sharing between the directory owner and consumer accounts.

Type annotations for `session.create_client("ds").unshare_directory` method.

Boto3 documentation:
[DirectoryService.Client.unshare_directory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.unshare_directory)

Asynchronous method. Use `await unshare_directory(...)` for a synchronous call.

Arguments mapping described in
[UnshareDirectoryRequestRequestTypeDef](./type_defs.md#unsharedirectoryrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `UnshareTarget`: [UnshareTargetTypeDef](./type_defs.md#unsharetargettypedef)
  *(required)*

Returns a `Coroutine` for
[UnshareDirectoryResultTypeDef](./type_defs.md#unsharedirectoryresulttypedef).

<a id="update_conditional_forwarder"></a>

### update_conditional_forwarder

Updates a conditional forwarder that has been set up for your Amazon Web
Services directory.

Type annotations for `session.create_client("ds").update_conditional_forwarder`
method.

Boto3 documentation:
[DirectoryService.Client.update_conditional_forwarder](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.update_conditional_forwarder)

Asynchronous method. Use `await update_conditional_forwarder(...)` for a
synchronous call.

Arguments mapping described in
[UpdateConditionalForwarderRequestRequestTypeDef](./type_defs.md#updateconditionalforwarderrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RemoteDomainName`: `str` *(required)*
- `DnsIpAddrs`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_number_of_domain_controllers"></a>

### update_number_of_domain_controllers

Adds or removes domain controllers to or from the directory.

Type annotations for
`session.create_client("ds").update_number_of_domain_controllers` method.

Boto3 documentation:
[DirectoryService.Client.update_number_of_domain_controllers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.update_number_of_domain_controllers)

Asynchronous method. Use `await update_number_of_domain_controllers(...)` for a
synchronous call.

Arguments mapping described in
[UpdateNumberOfDomainControllersRequestRequestTypeDef](./type_defs.md#updatenumberofdomaincontrollersrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `DesiredNumber`: `int` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_radius"></a>

### update_radius

Updates the Remote Authentication Dial In User Service (RADIUS) server
information for an AD Connector or Microsoft AD directory.

Type annotations for `session.create_client("ds").update_radius` method.

Boto3 documentation:
[DirectoryService.Client.update_radius](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.update_radius)

Asynchronous method. Use `await update_radius(...)` for a synchronous call.

Arguments mapping described in
[UpdateRadiusRequestRequestTypeDef](./type_defs.md#updateradiusrequestrequesttypedef).

Keyword-only arguments:

- `DirectoryId`: `str` *(required)*
- `RadiusSettings`:
  [RadiusSettingsTypeDef](./type_defs.md#radiussettingstypedef) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_trust"></a>

### update_trust

Updates the trust that has been set up between your Managed Microsoft AD
directory and an self-managed Active Directory.

Type annotations for `session.create_client("ds").update_trust` method.

Boto3 documentation:
[DirectoryService.Client.update_trust](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.update_trust)

Asynchronous method. Use `await update_trust(...)` for a synchronous call.

Arguments mapping described in
[UpdateTrustRequestRequestTypeDef](./type_defs.md#updatetrustrequestrequesttypedef).

Keyword-only arguments:

- `TrustId`: `str` *(required)*
- `SelectiveAuth`: [SelectiveAuthType](./literals.md#selectiveauthtype)

Returns a `Coroutine` for
[UpdateTrustResultTypeDef](./type_defs.md#updatetrustresulttypedef).

<a id="verify_trust"></a>

### verify_trust

Directory Service for Microsoft Active Directory allows you to configure and
verify trust relationships.

Type annotations for `session.create_client("ds").verify_trust` method.

Boto3 documentation:
[DirectoryService.Client.verify_trust](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.verify_trust)

Asynchronous method. Use `await verify_trust(...)` for a synchronous call.

Arguments mapping described in
[VerifyTrustRequestRequestTypeDef](./type_defs.md#verifytrustrequestrequesttypedef).

Keyword-only arguments:

- `TrustId`: `str` *(required)*

Returns a `Coroutine` for
[VerifyTrustResultTypeDef](./type_defs.md#verifytrustresulttypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("ds").__aenter__` method.

Boto3 documentation:
[DirectoryService.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [DirectoryServiceClient](#directoryserviceclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("ds").__aexit__` method.

Boto3 documentation:
[DirectoryService.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("ds").get_paginator` method with
overloads.

- `client.get_paginator("describe_directories")` ->
  [DescribeDirectoriesPaginator](./paginators.md#describedirectoriespaginator)
- `client.get_paginator("describe_domain_controllers")` ->
  [DescribeDomainControllersPaginator](./paginators.md#describedomaincontrollerspaginator)
- `client.get_paginator("describe_shared_directories")` ->
  [DescribeSharedDirectoriesPaginator](./paginators.md#describeshareddirectoriespaginator)
- `client.get_paginator("describe_snapshots")` ->
  [DescribeSnapshotsPaginator](./paginators.md#describesnapshotspaginator)
- `client.get_paginator("describe_trusts")` ->
  [DescribeTrustsPaginator](./paginators.md#describetrustspaginator)
- `client.get_paginator("list_ip_routes")` ->
  [ListIpRoutesPaginator](./paginators.md#listiproutespaginator)
- `client.get_paginator("list_log_subscriptions")` ->
  [ListLogSubscriptionsPaginator](./paginators.md#listlogsubscriptionspaginator)
- `client.get_paginator("list_schema_extensions")` ->
  [ListSchemaExtensionsPaginator](./paginators.md#listschemaextensionspaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
