<a id="type-annotations-for-aiobotocore-apprunner-module"></a>

# Type annotations for aiobotocore AppRunner module

> [Index](../README.md) > AppRunner

Auto-generated documentation for
[AppRunner](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
type annotations stubs module
[types-aiobotocore-apprunner](https://pypi.org/project/types-aiobotocore-apprunner/).

- [Type annotations for aiobotocore AppRunner module](#type-annotations-for-aiobotocore-apprunner-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [AppRunnerClient](#apprunnerclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `AppRunner`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `AppRunner` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[apprunner]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[apprunner]'


# standalone installation
python -m pip install types-aiobotocore-apprunner
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-apprunner
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="apprunnerclient"></a>

## AppRunnerClient

Type annotations for `session.create_client("apprunner")` as
[AppRunnerClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_apprunner.client import AppRunnerClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [associate_custom_domain](./client.md#associate_custom_domain)
- [can_paginate](./client.md#can_paginate)
- [create_auto_scaling_configuration](./client.md#create_auto_scaling_configuration)
- [create_connection](./client.md#create_connection)
- [create_service](./client.md#create_service)
- [create_vpc_connector](./client.md#create_vpc_connector)
- [delete_auto_scaling_configuration](./client.md#delete_auto_scaling_configuration)
- [delete_connection](./client.md#delete_connection)
- [delete_service](./client.md#delete_service)
- [delete_vpc_connector](./client.md#delete_vpc_connector)
- [describe_auto_scaling_configuration](./client.md#describe_auto_scaling_configuration)
- [describe_custom_domains](./client.md#describe_custom_domains)
- [describe_service](./client.md#describe_service)
- [describe_vpc_connector](./client.md#describe_vpc_connector)
- [disassociate_custom_domain](./client.md#disassociate_custom_domain)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [list_auto_scaling_configurations](./client.md#list_auto_scaling_configurations)
- [list_connections](./client.md#list_connections)
- [list_operations](./client.md#list_operations)
- [list_services](./client.md#list_services)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [list_vpc_connectors](./client.md#list_vpc_connectors)
- [pause_service](./client.md#pause_service)
- [resume_service](./client.md#resume_service)
- [start_deployment](./client.md#start_deployment)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_service](./client.md#update_service)

<a id="exceptions"></a>

### Exceptions

AppRunnerClient [exceptions](./client.md#exceptions)

- ClientError
- InternalServiceErrorException
- InvalidRequestException
- InvalidStateException
- ResourceNotFoundException
- ServiceQuotaExceededException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_apprunner.literals import AutoScalingConfigurationStatusType, ...
```

- [AutoScalingConfigurationStatusType](./literals.md#autoscalingconfigurationstatustype)
- [CertificateValidationRecordStatusType](./literals.md#certificatevalidationrecordstatustype)
- [ConfigurationSourceType](./literals.md#configurationsourcetype)
- [ConnectionStatusType](./literals.md#connectionstatustype)
- [CustomDomainAssociationStatusType](./literals.md#customdomainassociationstatustype)
- [EgressTypeType](./literals.md#egresstypetype)
- [HealthCheckProtocolType](./literals.md#healthcheckprotocoltype)
- [ImageRepositoryTypeType](./literals.md#imagerepositorytypetype)
- [OperationStatusType](./literals.md#operationstatustype)
- [OperationTypeType](./literals.md#operationtypetype)
- [ProviderTypeType](./literals.md#providertypetype)
- [RuntimeType](./literals.md#runtimetype)
- [ServiceStatusType](./literals.md#servicestatustype)
- [SourceCodeVersionTypeType](./literals.md#sourcecodeversiontypetype)
- [VpcConnectorStatusType](./literals.md#vpcconnectorstatustype)
- [AppRunnerServiceName](./literals.md#apprunnerservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_apprunner.type_defs import AssociateCustomDomainRequestRequestTypeDef, ...
```

- [AssociateCustomDomainRequestRequestTypeDef](./type_defs.md#associatecustomdomainrequestrequesttypedef)
- [AssociateCustomDomainResponseTypeDef](./type_defs.md#associatecustomdomainresponsetypedef)
- [AuthenticationConfigurationTypeDef](./type_defs.md#authenticationconfigurationtypedef)
- [AutoScalingConfigurationSummaryTypeDef](./type_defs.md#autoscalingconfigurationsummarytypedef)
- [AutoScalingConfigurationTypeDef](./type_defs.md#autoscalingconfigurationtypedef)
- [CertificateValidationRecordTypeDef](./type_defs.md#certificatevalidationrecordtypedef)
- [CodeConfigurationTypeDef](./type_defs.md#codeconfigurationtypedef)
- [CodeConfigurationValuesTypeDef](./type_defs.md#codeconfigurationvaluestypedef)
- [CodeRepositoryTypeDef](./type_defs.md#coderepositorytypedef)
- [ConnectionSummaryTypeDef](./type_defs.md#connectionsummarytypedef)
- [ConnectionTypeDef](./type_defs.md#connectiontypedef)
- [CreateAutoScalingConfigurationRequestRequestTypeDef](./type_defs.md#createautoscalingconfigurationrequestrequesttypedef)
- [CreateAutoScalingConfigurationResponseTypeDef](./type_defs.md#createautoscalingconfigurationresponsetypedef)
- [CreateConnectionRequestRequestTypeDef](./type_defs.md#createconnectionrequestrequesttypedef)
- [CreateConnectionResponseTypeDef](./type_defs.md#createconnectionresponsetypedef)
- [CreateServiceRequestRequestTypeDef](./type_defs.md#createservicerequestrequesttypedef)
- [CreateServiceResponseTypeDef](./type_defs.md#createserviceresponsetypedef)
- [CreateVpcConnectorRequestRequestTypeDef](./type_defs.md#createvpcconnectorrequestrequesttypedef)
- [CreateVpcConnectorResponseTypeDef](./type_defs.md#createvpcconnectorresponsetypedef)
- [CustomDomainTypeDef](./type_defs.md#customdomaintypedef)
- [DeleteAutoScalingConfigurationRequestRequestTypeDef](./type_defs.md#deleteautoscalingconfigurationrequestrequesttypedef)
- [DeleteAutoScalingConfigurationResponseTypeDef](./type_defs.md#deleteautoscalingconfigurationresponsetypedef)
- [DeleteConnectionRequestRequestTypeDef](./type_defs.md#deleteconnectionrequestrequesttypedef)
- [DeleteConnectionResponseTypeDef](./type_defs.md#deleteconnectionresponsetypedef)
- [DeleteServiceRequestRequestTypeDef](./type_defs.md#deleteservicerequestrequesttypedef)
- [DeleteServiceResponseTypeDef](./type_defs.md#deleteserviceresponsetypedef)
- [DeleteVpcConnectorRequestRequestTypeDef](./type_defs.md#deletevpcconnectorrequestrequesttypedef)
- [DeleteVpcConnectorResponseTypeDef](./type_defs.md#deletevpcconnectorresponsetypedef)
- [DescribeAutoScalingConfigurationRequestRequestTypeDef](./type_defs.md#describeautoscalingconfigurationrequestrequesttypedef)
- [DescribeAutoScalingConfigurationResponseTypeDef](./type_defs.md#describeautoscalingconfigurationresponsetypedef)
- [DescribeCustomDomainsRequestRequestTypeDef](./type_defs.md#describecustomdomainsrequestrequesttypedef)
- [DescribeCustomDomainsResponseTypeDef](./type_defs.md#describecustomdomainsresponsetypedef)
- [DescribeServiceRequestRequestTypeDef](./type_defs.md#describeservicerequestrequesttypedef)
- [DescribeServiceResponseTypeDef](./type_defs.md#describeserviceresponsetypedef)
- [DescribeVpcConnectorRequestRequestTypeDef](./type_defs.md#describevpcconnectorrequestrequesttypedef)
- [DescribeVpcConnectorResponseTypeDef](./type_defs.md#describevpcconnectorresponsetypedef)
- [DisassociateCustomDomainRequestRequestTypeDef](./type_defs.md#disassociatecustomdomainrequestrequesttypedef)
- [DisassociateCustomDomainResponseTypeDef](./type_defs.md#disassociatecustomdomainresponsetypedef)
- [EgressConfigurationTypeDef](./type_defs.md#egressconfigurationtypedef)
- [EncryptionConfigurationTypeDef](./type_defs.md#encryptionconfigurationtypedef)
- [HealthCheckConfigurationTypeDef](./type_defs.md#healthcheckconfigurationtypedef)
- [ImageConfigurationTypeDef](./type_defs.md#imageconfigurationtypedef)
- [ImageRepositoryTypeDef](./type_defs.md#imagerepositorytypedef)
- [InstanceConfigurationTypeDef](./type_defs.md#instanceconfigurationtypedef)
- [ListAutoScalingConfigurationsRequestRequestTypeDef](./type_defs.md#listautoscalingconfigurationsrequestrequesttypedef)
- [ListAutoScalingConfigurationsResponseTypeDef](./type_defs.md#listautoscalingconfigurationsresponsetypedef)
- [ListConnectionsRequestRequestTypeDef](./type_defs.md#listconnectionsrequestrequesttypedef)
- [ListConnectionsResponseTypeDef](./type_defs.md#listconnectionsresponsetypedef)
- [ListOperationsRequestRequestTypeDef](./type_defs.md#listoperationsrequestrequesttypedef)
- [ListOperationsResponseTypeDef](./type_defs.md#listoperationsresponsetypedef)
- [ListServicesRequestRequestTypeDef](./type_defs.md#listservicesrequestrequesttypedef)
- [ListServicesResponseTypeDef](./type_defs.md#listservicesresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListVpcConnectorsRequestRequestTypeDef](./type_defs.md#listvpcconnectorsrequestrequesttypedef)
- [ListVpcConnectorsResponseTypeDef](./type_defs.md#listvpcconnectorsresponsetypedef)
- [NetworkConfigurationTypeDef](./type_defs.md#networkconfigurationtypedef)
- [OperationSummaryTypeDef](./type_defs.md#operationsummarytypedef)
- [PauseServiceRequestRequestTypeDef](./type_defs.md#pauseservicerequestrequesttypedef)
- [PauseServiceResponseTypeDef](./type_defs.md#pauseserviceresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ResumeServiceRequestRequestTypeDef](./type_defs.md#resumeservicerequestrequesttypedef)
- [ResumeServiceResponseTypeDef](./type_defs.md#resumeserviceresponsetypedef)
- [ServiceSummaryTypeDef](./type_defs.md#servicesummarytypedef)
- [ServiceTypeDef](./type_defs.md#servicetypedef)
- [SourceCodeVersionTypeDef](./type_defs.md#sourcecodeversiontypedef)
- [SourceConfigurationTypeDef](./type_defs.md#sourceconfigurationtypedef)
- [StartDeploymentRequestRequestTypeDef](./type_defs.md#startdeploymentrequestrequesttypedef)
- [StartDeploymentResponseTypeDef](./type_defs.md#startdeploymentresponsetypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateServiceRequestRequestTypeDef](./type_defs.md#updateservicerequestrequesttypedef)
- [UpdateServiceResponseTypeDef](./type_defs.md#updateserviceresponsetypedef)
- [VpcConnectorTypeDef](./type_defs.md#vpcconnectortypedef)
