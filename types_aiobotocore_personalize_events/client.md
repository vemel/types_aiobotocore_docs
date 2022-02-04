<a id="personalizeeventsclient-for-aiobotocore-personalizeevents-module"></a>

# PersonalizeEventsClient for aiobotocore PersonalizeEvents module

> [Index](..) > [PersonalizeEvents](.) > PersonalizeEventsClient

Auto-generated documentation for
[PersonalizeEvents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents)
type annotations stubs module
[types-aiobotocore-personalize-events](https://pypi.org/project/types-aiobotocore-personalize-events/).

- [PersonalizeEventsClient for aiobotocore PersonalizeEvents module](#personalizeeventsclient-for-aiobotocore-personalizeevents-module)
  - [PersonalizeEventsClient](#personalizeeventsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [generate_presigned_url](#generate_presigned_url)
    - [put_events](#put_events)
    - [put_items](#put_items)
    - [put_users](#put_users)

<a id="personalizeeventsclient"></a>

## PersonalizeEventsClient

Type annotations for `aiobotocore.create_client("personalize-events")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_personalize_events.client import PersonalizeEventsClient

def get_personalize-events_client() -> PersonalizeEventsClient:
    return Session().client("personalize-events")
```

Boto3 documentation:
[PersonalizeEvents.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_personalize_events.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InvalidInputException`
- `Exceptions.ResourceInUseException`
- `Exceptions.ResourceNotFoundException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

PersonalizeEventsClient exceptions.

Type annotations for
`aiobotocore.create_client("personalize-events").exceptions` method.

Boto3 documentation:
[PersonalizeEvents.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("personalize-events").can_paginate` method.

Boto3 documentation:
[PersonalizeEvents.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("personalize-events").generate_presigned_url`
method.

Boto3 documentation:
[PersonalizeEvents.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="put_events"></a>

### put_events

Records user interaction event data.

Type annotations for
`aiobotocore.create_client("personalize-events").put_events` method.

Boto3 documentation:
[PersonalizeEvents.Client.put_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents.Client.put_events)

Asynchronous method. Use `await put_events(...)` for a synchronous call.

Arguments mapping described in
[PutEventsRequestRequestTypeDef](./type_defs.md#puteventsrequestrequesttypedef).

Keyword-only arguments:

- `trackingId`: `str` *(required)*
- `sessionId`: `str` *(required)*
- `eventList`: `Sequence`\[[EventTypeDef](./type_defs.md#eventtypedef)\]
  *(required)*
- `userId`: `str`

<a id="put_items"></a>

### put_items

Adds one or more items to an Items dataset.

Type annotations for
`aiobotocore.create_client("personalize-events").put_items` method.

Boto3 documentation:
[PersonalizeEvents.Client.put_items](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents.Client.put_items)

Asynchronous method. Use `await put_items(...)` for a synchronous call.

Arguments mapping described in
[PutItemsRequestRequestTypeDef](./type_defs.md#putitemsrequestrequesttypedef).

Keyword-only arguments:

- `datasetArn`: `str` *(required)*
- `items`: `Sequence`\[[ItemTypeDef](./type_defs.md#itemtypedef)\] *(required)*

<a id="put_users"></a>

### put_users

Adds one or more users to a Users dataset.

Type annotations for
`aiobotocore.create_client("personalize-events").put_users` method.

Boto3 documentation:
[PersonalizeEvents.Client.put_users](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents.Client.put_users)

Asynchronous method. Use `await put_users(...)` for a synchronous call.

Arguments mapping described in
[PutUsersRequestRequestTypeDef](./type_defs.md#putusersrequestrequesttypedef).

Keyword-only arguments:

- `datasetArn`: `str` *(required)*
- `users`: `Sequence`\[[UserTypeDef](./type_defs.md#usertypedef)\] *(required)*
