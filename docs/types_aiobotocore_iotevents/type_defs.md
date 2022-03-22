<a id="typed-dictionaries-for-aiobotocore-iotevents-module"></a>

# Typed dictionaries for aiobotocore IoTEvents module

> [Index](../README.md) > [IoTEvents](./README.md) > Typed dictionaries

Auto-generated documentation for
[IoTEvents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents)
type annotations stubs module
[types-aiobotocore-iotevents](https://pypi.org/project/types-aiobotocore-iotevents/).

- [Typed dictionaries for aiobotocore IoTEvents module](#typed-dictionaries-for-aiobotocore-iotevents-module)
  - [AcknowledgeFlowTypeDef](#acknowledgeflowtypedef)
  - [ActionTypeDef](#actiontypedef)
  - [AlarmActionTypeDef](#alarmactiontypedef)
  - [AlarmCapabilitiesTypeDef](#alarmcapabilitiestypedef)
  - [AlarmEventActionsTypeDef](#alarmeventactionstypedef)
  - [AlarmModelSummaryTypeDef](#alarmmodelsummarytypedef)
  - [AlarmModelVersionSummaryTypeDef](#alarmmodelversionsummarytypedef)
  - [AlarmNotificationTypeDef](#alarmnotificationtypedef)
  - [AlarmRuleTypeDef](#alarmruletypedef)
  - [AnalysisResultLocationTypeDef](#analysisresultlocationtypedef)
  - [AnalysisResultTypeDef](#analysisresulttypedef)
  - [AssetPropertyTimestampTypeDef](#assetpropertytimestamptypedef)
  - [AssetPropertyValueTypeDef](#assetpropertyvaluetypedef)
  - [AssetPropertyVariantTypeDef](#assetpropertyvarianttypedef)
  - [AttributeTypeDef](#attributetypedef)
  - [ClearTimerActionTypeDef](#cleartimeractiontypedef)
  - [CreateAlarmModelRequestRequestTypeDef](#createalarmmodelrequestrequesttypedef)
  - [CreateAlarmModelResponseTypeDef](#createalarmmodelresponsetypedef)
  - [CreateDetectorModelRequestRequestTypeDef](#createdetectormodelrequestrequesttypedef)
  - [CreateDetectorModelResponseTypeDef](#createdetectormodelresponsetypedef)
  - [CreateInputRequestRequestTypeDef](#createinputrequestrequesttypedef)
  - [CreateInputResponseTypeDef](#createinputresponsetypedef)
  - [DeleteAlarmModelRequestRequestTypeDef](#deletealarmmodelrequestrequesttypedef)
  - [DeleteDetectorModelRequestRequestTypeDef](#deletedetectormodelrequestrequesttypedef)
  - [DeleteInputRequestRequestTypeDef](#deleteinputrequestrequesttypedef)
  - [DescribeAlarmModelRequestRequestTypeDef](#describealarmmodelrequestrequesttypedef)
  - [DescribeAlarmModelResponseTypeDef](#describealarmmodelresponsetypedef)
  - [DescribeDetectorModelAnalysisRequestRequestTypeDef](#describedetectormodelanalysisrequestrequesttypedef)
  - [DescribeDetectorModelAnalysisResponseTypeDef](#describedetectormodelanalysisresponsetypedef)
  - [DescribeDetectorModelRequestRequestTypeDef](#describedetectormodelrequestrequesttypedef)
  - [DescribeDetectorModelResponseTypeDef](#describedetectormodelresponsetypedef)
  - [DescribeInputRequestRequestTypeDef](#describeinputrequestrequesttypedef)
  - [DescribeInputResponseTypeDef](#describeinputresponsetypedef)
  - [DescribeLoggingOptionsResponseTypeDef](#describeloggingoptionsresponsetypedef)
  - [DetectorDebugOptionTypeDef](#detectordebugoptiontypedef)
  - [DetectorModelConfigurationTypeDef](#detectormodelconfigurationtypedef)
  - [DetectorModelDefinitionTypeDef](#detectormodeldefinitiontypedef)
  - [DetectorModelSummaryTypeDef](#detectormodelsummarytypedef)
  - [DetectorModelTypeDef](#detectormodeltypedef)
  - [DetectorModelVersionSummaryTypeDef](#detectormodelversionsummarytypedef)
  - [DynamoDBActionTypeDef](#dynamodbactiontypedef)
  - [DynamoDBv2ActionTypeDef](#dynamodbv2actiontypedef)
  - [EmailConfigurationTypeDef](#emailconfigurationtypedef)
  - [EmailContentTypeDef](#emailcontenttypedef)
  - [EmailRecipientsTypeDef](#emailrecipientstypedef)
  - [EventTypeDef](#eventtypedef)
  - [FirehoseActionTypeDef](#firehoseactiontypedef)
  - [GetDetectorModelAnalysisResultsRequestRequestTypeDef](#getdetectormodelanalysisresultsrequestrequesttypedef)
  - [GetDetectorModelAnalysisResultsResponseTypeDef](#getdetectormodelanalysisresultsresponsetypedef)
  - [InitializationConfigurationTypeDef](#initializationconfigurationtypedef)
  - [InputConfigurationTypeDef](#inputconfigurationtypedef)
  - [InputDefinitionTypeDef](#inputdefinitiontypedef)
  - [InputIdentifierTypeDef](#inputidentifiertypedef)
  - [InputSummaryTypeDef](#inputsummarytypedef)
  - [InputTypeDef](#inputtypedef)
  - [IotEventsActionTypeDef](#ioteventsactiontypedef)
  - [IotEventsInputIdentifierTypeDef](#ioteventsinputidentifiertypedef)
  - [IotSiteWiseActionTypeDef](#iotsitewiseactiontypedef)
  - [IotSiteWiseAssetModelPropertyIdentifierTypeDef](#iotsitewiseassetmodelpropertyidentifiertypedef)
  - [IotSiteWiseInputIdentifierTypeDef](#iotsitewiseinputidentifiertypedef)
  - [IotTopicPublishActionTypeDef](#iottopicpublishactiontypedef)
  - [LambdaActionTypeDef](#lambdaactiontypedef)
  - [ListAlarmModelVersionsRequestRequestTypeDef](#listalarmmodelversionsrequestrequesttypedef)
  - [ListAlarmModelVersionsResponseTypeDef](#listalarmmodelversionsresponsetypedef)
  - [ListAlarmModelsRequestRequestTypeDef](#listalarmmodelsrequestrequesttypedef)
  - [ListAlarmModelsResponseTypeDef](#listalarmmodelsresponsetypedef)
  - [ListDetectorModelVersionsRequestRequestTypeDef](#listdetectormodelversionsrequestrequesttypedef)
  - [ListDetectorModelVersionsResponseTypeDef](#listdetectormodelversionsresponsetypedef)
  - [ListDetectorModelsRequestRequestTypeDef](#listdetectormodelsrequestrequesttypedef)
  - [ListDetectorModelsResponseTypeDef](#listdetectormodelsresponsetypedef)
  - [ListInputRoutingsRequestRequestTypeDef](#listinputroutingsrequestrequesttypedef)
  - [ListInputRoutingsResponseTypeDef](#listinputroutingsresponsetypedef)
  - [ListInputsRequestRequestTypeDef](#listinputsrequestrequesttypedef)
  - [ListInputsResponseTypeDef](#listinputsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [LoggingOptionsTypeDef](#loggingoptionstypedef)
  - [NotificationActionTypeDef](#notificationactiontypedef)
  - [NotificationTargetActionsTypeDef](#notificationtargetactionstypedef)
  - [OnEnterLifecycleTypeDef](#onenterlifecycletypedef)
  - [OnExitLifecycleTypeDef](#onexitlifecycletypedef)
  - [OnInputLifecycleTypeDef](#oninputlifecycletypedef)
  - [PayloadTypeDef](#payloadtypedef)
  - [PutLoggingOptionsRequestRequestTypeDef](#putloggingoptionsrequestrequesttypedef)
  - [RecipientDetailTypeDef](#recipientdetailtypedef)
  - [ResetTimerActionTypeDef](#resettimeractiontypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RoutedResourceTypeDef](#routedresourcetypedef)
  - [SMSConfigurationTypeDef](#smsconfigurationtypedef)
  - [SNSTopicPublishActionTypeDef](#snstopicpublishactiontypedef)
  - [SSOIdentityTypeDef](#ssoidentitytypedef)
  - [SetTimerActionTypeDef](#settimeractiontypedef)
  - [SetVariableActionTypeDef](#setvariableactiontypedef)
  - [SimpleRuleTypeDef](#simpleruletypedef)
  - [SqsActionTypeDef](#sqsactiontypedef)
  - [StartDetectorModelAnalysisRequestRequestTypeDef](#startdetectormodelanalysisrequestrequesttypedef)
  - [StartDetectorModelAnalysisResponseTypeDef](#startdetectormodelanalysisresponsetypedef)
  - [StateTypeDef](#statetypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TransitionEventTypeDef](#transitioneventtypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateAlarmModelRequestRequestTypeDef](#updatealarmmodelrequestrequesttypedef)
  - [UpdateAlarmModelResponseTypeDef](#updatealarmmodelresponsetypedef)
  - [UpdateDetectorModelRequestRequestTypeDef](#updatedetectormodelrequestrequesttypedef)
  - [UpdateDetectorModelResponseTypeDef](#updatedetectormodelresponsetypedef)
  - [UpdateInputRequestRequestTypeDef](#updateinputrequestrequesttypedef)
  - [UpdateInputResponseTypeDef](#updateinputresponsetypedef)

<a id="acknowledgeflowtypedef"></a>

## AcknowledgeFlowTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AcknowledgeFlowTypeDef
```

Required fields:

- `enabled`: `bool`

<a id="actiontypedef"></a>

## ActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ActionTypeDef
```

Optional fields:

- `setVariable`:
  [SetVariableActionTypeDef](./type_defs.md#setvariableactiontypedef)
- `sns`:
  [SNSTopicPublishActionTypeDef](./type_defs.md#snstopicpublishactiontypedef)
- `iotTopicPublish`:
  [IotTopicPublishActionTypeDef](./type_defs.md#iottopicpublishactiontypedef)
- `setTimer`: [SetTimerActionTypeDef](./type_defs.md#settimeractiontypedef)
- `clearTimer`:
  [ClearTimerActionTypeDef](./type_defs.md#cleartimeractiontypedef)
- `resetTimer`:
  [ResetTimerActionTypeDef](./type_defs.md#resettimeractiontypedef)
- `lambda`: [LambdaActionTypeDef](./type_defs.md#lambdaactiontypedef)
- `iotEvents`: [IotEventsActionTypeDef](./type_defs.md#ioteventsactiontypedef)
- `sqs`: [SqsActionTypeDef](./type_defs.md#sqsactiontypedef)
- `firehose`: [FirehoseActionTypeDef](./type_defs.md#firehoseactiontypedef)
- `dynamoDB`: [DynamoDBActionTypeDef](./type_defs.md#dynamodbactiontypedef)
- `dynamoDBv2`:
  [DynamoDBv2ActionTypeDef](./type_defs.md#dynamodbv2actiontypedef)
- `iotSiteWise`:
  [IotSiteWiseActionTypeDef](./type_defs.md#iotsitewiseactiontypedef)

<a id="alarmactiontypedef"></a>

## AlarmActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AlarmActionTypeDef
```

Optional fields:

- `sns`:
  [SNSTopicPublishActionTypeDef](./type_defs.md#snstopicpublishactiontypedef)
- `iotTopicPublish`:
  [IotTopicPublishActionTypeDef](./type_defs.md#iottopicpublishactiontypedef)
- `lambda`: [LambdaActionTypeDef](./type_defs.md#lambdaactiontypedef)
- `iotEvents`: [IotEventsActionTypeDef](./type_defs.md#ioteventsactiontypedef)
- `sqs`: [SqsActionTypeDef](./type_defs.md#sqsactiontypedef)
- `firehose`: [FirehoseActionTypeDef](./type_defs.md#firehoseactiontypedef)
- `dynamoDB`: [DynamoDBActionTypeDef](./type_defs.md#dynamodbactiontypedef)
- `dynamoDBv2`:
  [DynamoDBv2ActionTypeDef](./type_defs.md#dynamodbv2actiontypedef)
- `iotSiteWise`:
  [IotSiteWiseActionTypeDef](./type_defs.md#iotsitewiseactiontypedef)

<a id="alarmcapabilitiestypedef"></a>

## AlarmCapabilitiesTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AlarmCapabilitiesTypeDef
```

Optional fields:

- `initializationConfiguration`:
  [InitializationConfigurationTypeDef](./type_defs.md#initializationconfigurationtypedef)
- `acknowledgeFlow`:
  [AcknowledgeFlowTypeDef](./type_defs.md#acknowledgeflowtypedef)

<a id="alarmeventactionstypedef"></a>

## AlarmEventActionsTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AlarmEventActionsTypeDef
```

Optional fields:

- `alarmActions`:
  `Sequence`\[[AlarmActionTypeDef](./type_defs.md#alarmactiontypedef)\]

<a id="alarmmodelsummarytypedef"></a>

## AlarmModelSummaryTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AlarmModelSummaryTypeDef
```

Optional fields:

- `creationTime`: `datetime`
- `alarmModelDescription`: `str`
- `alarmModelName`: `str`

<a id="alarmmodelversionsummarytypedef"></a>

## AlarmModelVersionSummaryTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AlarmModelVersionSummaryTypeDef
```

Optional fields:

- `alarmModelName`: `str`
- `alarmModelArn`: `str`
- `alarmModelVersion`: `str`
- `roleArn`: `str`
- `creationTime`: `datetime`
- `lastUpdateTime`: `datetime`
- `status`:
  [AlarmModelVersionStatusType](./literals.md#alarmmodelversionstatustype)
- `statusMessage`: `str`

<a id="alarmnotificationtypedef"></a>

## AlarmNotificationTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AlarmNotificationTypeDef
```

Optional fields:

- `notificationActions`:
  `Sequence`\[[NotificationActionTypeDef](./type_defs.md#notificationactiontypedef)\]

<a id="alarmruletypedef"></a>

## AlarmRuleTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AlarmRuleTypeDef
```

Optional fields:

- `simpleRule`: [SimpleRuleTypeDef](./type_defs.md#simpleruletypedef)

<a id="analysisresultlocationtypedef"></a>

## AnalysisResultLocationTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AnalysisResultLocationTypeDef
```

Optional fields:

- `path`: `str`

<a id="analysisresulttypedef"></a>

## AnalysisResultTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AnalysisResultTypeDef
```

Optional fields:

- `type`: `str`
- `level`: [AnalysisResultLevelType](./literals.md#analysisresultleveltype)
- `message`: `str`
- `locations`:
  `List`\[[AnalysisResultLocationTypeDef](./type_defs.md#analysisresultlocationtypedef)\]

<a id="assetpropertytimestamptypedef"></a>

## AssetPropertyTimestampTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AssetPropertyTimestampTypeDef
```

Required fields:

- `timeInSeconds`: `str`

Optional fields:

- `offsetInNanos`: `str`

<a id="assetpropertyvaluetypedef"></a>

## AssetPropertyValueTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AssetPropertyValueTypeDef
```

Optional fields:

- `value`:
  [AssetPropertyVariantTypeDef](./type_defs.md#assetpropertyvarianttypedef)
- `timestamp`:
  [AssetPropertyTimestampTypeDef](./type_defs.md#assetpropertytimestamptypedef)
- `quality`: `str`

<a id="assetpropertyvarianttypedef"></a>

## AssetPropertyVariantTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AssetPropertyVariantTypeDef
```

Optional fields:

- `stringValue`: `str`
- `integerValue`: `str`
- `doubleValue`: `str`
- `booleanValue`: `str`

<a id="attributetypedef"></a>

## AttributeTypeDef

```python
from types_aiobotocore_iotevents.type_defs import AttributeTypeDef
```

Required fields:

- `jsonPath`: `str`

<a id="cleartimeractiontypedef"></a>

## ClearTimerActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ClearTimerActionTypeDef
```

Required fields:

- `timerName`: `str`

<a id="createalarmmodelrequestrequesttypedef"></a>

## CreateAlarmModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import CreateAlarmModelRequestRequestTypeDef
```

Required fields:

- `alarmModelName`: `str`
- `roleArn`: `str`
- `alarmRule`: [AlarmRuleTypeDef](./type_defs.md#alarmruletypedef)

Optional fields:

- `alarmModelDescription`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `key`: `str`
- `severity`: `int`
- `alarmNotification`:
  [AlarmNotificationTypeDef](./type_defs.md#alarmnotificationtypedef)
- `alarmEventActions`:
  [AlarmEventActionsTypeDef](./type_defs.md#alarmeventactionstypedef)
- `alarmCapabilities`:
  [AlarmCapabilitiesTypeDef](./type_defs.md#alarmcapabilitiestypedef)

<a id="createalarmmodelresponsetypedef"></a>

## CreateAlarmModelResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import CreateAlarmModelResponseTypeDef
```

Required fields:

- `creationTime`: `datetime`
- `alarmModelArn`: `str`
- `alarmModelVersion`: `str`
- `lastUpdateTime`: `datetime`
- `status`:
  [AlarmModelVersionStatusType](./literals.md#alarmmodelversionstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdetectormodelrequestrequesttypedef"></a>

## CreateDetectorModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import CreateDetectorModelRequestRequestTypeDef
```

Required fields:

- `detectorModelName`: `str`
- `detectorModelDefinition`:
  [DetectorModelDefinitionTypeDef](./type_defs.md#detectormodeldefinitiontypedef)
- `roleArn`: `str`

Optional fields:

- `detectorModelDescription`: `str`
- `key`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `evaluationMethod`:
  [EvaluationMethodType](./literals.md#evaluationmethodtype)

<a id="createdetectormodelresponsetypedef"></a>

## CreateDetectorModelResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import CreateDetectorModelResponseTypeDef
```

Required fields:

- `detectorModelConfiguration`:
  [DetectorModelConfigurationTypeDef](./type_defs.md#detectormodelconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createinputrequestrequesttypedef"></a>

## CreateInputRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import CreateInputRequestRequestTypeDef
```

Required fields:

- `inputName`: `str`
- `inputDefinition`:
  [InputDefinitionTypeDef](./type_defs.md#inputdefinitiontypedef)

Optional fields:

- `inputDescription`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createinputresponsetypedef"></a>

## CreateInputResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import CreateInputResponseTypeDef
```

Required fields:

- `inputConfiguration`:
  [InputConfigurationTypeDef](./type_defs.md#inputconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletealarmmodelrequestrequesttypedef"></a>

## DeleteAlarmModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DeleteAlarmModelRequestRequestTypeDef
```

Required fields:

- `alarmModelName`: `str`

<a id="deletedetectormodelrequestrequesttypedef"></a>

## DeleteDetectorModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DeleteDetectorModelRequestRequestTypeDef
```

Required fields:

- `detectorModelName`: `str`

<a id="deleteinputrequestrequesttypedef"></a>

## DeleteInputRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DeleteInputRequestRequestTypeDef
```

Required fields:

- `inputName`: `str`

<a id="describealarmmodelrequestrequesttypedef"></a>

## DescribeAlarmModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeAlarmModelRequestRequestTypeDef
```

Required fields:

- `alarmModelName`: `str`

Optional fields:

- `alarmModelVersion`: `str`

<a id="describealarmmodelresponsetypedef"></a>

## DescribeAlarmModelResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeAlarmModelResponseTypeDef
```

Required fields:

- `creationTime`: `datetime`
- `alarmModelArn`: `str`
- `alarmModelVersion`: `str`
- `lastUpdateTime`: `datetime`
- `status`:
  [AlarmModelVersionStatusType](./literals.md#alarmmodelversionstatustype)
- `statusMessage`: `str`
- `alarmModelName`: `str`
- `alarmModelDescription`: `str`
- `roleArn`: `str`
- `key`: `str`
- `severity`: `int`
- `alarmRule`: [AlarmRuleTypeDef](./type_defs.md#alarmruletypedef)
- `alarmNotification`:
  [AlarmNotificationTypeDef](./type_defs.md#alarmnotificationtypedef)
- `alarmEventActions`:
  [AlarmEventActionsTypeDef](./type_defs.md#alarmeventactionstypedef)
- `alarmCapabilities`:
  [AlarmCapabilitiesTypeDef](./type_defs.md#alarmcapabilitiestypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedetectormodelanalysisrequestrequesttypedef"></a>

## DescribeDetectorModelAnalysisRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeDetectorModelAnalysisRequestRequestTypeDef
```

Required fields:

- `analysisId`: `str`

<a id="describedetectormodelanalysisresponsetypedef"></a>

## DescribeDetectorModelAnalysisResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeDetectorModelAnalysisResponseTypeDef
```

Required fields:

- `status`: [AnalysisStatusType](./literals.md#analysisstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedetectormodelrequestrequesttypedef"></a>

## DescribeDetectorModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeDetectorModelRequestRequestTypeDef
```

Required fields:

- `detectorModelName`: `str`

Optional fields:

- `detectorModelVersion`: `str`

<a id="describedetectormodelresponsetypedef"></a>

## DescribeDetectorModelResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeDetectorModelResponseTypeDef
```

Required fields:

- `detectorModel`: [DetectorModelTypeDef](./type_defs.md#detectormodeltypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeinputrequestrequesttypedef"></a>

## DescribeInputRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeInputRequestRequestTypeDef
```

Required fields:

- `inputName`: `str`

<a id="describeinputresponsetypedef"></a>

## DescribeInputResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeInputResponseTypeDef
```

Required fields:

- `input`: [InputTypeDef](./type_defs.md#inputtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeloggingoptionsresponsetypedef"></a>

## DescribeLoggingOptionsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DescribeLoggingOptionsResponseTypeDef
```

Required fields:

- `loggingOptions`:
  [LoggingOptionsTypeDef](./type_defs.md#loggingoptionstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="detectordebugoptiontypedef"></a>

## DetectorDebugOptionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DetectorDebugOptionTypeDef
```

Required fields:

- `detectorModelName`: `str`

Optional fields:

- `keyValue`: `str`

<a id="detectormodelconfigurationtypedef"></a>

## DetectorModelConfigurationTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DetectorModelConfigurationTypeDef
```

Optional fields:

- `detectorModelName`: `str`
- `detectorModelVersion`: `str`
- `detectorModelDescription`: `str`
- `detectorModelArn`: `str`
- `roleArn`: `str`
- `creationTime`: `datetime`
- `lastUpdateTime`: `datetime`
- `status`:
  [DetectorModelVersionStatusType](./literals.md#detectormodelversionstatustype)
- `key`: `str`
- `evaluationMethod`:
  [EvaluationMethodType](./literals.md#evaluationmethodtype)

<a id="detectormodeldefinitiontypedef"></a>

## DetectorModelDefinitionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DetectorModelDefinitionTypeDef
```

Required fields:

- `states`: `Sequence`\[[StateTypeDef](./type_defs.md#statetypedef)\]
- `initialStateName`: `str`

<a id="detectormodelsummarytypedef"></a>

## DetectorModelSummaryTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DetectorModelSummaryTypeDef
```

Optional fields:

- `detectorModelName`: `str`
- `detectorModelDescription`: `str`
- `creationTime`: `datetime`

<a id="detectormodeltypedef"></a>

## DetectorModelTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DetectorModelTypeDef
```

Optional fields:

- `detectorModelDefinition`:
  [DetectorModelDefinitionTypeDef](./type_defs.md#detectormodeldefinitiontypedef)
- `detectorModelConfiguration`:
  [DetectorModelConfigurationTypeDef](./type_defs.md#detectormodelconfigurationtypedef)

<a id="detectormodelversionsummarytypedef"></a>

## DetectorModelVersionSummaryTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DetectorModelVersionSummaryTypeDef
```

Optional fields:

- `detectorModelName`: `str`
- `detectorModelVersion`: `str`
- `detectorModelArn`: `str`
- `roleArn`: `str`
- `creationTime`: `datetime`
- `lastUpdateTime`: `datetime`
- `status`:
  [DetectorModelVersionStatusType](./literals.md#detectormodelversionstatustype)
- `evaluationMethod`:
  [EvaluationMethodType](./literals.md#evaluationmethodtype)

<a id="dynamodbactiontypedef"></a>

## DynamoDBActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DynamoDBActionTypeDef
```

Required fields:

- `hashKeyField`: `str`
- `hashKeyValue`: `str`
- `tableName`: `str`

Optional fields:

- `hashKeyType`: `str`
- `rangeKeyType`: `str`
- `rangeKeyField`: `str`
- `rangeKeyValue`: `str`
- `operation`: `str`
- `payloadField`: `str`
- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="dynamodbv2actiontypedef"></a>

## DynamoDBv2ActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import DynamoDBv2ActionTypeDef
```

Required fields:

- `tableName`: `str`

Optional fields:

- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="emailconfigurationtypedef"></a>

## EmailConfigurationTypeDef

```python
from types_aiobotocore_iotevents.type_defs import EmailConfigurationTypeDef
```

Required fields:

- `from`: `str`
- `recipients`: [EmailRecipientsTypeDef](./type_defs.md#emailrecipientstypedef)

Optional fields:

- `content`: [EmailContentTypeDef](./type_defs.md#emailcontenttypedef)

<a id="emailcontenttypedef"></a>

## EmailContentTypeDef

```python
from types_aiobotocore_iotevents.type_defs import EmailContentTypeDef
```

Optional fields:

- `subject`: `str`
- `additionalMessage`: `str`

<a id="emailrecipientstypedef"></a>

## EmailRecipientsTypeDef

```python
from types_aiobotocore_iotevents.type_defs import EmailRecipientsTypeDef
```

Optional fields:

- `to`:
  `Sequence`\[[RecipientDetailTypeDef](./type_defs.md#recipientdetailtypedef)\]

<a id="eventtypedef"></a>

## EventTypeDef

```python
from types_aiobotocore_iotevents.type_defs import EventTypeDef
```

Required fields:

- `eventName`: `str`

Optional fields:

- `condition`: `str`
- `actions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]

<a id="firehoseactiontypedef"></a>

## FirehoseActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import FirehoseActionTypeDef
```

Required fields:

- `deliveryStreamName`: `str`

Optional fields:

- `separator`: `str`
- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="getdetectormodelanalysisresultsrequestrequesttypedef"></a>

## GetDetectorModelAnalysisResultsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import GetDetectorModelAnalysisResultsRequestRequestTypeDef
```

Required fields:

- `analysisId`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="getdetectormodelanalysisresultsresponsetypedef"></a>

## GetDetectorModelAnalysisResultsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import GetDetectorModelAnalysisResultsResponseTypeDef
```

Required fields:

- `analysisResults`:
  `List`\[[AnalysisResultTypeDef](./type_defs.md#analysisresulttypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="initializationconfigurationtypedef"></a>

## InitializationConfigurationTypeDef

```python
from types_aiobotocore_iotevents.type_defs import InitializationConfigurationTypeDef
```

Required fields:

- `disabledOnInitialization`: `bool`

<a id="inputconfigurationtypedef"></a>

## InputConfigurationTypeDef

```python
from types_aiobotocore_iotevents.type_defs import InputConfigurationTypeDef
```

Required fields:

- `inputName`: `str`
- `inputArn`: `str`
- `creationTime`: `datetime`
- `lastUpdateTime`: `datetime`
- `status`: [InputStatusType](./literals.md#inputstatustype)

Optional fields:

- `inputDescription`: `str`

<a id="inputdefinitiontypedef"></a>

## InputDefinitionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import InputDefinitionTypeDef
```

Required fields:

- `attributes`:
  `Sequence`\[[AttributeTypeDef](./type_defs.md#attributetypedef)\]

<a id="inputidentifiertypedef"></a>

## InputIdentifierTypeDef

```python
from types_aiobotocore_iotevents.type_defs import InputIdentifierTypeDef
```

Optional fields:

- `iotEventsInputIdentifier`:
  [IotEventsInputIdentifierTypeDef](./type_defs.md#ioteventsinputidentifiertypedef)
- `iotSiteWiseInputIdentifier`:
  [IotSiteWiseInputIdentifierTypeDef](./type_defs.md#iotsitewiseinputidentifiertypedef)

<a id="inputsummarytypedef"></a>

## InputSummaryTypeDef

```python
from types_aiobotocore_iotevents.type_defs import InputSummaryTypeDef
```

Optional fields:

- `inputName`: `str`
- `inputDescription`: `str`
- `inputArn`: `str`
- `creationTime`: `datetime`
- `lastUpdateTime`: `datetime`
- `status`: [InputStatusType](./literals.md#inputstatustype)

<a id="inputtypedef"></a>

## InputTypeDef

```python
from types_aiobotocore_iotevents.type_defs import InputTypeDef
```

Optional fields:

- `inputConfiguration`:
  [InputConfigurationTypeDef](./type_defs.md#inputconfigurationtypedef)
- `inputDefinition`:
  [InputDefinitionTypeDef](./type_defs.md#inputdefinitiontypedef)

<a id="ioteventsactiontypedef"></a>

## IotEventsActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import IotEventsActionTypeDef
```

Required fields:

- `inputName`: `str`

Optional fields:

- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="ioteventsinputidentifiertypedef"></a>

## IotEventsInputIdentifierTypeDef

```python
from types_aiobotocore_iotevents.type_defs import IotEventsInputIdentifierTypeDef
```

Required fields:

- `inputName`: `str`

<a id="iotsitewiseactiontypedef"></a>

## IotSiteWiseActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import IotSiteWiseActionTypeDef
```

Optional fields:

- `entryId`: `str`
- `assetId`: `str`
- `propertyId`: `str`
- `propertyAlias`: `str`
- `propertyValue`:
  [AssetPropertyValueTypeDef](./type_defs.md#assetpropertyvaluetypedef)

<a id="iotsitewiseassetmodelpropertyidentifiertypedef"></a>

## IotSiteWiseAssetModelPropertyIdentifierTypeDef

```python
from types_aiobotocore_iotevents.type_defs import IotSiteWiseAssetModelPropertyIdentifierTypeDef
```

Required fields:

- `assetModelId`: `str`
- `propertyId`: `str`

<a id="iotsitewiseinputidentifiertypedef"></a>

## IotSiteWiseInputIdentifierTypeDef

```python
from types_aiobotocore_iotevents.type_defs import IotSiteWiseInputIdentifierTypeDef
```

Optional fields:

- `iotSiteWiseAssetModelPropertyIdentifier`:
  [IotSiteWiseAssetModelPropertyIdentifierTypeDef](./type_defs.md#iotsitewiseassetmodelpropertyidentifiertypedef)

<a id="iottopicpublishactiontypedef"></a>

## IotTopicPublishActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import IotTopicPublishActionTypeDef
```

Required fields:

- `mqttTopic`: `str`

Optional fields:

- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="lambdaactiontypedef"></a>

## LambdaActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import LambdaActionTypeDef
```

Required fields:

- `functionArn`: `str`

Optional fields:

- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="listalarmmodelversionsrequestrequesttypedef"></a>

## ListAlarmModelVersionsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListAlarmModelVersionsRequestRequestTypeDef
```

Required fields:

- `alarmModelName`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listalarmmodelversionsresponsetypedef"></a>

## ListAlarmModelVersionsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListAlarmModelVersionsResponseTypeDef
```

Required fields:

- `alarmModelVersionSummaries`:
  `List`\[[AlarmModelVersionSummaryTypeDef](./type_defs.md#alarmmodelversionsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listalarmmodelsrequestrequesttypedef"></a>

## ListAlarmModelsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListAlarmModelsRequestRequestTypeDef
```

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listalarmmodelsresponsetypedef"></a>

## ListAlarmModelsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListAlarmModelsResponseTypeDef
```

Required fields:

- `alarmModelSummaries`:
  `List`\[[AlarmModelSummaryTypeDef](./type_defs.md#alarmmodelsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdetectormodelversionsrequestrequesttypedef"></a>

## ListDetectorModelVersionsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListDetectorModelVersionsRequestRequestTypeDef
```

Required fields:

- `detectorModelName`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listdetectormodelversionsresponsetypedef"></a>

## ListDetectorModelVersionsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListDetectorModelVersionsResponseTypeDef
```

Required fields:

- `detectorModelVersionSummaries`:
  `List`\[[DetectorModelVersionSummaryTypeDef](./type_defs.md#detectormodelversionsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdetectormodelsrequestrequesttypedef"></a>

## ListDetectorModelsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListDetectorModelsRequestRequestTypeDef
```

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listdetectormodelsresponsetypedef"></a>

## ListDetectorModelsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListDetectorModelsResponseTypeDef
```

Required fields:

- `detectorModelSummaries`:
  `List`\[[DetectorModelSummaryTypeDef](./type_defs.md#detectormodelsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinputroutingsrequestrequesttypedef"></a>

## ListInputRoutingsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListInputRoutingsRequestRequestTypeDef
```

Required fields:

- `inputIdentifier`:
  [InputIdentifierTypeDef](./type_defs.md#inputidentifiertypedef)

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listinputroutingsresponsetypedef"></a>

## ListInputRoutingsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListInputRoutingsResponseTypeDef
```

Required fields:

- `routedResources`:
  `List`\[[RoutedResourceTypeDef](./type_defs.md#routedresourcetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinputsrequestrequesttypedef"></a>

## ListInputsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListInputsRequestRequestTypeDef
```

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listinputsresponsetypedef"></a>

## ListInputsResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListInputsResponseTypeDef
```

Required fields:

- `inputSummaries`:
  `List`\[[InputSummaryTypeDef](./type_defs.md#inputsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="loggingoptionstypedef"></a>

## LoggingOptionsTypeDef

```python
from types_aiobotocore_iotevents.type_defs import LoggingOptionsTypeDef
```

Required fields:

- `roleArn`: `str`
- `level`: [LoggingLevelType](./literals.md#loggingleveltype)
- `enabled`: `bool`

Optional fields:

- `detectorDebugOptions`:
  `List`\[[DetectorDebugOptionTypeDef](./type_defs.md#detectordebugoptiontypedef)\]

<a id="notificationactiontypedef"></a>

## NotificationActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import NotificationActionTypeDef
```

Required fields:

- `action`:
  [NotificationTargetActionsTypeDef](./type_defs.md#notificationtargetactionstypedef)

Optional fields:

- `smsConfigurations`:
  `Sequence`\[[SMSConfigurationTypeDef](./type_defs.md#smsconfigurationtypedef)\]
- `emailConfigurations`:
  `Sequence`\[[EmailConfigurationTypeDef](./type_defs.md#emailconfigurationtypedef)\]

<a id="notificationtargetactionstypedef"></a>

## NotificationTargetActionsTypeDef

```python
from types_aiobotocore_iotevents.type_defs import NotificationTargetActionsTypeDef
```

Optional fields:

- `lambdaAction`: [LambdaActionTypeDef](./type_defs.md#lambdaactiontypedef)

<a id="onenterlifecycletypedef"></a>

## OnEnterLifecycleTypeDef

```python
from types_aiobotocore_iotevents.type_defs import OnEnterLifecycleTypeDef
```

Optional fields:

- `events`: `Sequence`\[[EventTypeDef](./type_defs.md#eventtypedef)\]

<a id="onexitlifecycletypedef"></a>

## OnExitLifecycleTypeDef

```python
from types_aiobotocore_iotevents.type_defs import OnExitLifecycleTypeDef
```

Optional fields:

- `events`: `Sequence`\[[EventTypeDef](./type_defs.md#eventtypedef)\]

<a id="oninputlifecycletypedef"></a>

## OnInputLifecycleTypeDef

```python
from types_aiobotocore_iotevents.type_defs import OnInputLifecycleTypeDef
```

Optional fields:

- `events`: `Sequence`\[[EventTypeDef](./type_defs.md#eventtypedef)\]
- `transitionEvents`:
  `Sequence`\[[TransitionEventTypeDef](./type_defs.md#transitioneventtypedef)\]

<a id="payloadtypedef"></a>

## PayloadTypeDef

```python
from types_aiobotocore_iotevents.type_defs import PayloadTypeDef
```

Required fields:

- `contentExpression`: `str`
- `type`: [PayloadTypeType](./literals.md#payloadtypetype)

<a id="putloggingoptionsrequestrequesttypedef"></a>

## PutLoggingOptionsRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import PutLoggingOptionsRequestRequestTypeDef
```

Required fields:

- `loggingOptions`:
  [LoggingOptionsTypeDef](./type_defs.md#loggingoptionstypedef)

<a id="recipientdetailtypedef"></a>

## RecipientDetailTypeDef

```python
from types_aiobotocore_iotevents.type_defs import RecipientDetailTypeDef
```

Optional fields:

- `ssoIdentity`: [SSOIdentityTypeDef](./type_defs.md#ssoidentitytypedef)

<a id="resettimeractiontypedef"></a>

## ResetTimerActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ResetTimerActionTypeDef
```

Required fields:

- `timerName`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_iotevents.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="routedresourcetypedef"></a>

## RoutedResourceTypeDef

```python
from types_aiobotocore_iotevents.type_defs import RoutedResourceTypeDef
```

Optional fields:

- `name`: `str`
- `arn`: `str`

<a id="smsconfigurationtypedef"></a>

## SMSConfigurationTypeDef

```python
from types_aiobotocore_iotevents.type_defs import SMSConfigurationTypeDef
```

Required fields:

- `recipients`:
  `Sequence`\[[RecipientDetailTypeDef](./type_defs.md#recipientdetailtypedef)\]

Optional fields:

- `senderId`: `str`
- `additionalMessage`: `str`

<a id="snstopicpublishactiontypedef"></a>

## SNSTopicPublishActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import SNSTopicPublishActionTypeDef
```

Required fields:

- `targetArn`: `str`

Optional fields:

- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="ssoidentitytypedef"></a>

## SSOIdentityTypeDef

```python
from types_aiobotocore_iotevents.type_defs import SSOIdentityTypeDef
```

Required fields:

- `identityStoreId`: `str`

Optional fields:

- `userId`: `str`

<a id="settimeractiontypedef"></a>

## SetTimerActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import SetTimerActionTypeDef
```

Required fields:

- `timerName`: `str`

Optional fields:

- `seconds`: `int`
- `durationExpression`: `str`

<a id="setvariableactiontypedef"></a>

## SetVariableActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import SetVariableActionTypeDef
```

Required fields:

- `variableName`: `str`
- `value`: `str`

<a id="simpleruletypedef"></a>

## SimpleRuleTypeDef

```python
from types_aiobotocore_iotevents.type_defs import SimpleRuleTypeDef
```

Required fields:

- `inputProperty`: `str`
- `comparisonOperator`:
  [ComparisonOperatorType](./literals.md#comparisonoperatortype)
- `threshold`: `str`

<a id="sqsactiontypedef"></a>

## SqsActionTypeDef

```python
from types_aiobotocore_iotevents.type_defs import SqsActionTypeDef
```

Required fields:

- `queueUrl`: `str`

Optional fields:

- `useBase64`: `bool`
- `payload`: [PayloadTypeDef](./type_defs.md#payloadtypedef)

<a id="startdetectormodelanalysisrequestrequesttypedef"></a>

## StartDetectorModelAnalysisRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import StartDetectorModelAnalysisRequestRequestTypeDef
```

Required fields:

- `detectorModelDefinition`:
  [DetectorModelDefinitionTypeDef](./type_defs.md#detectormodeldefinitiontypedef)

<a id="startdetectormodelanalysisresponsetypedef"></a>

## StartDetectorModelAnalysisResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import StartDetectorModelAnalysisResponseTypeDef
```

Required fields:

- `analysisId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="statetypedef"></a>

## StateTypeDef

```python
from types_aiobotocore_iotevents.type_defs import StateTypeDef
```

Required fields:

- `stateName`: `str`

Optional fields:

- `onInput`: [OnInputLifecycleTypeDef](./type_defs.md#oninputlifecycletypedef)
- `onEnter`: [OnEnterLifecycleTypeDef](./type_defs.md#onenterlifecycletypedef)
- `onExit`: [OnExitLifecycleTypeDef](./type_defs.md#onexitlifecycletypedef)

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_iotevents.type_defs import TagTypeDef
```

Required fields:

- `key`: `str`
- `value`: `str`

<a id="transitioneventtypedef"></a>

## TransitionEventTypeDef

```python
from types_aiobotocore_iotevents.type_defs import TransitionEventTypeDef
```

Required fields:

- `eventName`: `str`
- `condition`: `str`
- `nextState`: `str`

Optional fields:

- `actions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tagKeys`: `Sequence`\[`str`\]

<a id="updatealarmmodelrequestrequesttypedef"></a>

## UpdateAlarmModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import UpdateAlarmModelRequestRequestTypeDef
```

Required fields:

- `alarmModelName`: `str`
- `roleArn`: `str`
- `alarmRule`: [AlarmRuleTypeDef](./type_defs.md#alarmruletypedef)

Optional fields:

- `alarmModelDescription`: `str`
- `severity`: `int`
- `alarmNotification`:
  [AlarmNotificationTypeDef](./type_defs.md#alarmnotificationtypedef)
- `alarmEventActions`:
  [AlarmEventActionsTypeDef](./type_defs.md#alarmeventactionstypedef)
- `alarmCapabilities`:
  [AlarmCapabilitiesTypeDef](./type_defs.md#alarmcapabilitiestypedef)

<a id="updatealarmmodelresponsetypedef"></a>

## UpdateAlarmModelResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import UpdateAlarmModelResponseTypeDef
```

Required fields:

- `creationTime`: `datetime`
- `alarmModelArn`: `str`
- `alarmModelVersion`: `str`
- `lastUpdateTime`: `datetime`
- `status`:
  [AlarmModelVersionStatusType](./literals.md#alarmmodelversionstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatedetectormodelrequestrequesttypedef"></a>

## UpdateDetectorModelRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import UpdateDetectorModelRequestRequestTypeDef
```

Required fields:

- `detectorModelName`: `str`
- `detectorModelDefinition`:
  [DetectorModelDefinitionTypeDef](./type_defs.md#detectormodeldefinitiontypedef)
- `roleArn`: `str`

Optional fields:

- `detectorModelDescription`: `str`
- `evaluationMethod`:
  [EvaluationMethodType](./literals.md#evaluationmethodtype)

<a id="updatedetectormodelresponsetypedef"></a>

## UpdateDetectorModelResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import UpdateDetectorModelResponseTypeDef
```

Required fields:

- `detectorModelConfiguration`:
  [DetectorModelConfigurationTypeDef](./type_defs.md#detectormodelconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateinputrequestrequesttypedef"></a>

## UpdateInputRequestRequestTypeDef

```python
from types_aiobotocore_iotevents.type_defs import UpdateInputRequestRequestTypeDef
```

Required fields:

- `inputName`: `str`
- `inputDefinition`:
  [InputDefinitionTypeDef](./type_defs.md#inputdefinitiontypedef)

Optional fields:

- `inputDescription`: `str`

<a id="updateinputresponsetypedef"></a>

## UpdateInputResponseTypeDef

```python
from types_aiobotocore_iotevents.type_defs import UpdateInputResponseTypeDef
```

Required fields:

- `inputConfiguration`:
  [InputConfigurationTypeDef](./type_defs.md#inputconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
