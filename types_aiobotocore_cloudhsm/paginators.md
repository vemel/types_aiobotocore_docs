<a id="paginators-for-aiobotocore-cloudhsm-module"></a>

# Paginators for aiobotocore CloudHSM module

> [Index](..) > [CloudHSM](.) > Paginators

Auto-generated documentation for
[CloudHSM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM)
type annotations stubs module
[types-aiobotocore-cloudhsm](https://pypi.org/project/types-aiobotocore-cloudhsm/).

- [Paginators for aiobotocore CloudHSM module](#paginators-for-aiobotocore-cloudhsm-module)
  - [ListHapgsPaginator](#listhapgspaginator)
  - [ListHsmsPaginator](#listhsmspaginator)
  - [ListLunaClientsPaginator](#listlunaclientspaginator)

<a id="listhapgspaginator"></a>

## ListHapgsPaginator

Type annotations for
`aiobotocore.create_client("cloudhsm").get_paginator("list_hapgs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_cloudhsm.paginator import ListHapgsPaginator

def get_list_hapgs_paginator() -> ListHapgsPaginator:
    return Session().create_client("cloudhsm").get_paginator("list_hapgs")
```

Boto3 documentation:
[CloudHSM.Paginator.ListHapgs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHapgs)

Arguments for `ListHapgsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListHapgsPaginator.paginate` returns
`_PageIterator`\[[ListHapgsResponseTypeDef](./type_defs.md#listhapgsresponsetypedef)\].

<a id="listhsmspaginator"></a>

## ListHsmsPaginator

Type annotations for
`aiobotocore.create_client("cloudhsm").get_paginator("list_hsms")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_cloudhsm.paginator import ListHsmsPaginator

def get_list_hsms_paginator() -> ListHsmsPaginator:
    return Session().create_client("cloudhsm").get_paginator("list_hsms")
```

Boto3 documentation:
[CloudHSM.Paginator.ListHsms](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHsms)

Arguments for `ListHsmsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListHsmsPaginator.paginate` returns
`_PageIterator`\[[ListHsmsResponseTypeDef](./type_defs.md#listhsmsresponsetypedef)\].

<a id="listlunaclientspaginator"></a>

## ListLunaClientsPaginator

Type annotations for
`aiobotocore.create_client("cloudhsm").get_paginator("list_luna_clients")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_cloudhsm.paginator import ListLunaClientsPaginator

def get_list_luna_clients_paginator() -> ListLunaClientsPaginator:
    return Session().create_client("cloudhsm").get_paginator("list_luna_clients")
```

Boto3 documentation:
[CloudHSM.Paginator.ListLunaClients](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListLunaClients)

Arguments for `ListLunaClientsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListLunaClientsPaginator.paginate` returns
`_PageIterator`\[[ListLunaClientsResponseTypeDef](./type_defs.md#listlunaclientsresponsetypedef)\].
