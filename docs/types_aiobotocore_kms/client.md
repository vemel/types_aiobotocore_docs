<a id="kmsclient-for-aiobotocore-kms-module"></a>

# KMSClient for aiobotocore KMS module

> [Index](../README.md) > [KMS](./README.md) > KMSClient

Auto-generated documentation for
[KMS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS)
type annotations stubs module
[types-aiobotocore-kms](https://pypi.org/project/types-aiobotocore-kms/).

- [KMSClient for aiobotocore KMS module](#kmsclient-for-aiobotocore-kms-module)
  - [KMSClient](#kmsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [cancel_key_deletion](#cancel_key_deletion)
    - [connect_custom_key_store](#connect_custom_key_store)
    - [create_alias](#create_alias)
    - [create_custom_key_store](#create_custom_key_store)
    - [create_grant](#create_grant)
    - [create_key](#create_key)
    - [decrypt](#decrypt)
    - [delete_alias](#delete_alias)
    - [delete_custom_key_store](#delete_custom_key_store)
    - [delete_imported_key_material](#delete_imported_key_material)
    - [describe_custom_key_stores](#describe_custom_key_stores)
    - [describe_key](#describe_key)
    - [disable_key](#disable_key)
    - [disable_key_rotation](#disable_key_rotation)
    - [disconnect_custom_key_store](#disconnect_custom_key_store)
    - [enable_key](#enable_key)
    - [enable_key_rotation](#enable_key_rotation)
    - [encrypt](#encrypt)
    - [generate_data_key](#generate_data_key)
    - [generate_data_key_pair](#generate_data_key_pair)
    - [generate_data_key_pair_without_plaintext](#generate_data_key_pair_without_plaintext)
    - [generate_data_key_without_plaintext](#generate_data_key_without_plaintext)
    - [generate_presigned_url](#generate_presigned_url)
    - [generate_random](#generate_random)
    - [get_key_policy](#get_key_policy)
    - [get_key_rotation_status](#get_key_rotation_status)
    - [get_parameters_for_import](#get_parameters_for_import)
    - [get_public_key](#get_public_key)
    - [import_key_material](#import_key_material)
    - [list_aliases](#list_aliases)
    - [list_grants](#list_grants)
    - [list_key_policies](#list_key_policies)
    - [list_keys](#list_keys)
    - [list_resource_tags](#list_resource_tags)
    - [list_retirable_grants](#list_retirable_grants)
    - [put_key_policy](#put_key_policy)
    - [re_encrypt](#re_encrypt)
    - [replicate_key](#replicate_key)
    - [retire_grant](#retire_grant)
    - [revoke_grant](#revoke_grant)
    - [schedule_key_deletion](#schedule_key_deletion)
    - [sign](#sign)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_alias](#update_alias)
    - [update_custom_key_store](#update_custom_key_store)
    - [update_key_description](#update_key_description)
    - [update_primary_region](#update_primary_region)
    - [verify](#verify)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="kmsclient"></a>

## KMSClient

Type annotations for `session.create_client("kms")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_kms.client import KMSClient

session = get_session()
async with session.create_client("kms") as client:
    client: KMSClient
```

Boto3 documentation:
[KMS.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_kms.client import Exceptions

def handle_error(exc: Exceptions.AlreadyExistsException) -> None:
    ...
```

Exceptions:

- `Exceptions.AlreadyExistsException`
- `Exceptions.ClientError`
- `Exceptions.CloudHsmClusterInUseException`
- `Exceptions.CloudHsmClusterInvalidConfigurationException`
- `Exceptions.CloudHsmClusterNotActiveException`
- `Exceptions.CloudHsmClusterNotFoundException`
- `Exceptions.CloudHsmClusterNotRelatedException`
- `Exceptions.CustomKeyStoreHasCMKsException`
- `Exceptions.CustomKeyStoreInvalidStateException`
- `Exceptions.CustomKeyStoreNameInUseException`
- `Exceptions.CustomKeyStoreNotFoundException`
- `Exceptions.DependencyTimeoutException`
- `Exceptions.DisabledException`
- `Exceptions.ExpiredImportTokenException`
- `Exceptions.IncorrectKeyException`
- `Exceptions.IncorrectKeyMaterialException`
- `Exceptions.IncorrectTrustAnchorException`
- `Exceptions.InvalidAliasNameException`
- `Exceptions.InvalidArnException`
- `Exceptions.InvalidCiphertextException`
- `Exceptions.InvalidGrantIdException`
- `Exceptions.InvalidGrantTokenException`
- `Exceptions.InvalidImportTokenException`
- `Exceptions.InvalidKeyUsageException`
- `Exceptions.InvalidMarkerException`
- `Exceptions.KMSInternalException`
- `Exceptions.KMSInvalidSignatureException`
- `Exceptions.KMSInvalidStateException`
- `Exceptions.KeyUnavailableException`
- `Exceptions.LimitExceededException`
- `Exceptions.MalformedPolicyDocumentException`
- `Exceptions.NotFoundException`
- `Exceptions.TagException`
- `Exceptions.UnsupportedOperationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

KMSClient exceptions.

Type annotations for `session.create_client("kms").exceptions` method.

Boto3 documentation:
[KMS.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("kms").can_paginate` method.

Boto3 documentation:
[KMS.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="cancel\_key\_deletion"></a>

### cancel_key_deletion

Cancels the deletion of a KMS key.

Type annotations for `session.create_client("kms").cancel_key_deletion` method.

Boto3 documentation:
[KMS.Client.cancel_key_deletion](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.cancel_key_deletion)

Asynchronous method. Use `await cancel_key_deletion(...)` for a synchronous
call.

Arguments mapping described in
[CancelKeyDeletionRequestRequestTypeDef](./type_defs.md#cancelkeydeletionrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*

Returns a `Coroutine` for
[CancelKeyDeletionResponseTypeDef](./type_defs.md#cancelkeydeletionresponsetypedef).

<a id="connect\_custom\_key\_store"></a>

### connect_custom_key_store

Connects or reconnects a \[custom key
store\](https://docs.aws.amazon.com/kms/latest/developerguide/custom-key-store-
overview.html)\_ to its associated CloudHSM cluster.

Type annotations for `session.create_client("kms").connect_custom_key_store`
method.

Boto3 documentation:
[KMS.Client.connect_custom_key_store](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.connect_custom_key_store)

Asynchronous method. Use `await connect_custom_key_store(...)` for a
synchronous call.

Arguments mapping described in
[ConnectCustomKeyStoreRequestRequestTypeDef](./type_defs.md#connectcustomkeystorerequestrequesttypedef).

Keyword-only arguments:

- `CustomKeyStoreId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create\_alias"></a>

### create_alias

Creates a friendly name for a KMS key.

Type annotations for `session.create_client("kms").create_alias` method.

Boto3 documentation:
[KMS.Client.create_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.create_alias)

Asynchronous method. Use `await create_alias(...)` for a synchronous call.

Arguments mapping described in
[CreateAliasRequestRequestTypeDef](./type_defs.md#createaliasrequestrequesttypedef).

Keyword-only arguments:

- `AliasName`: `str` *(required)*
- `TargetKeyId`: `str` *(required)*

<a id="create\_custom\_key\_store"></a>

### create_custom_key_store

Creates a \[custom key
store\](https://docs.aws.amazon.com/kms/latest/developerguide/custom-key-store-
overview.html)\_ that is associated with an
[CloudHSM cluster](https://docs.aws.amazon.com/cloudhsm/latest/userguide/clusters.html)\_
that you own and manage.

Type annotations for `session.create_client("kms").create_custom_key_store`
method.

Boto3 documentation:
[KMS.Client.create_custom_key_store](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.create_custom_key_store)

Asynchronous method. Use `await create_custom_key_store(...)` for a synchronous
call.

Arguments mapping described in
[CreateCustomKeyStoreRequestRequestTypeDef](./type_defs.md#createcustomkeystorerequestrequesttypedef).

Keyword-only arguments:

- `CustomKeyStoreName`: `str` *(required)*
- `CloudHsmClusterId`: `str` *(required)*
- `TrustAnchorCertificate`: `str` *(required)*
- `KeyStorePassword`: `str` *(required)*

Returns a `Coroutine` for
[CreateCustomKeyStoreResponseTypeDef](./type_defs.md#createcustomkeystoreresponsetypedef).

<a id="create\_grant"></a>

### create_grant

Adds a grant to a KMS key.

Type annotations for `session.create_client("kms").create_grant` method.

Boto3 documentation:
[KMS.Client.create_grant](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.create_grant)

Asynchronous method. Use `await create_grant(...)` for a synchronous call.

Arguments mapping described in
[CreateGrantRequestRequestTypeDef](./type_defs.md#creategrantrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `GranteePrincipal`: `str` *(required)*
- `Operations`:
  `Sequence`\[[GrantOperationType](./literals.md#grantoperationtype)\]
  *(required)*
- `RetiringPrincipal`: `str`
- `Constraints`:
  [GrantConstraintsTypeDef](./type_defs.md#grantconstraintstypedef)
- `GrantTokens`: `Sequence`\[`str`\]
- `Name`: `str`

Returns a `Coroutine` for
[CreateGrantResponseTypeDef](./type_defs.md#creategrantresponsetypedef).

<a id="create\_key"></a>

### create_key

Creates a unique customer managed \[KMS
key\](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#kms-
keys)\_ in your Amazon Web Services account and Region.

Type annotations for `session.create_client("kms").create_key` method.

Boto3 documentation:
[KMS.Client.create_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.create_key)

Asynchronous method. Use `await create_key(...)` for a synchronous call.

Arguments mapping described in
[CreateKeyRequestRequestTypeDef](./type_defs.md#createkeyrequestrequesttypedef).

Keyword-only arguments:

- `Policy`: `str`
- `Description`: `str`
- `KeyUsage`: [KeyUsageTypeType](./literals.md#keyusagetypetype)
- `CustomerMasterKeySpec`:
  [CustomerMasterKeySpecType](./literals.md#customermasterkeyspectype)
- `KeySpec`: [KeySpecType](./literals.md#keyspectype)
- `Origin`: [OriginTypeType](./literals.md#origintypetype)
- `CustomKeyStoreId`: `str`
- `BypassPolicyLockoutSafetyCheck`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `MultiRegion`: `bool`

Returns a `Coroutine` for
[CreateKeyResponseTypeDef](./type_defs.md#createkeyresponsetypedef).

<a id="decrypt"></a>

### decrypt

Decrypts ciphertext that was encrypted by a KMS key using any of the following
operations * Encrypt * GenerateDataKey * GenerateDataKeyPair \*
GenerateDataKeyWithoutPlaintext * GenerateDataKeyPairWithoutPlaintext You can
use this operation to decrypt cipher...

Type annotations for `session.create_client("kms").decrypt` method.

Boto3 documentation:
[KMS.Client.decrypt](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.decrypt)

Asynchronous method. Use `await decrypt(...)` for a synchronous call.

Arguments mapping described in
[DecryptRequestRequestTypeDef](./type_defs.md#decryptrequestrequesttypedef).

Keyword-only arguments:

- `CiphertextBlob`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `EncryptionContext`: `Mapping`\[`str`, `str`\]
- `GrantTokens`: `Sequence`\[`str`\]
- `KeyId`: `str`
- `EncryptionAlgorithm`:
  [EncryptionAlgorithmSpecType](./literals.md#encryptionalgorithmspectype)

Returns a `Coroutine` for
[DecryptResponseTypeDef](./type_defs.md#decryptresponsetypedef).

<a id="delete\_alias"></a>

### delete_alias

Deletes the specified alias.

Type annotations for `session.create_client("kms").delete_alias` method.

Boto3 documentation:
[KMS.Client.delete_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.delete_alias)

Asynchronous method. Use `await delete_alias(...)` for a synchronous call.

Arguments mapping described in
[DeleteAliasRequestRequestTypeDef](./type_defs.md#deletealiasrequestrequesttypedef).

Keyword-only arguments:

- `AliasName`: `str` *(required)*

<a id="delete\_custom\_key\_store"></a>

### delete_custom_key_store

Deletes a \[custom key
store\](https://docs.aws.amazon.com/kms/latest/developerguide/custom-key-store-
overview.html)\_.

Type annotations for `session.create_client("kms").delete_custom_key_store`
method.

Boto3 documentation:
[KMS.Client.delete_custom_key_store](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.delete_custom_key_store)

Asynchronous method. Use `await delete_custom_key_store(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCustomKeyStoreRequestRequestTypeDef](./type_defs.md#deletecustomkeystorerequestrequesttypedef).

Keyword-only arguments:

- `CustomKeyStoreId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_imported\_key\_material"></a>

### delete_imported_key_material

Deletes key material that you previously imported.

Type annotations for
`session.create_client("kms").delete_imported_key_material` method.

Boto3 documentation:
[KMS.Client.delete_imported_key_material](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.delete_imported_key_material)

Asynchronous method. Use `await delete_imported_key_material(...)` for a
synchronous call.

Arguments mapping described in
[DeleteImportedKeyMaterialRequestRequestTypeDef](./type_defs.md#deleteimportedkeymaterialrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*

<a id="describe\_custom\_key\_stores"></a>

### describe_custom_key_stores

Gets information about \[custom key
stores\](https://docs.aws.amazon.com/kms/latest/developerguide/custom-key-store-
overview.html)\_ in the account and Region.

Type annotations for `session.create_client("kms").describe_custom_key_stores`
method.

Boto3 documentation:
[KMS.Client.describe_custom_key_stores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.describe_custom_key_stores)

Asynchronous method. Use `await describe_custom_key_stores(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCustomKeyStoresRequestRequestTypeDef](./type_defs.md#describecustomkeystoresrequestrequesttypedef).

Keyword-only arguments:

- `CustomKeyStoreId`: `str`
- `CustomKeyStoreName`: `str`
- `Limit`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[DescribeCustomKeyStoresResponseTypeDef](./type_defs.md#describecustomkeystoresresponsetypedef).

<a id="describe\_key"></a>

### describe_key

Provides detailed information about a KMS key.

Type annotations for `session.create_client("kms").describe_key` method.

Boto3 documentation:
[KMS.Client.describe_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.describe_key)

Asynchronous method. Use `await describe_key(...)` for a synchronous call.

Arguments mapping described in
[DescribeKeyRequestRequestTypeDef](./type_defs.md#describekeyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeKeyResponseTypeDef](./type_defs.md#describekeyresponsetypedef).

<a id="disable\_key"></a>

### disable_key

Sets the state of a KMS key to disabled.

Type annotations for `session.create_client("kms").disable_key` method.

Boto3 documentation:
[KMS.Client.disable_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.disable_key)

Asynchronous method. Use `await disable_key(...)` for a synchronous call.

Arguments mapping described in
[DisableKeyRequestRequestTypeDef](./type_defs.md#disablekeyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*

<a id="disable\_key\_rotation"></a>

### disable_key_rotation

Disables \[automatic rotation of the key
material\](https://docs.aws.amazon.com/kms/latest/developerguide/rotate-
keys.html)\_ for the specified symmetric KMS key.

Type annotations for `session.create_client("kms").disable_key_rotation`
method.

Boto3 documentation:
[KMS.Client.disable_key_rotation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.disable_key_rotation)

Asynchronous method. Use `await disable_key_rotation(...)` for a synchronous
call.

Arguments mapping described in
[DisableKeyRotationRequestRequestTypeDef](./type_defs.md#disablekeyrotationrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*

<a id="disconnect\_custom\_key\_store"></a>

### disconnect_custom_key_store

Disconnects the \[custom key
store\](https://docs.aws.amazon.com/kms/latest/developerguide/custom-key-store-
overview.html)\_ from its associated CloudHSM cluster.

Type annotations for `session.create_client("kms").disconnect_custom_key_store`
method.

Boto3 documentation:
[KMS.Client.disconnect_custom_key_store](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.disconnect_custom_key_store)

Asynchronous method. Use `await disconnect_custom_key_store(...)` for a
synchronous call.

Arguments mapping described in
[DisconnectCustomKeyStoreRequestRequestTypeDef](./type_defs.md#disconnectcustomkeystorerequestrequesttypedef).

Keyword-only arguments:

- `CustomKeyStoreId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="enable\_key"></a>

### enable_key

Sets the key state of a KMS key to enabled.

Type annotations for `session.create_client("kms").enable_key` method.

Boto3 documentation:
[KMS.Client.enable_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.enable_key)

Asynchronous method. Use `await enable_key(...)` for a synchronous call.

Arguments mapping described in
[EnableKeyRequestRequestTypeDef](./type_defs.md#enablekeyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*

<a id="enable\_key\_rotation"></a>

### enable_key_rotation

Enables \[automatic rotation of the key
material\](https://docs.aws.amazon.com/kms/latest/developerguide/rotate-
keys.html)\_ for the specified symmetric KMS key.

Type annotations for `session.create_client("kms").enable_key_rotation` method.

Boto3 documentation:
[KMS.Client.enable_key_rotation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.enable_key_rotation)

Asynchronous method. Use `await enable_key_rotation(...)` for a synchronous
call.

Arguments mapping described in
[EnableKeyRotationRequestRequestTypeDef](./type_defs.md#enablekeyrotationrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*

<a id="encrypt"></a>

### encrypt

Encrypts plaintext into ciphertext by using a KMS key.

Type annotations for `session.create_client("kms").encrypt` method.

Boto3 documentation:
[KMS.Client.encrypt](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.encrypt)

Asynchronous method. Use `await encrypt(...)` for a synchronous call.

Arguments mapping described in
[EncryptRequestRequestTypeDef](./type_defs.md#encryptrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Plaintext`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `EncryptionContext`: `Mapping`\[`str`, `str`\]
- `GrantTokens`: `Sequence`\[`str`\]
- `EncryptionAlgorithm`:
  [EncryptionAlgorithmSpecType](./literals.md#encryptionalgorithmspectype)

Returns a `Coroutine` for
[EncryptResponseTypeDef](./type_defs.md#encryptresponsetypedef).

<a id="generate\_data\_key"></a>

### generate_data_key

Generates a unique symmetric data key for client-side encryption.

Type annotations for `session.create_client("kms").generate_data_key` method.

Boto3 documentation:
[KMS.Client.generate_data_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key)

Asynchronous method. Use `await generate_data_key(...)` for a synchronous call.

Arguments mapping described in
[GenerateDataKeyRequestRequestTypeDef](./type_defs.md#generatedatakeyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `EncryptionContext`: `Mapping`\[`str`, `str`\]
- `NumberOfBytes`: `int`
- `KeySpec`: [DataKeySpecType](./literals.md#datakeyspectype)
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[GenerateDataKeyResponseTypeDef](./type_defs.md#generatedatakeyresponsetypedef).

<a id="generate\_data\_key\_pair"></a>

### generate_data_key_pair

Generates a unique asymmetric data key pair.

Type annotations for `session.create_client("kms").generate_data_key_pair`
method.

Boto3 documentation:
[KMS.Client.generate_data_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key_pair)

Asynchronous method. Use `await generate_data_key_pair(...)` for a synchronous
call.

Arguments mapping described in
[GenerateDataKeyPairRequestRequestTypeDef](./type_defs.md#generatedatakeypairrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `KeyPairSpec`: [DataKeyPairSpecType](./literals.md#datakeypairspectype)
  *(required)*
- `EncryptionContext`: `Mapping`\[`str`, `str`\]
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[GenerateDataKeyPairResponseTypeDef](./type_defs.md#generatedatakeypairresponsetypedef).

<a id="generate\_data\_key\_pair\_without\_plaintext"></a>

### generate_data_key_pair_without_plaintext

Generates a unique asymmetric data key pair.

Type annotations for
`session.create_client("kms").generate_data_key_pair_without_plaintext` method.

Boto3 documentation:
[KMS.Client.generate_data_key_pair_without_plaintext](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key_pair_without_plaintext)

Asynchronous method. Use `await generate_data_key_pair_without_plaintext(...)`
for a synchronous call.

Arguments mapping described in
[GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef](./type_defs.md#generatedatakeypairwithoutplaintextrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `KeyPairSpec`: [DataKeyPairSpecType](./literals.md#datakeypairspectype)
  *(required)*
- `EncryptionContext`: `Mapping`\[`str`, `str`\]
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[GenerateDataKeyPairWithoutPlaintextResponseTypeDef](./type_defs.md#generatedatakeypairwithoutplaintextresponsetypedef).

<a id="generate\_data\_key\_without\_plaintext"></a>

### generate_data_key_without_plaintext

Generates a unique symmetric data key.

Type annotations for
`session.create_client("kms").generate_data_key_without_plaintext` method.

Boto3 documentation:
[KMS.Client.generate_data_key_without_plaintext](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key_without_plaintext)

Asynchronous method. Use `await generate_data_key_without_plaintext(...)` for a
synchronous call.

Arguments mapping described in
[GenerateDataKeyWithoutPlaintextRequestRequestTypeDef](./type_defs.md#generatedatakeywithoutplaintextrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `EncryptionContext`: `Mapping`\[`str`, `str`\]
- `KeySpec`: [DataKeySpecType](./literals.md#datakeyspectype)
- `NumberOfBytes`: `int`
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[GenerateDataKeyWithoutPlaintextResponseTypeDef](./type_defs.md#generatedatakeywithoutplaintextresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("kms").generate_presigned_url`
method.

Boto3 documentation:
[KMS.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="generate\_random"></a>

### generate_random

Returns a random byte string that is cryptographically secure.

Type annotations for `session.create_client("kms").generate_random` method.

Boto3 documentation:
[KMS.Client.generate_random](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_random)

Asynchronous method. Use `await generate_random(...)` for a synchronous call.

Arguments mapping described in
[GenerateRandomRequestRequestTypeDef](./type_defs.md#generaterandomrequestrequesttypedef).

Keyword-only arguments:

- `NumberOfBytes`: `int`
- `CustomKeyStoreId`: `str`

Returns a `Coroutine` for
[GenerateRandomResponseTypeDef](./type_defs.md#generaterandomresponsetypedef).

<a id="get\_key\_policy"></a>

### get_key_policy

Gets a key policy attached to the specified KMS key.

Type annotations for `session.create_client("kms").get_key_policy` method.

Boto3 documentation:
[KMS.Client.get_key_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.get_key_policy)

Asynchronous method. Use `await get_key_policy(...)` for a synchronous call.

Arguments mapping described in
[GetKeyPolicyRequestRequestTypeDef](./type_defs.md#getkeypolicyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `PolicyName`: `str` *(required)*

Returns a `Coroutine` for
[GetKeyPolicyResponseTypeDef](./type_defs.md#getkeypolicyresponsetypedef).

<a id="get\_key\_rotation\_status"></a>

### get_key_rotation_status

Gets a Boolean value that indicates whether \[automatic rotation of the key
material\](https://docs.aws.amazon.com/kms/latest/developerguide/rotate-
keys.html)\_ is enabled for the specified KMS key.

Type annotations for `session.create_client("kms").get_key_rotation_status`
method.

Boto3 documentation:
[KMS.Client.get_key_rotation_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.get_key_rotation_status)

Asynchronous method. Use `await get_key_rotation_status(...)` for a synchronous
call.

Arguments mapping described in
[GetKeyRotationStatusRequestRequestTypeDef](./type_defs.md#getkeyrotationstatusrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*

Returns a `Coroutine` for
[GetKeyRotationStatusResponseTypeDef](./type_defs.md#getkeyrotationstatusresponsetypedef).

<a id="get\_parameters\_for\_import"></a>

### get_parameters_for_import

Returns the items you need to import key material into a symmetric, customer
managed KMS key.

Type annotations for `session.create_client("kms").get_parameters_for_import`
method.

Boto3 documentation:
[KMS.Client.get_parameters_for_import](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.get_parameters_for_import)

Asynchronous method. Use `await get_parameters_for_import(...)` for a
synchronous call.

Arguments mapping described in
[GetParametersForImportRequestRequestTypeDef](./type_defs.md#getparametersforimportrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `WrappingAlgorithm`: [AlgorithmSpecType](./literals.md#algorithmspectype)
  *(required)*
- `WrappingKeySpec`: `Literal['RSA_2048']` (see
  [WrappingKeySpecType](./literals.md#wrappingkeyspectype)) *(required)*

Returns a `Coroutine` for
[GetParametersForImportResponseTypeDef](./type_defs.md#getparametersforimportresponsetypedef).

<a id="get\_public\_key"></a>

### get_public_key

Returns the public key of an asymmetric KMS key.

Type annotations for `session.create_client("kms").get_public_key` method.

Boto3 documentation:
[KMS.Client.get_public_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.get_public_key)

Asynchronous method. Use `await get_public_key(...)` for a synchronous call.

Arguments mapping described in
[GetPublicKeyRequestRequestTypeDef](./type_defs.md#getpublickeyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[GetPublicKeyResponseTypeDef](./type_defs.md#getpublickeyresponsetypedef).

<a id="import\_key\_material"></a>

### import_key_material

Imports key material into an existing symmetric KMS KMS key that was created
without key material.

Type annotations for `session.create_client("kms").import_key_material` method.

Boto3 documentation:
[KMS.Client.import_key_material](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.import_key_material)

Asynchronous method. Use `await import_key_material(...)` for a synchronous
call.

Arguments mapping described in
[ImportKeyMaterialRequestRequestTypeDef](./type_defs.md#importkeymaterialrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `ImportToken`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `EncryptedKeyMaterial`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `ValidTo`: `Union`\[`datetime`, `str`\]
- `ExpirationModel`:
  [ExpirationModelTypeType](./literals.md#expirationmodeltypetype)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="list\_aliases"></a>

### list_aliases

Gets a list of aliases in the caller's Amazon Web Services account and region.

Type annotations for `session.create_client("kms").list_aliases` method.

Boto3 documentation:
[KMS.Client.list_aliases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.list_aliases)

Asynchronous method. Use `await list_aliases(...)` for a synchronous call.

Arguments mapping described in
[ListAliasesRequestRequestTypeDef](./type_defs.md#listaliasesrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str`
- `Limit`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ListAliasesResponseTypeDef](./type_defs.md#listaliasesresponsetypedef).

<a id="list\_grants"></a>

### list_grants

Gets a list of all grants for the specified KMS key.

Type annotations for `session.create_client("kms").list_grants` method.

Boto3 documentation:
[KMS.Client.list_grants](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.list_grants)

Asynchronous method. Use `await list_grants(...)` for a synchronous call.

Arguments mapping described in
[ListGrantsRequestRequestTypeDef](./type_defs.md#listgrantsrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Limit`: `int`
- `Marker`: `str`
- `GrantId`: `str`
- `GranteePrincipal`: `str`

Returns a `Coroutine` for
[ListGrantsResponseTypeDef](./type_defs.md#listgrantsresponsetypedef).

<a id="list\_key\_policies"></a>

### list_key_policies

Gets the names of the key policies that are attached to a KMS key.

Type annotations for `session.create_client("kms").list_key_policies` method.

Boto3 documentation:
[KMS.Client.list_key_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.list_key_policies)

Asynchronous method. Use `await list_key_policies(...)` for a synchronous call.

Arguments mapping described in
[ListKeyPoliciesRequestRequestTypeDef](./type_defs.md#listkeypoliciesrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Limit`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ListKeyPoliciesResponseTypeDef](./type_defs.md#listkeypoliciesresponsetypedef).

<a id="list\_keys"></a>

### list_keys

Gets a list of all KMS keys in the caller's Amazon Web Services account and
Region.

Type annotations for `session.create_client("kms").list_keys` method.

Boto3 documentation:
[KMS.Client.list_keys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.list_keys)

Asynchronous method. Use `await list_keys(...)` for a synchronous call.

Arguments mapping described in
[ListKeysRequestRequestTypeDef](./type_defs.md#listkeysrequestrequesttypedef).

Keyword-only arguments:

- `Limit`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ListKeysResponseTypeDef](./type_defs.md#listkeysresponsetypedef).

<a id="list\_resource\_tags"></a>

### list_resource_tags

Returns all tags on the specified KMS key.

Type annotations for `session.create_client("kms").list_resource_tags` method.

Boto3 documentation:
[KMS.Client.list_resource_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.list_resource_tags)

Asynchronous method. Use `await list_resource_tags(...)` for a synchronous
call.

Arguments mapping described in
[ListResourceTagsRequestRequestTypeDef](./type_defs.md#listresourcetagsrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Limit`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ListResourceTagsResponseTypeDef](./type_defs.md#listresourcetagsresponsetypedef).

<a id="list\_retirable\_grants"></a>

### list_retirable_grants

Returns information about all grants in the Amazon Web Services account and
Region that have the specified retiring principal.

Type annotations for `session.create_client("kms").list_retirable_grants`
method.

Boto3 documentation:
[KMS.Client.list_retirable_grants](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.list_retirable_grants)

Asynchronous method. Use `await list_retirable_grants(...)` for a synchronous
call.

Arguments mapping described in
[ListRetirableGrantsRequestRequestTypeDef](./type_defs.md#listretirablegrantsrequestrequesttypedef).

Keyword-only arguments:

- `RetiringPrincipal`: `str` *(required)*
- `Limit`: `int`
- `Marker`: `str`

Returns a `Coroutine` for
[ListGrantsResponseTypeDef](./type_defs.md#listgrantsresponsetypedef).

<a id="put\_key\_policy"></a>

### put_key_policy

Attaches a key policy to the specified KMS key.

Type annotations for `session.create_client("kms").put_key_policy` method.

Boto3 documentation:
[KMS.Client.put_key_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.put_key_policy)

Asynchronous method. Use `await put_key_policy(...)` for a synchronous call.

Arguments mapping described in
[PutKeyPolicyRequestRequestTypeDef](./type_defs.md#putkeypolicyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `PolicyName`: `str` *(required)*
- `Policy`: `str` *(required)*
- `BypassPolicyLockoutSafetyCheck`: `bool`

<a id="re\_encrypt"></a>

### re_encrypt

Decrypts ciphertext and then reencrypts it entirely within KMS.

Type annotations for `session.create_client("kms").re_encrypt` method.

Boto3 documentation:
[KMS.Client.re_encrypt](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.re_encrypt)

Asynchronous method. Use `await re_encrypt(...)` for a synchronous call.

Arguments mapping described in
[ReEncryptRequestRequestTypeDef](./type_defs.md#reencryptrequestrequesttypedef).

Keyword-only arguments:

- `CiphertextBlob`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `DestinationKeyId`: `str` *(required)*
- `SourceEncryptionContext`: `Mapping`\[`str`, `str`\]
- `SourceKeyId`: `str`
- `DestinationEncryptionContext`: `Mapping`\[`str`, `str`\]
- `SourceEncryptionAlgorithm`:
  [EncryptionAlgorithmSpecType](./literals.md#encryptionalgorithmspectype)
- `DestinationEncryptionAlgorithm`:
  [EncryptionAlgorithmSpecType](./literals.md#encryptionalgorithmspectype)
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ReEncryptResponseTypeDef](./type_defs.md#reencryptresponsetypedef).

<a id="replicate\_key"></a>

### replicate_key

Replicates a multi-Region key into the specified Region.

Type annotations for `session.create_client("kms").replicate_key` method.

Boto3 documentation:
[KMS.Client.replicate_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.replicate_key)

Asynchronous method. Use `await replicate_key(...)` for a synchronous call.

Arguments mapping described in
[ReplicateKeyRequestRequestTypeDef](./type_defs.md#replicatekeyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `ReplicaRegion`: `str` *(required)*
- `Policy`: `str`
- `BypassPolicyLockoutSafetyCheck`: `bool`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[ReplicateKeyResponseTypeDef](./type_defs.md#replicatekeyresponsetypedef).

<a id="retire\_grant"></a>

### retire_grant

Deletes a grant.

Type annotations for `session.create_client("kms").retire_grant` method.

Boto3 documentation:
[KMS.Client.retire_grant](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.retire_grant)

Asynchronous method. Use `await retire_grant(...)` for a synchronous call.

Arguments mapping described in
[RetireGrantRequestRequestTypeDef](./type_defs.md#retiregrantrequestrequesttypedef).

Keyword-only arguments:

- `GrantToken`: `str`
- `KeyId`: `str`
- `GrantId`: `str`

<a id="revoke\_grant"></a>

### revoke_grant

Deletes the specified grant.

Type annotations for `session.create_client("kms").revoke_grant` method.

Boto3 documentation:
[KMS.Client.revoke_grant](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.revoke_grant)

Asynchronous method. Use `await revoke_grant(...)` for a synchronous call.

Arguments mapping described in
[RevokeGrantRequestRequestTypeDef](./type_defs.md#revokegrantrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `GrantId`: `str` *(required)*

<a id="schedule\_key\_deletion"></a>

### schedule_key_deletion

Schedules the deletion of a KMS key.

Type annotations for `session.create_client("kms").schedule_key_deletion`
method.

Boto3 documentation:
[KMS.Client.schedule_key_deletion](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.schedule_key_deletion)

Asynchronous method. Use `await schedule_key_deletion(...)` for a synchronous
call.

Arguments mapping described in
[ScheduleKeyDeletionRequestRequestTypeDef](./type_defs.md#schedulekeydeletionrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `PendingWindowInDays`: `int`

Returns a `Coroutine` for
[ScheduleKeyDeletionResponseTypeDef](./type_defs.md#schedulekeydeletionresponsetypedef).

<a id="sign"></a>

### sign

Creates a
[digital signature](https://en.wikipedia.org/wiki/Digital_signature)\_ for a
message or message digest by using the private key in an asymmetric KMS key.

Type annotations for `session.create_client("kms").sign` method.

Boto3 documentation:
[KMS.Client.sign](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.sign)

Asynchronous method. Use `await sign(...)` for a synchronous call.

Arguments mapping described in
[SignRequestRequestTypeDef](./type_defs.md#signrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Message`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `SigningAlgorithm`:
  [SigningAlgorithmSpecType](./literals.md#signingalgorithmspectype)
  *(required)*
- `MessageType`: [MessageTypeType](./literals.md#messagetypetype)
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[SignResponseTypeDef](./type_defs.md#signresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Adds or edits tags on a \[customer managed
key\](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#customer-
cmk)\_ .

Type annotations for `session.create_client("kms").tag_resource` method.

Boto3 documentation:
[KMS.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

<a id="untag\_resource"></a>

### untag_resource

Deletes tags from a \[customer managed
key\](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#customer-
cmk)\_.

Type annotations for `session.create_client("kms").untag_resource` method.

Boto3 documentation:
[KMS.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update\_alias"></a>

### update_alias

Associates an existing KMS alias with a different KMS key.

Type annotations for `session.create_client("kms").update_alias` method.

Boto3 documentation:
[KMS.Client.update_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.update_alias)

Asynchronous method. Use `await update_alias(...)` for a synchronous call.

Arguments mapping described in
[UpdateAliasRequestRequestTypeDef](./type_defs.md#updatealiasrequestrequesttypedef).

Keyword-only arguments:

- `AliasName`: `str` *(required)*
- `TargetKeyId`: `str` *(required)*

<a id="update\_custom\_key\_store"></a>

### update_custom_key_store

Changes the properties of a custom key store.

Type annotations for `session.create_client("kms").update_custom_key_store`
method.

Boto3 documentation:
[KMS.Client.update_custom_key_store](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.update_custom_key_store)

Asynchronous method. Use `await update_custom_key_store(...)` for a synchronous
call.

Arguments mapping described in
[UpdateCustomKeyStoreRequestRequestTypeDef](./type_defs.md#updatecustomkeystorerequestrequesttypedef).

Keyword-only arguments:

- `CustomKeyStoreId`: `str` *(required)*
- `NewCustomKeyStoreName`: `str`
- `KeyStorePassword`: `str`
- `CloudHsmClusterId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_key\_description"></a>

### update_key_description

Updates the description of a KMS key.

Type annotations for `session.create_client("kms").update_key_description`
method.

Boto3 documentation:
[KMS.Client.update_key_description](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.update_key_description)

Asynchronous method. Use `await update_key_description(...)` for a synchronous
call.

Arguments mapping described in
[UpdateKeyDescriptionRequestRequestTypeDef](./type_defs.md#updatekeydescriptionrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Description`: `str` *(required)*

<a id="update\_primary\_region"></a>

### update_primary_region

Changes the primary key of a multi-Region key.

Type annotations for `session.create_client("kms").update_primary_region`
method.

Boto3 documentation:
[KMS.Client.update_primary_region](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.update_primary_region)

Asynchronous method. Use `await update_primary_region(...)` for a synchronous
call.

Arguments mapping described in
[UpdatePrimaryRegionRequestRequestTypeDef](./type_defs.md#updateprimaryregionrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `PrimaryRegion`: `str` *(required)*

<a id="verify"></a>

### verify

Verifies a digital signature that was generated by the Sign operation.

Type annotations for `session.create_client("kms").verify` method.

Boto3 documentation:
[KMS.Client.verify](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.verify)

Asynchronous method. Use `await verify(...)` for a synchronous call.

Arguments mapping described in
[VerifyRequestRequestTypeDef](./type_defs.md#verifyrequestrequesttypedef).

Keyword-only arguments:

- `KeyId`: `str` *(required)*
- `Message`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `Signature`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `SigningAlgorithm`:
  [SigningAlgorithmSpecType](./literals.md#signingalgorithmspectype)
  *(required)*
- `MessageType`: [MessageTypeType](./literals.md#messagetypetype)
- `GrantTokens`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[VerifyResponseTypeDef](./type_defs.md#verifyresponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("kms").__aenter__` method.

Boto3 documentation:
[KMS.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [KMSClient](#kmsclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("kms").__aexit__` method.

Boto3 documentation:
[KMS.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("kms").get_paginator` method with
overloads.

- `client.get_paginator("list_aliases")` ->
  [ListAliasesPaginator](./paginators.md#listaliasespaginator)
- `client.get_paginator("list_grants")` ->
  [ListGrantsPaginator](./paginators.md#listgrantspaginator)
- `client.get_paginator("list_key_policies")` ->
  [ListKeyPoliciesPaginator](./paginators.md#listkeypoliciespaginator)
- `client.get_paginator("list_keys")` ->
  [ListKeysPaginator](./paginators.md#listkeyspaginator)
