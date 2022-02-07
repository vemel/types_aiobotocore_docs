<a id="dlmclient-for-aiobotocore-dlm-module"></a>

# DLMClient for aiobotocore DLM module

> [Index](..) > [DLM](.) > DLMClient

Auto-generated documentation for
[DLM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM)
type annotations stubs module
[types-aiobotocore-dlm](https://pypi.org/project/types-aiobotocore-dlm/).

- [DLMClient for aiobotocore DLM module](#dlmclient-for-aiobotocore-dlm-module)
  - [DLMClient](#dlmclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_lifecycle_policy](#create_lifecycle_policy)
    - [delete_lifecycle_policy](#delete_lifecycle_policy)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_lifecycle_policies](#get_lifecycle_policies)
    - [get_lifecycle_policy](#get_lifecycle_policy)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_lifecycle_policy](#update_lifecycle_policy)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)

<a id="dlmclient"></a>

## DLMClient

Type annotations for `session.create_client("dlm")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_dlm.client import DLMClient

session = get_session()
async with session.create_client("dlm") as client:
    client: DLMClient
```

Boto3 documentation:
[DLM.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_dlm.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InternalServerException`
- `Exceptions.InvalidRequestException`
- `Exceptions.LimitExceededException`
- `Exceptions.ResourceNotFoundException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

DLMClient exceptions.

Type annotations for `session.create_client("dlm").exceptions` method.

Boto3 documentation:
[DLM.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("dlm").can_paginate` method.

Boto3 documentation:
[DLM.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_lifecycle_policy"></a>

### create_lifecycle_policy

Creates a policy to manage the lifecycle of the specified Amazon Web Services
resources.

Type annotations for `session.create_client("dlm").create_lifecycle_policy`
method.

Boto3 documentation:
[DLM.Client.create_lifecycle_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.create_lifecycle_policy)

Asynchronous method. Use `await create_lifecycle_policy(...)` for a synchronous
call.

Arguments mapping described in
[CreateLifecyclePolicyRequestRequestTypeDef](./type_defs.md#createlifecyclepolicyrequestrequesttypedef).

Keyword-only arguments:

- `ExecutionRoleArn`: `str` *(required)*
- `Description`: `str` *(required)*
- `State`:
  [SettablePolicyStateValuesType](./literals.md#settablepolicystatevaluestype)
  *(required)*
- `PolicyDetails`: [PolicyDetailsTypeDef](./type_defs.md#policydetailstypedef)
  *(required)*
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateLifecyclePolicyResponseTypeDef](./type_defs.md#createlifecyclepolicyresponsetypedef).

<a id="delete_lifecycle_policy"></a>

### delete_lifecycle_policy

Deletes the specified lifecycle policy and halts the automated operations that
the policy specified.

Type annotations for `session.create_client("dlm").delete_lifecycle_policy`
method.

Boto3 documentation:
[DLM.Client.delete_lifecycle_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.delete_lifecycle_policy)

Asynchronous method. Use `await delete_lifecycle_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLifecyclePolicyRequestRequestTypeDef](./type_defs.md#deletelifecyclepolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("dlm").generate_presigned_url`
method.

Boto3 documentation:
[DLM.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_lifecycle_policies"></a>

### get_lifecycle_policies

Gets summary information about all or the specified data lifecycle policies.

Type annotations for `session.create_client("dlm").get_lifecycle_policies`
method.

Boto3 documentation:
[DLM.Client.get_lifecycle_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.get_lifecycle_policies)

Asynchronous method. Use `await get_lifecycle_policies(...)` for a synchronous
call.

Arguments mapping described in
[GetLifecyclePoliciesRequestRequestTypeDef](./type_defs.md#getlifecyclepoliciesrequestrequesttypedef).

Keyword-only arguments:

- `PolicyIds`: `Sequence`\[`str`\]
- `State`:
  [GettablePolicyStateValuesType](./literals.md#gettablepolicystatevaluestype)
- `ResourceTypes`:
  `Sequence`\[[ResourceTypeValuesType](./literals.md#resourcetypevaluestype)\]
- `TargetTags`: `Sequence`\[`str`\]
- `TagsToAdd`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[GetLifecyclePoliciesResponseTypeDef](./type_defs.md#getlifecyclepoliciesresponsetypedef).

<a id="get_lifecycle_policy"></a>

### get_lifecycle_policy

Gets detailed information about the specified lifecycle policy.

Type annotations for `session.create_client("dlm").get_lifecycle_policy`
method.

Boto3 documentation:
[DLM.Client.get_lifecycle_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.get_lifecycle_policy)

Asynchronous method. Use `await get_lifecycle_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetLifecyclePolicyRequestRequestTypeDef](./type_defs.md#getlifecyclepolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*

Returns a `Coroutine` for
[GetLifecyclePolicyResponseTypeDef](./type_defs.md#getlifecyclepolicyresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags for the specified resource.

Type annotations for `session.create_client("dlm").list_tags_for_resource`
method.

Boto3 documentation:
[DLM.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds the specified tags to the specified resource.

Type annotations for `session.create_client("dlm").tag_resource` method.

Boto3 documentation:
[DLM.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes the specified tags from the specified resource.

Type annotations for `session.create_client("dlm").untag_resource` method.

Boto3 documentation:
[DLM.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_lifecycle_policy"></a>

### update_lifecycle_policy

Updates the specified lifecycle policy.

Type annotations for `session.create_client("dlm").update_lifecycle_policy`
method.

Boto3 documentation:
[DLM.Client.update_lifecycle_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.update_lifecycle_policy)

Asynchronous method. Use `await update_lifecycle_policy(...)` for a synchronous
call.

Arguments mapping described in
[UpdateLifecyclePolicyRequestRequestTypeDef](./type_defs.md#updatelifecyclepolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyId`: `str` *(required)*
- `ExecutionRoleArn`: `str`
- `State`:
  [SettablePolicyStateValuesType](./literals.md#settablepolicystatevaluestype)
- `Description`: `str`
- `PolicyDetails`: [PolicyDetailsTypeDef](./type_defs.md#policydetailstypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("dlm").__aenter__` method.

Boto3 documentation:
[DLM.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [DLMClient](#dlmclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("dlm").__aexit__` method.

Boto3 documentation:
[DLM.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
