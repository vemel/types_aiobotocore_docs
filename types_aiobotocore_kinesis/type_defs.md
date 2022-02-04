<a id="typed-dictionaries-for-aiobotocore-kinesis-module"></a>

# Typed dictionaries for aiobotocore Kinesis module

> [Index](..) > [Kinesis](.) > Typed dictionaries

Auto-generated documentation for
[Kinesis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis.html#Kinesis)
type annotations stubs module
[types-aiobotocore-kinesis](https://pypi.org/project/types-aiobotocore-kinesis/).

- [Typed dictionaries for aiobotocore Kinesis module](#typed-dictionaries-for-aiobotocore-kinesis-module)
  - [AddTagsToStreamInputRequestTypeDef](#addtagstostreaminputrequesttypedef)
  - [ChildShardTypeDef](#childshardtypedef)
  - [ConsumerDescriptionTypeDef](#consumerdescriptiontypedef)
  - [ConsumerTypeDef](#consumertypedef)
  - [CreateStreamInputRequestTypeDef](#createstreaminputrequesttypedef)
  - [DecreaseStreamRetentionPeriodInputRequestTypeDef](#decreasestreamretentionperiodinputrequesttypedef)
  - [DeleteStreamInputRequestTypeDef](#deletestreaminputrequesttypedef)
  - [DeregisterStreamConsumerInputRequestTypeDef](#deregisterstreamconsumerinputrequesttypedef)
  - [DescribeLimitsOutputTypeDef](#describelimitsoutputtypedef)
  - [DescribeStreamConsumerInputRequestTypeDef](#describestreamconsumerinputrequesttypedef)
  - [DescribeStreamConsumerOutputTypeDef](#describestreamconsumeroutputtypedef)
  - [DescribeStreamInputRequestTypeDef](#describestreaminputrequesttypedef)
  - [DescribeStreamOutputTypeDef](#describestreamoutputtypedef)
  - [DescribeStreamSummaryInputRequestTypeDef](#describestreamsummaryinputrequesttypedef)
  - [DescribeStreamSummaryOutputTypeDef](#describestreamsummaryoutputtypedef)
  - [DisableEnhancedMonitoringInputRequestTypeDef](#disableenhancedmonitoringinputrequesttypedef)
  - [EnableEnhancedMonitoringInputRequestTypeDef](#enableenhancedmonitoringinputrequesttypedef)
  - [EnhancedMetricsTypeDef](#enhancedmetricstypedef)
  - [EnhancedMonitoringOutputTypeDef](#enhancedmonitoringoutputtypedef)
  - [GetRecordsInputRequestTypeDef](#getrecordsinputrequesttypedef)
  - [GetRecordsOutputTypeDef](#getrecordsoutputtypedef)
  - [GetShardIteratorInputRequestTypeDef](#getsharditeratorinputrequesttypedef)
  - [GetShardIteratorOutputTypeDef](#getsharditeratoroutputtypedef)
  - [HashKeyRangeTypeDef](#hashkeyrangetypedef)
  - [IncreaseStreamRetentionPeriodInputRequestTypeDef](#increasestreamretentionperiodinputrequesttypedef)
  - [InternalFailureExceptionTypeDef](#internalfailureexceptiontypedef)
  - [KMSAccessDeniedExceptionTypeDef](#kmsaccessdeniedexceptiontypedef)
  - [KMSDisabledExceptionTypeDef](#kmsdisabledexceptiontypedef)
  - [KMSInvalidStateExceptionTypeDef](#kmsinvalidstateexceptiontypedef)
  - [KMSNotFoundExceptionTypeDef](#kmsnotfoundexceptiontypedef)
  - [KMSOptInRequiredTypeDef](#kmsoptinrequiredtypedef)
  - [KMSThrottlingExceptionTypeDef](#kmsthrottlingexceptiontypedef)
  - [ListShardsInputRequestTypeDef](#listshardsinputrequesttypedef)
  - [ListShardsOutputTypeDef](#listshardsoutputtypedef)
  - [ListStreamConsumersInputRequestTypeDef](#liststreamconsumersinputrequesttypedef)
  - [ListStreamConsumersOutputTypeDef](#liststreamconsumersoutputtypedef)
  - [ListStreamsInputRequestTypeDef](#liststreamsinputrequesttypedef)
  - [ListStreamsOutputTypeDef](#liststreamsoutputtypedef)
  - [ListTagsForStreamInputRequestTypeDef](#listtagsforstreaminputrequesttypedef)
  - [ListTagsForStreamOutputTypeDef](#listtagsforstreamoutputtypedef)
  - [MergeShardsInputRequestTypeDef](#mergeshardsinputrequesttypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PutRecordInputRequestTypeDef](#putrecordinputrequesttypedef)
  - [PutRecordOutputTypeDef](#putrecordoutputtypedef)
  - [PutRecordsInputRequestTypeDef](#putrecordsinputrequesttypedef)
  - [PutRecordsOutputTypeDef](#putrecordsoutputtypedef)
  - [PutRecordsRequestEntryTypeDef](#putrecordsrequestentrytypedef)
  - [PutRecordsResultEntryTypeDef](#putrecordsresultentrytypedef)
  - [RecordTypeDef](#recordtypedef)
  - [RegisterStreamConsumerInputRequestTypeDef](#registerstreamconsumerinputrequesttypedef)
  - [RegisterStreamConsumerOutputTypeDef](#registerstreamconsumeroutputtypedef)
  - [RemoveTagsFromStreamInputRequestTypeDef](#removetagsfromstreaminputrequesttypedef)
  - [ResourceInUseExceptionTypeDef](#resourceinuseexceptiontypedef)
  - [ResourceNotFoundExceptionTypeDef](#resourcenotfoundexceptiontypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SequenceNumberRangeTypeDef](#sequencenumberrangetypedef)
  - [ShardFilterTypeDef](#shardfiltertypedef)
  - [ShardTypeDef](#shardtypedef)
  - [SplitShardInputRequestTypeDef](#splitshardinputrequesttypedef)
  - [StartStreamEncryptionInputRequestTypeDef](#startstreamencryptioninputrequesttypedef)
  - [StartingPositionTypeDef](#startingpositiontypedef)
  - [StopStreamEncryptionInputRequestTypeDef](#stopstreamencryptioninputrequesttypedef)
  - [StreamDescriptionSummaryTypeDef](#streamdescriptionsummarytypedef)
  - [StreamDescriptionTypeDef](#streamdescriptiontypedef)
  - [StreamModeDetailsTypeDef](#streammodedetailstypedef)
  - [SubscribeToShardEventStreamTypeDef](#subscribetoshardeventstreamtypedef)
  - [SubscribeToShardEventTypeDef](#subscribetoshardeventtypedef)
  - [SubscribeToShardInputRequestTypeDef](#subscribetoshardinputrequesttypedef)
  - [SubscribeToShardOutputTypeDef](#subscribetoshardoutputtypedef)
  - [TagTypeDef](#tagtypedef)
  - [UpdateShardCountInputRequestTypeDef](#updateshardcountinputrequesttypedef)
  - [UpdateShardCountOutputTypeDef](#updateshardcountoutputtypedef)
  - [UpdateStreamModeInputRequestTypeDef](#updatestreammodeinputrequesttypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)

<a id="addtagstostreaminputrequesttypedef"></a>

## AddTagsToStreamInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import AddTagsToStreamInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="childshardtypedef"></a>

## ChildShardTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ChildShardTypeDef
```

Required fields:

- `ShardId`: `str`
- `ParentShards`: `List`\[`str`\]
- `HashKeyRange`: [HashKeyRangeTypeDef](./type_defs.md#hashkeyrangetypedef)

<a id="consumerdescriptiontypedef"></a>

## ConsumerDescriptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ConsumerDescriptionTypeDef
```

Required fields:

- `ConsumerName`: `str`
- `ConsumerARN`: `str`
- `ConsumerStatus`: [ConsumerStatusType](./literals.md#consumerstatustype)
- `ConsumerCreationTimestamp`: `datetime`
- `StreamARN`: `str`

<a id="consumertypedef"></a>

## ConsumerTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ConsumerTypeDef
```

Required fields:

- `ConsumerName`: `str`
- `ConsumerARN`: `str`
- `ConsumerStatus`: [ConsumerStatusType](./literals.md#consumerstatustype)
- `ConsumerCreationTimestamp`: `datetime`

<a id="createstreaminputrequesttypedef"></a>

## CreateStreamInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import CreateStreamInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`

Optional fields:

- `ShardCount`: `int`
- `StreamModeDetails`:
  [StreamModeDetailsTypeDef](./type_defs.md#streammodedetailstypedef)

<a id="decreasestreamretentionperiodinputrequesttypedef"></a>

## DecreaseStreamRetentionPeriodInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DecreaseStreamRetentionPeriodInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `RetentionPeriodHours`: `int`

<a id="deletestreaminputrequesttypedef"></a>

## DeleteStreamInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DeleteStreamInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`

Optional fields:

- `EnforceConsumerDeletion`: `bool`

<a id="deregisterstreamconsumerinputrequesttypedef"></a>

## DeregisterStreamConsumerInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DeregisterStreamConsumerInputRequestTypeDef
```

Optional fields:

- `StreamARN`: `str`
- `ConsumerName`: `str`
- `ConsumerARN`: `str`

<a id="describelimitsoutputtypedef"></a>

## DescribeLimitsOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DescribeLimitsOutputTypeDef
```

Required fields:

- `ShardLimit`: `int`
- `OpenShardCount`: `int`
- `OnDemandStreamCount`: `int`
- `OnDemandStreamCountLimit`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestreamconsumerinputrequesttypedef"></a>

## DescribeStreamConsumerInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DescribeStreamConsumerInputRequestTypeDef
```

Optional fields:

- `StreamARN`: `str`
- `ConsumerName`: `str`
- `ConsumerARN`: `str`

<a id="describestreamconsumeroutputtypedef"></a>

## DescribeStreamConsumerOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DescribeStreamConsumerOutputTypeDef
```

Required fields:

- `ConsumerDescription`:
  [ConsumerDescriptionTypeDef](./type_defs.md#consumerdescriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestreaminputrequesttypedef"></a>

## DescribeStreamInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DescribeStreamInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`

Optional fields:

- `Limit`: `int`
- `ExclusiveStartShardId`: `str`

<a id="describestreamoutputtypedef"></a>

## DescribeStreamOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DescribeStreamOutputTypeDef
```

Required fields:

- `StreamDescription`:
  [StreamDescriptionTypeDef](./type_defs.md#streamdescriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestreamsummaryinputrequesttypedef"></a>

## DescribeStreamSummaryInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DescribeStreamSummaryInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`

<a id="describestreamsummaryoutputtypedef"></a>

## DescribeStreamSummaryOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DescribeStreamSummaryOutputTypeDef
```

Required fields:

- `StreamDescriptionSummary`:
  [StreamDescriptionSummaryTypeDef](./type_defs.md#streamdescriptionsummarytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disableenhancedmonitoringinputrequesttypedef"></a>

## DisableEnhancedMonitoringInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import DisableEnhancedMonitoringInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `ShardLevelMetrics`:
  `Sequence`\[[MetricsNameType](./literals.md#metricsnametype)\]

<a id="enableenhancedmonitoringinputrequesttypedef"></a>

## EnableEnhancedMonitoringInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import EnableEnhancedMonitoringInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `ShardLevelMetrics`:
  `Sequence`\[[MetricsNameType](./literals.md#metricsnametype)\]

<a id="enhancedmetricstypedef"></a>

## EnhancedMetricsTypeDef

```python
from types_aiobotocore_kinesis.type_defs import EnhancedMetricsTypeDef
```

Optional fields:

- `ShardLevelMetrics`:
  `List`\[[MetricsNameType](./literals.md#metricsnametype)\]

<a id="enhancedmonitoringoutputtypedef"></a>

## EnhancedMonitoringOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import EnhancedMonitoringOutputTypeDef
```

Required fields:

- `StreamName`: `str`
- `CurrentShardLevelMetrics`:
  `List`\[[MetricsNameType](./literals.md#metricsnametype)\]
- `DesiredShardLevelMetrics`:
  `List`\[[MetricsNameType](./literals.md#metricsnametype)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getrecordsinputrequesttypedef"></a>

## GetRecordsInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import GetRecordsInputRequestTypeDef
```

Required fields:

- `ShardIterator`: `str`

Optional fields:

- `Limit`: `int`

<a id="getrecordsoutputtypedef"></a>

## GetRecordsOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import GetRecordsOutputTypeDef
```

Required fields:

- `Records`: `List`\[[RecordTypeDef](./type_defs.md#recordtypedef)\]
- `NextShardIterator`: `str`
- `MillisBehindLatest`: `int`
- `ChildShards`:
  `List`\[[ChildShardTypeDef](./type_defs.md#childshardtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsharditeratorinputrequesttypedef"></a>

## GetShardIteratorInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import GetShardIteratorInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `ShardId`: `str`
- `ShardIteratorType`:
  [ShardIteratorTypeType](./literals.md#sharditeratortypetype)

Optional fields:

- `StartingSequenceNumber`: `str`
- `Timestamp`: `Union`\[`datetime`, `str`\]

<a id="getsharditeratoroutputtypedef"></a>

## GetShardIteratorOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import GetShardIteratorOutputTypeDef
```

Required fields:

- `ShardIterator`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="hashkeyrangetypedef"></a>

## HashKeyRangeTypeDef

```python
from types_aiobotocore_kinesis.type_defs import HashKeyRangeTypeDef
```

Required fields:

- `StartingHashKey`: `str`
- `EndingHashKey`: `str`

<a id="increasestreamretentionperiodinputrequesttypedef"></a>

## IncreaseStreamRetentionPeriodInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import IncreaseStreamRetentionPeriodInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `RetentionPeriodHours`: `int`

<a id="internalfailureexceptiontypedef"></a>

## InternalFailureExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import InternalFailureExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="kmsaccessdeniedexceptiontypedef"></a>

## KMSAccessDeniedExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import KMSAccessDeniedExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="kmsdisabledexceptiontypedef"></a>

## KMSDisabledExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import KMSDisabledExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="kmsinvalidstateexceptiontypedef"></a>

## KMSInvalidStateExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import KMSInvalidStateExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="kmsnotfoundexceptiontypedef"></a>

## KMSNotFoundExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import KMSNotFoundExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="kmsoptinrequiredtypedef"></a>

## KMSOptInRequiredTypeDef

```python
from types_aiobotocore_kinesis.type_defs import KMSOptInRequiredTypeDef
```

Optional fields:

- `message`: `str`

<a id="kmsthrottlingexceptiontypedef"></a>

## KMSThrottlingExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import KMSThrottlingExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="listshardsinputrequesttypedef"></a>

## ListShardsInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListShardsInputRequestTypeDef
```

Optional fields:

- `StreamName`: `str`
- `NextToken`: `str`
- `ExclusiveStartShardId`: `str`
- `MaxResults`: `int`
- `StreamCreationTimestamp`: `Union`\[`datetime`, `str`\]
- `ShardFilter`: [ShardFilterTypeDef](./type_defs.md#shardfiltertypedef)

<a id="listshardsoutputtypedef"></a>

## ListShardsOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListShardsOutputTypeDef
```

Required fields:

- `Shards`: `List`\[[ShardTypeDef](./type_defs.md#shardtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststreamconsumersinputrequesttypedef"></a>

## ListStreamConsumersInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListStreamConsumersInputRequestTypeDef
```

Required fields:

- `StreamARN`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `StreamCreationTimestamp`: `Union`\[`datetime`, `str`\]

<a id="liststreamconsumersoutputtypedef"></a>

## ListStreamConsumersOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListStreamConsumersOutputTypeDef
```

Required fields:

- `Consumers`: `List`\[[ConsumerTypeDef](./type_defs.md#consumertypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststreamsinputrequesttypedef"></a>

## ListStreamsInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListStreamsInputRequestTypeDef
```

Optional fields:

- `Limit`: `int`
- `ExclusiveStartStreamName`: `str`

<a id="liststreamsoutputtypedef"></a>

## ListStreamsOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListStreamsOutputTypeDef
```

Required fields:

- `StreamNames`: `List`\[`str`\]
- `HasMoreStreams`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforstreaminputrequesttypedef"></a>

## ListTagsForStreamInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListTagsForStreamInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`

Optional fields:

- `ExclusiveStartTagKey`: `str`
- `Limit`: `int`

<a id="listtagsforstreamoutputtypedef"></a>

## ListTagsForStreamOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ListTagsForStreamOutputTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `HasMoreTags`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="mergeshardsinputrequesttypedef"></a>

## MergeShardsInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import MergeShardsInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `ShardToMerge`: `str`
- `AdjacentShardToMerge`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_kinesis.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="putrecordinputrequesttypedef"></a>

## PutRecordInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import PutRecordInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `Data`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `PartitionKey`: `str`

Optional fields:

- `ExplicitHashKey`: `str`
- `SequenceNumberForOrdering`: `str`

<a id="putrecordoutputtypedef"></a>

## PutRecordOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import PutRecordOutputTypeDef
```

Required fields:

- `ShardId`: `str`
- `SequenceNumber`: `str`
- `EncryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="putrecordsinputrequesttypedef"></a>

## PutRecordsInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import PutRecordsInputRequestTypeDef
```

Required fields:

- `Records`:
  `Sequence`\[[PutRecordsRequestEntryTypeDef](./type_defs.md#putrecordsrequestentrytypedef)\]
- `StreamName`: `str`

<a id="putrecordsoutputtypedef"></a>

## PutRecordsOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import PutRecordsOutputTypeDef
```

Required fields:

- `FailedRecordCount`: `int`
- `Records`:
  `List`\[[PutRecordsResultEntryTypeDef](./type_defs.md#putrecordsresultentrytypedef)\]
- `EncryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="putrecordsrequestentrytypedef"></a>

## PutRecordsRequestEntryTypeDef

```python
from types_aiobotocore_kinesis.type_defs import PutRecordsRequestEntryTypeDef
```

Required fields:

- `Data`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `PartitionKey`: `str`

Optional fields:

- `ExplicitHashKey`: `str`

<a id="putrecordsresultentrytypedef"></a>

## PutRecordsResultEntryTypeDef

```python
from types_aiobotocore_kinesis.type_defs import PutRecordsResultEntryTypeDef
```

Optional fields:

- `SequenceNumber`: `str`
- `ShardId`: `str`
- `ErrorCode`: `str`
- `ErrorMessage`: `str`

<a id="recordtypedef"></a>

## RecordTypeDef

```python
from types_aiobotocore_kinesis.type_defs import RecordTypeDef
```

Required fields:

- `SequenceNumber`: `str`
- `Data`: `bytes`
- `PartitionKey`: `str`

Optional fields:

- `ApproximateArrivalTimestamp`: `datetime`
- `EncryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)

<a id="registerstreamconsumerinputrequesttypedef"></a>

## RegisterStreamConsumerInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import RegisterStreamConsumerInputRequestTypeDef
```

Required fields:

- `StreamARN`: `str`
- `ConsumerName`: `str`

<a id="registerstreamconsumeroutputtypedef"></a>

## RegisterStreamConsumerOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import RegisterStreamConsumerOutputTypeDef
```

Required fields:

- `Consumer`: [ConsumerTypeDef](./type_defs.md#consumertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="removetagsfromstreaminputrequesttypedef"></a>

## RemoveTagsFromStreamInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import RemoveTagsFromStreamInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="resourceinuseexceptiontypedef"></a>

## ResourceInUseExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ResourceInUseExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="resourcenotfoundexceptiontypedef"></a>

## ResourceNotFoundExceptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ResourceNotFoundExceptionTypeDef
```

Optional fields:

- `message`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="sequencenumberrangetypedef"></a>

## SequenceNumberRangeTypeDef

```python
from types_aiobotocore_kinesis.type_defs import SequenceNumberRangeTypeDef
```

Required fields:

- `StartingSequenceNumber`: `str`

Optional fields:

- `EndingSequenceNumber`: `str`

<a id="shardfiltertypedef"></a>

## ShardFilterTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ShardFilterTypeDef
```

Required fields:

- `Type`: [ShardFilterTypeType](./literals.md#shardfiltertypetype)

Optional fields:

- `ShardId`: `str`
- `Timestamp`: `Union`\[`datetime`, `str`\]

<a id="shardtypedef"></a>

## ShardTypeDef

```python
from types_aiobotocore_kinesis.type_defs import ShardTypeDef
```

Required fields:

- `ShardId`: `str`
- `HashKeyRange`: [HashKeyRangeTypeDef](./type_defs.md#hashkeyrangetypedef)
- `SequenceNumberRange`:
  [SequenceNumberRangeTypeDef](./type_defs.md#sequencenumberrangetypedef)

Optional fields:

- `ParentShardId`: `str`
- `AdjacentParentShardId`: `str`

<a id="splitshardinputrequesttypedef"></a>

## SplitShardInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import SplitShardInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `ShardToSplit`: `str`
- `NewStartingHashKey`: `str`

<a id="startstreamencryptioninputrequesttypedef"></a>

## StartStreamEncryptionInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import StartStreamEncryptionInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `EncryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)
- `KeyId`: `str`

<a id="startingpositiontypedef"></a>

## StartingPositionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import StartingPositionTypeDef
```

Required fields:

- `Type`: [ShardIteratorTypeType](./literals.md#sharditeratortypetype)

Optional fields:

- `SequenceNumber`: `str`
- `Timestamp`: `Union`\[`datetime`, `str`\]

<a id="stopstreamencryptioninputrequesttypedef"></a>

## StopStreamEncryptionInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import StopStreamEncryptionInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `EncryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)
- `KeyId`: `str`

<a id="streamdescriptionsummarytypedef"></a>

## StreamDescriptionSummaryTypeDef

```python
from types_aiobotocore_kinesis.type_defs import StreamDescriptionSummaryTypeDef
```

Required fields:

- `StreamName`: `str`
- `StreamARN`: `str`
- `StreamStatus`: [StreamStatusType](./literals.md#streamstatustype)
- `RetentionPeriodHours`: `int`
- `StreamCreationTimestamp`: `datetime`
- `EnhancedMonitoring`:
  `List`\[[EnhancedMetricsTypeDef](./type_defs.md#enhancedmetricstypedef)\]
- `OpenShardCount`: `int`

Optional fields:

- `StreamModeDetails`:
  [StreamModeDetailsTypeDef](./type_defs.md#streammodedetailstypedef)
- `EncryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)
- `KeyId`: `str`
- `ConsumerCount`: `int`

<a id="streamdescriptiontypedef"></a>

## StreamDescriptionTypeDef

```python
from types_aiobotocore_kinesis.type_defs import StreamDescriptionTypeDef
```

Required fields:

- `StreamName`: `str`
- `StreamARN`: `str`
- `StreamStatus`: [StreamStatusType](./literals.md#streamstatustype)
- `Shards`: `List`\[[ShardTypeDef](./type_defs.md#shardtypedef)\]
- `HasMoreShards`: `bool`
- `RetentionPeriodHours`: `int`
- `StreamCreationTimestamp`: `datetime`
- `EnhancedMonitoring`:
  `List`\[[EnhancedMetricsTypeDef](./type_defs.md#enhancedmetricstypedef)\]

Optional fields:

- `StreamModeDetails`:
  [StreamModeDetailsTypeDef](./type_defs.md#streammodedetailstypedef)
- `EncryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)
- `KeyId`: `str`

<a id="streammodedetailstypedef"></a>

## StreamModeDetailsTypeDef

```python
from types_aiobotocore_kinesis.type_defs import StreamModeDetailsTypeDef
```

Required fields:

- `StreamMode`: [StreamModeType](./literals.md#streammodetype)

<a id="subscribetoshardeventstreamtypedef"></a>

## SubscribeToShardEventStreamTypeDef

```python
from types_aiobotocore_kinesis.type_defs import SubscribeToShardEventStreamTypeDef
```

Required fields:

- `SubscribeToShardEvent`:
  [SubscribeToShardEventTypeDef](./type_defs.md#subscribetoshardeventtypedef)

Optional fields:

- `ResourceNotFoundException`:
  [ResourceNotFoundExceptionTypeDef](./type_defs.md#resourcenotfoundexceptiontypedef)
- `ResourceInUseException`:
  [ResourceInUseExceptionTypeDef](./type_defs.md#resourceinuseexceptiontypedef)
- `KMSDisabledException`:
  [KMSDisabledExceptionTypeDef](./type_defs.md#kmsdisabledexceptiontypedef)
- `KMSInvalidStateException`:
  [KMSInvalidStateExceptionTypeDef](./type_defs.md#kmsinvalidstateexceptiontypedef)
- `KMSAccessDeniedException`:
  [KMSAccessDeniedExceptionTypeDef](./type_defs.md#kmsaccessdeniedexceptiontypedef)
- `KMSNotFoundException`:
  [KMSNotFoundExceptionTypeDef](./type_defs.md#kmsnotfoundexceptiontypedef)
- `KMSOptInRequired`:
  [KMSOptInRequiredTypeDef](./type_defs.md#kmsoptinrequiredtypedef)
- `KMSThrottlingException`:
  [KMSThrottlingExceptionTypeDef](./type_defs.md#kmsthrottlingexceptiontypedef)
- `InternalFailureException`:
  [InternalFailureExceptionTypeDef](./type_defs.md#internalfailureexceptiontypedef)

<a id="subscribetoshardeventtypedef"></a>

## SubscribeToShardEventTypeDef

```python
from types_aiobotocore_kinesis.type_defs import SubscribeToShardEventTypeDef
```

Required fields:

- `Records`: `List`\[[RecordTypeDef](./type_defs.md#recordtypedef)\]
- `ContinuationSequenceNumber`: `str`
- `MillisBehindLatest`: `int`

Optional fields:

- `ChildShards`:
  `List`\[[ChildShardTypeDef](./type_defs.md#childshardtypedef)\]

<a id="subscribetoshardinputrequesttypedef"></a>

## SubscribeToShardInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import SubscribeToShardInputRequestTypeDef
```

Required fields:

- `ConsumerARN`: `str`
- `ShardId`: `str`
- `StartingPosition`:
  [StartingPositionTypeDef](./type_defs.md#startingpositiontypedef)

<a id="subscribetoshardoutputtypedef"></a>

## SubscribeToShardOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import SubscribeToShardOutputTypeDef
```

Required fields:

- `EventStream`:
  [SubscribeToShardEventStreamTypeDef](./type_defs.md#subscribetoshardeventstreamtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_kinesis.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`

Optional fields:

- `Value`: `str`

<a id="updateshardcountinputrequesttypedef"></a>

## UpdateShardCountInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import UpdateShardCountInputRequestTypeDef
```

Required fields:

- `StreamName`: `str`
- `TargetShardCount`: `int`
- `ScalingType`: `Literal['UNIFORM_SCALING']` (see
  [ScalingTypeType](./literals.md#scalingtypetype))

<a id="updateshardcountoutputtypedef"></a>

## UpdateShardCountOutputTypeDef

```python
from types_aiobotocore_kinesis.type_defs import UpdateShardCountOutputTypeDef
```

Required fields:

- `StreamName`: `str`
- `CurrentShardCount`: `int`
- `TargetShardCount`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatestreammodeinputrequesttypedef"></a>

## UpdateStreamModeInputRequestTypeDef

```python
from types_aiobotocore_kinesis.type_defs import UpdateStreamModeInputRequestTypeDef
```

Required fields:

- `StreamARN`: `str`
- `StreamModeDetails`:
  [StreamModeDetailsTypeDef](./type_defs.md#streammodedetailstypedef)

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_kinesis.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`
