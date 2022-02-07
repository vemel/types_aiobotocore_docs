<a id="paginators-for-aiobotocore-greengrass-module"></a>

# Paginators for aiobotocore Greengrass module

> [Index](..) > [Greengrass](.) > Paginators

Auto-generated documentation for
[Greengrass](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass)
type annotations stubs module
[types-aiobotocore-greengrass](https://pypi.org/project/types-aiobotocore-greengrass/).

- [Paginators for aiobotocore Greengrass module](#paginators-for-aiobotocore-greengrass-module)
  - [ListBulkDeploymentDetailedReportsPaginator](#listbulkdeploymentdetailedreportspaginator)
  - [ListBulkDeploymentsPaginator](#listbulkdeploymentspaginator)
  - [ListConnectorDefinitionVersionsPaginator](#listconnectordefinitionversionspaginator)
  - [ListConnectorDefinitionsPaginator](#listconnectordefinitionspaginator)
  - [ListCoreDefinitionVersionsPaginator](#listcoredefinitionversionspaginator)
  - [ListCoreDefinitionsPaginator](#listcoredefinitionspaginator)
  - [ListDeploymentsPaginator](#listdeploymentspaginator)
  - [ListDeviceDefinitionVersionsPaginator](#listdevicedefinitionversionspaginator)
  - [ListDeviceDefinitionsPaginator](#listdevicedefinitionspaginator)
  - [ListFunctionDefinitionVersionsPaginator](#listfunctiondefinitionversionspaginator)
  - [ListFunctionDefinitionsPaginator](#listfunctiondefinitionspaginator)
  - [ListGroupVersionsPaginator](#listgroupversionspaginator)
  - [ListGroupsPaginator](#listgroupspaginator)
  - [ListLoggerDefinitionVersionsPaginator](#listloggerdefinitionversionspaginator)
  - [ListLoggerDefinitionsPaginator](#listloggerdefinitionspaginator)
  - [ListResourceDefinitionVersionsPaginator](#listresourcedefinitionversionspaginator)
  - [ListResourceDefinitionsPaginator](#listresourcedefinitionspaginator)
  - [ListSubscriptionDefinitionVersionsPaginator](#listsubscriptiondefinitionversionspaginator)
  - [ListSubscriptionDefinitionsPaginator](#listsubscriptiondefinitionspaginator)

<a id="listbulkdeploymentdetailedreportspaginator"></a>

## ListBulkDeploymentDetailedReportsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_bulk_deployment_detailed_reports")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListBulkDeploymentDetailedReportsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListBulkDeploymentDetailedReportsPaginator = client.get_paginator("list_bulk_deployment_detailed_reports")
```

Boto3 documentation:
[Greengrass.Paginator.ListBulkDeploymentDetailedReports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListBulkDeploymentDetailedReports)

Arguments for `ListBulkDeploymentDetailedReportsPaginator.paginate` method:

- `BulkDeploymentId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListBulkDeploymentDetailedReportsPaginator.paginate` returns
`_PageIterator`\[[ListBulkDeploymentDetailedReportsResponseTypeDef](./type_defs.md#listbulkdeploymentdetailedreportsresponsetypedef)\].

<a id="listbulkdeploymentspaginator"></a>

## ListBulkDeploymentsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_bulk_deployments")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListBulkDeploymentsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListBulkDeploymentsPaginator = client.get_paginator("list_bulk_deployments")
```

Boto3 documentation:
[Greengrass.Paginator.ListBulkDeployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListBulkDeployments)

Arguments for `ListBulkDeploymentsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListBulkDeploymentsPaginator.paginate` returns
`_PageIterator`\[[ListBulkDeploymentsResponseTypeDef](./type_defs.md#listbulkdeploymentsresponsetypedef)\].

<a id="listconnectordefinitionversionspaginator"></a>

## ListConnectorDefinitionVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_connector_definition_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListConnectorDefinitionVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListConnectorDefinitionVersionsPaginator = client.get_paginator("list_connector_definition_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListConnectorDefinitionVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListConnectorDefinitionVersions)

Arguments for `ListConnectorDefinitionVersionsPaginator.paginate` method:

- `ConnectorDefinitionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListConnectorDefinitionVersionsPaginator.paginate` returns
`_PageIterator`\[[ListConnectorDefinitionVersionsResponseTypeDef](./type_defs.md#listconnectordefinitionversionsresponsetypedef)\].

<a id="listconnectordefinitionspaginator"></a>

## ListConnectorDefinitionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_connector_definitions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListConnectorDefinitionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListConnectorDefinitionsPaginator = client.get_paginator("list_connector_definitions")
```

Boto3 documentation:
[Greengrass.Paginator.ListConnectorDefinitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListConnectorDefinitions)

Arguments for `ListConnectorDefinitionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListConnectorDefinitionsPaginator.paginate` returns
`_PageIterator`\[[ListConnectorDefinitionsResponseTypeDef](./type_defs.md#listconnectordefinitionsresponsetypedef)\].

<a id="listcoredefinitionversionspaginator"></a>

## ListCoreDefinitionVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_core_definition_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListCoreDefinitionVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListCoreDefinitionVersionsPaginator = client.get_paginator("list_core_definition_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListCoreDefinitionVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListCoreDefinitionVersions)

Arguments for `ListCoreDefinitionVersionsPaginator.paginate` method:

- `CoreDefinitionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListCoreDefinitionVersionsPaginator.paginate` returns
`_PageIterator`\[[ListCoreDefinitionVersionsResponseTypeDef](./type_defs.md#listcoredefinitionversionsresponsetypedef)\].

<a id="listcoredefinitionspaginator"></a>

## ListCoreDefinitionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_core_definitions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListCoreDefinitionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListCoreDefinitionsPaginator = client.get_paginator("list_core_definitions")
```

Boto3 documentation:
[Greengrass.Paginator.ListCoreDefinitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListCoreDefinitions)

Arguments for `ListCoreDefinitionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListCoreDefinitionsPaginator.paginate` returns
`_PageIterator`\[[ListCoreDefinitionsResponseTypeDef](./type_defs.md#listcoredefinitionsresponsetypedef)\].

<a id="listdeploymentspaginator"></a>

## ListDeploymentsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_deployments")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListDeploymentsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListDeploymentsPaginator = client.get_paginator("list_deployments")
```

Boto3 documentation:
[Greengrass.Paginator.ListDeployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListDeployments)

Arguments for `ListDeploymentsPaginator.paginate` method:

- `GroupId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDeploymentsPaginator.paginate` returns
`_PageIterator`\[[ListDeploymentsResponseTypeDef](./type_defs.md#listdeploymentsresponsetypedef)\].

<a id="listdevicedefinitionversionspaginator"></a>

## ListDeviceDefinitionVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_device_definition_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListDeviceDefinitionVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListDeviceDefinitionVersionsPaginator = client.get_paginator("list_device_definition_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListDeviceDefinitionVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListDeviceDefinitionVersions)

Arguments for `ListDeviceDefinitionVersionsPaginator.paginate` method:

- `DeviceDefinitionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDeviceDefinitionVersionsPaginator.paginate` returns
`_PageIterator`\[[ListDeviceDefinitionVersionsResponseTypeDef](./type_defs.md#listdevicedefinitionversionsresponsetypedef)\].

<a id="listdevicedefinitionspaginator"></a>

## ListDeviceDefinitionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_device_definitions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListDeviceDefinitionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListDeviceDefinitionsPaginator = client.get_paginator("list_device_definitions")
```

Boto3 documentation:
[Greengrass.Paginator.ListDeviceDefinitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListDeviceDefinitions)

Arguments for `ListDeviceDefinitionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDeviceDefinitionsPaginator.paginate` returns
`_PageIterator`\[[ListDeviceDefinitionsResponseTypeDef](./type_defs.md#listdevicedefinitionsresponsetypedef)\].

<a id="listfunctiondefinitionversionspaginator"></a>

## ListFunctionDefinitionVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_function_definition_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListFunctionDefinitionVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListFunctionDefinitionVersionsPaginator = client.get_paginator("list_function_definition_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListFunctionDefinitionVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListFunctionDefinitionVersions)

Arguments for `ListFunctionDefinitionVersionsPaginator.paginate` method:

- `FunctionDefinitionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListFunctionDefinitionVersionsPaginator.paginate` returns
`_PageIterator`\[[ListFunctionDefinitionVersionsResponseTypeDef](./type_defs.md#listfunctiondefinitionversionsresponsetypedef)\].

<a id="listfunctiondefinitionspaginator"></a>

## ListFunctionDefinitionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_function_definitions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListFunctionDefinitionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListFunctionDefinitionsPaginator = client.get_paginator("list_function_definitions")
```

Boto3 documentation:
[Greengrass.Paginator.ListFunctionDefinitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListFunctionDefinitions)

Arguments for `ListFunctionDefinitionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListFunctionDefinitionsPaginator.paginate` returns
`_PageIterator`\[[ListFunctionDefinitionsResponseTypeDef](./type_defs.md#listfunctiondefinitionsresponsetypedef)\].

<a id="listgroupversionspaginator"></a>

## ListGroupVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_group_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListGroupVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListGroupVersionsPaginator = client.get_paginator("list_group_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListGroupVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListGroupVersions)

Arguments for `ListGroupVersionsPaginator.paginate` method:

- `GroupId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGroupVersionsPaginator.paginate` returns
`_PageIterator`\[[ListGroupVersionsResponseTypeDef](./type_defs.md#listgroupversionsresponsetypedef)\].

<a id="listgroupspaginator"></a>

## ListGroupsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListGroupsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListGroupsPaginator = client.get_paginator("list_groups")
```

Boto3 documentation:
[Greengrass.Paginator.ListGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListGroups)

Arguments for `ListGroupsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGroupsPaginator.paginate` returns
`_PageIterator`\[[ListGroupsResponseTypeDef](./type_defs.md#listgroupsresponsetypedef)\].

<a id="listloggerdefinitionversionspaginator"></a>

## ListLoggerDefinitionVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_logger_definition_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListLoggerDefinitionVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListLoggerDefinitionVersionsPaginator = client.get_paginator("list_logger_definition_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListLoggerDefinitionVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListLoggerDefinitionVersions)

Arguments for `ListLoggerDefinitionVersionsPaginator.paginate` method:

- `LoggerDefinitionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListLoggerDefinitionVersionsPaginator.paginate` returns
`_PageIterator`\[[ListLoggerDefinitionVersionsResponseTypeDef](./type_defs.md#listloggerdefinitionversionsresponsetypedef)\].

<a id="listloggerdefinitionspaginator"></a>

## ListLoggerDefinitionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_logger_definitions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListLoggerDefinitionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListLoggerDefinitionsPaginator = client.get_paginator("list_logger_definitions")
```

Boto3 documentation:
[Greengrass.Paginator.ListLoggerDefinitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListLoggerDefinitions)

Arguments for `ListLoggerDefinitionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListLoggerDefinitionsPaginator.paginate` returns
`_PageIterator`\[[ListLoggerDefinitionsResponseTypeDef](./type_defs.md#listloggerdefinitionsresponsetypedef)\].

<a id="listresourcedefinitionversionspaginator"></a>

## ListResourceDefinitionVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_resource_definition_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListResourceDefinitionVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListResourceDefinitionVersionsPaginator = client.get_paginator("list_resource_definition_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListResourceDefinitionVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListResourceDefinitionVersions)

Arguments for `ListResourceDefinitionVersionsPaginator.paginate` method:

- `ResourceDefinitionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListResourceDefinitionVersionsPaginator.paginate` returns
`_PageIterator`\[[ListResourceDefinitionVersionsResponseTypeDef](./type_defs.md#listresourcedefinitionversionsresponsetypedef)\].

<a id="listresourcedefinitionspaginator"></a>

## ListResourceDefinitionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_resource_definitions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListResourceDefinitionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListResourceDefinitionsPaginator = client.get_paginator("list_resource_definitions")
```

Boto3 documentation:
[Greengrass.Paginator.ListResourceDefinitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListResourceDefinitions)

Arguments for `ListResourceDefinitionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListResourceDefinitionsPaginator.paginate` returns
`_PageIterator`\[[ListResourceDefinitionsResponseTypeDef](./type_defs.md#listresourcedefinitionsresponsetypedef)\].

<a id="listsubscriptiondefinitionversionspaginator"></a>

## ListSubscriptionDefinitionVersionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_subscription_definition_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListSubscriptionDefinitionVersionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListSubscriptionDefinitionVersionsPaginator = client.get_paginator("list_subscription_definition_versions")
```

Boto3 documentation:
[Greengrass.Paginator.ListSubscriptionDefinitionVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListSubscriptionDefinitionVersions)

Arguments for `ListSubscriptionDefinitionVersionsPaginator.paginate` method:

- `SubscriptionDefinitionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSubscriptionDefinitionVersionsPaginator.paginate` returns
`_PageIterator`\[[ListSubscriptionDefinitionVersionsResponseTypeDef](./type_defs.md#listsubscriptiondefinitionversionsresponsetypedef)\].

<a id="listsubscriptiondefinitionspaginator"></a>

## ListSubscriptionDefinitionsPaginator

Type annotations for
`session.create_client("greengrass").get_paginator("list_subscription_definitions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_greengrass.paginator import ListSubscriptionDefinitionsPaginator

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
    paginator: ListSubscriptionDefinitionsPaginator = client.get_paginator("list_subscription_definitions")
```

Boto3 documentation:
[Greengrass.Paginator.ListSubscriptionDefinitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Paginator.ListSubscriptionDefinitions)

Arguments for `ListSubscriptionDefinitionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSubscriptionDefinitionsPaginator.paginate` returns
`_PageIterator`\[[ListSubscriptionDefinitionsResponseTypeDef](./type_defs.md#listsubscriptiondefinitionsresponsetypedef)\].
