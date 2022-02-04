<a id="typed-dictionaries-for-aiobotocore-macie2-module"></a>

# Typed dictionaries for aiobotocore Macie2 module

> [Index](..) > [Macie2](.) > Typed dictionaries

Auto-generated documentation for
[Macie2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
type annotations stubs module
[types-aiobotocore-macie2](https://pypi.org/project/types-aiobotocore-macie2/).

- [Typed dictionaries for aiobotocore Macie2 module](#typed-dictionaries-for-aiobotocore-macie2-module)
  - [AcceptInvitationRequestRequestTypeDef](#acceptinvitationrequestrequesttypedef)
  - [AccessControlListTypeDef](#accesscontrollisttypedef)
  - [AccountDetailTypeDef](#accountdetailtypedef)
  - [AccountLevelPermissionsTypeDef](#accountlevelpermissionstypedef)
  - [AdminAccountTypeDef](#adminaccounttypedef)
  - [ApiCallDetailsTypeDef](#apicalldetailstypedef)
  - [AssumedRoleTypeDef](#assumedroletypedef)
  - [AwsAccountTypeDef](#awsaccounttypedef)
  - [AwsServiceTypeDef](#awsservicetypedef)
  - [BatchGetCustomDataIdentifierSummaryTypeDef](#batchgetcustomdataidentifiersummarytypedef)
  - [BatchGetCustomDataIdentifiersRequestRequestTypeDef](#batchgetcustomdataidentifiersrequestrequesttypedef)
  - [BatchGetCustomDataIdentifiersResponseTypeDef](#batchgetcustomdataidentifiersresponsetypedef)
  - [BlockPublicAccessTypeDef](#blockpublicaccesstypedef)
  - [BucketCountByEffectivePermissionTypeDef](#bucketcountbyeffectivepermissiontypedef)
  - [BucketCountByEncryptionTypeTypeDef](#bucketcountbyencryptiontypetypedef)
  - [BucketCountBySharedAccessTypeTypeDef](#bucketcountbysharedaccesstypetypedef)
  - [BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef](#bucketcountpolicyallowsunencryptedobjectuploadstypedef)
  - [BucketCriteriaAdditionalPropertiesTypeDef](#bucketcriteriaadditionalpropertiestypedef)
  - [BucketLevelPermissionsTypeDef](#bucketlevelpermissionstypedef)
  - [BucketMetadataTypeDef](#bucketmetadatatypedef)
  - [BucketPermissionConfigurationTypeDef](#bucketpermissionconfigurationtypedef)
  - [BucketPolicyTypeDef](#bucketpolicytypedef)
  - [BucketPublicAccessTypeDef](#bucketpublicaccesstypedef)
  - [BucketServerSideEncryptionTypeDef](#bucketserversideencryptiontypedef)
  - [BucketSortCriteriaTypeDef](#bucketsortcriteriatypedef)
  - [CellTypeDef](#celltypedef)
  - [ClassificationDetailsTypeDef](#classificationdetailstypedef)
  - [ClassificationExportConfigurationTypeDef](#classificationexportconfigurationtypedef)
  - [ClassificationResultStatusTypeDef](#classificationresultstatustypedef)
  - [ClassificationResultTypeDef](#classificationresulttypedef)
  - [CreateClassificationJobRequestRequestTypeDef](#createclassificationjobrequestrequesttypedef)
  - [CreateClassificationJobResponseTypeDef](#createclassificationjobresponsetypedef)
  - [CreateCustomDataIdentifierRequestRequestTypeDef](#createcustomdataidentifierrequestrequesttypedef)
  - [CreateCustomDataIdentifierResponseTypeDef](#createcustomdataidentifierresponsetypedef)
  - [CreateFindingsFilterRequestRequestTypeDef](#createfindingsfilterrequestrequesttypedef)
  - [CreateFindingsFilterResponseTypeDef](#createfindingsfilterresponsetypedef)
  - [CreateInvitationsRequestRequestTypeDef](#createinvitationsrequestrequesttypedef)
  - [CreateInvitationsResponseTypeDef](#createinvitationsresponsetypedef)
  - [CreateMemberRequestRequestTypeDef](#creatememberrequestrequesttypedef)
  - [CreateMemberResponseTypeDef](#creatememberresponsetypedef)
  - [CreateSampleFindingsRequestRequestTypeDef](#createsamplefindingsrequestrequesttypedef)
  - [CriteriaBlockForJobTypeDef](#criteriablockforjobtypedef)
  - [CriteriaForJobTypeDef](#criteriaforjobtypedef)
  - [CriterionAdditionalPropertiesTypeDef](#criterionadditionalpropertiestypedef)
  - [CustomDataIdentifierSummaryTypeDef](#customdataidentifiersummarytypedef)
  - [CustomDataIdentifiersTypeDef](#customdataidentifierstypedef)
  - [CustomDetectionTypeDef](#customdetectiontypedef)
  - [DeclineInvitationsRequestRequestTypeDef](#declineinvitationsrequestrequesttypedef)
  - [DeclineInvitationsResponseTypeDef](#declineinvitationsresponsetypedef)
  - [DefaultDetectionTypeDef](#defaultdetectiontypedef)
  - [DeleteCustomDataIdentifierRequestRequestTypeDef](#deletecustomdataidentifierrequestrequesttypedef)
  - [DeleteFindingsFilterRequestRequestTypeDef](#deletefindingsfilterrequestrequesttypedef)
  - [DeleteInvitationsRequestRequestTypeDef](#deleteinvitationsrequestrequesttypedef)
  - [DeleteInvitationsResponseTypeDef](#deleteinvitationsresponsetypedef)
  - [DeleteMemberRequestRequestTypeDef](#deletememberrequestrequesttypedef)
  - [DescribeBucketsRequestRequestTypeDef](#describebucketsrequestrequesttypedef)
  - [DescribeBucketsResponseTypeDef](#describebucketsresponsetypedef)
  - [DescribeClassificationJobRequestRequestTypeDef](#describeclassificationjobrequestrequesttypedef)
  - [DescribeClassificationJobResponseTypeDef](#describeclassificationjobresponsetypedef)
  - [DescribeOrganizationConfigurationResponseTypeDef](#describeorganizationconfigurationresponsetypedef)
  - [DisableOrganizationAdminAccountRequestRequestTypeDef](#disableorganizationadminaccountrequestrequesttypedef)
  - [DisassociateMemberRequestRequestTypeDef](#disassociatememberrequestrequesttypedef)
  - [DomainDetailsTypeDef](#domaindetailstypedef)
  - [EnableMacieRequestRequestTypeDef](#enablemacierequestrequesttypedef)
  - [EnableOrganizationAdminAccountRequestRequestTypeDef](#enableorganizationadminaccountrequestrequesttypedef)
  - [FederatedUserTypeDef](#federatedusertypedef)
  - [FindingActionTypeDef](#findingactiontypedef)
  - [FindingActorTypeDef](#findingactortypedef)
  - [FindingCriteriaTypeDef](#findingcriteriatypedef)
  - [FindingStatisticsSortCriteriaTypeDef](#findingstatisticssortcriteriatypedef)
  - [FindingTypeDef](#findingtypedef)
  - [FindingsFilterListItemTypeDef](#findingsfilterlistitemtypedef)
  - [GetAdministratorAccountResponseTypeDef](#getadministratoraccountresponsetypedef)
  - [GetBucketStatisticsRequestRequestTypeDef](#getbucketstatisticsrequestrequesttypedef)
  - [GetBucketStatisticsResponseTypeDef](#getbucketstatisticsresponsetypedef)
  - [GetClassificationExportConfigurationResponseTypeDef](#getclassificationexportconfigurationresponsetypedef)
  - [GetCustomDataIdentifierRequestRequestTypeDef](#getcustomdataidentifierrequestrequesttypedef)
  - [GetCustomDataIdentifierResponseTypeDef](#getcustomdataidentifierresponsetypedef)
  - [GetFindingStatisticsRequestRequestTypeDef](#getfindingstatisticsrequestrequesttypedef)
  - [GetFindingStatisticsResponseTypeDef](#getfindingstatisticsresponsetypedef)
  - [GetFindingsFilterRequestRequestTypeDef](#getfindingsfilterrequestrequesttypedef)
  - [GetFindingsFilterResponseTypeDef](#getfindingsfilterresponsetypedef)
  - [GetFindingsPublicationConfigurationResponseTypeDef](#getfindingspublicationconfigurationresponsetypedef)
  - [GetFindingsRequestRequestTypeDef](#getfindingsrequestrequesttypedef)
  - [GetFindingsResponseTypeDef](#getfindingsresponsetypedef)
  - [GetInvitationsCountResponseTypeDef](#getinvitationscountresponsetypedef)
  - [GetMacieSessionResponseTypeDef](#getmaciesessionresponsetypedef)
  - [GetMasterAccountResponseTypeDef](#getmasteraccountresponsetypedef)
  - [GetMemberRequestRequestTypeDef](#getmemberrequestrequesttypedef)
  - [GetMemberResponseTypeDef](#getmemberresponsetypedef)
  - [GetUsageStatisticsRequestRequestTypeDef](#getusagestatisticsrequestrequesttypedef)
  - [GetUsageStatisticsResponseTypeDef](#getusagestatisticsresponsetypedef)
  - [GetUsageTotalsRequestRequestTypeDef](#getusagetotalsrequestrequesttypedef)
  - [GetUsageTotalsResponseTypeDef](#getusagetotalsresponsetypedef)
  - [GroupCountTypeDef](#groupcounttypedef)
  - [IamUserTypeDef](#iamusertypedef)
  - [InvitationTypeDef](#invitationtypedef)
  - [IpAddressDetailsTypeDef](#ipaddressdetailstypedef)
  - [IpCityTypeDef](#ipcitytypedef)
  - [IpCountryTypeDef](#ipcountrytypedef)
  - [IpGeoLocationTypeDef](#ipgeolocationtypedef)
  - [IpOwnerTypeDef](#ipownertypedef)
  - [JobDetailsTypeDef](#jobdetailstypedef)
  - [JobScheduleFrequencyTypeDef](#jobschedulefrequencytypedef)
  - [JobScopeTermTypeDef](#jobscopetermtypedef)
  - [JobScopingBlockTypeDef](#jobscopingblocktypedef)
  - [JobSummaryTypeDef](#jobsummarytypedef)
  - [KeyValuePairTypeDef](#keyvaluepairtypedef)
  - [LastRunErrorStatusTypeDef](#lastrunerrorstatustypedef)
  - [ListClassificationJobsRequestRequestTypeDef](#listclassificationjobsrequestrequesttypedef)
  - [ListClassificationJobsResponseTypeDef](#listclassificationjobsresponsetypedef)
  - [ListCustomDataIdentifiersRequestRequestTypeDef](#listcustomdataidentifiersrequestrequesttypedef)
  - [ListCustomDataIdentifiersResponseTypeDef](#listcustomdataidentifiersresponsetypedef)
  - [ListFindingsFiltersRequestRequestTypeDef](#listfindingsfiltersrequestrequesttypedef)
  - [ListFindingsFiltersResponseTypeDef](#listfindingsfiltersresponsetypedef)
  - [ListFindingsRequestRequestTypeDef](#listfindingsrequestrequesttypedef)
  - [ListFindingsResponseTypeDef](#listfindingsresponsetypedef)
  - [ListInvitationsRequestRequestTypeDef](#listinvitationsrequestrequesttypedef)
  - [ListInvitationsResponseTypeDef](#listinvitationsresponsetypedef)
  - [ListJobsFilterCriteriaTypeDef](#listjobsfiltercriteriatypedef)
  - [ListJobsFilterTermTypeDef](#listjobsfiltertermtypedef)
  - [ListJobsSortCriteriaTypeDef](#listjobssortcriteriatypedef)
  - [ListManagedDataIdentifiersRequestRequestTypeDef](#listmanageddataidentifiersrequestrequesttypedef)
  - [ListManagedDataIdentifiersResponseTypeDef](#listmanageddataidentifiersresponsetypedef)
  - [ListMembersRequestRequestTypeDef](#listmembersrequestrequesttypedef)
  - [ListMembersResponseTypeDef](#listmembersresponsetypedef)
  - [ListOrganizationAdminAccountsRequestRequestTypeDef](#listorganizationadminaccountsrequestrequesttypedef)
  - [ListOrganizationAdminAccountsResponseTypeDef](#listorganizationadminaccountsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [ManagedDataIdentifierSummaryTypeDef](#manageddataidentifiersummarytypedef)
  - [MatchingBucketTypeDef](#matchingbuckettypedef)
  - [MatchingResourceTypeDef](#matchingresourcetypedef)
  - [MemberTypeDef](#membertypedef)
  - [MonthlyScheduleTypeDef](#monthlyscheduletypedef)
  - [ObjectCountByEncryptionTypeTypeDef](#objectcountbyencryptiontypetypedef)
  - [ObjectLevelStatisticsTypeDef](#objectlevelstatisticstypedef)
  - [OccurrencesTypeDef](#occurrencestypedef)
  - [PageTypeDef](#pagetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PolicyDetailsTypeDef](#policydetailstypedef)
  - [PutClassificationExportConfigurationRequestRequestTypeDef](#putclassificationexportconfigurationrequestrequesttypedef)
  - [PutClassificationExportConfigurationResponseTypeDef](#putclassificationexportconfigurationresponsetypedef)
  - [PutFindingsPublicationConfigurationRequestRequestTypeDef](#putfindingspublicationconfigurationrequestrequesttypedef)
  - [RangeTypeDef](#rangetypedef)
  - [RecordTypeDef](#recordtypedef)
  - [ReplicationDetailsTypeDef](#replicationdetailstypedef)
  - [ResourcesAffectedTypeDef](#resourcesaffectedtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3BucketCriteriaForJobTypeDef](#s3bucketcriteriaforjobtypedef)
  - [S3BucketDefinitionForJobTypeDef](#s3bucketdefinitionforjobtypedef)
  - [S3BucketOwnerTypeDef](#s3bucketownertypedef)
  - [S3BucketTypeDef](#s3buckettypedef)
  - [S3DestinationTypeDef](#s3destinationtypedef)
  - [S3JobDefinitionTypeDef](#s3jobdefinitiontypedef)
  - [S3ObjectTypeDef](#s3objecttypedef)
  - [ScopingTypeDef](#scopingtypedef)
  - [SearchResourcesBucketCriteriaTypeDef](#searchresourcesbucketcriteriatypedef)
  - [SearchResourcesCriteriaBlockTypeDef](#searchresourcescriteriablocktypedef)
  - [SearchResourcesCriteriaTypeDef](#searchresourcescriteriatypedef)
  - [SearchResourcesRequestRequestTypeDef](#searchresourcesrequestrequesttypedef)
  - [SearchResourcesResponseTypeDef](#searchresourcesresponsetypedef)
  - [SearchResourcesSimpleCriterionTypeDef](#searchresourcessimplecriteriontypedef)
  - [SearchResourcesSortCriteriaTypeDef](#searchresourcessortcriteriatypedef)
  - [SearchResourcesTagCriterionPairTypeDef](#searchresourcestagcriterionpairtypedef)
  - [SearchResourcesTagCriterionTypeDef](#searchresourcestagcriteriontypedef)
  - [SecurityHubConfigurationTypeDef](#securityhubconfigurationtypedef)
  - [SensitiveDataItemTypeDef](#sensitivedataitemtypedef)
  - [ServerSideEncryptionTypeDef](#serversideencryptiontypedef)
  - [ServiceLimitTypeDef](#servicelimittypedef)
  - [SessionContextAttributesTypeDef](#sessioncontextattributestypedef)
  - [SessionContextTypeDef](#sessioncontexttypedef)
  - [SessionIssuerTypeDef](#sessionissuertypedef)
  - [SeverityLevelTypeDef](#severityleveltypedef)
  - [SeverityTypeDef](#severitytypedef)
  - [SimpleCriterionForJobTypeDef](#simplecriterionforjobtypedef)
  - [SimpleScopeTermTypeDef](#simplescopetermtypedef)
  - [SortCriteriaTypeDef](#sortcriteriatypedef)
  - [StatisticsTypeDef](#statisticstypedef)
  - [TagCriterionForJobTypeDef](#tagcriterionforjobtypedef)
  - [TagCriterionPairForJobTypeDef](#tagcriterionpairforjobtypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagScopeTermTypeDef](#tagscopetermtypedef)
  - [TagValuePairTypeDef](#tagvaluepairtypedef)
  - [TestCustomDataIdentifierRequestRequestTypeDef](#testcustomdataidentifierrequestrequesttypedef)
  - [TestCustomDataIdentifierResponseTypeDef](#testcustomdataidentifierresponsetypedef)
  - [UnprocessedAccountTypeDef](#unprocessedaccounttypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateClassificationJobRequestRequestTypeDef](#updateclassificationjobrequestrequesttypedef)
  - [UpdateFindingsFilterRequestRequestTypeDef](#updatefindingsfilterrequestrequesttypedef)
  - [UpdateFindingsFilterResponseTypeDef](#updatefindingsfilterresponsetypedef)
  - [UpdateMacieSessionRequestRequestTypeDef](#updatemaciesessionrequestrequesttypedef)
  - [UpdateMemberSessionRequestRequestTypeDef](#updatemembersessionrequestrequesttypedef)
  - [UpdateOrganizationConfigurationRequestRequestTypeDef](#updateorganizationconfigurationrequestrequesttypedef)
  - [UsageByAccountTypeDef](#usagebyaccounttypedef)
  - [UsageRecordTypeDef](#usagerecordtypedef)
  - [UsageStatisticsFilterTypeDef](#usagestatisticsfiltertypedef)
  - [UsageStatisticsSortByTypeDef](#usagestatisticssortbytypedef)
  - [UsageTotalTypeDef](#usagetotaltypedef)
  - [UserIdentityRootTypeDef](#useridentityroottypedef)
  - [UserIdentityTypeDef](#useridentitytypedef)
  - [UserPausedDetailsTypeDef](#userpauseddetailstypedef)
  - [WeeklyScheduleTypeDef](#weeklyscheduletypedef)

<a id="acceptinvitationrequestrequesttypedef"></a>

## AcceptInvitationRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import AcceptInvitationRequestRequestTypeDef
```

Required fields:

- `invitationId`: `str`

Optional fields:

- `administratorAccountId`: `str`
- `masterAccount`: `str`

<a id="accesscontrollisttypedef"></a>

## AccessControlListTypeDef

```python
from types_aiobotocore_macie2.type_defs import AccessControlListTypeDef
```

Optional fields:

- `allowsPublicReadAccess`: `bool`
- `allowsPublicWriteAccess`: `bool`

<a id="accountdetailtypedef"></a>

## AccountDetailTypeDef

```python
from types_aiobotocore_macie2.type_defs import AccountDetailTypeDef
```

Required fields:

- `accountId`: `str`
- `email`: `str`

<a id="accountlevelpermissionstypedef"></a>

## AccountLevelPermissionsTypeDef

```python
from types_aiobotocore_macie2.type_defs import AccountLevelPermissionsTypeDef
```

Optional fields:

- `blockPublicAccess`:
  [BlockPublicAccessTypeDef](./type_defs.md#blockpublicaccesstypedef)

<a id="adminaccounttypedef"></a>

## AdminAccountTypeDef

```python
from types_aiobotocore_macie2.type_defs import AdminAccountTypeDef
```

Optional fields:

- `accountId`: `str`
- `status`: [AdminStatusType](./literals.md#adminstatustype)

<a id="apicalldetailstypedef"></a>

## ApiCallDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import ApiCallDetailsTypeDef
```

Optional fields:

- `api`: `str`
- `apiServiceName`: `str`
- `firstSeen`: `datetime`
- `lastSeen`: `datetime`

<a id="assumedroletypedef"></a>

## AssumedRoleTypeDef

```python
from types_aiobotocore_macie2.type_defs import AssumedRoleTypeDef
```

Optional fields:

- `accessKeyId`: `str`
- `accountId`: `str`
- `arn`: `str`
- `principalId`: `str`
- `sessionContext`:
  [SessionContextTypeDef](./type_defs.md#sessioncontexttypedef)

<a id="awsaccounttypedef"></a>

## AwsAccountTypeDef

```python
from types_aiobotocore_macie2.type_defs import AwsAccountTypeDef
```

Optional fields:

- `accountId`: `str`
- `principalId`: `str`

<a id="awsservicetypedef"></a>

## AwsServiceTypeDef

```python
from types_aiobotocore_macie2.type_defs import AwsServiceTypeDef
```

Optional fields:

- `invokedBy`: `str`

<a id="batchgetcustomdataidentifiersummarytypedef"></a>

## BatchGetCustomDataIdentifierSummaryTypeDef

```python
from types_aiobotocore_macie2.type_defs import BatchGetCustomDataIdentifierSummaryTypeDef
```

Optional fields:

- `arn`: `str`
- `createdAt`: `datetime`
- `deleted`: `bool`
- `description`: `str`
- `id`: `str`
- `name`: `str`

<a id="batchgetcustomdataidentifiersrequestrequesttypedef"></a>

## BatchGetCustomDataIdentifiersRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import BatchGetCustomDataIdentifiersRequestRequestTypeDef
```

Optional fields:

- `ids`: `Sequence`\[`str`\]

<a id="batchgetcustomdataidentifiersresponsetypedef"></a>

## BatchGetCustomDataIdentifiersResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import BatchGetCustomDataIdentifiersResponseTypeDef
```

Required fields:

- `customDataIdentifiers`:
  `List`\[[BatchGetCustomDataIdentifierSummaryTypeDef](./type_defs.md#batchgetcustomdataidentifiersummarytypedef)\]
- `notFoundIdentifierIds`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="blockpublicaccesstypedef"></a>

## BlockPublicAccessTypeDef

```python
from types_aiobotocore_macie2.type_defs import BlockPublicAccessTypeDef
```

Optional fields:

- `blockPublicAcls`: `bool`
- `blockPublicPolicy`: `bool`
- `ignorePublicAcls`: `bool`
- `restrictPublicBuckets`: `bool`

<a id="bucketcountbyeffectivepermissiontypedef"></a>

## BucketCountByEffectivePermissionTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketCountByEffectivePermissionTypeDef
```

Optional fields:

- `publiclyAccessible`: `int`
- `publiclyReadable`: `int`
- `publiclyWritable`: `int`
- `unknown`: `int`

<a id="bucketcountbyencryptiontypetypedef"></a>

## BucketCountByEncryptionTypeTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketCountByEncryptionTypeTypeDef
```

Optional fields:

- `kmsManaged`: `int`
- `s3Managed`: `int`
- `unencrypted`: `int`
- `unknown`: `int`

<a id="bucketcountbysharedaccesstypetypedef"></a>

## BucketCountBySharedAccessTypeTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketCountBySharedAccessTypeTypeDef
```

Optional fields:

- `external`: `int`
- `internal`: `int`
- `notShared`: `int`
- `unknown`: `int`

<a id="bucketcountpolicyallowsunencryptedobjectuploadstypedef"></a>

## BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef
```

Optional fields:

- `allowsUnencryptedObjectUploads`: `int`
- `deniesUnencryptedObjectUploads`: `int`
- `unknown`: `int`

<a id="bucketcriteriaadditionalpropertiestypedef"></a>

## BucketCriteriaAdditionalPropertiesTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketCriteriaAdditionalPropertiesTypeDef
```

Optional fields:

- `eq`: `Sequence`\[`str`\]
- `gt`: `int`
- `gte`: `int`
- `lt`: `int`
- `lte`: `int`
- `neq`: `Sequence`\[`str`\]
- `prefix`: `str`

<a id="bucketlevelpermissionstypedef"></a>

## BucketLevelPermissionsTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketLevelPermissionsTypeDef
```

Optional fields:

- `accessControlList`:
  [AccessControlListTypeDef](./type_defs.md#accesscontrollisttypedef)
- `blockPublicAccess`:
  [BlockPublicAccessTypeDef](./type_defs.md#blockpublicaccesstypedef)
- `bucketPolicy`: [BucketPolicyTypeDef](./type_defs.md#bucketpolicytypedef)

<a id="bucketmetadatatypedef"></a>

## BucketMetadataTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketMetadataTypeDef
```

Optional fields:

- `accountId`: `str`
- `allowsUnencryptedObjectUploads`:
  [AllowsUnencryptedObjectUploadsType](./literals.md#allowsunencryptedobjectuploadstype)
- `bucketArn`: `str`
- `bucketCreatedAt`: `datetime`
- `bucketName`: `str`
- `classifiableObjectCount`: `int`
- `classifiableSizeInBytes`: `int`
- `errorCode`: `Literal['ACCESS_DENIED']` (see
  [BucketMetadataErrorCodeType](./literals.md#bucketmetadataerrorcodetype))
- `errorMessage`: `str`
- `jobDetails`: [JobDetailsTypeDef](./type_defs.md#jobdetailstypedef)
- `lastUpdated`: `datetime`
- `objectCount`: `int`
- `objectCountByEncryptionType`:
  [ObjectCountByEncryptionTypeTypeDef](./type_defs.md#objectcountbyencryptiontypetypedef)
- `publicAccess`:
  [BucketPublicAccessTypeDef](./type_defs.md#bucketpublicaccesstypedef)
- `region`: `str`
- `replicationDetails`:
  [ReplicationDetailsTypeDef](./type_defs.md#replicationdetailstypedef)
- `serverSideEncryption`:
  [BucketServerSideEncryptionTypeDef](./type_defs.md#bucketserversideencryptiontypedef)
- `sharedAccess`: [SharedAccessType](./literals.md#sharedaccesstype)
- `sizeInBytes`: `int`
- `sizeInBytesCompressed`: `int`
- `tags`: `List`\[[KeyValuePairTypeDef](./type_defs.md#keyvaluepairtypedef)\]
- `unclassifiableObjectCount`:
  [ObjectLevelStatisticsTypeDef](./type_defs.md#objectlevelstatisticstypedef)
- `unclassifiableObjectSizeInBytes`:
  [ObjectLevelStatisticsTypeDef](./type_defs.md#objectlevelstatisticstypedef)
- `versioning`: `bool`

<a id="bucketpermissionconfigurationtypedef"></a>

## BucketPermissionConfigurationTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketPermissionConfigurationTypeDef
```

Optional fields:

- `accountLevelPermissions`:
  [AccountLevelPermissionsTypeDef](./type_defs.md#accountlevelpermissionstypedef)
- `bucketLevelPermissions`:
  [BucketLevelPermissionsTypeDef](./type_defs.md#bucketlevelpermissionstypedef)

<a id="bucketpolicytypedef"></a>

## BucketPolicyTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketPolicyTypeDef
```

Optional fields:

- `allowsPublicReadAccess`: `bool`
- `allowsPublicWriteAccess`: `bool`

<a id="bucketpublicaccesstypedef"></a>

## BucketPublicAccessTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketPublicAccessTypeDef
```

Optional fields:

- `effectivePermission`:
  [EffectivePermissionType](./literals.md#effectivepermissiontype)
- `permissionConfiguration`:
  [BucketPermissionConfigurationTypeDef](./type_defs.md#bucketpermissionconfigurationtypedef)

<a id="bucketserversideencryptiontypedef"></a>

## BucketServerSideEncryptionTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketServerSideEncryptionTypeDef
```

Optional fields:

- `kmsMasterKeyId`: `str`
- `type`: [TypeType](./literals.md#typetype)

<a id="bucketsortcriteriatypedef"></a>

## BucketSortCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import BucketSortCriteriaTypeDef
```

Optional fields:

- `attributeName`: `str`
- `orderBy`: [OrderByType](./literals.md#orderbytype)

<a id="celltypedef"></a>

## CellTypeDef

```python
from types_aiobotocore_macie2.type_defs import CellTypeDef
```

Optional fields:

- `cellReference`: `str`
- `column`: `int`
- `columnName`: `str`
- `row`: `int`

<a id="classificationdetailstypedef"></a>

## ClassificationDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import ClassificationDetailsTypeDef
```

Optional fields:

- `detailedResultsLocation`: `str`
- `jobArn`: `str`
- `jobId`: `str`
- `result`:
  [ClassificationResultTypeDef](./type_defs.md#classificationresulttypedef)

<a id="classificationexportconfigurationtypedef"></a>

## ClassificationExportConfigurationTypeDef

```python
from types_aiobotocore_macie2.type_defs import ClassificationExportConfigurationTypeDef
```

Optional fields:

- `s3Destination`: [S3DestinationTypeDef](./type_defs.md#s3destinationtypedef)

<a id="classificationresultstatustypedef"></a>

## ClassificationResultStatusTypeDef

```python
from types_aiobotocore_macie2.type_defs import ClassificationResultStatusTypeDef
```

Optional fields:

- `code`: `str`
- `reason`: `str`

<a id="classificationresulttypedef"></a>

## ClassificationResultTypeDef

```python
from types_aiobotocore_macie2.type_defs import ClassificationResultTypeDef
```

Optional fields:

- `additionalOccurrences`: `bool`
- `customDataIdentifiers`:
  [CustomDataIdentifiersTypeDef](./type_defs.md#customdataidentifierstypedef)
- `mimeType`: `str`
- `sensitiveData`:
  `List`\[[SensitiveDataItemTypeDef](./type_defs.md#sensitivedataitemtypedef)\]
- `sizeClassified`: `int`
- `status`:
  [ClassificationResultStatusTypeDef](./type_defs.md#classificationresultstatustypedef)

<a id="createclassificationjobrequestrequesttypedef"></a>

## CreateClassificationJobRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateClassificationJobRequestRequestTypeDef
```

Required fields:

- `clientToken`: `str`
- `jobType`: [JobTypeType](./literals.md#jobtypetype)
- `name`: `str`
- `s3JobDefinition`:
  [S3JobDefinitionTypeDef](./type_defs.md#s3jobdefinitiontypedef)

Optional fields:

- `customDataIdentifierIds`: `Sequence`\[`str`\]
- `description`: `str`
- `initialRun`: `bool`
- `managedDataIdentifierIds`: `Sequence`\[`str`\]
- `managedDataIdentifierSelector`:
  [ManagedDataIdentifierSelectorType](./literals.md#manageddataidentifierselectortype)
- `samplingPercentage`: `int`
- `scheduleFrequency`:
  [JobScheduleFrequencyTypeDef](./type_defs.md#jobschedulefrequencytypedef)
- `tags`: `Mapping`\[`str`, `str`\]

<a id="createclassificationjobresponsetypedef"></a>

## CreateClassificationJobResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateClassificationJobResponseTypeDef
```

Required fields:

- `jobArn`: `str`
- `jobId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createcustomdataidentifierrequestrequesttypedef"></a>

## CreateCustomDataIdentifierRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateCustomDataIdentifierRequestRequestTypeDef
```

Optional fields:

- `clientToken`: `str`
- `description`: `str`
- `ignoreWords`: `Sequence`\[`str`\]
- `keywords`: `Sequence`\[`str`\]
- `maximumMatchDistance`: `int`
- `name`: `str`
- `regex`: `str`
- `severityLevels`:
  `Sequence`\[[SeverityLevelTypeDef](./type_defs.md#severityleveltypedef)\]
- `tags`: `Mapping`\[`str`, `str`\]

<a id="createcustomdataidentifierresponsetypedef"></a>

## CreateCustomDataIdentifierResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateCustomDataIdentifierResponseTypeDef
```

Required fields:

- `customDataIdentifierId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createfindingsfilterrequestrequesttypedef"></a>

## CreateFindingsFilterRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateFindingsFilterRequestRequestTypeDef
```

Required fields:

- `action`: [FindingsFilterActionType](./literals.md#findingsfilteractiontype)
- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `name`: `str`

Optional fields:

- `clientToken`: `str`
- `description`: `str`
- `position`: `int`
- `tags`: `Mapping`\[`str`, `str`\]

<a id="createfindingsfilterresponsetypedef"></a>

## CreateFindingsFilterResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateFindingsFilterResponseTypeDef
```

Required fields:

- `arn`: `str`
- `id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createinvitationsrequestrequesttypedef"></a>

## CreateInvitationsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateInvitationsRequestRequestTypeDef
```

Required fields:

- `accountIds`: `Sequence`\[`str`\]

Optional fields:

- `disableEmailNotification`: `bool`
- `message`: `str`

<a id="createinvitationsresponsetypedef"></a>

## CreateInvitationsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateInvitationsResponseTypeDef
```

Required fields:

- `unprocessedAccounts`:
  `List`\[[UnprocessedAccountTypeDef](./type_defs.md#unprocessedaccounttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="creatememberrequestrequesttypedef"></a>

## CreateMemberRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateMemberRequestRequestTypeDef
```

Required fields:

- `account`: [AccountDetailTypeDef](./type_defs.md#accountdetailtypedef)

Optional fields:

- `tags`: `Mapping`\[`str`, `str`\]

<a id="creatememberresponsetypedef"></a>

## CreateMemberResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateMemberResponseTypeDef
```

Required fields:

- `arn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createsamplefindingsrequestrequesttypedef"></a>

## CreateSampleFindingsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import CreateSampleFindingsRequestRequestTypeDef
```

Optional fields:

- `findingTypes`:
  `Sequence`\[[FindingTypeType](./literals.md#findingtypetype)\]

<a id="criteriablockforjobtypedef"></a>

## CriteriaBlockForJobTypeDef

```python
from types_aiobotocore_macie2.type_defs import CriteriaBlockForJobTypeDef
```

Optional fields:

- `and`:
  `Sequence`\[[CriteriaForJobTypeDef](./type_defs.md#criteriaforjobtypedef)\]

<a id="criteriaforjobtypedef"></a>

## CriteriaForJobTypeDef

```python
from types_aiobotocore_macie2.type_defs import CriteriaForJobTypeDef
```

Optional fields:

- `simpleCriterion`:
  [SimpleCriterionForJobTypeDef](./type_defs.md#simplecriterionforjobtypedef)
- `tagCriterion`:
  [TagCriterionForJobTypeDef](./type_defs.md#tagcriterionforjobtypedef)

<a id="criterionadditionalpropertiestypedef"></a>

## CriterionAdditionalPropertiesTypeDef

```python
from types_aiobotocore_macie2.type_defs import CriterionAdditionalPropertiesTypeDef
```

Optional fields:

- `eq`: `Sequence`\[`str`\]
- `eqExactMatch`: `Sequence`\[`str`\]
- `gt`: `int`
- `gte`: `int`
- `lt`: `int`
- `lte`: `int`
- `neq`: `Sequence`\[`str`\]

<a id="customdataidentifiersummarytypedef"></a>

## CustomDataIdentifierSummaryTypeDef

```python
from types_aiobotocore_macie2.type_defs import CustomDataIdentifierSummaryTypeDef
```

Optional fields:

- `arn`: `str`
- `createdAt`: `datetime`
- `description`: `str`
- `id`: `str`
- `name`: `str`

<a id="customdataidentifierstypedef"></a>

## CustomDataIdentifiersTypeDef

```python
from types_aiobotocore_macie2.type_defs import CustomDataIdentifiersTypeDef
```

Optional fields:

- `detections`:
  `List`\[[CustomDetectionTypeDef](./type_defs.md#customdetectiontypedef)\]
- `totalCount`: `int`

<a id="customdetectiontypedef"></a>

## CustomDetectionTypeDef

```python
from types_aiobotocore_macie2.type_defs import CustomDetectionTypeDef
```

Optional fields:

- `arn`: `str`
- `count`: `int`
- `name`: `str`
- `occurrences`: [OccurrencesTypeDef](./type_defs.md#occurrencestypedef)

<a id="declineinvitationsrequestrequesttypedef"></a>

## DeclineInvitationsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DeclineInvitationsRequestRequestTypeDef
```

Required fields:

- `accountIds`: `Sequence`\[`str`\]

<a id="declineinvitationsresponsetypedef"></a>

## DeclineInvitationsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import DeclineInvitationsResponseTypeDef
```

Required fields:

- `unprocessedAccounts`:
  `List`\[[UnprocessedAccountTypeDef](./type_defs.md#unprocessedaccounttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="defaultdetectiontypedef"></a>

## DefaultDetectionTypeDef

```python
from types_aiobotocore_macie2.type_defs import DefaultDetectionTypeDef
```

Optional fields:

- `count`: `int`
- `occurrences`: [OccurrencesTypeDef](./type_defs.md#occurrencestypedef)
- `type`: `str`

<a id="deletecustomdataidentifierrequestrequesttypedef"></a>

## DeleteCustomDataIdentifierRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DeleteCustomDataIdentifierRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="deletefindingsfilterrequestrequesttypedef"></a>

## DeleteFindingsFilterRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DeleteFindingsFilterRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="deleteinvitationsrequestrequesttypedef"></a>

## DeleteInvitationsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DeleteInvitationsRequestRequestTypeDef
```

Required fields:

- `accountIds`: `Sequence`\[`str`\]

<a id="deleteinvitationsresponsetypedef"></a>

## DeleteInvitationsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import DeleteInvitationsResponseTypeDef
```

Required fields:

- `unprocessedAccounts`:
  `List`\[[UnprocessedAccountTypeDef](./type_defs.md#unprocessedaccounttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletememberrequestrequesttypedef"></a>

## DeleteMemberRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DeleteMemberRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="describebucketsrequestrequesttypedef"></a>

## DescribeBucketsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DescribeBucketsRequestRequestTypeDef
```

Optional fields:

- `criteria`: `Mapping`\[`str`,
  [BucketCriteriaAdditionalPropertiesTypeDef](./type_defs.md#bucketcriteriaadditionalpropertiestypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`:
  [BucketSortCriteriaTypeDef](./type_defs.md#bucketsortcriteriatypedef)

<a id="describebucketsresponsetypedef"></a>

## DescribeBucketsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import DescribeBucketsResponseTypeDef
```

Required fields:

- `buckets`:
  `List`\[[BucketMetadataTypeDef](./type_defs.md#bucketmetadatatypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeclassificationjobrequestrequesttypedef"></a>

## DescribeClassificationJobRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DescribeClassificationJobRequestRequestTypeDef
```

Required fields:

- `jobId`: `str`

<a id="describeclassificationjobresponsetypedef"></a>

## DescribeClassificationJobResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import DescribeClassificationJobResponseTypeDef
```

Required fields:

- `clientToken`: `str`
- `createdAt`: `datetime`
- `customDataIdentifierIds`: `List`\[`str`\]
- `description`: `str`
- `initialRun`: `bool`
- `jobArn`: `str`
- `jobId`: `str`
- `jobStatus`: [JobStatusType](./literals.md#jobstatustype)
- `jobType`: [JobTypeType](./literals.md#jobtypetype)
- `lastRunErrorStatus`:
  [LastRunErrorStatusTypeDef](./type_defs.md#lastrunerrorstatustypedef)
- `lastRunTime`: `datetime`
- `managedDataIdentifierIds`: `List`\[`str`\]
- `managedDataIdentifierSelector`:
  [ManagedDataIdentifierSelectorType](./literals.md#manageddataidentifierselectortype)
- `name`: `str`
- `s3JobDefinition`:
  [S3JobDefinitionTypeDef](./type_defs.md#s3jobdefinitiontypedef)
- `samplingPercentage`: `int`
- `scheduleFrequency`:
  [JobScheduleFrequencyTypeDef](./type_defs.md#jobschedulefrequencytypedef)
- `statistics`: [StatisticsTypeDef](./type_defs.md#statisticstypedef)
- `tags`: `Dict`\[`str`, `str`\]
- `userPausedDetails`:
  [UserPausedDetailsTypeDef](./type_defs.md#userpauseddetailstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeorganizationconfigurationresponsetypedef"></a>

## DescribeOrganizationConfigurationResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import DescribeOrganizationConfigurationResponseTypeDef
```

Required fields:

- `autoEnable`: `bool`
- `maxAccountLimitReached`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disableorganizationadminaccountrequestrequesttypedef"></a>

## DisableOrganizationAdminAccountRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DisableOrganizationAdminAccountRequestRequestTypeDef
```

Required fields:

- `adminAccountId`: `str`

<a id="disassociatememberrequestrequesttypedef"></a>

## DisassociateMemberRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import DisassociateMemberRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="domaindetailstypedef"></a>

## DomainDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import DomainDetailsTypeDef
```

Optional fields:

- `domainName`: `str`

<a id="enablemacierequestrequesttypedef"></a>

## EnableMacieRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import EnableMacieRequestRequestTypeDef
```

Optional fields:

- `clientToken`: `str`
- `findingPublishingFrequency`:
  [FindingPublishingFrequencyType](./literals.md#findingpublishingfrequencytype)
- `status`: [MacieStatusType](./literals.md#maciestatustype)

<a id="enableorganizationadminaccountrequestrequesttypedef"></a>

## EnableOrganizationAdminAccountRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import EnableOrganizationAdminAccountRequestRequestTypeDef
```

Required fields:

- `adminAccountId`: `str`

Optional fields:

- `clientToken`: `str`

<a id="federatedusertypedef"></a>

## FederatedUserTypeDef

```python
from types_aiobotocore_macie2.type_defs import FederatedUserTypeDef
```

Optional fields:

- `accessKeyId`: `str`
- `accountId`: `str`
- `arn`: `str`
- `principalId`: `str`
- `sessionContext`:
  [SessionContextTypeDef](./type_defs.md#sessioncontexttypedef)

<a id="findingactiontypedef"></a>

## FindingActionTypeDef

```python
from types_aiobotocore_macie2.type_defs import FindingActionTypeDef
```

Optional fields:

- `actionType`: `Literal['AWS_API_CALL']` (see
  [FindingActionTypeType](./literals.md#findingactiontypetype))
- `apiCallDetails`:
  [ApiCallDetailsTypeDef](./type_defs.md#apicalldetailstypedef)

<a id="findingactortypedef"></a>

## FindingActorTypeDef

```python
from types_aiobotocore_macie2.type_defs import FindingActorTypeDef
```

Optional fields:

- `domainDetails`: [DomainDetailsTypeDef](./type_defs.md#domaindetailstypedef)
- `ipAddressDetails`:
  [IpAddressDetailsTypeDef](./type_defs.md#ipaddressdetailstypedef)
- `userIdentity`: [UserIdentityTypeDef](./type_defs.md#useridentitytypedef)

<a id="findingcriteriatypedef"></a>

## FindingCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import FindingCriteriaTypeDef
```

Optional fields:

- `criterion`: `Mapping`\[`str`,
  [CriterionAdditionalPropertiesTypeDef](./type_defs.md#criterionadditionalpropertiestypedef)\]

<a id="findingstatisticssortcriteriatypedef"></a>

## FindingStatisticsSortCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import FindingStatisticsSortCriteriaTypeDef
```

Optional fields:

- `attributeName`:
  [FindingStatisticsSortAttributeNameType](./literals.md#findingstatisticssortattributenametype)
- `orderBy`: [OrderByType](./literals.md#orderbytype)

<a id="findingtypedef"></a>

## FindingTypeDef

```python
from types_aiobotocore_macie2.type_defs import FindingTypeDef
```

Optional fields:

- `accountId`: `str`
- `archived`: `bool`
- `category`: [FindingCategoryType](./literals.md#findingcategorytype)
- `classificationDetails`:
  [ClassificationDetailsTypeDef](./type_defs.md#classificationdetailstypedef)
- `count`: `int`
- `createdAt`: `datetime`
- `description`: `str`
- `id`: `str`
- `partition`: `str`
- `policyDetails`: [PolicyDetailsTypeDef](./type_defs.md#policydetailstypedef)
- `region`: `str`
- `resourcesAffected`:
  [ResourcesAffectedTypeDef](./type_defs.md#resourcesaffectedtypedef)
- `sample`: `bool`
- `schemaVersion`: `str`
- `severity`: [SeverityTypeDef](./type_defs.md#severitytypedef)
- `title`: `str`
- `type`: [FindingTypeType](./literals.md#findingtypetype)
- `updatedAt`: `datetime`

<a id="findingsfilterlistitemtypedef"></a>

## FindingsFilterListItemTypeDef

```python
from types_aiobotocore_macie2.type_defs import FindingsFilterListItemTypeDef
```

Optional fields:

- `action`: [FindingsFilterActionType](./literals.md#findingsfilteractiontype)
- `arn`: `str`
- `id`: `str`
- `name`: `str`
- `tags`: `Dict`\[`str`, `str`\]

<a id="getadministratoraccountresponsetypedef"></a>

## GetAdministratorAccountResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetAdministratorAccountResponseTypeDef
```

Required fields:

- `administrator`: [InvitationTypeDef](./type_defs.md#invitationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getbucketstatisticsrequestrequesttypedef"></a>

## GetBucketStatisticsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetBucketStatisticsRequestRequestTypeDef
```

Optional fields:

- `accountId`: `str`

<a id="getbucketstatisticsresponsetypedef"></a>

## GetBucketStatisticsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetBucketStatisticsResponseTypeDef
```

Required fields:

- `bucketCount`: `int`
- `bucketCountByEffectivePermission`:
  [BucketCountByEffectivePermissionTypeDef](./type_defs.md#bucketcountbyeffectivepermissiontypedef)
- `bucketCountByEncryptionType`:
  [BucketCountByEncryptionTypeTypeDef](./type_defs.md#bucketcountbyencryptiontypetypedef)
- `bucketCountByObjectEncryptionRequirement`:
  [BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef](./type_defs.md#bucketcountpolicyallowsunencryptedobjectuploadstypedef)
- `bucketCountBySharedAccessType`:
  [BucketCountBySharedAccessTypeTypeDef](./type_defs.md#bucketcountbysharedaccesstypetypedef)
- `classifiableObjectCount`: `int`
- `classifiableSizeInBytes`: `int`
- `lastUpdated`: `datetime`
- `objectCount`: `int`
- `sizeInBytes`: `int`
- `sizeInBytesCompressed`: `int`
- `unclassifiableObjectCount`:
  [ObjectLevelStatisticsTypeDef](./type_defs.md#objectlevelstatisticstypedef)
- `unclassifiableObjectSizeInBytes`:
  [ObjectLevelStatisticsTypeDef](./type_defs.md#objectlevelstatisticstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getclassificationexportconfigurationresponsetypedef"></a>

## GetClassificationExportConfigurationResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetClassificationExportConfigurationResponseTypeDef
```

Required fields:

- `configuration`:
  [ClassificationExportConfigurationTypeDef](./type_defs.md#classificationexportconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcustomdataidentifierrequestrequesttypedef"></a>

## GetCustomDataIdentifierRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetCustomDataIdentifierRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="getcustomdataidentifierresponsetypedef"></a>

## GetCustomDataIdentifierResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetCustomDataIdentifierResponseTypeDef
```

Required fields:

- `arn`: `str`
- `createdAt`: `datetime`
- `deleted`: `bool`
- `description`: `str`
- `id`: `str`
- `ignoreWords`: `List`\[`str`\]
- `keywords`: `List`\[`str`\]
- `maximumMatchDistance`: `int`
- `name`: `str`
- `regex`: `str`
- `severityLevels`:
  `List`\[[SeverityLevelTypeDef](./type_defs.md#severityleveltypedef)\]
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getfindingstatisticsrequestrequesttypedef"></a>

## GetFindingStatisticsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetFindingStatisticsRequestRequestTypeDef
```

Required fields:

- `groupBy`: [GroupByType](./literals.md#groupbytype)

Optional fields:

- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `size`: `int`
- `sortCriteria`:
  [FindingStatisticsSortCriteriaTypeDef](./type_defs.md#findingstatisticssortcriteriatypedef)

<a id="getfindingstatisticsresponsetypedef"></a>

## GetFindingStatisticsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetFindingStatisticsResponseTypeDef
```

Required fields:

- `countsByGroup`:
  `List`\[[GroupCountTypeDef](./type_defs.md#groupcounttypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getfindingsfilterrequestrequesttypedef"></a>

## GetFindingsFilterRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetFindingsFilterRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="getfindingsfilterresponsetypedef"></a>

## GetFindingsFilterResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetFindingsFilterResponseTypeDef
```

Required fields:

- `action`: [FindingsFilterActionType](./literals.md#findingsfilteractiontype)
- `arn`: `str`
- `description`: `str`
- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `id`: `str`
- `name`: `str`
- `position`: `int`
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getfindingspublicationconfigurationresponsetypedef"></a>

## GetFindingsPublicationConfigurationResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetFindingsPublicationConfigurationResponseTypeDef
```

Required fields:

- `securityHubConfiguration`:
  [SecurityHubConfigurationTypeDef](./type_defs.md#securityhubconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getfindingsrequestrequesttypedef"></a>

## GetFindingsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetFindingsRequestRequestTypeDef
```

Required fields:

- `findingIds`: `Sequence`\[`str`\]

Optional fields:

- `sortCriteria`: [SortCriteriaTypeDef](./type_defs.md#sortcriteriatypedef)

<a id="getfindingsresponsetypedef"></a>

## GetFindingsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetFindingsResponseTypeDef
```

Required fields:

- `findings`: `List`\[[FindingTypeDef](./type_defs.md#findingtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getinvitationscountresponsetypedef"></a>

## GetInvitationsCountResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetInvitationsCountResponseTypeDef
```

Required fields:

- `invitationsCount`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getmaciesessionresponsetypedef"></a>

## GetMacieSessionResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetMacieSessionResponseTypeDef
```

Required fields:

- `createdAt`: `datetime`
- `findingPublishingFrequency`:
  [FindingPublishingFrequencyType](./literals.md#findingpublishingfrequencytype)
- `serviceRole`: `str`
- `status`: [MacieStatusType](./literals.md#maciestatustype)
- `updatedAt`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getmasteraccountresponsetypedef"></a>

## GetMasterAccountResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetMasterAccountResponseTypeDef
```

Required fields:

- `master`: [InvitationTypeDef](./type_defs.md#invitationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getmemberrequestrequesttypedef"></a>

## GetMemberRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetMemberRequestRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="getmemberresponsetypedef"></a>

## GetMemberResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetMemberResponseTypeDef
```

Required fields:

- `accountId`: `str`
- `administratorAccountId`: `str`
- `arn`: `str`
- `email`: `str`
- `invitedAt`: `datetime`
- `masterAccountId`: `str`
- `relationshipStatus`:
  [RelationshipStatusType](./literals.md#relationshipstatustype)
- `tags`: `Dict`\[`str`, `str`\]
- `updatedAt`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getusagestatisticsrequestrequesttypedef"></a>

## GetUsageStatisticsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetUsageStatisticsRequestRequestTypeDef
```

Optional fields:

- `filterBy`:
  `Sequence`\[[UsageStatisticsFilterTypeDef](./type_defs.md#usagestatisticsfiltertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `sortBy`:
  [UsageStatisticsSortByTypeDef](./type_defs.md#usagestatisticssortbytypedef)
- `timeRange`: [TimeRangeType](./literals.md#timerangetype)

<a id="getusagestatisticsresponsetypedef"></a>

## GetUsageStatisticsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetUsageStatisticsResponseTypeDef
```

Required fields:

- `nextToken`: `str`
- `records`: `List`\[[UsageRecordTypeDef](./type_defs.md#usagerecordtypedef)\]
- `timeRange`: [TimeRangeType](./literals.md#timerangetype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getusagetotalsrequestrequesttypedef"></a>

## GetUsageTotalsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetUsageTotalsRequestRequestTypeDef
```

Optional fields:

- `timeRange`: `str`

<a id="getusagetotalsresponsetypedef"></a>

## GetUsageTotalsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import GetUsageTotalsResponseTypeDef
```

Required fields:

- `timeRange`: [TimeRangeType](./literals.md#timerangetype)
- `usageTotals`:
  `List`\[[UsageTotalTypeDef](./type_defs.md#usagetotaltypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="groupcounttypedef"></a>

## GroupCountTypeDef

```python
from types_aiobotocore_macie2.type_defs import GroupCountTypeDef
```

Optional fields:

- `count`: `int`
- `groupKey`: `str`

<a id="iamusertypedef"></a>

## IamUserTypeDef

```python
from types_aiobotocore_macie2.type_defs import IamUserTypeDef
```

Optional fields:

- `accountId`: `str`
- `arn`: `str`
- `principalId`: `str`
- `userName`: `str`

<a id="invitationtypedef"></a>

## InvitationTypeDef

```python
from types_aiobotocore_macie2.type_defs import InvitationTypeDef
```

Optional fields:

- `accountId`: `str`
- `invitationId`: `str`
- `invitedAt`: `datetime`
- `relationshipStatus`:
  [RelationshipStatusType](./literals.md#relationshipstatustype)

<a id="ipaddressdetailstypedef"></a>

## IpAddressDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import IpAddressDetailsTypeDef
```

Optional fields:

- `ipAddressV4`: `str`
- `ipCity`: [IpCityTypeDef](./type_defs.md#ipcitytypedef)
- `ipCountry`: [IpCountryTypeDef](./type_defs.md#ipcountrytypedef)
- `ipGeoLocation`: [IpGeoLocationTypeDef](./type_defs.md#ipgeolocationtypedef)
- `ipOwner`: [IpOwnerTypeDef](./type_defs.md#ipownertypedef)

<a id="ipcitytypedef"></a>

## IpCityTypeDef

```python
from types_aiobotocore_macie2.type_defs import IpCityTypeDef
```

Optional fields:

- `name`: `str`

<a id="ipcountrytypedef"></a>

## IpCountryTypeDef

```python
from types_aiobotocore_macie2.type_defs import IpCountryTypeDef
```

Optional fields:

- `code`: `str`
- `name`: `str`

<a id="ipgeolocationtypedef"></a>

## IpGeoLocationTypeDef

```python
from types_aiobotocore_macie2.type_defs import IpGeoLocationTypeDef
```

Optional fields:

- `lat`: `float`
- `lon`: `float`

<a id="ipownertypedef"></a>

## IpOwnerTypeDef

```python
from types_aiobotocore_macie2.type_defs import IpOwnerTypeDef
```

Optional fields:

- `asn`: `str`
- `asnOrg`: `str`
- `isp`: `str`
- `org`: `str`

<a id="jobdetailstypedef"></a>

## JobDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import JobDetailsTypeDef
```

Optional fields:

- `isDefinedInJob`: [IsDefinedInJobType](./literals.md#isdefinedinjobtype)
- `isMonitoredByJob`:
  [IsMonitoredByJobType](./literals.md#ismonitoredbyjobtype)
- `lastJobId`: `str`
- `lastJobRunTime`: `datetime`

<a id="jobschedulefrequencytypedef"></a>

## JobScheduleFrequencyTypeDef

```python
from types_aiobotocore_macie2.type_defs import JobScheduleFrequencyTypeDef
```

Optional fields:

- `dailySchedule`: `Mapping`\[`str`, `Any`\]
- `monthlySchedule`:
  [MonthlyScheduleTypeDef](./type_defs.md#monthlyscheduletypedef)
- `weeklySchedule`:
  [WeeklyScheduleTypeDef](./type_defs.md#weeklyscheduletypedef)

<a id="jobscopetermtypedef"></a>

## JobScopeTermTypeDef

```python
from types_aiobotocore_macie2.type_defs import JobScopeTermTypeDef
```

Optional fields:

- `simpleScopeTerm`:
  [SimpleScopeTermTypeDef](./type_defs.md#simplescopetermtypedef)
- `tagScopeTerm`: [TagScopeTermTypeDef](./type_defs.md#tagscopetermtypedef)

<a id="jobscopingblocktypedef"></a>

## JobScopingBlockTypeDef

```python
from types_aiobotocore_macie2.type_defs import JobScopingBlockTypeDef
```

Optional fields:

- `and`:
  `Sequence`\[[JobScopeTermTypeDef](./type_defs.md#jobscopetermtypedef)\]

<a id="jobsummarytypedef"></a>

## JobSummaryTypeDef

```python
from types_aiobotocore_macie2.type_defs import JobSummaryTypeDef
```

Optional fields:

- `bucketDefinitions`:
  `List`\[[S3BucketDefinitionForJobTypeDef](./type_defs.md#s3bucketdefinitionforjobtypedef)\]
- `createdAt`: `datetime`
- `jobId`: `str`
- `jobStatus`: [JobStatusType](./literals.md#jobstatustype)
- `jobType`: [JobTypeType](./literals.md#jobtypetype)
- `lastRunErrorStatus`:
  [LastRunErrorStatusTypeDef](./type_defs.md#lastrunerrorstatustypedef)
- `name`: `str`
- `userPausedDetails`:
  [UserPausedDetailsTypeDef](./type_defs.md#userpauseddetailstypedef)
- `bucketCriteria`:
  [S3BucketCriteriaForJobTypeDef](./type_defs.md#s3bucketcriteriaforjobtypedef)

<a id="keyvaluepairtypedef"></a>

## KeyValuePairTypeDef

```python
from types_aiobotocore_macie2.type_defs import KeyValuePairTypeDef
```

Optional fields:

- `key`: `str`
- `value`: `str`

<a id="lastrunerrorstatustypedef"></a>

## LastRunErrorStatusTypeDef

```python
from types_aiobotocore_macie2.type_defs import LastRunErrorStatusTypeDef
```

Optional fields:

- `code`:
  [LastRunErrorStatusCodeType](./literals.md#lastrunerrorstatuscodetype)

<a id="listclassificationjobsrequestrequesttypedef"></a>

## ListClassificationJobsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListClassificationJobsRequestRequestTypeDef
```

Optional fields:

- `filterCriteria`:
  [ListJobsFilterCriteriaTypeDef](./type_defs.md#listjobsfiltercriteriatypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`:
  [ListJobsSortCriteriaTypeDef](./type_defs.md#listjobssortcriteriatypedef)

<a id="listclassificationjobsresponsetypedef"></a>

## ListClassificationJobsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListClassificationJobsResponseTypeDef
```

Required fields:

- `items`: `List`\[[JobSummaryTypeDef](./type_defs.md#jobsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcustomdataidentifiersrequestrequesttypedef"></a>

## ListCustomDataIdentifiersRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListCustomDataIdentifiersRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listcustomdataidentifiersresponsetypedef"></a>

## ListCustomDataIdentifiersResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListCustomDataIdentifiersResponseTypeDef
```

Required fields:

- `items`:
  `List`\[[CustomDataIdentifierSummaryTypeDef](./type_defs.md#customdataidentifiersummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listfindingsfiltersrequestrequesttypedef"></a>

## ListFindingsFiltersRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListFindingsFiltersRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listfindingsfiltersresponsetypedef"></a>

## ListFindingsFiltersResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListFindingsFiltersResponseTypeDef
```

Required fields:

- `findingsFilterListItems`:
  `List`\[[FindingsFilterListItemTypeDef](./type_defs.md#findingsfilterlistitemtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listfindingsrequestrequesttypedef"></a>

## ListFindingsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListFindingsRequestRequestTypeDef
```

Optional fields:

- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`: [SortCriteriaTypeDef](./type_defs.md#sortcriteriatypedef)

<a id="listfindingsresponsetypedef"></a>

## ListFindingsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListFindingsResponseTypeDef
```

Required fields:

- `findingIds`: `List`\[`str`\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinvitationsrequestrequesttypedef"></a>

## ListInvitationsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListInvitationsRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listinvitationsresponsetypedef"></a>

## ListInvitationsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListInvitationsResponseTypeDef
```

Required fields:

- `invitations`:
  `List`\[[InvitationTypeDef](./type_defs.md#invitationtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listjobsfiltercriteriatypedef"></a>

## ListJobsFilterCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListJobsFilterCriteriaTypeDef
```

Optional fields:

- `excludes`:
  `Sequence`\[[ListJobsFilterTermTypeDef](./type_defs.md#listjobsfiltertermtypedef)\]
- `includes`:
  `Sequence`\[[ListJobsFilterTermTypeDef](./type_defs.md#listjobsfiltertermtypedef)\]

<a id="listjobsfiltertermtypedef"></a>

## ListJobsFilterTermTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListJobsFilterTermTypeDef
```

Optional fields:

- `comparator`: [JobComparatorType](./literals.md#jobcomparatortype)
- `key`: [ListJobsFilterKeyType](./literals.md#listjobsfilterkeytype)
- `values`: `Sequence`\[`str`\]

<a id="listjobssortcriteriatypedef"></a>

## ListJobsSortCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListJobsSortCriteriaTypeDef
```

Optional fields:

- `attributeName`:
  [ListJobsSortAttributeNameType](./literals.md#listjobssortattributenametype)
- `orderBy`: [OrderByType](./literals.md#orderbytype)

<a id="listmanageddataidentifiersrequestrequesttypedef"></a>

## ListManagedDataIdentifiersRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListManagedDataIdentifiersRequestRequestTypeDef
```

Optional fields:

- `nextToken`: `str`

<a id="listmanageddataidentifiersresponsetypedef"></a>

## ListManagedDataIdentifiersResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListManagedDataIdentifiersResponseTypeDef
```

Required fields:

- `items`:
  `List`\[[ManagedDataIdentifierSummaryTypeDef](./type_defs.md#manageddataidentifiersummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmembersrequestrequesttypedef"></a>

## ListMembersRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListMembersRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`
- `onlyAssociated`: `str`

<a id="listmembersresponsetypedef"></a>

## ListMembersResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListMembersResponseTypeDef
```

Required fields:

- `members`: `List`\[[MemberTypeDef](./type_defs.md#membertypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listorganizationadminaccountsrequestrequesttypedef"></a>

## ListOrganizationAdminAccountsRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListOrganizationAdminAccountsRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listorganizationadminaccountsresponsetypedef"></a>

## ListOrganizationAdminAccountsResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListOrganizationAdminAccountsResponseTypeDef
```

Required fields:

- `adminAccounts`:
  `List`\[[AdminAccountTypeDef](./type_defs.md#adminaccounttypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="manageddataidentifiersummarytypedef"></a>

## ManagedDataIdentifierSummaryTypeDef

```python
from types_aiobotocore_macie2.type_defs import ManagedDataIdentifierSummaryTypeDef
```

Optional fields:

- `category`:
  [SensitiveDataItemCategoryType](./literals.md#sensitivedataitemcategorytype)
- `id`: `str`

<a id="matchingbuckettypedef"></a>

## MatchingBucketTypeDef

```python
from types_aiobotocore_macie2.type_defs import MatchingBucketTypeDef
```

Optional fields:

- `accountId`: `str`
- `bucketName`: `str`
- `classifiableObjectCount`: `int`
- `classifiableSizeInBytes`: `int`
- `errorCode`: `Literal['ACCESS_DENIED']` (see
  [BucketMetadataErrorCodeType](./literals.md#bucketmetadataerrorcodetype))
- `errorMessage`: `str`
- `jobDetails`: [JobDetailsTypeDef](./type_defs.md#jobdetailstypedef)
- `objectCount`: `int`
- `objectCountByEncryptionType`:
  [ObjectCountByEncryptionTypeTypeDef](./type_defs.md#objectcountbyencryptiontypetypedef)
- `sizeInBytes`: `int`
- `sizeInBytesCompressed`: `int`
- `unclassifiableObjectCount`:
  [ObjectLevelStatisticsTypeDef](./type_defs.md#objectlevelstatisticstypedef)
- `unclassifiableObjectSizeInBytes`:
  [ObjectLevelStatisticsTypeDef](./type_defs.md#objectlevelstatisticstypedef)

<a id="matchingresourcetypedef"></a>

## MatchingResourceTypeDef

```python
from types_aiobotocore_macie2.type_defs import MatchingResourceTypeDef
```

Optional fields:

- `matchingBucket`:
  [MatchingBucketTypeDef](./type_defs.md#matchingbuckettypedef)

<a id="membertypedef"></a>

## MemberTypeDef

```python
from types_aiobotocore_macie2.type_defs import MemberTypeDef
```

Optional fields:

- `accountId`: `str`
- `administratorAccountId`: `str`
- `arn`: `str`
- `email`: `str`
- `invitedAt`: `datetime`
- `masterAccountId`: `str`
- `relationshipStatus`:
  [RelationshipStatusType](./literals.md#relationshipstatustype)
- `tags`: `Dict`\[`str`, `str`\]
- `updatedAt`: `datetime`

<a id="monthlyscheduletypedef"></a>

## MonthlyScheduleTypeDef

```python
from types_aiobotocore_macie2.type_defs import MonthlyScheduleTypeDef
```

Optional fields:

- `dayOfMonth`: `int`

<a id="objectcountbyencryptiontypetypedef"></a>

## ObjectCountByEncryptionTypeTypeDef

```python
from types_aiobotocore_macie2.type_defs import ObjectCountByEncryptionTypeTypeDef
```

Optional fields:

- `customerManaged`: `int`
- `kmsManaged`: `int`
- `s3Managed`: `int`
- `unencrypted`: `int`
- `unknown`: `int`

<a id="objectlevelstatisticstypedef"></a>

## ObjectLevelStatisticsTypeDef

```python
from types_aiobotocore_macie2.type_defs import ObjectLevelStatisticsTypeDef
```

Optional fields:

- `fileType`: `int`
- `storageClass`: `int`
- `total`: `int`

<a id="occurrencestypedef"></a>

## OccurrencesTypeDef

```python
from types_aiobotocore_macie2.type_defs import OccurrencesTypeDef
```

Optional fields:

- `cells`: `List`\[[CellTypeDef](./type_defs.md#celltypedef)\]
- `lineRanges`: `List`\[[RangeTypeDef](./type_defs.md#rangetypedef)\]
- `offsetRanges`: `List`\[[RangeTypeDef](./type_defs.md#rangetypedef)\]
- `pages`: `List`\[[PageTypeDef](./type_defs.md#pagetypedef)\]
- `records`: `List`\[[RecordTypeDef](./type_defs.md#recordtypedef)\]

<a id="pagetypedef"></a>

## PageTypeDef

```python
from types_aiobotocore_macie2.type_defs import PageTypeDef
```

Optional fields:

- `lineRange`: [RangeTypeDef](./type_defs.md#rangetypedef)
- `offsetRange`: [RangeTypeDef](./type_defs.md#rangetypedef)
- `pageNumber`: `int`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_macie2.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="policydetailstypedef"></a>

## PolicyDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import PolicyDetailsTypeDef
```

Optional fields:

- `action`: [FindingActionTypeDef](./type_defs.md#findingactiontypedef)
- `actor`: [FindingActorTypeDef](./type_defs.md#findingactortypedef)

<a id="putclassificationexportconfigurationrequestrequesttypedef"></a>

## PutClassificationExportConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import PutClassificationExportConfigurationRequestRequestTypeDef
```

Required fields:

- `configuration`:
  [ClassificationExportConfigurationTypeDef](./type_defs.md#classificationexportconfigurationtypedef)

<a id="putclassificationexportconfigurationresponsetypedef"></a>

## PutClassificationExportConfigurationResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import PutClassificationExportConfigurationResponseTypeDef
```

Required fields:

- `configuration`:
  [ClassificationExportConfigurationTypeDef](./type_defs.md#classificationexportconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="putfindingspublicationconfigurationrequestrequesttypedef"></a>

## PutFindingsPublicationConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import PutFindingsPublicationConfigurationRequestRequestTypeDef
```

Optional fields:

- `clientToken`: `str`
- `securityHubConfiguration`:
  [SecurityHubConfigurationTypeDef](./type_defs.md#securityhubconfigurationtypedef)

<a id="rangetypedef"></a>

## RangeTypeDef

```python
from types_aiobotocore_macie2.type_defs import RangeTypeDef
```

Optional fields:

- `end`: `int`
- `start`: `int`
- `startColumn`: `int`

<a id="recordtypedef"></a>

## RecordTypeDef

```python
from types_aiobotocore_macie2.type_defs import RecordTypeDef
```

Optional fields:

- `jsonPath`: `str`
- `recordIndex`: `int`

<a id="replicationdetailstypedef"></a>

## ReplicationDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import ReplicationDetailsTypeDef
```

Optional fields:

- `replicated`: `bool`
- `replicatedExternally`: `bool`
- `replicationAccounts`: `List`\[`str`\]

<a id="resourcesaffectedtypedef"></a>

## ResourcesAffectedTypeDef

```python
from types_aiobotocore_macie2.type_defs import ResourcesAffectedTypeDef
```

Optional fields:

- `s3Bucket`: [S3BucketTypeDef](./type_defs.md#s3buckettypedef)
- `s3Object`: [S3ObjectTypeDef](./type_defs.md#s3objecttypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_macie2.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3bucketcriteriaforjobtypedef"></a>

## S3BucketCriteriaForJobTypeDef

```python
from types_aiobotocore_macie2.type_defs import S3BucketCriteriaForJobTypeDef
```

Optional fields:

- `excludes`:
  [CriteriaBlockForJobTypeDef](./type_defs.md#criteriablockforjobtypedef)
- `includes`:
  [CriteriaBlockForJobTypeDef](./type_defs.md#criteriablockforjobtypedef)

<a id="s3bucketdefinitionforjobtypedef"></a>

## S3BucketDefinitionForJobTypeDef

```python
from types_aiobotocore_macie2.type_defs import S3BucketDefinitionForJobTypeDef
```

Required fields:

- `accountId`: `str`
- `buckets`: `Sequence`\[`str`\]

<a id="s3bucketownertypedef"></a>

## S3BucketOwnerTypeDef

```python
from types_aiobotocore_macie2.type_defs import S3BucketOwnerTypeDef
```

Optional fields:

- `displayName`: `str`
- `id`: `str`

<a id="s3buckettypedef"></a>

## S3BucketTypeDef

```python
from types_aiobotocore_macie2.type_defs import S3BucketTypeDef
```

Optional fields:

- `allowsUnencryptedObjectUploads`:
  [AllowsUnencryptedObjectUploadsType](./literals.md#allowsunencryptedobjectuploadstype)
- `arn`: `str`
- `createdAt`: `datetime`
- `defaultServerSideEncryption`:
  [ServerSideEncryptionTypeDef](./type_defs.md#serversideencryptiontypedef)
- `name`: `str`
- `owner`: [S3BucketOwnerTypeDef](./type_defs.md#s3bucketownertypedef)
- `publicAccess`:
  [BucketPublicAccessTypeDef](./type_defs.md#bucketpublicaccesstypedef)
- `tags`: `List`\[[KeyValuePairTypeDef](./type_defs.md#keyvaluepairtypedef)\]

<a id="s3destinationtypedef"></a>

## S3DestinationTypeDef

```python
from types_aiobotocore_macie2.type_defs import S3DestinationTypeDef
```

Required fields:

- `bucketName`: `str`
- `kmsKeyArn`: `str`

Optional fields:

- `keyPrefix`: `str`

<a id="s3jobdefinitiontypedef"></a>

## S3JobDefinitionTypeDef

```python
from types_aiobotocore_macie2.type_defs import S3JobDefinitionTypeDef
```

Optional fields:

- `bucketDefinitions`:
  `Sequence`\[[S3BucketDefinitionForJobTypeDef](./type_defs.md#s3bucketdefinitionforjobtypedef)\]
- `scoping`: [ScopingTypeDef](./type_defs.md#scopingtypedef)
- `bucketCriteria`:
  [S3BucketCriteriaForJobTypeDef](./type_defs.md#s3bucketcriteriaforjobtypedef)

<a id="s3objecttypedef"></a>

## S3ObjectTypeDef

```python
from types_aiobotocore_macie2.type_defs import S3ObjectTypeDef
```

Optional fields:

- `bucketArn`: `str`
- `eTag`: `str`
- `extension`: `str`
- `key`: `str`
- `lastModified`: `datetime`
- `path`: `str`
- `publicAccess`: `bool`
- `serverSideEncryption`:
  [ServerSideEncryptionTypeDef](./type_defs.md#serversideencryptiontypedef)
- `size`: `int`
- `storageClass`: [StorageClassType](./literals.md#storageclasstype)
- `tags`: `List`\[[KeyValuePairTypeDef](./type_defs.md#keyvaluepairtypedef)\]
- `versionId`: `str`

<a id="scopingtypedef"></a>

## ScopingTypeDef

```python
from types_aiobotocore_macie2.type_defs import ScopingTypeDef
```

Optional fields:

- `excludes`: [JobScopingBlockTypeDef](./type_defs.md#jobscopingblocktypedef)
- `includes`: [JobScopingBlockTypeDef](./type_defs.md#jobscopingblocktypedef)

<a id="searchresourcesbucketcriteriatypedef"></a>

## SearchResourcesBucketCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesBucketCriteriaTypeDef
```

Optional fields:

- `excludes`:
  [SearchResourcesCriteriaBlockTypeDef](./type_defs.md#searchresourcescriteriablocktypedef)
- `includes`:
  [SearchResourcesCriteriaBlockTypeDef](./type_defs.md#searchresourcescriteriablocktypedef)

<a id="searchresourcescriteriablocktypedef"></a>

## SearchResourcesCriteriaBlockTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesCriteriaBlockTypeDef
```

Optional fields:

- `and`:
  `Sequence`\[[SearchResourcesCriteriaTypeDef](./type_defs.md#searchresourcescriteriatypedef)\]

<a id="searchresourcescriteriatypedef"></a>

## SearchResourcesCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesCriteriaTypeDef
```

Optional fields:

- `simpleCriterion`:
  [SearchResourcesSimpleCriterionTypeDef](./type_defs.md#searchresourcessimplecriteriontypedef)
- `tagCriterion`:
  [SearchResourcesTagCriterionTypeDef](./type_defs.md#searchresourcestagcriteriontypedef)

<a id="searchresourcesrequestrequesttypedef"></a>

## SearchResourcesRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesRequestRequestTypeDef
```

Optional fields:

- `bucketCriteria`:
  [SearchResourcesBucketCriteriaTypeDef](./type_defs.md#searchresourcesbucketcriteriatypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `sortCriteria`:
  [SearchResourcesSortCriteriaTypeDef](./type_defs.md#searchresourcessortcriteriatypedef)

<a id="searchresourcesresponsetypedef"></a>

## SearchResourcesResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesResponseTypeDef
```

Required fields:

- `matchingResources`:
  `List`\[[MatchingResourceTypeDef](./type_defs.md#matchingresourcetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="searchresourcessimplecriteriontypedef"></a>

## SearchResourcesSimpleCriterionTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesSimpleCriterionTypeDef
```

Optional fields:

- `comparator`:
  [SearchResourcesComparatorType](./literals.md#searchresourcescomparatortype)
- `key`:
  [SearchResourcesSimpleCriterionKeyType](./literals.md#searchresourcessimplecriterionkeytype)
- `values`: `Sequence`\[`str`\]

<a id="searchresourcessortcriteriatypedef"></a>

## SearchResourcesSortCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesSortCriteriaTypeDef
```

Optional fields:

- `attributeName`:
  [SearchResourcesSortAttributeNameType](./literals.md#searchresourcessortattributenametype)
- `orderBy`: [OrderByType](./literals.md#orderbytype)

<a id="searchresourcestagcriterionpairtypedef"></a>

## SearchResourcesTagCriterionPairTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesTagCriterionPairTypeDef
```

Optional fields:

- `key`: `str`
- `value`: `str`

<a id="searchresourcestagcriteriontypedef"></a>

## SearchResourcesTagCriterionTypeDef

```python
from types_aiobotocore_macie2.type_defs import SearchResourcesTagCriterionTypeDef
```

Optional fields:

- `comparator`:
  [SearchResourcesComparatorType](./literals.md#searchresourcescomparatortype)
- `tagValues`:
  `Sequence`\[[SearchResourcesTagCriterionPairTypeDef](./type_defs.md#searchresourcestagcriterionpairtypedef)\]

<a id="securityhubconfigurationtypedef"></a>

## SecurityHubConfigurationTypeDef

```python
from types_aiobotocore_macie2.type_defs import SecurityHubConfigurationTypeDef
```

Required fields:

- `publishClassificationFindings`: `bool`
- `publishPolicyFindings`: `bool`

<a id="sensitivedataitemtypedef"></a>

## SensitiveDataItemTypeDef

```python
from types_aiobotocore_macie2.type_defs import SensitiveDataItemTypeDef
```

Optional fields:

- `category`:
  [SensitiveDataItemCategoryType](./literals.md#sensitivedataitemcategorytype)
- `detections`:
  `List`\[[DefaultDetectionTypeDef](./type_defs.md#defaultdetectiontypedef)\]
- `totalCount`: `int`

<a id="serversideencryptiontypedef"></a>

## ServerSideEncryptionTypeDef

```python
from types_aiobotocore_macie2.type_defs import ServerSideEncryptionTypeDef
```

Optional fields:

- `encryptionType`: [EncryptionTypeType](./literals.md#encryptiontypetype)
- `kmsMasterKeyId`: `str`

<a id="servicelimittypedef"></a>

## ServiceLimitTypeDef

```python
from types_aiobotocore_macie2.type_defs import ServiceLimitTypeDef
```

Optional fields:

- `isServiceLimited`: `bool`
- `unit`: `Literal['TERABYTES']` (see [UnitType](./literals.md#unittype))
- `value`: `int`

<a id="sessioncontextattributestypedef"></a>

## SessionContextAttributesTypeDef

```python
from types_aiobotocore_macie2.type_defs import SessionContextAttributesTypeDef
```

Optional fields:

- `creationDate`: `datetime`
- `mfaAuthenticated`: `bool`

<a id="sessioncontexttypedef"></a>

## SessionContextTypeDef

```python
from types_aiobotocore_macie2.type_defs import SessionContextTypeDef
```

Optional fields:

- `attributes`:
  [SessionContextAttributesTypeDef](./type_defs.md#sessioncontextattributestypedef)
- `sessionIssuer`: [SessionIssuerTypeDef](./type_defs.md#sessionissuertypedef)

<a id="sessionissuertypedef"></a>

## SessionIssuerTypeDef

```python
from types_aiobotocore_macie2.type_defs import SessionIssuerTypeDef
```

Optional fields:

- `accountId`: `str`
- `arn`: `str`
- `principalId`: `str`
- `type`: `str`
- `userName`: `str`

<a id="severityleveltypedef"></a>

## SeverityLevelTypeDef

```python
from types_aiobotocore_macie2.type_defs import SeverityLevelTypeDef
```

Required fields:

- `occurrencesThreshold`: `int`
- `severity`:
  [DataIdentifierSeverityType](./literals.md#dataidentifierseveritytype)

<a id="severitytypedef"></a>

## SeverityTypeDef

```python
from types_aiobotocore_macie2.type_defs import SeverityTypeDef
```

Optional fields:

- `description`:
  [SeverityDescriptionType](./literals.md#severitydescriptiontype)
- `score`: `int`

<a id="simplecriterionforjobtypedef"></a>

## SimpleCriterionForJobTypeDef

```python
from types_aiobotocore_macie2.type_defs import SimpleCriterionForJobTypeDef
```

Optional fields:

- `comparator`: [JobComparatorType](./literals.md#jobcomparatortype)
- `key`:
  [SimpleCriterionKeyForJobType](./literals.md#simplecriterionkeyforjobtype)
- `values`: `Sequence`\[`str`\]

<a id="simplescopetermtypedef"></a>

## SimpleScopeTermTypeDef

```python
from types_aiobotocore_macie2.type_defs import SimpleScopeTermTypeDef
```

Optional fields:

- `comparator`: [JobComparatorType](./literals.md#jobcomparatortype)
- `key`: [ScopeFilterKeyType](./literals.md#scopefilterkeytype)
- `values`: `Sequence`\[`str`\]

<a id="sortcriteriatypedef"></a>

## SortCriteriaTypeDef

```python
from types_aiobotocore_macie2.type_defs import SortCriteriaTypeDef
```

Optional fields:

- `attributeName`: `str`
- `orderBy`: [OrderByType](./literals.md#orderbytype)

<a id="statisticstypedef"></a>

## StatisticsTypeDef

```python
from types_aiobotocore_macie2.type_defs import StatisticsTypeDef
```

Optional fields:

- `approximateNumberOfObjectsToProcess`: `float`
- `numberOfRuns`: `float`

<a id="tagcriterionforjobtypedef"></a>

## TagCriterionForJobTypeDef

```python
from types_aiobotocore_macie2.type_defs import TagCriterionForJobTypeDef
```

Optional fields:

- `comparator`: [JobComparatorType](./literals.md#jobcomparatortype)
- `tagValues`:
  `Sequence`\[[TagCriterionPairForJobTypeDef](./type_defs.md#tagcriterionpairforjobtypedef)\]

<a id="tagcriterionpairforjobtypedef"></a>

## TagCriterionPairForJobTypeDef

```python
from types_aiobotocore_macie2.type_defs import TagCriterionPairForJobTypeDef
```

Optional fields:

- `key`: `str`
- `value`: `str`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

<a id="tagscopetermtypedef"></a>

## TagScopeTermTypeDef

```python
from types_aiobotocore_macie2.type_defs import TagScopeTermTypeDef
```

Optional fields:

- `comparator`: [JobComparatorType](./literals.md#jobcomparatortype)
- `key`: `str`
- `tagValues`:
  `Sequence`\[[TagValuePairTypeDef](./type_defs.md#tagvaluepairtypedef)\]
- `target`: `Literal['S3_OBJECT']` (see
  [TagTargetType](./literals.md#tagtargettype))

<a id="tagvaluepairtypedef"></a>

## TagValuePairTypeDef

```python
from types_aiobotocore_macie2.type_defs import TagValuePairTypeDef
```

Optional fields:

- `key`: `str`
- `value`: `str`

<a id="testcustomdataidentifierrequestrequesttypedef"></a>

## TestCustomDataIdentifierRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import TestCustomDataIdentifierRequestRequestTypeDef
```

Required fields:

- `regex`: `str`
- `sampleText`: `str`

Optional fields:

- `ignoreWords`: `Sequence`\[`str`\]
- `keywords`: `Sequence`\[`str`\]
- `maximumMatchDistance`: `int`

<a id="testcustomdataidentifierresponsetypedef"></a>

## TestCustomDataIdentifierResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import TestCustomDataIdentifierResponseTypeDef
```

Required fields:

- `matchCount`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="unprocessedaccounttypedef"></a>

## UnprocessedAccountTypeDef

```python
from types_aiobotocore_macie2.type_defs import UnprocessedAccountTypeDef
```

Optional fields:

- `accountId`: `str`
- `errorCode`: [ErrorCodeType](./literals.md#errorcodetype)
- `errorMessage`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tagKeys`: `Sequence`\[`str`\]

<a id="updateclassificationjobrequestrequesttypedef"></a>

## UpdateClassificationJobRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import UpdateClassificationJobRequestRequestTypeDef
```

Required fields:

- `jobId`: `str`
- `jobStatus`: [JobStatusType](./literals.md#jobstatustype)

<a id="updatefindingsfilterrequestrequesttypedef"></a>

## UpdateFindingsFilterRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import UpdateFindingsFilterRequestRequestTypeDef
```

Required fields:

- `id`: `str`

Optional fields:

- `action`: [FindingsFilterActionType](./literals.md#findingsfilteractiontype)
- `description`: `str`
- `findingCriteria`:
  [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- `name`: `str`
- `position`: `int`
- `clientToken`: `str`

<a id="updatefindingsfilterresponsetypedef"></a>

## UpdateFindingsFilterResponseTypeDef

```python
from types_aiobotocore_macie2.type_defs import UpdateFindingsFilterResponseTypeDef
```

Required fields:

- `arn`: `str`
- `id`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatemaciesessionrequestrequesttypedef"></a>

## UpdateMacieSessionRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import UpdateMacieSessionRequestRequestTypeDef
```

Optional fields:

- `findingPublishingFrequency`:
  [FindingPublishingFrequencyType](./literals.md#findingpublishingfrequencytype)
- `status`: [MacieStatusType](./literals.md#maciestatustype)

<a id="updatemembersessionrequestrequesttypedef"></a>

## UpdateMemberSessionRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import UpdateMemberSessionRequestRequestTypeDef
```

Required fields:

- `id`: `str`
- `status`: [MacieStatusType](./literals.md#maciestatustype)

<a id="updateorganizationconfigurationrequestrequesttypedef"></a>

## UpdateOrganizationConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_macie2.type_defs import UpdateOrganizationConfigurationRequestRequestTypeDef
```

Required fields:

- `autoEnable`: `bool`

<a id="usagebyaccounttypedef"></a>

## UsageByAccountTypeDef

```python
from types_aiobotocore_macie2.type_defs import UsageByAccountTypeDef
```

Optional fields:

- `currency`: `Literal['USD']` (see [CurrencyType](./literals.md#currencytype))
- `estimatedCost`: `str`
- `serviceLimit`: [ServiceLimitTypeDef](./type_defs.md#servicelimittypedef)
- `type`: [UsageTypeType](./literals.md#usagetypetype)

<a id="usagerecordtypedef"></a>

## UsageRecordTypeDef

```python
from types_aiobotocore_macie2.type_defs import UsageRecordTypeDef
```

Optional fields:

- `accountId`: `str`
- `freeTrialStartDate`: `datetime`
- `usage`:
  `List`\[[UsageByAccountTypeDef](./type_defs.md#usagebyaccounttypedef)\]

<a id="usagestatisticsfiltertypedef"></a>

## UsageStatisticsFilterTypeDef

```python
from types_aiobotocore_macie2.type_defs import UsageStatisticsFilterTypeDef
```

Optional fields:

- `comparator`:
  [UsageStatisticsFilterComparatorType](./literals.md#usagestatisticsfiltercomparatortype)
- `key`:
  [UsageStatisticsFilterKeyType](./literals.md#usagestatisticsfilterkeytype)
- `values`: `Sequence`\[`str`\]

<a id="usagestatisticssortbytypedef"></a>

## UsageStatisticsSortByTypeDef

```python
from types_aiobotocore_macie2.type_defs import UsageStatisticsSortByTypeDef
```

Optional fields:

- `key`: [UsageStatisticsSortKeyType](./literals.md#usagestatisticssortkeytype)
- `orderBy`: [OrderByType](./literals.md#orderbytype)

<a id="usagetotaltypedef"></a>

## UsageTotalTypeDef

```python
from types_aiobotocore_macie2.type_defs import UsageTotalTypeDef
```

Optional fields:

- `currency`: `Literal['USD']` (see [CurrencyType](./literals.md#currencytype))
- `estimatedCost`: `str`
- `type`: [UsageTypeType](./literals.md#usagetypetype)

<a id="useridentityroottypedef"></a>

## UserIdentityRootTypeDef

```python
from types_aiobotocore_macie2.type_defs import UserIdentityRootTypeDef
```

Optional fields:

- `accountId`: `str`
- `arn`: `str`
- `principalId`: `str`

<a id="useridentitytypedef"></a>

## UserIdentityTypeDef

```python
from types_aiobotocore_macie2.type_defs import UserIdentityTypeDef
```

Optional fields:

- `assumedRole`: [AssumedRoleTypeDef](./type_defs.md#assumedroletypedef)
- `awsAccount`: [AwsAccountTypeDef](./type_defs.md#awsaccounttypedef)
- `awsService`: [AwsServiceTypeDef](./type_defs.md#awsservicetypedef)
- `federatedUser`: [FederatedUserTypeDef](./type_defs.md#federatedusertypedef)
- `iamUser`: [IamUserTypeDef](./type_defs.md#iamusertypedef)
- `root`: [UserIdentityRootTypeDef](./type_defs.md#useridentityroottypedef)
- `type`: [UserIdentityTypeType](./literals.md#useridentitytypetype)

<a id="userpauseddetailstypedef"></a>

## UserPausedDetailsTypeDef

```python
from types_aiobotocore_macie2.type_defs import UserPausedDetailsTypeDef
```

Optional fields:

- `jobExpiresAt`: `datetime`
- `jobImminentExpirationHealthEventArn`: `str`
- `jobPausedAt`: `datetime`

<a id="weeklyscheduletypedef"></a>

## WeeklyScheduleTypeDef

```python
from types_aiobotocore_macie2.type_defs import WeeklyScheduleTypeDef
```

Optional fields:

- `dayOfWeek`: [DayOfWeekType](./literals.md#dayofweektype)
