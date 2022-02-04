<a id="waiters-for-aiobotocore-ecs-module"></a>

# Waiters for aiobotocore ECS module

> [Index](..) > [ECS](.) > Waiters

Auto-generated documentation for
[ECS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
type annotations stubs module
[types-aiobotocore-ecs](https://pypi.org/project/types-aiobotocore-ecs/).

- [Waiters for aiobotocore ECS module](#waiters-for-aiobotocore-ecs-module)
  - [ServicesInactiveWaiter](#servicesinactivewaiter)
  - [ServicesStableWaiter](#servicesstablewaiter)
  - [TasksRunningWaiter](#tasksrunningwaiter)
  - [TasksStoppedWaiter](#tasksstoppedwaiter)

<a id="servicesinactivewaiter"></a>

## ServicesInactiveWaiter

Type annotations for
`aiobotocore.create_client("ecs").get_waiter("services_inactive")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ecs.waiter import ServicesInactiveWaiter

def get_services_inactive_waiter() -> ServicesInactiveWaiter:
    return Session().create_client("ecs").get_waiter("services_inactive")
```

Boto3 documentation:
[ECS.Waiter.services_inactive](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Waiter.ServicesInactive)

Arguments for `ServicesInactiveWaiter.wait` method:

- `services`: `Sequence`\[`str`\] *(required)*
- `cluster`: `str`
- `include`: `Sequence`\[`Literal['TAGS']` (see
  [ServiceFieldType](./literals.md#servicefieldtype))\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="servicesstablewaiter"></a>

## ServicesStableWaiter

Type annotations for
`aiobotocore.create_client("ecs").get_waiter("services_stable")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ecs.waiter import ServicesStableWaiter

def get_services_stable_waiter() -> ServicesStableWaiter:
    return Session().create_client("ecs").get_waiter("services_stable")
```

Boto3 documentation:
[ECS.Waiter.services_stable](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Waiter.ServicesStable)

Arguments for `ServicesStableWaiter.wait` method:

- `services`: `Sequence`\[`str`\] *(required)*
- `cluster`: `str`
- `include`: `Sequence`\[`Literal['TAGS']` (see
  [ServiceFieldType](./literals.md#servicefieldtype))\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="tasksrunningwaiter"></a>

## TasksRunningWaiter

Type annotations for
`aiobotocore.create_client("ecs").get_waiter("tasks_running")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ecs.waiter import TasksRunningWaiter

def get_tasks_running_waiter() -> TasksRunningWaiter:
    return Session().create_client("ecs").get_waiter("tasks_running")
```

Boto3 documentation:
[ECS.Waiter.tasks_running](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Waiter.TasksRunning)

Arguments for `TasksRunningWaiter.wait` method:

- `tasks`: `Sequence`\[`str`\] *(required)*
- `cluster`: `str`
- `include`: `Sequence`\[`Literal['TAGS']` (see
  [TaskFieldType](./literals.md#taskfieldtype))\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="tasksstoppedwaiter"></a>

## TasksStoppedWaiter

Type annotations for
`aiobotocore.create_client("ecs").get_waiter("tasks_stopped")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ecs.waiter import TasksStoppedWaiter

def get_tasks_stopped_waiter() -> TasksStoppedWaiter:
    return Session().create_client("ecs").get_waiter("tasks_stopped")
```

Boto3 documentation:
[ECS.Waiter.tasks_stopped](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Waiter.TasksStopped)

Arguments for `TasksStoppedWaiter.wait` method:

- `tasks`: `Sequence`\[`str`\] *(required)*
- `cluster`: `str`
- `include`: `Sequence`\[`Literal['TAGS']` (see
  [TaskFieldType](./literals.md#taskfieldtype))\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
