# STS module

> [Index](../README.md) > STS


!!! note ""

    Auto-generated documentation for [STS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS)
    type annotations stubs module [types-aiobotocore-sts](https://pypi.org/project/types-aiobotocore-sts/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `STS`.

### From PyPI with pip

Install `types-aiobotocore` for `STS` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[sts]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[sts]'


# standalone installation
python -m pip install types-aiobotocore-sts
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-sts
```

## Usage

Code samples can be found in [Examples](./usage.md).

## STSClient

Type annotations and code completion for  `#!python session.create_client("sts")` as [STSClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_sts.client import STSClient


session = get_session()
async with session.create_client("sts") as client:
    client: STSClient
```








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_sts.literals import STSServiceName

def get_value() -> STSServiceName:
    return "sts"
```

- [STSServiceName](./literals.md#stsservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_sts.type_defs import AssumeRoleRequestRequestTypeDef

def get_value() -> AssumeRoleRequestRequestTypeDef:
    return {
        "RoleArn": ...,
        "RoleSessionName": ...,
    }
```

- [AssumeRoleRequestRequestTypeDef](./type_defs.md#assumerolerequestrequesttypedef)
- [AssumeRoleResponseTypeDef](./type_defs.md#assumeroleresponsetypedef)
- [AssumeRoleWithSAMLRequestRequestTypeDef](./type_defs.md#assumerolewithsamlrequestrequesttypedef)
- [AssumeRoleWithSAMLResponseTypeDef](./type_defs.md#assumerolewithsamlresponsetypedef)
- [AssumeRoleWithWebIdentityRequestRequestTypeDef](./type_defs.md#assumerolewithwebidentityrequestrequesttypedef)
- [AssumeRoleWithWebIdentityResponseTypeDef](./type_defs.md#assumerolewithwebidentityresponsetypedef)
- [AssumedRoleUserTypeDef](./type_defs.md#assumedroleusertypedef)
- [CredentialsTypeDef](./type_defs.md#credentialstypedef)
- [DecodeAuthorizationMessageRequestRequestTypeDef](./type_defs.md#decodeauthorizationmessagerequestrequesttypedef)
- [DecodeAuthorizationMessageResponseTypeDef](./type_defs.md#decodeauthorizationmessageresponsetypedef)
- [FederatedUserTypeDef](./type_defs.md#federatedusertypedef)
- [GetAccessKeyInfoRequestRequestTypeDef](./type_defs.md#getaccesskeyinforequestrequesttypedef)
- [GetAccessKeyInfoResponseTypeDef](./type_defs.md#getaccesskeyinforesponsetypedef)
- [GetCallerIdentityResponseTypeDef](./type_defs.md#getcalleridentityresponsetypedef)
- [GetFederationTokenRequestRequestTypeDef](./type_defs.md#getfederationtokenrequestrequesttypedef)
- [GetFederationTokenResponseTypeDef](./type_defs.md#getfederationtokenresponsetypedef)
- [GetSessionTokenRequestRequestTypeDef](./type_defs.md#getsessiontokenrequestrequesttypedef)
- [GetSessionTokenResponseTypeDef](./type_defs.md#getsessiontokenresponsetypedef)
- [PolicyDescriptorTypeTypeDef](./type_defs.md#policydescriptortypetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)

