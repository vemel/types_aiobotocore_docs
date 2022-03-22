<a id="typed-dictionaries-for-aiobotocore-timestreamquery-module"></a>

# Typed dictionaries for aiobotocore TimestreamQuery module

> [Index](../README.md) > [TimestreamQuery](./README.md) > Typed dictionaries

Auto-generated documentation for
[TimestreamQuery](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
type annotations stubs module
[types-aiobotocore-timestream-query](https://pypi.org/project/types-aiobotocore-timestream-query/).

- [Typed dictionaries for aiobotocore TimestreamQuery module](#typed-dictionaries-for-aiobotocore-timestreamquery-module)
  - [CancelQueryRequestRequestTypeDef](#cancelqueryrequestrequesttypedef)
  - [CancelQueryResponseTypeDef](#cancelqueryresponsetypedef)
  - [ColumnInfoTypeDef](#columninfotypedef)
  - [CreateScheduledQueryRequestRequestTypeDef](#createscheduledqueryrequestrequesttypedef)
  - [CreateScheduledQueryResponseTypeDef](#createscheduledqueryresponsetypedef)
  - [DatumTypeDef](#datumtypedef)
  - [DeleteScheduledQueryRequestRequestTypeDef](#deletescheduledqueryrequestrequesttypedef)
  - [DescribeEndpointsResponseTypeDef](#describeendpointsresponsetypedef)
  - [DescribeScheduledQueryRequestRequestTypeDef](#describescheduledqueryrequestrequesttypedef)
  - [DescribeScheduledQueryResponseTypeDef](#describescheduledqueryresponsetypedef)
  - [DimensionMappingTypeDef](#dimensionmappingtypedef)
  - [EndpointTypeDef](#endpointtypedef)
  - [ErrorReportConfigurationTypeDef](#errorreportconfigurationtypedef)
  - [ErrorReportLocationTypeDef](#errorreportlocationtypedef)
  - [ExecuteScheduledQueryRequestRequestTypeDef](#executescheduledqueryrequestrequesttypedef)
  - [ExecutionStatsTypeDef](#executionstatstypedef)
  - [ListScheduledQueriesRequestRequestTypeDef](#listscheduledqueriesrequestrequesttypedef)
  - [ListScheduledQueriesResponseTypeDef](#listscheduledqueriesresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [MixedMeasureMappingTypeDef](#mixedmeasuremappingtypedef)
  - [MultiMeasureAttributeMappingTypeDef](#multimeasureattributemappingtypedef)
  - [MultiMeasureMappingsTypeDef](#multimeasuremappingstypedef)
  - [NotificationConfigurationTypeDef](#notificationconfigurationtypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ParameterMappingTypeDef](#parametermappingtypedef)
  - [PrepareQueryRequestRequestTypeDef](#preparequeryrequestrequesttypedef)
  - [PrepareQueryResponseTypeDef](#preparequeryresponsetypedef)
  - [QueryRequestRequestTypeDef](#queryrequestrequesttypedef)
  - [QueryResponseTypeDef](#queryresponsetypedef)
  - [QueryStatusTypeDef](#querystatustypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RowTypeDef](#rowtypedef)
  - [S3ConfigurationTypeDef](#s3configurationtypedef)
  - [S3ReportLocationTypeDef](#s3reportlocationtypedef)
  - [ScheduleConfigurationTypeDef](#scheduleconfigurationtypedef)
  - [ScheduledQueryDescriptionTypeDef](#scheduledquerydescriptiontypedef)
  - [ScheduledQueryRunSummaryTypeDef](#scheduledqueryrunsummarytypedef)
  - [ScheduledQueryTypeDef](#scheduledquerytypedef)
  - [SelectColumnTypeDef](#selectcolumntypedef)
  - [SnsConfigurationTypeDef](#snsconfigurationtypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TargetConfigurationTypeDef](#targetconfigurationtypedef)
  - [TargetDestinationTypeDef](#targetdestinationtypedef)
  - [TimeSeriesDataPointTypeDef](#timeseriesdatapointtypedef)
  - [TimestreamConfigurationTypeDef](#timestreamconfigurationtypedef)
  - [TimestreamDestinationTypeDef](#timestreamdestinationtypedef)
  - [TypeTypeDef](#typetypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateScheduledQueryRequestRequestTypeDef](#updatescheduledqueryrequestrequesttypedef)

<a id="cancelqueryrequestrequesttypedef"></a>

## CancelQueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import CancelQueryRequestRequestTypeDef
```

Required fields:

- `QueryId`: `str`

<a id="cancelqueryresponsetypedef"></a>

## CancelQueryResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import CancelQueryResponseTypeDef
```

Required fields:

- `CancellationMessage`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="columninfotypedef"></a>

## ColumnInfoTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ColumnInfoTypeDef
```

Required fields:

- `Type`: [TypeTypeDef](./type_defs.md#typetypedef)

Optional fields:

- `Name`: `str`

<a id="createscheduledqueryrequestrequesttypedef"></a>

## CreateScheduledQueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import CreateScheduledQueryRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `QueryString`: `str`
- `ScheduleConfiguration`:
  [ScheduleConfigurationTypeDef](./type_defs.md#scheduleconfigurationtypedef)
- `NotificationConfiguration`:
  [NotificationConfigurationTypeDef](./type_defs.md#notificationconfigurationtypedef)
- `ScheduledQueryExecutionRoleArn`: `str`
- `ErrorReportConfiguration`:
  [ErrorReportConfigurationTypeDef](./type_defs.md#errorreportconfigurationtypedef)

Optional fields:

- `TargetConfiguration`:
  [TargetConfigurationTypeDef](./type_defs.md#targetconfigurationtypedef)
- `ClientToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `KmsKeyId`: `str`

<a id="createscheduledqueryresponsetypedef"></a>

## CreateScheduledQueryResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import CreateScheduledQueryResponseTypeDef
```

Required fields:

- `Arn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="datumtypedef"></a>

## DatumTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import DatumTypeDef
```

Optional fields:

- `ScalarValue`: `str`
- `TimeSeriesValue`:
  `List`\[[TimeSeriesDataPointTypeDef](./type_defs.md#timeseriesdatapointtypedef)\]
- `ArrayValue`: `List`\[[DatumTypeDef](./type_defs.md#datumtypedef)\]
- `RowValue`: [RowTypeDef](./type_defs.md#rowtypedef)
- `NullValue`: `bool`

<a id="deletescheduledqueryrequestrequesttypedef"></a>

## DeleteScheduledQueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import DeleteScheduledQueryRequestRequestTypeDef
```

Required fields:

- `ScheduledQueryArn`: `str`

<a id="describeendpointsresponsetypedef"></a>

## DescribeEndpointsResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import DescribeEndpointsResponseTypeDef
```

Required fields:

- `Endpoints`: `List`\[[EndpointTypeDef](./type_defs.md#endpointtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describescheduledqueryrequestrequesttypedef"></a>

## DescribeScheduledQueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import DescribeScheduledQueryRequestRequestTypeDef
```

Required fields:

- `ScheduledQueryArn`: `str`

<a id="describescheduledqueryresponsetypedef"></a>

## DescribeScheduledQueryResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import DescribeScheduledQueryResponseTypeDef
```

Required fields:

- `ScheduledQuery`:
  [ScheduledQueryDescriptionTypeDef](./type_defs.md#scheduledquerydescriptiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dimensionmappingtypedef"></a>

## DimensionMappingTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import DimensionMappingTypeDef
```

Required fields:

- `Name`: `str`
- `DimensionValueType`: `Literal['VARCHAR']` (see
  [DimensionValueTypeType](./literals.md#dimensionvaluetypetype))

<a id="endpointtypedef"></a>

## EndpointTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import EndpointTypeDef
```

Required fields:

- `Address`: `str`
- `CachePeriodInMinutes`: `int`

<a id="errorreportconfigurationtypedef"></a>

## ErrorReportConfigurationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ErrorReportConfigurationTypeDef
```

Required fields:

- `S3Configuration`:
  [S3ConfigurationTypeDef](./type_defs.md#s3configurationtypedef)

<a id="errorreportlocationtypedef"></a>

## ErrorReportLocationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ErrorReportLocationTypeDef
```

Optional fields:

- `S3ReportLocation`:
  [S3ReportLocationTypeDef](./type_defs.md#s3reportlocationtypedef)

<a id="executescheduledqueryrequestrequesttypedef"></a>

## ExecuteScheduledQueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ExecuteScheduledQueryRequestRequestTypeDef
```

Required fields:

- `ScheduledQueryArn`: `str`
- `InvocationTime`: `Union`\[`datetime`, `str`\]

Optional fields:

- `ClientToken`: `str`

<a id="executionstatstypedef"></a>

## ExecutionStatsTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ExecutionStatsTypeDef
```

Optional fields:

- `ExecutionTimeInMillis`: `int`
- `DataWrites`: `int`
- `BytesMetered`: `int`
- `RecordsIngested`: `int`
- `QueryResultRows`: `int`

<a id="listscheduledqueriesrequestrequesttypedef"></a>

## ListScheduledQueriesRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ListScheduledQueriesRequestRequestTypeDef
```

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listscheduledqueriesresponsetypedef"></a>

## ListScheduledQueriesResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ListScheduledQueriesResponseTypeDef
```

Required fields:

- `ScheduledQueries`:
  `List`\[[ScheduledQueryTypeDef](./type_defs.md#scheduledquerytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="mixedmeasuremappingtypedef"></a>

## MixedMeasureMappingTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import MixedMeasureMappingTypeDef
```

Required fields:

- `MeasureValueType`:
  [MeasureValueTypeType](./literals.md#measurevaluetypetype)

Optional fields:

- `MeasureName`: `str`
- `SourceColumn`: `str`
- `TargetMeasureName`: `str`
- `MultiMeasureAttributeMappings`:
  `Sequence`\[[MultiMeasureAttributeMappingTypeDef](./type_defs.md#multimeasureattributemappingtypedef)\]

<a id="multimeasureattributemappingtypedef"></a>

## MultiMeasureAttributeMappingTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import MultiMeasureAttributeMappingTypeDef
```

Required fields:

- `SourceColumn`: `str`
- `MeasureValueType`:
  [ScalarMeasureValueTypeType](./literals.md#scalarmeasurevaluetypetype)

Optional fields:

- `TargetMultiMeasureAttributeName`: `str`

<a id="multimeasuremappingstypedef"></a>

## MultiMeasureMappingsTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import MultiMeasureMappingsTypeDef
```

Required fields:

- `MultiMeasureAttributeMappings`:
  `Sequence`\[[MultiMeasureAttributeMappingTypeDef](./type_defs.md#multimeasureattributemappingtypedef)\]

Optional fields:

- `TargetMultiMeasureName`: `str`

<a id="notificationconfigurationtypedef"></a>

## NotificationConfigurationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import NotificationConfigurationTypeDef
```

Required fields:

- `SnsConfiguration`:
  [SnsConfigurationTypeDef](./type_defs.md#snsconfigurationtypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="parametermappingtypedef"></a>

## ParameterMappingTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ParameterMappingTypeDef
```

Required fields:

- `Name`: `str`
- `Type`: [TypeTypeDef](./type_defs.md#typetypedef)

<a id="preparequeryrequestrequesttypedef"></a>

## PrepareQueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import PrepareQueryRequestRequestTypeDef
```

Required fields:

- `QueryString`: `str`

Optional fields:

- `ValidateOnly`: `bool`

<a id="preparequeryresponsetypedef"></a>

## PrepareQueryResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import PrepareQueryResponseTypeDef
```

Required fields:

- `QueryString`: `str`
- `Columns`:
  `List`\[[SelectColumnTypeDef](./type_defs.md#selectcolumntypedef)\]
- `Parameters`:
  `List`\[[ParameterMappingTypeDef](./type_defs.md#parametermappingtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="queryrequestrequesttypedef"></a>

## QueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import QueryRequestRequestTypeDef
```

Required fields:

- `QueryString`: `str`

Optional fields:

- `ClientToken`: `str`
- `NextToken`: `str`
- `MaxRows`: `int`

<a id="queryresponsetypedef"></a>

## QueryResponseTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import QueryResponseTypeDef
```

Required fields:

- `QueryId`: `str`
- `NextToken`: `str`
- `Rows`: `List`\[[RowTypeDef](./type_defs.md#rowtypedef)\]
- `ColumnInfo`: `List`\[[ColumnInfoTypeDef](./type_defs.md#columninfotypedef)\]
- `QueryStatus`: [QueryStatusTypeDef](./type_defs.md#querystatustypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="querystatustypedef"></a>

## QueryStatusTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import QueryStatusTypeDef
```

Optional fields:

- `ProgressPercentage`: `float`
- `CumulativeBytesScanned`: `int`
- `CumulativeBytesMetered`: `int`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="rowtypedef"></a>

## RowTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import RowTypeDef
```

Required fields:

- `Data`: `List`\[[DatumTypeDef](./type_defs.md#datumtypedef)\]

<a id="s3configurationtypedef"></a>

## S3ConfigurationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import S3ConfigurationTypeDef
```

Required fields:

- `BucketName`: `str`

Optional fields:

- `ObjectKeyPrefix`: `str`
- `EncryptionOption`:
  [S3EncryptionOptionType](./literals.md#s3encryptionoptiontype)

<a id="s3reportlocationtypedef"></a>

## S3ReportLocationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import S3ReportLocationTypeDef
```

Optional fields:

- `BucketName`: `str`
- `ObjectKey`: `str`

<a id="scheduleconfigurationtypedef"></a>

## ScheduleConfigurationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ScheduleConfigurationTypeDef
```

Required fields:

- `ScheduleExpression`: `str`

<a id="scheduledquerydescriptiontypedef"></a>

## ScheduledQueryDescriptionTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ScheduledQueryDescriptionTypeDef
```

Required fields:

- `Arn`: `str`
- `Name`: `str`
- `QueryString`: `str`
- `State`: [ScheduledQueryStateType](./literals.md#scheduledquerystatetype)
- `ScheduleConfiguration`:
  [ScheduleConfigurationTypeDef](./type_defs.md#scheduleconfigurationtypedef)
- `NotificationConfiguration`:
  [NotificationConfigurationTypeDef](./type_defs.md#notificationconfigurationtypedef)

Optional fields:

- `CreationTime`: `datetime`
- `PreviousInvocationTime`: `datetime`
- `NextInvocationTime`: `datetime`
- `TargetConfiguration`:
  [TargetConfigurationTypeDef](./type_defs.md#targetconfigurationtypedef)
- `ScheduledQueryExecutionRoleArn`: `str`
- `KmsKeyId`: `str`
- `ErrorReportConfiguration`:
  [ErrorReportConfigurationTypeDef](./type_defs.md#errorreportconfigurationtypedef)
- `LastRunSummary`:
  [ScheduledQueryRunSummaryTypeDef](./type_defs.md#scheduledqueryrunsummarytypedef)
- `RecentlyFailedRuns`:
  `List`\[[ScheduledQueryRunSummaryTypeDef](./type_defs.md#scheduledqueryrunsummarytypedef)\]

<a id="scheduledqueryrunsummarytypedef"></a>

## ScheduledQueryRunSummaryTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ScheduledQueryRunSummaryTypeDef
```

Optional fields:

- `InvocationTime`: `datetime`
- `TriggerTime`: `datetime`
- `RunStatus`:
  [ScheduledQueryRunStatusType](./literals.md#scheduledqueryrunstatustype)
- `ExecutionStats`:
  [ExecutionStatsTypeDef](./type_defs.md#executionstatstypedef)
- `ErrorReportLocation`:
  [ErrorReportLocationTypeDef](./type_defs.md#errorreportlocationtypedef)
- `FailureReason`: `str`

<a id="scheduledquerytypedef"></a>

## ScheduledQueryTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import ScheduledQueryTypeDef
```

Required fields:

- `Arn`: `str`
- `Name`: `str`
- `State`: [ScheduledQueryStateType](./literals.md#scheduledquerystatetype)

Optional fields:

- `CreationTime`: `datetime`
- `PreviousInvocationTime`: `datetime`
- `NextInvocationTime`: `datetime`
- `ErrorReportConfiguration`:
  [ErrorReportConfigurationTypeDef](./type_defs.md#errorreportconfigurationtypedef)
- `TargetDestination`:
  [TargetDestinationTypeDef](./type_defs.md#targetdestinationtypedef)
- `LastRunStatus`:
  [ScheduledQueryRunStatusType](./literals.md#scheduledqueryrunstatustype)

<a id="selectcolumntypedef"></a>

## SelectColumnTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import SelectColumnTypeDef
```

Optional fields:

- `Name`: `str`
- `Type`: [TypeTypeDef](./type_defs.md#typetypedef)
- `DatabaseName`: `str`
- `TableName`: `str`
- `Aliased`: `bool`

<a id="snsconfigurationtypedef"></a>

## SnsConfigurationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import SnsConfigurationTypeDef
```

Required fields:

- `TopicArn`: `str`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="targetconfigurationtypedef"></a>

## TargetConfigurationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TargetConfigurationTypeDef
```

Required fields:

- `TimestreamConfiguration`:
  [TimestreamConfigurationTypeDef](./type_defs.md#timestreamconfigurationtypedef)

<a id="targetdestinationtypedef"></a>

## TargetDestinationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TargetDestinationTypeDef
```

Optional fields:

- `TimestreamDestination`:
  [TimestreamDestinationTypeDef](./type_defs.md#timestreamdestinationtypedef)

<a id="timeseriesdatapointtypedef"></a>

## TimeSeriesDataPointTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TimeSeriesDataPointTypeDef
```

Required fields:

- `Time`: `str`
- `Value`: [DatumTypeDef](./type_defs.md#datumtypedef)

<a id="timestreamconfigurationtypedef"></a>

## TimestreamConfigurationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TimestreamConfigurationTypeDef
```

Required fields:

- `DatabaseName`: `str`
- `TableName`: `str`
- `TimeColumn`: `str`
- `DimensionMappings`:
  `Sequence`\[[DimensionMappingTypeDef](./type_defs.md#dimensionmappingtypedef)\]

Optional fields:

- `MultiMeasureMappings`:
  [MultiMeasureMappingsTypeDef](./type_defs.md#multimeasuremappingstypedef)
- `MixedMeasureMappings`:
  `Sequence`\[[MixedMeasureMappingTypeDef](./type_defs.md#mixedmeasuremappingtypedef)\]
- `MeasureNameColumn`: `str`

<a id="timestreamdestinationtypedef"></a>

## TimestreamDestinationTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TimestreamDestinationTypeDef
```

Optional fields:

- `DatabaseName`: `str`
- `TableName`: `str`

<a id="typetypedef"></a>

## TypeTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import TypeTypeDef
```

Optional fields:

- `ScalarType`: [ScalarTypeType](./literals.md#scalartypetype)
- `ArrayColumnInfo`: [ColumnInfoTypeDef](./type_defs.md#columninfotypedef)
- `TimeSeriesMeasureValueColumnInfo`:
  [ColumnInfoTypeDef](./type_defs.md#columninfotypedef)
- `RowColumnInfo`:
  `List`\[[ColumnInfoTypeDef](./type_defs.md#columninfotypedef)\]

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updatescheduledqueryrequestrequesttypedef"></a>

## UpdateScheduledQueryRequestRequestTypeDef

```python
from types_aiobotocore_timestream_query.type_defs import UpdateScheduledQueryRequestRequestTypeDef
```

Required fields:

- `ScheduledQueryArn`: `str`
- `State`: [ScheduledQueryStateType](./literals.md#scheduledquerystatetype)
