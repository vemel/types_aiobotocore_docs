<a id="type-annotations-for-aiobotocore-sso-module"></a>

# Type annotations for aiobotocore SSO module

> [Index](..) > SSO

Auto-generated documentation for
[SSO](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
type annotations stubs module
[types-aiobotocore-sso](https://pypi.org/project/types-aiobotocore-sso/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[sso]'

# install as a standalone
pip install types-aiobotocore-sso
```

- [Type annotations for aiobotocore SSO module](#type-annotations-for-aiobotocore-sso-module)
  - [SSOClient](#ssoclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="ssoclient"></a>

## SSOClient

Type annotations for `aiobotocore.create_client("sso")` as
[SSOClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_sso.client import SSOClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_role_credentials](./client.md#get_role_credentials)
- [list_account_roles](./client.md#list_account_roles)
- [list_accounts](./client.md#list_accounts)
- [logout](./client.md#logout)

<a id="exceptions"></a>

### Exceptions

SSOClient [exceptions](./client.md#exceptions)

- ClientError
- InvalidRequestException
- ResourceNotFoundException
- TooManyRequestsException
- UnauthorizedException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("sso").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_sso.paginators import ListAccountRolesPaginator, ...
```

- [ListAccountRolesPaginator](./paginators.md#listaccountrolespaginator)
- [ListAccountsPaginator](./paginators.md#listaccountspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_sso.literals import ListAccountRolesPaginatorName, ...
```

- [ListAccountRolesPaginatorName](./literals.md#listaccountrolespaginatorname)
- [ListAccountsPaginatorName](./literals.md#listaccountspaginatorname)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_sso.type_defs import AccountInfoTypeDef, ...
```

- [AccountInfoTypeDef](./type_defs.md#accountinfotypedef)
- [GetRoleCredentialsRequestRequestTypeDef](./type_defs.md#getrolecredentialsrequestrequesttypedef)
- [GetRoleCredentialsResponseTypeDef](./type_defs.md#getrolecredentialsresponsetypedef)
- [ListAccountRolesRequestRequestTypeDef](./type_defs.md#listaccountrolesrequestrequesttypedef)
- [ListAccountRolesResponseTypeDef](./type_defs.md#listaccountrolesresponsetypedef)
- [ListAccountsRequestRequestTypeDef](./type_defs.md#listaccountsrequestrequesttypedef)
- [ListAccountsResponseTypeDef](./type_defs.md#listaccountsresponsetypedef)
- [LogoutRequestRequestTypeDef](./type_defs.md#logoutrequestrequesttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RoleCredentialsTypeDef](./type_defs.md#rolecredentialstypedef)
- [RoleInfoTypeDef](./type_defs.md#roleinfotypedef)
