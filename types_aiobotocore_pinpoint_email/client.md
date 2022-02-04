<a id="pinpointemailclient-for-aiobotocore-pinpointemail-module"></a>

# PinpointEmailClient for aiobotocore PinpointEmail module

> [Index](..) > [PinpointEmail](.) > PinpointEmailClient

Auto-generated documentation for
[PinpointEmail](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
type annotations stubs module
[types-aiobotocore-pinpoint-email](https://pypi.org/project/types-aiobotocore-pinpoint-email/).

- [PinpointEmailClient for aiobotocore PinpointEmail module](#pinpointemailclient-for-aiobotocore-pinpointemail-module)
  - [PinpointEmailClient](#pinpointemailclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_configuration_set](#create_configuration_set)
    - [create_configuration_set_event_destination](#create_configuration_set_event_destination)
    - [create_dedicated_ip_pool](#create_dedicated_ip_pool)
    - [create_deliverability_test_report](#create_deliverability_test_report)
    - [create_email_identity](#create_email_identity)
    - [delete_configuration_set](#delete_configuration_set)
    - [delete_configuration_set_event_destination](#delete_configuration_set_event_destination)
    - [delete_dedicated_ip_pool](#delete_dedicated_ip_pool)
    - [delete_email_identity](#delete_email_identity)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_account](#get_account)
    - [get_blacklist_reports](#get_blacklist_reports)
    - [get_configuration_set](#get_configuration_set)
    - [get_configuration_set_event_destinations](#get_configuration_set_event_destinations)
    - [get_dedicated_ip](#get_dedicated_ip)
    - [get_dedicated_ips](#get_dedicated_ips)
    - [get_deliverability_dashboard_options](#get_deliverability_dashboard_options)
    - [get_deliverability_test_report](#get_deliverability_test_report)
    - [get_domain_deliverability_campaign](#get_domain_deliverability_campaign)
    - [get_domain_statistics_report](#get_domain_statistics_report)
    - [get_email_identity](#get_email_identity)
    - [list_configuration_sets](#list_configuration_sets)
    - [list_dedicated_ip_pools](#list_dedicated_ip_pools)
    - [list_deliverability_test_reports](#list_deliverability_test_reports)
    - [list_domain_deliverability_campaigns](#list_domain_deliverability_campaigns)
    - [list_email_identities](#list_email_identities)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_account_dedicated_ip_warmup_attributes](#put_account_dedicated_ip_warmup_attributes)
    - [put_account_sending_attributes](#put_account_sending_attributes)
    - [put_configuration_set_delivery_options](#put_configuration_set_delivery_options)
    - [put_configuration_set_reputation_options](#put_configuration_set_reputation_options)
    - [put_configuration_set_sending_options](#put_configuration_set_sending_options)
    - [put_configuration_set_tracking_options](#put_configuration_set_tracking_options)
    - [put_dedicated_ip_in_pool](#put_dedicated_ip_in_pool)
    - [put_dedicated_ip_warmup_attributes](#put_dedicated_ip_warmup_attributes)
    - [put_deliverability_dashboard_option](#put_deliverability_dashboard_option)
    - [put_email_identity_dkim_attributes](#put_email_identity_dkim_attributes)
    - [put_email_identity_feedback_attributes](#put_email_identity_feedback_attributes)
    - [put_email_identity_mail_from_attributes](#put_email_identity_mail_from_attributes)
    - [send_email](#send_email)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_configuration_set_event_destination](#update_configuration_set_event_destination)
    - [get_paginator](#get_paginator)

<a id="pinpointemailclient"></a>

## PinpointEmailClient

Type annotations for `aiobotocore.create_client("pinpoint-email")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_pinpoint_email.client import PinpointEmailClient

def get_pinpoint-email_client() -> PinpointEmailClient:
    return Session().client("pinpoint-email")
```

Boto3 documentation:
[PinpointEmail.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_pinpoint_email.client import Exceptions

def handle_error(exc: Exceptions.AccountSuspendedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccountSuspendedException`
- `Exceptions.AlreadyExistsException`
- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConcurrentModificationException`
- `Exceptions.LimitExceededException`
- `Exceptions.MailFromDomainNotVerifiedException`
- `Exceptions.MessageRejected`
- `Exceptions.NotFoundException`
- `Exceptions.SendingPausedException`
- `Exceptions.TooManyRequestsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

PinpointEmailClient exceptions.

Type annotations for `aiobotocore.create_client("pinpoint-email").exceptions`
method.

Boto3 documentation:
[PinpointEmail.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("pinpoint-email").can_paginate`
method.

Boto3 documentation:
[PinpointEmail.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_configuration_set"></a>

### create_configuration_set

Create a configuration set.

Type annotations for
`aiobotocore.create_client("pinpoint-email").create_configuration_set` method.

Boto3 documentation:
[PinpointEmail.Client.create_configuration_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.create_configuration_set)

Asynchronous method. Use `await create_configuration_set(...)` for a
synchronous call.

Arguments mapping described in
[CreateConfigurationSetRequestRequestTypeDef](./type_defs.md#createconfigurationsetrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `TrackingOptions`:
  [TrackingOptionsTypeDef](./type_defs.md#trackingoptionstypedef)
- `DeliveryOptions`:
  [DeliveryOptionsTypeDef](./type_defs.md#deliveryoptionstypedef)
- `ReputationOptions`:
  [ReputationOptionsTypeDef](./type_defs.md#reputationoptionstypedef)
- `SendingOptions`:
  [SendingOptionsTypeDef](./type_defs.md#sendingoptionstypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_configuration_set_event_destination"></a>

### create_configuration_set_event_destination

Create an event destination.

Type annotations for
`aiobotocore.create_client("pinpoint-email").create_configuration_set_event_destination`
method.

Boto3 documentation:
[PinpointEmail.Client.create_configuration_set_event_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.create_configuration_set_event_destination)

Asynchronous method. Use
`await create_configuration_set_event_destination(...)` for a synchronous call.

Arguments mapping described in
[CreateConfigurationSetEventDestinationRequestRequestTypeDef](./type_defs.md#createconfigurationseteventdestinationrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `EventDestinationName`: `str` *(required)*
- `EventDestination`:
  [EventDestinationDefinitionTypeDef](./type_defs.md#eventdestinationdefinitiontypedef)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_dedicated_ip_pool"></a>

### create_dedicated_ip_pool

Create a new pool of dedicated IP addresses.

Type annotations for
`aiobotocore.create_client("pinpoint-email").create_dedicated_ip_pool` method.

Boto3 documentation:
[PinpointEmail.Client.create_dedicated_ip_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.create_dedicated_ip_pool)

Asynchronous method. Use `await create_dedicated_ip_pool(...)` for a
synchronous call.

Arguments mapping described in
[CreateDedicatedIpPoolRequestRequestTypeDef](./type_defs.md#creatededicatedippoolrequestrequesttypedef).

Keyword-only arguments:

- `PoolName`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_deliverability_test_report"></a>

### create_deliverability_test_report

Create a new predictive inbox placement test.

Type annotations for
`aiobotocore.create_client("pinpoint-email").create_deliverability_test_report`
method.

Boto3 documentation:
[PinpointEmail.Client.create_deliverability_test_report](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.create_deliverability_test_report)

Asynchronous method. Use `await create_deliverability_test_report(...)` for a
synchronous call.

Arguments mapping described in
[CreateDeliverabilityTestReportRequestRequestTypeDef](./type_defs.md#createdeliverabilitytestreportrequestrequesttypedef).

Keyword-only arguments:

- `FromEmailAddress`: `str` *(required)*
- `Content`: [EmailContentTypeDef](./type_defs.md#emailcontenttypedef)
  *(required)*
- `ReportName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDeliverabilityTestReportResponseTypeDef](./type_defs.md#createdeliverabilitytestreportresponsetypedef).

<a id="create_email_identity"></a>

### create_email_identity

Verifies an email identity for use with Amazon Pinpoint.

Type annotations for
`aiobotocore.create_client("pinpoint-email").create_email_identity` method.

Boto3 documentation:
[PinpointEmail.Client.create_email_identity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.create_email_identity)

Asynchronous method. Use `await create_email_identity(...)` for a synchronous
call.

Arguments mapping described in
[CreateEmailIdentityRequestRequestTypeDef](./type_defs.md#createemailidentityrequestrequesttypedef).

Keyword-only arguments:

- `EmailIdentity`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateEmailIdentityResponseTypeDef](./type_defs.md#createemailidentityresponsetypedef).

<a id="delete_configuration_set"></a>

### delete_configuration_set

Delete an existing configuration set.

Type annotations for
`aiobotocore.create_client("pinpoint-email").delete_configuration_set` method.

Boto3 documentation:
[PinpointEmail.Client.delete_configuration_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.delete_configuration_set)

Asynchronous method. Use `await delete_configuration_set(...)` for a
synchronous call.

Arguments mapping described in
[DeleteConfigurationSetRequestRequestTypeDef](./type_defs.md#deleteconfigurationsetrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_configuration_set_event_destination"></a>

### delete_configuration_set_event_destination

Delete an event destination.

Type annotations for
`aiobotocore.create_client("pinpoint-email").delete_configuration_set_event_destination`
method.

Boto3 documentation:
[PinpointEmail.Client.delete_configuration_set_event_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.delete_configuration_set_event_destination)

Asynchronous method. Use
`await delete_configuration_set_event_destination(...)` for a synchronous call.

Arguments mapping described in
[DeleteConfigurationSetEventDestinationRequestRequestTypeDef](./type_defs.md#deleteconfigurationseteventdestinationrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `EventDestinationName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_dedicated_ip_pool"></a>

### delete_dedicated_ip_pool

Delete a dedicated IP pool.

Type annotations for
`aiobotocore.create_client("pinpoint-email").delete_dedicated_ip_pool` method.

Boto3 documentation:
[PinpointEmail.Client.delete_dedicated_ip_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.delete_dedicated_ip_pool)

Asynchronous method. Use `await delete_dedicated_ip_pool(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDedicatedIpPoolRequestRequestTypeDef](./type_defs.md#deletededicatedippoolrequestrequesttypedef).

Keyword-only arguments:

- `PoolName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_email_identity"></a>

### delete_email_identity

Deletes an email identity that you previously verified for use with Amazon
Pinpoint.

Type annotations for
`aiobotocore.create_client("pinpoint-email").delete_email_identity` method.

Boto3 documentation:
[PinpointEmail.Client.delete_email_identity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.delete_email_identity)

Asynchronous method. Use `await delete_email_identity(...)` for a synchronous
call.

Arguments mapping described in
[DeleteEmailIdentityRequestRequestTypeDef](./type_defs.md#deleteemailidentityrequestrequesttypedef).

Keyword-only arguments:

- `EmailIdentity`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("pinpoint-email").generate_presigned_url` method.

Boto3 documentation:
[PinpointEmail.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_account"></a>

### get_account

Obtain information about the email-sending status and capabilities of your
Amazon Pinpoint account in the current AWS Region.

Type annotations for `aiobotocore.create_client("pinpoint-email").get_account`
method.

Boto3 documentation:
[PinpointEmail.Client.get_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_account)

Asynchronous method. Use `await get_account(...)` for a synchronous call.

Returns a `Coroutine` for
[GetAccountResponseTypeDef](./type_defs.md#getaccountresponsetypedef).

<a id="get_blacklist_reports"></a>

### get_blacklist_reports

Retrieve a list of the blacklists that your dedicated IP addresses appear on.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_blacklist_reports` method.

Boto3 documentation:
[PinpointEmail.Client.get_blacklist_reports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_blacklist_reports)

Asynchronous method. Use `await get_blacklist_reports(...)` for a synchronous
call.

Arguments mapping described in
[GetBlacklistReportsRequestRequestTypeDef](./type_defs.md#getblacklistreportsrequestrequesttypedef).

Keyword-only arguments:

- `BlacklistItemNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[GetBlacklistReportsResponseTypeDef](./type_defs.md#getblacklistreportsresponsetypedef).

<a id="get_configuration_set"></a>

### get_configuration_set

Get information about an existing configuration set, including the dedicated IP
pool that it's associated with, whether or not it's enabled for sending email,
and more.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_configuration_set` method.

Boto3 documentation:
[PinpointEmail.Client.get_configuration_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_configuration_set)

Asynchronous method. Use `await get_configuration_set(...)` for a synchronous
call.

Arguments mapping described in
[GetConfigurationSetRequestRequestTypeDef](./type_defs.md#getconfigurationsetrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*

Returns a `Coroutine` for
[GetConfigurationSetResponseTypeDef](./type_defs.md#getconfigurationsetresponsetypedef).

<a id="get_configuration_set_event_destinations"></a>

### get_configuration_set_event_destinations

Retrieve a list of event destinations that are associated with a configuration
set.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_configuration_set_event_destinations`
method.

Boto3 documentation:
[PinpointEmail.Client.get_configuration_set_event_destinations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_configuration_set_event_destinations)

Asynchronous method. Use `await get_configuration_set_event_destinations(...)`
for a synchronous call.

Arguments mapping described in
[GetConfigurationSetEventDestinationsRequestRequestTypeDef](./type_defs.md#getconfigurationseteventdestinationsrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*

Returns a `Coroutine` for
[GetConfigurationSetEventDestinationsResponseTypeDef](./type_defs.md#getconfigurationseteventdestinationsresponsetypedef).

<a id="get_dedicated_ip"></a>

### get_dedicated_ip

Get information about a dedicated IP address, including the name of the
dedicated IP pool that it's associated with, as well information about the
automatic warm-up process for the address.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_dedicated_ip` method.

Boto3 documentation:
[PinpointEmail.Client.get_dedicated_ip](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_dedicated_ip)

Asynchronous method. Use `await get_dedicated_ip(...)` for a synchronous call.

Arguments mapping described in
[GetDedicatedIpRequestRequestTypeDef](./type_defs.md#getdedicatediprequestrequesttypedef).

Keyword-only arguments:

- `Ip`: `str` *(required)*

Returns a `Coroutine` for
[GetDedicatedIpResponseTypeDef](./type_defs.md#getdedicatedipresponsetypedef).

<a id="get_dedicated_ips"></a>

### get_dedicated_ips

List the dedicated IP addresses that are associated with your Amazon Pinpoint
account.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_dedicated_ips` method.

Boto3 documentation:
[PinpointEmail.Client.get_dedicated_ips](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_dedicated_ips)

Asynchronous method. Use `await get_dedicated_ips(...)` for a synchronous call.

Arguments mapping described in
[GetDedicatedIpsRequestRequestTypeDef](./type_defs.md#getdedicatedipsrequestrequesttypedef).

Keyword-only arguments:

- `PoolName`: `str`
- `NextToken`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[GetDedicatedIpsResponseTypeDef](./type_defs.md#getdedicatedipsresponsetypedef).

<a id="get_deliverability_dashboard_options"></a>

### get_deliverability_dashboard_options

Retrieve information about the status of the Deliverability dashboard for your
Amazon Pinpoint account.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_deliverability_dashboard_options`
method.

Boto3 documentation:
[PinpointEmail.Client.get_deliverability_dashboard_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_deliverability_dashboard_options)

Asynchronous method. Use `await get_deliverability_dashboard_options(...)` for
a synchronous call.

Returns a `Coroutine` for
[GetDeliverabilityDashboardOptionsResponseTypeDef](./type_defs.md#getdeliverabilitydashboardoptionsresponsetypedef).

<a id="get_deliverability_test_report"></a>

### get_deliverability_test_report

Retrieve the results of a predictive inbox placement test.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_deliverability_test_report`
method.

Boto3 documentation:
[PinpointEmail.Client.get_deliverability_test_report](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_deliverability_test_report)

Asynchronous method. Use `await get_deliverability_test_report(...)` for a
synchronous call.

Arguments mapping described in
[GetDeliverabilityTestReportRequestRequestTypeDef](./type_defs.md#getdeliverabilitytestreportrequestrequesttypedef).

Keyword-only arguments:

- `ReportId`: `str` *(required)*

Returns a `Coroutine` for
[GetDeliverabilityTestReportResponseTypeDef](./type_defs.md#getdeliverabilitytestreportresponsetypedef).

<a id="get_domain_deliverability_campaign"></a>

### get_domain_deliverability_campaign

Retrieve all the deliverability data for a specific campaign.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_domain_deliverability_campaign`
method.

Boto3 documentation:
[PinpointEmail.Client.get_domain_deliverability_campaign](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_domain_deliverability_campaign)

Asynchronous method. Use `await get_domain_deliverability_campaign(...)` for a
synchronous call.

Arguments mapping described in
[GetDomainDeliverabilityCampaignRequestRequestTypeDef](./type_defs.md#getdomaindeliverabilitycampaignrequestrequesttypedef).

Keyword-only arguments:

- `CampaignId`: `str` *(required)*

Returns a `Coroutine` for
[GetDomainDeliverabilityCampaignResponseTypeDef](./type_defs.md#getdomaindeliverabilitycampaignresponsetypedef).

<a id="get_domain_statistics_report"></a>

### get_domain_statistics_report

Retrieve inbox placement and engagement rates for the domains that you use to
send email.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_domain_statistics_report`
method.

Boto3 documentation:
[PinpointEmail.Client.get_domain_statistics_report](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_domain_statistics_report)

Asynchronous method. Use `await get_domain_statistics_report(...)` for a
synchronous call.

Arguments mapping described in
[GetDomainStatisticsReportRequestRequestTypeDef](./type_defs.md#getdomainstatisticsreportrequestrequesttypedef).

Keyword-only arguments:

- `Domain`: `str` *(required)*
- `StartDate`: `Union`\[`datetime`, `str`\] *(required)*
- `EndDate`: `Union`\[`datetime`, `str`\] *(required)*

Returns a `Coroutine` for
[GetDomainStatisticsReportResponseTypeDef](./type_defs.md#getdomainstatisticsreportresponsetypedef).

<a id="get_email_identity"></a>

### get_email_identity

Provides information about a specific identity associated with your Amazon
Pinpoint account, including the identity's verification status, its DKIM
authentication status, and its custom Mail-From settings.

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_email_identity` method.

Boto3 documentation:
[PinpointEmail.Client.get_email_identity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.get_email_identity)

Asynchronous method. Use `await get_email_identity(...)` for a synchronous
call.

Arguments mapping described in
[GetEmailIdentityRequestRequestTypeDef](./type_defs.md#getemailidentityrequestrequesttypedef).

Keyword-only arguments:

- `EmailIdentity`: `str` *(required)*

Returns a `Coroutine` for
[GetEmailIdentityResponseTypeDef](./type_defs.md#getemailidentityresponsetypedef).

<a id="list_configuration_sets"></a>

### list_configuration_sets

List all of the configuration sets associated with your Amazon Pinpoint account
in the current region.

Type annotations for
`aiobotocore.create_client("pinpoint-email").list_configuration_sets` method.

Boto3 documentation:
[PinpointEmail.Client.list_configuration_sets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.list_configuration_sets)

Asynchronous method. Use `await list_configuration_sets(...)` for a synchronous
call.

Arguments mapping described in
[ListConfigurationSetsRequestRequestTypeDef](./type_defs.md#listconfigurationsetsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[ListConfigurationSetsResponseTypeDef](./type_defs.md#listconfigurationsetsresponsetypedef).

<a id="list_dedicated_ip_pools"></a>

### list_dedicated_ip_pools

List all of the dedicated IP pools that exist in your Amazon Pinpoint account
in the current AWS Region.

Type annotations for
`aiobotocore.create_client("pinpoint-email").list_dedicated_ip_pools` method.

Boto3 documentation:
[PinpointEmail.Client.list_dedicated_ip_pools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.list_dedicated_ip_pools)

Asynchronous method. Use `await list_dedicated_ip_pools(...)` for a synchronous
call.

Arguments mapping described in
[ListDedicatedIpPoolsRequestRequestTypeDef](./type_defs.md#listdedicatedippoolsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[ListDedicatedIpPoolsResponseTypeDef](./type_defs.md#listdedicatedippoolsresponsetypedef).

<a id="list_deliverability_test_reports"></a>

### list_deliverability_test_reports

Show a list of the predictive inbox placement tests that you've performed,
regardless of their statuses.

Type annotations for
`aiobotocore.create_client("pinpoint-email").list_deliverability_test_reports`
method.

Boto3 documentation:
[PinpointEmail.Client.list_deliverability_test_reports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.list_deliverability_test_reports)

Asynchronous method. Use `await list_deliverability_test_reports(...)` for a
synchronous call.

Arguments mapping described in
[ListDeliverabilityTestReportsRequestRequestTypeDef](./type_defs.md#listdeliverabilitytestreportsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[ListDeliverabilityTestReportsResponseTypeDef](./type_defs.md#listdeliverabilitytestreportsresponsetypedef).

<a id="list_domain_deliverability_campaigns"></a>

### list_domain_deliverability_campaigns

Retrieve deliverability data for all the campaigns that used a specific domain
to send email during a specified time range.

Type annotations for
`aiobotocore.create_client("pinpoint-email").list_domain_deliverability_campaigns`
method.

Boto3 documentation:
[PinpointEmail.Client.list_domain_deliverability_campaigns](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.list_domain_deliverability_campaigns)

Asynchronous method. Use `await list_domain_deliverability_campaigns(...)` for
a synchronous call.

Arguments mapping described in
[ListDomainDeliverabilityCampaignsRequestRequestTypeDef](./type_defs.md#listdomaindeliverabilitycampaignsrequestrequesttypedef).

Keyword-only arguments:

- `StartDate`: `Union`\[`datetime`, `str`\] *(required)*
- `EndDate`: `Union`\[`datetime`, `str`\] *(required)*
- `SubscribedDomain`: `str` *(required)*
- `NextToken`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[ListDomainDeliverabilityCampaignsResponseTypeDef](./type_defs.md#listdomaindeliverabilitycampaignsresponsetypedef).

<a id="list_email_identities"></a>

### list_email_identities

Returns a list of all of the email identities that are associated with your
Amazon Pinpoint account.

Type annotations for
`aiobotocore.create_client("pinpoint-email").list_email_identities` method.

Boto3 documentation:
[PinpointEmail.Client.list_email_identities](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.list_email_identities)

Asynchronous method. Use `await list_email_identities(...)` for a synchronous
call.

Arguments mapping described in
[ListEmailIdentitiesRequestRequestTypeDef](./type_defs.md#listemailidentitiesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[ListEmailIdentitiesResponseTypeDef](./type_defs.md#listemailidentitiesresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Retrieve a list of the tags (keys and values) that are associated with a
specified resource.

Type annotations for
`aiobotocore.create_client("pinpoint-email").list_tags_for_resource` method.

Boto3 documentation:
[PinpointEmail.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_account_dedicated_ip_warmup_attributes"></a>

### put_account_dedicated_ip_warmup_attributes

Enable or disable the automatic warm-up feature for dedicated IP addresses.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_account_dedicated_ip_warmup_attributes`
method.

Boto3 documentation:
[PinpointEmail.Client.put_account_dedicated_ip_warmup_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_account_dedicated_ip_warmup_attributes)

Asynchronous method. Use
`await put_account_dedicated_ip_warmup_attributes(...)` for a synchronous call.

Arguments mapping described in
[PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef](./type_defs.md#putaccountdedicatedipwarmupattributesrequestrequesttypedef).

Keyword-only arguments:

- `AutoWarmupEnabled`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_account_sending_attributes"></a>

### put_account_sending_attributes

Enable or disable the ability of your account to send email.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_account_sending_attributes`
method.

Boto3 documentation:
[PinpointEmail.Client.put_account_sending_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_account_sending_attributes)

Asynchronous method. Use `await put_account_sending_attributes(...)` for a
synchronous call.

Arguments mapping described in
[PutAccountSendingAttributesRequestRequestTypeDef](./type_defs.md#putaccountsendingattributesrequestrequesttypedef).

Keyword-only arguments:

- `SendingEnabled`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_configuration_set_delivery_options"></a>

### put_configuration_set_delivery_options

Associate a configuration set with a dedicated IP pool.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_configuration_set_delivery_options`
method.

Boto3 documentation:
[PinpointEmail.Client.put_configuration_set_delivery_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_configuration_set_delivery_options)

Asynchronous method. Use `await put_configuration_set_delivery_options(...)`
for a synchronous call.

Arguments mapping described in
[PutConfigurationSetDeliveryOptionsRequestRequestTypeDef](./type_defs.md#putconfigurationsetdeliveryoptionsrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `TlsPolicy`: [TlsPolicyType](./literals.md#tlspolicytype)
- `SendingPoolName`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_configuration_set_reputation_options"></a>

### put_configuration_set_reputation_options

Enable or disable collection of reputation metrics for emails that you send
using a particular configuration set in a specific AWS Region.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_configuration_set_reputation_options`
method.

Boto3 documentation:
[PinpointEmail.Client.put_configuration_set_reputation_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_configuration_set_reputation_options)

Asynchronous method. Use `await put_configuration_set_reputation_options(...)`
for a synchronous call.

Arguments mapping described in
[PutConfigurationSetReputationOptionsRequestRequestTypeDef](./type_defs.md#putconfigurationsetreputationoptionsrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `ReputationMetricsEnabled`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_configuration_set_sending_options"></a>

### put_configuration_set_sending_options

Enable or disable email sending for messages that use a particular
configuration set in a specific AWS Region.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_configuration_set_sending_options`
method.

Boto3 documentation:
[PinpointEmail.Client.put_configuration_set_sending_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_configuration_set_sending_options)

Asynchronous method. Use `await put_configuration_set_sending_options(...)` for
a synchronous call.

Arguments mapping described in
[PutConfigurationSetSendingOptionsRequestRequestTypeDef](./type_defs.md#putconfigurationsetsendingoptionsrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `SendingEnabled`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_configuration_set_tracking_options"></a>

### put_configuration_set_tracking_options

Specify a custom domain to use for open and click tracking elements in email
that you send using Amazon Pinpoint.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_configuration_set_tracking_options`
method.

Boto3 documentation:
[PinpointEmail.Client.put_configuration_set_tracking_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_configuration_set_tracking_options)

Asynchronous method. Use `await put_configuration_set_tracking_options(...)`
for a synchronous call.

Arguments mapping described in
[PutConfigurationSetTrackingOptionsRequestRequestTypeDef](./type_defs.md#putconfigurationsettrackingoptionsrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `CustomRedirectDomain`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_dedicated_ip_in_pool"></a>

### put_dedicated_ip_in_pool

Move a dedicated IP address to an existing dedicated IP pool.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_dedicated_ip_in_pool` method.

Boto3 documentation:
[PinpointEmail.Client.put_dedicated_ip_in_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_dedicated_ip_in_pool)

Asynchronous method. Use `await put_dedicated_ip_in_pool(...)` for a
synchronous call.

Arguments mapping described in
[PutDedicatedIpInPoolRequestRequestTypeDef](./type_defs.md#putdedicatedipinpoolrequestrequesttypedef).

Keyword-only arguments:

- `Ip`: `str` *(required)*
- `DestinationPoolName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_dedicated_ip_warmup_attributes"></a>

### put_dedicated_ip_warmup_attributes

See also: \[AWS API
Documentation\](https://docs.aws.amazon.com/goto/WebAPI/pinpoint-
email-2018-07-26/PutDedicatedIpWarmupAttributes).

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_dedicated_ip_warmup_attributes`
method.

Boto3 documentation:
[PinpointEmail.Client.put_dedicated_ip_warmup_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_dedicated_ip_warmup_attributes)

Asynchronous method. Use `await put_dedicated_ip_warmup_attributes(...)` for a
synchronous call.

Arguments mapping described in
[PutDedicatedIpWarmupAttributesRequestRequestTypeDef](./type_defs.md#putdedicatedipwarmupattributesrequestrequesttypedef).

Keyword-only arguments:

- `Ip`: `str` *(required)*
- `WarmupPercentage`: `int` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_deliverability_dashboard_option"></a>

### put_deliverability_dashboard_option

Enable or disable the Deliverability dashboard for your Amazon Pinpoint
account.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_deliverability_dashboard_option`
method.

Boto3 documentation:
[PinpointEmail.Client.put_deliverability_dashboard_option](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_deliverability_dashboard_option)

Asynchronous method. Use `await put_deliverability_dashboard_option(...)` for a
synchronous call.

Arguments mapping described in
[PutDeliverabilityDashboardOptionRequestRequestTypeDef](./type_defs.md#putdeliverabilitydashboardoptionrequestrequesttypedef).

Keyword-only arguments:

- `DashboardEnabled`: `bool` *(required)*
- `SubscribedDomains`:
  `Sequence`\[[DomainDeliverabilityTrackingOptionTypeDef](./type_defs.md#domaindeliverabilitytrackingoptiontypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_email_identity_dkim_attributes"></a>

### put_email_identity_dkim_attributes

Used to enable or disable DKIM authentication for an email identity.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_email_identity_dkim_attributes`
method.

Boto3 documentation:
[PinpointEmail.Client.put_email_identity_dkim_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_email_identity_dkim_attributes)

Asynchronous method. Use `await put_email_identity_dkim_attributes(...)` for a
synchronous call.

Arguments mapping described in
[PutEmailIdentityDkimAttributesRequestRequestTypeDef](./type_defs.md#putemailidentitydkimattributesrequestrequesttypedef).

Keyword-only arguments:

- `EmailIdentity`: `str` *(required)*
- `SigningEnabled`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_email_identity_feedback_attributes"></a>

### put_email_identity_feedback_attributes

Used to enable or disable feedback forwarding for an identity.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_email_identity_feedback_attributes`
method.

Boto3 documentation:
[PinpointEmail.Client.put_email_identity_feedback_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_email_identity_feedback_attributes)

Asynchronous method. Use `await put_email_identity_feedback_attributes(...)`
for a synchronous call.

Arguments mapping described in
[PutEmailIdentityFeedbackAttributesRequestRequestTypeDef](./type_defs.md#putemailidentityfeedbackattributesrequestrequesttypedef).

Keyword-only arguments:

- `EmailIdentity`: `str` *(required)*
- `EmailForwardingEnabled`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_email_identity_mail_from_attributes"></a>

### put_email_identity_mail_from_attributes

Used to enable or disable the custom Mail-From domain configuration for an
email identity.

Type annotations for
`aiobotocore.create_client("pinpoint-email").put_email_identity_mail_from_attributes`
method.

Boto3 documentation:
[PinpointEmail.Client.put_email_identity_mail_from_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.put_email_identity_mail_from_attributes)

Asynchronous method. Use `await put_email_identity_mail_from_attributes(...)`
for a synchronous call.

Arguments mapping described in
[PutEmailIdentityMailFromAttributesRequestRequestTypeDef](./type_defs.md#putemailidentitymailfromattributesrequestrequesttypedef).

Keyword-only arguments:

- `EmailIdentity`: `str` *(required)*
- `MailFromDomain`: `str`
- `BehaviorOnMxFailure`:
  [BehaviorOnMxFailureType](./literals.md#behavioronmxfailuretype)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="send_email"></a>

### send_email

Sends an email message.

Type annotations for `aiobotocore.create_client("pinpoint-email").send_email`
method.

Boto3 documentation:
[PinpointEmail.Client.send_email](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.send_email)

Asynchronous method. Use `await send_email(...)` for a synchronous call.

Arguments mapping described in
[SendEmailRequestRequestTypeDef](./type_defs.md#sendemailrequestrequesttypedef).

Keyword-only arguments:

- `Destination`: [DestinationTypeDef](./type_defs.md#destinationtypedef)
  *(required)*
- `Content`: [EmailContentTypeDef](./type_defs.md#emailcontenttypedef)
  *(required)*
- `FromEmailAddress`: `str`
- `ReplyToAddresses`: `Sequence`\[`str`\]
- `FeedbackForwardingEmailAddress`: `str`
- `EmailTags`:
  `Sequence`\[[MessageTagTypeDef](./type_defs.md#messagetagtypedef)\]
- `ConfigurationSetName`: `str`

Returns a `Coroutine` for
[SendEmailResponseTypeDef](./type_defs.md#sendemailresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Add one or more tags (keys and values) to a specified resource.

Type annotations for `aiobotocore.create_client("pinpoint-email").tag_resource`
method.

Boto3 documentation:
[PinpointEmail.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Remove one or more tags (keys and values) from a specified resource.

Type annotations for
`aiobotocore.create_client("pinpoint-email").untag_resource` method.

Boto3 documentation:
[PinpointEmail.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_configuration_set_event_destination"></a>

### update_configuration_set_event_destination

Update the configuration of an event destination for a configuration set.

Type annotations for
`aiobotocore.create_client("pinpoint-email").update_configuration_set_event_destination`
method.

Boto3 documentation:
[PinpointEmail.Client.update_configuration_set_event_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Client.update_configuration_set_event_destination)

Asynchronous method. Use
`await update_configuration_set_event_destination(...)` for a synchronous call.

Arguments mapping described in
[UpdateConfigurationSetEventDestinationRequestRequestTypeDef](./type_defs.md#updateconfigurationseteventdestinationrequestrequesttypedef).

Keyword-only arguments:

- `ConfigurationSetName`: `str` *(required)*
- `EventDestinationName`: `str` *(required)*
- `EventDestination`:
  [EventDestinationDefinitionTypeDef](./type_defs.md#eventdestinationdefinitiontypedef)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("pinpoint-email").get_paginator` method with
overloads.

- `client.get_paginator("get_dedicated_ips")` ->
  [GetDedicatedIpsPaginator](./paginators.md#getdedicatedipspaginator)
- `client.get_paginator("list_configuration_sets")` ->
  [ListConfigurationSetsPaginator](./paginators.md#listconfigurationsetspaginator)
- `client.get_paginator("list_dedicated_ip_pools")` ->
  [ListDedicatedIpPoolsPaginator](./paginators.md#listdedicatedippoolspaginator)
- `client.get_paginator("list_deliverability_test_reports")` ->
  [ListDeliverabilityTestReportsPaginator](./paginators.md#listdeliverabilitytestreportspaginator)
- `client.get_paginator("list_email_identities")` ->
  [ListEmailIdentitiesPaginator](./paginators.md#listemailidentitiespaginator)
