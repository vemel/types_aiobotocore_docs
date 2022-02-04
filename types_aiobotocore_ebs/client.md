<a id="ebsclient-for-aiobotocore-ebs-module"></a>

# EBSClient for aiobotocore EBS module

> [Index](..) > [EBS](.) > EBSClient

Auto-generated documentation for
[EBS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS)
type annotations stubs module
[types-aiobotocore-ebs](https://pypi.org/project/types-aiobotocore-ebs/).

- [EBSClient for aiobotocore EBS module](#ebsclient-for-aiobotocore-ebs-module)
  - [EBSClient](#ebsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [complete_snapshot](#complete_snapshot)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_snapshot_block](#get_snapshot_block)
    - [list_changed_blocks](#list_changed_blocks)
    - [list_snapshot_blocks](#list_snapshot_blocks)
    - [put_snapshot_block](#put_snapshot_block)
    - [start_snapshot](#start_snapshot)

<a id="ebsclient"></a>

## EBSClient

Type annotations for `aiobotocore.create_client("ebs")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_ebs.client import EBSClient

def get_ebs_client() -> EBSClient:
    return Session().client("ebs")
```

Boto3 documentation:
[EBS.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ebs.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConcurrentLimitExceededException`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.RequestThrottledException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

EBSClient exceptions.

Type annotations for `aiobotocore.create_client("ebs").exceptions` method.

Boto3 documentation:
[EBS.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("ebs").can_paginate` method.

Boto3 documentation:
[EBS.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="complete_snapshot"></a>

### complete_snapshot

Seals and completes the snapshot after all of the required blocks of data have
been written to it.

Type annotations for `aiobotocore.create_client("ebs").complete_snapshot`
method.

Boto3 documentation:
[EBS.Client.complete_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.complete_snapshot)

Asynchronous method. Use `await complete_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CompleteSnapshotRequestRequestTypeDef](./type_defs.md#completesnapshotrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `ChangedBlocksCount`: `int` *(required)*
- `Checksum`: `str`
- `ChecksumAlgorithm`: `Literal['SHA256']` (see
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype))
- `ChecksumAggregationMethod`: `Literal['LINEAR']` (see
  [ChecksumAggregationMethodType](./literals.md#checksumaggregationmethodtype))

Returns a `Coroutine` for
[CompleteSnapshotResponseTypeDef](./type_defs.md#completesnapshotresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("ebs").generate_presigned_url`
method.

Boto3 documentation:
[EBS.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_snapshot_block"></a>

### get_snapshot_block

Returns the data in a block in an Amazon Elastic Block Store snapshot.

Type annotations for `aiobotocore.create_client("ebs").get_snapshot_block`
method.

Boto3 documentation:
[EBS.Client.get_snapshot_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.get_snapshot_block)

Asynchronous method. Use `await get_snapshot_block(...)` for a synchronous
call.

Arguments mapping described in
[GetSnapshotBlockRequestRequestTypeDef](./type_defs.md#getsnapshotblockrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `BlockIndex`: `int` *(required)*
- `BlockToken`: `str` *(required)*

Returns a `Coroutine` for
[GetSnapshotBlockResponseTypeDef](./type_defs.md#getsnapshotblockresponsetypedef).

<a id="list_changed_blocks"></a>

### list_changed_blocks

Returns information about the blocks that are different between two Amazon
Elastic Block Store snapshots of the same volume/snapshot lineage.

Type annotations for `aiobotocore.create_client("ebs").list_changed_blocks`
method.

Boto3 documentation:
[EBS.Client.list_changed_blocks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.list_changed_blocks)

Asynchronous method. Use `await list_changed_blocks(...)` for a synchronous
call.

Arguments mapping described in
[ListChangedBlocksRequestRequestTypeDef](./type_defs.md#listchangedblocksrequestrequesttypedef).

Keyword-only arguments:

- `SecondSnapshotId`: `str` *(required)*
- `FirstSnapshotId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`
- `StartingBlockIndex`: `int`

Returns a `Coroutine` for
[ListChangedBlocksResponseTypeDef](./type_defs.md#listchangedblocksresponsetypedef).

<a id="list_snapshot_blocks"></a>

### list_snapshot_blocks

Returns information about the blocks in an Amazon Elastic Block Store snapshot.

Type annotations for `aiobotocore.create_client("ebs").list_snapshot_blocks`
method.

Boto3 documentation:
[EBS.Client.list_snapshot_blocks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.list_snapshot_blocks)

Asynchronous method. Use `await list_snapshot_blocks(...)` for a synchronous
call.

Arguments mapping described in
[ListSnapshotBlocksRequestRequestTypeDef](./type_defs.md#listsnapshotblocksrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `StartingBlockIndex`: `int`

Returns a `Coroutine` for
[ListSnapshotBlocksResponseTypeDef](./type_defs.md#listsnapshotblocksresponsetypedef).

<a id="put_snapshot_block"></a>

### put_snapshot_block

Writes a block of data to a snapshot.

Type annotations for `aiobotocore.create_client("ebs").put_snapshot_block`
method.

Boto3 documentation:
[EBS.Client.put_snapshot_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.put_snapshot_block)

Asynchronous method. Use `await put_snapshot_block(...)` for a synchronous
call.

Arguments mapping described in
[PutSnapshotBlockRequestRequestTypeDef](./type_defs.md#putsnapshotblockrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `BlockIndex`: `int` *(required)*
- `BlockData`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `DataLength`: `int` *(required)*
- `Checksum`: `str` *(required)*
- `ChecksumAlgorithm`: `Literal['SHA256']` (see
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)) *(required)*
- `Progress`: `int`

Returns a `Coroutine` for
[PutSnapshotBlockResponseTypeDef](./type_defs.md#putsnapshotblockresponsetypedef).

<a id="start_snapshot"></a>

### start_snapshot

Creates a new Amazon EBS snapshot.

Type annotations for `aiobotocore.create_client("ebs").start_snapshot` method.

Boto3 documentation:
[EBS.Client.start_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS.Client.start_snapshot)

Asynchronous method. Use `await start_snapshot(...)` for a synchronous call.

Arguments mapping described in
[StartSnapshotRequestRequestTypeDef](./type_defs.md#startsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `VolumeSize`: `int` *(required)*
- `ParentSnapshotId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `Description`: `str`
- `ClientToken`: `str`
- `Encrypted`: `bool`
- `KmsKeyArn`: `str`
- `Timeout`: `int`

Returns a `Coroutine` for
[StartSnapshotResponseTypeDef](./type_defs.md#startsnapshotresponsetypedef).
