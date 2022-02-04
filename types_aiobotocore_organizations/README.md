<a id="type-annotations-for-aiobotocore-organizations-module"></a>

# Type annotations for aiobotocore Organizations module

> [Index](..) > Organizations

Auto-generated documentation for
[Organizations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
type annotations stubs module
[types-aiobotocore-organizations](https://pypi.org/project/types-aiobotocore-organizations/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[organizations]'

# install as a standalone
pip install types-aiobotocore-organizations
```

- [Type annotations for aiobotocore Organizations module](#type-annotations-for-aiobotocore-organizations-module)
  - [OrganizationsClient](#organizationsclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="organizationsclient"></a>

## OrganizationsClient

Type annotations for `aiobotocore.create_client("organizations")` as
[OrganizationsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_organizations.client import OrganizationsClient
```

<a id="methods"></a>

### Methods

- [accept_handshake](./client.md#accept_handshake)
- [attach_policy](./client.md#attach_policy)
- [can_paginate](./client.md#can_paginate)
- [cancel_handshake](./client.md#cancel_handshake)
- [create_account](./client.md#create_account)
- [create_gov_cloud_account](./client.md#create_gov_cloud_account)
- [create_organization](./client.md#create_organization)
- [create_organizational_unit](./client.md#create_organizational_unit)
- [create_policy](./client.md#create_policy)
- [decline_handshake](./client.md#decline_handshake)
- [delete_organization](./client.md#delete_organization)
- [delete_organizational_unit](./client.md#delete_organizational_unit)
- [delete_policy](./client.md#delete_policy)
- [deregister_delegated_administrator](./client.md#deregister_delegated_administrator)
- [describe_account](./client.md#describe_account)
- [describe_create_account_status](./client.md#describe_create_account_status)
- [describe_effective_policy](./client.md#describe_effective_policy)
- [describe_handshake](./client.md#describe_handshake)
- [describe_organization](./client.md#describe_organization)
- [describe_organizational_unit](./client.md#describe_organizational_unit)
- [describe_policy](./client.md#describe_policy)
- [detach_policy](./client.md#detach_policy)
- [disable_aws_service_access](./client.md#disable_aws_service_access)
- [disable_policy_type](./client.md#disable_policy_type)
- [enable_all_features](./client.md#enable_all_features)
- [enable_aws_service_access](./client.md#enable_aws_service_access)
- [enable_policy_type](./client.md#enable_policy_type)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [invite_account_to_organization](./client.md#invite_account_to_organization)
- [leave_organization](./client.md#leave_organization)
- [list_accounts](./client.md#list_accounts)
- [list_accounts_for_parent](./client.md#list_accounts_for_parent)
- [list_aws_service_access_for_organization](./client.md#list_aws_service_access_for_organization)
- [list_children](./client.md#list_children)
- [list_create_account_status](./client.md#list_create_account_status)
- [list_delegated_administrators](./client.md#list_delegated_administrators)
- [list_delegated_services_for_account](./client.md#list_delegated_services_for_account)
- [list_handshakes_for_account](./client.md#list_handshakes_for_account)
- [list_handshakes_for_organization](./client.md#list_handshakes_for_organization)
- [list_organizational_units_for_parent](./client.md#list_organizational_units_for_parent)
- [list_parents](./client.md#list_parents)
- [list_policies](./client.md#list_policies)
- [list_policies_for_target](./client.md#list_policies_for_target)
- [list_roots](./client.md#list_roots)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [list_targets_for_policy](./client.md#list_targets_for_policy)
- [move_account](./client.md#move_account)
- [register_delegated_administrator](./client.md#register_delegated_administrator)
- [remove_account_from_organization](./client.md#remove_account_from_organization)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_organizational_unit](./client.md#update_organizational_unit)
- [update_policy](./client.md#update_policy)

<a id="exceptions"></a>

### Exceptions

OrganizationsClient [exceptions](./client.md#exceptions)

- AWSOrganizationsNotInUseException
- AccessDeniedException
- AccessDeniedForDependencyException
- AccountAlreadyRegisteredException
- AccountNotFoundException
- AccountNotRegisteredException
- AccountOwnerNotVerifiedException
- AlreadyInOrganizationException
- ChildNotFoundException
- ClientError
- ConcurrentModificationException
- ConstraintViolationException
- CreateAccountStatusNotFoundException
- DestinationParentNotFoundException
- DuplicateAccountException
- DuplicateHandshakeException
- DuplicateOrganizationalUnitException
- DuplicatePolicyAttachmentException
- DuplicatePolicyException
- EffectivePolicyNotFoundException
- FinalizingOrganizationException
- HandshakeAlreadyInStateException
- HandshakeConstraintViolationException
- HandshakeNotFoundException
- InvalidHandshakeTransitionException
- InvalidInputException
- MalformedPolicyDocumentException
- MasterCannotLeaveOrganizationException
- OrganizationNotEmptyException
- OrganizationalUnitNotEmptyException
- OrganizationalUnitNotFoundException
- ParentNotFoundException
- PolicyChangesInProgressException
- PolicyInUseException
- PolicyNotAttachedException
- PolicyNotFoundException
- PolicyTypeAlreadyEnabledException
- PolicyTypeNotAvailableForOrganizationException
- PolicyTypeNotEnabledException
- RootNotFoundException
- ServiceException
- SourceParentNotFoundException
- TargetNotFoundException
- TooManyRequestsException
- UnsupportedAPIEndpointException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("organizations").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_organizations.paginators import ListAWSServiceAccessForOrganizationPaginator, ...
```

- [ListAWSServiceAccessForOrganizationPaginator](./paginators.md#listawsserviceaccessfororganizationpaginator)
- [ListAccountsPaginator](./paginators.md#listaccountspaginator)
- [ListAccountsForParentPaginator](./paginators.md#listaccountsforparentpaginator)
- [ListChildrenPaginator](./paginators.md#listchildrenpaginator)
- [ListCreateAccountStatusPaginator](./paginators.md#listcreateaccountstatuspaginator)
- [ListDelegatedAdministratorsPaginator](./paginators.md#listdelegatedadministratorspaginator)
- [ListDelegatedServicesForAccountPaginator](./paginators.md#listdelegatedservicesforaccountpaginator)
- [ListHandshakesForAccountPaginator](./paginators.md#listhandshakesforaccountpaginator)
- [ListHandshakesForOrganizationPaginator](./paginators.md#listhandshakesfororganizationpaginator)
- [ListOrganizationalUnitsForParentPaginator](./paginators.md#listorganizationalunitsforparentpaginator)
- [ListParentsPaginator](./paginators.md#listparentspaginator)
- [ListPoliciesPaginator](./paginators.md#listpoliciespaginator)
- [ListPoliciesForTargetPaginator](./paginators.md#listpoliciesfortargetpaginator)
- [ListRootsPaginator](./paginators.md#listrootspaginator)
- [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- [ListTargetsForPolicyPaginator](./paginators.md#listtargetsforpolicypaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_organizations.literals import AccountJoinedMethodType, ...
```

- [AccountJoinedMethodType](./literals.md#accountjoinedmethodtype)
- [AccountStatusType](./literals.md#accountstatustype)
- [ActionTypeType](./literals.md#actiontypetype)
- [ChildTypeType](./literals.md#childtypetype)
- [CreateAccountFailureReasonType](./literals.md#createaccountfailurereasontype)
- [CreateAccountStateType](./literals.md#createaccountstatetype)
- [EffectivePolicyTypeType](./literals.md#effectivepolicytypetype)
- [HandshakePartyTypeType](./literals.md#handshakepartytypetype)
- [HandshakeResourceTypeType](./literals.md#handshakeresourcetypetype)
- [HandshakeStateType](./literals.md#handshakestatetype)
- [IAMUserAccessToBillingType](./literals.md#iamuseraccesstobillingtype)
- [ListAWSServiceAccessForOrganizationPaginatorName](./literals.md#listawsserviceaccessfororganizationpaginatorname)
- [ListAccountsForParentPaginatorName](./literals.md#listaccountsforparentpaginatorname)
- [ListAccountsPaginatorName](./literals.md#listaccountspaginatorname)
- [ListChildrenPaginatorName](./literals.md#listchildrenpaginatorname)
- [ListCreateAccountStatusPaginatorName](./literals.md#listcreateaccountstatuspaginatorname)
- [ListDelegatedAdministratorsPaginatorName](./literals.md#listdelegatedadministratorspaginatorname)
- [ListDelegatedServicesForAccountPaginatorName](./literals.md#listdelegatedservicesforaccountpaginatorname)
- [ListHandshakesForAccountPaginatorName](./literals.md#listhandshakesforaccountpaginatorname)
- [ListHandshakesForOrganizationPaginatorName](./literals.md#listhandshakesfororganizationpaginatorname)
- [ListOrganizationalUnitsForParentPaginatorName](./literals.md#listorganizationalunitsforparentpaginatorname)
- [ListParentsPaginatorName](./literals.md#listparentspaginatorname)
- [ListPoliciesForTargetPaginatorName](./literals.md#listpoliciesfortargetpaginatorname)
- [ListPoliciesPaginatorName](./literals.md#listpoliciespaginatorname)
- [ListRootsPaginatorName](./literals.md#listrootspaginatorname)
- [ListTagsForResourcePaginatorName](./literals.md#listtagsforresourcepaginatorname)
- [ListTargetsForPolicyPaginatorName](./literals.md#listtargetsforpolicypaginatorname)
- [OrganizationFeatureSetType](./literals.md#organizationfeaturesettype)
- [ParentTypeType](./literals.md#parenttypetype)
- [PolicyTypeStatusType](./literals.md#policytypestatustype)
- [PolicyTypeType](./literals.md#policytypetype)
- [TargetTypeType](./literals.md#targettypetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_organizations.type_defs import AcceptHandshakeRequestRequestTypeDef, ...
```

- [AcceptHandshakeRequestRequestTypeDef](./type_defs.md#accepthandshakerequestrequesttypedef)
- [AcceptHandshakeResponseTypeDef](./type_defs.md#accepthandshakeresponsetypedef)
- [AccountTypeDef](./type_defs.md#accounttypedef)
- [AttachPolicyRequestRequestTypeDef](./type_defs.md#attachpolicyrequestrequesttypedef)
- [CancelHandshakeRequestRequestTypeDef](./type_defs.md#cancelhandshakerequestrequesttypedef)
- [CancelHandshakeResponseTypeDef](./type_defs.md#cancelhandshakeresponsetypedef)
- [ChildTypeDef](./type_defs.md#childtypedef)
- [CreateAccountRequestRequestTypeDef](./type_defs.md#createaccountrequestrequesttypedef)
- [CreateAccountResponseTypeDef](./type_defs.md#createaccountresponsetypedef)
- [CreateAccountStatusTypeDef](./type_defs.md#createaccountstatustypedef)
- [CreateGovCloudAccountRequestRequestTypeDef](./type_defs.md#creategovcloudaccountrequestrequesttypedef)
- [CreateGovCloudAccountResponseTypeDef](./type_defs.md#creategovcloudaccountresponsetypedef)
- [CreateOrganizationRequestRequestTypeDef](./type_defs.md#createorganizationrequestrequesttypedef)
- [CreateOrganizationResponseTypeDef](./type_defs.md#createorganizationresponsetypedef)
- [CreateOrganizationalUnitRequestRequestTypeDef](./type_defs.md#createorganizationalunitrequestrequesttypedef)
- [CreateOrganizationalUnitResponseTypeDef](./type_defs.md#createorganizationalunitresponsetypedef)
- [CreatePolicyRequestRequestTypeDef](./type_defs.md#createpolicyrequestrequesttypedef)
- [CreatePolicyResponseTypeDef](./type_defs.md#createpolicyresponsetypedef)
- [DeclineHandshakeRequestRequestTypeDef](./type_defs.md#declinehandshakerequestrequesttypedef)
- [DeclineHandshakeResponseTypeDef](./type_defs.md#declinehandshakeresponsetypedef)
- [DelegatedAdministratorTypeDef](./type_defs.md#delegatedadministratortypedef)
- [DelegatedServiceTypeDef](./type_defs.md#delegatedservicetypedef)
- [DeleteOrganizationalUnitRequestRequestTypeDef](./type_defs.md#deleteorganizationalunitrequestrequesttypedef)
- [DeletePolicyRequestRequestTypeDef](./type_defs.md#deletepolicyrequestrequesttypedef)
- [DeregisterDelegatedAdministratorRequestRequestTypeDef](./type_defs.md#deregisterdelegatedadministratorrequestrequesttypedef)
- [DescribeAccountRequestRequestTypeDef](./type_defs.md#describeaccountrequestrequesttypedef)
- [DescribeAccountResponseTypeDef](./type_defs.md#describeaccountresponsetypedef)
- [DescribeCreateAccountStatusRequestRequestTypeDef](./type_defs.md#describecreateaccountstatusrequestrequesttypedef)
- [DescribeCreateAccountStatusResponseTypeDef](./type_defs.md#describecreateaccountstatusresponsetypedef)
- [DescribeEffectivePolicyRequestRequestTypeDef](./type_defs.md#describeeffectivepolicyrequestrequesttypedef)
- [DescribeEffectivePolicyResponseTypeDef](./type_defs.md#describeeffectivepolicyresponsetypedef)
- [DescribeHandshakeRequestRequestTypeDef](./type_defs.md#describehandshakerequestrequesttypedef)
- [DescribeHandshakeResponseTypeDef](./type_defs.md#describehandshakeresponsetypedef)
- [DescribeOrganizationResponseTypeDef](./type_defs.md#describeorganizationresponsetypedef)
- [DescribeOrganizationalUnitRequestRequestTypeDef](./type_defs.md#describeorganizationalunitrequestrequesttypedef)
- [DescribeOrganizationalUnitResponseTypeDef](./type_defs.md#describeorganizationalunitresponsetypedef)
- [DescribePolicyRequestRequestTypeDef](./type_defs.md#describepolicyrequestrequesttypedef)
- [DescribePolicyResponseTypeDef](./type_defs.md#describepolicyresponsetypedef)
- [DetachPolicyRequestRequestTypeDef](./type_defs.md#detachpolicyrequestrequesttypedef)
- [DisableAWSServiceAccessRequestRequestTypeDef](./type_defs.md#disableawsserviceaccessrequestrequesttypedef)
- [DisablePolicyTypeRequestRequestTypeDef](./type_defs.md#disablepolicytyperequestrequesttypedef)
- [DisablePolicyTypeResponseTypeDef](./type_defs.md#disablepolicytyperesponsetypedef)
- [EffectivePolicyTypeDef](./type_defs.md#effectivepolicytypedef)
- [EnableAWSServiceAccessRequestRequestTypeDef](./type_defs.md#enableawsserviceaccessrequestrequesttypedef)
- [EnableAllFeaturesResponseTypeDef](./type_defs.md#enableallfeaturesresponsetypedef)
- [EnablePolicyTypeRequestRequestTypeDef](./type_defs.md#enablepolicytyperequestrequesttypedef)
- [EnablePolicyTypeResponseTypeDef](./type_defs.md#enablepolicytyperesponsetypedef)
- [EnabledServicePrincipalTypeDef](./type_defs.md#enabledserviceprincipaltypedef)
- [HandshakeFilterTypeDef](./type_defs.md#handshakefiltertypedef)
- [HandshakePartyTypeDef](./type_defs.md#handshakepartytypedef)
- [HandshakeResourceTypeDef](./type_defs.md#handshakeresourcetypedef)
- [HandshakeTypeDef](./type_defs.md#handshaketypedef)
- [InviteAccountToOrganizationRequestRequestTypeDef](./type_defs.md#inviteaccounttoorganizationrequestrequesttypedef)
- [InviteAccountToOrganizationResponseTypeDef](./type_defs.md#inviteaccounttoorganizationresponsetypedef)
- [ListAWSServiceAccessForOrganizationRequestRequestTypeDef](./type_defs.md#listawsserviceaccessfororganizationrequestrequesttypedef)
- [ListAWSServiceAccessForOrganizationResponseTypeDef](./type_defs.md#listawsserviceaccessfororganizationresponsetypedef)
- [ListAccountsForParentRequestRequestTypeDef](./type_defs.md#listaccountsforparentrequestrequesttypedef)
- [ListAccountsForParentResponseTypeDef](./type_defs.md#listaccountsforparentresponsetypedef)
- [ListAccountsRequestRequestTypeDef](./type_defs.md#listaccountsrequestrequesttypedef)
- [ListAccountsResponseTypeDef](./type_defs.md#listaccountsresponsetypedef)
- [ListChildrenRequestRequestTypeDef](./type_defs.md#listchildrenrequestrequesttypedef)
- [ListChildrenResponseTypeDef](./type_defs.md#listchildrenresponsetypedef)
- [ListCreateAccountStatusRequestRequestTypeDef](./type_defs.md#listcreateaccountstatusrequestrequesttypedef)
- [ListCreateAccountStatusResponseTypeDef](./type_defs.md#listcreateaccountstatusresponsetypedef)
- [ListDelegatedAdministratorsRequestRequestTypeDef](./type_defs.md#listdelegatedadministratorsrequestrequesttypedef)
- [ListDelegatedAdministratorsResponseTypeDef](./type_defs.md#listdelegatedadministratorsresponsetypedef)
- [ListDelegatedServicesForAccountRequestRequestTypeDef](./type_defs.md#listdelegatedservicesforaccountrequestrequesttypedef)
- [ListDelegatedServicesForAccountResponseTypeDef](./type_defs.md#listdelegatedservicesforaccountresponsetypedef)
- [ListHandshakesForAccountRequestRequestTypeDef](./type_defs.md#listhandshakesforaccountrequestrequesttypedef)
- [ListHandshakesForAccountResponseTypeDef](./type_defs.md#listhandshakesforaccountresponsetypedef)
- [ListHandshakesForOrganizationRequestRequestTypeDef](./type_defs.md#listhandshakesfororganizationrequestrequesttypedef)
- [ListHandshakesForOrganizationResponseTypeDef](./type_defs.md#listhandshakesfororganizationresponsetypedef)
- [ListOrganizationalUnitsForParentRequestRequestTypeDef](./type_defs.md#listorganizationalunitsforparentrequestrequesttypedef)
- [ListOrganizationalUnitsForParentResponseTypeDef](./type_defs.md#listorganizationalunitsforparentresponsetypedef)
- [ListParentsRequestRequestTypeDef](./type_defs.md#listparentsrequestrequesttypedef)
- [ListParentsResponseTypeDef](./type_defs.md#listparentsresponsetypedef)
- [ListPoliciesForTargetRequestRequestTypeDef](./type_defs.md#listpoliciesfortargetrequestrequesttypedef)
- [ListPoliciesForTargetResponseTypeDef](./type_defs.md#listpoliciesfortargetresponsetypedef)
- [ListPoliciesRequestRequestTypeDef](./type_defs.md#listpoliciesrequestrequesttypedef)
- [ListPoliciesResponseTypeDef](./type_defs.md#listpoliciesresponsetypedef)
- [ListRootsRequestRequestTypeDef](./type_defs.md#listrootsrequestrequesttypedef)
- [ListRootsResponseTypeDef](./type_defs.md#listrootsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListTargetsForPolicyRequestRequestTypeDef](./type_defs.md#listtargetsforpolicyrequestrequesttypedef)
- [ListTargetsForPolicyResponseTypeDef](./type_defs.md#listtargetsforpolicyresponsetypedef)
- [MoveAccountRequestRequestTypeDef](./type_defs.md#moveaccountrequestrequesttypedef)
- [OrganizationTypeDef](./type_defs.md#organizationtypedef)
- [OrganizationalUnitTypeDef](./type_defs.md#organizationalunittypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ParentTypeDef](./type_defs.md#parenttypedef)
- [PolicySummaryTypeDef](./type_defs.md#policysummarytypedef)
- [PolicyTargetSummaryTypeDef](./type_defs.md#policytargetsummarytypedef)
- [PolicyTypeDef](./type_defs.md#policytypedef)
- [PolicyTypeSummaryTypeDef](./type_defs.md#policytypesummarytypedef)
- [RegisterDelegatedAdministratorRequestRequestTypeDef](./type_defs.md#registerdelegatedadministratorrequestrequesttypedef)
- [RemoveAccountFromOrganizationRequestRequestTypeDef](./type_defs.md#removeaccountfromorganizationrequestrequesttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RootTypeDef](./type_defs.md#roottypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateOrganizationalUnitRequestRequestTypeDef](./type_defs.md#updateorganizationalunitrequestrequesttypedef)
- [UpdateOrganizationalUnitResponseTypeDef](./type_defs.md#updateorganizationalunitresponsetypedef)
- [UpdatePolicyRequestRequestTypeDef](./type_defs.md#updatepolicyrequestrequesttypedef)
- [UpdatePolicyResponseTypeDef](./type_defs.md#updatepolicyresponsetypedef)
