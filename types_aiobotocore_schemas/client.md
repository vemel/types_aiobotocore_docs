<a id="schemasclient-for-aiobotocore-schemas-module"></a>

# SchemasClient for aiobotocore Schemas module

> [Index](..) > [Schemas](.) > SchemasClient

Auto-generated documentation for
[Schemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
type annotations stubs module
[types-aiobotocore-schemas](https://pypi.org/project/types-aiobotocore-schemas/).

- [SchemasClient for aiobotocore Schemas module](#schemasclient-for-aiobotocore-schemas-module)
  - [SchemasClient](#schemasclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_discoverer](#create_discoverer)
    - [create_registry](#create_registry)
    - [create_schema](#create_schema)
    - [delete_discoverer](#delete_discoverer)
    - [delete_registry](#delete_registry)
    - [delete_resource_policy](#delete_resource_policy)
    - [delete_schema](#delete_schema)
    - [delete_schema_version](#delete_schema_version)
    - [describe_code_binding](#describe_code_binding)
    - [describe_discoverer](#describe_discoverer)
    - [describe_registry](#describe_registry)
    - [describe_schema](#describe_schema)
    - [export_schema](#export_schema)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_code_binding_source](#get_code_binding_source)
    - [get_discovered_schema](#get_discovered_schema)
    - [get_resource_policy](#get_resource_policy)
    - [list_discoverers](#list_discoverers)
    - [list_registries](#list_registries)
    - [list_schema_versions](#list_schema_versions)
    - [list_schemas](#list_schemas)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_code_binding](#put_code_binding)
    - [put_resource_policy](#put_resource_policy)
    - [search_schemas](#search_schemas)
    - [start_discoverer](#start_discoverer)
    - [stop_discoverer](#stop_discoverer)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_discoverer](#update_discoverer)
    - [update_registry](#update_registry)
    - [update_schema](#update_schema)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="schemasclient"></a>

## SchemasClient

Type annotations for `aiobotocore.create_client("schemas")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_schemas.client import SchemasClient

def get_schemas_client() -> SchemasClient:
    return Session().client("schemas")
```

Boto3 documentation:
[Schemas.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_schemas.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.ForbiddenException`
- `Exceptions.GoneException`
- `Exceptions.InternalServerErrorException`
- `Exceptions.NotFoundException`
- `Exceptions.PreconditionFailedException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.TooManyRequestsException`
- `Exceptions.UnauthorizedException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

SchemasClient exceptions.

Type annotations for `aiobotocore.create_client("schemas").exceptions` method.

Boto3 documentation:
[Schemas.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("schemas").can_paginate`
method.

Boto3 documentation:
[Schemas.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_discoverer"></a>

### create_discoverer

Creates a discoverer.

Type annotations for `aiobotocore.create_client("schemas").create_discoverer`
method.

Boto3 documentation:
[Schemas.Client.create_discoverer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.create_discoverer)

Asynchronous method. Use `await create_discoverer(...)` for a synchronous call.

Arguments mapping described in
[CreateDiscovererRequestRequestTypeDef](./type_defs.md#creatediscovererrequestrequesttypedef).

Keyword-only arguments:

- `SourceArn`: `str` *(required)*
- `Description`: `str`
- `CrossAccount`: `bool`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateDiscovererResponseTypeDef](./type_defs.md#creatediscovererresponsetypedef).

<a id="create_registry"></a>

### create_registry

Creates a registry.

Type annotations for `aiobotocore.create_client("schemas").create_registry`
method.

Boto3 documentation:
[Schemas.Client.create_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.create_registry)

Asynchronous method. Use `await create_registry(...)` for a synchronous call.

Arguments mapping described in
[CreateRegistryRequestRequestTypeDef](./type_defs.md#createregistryrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateRegistryResponseTypeDef](./type_defs.md#createregistryresponsetypedef).

<a id="create_schema"></a>

### create_schema

Creates a schema definition.

Type annotations for `aiobotocore.create_client("schemas").create_schema`
method.

Boto3 documentation:
[Schemas.Client.create_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.create_schema)

Asynchronous method. Use `await create_schema(...)` for a synchronous call.

Arguments mapping described in
[CreateSchemaRequestRequestTypeDef](./type_defs.md#createschemarequestrequesttypedef).

Keyword-only arguments:

- `Content`: `str` *(required)*
- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `Type`: [TypeType](./literals.md#typetype) *(required)*
- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateSchemaResponseTypeDef](./type_defs.md#createschemaresponsetypedef).

<a id="delete_discoverer"></a>

### delete_discoverer

Deletes a discoverer.

Type annotations for `aiobotocore.create_client("schemas").delete_discoverer`
method.

Boto3 documentation:
[Schemas.Client.delete_discoverer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.delete_discoverer)

Asynchronous method. Use `await delete_discoverer(...)` for a synchronous call.

Arguments mapping described in
[DeleteDiscovererRequestRequestTypeDef](./type_defs.md#deletediscovererrequestrequesttypedef).

Keyword-only arguments:

- `DiscovererId`: `str` *(required)*

<a id="delete_registry"></a>

### delete_registry

Deletes a Registry.

Type annotations for `aiobotocore.create_client("schemas").delete_registry`
method.

Boto3 documentation:
[Schemas.Client.delete_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.delete_registry)

Asynchronous method. Use `await delete_registry(...)` for a synchronous call.

Arguments mapping described in
[DeleteRegistryRequestRequestTypeDef](./type_defs.md#deleteregistryrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*

<a id="delete_resource_policy"></a>

### delete_resource_policy

Delete the resource-based policy attached to the specified registry.

Type annotations for
`aiobotocore.create_client("schemas").delete_resource_policy` method.

Boto3 documentation:
[Schemas.Client.delete_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.delete_resource_policy)

Asynchronous method. Use `await delete_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResourcePolicyRequestRequestTypeDef](./type_defs.md#deleteresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str`

<a id="delete_schema"></a>

### delete_schema

Delete a schema definition.

Type annotations for `aiobotocore.create_client("schemas").delete_schema`
method.

Boto3 documentation:
[Schemas.Client.delete_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.delete_schema)

Asynchronous method. Use `await delete_schema(...)` for a synchronous call.

Arguments mapping described in
[DeleteSchemaRequestRequestTypeDef](./type_defs.md#deleteschemarequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*

<a id="delete_schema_version"></a>

### delete_schema_version

Delete the schema version definition See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/schemas-2019-12-02/DeleteSchemaVersion).

Type annotations for
`aiobotocore.create_client("schemas").delete_schema_version` method.

Boto3 documentation:
[Schemas.Client.delete_schema_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.delete_schema_version)

Asynchronous method. Use `await delete_schema_version(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSchemaVersionRequestRequestTypeDef](./type_defs.md#deleteschemaversionrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `SchemaVersion`: `str` *(required)*

<a id="describe_code_binding"></a>

### describe_code_binding

Describe the code binding URI.

Type annotations for
`aiobotocore.create_client("schemas").describe_code_binding` method.

Boto3 documentation:
[Schemas.Client.describe_code_binding](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.describe_code_binding)

Asynchronous method. Use `await describe_code_binding(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCodeBindingRequestRequestTypeDef](./type_defs.md#describecodebindingrequestrequesttypedef).

Keyword-only arguments:

- `Language`: `str` *(required)*
- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `SchemaVersion`: `str`

Returns a `Coroutine` for
[DescribeCodeBindingResponseTypeDef](./type_defs.md#describecodebindingresponsetypedef).

<a id="describe_discoverer"></a>

### describe_discoverer

Describes the discoverer.

Type annotations for `aiobotocore.create_client("schemas").describe_discoverer`
method.

Boto3 documentation:
[Schemas.Client.describe_discoverer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.describe_discoverer)

Asynchronous method. Use `await describe_discoverer(...)` for a synchronous
call.

Arguments mapping described in
[DescribeDiscovererRequestRequestTypeDef](./type_defs.md#describediscovererrequestrequesttypedef).

Keyword-only arguments:

- `DiscovererId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDiscovererResponseTypeDef](./type_defs.md#describediscovererresponsetypedef).

<a id="describe_registry"></a>

### describe_registry

Describes the registry.

Type annotations for `aiobotocore.create_client("schemas").describe_registry`
method.

Boto3 documentation:
[Schemas.Client.describe_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.describe_registry)

Asynchronous method. Use `await describe_registry(...)` for a synchronous call.

Arguments mapping described in
[DescribeRegistryRequestRequestTypeDef](./type_defs.md#describeregistryrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeRegistryResponseTypeDef](./type_defs.md#describeregistryresponsetypedef).

<a id="describe_schema"></a>

### describe_schema

Retrieve the schema definition.

Type annotations for `aiobotocore.create_client("schemas").describe_schema`
method.

Boto3 documentation:
[Schemas.Client.describe_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.describe_schema)

Asynchronous method. Use `await describe_schema(...)` for a synchronous call.

Arguments mapping described in
[DescribeSchemaRequestRequestTypeDef](./type_defs.md#describeschemarequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `SchemaVersion`: `str`

Returns a `Coroutine` for
[DescribeSchemaResponseTypeDef](./type_defs.md#describeschemaresponsetypedef).

<a id="export_schema"></a>

### export_schema

See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/schemas-2019-12-02/ExportSchema).

Type annotations for `aiobotocore.create_client("schemas").export_schema`
method.

Boto3 documentation:
[Schemas.Client.export_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.export_schema)

Asynchronous method. Use `await export_schema(...)` for a synchronous call.

Arguments mapping described in
[ExportSchemaRequestRequestTypeDef](./type_defs.md#exportschemarequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `Type`: `str` *(required)*
- `SchemaVersion`: `str`

Returns a `Coroutine` for
[ExportSchemaResponseTypeDef](./type_defs.md#exportschemaresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("schemas").generate_presigned_url` method.

Boto3 documentation:
[Schemas.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_code_binding_source"></a>

### get_code_binding_source

Get the code binding source URI.

Type annotations for
`aiobotocore.create_client("schemas").get_code_binding_source` method.

Boto3 documentation:
[Schemas.Client.get_code_binding_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.get_code_binding_source)

Asynchronous method. Use `await get_code_binding_source(...)` for a synchronous
call.

Arguments mapping described in
[GetCodeBindingSourceRequestRequestTypeDef](./type_defs.md#getcodebindingsourcerequestrequesttypedef).

Keyword-only arguments:

- `Language`: `str` *(required)*
- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `SchemaVersion`: `str`

Returns a `Coroutine` for
[GetCodeBindingSourceResponseTypeDef](./type_defs.md#getcodebindingsourceresponsetypedef).

<a id="get_discovered_schema"></a>

### get_discovered_schema

Get the discovered schema that was generated based on sampled events.

Type annotations for
`aiobotocore.create_client("schemas").get_discovered_schema` method.

Boto3 documentation:
[Schemas.Client.get_discovered_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.get_discovered_schema)

Asynchronous method. Use `await get_discovered_schema(...)` for a synchronous
call.

Arguments mapping described in
[GetDiscoveredSchemaRequestRequestTypeDef](./type_defs.md#getdiscoveredschemarequestrequesttypedef).

Keyword-only arguments:

- `Events`: `Sequence`\[`str`\] *(required)*
- `Type`: [TypeType](./literals.md#typetype) *(required)*

Returns a `Coroutine` for
[GetDiscoveredSchemaResponseTypeDef](./type_defs.md#getdiscoveredschemaresponsetypedef).

<a id="get_resource_policy"></a>

### get_resource_policy

Retrieves the resource-based policy attached to a given registry.

Type annotations for `aiobotocore.create_client("schemas").get_resource_policy`
method.

Boto3 documentation:
[Schemas.Client.get_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.get_resource_policy)

Asynchronous method. Use `await get_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetResourcePolicyRequestRequestTypeDef](./type_defs.md#getresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str`

Returns a `Coroutine` for
[GetResourcePolicyResponseTypeDef](./type_defs.md#getresourcepolicyresponsetypedef).

<a id="list_discoverers"></a>

### list_discoverers

List the discoverers.

Type annotations for `aiobotocore.create_client("schemas").list_discoverers`
method.

Boto3 documentation:
[Schemas.Client.list_discoverers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.list_discoverers)

Asynchronous method. Use `await list_discoverers(...)` for a synchronous call.

Arguments mapping described in
[ListDiscoverersRequestRequestTypeDef](./type_defs.md#listdiscoverersrequestrequesttypedef).

Keyword-only arguments:

- `DiscovererIdPrefix`: `str`
- `Limit`: `int`
- `NextToken`: `str`
- `SourceArnPrefix`: `str`

Returns a `Coroutine` for
[ListDiscoverersResponseTypeDef](./type_defs.md#listdiscoverersresponsetypedef).

<a id="list_registries"></a>

### list_registries

List the registries.

Type annotations for `aiobotocore.create_client("schemas").list_registries`
method.

Boto3 documentation:
[Schemas.Client.list_registries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.list_registries)

Asynchronous method. Use `await list_registries(...)` for a synchronous call.

Arguments mapping described in
[ListRegistriesRequestRequestTypeDef](./type_defs.md#listregistriesrequestrequesttypedef).

Keyword-only arguments:

- `Limit`: `int`
- `NextToken`: `str`
- `RegistryNamePrefix`: `str`
- `Scope`: `str`

Returns a `Coroutine` for
[ListRegistriesResponseTypeDef](./type_defs.md#listregistriesresponsetypedef).

<a id="list_schema_versions"></a>

### list_schema_versions

Provides a list of the schema versions and related information.

Type annotations for
`aiobotocore.create_client("schemas").list_schema_versions` method.

Boto3 documentation:
[Schemas.Client.list_schema_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.list_schema_versions)

Asynchronous method. Use `await list_schema_versions(...)` for a synchronous
call.

Arguments mapping described in
[ListSchemaVersionsRequestRequestTypeDef](./type_defs.md#listschemaversionsrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `Limit`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListSchemaVersionsResponseTypeDef](./type_defs.md#listschemaversionsresponsetypedef).

<a id="list_schemas"></a>

### list_schemas

List the schemas.

Type annotations for `aiobotocore.create_client("schemas").list_schemas`
method.

Boto3 documentation:
[Schemas.Client.list_schemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.list_schemas)

Asynchronous method. Use `await list_schemas(...)` for a synchronous call.

Arguments mapping described in
[ListSchemasRequestRequestTypeDef](./type_defs.md#listschemasrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `Limit`: `int`
- `NextToken`: `str`
- `SchemaNamePrefix`: `str`

Returns a `Coroutine` for
[ListSchemasResponseTypeDef](./type_defs.md#listschemasresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Get tags for resource.

Type annotations for
`aiobotocore.create_client("schemas").list_tags_for_resource` method.

Boto3 documentation:
[Schemas.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_code_binding"></a>

### put_code_binding

Put code binding URI See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/schemas-2019-12-02/PutCodeBinding).

Type annotations for `aiobotocore.create_client("schemas").put_code_binding`
method.

Boto3 documentation:
[Schemas.Client.put_code_binding](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.put_code_binding)

Asynchronous method. Use `await put_code_binding(...)` for a synchronous call.

Arguments mapping described in
[PutCodeBindingRequestRequestTypeDef](./type_defs.md#putcodebindingrequestrequesttypedef).

Keyword-only arguments:

- `Language`: `str` *(required)*
- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `SchemaVersion`: `str`

Returns a `Coroutine` for
[PutCodeBindingResponseTypeDef](./type_defs.md#putcodebindingresponsetypedef).

<a id="put_resource_policy"></a>

### put_resource_policy

The name of the policy.

Type annotations for `aiobotocore.create_client("schemas").put_resource_policy`
method.

Boto3 documentation:
[Schemas.Client.put_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.put_resource_policy)

Asynchronous method. Use `await put_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutResourcePolicyRequestRequestTypeDef](./type_defs.md#putresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `Policy`: `str` *(required)*
- `RegistryName`: `str`
- `RevisionId`: `str`

Returns a `Coroutine` for
[PutResourcePolicyResponseTypeDef](./type_defs.md#putresourcepolicyresponsetypedef).

<a id="search_schemas"></a>

### search_schemas

Search the schemas See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/schemas-2019-12-02/SearchSchemas).

Type annotations for `aiobotocore.create_client("schemas").search_schemas`
method.

Boto3 documentation:
[Schemas.Client.search_schemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.search_schemas)

Asynchronous method. Use `await search_schemas(...)` for a synchronous call.

Arguments mapping described in
[SearchSchemasRequestRequestTypeDef](./type_defs.md#searchschemasrequestrequesttypedef).

Keyword-only arguments:

- `Keywords`: `str` *(required)*
- `RegistryName`: `str` *(required)*
- `Limit`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[SearchSchemasResponseTypeDef](./type_defs.md#searchschemasresponsetypedef).

<a id="start_discoverer"></a>

### start_discoverer

Starts the discoverer See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/schemas-2019-12-02/StartDiscoverer).

Type annotations for `aiobotocore.create_client("schemas").start_discoverer`
method.

Boto3 documentation:
[Schemas.Client.start_discoverer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.start_discoverer)

Asynchronous method. Use `await start_discoverer(...)` for a synchronous call.

Arguments mapping described in
[StartDiscovererRequestRequestTypeDef](./type_defs.md#startdiscovererrequestrequesttypedef).

Keyword-only arguments:

- `DiscovererId`: `str` *(required)*

Returns a `Coroutine` for
[StartDiscovererResponseTypeDef](./type_defs.md#startdiscovererresponsetypedef).

<a id="stop_discoverer"></a>

### stop_discoverer

Stops the discoverer See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/schemas-2019-12-02/StopDiscoverer).

Type annotations for `aiobotocore.create_client("schemas").stop_discoverer`
method.

Boto3 documentation:
[Schemas.Client.stop_discoverer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.stop_discoverer)

Asynchronous method. Use `await stop_discoverer(...)` for a synchronous call.

Arguments mapping described in
[StopDiscovererRequestRequestTypeDef](./type_defs.md#stopdiscovererrequestrequesttypedef).

Keyword-only arguments:

- `DiscovererId`: `str` *(required)*

Returns a `Coroutine` for
[StopDiscovererResponseTypeDef](./type_defs.md#stopdiscovererresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Add tags to a resource.

Type annotations for `aiobotocore.create_client("schemas").tag_resource`
method.

Boto3 documentation:
[Schemas.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="untag_resource"></a>

### untag_resource

Removes tags from a resource.

Type annotations for `aiobotocore.create_client("schemas").untag_resource`
method.

Boto3 documentation:
[Schemas.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update_discoverer"></a>

### update_discoverer

Updates the discoverer See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/schemas-2019-12-02/UpdateDiscoverer).

Type annotations for `aiobotocore.create_client("schemas").update_discoverer`
method.

Boto3 documentation:
[Schemas.Client.update_discoverer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.update_discoverer)

Asynchronous method. Use `await update_discoverer(...)` for a synchronous call.

Arguments mapping described in
[UpdateDiscovererRequestRequestTypeDef](./type_defs.md#updatediscovererrequestrequesttypedef).

Keyword-only arguments:

- `DiscovererId`: `str` *(required)*
- `Description`: `str`
- `CrossAccount`: `bool`

Returns a `Coroutine` for
[UpdateDiscovererResponseTypeDef](./type_defs.md#updatediscovererresponsetypedef).

<a id="update_registry"></a>

### update_registry

Updates a registry.

Type annotations for `aiobotocore.create_client("schemas").update_registry`
method.

Boto3 documentation:
[Schemas.Client.update_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.update_registry)

Asynchronous method. Use `await update_registry(...)` for a synchronous call.

Arguments mapping described in
[UpdateRegistryRequestRequestTypeDef](./type_defs.md#updateregistryrequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `Description`: `str`

Returns a `Coroutine` for
[UpdateRegistryResponseTypeDef](./type_defs.md#updateregistryresponsetypedef).

<a id="update_schema"></a>

### update_schema

Updates the schema definition .

Type annotations for `aiobotocore.create_client("schemas").update_schema`
method.

Boto3 documentation:
[Schemas.Client.update_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Client.update_schema)

Asynchronous method. Use `await update_schema(...)` for a synchronous call.

Arguments mapping described in
[UpdateSchemaRequestRequestTypeDef](./type_defs.md#updateschemarequestrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `SchemaName`: `str` *(required)*
- `ClientTokenId`: `str`
- `Content`: `str`
- `Description`: `str`
- `Type`: [TypeType](./literals.md#typetype)

Returns a `Coroutine` for
[UpdateSchemaResponseTypeDef](./type_defs.md#updateschemaresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("schemas").get_paginator`
method with overloads.

- `client.get_paginator("list_discoverers")` ->
  [ListDiscoverersPaginator](./paginators.md#listdiscovererspaginator)
- `client.get_paginator("list_registries")` ->
  [ListRegistriesPaginator](./paginators.md#listregistriespaginator)
- `client.get_paginator("list_schema_versions")` ->
  [ListSchemaVersionsPaginator](./paginators.md#listschemaversionspaginator)
- `client.get_paginator("list_schemas")` ->
  [ListSchemasPaginator](./paginators.md#listschemaspaginator)
- `client.get_paginator("search_schemas")` ->
  [SearchSchemasPaginator](./paginators.md#searchschemaspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `aiobotocore.create_client("schemas").get_waiter` method
with overloads.

- `client.get_waiter("code_binding_exists")` ->
  [CodeBindingExistsWaiter](./waiters.md#codebindingexistswaiter)
