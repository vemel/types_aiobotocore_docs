# Waiters

> [Index](../README.md) > [IoTSiteWise](./README.md) > Waiters

!!! note ""

    Auto-generated documentation for [IoTSiteWise](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
    type annotations stubs module [types-aiobotocore-iotsitewise](https://pypi.org/project/types-aiobotocore-iotsitewise/).

## AssetActiveWaiter

Type annotations and code completion for `#!python session.create_client("iotsitewise").get_waiter("asset_active")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetActive)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetActiveWaiter

def get_asset_active_waiter() -> AssetActiveWaiter:
    return Session().client("iotsitewise").get_waiter("asset_active")
```


### wait

Type annotations and code completion for `#!python AssetActiveWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    assetId: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeAssetRequestAssetActiveWaitTypeDef = {  # (1)
    "assetId": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribeAssetRequestAssetActiveWaitTypeDef](./type_defs.md#describeassetrequestassetactivewaittypedef) 
## AssetModelActiveWaiter

Type annotations and code completion for `#!python session.create_client("iotsitewise").get_waiter("asset_model_active")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetModelActive)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetModelActiveWaiter

def get_asset_model_active_waiter() -> AssetModelActiveWaiter:
    return Session().client("iotsitewise").get_waiter("asset_model_active")
```


### wait

Type annotations and code completion for `#!python AssetModelActiveWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    assetModelId: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeAssetModelRequestAssetModelActiveWaitTypeDef = {  # (1)
    "assetModelId": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribeAssetModelRequestAssetModelActiveWaitTypeDef](./type_defs.md#describeassetmodelrequestassetmodelactivewaittypedef) 
## AssetModelNotExistsWaiter

Type annotations and code completion for `#!python session.create_client("iotsitewise").get_waiter("asset_model_not_exists")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetModelNotExists)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetModelNotExistsWaiter

def get_asset_model_not_exists_waiter() -> AssetModelNotExistsWaiter:
    return Session().client("iotsitewise").get_waiter("asset_model_not_exists")
```


### wait

Type annotations and code completion for `#!python AssetModelNotExistsWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    assetModelId: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeAssetModelRequestAssetModelNotExistsWaitTypeDef = {  # (1)
    "assetModelId": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribeAssetModelRequestAssetModelNotExistsWaitTypeDef](./type_defs.md#describeassetmodelrequestassetmodelnotexistswaittypedef) 
## AssetNotExistsWaiter

Type annotations and code completion for `#!python session.create_client("iotsitewise").get_waiter("asset_not_exists")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetNotExists)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetNotExistsWaiter

def get_asset_not_exists_waiter() -> AssetNotExistsWaiter:
    return Session().client("iotsitewise").get_waiter("asset_not_exists")
```


### wait

Type annotations and code completion for `#!python AssetNotExistsWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    assetId: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeAssetRequestAssetNotExistsWaitTypeDef = {  # (1)
    "assetId": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribeAssetRequestAssetNotExistsWaitTypeDef](./type_defs.md#describeassetrequestassetnotexistswaittypedef) 
## PortalActiveWaiter

Type annotations and code completion for `#!python session.create_client("iotsitewise").get_waiter("portal_active")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.PortalActive)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import PortalActiveWaiter

def get_portal_active_waiter() -> PortalActiveWaiter:
    return Session().client("iotsitewise").get_waiter("portal_active")
```


### wait

Type annotations and code completion for `#!python PortalActiveWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    portalId: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribePortalRequestPortalActiveWaitTypeDef = {  # (1)
    "portalId": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribePortalRequestPortalActiveWaitTypeDef](./type_defs.md#describeportalrequestportalactivewaittypedef) 
## PortalNotExistsWaiter

Type annotations and code completion for `#!python session.create_client("iotsitewise").get_waiter("portal_not_exists")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.PortalNotExists)

```python title="Usage example"
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import PortalNotExistsWaiter

def get_portal_not_exists_waiter() -> PortalNotExistsWaiter:
    return Session().client("iotsitewise").get_waiter("portal_not_exists")
```


### wait

Type annotations and code completion for `#!python PortalNotExistsWaiter.wait` method.

```python title="Method definition"
await def wait(
    self,
    *,
    portalId: str,
    WaiterConfig: WaiterConfigTypeDef = ...,  # (1)
) -> None:
    ...
```

1. See [:material-code-braces: WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef) 


```python title="Usage example with kwargs"
kwargs: DescribePortalRequestPortalNotExistsWaitTypeDef = {  # (1)
    "portalId": ...,
}

parent.wait(**kwargs)
```

1. See [:material-code-braces: DescribePortalRequestPortalNotExistsWaitTypeDef](./type_defs.md#describeportalrequestportalnotexistswaittypedef) 
