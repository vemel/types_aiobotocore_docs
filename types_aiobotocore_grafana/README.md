<a id="type-annotations-for-aiobotocore-managedgrafana-module"></a>

# Type annotations for aiobotocore ManagedGrafana module

> [Index](..) > ManagedGrafana

Auto-generated documentation for
[ManagedGrafana](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
type annotations stubs module
[types-aiobotocore-grafana](https://pypi.org/project/types-aiobotocore-grafana/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[grafana]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[grafana]'

# standalone installation
pip install types-aiobotocore-grafana
```

- [Type annotations for aiobotocore ManagedGrafana module](#type-annotations-for-aiobotocore-managedgrafana-module)
  - [ManagedGrafanaClient](#managedgrafanaclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="managedgrafanaclient"></a>

## ManagedGrafanaClient

Type annotations for `session.create_client("grafana")` as
[ManagedGrafanaClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_grafana.client import ManagedGrafanaClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [associate_license](./client.md#associate_license)
- [can_paginate](./client.md#can_paginate)
- [create_workspace](./client.md#create_workspace)
- [delete_workspace](./client.md#delete_workspace)
- [describe_workspace](./client.md#describe_workspace)
- [describe_workspace_authentication](./client.md#describe_workspace_authentication)
- [disassociate_license](./client.md#disassociate_license)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [list_permissions](./client.md#list_permissions)
- [list_workspaces](./client.md#list_workspaces)
- [update_permissions](./client.md#update_permissions)
- [update_workspace](./client.md#update_workspace)
- [update_workspace_authentication](./client.md#update_workspace_authentication)

<a id="exceptions"></a>

### Exceptions

ManagedGrafanaClient [exceptions](./client.md#exceptions)

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
`boto3.client("grafana").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_grafana.paginator import ListPermissionsPaginator, ...
```

- [ListPermissionsPaginator](./paginators.md#listpermissionspaginator)
- [ListWorkspacesPaginator](./paginators.md#listworkspacespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_grafana.literals import AccountAccessTypeType, ...
```

- [AccountAccessTypeType](./literals.md#accountaccesstypetype)
- [AuthenticationProviderTypesType](./literals.md#authenticationprovidertypestype)
- [DataSourceTypeType](./literals.md#datasourcetypetype)
- [LicenseTypeType](./literals.md#licensetypetype)
- [ListPermissionsPaginatorName](./literals.md#listpermissionspaginatorname)
- [ListWorkspacesPaginatorName](./literals.md#listworkspacespaginatorname)
- [NotificationDestinationTypeType](./literals.md#notificationdestinationtypetype)
- [PermissionTypeType](./literals.md#permissiontypetype)
- [RoleType](./literals.md#roletype)
- [SamlConfigurationStatusType](./literals.md#samlconfigurationstatustype)
- [UpdateActionType](./literals.md#updateactiontype)
- [UserTypeType](./literals.md#usertypetype)
- [WorkspaceStatusType](./literals.md#workspacestatustype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_grafana.type_defs import AssertionAttributesTypeDef, ...
```

- [AssertionAttributesTypeDef](./type_defs.md#assertionattributestypedef)
- [AssociateLicenseRequestRequestTypeDef](./type_defs.md#associatelicenserequestrequesttypedef)
- [AssociateLicenseResponseTypeDef](./type_defs.md#associatelicenseresponsetypedef)
- [AuthenticationDescriptionTypeDef](./type_defs.md#authenticationdescriptiontypedef)
- [AuthenticationSummaryTypeDef](./type_defs.md#authenticationsummarytypedef)
- [AwsSsoAuthenticationTypeDef](./type_defs.md#awsssoauthenticationtypedef)
- [CreateWorkspaceRequestRequestTypeDef](./type_defs.md#createworkspacerequestrequesttypedef)
- [CreateWorkspaceResponseTypeDef](./type_defs.md#createworkspaceresponsetypedef)
- [DeleteWorkspaceRequestRequestTypeDef](./type_defs.md#deleteworkspacerequestrequesttypedef)
- [DeleteWorkspaceResponseTypeDef](./type_defs.md#deleteworkspaceresponsetypedef)
- [DescribeWorkspaceAuthenticationRequestRequestTypeDef](./type_defs.md#describeworkspaceauthenticationrequestrequesttypedef)
- [DescribeWorkspaceAuthenticationResponseTypeDef](./type_defs.md#describeworkspaceauthenticationresponsetypedef)
- [DescribeWorkspaceRequestRequestTypeDef](./type_defs.md#describeworkspacerequestrequesttypedef)
- [DescribeWorkspaceResponseTypeDef](./type_defs.md#describeworkspaceresponsetypedef)
- [DisassociateLicenseRequestRequestTypeDef](./type_defs.md#disassociatelicenserequestrequesttypedef)
- [DisassociateLicenseResponseTypeDef](./type_defs.md#disassociatelicenseresponsetypedef)
- [IdpMetadataTypeDef](./type_defs.md#idpmetadatatypedef)
- [ListPermissionsRequestRequestTypeDef](./type_defs.md#listpermissionsrequestrequesttypedef)
- [ListPermissionsResponseTypeDef](./type_defs.md#listpermissionsresponsetypedef)
- [ListWorkspacesRequestRequestTypeDef](./type_defs.md#listworkspacesrequestrequesttypedef)
- [ListWorkspacesResponseTypeDef](./type_defs.md#listworkspacesresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PermissionEntryTypeDef](./type_defs.md#permissionentrytypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RoleValuesTypeDef](./type_defs.md#rolevaluestypedef)
- [SamlAuthenticationTypeDef](./type_defs.md#samlauthenticationtypedef)
- [SamlConfigurationTypeDef](./type_defs.md#samlconfigurationtypedef)
- [UpdateErrorTypeDef](./type_defs.md#updateerrortypedef)
- [UpdateInstructionTypeDef](./type_defs.md#updateinstructiontypedef)
- [UpdatePermissionsRequestRequestTypeDef](./type_defs.md#updatepermissionsrequestrequesttypedef)
- [UpdatePermissionsResponseTypeDef](./type_defs.md#updatepermissionsresponsetypedef)
- [UpdateWorkspaceAuthenticationRequestRequestTypeDef](./type_defs.md#updateworkspaceauthenticationrequestrequesttypedef)
- [UpdateWorkspaceAuthenticationResponseTypeDef](./type_defs.md#updateworkspaceauthenticationresponsetypedef)
- [UpdateWorkspaceRequestRequestTypeDef](./type_defs.md#updateworkspacerequestrequesttypedef)
- [UpdateWorkspaceResponseTypeDef](./type_defs.md#updateworkspaceresponsetypedef)
- [UserTypeDef](./type_defs.md#usertypedef)
- [WorkspaceDescriptionTypeDef](./type_defs.md#workspacedescriptiontypedef)
- [WorkspaceSummaryTypeDef](./type_defs.md#workspacesummarytypedef)
