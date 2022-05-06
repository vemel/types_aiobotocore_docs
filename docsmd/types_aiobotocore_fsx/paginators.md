# Paginators

> [Index](../README.md) > [FSx](./README.md) > Paginators

!!! note ""

    Auto-generated documentation for [FSx](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
    type annotations stubs module [types-aiobotocore-fsx](https://pypi.org/project/types-aiobotocore-fsx/).

## DescribeBackupsPaginator

Type annotations and code completion for `#!python session.create_client("fsx").get_paginator("describe_backups")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeBackups)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_fsx.paginator import DescribeBackupsPaginator

session = get_session()
async with session.create_client("fsx") as client:
    client: FSxClient
    paginator: DescribeBackupsPaginator = client.get_paginator("describe_backups")
```


### paginate

Type annotations and code completion for `#!python DescribeBackupsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    BackupIds: Sequence[str] = ...,
    Filters: Sequence[FilterTypeDef] = ...,  # (1)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[DescribeBackupsResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-braces: FilterTypeDef](./type_defs.md#filtertypedef) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: DescribeBackupsResponseTypeDef](./type_defs.md#describebackupsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeBackupsRequestDescribeBackupsPaginateTypeDef = {  # (1)
    "BackupIds": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeBackupsRequestDescribeBackupsPaginateTypeDef](./type_defs.md#describebackupsrequestdescribebackupspaginatetypedef) 
## DescribeFileSystemsPaginator

Type annotations and code completion for `#!python session.create_client("fsx").get_paginator("describe_file_systems")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeFileSystems)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_fsx.paginator import DescribeFileSystemsPaginator

session = get_session()
async with session.create_client("fsx") as client:
    client: FSxClient
    paginator: DescribeFileSystemsPaginator = client.get_paginator("describe_file_systems")
```


### paginate

Type annotations and code completion for `#!python DescribeFileSystemsPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    FileSystemIds: Sequence[str] = ...,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[DescribeFileSystemsResponseTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: DescribeFileSystemsResponseTypeDef](./type_defs.md#describefilesystemsresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = {  # (1)
    "FileSystemIds": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef](./type_defs.md#describefilesystemsrequestdescribefilesystemspaginatetypedef) 
## DescribeStorageVirtualMachinesPaginator

Type annotations and code completion for `#!python session.create_client("fsx").get_paginator("describe_storage_virtual_machines")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeStorageVirtualMachines)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_fsx.paginator import DescribeStorageVirtualMachinesPaginator

session = get_session()
async with session.create_client("fsx") as client:
    client: FSxClient
    paginator: DescribeStorageVirtualMachinesPaginator = client.get_paginator("describe_storage_virtual_machines")
```


### paginate

Type annotations and code completion for `#!python DescribeStorageVirtualMachinesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    StorageVirtualMachineIds: Sequence[str] = ...,
    Filters: Sequence[StorageVirtualMachineFilterTypeDef] = ...,  # (1)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[DescribeStorageVirtualMachinesResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-braces: StorageVirtualMachineFilterTypeDef](./type_defs.md#storagevirtualmachinefiltertypedef) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: DescribeStorageVirtualMachinesResponseTypeDef](./type_defs.md#describestoragevirtualmachinesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef = {  # (1)
    "StorageVirtualMachineIds": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef](./type_defs.md#describestoragevirtualmachinesrequestdescribestoragevirtualmachinespaginatetypedef) 
## DescribeVolumesPaginator

Type annotations and code completion for `#!python session.create_client("fsx").get_paginator("describe_volumes")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeVolumes)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_fsx.paginator import DescribeVolumesPaginator

session = get_session()
async with session.create_client("fsx") as client:
    client: FSxClient
    paginator: DescribeVolumesPaginator = client.get_paginator("describe_volumes")
```


### paginate

Type annotations and code completion for `#!python DescribeVolumesPaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    VolumeIds: Sequence[str] = ...,
    Filters: Sequence[VolumeFilterTypeDef] = ...,  # (1)
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (2)
) -> AsyncIterator[DescribeVolumesResponseTypeDef]:  # (3)
    ...
```

1. See [:material-code-braces: VolumeFilterTypeDef](./type_defs.md#volumefiltertypedef) 
2. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
3. See [:material-code-braces: DescribeVolumesResponseTypeDef](./type_defs.md#describevolumesresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: DescribeVolumesRequestDescribeVolumesPaginateTypeDef = {  # (1)
    "VolumeIds": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: DescribeVolumesRequestDescribeVolumesPaginateTypeDef](./type_defs.md#describevolumesrequestdescribevolumespaginatetypedef) 
## ListTagsForResourcePaginator

Type annotations and code completion for `#!python session.create_client("fsx").get_paginator("list_tags_for_resource")`.
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.ListTagsForResource)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_fsx.paginator import ListTagsForResourcePaginator

session = get_session()
async with session.create_client("fsx") as client:
    client: FSxClient
    paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
```


### paginate

Type annotations and code completion for `#!python ListTagsForResourcePaginator.paginate` method.

```python title="Method definition"
def paginate(
    self,
    *,
    ResourceARN: str,
    PaginationConfig: PaginatorConfigTypeDef = ...,  # (1)
) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:  # (2)
    ...
```

1. See [:material-code-braces: PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef) 
2. See [:material-code-braces: ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef) 


```python title="Usage example with kwargs"
kwargs: ListTagsForResourceRequestListTagsForResourcePaginateTypeDef = {  # (1)
    "ResourceARN": ...,
}

parent.paginate(**kwargs)
```

1. See [:material-code-braces: ListTagsForResourceRequestListTagsForResourcePaginateTypeDef](./type_defs.md#listtagsforresourcerequestlisttagsforresourcepaginatetypedef) 
