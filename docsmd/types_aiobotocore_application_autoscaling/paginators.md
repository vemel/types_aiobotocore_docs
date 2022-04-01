# Paginators

> [Index](../README.md) > [ApplicationAutoScaling](./README.md) > Paginators

!!! note ""

    Auto-generated documentation for [ApplicationAutoScaling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
    type annotations stubs module [types-aiobotocore-application-autoscaling](https://pypi.org/project/types-aiobotocore-application-autoscaling/).

## DescribeScalableTargetsPaginator

Type annotations and code completion for `#!python session.create_client("application-autoscaling").get_paginator("describe_scalable_targets")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalableTargets)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_application_autoscaling.paginator import DescribeScalableTargetsPaginator

session = get_session()
async with session.create_client("application-autoscaling") as client:
    client: ApplicationAutoScalingClient
    paginator: DescribeScalableTargetsPaginator = client.get_paginator("describe_scalable_targets")
```


### paginate

Type annotations and code completion for `#!python DescribeScalableTargetsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ServiceNamespace: ServiceNamespaceType,  # (1)
    ResourceIds: Sequence[str] = ...,
    ScalableDimension: ScalableDimensionType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[DescribeScalableTargetsResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: ServiceNamespaceType](./literals.md#servicenamespacetype) 
2. See [:material-code-brackets: ScalableDimensionType](./literals.md#scalabledimensiontype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: DescribeScalableTargetsResponseTypeDef](./type_defs.md#describescalabletargetsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = {  # (1)
    "ServiceNamespace": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef](./type_defs.md#describescalabletargetsrequestdescribescalabletargetspaginatetypedef) 
## DescribeScalingActivitiesPaginator

Type annotations and code completion for `#!python session.create_client("application-autoscaling").get_paginator("describe_scaling_activities")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalingActivities)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_application_autoscaling.paginator import DescribeScalingActivitiesPaginator

session = get_session()
async with session.create_client("application-autoscaling") as client:
    client: ApplicationAutoScalingClient
    paginator: DescribeScalingActivitiesPaginator = client.get_paginator("describe_scaling_activities")
```


### paginate

Type annotations and code completion for `#!python DescribeScalingActivitiesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ServiceNamespace: ServiceNamespaceType,  # (1)
    ResourceId: str = ...,
    ScalableDimension: ScalableDimensionType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[DescribeScalingActivitiesResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: ServiceNamespaceType](./literals.md#servicenamespacetype) 
2. See [:material-code-brackets: ScalableDimensionType](./literals.md#scalabledimensiontype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: DescribeScalingActivitiesResponseTypeDef](./type_defs.md#describescalingactivitiesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = {  # (1)
    "ServiceNamespace": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef](./type_defs.md#describescalingactivitiesrequestdescribescalingactivitiespaginatetypedef) 
## DescribeScalingPoliciesPaginator

Type annotations and code completion for `#!python session.create_client("application-autoscaling").get_paginator("describe_scaling_policies")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalingPolicies)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_application_autoscaling.paginator import DescribeScalingPoliciesPaginator

session = get_session()
async with session.create_client("application-autoscaling") as client:
    client: ApplicationAutoScalingClient
    paginator: DescribeScalingPoliciesPaginator = client.get_paginator("describe_scaling_policies")
```


### paginate

Type annotations and code completion for `#!python DescribeScalingPoliciesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ServiceNamespace: ServiceNamespaceType,  # (1)
    PolicyNames: Sequence[str] = ...,
    ResourceId: str = ...,
    ScalableDimension: ScalableDimensionType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[DescribeScalingPoliciesResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: ServiceNamespaceType](./literals.md#servicenamespacetype) 
2. See [:material-code-brackets: ScalableDimensionType](./literals.md#scalabledimensiontype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: DescribeScalingPoliciesResponseTypeDef](./type_defs.md#describescalingpoliciesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = {  # (1)
    "ServiceNamespace": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef](./type_defs.md#describescalingpoliciesrequestdescribescalingpoliciespaginatetypedef) 
## DescribeScheduledActionsPaginator

Type annotations and code completion for `#!python session.create_client("application-autoscaling").get_paginator("describe_scheduled_actions")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScheduledActions)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_application_autoscaling.paginator import DescribeScheduledActionsPaginator

session = get_session()
async with session.create_client("application-autoscaling") as client:
    client: ApplicationAutoScalingClient
    paginator: DescribeScheduledActionsPaginator = client.get_paginator("describe_scheduled_actions")
```


### paginate

Type annotations and code completion for `#!python DescribeScheduledActionsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ServiceNamespace: ServiceNamespaceType,  # (1)
    ScheduledActionNames: Sequence[str] = ...,
    ResourceId: str = ...,
    ScalableDimension: ScalableDimensionType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[DescribeScheduledActionsResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: ServiceNamespaceType](./literals.md#servicenamespacetype) 
2. See [:material-code-brackets: ScalableDimensionType](./literals.md#scalabledimensiontype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: DescribeScheduledActionsResponseTypeDef](./type_defs.md#describescheduledactionsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = {  # (1)
    "ServiceNamespace": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef](./type_defs.md#describescheduledactionsrequestdescribescheduledactionspaginatetypedef) 
