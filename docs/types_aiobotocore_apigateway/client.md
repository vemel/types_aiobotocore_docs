<a id="apigatewayclient-for-aiobotocore-apigateway-module"></a>

# APIGatewayClient for aiobotocore APIGateway module

> [Index](../README.md) > [APIGateway](./README.md) > APIGatewayClient

Auto-generated documentation for
[APIGateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway)
type annotations stubs module
[types-aiobotocore-apigateway](https://pypi.org/project/types-aiobotocore-apigateway/).

- [APIGatewayClient for aiobotocore APIGateway module](#apigatewayclient-for-aiobotocore-apigateway-module)
  - [APIGatewayClient](#apigatewayclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_api_key](#create_api_key)
    - [create_authorizer](#create_authorizer)
    - [create_base_path_mapping](#create_base_path_mapping)
    - [create_deployment](#create_deployment)
    - [create_documentation_part](#create_documentation_part)
    - [create_documentation_version](#create_documentation_version)
    - [create_domain_name](#create_domain_name)
    - [create_model](#create_model)
    - [create_request_validator](#create_request_validator)
    - [create_resource](#create_resource)
    - [create_rest_api](#create_rest_api)
    - [create_stage](#create_stage)
    - [create_usage_plan](#create_usage_plan)
    - [create_usage_plan_key](#create_usage_plan_key)
    - [create_vpc_link](#create_vpc_link)
    - [delete_api_key](#delete_api_key)
    - [delete_authorizer](#delete_authorizer)
    - [delete_base_path_mapping](#delete_base_path_mapping)
    - [delete_client_certificate](#delete_client_certificate)
    - [delete_deployment](#delete_deployment)
    - [delete_documentation_part](#delete_documentation_part)
    - [delete_documentation_version](#delete_documentation_version)
    - [delete_domain_name](#delete_domain_name)
    - [delete_gateway_response](#delete_gateway_response)
    - [delete_integration](#delete_integration)
    - [delete_integration_response](#delete_integration_response)
    - [delete_method](#delete_method)
    - [delete_method_response](#delete_method_response)
    - [delete_model](#delete_model)
    - [delete_request_validator](#delete_request_validator)
    - [delete_resource](#delete_resource)
    - [delete_rest_api](#delete_rest_api)
    - [delete_stage](#delete_stage)
    - [delete_usage_plan](#delete_usage_plan)
    - [delete_usage_plan_key](#delete_usage_plan_key)
    - [delete_vpc_link](#delete_vpc_link)
    - [flush_stage_authorizers_cache](#flush_stage_authorizers_cache)
    - [flush_stage_cache](#flush_stage_cache)
    - [generate_client_certificate](#generate_client_certificate)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_account](#get_account)
    - [get_api_key](#get_api_key)
    - [get_api_keys](#get_api_keys)
    - [get_authorizer](#get_authorizer)
    - [get_authorizers](#get_authorizers)
    - [get_base_path_mapping](#get_base_path_mapping)
    - [get_base_path_mappings](#get_base_path_mappings)
    - [get_client_certificate](#get_client_certificate)
    - [get_client_certificates](#get_client_certificates)
    - [get_deployment](#get_deployment)
    - [get_deployments](#get_deployments)
    - [get_documentation_part](#get_documentation_part)
    - [get_documentation_parts](#get_documentation_parts)
    - [get_documentation_version](#get_documentation_version)
    - [get_documentation_versions](#get_documentation_versions)
    - [get_domain_name](#get_domain_name)
    - [get_domain_names](#get_domain_names)
    - [get_export](#get_export)
    - [get_gateway_response](#get_gateway_response)
    - [get_gateway_responses](#get_gateway_responses)
    - [get_integration](#get_integration)
    - [get_integration_response](#get_integration_response)
    - [get_method](#get_method)
    - [get_method_response](#get_method_response)
    - [get_model](#get_model)
    - [get_model_template](#get_model_template)
    - [get_models](#get_models)
    - [get_request_validator](#get_request_validator)
    - [get_request_validators](#get_request_validators)
    - [get_resource](#get_resource)
    - [get_resources](#get_resources)
    - [get_rest_api](#get_rest_api)
    - [get_rest_apis](#get_rest_apis)
    - [get_sdk](#get_sdk)
    - [get_sdk_type](#get_sdk_type)
    - [get_sdk_types](#get_sdk_types)
    - [get_stage](#get_stage)
    - [get_stages](#get_stages)
    - [get_tags](#get_tags)
    - [get_usage](#get_usage)
    - [get_usage_plan](#get_usage_plan)
    - [get_usage_plan_key](#get_usage_plan_key)
    - [get_usage_plan_keys](#get_usage_plan_keys)
    - [get_usage_plans](#get_usage_plans)
    - [get_vpc_link](#get_vpc_link)
    - [get_vpc_links](#get_vpc_links)
    - [import_api_keys](#import_api_keys)
    - [import_documentation_parts](#import_documentation_parts)
    - [import_rest_api](#import_rest_api)
    - [put_gateway_response](#put_gateway_response)
    - [put_integration](#put_integration)
    - [put_integration_response](#put_integration_response)
    - [put_method](#put_method)
    - [put_method_response](#put_method_response)
    - [put_rest_api](#put_rest_api)
    - [tag_resource](#tag_resource)
    - [test_invoke_authorizer](#test_invoke_authorizer)
    - [test_invoke_method](#test_invoke_method)
    - [untag_resource](#untag_resource)
    - [update_account](#update_account)
    - [update_api_key](#update_api_key)
    - [update_authorizer](#update_authorizer)
    - [update_base_path_mapping](#update_base_path_mapping)
    - [update_client_certificate](#update_client_certificate)
    - [update_deployment](#update_deployment)
    - [update_documentation_part](#update_documentation_part)
    - [update_documentation_version](#update_documentation_version)
    - [update_domain_name](#update_domain_name)
    - [update_gateway_response](#update_gateway_response)
    - [update_integration](#update_integration)
    - [update_integration_response](#update_integration_response)
    - [update_method](#update_method)
    - [update_method_response](#update_method_response)
    - [update_model](#update_model)
    - [update_request_validator](#update_request_validator)
    - [update_resource](#update_resource)
    - [update_rest_api](#update_rest_api)
    - [update_stage](#update_stage)
    - [update_usage](#update_usage)
    - [update_usage_plan](#update_usage_plan)
    - [update_vpc_link](#update_vpc_link)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="apigatewayclient"></a>

## APIGatewayClient

Type annotations for `session.create_client("apigateway")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_apigateway.client import APIGatewayClient

session = get_session()
async with session.create_client("apigateway") as client:
    client: APIGatewayClient
```

Boto3 documentation:
[APIGateway.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_apigateway.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.LimitExceededException`
- `Exceptions.NotFoundException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.TooManyRequestsException`
- `Exceptions.UnauthorizedException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

APIGatewayClient exceptions.

Type annotations for `session.create_client("apigateway").exceptions` method.

Boto3 documentation:
[APIGateway.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("apigateway").can_paginate` method.

Boto3 documentation:
[APIGateway.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_api\_key"></a>

### create_api_key

Create an ApiKey resource.

Type annotations for `session.create_client("apigateway").create_api_key`
method.

Boto3 documentation:
[APIGateway.Client.create_api_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_api_key)

Asynchronous method. Use `await create_api_key(...)` for a synchronous call.

Arguments mapping described in
[CreateApiKeyRequestRequestTypeDef](./type_defs.md#createapikeyrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str`
- `description`: `str`
- `enabled`: `bool`
- `generateDistinctId`: `bool`
- `value`: `str`
- `stageKeys`: `Sequence`\[[StageKeyTypeDef](./type_defs.md#stagekeytypedef)\]
- `customerId`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ApiKeyResponseMetadataTypeDef](./type_defs.md#apikeyresponsemetadatatypedef).

<a id="create\_authorizer"></a>

### create_authorizer

Adds a new Authorizer resource to an existing RestApi resource.

Type annotations for `session.create_client("apigateway").create_authorizer`
method.

Boto3 documentation:
[APIGateway.Client.create_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_authorizer)

Asynchronous method. Use `await create_authorizer(...)` for a synchronous call.

Arguments mapping described in
[CreateAuthorizerRequestRequestTypeDef](./type_defs.md#createauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `name`: `str` *(required)*
- `type`: [AuthorizerTypeType](./literals.md#authorizertypetype) *(required)*
- `providerARNs`: `Sequence`\[`str`\]
- `authType`: `str`
- `authorizerUri`: `str`
- `authorizerCredentials`: `str`
- `identitySource`: `str`
- `identityValidationExpression`: `str`
- `authorizerResultTtlInSeconds`: `int`

Returns a `Coroutine` for
[AuthorizerResponseMetadataTypeDef](./type_defs.md#authorizerresponsemetadatatypedef).

<a id="create\_base\_path\_mapping"></a>

### create_base_path_mapping

Creates a new BasePathMapping resource.

Type annotations for
`session.create_client("apigateway").create_base_path_mapping` method.

Boto3 documentation:
[APIGateway.Client.create_base_path_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_base_path_mapping)

Asynchronous method. Use `await create_base_path_mapping(...)` for a
synchronous call.

Arguments mapping described in
[CreateBasePathMappingRequestRequestTypeDef](./type_defs.md#createbasepathmappingrequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `restApiId`: `str` *(required)*
- `basePath`: `str`
- `stage`: `str`

Returns a `Coroutine` for
[BasePathMappingResponseMetadataTypeDef](./type_defs.md#basepathmappingresponsemetadatatypedef).

<a id="create\_deployment"></a>

### create_deployment

Creates a Deployment resource, which makes a specified RestApi callable over
the internet.

Type annotations for `session.create_client("apigateway").create_deployment`
method.

Boto3 documentation:
[APIGateway.Client.create_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_deployment)

Asynchronous method. Use `await create_deployment(...)` for a synchronous call.

Arguments mapping described in
[CreateDeploymentRequestRequestTypeDef](./type_defs.md#createdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str`
- `stageDescription`: `str`
- `description`: `str`
- `cacheClusterEnabled`: `bool`
- `cacheClusterSize`:
  [CacheClusterSizeType](./literals.md#cacheclustersizetype)
- `variables`: `Mapping`\[`str`, `str`\]
- `canarySettings`:
  [DeploymentCanarySettingsTypeDef](./type_defs.md#deploymentcanarysettingstypedef)
- `tracingEnabled`: `bool`

Returns a `Coroutine` for
[DeploymentResponseMetadataTypeDef](./type_defs.md#deploymentresponsemetadatatypedef).

<a id="create\_documentation\_part"></a>

### create_documentation_part

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/CreateDocumentationPart).

Type annotations for
`session.create_client("apigateway").create_documentation_part` method.

Boto3 documentation:
[APIGateway.Client.create_documentation_part](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_documentation_part)

Asynchronous method. Use `await create_documentation_part(...)` for a
synchronous call.

Arguments mapping described in
[CreateDocumentationPartRequestRequestTypeDef](./type_defs.md#createdocumentationpartrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `location`:
  [DocumentationPartLocationTypeDef](./type_defs.md#documentationpartlocationtypedef)
  *(required)*
- `properties`: `str` *(required)*

Returns a `Coroutine` for
[DocumentationPartResponseMetadataTypeDef](./type_defs.md#documentationpartresponsemetadatatypedef).

<a id="create\_documentation\_version"></a>

### create_documentation_version

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/CreateDocumentationVersion).

Type annotations for
`session.create_client("apigateway").create_documentation_version` method.

Boto3 documentation:
[APIGateway.Client.create_documentation_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_documentation_version)

Asynchronous method. Use `await create_documentation_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateDocumentationVersionRequestRequestTypeDef](./type_defs.md#createdocumentationversionrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `documentationVersion`: `str` *(required)*
- `stageName`: `str`
- `description`: `str`

Returns a `Coroutine` for
[DocumentationVersionResponseMetadataTypeDef](./type_defs.md#documentationversionresponsemetadatatypedef).

<a id="create\_domain\_name"></a>

### create_domain_name

Creates a new domain name.

Type annotations for `session.create_client("apigateway").create_domain_name`
method.

Boto3 documentation:
[APIGateway.Client.create_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_domain_name)

Asynchronous method. Use `await create_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[CreateDomainNameRequestRequestTypeDef](./type_defs.md#createdomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `certificateName`: `str`
- `certificateBody`: `str`
- `certificatePrivateKey`: `str`
- `certificateChain`: `str`
- `certificateArn`: `str`
- `regionalCertificateName`: `str`
- `regionalCertificateArn`: `str`
- `endpointConfiguration`:
  [EndpointConfigurationTypeDef](./type_defs.md#endpointconfigurationtypedef)
- `tags`: `Mapping`\[`str`, `str`\]
- `securityPolicy`: [SecurityPolicyType](./literals.md#securitypolicytype)
- `mutualTlsAuthentication`:
  [MutualTlsAuthenticationInputTypeDef](./type_defs.md#mutualtlsauthenticationinputtypedef)
- `ownershipVerificationCertificateArn`: `str`

Returns a `Coroutine` for
[DomainNameResponseMetadataTypeDef](./type_defs.md#domainnameresponsemetadatatypedef).

<a id="create\_model"></a>

### create_model

Adds a new Model resource to an existing RestApi resource.

Type annotations for `session.create_client("apigateway").create_model` method.

Boto3 documentation:
[APIGateway.Client.create_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_model)

Asynchronous method. Use `await create_model(...)` for a synchronous call.

Arguments mapping described in
[CreateModelRequestRequestTypeDef](./type_defs.md#createmodelrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `name`: `str` *(required)*
- `contentType`: `str` *(required)*
- `description`: `str`
- `schema`: `str`

Returns a `Coroutine` for
[ModelResponseMetadataTypeDef](./type_defs.md#modelresponsemetadatatypedef).

<a id="create\_request\_validator"></a>

### create_request_validator

Creates a ReqeustValidator of a given RestApi .

Type annotations for
`session.create_client("apigateway").create_request_validator` method.

Boto3 documentation:
[APIGateway.Client.create_request_validator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_request_validator)

Asynchronous method. Use `await create_request_validator(...)` for a
synchronous call.

Arguments mapping described in
[CreateRequestValidatorRequestRequestTypeDef](./type_defs.md#createrequestvalidatorrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `name`: `str`
- `validateRequestBody`: `bool`
- `validateRequestParameters`: `bool`

Returns a `Coroutine` for
[RequestValidatorResponseMetadataTypeDef](./type_defs.md#requestvalidatorresponsemetadatatypedef).

<a id="create\_resource"></a>

### create_resource

Creates a Resource resource.

Type annotations for `session.create_client("apigateway").create_resource`
method.

Boto3 documentation:
[APIGateway.Client.create_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_resource)

Asynchronous method. Use `await create_resource(...)` for a synchronous call.

Arguments mapping described in
[CreateResourceRequestRequestTypeDef](./type_defs.md#createresourcerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `parentId`: `str` *(required)*
- `pathPart`: `str` *(required)*

Returns a `Coroutine` for
[ResourceResponseMetadataTypeDef](./type_defs.md#resourceresponsemetadatatypedef).

<a id="create\_rest\_api"></a>

### create_rest_api

Creates a new RestApi resource.

Type annotations for `session.create_client("apigateway").create_rest_api`
method.

Boto3 documentation:
[APIGateway.Client.create_rest_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_rest_api)

Asynchronous method. Use `await create_rest_api(...)` for a synchronous call.

Arguments mapping described in
[CreateRestApiRequestRequestTypeDef](./type_defs.md#createrestapirequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `description`: `str`
- `version`: `str`
- `cloneFrom`: `str`
- `binaryMediaTypes`: `Sequence`\[`str`\]
- `minimumCompressionSize`: `int`
- `apiKeySource`: [ApiKeySourceTypeType](./literals.md#apikeysourcetypetype)
- `endpointConfiguration`:
  [EndpointConfigurationTypeDef](./type_defs.md#endpointconfigurationtypedef)
- `policy`: `str`
- `tags`: `Mapping`\[`str`, `str`\]
- `disableExecuteApiEndpoint`: `bool`

Returns a `Coroutine` for
[RestApiResponseMetadataTypeDef](./type_defs.md#restapiresponsemetadatatypedef).

<a id="create\_stage"></a>

### create_stage

Creates a new Stage resource that references a pre-existing Deployment for the
API.

Type annotations for `session.create_client("apigateway").create_stage` method.

Boto3 documentation:
[APIGateway.Client.create_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_stage)

Asynchronous method. Use `await create_stage(...)` for a synchronous call.

Arguments mapping described in
[CreateStageRequestRequestTypeDef](./type_defs.md#createstagerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*
- `deploymentId`: `str` *(required)*
- `description`: `str`
- `cacheClusterEnabled`: `bool`
- `cacheClusterSize`:
  [CacheClusterSizeType](./literals.md#cacheclustersizetype)
- `variables`: `Mapping`\[`str`, `str`\]
- `documentationVersion`: `str`
- `canarySettings`:
  [CanarySettingsTypeDef](./type_defs.md#canarysettingstypedef)
- `tracingEnabled`: `bool`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[StageResponseMetadataTypeDef](./type_defs.md#stageresponsemetadatatypedef).

<a id="create\_usage\_plan"></a>

### create_usage_plan

Creates a usage plan with the throttle and quota limits, as well as the
associated API stages, specified in the payload.

Type annotations for `session.create_client("apigateway").create_usage_plan`
method.

Boto3 documentation:
[APIGateway.Client.create_usage_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_usage_plan)

Asynchronous method. Use `await create_usage_plan(...)` for a synchronous call.

Arguments mapping described in
[CreateUsagePlanRequestRequestTypeDef](./type_defs.md#createusageplanrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `description`: `str`
- `apiStages`: `Sequence`\[[ApiStageTypeDef](./type_defs.md#apistagetypedef)\]
- `throttle`: [ThrottleSettingsTypeDef](./type_defs.md#throttlesettingstypedef)
- `quota`: [QuotaSettingsTypeDef](./type_defs.md#quotasettingstypedef)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[UsagePlanResponseMetadataTypeDef](./type_defs.md#usageplanresponsemetadatatypedef).

<a id="create\_usage\_plan\_key"></a>

### create_usage_plan_key

Creates a usage plan key for adding an existing API key to a usage plan.

Type annotations for
`session.create_client("apigateway").create_usage_plan_key` method.

Boto3 documentation:
[APIGateway.Client.create_usage_plan_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_usage_plan_key)

Asynchronous method. Use `await create_usage_plan_key(...)` for a synchronous
call.

Arguments mapping described in
[CreateUsagePlanKeyRequestRequestTypeDef](./type_defs.md#createusageplankeyrequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*
- `keyId`: `str` *(required)*
- `keyType`: `str` *(required)*

Returns a `Coroutine` for
[UsagePlanKeyResponseMetadataTypeDef](./type_defs.md#usageplankeyresponsemetadatatypedef).

<a id="create\_vpc\_link"></a>

### create_vpc_link

Creates a VPC link, under the caller's account in a selected region, in an
asynchronous operation that typically takes 2-4 minutes to complete and become
operational.

Type annotations for `session.create_client("apigateway").create_vpc_link`
method.

Boto3 documentation:
[APIGateway.Client.create_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.create_vpc_link)

Asynchronous method. Use `await create_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[CreateVpcLinkRequestRequestTypeDef](./type_defs.md#createvpclinkrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `targetArns`: `Sequence`\[`str`\] *(required)*
- `description`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[VpcLinkResponseMetadataTypeDef](./type_defs.md#vpclinkresponsemetadatatypedef).

<a id="delete\_api\_key"></a>

### delete_api_key

Deletes the ApiKey resource.

Type annotations for `session.create_client("apigateway").delete_api_key`
method.

Boto3 documentation:
[APIGateway.Client.delete_api_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_api_key)

Asynchronous method. Use `await delete_api_key(...)` for a synchronous call.

Arguments mapping described in
[DeleteApiKeyRequestRequestTypeDef](./type_defs.md#deleteapikeyrequestrequesttypedef).

Keyword-only arguments:

- `apiKey`: `str` *(required)*

<a id="delete\_authorizer"></a>

### delete_authorizer

Deletes an existing Authorizer resource.

Type annotations for `session.create_client("apigateway").delete_authorizer`
method.

Boto3 documentation:
[APIGateway.Client.delete_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_authorizer)

Asynchronous method. Use `await delete_authorizer(...)` for a synchronous call.

Arguments mapping described in
[DeleteAuthorizerRequestRequestTypeDef](./type_defs.md#deleteauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `authorizerId`: `str` *(required)*

<a id="delete\_base\_path\_mapping"></a>

### delete_base_path_mapping

Deletes the BasePathMapping resource.

Type annotations for
`session.create_client("apigateway").delete_base_path_mapping` method.

Boto3 documentation:
[APIGateway.Client.delete_base_path_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_base_path_mapping)

Asynchronous method. Use `await delete_base_path_mapping(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBasePathMappingRequestRequestTypeDef](./type_defs.md#deletebasepathmappingrequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `basePath`: `str` *(required)*

<a id="delete\_client\_certificate"></a>

### delete_client_certificate

Deletes the ClientCertificate resource.

Type annotations for
`session.create_client("apigateway").delete_client_certificate` method.

Boto3 documentation:
[APIGateway.Client.delete_client_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_client_certificate)

Asynchronous method. Use `await delete_client_certificate(...)` for a
synchronous call.

Arguments mapping described in
[DeleteClientCertificateRequestRequestTypeDef](./type_defs.md#deleteclientcertificaterequestrequesttypedef).

Keyword-only arguments:

- `clientCertificateId`: `str` *(required)*

<a id="delete\_deployment"></a>

### delete_deployment

Deletes a Deployment resource.

Type annotations for `session.create_client("apigateway").delete_deployment`
method.

Boto3 documentation:
[APIGateway.Client.delete_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_deployment)

Asynchronous method. Use `await delete_deployment(...)` for a synchronous call.

Arguments mapping described in
[DeleteDeploymentRequestRequestTypeDef](./type_defs.md#deletedeploymentrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `deploymentId`: `str` *(required)*

<a id="delete\_documentation\_part"></a>

### delete_documentation_part

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/DeleteDocumentationPart).

Type annotations for
`session.create_client("apigateway").delete_documentation_part` method.

Boto3 documentation:
[APIGateway.Client.delete_documentation_part](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_documentation_part)

Asynchronous method. Use `await delete_documentation_part(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDocumentationPartRequestRequestTypeDef](./type_defs.md#deletedocumentationpartrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `documentationPartId`: `str` *(required)*

<a id="delete\_documentation\_version"></a>

### delete_documentation_version

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/DeleteDocumentationVersion).

Type annotations for
`session.create_client("apigateway").delete_documentation_version` method.

Boto3 documentation:
[APIGateway.Client.delete_documentation_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_documentation_version)

Asynchronous method. Use `await delete_documentation_version(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDocumentationVersionRequestRequestTypeDef](./type_defs.md#deletedocumentationversionrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `documentationVersion`: `str` *(required)*

<a id="delete\_domain\_name"></a>

### delete_domain_name

Deletes the DomainName resource.

Type annotations for `session.create_client("apigateway").delete_domain_name`
method.

Boto3 documentation:
[APIGateway.Client.delete_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_domain_name)

Asynchronous method. Use `await delete_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[DeleteDomainNameRequestRequestTypeDef](./type_defs.md#deletedomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*

<a id="delete\_gateway\_response"></a>

### delete_gateway_response

Clears any customization of a GatewayResponse of a specified response type on
the given RestApi and resets it with the default settings.

Type annotations for
`session.create_client("apigateway").delete_gateway_response` method.

Boto3 documentation:
[APIGateway.Client.delete_gateway_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_gateway_response)

Asynchronous method. Use `await delete_gateway_response(...)` for a synchronous
call.

Arguments mapping described in
[DeleteGatewayResponseRequestRequestTypeDef](./type_defs.md#deletegatewayresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `responseType`:
  [GatewayResponseTypeType](./literals.md#gatewayresponsetypetype) *(required)*

<a id="delete\_integration"></a>

### delete_integration

Represents a delete integration.

Type annotations for `session.create_client("apigateway").delete_integration`
method.

Boto3 documentation:
[APIGateway.Client.delete_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_integration)

Asynchronous method. Use `await delete_integration(...)` for a synchronous
call.

Arguments mapping described in
[DeleteIntegrationRequestRequestTypeDef](./type_defs.md#deleteintegrationrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*

<a id="delete\_integration\_response"></a>

### delete_integration_response

Represents a delete integration response.

Type annotations for
`session.create_client("apigateway").delete_integration_response` method.

Boto3 documentation:
[APIGateway.Client.delete_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_integration_response)

Asynchronous method. Use `await delete_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[DeleteIntegrationResponseRequestRequestTypeDef](./type_defs.md#deleteintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*

<a id="delete\_method"></a>

### delete_method

Deletes an existing Method resource.

Type annotations for `session.create_client("apigateway").delete_method`
method.

Boto3 documentation:
[APIGateway.Client.delete_method](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_method)

Asynchronous method. Use `await delete_method(...)` for a synchronous call.

Arguments mapping described in
[DeleteMethodRequestRequestTypeDef](./type_defs.md#deletemethodrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*

<a id="delete\_method\_response"></a>

### delete_method_response

Deletes an existing MethodResponse resource.

Type annotations for
`session.create_client("apigateway").delete_method_response` method.

Boto3 documentation:
[APIGateway.Client.delete_method_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_method_response)

Asynchronous method. Use `await delete_method_response(...)` for a synchronous
call.

Arguments mapping described in
[DeleteMethodResponseRequestRequestTypeDef](./type_defs.md#deletemethodresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*

<a id="delete\_model"></a>

### delete_model

Deletes a model.

Type annotations for `session.create_client("apigateway").delete_model` method.

Boto3 documentation:
[APIGateway.Client.delete_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_model)

Asynchronous method. Use `await delete_model(...)` for a synchronous call.

Arguments mapping described in
[DeleteModelRequestRequestTypeDef](./type_defs.md#deletemodelrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `modelName`: `str` *(required)*

<a id="delete\_request\_validator"></a>

### delete_request_validator

Deletes a RequestValidator of a given RestApi .

Type annotations for
`session.create_client("apigateway").delete_request_validator` method.

Boto3 documentation:
[APIGateway.Client.delete_request_validator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_request_validator)

Asynchronous method. Use `await delete_request_validator(...)` for a
synchronous call.

Arguments mapping described in
[DeleteRequestValidatorRequestRequestTypeDef](./type_defs.md#deleterequestvalidatorrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `requestValidatorId`: `str` *(required)*

<a id="delete\_resource"></a>

### delete_resource

Deletes a Resource resource.

Type annotations for `session.create_client("apigateway").delete_resource`
method.

Boto3 documentation:
[APIGateway.Client.delete_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_resource)

Asynchronous method. Use `await delete_resource(...)` for a synchronous call.

Arguments mapping described in
[DeleteResourceRequestRequestTypeDef](./type_defs.md#deleteresourcerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*

<a id="delete\_rest\_api"></a>

### delete_rest_api

Deletes the specified API.

Type annotations for `session.create_client("apigateway").delete_rest_api`
method.

Boto3 documentation:
[APIGateway.Client.delete_rest_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_rest_api)

Asynchronous method. Use `await delete_rest_api(...)` for a synchronous call.

Arguments mapping described in
[DeleteRestApiRequestRequestTypeDef](./type_defs.md#deleterestapirequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*

<a id="delete\_stage"></a>

### delete_stage

Deletes a Stage resource.

Type annotations for `session.create_client("apigateway").delete_stage` method.

Boto3 documentation:
[APIGateway.Client.delete_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_stage)

Asynchronous method. Use `await delete_stage(...)` for a synchronous call.

Arguments mapping described in
[DeleteStageRequestRequestTypeDef](./type_defs.md#deletestagerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*

<a id="delete\_usage\_plan"></a>

### delete_usage_plan

Deletes a usage plan of a given plan Id.

Type annotations for `session.create_client("apigateway").delete_usage_plan`
method.

Boto3 documentation:
[APIGateway.Client.delete_usage_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_usage_plan)

Asynchronous method. Use `await delete_usage_plan(...)` for a synchronous call.

Arguments mapping described in
[DeleteUsagePlanRequestRequestTypeDef](./type_defs.md#deleteusageplanrequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*

<a id="delete\_usage\_plan\_key"></a>

### delete_usage_plan_key

Deletes a usage plan key and remove the underlying API key from the associated
usage plan.

Type annotations for
`session.create_client("apigateway").delete_usage_plan_key` method.

Boto3 documentation:
[APIGateway.Client.delete_usage_plan_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_usage_plan_key)

Asynchronous method. Use `await delete_usage_plan_key(...)` for a synchronous
call.

Arguments mapping described in
[DeleteUsagePlanKeyRequestRequestTypeDef](./type_defs.md#deleteusageplankeyrequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*
- `keyId`: `str` *(required)*

<a id="delete\_vpc\_link"></a>

### delete_vpc_link

Deletes an existing VpcLink of a specified identifier.

Type annotations for `session.create_client("apigateway").delete_vpc_link`
method.

Boto3 documentation:
[APIGateway.Client.delete_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.delete_vpc_link)

Asynchronous method. Use `await delete_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[DeleteVpcLinkRequestRequestTypeDef](./type_defs.md#deletevpclinkrequestrequesttypedef).

Keyword-only arguments:

- `vpcLinkId`: `str` *(required)*

<a id="flush\_stage\_authorizers\_cache"></a>

### flush_stage_authorizers_cache

Flushes all authorizer cache entries on a stage.

Type annotations for
`session.create_client("apigateway").flush_stage_authorizers_cache` method.

Boto3 documentation:
[APIGateway.Client.flush_stage_authorizers_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.flush_stage_authorizers_cache)

Asynchronous method. Use `await flush_stage_authorizers_cache(...)` for a
synchronous call.

Arguments mapping described in
[FlushStageAuthorizersCacheRequestRequestTypeDef](./type_defs.md#flushstageauthorizerscacherequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*

<a id="flush\_stage\_cache"></a>

### flush_stage_cache

Flushes a stage's cache.

Type annotations for `session.create_client("apigateway").flush_stage_cache`
method.

Boto3 documentation:
[APIGateway.Client.flush_stage_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.flush_stage_cache)

Asynchronous method. Use `await flush_stage_cache(...)` for a synchronous call.

Arguments mapping described in
[FlushStageCacheRequestRequestTypeDef](./type_defs.md#flushstagecacherequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*

<a id="generate\_client\_certificate"></a>

### generate_client_certificate

Generates a ClientCertificate resource.

Type annotations for
`session.create_client("apigateway").generate_client_certificate` method.

Boto3 documentation:
[APIGateway.Client.generate_client_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.generate_client_certificate)

Asynchronous method. Use `await generate_client_certificate(...)` for a
synchronous call.

Arguments mapping described in
[GenerateClientCertificateRequestRequestTypeDef](./type_defs.md#generateclientcertificaterequestrequesttypedef).

Keyword-only arguments:

- `description`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ClientCertificateResponseMetadataTypeDef](./type_defs.md#clientcertificateresponsemetadatatypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("apigateway").generate_presigned_url` method.

Boto3 documentation:
[APIGateway.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_account"></a>

### get_account

Gets information about the current Account resource.

Type annotations for `session.create_client("apigateway").get_account` method.

Boto3 documentation:
[APIGateway.Client.get_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_account)

Asynchronous method. Use `await get_account(...)` for a synchronous call.

Returns a `Coroutine` for [AccountTypeDef](./type_defs.md#accounttypedef).

<a id="get\_api\_key"></a>

### get_api_key

Gets information about the current ApiKey resource.

Type annotations for `session.create_client("apigateway").get_api_key` method.

Boto3 documentation:
[APIGateway.Client.get_api_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_api_key)

Asynchronous method. Use `await get_api_key(...)` for a synchronous call.

Arguments mapping described in
[GetApiKeyRequestRequestTypeDef](./type_defs.md#getapikeyrequestrequesttypedef).

Keyword-only arguments:

- `apiKey`: `str` *(required)*
- `includeValue`: `bool`

Returns a `Coroutine` for
[ApiKeyResponseMetadataTypeDef](./type_defs.md#apikeyresponsemetadatatypedef).

<a id="get\_api\_keys"></a>

### get_api_keys

Gets information about the current ApiKeys resource.

Type annotations for `session.create_client("apigateway").get_api_keys` method.

Boto3 documentation:
[APIGateway.Client.get_api_keys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_api_keys)

Asynchronous method. Use `await get_api_keys(...)` for a synchronous call.

Arguments mapping described in
[GetApiKeysRequestRequestTypeDef](./type_defs.md#getapikeysrequestrequesttypedef).

Keyword-only arguments:

- `position`: `str`
- `limit`: `int`
- `nameQuery`: `str`
- `customerId`: `str`
- `includeValues`: `bool`

Returns a `Coroutine` for [ApiKeysTypeDef](./type_defs.md#apikeystypedef).

<a id="get\_authorizer"></a>

### get_authorizer

Describe an existing Authorizer resource.

Type annotations for `session.create_client("apigateway").get_authorizer`
method.

Boto3 documentation:
[APIGateway.Client.get_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_authorizer)

Asynchronous method. Use `await get_authorizer(...)` for a synchronous call.

Arguments mapping described in
[GetAuthorizerRequestRequestTypeDef](./type_defs.md#getauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `authorizerId`: `str` *(required)*

Returns a `Coroutine` for
[AuthorizerResponseMetadataTypeDef](./type_defs.md#authorizerresponsemetadatatypedef).

<a id="get\_authorizers"></a>

### get_authorizers

Describe an existing Authorizers resource.

Type annotations for `session.create_client("apigateway").get_authorizers`
method.

Boto3 documentation:
[APIGateway.Client.get_authorizers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_authorizers)

Asynchronous method. Use `await get_authorizers(...)` for a synchronous call.

Arguments mapping described in
[GetAuthorizersRequestRequestTypeDef](./type_defs.md#getauthorizersrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[AuthorizersTypeDef](./type_defs.md#authorizerstypedef).

<a id="get\_base\_path\_mapping"></a>

### get_base_path_mapping

Describe a BasePathMapping resource.

Type annotations for
`session.create_client("apigateway").get_base_path_mapping` method.

Boto3 documentation:
[APIGateway.Client.get_base_path_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_base_path_mapping)

Asynchronous method. Use `await get_base_path_mapping(...)` for a synchronous
call.

Arguments mapping described in
[GetBasePathMappingRequestRequestTypeDef](./type_defs.md#getbasepathmappingrequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `basePath`: `str` *(required)*

Returns a `Coroutine` for
[BasePathMappingResponseMetadataTypeDef](./type_defs.md#basepathmappingresponsemetadatatypedef).

<a id="get\_base\_path\_mappings"></a>

### get_base_path_mappings

Represents a collection of BasePathMapping resources.

Type annotations for
`session.create_client("apigateway").get_base_path_mappings` method.

Boto3 documentation:
[APIGateway.Client.get_base_path_mappings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_base_path_mappings)

Asynchronous method. Use `await get_base_path_mappings(...)` for a synchronous
call.

Arguments mapping described in
[GetBasePathMappingsRequestRequestTypeDef](./type_defs.md#getbasepathmappingsrequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[BasePathMappingsTypeDef](./type_defs.md#basepathmappingstypedef).

<a id="get\_client\_certificate"></a>

### get_client_certificate

Gets information about the current ClientCertificate resource.

Type annotations for
`session.create_client("apigateway").get_client_certificate` method.

Boto3 documentation:
[APIGateway.Client.get_client_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_client_certificate)

Asynchronous method. Use `await get_client_certificate(...)` for a synchronous
call.

Arguments mapping described in
[GetClientCertificateRequestRequestTypeDef](./type_defs.md#getclientcertificaterequestrequesttypedef).

Keyword-only arguments:

- `clientCertificateId`: `str` *(required)*

Returns a `Coroutine` for
[ClientCertificateResponseMetadataTypeDef](./type_defs.md#clientcertificateresponsemetadatatypedef).

<a id="get\_client\_certificates"></a>

### get_client_certificates

Gets a collection of ClientCertificate resources.

Type annotations for
`session.create_client("apigateway").get_client_certificates` method.

Boto3 documentation:
[APIGateway.Client.get_client_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_client_certificates)

Asynchronous method. Use `await get_client_certificates(...)` for a synchronous
call.

Arguments mapping described in
[GetClientCertificatesRequestRequestTypeDef](./type_defs.md#getclientcertificatesrequestrequesttypedef).

Keyword-only arguments:

- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[ClientCertificatesTypeDef](./type_defs.md#clientcertificatestypedef).

<a id="get\_deployment"></a>

### get_deployment

Gets information about a Deployment resource.

Type annotations for `session.create_client("apigateway").get_deployment`
method.

Boto3 documentation:
[APIGateway.Client.get_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_deployment)

Asynchronous method. Use `await get_deployment(...)` for a synchronous call.

Arguments mapping described in
[GetDeploymentRequestRequestTypeDef](./type_defs.md#getdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `deploymentId`: `str` *(required)*
- `embed`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DeploymentResponseMetadataTypeDef](./type_defs.md#deploymentresponsemetadatatypedef).

<a id="get\_deployments"></a>

### get_deployments

Gets information about a Deployments collection.

Type annotations for `session.create_client("apigateway").get_deployments`
method.

Boto3 documentation:
[APIGateway.Client.get_deployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_deployments)

Asynchronous method. Use `await get_deployments(...)` for a synchronous call.

Arguments mapping described in
[GetDeploymentsRequestRequestTypeDef](./type_defs.md#getdeploymentsrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[DeploymentsTypeDef](./type_defs.md#deploymentstypedef).

<a id="get\_documentation\_part"></a>

### get_documentation_part

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/GetDocumentationPart).

Type annotations for
`session.create_client("apigateway").get_documentation_part` method.

Boto3 documentation:
[APIGateway.Client.get_documentation_part](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_documentation_part)

Asynchronous method. Use `await get_documentation_part(...)` for a synchronous
call.

Arguments mapping described in
[GetDocumentationPartRequestRequestTypeDef](./type_defs.md#getdocumentationpartrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `documentationPartId`: `str` *(required)*

Returns a `Coroutine` for
[DocumentationPartResponseMetadataTypeDef](./type_defs.md#documentationpartresponsemetadatatypedef).

<a id="get\_documentation\_parts"></a>

### get_documentation_parts

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/GetDocumentationParts).

Type annotations for
`session.create_client("apigateway").get_documentation_parts` method.

Boto3 documentation:
[APIGateway.Client.get_documentation_parts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_documentation_parts)

Asynchronous method. Use `await get_documentation_parts(...)` for a synchronous
call.

Arguments mapping described in
[GetDocumentationPartsRequestRequestTypeDef](./type_defs.md#getdocumentationpartsrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `type`: [DocumentationPartTypeType](./literals.md#documentationparttypetype)
- `nameQuery`: `str`
- `path`: `str`
- `position`: `str`
- `limit`: `int`
- `locationStatus`:
  [LocationStatusTypeType](./literals.md#locationstatustypetype)

Returns a `Coroutine` for
[DocumentationPartsTypeDef](./type_defs.md#documentationpartstypedef).

<a id="get\_documentation\_version"></a>

### get_documentation_version

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/GetDocumentationVersion).

Type annotations for
`session.create_client("apigateway").get_documentation_version` method.

Boto3 documentation:
[APIGateway.Client.get_documentation_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_documentation_version)

Asynchronous method. Use `await get_documentation_version(...)` for a
synchronous call.

Arguments mapping described in
[GetDocumentationVersionRequestRequestTypeDef](./type_defs.md#getdocumentationversionrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `documentationVersion`: `str` *(required)*

Returns a `Coroutine` for
[DocumentationVersionResponseMetadataTypeDef](./type_defs.md#documentationversionresponsemetadatatypedef).

<a id="get\_documentation\_versions"></a>

### get_documentation_versions

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/GetDocumentationVersions).

Type annotations for
`session.create_client("apigateway").get_documentation_versions` method.

Boto3 documentation:
[APIGateway.Client.get_documentation_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_documentation_versions)

Asynchronous method. Use `await get_documentation_versions(...)` for a
synchronous call.

Arguments mapping described in
[GetDocumentationVersionsRequestRequestTypeDef](./type_defs.md#getdocumentationversionsrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[DocumentationVersionsTypeDef](./type_defs.md#documentationversionstypedef).

<a id="get\_domain\_name"></a>

### get_domain_name

Represents a domain name that is contained in a simpler, more intuitive URL
that can be called.

Type annotations for `session.create_client("apigateway").get_domain_name`
method.

Boto3 documentation:
[APIGateway.Client.get_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_domain_name)

Asynchronous method. Use `await get_domain_name(...)` for a synchronous call.

Arguments mapping described in
[GetDomainNameRequestRequestTypeDef](./type_defs.md#getdomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*

Returns a `Coroutine` for
[DomainNameResponseMetadataTypeDef](./type_defs.md#domainnameresponsemetadatatypedef).

<a id="get\_domain\_names"></a>

### get_domain_names

Represents a collection of DomainName resources.

Type annotations for `session.create_client("apigateway").get_domain_names`
method.

Boto3 documentation:
[APIGateway.Client.get_domain_names](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_domain_names)

Asynchronous method. Use `await get_domain_names(...)` for a synchronous call.

Arguments mapping described in
[GetDomainNamesRequestRequestTypeDef](./type_defs.md#getdomainnamesrequestrequesttypedef).

Keyword-only arguments:

- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[DomainNamesTypeDef](./type_defs.md#domainnamestypedef).

<a id="get\_export"></a>

### get_export

Exports a deployed version of a RestApi in a specified format.

Type annotations for `session.create_client("apigateway").get_export` method.

Boto3 documentation:
[APIGateway.Client.get_export](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_export)

Asynchronous method. Use `await get_export(...)` for a synchronous call.

Arguments mapping described in
[GetExportRequestRequestTypeDef](./type_defs.md#getexportrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*
- `exportType`: `str` *(required)*
- `parameters`: `Mapping`\[`str`, `str`\]
- `accepts`: `str`

Returns a `Coroutine` for
[ExportResponseTypeDef](./type_defs.md#exportresponsetypedef).

<a id="get\_gateway\_response"></a>

### get_gateway_response

Gets a GatewayResponse of a specified response type on the given RestApi .

Type annotations for `session.create_client("apigateway").get_gateway_response`
method.

Boto3 documentation:
[APIGateway.Client.get_gateway_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_gateway_response)

Asynchronous method. Use `await get_gateway_response(...)` for a synchronous
call.

Arguments mapping described in
[GetGatewayResponseRequestRequestTypeDef](./type_defs.md#getgatewayresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `responseType`:
  [GatewayResponseTypeType](./literals.md#gatewayresponsetypetype) *(required)*

Returns a `Coroutine` for
[GatewayResponseResponseMetadataTypeDef](./type_defs.md#gatewayresponseresponsemetadatatypedef).

<a id="get\_gateway\_responses"></a>

### get_gateway_responses

Gets the GatewayResponses collection on the given RestApi.

Type annotations for
`session.create_client("apigateway").get_gateway_responses` method.

Boto3 documentation:
[APIGateway.Client.get_gateway_responses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_gateway_responses)

Asynchronous method. Use `await get_gateway_responses(...)` for a synchronous
call.

Arguments mapping described in
[GetGatewayResponsesRequestRequestTypeDef](./type_defs.md#getgatewayresponsesrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[GatewayResponsesTypeDef](./type_defs.md#gatewayresponsestypedef).

<a id="get\_integration"></a>

### get_integration

Get the integration settings.

Type annotations for `session.create_client("apigateway").get_integration`
method.

Boto3 documentation:
[APIGateway.Client.get_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_integration)

Asynchronous method. Use `await get_integration(...)` for a synchronous call.

Arguments mapping described in
[GetIntegrationRequestRequestTypeDef](./type_defs.md#getintegrationrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*

Returns a `Coroutine` for
[IntegrationResponseMetadataTypeDef](./type_defs.md#integrationresponsemetadatatypedef).

<a id="get\_integration\_response"></a>

### get_integration_response

Represents a get integration response.

Type annotations for
`session.create_client("apigateway").get_integration_response` method.

Boto3 documentation:
[APIGateway.Client.get_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_integration_response)

Asynchronous method. Use `await get_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[GetIntegrationResponseRequestRequestTypeDef](./type_defs.md#getintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*

Returns a `Coroutine` for
[IntegrationResponseResponseMetadataTypeDef](./type_defs.md#integrationresponseresponsemetadatatypedef).

<a id="get\_method"></a>

### get_method

Describe an existing Method resource.

Type annotations for `session.create_client("apigateway").get_method` method.

Boto3 documentation:
[APIGateway.Client.get_method](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_method)

Asynchronous method. Use `await get_method(...)` for a synchronous call.

Arguments mapping described in
[GetMethodRequestRequestTypeDef](./type_defs.md#getmethodrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*

Returns a `Coroutine` for
[MethodResponseMetadataTypeDef](./type_defs.md#methodresponsemetadatatypedef).

<a id="get\_method\_response"></a>

### get_method_response

Describes a MethodResponse resource.

Type annotations for `session.create_client("apigateway").get_method_response`
method.

Boto3 documentation:
[APIGateway.Client.get_method_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_method_response)

Asynchronous method. Use `await get_method_response(...)` for a synchronous
call.

Arguments mapping described in
[GetMethodResponseRequestRequestTypeDef](./type_defs.md#getmethodresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*

Returns a `Coroutine` for
[MethodResponseResponseMetadataTypeDef](./type_defs.md#methodresponseresponsemetadatatypedef).

<a id="get\_model"></a>

### get_model

Describes an existing model defined for a RestApi resource.

Type annotations for `session.create_client("apigateway").get_model` method.

Boto3 documentation:
[APIGateway.Client.get_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_model)

Asynchronous method. Use `await get_model(...)` for a synchronous call.

Arguments mapping described in
[GetModelRequestRequestTypeDef](./type_defs.md#getmodelrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `modelName`: `str` *(required)*
- `flatten`: `bool`

Returns a `Coroutine` for
[ModelResponseMetadataTypeDef](./type_defs.md#modelresponsemetadatatypedef).

<a id="get\_model\_template"></a>

### get_model_template

Generates a sample mapping template that can be used to transform a payload
into the structure of a model.

Type annotations for `session.create_client("apigateway").get_model_template`
method.

Boto3 documentation:
[APIGateway.Client.get_model_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_model_template)

Asynchronous method. Use `await get_model_template(...)` for a synchronous
call.

Arguments mapping described in
[GetModelTemplateRequestRequestTypeDef](./type_defs.md#getmodeltemplaterequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `modelName`: `str` *(required)*

Returns a `Coroutine` for [TemplateTypeDef](./type_defs.md#templatetypedef).

<a id="get\_models"></a>

### get_models

Describes existing Models defined for a RestApi resource.

Type annotations for `session.create_client("apigateway").get_models` method.

Boto3 documentation:
[APIGateway.Client.get_models](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_models)

Asynchronous method. Use `await get_models(...)` for a synchronous call.

Arguments mapping described in
[GetModelsRequestRequestTypeDef](./type_defs.md#getmodelsrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for [ModelsTypeDef](./type_defs.md#modelstypedef).

<a id="get\_request\_validator"></a>

### get_request_validator

Gets a RequestValidator of a given RestApi .

Type annotations for
`session.create_client("apigateway").get_request_validator` method.

Boto3 documentation:
[APIGateway.Client.get_request_validator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_request_validator)

Asynchronous method. Use `await get_request_validator(...)` for a synchronous
call.

Arguments mapping described in
[GetRequestValidatorRequestRequestTypeDef](./type_defs.md#getrequestvalidatorrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `requestValidatorId`: `str` *(required)*

Returns a `Coroutine` for
[RequestValidatorResponseMetadataTypeDef](./type_defs.md#requestvalidatorresponsemetadatatypedef).

<a id="get\_request\_validators"></a>

### get_request_validators

Gets the RequestValidators collection of a given RestApi .

Type annotations for
`session.create_client("apigateway").get_request_validators` method.

Boto3 documentation:
[APIGateway.Client.get_request_validators](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_request_validators)

Asynchronous method. Use `await get_request_validators(...)` for a synchronous
call.

Arguments mapping described in
[GetRequestValidatorsRequestRequestTypeDef](./type_defs.md#getrequestvalidatorsrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[RequestValidatorsTypeDef](./type_defs.md#requestvalidatorstypedef).

<a id="get\_resource"></a>

### get_resource

Lists information about a resource.

Type annotations for `session.create_client("apigateway").get_resource` method.

Boto3 documentation:
[APIGateway.Client.get_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_resource)

Asynchronous method. Use `await get_resource(...)` for a synchronous call.

Arguments mapping described in
[GetResourceRequestRequestTypeDef](./type_defs.md#getresourcerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `embed`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ResourceResponseMetadataTypeDef](./type_defs.md#resourceresponsemetadatatypedef).

<a id="get\_resources"></a>

### get_resources

Lists information about a collection of Resource resources.

Type annotations for `session.create_client("apigateway").get_resources`
method.

Boto3 documentation:
[APIGateway.Client.get_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_resources)

Asynchronous method. Use `await get_resources(...)` for a synchronous call.

Arguments mapping described in
[GetResourcesRequestRequestTypeDef](./type_defs.md#getresourcesrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`
- `embed`: `Sequence`\[`str`\]

Returns a `Coroutine` for [ResourcesTypeDef](./type_defs.md#resourcestypedef).

<a id="get\_rest\_api"></a>

### get_rest_api

Lists the RestApi resource in the collection.

Type annotations for `session.create_client("apigateway").get_rest_api` method.

Boto3 documentation:
[APIGateway.Client.get_rest_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_rest_api)

Asynchronous method. Use `await get_rest_api(...)` for a synchronous call.

Arguments mapping described in
[GetRestApiRequestRequestTypeDef](./type_defs.md#getrestapirequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*

Returns a `Coroutine` for
[RestApiResponseMetadataTypeDef](./type_defs.md#restapiresponsemetadatatypedef).

<a id="get\_rest\_apis"></a>

### get_rest_apis

Lists the RestApis resources for your collection.

Type annotations for `session.create_client("apigateway").get_rest_apis`
method.

Boto3 documentation:
[APIGateway.Client.get_rest_apis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_rest_apis)

Asynchronous method. Use `await get_rest_apis(...)` for a synchronous call.

Arguments mapping described in
[GetRestApisRequestRequestTypeDef](./type_defs.md#getrestapisrequestrequesttypedef).

Keyword-only arguments:

- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for [RestApisTypeDef](./type_defs.md#restapistypedef).

<a id="get\_sdk"></a>

### get_sdk

Generates a client SDK for a RestApi and Stage .

Type annotations for `session.create_client("apigateway").get_sdk` method.

Boto3 documentation:
[APIGateway.Client.get_sdk](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_sdk)

Asynchronous method. Use `await get_sdk(...)` for a synchronous call.

Arguments mapping described in
[GetSdkRequestRequestTypeDef](./type_defs.md#getsdkrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*
- `sdkType`: `str` *(required)*
- `parameters`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[SdkResponseTypeDef](./type_defs.md#sdkresponsetypedef).

<a id="get\_sdk\_type"></a>

### get_sdk_type

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/GetSdkType).

Type annotations for `session.create_client("apigateway").get_sdk_type` method.

Boto3 documentation:
[APIGateway.Client.get_sdk_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_sdk_type)

Asynchronous method. Use `await get_sdk_type(...)` for a synchronous call.

Arguments mapping described in
[GetSdkTypeRequestRequestTypeDef](./type_defs.md#getsdktyperequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[SdkTypeResponseMetadataTypeDef](./type_defs.md#sdktyperesponsemetadatatypedef).

<a id="get\_sdk\_types"></a>

### get_sdk_types

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/GetSdkTypes).

Type annotations for `session.create_client("apigateway").get_sdk_types`
method.

Boto3 documentation:
[APIGateway.Client.get_sdk_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_sdk_types)

Asynchronous method. Use `await get_sdk_types(...)` for a synchronous call.

Arguments mapping described in
[GetSdkTypesRequestRequestTypeDef](./type_defs.md#getsdktypesrequestrequesttypedef).

Keyword-only arguments:

- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for [SdkTypesTypeDef](./type_defs.md#sdktypestypedef).

<a id="get\_stage"></a>

### get_stage

Gets information about a Stage resource.

Type annotations for `session.create_client("apigateway").get_stage` method.

Boto3 documentation:
[APIGateway.Client.get_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_stage)

Asynchronous method. Use `await get_stage(...)` for a synchronous call.

Arguments mapping described in
[GetStageRequestRequestTypeDef](./type_defs.md#getstagerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*

Returns a `Coroutine` for
[StageResponseMetadataTypeDef](./type_defs.md#stageresponsemetadatatypedef).

<a id="get\_stages"></a>

### get_stages

Gets information about one or more Stage resources.

Type annotations for `session.create_client("apigateway").get_stages` method.

Boto3 documentation:
[APIGateway.Client.get_stages](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_stages)

Asynchronous method. Use `await get_stages(...)` for a synchronous call.

Arguments mapping described in
[GetStagesRequestRequestTypeDef](./type_defs.md#getstagesrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `deploymentId`: `str`

Returns a `Coroutine` for [StagesTypeDef](./type_defs.md#stagestypedef).

<a id="get\_tags"></a>

### get_tags

Gets the Tags collection for a given resource.

Type annotations for `session.create_client("apigateway").get_tags` method.

Boto3 documentation:
[APIGateway.Client.get_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_tags)

Asynchronous method. Use `await get_tags(...)` for a synchronous call.

Arguments mapping described in
[GetTagsRequestRequestTypeDef](./type_defs.md#gettagsrequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for [TagsTypeDef](./type_defs.md#tagstypedef).

<a id="get\_usage"></a>

### get_usage

Gets the usage data of a usage plan in a specified time interval.

Type annotations for `session.create_client("apigateway").get_usage` method.

Boto3 documentation:
[APIGateway.Client.get_usage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_usage)

Asynchronous method. Use `await get_usage(...)` for a synchronous call.

Arguments mapping described in
[GetUsageRequestRequestTypeDef](./type_defs.md#getusagerequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*
- `startDate`: `str` *(required)*
- `endDate`: `str` *(required)*
- `keyId`: `str`
- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for [UsageTypeDef](./type_defs.md#usagetypedef).

<a id="get\_usage\_plan"></a>

### get_usage_plan

Gets a usage plan of a given plan identifier.

Type annotations for `session.create_client("apigateway").get_usage_plan`
method.

Boto3 documentation:
[APIGateway.Client.get_usage_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_usage_plan)

Asynchronous method. Use `await get_usage_plan(...)` for a synchronous call.

Arguments mapping described in
[GetUsagePlanRequestRequestTypeDef](./type_defs.md#getusageplanrequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*

Returns a `Coroutine` for
[UsagePlanResponseMetadataTypeDef](./type_defs.md#usageplanresponsemetadatatypedef).

<a id="get\_usage\_plan\_key"></a>

### get_usage_plan_key

Gets a usage plan key of a given key identifier.

Type annotations for `session.create_client("apigateway").get_usage_plan_key`
method.

Boto3 documentation:
[APIGateway.Client.get_usage_plan_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_usage_plan_key)

Asynchronous method. Use `await get_usage_plan_key(...)` for a synchronous
call.

Arguments mapping described in
[GetUsagePlanKeyRequestRequestTypeDef](./type_defs.md#getusageplankeyrequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*
- `keyId`: `str` *(required)*

Returns a `Coroutine` for
[UsagePlanKeyResponseMetadataTypeDef](./type_defs.md#usageplankeyresponsemetadatatypedef).

<a id="get\_usage\_plan\_keys"></a>

### get_usage_plan_keys

Gets all the usage plan keys representing the API keys added to a specified
usage plan.

Type annotations for `session.create_client("apigateway").get_usage_plan_keys`
method.

Boto3 documentation:
[APIGateway.Client.get_usage_plan_keys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_usage_plan_keys)

Asynchronous method. Use `await get_usage_plan_keys(...)` for a synchronous
call.

Arguments mapping described in
[GetUsagePlanKeysRequestRequestTypeDef](./type_defs.md#getusageplankeysrequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*
- `position`: `str`
- `limit`: `int`
- `nameQuery`: `str`

Returns a `Coroutine` for
[UsagePlanKeysTypeDef](./type_defs.md#usageplankeystypedef).

<a id="get\_usage\_plans"></a>

### get_usage_plans

Gets all the usage plans of the caller's account.

Type annotations for `session.create_client("apigateway").get_usage_plans`
method.

Boto3 documentation:
[APIGateway.Client.get_usage_plans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_usage_plans)

Asynchronous method. Use `await get_usage_plans(...)` for a synchronous call.

Arguments mapping described in
[GetUsagePlansRequestRequestTypeDef](./type_defs.md#getusageplansrequestrequesttypedef).

Keyword-only arguments:

- `position`: `str`
- `keyId`: `str`
- `limit`: `int`

Returns a `Coroutine` for
[UsagePlansTypeDef](./type_defs.md#usageplanstypedef).

<a id="get\_vpc\_link"></a>

### get_vpc_link

Gets a specified VPC link under the caller's account in a region.

Type annotations for `session.create_client("apigateway").get_vpc_link` method.

Boto3 documentation:
[APIGateway.Client.get_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_vpc_link)

Asynchronous method. Use `await get_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[GetVpcLinkRequestRequestTypeDef](./type_defs.md#getvpclinkrequestrequesttypedef).

Keyword-only arguments:

- `vpcLinkId`: `str` *(required)*

Returns a `Coroutine` for
[VpcLinkResponseMetadataTypeDef](./type_defs.md#vpclinkresponsemetadatatypedef).

<a id="get\_vpc\_links"></a>

### get_vpc_links

Gets the VpcLinks collection under the caller's account in a selected region.

Type annotations for `session.create_client("apigateway").get_vpc_links`
method.

Boto3 documentation:
[APIGateway.Client.get_vpc_links](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.get_vpc_links)

Asynchronous method. Use `await get_vpc_links(...)` for a synchronous call.

Arguments mapping described in
[GetVpcLinksRequestRequestTypeDef](./type_defs.md#getvpclinksrequestrequesttypedef).

Keyword-only arguments:

- `position`: `str`
- `limit`: `int`

Returns a `Coroutine` for [VpcLinksTypeDef](./type_defs.md#vpclinkstypedef).

<a id="import\_api\_keys"></a>

### import_api_keys

Import API keys from an external source, such as a CSV-formatted file.

Type annotations for `session.create_client("apigateway").import_api_keys`
method.

Boto3 documentation:
[APIGateway.Client.import_api_keys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.import_api_keys)

Asynchronous method. Use `await import_api_keys(...)` for a synchronous call.

Arguments mapping described in
[ImportApiKeysRequestRequestTypeDef](./type_defs.md#importapikeysrequestrequesttypedef).

Keyword-only arguments:

- `body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `format`: `Literal['csv']` (see
  [ApiKeysFormatType](./literals.md#apikeysformattype)) *(required)*
- `failOnWarnings`: `bool`

Returns a `Coroutine` for [ApiKeyIdsTypeDef](./type_defs.md#apikeyidstypedef).

<a id="import\_documentation\_parts"></a>

### import_documentation_parts

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/ImportDocumentationParts).

Type annotations for
`session.create_client("apigateway").import_documentation_parts` method.

Boto3 documentation:
[APIGateway.Client.import_documentation_parts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.import_documentation_parts)

Asynchronous method. Use `await import_documentation_parts(...)` for a
synchronous call.

Arguments mapping described in
[ImportDocumentationPartsRequestRequestTypeDef](./type_defs.md#importdocumentationpartsrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `mode`: [PutModeType](./literals.md#putmodetype)
- `failOnWarnings`: `bool`

Returns a `Coroutine` for
[DocumentationPartIdsTypeDef](./type_defs.md#documentationpartidstypedef).

<a id="import\_rest\_api"></a>

### import_rest_api

A feature of the API Gateway control service for creating a new API from an
external API definition file.

Type annotations for `session.create_client("apigateway").import_rest_api`
method.

Boto3 documentation:
[APIGateway.Client.import_rest_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.import_rest_api)

Asynchronous method. Use `await import_rest_api(...)` for a synchronous call.

Arguments mapping described in
[ImportRestApiRequestRequestTypeDef](./type_defs.md#importrestapirequestrequesttypedef).

Keyword-only arguments:

- `body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `failOnWarnings`: `bool`
- `parameters`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[RestApiResponseMetadataTypeDef](./type_defs.md#restapiresponsemetadatatypedef).

<a id="put\_gateway\_response"></a>

### put_gateway_response

Creates a customization of a GatewayResponse of a specified response type and
status code on the given RestApi .

Type annotations for `session.create_client("apigateway").put_gateway_response`
method.

Boto3 documentation:
[APIGateway.Client.put_gateway_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.put_gateway_response)

Asynchronous method. Use `await put_gateway_response(...)` for a synchronous
call.

Arguments mapping described in
[PutGatewayResponseRequestRequestTypeDef](./type_defs.md#putgatewayresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `responseType`:
  [GatewayResponseTypeType](./literals.md#gatewayresponsetypetype) *(required)*
- `statusCode`: `str`
- `responseParameters`: `Mapping`\[`str`, `str`\]
- `responseTemplates`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[GatewayResponseResponseMetadataTypeDef](./type_defs.md#gatewayresponseresponsemetadatatypedef).

<a id="put\_integration"></a>

### put_integration

Sets up a method's integration.

Type annotations for `session.create_client("apigateway").put_integration`
method.

Boto3 documentation:
[APIGateway.Client.put_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.put_integration)

Asynchronous method. Use `await put_integration(...)` for a synchronous call.

Arguments mapping described in
[PutIntegrationRequestRequestTypeDef](./type_defs.md#putintegrationrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `type`: [IntegrationTypeType](./literals.md#integrationtypetype) *(required)*
- `integrationHttpMethod`: `str`
- `uri`: `str`
- `connectionType`: [ConnectionTypeType](./literals.md#connectiontypetype)
- `connectionId`: `str`
- `credentials`: `str`
- `requestParameters`: `Mapping`\[`str`, `str`\]
- `requestTemplates`: `Mapping`\[`str`, `str`\]
- `passthroughBehavior`: `str`
- `cacheNamespace`: `str`
- `cacheKeyParameters`: `Sequence`\[`str`\]
- `contentHandling`:
  [ContentHandlingStrategyType](./literals.md#contenthandlingstrategytype)
- `timeoutInMillis`: `int`
- `tlsConfig`: [TlsConfigTypeDef](./type_defs.md#tlsconfigtypedef)

Returns a `Coroutine` for
[IntegrationResponseMetadataTypeDef](./type_defs.md#integrationresponsemetadatatypedef).

<a id="put\_integration\_response"></a>

### put_integration_response

Represents a put integration.

Type annotations for
`session.create_client("apigateway").put_integration_response` method.

Boto3 documentation:
[APIGateway.Client.put_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.put_integration_response)

Asynchronous method. Use `await put_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[PutIntegrationResponseRequestRequestTypeDef](./type_defs.md#putintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*
- `selectionPattern`: `str`
- `responseParameters`: `Mapping`\[`str`, `str`\]
- `responseTemplates`: `Mapping`\[`str`, `str`\]
- `contentHandling`:
  [ContentHandlingStrategyType](./literals.md#contenthandlingstrategytype)

Returns a `Coroutine` for
[IntegrationResponseResponseMetadataTypeDef](./type_defs.md#integrationresponseresponsemetadatatypedef).

<a id="put\_method"></a>

### put_method

Add a method to an existing Resource resource.

Type annotations for `session.create_client("apigateway").put_method` method.

Boto3 documentation:
[APIGateway.Client.put_method](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.put_method)

Asynchronous method. Use `await put_method(...)` for a synchronous call.

Arguments mapping described in
[PutMethodRequestRequestTypeDef](./type_defs.md#putmethodrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `authorizationType`: `str` *(required)*
- `authorizerId`: `str`
- `apiKeyRequired`: `bool`
- `operationName`: `str`
- `requestParameters`: `Mapping`\[`str`, `bool`\]
- `requestModels`: `Mapping`\[`str`, `str`\]
- `requestValidatorId`: `str`
- `authorizationScopes`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[MethodResponseMetadataTypeDef](./type_defs.md#methodresponsemetadatatypedef).

<a id="put\_method\_response"></a>

### put_method_response

Adds a MethodResponse to an existing Method resource.

Type annotations for `session.create_client("apigateway").put_method_response`
method.

Boto3 documentation:
[APIGateway.Client.put_method_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.put_method_response)

Asynchronous method. Use `await put_method_response(...)` for a synchronous
call.

Arguments mapping described in
[PutMethodResponseRequestRequestTypeDef](./type_defs.md#putmethodresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*
- `responseParameters`: `Mapping`\[`str`, `bool`\]
- `responseModels`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[MethodResponseResponseMetadataTypeDef](./type_defs.md#methodresponseresponsemetadatatypedef).

<a id="put\_rest\_api"></a>

### put_rest_api

A feature of the API Gateway control service for updating an existing API with
an input of external API definitions.

Type annotations for `session.create_client("apigateway").put_rest_api` method.

Boto3 documentation:
[APIGateway.Client.put_rest_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.put_rest_api)

Asynchronous method. Use `await put_rest_api(...)` for a synchronous call.

Arguments mapping described in
[PutRestApiRequestRequestTypeDef](./type_defs.md#putrestapirequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `mode`: [PutModeType](./literals.md#putmodetype)
- `failOnWarnings`: `bool`
- `parameters`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[RestApiResponseMetadataTypeDef](./type_defs.md#restapiresponsemetadatatypedef).

<a id="tag\_resource"></a>

### tag_resource

Adds or updates a tag on a given resource.

Type annotations for `session.create_client("apigateway").tag_resource` method.

Boto3 documentation:
[APIGateway.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="test\_invoke\_authorizer"></a>

### test_invoke_authorizer

Simulate the execution of an Authorizer in your RestApi with headers,
parameters, and an incoming request body.

Type annotations for
`session.create_client("apigateway").test_invoke_authorizer` method.

Boto3 documentation:
[APIGateway.Client.test_invoke_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.test_invoke_authorizer)

Asynchronous method. Use `await test_invoke_authorizer(...)` for a synchronous
call.

Arguments mapping described in
[TestInvokeAuthorizerRequestRequestTypeDef](./type_defs.md#testinvokeauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `authorizerId`: `str` *(required)*
- `headers`: `Mapping`\[`str`, `str`\]
- `multiValueHeaders`: `Mapping`\[`str`, `Sequence`\[`str`\]\]
- `pathWithQueryString`: `str`
- `body`: `str`
- `stageVariables`: `Mapping`\[`str`, `str`\]
- `additionalContext`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[TestInvokeAuthorizerResponseTypeDef](./type_defs.md#testinvokeauthorizerresponsetypedef).

<a id="test\_invoke\_method"></a>

### test_invoke_method

Simulate the execution of a Method in your RestApi with headers, parameters,
and an incoming request body.

Type annotations for `session.create_client("apigateway").test_invoke_method`
method.

Boto3 documentation:
[APIGateway.Client.test_invoke_method](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.test_invoke_method)

Asynchronous method. Use `await test_invoke_method(...)` for a synchronous
call.

Arguments mapping described in
[TestInvokeMethodRequestRequestTypeDef](./type_defs.md#testinvokemethodrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `pathWithQueryString`: `str`
- `body`: `str`
- `headers`: `Mapping`\[`str`, `str`\]
- `multiValueHeaders`: `Mapping`\[`str`, `Sequence`\[`str`\]\]
- `clientCertificateId`: `str`
- `stageVariables`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[TestInvokeMethodResponseTypeDef](./type_defs.md#testinvokemethodresponsetypedef).

<a id="untag\_resource"></a>

### untag_resource

Removes a tag from a given resource.

Type annotations for `session.create_client("apigateway").untag_resource`
method.

Boto3 documentation:
[APIGateway.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update\_account"></a>

### update_account

Changes information about the current Account resource.

Type annotations for `session.create_client("apigateway").update_account`
method.

Boto3 documentation:
[APIGateway.Client.update_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_account)

Asynchronous method. Use `await update_account(...)` for a synchronous call.

Arguments mapping described in
[UpdateAccountRequestRequestTypeDef](./type_defs.md#updateaccountrequestrequesttypedef).

Keyword-only arguments:

- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for [AccountTypeDef](./type_defs.md#accounttypedef).

<a id="update\_api\_key"></a>

### update_api_key

Changes information about an ApiKey resource.

Type annotations for `session.create_client("apigateway").update_api_key`
method.

Boto3 documentation:
[APIGateway.Client.update_api_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_api_key)

Asynchronous method. Use `await update_api_key(...)` for a synchronous call.

Arguments mapping described in
[UpdateApiKeyRequestRequestTypeDef](./type_defs.md#updateapikeyrequestrequesttypedef).

Keyword-only arguments:

- `apiKey`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[ApiKeyResponseMetadataTypeDef](./type_defs.md#apikeyresponsemetadatatypedef).

<a id="update\_authorizer"></a>

### update_authorizer

Updates an existing Authorizer resource.

Type annotations for `session.create_client("apigateway").update_authorizer`
method.

Boto3 documentation:
[APIGateway.Client.update_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_authorizer)

Asynchronous method. Use `await update_authorizer(...)` for a synchronous call.

Arguments mapping described in
[UpdateAuthorizerRequestRequestTypeDef](./type_defs.md#updateauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `authorizerId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[AuthorizerResponseMetadataTypeDef](./type_defs.md#authorizerresponsemetadatatypedef).

<a id="update\_base\_path\_mapping"></a>

### update_base_path_mapping

Changes information about the BasePathMapping resource.

Type annotations for
`session.create_client("apigateway").update_base_path_mapping` method.

Boto3 documentation:
[APIGateway.Client.update_base_path_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_base_path_mapping)

Asynchronous method. Use `await update_base_path_mapping(...)` for a
synchronous call.

Arguments mapping described in
[UpdateBasePathMappingRequestRequestTypeDef](./type_defs.md#updatebasepathmappingrequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `basePath`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[BasePathMappingResponseMetadataTypeDef](./type_defs.md#basepathmappingresponsemetadatatypedef).

<a id="update\_client\_certificate"></a>

### update_client_certificate

Changes information about an ClientCertificate resource.

Type annotations for
`session.create_client("apigateway").update_client_certificate` method.

Boto3 documentation:
[APIGateway.Client.update_client_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_client_certificate)

Asynchronous method. Use `await update_client_certificate(...)` for a
synchronous call.

Arguments mapping described in
[UpdateClientCertificateRequestRequestTypeDef](./type_defs.md#updateclientcertificaterequestrequesttypedef).

Keyword-only arguments:

- `clientCertificateId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[ClientCertificateResponseMetadataTypeDef](./type_defs.md#clientcertificateresponsemetadatatypedef).

<a id="update\_deployment"></a>

### update_deployment

Changes information about a Deployment resource.

Type annotations for `session.create_client("apigateway").update_deployment`
method.

Boto3 documentation:
[APIGateway.Client.update_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_deployment)

Asynchronous method. Use `await update_deployment(...)` for a synchronous call.

Arguments mapping described in
[UpdateDeploymentRequestRequestTypeDef](./type_defs.md#updatedeploymentrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `deploymentId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[DeploymentResponseMetadataTypeDef](./type_defs.md#deploymentresponsemetadatatypedef).

<a id="update\_documentation\_part"></a>

### update_documentation_part

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/UpdateDocumentationPart).

Type annotations for
`session.create_client("apigateway").update_documentation_part` method.

Boto3 documentation:
[APIGateway.Client.update_documentation_part](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_documentation_part)

Asynchronous method. Use `await update_documentation_part(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDocumentationPartRequestRequestTypeDef](./type_defs.md#updatedocumentationpartrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `documentationPartId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[DocumentationPartResponseMetadataTypeDef](./type_defs.md#documentationpartresponsemetadatatypedef).

<a id="update\_documentation\_version"></a>

### update_documentation_version

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/apigateway-2015-07-09/UpdateDocumentationVersion).

Type annotations for
`session.create_client("apigateway").update_documentation_version` method.

Boto3 documentation:
[APIGateway.Client.update_documentation_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_documentation_version)

Asynchronous method. Use `await update_documentation_version(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDocumentationVersionRequestRequestTypeDef](./type_defs.md#updatedocumentationversionrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `documentationVersion`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[DocumentationVersionResponseMetadataTypeDef](./type_defs.md#documentationversionresponsemetadatatypedef).

<a id="update\_domain\_name"></a>

### update_domain_name

Changes information about the DomainName resource.

Type annotations for `session.create_client("apigateway").update_domain_name`
method.

Boto3 documentation:
[APIGateway.Client.update_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_domain_name)

Asynchronous method. Use `await update_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[UpdateDomainNameRequestRequestTypeDef](./type_defs.md#updatedomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[DomainNameResponseMetadataTypeDef](./type_defs.md#domainnameresponsemetadatatypedef).

<a id="update\_gateway\_response"></a>

### update_gateway_response

Updates a GatewayResponse of a specified response type on the given RestApi .

Type annotations for
`session.create_client("apigateway").update_gateway_response` method.

Boto3 documentation:
[APIGateway.Client.update_gateway_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_gateway_response)

Asynchronous method. Use `await update_gateway_response(...)` for a synchronous
call.

Arguments mapping described in
[UpdateGatewayResponseRequestRequestTypeDef](./type_defs.md#updategatewayresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `responseType`:
  [GatewayResponseTypeType](./literals.md#gatewayresponsetypetype) *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[GatewayResponseResponseMetadataTypeDef](./type_defs.md#gatewayresponseresponsemetadatatypedef).

<a id="update\_integration"></a>

### update_integration

Represents an update integration.

Type annotations for `session.create_client("apigateway").update_integration`
method.

Boto3 documentation:
[APIGateway.Client.update_integration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_integration)

Asynchronous method. Use `await update_integration(...)` for a synchronous
call.

Arguments mapping described in
[UpdateIntegrationRequestRequestTypeDef](./type_defs.md#updateintegrationrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[IntegrationResponseMetadataTypeDef](./type_defs.md#integrationresponsemetadatatypedef).

<a id="update\_integration\_response"></a>

### update_integration_response

Represents an update integration response.

Type annotations for
`session.create_client("apigateway").update_integration_response` method.

Boto3 documentation:
[APIGateway.Client.update_integration_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_integration_response)

Asynchronous method. Use `await update_integration_response(...)` for a
synchronous call.

Arguments mapping described in
[UpdateIntegrationResponseRequestRequestTypeDef](./type_defs.md#updateintegrationresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[IntegrationResponseResponseMetadataTypeDef](./type_defs.md#integrationresponseresponsemetadatatypedef).

<a id="update\_method"></a>

### update_method

Updates an existing Method resource.

Type annotations for `session.create_client("apigateway").update_method`
method.

Boto3 documentation:
[APIGateway.Client.update_method](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_method)

Asynchronous method. Use `await update_method(...)` for a synchronous call.

Arguments mapping described in
[UpdateMethodRequestRequestTypeDef](./type_defs.md#updatemethodrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[MethodResponseMetadataTypeDef](./type_defs.md#methodresponsemetadatatypedef).

<a id="update\_method\_response"></a>

### update_method_response

Updates an existing MethodResponse resource.

Type annotations for
`session.create_client("apigateway").update_method_response` method.

Boto3 documentation:
[APIGateway.Client.update_method_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_method_response)

Asynchronous method. Use `await update_method_response(...)` for a synchronous
call.

Arguments mapping described in
[UpdateMethodResponseRequestRequestTypeDef](./type_defs.md#updatemethodresponserequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `httpMethod`: `str` *(required)*
- `statusCode`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[MethodResponseResponseMetadataTypeDef](./type_defs.md#methodresponseresponsemetadatatypedef).

<a id="update\_model"></a>

### update_model

Changes information about a model.

Type annotations for `session.create_client("apigateway").update_model` method.

Boto3 documentation:
[APIGateway.Client.update_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_model)

Asynchronous method. Use `await update_model(...)` for a synchronous call.

Arguments mapping described in
[UpdateModelRequestRequestTypeDef](./type_defs.md#updatemodelrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `modelName`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[ModelResponseMetadataTypeDef](./type_defs.md#modelresponsemetadatatypedef).

<a id="update\_request\_validator"></a>

### update_request_validator

Updates a RequestValidator of a given RestApi .

Type annotations for
`session.create_client("apigateway").update_request_validator` method.

Boto3 documentation:
[APIGateway.Client.update_request_validator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_request_validator)

Asynchronous method. Use `await update_request_validator(...)` for a
synchronous call.

Arguments mapping described in
[UpdateRequestValidatorRequestRequestTypeDef](./type_defs.md#updaterequestvalidatorrequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `requestValidatorId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[RequestValidatorResponseMetadataTypeDef](./type_defs.md#requestvalidatorresponsemetadatatypedef).

<a id="update\_resource"></a>

### update_resource

Changes information about a Resource resource.

Type annotations for `session.create_client("apigateway").update_resource`
method.

Boto3 documentation:
[APIGateway.Client.update_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_resource)

Asynchronous method. Use `await update_resource(...)` for a synchronous call.

Arguments mapping described in
[UpdateResourceRequestRequestTypeDef](./type_defs.md#updateresourcerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `resourceId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[ResourceResponseMetadataTypeDef](./type_defs.md#resourceresponsemetadatatypedef).

<a id="update\_rest\_api"></a>

### update_rest_api

Changes information about the specified API.

Type annotations for `session.create_client("apigateway").update_rest_api`
method.

Boto3 documentation:
[APIGateway.Client.update_rest_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_rest_api)

Asynchronous method. Use `await update_rest_api(...)` for a synchronous call.

Arguments mapping described in
[UpdateRestApiRequestRequestTypeDef](./type_defs.md#updaterestapirequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[RestApiResponseMetadataTypeDef](./type_defs.md#restapiresponsemetadatatypedef).

<a id="update\_stage"></a>

### update_stage

Changes information about a Stage resource.

Type annotations for `session.create_client("apigateway").update_stage` method.

Boto3 documentation:
[APIGateway.Client.update_stage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_stage)

Asynchronous method. Use `await update_stage(...)` for a synchronous call.

Arguments mapping described in
[UpdateStageRequestRequestTypeDef](./type_defs.md#updatestagerequestrequesttypedef).

Keyword-only arguments:

- `restApiId`: `str` *(required)*
- `stageName`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[StageResponseMetadataTypeDef](./type_defs.md#stageresponsemetadatatypedef).

<a id="update\_usage"></a>

### update_usage

Grants a temporary extension to the remaining quota of a usage plan associated
with a specified API key.

Type annotations for `session.create_client("apigateway").update_usage` method.

Boto3 documentation:
[APIGateway.Client.update_usage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_usage)

Asynchronous method. Use `await update_usage(...)` for a synchronous call.

Arguments mapping described in
[UpdateUsageRequestRequestTypeDef](./type_defs.md#updateusagerequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*
- `keyId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for [UsageTypeDef](./type_defs.md#usagetypedef).

<a id="update\_usage\_plan"></a>

### update_usage_plan

Updates a usage plan of a given plan Id.

Type annotations for `session.create_client("apigateway").update_usage_plan`
method.

Boto3 documentation:
[APIGateway.Client.update_usage_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_usage_plan)

Asynchronous method. Use `await update_usage_plan(...)` for a synchronous call.

Arguments mapping described in
[UpdateUsagePlanRequestRequestTypeDef](./type_defs.md#updateusageplanrequestrequesttypedef).

Keyword-only arguments:

- `usagePlanId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[UsagePlanResponseMetadataTypeDef](./type_defs.md#usageplanresponsemetadatatypedef).

<a id="update\_vpc\_link"></a>

### update_vpc_link

Updates an existing VpcLink of a specified identifier.

Type annotations for `session.create_client("apigateway").update_vpc_link`
method.

Boto3 documentation:
[APIGateway.Client.update_vpc_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.update_vpc_link)

Asynchronous method. Use `await update_vpc_link(...)` for a synchronous call.

Arguments mapping described in
[UpdateVpcLinkRequestRequestTypeDef](./type_defs.md#updatevpclinkrequestrequesttypedef).

Keyword-only arguments:

- `vpcLinkId`: `str` *(required)*
- `patchOperations`:
  `Sequence`\[[PatchOperationTypeDef](./type_defs.md#patchoperationtypedef)\]

Returns a `Coroutine` for
[VpcLinkResponseMetadataTypeDef](./type_defs.md#vpclinkresponsemetadatatypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("apigateway").__aenter__` method.

Boto3 documentation:
[APIGateway.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [APIGatewayClient](#apigatewayclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("apigateway").__aexit__` method.

Boto3 documentation:
[APIGateway.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html#APIGateway.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("apigateway").get_paginator` method
with overloads.

- `client.get_paginator("get_api_keys")` ->
  [GetApiKeysPaginator](./paginators.md#getapikeyspaginator)
- `client.get_paginator("get_authorizers")` ->
  [GetAuthorizersPaginator](./paginators.md#getauthorizerspaginator)
- `client.get_paginator("get_base_path_mappings")` ->
  [GetBasePathMappingsPaginator](./paginators.md#getbasepathmappingspaginator)
- `client.get_paginator("get_client_certificates")` ->
  [GetClientCertificatesPaginator](./paginators.md#getclientcertificatespaginator)
- `client.get_paginator("get_deployments")` ->
  [GetDeploymentsPaginator](./paginators.md#getdeploymentspaginator)
- `client.get_paginator("get_documentation_parts")` ->
  [GetDocumentationPartsPaginator](./paginators.md#getdocumentationpartspaginator)
- `client.get_paginator("get_documentation_versions")` ->
  [GetDocumentationVersionsPaginator](./paginators.md#getdocumentationversionspaginator)
- `client.get_paginator("get_domain_names")` ->
  [GetDomainNamesPaginator](./paginators.md#getdomainnamespaginator)
- `client.get_paginator("get_gateway_responses")` ->
  [GetGatewayResponsesPaginator](./paginators.md#getgatewayresponsespaginator)
- `client.get_paginator("get_models")` ->
  [GetModelsPaginator](./paginators.md#getmodelspaginator)
- `client.get_paginator("get_request_validators")` ->
  [GetRequestValidatorsPaginator](./paginators.md#getrequestvalidatorspaginator)
- `client.get_paginator("get_resources")` ->
  [GetResourcesPaginator](./paginators.md#getresourcespaginator)
- `client.get_paginator("get_rest_apis")` ->
  [GetRestApisPaginator](./paginators.md#getrestapispaginator)
- `client.get_paginator("get_sdk_types")` ->
  [GetSdkTypesPaginator](./paginators.md#getsdktypespaginator)
- `client.get_paginator("get_usage")` ->
  [GetUsagePaginator](./paginators.md#getusagepaginator)
- `client.get_paginator("get_usage_plan_keys")` ->
  [GetUsagePlanKeysPaginator](./paginators.md#getusageplankeyspaginator)
- `client.get_paginator("get_usage_plans")` ->
  [GetUsagePlansPaginator](./paginators.md#getusageplanspaginator)
- `client.get_paginator("get_vpc_links")` ->
  [GetVpcLinksPaginator](./paginators.md#getvpclinkspaginator)
