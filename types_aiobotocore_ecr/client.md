<a id="ecrclient-for-aiobotocore-ecr-module"></a>

# ECRClient for aiobotocore ECR module

> [Index](..) > [ECR](.) > ECRClient

Auto-generated documentation for
[ECR](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR)
type annotations stubs module
[types-aiobotocore-ecr](https://pypi.org/project/types-aiobotocore-ecr/).

- [ECRClient for aiobotocore ECR module](#ecrclient-for-aiobotocore-ecr-module)
  - [ECRClient](#ecrclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [batch_check_layer_availability](#batch_check_layer_availability)
    - [batch_delete_image](#batch_delete_image)
    - [batch_get_image](#batch_get_image)
    - [batch_get_repository_scanning_configuration](#batch_get_repository_scanning_configuration)
    - [can_paginate](#can_paginate)
    - [complete_layer_upload](#complete_layer_upload)
    - [create_pull_through_cache_rule](#create_pull_through_cache_rule)
    - [create_repository](#create_repository)
    - [delete_lifecycle_policy](#delete_lifecycle_policy)
    - [delete_pull_through_cache_rule](#delete_pull_through_cache_rule)
    - [delete_registry_policy](#delete_registry_policy)
    - [delete_repository](#delete_repository)
    - [delete_repository_policy](#delete_repository_policy)
    - [describe_image_replication_status](#describe_image_replication_status)
    - [describe_image_scan_findings](#describe_image_scan_findings)
    - [describe_images](#describe_images)
    - [describe_pull_through_cache_rules](#describe_pull_through_cache_rules)
    - [describe_registry](#describe_registry)
    - [describe_repositories](#describe_repositories)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_authorization_token](#get_authorization_token)
    - [get_download_url_for_layer](#get_download_url_for_layer)
    - [get_lifecycle_policy](#get_lifecycle_policy)
    - [get_lifecycle_policy_preview](#get_lifecycle_policy_preview)
    - [get_registry_policy](#get_registry_policy)
    - [get_registry_scanning_configuration](#get_registry_scanning_configuration)
    - [get_repository_policy](#get_repository_policy)
    - [initiate_layer_upload](#initiate_layer_upload)
    - [list_images](#list_images)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_image](#put_image)
    - [put_image_scanning_configuration](#put_image_scanning_configuration)
    - [put_image_tag_mutability](#put_image_tag_mutability)
    - [put_lifecycle_policy](#put_lifecycle_policy)
    - [put_registry_policy](#put_registry_policy)
    - [put_registry_scanning_configuration](#put_registry_scanning_configuration)
    - [put_replication_configuration](#put_replication_configuration)
    - [set_repository_policy](#set_repository_policy)
    - [start_image_scan](#start_image_scan)
    - [start_lifecycle_policy_preview](#start_lifecycle_policy_preview)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [upload_layer_part](#upload_layer_part)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="ecrclient"></a>

## ECRClient

Type annotations for `aiobotocore.create_client("ecr")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_ecr.client import ECRClient

def get_ecr_client() -> ECRClient:
    return Session().client("ecr")
```

Boto3 documentation:
[ECR.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ecr.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.EmptyUploadException`
- `Exceptions.ImageAlreadyExistsException`
- `Exceptions.ImageDigestDoesNotMatchException`
- `Exceptions.ImageNotFoundException`
- `Exceptions.ImageTagAlreadyExistsException`
- `Exceptions.InvalidLayerException`
- `Exceptions.InvalidLayerPartException`
- `Exceptions.InvalidParameterException`
- `Exceptions.InvalidTagParameterException`
- `Exceptions.KmsException`
- `Exceptions.LayerAlreadyExistsException`
- `Exceptions.LayerInaccessibleException`
- `Exceptions.LayerPartTooSmallException`
- `Exceptions.LayersNotFoundException`
- `Exceptions.LifecyclePolicyNotFoundException`
- `Exceptions.LifecyclePolicyPreviewInProgressException`
- `Exceptions.LifecyclePolicyPreviewNotFoundException`
- `Exceptions.LimitExceededException`
- `Exceptions.PullThroughCacheRuleAlreadyExistsException`
- `Exceptions.PullThroughCacheRuleNotFoundException`
- `Exceptions.ReferencedImagesNotFoundException`
- `Exceptions.RegistryPolicyNotFoundException`
- `Exceptions.RepositoryAlreadyExistsException`
- `Exceptions.RepositoryNotEmptyException`
- `Exceptions.RepositoryNotFoundException`
- `Exceptions.RepositoryPolicyNotFoundException`
- `Exceptions.ScanNotFoundException`
- `Exceptions.ServerException`
- `Exceptions.TooManyTagsException`
- `Exceptions.UnsupportedImageTypeException`
- `Exceptions.UnsupportedUpstreamRegistryException`
- `Exceptions.UploadNotFoundException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ECRClient exceptions.

Type annotations for `aiobotocore.create_client("ecr").exceptions` method.

Boto3 documentation:
[ECR.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="batch_check_layer_availability"></a>

### batch_check_layer_availability

Checks the availability of one or more image layers in a repository.

Type annotations for
`aiobotocore.create_client("ecr").batch_check_layer_availability` method.

Boto3 documentation:
[ECR.Client.batch_check_layer_availability](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.batch_check_layer_availability)

Asynchronous method. Use `await batch_check_layer_availability(...)` for a
synchronous call.

Arguments mapping described in
[BatchCheckLayerAvailabilityRequestRequestTypeDef](./type_defs.md#batchchecklayeravailabilityrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `layerDigests`: `Sequence`\[`str`\] *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[BatchCheckLayerAvailabilityResponseTypeDef](./type_defs.md#batchchecklayeravailabilityresponsetypedef).

<a id="batch_delete_image"></a>

### batch_delete_image

Deletes a list of specified images within a repository.

Type annotations for `aiobotocore.create_client("ecr").batch_delete_image`
method.

Boto3 documentation:
[ECR.Client.batch_delete_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.batch_delete_image)

Asynchronous method. Use `await batch_delete_image(...)` for a synchronous
call.

Arguments mapping described in
[BatchDeleteImageRequestRequestTypeDef](./type_defs.md#batchdeleteimagerequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageIds`:
  `Sequence`\[[ImageIdentifierTypeDef](./type_defs.md#imageidentifiertypedef)\]
  *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[BatchDeleteImageResponseTypeDef](./type_defs.md#batchdeleteimageresponsetypedef).

<a id="batch_get_image"></a>

### batch_get_image

Gets detailed information for an image.

Type annotations for `aiobotocore.create_client("ecr").batch_get_image` method.

Boto3 documentation:
[ECR.Client.batch_get_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.batch_get_image)

Asynchronous method. Use `await batch_get_image(...)` for a synchronous call.

Arguments mapping described in
[BatchGetImageRequestRequestTypeDef](./type_defs.md#batchgetimagerequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageIds`:
  `Sequence`\[[ImageIdentifierTypeDef](./type_defs.md#imageidentifiertypedef)\]
  *(required)*
- `registryId`: `str`
- `acceptedMediaTypes`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[BatchGetImageResponseTypeDef](./type_defs.md#batchgetimageresponsetypedef).

<a id="batch_get_repository_scanning_configuration"></a>

### batch_get_repository_scanning_configuration

Gets the scanning configuration for one or more repositories.

Type annotations for
`aiobotocore.create_client("ecr").batch_get_repository_scanning_configuration`
method.

Boto3 documentation:
[ECR.Client.batch_get_repository_scanning_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.batch_get_repository_scanning_configuration)

Asynchronous method. Use
`await batch_get_repository_scanning_configuration(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetRepositoryScanningConfigurationRequestRequestTypeDef](./type_defs.md#batchgetrepositoryscanningconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `repositoryNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetRepositoryScanningConfigurationResponseTypeDef](./type_defs.md#batchgetrepositoryscanningconfigurationresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("ecr").can_paginate` method.

Boto3 documentation:
[ECR.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="complete_layer_upload"></a>

### complete_layer_upload

Informs Amazon ECR that the image layer upload has completed for a specified
registry, repository name, and upload ID.

Type annotations for `aiobotocore.create_client("ecr").complete_layer_upload`
method.

Boto3 documentation:
[ECR.Client.complete_layer_upload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.complete_layer_upload)

Asynchronous method. Use `await complete_layer_upload(...)` for a synchronous
call.

Arguments mapping described in
[CompleteLayerUploadRequestRequestTypeDef](./type_defs.md#completelayeruploadrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `uploadId`: `str` *(required)*
- `layerDigests`: `Sequence`\[`str`\] *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[CompleteLayerUploadResponseTypeDef](./type_defs.md#completelayeruploadresponsetypedef).

<a id="create_pull_through_cache_rule"></a>

### create_pull_through_cache_rule

Creates a pull through cache rule.

Type annotations for
`aiobotocore.create_client("ecr").create_pull_through_cache_rule` method.

Boto3 documentation:
[ECR.Client.create_pull_through_cache_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.create_pull_through_cache_rule)

Asynchronous method. Use `await create_pull_through_cache_rule(...)` for a
synchronous call.

Arguments mapping described in
[CreatePullThroughCacheRuleRequestRequestTypeDef](./type_defs.md#createpullthroughcacherulerequestrequesttypedef).

Keyword-only arguments:

- `ecrRepositoryPrefix`: `str` *(required)*
- `upstreamRegistryUrl`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[CreatePullThroughCacheRuleResponseTypeDef](./type_defs.md#createpullthroughcacheruleresponsetypedef).

<a id="create_repository"></a>

### create_repository

Creates a repository.

Type annotations for `aiobotocore.create_client("ecr").create_repository`
method.

Boto3 documentation:
[ECR.Client.create_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.create_repository)

Asynchronous method. Use `await create_repository(...)` for a synchronous call.

Arguments mapping described in
[CreateRepositoryRequestRequestTypeDef](./type_defs.md#createrepositoryrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `imageTagMutability`:
  [ImageTagMutabilityType](./literals.md#imagetagmutabilitytype)
- `imageScanningConfiguration`:
  [ImageScanningConfigurationTypeDef](./type_defs.md#imagescanningconfigurationtypedef)
- `encryptionConfiguration`:
  [EncryptionConfigurationTypeDef](./type_defs.md#encryptionconfigurationtypedef)

Returns a `Coroutine` for
[CreateRepositoryResponseTypeDef](./type_defs.md#createrepositoryresponsetypedef).

<a id="delete_lifecycle_policy"></a>

### delete_lifecycle_policy

Deletes the lifecycle policy associated with the specified repository.

Type annotations for `aiobotocore.create_client("ecr").delete_lifecycle_policy`
method.

Boto3 documentation:
[ECR.Client.delete_lifecycle_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.delete_lifecycle_policy)

Asynchronous method. Use `await delete_lifecycle_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLifecyclePolicyRequestRequestTypeDef](./type_defs.md#deletelifecyclepolicyrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[DeleteLifecyclePolicyResponseTypeDef](./type_defs.md#deletelifecyclepolicyresponsetypedef).

<a id="delete_pull_through_cache_rule"></a>

### delete_pull_through_cache_rule

Deletes a pull through cache rule.

Type annotations for
`aiobotocore.create_client("ecr").delete_pull_through_cache_rule` method.

Boto3 documentation:
[ECR.Client.delete_pull_through_cache_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.delete_pull_through_cache_rule)

Asynchronous method. Use `await delete_pull_through_cache_rule(...)` for a
synchronous call.

Arguments mapping described in
[DeletePullThroughCacheRuleRequestRequestTypeDef](./type_defs.md#deletepullthroughcacherulerequestrequesttypedef).

Keyword-only arguments:

- `ecrRepositoryPrefix`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[DeletePullThroughCacheRuleResponseTypeDef](./type_defs.md#deletepullthroughcacheruleresponsetypedef).

<a id="delete_registry_policy"></a>

### delete_registry_policy

Deletes the registry permissions policy.

Type annotations for `aiobotocore.create_client("ecr").delete_registry_policy`
method.

Boto3 documentation:
[ECR.Client.delete_registry_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.delete_registry_policy)

Asynchronous method. Use `await delete_registry_policy(...)` for a synchronous
call.

Returns a `Coroutine` for
[DeleteRegistryPolicyResponseTypeDef](./type_defs.md#deleteregistrypolicyresponsetypedef).

<a id="delete_repository"></a>

### delete_repository

Deletes a repository.

Type annotations for `aiobotocore.create_client("ecr").delete_repository`
method.

Boto3 documentation:
[ECR.Client.delete_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.delete_repository)

Asynchronous method. Use `await delete_repository(...)` for a synchronous call.

Arguments mapping described in
[DeleteRepositoryRequestRequestTypeDef](./type_defs.md#deleterepositoryrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`
- `force`: `bool`

Returns a `Coroutine` for
[DeleteRepositoryResponseTypeDef](./type_defs.md#deleterepositoryresponsetypedef).

<a id="delete_repository_policy"></a>

### delete_repository_policy

Deletes the repository policy associated with the specified repository.

Type annotations for
`aiobotocore.create_client("ecr").delete_repository_policy` method.

Boto3 documentation:
[ECR.Client.delete_repository_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.delete_repository_policy)

Asynchronous method. Use `await delete_repository_policy(...)` for a
synchronous call.

Arguments mapping described in
[DeleteRepositoryPolicyRequestRequestTypeDef](./type_defs.md#deleterepositorypolicyrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[DeleteRepositoryPolicyResponseTypeDef](./type_defs.md#deleterepositorypolicyresponsetypedef).

<a id="describe_image_replication_status"></a>

### describe_image_replication_status

Returns the replication status for a specified image.

Type annotations for
`aiobotocore.create_client("ecr").describe_image_replication_status` method.

Boto3 documentation:
[ECR.Client.describe_image_replication_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.describe_image_replication_status)

Asynchronous method. Use `await describe_image_replication_status(...)` for a
synchronous call.

Arguments mapping described in
[DescribeImageReplicationStatusRequestRequestTypeDef](./type_defs.md#describeimagereplicationstatusrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageId`: [ImageIdentifierTypeDef](./type_defs.md#imageidentifiertypedef)
  *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[DescribeImageReplicationStatusResponseTypeDef](./type_defs.md#describeimagereplicationstatusresponsetypedef).

<a id="describe_image_scan_findings"></a>

### describe_image_scan_findings

Returns the scan findings for the specified image.

Type annotations for
`aiobotocore.create_client("ecr").describe_image_scan_findings` method.

Boto3 documentation:
[ECR.Client.describe_image_scan_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.describe_image_scan_findings)

Asynchronous method. Use `await describe_image_scan_findings(...)` for a
synchronous call.

Arguments mapping described in
[DescribeImageScanFindingsRequestRequestTypeDef](./type_defs.md#describeimagescanfindingsrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageId`: [ImageIdentifierTypeDef](./type_defs.md#imageidentifiertypedef)
  *(required)*
- `registryId`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[DescribeImageScanFindingsResponseTypeDef](./type_defs.md#describeimagescanfindingsresponsetypedef).

<a id="describe_images"></a>

### describe_images

Returns metadata about the images in a repository.

Type annotations for `aiobotocore.create_client("ecr").describe_images` method.

Boto3 documentation:
[ECR.Client.describe_images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.describe_images)

Asynchronous method. Use `await describe_images(...)` for a synchronous call.

Arguments mapping described in
[DescribeImagesRequestRequestTypeDef](./type_defs.md#describeimagesrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`
- `imageIds`:
  `Sequence`\[[ImageIdentifierTypeDef](./type_defs.md#imageidentifiertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`
- `filter`:
  [DescribeImagesFilterTypeDef](./type_defs.md#describeimagesfiltertypedef)

Returns a `Coroutine` for
[DescribeImagesResponseTypeDef](./type_defs.md#describeimagesresponsetypedef).

<a id="describe_pull_through_cache_rules"></a>

### describe_pull_through_cache_rules

Returns the pull through cache rules for a registry.

Type annotations for
`aiobotocore.create_client("ecr").describe_pull_through_cache_rules` method.

Boto3 documentation:
[ECR.Client.describe_pull_through_cache_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.describe_pull_through_cache_rules)

Asynchronous method. Use `await describe_pull_through_cache_rules(...)` for a
synchronous call.

Arguments mapping described in
[DescribePullThroughCacheRulesRequestRequestTypeDef](./type_defs.md#describepullthroughcacherulesrequestrequesttypedef).

Keyword-only arguments:

- `registryId`: `str`
- `ecrRepositoryPrefixes`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[DescribePullThroughCacheRulesResponseTypeDef](./type_defs.md#describepullthroughcacherulesresponsetypedef).

<a id="describe_registry"></a>

### describe_registry

Describes the settings for a registry.

Type annotations for `aiobotocore.create_client("ecr").describe_registry`
method.

Boto3 documentation:
[ECR.Client.describe_registry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.describe_registry)

Asynchronous method. Use `await describe_registry(...)` for a synchronous call.

Returns a `Coroutine` for
[DescribeRegistryResponseTypeDef](./type_defs.md#describeregistryresponsetypedef).

<a id="describe_repositories"></a>

### describe_repositories

Describes image repositories in a registry.

Type annotations for `aiobotocore.create_client("ecr").describe_repositories`
method.

Boto3 documentation:
[ECR.Client.describe_repositories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.describe_repositories)

Asynchronous method. Use `await describe_repositories(...)` for a synchronous
call.

Arguments mapping described in
[DescribeRepositoriesRequestRequestTypeDef](./type_defs.md#describerepositoriesrequestrequesttypedef).

Keyword-only arguments:

- `registryId`: `str`
- `repositoryNames`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[DescribeRepositoriesResponseTypeDef](./type_defs.md#describerepositoriesresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("ecr").generate_presigned_url`
method.

Boto3 documentation:
[ECR.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_authorization_token"></a>

### get_authorization_token

Retrieves an authorization token.

Type annotations for `aiobotocore.create_client("ecr").get_authorization_token`
method.

Boto3 documentation:
[ECR.Client.get_authorization_token](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.get_authorization_token)

Asynchronous method. Use `await get_authorization_token(...)` for a synchronous
call.

Arguments mapping described in
[GetAuthorizationTokenRequestRequestTypeDef](./type_defs.md#getauthorizationtokenrequestrequesttypedef).

Keyword-only arguments:

- `registryIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[GetAuthorizationTokenResponseTypeDef](./type_defs.md#getauthorizationtokenresponsetypedef).

<a id="get_download_url_for_layer"></a>

### get_download_url_for_layer

Retrieves the pre-signed Amazon S3 download URL corresponding to an image
layer.

Type annotations for
`aiobotocore.create_client("ecr").get_download_url_for_layer` method.

Boto3 documentation:
[ECR.Client.get_download_url_for_layer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.get_download_url_for_layer)

Asynchronous method. Use `await get_download_url_for_layer(...)` for a
synchronous call.

Arguments mapping described in
[GetDownloadUrlForLayerRequestRequestTypeDef](./type_defs.md#getdownloadurlforlayerrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `layerDigest`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[GetDownloadUrlForLayerResponseTypeDef](./type_defs.md#getdownloadurlforlayerresponsetypedef).

<a id="get_lifecycle_policy"></a>

### get_lifecycle_policy

Retrieves the lifecycle policy for the specified repository.

Type annotations for `aiobotocore.create_client("ecr").get_lifecycle_policy`
method.

Boto3 documentation:
[ECR.Client.get_lifecycle_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.get_lifecycle_policy)

Asynchronous method. Use `await get_lifecycle_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetLifecyclePolicyRequestRequestTypeDef](./type_defs.md#getlifecyclepolicyrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[GetLifecyclePolicyResponseTypeDef](./type_defs.md#getlifecyclepolicyresponsetypedef).

<a id="get_lifecycle_policy_preview"></a>

### get_lifecycle_policy_preview

Retrieves the results of the lifecycle policy preview request for the specified
repository.

Type annotations for
`aiobotocore.create_client("ecr").get_lifecycle_policy_preview` method.

Boto3 documentation:
[ECR.Client.get_lifecycle_policy_preview](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.get_lifecycle_policy_preview)

Asynchronous method. Use `await get_lifecycle_policy_preview(...)` for a
synchronous call.

Arguments mapping described in
[GetLifecyclePolicyPreviewRequestRequestTypeDef](./type_defs.md#getlifecyclepolicypreviewrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`
- `imageIds`:
  `Sequence`\[[ImageIdentifierTypeDef](./type_defs.md#imageidentifiertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`
- `filter`:
  [LifecyclePolicyPreviewFilterTypeDef](./type_defs.md#lifecyclepolicypreviewfiltertypedef)

Returns a `Coroutine` for
[GetLifecyclePolicyPreviewResponseTypeDef](./type_defs.md#getlifecyclepolicypreviewresponsetypedef).

<a id="get_registry_policy"></a>

### get_registry_policy

Retrieves the permissions policy for a registry.

Type annotations for `aiobotocore.create_client("ecr").get_registry_policy`
method.

Boto3 documentation:
[ECR.Client.get_registry_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.get_registry_policy)

Asynchronous method. Use `await get_registry_policy(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetRegistryPolicyResponseTypeDef](./type_defs.md#getregistrypolicyresponsetypedef).

<a id="get_registry_scanning_configuration"></a>

### get_registry_scanning_configuration

Retrieves the scanning configuration for a registry.

Type annotations for
`aiobotocore.create_client("ecr").get_registry_scanning_configuration` method.

Boto3 documentation:
[ECR.Client.get_registry_scanning_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.get_registry_scanning_configuration)

Asynchronous method. Use `await get_registry_scanning_configuration(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetRegistryScanningConfigurationResponseTypeDef](./type_defs.md#getregistryscanningconfigurationresponsetypedef).

<a id="get_repository_policy"></a>

### get_repository_policy

Retrieves the repository policy for the specified repository.

Type annotations for `aiobotocore.create_client("ecr").get_repository_policy`
method.

Boto3 documentation:
[ECR.Client.get_repository_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.get_repository_policy)

Asynchronous method. Use `await get_repository_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetRepositoryPolicyRequestRequestTypeDef](./type_defs.md#getrepositorypolicyrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[GetRepositoryPolicyResponseTypeDef](./type_defs.md#getrepositorypolicyresponsetypedef).

<a id="initiate_layer_upload"></a>

### initiate_layer_upload

Notifies Amazon ECR that you intend to upload an image layer.

Type annotations for `aiobotocore.create_client("ecr").initiate_layer_upload`
method.

Boto3 documentation:
[ECR.Client.initiate_layer_upload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.initiate_layer_upload)

Asynchronous method. Use `await initiate_layer_upload(...)` for a synchronous
call.

Arguments mapping described in
[InitiateLayerUploadRequestRequestTypeDef](./type_defs.md#initiatelayeruploadrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[InitiateLayerUploadResponseTypeDef](./type_defs.md#initiatelayeruploadresponsetypedef).

<a id="list_images"></a>

### list_images

Lists all the image IDs for the specified repository.

Type annotations for `aiobotocore.create_client("ecr").list_images` method.

Boto3 documentation:
[ECR.Client.list_images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.list_images)

Asynchronous method. Use `await list_images(...)` for a synchronous call.

Arguments mapping described in
[ListImagesRequestRequestTypeDef](./type_defs.md#listimagesrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`
- `nextToken`: `str`
- `maxResults`: `int`
- `filter`: [ListImagesFilterTypeDef](./type_defs.md#listimagesfiltertypedef)

Returns a `Coroutine` for
[ListImagesResponseTypeDef](./type_defs.md#listimagesresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

List the tags for an Amazon ECR resource.

Type annotations for `aiobotocore.create_client("ecr").list_tags_for_resource`
method.

Boto3 documentation:
[ECR.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_image"></a>

### put_image

Creates or updates the image manifest and tags associated with an image.

Type annotations for `aiobotocore.create_client("ecr").put_image` method.

Boto3 documentation:
[ECR.Client.put_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.put_image)

Asynchronous method. Use `await put_image(...)` for a synchronous call.

Arguments mapping described in
[PutImageRequestRequestTypeDef](./type_defs.md#putimagerequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageManifest`: `str` *(required)*
- `registryId`: `str`
- `imageManifestMediaType`: `str`
- `imageTag`: `str`
- `imageDigest`: `str`

Returns a `Coroutine` for
[PutImageResponseTypeDef](./type_defs.md#putimageresponsetypedef).

<a id="put_image_scanning_configuration"></a>

### put_image_scanning_configuration

Updates the image scanning configuration for the specified repository.

Type annotations for
`aiobotocore.create_client("ecr").put_image_scanning_configuration` method.

Boto3 documentation:
[ECR.Client.put_image_scanning_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.put_image_scanning_configuration)

Asynchronous method. Use `await put_image_scanning_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutImageScanningConfigurationRequestRequestTypeDef](./type_defs.md#putimagescanningconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageScanningConfiguration`:
  [ImageScanningConfigurationTypeDef](./type_defs.md#imagescanningconfigurationtypedef)
  *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[PutImageScanningConfigurationResponseTypeDef](./type_defs.md#putimagescanningconfigurationresponsetypedef).

<a id="put_image_tag_mutability"></a>

### put_image_tag_mutability

Updates the image tag mutability settings for the specified repository.

Type annotations for
`aiobotocore.create_client("ecr").put_image_tag_mutability` method.

Boto3 documentation:
[ECR.Client.put_image_tag_mutability](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.put_image_tag_mutability)

Asynchronous method. Use `await put_image_tag_mutability(...)` for a
synchronous call.

Arguments mapping described in
[PutImageTagMutabilityRequestRequestTypeDef](./type_defs.md#putimagetagmutabilityrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageTagMutability`:
  [ImageTagMutabilityType](./literals.md#imagetagmutabilitytype) *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[PutImageTagMutabilityResponseTypeDef](./type_defs.md#putimagetagmutabilityresponsetypedef).

<a id="put_lifecycle_policy"></a>

### put_lifecycle_policy

Creates or updates the lifecycle policy for the specified repository.

Type annotations for `aiobotocore.create_client("ecr").put_lifecycle_policy`
method.

Boto3 documentation:
[ECR.Client.put_lifecycle_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.put_lifecycle_policy)

Asynchronous method. Use `await put_lifecycle_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutLifecyclePolicyRequestRequestTypeDef](./type_defs.md#putlifecyclepolicyrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `lifecyclePolicyText`: `str` *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[PutLifecyclePolicyResponseTypeDef](./type_defs.md#putlifecyclepolicyresponsetypedef).

<a id="put_registry_policy"></a>

### put_registry_policy

Creates or updates the permissions policy for your registry.

Type annotations for `aiobotocore.create_client("ecr").put_registry_policy`
method.

Boto3 documentation:
[ECR.Client.put_registry_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.put_registry_policy)

Asynchronous method. Use `await put_registry_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutRegistryPolicyRequestRequestTypeDef](./type_defs.md#putregistrypolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyText`: `str` *(required)*

Returns a `Coroutine` for
[PutRegistryPolicyResponseTypeDef](./type_defs.md#putregistrypolicyresponsetypedef).

<a id="put_registry_scanning_configuration"></a>

### put_registry_scanning_configuration

Creates or updates the scanning configuration for your private registry.

Type annotations for
`aiobotocore.create_client("ecr").put_registry_scanning_configuration` method.

Boto3 documentation:
[ECR.Client.put_registry_scanning_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.put_registry_scanning_configuration)

Asynchronous method. Use `await put_registry_scanning_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutRegistryScanningConfigurationRequestRequestTypeDef](./type_defs.md#putregistryscanningconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `scanType`: [ScanTypeType](./literals.md#scantypetype)
- `rules`:
  `Sequence`\[[RegistryScanningRuleTypeDef](./type_defs.md#registryscanningruletypedef)\]

Returns a `Coroutine` for
[PutRegistryScanningConfigurationResponseTypeDef](./type_defs.md#putregistryscanningconfigurationresponsetypedef).

<a id="put_replication_configuration"></a>

### put_replication_configuration

Creates or updates the replication configuration for a registry.

Type annotations for
`aiobotocore.create_client("ecr").put_replication_configuration` method.

Boto3 documentation:
[ECR.Client.put_replication_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.put_replication_configuration)

Asynchronous method. Use `await put_replication_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutReplicationConfigurationRequestRequestTypeDef](./type_defs.md#putreplicationconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `replicationConfiguration`:
  [ReplicationConfigurationTypeDef](./type_defs.md#replicationconfigurationtypedef)
  *(required)*

Returns a `Coroutine` for
[PutReplicationConfigurationResponseTypeDef](./type_defs.md#putreplicationconfigurationresponsetypedef).

<a id="set_repository_policy"></a>

### set_repository_policy

Applies a repository policy to the specified repository to control access
permissions.

Type annotations for `aiobotocore.create_client("ecr").set_repository_policy`
method.

Boto3 documentation:
[ECR.Client.set_repository_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.set_repository_policy)

Asynchronous method. Use `await set_repository_policy(...)` for a synchronous
call.

Arguments mapping described in
[SetRepositoryPolicyRequestRequestTypeDef](./type_defs.md#setrepositorypolicyrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `policyText`: `str` *(required)*
- `registryId`: `str`
- `force`: `bool`

Returns a `Coroutine` for
[SetRepositoryPolicyResponseTypeDef](./type_defs.md#setrepositorypolicyresponsetypedef).

<a id="start_image_scan"></a>

### start_image_scan

Starts an image vulnerability scan.

Type annotations for `aiobotocore.create_client("ecr").start_image_scan`
method.

Boto3 documentation:
[ECR.Client.start_image_scan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.start_image_scan)

Asynchronous method. Use `await start_image_scan(...)` for a synchronous call.

Arguments mapping described in
[StartImageScanRequestRequestTypeDef](./type_defs.md#startimagescanrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `imageId`: [ImageIdentifierTypeDef](./type_defs.md#imageidentifiertypedef)
  *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[StartImageScanResponseTypeDef](./type_defs.md#startimagescanresponsetypedef).

<a id="start_lifecycle_policy_preview"></a>

### start_lifecycle_policy_preview

Starts a preview of a lifecycle policy for the specified repository.

Type annotations for
`aiobotocore.create_client("ecr").start_lifecycle_policy_preview` method.

Boto3 documentation:
[ECR.Client.start_lifecycle_policy_preview](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.start_lifecycle_policy_preview)

Asynchronous method. Use `await start_lifecycle_policy_preview(...)` for a
synchronous call.

Arguments mapping described in
[StartLifecyclePolicyPreviewRequestRequestTypeDef](./type_defs.md#startlifecyclepolicypreviewrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `registryId`: `str`
- `lifecyclePolicyText`: `str`

Returns a `Coroutine` for
[StartLifecyclePolicyPreviewResponseTypeDef](./type_defs.md#startlifecyclepolicypreviewresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds specified tags to a resource with the specified ARN.

Type annotations for `aiobotocore.create_client("ecr").tag_resource` method.

Boto3 documentation:
[ECR.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Deletes specified tags from a resource.

Type annotations for `aiobotocore.create_client("ecr").untag_resource` method.

Boto3 documentation:
[ECR.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="upload_layer_part"></a>

### upload_layer_part

Uploads an image layer part to Amazon ECR.

Type annotations for `aiobotocore.create_client("ecr").upload_layer_part`
method.

Boto3 documentation:
[ECR.Client.upload_layer_part](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Client.upload_layer_part)

Asynchronous method. Use `await upload_layer_part(...)` for a synchronous call.

Arguments mapping described in
[UploadLayerPartRequestRequestTypeDef](./type_defs.md#uploadlayerpartrequestrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `uploadId`: `str` *(required)*
- `partFirstByte`: `int` *(required)*
- `partLastByte`: `int` *(required)*
- `layerPartBlob`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `registryId`: `str`

Returns a `Coroutine` for
[UploadLayerPartResponseTypeDef](./type_defs.md#uploadlayerpartresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("ecr").get_paginator` method
with overloads.

- `client.get_paginator("describe_image_scan_findings")` ->
  [DescribeImageScanFindingsPaginator](./paginators.md#describeimagescanfindingspaginator)
- `client.get_paginator("describe_images")` ->
  [DescribeImagesPaginator](./paginators.md#describeimagespaginator)
- `client.get_paginator("describe_pull_through_cache_rules")` ->
  [DescribePullThroughCacheRulesPaginator](./paginators.md#describepullthroughcacherulespaginator)
- `client.get_paginator("describe_repositories")` ->
  [DescribeRepositoriesPaginator](./paginators.md#describerepositoriespaginator)
- `client.get_paginator("get_lifecycle_policy_preview")` ->
  [GetLifecyclePolicyPreviewPaginator](./paginators.md#getlifecyclepolicypreviewpaginator)
- `client.get_paginator("list_images")` ->
  [ListImagesPaginator](./paginators.md#listimagespaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `aiobotocore.create_client("ecr").get_waiter` method with
overloads.

- `client.get_waiter("image_scan_complete")` ->
  [ImageScanCompleteWaiter](./waiters.md#imagescancompletewaiter)
- `client.get_waiter("lifecycle_policy_preview_complete")` ->
  [LifecyclePolicyPreviewCompleteWaiter](./waiters.md#lifecyclepolicypreviewcompletewaiter)
