<a id="identitystoreclient-for-aiobotocore-identitystore-module"></a>

# IdentityStoreClient for aiobotocore IdentityStore module

> [Index](..) > [IdentityStore](.) > IdentityStoreClient

Auto-generated documentation for
[IdentityStore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore)
type annotations stubs module
[types-aiobotocore-identitystore](https://pypi.org/project/types-aiobotocore-identitystore/).

- [IdentityStoreClient for aiobotocore IdentityStore module](#identitystoreclient-for-aiobotocore-identitystore-module)
  - [IdentityStoreClient](#identitystoreclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [describe_group](#describe_group)
    - [describe_user](#describe_user)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_groups](#list_groups)
    - [list_users](#list_users)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)

<a id="identitystoreclient"></a>

## IdentityStoreClient

Type annotations for `session.create_client("identitystore")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_identitystore.client import IdentityStoreClient

session = get_session()
async with session.create_client("identitystore") as client:
    client: IdentityStoreClient
```

Boto3 documentation:
[IdentityStore.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_identitystore.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

IdentityStoreClient exceptions.

Type annotations for `session.create_client("identitystore").exceptions`
method.

Boto3 documentation:
[IdentityStore.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("identitystore").can_paginate`
method.

Boto3 documentation:
[IdentityStore.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="describe_group"></a>

### describe_group

Retrieves the group metadata and attributes from `GroupId` in an identity
store.

Type annotations for `session.create_client("identitystore").describe_group`
method.

Boto3 documentation:
[IdentityStore.Client.describe_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.describe_group)

Asynchronous method. Use `await describe_group(...)` for a synchronous call.

Arguments mapping described in
[DescribeGroupRequestRequestTypeDef](./type_defs.md#describegrouprequestrequesttypedef).

Keyword-only arguments:

- `IdentityStoreId`: `str` *(required)*
- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeGroupResponseTypeDef](./type_defs.md#describegroupresponsetypedef).

<a id="describe_user"></a>

### describe_user

Retrieves the user metadata and attributes from `UserId` in an identity store.

Type annotations for `session.create_client("identitystore").describe_user`
method.

Boto3 documentation:
[IdentityStore.Client.describe_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.describe_user)

Asynchronous method. Use `await describe_user(...)` for a synchronous call.

Arguments mapping described in
[DescribeUserRequestRequestTypeDef](./type_defs.md#describeuserrequestrequesttypedef).

Keyword-only arguments:

- `IdentityStoreId`: `str` *(required)*
- `UserId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeUserResponseTypeDef](./type_defs.md#describeuserresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("identitystore").generate_presigned_url` method.

Boto3 documentation:
[IdentityStore.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_groups"></a>

### list_groups

Lists the attribute name and value of the group that you specified in the
search.

Type annotations for `session.create_client("identitystore").list_groups`
method.

Boto3 documentation:
[IdentityStore.Client.list_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.list_groups)

Asynchronous method. Use `await list_groups(...)` for a synchronous call.

Arguments mapping described in
[ListGroupsRequestRequestTypeDef](./type_defs.md#listgroupsrequestrequesttypedef).

Keyword-only arguments:

- `IdentityStoreId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[ListGroupsResponseTypeDef](./type_defs.md#listgroupsresponsetypedef).

<a id="list_users"></a>

### list_users

Lists the attribute name and value of the user that you specified in the
search.

Type annotations for `session.create_client("identitystore").list_users`
method.

Boto3 documentation:
[IdentityStore.Client.list_users](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.list_users)

Asynchronous method. Use `await list_users(...)` for a synchronous call.

Arguments mapping described in
[ListUsersRequestRequestTypeDef](./type_defs.md#listusersrequestrequesttypedef).

Keyword-only arguments:

- `IdentityStoreId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[ListUsersResponseTypeDef](./type_defs.md#listusersresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("identitystore").__aenter__`
method.

Boto3 documentation:
[IdentityStore.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [IdentityStoreClient](#identitystoreclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("identitystore").__aexit__` method.

Boto3 documentation:
[IdentityStore.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
