<a id="servicequotasclient-for-aiobotocore-servicequotas-module"></a>

# ServiceQuotasClient for aiobotocore ServiceQuotas module

> [Index](..) > [ServiceQuotas](.) > ServiceQuotasClient

Auto-generated documentation for
[ServiceQuotas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas)
type annotations stubs module
[types-aiobotocore-service-quotas](https://pypi.org/project/types-aiobotocore-service-quotas/).

- [ServiceQuotasClient for aiobotocore ServiceQuotas module](#servicequotasclient-for-aiobotocore-servicequotas-module)
  - [ServiceQuotasClient](#servicequotasclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_service_quota_template](#associate_service_quota_template)
    - [can_paginate](#can_paginate)
    - [delete_service_quota_increase_request_from_template](#delete_service_quota_increase_request_from_template)
    - [disassociate_service_quota_template](#disassociate_service_quota_template)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_association_for_service_quota_template](#get_association_for_service_quota_template)
    - [get_aws_default_service_quota](#get_aws_default_service_quota)
    - [get_requested_service_quota_change](#get_requested_service_quota_change)
    - [get_service_quota](#get_service_quota)
    - [get_service_quota_increase_request_from_template](#get_service_quota_increase_request_from_template)
    - [list_aws_default_service_quotas](#list_aws_default_service_quotas)
    - [list_requested_service_quota_change_history](#list_requested_service_quota_change_history)
    - [list_requested_service_quota_change_history_by_quota](#list_requested_service_quota_change_history_by_quota)
    - [list_service_quota_increase_requests_in_template](#list_service_quota_increase_requests_in_template)
    - [list_service_quotas](#list_service_quotas)
    - [list_services](#list_services)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_service_quota_increase_request_into_template](#put_service_quota_increase_request_into_template)
    - [request_service_quota_increase](#request_service_quota_increase)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [get_paginator](#get_paginator)

<a id="servicequotasclient"></a>

## ServiceQuotasClient

Type annotations for `aiobotocore.create_client("service-quotas")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_service_quotas.client import ServiceQuotasClient

def get_service-quotas_client() -> ServiceQuotasClient:
    return Session().client("service-quotas")
```

Boto3 documentation:
[ServiceQuotas.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_service_quotas.client import Exceptions

def handle_error(exc: Exceptions.AWSServiceAccessNotEnabledException) -> None:
    ...
```

Exceptions:

- `Exceptions.AWSServiceAccessNotEnabledException`
- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.DependencyAccessDeniedException`
- `Exceptions.IllegalArgumentException`
- `Exceptions.InvalidPaginationTokenException`
- `Exceptions.InvalidResourceStateException`
- `Exceptions.NoAvailableOrganizationException`
- `Exceptions.NoSuchResourceException`
- `Exceptions.OrganizationNotInAllFeaturesModeException`
- `Exceptions.QuotaExceededException`
- `Exceptions.ResourceAlreadyExistsException`
- `Exceptions.ServiceException`
- `Exceptions.ServiceQuotaTemplateNotInUseException`
- `Exceptions.TagPolicyViolationException`
- `Exceptions.TemplatesNotAvailableInRegionException`
- `Exceptions.TooManyRequestsException`
- `Exceptions.TooManyTagsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ServiceQuotasClient exceptions.

Type annotations for `aiobotocore.create_client("service-quotas").exceptions`
method.

Boto3 documentation:
[ServiceQuotas.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate_service_quota_template"></a>

### associate_service_quota_template

Associates your quota request template with your organization.

Type annotations for
`aiobotocore.create_client("service-quotas").associate_service_quota_template`
method.

Boto3 documentation:
[ServiceQuotas.Client.associate_service_quota_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.associate_service_quota_template)

Asynchronous method. Use `await associate_service_quota_template(...)` for a
synchronous call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("service-quotas").can_paginate`
method.

Boto3 documentation:
[ServiceQuotas.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="delete_service_quota_increase_request_from_template"></a>

### delete_service_quota_increase_request_from_template

Deletes the quota increase request for the specified quota from your quota
request template.

Type annotations for
`aiobotocore.create_client("service-quotas").delete_service_quota_increase_request_from_template`
method.

Boto3 documentation:
[ServiceQuotas.Client.delete_service_quota_increase_request_from_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.delete_service_quota_increase_request_from_template)

Asynchronous method. Use
`await delete_service_quota_increase_request_from_template(...)` for a
synchronous call.

Arguments mapping described in
[DeleteServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef](./type_defs.md#deleteservicequotaincreaserequestfromtemplaterequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `QuotaCode`: `str` *(required)*
- `AwsRegion`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disassociate_service_quota_template"></a>

### disassociate_service_quota_template

Disables your quota request template.

Type annotations for
`aiobotocore.create_client("service-quotas").disassociate_service_quota_template`
method.

Boto3 documentation:
[ServiceQuotas.Client.disassociate_service_quota_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.disassociate_service_quota_template)

Asynchronous method. Use `await disassociate_service_quota_template(...)` for a
synchronous call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("service-quotas").generate_presigned_url` method.

Boto3 documentation:
[ServiceQuotas.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_association_for_service_quota_template"></a>

### get_association_for_service_quota_template

Retrieves the status of the association for the quota request template.

Type annotations for
`aiobotocore.create_client("service-quotas").get_association_for_service_quota_template`
method.

Boto3 documentation:
[ServiceQuotas.Client.get_association_for_service_quota_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.get_association_for_service_quota_template)

Asynchronous method. Use
`await get_association_for_service_quota_template(...)` for a synchronous call.

Returns a `Coroutine` for
[GetAssociationForServiceQuotaTemplateResponseTypeDef](./type_defs.md#getassociationforservicequotatemplateresponsetypedef).

<a id="get_aws_default_service_quota"></a>

### get_aws_default_service_quota

Retrieves the default value for the specified quota.

Type annotations for
`aiobotocore.create_client("service-quotas").get_aws_default_service_quota`
method.

Boto3 documentation:
[ServiceQuotas.Client.get_aws_default_service_quota](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.get_aws_default_service_quota)

Asynchronous method. Use `await get_aws_default_service_quota(...)` for a
synchronous call.

Arguments mapping described in
[GetAWSDefaultServiceQuotaRequestRequestTypeDef](./type_defs.md#getawsdefaultservicequotarequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `QuotaCode`: `str` *(required)*

Returns a `Coroutine` for
[GetAWSDefaultServiceQuotaResponseTypeDef](./type_defs.md#getawsdefaultservicequotaresponsetypedef).

<a id="get_requested_service_quota_change"></a>

### get_requested_service_quota_change

Retrieves information about the specified quota increase request.

Type annotations for
`aiobotocore.create_client("service-quotas").get_requested_service_quota_change`
method.

Boto3 documentation:
[ServiceQuotas.Client.get_requested_service_quota_change](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.get_requested_service_quota_change)

Asynchronous method. Use `await get_requested_service_quota_change(...)` for a
synchronous call.

Arguments mapping described in
[GetRequestedServiceQuotaChangeRequestRequestTypeDef](./type_defs.md#getrequestedservicequotachangerequestrequesttypedef).

Keyword-only arguments:

- `RequestId`: `str` *(required)*

Returns a `Coroutine` for
[GetRequestedServiceQuotaChangeResponseTypeDef](./type_defs.md#getrequestedservicequotachangeresponsetypedef).

<a id="get_service_quota"></a>

### get_service_quota

Retrieves the applied quota value for the specified quota.

Type annotations for
`aiobotocore.create_client("service-quotas").get_service_quota` method.

Boto3 documentation:
[ServiceQuotas.Client.get_service_quota](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.get_service_quota)

Asynchronous method. Use `await get_service_quota(...)` for a synchronous call.

Arguments mapping described in
[GetServiceQuotaRequestRequestTypeDef](./type_defs.md#getservicequotarequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `QuotaCode`: `str` *(required)*

Returns a `Coroutine` for
[GetServiceQuotaResponseTypeDef](./type_defs.md#getservicequotaresponsetypedef).

<a id="get_service_quota_increase_request_from_template"></a>

### get_service_quota_increase_request_from_template

Retrieves information about the specified quota increase request in your quota
request template.

Type annotations for
`aiobotocore.create_client("service-quotas").get_service_quota_increase_request_from_template`
method.

Boto3 documentation:
[ServiceQuotas.Client.get_service_quota_increase_request_from_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.get_service_quota_increase_request_from_template)

Asynchronous method. Use
`await get_service_quota_increase_request_from_template(...)` for a synchronous
call.

Arguments mapping described in
[GetServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef](./type_defs.md#getservicequotaincreaserequestfromtemplaterequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `QuotaCode`: `str` *(required)*
- `AwsRegion`: `str` *(required)*

Returns a `Coroutine` for
[GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef](./type_defs.md#getservicequotaincreaserequestfromtemplateresponsetypedef).

<a id="list_aws_default_service_quotas"></a>

### list_aws_default_service_quotas

Lists the default values for the quotas for the specified AWS service.

Type annotations for
`aiobotocore.create_client("service-quotas").list_aws_default_service_quotas`
method.

Boto3 documentation:
[ServiceQuotas.Client.list_aws_default_service_quotas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.list_aws_default_service_quotas)

Asynchronous method. Use `await list_aws_default_service_quotas(...)` for a
synchronous call.

Arguments mapping described in
[ListAWSDefaultServiceQuotasRequestRequestTypeDef](./type_defs.md#listawsdefaultservicequotasrequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListAWSDefaultServiceQuotasResponseTypeDef](./type_defs.md#listawsdefaultservicequotasresponsetypedef).

<a id="list_requested_service_quota_change_history"></a>

### list_requested_service_quota_change_history

Retrieves the quota increase requests for the specified service.

Type annotations for
`aiobotocore.create_client("service-quotas").list_requested_service_quota_change_history`
method.

Boto3 documentation:
[ServiceQuotas.Client.list_requested_service_quota_change_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.list_requested_service_quota_change_history)

Asynchronous method. Use
`await list_requested_service_quota_change_history(...)` for a synchronous
call.

Arguments mapping described in
[ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef](./type_defs.md#listrequestedservicequotachangehistoryrequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str`
- `Status`: [RequestStatusType](./literals.md#requeststatustype)
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListRequestedServiceQuotaChangeHistoryResponseTypeDef](./type_defs.md#listrequestedservicequotachangehistoryresponsetypedef).

<a id="list_requested_service_quota_change_history_by_quota"></a>

### list_requested_service_quota_change_history_by_quota

Retrieves the quota increase requests for the specified quota.

Type annotations for
`aiobotocore.create_client("service-quotas").list_requested_service_quota_change_history_by_quota`
method.

Boto3 documentation:
[ServiceQuotas.Client.list_requested_service_quota_change_history_by_quota](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.list_requested_service_quota_change_history_by_quota)

Asynchronous method. Use
`await list_requested_service_quota_change_history_by_quota(...)` for a
synchronous call.

Arguments mapping described in
[ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef](./type_defs.md#listrequestedservicequotachangehistorybyquotarequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `QuotaCode`: `str` *(required)*
- `Status`: [RequestStatusType](./literals.md#requeststatustype)
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef](./type_defs.md#listrequestedservicequotachangehistorybyquotaresponsetypedef).

<a id="list_service_quota_increase_requests_in_template"></a>

### list_service_quota_increase_requests_in_template

Lists the quota increase requests in the specified quota request template.

Type annotations for
`aiobotocore.create_client("service-quotas").list_service_quota_increase_requests_in_template`
method.

Boto3 documentation:
[ServiceQuotas.Client.list_service_quota_increase_requests_in_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.list_service_quota_increase_requests_in_template)

Asynchronous method. Use
`await list_service_quota_increase_requests_in_template(...)` for a synchronous
call.

Arguments mapping described in
[ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef](./type_defs.md#listservicequotaincreaserequestsintemplaterequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str`
- `AwsRegion`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef](./type_defs.md#listservicequotaincreaserequestsintemplateresponsetypedef).

<a id="list_service_quotas"></a>

### list_service_quotas

Lists the applied quota values for the specified AWS service.

Type annotations for
`aiobotocore.create_client("service-quotas").list_service_quotas` method.

Boto3 documentation:
[ServiceQuotas.Client.list_service_quotas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.list_service_quotas)

Asynchronous method. Use `await list_service_quotas(...)` for a synchronous
call.

Arguments mapping described in
[ListServiceQuotasRequestRequestTypeDef](./type_defs.md#listservicequotasrequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListServiceQuotasResponseTypeDef](./type_defs.md#listservicequotasresponsetypedef).

<a id="list_services"></a>

### list_services

Lists the names and codes for the services integrated with Service Quotas.

Type annotations for
`aiobotocore.create_client("service-quotas").list_services` method.

Boto3 documentation:
[ServiceQuotas.Client.list_services](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.list_services)

Asynchronous method. Use `await list_services(...)` for a synchronous call.

Arguments mapping described in
[ListServicesRequestRequestTypeDef](./type_defs.md#listservicesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListServicesResponseTypeDef](./type_defs.md#listservicesresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Returns a list of the tags assigned to the specified applied quota.

Type annotations for
`aiobotocore.create_client("service-quotas").list_tags_for_resource` method.

Boto3 documentation:
[ServiceQuotas.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_service_quota_increase_request_into_template"></a>

### put_service_quota_increase_request_into_template

Adds a quota increase request to your quota request template.

Type annotations for
`aiobotocore.create_client("service-quotas").put_service_quota_increase_request_into_template`
method.

Boto3 documentation:
[ServiceQuotas.Client.put_service_quota_increase_request_into_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.put_service_quota_increase_request_into_template)

Asynchronous method. Use
`await put_service_quota_increase_request_into_template(...)` for a synchronous
call.

Arguments mapping described in
[PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef](./type_defs.md#putservicequotaincreaserequestintotemplaterequestrequesttypedef).

Keyword-only arguments:

- `QuotaCode`: `str` *(required)*
- `ServiceCode`: `str` *(required)*
- `AwsRegion`: `str` *(required)*
- `DesiredValue`: `float` *(required)*

Returns a `Coroutine` for
[PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef](./type_defs.md#putservicequotaincreaserequestintotemplateresponsetypedef).

<a id="request_service_quota_increase"></a>

### request_service_quota_increase

Submits a quota increase request for the specified quota.

Type annotations for
`aiobotocore.create_client("service-quotas").request_service_quota_increase`
method.

Boto3 documentation:
[ServiceQuotas.Client.request_service_quota_increase](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.request_service_quota_increase)

Asynchronous method. Use `await request_service_quota_increase(...)` for a
synchronous call.

Arguments mapping described in
[RequestServiceQuotaIncreaseRequestRequestTypeDef](./type_defs.md#requestservicequotaincreaserequestrequesttypedef).

Keyword-only arguments:

- `ServiceCode`: `str` *(required)*
- `QuotaCode`: `str` *(required)*
- `DesiredValue`: `float` *(required)*

Returns a `Coroutine` for
[RequestServiceQuotaIncreaseResponseTypeDef](./type_defs.md#requestservicequotaincreaseresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds tags to the specified applied quota.

Type annotations for `aiobotocore.create_client("service-quotas").tag_resource`
method.

Boto3 documentation:
[ServiceQuotas.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from the specified applied quota.

Type annotations for
`aiobotocore.create_client("service-quotas").untag_resource` method.

Boto3 documentation:
[ServiceQuotas.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("service-quotas").get_paginator` method with
overloads.

- `client.get_paginator("list_aws_default_service_quotas")` ->
  [ListAWSDefaultServiceQuotasPaginator](./paginators.md#listawsdefaultservicequotaspaginator)
- `client.get_paginator("list_requested_service_quota_change_history")` ->
  [ListRequestedServiceQuotaChangeHistoryPaginator](./paginators.md#listrequestedservicequotachangehistorypaginator)
- `client.get_paginator("list_requested_service_quota_change_history_by_quota")`
  ->
  [ListRequestedServiceQuotaChangeHistoryByQuotaPaginator](./paginators.md#listrequestedservicequotachangehistorybyquotapaginator)
- `client.get_paginator("list_service_quota_increase_requests_in_template")` ->
  [ListServiceQuotaIncreaseRequestsInTemplatePaginator](./paginators.md#listservicequotaincreaserequestsintemplatepaginator)
- `client.get_paginator("list_service_quotas")` ->
  [ListServiceQuotasPaginator](./paginators.md#listservicequotaspaginator)
- `client.get_paginator("list_services")` ->
  [ListServicesPaginator](./paginators.md#listservicespaginator)
