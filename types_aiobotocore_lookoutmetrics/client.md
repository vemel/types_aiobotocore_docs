<a id="lookoutmetricsclient-for-aiobotocore-lookoutmetrics-module"></a>

# LookoutMetricsClient for aiobotocore LookoutMetrics module

> [Index](..) > [LookoutMetrics](.) > LookoutMetricsClient

Auto-generated documentation for
[LookoutMetrics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics)
type annotations stubs module
[types-aiobotocore-lookoutmetrics](https://pypi.org/project/types-aiobotocore-lookoutmetrics/).

- [LookoutMetricsClient for aiobotocore LookoutMetrics module](#lookoutmetricsclient-for-aiobotocore-lookoutmetrics-module)
  - [LookoutMetricsClient](#lookoutmetricsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [activate_anomaly_detector](#activate_anomaly_detector)
    - [back_test_anomaly_detector](#back_test_anomaly_detector)
    - [can_paginate](#can_paginate)
    - [create_alert](#create_alert)
    - [create_anomaly_detector](#create_anomaly_detector)
    - [create_metric_set](#create_metric_set)
    - [delete_alert](#delete_alert)
    - [delete_anomaly_detector](#delete_anomaly_detector)
    - [describe_alert](#describe_alert)
    - [describe_anomaly_detection_executions](#describe_anomaly_detection_executions)
    - [describe_anomaly_detector](#describe_anomaly_detector)
    - [describe_metric_set](#describe_metric_set)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_anomaly_group](#get_anomaly_group)
    - [get_feedback](#get_feedback)
    - [get_sample_data](#get_sample_data)
    - [list_alerts](#list_alerts)
    - [list_anomaly_detectors](#list_anomaly_detectors)
    - [list_anomaly_group_summaries](#list_anomaly_group_summaries)
    - [list_anomaly_group_time_series](#list_anomaly_group_time_series)
    - [list_metric_sets](#list_metric_sets)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_feedback](#put_feedback)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_anomaly_detector](#update_anomaly_detector)
    - [update_metric_set](#update_metric_set)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)

<a id="lookoutmetricsclient"></a>

## LookoutMetricsClient

Type annotations for `session.create_client("lookoutmetrics")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_lookoutmetrics.client import LookoutMetricsClient

session = get_session()
async with session.create_client("lookoutmetrics") as client:
    client: LookoutMetricsClient
```

Boto3 documentation:
[LookoutMetrics.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_lookoutmetrics.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.TooManyRequestsException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

LookoutMetricsClient exceptions.

Type annotations for `session.create_client("lookoutmetrics").exceptions`
method.

Boto3 documentation:
[LookoutMetrics.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="activate_anomaly_detector"></a>

### activate_anomaly_detector

Activates an anomaly detector.

Type annotations for
`session.create_client("lookoutmetrics").activate_anomaly_detector` method.

Boto3 documentation:
[LookoutMetrics.Client.activate_anomaly_detector](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.activate_anomaly_detector)

Asynchronous method. Use `await activate_anomaly_detector(...)` for a
synchronous call.

Arguments mapping described in
[ActivateAnomalyDetectorRequestRequestTypeDef](./type_defs.md#activateanomalydetectorrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="back_test_anomaly_detector"></a>

### back_test_anomaly_detector

Runs a backtest for anomaly detection for the specified resource.

Type annotations for
`session.create_client("lookoutmetrics").back_test_anomaly_detector` method.

Boto3 documentation:
[LookoutMetrics.Client.back_test_anomaly_detector](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.back_test_anomaly_detector)

Asynchronous method. Use `await back_test_anomaly_detector(...)` for a
synchronous call.

Arguments mapping described in
[BackTestAnomalyDetectorRequestRequestTypeDef](./type_defs.md#backtestanomalydetectorrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("lookoutmetrics").can_paginate`
method.

Boto3 documentation:
[LookoutMetrics.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_alert"></a>

### create_alert

Creates an alert for an anomaly detector.

Type annotations for `session.create_client("lookoutmetrics").create_alert`
method.

Boto3 documentation:
[LookoutMetrics.Client.create_alert](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.create_alert)

Asynchronous method. Use `await create_alert(...)` for a synchronous call.

Arguments mapping described in
[CreateAlertRequestRequestTypeDef](./type_defs.md#createalertrequestrequesttypedef).

Keyword-only arguments:

- `AlertName`: `str` *(required)*
- `AlertSensitivityThreshold`: `int` *(required)*
- `AnomalyDetectorArn`: `str` *(required)*
- `Action`: [ActionTypeDef](./type_defs.md#actiontypedef) *(required)*
- `AlertDescription`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateAlertResponseTypeDef](./type_defs.md#createalertresponsetypedef).

<a id="create_anomaly_detector"></a>

### create_anomaly_detector

Creates an anomaly detector.

Type annotations for
`session.create_client("lookoutmetrics").create_anomaly_detector` method.

Boto3 documentation:
[LookoutMetrics.Client.create_anomaly_detector](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.create_anomaly_detector)

Asynchronous method. Use `await create_anomaly_detector(...)` for a synchronous
call.

Arguments mapping described in
[CreateAnomalyDetectorRequestRequestTypeDef](./type_defs.md#createanomalydetectorrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorName`: `str` *(required)*
- `AnomalyDetectorConfig`:
  [AnomalyDetectorConfigTypeDef](./type_defs.md#anomalydetectorconfigtypedef)
  *(required)*
- `AnomalyDetectorDescription`: `str`
- `KmsKeyArn`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateAnomalyDetectorResponseTypeDef](./type_defs.md#createanomalydetectorresponsetypedef).

<a id="create_metric_set"></a>

### create_metric_set

Creates a dataset.

Type annotations for
`session.create_client("lookoutmetrics").create_metric_set` method.

Boto3 documentation:
[LookoutMetrics.Client.create_metric_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.create_metric_set)

Asynchronous method. Use `await create_metric_set(...)` for a synchronous call.

Arguments mapping described in
[CreateMetricSetRequestRequestTypeDef](./type_defs.md#createmetricsetrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*
- `MetricSetName`: `str` *(required)*
- `MetricList`: `Sequence`\[[MetricTypeDef](./type_defs.md#metrictypedef)\]
  *(required)*
- `MetricSource`: [MetricSourceTypeDef](./type_defs.md#metricsourcetypedef)
  *(required)*
- `MetricSetDescription`: `str`
- `Offset`: `int`
- `TimestampColumn`:
  [TimestampColumnTypeDef](./type_defs.md#timestampcolumntypedef)
- `DimensionList`: `Sequence`\[`str`\]
- `MetricSetFrequency`: [FrequencyType](./literals.md#frequencytype)
- `Timezone`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateMetricSetResponseTypeDef](./type_defs.md#createmetricsetresponsetypedef).

<a id="delete_alert"></a>

### delete_alert

Deletes an alert.

Type annotations for `session.create_client("lookoutmetrics").delete_alert`
method.

Boto3 documentation:
[LookoutMetrics.Client.delete_alert](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.delete_alert)

Asynchronous method. Use `await delete_alert(...)` for a synchronous call.

Arguments mapping described in
[DeleteAlertRequestRequestTypeDef](./type_defs.md#deletealertrequestrequesttypedef).

Keyword-only arguments:

- `AlertArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_anomaly_detector"></a>

### delete_anomaly_detector

Deletes a detector.

Type annotations for
`session.create_client("lookoutmetrics").delete_anomaly_detector` method.

Boto3 documentation:
[LookoutMetrics.Client.delete_anomaly_detector](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.delete_anomaly_detector)

Asynchronous method. Use `await delete_anomaly_detector(...)` for a synchronous
call.

Arguments mapping described in
[DeleteAnomalyDetectorRequestRequestTypeDef](./type_defs.md#deleteanomalydetectorrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_alert"></a>

### describe_alert

Describes an alert.

Type annotations for `session.create_client("lookoutmetrics").describe_alert`
method.

Boto3 documentation:
[LookoutMetrics.Client.describe_alert](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.describe_alert)

Asynchronous method. Use `await describe_alert(...)` for a synchronous call.

Arguments mapping described in
[DescribeAlertRequestRequestTypeDef](./type_defs.md#describealertrequestrequesttypedef).

Keyword-only arguments:

- `AlertArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAlertResponseTypeDef](./type_defs.md#describealertresponsetypedef).

<a id="describe_anomaly_detection_executions"></a>

### describe_anomaly_detection_executions

Returns information about the status of the specified anomaly detection jobs.

Type annotations for
`session.create_client("lookoutmetrics").describe_anomaly_detection_executions`
method.

Boto3 documentation:
[LookoutMetrics.Client.describe_anomaly_detection_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.describe_anomaly_detection_executions)

Asynchronous method. Use `await describe_anomaly_detection_executions(...)` for
a synchronous call.

Arguments mapping described in
[DescribeAnomalyDetectionExecutionsRequestRequestTypeDef](./type_defs.md#describeanomalydetectionexecutionsrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*
- `Timestamp`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeAnomalyDetectionExecutionsResponseTypeDef](./type_defs.md#describeanomalydetectionexecutionsresponsetypedef).

<a id="describe_anomaly_detector"></a>

### describe_anomaly_detector

Describes a detector.

Type annotations for
`session.create_client("lookoutmetrics").describe_anomaly_detector` method.

Boto3 documentation:
[LookoutMetrics.Client.describe_anomaly_detector](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.describe_anomaly_detector)

Asynchronous method. Use `await describe_anomaly_detector(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAnomalyDetectorRequestRequestTypeDef](./type_defs.md#describeanomalydetectorrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAnomalyDetectorResponseTypeDef](./type_defs.md#describeanomalydetectorresponsetypedef).

<a id="describe_metric_set"></a>

### describe_metric_set

Describes a dataset.

Type annotations for
`session.create_client("lookoutmetrics").describe_metric_set` method.

Boto3 documentation:
[LookoutMetrics.Client.describe_metric_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.describe_metric_set)

Asynchronous method. Use `await describe_metric_set(...)` for a synchronous
call.

Arguments mapping described in
[DescribeMetricSetRequestRequestTypeDef](./type_defs.md#describemetricsetrequestrequesttypedef).

Keyword-only arguments:

- `MetricSetArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeMetricSetResponseTypeDef](./type_defs.md#describemetricsetresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("lookoutmetrics").generate_presigned_url` method.

Boto3 documentation:
[LookoutMetrics.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_anomaly_group"></a>

### get_anomaly_group

Returns details about a group of anomalous metrics.

Type annotations for
`session.create_client("lookoutmetrics").get_anomaly_group` method.

Boto3 documentation:
[LookoutMetrics.Client.get_anomaly_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.get_anomaly_group)

Asynchronous method. Use `await get_anomaly_group(...)` for a synchronous call.

Arguments mapping described in
[GetAnomalyGroupRequestRequestTypeDef](./type_defs.md#getanomalygrouprequestrequesttypedef).

Keyword-only arguments:

- `AnomalyGroupId`: `str` *(required)*
- `AnomalyDetectorArn`: `str` *(required)*

Returns a `Coroutine` for
[GetAnomalyGroupResponseTypeDef](./type_defs.md#getanomalygroupresponsetypedef).

<a id="get_feedback"></a>

### get_feedback

Get feedback for an anomaly group.

Type annotations for `session.create_client("lookoutmetrics").get_feedback`
method.

Boto3 documentation:
[LookoutMetrics.Client.get_feedback](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.get_feedback)

Asynchronous method. Use `await get_feedback(...)` for a synchronous call.

Arguments mapping described in
[GetFeedbackRequestRequestTypeDef](./type_defs.md#getfeedbackrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*
- `AnomalyGroupTimeSeriesFeedback`:
  [AnomalyGroupTimeSeriesTypeDef](./type_defs.md#anomalygrouptimeseriestypedef)
  *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetFeedbackResponseTypeDef](./type_defs.md#getfeedbackresponsetypedef).

<a id="get_sample_data"></a>

### get_sample_data

Returns a selection of sample records from an Amazon S3 datasource.

Type annotations for `session.create_client("lookoutmetrics").get_sample_data`
method.

Boto3 documentation:
[LookoutMetrics.Client.get_sample_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.get_sample_data)

Asynchronous method. Use `await get_sample_data(...)` for a synchronous call.

Arguments mapping described in
[GetSampleDataRequestRequestTypeDef](./type_defs.md#getsampledatarequestrequesttypedef).

Keyword-only arguments:

- `S3SourceConfig`:
  [SampleDataS3SourceConfigTypeDef](./type_defs.md#sampledatas3sourceconfigtypedef)

Returns a `Coroutine` for
[GetSampleDataResponseTypeDef](./type_defs.md#getsampledataresponsetypedef).

<a id="list_alerts"></a>

### list_alerts

Lists the alerts attached to a detector.

Type annotations for `session.create_client("lookoutmetrics").list_alerts`
method.

Boto3 documentation:
[LookoutMetrics.Client.list_alerts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.list_alerts)

Asynchronous method. Use `await list_alerts(...)` for a synchronous call.

Arguments mapping described in
[ListAlertsRequestRequestTypeDef](./type_defs.md#listalertsrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListAlertsResponseTypeDef](./type_defs.md#listalertsresponsetypedef).

<a id="list_anomaly_detectors"></a>

### list_anomaly_detectors

Lists the detectors in the current AWS Region.

Type annotations for
`session.create_client("lookoutmetrics").list_anomaly_detectors` method.

Boto3 documentation:
[LookoutMetrics.Client.list_anomaly_detectors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.list_anomaly_detectors)

Asynchronous method. Use `await list_anomaly_detectors(...)` for a synchronous
call.

Arguments mapping described in
[ListAnomalyDetectorsRequestRequestTypeDef](./type_defs.md#listanomalydetectorsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAnomalyDetectorsResponseTypeDef](./type_defs.md#listanomalydetectorsresponsetypedef).

<a id="list_anomaly_group_summaries"></a>

### list_anomaly_group_summaries

Returns a list of anomaly groups.

Type annotations for
`session.create_client("lookoutmetrics").list_anomaly_group_summaries` method.

Boto3 documentation:
[LookoutMetrics.Client.list_anomaly_group_summaries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.list_anomaly_group_summaries)

Asynchronous method. Use `await list_anomaly_group_summaries(...)` for a
synchronous call.

Arguments mapping described in
[ListAnomalyGroupSummariesRequestRequestTypeDef](./type_defs.md#listanomalygroupsummariesrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*
- `SensitivityThreshold`: `int` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAnomalyGroupSummariesResponseTypeDef](./type_defs.md#listanomalygroupsummariesresponsetypedef).

<a id="list_anomaly_group_time_series"></a>

### list_anomaly_group_time_series

Gets a list of anomalous metrics for a measure in an anomaly group.

Type annotations for
`session.create_client("lookoutmetrics").list_anomaly_group_time_series`
method.

Boto3 documentation:
[LookoutMetrics.Client.list_anomaly_group_time_series](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.list_anomaly_group_time_series)

Asynchronous method. Use `await list_anomaly_group_time_series(...)` for a
synchronous call.

Arguments mapping described in
[ListAnomalyGroupTimeSeriesRequestRequestTypeDef](./type_defs.md#listanomalygrouptimeseriesrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*
- `AnomalyGroupId`: `str` *(required)*
- `MetricName`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAnomalyGroupTimeSeriesResponseTypeDef](./type_defs.md#listanomalygrouptimeseriesresponsetypedef).

<a id="list_metric_sets"></a>

### list_metric_sets

Lists the datasets in the current AWS Region.

Type annotations for `session.create_client("lookoutmetrics").list_metric_sets`
method.

Boto3 documentation:
[LookoutMetrics.Client.list_metric_sets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.list_metric_sets)

Asynchronous method. Use `await list_metric_sets(...)` for a synchronous call.

Arguments mapping described in
[ListMetricSetsRequestRequestTypeDef](./type_defs.md#listmetricsetsrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListMetricSetsResponseTypeDef](./type_defs.md#listmetricsetsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Gets a list of
\[tags\](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/detectors-
tags.html)\_ for a detector, dataset, or alert.

Type annotations for
`session.create_client("lookoutmetrics").list_tags_for_resource` method.

Boto3 documentation:
[LookoutMetrics.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_feedback"></a>

### put_feedback

Add feedback for an anomalous metric.

Type annotations for `session.create_client("lookoutmetrics").put_feedback`
method.

Boto3 documentation:
[LookoutMetrics.Client.put_feedback](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.put_feedback)

Asynchronous method. Use `await put_feedback(...)` for a synchronous call.

Arguments mapping described in
[PutFeedbackRequestRequestTypeDef](./type_defs.md#putfeedbackrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*
- `AnomalyGroupTimeSeriesFeedback`:
  [AnomalyGroupTimeSeriesFeedbackTypeDef](./type_defs.md#anomalygrouptimeseriesfeedbacktypedef)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Adds \[tags\](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/detectors-
tags.html)\_ to a detector, dataset, or alert.

Type annotations for `session.create_client("lookoutmetrics").tag_resource`
method.

Boto3 documentation:
[LookoutMetrics.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes
\[tags\](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/detectors-
tags.html)\_ from a detector, dataset, or alert.

Type annotations for `session.create_client("lookoutmetrics").untag_resource`
method.

Boto3 documentation:
[LookoutMetrics.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_anomaly_detector"></a>

### update_anomaly_detector

Updates a detector.

Type annotations for
`session.create_client("lookoutmetrics").update_anomaly_detector` method.

Boto3 documentation:
[LookoutMetrics.Client.update_anomaly_detector](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.update_anomaly_detector)

Asynchronous method. Use `await update_anomaly_detector(...)` for a synchronous
call.

Arguments mapping described in
[UpdateAnomalyDetectorRequestRequestTypeDef](./type_defs.md#updateanomalydetectorrequestrequesttypedef).

Keyword-only arguments:

- `AnomalyDetectorArn`: `str` *(required)*
- `KmsKeyArn`: `str`
- `AnomalyDetectorDescription`: `str`
- `AnomalyDetectorConfig`:
  [AnomalyDetectorConfigTypeDef](./type_defs.md#anomalydetectorconfigtypedef)

Returns a `Coroutine` for
[UpdateAnomalyDetectorResponseTypeDef](./type_defs.md#updateanomalydetectorresponsetypedef).

<a id="update_metric_set"></a>

### update_metric_set

Updates a dataset.

Type annotations for
`session.create_client("lookoutmetrics").update_metric_set` method.

Boto3 documentation:
[LookoutMetrics.Client.update_metric_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.update_metric_set)

Asynchronous method. Use `await update_metric_set(...)` for a synchronous call.

Arguments mapping described in
[UpdateMetricSetRequestRequestTypeDef](./type_defs.md#updatemetricsetrequestrequesttypedef).

Keyword-only arguments:

- `MetricSetArn`: `str` *(required)*
- `MetricSetDescription`: `str`
- `MetricList`: `Sequence`\[[MetricTypeDef](./type_defs.md#metrictypedef)\]
- `Offset`: `int`
- `TimestampColumn`:
  [TimestampColumnTypeDef](./type_defs.md#timestampcolumntypedef)
- `DimensionList`: `Sequence`\[`str`\]
- `MetricSetFrequency`: [FrequencyType](./literals.md#frequencytype)
- `MetricSource`: [MetricSourceTypeDef](./type_defs.md#metricsourcetypedef)

Returns a `Coroutine` for
[UpdateMetricSetResponseTypeDef](./type_defs.md#updatemetricsetresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("lookoutmetrics").__aenter__`
method.

Boto3 documentation:
[LookoutMetrics.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [LookoutMetricsClient](#lookoutmetricsclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("lookoutmetrics").__aexit__`
method.

Boto3 documentation:
[LookoutMetrics.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
