<a id="type-annotations-for-aiobotocore-qldbsession-module"></a>

# Type annotations for aiobotocore QLDBSession module

> [Index](..) > QLDBSession

Auto-generated documentation for
[QLDBSession](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb-session.html#QLDBSession)
type annotations stubs module
[types-aiobotocore-qldb-session](https://pypi.org/project/types-aiobotocore-qldb-session/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[qldb-session]'

# install as a standalone
pip install types-aiobotocore-qldb-session
```

- [Type annotations for aiobotocore QLDBSession module](#type-annotations-for-aiobotocore-qldbsession-module)
  - [QLDBSessionClient](#qldbsessionclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="qldbsessionclient"></a>

## QLDBSessionClient

Type annotations for `aiobotocore.create_client("qldb-session")` as
[QLDBSessionClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_qldb_session.client import QLDBSessionClient
```

<a id="methods"></a>

### Methods

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
from types_aiobotocore_qldb_session.literals import ServiceName, ...
```

- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_qldb_session.type_defs import AbortTransactionResultTypeDef, ...
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
