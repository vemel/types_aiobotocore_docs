<a id="servicediscoveryclient-for-aiobotocore-servicediscovery-module"></a>

# ServiceDiscoveryClient for aiobotocore ServiceDiscovery module

> [Index](..) > [ServiceDiscovery](.) > ServiceDiscoveryClient

Auto-generated documentation for
[ServiceDiscovery](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery)
type annotations stubs module
[types-aiobotocore-servicediscovery](https://pypi.org/project/types-aiobotocore-servicediscovery/).

- [ServiceDiscoveryClient for aiobotocore ServiceDiscovery module](#servicediscoveryclient-for-aiobotocore-servicediscovery-module)
  - [ServiceDiscoveryClient](#servicediscoveryclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_http_namespace](#create_http_namespace)
    - [create_private_dns_namespace](#create_private_dns_namespace)
    - [create_public_dns_namespace](#create_public_dns_namespace)
    - [create_service](#create_service)
    - [delete_namespace](#delete_namespace)
    - [delete_service](#delete_service)
    - [deregister_instance](#deregister_instance)
    - [discover_instances](#discover_instances)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_instance](#get_instance)
    - [get_instances_health_status](#get_instances_health_status)
    - [get_namespace](#get_namespace)
    - [get_operation](#get_operation)
    - [get_service](#get_service)
    - [list_instances](#list_instances)
    - [list_namespaces](#list_namespaces)
    - [list_operations](#list_operations)
    - [list_services](#list_services)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [register_instance](#register_instance)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_http_namespace](#update_http_namespace)
    - [update_instance_custom_health_status](#update_instance_custom_health_status)
    - [update_private_dns_namespace](#update_private_dns_namespace)
    - [update_public_dns_namespace](#update_public_dns_namespace)
    - [update_service](#update_service)
    - [get_paginator](#get_paginator)

<a id="servicediscoveryclient"></a>

## ServiceDiscoveryClient

Type annotations for `aiobotocore.create_client("servicediscovery")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_servicediscovery.client import ServiceDiscoveryClient

def get_servicediscovery_client() -> ServiceDiscoveryClient:
    return Session().client("servicediscovery")
```

Boto3 documentation:
[ServiceDiscovery.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_servicediscovery.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.CustomHealthNotFound`
- `Exceptions.DuplicateRequest`
- `Exceptions.InstanceNotFound`
- `Exceptions.InvalidInput`
- `Exceptions.NamespaceAlreadyExists`
- `Exceptions.NamespaceNotFound`
- `Exceptions.OperationNotFound`
- `Exceptions.RequestLimitExceeded`
- `Exceptions.ResourceInUse`
- `Exceptions.ResourceLimitExceeded`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceAlreadyExists`
- `Exceptions.ServiceNotFound`
- `Exceptions.TooManyTagsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ServiceDiscoveryClient exceptions.

Type annotations for `aiobotocore.create_client("servicediscovery").exceptions`
method.

Boto3 documentation:
[ServiceDiscovery.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("servicediscovery").can_paginate` method.

Boto3 documentation:
[ServiceDiscovery.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_http_namespace"></a>

### create_http_namespace

Creates an HTTP namespace.

Type annotations for
`aiobotocore.create_client("servicediscovery").create_http_namespace` method.

Boto3 documentation:
[ServiceDiscovery.Client.create_http_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.create_http_namespace)

Asynchronous method. Use `await create_http_namespace(...)` for a synchronous
call.

Arguments mapping described in
[CreateHttpNamespaceRequestRequestTypeDef](./type_defs.md#createhttpnamespacerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `CreatorRequestId`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateHttpNamespaceResponseTypeDef](./type_defs.md#createhttpnamespaceresponsetypedef).

<a id="create_private_dns_namespace"></a>

### create_private_dns_namespace

Creates a private namespace based on DNS, which is visible only inside a
specified Amazon VPC.

Type annotations for
`aiobotocore.create_client("servicediscovery").create_private_dns_namespace`
method.

Boto3 documentation:
[ServiceDiscovery.Client.create_private_dns_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.create_private_dns_namespace)

Asynchronous method. Use `await create_private_dns_namespace(...)` for a
synchronous call.

Arguments mapping described in
[CreatePrivateDnsNamespaceRequestRequestTypeDef](./type_defs.md#createprivatednsnamespacerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Vpc`: `str` *(required)*
- `CreatorRequestId`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `Properties`:
  [PrivateDnsNamespacePropertiesTypeDef](./type_defs.md#privatednsnamespacepropertiestypedef)

Returns a `Coroutine` for
[CreatePrivateDnsNamespaceResponseTypeDef](./type_defs.md#createprivatednsnamespaceresponsetypedef).

<a id="create_public_dns_namespace"></a>

### create_public_dns_namespace

Creates a public namespace based on DNS, which is visible on the internet.

Type annotations for
`aiobotocore.create_client("servicediscovery").create_public_dns_namespace`
method.

Boto3 documentation:
[ServiceDiscovery.Client.create_public_dns_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.create_public_dns_namespace)

Asynchronous method. Use `await create_public_dns_namespace(...)` for a
synchronous call.

Arguments mapping described in
[CreatePublicDnsNamespaceRequestRequestTypeDef](./type_defs.md#createpublicdnsnamespacerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `CreatorRequestId`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `Properties`:
  [PublicDnsNamespacePropertiesTypeDef](./type_defs.md#publicdnsnamespacepropertiestypedef)

Returns a `Coroutine` for
[CreatePublicDnsNamespaceResponseTypeDef](./type_defs.md#createpublicdnsnamespaceresponsetypedef).

<a id="create_service"></a>

### create_service

Creates a service.

Type annotations for
`aiobotocore.create_client("servicediscovery").create_service` method.

Boto3 documentation:
[ServiceDiscovery.Client.create_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.create_service)

Asynchronous method. Use `await create_service(...)` for a synchronous call.

Arguments mapping described in
[CreateServiceRequestRequestTypeDef](./type_defs.md#createservicerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `NamespaceId`: `str`
- `CreatorRequestId`: `str`
- `Description`: `str`
- `DnsConfig`: [DnsConfigTypeDef](./type_defs.md#dnsconfigtypedef)
- `HealthCheckConfig`:
  [HealthCheckConfigTypeDef](./type_defs.md#healthcheckconfigtypedef)
- `HealthCheckCustomConfig`:
  [HealthCheckCustomConfigTypeDef](./type_defs.md#healthcheckcustomconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `Type`: `Literal['HTTP']` (see
  [ServiceTypeOptionType](./literals.md#servicetypeoptiontype))

Returns a `Coroutine` for
[CreateServiceResponseTypeDef](./type_defs.md#createserviceresponsetypedef).

<a id="delete_namespace"></a>

### delete_namespace

Deletes a namespace from the current account.

Type annotations for
`aiobotocore.create_client("servicediscovery").delete_namespace` method.

Boto3 documentation:
[ServiceDiscovery.Client.delete_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.delete_namespace)

Asynchronous method. Use `await delete_namespace(...)` for a synchronous call.

Arguments mapping described in
[DeleteNamespaceRequestRequestTypeDef](./type_defs.md#deletenamespacerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*

Returns a `Coroutine` for
[DeleteNamespaceResponseTypeDef](./type_defs.md#deletenamespaceresponsetypedef).

<a id="delete_service"></a>

### delete_service

Deletes a specified service.

Type annotations for
`aiobotocore.create_client("servicediscovery").delete_service` method.

Boto3 documentation:
[ServiceDiscovery.Client.delete_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.delete_service)

Asynchronous method. Use `await delete_service(...)` for a synchronous call.

Arguments mapping described in
[DeleteServiceRequestRequestTypeDef](./type_defs.md#deleteservicerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deregister_instance"></a>

### deregister_instance

Deletes the Amazon Route 53 DNS records and health check, if any, that Cloud
Map created for the specified instance.

Type annotations for
`aiobotocore.create_client("servicediscovery").deregister_instance` method.

Boto3 documentation:
[ServiceDiscovery.Client.deregister_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.deregister_instance)

Asynchronous method. Use `await deregister_instance(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterInstanceRequestRequestTypeDef](./type_defs.md#deregisterinstancerequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `InstanceId`: `str` *(required)*

Returns a `Coroutine` for
[DeregisterInstanceResponseTypeDef](./type_defs.md#deregisterinstanceresponsetypedef).

<a id="discover_instances"></a>

### discover_instances

Discovers registered instances for a specified namespace and service.

Type annotations for
`aiobotocore.create_client("servicediscovery").discover_instances` method.

Boto3 documentation:
[ServiceDiscovery.Client.discover_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.discover_instances)

Asynchronous method. Use `await discover_instances(...)` for a synchronous
call.

Arguments mapping described in
[DiscoverInstancesRequestRequestTypeDef](./type_defs.md#discoverinstancesrequestrequesttypedef).

Keyword-only arguments:

- `NamespaceName`: `str` *(required)*
- `ServiceName`: `str` *(required)*
- `MaxResults`: `int`
- `QueryParameters`: `Mapping`\[`str`, `str`\]
- `OptionalParameters`: `Mapping`\[`str`, `str`\]
- `HealthStatus`:
  [HealthStatusFilterType](./literals.md#healthstatusfiltertype)

Returns a `Coroutine` for
[DiscoverInstancesResponseTypeDef](./type_defs.md#discoverinstancesresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("servicediscovery").generate_presigned_url` method.

Boto3 documentation:
[ServiceDiscovery.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_instance"></a>

### get_instance

Gets information about a specified instance.

Type annotations for
`aiobotocore.create_client("servicediscovery").get_instance` method.

Boto3 documentation:
[ServiceDiscovery.Client.get_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.get_instance)

Asynchronous method. Use `await get_instance(...)` for a synchronous call.

Arguments mapping described in
[GetInstanceRequestRequestTypeDef](./type_defs.md#getinstancerequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `InstanceId`: `str` *(required)*

Returns a `Coroutine` for
[GetInstanceResponseTypeDef](./type_defs.md#getinstanceresponsetypedef).

<a id="get_instances_health_status"></a>

### get_instances_health_status

Gets the current health status (`Healthy` , `Unhealthy` , or `Unknown` ) of one
or more instances that are associated with a specified service.

Type annotations for
`aiobotocore.create_client("servicediscovery").get_instances_health_status`
method.

Boto3 documentation:
[ServiceDiscovery.Client.get_instances_health_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.get_instances_health_status)

Asynchronous method. Use `await get_instances_health_status(...)` for a
synchronous call.

Arguments mapping described in
[GetInstancesHealthStatusRequestRequestTypeDef](./type_defs.md#getinstanceshealthstatusrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `Instances`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetInstancesHealthStatusResponseTypeDef](./type_defs.md#getinstanceshealthstatusresponsetypedef).

<a id="get_namespace"></a>

### get_namespace

Gets information about a namespace.

Type annotations for
`aiobotocore.create_client("servicediscovery").get_namespace` method.

Boto3 documentation:
[ServiceDiscovery.Client.get_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.get_namespace)

Asynchronous method. Use `await get_namespace(...)` for a synchronous call.

Arguments mapping described in
[GetNamespaceRequestRequestTypeDef](./type_defs.md#getnamespacerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*

Returns a `Coroutine` for
[GetNamespaceResponseTypeDef](./type_defs.md#getnamespaceresponsetypedef).

<a id="get_operation"></a>

### get_operation

Gets information about any operation that returns an operation ID in the
response, such as a `CreateService` request.

Type annotations for
`aiobotocore.create_client("servicediscovery").get_operation` method.

Boto3 documentation:
[ServiceDiscovery.Client.get_operation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.get_operation)

Asynchronous method. Use `await get_operation(...)` for a synchronous call.

Arguments mapping described in
[GetOperationRequestRequestTypeDef](./type_defs.md#getoperationrequestrequesttypedef).

Keyword-only arguments:

- `OperationId`: `str` *(required)*

Returns a `Coroutine` for
[GetOperationResponseTypeDef](./type_defs.md#getoperationresponsetypedef).

<a id="get_service"></a>

### get_service

Gets the settings for a specified service.

Type annotations for
`aiobotocore.create_client("servicediscovery").get_service` method.

Boto3 documentation:
[ServiceDiscovery.Client.get_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.get_service)

Asynchronous method. Use `await get_service(...)` for a synchronous call.

Arguments mapping described in
[GetServiceRequestRequestTypeDef](./type_defs.md#getservicerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*

Returns a `Coroutine` for
[GetServiceResponseTypeDef](./type_defs.md#getserviceresponsetypedef).

<a id="list_instances"></a>

### list_instances

Lists summary information about the instances that you registered by using a
specified service.

Type annotations for
`aiobotocore.create_client("servicediscovery").list_instances` method.

Boto3 documentation:
[ServiceDiscovery.Client.list_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.list_instances)

Asynchronous method. Use `await list_instances(...)` for a synchronous call.

Arguments mapping described in
[ListInstancesRequestRequestTypeDef](./type_defs.md#listinstancesrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListInstancesResponseTypeDef](./type_defs.md#listinstancesresponsetypedef).

<a id="list_namespaces"></a>

### list_namespaces

Lists summary information about the namespaces that were created by the current
account.

Type annotations for
`aiobotocore.create_client("servicediscovery").list_namespaces` method.

Boto3 documentation:
[ServiceDiscovery.Client.list_namespaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.list_namespaces)

Asynchronous method. Use `await list_namespaces(...)` for a synchronous call.

Arguments mapping described in
[ListNamespacesRequestRequestTypeDef](./type_defs.md#listnamespacesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`:
  `Sequence`\[[NamespaceFilterTypeDef](./type_defs.md#namespacefiltertypedef)\]

Returns a `Coroutine` for
[ListNamespacesResponseTypeDef](./type_defs.md#listnamespacesresponsetypedef).

<a id="list_operations"></a>

### list_operations

Lists operations that match the criteria that you specify.

Type annotations for
`aiobotocore.create_client("servicediscovery").list_operations` method.

Boto3 documentation:
[ServiceDiscovery.Client.list_operations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.list_operations)

Asynchronous method. Use `await list_operations(...)` for a synchronous call.

Arguments mapping described in
[ListOperationsRequestRequestTypeDef](./type_defs.md#listoperationsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`:
  `Sequence`\[[OperationFilterTypeDef](./type_defs.md#operationfiltertypedef)\]

Returns a `Coroutine` for
[ListOperationsResponseTypeDef](./type_defs.md#listoperationsresponsetypedef).

<a id="list_services"></a>

### list_services

Lists summary information for all the services that are associated with one or
more specified namespaces.

Type annotations for
`aiobotocore.create_client("servicediscovery").list_services` method.

Boto3 documentation:
[ServiceDiscovery.Client.list_services](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.list_services)

Asynchronous method. Use `await list_services(...)` for a synchronous call.

Arguments mapping described in
[ListServicesRequestRequestTypeDef](./type_defs.md#listservicesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`:
  `Sequence`\[[ServiceFilterTypeDef](./type_defs.md#servicefiltertypedef)\]

Returns a `Coroutine` for
[ListServicesResponseTypeDef](./type_defs.md#listservicesresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists tags for the specified resource.

Type annotations for
`aiobotocore.create_client("servicediscovery").list_tags_for_resource` method.

Boto3 documentation:
[ServiceDiscovery.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="register_instance"></a>

### register_instance

Creates or updates one or more records and, optionally, creates a health check
based on the settings in a specified service.

Type annotations for
`aiobotocore.create_client("servicediscovery").register_instance` method.

Boto3 documentation:
[ServiceDiscovery.Client.register_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.register_instance)

Asynchronous method. Use `await register_instance(...)` for a synchronous call.

Arguments mapping described in
[RegisterInstanceRequestRequestTypeDef](./type_defs.md#registerinstancerequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `InstanceId`: `str` *(required)*
- `Attributes`: `Mapping`\[`str`, `str`\] *(required)*
- `CreatorRequestId`: `str`

Returns a `Coroutine` for
[RegisterInstanceResponseTypeDef](./type_defs.md#registerinstanceresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds one or more tags to the specified resource.

Type annotations for
`aiobotocore.create_client("servicediscovery").tag_resource` method.

Boto3 documentation:
[ServiceDiscovery.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes one or more tags from the specified resource.

Type annotations for
`aiobotocore.create_client("servicediscovery").untag_resource` method.

Boto3 documentation:
[ServiceDiscovery.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_http_namespace"></a>

### update_http_namespace

Updates an HTTP namespace.

Type annotations for
`aiobotocore.create_client("servicediscovery").update_http_namespace` method.

Boto3 documentation:
[ServiceDiscovery.Client.update_http_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_http_namespace)

Asynchronous method. Use `await update_http_namespace(...)` for a synchronous
call.

Arguments mapping described in
[UpdateHttpNamespaceRequestRequestTypeDef](./type_defs.md#updatehttpnamespacerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*
- `Namespace`:
  [HttpNamespaceChangeTypeDef](./type_defs.md#httpnamespacechangetypedef)
  *(required)*
- `UpdaterRequestId`: `str`

Returns a `Coroutine` for
[UpdateHttpNamespaceResponseTypeDef](./type_defs.md#updatehttpnamespaceresponsetypedef).

<a id="update_instance_custom_health_status"></a>

### update_instance_custom_health_status

Submits a request to change the health status of a custom health check to
healthy or unhealthy.

Type annotations for
`aiobotocore.create_client("servicediscovery").update_instance_custom_health_status`
method.

Boto3 documentation:
[ServiceDiscovery.Client.update_instance_custom_health_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_instance_custom_health_status)

Asynchronous method. Use `await update_instance_custom_health_status(...)` for
a synchronous call.

Arguments mapping described in
[UpdateInstanceCustomHealthStatusRequestRequestTypeDef](./type_defs.md#updateinstancecustomhealthstatusrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `InstanceId`: `str` *(required)*
- `Status`: [CustomHealthStatusType](./literals.md#customhealthstatustype)
  *(required)*

<a id="update_private_dns_namespace"></a>

### update_private_dns_namespace

Updates a private DNS namespace.

Type annotations for
`aiobotocore.create_client("servicediscovery").update_private_dns_namespace`
method.

Boto3 documentation:
[ServiceDiscovery.Client.update_private_dns_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_private_dns_namespace)

Asynchronous method. Use `await update_private_dns_namespace(...)` for a
synchronous call.

Arguments mapping described in
[UpdatePrivateDnsNamespaceRequestRequestTypeDef](./type_defs.md#updateprivatednsnamespacerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*
- `Namespace`:
  [PrivateDnsNamespaceChangeTypeDef](./type_defs.md#privatednsnamespacechangetypedef)
  *(required)*
- `UpdaterRequestId`: `str`

Returns a `Coroutine` for
[UpdatePrivateDnsNamespaceResponseTypeDef](./type_defs.md#updateprivatednsnamespaceresponsetypedef).

<a id="update_public_dns_namespace"></a>

### update_public_dns_namespace

Updates a public DNS namespace.

Type annotations for
`aiobotocore.create_client("servicediscovery").update_public_dns_namespace`
method.

Boto3 documentation:
[ServiceDiscovery.Client.update_public_dns_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_public_dns_namespace)

Asynchronous method. Use `await update_public_dns_namespace(...)` for a
synchronous call.

Arguments mapping described in
[UpdatePublicDnsNamespaceRequestRequestTypeDef](./type_defs.md#updatepublicdnsnamespacerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*
- `Namespace`:
  [PublicDnsNamespaceChangeTypeDef](./type_defs.md#publicdnsnamespacechangetypedef)
  *(required)*
- `UpdaterRequestId`: `str`

Returns a `Coroutine` for
[UpdatePublicDnsNamespaceResponseTypeDef](./type_defs.md#updatepublicdnsnamespaceresponsetypedef).

<a id="update_service"></a>

### update_service

Submits a request to perform the following operations * Update the TTL setting
for existing `DnsRecords` configurations * Add, update, or delete
`HealthCheckConfig` for a specified service .

Type annotations for
`aiobotocore.create_client("servicediscovery").update_service` method.

Boto3 documentation:
[ServiceDiscovery.Client.update_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_service)

Asynchronous method. Use `await update_service(...)` for a synchronous call.

Arguments mapping described in
[UpdateServiceRequestRequestTypeDef](./type_defs.md#updateservicerequestrequesttypedef).

Keyword-only arguments:

- `Id`: `str` *(required)*
- `Service`: [ServiceChangeTypeDef](./type_defs.md#servicechangetypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateServiceResponseTypeDef](./type_defs.md#updateserviceresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("servicediscovery").get_paginator` method with
overloads.

- `client.get_paginator("list_instances")` ->
  [ListInstancesPaginator](./paginators.md#listinstancespaginator)
- `client.get_paginator("list_namespaces")` ->
  [ListNamespacesPaginator](./paginators.md#listnamespacespaginator)
- `client.get_paginator("list_operations")` ->
  [ListOperationsPaginator](./paginators.md#listoperationspaginator)
- `client.get_paginator("list_services")` ->
  [ListServicesPaginator](./paginators.md#listservicespaginator)
