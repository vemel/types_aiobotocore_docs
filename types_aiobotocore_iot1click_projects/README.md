<a id="type-annotations-for-aiobotocore-iot1clickprojects-module"></a>

# Type annotations for aiobotocore IoT1ClickProjects module

> [Index](..) > IoT1ClickProjects

Auto-generated documentation for
[IoT1ClickProjects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects)
type annotations stubs module
[types-aiobotocore-iot1click-projects](https://pypi.org/project/types-aiobotocore-iot1click-projects/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[iot1click-projects]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[iot1click-projects]'

# standalone installation
pip install types-aiobotocore-iot1click-projects
```

- [Type annotations for aiobotocore IoT1ClickProjects module](#type-annotations-for-aiobotocore-iot1clickprojects-module)
  - [IoT1ClickProjectsClient](#iot1clickprojectsclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="iot1clickprojectsclient"></a>

## IoT1ClickProjectsClient

Type annotations for `session.create_client("iot1click-projects")` as
[IoT1ClickProjectsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_iot1click_projects.client import IoT1ClickProjectsClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [associate_device_with_placement](./client.md#associate_device_with_placement)
- [can_paginate](./client.md#can_paginate)
- [create_placement](./client.md#create_placement)
- [create_project](./client.md#create_project)
- [delete_placement](./client.md#delete_placement)
- [delete_project](./client.md#delete_project)
- [describe_placement](./client.md#describe_placement)
- [describe_project](./client.md#describe_project)
- [disassociate_device_from_placement](./client.md#disassociate_device_from_placement)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_devices_in_placement](./client.md#get_devices_in_placement)
- [get_paginator](./client.md#get_paginator)
- [list_placements](./client.md#list_placements)
- [list_projects](./client.md#list_projects)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_placement](./client.md#update_placement)
- [update_project](./client.md#update_project)

<a id="exceptions"></a>

### Exceptions

IoT1ClickProjectsClient [exceptions](./client.md#exceptions)

- ClientError
- InternalFailureException
- InvalidRequestException
- ResourceConflictException
- ResourceNotFoundException
- TooManyRequestsException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("iot1click-projects").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_iot1click_projects.paginator import ListPlacementsPaginator, ...
```

- [ListPlacementsPaginator](./paginators.md#listplacementspaginator)
- [ListProjectsPaginator](./paginators.md#listprojectspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_iot1click_projects.literals import ListPlacementsPaginatorName, ...
```

- [ListPlacementsPaginatorName](./literals.md#listplacementspaginatorname)
- [ListProjectsPaginatorName](./literals.md#listprojectspaginatorname)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_iot1click_projects.type_defs import AssociateDeviceWithPlacementRequestRequestTypeDef, ...
```

- [AssociateDeviceWithPlacementRequestRequestTypeDef](./type_defs.md#associatedevicewithplacementrequestrequesttypedef)
- [CreatePlacementRequestRequestTypeDef](./type_defs.md#createplacementrequestrequesttypedef)
- [CreateProjectRequestRequestTypeDef](./type_defs.md#createprojectrequestrequesttypedef)
- [DeletePlacementRequestRequestTypeDef](./type_defs.md#deleteplacementrequestrequesttypedef)
- [DeleteProjectRequestRequestTypeDef](./type_defs.md#deleteprojectrequestrequesttypedef)
- [DescribePlacementRequestRequestTypeDef](./type_defs.md#describeplacementrequestrequesttypedef)
- [DescribePlacementResponseTypeDef](./type_defs.md#describeplacementresponsetypedef)
- [DescribeProjectRequestRequestTypeDef](./type_defs.md#describeprojectrequestrequesttypedef)
- [DescribeProjectResponseTypeDef](./type_defs.md#describeprojectresponsetypedef)
- [DeviceTemplateTypeDef](./type_defs.md#devicetemplatetypedef)
- [DisassociateDeviceFromPlacementRequestRequestTypeDef](./type_defs.md#disassociatedevicefromplacementrequestrequesttypedef)
- [GetDevicesInPlacementRequestRequestTypeDef](./type_defs.md#getdevicesinplacementrequestrequesttypedef)
- [GetDevicesInPlacementResponseTypeDef](./type_defs.md#getdevicesinplacementresponsetypedef)
- [ListPlacementsRequestRequestTypeDef](./type_defs.md#listplacementsrequestrequesttypedef)
- [ListPlacementsResponseTypeDef](./type_defs.md#listplacementsresponsetypedef)
- [ListProjectsRequestRequestTypeDef](./type_defs.md#listprojectsrequestrequesttypedef)
- [ListProjectsResponseTypeDef](./type_defs.md#listprojectsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PlacementDescriptionTypeDef](./type_defs.md#placementdescriptiontypedef)
- [PlacementSummaryTypeDef](./type_defs.md#placementsummarytypedef)
- [PlacementTemplateTypeDef](./type_defs.md#placementtemplatetypedef)
- [ProjectDescriptionTypeDef](./type_defs.md#projectdescriptiontypedef)
- [ProjectSummaryTypeDef](./type_defs.md#projectsummarytypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdatePlacementRequestRequestTypeDef](./type_defs.md#updateplacementrequestrequesttypedef)
- [UpdateProjectRequestRequestTypeDef](./type_defs.md#updateprojectrequestrequesttypedef)
