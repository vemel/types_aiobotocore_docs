<a id="lexruntimeserviceclient-for-aiobotocore-lexruntimeservice-module"></a>

# LexRuntimeServiceClient for aiobotocore LexRuntimeService module

> [Index](..) > [LexRuntimeService](.) > LexRuntimeServiceClient

Auto-generated documentation for
[LexRuntimeService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService)
type annotations stubs module
[types-aiobotocore-lex-runtime](https://pypi.org/project/types-aiobotocore-lex-runtime/).

- [LexRuntimeServiceClient for aiobotocore LexRuntimeService module](#lexruntimeserviceclient-for-aiobotocore-lexruntimeservice-module)
  - [LexRuntimeServiceClient](#lexruntimeserviceclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [delete_session](#delete_session)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_session](#get_session)
    - [post_content](#post_content)
    - [post_text](#post_text)
    - [put_session](#put_session)

<a id="lexruntimeserviceclient"></a>

## LexRuntimeServiceClient

Type annotations for `aiobotocore.create_client("lex-runtime")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_lex_runtime.client import LexRuntimeServiceClient

def get_lex-runtime_client() -> LexRuntimeServiceClient:
    return Session().client("lex-runtime")
```

Boto3 documentation:
[LexRuntimeService.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_lex_runtime.client import Exceptions

def handle_error(exc: Exceptions.BadGatewayException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadGatewayException`
- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.DependencyFailedException`
- `Exceptions.InternalFailureException`
- `Exceptions.LimitExceededException`
- `Exceptions.LoopDetectedException`
- `Exceptions.NotAcceptableException`
- `Exceptions.NotFoundException`
- `Exceptions.RequestTimeoutException`
- `Exceptions.UnsupportedMediaTypeException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

LexRuntimeServiceClient exceptions.

Type annotations for `aiobotocore.create_client("lex-runtime").exceptions`
method.

Boto3 documentation:
[LexRuntimeService.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("lex-runtime").can_paginate`
method.

Boto3 documentation:
[LexRuntimeService.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="delete_session"></a>

### delete_session

Removes session information for a specified bot, alias, and user ID.

Type annotations for `aiobotocore.create_client("lex-runtime").delete_session`
method.

Boto3 documentation:
[LexRuntimeService.Client.delete_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.delete_session)

Asynchronous method. Use `await delete_session(...)` for a synchronous call.

Arguments mapping described in
[DeleteSessionRequestRequestTypeDef](./type_defs.md#deletesessionrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*
- `userId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteSessionResponseTypeDef](./type_defs.md#deletesessionresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("lex-runtime").generate_presigned_url` method.

Boto3 documentation:
[LexRuntimeService.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_session"></a>

### get_session

Returns session information for a specified bot, alias, and user ID.

Type annotations for `aiobotocore.create_client("lex-runtime").get_session`
method.

Boto3 documentation:
[LexRuntimeService.Client.get_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.get_session)

Asynchronous method. Use `await get_session(...)` for a synchronous call.

Arguments mapping described in
[GetSessionRequestRequestTypeDef](./type_defs.md#getsessionrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*
- `userId`: `str` *(required)*
- `checkpointLabelFilter`: `str`

Returns a `Coroutine` for
[GetSessionResponseTypeDef](./type_defs.md#getsessionresponsetypedef).

<a id="post_content"></a>

### post_content

Sends user input (text or speech) to Amazon Lex.

Type annotations for `aiobotocore.create_client("lex-runtime").post_content`
method.

Boto3 documentation:
[LexRuntimeService.Client.post_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.post_content)

Asynchronous method. Use `await post_content(...)` for a synchronous call.

Arguments mapping described in
[PostContentRequestRequestTypeDef](./type_defs.md#postcontentrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*
- `userId`: `str` *(required)*
- `contentType`: `str` *(required)*
- `inputStream`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `sessionAttributes`: `str`
- `requestAttributes`: `str`
- `accept`: `str`
- `activeContexts`: `str`

Returns a `Coroutine` for
[PostContentResponseTypeDef](./type_defs.md#postcontentresponsetypedef).

<a id="post_text"></a>

### post_text

Sends user input to Amazon Lex.

Type annotations for `aiobotocore.create_client("lex-runtime").post_text`
method.

Boto3 documentation:
[LexRuntimeService.Client.post_text](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.post_text)

Asynchronous method. Use `await post_text(...)` for a synchronous call.

Arguments mapping described in
[PostTextRequestRequestTypeDef](./type_defs.md#posttextrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*
- `userId`: `str` *(required)*
- `inputText`: `str` *(required)*
- `sessionAttributes`: `Mapping`\[`str`, `str`\]
- `requestAttributes`: `Mapping`\[`str`, `str`\]
- `activeContexts`:
  `Sequence`\[[ActiveContextTypeDef](./type_defs.md#activecontexttypedef)\]

Returns a `Coroutine` for
[PostTextResponseTypeDef](./type_defs.md#posttextresponsetypedef).

<a id="put_session"></a>

### put_session

Creates a new session or modifies an existing session with an Amazon Lex bot.

Type annotations for `aiobotocore.create_client("lex-runtime").put_session`
method.

Boto3 documentation:
[LexRuntimeService.Client.put_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService.Client.put_session)

Asynchronous method. Use `await put_session(...)` for a synchronous call.

Arguments mapping described in
[PutSessionRequestRequestTypeDef](./type_defs.md#putsessionrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*
- `userId`: `str` *(required)*
- `sessionAttributes`: `Mapping`\[`str`, `str`\]
- `dialogAction`: [DialogActionTypeDef](./type_defs.md#dialogactiontypedef)
- `recentIntentSummaryView`:
  `Sequence`\[[IntentSummaryTypeDef](./type_defs.md#intentsummarytypedef)\]
- `accept`: `str`
- `activeContexts`:
  `Sequence`\[[ActiveContextTypeDef](./type_defs.md#activecontexttypedef)\]

Returns a `Coroutine` for
[PutSessionResponseTypeDef](./type_defs.md#putsessionresponsetypedef).
