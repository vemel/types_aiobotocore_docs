<a id="waiters-for-aiobotocore-opsworks-module"></a>

# Waiters for aiobotocore OpsWorks module

> [Index](..) > [OpsWorks](.) > Waiters

Auto-generated documentation for
[OpsWorks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
type annotations stubs module
[types-aiobotocore-opsworks](https://pypi.org/project/types-aiobotocore-opsworks/).

- [Waiters for aiobotocore OpsWorks module](#waiters-for-aiobotocore-opsworks-module)
  - [AppExistsWaiter](#appexistswaiter)
  - [DeploymentSuccessfulWaiter](#deploymentsuccessfulwaiter)
  - [InstanceOnlineWaiter](#instanceonlinewaiter)
  - [InstanceRegisteredWaiter](#instanceregisteredwaiter)
  - [InstanceStoppedWaiter](#instancestoppedwaiter)
  - [InstanceTerminatedWaiter](#instanceterminatedwaiter)

<a id="appexistswaiter"></a>

## AppExistsWaiter

Type annotations for
`aiobotocore.create_client("opsworks").get_waiter("app_exists")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_opsworks.waiter import AppExistsWaiter

def get_app_exists_waiter() -> AppExistsWaiter:
    return Session().create_client("opsworks").get_waiter("app_exists")
```

Boto3 documentation:
[OpsWorks.Waiter.app_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Waiter.AppExists)

Arguments for `AppExistsWaiter.wait` method:

- `StackId`: `str`
- `AppIds`: `Sequence`\[`str`\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="deploymentsuccessfulwaiter"></a>

## DeploymentSuccessfulWaiter

Type annotations for
`aiobotocore.create_client("opsworks").get_waiter("deployment_successful")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_opsworks.waiter import DeploymentSuccessfulWaiter

def get_deployment_successful_waiter() -> DeploymentSuccessfulWaiter:
    return Session().create_client("opsworks").get_waiter("deployment_successful")
```

Boto3 documentation:
[OpsWorks.Waiter.deployment_successful](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Waiter.DeploymentSuccessful)

Arguments for `DeploymentSuccessfulWaiter.wait` method:

- `StackId`: `str`
- `AppId`: `str`
- `DeploymentIds`: `Sequence`\[`str`\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="instanceonlinewaiter"></a>

## InstanceOnlineWaiter

Type annotations for
`aiobotocore.create_client("opsworks").get_waiter("instance_online")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_opsworks.waiter import InstanceOnlineWaiter

def get_instance_online_waiter() -> InstanceOnlineWaiter:
    return Session().create_client("opsworks").get_waiter("instance_online")
```

Boto3 documentation:
[OpsWorks.Waiter.instance_online](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Waiter.InstanceOnline)

Arguments for `InstanceOnlineWaiter.wait` method:

- `StackId`: `str`
- `LayerId`: `str`
- `InstanceIds`: `Sequence`\[`str`\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="instanceregisteredwaiter"></a>

## InstanceRegisteredWaiter

Type annotations for
`aiobotocore.create_client("opsworks").get_waiter("instance_registered")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_opsworks.waiter import InstanceRegisteredWaiter

def get_instance_registered_waiter() -> InstanceRegisteredWaiter:
    return Session().create_client("opsworks").get_waiter("instance_registered")
```

Boto3 documentation:
[OpsWorks.Waiter.instance_registered](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Waiter.InstanceRegistered)

Arguments for `InstanceRegisteredWaiter.wait` method:

- `StackId`: `str`
- `LayerId`: `str`
- `InstanceIds`: `Sequence`\[`str`\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="instancestoppedwaiter"></a>

## InstanceStoppedWaiter

Type annotations for
`aiobotocore.create_client("opsworks").get_waiter("instance_stopped")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_opsworks.waiter import InstanceStoppedWaiter

def get_instance_stopped_waiter() -> InstanceStoppedWaiter:
    return Session().create_client("opsworks").get_waiter("instance_stopped")
```

Boto3 documentation:
[OpsWorks.Waiter.instance_stopped](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Waiter.InstanceStopped)

Arguments for `InstanceStoppedWaiter.wait` method:

- `StackId`: `str`
- `LayerId`: `str`
- `InstanceIds`: `Sequence`\[`str`\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="instanceterminatedwaiter"></a>

## InstanceTerminatedWaiter

Type annotations for
`aiobotocore.create_client("opsworks").get_waiter("instance_terminated")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_opsworks.waiter import InstanceTerminatedWaiter

def get_instance_terminated_waiter() -> InstanceTerminatedWaiter:
    return Session().create_client("opsworks").get_waiter("instance_terminated")
```

Boto3 documentation:
[OpsWorks.Waiter.instance_terminated](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Waiter.InstanceTerminated)

Arguments for `InstanceTerminatedWaiter.wait` method:

- `StackId`: `str`
- `LayerId`: `str`
- `InstanceIds`: `Sequence`\[`str`\]
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
