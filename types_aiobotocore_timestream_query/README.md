<a id="type-annotations-for-aiobotocore-timestreamquery-module"></a>

# Type annotations for aiobotocore TimestreamQuery module

> [Index](..) > TimestreamQuery

Auto-generated documentation for
[TimestreamQuery](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
type annotations stubs module
[types-aiobotocore-timestream-query](https://pypi.org/project/types-aiobotocore-timestream-query/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[timestream-query]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[timestream-query]'

# standalone installation
pip install types-aiobotocore-timestream-query
```

- [Type annotations for aiobotocore TimestreamQuery module](#type-annotations-for-aiobotocore-timestreamquery-module)
  - [TimestreamQueryClient](#timestreamqueryclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="timestreamqueryclient"></a>

## TimestreamQueryClient

Type annotations for `session.create_client("timestream-query")` as
[TimestreamQueryClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_timestream_query.client import TimestreamQueryClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [cancel_query](./client.md#cancel_query)
- [create_scheduled_query](./client.md#create_scheduled_query)
- [delete_scheduled_query](./client.md#delete_scheduled_query)
- [describe_endpoints](./client.md#describe_endpoints)
- [describe_scheduled_query](./client.md#describe_scheduled_query)
- [exceptions](./client.md#exceptions)
- [execute_scheduled_query](./client.md#execute_scheduled_query)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [list_scheduled_queries](./client.md#list_scheduled_queries)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [prepare_query](./client.md#prepare_query)
- [query](./client.md#query)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_scheduled_query](./client.md#update_scheduled_query)

<a id="exceptions"></a>

### Exceptions

TimestreamQueryClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- ConflictException
- InternalServerException
- InvalidEndpointException
- QueryExecutionException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ThrottlingException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("timestream-query").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_timestream_query.paginator import ListScheduledQueriesPaginator, ...
```

- [ListScheduledQueriesPaginator](./paginators.md#listscheduledqueriespaginator)
- [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- [QueryPaginator](./paginators.md#querypaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_timestream_query.literals import DimensionValueTypeType, ...
```

- [DimensionValueTypeType](./literals.md#dimensionvaluetypetype)
- [ListScheduledQueriesPaginatorName](./literals.md#listscheduledqueriespaginatorname)
- [ListTagsForResourcePaginatorName](./literals.md#listtagsforresourcepaginatorname)
- [MeasureValueTypeType](./literals.md#measurevaluetypetype)
- [QueryPaginatorName](./literals.md#querypaginatorname)
- [S3EncryptionOptionType](./literals.md#s3encryptionoptiontype)
- [ScalarMeasureValueTypeType](./literals.md#scalarmeasurevaluetypetype)
- [ScalarTypeType](./literals.md#scalartypetype)
- [ScheduledQueryRunStatusType](./literals.md#scheduledqueryrunstatustype)
- [ScheduledQueryStateType](./literals.md#scheduledquerystatetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_timestream_query.type_defs import CancelQueryRequestRequestTypeDef, ...
```

- [CancelQueryRequestRequestTypeDef](./type_defs.md#cancelqueryrequestrequesttypedef)
- [CancelQueryResponseTypeDef](./type_defs.md#cancelqueryresponsetypedef)
- [ColumnInfoTypeDef](./type_defs.md#columninfotypedef)
- [CreateScheduledQueryRequestRequestTypeDef](./type_defs.md#createscheduledqueryrequestrequesttypedef)
- [CreateScheduledQueryResponseTypeDef](./type_defs.md#createscheduledqueryresponsetypedef)
- [DatumTypeDef](./type_defs.md#datumtypedef)
- [DeleteScheduledQueryRequestRequestTypeDef](./type_defs.md#deletescheduledqueryrequestrequesttypedef)
- [DescribeEndpointsResponseTypeDef](./type_defs.md#describeendpointsresponsetypedef)
- [DescribeScheduledQueryRequestRequestTypeDef](./type_defs.md#describescheduledqueryrequestrequesttypedef)
- [DescribeScheduledQueryResponseTypeDef](./type_defs.md#describescheduledqueryresponsetypedef)
- [DimensionMappingTypeDef](./type_defs.md#dimensionmappingtypedef)
- [EndpointTypeDef](./type_defs.md#endpointtypedef)
- [ErrorReportConfigurationTypeDef](./type_defs.md#errorreportconfigurationtypedef)
- [ErrorReportLocationTypeDef](./type_defs.md#errorreportlocationtypedef)
- [ExecuteScheduledQueryRequestRequestTypeDef](./type_defs.md#executescheduledqueryrequestrequesttypedef)
- [ExecutionStatsTypeDef](./type_defs.md#executionstatstypedef)
- [ListScheduledQueriesRequestRequestTypeDef](./type_defs.md#listscheduledqueriesrequestrequesttypedef)
- [ListScheduledQueriesResponseTypeDef](./type_defs.md#listscheduledqueriesresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [MixedMeasureMappingTypeDef](./type_defs.md#mixedmeasuremappingtypedef)
- [MultiMeasureAttributeMappingTypeDef](./type_defs.md#multimeasureattributemappingtypedef)
- [MultiMeasureMappingsTypeDef](./type_defs.md#multimeasuremappingstypedef)
- [NotificationConfigurationTypeDef](./type_defs.md#notificationconfigurationtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ParameterMappingTypeDef](./type_defs.md#parametermappingtypedef)
- [PrepareQueryRequestRequestTypeDef](./type_defs.md#preparequeryrequestrequesttypedef)
- [PrepareQueryResponseTypeDef](./type_defs.md#preparequeryresponsetypedef)
- [QueryRequestRequestTypeDef](./type_defs.md#queryrequestrequesttypedef)
- [QueryResponseTypeDef](./type_defs.md#queryresponsetypedef)
- [QueryStatusTypeDef](./type_defs.md#querystatustypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RowTypeDef](./type_defs.md#rowtypedef)
- [S3ConfigurationTypeDef](./type_defs.md#s3configurationtypedef)
- [S3ReportLocationTypeDef](./type_defs.md#s3reportlocationtypedef)
- [ScheduleConfigurationTypeDef](./type_defs.md#scheduleconfigurationtypedef)
- [ScheduledQueryDescriptionTypeDef](./type_defs.md#scheduledquerydescriptiontypedef)
- [ScheduledQueryRunSummaryTypeDef](./type_defs.md#scheduledqueryrunsummarytypedef)
- [ScheduledQueryTypeDef](./type_defs.md#scheduledquerytypedef)
- [SelectColumnTypeDef](./type_defs.md#selectcolumntypedef)
- [SnsConfigurationTypeDef](./type_defs.md#snsconfigurationtypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TargetConfigurationTypeDef](./type_defs.md#targetconfigurationtypedef)
- [TargetDestinationTypeDef](./type_defs.md#targetdestinationtypedef)
- [TimeSeriesDataPointTypeDef](./type_defs.md#timeseriesdatapointtypedef)
- [TimestreamConfigurationTypeDef](./type_defs.md#timestreamconfigurationtypedef)
- [TimestreamDestinationTypeDef](./type_defs.md#timestreamdestinationtypedef)
- [TypeTypeDef](./type_defs.md#typetypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateScheduledQueryRequestRequestTypeDef](./type_defs.md#updatescheduledqueryrequestrequesttypedef)
