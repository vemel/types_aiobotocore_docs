<a id="paginators-for-aiobotocore-glacier-module"></a>

# Paginators for aiobotocore Glacier module

> [Index](..) > [Glacier](.) > Paginators

Auto-generated documentation for
[Glacier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
type annotations stubs module
[types-aiobotocore-glacier](https://pypi.org/project/types-aiobotocore-glacier/).

- [Paginators for aiobotocore Glacier module](#paginators-for-aiobotocore-glacier-module)
  - [ListJobsPaginator](#listjobspaginator)
  - [ListMultipartUploadsPaginator](#listmultipartuploadspaginator)
  - [ListPartsPaginator](#listpartspaginator)
  - [ListVaultsPaginator](#listvaultspaginator)

<a id="listjobspaginator"></a>

## ListJobsPaginator

Type annotations for
`aiobotocore.create_client("glacier").get_paginator("list_jobs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_glacier.paginator import ListJobsPaginator

def get_list_jobs_paginator() -> ListJobsPaginator:
    return Session().create_client("glacier").get_paginator("list_jobs")
```

Boto3 documentation:
[Glacier.Paginator.ListJobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListJobs)

Arguments for `ListJobsPaginator.paginate` method:

- `accountId`: `str` *(required)*
- `vaultName`: `str` *(required)*
- `statuscode`: `str`
- `completed`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListJobsPaginator.paginate` returns
`_PageIterator`\[[ListJobsOutputTypeDef](./type_defs.md#listjobsoutputtypedef)\].

<a id="listmultipartuploadspaginator"></a>

## ListMultipartUploadsPaginator

Type annotations for
`aiobotocore.create_client("glacier").get_paginator("list_multipart_uploads")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_glacier.paginator import ListMultipartUploadsPaginator

def get_list_multipart_uploads_paginator() -> ListMultipartUploadsPaginator:
    return Session().create_client("glacier").get_paginator("list_multipart_uploads")
```

Boto3 documentation:
[Glacier.Paginator.ListMultipartUploads](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListMultipartUploads)

Arguments for `ListMultipartUploadsPaginator.paginate` method:

- `accountId`: `str` *(required)*
- `vaultName`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListMultipartUploadsPaginator.paginate` returns
`_PageIterator`\[[ListMultipartUploadsOutputTypeDef](./type_defs.md#listmultipartuploadsoutputtypedef)\].

<a id="listpartspaginator"></a>

## ListPartsPaginator

Type annotations for
`aiobotocore.create_client("glacier").get_paginator("list_parts")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_glacier.paginator import ListPartsPaginator

def get_list_parts_paginator() -> ListPartsPaginator:
    return Session().create_client("glacier").get_paginator("list_parts")
```

Boto3 documentation:
[Glacier.Paginator.ListParts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListParts)

Arguments for `ListPartsPaginator.paginate` method:

- `accountId`: `str` *(required)*
- `vaultName`: `str` *(required)*
- `uploadId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPartsPaginator.paginate` returns
`_PageIterator`\[[ListPartsOutputTypeDef](./type_defs.md#listpartsoutputtypedef)\].

<a id="listvaultspaginator"></a>

## ListVaultsPaginator

Type annotations for
`aiobotocore.create_client("glacier").get_paginator("list_vaults")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_glacier.paginator import ListVaultsPaginator

def get_list_vaults_paginator() -> ListVaultsPaginator:
    return Session().create_client("glacier").get_paginator("list_vaults")
```

Boto3 documentation:
[Glacier.Paginator.ListVaults](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListVaults)

Arguments for `ListVaultsPaginator.paginate` method:

- `accountId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListVaultsPaginator.paginate` returns
`_PageIterator`\[[ListVaultsOutputTypeDef](./type_defs.md#listvaultsoutputtypedef)\].
