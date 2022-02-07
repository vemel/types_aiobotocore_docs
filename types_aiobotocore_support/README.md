<a id="type-annotations-for-aiobotocore-support-module"></a>

# Type annotations for aiobotocore Support module

> [Index](..) > Support

Auto-generated documentation for
[Support](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support)
type annotations stubs module
[types-aiobotocore-support](https://pypi.org/project/types-aiobotocore-support/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[support]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[support]'

# standalone installation
pip install types-aiobotocore-support
```

- [Type annotations for aiobotocore Support module](#type-annotations-for-aiobotocore-support-module)
  - [SupportClient](#supportclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="supportclient"></a>

## SupportClient

Type annotations for `session.create_client("support")` as
[SupportClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_support.client import SupportClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [add_attachments_to_set](./client.md#add_attachments_to_set)
- [add_communication_to_case](./client.md#add_communication_to_case)
- [can_paginate](./client.md#can_paginate)
- [create_case](./client.md#create_case)
- [describe_attachment](./client.md#describe_attachment)
- [describe_cases](./client.md#describe_cases)
- [describe_communications](./client.md#describe_communications)
- [describe_services](./client.md#describe_services)
- [describe_severity_levels](./client.md#describe_severity_levels)
- [describe_trusted_advisor_check_refresh_statuses](./client.md#describe_trusted_advisor_check_refresh_statuses)
- [describe_trusted_advisor_check_result](./client.md#describe_trusted_advisor_check_result)
- [describe_trusted_advisor_check_summaries](./client.md#describe_trusted_advisor_check_summaries)
- [describe_trusted_advisor_checks](./client.md#describe_trusted_advisor_checks)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [refresh_trusted_advisor_check](./client.md#refresh_trusted_advisor_check)
- [resolve_case](./client.md#resolve_case)

<a id="exceptions"></a>

### Exceptions

SupportClient [exceptions](./client.md#exceptions)

- AttachmentIdNotFound
- AttachmentLimitExceeded
- AttachmentSetExpired
- AttachmentSetIdNotFound
- AttachmentSetSizeLimitExceeded
- CaseCreationLimitExceeded
- CaseIdNotFound
- ClientError
- DescribeAttachmentLimitExceeded
- InternalServerError

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("support").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_support.paginator import DescribeCasesPaginator, ...
```

- [DescribeCasesPaginator](./paginators.md#describecasespaginator)
- [DescribeCommunicationsPaginator](./paginators.md#describecommunicationspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_support.literals import DescribeCasesPaginatorName, ...
```

- [DescribeCasesPaginatorName](./literals.md#describecasespaginatorname)
- [DescribeCommunicationsPaginatorName](./literals.md#describecommunicationspaginatorname)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_support.type_defs import AddAttachmentsToSetRequestRequestTypeDef, ...
```

- [AddAttachmentsToSetRequestRequestTypeDef](./type_defs.md#addattachmentstosetrequestrequesttypedef)
- [AddAttachmentsToSetResponseTypeDef](./type_defs.md#addattachmentstosetresponsetypedef)
- [AddCommunicationToCaseRequestRequestTypeDef](./type_defs.md#addcommunicationtocaserequestrequesttypedef)
- [AddCommunicationToCaseResponseTypeDef](./type_defs.md#addcommunicationtocaseresponsetypedef)
- [AttachmentDetailsTypeDef](./type_defs.md#attachmentdetailstypedef)
- [AttachmentTypeDef](./type_defs.md#attachmenttypedef)
- [CaseDetailsTypeDef](./type_defs.md#casedetailstypedef)
- [CategoryTypeDef](./type_defs.md#categorytypedef)
- [CommunicationTypeDef](./type_defs.md#communicationtypedef)
- [CreateCaseRequestRequestTypeDef](./type_defs.md#createcaserequestrequesttypedef)
- [CreateCaseResponseTypeDef](./type_defs.md#createcaseresponsetypedef)
- [DescribeAttachmentRequestRequestTypeDef](./type_defs.md#describeattachmentrequestrequesttypedef)
- [DescribeAttachmentResponseTypeDef](./type_defs.md#describeattachmentresponsetypedef)
- [DescribeCasesRequestRequestTypeDef](./type_defs.md#describecasesrequestrequesttypedef)
- [DescribeCasesResponseTypeDef](./type_defs.md#describecasesresponsetypedef)
- [DescribeCommunicationsRequestRequestTypeDef](./type_defs.md#describecommunicationsrequestrequesttypedef)
- [DescribeCommunicationsResponseTypeDef](./type_defs.md#describecommunicationsresponsetypedef)
- [DescribeServicesRequestRequestTypeDef](./type_defs.md#describeservicesrequestrequesttypedef)
- [DescribeServicesResponseTypeDef](./type_defs.md#describeservicesresponsetypedef)
- [DescribeSeverityLevelsRequestRequestTypeDef](./type_defs.md#describeseveritylevelsrequestrequesttypedef)
- [DescribeSeverityLevelsResponseTypeDef](./type_defs.md#describeseveritylevelsresponsetypedef)
- [DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef](./type_defs.md#describetrustedadvisorcheckrefreshstatusesrequestrequesttypedef)
- [DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef](./type_defs.md#describetrustedadvisorcheckrefreshstatusesresponsetypedef)
- [DescribeTrustedAdvisorCheckResultRequestRequestTypeDef](./type_defs.md#describetrustedadvisorcheckresultrequestrequesttypedef)
- [DescribeTrustedAdvisorCheckResultResponseTypeDef](./type_defs.md#describetrustedadvisorcheckresultresponsetypedef)
- [DescribeTrustedAdvisorCheckSummariesRequestRequestTypeDef](./type_defs.md#describetrustedadvisorchecksummariesrequestrequesttypedef)
- [DescribeTrustedAdvisorCheckSummariesResponseTypeDef](./type_defs.md#describetrustedadvisorchecksummariesresponsetypedef)
- [DescribeTrustedAdvisorChecksRequestRequestTypeDef](./type_defs.md#describetrustedadvisorchecksrequestrequesttypedef)
- [DescribeTrustedAdvisorChecksResponseTypeDef](./type_defs.md#describetrustedadvisorchecksresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [RecentCaseCommunicationsTypeDef](./type_defs.md#recentcasecommunicationstypedef)
- [RefreshTrustedAdvisorCheckRequestRequestTypeDef](./type_defs.md#refreshtrustedadvisorcheckrequestrequesttypedef)
- [RefreshTrustedAdvisorCheckResponseTypeDef](./type_defs.md#refreshtrustedadvisorcheckresponsetypedef)
- [ResolveCaseRequestRequestTypeDef](./type_defs.md#resolvecaserequestrequesttypedef)
- [ResolveCaseResponseTypeDef](./type_defs.md#resolvecaseresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ServiceTypeDef](./type_defs.md#servicetypedef)
- [SeverityLevelTypeDef](./type_defs.md#severityleveltypedef)
- [TrustedAdvisorCategorySpecificSummaryTypeDef](./type_defs.md#trustedadvisorcategoryspecificsummarytypedef)
- [TrustedAdvisorCheckDescriptionTypeDef](./type_defs.md#trustedadvisorcheckdescriptiontypedef)
- [TrustedAdvisorCheckRefreshStatusTypeDef](./type_defs.md#trustedadvisorcheckrefreshstatustypedef)
- [TrustedAdvisorCheckResultTypeDef](./type_defs.md#trustedadvisorcheckresulttypedef)
- [TrustedAdvisorCheckSummaryTypeDef](./type_defs.md#trustedadvisorchecksummarytypedef)
- [TrustedAdvisorCostOptimizingSummaryTypeDef](./type_defs.md#trustedadvisorcostoptimizingsummarytypedef)
- [TrustedAdvisorResourceDetailTypeDef](./type_defs.md#trustedadvisorresourcedetailtypedef)
- [TrustedAdvisorResourcesSummaryTypeDef](./type_defs.md#trustedadvisorresourcessummarytypedef)
