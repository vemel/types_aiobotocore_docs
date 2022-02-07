<a id="waiters-for-aiobotocore-lambda-module"></a>

# Waiters for aiobotocore Lambda module

> [Index](..) > [Lambda](.) > Waiters

Auto-generated documentation for
[Lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda)
type annotations stubs module
[types-aiobotocore-lambda](https://pypi.org/project/types-aiobotocore-lambda/).

- [Waiters for aiobotocore Lambda module](#waiters-for-aiobotocore-lambda-module)
  - [FunctionActiveWaiter](#functionactivewaiter)
  - [FunctionExistsWaiter](#functionexistswaiter)
  - [FunctionUpdatedWaiter](#functionupdatedwaiter)

<a id="functionactivewaiter"></a>

## FunctionActiveWaiter

Type annotations for
`session.create_client("lambda").get_waiter("function_active")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_lambda.waiter import FunctionActiveWaiter

def get_function_active_waiter() -> FunctionActiveWaiter:
    return Session().client("lambda").get_waiter("function_active")
```

Boto3 documentation:
[Lambda.Waiter.function_active](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Waiter.FunctionActive)

Arguments for `FunctionActiveWaiter.wait` method:

- `FunctionName`: `str` *(required)*
- `Qualifier`: `str`
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="functionexistswaiter"></a>

## FunctionExistsWaiter

Type annotations for
`session.create_client("lambda").get_waiter("function_exists")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_lambda.waiter import FunctionExistsWaiter

def get_function_exists_waiter() -> FunctionExistsWaiter:
    return Session().client("lambda").get_waiter("function_exists")
```

Boto3 documentation:
[Lambda.Waiter.function_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Waiter.FunctionExists)

Arguments for `FunctionExistsWaiter.wait` method:

- `FunctionName`: `str` *(required)*
- `Qualifier`: `str`
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="functionupdatedwaiter"></a>

## FunctionUpdatedWaiter

Type annotations for
`session.create_client("lambda").get_waiter("function_updated")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_lambda.waiter import FunctionUpdatedWaiter

def get_function_updated_waiter() -> FunctionUpdatedWaiter:
    return Session().client("lambda").get_waiter("function_updated")
```

Boto3 documentation:
[Lambda.Waiter.function_updated](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Waiter.FunctionUpdated)

Arguments for `FunctionUpdatedWaiter.wait` method:

- `FunctionName`: `str` *(required)*
- `Qualifier`: `str`
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
