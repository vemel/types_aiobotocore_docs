<a id="type-annotations-for-aiobotocore-appregistry-module"></a>

# Type annotations for aiobotocore AppRegistry module

> [Index](../README.md) > AppRegistry

Auto-generated documentation for
[AppRegistry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry)
type annotations stubs module
[types-aiobotocore-servicecatalog-appregistry](https://pypi.org/project/types-aiobotocore-servicecatalog-appregistry/).

- [Type annotations for aiobotocore AppRegistry module](#type-annotations-for-aiobotocore-appregistry-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [AppRegistryClient](#appregistryclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `AppRegistry`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `AppRegistry` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[servicecatalog-appregistry]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[servicecatalog-appregistry]'


# standalone installation
python -m pip install types-aiobotocore-servicecatalog-appregistry
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-servicecatalog-appregistry
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="appregistryclient"></a>

## AppRegistryClient

Type annotations for `session.create_client("servicecatalog-appregistry")` as
[AppRegistryClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_servicecatalog_appregistry.client import AppRegistryClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [associate_attribute_group](./client.md#associate_attribute_group)
- [associate_resource](./client.md#associate_resource)
- [can_paginate](./client.md#can_paginate)
- [create_application](./client.md#create_application)
- [create_attribute_group](./client.md#create_attribute_group)
- [delete_application](./client.md#delete_application)
- [delete_attribute_group](./client.md#delete_attribute_group)
- [disassociate_attribute_group](./client.md#disassociate_attribute_group)
- [disassociate_resource](./client.md#disassociate_resource)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_application](./client.md#get_application)
- [get_associated_resource](./client.md#get_associated_resource)
- [get_attribute_group](./client.md#get_attribute_group)
- [get_paginator](./client.md#get_paginator)
- [list_applications](./client.md#list_applications)
- [list_associated_attribute_groups](./client.md#list_associated_attribute_groups)
- [list_associated_resources](./client.md#list_associated_resources)
- [list_attribute_groups](./client.md#list_attribute_groups)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [sync_resource](./client.md#sync_resource)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_application](./client.md#update_application)
- [update_attribute_group](./client.md#update_attribute_group)

<a id="exceptions"></a>

### Exceptions

AppRegistryClient [exceptions](./client.md#exceptions)

- ClientError
- ConflictException
- InternalServerException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("servicecatalog-appregistry").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_servicecatalog_appregistry.paginator import ListApplicationsPaginator, ...
```

- [ListApplicationsPaginator](./paginators.md#listapplicationspaginator)
- [ListAssociatedAttributeGroupsPaginator](./paginators.md#listassociatedattributegroupspaginator)
- [ListAssociatedResourcesPaginator](./paginators.md#listassociatedresourcespaginator)
- [ListAttributeGroupsPaginator](./paginators.md#listattributegroupspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_servicecatalog_appregistry.literals import ListApplicationsPaginatorName, ...
```

- [ListApplicationsPaginatorName](./literals.md#listapplicationspaginatorname)
- [ListAssociatedAttributeGroupsPaginatorName](./literals.md#listassociatedattributegroupspaginatorname)
- [ListAssociatedResourcesPaginatorName](./literals.md#listassociatedresourcespaginatorname)
- [ListAttributeGroupsPaginatorName](./literals.md#listattributegroupspaginatorname)
- [ResourceGroupStateType](./literals.md#resourcegroupstatetype)
- [ResourceTypeType](./literals.md#resourcetypetype)
- [SyncActionType](./literals.md#syncactiontype)
- [AppRegistryServiceName](./literals.md#appregistryservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_servicecatalog_appregistry.type_defs import ApplicationSummaryTypeDef, ...
```

- [ApplicationSummaryTypeDef](./type_defs.md#applicationsummarytypedef)
- [ApplicationTypeDef](./type_defs.md#applicationtypedef)
- [AssociateAttributeGroupRequestRequestTypeDef](./type_defs.md#associateattributegrouprequestrequesttypedef)
- [AssociateAttributeGroupResponseTypeDef](./type_defs.md#associateattributegroupresponsetypedef)
- [AssociateResourceRequestRequestTypeDef](./type_defs.md#associateresourcerequestrequesttypedef)
- [AssociateResourceResponseTypeDef](./type_defs.md#associateresourceresponsetypedef)
- [AttributeGroupSummaryTypeDef](./type_defs.md#attributegroupsummarytypedef)
- [AttributeGroupTypeDef](./type_defs.md#attributegrouptypedef)
- [CreateApplicationRequestRequestTypeDef](./type_defs.md#createapplicationrequestrequesttypedef)
- [CreateApplicationResponseTypeDef](./type_defs.md#createapplicationresponsetypedef)
- [CreateAttributeGroupRequestRequestTypeDef](./type_defs.md#createattributegrouprequestrequesttypedef)
- [CreateAttributeGroupResponseTypeDef](./type_defs.md#createattributegroupresponsetypedef)
- [DeleteApplicationRequestRequestTypeDef](./type_defs.md#deleteapplicationrequestrequesttypedef)
- [DeleteApplicationResponseTypeDef](./type_defs.md#deleteapplicationresponsetypedef)
- [DeleteAttributeGroupRequestRequestTypeDef](./type_defs.md#deleteattributegrouprequestrequesttypedef)
- [DeleteAttributeGroupResponseTypeDef](./type_defs.md#deleteattributegroupresponsetypedef)
- [DisassociateAttributeGroupRequestRequestTypeDef](./type_defs.md#disassociateattributegrouprequestrequesttypedef)
- [DisassociateAttributeGroupResponseTypeDef](./type_defs.md#disassociateattributegroupresponsetypedef)
- [DisassociateResourceRequestRequestTypeDef](./type_defs.md#disassociateresourcerequestrequesttypedef)
- [DisassociateResourceResponseTypeDef](./type_defs.md#disassociateresourceresponsetypedef)
- [GetApplicationRequestRequestTypeDef](./type_defs.md#getapplicationrequestrequesttypedef)
- [GetApplicationResponseTypeDef](./type_defs.md#getapplicationresponsetypedef)
- [GetAssociatedResourceRequestRequestTypeDef](./type_defs.md#getassociatedresourcerequestrequesttypedef)
- [GetAssociatedResourceResponseTypeDef](./type_defs.md#getassociatedresourceresponsetypedef)
- [GetAttributeGroupRequestRequestTypeDef](./type_defs.md#getattributegrouprequestrequesttypedef)
- [GetAttributeGroupResponseTypeDef](./type_defs.md#getattributegroupresponsetypedef)
- [IntegrationsTypeDef](./type_defs.md#integrationstypedef)
- [ListApplicationsRequestRequestTypeDef](./type_defs.md#listapplicationsrequestrequesttypedef)
- [ListApplicationsResponseTypeDef](./type_defs.md#listapplicationsresponsetypedef)
- [ListAssociatedAttributeGroupsRequestRequestTypeDef](./type_defs.md#listassociatedattributegroupsrequestrequesttypedef)
- [ListAssociatedAttributeGroupsResponseTypeDef](./type_defs.md#listassociatedattributegroupsresponsetypedef)
- [ListAssociatedResourcesRequestRequestTypeDef](./type_defs.md#listassociatedresourcesrequestrequesttypedef)
- [ListAssociatedResourcesResponseTypeDef](./type_defs.md#listassociatedresourcesresponsetypedef)
- [ListAttributeGroupsRequestRequestTypeDef](./type_defs.md#listattributegroupsrequestrequesttypedef)
- [ListAttributeGroupsResponseTypeDef](./type_defs.md#listattributegroupsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResourceGroupTypeDef](./type_defs.md#resourcegrouptypedef)
- [ResourceInfoTypeDef](./type_defs.md#resourceinfotypedef)
- [ResourceIntegrationsTypeDef](./type_defs.md#resourceintegrationstypedef)
- [ResourceTypeDef](./type_defs.md#resourcetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SyncResourceRequestRequestTypeDef](./type_defs.md#syncresourcerequestrequesttypedef)
- [SyncResourceResponseTypeDef](./type_defs.md#syncresourceresponsetypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateApplicationRequestRequestTypeDef](./type_defs.md#updateapplicationrequestrequesttypedef)
- [UpdateApplicationResponseTypeDef](./type_defs.md#updateapplicationresponsetypedef)
- [UpdateAttributeGroupRequestRequestTypeDef](./type_defs.md#updateattributegrouprequestrequesttypedef)
- [UpdateAttributeGroupResponseTypeDef](./type_defs.md#updateattributegroupresponsetypedef)
