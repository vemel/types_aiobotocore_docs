<a id="type-annotations-for-aiobotocore-personalize-module"></a>

# Type annotations for aiobotocore Personalize module

> [Index](..) > Personalize

Auto-generated documentation for
[Personalize](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize)
type annotations stubs module
[types-aiobotocore-personalize](https://pypi.org/project/types-aiobotocore-personalize/).

- [Type annotations for aiobotocore Personalize module](#type-annotations-for-aiobotocore-personalize-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [PersonalizeClient](#personalizeclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `Personalize`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `Personalize` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[personalize]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[personalize]'

# standalone installation
python -m pip install types-aiobotocore-personalize
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-personalize
```

<a id="personalizeclient"></a>

## PersonalizeClient

Type annotations for `session.create_client("personalize")` as
[PersonalizeClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_personalize.client import PersonalizeClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [create_batch_inference_job](./client.md#create_batch_inference_job)
- [create_batch_segment_job](./client.md#create_batch_segment_job)
- [create_campaign](./client.md#create_campaign)
- [create_dataset](./client.md#create_dataset)
- [create_dataset_export_job](./client.md#create_dataset_export_job)
- [create_dataset_group](./client.md#create_dataset_group)
- [create_dataset_import_job](./client.md#create_dataset_import_job)
- [create_event_tracker](./client.md#create_event_tracker)
- [create_filter](./client.md#create_filter)
- [create_recommender](./client.md#create_recommender)
- [create_schema](./client.md#create_schema)
- [create_solution](./client.md#create_solution)
- [create_solution_version](./client.md#create_solution_version)
- [delete_campaign](./client.md#delete_campaign)
- [delete_dataset](./client.md#delete_dataset)
- [delete_dataset_group](./client.md#delete_dataset_group)
- [delete_event_tracker](./client.md#delete_event_tracker)
- [delete_filter](./client.md#delete_filter)
- [delete_recommender](./client.md#delete_recommender)
- [delete_schema](./client.md#delete_schema)
- [delete_solution](./client.md#delete_solution)
- [describe_algorithm](./client.md#describe_algorithm)
- [describe_batch_inference_job](./client.md#describe_batch_inference_job)
- [describe_batch_segment_job](./client.md#describe_batch_segment_job)
- [describe_campaign](./client.md#describe_campaign)
- [describe_dataset](./client.md#describe_dataset)
- [describe_dataset_export_job](./client.md#describe_dataset_export_job)
- [describe_dataset_group](./client.md#describe_dataset_group)
- [describe_dataset_import_job](./client.md#describe_dataset_import_job)
- [describe_event_tracker](./client.md#describe_event_tracker)
- [describe_feature_transformation](./client.md#describe_feature_transformation)
- [describe_filter](./client.md#describe_filter)
- [describe_recipe](./client.md#describe_recipe)
- [describe_recommender](./client.md#describe_recommender)
- [describe_schema](./client.md#describe_schema)
- [describe_solution](./client.md#describe_solution)
- [describe_solution_version](./client.md#describe_solution_version)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_solution_metrics](./client.md#get_solution_metrics)
- [list_batch_inference_jobs](./client.md#list_batch_inference_jobs)
- [list_batch_segment_jobs](./client.md#list_batch_segment_jobs)
- [list_campaigns](./client.md#list_campaigns)
- [list_dataset_export_jobs](./client.md#list_dataset_export_jobs)
- [list_dataset_groups](./client.md#list_dataset_groups)
- [list_dataset_import_jobs](./client.md#list_dataset_import_jobs)
- [list_datasets](./client.md#list_datasets)
- [list_event_trackers](./client.md#list_event_trackers)
- [list_filters](./client.md#list_filters)
- [list_recipes](./client.md#list_recipes)
- [list_recommenders](./client.md#list_recommenders)
- [list_schemas](./client.md#list_schemas)
- [list_solution_versions](./client.md#list_solution_versions)
- [list_solutions](./client.md#list_solutions)
- [stop_solution_version_creation](./client.md#stop_solution_version_creation)
- [update_campaign](./client.md#update_campaign)
- [update_recommender](./client.md#update_recommender)

<a id="exceptions"></a>

### Exceptions

PersonalizeClient [exceptions](./client.md#exceptions)

- ClientError
- InvalidInputException
- InvalidNextTokenException
- LimitExceededException
- ResourceAlreadyExistsException
- ResourceInUseException
- ResourceNotFoundException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("personalize").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_personalize.paginator import ListBatchInferenceJobsPaginator, ...
```

- [ListBatchInferenceJobsPaginator](./paginators.md#listbatchinferencejobspaginator)
- [ListBatchSegmentJobsPaginator](./paginators.md#listbatchsegmentjobspaginator)
- [ListCampaignsPaginator](./paginators.md#listcampaignspaginator)
- [ListDatasetExportJobsPaginator](./paginators.md#listdatasetexportjobspaginator)
- [ListDatasetGroupsPaginator](./paginators.md#listdatasetgroupspaginator)
- [ListDatasetImportJobsPaginator](./paginators.md#listdatasetimportjobspaginator)
- [ListDatasetsPaginator](./paginators.md#listdatasetspaginator)
- [ListEventTrackersPaginator](./paginators.md#listeventtrackerspaginator)
- [ListFiltersPaginator](./paginators.md#listfilterspaginator)
- [ListRecipesPaginator](./paginators.md#listrecipespaginator)
- [ListRecommendersPaginator](./paginators.md#listrecommenderspaginator)
- [ListSchemasPaginator](./paginators.md#listschemaspaginator)
- [ListSolutionVersionsPaginator](./paginators.md#listsolutionversionspaginator)
- [ListSolutionsPaginator](./paginators.md#listsolutionspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_personalize.literals import DomainType, ...
```

- [DomainType](./literals.md#domaintype)
- [IngestionModeType](./literals.md#ingestionmodetype)
- [ListBatchInferenceJobsPaginatorName](./literals.md#listbatchinferencejobspaginatorname)
- [ListBatchSegmentJobsPaginatorName](./literals.md#listbatchsegmentjobspaginatorname)
- [ListCampaignsPaginatorName](./literals.md#listcampaignspaginatorname)
- [ListDatasetExportJobsPaginatorName](./literals.md#listdatasetexportjobspaginatorname)
- [ListDatasetGroupsPaginatorName](./literals.md#listdatasetgroupspaginatorname)
- [ListDatasetImportJobsPaginatorName](./literals.md#listdatasetimportjobspaginatorname)
- [ListDatasetsPaginatorName](./literals.md#listdatasetspaginatorname)
- [ListEventTrackersPaginatorName](./literals.md#listeventtrackerspaginatorname)
- [ListFiltersPaginatorName](./literals.md#listfilterspaginatorname)
- [ListRecipesPaginatorName](./literals.md#listrecipespaginatorname)
- [ListRecommendersPaginatorName](./literals.md#listrecommenderspaginatorname)
- [ListSchemasPaginatorName](./literals.md#listschemaspaginatorname)
- [ListSolutionVersionsPaginatorName](./literals.md#listsolutionversionspaginatorname)
- [ListSolutionsPaginatorName](./literals.md#listsolutionspaginatorname)
- [ObjectiveSensitivityType](./literals.md#objectivesensitivitytype)
- [RecipeProviderType](./literals.md#recipeprovidertype)
- [TrainingModeType](./literals.md#trainingmodetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_personalize.type_defs import AlgorithmImageTypeDef, ...
```

- [AlgorithmImageTypeDef](./type_defs.md#algorithmimagetypedef)
- [AlgorithmTypeDef](./type_defs.md#algorithmtypedef)
- [AutoMLConfigTypeDef](./type_defs.md#automlconfigtypedef)
- [AutoMLResultTypeDef](./type_defs.md#automlresulttypedef)
- [BatchInferenceJobConfigTypeDef](./type_defs.md#batchinferencejobconfigtypedef)
- [BatchInferenceJobInputTypeDef](./type_defs.md#batchinferencejobinputtypedef)
- [BatchInferenceJobOutputTypeDef](./type_defs.md#batchinferencejoboutputtypedef)
- [BatchInferenceJobSummaryTypeDef](./type_defs.md#batchinferencejobsummarytypedef)
- [BatchInferenceJobTypeDef](./type_defs.md#batchinferencejobtypedef)
- [BatchSegmentJobInputTypeDef](./type_defs.md#batchsegmentjobinputtypedef)
- [BatchSegmentJobOutputTypeDef](./type_defs.md#batchsegmentjoboutputtypedef)
- [BatchSegmentJobSummaryTypeDef](./type_defs.md#batchsegmentjobsummarytypedef)
- [BatchSegmentJobTypeDef](./type_defs.md#batchsegmentjobtypedef)
- [CampaignConfigTypeDef](./type_defs.md#campaignconfigtypedef)
- [CampaignSummaryTypeDef](./type_defs.md#campaignsummarytypedef)
- [CampaignTypeDef](./type_defs.md#campaigntypedef)
- [CampaignUpdateSummaryTypeDef](./type_defs.md#campaignupdatesummarytypedef)
- [CategoricalHyperParameterRangeTypeDef](./type_defs.md#categoricalhyperparameterrangetypedef)
- [ContinuousHyperParameterRangeTypeDef](./type_defs.md#continuoushyperparameterrangetypedef)
- [CreateBatchInferenceJobRequestRequestTypeDef](./type_defs.md#createbatchinferencejobrequestrequesttypedef)
- [CreateBatchInferenceJobResponseTypeDef](./type_defs.md#createbatchinferencejobresponsetypedef)
- [CreateBatchSegmentJobRequestRequestTypeDef](./type_defs.md#createbatchsegmentjobrequestrequesttypedef)
- [CreateBatchSegmentJobResponseTypeDef](./type_defs.md#createbatchsegmentjobresponsetypedef)
- [CreateCampaignRequestRequestTypeDef](./type_defs.md#createcampaignrequestrequesttypedef)
- [CreateCampaignResponseTypeDef](./type_defs.md#createcampaignresponsetypedef)
- [CreateDatasetExportJobRequestRequestTypeDef](./type_defs.md#createdatasetexportjobrequestrequesttypedef)
- [CreateDatasetExportJobResponseTypeDef](./type_defs.md#createdatasetexportjobresponsetypedef)
- [CreateDatasetGroupRequestRequestTypeDef](./type_defs.md#createdatasetgrouprequestrequesttypedef)
- [CreateDatasetGroupResponseTypeDef](./type_defs.md#createdatasetgroupresponsetypedef)
- [CreateDatasetImportJobRequestRequestTypeDef](./type_defs.md#createdatasetimportjobrequestrequesttypedef)
- [CreateDatasetImportJobResponseTypeDef](./type_defs.md#createdatasetimportjobresponsetypedef)
- [CreateDatasetRequestRequestTypeDef](./type_defs.md#createdatasetrequestrequesttypedef)
- [CreateDatasetResponseTypeDef](./type_defs.md#createdatasetresponsetypedef)
- [CreateEventTrackerRequestRequestTypeDef](./type_defs.md#createeventtrackerrequestrequesttypedef)
- [CreateEventTrackerResponseTypeDef](./type_defs.md#createeventtrackerresponsetypedef)
- [CreateFilterRequestRequestTypeDef](./type_defs.md#createfilterrequestrequesttypedef)
- [CreateFilterResponseTypeDef](./type_defs.md#createfilterresponsetypedef)
- [CreateRecommenderRequestRequestTypeDef](./type_defs.md#createrecommenderrequestrequesttypedef)
- [CreateRecommenderResponseTypeDef](./type_defs.md#createrecommenderresponsetypedef)
- [CreateSchemaRequestRequestTypeDef](./type_defs.md#createschemarequestrequesttypedef)
- [CreateSchemaResponseTypeDef](./type_defs.md#createschemaresponsetypedef)
- [CreateSolutionRequestRequestTypeDef](./type_defs.md#createsolutionrequestrequesttypedef)
- [CreateSolutionResponseTypeDef](./type_defs.md#createsolutionresponsetypedef)
- [CreateSolutionVersionRequestRequestTypeDef](./type_defs.md#createsolutionversionrequestrequesttypedef)
- [CreateSolutionVersionResponseTypeDef](./type_defs.md#createsolutionversionresponsetypedef)
- [DataSourceTypeDef](./type_defs.md#datasourcetypedef)
- [DatasetExportJobOutputTypeDef](./type_defs.md#datasetexportjoboutputtypedef)
- [DatasetExportJobSummaryTypeDef](./type_defs.md#datasetexportjobsummarytypedef)
- [DatasetExportJobTypeDef](./type_defs.md#datasetexportjobtypedef)
- [DatasetGroupSummaryTypeDef](./type_defs.md#datasetgroupsummarytypedef)
- [DatasetGroupTypeDef](./type_defs.md#datasetgrouptypedef)
- [DatasetImportJobSummaryTypeDef](./type_defs.md#datasetimportjobsummarytypedef)
- [DatasetImportJobTypeDef](./type_defs.md#datasetimportjobtypedef)
- [DatasetSchemaSummaryTypeDef](./type_defs.md#datasetschemasummarytypedef)
- [DatasetSchemaTypeDef](./type_defs.md#datasetschematypedef)
- [DatasetSummaryTypeDef](./type_defs.md#datasetsummarytypedef)
- [DatasetTypeDef](./type_defs.md#datasettypedef)
- [DefaultCategoricalHyperParameterRangeTypeDef](./type_defs.md#defaultcategoricalhyperparameterrangetypedef)
- [DefaultContinuousHyperParameterRangeTypeDef](./type_defs.md#defaultcontinuoushyperparameterrangetypedef)
- [DefaultHyperParameterRangesTypeDef](./type_defs.md#defaulthyperparameterrangestypedef)
- [DefaultIntegerHyperParameterRangeTypeDef](./type_defs.md#defaultintegerhyperparameterrangetypedef)
- [DeleteCampaignRequestRequestTypeDef](./type_defs.md#deletecampaignrequestrequesttypedef)
- [DeleteDatasetGroupRequestRequestTypeDef](./type_defs.md#deletedatasetgrouprequestrequesttypedef)
- [DeleteDatasetRequestRequestTypeDef](./type_defs.md#deletedatasetrequestrequesttypedef)
- [DeleteEventTrackerRequestRequestTypeDef](./type_defs.md#deleteeventtrackerrequestrequesttypedef)
- [DeleteFilterRequestRequestTypeDef](./type_defs.md#deletefilterrequestrequesttypedef)
- [DeleteRecommenderRequestRequestTypeDef](./type_defs.md#deleterecommenderrequestrequesttypedef)
- [DeleteSchemaRequestRequestTypeDef](./type_defs.md#deleteschemarequestrequesttypedef)
- [DeleteSolutionRequestRequestTypeDef](./type_defs.md#deletesolutionrequestrequesttypedef)
- [DescribeAlgorithmRequestRequestTypeDef](./type_defs.md#describealgorithmrequestrequesttypedef)
- [DescribeAlgorithmResponseTypeDef](./type_defs.md#describealgorithmresponsetypedef)
- [DescribeBatchInferenceJobRequestRequestTypeDef](./type_defs.md#describebatchinferencejobrequestrequesttypedef)
- [DescribeBatchInferenceJobResponseTypeDef](./type_defs.md#describebatchinferencejobresponsetypedef)
- [DescribeBatchSegmentJobRequestRequestTypeDef](./type_defs.md#describebatchsegmentjobrequestrequesttypedef)
- [DescribeBatchSegmentJobResponseTypeDef](./type_defs.md#describebatchsegmentjobresponsetypedef)
- [DescribeCampaignRequestRequestTypeDef](./type_defs.md#describecampaignrequestrequesttypedef)
- [DescribeCampaignResponseTypeDef](./type_defs.md#describecampaignresponsetypedef)
- [DescribeDatasetExportJobRequestRequestTypeDef](./type_defs.md#describedatasetexportjobrequestrequesttypedef)
- [DescribeDatasetExportJobResponseTypeDef](./type_defs.md#describedatasetexportjobresponsetypedef)
- [DescribeDatasetGroupRequestRequestTypeDef](./type_defs.md#describedatasetgrouprequestrequesttypedef)
- [DescribeDatasetGroupResponseTypeDef](./type_defs.md#describedatasetgroupresponsetypedef)
- [DescribeDatasetImportJobRequestRequestTypeDef](./type_defs.md#describedatasetimportjobrequestrequesttypedef)
- [DescribeDatasetImportJobResponseTypeDef](./type_defs.md#describedatasetimportjobresponsetypedef)
- [DescribeDatasetRequestRequestTypeDef](./type_defs.md#describedatasetrequestrequesttypedef)
- [DescribeDatasetResponseTypeDef](./type_defs.md#describedatasetresponsetypedef)
- [DescribeEventTrackerRequestRequestTypeDef](./type_defs.md#describeeventtrackerrequestrequesttypedef)
- [DescribeEventTrackerResponseTypeDef](./type_defs.md#describeeventtrackerresponsetypedef)
- [DescribeFeatureTransformationRequestRequestTypeDef](./type_defs.md#describefeaturetransformationrequestrequesttypedef)
- [DescribeFeatureTransformationResponseTypeDef](./type_defs.md#describefeaturetransformationresponsetypedef)
- [DescribeFilterRequestRequestTypeDef](./type_defs.md#describefilterrequestrequesttypedef)
- [DescribeFilterResponseTypeDef](./type_defs.md#describefilterresponsetypedef)
- [DescribeRecipeRequestRequestTypeDef](./type_defs.md#describereciperequestrequesttypedef)
- [DescribeRecipeResponseTypeDef](./type_defs.md#describereciperesponsetypedef)
- [DescribeRecommenderRequestRequestTypeDef](./type_defs.md#describerecommenderrequestrequesttypedef)
- [DescribeRecommenderResponseTypeDef](./type_defs.md#describerecommenderresponsetypedef)
- [DescribeSchemaRequestRequestTypeDef](./type_defs.md#describeschemarequestrequesttypedef)
- [DescribeSchemaResponseTypeDef](./type_defs.md#describeschemaresponsetypedef)
- [DescribeSolutionRequestRequestTypeDef](./type_defs.md#describesolutionrequestrequesttypedef)
- [DescribeSolutionResponseTypeDef](./type_defs.md#describesolutionresponsetypedef)
- [DescribeSolutionVersionRequestRequestTypeDef](./type_defs.md#describesolutionversionrequestrequesttypedef)
- [DescribeSolutionVersionResponseTypeDef](./type_defs.md#describesolutionversionresponsetypedef)
- [EventTrackerSummaryTypeDef](./type_defs.md#eventtrackersummarytypedef)
- [EventTrackerTypeDef](./type_defs.md#eventtrackertypedef)
- [FeatureTransformationTypeDef](./type_defs.md#featuretransformationtypedef)
- [FilterSummaryTypeDef](./type_defs.md#filtersummarytypedef)
- [FilterTypeDef](./type_defs.md#filtertypedef)
- [GetSolutionMetricsRequestRequestTypeDef](./type_defs.md#getsolutionmetricsrequestrequesttypedef)
- [GetSolutionMetricsResponseTypeDef](./type_defs.md#getsolutionmetricsresponsetypedef)
- [HPOConfigTypeDef](./type_defs.md#hpoconfigtypedef)
- [HPOObjectiveTypeDef](./type_defs.md#hpoobjectivetypedef)
- [HPOResourceConfigTypeDef](./type_defs.md#hporesourceconfigtypedef)
- [HyperParameterRangesTypeDef](./type_defs.md#hyperparameterrangestypedef)
- [IntegerHyperParameterRangeTypeDef](./type_defs.md#integerhyperparameterrangetypedef)
- [ListBatchInferenceJobsRequestRequestTypeDef](./type_defs.md#listbatchinferencejobsrequestrequesttypedef)
- [ListBatchInferenceJobsResponseTypeDef](./type_defs.md#listbatchinferencejobsresponsetypedef)
- [ListBatchSegmentJobsRequestRequestTypeDef](./type_defs.md#listbatchsegmentjobsrequestrequesttypedef)
- [ListBatchSegmentJobsResponseTypeDef](./type_defs.md#listbatchsegmentjobsresponsetypedef)
- [ListCampaignsRequestRequestTypeDef](./type_defs.md#listcampaignsrequestrequesttypedef)
- [ListCampaignsResponseTypeDef](./type_defs.md#listcampaignsresponsetypedef)
- [ListDatasetExportJobsRequestRequestTypeDef](./type_defs.md#listdatasetexportjobsrequestrequesttypedef)
- [ListDatasetExportJobsResponseTypeDef](./type_defs.md#listdatasetexportjobsresponsetypedef)
- [ListDatasetGroupsRequestRequestTypeDef](./type_defs.md#listdatasetgroupsrequestrequesttypedef)
- [ListDatasetGroupsResponseTypeDef](./type_defs.md#listdatasetgroupsresponsetypedef)
- [ListDatasetImportJobsRequestRequestTypeDef](./type_defs.md#listdatasetimportjobsrequestrequesttypedef)
- [ListDatasetImportJobsResponseTypeDef](./type_defs.md#listdatasetimportjobsresponsetypedef)
- [ListDatasetsRequestRequestTypeDef](./type_defs.md#listdatasetsrequestrequesttypedef)
- [ListDatasetsResponseTypeDef](./type_defs.md#listdatasetsresponsetypedef)
- [ListEventTrackersRequestRequestTypeDef](./type_defs.md#listeventtrackersrequestrequesttypedef)
- [ListEventTrackersResponseTypeDef](./type_defs.md#listeventtrackersresponsetypedef)
- [ListFiltersRequestRequestTypeDef](./type_defs.md#listfiltersrequestrequesttypedef)
- [ListFiltersResponseTypeDef](./type_defs.md#listfiltersresponsetypedef)
- [ListRecipesRequestRequestTypeDef](./type_defs.md#listrecipesrequestrequesttypedef)
- [ListRecipesResponseTypeDef](./type_defs.md#listrecipesresponsetypedef)
- [ListRecommendersRequestRequestTypeDef](./type_defs.md#listrecommendersrequestrequesttypedef)
- [ListRecommendersResponseTypeDef](./type_defs.md#listrecommendersresponsetypedef)
- [ListSchemasRequestRequestTypeDef](./type_defs.md#listschemasrequestrequesttypedef)
- [ListSchemasResponseTypeDef](./type_defs.md#listschemasresponsetypedef)
- [ListSolutionVersionsRequestRequestTypeDef](./type_defs.md#listsolutionversionsrequestrequesttypedef)
- [ListSolutionVersionsResponseTypeDef](./type_defs.md#listsolutionversionsresponsetypedef)
- [ListSolutionsRequestRequestTypeDef](./type_defs.md#listsolutionsrequestrequesttypedef)
- [ListSolutionsResponseTypeDef](./type_defs.md#listsolutionsresponsetypedef)
- [OptimizationObjectiveTypeDef](./type_defs.md#optimizationobjectivetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [RecipeSummaryTypeDef](./type_defs.md#recipesummarytypedef)
- [RecipeTypeDef](./type_defs.md#recipetypedef)
- [RecommenderConfigTypeDef](./type_defs.md#recommenderconfigtypedef)
- [RecommenderSummaryTypeDef](./type_defs.md#recommendersummarytypedef)
- [RecommenderTypeDef](./type_defs.md#recommendertypedef)
- [RecommenderUpdateSummaryTypeDef](./type_defs.md#recommenderupdatesummarytypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [S3DataConfigTypeDef](./type_defs.md#s3dataconfigtypedef)
- [SolutionConfigTypeDef](./type_defs.md#solutionconfigtypedef)
- [SolutionSummaryTypeDef](./type_defs.md#solutionsummarytypedef)
- [SolutionTypeDef](./type_defs.md#solutiontypedef)
- [SolutionVersionSummaryTypeDef](./type_defs.md#solutionversionsummarytypedef)
- [SolutionVersionTypeDef](./type_defs.md#solutionversiontypedef)
- [StopSolutionVersionCreationRequestRequestTypeDef](./type_defs.md#stopsolutionversioncreationrequestrequesttypedef)
- [TunedHPOParamsTypeDef](./type_defs.md#tunedhpoparamstypedef)
- [UpdateCampaignRequestRequestTypeDef](./type_defs.md#updatecampaignrequestrequesttypedef)
- [UpdateCampaignResponseTypeDef](./type_defs.md#updatecampaignresponsetypedef)
- [UpdateRecommenderRequestRequestTypeDef](./type_defs.md#updaterecommenderrequestrequesttypedef)
- [UpdateRecommenderResponseTypeDef](./type_defs.md#updaterecommenderresponsetypedef)
