<a id="typed-dictionaries-for-aiobotocore-appstream-module"></a>

# Typed dictionaries for aiobotocore AppStream module

> [Index](../README.md) > [AppStream](./README.md) > Typed dictionaries

Auto-generated documentation for
[AppStream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
type annotations stubs module
[types-aiobotocore-appstream](https://pypi.org/project/types-aiobotocore-appstream/).

- [Typed dictionaries for aiobotocore AppStream module](#typed-dictionaries-for-aiobotocore-appstream-module)
  - [AccessEndpointTypeDef](#accessendpointtypedef)
  - [AppBlockTypeDef](#appblocktypedef)
  - [ApplicationFleetAssociationTypeDef](#applicationfleetassociationtypedef)
  - [ApplicationSettingsResponseTypeDef](#applicationsettingsresponsetypedef)
  - [ApplicationSettingsTypeDef](#applicationsettingstypedef)
  - [ApplicationTypeDef](#applicationtypedef)
  - [AssociateApplicationFleetRequestRequestTypeDef](#associateapplicationfleetrequestrequesttypedef)
  - [AssociateApplicationFleetResultTypeDef](#associateapplicationfleetresulttypedef)
  - [AssociateApplicationToEntitlementRequestRequestTypeDef](#associateapplicationtoentitlementrequestrequesttypedef)
  - [AssociateFleetRequestRequestTypeDef](#associatefleetrequestrequesttypedef)
  - [BatchAssociateUserStackRequestRequestTypeDef](#batchassociateuserstackrequestrequesttypedef)
  - [BatchAssociateUserStackResultTypeDef](#batchassociateuserstackresulttypedef)
  - [BatchDisassociateUserStackRequestRequestTypeDef](#batchdisassociateuserstackrequestrequesttypedef)
  - [BatchDisassociateUserStackResultTypeDef](#batchdisassociateuserstackresulttypedef)
  - [ComputeCapacityStatusTypeDef](#computecapacitystatustypedef)
  - [ComputeCapacityTypeDef](#computecapacitytypedef)
  - [CopyImageRequestRequestTypeDef](#copyimagerequestrequesttypedef)
  - [CopyImageResponseTypeDef](#copyimageresponsetypedef)
  - [CreateAppBlockRequestRequestTypeDef](#createappblockrequestrequesttypedef)
  - [CreateAppBlockResultTypeDef](#createappblockresulttypedef)
  - [CreateApplicationRequestRequestTypeDef](#createapplicationrequestrequesttypedef)
  - [CreateApplicationResultTypeDef](#createapplicationresulttypedef)
  - [CreateDirectoryConfigRequestRequestTypeDef](#createdirectoryconfigrequestrequesttypedef)
  - [CreateDirectoryConfigResultTypeDef](#createdirectoryconfigresulttypedef)
  - [CreateEntitlementRequestRequestTypeDef](#createentitlementrequestrequesttypedef)
  - [CreateEntitlementResultTypeDef](#createentitlementresulttypedef)
  - [CreateFleetRequestRequestTypeDef](#createfleetrequestrequesttypedef)
  - [CreateFleetResultTypeDef](#createfleetresulttypedef)
  - [CreateImageBuilderRequestRequestTypeDef](#createimagebuilderrequestrequesttypedef)
  - [CreateImageBuilderResultTypeDef](#createimagebuilderresulttypedef)
  - [CreateImageBuilderStreamingURLRequestRequestTypeDef](#createimagebuilderstreamingurlrequestrequesttypedef)
  - [CreateImageBuilderStreamingURLResultTypeDef](#createimagebuilderstreamingurlresulttypedef)
  - [CreateStackRequestRequestTypeDef](#createstackrequestrequesttypedef)
  - [CreateStackResultTypeDef](#createstackresulttypedef)
  - [CreateStreamingURLRequestRequestTypeDef](#createstreamingurlrequestrequesttypedef)
  - [CreateStreamingURLResultTypeDef](#createstreamingurlresulttypedef)
  - [CreateUpdatedImageRequestRequestTypeDef](#createupdatedimagerequestrequesttypedef)
  - [CreateUpdatedImageResultTypeDef](#createupdatedimageresulttypedef)
  - [CreateUsageReportSubscriptionResultTypeDef](#createusagereportsubscriptionresulttypedef)
  - [CreateUserRequestRequestTypeDef](#createuserrequestrequesttypedef)
  - [DeleteAppBlockRequestRequestTypeDef](#deleteappblockrequestrequesttypedef)
  - [DeleteApplicationRequestRequestTypeDef](#deleteapplicationrequestrequesttypedef)
  - [DeleteDirectoryConfigRequestRequestTypeDef](#deletedirectoryconfigrequestrequesttypedef)
  - [DeleteEntitlementRequestRequestTypeDef](#deleteentitlementrequestrequesttypedef)
  - [DeleteFleetRequestRequestTypeDef](#deletefleetrequestrequesttypedef)
  - [DeleteImageBuilderRequestRequestTypeDef](#deleteimagebuilderrequestrequesttypedef)
  - [DeleteImageBuilderResultTypeDef](#deleteimagebuilderresulttypedef)
  - [DeleteImagePermissionsRequestRequestTypeDef](#deleteimagepermissionsrequestrequesttypedef)
  - [DeleteImageRequestRequestTypeDef](#deleteimagerequestrequesttypedef)
  - [DeleteImageResultTypeDef](#deleteimageresulttypedef)
  - [DeleteStackRequestRequestTypeDef](#deletestackrequestrequesttypedef)
  - [DeleteUserRequestRequestTypeDef](#deleteuserrequestrequesttypedef)
  - [DescribeAppBlocksRequestRequestTypeDef](#describeappblocksrequestrequesttypedef)
  - [DescribeAppBlocksResultTypeDef](#describeappblocksresulttypedef)
  - [DescribeApplicationFleetAssociationsRequestRequestTypeDef](#describeapplicationfleetassociationsrequestrequesttypedef)
  - [DescribeApplicationFleetAssociationsResultTypeDef](#describeapplicationfleetassociationsresulttypedef)
  - [DescribeApplicationsRequestRequestTypeDef](#describeapplicationsrequestrequesttypedef)
  - [DescribeApplicationsResultTypeDef](#describeapplicationsresulttypedef)
  - [DescribeDirectoryConfigsRequestRequestTypeDef](#describedirectoryconfigsrequestrequesttypedef)
  - [DescribeDirectoryConfigsResultTypeDef](#describedirectoryconfigsresulttypedef)
  - [DescribeEntitlementsRequestRequestTypeDef](#describeentitlementsrequestrequesttypedef)
  - [DescribeEntitlementsResultTypeDef](#describeentitlementsresulttypedef)
  - [DescribeFleetsRequestRequestTypeDef](#describefleetsrequestrequesttypedef)
  - [DescribeFleetsResultTypeDef](#describefleetsresulttypedef)
  - [DescribeImageBuildersRequestRequestTypeDef](#describeimagebuildersrequestrequesttypedef)
  - [DescribeImageBuildersResultTypeDef](#describeimagebuildersresulttypedef)
  - [DescribeImagePermissionsRequestRequestTypeDef](#describeimagepermissionsrequestrequesttypedef)
  - [DescribeImagePermissionsResultTypeDef](#describeimagepermissionsresulttypedef)
  - [DescribeImagesRequestRequestTypeDef](#describeimagesrequestrequesttypedef)
  - [DescribeImagesResultTypeDef](#describeimagesresulttypedef)
  - [DescribeSessionsRequestRequestTypeDef](#describesessionsrequestrequesttypedef)
  - [DescribeSessionsResultTypeDef](#describesessionsresulttypedef)
  - [DescribeStacksRequestRequestTypeDef](#describestacksrequestrequesttypedef)
  - [DescribeStacksResultTypeDef](#describestacksresulttypedef)
  - [DescribeUsageReportSubscriptionsRequestRequestTypeDef](#describeusagereportsubscriptionsrequestrequesttypedef)
  - [DescribeUsageReportSubscriptionsResultTypeDef](#describeusagereportsubscriptionsresulttypedef)
  - [DescribeUserStackAssociationsRequestRequestTypeDef](#describeuserstackassociationsrequestrequesttypedef)
  - [DescribeUserStackAssociationsResultTypeDef](#describeuserstackassociationsresulttypedef)
  - [DescribeUsersRequestRequestTypeDef](#describeusersrequestrequesttypedef)
  - [DescribeUsersResultTypeDef](#describeusersresulttypedef)
  - [DirectoryConfigTypeDef](#directoryconfigtypedef)
  - [DisableUserRequestRequestTypeDef](#disableuserrequestrequesttypedef)
  - [DisassociateApplicationFleetRequestRequestTypeDef](#disassociateapplicationfleetrequestrequesttypedef)
  - [DisassociateApplicationFromEntitlementRequestRequestTypeDef](#disassociateapplicationfromentitlementrequestrequesttypedef)
  - [DisassociateFleetRequestRequestTypeDef](#disassociatefleetrequestrequesttypedef)
  - [DomainJoinInfoTypeDef](#domainjoininfotypedef)
  - [EnableUserRequestRequestTypeDef](#enableuserrequestrequesttypedef)
  - [EntitledApplicationTypeDef](#entitledapplicationtypedef)
  - [EntitlementAttributeTypeDef](#entitlementattributetypedef)
  - [EntitlementTypeDef](#entitlementtypedef)
  - [ExpireSessionRequestRequestTypeDef](#expiresessionrequestrequesttypedef)
  - [FleetErrorTypeDef](#fleeterrortypedef)
  - [FleetTypeDef](#fleettypedef)
  - [ImageBuilderStateChangeReasonTypeDef](#imagebuilderstatechangereasontypedef)
  - [ImageBuilderTypeDef](#imagebuildertypedef)
  - [ImagePermissionsTypeDef](#imagepermissionstypedef)
  - [ImageStateChangeReasonTypeDef](#imagestatechangereasontypedef)
  - [ImageTypeDef](#imagetypedef)
  - [LastReportGenerationExecutionErrorTypeDef](#lastreportgenerationexecutionerrortypedef)
  - [ListAssociatedFleetsRequestRequestTypeDef](#listassociatedfleetsrequestrequesttypedef)
  - [ListAssociatedFleetsResultTypeDef](#listassociatedfleetsresulttypedef)
  - [ListAssociatedStacksRequestRequestTypeDef](#listassociatedstacksrequestrequesttypedef)
  - [ListAssociatedStacksResultTypeDef](#listassociatedstacksresulttypedef)
  - [ListEntitledApplicationsRequestRequestTypeDef](#listentitledapplicationsrequestrequesttypedef)
  - [ListEntitledApplicationsResultTypeDef](#listentitledapplicationsresulttypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [NetworkAccessConfigurationTypeDef](#networkaccessconfigurationtypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ResourceErrorTypeDef](#resourceerrortypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3LocationTypeDef](#s3locationtypedef)
  - [ScriptDetailsTypeDef](#scriptdetailstypedef)
  - [ServiceAccountCredentialsTypeDef](#serviceaccountcredentialstypedef)
  - [SessionTypeDef](#sessiontypedef)
  - [SharedImagePermissionsTypeDef](#sharedimagepermissionstypedef)
  - [StackErrorTypeDef](#stackerrortypedef)
  - [StackTypeDef](#stacktypedef)
  - [StartFleetRequestRequestTypeDef](#startfleetrequestrequesttypedef)
  - [StartImageBuilderRequestRequestTypeDef](#startimagebuilderrequestrequesttypedef)
  - [StartImageBuilderResultTypeDef](#startimagebuilderresulttypedef)
  - [StopFleetRequestRequestTypeDef](#stopfleetrequestrequesttypedef)
  - [StopImageBuilderRequestRequestTypeDef](#stopimagebuilderrequestrequesttypedef)
  - [StopImageBuilderResultTypeDef](#stopimagebuilderresulttypedef)
  - [StorageConnectorTypeDef](#storageconnectortypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateApplicationRequestRequestTypeDef](#updateapplicationrequestrequesttypedef)
  - [UpdateApplicationResultTypeDef](#updateapplicationresulttypedef)
  - [UpdateDirectoryConfigRequestRequestTypeDef](#updatedirectoryconfigrequestrequesttypedef)
  - [UpdateDirectoryConfigResultTypeDef](#updatedirectoryconfigresulttypedef)
  - [UpdateEntitlementRequestRequestTypeDef](#updateentitlementrequestrequesttypedef)
  - [UpdateEntitlementResultTypeDef](#updateentitlementresulttypedef)
  - [UpdateFleetRequestRequestTypeDef](#updatefleetrequestrequesttypedef)
  - [UpdateFleetResultTypeDef](#updatefleetresulttypedef)
  - [UpdateImagePermissionsRequestRequestTypeDef](#updateimagepermissionsrequestrequesttypedef)
  - [UpdateStackRequestRequestTypeDef](#updatestackrequestrequesttypedef)
  - [UpdateStackResultTypeDef](#updatestackresulttypedef)
  - [UsageReportSubscriptionTypeDef](#usagereportsubscriptiontypedef)
  - [UserSettingTypeDef](#usersettingtypedef)
  - [UserStackAssociationErrorTypeDef](#userstackassociationerrortypedef)
  - [UserStackAssociationTypeDef](#userstackassociationtypedef)
  - [UserTypeDef](#usertypedef)
  - [VpcConfigTypeDef](#vpcconfigtypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)

<a id="accessendpointtypedef"></a>

## AccessEndpointTypeDef

```python
from types_aiobotocore_appstream.type_defs import AccessEndpointTypeDef
```

Required fields:

- `EndpointType`: `Literal['STREAMING']` (see
  [AccessEndpointTypeType](./literals.md#accessendpointtypetype))

Optional fields:

- `VpceId`: `str`

<a id="appblocktypedef"></a>

## AppBlockTypeDef

```python
from types_aiobotocore_appstream.type_defs import AppBlockTypeDef
```

Required fields:

- `Name`: `str`
- `Arn`: `str`
- `SetupScriptDetails`:
  [ScriptDetailsTypeDef](./type_defs.md#scriptdetailstypedef)

Optional fields:

- `Description`: `str`
- `DisplayName`: `str`
- `SourceS3Location`: [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- `CreatedTime`: `datetime`

<a id="applicationfleetassociationtypedef"></a>

## ApplicationFleetAssociationTypeDef

```python
from types_aiobotocore_appstream.type_defs import ApplicationFleetAssociationTypeDef
```

Required fields:

- `FleetName`: `str`
- `ApplicationArn`: `str`

<a id="applicationsettingsresponsetypedef"></a>

## ApplicationSettingsResponseTypeDef

```python
from types_aiobotocore_appstream.type_defs import ApplicationSettingsResponseTypeDef
```

Optional fields:

- `Enabled`: `bool`
- `SettingsGroup`: `str`
- `S3BucketName`: `str`

<a id="applicationsettingstypedef"></a>

## ApplicationSettingsTypeDef

```python
from types_aiobotocore_appstream.type_defs import ApplicationSettingsTypeDef
```

Required fields:

- `Enabled`: `bool`

Optional fields:

- `SettingsGroup`: `str`

<a id="applicationtypedef"></a>

## ApplicationTypeDef

```python
from types_aiobotocore_appstream.type_defs import ApplicationTypeDef
```

Optional fields:

- `Name`: `str`
- `DisplayName`: `str`
- `IconURL`: `str`
- `LaunchPath`: `str`
- `LaunchParameters`: `str`
- `Enabled`: `bool`
- `Metadata`: `Dict`\[`str`, `str`\]
- `WorkingDirectory`: `str`
- `Description`: `str`
- `Arn`: `str`
- `AppBlockArn`: `str`
- `IconS3Location`: [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- `Platforms`: `List`\[[PlatformTypeType](./literals.md#platformtypetype)\]
- `InstanceFamilies`: `List`\[`str`\]
- `CreatedTime`: `datetime`

<a id="associateapplicationfleetrequestrequesttypedef"></a>

## AssociateApplicationFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import AssociateApplicationFleetRequestRequestTypeDef
```

Required fields:

- `FleetName`: `str`
- `ApplicationArn`: `str`

<a id="associateapplicationfleetresulttypedef"></a>

## AssociateApplicationFleetResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import AssociateApplicationFleetResultTypeDef
```

Required fields:

- `ApplicationFleetAssociation`:
  [ApplicationFleetAssociationTypeDef](./type_defs.md#applicationfleetassociationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="associateapplicationtoentitlementrequestrequesttypedef"></a>

## AssociateApplicationToEntitlementRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import AssociateApplicationToEntitlementRequestRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `EntitlementName`: `str`
- `ApplicationIdentifier`: `str`

<a id="associatefleetrequestrequesttypedef"></a>

## AssociateFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import AssociateFleetRequestRequestTypeDef
```

Required fields:

- `FleetName`: `str`
- `StackName`: `str`

<a id="batchassociateuserstackrequestrequesttypedef"></a>

## BatchAssociateUserStackRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import BatchAssociateUserStackRequestRequestTypeDef
```

Required fields:

- `UserStackAssociations`:
  `Sequence`\[[UserStackAssociationTypeDef](./type_defs.md#userstackassociationtypedef)\]

<a id="batchassociateuserstackresulttypedef"></a>

## BatchAssociateUserStackResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import BatchAssociateUserStackResultTypeDef
```

Required fields:

- `errors`:
  `List`\[[UserStackAssociationErrorTypeDef](./type_defs.md#userstackassociationerrortypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="batchdisassociateuserstackrequestrequesttypedef"></a>

## BatchDisassociateUserStackRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import BatchDisassociateUserStackRequestRequestTypeDef
```

Required fields:

- `UserStackAssociations`:
  `Sequence`\[[UserStackAssociationTypeDef](./type_defs.md#userstackassociationtypedef)\]

<a id="batchdisassociateuserstackresulttypedef"></a>

## BatchDisassociateUserStackResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import BatchDisassociateUserStackResultTypeDef
```

Required fields:

- `errors`:
  `List`\[[UserStackAssociationErrorTypeDef](./type_defs.md#userstackassociationerrortypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="computecapacitystatustypedef"></a>

## ComputeCapacityStatusTypeDef

```python
from types_aiobotocore_appstream.type_defs import ComputeCapacityStatusTypeDef
```

Required fields:

- `Desired`: `int`

Optional fields:

- `Running`: `int`
- `InUse`: `int`
- `Available`: `int`

<a id="computecapacitytypedef"></a>

## ComputeCapacityTypeDef

```python
from types_aiobotocore_appstream.type_defs import ComputeCapacityTypeDef
```

Required fields:

- `DesiredInstances`: `int`

<a id="copyimagerequestrequesttypedef"></a>

## CopyImageRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CopyImageRequestRequestTypeDef
```

Required fields:

- `SourceImageName`: `str`
- `DestinationImageName`: `str`
- `DestinationRegion`: `str`

Optional fields:

- `DestinationImageDescription`: `str`

<a id="copyimageresponsetypedef"></a>

## CopyImageResponseTypeDef

```python
from types_aiobotocore_appstream.type_defs import CopyImageResponseTypeDef
```

Required fields:

- `DestinationImageName`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createappblockrequestrequesttypedef"></a>

## CreateAppBlockRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateAppBlockRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `SourceS3Location`: [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- `SetupScriptDetails`:
  [ScriptDetailsTypeDef](./type_defs.md#scriptdetailstypedef)

Optional fields:

- `Description`: `str`
- `DisplayName`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="createappblockresulttypedef"></a>

## CreateAppBlockResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateAppBlockResultTypeDef
```

Required fields:

- `AppBlock`: [AppBlockTypeDef](./type_defs.md#appblocktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createapplicationrequestrequesttypedef"></a>

## CreateApplicationRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateApplicationRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `IconS3Location`: [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- `LaunchPath`: `str`
- `Platforms`: `Sequence`\[[PlatformTypeType](./literals.md#platformtypetype)\]
- `InstanceFamilies`: `Sequence`\[`str`\]
- `AppBlockArn`: `str`

Optional fields:

- `DisplayName`: `str`
- `Description`: `str`
- `WorkingDirectory`: `str`
- `LaunchParameters`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="createapplicationresulttypedef"></a>

## CreateApplicationResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateApplicationResultTypeDef
```

Required fields:

- `Application`: [ApplicationTypeDef](./type_defs.md#applicationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdirectoryconfigrequestrequesttypedef"></a>

## CreateDirectoryConfigRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateDirectoryConfigRequestRequestTypeDef
```

Required fields:

- `DirectoryName`: `str`
- `OrganizationalUnitDistinguishedNames`: `Sequence`\[`str`\]

Optional fields:

- `ServiceAccountCredentials`:
  [ServiceAccountCredentialsTypeDef](./type_defs.md#serviceaccountcredentialstypedef)

<a id="createdirectoryconfigresulttypedef"></a>

## CreateDirectoryConfigResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateDirectoryConfigResultTypeDef
```

Required fields:

- `DirectoryConfig`:
  [DirectoryConfigTypeDef](./type_defs.md#directoryconfigtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createentitlementrequestrequesttypedef"></a>

## CreateEntitlementRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateEntitlementRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `StackName`: `str`
- `AppVisibility`: [AppVisibilityType](./literals.md#appvisibilitytype)
- `Attributes`:
  `Sequence`\[[EntitlementAttributeTypeDef](./type_defs.md#entitlementattributetypedef)\]

Optional fields:

- `Description`: `str`

<a id="createentitlementresulttypedef"></a>

## CreateEntitlementResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateEntitlementResultTypeDef
```

Required fields:

- `Entitlement`: [EntitlementTypeDef](./type_defs.md#entitlementtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createfleetrequestrequesttypedef"></a>

## CreateFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateFleetRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `InstanceType`: `str`

Optional fields:

- `ImageName`: `str`
- `ImageArn`: `str`
- `FleetType`: [FleetTypeType](./literals.md#fleettypetype)
- `ComputeCapacity`:
  [ComputeCapacityTypeDef](./type_defs.md#computecapacitytypedef)
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `MaxUserDurationInSeconds`: `int`
- `DisconnectTimeoutInSeconds`: `int`
- `Description`: `str`
- `DisplayName`: `str`
- `EnableDefaultInternetAccess`: `bool`
- `DomainJoinInfo`:
  [DomainJoinInfoTypeDef](./type_defs.md#domainjoininfotypedef)
- `Tags`: `Mapping`\[`str`, `str`\]
- `IdleDisconnectTimeoutInSeconds`: `int`
- `IamRoleArn`: `str`
- `StreamView`: [StreamViewType](./literals.md#streamviewtype)
- `Platform`: [PlatformTypeType](./literals.md#platformtypetype)
- `MaxConcurrentSessions`: `int`
- `UsbDeviceFilterStrings`: `Sequence`\[`str`\]

<a id="createfleetresulttypedef"></a>

## CreateFleetResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateFleetResultTypeDef
```

Required fields:

- `Fleet`: [FleetTypeDef](./type_defs.md#fleettypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createimagebuilderrequestrequesttypedef"></a>

## CreateImageBuilderRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateImageBuilderRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `InstanceType`: `str`

Optional fields:

- `ImageName`: `str`
- `ImageArn`: `str`
- `Description`: `str`
- `DisplayName`: `str`
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `IamRoleArn`: `str`
- `EnableDefaultInternetAccess`: `bool`
- `DomainJoinInfo`:
  [DomainJoinInfoTypeDef](./type_defs.md#domainjoininfotypedef)
- `AppstreamAgentVersion`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `AccessEndpoints`:
  `Sequence`\[[AccessEndpointTypeDef](./type_defs.md#accessendpointtypedef)\]

<a id="createimagebuilderresulttypedef"></a>

## CreateImageBuilderResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateImageBuilderResultTypeDef
```

Required fields:

- `ImageBuilder`: [ImageBuilderTypeDef](./type_defs.md#imagebuildertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createimagebuilderstreamingurlrequestrequesttypedef"></a>

## CreateImageBuilderStreamingURLRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateImageBuilderStreamingURLRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Validity`: `int`

<a id="createimagebuilderstreamingurlresulttypedef"></a>

## CreateImageBuilderStreamingURLResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateImageBuilderStreamingURLResultTypeDef
```

Required fields:

- `StreamingURL`: `str`
- `Expires`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createstackrequestrequesttypedef"></a>

## CreateStackRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateStackRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Description`: `str`
- `DisplayName`: `str`
- `StorageConnectors`:
  `Sequence`\[[StorageConnectorTypeDef](./type_defs.md#storageconnectortypedef)\]
- `RedirectURL`: `str`
- `FeedbackURL`: `str`
- `UserSettings`:
  `Sequence`\[[UserSettingTypeDef](./type_defs.md#usersettingtypedef)\]
- `ApplicationSettings`:
  [ApplicationSettingsTypeDef](./type_defs.md#applicationsettingstypedef)
- `Tags`: `Mapping`\[`str`, `str`\]
- `AccessEndpoints`:
  `Sequence`\[[AccessEndpointTypeDef](./type_defs.md#accessendpointtypedef)\]
- `EmbedHostDomains`: `Sequence`\[`str`\]

<a id="createstackresulttypedef"></a>

## CreateStackResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateStackResultTypeDef
```

Required fields:

- `Stack`: [StackTypeDef](./type_defs.md#stacktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createstreamingurlrequestrequesttypedef"></a>

## CreateStreamingURLRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateStreamingURLRequestRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `FleetName`: `str`
- `UserId`: `str`

Optional fields:

- `ApplicationId`: `str`
- `Validity`: `int`
- `SessionContext`: `str`

<a id="createstreamingurlresulttypedef"></a>

## CreateStreamingURLResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateStreamingURLResultTypeDef
```

Required fields:

- `StreamingURL`: `str`
- `Expires`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createupdatedimagerequestrequesttypedef"></a>

## CreateUpdatedImageRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateUpdatedImageRequestRequestTypeDef
```

Required fields:

- `existingImageName`: `str`
- `newImageName`: `str`

Optional fields:

- `newImageDescription`: `str`
- `newImageDisplayName`: `str`
- `newImageTags`: `Mapping`\[`str`, `str`\]
- `dryRun`: `bool`

<a id="createupdatedimageresulttypedef"></a>

## CreateUpdatedImageResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateUpdatedImageResultTypeDef
```

Required fields:

- `image`: [ImageTypeDef](./type_defs.md#imagetypedef)
- `canUpdateImage`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createusagereportsubscriptionresulttypedef"></a>

## CreateUsageReportSubscriptionResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateUsageReportSubscriptionResultTypeDef
```

Required fields:

- `S3BucketName`: `str`
- `Schedule`: `Literal['DAILY']` (see
  [UsageReportScheduleType](./literals.md#usagereportscheduletype))
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createuserrequestrequesttypedef"></a>

## CreateUserRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import CreateUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

Optional fields:

- `MessageAction`: [MessageActionType](./literals.md#messageactiontype)
- `FirstName`: `str`
- `LastName`: `str`

<a id="deleteappblockrequestrequesttypedef"></a>

## DeleteAppBlockRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteAppBlockRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="deleteapplicationrequestrequesttypedef"></a>

## DeleteApplicationRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteApplicationRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="deletedirectoryconfigrequestrequesttypedef"></a>

## DeleteDirectoryConfigRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteDirectoryConfigRequestRequestTypeDef
```

Required fields:

- `DirectoryName`: `str`

<a id="deleteentitlementrequestrequesttypedef"></a>

## DeleteEntitlementRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteEntitlementRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `StackName`: `str`

<a id="deletefleetrequestrequesttypedef"></a>

## DeleteFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteFleetRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="deleteimagebuilderrequestrequesttypedef"></a>

## DeleteImageBuilderRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteImageBuilderRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="deleteimagebuilderresulttypedef"></a>

## DeleteImageBuilderResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteImageBuilderResultTypeDef
```

Required fields:

- `ImageBuilder`: [ImageBuilderTypeDef](./type_defs.md#imagebuildertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteimagepermissionsrequestrequesttypedef"></a>

## DeleteImagePermissionsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteImagePermissionsRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `SharedAccountId`: `str`

<a id="deleteimagerequestrequesttypedef"></a>

## DeleteImageRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteImageRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="deleteimageresulttypedef"></a>

## DeleteImageResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteImageResultTypeDef
```

Required fields:

- `Image`: [ImageTypeDef](./type_defs.md#imagetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletestackrequestrequesttypedef"></a>

## DeleteStackRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteStackRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="deleteuserrequestrequesttypedef"></a>

## DeleteUserRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DeleteUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

<a id="describeappblocksrequestrequesttypedef"></a>

## DescribeAppBlocksRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeAppBlocksRequestRequestTypeDef
```

Optional fields:

- `Arns`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="describeappblocksresulttypedef"></a>

## DescribeAppBlocksResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeAppBlocksResultTypeDef
```

Required fields:

- `AppBlocks`: `List`\[[AppBlockTypeDef](./type_defs.md#appblocktypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeapplicationfleetassociationsrequestrequesttypedef"></a>

## DescribeApplicationFleetAssociationsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeApplicationFleetAssociationsRequestRequestTypeDef
```

Optional fields:

- `FleetName`: `str`
- `ApplicationArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describeapplicationfleetassociationsresulttypedef"></a>

## DescribeApplicationFleetAssociationsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeApplicationFleetAssociationsResultTypeDef
```

Required fields:

- `ApplicationFleetAssociations`:
  `List`\[[ApplicationFleetAssociationTypeDef](./type_defs.md#applicationfleetassociationtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeapplicationsrequestrequesttypedef"></a>

## DescribeApplicationsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeApplicationsRequestRequestTypeDef
```

Optional fields:

- `Arns`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="describeapplicationsresulttypedef"></a>

## DescribeApplicationsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeApplicationsResultTypeDef
```

Required fields:

- `Applications`:
  `List`\[[ApplicationTypeDef](./type_defs.md#applicationtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedirectoryconfigsrequestrequesttypedef"></a>

## DescribeDirectoryConfigsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeDirectoryConfigsRequestRequestTypeDef
```

Optional fields:

- `DirectoryNames`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describedirectoryconfigsresulttypedef"></a>

## DescribeDirectoryConfigsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeDirectoryConfigsResultTypeDef
```

Required fields:

- `DirectoryConfigs`:
  `List`\[[DirectoryConfigTypeDef](./type_defs.md#directoryconfigtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeentitlementsrequestrequesttypedef"></a>

## DescribeEntitlementsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeEntitlementsRequestRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `Name`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="describeentitlementsresulttypedef"></a>

## DescribeEntitlementsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeEntitlementsResultTypeDef
```

Required fields:

- `Entitlements`:
  `List`\[[EntitlementTypeDef](./type_defs.md#entitlementtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describefleetsrequestrequesttypedef"></a>

## DescribeFleetsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeFleetsRequestRequestTypeDef
```

Optional fields:

- `Names`: `Sequence`\[`str`\]
- `NextToken`: `str`

<a id="describefleetsresulttypedef"></a>

## DescribeFleetsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeFleetsResultTypeDef
```

Required fields:

- `Fleets`: `List`\[[FleetTypeDef](./type_defs.md#fleettypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeimagebuildersrequestrequesttypedef"></a>

## DescribeImageBuildersRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeImageBuildersRequestRequestTypeDef
```

Optional fields:

- `Names`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describeimagebuildersresulttypedef"></a>

## DescribeImageBuildersResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeImageBuildersResultTypeDef
```

Required fields:

- `ImageBuilders`:
  `List`\[[ImageBuilderTypeDef](./type_defs.md#imagebuildertypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeimagepermissionsrequestrequesttypedef"></a>

## DescribeImagePermissionsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeImagePermissionsRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `MaxResults`: `int`
- `SharedAwsAccountIds`: `Sequence`\[`str`\]
- `NextToken`: `str`

<a id="describeimagepermissionsresulttypedef"></a>

## DescribeImagePermissionsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeImagePermissionsResultTypeDef
```

Required fields:

- `Name`: `str`
- `SharedImagePermissionsList`:
  `List`\[[SharedImagePermissionsTypeDef](./type_defs.md#sharedimagepermissionstypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeimagesrequestrequesttypedef"></a>

## DescribeImagesRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeImagesRequestRequestTypeDef
```

Optional fields:

- `Names`: `Sequence`\[`str`\]
- `Arns`: `Sequence`\[`str`\]
- `Type`: [VisibilityTypeType](./literals.md#visibilitytypetype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="describeimagesresulttypedef"></a>

## DescribeImagesResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeImagesResultTypeDef
```

Required fields:

- `Images`: `List`\[[ImageTypeDef](./type_defs.md#imagetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describesessionsrequestrequesttypedef"></a>

## DescribeSessionsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeSessionsRequestRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `FleetName`: `str`

Optional fields:

- `UserId`: `str`
- `NextToken`: `str`
- `Limit`: `int`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

<a id="describesessionsresulttypedef"></a>

## DescribeSessionsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeSessionsResultTypeDef
```

Required fields:

- `Sessions`: `List`\[[SessionTypeDef](./type_defs.md#sessiontypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestacksrequestrequesttypedef"></a>

## DescribeStacksRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeStacksRequestRequestTypeDef
```

Optional fields:

- `Names`: `Sequence`\[`str`\]
- `NextToken`: `str`

<a id="describestacksresulttypedef"></a>

## DescribeStacksResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeStacksResultTypeDef
```

Required fields:

- `Stacks`: `List`\[[StackTypeDef](./type_defs.md#stacktypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeusagereportsubscriptionsrequestrequesttypedef"></a>

## DescribeUsageReportSubscriptionsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeUsageReportSubscriptionsRequestRequestTypeDef
```

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describeusagereportsubscriptionsresulttypedef"></a>

## DescribeUsageReportSubscriptionsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeUsageReportSubscriptionsResultTypeDef
```

Required fields:

- `UsageReportSubscriptions`:
  `List`\[[UsageReportSubscriptionTypeDef](./type_defs.md#usagereportsubscriptiontypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeuserstackassociationsrequestrequesttypedef"></a>

## DescribeUserStackAssociationsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeUserStackAssociationsRequestRequestTypeDef
```

Optional fields:

- `StackName`: `str`
- `UserName`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describeuserstackassociationsresulttypedef"></a>

## DescribeUserStackAssociationsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeUserStackAssociationsResultTypeDef
```

Required fields:

- `UserStackAssociations`:
  `List`\[[UserStackAssociationTypeDef](./type_defs.md#userstackassociationtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeusersrequestrequesttypedef"></a>

## DescribeUsersRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeUsersRequestRequestTypeDef
```

Required fields:

- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`

<a id="describeusersresulttypedef"></a>

## DescribeUsersResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import DescribeUsersResultTypeDef
```

Required fields:

- `Users`: `List`\[[UserTypeDef](./type_defs.md#usertypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="directoryconfigtypedef"></a>

## DirectoryConfigTypeDef

```python
from types_aiobotocore_appstream.type_defs import DirectoryConfigTypeDef
```

Required fields:

- `DirectoryName`: `str`

Optional fields:

- `OrganizationalUnitDistinguishedNames`: `List`\[`str`\]
- `ServiceAccountCredentials`:
  [ServiceAccountCredentialsTypeDef](./type_defs.md#serviceaccountcredentialstypedef)
- `CreatedTime`: `datetime`

<a id="disableuserrequestrequesttypedef"></a>

## DisableUserRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DisableUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

<a id="disassociateapplicationfleetrequestrequesttypedef"></a>

## DisassociateApplicationFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DisassociateApplicationFleetRequestRequestTypeDef
```

Required fields:

- `FleetName`: `str`
- `ApplicationArn`: `str`

<a id="disassociateapplicationfromentitlementrequestrequesttypedef"></a>

## DisassociateApplicationFromEntitlementRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DisassociateApplicationFromEntitlementRequestRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `EntitlementName`: `str`
- `ApplicationIdentifier`: `str`

<a id="disassociatefleetrequestrequesttypedef"></a>

## DisassociateFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import DisassociateFleetRequestRequestTypeDef
```

Required fields:

- `FleetName`: `str`
- `StackName`: `str`

<a id="domainjoininfotypedef"></a>

## DomainJoinInfoTypeDef

```python
from types_aiobotocore_appstream.type_defs import DomainJoinInfoTypeDef
```

Optional fields:

- `DirectoryName`: `str`
- `OrganizationalUnitDistinguishedName`: `str`

<a id="enableuserrequestrequesttypedef"></a>

## EnableUserRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import EnableUserRequestRequestTypeDef
```

Required fields:

- `UserName`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

<a id="entitledapplicationtypedef"></a>

## EntitledApplicationTypeDef

```python
from types_aiobotocore_appstream.type_defs import EntitledApplicationTypeDef
```

Required fields:

- `ApplicationIdentifier`: `str`

<a id="entitlementattributetypedef"></a>

## EntitlementAttributeTypeDef

```python
from types_aiobotocore_appstream.type_defs import EntitlementAttributeTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

<a id="entitlementtypedef"></a>

## EntitlementTypeDef

```python
from types_aiobotocore_appstream.type_defs import EntitlementTypeDef
```

Required fields:

- `Name`: `str`
- `StackName`: `str`
- `AppVisibility`: [AppVisibilityType](./literals.md#appvisibilitytype)
- `Attributes`:
  `List`\[[EntitlementAttributeTypeDef](./type_defs.md#entitlementattributetypedef)\]

Optional fields:

- `Description`: `str`
- `CreatedTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="expiresessionrequestrequesttypedef"></a>

## ExpireSessionRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import ExpireSessionRequestRequestTypeDef
```

Required fields:

- `SessionId`: `str`

<a id="fleeterrortypedef"></a>

## FleetErrorTypeDef

```python
from types_aiobotocore_appstream.type_defs import FleetErrorTypeDef
```

Optional fields:

- `ErrorCode`: [FleetErrorCodeType](./literals.md#fleeterrorcodetype)
- `ErrorMessage`: `str`

<a id="fleettypedef"></a>

## FleetTypeDef

```python
from types_aiobotocore_appstream.type_defs import FleetTypeDef
```

Required fields:

- `Arn`: `str`
- `Name`: `str`
- `InstanceType`: `str`
- `ComputeCapacityStatus`:
  [ComputeCapacityStatusTypeDef](./type_defs.md#computecapacitystatustypedef)
- `State`: [FleetStateType](./literals.md#fleetstatetype)

Optional fields:

- `DisplayName`: `str`
- `Description`: `str`
- `ImageName`: `str`
- `ImageArn`: `str`
- `FleetType`: [FleetTypeType](./literals.md#fleettypetype)
- `MaxUserDurationInSeconds`: `int`
- `DisconnectTimeoutInSeconds`: `int`
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `CreatedTime`: `datetime`
- `FleetErrors`:
  `List`\[[FleetErrorTypeDef](./type_defs.md#fleeterrortypedef)\]
- `EnableDefaultInternetAccess`: `bool`
- `DomainJoinInfo`:
  [DomainJoinInfoTypeDef](./type_defs.md#domainjoininfotypedef)
- `IdleDisconnectTimeoutInSeconds`: `int`
- `IamRoleArn`: `str`
- `StreamView`: [StreamViewType](./literals.md#streamviewtype)
- `Platform`: [PlatformTypeType](./literals.md#platformtypetype)
- `MaxConcurrentSessions`: `int`
- `UsbDeviceFilterStrings`: `List`\[`str`\]

<a id="imagebuilderstatechangereasontypedef"></a>

## ImageBuilderStateChangeReasonTypeDef

```python
from types_aiobotocore_appstream.type_defs import ImageBuilderStateChangeReasonTypeDef
```

Optional fields:

- `Code`:
  [ImageBuilderStateChangeReasonCodeType](./literals.md#imagebuilderstatechangereasoncodetype)
- `Message`: `str`

<a id="imagebuildertypedef"></a>

## ImageBuilderTypeDef

```python
from types_aiobotocore_appstream.type_defs import ImageBuilderTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Arn`: `str`
- `ImageArn`: `str`
- `Description`: `str`
- `DisplayName`: `str`
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `InstanceType`: `str`
- `Platform`: [PlatformTypeType](./literals.md#platformtypetype)
- `IamRoleArn`: `str`
- `State`: [ImageBuilderStateType](./literals.md#imagebuilderstatetype)
- `StateChangeReason`:
  [ImageBuilderStateChangeReasonTypeDef](./type_defs.md#imagebuilderstatechangereasontypedef)
- `CreatedTime`: `datetime`
- `EnableDefaultInternetAccess`: `bool`
- `DomainJoinInfo`:
  [DomainJoinInfoTypeDef](./type_defs.md#domainjoininfotypedef)
- `NetworkAccessConfiguration`:
  [NetworkAccessConfigurationTypeDef](./type_defs.md#networkaccessconfigurationtypedef)
- `ImageBuilderErrors`:
  `List`\[[ResourceErrorTypeDef](./type_defs.md#resourceerrortypedef)\]
- `AppstreamAgentVersion`: `str`
- `AccessEndpoints`:
  `List`\[[AccessEndpointTypeDef](./type_defs.md#accessendpointtypedef)\]

<a id="imagepermissionstypedef"></a>

## ImagePermissionsTypeDef

```python
from types_aiobotocore_appstream.type_defs import ImagePermissionsTypeDef
```

Optional fields:

- `allowFleet`: `bool`
- `allowImageBuilder`: `bool`

<a id="imagestatechangereasontypedef"></a>

## ImageStateChangeReasonTypeDef

```python
from types_aiobotocore_appstream.type_defs import ImageStateChangeReasonTypeDef
```

Optional fields:

- `Code`:
  [ImageStateChangeReasonCodeType](./literals.md#imagestatechangereasoncodetype)
- `Message`: `str`

<a id="imagetypedef"></a>

## ImageTypeDef

```python
from types_aiobotocore_appstream.type_defs import ImageTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Arn`: `str`
- `BaseImageArn`: `str`
- `DisplayName`: `str`
- `State`: [ImageStateType](./literals.md#imagestatetype)
- `Visibility`: [VisibilityTypeType](./literals.md#visibilitytypetype)
- `ImageBuilderSupported`: `bool`
- `ImageBuilderName`: `str`
- `Platform`: [PlatformTypeType](./literals.md#platformtypetype)
- `Description`: `str`
- `StateChangeReason`:
  [ImageStateChangeReasonTypeDef](./type_defs.md#imagestatechangereasontypedef)
- `Applications`:
  `List`\[[ApplicationTypeDef](./type_defs.md#applicationtypedef)\]
- `CreatedTime`: `datetime`
- `PublicBaseImageReleasedDate`: `datetime`
- `AppstreamAgentVersion`: `str`
- `ImagePermissions`:
  [ImagePermissionsTypeDef](./type_defs.md#imagepermissionstypedef)
- `ImageErrors`:
  `List`\[[ResourceErrorTypeDef](./type_defs.md#resourceerrortypedef)\]

<a id="lastreportgenerationexecutionerrortypedef"></a>

## LastReportGenerationExecutionErrorTypeDef

```python
from types_aiobotocore_appstream.type_defs import LastReportGenerationExecutionErrorTypeDef
```

Optional fields:

- `ErrorCode`:
  [UsageReportExecutionErrorCodeType](./literals.md#usagereportexecutionerrorcodetype)
- `ErrorMessage`: `str`

<a id="listassociatedfleetsrequestrequesttypedef"></a>

## ListAssociatedFleetsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListAssociatedFleetsRequestRequestTypeDef
```

Required fields:

- `StackName`: `str`

Optional fields:

- `NextToken`: `str`

<a id="listassociatedfleetsresulttypedef"></a>

## ListAssociatedFleetsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListAssociatedFleetsResultTypeDef
```

Required fields:

- `Names`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listassociatedstacksrequestrequesttypedef"></a>

## ListAssociatedStacksRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListAssociatedStacksRequestRequestTypeDef
```

Required fields:

- `FleetName`: `str`

Optional fields:

- `NextToken`: `str`

<a id="listassociatedstacksresulttypedef"></a>

## ListAssociatedStacksResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListAssociatedStacksResultTypeDef
```

Required fields:

- `Names`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listentitledapplicationsrequestrequesttypedef"></a>

## ListEntitledApplicationsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListEntitledApplicationsRequestRequestTypeDef
```

Required fields:

- `StackName`: `str`
- `EntitlementName`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listentitledapplicationsresulttypedef"></a>

## ListEntitledApplicationsResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListEntitledApplicationsResultTypeDef
```

Required fields:

- `EntitledApplications`:
  `List`\[[EntitledApplicationTypeDef](./type_defs.md#entitledapplicationtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_appstream.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="networkaccessconfigurationtypedef"></a>

## NetworkAccessConfigurationTypeDef

```python
from types_aiobotocore_appstream.type_defs import NetworkAccessConfigurationTypeDef
```

Optional fields:

- `EniPrivateIpAddress`: `str`
- `EniId`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_appstream.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="resourceerrortypedef"></a>

## ResourceErrorTypeDef

```python
from types_aiobotocore_appstream.type_defs import ResourceErrorTypeDef
```

Optional fields:

- `ErrorCode`: [FleetErrorCodeType](./literals.md#fleeterrorcodetype)
- `ErrorMessage`: `str`
- `ErrorTimestamp`: `datetime`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_appstream.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3locationtypedef"></a>

## S3LocationTypeDef

```python
from types_aiobotocore_appstream.type_defs import S3LocationTypeDef
```

Required fields:

- `S3Bucket`: `str`
- `S3Key`: `str`

<a id="scriptdetailstypedef"></a>

## ScriptDetailsTypeDef

```python
from types_aiobotocore_appstream.type_defs import ScriptDetailsTypeDef
```

Required fields:

- `ScriptS3Location`: [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- `ExecutablePath`: `str`
- `TimeoutInSeconds`: `int`

Optional fields:

- `ExecutableParameters`: `str`

<a id="serviceaccountcredentialstypedef"></a>

## ServiceAccountCredentialsTypeDef

```python
from types_aiobotocore_appstream.type_defs import ServiceAccountCredentialsTypeDef
```

Required fields:

- `AccountName`: `str`
- `AccountPassword`: `str`

<a id="sessiontypedef"></a>

## SessionTypeDef

```python
from types_aiobotocore_appstream.type_defs import SessionTypeDef
```

Required fields:

- `Id`: `str`
- `UserId`: `str`
- `StackName`: `str`
- `FleetName`: `str`
- `State`: [SessionStateType](./literals.md#sessionstatetype)

Optional fields:

- `ConnectionState`:
  [SessionConnectionStateType](./literals.md#sessionconnectionstatetype)
- `StartTime`: `datetime`
- `MaxExpirationTime`: `datetime`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)
- `NetworkAccessConfiguration`:
  [NetworkAccessConfigurationTypeDef](./type_defs.md#networkaccessconfigurationtypedef)

<a id="sharedimagepermissionstypedef"></a>

## SharedImagePermissionsTypeDef

```python
from types_aiobotocore_appstream.type_defs import SharedImagePermissionsTypeDef
```

Required fields:

- `sharedAccountId`: `str`
- `imagePermissions`:
  [ImagePermissionsTypeDef](./type_defs.md#imagepermissionstypedef)

<a id="stackerrortypedef"></a>

## StackErrorTypeDef

```python
from types_aiobotocore_appstream.type_defs import StackErrorTypeDef
```

Optional fields:

- `ErrorCode`: [StackErrorCodeType](./literals.md#stackerrorcodetype)
- `ErrorMessage`: `str`

<a id="stacktypedef"></a>

## StackTypeDef

```python
from types_aiobotocore_appstream.type_defs import StackTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Arn`: `str`
- `Description`: `str`
- `DisplayName`: `str`
- `CreatedTime`: `datetime`
- `StorageConnectors`:
  `List`\[[StorageConnectorTypeDef](./type_defs.md#storageconnectortypedef)\]
- `RedirectURL`: `str`
- `FeedbackURL`: `str`
- `StackErrors`:
  `List`\[[StackErrorTypeDef](./type_defs.md#stackerrortypedef)\]
- `UserSettings`:
  `List`\[[UserSettingTypeDef](./type_defs.md#usersettingtypedef)\]
- `ApplicationSettings`:
  [ApplicationSettingsResponseTypeDef](./type_defs.md#applicationsettingsresponsetypedef)
- `AccessEndpoints`:
  `List`\[[AccessEndpointTypeDef](./type_defs.md#accessendpointtypedef)\]
- `EmbedHostDomains`: `List`\[`str`\]

<a id="startfleetrequestrequesttypedef"></a>

## StartFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import StartFleetRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="startimagebuilderrequestrequesttypedef"></a>

## StartImageBuilderRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import StartImageBuilderRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `AppstreamAgentVersion`: `str`

<a id="startimagebuilderresulttypedef"></a>

## StartImageBuilderResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import StartImageBuilderResultTypeDef
```

Required fields:

- `ImageBuilder`: [ImageBuilderTypeDef](./type_defs.md#imagebuildertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopfleetrequestrequesttypedef"></a>

## StopFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import StopFleetRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="stopimagebuilderrequestrequesttypedef"></a>

## StopImageBuilderRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import StopImageBuilderRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

<a id="stopimagebuilderresulttypedef"></a>

## StopImageBuilderResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import StopImageBuilderResultTypeDef
```

Required fields:

- `ImageBuilder`: [ImageBuilderTypeDef](./type_defs.md#imagebuildertypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="storageconnectortypedef"></a>

## StorageConnectorTypeDef

```python
from types_aiobotocore_appstream.type_defs import StorageConnectorTypeDef
```

Required fields:

- `ConnectorType`:
  [StorageConnectorTypeType](./literals.md#storageconnectortypetype)

Optional fields:

- `ResourceIdentifier`: `str`
- `Domains`: `Sequence`\[`str`\]

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updateapplicationrequestrequesttypedef"></a>

## UpdateApplicationRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateApplicationRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `DisplayName`: `str`
- `Description`: `str`
- `IconS3Location`: [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- `LaunchPath`: `str`
- `WorkingDirectory`: `str`
- `LaunchParameters`: `str`
- `AppBlockArn`: `str`
- `AttributesToDelete`:
  `Sequence`\[[ApplicationAttributeType](./literals.md#applicationattributetype)\]

<a id="updateapplicationresulttypedef"></a>

## UpdateApplicationResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateApplicationResultTypeDef
```

Required fields:

- `Application`: [ApplicationTypeDef](./type_defs.md#applicationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatedirectoryconfigrequestrequesttypedef"></a>

## UpdateDirectoryConfigRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateDirectoryConfigRequestRequestTypeDef
```

Required fields:

- `DirectoryName`: `str`

Optional fields:

- `OrganizationalUnitDistinguishedNames`: `Sequence`\[`str`\]
- `ServiceAccountCredentials`:
  [ServiceAccountCredentialsTypeDef](./type_defs.md#serviceaccountcredentialstypedef)

<a id="updatedirectoryconfigresulttypedef"></a>

## UpdateDirectoryConfigResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateDirectoryConfigResultTypeDef
```

Required fields:

- `DirectoryConfig`:
  [DirectoryConfigTypeDef](./type_defs.md#directoryconfigtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateentitlementrequestrequesttypedef"></a>

## UpdateEntitlementRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateEntitlementRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `StackName`: `str`

Optional fields:

- `Description`: `str`
- `AppVisibility`: [AppVisibilityType](./literals.md#appvisibilitytype)
- `Attributes`:
  `Sequence`\[[EntitlementAttributeTypeDef](./type_defs.md#entitlementattributetypedef)\]

<a id="updateentitlementresulttypedef"></a>

## UpdateEntitlementResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateEntitlementResultTypeDef
```

Required fields:

- `Entitlement`: [EntitlementTypeDef](./type_defs.md#entitlementtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatefleetrequestrequesttypedef"></a>

## UpdateFleetRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateFleetRequestRequestTypeDef
```

Optional fields:

- `ImageName`: `str`
- `ImageArn`: `str`
- `Name`: `str`
- `InstanceType`: `str`
- `ComputeCapacity`:
  [ComputeCapacityTypeDef](./type_defs.md#computecapacitytypedef)
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `MaxUserDurationInSeconds`: `int`
- `DisconnectTimeoutInSeconds`: `int`
- `DeleteVpcConfig`: `bool`
- `Description`: `str`
- `DisplayName`: `str`
- `EnableDefaultInternetAccess`: `bool`
- `DomainJoinInfo`:
  [DomainJoinInfoTypeDef](./type_defs.md#domainjoininfotypedef)
- `IdleDisconnectTimeoutInSeconds`: `int`
- `AttributesToDelete`:
  `Sequence`\[[FleetAttributeType](./literals.md#fleetattributetype)\]
- `IamRoleArn`: `str`
- `StreamView`: [StreamViewType](./literals.md#streamviewtype)
- `Platform`: [PlatformTypeType](./literals.md#platformtypetype)
- `MaxConcurrentSessions`: `int`
- `UsbDeviceFilterStrings`: `Sequence`\[`str`\]

<a id="updatefleetresulttypedef"></a>

## UpdateFleetResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateFleetResultTypeDef
```

Required fields:

- `Fleet`: [FleetTypeDef](./type_defs.md#fleettypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateimagepermissionsrequestrequesttypedef"></a>

## UpdateImagePermissionsRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateImagePermissionsRequestRequestTypeDef
```

Required fields:

- `Name`: `str`
- `SharedAccountId`: `str`
- `ImagePermissions`:
  [ImagePermissionsTypeDef](./type_defs.md#imagepermissionstypedef)

<a id="updatestackrequestrequesttypedef"></a>

## UpdateStackRequestRequestTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateStackRequestRequestTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `DisplayName`: `str`
- `Description`: `str`
- `StorageConnectors`:
  `Sequence`\[[StorageConnectorTypeDef](./type_defs.md#storageconnectortypedef)\]
- `DeleteStorageConnectors`: `bool`
- `RedirectURL`: `str`
- `FeedbackURL`: `str`
- `AttributesToDelete`:
  `Sequence`\[[StackAttributeType](./literals.md#stackattributetype)\]
- `UserSettings`:
  `Sequence`\[[UserSettingTypeDef](./type_defs.md#usersettingtypedef)\]
- `ApplicationSettings`:
  [ApplicationSettingsTypeDef](./type_defs.md#applicationsettingstypedef)
- `AccessEndpoints`:
  `Sequence`\[[AccessEndpointTypeDef](./type_defs.md#accessendpointtypedef)\]
- `EmbedHostDomains`: `Sequence`\[`str`\]

<a id="updatestackresulttypedef"></a>

## UpdateStackResultTypeDef

```python
from types_aiobotocore_appstream.type_defs import UpdateStackResultTypeDef
```

Required fields:

- `Stack`: [StackTypeDef](./type_defs.md#stacktypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="usagereportsubscriptiontypedef"></a>

## UsageReportSubscriptionTypeDef

```python
from types_aiobotocore_appstream.type_defs import UsageReportSubscriptionTypeDef
```

Optional fields:

- `S3BucketName`: `str`
- `Schedule`: `Literal['DAILY']` (see
  [UsageReportScheduleType](./literals.md#usagereportscheduletype))
- `LastGeneratedReportDate`: `datetime`
- `SubscriptionErrors`:
  `List`\[[LastReportGenerationExecutionErrorTypeDef](./type_defs.md#lastreportgenerationexecutionerrortypedef)\]

<a id="usersettingtypedef"></a>

## UserSettingTypeDef

```python
from types_aiobotocore_appstream.type_defs import UserSettingTypeDef
```

Required fields:

- `Action`: [ActionType](./literals.md#actiontype)
- `Permission`: [PermissionType](./literals.md#permissiontype)

<a id="userstackassociationerrortypedef"></a>

## UserStackAssociationErrorTypeDef

```python
from types_aiobotocore_appstream.type_defs import UserStackAssociationErrorTypeDef
```

Optional fields:

- `UserStackAssociation`:
  [UserStackAssociationTypeDef](./type_defs.md#userstackassociationtypedef)
- `ErrorCode`:
  [UserStackAssociationErrorCodeType](./literals.md#userstackassociationerrorcodetype)
- `ErrorMessage`: `str`

<a id="userstackassociationtypedef"></a>

## UserStackAssociationTypeDef

```python
from types_aiobotocore_appstream.type_defs import UserStackAssociationTypeDef
```

Required fields:

- `StackName`: `str`
- `UserName`: `str`
- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

Optional fields:

- `SendEmailNotification`: `bool`

<a id="usertypedef"></a>

## UserTypeDef

```python
from types_aiobotocore_appstream.type_defs import UserTypeDef
```

Required fields:

- `AuthenticationType`:
  [AuthenticationTypeType](./literals.md#authenticationtypetype)

Optional fields:

- `Arn`: `str`
- `UserName`: `str`
- `Enabled`: `bool`
- `Status`: `str`
- `FirstName`: `str`
- `LastName`: `str`
- `CreatedTime`: `datetime`

<a id="vpcconfigtypedef"></a>

## VpcConfigTypeDef

```python
from types_aiobotocore_appstream.type_defs import VpcConfigTypeDef
```

Optional fields:

- `SubnetIds`: `Sequence`\[`str`\]
- `SecurityGroupIds`: `Sequence`\[`str`\]

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_appstream.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`
