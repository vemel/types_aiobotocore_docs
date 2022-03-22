<a id="macieclient-for-aiobotocore-macie-module"></a>

# MacieClient for aiobotocore Macie module

> [Index](../README.md) > [Macie](./README.md) > MacieClient

Auto-generated documentation for
[Macie](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie)
type annotations stubs module
[types-aiobotocore-macie](https://pypi.org/project/types-aiobotocore-macie/).

- [MacieClient for aiobotocore Macie module](#macieclient-for-aiobotocore-macie-module)
  - [MacieClient](#macieclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_member_account](#associate_member_account)
    - [associate_s3_resources](#associate_s3_resources)
    - [can_paginate](#can_paginate)
    - [disassociate_member_account](#disassociate_member_account)
    - [disassociate_s3_resources](#disassociate_s3_resources)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_member_accounts](#list_member_accounts)
    - [list_s3_resources](#list_s3_resources)
    - [update_s3_resources](#update_s3_resources)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="macieclient"></a>

## MacieClient

Type annotations for `session.create_client("macie")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_macie.client import MacieClient

session = get_session()
async with session.create_client("macie") as client:
    client: MacieClient
```

Boto3 documentation:
[Macie.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_macie.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.InternalException`
- `Exceptions.InvalidInputException`
- `Exceptions.LimitExceededException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

MacieClient exceptions.

Type annotations for `session.create_client("macie").exceptions` method.

Boto3 documentation:
[Macie.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate\_member\_account"></a>

### associate_member_account

(Discontinued) Associates a specified Amazon Web Services account with Amazon
Macie Classic as a member account.

Type annotations for `session.create_client("macie").associate_member_account`
method.

Boto3 documentation:
[Macie.Client.associate_member_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.associate_member_account)

Asynchronous method. Use `await associate_member_account(...)` for a
synchronous call.

Arguments mapping described in
[AssociateMemberAccountRequestRequestTypeDef](./type_defs.md#associatememberaccountrequestrequesttypedef).

Keyword-only arguments:

- `memberAccountId`: `str` *(required)*

<a id="associate\_s3\_resources"></a>

### associate_s3_resources

(Discontinued) Associates specified S3 resources with Amazon Macie Classic for
monitoring and data classification.

Type annotations for `session.create_client("macie").associate_s3_resources`
method.

Boto3 documentation:
[Macie.Client.associate_s3_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.associate_s3_resources)

Asynchronous method. Use `await associate_s3_resources(...)` for a synchronous
call.

Arguments mapping described in
[AssociateS3ResourcesRequestRequestTypeDef](./type_defs.md#associates3resourcesrequestrequesttypedef).

Keyword-only arguments:

- `s3Resources`:
  `Sequence`\[[S3ResourceClassificationTypeDef](./type_defs.md#s3resourceclassificationtypedef)\]
  *(required)*
- `memberAccountId`: `str`

Returns a `Coroutine` for
[AssociateS3ResourcesResultTypeDef](./type_defs.md#associates3resourcesresulttypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("macie").can_paginate` method.

Boto3 documentation:
[Macie.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="disassociate\_member\_account"></a>

### disassociate_member_account

(Discontinued) Removes the specified member account from Amazon Macie Classic.

Type annotations for
`session.create_client("macie").disassociate_member_account` method.

Boto3 documentation:
[Macie.Client.disassociate_member_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.disassociate_member_account)

Asynchronous method. Use `await disassociate_member_account(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateMemberAccountRequestRequestTypeDef](./type_defs.md#disassociatememberaccountrequestrequesttypedef).

Keyword-only arguments:

- `memberAccountId`: `str` *(required)*

<a id="disassociate\_s3\_resources"></a>

### disassociate_s3_resources

(Discontinued) Removes specified S3 resources from being monitored by Amazon
Macie Classic.

Type annotations for `session.create_client("macie").disassociate_s3_resources`
method.

Boto3 documentation:
[Macie.Client.disassociate_s3_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.disassociate_s3_resources)

Asynchronous method. Use `await disassociate_s3_resources(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateS3ResourcesRequestRequestTypeDef](./type_defs.md#disassociates3resourcesrequestrequesttypedef).

Keyword-only arguments:

- `associatedS3Resources`:
  `Sequence`\[[S3ResourceTypeDef](./type_defs.md#s3resourcetypedef)\]
  *(required)*
- `memberAccountId`: `str`

Returns a `Coroutine` for
[DisassociateS3ResourcesResultTypeDef](./type_defs.md#disassociates3resourcesresulttypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("macie").generate_presigned_url`
method.

Boto3 documentation:
[Macie.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list\_member\_accounts"></a>

### list_member_accounts

(Discontinued) Lists all Amazon Macie Classic member accounts for the current
Macie Classic administrator account.

Type annotations for `session.create_client("macie").list_member_accounts`
method.

Boto3 documentation:
[Macie.Client.list_member_accounts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.list_member_accounts)

Asynchronous method. Use `await list_member_accounts(...)` for a synchronous
call.

Arguments mapping described in
[ListMemberAccountsRequestRequestTypeDef](./type_defs.md#listmemberaccountsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListMemberAccountsResultTypeDef](./type_defs.md#listmemberaccountsresulttypedef).

<a id="list\_s3\_resources"></a>

### list_s3_resources

(Discontinued) Lists all the S3 resources associated with Amazon Macie Classic.

Type annotations for `session.create_client("macie").list_s3_resources` method.

Boto3 documentation:
[Macie.Client.list_s3_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.list_s3_resources)

Asynchronous method. Use `await list_s3_resources(...)` for a synchronous call.

Arguments mapping described in
[ListS3ResourcesRequestRequestTypeDef](./type_defs.md#lists3resourcesrequestrequesttypedef).

Keyword-only arguments:

- `memberAccountId`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListS3ResourcesResultTypeDef](./type_defs.md#lists3resourcesresulttypedef).

<a id="update\_s3\_resources"></a>

### update_s3_resources

(Discontinued) Updates the classification types for the specified S3 resources.

Type annotations for `session.create_client("macie").update_s3_resources`
method.

Boto3 documentation:
[Macie.Client.update_s3_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.update_s3_resources)

Asynchronous method. Use `await update_s3_resources(...)` for a synchronous
call.

Arguments mapping described in
[UpdateS3ResourcesRequestRequestTypeDef](./type_defs.md#updates3resourcesrequestrequesttypedef).

Keyword-only arguments:

- `s3ResourcesUpdate`:
  `Sequence`\[[S3ResourceClassificationUpdateTypeDef](./type_defs.md#s3resourceclassificationupdatetypedef)\]
  *(required)*
- `memberAccountId`: `str`

Returns a `Coroutine` for
[UpdateS3ResourcesResultTypeDef](./type_defs.md#updates3resourcesresulttypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("macie").__aenter__` method.

Boto3 documentation:
[Macie.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [MacieClient](#macieclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("macie").__aexit__` method.

Boto3 documentation:
[Macie.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("macie").get_paginator` method with
overloads.

- `client.get_paginator("list_member_accounts")` ->
  [ListMemberAccountsPaginator](./paginators.md#listmemberaccountspaginator)
- `client.get_paginator("list_s3_resources")` ->
  [ListS3ResourcesPaginator](./paginators.md#lists3resourcespaginator)
