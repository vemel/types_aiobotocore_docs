<a id="paginators-for-aiobotocore-rekognition-module"></a>

# Paginators for aiobotocore Rekognition module

> [Index](..) > [Rekognition](.) > Paginators

Auto-generated documentation for
[Rekognition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition)
type annotations stubs module
[types-aiobotocore-rekognition](https://pypi.org/project/types-aiobotocore-rekognition/).

- [Paginators for aiobotocore Rekognition module](#paginators-for-aiobotocore-rekognition-module)
  - [DescribeProjectVersionsPaginator](#describeprojectversionspaginator)
  - [DescribeProjectsPaginator](#describeprojectspaginator)
  - [ListCollectionsPaginator](#listcollectionspaginator)
  - [ListDatasetEntriesPaginator](#listdatasetentriespaginator)
  - [ListDatasetLabelsPaginator](#listdatasetlabelspaginator)
  - [ListFacesPaginator](#listfacespaginator)
  - [ListStreamProcessorsPaginator](#liststreamprocessorspaginator)

<a id="describeprojectversionspaginator"></a>

## DescribeProjectVersionsPaginator

Type annotations for
`aiobotocore.create_client("rekognition").get_paginator("describe_project_versions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_rekognition.paginator import DescribeProjectVersionsPaginator

def get_describe_project_versions_paginator() -> DescribeProjectVersionsPaginator:
    return Session().create_client("rekognition").get_paginator("describe_project_versions")
```

Boto3 documentation:
[Rekognition.Paginator.DescribeProjectVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjectVersions)

Arguments for `DescribeProjectVersionsPaginator.paginate` method:

- `ProjectArn`: `str` *(required)*
- `VersionNames`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeProjectVersionsPaginator.paginate` returns
`_PageIterator`\[[DescribeProjectVersionsResponseTypeDef](./type_defs.md#describeprojectversionsresponsetypedef)\].

<a id="describeprojectspaginator"></a>

## DescribeProjectsPaginator

Type annotations for
`aiobotocore.create_client("rekognition").get_paginator("describe_projects")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_rekognition.paginator import DescribeProjectsPaginator

def get_describe_projects_paginator() -> DescribeProjectsPaginator:
    return Session().create_client("rekognition").get_paginator("describe_projects")
```

Boto3 documentation:
[Rekognition.Paginator.DescribeProjects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjects)

Arguments for `DescribeProjectsPaginator.paginate` method:

- `ProjectNames`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeProjectsPaginator.paginate` returns
`_PageIterator`\[[DescribeProjectsResponseTypeDef](./type_defs.md#describeprojectsresponsetypedef)\].

<a id="listcollectionspaginator"></a>

## ListCollectionsPaginator

Type annotations for
`aiobotocore.create_client("rekognition").get_paginator("list_collections")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_rekognition.paginator import ListCollectionsPaginator

def get_list_collections_paginator() -> ListCollectionsPaginator:
    return Session().create_client("rekognition").get_paginator("list_collections")
```

Boto3 documentation:
[Rekognition.Paginator.ListCollections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListCollections)

Arguments for `ListCollectionsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListCollectionsPaginator.paginate` returns
`_PageIterator`\[[ListCollectionsResponseTypeDef](./type_defs.md#listcollectionsresponsetypedef)\].

<a id="listdatasetentriespaginator"></a>

## ListDatasetEntriesPaginator

Type annotations for
`aiobotocore.create_client("rekognition").get_paginator("list_dataset_entries")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_rekognition.paginator import ListDatasetEntriesPaginator

def get_list_dataset_entries_paginator() -> ListDatasetEntriesPaginator:
    return Session().create_client("rekognition").get_paginator("list_dataset_entries")
```

Boto3 documentation:
[Rekognition.Paginator.ListDatasetEntries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetEntries)

Arguments for `ListDatasetEntriesPaginator.paginate` method:

- `DatasetArn`: `str` *(required)*
- `ContainsLabels`: `Sequence`\[`str`\]
- `Labeled`: `bool`
- `SourceRefContains`: `str`
- `HasErrors`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDatasetEntriesPaginator.paginate` returns
`_PageIterator`\[[ListDatasetEntriesResponseTypeDef](./type_defs.md#listdatasetentriesresponsetypedef)\].

<a id="listdatasetlabelspaginator"></a>

## ListDatasetLabelsPaginator

Type annotations for
`aiobotocore.create_client("rekognition").get_paginator("list_dataset_labels")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_rekognition.paginator import ListDatasetLabelsPaginator

def get_list_dataset_labels_paginator() -> ListDatasetLabelsPaginator:
    return Session().create_client("rekognition").get_paginator("list_dataset_labels")
```

Boto3 documentation:
[Rekognition.Paginator.ListDatasetLabels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetLabels)

Arguments for `ListDatasetLabelsPaginator.paginate` method:

- `DatasetArn`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDatasetLabelsPaginator.paginate` returns
`_PageIterator`\[[ListDatasetLabelsResponseTypeDef](./type_defs.md#listdatasetlabelsresponsetypedef)\].

<a id="listfacespaginator"></a>

## ListFacesPaginator

Type annotations for
`aiobotocore.create_client("rekognition").get_paginator("list_faces")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_rekognition.paginator import ListFacesPaginator

def get_list_faces_paginator() -> ListFacesPaginator:
    return Session().create_client("rekognition").get_paginator("list_faces")
```

Boto3 documentation:
[Rekognition.Paginator.ListFaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListFaces)

Arguments for `ListFacesPaginator.paginate` method:

- `CollectionId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListFacesPaginator.paginate` returns
`_PageIterator`\[[ListFacesResponseTypeDef](./type_defs.md#listfacesresponsetypedef)\].

<a id="liststreamprocessorspaginator"></a>

## ListStreamProcessorsPaginator

Type annotations for
`aiobotocore.create_client("rekognition").get_paginator("list_stream_processors")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_rekognition.paginator import ListStreamProcessorsPaginator

def get_list_stream_processors_paginator() -> ListStreamProcessorsPaginator:
    return Session().create_client("rekognition").get_paginator("list_stream_processors")
```

Boto3 documentation:
[Rekognition.Paginator.ListStreamProcessors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListStreamProcessors)

Arguments for `ListStreamProcessorsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListStreamProcessorsPaginator.paginate` returns
`_PageIterator`\[[ListStreamProcessorsResponseTypeDef](./type_defs.md#liststreamprocessorsresponsetypedef)\].
