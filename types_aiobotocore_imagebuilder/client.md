<a id="imagebuilderclient-for-aiobotocore-imagebuilder-module"></a>

# imagebuilderClient for aiobotocore imagebuilder module

> [Index](..) > [imagebuilder](.) > imagebuilderClient

Auto-generated documentation for
[imagebuilder](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder)
type annotations stubs module
[types-aiobotocore-imagebuilder](https://pypi.org/project/types-aiobotocore-imagebuilder/).

- [imagebuilderClient for aiobotocore imagebuilder module](#imagebuilderclient-for-aiobotocore-imagebuilder-module)
  - [imagebuilderClient](#imagebuilderclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [cancel_image_creation](#cancel_image_creation)
    - [create_component](#create_component)
    - [create_container_recipe](#create_container_recipe)
    - [create_distribution_configuration](#create_distribution_configuration)
    - [create_image](#create_image)
    - [create_image_pipeline](#create_image_pipeline)
    - [create_image_recipe](#create_image_recipe)
    - [create_infrastructure_configuration](#create_infrastructure_configuration)
    - [delete_component](#delete_component)
    - [delete_container_recipe](#delete_container_recipe)
    - [delete_distribution_configuration](#delete_distribution_configuration)
    - [delete_image](#delete_image)
    - [delete_image_pipeline](#delete_image_pipeline)
    - [delete_image_recipe](#delete_image_recipe)
    - [delete_infrastructure_configuration](#delete_infrastructure_configuration)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_component](#get_component)
    - [get_component_policy](#get_component_policy)
    - [get_container_recipe](#get_container_recipe)
    - [get_container_recipe_policy](#get_container_recipe_policy)
    - [get_distribution_configuration](#get_distribution_configuration)
    - [get_image](#get_image)
    - [get_image_pipeline](#get_image_pipeline)
    - [get_image_policy](#get_image_policy)
    - [get_image_recipe](#get_image_recipe)
    - [get_image_recipe_policy](#get_image_recipe_policy)
    - [get_infrastructure_configuration](#get_infrastructure_configuration)
    - [import_component](#import_component)
    - [list_component_build_versions](#list_component_build_versions)
    - [list_components](#list_components)
    - [list_container_recipes](#list_container_recipes)
    - [list_distribution_configurations](#list_distribution_configurations)
    - [list_image_build_versions](#list_image_build_versions)
    - [list_image_packages](#list_image_packages)
    - [list_image_pipeline_images](#list_image_pipeline_images)
    - [list_image_pipelines](#list_image_pipelines)
    - [list_image_recipes](#list_image_recipes)
    - [list_images](#list_images)
    - [list_infrastructure_configurations](#list_infrastructure_configurations)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_component_policy](#put_component_policy)
    - [put_container_recipe_policy](#put_container_recipe_policy)
    - [put_image_policy](#put_image_policy)
    - [put_image_recipe_policy](#put_image_recipe_policy)
    - [start_image_pipeline_execution](#start_image_pipeline_execution)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_distribution_configuration](#update_distribution_configuration)
    - [update_image_pipeline](#update_image_pipeline)
    - [update_infrastructure_configuration](#update_infrastructure_configuration)

<a id="imagebuilderclient"></a>

## imagebuilderClient

Type annotations for `aiobotocore.create_client("imagebuilder")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_imagebuilder.client import imagebuilderClient

def get_imagebuilder_client() -> imagebuilderClient:
    return Session().client("imagebuilder")
```

Boto3 documentation:
[imagebuilder.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_imagebuilder.client import Exceptions

def handle_error(exc: Exceptions.CallRateLimitExceededException) -> None:
    ...
```

Exceptions:

- `Exceptions.CallRateLimitExceededException`
- `Exceptions.ClientError`
- `Exceptions.ClientException`
- `Exceptions.ForbiddenException`
- `Exceptions.IdempotentParameterMismatchException`
- `Exceptions.InvalidPaginationTokenException`
- `Exceptions.InvalidParameterCombinationException`
- `Exceptions.InvalidParameterException`
- `Exceptions.InvalidParameterValueException`
- `Exceptions.InvalidRequestException`
- `Exceptions.InvalidVersionNumberException`
- `Exceptions.ResourceAlreadyExistsException`
- `Exceptions.ResourceDependencyException`
- `Exceptions.ResourceInUseException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ServiceUnavailableException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

imagebuilderClient exceptions.

Type annotations for `aiobotocore.create_client("imagebuilder").exceptions`
method.

Boto3 documentation:
[imagebuilder.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("imagebuilder").can_paginate`
method.

Boto3 documentation:
[imagebuilder.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_image_creation"></a>

### cancel_image_creation

CancelImageCreation cancels the creation of Image.

Type annotations for
`aiobotocore.create_client("imagebuilder").cancel_image_creation` method.

Boto3 documentation:
[imagebuilder.Client.cancel_image_creation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.cancel_image_creation)

Asynchronous method. Use `await cancel_image_creation(...)` for a synchronous
call.

Arguments mapping described in
[CancelImageCreationRequestRequestTypeDef](./type_defs.md#cancelimagecreationrequestrequesttypedef).

Keyword-only arguments:

- `imageBuildVersionArn`: `str` *(required)*
- `clientToken`: `str` *(required)*

Returns a `Coroutine` for
[CancelImageCreationResponseTypeDef](./type_defs.md#cancelimagecreationresponsetypedef).

<a id="create_component"></a>

### create_component

Creates a new component that can be used to build, validate, test, and assess
your image.

Type annotations for
`aiobotocore.create_client("imagebuilder").create_component` method.

Boto3 documentation:
[imagebuilder.Client.create_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_component)

Asynchronous method. Use `await create_component(...)` for a synchronous call.

Arguments mapping described in
[CreateComponentRequestRequestTypeDef](./type_defs.md#createcomponentrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `semanticVersion`: `str` *(required)*
- `platform`: [PlatformType](./literals.md#platformtype) *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `changeDescription`: `str`
- `supportedOsVersions`: `Sequence`\[`str`\]
- `data`: `str`
- `uri`: `str`
- `kmsKeyId`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateComponentResponseTypeDef](./type_defs.md#createcomponentresponsetypedef).

<a id="create_container_recipe"></a>

### create_container_recipe

Creates a new container recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").create_container_recipe` method.

Boto3 documentation:
[imagebuilder.Client.create_container_recipe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_container_recipe)

Asynchronous method. Use `await create_container_recipe(...)` for a synchronous
call.

Arguments mapping described in
[CreateContainerRecipeRequestRequestTypeDef](./type_defs.md#createcontainerreciperequestrequesttypedef).

Keyword-only arguments:

- `containerType`: `Literal['DOCKER']` (see
  [ContainerTypeType](./literals.md#containertypetype)) *(required)*
- `name`: `str` *(required)*
- `semanticVersion`: `str` *(required)*
- `components`:
  `Sequence`\[[ComponentConfigurationTypeDef](./type_defs.md#componentconfigurationtypedef)\]
  *(required)*
- `parentImage`: `str` *(required)*
- `targetRepository`:
  [TargetContainerRepositoryTypeDef](./type_defs.md#targetcontainerrepositorytypedef)
  *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `instanceConfiguration`:
  [InstanceConfigurationTypeDef](./type_defs.md#instanceconfigurationtypedef)
- `dockerfileTemplateData`: `str`
- `dockerfileTemplateUri`: `str`
- `platformOverride`: [PlatformType](./literals.md#platformtype)
- `imageOsVersionOverride`: `str`
- `tags`: `Mapping`\[`str`, `str`\]
- `workingDirectory`: `str`
- `kmsKeyId`: `str`

Returns a `Coroutine` for
[CreateContainerRecipeResponseTypeDef](./type_defs.md#createcontainerreciperesponsetypedef).

<a id="create_distribution_configuration"></a>

### create_distribution_configuration

Creates a new distribution configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").create_distribution_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.create_distribution_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_distribution_configuration)

Asynchronous method. Use `await create_distribution_configuration(...)` for a
synchronous call.

Arguments mapping described in
[CreateDistributionConfigurationRequestRequestTypeDef](./type_defs.md#createdistributionconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `distributions`:
  `Sequence`\[[DistributionTypeDef](./type_defs.md#distributiontypedef)\]
  *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateDistributionConfigurationResponseTypeDef](./type_defs.md#createdistributionconfigurationresponsetypedef).

<a id="create_image"></a>

### create_image

Creates a new image.

Type annotations for `aiobotocore.create_client("imagebuilder").create_image`
method.

Boto3 documentation:
[imagebuilder.Client.create_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image)

Asynchronous method. Use `await create_image(...)` for a synchronous call.

Arguments mapping described in
[CreateImageRequestRequestTypeDef](./type_defs.md#createimagerequestrequesttypedef).

Keyword-only arguments:

- `infrastructureConfigurationArn`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `imageRecipeArn`: `str`
- `containerRecipeArn`: `str`
- `distributionConfigurationArn`: `str`
- `imageTestsConfiguration`:
  [ImageTestsConfigurationTypeDef](./type_defs.md#imagetestsconfigurationtypedef)
- `enhancedImageMetadataEnabled`: `bool`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateImageResponseTypeDef](./type_defs.md#createimageresponsetypedef).

<a id="create_image_pipeline"></a>

### create_image_pipeline

Creates a new image pipeline.

Type annotations for
`aiobotocore.create_client("imagebuilder").create_image_pipeline` method.

Boto3 documentation:
[imagebuilder.Client.create_image_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image_pipeline)

Asynchronous method. Use `await create_image_pipeline(...)` for a synchronous
call.

Arguments mapping described in
[CreateImagePipelineRequestRequestTypeDef](./type_defs.md#createimagepipelinerequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `infrastructureConfigurationArn`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `imageRecipeArn`: `str`
- `containerRecipeArn`: `str`
- `distributionConfigurationArn`: `str`
- `imageTestsConfiguration`:
  [ImageTestsConfigurationTypeDef](./type_defs.md#imagetestsconfigurationtypedef)
- `enhancedImageMetadataEnabled`: `bool`
- `schedule`: [ScheduleTypeDef](./type_defs.md#scheduletypedef)
- `status`: [PipelineStatusType](./literals.md#pipelinestatustype)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateImagePipelineResponseTypeDef](./type_defs.md#createimagepipelineresponsetypedef).

<a id="create_image_recipe"></a>

### create_image_recipe

Creates a new image recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").create_image_recipe` method.

Boto3 documentation:
[imagebuilder.Client.create_image_recipe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image_recipe)

Asynchronous method. Use `await create_image_recipe(...)` for a synchronous
call.

Arguments mapping described in
[CreateImageRecipeRequestRequestTypeDef](./type_defs.md#createimagereciperequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `semanticVersion`: `str` *(required)*
- `components`:
  `Sequence`\[[ComponentConfigurationTypeDef](./type_defs.md#componentconfigurationtypedef)\]
  *(required)*
- `parentImage`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `blockDeviceMappings`:
  `Sequence`\[[InstanceBlockDeviceMappingTypeDef](./type_defs.md#instanceblockdevicemappingtypedef)\]
- `tags`: `Mapping`\[`str`, `str`\]
- `workingDirectory`: `str`
- `additionalInstanceConfiguration`:
  [AdditionalInstanceConfigurationTypeDef](./type_defs.md#additionalinstanceconfigurationtypedef)

Returns a `Coroutine` for
[CreateImageRecipeResponseTypeDef](./type_defs.md#createimagereciperesponsetypedef).

<a id="create_infrastructure_configuration"></a>

### create_infrastructure_configuration

Creates a new infrastructure configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").create_infrastructure_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.create_infrastructure_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_infrastructure_configuration)

Asynchronous method. Use `await create_infrastructure_configuration(...)` for a
synchronous call.

Arguments mapping described in
[CreateInfrastructureConfigurationRequestRequestTypeDef](./type_defs.md#createinfrastructureconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `instanceProfileName`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `instanceTypes`: `Sequence`\[`str`\]
- `securityGroupIds`: `Sequence`\[`str`\]
- `subnetId`: `str`
- `logging`: [LoggingTypeDef](./type_defs.md#loggingtypedef)
- `keyPair`: `str`
- `terminateInstanceOnFailure`: `bool`
- `snsTopicArn`: `str`
- `resourceTags`: `Mapping`\[`str`, `str`\]
- `instanceMetadataOptions`:
  [InstanceMetadataOptionsTypeDef](./type_defs.md#instancemetadataoptionstypedef)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateInfrastructureConfigurationResponseTypeDef](./type_defs.md#createinfrastructureconfigurationresponsetypedef).

<a id="delete_component"></a>

### delete_component

Deletes a component build version.

Type annotations for
`aiobotocore.create_client("imagebuilder").delete_component` method.

Boto3 documentation:
[imagebuilder.Client.delete_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_component)

Asynchronous method. Use `await delete_component(...)` for a synchronous call.

Arguments mapping described in
[DeleteComponentRequestRequestTypeDef](./type_defs.md#deletecomponentrequestrequesttypedef).

Keyword-only arguments:

- `componentBuildVersionArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteComponentResponseTypeDef](./type_defs.md#deletecomponentresponsetypedef).

<a id="delete_container_recipe"></a>

### delete_container_recipe

Deletes a container recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").delete_container_recipe` method.

Boto3 documentation:
[imagebuilder.Client.delete_container_recipe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_container_recipe)

Asynchronous method. Use `await delete_container_recipe(...)` for a synchronous
call.

Arguments mapping described in
[DeleteContainerRecipeRequestRequestTypeDef](./type_defs.md#deletecontainerreciperequestrequesttypedef).

Keyword-only arguments:

- `containerRecipeArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteContainerRecipeResponseTypeDef](./type_defs.md#deletecontainerreciperesponsetypedef).

<a id="delete_distribution_configuration"></a>

### delete_distribution_configuration

Deletes a distribution configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").delete_distribution_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.delete_distribution_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_distribution_configuration)

Asynchronous method. Use `await delete_distribution_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDistributionConfigurationRequestRequestTypeDef](./type_defs.md#deletedistributionconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `distributionConfigurationArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteDistributionConfigurationResponseTypeDef](./type_defs.md#deletedistributionconfigurationresponsetypedef).

<a id="delete_image"></a>

### delete_image

Deletes an Image Builder image resource.

Type annotations for `aiobotocore.create_client("imagebuilder").delete_image`
method.

Boto3 documentation:
[imagebuilder.Client.delete_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image)

Asynchronous method. Use `await delete_image(...)` for a synchronous call.

Arguments mapping described in
[DeleteImageRequestRequestTypeDef](./type_defs.md#deleteimagerequestrequesttypedef).

Keyword-only arguments:

- `imageBuildVersionArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteImageResponseTypeDef](./type_defs.md#deleteimageresponsetypedef).

<a id="delete_image_pipeline"></a>

### delete_image_pipeline

Deletes an image pipeline.

Type annotations for
`aiobotocore.create_client("imagebuilder").delete_image_pipeline` method.

Boto3 documentation:
[imagebuilder.Client.delete_image_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image_pipeline)

Asynchronous method. Use `await delete_image_pipeline(...)` for a synchronous
call.

Arguments mapping described in
[DeleteImagePipelineRequestRequestTypeDef](./type_defs.md#deleteimagepipelinerequestrequesttypedef).

Keyword-only arguments:

- `imagePipelineArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteImagePipelineResponseTypeDef](./type_defs.md#deleteimagepipelineresponsetypedef).

<a id="delete_image_recipe"></a>

### delete_image_recipe

Deletes an image recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").delete_image_recipe` method.

Boto3 documentation:
[imagebuilder.Client.delete_image_recipe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image_recipe)

Asynchronous method. Use `await delete_image_recipe(...)` for a synchronous
call.

Arguments mapping described in
[DeleteImageRecipeRequestRequestTypeDef](./type_defs.md#deleteimagereciperequestrequesttypedef).

Keyword-only arguments:

- `imageRecipeArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteImageRecipeResponseTypeDef](./type_defs.md#deleteimagereciperesponsetypedef).

<a id="delete_infrastructure_configuration"></a>

### delete_infrastructure_configuration

Deletes an infrastructure configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").delete_infrastructure_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.delete_infrastructure_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_infrastructure_configuration)

Asynchronous method. Use `await delete_infrastructure_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteInfrastructureConfigurationRequestRequestTypeDef](./type_defs.md#deleteinfrastructureconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `infrastructureConfigurationArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteInfrastructureConfigurationResponseTypeDef](./type_defs.md#deleteinfrastructureconfigurationresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("imagebuilder").generate_presigned_url` method.

Boto3 documentation:
[imagebuilder.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_component"></a>

### get_component

Gets a component object.

Type annotations for `aiobotocore.create_client("imagebuilder").get_component`
method.

Boto3 documentation:
[imagebuilder.Client.get_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_component)

Asynchronous method. Use `await get_component(...)` for a synchronous call.

Arguments mapping described in
[GetComponentRequestRequestTypeDef](./type_defs.md#getcomponentrequestrequesttypedef).

Keyword-only arguments:

- `componentBuildVersionArn`: `str` *(required)*

Returns a `Coroutine` for
[GetComponentResponseTypeDef](./type_defs.md#getcomponentresponsetypedef).

<a id="get_component_policy"></a>

### get_component_policy

Gets a component policy.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_component_policy` method.

Boto3 documentation:
[imagebuilder.Client.get_component_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_component_policy)

Asynchronous method. Use `await get_component_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetComponentPolicyRequestRequestTypeDef](./type_defs.md#getcomponentpolicyrequestrequesttypedef).

Keyword-only arguments:

- `componentArn`: `str` *(required)*

Returns a `Coroutine` for
[GetComponentPolicyResponseTypeDef](./type_defs.md#getcomponentpolicyresponsetypedef).

<a id="get_container_recipe"></a>

### get_container_recipe

Retrieves a container recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_container_recipe` method.

Boto3 documentation:
[imagebuilder.Client.get_container_recipe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_container_recipe)

Asynchronous method. Use `await get_container_recipe(...)` for a synchronous
call.

Arguments mapping described in
[GetContainerRecipeRequestRequestTypeDef](./type_defs.md#getcontainerreciperequestrequesttypedef).

Keyword-only arguments:

- `containerRecipeArn`: `str` *(required)*

Returns a `Coroutine` for
[GetContainerRecipeResponseTypeDef](./type_defs.md#getcontainerreciperesponsetypedef).

<a id="get_container_recipe_policy"></a>

### get_container_recipe_policy

Retrieves the policy for a container recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_container_recipe_policy` method.

Boto3 documentation:
[imagebuilder.Client.get_container_recipe_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_container_recipe_policy)

Asynchronous method. Use `await get_container_recipe_policy(...)` for a
synchronous call.

Arguments mapping described in
[GetContainerRecipePolicyRequestRequestTypeDef](./type_defs.md#getcontainerrecipepolicyrequestrequesttypedef).

Keyword-only arguments:

- `containerRecipeArn`: `str` *(required)*

Returns a `Coroutine` for
[GetContainerRecipePolicyResponseTypeDef](./type_defs.md#getcontainerrecipepolicyresponsetypedef).

<a id="get_distribution_configuration"></a>

### get_distribution_configuration

Gets a distribution configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_distribution_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.get_distribution_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_distribution_configuration)

Asynchronous method. Use `await get_distribution_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetDistributionConfigurationRequestRequestTypeDef](./type_defs.md#getdistributionconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `distributionConfigurationArn`: `str` *(required)*

Returns a `Coroutine` for
[GetDistributionConfigurationResponseTypeDef](./type_defs.md#getdistributionconfigurationresponsetypedef).

<a id="get_image"></a>

### get_image

Gets an image.

Type annotations for `aiobotocore.create_client("imagebuilder").get_image`
method.

Boto3 documentation:
[imagebuilder.Client.get_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image)

Asynchronous method. Use `await get_image(...)` for a synchronous call.

Arguments mapping described in
[GetImageRequestRequestTypeDef](./type_defs.md#getimagerequestrequesttypedef).

Keyword-only arguments:

- `imageBuildVersionArn`: `str` *(required)*

Returns a `Coroutine` for
[GetImageResponseTypeDef](./type_defs.md#getimageresponsetypedef).

<a id="get_image_pipeline"></a>

### get_image_pipeline

Gets an image pipeline.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_image_pipeline` method.

Boto3 documentation:
[imagebuilder.Client.get_image_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_pipeline)

Asynchronous method. Use `await get_image_pipeline(...)` for a synchronous
call.

Arguments mapping described in
[GetImagePipelineRequestRequestTypeDef](./type_defs.md#getimagepipelinerequestrequesttypedef).

Keyword-only arguments:

- `imagePipelineArn`: `str` *(required)*

Returns a `Coroutine` for
[GetImagePipelineResponseTypeDef](./type_defs.md#getimagepipelineresponsetypedef).

<a id="get_image_policy"></a>

### get_image_policy

Gets an image policy.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_image_policy` method.

Boto3 documentation:
[imagebuilder.Client.get_image_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_policy)

Asynchronous method. Use `await get_image_policy(...)` for a synchronous call.

Arguments mapping described in
[GetImagePolicyRequestRequestTypeDef](./type_defs.md#getimagepolicyrequestrequesttypedef).

Keyword-only arguments:

- `imageArn`: `str` *(required)*

Returns a `Coroutine` for
[GetImagePolicyResponseTypeDef](./type_defs.md#getimagepolicyresponsetypedef).

<a id="get_image_recipe"></a>

### get_image_recipe

Gets an image recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_image_recipe` method.

Boto3 documentation:
[imagebuilder.Client.get_image_recipe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_recipe)

Asynchronous method. Use `await get_image_recipe(...)` for a synchronous call.

Arguments mapping described in
[GetImageRecipeRequestRequestTypeDef](./type_defs.md#getimagereciperequestrequesttypedef).

Keyword-only arguments:

- `imageRecipeArn`: `str` *(required)*

Returns a `Coroutine` for
[GetImageRecipeResponseTypeDef](./type_defs.md#getimagereciperesponsetypedef).

<a id="get_image_recipe_policy"></a>

### get_image_recipe_policy

Gets an image recipe policy.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_image_recipe_policy` method.

Boto3 documentation:
[imagebuilder.Client.get_image_recipe_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_recipe_policy)

Asynchronous method. Use `await get_image_recipe_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetImageRecipePolicyRequestRequestTypeDef](./type_defs.md#getimagerecipepolicyrequestrequesttypedef).

Keyword-only arguments:

- `imageRecipeArn`: `str` *(required)*

Returns a `Coroutine` for
[GetImageRecipePolicyResponseTypeDef](./type_defs.md#getimagerecipepolicyresponsetypedef).

<a id="get_infrastructure_configuration"></a>

### get_infrastructure_configuration

Gets an infrastructure configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").get_infrastructure_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.get_infrastructure_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_infrastructure_configuration)

Asynchronous method. Use `await get_infrastructure_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetInfrastructureConfigurationRequestRequestTypeDef](./type_defs.md#getinfrastructureconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `infrastructureConfigurationArn`: `str` *(required)*

Returns a `Coroutine` for
[GetInfrastructureConfigurationResponseTypeDef](./type_defs.md#getinfrastructureconfigurationresponsetypedef).

<a id="import_component"></a>

### import_component

Imports a component and transforms its data into a component document.

Type annotations for
`aiobotocore.create_client("imagebuilder").import_component` method.

Boto3 documentation:
[imagebuilder.Client.import_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.import_component)

Asynchronous method. Use `await import_component(...)` for a synchronous call.

Arguments mapping described in
[ImportComponentRequestRequestTypeDef](./type_defs.md#importcomponentrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `semanticVersion`: `str` *(required)*
- `type`: [ComponentTypeType](./literals.md#componenttypetype) *(required)*
- `format`: `Literal['SHELL']` (see
  [ComponentFormatType](./literals.md#componentformattype)) *(required)*
- `platform`: [PlatformType](./literals.md#platformtype) *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `changeDescription`: `str`
- `data`: `str`
- `uri`: `str`
- `kmsKeyId`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[ImportComponentResponseTypeDef](./type_defs.md#importcomponentresponsetypedef).

<a id="list_component_build_versions"></a>

### list_component_build_versions

Returns the list of component build versions for the specified semantic
version.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_component_build_versions`
method.

Boto3 documentation:
[imagebuilder.Client.list_component_build_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_component_build_versions)

Asynchronous method. Use `await list_component_build_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListComponentBuildVersionsRequestRequestTypeDef](./type_defs.md#listcomponentbuildversionsrequestrequesttypedef).

Keyword-only arguments:

- `componentVersionArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListComponentBuildVersionsResponseTypeDef](./type_defs.md#listcomponentbuildversionsresponsetypedef).

<a id="list_components"></a>

### list_components

Returns the list of component build versions for the specified semantic
version.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_components` method.

Boto3 documentation:
[imagebuilder.Client.list_components](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_components)

Asynchronous method. Use `await list_components(...)` for a synchronous call.

Arguments mapping described in
[ListComponentsRequestRequestTypeDef](./type_defs.md#listcomponentsrequestrequesttypedef).

Keyword-only arguments:

- `owner`: [OwnershipType](./literals.md#ownershiptype)
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `byName`: `bool`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListComponentsResponseTypeDef](./type_defs.md#listcomponentsresponsetypedef).

<a id="list_container_recipes"></a>

### list_container_recipes

Returns a list of container recipes.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_container_recipes` method.

Boto3 documentation:
[imagebuilder.Client.list_container_recipes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_container_recipes)

Asynchronous method. Use `await list_container_recipes(...)` for a synchronous
call.

Arguments mapping described in
[ListContainerRecipesRequestRequestTypeDef](./type_defs.md#listcontainerrecipesrequestrequesttypedef).

Keyword-only arguments:

- `owner`: [OwnershipType](./literals.md#ownershiptype)
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListContainerRecipesResponseTypeDef](./type_defs.md#listcontainerrecipesresponsetypedef).

<a id="list_distribution_configurations"></a>

### list_distribution_configurations

Returns a list of distribution configurations.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_distribution_configurations`
method.

Boto3 documentation:
[imagebuilder.Client.list_distribution_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_distribution_configurations)

Asynchronous method. Use `await list_distribution_configurations(...)` for a
synchronous call.

Arguments mapping described in
[ListDistributionConfigurationsRequestRequestTypeDef](./type_defs.md#listdistributionconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListDistributionConfigurationsResponseTypeDef](./type_defs.md#listdistributionconfigurationsresponsetypedef).

<a id="list_image_build_versions"></a>

### list_image_build_versions

Returns a list of image build versions.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_image_build_versions` method.

Boto3 documentation:
[imagebuilder.Client.list_image_build_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_build_versions)

Asynchronous method. Use `await list_image_build_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListImageBuildVersionsRequestRequestTypeDef](./type_defs.md#listimagebuildversionsrequestrequesttypedef).

Keyword-only arguments:

- `imageVersionArn`: `str` *(required)*
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListImageBuildVersionsResponseTypeDef](./type_defs.md#listimagebuildversionsresponsetypedef).

<a id="list_image_packages"></a>

### list_image_packages

List the Packages that are associated with an Image Build Version, as
determined by Amazon Web Services Systems Manager Inventory at build time.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_image_packages` method.

Boto3 documentation:
[imagebuilder.Client.list_image_packages](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_packages)

Asynchronous method. Use `await list_image_packages(...)` for a synchronous
call.

Arguments mapping described in
[ListImagePackagesRequestRequestTypeDef](./type_defs.md#listimagepackagesrequestrequesttypedef).

Keyword-only arguments:

- `imageBuildVersionArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListImagePackagesResponseTypeDef](./type_defs.md#listimagepackagesresponsetypedef).

<a id="list_image_pipeline_images"></a>

### list_image_pipeline_images

Returns a list of images created by the specified pipeline.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_image_pipeline_images` method.

Boto3 documentation:
[imagebuilder.Client.list_image_pipeline_images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_pipeline_images)

Asynchronous method. Use `await list_image_pipeline_images(...)` for a
synchronous call.

Arguments mapping described in
[ListImagePipelineImagesRequestRequestTypeDef](./type_defs.md#listimagepipelineimagesrequestrequesttypedef).

Keyword-only arguments:

- `imagePipelineArn`: `str` *(required)*
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListImagePipelineImagesResponseTypeDef](./type_defs.md#listimagepipelineimagesresponsetypedef).

<a id="list_image_pipelines"></a>

### list_image_pipelines

Returns a list of image pipelines.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_image_pipelines` method.

Boto3 documentation:
[imagebuilder.Client.list_image_pipelines](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_pipelines)

Asynchronous method. Use `await list_image_pipelines(...)` for a synchronous
call.

Arguments mapping described in
[ListImagePipelinesRequestRequestTypeDef](./type_defs.md#listimagepipelinesrequestrequesttypedef).

Keyword-only arguments:

- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListImagePipelinesResponseTypeDef](./type_defs.md#listimagepipelinesresponsetypedef).

<a id="list_image_recipes"></a>

### list_image_recipes

Returns a list of image recipes.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_image_recipes` method.

Boto3 documentation:
[imagebuilder.Client.list_image_recipes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_recipes)

Asynchronous method. Use `await list_image_recipes(...)` for a synchronous
call.

Arguments mapping described in
[ListImageRecipesRequestRequestTypeDef](./type_defs.md#listimagerecipesrequestrequesttypedef).

Keyword-only arguments:

- `owner`: [OwnershipType](./literals.md#ownershiptype)
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListImageRecipesResponseTypeDef](./type_defs.md#listimagerecipesresponsetypedef).

<a id="list_images"></a>

### list_images

Returns the list of images that you have access to.

Type annotations for `aiobotocore.create_client("imagebuilder").list_images`
method.

Boto3 documentation:
[imagebuilder.Client.list_images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_images)

Asynchronous method. Use `await list_images(...)` for a synchronous call.

Arguments mapping described in
[ListImagesRequestRequestTypeDef](./type_defs.md#listimagesrequestrequesttypedef).

Keyword-only arguments:

- `owner`: [OwnershipType](./literals.md#ownershiptype)
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `byName`: `bool`
- `maxResults`: `int`
- `nextToken`: `str`
- `includeDeprecated`: `bool`

Returns a `Coroutine` for
[ListImagesResponseTypeDef](./type_defs.md#listimagesresponsetypedef).

<a id="list_infrastructure_configurations"></a>

### list_infrastructure_configurations

Returns a list of infrastructure configurations.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_infrastructure_configurations`
method.

Boto3 documentation:
[imagebuilder.Client.list_infrastructure_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_infrastructure_configurations)

Asynchronous method. Use `await list_infrastructure_configurations(...)` for a
synchronous call.

Arguments mapping described in
[ListInfrastructureConfigurationsRequestRequestTypeDef](./type_defs.md#listinfrastructureconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListInfrastructureConfigurationsResponseTypeDef](./type_defs.md#listinfrastructureconfigurationsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Returns the list of tags for the specified resource.

Type annotations for
`aiobotocore.create_client("imagebuilder").list_tags_for_resource` method.

Boto3 documentation:
[imagebuilder.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_component_policy"></a>

### put_component_policy

Applies a policy to a component.

Type annotations for
`aiobotocore.create_client("imagebuilder").put_component_policy` method.

Boto3 documentation:
[imagebuilder.Client.put_component_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_component_policy)

Asynchronous method. Use `await put_component_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutComponentPolicyRequestRequestTypeDef](./type_defs.md#putcomponentpolicyrequestrequesttypedef).

Keyword-only arguments:

- `componentArn`: `str` *(required)*
- `policy`: `str` *(required)*

Returns a `Coroutine` for
[PutComponentPolicyResponseTypeDef](./type_defs.md#putcomponentpolicyresponsetypedef).

<a id="put_container_recipe_policy"></a>

### put_container_recipe_policy

Applies a policy to a container image.

Type annotations for
`aiobotocore.create_client("imagebuilder").put_container_recipe_policy` method.

Boto3 documentation:
[imagebuilder.Client.put_container_recipe_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_container_recipe_policy)

Asynchronous method. Use `await put_container_recipe_policy(...)` for a
synchronous call.

Arguments mapping described in
[PutContainerRecipePolicyRequestRequestTypeDef](./type_defs.md#putcontainerrecipepolicyrequestrequesttypedef).

Keyword-only arguments:

- `containerRecipeArn`: `str` *(required)*
- `policy`: `str` *(required)*

Returns a `Coroutine` for
[PutContainerRecipePolicyResponseTypeDef](./type_defs.md#putcontainerrecipepolicyresponsetypedef).

<a id="put_image_policy"></a>

### put_image_policy

Applies a policy to an image.

Type annotations for
`aiobotocore.create_client("imagebuilder").put_image_policy` method.

Boto3 documentation:
[imagebuilder.Client.put_image_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_image_policy)

Asynchronous method. Use `await put_image_policy(...)` for a synchronous call.

Arguments mapping described in
[PutImagePolicyRequestRequestTypeDef](./type_defs.md#putimagepolicyrequestrequesttypedef).

Keyword-only arguments:

- `imageArn`: `str` *(required)*
- `policy`: `str` *(required)*

Returns a `Coroutine` for
[PutImagePolicyResponseTypeDef](./type_defs.md#putimagepolicyresponsetypedef).

<a id="put_image_recipe_policy"></a>

### put_image_recipe_policy

Applies a policy to an image recipe.

Type annotations for
`aiobotocore.create_client("imagebuilder").put_image_recipe_policy` method.

Boto3 documentation:
[imagebuilder.Client.put_image_recipe_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_image_recipe_policy)

Asynchronous method. Use `await put_image_recipe_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutImageRecipePolicyRequestRequestTypeDef](./type_defs.md#putimagerecipepolicyrequestrequesttypedef).

Keyword-only arguments:

- `imageRecipeArn`: `str` *(required)*
- `policy`: `str` *(required)*

Returns a `Coroutine` for
[PutImageRecipePolicyResponseTypeDef](./type_defs.md#putimagerecipepolicyresponsetypedef).

<a id="start_image_pipeline_execution"></a>

### start_image_pipeline_execution

Manually triggers a pipeline to create an image.

Type annotations for
`aiobotocore.create_client("imagebuilder").start_image_pipeline_execution`
method.

Boto3 documentation:
[imagebuilder.Client.start_image_pipeline_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.start_image_pipeline_execution)

Asynchronous method. Use `await start_image_pipeline_execution(...)` for a
synchronous call.

Arguments mapping described in
[StartImagePipelineExecutionRequestRequestTypeDef](./type_defs.md#startimagepipelineexecutionrequestrequesttypedef).

Keyword-only arguments:

- `imagePipelineArn`: `str` *(required)*
- `clientToken`: `str` *(required)*

Returns a `Coroutine` for
[StartImagePipelineExecutionResponseTypeDef](./type_defs.md#startimagepipelineexecutionresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds a tag to a resource.

Type annotations for `aiobotocore.create_client("imagebuilder").tag_resource`
method.

Boto3 documentation:
[imagebuilder.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes a tag from a resource.

Type annotations for `aiobotocore.create_client("imagebuilder").untag_resource`
method.

Boto3 documentation:
[imagebuilder.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_distribution_configuration"></a>

### update_distribution_configuration

Updates a new distribution configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").update_distribution_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.update_distribution_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_distribution_configuration)

Asynchronous method. Use `await update_distribution_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDistributionConfigurationRequestRequestTypeDef](./type_defs.md#updatedistributionconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `distributionConfigurationArn`: `str` *(required)*
- `distributions`:
  `Sequence`\[[DistributionTypeDef](./type_defs.md#distributiontypedef)\]
  *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`

Returns a `Coroutine` for
[UpdateDistributionConfigurationResponseTypeDef](./type_defs.md#updatedistributionconfigurationresponsetypedef).

<a id="update_image_pipeline"></a>

### update_image_pipeline

Updates an image pipeline.

Type annotations for
`aiobotocore.create_client("imagebuilder").update_image_pipeline` method.

Boto3 documentation:
[imagebuilder.Client.update_image_pipeline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_image_pipeline)

Asynchronous method. Use `await update_image_pipeline(...)` for a synchronous
call.

Arguments mapping described in
[UpdateImagePipelineRequestRequestTypeDef](./type_defs.md#updateimagepipelinerequestrequesttypedef).

Keyword-only arguments:

- `imagePipelineArn`: `str` *(required)*
- `infrastructureConfigurationArn`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `imageRecipeArn`: `str`
- `containerRecipeArn`: `str`
- `distributionConfigurationArn`: `str`
- `imageTestsConfiguration`:
  [ImageTestsConfigurationTypeDef](./type_defs.md#imagetestsconfigurationtypedef)
- `enhancedImageMetadataEnabled`: `bool`
- `schedule`: [ScheduleTypeDef](./type_defs.md#scheduletypedef)
- `status`: [PipelineStatusType](./literals.md#pipelinestatustype)

Returns a `Coroutine` for
[UpdateImagePipelineResponseTypeDef](./type_defs.md#updateimagepipelineresponsetypedef).

<a id="update_infrastructure_configuration"></a>

### update_infrastructure_configuration

Updates a new infrastructure configuration.

Type annotations for
`aiobotocore.create_client("imagebuilder").update_infrastructure_configuration`
method.

Boto3 documentation:
[imagebuilder.Client.update_infrastructure_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_infrastructure_configuration)

Asynchronous method. Use `await update_infrastructure_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateInfrastructureConfigurationRequestRequestTypeDef](./type_defs.md#updateinfrastructureconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `infrastructureConfigurationArn`: `str` *(required)*
- `instanceProfileName`: `str` *(required)*
- `clientToken`: `str` *(required)*
- `description`: `str`
- `instanceTypes`: `Sequence`\[`str`\]
- `securityGroupIds`: `Sequence`\[`str`\]
- `subnetId`: `str`
- `logging`: [LoggingTypeDef](./type_defs.md#loggingtypedef)
- `keyPair`: `str`
- `terminateInstanceOnFailure`: `bool`
- `snsTopicArn`: `str`
- `resourceTags`: `Mapping`\[`str`, `str`\]
- `instanceMetadataOptions`:
  [InstanceMetadataOptionsTypeDef](./type_defs.md#instancemetadataoptionstypedef)

Returns a `Coroutine` for
[UpdateInfrastructureConfigurationResponseTypeDef](./type_defs.md#updateinfrastructureconfigurationresponsetypedef).
