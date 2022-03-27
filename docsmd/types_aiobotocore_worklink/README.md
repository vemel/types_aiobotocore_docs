# WorkLink module

> [Index](../README.md) > WorkLink


!!! note ""

    Auto-generated documentation for [WorkLink](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink)
    type annotations stubs module [types-aiobotocore-worklink](https://pypi.org/project/types-aiobotocore-worklink/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `WorkLink`.

### From PyPI with pip

Install `types-aiobotocore` for `WorkLink` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[worklink]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[worklink]'


# standalone installation
python -m pip install types-aiobotocore-worklink
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-worklink
```

## Usage

Code samples can be found in [Examples](./usage.md).

## WorkLinkClient

Type annotations and code completion for  `#!python session.create_client("worklink")` as [WorkLinkClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_worklink.client import WorkLinkClient


session = get_session()
async with session.create_client("worklink") as client:
    client: WorkLinkClient
```








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_worklink.literals import AuthorizationProviderTypeType

def get_value() -> AuthorizationProviderTypeType:
    return "SAML"
```

- [AuthorizationProviderTypeType](./literals.md#authorizationprovidertypetype)
- [DeviceStatusType](./literals.md#devicestatustype)
- [DomainStatusType](./literals.md#domainstatustype)
- [FleetStatusType](./literals.md#fleetstatustype)
- [IdentityProviderTypeType](./literals.md#identityprovidertypetype)
- [WorkLinkServiceName](./literals.md#worklinkservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_worklink.type_defs import AssociateDomainRequestRequestTypeDef

def get_value() -> AssociateDomainRequestRequestTypeDef:
    return {
        "FleetArn": ...,
        "DomainName": ...,
        "AcmCertificateArn": ...,
    }
```

- [AssociateDomainRequestRequestTypeDef](./type_defs.md#associatedomainrequestrequesttypedef)
- [AssociateWebsiteAuthorizationProviderRequestRequestTypeDef](./type_defs.md#associatewebsiteauthorizationproviderrequestrequesttypedef)
- [AssociateWebsiteAuthorizationProviderResponseTypeDef](./type_defs.md#associatewebsiteauthorizationproviderresponsetypedef)
- [AssociateWebsiteCertificateAuthorityRequestRequestTypeDef](./type_defs.md#associatewebsitecertificateauthorityrequestrequesttypedef)
- [AssociateWebsiteCertificateAuthorityResponseTypeDef](./type_defs.md#associatewebsitecertificateauthorityresponsetypedef)
- [CreateFleetRequestRequestTypeDef](./type_defs.md#createfleetrequestrequesttypedef)
- [CreateFleetResponseTypeDef](./type_defs.md#createfleetresponsetypedef)
- [DeleteFleetRequestRequestTypeDef](./type_defs.md#deletefleetrequestrequesttypedef)
- [DescribeAuditStreamConfigurationRequestRequestTypeDef](./type_defs.md#describeauditstreamconfigurationrequestrequesttypedef)
- [DescribeAuditStreamConfigurationResponseTypeDef](./type_defs.md#describeauditstreamconfigurationresponsetypedef)
- [DescribeCompanyNetworkConfigurationRequestRequestTypeDef](./type_defs.md#describecompanynetworkconfigurationrequestrequesttypedef)
- [DescribeCompanyNetworkConfigurationResponseTypeDef](./type_defs.md#describecompanynetworkconfigurationresponsetypedef)
- [DescribeDevicePolicyConfigurationRequestRequestTypeDef](./type_defs.md#describedevicepolicyconfigurationrequestrequesttypedef)
- [DescribeDevicePolicyConfigurationResponseTypeDef](./type_defs.md#describedevicepolicyconfigurationresponsetypedef)
- [DescribeDeviceRequestRequestTypeDef](./type_defs.md#describedevicerequestrequesttypedef)
- [DescribeDeviceResponseTypeDef](./type_defs.md#describedeviceresponsetypedef)
- [DescribeDomainRequestRequestTypeDef](./type_defs.md#describedomainrequestrequesttypedef)
- [DescribeDomainResponseTypeDef](./type_defs.md#describedomainresponsetypedef)
- [DescribeFleetMetadataRequestRequestTypeDef](./type_defs.md#describefleetmetadatarequestrequesttypedef)
- [DescribeFleetMetadataResponseTypeDef](./type_defs.md#describefleetmetadataresponsetypedef)
- [DescribeIdentityProviderConfigurationRequestRequestTypeDef](./type_defs.md#describeidentityproviderconfigurationrequestrequesttypedef)
- [DescribeIdentityProviderConfigurationResponseTypeDef](./type_defs.md#describeidentityproviderconfigurationresponsetypedef)
- [DescribeWebsiteCertificateAuthorityRequestRequestTypeDef](./type_defs.md#describewebsitecertificateauthorityrequestrequesttypedef)
- [DescribeWebsiteCertificateAuthorityResponseTypeDef](./type_defs.md#describewebsitecertificateauthorityresponsetypedef)
- [DeviceSummaryTypeDef](./type_defs.md#devicesummarytypedef)
- [DisassociateDomainRequestRequestTypeDef](./type_defs.md#disassociatedomainrequestrequesttypedef)
- [DisassociateWebsiteAuthorizationProviderRequestRequestTypeDef](./type_defs.md#disassociatewebsiteauthorizationproviderrequestrequesttypedef)
- [DisassociateWebsiteCertificateAuthorityRequestRequestTypeDef](./type_defs.md#disassociatewebsitecertificateauthorityrequestrequesttypedef)
- [DomainSummaryTypeDef](./type_defs.md#domainsummarytypedef)
- [FleetSummaryTypeDef](./type_defs.md#fleetsummarytypedef)
- [ListDevicesRequestRequestTypeDef](./type_defs.md#listdevicesrequestrequesttypedef)
- [ListDevicesResponseTypeDef](./type_defs.md#listdevicesresponsetypedef)
- [ListDomainsRequestRequestTypeDef](./type_defs.md#listdomainsrequestrequesttypedef)
- [ListDomainsResponseTypeDef](./type_defs.md#listdomainsresponsetypedef)
- [ListFleetsRequestRequestTypeDef](./type_defs.md#listfleetsrequestrequesttypedef)
- [ListFleetsResponseTypeDef](./type_defs.md#listfleetsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListWebsiteAuthorizationProvidersRequestRequestTypeDef](./type_defs.md#listwebsiteauthorizationprovidersrequestrequesttypedef)
- [ListWebsiteAuthorizationProvidersResponseTypeDef](./type_defs.md#listwebsiteauthorizationprovidersresponsetypedef)
- [ListWebsiteCertificateAuthoritiesRequestRequestTypeDef](./type_defs.md#listwebsitecertificateauthoritiesrequestrequesttypedef)
- [ListWebsiteCertificateAuthoritiesResponseTypeDef](./type_defs.md#listwebsitecertificateauthoritiesresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RestoreDomainAccessRequestRequestTypeDef](./type_defs.md#restoredomainaccessrequestrequesttypedef)
- [RevokeDomainAccessRequestRequestTypeDef](./type_defs.md#revokedomainaccessrequestrequesttypedef)
- [SignOutUserRequestRequestTypeDef](./type_defs.md#signoutuserrequestrequesttypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateAuditStreamConfigurationRequestRequestTypeDef](./type_defs.md#updateauditstreamconfigurationrequestrequesttypedef)
- [UpdateCompanyNetworkConfigurationRequestRequestTypeDef](./type_defs.md#updatecompanynetworkconfigurationrequestrequesttypedef)
- [UpdateDevicePolicyConfigurationRequestRequestTypeDef](./type_defs.md#updatedevicepolicyconfigurationrequestrequesttypedef)
- [UpdateDomainMetadataRequestRequestTypeDef](./type_defs.md#updatedomainmetadatarequestrequesttypedef)
- [UpdateFleetMetadataRequestRequestTypeDef](./type_defs.md#updatefleetmetadatarequestrequesttypedef)
- [UpdateIdentityProviderConfigurationRequestRequestTypeDef](./type_defs.md#updateidentityproviderconfigurationrequestrequesttypedef)
- [WebsiteAuthorizationProviderSummaryTypeDef](./type_defs.md#websiteauthorizationprovidersummarytypedef)
- [WebsiteCaSummaryTypeDef](./type_defs.md#websitecasummarytypedef)

