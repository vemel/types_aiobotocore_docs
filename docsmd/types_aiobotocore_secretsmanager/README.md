# SecretsManager module

> [Index](../README.md) > SecretsManager


!!! note ""

    Auto-generated documentation for [SecretsManager](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
    type annotations stubs module [types-aiobotocore-secretsmanager](https://pypi.org/project/types-aiobotocore-secretsmanager/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `SecretsManager`.

### From PyPI with pip

Install `types-aiobotocore` for `SecretsManager` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[secretsmanager]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[secretsmanager]'


# standalone installation
python -m pip install types-aiobotocore-secretsmanager
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-secretsmanager
```

## Usage

Code samples can be found in [Examples](./usage.md).

## SecretsManagerClient

Type annotations and code completion for  `#!python session.create_client("secretsmanager")` as [SecretsManagerClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_secretsmanager.client import SecretsManagerClient


session = get_session()
async with session.create_client("secretsmanager") as client:
    client: SecretsManagerClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("secretsmanager").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_secretsmanager.paginator import ListSecretsPaginator

def get_list_secrets_paginator() -> ListSecretsPaginator:
    return client.get_paginator("list_secrets"))
```

- [ListSecretsPaginator](./paginators.md#listsecretspaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_secretsmanager.literals import FilterNameStringTypeType

def get_value() -> FilterNameStringTypeType:
    return "all"
```

- [FilterNameStringTypeType](./literals.md#filternamestringtypetype)
- [ListSecretsPaginatorName](./literals.md#listsecretspaginatorname)
- [SortOrderTypeType](./literals.md#sortordertypetype)
- [StatusTypeType](./literals.md#statustypetype)
- [SecretsManagerServiceName](./literals.md#secretsmanagerservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_secretsmanager.type_defs import CancelRotateSecretRequestRequestTypeDef

def get_value() -> CancelRotateSecretRequestRequestTypeDef:
    return {
        "SecretId": ...,
    }
```

- [CancelRotateSecretRequestRequestTypeDef](./type_defs.md#cancelrotatesecretrequestrequesttypedef)
- [CancelRotateSecretResponseTypeDef](./type_defs.md#cancelrotatesecretresponsetypedef)
- [CreateSecretRequestRequestTypeDef](./type_defs.md#createsecretrequestrequesttypedef)
- [CreateSecretResponseTypeDef](./type_defs.md#createsecretresponsetypedef)
- [DeleteResourcePolicyRequestRequestTypeDef](./type_defs.md#deleteresourcepolicyrequestrequesttypedef)
- [DeleteResourcePolicyResponseTypeDef](./type_defs.md#deleteresourcepolicyresponsetypedef)
- [DeleteSecretRequestRequestTypeDef](./type_defs.md#deletesecretrequestrequesttypedef)
- [DeleteSecretResponseTypeDef](./type_defs.md#deletesecretresponsetypedef)
- [DescribeSecretRequestRequestTypeDef](./type_defs.md#describesecretrequestrequesttypedef)
- [DescribeSecretResponseTypeDef](./type_defs.md#describesecretresponsetypedef)
- [FilterTypeDef](./type_defs.md#filtertypedef)
- [GetRandomPasswordRequestRequestTypeDef](./type_defs.md#getrandompasswordrequestrequesttypedef)
- [GetRandomPasswordResponseTypeDef](./type_defs.md#getrandompasswordresponsetypedef)
- [GetResourcePolicyRequestRequestTypeDef](./type_defs.md#getresourcepolicyrequestrequesttypedef)
- [GetResourcePolicyResponseTypeDef](./type_defs.md#getresourcepolicyresponsetypedef)
- [GetSecretValueRequestRequestTypeDef](./type_defs.md#getsecretvaluerequestrequesttypedef)
- [GetSecretValueResponseTypeDef](./type_defs.md#getsecretvalueresponsetypedef)
- [ListSecretVersionIdsRequestRequestTypeDef](./type_defs.md#listsecretversionidsrequestrequesttypedef)
- [ListSecretVersionIdsResponseTypeDef](./type_defs.md#listsecretversionidsresponsetypedef)
- [ListSecretsRequestListSecretsPaginateTypeDef](./type_defs.md#listsecretsrequestlistsecretspaginatetypedef)
- [ListSecretsRequestRequestTypeDef](./type_defs.md#listsecretsrequestrequesttypedef)
- [ListSecretsResponseTypeDef](./type_defs.md#listsecretsresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PutResourcePolicyRequestRequestTypeDef](./type_defs.md#putresourcepolicyrequestrequesttypedef)
- [PutResourcePolicyResponseTypeDef](./type_defs.md#putresourcepolicyresponsetypedef)
- [PutSecretValueRequestRequestTypeDef](./type_defs.md#putsecretvaluerequestrequesttypedef)
- [PutSecretValueResponseTypeDef](./type_defs.md#putsecretvalueresponsetypedef)
- [RemoveRegionsFromReplicationRequestRequestTypeDef](./type_defs.md#removeregionsfromreplicationrequestrequesttypedef)
- [RemoveRegionsFromReplicationResponseTypeDef](./type_defs.md#removeregionsfromreplicationresponsetypedef)
- [ReplicaRegionTypeTypeDef](./type_defs.md#replicaregiontypetypedef)
- [ReplicateSecretToRegionsRequestRequestTypeDef](./type_defs.md#replicatesecrettoregionsrequestrequesttypedef)
- [ReplicateSecretToRegionsResponseTypeDef](./type_defs.md#replicatesecrettoregionsresponsetypedef)
- [ReplicationStatusTypeTypeDef](./type_defs.md#replicationstatustypetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RestoreSecretRequestRequestTypeDef](./type_defs.md#restoresecretrequestrequesttypedef)
- [RestoreSecretResponseTypeDef](./type_defs.md#restoresecretresponsetypedef)
- [RotateSecretRequestRequestTypeDef](./type_defs.md#rotatesecretrequestrequesttypedef)
- [RotateSecretResponseTypeDef](./type_defs.md#rotatesecretresponsetypedef)
- [RotationRulesTypeTypeDef](./type_defs.md#rotationrulestypetypedef)
- [SecretListEntryTypeDef](./type_defs.md#secretlistentrytypedef)
- [SecretVersionsListEntryTypeDef](./type_defs.md#secretversionslistentrytypedef)
- [StopReplicationToReplicaRequestRequestTypeDef](./type_defs.md#stopreplicationtoreplicarequestrequesttypedef)
- [StopReplicationToReplicaResponseTypeDef](./type_defs.md#stopreplicationtoreplicaresponsetypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateSecretRequestRequestTypeDef](./type_defs.md#updatesecretrequestrequesttypedef)
- [UpdateSecretResponseTypeDef](./type_defs.md#updatesecretresponsetypedef)
- [UpdateSecretVersionStageRequestRequestTypeDef](./type_defs.md#updatesecretversionstagerequestrequesttypedef)
- [UpdateSecretVersionStageResponseTypeDef](./type_defs.md#updatesecretversionstageresponsetypedef)
- [ValidateResourcePolicyRequestRequestTypeDef](./type_defs.md#validateresourcepolicyrequestrequesttypedef)
- [ValidateResourcePolicyResponseTypeDef](./type_defs.md#validateresourcepolicyresponsetypedef)
- [ValidationErrorsEntryTypeDef](./type_defs.md#validationerrorsentrytypedef)

