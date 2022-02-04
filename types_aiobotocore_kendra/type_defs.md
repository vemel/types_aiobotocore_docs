<a id="typed-dictionaries-for-aiobotocore-kendra-module"></a>

# Typed dictionaries for aiobotocore kendra module

> [Index](..) > [kendra](.) > Typed dictionaries

Auto-generated documentation for
[kendra](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra)
type annotations stubs module
[types-aiobotocore-kendra](https://pypi.org/project/types-aiobotocore-kendra/).

- [Typed dictionaries for aiobotocore kendra module](#typed-dictionaries-for-aiobotocore-kendra-module)
  - [AccessControlListConfigurationTypeDef](#accesscontrollistconfigurationtypedef)
  - [AclConfigurationTypeDef](#aclconfigurationtypedef)
  - [AdditionalResultAttributeTypeDef](#additionalresultattributetypedef)
  - [AdditionalResultAttributeValueTypeDef](#additionalresultattributevaluetypedef)
  - [AssociateEntitiesToExperienceRequestRequestTypeDef](#associateentitiestoexperiencerequestrequesttypedef)
  - [AssociateEntitiesToExperienceResponseTypeDef](#associateentitiestoexperienceresponsetypedef)
  - [AssociatePersonasToEntitiesRequestRequestTypeDef](#associatepersonastoentitiesrequestrequesttypedef)
  - [AssociatePersonasToEntitiesResponseTypeDef](#associatepersonastoentitiesresponsetypedef)
  - [AttributeFilterTypeDef](#attributefiltertypedef)
  - [AuthenticationConfigurationTypeDef](#authenticationconfigurationtypedef)
  - [BasicAuthenticationConfigurationTypeDef](#basicauthenticationconfigurationtypedef)
  - [BatchDeleteDocumentRequestRequestTypeDef](#batchdeletedocumentrequestrequesttypedef)
  - [BatchDeleteDocumentResponseFailedDocumentTypeDef](#batchdeletedocumentresponsefaileddocumenttypedef)
  - [BatchDeleteDocumentResponseTypeDef](#batchdeletedocumentresponsetypedef)
  - [BatchGetDocumentStatusRequestRequestTypeDef](#batchgetdocumentstatusrequestrequesttypedef)
  - [BatchGetDocumentStatusResponseErrorTypeDef](#batchgetdocumentstatusresponseerrortypedef)
  - [BatchGetDocumentStatusResponseTypeDef](#batchgetdocumentstatusresponsetypedef)
  - [BatchPutDocumentRequestRequestTypeDef](#batchputdocumentrequestrequesttypedef)
  - [BatchPutDocumentResponseFailedDocumentTypeDef](#batchputdocumentresponsefaileddocumenttypedef)
  - [BatchPutDocumentResponseTypeDef](#batchputdocumentresponsetypedef)
  - [CapacityUnitsConfigurationTypeDef](#capacityunitsconfigurationtypedef)
  - [ClearQuerySuggestionsRequestRequestTypeDef](#clearquerysuggestionsrequestrequesttypedef)
  - [ClickFeedbackTypeDef](#clickfeedbacktypedef)
  - [ColumnConfigurationTypeDef](#columnconfigurationtypedef)
  - [ConfluenceAttachmentConfigurationTypeDef](#confluenceattachmentconfigurationtypedef)
  - [ConfluenceAttachmentToIndexFieldMappingTypeDef](#confluenceattachmenttoindexfieldmappingtypedef)
  - [ConfluenceBlogConfigurationTypeDef](#confluenceblogconfigurationtypedef)
  - [ConfluenceBlogToIndexFieldMappingTypeDef](#confluenceblogtoindexfieldmappingtypedef)
  - [ConfluenceConfigurationTypeDef](#confluenceconfigurationtypedef)
  - [ConfluencePageConfigurationTypeDef](#confluencepageconfigurationtypedef)
  - [ConfluencePageToIndexFieldMappingTypeDef](#confluencepagetoindexfieldmappingtypedef)
  - [ConfluenceSpaceConfigurationTypeDef](#confluencespaceconfigurationtypedef)
  - [ConfluenceSpaceToIndexFieldMappingTypeDef](#confluencespacetoindexfieldmappingtypedef)
  - [ConnectionConfigurationTypeDef](#connectionconfigurationtypedef)
  - [ContentSourceConfigurationTypeDef](#contentsourceconfigurationtypedef)
  - [CreateDataSourceRequestRequestTypeDef](#createdatasourcerequestrequesttypedef)
  - [CreateDataSourceResponseTypeDef](#createdatasourceresponsetypedef)
  - [CreateExperienceRequestRequestTypeDef](#createexperiencerequestrequesttypedef)
  - [CreateExperienceResponseTypeDef](#createexperienceresponsetypedef)
  - [CreateFaqRequestRequestTypeDef](#createfaqrequestrequesttypedef)
  - [CreateFaqResponseTypeDef](#createfaqresponsetypedef)
  - [CreateIndexRequestRequestTypeDef](#createindexrequestrequesttypedef)
  - [CreateIndexResponseTypeDef](#createindexresponsetypedef)
  - [CreateQuerySuggestionsBlockListRequestRequestTypeDef](#createquerysuggestionsblocklistrequestrequesttypedef)
  - [CreateQuerySuggestionsBlockListResponseTypeDef](#createquerysuggestionsblocklistresponsetypedef)
  - [CreateThesaurusRequestRequestTypeDef](#createthesaurusrequestrequesttypedef)
  - [CreateThesaurusResponseTypeDef](#createthesaurusresponsetypedef)
  - [CustomDocumentEnrichmentConfigurationTypeDef](#customdocumentenrichmentconfigurationtypedef)
  - [DataSourceConfigurationTypeDef](#datasourceconfigurationtypedef)
  - [DataSourceGroupTypeDef](#datasourcegrouptypedef)
  - [DataSourceSummaryTypeDef](#datasourcesummarytypedef)
  - [DataSourceSyncJobMetricTargetTypeDef](#datasourcesyncjobmetrictargettypedef)
  - [DataSourceSyncJobMetricsTypeDef](#datasourcesyncjobmetricstypedef)
  - [DataSourceSyncJobTypeDef](#datasourcesyncjobtypedef)
  - [DataSourceToIndexFieldMappingTypeDef](#datasourcetoindexfieldmappingtypedef)
  - [DataSourceVpcConfigurationTypeDef](#datasourcevpcconfigurationtypedef)
  - [DatabaseConfigurationTypeDef](#databaseconfigurationtypedef)
  - [DeleteDataSourceRequestRequestTypeDef](#deletedatasourcerequestrequesttypedef)
  - [DeleteExperienceRequestRequestTypeDef](#deleteexperiencerequestrequesttypedef)
  - [DeleteFaqRequestRequestTypeDef](#deletefaqrequestrequesttypedef)
  - [DeleteIndexRequestRequestTypeDef](#deleteindexrequestrequesttypedef)
  - [DeletePrincipalMappingRequestRequestTypeDef](#deleteprincipalmappingrequestrequesttypedef)
  - [DeleteQuerySuggestionsBlockListRequestRequestTypeDef](#deletequerysuggestionsblocklistrequestrequesttypedef)
  - [DeleteThesaurusRequestRequestTypeDef](#deletethesaurusrequestrequesttypedef)
  - [DescribeDataSourceRequestRequestTypeDef](#describedatasourcerequestrequesttypedef)
  - [DescribeDataSourceResponseTypeDef](#describedatasourceresponsetypedef)
  - [DescribeExperienceRequestRequestTypeDef](#describeexperiencerequestrequesttypedef)
  - [DescribeExperienceResponseTypeDef](#describeexperienceresponsetypedef)
  - [DescribeFaqRequestRequestTypeDef](#describefaqrequestrequesttypedef)
  - [DescribeFaqResponseTypeDef](#describefaqresponsetypedef)
  - [DescribeIndexRequestRequestTypeDef](#describeindexrequestrequesttypedef)
  - [DescribeIndexResponseTypeDef](#describeindexresponsetypedef)
  - [DescribePrincipalMappingRequestRequestTypeDef](#describeprincipalmappingrequestrequesttypedef)
  - [DescribePrincipalMappingResponseTypeDef](#describeprincipalmappingresponsetypedef)
  - [DescribeQuerySuggestionsBlockListRequestRequestTypeDef](#describequerysuggestionsblocklistrequestrequesttypedef)
  - [DescribeQuerySuggestionsBlockListResponseTypeDef](#describequerysuggestionsblocklistresponsetypedef)
  - [DescribeQuerySuggestionsConfigRequestRequestTypeDef](#describequerysuggestionsconfigrequestrequesttypedef)
  - [DescribeQuerySuggestionsConfigResponseTypeDef](#describequerysuggestionsconfigresponsetypedef)
  - [DescribeThesaurusRequestRequestTypeDef](#describethesaurusrequestrequesttypedef)
  - [DescribeThesaurusResponseTypeDef](#describethesaurusresponsetypedef)
  - [DisassociateEntitiesFromExperienceRequestRequestTypeDef](#disassociateentitiesfromexperiencerequestrequesttypedef)
  - [DisassociateEntitiesFromExperienceResponseTypeDef](#disassociateentitiesfromexperienceresponsetypedef)
  - [DisassociatePersonasFromEntitiesRequestRequestTypeDef](#disassociatepersonasfromentitiesrequestrequesttypedef)
  - [DisassociatePersonasFromEntitiesResponseTypeDef](#disassociatepersonasfromentitiesresponsetypedef)
  - [DocumentAttributeConditionTypeDef](#documentattributeconditiontypedef)
  - [DocumentAttributeTargetTypeDef](#documentattributetargettypedef)
  - [DocumentAttributeTypeDef](#documentattributetypedef)
  - [DocumentAttributeValueCountPairTypeDef](#documentattributevaluecountpairtypedef)
  - [DocumentAttributeValueTypeDef](#documentattributevaluetypedef)
  - [DocumentInfoTypeDef](#documentinfotypedef)
  - [DocumentMetadataConfigurationTypeDef](#documentmetadataconfigurationtypedef)
  - [DocumentRelevanceConfigurationTypeDef](#documentrelevanceconfigurationtypedef)
  - [DocumentTypeDef](#documenttypedef)
  - [DocumentsMetadataConfigurationTypeDef](#documentsmetadataconfigurationtypedef)
  - [EntityConfigurationTypeDef](#entityconfigurationtypedef)
  - [EntityDisplayDataTypeDef](#entitydisplaydatatypedef)
  - [EntityPersonaConfigurationTypeDef](#entitypersonaconfigurationtypedef)
  - [ExperienceConfigurationTypeDef](#experienceconfigurationtypedef)
  - [ExperienceEndpointTypeDef](#experienceendpointtypedef)
  - [ExperienceEntitiesSummaryTypeDef](#experienceentitiessummarytypedef)
  - [ExperiencesSummaryTypeDef](#experiencessummarytypedef)
  - [FacetResultTypeDef](#facetresulttypedef)
  - [FacetTypeDef](#facettypedef)
  - [FailedEntityTypeDef](#failedentitytypedef)
  - [FaqStatisticsTypeDef](#faqstatisticstypedef)
  - [FaqSummaryTypeDef](#faqsummarytypedef)
  - [GetQuerySuggestionsRequestRequestTypeDef](#getquerysuggestionsrequestrequesttypedef)
  - [GetQuerySuggestionsResponseTypeDef](#getquerysuggestionsresponsetypedef)
  - [GetSnapshotsRequestRequestTypeDef](#getsnapshotsrequestrequesttypedef)
  - [GetSnapshotsResponseTypeDef](#getsnapshotsresponsetypedef)
  - [GoogleDriveConfigurationTypeDef](#googledriveconfigurationtypedef)
  - [GroupMembersTypeDef](#groupmemberstypedef)
  - [GroupOrderingIdSummaryTypeDef](#grouporderingidsummarytypedef)
  - [GroupSummaryTypeDef](#groupsummarytypedef)
  - [HierarchicalPrincipalTypeDef](#hierarchicalprincipaltypedef)
  - [HighlightTypeDef](#highlighttypedef)
  - [HookConfigurationTypeDef](#hookconfigurationtypedef)
  - [IndexConfigurationSummaryTypeDef](#indexconfigurationsummarytypedef)
  - [IndexStatisticsTypeDef](#indexstatisticstypedef)
  - [InlineCustomDocumentEnrichmentConfigurationTypeDef](#inlinecustomdocumentenrichmentconfigurationtypedef)
  - [JsonTokenTypeConfigurationTypeDef](#jsontokentypeconfigurationtypedef)
  - [JwtTokenTypeConfigurationTypeDef](#jwttokentypeconfigurationtypedef)
  - [ListDataSourceSyncJobsRequestRequestTypeDef](#listdatasourcesyncjobsrequestrequesttypedef)
  - [ListDataSourceSyncJobsResponseTypeDef](#listdatasourcesyncjobsresponsetypedef)
  - [ListDataSourcesRequestRequestTypeDef](#listdatasourcesrequestrequesttypedef)
  - [ListDataSourcesResponseTypeDef](#listdatasourcesresponsetypedef)
  - [ListEntityPersonasRequestRequestTypeDef](#listentitypersonasrequestrequesttypedef)
  - [ListEntityPersonasResponseTypeDef](#listentitypersonasresponsetypedef)
  - [ListExperienceEntitiesRequestRequestTypeDef](#listexperienceentitiesrequestrequesttypedef)
  - [ListExperienceEntitiesResponseTypeDef](#listexperienceentitiesresponsetypedef)
  - [ListExperiencesRequestRequestTypeDef](#listexperiencesrequestrequesttypedef)
  - [ListExperiencesResponseTypeDef](#listexperiencesresponsetypedef)
  - [ListFaqsRequestRequestTypeDef](#listfaqsrequestrequesttypedef)
  - [ListFaqsResponseTypeDef](#listfaqsresponsetypedef)
  - [ListGroupsOlderThanOrderingIdRequestRequestTypeDef](#listgroupsolderthanorderingidrequestrequesttypedef)
  - [ListGroupsOlderThanOrderingIdResponseTypeDef](#listgroupsolderthanorderingidresponsetypedef)
  - [ListIndicesRequestRequestTypeDef](#listindicesrequestrequesttypedef)
  - [ListIndicesResponseTypeDef](#listindicesresponsetypedef)
  - [ListQuerySuggestionsBlockListsRequestRequestTypeDef](#listquerysuggestionsblocklistsrequestrequesttypedef)
  - [ListQuerySuggestionsBlockListsResponseTypeDef](#listquerysuggestionsblocklistsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [ListThesauriRequestRequestTypeDef](#listthesaurirequestrequesttypedef)
  - [ListThesauriResponseTypeDef](#listthesauriresponsetypedef)
  - [MemberGroupTypeDef](#membergrouptypedef)
  - [MemberUserTypeDef](#memberusertypedef)
  - [OneDriveConfigurationTypeDef](#onedriveconfigurationtypedef)
  - [OneDriveUsersTypeDef](#onedriveuserstypedef)
  - [PersonasSummaryTypeDef](#personassummarytypedef)
  - [PrincipalTypeDef](#principaltypedef)
  - [ProxyConfigurationTypeDef](#proxyconfigurationtypedef)
  - [PutPrincipalMappingRequestRequestTypeDef](#putprincipalmappingrequestrequesttypedef)
  - [QueryRequestRequestTypeDef](#queryrequestrequesttypedef)
  - [QueryResultItemTypeDef](#queryresultitemtypedef)
  - [QueryResultTypeDef](#queryresulttypedef)
  - [QuerySuggestionsBlockListSummaryTypeDef](#querysuggestionsblocklistsummarytypedef)
  - [RelevanceFeedbackTypeDef](#relevancefeedbacktypedef)
  - [RelevanceTypeDef](#relevancetypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3DataSourceConfigurationTypeDef](#s3datasourceconfigurationtypedef)
  - [S3PathTypeDef](#s3pathtypedef)
  - [SalesforceChatterFeedConfigurationTypeDef](#salesforcechatterfeedconfigurationtypedef)
  - [SalesforceConfigurationTypeDef](#salesforceconfigurationtypedef)
  - [SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef](#salesforcecustomknowledgearticletypeconfigurationtypedef)
  - [SalesforceKnowledgeArticleConfigurationTypeDef](#salesforceknowledgearticleconfigurationtypedef)
  - [SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef](#salesforcestandardknowledgearticletypeconfigurationtypedef)
  - [SalesforceStandardObjectAttachmentConfigurationTypeDef](#salesforcestandardobjectattachmentconfigurationtypedef)
  - [SalesforceStandardObjectConfigurationTypeDef](#salesforcestandardobjectconfigurationtypedef)
  - [ScoreAttributesTypeDef](#scoreattributestypedef)
  - [SearchTypeDef](#searchtypedef)
  - [SeedUrlConfigurationTypeDef](#seedurlconfigurationtypedef)
  - [ServerSideEncryptionConfigurationTypeDef](#serversideencryptionconfigurationtypedef)
  - [ServiceNowConfigurationTypeDef](#servicenowconfigurationtypedef)
  - [ServiceNowKnowledgeArticleConfigurationTypeDef](#servicenowknowledgearticleconfigurationtypedef)
  - [ServiceNowServiceCatalogConfigurationTypeDef](#servicenowservicecatalogconfigurationtypedef)
  - [SharePointConfigurationTypeDef](#sharepointconfigurationtypedef)
  - [SiteMapsConfigurationTypeDef](#sitemapsconfigurationtypedef)
  - [SortingConfigurationTypeDef](#sortingconfigurationtypedef)
  - [SqlConfigurationTypeDef](#sqlconfigurationtypedef)
  - [StartDataSourceSyncJobRequestRequestTypeDef](#startdatasourcesyncjobrequestrequesttypedef)
  - [StartDataSourceSyncJobResponseTypeDef](#startdatasourcesyncjobresponsetypedef)
  - [StatusTypeDef](#statustypedef)
  - [StopDataSourceSyncJobRequestRequestTypeDef](#stopdatasourcesyncjobrequestrequesttypedef)
  - [SubmitFeedbackRequestRequestTypeDef](#submitfeedbackrequestrequesttypedef)
  - [SuggestionHighlightTypeDef](#suggestionhighlighttypedef)
  - [SuggestionTextWithHighlightsTypeDef](#suggestiontextwithhighlightstypedef)
  - [SuggestionTypeDef](#suggestiontypedef)
  - [SuggestionValueTypeDef](#suggestionvaluetypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TextDocumentStatisticsTypeDef](#textdocumentstatisticstypedef)
  - [TextWithHighlightsTypeDef](#textwithhighlightstypedef)
  - [ThesaurusSummaryTypeDef](#thesaurussummarytypedef)
  - [TimeRangeTypeDef](#timerangetypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateDataSourceRequestRequestTypeDef](#updatedatasourcerequestrequesttypedef)
  - [UpdateExperienceRequestRequestTypeDef](#updateexperiencerequestrequesttypedef)
  - [UpdateIndexRequestRequestTypeDef](#updateindexrequestrequesttypedef)
  - [UpdateQuerySuggestionsBlockListRequestRequestTypeDef](#updatequerysuggestionsblocklistrequestrequesttypedef)
  - [UpdateQuerySuggestionsConfigRequestRequestTypeDef](#updatequerysuggestionsconfigrequestrequesttypedef)
  - [UpdateThesaurusRequestRequestTypeDef](#updatethesaurusrequestrequesttypedef)
  - [UrlsTypeDef](#urlstypedef)
  - [UserContextTypeDef](#usercontexttypedef)
  - [UserGroupResolutionConfigurationTypeDef](#usergroupresolutionconfigurationtypedef)
  - [UserIdentityConfigurationTypeDef](#useridentityconfigurationtypedef)
  - [UserTokenConfigurationTypeDef](#usertokenconfigurationtypedef)
  - [WebCrawlerConfigurationTypeDef](#webcrawlerconfigurationtypedef)
  - [WorkDocsConfigurationTypeDef](#workdocsconfigurationtypedef)

<a id="accesscontrollistconfigurationtypedef"></a>

## AccessControlListConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import AccessControlListConfigurationTypeDef
```

Optional fields:

- `KeyPath`: `str`

<a id="aclconfigurationtypedef"></a>

## AclConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import AclConfigurationTypeDef
```

Required fields:

- `AllowedGroupsColumnName`: `str`

<a id="additionalresultattributetypedef"></a>

## AdditionalResultAttributeTypeDef

```python
from types_aiobotocore_kendra.type_defs import AdditionalResultAttributeTypeDef
```

Required fields:

- `Key`: `str`
- `ValueType`: `Literal['TEXT_WITH_HIGHLIGHTS_VALUE']` (see
  [AdditionalResultAttributeValueTypeType](./literals.md#additionalresultattributevaluetypetype))
- `Value`:
  [AdditionalResultAttributeValueTypeDef](./type_defs.md#additionalresultattributevaluetypedef)

<a id="additionalresultattributevaluetypedef"></a>

## AdditionalResultAttributeValueTypeDef

```python
from types_aiobotocore_kendra.type_defs import AdditionalResultAttributeValueTypeDef
```

Optional fields:

- `TextWithHighlightsValue`:
  [TextWithHighlightsTypeDef](./type_defs.md#textwithhighlightstypedef)

<a id="associateentitiestoexperiencerequestrequesttypedef"></a>

## AssociateEntitiesToExperienceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import AssociateEntitiesToExperienceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `EntityList`:
  `Sequence`\[[EntityConfigurationTypeDef](./type_defs.md#entityconfigurationtypedef)\]

<a id="associateentitiestoexperienceresponsetypedef"></a>

## AssociateEntitiesToExperienceResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import AssociateEntitiesToExperienceResponseTypeDef
```

Required fields:

- `FailedEntityList`:
  `List`\[[FailedEntityTypeDef](./type_defs.md#failedentitytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="associatepersonastoentitiesrequestrequesttypedef"></a>

## AssociatePersonasToEntitiesRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import AssociatePersonasToEntitiesRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `Personas`:
  `Sequence`\[[EntityPersonaConfigurationTypeDef](./type_defs.md#entitypersonaconfigurationtypedef)\]

<a id="associatepersonastoentitiesresponsetypedef"></a>

## AssociatePersonasToEntitiesResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import AssociatePersonasToEntitiesResponseTypeDef
```

Required fields:

- `FailedEntityList`:
  `List`\[[FailedEntityTypeDef](./type_defs.md#failedentitytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="attributefiltertypedef"></a>

## AttributeFilterTypeDef

```python
from types_aiobotocore_kendra.type_defs import AttributeFilterTypeDef
```

Optional fields:

- `AndAllFilters`:
  `Sequence`\[[AttributeFilterTypeDef](./type_defs.md#attributefiltertypedef)\]
- `OrAllFilters`:
  `Sequence`\[[AttributeFilterTypeDef](./type_defs.md#attributefiltertypedef)\]
- `NotFilter`: [AttributeFilterTypeDef](./type_defs.md#attributefiltertypedef)
- `EqualsTo`:
  [DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)
- `ContainsAll`:
  [DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)
- `ContainsAny`:
  [DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)
- `GreaterThan`:
  [DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)
- `GreaterThanOrEquals`:
  [DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)
- `LessThan`:
  [DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)
- `LessThanOrEquals`:
  [DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)

<a id="authenticationconfigurationtypedef"></a>

## AuthenticationConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import AuthenticationConfigurationTypeDef
```

Optional fields:

- `BasicAuthentication`:
  `Sequence`\[[BasicAuthenticationConfigurationTypeDef](./type_defs.md#basicauthenticationconfigurationtypedef)\]

<a id="basicauthenticationconfigurationtypedef"></a>

## BasicAuthenticationConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import BasicAuthenticationConfigurationTypeDef
```

Required fields:

- `Host`: `str`
- `Port`: `int`
- `Credentials`: `str`

<a id="batchdeletedocumentrequestrequesttypedef"></a>

## BatchDeleteDocumentRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchDeleteDocumentRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `DocumentIdList`: `Sequence`\[`str`\]

Optional fields:

- `DataSourceSyncJobMetricTarget`:
  [DataSourceSyncJobMetricTargetTypeDef](./type_defs.md#datasourcesyncjobmetrictargettypedef)

<a id="batchdeletedocumentresponsefaileddocumenttypedef"></a>

## BatchDeleteDocumentResponseFailedDocumentTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchDeleteDocumentResponseFailedDocumentTypeDef
```

Optional fields:

- `Id`: `str`
- `ErrorCode`: [ErrorCodeType](./literals.md#errorcodetype)
- `ErrorMessage`: `str`

<a id="batchdeletedocumentresponsetypedef"></a>

## BatchDeleteDocumentResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchDeleteDocumentResponseTypeDef
```

Required fields:

- `FailedDocuments`:
  `List`\[[BatchDeleteDocumentResponseFailedDocumentTypeDef](./type_defs.md#batchdeletedocumentresponsefaileddocumenttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="batchgetdocumentstatusrequestrequesttypedef"></a>

## BatchGetDocumentStatusRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchGetDocumentStatusRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `DocumentInfoList`:
  `Sequence`\[[DocumentInfoTypeDef](./type_defs.md#documentinfotypedef)\]

<a id="batchgetdocumentstatusresponseerrortypedef"></a>

## BatchGetDocumentStatusResponseErrorTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchGetDocumentStatusResponseErrorTypeDef
```

Optional fields:

- `DocumentId`: `str`
- `ErrorCode`: [ErrorCodeType](./literals.md#errorcodetype)
- `ErrorMessage`: `str`

<a id="batchgetdocumentstatusresponsetypedef"></a>

## BatchGetDocumentStatusResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchGetDocumentStatusResponseTypeDef
```

Required fields:

- `Errors`:
  `List`\[[BatchGetDocumentStatusResponseErrorTypeDef](./type_defs.md#batchgetdocumentstatusresponseerrortypedef)\]
- `DocumentStatusList`: `List`\[[StatusTypeDef](./type_defs.md#statustypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="batchputdocumentrequestrequesttypedef"></a>

## BatchPutDocumentRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchPutDocumentRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Documents`: `Sequence`\[[DocumentTypeDef](./type_defs.md#documenttypedef)\]

Optional fields:

- `RoleArn`: `str`
- `CustomDocumentEnrichmentConfiguration`:
  [CustomDocumentEnrichmentConfigurationTypeDef](./type_defs.md#customdocumentenrichmentconfigurationtypedef)

<a id="batchputdocumentresponsefaileddocumenttypedef"></a>

## BatchPutDocumentResponseFailedDocumentTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchPutDocumentResponseFailedDocumentTypeDef
```

Optional fields:

- `Id`: `str`
- `ErrorCode`: [ErrorCodeType](./literals.md#errorcodetype)
- `ErrorMessage`: `str`

<a id="batchputdocumentresponsetypedef"></a>

## BatchPutDocumentResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import BatchPutDocumentResponseTypeDef
```

Required fields:

- `FailedDocuments`:
  `List`\[[BatchPutDocumentResponseFailedDocumentTypeDef](./type_defs.md#batchputdocumentresponsefaileddocumenttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="capacityunitsconfigurationtypedef"></a>

## CapacityUnitsConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import CapacityUnitsConfigurationTypeDef
```

Required fields:

- `StorageCapacityUnits`: `int`
- `QueryCapacityUnits`: `int`

<a id="clearquerysuggestionsrequestrequesttypedef"></a>

## ClearQuerySuggestionsRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ClearQuerySuggestionsRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

<a id="clickfeedbacktypedef"></a>

## ClickFeedbackTypeDef

```python
from types_aiobotocore_kendra.type_defs import ClickFeedbackTypeDef
```

Required fields:

- `ResultId`: `str`
- `ClickTime`: `Union`\[`datetime`, `str`\]

<a id="columnconfigurationtypedef"></a>

## ColumnConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ColumnConfigurationTypeDef
```

Required fields:

- `DocumentIdColumnName`: `str`
- `DocumentDataColumnName`: `str`
- `ChangeDetectingColumns`: `Sequence`\[`str`\]

Optional fields:

- `DocumentTitleColumnName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]

<a id="confluenceattachmentconfigurationtypedef"></a>

## ConfluenceAttachmentConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluenceAttachmentConfigurationTypeDef
```

Optional fields:

- `CrawlAttachments`: `bool`
- `AttachmentFieldMappings`:
  `Sequence`\[[ConfluenceAttachmentToIndexFieldMappingTypeDef](./type_defs.md#confluenceattachmenttoindexfieldmappingtypedef)\]

<a id="confluenceattachmenttoindexfieldmappingtypedef"></a>

## ConfluenceAttachmentToIndexFieldMappingTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluenceAttachmentToIndexFieldMappingTypeDef
```

Optional fields:

- `DataSourceFieldName`:
  [ConfluenceAttachmentFieldNameType](./literals.md#confluenceattachmentfieldnametype)
- `DateFieldFormat`: `str`
- `IndexFieldName`: `str`

<a id="confluenceblogconfigurationtypedef"></a>

## ConfluenceBlogConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluenceBlogConfigurationTypeDef
```

Optional fields:

- `BlogFieldMappings`:
  `Sequence`\[[ConfluenceBlogToIndexFieldMappingTypeDef](./type_defs.md#confluenceblogtoindexfieldmappingtypedef)\]

<a id="confluenceblogtoindexfieldmappingtypedef"></a>

## ConfluenceBlogToIndexFieldMappingTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluenceBlogToIndexFieldMappingTypeDef
```

Optional fields:

- `DataSourceFieldName`:
  [ConfluenceBlogFieldNameType](./literals.md#confluenceblogfieldnametype)
- `DateFieldFormat`: `str`
- `IndexFieldName`: `str`

<a id="confluenceconfigurationtypedef"></a>

## ConfluenceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluenceConfigurationTypeDef
```

Required fields:

- `ServerUrl`: `str`
- `SecretArn`: `str`
- `Version`: [ConfluenceVersionType](./literals.md#confluenceversiontype)

Optional fields:

- `SpaceConfiguration`:
  [ConfluenceSpaceConfigurationTypeDef](./type_defs.md#confluencespaceconfigurationtypedef)
- `PageConfiguration`:
  [ConfluencePageConfigurationTypeDef](./type_defs.md#confluencepageconfigurationtypedef)
- `BlogConfiguration`:
  [ConfluenceBlogConfigurationTypeDef](./type_defs.md#confluenceblogconfigurationtypedef)
- `AttachmentConfiguration`:
  [ConfluenceAttachmentConfigurationTypeDef](./type_defs.md#confluenceattachmentconfigurationtypedef)
- `VpcConfiguration`:
  [DataSourceVpcConfigurationTypeDef](./type_defs.md#datasourcevpcconfigurationtypedef)
- `InclusionPatterns`: `Sequence`\[`str`\]
- `ExclusionPatterns`: `Sequence`\[`str`\]

<a id="confluencepageconfigurationtypedef"></a>

## ConfluencePageConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluencePageConfigurationTypeDef
```

Optional fields:

- `PageFieldMappings`:
  `Sequence`\[[ConfluencePageToIndexFieldMappingTypeDef](./type_defs.md#confluencepagetoindexfieldmappingtypedef)\]

<a id="confluencepagetoindexfieldmappingtypedef"></a>

## ConfluencePageToIndexFieldMappingTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluencePageToIndexFieldMappingTypeDef
```

Optional fields:

- `DataSourceFieldName`:
  [ConfluencePageFieldNameType](./literals.md#confluencepagefieldnametype)
- `DateFieldFormat`: `str`
- `IndexFieldName`: `str`

<a id="confluencespaceconfigurationtypedef"></a>

## ConfluenceSpaceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluenceSpaceConfigurationTypeDef
```

Optional fields:

- `CrawlPersonalSpaces`: `bool`
- `CrawlArchivedSpaces`: `bool`
- `IncludeSpaces`: `Sequence`\[`str`\]
- `ExcludeSpaces`: `Sequence`\[`str`\]
- `SpaceFieldMappings`:
  `Sequence`\[[ConfluenceSpaceToIndexFieldMappingTypeDef](./type_defs.md#confluencespacetoindexfieldmappingtypedef)\]

<a id="confluencespacetoindexfieldmappingtypedef"></a>

## ConfluenceSpaceToIndexFieldMappingTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConfluenceSpaceToIndexFieldMappingTypeDef
```

Optional fields:

- `DataSourceFieldName`:
  [ConfluenceSpaceFieldNameType](./literals.md#confluencespacefieldnametype)
- `DateFieldFormat`: `str`
- `IndexFieldName`: `str`

<a id="connectionconfigurationtypedef"></a>

## ConnectionConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ConnectionConfigurationTypeDef
```

Required fields:

- `DatabaseHost`: `str`
- `DatabasePort`: `int`
- `DatabaseName`: `str`
- `TableName`: `str`
- `SecretArn`: `str`

<a id="contentsourceconfigurationtypedef"></a>

## ContentSourceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ContentSourceConfigurationTypeDef
```

Optional fields:

- `DataSourceIds`: `Sequence`\[`str`\]
- `FaqIds`: `Sequence`\[`str`\]
- `DirectPutContent`: `bool`

<a id="createdatasourcerequestrequesttypedef"></a>

## CreateDataSourceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateDataSourceRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `IndexId`: `str`
- `Type`: [DataSourceTypeType](./literals.md#datasourcetypetype)

Optional fields:

- `Configuration`:
  [DataSourceConfigurationTypeDef](./type_defs.md#datasourceconfigurationtypedef)
- `Description`: `str`
- `Schedule`: `str`
- `RoleArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`
- `LanguageCode`: `str`
- `CustomDocumentEnrichmentConfiguration`:
  [CustomDocumentEnrichmentConfigurationTypeDef](./type_defs.md#customdocumentenrichmentconfigurationtypedef)

<a id="createdatasourceresponsetypedef"></a>

## CreateDataSourceResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateDataSourceResponseTypeDef
```

Required fields:

- `Id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createexperiencerequestrequesttypedef"></a>

## CreateExperienceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateExperienceRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `IndexId`: `str`

Optional fields:

- `RoleArn`: `str`
- `Configuration`:
  [ExperienceConfigurationTypeDef](./type_defs.md#experienceconfigurationtypedef)
- `Description`: `str`
- `ClientToken`: `str`

<a id="createexperienceresponsetypedef"></a>

## CreateExperienceResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateExperienceResponseTypeDef
```

Required fields:

- `Id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createfaqrequestrequesttypedef"></a>

## CreateFaqRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateFaqRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Name`: `str`
- `S3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)
- `RoleArn`: `str`

Optional fields:

- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `FileFormat`: [FaqFileFormatType](./literals.md#faqfileformattype)
- `ClientToken`: `str`
- `LanguageCode`: `str`

<a id="createfaqresponsetypedef"></a>

## CreateFaqResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateFaqResponseTypeDef
```

Required fields:

- `Id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createindexrequestrequesttypedef"></a>

## CreateIndexRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateIndexRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `RoleArn`: `str`

Optional fields:

- `Edition`: [IndexEditionType](./literals.md#indexeditiontype)
- `ServerSideEncryptionConfiguration`:
  [ServerSideEncryptionConfigurationTypeDef](./type_defs.md#serversideencryptionconfigurationtypedef)
- `Description`: `str`
- `ClientToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `UserTokenConfigurations`:
  `Sequence`\[[UserTokenConfigurationTypeDef](./type_defs.md#usertokenconfigurationtypedef)\]
- `UserContextPolicy`:
  [UserContextPolicyType](./literals.md#usercontextpolicytype)
- `UserGroupResolutionConfiguration`:
  [UserGroupResolutionConfigurationTypeDef](./type_defs.md#usergroupresolutionconfigurationtypedef)

<a id="createindexresponsetypedef"></a>

## CreateIndexResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateIndexResponseTypeDef
```

Required fields:

- `Id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createquerysuggestionsblocklistrequestrequesttypedef"></a>

## CreateQuerySuggestionsBlockListRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateQuerySuggestionsBlockListRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Name`: `str`
- `SourceS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)
- `RoleArn`: `str`

Optional fields:

- `Description`: `str`
- `ClientToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createquerysuggestionsblocklistresponsetypedef"></a>

## CreateQuerySuggestionsBlockListResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateQuerySuggestionsBlockListResponseTypeDef
```

Required fields:

- `Id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createthesaurusrequestrequesttypedef"></a>

## CreateThesaurusRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateThesaurusRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Name`: `str`
- `RoleArn`: `str`
- `SourceS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)

Optional fields:

- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`

<a id="createthesaurusresponsetypedef"></a>

## CreateThesaurusResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import CreateThesaurusResponseTypeDef
```

Required fields:

- `Id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="customdocumentenrichmentconfigurationtypedef"></a>

## CustomDocumentEnrichmentConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import CustomDocumentEnrichmentConfigurationTypeDef
```

Optional fields:

- `InlineConfigurations`:
  `Sequence`\[[InlineCustomDocumentEnrichmentConfigurationTypeDef](./type_defs.md#inlinecustomdocumentenrichmentconfigurationtypedef)\]
- `PreExtractionHookConfiguration`:
  [HookConfigurationTypeDef](./type_defs.md#hookconfigurationtypedef)
- `PostExtractionHookConfiguration`:
  [HookConfigurationTypeDef](./type_defs.md#hookconfigurationtypedef)
- `RoleArn`: `str`

<a id="datasourceconfigurationtypedef"></a>

## DataSourceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceConfigurationTypeDef
```

Optional fields:

- `S3Configuration`:
  [S3DataSourceConfigurationTypeDef](./type_defs.md#s3datasourceconfigurationtypedef)
- `SharePointConfiguration`:
  [SharePointConfigurationTypeDef](./type_defs.md#sharepointconfigurationtypedef)
- `DatabaseConfiguration`:
  [DatabaseConfigurationTypeDef](./type_defs.md#databaseconfigurationtypedef)
- `SalesforceConfiguration`:
  [SalesforceConfigurationTypeDef](./type_defs.md#salesforceconfigurationtypedef)
- `OneDriveConfiguration`:
  [OneDriveConfigurationTypeDef](./type_defs.md#onedriveconfigurationtypedef)
- `ServiceNowConfiguration`:
  [ServiceNowConfigurationTypeDef](./type_defs.md#servicenowconfigurationtypedef)
- `ConfluenceConfiguration`:
  [ConfluenceConfigurationTypeDef](./type_defs.md#confluenceconfigurationtypedef)
- `GoogleDriveConfiguration`:
  [GoogleDriveConfigurationTypeDef](./type_defs.md#googledriveconfigurationtypedef)
- `WebCrawlerConfiguration`:
  [WebCrawlerConfigurationTypeDef](./type_defs.md#webcrawlerconfigurationtypedef)
- `WorkDocsConfiguration`:
  [WorkDocsConfigurationTypeDef](./type_defs.md#workdocsconfigurationtypedef)

<a id="datasourcegrouptypedef"></a>

## DataSourceGroupTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceGroupTypeDef
```

Required fields:

- `GroupId`: `str`
- `DataSourceId`: `str`

<a id="datasourcesummarytypedef"></a>

## DataSourceSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceSummaryTypeDef
```

Optional fields:

- `Name`: `str`
- `Id`: `str`
- `Type`: [DataSourceTypeType](./literals.md#datasourcetypetype)
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `Status`: [DataSourceStatusType](./literals.md#datasourcestatustype)
- `LanguageCode`: `str`

<a id="datasourcesyncjobmetrictargettypedef"></a>

## DataSourceSyncJobMetricTargetTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceSyncJobMetricTargetTypeDef
```

Required fields:

- `DataSourceId`: `str`

Optional fields:

- `DataSourceSyncJobId`: `str`

<a id="datasourcesyncjobmetricstypedef"></a>

## DataSourceSyncJobMetricsTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceSyncJobMetricsTypeDef
```

Optional fields:

- `DocumentsAdded`: `str`
- `DocumentsModified`: `str`
- `DocumentsDeleted`: `str`
- `DocumentsFailed`: `str`
- `DocumentsScanned`: `str`

<a id="datasourcesyncjobtypedef"></a>

## DataSourceSyncJobTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceSyncJobTypeDef
```

Optional fields:

- `ExecutionId`: `str`
- `StartTime`: `datetime`
- `EndTime`: `datetime`
- `Status`:
  [DataSourceSyncJobStatusType](./literals.md#datasourcesyncjobstatustype)
- `ErrorMessage`: `str`
- `ErrorCode`: [ErrorCodeType](./literals.md#errorcodetype)
- `DataSourceErrorCode`: `str`
- `Metrics`:
  [DataSourceSyncJobMetricsTypeDef](./type_defs.md#datasourcesyncjobmetricstypedef)

<a id="datasourcetoindexfieldmappingtypedef"></a>

## DataSourceToIndexFieldMappingTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceToIndexFieldMappingTypeDef
```

Required fields:

- `DataSourceFieldName`: `str`
- `IndexFieldName`: `str`

Optional fields:

- `DateFieldFormat`: `str`

<a id="datasourcevpcconfigurationtypedef"></a>

## DataSourceVpcConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import DataSourceVpcConfigurationTypeDef
```

Required fields:

- `SubnetIds`: `Sequence`\[`str`\]
- `SecurityGroupIds`: `Sequence`\[`str`\]

<a id="databaseconfigurationtypedef"></a>

## DatabaseConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import DatabaseConfigurationTypeDef
```

Required fields:

- `DatabaseEngineType`:
  [DatabaseEngineTypeType](./literals.md#databaseenginetypetype)
- `ConnectionConfiguration`:
  [ConnectionConfigurationTypeDef](./type_defs.md#connectionconfigurationtypedef)
- `ColumnConfiguration`:
  [ColumnConfigurationTypeDef](./type_defs.md#columnconfigurationtypedef)

Optional fields:

- `VpcConfiguration`:
  [DataSourceVpcConfigurationTypeDef](./type_defs.md#datasourcevpcconfigurationtypedef)
- `AclConfiguration`:
  [AclConfigurationTypeDef](./type_defs.md#aclconfigurationtypedef)
- `SqlConfiguration`:
  [SqlConfigurationTypeDef](./type_defs.md#sqlconfigurationtypedef)

<a id="deletedatasourcerequestrequesttypedef"></a>

## DeleteDataSourceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DeleteDataSourceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="deleteexperiencerequestrequesttypedef"></a>

## DeleteExperienceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DeleteExperienceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="deletefaqrequestrequesttypedef"></a>

## DeleteFaqRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DeleteFaqRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="deleteindexrequestrequesttypedef"></a>

## DeleteIndexRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DeleteIndexRequestRequestTypeDef
```

Required fields:

- `Id`: `str`

<a id="deleteprincipalmappingrequestrequesttypedef"></a>

## DeletePrincipalMappingRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DeletePrincipalMappingRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `GroupId`: `str`

Optional fields:

- `DataSourceId`: `str`
- `OrderingId`: `int`

<a id="deletequerysuggestionsblocklistrequestrequesttypedef"></a>

## DeleteQuerySuggestionsBlockListRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DeleteQuerySuggestionsBlockListRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Id`: `str`

<a id="deletethesaurusrequestrequesttypedef"></a>

## DeleteThesaurusRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DeleteThesaurusRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="describedatasourcerequestrequesttypedef"></a>

## DescribeDataSourceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeDataSourceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="describedatasourceresponsetypedef"></a>

## DescribeDataSourceResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeDataSourceResponseTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `Name`: `str`
- `Type`: [DataSourceTypeType](./literals.md#datasourcetypetype)
- `Configuration`:
  [DataSourceConfigurationTypeDef](./type_defs.md#datasourceconfigurationtypedef)
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `Description`: `str`
- `Status`: [DataSourceStatusType](./literals.md#datasourcestatustype)
- `Schedule`: `str`
- `RoleArn`: `str`
- `ErrorMessage`: `str`
- `LanguageCode`: `str`
- `CustomDocumentEnrichmentConfiguration`:
  [CustomDocumentEnrichmentConfigurationTypeDef](./type_defs.md#customdocumentenrichmentconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeexperiencerequestrequesttypedef"></a>

## DescribeExperienceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeExperienceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="describeexperienceresponsetypedef"></a>

## DescribeExperienceResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeExperienceResponseTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `Name`: `str`
- `Endpoints`:
  `List`\[[ExperienceEndpointTypeDef](./type_defs.md#experienceendpointtypedef)\]
- `Configuration`:
  [ExperienceConfigurationTypeDef](./type_defs.md#experienceconfigurationtypedef)
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `Description`: `str`
- `Status`: [ExperienceStatusType](./literals.md#experiencestatustype)
- `RoleArn`: `str`
- `ErrorMessage`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describefaqrequestrequesttypedef"></a>

## DescribeFaqRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeFaqRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="describefaqresponsetypedef"></a>

## DescribeFaqResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeFaqResponseTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `Name`: `str`
- `Description`: `str`
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `S3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)
- `Status`: [FaqStatusType](./literals.md#faqstatustype)
- `RoleArn`: `str`
- `ErrorMessage`: `str`
- `FileFormat`: [FaqFileFormatType](./literals.md#faqfileformattype)
- `LanguageCode`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeindexrequestrequesttypedef"></a>

## DescribeIndexRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeIndexRequestRequestTypeDef
```

Required fields:

- `Id`: `str`

<a id="describeindexresponsetypedef"></a>

## DescribeIndexResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeIndexResponseTypeDef
```

Required fields:

- `Name`: `str`
- `Id`: `str`
- `Edition`: [IndexEditionType](./literals.md#indexeditiontype)
- `RoleArn`: `str`
- `ServerSideEncryptionConfiguration`:
  [ServerSideEncryptionConfigurationTypeDef](./type_defs.md#serversideencryptionconfigurationtypedef)
- `Status`: [IndexStatusType](./literals.md#indexstatustype)
- `Description`: `str`
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `DocumentMetadataConfigurations`:
  `List`\[[DocumentMetadataConfigurationTypeDef](./type_defs.md#documentmetadataconfigurationtypedef)\]
- `IndexStatistics`:
  [IndexStatisticsTypeDef](./type_defs.md#indexstatisticstypedef)
- `ErrorMessage`: `str`
- `CapacityUnits`:
  [CapacityUnitsConfigurationTypeDef](./type_defs.md#capacityunitsconfigurationtypedef)
- `UserTokenConfigurations`:
  `List`\[[UserTokenConfigurationTypeDef](./type_defs.md#usertokenconfigurationtypedef)\]
- `UserContextPolicy`:
  [UserContextPolicyType](./literals.md#usercontextpolicytype)
- `UserGroupResolutionConfiguration`:
  [UserGroupResolutionConfigurationTypeDef](./type_defs.md#usergroupresolutionconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeprincipalmappingrequestrequesttypedef"></a>

## DescribePrincipalMappingRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribePrincipalMappingRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `GroupId`: `str`

Optional fields:

- `DataSourceId`: `str`

<a id="describeprincipalmappingresponsetypedef"></a>

## DescribePrincipalMappingResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribePrincipalMappingResponseTypeDef
```

Required fields:

- `IndexId`: `str`
- `DataSourceId`: `str`
- `GroupId`: `str`
- `GroupOrderingIdSummaries`:
  `List`\[[GroupOrderingIdSummaryTypeDef](./type_defs.md#grouporderingidsummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describequerysuggestionsblocklistrequestrequesttypedef"></a>

## DescribeQuerySuggestionsBlockListRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeQuerySuggestionsBlockListRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Id`: `str`

<a id="describequerysuggestionsblocklistresponsetypedef"></a>

## DescribeQuerySuggestionsBlockListResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeQuerySuggestionsBlockListResponseTypeDef
```

Required fields:

- `IndexId`: `str`
- `Id`: `str`
- `Name`: `str`
- `Description`: `str`
- `Status`:
  [QuerySuggestionsBlockListStatusType](./literals.md#querysuggestionsblockliststatustype)
- `ErrorMessage`: `str`
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `SourceS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)
- `ItemCount`: `int`
- `FileSizeBytes`: `int`
- `RoleArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describequerysuggestionsconfigrequestrequesttypedef"></a>

## DescribeQuerySuggestionsConfigRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeQuerySuggestionsConfigRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

<a id="describequerysuggestionsconfigresponsetypedef"></a>

## DescribeQuerySuggestionsConfigResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeQuerySuggestionsConfigResponseTypeDef
```

Required fields:

- `Mode`: [ModeType](./literals.md#modetype)
- `Status`:
  [QuerySuggestionsStatusType](./literals.md#querysuggestionsstatustype)
- `QueryLogLookBackWindowInDays`: `int`
- `IncludeQueriesWithoutUserInformation`: `bool`
- `MinimumNumberOfQueryingUsers`: `int`
- `MinimumQueryCount`: `int`
- `LastSuggestionsBuildTime`: `datetime`
- `LastClearTime`: `datetime`
- `TotalSuggestionsCount`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describethesaurusrequestrequesttypedef"></a>

## DescribeThesaurusRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeThesaurusRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="describethesaurusresponsetypedef"></a>

## DescribeThesaurusResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DescribeThesaurusResponseTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `Name`: `str`
- `Description`: `str`
- `Status`: [ThesaurusStatusType](./literals.md#thesaurusstatustype)
- `ErrorMessage`: `str`
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `RoleArn`: `str`
- `SourceS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)
- `FileSizeBytes`: `int`
- `TermCount`: `int`
- `SynonymRuleCount`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disassociateentitiesfromexperiencerequestrequesttypedef"></a>

## DisassociateEntitiesFromExperienceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DisassociateEntitiesFromExperienceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `EntityList`:
  `Sequence`\[[EntityConfigurationTypeDef](./type_defs.md#entityconfigurationtypedef)\]

<a id="disassociateentitiesfromexperienceresponsetypedef"></a>

## DisassociateEntitiesFromExperienceResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DisassociateEntitiesFromExperienceResponseTypeDef
```

Required fields:

- `FailedEntityList`:
  `List`\[[FailedEntityTypeDef](./type_defs.md#failedentitytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disassociatepersonasfromentitiesrequestrequesttypedef"></a>

## DisassociatePersonasFromEntitiesRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import DisassociatePersonasFromEntitiesRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`
- `EntityIds`: `Sequence`\[`str`\]

<a id="disassociatepersonasfromentitiesresponsetypedef"></a>

## DisassociatePersonasFromEntitiesResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import DisassociatePersonasFromEntitiesResponseTypeDef
```

Required fields:

- `FailedEntityList`:
  `List`\[[FailedEntityTypeDef](./type_defs.md#failedentitytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="documentattributeconditiontypedef"></a>

## DocumentAttributeConditionTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentAttributeConditionTypeDef
```

Required fields:

- `ConditionDocumentAttributeKey`: `str`
- `Operator`: [ConditionOperatorType](./literals.md#conditionoperatortype)

Optional fields:

- `ConditionOnValue`:
  [DocumentAttributeValueTypeDef](./type_defs.md#documentattributevaluetypedef)

<a id="documentattributetargettypedef"></a>

## DocumentAttributeTargetTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentAttributeTargetTypeDef
```

Optional fields:

- `TargetDocumentAttributeKey`: `str`
- `TargetDocumentAttributeValueDeletion`: `bool`
- `TargetDocumentAttributeValue`:
  [DocumentAttributeValueTypeDef](./type_defs.md#documentattributevaluetypedef)

<a id="documentattributetypedef"></a>

## DocumentAttributeTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentAttributeTypeDef
```

Required fields:

- `Key`: `str`
- `Value`:
  [DocumentAttributeValueTypeDef](./type_defs.md#documentattributevaluetypedef)

<a id="documentattributevaluecountpairtypedef"></a>

## DocumentAttributeValueCountPairTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentAttributeValueCountPairTypeDef
```

Optional fields:

- `DocumentAttributeValue`:
  [DocumentAttributeValueTypeDef](./type_defs.md#documentattributevaluetypedef)
- `Count`: `int`

<a id="documentattributevaluetypedef"></a>

## DocumentAttributeValueTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentAttributeValueTypeDef
```

Optional fields:

- `StringValue`: `str`
- `StringListValue`: `Sequence`\[`str`\]
- `LongValue`: `int`
- `DateValue`: `Union`\[`datetime`, `str`\]

<a id="documentinfotypedef"></a>

## DocumentInfoTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentInfoTypeDef
```

Required fields:

- `DocumentId`: `str`

Optional fields:

- `Attributes`:
  `Sequence`\[[DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)\]

<a id="documentmetadataconfigurationtypedef"></a>

## DocumentMetadataConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentMetadataConfigurationTypeDef
```

Required fields:

- `Name`: `str`
- `Type`:
  [DocumentAttributeValueTypeType](./literals.md#documentattributevaluetypetype)

Optional fields:

- `Relevance`: [RelevanceTypeDef](./type_defs.md#relevancetypedef)
- `Search`: [SearchTypeDef](./type_defs.md#searchtypedef)

<a id="documentrelevanceconfigurationtypedef"></a>

## DocumentRelevanceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentRelevanceConfigurationTypeDef
```

Required fields:

- `Name`: `str`
- `Relevance`: [RelevanceTypeDef](./type_defs.md#relevancetypedef)

<a id="documenttypedef"></a>

## DocumentTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentTypeDef
```

Required fields:

- `Id`: `str`

Optional fields:

- `Title`: `str`
- `Blob`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
- `S3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)
- `Attributes`:
  `Sequence`\[[DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)\]
- `AccessControlList`:
  `Sequence`\[[PrincipalTypeDef](./type_defs.md#principaltypedef)\]
- `HierarchicalAccessControlList`:
  `Sequence`\[[HierarchicalPrincipalTypeDef](./type_defs.md#hierarchicalprincipaltypedef)\]
- `ContentType`: [ContentTypeType](./literals.md#contenttypetype)

<a id="documentsmetadataconfigurationtypedef"></a>

## DocumentsMetadataConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import DocumentsMetadataConfigurationTypeDef
```

Optional fields:

- `S3Prefix`: `str`

<a id="entityconfigurationtypedef"></a>

## EntityConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import EntityConfigurationTypeDef
```

Required fields:

- `EntityId`: `str`
- `EntityType`: [EntityTypeType](./literals.md#entitytypetype)

<a id="entitydisplaydatatypedef"></a>

## EntityDisplayDataTypeDef

```python
from types_aiobotocore_kendra.type_defs import EntityDisplayDataTypeDef
```

Optional fields:

- `UserName`: `str`
- `GroupName`: `str`
- `IdentifiedUserName`: `str`
- `FirstName`: `str`
- `LastName`: `str`

<a id="entitypersonaconfigurationtypedef"></a>

## EntityPersonaConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import EntityPersonaConfigurationTypeDef
```

Required fields:

- `EntityId`: `str`
- `Persona`: [PersonaType](./literals.md#personatype)

<a id="experienceconfigurationtypedef"></a>

## ExperienceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ExperienceConfigurationTypeDef
```

Optional fields:

- `ContentSourceConfiguration`:
  [ContentSourceConfigurationTypeDef](./type_defs.md#contentsourceconfigurationtypedef)
- `UserIdentityConfiguration`:
  [UserIdentityConfigurationTypeDef](./type_defs.md#useridentityconfigurationtypedef)

<a id="experienceendpointtypedef"></a>

## ExperienceEndpointTypeDef

```python
from types_aiobotocore_kendra.type_defs import ExperienceEndpointTypeDef
```

Optional fields:

- `EndpointType`: `Literal['HOME']` (see
  [EndpointTypeType](./literals.md#endpointtypetype))
- `Endpoint`: `str`

<a id="experienceentitiessummarytypedef"></a>

## ExperienceEntitiesSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import ExperienceEntitiesSummaryTypeDef
```

Optional fields:

- `EntityId`: `str`
- `EntityType`: [EntityTypeType](./literals.md#entitytypetype)
- `DisplayData`:
  [EntityDisplayDataTypeDef](./type_defs.md#entitydisplaydatatypedef)

<a id="experiencessummarytypedef"></a>

## ExperiencesSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import ExperiencesSummaryTypeDef
```

Optional fields:

- `Name`: `str`
- `Id`: `str`
- `CreatedAt`: `datetime`
- `Status`: [ExperienceStatusType](./literals.md#experiencestatustype)
- `Endpoints`:
  `List`\[[ExperienceEndpointTypeDef](./type_defs.md#experienceendpointtypedef)\]

<a id="facetresulttypedef"></a>

## FacetResultTypeDef

```python
from types_aiobotocore_kendra.type_defs import FacetResultTypeDef
```

Optional fields:

- `DocumentAttributeKey`: `str`
- `DocumentAttributeValueType`:
  [DocumentAttributeValueTypeType](./literals.md#documentattributevaluetypetype)
- `DocumentAttributeValueCountPairs`:
  `List`\[[DocumentAttributeValueCountPairTypeDef](./type_defs.md#documentattributevaluecountpairtypedef)\]

<a id="facettypedef"></a>

## FacetTypeDef

```python
from types_aiobotocore_kendra.type_defs import FacetTypeDef
```

Optional fields:

- `DocumentAttributeKey`: `str`

<a id="failedentitytypedef"></a>

## FailedEntityTypeDef

```python
from types_aiobotocore_kendra.type_defs import FailedEntityTypeDef
```

Optional fields:

- `EntityId`: `str`
- `ErrorMessage`: `str`

<a id="faqstatisticstypedef"></a>

## FaqStatisticsTypeDef

```python
from types_aiobotocore_kendra.type_defs import FaqStatisticsTypeDef
```

Required fields:

- `IndexedQuestionAnswersCount`: `int`

<a id="faqsummarytypedef"></a>

## FaqSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import FaqSummaryTypeDef
```

Optional fields:

- `Id`: `str`
- `Name`: `str`
- `Status`: [FaqStatusType](./literals.md#faqstatustype)
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `FileFormat`: [FaqFileFormatType](./literals.md#faqfileformattype)
- `LanguageCode`: `str`

<a id="getquerysuggestionsrequestrequesttypedef"></a>

## GetQuerySuggestionsRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import GetQuerySuggestionsRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `QueryText`: `str`

Optional fields:

- `MaxSuggestionsCount`: `int`

<a id="getquerysuggestionsresponsetypedef"></a>

## GetQuerySuggestionsResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import GetQuerySuggestionsResponseTypeDef
```

Required fields:

- `QuerySuggestionsId`: `str`
- `Suggestions`:
  `List`\[[SuggestionTypeDef](./type_defs.md#suggestiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsnapshotsrequestrequesttypedef"></a>

## GetSnapshotsRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import GetSnapshotsRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Interval`: [IntervalType](./literals.md#intervaltype)
- `MetricType`: [MetricTypeType](./literals.md#metrictypetype)

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="getsnapshotsresponsetypedef"></a>

## GetSnapshotsResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import GetSnapshotsResponseTypeDef
```

Required fields:

- `SnapShotTimeFilter`: [TimeRangeTypeDef](./type_defs.md#timerangetypedef)
- `SnapshotsDataHeader`: `List`\[`str`\]
- `SnapshotsData`: `List`\[`List`\[`str`\]\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="googledriveconfigurationtypedef"></a>

## GoogleDriveConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import GoogleDriveConfigurationTypeDef
```

Required fields:

- `SecretArn`: `str`

Optional fields:

- `InclusionPatterns`: `Sequence`\[`str`\]
- `ExclusionPatterns`: `Sequence`\[`str`\]
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]
- `ExcludeMimeTypes`: `Sequence`\[`str`\]
- `ExcludeUserAccounts`: `Sequence`\[`str`\]
- `ExcludeSharedDrives`: `Sequence`\[`str`\]

<a id="groupmemberstypedef"></a>

## GroupMembersTypeDef

```python
from types_aiobotocore_kendra.type_defs import GroupMembersTypeDef
```

Optional fields:

- `MemberGroups`:
  `Sequence`\[[MemberGroupTypeDef](./type_defs.md#membergrouptypedef)\]
- `MemberUsers`:
  `Sequence`\[[MemberUserTypeDef](./type_defs.md#memberusertypedef)\]
- `S3PathforGroupMembers`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)

<a id="grouporderingidsummarytypedef"></a>

## GroupOrderingIdSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import GroupOrderingIdSummaryTypeDef
```

Optional fields:

- `Status`:
  [PrincipalMappingStatusType](./literals.md#principalmappingstatustype)
- `LastUpdatedAt`: `datetime`
- `ReceivedAt`: `datetime`
- `OrderingId`: `int`
- `FailureReason`: `str`

<a id="groupsummarytypedef"></a>

## GroupSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import GroupSummaryTypeDef
```

Optional fields:

- `GroupId`: `str`
- `OrderingId`: `int`

<a id="hierarchicalprincipaltypedef"></a>

## HierarchicalPrincipalTypeDef

```python
from types_aiobotocore_kendra.type_defs import HierarchicalPrincipalTypeDef
```

Required fields:

- `PrincipalList`:
  `Sequence`\[[PrincipalTypeDef](./type_defs.md#principaltypedef)\]

<a id="highlighttypedef"></a>

## HighlightTypeDef

```python
from types_aiobotocore_kendra.type_defs import HighlightTypeDef
```

Required fields:

- `BeginOffset`: `int`
- `EndOffset`: `int`

Optional fields:

- `TopAnswer`: `bool`
- `Type`: [HighlightTypeType](./literals.md#highlighttypetype)

<a id="hookconfigurationtypedef"></a>

## HookConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import HookConfigurationTypeDef
```

Required fields:

- `LambdaArn`: `str`
- `S3Bucket`: `str`

Optional fields:

- `InvocationCondition`:
  [DocumentAttributeConditionTypeDef](./type_defs.md#documentattributeconditiontypedef)

<a id="indexconfigurationsummarytypedef"></a>

## IndexConfigurationSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import IndexConfigurationSummaryTypeDef
```

Required fields:

- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `Status`: [IndexStatusType](./literals.md#indexstatustype)

Optional fields:

- `Name`: `str`
- `Id`: `str`
- `Edition`: [IndexEditionType](./literals.md#indexeditiontype)

<a id="indexstatisticstypedef"></a>

## IndexStatisticsTypeDef

```python
from types_aiobotocore_kendra.type_defs import IndexStatisticsTypeDef
```

Required fields:

- `FaqStatistics`: [FaqStatisticsTypeDef](./type_defs.md#faqstatisticstypedef)
- `TextDocumentStatistics`:
  [TextDocumentStatisticsTypeDef](./type_defs.md#textdocumentstatisticstypedef)

<a id="inlinecustomdocumentenrichmentconfigurationtypedef"></a>

## InlineCustomDocumentEnrichmentConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import InlineCustomDocumentEnrichmentConfigurationTypeDef
```

Optional fields:

- `Condition`:
  [DocumentAttributeConditionTypeDef](./type_defs.md#documentattributeconditiontypedef)
- `Target`:
  [DocumentAttributeTargetTypeDef](./type_defs.md#documentattributetargettypedef)
- `DocumentContentDeletion`: `bool`

<a id="jsontokentypeconfigurationtypedef"></a>

## JsonTokenTypeConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import JsonTokenTypeConfigurationTypeDef
```

Required fields:

- `UserNameAttributeField`: `str`
- `GroupAttributeField`: `str`

<a id="jwttokentypeconfigurationtypedef"></a>

## JwtTokenTypeConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import JwtTokenTypeConfigurationTypeDef
```

Required fields:

- `KeyLocation`: [KeyLocationType](./literals.md#keylocationtype)

Optional fields:

- `URL`: `str`
- `SecretManagerArn`: `str`
- `UserNameAttributeField`: `str`
- `GroupAttributeField`: `str`
- `Issuer`: `str`
- `ClaimRegex`: `str`

<a id="listdatasourcesyncjobsrequestrequesttypedef"></a>

## ListDataSourceSyncJobsRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListDataSourceSyncJobsRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `StartTimeFilter`: [TimeRangeTypeDef](./type_defs.md#timerangetypedef)
- `StatusFilter`:
  [DataSourceSyncJobStatusType](./literals.md#datasourcesyncjobstatustype)

<a id="listdatasourcesyncjobsresponsetypedef"></a>

## ListDataSourceSyncJobsResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListDataSourceSyncJobsResponseTypeDef
```

Required fields:

- `History`:
  `List`\[[DataSourceSyncJobTypeDef](./type_defs.md#datasourcesyncjobtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdatasourcesrequestrequesttypedef"></a>

## ListDataSourcesRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListDataSourcesRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listdatasourcesresponsetypedef"></a>

## ListDataSourcesResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListDataSourcesResponseTypeDef
```

Required fields:

- `SummaryItems`:
  `List`\[[DataSourceSummaryTypeDef](./type_defs.md#datasourcesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listentitypersonasrequestrequesttypedef"></a>

## ListEntityPersonasRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListEntityPersonasRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listentitypersonasresponsetypedef"></a>

## ListEntityPersonasResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListEntityPersonasResponseTypeDef
```

Required fields:

- `SummaryItems`:
  `List`\[[PersonasSummaryTypeDef](./type_defs.md#personassummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listexperienceentitiesrequestrequesttypedef"></a>

## ListExperienceEntitiesRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListExperienceEntitiesRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`

<a id="listexperienceentitiesresponsetypedef"></a>

## ListExperienceEntitiesResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListExperienceEntitiesResponseTypeDef
```

Required fields:

- `SummaryItems`:
  `List`\[[ExperienceEntitiesSummaryTypeDef](./type_defs.md#experienceentitiessummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listexperiencesrequestrequesttypedef"></a>

## ListExperiencesRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListExperiencesRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listexperiencesresponsetypedef"></a>

## ListExperiencesResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListExperiencesResponseTypeDef
```

Required fields:

- `SummaryItems`:
  `List`\[[ExperiencesSummaryTypeDef](./type_defs.md#experiencessummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listfaqsrequestrequesttypedef"></a>

## ListFaqsRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListFaqsRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listfaqsresponsetypedef"></a>

## ListFaqsResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListFaqsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `FaqSummaryItems`:
  `List`\[[FaqSummaryTypeDef](./type_defs.md#faqsummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listgroupsolderthanorderingidrequestrequesttypedef"></a>

## ListGroupsOlderThanOrderingIdRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListGroupsOlderThanOrderingIdRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `OrderingId`: `int`

Optional fields:

- `DataSourceId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listgroupsolderthanorderingidresponsetypedef"></a>

## ListGroupsOlderThanOrderingIdResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListGroupsOlderThanOrderingIdResponseTypeDef
```

Required fields:

- `GroupsSummaries`:
  `List`\[[GroupSummaryTypeDef](./type_defs.md#groupsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listindicesrequestrequesttypedef"></a>

## ListIndicesRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListIndicesRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listindicesresponsetypedef"></a>

## ListIndicesResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListIndicesResponseTypeDef
```

Required fields:

- `IndexConfigurationSummaryItems`:
  `List`\[[IndexConfigurationSummaryTypeDef](./type_defs.md#indexconfigurationsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listquerysuggestionsblocklistsrequestrequesttypedef"></a>

## ListQuerySuggestionsBlockListsRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListQuerySuggestionsBlockListsRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listquerysuggestionsblocklistsresponsetypedef"></a>

## ListQuerySuggestionsBlockListsResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListQuerySuggestionsBlockListsResponseTypeDef
```

Required fields:

- `BlockListSummaryItems`:
  `List`\[[QuerySuggestionsBlockListSummaryTypeDef](./type_defs.md#querysuggestionsblocklistsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listthesaurirequestrequesttypedef"></a>

## ListThesauriRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListThesauriRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listthesauriresponsetypedef"></a>

## ListThesauriResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import ListThesauriResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `ThesaurusSummaryItems`:
  `List`\[[ThesaurusSummaryTypeDef](./type_defs.md#thesaurussummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="membergrouptypedef"></a>

## MemberGroupTypeDef

```python
from types_aiobotocore_kendra.type_defs import MemberGroupTypeDef
```

Required fields:

- `GroupId`: `str`

Optional fields:

- `DataSourceId`: `str`

<a id="memberusertypedef"></a>

## MemberUserTypeDef

```python
from types_aiobotocore_kendra.type_defs import MemberUserTypeDef
```

Required fields:

- `UserId`: `str`

<a id="onedriveconfigurationtypedef"></a>

## OneDriveConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import OneDriveConfigurationTypeDef
```

Required fields:

- `TenantDomain`: `str`
- `SecretArn`: `str`
- `OneDriveUsers`: [OneDriveUsersTypeDef](./type_defs.md#onedriveuserstypedef)

Optional fields:

- `InclusionPatterns`: `Sequence`\[`str`\]
- `ExclusionPatterns`: `Sequence`\[`str`\]
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]
- `DisableLocalGroups`: `bool`

<a id="onedriveuserstypedef"></a>

## OneDriveUsersTypeDef

```python
from types_aiobotocore_kendra.type_defs import OneDriveUsersTypeDef
```

Optional fields:

- `OneDriveUserList`: `Sequence`\[`str`\]
- `OneDriveUserS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)

<a id="personassummarytypedef"></a>

## PersonasSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import PersonasSummaryTypeDef
```

Optional fields:

- `EntityId`: `str`
- `Persona`: [PersonaType](./literals.md#personatype)
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`

<a id="principaltypedef"></a>

## PrincipalTypeDef

```python
from types_aiobotocore_kendra.type_defs import PrincipalTypeDef
```

Required fields:

- `Name`: `str`
- `Type`: [PrincipalTypeType](./literals.md#principaltypetype)
- `Access`: [ReadAccessTypeType](./literals.md#readaccesstypetype)

Optional fields:

- `DataSourceId`: `str`

<a id="proxyconfigurationtypedef"></a>

## ProxyConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ProxyConfigurationTypeDef
```

Required fields:

- `Host`: `str`
- `Port`: `int`

Optional fields:

- `Credentials`: `str`

<a id="putprincipalmappingrequestrequesttypedef"></a>

## PutPrincipalMappingRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import PutPrincipalMappingRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `GroupId`: `str`
- `GroupMembers`: [GroupMembersTypeDef](./type_defs.md#groupmemberstypedef)

Optional fields:

- `DataSourceId`: `str`
- `OrderingId`: `int`
- `RoleArn`: `str`

<a id="queryrequestrequesttypedef"></a>

## QueryRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import QueryRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `QueryText`: `str`

Optional fields:

- `AttributeFilter`:
  [AttributeFilterTypeDef](./type_defs.md#attributefiltertypedef)
- `Facets`: `Sequence`\[[FacetTypeDef](./type_defs.md#facettypedef)\]
- `RequestedDocumentAttributes`: `Sequence`\[`str`\]
- `QueryResultTypeFilter`:
  [QueryResultTypeType](./literals.md#queryresulttypetype)
- `DocumentRelevanceOverrideConfigurations`:
  `Sequence`\[[DocumentRelevanceConfigurationTypeDef](./type_defs.md#documentrelevanceconfigurationtypedef)\]
- `PageNumber`: `int`
- `PageSize`: `int`
- `SortingConfiguration`:
  [SortingConfigurationTypeDef](./type_defs.md#sortingconfigurationtypedef)
- `UserContext`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `VisitorId`: `str`

<a id="queryresultitemtypedef"></a>

## QueryResultItemTypeDef

```python
from types_aiobotocore_kendra.type_defs import QueryResultItemTypeDef
```

Optional fields:

- `Id`: `str`
- `Type`: [QueryResultTypeType](./literals.md#queryresulttypetype)
- `AdditionalAttributes`:
  `List`\[[AdditionalResultAttributeTypeDef](./type_defs.md#additionalresultattributetypedef)\]
- `DocumentId`: `str`
- `DocumentTitle`:
  [TextWithHighlightsTypeDef](./type_defs.md#textwithhighlightstypedef)
- `DocumentExcerpt`:
  [TextWithHighlightsTypeDef](./type_defs.md#textwithhighlightstypedef)
- `DocumentURI`: `str`
- `DocumentAttributes`:
  `List`\[[DocumentAttributeTypeDef](./type_defs.md#documentattributetypedef)\]
- `ScoreAttributes`:
  [ScoreAttributesTypeDef](./type_defs.md#scoreattributestypedef)
- `FeedbackToken`: `str`

<a id="queryresulttypedef"></a>

## QueryResultTypeDef

```python
from types_aiobotocore_kendra.type_defs import QueryResultTypeDef
```

Required fields:

- `QueryId`: `str`
- `ResultItems`:
  `List`\[[QueryResultItemTypeDef](./type_defs.md#queryresultitemtypedef)\]
- `FacetResults`:
  `List`\[[FacetResultTypeDef](./type_defs.md#facetresulttypedef)\]
- `TotalNumberOfResults`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="querysuggestionsblocklistsummarytypedef"></a>

## QuerySuggestionsBlockListSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import QuerySuggestionsBlockListSummaryTypeDef
```

Optional fields:

- `Id`: `str`
- `Name`: `str`
- `Status`:
  [QuerySuggestionsBlockListStatusType](./literals.md#querysuggestionsblockliststatustype)
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `ItemCount`: `int`

<a id="relevancefeedbacktypedef"></a>

## RelevanceFeedbackTypeDef

```python
from types_aiobotocore_kendra.type_defs import RelevanceFeedbackTypeDef
```

Required fields:

- `ResultId`: `str`
- `RelevanceValue`: [RelevanceTypeType](./literals.md#relevancetypetype)

<a id="relevancetypedef"></a>

## RelevanceTypeDef

```python
from types_aiobotocore_kendra.type_defs import RelevanceTypeDef
```

Optional fields:

- `Freshness`: `bool`
- `Importance`: `int`
- `Duration`: `str`
- `RankOrder`: [OrderType](./literals.md#ordertype)
- `ValueImportanceMap`: `Dict`\[`str`, `int`\]

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_kendra.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3datasourceconfigurationtypedef"></a>

## S3DataSourceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import S3DataSourceConfigurationTypeDef
```

Required fields:

- `BucketName`: `str`

Optional fields:

- `InclusionPrefixes`: `Sequence`\[`str`\]
- `InclusionPatterns`: `Sequence`\[`str`\]
- `ExclusionPatterns`: `Sequence`\[`str`\]
- `DocumentsMetadataConfiguration`:
  [DocumentsMetadataConfigurationTypeDef](./type_defs.md#documentsmetadataconfigurationtypedef)
- `AccessControlListConfiguration`:
  [AccessControlListConfigurationTypeDef](./type_defs.md#accesscontrollistconfigurationtypedef)

<a id="s3pathtypedef"></a>

## S3PathTypeDef

```python
from types_aiobotocore_kendra.type_defs import S3PathTypeDef
```

Required fields:

- `Bucket`: `str`
- `Key`: `str`

<a id="salesforcechatterfeedconfigurationtypedef"></a>

## SalesforceChatterFeedConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SalesforceChatterFeedConfigurationTypeDef
```

Required fields:

- `DocumentDataFieldName`: `str`

Optional fields:

- `DocumentTitleFieldName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]
- `IncludeFilterTypes`:
  `Sequence`\[[SalesforceChatterFeedIncludeFilterTypeType](./literals.md#salesforcechatterfeedincludefiltertypetype)\]

<a id="salesforceconfigurationtypedef"></a>

## SalesforceConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SalesforceConfigurationTypeDef
```

Required fields:

- `ServerUrl`: `str`
- `SecretArn`: `str`

Optional fields:

- `StandardObjectConfigurations`:
  `Sequence`\[[SalesforceStandardObjectConfigurationTypeDef](./type_defs.md#salesforcestandardobjectconfigurationtypedef)\]
- `KnowledgeArticleConfiguration`:
  [SalesforceKnowledgeArticleConfigurationTypeDef](./type_defs.md#salesforceknowledgearticleconfigurationtypedef)
- `ChatterFeedConfiguration`:
  [SalesforceChatterFeedConfigurationTypeDef](./type_defs.md#salesforcechatterfeedconfigurationtypedef)
- `CrawlAttachments`: `bool`
- `StandardObjectAttachmentConfiguration`:
  [SalesforceStandardObjectAttachmentConfigurationTypeDef](./type_defs.md#salesforcestandardobjectattachmentconfigurationtypedef)
- `IncludeAttachmentFilePatterns`: `Sequence`\[`str`\]
- `ExcludeAttachmentFilePatterns`: `Sequence`\[`str`\]

<a id="salesforcecustomknowledgearticletypeconfigurationtypedef"></a>

## SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef
```

Required fields:

- `Name`: `str`
- `DocumentDataFieldName`: `str`

Optional fields:

- `DocumentTitleFieldName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]

<a id="salesforceknowledgearticleconfigurationtypedef"></a>

## SalesforceKnowledgeArticleConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SalesforceKnowledgeArticleConfigurationTypeDef
```

Required fields:

- `IncludedStates`:
  `Sequence`\[[SalesforceKnowledgeArticleStateType](./literals.md#salesforceknowledgearticlestatetype)\]

Optional fields:

- `StandardKnowledgeArticleTypeConfiguration`:
  [SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef](./type_defs.md#salesforcestandardknowledgearticletypeconfigurationtypedef)
- `CustomKnowledgeArticleTypeConfigurations`:
  `Sequence`\[[SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef](./type_defs.md#salesforcecustomknowledgearticletypeconfigurationtypedef)\]

<a id="salesforcestandardknowledgearticletypeconfigurationtypedef"></a>

## SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef
```

Required fields:

- `DocumentDataFieldName`: `str`

Optional fields:

- `DocumentTitleFieldName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]

<a id="salesforcestandardobjectattachmentconfigurationtypedef"></a>

## SalesforceStandardObjectAttachmentConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SalesforceStandardObjectAttachmentConfigurationTypeDef
```

Optional fields:

- `DocumentTitleFieldName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]

<a id="salesforcestandardobjectconfigurationtypedef"></a>

## SalesforceStandardObjectConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SalesforceStandardObjectConfigurationTypeDef
```

Required fields:

- `Name`:
  [SalesforceStandardObjectNameType](./literals.md#salesforcestandardobjectnametype)
- `DocumentDataFieldName`: `str`

Optional fields:

- `DocumentTitleFieldName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]

<a id="scoreattributestypedef"></a>

## ScoreAttributesTypeDef

```python
from types_aiobotocore_kendra.type_defs import ScoreAttributesTypeDef
```

Optional fields:

- `ScoreConfidence`: [ScoreConfidenceType](./literals.md#scoreconfidencetype)

<a id="searchtypedef"></a>

## SearchTypeDef

```python
from types_aiobotocore_kendra.type_defs import SearchTypeDef
```

Optional fields:

- `Facetable`: `bool`
- `Searchable`: `bool`
- `Displayable`: `bool`
- `Sortable`: `bool`

<a id="seedurlconfigurationtypedef"></a>

## SeedUrlConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SeedUrlConfigurationTypeDef
```

Required fields:

- `SeedUrls`: `Sequence`\[`str`\]

Optional fields:

- `WebCrawlerMode`: [WebCrawlerModeType](./literals.md#webcrawlermodetype)

<a id="serversideencryptionconfigurationtypedef"></a>

## ServerSideEncryptionConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ServerSideEncryptionConfigurationTypeDef
```

Optional fields:

- `KmsKeyId`: `str`

<a id="servicenowconfigurationtypedef"></a>

## ServiceNowConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ServiceNowConfigurationTypeDef
```

Required fields:

- `HostUrl`: `str`
- `SecretArn`: `str`
- `ServiceNowBuildVersion`:
  [ServiceNowBuildVersionTypeType](./literals.md#servicenowbuildversiontypetype)

Optional fields:

- `KnowledgeArticleConfiguration`:
  [ServiceNowKnowledgeArticleConfigurationTypeDef](./type_defs.md#servicenowknowledgearticleconfigurationtypedef)
- `ServiceCatalogConfiguration`:
  [ServiceNowServiceCatalogConfigurationTypeDef](./type_defs.md#servicenowservicecatalogconfigurationtypedef)
- `AuthenticationType`:
  [ServiceNowAuthenticationTypeType](./literals.md#servicenowauthenticationtypetype)

<a id="servicenowknowledgearticleconfigurationtypedef"></a>

## ServiceNowKnowledgeArticleConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ServiceNowKnowledgeArticleConfigurationTypeDef
```

Required fields:

- `DocumentDataFieldName`: `str`

Optional fields:

- `CrawlAttachments`: `bool`
- `IncludeAttachmentFilePatterns`: `Sequence`\[`str`\]
- `ExcludeAttachmentFilePatterns`: `Sequence`\[`str`\]
- `DocumentTitleFieldName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]
- `FilterQuery`: `str`

<a id="servicenowservicecatalogconfigurationtypedef"></a>

## ServiceNowServiceCatalogConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import ServiceNowServiceCatalogConfigurationTypeDef
```

Required fields:

- `DocumentDataFieldName`: `str`

Optional fields:

- `CrawlAttachments`: `bool`
- `IncludeAttachmentFilePatterns`: `Sequence`\[`str`\]
- `ExcludeAttachmentFilePatterns`: `Sequence`\[`str`\]
- `DocumentTitleFieldName`: `str`
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]

<a id="sharepointconfigurationtypedef"></a>

## SharePointConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SharePointConfigurationTypeDef
```

Required fields:

- `SharePointVersion`:
  [SharePointVersionType](./literals.md#sharepointversiontype)
- `Urls`: `Sequence`\[`str`\]
- `SecretArn`: `str`

Optional fields:

- `CrawlAttachments`: `bool`
- `UseChangeLog`: `bool`
- `InclusionPatterns`: `Sequence`\[`str`\]
- `ExclusionPatterns`: `Sequence`\[`str`\]
- `VpcConfiguration`:
  [DataSourceVpcConfigurationTypeDef](./type_defs.md#datasourcevpcconfigurationtypedef)
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]
- `DocumentTitleFieldName`: `str`
- `DisableLocalGroups`: `bool`
- `SslCertificateS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)

<a id="sitemapsconfigurationtypedef"></a>

## SiteMapsConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SiteMapsConfigurationTypeDef
```

Required fields:

- `SiteMaps`: `Sequence`\[`str`\]

<a id="sortingconfigurationtypedef"></a>

## SortingConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SortingConfigurationTypeDef
```

Required fields:

- `DocumentAttributeKey`: `str`
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="sqlconfigurationtypedef"></a>

## SqlConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import SqlConfigurationTypeDef
```

Optional fields:

- `QueryIdentifiersEnclosingOption`:
  [QueryIdentifiersEnclosingOptionType](./literals.md#queryidentifiersenclosingoptiontype)

<a id="startdatasourcesyncjobrequestrequesttypedef"></a>

## StartDataSourceSyncJobRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import StartDataSourceSyncJobRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="startdatasourcesyncjobresponsetypedef"></a>

## StartDataSourceSyncJobResponseTypeDef

```python
from types_aiobotocore_kendra.type_defs import StartDataSourceSyncJobResponseTypeDef
```

Required fields:

- `ExecutionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="statustypedef"></a>

## StatusTypeDef

```python
from types_aiobotocore_kendra.type_defs import StatusTypeDef
```

Optional fields:

- `DocumentId`: `str`
- `DocumentStatus`: [DocumentStatusType](./literals.md#documentstatustype)
- `FailureCode`: `str`
- `FailureReason`: `str`

<a id="stopdatasourcesyncjobrequestrequesttypedef"></a>

## StopDataSourceSyncJobRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import StopDataSourceSyncJobRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

<a id="submitfeedbackrequestrequesttypedef"></a>

## SubmitFeedbackRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import SubmitFeedbackRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `QueryId`: `str`

Optional fields:

- `ClickFeedbackItems`:
  `Sequence`\[[ClickFeedbackTypeDef](./type_defs.md#clickfeedbacktypedef)\]
- `RelevanceFeedbackItems`:
  `Sequence`\[[RelevanceFeedbackTypeDef](./type_defs.md#relevancefeedbacktypedef)\]

<a id="suggestionhighlighttypedef"></a>

## SuggestionHighlightTypeDef

```python
from types_aiobotocore_kendra.type_defs import SuggestionHighlightTypeDef
```

Optional fields:

- `BeginOffset`: `int`
- `EndOffset`: `int`

<a id="suggestiontextwithhighlightstypedef"></a>

## SuggestionTextWithHighlightsTypeDef

```python
from types_aiobotocore_kendra.type_defs import SuggestionTextWithHighlightsTypeDef
```

Optional fields:

- `Text`: `str`
- `Highlights`:
  `List`\[[SuggestionHighlightTypeDef](./type_defs.md#suggestionhighlighttypedef)\]

<a id="suggestiontypedef"></a>

## SuggestionTypeDef

```python
from types_aiobotocore_kendra.type_defs import SuggestionTypeDef
```

Optional fields:

- `Id`: `str`
- `Value`: [SuggestionValueTypeDef](./type_defs.md#suggestionvaluetypedef)

<a id="suggestionvaluetypedef"></a>

## SuggestionValueTypeDef

```python
from types_aiobotocore_kendra.type_defs import SuggestionValueTypeDef
```

Optional fields:

- `Text`:
  [SuggestionTextWithHighlightsTypeDef](./type_defs.md#suggestiontextwithhighlightstypedef)

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_kendra.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="textdocumentstatisticstypedef"></a>

## TextDocumentStatisticsTypeDef

```python
from types_aiobotocore_kendra.type_defs import TextDocumentStatisticsTypeDef
```

Required fields:

- `IndexedTextDocumentsCount`: `int`
- `IndexedTextBytes`: `int`

<a id="textwithhighlightstypedef"></a>

## TextWithHighlightsTypeDef

```python
from types_aiobotocore_kendra.type_defs import TextWithHighlightsTypeDef
```

Optional fields:

- `Text`: `str`
- `Highlights`: `List`\[[HighlightTypeDef](./type_defs.md#highlighttypedef)\]

<a id="thesaurussummarytypedef"></a>

## ThesaurusSummaryTypeDef

```python
from types_aiobotocore_kendra.type_defs import ThesaurusSummaryTypeDef
```

Optional fields:

- `Id`: `str`
- `Name`: `str`
- `Status`: [ThesaurusStatusType](./literals.md#thesaurusstatustype)
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`

<a id="timerangetypedef"></a>

## TimeRangeTypeDef

```python
from types_aiobotocore_kendra.type_defs import TimeRangeTypeDef
```

Optional fields:

- `StartTime`: `datetime`
- `EndTime`: `datetime`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updatedatasourcerequestrequesttypedef"></a>

## UpdateDataSourceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import UpdateDataSourceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

Optional fields:

- `Name`: `str`
- `Configuration`:
  [DataSourceConfigurationTypeDef](./type_defs.md#datasourceconfigurationtypedef)
- `Description`: `str`
- `Schedule`: `str`
- `RoleArn`: `str`
- `LanguageCode`: `str`
- `CustomDocumentEnrichmentConfiguration`:
  [CustomDocumentEnrichmentConfigurationTypeDef](./type_defs.md#customdocumentenrichmentconfigurationtypedef)

<a id="updateexperiencerequestrequesttypedef"></a>

## UpdateExperienceRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import UpdateExperienceRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

Optional fields:

- `Name`: `str`
- `RoleArn`: `str`
- `Configuration`:
  [ExperienceConfigurationTypeDef](./type_defs.md#experienceconfigurationtypedef)
- `Description`: `str`

<a id="updateindexrequestrequesttypedef"></a>

## UpdateIndexRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import UpdateIndexRequestRequestTypeDef
```

Required fields:

- `Id`: `str`

Optional fields:

- `Name`: `str`
- `RoleArn`: `str`
- `Description`: `str`
- `DocumentMetadataConfigurationUpdates`:
  `Sequence`\[[DocumentMetadataConfigurationTypeDef](./type_defs.md#documentmetadataconfigurationtypedef)\]
- `CapacityUnits`:
  [CapacityUnitsConfigurationTypeDef](./type_defs.md#capacityunitsconfigurationtypedef)
- `UserTokenConfigurations`:
  `Sequence`\[[UserTokenConfigurationTypeDef](./type_defs.md#usertokenconfigurationtypedef)\]
- `UserContextPolicy`:
  [UserContextPolicyType](./literals.md#usercontextpolicytype)
- `UserGroupResolutionConfiguration`:
  [UserGroupResolutionConfigurationTypeDef](./type_defs.md#usergroupresolutionconfigurationtypedef)

<a id="updatequerysuggestionsblocklistrequestrequesttypedef"></a>

## UpdateQuerySuggestionsBlockListRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import UpdateQuerySuggestionsBlockListRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`
- `Id`: `str`

Optional fields:

- `Name`: `str`
- `Description`: `str`
- `SourceS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)
- `RoleArn`: `str`

<a id="updatequerysuggestionsconfigrequestrequesttypedef"></a>

## UpdateQuerySuggestionsConfigRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import UpdateQuerySuggestionsConfigRequestRequestTypeDef
```

Required fields:

- `IndexId`: `str`

Optional fields:

- `Mode`: [ModeType](./literals.md#modetype)
- `QueryLogLookBackWindowInDays`: `int`
- `IncludeQueriesWithoutUserInformation`: `bool`
- `MinimumNumberOfQueryingUsers`: `int`
- `MinimumQueryCount`: `int`

<a id="updatethesaurusrequestrequesttypedef"></a>

## UpdateThesaurusRequestRequestTypeDef

```python
from types_aiobotocore_kendra.type_defs import UpdateThesaurusRequestRequestTypeDef
```

Required fields:

- `Id`: `str`
- `IndexId`: `str`

Optional fields:

- `Name`: `str`
- `Description`: `str`
- `RoleArn`: `str`
- `SourceS3Path`: [S3PathTypeDef](./type_defs.md#s3pathtypedef)

<a id="urlstypedef"></a>

## UrlsTypeDef

```python
from types_aiobotocore_kendra.type_defs import UrlsTypeDef
```

Optional fields:

- `SeedUrlConfiguration`:
  [SeedUrlConfigurationTypeDef](./type_defs.md#seedurlconfigurationtypedef)
- `SiteMapsConfiguration`:
  [SiteMapsConfigurationTypeDef](./type_defs.md#sitemapsconfigurationtypedef)

<a id="usercontexttypedef"></a>

## UserContextTypeDef

```python
from types_aiobotocore_kendra.type_defs import UserContextTypeDef
```

Optional fields:

- `Token`: `str`
- `UserId`: `str`
- `Groups`: `Sequence`\[`str`\]
- `DataSourceGroups`:
  `Sequence`\[[DataSourceGroupTypeDef](./type_defs.md#datasourcegrouptypedef)\]

<a id="usergroupresolutionconfigurationtypedef"></a>

## UserGroupResolutionConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import UserGroupResolutionConfigurationTypeDef
```

Required fields:

- `UserGroupResolutionMode`:
  [UserGroupResolutionModeType](./literals.md#usergroupresolutionmodetype)

<a id="useridentityconfigurationtypedef"></a>

## UserIdentityConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import UserIdentityConfigurationTypeDef
```

Optional fields:

- `IdentityAttributeName`: `str`

<a id="usertokenconfigurationtypedef"></a>

## UserTokenConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import UserTokenConfigurationTypeDef
```

Optional fields:

- `JwtTokenTypeConfiguration`:
  [JwtTokenTypeConfigurationTypeDef](./type_defs.md#jwttokentypeconfigurationtypedef)
- `JsonTokenTypeConfiguration`:
  [JsonTokenTypeConfigurationTypeDef](./type_defs.md#jsontokentypeconfigurationtypedef)

<a id="webcrawlerconfigurationtypedef"></a>

## WebCrawlerConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import WebCrawlerConfigurationTypeDef
```

Required fields:

- `Urls`: [UrlsTypeDef](./type_defs.md#urlstypedef)

Optional fields:

- `CrawlDepth`: `int`
- `MaxLinksPerPage`: `int`
- `MaxContentSizePerPageInMegaBytes`: `float`
- `MaxUrlsPerMinuteCrawlRate`: `int`
- `UrlInclusionPatterns`: `Sequence`\[`str`\]
- `UrlExclusionPatterns`: `Sequence`\[`str`\]
- `ProxyConfiguration`:
  [ProxyConfigurationTypeDef](./type_defs.md#proxyconfigurationtypedef)
- `AuthenticationConfiguration`:
  [AuthenticationConfigurationTypeDef](./type_defs.md#authenticationconfigurationtypedef)

<a id="workdocsconfigurationtypedef"></a>

## WorkDocsConfigurationTypeDef

```python
from types_aiobotocore_kendra.type_defs import WorkDocsConfigurationTypeDef
```

Required fields:

- `OrganizationId`: `str`

Optional fields:

- `CrawlComments`: `bool`
- `UseChangeLog`: `bool`
- `InclusionPatterns`: `Sequence`\[`str`\]
- `ExclusionPatterns`: `Sequence`\[`str`\]
- `FieldMappings`:
  `Sequence`\[[DataSourceToIndexFieldMappingTypeDef](./type_defs.md#datasourcetoindexfieldmappingtypedef)\]
