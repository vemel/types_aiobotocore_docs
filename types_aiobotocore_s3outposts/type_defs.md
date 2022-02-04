<a id="typed-dictionaries-for-aiobotocore-s3outposts-module"></a>

# Typed dictionaries for aiobotocore S3Outposts module

> [Index](..) > [S3Outposts](.) > Typed dictionaries

Auto-generated documentation for
[S3Outposts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
type annotations stubs module
[types-aiobotocore-s3outposts](https://pypi.org/project/types-aiobotocore-s3outposts/).

- [Typed dictionaries for aiobotocore S3Outposts module](#typed-dictionaries-for-aiobotocore-s3outposts-module)
  - [CreateEndpointRequestRequestTypeDef](#createendpointrequestrequesttypedef)
  - [CreateEndpointResultTypeDef](#createendpointresulttypedef)
  - [DeleteEndpointRequestRequestTypeDef](#deleteendpointrequestrequesttypedef)
  - [EndpointTypeDef](#endpointtypedef)
  - [ListEndpointsRequestRequestTypeDef](#listendpointsrequestrequesttypedef)
  - [ListEndpointsResultTypeDef](#listendpointsresulttypedef)
  - [NetworkInterfaceTypeDef](#networkinterfacetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)

<a id="createendpointrequestrequesttypedef"></a>

## CreateEndpointRequestRequestTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import CreateEndpointRequestRequestTypeDef
```

Required fields:

- `OutpostId`: `str`
- `SubnetId`: `str`
- `SecurityGroupId`: `str`

Optional fields:

- `AccessType`: [EndpointAccessTypeType](./literals.md#endpointaccesstypetype)
- `CustomerOwnedIpv4Pool`: `str`

<a id="createendpointresulttypedef"></a>

## CreateEndpointResultTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import CreateEndpointResultTypeDef
```

Required fields:

- `EndpointArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteendpointrequestrequesttypedef"></a>

## DeleteEndpointRequestRequestTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import DeleteEndpointRequestRequestTypeDef
```

Required fields:

- `EndpointId`: `str`
- `OutpostId`: `str`

<a id="endpointtypedef"></a>

## EndpointTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import EndpointTypeDef
```

Optional fields:

- `EndpointArn`: `str`
- `OutpostsId`: `str`
- `CidrBlock`: `str`
- `Status`: [EndpointStatusType](./literals.md#endpointstatustype)
- `CreationTime`: `datetime`
- `NetworkInterfaces`:
  `List`\[[NetworkInterfaceTypeDef](./type_defs.md#networkinterfacetypedef)\]
- `VpcId`: `str`
- `SubnetId`: `str`
- `SecurityGroupId`: `str`
- `AccessType`: [EndpointAccessTypeType](./literals.md#endpointaccesstypetype)
- `CustomerOwnedIpv4Pool`: `str`

<a id="listendpointsrequestrequesttypedef"></a>

## ListEndpointsRequestRequestTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import ListEndpointsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listendpointsresulttypedef"></a>

## ListEndpointsResultTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import ListEndpointsResultTypeDef
```

Required fields:

- `Endpoints`: `List`\[[EndpointTypeDef](./type_defs.md#endpointtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="networkinterfacetypedef"></a>

## NetworkInterfaceTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import NetworkInterfaceTypeDef
```

Optional fields:

- `NetworkInterfaceId`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_s3outposts.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`
