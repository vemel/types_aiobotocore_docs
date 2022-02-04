<a id="sqsclient-for-aiobotocore-sqs-module"></a>

# SQSClient for aiobotocore SQS module

> [Index](..) > [SQS](.) > SQSClient

Auto-generated documentation for
[SQS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
type annotations stubs module
[types-aiobotocore-sqs](https://pypi.org/project/types-aiobotocore-sqs/).

- [SQSClient for aiobotocore SQS module](#sqsclient-for-aiobotocore-sqs-module)
  - [SQSClient](#sqsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_permission](#add_permission)
    - [can_paginate](#can_paginate)
    - [change_message_visibility](#change_message_visibility)
    - [change_message_visibility_batch](#change_message_visibility_batch)
    - [create_queue](#create_queue)
    - [delete_message](#delete_message)
    - [delete_message_batch](#delete_message_batch)
    - [delete_queue](#delete_queue)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_queue_attributes](#get_queue_attributes)
    - [get_queue_url](#get_queue_url)
    - [list_dead_letter_source_queues](#list_dead_letter_source_queues)
    - [list_queue_tags](#list_queue_tags)
    - [list_queues](#list_queues)
    - [purge_queue](#purge_queue)
    - [receive_message](#receive_message)
    - [remove_permission](#remove_permission)
    - [send_message](#send_message)
    - [send_message_batch](#send_message_batch)
    - [set_queue_attributes](#set_queue_attributes)
    - [tag_queue](#tag_queue)
    - [untag_queue](#untag_queue)
    - [get_paginator](#get_paginator)

<a id="sqsclient"></a>

## SQSClient

Type annotations for `aiobotocore.create_client("sqs")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_sqs.client import SQSClient

def get_sqs_client() -> SQSClient:
    return Session().client("sqs")
```

Boto3 documentation:
[SQS.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_sqs.client import Exceptions

def handle_error(exc: Exceptions.BatchEntryIdsNotDistinct) -> None:
    ...
```

Exceptions:

- `Exceptions.BatchEntryIdsNotDistinct`
- `Exceptions.BatchRequestTooLong`
- `Exceptions.ClientError`
- `Exceptions.EmptyBatchRequest`
- `Exceptions.InvalidAttributeName`
- `Exceptions.InvalidBatchEntryId`
- `Exceptions.InvalidIdFormat`
- `Exceptions.InvalidMessageContents`
- `Exceptions.MessageNotInflight`
- `Exceptions.OverLimit`
- `Exceptions.PurgeQueueInProgress`
- `Exceptions.QueueDeletedRecently`
- `Exceptions.QueueDoesNotExist`
- `Exceptions.QueueNameExists`
- `Exceptions.ReceiptHandleIsInvalid`
- `Exceptions.TooManyEntriesInBatchRequest`
- `Exceptions.UnsupportedOperation`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

SQSClient exceptions.

Type annotations for `aiobotocore.create_client("sqs").exceptions` method.

Boto3 documentation:
[SQS.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add_permission"></a>

### add_permission

Adds a permission to a queue for a specific
[principal](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)\_.

Type annotations for `aiobotocore.create_client("sqs").add_permission` method.

Boto3 documentation:
[SQS.Client.add_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.add_permission)

Asynchronous method. Use `await add_permission(...)` for a synchronous call.

Arguments mapping described in
[AddPermissionRequestRequestTypeDef](./type_defs.md#addpermissionrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `Label`: `str` *(required)*
- `AWSAccountIds`: `Sequence`\[`str`\] *(required)*
- `Actions`: `Sequence`\[`str`\] *(required)*

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("sqs").can_paginate` method.

Boto3 documentation:
[SQS.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="change_message_visibility"></a>

### change_message_visibility

Changes the visibility timeout of a specified message in a queue to a new
value.

Type annotations for
`aiobotocore.create_client("sqs").change_message_visibility` method.

Boto3 documentation:
[SQS.Client.change_message_visibility](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.change_message_visibility)

Asynchronous method. Use `await change_message_visibility(...)` for a
synchronous call.

Arguments mapping described in
[ChangeMessageVisibilityRequestRequestTypeDef](./type_defs.md#changemessagevisibilityrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `ReceiptHandle`: `str` *(required)*
- `VisibilityTimeout`: `int` *(required)*

<a id="change_message_visibility_batch"></a>

### change_message_visibility_batch

Changes the visibility timeout of multiple messages.

Type annotations for
`aiobotocore.create_client("sqs").change_message_visibility_batch` method.

Boto3 documentation:
[SQS.Client.change_message_visibility_batch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.change_message_visibility_batch)

Asynchronous method. Use `await change_message_visibility_batch(...)` for a
synchronous call.

Arguments mapping described in
[ChangeMessageVisibilityBatchRequestRequestTypeDef](./type_defs.md#changemessagevisibilitybatchrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `Entries`:
  `Sequence`\[[ChangeMessageVisibilityBatchRequestEntryTypeDef](./type_defs.md#changemessagevisibilitybatchrequestentrytypedef)\]
  *(required)*

Returns a `Coroutine` for
[ChangeMessageVisibilityBatchResultTypeDef](./type_defs.md#changemessagevisibilitybatchresulttypedef).

<a id="create_queue"></a>

### create_queue

Creates a new standard or FIFO queue.

Type annotations for `aiobotocore.create_client("sqs").create_queue` method.

Boto3 documentation:
[SQS.Client.create_queue](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.create_queue)

Asynchronous method. Use `await create_queue(...)` for a synchronous call.

Arguments mapping described in
[CreateQueueRequestRequestTypeDef](./type_defs.md#createqueuerequestrequesttypedef).

Keyword-only arguments:

- `QueueName`: `str` *(required)*
- `Attributes`:
  `Mapping`\[[QueueAttributeNameType](./literals.md#queueattributenametype),
  `str`\]
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateQueueResultTypeDef](./type_defs.md#createqueueresulttypedef).

<a id="delete_message"></a>

### delete_message

Deletes the specified message from the specified queue.

Type annotations for `aiobotocore.create_client("sqs").delete_message` method.

Boto3 documentation:
[SQS.Client.delete_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.delete_message)

Asynchronous method. Use `await delete_message(...)` for a synchronous call.

Arguments mapping described in
[DeleteMessageRequestRequestTypeDef](./type_defs.md#deletemessagerequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `ReceiptHandle`: `str` *(required)*

<a id="delete_message_batch"></a>

### delete_message_batch

Deletes up to ten messages from the specified queue.

Type annotations for `aiobotocore.create_client("sqs").delete_message_batch`
method.

Boto3 documentation:
[SQS.Client.delete_message_batch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.delete_message_batch)

Asynchronous method. Use `await delete_message_batch(...)` for a synchronous
call.

Arguments mapping described in
[DeleteMessageBatchRequestRequestTypeDef](./type_defs.md#deletemessagebatchrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `Entries`:
  `Sequence`\[[DeleteMessageBatchRequestEntryTypeDef](./type_defs.md#deletemessagebatchrequestentrytypedef)\]
  *(required)*

Returns a `Coroutine` for
[DeleteMessageBatchResultTypeDef](./type_defs.md#deletemessagebatchresulttypedef).

<a id="delete_queue"></a>

### delete_queue

Deletes the queue specified by the `QueueUrl` , regardless of the queue's
contents.

Type annotations for `aiobotocore.create_client("sqs").delete_queue` method.

Boto3 documentation:
[SQS.Client.delete_queue](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.delete_queue)

Asynchronous method. Use `await delete_queue(...)` for a synchronous call.

Arguments mapping described in
[DeleteQueueRequestRequestTypeDef](./type_defs.md#deletequeuerequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("sqs").generate_presigned_url`
method.

Boto3 documentation:
[SQS.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_queue_attributes"></a>

### get_queue_attributes

Gets attributes for the specified queue.

Type annotations for `aiobotocore.create_client("sqs").get_queue_attributes`
method.

Boto3 documentation:
[SQS.Client.get_queue_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.get_queue_attributes)

Asynchronous method. Use `await get_queue_attributes(...)` for a synchronous
call.

Arguments mapping described in
[GetQueueAttributesRequestRequestTypeDef](./type_defs.md#getqueueattributesrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `AttributeNames`:
  `Sequence`\[[QueueAttributeNameType](./literals.md#queueattributenametype)\]

Returns a `Coroutine` for
[GetQueueAttributesResultTypeDef](./type_defs.md#getqueueattributesresulttypedef).

<a id="get_queue_url"></a>

### get_queue_url

Returns the URL of an existing Amazon SQS queue.

Type annotations for `aiobotocore.create_client("sqs").get_queue_url` method.

Boto3 documentation:
[SQS.Client.get_queue_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.get_queue_url)

Asynchronous method. Use `await get_queue_url(...)` for a synchronous call.

Arguments mapping described in
[GetQueueUrlRequestRequestTypeDef](./type_defs.md#getqueueurlrequestrequesttypedef).

Keyword-only arguments:

- `QueueName`: `str` *(required)*
- `QueueOwnerAWSAccountId`: `str`

Returns a `Coroutine` for
[GetQueueUrlResultTypeDef](./type_defs.md#getqueueurlresulttypedef).

<a id="list_dead_letter_source_queues"></a>

### list_dead_letter_source_queues

Returns a list of your queues that have the `RedrivePolicy` queue attribute
configured with a dead-letter queue.

Type annotations for
`aiobotocore.create_client("sqs").list_dead_letter_source_queues` method.

Boto3 documentation:
[SQS.Client.list_dead_letter_source_queues](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_dead_letter_source_queues)

Asynchronous method. Use `await list_dead_letter_source_queues(...)` for a
synchronous call.

Arguments mapping described in
[ListDeadLetterSourceQueuesRequestRequestTypeDef](./type_defs.md#listdeadlettersourcequeuesrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListDeadLetterSourceQueuesResultTypeDef](./type_defs.md#listdeadlettersourcequeuesresulttypedef).

<a id="list_queue_tags"></a>

### list_queue_tags

List all cost allocation tags added to the specified Amazon SQS queue.

Type annotations for `aiobotocore.create_client("sqs").list_queue_tags` method.

Boto3 documentation:
[SQS.Client.list_queue_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_queue_tags)

Asynchronous method. Use `await list_queue_tags(...)` for a synchronous call.

Arguments mapping described in
[ListQueueTagsRequestRequestTypeDef](./type_defs.md#listqueuetagsrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*

Returns a `Coroutine` for
[ListQueueTagsResultTypeDef](./type_defs.md#listqueuetagsresulttypedef).

<a id="list_queues"></a>

### list_queues

Returns a list of your queues in the current region.

Type annotations for `aiobotocore.create_client("sqs").list_queues` method.

Boto3 documentation:
[SQS.Client.list_queues](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_queues)

Asynchronous method. Use `await list_queues(...)` for a synchronous call.

Arguments mapping described in
[ListQueuesRequestRequestTypeDef](./type_defs.md#listqueuesrequestrequesttypedef).

Keyword-only arguments:

- `QueueNamePrefix`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListQueuesResultTypeDef](./type_defs.md#listqueuesresulttypedef).

<a id="purge_queue"></a>

### purge_queue

Deletes the messages in a queue specified by the `QueueURL` parameter.

Type annotations for `aiobotocore.create_client("sqs").purge_queue` method.

Boto3 documentation:
[SQS.Client.purge_queue](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.purge_queue)

Asynchronous method. Use `await purge_queue(...)` for a synchronous call.

Arguments mapping described in
[PurgeQueueRequestRequestTypeDef](./type_defs.md#purgequeuerequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*

<a id="receive_message"></a>

### receive_message

Retrieves one or more messages (up to 10), from the specified queue.

Type annotations for `aiobotocore.create_client("sqs").receive_message` method.

Boto3 documentation:
[SQS.Client.receive_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.receive_message)

Asynchronous method. Use `await receive_message(...)` for a synchronous call.

Arguments mapping described in
[ReceiveMessageRequestRequestTypeDef](./type_defs.md#receivemessagerequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `AttributeNames`:
  `Sequence`\[[QueueAttributeNameType](./literals.md#queueattributenametype)\]
- `MessageAttributeNames`: `Sequence`\[`str`\]
- `MaxNumberOfMessages`: `int`
- `VisibilityTimeout`: `int`
- `WaitTimeSeconds`: `int`
- `ReceiveRequestAttemptId`: `str`

Returns a `Coroutine` for
[ReceiveMessageResultTypeDef](./type_defs.md#receivemessageresulttypedef).

<a id="remove_permission"></a>

### remove_permission

Revokes any permissions in the queue policy that matches the specified `Label`
parameter.

Type annotations for `aiobotocore.create_client("sqs").remove_permission`
method.

Boto3 documentation:
[SQS.Client.remove_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.remove_permission)

Asynchronous method. Use `await remove_permission(...)` for a synchronous call.

Arguments mapping described in
[RemovePermissionRequestRequestTypeDef](./type_defs.md#removepermissionrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `Label`: `str` *(required)*

<a id="send_message"></a>

### send_message

Delivers a message to the specified queue.

Type annotations for `aiobotocore.create_client("sqs").send_message` method.

Boto3 documentation:
[SQS.Client.send_message](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.send_message)

Asynchronous method. Use `await send_message(...)` for a synchronous call.

Arguments mapping described in
[SendMessageRequestRequestTypeDef](./type_defs.md#sendmessagerequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `MessageBody`: `str` *(required)*
- `DelaySeconds`: `int`
- `MessageAttributes`: `Mapping`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]
- `MessageSystemAttributes`: `Mapping`\[`Literal['AWSTraceHeader']` (see
  [MessageSystemAttributeNameForSendsType](./literals.md#messagesystemattributenameforsendstype)),
  [MessageSystemAttributeValueTypeDef](./type_defs.md#messagesystemattributevaluetypedef)\]
- `MessageDeduplicationId`: `str`
- `MessageGroupId`: `str`

Returns a `Coroutine` for
[SendMessageResultTypeDef](./type_defs.md#sendmessageresulttypedef).

<a id="send_message_batch"></a>

### send_message_batch

Delivers up to ten messages to the specified queue.

Type annotations for `aiobotocore.create_client("sqs").send_message_batch`
method.

Boto3 documentation:
[SQS.Client.send_message_batch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.send_message_batch)

Asynchronous method. Use `await send_message_batch(...)` for a synchronous
call.

Arguments mapping described in
[SendMessageBatchRequestRequestTypeDef](./type_defs.md#sendmessagebatchrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `Entries`:
  `Sequence`\[[SendMessageBatchRequestEntryTypeDef](./type_defs.md#sendmessagebatchrequestentrytypedef)\]
  *(required)*

Returns a `Coroutine` for
[SendMessageBatchResultTypeDef](./type_defs.md#sendmessagebatchresulttypedef).

<a id="set_queue_attributes"></a>

### set_queue_attributes

Sets the value of one or more queue attributes.

Type annotations for `aiobotocore.create_client("sqs").set_queue_attributes`
method.

Boto3 documentation:
[SQS.Client.set_queue_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.set_queue_attributes)

Asynchronous method. Use `await set_queue_attributes(...)` for a synchronous
call.

Arguments mapping described in
[SetQueueAttributesRequestRequestTypeDef](./type_defs.md#setqueueattributesrequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `Attributes`:
  `Mapping`\[[QueueAttributeNameType](./literals.md#queueattributenametype),
  `str`\] *(required)*

<a id="tag_queue"></a>

### tag_queue

Add cost allocation tags to the specified Amazon SQS queue.

Type annotations for `aiobotocore.create_client("sqs").tag_queue` method.

Boto3 documentation:
[SQS.Client.tag_queue](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.tag_queue)

Asynchronous method. Use `await tag_queue(...)` for a synchronous call.

Arguments mapping described in
[TagQueueRequestRequestTypeDef](./type_defs.md#tagqueuerequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="untag_queue"></a>

### untag_queue

Remove cost allocation tags from the specified Amazon SQS queue.

Type annotations for `aiobotocore.create_client("sqs").untag_queue` method.

Boto3 documentation:
[SQS.Client.untag_queue](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.untag_queue)

Asynchronous method. Use `await untag_queue(...)` for a synchronous call.

Arguments mapping described in
[UntagQueueRequestRequestTypeDef](./type_defs.md#untagqueuerequestrequesttypedef).

Keyword-only arguments:

- `QueueUrl`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("sqs").get_paginator` method
with overloads.

- `client.get_paginator("list_dead_letter_source_queues")` ->
  [ListDeadLetterSourceQueuesPaginator](./paginators.md#listdeadlettersourcequeuespaginator)
- `client.get_paginator("list_queues")` ->
  [ListQueuesPaginator](./paginators.md#listqueuespaginator)
