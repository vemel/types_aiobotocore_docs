<a id="paginators-for-aiobotocore-ssoadmin-module"></a>

# Paginators for aiobotocore SSOAdmin module

> [Index](..) > [SSOAdmin](.) > Paginators

Auto-generated documentation for
[SSOAdmin](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin)
type annotations stubs module
[types-aiobotocore-sso-admin](https://pypi.org/project/types-aiobotocore-sso-admin/).

- [Paginators for aiobotocore SSOAdmin module](#paginators-for-aiobotocore-ssoadmin-module)
  - [ListAccountAssignmentCreationStatusPaginator](#listaccountassignmentcreationstatuspaginator)
  - [ListAccountAssignmentDeletionStatusPaginator](#listaccountassignmentdeletionstatuspaginator)
  - [ListAccountAssignmentsPaginator](#listaccountassignmentspaginator)
  - [ListAccountsForProvisionedPermissionSetPaginator](#listaccountsforprovisionedpermissionsetpaginator)
  - [ListInstancesPaginator](#listinstancespaginator)
  - [ListManagedPoliciesInPermissionSetPaginator](#listmanagedpoliciesinpermissionsetpaginator)
  - [ListPermissionSetProvisioningStatusPaginator](#listpermissionsetprovisioningstatuspaginator)
  - [ListPermissionSetsPaginator](#listpermissionsetspaginator)
  - [ListPermissionSetsProvisionedToAccountPaginator](#listpermissionsetsprovisionedtoaccountpaginator)
  - [ListTagsForResourcePaginator](#listtagsforresourcepaginator)

<a id="listaccountassignmentcreationstatuspaginator"></a>

## ListAccountAssignmentCreationStatusPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_account_assignment_creation_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListAccountAssignmentCreationStatusPaginator

def get_list_account_assignment_creation_status_paginator() -> ListAccountAssignmentCreationStatusPaginator:
    return Session().create_client("sso-admin").get_paginator("list_account_assignment_creation_status")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListAccountAssignmentCreationStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignmentCreationStatus)

Arguments for `ListAccountAssignmentCreationStatusPaginator.paginate` method:

- `InstanceArn`: `str` *(required)*
- `Filter`:
  [OperationStatusFilterTypeDef](./type_defs.md#operationstatusfiltertypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAccountAssignmentCreationStatusPaginator.paginate` returns
`_PageIterator`\[[ListAccountAssignmentCreationStatusResponseTypeDef](./type_defs.md#listaccountassignmentcreationstatusresponsetypedef)\].

<a id="listaccountassignmentdeletionstatuspaginator"></a>

## ListAccountAssignmentDeletionStatusPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_account_assignment_deletion_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListAccountAssignmentDeletionStatusPaginator

def get_list_account_assignment_deletion_status_paginator() -> ListAccountAssignmentDeletionStatusPaginator:
    return Session().create_client("sso-admin").get_paginator("list_account_assignment_deletion_status")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListAccountAssignmentDeletionStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignmentDeletionStatus)

Arguments for `ListAccountAssignmentDeletionStatusPaginator.paginate` method:

- `InstanceArn`: `str` *(required)*
- `Filter`:
  [OperationStatusFilterTypeDef](./type_defs.md#operationstatusfiltertypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAccountAssignmentDeletionStatusPaginator.paginate` returns
`_PageIterator`\[[ListAccountAssignmentDeletionStatusResponseTypeDef](./type_defs.md#listaccountassignmentdeletionstatusresponsetypedef)\].

<a id="listaccountassignmentspaginator"></a>

## ListAccountAssignmentsPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_account_assignments")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListAccountAssignmentsPaginator

def get_list_account_assignments_paginator() -> ListAccountAssignmentsPaginator:
    return Session().create_client("sso-admin").get_paginator("list_account_assignments")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListAccountAssignments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignments)

Arguments for `ListAccountAssignmentsPaginator.paginate` method:

- `InstanceArn`: `str` *(required)*
- `AccountId`: `str` *(required)*
- `PermissionSetArn`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAccountAssignmentsPaginator.paginate` returns
`_PageIterator`\[[ListAccountAssignmentsResponseTypeDef](./type_defs.md#listaccountassignmentsresponsetypedef)\].

<a id="listaccountsforprovisionedpermissionsetpaginator"></a>

## ListAccountsForProvisionedPermissionSetPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_accounts_for_provisioned_permission_set")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListAccountsForProvisionedPermissionSetPaginator

def get_list_accounts_for_provisioned_permission_set_paginator() -> ListAccountsForProvisionedPermissionSetPaginator:
    return Session().create_client("sso-admin").get_paginator("list_accounts_for_provisioned_permission_set")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListAccountsForProvisionedPermissionSet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountsForProvisionedPermissionSet)

Arguments for `ListAccountsForProvisionedPermissionSetPaginator.paginate`
method:

- `InstanceArn`: `str` *(required)*
- `PermissionSetArn`: `str` *(required)*
- `ProvisioningStatus`:
  [ProvisioningStatusType](./literals.md#provisioningstatustype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAccountsForProvisionedPermissionSetPaginator.paginate` returns
`_PageIterator`\[[ListAccountsForProvisionedPermissionSetResponseTypeDef](./type_defs.md#listaccountsforprovisionedpermissionsetresponsetypedef)\].

<a id="listinstancespaginator"></a>

## ListInstancesPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_instances")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListInstancesPaginator

def get_list_instances_paginator() -> ListInstancesPaginator:
    return Session().create_client("sso-admin").get_paginator("list_instances")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListInstances)

Arguments for `ListInstancesPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListInstancesPaginator.paginate` returns
`_PageIterator`\[[ListInstancesResponseTypeDef](./type_defs.md#listinstancesresponsetypedef)\].

<a id="listmanagedpoliciesinpermissionsetpaginator"></a>

## ListManagedPoliciesInPermissionSetPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_managed_policies_in_permission_set")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListManagedPoliciesInPermissionSetPaginator

def get_list_managed_policies_in_permission_set_paginator() -> ListManagedPoliciesInPermissionSetPaginator:
    return Session().create_client("sso-admin").get_paginator("list_managed_policies_in_permission_set")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListManagedPoliciesInPermissionSet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListManagedPoliciesInPermissionSet)

Arguments for `ListManagedPoliciesInPermissionSetPaginator.paginate` method:

- `InstanceArn`: `str` *(required)*
- `PermissionSetArn`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListManagedPoliciesInPermissionSetPaginator.paginate` returns
`_PageIterator`\[[ListManagedPoliciesInPermissionSetResponseTypeDef](./type_defs.md#listmanagedpoliciesinpermissionsetresponsetypedef)\].

<a id="listpermissionsetprovisioningstatuspaginator"></a>

## ListPermissionSetProvisioningStatusPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_permission_set_provisioning_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListPermissionSetProvisioningStatusPaginator

def get_list_permission_set_provisioning_status_paginator() -> ListPermissionSetProvisioningStatusPaginator:
    return Session().create_client("sso-admin").get_paginator("list_permission_set_provisioning_status")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListPermissionSetProvisioningStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSetProvisioningStatus)

Arguments for `ListPermissionSetProvisioningStatusPaginator.paginate` method:

- `InstanceArn`: `str` *(required)*
- `Filter`:
  [OperationStatusFilterTypeDef](./type_defs.md#operationstatusfiltertypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPermissionSetProvisioningStatusPaginator.paginate` returns
`_PageIterator`\[[ListPermissionSetProvisioningStatusResponseTypeDef](./type_defs.md#listpermissionsetprovisioningstatusresponsetypedef)\].

<a id="listpermissionsetspaginator"></a>

## ListPermissionSetsPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_permission_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListPermissionSetsPaginator

def get_list_permission_sets_paginator() -> ListPermissionSetsPaginator:
    return Session().create_client("sso-admin").get_paginator("list_permission_sets")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListPermissionSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSets)

Arguments for `ListPermissionSetsPaginator.paginate` method:

- `InstanceArn`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPermissionSetsPaginator.paginate` returns
`_PageIterator`\[[ListPermissionSetsResponseTypeDef](./type_defs.md#listpermissionsetsresponsetypedef)\].

<a id="listpermissionsetsprovisionedtoaccountpaginator"></a>

## ListPermissionSetsProvisionedToAccountPaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_permission_sets_provisioned_to_account")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListPermissionSetsProvisionedToAccountPaginator

def get_list_permission_sets_provisioned_to_account_paginator() -> ListPermissionSetsProvisionedToAccountPaginator:
    return Session().create_client("sso-admin").get_paginator("list_permission_sets_provisioned_to_account")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListPermissionSetsProvisionedToAccount](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSetsProvisionedToAccount)

Arguments for `ListPermissionSetsProvisionedToAccountPaginator.paginate`
method:

- `InstanceArn`: `str` *(required)*
- `AccountId`: `str` *(required)*
- `ProvisioningStatus`:
  [ProvisioningStatusType](./literals.md#provisioningstatustype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPermissionSetsProvisionedToAccountPaginator.paginate` returns
`_PageIterator`\[[ListPermissionSetsProvisionedToAccountResponseTypeDef](./type_defs.md#listpermissionsetsprovisionedtoaccountresponsetypedef)\].

<a id="listtagsforresourcepaginator"></a>

## ListTagsForResourcePaginator

Type annotations for
`aiobotocore.create_client("sso-admin").get_paginator("list_tags_for_resource")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_sso_admin.paginator import ListTagsForResourcePaginator

def get_list_tags_for_resource_paginator() -> ListTagsForResourcePaginator:
    return Session().create_client("sso-admin").get_paginator("list_tags_for_resource")
```

Boto3 documentation:
[SSOAdmin.Paginator.ListTagsForResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListTagsForResource)

Arguments for `ListTagsForResourcePaginator.paginate` method:

- `InstanceArn`: `str` *(required)*
- `ResourceArn`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTagsForResourcePaginator.paginate` returns
`_PageIterator`\[[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)\].
