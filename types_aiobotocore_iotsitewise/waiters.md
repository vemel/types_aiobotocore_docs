<a id="waiters-for-aiobotocore-iotsitewise-module"></a>

# Waiters for aiobotocore IoTSiteWise module

> [Index](..) > [IoTSiteWise](.) > Waiters

Auto-generated documentation for
[IoTSiteWise](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
type annotations stubs module
[types-aiobotocore-iotsitewise](https://pypi.org/project/types-aiobotocore-iotsitewise/).

- [Waiters for aiobotocore IoTSiteWise module](#waiters-for-aiobotocore-iotsitewise-module)
  - [AssetActiveWaiter](#assetactivewaiter)
  - [AssetModelActiveWaiter](#assetmodelactivewaiter)
  - [AssetModelNotExistsWaiter](#assetmodelnotexistswaiter)
  - [AssetNotExistsWaiter](#assetnotexistswaiter)
  - [PortalActiveWaiter](#portalactivewaiter)
  - [PortalNotExistsWaiter](#portalnotexistswaiter)

<a id="assetactivewaiter"></a>

## AssetActiveWaiter

Type annotations for
`session.create_client("iotsitewise").get_waiter("asset_active")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetActiveWaiter

def get_asset_active_waiter() -> AssetActiveWaiter:
    return Session().client("iotsitewise").get_waiter("asset_active")
```

Boto3 documentation:
[IoTSiteWise.Waiter.asset_active](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetActive)

Arguments for `AssetActiveWaiter.wait` method:

- `assetId`: `str` *(required)*
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="assetmodelactivewaiter"></a>

## AssetModelActiveWaiter

Type annotations for
`session.create_client("iotsitewise").get_waiter("asset_model_active")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetModelActiveWaiter

def get_asset_model_active_waiter() -> AssetModelActiveWaiter:
    return Session().client("iotsitewise").get_waiter("asset_model_active")
```

Boto3 documentation:
[IoTSiteWise.Waiter.asset_model_active](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetModelActive)

Arguments for `AssetModelActiveWaiter.wait` method:

- `assetModelId`: `str` *(required)*
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="assetmodelnotexistswaiter"></a>

## AssetModelNotExistsWaiter

Type annotations for
`session.create_client("iotsitewise").get_waiter("asset_model_not_exists")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetModelNotExistsWaiter

def get_asset_model_not_exists_waiter() -> AssetModelNotExistsWaiter:
    return Session().client("iotsitewise").get_waiter("asset_model_not_exists")
```

Boto3 documentation:
[IoTSiteWise.Waiter.asset_model_not_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetModelNotExists)

Arguments for `AssetModelNotExistsWaiter.wait` method:

- `assetModelId`: `str` *(required)*
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="assetnotexistswaiter"></a>

## AssetNotExistsWaiter

Type annotations for
`session.create_client("iotsitewise").get_waiter("asset_not_exists")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import AssetNotExistsWaiter

def get_asset_not_exists_waiter() -> AssetNotExistsWaiter:
    return Session().client("iotsitewise").get_waiter("asset_not_exists")
```

Boto3 documentation:
[IoTSiteWise.Waiter.asset_not_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.AssetNotExists)

Arguments for `AssetNotExistsWaiter.wait` method:

- `assetId`: `str` *(required)*
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="portalactivewaiter"></a>

## PortalActiveWaiter

Type annotations for
`session.create_client("iotsitewise").get_waiter("portal_active")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import PortalActiveWaiter

def get_portal_active_waiter() -> PortalActiveWaiter:
    return Session().client("iotsitewise").get_waiter("portal_active")
```

Boto3 documentation:
[IoTSiteWise.Waiter.portal_active](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.PortalActive)

Arguments for `PortalActiveWaiter.wait` method:

- `portalId`: `str` *(required)*
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)

<a id="portalnotexistswaiter"></a>

## PortalNotExistsWaiter

Type annotations for
`session.create_client("iotsitewise").get_waiter("portal_not_exists")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_iotsitewise.waiter import PortalNotExistsWaiter

def get_portal_not_exists_waiter() -> PortalNotExistsWaiter:
    return Session().client("iotsitewise").get_waiter("portal_not_exists")
```

Boto3 documentation:
[IoTSiteWise.Waiter.portal_not_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Waiter.PortalNotExists)

Arguments for `PortalNotExistsWaiter.wait` method:

- `portalId`: `str` *(required)*
- `WaiterConfig`: [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
