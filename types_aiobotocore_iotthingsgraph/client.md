<a id="iotthingsgraphclient-for-aiobotocore-iotthingsgraph-module"></a>

# IoTThingsGraphClient for aiobotocore IoTThingsGraph module

> [Index](..) > [IoTThingsGraph](.) > IoTThingsGraphClient

Auto-generated documentation for
[IoTThingsGraph](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph)
type annotations stubs module
[types-aiobotocore-iotthingsgraph](https://pypi.org/project/types-aiobotocore-iotthingsgraph/).

- [IoTThingsGraphClient for aiobotocore IoTThingsGraph module](#iotthingsgraphclient-for-aiobotocore-iotthingsgraph-module)
  - [IoTThingsGraphClient](#iotthingsgraphclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_entity_to_thing](#associate_entity_to_thing)
    - [can_paginate](#can_paginate)
    - [create_flow_template](#create_flow_template)
    - [create_system_instance](#create_system_instance)
    - [create_system_template](#create_system_template)
    - [delete_flow_template](#delete_flow_template)
    - [delete_namespace](#delete_namespace)
    - [delete_system_instance](#delete_system_instance)
    - [delete_system_template](#delete_system_template)
    - [deploy_system_instance](#deploy_system_instance)
    - [deprecate_flow_template](#deprecate_flow_template)
    - [deprecate_system_template](#deprecate_system_template)
    - [describe_namespace](#describe_namespace)
    - [dissociate_entity_from_thing](#dissociate_entity_from_thing)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_entities](#get_entities)
    - [get_flow_template](#get_flow_template)
    - [get_flow_template_revisions](#get_flow_template_revisions)
    - [get_namespace_deletion_status](#get_namespace_deletion_status)
    - [get_system_instance](#get_system_instance)
    - [get_system_template](#get_system_template)
    - [get_system_template_revisions](#get_system_template_revisions)
    - [get_upload_status](#get_upload_status)
    - [list_flow_execution_messages](#list_flow_execution_messages)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [search_entities](#search_entities)
    - [search_flow_executions](#search_flow_executions)
    - [search_flow_templates](#search_flow_templates)
    - [search_system_instances](#search_system_instances)
    - [search_system_templates](#search_system_templates)
    - [search_things](#search_things)
    - [tag_resource](#tag_resource)
    - [undeploy_system_instance](#undeploy_system_instance)
    - [untag_resource](#untag_resource)
    - [update_flow_template](#update_flow_template)
    - [update_system_template](#update_system_template)
    - [upload_entity_definitions](#upload_entity_definitions)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="iotthingsgraphclient"></a>

## IoTThingsGraphClient

Type annotations for `session.create_client("iotthingsgraph")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_iotthingsgraph.client import IoTThingsGraphClient

session = get_session()
async with session.create_client("iotthingsgraph") as client:
    client: IoTThingsGraphClient
```

Boto3 documentation:
[IoTThingsGraph.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_iotthingsgraph.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InternalFailureException`
- `Exceptions.InvalidRequestException`
- `Exceptions.LimitExceededException`
- `Exceptions.ResourceAlreadyExistsException`
- `Exceptions.ResourceInUseException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ThrottlingException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

IoTThingsGraphClient exceptions.

Type annotations for `session.create_client("iotthingsgraph").exceptions`
method.

Boto3 documentation:
[IoTThingsGraph.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate_entity_to_thing"></a>

### associate_entity_to_thing

Associates a device with a concrete thing that is in the user's registry.

Type annotations for
`session.create_client("iotthingsgraph").associate_entity_to_thing` method.

Boto3 documentation:
[IoTThingsGraph.Client.associate_entity_to_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.associate_entity_to_thing)

Asynchronous method. Use `await associate_entity_to_thing(...)` for a
synchronous call.

Arguments mapping described in
[AssociateEntityToThingRequestRequestTypeDef](./type_defs.md#associateentitytothingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `entityId`: `str` *(required)*
- `namespaceVersion`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("iotthingsgraph").can_paginate`
method.

Boto3 documentation:
[IoTThingsGraph.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_flow_template"></a>

### create_flow_template

Creates a workflow template.

Type annotations for
`session.create_client("iotthingsgraph").create_flow_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.create_flow_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.create_flow_template)

Asynchronous method. Use `await create_flow_template(...)` for a synchronous
call.

Arguments mapping described in
[CreateFlowTemplateRequestRequestTypeDef](./type_defs.md#createflowtemplaterequestrequesttypedef).

Keyword-only arguments:

- `definition`:
  [DefinitionDocumentTypeDef](./type_defs.md#definitiondocumenttypedef)
  *(required)*
- `compatibleNamespaceVersion`: `int`

Returns a `Coroutine` for
[CreateFlowTemplateResponseTypeDef](./type_defs.md#createflowtemplateresponsetypedef).

<a id="create_system_instance"></a>

### create_system_instance

Creates a system instance.

Type annotations for
`session.create_client("iotthingsgraph").create_system_instance` method.

Boto3 documentation:
[IoTThingsGraph.Client.create_system_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.create_system_instance)

Asynchronous method. Use `await create_system_instance(...)` for a synchronous
call.

Arguments mapping described in
[CreateSystemInstanceRequestRequestTypeDef](./type_defs.md#createsysteminstancerequestrequesttypedef).

Keyword-only arguments:

- `definition`:
  [DefinitionDocumentTypeDef](./type_defs.md#definitiondocumenttypedef)
  *(required)*
- `target`: [DeploymentTargetType](./literals.md#deploymenttargettype)
  *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `greengrassGroupName`: `str`
- `s3BucketName`: `str`
- `metricsConfiguration`:
  [MetricsConfigurationTypeDef](./type_defs.md#metricsconfigurationtypedef)
- `flowActionsRoleArn`: `str`

Returns a `Coroutine` for
[CreateSystemInstanceResponseTypeDef](./type_defs.md#createsysteminstanceresponsetypedef).

<a id="create_system_template"></a>

### create_system_template

Creates a system.

Type annotations for
`session.create_client("iotthingsgraph").create_system_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.create_system_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.create_system_template)

Asynchronous method. Use `await create_system_template(...)` for a synchronous
call.

Arguments mapping described in
[CreateSystemTemplateRequestRequestTypeDef](./type_defs.md#createsystemtemplaterequestrequesttypedef).

Keyword-only arguments:

- `definition`:
  [DefinitionDocumentTypeDef](./type_defs.md#definitiondocumenttypedef)
  *(required)*
- `compatibleNamespaceVersion`: `int`

Returns a `Coroutine` for
[CreateSystemTemplateResponseTypeDef](./type_defs.md#createsystemtemplateresponsetypedef).

<a id="delete_flow_template"></a>

### delete_flow_template

Deletes a workflow.

Type annotations for
`session.create_client("iotthingsgraph").delete_flow_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.delete_flow_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.delete_flow_template)

Asynchronous method. Use `await delete_flow_template(...)` for a synchronous
call.

Arguments mapping described in
[DeleteFlowTemplateRequestRequestTypeDef](./type_defs.md#deleteflowtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_namespace"></a>

### delete_namespace

Deletes the specified namespace.

Type annotations for `session.create_client("iotthingsgraph").delete_namespace`
method.

Boto3 documentation:
[IoTThingsGraph.Client.delete_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.delete_namespace)

Asynchronous method. Use `await delete_namespace(...)` for a synchronous call.

Returns a `Coroutine` for
[DeleteNamespaceResponseTypeDef](./type_defs.md#deletenamespaceresponsetypedef).

<a id="delete_system_instance"></a>

### delete_system_instance

Deletes a system instance.

Type annotations for
`session.create_client("iotthingsgraph").delete_system_instance` method.

Boto3 documentation:
[IoTThingsGraph.Client.delete_system_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.delete_system_instance)

Asynchronous method. Use `await delete_system_instance(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSystemInstanceRequestRequestTypeDef](./type_defs.md#deletesysteminstancerequestrequesttypedef).

Keyword-only arguments:

- `id`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_system_template"></a>

### delete_system_template

Deletes a system.

Type annotations for
`session.create_client("iotthingsgraph").delete_system_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.delete_system_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.delete_system_template)

Asynchronous method. Use `await delete_system_template(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSystemTemplateRequestRequestTypeDef](./type_defs.md#deletesystemtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deploy_system_instance"></a>

### deploy_system_instance

**Greengrass and Cloud Deployments** Deploys the system instance to the target
specified in `CreateSystemInstance` .

Type annotations for
`session.create_client("iotthingsgraph").deploy_system_instance` method.

Boto3 documentation:
[IoTThingsGraph.Client.deploy_system_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.deploy_system_instance)

Asynchronous method. Use `await deploy_system_instance(...)` for a synchronous
call.

Arguments mapping described in
[DeploySystemInstanceRequestRequestTypeDef](./type_defs.md#deploysysteminstancerequestrequesttypedef).

Keyword-only arguments:

- `id`: `str`

Returns a `Coroutine` for
[DeploySystemInstanceResponseTypeDef](./type_defs.md#deploysysteminstanceresponsetypedef).

<a id="deprecate_flow_template"></a>

### deprecate_flow_template

Deprecates the specified workflow.

Type annotations for
`session.create_client("iotthingsgraph").deprecate_flow_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.deprecate_flow_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.deprecate_flow_template)

Asynchronous method. Use `await deprecate_flow_template(...)` for a synchronous
call.

Arguments mapping described in
[DeprecateFlowTemplateRequestRequestTypeDef](./type_defs.md#deprecateflowtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deprecate_system_template"></a>

### deprecate_system_template

Deprecates the specified system.

Type annotations for
`session.create_client("iotthingsgraph").deprecate_system_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.deprecate_system_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.deprecate_system_template)

Asynchronous method. Use `await deprecate_system_template(...)` for a
synchronous call.

Arguments mapping described in
[DeprecateSystemTemplateRequestRequestTypeDef](./type_defs.md#deprecatesystemtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_namespace"></a>

### describe_namespace

Gets the latest version of the user's namespace and the public version that it
is tracking.

Type annotations for
`session.create_client("iotthingsgraph").describe_namespace` method.

Boto3 documentation:
[IoTThingsGraph.Client.describe_namespace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.describe_namespace)

Asynchronous method. Use `await describe_namespace(...)` for a synchronous
call.

Arguments mapping described in
[DescribeNamespaceRequestRequestTypeDef](./type_defs.md#describenamespacerequestrequesttypedef).

Keyword-only arguments:

- `namespaceName`: `str`

Returns a `Coroutine` for
[DescribeNamespaceResponseTypeDef](./type_defs.md#describenamespaceresponsetypedef).

<a id="dissociate_entity_from_thing"></a>

### dissociate_entity_from_thing

Dissociates a device entity from a concrete thing.

Type annotations for
`session.create_client("iotthingsgraph").dissociate_entity_from_thing` method.

Boto3 documentation:
[IoTThingsGraph.Client.dissociate_entity_from_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.dissociate_entity_from_thing)

Asynchronous method. Use `await dissociate_entity_from_thing(...)` for a
synchronous call.

Arguments mapping described in
[DissociateEntityFromThingRequestRequestTypeDef](./type_defs.md#dissociateentityfromthingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `entityType`: [EntityTypeType](./literals.md#entitytypetype) *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("iotthingsgraph").generate_presigned_url` method.

Boto3 documentation:
[IoTThingsGraph.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_entities"></a>

### get_entities

Gets definitions of the specified entities.

Type annotations for `session.create_client("iotthingsgraph").get_entities`
method.

Boto3 documentation:
[IoTThingsGraph.Client.get_entities](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_entities)

Asynchronous method. Use `await get_entities(...)` for a synchronous call.

Arguments mapping described in
[GetEntitiesRequestRequestTypeDef](./type_defs.md#getentitiesrequestrequesttypedef).

Keyword-only arguments:

- `ids`: `Sequence`\[`str`\] *(required)*
- `namespaceVersion`: `int`

Returns a `Coroutine` for
[GetEntitiesResponseTypeDef](./type_defs.md#getentitiesresponsetypedef).

<a id="get_flow_template"></a>

### get_flow_template

Gets the latest version of the `DefinitionDocument` and `FlowTemplateSummary`
for the specified workflow.

Type annotations for
`session.create_client("iotthingsgraph").get_flow_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.get_flow_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_flow_template)

Asynchronous method. Use `await get_flow_template(...)` for a synchronous call.

Arguments mapping described in
[GetFlowTemplateRequestRequestTypeDef](./type_defs.md#getflowtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `revisionNumber`: `int`

Returns a `Coroutine` for
[GetFlowTemplateResponseTypeDef](./type_defs.md#getflowtemplateresponsetypedef).

<a id="get_flow_template_revisions"></a>

### get_flow_template_revisions

Gets revisions of the specified workflow.

Type annotations for
`session.create_client("iotthingsgraph").get_flow_template_revisions` method.

Boto3 documentation:
[IoTThingsGraph.Client.get_flow_template_revisions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_flow_template_revisions)

Asynchronous method. Use `await get_flow_template_revisions(...)` for a
synchronous call.

Arguments mapping described in
[GetFlowTemplateRevisionsRequestRequestTypeDef](./type_defs.md#getflowtemplaterevisionsrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetFlowTemplateRevisionsResponseTypeDef](./type_defs.md#getflowtemplaterevisionsresponsetypedef).

<a id="get_namespace_deletion_status"></a>

### get_namespace_deletion_status

Gets the status of a namespace deletion task.

Type annotations for
`session.create_client("iotthingsgraph").get_namespace_deletion_status` method.

Boto3 documentation:
[IoTThingsGraph.Client.get_namespace_deletion_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_namespace_deletion_status)

Asynchronous method. Use `await get_namespace_deletion_status(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetNamespaceDeletionStatusResponseTypeDef](./type_defs.md#getnamespacedeletionstatusresponsetypedef).

<a id="get_system_instance"></a>

### get_system_instance

Gets a system instance.

Type annotations for
`session.create_client("iotthingsgraph").get_system_instance` method.

Boto3 documentation:
[IoTThingsGraph.Client.get_system_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_system_instance)

Asynchronous method. Use `await get_system_instance(...)` for a synchronous
call.

Arguments mapping described in
[GetSystemInstanceRequestRequestTypeDef](./type_defs.md#getsysteminstancerequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetSystemInstanceResponseTypeDef](./type_defs.md#getsysteminstanceresponsetypedef).

<a id="get_system_template"></a>

### get_system_template

Gets a system.

Type annotations for
`session.create_client("iotthingsgraph").get_system_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.get_system_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_system_template)

Asynchronous method. Use `await get_system_template(...)` for a synchronous
call.

Arguments mapping described in
[GetSystemTemplateRequestRequestTypeDef](./type_defs.md#getsystemtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `revisionNumber`: `int`

Returns a `Coroutine` for
[GetSystemTemplateResponseTypeDef](./type_defs.md#getsystemtemplateresponsetypedef).

<a id="get_system_template_revisions"></a>

### get_system_template_revisions

Gets revisions made to the specified system template.

Type annotations for
`session.create_client("iotthingsgraph").get_system_template_revisions` method.

Boto3 documentation:
[IoTThingsGraph.Client.get_system_template_revisions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_system_template_revisions)

Asynchronous method. Use `await get_system_template_revisions(...)` for a
synchronous call.

Arguments mapping described in
[GetSystemTemplateRevisionsRequestRequestTypeDef](./type_defs.md#getsystemtemplaterevisionsrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetSystemTemplateRevisionsResponseTypeDef](./type_defs.md#getsystemtemplaterevisionsresponsetypedef).

<a id="get_upload_status"></a>

### get_upload_status

Gets the status of the specified upload.

Type annotations for
`session.create_client("iotthingsgraph").get_upload_status` method.

Boto3 documentation:
[IoTThingsGraph.Client.get_upload_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.get_upload_status)

Asynchronous method. Use `await get_upload_status(...)` for a synchronous call.

Arguments mapping described in
[GetUploadStatusRequestRequestTypeDef](./type_defs.md#getuploadstatusrequestrequesttypedef).

Keyword-only arguments:

- `uploadId`: `str` *(required)*

Returns a `Coroutine` for
[GetUploadStatusResponseTypeDef](./type_defs.md#getuploadstatusresponsetypedef).

<a id="list_flow_execution_messages"></a>

### list_flow_execution_messages

Returns a list of objects that contain information about events in a flow
execution.

Type annotations for
`session.create_client("iotthingsgraph").list_flow_execution_messages` method.

Boto3 documentation:
[IoTThingsGraph.Client.list_flow_execution_messages](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.list_flow_execution_messages)

Asynchronous method. Use `await list_flow_execution_messages(...)` for a
synchronous call.

Arguments mapping described in
[ListFlowExecutionMessagesRequestRequestTypeDef](./type_defs.md#listflowexecutionmessagesrequestrequesttypedef).

Keyword-only arguments:

- `flowExecutionId`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListFlowExecutionMessagesResponseTypeDef](./type_defs.md#listflowexecutionmessagesresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists all tags on an AWS IoT Things Graph resource.

Type annotations for
`session.create_client("iotthingsgraph").list_tags_for_resource` method.

Boto3 documentation:
[IoTThingsGraph.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="search_entities"></a>

### search_entities

Searches for entities of the specified type.

Type annotations for `session.create_client("iotthingsgraph").search_entities`
method.

Boto3 documentation:
[IoTThingsGraph.Client.search_entities](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.search_entities)

Asynchronous method. Use `await search_entities(...)` for a synchronous call.

Arguments mapping described in
[SearchEntitiesRequestRequestTypeDef](./type_defs.md#searchentitiesrequestrequesttypedef).

Keyword-only arguments:

- `entityTypes`: `Sequence`\[[EntityTypeType](./literals.md#entitytypetype)\]
  *(required)*
- `filters`:
  `Sequence`\[[EntityFilterTypeDef](./type_defs.md#entityfiltertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`
- `namespaceVersion`: `int`

Returns a `Coroutine` for
[SearchEntitiesResponseTypeDef](./type_defs.md#searchentitiesresponsetypedef).

<a id="search_flow_executions"></a>

### search_flow_executions

Searches for AWS IoT Things Graph workflow execution instances.

Type annotations for
`session.create_client("iotthingsgraph").search_flow_executions` method.

Boto3 documentation:
[IoTThingsGraph.Client.search_flow_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.search_flow_executions)

Asynchronous method. Use `await search_flow_executions(...)` for a synchronous
call.

Arguments mapping described in
[SearchFlowExecutionsRequestRequestTypeDef](./type_defs.md#searchflowexecutionsrequestrequesttypedef).

Keyword-only arguments:

- `systemInstanceId`: `str` *(required)*
- `flowExecutionId`: `str`
- `startTime`: `Union`\[`datetime`, `str`\]
- `endTime`: `Union`\[`datetime`, `str`\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[SearchFlowExecutionsResponseTypeDef](./type_defs.md#searchflowexecutionsresponsetypedef).

<a id="search_flow_templates"></a>

### search_flow_templates

Searches for summary information about workflows.

Type annotations for
`session.create_client("iotthingsgraph").search_flow_templates` method.

Boto3 documentation:
[IoTThingsGraph.Client.search_flow_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.search_flow_templates)

Asynchronous method. Use `await search_flow_templates(...)` for a synchronous
call.

Arguments mapping described in
[SearchFlowTemplatesRequestRequestTypeDef](./type_defs.md#searchflowtemplatesrequestrequesttypedef).

Keyword-only arguments:

- `filters`:
  `Sequence`\[[FlowTemplateFilterTypeDef](./type_defs.md#flowtemplatefiltertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[SearchFlowTemplatesResponseTypeDef](./type_defs.md#searchflowtemplatesresponsetypedef).

<a id="search_system_instances"></a>

### search_system_instances

Searches for system instances in the user's account.

Type annotations for
`session.create_client("iotthingsgraph").search_system_instances` method.

Boto3 documentation:
[IoTThingsGraph.Client.search_system_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.search_system_instances)

Asynchronous method. Use `await search_system_instances(...)` for a synchronous
call.

Arguments mapping described in
[SearchSystemInstancesRequestRequestTypeDef](./type_defs.md#searchsysteminstancesrequestrequesttypedef).

Keyword-only arguments:

- `filters`:
  `Sequence`\[[SystemInstanceFilterTypeDef](./type_defs.md#systeminstancefiltertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[SearchSystemInstancesResponseTypeDef](./type_defs.md#searchsysteminstancesresponsetypedef).

<a id="search_system_templates"></a>

### search_system_templates

Searches for summary information about systems in the user's account.

Type annotations for
`session.create_client("iotthingsgraph").search_system_templates` method.

Boto3 documentation:
[IoTThingsGraph.Client.search_system_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.search_system_templates)

Asynchronous method. Use `await search_system_templates(...)` for a synchronous
call.

Arguments mapping described in
[SearchSystemTemplatesRequestRequestTypeDef](./type_defs.md#searchsystemtemplatesrequestrequesttypedef).

Keyword-only arguments:

- `filters`:
  `Sequence`\[[SystemTemplateFilterTypeDef](./type_defs.md#systemtemplatefiltertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[SearchSystemTemplatesResponseTypeDef](./type_defs.md#searchsystemtemplatesresponsetypedef).

<a id="search_things"></a>

### search_things

Searches for things associated with the specified entity.

Type annotations for `session.create_client("iotthingsgraph").search_things`
method.

Boto3 documentation:
[IoTThingsGraph.Client.search_things](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.search_things)

Asynchronous method. Use `await search_things(...)` for a synchronous call.

Arguments mapping described in
[SearchThingsRequestRequestTypeDef](./type_defs.md#searchthingsrequestrequesttypedef).

Keyword-only arguments:

- `entityId`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`
- `namespaceVersion`: `int`

Returns a `Coroutine` for
[SearchThingsResponseTypeDef](./type_defs.md#searchthingsresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Creates a tag for the specified resource.

Type annotations for `session.create_client("iotthingsgraph").tag_resource`
method.

Boto3 documentation:
[IoTThingsGraph.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="undeploy_system_instance"></a>

### undeploy_system_instance

Removes a system instance from its target (Cloud or Greengrass).

Type annotations for
`session.create_client("iotthingsgraph").undeploy_system_instance` method.

Boto3 documentation:
[IoTThingsGraph.Client.undeploy_system_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.undeploy_system_instance)

Asynchronous method. Use `await undeploy_system_instance(...)` for a
synchronous call.

Arguments mapping described in
[UndeploySystemInstanceRequestRequestTypeDef](./type_defs.md#undeploysysteminstancerequestrequesttypedef).

Keyword-only arguments:

- `id`: `str`

Returns a `Coroutine` for
[UndeploySystemInstanceResponseTypeDef](./type_defs.md#undeploysysteminstanceresponsetypedef).

<a id="untag_resource"></a>

### untag_resource

Removes a tag from the specified resource.

Type annotations for `session.create_client("iotthingsgraph").untag_resource`
method.

Boto3 documentation:
[IoTThingsGraph.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_flow_template"></a>

### update_flow_template

Updates the specified workflow.

Type annotations for
`session.create_client("iotthingsgraph").update_flow_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.update_flow_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.update_flow_template)

Asynchronous method. Use `await update_flow_template(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFlowTemplateRequestRequestTypeDef](./type_defs.md#updateflowtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `definition`:
  [DefinitionDocumentTypeDef](./type_defs.md#definitiondocumenttypedef)
  *(required)*
- `compatibleNamespaceVersion`: `int`

Returns a `Coroutine` for
[UpdateFlowTemplateResponseTypeDef](./type_defs.md#updateflowtemplateresponsetypedef).

<a id="update_system_template"></a>

### update_system_template

Updates the specified system.

Type annotations for
`session.create_client("iotthingsgraph").update_system_template` method.

Boto3 documentation:
[IoTThingsGraph.Client.update_system_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.update_system_template)

Asynchronous method. Use `await update_system_template(...)` for a synchronous
call.

Arguments mapping described in
[UpdateSystemTemplateRequestRequestTypeDef](./type_defs.md#updatesystemtemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `definition`:
  [DefinitionDocumentTypeDef](./type_defs.md#definitiondocumenttypedef)
  *(required)*
- `compatibleNamespaceVersion`: `int`

Returns a `Coroutine` for
[UpdateSystemTemplateResponseTypeDef](./type_defs.md#updatesystemtemplateresponsetypedef).

<a id="upload_entity_definitions"></a>

### upload_entity_definitions

Asynchronously uploads one or more entity definitions to the user's namespace.

Type annotations for
`session.create_client("iotthingsgraph").upload_entity_definitions` method.

Boto3 documentation:
[IoTThingsGraph.Client.upload_entity_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.upload_entity_definitions)

Asynchronous method. Use `await upload_entity_definitions(...)` for a
synchronous call.

Arguments mapping described in
[UploadEntityDefinitionsRequestRequestTypeDef](./type_defs.md#uploadentitydefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `document`:
  [DefinitionDocumentTypeDef](./type_defs.md#definitiondocumenttypedef)
- `syncWithPublicNamespace`: `bool`
- `deprecateExistingEntities`: `bool`

Returns a `Coroutine` for
[UploadEntityDefinitionsResponseTypeDef](./type_defs.md#uploadentitydefinitionsresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("iotthingsgraph").__aenter__`
method.

Boto3 documentation:
[IoTThingsGraph.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [IoTThingsGraphClient](#iotthingsgraphclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("iotthingsgraph").__aexit__`
method.

Boto3 documentation:
[IoTThingsGraph.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("iotthingsgraph").get_paginator`
method with overloads.

- `client.get_paginator("get_flow_template_revisions")` ->
  [GetFlowTemplateRevisionsPaginator](./paginators.md#getflowtemplaterevisionspaginator)
- `client.get_paginator("get_system_template_revisions")` ->
  [GetSystemTemplateRevisionsPaginator](./paginators.md#getsystemtemplaterevisionspaginator)
- `client.get_paginator("list_flow_execution_messages")` ->
  [ListFlowExecutionMessagesPaginator](./paginators.md#listflowexecutionmessagespaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- `client.get_paginator("search_entities")` ->
  [SearchEntitiesPaginator](./paginators.md#searchentitiespaginator)
- `client.get_paginator("search_flow_executions")` ->
  [SearchFlowExecutionsPaginator](./paginators.md#searchflowexecutionspaginator)
- `client.get_paginator("search_flow_templates")` ->
  [SearchFlowTemplatesPaginator](./paginators.md#searchflowtemplatespaginator)
- `client.get_paginator("search_system_instances")` ->
  [SearchSystemInstancesPaginator](./paginators.md#searchsysteminstancespaginator)
- `client.get_paginator("search_system_templates")` ->
  [SearchSystemTemplatesPaginator](./paginators.md#searchsystemtemplatespaginator)
- `client.get_paginator("search_things")` ->
  [SearchThingsPaginator](./paginators.md#searchthingspaginator)
