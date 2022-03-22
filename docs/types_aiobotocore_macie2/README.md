<a id="type-annotations-for-aiobotocore-macie2-module"></a>

# Type annotations for aiobotocore Macie2 module

> [Index](../README.md) > Macie2

Auto-generated documentation for
[Macie2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
type annotations stubs module
[types-aiobotocore-macie2](https://pypi.org/project/types-aiobotocore-macie2/).

- [Type annotations for aiobotocore Macie2 module](#type-annotations-for-aiobotocore-macie2-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [Macie2Client](#macie2client)
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

Click `Modify` and select `boto3 common` and `Macie2`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `Macie2` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[macie2]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[macie2]'


# standalone installation
python -m pip install types-aiobotocore-macie2
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-macie2
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="macie2client"></a>

## Macie2Client

Type annotations for `session.create_client("macie2")` as
[Macie2Client](./client.md)

Can be used directly:

```python
from types_aiobotocore_macie2.client import Macie2Client
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [accept_invitation](./client.md#accept_invitation)
- [batch_get_custom_data_identifiers](./client.md#batch_get_custom_data_identifiers)
- [can_paginate](./client.md#can_paginate)
- [create_classification_job](./client.md#create_classification_job)
- [create_custom_data_identifier](./client.md#create_custom_data_identifier)
- [create_findings_filter](./client.md#create_findings_filter)
- [create_invitations](./client.md#create_invitations)
- [create_member](./client.md#create_member)
- [create_sample_findings](./client.md#create_sample_findings)
- [decline_invitations](./client.md#decline_invitations)
- [delete_custom_data_identifier](./client.md#delete_custom_data_identifier)
- [delete_findings_filter](./client.md#delete_findings_filter)
- [delete_invitations](./client.md#delete_invitations)
- [delete_member](./client.md#delete_member)
- [describe_buckets](./client.md#describe_buckets)
- [describe_classification_job](./client.md#describe_classification_job)
- [describe_organization_configuration](./client.md#describe_organization_configuration)
- [disable_macie](./client.md#disable_macie)
- [disable_organization_admin_account](./client.md#disable_organization_admin_account)
- [disassociate_from_administrator_account](./client.md#disassociate_from_administrator_account)
- [disassociate_from_master_account](./client.md#disassociate_from_master_account)
- [disassociate_member](./client.md#disassociate_member)
- [enable_macie](./client.md#enable_macie)
- [enable_organization_admin_account](./client.md#enable_organization_admin_account)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_administrator_account](./client.md#get_administrator_account)
- [get_bucket_statistics](./client.md#get_bucket_statistics)
- [get_classification_export_configuration](./client.md#get_classification_export_configuration)
- [get_custom_data_identifier](./client.md#get_custom_data_identifier)
- [get_finding_statistics](./client.md#get_finding_statistics)
- [get_findings](./client.md#get_findings)
- [get_findings_filter](./client.md#get_findings_filter)
- [get_findings_publication_configuration](./client.md#get_findings_publication_configuration)
- [get_invitations_count](./client.md#get_invitations_count)
- [get_macie_session](./client.md#get_macie_session)
- [get_master_account](./client.md#get_master_account)
- [get_member](./client.md#get_member)
- [get_paginator](./client.md#get_paginator)
- [get_usage_statistics](./client.md#get_usage_statistics)
- [get_usage_totals](./client.md#get_usage_totals)
- [list_classification_jobs](./client.md#list_classification_jobs)
- [list_custom_data_identifiers](./client.md#list_custom_data_identifiers)
- [list_findings](./client.md#list_findings)
- [list_findings_filters](./client.md#list_findings_filters)
- [list_invitations](./client.md#list_invitations)
- [list_managed_data_identifiers](./client.md#list_managed_data_identifiers)
- [list_members](./client.md#list_members)
- [list_organization_admin_accounts](./client.md#list_organization_admin_accounts)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [put_classification_export_configuration](./client.md#put_classification_export_configuration)
- [put_findings_publication_configuration](./client.md#put_findings_publication_configuration)
- [search_resources](./client.md#search_resources)
- [tag_resource](./client.md#tag_resource)
- [test_custom_data_identifier](./client.md#test_custom_data_identifier)
- [untag_resource](./client.md#untag_resource)
- [update_classification_job](./client.md#update_classification_job)
- [update_findings_filter](./client.md#update_findings_filter)
- [update_macie_session](./client.md#update_macie_session)
- [update_member_session](./client.md#update_member_session)
- [update_organization_configuration](./client.md#update_organization_configuration)

<a id="exceptions"></a>

### Exceptions

Macie2Client [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- ConflictException
- InternalServerException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ThrottlingException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("macie2").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_macie2.paginator import DescribeBucketsPaginator, ...
```

- [DescribeBucketsPaginator](./paginators.md#describebucketspaginator)
- [GetUsageStatisticsPaginator](./paginators.md#getusagestatisticspaginator)
- [ListClassificationJobsPaginator](./paginators.md#listclassificationjobspaginator)
- [ListCustomDataIdentifiersPaginator](./paginators.md#listcustomdataidentifierspaginator)
- [ListFindingsPaginator](./paginators.md#listfindingspaginator)
- [ListFindingsFiltersPaginator](./paginators.md#listfindingsfilterspaginator)
- [ListInvitationsPaginator](./paginators.md#listinvitationspaginator)
- [ListMembersPaginator](./paginators.md#listmemberspaginator)
- [ListOrganizationAdminAccountsPaginator](./paginators.md#listorganizationadminaccountspaginator)
- [SearchResourcesPaginator](./paginators.md#searchresourcespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_macie2.literals import AdminStatusType, ...
```

- [AdminStatusType](./literals.md#adminstatustype)
- [AllowsUnencryptedObjectUploadsType](./literals.md#allowsunencryptedobjectuploadstype)
- [BucketMetadataErrorCodeType](./literals.md#bucketmetadataerrorcodetype)
- [CurrencyType](./literals.md#currencytype)
- [DataIdentifierSeverityType](./literals.md#dataidentifierseveritytype)
- [DayOfWeekType](./literals.md#dayofweektype)
- [DescribeBucketsPaginatorName](./literals.md#describebucketspaginatorname)
- [EffectivePermissionType](./literals.md#effectivepermissiontype)
- [EncryptionTypeType](./literals.md#encryptiontypetype)
- [ErrorCodeType](./literals.md#errorcodetype)
- [FindingActionTypeType](./literals.md#findingactiontypetype)
- [FindingCategoryType](./literals.md#findingcategorytype)
- [FindingPublishingFrequencyType](./literals.md#findingpublishingfrequencytype)
- [FindingStatisticsSortAttributeNameType](./literals.md#findingstatisticssortattributenametype)
- [FindingTypeType](./literals.md#findingtypetype)
- [FindingsFilterActionType](./literals.md#findingsfilteractiontype)
- [GetUsageStatisticsPaginatorName](./literals.md#getusagestatisticspaginatorname)
- [GroupByType](./literals.md#groupbytype)
- [IsDefinedInJobType](./literals.md#isdefinedinjobtype)
- [IsMonitoredByJobType](./literals.md#ismonitoredbyjobtype)
- [JobComparatorType](./literals.md#jobcomparatortype)
- [JobStatusType](./literals.md#jobstatustype)
- [JobTypeType](./literals.md#jobtypetype)
- [LastRunErrorStatusCodeType](./literals.md#lastrunerrorstatuscodetype)
- [ListClassificationJobsPaginatorName](./literals.md#listclassificationjobspaginatorname)
- [ListCustomDataIdentifiersPaginatorName](./literals.md#listcustomdataidentifierspaginatorname)
- [ListFindingsFiltersPaginatorName](./literals.md#listfindingsfilterspaginatorname)
- [ListFindingsPaginatorName](./literals.md#listfindingspaginatorname)
- [ListInvitationsPaginatorName](./literals.md#listinvitationspaginatorname)
- [ListJobsFilterKeyType](./literals.md#listjobsfilterkeytype)
- [ListJobsSortAttributeNameType](./literals.md#listjobssortattributenametype)
- [ListMembersPaginatorName](./literals.md#listmemberspaginatorname)
- [ListOrganizationAdminAccountsPaginatorName](./literals.md#listorganizationadminaccountspaginatorname)
- [MacieStatusType](./literals.md#maciestatustype)
- [ManagedDataIdentifierSelectorType](./literals.md#manageddataidentifierselectortype)
- [OrderByType](./literals.md#orderbytype)
- [RelationshipStatusType](./literals.md#relationshipstatustype)
- [ScopeFilterKeyType](./literals.md#scopefilterkeytype)
- [SearchResourcesComparatorType](./literals.md#searchresourcescomparatortype)
- [SearchResourcesPaginatorName](./literals.md#searchresourcespaginatorname)
- [SearchResourcesSimpleCriterionKeyType](./literals.md#searchresourcessimplecriterionkeytype)
- [SearchResourcesSortAttributeNameType](./literals.md#searchresourcessortattributenametype)
- [SensitiveDataItemCategoryType](./literals.md#sensitivedataitemcategorytype)
- [SeverityDescriptionType](./literals.md#severitydescriptiontype)
- [SharedAccessType](./literals.md#sharedaccesstype)
- [SimpleCriterionKeyForJobType](./literals.md#simplecriterionkeyforjobtype)
- [StorageClassType](./literals.md#storageclasstype)
- [TagTargetType](./literals.md#tagtargettype)
- [TimeRangeType](./literals.md#timerangetype)
- [TypeType](./literals.md#typetype)
- [UnitType](./literals.md#unittype)
- [UsageStatisticsFilterComparatorType](./literals.md#usagestatisticsfiltercomparatortype)
- [UsageStatisticsFilterKeyType](./literals.md#usagestatisticsfilterkeytype)
- [UsageStatisticsSortKeyType](./literals.md#usagestatisticssortkeytype)
- [UsageTypeType](./literals.md#usagetypetype)
- [UserIdentityTypeType](./literals.md#useridentitytypetype)
- [Macie2ServiceName](./literals.md#macie2servicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_macie2.type_defs import AcceptInvitationRequestRequestTypeDef, ...
```

- [AcceptInvitationRequestRequestTypeDef](./type_defs.md#acceptinvitationrequestrequesttypedef)
- [AccessControlListTypeDef](./type_defs.md#accesscontrollisttypedef)
- [AccountDetailTypeDef](./type_defs.md#accountdetailtypedef)
- [AccountLevelPermissionsTypeDef](./type_defs.md#accountlevelpermissionstypedef)
- [AdminAccountTypeDef](./type_defs.md#adminaccounttypedef)
- [ApiCallDetailsTypeDef](./type_defs.md#apicalldetailstypedef)
- [AssumedRoleTypeDef](./type_defs.md#assumedroletypedef)
- [AwsAccountTypeDef](./type_defs.md#awsaccounttypedef)
- [AwsServiceTypeDef](./type_defs.md#awsservicetypedef)
- [BatchGetCustomDataIdentifierSummaryTypeDef](./type_defs.md#batchgetcustomdataidentifiersummarytypedef)
- [BatchGetCustomDataIdentifiersRequestRequestTypeDef](./type_defs.md#batchgetcustomdataidentifiersrequestrequesttypedef)
- [BatchGetCustomDataIdentifiersResponseTypeDef](./type_defs.md#batchgetcustomdataidentifiersresponsetypedef)
- [BlockPublicAccessTypeDef](./type_defs.md#blockpublicaccesstypedef)
- [BucketCountByEffectivePermissionTypeDef](./type_defs.md#bucketcountbyeffectivepermissiontypedef)
- [BucketCountByEncryptionTypeTypeDef](./type_defs.md#bucketcountbyencryptiontypetypedef)
- [BucketCountBySharedAccessTypeTypeDef](./type_defs.md#bucketcountbysharedaccesstypetypedef)
- [BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef](./type_defs.md#bucketcountpolicyallowsunencryptedobjectuploadstypedef)
- [BucketCriteriaAdditionalPropertiesTypeDef](./type_defs.md#bucketcriteriaadditionalpropertiestypedef)
- [BucketLevelPermissionsTypeDef](./type_defs.md#bucketlevelpermissionstypedef)
- [BucketMetadataTypeDef](./type_defs.md#bucketmetadatatypedef)
- [BucketPermissionConfigurationTypeDef](./type_defs.md#bucketpermissionconfigurationtypedef)
- [BucketPolicyTypeDef](./type_defs.md#bucketpolicytypedef)
- [BucketPublicAccessTypeDef](./type_defs.md#bucketpublicaccesstypedef)
- [BucketServerSideEncryptionTypeDef](./type_defs.md#bucketserversideencryptiontypedef)
- [BucketSortCriteriaTypeDef](./type_defs.md#bucketsortcriteriatypedef)
- [CellTypeDef](./type_defs.md#celltypedef)
- [ClassificationDetailsTypeDef](./type_defs.md#classificationdetailstypedef)
- [ClassificationExportConfigurationTypeDef](./type_defs.md#classificationexportconfigurationtypedef)
- [ClassificationResultStatusTypeDef](./type_defs.md#classificationresultstatustypedef)
- [ClassificationResultTypeDef](./type_defs.md#classificationresulttypedef)
- [CreateClassificationJobRequestRequestTypeDef](./type_defs.md#createclassificationjobrequestrequesttypedef)
- [CreateClassificationJobResponseTypeDef](./type_defs.md#createclassificationjobresponsetypedef)
- [CreateCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#createcustomdataidentifierrequestrequesttypedef)
- [CreateCustomDataIdentifierResponseTypeDef](./type_defs.md#createcustomdataidentifierresponsetypedef)
- [CreateFindingsFilterRequestRequestTypeDef](./type_defs.md#createfindingsfilterrequestrequesttypedef)
- [CreateFindingsFilterResponseTypeDef](./type_defs.md#createfindingsfilterresponsetypedef)
- [CreateInvitationsRequestRequestTypeDef](./type_defs.md#createinvitationsrequestrequesttypedef)
- [CreateInvitationsResponseTypeDef](./type_defs.md#createinvitationsresponsetypedef)
- [CreateMemberRequestRequestTypeDef](./type_defs.md#creatememberrequestrequesttypedef)
- [CreateMemberResponseTypeDef](./type_defs.md#creatememberresponsetypedef)
- [CreateSampleFindingsRequestRequestTypeDef](./type_defs.md#createsamplefindingsrequestrequesttypedef)
- [CriteriaBlockForJobTypeDef](./type_defs.md#criteriablockforjobtypedef)
- [CriteriaForJobTypeDef](./type_defs.md#criteriaforjobtypedef)
- [CriterionAdditionalPropertiesTypeDef](./type_defs.md#criterionadditionalpropertiestypedef)
- [CustomDataIdentifierSummaryTypeDef](./type_defs.md#customdataidentifiersummarytypedef)
- [CustomDataIdentifiersTypeDef](./type_defs.md#customdataidentifierstypedef)
- [CustomDetectionTypeDef](./type_defs.md#customdetectiontypedef)
- [DeclineInvitationsRequestRequestTypeDef](./type_defs.md#declineinvitationsrequestrequesttypedef)
- [DeclineInvitationsResponseTypeDef](./type_defs.md#declineinvitationsresponsetypedef)
- [DefaultDetectionTypeDef](./type_defs.md#defaultdetectiontypedef)
- [DeleteCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#deletecustomdataidentifierrequestrequesttypedef)
- [DeleteFindingsFilterRequestRequestTypeDef](./type_defs.md#deletefindingsfilterrequestrequesttypedef)
- [DeleteInvitationsRequestRequestTypeDef](./type_defs.md#deleteinvitationsrequestrequesttypedef)
- [DeleteInvitationsResponseTypeDef](./type_defs.md#deleteinvitationsresponsetypedef)
- [DeleteMemberRequestRequestTypeDef](./type_defs.md#deletememberrequestrequesttypedef)
- [DescribeBucketsRequestRequestTypeDef](./type_defs.md#describebucketsrequestrequesttypedef)
- [DescribeBucketsResponseTypeDef](./type_defs.md#describebucketsresponsetypedef)
- [DescribeClassificationJobRequestRequestTypeDef](./type_defs.md#describeclassificationjobrequestrequesttypedef)
- [DescribeClassificationJobResponseTypeDef](./type_defs.md#describeclassificationjobresponsetypedef)
- [DescribeOrganizationConfigurationResponseTypeDef](./type_defs.md#describeorganizationconfigurationresponsetypedef)
- [DisableOrganizationAdminAccountRequestRequestTypeDef](./type_defs.md#disableorganizationadminaccountrequestrequesttypedef)
- [DisassociateMemberRequestRequestTypeDef](./type_defs.md#disassociatememberrequestrequesttypedef)
- [DomainDetailsTypeDef](./type_defs.md#domaindetailstypedef)
- [EnableMacieRequestRequestTypeDef](./type_defs.md#enablemacierequestrequesttypedef)
- [EnableOrganizationAdminAccountRequestRequestTypeDef](./type_defs.md#enableorganizationadminaccountrequestrequesttypedef)
- [FederatedUserTypeDef](./type_defs.md#federatedusertypedef)
- [FindingActionTypeDef](./type_defs.md#findingactiontypedef)
- [FindingActorTypeDef](./type_defs.md#findingactortypedef)
- [FindingCriteriaTypeDef](./type_defs.md#findingcriteriatypedef)
- [FindingStatisticsSortCriteriaTypeDef](./type_defs.md#findingstatisticssortcriteriatypedef)
- [FindingTypeDef](./type_defs.md#findingtypedef)
- [FindingsFilterListItemTypeDef](./type_defs.md#findingsfilterlistitemtypedef)
- [GetAdministratorAccountResponseTypeDef](./type_defs.md#getadministratoraccountresponsetypedef)
- [GetBucketStatisticsRequestRequestTypeDef](./type_defs.md#getbucketstatisticsrequestrequesttypedef)
- [GetBucketStatisticsResponseTypeDef](./type_defs.md#getbucketstatisticsresponsetypedef)
- [GetClassificationExportConfigurationResponseTypeDef](./type_defs.md#getclassificationexportconfigurationresponsetypedef)
- [GetCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#getcustomdataidentifierrequestrequesttypedef)
- [GetCustomDataIdentifierResponseTypeDef](./type_defs.md#getcustomdataidentifierresponsetypedef)
- [GetFindingStatisticsRequestRequestTypeDef](./type_defs.md#getfindingstatisticsrequestrequesttypedef)
- [GetFindingStatisticsResponseTypeDef](./type_defs.md#getfindingstatisticsresponsetypedef)
- [GetFindingsFilterRequestRequestTypeDef](./type_defs.md#getfindingsfilterrequestrequesttypedef)
- [GetFindingsFilterResponseTypeDef](./type_defs.md#getfindingsfilterresponsetypedef)
- [GetFindingsPublicationConfigurationResponseTypeDef](./type_defs.md#getfindingspublicationconfigurationresponsetypedef)
- [GetFindingsRequestRequestTypeDef](./type_defs.md#getfindingsrequestrequesttypedef)
- [GetFindingsResponseTypeDef](./type_defs.md#getfindingsresponsetypedef)
- [GetInvitationsCountResponseTypeDef](./type_defs.md#getinvitationscountresponsetypedef)
- [GetMacieSessionResponseTypeDef](./type_defs.md#getmaciesessionresponsetypedef)
- [GetMasterAccountResponseTypeDef](./type_defs.md#getmasteraccountresponsetypedef)
- [GetMemberRequestRequestTypeDef](./type_defs.md#getmemberrequestrequesttypedef)
- [GetMemberResponseTypeDef](./type_defs.md#getmemberresponsetypedef)
- [GetUsageStatisticsRequestRequestTypeDef](./type_defs.md#getusagestatisticsrequestrequesttypedef)
- [GetUsageStatisticsResponseTypeDef](./type_defs.md#getusagestatisticsresponsetypedef)
- [GetUsageTotalsRequestRequestTypeDef](./type_defs.md#getusagetotalsrequestrequesttypedef)
- [GetUsageTotalsResponseTypeDef](./type_defs.md#getusagetotalsresponsetypedef)
- [GroupCountTypeDef](./type_defs.md#groupcounttypedef)
- [IamUserTypeDef](./type_defs.md#iamusertypedef)
- [InvitationTypeDef](./type_defs.md#invitationtypedef)
- [IpAddressDetailsTypeDef](./type_defs.md#ipaddressdetailstypedef)
- [IpCityTypeDef](./type_defs.md#ipcitytypedef)
- [IpCountryTypeDef](./type_defs.md#ipcountrytypedef)
- [IpGeoLocationTypeDef](./type_defs.md#ipgeolocationtypedef)
- [IpOwnerTypeDef](./type_defs.md#ipownertypedef)
- [JobDetailsTypeDef](./type_defs.md#jobdetailstypedef)
- [JobScheduleFrequencyTypeDef](./type_defs.md#jobschedulefrequencytypedef)
- [JobScopeTermTypeDef](./type_defs.md#jobscopetermtypedef)
- [JobScopingBlockTypeDef](./type_defs.md#jobscopingblocktypedef)
- [JobSummaryTypeDef](./type_defs.md#jobsummarytypedef)
- [KeyValuePairTypeDef](./type_defs.md#keyvaluepairtypedef)
- [LastRunErrorStatusTypeDef](./type_defs.md#lastrunerrorstatustypedef)
- [ListClassificationJobsRequestRequestTypeDef](./type_defs.md#listclassificationjobsrequestrequesttypedef)
- [ListClassificationJobsResponseTypeDef](./type_defs.md#listclassificationjobsresponsetypedef)
- [ListCustomDataIdentifiersRequestRequestTypeDef](./type_defs.md#listcustomdataidentifiersrequestrequesttypedef)
- [ListCustomDataIdentifiersResponseTypeDef](./type_defs.md#listcustomdataidentifiersresponsetypedef)
- [ListFindingsFiltersRequestRequestTypeDef](./type_defs.md#listfindingsfiltersrequestrequesttypedef)
- [ListFindingsFiltersResponseTypeDef](./type_defs.md#listfindingsfiltersresponsetypedef)
- [ListFindingsRequestRequestTypeDef](./type_defs.md#listfindingsrequestrequesttypedef)
- [ListFindingsResponseTypeDef](./type_defs.md#listfindingsresponsetypedef)
- [ListInvitationsRequestRequestTypeDef](./type_defs.md#listinvitationsrequestrequesttypedef)
- [ListInvitationsResponseTypeDef](./type_defs.md#listinvitationsresponsetypedef)
- [ListJobsFilterCriteriaTypeDef](./type_defs.md#listjobsfiltercriteriatypedef)
- [ListJobsFilterTermTypeDef](./type_defs.md#listjobsfiltertermtypedef)
- [ListJobsSortCriteriaTypeDef](./type_defs.md#listjobssortcriteriatypedef)
- [ListManagedDataIdentifiersRequestRequestTypeDef](./type_defs.md#listmanageddataidentifiersrequestrequesttypedef)
- [ListManagedDataIdentifiersResponseTypeDef](./type_defs.md#listmanageddataidentifiersresponsetypedef)
- [ListMembersRequestRequestTypeDef](./type_defs.md#listmembersrequestrequesttypedef)
- [ListMembersResponseTypeDef](./type_defs.md#listmembersresponsetypedef)
- [ListOrganizationAdminAccountsRequestRequestTypeDef](./type_defs.md#listorganizationadminaccountsrequestrequesttypedef)
- [ListOrganizationAdminAccountsResponseTypeDef](./type_defs.md#listorganizationadminaccountsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ManagedDataIdentifierSummaryTypeDef](./type_defs.md#manageddataidentifiersummarytypedef)
- [MatchingBucketTypeDef](./type_defs.md#matchingbuckettypedef)
- [MatchingResourceTypeDef](./type_defs.md#matchingresourcetypedef)
- [MemberTypeDef](./type_defs.md#membertypedef)
- [MonthlyScheduleTypeDef](./type_defs.md#monthlyscheduletypedef)
- [ObjectCountByEncryptionTypeTypeDef](./type_defs.md#objectcountbyencryptiontypetypedef)
- [ObjectLevelStatisticsTypeDef](./type_defs.md#objectlevelstatisticstypedef)
- [OccurrencesTypeDef](./type_defs.md#occurrencestypedef)
- [PageTypeDef](./type_defs.md#pagetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PolicyDetailsTypeDef](./type_defs.md#policydetailstypedef)
- [PutClassificationExportConfigurationRequestRequestTypeDef](./type_defs.md#putclassificationexportconfigurationrequestrequesttypedef)
- [PutClassificationExportConfigurationResponseTypeDef](./type_defs.md#putclassificationexportconfigurationresponsetypedef)
- [PutFindingsPublicationConfigurationRequestRequestTypeDef](./type_defs.md#putfindingspublicationconfigurationrequestrequesttypedef)
- [RangeTypeDef](./type_defs.md#rangetypedef)
- [RecordTypeDef](./type_defs.md#recordtypedef)
- [ReplicationDetailsTypeDef](./type_defs.md#replicationdetailstypedef)
- [ResourcesAffectedTypeDef](./type_defs.md#resourcesaffectedtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [S3BucketCriteriaForJobTypeDef](./type_defs.md#s3bucketcriteriaforjobtypedef)
- [S3BucketDefinitionForJobTypeDef](./type_defs.md#s3bucketdefinitionforjobtypedef)
- [S3BucketOwnerTypeDef](./type_defs.md#s3bucketownertypedef)
- [S3BucketTypeDef](./type_defs.md#s3buckettypedef)
- [S3DestinationTypeDef](./type_defs.md#s3destinationtypedef)
- [S3JobDefinitionTypeDef](./type_defs.md#s3jobdefinitiontypedef)
- [S3ObjectTypeDef](./type_defs.md#s3objecttypedef)
- [ScopingTypeDef](./type_defs.md#scopingtypedef)
- [SearchResourcesBucketCriteriaTypeDef](./type_defs.md#searchresourcesbucketcriteriatypedef)
- [SearchResourcesCriteriaBlockTypeDef](./type_defs.md#searchresourcescriteriablocktypedef)
- [SearchResourcesCriteriaTypeDef](./type_defs.md#searchresourcescriteriatypedef)
- [SearchResourcesRequestRequestTypeDef](./type_defs.md#searchresourcesrequestrequesttypedef)
- [SearchResourcesResponseTypeDef](./type_defs.md#searchresourcesresponsetypedef)
- [SearchResourcesSimpleCriterionTypeDef](./type_defs.md#searchresourcessimplecriteriontypedef)
- [SearchResourcesSortCriteriaTypeDef](./type_defs.md#searchresourcessortcriteriatypedef)
- [SearchResourcesTagCriterionPairTypeDef](./type_defs.md#searchresourcestagcriterionpairtypedef)
- [SearchResourcesTagCriterionTypeDef](./type_defs.md#searchresourcestagcriteriontypedef)
- [SecurityHubConfigurationTypeDef](./type_defs.md#securityhubconfigurationtypedef)
- [SensitiveDataItemTypeDef](./type_defs.md#sensitivedataitemtypedef)
- [ServerSideEncryptionTypeDef](./type_defs.md#serversideencryptiontypedef)
- [ServiceLimitTypeDef](./type_defs.md#servicelimittypedef)
- [SessionContextAttributesTypeDef](./type_defs.md#sessioncontextattributestypedef)
- [SessionContextTypeDef](./type_defs.md#sessioncontexttypedef)
- [SessionIssuerTypeDef](./type_defs.md#sessionissuertypedef)
- [SeverityLevelTypeDef](./type_defs.md#severityleveltypedef)
- [SeverityTypeDef](./type_defs.md#severitytypedef)
- [SimpleCriterionForJobTypeDef](./type_defs.md#simplecriterionforjobtypedef)
- [SimpleScopeTermTypeDef](./type_defs.md#simplescopetermtypedef)
- [SortCriteriaTypeDef](./type_defs.md#sortcriteriatypedef)
- [StatisticsTypeDef](./type_defs.md#statisticstypedef)
- [TagCriterionForJobTypeDef](./type_defs.md#tagcriterionforjobtypedef)
- [TagCriterionPairForJobTypeDef](./type_defs.md#tagcriterionpairforjobtypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagScopeTermTypeDef](./type_defs.md#tagscopetermtypedef)
- [TagValuePairTypeDef](./type_defs.md#tagvaluepairtypedef)
- [TestCustomDataIdentifierRequestRequestTypeDef](./type_defs.md#testcustomdataidentifierrequestrequesttypedef)
- [TestCustomDataIdentifierResponseTypeDef](./type_defs.md#testcustomdataidentifierresponsetypedef)
- [UnprocessedAccountTypeDef](./type_defs.md#unprocessedaccounttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateClassificationJobRequestRequestTypeDef](./type_defs.md#updateclassificationjobrequestrequesttypedef)
- [UpdateFindingsFilterRequestRequestTypeDef](./type_defs.md#updatefindingsfilterrequestrequesttypedef)
- [UpdateFindingsFilterResponseTypeDef](./type_defs.md#updatefindingsfilterresponsetypedef)
- [UpdateMacieSessionRequestRequestTypeDef](./type_defs.md#updatemaciesessionrequestrequesttypedef)
- [UpdateMemberSessionRequestRequestTypeDef](./type_defs.md#updatemembersessionrequestrequesttypedef)
- [UpdateOrganizationConfigurationRequestRequestTypeDef](./type_defs.md#updateorganizationconfigurationrequestrequesttypedef)
- [UsageByAccountTypeDef](./type_defs.md#usagebyaccounttypedef)
- [UsageRecordTypeDef](./type_defs.md#usagerecordtypedef)
- [UsageStatisticsFilterTypeDef](./type_defs.md#usagestatisticsfiltertypedef)
- [UsageStatisticsSortByTypeDef](./type_defs.md#usagestatisticssortbytypedef)
- [UsageTotalTypeDef](./type_defs.md#usagetotaltypedef)
- [UserIdentityRootTypeDef](./type_defs.md#useridentityroottypedef)
- [UserIdentityTypeDef](./type_defs.md#useridentitytypedef)
- [UserPausedDetailsTypeDef](./type_defs.md#userpauseddetailstypedef)
- [WeeklyScheduleTypeDef](./type_defs.md#weeklyscheduletypedef)
