<a id="iotanalyticsclient-for-aiobotocore-iotanalytics-module"></a>

# IoTAnalyticsClient for aiobotocore IoTAnalytics module

> [Index](../README.md) > [IoTAnalytics](./README.md) > IoTAnalyticsClient

Auto-generated documentation for
[IoTAnalytics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics)
type annotations stubs module
[types-aiobotocore-iotanalytics](https://pypi.org/project/types-aiobotocore-iotanalytics/).

- [IoTAnalyticsClient for aiobotocore IoTAnalytics module](#iotanalyticsclient-for-aiobotocore-iotanalytics-module)
  - [IoTAnalyticsClient](#iotanalyticsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [batch_put_message](#batch_put_message)
    - [can_paginate](#can_paginate)
    - [cancel_pipeline_reprocessing](#cancel_pipeline_reprocessing)
    - [create_channel](#create_channel)
    - [create_dataset](#create_dataset)
    - [create_dataset_content](#create_dataset_content)
    - [create_datastore](#create_datastore)
    - [create_pipeline](#create_pipeline)
    - [delete_channel](#delete_channel)
    - [delete_dataset](#delete_dataset)
    - [delete_dataset_content](#delete_dataset_content)
    - [delete_datastore](#delete_datastore)
    - [delete_pipeline](#delete_pipeline)
    - [describe_channel](#describe_channel)
    - [describe_dataset](#describe_dataset)
    - [describe_datastore](#describe_datastore)
    - [describe_logging_options](#describe_logging_options)
    - [describe_pipeline](#describe_pipeline)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_dataset_content](#get_dataset_content)
    - [list_channels](#list_channels)
    - [list_dataset_contents](#list_dataset_contents)
    - [list_datasets](#list_datasets)
    - [list_datastores](#list_datastores)
    - [list_pipelines](#list_pipelines)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_logging_options](#put_logging_options)
    - [run_pipeline_activity](#run_pipeline_activity)
    - [sample_channel_data](#sample_channel_data)
    - [start_pipeline_reprocessing](#start_pipeline_reprocessing)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_channel](#update_channel)
    - [update_dataset](#update_dataset)
    - [update_datastore](#update_datastore)
    - [update_pipeline](#update_pipeline)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="iotanalyticsclient"></a>

## IoTAnalyticsClient

Type annotations for `session.create_client("iotanalytics")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_iotanalytics.client import IoTAnalyticsClient

session = get_session()
async with session.create_client("iotanalytics") as client:
    client: IoTAnalyticsClient
```

Boto3 documentation:
[IoTAnalytics.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_iotanalytics.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InternalFailureException`
- `Exceptions.InvalidRequestException`
- `Exceptions.LimitExceededException`
- `Exceptions.ResourceAlreadyExistsException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.ThrottlingException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

IoTAnalyticsClient exceptions.

Type annotations for `session.create_client("iotanalytics").exceptions` method.

Boto3 documentation:
[IoTAnalytics.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="batch\_put\_message"></a>

### batch_put_message

Sends messages to a channel.

Type annotations for `session.create_client("iotanalytics").batch_put_message`
method.

Boto3 documentation:
[IoTAnalytics.Client.batch_put_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.batch_put_message)

Asynchronous method. Use `await batch_put_message(...)` for a synchronous call.

Arguments mapping described in
[BatchPutMessageRequestRequestTypeDef](./type_defs.md#batchputmessagerequestrequesttypedef).

Keyword-only arguments:

- `channelName`: `str` *(required)*
- `messages`: `Sequence`\[[MessageTypeDef](./type_defs.md#messagetypedef)\]
  *(required)*

Returns a `Coroutine` for
[BatchPutMessageResponseTypeDef](./type_defs.md#batchputmessageresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("iotanalytics").can_paginate`
method.

Boto3 documentation:
[IoTAnalytics.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="cancel\_pipeline\_reprocessing"></a>

### cancel_pipeline_reprocessing

Cancels the reprocessing of data through the pipeline.

Type annotations for
`session.create_client("iotanalytics").cancel_pipeline_reprocessing` method.

Boto3 documentation:
[IoTAnalytics.Client.cancel_pipeline_reprocessing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.cancel_pipeline_reprocessing)

Asynchronous method. Use `await cancel_pipeline_reprocessing(...)` for a
synchronous call.

Arguments mapping described in
[CancelPipelineReprocessingRequestRequestTypeDef](./type_defs.md#cancelpipelinereprocessingrequestrequesttypedef).

Keyword-only arguments:

- `pipelineName`: `str` *(required)*
- `reprocessingId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create\_channel"></a>

### create_channel

Used to create a channel.

Type annotations for `session.create_client("iotanalytics").create_channel`
method.

Boto3 documentation:
[IoTAnalytics.Client.create_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.create_channel)

Asynchronous method. Use `await create_channel(...)` for a synchronous call.

Arguments mapping described in
[CreateChannelRequestRequestTypeDef](./type_defs.md#createchannelrequestrequesttypedef).

Keyword-only arguments:

- `channelName`: `str` *(required)*
- `channelStorage`:
  [ChannelStorageTypeDef](./type_defs.md#channelstoragetypedef)
- `retentionPeriod`:
  [RetentionPeriodTypeDef](./type_defs.md#retentionperiodtypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateChannelResponseTypeDef](./type_defs.md#createchannelresponsetypedef).

<a id="create\_dataset"></a>

### create_dataset

Used to create a dataset.

Type annotations for `session.create_client("iotanalytics").create_dataset`
method.

Boto3 documentation:
[IoTAnalytics.Client.create_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.create_dataset)

Asynchronous method. Use `await create_dataset(...)` for a synchronous call.

Arguments mapping described in
[CreateDatasetRequestRequestTypeDef](./type_defs.md#createdatasetrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*
- `actions`:
  `Sequence`\[[DatasetActionTypeDef](./type_defs.md#datasetactiontypedef)\]
  *(required)*
- `triggers`:
  `Sequence`\[[DatasetTriggerTypeDef](./type_defs.md#datasettriggertypedef)\]
- `contentDeliveryRules`:
  `Sequence`\[[DatasetContentDeliveryRuleTypeDef](./type_defs.md#datasetcontentdeliveryruletypedef)\]
- `retentionPeriod`:
  [RetentionPeriodTypeDef](./type_defs.md#retentionperiodtypedef)
- `versioningConfiguration`:
  [VersioningConfigurationTypeDef](./type_defs.md#versioningconfigurationtypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `lateDataRules`:
  `Sequence`\[[LateDataRuleTypeDef](./type_defs.md#latedataruletypedef)\]

Returns a `Coroutine` for
[CreateDatasetResponseTypeDef](./type_defs.md#createdatasetresponsetypedef).

<a id="create\_dataset\_content"></a>

### create_dataset_content

Creates the content of a dataset by applying a `queryAction` (a SQL query) or a
`containerAction` (executing a containerized application).

Type annotations for
`session.create_client("iotanalytics").create_dataset_content` method.

Boto3 documentation:
[IoTAnalytics.Client.create_dataset_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.create_dataset_content)

Asynchronous method. Use `await create_dataset_content(...)` for a synchronous
call.

Arguments mapping described in
[CreateDatasetContentRequestRequestTypeDef](./type_defs.md#createdatasetcontentrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*
- `versionId`: `str`

Returns a `Coroutine` for
[CreateDatasetContentResponseTypeDef](./type_defs.md#createdatasetcontentresponsetypedef).

<a id="create\_datastore"></a>

### create_datastore

Creates a data store, which is a repository for messages.

Type annotations for `session.create_client("iotanalytics").create_datastore`
method.

Boto3 documentation:
[IoTAnalytics.Client.create_datastore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.create_datastore)

Asynchronous method. Use `await create_datastore(...)` for a synchronous call.

Arguments mapping described in
[CreateDatastoreRequestRequestTypeDef](./type_defs.md#createdatastorerequestrequesttypedef).

Keyword-only arguments:

- `datastoreName`: `str` *(required)*
- `datastoreStorage`:
  [DatastoreStorageTypeDef](./type_defs.md#datastorestoragetypedef)
- `retentionPeriod`:
  [RetentionPeriodTypeDef](./type_defs.md#retentionperiodtypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `fileFormatConfiguration`:
  [FileFormatConfigurationTypeDef](./type_defs.md#fileformatconfigurationtypedef)
- `datastorePartitions`:
  [DatastorePartitionsTypeDef](./type_defs.md#datastorepartitionstypedef)

Returns a `Coroutine` for
[CreateDatastoreResponseTypeDef](./type_defs.md#createdatastoreresponsetypedef).

<a id="create\_pipeline"></a>

### create_pipeline

Creates a pipeline.

Type annotations for `session.create_client("iotanalytics").create_pipeline`
method.

Boto3 documentation:
[IoTAnalytics.Client.create_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.create_pipeline)

Asynchronous method. Use `await create_pipeline(...)` for a synchronous call.

Arguments mapping described in
[CreatePipelineRequestRequestTypeDef](./type_defs.md#createpipelinerequestrequesttypedef).

Keyword-only arguments:

- `pipelineName`: `str` *(required)*
- `pipelineActivities`:
  `Sequence`\[[PipelineActivityTypeDef](./type_defs.md#pipelineactivitytypedef)\]
  *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreatePipelineResponseTypeDef](./type_defs.md#createpipelineresponsetypedef).

<a id="delete\_channel"></a>

### delete_channel

Deletes the specified channel.

Type annotations for `session.create_client("iotanalytics").delete_channel`
method.

Boto3 documentation:
[IoTAnalytics.Client.delete_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.delete_channel)

Asynchronous method. Use `await delete_channel(...)` for a synchronous call.

Arguments mapping described in
[DeleteChannelRequestRequestTypeDef](./type_defs.md#deletechannelrequestrequesttypedef).

Keyword-only arguments:

- `channelName`: `str` *(required)*

<a id="delete\_dataset"></a>

### delete_dataset

Deletes the specified dataset.

Type annotations for `session.create_client("iotanalytics").delete_dataset`
method.

Boto3 documentation:
[IoTAnalytics.Client.delete_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.delete_dataset)

Asynchronous method. Use `await delete_dataset(...)` for a synchronous call.

Arguments mapping described in
[DeleteDatasetRequestRequestTypeDef](./type_defs.md#deletedatasetrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*

<a id="delete\_dataset\_content"></a>

### delete_dataset_content

Deletes the content of the specified dataset.

Type annotations for
`session.create_client("iotanalytics").delete_dataset_content` method.

Boto3 documentation:
[IoTAnalytics.Client.delete_dataset_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.delete_dataset_content)

Asynchronous method. Use `await delete_dataset_content(...)` for a synchronous
call.

Arguments mapping described in
[DeleteDatasetContentRequestRequestTypeDef](./type_defs.md#deletedatasetcontentrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*
- `versionId`: `str`

<a id="delete\_datastore"></a>

### delete_datastore

Deletes the specified data store.

Type annotations for `session.create_client("iotanalytics").delete_datastore`
method.

Boto3 documentation:
[IoTAnalytics.Client.delete_datastore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.delete_datastore)

Asynchronous method. Use `await delete_datastore(...)` for a synchronous call.

Arguments mapping described in
[DeleteDatastoreRequestRequestTypeDef](./type_defs.md#deletedatastorerequestrequesttypedef).

Keyword-only arguments:

- `datastoreName`: `str` *(required)*

<a id="delete\_pipeline"></a>

### delete_pipeline

Deletes the specified pipeline.

Type annotations for `session.create_client("iotanalytics").delete_pipeline`
method.

Boto3 documentation:
[IoTAnalytics.Client.delete_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.delete_pipeline)

Asynchronous method. Use `await delete_pipeline(...)` for a synchronous call.

Arguments mapping described in
[DeletePipelineRequestRequestTypeDef](./type_defs.md#deletepipelinerequestrequesttypedef).

Keyword-only arguments:

- `pipelineName`: `str` *(required)*

<a id="describe\_channel"></a>

### describe_channel

Retrieves information about a channel.

Type annotations for `session.create_client("iotanalytics").describe_channel`
method.

Boto3 documentation:
[IoTAnalytics.Client.describe_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.describe_channel)

Asynchronous method. Use `await describe_channel(...)` for a synchronous call.

Arguments mapping described in
[DescribeChannelRequestRequestTypeDef](./type_defs.md#describechannelrequestrequesttypedef).

Keyword-only arguments:

- `channelName`: `str` *(required)*
- `includeStatistics`: `bool`

Returns a `Coroutine` for
[DescribeChannelResponseTypeDef](./type_defs.md#describechannelresponsetypedef).

<a id="describe\_dataset"></a>

### describe_dataset

Retrieves information about a dataset.

Type annotations for `session.create_client("iotanalytics").describe_dataset`
method.

Boto3 documentation:
[IoTAnalytics.Client.describe_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.describe_dataset)

Asynchronous method. Use `await describe_dataset(...)` for a synchronous call.

Arguments mapping described in
[DescribeDatasetRequestRequestTypeDef](./type_defs.md#describedatasetrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDatasetResponseTypeDef](./type_defs.md#describedatasetresponsetypedef).

<a id="describe\_datastore"></a>

### describe_datastore

Retrieves information about a data store.

Type annotations for `session.create_client("iotanalytics").describe_datastore`
method.

Boto3 documentation:
[IoTAnalytics.Client.describe_datastore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.describe_datastore)

Asynchronous method. Use `await describe_datastore(...)` for a synchronous
call.

Arguments mapping described in
[DescribeDatastoreRequestRequestTypeDef](./type_defs.md#describedatastorerequestrequesttypedef).

Keyword-only arguments:

- `datastoreName`: `str` *(required)*
- `includeStatistics`: `bool`

Returns a `Coroutine` for
[DescribeDatastoreResponseTypeDef](./type_defs.md#describedatastoreresponsetypedef).

<a id="describe\_logging\_options"></a>

### describe_logging_options

Retrieves the current settings of the IoT Analytics logging options.

Type annotations for
`session.create_client("iotanalytics").describe_logging_options` method.

Boto3 documentation:
[IoTAnalytics.Client.describe_logging_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.describe_logging_options)

Asynchronous method. Use `await describe_logging_options(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeLoggingOptionsResponseTypeDef](./type_defs.md#describeloggingoptionsresponsetypedef).

<a id="describe\_pipeline"></a>

### describe_pipeline

Retrieves information about a pipeline.

Type annotations for `session.create_client("iotanalytics").describe_pipeline`
method.

Boto3 documentation:
[IoTAnalytics.Client.describe_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.describe_pipeline)

Asynchronous method. Use `await describe_pipeline(...)` for a synchronous call.

Arguments mapping described in
[DescribePipelineRequestRequestTypeDef](./type_defs.md#describepipelinerequestrequesttypedef).

Keyword-only arguments:

- `pipelineName`: `str` *(required)*

Returns a `Coroutine` for
[DescribePipelineResponseTypeDef](./type_defs.md#describepipelineresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("iotanalytics").generate_presigned_url` method.

Boto3 documentation:
[IoTAnalytics.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_dataset\_content"></a>

### get_dataset_content

Retrieves the contents of a dataset as presigned URIs.

Type annotations for
`session.create_client("iotanalytics").get_dataset_content` method.

Boto3 documentation:
[IoTAnalytics.Client.get_dataset_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.get_dataset_content)

Asynchronous method. Use `await get_dataset_content(...)` for a synchronous
call.

Arguments mapping described in
[GetDatasetContentRequestRequestTypeDef](./type_defs.md#getdatasetcontentrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*
- `versionId`: `str`

Returns a `Coroutine` for
[GetDatasetContentResponseTypeDef](./type_defs.md#getdatasetcontentresponsetypedef).

<a id="list\_channels"></a>

### list_channels

Retrieves a list of channels.

Type annotations for `session.create_client("iotanalytics").list_channels`
method.

Boto3 documentation:
[IoTAnalytics.Client.list_channels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.list_channels)

Asynchronous method. Use `await list_channels(...)` for a synchronous call.

Arguments mapping described in
[ListChannelsRequestRequestTypeDef](./type_defs.md#listchannelsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListChannelsResponseTypeDef](./type_defs.md#listchannelsresponsetypedef).

<a id="list\_dataset\_contents"></a>

### list_dataset_contents

Lists information about dataset contents that have been created.

Type annotations for
`session.create_client("iotanalytics").list_dataset_contents` method.

Boto3 documentation:
[IoTAnalytics.Client.list_dataset_contents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.list_dataset_contents)

Asynchronous method. Use `await list_dataset_contents(...)` for a synchronous
call.

Arguments mapping described in
[ListDatasetContentsRequestRequestTypeDef](./type_defs.md#listdatasetcontentsrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`
- `scheduledOnOrAfter`: `Union`\[`datetime`, `str`\]
- `scheduledBefore`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[ListDatasetContentsResponseTypeDef](./type_defs.md#listdatasetcontentsresponsetypedef).

<a id="list\_datasets"></a>

### list_datasets

Retrieves information about datasets.

Type annotations for `session.create_client("iotanalytics").list_datasets`
method.

Boto3 documentation:
[IoTAnalytics.Client.list_datasets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.list_datasets)

Asynchronous method. Use `await list_datasets(...)` for a synchronous call.

Arguments mapping described in
[ListDatasetsRequestRequestTypeDef](./type_defs.md#listdatasetsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListDatasetsResponseTypeDef](./type_defs.md#listdatasetsresponsetypedef).

<a id="list\_datastores"></a>

### list_datastores

Retrieves a list of data stores.

Type annotations for `session.create_client("iotanalytics").list_datastores`
method.

Boto3 documentation:
[IoTAnalytics.Client.list_datastores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.list_datastores)

Asynchronous method. Use `await list_datastores(...)` for a synchronous call.

Arguments mapping described in
[ListDatastoresRequestRequestTypeDef](./type_defs.md#listdatastoresrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListDatastoresResponseTypeDef](./type_defs.md#listdatastoresresponsetypedef).

<a id="list\_pipelines"></a>

### list_pipelines

Retrieves a list of pipelines.

Type annotations for `session.create_client("iotanalytics").list_pipelines`
method.

Boto3 documentation:
[IoTAnalytics.Client.list_pipelines](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.list_pipelines)

Asynchronous method. Use `await list_pipelines(...)` for a synchronous call.

Arguments mapping described in
[ListPipelinesRequestRequestTypeDef](./type_defs.md#listpipelinesrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListPipelinesResponseTypeDef](./type_defs.md#listpipelinesresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Lists the tags (metadata) that you have assigned to the resource.

Type annotations for
`session.create_client("iotanalytics").list_tags_for_resource` method.

Boto3 documentation:
[IoTAnalytics.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put\_logging\_options"></a>

### put_logging_options

Sets or updates the IoT Analytics logging options.

Type annotations for
`session.create_client("iotanalytics").put_logging_options` method.

Boto3 documentation:
[IoTAnalytics.Client.put_logging_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.put_logging_options)

Asynchronous method. Use `await put_logging_options(...)` for a synchronous
call.

Arguments mapping described in
[PutLoggingOptionsRequestRequestTypeDef](./type_defs.md#putloggingoptionsrequestrequesttypedef).

Keyword-only arguments:

- `loggingOptions`:
  [LoggingOptionsTypeDef](./type_defs.md#loggingoptionstypedef) *(required)*

<a id="run\_pipeline\_activity"></a>

### run_pipeline_activity

Simulates the results of running a pipeline activity on a message payload.

Type annotations for
`session.create_client("iotanalytics").run_pipeline_activity` method.

Boto3 documentation:
[IoTAnalytics.Client.run_pipeline_activity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.run_pipeline_activity)

Asynchronous method. Use `await run_pipeline_activity(...)` for a synchronous
call.

Arguments mapping described in
[RunPipelineActivityRequestRequestTypeDef](./type_defs.md#runpipelineactivityrequestrequesttypedef).

Keyword-only arguments:

- `pipelineActivity`:
  [PipelineActivityTypeDef](./type_defs.md#pipelineactivitytypedef)
  *(required)*
- `payloads`: `Sequence`\[`Union`\[`bytes`, `IO`\[`bytes`\],
  `StreamingBody`\]\] *(required)*

Returns a `Coroutine` for
[RunPipelineActivityResponseTypeDef](./type_defs.md#runpipelineactivityresponsetypedef).

<a id="sample\_channel\_data"></a>

### sample_channel_data

Retrieves a sample of messages from the specified channel ingested during the
specified timeframe.

Type annotations for
`session.create_client("iotanalytics").sample_channel_data` method.

Boto3 documentation:
[IoTAnalytics.Client.sample_channel_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.sample_channel_data)

Asynchronous method. Use `await sample_channel_data(...)` for a synchronous
call.

Arguments mapping described in
[SampleChannelDataRequestRequestTypeDef](./type_defs.md#samplechanneldatarequestrequesttypedef).

Keyword-only arguments:

- `channelName`: `str` *(required)*
- `maxMessages`: `int`
- `startTime`: `Union`\[`datetime`, `str`\]
- `endTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[SampleChannelDataResponseTypeDef](./type_defs.md#samplechanneldataresponsetypedef).

<a id="start\_pipeline\_reprocessing"></a>

### start_pipeline_reprocessing

Starts the reprocessing of raw message data through the pipeline.

Type annotations for
`session.create_client("iotanalytics").start_pipeline_reprocessing` method.

Boto3 documentation:
[IoTAnalytics.Client.start_pipeline_reprocessing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.start_pipeline_reprocessing)

Asynchronous method. Use `await start_pipeline_reprocessing(...)` for a
synchronous call.

Arguments mapping described in
[StartPipelineReprocessingRequestRequestTypeDef](./type_defs.md#startpipelinereprocessingrequestrequesttypedef).

Keyword-only arguments:

- `pipelineName`: `str` *(required)*
- `startTime`: `Union`\[`datetime`, `str`\]
- `endTime`: `Union`\[`datetime`, `str`\]
- `channelMessages`:
  [ChannelMessagesTypeDef](./type_defs.md#channelmessagestypedef)

Returns a `Coroutine` for
[StartPipelineReprocessingResponseTypeDef](./type_defs.md#startpipelinereprocessingresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Adds to or modifies the tags of the given resource.

Type annotations for `session.create_client("iotanalytics").tag_resource`
method.

Boto3 documentation:
[IoTAnalytics.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Removes the given tags (metadata) from the resource.

Type annotations for `session.create_client("iotanalytics").untag_resource`
method.

Boto3 documentation:
[IoTAnalytics.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_channel"></a>

### update_channel

Used to update the settings of a channel.

Type annotations for `session.create_client("iotanalytics").update_channel`
method.

Boto3 documentation:
[IoTAnalytics.Client.update_channel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.update_channel)

Asynchronous method. Use `await update_channel(...)` for a synchronous call.

Arguments mapping described in
[UpdateChannelRequestRequestTypeDef](./type_defs.md#updatechannelrequestrequesttypedef).

Keyword-only arguments:

- `channelName`: `str` *(required)*
- `channelStorage`:
  [ChannelStorageTypeDef](./type_defs.md#channelstoragetypedef)
- `retentionPeriod`:
  [RetentionPeriodTypeDef](./type_defs.md#retentionperiodtypedef)

<a id="update\_dataset"></a>

### update_dataset

Updates the settings of a dataset.

Type annotations for `session.create_client("iotanalytics").update_dataset`
method.

Boto3 documentation:
[IoTAnalytics.Client.update_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.update_dataset)

Asynchronous method. Use `await update_dataset(...)` for a synchronous call.

Arguments mapping described in
[UpdateDatasetRequestRequestTypeDef](./type_defs.md#updatedatasetrequestrequesttypedef).

Keyword-only arguments:

- `datasetName`: `str` *(required)*
- `actions`:
  `Sequence`\[[DatasetActionTypeDef](./type_defs.md#datasetactiontypedef)\]
  *(required)*
- `triggers`:
  `Sequence`\[[DatasetTriggerTypeDef](./type_defs.md#datasettriggertypedef)\]
- `contentDeliveryRules`:
  `Sequence`\[[DatasetContentDeliveryRuleTypeDef](./type_defs.md#datasetcontentdeliveryruletypedef)\]
- `retentionPeriod`:
  [RetentionPeriodTypeDef](./type_defs.md#retentionperiodtypedef)
- `versioningConfiguration`:
  [VersioningConfigurationTypeDef](./type_defs.md#versioningconfigurationtypedef)
- `lateDataRules`:
  `Sequence`\[[LateDataRuleTypeDef](./type_defs.md#latedataruletypedef)\]

<a id="update\_datastore"></a>

### update_datastore

Used to update the settings of a data store.

Type annotations for `session.create_client("iotanalytics").update_datastore`
method.

Boto3 documentation:
[IoTAnalytics.Client.update_datastore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.update_datastore)

Asynchronous method. Use `await update_datastore(...)` for a synchronous call.

Arguments mapping described in
[UpdateDatastoreRequestRequestTypeDef](./type_defs.md#updatedatastorerequestrequesttypedef).

Keyword-only arguments:

- `datastoreName`: `str` *(required)*
- `retentionPeriod`:
  [RetentionPeriodTypeDef](./type_defs.md#retentionperiodtypedef)
- `datastoreStorage`:
  [DatastoreStorageTypeDef](./type_defs.md#datastorestoragetypedef)
- `fileFormatConfiguration`:
  [FileFormatConfigurationTypeDef](./type_defs.md#fileformatconfigurationtypedef)

<a id="update\_pipeline"></a>

### update_pipeline

Updates the settings of a pipeline.

Type annotations for `session.create_client("iotanalytics").update_pipeline`
method.

Boto3 documentation:
[IoTAnalytics.Client.update_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.update_pipeline)

Asynchronous method. Use `await update_pipeline(...)` for a synchronous call.

Arguments mapping described in
[UpdatePipelineRequestRequestTypeDef](./type_defs.md#updatepipelinerequestrequesttypedef).

Keyword-only arguments:

- `pipelineName`: `str` *(required)*
- `pipelineActivities`:
  `Sequence`\[[PipelineActivityTypeDef](./type_defs.md#pipelineactivitytypedef)\]
  *(required)*

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("iotanalytics").__aenter__` method.

Boto3 documentation:
[IoTAnalytics.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [IoTAnalyticsClient](#iotanalyticsclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("iotanalytics").__aexit__` method.

Boto3 documentation:
[IoTAnalytics.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("iotanalytics").get_paginator`
method with overloads.

- `client.get_paginator("list_channels")` ->
  [ListChannelsPaginator](./paginators.md#listchannelspaginator)
- `client.get_paginator("list_dataset_contents")` ->
  [ListDatasetContentsPaginator](./paginators.md#listdatasetcontentspaginator)
- `client.get_paginator("list_datasets")` ->
  [ListDatasetsPaginator](./paginators.md#listdatasetspaginator)
- `client.get_paginator("list_datastores")` ->
  [ListDatastoresPaginator](./paginators.md#listdatastorespaginator)
- `client.get_paginator("list_pipelines")` ->
  [ListPipelinesPaginator](./paginators.md#listpipelinespaginator)
