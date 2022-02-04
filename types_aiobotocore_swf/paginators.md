<a id="paginators-for-aiobotocore-swf-module"></a>

# Paginators for aiobotocore SWF module

> [Index](..) > [SWF](.) > Paginators

Auto-generated documentation for
[SWF](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF)
type annotations stubs module
[types-aiobotocore-swf](https://pypi.org/project/types-aiobotocore-swf/).

- [Paginators for aiobotocore SWF module](#paginators-for-aiobotocore-swf-module)
  - [GetWorkflowExecutionHistoryPaginator](#getworkflowexecutionhistorypaginator)
  - [ListActivityTypesPaginator](#listactivitytypespaginator)
  - [ListClosedWorkflowExecutionsPaginator](#listclosedworkflowexecutionspaginator)
  - [ListDomainsPaginator](#listdomainspaginator)
  - [ListOpenWorkflowExecutionsPaginator](#listopenworkflowexecutionspaginator)
  - [ListWorkflowTypesPaginator](#listworkflowtypespaginator)
  - [PollForDecisionTaskPaginator](#pollfordecisiontaskpaginator)

<a id="getworkflowexecutionhistorypaginator"></a>

## GetWorkflowExecutionHistoryPaginator

Type annotations for
`aiobotocore.create_client("swf").get_paginator("get_workflow_execution_history")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_swf.paginator import GetWorkflowExecutionHistoryPaginator

def get_get_workflow_execution_history_paginator() -> GetWorkflowExecutionHistoryPaginator:
    return Session().create_client("swf").get_paginator("get_workflow_execution_history")
```

Boto3 documentation:
[SWF.Paginator.GetWorkflowExecutionHistory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.GetWorkflowExecutionHistory)

Arguments for `GetWorkflowExecutionHistoryPaginator.paginate` method:

- `domain`: `str` *(required)*
- `execution`:
  [WorkflowExecutionTypeDef](./type_defs.md#workflowexecutiontypedef)
  *(required)*
- `reverseOrder`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetWorkflowExecutionHistoryPaginator.paginate` returns
`_PageIterator`\[[HistoryTypeDef](./type_defs.md#historytypedef)\].

<a id="listactivitytypespaginator"></a>

## ListActivityTypesPaginator

Type annotations for
`aiobotocore.create_client("swf").get_paginator("list_activity_types")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_swf.paginator import ListActivityTypesPaginator

def get_list_activity_types_paginator() -> ListActivityTypesPaginator:
    return Session().create_client("swf").get_paginator("list_activity_types")
```

Boto3 documentation:
[SWF.Paginator.ListActivityTypes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListActivityTypes)

Arguments for `ListActivityTypesPaginator.paginate` method:

- `domain`: `str` *(required)*
- `registrationStatus`:
  [RegistrationStatusType](./literals.md#registrationstatustype) *(required)*
- `name`: `str`
- `reverseOrder`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListActivityTypesPaginator.paginate` returns
`_PageIterator`\[[ActivityTypeInfosTypeDef](./type_defs.md#activitytypeinfostypedef)\].

<a id="listclosedworkflowexecutionspaginator"></a>

## ListClosedWorkflowExecutionsPaginator

Type annotations for
`aiobotocore.create_client("swf").get_paginator("list_closed_workflow_executions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_swf.paginator import ListClosedWorkflowExecutionsPaginator

def get_list_closed_workflow_executions_paginator() -> ListClosedWorkflowExecutionsPaginator:
    return Session().create_client("swf").get_paginator("list_closed_workflow_executions")
```

Boto3 documentation:
[SWF.Paginator.ListClosedWorkflowExecutions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListClosedWorkflowExecutions)

Arguments for `ListClosedWorkflowExecutionsPaginator.paginate` method:

- `domain`: `str` *(required)*
- `startTimeFilter`:
  [ExecutionTimeFilterTypeDef](./type_defs.md#executiontimefiltertypedef)
- `closeTimeFilter`:
  [ExecutionTimeFilterTypeDef](./type_defs.md#executiontimefiltertypedef)
- `executionFilter`:
  [WorkflowExecutionFilterTypeDef](./type_defs.md#workflowexecutionfiltertypedef)
- `closeStatusFilter`:
  [CloseStatusFilterTypeDef](./type_defs.md#closestatusfiltertypedef)
- `typeFilter`:
  [WorkflowTypeFilterTypeDef](./type_defs.md#workflowtypefiltertypedef)
- `tagFilter`: [TagFilterTypeDef](./type_defs.md#tagfiltertypedef)
- `reverseOrder`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListClosedWorkflowExecutionsPaginator.paginate` returns
`_PageIterator`\[[WorkflowExecutionInfosTypeDef](./type_defs.md#workflowexecutioninfostypedef)\].

<a id="listdomainspaginator"></a>

## ListDomainsPaginator

Type annotations for
`aiobotocore.create_client("swf").get_paginator("list_domains")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_swf.paginator import ListDomainsPaginator

def get_list_domains_paginator() -> ListDomainsPaginator:
    return Session().create_client("swf").get_paginator("list_domains")
```

Boto3 documentation:
[SWF.Paginator.ListDomains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListDomains)

Arguments for `ListDomainsPaginator.paginate` method:

- `registrationStatus`:
  [RegistrationStatusType](./literals.md#registrationstatustype) *(required)*
- `reverseOrder`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDomainsPaginator.paginate` returns
`_PageIterator`\[[DomainInfosTypeDef](./type_defs.md#domaininfostypedef)\].

<a id="listopenworkflowexecutionspaginator"></a>

## ListOpenWorkflowExecutionsPaginator

Type annotations for
`aiobotocore.create_client("swf").get_paginator("list_open_workflow_executions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_swf.paginator import ListOpenWorkflowExecutionsPaginator

def get_list_open_workflow_executions_paginator() -> ListOpenWorkflowExecutionsPaginator:
    return Session().create_client("swf").get_paginator("list_open_workflow_executions")
```

Boto3 documentation:
[SWF.Paginator.ListOpenWorkflowExecutions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListOpenWorkflowExecutions)

Arguments for `ListOpenWorkflowExecutionsPaginator.paginate` method:

- `domain`: `str` *(required)*
- `startTimeFilter`:
  [ExecutionTimeFilterTypeDef](./type_defs.md#executiontimefiltertypedef)
  *(required)*
- `typeFilter`:
  [WorkflowTypeFilterTypeDef](./type_defs.md#workflowtypefiltertypedef)
- `tagFilter`: [TagFilterTypeDef](./type_defs.md#tagfiltertypedef)
- `reverseOrder`: `bool`
- `executionFilter`:
  [WorkflowExecutionFilterTypeDef](./type_defs.md#workflowexecutionfiltertypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListOpenWorkflowExecutionsPaginator.paginate` returns
`_PageIterator`\[[WorkflowExecutionInfosTypeDef](./type_defs.md#workflowexecutioninfostypedef)\].

<a id="listworkflowtypespaginator"></a>

## ListWorkflowTypesPaginator

Type annotations for
`aiobotocore.create_client("swf").get_paginator("list_workflow_types")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_swf.paginator import ListWorkflowTypesPaginator

def get_list_workflow_types_paginator() -> ListWorkflowTypesPaginator:
    return Session().create_client("swf").get_paginator("list_workflow_types")
```

Boto3 documentation:
[SWF.Paginator.ListWorkflowTypes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListWorkflowTypes)

Arguments for `ListWorkflowTypesPaginator.paginate` method:

- `domain`: `str` *(required)*
- `registrationStatus`:
  [RegistrationStatusType](./literals.md#registrationstatustype) *(required)*
- `name`: `str`
- `reverseOrder`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListWorkflowTypesPaginator.paginate` returns
`_PageIterator`\[[WorkflowTypeInfosTypeDef](./type_defs.md#workflowtypeinfostypedef)\].

<a id="pollfordecisiontaskpaginator"></a>

## PollForDecisionTaskPaginator

Type annotations for
`aiobotocore.create_client("swf").get_paginator("poll_for_decision_task")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_swf.paginator import PollForDecisionTaskPaginator

def get_poll_for_decision_task_paginator() -> PollForDecisionTaskPaginator:
    return Session().create_client("swf").get_paginator("poll_for_decision_task")
```

Boto3 documentation:
[SWF.Paginator.PollForDecisionTask](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.PollForDecisionTask)

Arguments for `PollForDecisionTaskPaginator.paginate` method:

- `domain`: `str` *(required)*
- `taskList`: [TaskListTypeDef](./type_defs.md#tasklisttypedef) *(required)*
- `identity`: `str`
- `reverseOrder`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`PollForDecisionTaskPaginator.paginate` returns
`_PageIterator`\[[DecisionTaskTypeDef](./type_defs.md#decisiontasktypedef)\].
