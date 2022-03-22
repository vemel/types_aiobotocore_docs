<a id="typed-dictionaries-for-aiobotocore-sso-module"></a>

# Typed dictionaries for aiobotocore SSO module

> [Index](../README.md) > [SSO](./README.md) > Typed dictionaries

Auto-generated documentation for
[SSO](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
type annotations stubs module
[types-aiobotocore-sso](https://pypi.org/project/types-aiobotocore-sso/).

- [Typed dictionaries for aiobotocore SSO module](#typed-dictionaries-for-aiobotocore-sso-module)
  - [AccountInfoTypeDef](#accountinfotypedef)
  - [GetRoleCredentialsRequestRequestTypeDef](#getrolecredentialsrequestrequesttypedef)
  - [GetRoleCredentialsResponseTypeDef](#getrolecredentialsresponsetypedef)
  - [ListAccountRolesRequestRequestTypeDef](#listaccountrolesrequestrequesttypedef)
  - [ListAccountRolesResponseTypeDef](#listaccountrolesresponsetypedef)
  - [ListAccountsRequestRequestTypeDef](#listaccountsrequestrequesttypedef)
  - [ListAccountsResponseTypeDef](#listaccountsresponsetypedef)
  - [LogoutRequestRequestTypeDef](#logoutrequestrequesttypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RoleCredentialsTypeDef](#rolecredentialstypedef)
  - [RoleInfoTypeDef](#roleinfotypedef)

<a id="accountinfotypedef"></a>

## AccountInfoTypeDef

```python
from types_aiobotocore_sso.type_defs import AccountInfoTypeDef
```

Optional fields:

- `accountId`: `str`
- `accountName`: `str`
- `emailAddress`: `str`

<a id="getrolecredentialsrequestrequesttypedef"></a>

## GetRoleCredentialsRequestRequestTypeDef

```python
from types_aiobotocore_sso.type_defs import GetRoleCredentialsRequestRequestTypeDef
```

Required fields:

- `roleName`: `str`
- `accountId`: `str`
- `accessToken`: `str`

<a id="getrolecredentialsresponsetypedef"></a>

## GetRoleCredentialsResponseTypeDef

```python
from types_aiobotocore_sso.type_defs import GetRoleCredentialsResponseTypeDef
```

Required fields:

- `roleCredentials`:
  [RoleCredentialsTypeDef](./type_defs.md#rolecredentialstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listaccountrolesrequestrequesttypedef"></a>

## ListAccountRolesRequestRequestTypeDef

```python
from types_aiobotocore_sso.type_defs import ListAccountRolesRequestRequestTypeDef
```

Required fields:

- `accessToken`: `str`
- `accountId`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listaccountrolesresponsetypedef"></a>

## ListAccountRolesResponseTypeDef

```python
from types_aiobotocore_sso.type_defs import ListAccountRolesResponseTypeDef
```

Required fields:

- `nextToken`: `str`
- `roleList`: `List`\[[RoleInfoTypeDef](./type_defs.md#roleinfotypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listaccountsrequestrequesttypedef"></a>

## ListAccountsRequestRequestTypeDef

```python
from types_aiobotocore_sso.type_defs import ListAccountsRequestRequestTypeDef
```

Required fields:

- `accessToken`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listaccountsresponsetypedef"></a>

## ListAccountsResponseTypeDef

```python
from types_aiobotocore_sso.type_defs import ListAccountsResponseTypeDef
```

Required fields:

- `nextToken`: `str`
- `accountList`:
  `List`\[[AccountInfoTypeDef](./type_defs.md#accountinfotypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="logoutrequestrequesttypedef"></a>

## LogoutRequestRequestTypeDef

```python
from types_aiobotocore_sso.type_defs import LogoutRequestRequestTypeDef
```

Required fields:

- `accessToken`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_sso.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_sso.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="rolecredentialstypedef"></a>

## RoleCredentialsTypeDef

```python
from types_aiobotocore_sso.type_defs import RoleCredentialsTypeDef
```

Optional fields:

- `accessKeyId`: `str`
- `secretAccessKey`: `str`
- `sessionToken`: `str`
- `expiration`: `int`

<a id="roleinfotypedef"></a>

## RoleInfoTypeDef

```python
from types_aiobotocore_sso.type_defs import RoleInfoTypeDef
```

Optional fields:

- `roleName`: `str`
- `accountId`: `str`
