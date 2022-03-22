<a id="appsyncclient-for-aiobotocore-appsync-module"></a>

# AppSyncClient for aiobotocore AppSync module

> [Index](../README.md) > [AppSync](./README.md) > AppSyncClient

Auto-generated documentation for
[AppSync](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
type annotations stubs module
[types-aiobotocore-appsync](https://pypi.org/project/types-aiobotocore-appsync/).

- [AppSyncClient for aiobotocore AppSync module](#appsyncclient-for-aiobotocore-appsync-module)
  - [AppSyncClient](#appsyncclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_api](#associate_api)
    - [can_paginate](#can_paginate)
    - [create_api_cache](#create_api_cache)
    - [create_api_key](#create_api_key)
    - [create_data_source](#create_data_source)
    - [create_domain_name](#create_domain_name)
    - [create_function](#create_function)
    - [create_graphql_api](#create_graphql_api)
    - [create_resolver](#create_resolver)
    - [create_type](#create_type)
    - [delete_api_cache](#delete_api_cache)
    - [delete_api_key](#delete_api_key)
    - [delete_data_source](#delete_data_source)
    - [delete_domain_name](#delete_domain_name)
    - [delete_function](#delete_function)
    - [delete_graphql_api](#delete_graphql_api)
    - [delete_resolver](#delete_resolver)
    - [delete_type](#delete_type)
    - [disassociate_api](#disassociate_api)
    - [flush_api_cache](#flush_api_cache)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_api_association](#get_api_association)
    - [get_api_cache](#get_api_cache)
    - [get_data_source](#get_data_source)
    - [get_domain_name](#get_domain_name)
    - [get_function](#get_function)
    - [get_graphql_api](#get_graphql_api)
    - [get_introspection_schema](#get_introspection_schema)
    - [get_resolver](#get_resolver)
    - [get_schema_creation_status](#get_schema_creation_status)
    - [get_type](#get_type)
    - [list_api_keys](#list_api_keys)
    - [list_data_sources](#list_data_sources)
    - [list_domain_names](#list_domain_names)
    - [list_functions](#list_functions)
    - [list_graphql_apis](#list_graphql_apis)
    - [list_resolvers](#list_resolvers)
    - [list_resolvers_by_function](#list_resolvers_by_function)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_types](#list_types)
    - [start_schema_creation](#start_schema_creation)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_api_cache](#update_api_cache)
    - [update_api_key](#update_api_key)
    - [update_data_source](#update_data_source)
    - [update_domain_name](#update_domain_name)
    - [update_function](#update_function)
    - [update_graphql_api](#update_graphql_api)
    - [update_resolver](#update_resolver)
    - [update_type](#update_type)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="appsyncclient"></a>

## AppSyncClient

Type annotations for `session.create_client("appsync")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_appsync.client import AppSyncClient

session = get_session()
async with session.create_client("appsync") as client:
    client: AppSyncClient
```

Boto3 documentation:
[AppSync.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_appsync.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ApiKeyLimitExceededException`
- `Exceptions.ApiKeyValidityOutOfBoundsException`
- `Exceptions.ApiLimitExceededException`
- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConcurrentModificationException`
- `Exceptions.GraphQLSchemaException`
- `Exceptions.InternalFailureException`
- `Exceptions.LimitExceededException`
- `Exceptions.NotFoundException`
- `Exceptions.UnauthorizedException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

AppSyncClient exceptions.

Type annotations for `session.create_client("appsync").exceptions` method.

Boto3 documentation:
[AppSync.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate\_api"></a>

### associate_api

Maps an endpoint to your custom domain.

Type annotations for `session.create_client("appsync").associate_api` method.

Boto3 documentation:
[AppSync.Client.associate_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.associate_api)

Asynchronous method. Use `await associate_api(...)` for a synchronous call.

Arguments mapping described in
[AssociateApiRequestRequestTypeDef](./type_defs.md#associateapirequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `apiId`: `str` *(required)*

Returns a `Coroutine` for
[AssociateApiResponseTypeDef](./type_defs.md#associateapiresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("appsync").can_paginate` method.

Boto3 documentation:
[AppSync.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_api\_cache"></a>

### create_api_cache

Creates a cache for the GraphQL API.

Type annotations for `session.create_client("appsync").create_api_cache`
method.

Boto3 documentation:
[AppSync.Client.create_api_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_api_cache)

Asynchronous method. Use `await create_api_cache(...)` for a synchronous call.

Arguments mapping described in
[CreateApiCacheRequestRequestTypeDef](./type_defs.md#createapicacherequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `ttl`: `int` *(required)*
- `apiCachingBehavior`:
  [ApiCachingBehaviorType](./literals.md#apicachingbehaviortype) *(required)*
- `type`: [ApiCacheTypeType](./literals.md#apicachetypetype) *(required)*
- `transitEncryptionEnabled`: `bool`
- `atRestEncryptionEnabled`: `bool`

Returns a `Coroutine` for
[CreateApiCacheResponseTypeDef](./type_defs.md#createapicacheresponsetypedef).

<a id="create\_api\_key"></a>

### create_api_key

Creates a unique key that you can distribute to clients who invoke your API.

Type annotations for `session.create_client("appsync").create_api_key` method.

Boto3 documentation:
[AppSync.Client.create_api_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_api_key)

Asynchronous method. Use `await create_api_key(...)` for a synchronous call.

Arguments mapping described in
[CreateApiKeyRequestRequestTypeDef](./type_defs.md#createapikeyrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `description`: `str`
- `expires`: `int`

Returns a `Coroutine` for
[CreateApiKeyResponseTypeDef](./type_defs.md#createapikeyresponsetypedef).

<a id="create\_data\_source"></a>

### create_data_source

Creates a `DataSource` object.

Type annotations for `session.create_client("appsync").create_data_source`
method.

Boto3 documentation:
[AppSync.Client.create_data_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_data_source)

Asynchronous method. Use `await create_data_source(...)` for a synchronous
call.

Arguments mapping described in
[CreateDataSourceRequestRequestTypeDef](./type_defs.md#createdatasourcerequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `name`: `str` *(required)*
- `type`: [DataSourceTypeType](./literals.md#datasourcetypetype) *(required)*
- `description`: `str`
- `serviceRoleArn`: `str`
- `dynamodbConfig`:
  [DynamodbDataSourceConfigTypeDef](./type_defs.md#dynamodbdatasourceconfigtypedef)
- `lambdaConfig`:
  [LambdaDataSourceConfigTypeDef](./type_defs.md#lambdadatasourceconfigtypedef)
- `elasticsearchConfig`:
  [ElasticsearchDataSourceConfigTypeDef](./type_defs.md#elasticsearchdatasourceconfigtypedef)
- `openSearchServiceConfig`:
  [OpenSearchServiceDataSourceConfigTypeDef](./type_defs.md#opensearchservicedatasourceconfigtypedef)
- `httpConfig`:
  [HttpDataSourceConfigTypeDef](./type_defs.md#httpdatasourceconfigtypedef)
- `relationalDatabaseConfig`:
  [RelationalDatabaseDataSourceConfigTypeDef](./type_defs.md#relationaldatabasedatasourceconfigtypedef)

Returns a `Coroutine` for
[CreateDataSourceResponseTypeDef](./type_defs.md#createdatasourceresponsetypedef).

<a id="create\_domain\_name"></a>

### create_domain_name

Creates a custom `DomainName` object.

Type annotations for `session.create_client("appsync").create_domain_name`
method.

Boto3 documentation:
[AppSync.Client.create_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_domain_name)

Asynchronous method. Use `await create_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[CreateDomainNameRequestRequestTypeDef](./type_defs.md#createdomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `certificateArn`: `str` *(required)*
- `description`: `str`

Returns a `Coroutine` for
[CreateDomainNameResponseTypeDef](./type_defs.md#createdomainnameresponsetypedef).

<a id="create\_function"></a>

### create_function

Creates a `Function` object.

Type annotations for `session.create_client("appsync").create_function` method.

Boto3 documentation:
[AppSync.Client.create_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_function)

Asynchronous method. Use `await create_function(...)` for a synchronous call.

Arguments mapping described in
[CreateFunctionRequestRequestTypeDef](./type_defs.md#createfunctionrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `name`: `str` *(required)*
- `dataSourceName`: `str` *(required)*
- `functionVersion`: `str` *(required)*
- `description`: `str`
- `requestMappingTemplate`: `str`
- `responseMappingTemplate`: `str`
- `syncConfig`: [SyncConfigTypeDef](./type_defs.md#syncconfigtypedef)
- `maxBatchSize`: `int`

Returns a `Coroutine` for
[CreateFunctionResponseTypeDef](./type_defs.md#createfunctionresponsetypedef).

<a id="create\_graphql\_api"></a>

### create_graphql_api

Creates a `GraphqlApi` object.

Type annotations for `session.create_client("appsync").create_graphql_api`
method.

Boto3 documentation:
[AppSync.Client.create_graphql_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_graphql_api)

Asynchronous method. Use `await create_graphql_api(...)` for a synchronous
call.

Arguments mapping described in
[CreateGraphqlApiRequestRequestTypeDef](./type_defs.md#creategraphqlapirequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `authenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype) *(required)*
- `logConfig`: [LogConfigTypeDef](./type_defs.md#logconfigtypedef)
- `userPoolConfig`:
  [UserPoolConfigTypeDef](./type_defs.md#userpoolconfigtypedef)
- `openIDConnectConfig`:
  [OpenIDConnectConfigTypeDef](./type_defs.md#openidconnectconfigtypedef)
- `tags`: `Mapping`\[`str`, `str`\]
- `additionalAuthenticationProviders`:
  `Sequence`\[[AdditionalAuthenticationProviderTypeDef](./type_defs.md#additionalauthenticationprovidertypedef)\]
- `xrayEnabled`: `bool`
- `lambdaAuthorizerConfig`:
  [LambdaAuthorizerConfigTypeDef](./type_defs.md#lambdaauthorizerconfigtypedef)

Returns a `Coroutine` for
[CreateGraphqlApiResponseTypeDef](./type_defs.md#creategraphqlapiresponsetypedef).

<a id="create\_resolver"></a>

### create_resolver

Creates a `Resolver` object.

Type annotations for `session.create_client("appsync").create_resolver` method.

Boto3 documentation:
[AppSync.Client.create_resolver](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_resolver)

Asynchronous method. Use `await create_resolver(...)` for a synchronous call.

Arguments mapping described in
[CreateResolverRequestRequestTypeDef](./type_defs.md#createresolverrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `fieldName`: `str` *(required)*
- `dataSourceName`: `str`
- `requestMappingTemplate`: `str`
- `responseMappingTemplate`: `str`
- `kind`: [ResolverKindType](./literals.md#resolverkindtype)
- `pipelineConfig`:
  [PipelineConfigTypeDef](./type_defs.md#pipelineconfigtypedef)
- `syncConfig`: [SyncConfigTypeDef](./type_defs.md#syncconfigtypedef)
- `cachingConfig`: [CachingConfigTypeDef](./type_defs.md#cachingconfigtypedef)
- `maxBatchSize`: `int`

Returns a `Coroutine` for
[CreateResolverResponseTypeDef](./type_defs.md#createresolverresponsetypedef).

<a id="create\_type"></a>

### create_type

Creates a `Type` object.

Type annotations for `session.create_client("appsync").create_type` method.

Boto3 documentation:
[AppSync.Client.create_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_type)

Asynchronous method. Use `await create_type(...)` for a synchronous call.

Arguments mapping described in
[CreateTypeRequestRequestTypeDef](./type_defs.md#createtyperequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `definition`: `str` *(required)*
- `format`: [TypeDefinitionFormatType](./literals.md#typedefinitionformattype)
  *(required)*

Returns a `Coroutine` for
[CreateTypeResponseTypeDef](./type_defs.md#createtyperesponsetypedef).

<a id="delete\_api\_cache"></a>

### delete_api_cache

Deletes an `ApiCache` object.

Type annotations for `session.create_client("appsync").delete_api_cache`
method.

Boto3 documentation:
[AppSync.Client.delete_api_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_api_cache)

Asynchronous method. Use `await delete_api_cache(...)` for a synchronous call.

Arguments mapping described in
[DeleteApiCacheRequestRequestTypeDef](./type_defs.md#deleteapicacherequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_api\_key"></a>

### delete_api_key

Deletes an API key.

Type annotations for `session.create_client("appsync").delete_api_key` method.

Boto3 documentation:
[AppSync.Client.delete_api_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_api_key)

Asynchronous method. Use `await delete_api_key(...)` for a synchronous call.

Arguments mapping described in
[DeleteApiKeyRequestRequestTypeDef](./type_defs.md#deleteapikeyrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_data\_source"></a>

### delete_data_source

Deletes a `DataSource` object.

Type annotations for `session.create_client("appsync").delete_data_source`
method.

Boto3 documentation:
[AppSync.Client.delete_data_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_data_source)

Asynchronous method. Use `await delete_data_source(...)` for a synchronous
call.

Arguments mapping described in
[DeleteDataSourceRequestRequestTypeDef](./type_defs.md#deletedatasourcerequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_domain\_name"></a>

### delete_domain_name

Deletes a custom `DomainName` object.

Type annotations for `session.create_client("appsync").delete_domain_name`
method.

Boto3 documentation:
[AppSync.Client.delete_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_domain_name)

Asynchronous method. Use `await delete_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[DeleteDomainNameRequestRequestTypeDef](./type_defs.md#deletedomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_function"></a>

### delete_function

Deletes a `Function` .

Type annotations for `session.create_client("appsync").delete_function` method.

Boto3 documentation:
[AppSync.Client.delete_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_function)

Asynchronous method. Use `await delete_function(...)` for a synchronous call.

Arguments mapping described in
[DeleteFunctionRequestRequestTypeDef](./type_defs.md#deletefunctionrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `functionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_graphql\_api"></a>

### delete_graphql_api

Deletes a `GraphqlApi` object.

Type annotations for `session.create_client("appsync").delete_graphql_api`
method.

Boto3 documentation:
[AppSync.Client.delete_graphql_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_graphql_api)

Asynchronous method. Use `await delete_graphql_api(...)` for a synchronous
call.

Arguments mapping described in
[DeleteGraphqlApiRequestRequestTypeDef](./type_defs.md#deletegraphqlapirequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_resolver"></a>

### delete_resolver

Deletes a `Resolver` object.

Type annotations for `session.create_client("appsync").delete_resolver` method.

Boto3 documentation:
[AppSync.Client.delete_resolver](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_resolver)

Asynchronous method. Use `await delete_resolver(...)` for a synchronous call.

Arguments mapping described in
[DeleteResolverRequestRequestTypeDef](./type_defs.md#deleteresolverrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `fieldName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_type"></a>

### delete_type

Deletes a `Type` object.

Type annotations for `session.create_client("appsync").delete_type` method.

Boto3 documentation:
[AppSync.Client.delete_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_type)

Asynchronous method. Use `await delete_type(...)` for a synchronous call.

Arguments mapping described in
[DeleteTypeRequestRequestTypeDef](./type_defs.md#deletetyperequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disassociate\_api"></a>

### disassociate_api

Removes an `ApiAssociation` object from a custom domain.

Type annotations for `session.create_client("appsync").disassociate_api`
method.

Boto3 documentation:
[AppSync.Client.disassociate_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.disassociate_api)

Asynchronous method. Use `await disassociate_api(...)` for a synchronous call.

Arguments mapping described in
[DisassociateApiRequestRequestTypeDef](./type_defs.md#disassociateapirequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="flush\_api\_cache"></a>

### flush_api_cache

Flushes an `ApiCache` object.

Type annotations for `session.create_client("appsync").flush_api_cache` method.

Boto3 documentation:
[AppSync.Client.flush_api_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.flush_api_cache)

Asynchronous method. Use `await flush_api_cache(...)` for a synchronous call.

Arguments mapping described in
[FlushApiCacheRequestRequestTypeDef](./type_defs.md#flushapicacherequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("appsync").generate_presigned_url`
method.

Boto3 documentation:
[AppSync.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_api\_association"></a>

### get_api_association

Retrieves an `ApiAssociation` object.

Type annotations for `session.create_client("appsync").get_api_association`
method.

Boto3 documentation:
[AppSync.Client.get_api_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_api_association)

Asynchronous method. Use `await get_api_association(...)` for a synchronous
call.

Arguments mapping described in
[GetApiAssociationRequestRequestTypeDef](./type_defs.md#getapiassociationrequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*

Returns a `Coroutine` for
[GetApiAssociationResponseTypeDef](./type_defs.md#getapiassociationresponsetypedef).

<a id="get\_api\_cache"></a>

### get_api_cache

Retrieves an `ApiCache` object.

Type annotations for `session.create_client("appsync").get_api_cache` method.

Boto3 documentation:
[AppSync.Client.get_api_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_api_cache)

Asynchronous method. Use `await get_api_cache(...)` for a synchronous call.

Arguments mapping described in
[GetApiCacheRequestRequestTypeDef](./type_defs.md#getapicacherequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*

Returns a `Coroutine` for
[GetApiCacheResponseTypeDef](./type_defs.md#getapicacheresponsetypedef).

<a id="get\_data\_source"></a>

### get_data_source

Retrieves a `DataSource` object.

Type annotations for `session.create_client("appsync").get_data_source` method.

Boto3 documentation:
[AppSync.Client.get_data_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_data_source)

Asynchronous method. Use `await get_data_source(...)` for a synchronous call.

Arguments mapping described in
[GetDataSourceRequestRequestTypeDef](./type_defs.md#getdatasourcerequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `name`: `str` *(required)*

Returns a `Coroutine` for
[GetDataSourceResponseTypeDef](./type_defs.md#getdatasourceresponsetypedef).

<a id="get\_domain\_name"></a>

### get_domain_name

Retrieves a custom `DomainName` object.

Type annotations for `session.create_client("appsync").get_domain_name` method.

Boto3 documentation:
[AppSync.Client.get_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_domain_name)

Asynchronous method. Use `await get_domain_name(...)` for a synchronous call.

Arguments mapping described in
[GetDomainNameRequestRequestTypeDef](./type_defs.md#getdomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*

Returns a `Coroutine` for
[GetDomainNameResponseTypeDef](./type_defs.md#getdomainnameresponsetypedef).

<a id="get\_function"></a>

### get_function

Get a `Function` .

Type annotations for `session.create_client("appsync").get_function` method.

Boto3 documentation:
[AppSync.Client.get_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_function)

Asynchronous method. Use `await get_function(...)` for a synchronous call.

Arguments mapping described in
[GetFunctionRequestRequestTypeDef](./type_defs.md#getfunctionrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `functionId`: `str` *(required)*

Returns a `Coroutine` for
[GetFunctionResponseTypeDef](./type_defs.md#getfunctionresponsetypedef).

<a id="get\_graphql\_api"></a>

### get_graphql_api

Retrieves a `GraphqlApi` object.

Type annotations for `session.create_client("appsync").get_graphql_api` method.

Boto3 documentation:
[AppSync.Client.get_graphql_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_graphql_api)

Asynchronous method. Use `await get_graphql_api(...)` for a synchronous call.

Arguments mapping described in
[GetGraphqlApiRequestRequestTypeDef](./type_defs.md#getgraphqlapirequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*

Returns a `Coroutine` for
[GetGraphqlApiResponseTypeDef](./type_defs.md#getgraphqlapiresponsetypedef).

<a id="get\_introspection\_schema"></a>

### get_introspection_schema

Retrieves the introspection schema for a GraphQL API.

Type annotations for
`session.create_client("appsync").get_introspection_schema` method.

Boto3 documentation:
[AppSync.Client.get_introspection_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_introspection_schema)

Asynchronous method. Use `await get_introspection_schema(...)` for a
synchronous call.

Arguments mapping described in
[GetIntrospectionSchemaRequestRequestTypeDef](./type_defs.md#getintrospectionschemarequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `format`: [OutputTypeType](./literals.md#outputtypetype) *(required)*
- `includeDirectives`: `bool`

Returns a `Coroutine` for
[GetIntrospectionSchemaResponseTypeDef](./type_defs.md#getintrospectionschemaresponsetypedef).

<a id="get\_resolver"></a>

### get_resolver

Retrieves a `Resolver` object.

Type annotations for `session.create_client("appsync").get_resolver` method.

Boto3 documentation:
[AppSync.Client.get_resolver](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_resolver)

Asynchronous method. Use `await get_resolver(...)` for a synchronous call.

Arguments mapping described in
[GetResolverRequestRequestTypeDef](./type_defs.md#getresolverrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `fieldName`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverResponseTypeDef](./type_defs.md#getresolverresponsetypedef).

<a id="get\_schema\_creation\_status"></a>

### get_schema_creation_status

Retrieves the current status of a schema creation operation.

Type annotations for
`session.create_client("appsync").get_schema_creation_status` method.

Boto3 documentation:
[AppSync.Client.get_schema_creation_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_schema_creation_status)

Asynchronous method. Use `await get_schema_creation_status(...)` for a
synchronous call.

Arguments mapping described in
[GetSchemaCreationStatusRequestRequestTypeDef](./type_defs.md#getschemacreationstatusrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*

Returns a `Coroutine` for
[GetSchemaCreationStatusResponseTypeDef](./type_defs.md#getschemacreationstatusresponsetypedef).

<a id="get\_type"></a>

### get_type

Retrieves a `Type` object.

Type annotations for `session.create_client("appsync").get_type` method.

Boto3 documentation:
[AppSync.Client.get_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_type)

Asynchronous method. Use `await get_type(...)` for a synchronous call.

Arguments mapping described in
[GetTypeRequestRequestTypeDef](./type_defs.md#gettyperequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `format`: [TypeDefinitionFormatType](./literals.md#typedefinitionformattype)
  *(required)*

Returns a `Coroutine` for
[GetTypeResponseTypeDef](./type_defs.md#gettyperesponsetypedef).

<a id="list\_api\_keys"></a>

### list_api_keys

Lists the API keys for a given API.

Type annotations for `session.create_client("appsync").list_api_keys` method.

Boto3 documentation:
[AppSync.Client.list_api_keys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_api_keys)

Asynchronous method. Use `await list_api_keys(...)` for a synchronous call.

Arguments mapping described in
[ListApiKeysRequestRequestTypeDef](./type_defs.md#listapikeysrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListApiKeysResponseTypeDef](./type_defs.md#listapikeysresponsetypedef).

<a id="list\_data\_sources"></a>

### list_data_sources

Lists the data sources for a given API.

Type annotations for `session.create_client("appsync").list_data_sources`
method.

Boto3 documentation:
[AppSync.Client.list_data_sources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_data_sources)

Asynchronous method. Use `await list_data_sources(...)` for a synchronous call.

Arguments mapping described in
[ListDataSourcesRequestRequestTypeDef](./type_defs.md#listdatasourcesrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListDataSourcesResponseTypeDef](./type_defs.md#listdatasourcesresponsetypedef).

<a id="list\_domain\_names"></a>

### list_domain_names

Lists multiple custom domain names.

Type annotations for `session.create_client("appsync").list_domain_names`
method.

Boto3 documentation:
[AppSync.Client.list_domain_names](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_domain_names)

Asynchronous method. Use `await list_domain_names(...)` for a synchronous call.

Arguments mapping described in
[ListDomainNamesRequestRequestTypeDef](./type_defs.md#listdomainnamesrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListDomainNamesResponseTypeDef](./type_defs.md#listdomainnamesresponsetypedef).

<a id="list\_functions"></a>

### list_functions

List multiple functions.

Type annotations for `session.create_client("appsync").list_functions` method.

Boto3 documentation:
[AppSync.Client.list_functions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_functions)

Asynchronous method. Use `await list_functions(...)` for a synchronous call.

Arguments mapping described in
[ListFunctionsRequestRequestTypeDef](./type_defs.md#listfunctionsrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListFunctionsResponseTypeDef](./type_defs.md#listfunctionsresponsetypedef).

<a id="list\_graphql\_apis"></a>

### list_graphql_apis

Lists your GraphQL APIs.

Type annotations for `session.create_client("appsync").list_graphql_apis`
method.

Boto3 documentation:
[AppSync.Client.list_graphql_apis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_graphql_apis)

Asynchronous method. Use `await list_graphql_apis(...)` for a synchronous call.

Arguments mapping described in
[ListGraphqlApisRequestRequestTypeDef](./type_defs.md#listgraphqlapisrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListGraphqlApisResponseTypeDef](./type_defs.md#listgraphqlapisresponsetypedef).

<a id="list\_resolvers"></a>

### list_resolvers

Lists the resolvers for a given API and type.

Type annotations for `session.create_client("appsync").list_resolvers` method.

Boto3 documentation:
[AppSync.Client.list_resolvers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_resolvers)

Asynchronous method. Use `await list_resolvers(...)` for a synchronous call.

Arguments mapping described in
[ListResolversRequestRequestTypeDef](./type_defs.md#listresolversrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListResolversResponseTypeDef](./type_defs.md#listresolversresponsetypedef).

<a id="list\_resolvers\_by\_function"></a>

### list_resolvers_by_function

List the resolvers that are associated with a specific function.

Type annotations for
`session.create_client("appsync").list_resolvers_by_function` method.

Boto3 documentation:
[AppSync.Client.list_resolvers_by_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_resolvers_by_function)

Asynchronous method. Use `await list_resolvers_by_function(...)` for a
synchronous call.

Arguments mapping described in
[ListResolversByFunctionRequestRequestTypeDef](./type_defs.md#listresolversbyfunctionrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `functionId`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListResolversByFunctionResponseTypeDef](./type_defs.md#listresolversbyfunctionresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Lists the tags for a resource.

Type annotations for `session.create_client("appsync").list_tags_for_resource`
method.

Boto3 documentation:
[AppSync.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list\_types"></a>

### list_types

Lists the types for a given API.

Type annotations for `session.create_client("appsync").list_types` method.

Boto3 documentation:
[AppSync.Client.list_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_types)

Asynchronous method. Use `await list_types(...)` for a synchronous call.

Arguments mapping described in
[ListTypesRequestRequestTypeDef](./type_defs.md#listtypesrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `format`: [TypeDefinitionFormatType](./literals.md#typedefinitionformattype)
  *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListTypesResponseTypeDef](./type_defs.md#listtypesresponsetypedef).

<a id="start\_schema\_creation"></a>

### start_schema_creation

Adds a new schema to your GraphQL API.

Type annotations for `session.create_client("appsync").start_schema_creation`
method.

Boto3 documentation:
[AppSync.Client.start_schema_creation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.start_schema_creation)

Asynchronous method. Use `await start_schema_creation(...)` for a synchronous
call.

Arguments mapping described in
[StartSchemaCreationRequestRequestTypeDef](./type_defs.md#startschemacreationrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `definition`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*

Returns a `Coroutine` for
[StartSchemaCreationResponseTypeDef](./type_defs.md#startschemacreationresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Tags a resource with user-supplied tags.

Type annotations for `session.create_client("appsync").tag_resource` method.

Boto3 documentation:
[AppSync.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Untags a resource.

Type annotations for `session.create_client("appsync").untag_resource` method.

Boto3 documentation:
[AppSync.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_api\_cache"></a>

### update_api_cache

Updates the cache for the GraphQL API.

Type annotations for `session.create_client("appsync").update_api_cache`
method.

Boto3 documentation:
[AppSync.Client.update_api_cache](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_api_cache)

Asynchronous method. Use `await update_api_cache(...)` for a synchronous call.

Arguments mapping described in
[UpdateApiCacheRequestRequestTypeDef](./type_defs.md#updateapicacherequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `ttl`: `int` *(required)*
- `apiCachingBehavior`:
  [ApiCachingBehaviorType](./literals.md#apicachingbehaviortype) *(required)*
- `type`: [ApiCacheTypeType](./literals.md#apicachetypetype) *(required)*

Returns a `Coroutine` for
[UpdateApiCacheResponseTypeDef](./type_defs.md#updateapicacheresponsetypedef).

<a id="update\_api\_key"></a>

### update_api_key

Updates an API key.

Type annotations for `session.create_client("appsync").update_api_key` method.

Boto3 documentation:
[AppSync.Client.update_api_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_api_key)

Asynchronous method. Use `await update_api_key(...)` for a synchronous call.

Arguments mapping described in
[UpdateApiKeyRequestRequestTypeDef](./type_defs.md#updateapikeyrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `id`: `str` *(required)*
- `description`: `str`
- `expires`: `int`

Returns a `Coroutine` for
[UpdateApiKeyResponseTypeDef](./type_defs.md#updateapikeyresponsetypedef).

<a id="update\_data\_source"></a>

### update_data_source

Updates a `DataSource` object.

Type annotations for `session.create_client("appsync").update_data_source`
method.

Boto3 documentation:
[AppSync.Client.update_data_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_data_source)

Asynchronous method. Use `await update_data_source(...)` for a synchronous
call.

Arguments mapping described in
[UpdateDataSourceRequestRequestTypeDef](./type_defs.md#updatedatasourcerequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `name`: `str` *(required)*
- `type`: [DataSourceTypeType](./literals.md#datasourcetypetype) *(required)*
- `description`: `str`
- `serviceRoleArn`: `str`
- `dynamodbConfig`:
  [DynamodbDataSourceConfigTypeDef](./type_defs.md#dynamodbdatasourceconfigtypedef)
- `lambdaConfig`:
  [LambdaDataSourceConfigTypeDef](./type_defs.md#lambdadatasourceconfigtypedef)
- `elasticsearchConfig`:
  [ElasticsearchDataSourceConfigTypeDef](./type_defs.md#elasticsearchdatasourceconfigtypedef)
- `openSearchServiceConfig`:
  [OpenSearchServiceDataSourceConfigTypeDef](./type_defs.md#opensearchservicedatasourceconfigtypedef)
- `httpConfig`:
  [HttpDataSourceConfigTypeDef](./type_defs.md#httpdatasourceconfigtypedef)
- `relationalDatabaseConfig`:
  [RelationalDatabaseDataSourceConfigTypeDef](./type_defs.md#relationaldatabasedatasourceconfigtypedef)

Returns a `Coroutine` for
[UpdateDataSourceResponseTypeDef](./type_defs.md#updatedatasourceresponsetypedef).

<a id="update\_domain\_name"></a>

### update_domain_name

Updates a custom `DomainName` object.

Type annotations for `session.create_client("appsync").update_domain_name`
method.

Boto3 documentation:
[AppSync.Client.update_domain_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_domain_name)

Asynchronous method. Use `await update_domain_name(...)` for a synchronous
call.

Arguments mapping described in
[UpdateDomainNameRequestRequestTypeDef](./type_defs.md#updatedomainnamerequestrequesttypedef).

Keyword-only arguments:

- `domainName`: `str` *(required)*
- `description`: `str`

Returns a `Coroutine` for
[UpdateDomainNameResponseTypeDef](./type_defs.md#updatedomainnameresponsetypedef).

<a id="update\_function"></a>

### update_function

Updates a `Function` object.

Type annotations for `session.create_client("appsync").update_function` method.

Boto3 documentation:
[AppSync.Client.update_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_function)

Asynchronous method. Use `await update_function(...)` for a synchronous call.

Arguments mapping described in
[UpdateFunctionRequestRequestTypeDef](./type_defs.md#updatefunctionrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `name`: `str` *(required)*
- `functionId`: `str` *(required)*
- `dataSourceName`: `str` *(required)*
- `functionVersion`: `str` *(required)*
- `description`: `str`
- `requestMappingTemplate`: `str`
- `responseMappingTemplate`: `str`
- `syncConfig`: [SyncConfigTypeDef](./type_defs.md#syncconfigtypedef)
- `maxBatchSize`: `int`

Returns a `Coroutine` for
[UpdateFunctionResponseTypeDef](./type_defs.md#updatefunctionresponsetypedef).

<a id="update\_graphql\_api"></a>

### update_graphql_api

Updates a `GraphqlApi` object.

Type annotations for `session.create_client("appsync").update_graphql_api`
method.

Boto3 documentation:
[AppSync.Client.update_graphql_api](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_graphql_api)

Asynchronous method. Use `await update_graphql_api(...)` for a synchronous
call.

Arguments mapping described in
[UpdateGraphqlApiRequestRequestTypeDef](./type_defs.md#updategraphqlapirequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `name`: `str` *(required)*
- `logConfig`: [LogConfigTypeDef](./type_defs.md#logconfigtypedef)
- `authenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)
- `userPoolConfig`:
  [UserPoolConfigTypeDef](./type_defs.md#userpoolconfigtypedef)
- `openIDConnectConfig`:
  [OpenIDConnectConfigTypeDef](./type_defs.md#openidconnectconfigtypedef)
- `additionalAuthenticationProviders`:
  `Sequence`\[[AdditionalAuthenticationProviderTypeDef](./type_defs.md#additionalauthenticationprovidertypedef)\]
- `xrayEnabled`: `bool`
- `lambdaAuthorizerConfig`:
  [LambdaAuthorizerConfigTypeDef](./type_defs.md#lambdaauthorizerconfigtypedef)

Returns a `Coroutine` for
[UpdateGraphqlApiResponseTypeDef](./type_defs.md#updategraphqlapiresponsetypedef).

<a id="update\_resolver"></a>

### update_resolver

Updates a `Resolver` object.

Type annotations for `session.create_client("appsync").update_resolver` method.

Boto3 documentation:
[AppSync.Client.update_resolver](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_resolver)

Asynchronous method. Use `await update_resolver(...)` for a synchronous call.

Arguments mapping described in
[UpdateResolverRequestRequestTypeDef](./type_defs.md#updateresolverrequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `fieldName`: `str` *(required)*
- `dataSourceName`: `str`
- `requestMappingTemplate`: `str`
- `responseMappingTemplate`: `str`
- `kind`: [ResolverKindType](./literals.md#resolverkindtype)
- `pipelineConfig`:
  [PipelineConfigTypeDef](./type_defs.md#pipelineconfigtypedef)
- `syncConfig`: [SyncConfigTypeDef](./type_defs.md#syncconfigtypedef)
- `cachingConfig`: [CachingConfigTypeDef](./type_defs.md#cachingconfigtypedef)
- `maxBatchSize`: `int`

Returns a `Coroutine` for
[UpdateResolverResponseTypeDef](./type_defs.md#updateresolverresponsetypedef).

<a id="update\_type"></a>

### update_type

Updates a `Type` object.

Type annotations for `session.create_client("appsync").update_type` method.

Boto3 documentation:
[AppSync.Client.update_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_type)

Asynchronous method. Use `await update_type(...)` for a synchronous call.

Arguments mapping described in
[UpdateTypeRequestRequestTypeDef](./type_defs.md#updatetyperequestrequesttypedef).

Keyword-only arguments:

- `apiId`: `str` *(required)*
- `typeName`: `str` *(required)*
- `format`: [TypeDefinitionFormatType](./literals.md#typedefinitionformattype)
  *(required)*
- `definition`: `str`

Returns a `Coroutine` for
[UpdateTypeResponseTypeDef](./type_defs.md#updatetyperesponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("appsync").__aenter__` method.

Boto3 documentation:
[AppSync.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [AppSyncClient](#appsyncclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("appsync").__aexit__` method.

Boto3 documentation:
[AppSync.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("appsync").get_paginator` method
with overloads.

- `client.get_paginator("list_api_keys")` ->
  [ListApiKeysPaginator](./paginators.md#listapikeyspaginator)
- `client.get_paginator("list_data_sources")` ->
  [ListDataSourcesPaginator](./paginators.md#listdatasourcespaginator)
- `client.get_paginator("list_functions")` ->
  [ListFunctionsPaginator](./paginators.md#listfunctionspaginator)
- `client.get_paginator("list_graphql_apis")` ->
  [ListGraphqlApisPaginator](./paginators.md#listgraphqlapispaginator)
- `client.get_paginator("list_resolvers")` ->
  [ListResolversPaginator](./paginators.md#listresolverspaginator)
- `client.get_paginator("list_resolvers_by_function")` ->
  [ListResolversByFunctionPaginator](./paginators.md#listresolversbyfunctionpaginator)
- `client.get_paginator("list_types")` ->
  [ListTypesPaginator](./paginators.md#listtypespaginator)
