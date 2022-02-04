<a id="typed-dictionaries-for-aiobotocore-lexmodelsv2-module"></a>

# Typed dictionaries for aiobotocore LexModelsV2 module

> [Index](..) > [LexModelsV2](.) > Typed dictionaries

Auto-generated documentation for
[LexModelsV2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2)
type annotations stubs module
[types-aiobotocore-lexv2-models](https://pypi.org/project/types-aiobotocore-lexv2-models/).

- [Typed dictionaries for aiobotocore LexModelsV2 module](#typed-dictionaries-for-aiobotocore-lexmodelsv2-module)
  - [AggregatedUtterancesFilterTypeDef](#aggregatedutterancesfiltertypedef)
  - [AggregatedUtterancesSortByTypeDef](#aggregatedutterancessortbytypedef)
  - [AggregatedUtterancesSummaryTypeDef](#aggregatedutterancessummarytypedef)
  - [AssociatedTranscriptFilterTypeDef](#associatedtranscriptfiltertypedef)
  - [AssociatedTranscriptTypeDef](#associatedtranscripttypedef)
  - [AudioLogDestinationTypeDef](#audiologdestinationtypedef)
  - [AudioLogSettingTypeDef](#audiologsettingtypedef)
  - [BotAliasHistoryEventTypeDef](#botaliashistoryeventtypedef)
  - [BotAliasLocaleSettingsTypeDef](#botaliaslocalesettingstypedef)
  - [BotAliasSummaryTypeDef](#botaliassummarytypedef)
  - [BotExportSpecificationTypeDef](#botexportspecificationtypedef)
  - [BotFilterTypeDef](#botfiltertypedef)
  - [BotImportSpecificationTypeDef](#botimportspecificationtypedef)
  - [BotLocaleExportSpecificationTypeDef](#botlocaleexportspecificationtypedef)
  - [BotLocaleFilterTypeDef](#botlocalefiltertypedef)
  - [BotLocaleHistoryEventTypeDef](#botlocalehistoryeventtypedef)
  - [BotLocaleImportSpecificationTypeDef](#botlocaleimportspecificationtypedef)
  - [BotLocaleSortByTypeDef](#botlocalesortbytypedef)
  - [BotLocaleSummaryTypeDef](#botlocalesummarytypedef)
  - [BotRecommendationResultStatisticsTypeDef](#botrecommendationresultstatisticstypedef)
  - [BotRecommendationResultsTypeDef](#botrecommendationresultstypedef)
  - [BotRecommendationSummaryTypeDef](#botrecommendationsummarytypedef)
  - [BotSortByTypeDef](#botsortbytypedef)
  - [BotSummaryTypeDef](#botsummarytypedef)
  - [BotVersionLocaleDetailsTypeDef](#botversionlocaledetailstypedef)
  - [BotVersionSortByTypeDef](#botversionsortbytypedef)
  - [BotVersionSummaryTypeDef](#botversionsummarytypedef)
  - [BuildBotLocaleRequestRequestTypeDef](#buildbotlocalerequestrequesttypedef)
  - [BuildBotLocaleResponseTypeDef](#buildbotlocaleresponsetypedef)
  - [BuiltInIntentSortByTypeDef](#builtinintentsortbytypedef)
  - [BuiltInIntentSummaryTypeDef](#builtinintentsummarytypedef)
  - [BuiltInSlotTypeSortByTypeDef](#builtinslottypesortbytypedef)
  - [BuiltInSlotTypeSummaryTypeDef](#builtinslottypesummarytypedef)
  - [ButtonTypeDef](#buttontypedef)
  - [CloudWatchLogGroupLogDestinationTypeDef](#cloudwatchloggrouplogdestinationtypedef)
  - [CodeHookSpecificationTypeDef](#codehookspecificationtypedef)
  - [ConversationLogSettingsTypeDef](#conversationlogsettingstypedef)
  - [CreateBotAliasRequestRequestTypeDef](#createbotaliasrequestrequesttypedef)
  - [CreateBotAliasResponseTypeDef](#createbotaliasresponsetypedef)
  - [CreateBotLocaleRequestRequestTypeDef](#createbotlocalerequestrequesttypedef)
  - [CreateBotLocaleResponseTypeDef](#createbotlocaleresponsetypedef)
  - [CreateBotRequestRequestTypeDef](#createbotrequestrequesttypedef)
  - [CreateBotResponseTypeDef](#createbotresponsetypedef)
  - [CreateBotVersionRequestRequestTypeDef](#createbotversionrequestrequesttypedef)
  - [CreateBotVersionResponseTypeDef](#createbotversionresponsetypedef)
  - [CreateExportRequestRequestTypeDef](#createexportrequestrequesttypedef)
  - [CreateExportResponseTypeDef](#createexportresponsetypedef)
  - [CreateIntentRequestRequestTypeDef](#createintentrequestrequesttypedef)
  - [CreateIntentResponseTypeDef](#createintentresponsetypedef)
  - [CreateResourcePolicyRequestRequestTypeDef](#createresourcepolicyrequestrequesttypedef)
  - [CreateResourcePolicyResponseTypeDef](#createresourcepolicyresponsetypedef)
  - [CreateResourcePolicyStatementRequestRequestTypeDef](#createresourcepolicystatementrequestrequesttypedef)
  - [CreateResourcePolicyStatementResponseTypeDef](#createresourcepolicystatementresponsetypedef)
  - [CreateSlotRequestRequestTypeDef](#createslotrequestrequesttypedef)
  - [CreateSlotResponseTypeDef](#createslotresponsetypedef)
  - [CreateSlotTypeRequestRequestTypeDef](#createslottyperequestrequesttypedef)
  - [CreateSlotTypeResponseTypeDef](#createslottyperesponsetypedef)
  - [CreateUploadUrlResponseTypeDef](#createuploadurlresponsetypedef)
  - [CustomPayloadTypeDef](#custompayloadtypedef)
  - [DataPrivacyTypeDef](#dataprivacytypedef)
  - [DateRangeFilterTypeDef](#daterangefiltertypedef)
  - [DeleteBotAliasRequestRequestTypeDef](#deletebotaliasrequestrequesttypedef)
  - [DeleteBotAliasResponseTypeDef](#deletebotaliasresponsetypedef)
  - [DeleteBotLocaleRequestRequestTypeDef](#deletebotlocalerequestrequesttypedef)
  - [DeleteBotLocaleResponseTypeDef](#deletebotlocaleresponsetypedef)
  - [DeleteBotRequestRequestTypeDef](#deletebotrequestrequesttypedef)
  - [DeleteBotResponseTypeDef](#deletebotresponsetypedef)
  - [DeleteBotVersionRequestRequestTypeDef](#deletebotversionrequestrequesttypedef)
  - [DeleteBotVersionResponseTypeDef](#deletebotversionresponsetypedef)
  - [DeleteExportRequestRequestTypeDef](#deleteexportrequestrequesttypedef)
  - [DeleteExportResponseTypeDef](#deleteexportresponsetypedef)
  - [DeleteImportRequestRequestTypeDef](#deleteimportrequestrequesttypedef)
  - [DeleteImportResponseTypeDef](#deleteimportresponsetypedef)
  - [DeleteIntentRequestRequestTypeDef](#deleteintentrequestrequesttypedef)
  - [DeleteResourcePolicyRequestRequestTypeDef](#deleteresourcepolicyrequestrequesttypedef)
  - [DeleteResourcePolicyResponseTypeDef](#deleteresourcepolicyresponsetypedef)
  - [DeleteResourcePolicyStatementRequestRequestTypeDef](#deleteresourcepolicystatementrequestrequesttypedef)
  - [DeleteResourcePolicyStatementResponseTypeDef](#deleteresourcepolicystatementresponsetypedef)
  - [DeleteSlotRequestRequestTypeDef](#deleteslotrequestrequesttypedef)
  - [DeleteSlotTypeRequestRequestTypeDef](#deleteslottyperequestrequesttypedef)
  - [DeleteUtterancesRequestRequestTypeDef](#deleteutterancesrequestrequesttypedef)
  - [DescribeBotAliasRequestRequestTypeDef](#describebotaliasrequestrequesttypedef)
  - [DescribeBotAliasResponseTypeDef](#describebotaliasresponsetypedef)
  - [DescribeBotLocaleRequestRequestTypeDef](#describebotlocalerequestrequesttypedef)
  - [DescribeBotLocaleResponseTypeDef](#describebotlocaleresponsetypedef)
  - [DescribeBotRecommendationRequestRequestTypeDef](#describebotrecommendationrequestrequesttypedef)
  - [DescribeBotRecommendationResponseTypeDef](#describebotrecommendationresponsetypedef)
  - [DescribeBotRequestRequestTypeDef](#describebotrequestrequesttypedef)
  - [DescribeBotResponseTypeDef](#describebotresponsetypedef)
  - [DescribeBotVersionRequestRequestTypeDef](#describebotversionrequestrequesttypedef)
  - [DescribeBotVersionResponseTypeDef](#describebotversionresponsetypedef)
  - [DescribeExportRequestRequestTypeDef](#describeexportrequestrequesttypedef)
  - [DescribeExportResponseTypeDef](#describeexportresponsetypedef)
  - [DescribeImportRequestRequestTypeDef](#describeimportrequestrequesttypedef)
  - [DescribeImportResponseTypeDef](#describeimportresponsetypedef)
  - [DescribeIntentRequestRequestTypeDef](#describeintentrequestrequesttypedef)
  - [DescribeIntentResponseTypeDef](#describeintentresponsetypedef)
  - [DescribeResourcePolicyRequestRequestTypeDef](#describeresourcepolicyrequestrequesttypedef)
  - [DescribeResourcePolicyResponseTypeDef](#describeresourcepolicyresponsetypedef)
  - [DescribeSlotRequestRequestTypeDef](#describeslotrequestrequesttypedef)
  - [DescribeSlotResponseTypeDef](#describeslotresponsetypedef)
  - [DescribeSlotTypeRequestRequestTypeDef](#describeslottyperequestrequesttypedef)
  - [DescribeSlotTypeResponseTypeDef](#describeslottyperesponsetypedef)
  - [DialogCodeHookSettingsTypeDef](#dialogcodehooksettingstypedef)
  - [EncryptionSettingTypeDef](#encryptionsettingtypedef)
  - [ExportFilterTypeDef](#exportfiltertypedef)
  - [ExportResourceSpecificationTypeDef](#exportresourcespecificationtypedef)
  - [ExportSortByTypeDef](#exportsortbytypedef)
  - [ExportSummaryTypeDef](#exportsummarytypedef)
  - [ExternalSourceSettingTypeDef](#externalsourcesettingtypedef)
  - [FulfillmentCodeHookSettingsTypeDef](#fulfillmentcodehooksettingstypedef)
  - [FulfillmentStartResponseSpecificationTypeDef](#fulfillmentstartresponsespecificationtypedef)
  - [FulfillmentUpdateResponseSpecificationTypeDef](#fulfillmentupdateresponsespecificationtypedef)
  - [FulfillmentUpdatesSpecificationTypeDef](#fulfillmentupdatesspecificationtypedef)
  - [GrammarSlotTypeSettingTypeDef](#grammarslottypesettingtypedef)
  - [GrammarSlotTypeSourceTypeDef](#grammarslottypesourcetypedef)
  - [ImageResponseCardTypeDef](#imageresponsecardtypedef)
  - [ImportFilterTypeDef](#importfiltertypedef)
  - [ImportResourceSpecificationTypeDef](#importresourcespecificationtypedef)
  - [ImportSortByTypeDef](#importsortbytypedef)
  - [ImportSummaryTypeDef](#importsummarytypedef)
  - [InputContextTypeDef](#inputcontexttypedef)
  - [IntentClosingSettingTypeDef](#intentclosingsettingtypedef)
  - [IntentConfirmationSettingTypeDef](#intentconfirmationsettingtypedef)
  - [IntentFilterTypeDef](#intentfiltertypedef)
  - [IntentSortByTypeDef](#intentsortbytypedef)
  - [IntentStatisticsTypeDef](#intentstatisticstypedef)
  - [IntentSummaryTypeDef](#intentsummarytypedef)
  - [KendraConfigurationTypeDef](#kendraconfigurationtypedef)
  - [LambdaCodeHookTypeDef](#lambdacodehooktypedef)
  - [LexTranscriptFilterTypeDef](#lextranscriptfiltertypedef)
  - [ListAggregatedUtterancesRequestRequestTypeDef](#listaggregatedutterancesrequestrequesttypedef)
  - [ListAggregatedUtterancesResponseTypeDef](#listaggregatedutterancesresponsetypedef)
  - [ListBotAliasesRequestRequestTypeDef](#listbotaliasesrequestrequesttypedef)
  - [ListBotAliasesResponseTypeDef](#listbotaliasesresponsetypedef)
  - [ListBotLocalesRequestRequestTypeDef](#listbotlocalesrequestrequesttypedef)
  - [ListBotLocalesResponseTypeDef](#listbotlocalesresponsetypedef)
  - [ListBotRecommendationsRequestRequestTypeDef](#listbotrecommendationsrequestrequesttypedef)
  - [ListBotRecommendationsResponseTypeDef](#listbotrecommendationsresponsetypedef)
  - [ListBotVersionsRequestRequestTypeDef](#listbotversionsrequestrequesttypedef)
  - [ListBotVersionsResponseTypeDef](#listbotversionsresponsetypedef)
  - [ListBotsRequestRequestTypeDef](#listbotsrequestrequesttypedef)
  - [ListBotsResponseTypeDef](#listbotsresponsetypedef)
  - [ListBuiltInIntentsRequestRequestTypeDef](#listbuiltinintentsrequestrequesttypedef)
  - [ListBuiltInIntentsResponseTypeDef](#listbuiltinintentsresponsetypedef)
  - [ListBuiltInSlotTypesRequestRequestTypeDef](#listbuiltinslottypesrequestrequesttypedef)
  - [ListBuiltInSlotTypesResponseTypeDef](#listbuiltinslottypesresponsetypedef)
  - [ListExportsRequestRequestTypeDef](#listexportsrequestrequesttypedef)
  - [ListExportsResponseTypeDef](#listexportsresponsetypedef)
  - [ListImportsRequestRequestTypeDef](#listimportsrequestrequesttypedef)
  - [ListImportsResponseTypeDef](#listimportsresponsetypedef)
  - [ListIntentsRequestRequestTypeDef](#listintentsrequestrequesttypedef)
  - [ListIntentsResponseTypeDef](#listintentsresponsetypedef)
  - [ListRecommendedIntentsRequestRequestTypeDef](#listrecommendedintentsrequestrequesttypedef)
  - [ListRecommendedIntentsResponseTypeDef](#listrecommendedintentsresponsetypedef)
  - [ListSlotTypesRequestRequestTypeDef](#listslottypesrequestrequesttypedef)
  - [ListSlotTypesResponseTypeDef](#listslottypesresponsetypedef)
  - [ListSlotsRequestRequestTypeDef](#listslotsrequestrequesttypedef)
  - [ListSlotsResponseTypeDef](#listslotsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [MessageGroupTypeDef](#messagegrouptypedef)
  - [MessageTypeDef](#messagetypedef)
  - [MultipleValuesSettingTypeDef](#multiplevaluessettingtypedef)
  - [ObfuscationSettingTypeDef](#obfuscationsettingtypedef)
  - [OutputContextTypeDef](#outputcontexttypedef)
  - [PathFormatTypeDef](#pathformattypedef)
  - [PlainTextMessageTypeDef](#plaintextmessagetypedef)
  - [PostFulfillmentStatusSpecificationTypeDef](#postfulfillmentstatusspecificationtypedef)
  - [PrincipalTypeDef](#principaltypedef)
  - [PromptSpecificationTypeDef](#promptspecificationtypedef)
  - [RecommendedIntentSummaryTypeDef](#recommendedintentsummarytypedef)
  - [RelativeAggregationDurationTypeDef](#relativeaggregationdurationtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ResponseSpecificationTypeDef](#responsespecificationtypedef)
  - [S3BucketLogDestinationTypeDef](#s3bucketlogdestinationtypedef)
  - [S3BucketTranscriptSourceTypeDef](#s3buckettranscriptsourcetypedef)
  - [SSMLMessageTypeDef](#ssmlmessagetypedef)
  - [SampleUtteranceTypeDef](#sampleutterancetypedef)
  - [SampleValueTypeDef](#samplevaluetypedef)
  - [SearchAssociatedTranscriptsRequestRequestTypeDef](#searchassociatedtranscriptsrequestrequesttypedef)
  - [SearchAssociatedTranscriptsResponseTypeDef](#searchassociatedtranscriptsresponsetypedef)
  - [SentimentAnalysisSettingsTypeDef](#sentimentanalysissettingstypedef)
  - [SlotDefaultValueSpecificationTypeDef](#slotdefaultvaluespecificationtypedef)
  - [SlotDefaultValueTypeDef](#slotdefaultvaluetypedef)
  - [SlotFilterTypeDef](#slotfiltertypedef)
  - [SlotPriorityTypeDef](#slotprioritytypedef)
  - [SlotSortByTypeDef](#slotsortbytypedef)
  - [SlotSummaryTypeDef](#slotsummarytypedef)
  - [SlotTypeFilterTypeDef](#slottypefiltertypedef)
  - [SlotTypeSortByTypeDef](#slottypesortbytypedef)
  - [SlotTypeStatisticsTypeDef](#slottypestatisticstypedef)
  - [SlotTypeSummaryTypeDef](#slottypesummarytypedef)
  - [SlotTypeValueTypeDef](#slottypevaluetypedef)
  - [SlotValueElicitationSettingTypeDef](#slotvalueelicitationsettingtypedef)
  - [SlotValueRegexFilterTypeDef](#slotvalueregexfiltertypedef)
  - [SlotValueSelectionSettingTypeDef](#slotvalueselectionsettingtypedef)
  - [StartBotRecommendationRequestRequestTypeDef](#startbotrecommendationrequestrequesttypedef)
  - [StartBotRecommendationResponseTypeDef](#startbotrecommendationresponsetypedef)
  - [StartImportRequestRequestTypeDef](#startimportrequestrequesttypedef)
  - [StartImportResponseTypeDef](#startimportresponsetypedef)
  - [StillWaitingResponseSpecificationTypeDef](#stillwaitingresponsespecificationtypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TextLogDestinationTypeDef](#textlogdestinationtypedef)
  - [TextLogSettingTypeDef](#textlogsettingtypedef)
  - [TranscriptFilterTypeDef](#transcriptfiltertypedef)
  - [TranscriptSourceSettingTypeDef](#transcriptsourcesettingtypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateBotAliasRequestRequestTypeDef](#updatebotaliasrequestrequesttypedef)
  - [UpdateBotAliasResponseTypeDef](#updatebotaliasresponsetypedef)
  - [UpdateBotLocaleRequestRequestTypeDef](#updatebotlocalerequestrequesttypedef)
  - [UpdateBotLocaleResponseTypeDef](#updatebotlocaleresponsetypedef)
  - [UpdateBotRecommendationRequestRequestTypeDef](#updatebotrecommendationrequestrequesttypedef)
  - [UpdateBotRecommendationResponseTypeDef](#updatebotrecommendationresponsetypedef)
  - [UpdateBotRequestRequestTypeDef](#updatebotrequestrequesttypedef)
  - [UpdateBotResponseTypeDef](#updatebotresponsetypedef)
  - [UpdateExportRequestRequestTypeDef](#updateexportrequestrequesttypedef)
  - [UpdateExportResponseTypeDef](#updateexportresponsetypedef)
  - [UpdateIntentRequestRequestTypeDef](#updateintentrequestrequesttypedef)
  - [UpdateIntentResponseTypeDef](#updateintentresponsetypedef)
  - [UpdateResourcePolicyRequestRequestTypeDef](#updateresourcepolicyrequestrequesttypedef)
  - [UpdateResourcePolicyResponseTypeDef](#updateresourcepolicyresponsetypedef)
  - [UpdateSlotRequestRequestTypeDef](#updateslotrequestrequesttypedef)
  - [UpdateSlotResponseTypeDef](#updateslotresponsetypedef)
  - [UpdateSlotTypeRequestRequestTypeDef](#updateslottyperequestrequesttypedef)
  - [UpdateSlotTypeResponseTypeDef](#updateslottyperesponsetypedef)
  - [UtteranceAggregationDurationTypeDef](#utteranceaggregationdurationtypedef)
  - [VoiceSettingsTypeDef](#voicesettingstypedef)
  - [WaitAndContinueSpecificationTypeDef](#waitandcontinuespecificationtypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)

<a id="aggregatedutterancesfiltertypedef"></a>

## AggregatedUtterancesFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import AggregatedUtterancesFilterTypeDef
```

Required fields:

- `name`: `Literal['Utterance']` (see
  [AggregatedUtterancesFilterNameType](./literals.md#aggregatedutterancesfilternametype))
- `values`: `Sequence`\[`str`\]
- `operator`:
  [AggregatedUtterancesFilterOperatorType](./literals.md#aggregatedutterancesfilteroperatortype)

<a id="aggregatedutterancessortbytypedef"></a>

## AggregatedUtterancesSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import AggregatedUtterancesSortByTypeDef
```

Required fields:

- `attribute`:
  [AggregatedUtterancesSortAttributeType](./literals.md#aggregatedutterancessortattributetype)
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="aggregatedutterancessummarytypedef"></a>

## AggregatedUtterancesSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import AggregatedUtterancesSummaryTypeDef
```

Optional fields:

- `utterance`: `str`
- `hitCount`: `int`
- `missedCount`: `int`
- `utteranceFirstRecordedInAggregationDuration`: `datetime`
- `utteranceLastRecordedInAggregationDuration`: `datetime`
- `containsDataFromDeletedResources`: `bool`

<a id="associatedtranscriptfiltertypedef"></a>

## AssociatedTranscriptFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import AssociatedTranscriptFilterTypeDef
```

Required fields:

- `name`:
  [AssociatedTranscriptFilterNameType](./literals.md#associatedtranscriptfilternametype)
- `values`: `Sequence`\[`str`\]

<a id="associatedtranscripttypedef"></a>

## AssociatedTranscriptTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import AssociatedTranscriptTypeDef
```

Optional fields:

- `transcript`: `str`

<a id="audiologdestinationtypedef"></a>

## AudioLogDestinationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import AudioLogDestinationTypeDef
```

Required fields:

- `s3Bucket`:
  [S3BucketLogDestinationTypeDef](./type_defs.md#s3bucketlogdestinationtypedef)

<a id="audiologsettingtypedef"></a>

## AudioLogSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import AudioLogSettingTypeDef
```

Required fields:

- `enabled`: `bool`
- `destination`:
  [AudioLogDestinationTypeDef](./type_defs.md#audiologdestinationtypedef)

<a id="botaliashistoryeventtypedef"></a>

## BotAliasHistoryEventTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotAliasHistoryEventTypeDef
```

Optional fields:

- `botVersion`: `str`
- `startDate`: `datetime`
- `endDate`: `datetime`

<a id="botaliaslocalesettingstypedef"></a>

## BotAliasLocaleSettingsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotAliasLocaleSettingsTypeDef
```

Required fields:

- `enabled`: `bool`

Optional fields:

- `codeHookSpecification`:
  [CodeHookSpecificationTypeDef](./type_defs.md#codehookspecificationtypedef)

<a id="botaliassummarytypedef"></a>

## BotAliasSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotAliasSummaryTypeDef
```

Optional fields:

- `botAliasId`: `str`
- `botAliasName`: `str`
- `description`: `str`
- `botVersion`: `str`
- `botAliasStatus`: [BotAliasStatusType](./literals.md#botaliasstatustype)
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`

<a id="botexportspecificationtypedef"></a>

## BotExportSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotExportSpecificationTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`

<a id="botfiltertypedef"></a>

## BotFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotFilterTypeDef
```

Required fields:

- `name`: `Literal['BotName']` (see
  [BotFilterNameType](./literals.md#botfilternametype))
- `values`: `Sequence`\[`str`\]
- `operator`: [BotFilterOperatorType](./literals.md#botfilteroperatortype)

<a id="botimportspecificationtypedef"></a>

## BotImportSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotImportSpecificationTypeDef
```

Required fields:

- `botName`: `str`
- `roleArn`: `str`
- `dataPrivacy`: [DataPrivacyTypeDef](./type_defs.md#dataprivacytypedef)

Optional fields:

- `idleSessionTTLInSeconds`: `int`
- `botTags`: `Dict`\[`str`, `str`\]
- `testBotAliasTags`: `Dict`\[`str`, `str`\]

<a id="botlocaleexportspecificationtypedef"></a>

## BotLocaleExportSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotLocaleExportSpecificationTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

<a id="botlocalefiltertypedef"></a>

## BotLocaleFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotLocaleFilterTypeDef
```

Required fields:

- `name`: `Literal['BotLocaleName']` (see
  [BotLocaleFilterNameType](./literals.md#botlocalefilternametype))
- `values`: `Sequence`\[`str`\]
- `operator`:
  [BotLocaleFilterOperatorType](./literals.md#botlocalefilteroperatortype)

<a id="botlocalehistoryeventtypedef"></a>

## BotLocaleHistoryEventTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotLocaleHistoryEventTypeDef
```

Required fields:

- `event`: `str`
- `eventDate`: `datetime`

<a id="botlocaleimportspecificationtypedef"></a>

## BotLocaleImportSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotLocaleImportSpecificationTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `nluIntentConfidenceThreshold`: `float`
- `voiceSettings`: [VoiceSettingsTypeDef](./type_defs.md#voicesettingstypedef)

<a id="botlocalesortbytypedef"></a>

## BotLocaleSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotLocaleSortByTypeDef
```

Required fields:

- `attribute`: `Literal['BotLocaleName']` (see
  [BotLocaleSortAttributeType](./literals.md#botlocalesortattributetype))
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="botlocalesummarytypedef"></a>

## BotLocaleSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotLocaleSummaryTypeDef
```

Optional fields:

- `localeId`: `str`
- `localeName`: `str`
- `description`: `str`
- `botLocaleStatus`: [BotLocaleStatusType](./literals.md#botlocalestatustype)
- `lastUpdatedDateTime`: `datetime`
- `lastBuildSubmittedDateTime`: `datetime`

<a id="botrecommendationresultstatisticstypedef"></a>

## BotRecommendationResultStatisticsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotRecommendationResultStatisticsTypeDef
```

Optional fields:

- `intents`: [IntentStatisticsTypeDef](./type_defs.md#intentstatisticstypedef)
- `slotTypes`:
  [SlotTypeStatisticsTypeDef](./type_defs.md#slottypestatisticstypedef)

<a id="botrecommendationresultstypedef"></a>

## BotRecommendationResultsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotRecommendationResultsTypeDef
```

Optional fields:

- `botLocaleExportUrl`: `str`
- `associatedTranscriptsUrl`: `str`
- `statistics`:
  [BotRecommendationResultStatisticsTypeDef](./type_defs.md#botrecommendationresultstatisticstypedef)

<a id="botrecommendationsummarytypedef"></a>

## BotRecommendationSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotRecommendationSummaryTypeDef
```

Required fields:

- `botRecommendationStatus`:
  [BotRecommendationStatusType](./literals.md#botrecommendationstatustype)
- `botRecommendationId`: `str`

Optional fields:

- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`

<a id="botsortbytypedef"></a>

## BotSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotSortByTypeDef
```

Required fields:

- `attribute`: `Literal['BotName']` (see
  [BotSortAttributeType](./literals.md#botsortattributetype))
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="botsummarytypedef"></a>

## BotSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotSummaryTypeDef
```

Optional fields:

- `botId`: `str`
- `botName`: `str`
- `description`: `str`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `latestBotVersion`: `str`
- `lastUpdatedDateTime`: `datetime`

<a id="botversionlocaledetailstypedef"></a>

## BotVersionLocaleDetailsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotVersionLocaleDetailsTypeDef
```

Required fields:

- `sourceBotVersion`: `str`

<a id="botversionsortbytypedef"></a>

## BotVersionSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotVersionSortByTypeDef
```

Required fields:

- `attribute`: `Literal['BotVersion']` (see
  [BotVersionSortAttributeType](./literals.md#botversionsortattributetype))
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="botversionsummarytypedef"></a>

## BotVersionSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BotVersionSummaryTypeDef
```

Optional fields:

- `botName`: `str`
- `botVersion`: `str`
- `description`: `str`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `creationDateTime`: `datetime`

<a id="buildbotlocalerequestrequesttypedef"></a>

## BuildBotLocaleRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BuildBotLocaleRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

<a id="buildbotlocaleresponsetypedef"></a>

## BuildBotLocaleResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BuildBotLocaleResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botLocaleStatus`: [BotLocaleStatusType](./literals.md#botlocalestatustype)
- `lastBuildSubmittedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="builtinintentsortbytypedef"></a>

## BuiltInIntentSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BuiltInIntentSortByTypeDef
```

Required fields:

- `attribute`: `Literal['IntentSignature']` (see
  [BuiltInIntentSortAttributeType](./literals.md#builtinintentsortattributetype))
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="builtinintentsummarytypedef"></a>

## BuiltInIntentSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BuiltInIntentSummaryTypeDef
```

Optional fields:

- `intentSignature`: `str`
- `description`: `str`

<a id="builtinslottypesortbytypedef"></a>

## BuiltInSlotTypeSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BuiltInSlotTypeSortByTypeDef
```

Required fields:

- `attribute`: `Literal['SlotTypeSignature']` (see
  [BuiltInSlotTypeSortAttributeType](./literals.md#builtinslottypesortattributetype))
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="builtinslottypesummarytypedef"></a>

## BuiltInSlotTypeSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import BuiltInSlotTypeSummaryTypeDef
```

Optional fields:

- `slotTypeSignature`: `str`
- `description`: `str`

<a id="buttontypedef"></a>

## ButtonTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ButtonTypeDef
```

Required fields:

- `text`: `str`
- `value`: `str`

<a id="cloudwatchloggrouplogdestinationtypedef"></a>

## CloudWatchLogGroupLogDestinationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CloudWatchLogGroupLogDestinationTypeDef
```

Required fields:

- `cloudWatchLogGroupArn`: `str`
- `logPrefix`: `str`

<a id="codehookspecificationtypedef"></a>

## CodeHookSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CodeHookSpecificationTypeDef
```

Required fields:

- `lambdaCodeHook`:
  [LambdaCodeHookTypeDef](./type_defs.md#lambdacodehooktypedef)

<a id="conversationlogsettingstypedef"></a>

## ConversationLogSettingsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ConversationLogSettingsTypeDef
```

Optional fields:

- `textLogSettings`:
  `Sequence`\[[TextLogSettingTypeDef](./type_defs.md#textlogsettingtypedef)\]
- `audioLogSettings`:
  `Sequence`\[[AudioLogSettingTypeDef](./type_defs.md#audiologsettingtypedef)\]

<a id="createbotaliasrequestrequesttypedef"></a>

## CreateBotAliasRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotAliasRequestRequestTypeDef
```

Required fields:

- `botAliasName`: `str`
- `botId`: `str`

Optional fields:

- `description`: `str`
- `botVersion`: `str`
- `botAliasLocaleSettings`: `Mapping`\[`str`,
  [BotAliasLocaleSettingsTypeDef](./type_defs.md#botaliaslocalesettingstypedef)\]
- `conversationLogSettings`:
  [ConversationLogSettingsTypeDef](./type_defs.md#conversationlogsettingstypedef)
- `sentimentAnalysisSettings`:
  [SentimentAnalysisSettingsTypeDef](./type_defs.md#sentimentanalysissettingstypedef)
- `tags`: `Mapping`\[`str`, `str`\]

<a id="createbotaliasresponsetypedef"></a>

## CreateBotAliasResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotAliasResponseTypeDef
```

Required fields:

- `botAliasId`: `str`
- `botAliasName`: `str`
- `description`: `str`
- `botVersion`: `str`
- `botAliasLocaleSettings`: `Dict`\[`str`,
  [BotAliasLocaleSettingsTypeDef](./type_defs.md#botaliaslocalesettingstypedef)\]
- `conversationLogSettings`:
  [ConversationLogSettingsTypeDef](./type_defs.md#conversationlogsettingstypedef)
- `sentimentAnalysisSettings`:
  [SentimentAnalysisSettingsTypeDef](./type_defs.md#sentimentanalysissettingstypedef)
- `botAliasStatus`: [BotAliasStatusType](./literals.md#botaliasstatustype)
- `botId`: `str`
- `creationDateTime`: `datetime`
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createbotlocalerequestrequesttypedef"></a>

## CreateBotLocaleRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotLocaleRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `nluIntentConfidenceThreshold`: `float`

Optional fields:

- `description`: `str`
- `voiceSettings`: [VoiceSettingsTypeDef](./type_defs.md#voicesettingstypedef)

<a id="createbotlocaleresponsetypedef"></a>

## CreateBotLocaleResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotLocaleResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeName`: `str`
- `localeId`: `str`
- `description`: `str`
- `nluIntentConfidenceThreshold`: `float`
- `voiceSettings`: [VoiceSettingsTypeDef](./type_defs.md#voicesettingstypedef)
- `botLocaleStatus`: [BotLocaleStatusType](./literals.md#botlocalestatustype)
- `creationDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createbotrequestrequesttypedef"></a>

## CreateBotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotRequestRequestTypeDef
```

Required fields:

- `botName`: `str`
- `roleArn`: `str`
- `dataPrivacy`: [DataPrivacyTypeDef](./type_defs.md#dataprivacytypedef)
- `idleSessionTTLInSeconds`: `int`

Optional fields:

- `description`: `str`
- `botTags`: `Mapping`\[`str`, `str`\]
- `testBotAliasTags`: `Mapping`\[`str`, `str`\]

<a id="createbotresponsetypedef"></a>

## CreateBotResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botName`: `str`
- `description`: `str`
- `roleArn`: `str`
- `dataPrivacy`: [DataPrivacyTypeDef](./type_defs.md#dataprivacytypedef)
- `idleSessionTTLInSeconds`: `int`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `creationDateTime`: `datetime`
- `botTags`: `Dict`\[`str`, `str`\]
- `testBotAliasTags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createbotversionrequestrequesttypedef"></a>

## CreateBotVersionRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotVersionRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersionLocaleSpecification`: `Mapping`\[`str`,
  [BotVersionLocaleDetailsTypeDef](./type_defs.md#botversionlocaledetailstypedef)\]

Optional fields:

- `description`: `str`

<a id="createbotversionresponsetypedef"></a>

## CreateBotVersionResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateBotVersionResponseTypeDef
```

Required fields:

- `botId`: `str`
- `description`: `str`
- `botVersion`: `str`
- `botVersionLocaleSpecification`: `Dict`\[`str`,
  [BotVersionLocaleDetailsTypeDef](./type_defs.md#botversionlocaledetailstypedef)\]
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `creationDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createexportrequestrequesttypedef"></a>

## CreateExportRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateExportRequestRequestTypeDef
```

Required fields:

- `resourceSpecification`:
  [ExportResourceSpecificationTypeDef](./type_defs.md#exportresourcespecificationtypedef)
- `fileFormat`: `Literal['LexJson']` (see
  [ImportExportFileFormatType](./literals.md#importexportfileformattype))

Optional fields:

- `filePassword`: `str`

<a id="createexportresponsetypedef"></a>

## CreateExportResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateExportResponseTypeDef
```

Required fields:

- `exportId`: `str`
- `resourceSpecification`:
  [ExportResourceSpecificationTypeDef](./type_defs.md#exportresourcespecificationtypedef)
- `fileFormat`: `Literal['LexJson']` (see
  [ImportExportFileFormatType](./literals.md#importexportfileformattype))
- `exportStatus`: [ExportStatusType](./literals.md#exportstatustype)
- `creationDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createintentrequestrequesttypedef"></a>

## CreateIntentRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateIntentRequestRequestTypeDef
```

Required fields:

- `intentName`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `description`: `str`
- `parentIntentSignature`: `str`
- `sampleUtterances`:
  `Sequence`\[[SampleUtteranceTypeDef](./type_defs.md#sampleutterancetypedef)\]
- `dialogCodeHook`:
  [DialogCodeHookSettingsTypeDef](./type_defs.md#dialogcodehooksettingstypedef)
- `fulfillmentCodeHook`:
  [FulfillmentCodeHookSettingsTypeDef](./type_defs.md#fulfillmentcodehooksettingstypedef)
- `intentConfirmationSetting`:
  [IntentConfirmationSettingTypeDef](./type_defs.md#intentconfirmationsettingtypedef)
- `intentClosingSetting`:
  [IntentClosingSettingTypeDef](./type_defs.md#intentclosingsettingtypedef)
- `inputContexts`:
  `Sequence`\[[InputContextTypeDef](./type_defs.md#inputcontexttypedef)\]
- `outputContexts`:
  `Sequence`\[[OutputContextTypeDef](./type_defs.md#outputcontexttypedef)\]
- `kendraConfiguration`:
  [KendraConfigurationTypeDef](./type_defs.md#kendraconfigurationtypedef)

<a id="createintentresponsetypedef"></a>

## CreateIntentResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateIntentResponseTypeDef
```

Required fields:

- `intentId`: `str`
- `intentName`: `str`
- `description`: `str`
- `parentIntentSignature`: `str`
- `sampleUtterances`:
  `List`\[[SampleUtteranceTypeDef](./type_defs.md#sampleutterancetypedef)\]
- `dialogCodeHook`:
  [DialogCodeHookSettingsTypeDef](./type_defs.md#dialogcodehooksettingstypedef)
- `fulfillmentCodeHook`:
  [FulfillmentCodeHookSettingsTypeDef](./type_defs.md#fulfillmentcodehooksettingstypedef)
- `intentConfirmationSetting`:
  [IntentConfirmationSettingTypeDef](./type_defs.md#intentconfirmationsettingtypedef)
- `intentClosingSetting`:
  [IntentClosingSettingTypeDef](./type_defs.md#intentclosingsettingtypedef)
- `inputContexts`:
  `List`\[[InputContextTypeDef](./type_defs.md#inputcontexttypedef)\]
- `outputContexts`:
  `List`\[[OutputContextTypeDef](./type_defs.md#outputcontexttypedef)\]
- `kendraConfiguration`:
  [KendraConfigurationTypeDef](./type_defs.md#kendraconfigurationtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `creationDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createresourcepolicyrequestrequesttypedef"></a>

## CreateResourcePolicyRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateResourcePolicyRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `policy`: `str`

<a id="createresourcepolicyresponsetypedef"></a>

## CreateResourcePolicyResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateResourcePolicyResponseTypeDef
```

Required fields:

- `resourceArn`: `str`
- `revisionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createresourcepolicystatementrequestrequesttypedef"></a>

## CreateResourcePolicyStatementRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateResourcePolicyStatementRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `statementId`: `str`
- `effect`: [EffectType](./literals.md#effecttype)
- `principal`:
  `Sequence`\[[PrincipalTypeDef](./type_defs.md#principaltypedef)\]
- `action`: `Sequence`\[`str`\]

Optional fields:

- `condition`: `Mapping`\[`str`, `Mapping`\[`str`, `str`\]\]
- `expectedRevisionId`: `str`

<a id="createresourcepolicystatementresponsetypedef"></a>

## CreateResourcePolicyStatementResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateResourcePolicyStatementResponseTypeDef
```

Required fields:

- `resourceArn`: `str`
- `revisionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createslotrequestrequesttypedef"></a>

## CreateSlotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateSlotRequestRequestTypeDef
```

Required fields:

- `slotName`: `str`
- `slotTypeId`: `str`
- `valueElicitationSetting`:
  [SlotValueElicitationSettingTypeDef](./type_defs.md#slotvalueelicitationsettingtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`

Optional fields:

- `description`: `str`
- `obfuscationSetting`:
  [ObfuscationSettingTypeDef](./type_defs.md#obfuscationsettingtypedef)
- `multipleValuesSetting`:
  [MultipleValuesSettingTypeDef](./type_defs.md#multiplevaluessettingtypedef)

<a id="createslotresponsetypedef"></a>

## CreateSlotResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateSlotResponseTypeDef
```

Required fields:

- `slotId`: `str`
- `slotName`: `str`
- `description`: `str`
- `slotTypeId`: `str`
- `valueElicitationSetting`:
  [SlotValueElicitationSettingTypeDef](./type_defs.md#slotvalueelicitationsettingtypedef)
- `obfuscationSetting`:
  [ObfuscationSettingTypeDef](./type_defs.md#obfuscationsettingtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`
- `creationDateTime`: `datetime`
- `multipleValuesSetting`:
  [MultipleValuesSettingTypeDef](./type_defs.md#multiplevaluessettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createslottyperequestrequesttypedef"></a>

## CreateSlotTypeRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateSlotTypeRequestRequestTypeDef
```

Required fields:

- `slotTypeName`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `description`: `str`
- `slotTypeValues`:
  `Sequence`\[[SlotTypeValueTypeDef](./type_defs.md#slottypevaluetypedef)\]
- `valueSelectionSetting`:
  [SlotValueSelectionSettingTypeDef](./type_defs.md#slotvalueselectionsettingtypedef)
- `parentSlotTypeSignature`: `str`
- `externalSourceSetting`:
  [ExternalSourceSettingTypeDef](./type_defs.md#externalsourcesettingtypedef)

<a id="createslottyperesponsetypedef"></a>

## CreateSlotTypeResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateSlotTypeResponseTypeDef
```

Required fields:

- `slotTypeId`: `str`
- `slotTypeName`: `str`
- `description`: `str`
- `slotTypeValues`:
  `List`\[[SlotTypeValueTypeDef](./type_defs.md#slottypevaluetypedef)\]
- `valueSelectionSetting`:
  [SlotValueSelectionSettingTypeDef](./type_defs.md#slotvalueselectionsettingtypedef)
- `parentSlotTypeSignature`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `creationDateTime`: `datetime`
- `externalSourceSetting`:
  [ExternalSourceSettingTypeDef](./type_defs.md#externalsourcesettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createuploadurlresponsetypedef"></a>

## CreateUploadUrlResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CreateUploadUrlResponseTypeDef
```

Required fields:

- `importId`: `str`
- `uploadUrl`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="custompayloadtypedef"></a>

## CustomPayloadTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import CustomPayloadTypeDef
```

Required fields:

- `value`: `str`

<a id="dataprivacytypedef"></a>

## DataPrivacyTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DataPrivacyTypeDef
```

Required fields:

- `childDirected`: `bool`

<a id="daterangefiltertypedef"></a>

## DateRangeFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DateRangeFilterTypeDef
```

Required fields:

- `startDateTime`: `datetime`
- `endDateTime`: `datetime`

<a id="deletebotaliasrequestrequesttypedef"></a>

## DeleteBotAliasRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotAliasRequestRequestTypeDef
```

Required fields:

- `botAliasId`: `str`
- `botId`: `str`

Optional fields:

- `skipResourceInUseCheck`: `bool`

<a id="deletebotaliasresponsetypedef"></a>

## DeleteBotAliasResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotAliasResponseTypeDef
```

Required fields:

- `botAliasId`: `str`
- `botId`: `str`
- `botAliasStatus`: [BotAliasStatusType](./literals.md#botaliasstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletebotlocalerequestrequesttypedef"></a>

## DeleteBotLocaleRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotLocaleRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

<a id="deletebotlocaleresponsetypedef"></a>

## DeleteBotLocaleResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotLocaleResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botLocaleStatus`: [BotLocaleStatusType](./literals.md#botlocalestatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletebotrequestrequesttypedef"></a>

## DeleteBotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotRequestRequestTypeDef
```

Required fields:

- `botId`: `str`

Optional fields:

- `skipResourceInUseCheck`: `bool`

<a id="deletebotresponsetypedef"></a>

## DeleteBotResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletebotversionrequestrequesttypedef"></a>

## DeleteBotVersionRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotVersionRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`

Optional fields:

- `skipResourceInUseCheck`: `bool`

<a id="deletebotversionresponsetypedef"></a>

## DeleteBotVersionResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteBotVersionResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteexportrequestrequesttypedef"></a>

## DeleteExportRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteExportRequestRequestTypeDef
```

Required fields:

- `exportId`: `str`

<a id="deleteexportresponsetypedef"></a>

## DeleteExportResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteExportResponseTypeDef
```

Required fields:

- `exportId`: `str`
- `exportStatus`: [ExportStatusType](./literals.md#exportstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteimportrequestrequesttypedef"></a>

## DeleteImportRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteImportRequestRequestTypeDef
```

Required fields:

- `importId`: `str`

<a id="deleteimportresponsetypedef"></a>

## DeleteImportResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteImportResponseTypeDef
```

Required fields:

- `importId`: `str`
- `importStatus`: [ImportStatusType](./literals.md#importstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteintentrequestrequesttypedef"></a>

## DeleteIntentRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteIntentRequestRequestTypeDef
```

Required fields:

- `intentId`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

<a id="deleteresourcepolicyrequestrequesttypedef"></a>

## DeleteResourcePolicyRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteResourcePolicyRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`

Optional fields:

- `expectedRevisionId`: `str`

<a id="deleteresourcepolicyresponsetypedef"></a>

## DeleteResourcePolicyResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteResourcePolicyResponseTypeDef
```

Required fields:

- `resourceArn`: `str`
- `revisionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteresourcepolicystatementrequestrequesttypedef"></a>

## DeleteResourcePolicyStatementRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteResourcePolicyStatementRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `statementId`: `str`

Optional fields:

- `expectedRevisionId`: `str`

<a id="deleteresourcepolicystatementresponsetypedef"></a>

## DeleteResourcePolicyStatementResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteResourcePolicyStatementResponseTypeDef
```

Required fields:

- `resourceArn`: `str`
- `revisionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteslotrequestrequesttypedef"></a>

## DeleteSlotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteSlotRequestRequestTypeDef
```

Required fields:

- `slotId`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`

<a id="deleteslottyperequestrequesttypedef"></a>

## DeleteSlotTypeRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteSlotTypeRequestRequestTypeDef
```

Required fields:

- `slotTypeId`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `skipResourceInUseCheck`: `bool`

<a id="deleteutterancesrequestrequesttypedef"></a>

## DeleteUtterancesRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DeleteUtterancesRequestRequestTypeDef
```

Required fields:

- `botId`: `str`

Optional fields:

- `localeId`: `str`
- `sessionId`: `str`

<a id="describebotaliasrequestrequesttypedef"></a>

## DescribeBotAliasRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotAliasRequestRequestTypeDef
```

Required fields:

- `botAliasId`: `str`
- `botId`: `str`

<a id="describebotaliasresponsetypedef"></a>

## DescribeBotAliasResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotAliasResponseTypeDef
```

Required fields:

- `botAliasId`: `str`
- `botAliasName`: `str`
- `description`: `str`
- `botVersion`: `str`
- `botAliasLocaleSettings`: `Dict`\[`str`,
  [BotAliasLocaleSettingsTypeDef](./type_defs.md#botaliaslocalesettingstypedef)\]
- `conversationLogSettings`:
  [ConversationLogSettingsTypeDef](./type_defs.md#conversationlogsettingstypedef)
- `sentimentAnalysisSettings`:
  [SentimentAnalysisSettingsTypeDef](./type_defs.md#sentimentanalysissettingstypedef)
- `botAliasHistoryEvents`:
  `List`\[[BotAliasHistoryEventTypeDef](./type_defs.md#botaliashistoryeventtypedef)\]
- `botAliasStatus`: [BotAliasStatusType](./literals.md#botaliasstatustype)
- `botId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describebotlocalerequestrequesttypedef"></a>

## DescribeBotLocaleRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotLocaleRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

<a id="describebotlocaleresponsetypedef"></a>

## DescribeBotLocaleResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotLocaleResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `localeName`: `str`
- `description`: `str`
- `nluIntentConfidenceThreshold`: `float`
- `voiceSettings`: [VoiceSettingsTypeDef](./type_defs.md#voicesettingstypedef)
- `intentsCount`: `int`
- `slotTypesCount`: `int`
- `botLocaleStatus`: [BotLocaleStatusType](./literals.md#botlocalestatustype)
- `failureReasons`: `List`\[`str`\]
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `lastBuildSubmittedDateTime`: `datetime`
- `botLocaleHistoryEvents`:
  `List`\[[BotLocaleHistoryEventTypeDef](./type_defs.md#botlocalehistoryeventtypedef)\]
- `recommendedActions`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describebotrecommendationrequestrequesttypedef"></a>

## DescribeBotRecommendationRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotRecommendationRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationId`: `str`

<a id="describebotrecommendationresponsetypedef"></a>

## DescribeBotRecommendationResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotRecommendationResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationStatus`:
  [BotRecommendationStatusType](./literals.md#botrecommendationstatustype)
- `botRecommendationId`: `str`
- `failureReasons`: `List`\[`str`\]
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `transcriptSourceSetting`:
  [TranscriptSourceSettingTypeDef](./type_defs.md#transcriptsourcesettingtypedef)
- `encryptionSetting`:
  [EncryptionSettingTypeDef](./type_defs.md#encryptionsettingtypedef)
- `botRecommendationResults`:
  [BotRecommendationResultsTypeDef](./type_defs.md#botrecommendationresultstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describebotrequestrequesttypedef"></a>

## DescribeBotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotRequestRequestTypeDef
```

Required fields:

- `botId`: `str`

<a id="describebotresponsetypedef"></a>

## DescribeBotResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botName`: `str`
- `description`: `str`
- `roleArn`: `str`
- `dataPrivacy`: [DataPrivacyTypeDef](./type_defs.md#dataprivacytypedef)
- `idleSessionTTLInSeconds`: `int`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describebotversionrequestrequesttypedef"></a>

## DescribeBotVersionRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotVersionRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`

<a id="describebotversionresponsetypedef"></a>

## DescribeBotVersionResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeBotVersionResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botName`: `str`
- `botVersion`: `str`
- `description`: `str`
- `roleArn`: `str`
- `dataPrivacy`: [DataPrivacyTypeDef](./type_defs.md#dataprivacytypedef)
- `idleSessionTTLInSeconds`: `int`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `failureReasons`: `List`\[`str`\]
- `creationDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeexportrequestrequesttypedef"></a>

## DescribeExportRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeExportRequestRequestTypeDef
```

Required fields:

- `exportId`: `str`

<a id="describeexportresponsetypedef"></a>

## DescribeExportResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeExportResponseTypeDef
```

Required fields:

- `exportId`: `str`
- `resourceSpecification`:
  [ExportResourceSpecificationTypeDef](./type_defs.md#exportresourcespecificationtypedef)
- `fileFormat`: `Literal['LexJson']` (see
  [ImportExportFileFormatType](./literals.md#importexportfileformattype))
- `exportStatus`: [ExportStatusType](./literals.md#exportstatustype)
- `failureReasons`: `List`\[`str`\]
- `downloadUrl`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeimportrequestrequesttypedef"></a>

## DescribeImportRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeImportRequestRequestTypeDef
```

Required fields:

- `importId`: `str`

<a id="describeimportresponsetypedef"></a>

## DescribeImportResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeImportResponseTypeDef
```

Required fields:

- `importId`: `str`
- `resourceSpecification`:
  [ImportResourceSpecificationTypeDef](./type_defs.md#importresourcespecificationtypedef)
- `importedResourceId`: `str`
- `importedResourceName`: `str`
- `mergeStrategy`: [MergeStrategyType](./literals.md#mergestrategytype)
- `importStatus`: [ImportStatusType](./literals.md#importstatustype)
- `failureReasons`: `List`\[`str`\]
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeintentrequestrequesttypedef"></a>

## DescribeIntentRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeIntentRequestRequestTypeDef
```

Required fields:

- `intentId`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

<a id="describeintentresponsetypedef"></a>

## DescribeIntentResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeIntentResponseTypeDef
```

Required fields:

- `intentId`: `str`
- `intentName`: `str`
- `description`: `str`
- `parentIntentSignature`: `str`
- `sampleUtterances`:
  `List`\[[SampleUtteranceTypeDef](./type_defs.md#sampleutterancetypedef)\]
- `dialogCodeHook`:
  [DialogCodeHookSettingsTypeDef](./type_defs.md#dialogcodehooksettingstypedef)
- `fulfillmentCodeHook`:
  [FulfillmentCodeHookSettingsTypeDef](./type_defs.md#fulfillmentcodehooksettingstypedef)
- `slotPriorities`:
  `List`\[[SlotPriorityTypeDef](./type_defs.md#slotprioritytypedef)\]
- `intentConfirmationSetting`:
  [IntentConfirmationSettingTypeDef](./type_defs.md#intentconfirmationsettingtypedef)
- `intentClosingSetting`:
  [IntentClosingSettingTypeDef](./type_defs.md#intentclosingsettingtypedef)
- `inputContexts`:
  `List`\[[InputContextTypeDef](./type_defs.md#inputcontexttypedef)\]
- `outputContexts`:
  `List`\[[OutputContextTypeDef](./type_defs.md#outputcontexttypedef)\]
- `kendraConfiguration`:
  [KendraConfigurationTypeDef](./type_defs.md#kendraconfigurationtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeresourcepolicyrequestrequesttypedef"></a>

## DescribeResourcePolicyRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeResourcePolicyRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`

<a id="describeresourcepolicyresponsetypedef"></a>

## DescribeResourcePolicyResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeResourcePolicyResponseTypeDef
```

Required fields:

- `resourceArn`: `str`
- `policy`: `str`
- `revisionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeslotrequestrequesttypedef"></a>

## DescribeSlotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeSlotRequestRequestTypeDef
```

Required fields:

- `slotId`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`

<a id="describeslotresponsetypedef"></a>

## DescribeSlotResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeSlotResponseTypeDef
```

Required fields:

- `slotId`: `str`
- `slotName`: `str`
- `description`: `str`
- `slotTypeId`: `str`
- `valueElicitationSetting`:
  [SlotValueElicitationSettingTypeDef](./type_defs.md#slotvalueelicitationsettingtypedef)
- `obfuscationSetting`:
  [ObfuscationSettingTypeDef](./type_defs.md#obfuscationsettingtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `multipleValuesSetting`:
  [MultipleValuesSettingTypeDef](./type_defs.md#multiplevaluessettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeslottyperequestrequesttypedef"></a>

## DescribeSlotTypeRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeSlotTypeRequestRequestTypeDef
```

Required fields:

- `slotTypeId`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

<a id="describeslottyperesponsetypedef"></a>

## DescribeSlotTypeResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DescribeSlotTypeResponseTypeDef
```

Required fields:

- `slotTypeId`: `str`
- `slotTypeName`: `str`
- `description`: `str`
- `slotTypeValues`:
  `List`\[[SlotTypeValueTypeDef](./type_defs.md#slottypevaluetypedef)\]
- `valueSelectionSetting`:
  [SlotValueSelectionSettingTypeDef](./type_defs.md#slotvalueselectionsettingtypedef)
- `parentSlotTypeSignature`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `externalSourceSetting`:
  [ExternalSourceSettingTypeDef](./type_defs.md#externalsourcesettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dialogcodehooksettingstypedef"></a>

## DialogCodeHookSettingsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import DialogCodeHookSettingsTypeDef
```

Required fields:

- `enabled`: `bool`

<a id="encryptionsettingtypedef"></a>

## EncryptionSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import EncryptionSettingTypeDef
```

Optional fields:

- `kmsKeyArn`: `str`
- `botLocaleExportPassword`: `str`
- `associatedTranscriptsPassword`: `str`

<a id="exportfiltertypedef"></a>

## ExportFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ExportFilterTypeDef
```

Required fields:

- `name`: `Literal['ExportResourceType']` (see
  [ExportFilterNameType](./literals.md#exportfilternametype))
- `values`: `Sequence`\[`str`\]
- `operator`:
  [ExportFilterOperatorType](./literals.md#exportfilteroperatortype)

<a id="exportresourcespecificationtypedef"></a>

## ExportResourceSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ExportResourceSpecificationTypeDef
```

Optional fields:

- `botExportSpecification`:
  [BotExportSpecificationTypeDef](./type_defs.md#botexportspecificationtypedef)
- `botLocaleExportSpecification`:
  [BotLocaleExportSpecificationTypeDef](./type_defs.md#botlocaleexportspecificationtypedef)

<a id="exportsortbytypedef"></a>

## ExportSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ExportSortByTypeDef
```

Required fields:

- `attribute`: `Literal['LastUpdatedDateTime']` (see
  [ExportSortAttributeType](./literals.md#exportsortattributetype))
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="exportsummarytypedef"></a>

## ExportSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ExportSummaryTypeDef
```

Optional fields:

- `exportId`: `str`
- `resourceSpecification`:
  [ExportResourceSpecificationTypeDef](./type_defs.md#exportresourcespecificationtypedef)
- `fileFormat`: `Literal['LexJson']` (see
  [ImportExportFileFormatType](./literals.md#importexportfileformattype))
- `exportStatus`: [ExportStatusType](./literals.md#exportstatustype)
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`

<a id="externalsourcesettingtypedef"></a>

## ExternalSourceSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ExternalSourceSettingTypeDef
```

Optional fields:

- `grammarSlotTypeSetting`:
  [GrammarSlotTypeSettingTypeDef](./type_defs.md#grammarslottypesettingtypedef)

<a id="fulfillmentcodehooksettingstypedef"></a>

## FulfillmentCodeHookSettingsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import FulfillmentCodeHookSettingsTypeDef
```

Required fields:

- `enabled`: `bool`

Optional fields:

- `postFulfillmentStatusSpecification`:
  [PostFulfillmentStatusSpecificationTypeDef](./type_defs.md#postfulfillmentstatusspecificationtypedef)
- `fulfillmentUpdatesSpecification`:
  [FulfillmentUpdatesSpecificationTypeDef](./type_defs.md#fulfillmentupdatesspecificationtypedef)

<a id="fulfillmentstartresponsespecificationtypedef"></a>

## FulfillmentStartResponseSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import FulfillmentStartResponseSpecificationTypeDef
```

Required fields:

- `delayInSeconds`: `int`
- `messageGroups`:
  `Sequence`\[[MessageGroupTypeDef](./type_defs.md#messagegrouptypedef)\]

Optional fields:

- `allowInterrupt`: `bool`

<a id="fulfillmentupdateresponsespecificationtypedef"></a>

## FulfillmentUpdateResponseSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import FulfillmentUpdateResponseSpecificationTypeDef
```

Required fields:

- `frequencyInSeconds`: `int`
- `messageGroups`:
  `Sequence`\[[MessageGroupTypeDef](./type_defs.md#messagegrouptypedef)\]

Optional fields:

- `allowInterrupt`: `bool`

<a id="fulfillmentupdatesspecificationtypedef"></a>

## FulfillmentUpdatesSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import FulfillmentUpdatesSpecificationTypeDef
```

Required fields:

- `active`: `bool`

Optional fields:

- `startResponse`:
  [FulfillmentStartResponseSpecificationTypeDef](./type_defs.md#fulfillmentstartresponsespecificationtypedef)
- `updateResponse`:
  [FulfillmentUpdateResponseSpecificationTypeDef](./type_defs.md#fulfillmentupdateresponsespecificationtypedef)
- `timeoutInSeconds`: `int`

<a id="grammarslottypesettingtypedef"></a>

## GrammarSlotTypeSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import GrammarSlotTypeSettingTypeDef
```

Optional fields:

- `source`:
  [GrammarSlotTypeSourceTypeDef](./type_defs.md#grammarslottypesourcetypedef)

<a id="grammarslottypesourcetypedef"></a>

## GrammarSlotTypeSourceTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import GrammarSlotTypeSourceTypeDef
```

Required fields:

- `s3BucketName`: `str`
- `s3ObjectKey`: `str`

Optional fields:

- `kmsKeyArn`: `str`

<a id="imageresponsecardtypedef"></a>

## ImageResponseCardTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ImageResponseCardTypeDef
```

Required fields:

- `title`: `str`

Optional fields:

- `subtitle`: `str`
- `imageUrl`: `str`
- `buttons`: `Sequence`\[[ButtonTypeDef](./type_defs.md#buttontypedef)\]

<a id="importfiltertypedef"></a>

## ImportFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ImportFilterTypeDef
```

Required fields:

- `name`: `Literal['ImportResourceType']` (see
  [ImportFilterNameType](./literals.md#importfilternametype))
- `values`: `Sequence`\[`str`\]
- `operator`:
  [ImportFilterOperatorType](./literals.md#importfilteroperatortype)

<a id="importresourcespecificationtypedef"></a>

## ImportResourceSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ImportResourceSpecificationTypeDef
```

Optional fields:

- `botImportSpecification`:
  [BotImportSpecificationTypeDef](./type_defs.md#botimportspecificationtypedef)
- `botLocaleImportSpecification`:
  [BotLocaleImportSpecificationTypeDef](./type_defs.md#botlocaleimportspecificationtypedef)

<a id="importsortbytypedef"></a>

## ImportSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ImportSortByTypeDef
```

Required fields:

- `attribute`: `Literal['LastUpdatedDateTime']` (see
  [ImportSortAttributeType](./literals.md#importsortattributetype))
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="importsummarytypedef"></a>

## ImportSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ImportSummaryTypeDef
```

Optional fields:

- `importId`: `str`
- `importedResourceId`: `str`
- `importedResourceName`: `str`
- `importStatus`: [ImportStatusType](./literals.md#importstatustype)
- `mergeStrategy`: [MergeStrategyType](./literals.md#mergestrategytype)
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`

<a id="inputcontexttypedef"></a>

## InputContextTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import InputContextTypeDef
```

Required fields:

- `name`: `str`

<a id="intentclosingsettingtypedef"></a>

## IntentClosingSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import IntentClosingSettingTypeDef
```

Required fields:

- `closingResponse`:
  [ResponseSpecificationTypeDef](./type_defs.md#responsespecificationtypedef)

Optional fields:

- `active`: `bool`

<a id="intentconfirmationsettingtypedef"></a>

## IntentConfirmationSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import IntentConfirmationSettingTypeDef
```

Required fields:

- `promptSpecification`:
  [PromptSpecificationTypeDef](./type_defs.md#promptspecificationtypedef)
- `declinationResponse`:
  [ResponseSpecificationTypeDef](./type_defs.md#responsespecificationtypedef)

Optional fields:

- `active`: `bool`

<a id="intentfiltertypedef"></a>

## IntentFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import IntentFilterTypeDef
```

Required fields:

- `name`: `Literal['IntentName']` (see
  [IntentFilterNameType](./literals.md#intentfilternametype))
- `values`: `Sequence`\[`str`\]
- `operator`:
  [IntentFilterOperatorType](./literals.md#intentfilteroperatortype)

<a id="intentsortbytypedef"></a>

## IntentSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import IntentSortByTypeDef
```

Required fields:

- `attribute`: [IntentSortAttributeType](./literals.md#intentsortattributetype)
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="intentstatisticstypedef"></a>

## IntentStatisticsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import IntentStatisticsTypeDef
```

Optional fields:

- `discoveredIntentCount`: `int`

<a id="intentsummarytypedef"></a>

## IntentSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import IntentSummaryTypeDef
```

Optional fields:

- `intentId`: `str`
- `intentName`: `str`
- `description`: `str`
- `parentIntentSignature`: `str`
- `inputContexts`:
  `List`\[[InputContextTypeDef](./type_defs.md#inputcontexttypedef)\]
- `outputContexts`:
  `List`\[[OutputContextTypeDef](./type_defs.md#outputcontexttypedef)\]
- `lastUpdatedDateTime`: `datetime`

<a id="kendraconfigurationtypedef"></a>

## KendraConfigurationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import KendraConfigurationTypeDef
```

Required fields:

- `kendraIndex`: `str`

Optional fields:

- `queryFilterStringEnabled`: `bool`
- `queryFilterString`: `str`

<a id="lambdacodehooktypedef"></a>

## LambdaCodeHookTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import LambdaCodeHookTypeDef
```

Required fields:

- `lambdaARN`: `str`
- `codeHookInterfaceVersion`: `str`

<a id="lextranscriptfiltertypedef"></a>

## LexTranscriptFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import LexTranscriptFilterTypeDef
```

Optional fields:

- `dateRangeFilter`:
  [DateRangeFilterTypeDef](./type_defs.md#daterangefiltertypedef)

<a id="listaggregatedutterancesrequestrequesttypedef"></a>

## ListAggregatedUtterancesRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListAggregatedUtterancesRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `localeId`: `str`
- `aggregationDuration`:
  [UtteranceAggregationDurationTypeDef](./type_defs.md#utteranceaggregationdurationtypedef)

Optional fields:

- `botAliasId`: `str`
- `botVersion`: `str`
- `sortBy`:
  [AggregatedUtterancesSortByTypeDef](./type_defs.md#aggregatedutterancessortbytypedef)
- `filters`:
  `Sequence`\[[AggregatedUtterancesFilterTypeDef](./type_defs.md#aggregatedutterancesfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listaggregatedutterancesresponsetypedef"></a>

## ListAggregatedUtterancesResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListAggregatedUtterancesResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botAliasId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `aggregationDuration`:
  [UtteranceAggregationDurationTypeDef](./type_defs.md#utteranceaggregationdurationtypedef)
- `aggregationWindowStartTime`: `datetime`
- `aggregationWindowEndTime`: `datetime`
- `aggregationLastRefreshedDateTime`: `datetime`
- `aggregatedUtterancesSummaries`:
  `List`\[[AggregatedUtterancesSummaryTypeDef](./type_defs.md#aggregatedutterancessummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbotaliasesrequestrequesttypedef"></a>

## ListBotAliasesRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotAliasesRequestRequestTypeDef
```

Required fields:

- `botId`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listbotaliasesresponsetypedef"></a>

## ListBotAliasesResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotAliasesResponseTypeDef
```

Required fields:

- `botAliasSummaries`:
  `List`\[[BotAliasSummaryTypeDef](./type_defs.md#botaliassummarytypedef)\]
- `nextToken`: `str`
- `botId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbotlocalesrequestrequesttypedef"></a>

## ListBotLocalesRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotLocalesRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`

Optional fields:

- `sortBy`: [BotLocaleSortByTypeDef](./type_defs.md#botlocalesortbytypedef)
- `filters`:
  `Sequence`\[[BotLocaleFilterTypeDef](./type_defs.md#botlocalefiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listbotlocalesresponsetypedef"></a>

## ListBotLocalesResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotLocalesResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `nextToken`: `str`
- `botLocaleSummaries`:
  `List`\[[BotLocaleSummaryTypeDef](./type_defs.md#botlocalesummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbotrecommendationsrequestrequesttypedef"></a>

## ListBotRecommendationsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotRecommendationsRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listbotrecommendationsresponsetypedef"></a>

## ListBotRecommendationsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotRecommendationsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationSummaries`:
  `List`\[[BotRecommendationSummaryTypeDef](./type_defs.md#botrecommendationsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbotversionsrequestrequesttypedef"></a>

## ListBotVersionsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotVersionsRequestRequestTypeDef
```

Required fields:

- `botId`: `str`

Optional fields:

- `sortBy`: [BotVersionSortByTypeDef](./type_defs.md#botversionsortbytypedef)
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listbotversionsresponsetypedef"></a>

## ListBotVersionsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotVersionsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersionSummaries`:
  `List`\[[BotVersionSummaryTypeDef](./type_defs.md#botversionsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbotsrequestrequesttypedef"></a>

## ListBotsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotsRequestRequestTypeDef
```

Optional fields:

- `sortBy`: [BotSortByTypeDef](./type_defs.md#botsortbytypedef)
- `filters`: `Sequence`\[[BotFilterTypeDef](./type_defs.md#botfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listbotsresponsetypedef"></a>

## ListBotsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBotsResponseTypeDef
```

Required fields:

- `botSummaries`:
  `List`\[[BotSummaryTypeDef](./type_defs.md#botsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbuiltinintentsrequestrequesttypedef"></a>

## ListBuiltInIntentsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBuiltInIntentsRequestRequestTypeDef
```

Required fields:

- `localeId`: `str`

Optional fields:

- `sortBy`:
  [BuiltInIntentSortByTypeDef](./type_defs.md#builtinintentsortbytypedef)
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listbuiltinintentsresponsetypedef"></a>

## ListBuiltInIntentsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBuiltInIntentsResponseTypeDef
```

Required fields:

- `builtInIntentSummaries`:
  `List`\[[BuiltInIntentSummaryTypeDef](./type_defs.md#builtinintentsummarytypedef)\]
- `nextToken`: `str`
- `localeId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listbuiltinslottypesrequestrequesttypedef"></a>

## ListBuiltInSlotTypesRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBuiltInSlotTypesRequestRequestTypeDef
```

Required fields:

- `localeId`: `str`

Optional fields:

- `sortBy`:
  [BuiltInSlotTypeSortByTypeDef](./type_defs.md#builtinslottypesortbytypedef)
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listbuiltinslottypesresponsetypedef"></a>

## ListBuiltInSlotTypesResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListBuiltInSlotTypesResponseTypeDef
```

Required fields:

- `builtInSlotTypeSummaries`:
  `List`\[[BuiltInSlotTypeSummaryTypeDef](./type_defs.md#builtinslottypesummarytypedef)\]
- `nextToken`: `str`
- `localeId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listexportsrequestrequesttypedef"></a>

## ListExportsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListExportsRequestRequestTypeDef
```

Optional fields:

- `botId`: `str`
- `botVersion`: `str`
- `sortBy`: [ExportSortByTypeDef](./type_defs.md#exportsortbytypedef)
- `filters`:
  `Sequence`\[[ExportFilterTypeDef](./type_defs.md#exportfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listexportsresponsetypedef"></a>

## ListExportsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListExportsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `exportSummaries`:
  `List`\[[ExportSummaryTypeDef](./type_defs.md#exportsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listimportsrequestrequesttypedef"></a>

## ListImportsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListImportsRequestRequestTypeDef
```

Optional fields:

- `botId`: `str`
- `botVersion`: `str`
- `sortBy`: [ImportSortByTypeDef](./type_defs.md#importsortbytypedef)
- `filters`:
  `Sequence`\[[ImportFilterTypeDef](./type_defs.md#importfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listimportsresponsetypedef"></a>

## ListImportsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListImportsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `importSummaries`:
  `List`\[[ImportSummaryTypeDef](./type_defs.md#importsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listintentsrequestrequesttypedef"></a>

## ListIntentsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListIntentsRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `sortBy`: [IntentSortByTypeDef](./type_defs.md#intentsortbytypedef)
- `filters`:
  `Sequence`\[[IntentFilterTypeDef](./type_defs.md#intentfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listintentsresponsetypedef"></a>

## ListIntentsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListIntentsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentSummaries`:
  `List`\[[IntentSummaryTypeDef](./type_defs.md#intentsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listrecommendedintentsrequestrequesttypedef"></a>

## ListRecommendedIntentsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListRecommendedIntentsRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationId`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listrecommendedintentsresponsetypedef"></a>

## ListRecommendedIntentsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListRecommendedIntentsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationId`: `str`
- `summaryList`:
  `List`\[[RecommendedIntentSummaryTypeDef](./type_defs.md#recommendedintentsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listslottypesrequestrequesttypedef"></a>

## ListSlotTypesRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListSlotTypesRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `sortBy`: [SlotTypeSortByTypeDef](./type_defs.md#slottypesortbytypedef)
- `filters`:
  `Sequence`\[[SlotTypeFilterTypeDef](./type_defs.md#slottypefiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listslottypesresponsetypedef"></a>

## ListSlotTypesResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListSlotTypesResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `slotTypeSummaries`:
  `List`\[[SlotTypeSummaryTypeDef](./type_defs.md#slottypesummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listslotsrequestrequesttypedef"></a>

## ListSlotsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListSlotsRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`

Optional fields:

- `sortBy`: [SlotSortByTypeDef](./type_defs.md#slotsortbytypedef)
- `filters`:
  `Sequence`\[[SlotFilterTypeDef](./type_defs.md#slotfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

<a id="listslotsresponsetypedef"></a>

## ListSlotsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListSlotsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`
- `slotSummaries`:
  `List`\[[SlotSummaryTypeDef](./type_defs.md#slotsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `resourceARN`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="messagegrouptypedef"></a>

## MessageGroupTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import MessageGroupTypeDef
```

Required fields:

- `message`: [MessageTypeDef](./type_defs.md#messagetypedef)

Optional fields:

- `variations`: `Sequence`\[[MessageTypeDef](./type_defs.md#messagetypedef)\]

<a id="messagetypedef"></a>

## MessageTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import MessageTypeDef
```

Optional fields:

- `plainTextMessage`:
  [PlainTextMessageTypeDef](./type_defs.md#plaintextmessagetypedef)
- `customPayload`: [CustomPayloadTypeDef](./type_defs.md#custompayloadtypedef)
- `ssmlMessage`: [SSMLMessageTypeDef](./type_defs.md#ssmlmessagetypedef)
- `imageResponseCard`:
  [ImageResponseCardTypeDef](./type_defs.md#imageresponsecardtypedef)

<a id="multiplevaluessettingtypedef"></a>

## MultipleValuesSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import MultipleValuesSettingTypeDef
```

Optional fields:

- `allowMultipleValues`: `bool`

<a id="obfuscationsettingtypedef"></a>

## ObfuscationSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ObfuscationSettingTypeDef
```

Required fields:

- `obfuscationSettingType`:
  [ObfuscationSettingTypeType](./literals.md#obfuscationsettingtypetype)

<a id="outputcontexttypedef"></a>

## OutputContextTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import OutputContextTypeDef
```

Required fields:

- `name`: `str`
- `timeToLiveInSeconds`: `int`
- `turnsToLive`: `int`

<a id="pathformattypedef"></a>

## PathFormatTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import PathFormatTypeDef
```

Optional fields:

- `objectPrefixes`: `List`\[`str`\]

<a id="plaintextmessagetypedef"></a>

## PlainTextMessageTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import PlainTextMessageTypeDef
```

Required fields:

- `value`: `str`

<a id="postfulfillmentstatusspecificationtypedef"></a>

## PostFulfillmentStatusSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import PostFulfillmentStatusSpecificationTypeDef
```

Optional fields:

- `successResponse`:
  [ResponseSpecificationTypeDef](./type_defs.md#responsespecificationtypedef)
- `failureResponse`:
  [ResponseSpecificationTypeDef](./type_defs.md#responsespecificationtypedef)
- `timeoutResponse`:
  [ResponseSpecificationTypeDef](./type_defs.md#responsespecificationtypedef)

<a id="principaltypedef"></a>

## PrincipalTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import PrincipalTypeDef
```

Optional fields:

- `service`: `str`
- `arn`: `str`

<a id="promptspecificationtypedef"></a>

## PromptSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import PromptSpecificationTypeDef
```

Required fields:

- `messageGroups`:
  `Sequence`\[[MessageGroupTypeDef](./type_defs.md#messagegrouptypedef)\]
- `maxRetries`: `int`

Optional fields:

- `allowInterrupt`: `bool`

<a id="recommendedintentsummarytypedef"></a>

## RecommendedIntentSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import RecommendedIntentSummaryTypeDef
```

Optional fields:

- `intentId`: `str`
- `intentName`: `str`
- `sampleUtterancesCount`: `int`

<a id="relativeaggregationdurationtypedef"></a>

## RelativeAggregationDurationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import RelativeAggregationDurationTypeDef
```

Required fields:

- `timeDimension`: [TimeDimensionType](./literals.md#timedimensiontype)
- `timeValue`: `int`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="responsespecificationtypedef"></a>

## ResponseSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import ResponseSpecificationTypeDef
```

Required fields:

- `messageGroups`:
  `Sequence`\[[MessageGroupTypeDef](./type_defs.md#messagegrouptypedef)\]

Optional fields:

- `allowInterrupt`: `bool`

<a id="s3bucketlogdestinationtypedef"></a>

## S3BucketLogDestinationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import S3BucketLogDestinationTypeDef
```

Required fields:

- `s3BucketArn`: `str`
- `logPrefix`: `str`

Optional fields:

- `kmsKeyArn`: `str`

<a id="s3buckettranscriptsourcetypedef"></a>

## S3BucketTranscriptSourceTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import S3BucketTranscriptSourceTypeDef
```

Required fields:

- `s3BucketName`: `str`
- `transcriptFormat`: `Literal['Lex']` (see
  [TranscriptFormatType](./literals.md#transcriptformattype))

Optional fields:

- `pathFormat`: [PathFormatTypeDef](./type_defs.md#pathformattypedef)
- `transcriptFilter`:
  [TranscriptFilterTypeDef](./type_defs.md#transcriptfiltertypedef)
- `kmsKeyArn`: `str`

<a id="ssmlmessagetypedef"></a>

## SSMLMessageTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SSMLMessageTypeDef
```

Required fields:

- `value`: `str`

<a id="sampleutterancetypedef"></a>

## SampleUtteranceTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SampleUtteranceTypeDef
```

Required fields:

- `utterance`: `str`

<a id="samplevaluetypedef"></a>

## SampleValueTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SampleValueTypeDef
```

Required fields:

- `value`: `str`

<a id="searchassociatedtranscriptsrequestrequesttypedef"></a>

## SearchAssociatedTranscriptsRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SearchAssociatedTranscriptsRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationId`: `str`
- `filters`:
  `Sequence`\[[AssociatedTranscriptFilterTypeDef](./type_defs.md#associatedtranscriptfiltertypedef)\]

Optional fields:

- `searchOrder`: [SearchOrderType](./literals.md#searchordertype)
- `maxResults`: `int`
- `nextIndex`: `int`

<a id="searchassociatedtranscriptsresponsetypedef"></a>

## SearchAssociatedTranscriptsResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SearchAssociatedTranscriptsResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationId`: `str`
- `nextIndex`: `int`
- `associatedTranscripts`:
  `List`\[[AssociatedTranscriptTypeDef](./type_defs.md#associatedtranscripttypedef)\]
- `totalResults`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="sentimentanalysissettingstypedef"></a>

## SentimentAnalysisSettingsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SentimentAnalysisSettingsTypeDef
```

Required fields:

- `detectSentiment`: `bool`

<a id="slotdefaultvaluespecificationtypedef"></a>

## SlotDefaultValueSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotDefaultValueSpecificationTypeDef
```

Required fields:

- `defaultValueList`:
  `Sequence`\[[SlotDefaultValueTypeDef](./type_defs.md#slotdefaultvaluetypedef)\]

<a id="slotdefaultvaluetypedef"></a>

## SlotDefaultValueTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotDefaultValueTypeDef
```

Required fields:

- `defaultValue`: `str`

<a id="slotfiltertypedef"></a>

## SlotFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotFilterTypeDef
```

Required fields:

- `name`: `Literal['SlotName']` (see
  [SlotFilterNameType](./literals.md#slotfilternametype))
- `values`: `Sequence`\[`str`\]
- `operator`: [SlotFilterOperatorType](./literals.md#slotfilteroperatortype)

<a id="slotprioritytypedef"></a>

## SlotPriorityTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotPriorityTypeDef
```

Required fields:

- `priority`: `int`
- `slotId`: `str`

<a id="slotsortbytypedef"></a>

## SlotSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotSortByTypeDef
```

Required fields:

- `attribute`: [SlotSortAttributeType](./literals.md#slotsortattributetype)
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="slotsummarytypedef"></a>

## SlotSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotSummaryTypeDef
```

Optional fields:

- `slotId`: `str`
- `slotName`: `str`
- `description`: `str`
- `slotConstraint`: [SlotConstraintType](./literals.md#slotconstrainttype)
- `slotTypeId`: `str`
- `valueElicitationPromptSpecification`:
  [PromptSpecificationTypeDef](./type_defs.md#promptspecificationtypedef)
- `lastUpdatedDateTime`: `datetime`

<a id="slottypefiltertypedef"></a>

## SlotTypeFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotTypeFilterTypeDef
```

Required fields:

- `name`: [SlotTypeFilterNameType](./literals.md#slottypefilternametype)
- `values`: `Sequence`\[`str`\]
- `operator`:
  [SlotTypeFilterOperatorType](./literals.md#slottypefilteroperatortype)

<a id="slottypesortbytypedef"></a>

## SlotTypeSortByTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotTypeSortByTypeDef
```

Required fields:

- `attribute`:
  [SlotTypeSortAttributeType](./literals.md#slottypesortattributetype)
- `order`: [SortOrderType](./literals.md#sortordertype)

<a id="slottypestatisticstypedef"></a>

## SlotTypeStatisticsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotTypeStatisticsTypeDef
```

Optional fields:

- `discoveredSlotTypeCount`: `int`

<a id="slottypesummarytypedef"></a>

## SlotTypeSummaryTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotTypeSummaryTypeDef
```

Optional fields:

- `slotTypeId`: `str`
- `slotTypeName`: `str`
- `description`: `str`
- `parentSlotTypeSignature`: `str`
- `lastUpdatedDateTime`: `datetime`
- `slotTypeCategory`:
  [SlotTypeCategoryType](./literals.md#slottypecategorytype)

<a id="slottypevaluetypedef"></a>

## SlotTypeValueTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotTypeValueTypeDef
```

Optional fields:

- `sampleValue`: [SampleValueTypeDef](./type_defs.md#samplevaluetypedef)
- `synonyms`:
  `Sequence`\[[SampleValueTypeDef](./type_defs.md#samplevaluetypedef)\]

<a id="slotvalueelicitationsettingtypedef"></a>

## SlotValueElicitationSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotValueElicitationSettingTypeDef
```

Required fields:

- `slotConstraint`: [SlotConstraintType](./literals.md#slotconstrainttype)

Optional fields:

- `defaultValueSpecification`:
  [SlotDefaultValueSpecificationTypeDef](./type_defs.md#slotdefaultvaluespecificationtypedef)
- `promptSpecification`:
  [PromptSpecificationTypeDef](./type_defs.md#promptspecificationtypedef)
- `sampleUtterances`:
  `Sequence`\[[SampleUtteranceTypeDef](./type_defs.md#sampleutterancetypedef)\]
- `waitAndContinueSpecification`:
  [WaitAndContinueSpecificationTypeDef](./type_defs.md#waitandcontinuespecificationtypedef)

<a id="slotvalueregexfiltertypedef"></a>

## SlotValueRegexFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotValueRegexFilterTypeDef
```

Required fields:

- `pattern`: `str`

<a id="slotvalueselectionsettingtypedef"></a>

## SlotValueSelectionSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import SlotValueSelectionSettingTypeDef
```

Required fields:

- `resolutionStrategy`:
  [SlotValueResolutionStrategyType](./literals.md#slotvalueresolutionstrategytype)

Optional fields:

- `regexFilter`:
  [SlotValueRegexFilterTypeDef](./type_defs.md#slotvalueregexfiltertypedef)

<a id="startbotrecommendationrequestrequesttypedef"></a>

## StartBotRecommendationRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import StartBotRecommendationRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `transcriptSourceSetting`:
  [TranscriptSourceSettingTypeDef](./type_defs.md#transcriptsourcesettingtypedef)

Optional fields:

- `encryptionSetting`:
  [EncryptionSettingTypeDef](./type_defs.md#encryptionsettingtypedef)

<a id="startbotrecommendationresponsetypedef"></a>

## StartBotRecommendationResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import StartBotRecommendationResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationStatus`:
  [BotRecommendationStatusType](./literals.md#botrecommendationstatustype)
- `botRecommendationId`: `str`
- `creationDateTime`: `datetime`
- `transcriptSourceSetting`:
  [TranscriptSourceSettingTypeDef](./type_defs.md#transcriptsourcesettingtypedef)
- `encryptionSetting`:
  [EncryptionSettingTypeDef](./type_defs.md#encryptionsettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startimportrequestrequesttypedef"></a>

## StartImportRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import StartImportRequestRequestTypeDef
```

Required fields:

- `importId`: `str`
- `resourceSpecification`:
  [ImportResourceSpecificationTypeDef](./type_defs.md#importresourcespecificationtypedef)
- `mergeStrategy`: [MergeStrategyType](./literals.md#mergestrategytype)

Optional fields:

- `filePassword`: `str`

<a id="startimportresponsetypedef"></a>

## StartImportResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import StartImportResponseTypeDef
```

Required fields:

- `importId`: `str`
- `resourceSpecification`:
  [ImportResourceSpecificationTypeDef](./type_defs.md#importresourcespecificationtypedef)
- `mergeStrategy`: [MergeStrategyType](./literals.md#mergestrategytype)
- `importStatus`: [ImportStatusType](./literals.md#importstatustype)
- `creationDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stillwaitingresponsespecificationtypedef"></a>

## StillWaitingResponseSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import StillWaitingResponseSpecificationTypeDef
```

Required fields:

- `messageGroups`:
  `Sequence`\[[MessageGroupTypeDef](./type_defs.md#messagegrouptypedef)\]
- `frequencyInSeconds`: `int`
- `timeoutInSeconds`: `int`

Optional fields:

- `allowInterrupt`: `bool`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `resourceARN`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

<a id="textlogdestinationtypedef"></a>

## TextLogDestinationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import TextLogDestinationTypeDef
```

Required fields:

- `cloudWatch`:
  [CloudWatchLogGroupLogDestinationTypeDef](./type_defs.md#cloudwatchloggrouplogdestinationtypedef)

<a id="textlogsettingtypedef"></a>

## TextLogSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import TextLogSettingTypeDef
```

Required fields:

- `enabled`: `bool`
- `destination`:
  [TextLogDestinationTypeDef](./type_defs.md#textlogdestinationtypedef)

<a id="transcriptfiltertypedef"></a>

## TranscriptFilterTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import TranscriptFilterTypeDef
```

Optional fields:

- `lexTranscriptFilter`:
  [LexTranscriptFilterTypeDef](./type_defs.md#lextranscriptfiltertypedef)

<a id="transcriptsourcesettingtypedef"></a>

## TranscriptSourceSettingTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import TranscriptSourceSettingTypeDef
```

Optional fields:

- `s3BucketTranscriptSource`:
  [S3BucketTranscriptSourceTypeDef](./type_defs.md#s3buckettranscriptsourcetypedef)

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `resourceARN`: `str`
- `tagKeys`: `Sequence`\[`str`\]

<a id="updatebotaliasrequestrequesttypedef"></a>

## UpdateBotAliasRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotAliasRequestRequestTypeDef
```

Required fields:

- `botAliasId`: `str`
- `botAliasName`: `str`
- `botId`: `str`

Optional fields:

- `description`: `str`
- `botVersion`: `str`
- `botAliasLocaleSettings`: `Mapping`\[`str`,
  [BotAliasLocaleSettingsTypeDef](./type_defs.md#botaliaslocalesettingstypedef)\]
- `conversationLogSettings`:
  [ConversationLogSettingsTypeDef](./type_defs.md#conversationlogsettingstypedef)
- `sentimentAnalysisSettings`:
  [SentimentAnalysisSettingsTypeDef](./type_defs.md#sentimentanalysissettingstypedef)

<a id="updatebotaliasresponsetypedef"></a>

## UpdateBotAliasResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotAliasResponseTypeDef
```

Required fields:

- `botAliasId`: `str`
- `botAliasName`: `str`
- `description`: `str`
- `botVersion`: `str`
- `botAliasLocaleSettings`: `Dict`\[`str`,
  [BotAliasLocaleSettingsTypeDef](./type_defs.md#botaliaslocalesettingstypedef)\]
- `conversationLogSettings`:
  [ConversationLogSettingsTypeDef](./type_defs.md#conversationlogsettingstypedef)
- `sentimentAnalysisSettings`:
  [SentimentAnalysisSettingsTypeDef](./type_defs.md#sentimentanalysissettingstypedef)
- `botAliasStatus`: [BotAliasStatusType](./literals.md#botaliasstatustype)
- `botId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatebotlocalerequestrequesttypedef"></a>

## UpdateBotLocaleRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotLocaleRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `nluIntentConfidenceThreshold`: `float`

Optional fields:

- `description`: `str`
- `voiceSettings`: [VoiceSettingsTypeDef](./type_defs.md#voicesettingstypedef)

<a id="updatebotlocaleresponsetypedef"></a>

## UpdateBotLocaleResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotLocaleResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `localeName`: `str`
- `description`: `str`
- `nluIntentConfidenceThreshold`: `float`
- `voiceSettings`: [VoiceSettingsTypeDef](./type_defs.md#voicesettingstypedef)
- `botLocaleStatus`: [BotLocaleStatusType](./literals.md#botlocalestatustype)
- `failureReasons`: `List`\[`str`\]
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `recommendedActions`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatebotrecommendationrequestrequesttypedef"></a>

## UpdateBotRecommendationRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotRecommendationRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationId`: `str`
- `encryptionSetting`:
  [EncryptionSettingTypeDef](./type_defs.md#encryptionsettingtypedef)

<a id="updatebotrecommendationresponsetypedef"></a>

## UpdateBotRecommendationResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotRecommendationResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `botRecommendationStatus`:
  [BotRecommendationStatusType](./literals.md#botrecommendationstatustype)
- `botRecommendationId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `transcriptSourceSetting`:
  [TranscriptSourceSettingTypeDef](./type_defs.md#transcriptsourcesettingtypedef)
- `encryptionSetting`:
  [EncryptionSettingTypeDef](./type_defs.md#encryptionsettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatebotrequestrequesttypedef"></a>

## UpdateBotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botName`: `str`
- `roleArn`: `str`
- `dataPrivacy`: [DataPrivacyTypeDef](./type_defs.md#dataprivacytypedef)
- `idleSessionTTLInSeconds`: `int`

Optional fields:

- `description`: `str`

<a id="updatebotresponsetypedef"></a>

## UpdateBotResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateBotResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botName`: `str`
- `description`: `str`
- `roleArn`: `str`
- `dataPrivacy`: [DataPrivacyTypeDef](./type_defs.md#dataprivacytypedef)
- `idleSessionTTLInSeconds`: `int`
- `botStatus`: [BotStatusType](./literals.md#botstatustype)
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateexportrequestrequesttypedef"></a>

## UpdateExportRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateExportRequestRequestTypeDef
```

Required fields:

- `exportId`: `str`

Optional fields:

- `filePassword`: `str`

<a id="updateexportresponsetypedef"></a>

## UpdateExportResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateExportResponseTypeDef
```

Required fields:

- `exportId`: `str`
- `resourceSpecification`:
  [ExportResourceSpecificationTypeDef](./type_defs.md#exportresourcespecificationtypedef)
- `fileFormat`: `Literal['LexJson']` (see
  [ImportExportFileFormatType](./literals.md#importexportfileformattype))
- `exportStatus`: [ExportStatusType](./literals.md#exportstatustype)
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateintentrequestrequesttypedef"></a>

## UpdateIntentRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateIntentRequestRequestTypeDef
```

Required fields:

- `intentId`: `str`
- `intentName`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `description`: `str`
- `parentIntentSignature`: `str`
- `sampleUtterances`:
  `Sequence`\[[SampleUtteranceTypeDef](./type_defs.md#sampleutterancetypedef)\]
- `dialogCodeHook`:
  [DialogCodeHookSettingsTypeDef](./type_defs.md#dialogcodehooksettingstypedef)
- `fulfillmentCodeHook`:
  [FulfillmentCodeHookSettingsTypeDef](./type_defs.md#fulfillmentcodehooksettingstypedef)
- `slotPriorities`:
  `Sequence`\[[SlotPriorityTypeDef](./type_defs.md#slotprioritytypedef)\]
- `intentConfirmationSetting`:
  [IntentConfirmationSettingTypeDef](./type_defs.md#intentconfirmationsettingtypedef)
- `intentClosingSetting`:
  [IntentClosingSettingTypeDef](./type_defs.md#intentclosingsettingtypedef)
- `inputContexts`:
  `Sequence`\[[InputContextTypeDef](./type_defs.md#inputcontexttypedef)\]
- `outputContexts`:
  `Sequence`\[[OutputContextTypeDef](./type_defs.md#outputcontexttypedef)\]
- `kendraConfiguration`:
  [KendraConfigurationTypeDef](./type_defs.md#kendraconfigurationtypedef)

<a id="updateintentresponsetypedef"></a>

## UpdateIntentResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateIntentResponseTypeDef
```

Required fields:

- `intentId`: `str`
- `intentName`: `str`
- `description`: `str`
- `parentIntentSignature`: `str`
- `sampleUtterances`:
  `List`\[[SampleUtteranceTypeDef](./type_defs.md#sampleutterancetypedef)\]
- `dialogCodeHook`:
  [DialogCodeHookSettingsTypeDef](./type_defs.md#dialogcodehooksettingstypedef)
- `fulfillmentCodeHook`:
  [FulfillmentCodeHookSettingsTypeDef](./type_defs.md#fulfillmentcodehooksettingstypedef)
- `slotPriorities`:
  `List`\[[SlotPriorityTypeDef](./type_defs.md#slotprioritytypedef)\]
- `intentConfirmationSetting`:
  [IntentConfirmationSettingTypeDef](./type_defs.md#intentconfirmationsettingtypedef)
- `intentClosingSetting`:
  [IntentClosingSettingTypeDef](./type_defs.md#intentclosingsettingtypedef)
- `inputContexts`:
  `List`\[[InputContextTypeDef](./type_defs.md#inputcontexttypedef)\]
- `outputContexts`:
  `List`\[[OutputContextTypeDef](./type_defs.md#outputcontexttypedef)\]
- `kendraConfiguration`:
  [KendraConfigurationTypeDef](./type_defs.md#kendraconfigurationtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateresourcepolicyrequestrequesttypedef"></a>

## UpdateResourcePolicyRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateResourcePolicyRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `policy`: `str`

Optional fields:

- `expectedRevisionId`: `str`

<a id="updateresourcepolicyresponsetypedef"></a>

## UpdateResourcePolicyResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateResourcePolicyResponseTypeDef
```

Required fields:

- `resourceArn`: `str`
- `revisionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateslotrequestrequesttypedef"></a>

## UpdateSlotRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateSlotRequestRequestTypeDef
```

Required fields:

- `slotId`: `str`
- `slotName`: `str`
- `slotTypeId`: `str`
- `valueElicitationSetting`:
  [SlotValueElicitationSettingTypeDef](./type_defs.md#slotvalueelicitationsettingtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`

Optional fields:

- `description`: `str`
- `obfuscationSetting`:
  [ObfuscationSettingTypeDef](./type_defs.md#obfuscationsettingtypedef)
- `multipleValuesSetting`:
  [MultipleValuesSettingTypeDef](./type_defs.md#multiplevaluessettingtypedef)

<a id="updateslotresponsetypedef"></a>

## UpdateSlotResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateSlotResponseTypeDef
```

Required fields:

- `slotId`: `str`
- `slotName`: `str`
- `description`: `str`
- `slotTypeId`: `str`
- `valueElicitationSetting`:
  [SlotValueElicitationSettingTypeDef](./type_defs.md#slotvalueelicitationsettingtypedef)
- `obfuscationSetting`:
  [ObfuscationSettingTypeDef](./type_defs.md#obfuscationsettingtypedef)
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `intentId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `multipleValuesSetting`:
  [MultipleValuesSettingTypeDef](./type_defs.md#multiplevaluessettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateslottyperequestrequesttypedef"></a>

## UpdateSlotTypeRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateSlotTypeRequestRequestTypeDef
```

Required fields:

- `slotTypeId`: `str`
- `slotTypeName`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`

Optional fields:

- `description`: `str`
- `slotTypeValues`:
  `Sequence`\[[SlotTypeValueTypeDef](./type_defs.md#slottypevaluetypedef)\]
- `valueSelectionSetting`:
  [SlotValueSelectionSettingTypeDef](./type_defs.md#slotvalueselectionsettingtypedef)
- `parentSlotTypeSignature`: `str`
- `externalSourceSetting`:
  [ExternalSourceSettingTypeDef](./type_defs.md#externalsourcesettingtypedef)

<a id="updateslottyperesponsetypedef"></a>

## UpdateSlotTypeResponseTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UpdateSlotTypeResponseTypeDef
```

Required fields:

- `slotTypeId`: `str`
- `slotTypeName`: `str`
- `description`: `str`
- `slotTypeValues`:
  `List`\[[SlotTypeValueTypeDef](./type_defs.md#slottypevaluetypedef)\]
- `valueSelectionSetting`:
  [SlotValueSelectionSettingTypeDef](./type_defs.md#slotvalueselectionsettingtypedef)
- `parentSlotTypeSignature`: `str`
- `botId`: `str`
- `botVersion`: `str`
- `localeId`: `str`
- `creationDateTime`: `datetime`
- `lastUpdatedDateTime`: `datetime`
- `externalSourceSetting`:
  [ExternalSourceSettingTypeDef](./type_defs.md#externalsourcesettingtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="utteranceaggregationdurationtypedef"></a>

## UtteranceAggregationDurationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import UtteranceAggregationDurationTypeDef
```

Required fields:

- `relativeAggregationDuration`:
  [RelativeAggregationDurationTypeDef](./type_defs.md#relativeaggregationdurationtypedef)

<a id="voicesettingstypedef"></a>

## VoiceSettingsTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import VoiceSettingsTypeDef
```

Required fields:

- `voiceId`: `str`

Optional fields:

- `engine`: [VoiceEngineType](./literals.md#voiceenginetype)

<a id="waitandcontinuespecificationtypedef"></a>

## WaitAndContinueSpecificationTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import WaitAndContinueSpecificationTypeDef
```

Required fields:

- `waitingResponse`:
  [ResponseSpecificationTypeDef](./type_defs.md#responsespecificationtypedef)
- `continueResponse`:
  [ResponseSpecificationTypeDef](./type_defs.md#responsespecificationtypedef)

Optional fields:

- `stillWaitingResponse`:
  [StillWaitingResponseSpecificationTypeDef](./type_defs.md#stillwaitingresponsespecificationtypedef)
- `active`: `bool`

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_lexv2_models.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`
