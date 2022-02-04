<a id="typed-dictionaries-for-aiobotocore-simpledb-module"></a>

# Typed dictionaries for aiobotocore SimpleDB module

> [Index](..) > [SimpleDB](.) > Typed dictionaries

Auto-generated documentation for
[SimpleDB](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
type annotations stubs module
[types-aiobotocore-sdb](https://pypi.org/project/types-aiobotocore-sdb/).

- [Typed dictionaries for aiobotocore SimpleDB module](#typed-dictionaries-for-aiobotocore-simpledb-module)
  - [AttributeTypeDef](#attributetypedef)
  - [BatchDeleteAttributesRequestRequestTypeDef](#batchdeleteattributesrequestrequesttypedef)
  - [BatchPutAttributesRequestRequestTypeDef](#batchputattributesrequestrequesttypedef)
  - [CreateDomainRequestRequestTypeDef](#createdomainrequestrequesttypedef)
  - [DeletableItemTypeDef](#deletableitemtypedef)
  - [DeleteAttributesRequestRequestTypeDef](#deleteattributesrequestrequesttypedef)
  - [DeleteDomainRequestRequestTypeDef](#deletedomainrequestrequesttypedef)
  - [DomainMetadataRequestRequestTypeDef](#domainmetadatarequestrequesttypedef)
  - [DomainMetadataResultTypeDef](#domainmetadataresulttypedef)
  - [GetAttributesRequestRequestTypeDef](#getattributesrequestrequesttypedef)
  - [GetAttributesResultTypeDef](#getattributesresulttypedef)
  - [ItemTypeDef](#itemtypedef)
  - [ListDomainsRequestRequestTypeDef](#listdomainsrequestrequesttypedef)
  - [ListDomainsResultTypeDef](#listdomainsresulttypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PutAttributesRequestRequestTypeDef](#putattributesrequestrequesttypedef)
  - [ReplaceableAttributeTypeDef](#replaceableattributetypedef)
  - [ReplaceableItemTypeDef](#replaceableitemtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SelectRequestRequestTypeDef](#selectrequestrequesttypedef)
  - [SelectResultTypeDef](#selectresulttypedef)
  - [UpdateConditionTypeDef](#updateconditiontypedef)

<a id="attributetypedef"></a>

## AttributeTypeDef

```python
from types_aiobotocore_sdb.type_defs import AttributeTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

Optional fields:

- `AlternateNameEncoding`: `str`
- `AlternateValueEncoding`: `str`

<a id="batchdeleteattributesrequestrequesttypedef"></a>

## BatchDeleteAttributesRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import BatchDeleteAttributesRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`
- `Items`:
  `Sequence`\[[DeletableItemTypeDef](./type_defs.md#deletableitemtypedef)\]

<a id="batchputattributesrequestrequesttypedef"></a>

## BatchPutAttributesRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import BatchPutAttributesRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`
- `Items`:
  `Sequence`\[[ReplaceableItemTypeDef](./type_defs.md#replaceableitemtypedef)\]

<a id="createdomainrequestrequesttypedef"></a>

## CreateDomainRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import CreateDomainRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`

<a id="deletableitemtypedef"></a>

## DeletableItemTypeDef

```python
from types_aiobotocore_sdb.type_defs import DeletableItemTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Attributes`:
  `Sequence`\[[AttributeTypeDef](./type_defs.md#attributetypedef)\]

<a id="deleteattributesrequestrequesttypedef"></a>

## DeleteAttributesRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import DeleteAttributesRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`
- `ItemName`: `str`

Optional fields:

- `Attributes`:
  `Sequence`\[[AttributeTypeDef](./type_defs.md#attributetypedef)\]
- `Expected`: [UpdateConditionTypeDef](./type_defs.md#updateconditiontypedef)

<a id="deletedomainrequestrequesttypedef"></a>

## DeleteDomainRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import DeleteDomainRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`

<a id="domainmetadatarequestrequesttypedef"></a>

## DomainMetadataRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import DomainMetadataRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`

<a id="domainmetadataresulttypedef"></a>

## DomainMetadataResultTypeDef

```python
from types_aiobotocore_sdb.type_defs import DomainMetadataResultTypeDef
```

Required fields:

- `ItemCount`: `int`
- `ItemNamesSizeBytes`: `int`
- `AttributeNameCount`: `int`
- `AttributeNamesSizeBytes`: `int`
- `AttributeValueCount`: `int`
- `AttributeValuesSizeBytes`: `int`
- `Timestamp`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getattributesrequestrequesttypedef"></a>

## GetAttributesRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import GetAttributesRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`
- `ItemName`: `str`

Optional fields:

- `AttributeNames`: `Sequence`\[`str`\]
- `ConsistentRead`: `bool`

<a id="getattributesresulttypedef"></a>

## GetAttributesResultTypeDef

```python
from types_aiobotocore_sdb.type_defs import GetAttributesResultTypeDef
```

Required fields:

- `Attributes`: `List`\[[AttributeTypeDef](./type_defs.md#attributetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="itemtypedef"></a>

## ItemTypeDef

```python
from types_aiobotocore_sdb.type_defs import ItemTypeDef
```

Required fields:

- `Name`: `str`
- `Attributes`: `List`\[[AttributeTypeDef](./type_defs.md#attributetypedef)\]

Optional fields:

- `AlternateNameEncoding`: `str`

<a id="listdomainsrequestrequesttypedef"></a>

## ListDomainsRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import ListDomainsRequestRequestTypeDef
```

Optional fields:

- `MaxNumberOfDomains`: `int`
- `NextToken`: `str`

<a id="listdomainsresulttypedef"></a>

## ListDomainsResultTypeDef

```python
from types_aiobotocore_sdb.type_defs import ListDomainsResultTypeDef
```

Required fields:

- `DomainNames`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_sdb.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="putattributesrequestrequesttypedef"></a>

## PutAttributesRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import PutAttributesRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`
- `ItemName`: `str`
- `Attributes`:
  `Sequence`\[[ReplaceableAttributeTypeDef](./type_defs.md#replaceableattributetypedef)\]

Optional fields:

- `Expected`: [UpdateConditionTypeDef](./type_defs.md#updateconditiontypedef)

<a id="replaceableattributetypedef"></a>

## ReplaceableAttributeTypeDef

```python
from types_aiobotocore_sdb.type_defs import ReplaceableAttributeTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

Optional fields:

- `Replace`: `bool`

<a id="replaceableitemtypedef"></a>

## ReplaceableItemTypeDef

```python
from types_aiobotocore_sdb.type_defs import ReplaceableItemTypeDef
```

Required fields:

- `Name`: `str`
- `Attributes`:
  `Sequence`\[[ReplaceableAttributeTypeDef](./type_defs.md#replaceableattributetypedef)\]

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_sdb.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="selectrequestrequesttypedef"></a>

## SelectRequestRequestTypeDef

```python
from types_aiobotocore_sdb.type_defs import SelectRequestRequestTypeDef
```

Required fields:

- `SelectExpression`: `str`

Optional fields:

- `NextToken`: `str`
- `ConsistentRead`: `bool`

<a id="selectresulttypedef"></a>

## SelectResultTypeDef

```python
from types_aiobotocore_sdb.type_defs import SelectResultTypeDef
```

Required fields:

- `Items`: `List`\[[ItemTypeDef](./type_defs.md#itemtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateconditiontypedef"></a>

## UpdateConditionTypeDef

```python
from types_aiobotocore_sdb.type_defs import UpdateConditionTypeDef
```

Optional fields:

- `Name`: `str`
- `Value`: `str`
- `Exists`: `bool`
