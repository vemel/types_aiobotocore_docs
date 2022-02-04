<a id="emrcontainersclient-for-aiobotocore-emrcontainers-module"></a>

# EMRContainersClient for aiobotocore EMRContainers module

> [Index](..) > [EMRContainers](.) > EMRContainersClient

Auto-generated documentation for
[EMRContainers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers)
type annotations stubs module
[types-aiobotocore-emr-containers](https://pypi.org/project/types-aiobotocore-emr-containers/).

- [EMRContainersClient for aiobotocore EMRContainers module](#emrcontainersclient-for-aiobotocore-emrcontainers-module)
  - [EMRContainersClient](#emrcontainersclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [cancel_job_run](#cancel_job_run)
    - [create_managed_endpoint](#create_managed_endpoint)
    - [create_virtual_cluster](#create_virtual_cluster)
    - [delete_managed_endpoint](#delete_managed_endpoint)
    - [delete_virtual_cluster](#delete_virtual_cluster)
    - [describe_job_run](#describe_job_run)
    - [describe_managed_endpoint](#describe_managed_endpoint)
    - [describe_virtual_cluster](#describe_virtual_cluster)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_job_runs](#list_job_runs)
    - [list_managed_endpoints](#list_managed_endpoints)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_virtual_clusters](#list_virtual_clusters)
    - [start_job_run](#start_job_run)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [get_paginator](#get_paginator)

<a id="emrcontainersclient"></a>

## EMRContainersClient

Type annotations for `aiobotocore.create_client("emr-containers")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_emr_containers.client import EMRContainersClient

def get_emr-containers_client() -> EMRContainersClient:
    return Session().client("emr-containers")
```

Boto3 documentation:
[EMRContainers.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_emr_containers.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

EMRContainersClient exceptions.

Type annotations for `aiobotocore.create_client("emr-containers").exceptions`
method.

Boto3 documentation:
[EMRContainers.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("emr-containers").can_paginate`
method.

Boto3 documentation:
[EMRContainers.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_job_run"></a>

### cancel_job_run

Cancels a job run.

Type annotations for
`aiobotocore.create_client("emr-containers").cancel_job_run` method.

Boto3 documentation:
[EMRContainers.Client.cancel_job_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.cancel_job_run)

Asynchronous method. Use `await cancel_job_run(...)` for a synchronous call.

Arguments mapping described in
[CancelJobRunRequestRequestTypeDef](./type_defs.md#canceljobrunrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `virtualClusterId`: `str` *(required)*

Returns a `Coroutine` for
[CancelJobRunResponseTypeDef](./type_defs.md#canceljobrunresponsetypedef).

<a id="create_managed_endpoint"></a>

### create_managed_endpoint

Creates a managed endpoint.

Type annotations for
`aiobotocore.create_client("emr-containers").create_managed_endpoint` method.

Boto3 documentation:
[EMRContainers.Client.create_managed_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_managed_endpoint)

Asynchronous method. Use `await create_managed_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[CreateManagedEndpointRequestRequestTypeDef](./type_defs.md#createmanagedendpointrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `virtualClusterId`: `str` *(required)*
- `type`: `str` *(required)*
- `releaseLabel`: `str` *(required)*
- `executionRoleArn`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `certificateArn`: `str`
- `configurationOverrides`:
  [ConfigurationOverridesTypeDef](./type_defs.md#configurationoverridestypedef)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateManagedEndpointResponseTypeDef](./type_defs.md#createmanagedendpointresponsetypedef).

<a id="create_virtual_cluster"></a>

### create_virtual_cluster

Creates a virtual cluster.

Type annotations for
`aiobotocore.create_client("emr-containers").create_virtual_cluster` method.

Boto3 documentation:
[EMRContainers.Client.create_virtual_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_virtual_cluster)

Asynchronous method. Use `await create_virtual_cluster(...)` for a synchronous
call.

Arguments mapping described in
[CreateVirtualClusterRequestRequestTypeDef](./type_defs.md#createvirtualclusterrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `containerProvider`:
  [ContainerProviderTypeDef](./type_defs.md#containerprovidertypedef)
  *(required)*
- `clientToken`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateVirtualClusterResponseTypeDef](./type_defs.md#createvirtualclusterresponsetypedef).

<a id="delete_managed_endpoint"></a>

### delete_managed_endpoint

Deletes a managed endpoint.

Type annotations for
`aiobotocore.create_client("emr-containers").delete_managed_endpoint` method.

Boto3 documentation:
[EMRContainers.Client.delete_managed_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_managed_endpoint)

Asynchronous method. Use `await delete_managed_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[DeleteManagedEndpointRequestRequestTypeDef](./type_defs.md#deletemanagedendpointrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `virtualClusterId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteManagedEndpointResponseTypeDef](./type_defs.md#deletemanagedendpointresponsetypedef).

<a id="delete_virtual_cluster"></a>

### delete_virtual_cluster

Deletes a virtual cluster.

Type annotations for
`aiobotocore.create_client("emr-containers").delete_virtual_cluster` method.

Boto3 documentation:
[EMRContainers.Client.delete_virtual_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_virtual_cluster)

Asynchronous method. Use `await delete_virtual_cluster(...)` for a synchronous
call.

Arguments mapping described in
[DeleteVirtualClusterRequestRequestTypeDef](./type_defs.md#deletevirtualclusterrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[DeleteVirtualClusterResponseTypeDef](./type_defs.md#deletevirtualclusterresponsetypedef).

<a id="describe_job_run"></a>

### describe_job_run

Displays detailed information about a job run.

Type annotations for
`aiobotocore.create_client("emr-containers").describe_job_run` method.

Boto3 documentation:
[EMRContainers.Client.describe_job_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_job_run)

Asynchronous method. Use `await describe_job_run(...)` for a synchronous call.

Arguments mapping described in
[DescribeJobRunRequestRequestTypeDef](./type_defs.md#describejobrunrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `virtualClusterId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeJobRunResponseTypeDef](./type_defs.md#describejobrunresponsetypedef).

<a id="describe_managed_endpoint"></a>

### describe_managed_endpoint

Displays detailed information about a managed endpoint.

Type annotations for
`aiobotocore.create_client("emr-containers").describe_managed_endpoint` method.

Boto3 documentation:
[EMRContainers.Client.describe_managed_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_managed_endpoint)

Asynchronous method. Use `await describe_managed_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[DescribeManagedEndpointRequestRequestTypeDef](./type_defs.md#describemanagedendpointrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `virtualClusterId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeManagedEndpointResponseTypeDef](./type_defs.md#describemanagedendpointresponsetypedef).

<a id="describe_virtual_cluster"></a>

### describe_virtual_cluster

Displays detailed information about a specified virtual cluster.

Type annotations for
`aiobotocore.create_client("emr-containers").describe_virtual_cluster` method.

Boto3 documentation:
[EMRContainers.Client.describe_virtual_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_virtual_cluster)

Asynchronous method. Use `await describe_virtual_cluster(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVirtualClusterRequestRequestTypeDef](./type_defs.md#describevirtualclusterrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[DescribeVirtualClusterResponseTypeDef](./type_defs.md#describevirtualclusterresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("emr-containers").generate_presigned_url` method.

Boto3 documentation:
[EMRContainers.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_job_runs"></a>

### list_job_runs

Lists job runs based on a set of parameters.

Type annotations for
`aiobotocore.create_client("emr-containers").list_job_runs` method.

Boto3 documentation:
[EMRContainers.Client.list_job_runs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_job_runs)

Asynchronous method. Use `await list_job_runs(...)` for a synchronous call.

Arguments mapping described in
[ListJobRunsRequestRequestTypeDef](./type_defs.md#listjobrunsrequestrequesttypedef).

Keyword-only arguments:

- `virtualClusterId`: `str` *(required)*
- `createdBefore`: `Union`\[`datetime`, `str`\]
- `createdAfter`: `Union`\[`datetime`, `str`\]
- `name`: `str`
- `states`: `Sequence`\[[JobRunStateType](./literals.md#jobrunstatetype)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListJobRunsResponseTypeDef](./type_defs.md#listjobrunsresponsetypedef).

<a id="list_managed_endpoints"></a>

### list_managed_endpoints

Lists managed endpoints based on a set of parameters.

Type annotations for
`aiobotocore.create_client("emr-containers").list_managed_endpoints` method.

Boto3 documentation:
[EMRContainers.Client.list_managed_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_managed_endpoints)

Asynchronous method. Use `await list_managed_endpoints(...)` for a synchronous
call.

Arguments mapping described in
[ListManagedEndpointsRequestRequestTypeDef](./type_defs.md#listmanagedendpointsrequestrequesttypedef).

Keyword-only arguments:

- `virtualClusterId`: `str` *(required)*
- `createdBefore`: `Union`\[`datetime`, `str`\]
- `createdAfter`: `Union`\[`datetime`, `str`\]
- `types`: `Sequence`\[`str`\]
- `states`: `Sequence`\[[EndpointStateType](./literals.md#endpointstatetype)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListManagedEndpointsResponseTypeDef](./type_defs.md#listmanagedendpointsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags assigned to the resources.

Type annotations for
`aiobotocore.create_client("emr-containers").list_tags_for_resource` method.

Boto3 documentation:
[EMRContainers.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list_virtual_clusters"></a>

### list_virtual_clusters

Lists information about the specified virtual cluster.

Type annotations for
`aiobotocore.create_client("emr-containers").list_virtual_clusters` method.

Boto3 documentation:
[EMRContainers.Client.list_virtual_clusters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_virtual_clusters)

Asynchronous method. Use `await list_virtual_clusters(...)` for a synchronous
call.

Arguments mapping described in
[ListVirtualClustersRequestRequestTypeDef](./type_defs.md#listvirtualclustersrequestrequesttypedef).

Keyword-only arguments:

- `containerProviderId`: `str`
- `containerProviderType`: `Literal['EKS']` (see
  [ContainerProviderTypeType](./literals.md#containerprovidertypetype))
- `createdAfter`: `Union`\[`datetime`, `str`\]
- `createdBefore`: `Union`\[`datetime`, `str`\]
- `states`:
  `Sequence`\[[VirtualClusterStateType](./literals.md#virtualclusterstatetype)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListVirtualClustersResponseTypeDef](./type_defs.md#listvirtualclustersresponsetypedef).

<a id="start_job_run"></a>

### start_job_run

Starts a job run.

Type annotations for
`aiobotocore.create_client("emr-containers").start_job_run` method.

Boto3 documentation:
[EMRContainers.Client.start_job_run](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.start_job_run)

Asynchronous method. Use `await start_job_run(...)` for a synchronous call.

Arguments mapping described in
[StartJobRunRequestRequestTypeDef](./type_defs.md#startjobrunrequestrequesttypedef).

Keyword-only arguments:

- `virtualClusterId`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `executionRoleArn`: `str` *(required)*
- `releaseLabel`: `str` *(required)*
- `jobDriver`: [JobDriverTypeDef](./type_defs.md#jobdrivertypedef) *(required)*
- `name`: `str`
- `configurationOverrides`:
  [ConfigurationOverridesTypeDef](./type_defs.md#configurationoverridestypedef)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[StartJobRunResponseTypeDef](./type_defs.md#startjobrunresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Assigns tags to resources.

Type annotations for `aiobotocore.create_client("emr-containers").tag_resource`
method.

Boto3 documentation:
[EMRContainers.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from resources.

Type annotations for
`aiobotocore.create_client("emr-containers").untag_resource` method.

Boto3 documentation:
[EMRContainers.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("emr-containers").get_paginator` method with
overloads.

- `client.get_paginator("list_job_runs")` ->
  [ListJobRunsPaginator](./paginators.md#listjobrunspaginator)
- `client.get_paginator("list_managed_endpoints")` ->
  [ListManagedEndpointsPaginator](./paginators.md#listmanagedendpointspaginator)
- `client.get_paginator("list_virtual_clusters")` ->
  [ListVirtualClustersPaginator](./paginators.md#listvirtualclusterspaginator)
