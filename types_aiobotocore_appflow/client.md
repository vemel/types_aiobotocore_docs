<a id="appflowclient-for-aiobotocore-appflow-module"></a>

# AppflowClient for aiobotocore Appflow module

> [Index](..) > [Appflow](.) > AppflowClient

Auto-generated documentation for
[Appflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
type annotations stubs module
[types-aiobotocore-appflow](https://pypi.org/project/types-aiobotocore-appflow/).

- [AppflowClient for aiobotocore Appflow module](#appflowclient-for-aiobotocore-appflow-module)
  - [AppflowClient](#appflowclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_connector_profile](#create_connector_profile)
    - [create_flow](#create_flow)
    - [delete_connector_profile](#delete_connector_profile)
    - [delete_flow](#delete_flow)
    - [describe_connector_entity](#describe_connector_entity)
    - [describe_connector_profiles](#describe_connector_profiles)
    - [describe_connectors](#describe_connectors)
    - [describe_flow](#describe_flow)
    - [describe_flow_execution_records](#describe_flow_execution_records)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_connector_entities](#list_connector_entities)
    - [list_flows](#list_flows)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [start_flow](#start_flow)
    - [stop_flow](#stop_flow)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_connector_profile](#update_connector_profile)
    - [update_flow](#update_flow)

<a id="appflowclient"></a>

## AppflowClient

Type annotations for `aiobotocore.create_client("appflow")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_appflow.client import AppflowClient

def get_appflow_client() -> AppflowClient:
    return Session().client("appflow")
```

Boto3 documentation:
[Appflow.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_appflow.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.ConnectorAuthenticationException`
- `Exceptions.ConnectorServerException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.UnsupportedOperationException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

AppflowClient exceptions.

Type annotations for `aiobotocore.create_client("appflow").exceptions` method.

Boto3 documentation:
[Appflow.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("appflow").can_paginate`
method.

Boto3 documentation:
[Appflow.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_connector_profile"></a>

### create_connector_profile

Creates a new connector profile associated with your Amazon Web Services
account.

Type annotations for
`aiobotocore.create_client("appflow").create_connector_profile` method.

Boto3 documentation:
[Appflow.Client.create_connector_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.create_connector_profile)

Asynchronous method. Use `await create_connector_profile(...)` for a
synchronous call.

Arguments mapping described in
[CreateConnectorProfileRequestRequestTypeDef](./type_defs.md#createconnectorprofilerequestrequesttypedef).

Keyword-only arguments:

- `connectorProfileName`: `str` *(required)*
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
  *(required)*
- `connectionMode`: [ConnectionModeType](./literals.md#connectionmodetype)
  *(required)*
- `connectorProfileConfig`:
  [ConnectorProfileConfigTypeDef](./type_defs.md#connectorprofileconfigtypedef)
  *(required)*
- `kmsArn`: `str`

Returns a `Coroutine` for
[CreateConnectorProfileResponseTypeDef](./type_defs.md#createconnectorprofileresponsetypedef).

<a id="create_flow"></a>

### create_flow

Enables your application to create a new flow using Amazon AppFlow.

Type annotations for `aiobotocore.create_client("appflow").create_flow` method.

Boto3 documentation:
[Appflow.Client.create_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.create_flow)

Asynchronous method. Use `await create_flow(...)` for a synchronous call.

Arguments mapping described in
[CreateFlowRequestRequestTypeDef](./type_defs.md#createflowrequestrequesttypedef).

Keyword-only arguments:

- `flowName`: `str` *(required)*
- `triggerConfig`: [TriggerConfigTypeDef](./type_defs.md#triggerconfigtypedef)
  *(required)*
- `sourceFlowConfig`:
  [SourceFlowConfigTypeDef](./type_defs.md#sourceflowconfigtypedef)
  *(required)*
- `destinationFlowConfigList`:
  `Sequence`\[[DestinationFlowConfigTypeDef](./type_defs.md#destinationflowconfigtypedef)\]
  *(required)*
- `tasks`: `Sequence`\[[TaskTypeDef](./type_defs.md#tasktypedef)\] *(required)*
- `description`: `str`
- `kmsArn`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateFlowResponseTypeDef](./type_defs.md#createflowresponsetypedef).

<a id="delete_connector_profile"></a>

### delete_connector_profile

Enables you to delete an existing connector profile.

Type annotations for
`aiobotocore.create_client("appflow").delete_connector_profile` method.

Boto3 documentation:
[Appflow.Client.delete_connector_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.delete_connector_profile)

Asynchronous method. Use `await delete_connector_profile(...)` for a
synchronous call.

Arguments mapping described in
[DeleteConnectorProfileRequestRequestTypeDef](./type_defs.md#deleteconnectorprofilerequestrequesttypedef).

Keyword-only arguments:

- `connectorProfileName`: `str` *(required)*
- `forceDelete`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_flow"></a>

### delete_flow

Enables your application to delete an existing flow.

Type annotations for `aiobotocore.create_client("appflow").delete_flow` method.

Boto3 documentation:
[Appflow.Client.delete_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.delete_flow)

Asynchronous method. Use `await delete_flow(...)` for a synchronous call.

Arguments mapping described in
[DeleteFlowRequestRequestTypeDef](./type_defs.md#deleteflowrequestrequesttypedef).

Keyword-only arguments:

- `flowName`: `str` *(required)*
- `forceDelete`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_connector_entity"></a>

### describe_connector_entity

Provides details regarding the entity used with the connector, with a
description of the data model for each entity.

Type annotations for
`aiobotocore.create_client("appflow").describe_connector_entity` method.

Boto3 documentation:
[Appflow.Client.describe_connector_entity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.describe_connector_entity)

Asynchronous method. Use `await describe_connector_entity(...)` for a
synchronous call.

Arguments mapping described in
[DescribeConnectorEntityRequestRequestTypeDef](./type_defs.md#describeconnectorentityrequestrequesttypedef).

Keyword-only arguments:

- `connectorEntityName`: `str` *(required)*
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `connectorProfileName`: `str`

Returns a `Coroutine` for
[DescribeConnectorEntityResponseTypeDef](./type_defs.md#describeconnectorentityresponsetypedef).

<a id="describe_connector_profiles"></a>

### describe_connector_profiles

Returns a list of `connector-profile` details matching the provided
`connector- profile` names and `connector-types`.

Type annotations for
`aiobotocore.create_client("appflow").describe_connector_profiles` method.

Boto3 documentation:
[Appflow.Client.describe_connector_profiles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.describe_connector_profiles)

Asynchronous method. Use `await describe_connector_profiles(...)` for a
synchronous call.

Arguments mapping described in
[DescribeConnectorProfilesRequestRequestTypeDef](./type_defs.md#describeconnectorprofilesrequestrequesttypedef).

Keyword-only arguments:

- `connectorProfileNames`: `Sequence`\[`str`\]
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeConnectorProfilesResponseTypeDef](./type_defs.md#describeconnectorprofilesresponsetypedef).

<a id="describe_connectors"></a>

### describe_connectors

Describes the connectors vended by Amazon AppFlow for specified connector
types.

Type annotations for `aiobotocore.create_client("appflow").describe_connectors`
method.

Boto3 documentation:
[Appflow.Client.describe_connectors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.describe_connectors)

Asynchronous method. Use `await describe_connectors(...)` for a synchronous
call.

Arguments mapping described in
[DescribeConnectorsRequestRequestTypeDef](./type_defs.md#describeconnectorsrequestrequesttypedef).

Keyword-only arguments:

- `connectorTypes`:
  `Sequence`\[[ConnectorTypeType](./literals.md#connectortypetype)\]
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeConnectorsResponseTypeDef](./type_defs.md#describeconnectorsresponsetypedef).

<a id="describe_flow"></a>

### describe_flow

Provides a description of the specified flow.

Type annotations for `aiobotocore.create_client("appflow").describe_flow`
method.

Boto3 documentation:
[Appflow.Client.describe_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.describe_flow)

Asynchronous method. Use `await describe_flow(...)` for a synchronous call.

Arguments mapping described in
[DescribeFlowRequestRequestTypeDef](./type_defs.md#describeflowrequestrequesttypedef).

Keyword-only arguments:

- `flowName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeFlowResponseTypeDef](./type_defs.md#describeflowresponsetypedef).

<a id="describe_flow_execution_records"></a>

### describe_flow_execution_records

Fetches the execution history of the flow.

Type annotations for
`aiobotocore.create_client("appflow").describe_flow_execution_records` method.

Boto3 documentation:
[Appflow.Client.describe_flow_execution_records](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.describe_flow_execution_records)

Asynchronous method. Use `await describe_flow_execution_records(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFlowExecutionRecordsRequestRequestTypeDef](./type_defs.md#describeflowexecutionrecordsrequestrequesttypedef).

Keyword-only arguments:

- `flowName`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeFlowExecutionRecordsResponseTypeDef](./type_defs.md#describeflowexecutionrecordsresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("appflow").generate_presigned_url` method.

Boto3 documentation:
[Appflow.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_connector_entities"></a>

### list_connector_entities

Returns the list of available connector entities supported by Amazon AppFlow.

Type annotations for
`aiobotocore.create_client("appflow").list_connector_entities` method.

Boto3 documentation:
[Appflow.Client.list_connector_entities](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.list_connector_entities)

Asynchronous method. Use `await list_connector_entities(...)` for a synchronous
call.

Arguments mapping described in
[ListConnectorEntitiesRequestRequestTypeDef](./type_defs.md#listconnectorentitiesrequestrequesttypedef).

Keyword-only arguments:

- `connectorProfileName`: `str`
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `entitiesPath`: `str`

Returns a `Coroutine` for
[ListConnectorEntitiesResponseTypeDef](./type_defs.md#listconnectorentitiesresponsetypedef).

<a id="list_flows"></a>

### list_flows

Lists all of the flows associated with your account.

Type annotations for `aiobotocore.create_client("appflow").list_flows` method.

Boto3 documentation:
[Appflow.Client.list_flows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.list_flows)

Asynchronous method. Use `await list_flows(...)` for a synchronous call.

Arguments mapping described in
[ListFlowsRequestRequestTypeDef](./type_defs.md#listflowsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListFlowsResponseTypeDef](./type_defs.md#listflowsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Retrieves the tags that are associated with a specified flow.

Type annotations for
`aiobotocore.create_client("appflow").list_tags_for_resource` method.

Boto3 documentation:
[Appflow.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="start_flow"></a>

### start_flow

Activates an existing flow.

Type annotations for `aiobotocore.create_client("appflow").start_flow` method.

Boto3 documentation:
[Appflow.Client.start_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.start_flow)

Asynchronous method. Use `await start_flow(...)` for a synchronous call.

Arguments mapping described in
[StartFlowRequestRequestTypeDef](./type_defs.md#startflowrequestrequesttypedef).

Keyword-only arguments:

- `flowName`: `str` *(required)*

Returns a `Coroutine` for
[StartFlowResponseTypeDef](./type_defs.md#startflowresponsetypedef).

<a id="stop_flow"></a>

### stop_flow

Deactivates the existing flow.

Type annotations for `aiobotocore.create_client("appflow").stop_flow` method.

Boto3 documentation:
[Appflow.Client.stop_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.stop_flow)

Asynchronous method. Use `await stop_flow(...)` for a synchronous call.

Arguments mapping described in
[StopFlowRequestRequestTypeDef](./type_defs.md#stopflowrequestrequesttypedef).

Keyword-only arguments:

- `flowName`: `str` *(required)*

Returns a `Coroutine` for
[StopFlowResponseTypeDef](./type_defs.md#stopflowresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Applies a tag to the specified flow.

Type annotations for `aiobotocore.create_client("appflow").tag_resource`
method.

Boto3 documentation:
[Appflow.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes a tag from the specified flow.

Type annotations for `aiobotocore.create_client("appflow").untag_resource`
method.

Boto3 documentation:
[Appflow.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_connector_profile"></a>

### update_connector_profile

Updates a given connector profile associated with your account.

Type annotations for
`aiobotocore.create_client("appflow").update_connector_profile` method.

Boto3 documentation:
[Appflow.Client.update_connector_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_connector_profile)

Asynchronous method. Use `await update_connector_profile(...)` for a
synchronous call.

Arguments mapping described in
[UpdateConnectorProfileRequestRequestTypeDef](./type_defs.md#updateconnectorprofilerequestrequesttypedef).

Keyword-only arguments:

- `connectorProfileName`: `str` *(required)*
- `connectionMode`: [ConnectionModeType](./literals.md#connectionmodetype)
  *(required)*
- `connectorProfileConfig`:
  [ConnectorProfileConfigTypeDef](./type_defs.md#connectorprofileconfigtypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateConnectorProfileResponseTypeDef](./type_defs.md#updateconnectorprofileresponsetypedef).

<a id="update_flow"></a>

### update_flow

Updates an existing flow.

Type annotations for `aiobotocore.create_client("appflow").update_flow` method.

Boto3 documentation:
[Appflow.Client.update_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_flow)

Asynchronous method. Use `await update_flow(...)` for a synchronous call.

Arguments mapping described in
[UpdateFlowRequestRequestTypeDef](./type_defs.md#updateflowrequestrequesttypedef).

Keyword-only arguments:

- `flowName`: `str` *(required)*
- `triggerConfig`: [TriggerConfigTypeDef](./type_defs.md#triggerconfigtypedef)
  *(required)*
- `sourceFlowConfig`:
  [SourceFlowConfigTypeDef](./type_defs.md#sourceflowconfigtypedef)
  *(required)*
- `destinationFlowConfigList`:
  `Sequence`\[[DestinationFlowConfigTypeDef](./type_defs.md#destinationflowconfigtypedef)\]
  *(required)*
- `tasks`: `Sequence`\[[TaskTypeDef](./type_defs.md#tasktypedef)\] *(required)*
- `description`: `str`

Returns a `Coroutine` for
[UpdateFlowResponseTypeDef](./type_defs.md#updateflowresponsetypedef).
