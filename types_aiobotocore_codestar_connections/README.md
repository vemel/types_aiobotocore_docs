<a id="type-annotations-for-aiobotocore-codestarconnections-module"></a>

# Type annotations for aiobotocore CodeStarconnections module

> [Index](..) > CodeStarconnections

Auto-generated documentation for
[CodeStarconnections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections)
type annotations stubs module
[types-aiobotocore-codestar-connections](https://pypi.org/project/types-aiobotocore-codestar-connections/).

- [Type annotations for aiobotocore CodeStarconnections module](#type-annotations-for-aiobotocore-codestarconnections-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [CodeStarconnectionsClient](#codestarconnectionsclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `CodeStarconnections`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `CodeStarconnections` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[codestar-connections]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[codestar-connections]'

# standalone installation
python -m pip install types-aiobotocore-codestar-connections
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-codestar-connections
```

<a id="codestarconnectionsclient"></a>

## CodeStarconnectionsClient

Type annotations for `session.create_client("codestar-connections")` as
[CodeStarconnectionsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_codestar_connections.client import CodeStarconnectionsClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [create_connection](./client.md#create_connection)
- [create_host](./client.md#create_host)
- [delete_connection](./client.md#delete_connection)
- [delete_host](./client.md#delete_host)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_connection](./client.md#get_connection)
- [get_host](./client.md#get_host)
- [list_connections](./client.md#list_connections)
- [list_hosts](./client.md#list_hosts)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_host](./client.md#update_host)

<a id="exceptions"></a>

### Exceptions

CodeStarconnectionsClient [exceptions](./client.md#exceptions)

- ClientError
- ConflictException
- LimitExceededException
- ResourceNotFoundException
- ResourceUnavailableException
- UnsupportedOperationException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_codestar_connections.literals import ConnectionStatusType, ...
```

- [ConnectionStatusType](./literals.md#connectionstatustype)
- [ProviderTypeType](./literals.md#providertypetype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_codestar_connections.type_defs import ConnectionTypeDef, ...
```

- [ConnectionTypeDef](./type_defs.md#connectiontypedef)
- [CreateConnectionInputRequestTypeDef](./type_defs.md#createconnectioninputrequesttypedef)
- [CreateConnectionOutputTypeDef](./type_defs.md#createconnectionoutputtypedef)
- [CreateHostInputRequestTypeDef](./type_defs.md#createhostinputrequesttypedef)
- [CreateHostOutputTypeDef](./type_defs.md#createhostoutputtypedef)
- [DeleteConnectionInputRequestTypeDef](./type_defs.md#deleteconnectioninputrequesttypedef)
- [DeleteHostInputRequestTypeDef](./type_defs.md#deletehostinputrequesttypedef)
- [GetConnectionInputRequestTypeDef](./type_defs.md#getconnectioninputrequesttypedef)
- [GetConnectionOutputTypeDef](./type_defs.md#getconnectionoutputtypedef)
- [GetHostInputRequestTypeDef](./type_defs.md#gethostinputrequesttypedef)
- [GetHostOutputTypeDef](./type_defs.md#gethostoutputtypedef)
- [HostTypeDef](./type_defs.md#hosttypedef)
- [ListConnectionsInputRequestTypeDef](./type_defs.md#listconnectionsinputrequesttypedef)
- [ListConnectionsOutputTypeDef](./type_defs.md#listconnectionsoutputtypedef)
- [ListHostsInputRequestTypeDef](./type_defs.md#listhostsinputrequesttypedef)
- [ListHostsOutputTypeDef](./type_defs.md#listhostsoutputtypedef)
- [ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef)
- [ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef)
- [UpdateHostInputRequestTypeDef](./type_defs.md#updatehostinputrequesttypedef)
- [VpcConfigurationTypeDef](./type_defs.md#vpcconfigurationtypedef)
