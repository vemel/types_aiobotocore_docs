<a id="applicationdiscoveryserviceclient-for-aiobotocore-applicationdiscoveryservice-module"></a>

# ApplicationDiscoveryServiceClient for aiobotocore ApplicationDiscoveryService module

> [Index](../README.md) > [ApplicationDiscoveryService](./README.md) >
> ApplicationDiscoveryServiceClient

Auto-generated documentation for
[ApplicationDiscoveryService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService)
type annotations stubs module
[types-aiobotocore-discovery](https://pypi.org/project/types-aiobotocore-discovery/).

- [ApplicationDiscoveryServiceClient for aiobotocore ApplicationDiscoveryService module](#applicationdiscoveryserviceclient-for-aiobotocore-applicationdiscoveryservice-module)
  - [ApplicationDiscoveryServiceClient](#applicationdiscoveryserviceclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_configuration_items_to_application](#associate_configuration_items_to_application)
    - [batch_delete_import_data](#batch_delete_import_data)
    - [can_paginate](#can_paginate)
    - [create_application](#create_application)
    - [create_tags](#create_tags)
    - [delete_applications](#delete_applications)
    - [delete_tags](#delete_tags)
    - [describe_agents](#describe_agents)
    - [describe_configurations](#describe_configurations)
    - [describe_continuous_exports](#describe_continuous_exports)
    - [describe_export_configurations](#describe_export_configurations)
    - [describe_export_tasks](#describe_export_tasks)
    - [describe_import_tasks](#describe_import_tasks)
    - [describe_tags](#describe_tags)
    - [disassociate_configuration_items_from_application](#disassociate_configuration_items_from_application)
    - [export_configurations](#export_configurations)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_discovery_summary](#get_discovery_summary)
    - [list_configurations](#list_configurations)
    - [list_server_neighbors](#list_server_neighbors)
    - [start_continuous_export](#start_continuous_export)
    - [start_data_collection_by_agent_ids](#start_data_collection_by_agent_ids)
    - [start_export_task](#start_export_task)
    - [start_import_task](#start_import_task)
    - [stop_continuous_export](#stop_continuous_export)
    - [stop_data_collection_by_agent_ids](#stop_data_collection_by_agent_ids)
    - [update_application](#update_application)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="applicationdiscoveryserviceclient"></a>

## ApplicationDiscoveryServiceClient

Type annotations for `session.create_client("discovery")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_discovery.client import ApplicationDiscoveryServiceClient

session = get_session()
async with session.create_client("discovery") as client:
    client: ApplicationDiscoveryServiceClient
```

Boto3 documentation:
[ApplicationDiscoveryService.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_discovery.client import Exceptions

def handle_error(exc: Exceptions.AuthorizationErrorException) -> None:
    ...
```

Exceptions:

- `Exceptions.AuthorizationErrorException`
- `Exceptions.ClientError`
- `Exceptions.ConflictErrorException`
- `Exceptions.HomeRegionNotSetException`
- `Exceptions.InvalidParameterException`
- `Exceptions.InvalidParameterValueException`
- `Exceptions.OperationNotPermittedException`
- `Exceptions.ResourceInUseException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServerInternalErrorException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ApplicationDiscoveryServiceClient exceptions.

Type annotations for `session.create_client("discovery").exceptions` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate\_configuration\_items\_to\_application"></a>

### associate_configuration_items_to_application

Associates one or more configuration items with an application.

Type annotations for
`session.create_client("discovery").associate_configuration_items_to_application`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.associate_configuration_items_to_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.associate_configuration_items_to_application)

Asynchronous method. Use
`await associate_configuration_items_to_application(...)` for a synchronous
call.

Arguments mapping described in
[AssociateConfigurationItemsToApplicationRequestRequestTypeDef](./type_defs.md#associateconfigurationitemstoapplicationrequestrequesttypedef).

Keyword-only arguments:

- `applicationConfigurationId`: `str` *(required)*
- `configurationIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="batch\_delete\_import\_data"></a>

### batch_delete_import_data

Deletes one or more import tasks, each identified by their import ID.

Type annotations for
`session.create_client("discovery").batch_delete_import_data` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.batch_delete_import_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.batch_delete_import_data)

Asynchronous method. Use `await batch_delete_import_data(...)` for a
synchronous call.

Arguments mapping described in
[BatchDeleteImportDataRequestRequestTypeDef](./type_defs.md#batchdeleteimportdatarequestrequesttypedef).

Keyword-only arguments:

- `importTaskIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchDeleteImportDataResponseTypeDef](./type_defs.md#batchdeleteimportdataresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("discovery").can_paginate` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_application"></a>

### create_application

Creates an application with the given name and description.

Type annotations for `session.create_client("discovery").create_application`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.create_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.create_application)

Asynchronous method. Use `await create_application(...)` for a synchronous
call.

Arguments mapping described in
[CreateApplicationRequestRequestTypeDef](./type_defs.md#createapplicationrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `description`: `str`

Returns a `Coroutine` for
[CreateApplicationResponseTypeDef](./type_defs.md#createapplicationresponsetypedef).

<a id="create\_tags"></a>

### create_tags

Creates one or more tags for configuration items.

Type annotations for `session.create_client("discovery").create_tags` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestRequestTypeDef](./type_defs.md#createtagsrequestrequesttypedef).

Keyword-only arguments:

- `configurationIds`: `Sequence`\[`str`\] *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_applications"></a>

### delete_applications

Deletes a list of applications and their associations with configuration items.

Type annotations for `session.create_client("discovery").delete_applications`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.delete_applications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.delete_applications)

Asynchronous method. Use `await delete_applications(...)` for a synchronous
call.

Arguments mapping described in
[DeleteApplicationsRequestRequestTypeDef](./type_defs.md#deleteapplicationsrequestrequesttypedef).

Keyword-only arguments:

- `configurationIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_tags"></a>

### delete_tags

Deletes the association between configuration items and one or more tags.

Type annotations for `session.create_client("discovery").delete_tags` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.delete_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.delete_tags)

Asynchronous method. Use `await delete_tags(...)` for a synchronous call.

Arguments mapping described in
[DeleteTagsRequestRequestTypeDef](./type_defs.md#deletetagsrequestrequesttypedef).

Keyword-only arguments:

- `configurationIds`: `Sequence`\[`str`\] *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe\_agents"></a>

### describe_agents

Lists agents or connectors as specified by ID or other filters.

Type annotations for `session.create_client("discovery").describe_agents`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.describe_agents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_agents)

Asynchronous method. Use `await describe_agents(...)` for a synchronous call.

Arguments mapping described in
[DescribeAgentsRequestRequestTypeDef](./type_defs.md#describeagentsrequestrequesttypedef).

Keyword-only arguments:

- `agentIds`: `Sequence`\[`str`\]
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeAgentsResponseTypeDef](./type_defs.md#describeagentsresponsetypedef).

<a id="describe\_configurations"></a>

### describe_configurations

Retrieves attributes for a list of configuration item IDs.

Type annotations for
`session.create_client("discovery").describe_configurations` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.describe_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_configurations)

Asynchronous method. Use `await describe_configurations(...)` for a synchronous
call.

Arguments mapping described in
[DescribeConfigurationsRequestRequestTypeDef](./type_defs.md#describeconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `configurationIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DescribeConfigurationsResponseTypeDef](./type_defs.md#describeconfigurationsresponsetypedef).

<a id="describe\_continuous\_exports"></a>

### describe_continuous_exports

Lists exports as specified by ID.

Type annotations for
`session.create_client("discovery").describe_continuous_exports` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.describe_continuous_exports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_continuous_exports)

Asynchronous method. Use `await describe_continuous_exports(...)` for a
synchronous call.

Arguments mapping described in
[DescribeContinuousExportsRequestRequestTypeDef](./type_defs.md#describecontinuousexportsrequestrequesttypedef).

Keyword-only arguments:

- `exportIds`: `Sequence`\[`str`\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeContinuousExportsResponseTypeDef](./type_defs.md#describecontinuousexportsresponsetypedef).

<a id="describe\_export\_configurations"></a>

### describe_export_configurations

`DescribeExportConfigurations` is deprecated.

Type annotations for
`session.create_client("discovery").describe_export_configurations` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.describe_export_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_export_configurations)

Asynchronous method. Use `await describe_export_configurations(...)` for a
synchronous call.

Arguments mapping described in
[DescribeExportConfigurationsRequestRequestTypeDef](./type_defs.md#describeexportconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `exportIds`: `Sequence`\[`str`\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeExportConfigurationsResponseTypeDef](./type_defs.md#describeexportconfigurationsresponsetypedef).

<a id="describe\_export\_tasks"></a>

### describe_export_tasks

Retrieve status of one or more export tasks.

Type annotations for `session.create_client("discovery").describe_export_tasks`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.describe_export_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_export_tasks)

Asynchronous method. Use `await describe_export_tasks(...)` for a synchronous
call.

Arguments mapping described in
[DescribeExportTasksRequestRequestTypeDef](./type_defs.md#describeexporttasksrequestrequesttypedef).

Keyword-only arguments:

- `exportIds`: `Sequence`\[`str`\]
- `filters`:
  `Sequence`\[[ExportFilterTypeDef](./type_defs.md#exportfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeExportTasksResponseTypeDef](./type_defs.md#describeexporttasksresponsetypedef).

<a id="describe\_import\_tasks"></a>

### describe_import_tasks

Returns an array of import tasks for your account, including status
information, times, IDs, the Amazon S3 Object URL for the import file, and
more.

Type annotations for `session.create_client("discovery").describe_import_tasks`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.describe_import_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_import_tasks)

Asynchronous method. Use `await describe_import_tasks(...)` for a synchronous
call.

Arguments mapping described in
[DescribeImportTasksRequestRequestTypeDef](./type_defs.md#describeimporttasksrequestrequesttypedef).

Keyword-only arguments:

- `filters`:
  `Sequence`\[[ImportTaskFilterTypeDef](./type_defs.md#importtaskfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeImportTasksResponseTypeDef](./type_defs.md#describeimporttasksresponsetypedef).

<a id="describe\_tags"></a>

### describe_tags

Retrieves a list of configuration items that have tags as specified by the key-
value pairs, name and value, passed to the optional parameter `filters` .

Type annotations for `session.create_client("discovery").describe_tags` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.describe_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_tags)

Asynchronous method. Use `await describe_tags(...)` for a synchronous call.

Arguments mapping described in
[DescribeTagsRequestRequestTypeDef](./type_defs.md#describetagsrequestrequesttypedef).

Keyword-only arguments:

- `filters`: `Sequence`\[[TagFilterTypeDef](./type_defs.md#tagfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeTagsResponseTypeDef](./type_defs.md#describetagsresponsetypedef).

<a id="disassociate\_configuration\_items\_from\_application"></a>

### disassociate_configuration_items_from_application

Disassociates one or more configuration items from an application.

Type annotations for
`session.create_client("discovery").disassociate_configuration_items_from_application`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.disassociate_configuration_items_from_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.disassociate_configuration_items_from_application)

Asynchronous method. Use
`await disassociate_configuration_items_from_application(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef](./type_defs.md#disassociateconfigurationitemsfromapplicationrequestrequesttypedef).

Keyword-only arguments:

- `applicationConfigurationId`: `str` *(required)*
- `configurationIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="export\_configurations"></a>

### export_configurations

Deprecated.

Type annotations for `session.create_client("discovery").export_configurations`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.export_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.export_configurations)

Asynchronous method. Use `await export_configurations(...)` for a synchronous
call.

Returns a `Coroutine` for
[ExportConfigurationsResponseTypeDef](./type_defs.md#exportconfigurationsresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("discovery").generate_presigned_url` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_discovery\_summary"></a>

### get_discovery_summary

Retrieves a short summary of discovered assets.

Type annotations for `session.create_client("discovery").get_discovery_summary`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.get_discovery_summary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.get_discovery_summary)

Asynchronous method. Use `await get_discovery_summary(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetDiscoverySummaryResponseTypeDef](./type_defs.md#getdiscoverysummaryresponsetypedef).

<a id="list\_configurations"></a>

### list_configurations

Retrieves a list of configuration items as specified by the value passed to the
required parameter `configurationType`.

Type annotations for `session.create_client("discovery").list_configurations`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.list_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.list_configurations)

Asynchronous method. Use `await list_configurations(...)` for a synchronous
call.

Arguments mapping described in
[ListConfigurationsRequestRequestTypeDef](./type_defs.md#listconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `configurationType`:
  [ConfigurationItemTypeType](./literals.md#configurationitemtypetype)
  *(required)*
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `orderBy`:
  `Sequence`\[[OrderByElementTypeDef](./type_defs.md#orderbyelementtypedef)\]

Returns a `Coroutine` for
[ListConfigurationsResponseTypeDef](./type_defs.md#listconfigurationsresponsetypedef).

<a id="list\_server\_neighbors"></a>

### list_server_neighbors

Retrieves a list of servers that are one network hop away from a specified
server.

Type annotations for `session.create_client("discovery").list_server_neighbors`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.list_server_neighbors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.list_server_neighbors)

Asynchronous method. Use `await list_server_neighbors(...)` for a synchronous
call.

Arguments mapping described in
[ListServerNeighborsRequestRequestTypeDef](./type_defs.md#listserverneighborsrequestrequesttypedef).

Keyword-only arguments:

- `configurationId`: `str` *(required)*
- `portInformationNeeded`: `bool`
- `neighborConfigurationIds`: `Sequence`\[`str`\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListServerNeighborsResponseTypeDef](./type_defs.md#listserverneighborsresponsetypedef).

<a id="start\_continuous\_export"></a>

### start_continuous_export

Start the continuous flow of agent's discovered data into Amazon Athena.

Type annotations for
`session.create_client("discovery").start_continuous_export` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.start_continuous_export](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_continuous_export)

Asynchronous method. Use `await start_continuous_export(...)` for a synchronous
call.

Returns a `Coroutine` for
[StartContinuousExportResponseTypeDef](./type_defs.md#startcontinuousexportresponsetypedef).

<a id="start\_data\_collection\_by\_agent\_ids"></a>

### start_data_collection_by_agent_ids

Instructs the specified agents or connectors to start collecting data.

Type annotations for
`session.create_client("discovery").start_data_collection_by_agent_ids` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.start_data_collection_by_agent_ids](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_data_collection_by_agent_ids)

Asynchronous method. Use `await start_data_collection_by_agent_ids(...)` for a
synchronous call.

Arguments mapping described in
[StartDataCollectionByAgentIdsRequestRequestTypeDef](./type_defs.md#startdatacollectionbyagentidsrequestrequesttypedef).

Keyword-only arguments:

- `agentIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[StartDataCollectionByAgentIdsResponseTypeDef](./type_defs.md#startdatacollectionbyagentidsresponsetypedef).

<a id="start\_export\_task"></a>

### start_export_task

Begins the export of discovered data to an S3 bucket.

Type annotations for `session.create_client("discovery").start_export_task`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.start_export_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_export_task)

Asynchronous method. Use `await start_export_task(...)` for a synchronous call.

Arguments mapping described in
[StartExportTaskRequestRequestTypeDef](./type_defs.md#startexporttaskrequestrequesttypedef).

Keyword-only arguments:

- `exportDataFormat`:
  `Sequence`\[[ExportDataFormatType](./literals.md#exportdataformattype)\]
- `filters`:
  `Sequence`\[[ExportFilterTypeDef](./type_defs.md#exportfiltertypedef)\]
- `startTime`: `Union`\[`datetime`, `str`\]
- `endTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[StartExportTaskResponseTypeDef](./type_defs.md#startexporttaskresponsetypedef).

<a id="start\_import\_task"></a>

### start_import_task

Starts an import task, which allows you to import details of your on-premises
environment directly into AWS Migration Hub without having to use the
Application Discovery Service (ADS) tools such as the Discovery Connector or
Discovery Agent.

Type annotations for `session.create_client("discovery").start_import_task`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.start_import_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_import_task)

Asynchronous method. Use `await start_import_task(...)` for a synchronous call.

Arguments mapping described in
[StartImportTaskRequestRequestTypeDef](./type_defs.md#startimporttaskrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `importUrl`: `str` *(required)*
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[StartImportTaskResponseTypeDef](./type_defs.md#startimporttaskresponsetypedef).

<a id="stop\_continuous\_export"></a>

### stop_continuous_export

Stop the continuous flow of agent's discovered data into Amazon Athena.

Type annotations for
`session.create_client("discovery").stop_continuous_export` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.stop_continuous_export](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.stop_continuous_export)

Asynchronous method. Use `await stop_continuous_export(...)` for a synchronous
call.

Arguments mapping described in
[StopContinuousExportRequestRequestTypeDef](./type_defs.md#stopcontinuousexportrequestrequesttypedef).

Keyword-only arguments:

- `exportId`: `str` *(required)*

Returns a `Coroutine` for
[StopContinuousExportResponseTypeDef](./type_defs.md#stopcontinuousexportresponsetypedef).

<a id="stop\_data\_collection\_by\_agent\_ids"></a>

### stop_data_collection_by_agent_ids

Instructs the specified agents or connectors to stop collecting data.

Type annotations for
`session.create_client("discovery").stop_data_collection_by_agent_ids` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.stop_data_collection_by_agent_ids](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.stop_data_collection_by_agent_ids)

Asynchronous method. Use `await stop_data_collection_by_agent_ids(...)` for a
synchronous call.

Arguments mapping described in
[StopDataCollectionByAgentIdsRequestRequestTypeDef](./type_defs.md#stopdatacollectionbyagentidsrequestrequesttypedef).

Keyword-only arguments:

- `agentIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[StopDataCollectionByAgentIdsResponseTypeDef](./type_defs.md#stopdatacollectionbyagentidsresponsetypedef).

<a id="update\_application"></a>

### update_application

Updates metadata about an application.

Type annotations for `session.create_client("discovery").update_application`
method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.update_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.update_application)

Asynchronous method. Use `await update_application(...)` for a synchronous
call.

Arguments mapping described in
[UpdateApplicationRequestRequestTypeDef](./type_defs.md#updateapplicationrequestrequesttypedef).

Keyword-only arguments:

- `configurationId`: `str` *(required)*
- `name`: `str`
- `description`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("discovery").__aenter__` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for
[ApplicationDiscoveryServiceClient](#applicationdiscoveryserviceclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("discovery").__aexit__` method.

Boto3 documentation:
[ApplicationDiscoveryService.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("discovery").get_paginator` method
with overloads.

- `client.get_paginator("describe_agents")` ->
  [DescribeAgentsPaginator](./paginators.md#describeagentspaginator)
- `client.get_paginator("describe_continuous_exports")` ->
  [DescribeContinuousExportsPaginator](./paginators.md#describecontinuousexportspaginator)
- `client.get_paginator("describe_export_configurations")` ->
  [DescribeExportConfigurationsPaginator](./paginators.md#describeexportconfigurationspaginator)
- `client.get_paginator("describe_export_tasks")` ->
  [DescribeExportTasksPaginator](./paginators.md#describeexporttaskspaginator)
- `client.get_paginator("describe_tags")` ->
  [DescribeTagsPaginator](./paginators.md#describetagspaginator)
- `client.get_paginator("list_configurations")` ->
  [ListConfigurationsPaginator](./paginators.md#listconfigurationspaginator)
