<a id="apigatewayv2client-for-aiobotocore-apigatewayv2-module"></a>

# ApiGatewayV2Client for aiobotocore ApiGatewayV2 module

> [Index](..) > [ApiGatewayV2](.) > ApiGatewayV2Client

Auto-generated documentation for
[ApiGatewayV2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2)
type annotations stubs module
[types-aiobotocore-apigatewayv2](https://pypi.org/project/types-aiobotocore-apigatewayv2/).

- [ApiGatewayV2Client for aiobotocore ApiGatewayV2 module](#apigatewayv2client-for-aiobotocore-apigatewayv2-module)
  - [ApiGatewayV2Client](#apigatewayv2client)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_api](#create_api)
    - [create_api_mapping](#create_api_mapping)
    - [create_authorizer](#create_authorizer)
    - [create_deployment](#create_deployment)
    - [create_domain_name](#create_domain_name)
    - [create_integration](#create_integration)
    - [create_integration_response](#create_integration_response)
    - [create_model](#create_model)
    - [create_route](#create_route)
    - [create_route_response](#create_route_response)
    - [create_stage](#create_stage)
    - [create_vpc_link](#create_vpc_link)
    - [delete_access_log_settings](#delete_access_log_settings)
    - [delete_api](#delete_api)
    - [delete_api_mapping](#delete_api_mapping)
    - [delete_authorizer](#delete_authorizer)
    - [delete_cors_configuration](#delete_cors_configuration)
    - [delete_deployment](#delete_deployment)
    - [delete_domain_name](#delete_domain_name)
    - [delete_integration](#delete_integration)
    - [delete_integration_response](#delete_integration_response)
    - [delete_model](#delete_model)
    - [delete_route](#delete_route)
    - [delete_route_request_parameter](#delete_route_request_parameter)
    - [delete_route_response](#delete_route_response)
    - [delete_route_settings](#delete_route_settings)
    - [delete_stage](#delete_stage)
    - [delete_vpc_link](#delete_vpc_link)
    - [export_api](#export_api)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_api](#get_api)
    - [get_api_mapping](#get_api_mapping)
    - [get_api_mappings](#get_api_mappings)
    - [get_apis](#get_apis)
    - [get_authorizer](#get_authorizer)
    - [get_authorizers](#get_authorizers)
    - [get_deployment](#get_deployment)
    - [get_deployments](#get_deployments)
    - [get_domain_name](#get_domain_name)
    - [get_domain_names](#get_domain_names)
    - [get_integration](#get_integration)
    - [get_integration_response](#get_integration_response)
    - [get_integration_responses](#get_integration_responses)
    - [get_integrations](#get_integrations)
    - [get_model](#get_model)
    - [get_model_template](#get_model_template)
    - [get_models](#get_models)
    - [get_route](#get_route)
    - [get_route_response](#get_route_response)
    - [get_route_responses](#get_route_responses)
    - [get_routes](#get_routes)
    - [get_stage](#get_stage)
    - [get_stages](#get_stages)
    - [get_tags](#get_tags)
    - [get_vpc_link](#get_vpc_link)
    - [get_vpc_links](#get_vpc_links)
    - [import_api](#import_api)
    - [reimport_api](#reimport_api)
    - [reset_authorizers_cache](#reset_authorizers_cache)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_api](#update_api)
    - [update_api_mapping](#update_api_mapping)
    - [update_authorizer](#update_authorizer)
    - [update_deployment](#update_deployment)
    - [update_domain_name](#update_domain_name)
    - [update_integration](#update_integration)
    - [update_integration_response](#update_integration_response)
    - [update_model](#update_model)
    - [update_route](#update_route)
    - [update_route_response](#update_route_response)
    - [update_stage](#update_stage)
    - [update_vpc_link](#update_vpc_link)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="apigatewayv2client"></a>

## ApiGatewayV2Client

Type annotations for `session.create_client("apigatewayv2")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_apigatewayv2.client import ApiGatewayV2Client

session = get_session()
async with session.create_client("apigatewayv2") as client:
    client: ApiGatewayV2Client
```

Boto3 documentation:
[ApiGatewayV2.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_apigatewayv2.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.NotFoundException`
- `Exceptions.TooManyRequestsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ApiGatewayV2Client exceptions.

Type annotations for `session.create_client("apigatewayv2").exceptions` method.

Boto3 documentation:
[ApiGatewayV2.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("apigatewayv2").can_paginate`
method.

Boto3 documentation:
[ApiGatewayV2.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_api"></a>

### create_api

Creates an Api resource.

Type annotations for `session.create_client("apigatewayv2").create_api` method.

Boto3 documentation:
[ApiGatewayV2.Client.create_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_api)

Asynchronous method. Use `await create_api(...)` for a synchronous call.

Arguments mapping described in
[CreateApiRequestRequestTypeDef](./type_defs.md#createapirequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `ProtocolType`: [ProtocolTypeType](./literals.md#protocoltypetype)
  *(required)*
- `ApiKeySelectionExpression`: `str`
- `CorsConfiguration`: [CorsTypeDef](./type_defs.md#corstypedef)
- `CredentialsArn`: `str`
- `Description`: `str`
- `DisableSchemaValidation`: `bool`
- `DisableExecuteApiEndpoint`: `bool`
- `RouteKey`: `str`
- `RouteSelectionExpression`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `Target`: `str`
- `Version`: `str`

Returns a `Coroutine` for
[CreateApiResponseTypeDef](./type_defs.md#createapiresponsetypedef).

<a id="create_api_mapping"></a>

### create_api_mapping

Creates an API mapping.

Type annotations for `session.create_client("apigatewayv2").create_api_mapping`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_api_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_api_mapping)

Asynchronous method. Use `await create_api_mapping(...)` for a synchronous
call.

Arguments mapping described in
[CreateApiMappingRequestRequestTypeDef](./type_defs.md#createapimappingrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `DomainName`: `str` *(required)*
- `Stage`: `str` *(required)*
- `ApiMappingKey`: `str`

Returns a `Coroutine` for
[CreateApiMappingResponseTypeDef](./type_defs.md#createapimappingresponsetypedef).

<a id="create_authorizer"></a>

### create_authorizer

Creates an Authorizer for an API.

Type annotations for `session.create_client("apigatewayv2").create_authorizer`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_authorizer)

Asynchronous method. Use `await create_authorizer(...)` for a synchronous call.

Arguments mapping described in
[CreateAuthorizerRequestRequestTypeDef](./type_defs.md#createauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `AuthorizerType`: [AuthorizerTypeType](./literals.md#authorizertypetype)
  *(required)*
- `IdentitySource`: `Sequence`\[`str`\] *(required)*
- `Name`: `str` *(required)*
- `AuthorizerCredentialsArn`: `str`
- `AuthorizerPayloadFormatVersion`: `str`
- `AuthorizerResultTtlInSeconds`: `int`
- `AuthorizerUri`: `str`
- `EnableSimpleResponses`: `bool`
- `IdentityValidationExpression`: `str`
- `JwtConfiguration`:
  [JWTConfigurationTypeDef](./type_defs.md#jwtconfigurationtypedef)

Returns a `Coroutine` for
[CreateAuthorizerResponseTypeDef](./type_defs.md#createauthorizerresponsetypedef).

<a id="create_deployment"></a>

### create_deployment

Creates a Deployment for an API.

Type annotations for `session.create_client("apigatewayv2").create_deployment`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_deployment)

Asynchronous method. Use `await create_deployment(...)` for a synchronous call.

Arguments mapping described in
[CreateDeploymentRequestRequestTypeDef](./type_defs.md#createdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `Description`: `str`
- `StageName`: `str`

Returns a `Coroutine` for
[CreateDeploymentResponseTypeDef](./type_defs.md#createdeploymentresponsetypedef).

<a id="create_domain_name"></a>

### create_domain_name

Creates a domain name.

Type annotations for `session.create_client("apigatewayv2").create_domain_name`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_domain_name)

Asynchronous method. Use `await create_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[CreateDomainNameRequestRequestTypeDef](./type_defs.md#createdomainnamerequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `DomainNameConfigurations`:
  `Sequence`\[[DomainNameConfigurationTypeDef](./type_defs.md#domainnameconfigurationtypedef)\]
- `MutualTlsAuthentication`:
  [MutualTlsAuthenticationInputTypeDef](./type_defs.md#mutualtlsauthenticationinputtypedef)
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateDomainNameResponseTypeDef](./type_defs.md#createdomainnameresponsetypedef).

<a id="create_integration"></a>

### create_integration

Creates an Integration.

Type annotations for `session.create_client("apigatewayv2").create_integration`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_integration)

Asynchronous method. Use `await create_integration(...)` for a synchronous
call.

Arguments mapping described in
[CreateIntegrationRequestRequestTypeDef](./type_defs.md#createintegrationrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationType`: [IntegrationTypeType](./literals.md#integrationtypetype)
  *(required)*
- `ConnectionId`: `str`
- `ConnectionType`: [ConnectionTypeType](./literals.md#connectiontypetype)
- `ContentHandlingStrategy`:
  [ContentHandlingStrategyType](./literals.md#contenthandlingstrategytype)
- `CredentialsArn`: `str`
- `Description`: `str`
- `IntegrationMethod`: `str`
- `IntegrationSubtype`: `str`
- `IntegrationUri`: `str`
- `PassthroughBehavior`:
  [PassthroughBehaviorType](./literals.md#passthroughbehaviortype)
- `PayloadFormatVersion`: `str`
- `RequestParameters`: `Mapping`\[`str`, `str`\]
- `RequestTemplates`: `Mapping`\[`str`, `str`\]
- `ResponseParameters`: `Mapping`\[`str`, `Mapping`\[`str`, `str`\]\]
- `TemplateSelectionExpression`: `str`
- `TimeoutInMillis`: `int`
- `TlsConfig`: [TlsConfigInputTypeDef](./type_defs.md#tlsconfiginputtypedef)

Returns a `Coroutine` for
[CreateIntegrationResultTypeDef](./type_defs.md#createintegrationresulttypedef).

<a id="create_integration_response"></a>

### create_integration_response

Creates an IntegrationResponses.

Type annotations for
`session.create_client("apigatewayv2").create_integration_response` method.

Boto3 documentation:
[ApiGatewayV2.Client.create_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_integration_response)

Asynchronous method. Use `await create_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[CreateIntegrationResponseRequestRequestTypeDef](./type_defs.md#createintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*
- `IntegrationResponseKey`: `str` *(required)*
- `ContentHandlingStrategy`:
  [ContentHandlingStrategyType](./literals.md#contenthandlingstrategytype)
- `ResponseParameters`: `Mapping`\[`str`, `str`\]
- `ResponseTemplates`: `Mapping`\[`str`, `str`\]
- `TemplateSelectionExpression`: `str`

Returns a `Coroutine` for
[CreateIntegrationResponseResponseTypeDef](./type_defs.md#createintegrationresponseresponsetypedef).

<a id="create_model"></a>

### create_model

Creates a Model for an API.

Type annotations for `session.create_client("apigatewayv2").create_model`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_model)

Asynchronous method. Use `await create_model(...)` for a synchronous call.

Arguments mapping described in
[CreateModelRequestRequestTypeDef](./type_defs.md#createmodelrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Schema`: `str` *(required)*
- `ContentType`: `str`
- `Description`: `str`

Returns a `Coroutine` for
[CreateModelResponseTypeDef](./type_defs.md#createmodelresponsetypedef).

<a id="create_route"></a>

### create_route

Creates a Route for an API.

Type annotations for `session.create_client("apigatewayv2").create_route`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_route)

Asynchronous method. Use `await create_route(...)` for a synchronous call.

Arguments mapping described in
[CreateRouteRequestRequestTypeDef](./type_defs.md#createrouterequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteKey`: `str` *(required)*
- `ApiKeyRequired`: `bool`
- `AuthorizationScopes`: `Sequence`\[`str`\]
- `AuthorizationType`:
  [AuthorizationTypeType](./literals.md#authorizationtypetype)
- `AuthorizerId`: `str`
- `ModelSelectionExpression`: `str`
- `OperationName`: `str`
- `RequestModels`: `Mapping`\[`str`, `str`\]
- `RequestParameters`: `Mapping`\[`str`,
  [ParameterConstraintsTypeDef](./type_defs.md#parameterconstraintstypedef)\]
- `RouteResponseSelectionExpression`: `str`
- `Target`: `str`

Returns a `Coroutine` for
[CreateRouteResultTypeDef](./type_defs.md#createrouteresulttypedef).

<a id="create_route_response"></a>

### create_route_response

Creates a RouteResponse for a Route.

Type annotations for
`session.create_client("apigatewayv2").create_route_response` method.

Boto3 documentation:
[ApiGatewayV2.Client.create_route_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_route_response)

Asynchronous method. Use `await create_route_response(...)` for a synchronous
call.

Arguments mapping described in
[CreateRouteResponseRequestRequestTypeDef](./type_defs.md#createrouteresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*
- `RouteResponseKey`: `str` *(required)*
- `ModelSelectionExpression`: `str`
- `ResponseModels`: `Mapping`\[`str`, `str`\]
- `ResponseParameters`: `Mapping`\[`str`,
  [ParameterConstraintsTypeDef](./type_defs.md#parameterconstraintstypedef)\]

Returns a `Coroutine` for
[CreateRouteResponseResponseTypeDef](./type_defs.md#createrouteresponseresponsetypedef).

<a id="create_stage"></a>

### create_stage

Creates a Stage for an API.

Type annotations for `session.create_client("apigatewayv2").create_stage`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_stage)

Asynchronous method. Use `await create_stage(...)` for a synchronous call.

Arguments mapping described in
[CreateStageRequestRequestTypeDef](./type_defs.md#createstagerequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `StageName`: `str` *(required)*
- `AccessLogSettings`:
  [AccessLogSettingsTypeDef](./type_defs.md#accesslogsettingstypedef)
- `AutoDeploy`: `bool`
- `ClientCertificateId`: `str`
- `DefaultRouteSettings`:
  [RouteSettingsTypeDef](./type_defs.md#routesettingstypedef)
- `DeploymentId`: `str`
- `Description`: `str`
- `RouteSettings`: `Mapping`\[`str`,
  [RouteSettingsTypeDef](./type_defs.md#routesettingstypedef)\]
- `StageVariables`: `Mapping`\[`str`, `str`\]
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateStageResponseTypeDef](./type_defs.md#createstageresponsetypedef).

<a id="create_vpc_link"></a>

### create_vpc_link

Creates a VPC link.

Type annotations for `session.create_client("apigatewayv2").create_vpc_link`
method.

Boto3 documentation:
[ApiGatewayV2.Client.create_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.create_vpc_link)

Asynchronous method. Use `await create_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[CreateVpcLinkRequestRequestTypeDef](./type_defs.md#createvpclinkrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateVpcLinkResponseTypeDef](./type_defs.md#createvpclinkresponsetypedef).

<a id="delete_access_log_settings"></a>

### delete_access_log_settings

Deletes the AccessLogSettings for a Stage.

Type annotations for
`session.create_client("apigatewayv2").delete_access_log_settings` method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_access_log_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_access_log_settings)

Asynchronous method. Use `await delete_access_log_settings(...)` for a
synchronous call.

Arguments mapping described in
[DeleteAccessLogSettingsRequestRequestTypeDef](./type_defs.md#deleteaccesslogsettingsrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `StageName`: `str` *(required)*

<a id="delete_api"></a>

### delete_api

Deletes an Api resource.

Type annotations for `session.create_client("apigatewayv2").delete_api` method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_api)

Asynchronous method. Use `await delete_api(...)` for a synchronous call.

Arguments mapping described in
[DeleteApiRequestRequestTypeDef](./type_defs.md#deleteapirequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*

<a id="delete_api_mapping"></a>

### delete_api_mapping

Deletes an API mapping.

Type annotations for `session.create_client("apigatewayv2").delete_api_mapping`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_api_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_api_mapping)

Asynchronous method. Use `await delete_api_mapping(...)` for a synchronous
call.

Arguments mapping described in
[DeleteApiMappingRequestRequestTypeDef](./type_defs.md#deleteapimappingrequestrequesttypedef).

Keyword-only arguments:

- `ApiMappingId`: `str` *(required)*
- `DomainName`: `str` *(required)*

<a id="delete_authorizer"></a>

### delete_authorizer

Deletes an Authorizer.

Type annotations for `session.create_client("apigatewayv2").delete_authorizer`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_authorizer)

Asynchronous method. Use `await delete_authorizer(...)` for a synchronous call.

Arguments mapping described in
[DeleteAuthorizerRequestRequestTypeDef](./type_defs.md#deleteauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `AuthorizerId`: `str` *(required)*

<a id="delete_cors_configuration"></a>

### delete_cors_configuration

Deletes a CORS configuration.

Type annotations for
`session.create_client("apigatewayv2").delete_cors_configuration` method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_cors_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_cors_configuration)

Asynchronous method. Use `await delete_cors_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCorsConfigurationRequestRequestTypeDef](./type_defs.md#deletecorsconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*

<a id="delete_deployment"></a>

### delete_deployment

Deletes a Deployment.

Type annotations for `session.create_client("apigatewayv2").delete_deployment`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_deployment)

Asynchronous method. Use `await delete_deployment(...)` for a synchronous call.

Arguments mapping described in
[DeleteDeploymentRequestRequestTypeDef](./type_defs.md#deletedeploymentrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `DeploymentId`: `str` *(required)*

<a id="delete_domain_name"></a>

### delete_domain_name

Deletes a domain name.

Type annotations for `session.create_client("apigatewayv2").delete_domain_name`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_domain_name)

Asynchronous method. Use `await delete_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[DeleteDomainNameRequestRequestTypeDef](./type_defs.md#deletedomainnamerequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*

<a id="delete_integration"></a>

### delete_integration

Deletes an Integration.

Type annotations for `session.create_client("apigatewayv2").delete_integration`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_integration)

Asynchronous method. Use `await delete_integration(...)` for a synchronous
call.

Arguments mapping described in
[DeleteIntegrationRequestRequestTypeDef](./type_defs.md#deleteintegrationrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*

<a id="delete_integration_response"></a>

### delete_integration_response

Deletes an IntegrationResponses.

Type annotations for
`session.create_client("apigatewayv2").delete_integration_response` method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_integration_response)

Asynchronous method. Use `await delete_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[DeleteIntegrationResponseRequestRequestTypeDef](./type_defs.md#deleteintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*
- `IntegrationResponseId`: `str` *(required)*

<a id="delete_model"></a>

### delete_model

Deletes a Model.

Type annotations for `session.create_client("apigatewayv2").delete_model`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_model)

Asynchronous method. Use `await delete_model(...)` for a synchronous call.

Arguments mapping described in
[DeleteModelRequestRequestTypeDef](./type_defs.md#deletemodelrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `ModelId`: `str` *(required)*

<a id="delete_route"></a>

### delete_route

Deletes a Route.

Type annotations for `session.create_client("apigatewayv2").delete_route`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_route)

Asynchronous method. Use `await delete_route(...)` for a synchronous call.

Arguments mapping described in
[DeleteRouteRequestRequestTypeDef](./type_defs.md#deleterouterequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*

<a id="delete_route_request_parameter"></a>

### delete_route_request_parameter

Deletes a route request parameter.

Type annotations for
`session.create_client("apigatewayv2").delete_route_request_parameter` method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_route_request_parameter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_route_request_parameter)

Asynchronous method. Use `await delete_route_request_parameter(...)` for a
synchronous call.

Arguments mapping described in
[DeleteRouteRequestParameterRequestRequestTypeDef](./type_defs.md#deleterouterequestparameterrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RequestParameterKey`: `str` *(required)*
- `RouteId`: `str` *(required)*

<a id="delete_route_response"></a>

### delete_route_response

Deletes a RouteResponse.

Type annotations for
`session.create_client("apigatewayv2").delete_route_response` method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_route_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_route_response)

Asynchronous method. Use `await delete_route_response(...)` for a synchronous
call.

Arguments mapping described in
[DeleteRouteResponseRequestRequestTypeDef](./type_defs.md#deleterouteresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*
- `RouteResponseId`: `str` *(required)*

<a id="delete_route_settings"></a>

### delete_route_settings

Deletes the RouteSettings for a stage.

Type annotations for
`session.create_client("apigatewayv2").delete_route_settings` method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_route_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_route_settings)

Asynchronous method. Use `await delete_route_settings(...)` for a synchronous
call.

Arguments mapping described in
[DeleteRouteSettingsRequestRequestTypeDef](./type_defs.md#deleteroutesettingsrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteKey`: `str` *(required)*
- `StageName`: `str` *(required)*

<a id="delete_stage"></a>

### delete_stage

Deletes a Stage.

Type annotations for `session.create_client("apigatewayv2").delete_stage`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_stage)

Asynchronous method. Use `await delete_stage(...)` for a synchronous call.

Arguments mapping described in
[DeleteStageRequestRequestTypeDef](./type_defs.md#deletestagerequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `StageName`: `str` *(required)*

<a id="delete_vpc_link"></a>

### delete_vpc_link

Deletes a VPC link.

Type annotations for `session.create_client("apigatewayv2").delete_vpc_link`
method.

Boto3 documentation:
[ApiGatewayV2.Client.delete_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.delete_vpc_link)

Asynchronous method. Use `await delete_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[DeleteVpcLinkRequestRequestTypeDef](./type_defs.md#deletevpclinkrequestrequesttypedef).

Keyword-only arguments:

- `VpcLinkId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="export_api"></a>

### export_api

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigatewayv2-2018-11-29/ExportApi).

Type annotations for `session.create_client("apigatewayv2").export_api` method.

Boto3 documentation:
[ApiGatewayV2.Client.export_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.export_api)

Asynchronous method. Use `await export_api(...)` for a synchronous call.

Arguments mapping described in
[ExportApiRequestRequestTypeDef](./type_defs.md#exportapirequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `OutputType`: [JSONYAMLType](./literals.md#jsonyamltype) *(required)*
- `Specification`: `Literal['OAS30']` (see
  [OAS30Type](./literals.md#oas30type)) *(required)*
- `ExportVersion`: `str`
- `IncludeExtensions`: `bool`
- `StageName`: `str`

Returns a `Coroutine` for
[ExportApiResponseTypeDef](./type_defs.md#exportapiresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("apigatewayv2").generate_presigned_url` method.

Boto3 documentation:
[ApiGatewayV2.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_api"></a>

### get_api

Gets an Api resource.

Type annotations for `session.create_client("apigatewayv2").get_api` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_api)

Asynchronous method. Use `await get_api(...)` for a synchronous call.

Arguments mapping described in
[GetApiRequestRequestTypeDef](./type_defs.md#getapirequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*

Returns a `Coroutine` for
[GetApiResponseTypeDef](./type_defs.md#getapiresponsetypedef).

<a id="get_api_mapping"></a>

### get_api_mapping

Gets an API mapping.

Type annotations for `session.create_client("apigatewayv2").get_api_mapping`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_api_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_api_mapping)

Asynchronous method. Use `await get_api_mapping(...)` for a synchronous call.

Arguments mapping described in
[GetApiMappingRequestRequestTypeDef](./type_defs.md#getapimappingrequestrequesttypedef).

Keyword-only arguments:

- `ApiMappingId`: `str` *(required)*
- `DomainName`: `str` *(required)*

Returns a `Coroutine` for
[GetApiMappingResponseTypeDef](./type_defs.md#getapimappingresponsetypedef).

<a id="get_api_mappings"></a>

### get_api_mappings

Gets API mappings.

Type annotations for `session.create_client("apigatewayv2").get_api_mappings`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_api_mappings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_api_mappings)

Asynchronous method. Use `await get_api_mappings(...)` for a synchronous call.

Arguments mapping described in
[GetApiMappingsRequestRequestTypeDef](./type_defs.md#getapimappingsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetApiMappingsResponseTypeDef](./type_defs.md#getapimappingsresponsetypedef).

<a id="get_apis"></a>

### get_apis

Gets a collection of Api resources.

Type annotations for `session.create_client("apigatewayv2").get_apis` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_apis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_apis)

Asynchronous method. Use `await get_apis(...)` for a synchronous call.

Arguments mapping described in
[GetApisRequestRequestTypeDef](./type_defs.md#getapisrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetApisResponseTypeDef](./type_defs.md#getapisresponsetypedef).

<a id="get_authorizer"></a>

### get_authorizer

Gets an Authorizer.

Type annotations for `session.create_client("apigatewayv2").get_authorizer`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_authorizer)

Asynchronous method. Use `await get_authorizer(...)` for a synchronous call.

Arguments mapping described in
[GetAuthorizerRequestRequestTypeDef](./type_defs.md#getauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `AuthorizerId`: `str` *(required)*

Returns a `Coroutine` for
[GetAuthorizerResponseTypeDef](./type_defs.md#getauthorizerresponsetypedef).

<a id="get_authorizers"></a>

### get_authorizers

Gets the Authorizers for an API.

Type annotations for `session.create_client("apigatewayv2").get_authorizers`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_authorizers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_authorizers)

Asynchronous method. Use `await get_authorizers(...)` for a synchronous call.

Arguments mapping described in
[GetAuthorizersRequestRequestTypeDef](./type_defs.md#getauthorizersrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetAuthorizersResponseTypeDef](./type_defs.md#getauthorizersresponsetypedef).

<a id="get_deployment"></a>

### get_deployment

Gets a Deployment.

Type annotations for `session.create_client("apigatewayv2").get_deployment`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_deployment)

Asynchronous method. Use `await get_deployment(...)` for a synchronous call.

Arguments mapping described in
[GetDeploymentRequestRequestTypeDef](./type_defs.md#getdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `DeploymentId`: `str` *(required)*

Returns a `Coroutine` for
[GetDeploymentResponseTypeDef](./type_defs.md#getdeploymentresponsetypedef).

<a id="get_deployments"></a>

### get_deployments

Gets the Deployments for an API.

Type annotations for `session.create_client("apigatewayv2").get_deployments`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_deployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_deployments)

Asynchronous method. Use `await get_deployments(...)` for a synchronous call.

Arguments mapping described in
[GetDeploymentsRequestRequestTypeDef](./type_defs.md#getdeploymentsrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetDeploymentsResponseTypeDef](./type_defs.md#getdeploymentsresponsetypedef).

<a id="get_domain_name"></a>

### get_domain_name

Gets a domain name.

Type annotations for `session.create_client("apigatewayv2").get_domain_name`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_domain_name)

Asynchronous method. Use `await get_domain_name(...)` for a synchronous call.

Arguments mapping described in
[GetDomainNameRequestRequestTypeDef](./type_defs.md#getdomainnamerequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*

Returns a `Coroutine` for
[GetDomainNameResponseTypeDef](./type_defs.md#getdomainnameresponsetypedef).

<a id="get_domain_names"></a>

### get_domain_names

Gets the domain names for an AWS account.

Type annotations for `session.create_client("apigatewayv2").get_domain_names`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_domain_names](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_domain_names)

Asynchronous method. Use `await get_domain_names(...)` for a synchronous call.

Arguments mapping described in
[GetDomainNamesRequestRequestTypeDef](./type_defs.md#getdomainnamesrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetDomainNamesResponseTypeDef](./type_defs.md#getdomainnamesresponsetypedef).

<a id="get_integration"></a>

### get_integration

Gets an Integration.

Type annotations for `session.create_client("apigatewayv2").get_integration`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_integration)

Asynchronous method. Use `await get_integration(...)` for a synchronous call.

Arguments mapping described in
[GetIntegrationRequestRequestTypeDef](./type_defs.md#getintegrationrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*

Returns a `Coroutine` for
[GetIntegrationResultTypeDef](./type_defs.md#getintegrationresulttypedef).

<a id="get_integration_response"></a>

### get_integration_response

Gets an IntegrationResponses.

Type annotations for
`session.create_client("apigatewayv2").get_integration_response` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_integration_response)

Asynchronous method. Use `await get_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[GetIntegrationResponseRequestRequestTypeDef](./type_defs.md#getintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*
- `IntegrationResponseId`: `str` *(required)*

Returns a `Coroutine` for
[GetIntegrationResponseResponseTypeDef](./type_defs.md#getintegrationresponseresponsetypedef).

<a id="get_integration_responses"></a>

### get_integration_responses

Gets the IntegrationResponses for an Integration.

Type annotations for
`session.create_client("apigatewayv2").get_integration_responses` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_integration_responses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_integration_responses)

Asynchronous method. Use `await get_integration_responses(...)` for a
synchronous call.

Arguments mapping described in
[GetIntegrationResponsesRequestRequestTypeDef](./type_defs.md#getintegrationresponsesrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetIntegrationResponsesResponseTypeDef](./type_defs.md#getintegrationresponsesresponsetypedef).

<a id="get_integrations"></a>

### get_integrations

Gets the Integrations for an API.

Type annotations for `session.create_client("apigatewayv2").get_integrations`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_integrations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_integrations)

Asynchronous method. Use `await get_integrations(...)` for a synchronous call.

Arguments mapping described in
[GetIntegrationsRequestRequestTypeDef](./type_defs.md#getintegrationsrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetIntegrationsResponseTypeDef](./type_defs.md#getintegrationsresponsetypedef).

<a id="get_model"></a>

### get_model

Gets a Model.

Type annotations for `session.create_client("apigatewayv2").get_model` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_model)

Asynchronous method. Use `await get_model(...)` for a synchronous call.

Arguments mapping described in
[GetModelRequestRequestTypeDef](./type_defs.md#getmodelrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `ModelId`: `str` *(required)*

Returns a `Coroutine` for
[GetModelResponseTypeDef](./type_defs.md#getmodelresponsetypedef).

<a id="get_model_template"></a>

### get_model_template

Gets a model template.

Type annotations for `session.create_client("apigatewayv2").get_model_template`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_model_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_model_template)

Asynchronous method. Use `await get_model_template(...)` for a synchronous
call.

Arguments mapping described in
[GetModelTemplateRequestRequestTypeDef](./type_defs.md#getmodeltemplaterequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `ModelId`: `str` *(required)*

Returns a `Coroutine` for
[GetModelTemplateResponseTypeDef](./type_defs.md#getmodeltemplateresponsetypedef).

<a id="get_models"></a>

### get_models

Gets the Models for an API.

Type annotations for `session.create_client("apigatewayv2").get_models` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_models](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_models)

Asynchronous method. Use `await get_models(...)` for a synchronous call.

Arguments mapping described in
[GetModelsRequestRequestTypeDef](./type_defs.md#getmodelsrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetModelsResponseTypeDef](./type_defs.md#getmodelsresponsetypedef).

<a id="get_route"></a>

### get_route

Gets a Route.

Type annotations for `session.create_client("apigatewayv2").get_route` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_route)

Asynchronous method. Use `await get_route(...)` for a synchronous call.

Arguments mapping described in
[GetRouteRequestRequestTypeDef](./type_defs.md#getrouterequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*

Returns a `Coroutine` for
[GetRouteResultTypeDef](./type_defs.md#getrouteresulttypedef).

<a id="get_route_response"></a>

### get_route_response

Gets a RouteResponse.

Type annotations for `session.create_client("apigatewayv2").get_route_response`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_route_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_route_response)

Asynchronous method. Use `await get_route_response(...)` for a synchronous
call.

Arguments mapping described in
[GetRouteResponseRequestRequestTypeDef](./type_defs.md#getrouteresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*
- `RouteResponseId`: `str` *(required)*

Returns a `Coroutine` for
[GetRouteResponseResponseTypeDef](./type_defs.md#getrouteresponseresponsetypedef).

<a id="get_route_responses"></a>

### get_route_responses

Gets the RouteResponses for a Route.

Type annotations for
`session.create_client("apigatewayv2").get_route_responses` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_route_responses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_route_responses)

Asynchronous method. Use `await get_route_responses(...)` for a synchronous
call.

Arguments mapping described in
[GetRouteResponsesRequestRequestTypeDef](./type_defs.md#getrouteresponsesrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetRouteResponsesResponseTypeDef](./type_defs.md#getrouteresponsesresponsetypedef).

<a id="get_routes"></a>

### get_routes

Gets the Routes for an API.

Type annotations for `session.create_client("apigatewayv2").get_routes` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_routes)

Asynchronous method. Use `await get_routes(...)` for a synchronous call.

Arguments mapping described in
[GetRoutesRequestRequestTypeDef](./type_defs.md#getroutesrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetRoutesResponseTypeDef](./type_defs.md#getroutesresponsetypedef).

<a id="get_stage"></a>

### get_stage

Gets a Stage.

Type annotations for `session.create_client("apigatewayv2").get_stage` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_stage)

Asynchronous method. Use `await get_stage(...)` for a synchronous call.

Arguments mapping described in
[GetStageRequestRequestTypeDef](./type_defs.md#getstagerequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `StageName`: `str` *(required)*

Returns a `Coroutine` for
[GetStageResponseTypeDef](./type_defs.md#getstageresponsetypedef).

<a id="get_stages"></a>

### get_stages

Gets the Stages for an API.

Type annotations for `session.create_client("apigatewayv2").get_stages` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_stages](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_stages)

Asynchronous method. Use `await get_stages(...)` for a synchronous call.

Arguments mapping described in
[GetStagesRequestRequestTypeDef](./type_defs.md#getstagesrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetStagesResponseTypeDef](./type_defs.md#getstagesresponsetypedef).

<a id="get_tags"></a>

### get_tags

Gets a collection of Tag resources.

Type annotations for `session.create_client("apigatewayv2").get_tags` method.

Boto3 documentation:
[ApiGatewayV2.Client.get_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_tags)

Asynchronous method. Use `await get_tags(...)` for a synchronous call.

Arguments mapping described in
[GetTagsRequestRequestTypeDef](./type_defs.md#gettagsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[GetTagsResponseTypeDef](./type_defs.md#gettagsresponsetypedef).

<a id="get_vpc_link"></a>

### get_vpc_link

Gets a VPC link.

Type annotations for `session.create_client("apigatewayv2").get_vpc_link`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_vpc_link)

Asynchronous method. Use `await get_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[GetVpcLinkRequestRequestTypeDef](./type_defs.md#getvpclinkrequestrequesttypedef).

Keyword-only arguments:

- `VpcLinkId`: `str` *(required)*

Returns a `Coroutine` for
[GetVpcLinkResponseTypeDef](./type_defs.md#getvpclinkresponsetypedef).

<a id="get_vpc_links"></a>

### get_vpc_links

Gets a collection of VPC links.

Type annotations for `session.create_client("apigatewayv2").get_vpc_links`
method.

Boto3 documentation:
[ApiGatewayV2.Client.get_vpc_links](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.get_vpc_links)

Asynchronous method. Use `await get_vpc_links(...)` for a synchronous call.

Arguments mapping described in
[GetVpcLinksRequestRequestTypeDef](./type_defs.md#getvpclinksrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetVpcLinksResponseTypeDef](./type_defs.md#getvpclinksresponsetypedef).

<a id="import_api"></a>

### import_api

Imports an API.

Type annotations for `session.create_client("apigatewayv2").import_api` method.

Boto3 documentation:
[ApiGatewayV2.Client.import_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.import_api)

Asynchronous method. Use `await import_api(...)` for a synchronous call.

Arguments mapping described in
[ImportApiRequestRequestTypeDef](./type_defs.md#importapirequestrequesttypedef).

Keyword-only arguments:

- `Body`: `str` *(required)*
- `Basepath`: `str`
- `FailOnWarnings`: `bool`

Returns a `Coroutine` for
[ImportApiResponseTypeDef](./type_defs.md#importapiresponsetypedef).

<a id="reimport_api"></a>

### reimport_api

Puts an Api resource.

Type annotations for `session.create_client("apigatewayv2").reimport_api`
method.

Boto3 documentation:
[ApiGatewayV2.Client.reimport_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.reimport_api)

Asynchronous method. Use `await reimport_api(...)` for a synchronous call.

Arguments mapping described in
[ReimportApiRequestRequestTypeDef](./type_defs.md#reimportapirequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `Body`: `str` *(required)*
- `Basepath`: `str`
- `FailOnWarnings`: `bool`

Returns a `Coroutine` for
[ReimportApiResponseTypeDef](./type_defs.md#reimportapiresponsetypedef).

<a id="reset_authorizers_cache"></a>

### reset_authorizers_cache

Resets all authorizer cache entries on a stage.

Type annotations for
`session.create_client("apigatewayv2").reset_authorizers_cache` method.

Boto3 documentation:
[ApiGatewayV2.Client.reset_authorizers_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.reset_authorizers_cache)

Asynchronous method. Use `await reset_authorizers_cache(...)` for a synchronous
call.

Arguments mapping described in
[ResetAuthorizersCacheRequestRequestTypeDef](./type_defs.md#resetauthorizerscacherequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `StageName`: `str` *(required)*

<a id="tag_resource"></a>

### tag_resource

Creates a new Tag resource to represent a tag.

Type annotations for `session.create_client("apigatewayv2").tag_resource`
method.

Boto3 documentation:
[ApiGatewayV2.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Deletes a Tag.

Type annotations for `session.create_client("apigatewayv2").untag_resource`
method.

Boto3 documentation:
[ApiGatewayV2.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update_api"></a>

### update_api

Updates an Api resource.

Type annotations for `session.create_client("apigatewayv2").update_api` method.

Boto3 documentation:
[ApiGatewayV2.Client.update_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_api)

Asynchronous method. Use `await update_api(...)` for a synchronous call.

Arguments mapping described in
[UpdateApiRequestRequestTypeDef](./type_defs.md#updateapirequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `ApiKeySelectionExpression`: `str`
- `CorsConfiguration`: [CorsTypeDef](./type_defs.md#corstypedef)
- `CredentialsArn`: `str`
- `Description`: `str`
- `DisableSchemaValidation`: `bool`
- `DisableExecuteApiEndpoint`: `bool`
- `Name`: `str`
- `RouteKey`: `str`
- `RouteSelectionExpression`: `str`
- `Target`: `str`
- `Version`: `str`

Returns a `Coroutine` for
[UpdateApiResponseTypeDef](./type_defs.md#updateapiresponsetypedef).

<a id="update_api_mapping"></a>

### update_api_mapping

The API mapping.

Type annotations for `session.create_client("apigatewayv2").update_api_mapping`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_api_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_api_mapping)

Asynchronous method. Use `await update_api_mapping(...)` for a synchronous
call.

Arguments mapping described in
[UpdateApiMappingRequestRequestTypeDef](./type_defs.md#updateapimappingrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `ApiMappingId`: `str` *(required)*
- `DomainName`: `str` *(required)*
- `ApiMappingKey`: `str`
- `Stage`: `str`

Returns a `Coroutine` for
[UpdateApiMappingResponseTypeDef](./type_defs.md#updateapimappingresponsetypedef).

<a id="update_authorizer"></a>

### update_authorizer

Updates an Authorizer.

Type annotations for `session.create_client("apigatewayv2").update_authorizer`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_authorizer)

Asynchronous method. Use `await update_authorizer(...)` for a synchronous call.

Arguments mapping described in
[UpdateAuthorizerRequestRequestTypeDef](./type_defs.md#updateauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `AuthorizerId`: `str` *(required)*
- `AuthorizerCredentialsArn`: `str`
- `AuthorizerPayloadFormatVersion`: `str`
- `AuthorizerResultTtlInSeconds`: `int`
- `AuthorizerType`: [AuthorizerTypeType](./literals.md#authorizertypetype)
- `AuthorizerUri`: `str`
- `EnableSimpleResponses`: `bool`
- `IdentitySource`: `Sequence`\[`str`\]
- `IdentityValidationExpression`: `str`
- `JwtConfiguration`:
  [JWTConfigurationTypeDef](./type_defs.md#jwtconfigurationtypedef)
- `Name`: `str`

Returns a `Coroutine` for
[UpdateAuthorizerResponseTypeDef](./type_defs.md#updateauthorizerresponsetypedef).

<a id="update_deployment"></a>

### update_deployment

Updates a Deployment.

Type annotations for `session.create_client("apigatewayv2").update_deployment`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_deployment)

Asynchronous method. Use `await update_deployment(...)` for a synchronous call.

Arguments mapping described in
[UpdateDeploymentRequestRequestTypeDef](./type_defs.md#updatedeploymentrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `DeploymentId`: `str` *(required)*
- `Description`: `str`

Returns a `Coroutine` for
[UpdateDeploymentResponseTypeDef](./type_defs.md#updatedeploymentresponsetypedef).

<a id="update_domain_name"></a>

### update_domain_name

Updates a domain name.

Type annotations for `session.create_client("apigatewayv2").update_domain_name`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_domain_name)

Asynchronous method. Use `await update_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[UpdateDomainNameRequestRequestTypeDef](./type_defs.md#updatedomainnamerequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `DomainNameConfigurations`:
  `Sequence`\[[DomainNameConfigurationTypeDef](./type_defs.md#domainnameconfigurationtypedef)\]
- `MutualTlsAuthentication`:
  [MutualTlsAuthenticationInputTypeDef](./type_defs.md#mutualtlsauthenticationinputtypedef)

Returns a `Coroutine` for
[UpdateDomainNameResponseTypeDef](./type_defs.md#updatedomainnameresponsetypedef).

<a id="update_integration"></a>

### update_integration

Updates an Integration.

Type annotations for `session.create_client("apigatewayv2").update_integration`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_integration)

Asynchronous method. Use `await update_integration(...)` for a synchronous
call.

Arguments mapping described in
[UpdateIntegrationRequestRequestTypeDef](./type_defs.md#updateintegrationrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*
- `ConnectionId`: `str`
- `ConnectionType`: [ConnectionTypeType](./literals.md#connectiontypetype)
- `ContentHandlingStrategy`:
  [ContentHandlingStrategyType](./literals.md#contenthandlingstrategytype)
- `CredentialsArn`: `str`
- `Description`: `str`
- `IntegrationMethod`: `str`
- `IntegrationSubtype`: `str`
- `IntegrationType`: [IntegrationTypeType](./literals.md#integrationtypetype)
- `IntegrationUri`: `str`
- `PassthroughBehavior`:
  [PassthroughBehaviorType](./literals.md#passthroughbehaviortype)
- `PayloadFormatVersion`: `str`
- `RequestParameters`: `Mapping`\[`str`, `str`\]
- `RequestTemplates`: `Mapping`\[`str`, `str`\]
- `ResponseParameters`: `Mapping`\[`str`, `Mapping`\[`str`, `str`\]\]
- `TemplateSelectionExpression`: `str`
- `TimeoutInMillis`: `int`
- `TlsConfig`: [TlsConfigInputTypeDef](./type_defs.md#tlsconfiginputtypedef)

Returns a `Coroutine` for
[UpdateIntegrationResultTypeDef](./type_defs.md#updateintegrationresulttypedef).

<a id="update_integration_response"></a>

### update_integration_response

Updates an IntegrationResponses.

Type annotations for
`session.create_client("apigatewayv2").update_integration_response` method.

Boto3 documentation:
[ApiGatewayV2.Client.update_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_integration_response)

Asynchronous method. Use `await update_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[UpdateIntegrationResponseRequestRequestTypeDef](./type_defs.md#updateintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `IntegrationId`: `str` *(required)*
- `IntegrationResponseId`: `str` *(required)*
- `ContentHandlingStrategy`:
  [ContentHandlingStrategyType](./literals.md#contenthandlingstrategytype)
- `IntegrationResponseKey`: `str`
- `ResponseParameters`: `Mapping`\[`str`, `str`\]
- `ResponseTemplates`: `Mapping`\[`str`, `str`\]
- `TemplateSelectionExpression`: `str`

Returns a `Coroutine` for
[UpdateIntegrationResponseResponseTypeDef](./type_defs.md#updateintegrationresponseresponsetypedef).

<a id="update_model"></a>

### update_model

Updates a Model.

Type annotations for `session.create_client("apigatewayv2").update_model`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_model)

Asynchronous method. Use `await update_model(...)` for a synchronous call.

Arguments mapping described in
[UpdateModelRequestRequestTypeDef](./type_defs.md#updatemodelrequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `ModelId`: `str` *(required)*
- `ContentType`: `str`
- `Description`: `str`
- `Name`: `str`
- `Schema`: `str`

Returns a `Coroutine` for
[UpdateModelResponseTypeDef](./type_defs.md#updatemodelresponsetypedef).

<a id="update_route"></a>

### update_route

Updates a Route.

Type annotations for `session.create_client("apigatewayv2").update_route`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_route)

Asynchronous method. Use `await update_route(...)` for a synchronous call.

Arguments mapping described in
[UpdateRouteRequestRequestTypeDef](./type_defs.md#updaterouterequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*
- `ApiKeyRequired`: `bool`
- `AuthorizationScopes`: `Sequence`\[`str`\]
- `AuthorizationType`:
  [AuthorizationTypeType](./literals.md#authorizationtypetype)
- `AuthorizerId`: `str`
- `ModelSelectionExpression`: `str`
- `OperationName`: `str`
- `RequestModels`: `Mapping`\[`str`, `str`\]
- `RequestParameters`: `Mapping`\[`str`,
  [ParameterConstraintsTypeDef](./type_defs.md#parameterconstraintstypedef)\]
- `RouteKey`: `str`
- `RouteResponseSelectionExpression`: `str`
- `Target`: `str`

Returns a `Coroutine` for
[UpdateRouteResultTypeDef](./type_defs.md#updaterouteresulttypedef).

<a id="update_route_response"></a>

### update_route_response

Updates a RouteResponse.

Type annotations for
`session.create_client("apigatewayv2").update_route_response` method.

Boto3 documentation:
[ApiGatewayV2.Client.update_route_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_route_response)

Asynchronous method. Use `await update_route_response(...)` for a synchronous
call.

Arguments mapping described in
[UpdateRouteResponseRequestRequestTypeDef](./type_defs.md#updaterouteresponserequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `RouteId`: `str` *(required)*
- `RouteResponseId`: `str` *(required)*
- `ModelSelectionExpression`: `str`
- `ResponseModels`: `Mapping`\[`str`, `str`\]
- `ResponseParameters`: `Mapping`\[`str`,
  [ParameterConstraintsTypeDef](./type_defs.md#parameterconstraintstypedef)\]
- `RouteResponseKey`: `str`

Returns a `Coroutine` for
[UpdateRouteResponseResponseTypeDef](./type_defs.md#updaterouteresponseresponsetypedef).

<a id="update_stage"></a>

### update_stage

Updates a Stage.

Type annotations for `session.create_client("apigatewayv2").update_stage`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_stage)

Asynchronous method. Use `await update_stage(...)` for a synchronous call.

Arguments mapping described in
[UpdateStageRequestRequestTypeDef](./type_defs.md#updatestagerequestrequesttypedef).

Keyword-only arguments:

- `ApiId`: `str` *(required)*
- `StageName`: `str` *(required)*
- `AccessLogSettings`:
  [AccessLogSettingsTypeDef](./type_defs.md#accesslogsettingstypedef)
- `AutoDeploy`: `bool`
- `ClientCertificateId`: `str`
- `DefaultRouteSettings`:
  [RouteSettingsTypeDef](./type_defs.md#routesettingstypedef)
- `DeploymentId`: `str`
- `Description`: `str`
- `RouteSettings`: `Mapping`\[`str`,
  [RouteSettingsTypeDef](./type_defs.md#routesettingstypedef)\]
- `StageVariables`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[UpdateStageResponseTypeDef](./type_defs.md#updatestageresponsetypedef).

<a id="update_vpc_link"></a>

### update_vpc_link

Updates a VPC link.

Type annotations for `session.create_client("apigatewayv2").update_vpc_link`
method.

Boto3 documentation:
[ApiGatewayV2.Client.update_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.update_vpc_link)

Asynchronous method. Use `await update_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[UpdateVpcLinkRequestRequestTypeDef](./type_defs.md#updatevpclinkrequestrequesttypedef).

Keyword-only arguments:

- `VpcLinkId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for
[UpdateVpcLinkResponseTypeDef](./type_defs.md#updatevpclinkresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("apigatewayv2").__aenter__` method.

Boto3 documentation:
[ApiGatewayV2.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [ApiGatewayV2Client](#apigatewayv2client).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("apigatewayv2").__aexit__` method.

Boto3 documentation:
[ApiGatewayV2.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("apigatewayv2").get_paginator`
method with overloads.

- `client.get_paginator("get_apis")` ->
  [GetApisPaginator](./paginators.md#getapispaginator)
- `client.get_paginator("get_authorizers")` ->
  [GetAuthorizersPaginator](./paginators.md#getauthorizerspaginator)
- `client.get_paginator("get_deployments")` ->
  [GetDeploymentsPaginator](./paginators.md#getdeploymentspaginator)
- `client.get_paginator("get_domain_names")` ->
  [GetDomainNamesPaginator](./paginators.md#getdomainnamespaginator)
- `client.get_paginator("get_integration_responses")` ->
  [GetIntegrationResponsesPaginator](./paginators.md#getintegrationresponsespaginator)
- `client.get_paginator("get_integrations")` ->
  [GetIntegrationsPaginator](./paginators.md#getintegrationspaginator)
- `client.get_paginator("get_models")` ->
  [GetModelsPaginator](./paginators.md#getmodelspaginator)
- `client.get_paginator("get_route_responses")` ->
  [GetRouteResponsesPaginator](./paginators.md#getrouteresponsespaginator)
- `client.get_paginator("get_routes")` ->
  [GetRoutesPaginator](./paginators.md#getroutespaginator)
- `client.get_paginator("get_stages")` ->
  [GetStagesPaginator](./paginators.md#getstagespaginator)
