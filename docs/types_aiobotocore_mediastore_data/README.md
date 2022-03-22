<a id="type-annotations-for-aiobotocore-mediastoredata-module"></a>

# Type annotations for aiobotocore MediaStoreData module

> [Index](../README.md) > MediaStoreData

Auto-generated documentation for
[MediaStoreData](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData)
type annotations stubs module
[types-aiobotocore-mediastore-data](https://pypi.org/project/types-aiobotocore-mediastore-data/).

- [Type annotations for aiobotocore MediaStoreData module](#type-annotations-for-aiobotocore-mediastoredata-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [MediaStoreDataClient](#mediastoredataclient)
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

Click `Modify` and select `boto3 common` and `MediaStoreData`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `MediaStoreData` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[mediastore-data]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[mediastore-data]'


# standalone installation
python -m pip install types-aiobotocore-mediastore-data
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-mediastore-data
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="mediastoredataclient"></a>

## MediaStoreDataClient

Type annotations for `session.create_client("mediastore-data")` as
[MediaStoreDataClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_mediastore_data.client import MediaStoreDataClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [delete_object](./client.md#delete_object)
- [describe_object](./client.md#describe_object)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_object](./client.md#get_object)
- [get_paginator](./client.md#get_paginator)
- [list_items](./client.md#list_items)
- [put_object](./client.md#put_object)

<a id="exceptions"></a>

### Exceptions

MediaStoreDataClient [exceptions](./client.md#exceptions)

- ClientError
- ContainerNotFoundException
- InternalServerError
- ObjectNotFoundException
- RequestedRangeNotSatisfiableException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("mediastore-data").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_mediastore_data.paginator import ListItemsPaginator, ...
```

- [ListItemsPaginator](./paginators.md#listitemspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_mediastore_data.literals import ItemTypeType, ...
```

- [ItemTypeType](./literals.md#itemtypetype)
- [ListItemsPaginatorName](./literals.md#listitemspaginatorname)
- [StorageClassType](./literals.md#storageclasstype)
- [UploadAvailabilityType](./literals.md#uploadavailabilitytype)
- [MediaStoreDataServiceName](./literals.md#mediastoredataservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_mediastore_data.type_defs import DeleteObjectRequestRequestTypeDef, ...
```

- [DeleteObjectRequestRequestTypeDef](./type_defs.md#deleteobjectrequestrequesttypedef)
- [DescribeObjectRequestRequestTypeDef](./type_defs.md#describeobjectrequestrequesttypedef)
- [DescribeObjectResponseTypeDef](./type_defs.md#describeobjectresponsetypedef)
- [GetObjectRequestRequestTypeDef](./type_defs.md#getobjectrequestrequesttypedef)
- [GetObjectResponseTypeDef](./type_defs.md#getobjectresponsetypedef)
- [ItemTypeDef](./type_defs.md#itemtypedef)
- [ListItemsRequestRequestTypeDef](./type_defs.md#listitemsrequestrequesttypedef)
- [ListItemsResponseTypeDef](./type_defs.md#listitemsresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PutObjectRequestRequestTypeDef](./type_defs.md#putobjectrequestrequesttypedef)
- [PutObjectResponseTypeDef](./type_defs.md#putobjectresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
