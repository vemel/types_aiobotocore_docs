<a id="paginators-for-aiobotocore-appstream-module"></a>

# Paginators for aiobotocore AppStream module

> [Index](..) > [AppStream](.) > Paginators

Auto-generated documentation for
[AppStream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
type annotations stubs module
[types-aiobotocore-appstream](https://pypi.org/project/types-aiobotocore-appstream/).

- [Paginators for aiobotocore AppStream module](#paginators-for-aiobotocore-appstream-module)
  - [DescribeDirectoryConfigsPaginator](#describedirectoryconfigspaginator)
  - [DescribeFleetsPaginator](#describefleetspaginator)
  - [DescribeImageBuildersPaginator](#describeimagebuilderspaginator)
  - [DescribeImagesPaginator](#describeimagespaginator)
  - [DescribeSessionsPaginator](#describesessionspaginator)
  - [DescribeStacksPaginator](#describestackspaginator)
  - [DescribeUserStackAssociationsPaginator](#describeuserstackassociationspaginator)
  - [DescribeUsersPaginator](#describeuserspaginator)
  - [ListAssociatedFleetsPaginator](#listassociatedfleetspaginator)
  - [ListAssociatedStacksPaginator](#listassociatedstackspaginator)

<a id="describedirectoryconfigspaginator"></a>

## DescribeDirectoryConfigsPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_directory_configs")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeDirectoryConfigsPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeDirectoryConfigsPaginator = client.get_paginator("describe_directory_configs")
```

Boto3 documentation:
[AppStream.Paginator.DescribeDirectoryConfigs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeDirectoryConfigs)

Arguments for `DescribeDirectoryConfigsPaginator.paginate` method:

- `DirectoryNames`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDirectoryConfigsPaginator.paginate` returns
`_PageIterator`\[[DescribeDirectoryConfigsResultTypeDef](./type_defs.md#describedirectoryconfigsresulttypedef)\].

<a id="describefleetspaginator"></a>

## DescribeFleetsPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_fleets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeFleetsPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeFleetsPaginator = client.get_paginator("describe_fleets")
```

Boto3 documentation:
[AppStream.Paginator.DescribeFleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeFleets)

Arguments for `DescribeFleetsPaginator.paginate` method:

- `Names`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFleetsPaginator.paginate` returns
`_PageIterator`\[[DescribeFleetsResultTypeDef](./type_defs.md#describefleetsresulttypedef)\].

<a id="describeimagebuilderspaginator"></a>

## DescribeImageBuildersPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_image_builders")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeImageBuildersPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeImageBuildersPaginator = client.get_paginator("describe_image_builders")
```

Boto3 documentation:
[AppStream.Paginator.DescribeImageBuilders](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImageBuilders)

Arguments for `DescribeImageBuildersPaginator.paginate` method:

- `Names`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeImageBuildersPaginator.paginate` returns
`_PageIterator`\[[DescribeImageBuildersResultTypeDef](./type_defs.md#describeimagebuildersresulttypedef)\].

<a id="describeimagespaginator"></a>

## DescribeImagesPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_images")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeImagesPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeImagesPaginator = client.get_paginator("describe_images")
```

Boto3 documentation:
[AppStream.Paginator.DescribeImages](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImages)

Arguments for `DescribeImagesPaginator.paginate` method:

- `Names`: `Sequence`\[`str`\]
- `Arns`: `Sequence`\[`str`\]
- `Type`: [VisibilityTypeType](./literals.md#visibilitytypetype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeImagesPaginator.paginate` returns
`_PageIterator`\[[DescribeImagesResultTypeDef](./type_defs.md#describeimagesresulttypedef)\].

<a id="describesessionspaginator"></a>

## DescribeSessionsPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_sessions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeSessionsPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeSessionsPaginator = client.get_paginator("describe_sessions")
```

Boto3 documentation:
[AppStream.Paginator.DescribeSessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeSessions)

Arguments for `DescribeSessionsPaginator.paginate` method:

- `StackName`: `str` *(required)*
- `FleetName`: `str` *(required)*
- `UserId`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSessionsPaginator.paginate` returns
`_PageIterator`\[[DescribeSessionsResultTypeDef](./type_defs.md#describesessionsresulttypedef)\].

<a id="describestackspaginator"></a>

## DescribeStacksPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_stacks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeStacksPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeStacksPaginator = client.get_paginator("describe_stacks")
```

Boto3 documentation:
[AppStream.Paginator.DescribeStacks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeStacks)

Arguments for `DescribeStacksPaginator.paginate` method:

- `Names`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeStacksPaginator.paginate` returns
`_PageIterator`\[[DescribeStacksResultTypeDef](./type_defs.md#describestacksresulttypedef)\].

<a id="describeuserstackassociationspaginator"></a>

## DescribeUserStackAssociationsPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_user_stack_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeUserStackAssociationsPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeUserStackAssociationsPaginator = client.get_paginator("describe_user_stack_associations")
```

Boto3 documentation:
[AppStream.Paginator.DescribeUserStackAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUserStackAssociations)

Arguments for `DescribeUserStackAssociationsPaginator.paginate` method:

- `StackName`: `str`
- `UserName`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeUserStackAssociationsPaginator.paginate` returns
`_PageIterator`\[[DescribeUserStackAssociationsResultTypeDef](./type_defs.md#describeuserstackassociationsresulttypedef)\].

<a id="describeuserspaginator"></a>

## DescribeUsersPaginator

Type annotations for
`session.create_client("appstream").get_paginator("describe_users")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import DescribeUsersPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
```

Boto3 documentation:
[AppStream.Paginator.DescribeUsers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUsers)

Arguments for `DescribeUsersPaginator.paginate` method:

- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype) *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeUsersPaginator.paginate` returns
`_PageIterator`\[[DescribeUsersResultTypeDef](./type_defs.md#describeusersresulttypedef)\].

<a id="listassociatedfleetspaginator"></a>

## ListAssociatedFleetsPaginator

Type annotations for
`session.create_client("appstream").get_paginator("list_associated_fleets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import ListAssociatedFleetsPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: ListAssociatedFleetsPaginator = client.get_paginator("list_associated_fleets")
```

Boto3 documentation:
[AppStream.Paginator.ListAssociatedFleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedFleets)

Arguments for `ListAssociatedFleetsPaginator.paginate` method:

- `StackName`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAssociatedFleetsPaginator.paginate` returns
`_PageIterator`\[[ListAssociatedFleetsResultTypeDef](./type_defs.md#listassociatedfleetsresulttypedef)\].

<a id="listassociatedstackspaginator"></a>

## ListAssociatedStacksPaginator

Type annotations for
`session.create_client("appstream").get_paginator("list_associated_stacks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_appstream.paginator import ListAssociatedStacksPaginator

session = get_session()
async with session.create_client("appstream") as client:
    client: AppStreamClient
    paginator: ListAssociatedStacksPaginator = client.get_paginator("list_associated_stacks")
```

Boto3 documentation:
[AppStream.Paginator.ListAssociatedStacks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedStacks)

Arguments for `ListAssociatedStacksPaginator.paginate` method:

- `FleetName`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAssociatedStacksPaginator.paginate` returns
`_PageIterator`\[[ListAssociatedStacksResultTypeDef](./type_defs.md#listassociatedstacksresulttypedef)\].
