<a id="type-annotations-for-aiobotocore-kinesis-module"></a>

# Type annotations for aiobotocore Kinesis module

> [Index](..) > Kinesis

Auto-generated documentation for
[Kinesis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis.html#Kinesis)
type annotations stubs module
[types-aiobotocore-kinesis](https://pypi.org/project/types-aiobotocore-kinesis/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[kinesis]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[kinesis]'

# standalone installation
pip install types-aiobotocore-kinesis
```

- [Type annotations for aiobotocore Kinesis module](#type-annotations-for-aiobotocore-kinesis-module)
  - [KinesisClient](#kinesisclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Waiters](#waiters)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="kinesisclient"></a>

## KinesisClient

Type annotations for `session.create_client("kinesis")` as
[KinesisClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_kinesis.client import KinesisClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [add_tags_to_stream](./client.md#add_tags_to_stream)
- [can_paginate](./client.md#can_paginate)
- [create_stream](./client.md#create_stream)
- [decrease_stream_retention_period](./client.md#decrease_stream_retention_period)
- [delete_stream](./client.md#delete_stream)
- [deregister_stream_consumer](./client.md#deregister_stream_consumer)
- [describe_limits](./client.md#describe_limits)
- [describe_stream](./client.md#describe_stream)
- [describe_stream_consumer](./client.md#describe_stream_consumer)
- [describe_stream_summary](./client.md#describe_stream_summary)
- [disable_enhanced_monitoring](./client.md#disable_enhanced_monitoring)
- [enable_enhanced_monitoring](./client.md#enable_enhanced_monitoring)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_records](./client.md#get_records)
- [get_shard_iterator](./client.md#get_shard_iterator)
- [get_waiter](./client.md#get_waiter)
- [increase_stream_retention_period](./client.md#increase_stream_retention_period)
- [list_shards](./client.md#list_shards)
- [list_stream_consumers](./client.md#list_stream_consumers)
- [list_streams](./client.md#list_streams)
- [list_tags_for_stream](./client.md#list_tags_for_stream)
- [merge_shards](./client.md#merge_shards)
- [put_record](./client.md#put_record)
- [put_records](./client.md#put_records)
- [register_stream_consumer](./client.md#register_stream_consumer)
- [remove_tags_from_stream](./client.md#remove_tags_from_stream)
- [split_shard](./client.md#split_shard)
- [start_stream_encryption](./client.md#start_stream_encryption)
- [stop_stream_encryption](./client.md#stop_stream_encryption)
- [subscribe_to_shard](./client.md#subscribe_to_shard)
- [update_shard_count](./client.md#update_shard_count)
- [update_stream_mode](./client.md#update_stream_mode)

<a id="exceptions"></a>

### Exceptions

KinesisClient [exceptions](./client.md#exceptions)

- ClientError
- ExpiredIteratorException
- ExpiredNextTokenException
- InternalFailureException
- InvalidArgumentException
- KMSAccessDeniedException
- KMSDisabledException
- KMSInvalidStateException
- KMSNotFoundException
- KMSOptInRequired
- KMSThrottlingException
- LimitExceededException
- ProvisionedThroughputExceededException
- ResourceInUseException
- ResourceNotFoundException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("kinesis").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_kinesis.paginator import DescribeStreamPaginator, ...
```

- [DescribeStreamPaginator](./paginators.md#describestreampaginator)
- [ListShardsPaginator](./paginators.md#listshardspaginator)
- [ListStreamConsumersPaginator](./paginators.md#liststreamconsumerspaginator)
- [ListStreamsPaginator](./paginators.md#liststreamspaginator)

<a id="waiters"></a>

## Waiters

Type annotations for [waiters](./waiters.md) from
`boto3.client("kinesis").get_waiter("...")`.

Can be used directly:

```python
from types_aiobotocore_kinesis.waiter import StreamExistsWaiter, ...
```

- [StreamExistsWaiter](./waiters.md#streamexistswaiter)
- [StreamNotExistsWaiter](./waiters.md#streamnotexistswaiter)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_kinesis.literals import ConsumerStatusType, ...
```

- [ConsumerStatusType](./literals.md#consumerstatustype)
- [DescribeStreamPaginatorName](./literals.md#describestreampaginatorname)
- [EncryptionTypeType](./literals.md#encryptiontypetype)
- [ListShardsPaginatorName](./literals.md#listshardspaginatorname)
- [ListStreamConsumersPaginatorName](./literals.md#liststreamconsumerspaginatorname)
- [ListStreamsPaginatorName](./literals.md#liststreamspaginatorname)
- [MetricsNameType](./literals.md#metricsnametype)
- [ScalingTypeType](./literals.md#scalingtypetype)
- [ShardFilterTypeType](./literals.md#shardfiltertypetype)
- [ShardIteratorTypeType](./literals.md#sharditeratortypetype)
- [StreamExistsWaiterName](./literals.md#streamexistswaitername)
- [StreamModeType](./literals.md#streammodetype)
- [StreamNotExistsWaiterName](./literals.md#streamnotexistswaitername)
- [StreamStatusType](./literals.md#streamstatustype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)
- [WaiterName](./literals.md#waitername)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_kinesis.type_defs import AddTagsToStreamInputRequestTypeDef, ...
```

- [AddTagsToStreamInputRequestTypeDef](./type_defs.md#addtagstostreaminputrequesttypedef)
- [ChildShardTypeDef](./type_defs.md#childshardtypedef)
- [ConsumerDescriptionTypeDef](./type_defs.md#consumerdescriptiontypedef)
- [ConsumerTypeDef](./type_defs.md#consumertypedef)
- [CreateStreamInputRequestTypeDef](./type_defs.md#createstreaminputrequesttypedef)
- [DecreaseStreamRetentionPeriodInputRequestTypeDef](./type_defs.md#decreasestreamretentionperiodinputrequesttypedef)
- [DeleteStreamInputRequestTypeDef](./type_defs.md#deletestreaminputrequesttypedef)
- [DeregisterStreamConsumerInputRequestTypeDef](./type_defs.md#deregisterstreamconsumerinputrequesttypedef)
- [DescribeLimitsOutputTypeDef](./type_defs.md#describelimitsoutputtypedef)
- [DescribeStreamConsumerInputRequestTypeDef](./type_defs.md#describestreamconsumerinputrequesttypedef)
- [DescribeStreamConsumerOutputTypeDef](./type_defs.md#describestreamconsumeroutputtypedef)
- [DescribeStreamInputRequestTypeDef](./type_defs.md#describestreaminputrequesttypedef)
- [DescribeStreamOutputTypeDef](./type_defs.md#describestreamoutputtypedef)
- [DescribeStreamSummaryInputRequestTypeDef](./type_defs.md#describestreamsummaryinputrequesttypedef)
- [DescribeStreamSummaryOutputTypeDef](./type_defs.md#describestreamsummaryoutputtypedef)
- [DisableEnhancedMonitoringInputRequestTypeDef](./type_defs.md#disableenhancedmonitoringinputrequesttypedef)
- [EnableEnhancedMonitoringInputRequestTypeDef](./type_defs.md#enableenhancedmonitoringinputrequesttypedef)
- [EnhancedMetricsTypeDef](./type_defs.md#enhancedmetricstypedef)
- [EnhancedMonitoringOutputTypeDef](./type_defs.md#enhancedmonitoringoutputtypedef)
- [GetRecordsInputRequestTypeDef](./type_defs.md#getrecordsinputrequesttypedef)
- [GetRecordsOutputTypeDef](./type_defs.md#getrecordsoutputtypedef)
- [GetShardIteratorInputRequestTypeDef](./type_defs.md#getsharditeratorinputrequesttypedef)
- [GetShardIteratorOutputTypeDef](./type_defs.md#getsharditeratoroutputtypedef)
- [HashKeyRangeTypeDef](./type_defs.md#hashkeyrangetypedef)
- [IncreaseStreamRetentionPeriodInputRequestTypeDef](./type_defs.md#increasestreamretentionperiodinputrequesttypedef)
- [InternalFailureExceptionTypeDef](./type_defs.md#internalfailureexceptiontypedef)
- [KMSAccessDeniedExceptionTypeDef](./type_defs.md#kmsaccessdeniedexceptiontypedef)
- [KMSDisabledExceptionTypeDef](./type_defs.md#kmsdisabledexceptiontypedef)
- [KMSInvalidStateExceptionTypeDef](./type_defs.md#kmsinvalidstateexceptiontypedef)
- [KMSNotFoundExceptionTypeDef](./type_defs.md#kmsnotfoundexceptiontypedef)
- [KMSOptInRequiredTypeDef](./type_defs.md#kmsoptinrequiredtypedef)
- [KMSThrottlingExceptionTypeDef](./type_defs.md#kmsthrottlingexceptiontypedef)
- [ListShardsInputRequestTypeDef](./type_defs.md#listshardsinputrequesttypedef)
- [ListShardsOutputTypeDef](./type_defs.md#listshardsoutputtypedef)
- [ListStreamConsumersInputRequestTypeDef](./type_defs.md#liststreamconsumersinputrequesttypedef)
- [ListStreamConsumersOutputTypeDef](./type_defs.md#liststreamconsumersoutputtypedef)
- [ListStreamsInputRequestTypeDef](./type_defs.md#liststreamsinputrequesttypedef)
- [ListStreamsOutputTypeDef](./type_defs.md#liststreamsoutputtypedef)
- [ListTagsForStreamInputRequestTypeDef](./type_defs.md#listtagsforstreaminputrequesttypedef)
- [ListTagsForStreamOutputTypeDef](./type_defs.md#listtagsforstreamoutputtypedef)
- [MergeShardsInputRequestTypeDef](./type_defs.md#mergeshardsinputrequesttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PutRecordInputRequestTypeDef](./type_defs.md#putrecordinputrequesttypedef)
- [PutRecordOutputTypeDef](./type_defs.md#putrecordoutputtypedef)
- [PutRecordsInputRequestTypeDef](./type_defs.md#putrecordsinputrequesttypedef)
- [PutRecordsOutputTypeDef](./type_defs.md#putrecordsoutputtypedef)
- [PutRecordsRequestEntryTypeDef](./type_defs.md#putrecordsrequestentrytypedef)
- [PutRecordsResultEntryTypeDef](./type_defs.md#putrecordsresultentrytypedef)
- [RecordTypeDef](./type_defs.md#recordtypedef)
- [RegisterStreamConsumerInputRequestTypeDef](./type_defs.md#registerstreamconsumerinputrequesttypedef)
- [RegisterStreamConsumerOutputTypeDef](./type_defs.md#registerstreamconsumeroutputtypedef)
- [RemoveTagsFromStreamInputRequestTypeDef](./type_defs.md#removetagsfromstreaminputrequesttypedef)
- [ResourceInUseExceptionTypeDef](./type_defs.md#resourceinuseexceptiontypedef)
- [ResourceNotFoundExceptionTypeDef](./type_defs.md#resourcenotfoundexceptiontypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SequenceNumberRangeTypeDef](./type_defs.md#sequencenumberrangetypedef)
- [ShardFilterTypeDef](./type_defs.md#shardfiltertypedef)
- [ShardTypeDef](./type_defs.md#shardtypedef)
- [SplitShardInputRequestTypeDef](./type_defs.md#splitshardinputrequesttypedef)
- [StartStreamEncryptionInputRequestTypeDef](./type_defs.md#startstreamencryptioninputrequesttypedef)
- [StartingPositionTypeDef](./type_defs.md#startingpositiontypedef)
- [StopStreamEncryptionInputRequestTypeDef](./type_defs.md#stopstreamencryptioninputrequesttypedef)
- [StreamDescriptionSummaryTypeDef](./type_defs.md#streamdescriptionsummarytypedef)
- [StreamDescriptionTypeDef](./type_defs.md#streamdescriptiontypedef)
- [StreamModeDetailsTypeDef](./type_defs.md#streammodedetailstypedef)
- [SubscribeToShardEventStreamTypeDef](./type_defs.md#subscribetoshardeventstreamtypedef)
- [SubscribeToShardEventTypeDef](./type_defs.md#subscribetoshardeventtypedef)
- [SubscribeToShardInputRequestTypeDef](./type_defs.md#subscribetoshardinputrequesttypedef)
- [SubscribeToShardOutputTypeDef](./type_defs.md#subscribetoshardoutputtypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UpdateShardCountInputRequestTypeDef](./type_defs.md#updateshardcountinputrequesttypedef)
- [UpdateShardCountOutputTypeDef](./type_defs.md#updateshardcountoutputtypedef)
- [UpdateStreamModeInputRequestTypeDef](./type_defs.md#updatestreammodeinputrequesttypedef)
- [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
