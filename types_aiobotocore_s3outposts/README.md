<a id="type-annotations-for-aiobotocore-s3outposts-module"></a>

# Type annotations for aiobotocore S3Outposts module

> [Index](..) > S3Outposts

Auto-generated documentation for
[S3Outposts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
type annotations stubs module
[types-aiobotocore-s3outposts](https://pypi.org/project/types-aiobotocore-s3outposts/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[s3outposts]'

# install as a standalone
pip install types-aiobotocore-s3outposts
```

- [Type annotations for aiobotocore S3Outposts module](#type-annotations-for-aiobotocore-s3outposts-module)
  - [S3OutpostsClient](#s3outpostsclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="s3outpostsclient"></a>

## S3OutpostsClient

Type annotations for `aiobotocore.create_client("s3outposts")` as
[S3OutpostsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_s3outposts.client import S3OutpostsClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_endpoint](./client.md#create_endpoint)
- [delete_endpoint](./client.md#delete_endpoint)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [list_endpoints](./client.md#list_endpoints)

<a id="exceptions"></a>

### Exceptions

S3OutpostsClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- ConflictException
- InternalServerException
- ResourceNotFoundException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("s3outposts").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_s3outposts.paginators import ListEndpointsPaginator, ...
```

- [ListEndpointsPaginator](./paginators.md#listendpointspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_s3outposts.literals import EndpointAccessTypeType, ...
```

- [EndpointAccessTypeType](./literals.md#endpointaccesstypetype)
- [EndpointStatusType](./literals.md#endpointstatustype)
- [ListEndpointsPaginatorName](./literals.md#listendpointspaginatorname)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_s3outposts.type_defs import CreateEndpointRequestRequestTypeDef, ...
```

- [CreateEndpointRequestRequestTypeDef](./type_defs.md#createendpointrequestrequesttypedef)
- [CreateEndpointResultTypeDef](./type_defs.md#createendpointresulttypedef)
- [DeleteEndpointRequestRequestTypeDef](./type_defs.md#deleteendpointrequestrequesttypedef)
- [EndpointTypeDef](./type_defs.md#endpointtypedef)
- [ListEndpointsRequestRequestTypeDef](./type_defs.md#listendpointsrequestrequesttypedef)
- [ListEndpointsResultTypeDef](./type_defs.md#listendpointsresulttypedef)
- [NetworkInterfaceTypeDef](./type_defs.md#networkinterfacetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
