<a id="kinesisanalyticsv2client-for-aiobotocore-kinesisanalyticsv2-module"></a>

# KinesisAnalyticsV2Client for aiobotocore KinesisAnalyticsV2 module

> [Index](../README.md) > [KinesisAnalyticsV2](./README.md) >
> KinesisAnalyticsV2Client

Auto-generated documentation for
[KinesisAnalyticsV2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2)
type annotations stubs module
[types-aiobotocore-kinesisanalyticsv2](https://pypi.org/project/types-aiobotocore-kinesisanalyticsv2/).

- [KinesisAnalyticsV2Client for aiobotocore KinesisAnalyticsV2 module](#kinesisanalyticsv2client-for-aiobotocore-kinesisanalyticsv2-module)
  - [KinesisAnalyticsV2Client](#kinesisanalyticsv2client)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_application_cloud_watch_logging_option](#add_application_cloud_watch_logging_option)
    - [add_application_input](#add_application_input)
    - [add_application_input_processing_configuration](#add_application_input_processing_configuration)
    - [add_application_output](#add_application_output)
    - [add_application_reference_data_source](#add_application_reference_data_source)
    - [add_application_vpc_configuration](#add_application_vpc_configuration)
    - [can_paginate](#can_paginate)
    - [create_application](#create_application)
    - [create_application_presigned_url](#create_application_presigned_url)
    - [create_application_snapshot](#create_application_snapshot)
    - [delete_application](#delete_application)
    - [delete_application_cloud_watch_logging_option](#delete_application_cloud_watch_logging_option)
    - [delete_application_input_processing_configuration](#delete_application_input_processing_configuration)
    - [delete_application_output](#delete_application_output)
    - [delete_application_reference_data_source](#delete_application_reference_data_source)
    - [delete_application_snapshot](#delete_application_snapshot)
    - [delete_application_vpc_configuration](#delete_application_vpc_configuration)
    - [describe_application](#describe_application)
    - [describe_application_snapshot](#describe_application_snapshot)
    - [describe_application_version](#describe_application_version)
    - [discover_input_schema](#discover_input_schema)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_application_snapshots](#list_application_snapshots)
    - [list_application_versions](#list_application_versions)
    - [list_applications](#list_applications)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [rollback_application](#rollback_application)
    - [start_application](#start_application)
    - [stop_application](#stop_application)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_application](#update_application)
    - [update_application_maintenance_configuration](#update_application_maintenance_configuration)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="kinesisanalyticsv2client"></a>

## KinesisAnalyticsV2Client

Type annotations for `session.create_client("kinesisanalyticsv2")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_kinesisanalyticsv2.client import KinesisAnalyticsV2Client

session = get_session()
async with session.create_client("kinesisanalyticsv2") as client:
    client: KinesisAnalyticsV2Client
```

Boto3 documentation:
[KinesisAnalyticsV2.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_kinesisanalyticsv2.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.CodeValidationException`
- `Exceptions.ConcurrentModificationException`
- `Exceptions.InvalidApplicationConfigurationException`
- `Exceptions.InvalidArgumentException`
- `Exceptions.InvalidRequestException`
- `Exceptions.LimitExceededException`
- `Exceptions.ResourceInUseException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ResourceProvisionedThroughputExceededException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.TooManyTagsException`
- `Exceptions.UnableToDetectSchemaException`
- `Exceptions.UnsupportedOperationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

KinesisAnalyticsV2Client exceptions.

Type annotations for `session.create_client("kinesisanalyticsv2").exceptions`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add\_application\_cloud\_watch\_logging\_option"></a>

### add_application_cloud_watch_logging_option

Adds an Amazon CloudWatch log stream to monitor application configuration
errors.

Type annotations for
`session.create_client("kinesisanalyticsv2").add_application_cloud_watch_logging_option`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.add_application_cloud_watch_logging_option](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.add_application_cloud_watch_logging_option)

Asynchronous method. Use
`await add_application_cloud_watch_logging_option(...)` for a synchronous call.

Arguments mapping described in
[AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef](./type_defs.md#addapplicationcloudwatchloggingoptionrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CloudWatchLoggingOption`:
  [CloudWatchLoggingOptionTypeDef](./type_defs.md#cloudwatchloggingoptiontypedef)
  *(required)*
- `CurrentApplicationVersionId`: `int`
- `ConditionalToken`: `str`

Returns a `Coroutine` for
[AddApplicationCloudWatchLoggingOptionResponseTypeDef](./type_defs.md#addapplicationcloudwatchloggingoptionresponsetypedef).

<a id="add\_application\_input"></a>

### add_application_input

Adds a streaming source to your SQL-based Kinesis Data Analytics application.

Type annotations for
`session.create_client("kinesisanalyticsv2").add_application_input` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.add_application_input](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.add_application_input)

Asynchronous method. Use `await add_application_input(...)` for a synchronous
call.

Arguments mapping described in
[AddApplicationInputRequestRequestTypeDef](./type_defs.md#addapplicationinputrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*
- `Input`: [InputTypeDef](./type_defs.md#inputtypedef) *(required)*

Returns a `Coroutine` for
[AddApplicationInputResponseTypeDef](./type_defs.md#addapplicationinputresponsetypedef).

<a id="add\_application\_input\_processing\_configuration"></a>

### add_application_input_processing_configuration

Adds an InputProcessingConfiguration to a SQL-based Kinesis Data Analytics
application.

Type annotations for
`session.create_client("kinesisanalyticsv2").add_application_input_processing_configuration`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.add_application_input_processing_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.add_application_input_processing_configuration)

Asynchronous method. Use
`await add_application_input_processing_configuration(...)` for a synchronous
call.

Arguments mapping described in
[AddApplicationInputProcessingConfigurationRequestRequestTypeDef](./type_defs.md#addapplicationinputprocessingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*
- `InputId`: `str` *(required)*
- `InputProcessingConfiguration`:
  [InputProcessingConfigurationTypeDef](./type_defs.md#inputprocessingconfigurationtypedef)
  *(required)*

Returns a `Coroutine` for
[AddApplicationInputProcessingConfigurationResponseTypeDef](./type_defs.md#addapplicationinputprocessingconfigurationresponsetypedef).

<a id="add\_application\_output"></a>

### add_application_output

Adds an external destination to your SQL-based Kinesis Data Analytics
application.

Type annotations for
`session.create_client("kinesisanalyticsv2").add_application_output` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.add_application_output](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.add_application_output)

Asynchronous method. Use `await add_application_output(...)` for a synchronous
call.

Arguments mapping described in
[AddApplicationOutputRequestRequestTypeDef](./type_defs.md#addapplicationoutputrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*
- `Output`: [OutputTypeDef](./type_defs.md#outputtypedef) *(required)*

Returns a `Coroutine` for
[AddApplicationOutputResponseTypeDef](./type_defs.md#addapplicationoutputresponsetypedef).

<a id="add\_application\_reference\_data\_source"></a>

### add_application_reference_data_source

Adds a reference data source to an existing SQL-based Kinesis Data Analytics
application.

Type annotations for
`session.create_client("kinesisanalyticsv2").add_application_reference_data_source`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.add_application_reference_data_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.add_application_reference_data_source)

Asynchronous method. Use `await add_application_reference_data_source(...)` for
a synchronous call.

Arguments mapping described in
[AddApplicationReferenceDataSourceRequestRequestTypeDef](./type_defs.md#addapplicationreferencedatasourcerequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*
- `ReferenceDataSource`:
  [ReferenceDataSourceTypeDef](./type_defs.md#referencedatasourcetypedef)
  *(required)*

Returns a `Coroutine` for
[AddApplicationReferenceDataSourceResponseTypeDef](./type_defs.md#addapplicationreferencedatasourceresponsetypedef).

<a id="add\_application\_vpc\_configuration"></a>

### add_application_vpc_configuration

Adds a Virtual Private Cloud (VPC) configuration to the application.

Type annotations for
`session.create_client("kinesisanalyticsv2").add_application_vpc_configuration`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.add_application_vpc_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.add_application_vpc_configuration)

Asynchronous method. Use `await add_application_vpc_configuration(...)` for a
synchronous call.

Arguments mapping described in
[AddApplicationVpcConfigurationRequestRequestTypeDef](./type_defs.md#addapplicationvpcconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `VpcConfiguration`:
  [VpcConfigurationTypeDef](./type_defs.md#vpcconfigurationtypedef)
  *(required)*
- `CurrentApplicationVersionId`: `int`
- `ConditionalToken`: `str`

Returns a `Coroutine` for
[AddApplicationVpcConfigurationResponseTypeDef](./type_defs.md#addapplicationvpcconfigurationresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("kinesisanalyticsv2").can_paginate`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_application"></a>

### create_application

Creates a Kinesis Data Analytics application.

Type annotations for
`session.create_client("kinesisanalyticsv2").create_application` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.create_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.create_application)

Asynchronous method. Use `await create_application(...)` for a synchronous
call.

Arguments mapping described in
[CreateApplicationRequestRequestTypeDef](./type_defs.md#createapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `RuntimeEnvironment`:
  [RuntimeEnvironmentType](./literals.md#runtimeenvironmenttype) *(required)*
- `ServiceExecutionRole`: `str` *(required)*
- `ApplicationDescription`: `str`
- `ApplicationConfiguration`:
  [ApplicationConfigurationTypeDef](./type_defs.md#applicationconfigurationtypedef)
- `CloudWatchLoggingOptions`:
  `Sequence`\[[CloudWatchLoggingOptionTypeDef](./type_defs.md#cloudwatchloggingoptiontypedef)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ApplicationMode`: [ApplicationModeType](./literals.md#applicationmodetype)

Returns a `Coroutine` for
[CreateApplicationResponseTypeDef](./type_defs.md#createapplicationresponsetypedef).

<a id="create\_application\_presigned\_url"></a>

### create_application_presigned_url

Creates and returns a URL that you can use to connect to an application's
extension.

Type annotations for
`session.create_client("kinesisanalyticsv2").create_application_presigned_url`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.create_application_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.create_application_presigned_url)

Asynchronous method. Use `await create_application_presigned_url(...)` for a
synchronous call.

Arguments mapping described in
[CreateApplicationPresignedUrlRequestRequestTypeDef](./type_defs.md#createapplicationpresignedurlrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `UrlType`: [UrlTypeType](./literals.md#urltypetype) *(required)*
- `SessionExpirationDurationInSeconds`: `int`

Returns a `Coroutine` for
[CreateApplicationPresignedUrlResponseTypeDef](./type_defs.md#createapplicationpresignedurlresponsetypedef).

<a id="create\_application\_snapshot"></a>

### create_application_snapshot

Creates a snapshot of the application's state data.

Type annotations for
`session.create_client("kinesisanalyticsv2").create_application_snapshot`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.create_application_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.create_application_snapshot)

Asynchronous method. Use `await create_application_snapshot(...)` for a
synchronous call.

Arguments mapping described in
[CreateApplicationSnapshotRequestRequestTypeDef](./type_defs.md#createapplicationsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `SnapshotName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_application"></a>

### delete_application

Deletes the specified application.

Type annotations for
`session.create_client("kinesisanalyticsv2").delete_application` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.delete_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.delete_application)

Asynchronous method. Use `await delete_application(...)` for a synchronous
call.

Arguments mapping described in
[DeleteApplicationRequestRequestTypeDef](./type_defs.md#deleteapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CreateTimestamp`: `Union`\[`datetime`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_application\_cloud\_watch\_logging\_option"></a>

### delete_application_cloud_watch_logging_option

Deletes an Amazon CloudWatch log stream from an Kinesis Data Analytics
application.

Type annotations for
`session.create_client("kinesisanalyticsv2").delete_application_cloud_watch_logging_option`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.delete_application_cloud_watch_logging_option](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.delete_application_cloud_watch_logging_option)

Asynchronous method. Use
`await delete_application_cloud_watch_logging_option(...)` for a synchronous
call.

Arguments mapping described in
[DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef](./type_defs.md#deleteapplicationcloudwatchloggingoptionrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CloudWatchLoggingOptionId`: `str` *(required)*
- `CurrentApplicationVersionId`: `int`
- `ConditionalToken`: `str`

Returns a `Coroutine` for
[DeleteApplicationCloudWatchLoggingOptionResponseTypeDef](./type_defs.md#deleteapplicationcloudwatchloggingoptionresponsetypedef).

<a id="delete\_application\_input\_processing\_configuration"></a>

### delete_application_input_processing_configuration

Deletes an InputProcessingConfiguration from an input.

Type annotations for
`session.create_client("kinesisanalyticsv2").delete_application_input_processing_configuration`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.delete_application_input_processing_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.delete_application_input_processing_configuration)

Asynchronous method. Use
`await delete_application_input_processing_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef](./type_defs.md#deleteapplicationinputprocessingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*
- `InputId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteApplicationInputProcessingConfigurationResponseTypeDef](./type_defs.md#deleteapplicationinputprocessingconfigurationresponsetypedef).

<a id="delete\_application\_output"></a>

### delete_application_output

Deletes the output destination configuration from your SQL-based Kinesis Data
Analytics application's configuration.

Type annotations for
`session.create_client("kinesisanalyticsv2").delete_application_output` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.delete_application_output](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.delete_application_output)

Asynchronous method. Use `await delete_application_output(...)` for a
synchronous call.

Arguments mapping described in
[DeleteApplicationOutputRequestRequestTypeDef](./type_defs.md#deleteapplicationoutputrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*
- `OutputId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteApplicationOutputResponseTypeDef](./type_defs.md#deleteapplicationoutputresponsetypedef).

<a id="delete\_application\_reference\_data\_source"></a>

### delete_application_reference_data_source

Deletes a reference data source configuration from the specified SQL-based
Kinesis Data Analytics application's configuration.

Type annotations for
`session.create_client("kinesisanalyticsv2").delete_application_reference_data_source`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.delete_application_reference_data_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.delete_application_reference_data_source)

Asynchronous method. Use `await delete_application_reference_data_source(...)`
for a synchronous call.

Arguments mapping described in
[DeleteApplicationReferenceDataSourceRequestRequestTypeDef](./type_defs.md#deleteapplicationreferencedatasourcerequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*
- `ReferenceId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteApplicationReferenceDataSourceResponseTypeDef](./type_defs.md#deleteapplicationreferencedatasourceresponsetypedef).

<a id="delete\_application\_snapshot"></a>

### delete_application_snapshot

Deletes a snapshot of application state.

Type annotations for
`session.create_client("kinesisanalyticsv2").delete_application_snapshot`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.delete_application_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.delete_application_snapshot)

Asynchronous method. Use `await delete_application_snapshot(...)` for a
synchronous call.

Arguments mapping described in
[DeleteApplicationSnapshotRequestRequestTypeDef](./type_defs.md#deleteapplicationsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `SnapshotName`: `str` *(required)*
- `SnapshotCreationTimestamp`: `Union`\[`datetime`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_application\_vpc\_configuration"></a>

### delete_application_vpc_configuration

Removes a VPC configuration from a Kinesis Data Analytics application.

Type annotations for
`session.create_client("kinesisanalyticsv2").delete_application_vpc_configuration`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.delete_application_vpc_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.delete_application_vpc_configuration)

Asynchronous method. Use `await delete_application_vpc_configuration(...)` for
a synchronous call.

Arguments mapping described in
[DeleteApplicationVpcConfigurationRequestRequestTypeDef](./type_defs.md#deleteapplicationvpcconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `VpcConfigurationId`: `str` *(required)*
- `CurrentApplicationVersionId`: `int`
- `ConditionalToken`: `str`

Returns a `Coroutine` for
[DeleteApplicationVpcConfigurationResponseTypeDef](./type_defs.md#deleteapplicationvpcconfigurationresponsetypedef).

<a id="describe\_application"></a>

### describe_application

Returns information about a specific Kinesis Data Analytics application.

Type annotations for
`session.create_client("kinesisanalyticsv2").describe_application` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.describe_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.describe_application)

Asynchronous method. Use `await describe_application(...)` for a synchronous
call.

Arguments mapping described in
[DescribeApplicationRequestRequestTypeDef](./type_defs.md#describeapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `IncludeAdditionalDetails`: `bool`

Returns a `Coroutine` for
[DescribeApplicationResponseTypeDef](./type_defs.md#describeapplicationresponsetypedef).

<a id="describe\_application\_snapshot"></a>

### describe_application_snapshot

Returns information about a snapshot of application state data.

Type annotations for
`session.create_client("kinesisanalyticsv2").describe_application_snapshot`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.describe_application_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.describe_application_snapshot)

Asynchronous method. Use `await describe_application_snapshot(...)` for a
synchronous call.

Arguments mapping described in
[DescribeApplicationSnapshotRequestRequestTypeDef](./type_defs.md#describeapplicationsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `SnapshotName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeApplicationSnapshotResponseTypeDef](./type_defs.md#describeapplicationsnapshotresponsetypedef).

<a id="describe\_application\_version"></a>

### describe_application_version

Provides a detailed description of a specified version of the application.

Type annotations for
`session.create_client("kinesisanalyticsv2").describe_application_version`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.describe_application_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.describe_application_version)

Asynchronous method. Use `await describe_application_version(...)` for a
synchronous call.

Arguments mapping described in
[DescribeApplicationVersionRequestRequestTypeDef](./type_defs.md#describeapplicationversionrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `ApplicationVersionId`: `int` *(required)*

Returns a `Coroutine` for
[DescribeApplicationVersionResponseTypeDef](./type_defs.md#describeapplicationversionresponsetypedef).

<a id="discover\_input\_schema"></a>

### discover_input_schema

Infers a schema for a SQL-based Kinesis Data Analytics application by
evaluating sample records on the specified streaming source (Kinesis data
stream or Kinesis Data Firehose delivery stream) or Amazon S3 object.

Type annotations for
`session.create_client("kinesisanalyticsv2").discover_input_schema` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.discover_input_schema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.discover_input_schema)

Asynchronous method. Use `await discover_input_schema(...)` for a synchronous
call.

Arguments mapping described in
[DiscoverInputSchemaRequestRequestTypeDef](./type_defs.md#discoverinputschemarequestrequesttypedef).

Keyword-only arguments:

- `ServiceExecutionRole`: `str` *(required)*
- `ResourceARN`: `str`
- `InputStartingPositionConfiguration`:
  [InputStartingPositionConfigurationTypeDef](./type_defs.md#inputstartingpositionconfigurationtypedef)
- `S3Configuration`:
  [S3ConfigurationTypeDef](./type_defs.md#s3configurationtypedef)
- `InputProcessingConfiguration`:
  [InputProcessingConfigurationTypeDef](./type_defs.md#inputprocessingconfigurationtypedef)

Returns a `Coroutine` for
[DiscoverInputSchemaResponseTypeDef](./type_defs.md#discoverinputschemaresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("kinesisanalyticsv2").generate_presigned_url` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list\_application\_snapshots"></a>

### list_application_snapshots

Lists information about the current application snapshots.

Type annotations for
`session.create_client("kinesisanalyticsv2").list_application_snapshots`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.list_application_snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.list_application_snapshots)

Asynchronous method. Use `await list_application_snapshots(...)` for a
synchronous call.

Arguments mapping described in
[ListApplicationSnapshotsRequestRequestTypeDef](./type_defs.md#listapplicationsnapshotsrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `Limit`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListApplicationSnapshotsResponseTypeDef](./type_defs.md#listapplicationsnapshotsresponsetypedef).

<a id="list\_application\_versions"></a>

### list_application_versions

Lists all the versions for the specified application, including versions that
were rolled back.

Type annotations for
`session.create_client("kinesisanalyticsv2").list_application_versions` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.list_application_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.list_application_versions)

Asynchronous method. Use `await list_application_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListApplicationVersionsRequestRequestTypeDef](./type_defs.md#listapplicationversionsrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `Limit`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListApplicationVersionsResponseTypeDef](./type_defs.md#listapplicationversionsresponsetypedef).

<a id="list\_applications"></a>

### list_applications

Returns a list of Kinesis Data Analytics applications in your account.

Type annotations for
`session.create_client("kinesisanalyticsv2").list_applications` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.list_applications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.list_applications)

Asynchronous method. Use `await list_applications(...)` for a synchronous call.

Arguments mapping described in
[ListApplicationsRequestRequestTypeDef](./type_defs.md#listapplicationsrequestrequesttypedef).

Keyword-only arguments:

- `Limit`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListApplicationsResponseTypeDef](./type_defs.md#listapplicationsresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Retrieves the list of key-value tags assigned to the application.

Type annotations for
`session.create_client("kinesisanalyticsv2").list_tags_for_resource` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="rollback\_application"></a>

### rollback_application

Reverts the application to the previous running version.

Type annotations for
`session.create_client("kinesisanalyticsv2").rollback_application` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.rollback_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.rollback_application)

Asynchronous method. Use `await rollback_application(...)` for a synchronous
call.

Arguments mapping described in
[RollbackApplicationRequestRequestTypeDef](./type_defs.md#rollbackapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int` *(required)*

Returns a `Coroutine` for
[RollbackApplicationResponseTypeDef](./type_defs.md#rollbackapplicationresponsetypedef).

<a id="start\_application"></a>

### start_application

Starts the specified Kinesis Data Analytics application.

Type annotations for
`session.create_client("kinesisanalyticsv2").start_application` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.start_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.start_application)

Asynchronous method. Use `await start_application(...)` for a synchronous call.

Arguments mapping described in
[StartApplicationRequestRequestTypeDef](./type_defs.md#startapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `RunConfiguration`:
  [RunConfigurationTypeDef](./type_defs.md#runconfigurationtypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="stop\_application"></a>

### stop_application

Stops the application from processing data.

Type annotations for
`session.create_client("kinesisanalyticsv2").stop_application` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.stop_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.stop_application)

Asynchronous method. Use `await stop_application(...)` for a synchronous call.

Arguments mapping described in
[StopApplicationRequestRequestTypeDef](./type_defs.md#stopapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `Force`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag\_resource"></a>

### tag_resource

Adds one or more key-value tags to a Kinesis Data Analytics application.

Type annotations for `session.create_client("kinesisanalyticsv2").tag_resource`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Removes one or more tags from a Kinesis Data Analytics application.

Type annotations for
`session.create_client("kinesisanalyticsv2").untag_resource` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_application"></a>

### update_application

Updates an existing Kinesis Data Analytics application.

Type annotations for
`session.create_client("kinesisanalyticsv2").update_application` method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.update_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.update_application)

Asynchronous method. Use `await update_application(...)` for a synchronous
call.

Arguments mapping described in
[UpdateApplicationRequestRequestTypeDef](./type_defs.md#updateapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `CurrentApplicationVersionId`: `int`
- `ApplicationConfigurationUpdate`:
  [ApplicationConfigurationUpdateTypeDef](./type_defs.md#applicationconfigurationupdatetypedef)
- `ServiceExecutionRoleUpdate`: `str`
- `RunConfigurationUpdate`:
  [RunConfigurationUpdateTypeDef](./type_defs.md#runconfigurationupdatetypedef)
- `CloudWatchLoggingOptionUpdates`:
  `Sequence`\[[CloudWatchLoggingOptionUpdateTypeDef](./type_defs.md#cloudwatchloggingoptionupdatetypedef)\]
- `ConditionalToken`: `str`

Returns a `Coroutine` for
[UpdateApplicationResponseTypeDef](./type_defs.md#updateapplicationresponsetypedef).

<a id="update\_application\_maintenance\_configuration"></a>

### update_application_maintenance_configuration

Updates the maintenance configuration of the Kinesis Data Analytics
application.

Type annotations for
`session.create_client("kinesisanalyticsv2").update_application_maintenance_configuration`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.update_application_maintenance_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.update_application_maintenance_configuration)

Asynchronous method. Use
`await update_application_maintenance_configuration(...)` for a synchronous
call.

Arguments mapping described in
[UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef](./type_defs.md#updateapplicationmaintenanceconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `ApplicationMaintenanceConfigurationUpdate`:
  [ApplicationMaintenanceConfigurationUpdateTypeDef](./type_defs.md#applicationmaintenanceconfigurationupdatetypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateApplicationMaintenanceConfigurationResponseTypeDef](./type_defs.md#updateapplicationmaintenanceconfigurationresponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("kinesisanalyticsv2").__aenter__`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for
[KinesisAnalyticsV2Client](#kinesisanalyticsv2client).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("kinesisanalyticsv2").__aexit__`
method.

Boto3 documentation:
[KinesisAnalyticsV2.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`session.create_client("kinesisanalyticsv2").get_paginator` method with
overloads.

- `client.get_paginator("list_application_snapshots")` ->
  [ListApplicationSnapshotsPaginator](./paginators.md#listapplicationsnapshotspaginator)
- `client.get_paginator("list_applications")` ->
  [ListApplicationsPaginator](./paginators.md#listapplicationspaginator)
