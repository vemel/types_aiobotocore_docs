<a id="mwaaclient-for-aiobotocore-mwaa-module"></a>

# MWAAClient for aiobotocore MWAA module

> [Index](..) > [MWAA](.) > MWAAClient

Auto-generated documentation for
[MWAA](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
type annotations stubs module
[types-aiobotocore-mwaa](https://pypi.org/project/types-aiobotocore-mwaa/).

- [MWAAClient for aiobotocore MWAA module](#mwaaclient-for-aiobotocore-mwaa-module)
  - [MWAAClient](#mwaaclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_cli_token](#create_cli_token)
    - [create_environment](#create_environment)
    - [create_web_login_token](#create_web_login_token)
    - [delete_environment](#delete_environment)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_environment](#get_environment)
    - [list_environments](#list_environments)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [publish_metrics](#publish_metrics)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_environment](#update_environment)
    - [get_paginator](#get_paginator)

<a id="mwaaclient"></a>

## MWAAClient

Type annotations for `aiobotocore.create_client("mwaa")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_mwaa.client import MWAAClient

def get_mwaa_client() -> MWAAClient:
    return Session().client("mwaa")
```

Boto3 documentation:
[MWAA.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_mwaa.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

MWAAClient exceptions.

Type annotations for `aiobotocore.create_client("mwaa").exceptions` method.

Boto3 documentation:
[MWAA.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("mwaa").can_paginate` method.

Boto3 documentation:
[MWAA.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_cli_token"></a>

### create_cli_token

Create a CLI token to use Airflow CLI.

Type annotations for `aiobotocore.create_client("mwaa").create_cli_token`
method.

Boto3 documentation:
[MWAA.Client.create_cli_token](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.create_cli_token)

Asynchronous method. Use `await create_cli_token(...)` for a synchronous call.

Arguments mapping described in
[CreateCliTokenRequestRequestTypeDef](./type_defs.md#createclitokenrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[CreateCliTokenResponseTypeDef](./type_defs.md#createclitokenresponsetypedef).

<a id="create_environment"></a>

### create_environment

Creates an Amazon Managed Workflows for Apache Airflow (MWAA) environment.

Type annotations for `aiobotocore.create_client("mwaa").create_environment`
method.

Boto3 documentation:
[MWAA.Client.create_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.create_environment)

Asynchronous method. Use `await create_environment(...)` for a synchronous
call.

Arguments mapping described in
[CreateEnvironmentInputRequestTypeDef](./type_defs.md#createenvironmentinputrequesttypedef).

Keyword-only arguments:

- `DagS3Path`: `str` *(required)*
- `ExecutionRoleArn`: `str` *(required)*
- `Name`: `str` *(required)*
- `NetworkConfiguration`:
  [NetworkConfigurationTypeDef](./type_defs.md#networkconfigurationtypedef)
  *(required)*
- `SourceBucketArn`: `str` *(required)*
- `AirflowConfigurationOptions`: `Mapping`\[`str`, `str`\]
- `AirflowVersion`: `str`
- `EnvironmentClass`: `str`
- `KmsKey`: `str`
- `LoggingConfiguration`:
  [LoggingConfigurationInputTypeDef](./type_defs.md#loggingconfigurationinputtypedef)
- `MaxWorkers`: `int`
- `MinWorkers`: `int`
- `PluginsS3ObjectVersion`: `str`
- `PluginsS3Path`: `str`
- `RequirementsS3ObjectVersion`: `str`
- `RequirementsS3Path`: `str`
- `Schedulers`: `int`
- `Tags`: `Mapping`\[`str`, `str`\]
- `WebserverAccessMode`:
  [WebserverAccessModeType](./literals.md#webserveraccessmodetype)
- `WeeklyMaintenanceWindowStart`: `str`

Returns a `Coroutine` for
[CreateEnvironmentOutputTypeDef](./type_defs.md#createenvironmentoutputtypedef).

<a id="create_web_login_token"></a>

### create_web_login_token

Create a JWT token to be used to login to Airflow Web UI with claims based
Authentication.

Type annotations for `aiobotocore.create_client("mwaa").create_web_login_token`
method.

Boto3 documentation:
[MWAA.Client.create_web_login_token](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.create_web_login_token)

Asynchronous method. Use `await create_web_login_token(...)` for a synchronous
call.

Arguments mapping described in
[CreateWebLoginTokenRequestRequestTypeDef](./type_defs.md#createweblogintokenrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[CreateWebLoginTokenResponseTypeDef](./type_defs.md#createweblogintokenresponsetypedef).

<a id="delete_environment"></a>

### delete_environment

Deletes an Amazon Managed Workflows for Apache Airflow (MWAA) environment.

Type annotations for `aiobotocore.create_client("mwaa").delete_environment`
method.

Boto3 documentation:
[MWAA.Client.delete_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.delete_environment)

Asynchronous method. Use `await delete_environment(...)` for a synchronous
call.

Arguments mapping described in
[DeleteEnvironmentInputRequestTypeDef](./type_defs.md#deleteenvironmentinputrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("mwaa").generate_presigned_url`
method.

Boto3 documentation:
[MWAA.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_environment"></a>

### get_environment

Retrieves the details of an Amazon Managed Workflows for Apache Airflow (MWAA)
environment.

Type annotations for `aiobotocore.create_client("mwaa").get_environment`
method.

Boto3 documentation:
[MWAA.Client.get_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.get_environment)

Asynchronous method. Use `await get_environment(...)` for a synchronous call.

Arguments mapping described in
[GetEnvironmentInputRequestTypeDef](./type_defs.md#getenvironmentinputrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetEnvironmentOutputTypeDef](./type_defs.md#getenvironmentoutputtypedef).

<a id="list_environments"></a>

### list_environments

Lists the Amazon Managed Workflows for Apache Airflow (MWAA) environments.

Type annotations for `aiobotocore.create_client("mwaa").list_environments`
method.

Boto3 documentation:
[MWAA.Client.list_environments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.list_environments)

Asynchronous method. Use `await list_environments(...)` for a synchronous call.

Arguments mapping described in
[ListEnvironmentsInputRequestTypeDef](./type_defs.md#listenvironmentsinputrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListEnvironmentsOutputTypeDef](./type_defs.md#listenvironmentsoutputtypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the key-value tag pairs associated to the Amazon Managed Workflows for
Apache Airflow (MWAA) environment.

Type annotations for `aiobotocore.create_client("mwaa").list_tags_for_resource`
method.

Boto3 documentation:
[MWAA.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef).

<a id="publish_metrics"></a>

### publish_metrics

An operation for publishing metrics from the customers to the Ops plane.

Type annotations for `aiobotocore.create_client("mwaa").publish_metrics`
method.

Boto3 documentation:
[MWAA.Client.publish_metrics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.publish_metrics)

Asynchronous method. Use `await publish_metrics(...)` for a synchronous call.

Arguments mapping described in
[PublishMetricsInputRequestTypeDef](./type_defs.md#publishmetricsinputrequesttypedef).

Keyword-only arguments:

- `EnvironmentName`: `str` *(required)*
- `MetricData`:
  `Sequence`\[[MetricDatumTypeDef](./type_defs.md#metricdatumtypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Associates key-value tag pairs to your Amazon Managed Workflows for Apache
Airflow (MWAA) environment.

Type annotations for `aiobotocore.create_client("mwaa").tag_resource` method.

Boto3 documentation:
[MWAA.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes key-value tag pairs associated to your Amazon Managed Workflows for
Apache Airflow (MWAA) environment.

Type annotations for `aiobotocore.create_client("mwaa").untag_resource` method.

Boto3 documentation:
[MWAA.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_environment"></a>

### update_environment

Updates an Amazon Managed Workflows for Apache Airflow (MWAA) environment.

Type annotations for `aiobotocore.create_client("mwaa").update_environment`
method.

Boto3 documentation:
[MWAA.Client.update_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.update_environment)

Asynchronous method. Use `await update_environment(...)` for a synchronous
call.

Arguments mapping described in
[UpdateEnvironmentInputRequestTypeDef](./type_defs.md#updateenvironmentinputrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `AirflowConfigurationOptions`: `Mapping`\[`str`, `str`\]
- `AirflowVersion`: `str`
- `DagS3Path`: `str`
- `EnvironmentClass`: `str`
- `ExecutionRoleArn`: `str`
- `LoggingConfiguration`:
  [LoggingConfigurationInputTypeDef](./type_defs.md#loggingconfigurationinputtypedef)
- `MaxWorkers`: `int`
- `MinWorkers`: `int`
- `NetworkConfiguration`:
  [UpdateNetworkConfigurationInputTypeDef](./type_defs.md#updatenetworkconfigurationinputtypedef)
- `PluginsS3ObjectVersion`: `str`
- `PluginsS3Path`: `str`
- `RequirementsS3ObjectVersion`: `str`
- `RequirementsS3Path`: `str`
- `Schedulers`: `int`
- `SourceBucketArn`: `str`
- `WebserverAccessMode`:
  [WebserverAccessModeType](./literals.md#webserveraccessmodetype)
- `WeeklyMaintenanceWindowStart`: `str`

Returns a `Coroutine` for
[UpdateEnvironmentOutputTypeDef](./type_defs.md#updateenvironmentoutputtypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("mwaa").get_paginator` method
with overloads.

- `client.get_paginator("list_environments")` ->
  [ListEnvironmentsPaginator](./paginators.md#listenvironmentspaginator)
