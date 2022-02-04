<a id="typed-dictionaries-for-aiobotocore-appconfig-module"></a>

# Typed dictionaries for aiobotocore AppConfig module

> [Index](..) > [AppConfig](.) > Typed dictionaries

Auto-generated documentation for
[AppConfig](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
type annotations stubs module
[types-aiobotocore-appconfig](https://pypi.org/project/types-aiobotocore-appconfig/).

- [Typed dictionaries for aiobotocore AppConfig module](#typed-dictionaries-for-aiobotocore-appconfig-module)
  - [ApplicationResponseMetadataTypeDef](#applicationresponsemetadatatypedef)
  - [ApplicationTypeDef](#applicationtypedef)
  - [ApplicationsTypeDef](#applicationstypedef)
  - [ConfigurationProfileSummaryTypeDef](#configurationprofilesummarytypedef)
  - [ConfigurationProfileTypeDef](#configurationprofiletypedef)
  - [ConfigurationProfilesTypeDef](#configurationprofilestypedef)
  - [ConfigurationTypeDef](#configurationtypedef)
  - [CreateApplicationRequestRequestTypeDef](#createapplicationrequestrequesttypedef)
  - [CreateConfigurationProfileRequestRequestTypeDef](#createconfigurationprofilerequestrequesttypedef)
  - [CreateDeploymentStrategyRequestRequestTypeDef](#createdeploymentstrategyrequestrequesttypedef)
  - [CreateEnvironmentRequestRequestTypeDef](#createenvironmentrequestrequesttypedef)
  - [CreateHostedConfigurationVersionRequestRequestTypeDef](#createhostedconfigurationversionrequestrequesttypedef)
  - [DeleteApplicationRequestRequestTypeDef](#deleteapplicationrequestrequesttypedef)
  - [DeleteConfigurationProfileRequestRequestTypeDef](#deleteconfigurationprofilerequestrequesttypedef)
  - [DeleteDeploymentStrategyRequestRequestTypeDef](#deletedeploymentstrategyrequestrequesttypedef)
  - [DeleteEnvironmentRequestRequestTypeDef](#deleteenvironmentrequestrequesttypedef)
  - [DeleteHostedConfigurationVersionRequestRequestTypeDef](#deletehostedconfigurationversionrequestrequesttypedef)
  - [DeploymentEventTypeDef](#deploymenteventtypedef)
  - [DeploymentStrategiesTypeDef](#deploymentstrategiestypedef)
  - [DeploymentStrategyResponseMetadataTypeDef](#deploymentstrategyresponsemetadatatypedef)
  - [DeploymentStrategyTypeDef](#deploymentstrategytypedef)
  - [DeploymentSummaryTypeDef](#deploymentsummarytypedef)
  - [DeploymentTypeDef](#deploymenttypedef)
  - [DeploymentsTypeDef](#deploymentstypedef)
  - [EnvironmentResponseMetadataTypeDef](#environmentresponsemetadatatypedef)
  - [EnvironmentTypeDef](#environmenttypedef)
  - [EnvironmentsTypeDef](#environmentstypedef)
  - [GetApplicationRequestRequestTypeDef](#getapplicationrequestrequesttypedef)
  - [GetConfigurationProfileRequestRequestTypeDef](#getconfigurationprofilerequestrequesttypedef)
  - [GetConfigurationRequestRequestTypeDef](#getconfigurationrequestrequesttypedef)
  - [GetDeploymentRequestRequestTypeDef](#getdeploymentrequestrequesttypedef)
  - [GetDeploymentStrategyRequestRequestTypeDef](#getdeploymentstrategyrequestrequesttypedef)
  - [GetEnvironmentRequestRequestTypeDef](#getenvironmentrequestrequesttypedef)
  - [GetHostedConfigurationVersionRequestRequestTypeDef](#gethostedconfigurationversionrequestrequesttypedef)
  - [HostedConfigurationVersionSummaryTypeDef](#hostedconfigurationversionsummarytypedef)
  - [HostedConfigurationVersionTypeDef](#hostedconfigurationversiontypedef)
  - [HostedConfigurationVersionsTypeDef](#hostedconfigurationversionstypedef)
  - [ListApplicationsRequestRequestTypeDef](#listapplicationsrequestrequesttypedef)
  - [ListConfigurationProfilesRequestRequestTypeDef](#listconfigurationprofilesrequestrequesttypedef)
  - [ListDeploymentStrategiesRequestRequestTypeDef](#listdeploymentstrategiesrequestrequesttypedef)
  - [ListDeploymentsRequestRequestTypeDef](#listdeploymentsrequestrequesttypedef)
  - [ListEnvironmentsRequestRequestTypeDef](#listenvironmentsrequestrequesttypedef)
  - [ListHostedConfigurationVersionsRequestRequestTypeDef](#listhostedconfigurationversionsrequestrequesttypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [MonitorTypeDef](#monitortypedef)
  - [ResourceTagsTypeDef](#resourcetagstypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [StartDeploymentRequestRequestTypeDef](#startdeploymentrequestrequesttypedef)
  - [StopDeploymentRequestRequestTypeDef](#stopdeploymentrequestrequesttypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateApplicationRequestRequestTypeDef](#updateapplicationrequestrequesttypedef)
  - [UpdateConfigurationProfileRequestRequestTypeDef](#updateconfigurationprofilerequestrequesttypedef)
  - [UpdateDeploymentStrategyRequestRequestTypeDef](#updatedeploymentstrategyrequestrequesttypedef)
  - [UpdateEnvironmentRequestRequestTypeDef](#updateenvironmentrequestrequesttypedef)
  - [ValidateConfigurationRequestRequestTypeDef](#validateconfigurationrequestrequesttypedef)
  - [ValidatorTypeDef](#validatortypedef)

<a id="applicationresponsemetadatatypedef"></a>

## ApplicationResponseMetadataTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ApplicationResponseMetadataTypeDef
```

Required fields:

- `Id`: `str`
- `Name`: `str`
- `Description`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="applicationtypedef"></a>

## ApplicationTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ApplicationTypeDef
```

Optional fields:

- `Id`: `str`
- `Name`: `str`
- `Description`: `str`

<a id="applicationstypedef"></a>

## ApplicationsTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ApplicationsTypeDef
```

Required fields:

- `Items`: `List`\[[ApplicationTypeDef](./type_defs.md#applicationtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="configurationprofilesummarytypedef"></a>

## ConfigurationProfileSummaryTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ConfigurationProfileSummaryTypeDef
```

Optional fields:

- `ApplicationId`: `str`
- `Id`: `str`
- `Name`: `str`
- `LocationUri`: `str`
- `ValidatorTypes`:
  `List`\[[ValidatorTypeType](./literals.md#validatortypetype)\]
- `Type`: `str`

<a id="configurationprofiletypedef"></a>

## ConfigurationProfileTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ConfigurationProfileTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `Id`: `str`
- `Name`: `str`
- `Description`: `str`
- `LocationUri`: `str`
- `RetrievalRoleArn`: `str`
- `Validators`: `List`\[[ValidatorTypeDef](./type_defs.md#validatortypedef)\]
- `Type`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="configurationprofilestypedef"></a>

## ConfigurationProfilesTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ConfigurationProfilesTypeDef
```

Required fields:

- `Items`:
  `List`\[[ConfigurationProfileSummaryTypeDef](./type_defs.md#configurationprofilesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="configurationtypedef"></a>

## ConfigurationTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ConfigurationTypeDef
```

Required fields:

- `Content`: `StreamingBody`
- `ConfigurationVersion`: `str`
- `ContentType`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createapplicationrequestrequesttypedef"></a>

## CreateApplicationRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import CreateApplicationRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="createconfigurationprofilerequestrequesttypedef"></a>

## CreateConfigurationProfileRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import CreateConfigurationProfileRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `Name`: `str`
- `LocationUri`: `str`

Optional fields:

- `Description`: `str`
- `RetrievalRoleArn`: `str`
- `Validators`:
  `Sequence`\[[ValidatorTypeDef](./type_defs.md#validatortypedef)\]
- `Tags`: `Mapping`\[`str`, `str`\]
- `Type`: `str`

<a id="createdeploymentstrategyrequestrequesttypedef"></a>

## CreateDeploymentStrategyRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import CreateDeploymentStrategyRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `DeploymentDurationInMinutes`: `int`
- `GrowthFactor`: `float`
- `ReplicateTo`: [ReplicateToType](./literals.md#replicatetotype)

Optional fields:

- `Description`: `str`
- `FinalBakeTimeInMinutes`: `int`
- `GrowthType`: [GrowthTypeType](./literals.md#growthtypetype)
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="createenvironmentrequestrequesttypedef"></a>

## CreateEnvironmentRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import CreateEnvironmentRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `Name`: `str`

Optional fields:

- `Description`: `str`
- `Monitors`: `Sequence`\[[MonitorTypeDef](./type_defs.md#monitortypedef)\]
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="createhostedconfigurationversionrequestrequesttypedef"></a>

## CreateHostedConfigurationVersionRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import CreateHostedConfigurationVersionRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`
- `Content`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `ContentType`: `str`

Optional fields:

- `Description`: `str`
- `LatestVersionNumber`: `int`

<a id="deleteapplicationrequestrequesttypedef"></a>

## DeleteApplicationRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeleteApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`

<a id="deleteconfigurationprofilerequestrequesttypedef"></a>

## DeleteConfigurationProfileRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeleteConfigurationProfileRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`

<a id="deletedeploymentstrategyrequestrequesttypedef"></a>

## DeleteDeploymentStrategyRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeleteDeploymentStrategyRequestRequestTypeDef
```

Required fields:

- `DeploymentStrategyId`: `str`

<a id="deleteenvironmentrequestrequesttypedef"></a>

## DeleteEnvironmentRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeleteEnvironmentRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`

<a id="deletehostedconfigurationversionrequestrequesttypedef"></a>

## DeleteHostedConfigurationVersionRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeleteHostedConfigurationVersionRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`
- `VersionNumber`: `int`

<a id="deploymenteventtypedef"></a>

## DeploymentEventTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeploymentEventTypeDef
```

Optional fields:

- `EventType`: [DeploymentEventTypeType](./literals.md#deploymenteventtypetype)
- `TriggeredBy`: [TriggeredByType](./literals.md#triggeredbytype)
- `Description`: `str`
- `OccurredAt`: `datetime`

<a id="deploymentstrategiestypedef"></a>

## DeploymentStrategiesTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeploymentStrategiesTypeDef
```

Required fields:

- `Items`:
  `List`\[[DeploymentStrategyTypeDef](./type_defs.md#deploymentstrategytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deploymentstrategyresponsemetadatatypedef"></a>

## DeploymentStrategyResponseMetadataTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeploymentStrategyResponseMetadataTypeDef
```

Required fields:

- `Id`: `str`
- `Name`: `str`
- `Description`: `str`
- `DeploymentDurationInMinutes`: `int`
- `GrowthType`: [GrowthTypeType](./literals.md#growthtypetype)
- `GrowthFactor`: `float`
- `FinalBakeTimeInMinutes`: `int`
- `ReplicateTo`: [ReplicateToType](./literals.md#replicatetotype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deploymentstrategytypedef"></a>

## DeploymentStrategyTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeploymentStrategyTypeDef
```

Optional fields:

- `Id`: `str`
- `Name`: `str`
- `Description`: `str`
- `DeploymentDurationInMinutes`: `int`
- `GrowthType`: [GrowthTypeType](./literals.md#growthtypetype)
- `GrowthFactor`: `float`
- `FinalBakeTimeInMinutes`: `int`
- `ReplicateTo`: [ReplicateToType](./literals.md#replicatetotype)

<a id="deploymentsummarytypedef"></a>

## DeploymentSummaryTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeploymentSummaryTypeDef
```

Optional fields:

- `DeploymentNumber`: `int`
- `ConfigurationName`: `str`
- `ConfigurationVersion`: `str`
- `DeploymentDurationInMinutes`: `int`
- `GrowthType`: [GrowthTypeType](./literals.md#growthtypetype)
- `GrowthFactor`: `float`
- `FinalBakeTimeInMinutes`: `int`
- `State`: [DeploymentStateType](./literals.md#deploymentstatetype)
- `PercentageComplete`: `float`
- `StartedAt`: `datetime`
- `CompletedAt`: `datetime`

<a id="deploymenttypedef"></a>

## DeploymentTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeploymentTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`
- `DeploymentStrategyId`: `str`
- `ConfigurationProfileId`: `str`
- `DeploymentNumber`: `int`
- `ConfigurationName`: `str`
- `ConfigurationLocationUri`: `str`
- `ConfigurationVersion`: `str`
- `Description`: `str`
- `DeploymentDurationInMinutes`: `int`
- `GrowthType`: [GrowthTypeType](./literals.md#growthtypetype)
- `GrowthFactor`: `float`
- `FinalBakeTimeInMinutes`: `int`
- `State`: [DeploymentStateType](./literals.md#deploymentstatetype)
- `EventLog`:
  `List`\[[DeploymentEventTypeDef](./type_defs.md#deploymenteventtypedef)\]
- `PercentageComplete`: `float`
- `StartedAt`: `datetime`
- `CompletedAt`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deploymentstypedef"></a>

## DeploymentsTypeDef

```python
from types_aiobotocore_appconfig.type_defs import DeploymentsTypeDef
```

Required fields:

- `Items`:
  `List`\[[DeploymentSummaryTypeDef](./type_defs.md#deploymentsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="environmentresponsemetadatatypedef"></a>

## EnvironmentResponseMetadataTypeDef

```python
from types_aiobotocore_appconfig.type_defs import EnvironmentResponseMetadataTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `Id`: `str`
- `Name`: `str`
- `Description`: `str`
- `State`: [EnvironmentStateType](./literals.md#environmentstatetype)
- `Monitors`: `List`\[[MonitorTypeDef](./type_defs.md#monitortypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="environmenttypedef"></a>

## EnvironmentTypeDef

```python
from types_aiobotocore_appconfig.type_defs import EnvironmentTypeDef
```

Optional fields:

- `ApplicationId`: `str`
- `Id`: `str`
- `Name`: `str`
- `Description`: `str`
- `State`: [EnvironmentStateType](./literals.md#environmentstatetype)
- `Monitors`: `List`\[[MonitorTypeDef](./type_defs.md#monitortypedef)\]

<a id="environmentstypedef"></a>

## EnvironmentsTypeDef

```python
from types_aiobotocore_appconfig.type_defs import EnvironmentsTypeDef
```

Required fields:

- `Items`: `List`\[[EnvironmentTypeDef](./type_defs.md#environmenttypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getapplicationrequestrequesttypedef"></a>

## GetApplicationRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import GetApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`

<a id="getconfigurationprofilerequestrequesttypedef"></a>

## GetConfigurationProfileRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import GetConfigurationProfileRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`

<a id="getconfigurationrequestrequesttypedef"></a>

## GetConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import GetConfigurationRequestRequestTypeDef
```

Required fields:

- `Application`: `str`
- `Environment`: `str`
- `Configuration`: `str`
- `ClientId`: `str`

Optional fields:

- `ClientConfigurationVersion`: `str`

<a id="getdeploymentrequestrequesttypedef"></a>

## GetDeploymentRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import GetDeploymentRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`
- `DeploymentNumber`: `int`

<a id="getdeploymentstrategyrequestrequesttypedef"></a>

## GetDeploymentStrategyRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import GetDeploymentStrategyRequestRequestTypeDef
```

Required fields:

- `DeploymentStrategyId`: `str`

<a id="getenvironmentrequestrequesttypedef"></a>

## GetEnvironmentRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import GetEnvironmentRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`

<a id="gethostedconfigurationversionrequestrequesttypedef"></a>

## GetHostedConfigurationVersionRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import GetHostedConfigurationVersionRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`
- `VersionNumber`: `int`

<a id="hostedconfigurationversionsummarytypedef"></a>

## HostedConfigurationVersionSummaryTypeDef

```python
from types_aiobotocore_appconfig.type_defs import HostedConfigurationVersionSummaryTypeDef
```

Optional fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`
- `VersionNumber`: `int`
- `Description`: `str`
- `ContentType`: `str`

<a id="hostedconfigurationversiontypedef"></a>

## HostedConfigurationVersionTypeDef

```python
from types_aiobotocore_appconfig.type_defs import HostedConfigurationVersionTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`
- `VersionNumber`: `int`
- `Description`: `str`
- `Content`: `StreamingBody`
- `ContentType`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="hostedconfigurationversionstypedef"></a>

## HostedConfigurationVersionsTypeDef

```python
from types_aiobotocore_appconfig.type_defs import HostedConfigurationVersionsTypeDef
```

Required fields:

- `Items`:
  `List`\[[HostedConfigurationVersionSummaryTypeDef](./type_defs.md#hostedconfigurationversionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listapplicationsrequestrequesttypedef"></a>

## ListApplicationsRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ListApplicationsRequestRequestTypeDef
```

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listconfigurationprofilesrequestrequesttypedef"></a>

## ListConfigurationProfilesRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ListConfigurationProfilesRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Type`: `str`

<a id="listdeploymentstrategiesrequestrequesttypedef"></a>

## ListDeploymentStrategiesRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ListDeploymentStrategiesRequestRequestTypeDef
```

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listdeploymentsrequestrequesttypedef"></a>

## ListDeploymentsRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ListDeploymentsRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listenvironmentsrequestrequesttypedef"></a>

## ListEnvironmentsRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ListEnvironmentsRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listhostedconfigurationversionsrequestrequesttypedef"></a>

## ListHostedConfigurationVersionsRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ListHostedConfigurationVersionsRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="monitortypedef"></a>

## MonitorTypeDef

```python
from types_aiobotocore_appconfig.type_defs import MonitorTypeDef
```

Required fields:

- `AlarmArn`: `str`

Optional fields:

- `AlarmRoleArn`: `str`

<a id="resourcetagstypedef"></a>

## ResourceTagsTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ResourceTagsTypeDef
```

Required fields:

- `Tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="startdeploymentrequestrequesttypedef"></a>

## StartDeploymentRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import StartDeploymentRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`
- `DeploymentStrategyId`: `str`
- `ConfigurationProfileId`: `str`
- `ConfigurationVersion`: `str`

Optional fields:

- `Description`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="stopdeploymentrequestrequesttypedef"></a>

## StopDeploymentRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import StopDeploymentRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`
- `DeploymentNumber`: `int`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updateapplicationrequestrequesttypedef"></a>

## UpdateApplicationRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import UpdateApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`

Optional fields:

- `Name`: `str`
- `Description`: `str`

<a id="updateconfigurationprofilerequestrequesttypedef"></a>

## UpdateConfigurationProfileRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import UpdateConfigurationProfileRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`

Optional fields:

- `Name`: `str`
- `Description`: `str`
- `RetrievalRoleArn`: `str`
- `Validators`:
  `Sequence`\[[ValidatorTypeDef](./type_defs.md#validatortypedef)\]

<a id="updatedeploymentstrategyrequestrequesttypedef"></a>

## UpdateDeploymentStrategyRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import UpdateDeploymentStrategyRequestRequestTypeDef
```

Required fields:

- `DeploymentStrategyId`: `str`

Optional fields:

- `Description`: `str`
- `DeploymentDurationInMinutes`: `int`
- `FinalBakeTimeInMinutes`: `int`
- `GrowthFactor`: `float`
- `GrowthType`: [GrowthTypeType](./literals.md#growthtypetype)

<a id="updateenvironmentrequestrequesttypedef"></a>

## UpdateEnvironmentRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import UpdateEnvironmentRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `EnvironmentId`: `str`

Optional fields:

- `Name`: `str`
- `Description`: `str`
- `Monitors`: `Sequence`\[[MonitorTypeDef](./type_defs.md#monitortypedef)\]

<a id="validateconfigurationrequestrequesttypedef"></a>

## ValidateConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ValidateConfigurationRequestRequestTypeDef
```

Required fields:

- `ApplicationId`: `str`
- `ConfigurationProfileId`: `str`
- `ConfigurationVersion`: `str`

<a id="validatortypedef"></a>

## ValidatorTypeDef

```python
from types_aiobotocore_appconfig.type_defs import ValidatorTypeDef
```

Required fields:

- `Type`: [ValidatorTypeType](./literals.md#validatortypetype)
- `Content`: `str`
