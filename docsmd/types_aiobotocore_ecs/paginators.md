# Paginators

> [Index](../README.md) > [ECS](./README.md) > Paginators

!!! note ""

    Auto-generated documentation for [ECS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
    type annotations stubs module [types-aiobotocore-ecs](https://pypi.org/project/types-aiobotocore-ecs/).

## ListAccountSettingsPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_account_settings")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListAccountSettings)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListAccountSettingsPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListAccountSettingsPaginator = client.get_paginator("list_account_settings")
```


### paginate

Type annotations and code completion for `#!python ListAccountSettingsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    name: SettingNameType = ...,  # (1)
    value: str = ...,
    principalArn: str = ...,
    effectiveSettings: bool = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[ListAccountSettingsResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-brackets: SettingNameType](./literals.md#settingnametype) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: ListAccountSettingsResponseTypeDef](./type_defs.md#listaccountsettingsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListAccountSettingsRequestListAccountSettingsPaginateTypeDef = {  # (1)
    "name": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListAccountSettingsRequestListAccountSettingsPaginateTypeDef](./type_defs.md#listaccountsettingsrequestlistaccountsettingspaginatetypedef) 
## ListAttributesPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_attributes")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListAttributes)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListAttributesPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListAttributesPaginator = client.get_paginator("list_attributes")
```


### paginate

Type annotations and code completion for `#!python ListAttributesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    targetType: TargetTypeType,  # (1)
    cluster: str = ...,
    attributeName: str = ...,
    attributeValue: str = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[ListAttributesResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-brackets: TargetTypeType](./literals.md#targettypetype) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: ListAttributesResponseTypeDef](./type_defs.md#listattributesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListAttributesRequestListAttributesPaginateTypeDef = {  # (1)
    "targetType": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListAttributesRequestListAttributesPaginateTypeDef](./type_defs.md#listattributesrequestlistattributespaginatetypedef) 
## ListClustersPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_clusters")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListClusters)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListClustersPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListClustersPaginator = client.get_paginator("list_clusters")
```


### paginate

Type annotations and code completion for `#!python ListClustersPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[ListClustersResponseTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: ListClustersResponseTypeDef](./type_defs.md#listclustersresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListClustersRequestListClustersPaginateTypeDef = {  # (1)
    "PaginationConfig": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListClustersRequestListClustersPaginateTypeDef](./type_defs.md#listclustersrequestlistclusterspaginatetypedef) 
## ListContainerInstancesPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_container_instances")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListContainerInstances)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListContainerInstancesPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListContainerInstancesPaginator = client.get_paginator("list_container_instances")
```


### paginate

Type annotations and code completion for `#!python ListContainerInstancesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    cluster: str = ...,
    filter: str = ...,
    status: ContainerInstanceStatusType = ...,  # (1)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[ListContainerInstancesResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-brackets: ContainerInstanceStatusType](./literals.md#containerinstancestatustype) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: ListContainerInstancesResponseTypeDef](./type_defs.md#listcontainerinstancesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListContainerInstancesRequestListContainerInstancesPaginateTypeDef = {  # (1)
    "cluster": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListContainerInstancesRequestListContainerInstancesPaginateTypeDef](./type_defs.md#listcontainerinstancesrequestlistcontainerinstancespaginatetypedef) 
## ListServicesPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_services")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListServices)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListServicesPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListServicesPaginator = client.get_paginator("list_services")
```


### paginate

Type annotations and code completion for `#!python ListServicesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    cluster: str = ...,
    launchType: LaunchTypeType = ...,  # (1)
    schedulingStrategy: SchedulingStrategyType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[ListServicesResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: LaunchTypeType](./literals.md#launchtypetype) 
2. See [:material-code-brackets: SchedulingStrategyType](./literals.md#schedulingstrategytype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: ListServicesResponseTypeDef](./type_defs.md#listservicesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListServicesRequestListServicesPaginateTypeDef = {  # (1)
    "cluster": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListServicesRequestListServicesPaginateTypeDef](./type_defs.md#listservicesrequestlistservicespaginatetypedef) 
## ListTaskDefinitionFamiliesPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_task_definition_families")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTaskDefinitionFamilies)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListTaskDefinitionFamiliesPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListTaskDefinitionFamiliesPaginator = client.get_paginator("list_task_definition_families")
```


### paginate

Type annotations and code completion for `#!python ListTaskDefinitionFamiliesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    familyPrefix: str = ...,
    status: TaskDefinitionFamilyStatusType = ...,  # (1)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[ListTaskDefinitionFamiliesResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-brackets: TaskDefinitionFamilyStatusType](./literals.md#taskdefinitionfamilystatustype) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: ListTaskDefinitionFamiliesResponseTypeDef](./type_defs.md#listtaskdefinitionfamiliesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef = {  # (1)
    "familyPrefix": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef](./type_defs.md#listtaskdefinitionfamiliesrequestlisttaskdefinitionfamiliespaginatetypedef) 
## ListTaskDefinitionsPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_task_definitions")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTaskDefinitions)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListTaskDefinitionsPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListTaskDefinitionsPaginator = client.get_paginator("list_task_definitions")
```


### paginate

Type annotations and code completion for `#!python ListTaskDefinitionsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    familyPrefix: str = ...,
    status: TaskDefinitionStatusType = ...,  # (1)
    sort: SortOrderType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[ListTaskDefinitionsResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: TaskDefinitionStatusType](./literals.md#taskdefinitionstatustype) 
2. See [:material-code-brackets: SortOrderType](./literals.md#sortordertype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: ListTaskDefinitionsResponseTypeDef](./type_defs.md#listtaskdefinitionsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef = {  # (1)
    "familyPrefix": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef](./type_defs.md#listtaskdefinitionsrequestlisttaskdefinitionspaginatetypedef) 
## ListTasksPaginator

Type annotations and code completion for `#!python session.create_client("ecs").get_paginator("list_tasks")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTasks)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_ecs.paginator import ListTasksPaginator

session = get_session()
async with session.create_client("ecs") as client:
    client: ECSClient
    paginator: ListTasksPaginator = client.get_paginator("list_tasks")
```


### paginate

Type annotations and code completion for `#!python ListTasksPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    cluster: str = ...,
    containerInstance: str = ...,
    family: str = ...,
    startedBy: str = ...,
    serviceName: str = ...,
    desiredStatus: DesiredStatusType = ...,  # (1)
    launchType: LaunchTypeType = ...,  # (2)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (3)
) -> AsyncIterator[ListTasksResponseTypeDef]:  # (4)
    ...
```

1. See [:material-code-brackets: DesiredStatusType](./literals.md#desiredstatustype) 
2. See [:material-code-brackets: LaunchTypeType](./literals.md#launchtypetype) 
3. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
4. See [:material-code-braces: ListTasksResponseTypeDef](./type_defs.md#listtasksresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListTasksRequestListTasksPaginateTypeDef = {  # (1)
    "cluster": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListTasksRequestListTasksPaginateTypeDef](./type_defs.md#listtasksrequestlisttaskspaginatetypedef) 
