# Waiters

> [Index](../README.md) > [Glacier](./README.md) > Waiters

!!! note ""

    Auto-generated documentation for [Glacier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
    type annotations stubs module [types-aiobotocore-glacier](https://pypi.org/project/types-aiobotocore-glacier/).

## VaultExistsWaiter

Type annotations and code completion for `#!python session.create_client("glacier").get_waiter("vault_exists")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Waiter.VaultExists)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_glacier.waiter import VaultExistsWaiter

def get_vault_exists_waiter() -> VaultExistsWaiter:
    return Session().client("glacier").get_waiter("vault_exists")
```


### wait

Type annotations and code completion for `#!python VaultExistsWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    accountId: str,
    vaultName: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeVaultInputVaultExistsWaitTypeDef = {  # (1)
    "accountId": ...,
    "vaultName": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribeVaultInputVaultExistsWaitTypeDef](./type_defs.md#describevaultinputvaultexistswaittypedef) 
## VaultNotExistsWaiter

Type annotations and code completion for `#!python session.create_client("glacier").get_waiter("vault_not_exists")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Waiter.VaultNotExists)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_glacier.waiter import VaultNotExistsWaiter

def get_vault_not_exists_waiter() -> VaultNotExistsWaiter:
    return Session().client("glacier").get_waiter("vault_not_exists")
```


### wait

Type annotations and code completion for `#!python VaultNotExistsWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    accountId: str,
    vaultName: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeVaultInputVaultNotExistsWaitTypeDef = {  # (1)
    "accountId": ...,
    "vaultName": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribeVaultInputVaultNotExistsWaitTypeDef](./type_defs.md#describevaultinputvaultnotexistswaittypedef) 
