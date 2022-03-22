<a id="cognitosyncclient-for-aiobotocore-cognitosync-module"></a>

# CognitoSyncClient for aiobotocore CognitoSync module

> [Index](../README.md) > [CognitoSync](./README.md) > CognitoSyncClient

Auto-generated documentation for
[CognitoSync](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync)
type annotations stubs module
[types-aiobotocore-cognito-sync](https://pypi.org/project/types-aiobotocore-cognito-sync/).

- [CognitoSyncClient for aiobotocore CognitoSync module](#cognitosyncclient-for-aiobotocore-cognitosync-module)
  - [CognitoSyncClient](#cognitosyncclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [bulk_publish](#bulk_publish)
    - [can_paginate](#can_paginate)
    - [delete_dataset](#delete_dataset)
    - [describe_dataset](#describe_dataset)
    - [describe_identity_pool_usage](#describe_identity_pool_usage)
    - [describe_identity_usage](#describe_identity_usage)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_bulk_publish_details](#get_bulk_publish_details)
    - [get_cognito_events](#get_cognito_events)
    - [get_identity_pool_configuration](#get_identity_pool_configuration)
    - [list_datasets](#list_datasets)
    - [list_identity_pool_usage](#list_identity_pool_usage)
    - [list_records](#list_records)
    - [register_device](#register_device)
    - [set_cognito_events](#set_cognito_events)
    - [set_identity_pool_configuration](#set_identity_pool_configuration)
    - [subscribe_to_dataset](#subscribe_to_dataset)
    - [unsubscribe_from_dataset](#unsubscribe_from_dataset)
    - [update_records](#update_records)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)

<a id="cognitosyncclient"></a>

## CognitoSyncClient

Type annotations for `session.create_client("cognito-sync")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_cognito_sync.client import CognitoSyncClient

session = get_session()
async with session.create_client("cognito-sync") as client:
    client: CognitoSyncClient
```

Boto3 documentation:
[CognitoSync.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_cognito_sync.client import Exceptions

def handle_error(exc: Exceptions.AlreadyStreamedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AlreadyStreamedException`
- `Exceptions.ClientError`
- `Exceptions.ConcurrentModificationException`
- `Exceptions.DuplicateRequestException`
- `Exceptions.InternalErrorException`
- `Exceptions.InvalidConfigurationException`
- `Exceptions.InvalidLambdaFunctionOutputException`
- `Exceptions.InvalidParameterException`
- `Exceptions.LambdaThrottledException`
- `Exceptions.LimitExceededException`
- `Exceptions.NotAuthorizedException`
- `Exceptions.ResourceConflictException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.TooManyRequestsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

CognitoSyncClient exceptions.

Type annotations for `session.create_client("cognito-sync").exceptions` method.

Boto3 documentation:
[CognitoSync.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="bulk\_publish"></a>

### bulk_publish

Initiates a bulk publish of all existing datasets for an Identity Pool to the
configured stream.

Type annotations for `session.create_client("cognito-sync").bulk_publish`
method.

Boto3 documentation:
[CognitoSync.Client.bulk_publish](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.bulk_publish)

Asynchronous method. Use `await bulk_publish(...)` for a synchronous call.

Arguments mapping described in
[BulkPublishRequestRequestTypeDef](./type_defs.md#bulkpublishrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*

Returns a `Coroutine` for
[BulkPublishResponseTypeDef](./type_defs.md#bulkpublishresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("cognito-sync").can_paginate`
method.

Boto3 documentation:
[CognitoSync.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="delete\_dataset"></a>

### delete_dataset

Deletes the specific dataset.

Type annotations for `session.create_client("cognito-sync").delete_dataset`
method.

Boto3 documentation:
[CognitoSync.Client.delete_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.delete_dataset)

Asynchronous method. Use `await delete_dataset(...)` for a synchronous call.

Arguments mapping described in
[DeleteDatasetRequestRequestTypeDef](./type_defs.md#deletedatasetrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `DatasetName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteDatasetResponseTypeDef](./type_defs.md#deletedatasetresponsetypedef).

<a id="describe\_dataset"></a>

### describe_dataset

Gets meta data about a dataset by identity and dataset name.

Type annotations for `session.create_client("cognito-sync").describe_dataset`
method.

Boto3 documentation:
[CognitoSync.Client.describe_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.describe_dataset)

Asynchronous method. Use `await describe_dataset(...)` for a synchronous call.

Arguments mapping described in
[DescribeDatasetRequestRequestTypeDef](./type_defs.md#describedatasetrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `DatasetName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDatasetResponseTypeDef](./type_defs.md#describedatasetresponsetypedef).

<a id="describe\_identity\_pool\_usage"></a>

### describe_identity_pool_usage

Gets usage details (for example, data storage) about a particular identity
pool.

Type annotations for
`session.create_client("cognito-sync").describe_identity_pool_usage` method.

Boto3 documentation:
[CognitoSync.Client.describe_identity_pool_usage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.describe_identity_pool_usage)

Asynchronous method. Use `await describe_identity_pool_usage(...)` for a
synchronous call.

Arguments mapping described in
[DescribeIdentityPoolUsageRequestRequestTypeDef](./type_defs.md#describeidentitypoolusagerequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeIdentityPoolUsageResponseTypeDef](./type_defs.md#describeidentitypoolusageresponsetypedef).

<a id="describe\_identity\_usage"></a>

### describe_identity_usage

Gets usage information for an identity, including number of datasets and data
usage.

Type annotations for
`session.create_client("cognito-sync").describe_identity_usage` method.

Boto3 documentation:
[CognitoSync.Client.describe_identity_usage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.describe_identity_usage)

Asynchronous method. Use `await describe_identity_usage(...)` for a synchronous
call.

Arguments mapping described in
[DescribeIdentityUsageRequestRequestTypeDef](./type_defs.md#describeidentityusagerequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeIdentityUsageResponseTypeDef](./type_defs.md#describeidentityusageresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("cognito-sync").generate_presigned_url` method.

Boto3 documentation:
[CognitoSync.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_bulk\_publish\_details"></a>

### get_bulk_publish_details

Get the status of the last BulkPublish operation for an identity pool.

Type annotations for
`session.create_client("cognito-sync").get_bulk_publish_details` method.

Boto3 documentation:
[CognitoSync.Client.get_bulk_publish_details](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.get_bulk_publish_details)

Asynchronous method. Use `await get_bulk_publish_details(...)` for a
synchronous call.

Arguments mapping described in
[GetBulkPublishDetailsRequestRequestTypeDef](./type_defs.md#getbulkpublishdetailsrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*

Returns a `Coroutine` for
[GetBulkPublishDetailsResponseTypeDef](./type_defs.md#getbulkpublishdetailsresponsetypedef).

<a id="get\_cognito\_events"></a>

### get_cognito_events

Gets the events and the corresponding Lambda functions associated with an
identity pool.

Type annotations for `session.create_client("cognito-sync").get_cognito_events`
method.

Boto3 documentation:
[CognitoSync.Client.get_cognito_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.get_cognito_events)

Asynchronous method. Use `await get_cognito_events(...)` for a synchronous
call.

Arguments mapping described in
[GetCognitoEventsRequestRequestTypeDef](./type_defs.md#getcognitoeventsrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*

Returns a `Coroutine` for
[GetCognitoEventsResponseTypeDef](./type_defs.md#getcognitoeventsresponsetypedef).

<a id="get\_identity\_pool\_configuration"></a>

### get_identity_pool_configuration

Gets the configuration settings of an identity pool.

Type annotations for
`session.create_client("cognito-sync").get_identity_pool_configuration` method.

Boto3 documentation:
[CognitoSync.Client.get_identity_pool_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.get_identity_pool_configuration)

Asynchronous method. Use `await get_identity_pool_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetIdentityPoolConfigurationRequestRequestTypeDef](./type_defs.md#getidentitypoolconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*

Returns a `Coroutine` for
[GetIdentityPoolConfigurationResponseTypeDef](./type_defs.md#getidentitypoolconfigurationresponsetypedef).

<a id="list\_datasets"></a>

### list_datasets

Lists datasets for an identity.

Type annotations for `session.create_client("cognito-sync").list_datasets`
method.

Boto3 documentation:
[CognitoSync.Client.list_datasets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.list_datasets)

Asynchronous method. Use `await list_datasets(...)` for a synchronous call.

Arguments mapping described in
[ListDatasetsRequestRequestTypeDef](./type_defs.md#listdatasetsrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListDatasetsResponseTypeDef](./type_defs.md#listdatasetsresponsetypedef).

<a id="list\_identity\_pool\_usage"></a>

### list_identity_pool_usage

Gets a list of identity pools registered with Cognito.

Type annotations for
`session.create_client("cognito-sync").list_identity_pool_usage` method.

Boto3 documentation:
[CognitoSync.Client.list_identity_pool_usage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.list_identity_pool_usage)

Asynchronous method. Use `await list_identity_pool_usage(...)` for a
synchronous call.

Arguments mapping described in
[ListIdentityPoolUsageRequestRequestTypeDef](./type_defs.md#listidentitypoolusagerequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListIdentityPoolUsageResponseTypeDef](./type_defs.md#listidentitypoolusageresponsetypedef).

<a id="list\_records"></a>

### list_records

Gets paginated records, optionally changed after a particular sync count for a
dataset and identity.

Type annotations for `session.create_client("cognito-sync").list_records`
method.

Boto3 documentation:
[CognitoSync.Client.list_records](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.list_records)

Asynchronous method. Use `await list_records(...)` for a synchronous call.

Arguments mapping described in
[ListRecordsRequestRequestTypeDef](./type_defs.md#listrecordsrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `DatasetName`: `str` *(required)*
- `LastSyncCount`: `int`
- `NextToken`: `str`
- `MaxResults`: `int`
- `SyncSessionToken`: `str`

Returns a `Coroutine` for
[ListRecordsResponseTypeDef](./type_defs.md#listrecordsresponsetypedef).

<a id="register\_device"></a>

### register_device

Registers a device to receive push sync notifications.

Type annotations for `session.create_client("cognito-sync").register_device`
method.

Boto3 documentation:
[CognitoSync.Client.register_device](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.register_device)

Asynchronous method. Use `await register_device(...)` for a synchronous call.

Arguments mapping described in
[RegisterDeviceRequestRequestTypeDef](./type_defs.md#registerdevicerequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `Platform`: [PlatformType](./literals.md#platformtype) *(required)*
- `Token`: `str` *(required)*

Returns a `Coroutine` for
[RegisterDeviceResponseTypeDef](./type_defs.md#registerdeviceresponsetypedef).

<a id="set\_cognito\_events"></a>

### set_cognito_events

Sets the AWS Lambda function for a given event type for an identity pool.

Type annotations for `session.create_client("cognito-sync").set_cognito_events`
method.

Boto3 documentation:
[CognitoSync.Client.set_cognito_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.set_cognito_events)

Asynchronous method. Use `await set_cognito_events(...)` for a synchronous
call.

Arguments mapping described in
[SetCognitoEventsRequestRequestTypeDef](./type_defs.md#setcognitoeventsrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `Events`: `Mapping`\[`str`, `str`\] *(required)*

<a id="set\_identity\_pool\_configuration"></a>

### set_identity_pool_configuration

Sets the necessary configuration for push sync.

Type annotations for
`session.create_client("cognito-sync").set_identity_pool_configuration` method.

Boto3 documentation:
[CognitoSync.Client.set_identity_pool_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.set_identity_pool_configuration)

Asynchronous method. Use `await set_identity_pool_configuration(...)` for a
synchronous call.

Arguments mapping described in
[SetIdentityPoolConfigurationRequestRequestTypeDef](./type_defs.md#setidentitypoolconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `PushSync`: [PushSyncTypeDef](./type_defs.md#pushsynctypedef)
- `CognitoStreams`:
  [CognitoStreamsTypeDef](./type_defs.md#cognitostreamstypedef)

Returns a `Coroutine` for
[SetIdentityPoolConfigurationResponseTypeDef](./type_defs.md#setidentitypoolconfigurationresponsetypedef).

<a id="subscribe\_to\_dataset"></a>

### subscribe_to_dataset

Subscribes to receive notifications when a dataset is modified by another
device.

Type annotations for
`session.create_client("cognito-sync").subscribe_to_dataset` method.

Boto3 documentation:
[CognitoSync.Client.subscribe_to_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.subscribe_to_dataset)

Asynchronous method. Use `await subscribe_to_dataset(...)` for a synchronous
call.

Arguments mapping described in
[SubscribeToDatasetRequestRequestTypeDef](./type_defs.md#subscribetodatasetrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `DatasetName`: `str` *(required)*
- `DeviceId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="unsubscribe\_from\_dataset"></a>

### unsubscribe_from_dataset

Unsubscribes from receiving notifications when a dataset is modified by another
device.

Type annotations for
`session.create_client("cognito-sync").unsubscribe_from_dataset` method.

Boto3 documentation:
[CognitoSync.Client.unsubscribe_from_dataset](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.unsubscribe_from_dataset)

Asynchronous method. Use `await unsubscribe_from_dataset(...)` for a
synchronous call.

Arguments mapping described in
[UnsubscribeFromDatasetRequestRequestTypeDef](./type_defs.md#unsubscribefromdatasetrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `DatasetName`: `str` *(required)*
- `DeviceId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_records"></a>

### update_records

Posts updates to records and adds and deletes records for a dataset and user.

Type annotations for `session.create_client("cognito-sync").update_records`
method.

Boto3 documentation:
[CognitoSync.Client.update_records](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.update_records)

Asynchronous method. Use `await update_records(...)` for a synchronous call.

Arguments mapping described in
[UpdateRecordsRequestRequestTypeDef](./type_defs.md#updaterecordsrequestrequesttypedef).

Keyword-only arguments:

- `IdentityPoolId`: `str` *(required)*
- `IdentityId`: `str` *(required)*
- `DatasetName`: `str` *(required)*
- `SyncSessionToken`: `str` *(required)*
- `DeviceId`: `str`
- `RecordPatches`:
  `Sequence`\[[RecordPatchTypeDef](./type_defs.md#recordpatchtypedef)\]
- `ClientContext`: `str`

Returns a `Coroutine` for
[UpdateRecordsResponseTypeDef](./type_defs.md#updaterecordsresponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("cognito-sync").__aenter__` method.

Boto3 documentation:
[CognitoSync.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [CognitoSyncClient](#cognitosyncclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("cognito-sync").__aexit__` method.

Boto3 documentation:
[CognitoSync.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
