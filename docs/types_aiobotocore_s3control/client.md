<a id="s3controlclient-for-aiobotocore-s3control-module"></a>

# S3ControlClient for aiobotocore S3Control module

> [Index](../README.md) > [S3Control](./README.md) > S3ControlClient

Auto-generated documentation for
[S3Control](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control)
type annotations stubs module
[types-aiobotocore-s3control](https://pypi.org/project/types-aiobotocore-s3control/).

- [S3ControlClient for aiobotocore S3Control module](#s3controlclient-for-aiobotocore-s3control-module)
  - [S3ControlClient](#s3controlclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_access_point](#create_access_point)
    - [create_access_point_for_object_lambda](#create_access_point_for_object_lambda)
    - [create_bucket](#create_bucket)
    - [create_job](#create_job)
    - [create_multi_region_access_point](#create_multi_region_access_point)
    - [delete_access_point](#delete_access_point)
    - [delete_access_point_for_object_lambda](#delete_access_point_for_object_lambda)
    - [delete_access_point_policy](#delete_access_point_policy)
    - [delete_access_point_policy_for_object_lambda](#delete_access_point_policy_for_object_lambda)
    - [delete_bucket](#delete_bucket)
    - [delete_bucket_lifecycle_configuration](#delete_bucket_lifecycle_configuration)
    - [delete_bucket_policy](#delete_bucket_policy)
    - [delete_bucket_tagging](#delete_bucket_tagging)
    - [delete_job_tagging](#delete_job_tagging)
    - [delete_multi_region_access_point](#delete_multi_region_access_point)
    - [delete_public_access_block](#delete_public_access_block)
    - [delete_storage_lens_configuration](#delete_storage_lens_configuration)
    - [delete_storage_lens_configuration_tagging](#delete_storage_lens_configuration_tagging)
    - [describe_job](#describe_job)
    - [describe_multi_region_access_point_operation](#describe_multi_region_access_point_operation)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_access_point](#get_access_point)
    - [get_access_point_configuration_for_object_lambda](#get_access_point_configuration_for_object_lambda)
    - [get_access_point_for_object_lambda](#get_access_point_for_object_lambda)
    - [get_access_point_policy](#get_access_point_policy)
    - [get_access_point_policy_for_object_lambda](#get_access_point_policy_for_object_lambda)
    - [get_access_point_policy_status](#get_access_point_policy_status)
    - [get_access_point_policy_status_for_object_lambda](#get_access_point_policy_status_for_object_lambda)
    - [get_bucket](#get_bucket)
    - [get_bucket_lifecycle_configuration](#get_bucket_lifecycle_configuration)
    - [get_bucket_policy](#get_bucket_policy)
    - [get_bucket_tagging](#get_bucket_tagging)
    - [get_job_tagging](#get_job_tagging)
    - [get_multi_region_access_point](#get_multi_region_access_point)
    - [get_multi_region_access_point_policy](#get_multi_region_access_point_policy)
    - [get_multi_region_access_point_policy_status](#get_multi_region_access_point_policy_status)
    - [get_public_access_block](#get_public_access_block)
    - [get_storage_lens_configuration](#get_storage_lens_configuration)
    - [get_storage_lens_configuration_tagging](#get_storage_lens_configuration_tagging)
    - [list_access_points](#list_access_points)
    - [list_access_points_for_object_lambda](#list_access_points_for_object_lambda)
    - [list_jobs](#list_jobs)
    - [list_multi_region_access_points](#list_multi_region_access_points)
    - [list_regional_buckets](#list_regional_buckets)
    - [list_storage_lens_configurations](#list_storage_lens_configurations)
    - [put_access_point_configuration_for_object_lambda](#put_access_point_configuration_for_object_lambda)
    - [put_access_point_policy](#put_access_point_policy)
    - [put_access_point_policy_for_object_lambda](#put_access_point_policy_for_object_lambda)
    - [put_bucket_lifecycle_configuration](#put_bucket_lifecycle_configuration)
    - [put_bucket_policy](#put_bucket_policy)
    - [put_bucket_tagging](#put_bucket_tagging)
    - [put_job_tagging](#put_job_tagging)
    - [put_multi_region_access_point_policy](#put_multi_region_access_point_policy)
    - [put_public_access_block](#put_public_access_block)
    - [put_storage_lens_configuration](#put_storage_lens_configuration)
    - [put_storage_lens_configuration_tagging](#put_storage_lens_configuration_tagging)
    - [update_job_priority](#update_job_priority)
    - [update_job_status](#update_job_status)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="s3controlclient"></a>

## S3ControlClient

Type annotations for `session.create_client("s3control")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_s3control.client import S3ControlClient

session = get_session()
async with session.create_client("s3control") as client:
    client: S3ControlClient
```

Boto3 documentation:
[S3Control.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_s3control.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.BucketAlreadyExists`
- `Exceptions.BucketAlreadyOwnedByYou`
- `Exceptions.ClientError`
- `Exceptions.IdempotencyException`
- `Exceptions.InternalServiceException`
- `Exceptions.InvalidNextTokenException`
- `Exceptions.InvalidRequestException`
- `Exceptions.JobStatusException`
- `Exceptions.NoSuchPublicAccessBlockConfiguration`
- `Exceptions.NotFoundException`
- `Exceptions.TooManyRequestsException`
- `Exceptions.TooManyTagsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

S3ControlClient exceptions.

Type annotations for `session.create_client("s3control").exceptions` method.

Boto3 documentation:
[S3Control.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("s3control").can_paginate` method.

Boto3 documentation:
[S3Control.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_access\_point"></a>

### create_access_point

Creates an access point and associates it with the specified bucket.

Type annotations for `session.create_client("s3control").create_access_point`
method.

Boto3 documentation:
[S3Control.Client.create_access_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.create_access_point)

Asynchronous method. Use `await create_access_point(...)` for a synchronous
call.

Arguments mapping described in
[CreateAccessPointRequestRequestTypeDef](./type_defs.md#createaccesspointrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Bucket`: `str` *(required)*
- `VpcConfiguration`:
  [VpcConfigurationTypeDef](./type_defs.md#vpcconfigurationtypedef)
- `PublicAccessBlockConfiguration`:
  [PublicAccessBlockConfigurationTypeDef](./type_defs.md#publicaccessblockconfigurationtypedef)

Returns a `Coroutine` for
[CreateAccessPointResultTypeDef](./type_defs.md#createaccesspointresulttypedef).

<a id="create\_access\_point\_for\_object\_lambda"></a>

### create_access_point_for_object_lambda

Creates an Object Lambda Access Point.

Type annotations for
`session.create_client("s3control").create_access_point_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.create_access_point_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.create_access_point_for_object_lambda)

Asynchronous method. Use `await create_access_point_for_object_lambda(...)` for
a synchronous call.

Arguments mapping described in
[CreateAccessPointForObjectLambdaRequestRequestTypeDef](./type_defs.md#createaccesspointforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Configuration`:
  [ObjectLambdaConfigurationTypeDef](./type_defs.md#objectlambdaconfigurationtypedef)
  *(required)*

Returns a `Coroutine` for
[CreateAccessPointForObjectLambdaResultTypeDef](./type_defs.md#createaccesspointforobjectlambdaresulttypedef).

<a id="create\_bucket"></a>

### create_bucket

.

Type annotations for `session.create_client("s3control").create_bucket` method.

Boto3 documentation:
[S3Control.Client.create_bucket](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.create_bucket)

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
- `OutpostId`: `str`

Returns a `Coroutine` for
[CreateBucketResultTypeDef](./type_defs.md#createbucketresulttypedef).

<a id="create\_job"></a>

### create_job

You can use S3 Batch Operations to perform large-scale batch actions on Amazon
S3 objects.

Type annotations for `session.create_client("s3control").create_job` method.

Boto3 documentation:
[S3Control.Client.create_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.create_job)

Asynchronous method. Use `await create_job(...)` for a synchronous call.

Arguments mapping described in
[CreateJobRequestRequestTypeDef](./type_defs.md#createjobrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Operation`: [JobOperationTypeDef](./type_defs.md#joboperationtypedef)
  *(required)*
- `Report`: [JobReportTypeDef](./type_defs.md#jobreporttypedef) *(required)*
- `ClientRequestToken`: `str` *(required)*
- `Priority`: `int` *(required)*
- `RoleArn`: `str` *(required)*
- `ConfirmationRequired`: `bool`
- `Manifest`: [JobManifestTypeDef](./type_defs.md#jobmanifesttypedef)
- `Description`: `str`
- `Tags`: `Sequence`\[[S3TagTypeDef](./type_defs.md#s3tagtypedef)\]
- `ManifestGenerator`:
  [JobManifestGeneratorTypeDef](./type_defs.md#jobmanifestgeneratortypedef)

Returns a `Coroutine` for
[CreateJobResultTypeDef](./type_defs.md#createjobresulttypedef).

<a id="create\_multi\_region\_access\_point"></a>

### create_multi_region_access_point

Creates a Multi-Region Access Point and associates it with the specified
buckets.

Type annotations for
`session.create_client("s3control").create_multi_region_access_point` method.

Boto3 documentation:
[S3Control.Client.create_multi_region_access_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.create_multi_region_access_point)

Asynchronous method. Use `await create_multi_region_access_point(...)` for a
synchronous call.

Arguments mapping described in
[CreateMultiRegionAccessPointRequestRequestTypeDef](./type_defs.md#createmultiregionaccesspointrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `Details`:
  [CreateMultiRegionAccessPointInputTypeDef](./type_defs.md#createmultiregionaccesspointinputtypedef)
  *(required)*

Returns a `Coroutine` for
[CreateMultiRegionAccessPointResultTypeDef](./type_defs.md#createmultiregionaccesspointresulttypedef).

<a id="delete\_access\_point"></a>

### delete_access_point

Deletes the specified access point.

Type annotations for `session.create_client("s3control").delete_access_point`
method.

Boto3 documentation:
[S3Control.Client.delete_access_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_access_point)

Asynchronous method. Use `await delete_access_point(...)` for a synchronous
call.

Arguments mapping described in
[DeleteAccessPointRequestRequestTypeDef](./type_defs.md#deleteaccesspointrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

<a id="delete\_access\_point\_for\_object\_lambda"></a>

### delete_access_point_for_object_lambda

Deletes the specified Object Lambda Access Point.

Type annotations for
`session.create_client("s3control").delete_access_point_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.delete_access_point_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_access_point_for_object_lambda)

Asynchronous method. Use `await delete_access_point_for_object_lambda(...)` for
a synchronous call.

Arguments mapping described in
[DeleteAccessPointForObjectLambdaRequestRequestTypeDef](./type_defs.md#deleteaccesspointforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

<a id="delete\_access\_point\_policy"></a>

### delete_access_point_policy

Deletes the access point policy for the specified access point.

Type annotations for
`session.create_client("s3control").delete_access_point_policy` method.

Boto3 documentation:
[S3Control.Client.delete_access_point_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_access_point_policy)

Asynchronous method. Use `await delete_access_point_policy(...)` for a
synchronous call.

Arguments mapping described in
[DeleteAccessPointPolicyRequestRequestTypeDef](./type_defs.md#deleteaccesspointpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

<a id="delete\_access\_point\_policy\_for\_object\_lambda"></a>

### delete_access_point_policy_for_object_lambda

Removes the resource policy for an Object Lambda Access Point.

Type annotations for
`session.create_client("s3control").delete_access_point_policy_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.delete_access_point_policy_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_access_point_policy_for_object_lambda)

Asynchronous method. Use
`await delete_access_point_policy_for_object_lambda(...)` for a synchronous
call.

Arguments mapping described in
[DeleteAccessPointPolicyForObjectLambdaRequestRequestTypeDef](./type_defs.md#deleteaccesspointpolicyforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

<a id="delete\_bucket"></a>

### delete_bucket

.

Type annotations for `session.create_client("s3control").delete_bucket` method.

Boto3 documentation:
[S3Control.Client.delete_bucket](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket)

Asynchronous method. Use `await delete_bucket(...)` for a synchronous call.

Arguments mapping described in
[DeleteBucketRequestRequestTypeDef](./type_defs.md#deletebucketrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

<a id="delete\_bucket\_lifecycle\_configuration"></a>

### delete_bucket_lifecycle_configuration

.

Type annotations for
`session.create_client("s3control").delete_bucket_lifecycle_configuration`
method.

Boto3 documentation:
[S3Control.Client.delete_bucket_lifecycle_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_lifecycle_configuration)

Asynchronous method. Use `await delete_bucket_lifecycle_configuration(...)` for
a synchronous call.

Arguments mapping described in
[DeleteBucketLifecycleConfigurationRequestRequestTypeDef](./type_defs.md#deletebucketlifecycleconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

<a id="delete\_bucket\_policy"></a>

### delete_bucket_policy

.

Type annotations for `session.create_client("s3control").delete_bucket_policy`
method.

Boto3 documentation:
[S3Control.Client.delete_bucket_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_policy)

Asynchronous method. Use `await delete_bucket_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketPolicyRequestRequestTypeDef](./type_defs.md#deletebucketpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

<a id="delete\_bucket\_tagging"></a>

### delete_bucket_tagging

.

Type annotations for `session.create_client("s3control").delete_bucket_tagging`
method.

Boto3 documentation:
[S3Control.Client.delete_bucket_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_tagging)

Asynchronous method. Use `await delete_bucket_tagging(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBucketTaggingRequestRequestTypeDef](./type_defs.md#deletebuckettaggingrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

<a id="delete\_job\_tagging"></a>

### delete_job_tagging

Removes the entire tag set from the specified S3 Batch Operations job.

Type annotations for `session.create_client("s3control").delete_job_tagging`
method.

Boto3 documentation:
[S3Control.Client.delete_job_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_job_tagging)

Asynchronous method. Use `await delete_job_tagging(...)` for a synchronous
call.

Arguments mapping described in
[DeleteJobTaggingRequestRequestTypeDef](./type_defs.md#deletejobtaggingrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `JobId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_multi\_region\_access\_point"></a>

### delete_multi_region_access_point

Deletes a Multi-Region Access Point.

Type annotations for
`session.create_client("s3control").delete_multi_region_access_point` method.

Boto3 documentation:
[S3Control.Client.delete_multi_region_access_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_multi_region_access_point)

Asynchronous method. Use `await delete_multi_region_access_point(...)` for a
synchronous call.

Arguments mapping described in
[DeleteMultiRegionAccessPointRequestRequestTypeDef](./type_defs.md#deletemultiregionaccesspointrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `Details`:
  [DeleteMultiRegionAccessPointInputTypeDef](./type_defs.md#deletemultiregionaccesspointinputtypedef)
  *(required)*

Returns a `Coroutine` for
[DeleteMultiRegionAccessPointResultTypeDef](./type_defs.md#deletemultiregionaccesspointresulttypedef).

<a id="delete\_public\_access\_block"></a>

### delete_public_access_block

Removes the `PublicAccessBlock` configuration for an Amazon Web Services
account.

Type annotations for
`session.create_client("s3control").delete_public_access_block` method.

Boto3 documentation:
[S3Control.Client.delete_public_access_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_public_access_block)

Asynchronous method. Use `await delete_public_access_block(...)` for a
synchronous call.

Arguments mapping described in
[DeletePublicAccessBlockRequestRequestTypeDef](./type_defs.md#deletepublicaccessblockrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*

<a id="delete\_storage\_lens\_configuration"></a>

### delete_storage_lens_configuration

Deletes the Amazon S3 Storage Lens configuration.

Type annotations for
`session.create_client("s3control").delete_storage_lens_configuration` method.

Boto3 documentation:
[S3Control.Client.delete_storage_lens_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_storage_lens_configuration)

Asynchronous method. Use `await delete_storage_lens_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteStorageLensConfigurationRequestRequestTypeDef](./type_defs.md#deletestoragelensconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ConfigId`: `str` *(required)*
- `AccountId`: `str` *(required)*

<a id="delete\_storage\_lens\_configuration\_tagging"></a>

### delete_storage_lens_configuration_tagging

Deletes the Amazon S3 Storage Lens configuration tags.

Type annotations for
`session.create_client("s3control").delete_storage_lens_configuration_tagging`
method.

Boto3 documentation:
[S3Control.Client.delete_storage_lens_configuration_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_storage_lens_configuration_tagging)

Asynchronous method. Use `await delete_storage_lens_configuration_tagging(...)`
for a synchronous call.

Arguments mapping described in
[DeleteStorageLensConfigurationTaggingRequestRequestTypeDef](./type_defs.md#deletestoragelensconfigurationtaggingrequestrequesttypedef).

Keyword-only arguments:

- `ConfigId`: `str` *(required)*
- `AccountId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe\_job"></a>

### describe_job

Retrieves the configuration parameters and status for a Batch Operations job.

Type annotations for `session.create_client("s3control").describe_job` method.

Boto3 documentation:
[S3Control.Client.describe_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.describe_job)

Asynchronous method. Use `await describe_job(...)` for a synchronous call.

Arguments mapping described in
[DescribeJobRequestRequestTypeDef](./type_defs.md#describejobrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `JobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeJobResultTypeDef](./type_defs.md#describejobresulttypedef).

<a id="describe\_multi\_region\_access\_point\_operation"></a>

### describe_multi_region_access_point_operation

Retrieves the status of an asynchronous request to manage a Multi-Region Access
Point.

Type annotations for
`session.create_client("s3control").describe_multi_region_access_point_operation`
method.

Boto3 documentation:
[S3Control.Client.describe_multi_region_access_point_operation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.describe_multi_region_access_point_operation)

Asynchronous method. Use
`await describe_multi_region_access_point_operation(...)` for a synchronous
call.

Arguments mapping described in
[DescribeMultiRegionAccessPointOperationRequestRequestTypeDef](./type_defs.md#describemultiregionaccesspointoperationrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `RequestTokenARN`: `str` *(required)*

Returns a `Coroutine` for
[DescribeMultiRegionAccessPointOperationResultTypeDef](./type_defs.md#describemultiregionaccesspointoperationresulttypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("s3control").generate_presigned_url` method.

Boto3 documentation:
[S3Control.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_access\_point"></a>

### get_access_point

Returns configuration information about the specified access point.

Type annotations for `session.create_client("s3control").get_access_point`
method.

Boto3 documentation:
[S3Control.Client.get_access_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point)

Asynchronous method. Use `await get_access_point(...)` for a synchronous call.

Arguments mapping described in
[GetAccessPointRequestRequestTypeDef](./type_defs.md#getaccesspointrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPointResultTypeDef](./type_defs.md#getaccesspointresulttypedef).

<a id="get\_access\_point\_configuration\_for\_object\_lambda"></a>

### get_access_point_configuration_for_object_lambda

Returns configuration for an Object Lambda Access Point.

Type annotations for
`session.create_client("s3control").get_access_point_configuration_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.get_access_point_configuration_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_configuration_for_object_lambda)

Asynchronous method. Use
`await get_access_point_configuration_for_object_lambda(...)` for a synchronous
call.

Arguments mapping described in
[GetAccessPointConfigurationForObjectLambdaRequestRequestTypeDef](./type_defs.md#getaccesspointconfigurationforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPointConfigurationForObjectLambdaResultTypeDef](./type_defs.md#getaccesspointconfigurationforobjectlambdaresulttypedef).

<a id="get\_access\_point\_for\_object\_lambda"></a>

### get_access_point_for_object_lambda

Returns configuration information about the specified Object Lambda Access
Point The following actions are related to `GetAccessPointForObjectLambda` \*
`CreateAccessPointForObjectLambda <https://docs.aws.amazon.com/AmazonS3/latest/API/API_control_CreateAccessPointForObjectLambda.htm...`.

Type annotations for
`session.create_client("s3control").get_access_point_for_object_lambda` method.

Boto3 documentation:
[S3Control.Client.get_access_point_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_for_object_lambda)

Asynchronous method. Use `await get_access_point_for_object_lambda(...)` for a
synchronous call.

Arguments mapping described in
[GetAccessPointForObjectLambdaRequestRequestTypeDef](./type_defs.md#getaccesspointforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPointForObjectLambdaResultTypeDef](./type_defs.md#getaccesspointforobjectlambdaresulttypedef).

<a id="get\_access\_point\_policy"></a>

### get_access_point_policy

Returns the access point policy associated with the specified access point.

Type annotations for
`session.create_client("s3control").get_access_point_policy` method.

Boto3 documentation:
[S3Control.Client.get_access_point_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_policy)

Asynchronous method. Use `await get_access_point_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetAccessPointPolicyRequestRequestTypeDef](./type_defs.md#getaccesspointpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPointPolicyResultTypeDef](./type_defs.md#getaccesspointpolicyresulttypedef).

<a id="get\_access\_point\_policy\_for\_object\_lambda"></a>

### get_access_point_policy_for_object_lambda

Returns the resource policy for an Object Lambda Access Point.

Type annotations for
`session.create_client("s3control").get_access_point_policy_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.get_access_point_policy_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_policy_for_object_lambda)

Asynchronous method. Use `await get_access_point_policy_for_object_lambda(...)`
for a synchronous call.

Arguments mapping described in
[GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef](./type_defs.md#getaccesspointpolicyforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPointPolicyForObjectLambdaResultTypeDef](./type_defs.md#getaccesspointpolicyforobjectlambdaresulttypedef).

<a id="get\_access\_point\_policy\_status"></a>

### get_access_point_policy_status

Indicates whether the specified access point currently has a policy that allows
public access.

Type annotations for
`session.create_client("s3control").get_access_point_policy_status` method.

Boto3 documentation:
[S3Control.Client.get_access_point_policy_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_policy_status)

Asynchronous method. Use `await get_access_point_policy_status(...)` for a
synchronous call.

Arguments mapping described in
[GetAccessPointPolicyStatusRequestRequestTypeDef](./type_defs.md#getaccesspointpolicystatusrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPointPolicyStatusResultTypeDef](./type_defs.md#getaccesspointpolicystatusresulttypedef).

<a id="get\_access\_point\_policy\_status\_for\_object\_lambda"></a>

### get_access_point_policy_status_for_object_lambda

Returns the status of the resource policy associated with an Object Lambda
Access Point.

Type annotations for
`session.create_client("s3control").get_access_point_policy_status_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.get_access_point_policy_status_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_policy_status_for_object_lambda)

Asynchronous method. Use
`await get_access_point_policy_status_for_object_lambda(...)` for a synchronous
call.

Arguments mapping described in
[GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef](./type_defs.md#getaccesspointpolicystatusforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPointPolicyStatusForObjectLambdaResultTypeDef](./type_defs.md#getaccesspointpolicystatusforobjectlambdaresulttypedef).

<a id="get\_bucket"></a>

### get_bucket

Gets an Amazon S3 on Outposts bucket.

Type annotations for `session.create_client("s3control").get_bucket` method.

Boto3 documentation:
[S3Control.Client.get_bucket](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket)

Asynchronous method. Use `await get_bucket(...)` for a synchronous call.

Arguments mapping described in
[GetBucketRequestRequestTypeDef](./type_defs.md#getbucketrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

Returns a `Coroutine` for
[GetBucketResultTypeDef](./type_defs.md#getbucketresulttypedef).

<a id="get\_bucket\_lifecycle\_configuration"></a>

### get_bucket_lifecycle_configuration

.

Type annotations for
`session.create_client("s3control").get_bucket_lifecycle_configuration` method.

Boto3 documentation:
[S3Control.Client.get_bucket_lifecycle_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_lifecycle_configuration)

Asynchronous method. Use `await get_bucket_lifecycle_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetBucketLifecycleConfigurationRequestRequestTypeDef](./type_defs.md#getbucketlifecycleconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

Returns a `Coroutine` for
[GetBucketLifecycleConfigurationResultTypeDef](./type_defs.md#getbucketlifecycleconfigurationresulttypedef).

<a id="get\_bucket\_policy"></a>

### get_bucket_policy

.

Type annotations for `session.create_client("s3control").get_bucket_policy`
method.

Boto3 documentation:
[S3Control.Client.get_bucket_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_policy)

Asynchronous method. Use `await get_bucket_policy(...)` for a synchronous call.

Arguments mapping described in
[GetBucketPolicyRequestRequestTypeDef](./type_defs.md#getbucketpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

Returns a `Coroutine` for
[GetBucketPolicyResultTypeDef](./type_defs.md#getbucketpolicyresulttypedef).

<a id="get\_bucket\_tagging"></a>

### get_bucket_tagging

.

Type annotations for `session.create_client("s3control").get_bucket_tagging`
method.

Boto3 documentation:
[S3Control.Client.get_bucket_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_tagging)

Asynchronous method. Use `await get_bucket_tagging(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketTaggingRequestRequestTypeDef](./type_defs.md#getbuckettaggingrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*

Returns a `Coroutine` for
[GetBucketTaggingResultTypeDef](./type_defs.md#getbuckettaggingresulttypedef).

<a id="get\_job\_tagging"></a>

### get_job_tagging

Returns the tags on an S3 Batch Operations job.

Type annotations for `session.create_client("s3control").get_job_tagging`
method.

Boto3 documentation:
[S3Control.Client.get_job_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_job_tagging)

Asynchronous method. Use `await get_job_tagging(...)` for a synchronous call.

Arguments mapping described in
[GetJobTaggingRequestRequestTypeDef](./type_defs.md#getjobtaggingrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `JobId`: `str` *(required)*

Returns a `Coroutine` for
[GetJobTaggingResultTypeDef](./type_defs.md#getjobtaggingresulttypedef).

<a id="get\_multi\_region\_access\_point"></a>

### get_multi_region_access_point

Returns configuration information about the specified Multi-Region Access
Point.

Type annotations for
`session.create_client("s3control").get_multi_region_access_point` method.

Boto3 documentation:
[S3Control.Client.get_multi_region_access_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_multi_region_access_point)

Asynchronous method. Use `await get_multi_region_access_point(...)` for a
synchronous call.

Arguments mapping described in
[GetMultiRegionAccessPointRequestRequestTypeDef](./type_defs.md#getmultiregionaccesspointrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetMultiRegionAccessPointResultTypeDef](./type_defs.md#getmultiregionaccesspointresulttypedef).

<a id="get\_multi\_region\_access\_point\_policy"></a>

### get_multi_region_access_point_policy

Returns the access control policy of the specified Multi-Region Access Point.

Type annotations for
`session.create_client("s3control").get_multi_region_access_point_policy`
method.

Boto3 documentation:
[S3Control.Client.get_multi_region_access_point_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_multi_region_access_point_policy)

Asynchronous method. Use `await get_multi_region_access_point_policy(...)` for
a synchronous call.

Arguments mapping described in
[GetMultiRegionAccessPointPolicyRequestRequestTypeDef](./type_defs.md#getmultiregionaccesspointpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetMultiRegionAccessPointPolicyResultTypeDef](./type_defs.md#getmultiregionaccesspointpolicyresulttypedef).

<a id="get\_multi\_region\_access\_point\_policy\_status"></a>

### get_multi_region_access_point_policy_status

Indicates whether the specified Multi-Region Access Point has an access control
policy that allows public access.

Type annotations for
`session.create_client("s3control").get_multi_region_access_point_policy_status`
method.

Boto3 documentation:
[S3Control.Client.get_multi_region_access_point_policy_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_multi_region_access_point_policy_status)

Asynchronous method. Use
`await get_multi_region_access_point_policy_status(...)` for a synchronous
call.

Arguments mapping described in
[GetMultiRegionAccessPointPolicyStatusRequestRequestTypeDef](./type_defs.md#getmultiregionaccesspointpolicystatusrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*

Returns a `Coroutine` for
[GetMultiRegionAccessPointPolicyStatusResultTypeDef](./type_defs.md#getmultiregionaccesspointpolicystatusresulttypedef).

<a id="get\_public\_access\_block"></a>

### get_public_access_block

Retrieves the `PublicAccessBlock` configuration for an Amazon Web Services
account.

Type annotations for
`session.create_client("s3control").get_public_access_block` method.

Boto3 documentation:
[S3Control.Client.get_public_access_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_public_access_block)

Asynchronous method. Use `await get_public_access_block(...)` for a synchronous
call.

Arguments mapping described in
[GetPublicAccessBlockRequestRequestTypeDef](./type_defs.md#getpublicaccessblockrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*

Returns a `Coroutine` for
[GetPublicAccessBlockOutputTypeDef](./type_defs.md#getpublicaccessblockoutputtypedef).

<a id="get\_storage\_lens\_configuration"></a>

### get_storage_lens_configuration

Gets the Amazon S3 Storage Lens configuration.

Type annotations for
`session.create_client("s3control").get_storage_lens_configuration` method.

Boto3 documentation:
[S3Control.Client.get_storage_lens_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_storage_lens_configuration)

Asynchronous method. Use `await get_storage_lens_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetStorageLensConfigurationRequestRequestTypeDef](./type_defs.md#getstoragelensconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ConfigId`: `str` *(required)*
- `AccountId`: `str` *(required)*

Returns a `Coroutine` for
[GetStorageLensConfigurationResultTypeDef](./type_defs.md#getstoragelensconfigurationresulttypedef).

<a id="get\_storage\_lens\_configuration\_tagging"></a>

### get_storage_lens_configuration_tagging

Gets the tags of Amazon S3 Storage Lens configuration.

Type annotations for
`session.create_client("s3control").get_storage_lens_configuration_tagging`
method.

Boto3 documentation:
[S3Control.Client.get_storage_lens_configuration_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_storage_lens_configuration_tagging)

Asynchronous method. Use `await get_storage_lens_configuration_tagging(...)`
for a synchronous call.

Arguments mapping described in
[GetStorageLensConfigurationTaggingRequestRequestTypeDef](./type_defs.md#getstoragelensconfigurationtaggingrequestrequesttypedef).

Keyword-only arguments:

- `ConfigId`: `str` *(required)*
- `AccountId`: `str` *(required)*

Returns a `Coroutine` for
[GetStorageLensConfigurationTaggingResultTypeDef](./type_defs.md#getstoragelensconfigurationtaggingresulttypedef).

<a id="list\_access\_points"></a>

### list_access_points

Returns a list of the access points currently associated with the specified
bucket.

Type annotations for `session.create_client("s3control").list_access_points`
method.

Boto3 documentation:
[S3Control.Client.list_access_points](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_access_points)

Asynchronous method. Use `await list_access_points(...)` for a synchronous
call.

Arguments mapping described in
[ListAccessPointsRequestRequestTypeDef](./type_defs.md#listaccesspointsrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListAccessPointsResultTypeDef](./type_defs.md#listaccesspointsresulttypedef).

<a id="list\_access\_points\_for\_object\_lambda"></a>

### list_access_points_for_object_lambda

Returns some or all (up to 1,000) access points associated with the Object
Lambda Access Point per call.

Type annotations for
`session.create_client("s3control").list_access_points_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.list_access_points_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_access_points_for_object_lambda)

Asynchronous method. Use `await list_access_points_for_object_lambda(...)` for
a synchronous call.

Arguments mapping described in
[ListAccessPointsForObjectLambdaRequestRequestTypeDef](./type_defs.md#listaccesspointsforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListAccessPointsForObjectLambdaResultTypeDef](./type_defs.md#listaccesspointsforobjectlambdaresulttypedef).

<a id="list\_jobs"></a>

### list_jobs

Lists current S3 Batch Operations jobs and jobs that have ended within the last
30 days for the Amazon Web Services account making the request.

Type annotations for `session.create_client("s3control").list_jobs` method.

Boto3 documentation:
[S3Control.Client.list_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_jobs)

Asynchronous method. Use `await list_jobs(...)` for a synchronous call.

Arguments mapping described in
[ListJobsRequestRequestTypeDef](./type_defs.md#listjobsrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `JobStatuses`: `Sequence`\[[JobStatusType](./literals.md#jobstatustype)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListJobsResultTypeDef](./type_defs.md#listjobsresulttypedef).

<a id="list\_multi\_region\_access\_points"></a>

### list_multi_region_access_points

Returns a list of the Multi-Region Access Points currently associated with the
specified Amazon Web Services account.

Type annotations for
`session.create_client("s3control").list_multi_region_access_points` method.

Boto3 documentation:
[S3Control.Client.list_multi_region_access_points](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_multi_region_access_points)

Asynchronous method. Use `await list_multi_region_access_points(...)` for a
synchronous call.

Arguments mapping described in
[ListMultiRegionAccessPointsRequestRequestTypeDef](./type_defs.md#listmultiregionaccesspointsrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListMultiRegionAccessPointsResultTypeDef](./type_defs.md#listmultiregionaccesspointsresulttypedef).

<a id="list\_regional\_buckets"></a>

### list_regional_buckets

Returns a list of all Outposts buckets in an Outpost that are owned by the
authenticated sender of the request.

Type annotations for `session.create_client("s3control").list_regional_buckets`
method.

Boto3 documentation:
[S3Control.Client.list_regional_buckets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_regional_buckets)

Asynchronous method. Use `await list_regional_buckets(...)` for a synchronous
call.

Arguments mapping described in
[ListRegionalBucketsRequestRequestTypeDef](./type_defs.md#listregionalbucketsrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `OutpostId`: `str`

Returns a `Coroutine` for
[ListRegionalBucketsResultTypeDef](./type_defs.md#listregionalbucketsresulttypedef).

<a id="list\_storage\_lens\_configurations"></a>

### list_storage_lens_configurations

Gets a list of Amazon S3 Storage Lens configurations.

Type annotations for
`session.create_client("s3control").list_storage_lens_configurations` method.

Boto3 documentation:
[S3Control.Client.list_storage_lens_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_storage_lens_configurations)

Asynchronous method. Use `await list_storage_lens_configurations(...)` for a
synchronous call.

Arguments mapping described in
[ListStorageLensConfigurationsRequestRequestTypeDef](./type_defs.md#liststoragelensconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[ListStorageLensConfigurationsResultTypeDef](./type_defs.md#liststoragelensconfigurationsresulttypedef).

<a id="put\_access\_point\_configuration\_for\_object\_lambda"></a>

### put_access_point_configuration_for_object_lambda

Replaces configuration for an Object Lambda Access Point.

Type annotations for
`session.create_client("s3control").put_access_point_configuration_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.put_access_point_configuration_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_access_point_configuration_for_object_lambda)

Asynchronous method. Use
`await put_access_point_configuration_for_object_lambda(...)` for a synchronous
call.

Arguments mapping described in
[PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef](./type_defs.md#putaccesspointconfigurationforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Configuration`:
  [ObjectLambdaConfigurationTypeDef](./type_defs.md#objectlambdaconfigurationtypedef)
  *(required)*

<a id="put\_access\_point\_policy"></a>

### put_access_point_policy

Associates an access policy with the specified access point.

Type annotations for
`session.create_client("s3control").put_access_point_policy` method.

Boto3 documentation:
[S3Control.Client.put_access_point_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_access_point_policy)

Asynchronous method. Use `await put_access_point_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutAccessPointPolicyRequestRequestTypeDef](./type_defs.md#putaccesspointpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Policy`: `str` *(required)*

<a id="put\_access\_point\_policy\_for\_object\_lambda"></a>

### put_access_point_policy_for_object_lambda

Creates or replaces resource policy for an Object Lambda Access Point.

Type annotations for
`session.create_client("s3control").put_access_point_policy_for_object_lambda`
method.

Boto3 documentation:
[S3Control.Client.put_access_point_policy_for_object_lambda](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_access_point_policy_for_object_lambda)

Asynchronous method. Use `await put_access_point_policy_for_object_lambda(...)`
for a synchronous call.

Arguments mapping described in
[PutAccessPointPolicyForObjectLambdaRequestRequestTypeDef](./type_defs.md#putaccesspointpolicyforobjectlambdarequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Policy`: `str` *(required)*

<a id="put\_bucket\_lifecycle\_configuration"></a>

### put_bucket_lifecycle_configuration

.

Type annotations for
`session.create_client("s3control").put_bucket_lifecycle_configuration` method.

Boto3 documentation:
[S3Control.Client.put_bucket_lifecycle_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_lifecycle_configuration)

Asynchronous method. Use `await put_bucket_lifecycle_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutBucketLifecycleConfigurationRequestRequestTypeDef](./type_defs.md#putbucketlifecycleconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*
- `LifecycleConfiguration`:
  [LifecycleConfigurationTypeDef](./type_defs.md#lifecycleconfigurationtypedef)

<a id="put\_bucket\_policy"></a>

### put_bucket_policy

.

Type annotations for `session.create_client("s3control").put_bucket_policy`
method.

Boto3 documentation:
[S3Control.Client.put_bucket_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_policy)

Asynchronous method. Use `await put_bucket_policy(...)` for a synchronous call.

Arguments mapping described in
[PutBucketPolicyRequestRequestTypeDef](./type_defs.md#putbucketpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*
- `Policy`: `str` *(required)*
- `ConfirmRemoveSelfBucketAccess`: `bool`

<a id="put\_bucket\_tagging"></a>

### put_bucket_tagging

.

Type annotations for `session.create_client("s3control").put_bucket_tagging`
method.

Boto3 documentation:
[S3Control.Client.put_bucket_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_tagging)

Asynchronous method. Use `await put_bucket_tagging(...)` for a synchronous
call.

Arguments mapping described in
[PutBucketTaggingRequestRequestTypeDef](./type_defs.md#putbuckettaggingrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `Bucket`: `str` *(required)*
- `Tagging`: [TaggingTypeDef](./type_defs.md#taggingtypedef) *(required)*

<a id="put\_job\_tagging"></a>

### put_job_tagging

Sets the supplied tag-set on an S3 Batch Operations job.

Type annotations for `session.create_client("s3control").put_job_tagging`
method.

Boto3 documentation:
[S3Control.Client.put_job_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_job_tagging)

Asynchronous method. Use `await put_job_tagging(...)` for a synchronous call.

Arguments mapping described in
[PutJobTaggingRequestRequestTypeDef](./type_defs.md#putjobtaggingrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `JobId`: `str` *(required)*
- `Tags`: `Sequence`\[[S3TagTypeDef](./type_defs.md#s3tagtypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="put\_multi\_region\_access\_point\_policy"></a>

### put_multi_region_access_point_policy

Associates an access control policy with the specified Multi-Region Access
Point.

Type annotations for
`session.create_client("s3control").put_multi_region_access_point_policy`
method.

Boto3 documentation:
[S3Control.Client.put_multi_region_access_point_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_multi_region_access_point_policy)

Asynchronous method. Use `await put_multi_region_access_point_policy(...)` for
a synchronous call.

Arguments mapping described in
[PutMultiRegionAccessPointPolicyRequestRequestTypeDef](./type_defs.md#putmultiregionaccesspointpolicyrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `Details`:
  [PutMultiRegionAccessPointPolicyInputTypeDef](./type_defs.md#putmultiregionaccesspointpolicyinputtypedef)
  *(required)*

Returns a `Coroutine` for
[PutMultiRegionAccessPointPolicyResultTypeDef](./type_defs.md#putmultiregionaccesspointpolicyresulttypedef).

<a id="put\_public\_access\_block"></a>

### put_public_access_block

Creates or modifies the `PublicAccessBlock` configuration for an Amazon Web
Services account.

Type annotations for
`session.create_client("s3control").put_public_access_block` method.

Boto3 documentation:
[S3Control.Client.put_public_access_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_public_access_block)

Asynchronous method. Use `await put_public_access_block(...)` for a synchronous
call.

Arguments mapping described in
[PutPublicAccessBlockRequestRequestTypeDef](./type_defs.md#putpublicaccessblockrequestrequesttypedef).

Keyword-only arguments:

- `PublicAccessBlockConfiguration`:
  [PublicAccessBlockConfigurationTypeDef](./type_defs.md#publicaccessblockconfigurationtypedef)
  *(required)*
- `AccountId`: `str` *(required)*

<a id="put\_storage\_lens\_configuration"></a>

### put_storage_lens_configuration

Puts an Amazon S3 Storage Lens configuration.

Type annotations for
`session.create_client("s3control").put_storage_lens_configuration` method.

Boto3 documentation:
[S3Control.Client.put_storage_lens_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_storage_lens_configuration)

Asynchronous method. Use `await put_storage_lens_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutStorageLensConfigurationRequestRequestTypeDef](./type_defs.md#putstoragelensconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ConfigId`: `str` *(required)*
- `AccountId`: `str` *(required)*
- `StorageLensConfiguration`:
  [StorageLensConfigurationTypeDef](./type_defs.md#storagelensconfigurationtypedef)
  *(required)*
- `Tags`:
  `Sequence`\[[StorageLensTagTypeDef](./type_defs.md#storagelenstagtypedef)\]

<a id="put\_storage\_lens\_configuration\_tagging"></a>

### put_storage_lens_configuration_tagging

Put or replace tags on an existing Amazon S3 Storage Lens configuration.

Type annotations for
`session.create_client("s3control").put_storage_lens_configuration_tagging`
method.

Boto3 documentation:
[S3Control.Client.put_storage_lens_configuration_tagging](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_storage_lens_configuration_tagging)

Asynchronous method. Use `await put_storage_lens_configuration_tagging(...)`
for a synchronous call.

Arguments mapping described in
[PutStorageLensConfigurationTaggingRequestRequestTypeDef](./type_defs.md#putstoragelensconfigurationtaggingrequestrequesttypedef).

Keyword-only arguments:

- `ConfigId`: `str` *(required)*
- `AccountId`: `str` *(required)*
- `Tags`:
  `Sequence`\[[StorageLensTagTypeDef](./type_defs.md#storagelenstagtypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_job\_priority"></a>

### update_job_priority

Updates an existing S3 Batch Operations job's priority.

Type annotations for `session.create_client("s3control").update_job_priority`
method.

Boto3 documentation:
[S3Control.Client.update_job_priority](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.update_job_priority)

Asynchronous method. Use `await update_job_priority(...)` for a synchronous
call.

Arguments mapping described in
[UpdateJobPriorityRequestRequestTypeDef](./type_defs.md#updatejobpriorityrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `JobId`: `str` *(required)*
- `Priority`: `int` *(required)*

Returns a `Coroutine` for
[UpdateJobPriorityResultTypeDef](./type_defs.md#updatejobpriorityresulttypedef).

<a id="update\_job\_status"></a>

### update_job_status

Updates the status for the specified job.

Type annotations for `session.create_client("s3control").update_job_status`
method.

Boto3 documentation:
[S3Control.Client.update_job_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.update_job_status)

Asynchronous method. Use `await update_job_status(...)` for a synchronous call.

Arguments mapping described in
[UpdateJobStatusRequestRequestTypeDef](./type_defs.md#updatejobstatusrequestrequesttypedef).

Keyword-only arguments:

- `AccountId`: `str` *(required)*
- `JobId`: `str` *(required)*
- `RequestedJobStatus`:
  [RequestedJobStatusType](./literals.md#requestedjobstatustype) *(required)*
- `StatusUpdateReason`: `str`

Returns a `Coroutine` for
[UpdateJobStatusResultTypeDef](./type_defs.md#updatejobstatusresulttypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("s3control").__aenter__` method.

Boto3 documentation:
[S3Control.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [S3ControlClient](#s3controlclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("s3control").__aexit__` method.

Boto3 documentation:
[S3Control.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("s3control").get_paginator` method
with overloads.

- `client.get_paginator("list_access_points_for_object_lambda")` ->
  [ListAccessPointsForObjectLambdaPaginator](./paginators.md#listaccesspointsforobjectlambdapaginator)
