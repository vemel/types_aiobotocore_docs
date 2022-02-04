<a id="typed-dictionaries-for-aiobotocore-autoscalingplans-module"></a>

# Typed dictionaries for aiobotocore AutoScalingPlans module

> [Index](..) > [AutoScalingPlans](.) > Typed dictionaries

Auto-generated documentation for
[AutoScalingPlans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
type annotations stubs module
[types-aiobotocore-autoscaling-plans](https://pypi.org/project/types-aiobotocore-autoscaling-plans/).

- [Typed dictionaries for aiobotocore AutoScalingPlans module](#typed-dictionaries-for-aiobotocore-autoscalingplans-module)
  - [ApplicationSourceTypeDef](#applicationsourcetypedef)
  - [CreateScalingPlanRequestRequestTypeDef](#createscalingplanrequestrequesttypedef)
  - [CreateScalingPlanResponseTypeDef](#createscalingplanresponsetypedef)
  - [CustomizedLoadMetricSpecificationTypeDef](#customizedloadmetricspecificationtypedef)
  - [CustomizedScalingMetricSpecificationTypeDef](#customizedscalingmetricspecificationtypedef)
  - [DatapointTypeDef](#datapointtypedef)
  - [DeleteScalingPlanRequestRequestTypeDef](#deletescalingplanrequestrequesttypedef)
  - [DescribeScalingPlanResourcesRequestRequestTypeDef](#describescalingplanresourcesrequestrequesttypedef)
  - [DescribeScalingPlanResourcesResponseTypeDef](#describescalingplanresourcesresponsetypedef)
  - [DescribeScalingPlansRequestRequestTypeDef](#describescalingplansrequestrequesttypedef)
  - [DescribeScalingPlansResponseTypeDef](#describescalingplansresponsetypedef)
  - [GetScalingPlanResourceForecastDataRequestRequestTypeDef](#getscalingplanresourceforecastdatarequestrequesttypedef)
  - [GetScalingPlanResourceForecastDataResponseTypeDef](#getscalingplanresourceforecastdataresponsetypedef)
  - [MetricDimensionTypeDef](#metricdimensiontypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PredefinedLoadMetricSpecificationTypeDef](#predefinedloadmetricspecificationtypedef)
  - [PredefinedScalingMetricSpecificationTypeDef](#predefinedscalingmetricspecificationtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ScalingInstructionTypeDef](#scalinginstructiontypedef)
  - [ScalingPlanResourceTypeDef](#scalingplanresourcetypedef)
  - [ScalingPlanTypeDef](#scalingplantypedef)
  - [ScalingPolicyTypeDef](#scalingpolicytypedef)
  - [TagFilterTypeDef](#tagfiltertypedef)
  - [TargetTrackingConfigurationTypeDef](#targettrackingconfigurationtypedef)
  - [UpdateScalingPlanRequestRequestTypeDef](#updatescalingplanrequestrequesttypedef)

<a id="applicationsourcetypedef"></a>

## ApplicationSourceTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import ApplicationSourceTypeDef
```

Optional fields:

- `CloudFormationStackARN`: `str`
- `TagFilters`:
  `Sequence`\[[TagFilterTypeDef](./type_defs.md#tagfiltertypedef)\]

<a id="createscalingplanrequestrequesttypedef"></a>

## CreateScalingPlanRequestRequestTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import CreateScalingPlanRequestRequestTypeDef
```

Required fields:

- `ScalingPlanName`: `str`
- `ApplicationSource`:
  [ApplicationSourceTypeDef](./type_defs.md#applicationsourcetypedef)
- `ScalingInstructions`:
  `Sequence`\[[ScalingInstructionTypeDef](./type_defs.md#scalinginstructiontypedef)\]

<a id="createscalingplanresponsetypedef"></a>

## CreateScalingPlanResponseTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import CreateScalingPlanResponseTypeDef
```

Required fields:

- `ScalingPlanVersion`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="customizedloadmetricspecificationtypedef"></a>

## CustomizedLoadMetricSpecificationTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import CustomizedLoadMetricSpecificationTypeDef
```

Required fields:

- `MetricName`: `str`
- `Namespace`: `str`
- `Statistic`: [MetricStatisticType](./literals.md#metricstatistictype)

Optional fields:

- `Dimensions`:
  `Sequence`\[[MetricDimensionTypeDef](./type_defs.md#metricdimensiontypedef)\]
- `Unit`: `str`

<a id="customizedscalingmetricspecificationtypedef"></a>

## CustomizedScalingMetricSpecificationTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import CustomizedScalingMetricSpecificationTypeDef
```

Required fields:

- `MetricName`: `str`
- `Namespace`: `str`
- `Statistic`: [MetricStatisticType](./literals.md#metricstatistictype)

Optional fields:

- `Dimensions`:
  `Sequence`\[[MetricDimensionTypeDef](./type_defs.md#metricdimensiontypedef)\]
- `Unit`: `str`

<a id="datapointtypedef"></a>

## DatapointTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import DatapointTypeDef
```

Optional fields:

- `Timestamp`: `datetime`
- `Value`: `float`

<a id="deletescalingplanrequestrequesttypedef"></a>

## DeleteScalingPlanRequestRequestTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import DeleteScalingPlanRequestRequestTypeDef
```

Required fields:

- `ScalingPlanName`: `str`
- `ScalingPlanVersion`: `int`

<a id="describescalingplanresourcesrequestrequesttypedef"></a>

## DescribeScalingPlanResourcesRequestRequestTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import DescribeScalingPlanResourcesRequestRequestTypeDef
```

Required fields:

- `ScalingPlanName`: `str`
- `ScalingPlanVersion`: `int`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describescalingplanresourcesresponsetypedef"></a>

## DescribeScalingPlanResourcesResponseTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import DescribeScalingPlanResourcesResponseTypeDef
```

Required fields:

- `ScalingPlanResources`:
  `List`\[[ScalingPlanResourceTypeDef](./type_defs.md#scalingplanresourcetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describescalingplansrequestrequesttypedef"></a>

## DescribeScalingPlansRequestRequestTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import DescribeScalingPlansRequestRequestTypeDef
```

Optional fields:

- `ScalingPlanNames`: `Sequence`\[`str`\]
- `ScalingPlanVersion`: `int`
- `ApplicationSources`:
  `Sequence`\[[ApplicationSourceTypeDef](./type_defs.md#applicationsourcetypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describescalingplansresponsetypedef"></a>

## DescribeScalingPlansResponseTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import DescribeScalingPlansResponseTypeDef
```

Required fields:

- `ScalingPlans`:
  `List`\[[ScalingPlanTypeDef](./type_defs.md#scalingplantypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getscalingplanresourceforecastdatarequestrequesttypedef"></a>

## GetScalingPlanResourceForecastDataRequestRequestTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import GetScalingPlanResourceForecastDataRequestRequestTypeDef
```

Required fields:

- `ScalingPlanName`: `str`
- `ScalingPlanVersion`: `int`
- `ServiceNamespace`:
  [ServiceNamespaceType](./literals.md#servicenamespacetype)
- `ResourceId`: `str`
- `ScalableDimension`:
  [ScalableDimensionType](./literals.md#scalabledimensiontype)
- `ForecastDataType`:
  [ForecastDataTypeType](./literals.md#forecastdatatypetype)
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]

<a id="getscalingplanresourceforecastdataresponsetypedef"></a>

## GetScalingPlanResourceForecastDataResponseTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import GetScalingPlanResourceForecastDataResponseTypeDef
```

Required fields:

- `Datapoints`: `List`\[[DatapointTypeDef](./type_defs.md#datapointtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="metricdimensiontypedef"></a>

## MetricDimensionTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import MetricDimensionTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="predefinedloadmetricspecificationtypedef"></a>

## PredefinedLoadMetricSpecificationTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import PredefinedLoadMetricSpecificationTypeDef
```

Required fields:

- `PredefinedLoadMetricType`:
  [LoadMetricTypeType](./literals.md#loadmetrictypetype)

Optional fields:

- `ResourceLabel`: `str`

<a id="predefinedscalingmetricspecificationtypedef"></a>

## PredefinedScalingMetricSpecificationTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import PredefinedScalingMetricSpecificationTypeDef
```

Required fields:

- `PredefinedScalingMetricType`:
  [ScalingMetricTypeType](./literals.md#scalingmetrictypetype)

Optional fields:

- `ResourceLabel`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="scalinginstructiontypedef"></a>

## ScalingInstructionTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import ScalingInstructionTypeDef
```

Required fields:

- `ServiceNamespace`:
  [ServiceNamespaceType](./literals.md#servicenamespacetype)
- `ResourceId`: `str`
- `ScalableDimension`:
  [ScalableDimensionType](./literals.md#scalabledimensiontype)
- `MinCapacity`: `int`
- `MaxCapacity`: `int`
- `TargetTrackingConfigurations`:
  `Sequence`\[[TargetTrackingConfigurationTypeDef](./type_defs.md#targettrackingconfigurationtypedef)\]

Optional fields:

- `PredefinedLoadMetricSpecification`:
  [PredefinedLoadMetricSpecificationTypeDef](./type_defs.md#predefinedloadmetricspecificationtypedef)
- `CustomizedLoadMetricSpecification`:
  [CustomizedLoadMetricSpecificationTypeDef](./type_defs.md#customizedloadmetricspecificationtypedef)
- `ScheduledActionBufferTime`: `int`
- `PredictiveScalingMaxCapacityBehavior`:
  [PredictiveScalingMaxCapacityBehaviorType](./literals.md#predictivescalingmaxcapacitybehaviortype)
- `PredictiveScalingMaxCapacityBuffer`: `int`
- `PredictiveScalingMode`:
  [PredictiveScalingModeType](./literals.md#predictivescalingmodetype)
- `ScalingPolicyUpdateBehavior`:
  [ScalingPolicyUpdateBehaviorType](./literals.md#scalingpolicyupdatebehaviortype)
- `DisableDynamicScaling`: `bool`

<a id="scalingplanresourcetypedef"></a>

## ScalingPlanResourceTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import ScalingPlanResourceTypeDef
```

Required fields:

- `ScalingPlanName`: `str`
- `ScalingPlanVersion`: `int`
- `ServiceNamespace`:
  [ServiceNamespaceType](./literals.md#servicenamespacetype)
- `ResourceId`: `str`
- `ScalableDimension`:
  [ScalableDimensionType](./literals.md#scalabledimensiontype)
- `ScalingStatusCode`:
  [ScalingStatusCodeType](./literals.md#scalingstatuscodetype)

Optional fields:

- `ScalingPolicies`:
  `List`\[[ScalingPolicyTypeDef](./type_defs.md#scalingpolicytypedef)\]
- `ScalingStatusMessage`: `str`

<a id="scalingplantypedef"></a>

## ScalingPlanTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import ScalingPlanTypeDef
```

Required fields:

- `ScalingPlanName`: `str`
- `ScalingPlanVersion`: `int`
- `ApplicationSource`:
  [ApplicationSourceTypeDef](./type_defs.md#applicationsourcetypedef)
- `ScalingInstructions`:
  `List`\[[ScalingInstructionTypeDef](./type_defs.md#scalinginstructiontypedef)\]
- `StatusCode`:
  [ScalingPlanStatusCodeType](./literals.md#scalingplanstatuscodetype)

Optional fields:

- `StatusMessage`: `str`
- `StatusStartTime`: `datetime`
- `CreationTime`: `datetime`

<a id="scalingpolicytypedef"></a>

## ScalingPolicyTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import ScalingPolicyTypeDef
```

Required fields:

- `PolicyName`: `str`
- `PolicyType`: `Literal['TargetTrackingScaling']` (see
  [PolicyTypeType](./literals.md#policytypetype))

Optional fields:

- `TargetTrackingConfiguration`:
  [TargetTrackingConfigurationTypeDef](./type_defs.md#targettrackingconfigurationtypedef)

<a id="tagfiltertypedef"></a>

## TagFilterTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import TagFilterTypeDef
```

Optional fields:

- `Key`: `str`
- `Values`: `Sequence`\[`str`\]

<a id="targettrackingconfigurationtypedef"></a>

## TargetTrackingConfigurationTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import TargetTrackingConfigurationTypeDef
```

Required fields:

- `TargetValue`: `float`

Optional fields:

- `PredefinedScalingMetricSpecification`:
  [PredefinedScalingMetricSpecificationTypeDef](./type_defs.md#predefinedscalingmetricspecificationtypedef)
- `CustomizedScalingMetricSpecification`:
  [CustomizedScalingMetricSpecificationTypeDef](./type_defs.md#customizedscalingmetricspecificationtypedef)
- `DisableScaleIn`: `bool`
- `ScaleOutCooldown`: `int`
- `ScaleInCooldown`: `int`
- `EstimatedInstanceWarmup`: `int`

<a id="updatescalingplanrequestrequesttypedef"></a>

## UpdateScalingPlanRequestRequestTypeDef

```python
from types_aiobotocore_autoscaling_plans.type_defs import UpdateScalingPlanRequestRequestTypeDef
```

Required fields:

- `ScalingPlanName`: `str`
- `ScalingPlanVersion`: `int`

Optional fields:

- `ApplicationSource`:
  [ApplicationSourceTypeDef](./type_defs.md#applicationsourcetypedef)
- `ScalingInstructions`:
  `Sequence`\[[ScalingInstructionTypeDef](./type_defs.md#scalinginstructiontypedef)\]
