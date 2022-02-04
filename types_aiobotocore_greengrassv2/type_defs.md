<a id="typed-dictionaries-for-aiobotocore-greengrassv2-module"></a>

# Typed dictionaries for aiobotocore GreengrassV2 module

> [Index](..) > [GreengrassV2](.) > Typed dictionaries

Auto-generated documentation for
[GreengrassV2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2)
type annotations stubs module
[types-aiobotocore-greengrassv2](https://pypi.org/project/types-aiobotocore-greengrassv2/).

- [Typed dictionaries for aiobotocore GreengrassV2 module](#typed-dictionaries-for-aiobotocore-greengrassv2-module)
  - [AssociateClientDeviceWithCoreDeviceEntryTypeDef](#associateclientdevicewithcoredeviceentrytypedef)
  - [AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef](#associateclientdevicewithcoredeviceerrorentrytypedef)
  - [AssociatedClientDeviceTypeDef](#associatedclientdevicetypedef)
  - [BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef](#batchassociateclientdevicewithcoredevicerequestrequesttypedef)
  - [BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef](#batchassociateclientdevicewithcoredeviceresponsetypedef)
  - [BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef](#batchdisassociateclientdevicefromcoredevicerequestrequesttypedef)
  - [BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef](#batchdisassociateclientdevicefromcoredeviceresponsetypedef)
  - [CancelDeploymentRequestRequestTypeDef](#canceldeploymentrequestrequesttypedef)
  - [CancelDeploymentResponseTypeDef](#canceldeploymentresponsetypedef)
  - [CloudComponentStatusTypeDef](#cloudcomponentstatustypedef)
  - [ComponentCandidateTypeDef](#componentcandidatetypedef)
  - [ComponentConfigurationUpdateTypeDef](#componentconfigurationupdatetypedef)
  - [ComponentDependencyRequirementTypeDef](#componentdependencyrequirementtypedef)
  - [ComponentDeploymentSpecificationTypeDef](#componentdeploymentspecificationtypedef)
  - [ComponentLatestVersionTypeDef](#componentlatestversiontypedef)
  - [ComponentPlatformTypeDef](#componentplatformtypedef)
  - [ComponentRunWithTypeDef](#componentrunwithtypedef)
  - [ComponentTypeDef](#componenttypedef)
  - [ComponentVersionListItemTypeDef](#componentversionlistitemtypedef)
  - [CoreDeviceTypeDef](#coredevicetypedef)
  - [CreateComponentVersionRequestRequestTypeDef](#createcomponentversionrequestrequesttypedef)
  - [CreateComponentVersionResponseTypeDef](#createcomponentversionresponsetypedef)
  - [CreateDeploymentRequestRequestTypeDef](#createdeploymentrequestrequesttypedef)
  - [CreateDeploymentResponseTypeDef](#createdeploymentresponsetypedef)
  - [DeleteComponentRequestRequestTypeDef](#deletecomponentrequestrequesttypedef)
  - [DeleteCoreDeviceRequestRequestTypeDef](#deletecoredevicerequestrequesttypedef)
  - [DeploymentComponentUpdatePolicyTypeDef](#deploymentcomponentupdatepolicytypedef)
  - [DeploymentConfigurationValidationPolicyTypeDef](#deploymentconfigurationvalidationpolicytypedef)
  - [DeploymentIoTJobConfigurationTypeDef](#deploymentiotjobconfigurationtypedef)
  - [DeploymentPoliciesTypeDef](#deploymentpoliciestypedef)
  - [DeploymentTypeDef](#deploymenttypedef)
  - [DescribeComponentRequestRequestTypeDef](#describecomponentrequestrequesttypedef)
  - [DescribeComponentResponseTypeDef](#describecomponentresponsetypedef)
  - [DisassociateClientDeviceFromCoreDeviceEntryTypeDef](#disassociateclientdevicefromcoredeviceentrytypedef)
  - [DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef](#disassociateclientdevicefromcoredeviceerrorentrytypedef)
  - [EffectiveDeploymentTypeDef](#effectivedeploymenttypedef)
  - [GetComponentRequestRequestTypeDef](#getcomponentrequestrequesttypedef)
  - [GetComponentResponseTypeDef](#getcomponentresponsetypedef)
  - [GetComponentVersionArtifactRequestRequestTypeDef](#getcomponentversionartifactrequestrequesttypedef)
  - [GetComponentVersionArtifactResponseTypeDef](#getcomponentversionartifactresponsetypedef)
  - [GetCoreDeviceRequestRequestTypeDef](#getcoredevicerequestrequesttypedef)
  - [GetCoreDeviceResponseTypeDef](#getcoredeviceresponsetypedef)
  - [GetDeploymentRequestRequestTypeDef](#getdeploymentrequestrequesttypedef)
  - [GetDeploymentResponseTypeDef](#getdeploymentresponsetypedef)
  - [InstalledComponentTypeDef](#installedcomponenttypedef)
  - [IoTJobAbortConfigTypeDef](#iotjobabortconfigtypedef)
  - [IoTJobAbortCriteriaTypeDef](#iotjobabortcriteriatypedef)
  - [IoTJobExecutionsRolloutConfigTypeDef](#iotjobexecutionsrolloutconfigtypedef)
  - [IoTJobExponentialRolloutRateTypeDef](#iotjobexponentialrolloutratetypedef)
  - [IoTJobRateIncreaseCriteriaTypeDef](#iotjobrateincreasecriteriatypedef)
  - [IoTJobTimeoutConfigTypeDef](#iotjobtimeoutconfigtypedef)
  - [LambdaContainerParamsTypeDef](#lambdacontainerparamstypedef)
  - [LambdaDeviceMountTypeDef](#lambdadevicemounttypedef)
  - [LambdaEventSourceTypeDef](#lambdaeventsourcetypedef)
  - [LambdaExecutionParametersTypeDef](#lambdaexecutionparameterstypedef)
  - [LambdaFunctionRecipeSourceTypeDef](#lambdafunctionrecipesourcetypedef)
  - [LambdaLinuxProcessParamsTypeDef](#lambdalinuxprocessparamstypedef)
  - [LambdaVolumeMountTypeDef](#lambdavolumemounttypedef)
  - [ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef](#listclientdevicesassociatedwithcoredevicerequestrequesttypedef)
  - [ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef](#listclientdevicesassociatedwithcoredeviceresponsetypedef)
  - [ListComponentVersionsRequestRequestTypeDef](#listcomponentversionsrequestrequesttypedef)
  - [ListComponentVersionsResponseTypeDef](#listcomponentversionsresponsetypedef)
  - [ListComponentsRequestRequestTypeDef](#listcomponentsrequestrequesttypedef)
  - [ListComponentsResponseTypeDef](#listcomponentsresponsetypedef)
  - [ListCoreDevicesRequestRequestTypeDef](#listcoredevicesrequestrequesttypedef)
  - [ListCoreDevicesResponseTypeDef](#listcoredevicesresponsetypedef)
  - [ListDeploymentsRequestRequestTypeDef](#listdeploymentsrequestrequesttypedef)
  - [ListDeploymentsResponseTypeDef](#listdeploymentsresponsetypedef)
  - [ListEffectiveDeploymentsRequestRequestTypeDef](#listeffectivedeploymentsrequestrequesttypedef)
  - [ListEffectiveDeploymentsResponseTypeDef](#listeffectivedeploymentsresponsetypedef)
  - [ListInstalledComponentsRequestRequestTypeDef](#listinstalledcomponentsrequestrequesttypedef)
  - [ListInstalledComponentsResponseTypeDef](#listinstalledcomponentsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ResolveComponentCandidatesRequestRequestTypeDef](#resolvecomponentcandidatesrequestrequesttypedef)
  - [ResolveComponentCandidatesResponseTypeDef](#resolvecomponentcandidatesresponsetypedef)
  - [ResolvedComponentVersionTypeDef](#resolvedcomponentversiontypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SystemResourceLimitsTypeDef](#systemresourcelimitstypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)

<a id="associateclientdevicewithcoredeviceentrytypedef"></a>

## AssociateClientDeviceWithCoreDeviceEntryTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import AssociateClientDeviceWithCoreDeviceEntryTypeDef
```

Required fields:

- `thingName`: `str`

<a id="associateclientdevicewithcoredeviceerrorentrytypedef"></a>

## AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef
```

Optional fields:

- `thingName`: `str`
- `code`: `str`
- `message`: `str`

<a id="associatedclientdevicetypedef"></a>

## AssociatedClientDeviceTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import AssociatedClientDeviceTypeDef
```

Optional fields:

- `thingName`: `str`
- `associationTimestamp`: `datetime`

<a id="batchassociateclientdevicewithcoredevicerequestrequesttypedef"></a>

## BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`

Optional fields:

- `entries`:
  `Sequence`\[[AssociateClientDeviceWithCoreDeviceEntryTypeDef](./type_defs.md#associateclientdevicewithcoredeviceentrytypedef)\]

<a id="batchassociateclientdevicewithcoredeviceresponsetypedef"></a>

## BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef
```

Required fields:

- `errorEntries`:
  `List`\[[AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef](./type_defs.md#associateclientdevicewithcoredeviceerrorentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="batchdisassociateclientdevicefromcoredevicerequestrequesttypedef"></a>

## BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`

Optional fields:

- `entries`:
  `Sequence`\[[DisassociateClientDeviceFromCoreDeviceEntryTypeDef](./type_defs.md#disassociateclientdevicefromcoredeviceentrytypedef)\]

<a id="batchdisassociateclientdevicefromcoredeviceresponsetypedef"></a>

## BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef
```

Required fields:

- `errorEntries`:
  `List`\[[DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef](./type_defs.md#disassociateclientdevicefromcoredeviceerrorentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="canceldeploymentrequestrequesttypedef"></a>

## CancelDeploymentRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CancelDeploymentRequestRequestTypeDef
```

Required fields:

- `deploymentId`: `str`

<a id="canceldeploymentresponsetypedef"></a>

## CancelDeploymentResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CancelDeploymentResponseTypeDef
```

Required fields:

- `message`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="cloudcomponentstatustypedef"></a>

## CloudComponentStatusTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CloudComponentStatusTypeDef
```

Optional fields:

- `componentState`:
  [CloudComponentStateType](./literals.md#cloudcomponentstatetype)
- `message`: `str`
- `errors`: `Dict`\[`str`, `str`\]

<a id="componentcandidatetypedef"></a>

## ComponentCandidateTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentCandidateTypeDef
```

Optional fields:

- `componentName`: `str`
- `componentVersion`: `str`
- `versionRequirements`: `Mapping`\[`str`, `str`\]

<a id="componentconfigurationupdatetypedef"></a>

## ComponentConfigurationUpdateTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentConfigurationUpdateTypeDef
```

Optional fields:

- `merge`: `str`
- `reset`: `Sequence`\[`str`\]

<a id="componentdependencyrequirementtypedef"></a>

## ComponentDependencyRequirementTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentDependencyRequirementTypeDef
```

Optional fields:

- `versionRequirement`: `str`
- `dependencyType`:
  [ComponentDependencyTypeType](./literals.md#componentdependencytypetype)

<a id="componentdeploymentspecificationtypedef"></a>

## ComponentDeploymentSpecificationTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentDeploymentSpecificationTypeDef
```

Optional fields:

- `componentVersion`: `str`
- `configurationUpdate`:
  [ComponentConfigurationUpdateTypeDef](./type_defs.md#componentconfigurationupdatetypedef)
- `runWith`: [ComponentRunWithTypeDef](./type_defs.md#componentrunwithtypedef)

<a id="componentlatestversiontypedef"></a>

## ComponentLatestVersionTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentLatestVersionTypeDef
```

Optional fields:

- `arn`: `str`
- `componentVersion`: `str`
- `creationTimestamp`: `datetime`
- `description`: `str`
- `publisher`: `str`
- `platforms`:
  `List`\[[ComponentPlatformTypeDef](./type_defs.md#componentplatformtypedef)\]

<a id="componentplatformtypedef"></a>

## ComponentPlatformTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentPlatformTypeDef
```

Optional fields:

- `name`: `str`
- `attributes`: `Mapping`\[`str`, `str`\]

<a id="componentrunwithtypedef"></a>

## ComponentRunWithTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentRunWithTypeDef
```

Optional fields:

- `posixUser`: `str`
- `systemResourceLimits`:
  [SystemResourceLimitsTypeDef](./type_defs.md#systemresourcelimitstypedef)
- `windowsUser`: `str`

<a id="componenttypedef"></a>

## ComponentTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentTypeDef
```

Optional fields:

- `arn`: `str`
- `componentName`: `str`
- `latestVersion`:
  [ComponentLatestVersionTypeDef](./type_defs.md#componentlatestversiontypedef)

<a id="componentversionlistitemtypedef"></a>

## ComponentVersionListItemTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ComponentVersionListItemTypeDef
```

Optional fields:

- `componentName`: `str`
- `componentVersion`: `str`
- `arn`: `str`

<a id="coredevicetypedef"></a>

## CoreDeviceTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CoreDeviceTypeDef
```

Optional fields:

- `coreDeviceThingName`: `str`
- `status`: [CoreDeviceStatusType](./literals.md#coredevicestatustype)
- `lastStatusUpdateTimestamp`: `datetime`

<a id="createcomponentversionrequestrequesttypedef"></a>

## CreateComponentVersionRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CreateComponentVersionRequestRequestTypeDef
```

Optional fields:

- `inlineRecipe`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `lambdaFunction`:
  [LambdaFunctionRecipeSourceTypeDef](./type_defs.md#lambdafunctionrecipesourcetypedef)
- `tags`: `Mapping`\[`str`, `str`\]
- `clientToken`: `str`

<a id="createcomponentversionresponsetypedef"></a>

## CreateComponentVersionResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CreateComponentVersionResponseTypeDef
```

Required fields:

- `arn`: `str`
- `componentName`: `str`
- `componentVersion`: `str`
- `creationTimestamp`: `datetime`
- `status`:
  [CloudComponentStatusTypeDef](./type_defs.md#cloudcomponentstatustypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdeploymentrequestrequesttypedef"></a>

## CreateDeploymentRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CreateDeploymentRequestRequestTypeDef
```

Required fields:

- `targetArn`: `str`

Optional fields:

- `deploymentName`: `str`
- `components`: `Mapping`\[`str`,
  [ComponentDeploymentSpecificationTypeDef](./type_defs.md#componentdeploymentspecificationtypedef)\]
- `iotJobConfiguration`:
  [DeploymentIoTJobConfigurationTypeDef](./type_defs.md#deploymentiotjobconfigurationtypedef)
- `deploymentPolicies`:
  [DeploymentPoliciesTypeDef](./type_defs.md#deploymentpoliciestypedef)
- `tags`: `Mapping`\[`str`, `str`\]
- `clientToken`: `str`

<a id="createdeploymentresponsetypedef"></a>

## CreateDeploymentResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import CreateDeploymentResponseTypeDef
```

Required fields:

- `deploymentId`: `str`
- `iotJobId`: `str`
- `iotJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletecomponentrequestrequesttypedef"></a>

## DeleteComponentRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DeleteComponentRequestRequestTypeDef
```

Required fields:

- `arn`: `str`

<a id="deletecoredevicerequestrequesttypedef"></a>

## DeleteCoreDeviceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DeleteCoreDeviceRequestRequestTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`

<a id="deploymentcomponentupdatepolicytypedef"></a>

## DeploymentComponentUpdatePolicyTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DeploymentComponentUpdatePolicyTypeDef
```

Optional fields:

- `timeoutInSeconds`: `int`
- `action`:
  [DeploymentComponentUpdatePolicyActionType](./literals.md#deploymentcomponentupdatepolicyactiontype)

<a id="deploymentconfigurationvalidationpolicytypedef"></a>

## DeploymentConfigurationValidationPolicyTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DeploymentConfigurationValidationPolicyTypeDef
```

Optional fields:

- `timeoutInSeconds`: `int`

<a id="deploymentiotjobconfigurationtypedef"></a>

## DeploymentIoTJobConfigurationTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DeploymentIoTJobConfigurationTypeDef
```

Optional fields:

- `jobExecutionsRolloutConfig`:
  [IoTJobExecutionsRolloutConfigTypeDef](./type_defs.md#iotjobexecutionsrolloutconfigtypedef)
- `abortConfig`:
  [IoTJobAbortConfigTypeDef](./type_defs.md#iotjobabortconfigtypedef)
- `timeoutConfig`:
  [IoTJobTimeoutConfigTypeDef](./type_defs.md#iotjobtimeoutconfigtypedef)

<a id="deploymentpoliciestypedef"></a>

## DeploymentPoliciesTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DeploymentPoliciesTypeDef
```

Optional fields:

- `failureHandlingPolicy`:
  [DeploymentFailureHandlingPolicyType](./literals.md#deploymentfailurehandlingpolicytype)
- `componentUpdatePolicy`:
  [DeploymentComponentUpdatePolicyTypeDef](./type_defs.md#deploymentcomponentupdatepolicytypedef)
- `configurationValidationPolicy`:
  [DeploymentConfigurationValidationPolicyTypeDef](./type_defs.md#deploymentconfigurationvalidationpolicytypedef)

<a id="deploymenttypedef"></a>

## DeploymentTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DeploymentTypeDef
```

Optional fields:

- `targetArn`: `str`
- `revisionId`: `str`
- `deploymentId`: `str`
- `deploymentName`: `str`
- `creationTimestamp`: `datetime`
- `deploymentStatus`:
  [DeploymentStatusType](./literals.md#deploymentstatustype)
- `isLatestForTarget`: `bool`

<a id="describecomponentrequestrequesttypedef"></a>

## DescribeComponentRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DescribeComponentRequestRequestTypeDef
```

Required fields:

- `arn`: `str`

<a id="describecomponentresponsetypedef"></a>

## DescribeComponentResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DescribeComponentResponseTypeDef
```

Required fields:

- `arn`: `str`
- `componentName`: `str`
- `componentVersion`: `str`
- `creationTimestamp`: `datetime`
- `publisher`: `str`
- `description`: `str`
- `status`:
  [CloudComponentStatusTypeDef](./type_defs.md#cloudcomponentstatustypedef)
- `platforms`:
  `List`\[[ComponentPlatformTypeDef](./type_defs.md#componentplatformtypedef)\]
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disassociateclientdevicefromcoredeviceentrytypedef"></a>

## DisassociateClientDeviceFromCoreDeviceEntryTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DisassociateClientDeviceFromCoreDeviceEntryTypeDef
```

Required fields:

- `thingName`: `str`

<a id="disassociateclientdevicefromcoredeviceerrorentrytypedef"></a>

## DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef
```

Optional fields:

- `thingName`: `str`
- `code`: `str`
- `message`: `str`

<a id="effectivedeploymenttypedef"></a>

## EffectiveDeploymentTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import EffectiveDeploymentTypeDef
```

Required fields:

- `deploymentId`: `str`
- `deploymentName`: `str`
- `targetArn`: `str`
- `coreDeviceExecutionStatus`:
  [EffectiveDeploymentExecutionStatusType](./literals.md#effectivedeploymentexecutionstatustype)
- `creationTimestamp`: `datetime`
- `modifiedTimestamp`: `datetime`

Optional fields:

- `iotJobId`: `str`
- `iotJobArn`: `str`
- `description`: `str`
- `reason`: `str`

<a id="getcomponentrequestrequesttypedef"></a>

## GetComponentRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetComponentRequestRequestTypeDef
```

Required fields:

- `arn`: `str`

Optional fields:

- `recipeOutputFormat`:
  [RecipeOutputFormatType](./literals.md#recipeoutputformattype)

<a id="getcomponentresponsetypedef"></a>

## GetComponentResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetComponentResponseTypeDef
```

Required fields:

- `recipeOutputFormat`:
  [RecipeOutputFormatType](./literals.md#recipeoutputformattype)
- `recipe`: `bytes`
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcomponentversionartifactrequestrequesttypedef"></a>

## GetComponentVersionArtifactRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetComponentVersionArtifactRequestRequestTypeDef
```

Required fields:

- `arn`: `str`
- `artifactName`: `str`

<a id="getcomponentversionartifactresponsetypedef"></a>

## GetComponentVersionArtifactResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetComponentVersionArtifactResponseTypeDef
```

Required fields:

- `preSignedUrl`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcoredevicerequestrequesttypedef"></a>

## GetCoreDeviceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetCoreDeviceRequestRequestTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`

<a id="getcoredeviceresponsetypedef"></a>

## GetCoreDeviceResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetCoreDeviceResponseTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`
- `coreVersion`: `str`
- `platform`: `str`
- `architecture`: `str`
- `status`: [CoreDeviceStatusType](./literals.md#coredevicestatustype)
- `lastStatusUpdateTimestamp`: `datetime`
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdeploymentrequestrequesttypedef"></a>

## GetDeploymentRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetDeploymentRequestRequestTypeDef
```

Required fields:

- `deploymentId`: `str`

<a id="getdeploymentresponsetypedef"></a>

## GetDeploymentResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import GetDeploymentResponseTypeDef
```

Required fields:

- `targetArn`: `str`
- `revisionId`: `str`
- `deploymentId`: `str`
- `deploymentName`: `str`
- `deploymentStatus`:
  [DeploymentStatusType](./literals.md#deploymentstatustype)
- `iotJobId`: `str`
- `iotJobArn`: `str`
- `components`: `Dict`\[`str`,
  [ComponentDeploymentSpecificationTypeDef](./type_defs.md#componentdeploymentspecificationtypedef)\]
- `deploymentPolicies`:
  [DeploymentPoliciesTypeDef](./type_defs.md#deploymentpoliciestypedef)
- `iotJobConfiguration`:
  [DeploymentIoTJobConfigurationTypeDef](./type_defs.md#deploymentiotjobconfigurationtypedef)
- `creationTimestamp`: `datetime`
- `isLatestForTarget`: `bool`
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="installedcomponenttypedef"></a>

## InstalledComponentTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import InstalledComponentTypeDef
```

Optional fields:

- `componentName`: `str`
- `componentVersion`: `str`
- `lifecycleState`:
  [InstalledComponentLifecycleStateType](./literals.md#installedcomponentlifecyclestatetype)
- `lifecycleStateDetails`: `str`
- `isRoot`: `bool`

<a id="iotjobabortconfigtypedef"></a>

## IoTJobAbortConfigTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import IoTJobAbortConfigTypeDef
```

Required fields:

- `criteriaList`:
  `Sequence`\[[IoTJobAbortCriteriaTypeDef](./type_defs.md#iotjobabortcriteriatypedef)\]

<a id="iotjobabortcriteriatypedef"></a>

## IoTJobAbortCriteriaTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import IoTJobAbortCriteriaTypeDef
```

Required fields:

- `failureType`:
  [IoTJobExecutionFailureTypeType](./literals.md#iotjobexecutionfailuretypetype)
- `action`: `Literal['CANCEL']` (see
  [IoTJobAbortActionType](./literals.md#iotjobabortactiontype))
- `thresholdPercentage`: `float`
- `minNumberOfExecutedThings`: `int`

<a id="iotjobexecutionsrolloutconfigtypedef"></a>

## IoTJobExecutionsRolloutConfigTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import IoTJobExecutionsRolloutConfigTypeDef
```

Optional fields:

- `exponentialRate`:
  [IoTJobExponentialRolloutRateTypeDef](./type_defs.md#iotjobexponentialrolloutratetypedef)
- `maximumPerMinute`: `int`

<a id="iotjobexponentialrolloutratetypedef"></a>

## IoTJobExponentialRolloutRateTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import IoTJobExponentialRolloutRateTypeDef
```

Required fields:

- `baseRatePerMinute`: `int`
- `incrementFactor`: `float`
- `rateIncreaseCriteria`:
  [IoTJobRateIncreaseCriteriaTypeDef](./type_defs.md#iotjobrateincreasecriteriatypedef)

<a id="iotjobrateincreasecriteriatypedef"></a>

## IoTJobRateIncreaseCriteriaTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import IoTJobRateIncreaseCriteriaTypeDef
```

Optional fields:

- `numberOfNotifiedThings`: `int`
- `numberOfSucceededThings`: `int`

<a id="iotjobtimeoutconfigtypedef"></a>

## IoTJobTimeoutConfigTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import IoTJobTimeoutConfigTypeDef
```

Optional fields:

- `inProgressTimeoutInMinutes`: `int`

<a id="lambdacontainerparamstypedef"></a>

## LambdaContainerParamsTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import LambdaContainerParamsTypeDef
```

Optional fields:

- `memorySizeInKB`: `int`
- `mountROSysfs`: `bool`
- `volumes`:
  `Sequence`\[[LambdaVolumeMountTypeDef](./type_defs.md#lambdavolumemounttypedef)\]
- `devices`:
  `Sequence`\[[LambdaDeviceMountTypeDef](./type_defs.md#lambdadevicemounttypedef)\]

<a id="lambdadevicemounttypedef"></a>

## LambdaDeviceMountTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import LambdaDeviceMountTypeDef
```

Required fields:

- `path`: `str`

Optional fields:

- `permission`:
  [LambdaFilesystemPermissionType](./literals.md#lambdafilesystempermissiontype)
- `addGroupOwner`: `bool`

<a id="lambdaeventsourcetypedef"></a>

## LambdaEventSourceTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import LambdaEventSourceTypeDef
```

Required fields:

- `topic`: `str`
- `type`: [LambdaEventSourceTypeType](./literals.md#lambdaeventsourcetypetype)

<a id="lambdaexecutionparameterstypedef"></a>

## LambdaExecutionParametersTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import LambdaExecutionParametersTypeDef
```

Optional fields:

- `eventSources`:
  `Sequence`\[[LambdaEventSourceTypeDef](./type_defs.md#lambdaeventsourcetypedef)\]
- `maxQueueSize`: `int`
- `maxInstancesCount`: `int`
- `maxIdleTimeInSeconds`: `int`
- `timeoutInSeconds`: `int`
- `statusTimeoutInSeconds`: `int`
- `pinned`: `bool`
- `inputPayloadEncodingType`:
  [LambdaInputPayloadEncodingTypeType](./literals.md#lambdainputpayloadencodingtypetype)
- `execArgs`: `Sequence`\[`str`\]
- `environmentVariables`: `Mapping`\[`str`, `str`\]
- `linuxProcessParams`:
  [LambdaLinuxProcessParamsTypeDef](./type_defs.md#lambdalinuxprocessparamstypedef)

<a id="lambdafunctionrecipesourcetypedef"></a>

## LambdaFunctionRecipeSourceTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import LambdaFunctionRecipeSourceTypeDef
```

Required fields:

- `lambdaArn`: `str`

Optional fields:

- `componentName`: `str`
- `componentVersion`: `str`
- `componentPlatforms`:
  `Sequence`\[[ComponentPlatformTypeDef](./type_defs.md#componentplatformtypedef)\]
- `componentDependencies`: `Mapping`\[`str`,
  [ComponentDependencyRequirementTypeDef](./type_defs.md#componentdependencyrequirementtypedef)\]
- `componentLambdaParameters`:
  [LambdaExecutionParametersTypeDef](./type_defs.md#lambdaexecutionparameterstypedef)

<a id="lambdalinuxprocessparamstypedef"></a>

## LambdaLinuxProcessParamsTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import LambdaLinuxProcessParamsTypeDef
```

Optional fields:

- `isolationMode`:
  [LambdaIsolationModeType](./literals.md#lambdaisolationmodetype)
- `containerParams`:
  [LambdaContainerParamsTypeDef](./type_defs.md#lambdacontainerparamstypedef)

<a id="lambdavolumemounttypedef"></a>

## LambdaVolumeMountTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import LambdaVolumeMountTypeDef
```

Required fields:

- `sourcePath`: `str`
- `destinationPath`: `str`

Optional fields:

- `permission`:
  [LambdaFilesystemPermissionType](./literals.md#lambdafilesystempermissiontype)
- `addGroupOwner`: `bool`

<a id="listclientdevicesassociatedwithcoredevicerequestrequesttypedef"></a>

## ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listclientdevicesassociatedwithcoredeviceresponsetypedef"></a>

## ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef
```

Required fields:

- `associatedClientDevices`:
  `List`\[[AssociatedClientDeviceTypeDef](./type_defs.md#associatedclientdevicetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcomponentversionsrequestrequesttypedef"></a>

## ListComponentVersionsRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListComponentVersionsRequestRequestTypeDef
```

Required fields:

- `arn`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listcomponentversionsresponsetypedef"></a>

## ListComponentVersionsResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListComponentVersionsResponseTypeDef
```

Required fields:

- `componentVersions`:
  `List`\[[ComponentVersionListItemTypeDef](./type_defs.md#componentversionlistitemtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcomponentsrequestrequesttypedef"></a>

## ListComponentsRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListComponentsRequestRequestTypeDef
```

Optional fields:

- `scope`:
  [ComponentVisibilityScopeType](./literals.md#componentvisibilityscopetype)
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listcomponentsresponsetypedef"></a>

## ListComponentsResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListComponentsResponseTypeDef
```

Required fields:

- `components`: `List`\[[ComponentTypeDef](./type_defs.md#componenttypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcoredevicesrequestrequesttypedef"></a>

## ListCoreDevicesRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListCoreDevicesRequestRequestTypeDef
```

Optional fields:

- `thingGroupArn`: `str`
- `status`: [CoreDeviceStatusType](./literals.md#coredevicestatustype)
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listcoredevicesresponsetypedef"></a>

## ListCoreDevicesResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListCoreDevicesResponseTypeDef
```

Required fields:

- `coreDevices`:
  `List`\[[CoreDeviceTypeDef](./type_defs.md#coredevicetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdeploymentsrequestrequesttypedef"></a>

## ListDeploymentsRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListDeploymentsRequestRequestTypeDef
```

Optional fields:

- `targetArn`: `str`
- `historyFilter`:
  [DeploymentHistoryFilterType](./literals.md#deploymenthistoryfiltertype)
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listdeploymentsresponsetypedef"></a>

## ListDeploymentsResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListDeploymentsResponseTypeDef
```

Required fields:

- `deployments`:
  `List`\[[DeploymentTypeDef](./type_defs.md#deploymenttypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listeffectivedeploymentsrequestrequesttypedef"></a>

## ListEffectiveDeploymentsRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListEffectiveDeploymentsRequestRequestTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listeffectivedeploymentsresponsetypedef"></a>

## ListEffectiveDeploymentsResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListEffectiveDeploymentsResponseTypeDef
```

Required fields:

- `effectiveDeployments`:
  `List`\[[EffectiveDeploymentTypeDef](./type_defs.md#effectivedeploymenttypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinstalledcomponentsrequestrequesttypedef"></a>

## ListInstalledComponentsRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListInstalledComponentsRequestRequestTypeDef
```

Required fields:

- `coreDeviceThingName`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listinstalledcomponentsresponsetypedef"></a>

## ListInstalledComponentsResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListInstalledComponentsResponseTypeDef
```

Required fields:

- `installedComponents`:
  `List`\[[InstalledComponentTypeDef](./type_defs.md#installedcomponenttypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="resolvecomponentcandidatesrequestrequesttypedef"></a>

## ResolveComponentCandidatesRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ResolveComponentCandidatesRequestRequestTypeDef
```

Required fields:

- `platform`:
  [ComponentPlatformTypeDef](./type_defs.md#componentplatformtypedef)
- `componentCandidates`:
  `Sequence`\[[ComponentCandidateTypeDef](./type_defs.md#componentcandidatetypedef)\]

<a id="resolvecomponentcandidatesresponsetypedef"></a>

## ResolveComponentCandidatesResponseTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ResolveComponentCandidatesResponseTypeDef
```

Required fields:

- `resolvedComponentVersions`:
  `List`\[[ResolvedComponentVersionTypeDef](./type_defs.md#resolvedcomponentversiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="resolvedcomponentversiontypedef"></a>

## ResolvedComponentVersionTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ResolvedComponentVersionTypeDef
```

Optional fields:

- `arn`: `str`
- `componentName`: `str`
- `componentVersion`: `str`
- `recipe`: `bytes`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="systemresourcelimitstypedef"></a>

## SystemResourceLimitsTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import SystemResourceLimitsTypeDef
```

Optional fields:

- `memory`: `int`
- `cpus`: `float`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_greengrassv2.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tagKeys`: `Sequence`\[`str`\]
