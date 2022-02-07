<a id="glueclient-for-aiobotocore-glue-module"></a>

# GlueClient for aiobotocore Glue module

> [Index](..) > [Glue](.) > GlueClient

Auto-generated documentation for
[Glue](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue)
type annotations stubs module
[types-aiobotocore-glue](https://pypi.org/project/types-aiobotocore-glue/).

- [GlueClient for aiobotocore Glue module](#glueclient-for-aiobotocore-glue-module)
  - [GlueClient](#glueclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [batch_create_partition](#batch_create_partition)
    - [batch_delete_connection](#batch_delete_connection)
    - [batch_delete_partition](#batch_delete_partition)
    - [batch_delete_table](#batch_delete_table)
    - [batch_delete_table_version](#batch_delete_table_version)
    - [batch_get_blueprints](#batch_get_blueprints)
    - [batch_get_crawlers](#batch_get_crawlers)
    - [batch_get_dev_endpoints](#batch_get_dev_endpoints)
    - [batch_get_jobs](#batch_get_jobs)
    - [batch_get_partition](#batch_get_partition)
    - [batch_get_triggers](#batch_get_triggers)
    - [batch_get_workflows](#batch_get_workflows)
    - [batch_stop_job_run](#batch_stop_job_run)
    - [batch_update_partition](#batch_update_partition)
    - [can_paginate](#can_paginate)
    - [cancel_ml_task_run](#cancel_ml_task_run)
    - [check_schema_version_validity](#check_schema_version_validity)
    - [create_blueprint](#create_blueprint)
    - [create_classifier](#create_classifier)
    - [create_connection](#create_connection)
    - [create_crawler](#create_crawler)
    - [create_database](#create_database)
    - [create_dev_endpoint](#create_dev_endpoint)
    - [create_job](#create_job)
    - [create_ml_transform](#create_ml_transform)
    - [create_partition](#create_partition)
    - [create_partition_index](#create_partition_index)
    - [create_registry](#create_registry)
    - [create_schema](#create_schema)
    - [create_script](#create_script)
    - [create_security_configuration](#create_security_configuration)
    - [create_table](#create_table)
    - [create_trigger](#create_trigger)
    - [create_user_defined_function](#create_user_defined_function)
    - [create_workflow](#create_workflow)
    - [delete_blueprint](#delete_blueprint)
    - [delete_classifier](#delete_classifier)
    - [delete_column_statistics_for_partition](#delete_column_statistics_for_partition)
    - [delete_column_statistics_for_table](#delete_column_statistics_for_table)
    - [delete_connection](#delete_connection)
    - [delete_crawler](#delete_crawler)
    - [delete_database](#delete_database)
    - [delete_dev_endpoint](#delete_dev_endpoint)
    - [delete_job](#delete_job)
    - [delete_ml_transform](#delete_ml_transform)
    - [delete_partition](#delete_partition)
    - [delete_partition_index](#delete_partition_index)
    - [delete_registry](#delete_registry)
    - [delete_resource_policy](#delete_resource_policy)
    - [delete_schema](#delete_schema)
    - [delete_schema_versions](#delete_schema_versions)
    - [delete_security_configuration](#delete_security_configuration)
    - [delete_table](#delete_table)
    - [delete_table_version](#delete_table_version)
    - [delete_trigger](#delete_trigger)
    - [delete_user_defined_function](#delete_user_defined_function)
    - [delete_workflow](#delete_workflow)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_blueprint](#get_blueprint)
    - [get_blueprint_run](#get_blueprint_run)
    - [get_blueprint_runs](#get_blueprint_runs)
    - [get_catalog_import_status](#get_catalog_import_status)
    - [get_classifier](#get_classifier)
    - [get_classifiers](#get_classifiers)
    - [get_column_statistics_for_partition](#get_column_statistics_for_partition)
    - [get_column_statistics_for_table](#get_column_statistics_for_table)
    - [get_connection](#get_connection)
    - [get_connections](#get_connections)
    - [get_crawler](#get_crawler)
    - [get_crawler_metrics](#get_crawler_metrics)
    - [get_crawlers](#get_crawlers)
    - [get_data_catalog_encryption_settings](#get_data_catalog_encryption_settings)
    - [get_database](#get_database)
    - [get_databases](#get_databases)
    - [get_dataflow_graph](#get_dataflow_graph)
    - [get_dev_endpoint](#get_dev_endpoint)
    - [get_dev_endpoints](#get_dev_endpoints)
    - [get_job](#get_job)
    - [get_job_bookmark](#get_job_bookmark)
    - [get_job_run](#get_job_run)
    - [get_job_runs](#get_job_runs)
    - [get_jobs](#get_jobs)
    - [get_mapping](#get_mapping)
    - [get_ml_task_run](#get_ml_task_run)
    - [get_ml_task_runs](#get_ml_task_runs)
    - [get_ml_transform](#get_ml_transform)
    - [get_ml_transforms](#get_ml_transforms)
    - [get_partition](#get_partition)
    - [get_partition_indexes](#get_partition_indexes)
    - [get_partitions](#get_partitions)
    - [get_plan](#get_plan)
    - [get_registry](#get_registry)
    - [get_resource_policies](#get_resource_policies)
    - [get_resource_policy](#get_resource_policy)
    - [get_schema](#get_schema)
    - [get_schema_by_definition](#get_schema_by_definition)
    - [get_schema_version](#get_schema_version)
    - [get_schema_versions_diff](#get_schema_versions_diff)
    - [get_security_configuration](#get_security_configuration)
    - [get_security_configurations](#get_security_configurations)
    - [get_table](#get_table)
    - [get_table_version](#get_table_version)
    - [get_table_versions](#get_table_versions)
    - [get_tables](#get_tables)
    - [get_tags](#get_tags)
    - [get_trigger](#get_trigger)
    - [get_triggers](#get_triggers)
    - [get_user_defined_function](#get_user_defined_function)
    - [get_user_defined_functions](#get_user_defined_functions)
    - [get_workflow](#get_workflow)
    - [get_workflow_run](#get_workflow_run)
    - [get_workflow_run_properties](#get_workflow_run_properties)
    - [get_workflow_runs](#get_workflow_runs)
    - [import_catalog_to_glue](#import_catalog_to_glue)
    - [list_blueprints](#list_blueprints)
    - [list_crawlers](#list_crawlers)
    - [list_dev_endpoints](#list_dev_endpoints)
    - [list_jobs](#list_jobs)
    - [list_ml_transforms](#list_ml_transforms)
    - [list_registries](#list_registries)
    - [list_schema_versions](#list_schema_versions)
    - [list_schemas](#list_schemas)
    - [list_triggers](#list_triggers)
    - [list_workflows](#list_workflows)
    - [put_data_catalog_encryption_settings](#put_data_catalog_encryption_settings)
    - [put_resource_policy](#put_resource_policy)
    - [put_schema_version_metadata](#put_schema_version_metadata)
    - [put_workflow_run_properties](#put_workflow_run_properties)
    - [query_schema_version_metadata](#query_schema_version_metadata)
    - [register_schema_version](#register_schema_version)
    - [remove_schema_version_metadata](#remove_schema_version_metadata)
    - [reset_job_bookmark](#reset_job_bookmark)
    - [resume_workflow_run](#resume_workflow_run)
    - [search_tables](#search_tables)
    - [start_blueprint_run](#start_blueprint_run)
    - [start_crawler](#start_crawler)
    - [start_crawler_schedule](#start_crawler_schedule)
    - [start_export_labels_task_run](#start_export_labels_task_run)
    - [start_import_labels_task_run](#start_import_labels_task_run)
    - [start_job_run](#start_job_run)
    - [start_ml_evaluation_task_run](#start_ml_evaluation_task_run)
    - [start_ml_labeling_set_generation_task_run](#start_ml_labeling_set_generation_task_run)
    - [start_trigger](#start_trigger)
    - [start_workflow_run](#start_workflow_run)
    - [stop_crawler](#stop_crawler)
    - [stop_crawler_schedule](#stop_crawler_schedule)
    - [stop_trigger](#stop_trigger)
    - [stop_workflow_run](#stop_workflow_run)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_blueprint](#update_blueprint)
    - [update_classifier](#update_classifier)
    - [update_column_statistics_for_partition](#update_column_statistics_for_partition)
    - [update_column_statistics_for_table](#update_column_statistics_for_table)
    - [update_connection](#update_connection)
    - [update_crawler](#update_crawler)
    - [update_crawler_schedule](#update_crawler_schedule)
    - [update_database](#update_database)
    - [update_dev_endpoint](#update_dev_endpoint)
    - [update_job](#update_job)
    - [update_ml_transform](#update_ml_transform)
    - [update_partition](#update_partition)
    - [update_registry](#update_registry)
    - [update_schema](#update_schema)
    - [update_table](#update_table)
    - [update_trigger](#update_trigger)
    - [update_user_defined_function](#update_user_defined_function)
    - [update_workflow](#update_workflow)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="glueclient"></a>

## GlueClient

Type annotations for `session.create_client("glue")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_glue.client import GlueClient

session = get_session()
async with session.create_client("glue") as client:
    client: GlueClient
```

Boto3 documentation:
[Glue.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_glue.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.AlreadyExistsException`
- `Exceptions.ClientError`
- `Exceptions.ConcurrentModificationException`
- `Exceptions.ConcurrentRunsExceededException`
- `Exceptions.ConditionCheckFailureException`
- `Exceptions.ConflictException`
- `Exceptions.CrawlerNotRunningException`
- `Exceptions.CrawlerRunningException`
- `Exceptions.CrawlerStoppingException`
- `Exceptions.EntityNotFoundException`
- `Exceptions.GlueEncryptionException`
- `Exceptions.IdempotentParameterMismatchException`
- `Exceptions.IllegalBlueprintStateException`
- `Exceptions.IllegalWorkflowStateException`
- `Exceptions.InternalServiceException`
- `Exceptions.InvalidInputException`
- `Exceptions.InvalidStateException`
- `Exceptions.MLTransformNotReadyException`
- `Exceptions.NoScheduleException`
- `Exceptions.OperationTimeoutException`
- `Exceptions.ResourceNotReadyException`
- `Exceptions.ResourceNumberLimitExceededException`
- `Exceptions.SchedulerNotRunningException`
- `Exceptions.SchedulerRunningException`
- `Exceptions.SchedulerTransitioningException`
- `Exceptions.ValidationException`
- `Exceptions.VersionMismatchException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

GlueClient exceptions.

Type annotations for `session.create_client("glue").exceptions` method.

Boto3 documentation:
[Glue.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="batch_create_partition"></a>

### batch_create_partition

Creates one or more partitions in a batch operation.

Type annotations for `session.create_client("glue").batch_create_partition`
method.

Boto3 documentation:
[Glue.Client.batch_create_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_create_partition)

Asynchronous method. Use `await batch_create_partition(...)` for a synchronous
call.

Arguments mapping described in
[BatchCreatePartitionRequestRequestTypeDef](./type_defs.md#batchcreatepartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionInputList`:
  `Sequence`\[[PartitionInputTypeDef](./type_defs.md#partitioninputtypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchCreatePartitionResponseTypeDef](./type_defs.md#batchcreatepartitionresponsetypedef).

<a id="batch_delete_connection"></a>

### batch_delete_connection

Deletes a list of connection definitions from the Data Catalog.

Type annotations for `session.create_client("glue").batch_delete_connection`
method.

Boto3 documentation:
[Glue.Client.batch_delete_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_delete_connection)

Asynchronous method. Use `await batch_delete_connection(...)` for a synchronous
call.

Arguments mapping described in
[BatchDeleteConnectionRequestRequestTypeDef](./type_defs.md#batchdeleteconnectionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionNameList`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchDeleteConnectionResponseTypeDef](./type_defs.md#batchdeleteconnectionresponsetypedef).

<a id="batch_delete_partition"></a>

### batch_delete_partition

Deletes one or more partitions in a batch operation.

Type annotations for `session.create_client("glue").batch_delete_partition`
method.

Boto3 documentation:
[Glue.Client.batch_delete_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_delete_partition)

Asynchronous method. Use `await batch_delete_partition(...)` for a synchronous
call.

Arguments mapping described in
[BatchDeletePartitionRequestRequestTypeDef](./type_defs.md#batchdeletepartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionsToDelete`:
  `Sequence`\[[PartitionValueListTypeDef](./type_defs.md#partitionvaluelisttypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchDeletePartitionResponseTypeDef](./type_defs.md#batchdeletepartitionresponsetypedef).

<a id="batch_delete_table"></a>

### batch_delete_table

Deletes multiple tables at once.

Type annotations for `session.create_client("glue").batch_delete_table` method.

Boto3 documentation:
[Glue.Client.batch_delete_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_delete_table)

Asynchronous method. Use `await batch_delete_table(...)` for a synchronous
call.

Arguments mapping described in
[BatchDeleteTableRequestRequestTypeDef](./type_defs.md#batchdeletetablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TablesToDelete`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`
- `TransactionId`: `str`

Returns a `Coroutine` for
[BatchDeleteTableResponseTypeDef](./type_defs.md#batchdeletetableresponsetypedef).

<a id="batch_delete_table_version"></a>

### batch_delete_table_version

Deletes a specified batch of versions of a table.

Type annotations for `session.create_client("glue").batch_delete_table_version`
method.

Boto3 documentation:
[Glue.Client.batch_delete_table_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_delete_table_version)

Asynchronous method. Use `await batch_delete_table_version(...)` for a
synchronous call.

Arguments mapping described in
[BatchDeleteTableVersionRequestRequestTypeDef](./type_defs.md#batchdeletetableversionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `VersionIds`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchDeleteTableVersionResponseTypeDef](./type_defs.md#batchdeletetableversionresponsetypedef).

<a id="batch_get_blueprints"></a>

### batch_get_blueprints

Retrieves information about a list of blueprints.

Type annotations for `session.create_client("glue").batch_get_blueprints`
method.

Boto3 documentation:
[Glue.Client.batch_get_blueprints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_get_blueprints)

Asynchronous method. Use `await batch_get_blueprints(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetBlueprintsRequestRequestTypeDef](./type_defs.md#batchgetblueprintsrequestrequesttypedef).

Keyword-only arguments:

- `Names`: `Sequence`\[`str`\] *(required)*
- `IncludeBlueprint`: `bool`
- `IncludeParameterSpec`: `bool`

Returns a `Coroutine` for
[BatchGetBlueprintsResponseTypeDef](./type_defs.md#batchgetblueprintsresponsetypedef).

<a id="batch_get_crawlers"></a>

### batch_get_crawlers

Returns a list of resource metadata for a given list of crawler names.

Type annotations for `session.create_client("glue").batch_get_crawlers` method.

Boto3 documentation:
[Glue.Client.batch_get_crawlers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_get_crawlers)

Asynchronous method. Use `await batch_get_crawlers(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetCrawlersRequestRequestTypeDef](./type_defs.md#batchgetcrawlersrequestrequesttypedef).

Keyword-only arguments:

- `CrawlerNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetCrawlersResponseTypeDef](./type_defs.md#batchgetcrawlersresponsetypedef).

<a id="batch_get_dev_endpoints"></a>

### batch_get_dev_endpoints

Returns a list of resource metadata for a given list of development endpoint
names.

Type annotations for `session.create_client("glue").batch_get_dev_endpoints`
method.

Boto3 documentation:
[Glue.Client.batch_get_dev_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_get_dev_endpoints)

Asynchronous method. Use `await batch_get_dev_endpoints(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetDevEndpointsRequestRequestTypeDef](./type_defs.md#batchgetdevendpointsrequestrequesttypedef).

Keyword-only arguments:

- `DevEndpointNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetDevEndpointsResponseTypeDef](./type_defs.md#batchgetdevendpointsresponsetypedef).

<a id="batch_get_jobs"></a>

### batch_get_jobs

Returns a list of resource metadata for a given list of job names.

Type annotations for `session.create_client("glue").batch_get_jobs` method.

Boto3 documentation:
[Glue.Client.batch_get_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_get_jobs)

Asynchronous method. Use `await batch_get_jobs(...)` for a synchronous call.

Arguments mapping described in
[BatchGetJobsRequestRequestTypeDef](./type_defs.md#batchgetjobsrequestrequesttypedef).

Keyword-only arguments:

- `JobNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetJobsResponseTypeDef](./type_defs.md#batchgetjobsresponsetypedef).

<a id="batch_get_partition"></a>

### batch_get_partition

Retrieves partitions in a batch request.

Type annotations for `session.create_client("glue").batch_get_partition`
method.

Boto3 documentation:
[Glue.Client.batch_get_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_get_partition)

Asynchronous method. Use `await batch_get_partition(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetPartitionRequestRequestTypeDef](./type_defs.md#batchgetpartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionsToGet`:
  `Sequence`\[[PartitionValueListTypeDef](./type_defs.md#partitionvaluelisttypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchGetPartitionResponseTypeDef](./type_defs.md#batchgetpartitionresponsetypedef).

<a id="batch_get_triggers"></a>

### batch_get_triggers

Returns a list of resource metadata for a given list of trigger names.

Type annotations for `session.create_client("glue").batch_get_triggers` method.

Boto3 documentation:
[Glue.Client.batch_get_triggers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_get_triggers)

Asynchronous method. Use `await batch_get_triggers(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetTriggersRequestRequestTypeDef](./type_defs.md#batchgettriggersrequestrequesttypedef).

Keyword-only arguments:

- `TriggerNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetTriggersResponseTypeDef](./type_defs.md#batchgettriggersresponsetypedef).

<a id="batch_get_workflows"></a>

### batch_get_workflows

Returns a list of resource metadata for a given list of workflow names.

Type annotations for `session.create_client("glue").batch_get_workflows`
method.

Boto3 documentation:
[Glue.Client.batch_get_workflows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_get_workflows)

Asynchronous method. Use `await batch_get_workflows(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetWorkflowsRequestRequestTypeDef](./type_defs.md#batchgetworkflowsrequestrequesttypedef).

Keyword-only arguments:

- `Names`: `Sequence`\[`str`\] *(required)*
- `IncludeGraph`: `bool`

Returns a `Coroutine` for
[BatchGetWorkflowsResponseTypeDef](./type_defs.md#batchgetworkflowsresponsetypedef).

<a id="batch_stop_job_run"></a>

### batch_stop_job_run

Stops one or more job runs for a specified job definition.

Type annotations for `session.create_client("glue").batch_stop_job_run` method.

Boto3 documentation:
[Glue.Client.batch_stop_job_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_stop_job_run)

Asynchronous method. Use `await batch_stop_job_run(...)` for a synchronous
call.

Arguments mapping described in
[BatchStopJobRunRequestRequestTypeDef](./type_defs.md#batchstopjobrunrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*
- `JobRunIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchStopJobRunResponseTypeDef](./type_defs.md#batchstopjobrunresponsetypedef).

<a id="batch_update_partition"></a>

### batch_update_partition

Updates one or more partitions in a batch operation.

Type annotations for `session.create_client("glue").batch_update_partition`
method.

Boto3 documentation:
[Glue.Client.batch_update_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.batch_update_partition)

Asynchronous method. Use `await batch_update_partition(...)` for a synchronous
call.

Arguments mapping described in
[BatchUpdatePartitionRequestRequestTypeDef](./type_defs.md#batchupdatepartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `Entries`:
  `Sequence`\[[BatchUpdatePartitionRequestEntryTypeDef](./type_defs.md#batchupdatepartitionrequestentrytypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[BatchUpdatePartitionResponseTypeDef](./type_defs.md#batchupdatepartitionresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("glue").can_paginate` method.

Boto3 documentation:
[Glue.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="cancel_ml_task_run"></a>

### cancel_ml_task_run

Cancels (stops) a task run.

Type annotations for `session.create_client("glue").cancel_ml_task_run` method.

Boto3 documentation:
[Glue.Client.cancel_ml_task_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.cancel_ml_task_run)

Asynchronous method. Use `await cancel_ml_task_run(...)` for a synchronous
call.

Arguments mapping described in
[CancelMLTaskRunRequestRequestTypeDef](./type_defs.md#cancelmltaskrunrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*
- `TaskRunId`: `str` *(required)*

Returns a `Coroutine` for
[CancelMLTaskRunResponseTypeDef](./type_defs.md#cancelmltaskrunresponsetypedef).

<a id="check_schema_version_validity"></a>

### check_schema_version_validity

Validates the supplied schema.

Type annotations for
`session.create_client("glue").check_schema_version_validity` method.

Boto3 documentation:
[Glue.Client.check_schema_version_validity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.check_schema_version_validity)

Asynchronous method. Use `await check_schema_version_validity(...)` for a
synchronous call.

Arguments mapping described in
[CheckSchemaVersionValidityInputRequestTypeDef](./type_defs.md#checkschemaversionvalidityinputrequesttypedef).

Keyword-only arguments:

- `DataFormat`: [DataFormatType](./literals.md#dataformattype) *(required)*
- `SchemaDefinition`: `str` *(required)*

Returns a `Coroutine` for
[CheckSchemaVersionValidityResponseTypeDef](./type_defs.md#checkschemaversionvalidityresponsetypedef).

<a id="create_blueprint"></a>

### create_blueprint

Registers a blueprint with Glue.

Type annotations for `session.create_client("glue").create_blueprint` method.

Boto3 documentation:
[Glue.Client.create_blueprint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_blueprint)

Asynchronous method. Use `await create_blueprint(...)` for a synchronous call.

Arguments mapping described in
[CreateBlueprintRequestRequestTypeDef](./type_defs.md#createblueprintrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `BlueprintLocation`: `str` *(required)*
- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateBlueprintResponseTypeDef](./type_defs.md#createblueprintresponsetypedef).

<a id="create_classifier"></a>

### create_classifier

Creates a classifier in the user's account.

Type annotations for `session.create_client("glue").create_classifier` method.

Boto3 documentation:
[Glue.Client.create_classifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_classifier)

Asynchronous method. Use `await create_classifier(...)` for a synchronous call.

Arguments mapping described in
[CreateClassifierRequestRequestTypeDef](./type_defs.md#createclassifierrequestrequesttypedef).

Keyword-only arguments:

- `GrokClassifier`:
  [CreateGrokClassifierRequestTypeDef](./type_defs.md#creategrokclassifierrequesttypedef)
- `XMLClassifier`:
  [CreateXMLClassifierRequestTypeDef](./type_defs.md#createxmlclassifierrequesttypedef)
- `JsonClassifier`:
  [CreateJsonClassifierRequestTypeDef](./type_defs.md#createjsonclassifierrequesttypedef)
- `CsvClassifier`:
  [CreateCsvClassifierRequestTypeDef](./type_defs.md#createcsvclassifierrequesttypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_connection"></a>

### create_connection

Creates a connection definition in the Data Catalog.

Type annotations for `session.create_client("glue").create_connection` method.

Boto3 documentation:
[Glue.Client.create_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_connection)

Asynchronous method. Use `await create_connection(...)` for a synchronous call.

Arguments mapping described in
[CreateConnectionRequestRequestTypeDef](./type_defs.md#createconnectionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionInput`:
  [ConnectionInputTypeDef](./type_defs.md#connectioninputtypedef) *(required)*
- `CatalogId`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_crawler"></a>

### create_crawler

Creates a new crawler with specified targets, role, configuration, and optional
schedule.

Type annotations for `session.create_client("glue").create_crawler` method.

Boto3 documentation:
[Glue.Client.create_crawler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_crawler)

Asynchronous method. Use `await create_crawler(...)` for a synchronous call.

Arguments mapping described in
[CreateCrawlerRequestRequestTypeDef](./type_defs.md#createcrawlerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Role`: `str` *(required)*
- `Targets`: [CrawlerTargetsTypeDef](./type_defs.md#crawlertargetstypedef)
  *(required)*
- `DatabaseName`: `str`
- `Description`: `str`
- `Schedule`: `str`
- `Classifiers`: `Sequence`\[`str`\]
- `TablePrefix`: `str`
- `SchemaChangePolicy`:
  [SchemaChangePolicyTypeDef](./type_defs.md#schemachangepolicytypedef)
- `RecrawlPolicy`: [RecrawlPolicyTypeDef](./type_defs.md#recrawlpolicytypedef)
- `LineageConfiguration`:
  [LineageConfigurationTypeDef](./type_defs.md#lineageconfigurationtypedef)
- `Configuration`: `str`
- `CrawlerSecurityConfiguration`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_database"></a>

### create_database

Creates a new database in a Data Catalog.

Type annotations for `session.create_client("glue").create_database` method.

Boto3 documentation:
[Glue.Client.create_database](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_database)

Asynchronous method. Use `await create_database(...)` for a synchronous call.

Arguments mapping described in
[CreateDatabaseRequestRequestTypeDef](./type_defs.md#createdatabaserequestrequesttypedef).

Keyword-only arguments:

- `DatabaseInput`: [DatabaseInputTypeDef](./type_defs.md#databaseinputtypedef)
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_dev_endpoint"></a>

### create_dev_endpoint

Creates a new development endpoint.

Type annotations for `session.create_client("glue").create_dev_endpoint`
method.

Boto3 documentation:
[Glue.Client.create_dev_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_dev_endpoint)

Asynchronous method. Use `await create_dev_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[CreateDevEndpointRequestRequestTypeDef](./type_defs.md#createdevendpointrequestrequesttypedef).

Keyword-only arguments:

- `EndpointName`: `str` *(required)*
- `RoleArn`: `str` *(required)*
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `SubnetId`: `str`
- `PublicKey`: `str`
- `PublicKeys`: `Sequence`\[`str`\]
- `NumberOfNodes`: `int`
- `WorkerType`: [WorkerTypeType](./literals.md#workertypetype)
- `GlueVersion`: `str`
- `NumberOfWorkers`: `int`
- `ExtraPythonLibsS3Path`: `str`
- `ExtraJarsS3Path`: `str`
- `SecurityConfiguration`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `Arguments`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateDevEndpointResponseTypeDef](./type_defs.md#createdevendpointresponsetypedef).

<a id="create_job"></a>

### create_job

Creates a new job definition.

Type annotations for `session.create_client("glue").create_job` method.

Boto3 documentation:
[Glue.Client.create_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_job)

Asynchronous method. Use `await create_job(...)` for a synchronous call.

Arguments mapping described in
[CreateJobRequestRequestTypeDef](./type_defs.md#createjobrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Role`: `str` *(required)*
- `Command`: [JobCommandTypeDef](./type_defs.md#jobcommandtypedef) *(required)*
- `Description`: `str`
- `LogUri`: `str`
- `ExecutionProperty`:
  [ExecutionPropertyTypeDef](./type_defs.md#executionpropertytypedef)
- `DefaultArguments`: `Mapping`\[`str`, `str`\]
- `NonOverridableArguments`: `Mapping`\[`str`, `str`\]
- `Connections`:
  [ConnectionsListTypeDef](./type_defs.md#connectionslisttypedef)
- `MaxRetries`: `int`
- `AllocatedCapacity`: `int`
- `Timeout`: `int`
- `MaxCapacity`: `float`
- `SecurityConfiguration`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `NotificationProperty`:
  [NotificationPropertyTypeDef](./type_defs.md#notificationpropertytypedef)
- `GlueVersion`: `str`
- `NumberOfWorkers`: `int`
- `WorkerType`: [WorkerTypeType](./literals.md#workertypetype)

Returns a `Coroutine` for
[CreateJobResponseTypeDef](./type_defs.md#createjobresponsetypedef).

<a id="create_ml_transform"></a>

### create_ml_transform

Creates an Glue machine learning transform.

Type annotations for `session.create_client("glue").create_ml_transform`
method.

Boto3 documentation:
[Glue.Client.create_ml_transform](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_ml_transform)

Asynchronous method. Use `await create_ml_transform(...)` for a synchronous
call.

Arguments mapping described in
[CreateMLTransformRequestRequestTypeDef](./type_defs.md#createmltransformrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `InputRecordTables`:
  `Sequence`\[[GlueTableTypeDef](./type_defs.md#gluetabletypedef)\]
  *(required)*
- `Parameters`:
  [TransformParametersTypeDef](./type_defs.md#transformparameterstypedef)
  *(required)*
- `Role`: `str` *(required)*
- `Description`: `str`
- `GlueVersion`: `str`
- `MaxCapacity`: `float`
- `WorkerType`: [WorkerTypeType](./literals.md#workertypetype)
- `NumberOfWorkers`: `int`
- `Timeout`: `int`
- `MaxRetries`: `int`
- `Tags`: `Mapping`\[`str`, `str`\]
- `TransformEncryption`:
  [TransformEncryptionTypeDef](./type_defs.md#transformencryptiontypedef)

Returns a `Coroutine` for
[CreateMLTransformResponseTypeDef](./type_defs.md#createmltransformresponsetypedef).

<a id="create_partition"></a>

### create_partition

Creates a new partition.

Type annotations for `session.create_client("glue").create_partition` method.

Boto3 documentation:
[Glue.Client.create_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_partition)

Asynchronous method. Use `await create_partition(...)` for a synchronous call.

Arguments mapping described in
[CreatePartitionRequestRequestTypeDef](./type_defs.md#createpartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionInput`:
  [PartitionInputTypeDef](./type_defs.md#partitioninputtypedef) *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_partition_index"></a>

### create_partition_index

Creates a specified partition index in an existing table.

Type annotations for `session.create_client("glue").create_partition_index`
method.

Boto3 documentation:
[Glue.Client.create_partition_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_partition_index)

Asynchronous method. Use `await create_partition_index(...)` for a synchronous
call.

Arguments mapping described in
[CreatePartitionIndexRequestRequestTypeDef](./type_defs.md#createpartitionindexrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionIndex`:
  [PartitionIndexTypeDef](./type_defs.md#partitionindextypedef) *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_registry"></a>

### create_registry

Creates a new registry which may be used to hold a collection of schemas.

Type annotations for `session.create_client("glue").create_registry` method.

Boto3 documentation:
[Glue.Client.create_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_registry)

Asynchronous method. Use `await create_registry(...)` for a synchronous call.

Arguments mapping described in
[CreateRegistryInputRequestTypeDef](./type_defs.md#createregistryinputrequesttypedef).

Keyword-only arguments:

- `RegistryName`: `str` *(required)*
- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateRegistryResponseTypeDef](./type_defs.md#createregistryresponsetypedef).

<a id="create_schema"></a>

### create_schema

Creates a new schema set and registers the schema definition.

Type annotations for `session.create_client("glue").create_schema` method.

Boto3 documentation:
[Glue.Client.create_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_schema)

Asynchronous method. Use `await create_schema(...)` for a synchronous call.

Arguments mapping described in
[CreateSchemaInputRequestTypeDef](./type_defs.md#createschemainputrequesttypedef).

Keyword-only arguments:

- `SchemaName`: `str` *(required)*
- `DataFormat`: [DataFormatType](./literals.md#dataformattype) *(required)*
- `RegistryId`: [RegistryIdTypeDef](./type_defs.md#registryidtypedef)
- `Compatibility`: [CompatibilityType](./literals.md#compatibilitytype)
- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `SchemaDefinition`: `str`

Returns a `Coroutine` for
[CreateSchemaResponseTypeDef](./type_defs.md#createschemaresponsetypedef).

<a id="create_script"></a>

### create_script

Transforms a directed acyclic graph (DAG) into code.

Type annotations for `session.create_client("glue").create_script` method.

Boto3 documentation:
[Glue.Client.create_script](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_script)

Asynchronous method. Use `await create_script(...)` for a synchronous call.

Arguments mapping described in
[CreateScriptRequestRequestTypeDef](./type_defs.md#createscriptrequestrequesttypedef).

Keyword-only arguments:

- `DagNodes`:
  `Sequence`\[[CodeGenNodeTypeDef](./type_defs.md#codegennodetypedef)\]
- `DagEdges`:
  `Sequence`\[[CodeGenEdgeTypeDef](./type_defs.md#codegenedgetypedef)\]
- `Language`: [LanguageType](./literals.md#languagetype)

Returns a `Coroutine` for
[CreateScriptResponseTypeDef](./type_defs.md#createscriptresponsetypedef).

<a id="create_security_configuration"></a>

### create_security_configuration

Creates a new security configuration.

Type annotations for
`session.create_client("glue").create_security_configuration` method.

Boto3 documentation:
[Glue.Client.create_security_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_security_configuration)

Asynchronous method. Use `await create_security_configuration(...)` for a
synchronous call.

Arguments mapping described in
[CreateSecurityConfigurationRequestRequestTypeDef](./type_defs.md#createsecurityconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `EncryptionConfiguration`:
  [EncryptionConfigurationTypeDef](./type_defs.md#encryptionconfigurationtypedef)
  *(required)*

Returns a `Coroutine` for
[CreateSecurityConfigurationResponseTypeDef](./type_defs.md#createsecurityconfigurationresponsetypedef).

<a id="create_table"></a>

### create_table

Creates a new table definition in the Data Catalog.

Type annotations for `session.create_client("glue").create_table` method.

Boto3 documentation:
[Glue.Client.create_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_table)

Asynchronous method. Use `await create_table(...)` for a synchronous call.

Arguments mapping described in
[CreateTableRequestRequestTypeDef](./type_defs.md#createtablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableInput`: [TableInputTypeDef](./type_defs.md#tableinputtypedef)
  *(required)*
- `CatalogId`: `str`
- `PartitionIndexes`:
  `Sequence`\[[PartitionIndexTypeDef](./type_defs.md#partitionindextypedef)\]
- `TransactionId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_trigger"></a>

### create_trigger

Creates a new trigger.

Type annotations for `session.create_client("glue").create_trigger` method.

Boto3 documentation:
[Glue.Client.create_trigger](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_trigger)

Asynchronous method. Use `await create_trigger(...)` for a synchronous call.

Arguments mapping described in
[CreateTriggerRequestRequestTypeDef](./type_defs.md#createtriggerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Type`: [TriggerTypeType](./literals.md#triggertypetype) *(required)*
- `Actions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]
  *(required)*
- `WorkflowName`: `str`
- `Schedule`: `str`
- `Predicate`: [PredicateTypeDef](./type_defs.md#predicatetypedef)
- `Description`: `str`
- `StartOnCreation`: `bool`
- `Tags`: `Mapping`\[`str`, `str`\]
- `EventBatchingCondition`:
  [EventBatchingConditionTypeDef](./type_defs.md#eventbatchingconditiontypedef)

Returns a `Coroutine` for
[CreateTriggerResponseTypeDef](./type_defs.md#createtriggerresponsetypedef).

<a id="create_user_defined_function"></a>

### create_user_defined_function

Creates a new function definition in the Data Catalog.

Type annotations for
`session.create_client("glue").create_user_defined_function` method.

Boto3 documentation:
[Glue.Client.create_user_defined_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_user_defined_function)

Asynchronous method. Use `await create_user_defined_function(...)` for a
synchronous call.

Arguments mapping described in
[CreateUserDefinedFunctionRequestRequestTypeDef](./type_defs.md#createuserdefinedfunctionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `FunctionInput`:
  [UserDefinedFunctionInputTypeDef](./type_defs.md#userdefinedfunctioninputtypedef)
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_workflow"></a>

### create_workflow

Creates a new workflow.

Type annotations for `session.create_client("glue").create_workflow` method.

Boto3 documentation:
[Glue.Client.create_workflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_workflow)

Asynchronous method. Use `await create_workflow(...)` for a synchronous call.

Arguments mapping described in
[CreateWorkflowRequestRequestTypeDef](./type_defs.md#createworkflowrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Description`: `str`
- `DefaultRunProperties`: `Mapping`\[`str`, `str`\]
- `Tags`: `Mapping`\[`str`, `str`\]
- `MaxConcurrentRuns`: `int`

Returns a `Coroutine` for
[CreateWorkflowResponseTypeDef](./type_defs.md#createworkflowresponsetypedef).

<a id="delete_blueprint"></a>

### delete_blueprint

Deletes an existing blueprint.

Type annotations for `session.create_client("glue").delete_blueprint` method.

Boto3 documentation:
[Glue.Client.delete_blueprint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_blueprint)

Asynchronous method. Use `await delete_blueprint(...)` for a synchronous call.

Arguments mapping described in
[DeleteBlueprintRequestRequestTypeDef](./type_defs.md#deleteblueprintrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[DeleteBlueprintResponseTypeDef](./type_defs.md#deleteblueprintresponsetypedef).

<a id="delete_classifier"></a>

### delete_classifier

Removes a classifier from the Data Catalog.

Type annotations for `session.create_client("glue").delete_classifier` method.

Boto3 documentation:
[Glue.Client.delete_classifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_classifier)

Asynchronous method. Use `await delete_classifier(...)` for a synchronous call.

Arguments mapping described in
[DeleteClassifierRequestRequestTypeDef](./type_defs.md#deleteclassifierrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_column_statistics_for_partition"></a>

### delete_column_statistics_for_partition

Delete the partition column statistics of a column.

Type annotations for
`session.create_client("glue").delete_column_statistics_for_partition` method.

Boto3 documentation:
[Glue.Client.delete_column_statistics_for_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_column_statistics_for_partition)

Asynchronous method. Use `await delete_column_statistics_for_partition(...)`
for a synchronous call.

Arguments mapping described in
[DeleteColumnStatisticsForPartitionRequestRequestTypeDef](./type_defs.md#deletecolumnstatisticsforpartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionValues`: `Sequence`\[`str`\] *(required)*
- `ColumnName`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_column_statistics_for_table"></a>

### delete_column_statistics_for_table

Retrieves table statistics of columns.

Type annotations for
`session.create_client("glue").delete_column_statistics_for_table` method.

Boto3 documentation:
[Glue.Client.delete_column_statistics_for_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_column_statistics_for_table)

Asynchronous method. Use `await delete_column_statistics_for_table(...)` for a
synchronous call.

Arguments mapping described in
[DeleteColumnStatisticsForTableRequestRequestTypeDef](./type_defs.md#deletecolumnstatisticsfortablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `ColumnName`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_connection"></a>

### delete_connection

Deletes a connection from the Data Catalog.

Type annotations for `session.create_client("glue").delete_connection` method.

Boto3 documentation:
[Glue.Client.delete_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_connection)

Asynchronous method. Use `await delete_connection(...)` for a synchronous call.

Arguments mapping described in
[DeleteConnectionRequestRequestTypeDef](./type_defs.md#deleteconnectionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionName`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_crawler"></a>

### delete_crawler

Removes a specified crawler from the Glue Data Catalog, unless the crawler
state is `RUNNING` .

Type annotations for `session.create_client("glue").delete_crawler` method.

Boto3 documentation:
[Glue.Client.delete_crawler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_crawler)

Asynchronous method. Use `await delete_crawler(...)` for a synchronous call.

Arguments mapping described in
[DeleteCrawlerRequestRequestTypeDef](./type_defs.md#deletecrawlerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_database"></a>

### delete_database

Removes a specified database from a Data Catalog.

Type annotations for `session.create_client("glue").delete_database` method.

Boto3 documentation:
[Glue.Client.delete_database](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_database)

Asynchronous method. Use `await delete_database(...)` for a synchronous call.

Arguments mapping described in
[DeleteDatabaseRequestRequestTypeDef](./type_defs.md#deletedatabaserequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_dev_endpoint"></a>

### delete_dev_endpoint

Deletes a specified development endpoint.

Type annotations for `session.create_client("glue").delete_dev_endpoint`
method.

Boto3 documentation:
[Glue.Client.delete_dev_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_dev_endpoint)

Asynchronous method. Use `await delete_dev_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[DeleteDevEndpointRequestRequestTypeDef](./type_defs.md#deletedevendpointrequestrequesttypedef).

Keyword-only arguments:

- `EndpointName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_job"></a>

### delete_job

Deletes a specified job definition.

Type annotations for `session.create_client("glue").delete_job` method.

Boto3 documentation:
[Glue.Client.delete_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_job)

Asynchronous method. Use `await delete_job(...)` for a synchronous call.

Arguments mapping described in
[DeleteJobRequestRequestTypeDef](./type_defs.md#deletejobrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteJobResponseTypeDef](./type_defs.md#deletejobresponsetypedef).

<a id="delete_ml_transform"></a>

### delete_ml_transform

Deletes an Glue machine learning transform.

Type annotations for `session.create_client("glue").delete_ml_transform`
method.

Boto3 documentation:
[Glue.Client.delete_ml_transform](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_ml_transform)

Asynchronous method. Use `await delete_ml_transform(...)` for a synchronous
call.

Arguments mapping described in
[DeleteMLTransformRequestRequestTypeDef](./type_defs.md#deletemltransformrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteMLTransformResponseTypeDef](./type_defs.md#deletemltransformresponsetypedef).

<a id="delete_partition"></a>

### delete_partition

Deletes a specified partition.

Type annotations for `session.create_client("glue").delete_partition` method.

Boto3 documentation:
[Glue.Client.delete_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_partition)

Asynchronous method. Use `await delete_partition(...)` for a synchronous call.

Arguments mapping described in
[DeletePartitionRequestRequestTypeDef](./type_defs.md#deletepartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionValues`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_partition_index"></a>

### delete_partition_index

Deletes a specified partition index from an existing table.

Type annotations for `session.create_client("glue").delete_partition_index`
method.

Boto3 documentation:
[Glue.Client.delete_partition_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_partition_index)

Asynchronous method. Use `await delete_partition_index(...)` for a synchronous
call.

Arguments mapping described in
[DeletePartitionIndexRequestRequestTypeDef](./type_defs.md#deletepartitionindexrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `IndexName`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_registry"></a>

### delete_registry

Delete the entire registry including schema and all of its versions.

Type annotations for `session.create_client("glue").delete_registry` method.

Boto3 documentation:
[Glue.Client.delete_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_registry)

Asynchronous method. Use `await delete_registry(...)` for a synchronous call.

Arguments mapping described in
[DeleteRegistryInputRequestTypeDef](./type_defs.md#deleteregistryinputrequesttypedef).

Keyword-only arguments:

- `RegistryId`: [RegistryIdTypeDef](./type_defs.md#registryidtypedef)
  *(required)*

Returns a `Coroutine` for
[DeleteRegistryResponseTypeDef](./type_defs.md#deleteregistryresponsetypedef).

<a id="delete_resource_policy"></a>

### delete_resource_policy

Deletes a specified policy.

Type annotations for `session.create_client("glue").delete_resource_policy`
method.

Boto3 documentation:
[Glue.Client.delete_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_resource_policy)

Asynchronous method. Use `await delete_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResourcePolicyRequestRequestTypeDef](./type_defs.md#deleteresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyHashCondition`: `str`
- `ResourceArn`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_schema"></a>

### delete_schema

Deletes the entire schema set, including the schema set and all of its
versions.

Type annotations for `session.create_client("glue").delete_schema` method.

Boto3 documentation:
[Glue.Client.delete_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_schema)

Asynchronous method. Use `await delete_schema(...)` for a synchronous call.

Arguments mapping described in
[DeleteSchemaInputRequestTypeDef](./type_defs.md#deleteschemainputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*

Returns a `Coroutine` for
[DeleteSchemaResponseTypeDef](./type_defs.md#deleteschemaresponsetypedef).

<a id="delete_schema_versions"></a>

### delete_schema_versions

Remove versions from the specified schema.

Type annotations for `session.create_client("glue").delete_schema_versions`
method.

Boto3 documentation:
[Glue.Client.delete_schema_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_schema_versions)

Asynchronous method. Use `await delete_schema_versions(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSchemaVersionsInputRequestTypeDef](./type_defs.md#deleteschemaversionsinputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*
- `Versions`: `str` *(required)*

Returns a `Coroutine` for
[DeleteSchemaVersionsResponseTypeDef](./type_defs.md#deleteschemaversionsresponsetypedef).

<a id="delete_security_configuration"></a>

### delete_security_configuration

Deletes a specified security configuration.

Type annotations for
`session.create_client("glue").delete_security_configuration` method.

Boto3 documentation:
[Glue.Client.delete_security_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_security_configuration)

Asynchronous method. Use `await delete_security_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteSecurityConfigurationRequestRequestTypeDef](./type_defs.md#deletesecurityconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_table"></a>

### delete_table

Removes a table definition from the Data Catalog.

Type annotations for `session.create_client("glue").delete_table` method.

Boto3 documentation:
[Glue.Client.delete_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_table)

Asynchronous method. Use `await delete_table(...)` for a synchronous call.

Arguments mapping described in
[DeleteTableRequestRequestTypeDef](./type_defs.md#deletetablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `Name`: `str` *(required)*
- `CatalogId`: `str`
- `TransactionId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_table_version"></a>

### delete_table_version

Deletes a specified version of a table.

Type annotations for `session.create_client("glue").delete_table_version`
method.

Boto3 documentation:
[Glue.Client.delete_table_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_table_version)

Asynchronous method. Use `await delete_table_version(...)` for a synchronous
call.

Arguments mapping described in
[DeleteTableVersionRequestRequestTypeDef](./type_defs.md#deletetableversionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `VersionId`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_trigger"></a>

### delete_trigger

Deletes a specified trigger.

Type annotations for `session.create_client("glue").delete_trigger` method.

Boto3 documentation:
[Glue.Client.delete_trigger](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_trigger)

Asynchronous method. Use `await delete_trigger(...)` for a synchronous call.

Arguments mapping described in
[DeleteTriggerRequestRequestTypeDef](./type_defs.md#deletetriggerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[DeleteTriggerResponseTypeDef](./type_defs.md#deletetriggerresponsetypedef).

<a id="delete_user_defined_function"></a>

### delete_user_defined_function

Deletes an existing function definition from the Data Catalog.

Type annotations for
`session.create_client("glue").delete_user_defined_function` method.

Boto3 documentation:
[Glue.Client.delete_user_defined_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_user_defined_function)

Asynchronous method. Use `await delete_user_defined_function(...)` for a
synchronous call.

Arguments mapping described in
[DeleteUserDefinedFunctionRequestRequestTypeDef](./type_defs.md#deleteuserdefinedfunctionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `FunctionName`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_workflow"></a>

### delete_workflow

Deletes a workflow.

Type annotations for `session.create_client("glue").delete_workflow` method.

Boto3 documentation:
[Glue.Client.delete_workflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_workflow)

Asynchronous method. Use `await delete_workflow(...)` for a synchronous call.

Arguments mapping described in
[DeleteWorkflowRequestRequestTypeDef](./type_defs.md#deleteworkflowrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[DeleteWorkflowResponseTypeDef](./type_defs.md#deleteworkflowresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("glue").generate_presigned_url`
method.

Boto3 documentation:
[Glue.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_blueprint"></a>

### get_blueprint

Retrieves the details of a blueprint.

Type annotations for `session.create_client("glue").get_blueprint` method.

Boto3 documentation:
[Glue.Client.get_blueprint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_blueprint)

Asynchronous method. Use `await get_blueprint(...)` for a synchronous call.

Arguments mapping described in
[GetBlueprintRequestRequestTypeDef](./type_defs.md#getblueprintrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `IncludeBlueprint`: `bool`
- `IncludeParameterSpec`: `bool`

Returns a `Coroutine` for
[GetBlueprintResponseTypeDef](./type_defs.md#getblueprintresponsetypedef).

<a id="get_blueprint_run"></a>

### get_blueprint_run

Retrieves the details of a blueprint run.

Type annotations for `session.create_client("glue").get_blueprint_run` method.

Boto3 documentation:
[Glue.Client.get_blueprint_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_blueprint_run)

Asynchronous method. Use `await get_blueprint_run(...)` for a synchronous call.

Arguments mapping described in
[GetBlueprintRunRequestRequestTypeDef](./type_defs.md#getblueprintrunrequestrequesttypedef).

Keyword-only arguments:

- `BlueprintName`: `str` *(required)*
- `RunId`: `str` *(required)*

Returns a `Coroutine` for
[GetBlueprintRunResponseTypeDef](./type_defs.md#getblueprintrunresponsetypedef).

<a id="get_blueprint_runs"></a>

### get_blueprint_runs

Retrieves the details of blueprint runs for a specified blueprint.

Type annotations for `session.create_client("glue").get_blueprint_runs` method.

Boto3 documentation:
[Glue.Client.get_blueprint_runs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_blueprint_runs)

Asynchronous method. Use `await get_blueprint_runs(...)` for a synchronous
call.

Arguments mapping described in
[GetBlueprintRunsRequestRequestTypeDef](./type_defs.md#getblueprintrunsrequestrequesttypedef).

Keyword-only arguments:

- `BlueprintName`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetBlueprintRunsResponseTypeDef](./type_defs.md#getblueprintrunsresponsetypedef).

<a id="get_catalog_import_status"></a>

### get_catalog_import_status

Retrieves the status of a migration operation.

Type annotations for `session.create_client("glue").get_catalog_import_status`
method.

Boto3 documentation:
[Glue.Client.get_catalog_import_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_catalog_import_status)

Asynchronous method. Use `await get_catalog_import_status(...)` for a
synchronous call.

Arguments mapping described in
[GetCatalogImportStatusRequestRequestTypeDef](./type_defs.md#getcatalogimportstatusrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`

Returns a `Coroutine` for
[GetCatalogImportStatusResponseTypeDef](./type_defs.md#getcatalogimportstatusresponsetypedef).

<a id="get_classifier"></a>

### get_classifier

Retrieve a classifier by name.

Type annotations for `session.create_client("glue").get_classifier` method.

Boto3 documentation:
[Glue.Client.get_classifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_classifier)

Asynchronous method. Use `await get_classifier(...)` for a synchronous call.

Arguments mapping described in
[GetClassifierRequestRequestTypeDef](./type_defs.md#getclassifierrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetClassifierResponseTypeDef](./type_defs.md#getclassifierresponsetypedef).

<a id="get_classifiers"></a>

### get_classifiers

Lists all classifier objects in the Data Catalog.

Type annotations for `session.create_client("glue").get_classifiers` method.

Boto3 documentation:
[Glue.Client.get_classifiers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_classifiers)

Asynchronous method. Use `await get_classifiers(...)` for a synchronous call.

Arguments mapping described in
[GetClassifiersRequestRequestTypeDef](./type_defs.md#getclassifiersrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetClassifiersResponseTypeDef](./type_defs.md#getclassifiersresponsetypedef).

<a id="get_column_statistics_for_partition"></a>

### get_column_statistics_for_partition

Retrieves partition statistics of columns.

Type annotations for
`session.create_client("glue").get_column_statistics_for_partition` method.

Boto3 documentation:
[Glue.Client.get_column_statistics_for_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_column_statistics_for_partition)

Asynchronous method. Use `await get_column_statistics_for_partition(...)` for a
synchronous call.

Arguments mapping described in
[GetColumnStatisticsForPartitionRequestRequestTypeDef](./type_defs.md#getcolumnstatisticsforpartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionValues`: `Sequence`\[`str`\] *(required)*
- `ColumnNames`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[GetColumnStatisticsForPartitionResponseTypeDef](./type_defs.md#getcolumnstatisticsforpartitionresponsetypedef).

<a id="get_column_statistics_for_table"></a>

### get_column_statistics_for_table

Retrieves table statistics of columns.

Type annotations for
`session.create_client("glue").get_column_statistics_for_table` method.

Boto3 documentation:
[Glue.Client.get_column_statistics_for_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_column_statistics_for_table)

Asynchronous method. Use `await get_column_statistics_for_table(...)` for a
synchronous call.

Arguments mapping described in
[GetColumnStatisticsForTableRequestRequestTypeDef](./type_defs.md#getcolumnstatisticsfortablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `ColumnNames`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[GetColumnStatisticsForTableResponseTypeDef](./type_defs.md#getcolumnstatisticsfortableresponsetypedef).

<a id="get_connection"></a>

### get_connection

Retrieves a connection definition from the Data Catalog.

Type annotations for `session.create_client("glue").get_connection` method.

Boto3 documentation:
[Glue.Client.get_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_connection)

Asynchronous method. Use `await get_connection(...)` for a synchronous call.

Arguments mapping described in
[GetConnectionRequestRequestTypeDef](./type_defs.md#getconnectionrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `CatalogId`: `str`
- `HidePassword`: `bool`

Returns a `Coroutine` for
[GetConnectionResponseTypeDef](./type_defs.md#getconnectionresponsetypedef).

<a id="get_connections"></a>

### get_connections

Retrieves a list of connection definitions from the Data Catalog.

Type annotations for `session.create_client("glue").get_connections` method.

Boto3 documentation:
[Glue.Client.get_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_connections)

Asynchronous method. Use `await get_connections(...)` for a synchronous call.

Arguments mapping described in
[GetConnectionsRequestRequestTypeDef](./type_defs.md#getconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`
- `Filter`:
  [GetConnectionsFilterTypeDef](./type_defs.md#getconnectionsfiltertypedef)
- `HidePassword`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetConnectionsResponseTypeDef](./type_defs.md#getconnectionsresponsetypedef).

<a id="get_crawler"></a>

### get_crawler

Retrieves metadata for a specified crawler.

Type annotations for `session.create_client("glue").get_crawler` method.

Boto3 documentation:
[Glue.Client.get_crawler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_crawler)

Asynchronous method. Use `await get_crawler(...)` for a synchronous call.

Arguments mapping described in
[GetCrawlerRequestRequestTypeDef](./type_defs.md#getcrawlerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetCrawlerResponseTypeDef](./type_defs.md#getcrawlerresponsetypedef).

<a id="get_crawler_metrics"></a>

### get_crawler_metrics

Retrieves metrics about specified crawlers.

Type annotations for `session.create_client("glue").get_crawler_metrics`
method.

Boto3 documentation:
[Glue.Client.get_crawler_metrics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_crawler_metrics)

Asynchronous method. Use `await get_crawler_metrics(...)` for a synchronous
call.

Arguments mapping described in
[GetCrawlerMetricsRequestRequestTypeDef](./type_defs.md#getcrawlermetricsrequestrequesttypedef).

Keyword-only arguments:

- `CrawlerNameList`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetCrawlerMetricsResponseTypeDef](./type_defs.md#getcrawlermetricsresponsetypedef).

<a id="get_crawlers"></a>

### get_crawlers

Retrieves metadata for all crawlers defined in the customer account.

Type annotations for `session.create_client("glue").get_crawlers` method.

Boto3 documentation:
[Glue.Client.get_crawlers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_crawlers)

Asynchronous method. Use `await get_crawlers(...)` for a synchronous call.

Arguments mapping described in
[GetCrawlersRequestRequestTypeDef](./type_defs.md#getcrawlersrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetCrawlersResponseTypeDef](./type_defs.md#getcrawlersresponsetypedef).

<a id="get_data_catalog_encryption_settings"></a>

### get_data_catalog_encryption_settings

Retrieves the security configuration for a specified catalog.

Type annotations for
`session.create_client("glue").get_data_catalog_encryption_settings` method.

Boto3 documentation:
[Glue.Client.get_data_catalog_encryption_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_data_catalog_encryption_settings)

Asynchronous method. Use `await get_data_catalog_encryption_settings(...)` for
a synchronous call.

Arguments mapping described in
[GetDataCatalogEncryptionSettingsRequestRequestTypeDef](./type_defs.md#getdatacatalogencryptionsettingsrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`

Returns a `Coroutine` for
[GetDataCatalogEncryptionSettingsResponseTypeDef](./type_defs.md#getdatacatalogencryptionsettingsresponsetypedef).

<a id="get_database"></a>

### get_database

Retrieves the definition of a specified database.

Type annotations for `session.create_client("glue").get_database` method.

Boto3 documentation:
[Glue.Client.get_database](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_database)

Asynchronous method. Use `await get_database(...)` for a synchronous call.

Arguments mapping described in
[GetDatabaseRequestRequestTypeDef](./type_defs.md#getdatabaserequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[GetDatabaseResponseTypeDef](./type_defs.md#getdatabaseresponsetypedef).

<a id="get_databases"></a>

### get_databases

Retrieves all databases defined in a given Data Catalog.

Type annotations for `session.create_client("glue").get_databases` method.

Boto3 documentation:
[Glue.Client.get_databases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_databases)

Asynchronous method. Use `await get_databases(...)` for a synchronous call.

Arguments mapping described in
[GetDatabasesRequestRequestTypeDef](./type_defs.md#getdatabasesrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`
- `ResourceShareType`:
  [ResourceShareTypeType](./literals.md#resourcesharetypetype)

Returns a `Coroutine` for
[GetDatabasesResponseTypeDef](./type_defs.md#getdatabasesresponsetypedef).

<a id="get_dataflow_graph"></a>

### get_dataflow_graph

Transforms a Python script into a directed acyclic graph (DAG).

Type annotations for `session.create_client("glue").get_dataflow_graph` method.

Boto3 documentation:
[Glue.Client.get_dataflow_graph](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_dataflow_graph)

Asynchronous method. Use `await get_dataflow_graph(...)` for a synchronous
call.

Arguments mapping described in
[GetDataflowGraphRequestRequestTypeDef](./type_defs.md#getdataflowgraphrequestrequesttypedef).

Keyword-only arguments:

- `PythonScript`: `str`

Returns a `Coroutine` for
[GetDataflowGraphResponseTypeDef](./type_defs.md#getdataflowgraphresponsetypedef).

<a id="get_dev_endpoint"></a>

### get_dev_endpoint

Retrieves information about a specified development endpoint.

Type annotations for `session.create_client("glue").get_dev_endpoint` method.

Boto3 documentation:
[Glue.Client.get_dev_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_dev_endpoint)

Asynchronous method. Use `await get_dev_endpoint(...)` for a synchronous call.

Arguments mapping described in
[GetDevEndpointRequestRequestTypeDef](./type_defs.md#getdevendpointrequestrequesttypedef).

Keyword-only arguments:

- `EndpointName`: `str` *(required)*

Returns a `Coroutine` for
[GetDevEndpointResponseTypeDef](./type_defs.md#getdevendpointresponsetypedef).

<a id="get_dev_endpoints"></a>

### get_dev_endpoints

Retrieves all the development endpoints in this AWS account.

Type annotations for `session.create_client("glue").get_dev_endpoints` method.

Boto3 documentation:
[Glue.Client.get_dev_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_dev_endpoints)

Asynchronous method. Use `await get_dev_endpoints(...)` for a synchronous call.

Arguments mapping described in
[GetDevEndpointsRequestRequestTypeDef](./type_defs.md#getdevendpointsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetDevEndpointsResponseTypeDef](./type_defs.md#getdevendpointsresponsetypedef).

<a id="get_job"></a>

### get_job

Retrieves an existing job definition.

Type annotations for `session.create_client("glue").get_job` method.

Boto3 documentation:
[Glue.Client.get_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_job)

Asynchronous method. Use `await get_job(...)` for a synchronous call.

Arguments mapping described in
[GetJobRequestRequestTypeDef](./type_defs.md#getjobrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*

Returns a `Coroutine` for
[GetJobResponseTypeDef](./type_defs.md#getjobresponsetypedef).

<a id="get_job_bookmark"></a>

### get_job_bookmark

Returns information on a job bookmark entry.

Type annotations for `session.create_client("glue").get_job_bookmark` method.

Boto3 documentation:
[Glue.Client.get_job_bookmark](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_job_bookmark)

Asynchronous method. Use `await get_job_bookmark(...)` for a synchronous call.

Arguments mapping described in
[GetJobBookmarkRequestRequestTypeDef](./type_defs.md#getjobbookmarkrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*
- `RunId`: `str`

Returns a `Coroutine` for
[GetJobBookmarkResponseTypeDef](./type_defs.md#getjobbookmarkresponsetypedef).

<a id="get_job_run"></a>

### get_job_run

Retrieves the metadata for a given job run.

Type annotations for `session.create_client("glue").get_job_run` method.

Boto3 documentation:
[Glue.Client.get_job_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_job_run)

Asynchronous method. Use `await get_job_run(...)` for a synchronous call.

Arguments mapping described in
[GetJobRunRequestRequestTypeDef](./type_defs.md#getjobrunrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*
- `RunId`: `str` *(required)*
- `PredecessorsIncluded`: `bool`

Returns a `Coroutine` for
[GetJobRunResponseTypeDef](./type_defs.md#getjobrunresponsetypedef).

<a id="get_job_runs"></a>

### get_job_runs

Retrieves metadata for all runs of a given job definition.

Type annotations for `session.create_client("glue").get_job_runs` method.

Boto3 documentation:
[Glue.Client.get_job_runs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_job_runs)

Asynchronous method. Use `await get_job_runs(...)` for a synchronous call.

Arguments mapping described in
[GetJobRunsRequestRequestTypeDef](./type_defs.md#getjobrunsrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetJobRunsResponseTypeDef](./type_defs.md#getjobrunsresponsetypedef).

<a id="get_jobs"></a>

### get_jobs

Retrieves all current job definitions.

Type annotations for `session.create_client("glue").get_jobs` method.

Boto3 documentation:
[Glue.Client.get_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_jobs)

Asynchronous method. Use `await get_jobs(...)` for a synchronous call.

Arguments mapping described in
[GetJobsRequestRequestTypeDef](./type_defs.md#getjobsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetJobsResponseTypeDef](./type_defs.md#getjobsresponsetypedef).

<a id="get_mapping"></a>

### get_mapping

Creates mappings.

Type annotations for `session.create_client("glue").get_mapping` method.

Boto3 documentation:
[Glue.Client.get_mapping](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_mapping)

Asynchronous method. Use `await get_mapping(...)` for a synchronous call.

Arguments mapping described in
[GetMappingRequestRequestTypeDef](./type_defs.md#getmappingrequestrequesttypedef).

Keyword-only arguments:

- `Source`: [CatalogEntryTypeDef](./type_defs.md#catalogentrytypedef)
  *(required)*
- `Sinks`:
  `Sequence`\[[CatalogEntryTypeDef](./type_defs.md#catalogentrytypedef)\]
- `Location`: [LocationTypeDef](./type_defs.md#locationtypedef)

Returns a `Coroutine` for
[GetMappingResponseTypeDef](./type_defs.md#getmappingresponsetypedef).

<a id="get_ml_task_run"></a>

### get_ml_task_run

Gets details for a specific task run on a machine learning transform.

Type annotations for `session.create_client("glue").get_ml_task_run` method.

Boto3 documentation:
[Glue.Client.get_ml_task_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_ml_task_run)

Asynchronous method. Use `await get_ml_task_run(...)` for a synchronous call.

Arguments mapping described in
[GetMLTaskRunRequestRequestTypeDef](./type_defs.md#getmltaskrunrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*
- `TaskRunId`: `str` *(required)*

Returns a `Coroutine` for
[GetMLTaskRunResponseTypeDef](./type_defs.md#getmltaskrunresponsetypedef).

<a id="get_ml_task_runs"></a>

### get_ml_task_runs

Gets a list of runs for a machine learning transform.

Type annotations for `session.create_client("glue").get_ml_task_runs` method.

Boto3 documentation:
[Glue.Client.get_ml_task_runs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_ml_task_runs)

Asynchronous method. Use `await get_ml_task_runs(...)` for a synchronous call.

Arguments mapping described in
[GetMLTaskRunsRequestRequestTypeDef](./type_defs.md#getmltaskrunsrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `Filter`:
  [TaskRunFilterCriteriaTypeDef](./type_defs.md#taskrunfiltercriteriatypedef)
- `Sort`:
  [TaskRunSortCriteriaTypeDef](./type_defs.md#taskrunsortcriteriatypedef)

Returns a `Coroutine` for
[GetMLTaskRunsResponseTypeDef](./type_defs.md#getmltaskrunsresponsetypedef).

<a id="get_ml_transform"></a>

### get_ml_transform

Gets an Glue machine learning transform artifact and all its corresponding
metadata.

Type annotations for `session.create_client("glue").get_ml_transform` method.

Boto3 documentation:
[Glue.Client.get_ml_transform](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_ml_transform)

Asynchronous method. Use `await get_ml_transform(...)` for a synchronous call.

Arguments mapping described in
[GetMLTransformRequestRequestTypeDef](./type_defs.md#getmltransformrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*

Returns a `Coroutine` for
[GetMLTransformResponseTypeDef](./type_defs.md#getmltransformresponsetypedef).

<a id="get_ml_transforms"></a>

### get_ml_transforms

Gets a sortable, filterable list of existing Glue machine learning transforms.

Type annotations for `session.create_client("glue").get_ml_transforms` method.

Boto3 documentation:
[Glue.Client.get_ml_transforms](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_ml_transforms)

Asynchronous method. Use `await get_ml_transforms(...)` for a synchronous call.

Arguments mapping described in
[GetMLTransformsRequestRequestTypeDef](./type_defs.md#getmltransformsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filter`:
  [TransformFilterCriteriaTypeDef](./type_defs.md#transformfiltercriteriatypedef)
- `Sort`:
  [TransformSortCriteriaTypeDef](./type_defs.md#transformsortcriteriatypedef)

Returns a `Coroutine` for
[GetMLTransformsResponseTypeDef](./type_defs.md#getmltransformsresponsetypedef).

<a id="get_partition"></a>

### get_partition

Retrieves information about a specified partition.

Type annotations for `session.create_client("glue").get_partition` method.

Boto3 documentation:
[Glue.Client.get_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_partition)

Asynchronous method. Use `await get_partition(...)` for a synchronous call.

Arguments mapping described in
[GetPartitionRequestRequestTypeDef](./type_defs.md#getpartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionValues`: `Sequence`\[`str`\] *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[GetPartitionResponseTypeDef](./type_defs.md#getpartitionresponsetypedef).

<a id="get_partition_indexes"></a>

### get_partition_indexes

Retrieves the partition indexes associated with a table.

Type annotations for `session.create_client("glue").get_partition_indexes`
method.

Boto3 documentation:
[Glue.Client.get_partition_indexes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_partition_indexes)

Asynchronous method. Use `await get_partition_indexes(...)` for a synchronous
call.

Arguments mapping described in
[GetPartitionIndexesRequestRequestTypeDef](./type_defs.md#getpartitionindexesrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `CatalogId`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetPartitionIndexesResponseTypeDef](./type_defs.md#getpartitionindexesresponsetypedef).

<a id="get_partitions"></a>

### get_partitions

Retrieves information about the partitions in a table.

Type annotations for `session.create_client("glue").get_partitions` method.

Boto3 documentation:
[Glue.Client.get_partitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_partitions)

Asynchronous method. Use `await get_partitions(...)` for a synchronous call.

Arguments mapping described in
[GetPartitionsRequestRequestTypeDef](./type_defs.md#getpartitionsrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `CatalogId`: `str`
- `Expression`: `str`
- `NextToken`: `str`
- `Segment`: [SegmentTypeDef](./type_defs.md#segmenttypedef)
- `MaxResults`: `int`
- `ExcludeColumnSchema`: `bool`
- `TransactionId`: `str`
- `QueryAsOfTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[GetPartitionsResponseTypeDef](./type_defs.md#getpartitionsresponsetypedef).

<a id="get_plan"></a>

### get_plan

Gets code to perform a specified mapping.

Type annotations for `session.create_client("glue").get_plan` method.

Boto3 documentation:
[Glue.Client.get_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_plan)

Asynchronous method. Use `await get_plan(...)` for a synchronous call.

Arguments mapping described in
[GetPlanRequestRequestTypeDef](./type_defs.md#getplanrequestrequesttypedef).

Keyword-only arguments:

- `Mapping`:
  `Sequence`\[[MappingEntryTypeDef](./type_defs.md#mappingentrytypedef)\]
  *(required)*
- `Source`: [CatalogEntryTypeDef](./type_defs.md#catalogentrytypedef)
  *(required)*
- `Sinks`:
  `Sequence`\[[CatalogEntryTypeDef](./type_defs.md#catalogentrytypedef)\]
- `Location`: [LocationTypeDef](./type_defs.md#locationtypedef)
- `Language`: [LanguageType](./literals.md#languagetype)
- `AdditionalPlanOptionsMap`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[GetPlanResponseTypeDef](./type_defs.md#getplanresponsetypedef).

<a id="get_registry"></a>

### get_registry

Describes the specified registry in detail.

Type annotations for `session.create_client("glue").get_registry` method.

Boto3 documentation:
[Glue.Client.get_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_registry)

Asynchronous method. Use `await get_registry(...)` for a synchronous call.

Arguments mapping described in
[GetRegistryInputRequestTypeDef](./type_defs.md#getregistryinputrequesttypedef).

Keyword-only arguments:

- `RegistryId`: [RegistryIdTypeDef](./type_defs.md#registryidtypedef)
  *(required)*

Returns a `Coroutine` for
[GetRegistryResponseTypeDef](./type_defs.md#getregistryresponsetypedef).

<a id="get_resource_policies"></a>

### get_resource_policies

Retrieves the resource policies set on individual resources by Resource Access
Manager during cross-account permission grants.

Type annotations for `session.create_client("glue").get_resource_policies`
method.

Boto3 documentation:
[Glue.Client.get_resource_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_resource_policies)

Asynchronous method. Use `await get_resource_policies(...)` for a synchronous
call.

Arguments mapping described in
[GetResourcePoliciesRequestRequestTypeDef](./type_defs.md#getresourcepoliciesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetResourcePoliciesResponseTypeDef](./type_defs.md#getresourcepoliciesresponsetypedef).

<a id="get_resource_policy"></a>

### get_resource_policy

Retrieves a specified resource policy.

Type annotations for `session.create_client("glue").get_resource_policy`
method.

Boto3 documentation:
[Glue.Client.get_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_resource_policy)

Asynchronous method. Use `await get_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetResourcePolicyRequestRequestTypeDef](./type_defs.md#getresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str`

Returns a `Coroutine` for
[GetResourcePolicyResponseTypeDef](./type_defs.md#getresourcepolicyresponsetypedef).

<a id="get_schema"></a>

### get_schema

Describes the specified schema in detail.

Type annotations for `session.create_client("glue").get_schema` method.

Boto3 documentation:
[Glue.Client.get_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_schema)

Asynchronous method. Use `await get_schema(...)` for a synchronous call.

Arguments mapping described in
[GetSchemaInputRequestTypeDef](./type_defs.md#getschemainputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*

Returns a `Coroutine` for
[GetSchemaResponseTypeDef](./type_defs.md#getschemaresponsetypedef).

<a id="get_schema_by_definition"></a>

### get_schema_by_definition

Retrieves a schema by the `SchemaDefinition`.

Type annotations for `session.create_client("glue").get_schema_by_definition`
method.

Boto3 documentation:
[Glue.Client.get_schema_by_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_schema_by_definition)

Asynchronous method. Use `await get_schema_by_definition(...)` for a
synchronous call.

Arguments mapping described in
[GetSchemaByDefinitionInputRequestTypeDef](./type_defs.md#getschemabydefinitioninputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*
- `SchemaDefinition`: `str` *(required)*

Returns a `Coroutine` for
[GetSchemaByDefinitionResponseTypeDef](./type_defs.md#getschemabydefinitionresponsetypedef).

<a id="get_schema_version"></a>

### get_schema_version

Get the specified schema by its unique ID assigned when a version of the schema
is created or registered.

Type annotations for `session.create_client("glue").get_schema_version` method.

Boto3 documentation:
[Glue.Client.get_schema_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_schema_version)

Asynchronous method. Use `await get_schema_version(...)` for a synchronous
call.

Arguments mapping described in
[GetSchemaVersionInputRequestTypeDef](./type_defs.md#getschemaversioninputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef)
- `SchemaVersionId`: `str`
- `SchemaVersionNumber`:
  [SchemaVersionNumberTypeDef](./type_defs.md#schemaversionnumbertypedef)

Returns a `Coroutine` for
[GetSchemaVersionResponseTypeDef](./type_defs.md#getschemaversionresponsetypedef).

<a id="get_schema_versions_diff"></a>

### get_schema_versions_diff

Fetches the schema version difference in the specified difference type between
two stored schema versions in the Schema Registry.

Type annotations for `session.create_client("glue").get_schema_versions_diff`
method.

Boto3 documentation:
[Glue.Client.get_schema_versions_diff](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_schema_versions_diff)

Asynchronous method. Use `await get_schema_versions_diff(...)` for a
synchronous call.

Arguments mapping described in
[GetSchemaVersionsDiffInputRequestTypeDef](./type_defs.md#getschemaversionsdiffinputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*
- `FirstSchemaVersionNumber`:
  [SchemaVersionNumberTypeDef](./type_defs.md#schemaversionnumbertypedef)
  *(required)*
- `SecondSchemaVersionNumber`:
  [SchemaVersionNumberTypeDef](./type_defs.md#schemaversionnumbertypedef)
  *(required)*
- `SchemaDiffType`: `Literal['SYNTAX_DIFF']` (see
  [SchemaDiffTypeType](./literals.md#schemadifftypetype)) *(required)*

Returns a `Coroutine` for
[GetSchemaVersionsDiffResponseTypeDef](./type_defs.md#getschemaversionsdiffresponsetypedef).

<a id="get_security_configuration"></a>

### get_security_configuration

Retrieves a specified security configuration.

Type annotations for `session.create_client("glue").get_security_configuration`
method.

Boto3 documentation:
[Glue.Client.get_security_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_security_configuration)

Asynchronous method. Use `await get_security_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetSecurityConfigurationRequestRequestTypeDef](./type_defs.md#getsecurityconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetSecurityConfigurationResponseTypeDef](./type_defs.md#getsecurityconfigurationresponsetypedef).

<a id="get_security_configurations"></a>

### get_security_configurations

Retrieves a list of all security configurations.

Type annotations for
`session.create_client("glue").get_security_configurations` method.

Boto3 documentation:
[Glue.Client.get_security_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_security_configurations)

Asynchronous method. Use `await get_security_configurations(...)` for a
synchronous call.

Arguments mapping described in
[GetSecurityConfigurationsRequestRequestTypeDef](./type_defs.md#getsecurityconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetSecurityConfigurationsResponseTypeDef](./type_defs.md#getsecurityconfigurationsresponsetypedef).

<a id="get_table"></a>

### get_table

Retrieves the `Table` definition in a Data Catalog for a specified table.

Type annotations for `session.create_client("glue").get_table` method.

Boto3 documentation:
[Glue.Client.get_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_table)

Asynchronous method. Use `await get_table(...)` for a synchronous call.

Arguments mapping described in
[GetTableRequestRequestTypeDef](./type_defs.md#gettablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `Name`: `str` *(required)*
- `CatalogId`: `str`
- `TransactionId`: `str`
- `QueryAsOfTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[GetTableResponseTypeDef](./type_defs.md#gettableresponsetypedef).

<a id="get_table_version"></a>

### get_table_version

Retrieves a specified version of a table.

Type annotations for `session.create_client("glue").get_table_version` method.

Boto3 documentation:
[Glue.Client.get_table_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_table_version)

Asynchronous method. Use `await get_table_version(...)` for a synchronous call.

Arguments mapping described in
[GetTableVersionRequestRequestTypeDef](./type_defs.md#gettableversionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `CatalogId`: `str`
- `VersionId`: `str`

Returns a `Coroutine` for
[GetTableVersionResponseTypeDef](./type_defs.md#gettableversionresponsetypedef).

<a id="get_table_versions"></a>

### get_table_versions

Retrieves a list of strings that identify available versions of a specified
table.

Type annotations for `session.create_client("glue").get_table_versions` method.

Boto3 documentation:
[Glue.Client.get_table_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_table_versions)

Asynchronous method. Use `await get_table_versions(...)` for a synchronous
call.

Arguments mapping described in
[GetTableVersionsRequestRequestTypeDef](./type_defs.md#gettableversionsrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `CatalogId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetTableVersionsResponseTypeDef](./type_defs.md#gettableversionsresponsetypedef).

<a id="get_tables"></a>

### get_tables

Retrieves the definitions of some or all of the tables in a given `Database` .

Type annotations for `session.create_client("glue").get_tables` method.

Boto3 documentation:
[Glue.Client.get_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_tables)

Asynchronous method. Use `await get_tables(...)` for a synchronous call.

Arguments mapping described in
[GetTablesRequestRequestTypeDef](./type_defs.md#gettablesrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `CatalogId`: `str`
- `Expression`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`
- `TransactionId`: `str`
- `QueryAsOfTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[GetTablesResponseTypeDef](./type_defs.md#gettablesresponsetypedef).

<a id="get_tags"></a>

### get_tags

Retrieves a list of tags associated with a resource.

Type annotations for `session.create_client("glue").get_tags` method.

Boto3 documentation:
[Glue.Client.get_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_tags)

Asynchronous method. Use `await get_tags(...)` for a synchronous call.

Arguments mapping described in
[GetTagsRequestRequestTypeDef](./type_defs.md#gettagsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[GetTagsResponseTypeDef](./type_defs.md#gettagsresponsetypedef).

<a id="get_trigger"></a>

### get_trigger

Retrieves the definition of a trigger.

Type annotations for `session.create_client("glue").get_trigger` method.

Boto3 documentation:
[Glue.Client.get_trigger](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_trigger)

Asynchronous method. Use `await get_trigger(...)` for a synchronous call.

Arguments mapping described in
[GetTriggerRequestRequestTypeDef](./type_defs.md#gettriggerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetTriggerResponseTypeDef](./type_defs.md#gettriggerresponsetypedef).

<a id="get_triggers"></a>

### get_triggers

Gets all the triggers associated with a job.

Type annotations for `session.create_client("glue").get_triggers` method.

Boto3 documentation:
[Glue.Client.get_triggers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_triggers)

Asynchronous method. Use `await get_triggers(...)` for a synchronous call.

Arguments mapping described in
[GetTriggersRequestRequestTypeDef](./type_defs.md#gettriggersrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `DependentJobName`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetTriggersResponseTypeDef](./type_defs.md#gettriggersresponsetypedef).

<a id="get_user_defined_function"></a>

### get_user_defined_function

Retrieves a specified function definition from the Data Catalog.

Type annotations for `session.create_client("glue").get_user_defined_function`
method.

Boto3 documentation:
[Glue.Client.get_user_defined_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_user_defined_function)

Asynchronous method. Use `await get_user_defined_function(...)` for a
synchronous call.

Arguments mapping described in
[GetUserDefinedFunctionRequestRequestTypeDef](./type_defs.md#getuserdefinedfunctionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `FunctionName`: `str` *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[GetUserDefinedFunctionResponseTypeDef](./type_defs.md#getuserdefinedfunctionresponsetypedef).

<a id="get_user_defined_functions"></a>

### get_user_defined_functions

Retrieves multiple function definitions from the Data Catalog.

Type annotations for `session.create_client("glue").get_user_defined_functions`
method.

Boto3 documentation:
[Glue.Client.get_user_defined_functions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_user_defined_functions)

Asynchronous method. Use `await get_user_defined_functions(...)` for a
synchronous call.

Arguments mapping described in
[GetUserDefinedFunctionsRequestRequestTypeDef](./type_defs.md#getuserdefinedfunctionsrequestrequesttypedef).

Keyword-only arguments:

- `Pattern`: `str` *(required)*
- `CatalogId`: `str`
- `DatabaseName`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetUserDefinedFunctionsResponseTypeDef](./type_defs.md#getuserdefinedfunctionsresponsetypedef).

<a id="get_workflow"></a>

### get_workflow

Retrieves resource metadata for a workflow.

Type annotations for `session.create_client("glue").get_workflow` method.

Boto3 documentation:
[Glue.Client.get_workflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_workflow)

Asynchronous method. Use `await get_workflow(...)` for a synchronous call.

Arguments mapping described in
[GetWorkflowRequestRequestTypeDef](./type_defs.md#getworkflowrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `IncludeGraph`: `bool`

Returns a `Coroutine` for
[GetWorkflowResponseTypeDef](./type_defs.md#getworkflowresponsetypedef).

<a id="get_workflow_run"></a>

### get_workflow_run

Retrieves the metadata for a given workflow run.

Type annotations for `session.create_client("glue").get_workflow_run` method.

Boto3 documentation:
[Glue.Client.get_workflow_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_workflow_run)

Asynchronous method. Use `await get_workflow_run(...)` for a synchronous call.

Arguments mapping described in
[GetWorkflowRunRequestRequestTypeDef](./type_defs.md#getworkflowrunrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `RunId`: `str` *(required)*
- `IncludeGraph`: `bool`

Returns a `Coroutine` for
[GetWorkflowRunResponseTypeDef](./type_defs.md#getworkflowrunresponsetypedef).

<a id="get_workflow_run_properties"></a>

### get_workflow_run_properties

Retrieves the workflow run properties which were set during the run.

Type annotations for
`session.create_client("glue").get_workflow_run_properties` method.

Boto3 documentation:
[Glue.Client.get_workflow_run_properties](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_workflow_run_properties)

Asynchronous method. Use `await get_workflow_run_properties(...)` for a
synchronous call.

Arguments mapping described in
[GetWorkflowRunPropertiesRequestRequestTypeDef](./type_defs.md#getworkflowrunpropertiesrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `RunId`: `str` *(required)*

Returns a `Coroutine` for
[GetWorkflowRunPropertiesResponseTypeDef](./type_defs.md#getworkflowrunpropertiesresponsetypedef).

<a id="get_workflow_runs"></a>

### get_workflow_runs

Retrieves metadata for all runs of a given workflow.

Type annotations for `session.create_client("glue").get_workflow_runs` method.

Boto3 documentation:
[Glue.Client.get_workflow_runs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_workflow_runs)

Asynchronous method. Use `await get_workflow_runs(...)` for a synchronous call.

Arguments mapping described in
[GetWorkflowRunsRequestRequestTypeDef](./type_defs.md#getworkflowrunsrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `IncludeGraph`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetWorkflowRunsResponseTypeDef](./type_defs.md#getworkflowrunsresponsetypedef).

<a id="import_catalog_to_glue"></a>

### import_catalog_to_glue

Imports an existing Amazon Athena Data Catalog to Glue.

Type annotations for `session.create_client("glue").import_catalog_to_glue`
method.

Boto3 documentation:
[Glue.Client.import_catalog_to_glue](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.import_catalog_to_glue)

Asynchronous method. Use `await import_catalog_to_glue(...)` for a synchronous
call.

Arguments mapping described in
[ImportCatalogToGlueRequestRequestTypeDef](./type_defs.md#importcatalogtogluerequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="list_blueprints"></a>

### list_blueprints

Lists all the blueprint names in an account.

Type annotations for `session.create_client("glue").list_blueprints` method.

Boto3 documentation:
[Glue.Client.list_blueprints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_blueprints)

Asynchronous method. Use `await list_blueprints(...)` for a synchronous call.

Arguments mapping described in
[ListBlueprintsRequestRequestTypeDef](./type_defs.md#listblueprintsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ListBlueprintsResponseTypeDef](./type_defs.md#listblueprintsresponsetypedef).

<a id="list_crawlers"></a>

### list_crawlers

Retrieves the names of all crawler resources in this Amazon Web Services
account, or the resources with the specified tag.

Type annotations for `session.create_client("glue").list_crawlers` method.

Boto3 documentation:
[Glue.Client.list_crawlers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_crawlers)

Asynchronous method. Use `await list_crawlers(...)` for a synchronous call.

Arguments mapping described in
[ListCrawlersRequestRequestTypeDef](./type_defs.md#listcrawlersrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ListCrawlersResponseTypeDef](./type_defs.md#listcrawlersresponsetypedef).

<a id="list_dev_endpoints"></a>

### list_dev_endpoints

Retrieves the names of all `DevEndpoint` resources in this Amazon Web Services
account, or the resources with the specified tag.

Type annotations for `session.create_client("glue").list_dev_endpoints` method.

Boto3 documentation:
[Glue.Client.list_dev_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_dev_endpoints)

Asynchronous method. Use `await list_dev_endpoints(...)` for a synchronous
call.

Arguments mapping described in
[ListDevEndpointsRequestRequestTypeDef](./type_defs.md#listdevendpointsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ListDevEndpointsResponseTypeDef](./type_defs.md#listdevendpointsresponsetypedef).

<a id="list_jobs"></a>

### list_jobs

Retrieves the names of all job resources in this Amazon Web Services account,
or the resources with the specified tag.

Type annotations for `session.create_client("glue").list_jobs` method.

Boto3 documentation:
[Glue.Client.list_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_jobs)

Asynchronous method. Use `await list_jobs(...)` for a synchronous call.

Arguments mapping described in
[ListJobsRequestRequestTypeDef](./type_defs.md#listjobsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ListJobsResponseTypeDef](./type_defs.md#listjobsresponsetypedef).

<a id="list_ml_transforms"></a>

### list_ml_transforms

Retrieves a sortable, filterable list of existing Glue machine learning
transforms in this Amazon Web Services account, or the resources with the
specified tag.

Type annotations for `session.create_client("glue").list_ml_transforms` method.

Boto3 documentation:
[Glue.Client.list_ml_transforms](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_ml_transforms)

Asynchronous method. Use `await list_ml_transforms(...)` for a synchronous
call.

Arguments mapping described in
[ListMLTransformsRequestRequestTypeDef](./type_defs.md#listmltransformsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filter`:
  [TransformFilterCriteriaTypeDef](./type_defs.md#transformfiltercriteriatypedef)
- `Sort`:
  [TransformSortCriteriaTypeDef](./type_defs.md#transformsortcriteriatypedef)
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ListMLTransformsResponseTypeDef](./type_defs.md#listmltransformsresponsetypedef).

<a id="list_registries"></a>

### list_registries

Returns a list of registries that you have created, with minimal registry
information.

Type annotations for `session.create_client("glue").list_registries` method.

Boto3 documentation:
[Glue.Client.list_registries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_registries)

Asynchronous method. Use `await list_registries(...)` for a synchronous call.

Arguments mapping described in
[ListRegistriesInputRequestTypeDef](./type_defs.md#listregistriesinputrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListRegistriesResponseTypeDef](./type_defs.md#listregistriesresponsetypedef).

<a id="list_schema_versions"></a>

### list_schema_versions

Returns a list of schema versions that you have created, with minimal
information.

Type annotations for `session.create_client("glue").list_schema_versions`
method.

Boto3 documentation:
[Glue.Client.list_schema_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_schema_versions)

Asynchronous method. Use `await list_schema_versions(...)` for a synchronous
call.

Arguments mapping described in
[ListSchemaVersionsInputRequestTypeDef](./type_defs.md#listschemaversionsinputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListSchemaVersionsResponseTypeDef](./type_defs.md#listschemaversionsresponsetypedef).

<a id="list_schemas"></a>

### list_schemas

Returns a list of schemas with minimal details.

Type annotations for `session.create_client("glue").list_schemas` method.

Boto3 documentation:
[Glue.Client.list_schemas](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_schemas)

Asynchronous method. Use `await list_schemas(...)` for a synchronous call.

Arguments mapping described in
[ListSchemasInputRequestTypeDef](./type_defs.md#listschemasinputrequesttypedef).

Keyword-only arguments:

- `RegistryId`: [RegistryIdTypeDef](./type_defs.md#registryidtypedef)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListSchemasResponseTypeDef](./type_defs.md#listschemasresponsetypedef).

<a id="list_triggers"></a>

### list_triggers

Retrieves the names of all trigger resources in this Amazon Web Services
account, or the resources with the specified tag.

Type annotations for `session.create_client("glue").list_triggers` method.

Boto3 documentation:
[Glue.Client.list_triggers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_triggers)

Asynchronous method. Use `await list_triggers(...)` for a synchronous call.

Arguments mapping described in
[ListTriggersRequestRequestTypeDef](./type_defs.md#listtriggersrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `DependentJobName`: `str`
- `MaxResults`: `int`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ListTriggersResponseTypeDef](./type_defs.md#listtriggersresponsetypedef).

<a id="list_workflows"></a>

### list_workflows

Lists names of workflows created in the account.

Type annotations for `session.create_client("glue").list_workflows` method.

Boto3 documentation:
[Glue.Client.list_workflows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_workflows)

Asynchronous method. Use `await list_workflows(...)` for a synchronous call.

Arguments mapping described in
[ListWorkflowsRequestRequestTypeDef](./type_defs.md#listworkflowsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListWorkflowsResponseTypeDef](./type_defs.md#listworkflowsresponsetypedef).

<a id="put_data_catalog_encryption_settings"></a>

### put_data_catalog_encryption_settings

Sets the security configuration for a specified catalog.

Type annotations for
`session.create_client("glue").put_data_catalog_encryption_settings` method.

Boto3 documentation:
[Glue.Client.put_data_catalog_encryption_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.put_data_catalog_encryption_settings)

Asynchronous method. Use `await put_data_catalog_encryption_settings(...)` for
a synchronous call.

Arguments mapping described in
[PutDataCatalogEncryptionSettingsRequestRequestTypeDef](./type_defs.md#putdatacatalogencryptionsettingsrequestrequesttypedef).

Keyword-only arguments:

- `DataCatalogEncryptionSettings`:
  [DataCatalogEncryptionSettingsTypeDef](./type_defs.md#datacatalogencryptionsettingstypedef)
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put_resource_policy"></a>

### put_resource_policy

Sets the Data Catalog resource policy for access control.

Type annotations for `session.create_client("glue").put_resource_policy`
method.

Boto3 documentation:
[Glue.Client.put_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.put_resource_policy)

Asynchronous method. Use `await put_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutResourcePolicyRequestRequestTypeDef](./type_defs.md#putresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyInJson`: `str` *(required)*
- `ResourceArn`: `str`
- `PolicyHashCondition`: `str`
- `PolicyExistsCondition`:
  [ExistConditionType](./literals.md#existconditiontype)
- `EnableHybrid`:
  [EnableHybridValuesType](./literals.md#enablehybridvaluestype)

Returns a `Coroutine` for
[PutResourcePolicyResponseTypeDef](./type_defs.md#putresourcepolicyresponsetypedef).

<a id="put_schema_version_metadata"></a>

### put_schema_version_metadata

Puts the metadata key value pair for a specified schema version ID.

Type annotations for
`session.create_client("glue").put_schema_version_metadata` method.

Boto3 documentation:
[Glue.Client.put_schema_version_metadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.put_schema_version_metadata)

Asynchronous method. Use `await put_schema_version_metadata(...)` for a
synchronous call.

Arguments mapping described in
[PutSchemaVersionMetadataInputRequestTypeDef](./type_defs.md#putschemaversionmetadatainputrequesttypedef).

Keyword-only arguments:

- `MetadataKeyValue`:
  [MetadataKeyValuePairTypeDef](./type_defs.md#metadatakeyvaluepairtypedef)
  *(required)*
- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef)
- `SchemaVersionNumber`:
  [SchemaVersionNumberTypeDef](./type_defs.md#schemaversionnumbertypedef)
- `SchemaVersionId`: `str`

Returns a `Coroutine` for
[PutSchemaVersionMetadataResponseTypeDef](./type_defs.md#putschemaversionmetadataresponsetypedef).

<a id="put_workflow_run_properties"></a>

### put_workflow_run_properties

Puts the specified workflow run properties for the given workflow run.

Type annotations for
`session.create_client("glue").put_workflow_run_properties` method.

Boto3 documentation:
[Glue.Client.put_workflow_run_properties](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.put_workflow_run_properties)

Asynchronous method. Use `await put_workflow_run_properties(...)` for a
synchronous call.

Arguments mapping described in
[PutWorkflowRunPropertiesRequestRequestTypeDef](./type_defs.md#putworkflowrunpropertiesrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `RunId`: `str` *(required)*
- `RunProperties`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="query_schema_version_metadata"></a>

### query_schema_version_metadata

Queries for the schema version metadata information.

Type annotations for
`session.create_client("glue").query_schema_version_metadata` method.

Boto3 documentation:
[Glue.Client.query_schema_version_metadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.query_schema_version_metadata)

Asynchronous method. Use `await query_schema_version_metadata(...)` for a
synchronous call.

Arguments mapping described in
[QuerySchemaVersionMetadataInputRequestTypeDef](./type_defs.md#queryschemaversionmetadatainputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef)
- `SchemaVersionNumber`:
  [SchemaVersionNumberTypeDef](./type_defs.md#schemaversionnumbertypedef)
- `SchemaVersionId`: `str`
- `MetadataList`:
  `Sequence`\[[MetadataKeyValuePairTypeDef](./type_defs.md#metadatakeyvaluepairtypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[QuerySchemaVersionMetadataResponseTypeDef](./type_defs.md#queryschemaversionmetadataresponsetypedef).

<a id="register_schema_version"></a>

### register_schema_version

Adds a new version to the existing schema.

Type annotations for `session.create_client("glue").register_schema_version`
method.

Boto3 documentation:
[Glue.Client.register_schema_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.register_schema_version)

Asynchronous method. Use `await register_schema_version(...)` for a synchronous
call.

Arguments mapping described in
[RegisterSchemaVersionInputRequestTypeDef](./type_defs.md#registerschemaversioninputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*
- `SchemaDefinition`: `str` *(required)*

Returns a `Coroutine` for
[RegisterSchemaVersionResponseTypeDef](./type_defs.md#registerschemaversionresponsetypedef).

<a id="remove_schema_version_metadata"></a>

### remove_schema_version_metadata

Removes a key value pair from the schema version metadata for the specified
schema version ID.

Type annotations for
`session.create_client("glue").remove_schema_version_metadata` method.

Boto3 documentation:
[Glue.Client.remove_schema_version_metadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.remove_schema_version_metadata)

Asynchronous method. Use `await remove_schema_version_metadata(...)` for a
synchronous call.

Arguments mapping described in
[RemoveSchemaVersionMetadataInputRequestTypeDef](./type_defs.md#removeschemaversionmetadatainputrequesttypedef).

Keyword-only arguments:

- `MetadataKeyValue`:
  [MetadataKeyValuePairTypeDef](./type_defs.md#metadatakeyvaluepairtypedef)
  *(required)*
- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef)
- `SchemaVersionNumber`:
  [SchemaVersionNumberTypeDef](./type_defs.md#schemaversionnumbertypedef)
- `SchemaVersionId`: `str`

Returns a `Coroutine` for
[RemoveSchemaVersionMetadataResponseTypeDef](./type_defs.md#removeschemaversionmetadataresponsetypedef).

<a id="reset_job_bookmark"></a>

### reset_job_bookmark

Resets a bookmark entry.

Type annotations for `session.create_client("glue").reset_job_bookmark` method.

Boto3 documentation:
[Glue.Client.reset_job_bookmark](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.reset_job_bookmark)

Asynchronous method. Use `await reset_job_bookmark(...)` for a synchronous
call.

Arguments mapping described in
[ResetJobBookmarkRequestRequestTypeDef](./type_defs.md#resetjobbookmarkrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*
- `RunId`: `str`

Returns a `Coroutine` for
[ResetJobBookmarkResponseTypeDef](./type_defs.md#resetjobbookmarkresponsetypedef).

<a id="resume_workflow_run"></a>

### resume_workflow_run

Restarts selected nodes of a previous partially completed workflow run and
resumes the workflow run.

Type annotations for `session.create_client("glue").resume_workflow_run`
method.

Boto3 documentation:
[Glue.Client.resume_workflow_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.resume_workflow_run)

Asynchronous method. Use `await resume_workflow_run(...)` for a synchronous
call.

Arguments mapping described in
[ResumeWorkflowRunRequestRequestTypeDef](./type_defs.md#resumeworkflowrunrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `RunId`: `str` *(required)*
- `NodeIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[ResumeWorkflowRunResponseTypeDef](./type_defs.md#resumeworkflowrunresponsetypedef).

<a id="search_tables"></a>

### search_tables

Searches a set of tables based on properties in the table metadata as well as
on the parent database.

Type annotations for `session.create_client("glue").search_tables` method.

Boto3 documentation:
[Glue.Client.search_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.search_tables)

Asynchronous method. Use `await search_tables(...)` for a synchronous call.

Arguments mapping described in
[SearchTablesRequestRequestTypeDef](./type_defs.md#searchtablesrequestrequesttypedef).

Keyword-only arguments:

- `CatalogId`: `str`
- `NextToken`: `str`
- `Filters`:
  `Sequence`\[[PropertyPredicateTypeDef](./type_defs.md#propertypredicatetypedef)\]
- `SearchText`: `str`
- `SortCriteria`:
  `Sequence`\[[SortCriterionTypeDef](./type_defs.md#sortcriteriontypedef)\]
- `MaxResults`: `int`
- `ResourceShareType`:
  [ResourceShareTypeType](./literals.md#resourcesharetypetype)

Returns a `Coroutine` for
[SearchTablesResponseTypeDef](./type_defs.md#searchtablesresponsetypedef).

<a id="start_blueprint_run"></a>

### start_blueprint_run

Starts a new run of the specified blueprint.

Type annotations for `session.create_client("glue").start_blueprint_run`
method.

Boto3 documentation:
[Glue.Client.start_blueprint_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_blueprint_run)

Asynchronous method. Use `await start_blueprint_run(...)` for a synchronous
call.

Arguments mapping described in
[StartBlueprintRunRequestRequestTypeDef](./type_defs.md#startblueprintrunrequestrequesttypedef).

Keyword-only arguments:

- `BlueprintName`: `str` *(required)*
- `RoleArn`: `str` *(required)*
- `Parameters`: `str`

Returns a `Coroutine` for
[StartBlueprintRunResponseTypeDef](./type_defs.md#startblueprintrunresponsetypedef).

<a id="start_crawler"></a>

### start_crawler

Starts a crawl using the specified crawler, regardless of what is scheduled.

Type annotations for `session.create_client("glue").start_crawler` method.

Boto3 documentation:
[Glue.Client.start_crawler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_crawler)

Asynchronous method. Use `await start_crawler(...)` for a synchronous call.

Arguments mapping described in
[StartCrawlerRequestRequestTypeDef](./type_defs.md#startcrawlerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="start_crawler_schedule"></a>

### start_crawler_schedule

Changes the schedule state of the specified crawler to `SCHEDULED` , unless the
crawler is already running or the schedule state is already `SCHEDULED` .

Type annotations for `session.create_client("glue").start_crawler_schedule`
method.

Boto3 documentation:
[Glue.Client.start_crawler_schedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_crawler_schedule)

Asynchronous method. Use `await start_crawler_schedule(...)` for a synchronous
call.

Arguments mapping described in
[StartCrawlerScheduleRequestRequestTypeDef](./type_defs.md#startcrawlerschedulerequestrequesttypedef).

Keyword-only arguments:

- `CrawlerName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="start_export_labels_task_run"></a>

### start_export_labels_task_run

Begins an asynchronous task to export all labeled data for a particular
transform.

Type annotations for
`session.create_client("glue").start_export_labels_task_run` method.

Boto3 documentation:
[Glue.Client.start_export_labels_task_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_export_labels_task_run)

Asynchronous method. Use `await start_export_labels_task_run(...)` for a
synchronous call.

Arguments mapping described in
[StartExportLabelsTaskRunRequestRequestTypeDef](./type_defs.md#startexportlabelstaskrunrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*
- `OutputS3Path`: `str` *(required)*

Returns a `Coroutine` for
[StartExportLabelsTaskRunResponseTypeDef](./type_defs.md#startexportlabelstaskrunresponsetypedef).

<a id="start_import_labels_task_run"></a>

### start_import_labels_task_run

Enables you to provide additional labels (examples of truth) to be used to
teach the machine learning transform and improve its quality.

Type annotations for
`session.create_client("glue").start_import_labels_task_run` method.

Boto3 documentation:
[Glue.Client.start_import_labels_task_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_import_labels_task_run)

Asynchronous method. Use `await start_import_labels_task_run(...)` for a
synchronous call.

Arguments mapping described in
[StartImportLabelsTaskRunRequestRequestTypeDef](./type_defs.md#startimportlabelstaskrunrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*
- `InputS3Path`: `str` *(required)*
- `ReplaceAllLabels`: `bool`

Returns a `Coroutine` for
[StartImportLabelsTaskRunResponseTypeDef](./type_defs.md#startimportlabelstaskrunresponsetypedef).

<a id="start_job_run"></a>

### start_job_run

Starts a job run using a job definition.

Type annotations for `session.create_client("glue").start_job_run` method.

Boto3 documentation:
[Glue.Client.start_job_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_job_run)

Asynchronous method. Use `await start_job_run(...)` for a synchronous call.

Arguments mapping described in
[StartJobRunRequestRequestTypeDef](./type_defs.md#startjobrunrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*
- `JobRunId`: `str`
- `Arguments`: `Mapping`\[`str`, `str`\]
- `AllocatedCapacity`: `int`
- `Timeout`: `int`
- `MaxCapacity`: `float`
- `SecurityConfiguration`: `str`
- `NotificationProperty`:
  [NotificationPropertyTypeDef](./type_defs.md#notificationpropertytypedef)
- `WorkerType`: [WorkerTypeType](./literals.md#workertypetype)
- `NumberOfWorkers`: `int`

Returns a `Coroutine` for
[StartJobRunResponseTypeDef](./type_defs.md#startjobrunresponsetypedef).

<a id="start_ml_evaluation_task_run"></a>

### start_ml_evaluation_task_run

Starts a task to estimate the quality of the transform.

Type annotations for
`session.create_client("glue").start_ml_evaluation_task_run` method.

Boto3 documentation:
[Glue.Client.start_ml_evaluation_task_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_ml_evaluation_task_run)

Asynchronous method. Use `await start_ml_evaluation_task_run(...)` for a
synchronous call.

Arguments mapping described in
[StartMLEvaluationTaskRunRequestRequestTypeDef](./type_defs.md#startmlevaluationtaskrunrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*

Returns a `Coroutine` for
[StartMLEvaluationTaskRunResponseTypeDef](./type_defs.md#startmlevaluationtaskrunresponsetypedef).

<a id="start_ml_labeling_set_generation_task_run"></a>

### start_ml_labeling_set_generation_task_run

Starts the active learning workflow for your machine learning transform to
improve the transform's quality by generating label sets and adding labels.

Type annotations for
`session.create_client("glue").start_ml_labeling_set_generation_task_run`
method.

Boto3 documentation:
[Glue.Client.start_ml_labeling_set_generation_task_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_ml_labeling_set_generation_task_run)

Asynchronous method. Use `await start_ml_labeling_set_generation_task_run(...)`
for a synchronous call.

Arguments mapping described in
[StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef](./type_defs.md#startmllabelingsetgenerationtaskrunrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*
- `OutputS3Path`: `str` *(required)*

Returns a `Coroutine` for
[StartMLLabelingSetGenerationTaskRunResponseTypeDef](./type_defs.md#startmllabelingsetgenerationtaskrunresponsetypedef).

<a id="start_trigger"></a>

### start_trigger

Starts an existing trigger.

Type annotations for `session.create_client("glue").start_trigger` method.

Boto3 documentation:
[Glue.Client.start_trigger](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_trigger)

Asynchronous method. Use `await start_trigger(...)` for a synchronous call.

Arguments mapping described in
[StartTriggerRequestRequestTypeDef](./type_defs.md#starttriggerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[StartTriggerResponseTypeDef](./type_defs.md#starttriggerresponsetypedef).

<a id="start_workflow_run"></a>

### start_workflow_run

Starts a new run of the specified workflow.

Type annotations for `session.create_client("glue").start_workflow_run` method.

Boto3 documentation:
[Glue.Client.start_workflow_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_workflow_run)

Asynchronous method. Use `await start_workflow_run(...)` for a synchronous
call.

Arguments mapping described in
[StartWorkflowRunRequestRequestTypeDef](./type_defs.md#startworkflowrunrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[StartWorkflowRunResponseTypeDef](./type_defs.md#startworkflowrunresponsetypedef).

<a id="stop_crawler"></a>

### stop_crawler

If the specified crawler is running, stops the crawl.

Type annotations for `session.create_client("glue").stop_crawler` method.

Boto3 documentation:
[Glue.Client.stop_crawler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_crawler)

Asynchronous method. Use `await stop_crawler(...)` for a synchronous call.

Arguments mapping described in
[StopCrawlerRequestRequestTypeDef](./type_defs.md#stopcrawlerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="stop_crawler_schedule"></a>

### stop_crawler_schedule

Sets the schedule state of the specified crawler to `NOT_SCHEDULED` , but does
not stop the crawler if it is already running.

Type annotations for `session.create_client("glue").stop_crawler_schedule`
method.

Boto3 documentation:
[Glue.Client.stop_crawler_schedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_crawler_schedule)

Asynchronous method. Use `await stop_crawler_schedule(...)` for a synchronous
call.

Arguments mapping described in
[StopCrawlerScheduleRequestRequestTypeDef](./type_defs.md#stopcrawlerschedulerequestrequesttypedef).

Keyword-only arguments:

- `CrawlerName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="stop_trigger"></a>

### stop_trigger

Stops a specified trigger.

Type annotations for `session.create_client("glue").stop_trigger` method.

Boto3 documentation:
[Glue.Client.stop_trigger](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_trigger)

Asynchronous method. Use `await stop_trigger(...)` for a synchronous call.

Arguments mapping described in
[StopTriggerRequestRequestTypeDef](./type_defs.md#stoptriggerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[StopTriggerResponseTypeDef](./type_defs.md#stoptriggerresponsetypedef).

<a id="stop_workflow_run"></a>

### stop_workflow_run

Stops the execution of the specified workflow run.

Type annotations for `session.create_client("glue").stop_workflow_run` method.

Boto3 documentation:
[Glue.Client.stop_workflow_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_workflow_run)

Asynchronous method. Use `await stop_workflow_run(...)` for a synchronous call.

Arguments mapping described in
[StopWorkflowRunRequestRequestTypeDef](./type_defs.md#stopworkflowrunrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `RunId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Adds tags to a resource.

Type annotations for `session.create_client("glue").tag_resource` method.

Boto3 documentation:
[Glue.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagsToAdd`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from a resource.

Type annotations for `session.create_client("glue").untag_resource` method.

Boto3 documentation:
[Glue.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagsToRemove`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_blueprint"></a>

### update_blueprint

Updates a registered blueprint.

Type annotations for `session.create_client("glue").update_blueprint` method.

Boto3 documentation:
[Glue.Client.update_blueprint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_blueprint)

Asynchronous method. Use `await update_blueprint(...)` for a synchronous call.

Arguments mapping described in
[UpdateBlueprintRequestRequestTypeDef](./type_defs.md#updateblueprintrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `BlueprintLocation`: `str` *(required)*
- `Description`: `str`

Returns a `Coroutine` for
[UpdateBlueprintResponseTypeDef](./type_defs.md#updateblueprintresponsetypedef).

<a id="update_classifier"></a>

### update_classifier

Modifies an existing classifier (a `GrokClassifier` , an `XMLClassifier` , a
`JsonClassifier` , or a `CsvClassifier` , depending on which field is present).

Type annotations for `session.create_client("glue").update_classifier` method.

Boto3 documentation:
[Glue.Client.update_classifier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_classifier)

Asynchronous method. Use `await update_classifier(...)` for a synchronous call.

Arguments mapping described in
[UpdateClassifierRequestRequestTypeDef](./type_defs.md#updateclassifierrequestrequesttypedef).

Keyword-only arguments:

- `GrokClassifier`:
  [UpdateGrokClassifierRequestTypeDef](./type_defs.md#updategrokclassifierrequesttypedef)
- `XMLClassifier`:
  [UpdateXMLClassifierRequestTypeDef](./type_defs.md#updatexmlclassifierrequesttypedef)
- `JsonClassifier`:
  [UpdateJsonClassifierRequestTypeDef](./type_defs.md#updatejsonclassifierrequesttypedef)
- `CsvClassifier`:
  [UpdateCsvClassifierRequestTypeDef](./type_defs.md#updatecsvclassifierrequesttypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_column_statistics_for_partition"></a>

### update_column_statistics_for_partition

Creates or updates partition statistics of columns.

Type annotations for
`session.create_client("glue").update_column_statistics_for_partition` method.

Boto3 documentation:
[Glue.Client.update_column_statistics_for_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_column_statistics_for_partition)

Asynchronous method. Use `await update_column_statistics_for_partition(...)`
for a synchronous call.

Arguments mapping described in
[UpdateColumnStatisticsForPartitionRequestRequestTypeDef](./type_defs.md#updatecolumnstatisticsforpartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionValues`: `Sequence`\[`str`\] *(required)*
- `ColumnStatisticsList`:
  `Sequence`\[[ColumnStatisticsTypeDef](./type_defs.md#columnstatisticstypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[UpdateColumnStatisticsForPartitionResponseTypeDef](./type_defs.md#updatecolumnstatisticsforpartitionresponsetypedef).

<a id="update_column_statistics_for_table"></a>

### update_column_statistics_for_table

Creates or updates table statistics of columns.

Type annotations for
`session.create_client("glue").update_column_statistics_for_table` method.

Boto3 documentation:
[Glue.Client.update_column_statistics_for_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_column_statistics_for_table)

Asynchronous method. Use `await update_column_statistics_for_table(...)` for a
synchronous call.

Arguments mapping described in
[UpdateColumnStatisticsForTableRequestRequestTypeDef](./type_defs.md#updatecolumnstatisticsfortablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `ColumnStatisticsList`:
  `Sequence`\[[ColumnStatisticsTypeDef](./type_defs.md#columnstatisticstypedef)\]
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for
[UpdateColumnStatisticsForTableResponseTypeDef](./type_defs.md#updatecolumnstatisticsfortableresponsetypedef).

<a id="update_connection"></a>

### update_connection

Updates a connection definition in the Data Catalog.

Type annotations for `session.create_client("glue").update_connection` method.

Boto3 documentation:
[Glue.Client.update_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_connection)

Asynchronous method. Use `await update_connection(...)` for a synchronous call.

Arguments mapping described in
[UpdateConnectionRequestRequestTypeDef](./type_defs.md#updateconnectionrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `ConnectionInput`:
  [ConnectionInputTypeDef](./type_defs.md#connectioninputtypedef) *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_crawler"></a>

### update_crawler

Updates a crawler.

Type annotations for `session.create_client("glue").update_crawler` method.

Boto3 documentation:
[Glue.Client.update_crawler](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_crawler)

Asynchronous method. Use `await update_crawler(...)` for a synchronous call.

Arguments mapping described in
[UpdateCrawlerRequestRequestTypeDef](./type_defs.md#updatecrawlerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Role`: `str`
- `DatabaseName`: `str`
- `Description`: `str`
- `Targets`: [CrawlerTargetsTypeDef](./type_defs.md#crawlertargetstypedef)
- `Schedule`: `str`
- `Classifiers`: `Sequence`\[`str`\]
- `TablePrefix`: `str`
- `SchemaChangePolicy`:
  [SchemaChangePolicyTypeDef](./type_defs.md#schemachangepolicytypedef)
- `RecrawlPolicy`: [RecrawlPolicyTypeDef](./type_defs.md#recrawlpolicytypedef)
- `LineageConfiguration`:
  [LineageConfigurationTypeDef](./type_defs.md#lineageconfigurationtypedef)
- `Configuration`: `str`
- `CrawlerSecurityConfiguration`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_crawler_schedule"></a>

### update_crawler_schedule

Updates the schedule of a crawler using a `cron` expression.

Type annotations for `session.create_client("glue").update_crawler_schedule`
method.

Boto3 documentation:
[Glue.Client.update_crawler_schedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_crawler_schedule)

Asynchronous method. Use `await update_crawler_schedule(...)` for a synchronous
call.

Arguments mapping described in
[UpdateCrawlerScheduleRequestRequestTypeDef](./type_defs.md#updatecrawlerschedulerequestrequesttypedef).

Keyword-only arguments:

- `CrawlerName`: `str` *(required)*
- `Schedule`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_database"></a>

### update_database

Updates an existing database definition in a Data Catalog.

Type annotations for `session.create_client("glue").update_database` method.

Boto3 documentation:
[Glue.Client.update_database](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_database)

Asynchronous method. Use `await update_database(...)` for a synchronous call.

Arguments mapping described in
[UpdateDatabaseRequestRequestTypeDef](./type_defs.md#updatedatabaserequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `DatabaseInput`: [DatabaseInputTypeDef](./type_defs.md#databaseinputtypedef)
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_dev_endpoint"></a>

### update_dev_endpoint

Updates a specified development endpoint.

Type annotations for `session.create_client("glue").update_dev_endpoint`
method.

Boto3 documentation:
[Glue.Client.update_dev_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_dev_endpoint)

Asynchronous method. Use `await update_dev_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[UpdateDevEndpointRequestRequestTypeDef](./type_defs.md#updatedevendpointrequestrequesttypedef).

Keyword-only arguments:

- `EndpointName`: `str` *(required)*
- `PublicKey`: `str`
- `AddPublicKeys`: `Sequence`\[`str`\]
- `DeletePublicKeys`: `Sequence`\[`str`\]
- `CustomLibraries`:
  [DevEndpointCustomLibrariesTypeDef](./type_defs.md#devendpointcustomlibrariestypedef)
- `UpdateEtlLibraries`: `bool`
- `DeleteArguments`: `Sequence`\[`str`\]
- `AddArguments`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_job"></a>

### update_job

Updates an existing job definition.

Type annotations for `session.create_client("glue").update_job` method.

Boto3 documentation:
[Glue.Client.update_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_job)

Asynchronous method. Use `await update_job(...)` for a synchronous call.

Arguments mapping described in
[UpdateJobRequestRequestTypeDef](./type_defs.md#updatejobrequestrequesttypedef).

Keyword-only arguments:

- `JobName`: `str` *(required)*
- `JobUpdate`: [JobUpdateTypeDef](./type_defs.md#jobupdatetypedef) *(required)*

Returns a `Coroutine` for
[UpdateJobResponseTypeDef](./type_defs.md#updatejobresponsetypedef).

<a id="update_ml_transform"></a>

### update_ml_transform

Updates an existing machine learning transform.

Type annotations for `session.create_client("glue").update_ml_transform`
method.

Boto3 documentation:
[Glue.Client.update_ml_transform](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_ml_transform)

Asynchronous method. Use `await update_ml_transform(...)` for a synchronous
call.

Arguments mapping described in
[UpdateMLTransformRequestRequestTypeDef](./type_defs.md#updatemltransformrequestrequesttypedef).

Keyword-only arguments:

- `TransformId`: `str` *(required)*
- `Name`: `str`
- `Description`: `str`
- `Parameters`:
  [TransformParametersTypeDef](./type_defs.md#transformparameterstypedef)
- `Role`: `str`
- `GlueVersion`: `str`
- `MaxCapacity`: `float`
- `WorkerType`: [WorkerTypeType](./literals.md#workertypetype)
- `NumberOfWorkers`: `int`
- `Timeout`: `int`
- `MaxRetries`: `int`

Returns a `Coroutine` for
[UpdateMLTransformResponseTypeDef](./type_defs.md#updatemltransformresponsetypedef).

<a id="update_partition"></a>

### update_partition

Updates a partition.

Type annotations for `session.create_client("glue").update_partition` method.

Boto3 documentation:
[Glue.Client.update_partition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_partition)

Asynchronous method. Use `await update_partition(...)` for a synchronous call.

Arguments mapping described in
[UpdatePartitionRequestRequestTypeDef](./type_defs.md#updatepartitionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableName`: `str` *(required)*
- `PartitionValueList`: `Sequence`\[`str`\] *(required)*
- `PartitionInput`:
  [PartitionInputTypeDef](./type_defs.md#partitioninputtypedef) *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_registry"></a>

### update_registry

Updates an existing registry which is used to hold a collection of schemas.

Type annotations for `session.create_client("glue").update_registry` method.

Boto3 documentation:
[Glue.Client.update_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_registry)

Asynchronous method. Use `await update_registry(...)` for a synchronous call.

Arguments mapping described in
[UpdateRegistryInputRequestTypeDef](./type_defs.md#updateregistryinputrequesttypedef).

Keyword-only arguments:

- `RegistryId`: [RegistryIdTypeDef](./type_defs.md#registryidtypedef)
  *(required)*
- `Description`: `str` *(required)*

Returns a `Coroutine` for
[UpdateRegistryResponseTypeDef](./type_defs.md#updateregistryresponsetypedef).

<a id="update_schema"></a>

### update_schema

Updates the description, compatibility setting, or version checkpoint for a
schema set.

Type annotations for `session.create_client("glue").update_schema` method.

Boto3 documentation:
[Glue.Client.update_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_schema)

Asynchronous method. Use `await update_schema(...)` for a synchronous call.

Arguments mapping described in
[UpdateSchemaInputRequestTypeDef](./type_defs.md#updateschemainputrequesttypedef).

Keyword-only arguments:

- `SchemaId`: [SchemaIdTypeDef](./type_defs.md#schemaidtypedef) *(required)*
- `SchemaVersionNumber`:
  [SchemaVersionNumberTypeDef](./type_defs.md#schemaversionnumbertypedef)
- `Compatibility`: [CompatibilityType](./literals.md#compatibilitytype)
- `Description`: `str`

Returns a `Coroutine` for
[UpdateSchemaResponseTypeDef](./type_defs.md#updateschemaresponsetypedef).

<a id="update_table"></a>

### update_table

Updates a metadata table in the Data Catalog.

Type annotations for `session.create_client("glue").update_table` method.

Boto3 documentation:
[Glue.Client.update_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_table)

Asynchronous method. Use `await update_table(...)` for a synchronous call.

Arguments mapping described in
[UpdateTableRequestRequestTypeDef](./type_defs.md#updatetablerequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `TableInput`: [TableInputTypeDef](./type_defs.md#tableinputtypedef)
  *(required)*
- `CatalogId`: `str`
- `SkipArchive`: `bool`
- `TransactionId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_trigger"></a>

### update_trigger

Updates a trigger definition.

Type annotations for `session.create_client("glue").update_trigger` method.

Boto3 documentation:
[Glue.Client.update_trigger](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_trigger)

Asynchronous method. Use `await update_trigger(...)` for a synchronous call.

Arguments mapping described in
[UpdateTriggerRequestRequestTypeDef](./type_defs.md#updatetriggerrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `TriggerUpdate`: [TriggerUpdateTypeDef](./type_defs.md#triggerupdatetypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateTriggerResponseTypeDef](./type_defs.md#updatetriggerresponsetypedef).

<a id="update_user_defined_function"></a>

### update_user_defined_function

Updates an existing function definition in the Data Catalog.

Type annotations for
`session.create_client("glue").update_user_defined_function` method.

Boto3 documentation:
[Glue.Client.update_user_defined_function](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_user_defined_function)

Asynchronous method. Use `await update_user_defined_function(...)` for a
synchronous call.

Arguments mapping described in
[UpdateUserDefinedFunctionRequestRequestTypeDef](./type_defs.md#updateuserdefinedfunctionrequestrequesttypedef).

Keyword-only arguments:

- `DatabaseName`: `str` *(required)*
- `FunctionName`: `str` *(required)*
- `FunctionInput`:
  [UserDefinedFunctionInputTypeDef](./type_defs.md#userdefinedfunctioninputtypedef)
  *(required)*
- `CatalogId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_workflow"></a>

### update_workflow

Updates an existing workflow.

Type annotations for `session.create_client("glue").update_workflow` method.

Boto3 documentation:
[Glue.Client.update_workflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_workflow)

Asynchronous method. Use `await update_workflow(...)` for a synchronous call.

Arguments mapping described in
[UpdateWorkflowRequestRequestTypeDef](./type_defs.md#updateworkflowrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Description`: `str`
- `DefaultRunProperties`: `Mapping`\[`str`, `str`\]
- `MaxConcurrentRuns`: `int`

Returns a `Coroutine` for
[UpdateWorkflowResponseTypeDef](./type_defs.md#updateworkflowresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("glue").__aenter__` method.

Boto3 documentation:
[Glue.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [GlueClient](#glueclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("glue").__aexit__` method.

Boto3 documentation:
[Glue.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("glue").get_paginator` method with
overloads.

- `client.get_paginator("get_classifiers")` ->
  [GetClassifiersPaginator](./paginators.md#getclassifierspaginator)
- `client.get_paginator("get_connections")` ->
  [GetConnectionsPaginator](./paginators.md#getconnectionspaginator)
- `client.get_paginator("get_crawler_metrics")` ->
  [GetCrawlerMetricsPaginator](./paginators.md#getcrawlermetricspaginator)
- `client.get_paginator("get_crawlers")` ->
  [GetCrawlersPaginator](./paginators.md#getcrawlerspaginator)
- `client.get_paginator("get_databases")` ->
  [GetDatabasesPaginator](./paginators.md#getdatabasespaginator)
- `client.get_paginator("get_dev_endpoints")` ->
  [GetDevEndpointsPaginator](./paginators.md#getdevendpointspaginator)
- `client.get_paginator("get_job_runs")` ->
  [GetJobRunsPaginator](./paginators.md#getjobrunspaginator)
- `client.get_paginator("get_jobs")` ->
  [GetJobsPaginator](./paginators.md#getjobspaginator)
- `client.get_paginator("get_partition_indexes")` ->
  [GetPartitionIndexesPaginator](./paginators.md#getpartitionindexespaginator)
- `client.get_paginator("get_partitions")` ->
  [GetPartitionsPaginator](./paginators.md#getpartitionspaginator)
- `client.get_paginator("get_resource_policies")` ->
  [GetResourcePoliciesPaginator](./paginators.md#getresourcepoliciespaginator)
- `client.get_paginator("get_security_configurations")` ->
  [GetSecurityConfigurationsPaginator](./paginators.md#getsecurityconfigurationspaginator)
- `client.get_paginator("get_table_versions")` ->
  [GetTableVersionsPaginator](./paginators.md#gettableversionspaginator)
- `client.get_paginator("get_tables")` ->
  [GetTablesPaginator](./paginators.md#gettablespaginator)
- `client.get_paginator("get_triggers")` ->
  [GetTriggersPaginator](./paginators.md#gettriggerspaginator)
- `client.get_paginator("get_user_defined_functions")` ->
  [GetUserDefinedFunctionsPaginator](./paginators.md#getuserdefinedfunctionspaginator)
- `client.get_paginator("list_registries")` ->
  [ListRegistriesPaginator](./paginators.md#listregistriespaginator)
- `client.get_paginator("list_schema_versions")` ->
  [ListSchemaVersionsPaginator](./paginators.md#listschemaversionspaginator)
- `client.get_paginator("list_schemas")` ->
  [ListSchemasPaginator](./paginators.md#listschemaspaginator)
