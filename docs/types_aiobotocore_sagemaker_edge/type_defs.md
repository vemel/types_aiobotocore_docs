<a id="typed-dictionaries-for-aiobotocore-sagemakeredgemanager-module"></a>

# Typed dictionaries for aiobotocore SagemakerEdgeManager module

> [Index](../README.md) > [SagemakerEdgeManager](./README.md) > Typed
> dictionaries

Auto-generated documentation for
[SagemakerEdgeManager](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager)
type annotations stubs module
[types-aiobotocore-sagemaker-edge](https://pypi.org/project/types-aiobotocore-sagemaker-edge/).

- [Typed dictionaries for aiobotocore SagemakerEdgeManager module](#typed-dictionaries-for-aiobotocore-sagemakeredgemanager-module)
  - [EdgeMetricTypeDef](#edgemetrictypedef)
  - [GetDeviceRegistrationRequestRequestTypeDef](#getdeviceregistrationrequestrequesttypedef)
  - [GetDeviceRegistrationResultTypeDef](#getdeviceregistrationresulttypedef)
  - [ModelTypeDef](#modeltypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SendHeartbeatRequestRequestTypeDef](#sendheartbeatrequestrequesttypedef)

<a id="edgemetrictypedef"></a>

## EdgeMetricTypeDef

```python
from types_aiobotocore_sagemaker_edge.type_defs import EdgeMetricTypeDef
```

Optional fields:

- `Dimension`: `str`
- `MetricName`: `str`
- `Value`: `float`
- `Timestamp`: `Union`\[`datetime`, `str`\]

<a id="getdeviceregistrationrequestrequesttypedef"></a>

## GetDeviceRegistrationRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker_edge.type_defs import GetDeviceRegistrationRequestRequestTypeDef
```

Required fields:

- `DeviceName`: `str`
- `DeviceFleetName`: `str`

<a id="getdeviceregistrationresulttypedef"></a>

## GetDeviceRegistrationResultTypeDef

```python
from types_aiobotocore_sagemaker_edge.type_defs import GetDeviceRegistrationResultTypeDef
```

Required fields:

- `DeviceRegistration`: `str`
- `CacheTTL`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="modeltypedef"></a>

## ModelTypeDef

```python
from types_aiobotocore_sagemaker_edge.type_defs import ModelTypeDef
```

Optional fields:

- `ModelName`: `str`
- `ModelVersion`: `str`
- `LatestSampleTime`: `Union`\[`datetime`, `str`\]
- `LatestInference`: `Union`\[`datetime`, `str`\]
- `ModelMetrics`:
  `Sequence`\[[EdgeMetricTypeDef](./type_defs.md#edgemetrictypedef)\]

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_sagemaker_edge.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="sendheartbeatrequestrequesttypedef"></a>

## SendHeartbeatRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker_edge.type_defs import SendHeartbeatRequestRequestTypeDef
```

Required fields:

- `AgentVersion`: `str`
- `DeviceName`: `str`
- `DeviceFleetName`: `str`

Optional fields:

- `AgentMetrics`:
  `Sequence`\[[EdgeMetricTypeDef](./type_defs.md#edgemetrictypedef)\]
- `Models`: `Sequence`\[[ModelTypeDef](./type_defs.md#modeltypedef)\]
