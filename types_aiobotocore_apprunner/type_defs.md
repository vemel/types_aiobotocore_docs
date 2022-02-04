<a id="typed-dictionaries-for-aiobotocore-apprunner-module"></a>

# Typed dictionaries for aiobotocore AppRunner module

> [Index](..) > [AppRunner](.) > Typed dictionaries

Auto-generated documentation for
[AppRunner](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
type annotations stubs module
[types-aiobotocore-apprunner](https://pypi.org/project/types-aiobotocore-apprunner/).

- [Typed dictionaries for aiobotocore AppRunner module](#typed-dictionaries-for-aiobotocore-apprunner-module)
  - [AssociateCustomDomainRequestRequestTypeDef](#associatecustomdomainrequestrequesttypedef)
  - [AssociateCustomDomainResponseTypeDef](#associatecustomdomainresponsetypedef)
  - [AuthenticationConfigurationTypeDef](#authenticationconfigurationtypedef)
  - [AutoScalingConfigurationSummaryTypeDef](#autoscalingconfigurationsummarytypedef)
  - [AutoScalingConfigurationTypeDef](#autoscalingconfigurationtypedef)
  - [CertificateValidationRecordTypeDef](#certificatevalidationrecordtypedef)
  - [CodeConfigurationTypeDef](#codeconfigurationtypedef)
  - [CodeConfigurationValuesTypeDef](#codeconfigurationvaluestypedef)
  - [CodeRepositoryTypeDef](#coderepositorytypedef)
  - [ConnectionSummaryTypeDef](#connectionsummarytypedef)
  - [ConnectionTypeDef](#connectiontypedef)
  - [CreateAutoScalingConfigurationRequestRequestTypeDef](#createautoscalingconfigurationrequestrequesttypedef)
  - [CreateAutoScalingConfigurationResponseTypeDef](#createautoscalingconfigurationresponsetypedef)
  - [CreateConnectionRequestRequestTypeDef](#createconnectionrequestrequesttypedef)
  - [CreateConnectionResponseTypeDef](#createconnectionresponsetypedef)
  - [CreateServiceRequestRequestTypeDef](#createservicerequestrequesttypedef)
  - [CreateServiceResponseTypeDef](#createserviceresponsetypedef)
  - [CustomDomainTypeDef](#customdomaintypedef)
  - [DeleteAutoScalingConfigurationRequestRequestTypeDef](#deleteautoscalingconfigurationrequestrequesttypedef)
  - [DeleteAutoScalingConfigurationResponseTypeDef](#deleteautoscalingconfigurationresponsetypedef)
  - [DeleteConnectionRequestRequestTypeDef](#deleteconnectionrequestrequesttypedef)
  - [DeleteConnectionResponseTypeDef](#deleteconnectionresponsetypedef)
  - [DeleteServiceRequestRequestTypeDef](#deleteservicerequestrequesttypedef)
  - [DeleteServiceResponseTypeDef](#deleteserviceresponsetypedef)
  - [DescribeAutoScalingConfigurationRequestRequestTypeDef](#describeautoscalingconfigurationrequestrequesttypedef)
  - [DescribeAutoScalingConfigurationResponseTypeDef](#describeautoscalingconfigurationresponsetypedef)
  - [DescribeCustomDomainsRequestRequestTypeDef](#describecustomdomainsrequestrequesttypedef)
  - [DescribeCustomDomainsResponseTypeDef](#describecustomdomainsresponsetypedef)
  - [DescribeServiceRequestRequestTypeDef](#describeservicerequestrequesttypedef)
  - [DescribeServiceResponseTypeDef](#describeserviceresponsetypedef)
  - [DisassociateCustomDomainRequestRequestTypeDef](#disassociatecustomdomainrequestrequesttypedef)
  - [DisassociateCustomDomainResponseTypeDef](#disassociatecustomdomainresponsetypedef)
  - [EncryptionConfigurationTypeDef](#encryptionconfigurationtypedef)
  - [HealthCheckConfigurationTypeDef](#healthcheckconfigurationtypedef)
  - [ImageConfigurationTypeDef](#imageconfigurationtypedef)
  - [ImageRepositoryTypeDef](#imagerepositorytypedef)
  - [InstanceConfigurationTypeDef](#instanceconfigurationtypedef)
  - [ListAutoScalingConfigurationsRequestRequestTypeDef](#listautoscalingconfigurationsrequestrequesttypedef)
  - [ListAutoScalingConfigurationsResponseTypeDef](#listautoscalingconfigurationsresponsetypedef)
  - [ListConnectionsRequestRequestTypeDef](#listconnectionsrequestrequesttypedef)
  - [ListConnectionsResponseTypeDef](#listconnectionsresponsetypedef)
  - [ListOperationsRequestRequestTypeDef](#listoperationsrequestrequesttypedef)
  - [ListOperationsResponseTypeDef](#listoperationsresponsetypedef)
  - [ListServicesRequestRequestTypeDef](#listservicesrequestrequesttypedef)
  - [ListServicesResponseTypeDef](#listservicesresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [OperationSummaryTypeDef](#operationsummarytypedef)
  - [PauseServiceRequestRequestTypeDef](#pauseservicerequestrequesttypedef)
  - [PauseServiceResponseTypeDef](#pauseserviceresponsetypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ResumeServiceRequestRequestTypeDef](#resumeservicerequestrequesttypedef)
  - [ResumeServiceResponseTypeDef](#resumeserviceresponsetypedef)
  - [ServiceSummaryTypeDef](#servicesummarytypedef)
  - [ServiceTypeDef](#servicetypedef)
  - [SourceCodeVersionTypeDef](#sourcecodeversiontypedef)
  - [SourceConfigurationTypeDef](#sourceconfigurationtypedef)
  - [StartDeploymentRequestRequestTypeDef](#startdeploymentrequestrequesttypedef)
  - [StartDeploymentResponseTypeDef](#startdeploymentresponsetypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateServiceRequestRequestTypeDef](#updateservicerequestrequesttypedef)
  - [UpdateServiceResponseTypeDef](#updateserviceresponsetypedef)

<a id="associatecustomdomainrequestrequesttypedef"></a>

## AssociateCustomDomainRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import AssociateCustomDomainRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`
- `DomainName`: `str`

Optional fields:

- `EnableWWWSubdomain`: `bool`

<a id="associatecustomdomainresponsetypedef"></a>

## AssociateCustomDomainResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import AssociateCustomDomainResponseTypeDef
```

Required fields:

- `DNSTarget`: `str`
- `ServiceArn`: `str`
- `CustomDomain`: [CustomDomainTypeDef](./type_defs.md#customdomaintypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="authenticationconfigurationtypedef"></a>

## AuthenticationConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import AuthenticationConfigurationTypeDef
```

Optional fields:

- `ConnectionArn`: `str`
- `AccessRoleArn`: `str`

<a id="autoscalingconfigurationsummarytypedef"></a>

## AutoScalingConfigurationSummaryTypeDef

```python
from types_aiobotocore_apprunner.type_defs import AutoScalingConfigurationSummaryTypeDef
```

Optional fields:

- `AutoScalingConfigurationArn`: `str`
- `AutoScalingConfigurationName`: `str`
- `AutoScalingConfigurationRevision`: `int`

<a id="autoscalingconfigurationtypedef"></a>

## AutoScalingConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import AutoScalingConfigurationTypeDef
```

Optional fields:

- `AutoScalingConfigurationArn`: `str`
- `AutoScalingConfigurationName`: `str`
- `AutoScalingConfigurationRevision`: `int`
- `Latest`: `bool`
- `Status`:
  [AutoScalingConfigurationStatusType](./literals.md#autoscalingconfigurationstatustype)
- `MaxConcurrency`: `int`
- `MinSize`: `int`
- `MaxSize`: `int`
- `CreatedAt`: `datetime`
- `DeletedAt`: `datetime`

<a id="certificatevalidationrecordtypedef"></a>

## CertificateValidationRecordTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CertificateValidationRecordTypeDef
```

Optional fields:

- `Name`: `str`
- `Type`: `str`
- `Value`: `str`
- `Status`:
  [CertificateValidationRecordStatusType](./literals.md#certificatevalidationrecordstatustype)

<a id="codeconfigurationtypedef"></a>

## CodeConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CodeConfigurationTypeDef
```

Required fields:

- `ConfigurationSource`:
  [ConfigurationSourceType](./literals.md#configurationsourcetype)

Optional fields:

- `CodeConfigurationValues`:
  [CodeConfigurationValuesTypeDef](./type_defs.md#codeconfigurationvaluestypedef)

<a id="codeconfigurationvaluestypedef"></a>

## CodeConfigurationValuesTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CodeConfigurationValuesTypeDef
```

Required fields:

- `Runtime`: [RuntimeType](./literals.md#runtimetype)

Optional fields:

- `BuildCommand`: `str`
- `StartCommand`: `str`
- `Port`: `str`
- `RuntimeEnvironmentVariables`: `Mapping`\[`str`, `str`\]

<a id="coderepositorytypedef"></a>

## CodeRepositoryTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CodeRepositoryTypeDef
```

Required fields:

- `RepositoryUrl`: `str`
- `SourceCodeVersion`:
  [SourceCodeVersionTypeDef](./type_defs.md#sourcecodeversiontypedef)

Optional fields:

- `CodeConfiguration`:
  [CodeConfigurationTypeDef](./type_defs.md#codeconfigurationtypedef)

<a id="connectionsummarytypedef"></a>

## ConnectionSummaryTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ConnectionSummaryTypeDef
```

Optional fields:

- `ConnectionName`: `str`
- `ConnectionArn`: `str`
- `ProviderType`: `Literal['GITHUB']` (see
  [ProviderTypeType](./literals.md#providertypetype))
- `Status`: [ConnectionStatusType](./literals.md#connectionstatustype)
- `CreatedAt`: `datetime`

<a id="connectiontypedef"></a>

## ConnectionTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ConnectionTypeDef
```

Optional fields:

- `ConnectionName`: `str`
- `ConnectionArn`: `str`
- `ProviderType`: `Literal['GITHUB']` (see
  [ProviderTypeType](./literals.md#providertypetype))
- `Status`: [ConnectionStatusType](./literals.md#connectionstatustype)
- `CreatedAt`: `datetime`

<a id="createautoscalingconfigurationrequestrequesttypedef"></a>

## CreateAutoScalingConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CreateAutoScalingConfigurationRequestRequestTypeDef
```

Required fields:

- `AutoScalingConfigurationName`: `str`

Optional fields:

- `MaxConcurrency`: `int`
- `MinSize`: `int`
- `MaxSize`: `int`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createautoscalingconfigurationresponsetypedef"></a>

## CreateAutoScalingConfigurationResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CreateAutoScalingConfigurationResponseTypeDef
```

Required fields:

- `AutoScalingConfiguration`:
  [AutoScalingConfigurationTypeDef](./type_defs.md#autoscalingconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createconnectionrequestrequesttypedef"></a>

## CreateConnectionRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CreateConnectionRequestRequestTypeDef
```

Required fields:

- `ConnectionName`: `str`
- `ProviderType`: `Literal['GITHUB']` (see
  [ProviderTypeType](./literals.md#providertypetype))

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createconnectionresponsetypedef"></a>

## CreateConnectionResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CreateConnectionResponseTypeDef
```

Required fields:

- `Connection`: [ConnectionTypeDef](./type_defs.md#connectiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createservicerequestrequesttypedef"></a>

## CreateServiceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CreateServiceRequestRequestTypeDef
```

Required fields:

- `ServiceName`: `str`
- `SourceConfiguration`:
  [SourceConfigurationTypeDef](./type_defs.md#sourceconfigurationtypedef)

Optional fields:

- `InstanceConfiguration`:
  [InstanceConfigurationTypeDef](./type_defs.md#instanceconfigurationtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `EncryptionConfiguration`:
  [EncryptionConfigurationTypeDef](./type_defs.md#encryptionconfigurationtypedef)
- `HealthCheckConfiguration`:
  [HealthCheckConfigurationTypeDef](./type_defs.md#healthcheckconfigurationtypedef)
- `AutoScalingConfigurationArn`: `str`

<a id="createserviceresponsetypedef"></a>

## CreateServiceResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CreateServiceResponseTypeDef
```

Required fields:

- `Service`: [ServiceTypeDef](./type_defs.md#servicetypedef)
- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="customdomaintypedef"></a>

## CustomDomainTypeDef

```python
from types_aiobotocore_apprunner.type_defs import CustomDomainTypeDef
```

Required fields:

- `DomainName`: `str`
- `EnableWWWSubdomain`: `bool`
- `Status`:
  [CustomDomainAssociationStatusType](./literals.md#customdomainassociationstatustype)

Optional fields:

- `CertificateValidationRecords`:
  `List`\[[CertificateValidationRecordTypeDef](./type_defs.md#certificatevalidationrecordtypedef)\]

<a id="deleteautoscalingconfigurationrequestrequesttypedef"></a>

## DeleteAutoScalingConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DeleteAutoScalingConfigurationRequestRequestTypeDef
```

Required fields:

- `AutoScalingConfigurationArn`: `str`

<a id="deleteautoscalingconfigurationresponsetypedef"></a>

## DeleteAutoScalingConfigurationResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DeleteAutoScalingConfigurationResponseTypeDef
```

Required fields:

- `AutoScalingConfiguration`:
  [AutoScalingConfigurationTypeDef](./type_defs.md#autoscalingconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteconnectionrequestrequesttypedef"></a>

## DeleteConnectionRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DeleteConnectionRequestRequestTypeDef
```

Required fields:

- `ConnectionArn`: `str`

<a id="deleteconnectionresponsetypedef"></a>

## DeleteConnectionResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DeleteConnectionResponseTypeDef
```

Required fields:

- `Connection`: [ConnectionTypeDef](./type_defs.md#connectiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteservicerequestrequesttypedef"></a>

## DeleteServiceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DeleteServiceRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

<a id="deleteserviceresponsetypedef"></a>

## DeleteServiceResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DeleteServiceResponseTypeDef
```

Required fields:

- `Service`: [ServiceTypeDef](./type_defs.md#servicetypedef)
- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeautoscalingconfigurationrequestrequesttypedef"></a>

## DescribeAutoScalingConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DescribeAutoScalingConfigurationRequestRequestTypeDef
```

Required fields:

- `AutoScalingConfigurationArn`: `str`

<a id="describeautoscalingconfigurationresponsetypedef"></a>

## DescribeAutoScalingConfigurationResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DescribeAutoScalingConfigurationResponseTypeDef
```

Required fields:

- `AutoScalingConfiguration`:
  [AutoScalingConfigurationTypeDef](./type_defs.md#autoscalingconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describecustomdomainsrequestrequesttypedef"></a>

## DescribeCustomDomainsRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DescribeCustomDomainsRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="describecustomdomainsresponsetypedef"></a>

## DescribeCustomDomainsResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DescribeCustomDomainsResponseTypeDef
```

Required fields:

- `DNSTarget`: `str`
- `ServiceArn`: `str`
- `CustomDomains`:
  `List`\[[CustomDomainTypeDef](./type_defs.md#customdomaintypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeservicerequestrequesttypedef"></a>

## DescribeServiceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DescribeServiceRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

<a id="describeserviceresponsetypedef"></a>

## DescribeServiceResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DescribeServiceResponseTypeDef
```

Required fields:

- `Service`: [ServiceTypeDef](./type_defs.md#servicetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disassociatecustomdomainrequestrequesttypedef"></a>

## DisassociateCustomDomainRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DisassociateCustomDomainRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`
- `DomainName`: `str`

<a id="disassociatecustomdomainresponsetypedef"></a>

## DisassociateCustomDomainResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import DisassociateCustomDomainResponseTypeDef
```

Required fields:

- `DNSTarget`: `str`
- `ServiceArn`: `str`
- `CustomDomain`: [CustomDomainTypeDef](./type_defs.md#customdomaintypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="encryptionconfigurationtypedef"></a>

## EncryptionConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import EncryptionConfigurationTypeDef
```

Required fields:

- `KmsKey`: `str`

<a id="healthcheckconfigurationtypedef"></a>

## HealthCheckConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import HealthCheckConfigurationTypeDef
```

Optional fields:

- `Protocol`: [HealthCheckProtocolType](./literals.md#healthcheckprotocoltype)
- `Path`: `str`
- `Interval`: `int`
- `Timeout`: `int`
- `HealthyThreshold`: `int`
- `UnhealthyThreshold`: `int`

<a id="imageconfigurationtypedef"></a>

## ImageConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ImageConfigurationTypeDef
```

Optional fields:

- `RuntimeEnvironmentVariables`: `Mapping`\[`str`, `str`\]
- `StartCommand`: `str`
- `Port`: `str`

<a id="imagerepositorytypedef"></a>

## ImageRepositoryTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ImageRepositoryTypeDef
```

Required fields:

- `ImageIdentifier`: `str`
- `ImageRepositoryType`:
  [ImageRepositoryTypeType](./literals.md#imagerepositorytypetype)

Optional fields:

- `ImageConfiguration`:
  [ImageConfigurationTypeDef](./type_defs.md#imageconfigurationtypedef)

<a id="instanceconfigurationtypedef"></a>

## InstanceConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import InstanceConfigurationTypeDef
```

Optional fields:

- `Cpu`: `str`
- `Memory`: `str`
- `InstanceRoleArn`: `str`

<a id="listautoscalingconfigurationsrequestrequesttypedef"></a>

## ListAutoScalingConfigurationsRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListAutoScalingConfigurationsRequestRequestTypeDef
```

Optional fields:

- `AutoScalingConfigurationName`: `str`
- `LatestOnly`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listautoscalingconfigurationsresponsetypedef"></a>

## ListAutoScalingConfigurationsResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListAutoScalingConfigurationsResponseTypeDef
```

Required fields:

- `AutoScalingConfigurationSummaryList`:
  `List`\[[AutoScalingConfigurationSummaryTypeDef](./type_defs.md#autoscalingconfigurationsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listconnectionsrequestrequesttypedef"></a>

## ListConnectionsRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListConnectionsRequestRequestTypeDef
```

Optional fields:

- `ConnectionName`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listconnectionsresponsetypedef"></a>

## ListConnectionsResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListConnectionsResponseTypeDef
```

Required fields:

- `ConnectionSummaryList`:
  `List`\[[ConnectionSummaryTypeDef](./type_defs.md#connectionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listoperationsrequestrequesttypedef"></a>

## ListOperationsRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListOperationsRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listoperationsresponsetypedef"></a>

## ListOperationsResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListOperationsResponseTypeDef
```

Required fields:

- `OperationSummaryList`:
  `List`\[[OperationSummaryTypeDef](./type_defs.md#operationsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listservicesrequestrequesttypedef"></a>

## ListServicesRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListServicesRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listservicesresponsetypedef"></a>

## ListServicesResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListServicesResponseTypeDef
```

Required fields:

- `ServiceSummaryList`:
  `List`\[[ServiceSummaryTypeDef](./type_defs.md#servicesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="operationsummarytypedef"></a>

## OperationSummaryTypeDef

```python
from types_aiobotocore_apprunner.type_defs import OperationSummaryTypeDef
```

Optional fields:

- `Id`: `str`
- `Type`: [OperationTypeType](./literals.md#operationtypetype)
- `Status`: [OperationStatusType](./literals.md#operationstatustype)
- `TargetArn`: `str`
- `StartedAt`: `datetime`
- `EndedAt`: `datetime`
- `UpdatedAt`: `datetime`

<a id="pauseservicerequestrequesttypedef"></a>

## PauseServiceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import PauseServiceRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

<a id="pauseserviceresponsetypedef"></a>

## PauseServiceResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import PauseServiceResponseTypeDef
```

Required fields:

- `Service`: [ServiceTypeDef](./type_defs.md#servicetypedef)
- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="resumeservicerequestrequesttypedef"></a>

## ResumeServiceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ResumeServiceRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

<a id="resumeserviceresponsetypedef"></a>

## ResumeServiceResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ResumeServiceResponseTypeDef
```

Required fields:

- `Service`: [ServiceTypeDef](./type_defs.md#servicetypedef)
- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="servicesummarytypedef"></a>

## ServiceSummaryTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ServiceSummaryTypeDef
```

Optional fields:

- `ServiceName`: `str`
- `ServiceId`: `str`
- `ServiceArn`: `str`
- `ServiceUrl`: `str`
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `Status`: [ServiceStatusType](./literals.md#servicestatustype)

<a id="servicetypedef"></a>

## ServiceTypeDef

```python
from types_aiobotocore_apprunner.type_defs import ServiceTypeDef
```

Required fields:

- `ServiceName`: `str`
- `ServiceId`: `str`
- `ServiceArn`: `str`
- `ServiceUrl`: `str`
- `CreatedAt`: `datetime`
- `UpdatedAt`: `datetime`
- `Status`: [ServiceStatusType](./literals.md#servicestatustype)
- `SourceConfiguration`:
  [SourceConfigurationTypeDef](./type_defs.md#sourceconfigurationtypedef)
- `InstanceConfiguration`:
  [InstanceConfigurationTypeDef](./type_defs.md#instanceconfigurationtypedef)
- `AutoScalingConfigurationSummary`:
  [AutoScalingConfigurationSummaryTypeDef](./type_defs.md#autoscalingconfigurationsummarytypedef)

Optional fields:

- `DeletedAt`: `datetime`
- `EncryptionConfiguration`:
  [EncryptionConfigurationTypeDef](./type_defs.md#encryptionconfigurationtypedef)
- `HealthCheckConfiguration`:
  [HealthCheckConfigurationTypeDef](./type_defs.md#healthcheckconfigurationtypedef)

<a id="sourcecodeversiontypedef"></a>

## SourceCodeVersionTypeDef

```python
from types_aiobotocore_apprunner.type_defs import SourceCodeVersionTypeDef
```

Required fields:

- `Type`: `Literal['BRANCH']` (see
  [SourceCodeVersionTypeType](./literals.md#sourcecodeversiontypetype))
- `Value`: `str`

<a id="sourceconfigurationtypedef"></a>

## SourceConfigurationTypeDef

```python
from types_aiobotocore_apprunner.type_defs import SourceConfigurationTypeDef
```

Optional fields:

- `CodeRepository`:
  [CodeRepositoryTypeDef](./type_defs.md#coderepositorytypedef)
- `ImageRepository`:
  [ImageRepositoryTypeDef](./type_defs.md#imagerepositorytypedef)
- `AutoDeploymentsEnabled`: `bool`
- `AuthenticationConfiguration`:
  [AuthenticationConfigurationTypeDef](./type_defs.md#authenticationconfigurationtypedef)

<a id="startdeploymentrequestrequesttypedef"></a>

## StartDeploymentRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import StartDeploymentRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

<a id="startdeploymentresponsetypedef"></a>

## StartDeploymentResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import StartDeploymentResponseTypeDef
```

Required fields:

- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_apprunner.type_defs import TagTypeDef
```

Optional fields:

- `Key`: `str`
- `Value`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updateservicerequestrequesttypedef"></a>

## UpdateServiceRequestRequestTypeDef

```python
from types_aiobotocore_apprunner.type_defs import UpdateServiceRequestRequestTypeDef
```

Required fields:

- `ServiceArn`: `str`

Optional fields:

- `SourceConfiguration`:
  [SourceConfigurationTypeDef](./type_defs.md#sourceconfigurationtypedef)
- `InstanceConfiguration`:
  [InstanceConfigurationTypeDef](./type_defs.md#instanceconfigurationtypedef)
- `AutoScalingConfigurationArn`: `str`
- `HealthCheckConfiguration`:
  [HealthCheckConfigurationTypeDef](./type_defs.md#healthcheckconfigurationtypedef)

<a id="updateserviceresponsetypedef"></a>

## UpdateServiceResponseTypeDef

```python
from types_aiobotocore_apprunner.type_defs import UpdateServiceResponseTypeDef
```

Required fields:

- `Service`: [ServiceTypeDef](./type_defs.md#servicetypedef)
- `OperationId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
