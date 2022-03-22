<a id="macie2client-for-aiobotocore-macie2-module"></a>

# Macie2Client for aiobotocore Macie2 module

> [Index](../README.md) > [Macie2](./README.md) > Macie2Client

Auto-generated documentation for
[Macie2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
type annotations stubs module
[types-aiobotocore-macie2](https://pypi.org/project/types-aiobotocore-macie2/).

- [Macie2Client for aiobotocore Macie2 module](#macie2client-for-aiobotocore-macie2-module)
  - [Macie2Client](#macie2client)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_invitation](#accept_invitation)
    - [batch_get_custom_data_identifiers](#batch_get_custom_data_identifiers)
    - [can_paginate](#can_paginate)
    - [create_classification_job](#create_classification_job)
    - [create_custom_data_identifier](#create_custom_data_identifier)
    - [create_findings_filter](#create_findings_filter)
    - [create_invitations](#create_invitations)
    - [create_member](#create_member)
    - [create_sample_findings](#create_sample_findings)
    - [decline_invitations](#decline_invitations)
    - [delete_custom_data_identifier](#delete_custom_data_identifier)
    - [delete_findings_filter](#delete_findings_filter)
    - [delete_invitations](#delete_invitations)
    - [delete_member](#delete_member)
    - [describe_buckets](#describe_buckets)
    - [describe_classification_job](#describe_classification_job)
    - [describe_organization_configuration](#describe_organization_configuration)
    - [disable_macie](#disable_macie)
    - [disable_organization_admin_account](#disable_organization_admin_account)
    - [disassociate_from_administrator_account](#disassociate_from_administrator_account)
    - [disassociate_from_master_account](#disassociate_from_master_account)
    - [disassociate_member](#disassociate_member)
    - [enable_macie](#enable_macie)
    - [enable_organization_admin_account](#enable_organization_admin_account)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_administrator_account](#get_administrator_account)
    - [get_bucket_statistics](#get_bucket_statistics)
    - [get_classification_export_configuration](#get_classification_export_configuration)
    - [get_custom_data_identifier](#get_custom_data_identifier)
    - [get_finding_statistics](#get_finding_statistics)
    - [get_findings](#get_findings)
    - [get_findings_filter](#get_findings_filter)
    - [get_findings_publication_configuration](#get_findings_publication_configuration)
    - [get_invitations_count](#get_invitations_count)
    - [get_macie_session](#get_macie_session)
    - [get_master_account](#get_master_account)
    - [get_member](#get_member)
    - [get_usage_statistics](#get_usage_statistics)
    - [get_usage_totals](#get_usage_totals)
    - [list_classification_jobs](#list_classification_jobs)
    - [list_custom_data_identifiers](#list_custom_data_identifiers)
    - [list_findings](#list_findings)
    - [list_findings_filters](#list_findings_filters)
    - [list_invitations](#list_invitations)
    - [list_managed_data_identifiers](#list_managed_data_identifiers)
    - [list_members](#list_members)
    - [list_organization_admin_accounts](#list_organization_admin_accounts)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_classification_export_configuration](#put_classification_export_configuration)
    - [put_findings_publication_configuration](#put_findings_publication_configuration)
    - [search_resources](#search_resources)
    - [tag_resource](#tag_resource)
    - [test_custom_data_identifier](#test_custom_data_identifier)
    - [untag_resource](#untag_resource)
    - [update_classification_job](#update_classification_job)
    - [update_findings_filter](#update_findings_filter)
    - [update_macie_session](#update_macie_session)
    - [update_member_session](#update_member_session)
    - [update_organization_configuration](#update_organization_configuration)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="macie2client"></a>

## Macie2Client

Type annotations for `session.create_client("macie2")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_macie2.client import Macie2Client

session = get_session()
async with session.create_client("macie2") as client:
    client: Macie2Client
```

Boto3 documentation:
[Macie2.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_macie2.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

Macie2Client exceptions.

Type annotations for `session.create_client("macie2").exceptions` method.

Boto3 documentation:
[Macie2.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept\_invitation"></a>

### accept_invitation

Accepts an Amazon Macie membership invitation that was received from a specific
account.

Type annotations for `session.create_client("macie2").accept_invitation`
method.

Boto3 documentation:
[Macie2.Client.accept_invitation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.accept_invitation)

Asynchronous method. Use `await accept_invitation(...)` for a synchronous call.

Arguments mapping described in
[AcceptInvitationRequestRequestTypeDef](./type_defs.md#acceptinvitationrequestrequesttypedef).

Keyword-only arguments:

- `invitationId`: `str` *(required)*
- `administratorAccountId`: `str`
- `masterAccount`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="batch\_get\_custom\_data\_identifiers"></a>

### batch_get_custom_data_identifiers

Retrieves information about one or more custom data identifiers.

Type annotations for
`session.create_client("macie2").batch_get_custom_data_identifiers` method.

Boto3 documentation:
[Macie2.Client.batch_get_custom_data_identifiers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.batch_get_custom_data_identifiers)

Asynchronous method. Use `await batch_get_custom_data_identifiers(...)` for a
synchronous call.

Arguments mapping described in
[BatchGetCustomDataIdentifiersRequestRequestTypeDef](./type_defs.md#batchgetcustomdataidentifiersrequestrequesttypedef).

Keyword-only arguments:

- `ids`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[BatchGetCustomDataIdentifiersResponseTypeDef](./type_defs.md#batchgetcustomdataidentifiersresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("macie2").can_paginate` method.

Boto3 documentation:
[Macie2.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_classification\_job"></a>

### create_classification_job

Creates and defines the settings for a classification job.

Type annotations for
`session.create_client("macie2").create_classification_job` method.

Boto3 documentation:
[Macie2.Client.create_classification_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.create_classification_job)

Asynchronous method. Use `await create_classification_job(...)` for a
synchronous call.

Arguments mapping described in
[CreateClassificationJobRequestRequestTypeDef](./type_defs.md#createclassificationjobrequestrequesttypedef).

Keyword-only arguments:

- `clientToken`: `str` *(required)*
- `jobType`: [JobTypeType](./literals.md#jobtypetype) *(required)*
- `name`: `str` *(required)*
- `s3JobDefinition`:
  [S3JobDefinitionTypeDef](./type_defs.md#s3jobdefinitiontypedef) *(required)*
- `customDataIdentifierIds`: `Sequence`\[`str`\]
- `description`: `str`
- `initialRun`: `bool`
- `managedDataIdentifierIds`: `Sequence`\[`str`\]
- `managedDataIdentifierSelector`:
  [ManagedDataIdentifierSelectorType](./literals.md#manageddataidentifierselectortype)
- `samplingPercentage`: `int`
- `scheduleFrequency`:
  [JobScheduleFrequencyTypeDef](./type_defs.md#jobschedulefrequencytypedef)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateClassificationJobResponseTypeDef](./type_defs.md#createclassificationjobresponsetypedef).

<a id="create\_custom\_data\_identifier"></a>

### create_custom_data_identifier

Creates and defines the criteria and other settings for a custom data
identifier.

Type annotations for
`session.create_client("macie2").create_custom_data_identifier` method.

Boto3 documentation:
[Macie2.Client.create_custom_data_identifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.create_custom_data_identifier)

Asynchronous method. Use `await create_custom_data_identifier(...)` for a
synchronous call.

Arguments mapping described in
[CreateCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#createcustomdataidentifierrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `regex`: `str` *(required)*
- `clientToken`: `str`
- `description`: `str`
- `ignoreWords`: `Sequence`\[`str`\]
- `keywords`: `Sequence`\[`str`\]
- `maximumMatchDistance`: `int`
- `severityLevels`:
  `Sequence`\[[SeverityLevelTypeDef](./type_defs.md#severityleveltypedef)\]
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateCustomDataIdentifierResponseTypeDef](./type_defs.md#createcustomdataidentifierresponsetypedef).

<a id="create\_findings\_filter"></a>

### create_findings_filter

Creates and defines the criteria and other settings for a findings filter.

Type annotations for `session.create_client("macie2").create_findings_filter`
method.

Boto3 documentation:
[Macie2.Client.create_findings_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.create_findings_filter)

Asynchronous method. Use `await create_findings_filter(...)` for a synchronous
call.

Arguments mapping described in
[CreateFindingsFilterRequestRequestTypeDef](./type_defs.md#createfindingsfilterrequestrequesttypedef).

Keyword-only arguments:

- `action`: [FindingsFilterActionType](./literals.md#findingsfilteractiontype)
  *(required)*
- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef) *(required)*
- `name`: `str` *(required)*
- `clientToken`: `str`
- `description`: `str`
- `position`: `int`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateFindingsFilterResponseTypeDef](./type_defs.md#createfindingsfilterresponsetypedef).

<a id="create\_invitations"></a>

### create_invitations

Sends an Amazon Macie membership invitation to one or more accounts.

Type annotations for `session.create_client("macie2").create_invitations`
method.

Boto3 documentation:
[Macie2.Client.create_invitations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.create_invitations)

Asynchronous method. Use `await create_invitations(...)` for a synchronous
call.

Arguments mapping described in
[CreateInvitationsRequestRequestTypeDef](./type_defs.md#createinvitationsrequestrequesttypedef).

Keyword-only arguments:

- `accountIds`: `Sequence`\[`str`\] *(required)*
- `disableEmailNotification`: `bool`
- `message`: `str`

Returns a `Coroutine` for
[CreateInvitationsResponseTypeDef](./type_defs.md#createinvitationsresponsetypedef).

<a id="create\_member"></a>

### create_member

Associates an account with an Amazon Macie administrator account.

Type annotations for `session.create_client("macie2").create_member` method.

Boto3 documentation:
[Macie2.Client.create_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.create_member)

Asynchronous method. Use `await create_member(...)` for a synchronous call.

Arguments mapping described in
[CreateMemberRequestRequestTypeDef](./type_defs.md#creatememberrequestrequesttypedef).

Keyword-only arguments:

- `account`: [AccountDetailTypeDef](./type_defs.md#accountdetailtypedef)
  *(required)*
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateMemberResponseTypeDef](./type_defs.md#creatememberresponsetypedef).

<a id="create\_sample\_findings"></a>

### create_sample_findings

Creates sample findings.

Type annotations for `session.create_client("macie2").create_sample_findings`
method.

Boto3 documentation:
[Macie2.Client.create_sample_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.create_sample_findings)

Asynchronous method. Use `await create_sample_findings(...)` for a synchronous
call.

Arguments mapping described in
[CreateSampleFindingsRequestRequestTypeDef](./type_defs.md#createsamplefindingsrequestrequesttypedef).

Keyword-only arguments:

- `findingTypes`:
  `Sequence`\[[FindingTypeType](./literals.md#findingtypetype)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="decline\_invitations"></a>

### decline_invitations

Declines Amazon Macie membership invitations that were received from specific
accounts.

Type annotations for `session.create_client("macie2").decline_invitations`
method.

Boto3 documentation:
[Macie2.Client.decline_invitations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.decline_invitations)

Asynchronous method. Use `await decline_invitations(...)` for a synchronous
call.

Arguments mapping described in
[DeclineInvitationsRequestRequestTypeDef](./type_defs.md#declineinvitationsrequestrequesttypedef).

Keyword-only arguments:

- `accountIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DeclineInvitationsResponseTypeDef](./type_defs.md#declineinvitationsresponsetypedef).

<a id="delete\_custom\_data\_identifier"></a>

### delete_custom_data_identifier

Soft deletes a custom data identifier.

Type annotations for
`session.create_client("macie2").delete_custom_data_identifier` method.

Boto3 documentation:
[Macie2.Client.delete_custom_data_identifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.delete_custom_data_identifier)

Asynchronous method. Use `await delete_custom_data_identifier(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#deletecustomdataidentifierrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_findings\_filter"></a>

### delete_findings_filter

Deletes a findings filter.

Type annotations for `session.create_client("macie2").delete_findings_filter`
method.

Boto3 documentation:
[Macie2.Client.delete_findings_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.delete_findings_filter)

Asynchronous method. Use `await delete_findings_filter(...)` for a synchronous
call.

Arguments mapping described in
[DeleteFindingsFilterRequestRequestTypeDef](./type_defs.md#deletefindingsfilterrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_invitations"></a>

### delete_invitations

Deletes Amazon Macie membership invitations that were received from specific
accounts.

Type annotations for `session.create_client("macie2").delete_invitations`
method.

Boto3 documentation:
[Macie2.Client.delete_invitations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.delete_invitations)

Asynchronous method. Use `await delete_invitations(...)` for a synchronous
call.

Arguments mapping described in
[DeleteInvitationsRequestRequestTypeDef](./type_defs.md#deleteinvitationsrequestrequesttypedef).

Keyword-only arguments:

- `accountIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DeleteInvitationsResponseTypeDef](./type_defs.md#deleteinvitationsresponsetypedef).

<a id="delete\_member"></a>

### delete_member

Deletes the association between an Amazon Macie administrator account and an
account.

Type annotations for `session.create_client("macie2").delete_member` method.

Boto3 documentation:
[Macie2.Client.delete_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.delete_member)

Asynchronous method. Use `await delete_member(...)` for a synchronous call.

Arguments mapping described in
[DeleteMemberRequestRequestTypeDef](./type_defs.md#deletememberrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe\_buckets"></a>

### describe_buckets

Retrieves (queries) statistical data and other information about one or more S3
buckets that Amazon Macie monitors and analyzes.

Type annotations for `session.create_client("macie2").describe_buckets` method.

Boto3 documentation:
[Macie2.Client.describe_buckets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.describe_buckets)

Asynchronous method. Use `await describe_buckets(...)` for a synchronous call.

Arguments mapping described in
[DescribeBucketsRequestRequestTypeDef](./type_defs.md#describebucketsrequestrequesttypedef).

Keyword-only arguments:

- `criteria`: `Mapping`\[`str`,
  [BucketCriteriaAdditionalPropertiesTypeDef](./type_defs.md#bucketcriteriaadditionalpropertiestypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`:
  [BucketSortCriteriaTypeDef](./type_defs.md#bucketsortcriteriatypedef)

Returns a `Coroutine` for
[DescribeBucketsResponseTypeDef](./type_defs.md#describebucketsresponsetypedef).

<a id="describe\_classification\_job"></a>

### describe_classification_job

Retrieves the status and settings for a classification job.

Type annotations for
`session.create_client("macie2").describe_classification_job` method.

Boto3 documentation:
[Macie2.Client.describe_classification_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.describe_classification_job)

Asynchronous method. Use `await describe_classification_job(...)` for a
synchronous call.

Arguments mapping described in
[DescribeClassificationJobRequestRequestTypeDef](./type_defs.md#describeclassificationjobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeClassificationJobResponseTypeDef](./type_defs.md#describeclassificationjobresponsetypedef).

<a id="describe\_organization\_configuration"></a>

### describe_organization_configuration

Retrieves the Amazon Macie configuration settings for an organization in
Organizations.

Type annotations for
`session.create_client("macie2").describe_organization_configuration` method.

Boto3 documentation:
[Macie2.Client.describe_organization_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.describe_organization_configuration)

Asynchronous method. Use `await describe_organization_configuration(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeOrganizationConfigurationResponseTypeDef](./type_defs.md#describeorganizationconfigurationresponsetypedef).

<a id="disable\_macie"></a>

### disable_macie

Disables Amazon Macie and deletes all settings and resources for a Macie
account.

Type annotations for `session.create_client("macie2").disable_macie` method.

Boto3 documentation:
[Macie2.Client.disable_macie](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.disable_macie)

Asynchronous method. Use `await disable_macie(...)` for a synchronous call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disable\_organization\_admin\_account"></a>

### disable_organization_admin_account

Disables an account as the delegated Amazon Macie administrator account for an
organization in Organizations.

Type annotations for
`session.create_client("macie2").disable_organization_admin_account` method.

Boto3 documentation:
[Macie2.Client.disable_organization_admin_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.disable_organization_admin_account)

Asynchronous method. Use `await disable_organization_admin_account(...)` for a
synchronous call.

Arguments mapping described in
[DisableOrganizationAdminAccountRequestRequestTypeDef](./type_defs.md#disableorganizationadminaccountrequestrequesttypedef).

Keyword-only arguments:

- `adminAccountId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disassociate\_from\_administrator\_account"></a>

### disassociate_from_administrator_account

Disassociates a member account from its Amazon Macie administrator account.

Type annotations for
`session.create_client("macie2").disassociate_from_administrator_account`
method.

Boto3 documentation:
[Macie2.Client.disassociate_from_administrator_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.disassociate_from_administrator_account)

Asynchronous method. Use `await disassociate_from_administrator_account(...)`
for a synchronous call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disassociate\_from\_master\_account"></a>

### disassociate_from_master_account

(Deprecated) Disassociates a member account from its Amazon Macie administrator
account.

Type annotations for
`session.create_client("macie2").disassociate_from_master_account` method.

Boto3 documentation:
[Macie2.Client.disassociate_from_master_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.disassociate_from_master_account)

Asynchronous method. Use `await disassociate_from_master_account(...)` for a
synchronous call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disassociate\_member"></a>

### disassociate_member

Disassociates an Amazon Macie administrator account from a member account.

Type annotations for `session.create_client("macie2").disassociate_member`
method.

Boto3 documentation:
[Macie2.Client.disassociate_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.disassociate_member)

Asynchronous method. Use `await disassociate_member(...)` for a synchronous
call.

Arguments mapping described in
[DisassociateMemberRequestRequestTypeDef](./type_defs.md#disassociatememberrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="enable\_macie"></a>

### enable_macie

Enables Amazon Macie and specifies the configuration settings for a Macie
account.

Type annotations for `session.create_client("macie2").enable_macie` method.

Boto3 documentation:
[Macie2.Client.enable_macie](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.enable_macie)

Asynchronous method. Use `await enable_macie(...)` for a synchronous call.

Arguments mapping described in
[EnableMacieRequestRequestTypeDef](./type_defs.md#enablemacierequestrequesttypedef).

Keyword-only arguments:

- `clientToken`: `str`
- `findingPublishingFrequency`:
  [FindingPublishingFrequencyType](./literals.md#findingpublishingfrequencytype)
- `status`: [MacieStatusType](./literals.md#maciestatustype)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="enable\_organization\_admin\_account"></a>

### enable_organization_admin_account

Designates an account as the delegated Amazon Macie administrator account for
an organization in Organizations.

Type annotations for
`session.create_client("macie2").enable_organization_admin_account` method.

Boto3 documentation:
[Macie2.Client.enable_organization_admin_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.enable_organization_admin_account)

Asynchronous method. Use `await enable_organization_admin_account(...)` for a
synchronous call.

Arguments mapping described in
[EnableOrganizationAdminAccountRequestRequestTypeDef](./type_defs.md#enableorganizationadminaccountrequestrequesttypedef).

Keyword-only arguments:

- `adminAccountId`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("macie2").generate_presigned_url`
method.

Boto3 documentation:
[Macie2.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_administrator\_account"></a>

### get_administrator_account

Retrieves information about the Amazon Macie administrator account for an
account.

Type annotations for
`session.create_client("macie2").get_administrator_account` method.

Boto3 documentation:
[Macie2.Client.get_administrator_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_administrator_account)

Asynchronous method. Use `await get_administrator_account(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetAdministratorAccountResponseTypeDef](./type_defs.md#getadministratoraccountresponsetypedef).

<a id="get\_bucket\_statistics"></a>

### get_bucket_statistics

Retrieves (queries) aggregated statistical data about S3 buckets that Amazon
Macie monitors and analyzes.

Type annotations for `session.create_client("macie2").get_bucket_statistics`
method.

Boto3 documentation:
[Macie2.Client.get_bucket_statistics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_bucket_statistics)

Asynchronous method. Use `await get_bucket_statistics(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketStatisticsRequestRequestTypeDef](./type_defs.md#getbucketstatisticsrequestrequesttypedef).

Keyword-only arguments:

- `accountId`: `str`

Returns a `Coroutine` for
[GetBucketStatisticsResponseTypeDef](./type_defs.md#getbucketstatisticsresponsetypedef).

<a id="get\_classification\_export\_configuration"></a>

### get_classification_export_configuration

Retrieves the configuration settings for storing data classification results.

Type annotations for
`session.create_client("macie2").get_classification_export_configuration`
method.

Boto3 documentation:
[Macie2.Client.get_classification_export_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_classification_export_configuration)

Asynchronous method. Use `await get_classification_export_configuration(...)`
for a synchronous call.

Returns a `Coroutine` for
[GetClassificationExportConfigurationResponseTypeDef](./type_defs.md#getclassificationexportconfigurationresponsetypedef).

<a id="get\_custom\_data\_identifier"></a>

### get_custom_data_identifier

Retrieves the criteria and other settings for a custom data identifier.

Type annotations for
`session.create_client("macie2").get_custom_data_identifier` method.

Boto3 documentation:
[Macie2.Client.get_custom_data_identifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_custom_data_identifier)

Asynchronous method. Use `await get_custom_data_identifier(...)` for a
synchronous call.

Arguments mapping described in
[GetCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#getcustomdataidentifierrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetCustomDataIdentifierResponseTypeDef](./type_defs.md#getcustomdataidentifierresponsetypedef).

<a id="get\_finding\_statistics"></a>

### get_finding_statistics

Retrieves (queries) aggregated statistical data about findings.

Type annotations for `session.create_client("macie2").get_finding_statistics`
method.

Boto3 documentation:
[Macie2.Client.get_finding_statistics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_finding_statistics)

Asynchronous method. Use `await get_finding_statistics(...)` for a synchronous
call.

Arguments mapping described in
[GetFindingStatisticsRequestRequestTypeDef](./type_defs.md#getfindingstatisticsrequestrequesttypedef).

Keyword-only arguments:

- `groupBy`: [GroupByType](./literals.md#groupbytype) *(required)*
- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `size`: `int`
- `sortCriteria`:
  [FindingStatisticsSortCriteriaTypeDef](./type_defs.md#findingstatisticssortcriteriatypedef)

Returns a `Coroutine` for
[GetFindingStatisticsResponseTypeDef](./type_defs.md#getfindingstatisticsresponsetypedef).

<a id="get\_findings"></a>

### get_findings

Retrieves the details of one or more findings.

Type annotations for `session.create_client("macie2").get_findings` method.

Boto3 documentation:
[Macie2.Client.get_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_findings)

Asynchronous method. Use `await get_findings(...)` for a synchronous call.

Arguments mapping described in
[GetFindingsRequestRequestTypeDef](./type_defs.md#getfindingsrequestrequesttypedef).

Keyword-only arguments:

- `findingIds`: `Sequence`\[`str`\] *(required)*
- `sortCriteria`: [SortCriteriaTypeDef](./type_defs.md#sortcriteriatypedef)

Returns a `Coroutine` for
[GetFindingsResponseTypeDef](./type_defs.md#getfindingsresponsetypedef).

<a id="get\_findings\_filter"></a>

### get_findings_filter

Retrieves the criteria and other settings for a findings filter.

Type annotations for `session.create_client("macie2").get_findings_filter`
method.

Boto3 documentation:
[Macie2.Client.get_findings_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_findings_filter)

Asynchronous method. Use `await get_findings_filter(...)` for a synchronous
call.

Arguments mapping described in
[GetFindingsFilterRequestRequestTypeDef](./type_defs.md#getfindingsfilterrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetFindingsFilterResponseTypeDef](./type_defs.md#getfindingsfilterresponsetypedef).

<a id="get\_findings\_publication\_configuration"></a>

### get_findings_publication_configuration

Retrieves the configuration settings for publishing findings to Security Hub.

Type annotations for
`session.create_client("macie2").get_findings_publication_configuration`
method.

Boto3 documentation:
[Macie2.Client.get_findings_publication_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_findings_publication_configuration)

Asynchronous method. Use `await get_findings_publication_configuration(...)`
for a synchronous call.

Returns a `Coroutine` for
[GetFindingsPublicationConfigurationResponseTypeDef](./type_defs.md#getfindingspublicationconfigurationresponsetypedef).

<a id="get\_invitations\_count"></a>

### get_invitations_count

Retrieves the count of Amazon Macie membership invitations that were received
by an account.

Type annotations for `session.create_client("macie2").get_invitations_count`
method.

Boto3 documentation:
[Macie2.Client.get_invitations_count](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_invitations_count)

Asynchronous method. Use `await get_invitations_count(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetInvitationsCountResponseTypeDef](./type_defs.md#getinvitationscountresponsetypedef).

<a id="get\_macie\_session"></a>

### get_macie_session

Retrieves the current status and configuration settings for an Amazon Macie
account.

Type annotations for `session.create_client("macie2").get_macie_session`
method.

Boto3 documentation:
[Macie2.Client.get_macie_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_macie_session)

Asynchronous method. Use `await get_macie_session(...)` for a synchronous call.

Returns a `Coroutine` for
[GetMacieSessionResponseTypeDef](./type_defs.md#getmaciesessionresponsetypedef).

<a id="get\_master\_account"></a>

### get_master_account

(Deprecated) Retrieves information about the Amazon Macie administrator account
for an account.

Type annotations for `session.create_client("macie2").get_master_account`
method.

Boto3 documentation:
[Macie2.Client.get_master_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_master_account)

Asynchronous method. Use `await get_master_account(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetMasterAccountResponseTypeDef](./type_defs.md#getmasteraccountresponsetypedef).

<a id="get\_member"></a>

### get_member

Retrieves information about an account that's associated with an Amazon Macie
administrator account.

Type annotations for `session.create_client("macie2").get_member` method.

Boto3 documentation:
[Macie2.Client.get_member](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_member)

Asynchronous method. Use `await get_member(...)` for a synchronous call.

Arguments mapping described in
[GetMemberRequestRequestTypeDef](./type_defs.md#getmemberrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetMemberResponseTypeDef](./type_defs.md#getmemberresponsetypedef).

<a id="get\_usage\_statistics"></a>

### get_usage_statistics

Retrieves (queries) quotas and aggregated usage data for one or more accounts.

Type annotations for `session.create_client("macie2").get_usage_statistics`
method.

Boto3 documentation:
[Macie2.Client.get_usage_statistics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_usage_statistics)

Asynchronous method. Use `await get_usage_statistics(...)` for a synchronous
call.

Arguments mapping described in
[GetUsageStatisticsRequestRequestTypeDef](./type_defs.md#getusagestatisticsrequestrequesttypedef).

Keyword-only arguments:

- `filterBy`:
  `Sequence`\[[UsageStatisticsFilterTypeDef](./type_defs.md#usagestatisticsfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `sortBy`:
  [UsageStatisticsSortByTypeDef](./type_defs.md#usagestatisticssortbytypedef)
- `timeRange`: [TimeRangeType](./literals.md#timerangetype)

Returns a `Coroutine` for
[GetUsageStatisticsResponseTypeDef](./type_defs.md#getusagestatisticsresponsetypedef).

<a id="get\_usage\_totals"></a>

### get_usage_totals

Retrieves (queries) aggregated usage data for an account.

Type annotations for `session.create_client("macie2").get_usage_totals` method.

Boto3 documentation:
[Macie2.Client.get_usage_totals](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.get_usage_totals)

Asynchronous method. Use `await get_usage_totals(...)` for a synchronous call.

Arguments mapping described in
[GetUsageTotalsRequestRequestTypeDef](./type_defs.md#getusagetotalsrequestrequesttypedef).

Keyword-only arguments:

- `timeRange`: `str`

Returns a `Coroutine` for
[GetUsageTotalsResponseTypeDef](./type_defs.md#getusagetotalsresponsetypedef).

<a id="list\_classification\_jobs"></a>

### list_classification_jobs

Retrieves a subset of information about one or more classification jobs.

Type annotations for `session.create_client("macie2").list_classification_jobs`
method.

Boto3 documentation:
[Macie2.Client.list_classification_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_classification_jobs)

Asynchronous method. Use `await list_classification_jobs(...)` for a
synchronous call.

Arguments mapping described in
[ListClassificationJobsRequestRequestTypeDef](./type_defs.md#listclassificationjobsrequestrequesttypedef).

Keyword-only arguments:

- `filterCriteria`:
  [ListJobsFilterCriteriaTypeDef](./type_defs.md#listjobsfiltercriteriatypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`:
  [ListJobsSortCriteriaTypeDef](./type_defs.md#listjobssortcriteriatypedef)

Returns a `Coroutine` for
[ListClassificationJobsResponseTypeDef](./type_defs.md#listclassificationjobsresponsetypedef).

<a id="list\_custom\_data\_identifiers"></a>

### list_custom_data_identifiers

Retrieves a subset of information about all the custom data identifiers for an
account.

Type annotations for
`session.create_client("macie2").list_custom_data_identifiers` method.

Boto3 documentation:
[Macie2.Client.list_custom_data_identifiers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_custom_data_identifiers)

Asynchronous method. Use `await list_custom_data_identifiers(...)` for a
synchronous call.

Arguments mapping described in
[ListCustomDataIdentifiersRequestRequestTypeDef](./type_defs.md#listcustomdataidentifiersrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListCustomDataIdentifiersResponseTypeDef](./type_defs.md#listcustomdataidentifiersresponsetypedef).

<a id="list\_findings"></a>

### list_findings

Retrieves a subset of information about one or more findings.

Type annotations for `session.create_client("macie2").list_findings` method.

Boto3 documentation:
[Macie2.Client.list_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_findings)

Asynchronous method. Use `await list_findings(...)` for a synchronous call.

Arguments mapping described in
[ListFindingsRequestRequestTypeDef](./type_defs.md#listfindingsrequestrequesttypedef).

Keyword-only arguments:

- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`: [SortCriteriaTypeDef](./type_defs.md#sortcriteriatypedef)

Returns a `Coroutine` for
[ListFindingsResponseTypeDef](./type_defs.md#listfindingsresponsetypedef).

<a id="list\_findings\_filters"></a>

### list_findings_filters

Retrieves a subset of information about all the findings filters for an
account.

Type annotations for `session.create_client("macie2").list_findings_filters`
method.

Boto3 documentation:
[Macie2.Client.list_findings_filters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_findings_filters)

Asynchronous method. Use `await list_findings_filters(...)` for a synchronous
call.

Arguments mapping described in
[ListFindingsFiltersRequestRequestTypeDef](./type_defs.md#listfindingsfiltersrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListFindingsFiltersResponseTypeDef](./type_defs.md#listfindingsfiltersresponsetypedef).

<a id="list\_invitations"></a>

### list_invitations

Retrieves information about the Amazon Macie membership invitations that were
received by an account.

Type annotations for `session.create_client("macie2").list_invitations` method.

Boto3 documentation:
[Macie2.Client.list_invitations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_invitations)

Asynchronous method. Use `await list_invitations(...)` for a synchronous call.

Arguments mapping described in
[ListInvitationsRequestRequestTypeDef](./type_defs.md#listinvitationsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListInvitationsResponseTypeDef](./type_defs.md#listinvitationsresponsetypedef).

<a id="list\_managed\_data\_identifiers"></a>

### list_managed_data_identifiers

Retrieves information about all the managed data identifiers that Amazon Macie
currently provides.

Type annotations for
`session.create_client("macie2").list_managed_data_identifiers` method.

Boto3 documentation:
[Macie2.Client.list_managed_data_identifiers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_managed_data_identifiers)

Asynchronous method. Use `await list_managed_data_identifiers(...)` for a
synchronous call.

Arguments mapping described in
[ListManagedDataIdentifiersRequestRequestTypeDef](./type_defs.md#listmanageddataidentifiersrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`

Returns a `Coroutine` for
[ListManagedDataIdentifiersResponseTypeDef](./type_defs.md#listmanageddataidentifiersresponsetypedef).

<a id="list\_members"></a>

### list_members

Retrieves information about the accounts that are associated with an Amazon
Macie administrator account.

Type annotations for `session.create_client("macie2").list_members` method.

Boto3 documentation:
[Macie2.Client.list_members](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_members)

Asynchronous method. Use `await list_members(...)` for a synchronous call.

Arguments mapping described in
[ListMembersRequestRequestTypeDef](./type_defs.md#listmembersrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`
- `onlyAssociated`: `str`

Returns a `Coroutine` for
[ListMembersResponseTypeDef](./type_defs.md#listmembersresponsetypedef).

<a id="list\_organization\_admin\_accounts"></a>

### list_organization_admin_accounts

Retrieves information about the delegated Amazon Macie administrator account
for an organization in Organizations.

Type annotations for
`session.create_client("macie2").list_organization_admin_accounts` method.

Boto3 documentation:
[Macie2.Client.list_organization_admin_accounts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_organization_admin_accounts)

Asynchronous method. Use `await list_organization_admin_accounts(...)` for a
synchronous call.

Arguments mapping described in
[ListOrganizationAdminAccountsRequestRequestTypeDef](./type_defs.md#listorganizationadminaccountsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListOrganizationAdminAccountsResponseTypeDef](./type_defs.md#listorganizationadminaccountsresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Retrieves the tags (keys and values) that are associated with a classification
job, custom data identifier, findings filter, or member account.

Type annotations for `session.create_client("macie2").list_tags_for_resource`
method.

Boto3 documentation:
[Macie2.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put\_classification\_export\_configuration"></a>

### put_classification_export_configuration

Creates or updates the configuration settings for storing data classification
results.

Type annotations for
`session.create_client("macie2").put_classification_export_configuration`
method.

Boto3 documentation:
[Macie2.Client.put_classification_export_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.put_classification_export_configuration)

Asynchronous method. Use `await put_classification_export_configuration(...)`
for a synchronous call.

Arguments mapping described in
[PutClassificationExportConfigurationRequestRequestTypeDef](./type_defs.md#putclassificationexportconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `configuration`:
  [ClassificationExportConfigurationTypeDef](./type_defs.md#classificationexportconfigurationtypedef)
  *(required)*

Returns a `Coroutine` for
[PutClassificationExportConfigurationResponseTypeDef](./type_defs.md#putclassificationexportconfigurationresponsetypedef).

<a id="put\_findings\_publication\_configuration"></a>

### put_findings_publication_configuration

Updates the configuration settings for publishing findings to Security Hub.

Type annotations for
`session.create_client("macie2").put_findings_publication_configuration`
method.

Boto3 documentation:
[Macie2.Client.put_findings_publication_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.put_findings_publication_configuration)

Asynchronous method. Use `await put_findings_publication_configuration(...)`
for a synchronous call.

Arguments mapping described in
[PutFindingsPublicationConfigurationRequestRequestTypeDef](./type_defs.md#putfindingspublicationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `clientToken`: `str`
- `securityHubConfiguration`:
  [SecurityHubConfigurationTypeDef](./type_defs.md#securityhubconfigurationtypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="search\_resources"></a>

### search_resources

Retrieves (queries) statistical data and other information about Amazon Web
Services resources that Amazon Macie monitors and analyzes.

Type annotations for `session.create_client("macie2").search_resources` method.

Boto3 documentation:
[Macie2.Client.search_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.search_resources)

Asynchronous method. Use `await search_resources(...)` for a synchronous call.

Arguments mapping described in
[SearchResourcesRequestRequestTypeDef](./type_defs.md#searchresourcesrequestrequesttypedef).

Keyword-only arguments:

- `bucketCriteria`:
  [SearchResourcesBucketCriteriaTypeDef](./type_defs.md#searchresourcesbucketcriteriatypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`:
  [SearchResourcesSortCriteriaTypeDef](./type_defs.md#searchresourcessortcriteriatypedef)

Returns a `Coroutine` for
[SearchResourcesResponseTypeDef](./type_defs.md#searchresourcesresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Adds or updates one or more tags (keys and values) that are associated with a
classification job, custom data identifier, findings filter, or member account.

Type annotations for `session.create_client("macie2").tag_resource` method.

Boto3 documentation:
[Macie2.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="test\_custom\_data\_identifier"></a>

### test_custom_data_identifier

Tests a custom data identifier.

Type annotations for
`session.create_client("macie2").test_custom_data_identifier` method.

Boto3 documentation:
[Macie2.Client.test_custom_data_identifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.test_custom_data_identifier)

Asynchronous method. Use `await test_custom_data_identifier(...)` for a
synchronous call.

Arguments mapping described in
[TestCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#testcustomdataidentifierrequestrequesttypedef).

Keyword-only arguments:

- `regex`: `str` *(required)*
- `sampleText`: `str` *(required)*
- `ignoreWords`: `Sequence`\[`str`\]
- `keywords`: `Sequence`\[`str`\]
- `maximumMatchDistance`: `int`

Returns a `Coroutine` for
[TestCustomDataIdentifierResponseTypeDef](./type_defs.md#testcustomdataidentifierresponsetypedef).

<a id="untag\_resource"></a>

### untag_resource

Removes one or more tags (keys and values) from a classification job, custom
data identifier, findings filter, or member account.

Type annotations for `session.create_client("macie2").untag_resource` method.

Boto3 documentation:
[Macie2.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_classification\_job"></a>

### update_classification_job

Changes the status of a classification job.

Type annotations for
`session.create_client("macie2").update_classification_job` method.

Boto3 documentation:
[Macie2.Client.update_classification_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.update_classification_job)

Asynchronous method. Use `await update_classification_job(...)` for a
synchronous call.

Arguments mapping described in
[UpdateClassificationJobRequestRequestTypeDef](./type_defs.md#updateclassificationjobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `jobStatus`: [JobStatusType](./literals.md#jobstatustype) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_findings\_filter"></a>

### update_findings_filter

Updates the criteria and other settings for a findings filter.

Type annotations for `session.create_client("macie2").update_findings_filter`
method.

Boto3 documentation:
[Macie2.Client.update_findings_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.update_findings_filter)

Asynchronous method. Use `await update_findings_filter(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFindingsFilterRequestRequestTypeDef](./type_defs.md#updatefindingsfilterrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `action`: [FindingsFilterActionType](./literals.md#findingsfilteractiontype)
- `description`: `str`
- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `name`: `str`
- `position`: `int`
- `clientToken`: `str`

Returns a `Coroutine` for
[UpdateFindingsFilterResponseTypeDef](./type_defs.md#updatefindingsfilterresponsetypedef).

<a id="update\_macie\_session"></a>

### update_macie_session

Suspends or re-enables Amazon Macie, or updates the configuration settings for
a Macie account.

Type annotations for `session.create_client("macie2").update_macie_session`
method.

Boto3 documentation:
[Macie2.Client.update_macie_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.update_macie_session)

Asynchronous method. Use `await update_macie_session(...)` for a synchronous
call.

Arguments mapping described in
[UpdateMacieSessionRequestRequestTypeDef](./type_defs.md#updatemaciesessionrequestrequesttypedef).

Keyword-only arguments:

- `findingPublishingFrequency`:
  [FindingPublishingFrequencyType](./literals.md#findingpublishingfrequencytype)
- `status`: [MacieStatusType](./literals.md#maciestatustype)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_member\_session"></a>

### update_member_session

Enables an Amazon Macie administrator to suspend or re-enable Macie for a
member account.

Type annotations for `session.create_client("macie2").update_member_session`
method.

Boto3 documentation:
[Macie2.Client.update_member_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.update_member_session)

Asynchronous method. Use `await update_member_session(...)` for a synchronous
call.

Arguments mapping described in
[UpdateMemberSessionRequestRequestTypeDef](./type_defs.md#updatemembersessionrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `status`: [MacieStatusType](./literals.md#maciestatustype) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_organization\_configuration"></a>

### update_organization_configuration

Updates the Amazon Macie configuration settings for an organization in
Organizations.

Type annotations for
`session.create_client("macie2").update_organization_configuration` method.

Boto3 documentation:
[Macie2.Client.update_organization_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.update_organization_configuration)

Asynchronous method. Use `await update_organization_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateOrganizationConfigurationRequestRequestTypeDef](./type_defs.md#updateorganizationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `autoEnable`: `bool` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("macie2").__aenter__` method.

Boto3 documentation:
[Macie2.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [Macie2Client](#macie2client).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("macie2").__aexit__` method.

Boto3 documentation:
[Macie2.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("macie2").get_paginator` method
with overloads.

- `client.get_paginator("describe_buckets")` ->
  [DescribeBucketsPaginator](./paginators.md#describebucketspaginator)
- `client.get_paginator("get_usage_statistics")` ->
  [GetUsageStatisticsPaginator](./paginators.md#getusagestatisticspaginator)
- `client.get_paginator("list_classification_jobs")` ->
  [ListClassificationJobsPaginator](./paginators.md#listclassificationjobspaginator)
- `client.get_paginator("list_custom_data_identifiers")` ->
  [ListCustomDataIdentifiersPaginator](./paginators.md#listcustomdataidentifierspaginator)
- `client.get_paginator("list_findings")` ->
  [ListFindingsPaginator](./paginators.md#listfindingspaginator)
- `client.get_paginator("list_findings_filters")` ->
  [ListFindingsFiltersPaginator](./paginators.md#listfindingsfilterspaginator)
- `client.get_paginator("list_invitations")` ->
  [ListInvitationsPaginator](./paginators.md#listinvitationspaginator)
- `client.get_paginator("list_members")` ->
  [ListMembersPaginator](./paginators.md#listmemberspaginator)
- `client.get_paginator("list_organization_admin_accounts")` ->
  [ListOrganizationAdminAccountsPaginator](./paginators.md#listorganizationadminaccountspaginator)
- `client.get_paginator("search_resources")` ->
  [SearchResourcesPaginator](./paginators.md#searchresourcespaginator)
