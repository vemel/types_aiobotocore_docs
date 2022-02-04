<a id="type-annotations-for-aiobotocore-iotfleethub-module"></a>

# Type annotations for aiobotocore IoTFleetHub module

> [Index](..) > IoTFleetHub

Auto-generated documentation for
[IoTFleetHub](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub)
type annotations stubs module
[types-aiobotocore-iotfleethub](https://pypi.org/project/types-aiobotocore-iotfleethub/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[iotfleethub]'

# install as a standalone
pip install types-aiobotocore-iotfleethub
```

- [Type annotations for aiobotocore IoTFleetHub module](#type-annotations-for-aiobotocore-iotfleethub-module)
  - [IoTFleetHubClient](#iotfleethubclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="iotfleethubclient"></a>

## IoTFleetHubClient

Type annotations for `aiobotocore.create_client("iotfleethub")` as
[IoTFleetHubClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_iotfleethub.client import IoTFleetHubClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_application](./client.md#create_application)
- [delete_application](./client.md#delete_application)
- [describe_application](./client.md#describe_application)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [list_applications](./client.md#list_applications)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_application](./client.md#update_application)

<a id="exceptions"></a>

### Exceptions

IoTFleetHubClient [exceptions](./client.md#exceptions)

- ClientError
- ConflictException
- InternalFailureException
- InvalidRequestException
- LimitExceededException
- ResourceNotFoundException
- ThrottlingException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("iotfleethub").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_iotfleethub.paginators import ListApplicationsPaginator, ...
```

- [ListApplicationsPaginator](./paginators.md#listapplicationspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_iotfleethub.literals import ApplicationStateType, ...
```

- [ApplicationStateType](./literals.md#applicationstatetype)
- [ListApplicationsPaginatorName](./literals.md#listapplicationspaginatorname)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_iotfleethub.type_defs import ApplicationSummaryTypeDef, ...
```

- [ApplicationSummaryTypeDef](./type_defs.md#applicationsummarytypedef)
- [CreateApplicationRequestRequestTypeDef](./type_defs.md#createapplicationrequestrequesttypedef)
- [CreateApplicationResponseTypeDef](./type_defs.md#createapplicationresponsetypedef)
- [DeleteApplicationRequestRequestTypeDef](./type_defs.md#deleteapplicationrequestrequesttypedef)
- [DescribeApplicationRequestRequestTypeDef](./type_defs.md#describeapplicationrequestrequesttypedef)
- [DescribeApplicationResponseTypeDef](./type_defs.md#describeapplicationresponsetypedef)
- [ListApplicationsRequestRequestTypeDef](./type_defs.md#listapplicationsrequestrequesttypedef)
- [ListApplicationsResponseTypeDef](./type_defs.md#listapplicationsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateApplicationRequestRequestTypeDef](./type_defs.md#updateapplicationrequestrequesttypedef)
