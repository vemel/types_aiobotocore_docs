<a id="sagemakerruntimeclient-for-aiobotocore-sagemakerruntime-module"></a>

# SageMakerRuntimeClient for aiobotocore SageMakerRuntime module

> [Index](..) > [SageMakerRuntime](.) > SageMakerRuntimeClient

Auto-generated documentation for
[SageMakerRuntime](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime)
type annotations stubs module
[types-aiobotocore-sagemaker-runtime](https://pypi.org/project/types-aiobotocore-sagemaker-runtime/).

- [SageMakerRuntimeClient for aiobotocore SageMakerRuntime module](#sagemakerruntimeclient-for-aiobotocore-sagemakerruntime-module)
  - [SageMakerRuntimeClient](#sagemakerruntimeclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [generate_presigned_url](#generate_presigned_url)
    - [invoke_endpoint](#invoke_endpoint)
    - [invoke_endpoint_async](#invoke_endpoint_async)

<a id="sagemakerruntimeclient"></a>

## SageMakerRuntimeClient

Type annotations for `aiobotocore.create_client("sagemaker-runtime")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_sagemaker_runtime.client import SageMakerRuntimeClient

def get_sagemaker-runtime_client() -> SageMakerRuntimeClient:
    return Session().client("sagemaker-runtime")
```

Boto3 documentation:
[SageMakerRuntime.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_sagemaker_runtime.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InternalDependencyException`
- `Exceptions.InternalFailure`
- `Exceptions.ModelError`
- `Exceptions.ModelNotReadyException`
- `Exceptions.ServiceUnavailable`
- `Exceptions.ValidationError`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

SageMakerRuntimeClient exceptions.

Type annotations for
`aiobotocore.create_client("sagemaker-runtime").exceptions` method.

Boto3 documentation:
[SageMakerRuntime.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("sagemaker-runtime").can_paginate` method.

Boto3 documentation:
[SageMakerRuntime.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("sagemaker-runtime").generate_presigned_url` method.

Boto3 documentation:
[SageMakerRuntime.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="invoke_endpoint"></a>

### invoke_endpoint

After you deploy a model into production using Amazon SageMaker hosting
services, your client applications use this API to get inferences from the
model hosted at the specified endpoint.

Type annotations for
`aiobotocore.create_client("sagemaker-runtime").invoke_endpoint` method.

Boto3 documentation:
[SageMakerRuntime.Client.invoke_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime.Client.invoke_endpoint)

Asynchronous method. Use `await invoke_endpoint(...)` for a synchronous call.

Arguments mapping described in
[InvokeEndpointInputRequestTypeDef](./type_defs.md#invokeendpointinputrequesttypedef).

Keyword-only arguments:

- `EndpointName`: `str` *(required)*
- `Body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `ContentType`: `str`
- `Accept`: `str`
- `CustomAttributes`: `str`
- `TargetModel`: `str`
- `TargetVariant`: `str`
- `TargetContainerHostname`: `str`
- `InferenceId`: `str`

Returns a `Coroutine` for
[InvokeEndpointOutputTypeDef](./type_defs.md#invokeendpointoutputtypedef).

<a id="invoke_endpoint_async"></a>

### invoke_endpoint_async

.

Type annotations for
`aiobotocore.create_client("sagemaker-runtime").invoke_endpoint_async` method.

Boto3 documentation:
[SageMakerRuntime.Client.invoke_endpoint_async](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime.Client.invoke_endpoint_async)

Asynchronous method. Use `await invoke_endpoint_async(...)` for a synchronous
call.

Arguments mapping described in
[InvokeEndpointAsyncInputRequestTypeDef](./type_defs.md#invokeendpointasyncinputrequesttypedef).

Keyword-only arguments:

- `EndpointName`: `str` *(required)*
- `InputLocation`: `str` *(required)*
- `ContentType`: `str`
- `Accept`: `str`
- `CustomAttributes`: `str`
- `InferenceId`: `str`
- `RequestTTLSeconds`: `int`

Returns a `Coroutine` for
[InvokeEndpointAsyncOutputTypeDef](./type_defs.md#invokeendpointasyncoutputtypedef).
