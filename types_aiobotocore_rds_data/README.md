<a id="type-annotations-for-aiobotocore-rdsdataservice-module"></a>

# Type annotations for aiobotocore RDSDataService module

> [Index](..) > RDSDataService

Auto-generated documentation for
[RDSDataService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService)
type annotations stubs module
[types-aiobotocore-rds-data](https://pypi.org/project/types-aiobotocore-rds-data/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[rds-data]'

# install as a standalone
pip install types-aiobotocore-rds-data
```

- [Type annotations for aiobotocore RDSDataService module](#type-annotations-for-aiobotocore-rdsdataservice-module)
  - [RDSDataServiceClient](#rdsdataserviceclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="rdsdataserviceclient"></a>

## RDSDataServiceClient

Type annotations for `aiobotocore.create_client("rds-data")` as
[RDSDataServiceClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_rds_data.client import RDSDataServiceClient
```

<a id="methods"></a>

### Methods

- [batch_execute_statement](./client.md#batch_execute_statement)
- [begin_transaction](./client.md#begin_transaction)
- [can_paginate](./client.md#can_paginate)
- [commit_transaction](./client.md#commit_transaction)
- [exceptions](./client.md#exceptions)
- [execute_sql](./client.md#execute_sql)
- [execute_statement](./client.md#execute_statement)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [rollback_transaction](./client.md#rollback_transaction)

<a id="exceptions"></a>

### Exceptions

RDSDataServiceClient [exceptions](./client.md#exceptions)

- BadRequestException
- ClientError
- ForbiddenException
- InternalServerErrorException
- NotFoundException
- ServiceUnavailableError
- StatementTimeoutException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_rds_data.literals import DecimalReturnTypeType, ...
```

- [DecimalReturnTypeType](./literals.md#decimalreturntypetype)
- [TypeHintType](./literals.md#typehinttype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_rds_data.type_defs import ArrayValueTypeDef, ...
```

- [ArrayValueTypeDef](./type_defs.md#arrayvaluetypedef)
- [BatchExecuteStatementRequestRequestTypeDef](./type_defs.md#batchexecutestatementrequestrequesttypedef)
- [BatchExecuteStatementResponseTypeDef](./type_defs.md#batchexecutestatementresponsetypedef)
- [BeginTransactionRequestRequestTypeDef](./type_defs.md#begintransactionrequestrequesttypedef)
- [BeginTransactionResponseTypeDef](./type_defs.md#begintransactionresponsetypedef)
- [ColumnMetadataTypeDef](./type_defs.md#columnmetadatatypedef)
- [CommitTransactionRequestRequestTypeDef](./type_defs.md#committransactionrequestrequesttypedef)
- [CommitTransactionResponseTypeDef](./type_defs.md#committransactionresponsetypedef)
- [ExecuteSqlRequestRequestTypeDef](./type_defs.md#executesqlrequestrequesttypedef)
- [ExecuteSqlResponseTypeDef](./type_defs.md#executesqlresponsetypedef)
- [ExecuteStatementRequestRequestTypeDef](./type_defs.md#executestatementrequestrequesttypedef)
- [ExecuteStatementResponseTypeDef](./type_defs.md#executestatementresponsetypedef)
- [FieldTypeDef](./type_defs.md#fieldtypedef)
- [RecordTypeDef](./type_defs.md#recordtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ResultFrameTypeDef](./type_defs.md#resultframetypedef)
- [ResultSetMetadataTypeDef](./type_defs.md#resultsetmetadatatypedef)
- [ResultSetOptionsTypeDef](./type_defs.md#resultsetoptionstypedef)
- [RollbackTransactionRequestRequestTypeDef](./type_defs.md#rollbacktransactionrequestrequesttypedef)
- [RollbackTransactionResponseTypeDef](./type_defs.md#rollbacktransactionresponsetypedef)
- [SqlParameterTypeDef](./type_defs.md#sqlparametertypedef)
- [SqlStatementResultTypeDef](./type_defs.md#sqlstatementresulttypedef)
- [StructValueTypeDef](./type_defs.md#structvaluetypedef)
- [UpdateResultTypeDef](./type_defs.md#updateresulttypedef)
- [ValueTypeDef](./type_defs.md#valuetypedef)
