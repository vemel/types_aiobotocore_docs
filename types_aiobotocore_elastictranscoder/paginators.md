<a id="paginators-for-aiobotocore-elastictranscoder-module"></a>

# Paginators for aiobotocore ElasticTranscoder module

> [Index](..) > [ElasticTranscoder](.) > Paginators

Auto-generated documentation for
[ElasticTranscoder](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder)
type annotations stubs module
[types-aiobotocore-elastictranscoder](https://pypi.org/project/types-aiobotocore-elastictranscoder/).

- [Paginators for aiobotocore ElasticTranscoder module](#paginators-for-aiobotocore-elastictranscoder-module)
  - [ListJobsByPipelinePaginator](#listjobsbypipelinepaginator)
  - [ListJobsByStatusPaginator](#listjobsbystatuspaginator)
  - [ListPipelinesPaginator](#listpipelinespaginator)
  - [ListPresetsPaginator](#listpresetspaginator)

<a id="listjobsbypipelinepaginator"></a>

## ListJobsByPipelinePaginator

Type annotations for
`aiobotocore.create_client("elastictranscoder").get_paginator("list_jobs_by_pipeline")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_elastictranscoder.paginator import ListJobsByPipelinePaginator

def get_list_jobs_by_pipeline_paginator() -> ListJobsByPipelinePaginator:
    return Session().create_client("elastictranscoder").get_paginator("list_jobs_by_pipeline")
```

Boto3 documentation:
[ElasticTranscoder.Paginator.ListJobsByPipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByPipeline)

Arguments for `ListJobsByPipelinePaginator.paginate` method:

- `PipelineId`: `str` *(required)*
- `Ascending`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListJobsByPipelinePaginator.paginate` returns
`_PageIterator`\[[ListJobsByPipelineResponseTypeDef](./type_defs.md#listjobsbypipelineresponsetypedef)\].

<a id="listjobsbystatuspaginator"></a>

## ListJobsByStatusPaginator

Type annotations for
`aiobotocore.create_client("elastictranscoder").get_paginator("list_jobs_by_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_elastictranscoder.paginator import ListJobsByStatusPaginator

def get_list_jobs_by_status_paginator() -> ListJobsByStatusPaginator:
    return Session().create_client("elastictranscoder").get_paginator("list_jobs_by_status")
```

Boto3 documentation:
[ElasticTranscoder.Paginator.ListJobsByStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByStatus)

Arguments for `ListJobsByStatusPaginator.paginate` method:

- `Status`: `str` *(required)*
- `Ascending`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListJobsByStatusPaginator.paginate` returns
`_PageIterator`\[[ListJobsByStatusResponseTypeDef](./type_defs.md#listjobsbystatusresponsetypedef)\].

<a id="listpipelinespaginator"></a>

## ListPipelinesPaginator

Type annotations for
`aiobotocore.create_client("elastictranscoder").get_paginator("list_pipelines")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_elastictranscoder.paginator import ListPipelinesPaginator

def get_list_pipelines_paginator() -> ListPipelinesPaginator:
    return Session().create_client("elastictranscoder").get_paginator("list_pipelines")
```

Boto3 documentation:
[ElasticTranscoder.Paginator.ListPipelines](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPipelines)

Arguments for `ListPipelinesPaginator.paginate` method:

- `Ascending`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPipelinesPaginator.paginate` returns
`_PageIterator`\[[ListPipelinesResponseTypeDef](./type_defs.md#listpipelinesresponsetypedef)\].

<a id="listpresetspaginator"></a>

## ListPresetsPaginator

Type annotations for
`aiobotocore.create_client("elastictranscoder").get_paginator("list_presets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_elastictranscoder.paginator import ListPresetsPaginator

def get_list_presets_paginator() -> ListPresetsPaginator:
    return Session().create_client("elastictranscoder").get_paginator("list_presets")
```

Boto3 documentation:
[ElasticTranscoder.Paginator.ListPresets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPresets)

Arguments for `ListPresetsPaginator.paginate` method:

- `Ascending`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPresetsPaginator.paginate` returns
`_PageIterator`\[[ListPresetsResponseTypeDef](./type_defs.md#listpresetsresponsetypedef)\].
