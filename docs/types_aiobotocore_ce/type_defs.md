<a id="typed-dictionaries-for-aiobotocore-costexplorer-module"></a>

# Typed dictionaries for aiobotocore CostExplorer module

> [Index](../README.md) > [CostExplorer](./README.md) > Typed dictionaries

Auto-generated documentation for
[CostExplorer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ce.html#CostExplorer)
type annotations stubs module
[types-aiobotocore-ce](https://pypi.org/project/types-aiobotocore-ce/).

- [Typed dictionaries for aiobotocore CostExplorer module](#typed-dictionaries-for-aiobotocore-costexplorer-module)
  - [AnomalyDateIntervalTypeDef](#anomalydateintervaltypedef)
  - [AnomalyMonitorTypeDef](#anomalymonitortypedef)
  - [AnomalyScoreTypeDef](#anomalyscoretypedef)
  - [AnomalySubscriptionTypeDef](#anomalysubscriptiontypedef)
  - [AnomalyTypeDef](#anomalytypedef)
  - [CostCategoryInheritedValueDimensionTypeDef](#costcategoryinheritedvaluedimensiontypedef)
  - [CostCategoryProcessingStatusTypeDef](#costcategoryprocessingstatustypedef)
  - [CostCategoryReferenceTypeDef](#costcategoryreferencetypedef)
  - [CostCategoryRuleTypeDef](#costcategoryruletypedef)
  - [CostCategorySplitChargeRuleParameterTypeDef](#costcategorysplitchargeruleparametertypedef)
  - [CostCategorySplitChargeRuleTypeDef](#costcategorysplitchargeruletypedef)
  - [CostCategoryTypeDef](#costcategorytypedef)
  - [CostCategoryValuesTypeDef](#costcategoryvaluestypedef)
  - [CoverageByTimeTypeDef](#coveragebytimetypedef)
  - [CoverageCostTypeDef](#coveragecosttypedef)
  - [CoverageHoursTypeDef](#coveragehourstypedef)
  - [CoverageNormalizedUnitsTypeDef](#coveragenormalizedunitstypedef)
  - [CoverageTypeDef](#coveragetypedef)
  - [CreateAnomalyMonitorRequestRequestTypeDef](#createanomalymonitorrequestrequesttypedef)
  - [CreateAnomalyMonitorResponseTypeDef](#createanomalymonitorresponsetypedef)
  - [CreateAnomalySubscriptionRequestRequestTypeDef](#createanomalysubscriptionrequestrequesttypedef)
  - [CreateAnomalySubscriptionResponseTypeDef](#createanomalysubscriptionresponsetypedef)
  - [CreateCostCategoryDefinitionRequestRequestTypeDef](#createcostcategorydefinitionrequestrequesttypedef)
  - [CreateCostCategoryDefinitionResponseTypeDef](#createcostcategorydefinitionresponsetypedef)
  - [CurrentInstanceTypeDef](#currentinstancetypedef)
  - [DateIntervalTypeDef](#dateintervaltypedef)
  - [DeleteAnomalyMonitorRequestRequestTypeDef](#deleteanomalymonitorrequestrequesttypedef)
  - [DeleteAnomalySubscriptionRequestRequestTypeDef](#deleteanomalysubscriptionrequestrequesttypedef)
  - [DeleteCostCategoryDefinitionRequestRequestTypeDef](#deletecostcategorydefinitionrequestrequesttypedef)
  - [DeleteCostCategoryDefinitionResponseTypeDef](#deletecostcategorydefinitionresponsetypedef)
  - [DescribeCostCategoryDefinitionRequestRequestTypeDef](#describecostcategorydefinitionrequestrequesttypedef)
  - [DescribeCostCategoryDefinitionResponseTypeDef](#describecostcategorydefinitionresponsetypedef)
  - [DimensionValuesTypeDef](#dimensionvaluestypedef)
  - [DimensionValuesWithAttributesTypeDef](#dimensionvalueswithattributestypedef)
  - [DiskResourceUtilizationTypeDef](#diskresourceutilizationtypedef)
  - [EBSResourceUtilizationTypeDef](#ebsresourceutilizationtypedef)
  - [EC2InstanceDetailsTypeDef](#ec2instancedetailstypedef)
  - [EC2ResourceDetailsTypeDef](#ec2resourcedetailstypedef)
  - [EC2ResourceUtilizationTypeDef](#ec2resourceutilizationtypedef)
  - [EC2SpecificationTypeDef](#ec2specificationtypedef)
  - [ESInstanceDetailsTypeDef](#esinstancedetailstypedef)
  - [ElastiCacheInstanceDetailsTypeDef](#elasticacheinstancedetailstypedef)
  - [ExpressionTypeDef](#expressiontypedef)
  - [ForecastResultTypeDef](#forecastresulttypedef)
  - [GetAnomaliesRequestRequestTypeDef](#getanomaliesrequestrequesttypedef)
  - [GetAnomaliesResponseTypeDef](#getanomaliesresponsetypedef)
  - [GetAnomalyMonitorsRequestRequestTypeDef](#getanomalymonitorsrequestrequesttypedef)
  - [GetAnomalyMonitorsResponseTypeDef](#getanomalymonitorsresponsetypedef)
  - [GetAnomalySubscriptionsRequestRequestTypeDef](#getanomalysubscriptionsrequestrequesttypedef)
  - [GetAnomalySubscriptionsResponseTypeDef](#getanomalysubscriptionsresponsetypedef)
  - [GetCostAndUsageRequestRequestTypeDef](#getcostandusagerequestrequesttypedef)
  - [GetCostAndUsageResponseTypeDef](#getcostandusageresponsetypedef)
  - [GetCostAndUsageWithResourcesRequestRequestTypeDef](#getcostandusagewithresourcesrequestrequesttypedef)
  - [GetCostAndUsageWithResourcesResponseTypeDef](#getcostandusagewithresourcesresponsetypedef)
  - [GetCostCategoriesRequestRequestTypeDef](#getcostcategoriesrequestrequesttypedef)
  - [GetCostCategoriesResponseTypeDef](#getcostcategoriesresponsetypedef)
  - [GetCostForecastRequestRequestTypeDef](#getcostforecastrequestrequesttypedef)
  - [GetCostForecastResponseTypeDef](#getcostforecastresponsetypedef)
  - [GetDimensionValuesRequestRequestTypeDef](#getdimensionvaluesrequestrequesttypedef)
  - [GetDimensionValuesResponseTypeDef](#getdimensionvaluesresponsetypedef)
  - [GetReservationCoverageRequestRequestTypeDef](#getreservationcoveragerequestrequesttypedef)
  - [GetReservationCoverageResponseTypeDef](#getreservationcoverageresponsetypedef)
  - [GetReservationPurchaseRecommendationRequestRequestTypeDef](#getreservationpurchaserecommendationrequestrequesttypedef)
  - [GetReservationPurchaseRecommendationResponseTypeDef](#getreservationpurchaserecommendationresponsetypedef)
  - [GetReservationUtilizationRequestRequestTypeDef](#getreservationutilizationrequestrequesttypedef)
  - [GetReservationUtilizationResponseTypeDef](#getreservationutilizationresponsetypedef)
  - [GetRightsizingRecommendationRequestRequestTypeDef](#getrightsizingrecommendationrequestrequesttypedef)
  - [GetRightsizingRecommendationResponseTypeDef](#getrightsizingrecommendationresponsetypedef)
  - [GetSavingsPlansCoverageRequestRequestTypeDef](#getsavingsplanscoveragerequestrequesttypedef)
  - [GetSavingsPlansCoverageResponseTypeDef](#getsavingsplanscoverageresponsetypedef)
  - [GetSavingsPlansPurchaseRecommendationRequestRequestTypeDef](#getsavingsplanspurchaserecommendationrequestrequesttypedef)
  - [GetSavingsPlansPurchaseRecommendationResponseTypeDef](#getsavingsplanspurchaserecommendationresponsetypedef)
  - [GetSavingsPlansUtilizationDetailsRequestRequestTypeDef](#getsavingsplansutilizationdetailsrequestrequesttypedef)
  - [GetSavingsPlansUtilizationDetailsResponseTypeDef](#getsavingsplansutilizationdetailsresponsetypedef)
  - [GetSavingsPlansUtilizationRequestRequestTypeDef](#getsavingsplansutilizationrequestrequesttypedef)
  - [GetSavingsPlansUtilizationResponseTypeDef](#getsavingsplansutilizationresponsetypedef)
  - [GetTagsRequestRequestTypeDef](#gettagsrequestrequesttypedef)
  - [GetTagsResponseTypeDef](#gettagsresponsetypedef)
  - [GetUsageForecastRequestRequestTypeDef](#getusageforecastrequestrequesttypedef)
  - [GetUsageForecastResponseTypeDef](#getusageforecastresponsetypedef)
  - [GroupDefinitionTypeDef](#groupdefinitiontypedef)
  - [GroupTypeDef](#grouptypedef)
  - [ImpactTypeDef](#impacttypedef)
  - [InstanceDetailsTypeDef](#instancedetailstypedef)
  - [ListCostCategoryDefinitionsRequestRequestTypeDef](#listcostcategorydefinitionsrequestrequesttypedef)
  - [ListCostCategoryDefinitionsResponseTypeDef](#listcostcategorydefinitionsresponsetypedef)
  - [MetricValueTypeDef](#metricvaluetypedef)
  - [ModifyRecommendationDetailTypeDef](#modifyrecommendationdetailtypedef)
  - [NetworkResourceUtilizationTypeDef](#networkresourceutilizationtypedef)
  - [ProvideAnomalyFeedbackRequestRequestTypeDef](#provideanomalyfeedbackrequestrequesttypedef)
  - [ProvideAnomalyFeedbackResponseTypeDef](#provideanomalyfeedbackresponsetypedef)
  - [RDSInstanceDetailsTypeDef](#rdsinstancedetailstypedef)
  - [RedshiftInstanceDetailsTypeDef](#redshiftinstancedetailstypedef)
  - [ReservationAggregatesTypeDef](#reservationaggregatestypedef)
  - [ReservationCoverageGroupTypeDef](#reservationcoveragegrouptypedef)
  - [ReservationPurchaseRecommendationDetailTypeDef](#reservationpurchaserecommendationdetailtypedef)
  - [ReservationPurchaseRecommendationMetadataTypeDef](#reservationpurchaserecommendationmetadatatypedef)
  - [ReservationPurchaseRecommendationSummaryTypeDef](#reservationpurchaserecommendationsummarytypedef)
  - [ReservationPurchaseRecommendationTypeDef](#reservationpurchaserecommendationtypedef)
  - [ReservationUtilizationGroupTypeDef](#reservationutilizationgrouptypedef)
  - [ResourceDetailsTypeDef](#resourcedetailstypedef)
  - [ResourceUtilizationTypeDef](#resourceutilizationtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ResultByTimeTypeDef](#resultbytimetypedef)
  - [RightsizingRecommendationConfigurationTypeDef](#rightsizingrecommendationconfigurationtypedef)
  - [RightsizingRecommendationMetadataTypeDef](#rightsizingrecommendationmetadatatypedef)
  - [RightsizingRecommendationSummaryTypeDef](#rightsizingrecommendationsummarytypedef)
  - [RightsizingRecommendationTypeDef](#rightsizingrecommendationtypedef)
  - [RootCauseTypeDef](#rootcausetypedef)
  - [SavingsPlansAmortizedCommitmentTypeDef](#savingsplansamortizedcommitmenttypedef)
  - [SavingsPlansCoverageDataTypeDef](#savingsplanscoveragedatatypedef)
  - [SavingsPlansCoverageTypeDef](#savingsplanscoveragetypedef)
  - [SavingsPlansDetailsTypeDef](#savingsplansdetailstypedef)
  - [SavingsPlansPurchaseRecommendationDetailTypeDef](#savingsplanspurchaserecommendationdetailtypedef)
  - [SavingsPlansPurchaseRecommendationMetadataTypeDef](#savingsplanspurchaserecommendationmetadatatypedef)
  - [SavingsPlansPurchaseRecommendationSummaryTypeDef](#savingsplanspurchaserecommendationsummarytypedef)
  - [SavingsPlansPurchaseRecommendationTypeDef](#savingsplanspurchaserecommendationtypedef)
  - [SavingsPlansSavingsTypeDef](#savingsplanssavingstypedef)
  - [SavingsPlansUtilizationAggregatesTypeDef](#savingsplansutilizationaggregatestypedef)
  - [SavingsPlansUtilizationByTimeTypeDef](#savingsplansutilizationbytimetypedef)
  - [SavingsPlansUtilizationDetailTypeDef](#savingsplansutilizationdetailtypedef)
  - [SavingsPlansUtilizationTypeDef](#savingsplansutilizationtypedef)
  - [ServiceSpecificationTypeDef](#servicespecificationtypedef)
  - [SortDefinitionTypeDef](#sortdefinitiontypedef)
  - [SubscriberTypeDef](#subscribertypedef)
  - [TagValuesTypeDef](#tagvaluestypedef)
  - [TargetInstanceTypeDef](#targetinstancetypedef)
  - [TerminateRecommendationDetailTypeDef](#terminaterecommendationdetailtypedef)
  - [TotalImpactFilterTypeDef](#totalimpactfiltertypedef)
  - [UpdateAnomalyMonitorRequestRequestTypeDef](#updateanomalymonitorrequestrequesttypedef)
  - [UpdateAnomalyMonitorResponseTypeDef](#updateanomalymonitorresponsetypedef)
  - [UpdateAnomalySubscriptionRequestRequestTypeDef](#updateanomalysubscriptionrequestrequesttypedef)
  - [UpdateAnomalySubscriptionResponseTypeDef](#updateanomalysubscriptionresponsetypedef)
  - [UpdateCostCategoryDefinitionRequestRequestTypeDef](#updatecostcategorydefinitionrequestrequesttypedef)
  - [UpdateCostCategoryDefinitionResponseTypeDef](#updatecostcategorydefinitionresponsetypedef)
  - [UtilizationByTimeTypeDef](#utilizationbytimetypedef)

<a id="anomalydateintervaltypedef"></a>

## AnomalyDateIntervalTypeDef

```python
from types_aiobotocore_ce.type_defs import AnomalyDateIntervalTypeDef
```

Required fields:

- `StartDate`: `str`

Optional fields:

- `EndDate`: `str`

<a id="anomalymonitortypedef"></a>

## AnomalyMonitorTypeDef

```python
from types_aiobotocore_ce.type_defs import AnomalyMonitorTypeDef
```

Required fields:

- `MonitorName`: `str`
- `MonitorType`: [MonitorTypeType](./literals.md#monitortypetype)

Optional fields:

- `MonitorArn`: `str`
- `CreationDate`: `str`
- `LastUpdatedDate`: `str`
- `LastEvaluatedDate`: `str`
- `MonitorDimension`: `Literal['SERVICE']` (see
  [MonitorDimensionType](./literals.md#monitordimensiontype))
- `MonitorSpecification`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `DimensionalValueCount`: `int`

<a id="anomalyscoretypedef"></a>

## AnomalyScoreTypeDef

```python
from types_aiobotocore_ce.type_defs import AnomalyScoreTypeDef
```

Required fields:

- `MaxScore`: `float`
- `CurrentScore`: `float`

<a id="anomalysubscriptiontypedef"></a>

## AnomalySubscriptionTypeDef

```python
from types_aiobotocore_ce.type_defs import AnomalySubscriptionTypeDef
```

Required fields:

- `MonitorArnList`: `Sequence`\[`str`\]
- `Subscribers`:
  `Sequence`\[[SubscriberTypeDef](./type_defs.md#subscribertypedef)\]
- `Threshold`: `float`
- `Frequency`:
  [AnomalySubscriptionFrequencyType](./literals.md#anomalysubscriptionfrequencytype)
- `SubscriptionName`: `str`

Optional fields:

- `SubscriptionArn`: `str`
- `AccountId`: `str`

<a id="anomalytypedef"></a>

## AnomalyTypeDef

```python
from types_aiobotocore_ce.type_defs import AnomalyTypeDef
```

Required fields:

- `AnomalyId`: `str`
- `AnomalyScore`: [AnomalyScoreTypeDef](./type_defs.md#anomalyscoretypedef)
- `Impact`: [ImpactTypeDef](./type_defs.md#impacttypedef)
- `MonitorArn`: `str`

Optional fields:

- `AnomalyStartDate`: `str`
- `AnomalyEndDate`: `str`
- `DimensionValue`: `str`
- `RootCauses`: `List`\[[RootCauseTypeDef](./type_defs.md#rootcausetypedef)\]
- `Feedback`: [AnomalyFeedbackTypeType](./literals.md#anomalyfeedbacktypetype)

<a id="costcategoryinheritedvaluedimensiontypedef"></a>

## CostCategoryInheritedValueDimensionTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategoryInheritedValueDimensionTypeDef
```

Optional fields:

- `DimensionName`:
  [CostCategoryInheritedValueDimensionNameType](./literals.md#costcategoryinheritedvaluedimensionnametype)
- `DimensionKey`: `str`

<a id="costcategoryprocessingstatustypedef"></a>

## CostCategoryProcessingStatusTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategoryProcessingStatusTypeDef
```

Optional fields:

- `Component`: `Literal['COST_EXPLORER']` (see
  [CostCategoryStatusComponentType](./literals.md#costcategorystatuscomponenttype))
- `Status`: [CostCategoryStatusType](./literals.md#costcategorystatustype)

<a id="costcategoryreferencetypedef"></a>

## CostCategoryReferenceTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategoryReferenceTypeDef
```

Optional fields:

- `CostCategoryArn`: `str`
- `Name`: `str`
- `EffectiveStart`: `str`
- `EffectiveEnd`: `str`
- `NumberOfRules`: `int`
- `ProcessingStatus`:
  `List`\[[CostCategoryProcessingStatusTypeDef](./type_defs.md#costcategoryprocessingstatustypedef)\]
- `Values`: `List`\[`str`\]
- `DefaultValue`: `str`

<a id="costcategoryruletypedef"></a>

## CostCategoryRuleTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategoryRuleTypeDef
```

Optional fields:

- `Value`: `str`
- `Rule`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `InheritedValue`:
  [CostCategoryInheritedValueDimensionTypeDef](./type_defs.md#costcategoryinheritedvaluedimensiontypedef)
- `Type`: [CostCategoryRuleTypeType](./literals.md#costcategoryruletypetype)

<a id="costcategorysplitchargeruleparametertypedef"></a>

## CostCategorySplitChargeRuleParameterTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategorySplitChargeRuleParameterTypeDef
```

Required fields:

- `Type`: `Literal['ALLOCATION_PERCENTAGES']` (see
  [CostCategorySplitChargeRuleParameterTypeType](./literals.md#costcategorysplitchargeruleparametertypetype))
- `Values`: `Sequence`\[`str`\]

<a id="costcategorysplitchargeruletypedef"></a>

## CostCategorySplitChargeRuleTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategorySplitChargeRuleTypeDef
```

Required fields:

- `Source`: `str`
- `Targets`: `Sequence`\[`str`\]
- `Method`:
  [CostCategorySplitChargeMethodType](./literals.md#costcategorysplitchargemethodtype)

Optional fields:

- `Parameters`:
  `Sequence`\[[CostCategorySplitChargeRuleParameterTypeDef](./type_defs.md#costcategorysplitchargeruleparametertypedef)\]

<a id="costcategorytypedef"></a>

## CostCategoryTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategoryTypeDef
```

Required fields:

- `CostCategoryArn`: `str`
- `EffectiveStart`: `str`
- `Name`: `str`
- `RuleVersion`: `Literal['CostCategoryExpression.v1']` (see
  [CostCategoryRuleVersionType](./literals.md#costcategoryruleversiontype))
- `Rules`:
  `List`\[[CostCategoryRuleTypeDef](./type_defs.md#costcategoryruletypedef)\]

Optional fields:

- `EffectiveEnd`: `str`
- `SplitChargeRules`:
  `List`\[[CostCategorySplitChargeRuleTypeDef](./type_defs.md#costcategorysplitchargeruletypedef)\]
- `ProcessingStatus`:
  `List`\[[CostCategoryProcessingStatusTypeDef](./type_defs.md#costcategoryprocessingstatustypedef)\]
- `DefaultValue`: `str`

<a id="costcategoryvaluestypedef"></a>

## CostCategoryValuesTypeDef

```python
from types_aiobotocore_ce.type_defs import CostCategoryValuesTypeDef
```

Optional fields:

- `Key`: `str`
- `Values`: `Sequence`\[`str`\]
- `MatchOptions`:
  `Sequence`\[[MatchOptionType](./literals.md#matchoptiontype)\]

<a id="coveragebytimetypedef"></a>

## CoverageByTimeTypeDef

```python
from types_aiobotocore_ce.type_defs import CoverageByTimeTypeDef
```

Optional fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Groups`:
  `List`\[[ReservationCoverageGroupTypeDef](./type_defs.md#reservationcoveragegrouptypedef)\]
- `Total`: [CoverageTypeDef](./type_defs.md#coveragetypedef)

<a id="coveragecosttypedef"></a>

## CoverageCostTypeDef

```python
from types_aiobotocore_ce.type_defs import CoverageCostTypeDef
```

Optional fields:

- `OnDemandCost`: `str`

<a id="coveragehourstypedef"></a>

## CoverageHoursTypeDef

```python
from types_aiobotocore_ce.type_defs import CoverageHoursTypeDef
```

Optional fields:

- `OnDemandHours`: `str`
- `ReservedHours`: `str`
- `TotalRunningHours`: `str`
- `CoverageHoursPercentage`: `str`

<a id="coveragenormalizedunitstypedef"></a>

## CoverageNormalizedUnitsTypeDef

```python
from types_aiobotocore_ce.type_defs import CoverageNormalizedUnitsTypeDef
```

Optional fields:

- `OnDemandNormalizedUnits`: `str`
- `ReservedNormalizedUnits`: `str`
- `TotalRunningNormalizedUnits`: `str`
- `CoverageNormalizedUnitsPercentage`: `str`

<a id="coveragetypedef"></a>

## CoverageTypeDef

```python
from types_aiobotocore_ce.type_defs import CoverageTypeDef
```

Optional fields:

- `CoverageHours`: [CoverageHoursTypeDef](./type_defs.md#coveragehourstypedef)
- `CoverageNormalizedUnits`:
  [CoverageNormalizedUnitsTypeDef](./type_defs.md#coveragenormalizedunitstypedef)
- `CoverageCost`: [CoverageCostTypeDef](./type_defs.md#coveragecosttypedef)

<a id="createanomalymonitorrequestrequesttypedef"></a>

## CreateAnomalyMonitorRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import CreateAnomalyMonitorRequestRequestTypeDef
```

Required fields:

- `AnomalyMonitor`:
  [AnomalyMonitorTypeDef](./type_defs.md#anomalymonitortypedef)

<a id="createanomalymonitorresponsetypedef"></a>

## CreateAnomalyMonitorResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import CreateAnomalyMonitorResponseTypeDef
```

Required fields:

- `MonitorArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createanomalysubscriptionrequestrequesttypedef"></a>

## CreateAnomalySubscriptionRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import CreateAnomalySubscriptionRequestRequestTypeDef
```

Required fields:

- `AnomalySubscription`:
  [AnomalySubscriptionTypeDef](./type_defs.md#anomalysubscriptiontypedef)

<a id="createanomalysubscriptionresponsetypedef"></a>

## CreateAnomalySubscriptionResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import CreateAnomalySubscriptionResponseTypeDef
```

Required fields:

- `SubscriptionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createcostcategorydefinitionrequestrequesttypedef"></a>

## CreateCostCategoryDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import CreateCostCategoryDefinitionRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `RuleVersion`: `Literal['CostCategoryExpression.v1']` (see
  [CostCategoryRuleVersionType](./literals.md#costcategoryruleversiontype))
- `Rules`:
  `Sequence`\[[CostCategoryRuleTypeDef](./type_defs.md#costcategoryruletypedef)\]

Optional fields:

- `DefaultValue`: `str`
- `SplitChargeRules`:
  `Sequence`\[[CostCategorySplitChargeRuleTypeDef](./type_defs.md#costcategorysplitchargeruletypedef)\]

<a id="createcostcategorydefinitionresponsetypedef"></a>

## CreateCostCategoryDefinitionResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import CreateCostCategoryDefinitionResponseTypeDef
```

Required fields:

- `CostCategoryArn`: `str`
- `EffectiveStart`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="currentinstancetypedef"></a>

## CurrentInstanceTypeDef

```python
from types_aiobotocore_ce.type_defs import CurrentInstanceTypeDef
```

Optional fields:

- `ResourceId`: `str`
- `InstanceName`: `str`
- `Tags`: `List`\[[TagValuesTypeDef](./type_defs.md#tagvaluestypedef)\]
- `ResourceDetails`:
  [ResourceDetailsTypeDef](./type_defs.md#resourcedetailstypedef)
- `ResourceUtilization`:
  [ResourceUtilizationTypeDef](./type_defs.md#resourceutilizationtypedef)
- `ReservationCoveredHoursInLookbackPeriod`: `str`
- `SavingsPlansCoveredHoursInLookbackPeriod`: `str`
- `OnDemandHoursInLookbackPeriod`: `str`
- `TotalRunningHoursInLookbackPeriod`: `str`
- `MonthlyCost`: `str`
- `CurrencyCode`: `str`

<a id="dateintervaltypedef"></a>

## DateIntervalTypeDef

```python
from types_aiobotocore_ce.type_defs import DateIntervalTypeDef
```

Required fields:

- `Start`: `str`
- `End`: `str`

<a id="deleteanomalymonitorrequestrequesttypedef"></a>

## DeleteAnomalyMonitorRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import DeleteAnomalyMonitorRequestRequestTypeDef
```

Required fields:

- `MonitorArn`: `str`

<a id="deleteanomalysubscriptionrequestrequesttypedef"></a>

## DeleteAnomalySubscriptionRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import DeleteAnomalySubscriptionRequestRequestTypeDef
```

Required fields:

- `SubscriptionArn`: `str`

<a id="deletecostcategorydefinitionrequestrequesttypedef"></a>

## DeleteCostCategoryDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import DeleteCostCategoryDefinitionRequestRequestTypeDef
```

Required fields:

- `CostCategoryArn`: `str`

<a id="deletecostcategorydefinitionresponsetypedef"></a>

## DeleteCostCategoryDefinitionResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import DeleteCostCategoryDefinitionResponseTypeDef
```

Required fields:

- `CostCategoryArn`: `str`
- `EffectiveEnd`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describecostcategorydefinitionrequestrequesttypedef"></a>

## DescribeCostCategoryDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import DescribeCostCategoryDefinitionRequestRequestTypeDef
```

Required fields:

- `CostCategoryArn`: `str`

Optional fields:

- `EffectiveOn`: `str`

<a id="describecostcategorydefinitionresponsetypedef"></a>

## DescribeCostCategoryDefinitionResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import DescribeCostCategoryDefinitionResponseTypeDef
```

Required fields:

- `CostCategory`: [CostCategoryTypeDef](./type_defs.md#costcategorytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dimensionvaluestypedef"></a>

## DimensionValuesTypeDef

```python
from types_aiobotocore_ce.type_defs import DimensionValuesTypeDef
```

Optional fields:

- `Key`: [DimensionType](./literals.md#dimensiontype)
- `Values`: `Sequence`\[`str`\]
- `MatchOptions`:
  `Sequence`\[[MatchOptionType](./literals.md#matchoptiontype)\]

<a id="dimensionvalueswithattributestypedef"></a>

## DimensionValuesWithAttributesTypeDef

```python
from types_aiobotocore_ce.type_defs import DimensionValuesWithAttributesTypeDef
```

Optional fields:

- `Value`: `str`
- `Attributes`: `Dict`\[`str`, `str`\]

<a id="diskresourceutilizationtypedef"></a>

## DiskResourceUtilizationTypeDef

```python
from types_aiobotocore_ce.type_defs import DiskResourceUtilizationTypeDef
```

Optional fields:

- `DiskReadOpsPerSecond`: `str`
- `DiskWriteOpsPerSecond`: `str`
- `DiskReadBytesPerSecond`: `str`
- `DiskWriteBytesPerSecond`: `str`

<a id="ebsresourceutilizationtypedef"></a>

## EBSResourceUtilizationTypeDef

```python
from types_aiobotocore_ce.type_defs import EBSResourceUtilizationTypeDef
```

Optional fields:

- `EbsReadOpsPerSecond`: `str`
- `EbsWriteOpsPerSecond`: `str`
- `EbsReadBytesPerSecond`: `str`
- `EbsWriteBytesPerSecond`: `str`

<a id="ec2instancedetailstypedef"></a>

## EC2InstanceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import EC2InstanceDetailsTypeDef
```

Optional fields:

- `Family`: `str`
- `InstanceType`: `str`
- `Region`: `str`
- `AvailabilityZone`: `str`
- `Platform`: `str`
- `Tenancy`: `str`
- `CurrentGeneration`: `bool`
- `SizeFlexEligible`: `bool`

<a id="ec2resourcedetailstypedef"></a>

## EC2ResourceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import EC2ResourceDetailsTypeDef
```

Optional fields:

- `HourlyOnDemandRate`: `str`
- `InstanceType`: `str`
- `Platform`: `str`
- `Region`: `str`
- `Sku`: `str`
- `Memory`: `str`
- `NetworkPerformance`: `str`
- `Storage`: `str`
- `Vcpu`: `str`

<a id="ec2resourceutilizationtypedef"></a>

## EC2ResourceUtilizationTypeDef

```python
from types_aiobotocore_ce.type_defs import EC2ResourceUtilizationTypeDef
```

Optional fields:

- `MaxCpuUtilizationPercentage`: `str`
- `MaxMemoryUtilizationPercentage`: `str`
- `MaxStorageUtilizationPercentage`: `str`
- `EBSResourceUtilization`:
  [EBSResourceUtilizationTypeDef](./type_defs.md#ebsresourceutilizationtypedef)
- `DiskResourceUtilization`:
  [DiskResourceUtilizationTypeDef](./type_defs.md#diskresourceutilizationtypedef)
- `NetworkResourceUtilization`:
  [NetworkResourceUtilizationTypeDef](./type_defs.md#networkresourceutilizationtypedef)

<a id="ec2specificationtypedef"></a>

## EC2SpecificationTypeDef

```python
from types_aiobotocore_ce.type_defs import EC2SpecificationTypeDef
```

Optional fields:

- `OfferingClass`: [OfferingClassType](./literals.md#offeringclasstype)

<a id="esinstancedetailstypedef"></a>

## ESInstanceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import ESInstanceDetailsTypeDef
```

Optional fields:

- `InstanceClass`: `str`
- `InstanceSize`: `str`
- `Region`: `str`
- `CurrentGeneration`: `bool`
- `SizeFlexEligible`: `bool`

<a id="elasticacheinstancedetailstypedef"></a>

## ElastiCacheInstanceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import ElastiCacheInstanceDetailsTypeDef
```

Optional fields:

- `Family`: `str`
- `NodeType`: `str`
- `Region`: `str`
- `ProductDescription`: `str`
- `CurrentGeneration`: `bool`
- `SizeFlexEligible`: `bool`

<a id="expressiontypedef"></a>

## ExpressionTypeDef

```python
from types_aiobotocore_ce.type_defs import ExpressionTypeDef
```

Optional fields:

- `Or`: `Sequence`\[[ExpressionTypeDef](./type_defs.md#expressiontypedef)\]
- `And`: `Sequence`\[[ExpressionTypeDef](./type_defs.md#expressiontypedef)\]
- `Not`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `Dimensions`: [DimensionValuesTypeDef](./type_defs.md#dimensionvaluestypedef)
- `Tags`: [TagValuesTypeDef](./type_defs.md#tagvaluestypedef)
- `CostCategories`:
  [CostCategoryValuesTypeDef](./type_defs.md#costcategoryvaluestypedef)

<a id="forecastresulttypedef"></a>

## ForecastResultTypeDef

```python
from types_aiobotocore_ce.type_defs import ForecastResultTypeDef
```

Optional fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `MeanValue`: `str`
- `PredictionIntervalLowerBound`: `str`
- `PredictionIntervalUpperBound`: `str`

<a id="getanomaliesrequestrequesttypedef"></a>

## GetAnomaliesRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetAnomaliesRequestRequestTypeDef
```

Required fields:

- `DateInterval`:
  [AnomalyDateIntervalTypeDef](./type_defs.md#anomalydateintervaltypedef)

Optional fields:

- `MonitorArn`: `str`
- `Feedback`: [AnomalyFeedbackTypeType](./literals.md#anomalyfeedbacktypetype)
- `TotalImpact`:
  [TotalImpactFilterTypeDef](./type_defs.md#totalimpactfiltertypedef)
- `NextPageToken`: `str`
- `MaxResults`: `int`

<a id="getanomaliesresponsetypedef"></a>

## GetAnomaliesResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetAnomaliesResponseTypeDef
```

Required fields:

- `Anomalies`: `List`\[[AnomalyTypeDef](./type_defs.md#anomalytypedef)\]
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getanomalymonitorsrequestrequesttypedef"></a>

## GetAnomalyMonitorsRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetAnomalyMonitorsRequestRequestTypeDef
```

Optional fields:

- `MonitorArnList`: `Sequence`\[`str`\]
- `NextPageToken`: `str`
- `MaxResults`: `int`

<a id="getanomalymonitorsresponsetypedef"></a>

## GetAnomalyMonitorsResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetAnomalyMonitorsResponseTypeDef
```

Required fields:

- `AnomalyMonitors`:
  `List`\[[AnomalyMonitorTypeDef](./type_defs.md#anomalymonitortypedef)\]
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getanomalysubscriptionsrequestrequesttypedef"></a>

## GetAnomalySubscriptionsRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetAnomalySubscriptionsRequestRequestTypeDef
```

Optional fields:

- `SubscriptionArnList`: `Sequence`\[`str`\]
- `MonitorArn`: `str`
- `NextPageToken`: `str`
- `MaxResults`: `int`

<a id="getanomalysubscriptionsresponsetypedef"></a>

## GetAnomalySubscriptionsResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetAnomalySubscriptionsResponseTypeDef
```

Required fields:

- `AnomalySubscriptions`:
  `List`\[[AnomalySubscriptionTypeDef](./type_defs.md#anomalysubscriptiontypedef)\]
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcostandusagerequestrequesttypedef"></a>

## GetCostAndUsageRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostAndUsageRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Granularity`: [GranularityType](./literals.md#granularitytype)
- `Metrics`: `Sequence`\[`str`\]

Optional fields:

- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `GroupBy`:
  `Sequence`\[[GroupDefinitionTypeDef](./type_defs.md#groupdefinitiontypedef)\]
- `NextPageToken`: `str`

<a id="getcostandusageresponsetypedef"></a>

## GetCostAndUsageResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostAndUsageResponseTypeDef
```

Required fields:

- `NextPageToken`: `str`
- `GroupDefinitions`:
  `List`\[[GroupDefinitionTypeDef](./type_defs.md#groupdefinitiontypedef)\]
- `ResultsByTime`:
  `List`\[[ResultByTimeTypeDef](./type_defs.md#resultbytimetypedef)\]
- `DimensionValueAttributes`:
  `List`\[[DimensionValuesWithAttributesTypeDef](./type_defs.md#dimensionvalueswithattributestypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcostandusagewithresourcesrequestrequesttypedef"></a>

## GetCostAndUsageWithResourcesRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostAndUsageWithResourcesRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Granularity`: [GranularityType](./literals.md#granularitytype)
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)

Optional fields:

- `Metrics`: `Sequence`\[`str`\]
- `GroupBy`:
  `Sequence`\[[GroupDefinitionTypeDef](./type_defs.md#groupdefinitiontypedef)\]
- `NextPageToken`: `str`

<a id="getcostandusagewithresourcesresponsetypedef"></a>

## GetCostAndUsageWithResourcesResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostAndUsageWithResourcesResponseTypeDef
```

Required fields:

- `NextPageToken`: `str`
- `GroupDefinitions`:
  `List`\[[GroupDefinitionTypeDef](./type_defs.md#groupdefinitiontypedef)\]
- `ResultsByTime`:
  `List`\[[ResultByTimeTypeDef](./type_defs.md#resultbytimetypedef)\]
- `DimensionValueAttributes`:
  `List`\[[DimensionValuesWithAttributesTypeDef](./type_defs.md#dimensionvalueswithattributestypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcostcategoriesrequestrequesttypedef"></a>

## GetCostCategoriesRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostCategoriesRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

Optional fields:

- `SearchString`: `str`
- `CostCategoryName`: `str`
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `SortBy`:
  `Sequence`\[[SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)\]
- `MaxResults`: `int`
- `NextPageToken`: `str`

<a id="getcostcategoriesresponsetypedef"></a>

## GetCostCategoriesResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostCategoriesResponseTypeDef
```

Required fields:

- `NextPageToken`: `str`
- `CostCategoryNames`: `List`\[`str`\]
- `CostCategoryValues`: `List`\[`str`\]
- `ReturnSize`: `int`
- `TotalSize`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcostforecastrequestrequesttypedef"></a>

## GetCostForecastRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostForecastRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Metric`: [MetricType](./literals.md#metrictype)
- `Granularity`: [GranularityType](./literals.md#granularitytype)

Optional fields:

- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `PredictionIntervalLevel`: `int`

<a id="getcostforecastresponsetypedef"></a>

## GetCostForecastResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetCostForecastResponseTypeDef
```

Required fields:

- `Total`: [MetricValueTypeDef](./type_defs.md#metricvaluetypedef)
- `ForecastResultsByTime`:
  `List`\[[ForecastResultTypeDef](./type_defs.md#forecastresulttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdimensionvaluesrequestrequesttypedef"></a>

## GetDimensionValuesRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetDimensionValuesRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Dimension`: [DimensionType](./literals.md#dimensiontype)

Optional fields:

- `SearchString`: `str`
- `Context`: [ContextType](./literals.md#contexttype)
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `SortBy`:
  `Sequence`\[[SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)\]
- `MaxResults`: `int`
- `NextPageToken`: `str`

<a id="getdimensionvaluesresponsetypedef"></a>

## GetDimensionValuesResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetDimensionValuesResponseTypeDef
```

Required fields:

- `DimensionValues`:
  `List`\[[DimensionValuesWithAttributesTypeDef](./type_defs.md#dimensionvalueswithattributestypedef)\]
- `ReturnSize`: `int`
- `TotalSize`: `int`
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getreservationcoveragerequestrequesttypedef"></a>

## GetReservationCoverageRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetReservationCoverageRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

Optional fields:

- `GroupBy`:
  `Sequence`\[[GroupDefinitionTypeDef](./type_defs.md#groupdefinitiontypedef)\]
- `Granularity`: [GranularityType](./literals.md#granularitytype)
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `Metrics`: `Sequence`\[`str`\]
- `NextPageToken`: `str`
- `SortBy`: [SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)
- `MaxResults`: `int`

<a id="getreservationcoverageresponsetypedef"></a>

## GetReservationCoverageResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetReservationCoverageResponseTypeDef
```

Required fields:

- `CoveragesByTime`:
  `List`\[[CoverageByTimeTypeDef](./type_defs.md#coveragebytimetypedef)\]
- `Total`: [CoverageTypeDef](./type_defs.md#coveragetypedef)
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getreservationpurchaserecommendationrequestrequesttypedef"></a>

## GetReservationPurchaseRecommendationRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetReservationPurchaseRecommendationRequestRequestTypeDef
```

Required fields:

- `Service`: `str`

Optional fields:

- `AccountId`: `str`
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `AccountScope`: [AccountScopeType](./literals.md#accountscopetype)
- `LookbackPeriodInDays`:
  [LookbackPeriodInDaysType](./literals.md#lookbackperiodindaystype)
- `TermInYears`: [TermInYearsType](./literals.md#terminyearstype)
- `PaymentOption`: [PaymentOptionType](./literals.md#paymentoptiontype)
- `ServiceSpecification`:
  [ServiceSpecificationTypeDef](./type_defs.md#servicespecificationtypedef)
- `PageSize`: `int`
- `NextPageToken`: `str`

<a id="getreservationpurchaserecommendationresponsetypedef"></a>

## GetReservationPurchaseRecommendationResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetReservationPurchaseRecommendationResponseTypeDef
```

Required fields:

- `Metadata`:
  [ReservationPurchaseRecommendationMetadataTypeDef](./type_defs.md#reservationpurchaserecommendationmetadatatypedef)
- `Recommendations`:
  `List`\[[ReservationPurchaseRecommendationTypeDef](./type_defs.md#reservationpurchaserecommendationtypedef)\]
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getreservationutilizationrequestrequesttypedef"></a>

## GetReservationUtilizationRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetReservationUtilizationRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

Optional fields:

- `GroupBy`:
  `Sequence`\[[GroupDefinitionTypeDef](./type_defs.md#groupdefinitiontypedef)\]
- `Granularity`: [GranularityType](./literals.md#granularitytype)
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `SortBy`: [SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)
- `NextPageToken`: `str`
- `MaxResults`: `int`

<a id="getreservationutilizationresponsetypedef"></a>

## GetReservationUtilizationResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetReservationUtilizationResponseTypeDef
```

Required fields:

- `UtilizationsByTime`:
  `List`\[[UtilizationByTimeTypeDef](./type_defs.md#utilizationbytimetypedef)\]
- `Total`:
  [ReservationAggregatesTypeDef](./type_defs.md#reservationaggregatestypedef)
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getrightsizingrecommendationrequestrequesttypedef"></a>

## GetRightsizingRecommendationRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetRightsizingRecommendationRequestRequestTypeDef
```

Required fields:

- `Service`: `str`

Optional fields:

- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `Configuration`:
  [RightsizingRecommendationConfigurationTypeDef](./type_defs.md#rightsizingrecommendationconfigurationtypedef)
- `PageSize`: `int`
- `NextPageToken`: `str`

<a id="getrightsizingrecommendationresponsetypedef"></a>

## GetRightsizingRecommendationResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetRightsizingRecommendationResponseTypeDef
```

Required fields:

- `Metadata`:
  [RightsizingRecommendationMetadataTypeDef](./type_defs.md#rightsizingrecommendationmetadatatypedef)
- `Summary`:
  [RightsizingRecommendationSummaryTypeDef](./type_defs.md#rightsizingrecommendationsummarytypedef)
- `RightsizingRecommendations`:
  `List`\[[RightsizingRecommendationTypeDef](./type_defs.md#rightsizingrecommendationtypedef)\]
- `NextPageToken`: `str`
- `Configuration`:
  [RightsizingRecommendationConfigurationTypeDef](./type_defs.md#rightsizingrecommendationconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsavingsplanscoveragerequestrequesttypedef"></a>

## GetSavingsPlansCoverageRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansCoverageRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

Optional fields:

- `GroupBy`:
  `Sequence`\[[GroupDefinitionTypeDef](./type_defs.md#groupdefinitiontypedef)\]
- `Granularity`: [GranularityType](./literals.md#granularitytype)
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `Metrics`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`
- `SortBy`: [SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)

<a id="getsavingsplanscoverageresponsetypedef"></a>

## GetSavingsPlansCoverageResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansCoverageResponseTypeDef
```

Required fields:

- `SavingsPlansCoverages`:
  `List`\[[SavingsPlansCoverageTypeDef](./type_defs.md#savingsplanscoveragetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsavingsplanspurchaserecommendationrequestrequesttypedef"></a>

## GetSavingsPlansPurchaseRecommendationRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansPurchaseRecommendationRequestRequestTypeDef
```

Required fields:

- `SavingsPlansType`:
  [SupportedSavingsPlansTypeType](./literals.md#supportedsavingsplanstypetype)
- `TermInYears`: [TermInYearsType](./literals.md#terminyearstype)
- `PaymentOption`: [PaymentOptionType](./literals.md#paymentoptiontype)
- `LookbackPeriodInDays`:
  [LookbackPeriodInDaysType](./literals.md#lookbackperiodindaystype)

Optional fields:

- `AccountScope`: [AccountScopeType](./literals.md#accountscopetype)
- `NextPageToken`: `str`
- `PageSize`: `int`
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)

<a id="getsavingsplanspurchaserecommendationresponsetypedef"></a>

## GetSavingsPlansPurchaseRecommendationResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansPurchaseRecommendationResponseTypeDef
```

Required fields:

- `Metadata`:
  [SavingsPlansPurchaseRecommendationMetadataTypeDef](./type_defs.md#savingsplanspurchaserecommendationmetadatatypedef)
- `SavingsPlansPurchaseRecommendation`:
  [SavingsPlansPurchaseRecommendationTypeDef](./type_defs.md#savingsplanspurchaserecommendationtypedef)
- `NextPageToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsavingsplansutilizationdetailsrequestrequesttypedef"></a>

## GetSavingsPlansUtilizationDetailsRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansUtilizationDetailsRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

Optional fields:

- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `DataType`:
  `Sequence`\[[SavingsPlansDataTypeType](./literals.md#savingsplansdatatypetype)\]
- `NextToken`: `str`
- `MaxResults`: `int`
- `SortBy`: [SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)

<a id="getsavingsplansutilizationdetailsresponsetypedef"></a>

## GetSavingsPlansUtilizationDetailsResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansUtilizationDetailsResponseTypeDef
```

Required fields:

- `SavingsPlansUtilizationDetails`:
  `List`\[[SavingsPlansUtilizationDetailTypeDef](./type_defs.md#savingsplansutilizationdetailtypedef)\]
- `Total`:
  [SavingsPlansUtilizationAggregatesTypeDef](./type_defs.md#savingsplansutilizationaggregatestypedef)
- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsavingsplansutilizationrequestrequesttypedef"></a>

## GetSavingsPlansUtilizationRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansUtilizationRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

Optional fields:

- `Granularity`: [GranularityType](./literals.md#granularitytype)
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `SortBy`: [SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)

<a id="getsavingsplansutilizationresponsetypedef"></a>

## GetSavingsPlansUtilizationResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetSavingsPlansUtilizationResponseTypeDef
```

Required fields:

- `SavingsPlansUtilizationsByTime`:
  `List`\[[SavingsPlansUtilizationByTimeTypeDef](./type_defs.md#savingsplansutilizationbytimetypedef)\]
- `Total`:
  [SavingsPlansUtilizationAggregatesTypeDef](./type_defs.md#savingsplansutilizationaggregatestypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="gettagsrequestrequesttypedef"></a>

## GetTagsRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetTagsRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

Optional fields:

- `SearchString`: `str`
- `TagKey`: `str`
- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `SortBy`:
  `Sequence`\[[SortDefinitionTypeDef](./type_defs.md#sortdefinitiontypedef)\]
- `MaxResults`: `int`
- `NextPageToken`: `str`

<a id="gettagsresponsetypedef"></a>

## GetTagsResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetTagsResponseTypeDef
```

Required fields:

- `NextPageToken`: `str`
- `Tags`: `List`\[`str`\]
- `ReturnSize`: `int`
- `TotalSize`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getusageforecastrequestrequesttypedef"></a>

## GetUsageForecastRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import GetUsageForecastRequestRequestTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Metric`: [MetricType](./literals.md#metrictype)
- `Granularity`: [GranularityType](./literals.md#granularitytype)

Optional fields:

- `Filter`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- `PredictionIntervalLevel`: `int`

<a id="getusageforecastresponsetypedef"></a>

## GetUsageForecastResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import GetUsageForecastResponseTypeDef
```

Required fields:

- `Total`: [MetricValueTypeDef](./type_defs.md#metricvaluetypedef)
- `ForecastResultsByTime`:
  `List`\[[ForecastResultTypeDef](./type_defs.md#forecastresulttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="groupdefinitiontypedef"></a>

## GroupDefinitionTypeDef

```python
from types_aiobotocore_ce.type_defs import GroupDefinitionTypeDef
```

Optional fields:

- `Type`: [GroupDefinitionTypeType](./literals.md#groupdefinitiontypetype)
- `Key`: `str`

<a id="grouptypedef"></a>

## GroupTypeDef

```python
from types_aiobotocore_ce.type_defs import GroupTypeDef
```

Optional fields:

- `Keys`: `List`\[`str`\]
- `Metrics`: `Dict`\[`str`,
  [MetricValueTypeDef](./type_defs.md#metricvaluetypedef)\]

<a id="impacttypedef"></a>

## ImpactTypeDef

```python
from types_aiobotocore_ce.type_defs import ImpactTypeDef
```

Required fields:

- `MaxImpact`: `float`

Optional fields:

- `TotalImpact`: `float`

<a id="instancedetailstypedef"></a>

## InstanceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import InstanceDetailsTypeDef
```

Optional fields:

- `EC2InstanceDetails`:
  [EC2InstanceDetailsTypeDef](./type_defs.md#ec2instancedetailstypedef)
- `RDSInstanceDetails`:
  [RDSInstanceDetailsTypeDef](./type_defs.md#rdsinstancedetailstypedef)
- `RedshiftInstanceDetails`:
  [RedshiftInstanceDetailsTypeDef](./type_defs.md#redshiftinstancedetailstypedef)
- `ElastiCacheInstanceDetails`:
  [ElastiCacheInstanceDetailsTypeDef](./type_defs.md#elasticacheinstancedetailstypedef)
- `ESInstanceDetails`:
  [ESInstanceDetailsTypeDef](./type_defs.md#esinstancedetailstypedef)

<a id="listcostcategorydefinitionsrequestrequesttypedef"></a>

## ListCostCategoryDefinitionsRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import ListCostCategoryDefinitionsRequestRequestTypeDef
```

Optional fields:

- `EffectiveOn`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listcostcategorydefinitionsresponsetypedef"></a>

## ListCostCategoryDefinitionsResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import ListCostCategoryDefinitionsResponseTypeDef
```

Required fields:

- `CostCategoryReferences`:
  `List`\[[CostCategoryReferenceTypeDef](./type_defs.md#costcategoryreferencetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="metricvaluetypedef"></a>

## MetricValueTypeDef

```python
from types_aiobotocore_ce.type_defs import MetricValueTypeDef
```

Optional fields:

- `Amount`: `str`
- `Unit`: `str`

<a id="modifyrecommendationdetailtypedef"></a>

## ModifyRecommendationDetailTypeDef

```python
from types_aiobotocore_ce.type_defs import ModifyRecommendationDetailTypeDef
```

Optional fields:

- `TargetInstances`:
  `List`\[[TargetInstanceTypeDef](./type_defs.md#targetinstancetypedef)\]

<a id="networkresourceutilizationtypedef"></a>

## NetworkResourceUtilizationTypeDef

```python
from types_aiobotocore_ce.type_defs import NetworkResourceUtilizationTypeDef
```

Optional fields:

- `NetworkInBytesPerSecond`: `str`
- `NetworkOutBytesPerSecond`: `str`
- `NetworkPacketsInPerSecond`: `str`
- `NetworkPacketsOutPerSecond`: `str`

<a id="provideanomalyfeedbackrequestrequesttypedef"></a>

## ProvideAnomalyFeedbackRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import ProvideAnomalyFeedbackRequestRequestTypeDef
```

Required fields:

- `AnomalyId`: `str`
- `Feedback`: [AnomalyFeedbackTypeType](./literals.md#anomalyfeedbacktypetype)

<a id="provideanomalyfeedbackresponsetypedef"></a>

## ProvideAnomalyFeedbackResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import ProvideAnomalyFeedbackResponseTypeDef
```

Required fields:

- `AnomalyId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="rdsinstancedetailstypedef"></a>

## RDSInstanceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import RDSInstanceDetailsTypeDef
```

Optional fields:

- `Family`: `str`
- `InstanceType`: `str`
- `Region`: `str`
- `DatabaseEngine`: `str`
- `DatabaseEdition`: `str`
- `DeploymentOption`: `str`
- `LicenseModel`: `str`
- `CurrentGeneration`: `bool`
- `SizeFlexEligible`: `bool`

<a id="redshiftinstancedetailstypedef"></a>

## RedshiftInstanceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import RedshiftInstanceDetailsTypeDef
```

Optional fields:

- `Family`: `str`
- `NodeType`: `str`
- `Region`: `str`
- `CurrentGeneration`: `bool`
- `SizeFlexEligible`: `bool`

<a id="reservationaggregatestypedef"></a>

## ReservationAggregatesTypeDef

```python
from types_aiobotocore_ce.type_defs import ReservationAggregatesTypeDef
```

Optional fields:

- `UtilizationPercentage`: `str`
- `UtilizationPercentageInUnits`: `str`
- `PurchasedHours`: `str`
- `PurchasedUnits`: `str`
- `TotalActualHours`: `str`
- `TotalActualUnits`: `str`
- `UnusedHours`: `str`
- `UnusedUnits`: `str`
- `OnDemandCostOfRIHoursUsed`: `str`
- `NetRISavings`: `str`
- `TotalPotentialRISavings`: `str`
- `AmortizedUpfrontFee`: `str`
- `AmortizedRecurringFee`: `str`
- `TotalAmortizedFee`: `str`
- `RICostForUnusedHours`: `str`
- `RealizedSavings`: `str`
- `UnrealizedSavings`: `str`

<a id="reservationcoveragegrouptypedef"></a>

## ReservationCoverageGroupTypeDef

```python
from types_aiobotocore_ce.type_defs import ReservationCoverageGroupTypeDef
```

Optional fields:

- `Attributes`: `Dict`\[`str`, `str`\]
- `Coverage`: [CoverageTypeDef](./type_defs.md#coveragetypedef)

<a id="reservationpurchaserecommendationdetailtypedef"></a>

## ReservationPurchaseRecommendationDetailTypeDef

```python
from types_aiobotocore_ce.type_defs import ReservationPurchaseRecommendationDetailTypeDef
```

Optional fields:

- `AccountId`: `str`
- `InstanceDetails`:
  [InstanceDetailsTypeDef](./type_defs.md#instancedetailstypedef)
- `RecommendedNumberOfInstancesToPurchase`: `str`
- `RecommendedNormalizedUnitsToPurchase`: `str`
- `MinimumNumberOfInstancesUsedPerHour`: `str`
- `MinimumNormalizedUnitsUsedPerHour`: `str`
- `MaximumNumberOfInstancesUsedPerHour`: `str`
- `MaximumNormalizedUnitsUsedPerHour`: `str`
- `AverageNumberOfInstancesUsedPerHour`: `str`
- `AverageNormalizedUnitsUsedPerHour`: `str`
- `AverageUtilization`: `str`
- `EstimatedBreakEvenInMonths`: `str`
- `CurrencyCode`: `str`
- `EstimatedMonthlySavingsAmount`: `str`
- `EstimatedMonthlySavingsPercentage`: `str`
- `EstimatedMonthlyOnDemandCost`: `str`
- `EstimatedReservationCostForLookbackPeriod`: `str`
- `UpfrontCost`: `str`
- `RecurringStandardMonthlyCost`: `str`

<a id="reservationpurchaserecommendationmetadatatypedef"></a>

## ReservationPurchaseRecommendationMetadataTypeDef

```python
from types_aiobotocore_ce.type_defs import ReservationPurchaseRecommendationMetadataTypeDef
```

Optional fields:

- `RecommendationId`: `str`
- `GenerationTimestamp`: `str`

<a id="reservationpurchaserecommendationsummarytypedef"></a>

## ReservationPurchaseRecommendationSummaryTypeDef

```python
from types_aiobotocore_ce.type_defs import ReservationPurchaseRecommendationSummaryTypeDef
```

Optional fields:

- `TotalEstimatedMonthlySavingsAmount`: `str`
- `TotalEstimatedMonthlySavingsPercentage`: `str`
- `CurrencyCode`: `str`

<a id="reservationpurchaserecommendationtypedef"></a>

## ReservationPurchaseRecommendationTypeDef

```python
from types_aiobotocore_ce.type_defs import ReservationPurchaseRecommendationTypeDef
```

Optional fields:

- `AccountScope`: [AccountScopeType](./literals.md#accountscopetype)
- `LookbackPeriodInDays`:
  [LookbackPeriodInDaysType](./literals.md#lookbackperiodindaystype)
- `TermInYears`: [TermInYearsType](./literals.md#terminyearstype)
- `PaymentOption`: [PaymentOptionType](./literals.md#paymentoptiontype)
- `ServiceSpecification`:
  [ServiceSpecificationTypeDef](./type_defs.md#servicespecificationtypedef)
- `RecommendationDetails`:
  `List`\[[ReservationPurchaseRecommendationDetailTypeDef](./type_defs.md#reservationpurchaserecommendationdetailtypedef)\]
- `RecommendationSummary`:
  [ReservationPurchaseRecommendationSummaryTypeDef](./type_defs.md#reservationpurchaserecommendationsummarytypedef)

<a id="reservationutilizationgrouptypedef"></a>

## ReservationUtilizationGroupTypeDef

```python
from types_aiobotocore_ce.type_defs import ReservationUtilizationGroupTypeDef
```

Optional fields:

- `Key`: `str`
- `Value`: `str`
- `Attributes`: `Dict`\[`str`, `str`\]
- `Utilization`:
  [ReservationAggregatesTypeDef](./type_defs.md#reservationaggregatestypedef)

<a id="resourcedetailstypedef"></a>

## ResourceDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import ResourceDetailsTypeDef
```

Optional fields:

- `EC2ResourceDetails`:
  [EC2ResourceDetailsTypeDef](./type_defs.md#ec2resourcedetailstypedef)

<a id="resourceutilizationtypedef"></a>

## ResourceUtilizationTypeDef

```python
from types_aiobotocore_ce.type_defs import ResourceUtilizationTypeDef
```

Optional fields:

- `EC2ResourceUtilization`:
  [EC2ResourceUtilizationTypeDef](./type_defs.md#ec2resourceutilizationtypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_ce.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="resultbytimetypedef"></a>

## ResultByTimeTypeDef

```python
from types_aiobotocore_ce.type_defs import ResultByTimeTypeDef
```

Optional fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Total`: `Dict`\[`str`,
  [MetricValueTypeDef](./type_defs.md#metricvaluetypedef)\]
- `Groups`: `List`\[[GroupTypeDef](./type_defs.md#grouptypedef)\]
- `Estimated`: `bool`

<a id="rightsizingrecommendationconfigurationtypedef"></a>

## RightsizingRecommendationConfigurationTypeDef

```python
from types_aiobotocore_ce.type_defs import RightsizingRecommendationConfigurationTypeDef
```

Required fields:

- `RecommendationTarget`:
  [RecommendationTargetType](./literals.md#recommendationtargettype)
- `BenefitsConsidered`: `bool`

<a id="rightsizingrecommendationmetadatatypedef"></a>

## RightsizingRecommendationMetadataTypeDef

```python
from types_aiobotocore_ce.type_defs import RightsizingRecommendationMetadataTypeDef
```

Optional fields:

- `RecommendationId`: `str`
- `GenerationTimestamp`: `str`
- `LookbackPeriodInDays`:
  [LookbackPeriodInDaysType](./literals.md#lookbackperiodindaystype)
- `AdditionalMetadata`: `str`

<a id="rightsizingrecommendationsummarytypedef"></a>

## RightsizingRecommendationSummaryTypeDef

```python
from types_aiobotocore_ce.type_defs import RightsizingRecommendationSummaryTypeDef
```

Optional fields:

- `TotalRecommendationCount`: `str`
- `EstimatedTotalMonthlySavingsAmount`: `str`
- `SavingsCurrencyCode`: `str`
- `SavingsPercentage`: `str`

<a id="rightsizingrecommendationtypedef"></a>

## RightsizingRecommendationTypeDef

```python
from types_aiobotocore_ce.type_defs import RightsizingRecommendationTypeDef
```

Optional fields:

- `AccountId`: `str`
- `CurrentInstance`:
  [CurrentInstanceTypeDef](./type_defs.md#currentinstancetypedef)
- `RightsizingType`: [RightsizingTypeType](./literals.md#rightsizingtypetype)
- `ModifyRecommendationDetail`:
  [ModifyRecommendationDetailTypeDef](./type_defs.md#modifyrecommendationdetailtypedef)
- `TerminateRecommendationDetail`:
  [TerminateRecommendationDetailTypeDef](./type_defs.md#terminaterecommendationdetailtypedef)
- `FindingReasonCodes`:
  `List`\[[FindingReasonCodeType](./literals.md#findingreasoncodetype)\]

<a id="rootcausetypedef"></a>

## RootCauseTypeDef

```python
from types_aiobotocore_ce.type_defs import RootCauseTypeDef
```

Optional fields:

- `Service`: `str`
- `Region`: `str`
- `LinkedAccount`: `str`
- `UsageType`: `str`

<a id="savingsplansamortizedcommitmenttypedef"></a>

## SavingsPlansAmortizedCommitmentTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansAmortizedCommitmentTypeDef
```

Optional fields:

- `AmortizedRecurringCommitment`: `str`
- `AmortizedUpfrontCommitment`: `str`
- `TotalAmortizedCommitment`: `str`

<a id="savingsplanscoveragedatatypedef"></a>

## SavingsPlansCoverageDataTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansCoverageDataTypeDef
```

Optional fields:

- `SpendCoveredBySavingsPlans`: `str`
- `OnDemandCost`: `str`
- `TotalCost`: `str`
- `CoveragePercentage`: `str`

<a id="savingsplanscoveragetypedef"></a>

## SavingsPlansCoverageTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansCoverageTypeDef
```

Optional fields:

- `Attributes`: `Dict`\[`str`, `str`\]
- `Coverage`:
  [SavingsPlansCoverageDataTypeDef](./type_defs.md#savingsplanscoveragedatatypedef)
- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)

<a id="savingsplansdetailstypedef"></a>

## SavingsPlansDetailsTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansDetailsTypeDef
```

Optional fields:

- `Region`: `str`
- `InstanceFamily`: `str`
- `OfferingId`: `str`

<a id="savingsplanspurchaserecommendationdetailtypedef"></a>

## SavingsPlansPurchaseRecommendationDetailTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansPurchaseRecommendationDetailTypeDef
```

Optional fields:

- `SavingsPlansDetails`:
  [SavingsPlansDetailsTypeDef](./type_defs.md#savingsplansdetailstypedef)
- `AccountId`: `str`
- `UpfrontCost`: `str`
- `EstimatedROI`: `str`
- `CurrencyCode`: `str`
- `EstimatedSPCost`: `str`
- `EstimatedOnDemandCost`: `str`
- `EstimatedOnDemandCostWithCurrentCommitment`: `str`
- `EstimatedSavingsAmount`: `str`
- `EstimatedSavingsPercentage`: `str`
- `HourlyCommitmentToPurchase`: `str`
- `EstimatedAverageUtilization`: `str`
- `EstimatedMonthlySavingsAmount`: `str`
- `CurrentMinimumHourlyOnDemandSpend`: `str`
- `CurrentMaximumHourlyOnDemandSpend`: `str`
- `CurrentAverageHourlyOnDemandSpend`: `str`

<a id="savingsplanspurchaserecommendationmetadatatypedef"></a>

## SavingsPlansPurchaseRecommendationMetadataTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansPurchaseRecommendationMetadataTypeDef
```

Optional fields:

- `RecommendationId`: `str`
- `GenerationTimestamp`: `str`
- `AdditionalMetadata`: `str`

<a id="savingsplanspurchaserecommendationsummarytypedef"></a>

## SavingsPlansPurchaseRecommendationSummaryTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansPurchaseRecommendationSummaryTypeDef
```

Optional fields:

- `EstimatedROI`: `str`
- `CurrencyCode`: `str`
- `EstimatedTotalCost`: `str`
- `CurrentOnDemandSpend`: `str`
- `EstimatedSavingsAmount`: `str`
- `TotalRecommendationCount`: `str`
- `DailyCommitmentToPurchase`: `str`
- `HourlyCommitmentToPurchase`: `str`
- `EstimatedSavingsPercentage`: `str`
- `EstimatedMonthlySavingsAmount`: `str`
- `EstimatedOnDemandCostWithCurrentCommitment`: `str`

<a id="savingsplanspurchaserecommendationtypedef"></a>

## SavingsPlansPurchaseRecommendationTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansPurchaseRecommendationTypeDef
```

Optional fields:

- `AccountScope`: [AccountScopeType](./literals.md#accountscopetype)
- `SavingsPlansType`:
  [SupportedSavingsPlansTypeType](./literals.md#supportedsavingsplanstypetype)
- `TermInYears`: [TermInYearsType](./literals.md#terminyearstype)
- `PaymentOption`: [PaymentOptionType](./literals.md#paymentoptiontype)
- `LookbackPeriodInDays`:
  [LookbackPeriodInDaysType](./literals.md#lookbackperiodindaystype)
- `SavingsPlansPurchaseRecommendationDetails`:
  `List`\[[SavingsPlansPurchaseRecommendationDetailTypeDef](./type_defs.md#savingsplanspurchaserecommendationdetailtypedef)\]
- `SavingsPlansPurchaseRecommendationSummary`:
  [SavingsPlansPurchaseRecommendationSummaryTypeDef](./type_defs.md#savingsplanspurchaserecommendationsummarytypedef)

<a id="savingsplanssavingstypedef"></a>

## SavingsPlansSavingsTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansSavingsTypeDef
```

Optional fields:

- `NetSavings`: `str`
- `OnDemandCostEquivalent`: `str`

<a id="savingsplansutilizationaggregatestypedef"></a>

## SavingsPlansUtilizationAggregatesTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansUtilizationAggregatesTypeDef
```

Required fields:

- `Utilization`:
  [SavingsPlansUtilizationTypeDef](./type_defs.md#savingsplansutilizationtypedef)

Optional fields:

- `Savings`:
  [SavingsPlansSavingsTypeDef](./type_defs.md#savingsplanssavingstypedef)
- `AmortizedCommitment`:
  [SavingsPlansAmortizedCommitmentTypeDef](./type_defs.md#savingsplansamortizedcommitmenttypedef)

<a id="savingsplansutilizationbytimetypedef"></a>

## SavingsPlansUtilizationByTimeTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansUtilizationByTimeTypeDef
```

Required fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Utilization`:
  [SavingsPlansUtilizationTypeDef](./type_defs.md#savingsplansutilizationtypedef)

Optional fields:

- `Savings`:
  [SavingsPlansSavingsTypeDef](./type_defs.md#savingsplanssavingstypedef)
- `AmortizedCommitment`:
  [SavingsPlansAmortizedCommitmentTypeDef](./type_defs.md#savingsplansamortizedcommitmenttypedef)

<a id="savingsplansutilizationdetailtypedef"></a>

## SavingsPlansUtilizationDetailTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansUtilizationDetailTypeDef
```

Optional fields:

- `SavingsPlanArn`: `str`
- `Attributes`: `Dict`\[`str`, `str`\]
- `Utilization`:
  [SavingsPlansUtilizationTypeDef](./type_defs.md#savingsplansutilizationtypedef)
- `Savings`:
  [SavingsPlansSavingsTypeDef](./type_defs.md#savingsplanssavingstypedef)
- `AmortizedCommitment`:
  [SavingsPlansAmortizedCommitmentTypeDef](./type_defs.md#savingsplansamortizedcommitmenttypedef)

<a id="savingsplansutilizationtypedef"></a>

## SavingsPlansUtilizationTypeDef

```python
from types_aiobotocore_ce.type_defs import SavingsPlansUtilizationTypeDef
```

Optional fields:

- `TotalCommitment`: `str`
- `UsedCommitment`: `str`
- `UnusedCommitment`: `str`
- `UtilizationPercentage`: `str`

<a id="servicespecificationtypedef"></a>

## ServiceSpecificationTypeDef

```python
from types_aiobotocore_ce.type_defs import ServiceSpecificationTypeDef
```

Optional fields:

- `EC2Specification`:
  [EC2SpecificationTypeDef](./type_defs.md#ec2specificationtypedef)

<a id="sortdefinitiontypedef"></a>

## SortDefinitionTypeDef

```python
from types_aiobotocore_ce.type_defs import SortDefinitionTypeDef
```

Required fields:

- `Key`: `str`

Optional fields:

- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="subscribertypedef"></a>

## SubscriberTypeDef

```python
from types_aiobotocore_ce.type_defs import SubscriberTypeDef
```

Optional fields:

- `Address`: `str`
- `Type`: [SubscriberTypeType](./literals.md#subscribertypetype)
- `Status`: [SubscriberStatusType](./literals.md#subscriberstatustype)

<a id="tagvaluestypedef"></a>

## TagValuesTypeDef

```python
from types_aiobotocore_ce.type_defs import TagValuesTypeDef
```

Optional fields:

- `Key`: `str`
- `Values`: `Sequence`\[`str`\]
- `MatchOptions`:
  `Sequence`\[[MatchOptionType](./literals.md#matchoptiontype)\]

<a id="targetinstancetypedef"></a>

## TargetInstanceTypeDef

```python
from types_aiobotocore_ce.type_defs import TargetInstanceTypeDef
```

Optional fields:

- `EstimatedMonthlyCost`: `str`
- `EstimatedMonthlySavings`: `str`
- `CurrencyCode`: `str`
- `DefaultTargetInstance`: `bool`
- `ResourceDetails`:
  [ResourceDetailsTypeDef](./type_defs.md#resourcedetailstypedef)
- `ExpectedResourceUtilization`:
  [ResourceUtilizationTypeDef](./type_defs.md#resourceutilizationtypedef)
- `PlatformDifferences`:
  `List`\[[PlatformDifferenceType](./literals.md#platformdifferencetype)\]

<a id="terminaterecommendationdetailtypedef"></a>

## TerminateRecommendationDetailTypeDef

```python
from types_aiobotocore_ce.type_defs import TerminateRecommendationDetailTypeDef
```

Optional fields:

- `EstimatedMonthlySavings`: `str`
- `CurrencyCode`: `str`

<a id="totalimpactfiltertypedef"></a>

## TotalImpactFilterTypeDef

```python
from types_aiobotocore_ce.type_defs import TotalImpactFilterTypeDef
```

Required fields:

- `NumericOperator`: [NumericOperatorType](./literals.md#numericoperatortype)
- `StartValue`: `float`

Optional fields:

- `EndValue`: `float`

<a id="updateanomalymonitorrequestrequesttypedef"></a>

## UpdateAnomalyMonitorRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import UpdateAnomalyMonitorRequestRequestTypeDef
```

Required fields:

- `MonitorArn`: `str`

Optional fields:

- `MonitorName`: `str`

<a id="updateanomalymonitorresponsetypedef"></a>

## UpdateAnomalyMonitorResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import UpdateAnomalyMonitorResponseTypeDef
```

Required fields:

- `MonitorArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateanomalysubscriptionrequestrequesttypedef"></a>

## UpdateAnomalySubscriptionRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import UpdateAnomalySubscriptionRequestRequestTypeDef
```

Required fields:

- `SubscriptionArn`: `str`

Optional fields:

- `Threshold`: `float`
- `Frequency`:
  [AnomalySubscriptionFrequencyType](./literals.md#anomalysubscriptionfrequencytype)
- `MonitorArnList`: `Sequence`\[`str`\]
- `Subscribers`:
  `Sequence`\[[SubscriberTypeDef](./type_defs.md#subscribertypedef)\]
- `SubscriptionName`: `str`

<a id="updateanomalysubscriptionresponsetypedef"></a>

## UpdateAnomalySubscriptionResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import UpdateAnomalySubscriptionResponseTypeDef
```

Required fields:

- `SubscriptionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatecostcategorydefinitionrequestrequesttypedef"></a>

## UpdateCostCategoryDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_ce.type_defs import UpdateCostCategoryDefinitionRequestRequestTypeDef
```

Required fields:

- `CostCategoryArn`: `str`
- `RuleVersion`: `Literal['CostCategoryExpression.v1']` (see
  [CostCategoryRuleVersionType](./literals.md#costcategoryruleversiontype))
- `Rules`:
  `Sequence`\[[CostCategoryRuleTypeDef](./type_defs.md#costcategoryruletypedef)\]

Optional fields:

- `DefaultValue`: `str`
- `SplitChargeRules`:
  `Sequence`\[[CostCategorySplitChargeRuleTypeDef](./type_defs.md#costcategorysplitchargeruletypedef)\]

<a id="updatecostcategorydefinitionresponsetypedef"></a>

## UpdateCostCategoryDefinitionResponseTypeDef

```python
from types_aiobotocore_ce.type_defs import UpdateCostCategoryDefinitionResponseTypeDef
```

Required fields:

- `CostCategoryArn`: `str`
- `EffectiveStart`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="utilizationbytimetypedef"></a>

## UtilizationByTimeTypeDef

```python
from types_aiobotocore_ce.type_defs import UtilizationByTimeTypeDef
```

Optional fields:

- `TimePeriod`: [DateIntervalTypeDef](./type_defs.md#dateintervaltypedef)
- `Groups`:
  `List`\[[ReservationUtilizationGroupTypeDef](./type_defs.md#reservationutilizationgrouptypedef)\]
- `Total`:
  [ReservationAggregatesTypeDef](./type_defs.md#reservationaggregatestypedef)
