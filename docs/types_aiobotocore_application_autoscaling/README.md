<a id="type-annotations-for-aiobotocore-applicationautoscaling-module"></a>

# Type annotations for aiobotocore ApplicationAutoScaling module

> [Index](../README.md) > ApplicationAutoScaling

Auto-generated documentation for
[ApplicationAutoScaling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
type annotations stubs module
[types-aiobotocore-application-autoscaling](https://pypi.org/project/types-aiobotocore-application-autoscaling/).

- [Type annotations for aiobotocore ApplicationAutoScaling module](#type-annotations-for-aiobotocore-applicationautoscaling-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [ApplicationAutoScalingClient](#applicationautoscalingclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `ApplicationAutoScaling`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `ApplicationAutoScaling` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[application-autoscaling]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[application-autoscaling]'


# standalone installation
python -m pip install types-aiobotocore-application-autoscaling
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-application-autoscaling
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="applicationautoscalingclient"></a>

## ApplicationAutoScalingClient

Type annotations for `session.create_client("application-autoscaling")` as
[ApplicationAutoScalingClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_application_autoscaling.client import ApplicationAutoScalingClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [delete_scaling_policy](./client.md#delete_scaling_policy)
- [delete_scheduled_action](./client.md#delete_scheduled_action)
- [deregister_scalable_target](./client.md#deregister_scalable_target)
- [describe_scalable_targets](./client.md#describe_scalable_targets)
- [describe_scaling_activities](./client.md#describe_scaling_activities)
- [describe_scaling_policies](./client.md#describe_scaling_policies)
- [describe_scheduled_actions](./client.md#describe_scheduled_actions)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [put_scaling_policy](./client.md#put_scaling_policy)
- [put_scheduled_action](./client.md#put_scheduled_action)
- [register_scalable_target](./client.md#register_scalable_target)

<a id="exceptions"></a>

### Exceptions

ApplicationAutoScalingClient [exceptions](./client.md#exceptions)

- ClientError
- ConcurrentUpdateException
- FailedResourceAccessException
- InternalServiceException
- InvalidNextTokenException
- LimitExceededException
- ObjectNotFoundException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("application-autoscaling").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_application_autoscaling.paginator import DescribeScalableTargetsPaginator, ...
```

- [DescribeScalableTargetsPaginator](./paginators.md#describescalabletargetspaginator)
- [DescribeScalingActivitiesPaginator](./paginators.md#describescalingactivitiespaginator)
- [DescribeScalingPoliciesPaginator](./paginators.md#describescalingpoliciespaginator)
- [DescribeScheduledActionsPaginator](./paginators.md#describescheduledactionspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_application_autoscaling.literals import AdjustmentTypeType, ...
```

- [AdjustmentTypeType](./literals.md#adjustmenttypetype)
- [DescribeScalableTargetsPaginatorName](./literals.md#describescalabletargetspaginatorname)
- [DescribeScalingActivitiesPaginatorName](./literals.md#describescalingactivitiespaginatorname)
- [DescribeScalingPoliciesPaginatorName](./literals.md#describescalingpoliciespaginatorname)
- [DescribeScheduledActionsPaginatorName](./literals.md#describescheduledactionspaginatorname)
- [MetricAggregationTypeType](./literals.md#metricaggregationtypetype)
- [MetricStatisticType](./literals.md#metricstatistictype)
- [MetricTypeType](./literals.md#metrictypetype)
- [PolicyTypeType](./literals.md#policytypetype)
- [ScalableDimensionType](./literals.md#scalabledimensiontype)
- [ScalingActivityStatusCodeType](./literals.md#scalingactivitystatuscodetype)
- [ServiceNamespaceType](./literals.md#servicenamespacetype)
- [ApplicationAutoScalingServiceName](./literals.md#applicationautoscalingservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_application_autoscaling.type_defs import AlarmTypeDef, ...
```

- [AlarmTypeDef](./type_defs.md#alarmtypedef)
- [CustomizedMetricSpecificationTypeDef](./type_defs.md#customizedmetricspecificationtypedef)
- [DeleteScalingPolicyRequestRequestTypeDef](./type_defs.md#deletescalingpolicyrequestrequesttypedef)
- [DeleteScheduledActionRequestRequestTypeDef](./type_defs.md#deletescheduledactionrequestrequesttypedef)
- [DeregisterScalableTargetRequestRequestTypeDef](./type_defs.md#deregisterscalabletargetrequestrequesttypedef)
- [DescribeScalableTargetsRequestRequestTypeDef](./type_defs.md#describescalabletargetsrequestrequesttypedef)
- [DescribeScalableTargetsResponseTypeDef](./type_defs.md#describescalabletargetsresponsetypedef)
- [DescribeScalingActivitiesRequestRequestTypeDef](./type_defs.md#describescalingactivitiesrequestrequesttypedef)
- [DescribeScalingActivitiesResponseTypeDef](./type_defs.md#describescalingactivitiesresponsetypedef)
- [DescribeScalingPoliciesRequestRequestTypeDef](./type_defs.md#describescalingpoliciesrequestrequesttypedef)
- [DescribeScalingPoliciesResponseTypeDef](./type_defs.md#describescalingpoliciesresponsetypedef)
- [DescribeScheduledActionsRequestRequestTypeDef](./type_defs.md#describescheduledactionsrequestrequesttypedef)
- [DescribeScheduledActionsResponseTypeDef](./type_defs.md#describescheduledactionsresponsetypedef)
- [MetricDimensionTypeDef](./type_defs.md#metricdimensiontypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PredefinedMetricSpecificationTypeDef](./type_defs.md#predefinedmetricspecificationtypedef)
- [PutScalingPolicyRequestRequestTypeDef](./type_defs.md#putscalingpolicyrequestrequesttypedef)
- [PutScalingPolicyResponseTypeDef](./type_defs.md#putscalingpolicyresponsetypedef)
- [PutScheduledActionRequestRequestTypeDef](./type_defs.md#putscheduledactionrequestrequesttypedef)
- [RegisterScalableTargetRequestRequestTypeDef](./type_defs.md#registerscalabletargetrequestrequesttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ScalableTargetActionTypeDef](./type_defs.md#scalabletargetactiontypedef)
- [ScalableTargetTypeDef](./type_defs.md#scalabletargettypedef)
- [ScalingActivityTypeDef](./type_defs.md#scalingactivitytypedef)
- [ScalingPolicyTypeDef](./type_defs.md#scalingpolicytypedef)
- [ScheduledActionTypeDef](./type_defs.md#scheduledactiontypedef)
- [StepAdjustmentTypeDef](./type_defs.md#stepadjustmenttypedef)
- [StepScalingPolicyConfigurationTypeDef](./type_defs.md#stepscalingpolicyconfigurationtypedef)
- [SuspendedStateTypeDef](./type_defs.md#suspendedstatetypedef)
- [TargetTrackingScalingPolicyConfigurationTypeDef](./type_defs.md#targettrackingscalingpolicyconfigurationtypedef)
