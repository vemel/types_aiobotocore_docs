# SimpleDB module

> [Index](../README.md) > SimpleDB


!!! note ""

    Auto-generated documentation for [SimpleDB](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
    type annotations stubs module [types-aiobotocore-sdb](https://pypi.org/project/types-aiobotocore-sdb/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `SimpleDB`.

### From PyPI with pip

Install `types-aiobotocore` for `SimpleDB` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[sdb]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[sdb]'


# standalone installation
python -m pip install types-aiobotocore-sdb
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-sdb
```

## Usage

Code samples can be found in [Examples](./usage.md).

## SimpleDBClient

Type annotations and code completion for  `#!python session.create_client("sdb")` as [SimpleDBClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_sdb.client import SimpleDBClient


session = get_session()
async with session.create_client("sdb") as client:
    client: SimpleDBClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("sdb").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_sdb.paginator import ListDomainsPaginator

def get_list_domains_paginator() -> ListDomainsPaginator:
    return client.get_paginator("list_domains"))
```

- [ListDomainsPaginator](./paginators.md#listdomainspaginator)
- [SelectPaginator](./paginators.md#selectpaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_sdb.literals import ListDomainsPaginatorName

def get_value() -> ListDomainsPaginatorName:
    return "list_domains"
```

- [ListDomainsPaginatorName](./literals.md#listdomainspaginatorname)
- [SelectPaginatorName](./literals.md#selectpaginatorname)
- [SimpleDBServiceName](./literals.md#simpledbservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_sdb.type_defs import AttributeTypeDef

def get_value() -> AttributeTypeDef:
    return {
        "Name": ...,
        "Value": ...,
    }
```

- [AttributeTypeDef](./type_defs.md#attributetypedef)
- [BatchDeleteAttributesRequestRequestTypeDef](./type_defs.md#batchdeleteattributesrequestrequesttypedef)
- [BatchPutAttributesRequestRequestTypeDef](./type_defs.md#batchputattributesrequestrequesttypedef)
- [CreateDomainRequestRequestTypeDef](./type_defs.md#createdomainrequestrequesttypedef)
- [DeletableItemTypeDef](./type_defs.md#deletableitemtypedef)
- [DeleteAttributesRequestRequestTypeDef](./type_defs.md#deleteattributesrequestrequesttypedef)
- [DeleteDomainRequestRequestTypeDef](./type_defs.md#deletedomainrequestrequesttypedef)
- [DomainMetadataRequestRequestTypeDef](./type_defs.md#domainmetadatarequestrequesttypedef)
- [DomainMetadataResultTypeDef](./type_defs.md#domainmetadataresulttypedef)
- [GetAttributesRequestRequestTypeDef](./type_defs.md#getattributesrequestrequesttypedef)
- [GetAttributesResultTypeDef](./type_defs.md#getattributesresulttypedef)
- [ItemTypeDef](./type_defs.md#itemtypedef)
- [ListDomainsRequestListDomainsPaginateTypeDef](./type_defs.md#listdomainsrequestlistdomainspaginatetypedef)
- [ListDomainsRequestRequestTypeDef](./type_defs.md#listdomainsrequestrequesttypedef)
- [ListDomainsResultTypeDef](./type_defs.md#listdomainsresulttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PutAttributesRequestRequestTypeDef](./type_defs.md#putattributesrequestrequesttypedef)
- [ReplaceableAttributeTypeDef](./type_defs.md#replaceableattributetypedef)
- [ReplaceableItemTypeDef](./type_defs.md#replaceableitemtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SelectRequestRequestTypeDef](./type_defs.md#selectrequestrequesttypedef)
- [SelectRequestSelectPaginateTypeDef](./type_defs.md#selectrequestselectpaginatetypedef)
- [SelectResultTypeDef](./type_defs.md#selectresulttypedef)
- [UpdateConditionTypeDef](./type_defs.md#updateconditiontypedef)

