<a id="type-annotations-for-aiobotocore-marketplacecatalog-module"></a>

# Type annotations for aiobotocore MarketplaceCatalog module

> [Index](..) > MarketplaceCatalog

Auto-generated documentation for
[MarketplaceCatalog](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog)
type annotations stubs module
[types-aiobotocore-marketplace-catalog](https://pypi.org/project/types-aiobotocore-marketplace-catalog/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[marketplace-catalog]'

# install as a standalone
pip install types-aiobotocore-marketplace-catalog
```

- [Type annotations for aiobotocore MarketplaceCatalog module](#type-annotations-for-aiobotocore-marketplacecatalog-module)
  - [MarketplaceCatalogClient](#marketplacecatalogclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="marketplacecatalogclient"></a>

## MarketplaceCatalogClient

Type annotations for `aiobotocore.create_client("marketplace-catalog")` as
[MarketplaceCatalogClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_marketplace_catalog.client import MarketplaceCatalogClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [cancel_change_set](./client.md#cancel_change_set)
- [describe_change_set](./client.md#describe_change_set)
- [describe_entity](./client.md#describe_entity)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [list_change_sets](./client.md#list_change_sets)
- [list_entities](./client.md#list_entities)
- [start_change_set](./client.md#start_change_set)

<a id="exceptions"></a>

### Exceptions

MarketplaceCatalogClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- InternalServiceException
- ResourceInUseException
- ResourceNotFoundException
- ResourceNotSupportedException
- ServiceQuotaExceededException
- ThrottlingException
- ValidationException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_marketplace_catalog.literals import ChangeStatusType, ...
```

- [ChangeStatusType](./literals.md#changestatustype)
- [FailureCodeType](./literals.md#failurecodetype)
- [SortOrderType](./literals.md#sortordertype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_marketplace_catalog.type_defs import CancelChangeSetRequestRequestTypeDef, ...
```

- [CancelChangeSetRequestRequestTypeDef](./type_defs.md#cancelchangesetrequestrequesttypedef)
- [CancelChangeSetResponseTypeDef](./type_defs.md#cancelchangesetresponsetypedef)
- [ChangeSetSummaryListItemTypeDef](./type_defs.md#changesetsummarylistitemtypedef)
- [ChangeSummaryTypeDef](./type_defs.md#changesummarytypedef)
- [ChangeTypeDef](./type_defs.md#changetypedef)
- [DescribeChangeSetRequestRequestTypeDef](./type_defs.md#describechangesetrequestrequesttypedef)
- [DescribeChangeSetResponseTypeDef](./type_defs.md#describechangesetresponsetypedef)
- [DescribeEntityRequestRequestTypeDef](./type_defs.md#describeentityrequestrequesttypedef)
- [DescribeEntityResponseTypeDef](./type_defs.md#describeentityresponsetypedef)
- [EntitySummaryTypeDef](./type_defs.md#entitysummarytypedef)
- [EntityTypeDef](./type_defs.md#entitytypedef)
- [ErrorDetailTypeDef](./type_defs.md#errordetailtypedef)
- [FilterTypeDef](./type_defs.md#filtertypedef)
- [ListChangeSetsRequestRequestTypeDef](./type_defs.md#listchangesetsrequestrequesttypedef)
- [ListChangeSetsResponseTypeDef](./type_defs.md#listchangesetsresponsetypedef)
- [ListEntitiesRequestRequestTypeDef](./type_defs.md#listentitiesrequestrequesttypedef)
- [ListEntitiesResponseTypeDef](./type_defs.md#listentitiesresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SortTypeDef](./type_defs.md#sorttypedef)
- [StartChangeSetRequestRequestTypeDef](./type_defs.md#startchangesetrequestrequesttypedef)
- [StartChangeSetResponseTypeDef](./type_defs.md#startchangesetresponsetypedef)
