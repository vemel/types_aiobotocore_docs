<a id="lookoutequipmentclient-for-aiobotocore-lookoutequipment-module"></a>

# LookoutEquipmentClient for aiobotocore LookoutEquipment module

> [Index](../README.md) > [LookoutEquipment](./README.md) >
> LookoutEquipmentClient

Auto-generated documentation for
[LookoutEquipment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment)
type annotations stubs module
[types-aiobotocore-lookoutequipment](https://pypi.org/project/types-aiobotocore-lookoutequipment/).

- [LookoutEquipmentClient for aiobotocore LookoutEquipment module](#lookoutequipmentclient-for-aiobotocore-lookoutequipment-module)
  - [LookoutEquipmentClient](#lookoutequipmentclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_dataset](#create_dataset)
    - [create_inference_scheduler](#create_inference_scheduler)
    - [create_model](#create_model)
    - [delete_dataset](#delete_dataset)
    - [delete_inference_scheduler](#delete_inference_scheduler)
    - [delete_model](#delete_model)
    - [describe_data_ingestion_job](#describe_data_ingestion_job)
    - [describe_dataset](#describe_dataset)
    - [describe_inference_scheduler](#describe_inference_scheduler)
    - [describe_model](#describe_model)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_data_ingestion_jobs](#list_data_ingestion_jobs)
    - [list_datasets](#list_datasets)
    - [list_inference_executions](#list_inference_executions)
    - [list_inference_schedulers](#list_inference_schedulers)
    - [list_models](#list_models)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [start_data_ingestion_job](#start_data_ingestion_job)
    - [start_inference_scheduler](#start_inference_scheduler)
    - [stop_inference_scheduler](#stop_inference_scheduler)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_inference_scheduler](#update_inference_scheduler)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)

<a id="lookoutequipmentclient"></a>

## LookoutEquipmentClient

Type annotations for `session.create_client("lookoutequipment")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_lookoutequipment.client import LookoutEquipmentClient

session = get_session()
async with session.create_client("lookoutequipment") as client:
    client: LookoutEquipmentClient
```

Boto3 documentation:
[LookoutEquipment.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_lookoutequipment.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

LookoutEquipmentClient exceptions.

Type annotations for `session.create_client("lookoutequipment").exceptions`
method.

Boto3 documentation:
[LookoutEquipment.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("lookoutequipment").can_paginate`
method.

Boto3 documentation:
[LookoutEquipment.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_dataset"></a>

### create_dataset

Creates a container for a collection of data being ingested for analysis.

Type annotations for `session.create_client("lookoutequipment").create_dataset`
method.

Boto3 documentation:
[LookoutEquipment.Client.create_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.create_dataset)

Asynchronous method. Use `await create_dataset(...)` for a synchronous call.

Arguments mapping described in
[CreateDatasetRequestRequestTypeDef](./type_defs.md#createdatasetrequestrequesttypedef).

Keyword-only arguments:

- `DatasetName`: `str` *(required)*
- `DatasetSchema`: [DatasetSchemaTypeDef](./type_defs.md#datasetschematypedef)
  *(required)*
- `ClientToken`: `str` *(required)*
- `ServerSideKmsKeyId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDatasetResponseTypeDef](./type_defs.md#createdatasetresponsetypedef).

<a id="create\_inference\_scheduler"></a>

### create_inference_scheduler

Creates a scheduled inference.

Type annotations for
`session.create_client("lookoutequipment").create_inference_scheduler` method.

Boto3 documentation:
[LookoutEquipment.Client.create_inference_scheduler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.create_inference_scheduler)

Asynchronous method. Use `await create_inference_scheduler(...)` for a
synchronous call.

Arguments mapping described in
[CreateInferenceSchedulerRequestRequestTypeDef](./type_defs.md#createinferenceschedulerrequestrequesttypedef).

Keyword-only arguments:

- `ModelName`: `str` *(required)*
- `InferenceSchedulerName`: `str` *(required)*
- `DataUploadFrequency`:
  [DataUploadFrequencyType](./literals.md#datauploadfrequencytype) *(required)*
- `DataInputConfiguration`:
  [InferenceInputConfigurationTypeDef](./type_defs.md#inferenceinputconfigurationtypedef)
  *(required)*
- `DataOutputConfiguration`:
  [InferenceOutputConfigurationTypeDef](./type_defs.md#inferenceoutputconfigurationtypedef)
  *(required)*
- `RoleArn`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `DataDelayOffsetInMinutes`: `int`
- `ServerSideKmsKeyId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateInferenceSchedulerResponseTypeDef](./type_defs.md#createinferenceschedulerresponsetypedef).

<a id="create\_model"></a>

### create_model

Creates an ML model for data inference.

Type annotations for `session.create_client("lookoutequipment").create_model`
method.

Boto3 documentation:
[LookoutEquipment.Client.create_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.create_model)

Asynchronous method. Use `await create_model(...)` for a synchronous call.

Arguments mapping described in
[CreateModelRequestRequestTypeDef](./type_defs.md#createmodelrequestrequesttypedef).

Keyword-only arguments:

- `ModelName`: `str` *(required)*
- `DatasetName`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `DatasetSchema`: [DatasetSchemaTypeDef](./type_defs.md#datasetschematypedef)
- `LabelsInputConfiguration`:
  [LabelsInputConfigurationTypeDef](./type_defs.md#labelsinputconfigurationtypedef)
- `TrainingDataStartTime`: `Union`\[`datetime`, `str`\]
- `TrainingDataEndTime`: `Union`\[`datetime`, `str`\]
- `EvaluationDataStartTime`: `Union`\[`datetime`, `str`\]
- `EvaluationDataEndTime`: `Union`\[`datetime`, `str`\]
- `RoleArn`: `str`
- `DataPreProcessingConfiguration`:
  [DataPreProcessingConfigurationTypeDef](./type_defs.md#datapreprocessingconfigurationtypedef)
- `ServerSideKmsKeyId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `OffCondition`: `str`

Returns a `Coroutine` for
[CreateModelResponseTypeDef](./type_defs.md#createmodelresponsetypedef).

<a id="delete\_dataset"></a>

### delete_dataset

Deletes a dataset and associated artifacts.

Type annotations for `session.create_client("lookoutequipment").delete_dataset`
method.

Boto3 documentation:
[LookoutEquipment.Client.delete_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.delete_dataset)

Asynchronous method. Use `await delete_dataset(...)` for a synchronous call.

Arguments mapping described in
[DeleteDatasetRequestRequestTypeDef](./type_defs.md#deletedatasetrequestrequesttypedef).

Keyword-only arguments:

- `DatasetName`: `str` *(required)*

<a id="delete\_inference\_scheduler"></a>

### delete_inference_scheduler

Deletes an inference scheduler that has been set up.

Type annotations for
`session.create_client("lookoutequipment").delete_inference_scheduler` method.

Boto3 documentation:
[LookoutEquipment.Client.delete_inference_scheduler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.delete_inference_scheduler)

Asynchronous method. Use `await delete_inference_scheduler(...)` for a
synchronous call.

Arguments mapping described in
[DeleteInferenceSchedulerRequestRequestTypeDef](./type_defs.md#deleteinferenceschedulerrequestrequesttypedef).

Keyword-only arguments:

- `InferenceSchedulerName`: `str` *(required)*

<a id="delete\_model"></a>

### delete_model

Deletes an ML model currently available for Amazon Lookout for Equipment.

Type annotations for `session.create_client("lookoutequipment").delete_model`
method.

Boto3 documentation:
[LookoutEquipment.Client.delete_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.delete_model)

Asynchronous method. Use `await delete_model(...)` for a synchronous call.

Arguments mapping described in
[DeleteModelRequestRequestTypeDef](./type_defs.md#deletemodelrequestrequesttypedef).

Keyword-only arguments:

- `ModelName`: `str` *(required)*

<a id="describe\_data\_ingestion\_job"></a>

### describe_data_ingestion_job

Provides information on a specific data ingestion job such as creation time,
dataset ARN, status, and so on.

Type annotations for
`session.create_client("lookoutequipment").describe_data_ingestion_job` method.

Boto3 documentation:
[LookoutEquipment.Client.describe_data_ingestion_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.describe_data_ingestion_job)

Asynchronous method. Use `await describe_data_ingestion_job(...)` for a
synchronous call.

Arguments mapping described in
[DescribeDataIngestionJobRequestRequestTypeDef](./type_defs.md#describedataingestionjobrequestrequesttypedef).

Keyword-only arguments:

- `JobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDataIngestionJobResponseTypeDef](./type_defs.md#describedataingestionjobresponsetypedef).

<a id="describe\_dataset"></a>

### describe_dataset

Provides a JSON description of the data that is in each time series dataset,
including names, column names, and data types.

Type annotations for
`session.create_client("lookoutequipment").describe_dataset` method.

Boto3 documentation:
[LookoutEquipment.Client.describe_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.describe_dataset)

Asynchronous method. Use `await describe_dataset(...)` for a synchronous call.

Arguments mapping described in
[DescribeDatasetRequestRequestTypeDef](./type_defs.md#describedatasetrequestrequesttypedef).

Keyword-only arguments:

- `DatasetName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDatasetResponseTypeDef](./type_defs.md#describedatasetresponsetypedef).

<a id="describe\_inference\_scheduler"></a>

### describe_inference_scheduler

Specifies information about the inference scheduler being used, including name,
model, status, and associated metadata See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/lookoutequipment-2020-12-15/DescribeInferenceScheduler).

Type annotations for
`session.create_client("lookoutequipment").describe_inference_scheduler`
method.

Boto3 documentation:
[LookoutEquipment.Client.describe_inference_scheduler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.describe_inference_scheduler)

Asynchronous method. Use `await describe_inference_scheduler(...)` for a
synchronous call.

Arguments mapping described in
[DescribeInferenceSchedulerRequestRequestTypeDef](./type_defs.md#describeinferenceschedulerrequestrequesttypedef).

Keyword-only arguments:

- `InferenceSchedulerName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeInferenceSchedulerResponseTypeDef](./type_defs.md#describeinferenceschedulerresponsetypedef).

<a id="describe\_model"></a>

### describe_model

Provides a JSON containing the overall information about a specific ML model,
including model name and ARN, dataset, training and evaluation information,
status, and so on.

Type annotations for `session.create_client("lookoutequipment").describe_model`
method.

Boto3 documentation:
[LookoutEquipment.Client.describe_model](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.describe_model)

Asynchronous method. Use `await describe_model(...)` for a synchronous call.

Arguments mapping described in
[DescribeModelRequestRequestTypeDef](./type_defs.md#describemodelrequestrequesttypedef).

Keyword-only arguments:

- `ModelName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeModelResponseTypeDef](./type_defs.md#describemodelresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("lookoutequipment").generate_presigned_url` method.

Boto3 documentation:
[LookoutEquipment.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list\_data\_ingestion\_jobs"></a>

### list_data_ingestion_jobs

Provides a list of all data ingestion jobs, including dataset name and ARN, S3
location of the input data, status, and so on.

Type annotations for
`session.create_client("lookoutequipment").list_data_ingestion_jobs` method.

Boto3 documentation:
[LookoutEquipment.Client.list_data_ingestion_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.list_data_ingestion_jobs)

Asynchronous method. Use `await list_data_ingestion_jobs(...)` for a
synchronous call.

Arguments mapping described in
[ListDataIngestionJobsRequestRequestTypeDef](./type_defs.md#listdataingestionjobsrequestrequesttypedef).

Keyword-only arguments:

- `DatasetName`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`
- `Status`: [IngestionJobStatusType](./literals.md#ingestionjobstatustype)

Returns a `Coroutine` for
[ListDataIngestionJobsResponseTypeDef](./type_defs.md#listdataingestionjobsresponsetypedef).

<a id="list\_datasets"></a>

### list_datasets

Lists all datasets currently available in your account, filtering on the
dataset name.

Type annotations for `session.create_client("lookoutequipment").list_datasets`
method.

Boto3 documentation:
[LookoutEquipment.Client.list_datasets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.list_datasets)

Asynchronous method. Use `await list_datasets(...)` for a synchronous call.

Arguments mapping described in
[ListDatasetsRequestRequestTypeDef](./type_defs.md#listdatasetsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `DatasetNameBeginsWith`: `str`

Returns a `Coroutine` for
[ListDatasetsResponseTypeDef](./type_defs.md#listdatasetsresponsetypedef).

<a id="list\_inference\_executions"></a>

### list_inference_executions

Lists all inference executions that have been performed by the specified
inference scheduler.

Type annotations for
`session.create_client("lookoutequipment").list_inference_executions` method.

Boto3 documentation:
[LookoutEquipment.Client.list_inference_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.list_inference_executions)

Asynchronous method. Use `await list_inference_executions(...)` for a
synchronous call.

Arguments mapping described in
[ListInferenceExecutionsRequestRequestTypeDef](./type_defs.md#listinferenceexecutionsrequestrequesttypedef).

Keyword-only arguments:

- `InferenceSchedulerName`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `DataStartTimeAfter`: `Union`\[`datetime`, `str`\]
- `DataEndTimeBefore`: `Union`\[`datetime`, `str`\]
- `Status`:
  [InferenceExecutionStatusType](./literals.md#inferenceexecutionstatustype)

Returns a `Coroutine` for
[ListInferenceExecutionsResponseTypeDef](./type_defs.md#listinferenceexecutionsresponsetypedef).

<a id="list\_inference\_schedulers"></a>

### list_inference_schedulers

Retrieves a list of all inference schedulers currently available for your
account.

Type annotations for
`session.create_client("lookoutequipment").list_inference_schedulers` method.

Boto3 documentation:
[LookoutEquipment.Client.list_inference_schedulers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.list_inference_schedulers)

Asynchronous method. Use `await list_inference_schedulers(...)` for a
synchronous call.

Arguments mapping described in
[ListInferenceSchedulersRequestRequestTypeDef](./type_defs.md#listinferenceschedulersrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `InferenceSchedulerNameBeginsWith`: `str`
- `ModelName`: `str`

Returns a `Coroutine` for
[ListInferenceSchedulersResponseTypeDef](./type_defs.md#listinferenceschedulersresponsetypedef).

<a id="list\_models"></a>

### list_models

Generates a list of all models in the account, including model name and ARN,
dataset, and status.

Type annotations for `session.create_client("lookoutequipment").list_models`
method.

Boto3 documentation:
[LookoutEquipment.Client.list_models](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.list_models)

Asynchronous method. Use `await list_models(...)` for a synchronous call.

Arguments mapping described in
[ListModelsRequestRequestTypeDef](./type_defs.md#listmodelsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Status`: [ModelStatusType](./literals.md#modelstatustype)
- `ModelNameBeginsWith`: `str`
- `DatasetNameBeginsWith`: `str`

Returns a `Coroutine` for
[ListModelsResponseTypeDef](./type_defs.md#listmodelsresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Lists all the tags for a specified resource, including key and value.

Type annotations for
`session.create_client("lookoutequipment").list_tags_for_resource` method.

Boto3 documentation:
[LookoutEquipment.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="start\_data\_ingestion\_job"></a>

### start_data_ingestion_job

Starts a data ingestion job.

Type annotations for
`session.create_client("lookoutequipment").start_data_ingestion_job` method.

Boto3 documentation:
[LookoutEquipment.Client.start_data_ingestion_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.start_data_ingestion_job)

Asynchronous method. Use `await start_data_ingestion_job(...)` for a
synchronous call.

Arguments mapping described in
[StartDataIngestionJobRequestRequestTypeDef](./type_defs.md#startdataingestionjobrequestrequesttypedef).

Keyword-only arguments:

- `DatasetName`: `str` *(required)*
- `IngestionInputConfiguration`:
  [IngestionInputConfigurationTypeDef](./type_defs.md#ingestioninputconfigurationtypedef)
  *(required)*
- `RoleArn`: `str` *(required)*
- `ClientToken`: `str` *(required)*

Returns a `Coroutine` for
[StartDataIngestionJobResponseTypeDef](./type_defs.md#startdataingestionjobresponsetypedef).

<a id="start\_inference\_scheduler"></a>

### start_inference_scheduler

Starts an inference scheduler.

Type annotations for
`session.create_client("lookoutequipment").start_inference_scheduler` method.

Boto3 documentation:
[LookoutEquipment.Client.start_inference_scheduler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.start_inference_scheduler)

Asynchronous method. Use `await start_inference_scheduler(...)` for a
synchronous call.

Arguments mapping described in
[StartInferenceSchedulerRequestRequestTypeDef](./type_defs.md#startinferenceschedulerrequestrequesttypedef).

Keyword-only arguments:

- `InferenceSchedulerName`: `str` *(required)*

Returns a `Coroutine` for
[StartInferenceSchedulerResponseTypeDef](./type_defs.md#startinferenceschedulerresponsetypedef).

<a id="stop\_inference\_scheduler"></a>

### stop_inference_scheduler

Stops an inference scheduler.

Type annotations for
`session.create_client("lookoutequipment").stop_inference_scheduler` method.

Boto3 documentation:
[LookoutEquipment.Client.stop_inference_scheduler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.stop_inference_scheduler)

Asynchronous method. Use `await stop_inference_scheduler(...)` for a
synchronous call.

Arguments mapping described in
[StopInferenceSchedulerRequestRequestTypeDef](./type_defs.md#stopinferenceschedulerrequestrequesttypedef).

Keyword-only arguments:

- `InferenceSchedulerName`: `str` *(required)*

Returns a `Coroutine` for
[StopInferenceSchedulerResponseTypeDef](./type_defs.md#stopinferenceschedulerresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Associates a given tag to a resource in your account.

Type annotations for `session.create_client("lookoutequipment").tag_resource`
method.

Boto3 documentation:
[LookoutEquipment.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Removes a specific tag from a given resource.

Type annotations for `session.create_client("lookoutequipment").untag_resource`
method.

Boto3 documentation:
[LookoutEquipment.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_inference\_scheduler"></a>

### update_inference_scheduler

Updates an inference scheduler.

Type annotations for
`session.create_client("lookoutequipment").update_inference_scheduler` method.

Boto3 documentation:
[LookoutEquipment.Client.update_inference_scheduler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.update_inference_scheduler)

Asynchronous method. Use `await update_inference_scheduler(...)` for a
synchronous call.

Arguments mapping described in
[UpdateInferenceSchedulerRequestRequestTypeDef](./type_defs.md#updateinferenceschedulerrequestrequesttypedef).

Keyword-only arguments:

- `InferenceSchedulerName`: `str` *(required)*
- `DataDelayOffsetInMinutes`: `int`
- `DataUploadFrequency`:
  [DataUploadFrequencyType](./literals.md#datauploadfrequencytype)
- `DataInputConfiguration`:
  [InferenceInputConfigurationTypeDef](./type_defs.md#inferenceinputconfigurationtypedef)
- `DataOutputConfiguration`:
  [InferenceOutputConfigurationTypeDef](./type_defs.md#inferenceoutputconfigurationtypedef)
- `RoleArn`: `str`

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("lookoutequipment").__aenter__`
method.

Boto3 documentation:
[LookoutEquipment.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [LookoutEquipmentClient](#lookoutequipmentclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("lookoutequipment").__aexit__`
method.

Boto3 documentation:
[LookoutEquipment.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
