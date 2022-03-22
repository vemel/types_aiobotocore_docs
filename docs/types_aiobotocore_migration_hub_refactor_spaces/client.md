<a id="migrationhubrefactorspacesclient-for-aiobotocore-migrationhubrefactorspaces-module"></a>

# MigrationHubRefactorSpacesClient for aiobotocore MigrationHubRefactorSpaces module

> [Index](../README.md) > [MigrationHubRefactorSpaces](./README.md) >
> MigrationHubRefactorSpacesClient

Auto-generated documentation for
[MigrationHubRefactorSpaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces)
type annotations stubs module
[types-aiobotocore-migration-hub-refactor-spaces](https://pypi.org/project/types-aiobotocore-migration-hub-refactor-spaces/).

- [MigrationHubRefactorSpacesClient for aiobotocore MigrationHubRefactorSpaces module](#migrationhubrefactorspacesclient-for-aiobotocore-migrationhubrefactorspaces-module)
  - [MigrationHubRefactorSpacesClient](#migrationhubrefactorspacesclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_application](#create_application)
    - [create_environment](#create_environment)
    - [create_route](#create_route)
    - [create_service](#create_service)
    - [delete_application](#delete_application)
    - [delete_environment](#delete_environment)
    - [delete_resource_policy](#delete_resource_policy)
    - [delete_route](#delete_route)
    - [delete_service](#delete_service)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_application](#get_application)
    - [get_environment](#get_environment)
    - [get_resource_policy](#get_resource_policy)
    - [get_route](#get_route)
    - [get_service](#get_service)
    - [list_applications](#list_applications)
    - [list_environment_vpcs](#list_environment_vpcs)
    - [list_environments](#list_environments)
    - [list_routes](#list_routes)
    - [list_services](#list_services)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_resource_policy](#put_resource_policy)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="migrationhubrefactorspacesclient"></a>

## MigrationHubRefactorSpacesClient

Type annotations for `session.create_client("migration-hub-refactor-spaces")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_migration_hub_refactor_spaces.client import MigrationHubRefactorSpacesClient

session = get_session()
async with session.create_client("migration-hub-refactor-spaces") as client:
    client: MigrationHubRefactorSpacesClient
```

Boto3 documentation:
[MigrationHubRefactorSpaces.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_migration_hub_refactor_spaces.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.InvalidResourcePolicyException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

MigrationHubRefactorSpacesClient exceptions.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").exceptions` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").can_paginate` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_application"></a>

### create_application

Creates an Amazon Web Services Migration Hub Refactor Spaces application.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").create_application`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.create_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.create_application)

Asynchronous method. Use `await create_application(...)` for a synchronous
call.

Arguments mapping described in
[CreateApplicationRequestRequestTypeDef](./type_defs.md#createapplicationrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentIdentifier`: `str` *(required)*
- `Name`: `str` *(required)*
- `ProxyType`: `Literal['API_GATEWAY']` (see
  [ProxyTypeType](./literals.md#proxytypetype)) *(required)*
- `VpcId`: `str` *(required)*
- `ApiGatewayProxy`:
  [ApiGatewayProxyInputTypeDef](./type_defs.md#apigatewayproxyinputtypedef)
- `ClientToken`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateApplicationResponseTypeDef](./type_defs.md#createapplicationresponsetypedef).

<a id="create\_environment"></a>

### create_environment

Creates an Amazon Web Services Migration Hub Refactor Spaces environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").create_environment`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.create_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.create_environment)

Asynchronous method. Use `await create_environment(...)` for a synchronous
call.

Arguments mapping described in
[CreateEnvironmentRequestRequestTypeDef](./type_defs.md#createenvironmentrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `NetworkFabricType`: `Literal['TRANSIT_GATEWAY']` (see
  [NetworkFabricTypeType](./literals.md#networkfabrictypetype)) *(required)*
- `ClientToken`: `str`
- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateEnvironmentResponseTypeDef](./type_defs.md#createenvironmentresponsetypedef).

<a id="create\_route"></a>

### create_route

Creates an Amazon Web Services Migration Hub Refactor Spaces route.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").create_route` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.create_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.create_route)

Asynchronous method. Use `await create_route(...)` for a synchronous call.

Arguments mapping described in
[CreateRouteRequestRequestTypeDef](./type_defs.md#createrouterequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `RouteType`: [RouteTypeType](./literals.md#routetypetype) *(required)*
- `ServiceIdentifier`: `str` *(required)*
- `ClientToken`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `UriPathRoute`:
  [UriPathRouteInputTypeDef](./type_defs.md#uripathrouteinputtypedef)

Returns a `Coroutine` for
[CreateRouteResponseTypeDef](./type_defs.md#createrouteresponsetypedef).

<a id="create\_service"></a>

### create_service

Creates an Amazon Web Services Migration Hub Refactor Spaces service.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").create_service` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.create_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.create_service)

Asynchronous method. Use `await create_service(...)` for a synchronous call.

Arguments mapping described in
[CreateServiceRequestRequestTypeDef](./type_defs.md#createservicerequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EndpointType`:
  [ServiceEndpointTypeType](./literals.md#serviceendpointtypetype) *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `Name`: `str` *(required)*
- `ClientToken`: `str`
- `Description`: `str`
- `LambdaEndpoint`:
  [LambdaEndpointInputTypeDef](./type_defs.md#lambdaendpointinputtypedef)
- `Tags`: `Mapping`\[`str`, `str`\]
- `UrlEndpoint`:
  [UrlEndpointInputTypeDef](./type_defs.md#urlendpointinputtypedef)
- `VpcId`: `str`

Returns a `Coroutine` for
[CreateServiceResponseTypeDef](./type_defs.md#createserviceresponsetypedef).

<a id="delete\_application"></a>

### delete_application

Deletes an Amazon Web Services Migration Hub Refactor Spaces application.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").delete_application`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.delete_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.delete_application)

Asynchronous method. Use `await delete_application(...)` for a synchronous
call.

Arguments mapping described in
[DeleteApplicationRequestRequestTypeDef](./type_defs.md#deleteapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[DeleteApplicationResponseTypeDef](./type_defs.md#deleteapplicationresponsetypedef).

<a id="delete\_environment"></a>

### delete_environment

Deletes an Amazon Web Services Migration Hub Refactor Spaces environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").delete_environment`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.delete_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.delete_environment)

Asynchronous method. Use `await delete_environment(...)` for a synchronous
call.

Arguments mapping described in
[DeleteEnvironmentRequestRequestTypeDef](./type_defs.md#deleteenvironmentrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[DeleteEnvironmentResponseTypeDef](./type_defs.md#deleteenvironmentresponsetypedef).

<a id="delete\_resource\_policy"></a>

### delete_resource_policy

Deletes the resource policy set for the environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").delete_resource_policy`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.delete_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.delete_resource_policy)

Asynchronous method. Use `await delete_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResourcePolicyRequestRequestTypeDef](./type_defs.md#deleteresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `Identifier`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_route"></a>

### delete_route

Deletes an Amazon Web Services Migration Hub Refactor Spaces route.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").delete_route` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.delete_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.delete_route)

Asynchronous method. Use `await delete_route(...)` for a synchronous call.

Arguments mapping described in
[DeleteRouteRequestRequestTypeDef](./type_defs.md#deleterouterequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `RouteIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[DeleteRouteResponseTypeDef](./type_defs.md#deleterouteresponsetypedef).

<a id="delete\_service"></a>

### delete_service

Deletes an Amazon Web Services Migration Hub Refactor Spaces service.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").delete_service` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.delete_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.delete_service)

Asynchronous method. Use `await delete_service(...)` for a synchronous call.

Arguments mapping described in
[DeleteServiceRequestRequestTypeDef](./type_defs.md#deleteservicerequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `ServiceIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[DeleteServiceResponseTypeDef](./type_defs.md#deleteserviceresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").generate_presigned_url`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_application"></a>

### get_application

Gets an Amazon Web Services Migration Hub Refactor Spaces application.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").get_application`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.get_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.get_application)

Asynchronous method. Use `await get_application(...)` for a synchronous call.

Arguments mapping described in
[GetApplicationRequestRequestTypeDef](./type_defs.md#getapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[GetApplicationResponseTypeDef](./type_defs.md#getapplicationresponsetypedef).

<a id="get\_environment"></a>

### get_environment

Gets an Amazon Web Services Migration Hub Refactor Spaces environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").get_environment`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.get_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.get_environment)

Asynchronous method. Use `await get_environment(...)` for a synchronous call.

Arguments mapping described in
[GetEnvironmentRequestRequestTypeDef](./type_defs.md#getenvironmentrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[GetEnvironmentResponseTypeDef](./type_defs.md#getenvironmentresponsetypedef).

<a id="get\_resource\_policy"></a>

### get_resource_policy

Gets the resource-based permission policy that is set for the given
environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").get_resource_policy`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.get_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.get_resource_policy)

Asynchronous method. Use `await get_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetResourcePolicyRequestRequestTypeDef](./type_defs.md#getresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `Identifier`: `str` *(required)*

Returns a `Coroutine` for
[GetResourcePolicyResponseTypeDef](./type_defs.md#getresourcepolicyresponsetypedef).

<a id="get\_route"></a>

### get_route

Gets an Amazon Web Services Migration Hub Refactor Spaces route.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").get_route` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.get_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.get_route)

Asynchronous method. Use `await get_route(...)` for a synchronous call.

Arguments mapping described in
[GetRouteRequestRequestTypeDef](./type_defs.md#getrouterequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `RouteIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[GetRouteResponseTypeDef](./type_defs.md#getrouteresponsetypedef).

<a id="get\_service"></a>

### get_service

Gets an Amazon Web Services Migration Hub Refactor Spaces service.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").get_service` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.get_service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.get_service)

Asynchronous method. Use `await get_service(...)` for a synchronous call.

Arguments mapping described in
[GetServiceRequestRequestTypeDef](./type_defs.md#getservicerequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `ServiceIdentifier`: `str` *(required)*

Returns a `Coroutine` for
[GetServiceResponseTypeDef](./type_defs.md#getserviceresponsetypedef).

<a id="list\_applications"></a>

### list_applications

Lists all the Amazon Web Services Migration Hub Refactor Spaces applications
within an environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").list_applications`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.list_applications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.list_applications)

Asynchronous method. Use `await list_applications(...)` for a synchronous call.

Arguments mapping described in
[ListApplicationsRequestRequestTypeDef](./type_defs.md#listapplicationsrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentIdentifier`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListApplicationsResponseTypeDef](./type_defs.md#listapplicationsresponsetypedef).

<a id="list\_environment\_vpcs"></a>

### list_environment_vpcs

Lists all Amazon Web Services Migration Hub Refactor Spaces service virtual
private clouds (VPCs) that are part of the environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").list_environment_vpcs`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.list_environment_vpcs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.list_environment_vpcs)

Asynchronous method. Use `await list_environment_vpcs(...)` for a synchronous
call.

Arguments mapping described in
[ListEnvironmentVpcsRequestRequestTypeDef](./type_defs.md#listenvironmentvpcsrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentIdentifier`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListEnvironmentVpcsResponseTypeDef](./type_defs.md#listenvironmentvpcsresponsetypedef).

<a id="list\_environments"></a>

### list_environments

Lists Amazon Web Services Migration Hub Refactor Spaces environments owned by a
caller account or shared with the caller account.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").list_environments`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.list_environments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.list_environments)

Asynchronous method. Use `await list_environments(...)` for a synchronous call.

Arguments mapping described in
[ListEnvironmentsRequestRequestTypeDef](./type_defs.md#listenvironmentsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListEnvironmentsResponseTypeDef](./type_defs.md#listenvironmentsresponsetypedef).

<a id="list\_routes"></a>

### list_routes

Lists all the Amazon Web Services Migration Hub Refactor Spaces routes within
an application.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").list_routes` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.list_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.list_routes)

Asynchronous method. Use `await list_routes(...)` for a synchronous call.

Arguments mapping described in
[ListRoutesRequestRequestTypeDef](./type_defs.md#listroutesrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListRoutesResponseTypeDef](./type_defs.md#listroutesresponsetypedef).

<a id="list\_services"></a>

### list_services

Lists all the Amazon Web Services Migration Hub Refactor Spaces services within
an application.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").list_services` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.list_services](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.list_services)

Asynchronous method. Use `await list_services(...)` for a synchronous call.

Arguments mapping described in
[ListServicesRequestRequestTypeDef](./type_defs.md#listservicesrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationIdentifier`: `str` *(required)*
- `EnvironmentIdentifier`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListServicesResponseTypeDef](./type_defs.md#listservicesresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Lists the tags of a resource.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").list_tags_for_resource`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put\_resource\_policy"></a>

### put_resource_policy

Attaches a resource-based permission policy to the Amazon Web Services
Migration Hub Refactor Spaces environment.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").put_resource_policy`
method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.put_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.put_resource_policy)

Asynchronous method. Use `await put_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutResourcePolicyRequestRequestTypeDef](./type_defs.md#putresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `Policy`: `str` *(required)*
- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag\_resource"></a>

### tag_resource

Removes the tags of a given resource.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").tag_resource` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Adds to or modifies the tags of the given resource.

Type annotations for
`session.create_client("migration-hub-refactor-spaces").untag_resource` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for
`session.create_client("migration-hub-refactor-spaces").__aenter__` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for
[MigrationHubRefactorSpacesClient](#migrationhubrefactorspacesclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for
`session.create_client("migration-hub-refactor-spaces").__aexit__` method.

Boto3 documentation:
[MigrationHubRefactorSpaces.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`session.create_client("migration-hub-refactor-spaces").get_paginator` method
with overloads.

- `client.get_paginator("list_applications")` ->
  [ListApplicationsPaginator](./paginators.md#listapplicationspaginator)
- `client.get_paginator("list_environment_vpcs")` ->
  [ListEnvironmentVpcsPaginator](./paginators.md#listenvironmentvpcspaginator)
- `client.get_paginator("list_environments")` ->
  [ListEnvironmentsPaginator](./paginators.md#listenvironmentspaginator)
- `client.get_paginator("list_routes")` ->
  [ListRoutesPaginator](./paginators.md#listroutespaginator)
- `client.get_paginator("list_services")` ->
  [ListServicesPaginator](./paginators.md#listservicespaginator)
