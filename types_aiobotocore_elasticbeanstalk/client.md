<a id="elasticbeanstalkclient-for-aiobotocore-elasticbeanstalk-module"></a>

# ElasticBeanstalkClient for aiobotocore ElasticBeanstalk module

> [Index](..) > [ElasticBeanstalk](.) > ElasticBeanstalkClient

Auto-generated documentation for
[ElasticBeanstalk](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk)
type annotations stubs module
[types-aiobotocore-elasticbeanstalk](https://pypi.org/project/types-aiobotocore-elasticbeanstalk/).

- [ElasticBeanstalkClient for aiobotocore ElasticBeanstalk module](#elasticbeanstalkclient-for-aiobotocore-elasticbeanstalk-module)
  - [ElasticBeanstalkClient](#elasticbeanstalkclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [abort_environment_update](#abort_environment_update)
    - [apply_environment_managed_action](#apply_environment_managed_action)
    - [associate_environment_operations_role](#associate_environment_operations_role)
    - [can_paginate](#can_paginate)
    - [check_dns_availability](#check_dns_availability)
    - [compose_environments](#compose_environments)
    - [create_application](#create_application)
    - [create_application_version](#create_application_version)
    - [create_configuration_template](#create_configuration_template)
    - [create_environment](#create_environment)
    - [create_platform_version](#create_platform_version)
    - [create_storage_location](#create_storage_location)
    - [delete_application](#delete_application)
    - [delete_application_version](#delete_application_version)
    - [delete_configuration_template](#delete_configuration_template)
    - [delete_environment_configuration](#delete_environment_configuration)
    - [delete_platform_version](#delete_platform_version)
    - [describe_account_attributes](#describe_account_attributes)
    - [describe_application_versions](#describe_application_versions)
    - [describe_applications](#describe_applications)
    - [describe_configuration_options](#describe_configuration_options)
    - [describe_configuration_settings](#describe_configuration_settings)
    - [describe_environment_health](#describe_environment_health)
    - [describe_environment_managed_action_history](#describe_environment_managed_action_history)
    - [describe_environment_managed_actions](#describe_environment_managed_actions)
    - [describe_environment_resources](#describe_environment_resources)
    - [describe_environments](#describe_environments)
    - [describe_events](#describe_events)
    - [describe_instances_health](#describe_instances_health)
    - [describe_platform_version](#describe_platform_version)
    - [disassociate_environment_operations_role](#disassociate_environment_operations_role)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_available_solution_stacks](#list_available_solution_stacks)
    - [list_platform_branches](#list_platform_branches)
    - [list_platform_versions](#list_platform_versions)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [rebuild_environment](#rebuild_environment)
    - [request_environment_info](#request_environment_info)
    - [restart_app_server](#restart_app_server)
    - [retrieve_environment_info](#retrieve_environment_info)
    - [swap_environment_cnames](#swap_environment_cnames)
    - [terminate_environment](#terminate_environment)
    - [update_application](#update_application)
    - [update_application_resource_lifecycle](#update_application_resource_lifecycle)
    - [update_application_version](#update_application_version)
    - [update_configuration_template](#update_configuration_template)
    - [update_environment](#update_environment)
    - [update_tags_for_resource](#update_tags_for_resource)
    - [validate_configuration_settings](#validate_configuration_settings)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="elasticbeanstalkclient"></a>

## ElasticBeanstalkClient

Type annotations for `aiobotocore.create_client("elasticbeanstalk")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_elasticbeanstalk.client import ElasticBeanstalkClient

def get_elasticbeanstalk_client() -> ElasticBeanstalkClient:
    return Session().client("elasticbeanstalk")
```

Boto3 documentation:
[ElasticBeanstalk.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_elasticbeanstalk.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.CodeBuildNotInServiceRegionException`
- `Exceptions.ElasticBeanstalkServiceException`
- `Exceptions.InsufficientPrivilegesException`
- `Exceptions.InvalidRequestException`
- `Exceptions.ManagedActionInvalidStateException`
- `Exceptions.OperationInProgressException`
- `Exceptions.PlatformVersionStillReferencedException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ResourceTypeNotSupportedException`
- `Exceptions.S3LocationNotInServiceRegionException`
- `Exceptions.S3SubscriptionRequiredException`
- `Exceptions.SourceBundleDeletionException`
- `Exceptions.TooManyApplicationVersionsException`
- `Exceptions.TooManyApplicationsException`
- `Exceptions.TooManyBucketsException`
- `Exceptions.TooManyConfigurationTemplatesException`
- `Exceptions.TooManyEnvironmentsException`
- `Exceptions.TooManyPlatformsException`
- `Exceptions.TooManyTagsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ElasticBeanstalkClient exceptions.

Type annotations for `aiobotocore.create_client("elasticbeanstalk").exceptions`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="abort_environment_update"></a>

### abort_environment_update

Cancels in-progress environment configuration update or application version
deployment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").abort_environment_update`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.abort_environment_update](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.abort_environment_update)

Asynchronous method. Use `await abort_environment_update(...)` for a
synchronous call.

Arguments mapping described in
[AbortEnvironmentUpdateMessageRequestTypeDef](./type_defs.md#abortenvironmentupdatemessagerequesttypedef).

Keyword-only arguments:

- `EnvironmentId`: `str`
- `EnvironmentName`: `str`

<a id="apply_environment_managed_action"></a>

### apply_environment_managed_action

Applies a scheduled managed action immediately.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").apply_environment_managed_action`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.apply_environment_managed_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.apply_environment_managed_action)

Asynchronous method. Use `await apply_environment_managed_action(...)` for a
synchronous call.

Arguments mapping described in
[ApplyEnvironmentManagedActionRequestRequestTypeDef](./type_defs.md#applyenvironmentmanagedactionrequestrequesttypedef).

Keyword-only arguments:

- `ActionId`: `str` *(required)*
- `EnvironmentName`: `str`
- `EnvironmentId`: `str`

Returns a `Coroutine` for
[ApplyEnvironmentManagedActionResultTypeDef](./type_defs.md#applyenvironmentmanagedactionresulttypedef).

<a id="associate_environment_operations_role"></a>

### associate_environment_operations_role

Add or change the operations role used by an environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").associate_environment_operations_role`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.associate_environment_operations_role](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.associate_environment_operations_role)

Asynchronous method. Use `await associate_environment_operations_role(...)` for
a synchronous call.

Arguments mapping described in
[AssociateEnvironmentOperationsRoleMessageRequestTypeDef](./type_defs.md#associateenvironmentoperationsrolemessagerequesttypedef).

Keyword-only arguments:

- `EnvironmentName`: `str` *(required)*
- `OperationsRole`: `str` *(required)*

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").can_paginate` method.

Boto3 documentation:
[ElasticBeanstalk.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="check_dns_availability"></a>

### check_dns_availability

Checks if the specified CNAME is available.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").check_dns_availability` method.

Boto3 documentation:
[ElasticBeanstalk.Client.check_dns_availability](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.check_dns_availability)

Asynchronous method. Use `await check_dns_availability(...)` for a synchronous
call.

Arguments mapping described in
[CheckDNSAvailabilityMessageRequestTypeDef](./type_defs.md#checkdnsavailabilitymessagerequesttypedef).

Keyword-only arguments:

- `CNAMEPrefix`: `str` *(required)*

Returns a `Coroutine` for
[CheckDNSAvailabilityResultMessageTypeDef](./type_defs.md#checkdnsavailabilityresultmessagetypedef).

<a id="compose_environments"></a>

### compose_environments

Create or update a group of environments that each run a separate component of
a single application.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").compose_environments` method.

Boto3 documentation:
[ElasticBeanstalk.Client.compose_environments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.compose_environments)

Asynchronous method. Use `await compose_environments(...)` for a synchronous
call.

Arguments mapping described in
[ComposeEnvironmentsMessageRequestTypeDef](./type_defs.md#composeenvironmentsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str`
- `GroupName`: `str`
- `VersionLabels`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[EnvironmentDescriptionsMessageTypeDef](./type_defs.md#environmentdescriptionsmessagetypedef).

<a id="create_application"></a>

### create_application

Creates an application that has one configuration template named `default` and
no application versions.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").create_application` method.

Boto3 documentation:
[ElasticBeanstalk.Client.create_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.create_application)

Asynchronous method. Use `await create_application(...)` for a synchronous
call.

Arguments mapping described in
[CreateApplicationMessageRequestTypeDef](./type_defs.md#createapplicationmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `Description`: `str`
- `ResourceLifecycleConfig`:
  [ApplicationResourceLifecycleConfigTypeDef](./type_defs.md#applicationresourcelifecycleconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[ApplicationDescriptionMessageTypeDef](./type_defs.md#applicationdescriptionmessagetypedef).

<a id="create_application_version"></a>

### create_application_version

Creates an application version for the specified application.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").create_application_version`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.create_application_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.create_application_version)

Asynchronous method. Use `await create_application_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateApplicationVersionMessageRequestTypeDef](./type_defs.md#createapplicationversionmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `VersionLabel`: `str` *(required)*
- `Description`: `str`
- `SourceBuildInformation`:
  [SourceBuildInformationTypeDef](./type_defs.md#sourcebuildinformationtypedef)
- `SourceBundle`: [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- `BuildConfiguration`:
  [BuildConfigurationTypeDef](./type_defs.md#buildconfigurationtypedef)
- `AutoCreateApplication`: `bool`
- `Process`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[ApplicationVersionDescriptionMessageTypeDef](./type_defs.md#applicationversiondescriptionmessagetypedef).

<a id="create_configuration_template"></a>

### create_configuration_template

.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").create_configuration_template`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.create_configuration_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.create_configuration_template)

Asynchronous method. Use `await create_configuration_template(...)` for a
synchronous call.

Arguments mapping described in
[CreateConfigurationTemplateMessageRequestTypeDef](./type_defs.md#createconfigurationtemplatemessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `TemplateName`: `str` *(required)*
- `SolutionStackName`: `str`
- `PlatformArn`: `str`
- `SourceConfiguration`:
  [SourceConfigurationTypeDef](./type_defs.md#sourceconfigurationtypedef)
- `EnvironmentId`: `str`
- `Description`: `str`
- `OptionSettings`:
  `Sequence`\[[ConfigurationOptionSettingTypeDef](./type_defs.md#configurationoptionsettingtypedef)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[ConfigurationSettingsDescriptionResponseMetadataTypeDef](./type_defs.md#configurationsettingsdescriptionresponsemetadatatypedef).

<a id="create_environment"></a>

### create_environment

Launches an AWS Elastic Beanstalk environment for the specified application
using the specified configuration.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").create_environment` method.

Boto3 documentation:
[ElasticBeanstalk.Client.create_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.create_environment)

Asynchronous method. Use `await create_environment(...)` for a synchronous
call.

Arguments mapping described in
[CreateEnvironmentMessageRequestTypeDef](./type_defs.md#createenvironmentmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `EnvironmentName`: `str`
- `GroupName`: `str`
- `Description`: `str`
- `CNAMEPrefix`: `str`
- `Tier`: [EnvironmentTierTypeDef](./type_defs.md#environmenttiertypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `VersionLabel`: `str`
- `TemplateName`: `str`
- `SolutionStackName`: `str`
- `PlatformArn`: `str`
- `OptionSettings`:
  `Sequence`\[[ConfigurationOptionSettingTypeDef](./type_defs.md#configurationoptionsettingtypedef)\]
- `OptionsToRemove`:
  `Sequence`\[[OptionSpecificationTypeDef](./type_defs.md#optionspecificationtypedef)\]
- `OperationsRole`: `str`

Returns a `Coroutine` for
[EnvironmentDescriptionResponseMetadataTypeDef](./type_defs.md#environmentdescriptionresponsemetadatatypedef).

<a id="create_platform_version"></a>

### create_platform_version

Create a new version of your custom platform.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").create_platform_version` method.

Boto3 documentation:
[ElasticBeanstalk.Client.create_platform_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.create_platform_version)

Asynchronous method. Use `await create_platform_version(...)` for a synchronous
call.

Arguments mapping described in
[CreatePlatformVersionRequestRequestTypeDef](./type_defs.md#createplatformversionrequestrequesttypedef).

Keyword-only arguments:

- `PlatformName`: `str` *(required)*
- `PlatformVersion`: `str` *(required)*
- `PlatformDefinitionBundle`:
  [S3LocationTypeDef](./type_defs.md#s3locationtypedef) *(required)*
- `EnvironmentName`: `str`
- `OptionSettings`:
  `Sequence`\[[ConfigurationOptionSettingTypeDef](./type_defs.md#configurationoptionsettingtypedef)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreatePlatformVersionResultTypeDef](./type_defs.md#createplatformversionresulttypedef).

<a id="create_storage_location"></a>

### create_storage_location

Creates a bucket in Amazon S3 to store application versions, logs, and other
files used by Elastic Beanstalk environments.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").create_storage_location` method.

Boto3 documentation:
[ElasticBeanstalk.Client.create_storage_location](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.create_storage_location)

Asynchronous method. Use `await create_storage_location(...)` for a synchronous
call.

Returns a `Coroutine` for
[CreateStorageLocationResultMessageTypeDef](./type_defs.md#createstoragelocationresultmessagetypedef).

<a id="delete_application"></a>

### delete_application

Deletes the specified application along with all associated versions and
configurations.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").delete_application` method.

Boto3 documentation:
[ElasticBeanstalk.Client.delete_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.delete_application)

Asynchronous method. Use `await delete_application(...)` for a synchronous
call.

Arguments mapping described in
[DeleteApplicationMessageRequestTypeDef](./type_defs.md#deleteapplicationmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `TerminateEnvByForce`: `bool`

<a id="delete_application_version"></a>

### delete_application_version

Deletes the specified version from the specified application.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").delete_application_version`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.delete_application_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.delete_application_version)

Asynchronous method. Use `await delete_application_version(...)` for a
synchronous call.

Arguments mapping described in
[DeleteApplicationVersionMessageRequestTypeDef](./type_defs.md#deleteapplicationversionmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `VersionLabel`: `str` *(required)*
- `DeleteSourceBundle`: `bool`

<a id="delete_configuration_template"></a>

### delete_configuration_template

Deletes the specified configuration template.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").delete_configuration_template`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.delete_configuration_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.delete_configuration_template)

Asynchronous method. Use `await delete_configuration_template(...)` for a
synchronous call.

Arguments mapping described in
[DeleteConfigurationTemplateMessageRequestTypeDef](./type_defs.md#deleteconfigurationtemplatemessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `TemplateName`: `str` *(required)*

<a id="delete_environment_configuration"></a>

### delete_environment_configuration

Deletes the draft configuration associated with the running environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").delete_environment_configuration`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.delete_environment_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.delete_environment_configuration)

Asynchronous method. Use `await delete_environment_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteEnvironmentConfigurationMessageRequestTypeDef](./type_defs.md#deleteenvironmentconfigurationmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `EnvironmentName`: `str` *(required)*

<a id="delete_platform_version"></a>

### delete_platform_version

Deletes the specified version of a custom platform.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").delete_platform_version` method.

Boto3 documentation:
[ElasticBeanstalk.Client.delete_platform_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.delete_platform_version)

Asynchronous method. Use `await delete_platform_version(...)` for a synchronous
call.

Arguments mapping described in
[DeletePlatformVersionRequestRequestTypeDef](./type_defs.md#deleteplatformversionrequestrequesttypedef).

Keyword-only arguments:

- `PlatformArn`: `str`

Returns a `Coroutine` for
[DeletePlatformVersionResultTypeDef](./type_defs.md#deleteplatformversionresulttypedef).

<a id="describe_account_attributes"></a>

### describe_account_attributes

Returns attributes related to AWS Elastic Beanstalk that are associated with
the calling AWS account.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_account_attributes`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_account_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_account_attributes)

Asynchronous method. Use `await describe_account_attributes(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeAccountAttributesResultTypeDef](./type_defs.md#describeaccountattributesresulttypedef).

<a id="describe_application_versions"></a>

### describe_application_versions

Retrieve a list of application versions.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_application_versions`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_application_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_application_versions)

Asynchronous method. Use `await describe_application_versions(...)` for a
synchronous call.

Arguments mapping described in
[DescribeApplicationVersionsMessageRequestTypeDef](./type_defs.md#describeapplicationversionsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str`
- `VersionLabels`: `Sequence`\[`str`\]
- `MaxRecords`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ApplicationVersionDescriptionsMessageTypeDef](./type_defs.md#applicationversiondescriptionsmessagetypedef).

<a id="describe_applications"></a>

### describe_applications

Returns the descriptions of existing applications.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_applications` method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_applications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_applications)

Asynchronous method. Use `await describe_applications(...)` for a synchronous
call.

Arguments mapping described in
[DescribeApplicationsMessageRequestTypeDef](./type_defs.md#describeapplicationsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationNames`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ApplicationDescriptionsMessageTypeDef](./type_defs.md#applicationdescriptionsmessagetypedef).

<a id="describe_configuration_options"></a>

### describe_configuration_options

Describes the configuration options that are used in a particular configuration
template or environment, or that a specified solution stack defines.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_configuration_options`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_configuration_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_configuration_options)

Asynchronous method. Use `await describe_configuration_options(...)` for a
synchronous call.

Arguments mapping described in
[DescribeConfigurationOptionsMessageRequestTypeDef](./type_defs.md#describeconfigurationoptionsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str`
- `TemplateName`: `str`
- `EnvironmentName`: `str`
- `SolutionStackName`: `str`
- `PlatformArn`: `str`
- `Options`:
  `Sequence`\[[OptionSpecificationTypeDef](./type_defs.md#optionspecificationtypedef)\]

Returns a `Coroutine` for
[ConfigurationOptionsDescriptionTypeDef](./type_defs.md#configurationoptionsdescriptiontypedef).

<a id="describe_configuration_settings"></a>

### describe_configuration_settings

Returns a description of the settings for the specified configuration set, that
is, either a configuration template or the configuration set associated with a
running environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_configuration_settings`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_configuration_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_configuration_settings)

Asynchronous method. Use `await describe_configuration_settings(...)` for a
synchronous call.

Arguments mapping described in
[DescribeConfigurationSettingsMessageRequestTypeDef](./type_defs.md#describeconfigurationsettingsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `TemplateName`: `str`
- `EnvironmentName`: `str`

Returns a `Coroutine` for
[ConfigurationSettingsDescriptionsTypeDef](./type_defs.md#configurationsettingsdescriptionstypedef).

<a id="describe_environment_health"></a>

### describe_environment_health

Returns information about the overall health of the specified environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_environment_health`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_environment_health](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_environment_health)

Asynchronous method. Use `await describe_environment_health(...)` for a
synchronous call.

Arguments mapping described in
[DescribeEnvironmentHealthRequestRequestTypeDef](./type_defs.md#describeenvironmenthealthrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentName`: `str`
- `EnvironmentId`: `str`
- `AttributeNames`:
  `Sequence`\[[EnvironmentHealthAttributeType](./literals.md#environmenthealthattributetype)\]

Returns a `Coroutine` for
[DescribeEnvironmentHealthResultTypeDef](./type_defs.md#describeenvironmenthealthresulttypedef).

<a id="describe_environment_managed_action_history"></a>

### describe_environment_managed_action_history

Lists an environment's completed and failed managed actions.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_environment_managed_action_history`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_environment_managed_action_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_environment_managed_action_history)

Asynchronous method. Use
`await describe_environment_managed_action_history(...)` for a synchronous
call.

Arguments mapping described in
[DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef](./type_defs.md#describeenvironmentmanagedactionhistoryrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentId`: `str`
- `EnvironmentName`: `str`
- `NextToken`: `str`
- `MaxItems`: `int`

Returns a `Coroutine` for
[DescribeEnvironmentManagedActionHistoryResultTypeDef](./type_defs.md#describeenvironmentmanagedactionhistoryresulttypedef).

<a id="describe_environment_managed_actions"></a>

### describe_environment_managed_actions

Lists an environment's upcoming and in-progress managed actions.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_environment_managed_actions`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_environment_managed_actions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_environment_managed_actions)

Asynchronous method. Use `await describe_environment_managed_actions(...)` for
a synchronous call.

Arguments mapping described in
[DescribeEnvironmentManagedActionsRequestRequestTypeDef](./type_defs.md#describeenvironmentmanagedactionsrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentName`: `str`
- `EnvironmentId`: `str`
- `Status`: [ActionStatusType](./literals.md#actionstatustype)

Returns a `Coroutine` for
[DescribeEnvironmentManagedActionsResultTypeDef](./type_defs.md#describeenvironmentmanagedactionsresulttypedef).

<a id="describe_environment_resources"></a>

### describe_environment_resources

Returns AWS resources for this environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_environment_resources`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_environment_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_environment_resources)

Asynchronous method. Use `await describe_environment_resources(...)` for a
synchronous call.

Arguments mapping described in
[DescribeEnvironmentResourcesMessageRequestTypeDef](./type_defs.md#describeenvironmentresourcesmessagerequesttypedef).

Keyword-only arguments:

- `EnvironmentId`: `str`
- `EnvironmentName`: `str`

Returns a `Coroutine` for
[EnvironmentResourceDescriptionsMessageTypeDef](./type_defs.md#environmentresourcedescriptionsmessagetypedef).

<a id="describe_environments"></a>

### describe_environments

Returns descriptions for existing environments.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_environments` method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_environments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_environments)

Asynchronous method. Use `await describe_environments(...)` for a synchronous
call.

Arguments mapping described in
[DescribeEnvironmentsMessageRequestTypeDef](./type_defs.md#describeenvironmentsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str`
- `VersionLabel`: `str`
- `EnvironmentIds`: `Sequence`\[`str`\]
- `EnvironmentNames`: `Sequence`\[`str`\]
- `IncludeDeleted`: `bool`
- `IncludedDeletedBackTo`: `Union`\[`datetime`, `str`\]
- `MaxRecords`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[EnvironmentDescriptionsMessageTypeDef](./type_defs.md#environmentdescriptionsmessagetypedef).

<a id="describe_events"></a>

### describe_events

Returns list of event descriptions matching criteria up to the last 6 weeks.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_events` method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_events)

Asynchronous method. Use `await describe_events(...)` for a synchronous call.

Arguments mapping described in
[DescribeEventsMessageRequestTypeDef](./type_defs.md#describeeventsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str`
- `VersionLabel`: `str`
- `TemplateName`: `str`
- `EnvironmentId`: `str`
- `EnvironmentName`: `str`
- `PlatformArn`: `str`
- `RequestId`: `str`
- `Severity`: [EventSeverityType](./literals.md#eventseveritytype)
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `MaxRecords`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[EventDescriptionsMessageTypeDef](./type_defs.md#eventdescriptionsmessagetypedef).

<a id="describe_instances_health"></a>

### describe_instances_health

Retrieves detailed information about the health of instances in your AWS
Elastic Beanstalk.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_instances_health`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_instances_health](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_instances_health)

Asynchronous method. Use `await describe_instances_health(...)` for a
synchronous call.

Arguments mapping described in
[DescribeInstancesHealthRequestRequestTypeDef](./type_defs.md#describeinstanceshealthrequestrequesttypedef).

Keyword-only arguments:

- `EnvironmentName`: `str`
- `EnvironmentId`: `str`
- `AttributeNames`:
  `Sequence`\[[InstancesHealthAttributeType](./literals.md#instanceshealthattributetype)\]
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeInstancesHealthResultTypeDef](./type_defs.md#describeinstanceshealthresulttypedef).

<a id="describe_platform_version"></a>

### describe_platform_version

Describes a platform version.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").describe_platform_version`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.describe_platform_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.describe_platform_version)

Asynchronous method. Use `await describe_platform_version(...)` for a
synchronous call.

Arguments mapping described in
[DescribePlatformVersionRequestRequestTypeDef](./type_defs.md#describeplatformversionrequestrequesttypedef).

Keyword-only arguments:

- `PlatformArn`: `str`

Returns a `Coroutine` for
[DescribePlatformVersionResultTypeDef](./type_defs.md#describeplatformversionresulttypedef).

<a id="disassociate_environment_operations_role"></a>

### disassociate_environment_operations_role

Disassociate the operations role from an environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").disassociate_environment_operations_role`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.disassociate_environment_operations_role](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.disassociate_environment_operations_role)

Asynchronous method. Use `await disassociate_environment_operations_role(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateEnvironmentOperationsRoleMessageRequestTypeDef](./type_defs.md#disassociateenvironmentoperationsrolemessagerequesttypedef).

Keyword-only arguments:

- `EnvironmentName`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").generate_presigned_url` method.

Boto3 documentation:
[ElasticBeanstalk.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_available_solution_stacks"></a>

### list_available_solution_stacks

Returns a list of the available solution stack names, with the public version
first and then in reverse chronological order.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").list_available_solution_stacks`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.list_available_solution_stacks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.list_available_solution_stacks)

Asynchronous method. Use `await list_available_solution_stacks(...)` for a
synchronous call.

Returns a `Coroutine` for
[ListAvailableSolutionStacksResultMessageTypeDef](./type_defs.md#listavailablesolutionstacksresultmessagetypedef).

<a id="list_platform_branches"></a>

### list_platform_branches

Lists the platform branches available for your account in an AWS Region.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").list_platform_branches` method.

Boto3 documentation:
[ElasticBeanstalk.Client.list_platform_branches](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.list_platform_branches)

Asynchronous method. Use `await list_platform_branches(...)` for a synchronous
call.

Arguments mapping described in
[ListPlatformBranchesRequestRequestTypeDef](./type_defs.md#listplatformbranchesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`:
  `Sequence`\[[SearchFilterTypeDef](./type_defs.md#searchfiltertypedef)\]
- `MaxRecords`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListPlatformBranchesResultTypeDef](./type_defs.md#listplatformbranchesresulttypedef).

<a id="list_platform_versions"></a>

### list_platform_versions

Lists the platform versions available for your account in an AWS Region.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").list_platform_versions` method.

Boto3 documentation:
[ElasticBeanstalk.Client.list_platform_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.list_platform_versions)

Asynchronous method. Use `await list_platform_versions(...)` for a synchronous
call.

Arguments mapping described in
[ListPlatformVersionsRequestRequestTypeDef](./type_defs.md#listplatformversionsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`:
  `Sequence`\[[PlatformFilterTypeDef](./type_defs.md#platformfiltertypedef)\]
- `MaxRecords`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListPlatformVersionsResultTypeDef](./type_defs.md#listplatformversionsresulttypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Return the tags applied to an AWS Elastic Beanstalk resource.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").list_tags_for_resource` method.

Boto3 documentation:
[ElasticBeanstalk.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceMessageRequestTypeDef](./type_defs.md#listtagsforresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ResourceTagsDescriptionMessageTypeDef](./type_defs.md#resourcetagsdescriptionmessagetypedef).

<a id="rebuild_environment"></a>

### rebuild_environment

Deletes and recreates all of the AWS resources (for example: the Auto Scaling
group, load balancer, etc.) for a specified environment and forces a restart.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").rebuild_environment` method.

Boto3 documentation:
[ElasticBeanstalk.Client.rebuild_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.rebuild_environment)

Asynchronous method. Use `await rebuild_environment(...)` for a synchronous
call.

Arguments mapping described in
[RebuildEnvironmentMessageRequestTypeDef](./type_defs.md#rebuildenvironmentmessagerequesttypedef).

Keyword-only arguments:

- `EnvironmentId`: `str`
- `EnvironmentName`: `str`

<a id="request_environment_info"></a>

### request_environment_info

Initiates a request to compile the specified type of information of the
deployed environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").request_environment_info`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.request_environment_info](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.request_environment_info)

Asynchronous method. Use `await request_environment_info(...)` for a
synchronous call.

Arguments mapping described in
[RequestEnvironmentInfoMessageRequestTypeDef](./type_defs.md#requestenvironmentinfomessagerequesttypedef).

Keyword-only arguments:

- `InfoType`: [EnvironmentInfoTypeType](./literals.md#environmentinfotypetype)
  *(required)*
- `EnvironmentId`: `str`
- `EnvironmentName`: `str`

<a id="restart_app_server"></a>

### restart_app_server

Causes the environment to restart the application container server running on
each Amazon EC2 instance.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").restart_app_server` method.

Boto3 documentation:
[ElasticBeanstalk.Client.restart_app_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.restart_app_server)

Asynchronous method. Use `await restart_app_server(...)` for a synchronous
call.

Arguments mapping described in
[RestartAppServerMessageRequestTypeDef](./type_defs.md#restartappservermessagerequesttypedef).

Keyword-only arguments:

- `EnvironmentId`: `str`
- `EnvironmentName`: `str`

<a id="retrieve_environment_info"></a>

### retrieve_environment_info

Retrieves the compiled information from a RequestEnvironmentInfo request.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").retrieve_environment_info`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.retrieve_environment_info](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.retrieve_environment_info)

Asynchronous method. Use `await retrieve_environment_info(...)` for a
synchronous call.

Arguments mapping described in
[RetrieveEnvironmentInfoMessageRequestTypeDef](./type_defs.md#retrieveenvironmentinfomessagerequesttypedef).

Keyword-only arguments:

- `InfoType`: [EnvironmentInfoTypeType](./literals.md#environmentinfotypetype)
  *(required)*
- `EnvironmentId`: `str`
- `EnvironmentName`: `str`

Returns a `Coroutine` for
[RetrieveEnvironmentInfoResultMessageTypeDef](./type_defs.md#retrieveenvironmentinforesultmessagetypedef).

<a id="swap_environment_cnames"></a>

### swap_environment_cnames

Swaps the CNAMEs of two environments.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").swap_environment_cnames` method.

Boto3 documentation:
[ElasticBeanstalk.Client.swap_environment_cnames](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.swap_environment_cnames)

Asynchronous method. Use `await swap_environment_cnames(...)` for a synchronous
call.

Arguments mapping described in
[SwapEnvironmentCNAMEsMessageRequestTypeDef](./type_defs.md#swapenvironmentcnamesmessagerequesttypedef).

Keyword-only arguments:

- `SourceEnvironmentId`: `str`
- `SourceEnvironmentName`: `str`
- `DestinationEnvironmentId`: `str`
- `DestinationEnvironmentName`: `str`

<a id="terminate_environment"></a>

### terminate_environment

Terminates the specified environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").terminate_environment` method.

Boto3 documentation:
[ElasticBeanstalk.Client.terminate_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.terminate_environment)

Asynchronous method. Use `await terminate_environment(...)` for a synchronous
call.

Arguments mapping described in
[TerminateEnvironmentMessageRequestTypeDef](./type_defs.md#terminateenvironmentmessagerequesttypedef).

Keyword-only arguments:

- `EnvironmentId`: `str`
- `EnvironmentName`: `str`
- `TerminateResources`: `bool`
- `ForceTerminate`: `bool`

Returns a `Coroutine` for
[EnvironmentDescriptionResponseMetadataTypeDef](./type_defs.md#environmentdescriptionresponsemetadatatypedef).

<a id="update_application"></a>

### update_application

Updates the specified application to have the specified properties.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").update_application` method.

Boto3 documentation:
[ElasticBeanstalk.Client.update_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.update_application)

Asynchronous method. Use `await update_application(...)` for a synchronous
call.

Arguments mapping described in
[UpdateApplicationMessageRequestTypeDef](./type_defs.md#updateapplicationmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `Description`: `str`

Returns a `Coroutine` for
[ApplicationDescriptionMessageTypeDef](./type_defs.md#applicationdescriptionmessagetypedef).

<a id="update_application_resource_lifecycle"></a>

### update_application_resource_lifecycle

Modifies lifecycle settings for an application.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").update_application_resource_lifecycle`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.update_application_resource_lifecycle](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.update_application_resource_lifecycle)

Asynchronous method. Use `await update_application_resource_lifecycle(...)` for
a synchronous call.

Arguments mapping described in
[UpdateApplicationResourceLifecycleMessageRequestTypeDef](./type_defs.md#updateapplicationresourcelifecyclemessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `ResourceLifecycleConfig`:
  [ApplicationResourceLifecycleConfigTypeDef](./type_defs.md#applicationresourcelifecycleconfigtypedef)
  *(required)*

Returns a `Coroutine` for
[ApplicationResourceLifecycleDescriptionMessageTypeDef](./type_defs.md#applicationresourcelifecycledescriptionmessagetypedef).

<a id="update_application_version"></a>

### update_application_version

Updates the specified application version to have the specified properties.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").update_application_version`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.update_application_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.update_application_version)

Asynchronous method. Use `await update_application_version(...)` for a
synchronous call.

Arguments mapping described in
[UpdateApplicationVersionMessageRequestTypeDef](./type_defs.md#updateapplicationversionmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `VersionLabel`: `str` *(required)*
- `Description`: `str`

Returns a `Coroutine` for
[ApplicationVersionDescriptionMessageTypeDef](./type_defs.md#applicationversiondescriptionmessagetypedef).

<a id="update_configuration_template"></a>

### update_configuration_template

Updates the specified configuration template to have the specified properties
or configuration option values.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").update_configuration_template`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.update_configuration_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.update_configuration_template)

Asynchronous method. Use `await update_configuration_template(...)` for a
synchronous call.

Arguments mapping described in
[UpdateConfigurationTemplateMessageRequestTypeDef](./type_defs.md#updateconfigurationtemplatemessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `TemplateName`: `str` *(required)*
- `Description`: `str`
- `OptionSettings`:
  `Sequence`\[[ConfigurationOptionSettingTypeDef](./type_defs.md#configurationoptionsettingtypedef)\]
- `OptionsToRemove`:
  `Sequence`\[[OptionSpecificationTypeDef](./type_defs.md#optionspecificationtypedef)\]

Returns a `Coroutine` for
[ConfigurationSettingsDescriptionResponseMetadataTypeDef](./type_defs.md#configurationsettingsdescriptionresponsemetadatatypedef).

<a id="update_environment"></a>

### update_environment

Updates the environment description, deploys a new application version, updates
the configuration settings to an entirely new configuration template, or
updates select configuration option values in the running environment.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").update_environment` method.

Boto3 documentation:
[ElasticBeanstalk.Client.update_environment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.update_environment)

Asynchronous method. Use `await update_environment(...)` for a synchronous
call.

Arguments mapping described in
[UpdateEnvironmentMessageRequestTypeDef](./type_defs.md#updateenvironmentmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str`
- `EnvironmentId`: `str`
- `EnvironmentName`: `str`
- `GroupName`: `str`
- `Description`: `str`
- `Tier`: [EnvironmentTierTypeDef](./type_defs.md#environmenttiertypedef)
- `VersionLabel`: `str`
- `TemplateName`: `str`
- `SolutionStackName`: `str`
- `PlatformArn`: `str`
- `OptionSettings`:
  `Sequence`\[[ConfigurationOptionSettingTypeDef](./type_defs.md#configurationoptionsettingtypedef)\]
- `OptionsToRemove`:
  `Sequence`\[[OptionSpecificationTypeDef](./type_defs.md#optionspecificationtypedef)\]

Returns a `Coroutine` for
[EnvironmentDescriptionResponseMetadataTypeDef](./type_defs.md#environmentdescriptionresponsemetadatatypedef).

<a id="update_tags_for_resource"></a>

### update_tags_for_resource

Update the list of tags applied to an AWS Elastic Beanstalk resource.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").update_tags_for_resource`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.update_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.update_tags_for_resource)

Asynchronous method. Use `await update_tags_for_resource(...)` for a
synchronous call.

Arguments mapping described in
[UpdateTagsForResourceMessageRequestTypeDef](./type_defs.md#updatetagsforresourcemessagerequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagsToAdd`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `TagsToRemove`: `Sequence`\[`str`\]

<a id="validate_configuration_settings"></a>

### validate_configuration_settings

Takes a set of configuration settings and either a configuration template or
environment, and determines whether those values are valid.

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").validate_configuration_settings`
method.

Boto3 documentation:
[ElasticBeanstalk.Client.validate_configuration_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Client.validate_configuration_settings)

Asynchronous method. Use `await validate_configuration_settings(...)` for a
synchronous call.

Arguments mapping described in
[ValidateConfigurationSettingsMessageRequestTypeDef](./type_defs.md#validateconfigurationsettingsmessagerequesttypedef).

Keyword-only arguments:

- `ApplicationName`: `str` *(required)*
- `OptionSettings`:
  `Sequence`\[[ConfigurationOptionSettingTypeDef](./type_defs.md#configurationoptionsettingtypedef)\]
  *(required)*
- `TemplateName`: `str`
- `EnvironmentName`: `str`

Returns a `Coroutine` for
[ConfigurationSettingsValidationMessagesTypeDef](./type_defs.md#configurationsettingsvalidationmessagestypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("elasticbeanstalk").get_paginator` method with
overloads.

- `client.get_paginator("describe_application_versions")` ->
  [DescribeApplicationVersionsPaginator](./paginators.md#describeapplicationversionspaginator)
- `client.get_paginator("describe_environment_managed_action_history")` ->
  [DescribeEnvironmentManagedActionHistoryPaginator](./paginators.md#describeenvironmentmanagedactionhistorypaginator)
- `client.get_paginator("describe_environments")` ->
  [DescribeEnvironmentsPaginator](./paginators.md#describeenvironmentspaginator)
- `client.get_paginator("describe_events")` ->
  [DescribeEventsPaginator](./paginators.md#describeeventspaginator)
- `client.get_paginator("list_platform_versions")` ->
  [ListPlatformVersionsPaginator](./paginators.md#listplatformversionspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `aiobotocore.create_client("elasticbeanstalk").get_waiter`
method with overloads.

- `client.get_waiter("environment_exists")` ->
  [EnvironmentExistsWaiter](./waiters.md#environmentexistswaiter)
- `client.get_waiter("environment_terminated")` ->
  [EnvironmentTerminatedWaiter](./waiters.md#environmentterminatedwaiter)
- `client.get_waiter("environment_updated")` ->
  [EnvironmentUpdatedWaiter](./waiters.md#environmentupdatedwaiter)
