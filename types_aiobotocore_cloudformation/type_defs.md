<a id="typed-dictionaries-for-aiobotocore-cloudformation-module"></a>

# Typed dictionaries for aiobotocore CloudFormation module

> [Index](..) > [CloudFormation](.) > Typed dictionaries

Auto-generated documentation for
[CloudFormation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
type annotations stubs module
[types-aiobotocore-cloudformation](https://pypi.org/project/types-aiobotocore-cloudformation/).

- [Typed dictionaries for aiobotocore CloudFormation module](#typed-dictionaries-for-aiobotocore-cloudformation-module)
  - [AccountGateResultTypeDef](#accountgateresulttypedef)
  - [AccountLimitTypeDef](#accountlimittypedef)
  - [ActivateTypeInputRequestTypeDef](#activatetypeinputrequesttypedef)
  - [ActivateTypeOutputTypeDef](#activatetypeoutputtypedef)
  - [AutoDeploymentTypeDef](#autodeploymenttypedef)
  - [BatchDescribeTypeConfigurationsErrorTypeDef](#batchdescribetypeconfigurationserrortypedef)
  - [BatchDescribeTypeConfigurationsInputRequestTypeDef](#batchdescribetypeconfigurationsinputrequesttypedef)
  - [BatchDescribeTypeConfigurationsOutputTypeDef](#batchdescribetypeconfigurationsoutputtypedef)
  - [CancelUpdateStackInputRequestTypeDef](#cancelupdatestackinputrequesttypedef)
  - [CancelUpdateStackInputStackTypeDef](#cancelupdatestackinputstacktypedef)
  - [ChangeSetSummaryTypeDef](#changesetsummarytypedef)
  - [ChangeTypeDef](#changetypedef)
  - [ContinueUpdateRollbackInputRequestTypeDef](#continueupdaterollbackinputrequesttypedef)
  - [CreateChangeSetInputRequestTypeDef](#createchangesetinputrequesttypedef)
  - [CreateChangeSetOutputTypeDef](#createchangesetoutputtypedef)
  - [CreateStackInputRequestTypeDef](#createstackinputrequesttypedef)
  - [CreateStackInputServiceResourceTypeDef](#createstackinputserviceresourcetypedef)
  - [CreateStackInstancesInputRequestTypeDef](#createstackinstancesinputrequesttypedef)
  - [CreateStackInstancesOutputTypeDef](#createstackinstancesoutputtypedef)
  - [CreateStackOutputTypeDef](#createstackoutputtypedef)
  - [CreateStackSetInputRequestTypeDef](#createstacksetinputrequesttypedef)
  - [CreateStackSetOutputTypeDef](#createstacksetoutputtypedef)
  - [DeactivateTypeInputRequestTypeDef](#deactivatetypeinputrequesttypedef)
  - [DeleteChangeSetInputRequestTypeDef](#deletechangesetinputrequesttypedef)
  - [DeleteStackInputRequestTypeDef](#deletestackinputrequesttypedef)
  - [DeleteStackInputStackTypeDef](#deletestackinputstacktypedef)
  - [DeleteStackInstancesInputRequestTypeDef](#deletestackinstancesinputrequesttypedef)
  - [DeleteStackInstancesOutputTypeDef](#deletestackinstancesoutputtypedef)
  - [DeleteStackSetInputRequestTypeDef](#deletestacksetinputrequesttypedef)
  - [DeploymentTargetsTypeDef](#deploymenttargetstypedef)
  - [DeregisterTypeInputRequestTypeDef](#deregistertypeinputrequesttypedef)
  - [DescribeAccountLimitsInputRequestTypeDef](#describeaccountlimitsinputrequesttypedef)
  - [DescribeAccountLimitsOutputTypeDef](#describeaccountlimitsoutputtypedef)
  - [DescribeChangeSetInputRequestTypeDef](#describechangesetinputrequesttypedef)
  - [DescribeChangeSetOutputTypeDef](#describechangesetoutputtypedef)
  - [DescribePublisherInputRequestTypeDef](#describepublisherinputrequesttypedef)
  - [DescribePublisherOutputTypeDef](#describepublisheroutputtypedef)
  - [DescribeStackDriftDetectionStatusInputRequestTypeDef](#describestackdriftdetectionstatusinputrequesttypedef)
  - [DescribeStackDriftDetectionStatusOutputTypeDef](#describestackdriftdetectionstatusoutputtypedef)
  - [DescribeStackEventsInputRequestTypeDef](#describestackeventsinputrequesttypedef)
  - [DescribeStackEventsOutputTypeDef](#describestackeventsoutputtypedef)
  - [DescribeStackInstanceInputRequestTypeDef](#describestackinstanceinputrequesttypedef)
  - [DescribeStackInstanceOutputTypeDef](#describestackinstanceoutputtypedef)
  - [DescribeStackResourceDriftsInputRequestTypeDef](#describestackresourcedriftsinputrequesttypedef)
  - [DescribeStackResourceDriftsOutputTypeDef](#describestackresourcedriftsoutputtypedef)
  - [DescribeStackResourceInputRequestTypeDef](#describestackresourceinputrequesttypedef)
  - [DescribeStackResourceOutputTypeDef](#describestackresourceoutputtypedef)
  - [DescribeStackResourcesInputRequestTypeDef](#describestackresourcesinputrequesttypedef)
  - [DescribeStackResourcesOutputTypeDef](#describestackresourcesoutputtypedef)
  - [DescribeStackSetInputRequestTypeDef](#describestacksetinputrequesttypedef)
  - [DescribeStackSetOperationInputRequestTypeDef](#describestacksetoperationinputrequesttypedef)
  - [DescribeStackSetOperationOutputTypeDef](#describestacksetoperationoutputtypedef)
  - [DescribeStackSetOutputTypeDef](#describestacksetoutputtypedef)
  - [DescribeStacksInputRequestTypeDef](#describestacksinputrequesttypedef)
  - [DescribeStacksOutputTypeDef](#describestacksoutputtypedef)
  - [DescribeTypeInputRequestTypeDef](#describetypeinputrequesttypedef)
  - [DescribeTypeOutputTypeDef](#describetypeoutputtypedef)
  - [DescribeTypeRegistrationInputRequestTypeDef](#describetyperegistrationinputrequesttypedef)
  - [DescribeTypeRegistrationOutputTypeDef](#describetyperegistrationoutputtypedef)
  - [DetectStackDriftInputRequestTypeDef](#detectstackdriftinputrequesttypedef)
  - [DetectStackDriftOutputTypeDef](#detectstackdriftoutputtypedef)
  - [DetectStackResourceDriftInputRequestTypeDef](#detectstackresourcedriftinputrequesttypedef)
  - [DetectStackResourceDriftOutputTypeDef](#detectstackresourcedriftoutputtypedef)
  - [DetectStackSetDriftInputRequestTypeDef](#detectstacksetdriftinputrequesttypedef)
  - [DetectStackSetDriftOutputTypeDef](#detectstacksetdriftoutputtypedef)
  - [EstimateTemplateCostInputRequestTypeDef](#estimatetemplatecostinputrequesttypedef)
  - [EstimateTemplateCostOutputTypeDef](#estimatetemplatecostoutputtypedef)
  - [ExecuteChangeSetInputRequestTypeDef](#executechangesetinputrequesttypedef)
  - [ExportTypeDef](#exporttypedef)
  - [GetStackPolicyInputRequestTypeDef](#getstackpolicyinputrequesttypedef)
  - [GetStackPolicyOutputTypeDef](#getstackpolicyoutputtypedef)
  - [GetTemplateInputRequestTypeDef](#gettemplateinputrequesttypedef)
  - [GetTemplateOutputTypeDef](#gettemplateoutputtypedef)
  - [GetTemplateSummaryInputRequestTypeDef](#gettemplatesummaryinputrequesttypedef)
  - [GetTemplateSummaryOutputTypeDef](#gettemplatesummaryoutputtypedef)
  - [ImportStacksToStackSetInputRequestTypeDef](#importstackstostacksetinputrequesttypedef)
  - [ImportStacksToStackSetOutputTypeDef](#importstackstostacksetoutputtypedef)
  - [ListChangeSetsInputRequestTypeDef](#listchangesetsinputrequesttypedef)
  - [ListChangeSetsOutputTypeDef](#listchangesetsoutputtypedef)
  - [ListExportsInputRequestTypeDef](#listexportsinputrequesttypedef)
  - [ListExportsOutputTypeDef](#listexportsoutputtypedef)
  - [ListImportsInputRequestTypeDef](#listimportsinputrequesttypedef)
  - [ListImportsOutputTypeDef](#listimportsoutputtypedef)
  - [ListStackInstancesInputRequestTypeDef](#liststackinstancesinputrequesttypedef)
  - [ListStackInstancesOutputTypeDef](#liststackinstancesoutputtypedef)
  - [ListStackResourcesInputRequestTypeDef](#liststackresourcesinputrequesttypedef)
  - [ListStackResourcesOutputTypeDef](#liststackresourcesoutputtypedef)
  - [ListStackSetOperationResultsInputRequestTypeDef](#liststacksetoperationresultsinputrequesttypedef)
  - [ListStackSetOperationResultsOutputTypeDef](#liststacksetoperationresultsoutputtypedef)
  - [ListStackSetOperationsInputRequestTypeDef](#liststacksetoperationsinputrequesttypedef)
  - [ListStackSetOperationsOutputTypeDef](#liststacksetoperationsoutputtypedef)
  - [ListStackSetsInputRequestTypeDef](#liststacksetsinputrequesttypedef)
  - [ListStackSetsOutputTypeDef](#liststacksetsoutputtypedef)
  - [ListStacksInputRequestTypeDef](#liststacksinputrequesttypedef)
  - [ListStacksOutputTypeDef](#liststacksoutputtypedef)
  - [ListTypeRegistrationsInputRequestTypeDef](#listtyperegistrationsinputrequesttypedef)
  - [ListTypeRegistrationsOutputTypeDef](#listtyperegistrationsoutputtypedef)
  - [ListTypeVersionsInputRequestTypeDef](#listtypeversionsinputrequesttypedef)
  - [ListTypeVersionsOutputTypeDef](#listtypeversionsoutputtypedef)
  - [ListTypesInputRequestTypeDef](#listtypesinputrequesttypedef)
  - [ListTypesOutputTypeDef](#listtypesoutputtypedef)
  - [LoggingConfigTypeDef](#loggingconfigtypedef)
  - [ManagedExecutionTypeDef](#managedexecutiontypedef)
  - [ModuleInfoResponseMetadataTypeDef](#moduleinforesponsemetadatatypedef)
  - [ModuleInfoTypeDef](#moduleinfotypedef)
  - [OutputTypeDef](#outputtypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ParameterConstraintsTypeDef](#parameterconstraintstypedef)
  - [ParameterDeclarationTypeDef](#parameterdeclarationtypedef)
  - [ParameterTypeDef](#parametertypedef)
  - [PhysicalResourceIdContextKeyValuePairTypeDef](#physicalresourceidcontextkeyvaluepairtypedef)
  - [PropertyDifferenceTypeDef](#propertydifferencetypedef)
  - [PublishTypeInputRequestTypeDef](#publishtypeinputrequesttypedef)
  - [PublishTypeOutputTypeDef](#publishtypeoutputtypedef)
  - [RecordHandlerProgressInputRequestTypeDef](#recordhandlerprogressinputrequesttypedef)
  - [RegisterPublisherInputRequestTypeDef](#registerpublisherinputrequesttypedef)
  - [RegisterPublisherOutputTypeDef](#registerpublisheroutputtypedef)
  - [RegisterTypeInputRequestTypeDef](#registertypeinputrequesttypedef)
  - [RegisterTypeOutputTypeDef](#registertypeoutputtypedef)
  - [RequiredActivatedTypeTypeDef](#requiredactivatedtypetypedef)
  - [ResourceChangeDetailTypeDef](#resourcechangedetailtypedef)
  - [ResourceChangeTypeDef](#resourcechangetypedef)
  - [ResourceIdentifierSummaryTypeDef](#resourceidentifiersummarytypedef)
  - [ResourceTargetDefinitionTypeDef](#resourcetargetdefinitiontypedef)
  - [ResourceToImportTypeDef](#resourcetoimporttypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RollbackConfigurationResponseMetadataTypeDef](#rollbackconfigurationresponsemetadatatypedef)
  - [RollbackConfigurationTypeDef](#rollbackconfigurationtypedef)
  - [RollbackStackInputRequestTypeDef](#rollbackstackinputrequesttypedef)
  - [RollbackStackOutputTypeDef](#rollbackstackoutputtypedef)
  - [RollbackTriggerTypeDef](#rollbacktriggertypedef)
  - [ServiceResourceEventRequestTypeDef](#serviceresourceeventrequesttypedef)
  - [ServiceResourceStackRequestTypeDef](#serviceresourcestackrequesttypedef)
  - [ServiceResourceStackResourceRequestTypeDef](#serviceresourcestackresourcerequesttypedef)
  - [ServiceResourceStackResourceSummaryRequestTypeDef](#serviceresourcestackresourcesummaryrequesttypedef)
  - [SetStackPolicyInputRequestTypeDef](#setstackpolicyinputrequesttypedef)
  - [SetTypeConfigurationInputRequestTypeDef](#settypeconfigurationinputrequesttypedef)
  - [SetTypeConfigurationOutputTypeDef](#settypeconfigurationoutputtypedef)
  - [SetTypeDefaultVersionInputRequestTypeDef](#settypedefaultversioninputrequesttypedef)
  - [SignalResourceInputRequestTypeDef](#signalresourceinputrequesttypedef)
  - [StackDriftInformationResponseMetadataTypeDef](#stackdriftinformationresponsemetadatatypedef)
  - [StackDriftInformationSummaryTypeDef](#stackdriftinformationsummarytypedef)
  - [StackDriftInformationTypeDef](#stackdriftinformationtypedef)
  - [StackEventTypeDef](#stackeventtypedef)
  - [StackInstanceComprehensiveStatusTypeDef](#stackinstancecomprehensivestatustypedef)
  - [StackInstanceFilterTypeDef](#stackinstancefiltertypedef)
  - [StackInstanceSummaryTypeDef](#stackinstancesummarytypedef)
  - [StackInstanceTypeDef](#stackinstancetypedef)
  - [StackResourceDetailTypeDef](#stackresourcedetailtypedef)
  - [StackResourceDriftInformationResponseMetadataTypeDef](#stackresourcedriftinformationresponsemetadatatypedef)
  - [StackResourceDriftInformationSummaryResponseMetadataTypeDef](#stackresourcedriftinformationsummaryresponsemetadatatypedef)
  - [StackResourceDriftInformationSummaryTypeDef](#stackresourcedriftinformationsummarytypedef)
  - [StackResourceDriftInformationTypeDef](#stackresourcedriftinformationtypedef)
  - [StackResourceDriftTypeDef](#stackresourcedrifttypedef)
  - [StackResourceRequestTypeDef](#stackresourcerequesttypedef)
  - [StackResourceSummaryTypeDef](#stackresourcesummarytypedef)
  - [StackResourceTypeDef](#stackresourcetypedef)
  - [StackSetDriftDetectionDetailsTypeDef](#stacksetdriftdetectiondetailstypedef)
  - [StackSetOperationPreferencesTypeDef](#stacksetoperationpreferencestypedef)
  - [StackSetOperationResultSummaryTypeDef](#stacksetoperationresultsummarytypedef)
  - [StackSetOperationSummaryTypeDef](#stacksetoperationsummarytypedef)
  - [StackSetOperationTypeDef](#stacksetoperationtypedef)
  - [StackSetSummaryTypeDef](#stacksetsummarytypedef)
  - [StackSetTypeDef](#stacksettypedef)
  - [StackSummaryTypeDef](#stacksummarytypedef)
  - [StackTypeDef](#stacktypedef)
  - [StopStackSetOperationInputRequestTypeDef](#stopstacksetoperationinputrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TemplateParameterTypeDef](#templateparametertypedef)
  - [TestTypeInputRequestTypeDef](#testtypeinputrequesttypedef)
  - [TestTypeOutputTypeDef](#testtypeoutputtypedef)
  - [TypeConfigurationDetailsTypeDef](#typeconfigurationdetailstypedef)
  - [TypeConfigurationIdentifierTypeDef](#typeconfigurationidentifiertypedef)
  - [TypeFiltersTypeDef](#typefilterstypedef)
  - [TypeSummaryTypeDef](#typesummarytypedef)
  - [TypeVersionSummaryTypeDef](#typeversionsummarytypedef)
  - [UpdateStackInputRequestTypeDef](#updatestackinputrequesttypedef)
  - [UpdateStackInputStackTypeDef](#updatestackinputstacktypedef)
  - [UpdateStackInstancesInputRequestTypeDef](#updatestackinstancesinputrequesttypedef)
  - [UpdateStackInstancesOutputTypeDef](#updatestackinstancesoutputtypedef)
  - [UpdateStackOutputTypeDef](#updatestackoutputtypedef)
  - [UpdateStackSetInputRequestTypeDef](#updatestacksetinputrequesttypedef)
  - [UpdateStackSetOutputTypeDef](#updatestacksetoutputtypedef)
  - [UpdateTerminationProtectionInputRequestTypeDef](#updateterminationprotectioninputrequesttypedef)
  - [UpdateTerminationProtectionOutputTypeDef](#updateterminationprotectionoutputtypedef)
  - [ValidateTemplateInputRequestTypeDef](#validatetemplateinputrequesttypedef)
  - [ValidateTemplateOutputTypeDef](#validatetemplateoutputtypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)

<a id="accountgateresulttypedef"></a>

## AccountGateResultTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import AccountGateResultTypeDef
```

Optional fields:

- `Status`: [AccountGateStatusType](./literals.md#accountgatestatustype)
- `StatusReason`: `str`

<a id="accountlimittypedef"></a>

## AccountLimitTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import AccountLimitTypeDef
```

Optional fields:

- `Name`: `str`
- `Value`: `int`

<a id="activatetypeinputrequesttypedef"></a>

## ActivateTypeInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ActivateTypeInputRequestTypeDef
```

Optional fields:

- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `PublicTypeArn`: `str`
- `PublisherId`: `str`
- `TypeName`: `str`
- `TypeNameAlias`: `str`
- `AutoUpdate`: `bool`
- `LoggingConfig`: [LoggingConfigTypeDef](./type_defs.md#loggingconfigtypedef)
- `ExecutionRoleArn`: `str`
- `VersionBump`: [VersionBumpType](./literals.md#versionbumptype)
- `MajorVersion`: `int`

<a id="activatetypeoutputtypedef"></a>

## ActivateTypeOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ActivateTypeOutputTypeDef
```

Required fields:

- `Arn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="autodeploymenttypedef"></a>

## AutoDeploymentTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import AutoDeploymentTypeDef
```

Optional fields:

- `Enabled`: `bool`
- `RetainStacksOnAccountRemoval`: `bool`

<a id="batchdescribetypeconfigurationserrortypedef"></a>

## BatchDescribeTypeConfigurationsErrorTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import BatchDescribeTypeConfigurationsErrorTypeDef
```

Optional fields:

- `ErrorCode`: `str`
- `ErrorMessage`: `str`
- `TypeConfigurationIdentifier`:
  [TypeConfigurationIdentifierTypeDef](./type_defs.md#typeconfigurationidentifiertypedef)

<a id="batchdescribetypeconfigurationsinputrequesttypedef"></a>

## BatchDescribeTypeConfigurationsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import BatchDescribeTypeConfigurationsInputRequestTypeDef
```

Required fields:

- `TypeConfigurationIdentifiers`:
  `Sequence`\[[TypeConfigurationIdentifierTypeDef](./type_defs.md#typeconfigurationidentifiertypedef)\]

<a id="batchdescribetypeconfigurationsoutputtypedef"></a>

## BatchDescribeTypeConfigurationsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import BatchDescribeTypeConfigurationsOutputTypeDef
```

Required fields:

- `Errors`:
  `List`\[[BatchDescribeTypeConfigurationsErrorTypeDef](./type_defs.md#batchdescribetypeconfigurationserrortypedef)\]
- `UnprocessedTypeConfigurations`:
  `List`\[[TypeConfigurationIdentifierTypeDef](./type_defs.md#typeconfigurationidentifiertypedef)\]
- `TypeConfigurations`:
  `List`\[[TypeConfigurationDetailsTypeDef](./type_defs.md#typeconfigurationdetailstypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="cancelupdatestackinputrequesttypedef"></a>

## CancelUpdateStackInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CancelUpdateStackInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `ClientRequestToken`: `str`

<a id="cancelupdatestackinputstacktypedef"></a>

## CancelUpdateStackInputStackTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CancelUpdateStackInputStackTypeDef
```

Optional fields:

- `ClientRequestToken`: `str`

<a id="changesetsummarytypedef"></a>

## ChangeSetSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ChangeSetSummaryTypeDef
```

Optional fields:

- `StackId`: `str`
- `StackName`: `str`
- `ChangeSetId`: `str`
- `ChangeSetName`: `str`
- `ExecutionStatus`: [ExecutionStatusType](./literals.md#executionstatustype)
- `Status`: [ChangeSetStatusType](./literals.md#changesetstatustype)
- `StatusReason`: `str`
- `CreationTime`: `datetime`
- `Description`: `str`
- `IncludeNestedStacks`: `bool`
- `ParentChangeSetId`: `str`
- `RootChangeSetId`: `str`

<a id="changetypedef"></a>

## ChangeTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ChangeTypeDef
```

Optional fields:

- `Type`: `Literal['Resource']` (see
  [ChangeTypeType](./literals.md#changetypetype))
- `ResourceChange`:
  [ResourceChangeTypeDef](./type_defs.md#resourcechangetypedef)

<a id="continueupdaterollbackinputrequesttypedef"></a>

## ContinueUpdateRollbackInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ContinueUpdateRollbackInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `RoleARN`: `str`
- `ResourcesToSkip`: `Sequence`\[`str`\]
- `ClientRequestToken`: `str`

<a id="createchangesetinputrequesttypedef"></a>

## CreateChangeSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateChangeSetInputRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `ChangeSetName`: `str`

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `UsePreviousTemplate`: `bool`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `NotificationARNs`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`
- `Description`: `str`
- `ChangeSetType`: [ChangeSetTypeType](./literals.md#changesettypetype)
- `ResourcesToImport`:
  `Sequence`\[[ResourceToImportTypeDef](./type_defs.md#resourcetoimporttypedef)\]
- `IncludeNestedStacks`: `bool`

<a id="createchangesetoutputtypedef"></a>

## CreateChangeSetOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateChangeSetOutputTypeDef
```

Required fields:

- `Id`: `str`
- `StackId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createstackinputrequesttypedef"></a>

## CreateStackInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateStackInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `DisableRollback`: `bool`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `TimeoutInMinutes`: `int`
- `NotificationARNs`: `Sequence`\[`str`\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `OnFailure`: [OnFailureType](./literals.md#onfailuretype)
- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientRequestToken`: `str`
- `EnableTerminationProtection`: `bool`

<a id="createstackinputserviceresourcetypedef"></a>

## CreateStackInputServiceResourceTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateStackInputServiceResourceTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `DisableRollback`: `bool`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `TimeoutInMinutes`: `int`
- `NotificationARNs`: `Sequence`\[`str`\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `OnFailure`: [OnFailureType](./literals.md#onfailuretype)
- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientRequestToken`: `str`
- `EnableTerminationProtection`: `bool`

<a id="createstackinstancesinputrequesttypedef"></a>

## CreateStackInstancesInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateStackInstancesInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`
- `Regions`: `Sequence`\[`str`\]

Optional fields:

- `Accounts`: `Sequence`\[`str`\]
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `ParameterOverrides`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="createstackinstancesoutputtypedef"></a>

## CreateStackInstancesOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateStackInstancesOutputTypeDef
```

Required fields:

- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createstackoutputtypedef"></a>

## CreateStackOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateStackOutputTypeDef
```

Required fields:

- `StackId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createstacksetinputrequesttypedef"></a>

## CreateStackSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateStackSetInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `Description`: `str`
- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `StackId`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `AdministrationRoleARN`: `str`
- `ExecutionRoleName`: `str`
- `PermissionModel`: [PermissionModelsType](./literals.md#permissionmodelstype)
- `AutoDeployment`:
  [AutoDeploymentTypeDef](./type_defs.md#autodeploymenttypedef)
- `CallAs`: [CallAsType](./literals.md#callastype)
- `ClientRequestToken`: `str`
- `ManagedExecution`:
  [ManagedExecutionTypeDef](./type_defs.md#managedexecutiontypedef)

<a id="createstacksetoutputtypedef"></a>

## CreateStackSetOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import CreateStackSetOutputTypeDef
```

Required fields:

- `StackSetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deactivatetypeinputrequesttypedef"></a>

## DeactivateTypeInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeactivateTypeInputRequestTypeDef
```

Optional fields:

- `TypeName`: `str`
- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `Arn`: `str`

<a id="deletechangesetinputrequesttypedef"></a>

## DeleteChangeSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeleteChangeSetInputRequestTypeDef
```

Required fields:

- `ChangeSetName`: `str`

Optional fields:

- `StackName`: `str`

<a id="deletestackinputrequesttypedef"></a>

## DeleteStackInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeleteStackInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `RetainResources`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `ClientRequestToken`: `str`

<a id="deletestackinputstacktypedef"></a>

## DeleteStackInputStackTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeleteStackInputStackTypeDef
```

Optional fields:

- `RetainResources`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `ClientRequestToken`: `str`

<a id="deletestackinstancesinputrequesttypedef"></a>

## DeleteStackInstancesInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeleteStackInstancesInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`
- `Regions`: `Sequence`\[`str`\]
- `RetainStacks`: `bool`

Optional fields:

- `Accounts`: `Sequence`\[`str`\]
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="deletestackinstancesoutputtypedef"></a>

## DeleteStackInstancesOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeleteStackInstancesOutputTypeDef
```

Required fields:

- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletestacksetinputrequesttypedef"></a>

## DeleteStackSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeleteStackSetInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="deploymenttargetstypedef"></a>

## DeploymentTargetsTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeploymentTargetsTypeDef
```

Optional fields:

- `Accounts`: `Sequence`\[`str`\]
- `AccountsUrl`: `str`
- `OrganizationalUnitIds`: `Sequence`\[`str`\]

<a id="deregistertypeinputrequesttypedef"></a>

## DeregisterTypeInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DeregisterTypeInputRequestTypeDef
```

Optional fields:

- `Arn`: `str`
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `VersionId`: `str`

<a id="describeaccountlimitsinputrequesttypedef"></a>

## DescribeAccountLimitsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeAccountLimitsInputRequestTypeDef
```

Optional fields:

- `NextToken`: `str`

<a id="describeaccountlimitsoutputtypedef"></a>

## DescribeAccountLimitsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeAccountLimitsOutputTypeDef
```

Required fields:

- `AccountLimits`:
  `List`\[[AccountLimitTypeDef](./type_defs.md#accountlimittypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describechangesetinputrequesttypedef"></a>

## DescribeChangeSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeChangeSetInputRequestTypeDef
```

Required fields:

- `ChangeSetName`: `str`

Optional fields:

- `StackName`: `str`
- `NextToken`: `str`

<a id="describechangesetoutputtypedef"></a>

## DescribeChangeSetOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeChangeSetOutputTypeDef
```

Required fields:

- `ChangeSetName`: `str`
- `ChangeSetId`: `str`
- `StackId`: `str`
- `StackName`: `str`
- `Description`: `str`
- `Parameters`: `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `CreationTime`: `datetime`
- `ExecutionStatus`: [ExecutionStatusType](./literals.md#executionstatustype)
- `Status`: [ChangeSetStatusType](./literals.md#changesetstatustype)
- `StatusReason`: `str`
- `NotificationARNs`: `List`\[`str`\]
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `Capabilities`: `List`\[[CapabilityType](./literals.md#capabilitytype)\]
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `Changes`: `List`\[[ChangeTypeDef](./type_defs.md#changetypedef)\]
- `NextToken`: `str`
- `IncludeNestedStacks`: `bool`
- `ParentChangeSetId`: `str`
- `RootChangeSetId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describepublisherinputrequesttypedef"></a>

## DescribePublisherInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribePublisherInputRequestTypeDef
```

Optional fields:

- `PublisherId`: `str`

<a id="describepublisheroutputtypedef"></a>

## DescribePublisherOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribePublisherOutputTypeDef
```

Required fields:

- `PublisherId`: `str`
- `PublisherStatus`: [PublisherStatusType](./literals.md#publisherstatustype)
- `IdentityProvider`:
  [IdentityProviderType](./literals.md#identityprovidertype)
- `PublisherProfile`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestackdriftdetectionstatusinputrequesttypedef"></a>

## DescribeStackDriftDetectionStatusInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackDriftDetectionStatusInputRequestTypeDef
```

Required fields:

- `StackDriftDetectionId`: `str`

<a id="describestackdriftdetectionstatusoutputtypedef"></a>

## DescribeStackDriftDetectionStatusOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackDriftDetectionStatusOutputTypeDef
```

Required fields:

- `StackId`: `str`
- `StackDriftDetectionId`: `str`
- `StackDriftStatus`:
  [StackDriftStatusType](./literals.md#stackdriftstatustype)
- `DetectionStatus`:
  [StackDriftDetectionStatusType](./literals.md#stackdriftdetectionstatustype)
- `DetectionStatusReason`: `str`
- `DriftedStackResourceCount`: `int`
- `Timestamp`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestackeventsinputrequesttypedef"></a>

## DescribeStackEventsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackEventsInputRequestTypeDef
```

Optional fields:

- `StackName`: `str`
- `NextToken`: `str`

<a id="describestackeventsoutputtypedef"></a>

## DescribeStackEventsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackEventsOutputTypeDef
```

Required fields:

- `StackEvents`:
  `List`\[[StackEventTypeDef](./type_defs.md#stackeventtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestackinstanceinputrequesttypedef"></a>

## DescribeStackInstanceInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackInstanceInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`
- `StackInstanceAccount`: `str`
- `StackInstanceRegion`: `str`

Optional fields:

- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="describestackinstanceoutputtypedef"></a>

## DescribeStackInstanceOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackInstanceOutputTypeDef
```

Required fields:

- `StackInstance`: [StackInstanceTypeDef](./type_defs.md#stackinstancetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestackresourcedriftsinputrequesttypedef"></a>

## DescribeStackResourceDriftsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackResourceDriftsInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `StackResourceDriftStatusFilters`:
  `Sequence`\[[StackResourceDriftStatusType](./literals.md#stackresourcedriftstatustype)\]
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="describestackresourcedriftsoutputtypedef"></a>

## DescribeStackResourceDriftsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackResourceDriftsOutputTypeDef
```

Required fields:

- `StackResourceDrifts`:
  `List`\[[StackResourceDriftTypeDef](./type_defs.md#stackresourcedrifttypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestackresourceinputrequesttypedef"></a>

## DescribeStackResourceInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackResourceInputRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `LogicalResourceId`: `str`

<a id="describestackresourceoutputtypedef"></a>

## DescribeStackResourceOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackResourceOutputTypeDef
```

Required fields:

- `StackResourceDetail`:
  [StackResourceDetailTypeDef](./type_defs.md#stackresourcedetailtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestackresourcesinputrequesttypedef"></a>

## DescribeStackResourcesInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackResourcesInputRequestTypeDef
```

Optional fields:

- `StackName`: `str`
- `LogicalResourceId`: `str`
- `PhysicalResourceId`: `str`

<a id="describestackresourcesoutputtypedef"></a>

## DescribeStackResourcesOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackResourcesOutputTypeDef
```

Required fields:

- `StackResources`:
  `List`\[[StackResourceTypeDef](./type_defs.md#stackresourcetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestacksetinputrequesttypedef"></a>

## DescribeStackSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackSetInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="describestacksetoperationinputrequesttypedef"></a>

## DescribeStackSetOperationInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackSetOperationInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`
- `OperationId`: `str`

Optional fields:

- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="describestacksetoperationoutputtypedef"></a>

## DescribeStackSetOperationOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackSetOperationOutputTypeDef
```

Required fields:

- `StackSetOperation`:
  [StackSetOperationTypeDef](./type_defs.md#stacksetoperationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestacksetoutputtypedef"></a>

## DescribeStackSetOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStackSetOutputTypeDef
```

Required fields:

- `StackSet`: [StackSetTypeDef](./type_defs.md#stacksettypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestacksinputrequesttypedef"></a>

## DescribeStacksInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStacksInputRequestTypeDef
```

Optional fields:

- `StackName`: `str`
- `NextToken`: `str`

<a id="describestacksoutputtypedef"></a>

## DescribeStacksOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeStacksOutputTypeDef
```

Required fields:

- `Stacks`: `List`\[[StackTypeDef](./type_defs.md#stacktypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetypeinputrequesttypedef"></a>

## DescribeTypeInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeTypeInputRequestTypeDef
```

Optional fields:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `Arn`: `str`
- `VersionId`: `str`
- `PublisherId`: `str`
- `PublicVersionNumber`: `str`

<a id="describetypeoutputtypedef"></a>

## DescribeTypeOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeTypeOutputTypeDef
```

Required fields:

- `Arn`: `str`
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `DefaultVersionId`: `str`
- `IsDefaultVersion`: `bool`
- `TypeTestsStatus`: [TypeTestsStatusType](./literals.md#typetestsstatustype)
- `TypeTestsStatusDescription`: `str`
- `Description`: `str`
- `Schema`: `str`
- `ProvisioningType`:
  [ProvisioningTypeType](./literals.md#provisioningtypetype)
- `DeprecatedStatus`:
  [DeprecatedStatusType](./literals.md#deprecatedstatustype)
- `LoggingConfig`: [LoggingConfigTypeDef](./type_defs.md#loggingconfigtypedef)
- `RequiredActivatedTypes`:
  `List`\[[RequiredActivatedTypeTypeDef](./type_defs.md#requiredactivatedtypetypedef)\]
- `ExecutionRoleArn`: `str`
- `Visibility`: [VisibilityType](./literals.md#visibilitytype)
- `SourceUrl`: `str`
- `DocumentationUrl`: `str`
- `LastUpdated`: `datetime`
- `TimeCreated`: `datetime`
- `ConfigurationSchema`: `str`
- `PublisherId`: `str`
- `OriginalTypeName`: `str`
- `OriginalTypeArn`: `str`
- `PublicVersionNumber`: `str`
- `LatestPublicVersion`: `str`
- `IsActivated`: `bool`
- `AutoUpdate`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetyperegistrationinputrequesttypedef"></a>

## DescribeTypeRegistrationInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeTypeRegistrationInputRequestTypeDef
```

Required fields:

- `RegistrationToken`: `str`

<a id="describetyperegistrationoutputtypedef"></a>

## DescribeTypeRegistrationOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DescribeTypeRegistrationOutputTypeDef
```

Required fields:

- `ProgressStatus`:
  [RegistrationStatusType](./literals.md#registrationstatustype)
- `Description`: `str`
- `TypeArn`: `str`
- `TypeVersionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="detectstackdriftinputrequesttypedef"></a>

## DetectStackDriftInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DetectStackDriftInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `LogicalResourceIds`: `Sequence`\[`str`\]

<a id="detectstackdriftoutputtypedef"></a>

## DetectStackDriftOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DetectStackDriftOutputTypeDef
```

Required fields:

- `StackDriftDetectionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="detectstackresourcedriftinputrequesttypedef"></a>

## DetectStackResourceDriftInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DetectStackResourceDriftInputRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `LogicalResourceId`: `str`

<a id="detectstackresourcedriftoutputtypedef"></a>

## DetectStackResourceDriftOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DetectStackResourceDriftOutputTypeDef
```

Required fields:

- `StackResourceDrift`:
  [StackResourceDriftTypeDef](./type_defs.md#stackresourcedrifttypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="detectstacksetdriftinputrequesttypedef"></a>

## DetectStackSetDriftInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DetectStackSetDriftInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="detectstacksetdriftoutputtypedef"></a>

## DetectStackSetDriftOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import DetectStackSetDriftOutputTypeDef
```

Required fields:

- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="estimatetemplatecostinputrequesttypedef"></a>

## EstimateTemplateCostInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import EstimateTemplateCostInputRequestTypeDef
```

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

<a id="estimatetemplatecostoutputtypedef"></a>

## EstimateTemplateCostOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import EstimateTemplateCostOutputTypeDef
```

Required fields:

- `Url`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="executechangesetinputrequesttypedef"></a>

## ExecuteChangeSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ExecuteChangeSetInputRequestTypeDef
```

Required fields:

- `ChangeSetName`: `str`

Optional fields:

- `StackName`: `str`
- `ClientRequestToken`: `str`
- `DisableRollback`: `bool`

<a id="exporttypedef"></a>

## ExportTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ExportTypeDef
```

Optional fields:

- `ExportingStackId`: `str`
- `Name`: `str`
- `Value`: `str`

<a id="getstackpolicyinputrequesttypedef"></a>

## GetStackPolicyInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import GetStackPolicyInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

<a id="getstackpolicyoutputtypedef"></a>

## GetStackPolicyOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import GetStackPolicyOutputTypeDef
```

Required fields:

- `StackPolicyBody`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="gettemplateinputrequesttypedef"></a>

## GetTemplateInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import GetTemplateInputRequestTypeDef
```

Optional fields:

- `StackName`: `str`
- `ChangeSetName`: `str`
- `TemplateStage`: [TemplateStageType](./literals.md#templatestagetype)

<a id="gettemplateoutputtypedef"></a>

## GetTemplateOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import GetTemplateOutputTypeDef
```

Required fields:

- `TemplateBody`: `str`
- `StagesAvailable`:
  `List`\[[TemplateStageType](./literals.md#templatestagetype)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="gettemplatesummaryinputrequesttypedef"></a>

## GetTemplateSummaryInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import GetTemplateSummaryInputRequestTypeDef
```

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `StackName`: `str`
- `StackSetName`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="gettemplatesummaryoutputtypedef"></a>

## GetTemplateSummaryOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import GetTemplateSummaryOutputTypeDef
```

Required fields:

- `Parameters`:
  `List`\[[ParameterDeclarationTypeDef](./type_defs.md#parameterdeclarationtypedef)\]
- `Description`: `str`
- `Capabilities`: `List`\[[CapabilityType](./literals.md#capabilitytype)\]
- `CapabilitiesReason`: `str`
- `ResourceTypes`: `List`\[`str`\]
- `Version`: `str`
- `Metadata`: `str`
- `DeclaredTransforms`: `List`\[`str`\]
- `ResourceIdentifierSummaries`:
  `List`\[[ResourceIdentifierSummaryTypeDef](./type_defs.md#resourceidentifiersummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="importstackstostacksetinputrequesttypedef"></a>

## ImportStacksToStackSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ImportStacksToStackSetInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `StackIds`: `Sequence`\[`str`\]
- `StackIdsUrl`: `str`
- `OrganizationalUnitIds`: `Sequence`\[`str`\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="importstackstostacksetoutputtypedef"></a>

## ImportStacksToStackSetOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ImportStacksToStackSetOutputTypeDef
```

Required fields:

- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listchangesetsinputrequesttypedef"></a>

## ListChangeSetsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListChangeSetsInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `NextToken`: `str`

<a id="listchangesetsoutputtypedef"></a>

## ListChangeSetsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListChangeSetsOutputTypeDef
```

Required fields:

- `Summaries`:
  `List`\[[ChangeSetSummaryTypeDef](./type_defs.md#changesetsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listexportsinputrequesttypedef"></a>

## ListExportsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListExportsInputRequestTypeDef
```

Optional fields:

- `NextToken`: `str`

<a id="listexportsoutputtypedef"></a>

## ListExportsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListExportsOutputTypeDef
```

Required fields:

- `Exports`: `List`\[[ExportTypeDef](./type_defs.md#exporttypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listimportsinputrequesttypedef"></a>

## ListImportsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListImportsInputRequestTypeDef
```

Required fields:

- `ExportName`: `str`

Optional fields:

- `NextToken`: `str`

<a id="listimportsoutputtypedef"></a>

## ListImportsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListImportsOutputTypeDef
```

Required fields:

- `Imports`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststackinstancesinputrequesttypedef"></a>

## ListStackInstancesInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackInstancesInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`:
  `Sequence`\[[StackInstanceFilterTypeDef](./type_defs.md#stackinstancefiltertypedef)\]
- `StackInstanceAccount`: `str`
- `StackInstanceRegion`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="liststackinstancesoutputtypedef"></a>

## ListStackInstancesOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackInstancesOutputTypeDef
```

Required fields:

- `Summaries`:
  `List`\[[StackInstanceSummaryTypeDef](./type_defs.md#stackinstancesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststackresourcesinputrequesttypedef"></a>

## ListStackResourcesInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackResourcesInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `NextToken`: `str`

<a id="liststackresourcesoutputtypedef"></a>

## ListStackResourcesOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackResourcesOutputTypeDef
```

Required fields:

- `StackResourceSummaries`:
  `List`\[[StackResourceSummaryTypeDef](./type_defs.md#stackresourcesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststacksetoperationresultsinputrequesttypedef"></a>

## ListStackSetOperationResultsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackSetOperationResultsInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`
- `OperationId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="liststacksetoperationresultsoutputtypedef"></a>

## ListStackSetOperationResultsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackSetOperationResultsOutputTypeDef
```

Required fields:

- `Summaries`:
  `List`\[[StackSetOperationResultSummaryTypeDef](./type_defs.md#stacksetoperationresultsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststacksetoperationsinputrequesttypedef"></a>

## ListStackSetOperationsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackSetOperationsInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="liststacksetoperationsoutputtypedef"></a>

## ListStackSetOperationsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackSetOperationsOutputTypeDef
```

Required fields:

- `Summaries`:
  `List`\[[StackSetOperationSummaryTypeDef](./type_defs.md#stacksetoperationsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststacksetsinputrequesttypedef"></a>

## ListStackSetsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackSetsInputRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Status`: [StackSetStatusType](./literals.md#stacksetstatustype)
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="liststacksetsoutputtypedef"></a>

## ListStackSetsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStackSetsOutputTypeDef
```

Required fields:

- `Summaries`:
  `List`\[[StackSetSummaryTypeDef](./type_defs.md#stacksetsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststacksinputrequesttypedef"></a>

## ListStacksInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStacksInputRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `StackStatusFilter`:
  `Sequence`\[[StackStatusType](./literals.md#stackstatustype)\]

<a id="liststacksoutputtypedef"></a>

## ListStacksOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListStacksOutputTypeDef
```

Required fields:

- `StackSummaries`:
  `List`\[[StackSummaryTypeDef](./type_defs.md#stacksummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtyperegistrationsinputrequesttypedef"></a>

## ListTypeRegistrationsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListTypeRegistrationsInputRequestTypeDef
```

Optional fields:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `TypeArn`: `str`
- `RegistrationStatusFilter`:
  [RegistrationStatusType](./literals.md#registrationstatustype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtyperegistrationsoutputtypedef"></a>

## ListTypeRegistrationsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListTypeRegistrationsOutputTypeDef
```

Required fields:

- `RegistrationTokenList`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtypeversionsinputrequesttypedef"></a>

## ListTypeVersionsInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListTypeVersionsInputRequestTypeDef
```

Optional fields:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `Arn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`
- `DeprecatedStatus`:
  [DeprecatedStatusType](./literals.md#deprecatedstatustype)
- `PublisherId`: `str`

<a id="listtypeversionsoutputtypedef"></a>

## ListTypeVersionsOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListTypeVersionsOutputTypeDef
```

Required fields:

- `TypeVersionSummaries`:
  `List`\[[TypeVersionSummaryTypeDef](./type_defs.md#typeversionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtypesinputrequesttypedef"></a>

## ListTypesInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListTypesInputRequestTypeDef
```

Optional fields:

- `Visibility`: [VisibilityType](./literals.md#visibilitytype)
- `ProvisioningType`:
  [ProvisioningTypeType](./literals.md#provisioningtypetype)
- `DeprecatedStatus`:
  [DeprecatedStatusType](./literals.md#deprecatedstatustype)
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `Filters`: [TypeFiltersTypeDef](./type_defs.md#typefilterstypedef)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtypesoutputtypedef"></a>

## ListTypesOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ListTypesOutputTypeDef
```

Required fields:

- `TypeSummaries`:
  `List`\[[TypeSummaryTypeDef](./type_defs.md#typesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="loggingconfigtypedef"></a>

## LoggingConfigTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import LoggingConfigTypeDef
```

Required fields:

- `LogRoleArn`: `str`
- `LogGroupName`: `str`

<a id="managedexecutiontypedef"></a>

## ManagedExecutionTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ManagedExecutionTypeDef
```

Optional fields:

- `Active`: `bool`

<a id="moduleinforesponsemetadatatypedef"></a>

## ModuleInfoResponseMetadataTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ModuleInfoResponseMetadataTypeDef
```

Required fields:

- `TypeHierarchy`: `str`
- `LogicalIdHierarchy`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="moduleinfotypedef"></a>

## ModuleInfoTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ModuleInfoTypeDef
```

Optional fields:

- `TypeHierarchy`: `str`
- `LogicalIdHierarchy`: `str`

<a id="outputtypedef"></a>

## OutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import OutputTypeDef
```

Optional fields:

- `OutputKey`: `str`
- `OutputValue`: `str`
- `Description`: `str`
- `ExportName`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="parameterconstraintstypedef"></a>

## ParameterConstraintsTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ParameterConstraintsTypeDef
```

Optional fields:

- `AllowedValues`: `List`\[`str`\]

<a id="parameterdeclarationtypedef"></a>

## ParameterDeclarationTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ParameterDeclarationTypeDef
```

Optional fields:

- `ParameterKey`: `str`
- `DefaultValue`: `str`
- `ParameterType`: `str`
- `NoEcho`: `bool`
- `Description`: `str`
- `ParameterConstraints`:
  [ParameterConstraintsTypeDef](./type_defs.md#parameterconstraintstypedef)

<a id="parametertypedef"></a>

## ParameterTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ParameterTypeDef
```

Optional fields:

- `ParameterKey`: `str`
- `ParameterValue`: `str`
- `UsePreviousValue`: `bool`
- `ResolvedValue`: `str`

<a id="physicalresourceidcontextkeyvaluepairtypedef"></a>

## PhysicalResourceIdContextKeyValuePairTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import PhysicalResourceIdContextKeyValuePairTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="propertydifferencetypedef"></a>

## PropertyDifferenceTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import PropertyDifferenceTypeDef
```

Required fields:

- `PropertyPath`: `str`
- `ExpectedValue`: `str`
- `ActualValue`: `str`
- `DifferenceType`: [DifferenceTypeType](./literals.md#differencetypetype)

<a id="publishtypeinputrequesttypedef"></a>

## PublishTypeInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import PublishTypeInputRequestTypeDef
```

Optional fields:

- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `Arn`: `str`
- `TypeName`: `str`
- `PublicVersionNumber`: `str`

<a id="publishtypeoutputtypedef"></a>

## PublishTypeOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import PublishTypeOutputTypeDef
```

Required fields:

- `PublicTypeArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="recordhandlerprogressinputrequesttypedef"></a>

## RecordHandlerProgressInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RecordHandlerProgressInputRequestTypeDef
```

Required fields:

- `BearerToken`: `str`
- `OperationStatus`: [OperationStatusType](./literals.md#operationstatustype)

Optional fields:

- `CurrentOperationStatus`:
  [OperationStatusType](./literals.md#operationstatustype)
- `StatusMessage`: `str`
- `ErrorCode`: [HandlerErrorCodeType](./literals.md#handlererrorcodetype)
- `ResourceModel`: `str`
- `ClientRequestToken`: `str`

<a id="registerpublisherinputrequesttypedef"></a>

## RegisterPublisherInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RegisterPublisherInputRequestTypeDef
```

Optional fields:

- `AcceptTermsAndConditions`: `bool`
- `ConnectionArn`: `str`

<a id="registerpublisheroutputtypedef"></a>

## RegisterPublisherOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RegisterPublisherOutputTypeDef
```

Required fields:

- `PublisherId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="registertypeinputrequesttypedef"></a>

## RegisterTypeInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RegisterTypeInputRequestTypeDef
```

Required fields:

- `TypeName`: `str`
- `SchemaHandlerPackage`: `str`

Optional fields:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `LoggingConfig`: [LoggingConfigTypeDef](./type_defs.md#loggingconfigtypedef)
- `ExecutionRoleArn`: `str`
- `ClientRequestToken`: `str`

<a id="registertypeoutputtypedef"></a>

## RegisterTypeOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RegisterTypeOutputTypeDef
```

Required fields:

- `RegistrationToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="requiredactivatedtypetypedef"></a>

## RequiredActivatedTypeTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RequiredActivatedTypeTypeDef
```

Optional fields:

- `TypeNameAlias`: `str`
- `OriginalTypeName`: `str`
- `PublisherId`: `str`
- `SupportedMajorVersions`: `List`\[`int`\]

<a id="resourcechangedetailtypedef"></a>

## ResourceChangeDetailTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ResourceChangeDetailTypeDef
```

Optional fields:

- `Target`:
  [ResourceTargetDefinitionTypeDef](./type_defs.md#resourcetargetdefinitiontypedef)
- `Evaluation`: [EvaluationTypeType](./literals.md#evaluationtypetype)
- `ChangeSource`: [ChangeSourceType](./literals.md#changesourcetype)
- `CausingEntity`: `str`

<a id="resourcechangetypedef"></a>

## ResourceChangeTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ResourceChangeTypeDef
```

Optional fields:

- `Action`: [ChangeActionType](./literals.md#changeactiontype)
- `LogicalResourceId`: `str`
- `PhysicalResourceId`: `str`
- `ResourceType`: `str`
- `Replacement`: [ReplacementType](./literals.md#replacementtype)
- `Scope`:
  `List`\[[ResourceAttributeType](./literals.md#resourceattributetype)\]
- `Details`:
  `List`\[[ResourceChangeDetailTypeDef](./type_defs.md#resourcechangedetailtypedef)\]
- `ChangeSetId`: `str`
- `ModuleInfo`: [ModuleInfoTypeDef](./type_defs.md#moduleinfotypedef)

<a id="resourceidentifiersummarytypedef"></a>

## ResourceIdentifierSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ResourceIdentifierSummaryTypeDef
```

Optional fields:

- `ResourceType`: `str`
- `LogicalResourceIds`: `List`\[`str`\]
- `ResourceIdentifiers`: `List`\[`str`\]

<a id="resourcetargetdefinitiontypedef"></a>

## ResourceTargetDefinitionTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ResourceTargetDefinitionTypeDef
```

Optional fields:

- `Attribute`: [ResourceAttributeType](./literals.md#resourceattributetype)
- `Name`: `str`
- `RequiresRecreation`:
  [RequiresRecreationType](./literals.md#requiresrecreationtype)

<a id="resourcetoimporttypedef"></a>

## ResourceToImportTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ResourceToImportTypeDef
```

Required fields:

- `ResourceType`: `str`
- `LogicalResourceId`: `str`
- `ResourceIdentifier`: `Mapping`\[`str`, `str`\]

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="rollbackconfigurationresponsemetadatatypedef"></a>

## RollbackConfigurationResponseMetadataTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RollbackConfigurationResponseMetadataTypeDef
```

Required fields:

- `RollbackTriggers`:
  `List`\[[RollbackTriggerTypeDef](./type_defs.md#rollbacktriggertypedef)\]
- `MonitoringTimeInMinutes`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="rollbackconfigurationtypedef"></a>

## RollbackConfigurationTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RollbackConfigurationTypeDef
```

Optional fields:

- `RollbackTriggers`:
  `Sequence`\[[RollbackTriggerTypeDef](./type_defs.md#rollbacktriggertypedef)\]
- `MonitoringTimeInMinutes`: `int`

<a id="rollbackstackinputrequesttypedef"></a>

## RollbackStackInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RollbackStackInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `RoleARN`: `str`
- `ClientRequestToken`: `str`

<a id="rollbackstackoutputtypedef"></a>

## RollbackStackOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RollbackStackOutputTypeDef
```

Required fields:

- `StackId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="rollbacktriggertypedef"></a>

## RollbackTriggerTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import RollbackTriggerTypeDef
```

Required fields:

- `Arn`: `str`
- `Type`: `str`

<a id="serviceresourceeventrequesttypedef"></a>

## ServiceResourceEventRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ServiceResourceEventRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="serviceresourcestackrequesttypedef"></a>

## ServiceResourceStackRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ServiceResourceStackRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="serviceresourcestackresourcerequesttypedef"></a>

## ServiceResourceStackResourceRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ServiceResourceStackResourceRequestTypeDef
```

Required fields:

- `stack_name`: `str`
- `logical_id`: `str`

<a id="serviceresourcestackresourcesummaryrequesttypedef"></a>

## ServiceResourceStackResourceSummaryRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ServiceResourceStackResourceSummaryRequestTypeDef
```

Required fields:

- `stack_name`: `str`
- `logical_id`: `str`

<a id="setstackpolicyinputrequesttypedef"></a>

## SetStackPolicyInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import SetStackPolicyInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`

<a id="settypeconfigurationinputrequesttypedef"></a>

## SetTypeConfigurationInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import SetTypeConfigurationInputRequestTypeDef
```

Required fields:

- `Configuration`: `str`

Optional fields:

- `TypeArn`: `str`
- `ConfigurationAlias`: `str`
- `TypeName`: `str`
- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)

<a id="settypeconfigurationoutputtypedef"></a>

## SetTypeConfigurationOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import SetTypeConfigurationOutputTypeDef
```

Required fields:

- `ConfigurationArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="settypedefaultversioninputrequesttypedef"></a>

## SetTypeDefaultVersionInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import SetTypeDefaultVersionInputRequestTypeDef
```

Optional fields:

- `Arn`: `str`
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `VersionId`: `str`

<a id="signalresourceinputrequesttypedef"></a>

## SignalResourceInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import SignalResourceInputRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `LogicalResourceId`: `str`
- `UniqueId`: `str`
- `Status`: [ResourceSignalStatusType](./literals.md#resourcesignalstatustype)

<a id="stackdriftinformationresponsemetadatatypedef"></a>

## StackDriftInformationResponseMetadataTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackDriftInformationResponseMetadataTypeDef
```

Required fields:

- `StackDriftStatus`:
  [StackDriftStatusType](./literals.md#stackdriftstatustype)
- `LastCheckTimestamp`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stackdriftinformationsummarytypedef"></a>

## StackDriftInformationSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackDriftInformationSummaryTypeDef
```

Required fields:

- `StackDriftStatus`:
  [StackDriftStatusType](./literals.md#stackdriftstatustype)

Optional fields:

- `LastCheckTimestamp`: `datetime`

<a id="stackdriftinformationtypedef"></a>

## StackDriftInformationTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackDriftInformationTypeDef
```

Required fields:

- `StackDriftStatus`:
  [StackDriftStatusType](./literals.md#stackdriftstatustype)

Optional fields:

- `LastCheckTimestamp`: `datetime`

<a id="stackeventtypedef"></a>

## StackEventTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackEventTypeDef
```

Required fields:

- `StackId`: `str`
- `EventId`: `str`
- `StackName`: `str`
- `Timestamp`: `datetime`

Optional fields:

- `LogicalResourceId`: `str`
- `PhysicalResourceId`: `str`
- `ResourceType`: `str`
- `ResourceStatus`: [ResourceStatusType](./literals.md#resourcestatustype)
- `ResourceStatusReason`: `str`
- `ResourceProperties`: `str`
- `ClientRequestToken`: `str`

<a id="stackinstancecomprehensivestatustypedef"></a>

## StackInstanceComprehensiveStatusTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackInstanceComprehensiveStatusTypeDef
```

Optional fields:

- `DetailedStatus`:
  [StackInstanceDetailedStatusType](./literals.md#stackinstancedetailedstatustype)

<a id="stackinstancefiltertypedef"></a>

## StackInstanceFilterTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackInstanceFilterTypeDef
```

Optional fields:

- `Name`: `Literal['DETAILED_STATUS']` (see
  [StackInstanceFilterNameType](./literals.md#stackinstancefilternametype))
- `Values`: `str`

<a id="stackinstancesummarytypedef"></a>

## StackInstanceSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackInstanceSummaryTypeDef
```

Optional fields:

- `StackSetId`: `str`
- `Region`: `str`
- `Account`: `str`
- `StackId`: `str`
- `Status`: [StackInstanceStatusType](./literals.md#stackinstancestatustype)
- `StatusReason`: `str`
- `StackInstanceStatus`:
  [StackInstanceComprehensiveStatusTypeDef](./type_defs.md#stackinstancecomprehensivestatustypedef)
- `OrganizationalUnitId`: `str`
- `DriftStatus`: [StackDriftStatusType](./literals.md#stackdriftstatustype)
- `LastDriftCheckTimestamp`: `datetime`

<a id="stackinstancetypedef"></a>

## StackInstanceTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackInstanceTypeDef
```

Optional fields:

- `StackSetId`: `str`
- `Region`: `str`
- `Account`: `str`
- `StackId`: `str`
- `ParameterOverrides`:
  `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Status`: [StackInstanceStatusType](./literals.md#stackinstancestatustype)
- `StackInstanceStatus`:
  [StackInstanceComprehensiveStatusTypeDef](./type_defs.md#stackinstancecomprehensivestatustypedef)
- `StatusReason`: `str`
- `OrganizationalUnitId`: `str`
- `DriftStatus`: [StackDriftStatusType](./literals.md#stackdriftstatustype)
- `LastDriftCheckTimestamp`: `datetime`

<a id="stackresourcedetailtypedef"></a>

## StackResourceDetailTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceDetailTypeDef
```

Required fields:

- `LogicalResourceId`: `str`
- `ResourceType`: `str`
- `LastUpdatedTimestamp`: `datetime`
- `ResourceStatus`: [ResourceStatusType](./literals.md#resourcestatustype)

Optional fields:

- `StackName`: `str`
- `StackId`: `str`
- `PhysicalResourceId`: `str`
- `ResourceStatusReason`: `str`
- `Description`: `str`
- `Metadata`: `str`
- `DriftInformation`:
  [StackResourceDriftInformationTypeDef](./type_defs.md#stackresourcedriftinformationtypedef)
- `ModuleInfo`: [ModuleInfoTypeDef](./type_defs.md#moduleinfotypedef)

<a id="stackresourcedriftinformationresponsemetadatatypedef"></a>

## StackResourceDriftInformationResponseMetadataTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceDriftInformationResponseMetadataTypeDef
```

Required fields:

- `StackResourceDriftStatus`:
  [StackResourceDriftStatusType](./literals.md#stackresourcedriftstatustype)
- `LastCheckTimestamp`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stackresourcedriftinformationsummaryresponsemetadatatypedef"></a>

## StackResourceDriftInformationSummaryResponseMetadataTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceDriftInformationSummaryResponseMetadataTypeDef
```

Required fields:

- `StackResourceDriftStatus`:
  [StackResourceDriftStatusType](./literals.md#stackresourcedriftstatustype)
- `LastCheckTimestamp`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stackresourcedriftinformationsummarytypedef"></a>

## StackResourceDriftInformationSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceDriftInformationSummaryTypeDef
```

Required fields:

- `StackResourceDriftStatus`:
  [StackResourceDriftStatusType](./literals.md#stackresourcedriftstatustype)

Optional fields:

- `LastCheckTimestamp`: `datetime`

<a id="stackresourcedriftinformationtypedef"></a>

## StackResourceDriftInformationTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceDriftInformationTypeDef
```

Required fields:

- `StackResourceDriftStatus`:
  [StackResourceDriftStatusType](./literals.md#stackresourcedriftstatustype)

Optional fields:

- `LastCheckTimestamp`: `datetime`

<a id="stackresourcedrifttypedef"></a>

## StackResourceDriftTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceDriftTypeDef
```

Required fields:

- `StackId`: `str`
- `LogicalResourceId`: `str`
- `ResourceType`: `str`
- `StackResourceDriftStatus`:
  [StackResourceDriftStatusType](./literals.md#stackresourcedriftstatustype)
- `Timestamp`: `datetime`

Optional fields:

- `PhysicalResourceId`: `str`
- `PhysicalResourceIdContext`:
  `List`\[[PhysicalResourceIdContextKeyValuePairTypeDef](./type_defs.md#physicalresourceidcontextkeyvaluepairtypedef)\]
- `ExpectedProperties`: `str`
- `ActualProperties`: `str`
- `PropertyDifferences`:
  `List`\[[PropertyDifferenceTypeDef](./type_defs.md#propertydifferencetypedef)\]
- `ModuleInfo`: [ModuleInfoTypeDef](./type_defs.md#moduleinfotypedef)

<a id="stackresourcerequesttypedef"></a>

## StackResourceRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceRequestTypeDef
```

Required fields:

- `logical_id`: `str`

<a id="stackresourcesummarytypedef"></a>

## StackResourceSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceSummaryTypeDef
```

Required fields:

- `LogicalResourceId`: `str`
- `ResourceType`: `str`
- `LastUpdatedTimestamp`: `datetime`
- `ResourceStatus`: [ResourceStatusType](./literals.md#resourcestatustype)

Optional fields:

- `PhysicalResourceId`: `str`
- `ResourceStatusReason`: `str`
- `DriftInformation`:
  [StackResourceDriftInformationSummaryTypeDef](./type_defs.md#stackresourcedriftinformationsummarytypedef)
- `ModuleInfo`: [ModuleInfoTypeDef](./type_defs.md#moduleinfotypedef)

<a id="stackresourcetypedef"></a>

## StackResourceTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackResourceTypeDef
```

Required fields:

- `LogicalResourceId`: `str`
- `ResourceType`: `str`
- `Timestamp`: `datetime`
- `ResourceStatus`: [ResourceStatusType](./literals.md#resourcestatustype)

Optional fields:

- `StackName`: `str`
- `StackId`: `str`
- `PhysicalResourceId`: `str`
- `ResourceStatusReason`: `str`
- `Description`: `str`
- `DriftInformation`:
  [StackResourceDriftInformationTypeDef](./type_defs.md#stackresourcedriftinformationtypedef)
- `ModuleInfo`: [ModuleInfoTypeDef](./type_defs.md#moduleinfotypedef)

<a id="stacksetdriftdetectiondetailstypedef"></a>

## StackSetDriftDetectionDetailsTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSetDriftDetectionDetailsTypeDef
```

Optional fields:

- `DriftStatus`:
  [StackSetDriftStatusType](./literals.md#stacksetdriftstatustype)
- `DriftDetectionStatus`:
  [StackSetDriftDetectionStatusType](./literals.md#stacksetdriftdetectionstatustype)
- `LastDriftCheckTimestamp`: `datetime`
- `TotalStackInstancesCount`: `int`
- `DriftedStackInstancesCount`: `int`
- `InSyncStackInstancesCount`: `int`
- `InProgressStackInstancesCount`: `int`
- `FailedStackInstancesCount`: `int`

<a id="stacksetoperationpreferencestypedef"></a>

## StackSetOperationPreferencesTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSetOperationPreferencesTypeDef
```

Optional fields:

- `RegionConcurrencyType`:
  [RegionConcurrencyTypeType](./literals.md#regionconcurrencytypetype)
- `RegionOrder`: `Sequence`\[`str`\]
- `FailureToleranceCount`: `int`
- `FailureTolerancePercentage`: `int`
- `MaxConcurrentCount`: `int`
- `MaxConcurrentPercentage`: `int`

<a id="stacksetoperationresultsummarytypedef"></a>

## StackSetOperationResultSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSetOperationResultSummaryTypeDef
```

Optional fields:

- `Account`: `str`
- `Region`: `str`
- `Status`:
  [StackSetOperationResultStatusType](./literals.md#stacksetoperationresultstatustype)
- `StatusReason`: `str`
- `AccountGateResult`:
  [AccountGateResultTypeDef](./type_defs.md#accountgateresulttypedef)
- `OrganizationalUnitId`: `str`

<a id="stacksetoperationsummarytypedef"></a>

## StackSetOperationSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSetOperationSummaryTypeDef
```

Optional fields:

- `OperationId`: `str`
- `Action`:
  [StackSetOperationActionType](./literals.md#stacksetoperationactiontype)
- `Status`:
  [StackSetOperationStatusType](./literals.md#stacksetoperationstatustype)
- `CreationTimestamp`: `datetime`
- `EndTimestamp`: `datetime`

<a id="stacksetoperationtypedef"></a>

## StackSetOperationTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSetOperationTypeDef
```

Optional fields:

- `OperationId`: `str`
- `StackSetId`: `str`
- `Action`:
  [StackSetOperationActionType](./literals.md#stacksetoperationactiontype)
- `Status`:
  [StackSetOperationStatusType](./literals.md#stacksetoperationstatustype)
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `RetainStacks`: `bool`
- `AdministrationRoleARN`: `str`
- `ExecutionRoleName`: `str`
- `CreationTimestamp`: `datetime`
- `EndTimestamp`: `datetime`
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `StackSetDriftDetectionDetails`:
  [StackSetDriftDetectionDetailsTypeDef](./type_defs.md#stacksetdriftdetectiondetailstypedef)

<a id="stacksetsummarytypedef"></a>

## StackSetSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSetSummaryTypeDef
```

Optional fields:

- `StackSetName`: `str`
- `StackSetId`: `str`
- `Description`: `str`
- `Status`: [StackSetStatusType](./literals.md#stacksetstatustype)
- `AutoDeployment`:
  [AutoDeploymentTypeDef](./type_defs.md#autodeploymenttypedef)
- `PermissionModel`: [PermissionModelsType](./literals.md#permissionmodelstype)
- `DriftStatus`: [StackDriftStatusType](./literals.md#stackdriftstatustype)
- `LastDriftCheckTimestamp`: `datetime`
- `ManagedExecution`:
  [ManagedExecutionTypeDef](./type_defs.md#managedexecutiontypedef)

<a id="stacksettypedef"></a>

## StackSetTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSetTypeDef
```

Optional fields:

- `StackSetName`: `str`
- `StackSetId`: `str`
- `Description`: `str`
- `Status`: [StackSetStatusType](./literals.md#stacksetstatustype)
- `TemplateBody`: `str`
- `Parameters`: `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `List`\[[CapabilityType](./literals.md#capabilitytype)\]
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `StackSetARN`: `str`
- `AdministrationRoleARN`: `str`
- `ExecutionRoleName`: `str`
- `StackSetDriftDetectionDetails`:
  [StackSetDriftDetectionDetailsTypeDef](./type_defs.md#stacksetdriftdetectiondetailstypedef)
- `AutoDeployment`:
  [AutoDeploymentTypeDef](./type_defs.md#autodeploymenttypedef)
- `PermissionModel`: [PermissionModelsType](./literals.md#permissionmodelstype)
- `OrganizationalUnitIds`: `List`\[`str`\]
- `ManagedExecution`:
  [ManagedExecutionTypeDef](./type_defs.md#managedexecutiontypedef)

<a id="stacksummarytypedef"></a>

## StackSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackSummaryTypeDef
```

Required fields:

- `StackName`: `str`
- `CreationTime`: `datetime`
- `StackStatus`: [StackStatusType](./literals.md#stackstatustype)

Optional fields:

- `StackId`: `str`
- `TemplateDescription`: `str`
- `LastUpdatedTime`: `datetime`
- `DeletionTime`: `datetime`
- `StackStatusReason`: `str`
- `ParentId`: `str`
- `RootId`: `str`
- `DriftInformation`:
  [StackDriftInformationSummaryTypeDef](./type_defs.md#stackdriftinformationsummarytypedef)

<a id="stacktypedef"></a>

## StackTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StackTypeDef
```

Required fields:

- `StackName`: `str`
- `CreationTime`: `datetime`
- `StackStatus`: [StackStatusType](./literals.md#stackstatustype)

Optional fields:

- `StackId`: `str`
- `ChangeSetId`: `str`
- `Description`: `str`
- `Parameters`: `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `DeletionTime`: `datetime`
- `LastUpdatedTime`: `datetime`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `StackStatusReason`: `str`
- `DisableRollback`: `bool`
- `NotificationARNs`: `List`\[`str`\]
- `TimeoutInMinutes`: `int`
- `Capabilities`: `List`\[[CapabilityType](./literals.md#capabilitytype)\]
- `Outputs`: `List`\[[OutputTypeDef](./type_defs.md#outputtypedef)\]
- `RoleARN`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `EnableTerminationProtection`: `bool`
- `ParentId`: `str`
- `RootId`: `str`
- `DriftInformation`:
  [StackDriftInformationTypeDef](./type_defs.md#stackdriftinformationtypedef)

<a id="stopstacksetoperationinputrequesttypedef"></a>

## StopStackSetOperationInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import StopStackSetOperationInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`
- `OperationId`: `str`

Optional fields:

- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="templateparametertypedef"></a>

## TemplateParameterTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TemplateParameterTypeDef
```

Optional fields:

- `ParameterKey`: `str`
- `DefaultValue`: `str`
- `NoEcho`: `bool`
- `Description`: `str`

<a id="testtypeinputrequesttypedef"></a>

## TestTypeInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TestTypeInputRequestTypeDef
```

Optional fields:

- `Arn`: `str`
- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `TypeName`: `str`
- `VersionId`: `str`
- `LogDeliveryBucket`: `str`

<a id="testtypeoutputtypedef"></a>

## TestTypeOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TestTypeOutputTypeDef
```

Required fields:

- `TypeVersionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="typeconfigurationdetailstypedef"></a>

## TypeConfigurationDetailsTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TypeConfigurationDetailsTypeDef
```

Optional fields:

- `Arn`: `str`
- `Alias`: `str`
- `Configuration`: `str`
- `LastUpdated`: `datetime`
- `TypeArn`: `str`
- `TypeName`: `str`
- `IsDefaultConfiguration`: `bool`

<a id="typeconfigurationidentifiertypedef"></a>

## TypeConfigurationIdentifierTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TypeConfigurationIdentifierTypeDef
```

Optional fields:

- `TypeArn`: `str`
- `TypeConfigurationAlias`: `str`
- `TypeConfigurationArn`: `str`
- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `TypeName`: `str`

<a id="typefilterstypedef"></a>

## TypeFiltersTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TypeFiltersTypeDef
```

Optional fields:

- `Category`: [CategoryType](./literals.md#categorytype)
- `PublisherId`: `str`
- `TypeNamePrefix`: `str`

<a id="typesummarytypedef"></a>

## TypeSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TypeSummaryTypeDef
```

Optional fields:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `DefaultVersionId`: `str`
- `TypeArn`: `str`
- `LastUpdated`: `datetime`
- `Description`: `str`
- `PublisherId`: `str`
- `OriginalTypeName`: `str`
- `PublicVersionNumber`: `str`
- `LatestPublicVersion`: `str`
- `PublisherIdentity`:
  [IdentityProviderType](./literals.md#identityprovidertype)
- `PublisherName`: `str`
- `IsActivated`: `bool`

<a id="typeversionsummarytypedef"></a>

## TypeVersionSummaryTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import TypeVersionSummaryTypeDef
```

Optional fields:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `VersionId`: `str`
- `IsDefaultVersion`: `bool`
- `Arn`: `str`
- `TimeCreated`: `datetime`
- `Description`: `str`
- `PublicVersionNumber`: `str`

<a id="updatestackinputrequesttypedef"></a>

## UpdateStackInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateStackInputRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `UsePreviousTemplate`: `bool`
- `StackPolicyDuringUpdateBody`: `str`
- `StackPolicyDuringUpdateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`
- `NotificationARNs`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `DisableRollback`: `bool`
- `ClientRequestToken`: `str`

<a id="updatestackinputstacktypedef"></a>

## UpdateStackInputStackTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateStackInputStackTypeDef
```

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `UsePreviousTemplate`: `bool`
- `StackPolicyDuringUpdateBody`: `str`
- `StackPolicyDuringUpdateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`
- `NotificationARNs`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `DisableRollback`: `bool`
- `ClientRequestToken`: `str`

<a id="updatestackinstancesinputrequesttypedef"></a>

## UpdateStackInstancesInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateStackInstancesInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`
- `Regions`: `Sequence`\[`str`\]

Optional fields:

- `Accounts`: `Sequence`\[`str`\]
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `ParameterOverrides`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

<a id="updatestackinstancesoutputtypedef"></a>

## UpdateStackInstancesOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateStackInstancesOutputTypeDef
```

Required fields:

- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatestackoutputtypedef"></a>

## UpdateStackOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateStackOutputTypeDef
```

Required fields:

- `StackId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatestacksetinputrequesttypedef"></a>

## UpdateStackSetInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateStackSetInputRequestTypeDef
```

Required fields:

- `StackSetName`: `str`

Optional fields:

- `Description`: `str`
- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `UsePreviousTemplate`: `bool`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `AdministrationRoleARN`: `str`
- `ExecutionRoleName`: `str`
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `PermissionModel`: [PermissionModelsType](./literals.md#permissionmodelstype)
- `AutoDeployment`:
  [AutoDeploymentTypeDef](./type_defs.md#autodeploymenttypedef)
- `OperationId`: `str`
- `Accounts`: `Sequence`\[`str`\]
- `Regions`: `Sequence`\[`str`\]
- `CallAs`: [CallAsType](./literals.md#callastype)
- `ManagedExecution`:
  [ManagedExecutionTypeDef](./type_defs.md#managedexecutiontypedef)

<a id="updatestacksetoutputtypedef"></a>

## UpdateStackSetOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateStackSetOutputTypeDef
```

Required fields:

- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateterminationprotectioninputrequesttypedef"></a>

## UpdateTerminationProtectionInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateTerminationProtectionInputRequestTypeDef
```

Required fields:

- `EnableTerminationProtection`: `bool`
- `StackName`: `str`

<a id="updateterminationprotectionoutputtypedef"></a>

## UpdateTerminationProtectionOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import UpdateTerminationProtectionOutputTypeDef
```

Required fields:

- `StackId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="validatetemplateinputrequesttypedef"></a>

## ValidateTemplateInputRequestTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ValidateTemplateInputRequestTypeDef
```

Optional fields:

- `TemplateBody`: `str`
- `TemplateURL`: `str`

<a id="validatetemplateoutputtypedef"></a>

## ValidateTemplateOutputTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import ValidateTemplateOutputTypeDef
```

Required fields:

- `Parameters`:
  `List`\[[TemplateParameterTypeDef](./type_defs.md#templateparametertypedef)\]
- `Description`: `str`
- `Capabilities`: `List`\[[CapabilityType](./literals.md#capabilitytype)\]
- `CapabilitiesReason`: `str`
- `DeclaredTransforms`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_cloudformation.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`
