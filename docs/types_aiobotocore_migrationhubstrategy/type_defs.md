<a id="typed-dictionaries-for-aiobotocore-migrationhubstrategyrecommendations-module"></a>

# Typed dictionaries for aiobotocore MigrationHubStrategyRecommendations module

> [Index](../README.md) > [MigrationHubStrategyRecommendations](./README.md) >
> Typed dictionaries

Auto-generated documentation for
[MigrationHubStrategyRecommendations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations)
type annotations stubs module
[types-aiobotocore-migrationhubstrategy](https://pypi.org/project/types-aiobotocore-migrationhubstrategy/).

- [Typed dictionaries for aiobotocore MigrationHubStrategyRecommendations module](#typed-dictionaries-for-aiobotocore-migrationhubstrategyrecommendations-module)
  - [AntipatternSeveritySummaryTypeDef](#antipatternseveritysummarytypedef)
  - [ApplicationComponentDetailTypeDef](#applicationcomponentdetailtypedef)
  - [ApplicationComponentStrategyTypeDef](#applicationcomponentstrategytypedef)
  - [ApplicationComponentSummaryTypeDef](#applicationcomponentsummarytypedef)
  - [ApplicationPreferencesTypeDef](#applicationpreferencestypedef)
  - [AssessmentSummaryTypeDef](#assessmentsummarytypedef)
  - [AssociatedApplicationTypeDef](#associatedapplicationtypedef)
  - [AwsManagedResourcesTypeDef](#awsmanagedresourcestypedef)
  - [BusinessGoalsTypeDef](#businessgoalstypedef)
  - [CollectorTypeDef](#collectortypedef)
  - [DataCollectionDetailsTypeDef](#datacollectiondetailstypedef)
  - [DatabaseConfigDetailTypeDef](#databaseconfigdetailtypedef)
  - [DatabaseMigrationPreferenceTypeDef](#databasemigrationpreferencetypedef)
  - [DatabasePreferencesTypeDef](#databasepreferencestypedef)
  - [GetApplicationComponentDetailsRequestRequestTypeDef](#getapplicationcomponentdetailsrequestrequesttypedef)
  - [GetApplicationComponentDetailsResponseTypeDef](#getapplicationcomponentdetailsresponsetypedef)
  - [GetApplicationComponentStrategiesRequestRequestTypeDef](#getapplicationcomponentstrategiesrequestrequesttypedef)
  - [GetApplicationComponentStrategiesResponseTypeDef](#getapplicationcomponentstrategiesresponsetypedef)
  - [GetAssessmentRequestRequestTypeDef](#getassessmentrequestrequesttypedef)
  - [GetAssessmentResponseTypeDef](#getassessmentresponsetypedef)
  - [GetImportFileTaskRequestRequestTypeDef](#getimportfiletaskrequestrequesttypedef)
  - [GetImportFileTaskResponseTypeDef](#getimportfiletaskresponsetypedef)
  - [GetPortfolioPreferencesResponseTypeDef](#getportfoliopreferencesresponsetypedef)
  - [GetPortfolioSummaryResponseTypeDef](#getportfoliosummaryresponsetypedef)
  - [GetRecommendationReportDetailsRequestRequestTypeDef](#getrecommendationreportdetailsrequestrequesttypedef)
  - [GetRecommendationReportDetailsResponseTypeDef](#getrecommendationreportdetailsresponsetypedef)
  - [GetServerDetailsRequestRequestTypeDef](#getserverdetailsrequestrequesttypedef)
  - [GetServerDetailsResponseTypeDef](#getserverdetailsresponsetypedef)
  - [GetServerStrategiesRequestRequestTypeDef](#getserverstrategiesrequestrequesttypedef)
  - [GetServerStrategiesResponseTypeDef](#getserverstrategiesresponsetypedef)
  - [GroupTypeDef](#grouptypedef)
  - [HeterogeneousTypeDef](#heterogeneoustypedef)
  - [HomogeneousTypeDef](#homogeneoustypedef)
  - [ImportFileTaskInformationTypeDef](#importfiletaskinformationtypedef)
  - [ListApplicationComponentsRequestRequestTypeDef](#listapplicationcomponentsrequestrequesttypedef)
  - [ListApplicationComponentsResponseTypeDef](#listapplicationcomponentsresponsetypedef)
  - [ListCollectorsRequestRequestTypeDef](#listcollectorsrequestrequesttypedef)
  - [ListCollectorsResponseTypeDef](#listcollectorsresponsetypedef)
  - [ListImportFileTaskRequestRequestTypeDef](#listimportfiletaskrequestrequesttypedef)
  - [ListImportFileTaskResponseTypeDef](#listimportfiletaskresponsetypedef)
  - [ListServersRequestRequestTypeDef](#listserversrequestrequesttypedef)
  - [ListServersResponseTypeDef](#listserversresponsetypedef)
  - [ManagementPreferenceTypeDef](#managementpreferencetypedef)
  - [NetworkInfoTypeDef](#networkinfotypedef)
  - [NoDatabaseMigrationPreferenceTypeDef](#nodatabasemigrationpreferencetypedef)
  - [NoManagementPreferenceTypeDef](#nomanagementpreferencetypedef)
  - [OSInfoTypeDef](#osinfotypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PrioritizeBusinessGoalsTypeDef](#prioritizebusinessgoalstypedef)
  - [PutPortfolioPreferencesRequestRequestTypeDef](#putportfoliopreferencesrequestrequesttypedef)
  - [RecommendationReportDetailsTypeDef](#recommendationreportdetailstypedef)
  - [RecommendationSetTypeDef](#recommendationsettypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3ObjectTypeDef](#s3objecttypedef)
  - [SelfManageResourcesTypeDef](#selfmanageresourcestypedef)
  - [ServerDetailTypeDef](#serverdetailtypedef)
  - [ServerStrategyTypeDef](#serverstrategytypedef)
  - [ServerSummaryTypeDef](#serversummarytypedef)
  - [SourceCodeRepositoryTypeDef](#sourcecoderepositorytypedef)
  - [SourceCodeTypeDef](#sourcecodetypedef)
  - [StartAssessmentRequestRequestTypeDef](#startassessmentrequestrequesttypedef)
  - [StartAssessmentResponseTypeDef](#startassessmentresponsetypedef)
  - [StartImportFileTaskRequestRequestTypeDef](#startimportfiletaskrequestrequesttypedef)
  - [StartImportFileTaskResponseTypeDef](#startimportfiletaskresponsetypedef)
  - [StartRecommendationReportGenerationRequestRequestTypeDef](#startrecommendationreportgenerationrequestrequesttypedef)
  - [StartRecommendationReportGenerationResponseTypeDef](#startrecommendationreportgenerationresponsetypedef)
  - [StopAssessmentRequestRequestTypeDef](#stopassessmentrequestrequesttypedef)
  - [StrategyOptionTypeDef](#strategyoptiontypedef)
  - [StrategySummaryTypeDef](#strategysummarytypedef)
  - [SystemInfoTypeDef](#systeminfotypedef)
  - [TransformationToolTypeDef](#transformationtooltypedef)
  - [UpdateApplicationComponentConfigRequestRequestTypeDef](#updateapplicationcomponentconfigrequestrequesttypedef)
  - [UpdateServerConfigRequestRequestTypeDef](#updateserverconfigrequestrequesttypedef)

<a id="antipatternseveritysummarytypedef"></a>

## AntipatternSeveritySummaryTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import AntipatternSeveritySummaryTypeDef
```

Optional fields:

- `count`: `int`
- `severity`: [SeverityType](./literals.md#severitytype)

<a id="applicationcomponentdetailtypedef"></a>

## ApplicationComponentDetailTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ApplicationComponentDetailTypeDef
```

Optional fields:

- `analysisStatus`:
  [SrcCodeOrDbAnalysisStatusType](./literals.md#srccodeordbanalysisstatustype)
- `antipatternReportS3Object`:
  [S3ObjectTypeDef](./type_defs.md#s3objecttypedef)
- `antipatternReportStatus`:
  [AntipatternReportStatusType](./literals.md#antipatternreportstatustype)
- `antipatternReportStatusMessage`: `str`
- `appType`: [AppTypeType](./literals.md#apptypetype)
- `associatedServerId`: `str`
- `databaseConfigDetail`:
  [DatabaseConfigDetailTypeDef](./type_defs.md#databaseconfigdetailtypedef)
- `id`: `str`
- `inclusionStatus`: [InclusionStatusType](./literals.md#inclusionstatustype)
- `lastAnalyzedTimestamp`: `datetime`
- `listAntipatternSeveritySummary`:
  `List`\[[AntipatternSeveritySummaryTypeDef](./type_defs.md#antipatternseveritysummarytypedef)\]
- `moreServerAssociationExists`: `bool`
- `name`: `str`
- `osDriver`: `str`
- `osVersion`: `str`
- `recommendationSet`:
  [RecommendationSetTypeDef](./type_defs.md#recommendationsettypedef)
- `resourceSubType`: [ResourceSubTypeType](./literals.md#resourcesubtypetype)
- `sourceCodeRepositories`:
  `List`\[[SourceCodeRepositoryTypeDef](./type_defs.md#sourcecoderepositorytypedef)\]
- `statusMessage`: `str`

<a id="applicationcomponentstrategytypedef"></a>

## ApplicationComponentStrategyTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ApplicationComponentStrategyTypeDef
```

Optional fields:

- `isPreferred`: `bool`
- `recommendation`:
  [RecommendationSetTypeDef](./type_defs.md#recommendationsettypedef)
- `status`:
  [StrategyRecommendationType](./literals.md#strategyrecommendationtype)

<a id="applicationcomponentsummarytypedef"></a>

## ApplicationComponentSummaryTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ApplicationComponentSummaryTypeDef
```

Optional fields:

- `appType`: [AppTypeType](./literals.md#apptypetype)
- `count`: `int`

<a id="applicationpreferencestypedef"></a>

## ApplicationPreferencesTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ApplicationPreferencesTypeDef
```

Optional fields:

- `managementPreference`:
  [ManagementPreferenceTypeDef](./type_defs.md#managementpreferencetypedef)

<a id="assessmentsummarytypedef"></a>

## AssessmentSummaryTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import AssessmentSummaryTypeDef
```

Optional fields:

- `antipatternReportS3Object`:
  [S3ObjectTypeDef](./type_defs.md#s3objecttypedef)
- `antipatternReportStatus`:
  [AntipatternReportStatusType](./literals.md#antipatternreportstatustype)
- `antipatternReportStatusMessage`: `str`
- `lastAnalyzedTimestamp`: `datetime`
- `listAntipatternSeveritySummary`:
  `List`\[[AntipatternSeveritySummaryTypeDef](./type_defs.md#antipatternseveritysummarytypedef)\]
- `listApplicationComponentStrategySummary`:
  `List`\[[StrategySummaryTypeDef](./type_defs.md#strategysummarytypedef)\]
- `listApplicationComponentSummary`:
  `List`\[[ApplicationComponentSummaryTypeDef](./type_defs.md#applicationcomponentsummarytypedef)\]
- `listServerStrategySummary`:
  `List`\[[StrategySummaryTypeDef](./type_defs.md#strategysummarytypedef)\]
- `listServerSummary`:
  `List`\[[ServerSummaryTypeDef](./type_defs.md#serversummarytypedef)\]

<a id="associatedapplicationtypedef"></a>

## AssociatedApplicationTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import AssociatedApplicationTypeDef
```

Optional fields:

- `id`: `str`
- `name`: `str`

<a id="awsmanagedresourcestypedef"></a>

## AwsManagedResourcesTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import AwsManagedResourcesTypeDef
```

Required fields:

- `targetDestination`:
  `List`\[[AwsManagedTargetDestinationType](./literals.md#awsmanagedtargetdestinationtype)\]

<a id="businessgoalstypedef"></a>

## BusinessGoalsTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import BusinessGoalsTypeDef
```

Optional fields:

- `licenseCostReduction`: `int`
- `modernizeInfrastructureWithCloudNativeTechnologies`: `int`
- `reduceOperationalOverheadWithManagedServices`: `int`
- `speedOfMigration`: `int`

<a id="collectortypedef"></a>

## CollectorTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import CollectorTypeDef
```

Optional fields:

- `collectorHealth`: [CollectorHealthType](./literals.md#collectorhealthtype)
- `collectorId`: `str`
- `collectorVersion`: `str`
- `hostName`: `str`
- `ipAddress`: `str`
- `lastActivityTimeStamp`: `str`
- `registeredTimeStamp`: `str`

<a id="datacollectiondetailstypedef"></a>

## DataCollectionDetailsTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import DataCollectionDetailsTypeDef
```

Optional fields:

- `completionTime`: `datetime`
- `failed`: `int`
- `inProgress`: `int`
- `servers`: `int`
- `startTime`: `datetime`
- `status`: [AssessmentStatusType](./literals.md#assessmentstatustype)
- `success`: `int`

<a id="databaseconfigdetailtypedef"></a>

## DatabaseConfigDetailTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import DatabaseConfigDetailTypeDef
```

Optional fields:

- `secretName`: `str`

<a id="databasemigrationpreferencetypedef"></a>

## DatabaseMigrationPreferenceTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import DatabaseMigrationPreferenceTypeDef
```

Optional fields:

- `heterogeneous`: [HeterogeneousTypeDef](./type_defs.md#heterogeneoustypedef)
- `homogeneous`: [HomogeneousTypeDef](./type_defs.md#homogeneoustypedef)
- `noPreference`:
  [NoDatabaseMigrationPreferenceTypeDef](./type_defs.md#nodatabasemigrationpreferencetypedef)

<a id="databasepreferencestypedef"></a>

## DatabasePreferencesTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import DatabasePreferencesTypeDef
```

Optional fields:

- `databaseManagementPreference`:
  [DatabaseManagementPreferenceType](./literals.md#databasemanagementpreferencetype)
- `databaseMigrationPreference`:
  [DatabaseMigrationPreferenceTypeDef](./type_defs.md#databasemigrationpreferencetypedef)

<a id="getapplicationcomponentdetailsrequestrequesttypedef"></a>

## GetApplicationComponentDetailsRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetApplicationComponentDetailsRequestRequestTypeDef
```

Required fields:

- `applicationComponentId`: `str`

<a id="getapplicationcomponentdetailsresponsetypedef"></a>

## GetApplicationComponentDetailsResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetApplicationComponentDetailsResponseTypeDef
```

Required fields:

- `applicationComponentDetail`:
  [ApplicationComponentDetailTypeDef](./type_defs.md#applicationcomponentdetailtypedef)
- `associatedApplications`:
  `List`\[[AssociatedApplicationTypeDef](./type_defs.md#associatedapplicationtypedef)\]
- `associatedServerIds`: `List`\[`str`\]
- `moreApplicationResource`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getapplicationcomponentstrategiesrequestrequesttypedef"></a>

## GetApplicationComponentStrategiesRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetApplicationComponentStrategiesRequestRequestTypeDef
```

Required fields:

- `applicationComponentId`: `str`

<a id="getapplicationcomponentstrategiesresponsetypedef"></a>

## GetApplicationComponentStrategiesResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetApplicationComponentStrategiesResponseTypeDef
```

Required fields:

- `applicationComponentStrategies`:
  `List`\[[ApplicationComponentStrategyTypeDef](./type_defs.md#applicationcomponentstrategytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getassessmentrequestrequesttypedef"></a>

## GetAssessmentRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetAssessmentRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="getassessmentresponsetypedef"></a>

## GetAssessmentResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetAssessmentResponseTypeDef
```

Required fields:

- `dataCollectionDetails`:
  [DataCollectionDetailsTypeDef](./type_defs.md#datacollectiondetailstypedef)
- `id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getimportfiletaskrequestrequesttypedef"></a>

## GetImportFileTaskRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetImportFileTaskRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="getimportfiletaskresponsetypedef"></a>

## GetImportFileTaskResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetImportFileTaskResponseTypeDef
```

Required fields:

- `completionTime`: `datetime`
- `id`: `str`
- `importName`: `str`
- `inputS3Bucket`: `str`
- `inputS3Key`: `str`
- `numberOfRecordsFailed`: `int`
- `numberOfRecordsSuccess`: `int`
- `startTime`: `datetime`
- `status`: [ImportFileTaskStatusType](./literals.md#importfiletaskstatustype)
- `statusReportS3Bucket`: `str`
- `statusReportS3Key`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getportfoliopreferencesresponsetypedef"></a>

## GetPortfolioPreferencesResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetPortfolioPreferencesResponseTypeDef
```

Required fields:

- `applicationPreferences`:
  [ApplicationPreferencesTypeDef](./type_defs.md#applicationpreferencestypedef)
- `databasePreferences`:
  [DatabasePreferencesTypeDef](./type_defs.md#databasepreferencestypedef)
- `prioritizeBusinessGoals`:
  [PrioritizeBusinessGoalsTypeDef](./type_defs.md#prioritizebusinessgoalstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getportfoliosummaryresponsetypedef"></a>

## GetPortfolioSummaryResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetPortfolioSummaryResponseTypeDef
```

Required fields:

- `assessmentSummary`:
  [AssessmentSummaryTypeDef](./type_defs.md#assessmentsummarytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getrecommendationreportdetailsrequestrequesttypedef"></a>

## GetRecommendationReportDetailsRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetRecommendationReportDetailsRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="getrecommendationreportdetailsresponsetypedef"></a>

## GetRecommendationReportDetailsResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetRecommendationReportDetailsResponseTypeDef
```

Required fields:

- `id`: `str`
- `recommendationReportDetails`:
  [RecommendationReportDetailsTypeDef](./type_defs.md#recommendationreportdetailstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getserverdetailsrequestrequesttypedef"></a>

## GetServerDetailsRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetServerDetailsRequestRequestTypeDef
```

Required fields:

- `serverId`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="getserverdetailsresponsetypedef"></a>

## GetServerDetailsResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetServerDetailsResponseTypeDef
```

Required fields:

- `associatedApplications`:
  `List`\[[AssociatedApplicationTypeDef](./type_defs.md#associatedapplicationtypedef)\]
- `nextToken`: `str`
- `serverDetail`: [ServerDetailTypeDef](./type_defs.md#serverdetailtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getserverstrategiesrequestrequesttypedef"></a>

## GetServerStrategiesRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetServerStrategiesRequestRequestTypeDef
```

Required fields:

- `serverId`: `str`

<a id="getserverstrategiesresponsetypedef"></a>

## GetServerStrategiesResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GetServerStrategiesResponseTypeDef
```

Required fields:

- `serverStrategies`:
  `List`\[[ServerStrategyTypeDef](./type_defs.md#serverstrategytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="grouptypedef"></a>

## GroupTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import GroupTypeDef
```

Optional fields:

- `name`: `Literal['ExternalId']` (see
  [GroupNameType](./literals.md#groupnametype))
- `value`: `str`

<a id="heterogeneoustypedef"></a>

## HeterogeneousTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import HeterogeneousTypeDef
```

Required fields:

- `targetDatabaseEngine`:
  `List`\[[HeterogeneousTargetDatabaseEngineType](./literals.md#heterogeneoustargetdatabaseenginetype)\]

<a id="homogeneoustypedef"></a>

## HomogeneousTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import HomogeneousTypeDef
```

Optional fields:

- `targetDatabaseEngine`: `List`\[`Literal['None specified']` (see
  [HomogeneousTargetDatabaseEngineType](./literals.md#homogeneoustargetdatabaseenginetype))\]

<a id="importfiletaskinformationtypedef"></a>

## ImportFileTaskInformationTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ImportFileTaskInformationTypeDef
```

Optional fields:

- `completionTime`: `datetime`
- `id`: `str`
- `importName`: `str`
- `inputS3Bucket`: `str`
- `inputS3Key`: `str`
- `numberOfRecordsFailed`: `int`
- `numberOfRecordsSuccess`: `int`
- `startTime`: `datetime`
- `status`: [ImportFileTaskStatusType](./literals.md#importfiletaskstatustype)
- `statusReportS3Bucket`: `str`
- `statusReportS3Key`: `str`

<a id="listapplicationcomponentsrequestrequesttypedef"></a>

## ListApplicationComponentsRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListApplicationComponentsRequestRequestTypeDef
```

Optional fields:

- `applicationComponentCriteria`:
  [ApplicationComponentCriteriaType](./literals.md#applicationcomponentcriteriatype)
- `filterValue`: `str`
- `groupIdFilter`: `Sequence`\[[GroupTypeDef](./type_defs.md#grouptypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `sort`: [SortOrderType](./literals.md#sortordertype)

<a id="listapplicationcomponentsresponsetypedef"></a>

## ListApplicationComponentsResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListApplicationComponentsResponseTypeDef
```

Required fields:

- `applicationComponentInfos`:
  `List`\[[ApplicationComponentDetailTypeDef](./type_defs.md#applicationcomponentdetailtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcollectorsrequestrequesttypedef"></a>

## ListCollectorsRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListCollectorsRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listcollectorsresponsetypedef"></a>

## ListCollectorsResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListCollectorsResponseTypeDef
```

Required fields:

- `Collectors`: `List`\[[CollectorTypeDef](./type_defs.md#collectortypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listimportfiletaskrequestrequesttypedef"></a>

## ListImportFileTaskRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListImportFileTaskRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listimportfiletaskresponsetypedef"></a>

## ListImportFileTaskResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListImportFileTaskResponseTypeDef
```

Required fields:

- `nextToken`: `str`
- `taskInfos`:
  `List`\[[ImportFileTaskInformationTypeDef](./type_defs.md#importfiletaskinformationtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listserversrequestrequesttypedef"></a>

## ListServersRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListServersRequestRequestTypeDef
```

Optional fields:

- `filterValue`: `str`
- `groupIdFilter`: `Sequence`\[[GroupTypeDef](./type_defs.md#grouptypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `serverCriteria`: [ServerCriteriaType](./literals.md#servercriteriatype)
- `sort`: [SortOrderType](./literals.md#sortordertype)

<a id="listserversresponsetypedef"></a>

## ListServersResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ListServersResponseTypeDef
```

Required fields:

- `nextToken`: `str`
- `serverInfos`:
  `List`\[[ServerDetailTypeDef](./type_defs.md#serverdetailtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="managementpreferencetypedef"></a>

## ManagementPreferenceTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ManagementPreferenceTypeDef
```

Optional fields:

- `awsManagedResources`:
  [AwsManagedResourcesTypeDef](./type_defs.md#awsmanagedresourcestypedef)
- `noPreference`:
  [NoManagementPreferenceTypeDef](./type_defs.md#nomanagementpreferencetypedef)
- `selfManageResources`:
  [SelfManageResourcesTypeDef](./type_defs.md#selfmanageresourcestypedef)

<a id="networkinfotypedef"></a>

## NetworkInfoTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import NetworkInfoTypeDef
```

Required fields:

- `interfaceName`: `str`
- `ipAddress`: `str`
- `macAddress`: `str`
- `netMask`: `str`

<a id="nodatabasemigrationpreferencetypedef"></a>

## NoDatabaseMigrationPreferenceTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import NoDatabaseMigrationPreferenceTypeDef
```

Required fields:

- `targetDatabaseEngine`:
  `List`\[[TargetDatabaseEngineType](./literals.md#targetdatabaseenginetype)\]

<a id="nomanagementpreferencetypedef"></a>

## NoManagementPreferenceTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import NoManagementPreferenceTypeDef
```

Required fields:

- `targetDestination`:
  `List`\[[NoPreferenceTargetDestinationType](./literals.md#nopreferencetargetdestinationtype)\]

<a id="osinfotypedef"></a>

## OSInfoTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import OSInfoTypeDef
```

Optional fields:

- `type`: [OSTypeType](./literals.md#ostypetype)
- `version`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="prioritizebusinessgoalstypedef"></a>

## PrioritizeBusinessGoalsTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import PrioritizeBusinessGoalsTypeDef
```

Optional fields:

- `businessGoals`: [BusinessGoalsTypeDef](./type_defs.md#businessgoalstypedef)

<a id="putportfoliopreferencesrequestrequesttypedef"></a>

## PutPortfolioPreferencesRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import PutPortfolioPreferencesRequestRequestTypeDef
```

Optional fields:

- `applicationPreferences`:
  [ApplicationPreferencesTypeDef](./type_defs.md#applicationpreferencestypedef)
- `databasePreferences`:
  [DatabasePreferencesTypeDef](./type_defs.md#databasepreferencestypedef)
- `prioritizeBusinessGoals`:
  [PrioritizeBusinessGoalsTypeDef](./type_defs.md#prioritizebusinessgoalstypedef)

<a id="recommendationreportdetailstypedef"></a>

## RecommendationReportDetailsTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import RecommendationReportDetailsTypeDef
```

Optional fields:

- `completionTime`: `datetime`
- `s3Bucket`: `str`
- `s3Keys`: `List`\[`str`\]
- `startTime`: `datetime`
- `status`:
  [RecommendationReportStatusType](./literals.md#recommendationreportstatustype)
- `statusMessage`: `str`

<a id="recommendationsettypedef"></a>

## RecommendationSetTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import RecommendationSetTypeDef
```

Optional fields:

- `strategy`: [StrategyType](./literals.md#strategytype)
- `targetDestination`:
  [TargetDestinationType](./literals.md#targetdestinationtype)
- `transformationTool`:
  [TransformationToolTypeDef](./type_defs.md#transformationtooltypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3objecttypedef"></a>

## S3ObjectTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import S3ObjectTypeDef
```

Optional fields:

- `s3Bucket`: `str`
- `s3key`: `str`

<a id="selfmanageresourcestypedef"></a>

## SelfManageResourcesTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import SelfManageResourcesTypeDef
```

Required fields:

- `targetDestination`:
  `List`\[[SelfManageTargetDestinationType](./literals.md#selfmanagetargetdestinationtype)\]

<a id="serverdetailtypedef"></a>

## ServerDetailTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ServerDetailTypeDef
```

Optional fields:

- `antipatternReportS3Object`:
  [S3ObjectTypeDef](./type_defs.md#s3objecttypedef)
- `antipatternReportStatus`:
  [AntipatternReportStatusType](./literals.md#antipatternreportstatustype)
- `antipatternReportStatusMessage`: `str`
- `applicationComponentStrategySummary`:
  `List`\[[StrategySummaryTypeDef](./type_defs.md#strategysummarytypedef)\]
- `dataCollectionStatus`:
  [RunTimeAssessmentStatusType](./literals.md#runtimeassessmentstatustype)
- `id`: `str`
- `lastAnalyzedTimestamp`: `datetime`
- `listAntipatternSeveritySummary`:
  `List`\[[AntipatternSeveritySummaryTypeDef](./type_defs.md#antipatternseveritysummarytypedef)\]
- `name`: `str`
- `recommendationSet`:
  [RecommendationSetTypeDef](./type_defs.md#recommendationsettypedef)
- `serverType`: `str`
- `statusMessage`: `str`
- `systemInfo`: [SystemInfoTypeDef](./type_defs.md#systeminfotypedef)

<a id="serverstrategytypedef"></a>

## ServerStrategyTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ServerStrategyTypeDef
```

Optional fields:

- `isPreferred`: `bool`
- `numberOfApplicationComponents`: `int`
- `recommendation`:
  [RecommendationSetTypeDef](./type_defs.md#recommendationsettypedef)
- `status`:
  [StrategyRecommendationType](./literals.md#strategyrecommendationtype)

<a id="serversummarytypedef"></a>

## ServerSummaryTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import ServerSummaryTypeDef
```

Optional fields:

- `ServerOsType`: [ServerOsTypeType](./literals.md#serverostypetype)
- `count`: `int`

<a id="sourcecoderepositorytypedef"></a>

## SourceCodeRepositoryTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import SourceCodeRepositoryTypeDef
```

Optional fields:

- `branch`: `str`
- `repository`: `str`
- `versionControlType`: `str`

<a id="sourcecodetypedef"></a>

## SourceCodeTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import SourceCodeTypeDef
```

Optional fields:

- `location`: `str`
- `sourceVersion`: `str`
- `versionControl`: [VersionControlType](./literals.md#versioncontroltype)

<a id="startassessmentrequestrequesttypedef"></a>

## StartAssessmentRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StartAssessmentRequestRequestTypeDef
```

Optional fields:

- `s3bucketForAnalysisData`: `str`
- `s3bucketForReportData`: `str`

<a id="startassessmentresponsetypedef"></a>

## StartAssessmentResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StartAssessmentResponseTypeDef
```

Required fields:

- `assessmentId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startimportfiletaskrequestrequesttypedef"></a>

## StartImportFileTaskRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StartImportFileTaskRequestRequestTypeDef
```

Required fields:

- `S3Bucket`: `str`
- `name`: `str`
- `s3key`: `str`

Optional fields:

- `dataSourceType`: [DataSourceTypeType](./literals.md#datasourcetypetype)
- `groupId`: `Sequence`\[[GroupTypeDef](./type_defs.md#grouptypedef)\]
- `s3bucketForReportData`: `str`

<a id="startimportfiletaskresponsetypedef"></a>

## StartImportFileTaskResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StartImportFileTaskResponseTypeDef
```

Required fields:

- `id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="startrecommendationreportgenerationrequestrequesttypedef"></a>

## StartRecommendationReportGenerationRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StartRecommendationReportGenerationRequestRequestTypeDef
```

Optional fields:

- `groupIdFilter`: `Sequence`\[[GroupTypeDef](./type_defs.md#grouptypedef)\]
- `outputFormat`: [OutputFormatType](./literals.md#outputformattype)

<a id="startrecommendationreportgenerationresponsetypedef"></a>

## StartRecommendationReportGenerationResponseTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StartRecommendationReportGenerationResponseTypeDef
```

Required fields:

- `id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopassessmentrequestrequesttypedef"></a>

## StopAssessmentRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StopAssessmentRequestRequestTypeDef
```

Required fields:

- `assessmentId`: `str`

<a id="strategyoptiontypedef"></a>

## StrategyOptionTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StrategyOptionTypeDef
```

Optional fields:

- `isPreferred`: `bool`
- `strategy`: [StrategyType](./literals.md#strategytype)
- `targetDestination`:
  [TargetDestinationType](./literals.md#targetdestinationtype)
- `toolName`:
  [TransformationToolNameType](./literals.md#transformationtoolnametype)

<a id="strategysummarytypedef"></a>

## StrategySummaryTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import StrategySummaryTypeDef
```

Optional fields:

- `count`: `int`
- `strategy`: [StrategyType](./literals.md#strategytype)

<a id="systeminfotypedef"></a>

## SystemInfoTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import SystemInfoTypeDef
```

Optional fields:

- `cpuArchitecture`: `str`
- `fileSystemType`: `str`
- `networkInfoList`:
  `List`\[[NetworkInfoTypeDef](./type_defs.md#networkinfotypedef)\]
- `osInfo`: [OSInfoTypeDef](./type_defs.md#osinfotypedef)

<a id="transformationtooltypedef"></a>

## TransformationToolTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import TransformationToolTypeDef
```

Optional fields:

- `description`: `str`
- `name`:
  [TransformationToolNameType](./literals.md#transformationtoolnametype)
- `tranformationToolInstallationLink`: `str`

<a id="updateapplicationcomponentconfigrequestrequesttypedef"></a>

## UpdateApplicationComponentConfigRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import UpdateApplicationComponentConfigRequestRequestTypeDef
```

Required fields:

- `applicationComponentId`: `str`

Optional fields:

- `inclusionStatus`: [InclusionStatusType](./literals.md#inclusionstatustype)
- `secretsManagerKey`: `str`
- `sourceCodeList`:
  `Sequence`\[[SourceCodeTypeDef](./type_defs.md#sourcecodetypedef)\]
- `strategyOption`:
  [StrategyOptionTypeDef](./type_defs.md#strategyoptiontypedef)

<a id="updateserverconfigrequestrequesttypedef"></a>

## UpdateServerConfigRequestRequestTypeDef

```python
from types_aiobotocore_migrationhubstrategy.type_defs import UpdateServerConfigRequestRequestTypeDef
```

Required fields:

- `serverId`: `str`

Optional fields:

- `strategyOption`:
  [StrategyOptionTypeDef](./type_defs.md#strategyoptiontypedef)
