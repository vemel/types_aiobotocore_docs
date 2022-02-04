<a id="typed-dictionaries-for-aiobotocore-iam-module"></a>

# Typed dictionaries for aiobotocore IAM module

> [Index](..) > [IAM](.) > Typed dictionaries

Auto-generated documentation for
[IAM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM)
type annotations stubs module
[types-aiobotocore-iam](https://pypi.org/project/types-aiobotocore-iam/).

- [Typed dictionaries for aiobotocore IAM module](#typed-dictionaries-for-aiobotocore-iam-module)
  - [AccessDetailTypeDef](#accessdetailtypedef)
  - [AccessKeyLastUsedTypeDef](#accesskeylastusedtypedef)
  - [AccessKeyMetadataTypeDef](#accesskeymetadatatypedef)
  - [AccessKeyTypeDef](#accesskeytypedef)
  - [AddClientIDToOpenIDConnectProviderRequestRequestTypeDef](#addclientidtoopenidconnectproviderrequestrequesttypedef)
  - [AddRoleToInstanceProfileRequestInstanceProfileTypeDef](#addroletoinstanceprofilerequestinstanceprofiletypedef)
  - [AddRoleToInstanceProfileRequestRequestTypeDef](#addroletoinstanceprofilerequestrequesttypedef)
  - [AddUserToGroupRequestGroupTypeDef](#addusertogrouprequestgrouptypedef)
  - [AddUserToGroupRequestRequestTypeDef](#addusertogrouprequestrequesttypedef)
  - [AddUserToGroupRequestUserTypeDef](#addusertogrouprequestusertypedef)
  - [AttachGroupPolicyRequestGroupTypeDef](#attachgrouppolicyrequestgrouptypedef)
  - [AttachGroupPolicyRequestPolicyTypeDef](#attachgrouppolicyrequestpolicytypedef)
  - [AttachGroupPolicyRequestRequestTypeDef](#attachgrouppolicyrequestrequesttypedef)
  - [AttachRolePolicyRequestPolicyTypeDef](#attachrolepolicyrequestpolicytypedef)
  - [AttachRolePolicyRequestRequestTypeDef](#attachrolepolicyrequestrequesttypedef)
  - [AttachRolePolicyRequestRoleTypeDef](#attachrolepolicyrequestroletypedef)
  - [AttachUserPolicyRequestPolicyTypeDef](#attachuserpolicyrequestpolicytypedef)
  - [AttachUserPolicyRequestRequestTypeDef](#attachuserpolicyrequestrequesttypedef)
  - [AttachUserPolicyRequestUserTypeDef](#attachuserpolicyrequestusertypedef)
  - [AttachedPermissionsBoundaryResponseMetadataTypeDef](#attachedpermissionsboundaryresponsemetadatatypedef)
  - [AttachedPermissionsBoundaryTypeDef](#attachedpermissionsboundarytypedef)
  - [AttachedPolicyTypeDef](#attachedpolicytypedef)
  - [ChangePasswordRequestRequestTypeDef](#changepasswordrequestrequesttypedef)
  - [ChangePasswordRequestServiceResourceTypeDef](#changepasswordrequestserviceresourcetypedef)
  - [ContextEntryTypeDef](#contextentrytypedef)
  - [CreateAccessKeyRequestRequestTypeDef](#createaccesskeyrequestrequesttypedef)
  - [CreateAccessKeyResponseTypeDef](#createaccesskeyresponsetypedef)
  - [CreateAccountAliasRequestRequestTypeDef](#createaccountaliasrequestrequesttypedef)
  - [CreateAccountAliasRequestServiceResourceTypeDef](#createaccountaliasrequestserviceresourcetypedef)
  - [CreateGroupRequestGroupTypeDef](#creategrouprequestgrouptypedef)
  - [CreateGroupRequestRequestTypeDef](#creategrouprequestrequesttypedef)
  - [CreateGroupRequestServiceResourceTypeDef](#creategrouprequestserviceresourcetypedef)
  - [CreateGroupResponseTypeDef](#creategroupresponsetypedef)
  - [CreateInstanceProfileRequestRequestTypeDef](#createinstanceprofilerequestrequesttypedef)
  - [CreateInstanceProfileRequestServiceResourceTypeDef](#createinstanceprofilerequestserviceresourcetypedef)
  - [CreateInstanceProfileResponseTypeDef](#createinstanceprofileresponsetypedef)
  - [CreateLoginProfileRequestLoginProfileTypeDef](#createloginprofilerequestloginprofiletypedef)
  - [CreateLoginProfileRequestRequestTypeDef](#createloginprofilerequestrequesttypedef)
  - [CreateLoginProfileRequestUserTypeDef](#createloginprofilerequestusertypedef)
  - [CreateLoginProfileResponseTypeDef](#createloginprofileresponsetypedef)
  - [CreateOpenIDConnectProviderRequestRequestTypeDef](#createopenidconnectproviderrequestrequesttypedef)
  - [CreateOpenIDConnectProviderResponseTypeDef](#createopenidconnectproviderresponsetypedef)
  - [CreatePolicyRequestRequestTypeDef](#createpolicyrequestrequesttypedef)
  - [CreatePolicyRequestServiceResourceTypeDef](#createpolicyrequestserviceresourcetypedef)
  - [CreatePolicyResponseTypeDef](#createpolicyresponsetypedef)
  - [CreatePolicyVersionRequestPolicyTypeDef](#createpolicyversionrequestpolicytypedef)
  - [CreatePolicyVersionRequestRequestTypeDef](#createpolicyversionrequestrequesttypedef)
  - [CreatePolicyVersionResponseTypeDef](#createpolicyversionresponsetypedef)
  - [CreateRoleRequestRequestTypeDef](#createrolerequestrequesttypedef)
  - [CreateRoleRequestServiceResourceTypeDef](#createrolerequestserviceresourcetypedef)
  - [CreateRoleResponseTypeDef](#createroleresponsetypedef)
  - [CreateSAMLProviderRequestRequestTypeDef](#createsamlproviderrequestrequesttypedef)
  - [CreateSAMLProviderRequestServiceResourceTypeDef](#createsamlproviderrequestserviceresourcetypedef)
  - [CreateSAMLProviderResponseTypeDef](#createsamlproviderresponsetypedef)
  - [CreateServiceLinkedRoleRequestRequestTypeDef](#createservicelinkedrolerequestrequesttypedef)
  - [CreateServiceLinkedRoleResponseTypeDef](#createservicelinkedroleresponsetypedef)
  - [CreateServiceSpecificCredentialRequestRequestTypeDef](#createservicespecificcredentialrequestrequesttypedef)
  - [CreateServiceSpecificCredentialResponseTypeDef](#createservicespecificcredentialresponsetypedef)
  - [CreateUserRequestRequestTypeDef](#createuserrequestrequesttypedef)
  - [CreateUserRequestServiceResourceTypeDef](#createuserrequestserviceresourcetypedef)
  - [CreateUserRequestUserTypeDef](#createuserrequestusertypedef)
  - [CreateUserResponseTypeDef](#createuserresponsetypedef)
  - [CreateVirtualMFADeviceRequestRequestTypeDef](#createvirtualmfadevicerequestrequesttypedef)
  - [CreateVirtualMFADeviceRequestServiceResourceTypeDef](#createvirtualmfadevicerequestserviceresourcetypedef)
  - [CreateVirtualMFADeviceResponseTypeDef](#createvirtualmfadeviceresponsetypedef)
  - [DeactivateMFADeviceRequestRequestTypeDef](#deactivatemfadevicerequestrequesttypedef)
  - [DeleteAccessKeyRequestRequestTypeDef](#deleteaccesskeyrequestrequesttypedef)
  - [DeleteAccountAliasRequestRequestTypeDef](#deleteaccountaliasrequestrequesttypedef)
  - [DeleteGroupPolicyRequestRequestTypeDef](#deletegrouppolicyrequestrequesttypedef)
  - [DeleteGroupRequestRequestTypeDef](#deletegrouprequestrequesttypedef)
  - [DeleteInstanceProfileRequestRequestTypeDef](#deleteinstanceprofilerequestrequesttypedef)
  - [DeleteLoginProfileRequestRequestTypeDef](#deleteloginprofilerequestrequesttypedef)
  - [DeleteOpenIDConnectProviderRequestRequestTypeDef](#deleteopenidconnectproviderrequestrequesttypedef)
  - [DeletePolicyRequestRequestTypeDef](#deletepolicyrequestrequesttypedef)
  - [DeletePolicyVersionRequestRequestTypeDef](#deletepolicyversionrequestrequesttypedef)
  - [DeleteRolePermissionsBoundaryRequestRequestTypeDef](#deleterolepermissionsboundaryrequestrequesttypedef)
  - [DeleteRolePolicyRequestRequestTypeDef](#deleterolepolicyrequestrequesttypedef)
  - [DeleteRoleRequestRequestTypeDef](#deleterolerequestrequesttypedef)
  - [DeleteSAMLProviderRequestRequestTypeDef](#deletesamlproviderrequestrequesttypedef)
  - [DeleteSSHPublicKeyRequestRequestTypeDef](#deletesshpublickeyrequestrequesttypedef)
  - [DeleteServerCertificateRequestRequestTypeDef](#deleteservercertificaterequestrequesttypedef)
  - [DeleteServiceLinkedRoleRequestRequestTypeDef](#deleteservicelinkedrolerequestrequesttypedef)
  - [DeleteServiceLinkedRoleResponseTypeDef](#deleteservicelinkedroleresponsetypedef)
  - [DeleteServiceSpecificCredentialRequestRequestTypeDef](#deleteservicespecificcredentialrequestrequesttypedef)
  - [DeleteSigningCertificateRequestRequestTypeDef](#deletesigningcertificaterequestrequesttypedef)
  - [DeleteUserPermissionsBoundaryRequestRequestTypeDef](#deleteuserpermissionsboundaryrequestrequesttypedef)
  - [DeleteUserPolicyRequestRequestTypeDef](#deleteuserpolicyrequestrequesttypedef)
  - [DeleteUserRequestRequestTypeDef](#deleteuserrequestrequesttypedef)
  - [DeleteVirtualMFADeviceRequestRequestTypeDef](#deletevirtualmfadevicerequestrequesttypedef)
  - [DeletionTaskFailureReasonTypeTypeDef](#deletiontaskfailurereasontypetypedef)
  - [DetachGroupPolicyRequestGroupTypeDef](#detachgrouppolicyrequestgrouptypedef)
  - [DetachGroupPolicyRequestPolicyTypeDef](#detachgrouppolicyrequestpolicytypedef)
  - [DetachGroupPolicyRequestRequestTypeDef](#detachgrouppolicyrequestrequesttypedef)
  - [DetachRolePolicyRequestPolicyTypeDef](#detachrolepolicyrequestpolicytypedef)
  - [DetachRolePolicyRequestRequestTypeDef](#detachrolepolicyrequestrequesttypedef)
  - [DetachRolePolicyRequestRoleTypeDef](#detachrolepolicyrequestroletypedef)
  - [DetachUserPolicyRequestPolicyTypeDef](#detachuserpolicyrequestpolicytypedef)
  - [DetachUserPolicyRequestRequestTypeDef](#detachuserpolicyrequestrequesttypedef)
  - [DetachUserPolicyRequestUserTypeDef](#detachuserpolicyrequestusertypedef)
  - [EnableMFADeviceRequestMfaDeviceTypeDef](#enablemfadevicerequestmfadevicetypedef)
  - [EnableMFADeviceRequestRequestTypeDef](#enablemfadevicerequestrequesttypedef)
  - [EnableMFADeviceRequestUserTypeDef](#enablemfadevicerequestusertypedef)
  - [EntityDetailsTypeDef](#entitydetailstypedef)
  - [EntityInfoTypeDef](#entityinfotypedef)
  - [ErrorDetailsTypeDef](#errordetailstypedef)
  - [EvaluationResultTypeDef](#evaluationresulttypedef)
  - [GenerateCredentialReportResponseTypeDef](#generatecredentialreportresponsetypedef)
  - [GenerateOrganizationsAccessReportRequestRequestTypeDef](#generateorganizationsaccessreportrequestrequesttypedef)
  - [GenerateOrganizationsAccessReportResponseTypeDef](#generateorganizationsaccessreportresponsetypedef)
  - [GenerateServiceLastAccessedDetailsRequestRequestTypeDef](#generateservicelastaccesseddetailsrequestrequesttypedef)
  - [GenerateServiceLastAccessedDetailsResponseTypeDef](#generateservicelastaccesseddetailsresponsetypedef)
  - [GetAccessKeyLastUsedRequestRequestTypeDef](#getaccesskeylastusedrequestrequesttypedef)
  - [GetAccessKeyLastUsedResponseTypeDef](#getaccesskeylastusedresponsetypedef)
  - [GetAccountAuthorizationDetailsRequestRequestTypeDef](#getaccountauthorizationdetailsrequestrequesttypedef)
  - [GetAccountAuthorizationDetailsResponseTypeDef](#getaccountauthorizationdetailsresponsetypedef)
  - [GetAccountPasswordPolicyResponseTypeDef](#getaccountpasswordpolicyresponsetypedef)
  - [GetAccountSummaryResponseTypeDef](#getaccountsummaryresponsetypedef)
  - [GetContextKeysForCustomPolicyRequestRequestTypeDef](#getcontextkeysforcustompolicyrequestrequesttypedef)
  - [GetContextKeysForPolicyResponseTypeDef](#getcontextkeysforpolicyresponsetypedef)
  - [GetContextKeysForPrincipalPolicyRequestRequestTypeDef](#getcontextkeysforprincipalpolicyrequestrequesttypedef)
  - [GetCredentialReportResponseTypeDef](#getcredentialreportresponsetypedef)
  - [GetGroupPolicyRequestRequestTypeDef](#getgrouppolicyrequestrequesttypedef)
  - [GetGroupPolicyResponseTypeDef](#getgrouppolicyresponsetypedef)
  - [GetGroupRequestRequestTypeDef](#getgrouprequestrequesttypedef)
  - [GetGroupResponseTypeDef](#getgroupresponsetypedef)
  - [GetInstanceProfileRequestRequestTypeDef](#getinstanceprofilerequestrequesttypedef)
  - [GetInstanceProfileResponseTypeDef](#getinstanceprofileresponsetypedef)
  - [GetLoginProfileRequestRequestTypeDef](#getloginprofilerequestrequesttypedef)
  - [GetLoginProfileResponseTypeDef](#getloginprofileresponsetypedef)
  - [GetOpenIDConnectProviderRequestRequestTypeDef](#getopenidconnectproviderrequestrequesttypedef)
  - [GetOpenIDConnectProviderResponseTypeDef](#getopenidconnectproviderresponsetypedef)
  - [GetOrganizationsAccessReportRequestRequestTypeDef](#getorganizationsaccessreportrequestrequesttypedef)
  - [GetOrganizationsAccessReportResponseTypeDef](#getorganizationsaccessreportresponsetypedef)
  - [GetPolicyRequestRequestTypeDef](#getpolicyrequestrequesttypedef)
  - [GetPolicyResponseTypeDef](#getpolicyresponsetypedef)
  - [GetPolicyVersionRequestRequestTypeDef](#getpolicyversionrequestrequesttypedef)
  - [GetPolicyVersionResponseTypeDef](#getpolicyversionresponsetypedef)
  - [GetRolePolicyRequestRequestTypeDef](#getrolepolicyrequestrequesttypedef)
  - [GetRolePolicyResponseTypeDef](#getrolepolicyresponsetypedef)
  - [GetRoleRequestRequestTypeDef](#getrolerequestrequesttypedef)
  - [GetRoleResponseTypeDef](#getroleresponsetypedef)
  - [GetSAMLProviderRequestRequestTypeDef](#getsamlproviderrequestrequesttypedef)
  - [GetSAMLProviderResponseTypeDef](#getsamlproviderresponsetypedef)
  - [GetSSHPublicKeyRequestRequestTypeDef](#getsshpublickeyrequestrequesttypedef)
  - [GetSSHPublicKeyResponseTypeDef](#getsshpublickeyresponsetypedef)
  - [GetServerCertificateRequestRequestTypeDef](#getservercertificaterequestrequesttypedef)
  - [GetServerCertificateResponseTypeDef](#getservercertificateresponsetypedef)
  - [GetServiceLastAccessedDetailsRequestRequestTypeDef](#getservicelastaccesseddetailsrequestrequesttypedef)
  - [GetServiceLastAccessedDetailsResponseTypeDef](#getservicelastaccesseddetailsresponsetypedef)
  - [GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef](#getservicelastaccesseddetailswithentitiesrequestrequesttypedef)
  - [GetServiceLastAccessedDetailsWithEntitiesResponseTypeDef](#getservicelastaccesseddetailswithentitiesresponsetypedef)
  - [GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef](#getservicelinkedroledeletionstatusrequestrequesttypedef)
  - [GetServiceLinkedRoleDeletionStatusResponseTypeDef](#getservicelinkedroledeletionstatusresponsetypedef)
  - [GetUserPolicyRequestRequestTypeDef](#getuserpolicyrequestrequesttypedef)
  - [GetUserPolicyResponseTypeDef](#getuserpolicyresponsetypedef)
  - [GetUserRequestRequestTypeDef](#getuserrequestrequesttypedef)
  - [GetUserResponseTypeDef](#getuserresponsetypedef)
  - [GroupDetailTypeDef](#groupdetailtypedef)
  - [GroupPolicyRequestTypeDef](#grouppolicyrequesttypedef)
  - [GroupTypeDef](#grouptypedef)
  - [InstanceProfileTypeDef](#instanceprofiletypedef)
  - [ListAccessKeysRequestRequestTypeDef](#listaccesskeysrequestrequesttypedef)
  - [ListAccessKeysResponseTypeDef](#listaccesskeysresponsetypedef)
  - [ListAccountAliasesRequestRequestTypeDef](#listaccountaliasesrequestrequesttypedef)
  - [ListAccountAliasesResponseTypeDef](#listaccountaliasesresponsetypedef)
  - [ListAttachedGroupPoliciesRequestRequestTypeDef](#listattachedgrouppoliciesrequestrequesttypedef)
  - [ListAttachedGroupPoliciesResponseTypeDef](#listattachedgrouppoliciesresponsetypedef)
  - [ListAttachedRolePoliciesRequestRequestTypeDef](#listattachedrolepoliciesrequestrequesttypedef)
  - [ListAttachedRolePoliciesResponseTypeDef](#listattachedrolepoliciesresponsetypedef)
  - [ListAttachedUserPoliciesRequestRequestTypeDef](#listattacheduserpoliciesrequestrequesttypedef)
  - [ListAttachedUserPoliciesResponseTypeDef](#listattacheduserpoliciesresponsetypedef)
  - [ListEntitiesForPolicyRequestRequestTypeDef](#listentitiesforpolicyrequestrequesttypedef)
  - [ListEntitiesForPolicyResponseTypeDef](#listentitiesforpolicyresponsetypedef)
  - [ListGroupPoliciesRequestRequestTypeDef](#listgrouppoliciesrequestrequesttypedef)
  - [ListGroupPoliciesResponseTypeDef](#listgrouppoliciesresponsetypedef)
  - [ListGroupsForUserRequestRequestTypeDef](#listgroupsforuserrequestrequesttypedef)
  - [ListGroupsForUserResponseTypeDef](#listgroupsforuserresponsetypedef)
  - [ListGroupsRequestRequestTypeDef](#listgroupsrequestrequesttypedef)
  - [ListGroupsResponseTypeDef](#listgroupsresponsetypedef)
  - [ListInstanceProfileTagsRequestRequestTypeDef](#listinstanceprofiletagsrequestrequesttypedef)
  - [ListInstanceProfileTagsResponseTypeDef](#listinstanceprofiletagsresponsetypedef)
  - [ListInstanceProfilesForRoleRequestRequestTypeDef](#listinstanceprofilesforrolerequestrequesttypedef)
  - [ListInstanceProfilesForRoleResponseTypeDef](#listinstanceprofilesforroleresponsetypedef)
  - [ListInstanceProfilesRequestRequestTypeDef](#listinstanceprofilesrequestrequesttypedef)
  - [ListInstanceProfilesResponseTypeDef](#listinstanceprofilesresponsetypedef)
  - [ListMFADeviceTagsRequestRequestTypeDef](#listmfadevicetagsrequestrequesttypedef)
  - [ListMFADeviceTagsResponseTypeDef](#listmfadevicetagsresponsetypedef)
  - [ListMFADevicesRequestRequestTypeDef](#listmfadevicesrequestrequesttypedef)
  - [ListMFADevicesResponseTypeDef](#listmfadevicesresponsetypedef)
  - [ListOpenIDConnectProviderTagsRequestRequestTypeDef](#listopenidconnectprovidertagsrequestrequesttypedef)
  - [ListOpenIDConnectProviderTagsResponseTypeDef](#listopenidconnectprovidertagsresponsetypedef)
  - [ListOpenIDConnectProvidersResponseTypeDef](#listopenidconnectprovidersresponsetypedef)
  - [ListPoliciesGrantingServiceAccessEntryTypeDef](#listpoliciesgrantingserviceaccessentrytypedef)
  - [ListPoliciesGrantingServiceAccessRequestRequestTypeDef](#listpoliciesgrantingserviceaccessrequestrequesttypedef)
  - [ListPoliciesGrantingServiceAccessResponseTypeDef](#listpoliciesgrantingserviceaccessresponsetypedef)
  - [ListPoliciesRequestRequestTypeDef](#listpoliciesrequestrequesttypedef)
  - [ListPoliciesResponseTypeDef](#listpoliciesresponsetypedef)
  - [ListPolicyTagsRequestRequestTypeDef](#listpolicytagsrequestrequesttypedef)
  - [ListPolicyTagsResponseTypeDef](#listpolicytagsresponsetypedef)
  - [ListPolicyVersionsRequestRequestTypeDef](#listpolicyversionsrequestrequesttypedef)
  - [ListPolicyVersionsResponseTypeDef](#listpolicyversionsresponsetypedef)
  - [ListRolePoliciesRequestRequestTypeDef](#listrolepoliciesrequestrequesttypedef)
  - [ListRolePoliciesResponseTypeDef](#listrolepoliciesresponsetypedef)
  - [ListRoleTagsRequestRequestTypeDef](#listroletagsrequestrequesttypedef)
  - [ListRoleTagsResponseTypeDef](#listroletagsresponsetypedef)
  - [ListRolesRequestRequestTypeDef](#listrolesrequestrequesttypedef)
  - [ListRolesResponseTypeDef](#listrolesresponsetypedef)
  - [ListSAMLProviderTagsRequestRequestTypeDef](#listsamlprovidertagsrequestrequesttypedef)
  - [ListSAMLProviderTagsResponseTypeDef](#listsamlprovidertagsresponsetypedef)
  - [ListSAMLProvidersResponseTypeDef](#listsamlprovidersresponsetypedef)
  - [ListSSHPublicKeysRequestRequestTypeDef](#listsshpublickeysrequestrequesttypedef)
  - [ListSSHPublicKeysResponseTypeDef](#listsshpublickeysresponsetypedef)
  - [ListServerCertificateTagsRequestRequestTypeDef](#listservercertificatetagsrequestrequesttypedef)
  - [ListServerCertificateTagsResponseTypeDef](#listservercertificatetagsresponsetypedef)
  - [ListServerCertificatesRequestRequestTypeDef](#listservercertificatesrequestrequesttypedef)
  - [ListServerCertificatesResponseTypeDef](#listservercertificatesresponsetypedef)
  - [ListServiceSpecificCredentialsRequestRequestTypeDef](#listservicespecificcredentialsrequestrequesttypedef)
  - [ListServiceSpecificCredentialsResponseTypeDef](#listservicespecificcredentialsresponsetypedef)
  - [ListSigningCertificatesRequestRequestTypeDef](#listsigningcertificatesrequestrequesttypedef)
  - [ListSigningCertificatesResponseTypeDef](#listsigningcertificatesresponsetypedef)
  - [ListUserPoliciesRequestRequestTypeDef](#listuserpoliciesrequestrequesttypedef)
  - [ListUserPoliciesResponseTypeDef](#listuserpoliciesresponsetypedef)
  - [ListUserTagsRequestRequestTypeDef](#listusertagsrequestrequesttypedef)
  - [ListUserTagsResponseTypeDef](#listusertagsresponsetypedef)
  - [ListUsersRequestRequestTypeDef](#listusersrequestrequesttypedef)
  - [ListUsersResponseTypeDef](#listusersresponsetypedef)
  - [ListVirtualMFADevicesRequestRequestTypeDef](#listvirtualmfadevicesrequestrequesttypedef)
  - [ListVirtualMFADevicesResponseTypeDef](#listvirtualmfadevicesresponsetypedef)
  - [LoginProfileTypeDef](#loginprofiletypedef)
  - [MFADeviceTypeDef](#mfadevicetypedef)
  - [ManagedPolicyDetailTypeDef](#managedpolicydetailtypedef)
  - [OpenIDConnectProviderListEntryTypeDef](#openidconnectproviderlistentrytypedef)
  - [OrganizationsDecisionDetailTypeDef](#organizationsdecisiondetailtypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PasswordPolicyTypeDef](#passwordpolicytypedef)
  - [PermissionsBoundaryDecisionDetailTypeDef](#permissionsboundarydecisiondetailtypedef)
  - [PolicyDetailTypeDef](#policydetailtypedef)
  - [PolicyGrantingServiceAccessTypeDef](#policygrantingserviceaccesstypedef)
  - [PolicyGroupTypeDef](#policygrouptypedef)
  - [PolicyRoleTypeDef](#policyroletypedef)
  - [PolicyTypeDef](#policytypedef)
  - [PolicyUserTypeDef](#policyusertypedef)
  - [PolicyVersionTypeDef](#policyversiontypedef)
  - [PositionTypeDef](#positiontypedef)
  - [PutGroupPolicyRequestGroupPolicyTypeDef](#putgrouppolicyrequestgrouppolicytypedef)
  - [PutGroupPolicyRequestGroupTypeDef](#putgrouppolicyrequestgrouptypedef)
  - [PutGroupPolicyRequestRequestTypeDef](#putgrouppolicyrequestrequesttypedef)
  - [PutRolePermissionsBoundaryRequestRequestTypeDef](#putrolepermissionsboundaryrequestrequesttypedef)
  - [PutRolePolicyRequestRequestTypeDef](#putrolepolicyrequestrequesttypedef)
  - [PutRolePolicyRequestRolePolicyTypeDef](#putrolepolicyrequestrolepolicytypedef)
  - [PutUserPermissionsBoundaryRequestRequestTypeDef](#putuserpermissionsboundaryrequestrequesttypedef)
  - [PutUserPolicyRequestRequestTypeDef](#putuserpolicyrequestrequesttypedef)
  - [PutUserPolicyRequestUserPolicyTypeDef](#putuserpolicyrequestuserpolicytypedef)
  - [PutUserPolicyRequestUserTypeDef](#putuserpolicyrequestusertypedef)
  - [RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef](#removeclientidfromopenidconnectproviderrequestrequesttypedef)
  - [RemoveRoleFromInstanceProfileRequestInstanceProfileTypeDef](#removerolefrominstanceprofilerequestinstanceprofiletypedef)
  - [RemoveRoleFromInstanceProfileRequestRequestTypeDef](#removerolefrominstanceprofilerequestrequesttypedef)
  - [RemoveUserFromGroupRequestGroupTypeDef](#removeuserfromgrouprequestgrouptypedef)
  - [RemoveUserFromGroupRequestRequestTypeDef](#removeuserfromgrouprequestrequesttypedef)
  - [RemoveUserFromGroupRequestUserTypeDef](#removeuserfromgrouprequestusertypedef)
  - [ResetServiceSpecificCredentialRequestRequestTypeDef](#resetservicespecificcredentialrequestrequesttypedef)
  - [ResetServiceSpecificCredentialResponseTypeDef](#resetservicespecificcredentialresponsetypedef)
  - [ResourceSpecificResultTypeDef](#resourcespecificresulttypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ResyncMFADeviceRequestMfaDeviceTypeDef](#resyncmfadevicerequestmfadevicetypedef)
  - [ResyncMFADeviceRequestRequestTypeDef](#resyncmfadevicerequestrequesttypedef)
  - [RoleDetailTypeDef](#roledetailtypedef)
  - [RoleLastUsedResponseMetadataTypeDef](#rolelastusedresponsemetadatatypedef)
  - [RoleLastUsedTypeDef](#rolelastusedtypedef)
  - [RolePolicyRequestTypeDef](#rolepolicyrequesttypedef)
  - [RoleTypeDef](#roletypedef)
  - [RoleUsageTypeTypeDef](#roleusagetypetypedef)
  - [SAMLProviderListEntryTypeDef](#samlproviderlistentrytypedef)
  - [SSHPublicKeyMetadataTypeDef](#sshpublickeymetadatatypedef)
  - [SSHPublicKeyTypeDef](#sshpublickeytypedef)
  - [ServerCertificateMetadataResponseMetadataTypeDef](#servercertificatemetadataresponsemetadatatypedef)
  - [ServerCertificateMetadataTypeDef](#servercertificatemetadatatypedef)
  - [ServerCertificateTypeDef](#servercertificatetypedef)
  - [ServiceLastAccessedTypeDef](#servicelastaccessedtypedef)
  - [ServiceResourceAccessKeyPairRequestTypeDef](#serviceresourceaccesskeypairrequesttypedef)
  - [ServiceResourceAccessKeyRequestTypeDef](#serviceresourceaccesskeyrequesttypedef)
  - [ServiceResourceAssumeRolePolicyRequestTypeDef](#serviceresourceassumerolepolicyrequesttypedef)
  - [ServiceResourceGroupPolicyRequestTypeDef](#serviceresourcegrouppolicyrequesttypedef)
  - [ServiceResourceGroupRequestTypeDef](#serviceresourcegrouprequesttypedef)
  - [ServiceResourceInstanceProfileRequestTypeDef](#serviceresourceinstanceprofilerequesttypedef)
  - [ServiceResourceLoginProfileRequestTypeDef](#serviceresourceloginprofilerequesttypedef)
  - [ServiceResourceMfaDeviceRequestTypeDef](#serviceresourcemfadevicerequesttypedef)
  - [ServiceResourcePolicyRequestTypeDef](#serviceresourcepolicyrequesttypedef)
  - [ServiceResourcePolicyVersionRequestTypeDef](#serviceresourcepolicyversionrequesttypedef)
  - [ServiceResourceRolePolicyRequestTypeDef](#serviceresourcerolepolicyrequesttypedef)
  - [ServiceResourceRoleRequestTypeDef](#serviceresourcerolerequesttypedef)
  - [ServiceResourceSamlProviderRequestTypeDef](#serviceresourcesamlproviderrequesttypedef)
  - [ServiceResourceServerCertificateRequestTypeDef](#serviceresourceservercertificaterequesttypedef)
  - [ServiceResourceSigningCertificateRequestTypeDef](#serviceresourcesigningcertificaterequesttypedef)
  - [ServiceResourceUserPolicyRequestTypeDef](#serviceresourceuserpolicyrequesttypedef)
  - [ServiceResourceUserRequestTypeDef](#serviceresourceuserrequesttypedef)
  - [ServiceResourceVirtualMfaDeviceRequestTypeDef](#serviceresourcevirtualmfadevicerequesttypedef)
  - [ServiceSpecificCredentialMetadataTypeDef](#servicespecificcredentialmetadatatypedef)
  - [ServiceSpecificCredentialTypeDef](#servicespecificcredentialtypedef)
  - [SetDefaultPolicyVersionRequestRequestTypeDef](#setdefaultpolicyversionrequestrequesttypedef)
  - [SetSecurityTokenServicePreferencesRequestRequestTypeDef](#setsecuritytokenservicepreferencesrequestrequesttypedef)
  - [SigningCertificateTypeDef](#signingcertificatetypedef)
  - [SimulateCustomPolicyRequestRequestTypeDef](#simulatecustompolicyrequestrequesttypedef)
  - [SimulatePolicyResponseTypeDef](#simulatepolicyresponsetypedef)
  - [SimulatePrincipalPolicyRequestRequestTypeDef](#simulateprincipalpolicyrequestrequesttypedef)
  - [StatementTypeDef](#statementtypedef)
  - [TagInstanceProfileRequestRequestTypeDef](#taginstanceprofilerequestrequesttypedef)
  - [TagMFADeviceRequestRequestTypeDef](#tagmfadevicerequestrequesttypedef)
  - [TagOpenIDConnectProviderRequestRequestTypeDef](#tagopenidconnectproviderrequestrequesttypedef)
  - [TagPolicyRequestRequestTypeDef](#tagpolicyrequestrequesttypedef)
  - [TagRoleRequestRequestTypeDef](#tagrolerequestrequesttypedef)
  - [TagSAMLProviderRequestRequestTypeDef](#tagsamlproviderrequestrequesttypedef)
  - [TagServerCertificateRequestRequestTypeDef](#tagservercertificaterequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TagUserRequestRequestTypeDef](#taguserrequestrequesttypedef)
  - [TrackedActionLastAccessedTypeDef](#trackedactionlastaccessedtypedef)
  - [UntagInstanceProfileRequestRequestTypeDef](#untaginstanceprofilerequestrequesttypedef)
  - [UntagMFADeviceRequestRequestTypeDef](#untagmfadevicerequestrequesttypedef)
  - [UntagOpenIDConnectProviderRequestRequestTypeDef](#untagopenidconnectproviderrequestrequesttypedef)
  - [UntagPolicyRequestRequestTypeDef](#untagpolicyrequestrequesttypedef)
  - [UntagRoleRequestRequestTypeDef](#untagrolerequestrequesttypedef)
  - [UntagSAMLProviderRequestRequestTypeDef](#untagsamlproviderrequestrequesttypedef)
  - [UntagServerCertificateRequestRequestTypeDef](#untagservercertificaterequestrequesttypedef)
  - [UntagUserRequestRequestTypeDef](#untaguserrequestrequesttypedef)
  - [UpdateAccessKeyRequestAccessKeyPairTypeDef](#updateaccesskeyrequestaccesskeypairtypedef)
  - [UpdateAccessKeyRequestAccessKeyTypeDef](#updateaccesskeyrequestaccesskeytypedef)
  - [UpdateAccessKeyRequestRequestTypeDef](#updateaccesskeyrequestrequesttypedef)
  - [UpdateAccountPasswordPolicyRequestAccountPasswordPolicyTypeDef](#updateaccountpasswordpolicyrequestaccountpasswordpolicytypedef)
  - [UpdateAccountPasswordPolicyRequestRequestTypeDef](#updateaccountpasswordpolicyrequestrequesttypedef)
  - [UpdateAccountPasswordPolicyRequestServiceResourceTypeDef](#updateaccountpasswordpolicyrequestserviceresourcetypedef)
  - [UpdateAssumeRolePolicyRequestAssumeRolePolicyTypeDef](#updateassumerolepolicyrequestassumerolepolicytypedef)
  - [UpdateAssumeRolePolicyRequestRequestTypeDef](#updateassumerolepolicyrequestrequesttypedef)
  - [UpdateGroupRequestGroupTypeDef](#updategrouprequestgrouptypedef)
  - [UpdateGroupRequestRequestTypeDef](#updategrouprequestrequesttypedef)
  - [UpdateLoginProfileRequestLoginProfileTypeDef](#updateloginprofilerequestloginprofiletypedef)
  - [UpdateLoginProfileRequestRequestTypeDef](#updateloginprofilerequestrequesttypedef)
  - [UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef](#updateopenidconnectproviderthumbprintrequestrequesttypedef)
  - [UpdateRoleDescriptionRequestRequestTypeDef](#updateroledescriptionrequestrequesttypedef)
  - [UpdateRoleDescriptionResponseTypeDef](#updateroledescriptionresponsetypedef)
  - [UpdateRoleRequestRequestTypeDef](#updaterolerequestrequesttypedef)
  - [UpdateSAMLProviderRequestRequestTypeDef](#updatesamlproviderrequestrequesttypedef)
  - [UpdateSAMLProviderRequestSamlProviderTypeDef](#updatesamlproviderrequestsamlprovidertypedef)
  - [UpdateSAMLProviderResponseTypeDef](#updatesamlproviderresponsetypedef)
  - [UpdateSSHPublicKeyRequestRequestTypeDef](#updatesshpublickeyrequestrequesttypedef)
  - [UpdateServerCertificateRequestRequestTypeDef](#updateservercertificaterequestrequesttypedef)
  - [UpdateServerCertificateRequestServerCertificateTypeDef](#updateservercertificaterequestservercertificatetypedef)
  - [UpdateServiceSpecificCredentialRequestRequestTypeDef](#updateservicespecificcredentialrequestrequesttypedef)
  - [UpdateSigningCertificateRequestRequestTypeDef](#updatesigningcertificaterequestrequesttypedef)
  - [UpdateSigningCertificateRequestSigningCertificateTypeDef](#updatesigningcertificaterequestsigningcertificatetypedef)
  - [UpdateUserRequestRequestTypeDef](#updateuserrequestrequesttypedef)
  - [UpdateUserRequestUserTypeDef](#updateuserrequestusertypedef)
  - [UploadSSHPublicKeyRequestRequestTypeDef](#uploadsshpublickeyrequestrequesttypedef)
  - [UploadSSHPublicKeyResponseTypeDef](#uploadsshpublickeyresponsetypedef)
  - [UploadServerCertificateRequestRequestTypeDef](#uploadservercertificaterequestrequesttypedef)
  - [UploadServerCertificateRequestServiceResourceTypeDef](#uploadservercertificaterequestserviceresourcetypedef)
  - [UploadServerCertificateResponseTypeDef](#uploadservercertificateresponsetypedef)
  - [UploadSigningCertificateRequestRequestTypeDef](#uploadsigningcertificaterequestrequesttypedef)
  - [UploadSigningCertificateRequestServiceResourceTypeDef](#uploadsigningcertificaterequestserviceresourcetypedef)
  - [UploadSigningCertificateResponseTypeDef](#uploadsigningcertificateresponsetypedef)
  - [UserAccessKeyRequestTypeDef](#useraccesskeyrequesttypedef)
  - [UserDetailTypeDef](#userdetailtypedef)
  - [UserMfaDeviceRequestTypeDef](#usermfadevicerequesttypedef)
  - [UserPolicyRequestTypeDef](#userpolicyrequesttypedef)
  - [UserResponseMetadataTypeDef](#userresponsemetadatatypedef)
  - [UserSigningCertificateRequestTypeDef](#usersigningcertificaterequesttypedef)
  - [UserTypeDef](#usertypedef)
  - [VirtualMFADeviceTypeDef](#virtualmfadevicetypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)

<a id="accessdetailtypedef"></a>

## AccessDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import AccessDetailTypeDef
```

Required fields:

- `ServiceName`: `str`
- `ServiceNamespace`: `str`

Optional fields:

- `Region`: `str`
- `EntityPath`: `str`
- `LastAuthenticatedTime`: `datetime`
- `TotalAuthenticatedEntities`: `int`

<a id="accesskeylastusedtypedef"></a>

## AccessKeyLastUsedTypeDef

```python
from types_aiobotocore_iam.type_defs import AccessKeyLastUsedTypeDef
```

Required fields:

- `LastUsedDate`: `datetime`
- `ServiceName`: `str`
- `Region`: `str`

<a id="accesskeymetadatatypedef"></a>

## AccessKeyMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import AccessKeyMetadataTypeDef
```

Optional fields:

- `UserName`: `str`
- `AccessKeyId`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)
- `CreateDate`: `datetime`

<a id="accesskeytypedef"></a>

## AccessKeyTypeDef

```python
from types_aiobotocore_iam.type_defs import AccessKeyTypeDef
```

Required fields:

- `UserName`: `str`
- `AccessKeyId`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)
- `SecretAccessKey`: `str`

Optional fields:

- `CreateDate`: `datetime`

<a id="addclientidtoopenidconnectproviderrequestrequesttypedef"></a>

## AddClientIDToOpenIDConnectProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import AddClientIDToOpenIDConnectProviderRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`
- `ClientID`: `str`

<a id="addroletoinstanceprofilerequestinstanceprofiletypedef"></a>

## AddRoleToInstanceProfileRequestInstanceProfileTypeDef

```python
from types_aiobotocore_iam.type_defs import AddRoleToInstanceProfileRequestInstanceProfileTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="addroletoinstanceprofilerequestrequesttypedef"></a>

## AddRoleToInstanceProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import AddRoleToInstanceProfileRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`
- `RoleName`: `str`

<a id="addusertogrouprequestgrouptypedef"></a>

## AddUserToGroupRequestGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import AddUserToGroupRequestGroupTypeDef
```

Required fields:

- `UserName`: `str`

<a id="addusertogrouprequestrequesttypedef"></a>

## AddUserToGroupRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import AddUserToGroupRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`
- `UserName`: `str`

<a id="addusertogrouprequestusertypedef"></a>

## AddUserToGroupRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import AddUserToGroupRequestUserTypeDef
```

Required fields:

- `GroupName`: `str`

<a id="attachgrouppolicyrequestgrouptypedef"></a>

## AttachGroupPolicyRequestGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachGroupPolicyRequestGroupTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="attachgrouppolicyrequestpolicytypedef"></a>

## AttachGroupPolicyRequestPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachGroupPolicyRequestPolicyTypeDef
```

Required fields:

- `GroupName`: `str`

<a id="attachgrouppolicyrequestrequesttypedef"></a>

## AttachGroupPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachGroupPolicyRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`
- `PolicyArn`: `str`

<a id="attachrolepolicyrequestpolicytypedef"></a>

## AttachRolePolicyRequestPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachRolePolicyRequestPolicyTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="attachrolepolicyrequestrequesttypedef"></a>

## AttachRolePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachRolePolicyRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `PolicyArn`: `str`

<a id="attachrolepolicyrequestroletypedef"></a>

## AttachRolePolicyRequestRoleTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachRolePolicyRequestRoleTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="attachuserpolicyrequestpolicytypedef"></a>

## AttachUserPolicyRequestPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachUserPolicyRequestPolicyTypeDef
```

Required fields:

- `UserName`: `str`

<a id="attachuserpolicyrequestrequesttypedef"></a>

## AttachUserPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachUserPolicyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `PolicyArn`: `str`

<a id="attachuserpolicyrequestusertypedef"></a>

## AttachUserPolicyRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachUserPolicyRequestUserTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="attachedpermissionsboundaryresponsemetadatatypedef"></a>

## AttachedPermissionsBoundaryResponseMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachedPermissionsBoundaryResponseMetadataTypeDef
```

Required fields:

- `PermissionsBoundaryType`: `Literal['PermissionsBoundaryPolicy']` (see
  [PermissionsBoundaryAttachmentTypeType](./literals.md#permissionsboundaryattachmenttypetype))
- `PermissionsBoundaryArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="attachedpermissionsboundarytypedef"></a>

## AttachedPermissionsBoundaryTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachedPermissionsBoundaryTypeDef
```

Optional fields:

- `PermissionsBoundaryType`: `Literal['PermissionsBoundaryPolicy']` (see
  [PermissionsBoundaryAttachmentTypeType](./literals.md#permissionsboundaryattachmenttypetype))
- `PermissionsBoundaryArn`: `str`

<a id="attachedpolicytypedef"></a>

## AttachedPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import AttachedPolicyTypeDef
```

Optional fields:

- `PolicyName`: `str`
- `PolicyArn`: `str`

<a id="changepasswordrequestrequesttypedef"></a>

## ChangePasswordRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ChangePasswordRequestRequestTypeDef
```

Required fields:

- `OldPassword`: `str`
- `NewPassword`: `str`

<a id="changepasswordrequestserviceresourcetypedef"></a>

## ChangePasswordRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import ChangePasswordRequestServiceResourceTypeDef
```

Required fields:

- `OldPassword`: `str`
- `NewPassword`: `str`

<a id="contextentrytypedef"></a>

## ContextEntryTypeDef

```python
from types_aiobotocore_iam.type_defs import ContextEntryTypeDef
```

Optional fields:

- `ContextKeyName`: `str`
- `ContextKeyValues`: `Sequence`\[`str`\]
- `ContextKeyType`:
  [ContextKeyTypeEnumType](./literals.md#contextkeytypeenumtype)

<a id="createaccesskeyrequestrequesttypedef"></a>

## CreateAccessKeyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateAccessKeyRequestRequestTypeDef
```

Optional fields:

- `UserName`: `str`

<a id="createaccesskeyresponsetypedef"></a>

## CreateAccessKeyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateAccessKeyResponseTypeDef
```

Required fields:

- `AccessKey`: [AccessKeyTypeDef](./type_defs.md#accesskeytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createaccountaliasrequestrequesttypedef"></a>

## CreateAccountAliasRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateAccountAliasRequestRequestTypeDef
```

Required fields:

- `AccountAlias`: `str`

<a id="createaccountaliasrequestserviceresourcetypedef"></a>

## CreateAccountAliasRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateAccountAliasRequestServiceResourceTypeDef
```

Required fields:

- `AccountAlias`: `str`

<a id="creategrouprequestgrouptypedef"></a>

## CreateGroupRequestGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateGroupRequestGroupTypeDef
```

Optional fields:

- `Path`: `str`

<a id="creategrouprequestrequesttypedef"></a>

## CreateGroupRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateGroupRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`

Optional fields:

- `Path`: `str`

<a id="creategrouprequestserviceresourcetypedef"></a>

## CreateGroupRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateGroupRequestServiceResourceTypeDef
```

Required fields:

- `GroupName`: `str`

Optional fields:

- `Path`: `str`

<a id="creategroupresponsetypedef"></a>

## CreateGroupResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateGroupResponseTypeDef
```

Required fields:

- `Group`: [GroupTypeDef](./type_defs.md#grouptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createinstanceprofilerequestrequesttypedef"></a>

## CreateInstanceProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateInstanceProfileRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`

Optional fields:

- `Path`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createinstanceprofilerequestserviceresourcetypedef"></a>

## CreateInstanceProfileRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateInstanceProfileRequestServiceResourceTypeDef
```

Required fields:

- `InstanceProfileName`: `str`

Optional fields:

- `Path`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createinstanceprofileresponsetypedef"></a>

## CreateInstanceProfileResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateInstanceProfileResponseTypeDef
```

Required fields:

- `InstanceProfile`:
  [InstanceProfileTypeDef](./type_defs.md#instanceprofiletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createloginprofilerequestloginprofiletypedef"></a>

## CreateLoginProfileRequestLoginProfileTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateLoginProfileRequestLoginProfileTypeDef
```

Required fields:

- `Password`: `str`

Optional fields:

- `PasswordResetRequired`: `bool`

<a id="createloginprofilerequestrequesttypedef"></a>

## CreateLoginProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateLoginProfileRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `Password`: `str`

Optional fields:

- `PasswordResetRequired`: `bool`

<a id="createloginprofilerequestusertypedef"></a>

## CreateLoginProfileRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateLoginProfileRequestUserTypeDef
```

Required fields:

- `Password`: `str`

Optional fields:

- `PasswordResetRequired`: `bool`

<a id="createloginprofileresponsetypedef"></a>

## CreateLoginProfileResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateLoginProfileResponseTypeDef
```

Required fields:

- `LoginProfile`: [LoginProfileTypeDef](./type_defs.md#loginprofiletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createopenidconnectproviderrequestrequesttypedef"></a>

## CreateOpenIDConnectProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateOpenIDConnectProviderRequestRequestTypeDef
```

Required fields:

- `Url`: `str`
- `ThumbprintList`: `Sequence`\[`str`\]

Optional fields:

- `ClientIDList`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createopenidconnectproviderresponsetypedef"></a>

## CreateOpenIDConnectProviderResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateOpenIDConnectProviderResponseTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpolicyrequestrequesttypedef"></a>

## CreatePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreatePolicyRequestRequestTypeDef
```

Required fields:

- `PolicyName`: `str`
- `PolicyDocument`: `str`

Optional fields:

- `Path`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createpolicyrequestserviceresourcetypedef"></a>

## CreatePolicyRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreatePolicyRequestServiceResourceTypeDef
```

Required fields:

- `PolicyName`: `str`
- `PolicyDocument`: `str`

Optional fields:

- `Path`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createpolicyresponsetypedef"></a>

## CreatePolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreatePolicyResponseTypeDef
```

Required fields:

- `Policy`: [PolicyTypeDef](./type_defs.md#policytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpolicyversionrequestpolicytypedef"></a>

## CreatePolicyVersionRequestPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import CreatePolicyVersionRequestPolicyTypeDef
```

Required fields:

- `PolicyDocument`: `str`

Optional fields:

- `SetAsDefault`: `bool`

<a id="createpolicyversionrequestrequesttypedef"></a>

## CreatePolicyVersionRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreatePolicyVersionRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`
- `PolicyDocument`: `str`

Optional fields:

- `SetAsDefault`: `bool`

<a id="createpolicyversionresponsetypedef"></a>

## CreatePolicyVersionResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreatePolicyVersionResponseTypeDef
```

Required fields:

- `PolicyVersion`: [PolicyVersionTypeDef](./type_defs.md#policyversiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createrolerequestrequesttypedef"></a>

## CreateRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `AssumeRolePolicyDocument`: `str`

Optional fields:

- `Path`: `str`
- `Description`: `str`
- `MaxSessionDuration`: `int`
- `PermissionsBoundary`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createrolerequestserviceresourcetypedef"></a>

## CreateRoleRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateRoleRequestServiceResourceTypeDef
```

Required fields:

- `RoleName`: `str`
- `AssumeRolePolicyDocument`: `str`

Optional fields:

- `Path`: `str`
- `Description`: `str`
- `MaxSessionDuration`: `int`
- `PermissionsBoundary`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createroleresponsetypedef"></a>

## CreateRoleResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateRoleResponseTypeDef
```

Required fields:

- `Role`: [RoleTypeDef](./type_defs.md#roletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createsamlproviderrequestrequesttypedef"></a>

## CreateSAMLProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateSAMLProviderRequestRequestTypeDef
```

Required fields:

- `SAMLMetadataDocument`: `str`
- `Name`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createsamlproviderrequestserviceresourcetypedef"></a>

## CreateSAMLProviderRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateSAMLProviderRequestServiceResourceTypeDef
```

Required fields:

- `SAMLMetadataDocument`: `str`
- `Name`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createsamlproviderresponsetypedef"></a>

## CreateSAMLProviderResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateSAMLProviderResponseTypeDef
```

Required fields:

- `SAMLProviderArn`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createservicelinkedrolerequestrequesttypedef"></a>

## CreateServiceLinkedRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateServiceLinkedRoleRequestRequestTypeDef
```

Required fields:

- `AWSServiceName`: `str`

Optional fields:

- `Description`: `str`
- `CustomSuffix`: `str`

<a id="createservicelinkedroleresponsetypedef"></a>

## CreateServiceLinkedRoleResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateServiceLinkedRoleResponseTypeDef
```

Required fields:

- `Role`: [RoleTypeDef](./type_defs.md#roletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createservicespecificcredentialrequestrequesttypedef"></a>

## CreateServiceSpecificCredentialRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateServiceSpecificCredentialRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `ServiceName`: `str`

<a id="createservicespecificcredentialresponsetypedef"></a>

## CreateServiceSpecificCredentialResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateServiceSpecificCredentialResponseTypeDef
```

Required fields:

- `ServiceSpecificCredential`:
  [ServiceSpecificCredentialTypeDef](./type_defs.md#servicespecificcredentialtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createuserrequestrequesttypedef"></a>

## CreateUserRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `Path`: `str`
- `PermissionsBoundary`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createuserrequestserviceresourcetypedef"></a>

## CreateUserRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateUserRequestServiceResourceTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `Path`: `str`
- `PermissionsBoundary`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createuserrequestusertypedef"></a>

## CreateUserRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateUserRequestUserTypeDef
```

Optional fields:

- `Path`: `str`
- `PermissionsBoundary`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createuserresponsetypedef"></a>

## CreateUserResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateUserResponseTypeDef
```

Required fields:

- `User`: [UserTypeDef](./type_defs.md#usertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createvirtualmfadevicerequestrequesttypedef"></a>

## CreateVirtualMFADeviceRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateVirtualMFADeviceRequestRequestTypeDef
```

Required fields:

- `VirtualMFADeviceName`: `str`

Optional fields:

- `Path`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createvirtualmfadevicerequestserviceresourcetypedef"></a>

## CreateVirtualMFADeviceRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateVirtualMFADeviceRequestServiceResourceTypeDef
```

Required fields:

- `VirtualMFADeviceName`: `str`

Optional fields:

- `Path`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createvirtualmfadeviceresponsetypedef"></a>

## CreateVirtualMFADeviceResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import CreateVirtualMFADeviceResponseTypeDef
```

Required fields:

- `VirtualMFADevice`:
  [VirtualMFADeviceTypeDef](./type_defs.md#virtualmfadevicetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deactivatemfadevicerequestrequesttypedef"></a>

## DeactivateMFADeviceRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeactivateMFADeviceRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `SerialNumber`: `str`

<a id="deleteaccesskeyrequestrequesttypedef"></a>

## DeleteAccessKeyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteAccessKeyRequestRequestTypeDef
```

Required fields:

- `AccessKeyId`: `str`

Optional fields:

- `UserName`: `str`

<a id="deleteaccountaliasrequestrequesttypedef"></a>

## DeleteAccountAliasRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteAccountAliasRequestRequestTypeDef
```

Required fields:

- `AccountAlias`: `str`

<a id="deletegrouppolicyrequestrequesttypedef"></a>

## DeleteGroupPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteGroupPolicyRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`
- `PolicyName`: `str`

<a id="deletegrouprequestrequesttypedef"></a>

## DeleteGroupRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteGroupRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`

<a id="deleteinstanceprofilerequestrequesttypedef"></a>

## DeleteInstanceProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteInstanceProfileRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`

<a id="deleteloginprofilerequestrequesttypedef"></a>

## DeleteLoginProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteLoginProfileRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

<a id="deleteopenidconnectproviderrequestrequesttypedef"></a>

## DeleteOpenIDConnectProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteOpenIDConnectProviderRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`

<a id="deletepolicyrequestrequesttypedef"></a>

## DeletePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeletePolicyRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="deletepolicyversionrequestrequesttypedef"></a>

## DeletePolicyVersionRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeletePolicyVersionRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`
- `VersionId`: `str`

<a id="deleterolepermissionsboundaryrequestrequesttypedef"></a>

## DeleteRolePermissionsBoundaryRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteRolePermissionsBoundaryRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="deleterolepolicyrequestrequesttypedef"></a>

## DeleteRolePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteRolePolicyRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `PolicyName`: `str`

<a id="deleterolerequestrequesttypedef"></a>

## DeleteRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="deletesamlproviderrequestrequesttypedef"></a>

## DeleteSAMLProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteSAMLProviderRequestRequestTypeDef
```

Required fields:

- `SAMLProviderArn`: `str`

<a id="deletesshpublickeyrequestrequesttypedef"></a>

## DeleteSSHPublicKeyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteSSHPublicKeyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `SSHPublicKeyId`: `str`

<a id="deleteservercertificaterequestrequesttypedef"></a>

## DeleteServerCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteServerCertificateRequestRequestTypeDef
```

Required fields:

- `ServerCertificateName`: `str`

<a id="deleteservicelinkedrolerequestrequesttypedef"></a>

## DeleteServiceLinkedRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteServiceLinkedRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="deleteservicelinkedroleresponsetypedef"></a>

## DeleteServiceLinkedRoleResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteServiceLinkedRoleResponseTypeDef
```

Required fields:

- `DeletionTaskId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteservicespecificcredentialrequestrequesttypedef"></a>

## DeleteServiceSpecificCredentialRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteServiceSpecificCredentialRequestRequestTypeDef
```

Required fields:

- `ServiceSpecificCredentialId`: `str`

Optional fields:

- `UserName`: `str`

<a id="deletesigningcertificaterequestrequesttypedef"></a>

## DeleteSigningCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteSigningCertificateRequestRequestTypeDef
```

Required fields:

- `CertificateId`: `str`

Optional fields:

- `UserName`: `str`

<a id="deleteuserpermissionsboundaryrequestrequesttypedef"></a>

## DeleteUserPermissionsBoundaryRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteUserPermissionsBoundaryRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

<a id="deleteuserpolicyrequestrequesttypedef"></a>

## DeleteUserPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteUserPolicyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `PolicyName`: `str`

<a id="deleteuserrequestrequesttypedef"></a>

## DeleteUserRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

<a id="deletevirtualmfadevicerequestrequesttypedef"></a>

## DeleteVirtualMFADeviceRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DeleteVirtualMFADeviceRequestRequestTypeDef
```

Required fields:

- `SerialNumber`: `str`

<a id="deletiontaskfailurereasontypetypedef"></a>

## DeletionTaskFailureReasonTypeTypeDef

```python
from types_aiobotocore_iam.type_defs import DeletionTaskFailureReasonTypeTypeDef
```

Optional fields:

- `Reason`: `str`
- `RoleUsageList`:
  `List`\[[RoleUsageTypeTypeDef](./type_defs.md#roleusagetypetypedef)\]

<a id="detachgrouppolicyrequestgrouptypedef"></a>

## DetachGroupPolicyRequestGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachGroupPolicyRequestGroupTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="detachgrouppolicyrequestpolicytypedef"></a>

## DetachGroupPolicyRequestPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachGroupPolicyRequestPolicyTypeDef
```

Required fields:

- `GroupName`: `str`

<a id="detachgrouppolicyrequestrequesttypedef"></a>

## DetachGroupPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachGroupPolicyRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`
- `PolicyArn`: `str`

<a id="detachrolepolicyrequestpolicytypedef"></a>

## DetachRolePolicyRequestPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachRolePolicyRequestPolicyTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="detachrolepolicyrequestrequesttypedef"></a>

## DetachRolePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachRolePolicyRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `PolicyArn`: `str`

<a id="detachrolepolicyrequestroletypedef"></a>

## DetachRolePolicyRequestRoleTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachRolePolicyRequestRoleTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="detachuserpolicyrequestpolicytypedef"></a>

## DetachUserPolicyRequestPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachUserPolicyRequestPolicyTypeDef
```

Required fields:

- `UserName`: `str`

<a id="detachuserpolicyrequestrequesttypedef"></a>

## DetachUserPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachUserPolicyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `PolicyArn`: `str`

<a id="detachuserpolicyrequestusertypedef"></a>

## DetachUserPolicyRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import DetachUserPolicyRequestUserTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="enablemfadevicerequestmfadevicetypedef"></a>

## EnableMFADeviceRequestMfaDeviceTypeDef

```python
from types_aiobotocore_iam.type_defs import EnableMFADeviceRequestMfaDeviceTypeDef
```

Required fields:

- `AuthenticationCode1`: `str`
- `AuthenticationCode2`: `str`

<a id="enablemfadevicerequestrequesttypedef"></a>

## EnableMFADeviceRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import EnableMFADeviceRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `SerialNumber`: `str`
- `AuthenticationCode1`: `str`
- `AuthenticationCode2`: `str`

<a id="enablemfadevicerequestusertypedef"></a>

## EnableMFADeviceRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import EnableMFADeviceRequestUserTypeDef
```

Required fields:

- `SerialNumber`: `str`
- `AuthenticationCode1`: `str`
- `AuthenticationCode2`: `str`

<a id="entitydetailstypedef"></a>

## EntityDetailsTypeDef

```python
from types_aiobotocore_iam.type_defs import EntityDetailsTypeDef
```

Required fields:

- `EntityInfo`: [EntityInfoTypeDef](./type_defs.md#entityinfotypedef)

Optional fields:

- `LastAuthenticated`: `datetime`

<a id="entityinfotypedef"></a>

## EntityInfoTypeDef

```python
from types_aiobotocore_iam.type_defs import EntityInfoTypeDef
```

Required fields:

- `Arn`: `str`
- `Name`: `str`
- `Type`: [policyOwnerEntityTypeType](./literals.md#policyownerentitytypetype)
- `Id`: `str`

Optional fields:

- `Path`: `str`

<a id="errordetailstypedef"></a>

## ErrorDetailsTypeDef

```python
from types_aiobotocore_iam.type_defs import ErrorDetailsTypeDef
```

Required fields:

- `Message`: `str`
- `Code`: `str`

<a id="evaluationresulttypedef"></a>

## EvaluationResultTypeDef

```python
from types_aiobotocore_iam.type_defs import EvaluationResultTypeDef
```

Required fields:

- `EvalActionName`: `str`
- `EvalDecision`:
  [PolicyEvaluationDecisionTypeType](./literals.md#policyevaluationdecisiontypetype)

Optional fields:

- `EvalResourceName`: `str`
- `MatchedStatements`:
  `List`\[[StatementTypeDef](./type_defs.md#statementtypedef)\]
- `MissingContextValues`: `List`\[`str`\]
- `OrganizationsDecisionDetail`:
  [OrganizationsDecisionDetailTypeDef](./type_defs.md#organizationsdecisiondetailtypedef)
- `PermissionsBoundaryDecisionDetail`:
  [PermissionsBoundaryDecisionDetailTypeDef](./type_defs.md#permissionsboundarydecisiondetailtypedef)
- `EvalDecisionDetails`: `Dict`\[`str`,
  [PolicyEvaluationDecisionTypeType](./literals.md#policyevaluationdecisiontypetype)\]
- `ResourceSpecificResults`:
  `List`\[[ResourceSpecificResultTypeDef](./type_defs.md#resourcespecificresulttypedef)\]

<a id="generatecredentialreportresponsetypedef"></a>

## GenerateCredentialReportResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GenerateCredentialReportResponseTypeDef
```

Required fields:

- `State`: [ReportStateTypeType](./literals.md#reportstatetypetype)
- `Description`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="generateorganizationsaccessreportrequestrequesttypedef"></a>

## GenerateOrganizationsAccessReportRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GenerateOrganizationsAccessReportRequestRequestTypeDef
```

Required fields:

- `EntityPath`: `str`

Optional fields:

- `OrganizationsPolicyId`: `str`

<a id="generateorganizationsaccessreportresponsetypedef"></a>

## GenerateOrganizationsAccessReportResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GenerateOrganizationsAccessReportResponseTypeDef
```

Required fields:

- `JobId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="generateservicelastaccesseddetailsrequestrequesttypedef"></a>

## GenerateServiceLastAccessedDetailsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GenerateServiceLastAccessedDetailsRequestRequestTypeDef
```

Required fields:

- `Arn`: `str`

Optional fields:

- `Granularity`:
  [AccessAdvisorUsageGranularityTypeType](./literals.md#accessadvisorusagegranularitytypetype)

<a id="generateservicelastaccesseddetailsresponsetypedef"></a>

## GenerateServiceLastAccessedDetailsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GenerateServiceLastAccessedDetailsResponseTypeDef
```

Required fields:

- `JobId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getaccesskeylastusedrequestrequesttypedef"></a>

## GetAccessKeyLastUsedRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetAccessKeyLastUsedRequestRequestTypeDef
```

Required fields:

- `AccessKeyId`: `str`

<a id="getaccesskeylastusedresponsetypedef"></a>

## GetAccessKeyLastUsedResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetAccessKeyLastUsedResponseTypeDef
```

Required fields:

- `UserName`: `str`
- `AccessKeyLastUsed`:
  [AccessKeyLastUsedTypeDef](./type_defs.md#accesskeylastusedtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getaccountauthorizationdetailsrequestrequesttypedef"></a>

## GetAccountAuthorizationDetailsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetAccountAuthorizationDetailsRequestRequestTypeDef
```

Optional fields:

- `Filter`: `Sequence`\[[EntityTypeType](./literals.md#entitytypetype)\]
- `MaxItems`: `int`
- `Marker`: `str`

<a id="getaccountauthorizationdetailsresponsetypedef"></a>

## GetAccountAuthorizationDetailsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetAccountAuthorizationDetailsResponseTypeDef
```

Required fields:

- `UserDetailList`:
  `List`\[[UserDetailTypeDef](./type_defs.md#userdetailtypedef)\]
- `GroupDetailList`:
  `List`\[[GroupDetailTypeDef](./type_defs.md#groupdetailtypedef)\]
- `RoleDetailList`:
  `List`\[[RoleDetailTypeDef](./type_defs.md#roledetailtypedef)\]
- `Policies`:
  `List`\[[ManagedPolicyDetailTypeDef](./type_defs.md#managedpolicydetailtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getaccountpasswordpolicyresponsetypedef"></a>

## GetAccountPasswordPolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetAccountPasswordPolicyResponseTypeDef
```

Required fields:

- `PasswordPolicy`:
  [PasswordPolicyTypeDef](./type_defs.md#passwordpolicytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getaccountsummaryresponsetypedef"></a>

## GetAccountSummaryResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetAccountSummaryResponseTypeDef
```

Required fields:

- `SummaryMap`: `Dict`\[[summaryKeyTypeType](./literals.md#summarykeytypetype),
  `int`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcontextkeysforcustompolicyrequestrequesttypedef"></a>

## GetContextKeysForCustomPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetContextKeysForCustomPolicyRequestRequestTypeDef
```

Required fields:

- `PolicyInputList`: `Sequence`\[`str`\]

<a id="getcontextkeysforpolicyresponsetypedef"></a>

## GetContextKeysForPolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetContextKeysForPolicyResponseTypeDef
```

Required fields:

- `ContextKeyNames`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcontextkeysforprincipalpolicyrequestrequesttypedef"></a>

## GetContextKeysForPrincipalPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetContextKeysForPrincipalPolicyRequestRequestTypeDef
```

Required fields:

- `PolicySourceArn`: `str`

Optional fields:

- `PolicyInputList`: `Sequence`\[`str`\]

<a id="getcredentialreportresponsetypedef"></a>

## GetCredentialReportResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetCredentialReportResponseTypeDef
```

Required fields:

- `Content`: `bytes`
- `ReportFormat`: `Literal['text/csv']` (see
  [ReportFormatTypeType](./literals.md#reportformattypetype))
- `GeneratedTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getgrouppolicyrequestrequesttypedef"></a>

## GetGroupPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetGroupPolicyRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`
- `PolicyName`: `str`

<a id="getgrouppolicyresponsetypedef"></a>

## GetGroupPolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetGroupPolicyResponseTypeDef
```

Required fields:

- `GroupName`: `str`
- `PolicyName`: `str`
- `PolicyDocument`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getgrouprequestrequesttypedef"></a>

## GetGroupRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetGroupRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="getgroupresponsetypedef"></a>

## GetGroupResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetGroupResponseTypeDef
```

Required fields:

- `Group`: [GroupTypeDef](./type_defs.md#grouptypedef)
- `Users`: `List`\[[UserTypeDef](./type_defs.md#usertypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getinstanceprofilerequestrequesttypedef"></a>

## GetInstanceProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetInstanceProfileRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`

<a id="getinstanceprofileresponsetypedef"></a>

## GetInstanceProfileResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetInstanceProfileResponseTypeDef
```

Required fields:

- `InstanceProfile`:
  [InstanceProfileTypeDef](./type_defs.md#instanceprofiletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getloginprofilerequestrequesttypedef"></a>

## GetLoginProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetLoginProfileRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

<a id="getloginprofileresponsetypedef"></a>

## GetLoginProfileResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetLoginProfileResponseTypeDef
```

Required fields:

- `LoginProfile`: [LoginProfileTypeDef](./type_defs.md#loginprofiletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getopenidconnectproviderrequestrequesttypedef"></a>

## GetOpenIDConnectProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetOpenIDConnectProviderRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`

<a id="getopenidconnectproviderresponsetypedef"></a>

## GetOpenIDConnectProviderResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetOpenIDConnectProviderResponseTypeDef
```

Required fields:

- `Url`: `str`
- `ClientIDList`: `List`\[`str`\]
- `ThumbprintList`: `List`\[`str`\]
- `CreateDate`: `datetime`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getorganizationsaccessreportrequestrequesttypedef"></a>

## GetOrganizationsAccessReportRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetOrganizationsAccessReportRequestRequestTypeDef
```

Required fields:

- `JobId`: `str`

Optional fields:

- `MaxItems`: `int`
- `Marker`: `str`
- `SortKey`: [sortKeyTypeType](./literals.md#sortkeytypetype)

<a id="getorganizationsaccessreportresponsetypedef"></a>

## GetOrganizationsAccessReportResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetOrganizationsAccessReportResponseTypeDef
```

Required fields:

- `JobStatus`: [jobStatusTypeType](./literals.md#jobstatustypetype)
- `JobCreationDate`: `datetime`
- `JobCompletionDate`: `datetime`
- `NumberOfServicesAccessible`: `int`
- `NumberOfServicesNotAccessed`: `int`
- `AccessDetails`:
  `List`\[[AccessDetailTypeDef](./type_defs.md#accessdetailtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ErrorDetails`: [ErrorDetailsTypeDef](./type_defs.md#errordetailstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getpolicyrequestrequesttypedef"></a>

## GetPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetPolicyRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`

<a id="getpolicyresponsetypedef"></a>

## GetPolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetPolicyResponseTypeDef
```

Required fields:

- `Policy`: [PolicyTypeDef](./type_defs.md#policytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getpolicyversionrequestrequesttypedef"></a>

## GetPolicyVersionRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetPolicyVersionRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`
- `VersionId`: `str`

<a id="getpolicyversionresponsetypedef"></a>

## GetPolicyVersionResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetPolicyVersionResponseTypeDef
```

Required fields:

- `PolicyVersion`: [PolicyVersionTypeDef](./type_defs.md#policyversiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getrolepolicyrequestrequesttypedef"></a>

## GetRolePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetRolePolicyRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `PolicyName`: `str`

<a id="getrolepolicyresponsetypedef"></a>

## GetRolePolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetRolePolicyResponseTypeDef
```

Required fields:

- `RoleName`: `str`
- `PolicyName`: `str`
- `PolicyDocument`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getrolerequestrequesttypedef"></a>

## GetRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="getroleresponsetypedef"></a>

## GetRoleResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetRoleResponseTypeDef
```

Required fields:

- `Role`: [RoleTypeDef](./type_defs.md#roletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsamlproviderrequestrequesttypedef"></a>

## GetSAMLProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetSAMLProviderRequestRequestTypeDef
```

Required fields:

- `SAMLProviderArn`: `str`

<a id="getsamlproviderresponsetypedef"></a>

## GetSAMLProviderResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetSAMLProviderResponseTypeDef
```

Required fields:

- `SAMLMetadataDocument`: `str`
- `CreateDate`: `datetime`
- `ValidUntil`: `datetime`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsshpublickeyrequestrequesttypedef"></a>

## GetSSHPublicKeyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetSSHPublicKeyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `SSHPublicKeyId`: `str`
- `Encoding`: [encodingTypeType](./literals.md#encodingtypetype)

<a id="getsshpublickeyresponsetypedef"></a>

## GetSSHPublicKeyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetSSHPublicKeyResponseTypeDef
```

Required fields:

- `SSHPublicKey`: [SSHPublicKeyTypeDef](./type_defs.md#sshpublickeytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getservercertificaterequestrequesttypedef"></a>

## GetServerCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServerCertificateRequestRequestTypeDef
```

Required fields:

- `ServerCertificateName`: `str`

<a id="getservercertificateresponsetypedef"></a>

## GetServerCertificateResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServerCertificateResponseTypeDef
```

Required fields:

- `ServerCertificate`:
  [ServerCertificateTypeDef](./type_defs.md#servercertificatetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getservicelastaccesseddetailsrequestrequesttypedef"></a>

## GetServiceLastAccessedDetailsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServiceLastAccessedDetailsRequestRequestTypeDef
```

Required fields:

- `JobId`: `str`

Optional fields:

- `MaxItems`: `int`
- `Marker`: `str`

<a id="getservicelastaccesseddetailsresponsetypedef"></a>

## GetServiceLastAccessedDetailsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServiceLastAccessedDetailsResponseTypeDef
```

Required fields:

- `JobStatus`: [jobStatusTypeType](./literals.md#jobstatustypetype)
- `JobType`:
  [AccessAdvisorUsageGranularityTypeType](./literals.md#accessadvisorusagegranularitytypetype)
- `JobCreationDate`: `datetime`
- `ServicesLastAccessed`:
  `List`\[[ServiceLastAccessedTypeDef](./type_defs.md#servicelastaccessedtypedef)\]
- `JobCompletionDate`: `datetime`
- `IsTruncated`: `bool`
- `Marker`: `str`
- `Error`: [ErrorDetailsTypeDef](./type_defs.md#errordetailstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getservicelastaccesseddetailswithentitiesrequestrequesttypedef"></a>

## GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef
```

Required fields:

- `JobId`: `str`
- `ServiceNamespace`: `str`

Optional fields:

- `MaxItems`: `int`
- `Marker`: `str`

<a id="getservicelastaccesseddetailswithentitiesresponsetypedef"></a>

## GetServiceLastAccessedDetailsWithEntitiesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServiceLastAccessedDetailsWithEntitiesResponseTypeDef
```

Required fields:

- `JobStatus`: [jobStatusTypeType](./literals.md#jobstatustypetype)
- `JobCreationDate`: `datetime`
- `JobCompletionDate`: `datetime`
- `EntityDetailsList`:
  `List`\[[EntityDetailsTypeDef](./type_defs.md#entitydetailstypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `Error`: [ErrorDetailsTypeDef](./type_defs.md#errordetailstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getservicelinkedroledeletionstatusrequestrequesttypedef"></a>

## GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef
```

Required fields:

- `DeletionTaskId`: `str`

<a id="getservicelinkedroledeletionstatusresponsetypedef"></a>

## GetServiceLinkedRoleDeletionStatusResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetServiceLinkedRoleDeletionStatusResponseTypeDef
```

Required fields:

- `Status`:
  [DeletionTaskStatusTypeType](./literals.md#deletiontaskstatustypetype)
- `Reason`:
  [DeletionTaskFailureReasonTypeTypeDef](./type_defs.md#deletiontaskfailurereasontypetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getuserpolicyrequestrequesttypedef"></a>

## GetUserPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetUserPolicyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `PolicyName`: `str`

<a id="getuserpolicyresponsetypedef"></a>

## GetUserPolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetUserPolicyResponseTypeDef
```

Required fields:

- `UserName`: `str`
- `PolicyName`: `str`
- `PolicyDocument`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getuserrequestrequesttypedef"></a>

## GetUserRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GetUserRequestRequestTypeDef
```

Optional fields:

- `UserName`: `str`

<a id="getuserresponsetypedef"></a>

## GetUserResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import GetUserResponseTypeDef
```

Required fields:

- `User`: [UserTypeDef](./type_defs.md#usertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="groupdetailtypedef"></a>

## GroupDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import GroupDetailTypeDef
```

Optional fields:

- `Path`: `str`
- `GroupName`: `str`
- `GroupId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`
- `GroupPolicyList`:
  `List`\[[PolicyDetailTypeDef](./type_defs.md#policydetailtypedef)\]
- `AttachedManagedPolicies`:
  `List`\[[AttachedPolicyTypeDef](./type_defs.md#attachedpolicytypedef)\]

<a id="grouppolicyrequesttypedef"></a>

## GroupPolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import GroupPolicyRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="grouptypedef"></a>

## GroupTypeDef

```python
from types_aiobotocore_iam.type_defs import GroupTypeDef
```

Required fields:

- `Path`: `str`
- `GroupName`: `str`
- `GroupId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`

<a id="instanceprofiletypedef"></a>

## InstanceProfileTypeDef

```python
from types_aiobotocore_iam.type_defs import InstanceProfileTypeDef
```

Required fields:

- `Path`: `str`
- `InstanceProfileName`: `str`
- `InstanceProfileId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`
- `Roles`: `List`\[[RoleTypeDef](./type_defs.md#roletypedef)\]

Optional fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="listaccesskeysrequestrequesttypedef"></a>

## ListAccessKeysRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAccessKeysRequestRequestTypeDef
```

Optional fields:

- `UserName`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listaccesskeysresponsetypedef"></a>

## ListAccessKeysResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAccessKeysResponseTypeDef
```

Required fields:

- `AccessKeyMetadata`:
  `List`\[[AccessKeyMetadataTypeDef](./type_defs.md#accesskeymetadatatypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listaccountaliasesrequestrequesttypedef"></a>

## ListAccountAliasesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAccountAliasesRequestRequestTypeDef
```

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listaccountaliasesresponsetypedef"></a>

## ListAccountAliasesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAccountAliasesResponseTypeDef
```

Required fields:

- `AccountAliases`: `List`\[`str`\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listattachedgrouppoliciesrequestrequesttypedef"></a>

## ListAttachedGroupPoliciesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAttachedGroupPoliciesRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listattachedgrouppoliciesresponsetypedef"></a>

## ListAttachedGroupPoliciesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAttachedGroupPoliciesResponseTypeDef
```

Required fields:

- `AttachedPolicies`:
  `List`\[[AttachedPolicyTypeDef](./type_defs.md#attachedpolicytypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listattachedrolepoliciesrequestrequesttypedef"></a>

## ListAttachedRolePoliciesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAttachedRolePoliciesRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listattachedrolepoliciesresponsetypedef"></a>

## ListAttachedRolePoliciesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAttachedRolePoliciesResponseTypeDef
```

Required fields:

- `AttachedPolicies`:
  `List`\[[AttachedPolicyTypeDef](./type_defs.md#attachedpolicytypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listattacheduserpoliciesrequestrequesttypedef"></a>

## ListAttachedUserPoliciesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAttachedUserPoliciesRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listattacheduserpoliciesresponsetypedef"></a>

## ListAttachedUserPoliciesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListAttachedUserPoliciesResponseTypeDef
```

Required fields:

- `AttachedPolicies`:
  `List`\[[AttachedPolicyTypeDef](./type_defs.md#attachedpolicytypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listentitiesforpolicyrequestrequesttypedef"></a>

## ListEntitiesForPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListEntitiesForPolicyRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`

Optional fields:

- `EntityFilter`: [EntityTypeType](./literals.md#entitytypetype)
- `PathPrefix`: `str`
- `PolicyUsageFilter`: [PolicyUsageTypeType](./literals.md#policyusagetypetype)
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listentitiesforpolicyresponsetypedef"></a>

## ListEntitiesForPolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListEntitiesForPolicyResponseTypeDef
```

Required fields:

- `PolicyGroups`:
  `List`\[[PolicyGroupTypeDef](./type_defs.md#policygrouptypedef)\]
- `PolicyUsers`:
  `List`\[[PolicyUserTypeDef](./type_defs.md#policyusertypedef)\]
- `PolicyRoles`:
  `List`\[[PolicyRoleTypeDef](./type_defs.md#policyroletypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listgrouppoliciesrequestrequesttypedef"></a>

## ListGroupPoliciesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListGroupPoliciesRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listgrouppoliciesresponsetypedef"></a>

## ListGroupPoliciesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListGroupPoliciesResponseTypeDef
```

Required fields:

- `PolicyNames`: `List`\[`str`\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listgroupsforuserrequestrequesttypedef"></a>

## ListGroupsForUserRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListGroupsForUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listgroupsforuserresponsetypedef"></a>

## ListGroupsForUserResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListGroupsForUserResponseTypeDef
```

Required fields:

- `Groups`: `List`\[[GroupTypeDef](./type_defs.md#grouptypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listgroupsrequestrequesttypedef"></a>

## ListGroupsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListGroupsRequestRequestTypeDef
```

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listgroupsresponsetypedef"></a>

## ListGroupsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListGroupsResponseTypeDef
```

Required fields:

- `Groups`: `List`\[[GroupTypeDef](./type_defs.md#grouptypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinstanceprofiletagsrequestrequesttypedef"></a>

## ListInstanceProfileTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListInstanceProfileTagsRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listinstanceprofiletagsresponsetypedef"></a>

## ListInstanceProfileTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListInstanceProfileTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinstanceprofilesforrolerequestrequesttypedef"></a>

## ListInstanceProfilesForRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListInstanceProfilesForRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listinstanceprofilesforroleresponsetypedef"></a>

## ListInstanceProfilesForRoleResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListInstanceProfilesForRoleResponseTypeDef
```

Required fields:

- `InstanceProfiles`:
  `List`\[[InstanceProfileTypeDef](./type_defs.md#instanceprofiletypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinstanceprofilesrequestrequesttypedef"></a>

## ListInstanceProfilesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListInstanceProfilesRequestRequestTypeDef
```

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listinstanceprofilesresponsetypedef"></a>

## ListInstanceProfilesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListInstanceProfilesResponseTypeDef
```

Required fields:

- `InstanceProfiles`:
  `List`\[[InstanceProfileTypeDef](./type_defs.md#instanceprofiletypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmfadevicetagsrequestrequesttypedef"></a>

## ListMFADeviceTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListMFADeviceTagsRequestRequestTypeDef
```

Required fields:

- `SerialNumber`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listmfadevicetagsresponsetypedef"></a>

## ListMFADeviceTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListMFADeviceTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmfadevicesrequestrequesttypedef"></a>

## ListMFADevicesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListMFADevicesRequestRequestTypeDef
```

Optional fields:

- `UserName`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listmfadevicesresponsetypedef"></a>

## ListMFADevicesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListMFADevicesResponseTypeDef
```

Required fields:

- `MFADevices`: `List`\[[MFADeviceTypeDef](./type_defs.md#mfadevicetypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listopenidconnectprovidertagsrequestrequesttypedef"></a>

## ListOpenIDConnectProviderTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListOpenIDConnectProviderTagsRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listopenidconnectprovidertagsresponsetypedef"></a>

## ListOpenIDConnectProviderTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListOpenIDConnectProviderTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listopenidconnectprovidersresponsetypedef"></a>

## ListOpenIDConnectProvidersResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListOpenIDConnectProvidersResponseTypeDef
```

Required fields:

- `OpenIDConnectProviderList`:
  `List`\[[OpenIDConnectProviderListEntryTypeDef](./type_defs.md#openidconnectproviderlistentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpoliciesgrantingserviceaccessentrytypedef"></a>

## ListPoliciesGrantingServiceAccessEntryTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPoliciesGrantingServiceAccessEntryTypeDef
```

Optional fields:

- `ServiceNamespace`: `str`
- `Policies`:
  `List`\[[PolicyGrantingServiceAccessTypeDef](./type_defs.md#policygrantingserviceaccesstypedef)\]

<a id="listpoliciesgrantingserviceaccessrequestrequesttypedef"></a>

## ListPoliciesGrantingServiceAccessRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPoliciesGrantingServiceAccessRequestRequestTypeDef
```

Required fields:

- `Arn`: `str`
- `ServiceNamespaces`: `Sequence`\[`str`\]

Optional fields:

- `Marker`: `str`

<a id="listpoliciesgrantingserviceaccessresponsetypedef"></a>

## ListPoliciesGrantingServiceAccessResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPoliciesGrantingServiceAccessResponseTypeDef
```

Required fields:

- `PoliciesGrantingServiceAccess`:
  `List`\[[ListPoliciesGrantingServiceAccessEntryTypeDef](./type_defs.md#listpoliciesgrantingserviceaccessentrytypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpoliciesrequestrequesttypedef"></a>

## ListPoliciesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPoliciesRequestRequestTypeDef
```

Optional fields:

- `Scope`: [policyScopeTypeType](./literals.md#policyscopetypetype)
- `OnlyAttached`: `bool`
- `PathPrefix`: `str`
- `PolicyUsageFilter`: [PolicyUsageTypeType](./literals.md#policyusagetypetype)
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listpoliciesresponsetypedef"></a>

## ListPoliciesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPoliciesResponseTypeDef
```

Required fields:

- `Policies`: `List`\[[PolicyTypeDef](./type_defs.md#policytypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpolicytagsrequestrequesttypedef"></a>

## ListPolicyTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPolicyTagsRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listpolicytagsresponsetypedef"></a>

## ListPolicyTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPolicyTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpolicyversionsrequestrequesttypedef"></a>

## ListPolicyVersionsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPolicyVersionsRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listpolicyversionsresponsetypedef"></a>

## ListPolicyVersionsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListPolicyVersionsResponseTypeDef
```

Required fields:

- `Versions`:
  `List`\[[PolicyVersionTypeDef](./type_defs.md#policyversiontypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listrolepoliciesrequestrequesttypedef"></a>

## ListRolePoliciesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListRolePoliciesRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listrolepoliciesresponsetypedef"></a>

## ListRolePoliciesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListRolePoliciesResponseTypeDef
```

Required fields:

- `PolicyNames`: `List`\[`str`\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listroletagsrequestrequesttypedef"></a>

## ListRoleTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListRoleTagsRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listroletagsresponsetypedef"></a>

## ListRoleTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListRoleTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listrolesrequestrequesttypedef"></a>

## ListRolesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListRolesRequestRequestTypeDef
```

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listrolesresponsetypedef"></a>

## ListRolesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListRolesResponseTypeDef
```

Required fields:

- `Roles`: `List`\[[RoleTypeDef](./type_defs.md#roletypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listsamlprovidertagsrequestrequesttypedef"></a>

## ListSAMLProviderTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListSAMLProviderTagsRequestRequestTypeDef
```

Required fields:

- `SAMLProviderArn`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listsamlprovidertagsresponsetypedef"></a>

## ListSAMLProviderTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListSAMLProviderTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listsamlprovidersresponsetypedef"></a>

## ListSAMLProvidersResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListSAMLProvidersResponseTypeDef
```

Required fields:

- `SAMLProviderList`:
  `List`\[[SAMLProviderListEntryTypeDef](./type_defs.md#samlproviderlistentrytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listsshpublickeysrequestrequesttypedef"></a>

## ListSSHPublicKeysRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListSSHPublicKeysRequestRequestTypeDef
```

Optional fields:

- `UserName`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listsshpublickeysresponsetypedef"></a>

## ListSSHPublicKeysResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListSSHPublicKeysResponseTypeDef
```

Required fields:

- `SSHPublicKeys`:
  `List`\[[SSHPublicKeyMetadataTypeDef](./type_defs.md#sshpublickeymetadatatypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listservercertificatetagsrequestrequesttypedef"></a>

## ListServerCertificateTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListServerCertificateTagsRequestRequestTypeDef
```

Required fields:

- `ServerCertificateName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listservercertificatetagsresponsetypedef"></a>

## ListServerCertificateTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListServerCertificateTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listservercertificatesrequestrequesttypedef"></a>

## ListServerCertificatesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListServerCertificatesRequestRequestTypeDef
```

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listservercertificatesresponsetypedef"></a>

## ListServerCertificatesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListServerCertificatesResponseTypeDef
```

Required fields:

- `ServerCertificateMetadataList`:
  `List`\[[ServerCertificateMetadataTypeDef](./type_defs.md#servercertificatemetadatatypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listservicespecificcredentialsrequestrequesttypedef"></a>

## ListServiceSpecificCredentialsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListServiceSpecificCredentialsRequestRequestTypeDef
```

Optional fields:

- `UserName`: `str`
- `ServiceName`: `str`

<a id="listservicespecificcredentialsresponsetypedef"></a>

## ListServiceSpecificCredentialsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListServiceSpecificCredentialsResponseTypeDef
```

Required fields:

- `ServiceSpecificCredentials`:
  `List`\[[ServiceSpecificCredentialMetadataTypeDef](./type_defs.md#servicespecificcredentialmetadatatypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listsigningcertificatesrequestrequesttypedef"></a>

## ListSigningCertificatesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListSigningCertificatesRequestRequestTypeDef
```

Optional fields:

- `UserName`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listsigningcertificatesresponsetypedef"></a>

## ListSigningCertificatesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListSigningCertificatesResponseTypeDef
```

Required fields:

- `Certificates`:
  `List`\[[SigningCertificateTypeDef](./type_defs.md#signingcertificatetypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listuserpoliciesrequestrequesttypedef"></a>

## ListUserPoliciesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListUserPoliciesRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listuserpoliciesresponsetypedef"></a>

## ListUserPoliciesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListUserPoliciesResponseTypeDef
```

Required fields:

- `PolicyNames`: `List`\[`str`\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listusertagsrequestrequesttypedef"></a>

## ListUserTagsRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListUserTagsRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `Marker`: `str`
- `MaxItems`: `int`

<a id="listusertagsresponsetypedef"></a>

## ListUserTagsResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListUserTagsResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listusersrequestrequesttypedef"></a>

## ListUsersRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListUsersRequestRequestTypeDef
```

Optional fields:

- `PathPrefix`: `str`
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listusersresponsetypedef"></a>

## ListUsersResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListUsersResponseTypeDef
```

Required fields:

- `Users`: `List`\[[UserTypeDef](./type_defs.md#usertypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listvirtualmfadevicesrequestrequesttypedef"></a>

## ListVirtualMFADevicesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ListVirtualMFADevicesRequestRequestTypeDef
```

Optional fields:

- `AssignmentStatus`:
  [assignmentStatusTypeType](./literals.md#assignmentstatustypetype)
- `Marker`: `str`
- `MaxItems`: `int`

<a id="listvirtualmfadevicesresponsetypedef"></a>

## ListVirtualMFADevicesResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ListVirtualMFADevicesResponseTypeDef
```

Required fields:

- `VirtualMFADevices`:
  `List`\[[VirtualMFADeviceTypeDef](./type_defs.md#virtualmfadevicetypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="loginprofiletypedef"></a>

## LoginProfileTypeDef

```python
from types_aiobotocore_iam.type_defs import LoginProfileTypeDef
```

Required fields:

- `UserName`: `str`
- `CreateDate`: `datetime`

Optional fields:

- `PasswordResetRequired`: `bool`

<a id="mfadevicetypedef"></a>

## MFADeviceTypeDef

```python
from types_aiobotocore_iam.type_defs import MFADeviceTypeDef
```

Required fields:

- `UserName`: `str`
- `SerialNumber`: `str`
- `EnableDate`: `datetime`

<a id="managedpolicydetailtypedef"></a>

## ManagedPolicyDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import ManagedPolicyDetailTypeDef
```

Optional fields:

- `PolicyName`: `str`
- `PolicyId`: `str`
- `Arn`: `str`
- `Path`: `str`
- `DefaultVersionId`: `str`
- `AttachmentCount`: `int`
- `PermissionsBoundaryUsageCount`: `int`
- `IsAttachable`: `bool`
- `Description`: `str`
- `CreateDate`: `datetime`
- `UpdateDate`: `datetime`
- `PolicyVersionList`:
  `List`\[[PolicyVersionTypeDef](./type_defs.md#policyversiontypedef)\]

<a id="openidconnectproviderlistentrytypedef"></a>

## OpenIDConnectProviderListEntryTypeDef

```python
from types_aiobotocore_iam.type_defs import OpenIDConnectProviderListEntryTypeDef
```

Optional fields:

- `Arn`: `str`

<a id="organizationsdecisiondetailtypedef"></a>

## OrganizationsDecisionDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import OrganizationsDecisionDetailTypeDef
```

Optional fields:

- `AllowedByOrganizations`: `bool`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_iam.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="passwordpolicytypedef"></a>

## PasswordPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import PasswordPolicyTypeDef
```

Optional fields:

- `MinimumPasswordLength`: `int`
- `RequireSymbols`: `bool`
- `RequireNumbers`: `bool`
- `RequireUppercaseCharacters`: `bool`
- `RequireLowercaseCharacters`: `bool`
- `AllowUsersToChangePassword`: `bool`
- `ExpirePasswords`: `bool`
- `MaxPasswordAge`: `int`
- `PasswordReusePrevention`: `int`
- `HardExpiry`: `bool`

<a id="permissionsboundarydecisiondetailtypedef"></a>

## PermissionsBoundaryDecisionDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import PermissionsBoundaryDecisionDetailTypeDef
```

Optional fields:

- `AllowedByPermissionsBoundary`: `bool`

<a id="policydetailtypedef"></a>

## PolicyDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import PolicyDetailTypeDef
```

Optional fields:

- `PolicyName`: `str`
- `PolicyDocument`: `str`

<a id="policygrantingserviceaccesstypedef"></a>

## PolicyGrantingServiceAccessTypeDef

```python
from types_aiobotocore_iam.type_defs import PolicyGrantingServiceAccessTypeDef
```

Required fields:

- `PolicyName`: `str`
- `PolicyType`: [policyTypeType](./literals.md#policytypetype)

Optional fields:

- `PolicyArn`: `str`
- `EntityType`:
  [policyOwnerEntityTypeType](./literals.md#policyownerentitytypetype)
- `EntityName`: `str`

<a id="policygrouptypedef"></a>

## PolicyGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import PolicyGroupTypeDef
```

Optional fields:

- `GroupName`: `str`
- `GroupId`: `str`

<a id="policyroletypedef"></a>

## PolicyRoleTypeDef

```python
from types_aiobotocore_iam.type_defs import PolicyRoleTypeDef
```

Optional fields:

- `RoleName`: `str`
- `RoleId`: `str`

<a id="policytypedef"></a>

## PolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import PolicyTypeDef
```

Optional fields:

- `PolicyName`: `str`
- `PolicyId`: `str`
- `Arn`: `str`
- `Path`: `str`
- `DefaultVersionId`: `str`
- `AttachmentCount`: `int`
- `PermissionsBoundaryUsageCount`: `int`
- `IsAttachable`: `bool`
- `Description`: `str`
- `CreateDate`: `datetime`
- `UpdateDate`: `datetime`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="policyusertypedef"></a>

## PolicyUserTypeDef

```python
from types_aiobotocore_iam.type_defs import PolicyUserTypeDef
```

Optional fields:

- `UserName`: `str`
- `UserId`: `str`

<a id="policyversiontypedef"></a>

## PolicyVersionTypeDef

```python
from types_aiobotocore_iam.type_defs import PolicyVersionTypeDef
```

Optional fields:

- `Document`: `str`
- `VersionId`: `str`
- `IsDefaultVersion`: `bool`
- `CreateDate`: `datetime`

<a id="positiontypedef"></a>

## PositionTypeDef

```python
from types_aiobotocore_iam.type_defs import PositionTypeDef
```

Optional fields:

- `Line`: `int`
- `Column`: `int`

<a id="putgrouppolicyrequestgrouppolicytypedef"></a>

## PutGroupPolicyRequestGroupPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import PutGroupPolicyRequestGroupPolicyTypeDef
```

Required fields:

- `PolicyDocument`: `str`

<a id="putgrouppolicyrequestgrouptypedef"></a>

## PutGroupPolicyRequestGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import PutGroupPolicyRequestGroupTypeDef
```

Required fields:

- `PolicyName`: `str`
- `PolicyDocument`: `str`

<a id="putgrouppolicyrequestrequesttypedef"></a>

## PutGroupPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import PutGroupPolicyRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`
- `PolicyName`: `str`
- `PolicyDocument`: `str`

<a id="putrolepermissionsboundaryrequestrequesttypedef"></a>

## PutRolePermissionsBoundaryRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import PutRolePermissionsBoundaryRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `PermissionsBoundary`: `str`

<a id="putrolepolicyrequestrequesttypedef"></a>

## PutRolePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import PutRolePolicyRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `PolicyName`: `str`
- `PolicyDocument`: `str`

<a id="putrolepolicyrequestrolepolicytypedef"></a>

## PutRolePolicyRequestRolePolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import PutRolePolicyRequestRolePolicyTypeDef
```

Required fields:

- `PolicyDocument`: `str`

<a id="putuserpermissionsboundaryrequestrequesttypedef"></a>

## PutUserPermissionsBoundaryRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import PutUserPermissionsBoundaryRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `PermissionsBoundary`: `str`

<a id="putuserpolicyrequestrequesttypedef"></a>

## PutUserPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import PutUserPolicyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `PolicyName`: `str`
- `PolicyDocument`: `str`

<a id="putuserpolicyrequestuserpolicytypedef"></a>

## PutUserPolicyRequestUserPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import PutUserPolicyRequestUserPolicyTypeDef
```

Required fields:

- `PolicyDocument`: `str`

<a id="putuserpolicyrequestusertypedef"></a>

## PutUserPolicyRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import PutUserPolicyRequestUserTypeDef
```

Required fields:

- `PolicyName`: `str`
- `PolicyDocument`: `str`

<a id="removeclientidfromopenidconnectproviderrequestrequesttypedef"></a>

## RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`
- `ClientID`: `str`

<a id="removerolefrominstanceprofilerequestinstanceprofiletypedef"></a>

## RemoveRoleFromInstanceProfileRequestInstanceProfileTypeDef

```python
from types_aiobotocore_iam.type_defs import RemoveRoleFromInstanceProfileRequestInstanceProfileTypeDef
```

Required fields:

- `RoleName`: `str`

<a id="removerolefrominstanceprofilerequestrequesttypedef"></a>

## RemoveRoleFromInstanceProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import RemoveRoleFromInstanceProfileRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`
- `RoleName`: `str`

<a id="removeuserfromgrouprequestgrouptypedef"></a>

## RemoveUserFromGroupRequestGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import RemoveUserFromGroupRequestGroupTypeDef
```

Required fields:

- `UserName`: `str`

<a id="removeuserfromgrouprequestrequesttypedef"></a>

## RemoveUserFromGroupRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import RemoveUserFromGroupRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`
- `UserName`: `str`

<a id="removeuserfromgrouprequestusertypedef"></a>

## RemoveUserFromGroupRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import RemoveUserFromGroupRequestUserTypeDef
```

Required fields:

- `GroupName`: `str`

<a id="resetservicespecificcredentialrequestrequesttypedef"></a>

## ResetServiceSpecificCredentialRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ResetServiceSpecificCredentialRequestRequestTypeDef
```

Required fields:

- `ServiceSpecificCredentialId`: `str`

Optional fields:

- `UserName`: `str`

<a id="resetservicespecificcredentialresponsetypedef"></a>

## ResetServiceSpecificCredentialResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import ResetServiceSpecificCredentialResponseTypeDef
```

Required fields:

- `ServiceSpecificCredential`:
  [ServiceSpecificCredentialTypeDef](./type_defs.md#servicespecificcredentialtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="resourcespecificresulttypedef"></a>

## ResourceSpecificResultTypeDef

```python
from types_aiobotocore_iam.type_defs import ResourceSpecificResultTypeDef
```

Required fields:

- `EvalResourceName`: `str`
- `EvalResourceDecision`:
  [PolicyEvaluationDecisionTypeType](./literals.md#policyevaluationdecisiontypetype)

Optional fields:

- `MatchedStatements`:
  `List`\[[StatementTypeDef](./type_defs.md#statementtypedef)\]
- `MissingContextValues`: `List`\[`str`\]
- `EvalDecisionDetails`: `Dict`\[`str`,
  [PolicyEvaluationDecisionTypeType](./literals.md#policyevaluationdecisiontypetype)\]
- `PermissionsBoundaryDecisionDetail`:
  [PermissionsBoundaryDecisionDetailTypeDef](./type_defs.md#permissionsboundarydecisiondetailtypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="resyncmfadevicerequestmfadevicetypedef"></a>

## ResyncMFADeviceRequestMfaDeviceTypeDef

```python
from types_aiobotocore_iam.type_defs import ResyncMFADeviceRequestMfaDeviceTypeDef
```

Required fields:

- `AuthenticationCode1`: `str`
- `AuthenticationCode2`: `str`

<a id="resyncmfadevicerequestrequesttypedef"></a>

## ResyncMFADeviceRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ResyncMFADeviceRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `SerialNumber`: `str`
- `AuthenticationCode1`: `str`
- `AuthenticationCode2`: `str`

<a id="roledetailtypedef"></a>

## RoleDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import RoleDetailTypeDef
```

Optional fields:

- `Path`: `str`
- `RoleName`: `str`
- `RoleId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`
- `AssumeRolePolicyDocument`: `str`
- `InstanceProfileList`:
  `List`\[[InstanceProfileTypeDef](./type_defs.md#instanceprofiletypedef)\]
- `RolePolicyList`:
  `List`\[[PolicyDetailTypeDef](./type_defs.md#policydetailtypedef)\]
- `AttachedManagedPolicies`:
  `List`\[[AttachedPolicyTypeDef](./type_defs.md#attachedpolicytypedef)\]
- `PermissionsBoundary`:
  [AttachedPermissionsBoundaryTypeDef](./type_defs.md#attachedpermissionsboundarytypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `RoleLastUsed`: [RoleLastUsedTypeDef](./type_defs.md#rolelastusedtypedef)

<a id="rolelastusedresponsemetadatatypedef"></a>

## RoleLastUsedResponseMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import RoleLastUsedResponseMetadataTypeDef
```

Required fields:

- `LastUsedDate`: `datetime`
- `Region`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="rolelastusedtypedef"></a>

## RoleLastUsedTypeDef

```python
from types_aiobotocore_iam.type_defs import RoleLastUsedTypeDef
```

Optional fields:

- `LastUsedDate`: `datetime`
- `Region`: `str`

<a id="rolepolicyrequesttypedef"></a>

## RolePolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import RolePolicyRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="roletypedef"></a>

## RoleTypeDef

```python
from types_aiobotocore_iam.type_defs import RoleTypeDef
```

Required fields:

- `Path`: `str`
- `RoleName`: `str`
- `RoleId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`

Optional fields:

- `AssumeRolePolicyDocument`: `str`
- `Description`: `str`
- `MaxSessionDuration`: `int`
- `PermissionsBoundary`:
  [AttachedPermissionsBoundaryTypeDef](./type_defs.md#attachedpermissionsboundarytypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `RoleLastUsed`: [RoleLastUsedTypeDef](./type_defs.md#rolelastusedtypedef)

<a id="roleusagetypetypedef"></a>

## RoleUsageTypeTypeDef

```python
from types_aiobotocore_iam.type_defs import RoleUsageTypeTypeDef
```

Optional fields:

- `Region`: `str`
- `Resources`: `List`\[`str`\]

<a id="samlproviderlistentrytypedef"></a>

## SAMLProviderListEntryTypeDef

```python
from types_aiobotocore_iam.type_defs import SAMLProviderListEntryTypeDef
```

Optional fields:

- `Arn`: `str`
- `ValidUntil`: `datetime`
- `CreateDate`: `datetime`

<a id="sshpublickeymetadatatypedef"></a>

## SSHPublicKeyMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import SSHPublicKeyMetadataTypeDef
```

Required fields:

- `UserName`: `str`
- `SSHPublicKeyId`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)
- `UploadDate`: `datetime`

<a id="sshpublickeytypedef"></a>

## SSHPublicKeyTypeDef

```python
from types_aiobotocore_iam.type_defs import SSHPublicKeyTypeDef
```

Required fields:

- `UserName`: `str`
- `SSHPublicKeyId`: `str`
- `Fingerprint`: `str`
- `SSHPublicKeyBody`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)

Optional fields:

- `UploadDate`: `datetime`

<a id="servercertificatemetadataresponsemetadatatypedef"></a>

## ServerCertificateMetadataResponseMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import ServerCertificateMetadataResponseMetadataTypeDef
```

Required fields:

- `Path`: `str`
- `ServerCertificateName`: `str`
- `ServerCertificateId`: `str`
- `Arn`: `str`
- `UploadDate`: `datetime`
- `Expiration`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="servercertificatemetadatatypedef"></a>

## ServerCertificateMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import ServerCertificateMetadataTypeDef
```

Required fields:

- `Path`: `str`
- `ServerCertificateName`: `str`
- `ServerCertificateId`: `str`
- `Arn`: `str`

Optional fields:

- `UploadDate`: `datetime`
- `Expiration`: `datetime`

<a id="servercertificatetypedef"></a>

## ServerCertificateTypeDef

```python
from types_aiobotocore_iam.type_defs import ServerCertificateTypeDef
```

Required fields:

- `ServerCertificateMetadata`:
  [ServerCertificateMetadataTypeDef](./type_defs.md#servercertificatemetadatatypedef)
- `CertificateBody`: `str`

Optional fields:

- `CertificateChain`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="servicelastaccessedtypedef"></a>

## ServiceLastAccessedTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceLastAccessedTypeDef
```

Required fields:

- `ServiceName`: `str`
- `ServiceNamespace`: `str`

Optional fields:

- `LastAuthenticated`: `datetime`
- `LastAuthenticatedEntity`: `str`
- `LastAuthenticatedRegion`: `str`
- `TotalAuthenticatedEntities`: `int`
- `TrackedActionsLastAccessed`:
  `List`\[[TrackedActionLastAccessedTypeDef](./type_defs.md#trackedactionlastaccessedtypedef)\]

<a id="serviceresourceaccesskeypairrequesttypedef"></a>

## ServiceResourceAccessKeyPairRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceAccessKeyPairRequestTypeDef
```

Required fields:

- `user_name`: `str`
- `id`: `str`
- `secret`: `str`

<a id="serviceresourceaccesskeyrequesttypedef"></a>

## ServiceResourceAccessKeyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceAccessKeyRequestTypeDef
```

Required fields:

- `user_name`: `str`
- `id`: `str`

<a id="serviceresourceassumerolepolicyrequesttypedef"></a>

## ServiceResourceAssumeRolePolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceAssumeRolePolicyRequestTypeDef
```

Required fields:

- `role_name`: `str`

<a id="serviceresourcegrouppolicyrequesttypedef"></a>

## ServiceResourceGroupPolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceGroupPolicyRequestTypeDef
```

Required fields:

- `group_name`: `str`
- `name`: `str`

<a id="serviceresourcegrouprequesttypedef"></a>

## ServiceResourceGroupRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceGroupRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="serviceresourceinstanceprofilerequesttypedef"></a>

## ServiceResourceInstanceProfileRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceInstanceProfileRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="serviceresourceloginprofilerequesttypedef"></a>

## ServiceResourceLoginProfileRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceLoginProfileRequestTypeDef
```

Required fields:

- `user_name`: `str`

<a id="serviceresourcemfadevicerequesttypedef"></a>

## ServiceResourceMfaDeviceRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceMfaDeviceRequestTypeDef
```

Required fields:

- `user_name`: `str`
- `serial_number`: `str`

<a id="serviceresourcepolicyrequesttypedef"></a>

## ServiceResourcePolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourcePolicyRequestTypeDef
```

Required fields:

- `policy_arn`: `str`

<a id="serviceresourcepolicyversionrequesttypedef"></a>

## ServiceResourcePolicyVersionRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourcePolicyVersionRequestTypeDef
```

Required fields:

- `arn`: `str`
- `version_id`: `str`

<a id="serviceresourcerolepolicyrequesttypedef"></a>

## ServiceResourceRolePolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceRolePolicyRequestTypeDef
```

Required fields:

- `role_name`: `str`
- `name`: `str`

<a id="serviceresourcerolerequesttypedef"></a>

## ServiceResourceRoleRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceRoleRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="serviceresourcesamlproviderrequesttypedef"></a>

## ServiceResourceSamlProviderRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceSamlProviderRequestTypeDef
```

Required fields:

- `arn`: `str`

<a id="serviceresourceservercertificaterequesttypedef"></a>

## ServiceResourceServerCertificateRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceServerCertificateRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="serviceresourcesigningcertificaterequesttypedef"></a>

## ServiceResourceSigningCertificateRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceSigningCertificateRequestTypeDef
```

Required fields:

- `user_name`: `str`
- `id`: `str`

<a id="serviceresourceuserpolicyrequesttypedef"></a>

## ServiceResourceUserPolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceUserPolicyRequestTypeDef
```

Required fields:

- `user_name`: `str`
- `name`: `str`

<a id="serviceresourceuserrequesttypedef"></a>

## ServiceResourceUserRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceUserRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="serviceresourcevirtualmfadevicerequesttypedef"></a>

## ServiceResourceVirtualMfaDeviceRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceResourceVirtualMfaDeviceRequestTypeDef
```

Required fields:

- `serial_number`: `str`

<a id="servicespecificcredentialmetadatatypedef"></a>

## ServiceSpecificCredentialMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceSpecificCredentialMetadataTypeDef
```

Required fields:

- `UserName`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)
- `ServiceUserName`: `str`
- `CreateDate`: `datetime`
- `ServiceSpecificCredentialId`: `str`
- `ServiceName`: `str`

<a id="servicespecificcredentialtypedef"></a>

## ServiceSpecificCredentialTypeDef

```python
from types_aiobotocore_iam.type_defs import ServiceSpecificCredentialTypeDef
```

Required fields:

- `CreateDate`: `datetime`
- `ServiceName`: `str`
- `ServiceUserName`: `str`
- `ServicePassword`: `str`
- `ServiceSpecificCredentialId`: `str`
- `UserName`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)

<a id="setdefaultpolicyversionrequestrequesttypedef"></a>

## SetDefaultPolicyVersionRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import SetDefaultPolicyVersionRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`
- `VersionId`: `str`

<a id="setsecuritytokenservicepreferencesrequestrequesttypedef"></a>

## SetSecurityTokenServicePreferencesRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import SetSecurityTokenServicePreferencesRequestRequestTypeDef
```

Required fields:

- `GlobalEndpointTokenVersion`:
  [globalEndpointTokenVersionType](./literals.md#globalendpointtokenversiontype)

<a id="signingcertificatetypedef"></a>

## SigningCertificateTypeDef

```python
from types_aiobotocore_iam.type_defs import SigningCertificateTypeDef
```

Required fields:

- `UserName`: `str`
- `CertificateId`: `str`
- `CertificateBody`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)

Optional fields:

- `UploadDate`: `datetime`

<a id="simulatecustompolicyrequestrequesttypedef"></a>

## SimulateCustomPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import SimulateCustomPolicyRequestRequestTypeDef
```

Required fields:

- `PolicyInputList`: `Sequence`\[`str`\]
- `ActionNames`: `Sequence`\[`str`\]

Optional fields:

- `PermissionsBoundaryPolicyInputList`: `Sequence`\[`str`\]
- `ResourceArns`: `Sequence`\[`str`\]
- `ResourcePolicy`: `str`
- `ResourceOwner`: `str`
- `CallerArn`: `str`
- `ContextEntries`:
  `Sequence`\[[ContextEntryTypeDef](./type_defs.md#contextentrytypedef)\]
- `ResourceHandlingOption`: `str`
- `MaxItems`: `int`
- `Marker`: `str`

<a id="simulatepolicyresponsetypedef"></a>

## SimulatePolicyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import SimulatePolicyResponseTypeDef
```

Required fields:

- `EvaluationResults`:
  `List`\[[EvaluationResultTypeDef](./type_defs.md#evaluationresulttypedef)\]
- `IsTruncated`: `bool`
- `Marker`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="simulateprincipalpolicyrequestrequesttypedef"></a>

## SimulatePrincipalPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import SimulatePrincipalPolicyRequestRequestTypeDef
```

Required fields:

- `PolicySourceArn`: `str`
- `ActionNames`: `Sequence`\[`str`\]

Optional fields:

- `PolicyInputList`: `Sequence`\[`str`\]
- `PermissionsBoundaryPolicyInputList`: `Sequence`\[`str`\]
- `ResourceArns`: `Sequence`\[`str`\]
- `ResourcePolicy`: `str`
- `ResourceOwner`: `str`
- `CallerArn`: `str`
- `ContextEntries`:
  `Sequence`\[[ContextEntryTypeDef](./type_defs.md#contextentrytypedef)\]
- `ResourceHandlingOption`: `str`
- `MaxItems`: `int`
- `Marker`: `str`

<a id="statementtypedef"></a>

## StatementTypeDef

```python
from types_aiobotocore_iam.type_defs import StatementTypeDef
```

Optional fields:

- `SourcePolicyId`: `str`
- `SourcePolicyType`:
  [PolicySourceTypeType](./literals.md#policysourcetypetype)
- `StartPosition`: [PositionTypeDef](./type_defs.md#positiontypedef)
- `EndPosition`: [PositionTypeDef](./type_defs.md#positiontypedef)

<a id="taginstanceprofilerequestrequesttypedef"></a>

## TagInstanceProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagInstanceProfileRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagmfadevicerequestrequesttypedef"></a>

## TagMFADeviceRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagMFADeviceRequestRequestTypeDef
```

Required fields:

- `SerialNumber`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagopenidconnectproviderrequestrequesttypedef"></a>

## TagOpenIDConnectProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagOpenIDConnectProviderRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagpolicyrequestrequesttypedef"></a>

## TagPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagPolicyRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagrolerequestrequesttypedef"></a>

## TagRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagsamlproviderrequestrequesttypedef"></a>

## TagSAMLProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagSAMLProviderRequestRequestTypeDef
```

Required fields:

- `SAMLProviderArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagservercertificaterequestrequesttypedef"></a>

## TagServerCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagServerCertificateRequestRequestTypeDef
```

Required fields:

- `ServerCertificateName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_iam.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="taguserrequestrequesttypedef"></a>

## TagUserRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import TagUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="trackedactionlastaccessedtypedef"></a>

## TrackedActionLastAccessedTypeDef

```python
from types_aiobotocore_iam.type_defs import TrackedActionLastAccessedTypeDef
```

Optional fields:

- `ActionName`: `str`
- `LastAccessedEntity`: `str`
- `LastAccessedTime`: `datetime`
- `LastAccessedRegion`: `str`

<a id="untaginstanceprofilerequestrequesttypedef"></a>

## UntagInstanceProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagInstanceProfileRequestRequestTypeDef
```

Required fields:

- `InstanceProfileName`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="untagmfadevicerequestrequesttypedef"></a>

## UntagMFADeviceRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagMFADeviceRequestRequestTypeDef
```

Required fields:

- `SerialNumber`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="untagopenidconnectproviderrequestrequesttypedef"></a>

## UntagOpenIDConnectProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagOpenIDConnectProviderRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="untagpolicyrequestrequesttypedef"></a>

## UntagPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagPolicyRequestRequestTypeDef
```

Required fields:

- `PolicyArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="untagrolerequestrequesttypedef"></a>

## UntagRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="untagsamlproviderrequestrequesttypedef"></a>

## UntagSAMLProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagSAMLProviderRequestRequestTypeDef
```

Required fields:

- `SAMLProviderArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="untagservercertificaterequestrequesttypedef"></a>

## UntagServerCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagServerCertificateRequestRequestTypeDef
```

Required fields:

- `ServerCertificateName`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="untaguserrequestrequesttypedef"></a>

## UntagUserRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UntagUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updateaccesskeyrequestaccesskeypairtypedef"></a>

## UpdateAccessKeyRequestAccessKeyPairTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAccessKeyRequestAccessKeyPairTypeDef
```

Required fields:

- `Status`: [statusTypeType](./literals.md#statustypetype)

<a id="updateaccesskeyrequestaccesskeytypedef"></a>

## UpdateAccessKeyRequestAccessKeyTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAccessKeyRequestAccessKeyTypeDef
```

Required fields:

- `Status`: [statusTypeType](./literals.md#statustypetype)

<a id="updateaccesskeyrequestrequesttypedef"></a>

## UpdateAccessKeyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAccessKeyRequestRequestTypeDef
```

Required fields:

- `AccessKeyId`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)

Optional fields:

- `UserName`: `str`

<a id="updateaccountpasswordpolicyrequestaccountpasswordpolicytypedef"></a>

## UpdateAccountPasswordPolicyRequestAccountPasswordPolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAccountPasswordPolicyRequestAccountPasswordPolicyTypeDef
```

Optional fields:

- `MinimumPasswordLength`: `int`
- `RequireSymbols`: `bool`
- `RequireNumbers`: `bool`
- `RequireUppercaseCharacters`: `bool`
- `RequireLowercaseCharacters`: `bool`
- `AllowUsersToChangePassword`: `bool`
- `MaxPasswordAge`: `int`
- `PasswordReusePrevention`: `int`
- `HardExpiry`: `bool`

<a id="updateaccountpasswordpolicyrequestrequesttypedef"></a>

## UpdateAccountPasswordPolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAccountPasswordPolicyRequestRequestTypeDef
```

Optional fields:

- `MinimumPasswordLength`: `int`
- `RequireSymbols`: `bool`
- `RequireNumbers`: `bool`
- `RequireUppercaseCharacters`: `bool`
- `RequireLowercaseCharacters`: `bool`
- `AllowUsersToChangePassword`: `bool`
- `MaxPasswordAge`: `int`
- `PasswordReusePrevention`: `int`
- `HardExpiry`: `bool`

<a id="updateaccountpasswordpolicyrequestserviceresourcetypedef"></a>

## UpdateAccountPasswordPolicyRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAccountPasswordPolicyRequestServiceResourceTypeDef
```

Optional fields:

- `MinimumPasswordLength`: `int`
- `RequireSymbols`: `bool`
- `RequireNumbers`: `bool`
- `RequireUppercaseCharacters`: `bool`
- `RequireLowercaseCharacters`: `bool`
- `AllowUsersToChangePassword`: `bool`
- `MaxPasswordAge`: `int`
- `PasswordReusePrevention`: `int`
- `HardExpiry`: `bool`

<a id="updateassumerolepolicyrequestassumerolepolicytypedef"></a>

## UpdateAssumeRolePolicyRequestAssumeRolePolicyTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAssumeRolePolicyRequestAssumeRolePolicyTypeDef
```

Required fields:

- `PolicyDocument`: `str`

<a id="updateassumerolepolicyrequestrequesttypedef"></a>

## UpdateAssumeRolePolicyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateAssumeRolePolicyRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `PolicyDocument`: `str`

<a id="updategrouprequestgrouptypedef"></a>

## UpdateGroupRequestGroupTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateGroupRequestGroupTypeDef
```

Optional fields:

- `NewPath`: `str`
- `NewGroupName`: `str`

<a id="updategrouprequestrequesttypedef"></a>

## UpdateGroupRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateGroupRequestRequestTypeDef
```

Required fields:

- `GroupName`: `str`

Optional fields:

- `NewPath`: `str`
- `NewGroupName`: `str`

<a id="updateloginprofilerequestloginprofiletypedef"></a>

## UpdateLoginProfileRequestLoginProfileTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateLoginProfileRequestLoginProfileTypeDef
```

Optional fields:

- `Password`: `str`
- `PasswordResetRequired`: `bool`

<a id="updateloginprofilerequestrequesttypedef"></a>

## UpdateLoginProfileRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateLoginProfileRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `Password`: `str`
- `PasswordResetRequired`: `bool`

<a id="updateopenidconnectproviderthumbprintrequestrequesttypedef"></a>

## UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef
```

Required fields:

- `OpenIDConnectProviderArn`: `str`
- `ThumbprintList`: `Sequence`\[`str`\]

<a id="updateroledescriptionrequestrequesttypedef"></a>

## UpdateRoleDescriptionRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateRoleDescriptionRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`
- `Description`: `str`

<a id="updateroledescriptionresponsetypedef"></a>

## UpdateRoleDescriptionResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateRoleDescriptionResponseTypeDef
```

Required fields:

- `Role`: [RoleTypeDef](./type_defs.md#roletypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updaterolerequestrequesttypedef"></a>

## UpdateRoleRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateRoleRequestRequestTypeDef
```

Required fields:

- `RoleName`: `str`

Optional fields:

- `Description`: `str`
- `MaxSessionDuration`: `int`

<a id="updatesamlproviderrequestrequesttypedef"></a>

## UpdateSAMLProviderRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateSAMLProviderRequestRequestTypeDef
```

Required fields:

- `SAMLMetadataDocument`: `str`
- `SAMLProviderArn`: `str`

<a id="updatesamlproviderrequestsamlprovidertypedef"></a>

## UpdateSAMLProviderRequestSamlProviderTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateSAMLProviderRequestSamlProviderTypeDef
```

Required fields:

- `SAMLMetadataDocument`: `str`

<a id="updatesamlproviderresponsetypedef"></a>

## UpdateSAMLProviderResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateSAMLProviderResponseTypeDef
```

Required fields:

- `SAMLProviderArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatesshpublickeyrequestrequesttypedef"></a>

## UpdateSSHPublicKeyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateSSHPublicKeyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `SSHPublicKeyId`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)

<a id="updateservercertificaterequestrequesttypedef"></a>

## UpdateServerCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateServerCertificateRequestRequestTypeDef
```

Required fields:

- `ServerCertificateName`: `str`

Optional fields:

- `NewPath`: `str`
- `NewServerCertificateName`: `str`

<a id="updateservercertificaterequestservercertificatetypedef"></a>

## UpdateServerCertificateRequestServerCertificateTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateServerCertificateRequestServerCertificateTypeDef
```

Optional fields:

- `NewPath`: `str`
- `NewServerCertificateName`: `str`

<a id="updateservicespecificcredentialrequestrequesttypedef"></a>

## UpdateServiceSpecificCredentialRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateServiceSpecificCredentialRequestRequestTypeDef
```

Required fields:

- `ServiceSpecificCredentialId`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)

Optional fields:

- `UserName`: `str`

<a id="updatesigningcertificaterequestrequesttypedef"></a>

## UpdateSigningCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateSigningCertificateRequestRequestTypeDef
```

Required fields:

- `CertificateId`: `str`
- `Status`: [statusTypeType](./literals.md#statustypetype)

Optional fields:

- `UserName`: `str`

<a id="updatesigningcertificaterequestsigningcertificatetypedef"></a>

## UpdateSigningCertificateRequestSigningCertificateTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateSigningCertificateRequestSigningCertificateTypeDef
```

Required fields:

- `Status`: [statusTypeType](./literals.md#statustypetype)

<a id="updateuserrequestrequesttypedef"></a>

## UpdateUserRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`

Optional fields:

- `NewPath`: `str`
- `NewUserName`: `str`

<a id="updateuserrequestusertypedef"></a>

## UpdateUserRequestUserTypeDef

```python
from types_aiobotocore_iam.type_defs import UpdateUserRequestUserTypeDef
```

Optional fields:

- `NewPath`: `str`
- `NewUserName`: `str`

<a id="uploadsshpublickeyrequestrequesttypedef"></a>

## UploadSSHPublicKeyRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadSSHPublicKeyRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `SSHPublicKeyBody`: `str`

<a id="uploadsshpublickeyresponsetypedef"></a>

## UploadSSHPublicKeyResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadSSHPublicKeyResponseTypeDef
```

Required fields:

- `SSHPublicKey`: [SSHPublicKeyTypeDef](./type_defs.md#sshpublickeytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="uploadservercertificaterequestrequesttypedef"></a>

## UploadServerCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadServerCertificateRequestRequestTypeDef
```

Required fields:

- `ServerCertificateName`: `str`
- `CertificateBody`: `str`
- `PrivateKey`: `str`

Optional fields:

- `Path`: `str`
- `CertificateChain`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="uploadservercertificaterequestserviceresourcetypedef"></a>

## UploadServerCertificateRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadServerCertificateRequestServiceResourceTypeDef
```

Required fields:

- `ServerCertificateName`: `str`
- `CertificateBody`: `str`
- `PrivateKey`: `str`

Optional fields:

- `Path`: `str`
- `CertificateChain`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="uploadservercertificateresponsetypedef"></a>

## UploadServerCertificateResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadServerCertificateResponseTypeDef
```

Required fields:

- `ServerCertificateMetadata`:
  [ServerCertificateMetadataTypeDef](./type_defs.md#servercertificatemetadatatypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="uploadsigningcertificaterequestrequesttypedef"></a>

## UploadSigningCertificateRequestRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadSigningCertificateRequestRequestTypeDef
```

Required fields:

- `CertificateBody`: `str`

Optional fields:

- `UserName`: `str`

<a id="uploadsigningcertificaterequestserviceresourcetypedef"></a>

## UploadSigningCertificateRequestServiceResourceTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadSigningCertificateRequestServiceResourceTypeDef
```

Required fields:

- `CertificateBody`: `str`

Optional fields:

- `UserName`: `str`

<a id="uploadsigningcertificateresponsetypedef"></a>

## UploadSigningCertificateResponseTypeDef

```python
from types_aiobotocore_iam.type_defs import UploadSigningCertificateResponseTypeDef
```

Required fields:

- `Certificate`:
  [SigningCertificateTypeDef](./type_defs.md#signingcertificatetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="useraccesskeyrequesttypedef"></a>

## UserAccessKeyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UserAccessKeyRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="userdetailtypedef"></a>

## UserDetailTypeDef

```python
from types_aiobotocore_iam.type_defs import UserDetailTypeDef
```

Optional fields:

- `Path`: `str`
- `UserName`: `str`
- `UserId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`
- `UserPolicyList`:
  `List`\[[PolicyDetailTypeDef](./type_defs.md#policydetailtypedef)\]
- `GroupList`: `List`\[`str`\]
- `AttachedManagedPolicies`:
  `List`\[[AttachedPolicyTypeDef](./type_defs.md#attachedpolicytypedef)\]
- `PermissionsBoundary`:
  [AttachedPermissionsBoundaryTypeDef](./type_defs.md#attachedpermissionsboundarytypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="usermfadevicerequesttypedef"></a>

## UserMfaDeviceRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UserMfaDeviceRequestTypeDef
```

Required fields:

- `serial_number`: `str`

<a id="userpolicyrequesttypedef"></a>

## UserPolicyRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UserPolicyRequestTypeDef
```

Required fields:

- `name`: `str`

<a id="userresponsemetadatatypedef"></a>

## UserResponseMetadataTypeDef

```python
from types_aiobotocore_iam.type_defs import UserResponseMetadataTypeDef
```

Required fields:

- `Path`: `str`
- `UserName`: `str`
- `UserId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`
- `PasswordLastUsed`: `datetime`
- `PermissionsBoundary`:
  [AttachedPermissionsBoundaryTypeDef](./type_defs.md#attachedpermissionsboundarytypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="usersigningcertificaterequesttypedef"></a>

## UserSigningCertificateRequestTypeDef

```python
from types_aiobotocore_iam.type_defs import UserSigningCertificateRequestTypeDef
```

Required fields:

- `id`: `str`

<a id="usertypedef"></a>

## UserTypeDef

```python
from types_aiobotocore_iam.type_defs import UserTypeDef
```

Required fields:

- `Path`: `str`
- `UserName`: `str`
- `UserId`: `str`
- `Arn`: `str`
- `CreateDate`: `datetime`

Optional fields:

- `PasswordLastUsed`: `datetime`
- `PermissionsBoundary`:
  [AttachedPermissionsBoundaryTypeDef](./type_defs.md#attachedpermissionsboundarytypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="virtualmfadevicetypedef"></a>

## VirtualMFADeviceTypeDef

```python
from types_aiobotocore_iam.type_defs import VirtualMFADeviceTypeDef
```

Required fields:

- `SerialNumber`: `str`

Optional fields:

- `Base32StringSeed`: `bytes`
- `QRCodePNG`: `bytes`
- `User`: [UserTypeDef](./type_defs.md#usertypedef)
- `EnableDate`: `datetime`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_iam.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`
