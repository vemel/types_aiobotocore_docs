<a id="type-annotations-for-aiobotocore-appconfig-module"></a>

# Type annotations for aiobotocore AppConfig module

> [Index](..) > AppConfig

Auto-generated documentation for
[AppConfig](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
type annotations stubs module
[types-aiobotocore-appconfig](https://pypi.org/project/types-aiobotocore-appconfig/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[appconfig]'

# install as a standalone
pip install types-aiobotocore-appconfig
```

- [Type annotations for aiobotocore AppConfig module](#type-annotations-for-aiobotocore-appconfig-module)
  - [AppConfigClient](#appconfigclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="appconfigclient"></a>

## AppConfigClient

Type annotations for `aiobotocore.create_client("appconfig")` as
[AppConfigClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_appconfig.client import AppConfigClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_application](./client.md#create_application)
- [create_configuration_profile](./client.md#create_configuration_profile)
- [create_deployment_strategy](./client.md#create_deployment_strategy)
- [create_environment](./client.md#create_environment)
- [create_hosted_configuration_version](./client.md#create_hosted_configuration_version)
- [delete_application](./client.md#delete_application)
- [delete_configuration_profile](./client.md#delete_configuration_profile)
- [delete_deployment_strategy](./client.md#delete_deployment_strategy)
- [delete_environment](./client.md#delete_environment)
- [delete_hosted_configuration_version](./client.md#delete_hosted_configuration_version)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_application](./client.md#get_application)
- [get_configuration](./client.md#get_configuration)
- [get_configuration_profile](./client.md#get_configuration_profile)
- [get_deployment](./client.md#get_deployment)
- [get_deployment_strategy](./client.md#get_deployment_strategy)
- [get_environment](./client.md#get_environment)
- [get_hosted_configuration_version](./client.md#get_hosted_configuration_version)
- [list_applications](./client.md#list_applications)
- [list_configuration_profiles](./client.md#list_configuration_profiles)
- [list_deployment_strategies](./client.md#list_deployment_strategies)
- [list_deployments](./client.md#list_deployments)
- [list_environments](./client.md#list_environments)
- [list_hosted_configuration_versions](./client.md#list_hosted_configuration_versions)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [start_deployment](./client.md#start_deployment)
- [stop_deployment](./client.md#stop_deployment)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_application](./client.md#update_application)
- [update_configuration_profile](./client.md#update_configuration_profile)
- [update_deployment_strategy](./client.md#update_deployment_strategy)
- [update_environment](./client.md#update_environment)
- [validate_configuration](./client.md#validate_configuration)

<a id="exceptions"></a>

### Exceptions

AppConfigClient [exceptions](./client.md#exceptions)

- BadRequestException
- ClientError
- ConflictException
- InternalServerException
- PayloadTooLargeException
- ResourceNotFoundException
- ServiceQuotaExceededException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_appconfig.literals import DeploymentEventTypeType, ...
```

- [DeploymentEventTypeType](./literals.md#deploymenteventtypetype)
- [DeploymentStateType](./literals.md#deploymentstatetype)
- [EnvironmentStateType](./literals.md#environmentstatetype)
- [GrowthTypeType](./literals.md#growthtypetype)
- [ReplicateToType](./literals.md#replicatetotype)
- [TriggeredByType](./literals.md#triggeredbytype)
- [ValidatorTypeType](./literals.md#validatortypetype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_appconfig.type_defs import ApplicationResponseMetadataTypeDef, ...
```

- [ApplicationResponseMetadataTypeDef](./type_defs.md#applicationresponsemetadatatypedef)
- [ApplicationTypeDef](./type_defs.md#applicationtypedef)
- [ApplicationsTypeDef](./type_defs.md#applicationstypedef)
- [ConfigurationProfileSummaryTypeDef](./type_defs.md#configurationprofilesummarytypedef)
- [ConfigurationProfileTypeDef](./type_defs.md#configurationprofiletypedef)
- [ConfigurationProfilesTypeDef](./type_defs.md#configurationprofilestypedef)
- [ConfigurationTypeDef](./type_defs.md#configurationtypedef)
- [CreateApplicationRequestRequestTypeDef](./type_defs.md#createapplicationrequestrequesttypedef)
- [CreateConfigurationProfileRequestRequestTypeDef](./type_defs.md#createconfigurationprofilerequestrequesttypedef)
- [CreateDeploymentStrategyRequestRequestTypeDef](./type_defs.md#createdeploymentstrategyrequestrequesttypedef)
- [CreateEnvironmentRequestRequestTypeDef](./type_defs.md#createenvironmentrequestrequesttypedef)
- [CreateHostedConfigurationVersionRequestRequestTypeDef](./type_defs.md#createhostedconfigurationversionrequestrequesttypedef)
- [DeleteApplicationRequestRequestTypeDef](./type_defs.md#deleteapplicationrequestrequesttypedef)
- [DeleteConfigurationProfileRequestRequestTypeDef](./type_defs.md#deleteconfigurationprofilerequestrequesttypedef)
- [DeleteDeploymentStrategyRequestRequestTypeDef](./type_defs.md#deletedeploymentstrategyrequestrequesttypedef)
- [DeleteEnvironmentRequestRequestTypeDef](./type_defs.md#deleteenvironmentrequestrequesttypedef)
- [DeleteHostedConfigurationVersionRequestRequestTypeDef](./type_defs.md#deletehostedconfigurationversionrequestrequesttypedef)
- [DeploymentEventTypeDef](./type_defs.md#deploymenteventtypedef)
- [DeploymentStrategiesTypeDef](./type_defs.md#deploymentstrategiestypedef)
- [DeploymentStrategyResponseMetadataTypeDef](./type_defs.md#deploymentstrategyresponsemetadatatypedef)
- [DeploymentStrategyTypeDef](./type_defs.md#deploymentstrategytypedef)
- [DeploymentSummaryTypeDef](./type_defs.md#deploymentsummarytypedef)
- [DeploymentTypeDef](./type_defs.md#deploymenttypedef)
- [DeploymentsTypeDef](./type_defs.md#deploymentstypedef)
- [EnvironmentResponseMetadataTypeDef](./type_defs.md#environmentresponsemetadatatypedef)
- [EnvironmentTypeDef](./type_defs.md#environmenttypedef)
- [EnvironmentsTypeDef](./type_defs.md#environmentstypedef)
- [GetApplicationRequestRequestTypeDef](./type_defs.md#getapplicationrequestrequesttypedef)
- [GetConfigurationProfileRequestRequestTypeDef](./type_defs.md#getconfigurationprofilerequestrequesttypedef)
- [GetConfigurationRequestRequestTypeDef](./type_defs.md#getconfigurationrequestrequesttypedef)
- [GetDeploymentRequestRequestTypeDef](./type_defs.md#getdeploymentrequestrequesttypedef)
- [GetDeploymentStrategyRequestRequestTypeDef](./type_defs.md#getdeploymentstrategyrequestrequesttypedef)
- [GetEnvironmentRequestRequestTypeDef](./type_defs.md#getenvironmentrequestrequesttypedef)
- [GetHostedConfigurationVersionRequestRequestTypeDef](./type_defs.md#gethostedconfigurationversionrequestrequesttypedef)
- [HostedConfigurationVersionSummaryTypeDef](./type_defs.md#hostedconfigurationversionsummarytypedef)
- [HostedConfigurationVersionTypeDef](./type_defs.md#hostedconfigurationversiontypedef)
- [HostedConfigurationVersionsTypeDef](./type_defs.md#hostedconfigurationversionstypedef)
- [ListApplicationsRequestRequestTypeDef](./type_defs.md#listapplicationsrequestrequesttypedef)
- [ListConfigurationProfilesRequestRequestTypeDef](./type_defs.md#listconfigurationprofilesrequestrequesttypedef)
- [ListDeploymentStrategiesRequestRequestTypeDef](./type_defs.md#listdeploymentstrategiesrequestrequesttypedef)
- [ListDeploymentsRequestRequestTypeDef](./type_defs.md#listdeploymentsrequestrequesttypedef)
- [ListEnvironmentsRequestRequestTypeDef](./type_defs.md#listenvironmentsrequestrequesttypedef)
- [ListHostedConfigurationVersionsRequestRequestTypeDef](./type_defs.md#listhostedconfigurationversionsrequestrequesttypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [MonitorTypeDef](./type_defs.md#monitortypedef)
- [ResourceTagsTypeDef](./type_defs.md#resourcetagstypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartDeploymentRequestRequestTypeDef](./type_defs.md#startdeploymentrequestrequesttypedef)
- [StopDeploymentRequestRequestTypeDef](./type_defs.md#stopdeploymentrequestrequesttypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateApplicationRequestRequestTypeDef](./type_defs.md#updateapplicationrequestrequesttypedef)
- [UpdateConfigurationProfileRequestRequestTypeDef](./type_defs.md#updateconfigurationprofilerequestrequesttypedef)
- [UpdateDeploymentStrategyRequestRequestTypeDef](./type_defs.md#updatedeploymentstrategyrequestrequesttypedef)
- [UpdateEnvironmentRequestRequestTypeDef](./type_defs.md#updateenvironmentrequestrequesttypedef)
- [ValidateConfigurationRequestRequestTypeDef](./type_defs.md#validateconfigurationrequestrequesttypedef)
- [ValidatorTypeDef](./type_defs.md#validatortypedef)
