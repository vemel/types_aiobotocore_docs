<a id="paginators-for-aiobotocore-organizations-module"></a>

# Paginators for aiobotocore Organizations module

> [Index](..) > [Organizations](.) > Paginators

Auto-generated documentation for
[Organizations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
type annotations stubs module
[types-aiobotocore-organizations](https://pypi.org/project/types-aiobotocore-organizations/).

- [Paginators for aiobotocore Organizations module](#paginators-for-aiobotocore-organizations-module)
  - [ListAWSServiceAccessForOrganizationPaginator](#listawsserviceaccessfororganizationpaginator)
  - [ListAccountsPaginator](#listaccountspaginator)
  - [ListAccountsForParentPaginator](#listaccountsforparentpaginator)
  - [ListChildrenPaginator](#listchildrenpaginator)
  - [ListCreateAccountStatusPaginator](#listcreateaccountstatuspaginator)
  - [ListDelegatedAdministratorsPaginator](#listdelegatedadministratorspaginator)
  - [ListDelegatedServicesForAccountPaginator](#listdelegatedservicesforaccountpaginator)
  - [ListHandshakesForAccountPaginator](#listhandshakesforaccountpaginator)
  - [ListHandshakesForOrganizationPaginator](#listhandshakesfororganizationpaginator)
  - [ListOrganizationalUnitsForParentPaginator](#listorganizationalunitsforparentpaginator)
  - [ListParentsPaginator](#listparentspaginator)
  - [ListPoliciesPaginator](#listpoliciespaginator)
  - [ListPoliciesForTargetPaginator](#listpoliciesfortargetpaginator)
  - [ListRootsPaginator](#listrootspaginator)
  - [ListTagsForResourcePaginator](#listtagsforresourcepaginator)
  - [ListTargetsForPolicyPaginator](#listtargetsforpolicypaginator)

<a id="listawsserviceaccessfororganizationpaginator"></a>

## ListAWSServiceAccessForOrganizationPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_aws_service_access_for_organization")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListAWSServiceAccessForOrganizationPaginator

def get_list_aws_service_access_for_organization_paginator() -> ListAWSServiceAccessForOrganizationPaginator:
    return Session().create_client("organizations").get_paginator("list_aws_service_access_for_organization")
```

Boto3 documentation:
[Organizations.Paginator.ListAWSServiceAccessForOrganization](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAWSServiceAccessForOrganization)

Arguments for `ListAWSServiceAccessForOrganizationPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAWSServiceAccessForOrganizationPaginator.paginate` returns
`_PageIterator`\[[ListAWSServiceAccessForOrganizationResponseTypeDef](./type_defs.md#listawsserviceaccessfororganizationresponsetypedef)\].

<a id="listaccountspaginator"></a>

## ListAccountsPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_accounts")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListAccountsPaginator

def get_list_accounts_paginator() -> ListAccountsPaginator:
    return Session().create_client("organizations").get_paginator("list_accounts")
```

Boto3 documentation:
[Organizations.Paginator.ListAccounts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccounts)

Arguments for `ListAccountsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAccountsPaginator.paginate` returns
`_PageIterator`\[[ListAccountsResponseTypeDef](./type_defs.md#listaccountsresponsetypedef)\].

<a id="listaccountsforparentpaginator"></a>

## ListAccountsForParentPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_accounts_for_parent")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListAccountsForParentPaginator

def get_list_accounts_for_parent_paginator() -> ListAccountsForParentPaginator:
    return Session().create_client("organizations").get_paginator("list_accounts_for_parent")
```

Boto3 documentation:
[Organizations.Paginator.ListAccountsForParent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccountsForParent)

Arguments for `ListAccountsForParentPaginator.paginate` method:

- `ParentId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAccountsForParentPaginator.paginate` returns
`_PageIterator`\[[ListAccountsForParentResponseTypeDef](./type_defs.md#listaccountsforparentresponsetypedef)\].

<a id="listchildrenpaginator"></a>

## ListChildrenPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_children")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListChildrenPaginator

def get_list_children_paginator() -> ListChildrenPaginator:
    return Session().create_client("organizations").get_paginator("list_children")
```

Boto3 documentation:
[Organizations.Paginator.ListChildren](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListChildren)

Arguments for `ListChildrenPaginator.paginate` method:

- `ParentId`: `str` *(required)*
- `ChildType`: [ChildTypeType](./literals.md#childtypetype) *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListChildrenPaginator.paginate` returns
`_PageIterator`\[[ListChildrenResponseTypeDef](./type_defs.md#listchildrenresponsetypedef)\].

<a id="listcreateaccountstatuspaginator"></a>

## ListCreateAccountStatusPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_create_account_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListCreateAccountStatusPaginator

def get_list_create_account_status_paginator() -> ListCreateAccountStatusPaginator:
    return Session().create_client("organizations").get_paginator("list_create_account_status")
```

Boto3 documentation:
[Organizations.Paginator.ListCreateAccountStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListCreateAccountStatus)

Arguments for `ListCreateAccountStatusPaginator.paginate` method:

- `States`:
  `Sequence`\[[CreateAccountStateType](./literals.md#createaccountstatetype)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListCreateAccountStatusPaginator.paginate` returns
`_PageIterator`\[[ListCreateAccountStatusResponseTypeDef](./type_defs.md#listcreateaccountstatusresponsetypedef)\].

<a id="listdelegatedadministratorspaginator"></a>

## ListDelegatedAdministratorsPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_delegated_administrators")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListDelegatedAdministratorsPaginator

def get_list_delegated_administrators_paginator() -> ListDelegatedAdministratorsPaginator:
    return Session().create_client("organizations").get_paginator("list_delegated_administrators")
```

Boto3 documentation:
[Organizations.Paginator.ListDelegatedAdministrators](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedAdministrators)

Arguments for `ListDelegatedAdministratorsPaginator.paginate` method:

- `ServicePrincipal`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDelegatedAdministratorsPaginator.paginate` returns
`_PageIterator`\[[ListDelegatedAdministratorsResponseTypeDef](./type_defs.md#listdelegatedadministratorsresponsetypedef)\].

<a id="listdelegatedservicesforaccountpaginator"></a>

## ListDelegatedServicesForAccountPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_delegated_services_for_account")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListDelegatedServicesForAccountPaginator

def get_list_delegated_services_for_account_paginator() -> ListDelegatedServicesForAccountPaginator:
    return Session().create_client("organizations").get_paginator("list_delegated_services_for_account")
```

Boto3 documentation:
[Organizations.Paginator.ListDelegatedServicesForAccount](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedServicesForAccount)

Arguments for `ListDelegatedServicesForAccountPaginator.paginate` method:

- `AccountId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDelegatedServicesForAccountPaginator.paginate` returns
`_PageIterator`\[[ListDelegatedServicesForAccountResponseTypeDef](./type_defs.md#listdelegatedservicesforaccountresponsetypedef)\].

<a id="listhandshakesforaccountpaginator"></a>

## ListHandshakesForAccountPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_handshakes_for_account")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListHandshakesForAccountPaginator

def get_list_handshakes_for_account_paginator() -> ListHandshakesForAccountPaginator:
    return Session().create_client("organizations").get_paginator("list_handshakes_for_account")
```

Boto3 documentation:
[Organizations.Paginator.ListHandshakesForAccount](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListHandshakesForAccount)

Arguments for `ListHandshakesForAccountPaginator.paginate` method:

- `Filter`: [HandshakeFilterTypeDef](./type_defs.md#handshakefiltertypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListHandshakesForAccountPaginator.paginate` returns
`_PageIterator`\[[ListHandshakesForAccountResponseTypeDef](./type_defs.md#listhandshakesforaccountresponsetypedef)\].

<a id="listhandshakesfororganizationpaginator"></a>

## ListHandshakesForOrganizationPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_handshakes_for_organization")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListHandshakesForOrganizationPaginator

def get_list_handshakes_for_organization_paginator() -> ListHandshakesForOrganizationPaginator:
    return Session().create_client("organizations").get_paginator("list_handshakes_for_organization")
```

Boto3 documentation:
[Organizations.Paginator.ListHandshakesForOrganization](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListHandshakesForOrganization)

Arguments for `ListHandshakesForOrganizationPaginator.paginate` method:

- `Filter`: [HandshakeFilterTypeDef](./type_defs.md#handshakefiltertypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListHandshakesForOrganizationPaginator.paginate` returns
`_PageIterator`\[[ListHandshakesForOrganizationResponseTypeDef](./type_defs.md#listhandshakesfororganizationresponsetypedef)\].

<a id="listorganizationalunitsforparentpaginator"></a>

## ListOrganizationalUnitsForParentPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_organizational_units_for_parent")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListOrganizationalUnitsForParentPaginator

def get_list_organizational_units_for_parent_paginator() -> ListOrganizationalUnitsForParentPaginator:
    return Session().create_client("organizations").get_paginator("list_organizational_units_for_parent")
```

Boto3 documentation:
[Organizations.Paginator.ListOrganizationalUnitsForParent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListOrganizationalUnitsForParent)

Arguments for `ListOrganizationalUnitsForParentPaginator.paginate` method:

- `ParentId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListOrganizationalUnitsForParentPaginator.paginate` returns
`_PageIterator`\[[ListOrganizationalUnitsForParentResponseTypeDef](./type_defs.md#listorganizationalunitsforparentresponsetypedef)\].

<a id="listparentspaginator"></a>

## ListParentsPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_parents")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListParentsPaginator

def get_list_parents_paginator() -> ListParentsPaginator:
    return Session().create_client("organizations").get_paginator("list_parents")
```

Boto3 documentation:
[Organizations.Paginator.ListParents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListParents)

Arguments for `ListParentsPaginator.paginate` method:

- `ChildId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListParentsPaginator.paginate` returns
`_PageIterator`\[[ListParentsResponseTypeDef](./type_defs.md#listparentsresponsetypedef)\].

<a id="listpoliciespaginator"></a>

## ListPoliciesPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_policies")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListPoliciesPaginator

def get_list_policies_paginator() -> ListPoliciesPaginator:
    return Session().create_client("organizations").get_paginator("list_policies")
```

Boto3 documentation:
[Organizations.Paginator.ListPolicies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPolicies)

Arguments for `ListPoliciesPaginator.paginate` method:

- `Filter`: [PolicyTypeType](./literals.md#policytypetype) *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPoliciesPaginator.paginate` returns
`_PageIterator`\[[ListPoliciesResponseTypeDef](./type_defs.md#listpoliciesresponsetypedef)\].

<a id="listpoliciesfortargetpaginator"></a>

## ListPoliciesForTargetPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_policies_for_target")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListPoliciesForTargetPaginator

def get_list_policies_for_target_paginator() -> ListPoliciesForTargetPaginator:
    return Session().create_client("organizations").get_paginator("list_policies_for_target")
```

Boto3 documentation:
[Organizations.Paginator.ListPoliciesForTarget](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPoliciesForTarget)

Arguments for `ListPoliciesForTargetPaginator.paginate` method:

- `TargetId`: `str` *(required)*
- `Filter`: [PolicyTypeType](./literals.md#policytypetype) *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPoliciesForTargetPaginator.paginate` returns
`_PageIterator`\[[ListPoliciesForTargetResponseTypeDef](./type_defs.md#listpoliciesfortargetresponsetypedef)\].

<a id="listrootspaginator"></a>

## ListRootsPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_roots")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListRootsPaginator

def get_list_roots_paginator() -> ListRootsPaginator:
    return Session().create_client("organizations").get_paginator("list_roots")
```

Boto3 documentation:
[Organizations.Paginator.ListRoots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListRoots)

Arguments for `ListRootsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRootsPaginator.paginate` returns
`_PageIterator`\[[ListRootsResponseTypeDef](./type_defs.md#listrootsresponsetypedef)\].

<a id="listtagsforresourcepaginator"></a>

## ListTagsForResourcePaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_tags_for_resource")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListTagsForResourcePaginator

def get_list_tags_for_resource_paginator() -> ListTagsForResourcePaginator:
    return Session().create_client("organizations").get_paginator("list_tags_for_resource")
```

Boto3 documentation:
[Organizations.Paginator.ListTagsForResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTagsForResource)

Arguments for `ListTagsForResourcePaginator.paginate` method:

- `ResourceId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTagsForResourcePaginator.paginate` returns
`_PageIterator`\[[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)\].

<a id="listtargetsforpolicypaginator"></a>

## ListTargetsForPolicyPaginator

Type annotations for
`aiobotocore.create_client("organizations").get_paginator("list_targets_for_policy")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_organizations.paginator import ListTargetsForPolicyPaginator

def get_list_targets_for_policy_paginator() -> ListTargetsForPolicyPaginator:
    return Session().create_client("organizations").get_paginator("list_targets_for_policy")
```

Boto3 documentation:
[Organizations.Paginator.ListTargetsForPolicy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTargetsForPolicy)

Arguments for `ListTargetsForPolicyPaginator.paginate` method:

- `PolicyId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTargetsForPolicyPaginator.paginate` returns
`_PageIterator`\[[ListTargetsForPolicyResponseTypeDef](./type_defs.md#listtargetsforpolicyresponsetypedef)\].
