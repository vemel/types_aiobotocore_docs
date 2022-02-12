<a id="type-annotations-for-aiobotocore-codebuild-module"></a>

# Type annotations for aiobotocore CodeBuild module

> [Index](..) > CodeBuild

Auto-generated documentation for
[CodeBuild](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild)
type annotations stubs module
[types-aiobotocore-codebuild](https://pypi.org/project/types-aiobotocore-codebuild/).

- [Type annotations for aiobotocore CodeBuild module](#type-annotations-for-aiobotocore-codebuild-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [CodeBuildClient](#codebuildclient)
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

Click `Modify` and select `boto3 common` and `CodeBuild`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `CodeBuild` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[codebuild]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[codebuild]'

# standalone installation
python -m pip install types-aiobotocore-codebuild
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-codebuild
```

<a id="codebuildclient"></a>

## CodeBuildClient

Type annotations for `session.create_client("codebuild")` as
[CodeBuildClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_codebuild.client import CodeBuildClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [batch_delete_builds](./client.md#batch_delete_builds)
- [batch_get_build_batches](./client.md#batch_get_build_batches)
- [batch_get_builds](./client.md#batch_get_builds)
- [batch_get_projects](./client.md#batch_get_projects)
- [batch_get_report_groups](./client.md#batch_get_report_groups)
- [batch_get_reports](./client.md#batch_get_reports)
- [can_paginate](./client.md#can_paginate)
- [create_project](./client.md#create_project)
- [create_report_group](./client.md#create_report_group)
- [create_webhook](./client.md#create_webhook)
- [delete_build_batch](./client.md#delete_build_batch)
- [delete_project](./client.md#delete_project)
- [delete_report](./client.md#delete_report)
- [delete_report_group](./client.md#delete_report_group)
- [delete_resource_policy](./client.md#delete_resource_policy)
- [delete_source_credentials](./client.md#delete_source_credentials)
- [delete_webhook](./client.md#delete_webhook)
- [describe_code_coverages](./client.md#describe_code_coverages)
- [describe_test_cases](./client.md#describe_test_cases)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_report_group_trend](./client.md#get_report_group_trend)
- [get_resource_policy](./client.md#get_resource_policy)
- [import_source_credentials](./client.md#import_source_credentials)
- [invalidate_project_cache](./client.md#invalidate_project_cache)
- [list_build_batches](./client.md#list_build_batches)
- [list_build_batches_for_project](./client.md#list_build_batches_for_project)
- [list_builds](./client.md#list_builds)
- [list_builds_for_project](./client.md#list_builds_for_project)
- [list_curated_environment_images](./client.md#list_curated_environment_images)
- [list_projects](./client.md#list_projects)
- [list_report_groups](./client.md#list_report_groups)
- [list_reports](./client.md#list_reports)
- [list_reports_for_report_group](./client.md#list_reports_for_report_group)
- [list_shared_projects](./client.md#list_shared_projects)
- [list_shared_report_groups](./client.md#list_shared_report_groups)
- [list_source_credentials](./client.md#list_source_credentials)
- [put_resource_policy](./client.md#put_resource_policy)
- [retry_build](./client.md#retry_build)
- [retry_build_batch](./client.md#retry_build_batch)
- [start_build](./client.md#start_build)
- [start_build_batch](./client.md#start_build_batch)
- [stop_build](./client.md#stop_build)
- [stop_build_batch](./client.md#stop_build_batch)
- [update_project](./client.md#update_project)
- [update_project_visibility](./client.md#update_project_visibility)
- [update_report_group](./client.md#update_report_group)
- [update_webhook](./client.md#update_webhook)

<a id="exceptions"></a>

### Exceptions

CodeBuildClient [exceptions](./client.md#exceptions)

- AccountLimitExceededException
- ClientError
- InvalidInputException
- OAuthProviderException
- ResourceAlreadyExistsException
- ResourceNotFoundException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("codebuild").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_codebuild.paginator import DescribeCodeCoveragesPaginator, ...
```

- [DescribeCodeCoveragesPaginator](./paginators.md#describecodecoveragespaginator)
- [DescribeTestCasesPaginator](./paginators.md#describetestcasespaginator)
- [ListBuildBatchesPaginator](./paginators.md#listbuildbatchespaginator)
- [ListBuildBatchesForProjectPaginator](./paginators.md#listbuildbatchesforprojectpaginator)
- [ListBuildsPaginator](./paginators.md#listbuildspaginator)
- [ListBuildsForProjectPaginator](./paginators.md#listbuildsforprojectpaginator)
- [ListProjectsPaginator](./paginators.md#listprojectspaginator)
- [ListReportGroupsPaginator](./paginators.md#listreportgroupspaginator)
- [ListReportsPaginator](./paginators.md#listreportspaginator)
- [ListReportsForReportGroupPaginator](./paginators.md#listreportsforreportgrouppaginator)
- [ListSharedProjectsPaginator](./paginators.md#listsharedprojectspaginator)
- [ListSharedReportGroupsPaginator](./paginators.md#listsharedreportgroupspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_codebuild.literals import ArtifactNamespaceType, ...
```

- [ArtifactNamespaceType](./literals.md#artifactnamespacetype)
- [ArtifactPackagingType](./literals.md#artifactpackagingtype)
- [ArtifactsTypeType](./literals.md#artifactstypetype)
- [AuthTypeType](./literals.md#authtypetype)
- [BatchReportModeTypeType](./literals.md#batchreportmodetypetype)
- [BucketOwnerAccessType](./literals.md#bucketowneraccesstype)
- [BuildBatchPhaseTypeType](./literals.md#buildbatchphasetypetype)
- [BuildPhaseTypeType](./literals.md#buildphasetypetype)
- [CacheModeType](./literals.md#cachemodetype)
- [CacheTypeType](./literals.md#cachetypetype)
- [ComputeTypeType](./literals.md#computetypetype)
- [CredentialProviderTypeType](./literals.md#credentialprovidertypetype)
- [DescribeCodeCoveragesPaginatorName](./literals.md#describecodecoveragespaginatorname)
- [DescribeTestCasesPaginatorName](./literals.md#describetestcasespaginatorname)
- [EnvironmentTypeType](./literals.md#environmenttypetype)
- [EnvironmentVariableTypeType](./literals.md#environmentvariabletypetype)
- [FileSystemTypeType](./literals.md#filesystemtypetype)
- [ImagePullCredentialsTypeType](./literals.md#imagepullcredentialstypetype)
- [LanguageTypeType](./literals.md#languagetypetype)
- [ListBuildBatchesForProjectPaginatorName](./literals.md#listbuildbatchesforprojectpaginatorname)
- [ListBuildBatchesPaginatorName](./literals.md#listbuildbatchespaginatorname)
- [ListBuildsForProjectPaginatorName](./literals.md#listbuildsforprojectpaginatorname)
- [ListBuildsPaginatorName](./literals.md#listbuildspaginatorname)
- [ListProjectsPaginatorName](./literals.md#listprojectspaginatorname)
- [ListReportGroupsPaginatorName](./literals.md#listreportgroupspaginatorname)
- [ListReportsForReportGroupPaginatorName](./literals.md#listreportsforreportgrouppaginatorname)
- [ListReportsPaginatorName](./literals.md#listreportspaginatorname)
- [ListSharedProjectsPaginatorName](./literals.md#listsharedprojectspaginatorname)
- [ListSharedReportGroupsPaginatorName](./literals.md#listsharedreportgroupspaginatorname)
- [LogsConfigStatusTypeType](./literals.md#logsconfigstatustypetype)
- [PlatformTypeType](./literals.md#platformtypetype)
- [ProjectSortByTypeType](./literals.md#projectsortbytypetype)
- [ProjectVisibilityTypeType](./literals.md#projectvisibilitytypetype)
- [ReportCodeCoverageSortByTypeType](./literals.md#reportcodecoveragesortbytypetype)
- [ReportExportConfigTypeType](./literals.md#reportexportconfigtypetype)
- [ReportGroupSortByTypeType](./literals.md#reportgroupsortbytypetype)
- [ReportGroupStatusTypeType](./literals.md#reportgroupstatustypetype)
- [ReportGroupTrendFieldTypeType](./literals.md#reportgrouptrendfieldtypetype)
- [ReportPackagingTypeType](./literals.md#reportpackagingtypetype)
- [ReportStatusTypeType](./literals.md#reportstatustypetype)
- [ReportTypeType](./literals.md#reporttypetype)
- [RetryBuildBatchTypeType](./literals.md#retrybuildbatchtypetype)
- [ServerTypeType](./literals.md#servertypetype)
- [SharedResourceSortByTypeType](./literals.md#sharedresourcesortbytypetype)
- [SortOrderTypeType](./literals.md#sortordertypetype)
- [SourceAuthTypeType](./literals.md#sourceauthtypetype)
- [SourceTypeType](./literals.md#sourcetypetype)
- [StatusTypeType](./literals.md#statustypetype)
- [WebhookBuildTypeType](./literals.md#webhookbuildtypetype)
- [WebhookFilterTypeType](./literals.md#webhookfiltertypetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_codebuild.type_defs import BatchDeleteBuildsInputRequestTypeDef, ...
```

- [BatchDeleteBuildsInputRequestTypeDef](./type_defs.md#batchdeletebuildsinputrequesttypedef)
- [BatchDeleteBuildsOutputTypeDef](./type_defs.md#batchdeletebuildsoutputtypedef)
- [BatchGetBuildBatchesInputRequestTypeDef](./type_defs.md#batchgetbuildbatchesinputrequesttypedef)
- [BatchGetBuildBatchesOutputTypeDef](./type_defs.md#batchgetbuildbatchesoutputtypedef)
- [BatchGetBuildsInputRequestTypeDef](./type_defs.md#batchgetbuildsinputrequesttypedef)
- [BatchGetBuildsOutputTypeDef](./type_defs.md#batchgetbuildsoutputtypedef)
- [BatchGetProjectsInputRequestTypeDef](./type_defs.md#batchgetprojectsinputrequesttypedef)
- [BatchGetProjectsOutputTypeDef](./type_defs.md#batchgetprojectsoutputtypedef)
- [BatchGetReportGroupsInputRequestTypeDef](./type_defs.md#batchgetreportgroupsinputrequesttypedef)
- [BatchGetReportGroupsOutputTypeDef](./type_defs.md#batchgetreportgroupsoutputtypedef)
- [BatchGetReportsInputRequestTypeDef](./type_defs.md#batchgetreportsinputrequesttypedef)
- [BatchGetReportsOutputTypeDef](./type_defs.md#batchgetreportsoutputtypedef)
- [BatchRestrictionsTypeDef](./type_defs.md#batchrestrictionstypedef)
- [BuildArtifactsTypeDef](./type_defs.md#buildartifactstypedef)
- [BuildBatchFilterTypeDef](./type_defs.md#buildbatchfiltertypedef)
- [BuildBatchPhaseTypeDef](./type_defs.md#buildbatchphasetypedef)
- [BuildBatchTypeDef](./type_defs.md#buildbatchtypedef)
- [BuildGroupTypeDef](./type_defs.md#buildgrouptypedef)
- [BuildNotDeletedTypeDef](./type_defs.md#buildnotdeletedtypedef)
- [BuildPhaseTypeDef](./type_defs.md#buildphasetypedef)
- [BuildStatusConfigTypeDef](./type_defs.md#buildstatusconfigtypedef)
- [BuildSummaryTypeDef](./type_defs.md#buildsummarytypedef)
- [BuildTypeDef](./type_defs.md#buildtypedef)
- [CloudWatchLogsConfigTypeDef](./type_defs.md#cloudwatchlogsconfigtypedef)
- [CodeCoverageReportSummaryTypeDef](./type_defs.md#codecoveragereportsummarytypedef)
- [CodeCoverageTypeDef](./type_defs.md#codecoveragetypedef)
- [CreateProjectInputRequestTypeDef](./type_defs.md#createprojectinputrequesttypedef)
- [CreateProjectOutputTypeDef](./type_defs.md#createprojectoutputtypedef)
- [CreateReportGroupInputRequestTypeDef](./type_defs.md#createreportgroupinputrequesttypedef)
- [CreateReportGroupOutputTypeDef](./type_defs.md#createreportgroupoutputtypedef)
- [CreateWebhookInputRequestTypeDef](./type_defs.md#createwebhookinputrequesttypedef)
- [CreateWebhookOutputTypeDef](./type_defs.md#createwebhookoutputtypedef)
- [DebugSessionTypeDef](./type_defs.md#debugsessiontypedef)
- [DeleteBuildBatchInputRequestTypeDef](./type_defs.md#deletebuildbatchinputrequesttypedef)
- [DeleteBuildBatchOutputTypeDef](./type_defs.md#deletebuildbatchoutputtypedef)
- [DeleteProjectInputRequestTypeDef](./type_defs.md#deleteprojectinputrequesttypedef)
- [DeleteReportGroupInputRequestTypeDef](./type_defs.md#deletereportgroupinputrequesttypedef)
- [DeleteReportInputRequestTypeDef](./type_defs.md#deletereportinputrequesttypedef)
- [DeleteResourcePolicyInputRequestTypeDef](./type_defs.md#deleteresourcepolicyinputrequesttypedef)
- [DeleteSourceCredentialsInputRequestTypeDef](./type_defs.md#deletesourcecredentialsinputrequesttypedef)
- [DeleteSourceCredentialsOutputTypeDef](./type_defs.md#deletesourcecredentialsoutputtypedef)
- [DeleteWebhookInputRequestTypeDef](./type_defs.md#deletewebhookinputrequesttypedef)
- [DescribeCodeCoveragesInputRequestTypeDef](./type_defs.md#describecodecoveragesinputrequesttypedef)
- [DescribeCodeCoveragesOutputTypeDef](./type_defs.md#describecodecoveragesoutputtypedef)
- [DescribeTestCasesInputRequestTypeDef](./type_defs.md#describetestcasesinputrequesttypedef)
- [DescribeTestCasesOutputTypeDef](./type_defs.md#describetestcasesoutputtypedef)
- [EnvironmentImageTypeDef](./type_defs.md#environmentimagetypedef)
- [EnvironmentLanguageTypeDef](./type_defs.md#environmentlanguagetypedef)
- [EnvironmentPlatformTypeDef](./type_defs.md#environmentplatformtypedef)
- [EnvironmentVariableTypeDef](./type_defs.md#environmentvariabletypedef)
- [ExportedEnvironmentVariableTypeDef](./type_defs.md#exportedenvironmentvariabletypedef)
- [GetReportGroupTrendInputRequestTypeDef](./type_defs.md#getreportgrouptrendinputrequesttypedef)
- [GetReportGroupTrendOutputTypeDef](./type_defs.md#getreportgrouptrendoutputtypedef)
- [GetResourcePolicyInputRequestTypeDef](./type_defs.md#getresourcepolicyinputrequesttypedef)
- [GetResourcePolicyOutputTypeDef](./type_defs.md#getresourcepolicyoutputtypedef)
- [GitSubmodulesConfigTypeDef](./type_defs.md#gitsubmodulesconfigtypedef)
- [ImportSourceCredentialsInputRequestTypeDef](./type_defs.md#importsourcecredentialsinputrequesttypedef)
- [ImportSourceCredentialsOutputTypeDef](./type_defs.md#importsourcecredentialsoutputtypedef)
- [InvalidateProjectCacheInputRequestTypeDef](./type_defs.md#invalidateprojectcacheinputrequesttypedef)
- [ListBuildBatchesForProjectInputRequestTypeDef](./type_defs.md#listbuildbatchesforprojectinputrequesttypedef)
- [ListBuildBatchesForProjectOutputTypeDef](./type_defs.md#listbuildbatchesforprojectoutputtypedef)
- [ListBuildBatchesInputRequestTypeDef](./type_defs.md#listbuildbatchesinputrequesttypedef)
- [ListBuildBatchesOutputTypeDef](./type_defs.md#listbuildbatchesoutputtypedef)
- [ListBuildsForProjectInputRequestTypeDef](./type_defs.md#listbuildsforprojectinputrequesttypedef)
- [ListBuildsForProjectOutputTypeDef](./type_defs.md#listbuildsforprojectoutputtypedef)
- [ListBuildsInputRequestTypeDef](./type_defs.md#listbuildsinputrequesttypedef)
- [ListBuildsOutputTypeDef](./type_defs.md#listbuildsoutputtypedef)
- [ListCuratedEnvironmentImagesOutputTypeDef](./type_defs.md#listcuratedenvironmentimagesoutputtypedef)
- [ListProjectsInputRequestTypeDef](./type_defs.md#listprojectsinputrequesttypedef)
- [ListProjectsOutputTypeDef](./type_defs.md#listprojectsoutputtypedef)
- [ListReportGroupsInputRequestTypeDef](./type_defs.md#listreportgroupsinputrequesttypedef)
- [ListReportGroupsOutputTypeDef](./type_defs.md#listreportgroupsoutputtypedef)
- [ListReportsForReportGroupInputRequestTypeDef](./type_defs.md#listreportsforreportgroupinputrequesttypedef)
- [ListReportsForReportGroupOutputTypeDef](./type_defs.md#listreportsforreportgroupoutputtypedef)
- [ListReportsInputRequestTypeDef](./type_defs.md#listreportsinputrequesttypedef)
- [ListReportsOutputTypeDef](./type_defs.md#listreportsoutputtypedef)
- [ListSharedProjectsInputRequestTypeDef](./type_defs.md#listsharedprojectsinputrequesttypedef)
- [ListSharedProjectsOutputTypeDef](./type_defs.md#listsharedprojectsoutputtypedef)
- [ListSharedReportGroupsInputRequestTypeDef](./type_defs.md#listsharedreportgroupsinputrequesttypedef)
- [ListSharedReportGroupsOutputTypeDef](./type_defs.md#listsharedreportgroupsoutputtypedef)
- [ListSourceCredentialsOutputTypeDef](./type_defs.md#listsourcecredentialsoutputtypedef)
- [LogsConfigTypeDef](./type_defs.md#logsconfigtypedef)
- [LogsLocationTypeDef](./type_defs.md#logslocationtypedef)
- [NetworkInterfaceTypeDef](./type_defs.md#networkinterfacetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PhaseContextTypeDef](./type_defs.md#phasecontexttypedef)
- [ProjectArtifactsTypeDef](./type_defs.md#projectartifactstypedef)
- [ProjectBadgeTypeDef](./type_defs.md#projectbadgetypedef)
- [ProjectBuildBatchConfigTypeDef](./type_defs.md#projectbuildbatchconfigtypedef)
- [ProjectCacheTypeDef](./type_defs.md#projectcachetypedef)
- [ProjectEnvironmentTypeDef](./type_defs.md#projectenvironmenttypedef)
- [ProjectFileSystemLocationTypeDef](./type_defs.md#projectfilesystemlocationtypedef)
- [ProjectSourceTypeDef](./type_defs.md#projectsourcetypedef)
- [ProjectSourceVersionTypeDef](./type_defs.md#projectsourceversiontypedef)
- [ProjectTypeDef](./type_defs.md#projecttypedef)
- [PutResourcePolicyInputRequestTypeDef](./type_defs.md#putresourcepolicyinputrequesttypedef)
- [PutResourcePolicyOutputTypeDef](./type_defs.md#putresourcepolicyoutputtypedef)
- [RegistryCredentialTypeDef](./type_defs.md#registrycredentialtypedef)
- [ReportExportConfigTypeDef](./type_defs.md#reportexportconfigtypedef)
- [ReportFilterTypeDef](./type_defs.md#reportfiltertypedef)
- [ReportGroupTrendStatsTypeDef](./type_defs.md#reportgrouptrendstatstypedef)
- [ReportGroupTypeDef](./type_defs.md#reportgrouptypedef)
- [ReportTypeDef](./type_defs.md#reporttypedef)
- [ReportWithRawDataTypeDef](./type_defs.md#reportwithrawdatatypedef)
- [ResolvedArtifactTypeDef](./type_defs.md#resolvedartifacttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RetryBuildBatchInputRequestTypeDef](./type_defs.md#retrybuildbatchinputrequesttypedef)
- [RetryBuildBatchOutputTypeDef](./type_defs.md#retrybuildbatchoutputtypedef)
- [RetryBuildInputRequestTypeDef](./type_defs.md#retrybuildinputrequesttypedef)
- [RetryBuildOutputTypeDef](./type_defs.md#retrybuildoutputtypedef)
- [S3LogsConfigTypeDef](./type_defs.md#s3logsconfigtypedef)
- [S3ReportExportConfigTypeDef](./type_defs.md#s3reportexportconfigtypedef)
- [SourceAuthTypeDef](./type_defs.md#sourceauthtypedef)
- [SourceCredentialsInfoTypeDef](./type_defs.md#sourcecredentialsinfotypedef)
- [StartBuildBatchInputRequestTypeDef](./type_defs.md#startbuildbatchinputrequesttypedef)
- [StartBuildBatchOutputTypeDef](./type_defs.md#startbuildbatchoutputtypedef)
- [StartBuildInputRequestTypeDef](./type_defs.md#startbuildinputrequesttypedef)
- [StartBuildOutputTypeDef](./type_defs.md#startbuildoutputtypedef)
- [StopBuildBatchInputRequestTypeDef](./type_defs.md#stopbuildbatchinputrequesttypedef)
- [StopBuildBatchOutputTypeDef](./type_defs.md#stopbuildbatchoutputtypedef)
- [StopBuildInputRequestTypeDef](./type_defs.md#stopbuildinputrequesttypedef)
- [StopBuildOutputTypeDef](./type_defs.md#stopbuildoutputtypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TestCaseFilterTypeDef](./type_defs.md#testcasefiltertypedef)
- [TestCaseTypeDef](./type_defs.md#testcasetypedef)
- [TestReportSummaryTypeDef](./type_defs.md#testreportsummarytypedef)
- [UpdateProjectInputRequestTypeDef](./type_defs.md#updateprojectinputrequesttypedef)
- [UpdateProjectOutputTypeDef](./type_defs.md#updateprojectoutputtypedef)
- [UpdateProjectVisibilityInputRequestTypeDef](./type_defs.md#updateprojectvisibilityinputrequesttypedef)
- [UpdateProjectVisibilityOutputTypeDef](./type_defs.md#updateprojectvisibilityoutputtypedef)
- [UpdateReportGroupInputRequestTypeDef](./type_defs.md#updatereportgroupinputrequesttypedef)
- [UpdateReportGroupOutputTypeDef](./type_defs.md#updatereportgroupoutputtypedef)
- [UpdateWebhookInputRequestTypeDef](./type_defs.md#updatewebhookinputrequesttypedef)
- [UpdateWebhookOutputTypeDef](./type_defs.md#updatewebhookoutputtypedef)
- [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- [WebhookFilterTypeDef](./type_defs.md#webhookfiltertypedef)
- [WebhookTypeDef](./type_defs.md#webhooktypedef)
