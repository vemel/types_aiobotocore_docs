<a id="typed-dictionaries-for-aiobotocore-forecastservice-module"></a>

# Typed dictionaries for aiobotocore ForecastService module

> [Index](../README.md) > [ForecastService](./README.md) > Typed dictionaries

Auto-generated documentation for
[ForecastService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecast.html#ForecastService)
type annotations stubs module
[types-aiobotocore-forecast](https://pypi.org/project/types-aiobotocore-forecast/).

- [Typed dictionaries for aiobotocore ForecastService module](#typed-dictionaries-for-aiobotocore-forecastservice-module)
  - [AdditionalDatasetTypeDef](#additionaldatasettypedef)
  - [AttributeConfigTypeDef](#attributeconfigtypedef)
  - [CategoricalParameterRangeTypeDef](#categoricalparameterrangetypedef)
  - [ContinuousParameterRangeTypeDef](#continuousparameterrangetypedef)
  - [CreateAutoPredictorRequestRequestTypeDef](#createautopredictorrequestrequesttypedef)
  - [CreateAutoPredictorResponseTypeDef](#createautopredictorresponsetypedef)
  - [CreateDatasetGroupRequestRequestTypeDef](#createdatasetgrouprequestrequesttypedef)
  - [CreateDatasetGroupResponseTypeDef](#createdatasetgroupresponsetypedef)
  - [CreateDatasetImportJobRequestRequestTypeDef](#createdatasetimportjobrequestrequesttypedef)
  - [CreateDatasetImportJobResponseTypeDef](#createdatasetimportjobresponsetypedef)
  - [CreateDatasetRequestRequestTypeDef](#createdatasetrequestrequesttypedef)
  - [CreateDatasetResponseTypeDef](#createdatasetresponsetypedef)
  - [CreateExplainabilityExportRequestRequestTypeDef](#createexplainabilityexportrequestrequesttypedef)
  - [CreateExplainabilityExportResponseTypeDef](#createexplainabilityexportresponsetypedef)
  - [CreateExplainabilityRequestRequestTypeDef](#createexplainabilityrequestrequesttypedef)
  - [CreateExplainabilityResponseTypeDef](#createexplainabilityresponsetypedef)
  - [CreateForecastExportJobRequestRequestTypeDef](#createforecastexportjobrequestrequesttypedef)
  - [CreateForecastExportJobResponseTypeDef](#createforecastexportjobresponsetypedef)
  - [CreateForecastRequestRequestTypeDef](#createforecastrequestrequesttypedef)
  - [CreateForecastResponseTypeDef](#createforecastresponsetypedef)
  - [CreatePredictorBacktestExportJobRequestRequestTypeDef](#createpredictorbacktestexportjobrequestrequesttypedef)
  - [CreatePredictorBacktestExportJobResponseTypeDef](#createpredictorbacktestexportjobresponsetypedef)
  - [CreatePredictorRequestRequestTypeDef](#createpredictorrequestrequesttypedef)
  - [CreatePredictorResponseTypeDef](#createpredictorresponsetypedef)
  - [DataConfigTypeDef](#dataconfigtypedef)
  - [DataDestinationTypeDef](#datadestinationtypedef)
  - [DataSourceTypeDef](#datasourcetypedef)
  - [DatasetGroupSummaryTypeDef](#datasetgroupsummarytypedef)
  - [DatasetImportJobSummaryTypeDef](#datasetimportjobsummarytypedef)
  - [DatasetSummaryTypeDef](#datasetsummarytypedef)
  - [DeleteDatasetGroupRequestRequestTypeDef](#deletedatasetgrouprequestrequesttypedef)
  - [DeleteDatasetImportJobRequestRequestTypeDef](#deletedatasetimportjobrequestrequesttypedef)
  - [DeleteDatasetRequestRequestTypeDef](#deletedatasetrequestrequesttypedef)
  - [DeleteExplainabilityExportRequestRequestTypeDef](#deleteexplainabilityexportrequestrequesttypedef)
  - [DeleteExplainabilityRequestRequestTypeDef](#deleteexplainabilityrequestrequesttypedef)
  - [DeleteForecastExportJobRequestRequestTypeDef](#deleteforecastexportjobrequestrequesttypedef)
  - [DeleteForecastRequestRequestTypeDef](#deleteforecastrequestrequesttypedef)
  - [DeletePredictorBacktestExportJobRequestRequestTypeDef](#deletepredictorbacktestexportjobrequestrequesttypedef)
  - [DeletePredictorRequestRequestTypeDef](#deletepredictorrequestrequesttypedef)
  - [DeleteResourceTreeRequestRequestTypeDef](#deleteresourcetreerequestrequesttypedef)
  - [DescribeAutoPredictorRequestRequestTypeDef](#describeautopredictorrequestrequesttypedef)
  - [DescribeAutoPredictorResponseTypeDef](#describeautopredictorresponsetypedef)
  - [DescribeDatasetGroupRequestRequestTypeDef](#describedatasetgrouprequestrequesttypedef)
  - [DescribeDatasetGroupResponseTypeDef](#describedatasetgroupresponsetypedef)
  - [DescribeDatasetImportJobRequestRequestTypeDef](#describedatasetimportjobrequestrequesttypedef)
  - [DescribeDatasetImportJobResponseTypeDef](#describedatasetimportjobresponsetypedef)
  - [DescribeDatasetRequestRequestTypeDef](#describedatasetrequestrequesttypedef)
  - [DescribeDatasetResponseTypeDef](#describedatasetresponsetypedef)
  - [DescribeExplainabilityExportRequestRequestTypeDef](#describeexplainabilityexportrequestrequesttypedef)
  - [DescribeExplainabilityExportResponseTypeDef](#describeexplainabilityexportresponsetypedef)
  - [DescribeExplainabilityRequestRequestTypeDef](#describeexplainabilityrequestrequesttypedef)
  - [DescribeExplainabilityResponseTypeDef](#describeexplainabilityresponsetypedef)
  - [DescribeForecastExportJobRequestRequestTypeDef](#describeforecastexportjobrequestrequesttypedef)
  - [DescribeForecastExportJobResponseTypeDef](#describeforecastexportjobresponsetypedef)
  - [DescribeForecastRequestRequestTypeDef](#describeforecastrequestrequesttypedef)
  - [DescribeForecastResponseTypeDef](#describeforecastresponsetypedef)
  - [DescribePredictorBacktestExportJobRequestRequestTypeDef](#describepredictorbacktestexportjobrequestrequesttypedef)
  - [DescribePredictorBacktestExportJobResponseTypeDef](#describepredictorbacktestexportjobresponsetypedef)
  - [DescribePredictorRequestRequestTypeDef](#describepredictorrequestrequesttypedef)
  - [DescribePredictorResponseTypeDef](#describepredictorresponsetypedef)
  - [EncryptionConfigTypeDef](#encryptionconfigtypedef)
  - [ErrorMetricTypeDef](#errormetrictypedef)
  - [EvaluationParametersTypeDef](#evaluationparameterstypedef)
  - [EvaluationResultTypeDef](#evaluationresulttypedef)
  - [ExplainabilityConfigTypeDef](#explainabilityconfigtypedef)
  - [ExplainabilityExportSummaryTypeDef](#explainabilityexportsummarytypedef)
  - [ExplainabilityInfoTypeDef](#explainabilityinfotypedef)
  - [ExplainabilitySummaryTypeDef](#explainabilitysummarytypedef)
  - [FeaturizationConfigTypeDef](#featurizationconfigtypedef)
  - [FeaturizationMethodTypeDef](#featurizationmethodtypedef)
  - [FeaturizationTypeDef](#featurizationtypedef)
  - [FilterTypeDef](#filtertypedef)
  - [ForecastExportJobSummaryTypeDef](#forecastexportjobsummarytypedef)
  - [ForecastSummaryTypeDef](#forecastsummarytypedef)
  - [GetAccuracyMetricsRequestRequestTypeDef](#getaccuracymetricsrequestrequesttypedef)
  - [GetAccuracyMetricsResponseTypeDef](#getaccuracymetricsresponsetypedef)
  - [HyperParameterTuningJobConfigTypeDef](#hyperparametertuningjobconfigtypedef)
  - [InputDataConfigTypeDef](#inputdataconfigtypedef)
  - [IntegerParameterRangeTypeDef](#integerparameterrangetypedef)
  - [ListDatasetGroupsRequestRequestTypeDef](#listdatasetgroupsrequestrequesttypedef)
  - [ListDatasetGroupsResponseTypeDef](#listdatasetgroupsresponsetypedef)
  - [ListDatasetImportJobsRequestRequestTypeDef](#listdatasetimportjobsrequestrequesttypedef)
  - [ListDatasetImportJobsResponseTypeDef](#listdatasetimportjobsresponsetypedef)
  - [ListDatasetsRequestRequestTypeDef](#listdatasetsrequestrequesttypedef)
  - [ListDatasetsResponseTypeDef](#listdatasetsresponsetypedef)
  - [ListExplainabilitiesRequestRequestTypeDef](#listexplainabilitiesrequestrequesttypedef)
  - [ListExplainabilitiesResponseTypeDef](#listexplainabilitiesresponsetypedef)
  - [ListExplainabilityExportsRequestRequestTypeDef](#listexplainabilityexportsrequestrequesttypedef)
  - [ListExplainabilityExportsResponseTypeDef](#listexplainabilityexportsresponsetypedef)
  - [ListForecastExportJobsRequestRequestTypeDef](#listforecastexportjobsrequestrequesttypedef)
  - [ListForecastExportJobsResponseTypeDef](#listforecastexportjobsresponsetypedef)
  - [ListForecastsRequestRequestTypeDef](#listforecastsrequestrequesttypedef)
  - [ListForecastsResponseTypeDef](#listforecastsresponsetypedef)
  - [ListPredictorBacktestExportJobsRequestRequestTypeDef](#listpredictorbacktestexportjobsrequestrequesttypedef)
  - [ListPredictorBacktestExportJobsResponseTypeDef](#listpredictorbacktestexportjobsresponsetypedef)
  - [ListPredictorsRequestRequestTypeDef](#listpredictorsrequestrequesttypedef)
  - [ListPredictorsResponseTypeDef](#listpredictorsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [MetricsTypeDef](#metricstypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ParameterRangesTypeDef](#parameterrangestypedef)
  - [PredictorBacktestExportJobSummaryTypeDef](#predictorbacktestexportjobsummarytypedef)
  - [PredictorExecutionDetailsTypeDef](#predictorexecutiondetailstypedef)
  - [PredictorExecutionTypeDef](#predictorexecutiontypedef)
  - [PredictorSummaryTypeDef](#predictorsummarytypedef)
  - [ReferencePredictorSummaryTypeDef](#referencepredictorsummarytypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3ConfigTypeDef](#s3configtypedef)
  - [SchemaAttributeTypeDef](#schemaattributetypedef)
  - [SchemaTypeDef](#schematypedef)
  - [StatisticsTypeDef](#statisticstypedef)
  - [StopResourceRequestRequestTypeDef](#stopresourcerequestrequesttypedef)
  - [SupplementaryFeatureTypeDef](#supplementaryfeaturetypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TestWindowSummaryTypeDef](#testwindowsummarytypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateDatasetGroupRequestRequestTypeDef](#updatedatasetgrouprequestrequesttypedef)
  - [WeightedQuantileLossTypeDef](#weightedquantilelosstypedef)
  - [WindowSummaryTypeDef](#windowsummarytypedef)

<a id="additionaldatasettypedef"></a>

## AdditionalDatasetTypeDef

```python
from types_aiobotocore_forecast.type_defs import AdditionalDatasetTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Configuration`: `Mapping`\[`str`, `Sequence`\[`str`\]\]

<a id="attributeconfigtypedef"></a>

## AttributeConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import AttributeConfigTypeDef
```

Required fields:

- `AttributeName`: `str`
- `Transformations`: `Mapping`\[`str`, `str`\]

<a id="categoricalparameterrangetypedef"></a>

## CategoricalParameterRangeTypeDef

```python
from types_aiobotocore_forecast.type_defs import CategoricalParameterRangeTypeDef
```

Required fields:

- `Name`: `str`
- `Values`: `Sequence`\[`str`\]

<a id="continuousparameterrangetypedef"></a>

## ContinuousParameterRangeTypeDef

```python
from types_aiobotocore_forecast.type_defs import ContinuousParameterRangeTypeDef
```

Required fields:

- `Name`: `str`
- `MaxValue`: `float`
- `MinValue`: `float`

Optional fields:

- `ScalingType`: [ScalingTypeType](./literals.md#scalingtypetype)

<a id="createautopredictorrequestrequesttypedef"></a>

## CreateAutoPredictorRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateAutoPredictorRequestRequestTypeDef
```

Required fields:

- `PredictorName`: `str`

Optional fields:

- `ForecastHorizon`: `int`
- `ForecastTypes`: `Sequence`\[`str`\]
- `ForecastDimensions`: `Sequence`\[`str`\]
- `ForecastFrequency`: `str`
- `DataConfig`: [DataConfigTypeDef](./type_defs.md#dataconfigtypedef)
- `EncryptionConfig`:
  [EncryptionConfigTypeDef](./type_defs.md#encryptionconfigtypedef)
- `ReferencePredictorArn`: `str`
- `OptimizationMetric`:
  [OptimizationMetricType](./literals.md#optimizationmetrictype)
- `ExplainPredictor`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createautopredictorresponsetypedef"></a>

## CreateAutoPredictorResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateAutoPredictorResponseTypeDef
```

Required fields:

- `PredictorArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdatasetgrouprequestrequesttypedef"></a>

## CreateDatasetGroupRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateDatasetGroupRequestRequestTypeDef
```

Required fields:

- `DatasetGroupName`: `str`
- `Domain`: [DomainType](./literals.md#domaintype)

Optional fields:

- `DatasetArns`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdatasetgroupresponsetypedef"></a>

## CreateDatasetGroupResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateDatasetGroupResponseTypeDef
```

Required fields:

- `DatasetGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdatasetimportjobrequestrequesttypedef"></a>

## CreateDatasetImportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateDatasetImportJobRequestRequestTypeDef
```

Required fields:

- `DatasetImportJobName`: `str`
- `DatasetArn`: `str`
- `DataSource`: [DataSourceTypeDef](./type_defs.md#datasourcetypedef)

Optional fields:

- `TimestampFormat`: `str`
- `TimeZone`: `str`
- `UseGeolocationForTimeZone`: `bool`
- `GeolocationFormat`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdatasetimportjobresponsetypedef"></a>

## CreateDatasetImportJobResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateDatasetImportJobResponseTypeDef
```

Required fields:

- `DatasetImportJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdatasetrequestrequesttypedef"></a>

## CreateDatasetRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateDatasetRequestRequestTypeDef
```

Required fields:

- `DatasetName`: `str`
- `Domain`: [DomainType](./literals.md#domaintype)
- `DatasetType`: [DatasetTypeType](./literals.md#datasettypetype)
- `Schema`: [SchemaTypeDef](./type_defs.md#schematypedef)

Optional fields:

- `DataFrequency`: `str`
- `EncryptionConfig`:
  [EncryptionConfigTypeDef](./type_defs.md#encryptionconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdatasetresponsetypedef"></a>

## CreateDatasetResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateDatasetResponseTypeDef
```

Required fields:

- `DatasetArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createexplainabilityexportrequestrequesttypedef"></a>

## CreateExplainabilityExportRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateExplainabilityExportRequestRequestTypeDef
```

Required fields:

- `ExplainabilityExportName`: `str`
- `ExplainabilityArn`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createexplainabilityexportresponsetypedef"></a>

## CreateExplainabilityExportResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateExplainabilityExportResponseTypeDef
```

Required fields:

- `ExplainabilityExportArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createexplainabilityrequestrequesttypedef"></a>

## CreateExplainabilityRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateExplainabilityRequestRequestTypeDef
```

Required fields:

- `ExplainabilityName`: `str`
- `ResourceArn`: `str`
- `ExplainabilityConfig`:
  [ExplainabilityConfigTypeDef](./type_defs.md#explainabilityconfigtypedef)

Optional fields:

- `DataSource`: [DataSourceTypeDef](./type_defs.md#datasourcetypedef)
- `Schema`: [SchemaTypeDef](./type_defs.md#schematypedef)
- `EnableVisualization`: `bool`
- `StartDateTime`: `str`
- `EndDateTime`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createexplainabilityresponsetypedef"></a>

## CreateExplainabilityResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateExplainabilityResponseTypeDef
```

Required fields:

- `ExplainabilityArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createforecastexportjobrequestrequesttypedef"></a>

## CreateForecastExportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateForecastExportJobRequestRequestTypeDef
```

Required fields:

- `ForecastExportJobName`: `str`
- `ForecastArn`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createforecastexportjobresponsetypedef"></a>

## CreateForecastExportJobResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateForecastExportJobResponseTypeDef
```

Required fields:

- `ForecastExportJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createforecastrequestrequesttypedef"></a>

## CreateForecastRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateForecastRequestRequestTypeDef
```

Required fields:

- `ForecastName`: `str`
- `PredictorArn`: `str`

Optional fields:

- `ForecastTypes`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createforecastresponsetypedef"></a>

## CreateForecastResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreateForecastResponseTypeDef
```

Required fields:

- `ForecastArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpredictorbacktestexportjobrequestrequesttypedef"></a>

## CreatePredictorBacktestExportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreatePredictorBacktestExportJobRequestRequestTypeDef
```

Required fields:

- `PredictorBacktestExportJobName`: `str`
- `PredictorArn`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createpredictorbacktestexportjobresponsetypedef"></a>

## CreatePredictorBacktestExportJobResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreatePredictorBacktestExportJobResponseTypeDef
```

Required fields:

- `PredictorBacktestExportJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpredictorrequestrequesttypedef"></a>

## CreatePredictorRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreatePredictorRequestRequestTypeDef
```

Required fields:

- `PredictorName`: `str`
- `ForecastHorizon`: `int`
- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef)
- `FeaturizationConfig`:
  [FeaturizationConfigTypeDef](./type_defs.md#featurizationconfigtypedef)

Optional fields:

- `AlgorithmArn`: `str`
- `ForecastTypes`: `Sequence`\[`str`\]
- `PerformAutoML`: `bool`
- `AutoMLOverrideStrategy`:
  [AutoMLOverrideStrategyType](./literals.md#automloverridestrategytype)
- `PerformHPO`: `bool`
- `TrainingParameters`: `Mapping`\[`str`, `str`\]
- `EvaluationParameters`:
  [EvaluationParametersTypeDef](./type_defs.md#evaluationparameterstypedef)
- `HPOConfig`:
  [HyperParameterTuningJobConfigTypeDef](./type_defs.md#hyperparametertuningjobconfigtypedef)
- `EncryptionConfig`:
  [EncryptionConfigTypeDef](./type_defs.md#encryptionconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `OptimizationMetric`:
  [OptimizationMetricType](./literals.md#optimizationmetrictype)

<a id="createpredictorresponsetypedef"></a>

## CreatePredictorResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import CreatePredictorResponseTypeDef
```

Required fields:

- `PredictorArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dataconfigtypedef"></a>

## DataConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import DataConfigTypeDef
```

Required fields:

- `DatasetGroupArn`: `str`

Optional fields:

- `AttributeConfigs`:
  `Sequence`\[[AttributeConfigTypeDef](./type_defs.md#attributeconfigtypedef)\]
- `AdditionalDatasets`:
  `Sequence`\[[AdditionalDatasetTypeDef](./type_defs.md#additionaldatasettypedef)\]

<a id="datadestinationtypedef"></a>

## DataDestinationTypeDef

```python
from types_aiobotocore_forecast.type_defs import DataDestinationTypeDef
```

Required fields:

- `S3Config`: [S3ConfigTypeDef](./type_defs.md#s3configtypedef)

<a id="datasourcetypedef"></a>

## DataSourceTypeDef

```python
from types_aiobotocore_forecast.type_defs import DataSourceTypeDef
```

Required fields:

- `S3Config`: [S3ConfigTypeDef](./type_defs.md#s3configtypedef)

<a id="datasetgroupsummarytypedef"></a>

## DatasetGroupSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import DatasetGroupSummaryTypeDef
```

Optional fields:

- `DatasetGroupArn`: `str`
- `DatasetGroupName`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="datasetimportjobsummarytypedef"></a>

## DatasetImportJobSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import DatasetImportJobSummaryTypeDef
```

Optional fields:

- `DatasetImportJobArn`: `str`
- `DatasetImportJobName`: `str`
- `DataSource`: [DataSourceTypeDef](./type_defs.md#datasourcetypedef)
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="datasetsummarytypedef"></a>

## DatasetSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import DatasetSummaryTypeDef
```

Optional fields:

- `DatasetArn`: `str`
- `DatasetName`: `str`
- `DatasetType`: [DatasetTypeType](./literals.md#datasettypetype)
- `Domain`: [DomainType](./literals.md#domaintype)
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="deletedatasetgrouprequestrequesttypedef"></a>

## DeleteDatasetGroupRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteDatasetGroupRequestRequestTypeDef
```

Required fields:

- `DatasetGroupArn`: `str`

<a id="deletedatasetimportjobrequestrequesttypedef"></a>

## DeleteDatasetImportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteDatasetImportJobRequestRequestTypeDef
```

Required fields:

- `DatasetImportJobArn`: `str`

<a id="deletedatasetrequestrequesttypedef"></a>

## DeleteDatasetRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteDatasetRequestRequestTypeDef
```

Required fields:

- `DatasetArn`: `str`

<a id="deleteexplainabilityexportrequestrequesttypedef"></a>

## DeleteExplainabilityExportRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteExplainabilityExportRequestRequestTypeDef
```

Required fields:

- `ExplainabilityExportArn`: `str`

<a id="deleteexplainabilityrequestrequesttypedef"></a>

## DeleteExplainabilityRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteExplainabilityRequestRequestTypeDef
```

Required fields:

- `ExplainabilityArn`: `str`

<a id="deleteforecastexportjobrequestrequesttypedef"></a>

## DeleteForecastExportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteForecastExportJobRequestRequestTypeDef
```

Required fields:

- `ForecastExportJobArn`: `str`

<a id="deleteforecastrequestrequesttypedef"></a>

## DeleteForecastRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteForecastRequestRequestTypeDef
```

Required fields:

- `ForecastArn`: `str`

<a id="deletepredictorbacktestexportjobrequestrequesttypedef"></a>

## DeletePredictorBacktestExportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeletePredictorBacktestExportJobRequestRequestTypeDef
```

Required fields:

- `PredictorBacktestExportJobArn`: `str`

<a id="deletepredictorrequestrequesttypedef"></a>

## DeletePredictorRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeletePredictorRequestRequestTypeDef
```

Required fields:

- `PredictorArn`: `str`

<a id="deleteresourcetreerequestrequesttypedef"></a>

## DeleteResourceTreeRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DeleteResourceTreeRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="describeautopredictorrequestrequesttypedef"></a>

## DescribeAutoPredictorRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeAutoPredictorRequestRequestTypeDef
```

Required fields:

- `PredictorArn`: `str`

<a id="describeautopredictorresponsetypedef"></a>

## DescribeAutoPredictorResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeAutoPredictorResponseTypeDef
```

Required fields:

- `PredictorArn`: `str`
- `PredictorName`: `str`
- `ForecastHorizon`: `int`
- `ForecastTypes`: `List`\[`str`\]
- `ForecastFrequency`: `str`
- `ForecastDimensions`: `List`\[`str`\]
- `DatasetImportJobArns`: `List`\[`str`\]
- `DataConfig`: [DataConfigTypeDef](./type_defs.md#dataconfigtypedef)
- `EncryptionConfig`:
  [EncryptionConfigTypeDef](./type_defs.md#encryptionconfigtypedef)
- `ReferencePredictorSummary`:
  [ReferencePredictorSummaryTypeDef](./type_defs.md#referencepredictorsummarytypedef)
- `EstimatedTimeRemainingInMinutes`: `int`
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `OptimizationMetric`:
  [OptimizationMetricType](./literals.md#optimizationmetrictype)
- `ExplainabilityInfo`:
  [ExplainabilityInfoTypeDef](./type_defs.md#explainabilityinfotypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedatasetgrouprequestrequesttypedef"></a>

## DescribeDatasetGroupRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeDatasetGroupRequestRequestTypeDef
```

Required fields:

- `DatasetGroupArn`: `str`

<a id="describedatasetgroupresponsetypedef"></a>

## DescribeDatasetGroupResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeDatasetGroupResponseTypeDef
```

Required fields:

- `DatasetGroupName`: `str`
- `DatasetGroupArn`: `str`
- `DatasetArns`: `List`\[`str`\]
- `Domain`: [DomainType](./literals.md#domaintype)
- `Status`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedatasetimportjobrequestrequesttypedef"></a>

## DescribeDatasetImportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeDatasetImportJobRequestRequestTypeDef
```

Required fields:

- `DatasetImportJobArn`: `str`

<a id="describedatasetimportjobresponsetypedef"></a>

## DescribeDatasetImportJobResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeDatasetImportJobResponseTypeDef
```

Required fields:

- `DatasetImportJobName`: `str`
- `DatasetImportJobArn`: `str`
- `DatasetArn`: `str`
- `TimestampFormat`: `str`
- `TimeZone`: `str`
- `UseGeolocationForTimeZone`: `bool`
- `GeolocationFormat`: `str`
- `DataSource`: [DataSourceTypeDef](./type_defs.md#datasourcetypedef)
- `EstimatedTimeRemainingInMinutes`: `int`
- `FieldStatistics`: `Dict`\[`str`,
  [StatisticsTypeDef](./type_defs.md#statisticstypedef)\]
- `DataSize`: `float`
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedatasetrequestrequesttypedef"></a>

## DescribeDatasetRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeDatasetRequestRequestTypeDef
```

Required fields:

- `DatasetArn`: `str`

<a id="describedatasetresponsetypedef"></a>

## DescribeDatasetResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeDatasetResponseTypeDef
```

Required fields:

- `DatasetArn`: `str`
- `DatasetName`: `str`
- `Domain`: [DomainType](./literals.md#domaintype)
- `DatasetType`: [DatasetTypeType](./literals.md#datasettypetype)
- `DataFrequency`: `str`
- `Schema`: [SchemaTypeDef](./type_defs.md#schematypedef)
- `EncryptionConfig`:
  [EncryptionConfigTypeDef](./type_defs.md#encryptionconfigtypedef)
- `Status`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeexplainabilityexportrequestrequesttypedef"></a>

## DescribeExplainabilityExportRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeExplainabilityExportRequestRequestTypeDef
```

Required fields:

- `ExplainabilityExportArn`: `str`

<a id="describeexplainabilityexportresponsetypedef"></a>

## DescribeExplainabilityExportResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeExplainabilityExportResponseTypeDef
```

Required fields:

- `ExplainabilityExportArn`: `str`
- `ExplainabilityExportName`: `str`
- `ExplainabilityArn`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)
- `Message`: `str`
- `Status`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeexplainabilityrequestrequesttypedef"></a>

## DescribeExplainabilityRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeExplainabilityRequestRequestTypeDef
```

Required fields:

- `ExplainabilityArn`: `str`

<a id="describeexplainabilityresponsetypedef"></a>

## DescribeExplainabilityResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeExplainabilityResponseTypeDef
```

Required fields:

- `ExplainabilityArn`: `str`
- `ExplainabilityName`: `str`
- `ResourceArn`: `str`
- `ExplainabilityConfig`:
  [ExplainabilityConfigTypeDef](./type_defs.md#explainabilityconfigtypedef)
- `EnableVisualization`: `bool`
- `DataSource`: [DataSourceTypeDef](./type_defs.md#datasourcetypedef)
- `Schema`: [SchemaTypeDef](./type_defs.md#schematypedef)
- `StartDateTime`: `str`
- `EndDateTime`: `str`
- `EstimatedTimeRemainingInMinutes`: `int`
- `Message`: `str`
- `Status`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeforecastexportjobrequestrequesttypedef"></a>

## DescribeForecastExportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeForecastExportJobRequestRequestTypeDef
```

Required fields:

- `ForecastExportJobArn`: `str`

<a id="describeforecastexportjobresponsetypedef"></a>

## DescribeForecastExportJobResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeForecastExportJobResponseTypeDef
```

Required fields:

- `ForecastExportJobArn`: `str`
- `ForecastExportJobName`: `str`
- `ForecastArn`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)
- `Message`: `str`
- `Status`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeforecastrequestrequesttypedef"></a>

## DescribeForecastRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeForecastRequestRequestTypeDef
```

Required fields:

- `ForecastArn`: `str`

<a id="describeforecastresponsetypedef"></a>

## DescribeForecastResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribeForecastResponseTypeDef
```

Required fields:

- `ForecastArn`: `str`
- `ForecastName`: `str`
- `ForecastTypes`: `List`\[`str`\]
- `PredictorArn`: `str`
- `DatasetGroupArn`: `str`
- `EstimatedTimeRemainingInMinutes`: `int`
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describepredictorbacktestexportjobrequestrequesttypedef"></a>

## DescribePredictorBacktestExportJobRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribePredictorBacktestExportJobRequestRequestTypeDef
```

Required fields:

- `PredictorBacktestExportJobArn`: `str`

<a id="describepredictorbacktestexportjobresponsetypedef"></a>

## DescribePredictorBacktestExportJobResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribePredictorBacktestExportJobResponseTypeDef
```

Required fields:

- `PredictorBacktestExportJobArn`: `str`
- `PredictorBacktestExportJobName`: `str`
- `PredictorArn`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)
- `Message`: `str`
- `Status`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describepredictorrequestrequesttypedef"></a>

## DescribePredictorRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribePredictorRequestRequestTypeDef
```

Required fields:

- `PredictorArn`: `str`

<a id="describepredictorresponsetypedef"></a>

## DescribePredictorResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import DescribePredictorResponseTypeDef
```

Required fields:

- `PredictorArn`: `str`
- `PredictorName`: `str`
- `AlgorithmArn`: `str`
- `AutoMLAlgorithmArns`: `List`\[`str`\]
- `ForecastHorizon`: `int`
- `ForecastTypes`: `List`\[`str`\]
- `PerformAutoML`: `bool`
- `AutoMLOverrideStrategy`:
  [AutoMLOverrideStrategyType](./literals.md#automloverridestrategytype)
- `PerformHPO`: `bool`
- `TrainingParameters`: `Dict`\[`str`, `str`\]
- `EvaluationParameters`:
  [EvaluationParametersTypeDef](./type_defs.md#evaluationparameterstypedef)
- `HPOConfig`:
  [HyperParameterTuningJobConfigTypeDef](./type_defs.md#hyperparametertuningjobconfigtypedef)
- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef)
- `FeaturizationConfig`:
  [FeaturizationConfigTypeDef](./type_defs.md#featurizationconfigtypedef)
- `EncryptionConfig`:
  [EncryptionConfigTypeDef](./type_defs.md#encryptionconfigtypedef)
- `PredictorExecutionDetails`:
  [PredictorExecutionDetailsTypeDef](./type_defs.md#predictorexecutiondetailstypedef)
- `EstimatedTimeRemainingInMinutes`: `int`
- `IsAutoPredictor`: `bool`
- `DatasetImportJobArns`: `List`\[`str`\]
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`
- `OptimizationMetric`:
  [OptimizationMetricType](./literals.md#optimizationmetrictype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="encryptionconfigtypedef"></a>

## EncryptionConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import EncryptionConfigTypeDef
```

Required fields:

- `RoleArn`: `str`
- `KMSKeyArn`: `str`

<a id="errormetrictypedef"></a>

## ErrorMetricTypeDef

```python
from types_aiobotocore_forecast.type_defs import ErrorMetricTypeDef
```

Optional fields:

- `ForecastType`: `str`
- `WAPE`: `float`
- `RMSE`: `float`
- `MASE`: `float`
- `MAPE`: `float`

<a id="evaluationparameterstypedef"></a>

## EvaluationParametersTypeDef

```python
from types_aiobotocore_forecast.type_defs import EvaluationParametersTypeDef
```

Optional fields:

- `NumberOfBacktestWindows`: `int`
- `BackTestWindowOffset`: `int`

<a id="evaluationresulttypedef"></a>

## EvaluationResultTypeDef

```python
from types_aiobotocore_forecast.type_defs import EvaluationResultTypeDef
```

Optional fields:

- `AlgorithmArn`: `str`
- `TestWindows`:
  `List`\[[WindowSummaryTypeDef](./type_defs.md#windowsummarytypedef)\]

<a id="explainabilityconfigtypedef"></a>

## ExplainabilityConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import ExplainabilityConfigTypeDef
```

Required fields:

- `TimeSeriesGranularity`:
  [TimeSeriesGranularityType](./literals.md#timeseriesgranularitytype)
- `TimePointGranularity`:
  [TimePointGranularityType](./literals.md#timepointgranularitytype)

<a id="explainabilityexportsummarytypedef"></a>

## ExplainabilityExportSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import ExplainabilityExportSummaryTypeDef
```

Optional fields:

- `ExplainabilityExportArn`: `str`
- `ExplainabilityExportName`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="explainabilityinfotypedef"></a>

## ExplainabilityInfoTypeDef

```python
from types_aiobotocore_forecast.type_defs import ExplainabilityInfoTypeDef
```

Optional fields:

- `ExplainabilityArn`: `str`
- `Status`: `str`

<a id="explainabilitysummarytypedef"></a>

## ExplainabilitySummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import ExplainabilitySummaryTypeDef
```

Optional fields:

- `ExplainabilityArn`: `str`
- `ExplainabilityName`: `str`
- `ResourceArn`: `str`
- `ExplainabilityConfig`:
  [ExplainabilityConfigTypeDef](./type_defs.md#explainabilityconfigtypedef)
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="featurizationconfigtypedef"></a>

## FeaturizationConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import FeaturizationConfigTypeDef
```

Required fields:

- `ForecastFrequency`: `str`

Optional fields:

- `ForecastDimensions`: `Sequence`\[`str`\]
- `Featurizations`:
  `Sequence`\[[FeaturizationTypeDef](./type_defs.md#featurizationtypedef)\]

<a id="featurizationmethodtypedef"></a>

## FeaturizationMethodTypeDef

```python
from types_aiobotocore_forecast.type_defs import FeaturizationMethodTypeDef
```

Required fields:

- `FeaturizationMethodName`: `Literal['filling']` (see
  [FeaturizationMethodNameType](./literals.md#featurizationmethodnametype))

Optional fields:

- `FeaturizationMethodParameters`: `Mapping`\[`str`, `str`\]

<a id="featurizationtypedef"></a>

## FeaturizationTypeDef

```python
from types_aiobotocore_forecast.type_defs import FeaturizationTypeDef
```

Required fields:

- `AttributeName`: `str`

Optional fields:

- `FeaturizationPipeline`:
  `Sequence`\[[FeaturizationMethodTypeDef](./type_defs.md#featurizationmethodtypedef)\]

<a id="filtertypedef"></a>

## FilterTypeDef

```python
from types_aiobotocore_forecast.type_defs import FilterTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`
- `Condition`:
  [FilterConditionStringType](./literals.md#filterconditionstringtype)

<a id="forecastexportjobsummarytypedef"></a>

## ForecastExportJobSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import ForecastExportJobSummaryTypeDef
```

Optional fields:

- `ForecastExportJobArn`: `str`
- `ForecastExportJobName`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="forecastsummarytypedef"></a>

## ForecastSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import ForecastSummaryTypeDef
```

Optional fields:

- `ForecastArn`: `str`
- `ForecastName`: `str`
- `PredictorArn`: `str`
- `CreatedUsingAutoPredictor`: `bool`
- `DatasetGroupArn`: `str`
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="getaccuracymetricsrequestrequesttypedef"></a>

## GetAccuracyMetricsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import GetAccuracyMetricsRequestRequestTypeDef
```

Required fields:

- `PredictorArn`: `str`

<a id="getaccuracymetricsresponsetypedef"></a>

## GetAccuracyMetricsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import GetAccuracyMetricsResponseTypeDef
```

Required fields:

- `PredictorEvaluationResults`:
  `List`\[[EvaluationResultTypeDef](./type_defs.md#evaluationresulttypedef)\]
- `IsAutoPredictor`: `bool`
- `AutoMLOverrideStrategy`:
  [AutoMLOverrideStrategyType](./literals.md#automloverridestrategytype)
- `OptimizationMetric`:
  [OptimizationMetricType](./literals.md#optimizationmetrictype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="hyperparametertuningjobconfigtypedef"></a>

## HyperParameterTuningJobConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import HyperParameterTuningJobConfigTypeDef
```

Optional fields:

- `ParameterRanges`:
  [ParameterRangesTypeDef](./type_defs.md#parameterrangestypedef)

<a id="inputdataconfigtypedef"></a>

## InputDataConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import InputDataConfigTypeDef
```

Required fields:

- `DatasetGroupArn`: `str`

Optional fields:

- `SupplementaryFeatures`:
  `Sequence`\[[SupplementaryFeatureTypeDef](./type_defs.md#supplementaryfeaturetypedef)\]

<a id="integerparameterrangetypedef"></a>

## IntegerParameterRangeTypeDef

```python
from types_aiobotocore_forecast.type_defs import IntegerParameterRangeTypeDef
```

Required fields:

- `Name`: `str`
- `MaxValue`: `int`
- `MinValue`: `int`

Optional fields:

- `ScalingType`: [ScalingTypeType](./literals.md#scalingtypetype)

<a id="listdatasetgroupsrequestrequesttypedef"></a>

## ListDatasetGroupsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListDatasetGroupsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listdatasetgroupsresponsetypedef"></a>

## ListDatasetGroupsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListDatasetGroupsResponseTypeDef
```

Required fields:

- `DatasetGroups`:
  `List`\[[DatasetGroupSummaryTypeDef](./type_defs.md#datasetgroupsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdatasetimportjobsrequestrequesttypedef"></a>

## ListDatasetImportJobsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListDatasetImportJobsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="listdatasetimportjobsresponsetypedef"></a>

## ListDatasetImportJobsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListDatasetImportJobsResponseTypeDef
```

Required fields:

- `DatasetImportJobs`:
  `List`\[[DatasetImportJobSummaryTypeDef](./type_defs.md#datasetimportjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdatasetsrequestrequesttypedef"></a>

## ListDatasetsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListDatasetsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listdatasetsresponsetypedef"></a>

## ListDatasetsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListDatasetsResponseTypeDef
```

Required fields:

- `Datasets`:
  `List`\[[DatasetSummaryTypeDef](./type_defs.md#datasetsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listexplainabilitiesrequestrequesttypedef"></a>

## ListExplainabilitiesRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListExplainabilitiesRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="listexplainabilitiesresponsetypedef"></a>

## ListExplainabilitiesResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListExplainabilitiesResponseTypeDef
```

Required fields:

- `Explainabilities`:
  `List`\[[ExplainabilitySummaryTypeDef](./type_defs.md#explainabilitysummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listexplainabilityexportsrequestrequesttypedef"></a>

## ListExplainabilityExportsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListExplainabilityExportsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="listexplainabilityexportsresponsetypedef"></a>

## ListExplainabilityExportsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListExplainabilityExportsResponseTypeDef
```

Required fields:

- `ExplainabilityExports`:
  `List`\[[ExplainabilityExportSummaryTypeDef](./type_defs.md#explainabilityexportsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listforecastexportjobsrequestrequesttypedef"></a>

## ListForecastExportJobsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListForecastExportJobsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="listforecastexportjobsresponsetypedef"></a>

## ListForecastExportJobsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListForecastExportJobsResponseTypeDef
```

Required fields:

- `ForecastExportJobs`:
  `List`\[[ForecastExportJobSummaryTypeDef](./type_defs.md#forecastexportjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listforecastsrequestrequesttypedef"></a>

## ListForecastsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListForecastsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="listforecastsresponsetypedef"></a>

## ListForecastsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListForecastsResponseTypeDef
```

Required fields:

- `Forecasts`:
  `List`\[[ForecastSummaryTypeDef](./type_defs.md#forecastsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpredictorbacktestexportjobsrequestrequesttypedef"></a>

## ListPredictorBacktestExportJobsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListPredictorBacktestExportJobsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="listpredictorbacktestexportjobsresponsetypedef"></a>

## ListPredictorBacktestExportJobsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListPredictorBacktestExportJobsResponseTypeDef
```

Required fields:

- `PredictorBacktestExportJobs`:
  `List`\[[PredictorBacktestExportJobSummaryTypeDef](./type_defs.md#predictorbacktestexportjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpredictorsrequestrequesttypedef"></a>

## ListPredictorsRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListPredictorsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="listpredictorsresponsetypedef"></a>

## ListPredictorsResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListPredictorsResponseTypeDef
```

Required fields:

- `Predictors`:
  `List`\[[PredictorSummaryTypeDef](./type_defs.md#predictorsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_forecast.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="metricstypedef"></a>

## MetricsTypeDef

```python
from types_aiobotocore_forecast.type_defs import MetricsTypeDef
```

Optional fields:

- `RMSE`: `float`
- `WeightedQuantileLosses`:
  `List`\[[WeightedQuantileLossTypeDef](./type_defs.md#weightedquantilelosstypedef)\]
- `ErrorMetrics`:
  `List`\[[ErrorMetricTypeDef](./type_defs.md#errormetrictypedef)\]
- `AverageWeightedQuantileLoss`: `float`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="parameterrangestypedef"></a>

## ParameterRangesTypeDef

```python
from types_aiobotocore_forecast.type_defs import ParameterRangesTypeDef
```

Optional fields:

- `CategoricalParameterRanges`:
  `Sequence`\[[CategoricalParameterRangeTypeDef](./type_defs.md#categoricalparameterrangetypedef)\]
- `ContinuousParameterRanges`:
  `Sequence`\[[ContinuousParameterRangeTypeDef](./type_defs.md#continuousparameterrangetypedef)\]
- `IntegerParameterRanges`:
  `Sequence`\[[IntegerParameterRangeTypeDef](./type_defs.md#integerparameterrangetypedef)\]

<a id="predictorbacktestexportjobsummarytypedef"></a>

## PredictorBacktestExportJobSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import PredictorBacktestExportJobSummaryTypeDef
```

Optional fields:

- `PredictorBacktestExportJobArn`: `str`
- `PredictorBacktestExportJobName`: `str`
- `Destination`:
  [DataDestinationTypeDef](./type_defs.md#datadestinationtypedef)
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="predictorexecutiondetailstypedef"></a>

## PredictorExecutionDetailsTypeDef

```python
from types_aiobotocore_forecast.type_defs import PredictorExecutionDetailsTypeDef
```

Optional fields:

- `PredictorExecutions`:
  `List`\[[PredictorExecutionTypeDef](./type_defs.md#predictorexecutiontypedef)\]

<a id="predictorexecutiontypedef"></a>

## PredictorExecutionTypeDef

```python
from types_aiobotocore_forecast.type_defs import PredictorExecutionTypeDef
```

Optional fields:

- `AlgorithmArn`: `str`
- `TestWindows`:
  `List`\[[TestWindowSummaryTypeDef](./type_defs.md#testwindowsummarytypedef)\]

<a id="predictorsummarytypedef"></a>

## PredictorSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import PredictorSummaryTypeDef
```

Optional fields:

- `PredictorArn`: `str`
- `PredictorName`: `str`
- `DatasetGroupArn`: `str`
- `IsAutoPredictor`: `bool`
- `ReferencePredictorSummary`:
  [ReferencePredictorSummaryTypeDef](./type_defs.md#referencepredictorsummarytypedef)
- `Status`: `str`
- `Message`: `str`
- `CreationTime`: `datetime`
- `LastModificationTime`: `datetime`

<a id="referencepredictorsummarytypedef"></a>

## ReferencePredictorSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import ReferencePredictorSummaryTypeDef
```

Optional fields:

- `Arn`: `str`
- `State`: [StateType](./literals.md#statetype)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_forecast.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3configtypedef"></a>

## S3ConfigTypeDef

```python
from types_aiobotocore_forecast.type_defs import S3ConfigTypeDef
```

Required fields:

- `Path`: `str`
- `RoleArn`: `str`

Optional fields:

- `KMSKeyArn`: `str`

<a id="schemaattributetypedef"></a>

## SchemaAttributeTypeDef

```python
from types_aiobotocore_forecast.type_defs import SchemaAttributeTypeDef
```

Optional fields:

- `AttributeName`: `str`
- `AttributeType`: [AttributeTypeType](./literals.md#attributetypetype)

<a id="schematypedef"></a>

## SchemaTypeDef

```python
from types_aiobotocore_forecast.type_defs import SchemaTypeDef
```

Optional fields:

- `Attributes`:
  `Sequence`\[[SchemaAttributeTypeDef](./type_defs.md#schemaattributetypedef)\]

<a id="statisticstypedef"></a>

## StatisticsTypeDef

```python
from types_aiobotocore_forecast.type_defs import StatisticsTypeDef
```

Optional fields:

- `Count`: `int`
- `CountDistinct`: `int`
- `CountNull`: `int`
- `CountNan`: `int`
- `Min`: `str`
- `Max`: `str`
- `Avg`: `float`
- `Stddev`: `float`
- `CountLong`: `int`
- `CountDistinctLong`: `int`
- `CountNullLong`: `int`
- `CountNanLong`: `int`

<a id="stopresourcerequestrequesttypedef"></a>

## StopResourceRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import StopResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="supplementaryfeaturetypedef"></a>

## SupplementaryFeatureTypeDef

```python
from types_aiobotocore_forecast.type_defs import SupplementaryFeatureTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_forecast.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="testwindowsummarytypedef"></a>

## TestWindowSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import TestWindowSummaryTypeDef
```

Optional fields:

- `TestWindowStart`: `datetime`
- `TestWindowEnd`: `datetime`
- `Status`: `str`
- `Message`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updatedatasetgrouprequestrequesttypedef"></a>

## UpdateDatasetGroupRequestRequestTypeDef

```python
from types_aiobotocore_forecast.type_defs import UpdateDatasetGroupRequestRequestTypeDef
```

Required fields:

- `DatasetGroupArn`: `str`
- `DatasetArns`: `Sequence`\[`str`\]

<a id="weightedquantilelosstypedef"></a>

## WeightedQuantileLossTypeDef

```python
from types_aiobotocore_forecast.type_defs import WeightedQuantileLossTypeDef
```

Optional fields:

- `Quantile`: `float`
- `LossValue`: `float`

<a id="windowsummarytypedef"></a>

## WindowSummaryTypeDef

```python
from types_aiobotocore_forecast.type_defs import WindowSummaryTypeDef
```

Optional fields:

- `TestWindowStart`: `datetime`
- `TestWindowEnd`: `datetime`
- `ItemCount`: `int`
- `EvaluationType`: [EvaluationTypeType](./literals.md#evaluationtypetype)
- `Metrics`: [MetricsTypeDef](./type_defs.md#metricstypedef)
