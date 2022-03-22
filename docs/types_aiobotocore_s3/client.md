<a id="s3client-for-aiobotocore-s3-module"></a>

# S3Client for aiobotocore S3 module

> [Index](../README.md) > [S3](./README.md) > S3Client

Auto-generated documentation for
[S3](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3)
type annotations stubs module
[types-aiobotocore-s3](https://pypi.org/project/types-aiobotocore-s3/).

- [S3Client for aiobotocore S3 module](#s3client-for-aiobotocore-s3-module)
  - [S3Client](#s3client)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [abort_multipart_upload](#abort_multipart_upload)
    - [can_paginate](#can_paginate)
    - [complete_multipart_upload](#complete_multipart_upload)
    - [copy](#copy)
    - [copy_object](#copy_object)
    - [create_bucket](#create_bucket)
    - [create_multipart_upload](#create_multipart_upload)
    - [delete_bucket](#delete_bucket)
    - [delete_bucket_analytics_configuration](#delete_bucket_analytics_configuration)
    - [delete_bucket_cors](#delete_bucket_cors)
    - [delete_bucket_encryption](#delete_bucket_encryption)
    - [delete_bucket_intelligent_tiering_configuration](#delete_bucket_intelligent_tiering_configuration)
    - [delete_bucket_inventory_configuration](#delete_bucket_inventory_configuration)
    - [delete_bucket_lifecycle](#delete_bucket_lifecycle)
    - [delete_bucket_metrics_configuration](#delete_bucket_metrics_configuration)
    - [delete_bucket_ownership_controls](#delete_bucket_ownership_controls)
    - [delete_bucket_policy](#delete_bucket_policy)
    - [delete_bucket_replication](#delete_bucket_replication)
    - [delete_bucket_tagging](#delete_bucket_tagging)
    - [delete_bucket_website](#delete_bucket_website)
    - [delete_object](#delete_object)
    - [delete_object_tagging](#delete_object_tagging)
    - [delete_objects](#delete_objects)
    - [delete_public_access_block](#delete_public_access_block)
    - [download_file](#download_file)
    - [download_fileobj](#download_fileobj)
    - [generate_presigned_post](#generate_presigned_post)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_bucket_accelerate_configuration](#get_bucket_accelerate_configuration)
    - [get_bucket_acl](#get_bucket_acl)
    - [get_bucket_analytics_configuration](#get_bucket_analytics_configuration)
    - [get_bucket_cors](#get_bucket_cors)
    - [get_bucket_encryption](#get_bucket_encryption)
    - [get_bucket_intelligent_tiering_configuration](#get_bucket_intelligent_tiering_configuration)
    - [get_bucket_inventory_configuration](#get_bucket_inventory_configuration)
    - [get_bucket_lifecycle](#get_bucket_lifecycle)
    - [get_bucket_lifecycle_configuration](#get_bucket_lifecycle_configuration)
    - [get_bucket_location](#get_bucket_location)
    - [get_bucket_logging](#get_bucket_logging)
    - [get_bucket_metrics_configuration](#get_bucket_metrics_configuration)
    - [get_bucket_notification](#get_bucket_notification)
    - [get_bucket_notification_configuration](#get_bucket_notification_configuration)
    - [get_bucket_ownership_controls](#get_bucket_ownership_controls)
    - [get_bucket_policy](#get_bucket_policy)
    - [get_bucket_policy_status](#get_bucket_policy_status)
    - [get_bucket_replication](#get_bucket_replication)
    - [get_bucket_request_payment](#get_bucket_request_payment)
    - [get_bucket_tagging](#get_bucket_tagging)
    - [get_bucket_versioning](#get_bucket_versioning)
    - [get_bucket_website](#get_bucket_website)
    - [get_object](#get_object)
    - [get_object_acl](#get_object_acl)
    - [get_object_attributes](#get_object_attributes)
    - [get_object_legal_hold](#get_object_legal_hold)
    - [get_object_lock_configuration](#get_object_lock_configuration)
    - [get_object_retention](#get_object_retention)
    - [get_object_tagging](#get_object_tagging)
    - [get_object_torrent](#get_object_torrent)
    - [get_public_access_block](#get_public_access_block)
    - [head_bucket](#head_bucket)
    - [head_object](#head_object)
    - [list_bucket_analytics_configurations](#list_bucket_analytics_configurations)
    - [list_bucket_intelligent_tiering_configurations](#list_bucket_intelligent_tiering_configurations)
    - [list_bucket_inventory_configurations](#list_bucket_inventory_configurations)
    - [list_bucket_metrics_configurations](#list_bucket_metrics_configurations)
    - [list_buckets](#list_buckets)
    - [list_multipart_uploads](#list_multipart_uploads)
    - [list_object_versions](#list_object_versions)
    - [list_objects](#list_objects)
    - [list_objects_v2](#list_objects_v2)
    - [list_parts](#list_parts)
    - [put_bucket_accelerate_configuration](#put_bucket_accelerate_configuration)
    - [put_bucket_acl](#put_bucket_acl)
    - [put_bucket_analytics_configuration](#put_bucket_analytics_configuration)
    - [put_bucket_cors](#put_bucket_cors)
    - [put_bucket_encryption](#put_bucket_encryption)
    - [put_bucket_intelligent_tiering_configuration](#put_bucket_intelligent_tiering_configuration)
    - [put_bucket_inventory_configuration](#put_bucket_inventory_configuration)
    - [put_bucket_lifecycle](#put_bucket_lifecycle)
    - [put_bucket_lifecycle_configuration](#put_bucket_lifecycle_configuration)
    - [put_bucket_logging](#put_bucket_logging)
    - [put_bucket_metrics_configuration](#put_bucket_metrics_configuration)
    - [put_bucket_notification](#put_bucket_notification)
    - [put_bucket_notification_configuration](#put_bucket_notification_configuration)
    - [put_bucket_ownership_controls](#put_bucket_ownership_controls)
    - [put_bucket_policy](#put_bucket_policy)
    - [put_bucket_replication](#put_bucket_replication)
    - [put_bucket_request_payment](#put_bucket_request_payment)
    - [put_bucket_tagging](#put_bucket_tagging)
    - [put_bucket_versioning](#put_bucket_versioning)
    - [put_bucket_website](#put_bucket_website)
    - [put_object](#put_object)
    - [put_object_acl](#put_object_acl)
    - [put_object_legal_hold](#put_object_legal_hold)
    - [put_object_lock_configuration](#put_object_lock_configuration)
    - [put_object_retention](#put_object_retention)
    - [put_object_tagging](#put_object_tagging)
    - [put_public_access_block](#put_public_access_block)
    - [restore_object](#restore_object)
    - [select_object_content](#select_object_content)
    - [upload_file](#upload_file)
    - [upload_fileobj](#upload_fileobj)
    - [upload_part](#upload_part)
    - [upload_part_copy](#upload_part_copy)
    - [write_get_object_response](#write_get_object_response)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="s3client"></a>

## S3Client

Type annotations for `session.create_client("s3")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_s3.client import S3Client

session = get_session()
async with session.create_client("s3") as client:
    client: S3Client
```

Boto3 documentation:
[S3.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_s3.client import Exceptions

def handle_error(exc: Exceptions.BucketAlreadyExists) -> None:
    ...
```

Exceptions:

- `Exceptions.BucketAlreadyExists`
- `Exceptions.BucketAlreadyOwnedByYou`
- `Exceptions.ClientError`
- `Exceptions.InvalidObjectState`
- `Exceptions.NoSuchBucket`
- `Exceptions.NoSuchKey`
- `Exceptions.NoSuchUpload`
- `Exceptions.ObjectAlreadyInActiveTierError`
- `Exceptions.ObjectNotInActiveTierError`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

S3Client exceptions.

Type annotations for `session.create_client("s3").exceptions` method.

Boto3 documentation:
[S3.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="abort\_multipart\_upload"></a>

### abort_multipart_upload

This action aborts a multipart upload.

Type annotations for `session.create_client("s3").abort_multipart_upload`
method.

Boto3 documentation:
[S3.Client.abort_multipart_upload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.abort_multipart_upload)

Asynchronous method. Use `await abort_multipart_upload(...)` for a synchronous
call.

Arguments mapping described in
[AbortMultipartUploadRequestRequestTypeDef](./type_defs.md#abortmultipartuploadrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `UploadId`: `str` *(required)*
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[AbortMultipartUploadOutputTypeDef](./type_defs.md#abortmultipartuploadoutputtypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("s3").can_paginate` method.

Boto3 documentation:
[S3.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="complete\_multipart\_upload"></a>

### complete_multipart_upload

Completes a multipart upload by assembling previously uploaded parts.

Type annotations for `session.create_client("s3").complete_multipart_upload`
method.

Boto3 documentation:
[S3.Client.complete_multipart_upload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.complete_multipart_upload)

Asynchronous method. Use `await complete_multipart_upload(...)` for a
synchronous call.

Arguments mapping described in
[CompleteMultipartUploadRequestRequestTypeDef](./type_defs.md#completemultipartuploadrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `UploadId`: `str` *(required)*
- `MultipartUpload`:
  [CompletedMultipartUploadTypeDef](./type_defs.md#completedmultipartuploadtypedef)
- `ChecksumCRC32`: `str`
- `ChecksumCRC32C`: `str`
- `ChecksumSHA1`: `str`
- `ChecksumSHA256`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`

Returns a `Coroutine` for
[CompleteMultipartUploadOutputTypeDef](./type_defs.md#completemultipartuploadoutputtypedef).

<a id="copy"></a>

### copy

Copy an object from one S3 location to another.

Type annotations for `session.create_client("s3").copy` method.

Boto3 documentation:
[S3.Client.copy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.copy)

Asynchronous method. Use `await copy(...)` for a synchronous call.

Arguments mapping described in
[ClientCopyRequestTypeDef](./type_defs.md#clientcopyrequesttypedef).

Arguments:

- `CopySource`: [CopySourceTypeDef](./type_defs.md#copysourcetypedef)
  *(required)*
- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `ExtraArgs`: `Dict`\[`str`, `Any`\]
- `Callback`: `Callable`\[`...`, `Any`\]
- `SourceClient`: `BaseClient`
- `Config`: `TransferConfig`

<a id="copy\_object"></a>

### copy_object

Creates a copy of an object that is already stored in Amazon S3.

Type annotations for `session.create_client("s3").copy_object` method.

Boto3 documentation:
[S3.Client.copy_object](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.copy_object)

Asynchronous method. Use `await copy_object(...)` for a synchronous call.

Arguments mapping described in
[CopyObjectRequestRequestTypeDef](./type_defs.md#copyobjectrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `CopySource`: `Union`\[`str`,
  [CopySourceTypeDef](./type_defs.md#copysourcetypedef)\] *(required)*
- `Key`: `str` *(required)*
- `ACL`: [ObjectCannedACLType](./literals.md#objectcannedacltype)
- `CacheControl`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ContentDisposition`: `str`
- `ContentEncoding`: `str`
- `ContentLanguage`: `str`
- `ContentType`: `str`
- `CopySourceIfMatch`: `str`
- `CopySourceIfModifiedSince`: `Union`\[`datetime`, `str`\]
- `CopySourceIfNoneMatch`: `str`
- `CopySourceIfUnmodifiedSince`: `Union`\[`datetime`, `str`\]
- `Expires`: `Union`\[`datetime`, `str`\]
- `GrantFullControl`: `str`
- `GrantRead`: `str`
- `GrantReadACP`: `str`
- `GrantWriteACP`: `str`
- `Metadata`: `Mapping`\[`str`, `str`\]
- `MetadataDirective`:
  [MetadataDirectiveType](./literals.md#metadatadirectivetype)
- `TaggingDirective`:
  [TaggingDirectiveType](./literals.md#taggingdirectivetype)
- `ServerSideEncryption`:
  [ServerSideEncryptionType](./literals.md#serversideencryptiontype)
- `StorageClass`: [StorageClassType](./literals.md#storageclasstype)
- `WebsiteRedirectLocation`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `SSEKMSKeyId`: `str`
- `SSEKMSEncryptionContext`: `str`
- `BucketKeyEnabled`: `bool`
- `CopySourceSSECustomerAlgorithm`: `str`
- `CopySourceSSECustomerKey`: `str`
- `CopySourceSSECustomerKeyMD5`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `Tagging`: `str`
- `ObjectLockMode`: [ObjectLockModeType](./literals.md#objectlockmodetype)
- `ObjectLockRetainUntilDate`: `Union`\[`datetime`, `str`\]
- `ObjectLockLegalHoldStatus`:
  [ObjectLockLegalHoldStatusType](./literals.md#objectlocklegalholdstatustype)
- `ExpectedBucketOwner`: `str`
- `ExpectedSourceBucketOwner`: `str`

Returns a `Coroutine` for
[CopyObjectOutputTypeDef](./type_defs.md#copyobjectoutputtypedef).

<a id="create\_bucket"></a>

### create_bucket

Creates a new S3 bucket.

Type annotations for `session.create_client("s3").create_bucket` method.

Boto3 documentation:
[S3.Client.create_bucket](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.create_bucket)

Asynchronous method. Use `await create_bucket(...)` for a synchronous call.

Arguments mapping described in
[CreateBucketRequestRequestTypeDef](./type_defs.md#createbucketrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ACL`: [BucketCannedACLType](./literals.md#bucketcannedacltype)
- `CreateBucketConfiguration`:
  [CreateBucketConfigurationTypeDef](./type_defs.md#createbucketconfigurationtypedef)
- `GrantFullControl`: `str`
- `GrantRead`: `str`
- `GrantReadACP`: `str`
- `GrantWrite`: `str`
- `GrantWriteACP`: `str`
- `ObjectLockEnabledForBucket`: `bool`
- `ObjectOwnership`: [ObjectOwnershipType](./literals.md#objectownershiptype)

Returns a `Coroutine` for
[CreateBucketOutputTypeDef](./type_defs.md#createbucketoutputtypedef).

<a id="create\_multipart\_upload"></a>

### create_multipart_upload

This action initiates a multipart upload and returns an upload ID.

Type annotations for `session.create_client("s3").create_multipart_upload`
method.

Boto3 documentation:
[S3.Client.create_multipart_upload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.create_multipart_upload)

Asynchronous method. Use `await create_multipart_upload(...)` for a synchronous
call.

Arguments mapping described in
[CreateMultipartUploadRequestRequestTypeDef](./type_defs.md#createmultipartuploadrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `ACL`: [ObjectCannedACLType](./literals.md#objectcannedacltype)
- `CacheControl`: `str`
- `ContentDisposition`: `str`
- `ContentEncoding`: `str`
- `ContentLanguage`: `str`
- `ContentType`: `str`
- `Expires`: `Union`\[`datetime`, `str`\]
- `GrantFullControl`: `str`
- `GrantRead`: `str`
- `GrantReadACP`: `str`
- `GrantWriteACP`: `str`
- `Metadata`: `Mapping`\[`str`, `str`\]
- `ServerSideEncryption`:
  [ServerSideEncryptionType](./literals.md#serversideencryptiontype)
- `StorageClass`: [StorageClassType](./literals.md#storageclasstype)
- `WebsiteRedirectLocation`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `SSEKMSKeyId`: `str`
- `SSEKMSEncryptionContext`: `str`
- `BucketKeyEnabled`: `bool`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `Tagging`: `str`
- `ObjectLockMode`: [ObjectLockModeType](./literals.md#objectlockmodetype)
- `ObjectLockRetainUntilDate`: `Union`\[`datetime`, `str`\]
- `ObjectLockLegalHoldStatus`:
  [ObjectLockLegalHoldStatusType](./literals.md#objectlocklegalholdstatustype)
- `ExpectedBucketOwner`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)

Returns a `Coroutine` for
[CreateMultipartUploadOutputTypeDef](./type_defs.md#createmultipartuploadoutputtypedef).

<a id="delete\_bucket"></a>

### delete_bucket

Deletes the S3 bucket.

Type annotations for `session.create_client("s3").delete_bucket` method.

Boto3 documentation:
[S3.Client.delete_bucket](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket)

Asynchronous method. Use `await delete_bucket(...)` for a synchronous call.

Arguments mapping described in
[DeleteBucketRequestRequestTypeDef](./type_defs.md#deletebucketrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_analytics\_configuration"></a>

### delete_bucket_analytics_configuration

Deletes an analytics configuration for the bucket (specified by the analytics
configuration ID).

Type annotations for
`session.create_client("s3").delete_bucket_analytics_configuration` method.

Boto3 documentation:
[S3.Client.delete_bucket_analytics_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_analytics_configuration)

Asynchronous method. Use `await delete_bucket_analytics_configuration(...)` for
a synchronous call.

Arguments mapping described in
[DeleteBucketAnalyticsConfigurationRequestRequestTypeDef](./type_defs.md#deletebucketanalyticsconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_cors"></a>

### delete_bucket_cors

Deletes the `cors` configuration information set for the bucket.

Type annotations for `session.create_client("s3").delete_bucket_cors` method.

Boto3 documentation:
[S3.Client.delete_bucket_cors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_cors)

Asynchronous method. Use `await delete_bucket_cors(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketCorsRequestRequestTypeDef](./type_defs.md#deletebucketcorsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_encryption"></a>

### delete_bucket_encryption

This implementation of the DELETE action removes default encryption from the
bucket.

Type annotations for `session.create_client("s3").delete_bucket_encryption`
method.

Boto3 documentation:
[S3.Client.delete_bucket_encryption](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_encryption)

Asynchronous method. Use `await delete_bucket_encryption(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBucketEncryptionRequestRequestTypeDef](./type_defs.md#deletebucketencryptionrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_intelligent\_tiering\_configuration"></a>

### delete_bucket_intelligent_tiering_configuration

Deletes the S3 Intelligent-Tiering configuration from the specified bucket.

Type annotations for
`session.create_client("s3").delete_bucket_intelligent_tiering_configuration`
method.

Boto3 documentation:
[S3.Client.delete_bucket_intelligent_tiering_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_intelligent_tiering_configuration)

Asynchronous method. Use
`await delete_bucket_intelligent_tiering_configuration(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketIntelligentTieringConfigurationRequestRequestTypeDef](./type_defs.md#deletebucketintelligenttieringconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*

<a id="delete\_bucket\_inventory\_configuration"></a>

### delete_bucket_inventory_configuration

Deletes an inventory configuration (identified by the inventory ID) from the
bucket.

Type annotations for
`session.create_client("s3").delete_bucket_inventory_configuration` method.

Boto3 documentation:
[S3.Client.delete_bucket_inventory_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_inventory_configuration)

Asynchronous method. Use `await delete_bucket_inventory_configuration(...)` for
a synchronous call.

Arguments mapping described in
[DeleteBucketInventoryConfigurationRequestRequestTypeDef](./type_defs.md#deletebucketinventoryconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_lifecycle"></a>

### delete_bucket_lifecycle

Deletes the lifecycle configuration from the specified bucket.

Type annotations for `session.create_client("s3").delete_bucket_lifecycle`
method.

Boto3 documentation:
[S3.Client.delete_bucket_lifecycle](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_lifecycle)

Asynchronous method. Use `await delete_bucket_lifecycle(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketLifecycleRequestRequestTypeDef](./type_defs.md#deletebucketlifecyclerequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_metrics\_configuration"></a>

### delete_bucket_metrics_configuration

Deletes a metrics configuration for the Amazon CloudWatch request metrics
(specified by the metrics configuration ID) from the bucket.

Type annotations for
`session.create_client("s3").delete_bucket_metrics_configuration` method.

Boto3 documentation:
[S3.Client.delete_bucket_metrics_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_metrics_configuration)

Asynchronous method. Use `await delete_bucket_metrics_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBucketMetricsConfigurationRequestRequestTypeDef](./type_defs.md#deletebucketmetricsconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_ownership\_controls"></a>

### delete_bucket_ownership_controls

Removes `OwnershipControls` for an Amazon S3 bucket.

Type annotations for
`session.create_client("s3").delete_bucket_ownership_controls` method.

Boto3 documentation:
[S3.Client.delete_bucket_ownership_controls](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_ownership_controls)

Asynchronous method. Use `await delete_bucket_ownership_controls(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBucketOwnershipControlsRequestRequestTypeDef](./type_defs.md#deletebucketownershipcontrolsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_policy"></a>

### delete_bucket_policy

This implementation of the DELETE action uses the policy subresource to delete
the policy of a specified bucket.

Type annotations for `session.create_client("s3").delete_bucket_policy` method.

Boto3 documentation:
[S3.Client.delete_bucket_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_policy)

Asynchronous method. Use `await delete_bucket_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketPolicyRequestRequestTypeDef](./type_defs.md#deletebucketpolicyrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_replication"></a>

### delete_bucket_replication

Deletes the replication configuration from the bucket.

Type annotations for `session.create_client("s3").delete_bucket_replication`
method.

Boto3 documentation:
[S3.Client.delete_bucket_replication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_replication)

Asynchronous method. Use `await delete_bucket_replication(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBucketReplicationRequestRequestTypeDef](./type_defs.md#deletebucketreplicationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_tagging"></a>

### delete_bucket_tagging

Deletes the tags from the bucket.

Type annotations for `session.create_client("s3").delete_bucket_tagging`
method.

Boto3 documentation:
[S3.Client.delete_bucket_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_tagging)

Asynchronous method. Use `await delete_bucket_tagging(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketTaggingRequestRequestTypeDef](./type_defs.md#deletebuckettaggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_bucket\_website"></a>

### delete_bucket_website

This action removes the website configuration for a bucket.

Type annotations for `session.create_client("s3").delete_bucket_website`
method.

Boto3 documentation:
[S3.Client.delete_bucket_website](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_website)

Asynchronous method. Use `await delete_bucket_website(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketWebsiteRequestRequestTypeDef](./type_defs.md#deletebucketwebsiterequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="delete\_object"></a>

### delete_object

Removes the null version (if there is one) of an object and inserts a delete
marker, which becomes the latest version of the object.

Type annotations for `session.create_client("s3").delete_object` method.

Boto3 documentation:
[S3.Client.delete_object](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_object)

Asynchronous method. Use `await delete_object(...)` for a synchronous call.

Arguments mapping described in
[DeleteObjectRequestRequestTypeDef](./type_defs.md#deleteobjectrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `MFA`: `str`
- `VersionId`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `BypassGovernanceRetention`: `bool`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[DeleteObjectOutputTypeDef](./type_defs.md#deleteobjectoutputtypedef).

<a id="delete\_object\_tagging"></a>

### delete_object_tagging

Removes the entire tag set from the specified object.

Type annotations for `session.create_client("s3").delete_object_tagging`
method.

Boto3 documentation:
[S3.Client.delete_object_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_object_tagging)

Asynchronous method. Use `await delete_object_tagging(...)` for a synchronous
call.

Arguments mapping described in
[DeleteObjectTaggingRequestRequestTypeDef](./type_defs.md#deleteobjecttaggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `VersionId`: `str`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[DeleteObjectTaggingOutputTypeDef](./type_defs.md#deleteobjecttaggingoutputtypedef).

<a id="delete\_objects"></a>

### delete_objects

This action enables you to delete multiple objects from a bucket using a single
HTTP request.

Type annotations for `session.create_client("s3").delete_objects` method.

Boto3 documentation:
[S3.Client.delete_objects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_objects)

Asynchronous method. Use `await delete_objects(...)` for a synchronous call.

Arguments mapping described in
[DeleteObjectsRequestRequestTypeDef](./type_defs.md#deleteobjectsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Delete`: [DeleteTypeDef](./type_defs.md#deletetypedef) *(required)*
- `MFA`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `BypassGovernanceRetention`: `bool`
- `ExpectedBucketOwner`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)

Returns a `Coroutine` for
[DeleteObjectsOutputTypeDef](./type_defs.md#deleteobjectsoutputtypedef).

<a id="delete\_public\_access\_block"></a>

### delete_public_access_block

Removes the `PublicAccessBlock` configuration for an Amazon S3 bucket.

Type annotations for `session.create_client("s3").delete_public_access_block`
method.

Boto3 documentation:
[S3.Client.delete_public_access_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_public_access_block)

Asynchronous method. Use `await delete_public_access_block(...)` for a
synchronous call.

Arguments mapping described in
[DeletePublicAccessBlockRequestRequestTypeDef](./type_defs.md#deletepublicaccessblockrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="download\_file"></a>

### download_file

Download an S3 object to a file.

Type annotations for `session.create_client("s3").download_file` method.

Boto3 documentation:
[S3.Client.download_file](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.download_file)

Asynchronous method. Use `await download_file(...)` for a synchronous call.

Arguments mapping described in
[ClientDownloadFileRequestTypeDef](./type_defs.md#clientdownloadfilerequesttypedef).

Arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `Filename`: `str` *(required)*
- `ExtraArgs`: `Dict`\[`str`, `Any`\]
- `Callback`: `Callable`\[`...`, `Any`\]
- `Config`: `TransferConfig`

<a id="download\_fileobj"></a>

### download_fileobj

Download an object from S3 to a file-like object.

Type annotations for `session.create_client("s3").download_fileobj` method.

Boto3 documentation:
[S3.Client.download_fileobj](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.download_fileobj)

Asynchronous method. Use `await download_fileobj(...)` for a synchronous call.

Arguments mapping described in
[ClientDownloadFileobjRequestTypeDef](./type_defs.md#clientdownloadfileobjrequesttypedef).

Arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `Fileobj`: `Union`\[`IO`\[`Any`\], `StreamingBody`\] *(required)*
- `ExtraArgs`: `Dict`\[`str`, `Any`\]
- `Callback`: `Callable`\[`...`, `Any`\]
- `Config`: `TransferConfig`

<a id="generate\_presigned\_post"></a>

### generate_presigned_post

Builds the url and the form fields used for a presigned s3 post.

Type annotations for `session.create_client("s3").generate_presigned_post`
method.

Boto3 documentation:
[S3.Client.generate_presigned_post](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.generate_presigned_post)

Asynchronous method. Use `await generate_presigned_post(...)` for a synchronous
call.

Arguments mapping described in
[ClientGeneratePresignedPostRequestTypeDef](./type_defs.md#clientgeneratepresignedpostrequesttypedef).

Arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `Fields`: `Dict`\[`str`, `Any`\]
- `Conditions`: `List`\[`Any`\]
- `ExpiresIn`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("s3").generate_presigned_url`
method.

Boto3 documentation:
[S3.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_bucket\_accelerate\_configuration"></a>

### get_bucket_accelerate_configuration

This implementation of the GET action uses the `accelerate` subresource to
return the Transfer Acceleration state of a bucket, which is either `Enabled`
or `Suspended`.

Type annotations for
`session.create_client("s3").get_bucket_accelerate_configuration` method.

Boto3 documentation:
[S3.Client.get_bucket_accelerate_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_accelerate_configuration)

Asynchronous method. Use `await get_bucket_accelerate_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketAccelerateConfigurationRequestRequestTypeDef](./type_defs.md#getbucketaccelerateconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketAccelerateConfigurationOutputTypeDef](./type_defs.md#getbucketaccelerateconfigurationoutputtypedef).

<a id="get\_bucket\_acl"></a>

### get_bucket_acl

This implementation of the `GET` action uses the `acl` subresource to return
the access control list (ACL) of a bucket.

Type annotations for `session.create_client("s3").get_bucket_acl` method.

Boto3 documentation:
[S3.Client.get_bucket_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_acl)

Asynchronous method. Use `await get_bucket_acl(...)` for a synchronous call.

Arguments mapping described in
[GetBucketAclRequestRequestTypeDef](./type_defs.md#getbucketaclrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketAclOutputTypeDef](./type_defs.md#getbucketacloutputtypedef).

<a id="get\_bucket\_analytics\_configuration"></a>

### get_bucket_analytics_configuration

This implementation of the GET action returns an analytics configuration
(identified by the analytics configuration ID) from the bucket.

Type annotations for
`session.create_client("s3").get_bucket_analytics_configuration` method.

Boto3 documentation:
[S3.Client.get_bucket_analytics_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_analytics_configuration)

Asynchronous method. Use `await get_bucket_analytics_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketAnalyticsConfigurationRequestRequestTypeDef](./type_defs.md#getbucketanalyticsconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketAnalyticsConfigurationOutputTypeDef](./type_defs.md#getbucketanalyticsconfigurationoutputtypedef).

<a id="get\_bucket\_cors"></a>

### get_bucket_cors

Returns the Cross-Origin Resource Sharing (CORS) configuration information set
for the bucket.

Type annotations for `session.create_client("s3").get_bucket_cors` method.

Boto3 documentation:
[S3.Client.get_bucket_cors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_cors)

Asynchronous method. Use `await get_bucket_cors(...)` for a synchronous call.

Arguments mapping described in
[GetBucketCorsRequestRequestTypeDef](./type_defs.md#getbucketcorsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketCorsOutputTypeDef](./type_defs.md#getbucketcorsoutputtypedef).

<a id="get\_bucket\_encryption"></a>

### get_bucket_encryption

Returns the default encryption configuration for an Amazon S3 bucket.

Type annotations for `session.create_client("s3").get_bucket_encryption`
method.

Boto3 documentation:
[S3.Client.get_bucket_encryption](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_encryption)

Asynchronous method. Use `await get_bucket_encryption(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketEncryptionRequestRequestTypeDef](./type_defs.md#getbucketencryptionrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketEncryptionOutputTypeDef](./type_defs.md#getbucketencryptionoutputtypedef).

<a id="get\_bucket\_intelligent\_tiering\_configuration"></a>

### get_bucket_intelligent_tiering_configuration

Gets the S3 Intelligent-Tiering configuration from the specified bucket.

Type annotations for
`session.create_client("s3").get_bucket_intelligent_tiering_configuration`
method.

Boto3 documentation:
[S3.Client.get_bucket_intelligent_tiering_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_intelligent_tiering_configuration)

Asynchronous method. Use
`await get_bucket_intelligent_tiering_configuration(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketIntelligentTieringConfigurationRequestRequestTypeDef](./type_defs.md#getbucketintelligenttieringconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*

Returns a `Coroutine` for
[GetBucketIntelligentTieringConfigurationOutputTypeDef](./type_defs.md#getbucketintelligenttieringconfigurationoutputtypedef).

<a id="get\_bucket\_inventory\_configuration"></a>

### get_bucket_inventory_configuration

Returns an inventory configuration (identified by the inventory configuration
ID) from the bucket.

Type annotations for
`session.create_client("s3").get_bucket_inventory_configuration` method.

Boto3 documentation:
[S3.Client.get_bucket_inventory_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_inventory_configuration)

Asynchronous method. Use `await get_bucket_inventory_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketInventoryConfigurationRequestRequestTypeDef](./type_defs.md#getbucketinventoryconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketInventoryConfigurationOutputTypeDef](./type_defs.md#getbucketinventoryconfigurationoutputtypedef).

<a id="get\_bucket\_lifecycle"></a>

### get_bucket_lifecycle

.

Type annotations for `session.create_client("s3").get_bucket_lifecycle` method.

Boto3 documentation:
[S3.Client.get_bucket_lifecycle](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_lifecycle)

Asynchronous method. Use `await get_bucket_lifecycle(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketLifecycleRequestRequestTypeDef](./type_defs.md#getbucketlifecyclerequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketLifecycleOutputTypeDef](./type_defs.md#getbucketlifecycleoutputtypedef).

<a id="get\_bucket\_lifecycle\_configuration"></a>

### get_bucket_lifecycle_configuration

.

Type annotations for
`session.create_client("s3").get_bucket_lifecycle_configuration` method.

Boto3 documentation:
[S3.Client.get_bucket_lifecycle_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_lifecycle_configuration)

Asynchronous method. Use `await get_bucket_lifecycle_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketLifecycleConfigurationRequestRequestTypeDef](./type_defs.md#getbucketlifecycleconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketLifecycleConfigurationOutputTypeDef](./type_defs.md#getbucketlifecycleconfigurationoutputtypedef).

<a id="get\_bucket\_location"></a>

### get_bucket_location

Returns the Region the bucket resides in.

Type annotations for `session.create_client("s3").get_bucket_location` method.

Boto3 documentation:
[S3.Client.get_bucket_location](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_location)

Asynchronous method. Use `await get_bucket_location(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketLocationRequestRequestTypeDef](./type_defs.md#getbucketlocationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketLocationOutputTypeDef](./type_defs.md#getbucketlocationoutputtypedef).

<a id="get\_bucket\_logging"></a>

### get_bucket_logging

Returns the logging status of a bucket and the permissions users have to view
and modify that status.

Type annotations for `session.create_client("s3").get_bucket_logging` method.

Boto3 documentation:
[S3.Client.get_bucket_logging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_logging)

Asynchronous method. Use `await get_bucket_logging(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketLoggingRequestRequestTypeDef](./type_defs.md#getbucketloggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketLoggingOutputTypeDef](./type_defs.md#getbucketloggingoutputtypedef).

<a id="get\_bucket\_metrics\_configuration"></a>

### get_bucket_metrics_configuration

Gets a metrics configuration (specified by the metrics configuration ID) from
the bucket.

Type annotations for
`session.create_client("s3").get_bucket_metrics_configuration` method.

Boto3 documentation:
[S3.Client.get_bucket_metrics_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_metrics_configuration)

Asynchronous method. Use `await get_bucket_metrics_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketMetricsConfigurationRequestRequestTypeDef](./type_defs.md#getbucketmetricsconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketMetricsConfigurationOutputTypeDef](./type_defs.md#getbucketmetricsconfigurationoutputtypedef).

<a id="get\_bucket\_notification"></a>

### get_bucket_notification

No longer used, see
[GetBucketNotificationConfiguration](https://docs.aws.amazon.com/AmazonS3/latest/API/API_GetBucketNotificationConfiguration.html)\_
.

Type annotations for `session.create_client("s3").get_bucket_notification`
method.

Boto3 documentation:
[S3.Client.get_bucket_notification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_notification)

Asynchronous method. Use `await get_bucket_notification(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketNotificationConfigurationRequestRequestTypeDef](./type_defs.md#getbucketnotificationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[NotificationConfigurationDeprecatedResponseMetadataTypeDef](./type_defs.md#notificationconfigurationdeprecatedresponsemetadatatypedef).

<a id="get\_bucket\_notification\_configuration"></a>

### get_bucket_notification_configuration

Returns the notification configuration of a bucket.

Type annotations for
`session.create_client("s3").get_bucket_notification_configuration` method.

Boto3 documentation:
[S3.Client.get_bucket_notification_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_notification_configuration)

Asynchronous method. Use `await get_bucket_notification_configuration(...)` for
a synchronous call.

Arguments mapping described in
[GetBucketNotificationConfigurationRequestRequestTypeDef](./type_defs.md#getbucketnotificationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[NotificationConfigurationResponseMetadataTypeDef](./type_defs.md#notificationconfigurationresponsemetadatatypedef).

<a id="get\_bucket\_ownership\_controls"></a>

### get_bucket_ownership_controls

Retrieves `OwnershipControls` for an Amazon S3 bucket.

Type annotations for
`session.create_client("s3").get_bucket_ownership_controls` method.

Boto3 documentation:
[S3.Client.get_bucket_ownership_controls](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_ownership_controls)

Asynchronous method. Use `await get_bucket_ownership_controls(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketOwnershipControlsRequestRequestTypeDef](./type_defs.md#getbucketownershipcontrolsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketOwnershipControlsOutputTypeDef](./type_defs.md#getbucketownershipcontrolsoutputtypedef).

<a id="get\_bucket\_policy"></a>

### get_bucket_policy

Returns the policy of a specified bucket.

Type annotations for `session.create_client("s3").get_bucket_policy` method.

Boto3 documentation:
[S3.Client.get_bucket_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_policy)

Asynchronous method. Use `await get_bucket_policy(...)` for a synchronous call.

Arguments mapping described in
[GetBucketPolicyRequestRequestTypeDef](./type_defs.md#getbucketpolicyrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketPolicyOutputTypeDef](./type_defs.md#getbucketpolicyoutputtypedef).

<a id="get\_bucket\_policy\_status"></a>

### get_bucket_policy_status

Retrieves the policy status for an Amazon S3 bucket, indicating whether the
bucket is public.

Type annotations for `session.create_client("s3").get_bucket_policy_status`
method.

Boto3 documentation:
[S3.Client.get_bucket_policy_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_policy_status)

Asynchronous method. Use `await get_bucket_policy_status(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketPolicyStatusRequestRequestTypeDef](./type_defs.md#getbucketpolicystatusrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketPolicyStatusOutputTypeDef](./type_defs.md#getbucketpolicystatusoutputtypedef).

<a id="get\_bucket\_replication"></a>

### get_bucket_replication

Returns the replication configuration of a bucket.

Type annotations for `session.create_client("s3").get_bucket_replication`
method.

Boto3 documentation:
[S3.Client.get_bucket_replication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_replication)

Asynchronous method. Use `await get_bucket_replication(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketReplicationRequestRequestTypeDef](./type_defs.md#getbucketreplicationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketReplicationOutputTypeDef](./type_defs.md#getbucketreplicationoutputtypedef).

<a id="get\_bucket\_request\_payment"></a>

### get_bucket_request_payment

Returns the request payment configuration of a bucket.

Type annotations for `session.create_client("s3").get_bucket_request_payment`
method.

Boto3 documentation:
[S3.Client.get_bucket_request_payment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_request_payment)

Asynchronous method. Use `await get_bucket_request_payment(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketRequestPaymentRequestRequestTypeDef](./type_defs.md#getbucketrequestpaymentrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketRequestPaymentOutputTypeDef](./type_defs.md#getbucketrequestpaymentoutputtypedef).

<a id="get\_bucket\_tagging"></a>

### get_bucket_tagging

Returns the tag set associated with the bucket.

Type annotations for `session.create_client("s3").get_bucket_tagging` method.

Boto3 documentation:
[S3.Client.get_bucket_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_tagging)

Asynchronous method. Use `await get_bucket_tagging(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketTaggingRequestRequestTypeDef](./type_defs.md#getbuckettaggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketTaggingOutputTypeDef](./type_defs.md#getbuckettaggingoutputtypedef).

<a id="get\_bucket\_versioning"></a>

### get_bucket_versioning

Returns the versioning state of a bucket.

Type annotations for `session.create_client("s3").get_bucket_versioning`
method.

Boto3 documentation:
[S3.Client.get_bucket_versioning](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_versioning)

Asynchronous method. Use `await get_bucket_versioning(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketVersioningRequestRequestTypeDef](./type_defs.md#getbucketversioningrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketVersioningOutputTypeDef](./type_defs.md#getbucketversioningoutputtypedef).

<a id="get\_bucket\_website"></a>

### get_bucket_website

Returns the website configuration for a bucket.

Type annotations for `session.create_client("s3").get_bucket_website` method.

Boto3 documentation:
[S3.Client.get_bucket_website](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_website)

Asynchronous method. Use `await get_bucket_website(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketWebsiteRequestRequestTypeDef](./type_defs.md#getbucketwebsiterequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetBucketWebsiteOutputTypeDef](./type_defs.md#getbucketwebsiteoutputtypedef).

<a id="get\_object"></a>

### get_object

Retrieves objects from Amazon S3.

Type annotations for `session.create_client("s3").get_object` method.

Boto3 documentation:
[S3.Client.get_object](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object)

Asynchronous method. Use `await get_object(...)` for a synchronous call.

Arguments mapping described in
[GetObjectRequestRequestTypeDef](./type_defs.md#getobjectrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `IfMatch`: `str`
- `IfModifiedSince`: `Union`\[`datetime`, `str`\]
- `IfNoneMatch`: `str`
- `IfUnmodifiedSince`: `Union`\[`datetime`, `str`\]
- `Range`: `str`
- `ResponseCacheControl`: `str`
- `ResponseContentDisposition`: `str`
- `ResponseContentEncoding`: `str`
- `ResponseContentLanguage`: `str`
- `ResponseContentType`: `str`
- `ResponseExpires`: `Union`\[`datetime`, `str`\]
- `VersionId`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `PartNumber`: `int`
- `ExpectedBucketOwner`: `str`
- `ChecksumMode`: `Literal['ENABLED']` (see
  [ChecksumModeType](./literals.md#checksummodetype))

Returns a `Coroutine` for
[GetObjectOutputTypeDef](./type_defs.md#getobjectoutputtypedef).

<a id="get\_object\_acl"></a>

### get_object_acl

Returns the access control list (ACL) of an object.

Type annotations for `session.create_client("s3").get_object_acl` method.

Boto3 documentation:
[S3.Client.get_object_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object_acl)

Asynchronous method. Use `await get_object_acl(...)` for a synchronous call.

Arguments mapping described in
[GetObjectAclRequestRequestTypeDef](./type_defs.md#getobjectaclrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `VersionId`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetObjectAclOutputTypeDef](./type_defs.md#getobjectacloutputtypedef).

<a id="get\_object\_attributes"></a>

### get_object_attributes

Retrieves all the metadata from an object without returning the object itself.

Type annotations for `session.create_client("s3").get_object_attributes`
method.

Boto3 documentation:
[S3.Client.get_object_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object_attributes)

Asynchronous method. Use `await get_object_attributes(...)` for a synchronous
call.

Arguments mapping described in
[GetObjectAttributesRequestRequestTypeDef](./type_defs.md#getobjectattributesrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `ObjectAttributes`:
  `Sequence`\[[ObjectAttributesType](./literals.md#objectattributestype)\]
  *(required)*
- `VersionId`: `str`
- `MaxParts`: `int`
- `PartNumberMarker`: `int`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetObjectAttributesOutputTypeDef](./type_defs.md#getobjectattributesoutputtypedef).

<a id="get\_object\_legal\_hold"></a>

### get_object_legal_hold

Gets an object's current legal hold status.

Type annotations for `session.create_client("s3").get_object_legal_hold`
method.

Boto3 documentation:
[S3.Client.get_object_legal_hold](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object_legal_hold)

Asynchronous method. Use `await get_object_legal_hold(...)` for a synchronous
call.

Arguments mapping described in
[GetObjectLegalHoldRequestRequestTypeDef](./type_defs.md#getobjectlegalholdrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `VersionId`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetObjectLegalHoldOutputTypeDef](./type_defs.md#getobjectlegalholdoutputtypedef).

<a id="get\_object\_lock\_configuration"></a>

### get_object_lock_configuration

Gets the Object Lock configuration for a bucket.

Type annotations for
`session.create_client("s3").get_object_lock_configuration` method.

Boto3 documentation:
[S3.Client.get_object_lock_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object_lock_configuration)

Asynchronous method. Use `await get_object_lock_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetObjectLockConfigurationRequestRequestTypeDef](./type_defs.md#getobjectlockconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetObjectLockConfigurationOutputTypeDef](./type_defs.md#getobjectlockconfigurationoutputtypedef).

<a id="get\_object\_retention"></a>

### get_object_retention

Retrieves an object's retention settings.

Type annotations for `session.create_client("s3").get_object_retention` method.

Boto3 documentation:
[S3.Client.get_object_retention](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object_retention)

Asynchronous method. Use `await get_object_retention(...)` for a synchronous
call.

Arguments mapping described in
[GetObjectRetentionRequestRequestTypeDef](./type_defs.md#getobjectretentionrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `VersionId`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetObjectRetentionOutputTypeDef](./type_defs.md#getobjectretentionoutputtypedef).

<a id="get\_object\_tagging"></a>

### get_object_tagging

Returns the tag-set of an object.

Type annotations for `session.create_client("s3").get_object_tagging` method.

Boto3 documentation:
[S3.Client.get_object_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object_tagging)

Asynchronous method. Use `await get_object_tagging(...)` for a synchronous
call.

Arguments mapping described in
[GetObjectTaggingRequestRequestTypeDef](./type_defs.md#getobjecttaggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `VersionId`: `str`
- `ExpectedBucketOwner`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))

Returns a `Coroutine` for
[GetObjectTaggingOutputTypeDef](./type_defs.md#getobjecttaggingoutputtypedef).

<a id="get\_object\_torrent"></a>

### get_object_torrent

Returns torrent files from a bucket.

Type annotations for `session.create_client("s3").get_object_torrent` method.

Boto3 documentation:
[S3.Client.get_object_torrent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_object_torrent)

Asynchronous method. Use `await get_object_torrent(...)` for a synchronous
call.

Arguments mapping described in
[GetObjectTorrentRequestRequestTypeDef](./type_defs.md#getobjecttorrentrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetObjectTorrentOutputTypeDef](./type_defs.md#getobjecttorrentoutputtypedef).

<a id="get\_public\_access\_block"></a>

### get_public_access_block

Retrieves the `PublicAccessBlock` configuration for an Amazon S3 bucket.

Type annotations for `session.create_client("s3").get_public_access_block`
method.

Boto3 documentation:
[S3.Client.get_public_access_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_public_access_block)

Asynchronous method. Use `await get_public_access_block(...)` for a synchronous
call.

Arguments mapping described in
[GetPublicAccessBlockRequestRequestTypeDef](./type_defs.md#getpublicaccessblockrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[GetPublicAccessBlockOutputTypeDef](./type_defs.md#getpublicaccessblockoutputtypedef).

<a id="head\_bucket"></a>

### head_bucket

This action is useful to determine if a bucket exists and you have permission
to access it.

Type annotations for `session.create_client("s3").head_bucket` method.

Boto3 documentation:
[S3.Client.head_bucket](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.head_bucket)

Asynchronous method. Use `await head_bucket(...)` for a synchronous call.

Arguments mapping described in
[HeadBucketRequestRequestTypeDef](./type_defs.md#headbucketrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ExpectedBucketOwner`: `str`

<a id="head\_object"></a>

### head_object

The HEAD action retrieves metadata from an object without returning the object
itself.

Type annotations for `session.create_client("s3").head_object` method.

Boto3 documentation:
[S3.Client.head_object](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.head_object)

Asynchronous method. Use `await head_object(...)` for a synchronous call.

Arguments mapping described in
[HeadObjectRequestRequestTypeDef](./type_defs.md#headobjectrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `IfMatch`: `str`
- `IfModifiedSince`: `Union`\[`datetime`, `str`\]
- `IfNoneMatch`: `str`
- `IfUnmodifiedSince`: `Union`\[`datetime`, `str`\]
- `Range`: `str`
- `VersionId`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `PartNumber`: `int`
- `ExpectedBucketOwner`: `str`
- `ChecksumMode`: `Literal['ENABLED']` (see
  [ChecksumModeType](./literals.md#checksummodetype))

Returns a `Coroutine` for
[HeadObjectOutputTypeDef](./type_defs.md#headobjectoutputtypedef).

<a id="list\_bucket\_analytics\_configurations"></a>

### list_bucket_analytics_configurations

Lists the analytics configurations for the bucket.

Type annotations for
`session.create_client("s3").list_bucket_analytics_configurations` method.

Boto3 documentation:
[S3.Client.list_bucket_analytics_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_bucket_analytics_configurations)

Asynchronous method. Use `await list_bucket_analytics_configurations(...)` for
a synchronous call.

Arguments mapping described in
[ListBucketAnalyticsConfigurationsRequestRequestTypeDef](./type_defs.md#listbucketanalyticsconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ContinuationToken`: `str`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[ListBucketAnalyticsConfigurationsOutputTypeDef](./type_defs.md#listbucketanalyticsconfigurationsoutputtypedef).

<a id="list\_bucket\_intelligent\_tiering\_configurations"></a>

### list_bucket_intelligent_tiering_configurations

Lists the S3 Intelligent-Tiering configuration from the specified bucket.

Type annotations for
`session.create_client("s3").list_bucket_intelligent_tiering_configurations`
method.

Boto3 documentation:
[S3.Client.list_bucket_intelligent_tiering_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_bucket_intelligent_tiering_configurations)

Asynchronous method. Use
`await list_bucket_intelligent_tiering_configurations(...)` for a synchronous
call.

Arguments mapping described in
[ListBucketIntelligentTieringConfigurationsRequestRequestTypeDef](./type_defs.md#listbucketintelligenttieringconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ContinuationToken`: `str`

Returns a `Coroutine` for
[ListBucketIntelligentTieringConfigurationsOutputTypeDef](./type_defs.md#listbucketintelligenttieringconfigurationsoutputtypedef).

<a id="list\_bucket\_inventory\_configurations"></a>

### list_bucket_inventory_configurations

Returns a list of inventory configurations for the bucket.

Type annotations for
`session.create_client("s3").list_bucket_inventory_configurations` method.

Boto3 documentation:
[S3.Client.list_bucket_inventory_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_bucket_inventory_configurations)

Asynchronous method. Use `await list_bucket_inventory_configurations(...)` for
a synchronous call.

Arguments mapping described in
[ListBucketInventoryConfigurationsRequestRequestTypeDef](./type_defs.md#listbucketinventoryconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ContinuationToken`: `str`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[ListBucketInventoryConfigurationsOutputTypeDef](./type_defs.md#listbucketinventoryconfigurationsoutputtypedef).

<a id="list\_bucket\_metrics\_configurations"></a>

### list_bucket_metrics_configurations

Lists the metrics configurations for the bucket.

Type annotations for
`session.create_client("s3").list_bucket_metrics_configurations` method.

Boto3 documentation:
[S3.Client.list_bucket_metrics_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_bucket_metrics_configurations)

Asynchronous method. Use `await list_bucket_metrics_configurations(...)` for a
synchronous call.

Arguments mapping described in
[ListBucketMetricsConfigurationsRequestRequestTypeDef](./type_defs.md#listbucketmetricsconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ContinuationToken`: `str`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[ListBucketMetricsConfigurationsOutputTypeDef](./type_defs.md#listbucketmetricsconfigurationsoutputtypedef).

<a id="list\_buckets"></a>

### list_buckets

Returns a list of all buckets owned by the authenticated sender of the request.

Type annotations for `session.create_client("s3").list_buckets` method.

Boto3 documentation:
[S3.Client.list_buckets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_buckets)

Asynchronous method. Use `await list_buckets(...)` for a synchronous call.

Returns a `Coroutine` for
[ListBucketsOutputTypeDef](./type_defs.md#listbucketsoutputtypedef).

<a id="list\_multipart\_uploads"></a>

### list_multipart_uploads

This action lists in-progress multipart uploads.

Type annotations for `session.create_client("s3").list_multipart_uploads`
method.

Boto3 documentation:
[S3.Client.list_multipart_uploads](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_multipart_uploads)

Asynchronous method. Use `await list_multipart_uploads(...)` for a synchronous
call.

Arguments mapping described in
[ListMultipartUploadsRequestRequestTypeDef](./type_defs.md#listmultipartuploadsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Delimiter`: `str`
- `EncodingType`: `Literal['url']` (see
  [EncodingTypeType](./literals.md#encodingtypetype))
- `KeyMarker`: `str`
- `MaxUploads`: `int`
- `Prefix`: `str`
- `UploadIdMarker`: `str`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[ListMultipartUploadsOutputTypeDef](./type_defs.md#listmultipartuploadsoutputtypedef).

<a id="list\_object\_versions"></a>

### list_object_versions

Returns metadata about all versions of the objects in a bucket.

Type annotations for `session.create_client("s3").list_object_versions` method.

Boto3 documentation:
[S3.Client.list_object_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_object_versions)

Asynchronous method. Use `await list_object_versions(...)` for a synchronous
call.

Arguments mapping described in
[ListObjectVersionsRequestRequestTypeDef](./type_defs.md#listobjectversionsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Delimiter`: `str`
- `EncodingType`: `Literal['url']` (see
  [EncodingTypeType](./literals.md#encodingtypetype))
- `KeyMarker`: `str`
- `MaxKeys`: `int`
- `Prefix`: `str`
- `VersionIdMarker`: `str`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[ListObjectVersionsOutputTypeDef](./type_defs.md#listobjectversionsoutputtypedef).

<a id="list\_objects"></a>

### list_objects

Returns some or all (up to 1,000) of the objects in a bucket.

Type annotations for `session.create_client("s3").list_objects` method.

Boto3 documentation:
[S3.Client.list_objects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_objects)

Asynchronous method. Use `await list_objects(...)` for a synchronous call.

Arguments mapping described in
[ListObjectsRequestRequestTypeDef](./type_defs.md#listobjectsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Delimiter`: `str`
- `EncodingType`: `Literal['url']` (see
  [EncodingTypeType](./literals.md#encodingtypetype))
- `Marker`: `str`
- `MaxKeys`: `int`
- `Prefix`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[ListObjectsOutputTypeDef](./type_defs.md#listobjectsoutputtypedef).

<a id="list\_objects\_v2"></a>

### list_objects_v2

Returns some or all (up to 1,000) of the objects in a bucket with each request.

Type annotations for `session.create_client("s3").list_objects_v2` method.

Boto3 documentation:
[S3.Client.list_objects_v2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_objects_v2)

Asynchronous method. Use `await list_objects_v2(...)` for a synchronous call.

Arguments mapping described in
[ListObjectsV2RequestRequestTypeDef](./type_defs.md#listobjectsv2requestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Delimiter`: `str`
- `EncodingType`: `Literal['url']` (see
  [EncodingTypeType](./literals.md#encodingtypetype))
- `MaxKeys`: `int`
- `Prefix`: `str`
- `ContinuationToken`: `str`
- `FetchOwner`: `bool`
- `StartAfter`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[ListObjectsV2OutputTypeDef](./type_defs.md#listobjectsv2outputtypedef).

<a id="list\_parts"></a>

### list_parts

Lists the parts that have been uploaded for a specific multipart upload.

Type annotations for `session.create_client("s3").list_parts` method.

Boto3 documentation:
[S3.Client.list_parts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_parts)

Asynchronous method. Use `await list_parts(...)` for a synchronous call.

Arguments mapping described in
[ListPartsRequestRequestTypeDef](./type_defs.md#listpartsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `UploadId`: `str` *(required)*
- `MaxParts`: `int`
- `PartNumberMarker`: `int`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`

Returns a `Coroutine` for
[ListPartsOutputTypeDef](./type_defs.md#listpartsoutputtypedef).

<a id="put\_bucket\_accelerate\_configuration"></a>

### put_bucket_accelerate_configuration

Sets the accelerate configuration of an existing bucket.

Type annotations for
`session.create_client("s3").put_bucket_accelerate_configuration` method.

Boto3 documentation:
[S3.Client.put_bucket_accelerate_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_accelerate_configuration)

Asynchronous method. Use `await put_bucket_accelerate_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketAccelerateConfigurationRequestRequestTypeDef](./type_defs.md#putbucketaccelerateconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `AccelerateConfiguration`:
  [AccelerateConfigurationTypeDef](./type_defs.md#accelerateconfigurationtypedef)
  *(required)*
- `ExpectedBucketOwner`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)

<a id="put\_bucket\_acl"></a>

### put_bucket_acl

Sets the permissions on an existing bucket using access control lists (ACL).

Type annotations for `session.create_client("s3").put_bucket_acl` method.

Boto3 documentation:
[S3.Client.put_bucket_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_acl)

Asynchronous method. Use `await put_bucket_acl(...)` for a synchronous call.

Arguments mapping described in
[PutBucketAclRequestRequestTypeDef](./type_defs.md#putbucketaclrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ACL`: [BucketCannedACLType](./literals.md#bucketcannedacltype)
- `AccessControlPolicy`:
  [AccessControlPolicyTypeDef](./type_defs.md#accesscontrolpolicytypedef)
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `GrantFullControl`: `str`
- `GrantRead`: `str`
- `GrantReadACP`: `str`
- `GrantWrite`: `str`
- `GrantWriteACP`: `str`
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_analytics\_configuration"></a>

### put_bucket_analytics_configuration

Sets an analytics configuration for the bucket (specified by the analytics
configuration ID).

Type annotations for
`session.create_client("s3").put_bucket_analytics_configuration` method.

Boto3 documentation:
[S3.Client.put_bucket_analytics_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_analytics_configuration)

Asynchronous method. Use `await put_bucket_analytics_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketAnalyticsConfigurationRequestRequestTypeDef](./type_defs.md#putbucketanalyticsconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `AnalyticsConfiguration`:
  [AnalyticsConfigurationTypeDef](./type_defs.md#analyticsconfigurationtypedef)
  *(required)*
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_cors"></a>

### put_bucket_cors

Sets the `cors` configuration for your bucket.

Type annotations for `session.create_client("s3").put_bucket_cors` method.

Boto3 documentation:
[S3.Client.put_bucket_cors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_cors)

Asynchronous method. Use `await put_bucket_cors(...)` for a synchronous call.

Arguments mapping described in
[PutBucketCorsRequestRequestTypeDef](./type_defs.md#putbucketcorsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `CORSConfiguration`:
  [CORSConfigurationTypeDef](./type_defs.md#corsconfigurationtypedef)
  *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_encryption"></a>

### put_bucket_encryption

This action uses the `encryption` subresource to configure default encryption
and Amazon S3 Bucket Key for an existing bucket.

Type annotations for `session.create_client("s3").put_bucket_encryption`
method.

Boto3 documentation:
[S3.Client.put_bucket_encryption](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_encryption)

Asynchronous method. Use `await put_bucket_encryption(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketEncryptionRequestRequestTypeDef](./type_defs.md#putbucketencryptionrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ServerSideEncryptionConfiguration`:
  [ServerSideEncryptionConfigurationTypeDef](./type_defs.md#serversideencryptionconfigurationtypedef)
  *(required)*
- `ContentMD5`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_intelligent\_tiering\_configuration"></a>

### put_bucket_intelligent_tiering_configuration

Puts a S3 Intelligent-Tiering configuration to the specified bucket.

Type annotations for
`session.create_client("s3").put_bucket_intelligent_tiering_configuration`
method.

Boto3 documentation:
[S3.Client.put_bucket_intelligent_tiering_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_intelligent_tiering_configuration)

Asynchronous method. Use
`await put_bucket_intelligent_tiering_configuration(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketIntelligentTieringConfigurationRequestRequestTypeDef](./type_defs.md#putbucketintelligenttieringconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `IntelligentTieringConfiguration`:
  [IntelligentTieringConfigurationTypeDef](./type_defs.md#intelligenttieringconfigurationtypedef)
  *(required)*

<a id="put\_bucket\_inventory\_configuration"></a>

### put_bucket_inventory_configuration

This implementation of the `PUT` action adds an inventory configuration
(identified by the inventory ID) to the bucket.

Type annotations for
`session.create_client("s3").put_bucket_inventory_configuration` method.

Boto3 documentation:
[S3.Client.put_bucket_inventory_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_inventory_configuration)

Asynchronous method. Use `await put_bucket_inventory_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketInventoryConfigurationRequestRequestTypeDef](./type_defs.md#putbucketinventoryconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `InventoryConfiguration`:
  [InventoryConfigurationTypeDef](./type_defs.md#inventoryconfigurationtypedef)
  *(required)*
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_lifecycle"></a>

### put_bucket_lifecycle

.

Type annotations for `session.create_client("s3").put_bucket_lifecycle` method.

Boto3 documentation:
[S3.Client.put_bucket_lifecycle](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_lifecycle)

Asynchronous method. Use `await put_bucket_lifecycle(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketLifecycleRequestRequestTypeDef](./type_defs.md#putbucketlifecyclerequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `LifecycleConfiguration`:
  [LifecycleConfigurationTypeDef](./type_defs.md#lifecycleconfigurationtypedef)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_lifecycle\_configuration"></a>

### put_bucket_lifecycle_configuration

Creates a new lifecycle configuration for the bucket or replaces an existing
lifecycle configuration.

Type annotations for
`session.create_client("s3").put_bucket_lifecycle_configuration` method.

Boto3 documentation:
[S3.Client.put_bucket_lifecycle_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_lifecycle_configuration)

Asynchronous method. Use `await put_bucket_lifecycle_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketLifecycleConfigurationRequestRequestTypeDef](./type_defs.md#putbucketlifecycleconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `LifecycleConfiguration`:
  [BucketLifecycleConfigurationTypeDef](./type_defs.md#bucketlifecycleconfigurationtypedef)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_logging"></a>

### put_bucket_logging

Set the logging parameters for a bucket and to specify permissions for who can
view and modify the logging parameters.

Type annotations for `session.create_client("s3").put_bucket_logging` method.

Boto3 documentation:
[S3.Client.put_bucket_logging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_logging)

Asynchronous method. Use `await put_bucket_logging(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketLoggingRequestRequestTypeDef](./type_defs.md#putbucketloggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `BucketLoggingStatus`:
  [BucketLoggingStatusTypeDef](./type_defs.md#bucketloggingstatustypedef)
  *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_metrics\_configuration"></a>

### put_bucket_metrics_configuration

Sets a metrics configuration (specified by the metrics configuration ID) for
the bucket.

Type annotations for
`session.create_client("s3").put_bucket_metrics_configuration` method.

Boto3 documentation:
[S3.Client.put_bucket_metrics_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_metrics_configuration)

Asynchronous method. Use `await put_bucket_metrics_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketMetricsConfigurationRequestRequestTypeDef](./type_defs.md#putbucketmetricsconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Id`: `str` *(required)*
- `MetricsConfiguration`:
  [MetricsConfigurationTypeDef](./type_defs.md#metricsconfigurationtypedef)
  *(required)*
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_notification"></a>

### put_bucket_notification

No longer used, see the
[PutBucketNotificationConfiguration](https://docs.aws.amazon.com/AmazonS3/latest/API/API_PutBucketNotificationConfiguration.html)\_
operation.

Type annotations for `session.create_client("s3").put_bucket_notification`
method.

Boto3 documentation:
[S3.Client.put_bucket_notification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_notification)

Asynchronous method. Use `await put_bucket_notification(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketNotificationRequestRequestTypeDef](./type_defs.md#putbucketnotificationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `NotificationConfiguration`:
  [NotificationConfigurationDeprecatedTypeDef](./type_defs.md#notificationconfigurationdeprecatedtypedef)
  *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_notification\_configuration"></a>

### put_bucket_notification_configuration

Enables notifications of specified events for a bucket.

Type annotations for
`session.create_client("s3").put_bucket_notification_configuration` method.

Boto3 documentation:
[S3.Client.put_bucket_notification_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_notification_configuration)

Asynchronous method. Use `await put_bucket_notification_configuration(...)` for
a synchronous call.

Arguments mapping described in
[PutBucketNotificationConfigurationRequestRequestTypeDef](./type_defs.md#putbucketnotificationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `NotificationConfiguration`:
  [NotificationConfigurationTypeDef](./type_defs.md#notificationconfigurationtypedef)
  *(required)*
- `ExpectedBucketOwner`: `str`
- `SkipDestinationValidation`: `bool`

<a id="put\_bucket\_ownership\_controls"></a>

### put_bucket_ownership_controls

Creates or modifies `OwnershipControls` for an Amazon S3 bucket.

Type annotations for
`session.create_client("s3").put_bucket_ownership_controls` method.

Boto3 documentation:
[S3.Client.put_bucket_ownership_controls](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_ownership_controls)

Asynchronous method. Use `await put_bucket_ownership_controls(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketOwnershipControlsRequestRequestTypeDef](./type_defs.md#putbucketownershipcontrolsrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `OwnershipControls`:
  [OwnershipControlsTypeDef](./type_defs.md#ownershipcontrolstypedef)
  *(required)*
- `ContentMD5`: `str`
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_policy"></a>

### put_bucket_policy

Applies an Amazon S3 bucket policy to an Amazon S3 bucket.

Type annotations for `session.create_client("s3").put_bucket_policy` method.

Boto3 documentation:
[S3.Client.put_bucket_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_policy)

Asynchronous method. Use `await put_bucket_policy(...)` for a synchronous call.

Arguments mapping described in
[PutBucketPolicyRequestRequestTypeDef](./type_defs.md#putbucketpolicyrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Policy`: `str` *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ConfirmRemoveSelfBucketAccess`: `bool`
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_replication"></a>

### put_bucket_replication

Creates a replication configuration or replaces an existing one.

Type annotations for `session.create_client("s3").put_bucket_replication`
method.

Boto3 documentation:
[S3.Client.put_bucket_replication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_replication)

Asynchronous method. Use `await put_bucket_replication(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketReplicationRequestRequestTypeDef](./type_defs.md#putbucketreplicationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ReplicationConfiguration`:
  [ReplicationConfigurationTypeDef](./type_defs.md#replicationconfigurationtypedef)
  *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `Token`: `str`
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_request\_payment"></a>

### put_bucket_request_payment

Sets the request payment configuration for a bucket.

Type annotations for `session.create_client("s3").put_bucket_request_payment`
method.

Boto3 documentation:
[S3.Client.put_bucket_request_payment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_request_payment)

Asynchronous method. Use `await put_bucket_request_payment(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketRequestPaymentRequestRequestTypeDef](./type_defs.md#putbucketrequestpaymentrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `RequestPaymentConfiguration`:
  [RequestPaymentConfigurationTypeDef](./type_defs.md#requestpaymentconfigurationtypedef)
  *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_tagging"></a>

### put_bucket_tagging

Sets the tags for a bucket.

Type annotations for `session.create_client("s3").put_bucket_tagging` method.

Boto3 documentation:
[S3.Client.put_bucket_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_tagging)

Asynchronous method. Use `await put_bucket_tagging(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketTaggingRequestRequestTypeDef](./type_defs.md#putbuckettaggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Tagging`: [TaggingTypeDef](./type_defs.md#taggingtypedef) *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_versioning"></a>

### put_bucket_versioning

Sets the versioning state of an existing bucket.

Type annotations for `session.create_client("s3").put_bucket_versioning`
method.

Boto3 documentation:
[S3.Client.put_bucket_versioning](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_versioning)

Asynchronous method. Use `await put_bucket_versioning(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketVersioningRequestRequestTypeDef](./type_defs.md#putbucketversioningrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `VersioningConfiguration`:
  [VersioningConfigurationTypeDef](./type_defs.md#versioningconfigurationtypedef)
  *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `MFA`: `str`
- `ExpectedBucketOwner`: `str`

<a id="put\_bucket\_website"></a>

### put_bucket_website

Sets the configuration of the website that is specified in the `website`
subresource.

Type annotations for `session.create_client("s3").put_bucket_website` method.

Boto3 documentation:
[S3.Client.put_bucket_website](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_website)

Asynchronous method. Use `await put_bucket_website(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketWebsiteRequestRequestTypeDef](./type_defs.md#putbucketwebsiterequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `WebsiteConfiguration`:
  [WebsiteConfigurationTypeDef](./type_defs.md#websiteconfigurationtypedef)
  *(required)*
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="put\_object"></a>

### put_object

Adds an object to a bucket.

Type annotations for `session.create_client("s3").put_object` method.

Boto3 documentation:
[S3.Client.put_object](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_object)

Asynchronous method. Use `await put_object(...)` for a synchronous call.

Arguments mapping described in
[PutObjectRequestRequestTypeDef](./type_defs.md#putobjectrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `ACL`: [ObjectCannedACLType](./literals.md#objectcannedacltype)
- `Body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `CacheControl`: `str`
- `ContentDisposition`: `str`
- `ContentEncoding`: `str`
- `ContentLanguage`: `str`
- `ContentLength`: `int`
- `ContentMD5`: `str`
- `ContentType`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ChecksumCRC32`: `str`
- `ChecksumCRC32C`: `str`
- `ChecksumSHA1`: `str`
- `ChecksumSHA256`: `str`
- `Expires`: `Union`\[`datetime`, `str`\]
- `GrantFullControl`: `str`
- `GrantRead`: `str`
- `GrantReadACP`: `str`
- `GrantWriteACP`: `str`
- `Metadata`: `Mapping`\[`str`, `str`\]
- `ServerSideEncryption`:
  [ServerSideEncryptionType](./literals.md#serversideencryptiontype)
- `StorageClass`: [StorageClassType](./literals.md#storageclasstype)
- `WebsiteRedirectLocation`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `SSEKMSKeyId`: `str`
- `SSEKMSEncryptionContext`: `str`
- `BucketKeyEnabled`: `bool`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `Tagging`: `str`
- `ObjectLockMode`: [ObjectLockModeType](./literals.md#objectlockmodetype)
- `ObjectLockRetainUntilDate`: `Union`\[`datetime`, `str`\]
- `ObjectLockLegalHoldStatus`:
  [ObjectLockLegalHoldStatusType](./literals.md#objectlocklegalholdstatustype)
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[PutObjectOutputTypeDef](./type_defs.md#putobjectoutputtypedef).

<a id="put\_object\_acl"></a>

### put_object_acl

Uses the `acl` subresource to set the access control list (ACL) permissions for
a new or existing object in an S3 bucket.

Type annotations for `session.create_client("s3").put_object_acl` method.

Boto3 documentation:
[S3.Client.put_object_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_object_acl)

Asynchronous method. Use `await put_object_acl(...)` for a synchronous call.

Arguments mapping described in
[PutObjectAclRequestRequestTypeDef](./type_defs.md#putobjectaclrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `ACL`: [ObjectCannedACLType](./literals.md#objectcannedacltype)
- `AccessControlPolicy`:
  [AccessControlPolicyTypeDef](./type_defs.md#accesscontrolpolicytypedef)
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `GrantFullControl`: `str`
- `GrantRead`: `str`
- `GrantReadACP`: `str`
- `GrantWrite`: `str`
- `GrantWriteACP`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `VersionId`: `str`
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[PutObjectAclOutputTypeDef](./type_defs.md#putobjectacloutputtypedef).

<a id="put\_object\_legal\_hold"></a>

### put_object_legal_hold

Applies a legal hold configuration to the specified object.

Type annotations for `session.create_client("s3").put_object_legal_hold`
method.

Boto3 documentation:
[S3.Client.put_object_legal_hold](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_object_legal_hold)

Asynchronous method. Use `await put_object_legal_hold(...)` for a synchronous
call.

Arguments mapping described in
[PutObjectLegalHoldRequestRequestTypeDef](./type_defs.md#putobjectlegalholdrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `LegalHold`:
  [ObjectLockLegalHoldTypeDef](./type_defs.md#objectlocklegalholdtypedef)
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `VersionId`: `str`
- `ContentMD5`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[PutObjectLegalHoldOutputTypeDef](./type_defs.md#putobjectlegalholdoutputtypedef).

<a id="put\_object\_lock\_configuration"></a>

### put_object_lock_configuration

Places an Object Lock configuration on the specified bucket.

Type annotations for
`session.create_client("s3").put_object_lock_configuration` method.

Boto3 documentation:
[S3.Client.put_object_lock_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_object_lock_configuration)

Asynchronous method. Use `await put_object_lock_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutObjectLockConfigurationRequestRequestTypeDef](./type_defs.md#putobjectlockconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ObjectLockConfiguration`:
  [ObjectLockConfigurationTypeDef](./type_defs.md#objectlockconfigurationtypedef)
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `Token`: `str`
- `ContentMD5`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[PutObjectLockConfigurationOutputTypeDef](./type_defs.md#putobjectlockconfigurationoutputtypedef).

<a id="put\_object\_retention"></a>

### put_object_retention

Places an Object Retention configuration on an object.

Type annotations for `session.create_client("s3").put_object_retention` method.

Boto3 documentation:
[S3.Client.put_object_retention](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_object_retention)

Asynchronous method. Use `await put_object_retention(...)` for a synchronous
call.

Arguments mapping described in
[PutObjectRetentionRequestRequestTypeDef](./type_defs.md#putobjectretentionrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `Retention`:
  [ObjectLockRetentionTypeDef](./type_defs.md#objectlockretentiontypedef)
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `VersionId`: `str`
- `BypassGovernanceRetention`: `bool`
- `ContentMD5`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[PutObjectRetentionOutputTypeDef](./type_defs.md#putobjectretentionoutputtypedef).

<a id="put\_object\_tagging"></a>

### put_object_tagging

Sets the supplied tag-set to an object that already exists in a bucket.

Type annotations for `session.create_client("s3").put_object_tagging` method.

Boto3 documentation:
[S3.Client.put_object_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_object_tagging)

Asynchronous method. Use `await put_object_tagging(...)` for a synchronous
call.

Arguments mapping described in
[PutObjectTaggingRequestRequestTypeDef](./type_defs.md#putobjecttaggingrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `Tagging`: [TaggingTypeDef](./type_defs.md#taggingtypedef) *(required)*
- `VersionId`: `str`
- `ContentMD5`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))

Returns a `Coroutine` for
[PutObjectTaggingOutputTypeDef](./type_defs.md#putobjecttaggingoutputtypedef).

<a id="put\_public\_access\_block"></a>

### put_public_access_block

Creates or modifies the `PublicAccessBlock` configuration for an Amazon S3
bucket.

Type annotations for `session.create_client("s3").put_public_access_block`
method.

Boto3 documentation:
[S3.Client.put_public_access_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_public_access_block)

Asynchronous method. Use `await put_public_access_block(...)` for a synchronous
call.

Arguments mapping described in
[PutPublicAccessBlockRequestRequestTypeDef](./type_defs.md#putpublicaccessblockrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `PublicAccessBlockConfiguration`:
  [PublicAccessBlockConfigurationTypeDef](./type_defs.md#publicaccessblockconfigurationtypedef)
  *(required)*
- `ContentMD5`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

<a id="restore\_object"></a>

### restore_object

Restores an archived copy of an object back into Amazon S3 This action is not
supported by Amazon S3 on Outposts.

Type annotations for `session.create_client("s3").restore_object` method.

Boto3 documentation:
[S3.Client.restore_object](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.restore_object)

Asynchronous method. Use `await restore_object(...)` for a synchronous call.

Arguments mapping described in
[RestoreObjectRequestRequestTypeDef](./type_defs.md#restoreobjectrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `VersionId`: `str`
- `RestoreRequest`:
  [RestoreRequestTypeDef](./type_defs.md#restorerequesttypedef)
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[RestoreObjectOutputTypeDef](./type_defs.md#restoreobjectoutputtypedef).

<a id="select\_object\_content"></a>

### select_object_content

This action filters the contents of an Amazon S3 object based on a simple
structured query language (SQL) statement.

Type annotations for `session.create_client("s3").select_object_content`
method.

Boto3 documentation:
[S3.Client.select_object_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.select_object_content)

Asynchronous method. Use `await select_object_content(...)` for a synchronous
call.

Arguments mapping described in
[SelectObjectContentRequestRequestTypeDef](./type_defs.md#selectobjectcontentrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `Expression`: `str` *(required)*
- `ExpressionType`: `Literal['SQL']` (see
  [ExpressionTypeType](./literals.md#expressiontypetype)) *(required)*
- `InputSerialization`:
  [InputSerializationTypeDef](./type_defs.md#inputserializationtypedef)
  *(required)*
- `OutputSerialization`:
  [OutputSerializationTypeDef](./type_defs.md#outputserializationtypedef)
  *(required)*
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `RequestProgress`:
  [RequestProgressTypeDef](./type_defs.md#requestprogresstypedef)
- `ScanRange`: [ScanRangeTypeDef](./type_defs.md#scanrangetypedef)
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[SelectObjectContentOutputTypeDef](./type_defs.md#selectobjectcontentoutputtypedef).

<a id="upload\_file"></a>

### upload_file

Upload a file to an S3 object.

Type annotations for `session.create_client("s3").upload_file` method.

Boto3 documentation:
[S3.Client.upload_file](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.upload_file)

Asynchronous method. Use `await upload_file(...)` for a synchronous call.

Arguments mapping described in
[ClientUploadFileRequestTypeDef](./type_defs.md#clientuploadfilerequesttypedef).

Arguments:

- `Filename`: `str` *(required)*
- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `ExtraArgs`: `Dict`\[`str`, `Any`\]
- `Callback`: `Callable`\[`...`, `Any`\]
- `Config`: `TransferConfig`

<a id="upload\_fileobj"></a>

### upload_fileobj

Upload a file-like object to S3.

Type annotations for `session.create_client("s3").upload_fileobj` method.

Boto3 documentation:
[S3.Client.upload_fileobj](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.upload_fileobj)

Asynchronous method. Use `await upload_fileobj(...)` for a synchronous call.

Arguments mapping described in
[ClientUploadFileobjRequestTypeDef](./type_defs.md#clientuploadfileobjrequesttypedef).

Arguments:

- `Fileobj`: `Union`\[`IO`\[`Any`\], `StreamingBody`\] *(required)*
- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `ExtraArgs`: `Dict`\[`str`, `Any`\]
- `Callback`: `Callable`\[`...`, `Any`\]
- `Config`: `TransferConfig`

<a id="upload\_part"></a>

### upload_part

Uploads a part in a multipart upload.

Type annotations for `session.create_client("s3").upload_part` method.

Boto3 documentation:
[S3.Client.upload_part](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.upload_part)

Asynchronous method. Use `await upload_part(...)` for a synchronous call.

Arguments mapping described in
[UploadPartRequestRequestTypeDef](./type_defs.md#uploadpartrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `Key`: `str` *(required)*
- `PartNumber`: `int` *(required)*
- `UploadId`: `str` *(required)*
- `Body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `ContentLength`: `int`
- `ContentMD5`: `str`
- `ChecksumAlgorithm`:
  [ChecksumAlgorithmType](./literals.md#checksumalgorithmtype)
- `ChecksumCRC32`: `str`
- `ChecksumCRC32C`: `str`
- `ChecksumSHA1`: `str`
- `ChecksumSHA256`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`

Returns a `Coroutine` for
[UploadPartOutputTypeDef](./type_defs.md#uploadpartoutputtypedef).

<a id="upload\_part\_copy"></a>

### upload_part_copy

Uploads a part by copying data from an existing object as data source.

Type annotations for `session.create_client("s3").upload_part_copy` method.

Boto3 documentation:
[S3.Client.upload_part_copy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.upload_part_copy)

Asynchronous method. Use `await upload_part_copy(...)` for a synchronous call.

Arguments mapping described in
[UploadPartCopyRequestRequestTypeDef](./type_defs.md#uploadpartcopyrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `CopySource`: `Union`\[`str`,
  [CopySourceTypeDef](./type_defs.md#copysourcetypedef)\] *(required)*
- `Key`: `str` *(required)*
- `PartNumber`: `int` *(required)*
- `UploadId`: `str` *(required)*
- `CopySourceIfMatch`: `str`
- `CopySourceIfModifiedSince`: `Union`\[`datetime`, `str`\]
- `CopySourceIfNoneMatch`: `str`
- `CopySourceIfUnmodifiedSince`: `Union`\[`datetime`, `str`\]
- `CopySourceRange`: `str`
- `SSECustomerAlgorithm`: `str`
- `SSECustomerKey`: `str`
- `SSECustomerKeyMD5`: `str`
- `CopySourceSSECustomerAlgorithm`: `str`
- `CopySourceSSECustomerKey`: `str`
- `CopySourceSSECustomerKeyMD5`: `str`
- `RequestPayer`: `Literal['requester']` (see
  [RequestPayerType](./literals.md#requestpayertype))
- `ExpectedBucketOwner`: `str`
- `ExpectedSourceBucketOwner`: `str`

Returns a `Coroutine` for
[UploadPartCopyOutputTypeDef](./type_defs.md#uploadpartcopyoutputtypedef).

<a id="write\_get\_object\_response"></a>

### write_get_object_response

Passes transformed objects to a `GetObject` operation when using Object Lambda
access points.

Type annotations for `session.create_client("s3").write_get_object_response`
method.

Boto3 documentation:
[S3.Client.write_get_object_response](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.write_get_object_response)

Asynchronous method. Use `await write_get_object_response(...)` for a
synchronous call.

Arguments mapping described in
[WriteGetObjectResponseRequestRequestTypeDef](./type_defs.md#writegetobjectresponserequestrequesttypedef).

Keyword-only arguments:

- `RequestRoute`: `str` *(required)*
- `RequestToken`: `str` *(required)*
- `Body`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `StatusCode`: `int`
- `ErrorCode`: `str`
- `ErrorMessage`: `str`
- `AcceptRanges`: `str`
- `CacheControl`: `str`
- `ContentDisposition`: `str`
- `ContentEncoding`: `str`
- `ContentLanguage`: `str`
- `ContentLength`: `int`
- `ContentRange`: `str`
- `ContentType`: `str`
- `ChecksumCRC32`: `str`
- `ChecksumCRC32C`: `str`
- `ChecksumSHA1`: `str`
- `ChecksumSHA256`: `str`
- `DeleteMarker`: `bool`
- `ETag`: `str`
- `Expires`: `Union`\[`datetime`, `str`\]
- `Expiration`: `str`
- `LastModified`: `Union`\[`datetime`, `str`\]
- `MissingMeta`: `int`
- `Metadata`: `Mapping`\[`str`, `str`\]
- `ObjectLockMode`: [ObjectLockModeType](./literals.md#objectlockmodetype)
- `ObjectLockLegalHoldStatus`:
  [ObjectLockLegalHoldStatusType](./literals.md#objectlocklegalholdstatustype)
- `ObjectLockRetainUntilDate`: `Union`\[`datetime`, `str`\]
- `PartsCount`: `int`
- `ReplicationStatus`:
  [ReplicationStatusType](./literals.md#replicationstatustype)
- `RequestCharged`: `Literal['requester']` (see
  [RequestChargedType](./literals.md#requestchargedtype))
- `Restore`: `str`
- `ServerSideEncryption`:
  [ServerSideEncryptionType](./literals.md#serversideencryptiontype)
- `SSECustomerAlgorithm`: `str`
- `SSEKMSKeyId`: `str`
- `SSECustomerKeyMD5`: `str`
- `StorageClass`: [StorageClassType](./literals.md#storageclasstype)
- `TagCount`: `int`
- `VersionId`: `str`
- `BucketKeyEnabled`: `bool`

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("s3").__aenter__` method.

Boto3 documentation:
[S3.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [S3Client](#s3client).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("s3").__aexit__` method.

Boto3 documentation:
[S3.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("s3").get_paginator` method with
overloads.

- `client.get_paginator("list_multipart_uploads")` ->
  [ListMultipartUploadsPaginator](./paginators.md#listmultipartuploadspaginator)
- `client.get_paginator("list_object_versions")` ->
  [ListObjectVersionsPaginator](./paginators.md#listobjectversionspaginator)
- `client.get_paginator("list_objects")` ->
  [ListObjectsPaginator](./paginators.md#listobjectspaginator)
- `client.get_paginator("list_objects_v2")` ->
  [ListObjectsV2Paginator](./paginators.md#listobjectsv2paginator)
- `client.get_paginator("list_parts")` ->
  [ListPartsPaginator](./paginators.md#listpartspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("s3").get_waiter` method with
overloads.

- `client.get_waiter("bucket_exists")` ->
  [BucketExistsWaiter](./waiters.md#bucketexistswaiter)
- `client.get_waiter("bucket_not_exists")` ->
  [BucketNotExistsWaiter](./waiters.md#bucketnotexistswaiter)
- `client.get_waiter("object_exists")` ->
  [ObjectExistsWaiter](./waiters.md#objectexistswaiter)
- `client.get_waiter("object_not_exists")` ->
  [ObjectNotExistsWaiter](./waiters.md#objectnotexistswaiter)
