<a id="cloudwatchserviceresource-for-aiobotocore-cloudwatch-module"></a>

# CloudWatchServiceResource for aiobotocore CloudWatch module

> [Index](..) > [CloudWatch](.) > CloudWatchServiceResource

Auto-generated documentation for
[CloudWatch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch)
type annotations stubs module
[types-aiobotocore-cloudwatch](https://pypi.org/project/types-aiobotocore-cloudwatch/).

- [CloudWatchServiceResource for aiobotocore CloudWatch module](#cloudwatchserviceresource-for-aiobotocore-cloudwatch-module)
  - [CloudWatchServiceResource](#cloudwatchserviceresource)
  - [Attributes](#attributes)
  - [Collections](#collections)
    - [ServiceResourceAlarmsCollection](#serviceresourcealarmscollection)
    - [ServiceResourceMetricsCollection](#serviceresourcemetricscollection)
  - [Methods](#methods)
    - [CloudWatchServiceResource.Alarm method](#cloudwatchserviceresourcealarm-method)
    - [CloudWatchServiceResource.Metric method](#cloudwatchserviceresourcemetric-method)
    - [CloudWatchServiceResource.get_available_subresources method](#cloudwatchserviceresourceget_available_subresources-method)
  - [Alarm](#alarm)
    - [Alarm attributes](#alarm-attributes)
    - [Alarm methods](#alarm-methods)
  - [Metric](#metric)
    - [Metric attributes](#metric-attributes)
    - [Metric collections](#metric-collections)
    - [Metric methods](#metric-methods)

<a id="cloudwatchserviceresource"></a>

## CloudWatchServiceResource

Type annotations for `aiobotocore.resource("cloudwatch")`, included resources
and collections.

Can be used directly:

```python
from types_aiobotocore_cloudwatch.service_resource import CloudWatchServiceResource

def get_cloudwatch_resource() -> CloudWatchServiceResource:
    return boto3.resource("cloudwatch")
```

Boto3 documentation:
[CloudWatch.ServiceResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource)

<a id="attributes"></a>

## Attributes

- `meta`: [CloudWatchResourceMeta](#cloudwatchresourcemeta)

- `alarms`: [ServiceResourceAlarmsCollection](#serviceresourcealarmscollection)

- `metrics`:
  [ServiceResourceMetricsCollection](#serviceresourcemetricscollection)

<a id="collections"></a>

## Collections

<a id="serviceresourcealarmscollection"></a>

### ServiceResourceAlarmsCollection

Type annotations for `boto3.resource("cloudwatch").alarms` collection.

Can be used directly:

```python
from types_aiobotocore_cloudwatch.service_resource import ServiceResourceAlarmsCollection,

def get_collection() -> ServiceResourceAlarmsCollection:
    return boto3.resource("cloudwatch").alarms
```

Provides access to [Alarm](#alarm) resource.

Boto3 documentation:
[CloudWatch.ServiceResource.alarms](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource.alarms)

<a id="serviceresourcemetricscollection"></a>

### ServiceResourceMetricsCollection

Type annotations for `boto3.resource("cloudwatch").metrics` collection.

Can be used directly:

```python
from types_aiobotocore_cloudwatch.service_resource import ServiceResourceMetricsCollection,

def get_collection() -> ServiceResourceMetricsCollection:
    return boto3.resource("cloudwatch").metrics
```

Provides access to [Metric](#metric) resource.

Boto3 documentation:
[CloudWatch.ServiceResource.metrics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource.metrics)

<a id="methods"></a>

## Methods

<a id="cloudwatchserviceresourcealarm-method"></a>

### CloudWatchServiceResource.Alarm method

Creates a Alarm resource.

Type annotations for `aiobotocore.resource("cloudwatch").Alarm` method.

Boto3 documentation:
[CloudWatch.ServiceResource.Alarm](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource.Alarm)

Asynchronous method. Use `await Alarm(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceAlarmRequestTypeDef](./type_defs.md#serviceresourcealarmrequesttypedef).

Arguments:

- `name`: `str` *(required)*

Returns a `Coroutine` for [Alarm](#alarm).

<a id="cloudwatchserviceresourcemetric-method"></a>

### CloudWatchServiceResource.Metric method

Creates a Metric resource.

Type annotations for `aiobotocore.resource("cloudwatch").Metric` method.

Boto3 documentation:
[CloudWatch.ServiceResource.Metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource.Metric)

Asynchronous method. Use `await Metric(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceMetricRequestTypeDef](./type_defs.md#serviceresourcemetricrequesttypedef).

Arguments:

- `namespace`: `str` *(required)*
- `name`: `str` *(required)*

Returns a `Coroutine` for [Metric](#metric).

<a id="cloudwatchserviceresourceget_available_subresources-method"></a>

### CloudWatchServiceResource.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudwatch").get_available_subresources` method.

Boto3 documentation:
[CloudWatch.ServiceResource.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="alarm"></a>

## Alarm

Type annotations for `aiobotocore.resource("cloudwatch").Alarm` class.

Can be used directly:

```python
from types_aiobotocore_cloudwatch.service_resource import Alarm

def get_resource() -> Alarm:
    return boto3.resource("cloudwatch").Alarm(...)
```

Boto3 documentation:
[CloudWatch.Alarm](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource.Alarm)

<a id="alarm-attributes"></a>

### Alarm attributes

- `alarm_name`: `str`
- `alarm_arn`: `str`
- `alarm_description`: `str`
- `alarm_configuration_updated_timestamp`: `datetime`
- `actions_enabled`: `bool`
- `ok_actions`: `List`\[`str`\]
- `alarm_actions`: `List`\[`str`\]
- `insufficient_data_actions`: `List`\[`str`\]
- `state_value`: [StateValueType](./literals.md#statevaluetype)
- `state_reason`: `str`
- `state_reason_data`: `str`
- `state_updated_timestamp`: `datetime`
- `metric_name`: `str`
- `namespace`: `str`
- `statistic`: [StatisticType](./literals.md#statistictype)
- `extended_statistic`: `str`
- `dimensions`: `List`\[[DimensionTypeDef](./type_defs.md#dimensiontypedef)\]
- `period`: `int`
- `unit`: [StandardUnitType](./literals.md#standardunittype)
- `evaluation_periods`: `int`
- `datapoints_to_alarm`: `int`
- `threshold`: `float`
- `comparison_operator`:
  [ComparisonOperatorType](./literals.md#comparisonoperatortype)
- `treat_missing_data`: `str`
- `evaluate_low_sample_count_percentile`: `str`
- `metrics`:
  `List`\[[MetricDataQueryTypeDef](./type_defs.md#metricdataquerytypedef)\]
- `threshold_metric_id`: `str`
- `name`: `str`
- `metric`: [Metric](#metric)

<a id="alarm-methods"></a>

### Alarm methods

<a id="alarmdelete-method"></a>

#### Alarm.delete method

Deletes the specified alarms.

Type annotations for `aiobotocore.resource("cloudwatch").delete` method.

Boto3 documentation:
[CloudWatch.Alarm.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

<a id="alarmdescribe_history-method"></a>

#### Alarm.describe_history method

Retrieves the history for the specified alarm.

Type annotations for `aiobotocore.resource("cloudwatch").describe_history`
method.

Boto3 documentation:
[CloudWatch.Alarm.describe_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.describe_history)

Asynchronous method. Use `await describe_history(...)` for a synchronous call.

Arguments mapping described in
[DescribeAlarmHistoryInputAlarmTypeDef](./type_defs.md#describealarmhistoryinputalarmtypedef).

Keyword-only arguments:

- `AlarmTypes`: `Sequence`\[[AlarmTypeType](./literals.md#alarmtypetype)\]
- `HistoryItemType`: [HistoryItemTypeType](./literals.md#historyitemtypetype)
- `StartDate`: `Union`\[`datetime`, `str`\]
- `EndDate`: `Union`\[`datetime`, `str`\]
- `MaxRecords`: `int`
- `NextToken`: `str`
- `ScanBy`: [ScanByType](./literals.md#scanbytype)

Returns a `Coroutine` for
[DescribeAlarmHistoryOutputTypeDef](./type_defs.md#describealarmhistoryoutputtypedef).

<a id="alarmdisable_actions-method"></a>

#### Alarm.disable_actions method

Disables the actions for the specified alarms.

Type annotations for `aiobotocore.resource("cloudwatch").disable_actions`
method.

Boto3 documentation:
[CloudWatch.Alarm.disable_actions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.disable_actions)

Asynchronous method. Use `await disable_actions(...)` for a synchronous call.

<a id="alarmenable_actions-method"></a>

#### Alarm.enable_actions method

Enables the actions for the specified alarms.

Type annotations for `aiobotocore.resource("cloudwatch").enable_actions`
method.

Boto3 documentation:
[CloudWatch.Alarm.enable_actions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.enable_actions)

Asynchronous method. Use `await enable_actions(...)` for a synchronous call.

<a id="alarmget_available_subresources-method"></a>

#### Alarm.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudwatch").get_available_subresources` method.

Boto3 documentation:
[CloudWatch.Alarm.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="alarmload-method"></a>

#### Alarm.load method

Calls :py:meth:`CloudWatch.Client.describe_alarms` to update the attributes of
the Alarm resource.

Type annotations for `aiobotocore.resource("cloudwatch").load` method.

Boto3 documentation:
[CloudWatch.Alarm.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="alarmreload-method"></a>

#### Alarm.reload method

Calls :py:meth:`CloudWatch.Client.describe_alarms` to update the attributes of
the Alarm resource.

Type annotations for `aiobotocore.resource("cloudwatch").reload` method.

Boto3 documentation:
[CloudWatch.Alarm.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="alarmset_state-method"></a>

#### Alarm.set_state method

Temporarily sets the state of an alarm for testing purposes.

Type annotations for `aiobotocore.resource("cloudwatch").set_state` method.

Boto3 documentation:
[CloudWatch.Alarm.set_state](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Alarm.set_state)

Asynchronous method. Use `await set_state(...)` for a synchronous call.

Arguments mapping described in
[SetAlarmStateInputAlarmTypeDef](./type_defs.md#setalarmstateinputalarmtypedef).

Keyword-only arguments:

- `StateValue`: [StateValueType](./literals.md#statevaluetype) *(required)*
- `StateReason`: `str` *(required)*
- `StateReasonData`: `str`

<a id="metric"></a>

## Metric

Type annotations for `aiobotocore.resource("cloudwatch").Metric` class.

Can be used directly:

```python
from types_aiobotocore_cloudwatch.service_resource import Metric

def get_resource() -> Metric:
    return boto3.resource("cloudwatch").Metric(...)
```

Boto3 documentation:
[CloudWatch.Metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.ServiceResource.Metric)

<a id="metric-attributes"></a>

### Metric attributes

- `metric_name`: `str`
- `dimensions`: `List`\[[DimensionTypeDef](./type_defs.md#dimensiontypedef)\]
- `namespace`: `str`
- `name`: `str`
- `alarms`: [MetricAlarmsCollection](#metricalarmscollection)

<a id="metric-collections"></a>

### Metric collections

<a id="metricalarms"></a>

#### Metric.alarms

Type annotations for `aiobotocore.resource("cloudwatch").Metric(...).alarms`
collection.

Can be used directly:

```python
from types_aiobotocore_cloudwatch.service_resource import MetricAlarmsCollection,

def get_collection() -> MetricAlarmsCollection:
    resource = boto3.resource("cloudwatch").Metric(...)
    return resource.alarms
```

Provides access to [Alarm](#alarm) resource.

Boto3 documentation:
[CloudWatch.Metric.MetricAlarmsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Metric.alarms)

<a id="metric-methods"></a>

### Metric methods

<a id="metricget_available_subresources-method"></a>

#### Metric.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudwatch").get_available_subresources` method.

Boto3 documentation:
[CloudWatch.Metric.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Metric.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="metricget_statistics-method"></a>

#### Metric.get_statistics method

Gets statistics for the specified metric.

Type annotations for `aiobotocore.resource("cloudwatch").get_statistics`
method.

Boto3 documentation:
[CloudWatch.Metric.get_statistics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Metric.get_statistics)

Asynchronous method. Use `await get_statistics(...)` for a synchronous call.

Arguments mapping described in
[GetMetricStatisticsInputMetricTypeDef](./type_defs.md#getmetricstatisticsinputmetrictypedef).

Keyword-only arguments:

- `StartTime`: `Union`\[`datetime`, `str`\] *(required)*
- `EndTime`: `Union`\[`datetime`, `str`\] *(required)*
- `Period`: `int` *(required)*
- `Dimensions`:
  `Sequence`\[[DimensionTypeDef](./type_defs.md#dimensiontypedef)\]
- `Statistics`: `Sequence`\[[StatisticType](./literals.md#statistictype)\]
- `ExtendedStatistics`: `Sequence`\[`str`\]
- `Unit`: [StandardUnitType](./literals.md#standardunittype)

Returns a `Coroutine` for
[GetMetricStatisticsOutputTypeDef](./type_defs.md#getmetricstatisticsoutputtypedef).

<a id="metricload-method"></a>

#### Metric.load method

Calls :py:meth:`CloudWatch.Client.list_metrics` to update the attributes of the
Metric resource.

Type annotations for `aiobotocore.resource("cloudwatch").load` method.

Boto3 documentation:
[CloudWatch.Metric.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Metric.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="metricput_alarm-method"></a>

#### Metric.put_alarm method

Creates or updates an alarm and associates it with the specified metric, metric
math expression, or anomaly detection model.

Type annotations for `aiobotocore.resource("cloudwatch").put_alarm` method.

Boto3 documentation:
[CloudWatch.Metric.put_alarm](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Metric.put_alarm)

Asynchronous method. Use `await put_alarm(...)` for a synchronous call.

Arguments mapping described in
[PutMetricAlarmInputMetricTypeDef](./type_defs.md#putmetricalarminputmetrictypedef).

Keyword-only arguments:

- `AlarmName`: `str` *(required)*
- `EvaluationPeriods`: `int` *(required)*
- `ComparisonOperator`:
  [ComparisonOperatorType](./literals.md#comparisonoperatortype) *(required)*
- `AlarmDescription`: `str`
- `ActionsEnabled`: `bool`
- `OKActions`: `Sequence`\[`str`\]
- `AlarmActions`: `Sequence`\[`str`\]
- `InsufficientDataActions`: `Sequence`\[`str`\]
- `Statistic`: [StatisticType](./literals.md#statistictype)
- `ExtendedStatistic`: `str`
- `Dimensions`:
  `Sequence`\[[DimensionTypeDef](./type_defs.md#dimensiontypedef)\]
- `Period`: `int`
- `Unit`: [StandardUnitType](./literals.md#standardunittype)
- `DatapointsToAlarm`: `int`
- `Threshold`: `float`
- `TreatMissingData`: `str`
- `EvaluateLowSampleCountPercentile`: `str`
- `Metrics`:
  `Sequence`\[[MetricDataQueryTypeDef](./type_defs.md#metricdataquerytypedef)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ThresholdMetricId`: `str`

Returns a `Coroutine` for [Alarm](#alarm).

<a id="metricput_data-method"></a>

#### Metric.put_data method

Publishes metric data points to Amazon CloudWatch.

Type annotations for `aiobotocore.resource("cloudwatch").put_data` method.

Boto3 documentation:
[CloudWatch.Metric.put_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Metric.put_data)

Asynchronous method. Use `await put_data(...)` for a synchronous call.

<a id="metricreload-method"></a>

#### Metric.reload method

Calls :py:meth:`CloudWatch.Client.list_metrics` to update the attributes of the
Metric resource.

Type annotations for `aiobotocore.resource("cloudwatch").reload` method.

Boto3 documentation:
[CloudWatch.Metric.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Metric.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.
