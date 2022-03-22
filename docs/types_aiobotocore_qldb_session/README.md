<a id="type-annotations-for-aiobotocore-qldbsession-module"></a>

# Type annotations for aiobotocore QLDBSession module

> [Index](../README.md) > QLDBSession

Auto-generated documentation for
[QLDBSession](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb-session.html#QLDBSession)
type annotations stubs module
[types-aiobotocore-qldb-session](https://pypi.org/project/types-aiobotocore-qldb-session/).

- [Type annotations for aiobotocore QLDBSession module](#type-annotations-for-aiobotocore-qldbsession-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [QLDBSessionClient](#qldbsessionclient)
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

Click `Modify` and select `boto3 common` and `QLDBSession`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `QLDBSession` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[qldb-session]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[qldb-session]'


# standalone installation
python -m pip install types-aiobotocore-qldb-session
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-qldb-session
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="qldbsessionclient"></a>

## QLDBSessionClient

Type annotations for `session.create_client("qldb-session")` as
[QLDBSessionClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_qldb_session.client import QLDBSessionClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [send_command](./client.md#send_command)

<a id="exceptions"></a>

### Exceptions

QLDBSessionClient [exceptions](./client.md#exceptions)

- BadRequestException
- CapacityExceededException
- ClientError
- InvalidSessionException
- LimitExceededException
- OccConflictException
- RateExceededException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_qldb_session.literals import QLDBSessionServiceName, ...
```

- [QLDBSessionServiceName](./literals.md#qldbsessionservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_qldb_session.type_defs import AbortTransactionResultTypeDef, ...
```

- [AbortTransactionResultTypeDef](./type_defs.md#aborttransactionresulttypedef)
- [CommitTransactionRequestTypeDef](./type_defs.md#committransactionrequesttypedef)
- [CommitTransactionResultTypeDef](./type_defs.md#committransactionresulttypedef)
- [EndSessionResultTypeDef](./type_defs.md#endsessionresulttypedef)
- [ExecuteStatementRequestTypeDef](./type_defs.md#executestatementrequesttypedef)
- [ExecuteStatementResultTypeDef](./type_defs.md#executestatementresulttypedef)
- [FetchPageRequestTypeDef](./type_defs.md#fetchpagerequesttypedef)
- [FetchPageResultTypeDef](./type_defs.md#fetchpageresulttypedef)
- [IOUsageTypeDef](./type_defs.md#iousagetypedef)
- [PageTypeDef](./type_defs.md#pagetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SendCommandRequestRequestTypeDef](./type_defs.md#sendcommandrequestrequesttypedef)
- [SendCommandResultTypeDef](./type_defs.md#sendcommandresulttypedef)
- [StartSessionRequestTypeDef](./type_defs.md#startsessionrequesttypedef)
- [StartSessionResultTypeDef](./type_defs.md#startsessionresulttypedef)
- [StartTransactionResultTypeDef](./type_defs.md#starttransactionresulttypedef)
- [TimingInformationTypeDef](./type_defs.md#timinginformationtypedef)
- [ValueHolderTypeDef](./type_defs.md#valueholdertypedef)
