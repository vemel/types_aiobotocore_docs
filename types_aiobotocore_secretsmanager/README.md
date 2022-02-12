<a id="type-annotations-for-aiobotocore-secretsmanager-module"></a>

# Type annotations for aiobotocore SecretsManager module

> [Index](..) > SecretsManager

Auto-generated documentation for
[SecretsManager](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
type annotations stubs module
[types-aiobotocore-secretsmanager](https://pypi.org/project/types-aiobotocore-secretsmanager/).

- [Type annotations for aiobotocore SecretsManager module](#type-annotations-for-aiobotocore-secretsmanager-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [SecretsManagerClient](#secretsmanagerclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `SecretsManager`.

<a id="from-pypi-with-pip"></a>

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

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-secretsmanager
```

<a id="secretsmanagerclient"></a>

## SecretsManagerClient

Type annotations for `session.create_client("secretsmanager")` as
[SecretsManagerClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_secretsmanager.client import SecretsManagerClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [cancel_rotate_secret](./client.md#cancel_rotate_secret)
- [create_secret](./client.md#create_secret)
- [delete_resource_policy](./client.md#delete_resource_policy)
- [delete_secret](./client.md#delete_secret)
- [describe_secret](./client.md#describe_secret)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_random_password](./client.md#get_random_password)
- [get_resource_policy](./client.md#get_resource_policy)
- [get_secret_value](./client.md#get_secret_value)
- [list_secret_version_ids](./client.md#list_secret_version_ids)
- [list_secrets](./client.md#list_secrets)
- [put_resource_policy](./client.md#put_resource_policy)
- [put_secret_value](./client.md#put_secret_value)
- [remove_regions_from_replication](./client.md#remove_regions_from_replication)
- [replicate_secret_to_regions](./client.md#replicate_secret_to_regions)
- [restore_secret](./client.md#restore_secret)
- [rotate_secret](./client.md#rotate_secret)
- [stop_replication_to_replica](./client.md#stop_replication_to_replica)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_secret](./client.md#update_secret)
- [update_secret_version_stage](./client.md#update_secret_version_stage)
- [validate_resource_policy](./client.md#validate_resource_policy)

<a id="exceptions"></a>

### Exceptions

SecretsManagerClient [exceptions](./client.md#exceptions)

- ClientError
- DecryptionFailure
- EncryptionFailure
- InternalServiceError
- InvalidNextTokenException
- InvalidParameterException
- InvalidRequestException
- LimitExceededException
- MalformedPolicyDocumentException
- PreconditionNotMetException
- PublicPolicyException
- ResourceExistsException
- ResourceNotFoundException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("secretsmanager").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_secretsmanager.paginator import ListSecretsPaginator, ...
```

- [ListSecretsPaginator](./paginators.md#listsecretspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_secretsmanager.literals import FilterNameStringTypeType, ...
```

- [FilterNameStringTypeType](./literals.md#filternamestringtypetype)
- [ListSecretsPaginatorName](./literals.md#listsecretspaginatorname)
- [SortOrderTypeType](./literals.md#sortordertypetype)
- [StatusTypeType](./literals.md#statustypetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_secretsmanager.type_defs import CancelRotateSecretRequestRequestTypeDef, ...
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
