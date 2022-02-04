<a id="type-annotations-for-aiobotocore-cognitoidentity-module"></a>

# Type annotations for aiobotocore CognitoIdentity module

> [Index](..) > CognitoIdentity

Auto-generated documentation for
[CognitoIdentity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity)
type annotations stubs module
[types-aiobotocore-cognito-identity](https://pypi.org/project/types-aiobotocore-cognito-identity/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[cognito-identity]'

# install as a standalone
pip install types-aiobotocore-cognito-identity
```

- [Type annotations for aiobotocore CognitoIdentity module](#type-annotations-for-aiobotocore-cognitoidentity-module)
  - [CognitoIdentityClient](#cognitoidentityclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="cognitoidentityclient"></a>

## CognitoIdentityClient

Type annotations for `aiobotocore.create_client("cognito-identity")` as
[CognitoIdentityClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_cognito_identity.client import CognitoIdentityClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_identity_pool](./client.md#create_identity_pool)
- [delete_identities](./client.md#delete_identities)
- [delete_identity_pool](./client.md#delete_identity_pool)
- [describe_identity](./client.md#describe_identity)
- [describe_identity_pool](./client.md#describe_identity_pool)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_credentials_for_identity](./client.md#get_credentials_for_identity)
- [get_id](./client.md#get_id)
- [get_identity_pool_roles](./client.md#get_identity_pool_roles)
- [get_open_id_token](./client.md#get_open_id_token)
- [get_open_id_token_for_developer_identity](./client.md#get_open_id_token_for_developer_identity)
- [get_paginator](./client.md#get_paginator)
- [get_principal_tag_attribute_map](./client.md#get_principal_tag_attribute_map)
- [list_identities](./client.md#list_identities)
- [list_identity_pools](./client.md#list_identity_pools)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [lookup_developer_identity](./client.md#lookup_developer_identity)
- [merge_developer_identities](./client.md#merge_developer_identities)
- [set_identity_pool_roles](./client.md#set_identity_pool_roles)
- [set_principal_tag_attribute_map](./client.md#set_principal_tag_attribute_map)
- [tag_resource](./client.md#tag_resource)
- [unlink_developer_identity](./client.md#unlink_developer_identity)
- [unlink_identity](./client.md#unlink_identity)
- [untag_resource](./client.md#untag_resource)
- [update_identity_pool](./client.md#update_identity_pool)

<a id="exceptions"></a>

### Exceptions

CognitoIdentityClient [exceptions](./client.md#exceptions)

- ClientError
- ConcurrentModificationException
- DeveloperUserAlreadyRegisteredException
- ExternalServiceException
- InternalErrorException
- InvalidIdentityPoolConfigurationException
- InvalidParameterException
- LimitExceededException
- NotAuthorizedException
- ResourceConflictException
- ResourceNotFoundException
- TooManyRequestsException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("cognito-identity").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_cognito_identity.paginators import ListIdentityPoolsPaginator, ...
```

- [ListIdentityPoolsPaginator](./paginators.md#listidentitypoolspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_cognito_identity.literals import AmbiguousRoleResolutionTypeType, ...
```

- [AmbiguousRoleResolutionTypeType](./literals.md#ambiguousroleresolutiontypetype)
- [ErrorCodeType](./literals.md#errorcodetype)
- [ListIdentityPoolsPaginatorName](./literals.md#listidentitypoolspaginatorname)
- [MappingRuleMatchTypeType](./literals.md#mappingrulematchtypetype)
- [RoleMappingTypeType](./literals.md#rolemappingtypetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_cognito_identity.type_defs import CognitoIdentityProviderTypeDef, ...
```

- [CognitoIdentityProviderTypeDef](./type_defs.md#cognitoidentityprovidertypedef)
- [CreateIdentityPoolInputRequestTypeDef](./type_defs.md#createidentitypoolinputrequesttypedef)
- [CredentialsTypeDef](./type_defs.md#credentialstypedef)
- [DeleteIdentitiesInputRequestTypeDef](./type_defs.md#deleteidentitiesinputrequesttypedef)
- [DeleteIdentitiesResponseTypeDef](./type_defs.md#deleteidentitiesresponsetypedef)
- [DeleteIdentityPoolInputRequestTypeDef](./type_defs.md#deleteidentitypoolinputrequesttypedef)
- [DescribeIdentityInputRequestTypeDef](./type_defs.md#describeidentityinputrequesttypedef)
- [DescribeIdentityPoolInputRequestTypeDef](./type_defs.md#describeidentitypoolinputrequesttypedef)
- [GetCredentialsForIdentityInputRequestTypeDef](./type_defs.md#getcredentialsforidentityinputrequesttypedef)
- [GetCredentialsForIdentityResponseTypeDef](./type_defs.md#getcredentialsforidentityresponsetypedef)
- [GetIdInputRequestTypeDef](./type_defs.md#getidinputrequesttypedef)
- [GetIdResponseTypeDef](./type_defs.md#getidresponsetypedef)
- [GetIdentityPoolRolesInputRequestTypeDef](./type_defs.md#getidentitypoolrolesinputrequesttypedef)
- [GetIdentityPoolRolesResponseTypeDef](./type_defs.md#getidentitypoolrolesresponsetypedef)
- [GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef](./type_defs.md#getopenidtokenfordeveloperidentityinputrequesttypedef)
- [GetOpenIdTokenForDeveloperIdentityResponseTypeDef](./type_defs.md#getopenidtokenfordeveloperidentityresponsetypedef)
- [GetOpenIdTokenInputRequestTypeDef](./type_defs.md#getopenidtokeninputrequesttypedef)
- [GetOpenIdTokenResponseTypeDef](./type_defs.md#getopenidtokenresponsetypedef)
- [GetPrincipalTagAttributeMapInputRequestTypeDef](./type_defs.md#getprincipaltagattributemapinputrequesttypedef)
- [GetPrincipalTagAttributeMapResponseTypeDef](./type_defs.md#getprincipaltagattributemapresponsetypedef)
- [IdentityDescriptionResponseMetadataTypeDef](./type_defs.md#identitydescriptionresponsemetadatatypedef)
- [IdentityDescriptionTypeDef](./type_defs.md#identitydescriptiontypedef)
- [IdentityPoolRequestTypeDef](./type_defs.md#identitypoolrequesttypedef)
- [IdentityPoolShortDescriptionTypeDef](./type_defs.md#identitypoolshortdescriptiontypedef)
- [IdentityPoolTypeDef](./type_defs.md#identitypooltypedef)
- [ListIdentitiesInputRequestTypeDef](./type_defs.md#listidentitiesinputrequesttypedef)
- [ListIdentitiesResponseTypeDef](./type_defs.md#listidentitiesresponsetypedef)
- [ListIdentityPoolsInputRequestTypeDef](./type_defs.md#listidentitypoolsinputrequesttypedef)
- [ListIdentityPoolsResponseTypeDef](./type_defs.md#listidentitypoolsresponsetypedef)
- [ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [LookupDeveloperIdentityInputRequestTypeDef](./type_defs.md#lookupdeveloperidentityinputrequesttypedef)
- [LookupDeveloperIdentityResponseTypeDef](./type_defs.md#lookupdeveloperidentityresponsetypedef)
- [MappingRuleTypeDef](./type_defs.md#mappingruletypedef)
- [MergeDeveloperIdentitiesInputRequestTypeDef](./type_defs.md#mergedeveloperidentitiesinputrequesttypedef)
- [MergeDeveloperIdentitiesResponseTypeDef](./type_defs.md#mergedeveloperidentitiesresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RoleMappingTypeDef](./type_defs.md#rolemappingtypedef)
- [RulesConfigurationTypeTypeDef](./type_defs.md#rulesconfigurationtypetypedef)
- [SetIdentityPoolRolesInputRequestTypeDef](./type_defs.md#setidentitypoolrolesinputrequesttypedef)
- [SetPrincipalTagAttributeMapInputRequestTypeDef](./type_defs.md#setprincipaltagattributemapinputrequesttypedef)
- [SetPrincipalTagAttributeMapResponseTypeDef](./type_defs.md#setprincipaltagattributemapresponsetypedef)
- [TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef)
- [UnlinkDeveloperIdentityInputRequestTypeDef](./type_defs.md#unlinkdeveloperidentityinputrequesttypedef)
- [UnlinkIdentityInputRequestTypeDef](./type_defs.md#unlinkidentityinputrequesttypedef)
- [UnprocessedIdentityIdTypeDef](./type_defs.md#unprocessedidentityidtypedef)
- [UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef)
