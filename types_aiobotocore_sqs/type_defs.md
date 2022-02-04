<a id="typed-dictionaries-for-aiobotocore-sqs-module"></a>

# Typed dictionaries for aiobotocore SQS module

> [Index](..) > [SQS](.) > Typed dictionaries

Auto-generated documentation for
[SQS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
type annotations stubs module
[types-aiobotocore-sqs](https://pypi.org/project/types-aiobotocore-sqs/).

- [Typed dictionaries for aiobotocore SQS module](#typed-dictionaries-for-aiobotocore-sqs-module)
  - [AddPermissionRequestQueueTypeDef](#addpermissionrequestqueuetypedef)
  - [AddPermissionRequestRequestTypeDef](#addpermissionrequestrequesttypedef)
  - [BatchResultErrorEntryTypeDef](#batchresulterrorentrytypedef)
  - [ChangeMessageVisibilityBatchRequestEntryTypeDef](#changemessagevisibilitybatchrequestentrytypedef)
  - [ChangeMessageVisibilityBatchRequestQueueTypeDef](#changemessagevisibilitybatchrequestqueuetypedef)
  - [ChangeMessageVisibilityBatchRequestRequestTypeDef](#changemessagevisibilitybatchrequestrequesttypedef)
  - [ChangeMessageVisibilityBatchResultEntryTypeDef](#changemessagevisibilitybatchresultentrytypedef)
  - [ChangeMessageVisibilityBatchResultTypeDef](#changemessagevisibilitybatchresulttypedef)
  - [ChangeMessageVisibilityRequestMessageTypeDef](#changemessagevisibilityrequestmessagetypedef)
  - [ChangeMessageVisibilityRequestRequestTypeDef](#changemessagevisibilityrequestrequesttypedef)
  - [CreateQueueRequestRequestTypeDef](#createqueuerequestrequesttypedef)
  - [CreateQueueRequestServiceResourceTypeDef](#createqueuerequestserviceresourcetypedef)
  - [CreateQueueResultTypeDef](#createqueueresulttypedef)
  - [DeleteMessageBatchRequestEntryTypeDef](#deletemessagebatchrequestentrytypedef)
  - [DeleteMessageBatchRequestQueueTypeDef](#deletemessagebatchrequestqueuetypedef)
  - [DeleteMessageBatchRequestRequestTypeDef](#deletemessagebatchrequestrequesttypedef)
  - [DeleteMessageBatchResultEntryTypeDef](#deletemessagebatchresultentrytypedef)
  - [DeleteMessageBatchResultTypeDef](#deletemessagebatchresulttypedef)
  - [DeleteMessageRequestRequestTypeDef](#deletemessagerequestrequesttypedef)
  - [DeleteQueueRequestRequestTypeDef](#deletequeuerequestrequesttypedef)
  - [GetQueueAttributesRequestRequestTypeDef](#getqueueattributesrequestrequesttypedef)
  - [GetQueueAttributesResultTypeDef](#getqueueattributesresulttypedef)
  - [GetQueueUrlRequestRequestTypeDef](#getqueueurlrequestrequesttypedef)
  - [GetQueueUrlRequestServiceResourceTypeDef](#getqueueurlrequestserviceresourcetypedef)
  - [GetQueueUrlResultTypeDef](#getqueueurlresulttypedef)
  - [ListDeadLetterSourceQueuesRequestRequestTypeDef](#listdeadlettersourcequeuesrequestrequesttypedef)
  - [ListDeadLetterSourceQueuesResultTypeDef](#listdeadlettersourcequeuesresulttypedef)
  - [ListQueueTagsRequestRequestTypeDef](#listqueuetagsrequestrequesttypedef)
  - [ListQueueTagsResultTypeDef](#listqueuetagsresulttypedef)
  - [ListQueuesRequestRequestTypeDef](#listqueuesrequestrequesttypedef)
  - [ListQueuesResultTypeDef](#listqueuesresulttypedef)
  - [MessageAttributeValueTypeDef](#messageattributevaluetypedef)
  - [MessageSystemAttributeValueTypeDef](#messagesystemattributevaluetypedef)
  - [MessageTypeDef](#messagetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PurgeQueueRequestRequestTypeDef](#purgequeuerequestrequesttypedef)
  - [QueueMessageRequestTypeDef](#queuemessagerequesttypedef)
  - [ReceiveMessageRequestQueueTypeDef](#receivemessagerequestqueuetypedef)
  - [ReceiveMessageRequestRequestTypeDef](#receivemessagerequestrequesttypedef)
  - [ReceiveMessageResultTypeDef](#receivemessageresulttypedef)
  - [RemovePermissionRequestQueueTypeDef](#removepermissionrequestqueuetypedef)
  - [RemovePermissionRequestRequestTypeDef](#removepermissionrequestrequesttypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SendMessageBatchRequestEntryTypeDef](#sendmessagebatchrequestentrytypedef)
  - [SendMessageBatchRequestQueueTypeDef](#sendmessagebatchrequestqueuetypedef)
  - [SendMessageBatchRequestRequestTypeDef](#sendmessagebatchrequestrequesttypedef)
  - [SendMessageBatchResultEntryTypeDef](#sendmessagebatchresultentrytypedef)
  - [SendMessageBatchResultTypeDef](#sendmessagebatchresulttypedef)
  - [SendMessageRequestQueueTypeDef](#sendmessagerequestqueuetypedef)
  - [SendMessageRequestRequestTypeDef](#sendmessagerequestrequesttypedef)
  - [SendMessageResultTypeDef](#sendmessageresulttypedef)
  - [ServiceResourceMessageRequestTypeDef](#serviceresourcemessagerequesttypedef)
  - [ServiceResourceQueueRequestTypeDef](#serviceresourcequeuerequesttypedef)
  - [SetQueueAttributesRequestQueueTypeDef](#setqueueattributesrequestqueuetypedef)
  - [SetQueueAttributesRequestRequestTypeDef](#setqueueattributesrequestrequesttypedef)
  - [TagQueueRequestRequestTypeDef](#tagqueuerequestrequesttypedef)
  - [UntagQueueRequestRequestTypeDef](#untagqueuerequestrequesttypedef)

<a id="addpermissionrequestqueuetypedef"></a>

## AddPermissionRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import AddPermissionRequestQueueTypeDef
```

Required fields:

- `Label`: `str`
- `AWSAccountIds`: `Sequence`\[`str`\]
- `Actions`: `Sequence`\[`str`\]

<a id="addpermissionrequestrequesttypedef"></a>

## AddPermissionRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import AddPermissionRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `Label`: `str`
- `AWSAccountIds`: `Sequence`\[`str`\]
- `Actions`: `Sequence`\[`str`\]

<a id="batchresulterrorentrytypedef"></a>

## BatchResultErrorEntryTypeDef

```python
from types_aiobotocore_sqs.type_defs import BatchResultErrorEntryTypeDef
```

Required fields:

- `Id`: `str`
- `SenderFault`: `bool`
- `Code`: `str`

Optional fields:

- `Message`: `str`

<a id="changemessagevisibilitybatchrequestentrytypedef"></a>

## ChangeMessageVisibilityBatchRequestEntryTypeDef

```python
from types_aiobotocore_sqs.type_defs import ChangeMessageVisibilityBatchRequestEntryTypeDef
```

Required fields:

- `Id`: `str`
- `ReceiptHandle`: `str`

Optional fields:

- `VisibilityTimeout`: `int`

<a id="changemessagevisibilitybatchrequestqueuetypedef"></a>

## ChangeMessageVisibilityBatchRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import ChangeMessageVisibilityBatchRequestQueueTypeDef
```

Required fields:

- `Entries`:
  `Sequence`\[[ChangeMessageVisibilityBatchRequestEntryTypeDef](./type_defs.md#changemessagevisibilitybatchrequestentrytypedef)\]

<a id="changemessagevisibilitybatchrequestrequesttypedef"></a>

## ChangeMessageVisibilityBatchRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ChangeMessageVisibilityBatchRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `Entries`:
  `Sequence`\[[ChangeMessageVisibilityBatchRequestEntryTypeDef](./type_defs.md#changemessagevisibilitybatchrequestentrytypedef)\]

<a id="changemessagevisibilitybatchresultentrytypedef"></a>

## ChangeMessageVisibilityBatchResultEntryTypeDef

```python
from types_aiobotocore_sqs.type_defs import ChangeMessageVisibilityBatchResultEntryTypeDef
```

Required fields:

- `Id`: `str`

<a id="changemessagevisibilitybatchresulttypedef"></a>

## ChangeMessageVisibilityBatchResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import ChangeMessageVisibilityBatchResultTypeDef
```

Required fields:

- `Successful`:
  `List`\[[ChangeMessageVisibilityBatchResultEntryTypeDef](./type_defs.md#changemessagevisibilitybatchresultentrytypedef)\]
- `Failed`:
  `List`\[[BatchResultErrorEntryTypeDef](./type_defs.md#batchresulterrorentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="changemessagevisibilityrequestmessagetypedef"></a>

## ChangeMessageVisibilityRequestMessageTypeDef

```python
from types_aiobotocore_sqs.type_defs import ChangeMessageVisibilityRequestMessageTypeDef
```

Required fields:

- `VisibilityTimeout`: `int`

<a id="changemessagevisibilityrequestrequesttypedef"></a>

## ChangeMessageVisibilityRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ChangeMessageVisibilityRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `ReceiptHandle`: `str`
- `VisibilityTimeout`: `int`

<a id="createqueuerequestrequesttypedef"></a>

## CreateQueueRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import CreateQueueRequestRequestTypeDef
```

Required fields:

- `QueueName`: `str`

Optional fields:

- `Attributes`:
  `Mapping`\[[QueueAttributeNameType](./literals.md#queueattributenametype),
  `str`\]
- `tags`: `Mapping`\[`str`, `str`\]

<a id="createqueuerequestserviceresourcetypedef"></a>

## CreateQueueRequestServiceResourceTypeDef

```python
from types_aiobotocore_sqs.type_defs import CreateQueueRequestServiceResourceTypeDef
```

Required fields:

- `QueueName`: `str`

Optional fields:

- `Attributes`:
  `Mapping`\[[QueueAttributeNameType](./literals.md#queueattributenametype),
  `str`\]
- `tags`: `Mapping`\[`str`, `str`\]

<a id="createqueueresulttypedef"></a>

## CreateQueueResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import CreateQueueResultTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletemessagebatchrequestentrytypedef"></a>

## DeleteMessageBatchRequestEntryTypeDef

```python
from types_aiobotocore_sqs.type_defs import DeleteMessageBatchRequestEntryTypeDef
```

Required fields:

- `Id`: `str`
- `ReceiptHandle`: `str`

<a id="deletemessagebatchrequestqueuetypedef"></a>

## DeleteMessageBatchRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import DeleteMessageBatchRequestQueueTypeDef
```

Required fields:

- `Entries`:
  `Sequence`\[[DeleteMessageBatchRequestEntryTypeDef](./type_defs.md#deletemessagebatchrequestentrytypedef)\]

<a id="deletemessagebatchrequestrequesttypedef"></a>

## DeleteMessageBatchRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import DeleteMessageBatchRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `Entries`:
  `Sequence`\[[DeleteMessageBatchRequestEntryTypeDef](./type_defs.md#deletemessagebatchrequestentrytypedef)\]

<a id="deletemessagebatchresultentrytypedef"></a>

## DeleteMessageBatchResultEntryTypeDef

```python
from types_aiobotocore_sqs.type_defs import DeleteMessageBatchResultEntryTypeDef
```

Required fields:

- `Id`: `str`

<a id="deletemessagebatchresulttypedef"></a>

## DeleteMessageBatchResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import DeleteMessageBatchResultTypeDef
```

Required fields:

- `Successful`:
  `List`\[[DeleteMessageBatchResultEntryTypeDef](./type_defs.md#deletemessagebatchresultentrytypedef)\]
- `Failed`:
  `List`\[[BatchResultErrorEntryTypeDef](./type_defs.md#batchresulterrorentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletemessagerequestrequesttypedef"></a>

## DeleteMessageRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import DeleteMessageRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `ReceiptHandle`: `str`

<a id="deletequeuerequestrequesttypedef"></a>

## DeleteQueueRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import DeleteQueueRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`

<a id="getqueueattributesrequestrequesttypedef"></a>

## GetQueueAttributesRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import GetQueueAttributesRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`

Optional fields:

- `AttributeNames`:
  `Sequence`\[[QueueAttributeNameType](./literals.md#queueattributenametype)\]

<a id="getqueueattributesresulttypedef"></a>

## GetQueueAttributesResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import GetQueueAttributesResultTypeDef
```

Required fields:

- `Attributes`:
  `Dict`\[[QueueAttributeNameType](./literals.md#queueattributenametype),
  `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getqueueurlrequestrequesttypedef"></a>

## GetQueueUrlRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import GetQueueUrlRequestRequestTypeDef
```

Required fields:

- `QueueName`: `str`

Optional fields:

- `QueueOwnerAWSAccountId`: `str`

<a id="getqueueurlrequestserviceresourcetypedef"></a>

## GetQueueUrlRequestServiceResourceTypeDef

```python
from types_aiobotocore_sqs.type_defs import GetQueueUrlRequestServiceResourceTypeDef
```

Required fields:

- `QueueName`: `str`

Optional fields:

- `QueueOwnerAWSAccountId`: `str`

<a id="getqueueurlresulttypedef"></a>

## GetQueueUrlResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import GetQueueUrlResultTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdeadlettersourcequeuesrequestrequesttypedef"></a>

## ListDeadLetterSourceQueuesRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ListDeadLetterSourceQueuesRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listdeadlettersourcequeuesresulttypedef"></a>

## ListDeadLetterSourceQueuesResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import ListDeadLetterSourceQueuesResultTypeDef
```

Required fields:

- `queueUrls`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listqueuetagsrequestrequesttypedef"></a>

## ListQueueTagsRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ListQueueTagsRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`

<a id="listqueuetagsresulttypedef"></a>

## ListQueueTagsResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import ListQueueTagsResultTypeDef
```

Required fields:

- `Tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listqueuesrequestrequesttypedef"></a>

## ListQueuesRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ListQueuesRequestRequestTypeDef
```

Optional fields:

- `QueueNamePrefix`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listqueuesresulttypedef"></a>

## ListQueuesResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import ListQueuesResultTypeDef
```

Required fields:

- `QueueUrls`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="messageattributevaluetypedef"></a>

## MessageAttributeValueTypeDef

```python
from types_aiobotocore_sqs.type_defs import MessageAttributeValueTypeDef
```

Required fields:

- `DataType`: `str`

Optional fields:

- `StringValue`: `str`
- `BinaryValue`: `bytes`
- `StringListValues`: `List`\[`str`\]
- `BinaryListValues`: `List`\[`bytes`\]

<a id="messagesystemattributevaluetypedef"></a>

## MessageSystemAttributeValueTypeDef

```python
from types_aiobotocore_sqs.type_defs import MessageSystemAttributeValueTypeDef
```

Required fields:

- `DataType`: `str`

Optional fields:

- `StringValue`: `str`
- `BinaryValue`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `StringListValues`: `Sequence`\[`str`\]
- `BinaryListValues`: `Sequence`\[`Union`\[`bytes`, `IO`\[`bytes`\],
  `StreamingBody`\]\]

<a id="messagetypedef"></a>

## MessageTypeDef

```python
from types_aiobotocore_sqs.type_defs import MessageTypeDef
```

Optional fields:

- `MessageId`: `str`
- `ReceiptHandle`: `str`
- `MD5OfBody`: `str`
- `Body`: `str`
- `Attributes`:
  `Dict`\[[MessageSystemAttributeNameType](./literals.md#messagesystemattributenametype),
  `str`\]
- `MD5OfMessageAttributes`: `str`
- `MessageAttributes`: `Dict`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_sqs.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="purgequeuerequestrequesttypedef"></a>

## PurgeQueueRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import PurgeQueueRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`

<a id="queuemessagerequesttypedef"></a>

## QueueMessageRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import QueueMessageRequestTypeDef
```

Required fields:

- `receipt_handle`: `str`

<a id="receivemessagerequestqueuetypedef"></a>

## ReceiveMessageRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import ReceiveMessageRequestQueueTypeDef
```

Optional fields:

- `AttributeNames`:
  `Sequence`\[[QueueAttributeNameType](./literals.md#queueattributenametype)\]
- `MessageAttributeNames`: `Sequence`\[`str`\]
- `MaxNumberOfMessages`: `int`
- `VisibilityTimeout`: `int`
- `WaitTimeSeconds`: `int`
- `ReceiveRequestAttemptId`: `str`

<a id="receivemessagerequestrequesttypedef"></a>

## ReceiveMessageRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ReceiveMessageRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`

Optional fields:

- `AttributeNames`:
  `Sequence`\[[QueueAttributeNameType](./literals.md#queueattributenametype)\]
- `MessageAttributeNames`: `Sequence`\[`str`\]
- `MaxNumberOfMessages`: `int`
- `VisibilityTimeout`: `int`
- `WaitTimeSeconds`: `int`
- `ReceiveRequestAttemptId`: `str`

<a id="receivemessageresulttypedef"></a>

## ReceiveMessageResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import ReceiveMessageResultTypeDef
```

Required fields:

- `Messages`: `List`\[[MessageTypeDef](./type_defs.md#messagetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="removepermissionrequestqueuetypedef"></a>

## RemovePermissionRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import RemovePermissionRequestQueueTypeDef
```

Required fields:

- `Label`: `str`

<a id="removepermissionrequestrequesttypedef"></a>

## RemovePermissionRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import RemovePermissionRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `Label`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_sqs.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="sendmessagebatchrequestentrytypedef"></a>

## SendMessageBatchRequestEntryTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageBatchRequestEntryTypeDef
```

Required fields:

- `Id`: `str`
- `MessageBody`: `str`

Optional fields:

- `DelaySeconds`: `int`
- `MessageAttributes`: `Mapping`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]
- `MessageSystemAttributes`: `Mapping`\[`Literal['AWSTraceHeader']` (see
  [MessageSystemAttributeNameForSendsType](./literals.md#messagesystemattributenameforsendstype)),
  [MessageSystemAttributeValueTypeDef](./type_defs.md#messagesystemattributevaluetypedef)\]
- `MessageDeduplicationId`: `str`
- `MessageGroupId`: `str`

<a id="sendmessagebatchrequestqueuetypedef"></a>

## SendMessageBatchRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageBatchRequestQueueTypeDef
```

Required fields:

- `Entries`:
  `Sequence`\[[SendMessageBatchRequestEntryTypeDef](./type_defs.md#sendmessagebatchrequestentrytypedef)\]

<a id="sendmessagebatchrequestrequesttypedef"></a>

## SendMessageBatchRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageBatchRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `Entries`:
  `Sequence`\[[SendMessageBatchRequestEntryTypeDef](./type_defs.md#sendmessagebatchrequestentrytypedef)\]

<a id="sendmessagebatchresultentrytypedef"></a>

## SendMessageBatchResultEntryTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageBatchResultEntryTypeDef
```

Required fields:

- `Id`: `str`
- `MessageId`: `str`
- `MD5OfMessageBody`: `str`

Optional fields:

- `MD5OfMessageAttributes`: `str`
- `MD5OfMessageSystemAttributes`: `str`
- `SequenceNumber`: `str`

<a id="sendmessagebatchresulttypedef"></a>

## SendMessageBatchResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageBatchResultTypeDef
```

Required fields:

- `Successful`:
  `List`\[[SendMessageBatchResultEntryTypeDef](./type_defs.md#sendmessagebatchresultentrytypedef)\]
- `Failed`:
  `List`\[[BatchResultErrorEntryTypeDef](./type_defs.md#batchresulterrorentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="sendmessagerequestqueuetypedef"></a>

## SendMessageRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageRequestQueueTypeDef
```

Required fields:

- `MessageBody`: `str`

Optional fields:

- `DelaySeconds`: `int`
- `MessageAttributes`: `Mapping`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]
- `MessageSystemAttributes`: `Mapping`\[`Literal['AWSTraceHeader']` (see
  [MessageSystemAttributeNameForSendsType](./literals.md#messagesystemattributenameforsendstype)),
  [MessageSystemAttributeValueTypeDef](./type_defs.md#messagesystemattributevaluetypedef)\]
- `MessageDeduplicationId`: `str`
- `MessageGroupId`: `str`

<a id="sendmessagerequestrequesttypedef"></a>

## SendMessageRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `MessageBody`: `str`

Optional fields:

- `DelaySeconds`: `int`
- `MessageAttributes`: `Mapping`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]
- `MessageSystemAttributes`: `Mapping`\[`Literal['AWSTraceHeader']` (see
  [MessageSystemAttributeNameForSendsType](./literals.md#messagesystemattributenameforsendstype)),
  [MessageSystemAttributeValueTypeDef](./type_defs.md#messagesystemattributevaluetypedef)\]
- `MessageDeduplicationId`: `str`
- `MessageGroupId`: `str`

<a id="sendmessageresulttypedef"></a>

## SendMessageResultTypeDef

```python
from types_aiobotocore_sqs.type_defs import SendMessageResultTypeDef
```

Required fields:

- `MD5OfMessageBody`: `str`
- `MD5OfMessageAttributes`: `str`
- `MD5OfMessageSystemAttributes`: `str`
- `MessageId`: `str`
- `SequenceNumber`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="serviceresourcemessagerequesttypedef"></a>

## ServiceResourceMessageRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ServiceResourceMessageRequestTypeDef
```

Required fields:

- `queue_url`: `str`
- `receipt_handle`: `str`

<a id="serviceresourcequeuerequesttypedef"></a>

## ServiceResourceQueueRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import ServiceResourceQueueRequestTypeDef
```

Required fields:

- `url`: `str`

<a id="setqueueattributesrequestqueuetypedef"></a>

## SetQueueAttributesRequestQueueTypeDef

```python
from types_aiobotocore_sqs.type_defs import SetQueueAttributesRequestQueueTypeDef
```

Required fields:

- `Attributes`:
  `Mapping`\[[QueueAttributeNameType](./literals.md#queueattributenametype),
  `str`\]

<a id="setqueueattributesrequestrequesttypedef"></a>

## SetQueueAttributesRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import SetQueueAttributesRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `Attributes`:
  `Mapping`\[[QueueAttributeNameType](./literals.md#queueattributenametype),
  `str`\]

<a id="tagqueuerequestrequesttypedef"></a>

## TagQueueRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import TagQueueRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="untagqueuerequestrequesttypedef"></a>

## UntagQueueRequestRequestTypeDef

```python
from types_aiobotocore_sqs.type_defs import UntagQueueRequestRequestTypeDef
```

Required fields:

- `QueueUrl`: `str`
- `TagKeys`: `Sequence`\[`str`\]
