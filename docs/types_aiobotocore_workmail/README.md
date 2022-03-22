<a id="type-annotations-for-aiobotocore-workmail-module"></a>

# Type annotations for aiobotocore WorkMail module

> [Index](../README.md) > WorkMail

Auto-generated documentation for
[WorkMail](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail)
type annotations stubs module
[types-aiobotocore-workmail](https://pypi.org/project/types-aiobotocore-workmail/).

- [Type annotations for aiobotocore WorkMail module](#type-annotations-for-aiobotocore-workmail-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [WorkMailClient](#workmailclient)
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

Click `Modify` and select `boto3 common` and `WorkMail`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `WorkMail` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[workmail]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[workmail]'


# standalone installation
python -m pip install types-aiobotocore-workmail
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-workmail
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="workmailclient"></a>

## WorkMailClient

Type annotations for `session.create_client("workmail")` as
[WorkMailClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_workmail.client import WorkMailClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [associate_delegate_to_resource](./client.md#associate_delegate_to_resource)
- [associate_member_to_group](./client.md#associate_member_to_group)
- [can_paginate](./client.md#can_paginate)
- [cancel_mailbox_export_job](./client.md#cancel_mailbox_export_job)
- [create_alias](./client.md#create_alias)
- [create_group](./client.md#create_group)
- [create_mobile_device_access_rule](./client.md#create_mobile_device_access_rule)
- [create_organization](./client.md#create_organization)
- [create_resource](./client.md#create_resource)
- [create_user](./client.md#create_user)
- [delete_access_control_rule](./client.md#delete_access_control_rule)
- [delete_alias](./client.md#delete_alias)
- [delete_email_monitoring_configuration](./client.md#delete_email_monitoring_configuration)
- [delete_group](./client.md#delete_group)
- [delete_mailbox_permissions](./client.md#delete_mailbox_permissions)
- [delete_mobile_device_access_override](./client.md#delete_mobile_device_access_override)
- [delete_mobile_device_access_rule](./client.md#delete_mobile_device_access_rule)
- [delete_organization](./client.md#delete_organization)
- [delete_resource](./client.md#delete_resource)
- [delete_retention_policy](./client.md#delete_retention_policy)
- [delete_user](./client.md#delete_user)
- [deregister_from_work_mail](./client.md#deregister_from_work_mail)
- [deregister_mail_domain](./client.md#deregister_mail_domain)
- [describe_email_monitoring_configuration](./client.md#describe_email_monitoring_configuration)
- [describe_group](./client.md#describe_group)
- [describe_inbound_dmarc_settings](./client.md#describe_inbound_dmarc_settings)
- [describe_mailbox_export_job](./client.md#describe_mailbox_export_job)
- [describe_organization](./client.md#describe_organization)
- [describe_resource](./client.md#describe_resource)
- [describe_user](./client.md#describe_user)
- [disassociate_delegate_from_resource](./client.md#disassociate_delegate_from_resource)
- [disassociate_member_from_group](./client.md#disassociate_member_from_group)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_access_control_effect](./client.md#get_access_control_effect)
- [get_default_retention_policy](./client.md#get_default_retention_policy)
- [get_mail_domain](./client.md#get_mail_domain)
- [get_mailbox_details](./client.md#get_mailbox_details)
- [get_mobile_device_access_effect](./client.md#get_mobile_device_access_effect)
- [get_mobile_device_access_override](./client.md#get_mobile_device_access_override)
- [get_paginator](./client.md#get_paginator)
- [list_access_control_rules](./client.md#list_access_control_rules)
- [list_aliases](./client.md#list_aliases)
- [list_group_members](./client.md#list_group_members)
- [list_groups](./client.md#list_groups)
- [list_mail_domains](./client.md#list_mail_domains)
- [list_mailbox_export_jobs](./client.md#list_mailbox_export_jobs)
- [list_mailbox_permissions](./client.md#list_mailbox_permissions)
- [list_mobile_device_access_overrides](./client.md#list_mobile_device_access_overrides)
- [list_mobile_device_access_rules](./client.md#list_mobile_device_access_rules)
- [list_organizations](./client.md#list_organizations)
- [list_resource_delegates](./client.md#list_resource_delegates)
- [list_resources](./client.md#list_resources)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [list_users](./client.md#list_users)
- [put_access_control_rule](./client.md#put_access_control_rule)
- [put_email_monitoring_configuration](./client.md#put_email_monitoring_configuration)
- [put_inbound_dmarc_settings](./client.md#put_inbound_dmarc_settings)
- [put_mailbox_permissions](./client.md#put_mailbox_permissions)
- [put_mobile_device_access_override](./client.md#put_mobile_device_access_override)
- [put_retention_policy](./client.md#put_retention_policy)
- [register_mail_domain](./client.md#register_mail_domain)
- [register_to_work_mail](./client.md#register_to_work_mail)
- [reset_password](./client.md#reset_password)
- [start_mailbox_export_job](./client.md#start_mailbox_export_job)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_default_mail_domain](./client.md#update_default_mail_domain)
- [update_mailbox_quota](./client.md#update_mailbox_quota)
- [update_mobile_device_access_rule](./client.md#update_mobile_device_access_rule)
- [update_primary_email_address](./client.md#update_primary_email_address)
- [update_resource](./client.md#update_resource)

<a id="exceptions"></a>

### Exceptions

WorkMailClient [exceptions](./client.md#exceptions)

- ClientError
- DirectoryInUseException
- DirectoryServiceAuthenticationFailedException
- DirectoryUnavailableException
- EmailAddressInUseException
- EntityAlreadyRegisteredException
- EntityNotFoundException
- EntityStateException
- InvalidConfigurationException
- InvalidCustomSesConfigurationException
- InvalidParameterException
- InvalidPasswordException
- LimitExceededException
- MailDomainInUseException
- MailDomainNotFoundException
- MailDomainStateException
- NameAvailabilityException
- OrganizationNotFoundException
- OrganizationStateException
- ReservedNameException
- ResourceNotFoundException
- TooManyTagsException
- UnsupportedOperationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("workmail").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_workmail.paginator import ListAliasesPaginator, ...
```

- [ListAliasesPaginator](./paginators.md#listaliasespaginator)
- [ListGroupMembersPaginator](./paginators.md#listgroupmemberspaginator)
- [ListGroupsPaginator](./paginators.md#listgroupspaginator)
- [ListMailboxPermissionsPaginator](./paginators.md#listmailboxpermissionspaginator)
- [ListOrganizationsPaginator](./paginators.md#listorganizationspaginator)
- [ListResourceDelegatesPaginator](./paginators.md#listresourcedelegatespaginator)
- [ListResourcesPaginator](./paginators.md#listresourcespaginator)
- [ListUsersPaginator](./paginators.md#listuserspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_workmail.literals import AccessControlRuleEffectType, ...
```

- [AccessControlRuleEffectType](./literals.md#accesscontrolruleeffecttype)
- [DnsRecordVerificationStatusType](./literals.md#dnsrecordverificationstatustype)
- [EntityStateType](./literals.md#entitystatetype)
- [FolderNameType](./literals.md#foldernametype)
- [ListAliasesPaginatorName](./literals.md#listaliasespaginatorname)
- [ListGroupMembersPaginatorName](./literals.md#listgroupmemberspaginatorname)
- [ListGroupsPaginatorName](./literals.md#listgroupspaginatorname)
- [ListMailboxPermissionsPaginatorName](./literals.md#listmailboxpermissionspaginatorname)
- [ListOrganizationsPaginatorName](./literals.md#listorganizationspaginatorname)
- [ListResourceDelegatesPaginatorName](./literals.md#listresourcedelegatespaginatorname)
- [ListResourcesPaginatorName](./literals.md#listresourcespaginatorname)
- [ListUsersPaginatorName](./literals.md#listuserspaginatorname)
- [MailboxExportJobStateType](./literals.md#mailboxexportjobstatetype)
- [MemberTypeType](./literals.md#membertypetype)
- [MobileDeviceAccessRuleEffectType](./literals.md#mobiledeviceaccessruleeffecttype)
- [PermissionTypeType](./literals.md#permissiontypetype)
- [ResourceTypeType](./literals.md#resourcetypetype)
- [RetentionActionType](./literals.md#retentionactiontype)
- [UserRoleType](./literals.md#userroletype)
- [WorkMailServiceName](./literals.md#workmailservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_workmail.type_defs import AccessControlRuleTypeDef, ...
```

- [AccessControlRuleTypeDef](./type_defs.md#accesscontrolruletypedef)
- [AssociateDelegateToResourceRequestRequestTypeDef](./type_defs.md#associatedelegatetoresourcerequestrequesttypedef)
- [AssociateMemberToGroupRequestRequestTypeDef](./type_defs.md#associatemembertogrouprequestrequesttypedef)
- [BookingOptionsTypeDef](./type_defs.md#bookingoptionstypedef)
- [CancelMailboxExportJobRequestRequestTypeDef](./type_defs.md#cancelmailboxexportjobrequestrequesttypedef)
- [CreateAliasRequestRequestTypeDef](./type_defs.md#createaliasrequestrequesttypedef)
- [CreateGroupRequestRequestTypeDef](./type_defs.md#creategrouprequestrequesttypedef)
- [CreateGroupResponseTypeDef](./type_defs.md#creategroupresponsetypedef)
- [CreateMobileDeviceAccessRuleRequestRequestTypeDef](./type_defs.md#createmobiledeviceaccessrulerequestrequesttypedef)
- [CreateMobileDeviceAccessRuleResponseTypeDef](./type_defs.md#createmobiledeviceaccessruleresponsetypedef)
- [CreateOrganizationRequestRequestTypeDef](./type_defs.md#createorganizationrequestrequesttypedef)
- [CreateOrganizationResponseTypeDef](./type_defs.md#createorganizationresponsetypedef)
- [CreateResourceRequestRequestTypeDef](./type_defs.md#createresourcerequestrequesttypedef)
- [CreateResourceResponseTypeDef](./type_defs.md#createresourceresponsetypedef)
- [CreateUserRequestRequestTypeDef](./type_defs.md#createuserrequestrequesttypedef)
- [CreateUserResponseTypeDef](./type_defs.md#createuserresponsetypedef)
- [DelegateTypeDef](./type_defs.md#delegatetypedef)
- [DeleteAccessControlRuleRequestRequestTypeDef](./type_defs.md#deleteaccesscontrolrulerequestrequesttypedef)
- [DeleteAliasRequestRequestTypeDef](./type_defs.md#deletealiasrequestrequesttypedef)
- [DeleteEmailMonitoringConfigurationRequestRequestTypeDef](./type_defs.md#deleteemailmonitoringconfigurationrequestrequesttypedef)
- [DeleteGroupRequestRequestTypeDef](./type_defs.md#deletegrouprequestrequesttypedef)
- [DeleteMailboxPermissionsRequestRequestTypeDef](./type_defs.md#deletemailboxpermissionsrequestrequesttypedef)
- [DeleteMobileDeviceAccessOverrideRequestRequestTypeDef](./type_defs.md#deletemobiledeviceaccessoverriderequestrequesttypedef)
- [DeleteMobileDeviceAccessRuleRequestRequestTypeDef](./type_defs.md#deletemobiledeviceaccessrulerequestrequesttypedef)
- [DeleteOrganizationRequestRequestTypeDef](./type_defs.md#deleteorganizationrequestrequesttypedef)
- [DeleteOrganizationResponseTypeDef](./type_defs.md#deleteorganizationresponsetypedef)
- [DeleteResourceRequestRequestTypeDef](./type_defs.md#deleteresourcerequestrequesttypedef)
- [DeleteRetentionPolicyRequestRequestTypeDef](./type_defs.md#deleteretentionpolicyrequestrequesttypedef)
- [DeleteUserRequestRequestTypeDef](./type_defs.md#deleteuserrequestrequesttypedef)
- [DeregisterFromWorkMailRequestRequestTypeDef](./type_defs.md#deregisterfromworkmailrequestrequesttypedef)
- [DeregisterMailDomainRequestRequestTypeDef](./type_defs.md#deregistermaildomainrequestrequesttypedef)
- [DescribeEmailMonitoringConfigurationRequestRequestTypeDef](./type_defs.md#describeemailmonitoringconfigurationrequestrequesttypedef)
- [DescribeEmailMonitoringConfigurationResponseTypeDef](./type_defs.md#describeemailmonitoringconfigurationresponsetypedef)
- [DescribeGroupRequestRequestTypeDef](./type_defs.md#describegrouprequestrequesttypedef)
- [DescribeGroupResponseTypeDef](./type_defs.md#describegroupresponsetypedef)
- [DescribeInboundDmarcSettingsRequestRequestTypeDef](./type_defs.md#describeinbounddmarcsettingsrequestrequesttypedef)
- [DescribeInboundDmarcSettingsResponseTypeDef](./type_defs.md#describeinbounddmarcsettingsresponsetypedef)
- [DescribeMailboxExportJobRequestRequestTypeDef](./type_defs.md#describemailboxexportjobrequestrequesttypedef)
- [DescribeMailboxExportJobResponseTypeDef](./type_defs.md#describemailboxexportjobresponsetypedef)
- [DescribeOrganizationRequestRequestTypeDef](./type_defs.md#describeorganizationrequestrequesttypedef)
- [DescribeOrganizationResponseTypeDef](./type_defs.md#describeorganizationresponsetypedef)
- [DescribeResourceRequestRequestTypeDef](./type_defs.md#describeresourcerequestrequesttypedef)
- [DescribeResourceResponseTypeDef](./type_defs.md#describeresourceresponsetypedef)
- [DescribeUserRequestRequestTypeDef](./type_defs.md#describeuserrequestrequesttypedef)
- [DescribeUserResponseTypeDef](./type_defs.md#describeuserresponsetypedef)
- [DisassociateDelegateFromResourceRequestRequestTypeDef](./type_defs.md#disassociatedelegatefromresourcerequestrequesttypedef)
- [DisassociateMemberFromGroupRequestRequestTypeDef](./type_defs.md#disassociatememberfromgrouprequestrequesttypedef)
- [DnsRecordTypeDef](./type_defs.md#dnsrecordtypedef)
- [DomainTypeDef](./type_defs.md#domaintypedef)
- [FolderConfigurationTypeDef](./type_defs.md#folderconfigurationtypedef)
- [GetAccessControlEffectRequestRequestTypeDef](./type_defs.md#getaccesscontroleffectrequestrequesttypedef)
- [GetAccessControlEffectResponseTypeDef](./type_defs.md#getaccesscontroleffectresponsetypedef)
- [GetDefaultRetentionPolicyRequestRequestTypeDef](./type_defs.md#getdefaultretentionpolicyrequestrequesttypedef)
- [GetDefaultRetentionPolicyResponseTypeDef](./type_defs.md#getdefaultretentionpolicyresponsetypedef)
- [GetMailDomainRequestRequestTypeDef](./type_defs.md#getmaildomainrequestrequesttypedef)
- [GetMailDomainResponseTypeDef](./type_defs.md#getmaildomainresponsetypedef)
- [GetMailboxDetailsRequestRequestTypeDef](./type_defs.md#getmailboxdetailsrequestrequesttypedef)
- [GetMailboxDetailsResponseTypeDef](./type_defs.md#getmailboxdetailsresponsetypedef)
- [GetMobileDeviceAccessEffectRequestRequestTypeDef](./type_defs.md#getmobiledeviceaccesseffectrequestrequesttypedef)
- [GetMobileDeviceAccessEffectResponseTypeDef](./type_defs.md#getmobiledeviceaccesseffectresponsetypedef)
- [GetMobileDeviceAccessOverrideRequestRequestTypeDef](./type_defs.md#getmobiledeviceaccessoverriderequestrequesttypedef)
- [GetMobileDeviceAccessOverrideResponseTypeDef](./type_defs.md#getmobiledeviceaccessoverrideresponsetypedef)
- [GroupTypeDef](./type_defs.md#grouptypedef)
- [ListAccessControlRulesRequestRequestTypeDef](./type_defs.md#listaccesscontrolrulesrequestrequesttypedef)
- [ListAccessControlRulesResponseTypeDef](./type_defs.md#listaccesscontrolrulesresponsetypedef)
- [ListAliasesRequestRequestTypeDef](./type_defs.md#listaliasesrequestrequesttypedef)
- [ListAliasesResponseTypeDef](./type_defs.md#listaliasesresponsetypedef)
- [ListGroupMembersRequestRequestTypeDef](./type_defs.md#listgroupmembersrequestrequesttypedef)
- [ListGroupMembersResponseTypeDef](./type_defs.md#listgroupmembersresponsetypedef)
- [ListGroupsRequestRequestTypeDef](./type_defs.md#listgroupsrequestrequesttypedef)
- [ListGroupsResponseTypeDef](./type_defs.md#listgroupsresponsetypedef)
- [ListMailDomainsRequestRequestTypeDef](./type_defs.md#listmaildomainsrequestrequesttypedef)
- [ListMailDomainsResponseTypeDef](./type_defs.md#listmaildomainsresponsetypedef)
- [ListMailboxExportJobsRequestRequestTypeDef](./type_defs.md#listmailboxexportjobsrequestrequesttypedef)
- [ListMailboxExportJobsResponseTypeDef](./type_defs.md#listmailboxexportjobsresponsetypedef)
- [ListMailboxPermissionsRequestRequestTypeDef](./type_defs.md#listmailboxpermissionsrequestrequesttypedef)
- [ListMailboxPermissionsResponseTypeDef](./type_defs.md#listmailboxpermissionsresponsetypedef)
- [ListMobileDeviceAccessOverridesRequestRequestTypeDef](./type_defs.md#listmobiledeviceaccessoverridesrequestrequesttypedef)
- [ListMobileDeviceAccessOverridesResponseTypeDef](./type_defs.md#listmobiledeviceaccessoverridesresponsetypedef)
- [ListMobileDeviceAccessRulesRequestRequestTypeDef](./type_defs.md#listmobiledeviceaccessrulesrequestrequesttypedef)
- [ListMobileDeviceAccessRulesResponseTypeDef](./type_defs.md#listmobiledeviceaccessrulesresponsetypedef)
- [ListOrganizationsRequestRequestTypeDef](./type_defs.md#listorganizationsrequestrequesttypedef)
- [ListOrganizationsResponseTypeDef](./type_defs.md#listorganizationsresponsetypedef)
- [ListResourceDelegatesRequestRequestTypeDef](./type_defs.md#listresourcedelegatesrequestrequesttypedef)
- [ListResourceDelegatesResponseTypeDef](./type_defs.md#listresourcedelegatesresponsetypedef)
- [ListResourcesRequestRequestTypeDef](./type_defs.md#listresourcesrequestrequesttypedef)
- [ListResourcesResponseTypeDef](./type_defs.md#listresourcesresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListUsersRequestRequestTypeDef](./type_defs.md#listusersrequestrequesttypedef)
- [ListUsersResponseTypeDef](./type_defs.md#listusersresponsetypedef)
- [MailDomainSummaryTypeDef](./type_defs.md#maildomainsummarytypedef)
- [MailboxExportJobTypeDef](./type_defs.md#mailboxexportjobtypedef)
- [MemberTypeDef](./type_defs.md#membertypedef)
- [MobileDeviceAccessMatchedRuleTypeDef](./type_defs.md#mobiledeviceaccessmatchedruletypedef)
- [MobileDeviceAccessOverrideTypeDef](./type_defs.md#mobiledeviceaccessoverridetypedef)
- [MobileDeviceAccessRuleTypeDef](./type_defs.md#mobiledeviceaccessruletypedef)
- [OrganizationSummaryTypeDef](./type_defs.md#organizationsummarytypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PermissionTypeDef](./type_defs.md#permissiontypedef)
- [PutAccessControlRuleRequestRequestTypeDef](./type_defs.md#putaccesscontrolrulerequestrequesttypedef)
- [PutEmailMonitoringConfigurationRequestRequestTypeDef](./type_defs.md#putemailmonitoringconfigurationrequestrequesttypedef)
- [PutInboundDmarcSettingsRequestRequestTypeDef](./type_defs.md#putinbounddmarcsettingsrequestrequesttypedef)
- [PutMailboxPermissionsRequestRequestTypeDef](./type_defs.md#putmailboxpermissionsrequestrequesttypedef)
- [PutMobileDeviceAccessOverrideRequestRequestTypeDef](./type_defs.md#putmobiledeviceaccessoverriderequestrequesttypedef)
- [PutRetentionPolicyRequestRequestTypeDef](./type_defs.md#putretentionpolicyrequestrequesttypedef)
- [RegisterMailDomainRequestRequestTypeDef](./type_defs.md#registermaildomainrequestrequesttypedef)
- [RegisterToWorkMailRequestRequestTypeDef](./type_defs.md#registertoworkmailrequestrequesttypedef)
- [ResetPasswordRequestRequestTypeDef](./type_defs.md#resetpasswordrequestrequesttypedef)
- [ResourceTypeDef](./type_defs.md#resourcetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartMailboxExportJobRequestRequestTypeDef](./type_defs.md#startmailboxexportjobrequestrequesttypedef)
- [StartMailboxExportJobResponseTypeDef](./type_defs.md#startmailboxexportjobresponsetypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateDefaultMailDomainRequestRequestTypeDef](./type_defs.md#updatedefaultmaildomainrequestrequesttypedef)
- [UpdateMailboxQuotaRequestRequestTypeDef](./type_defs.md#updatemailboxquotarequestrequesttypedef)
- [UpdateMobileDeviceAccessRuleRequestRequestTypeDef](./type_defs.md#updatemobiledeviceaccessrulerequestrequesttypedef)
- [UpdatePrimaryEmailAddressRequestRequestTypeDef](./type_defs.md#updateprimaryemailaddressrequestrequesttypedef)
- [UpdateResourceRequestRequestTypeDef](./type_defs.md#updateresourcerequestrequesttypedef)
- [UserTypeDef](./type_defs.md#usertypedef)
