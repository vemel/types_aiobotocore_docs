<a id="apigatewaymanagementapiclient-for-aiobotocore-apigatewaymanagementapi-module"></a>

# ApiGatewayManagementApiClient for aiobotocore ApiGatewayManagementApi module

> [Index](..) > [ApiGatewayManagementApi](.) > ApiGatewayManagementApiClient

Auto-generated documentation for
[ApiGatewayManagementApi](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi)
type annotations stubs module
[types-aiobotocore-apigatewaymanagementapi](https://pypi.org/project/types-aiobotocore-apigatewaymanagementapi/).

- [ApiGatewayManagementApiClient for aiobotocore ApiGatewayManagementApi module](#apigatewaymanagementapiclient-for-aiobotocore-apigatewaymanagementapi-module)
  - [ApiGatewayManagementApiClient](#apigatewaymanagementapiclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [delete_connection](#delete_connection)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_connection](#get_connection)
    - [post_to_connection](#post_to_connection)

<a id="apigatewaymanagementapiclient"></a>

## ApiGatewayManagementApiClient

Type annotations for `aiobotocore.create_client("apigatewaymanagementapi")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_apigatewaymanagementapi.client import ApiGatewayManagementApiClient

def get_apigatewaymanagementapi_client() -> ApiGatewayManagementApiClient:
    return Session().client("apigatewaymanagementapi")
```

Boto3 documentation:
[ApiGatewayManagementApi.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_apigatewaymanagementapi.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.ForbiddenException`
- `Exceptions.GoneException`
- `Exceptions.LimitExceededException`
- `Exceptions.PayloadTooLargeException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ApiGatewayManagementApiClient exceptions.

Type annotations for
`aiobotocore.create_client("apigatewaymanagementapi").exceptions` method.

Boto3 documentation:
[ApiGatewayManagementApi.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("apigatewaymanagementapi").can_paginate` method.

Boto3 documentation:
[ApiGatewayManagementApi.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="delete_connection"></a>

### delete_connection

Delete the connection with the provided id.

Type annotations for
`aiobotocore.create_client("apigatewaymanagementapi").delete_connection`
method.

Boto3 documentation:
[ApiGatewayManagementApi.Client.delete_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi.Client.delete_connection)

Asynchronous method. Use `await delete_connection(...)` for a synchronous call.

Arguments mapping described in
[DeleteConnectionRequestRequestTypeDef](./type_defs.md#deleteconnectionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionId`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("apigatewaymanagementapi").generate_presigned_url`
method.

Boto3 documentation:
[ApiGatewayManagementApi.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_connection"></a>

### get_connection

Get information about the connection with the provided id.

Type annotations for
`aiobotocore.create_client("apigatewaymanagementapi").get_connection` method.

Boto3 documentation:
[ApiGatewayManagementApi.Client.get_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi.Client.get_connection)

Asynchronous method. Use `await get_connection(...)` for a synchronous call.

Arguments mapping described in
[GetConnectionRequestRequestTypeDef](./type_defs.md#getconnectionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionId`: `str` *(required)*

Returns a `Coroutine` for
[GetConnectionResponseTypeDef](./type_defs.md#getconnectionresponsetypedef).

<a id="post_to_connection"></a>

### post_to_connection

Sends the provided data to the specified connection.

Type annotations for
`aiobotocore.create_client("apigatewaymanagementapi").post_to_connection`
method.

Boto3 documentation:
[ApiGatewayManagementApi.Client.post_to_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewaymanagementapi.html#ApiGatewayManagementApi.Client.post_to_connection)

Asynchronous method. Use `await post_to_connection(...)` for a synchronous
call.

Arguments mapping described in
[PostToConnectionRequestRequestTypeDef](./type_defs.md#posttoconnectionrequestrequesttypedef).

Keyword-only arguments:

- `Data`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `ConnectionId`: `str` *(required)*
