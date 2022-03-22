<a id="typed-dictionaries-for-aiobotocore-fms-module"></a>

# Typed dictionaries for aiobotocore FMS module

> [Index](../README.md) > [FMS](./README.md) > Typed dictionaries

Auto-generated documentation for
[FMS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
type annotations stubs module
[types-aiobotocore-fms](https://pypi.org/project/types-aiobotocore-fms/).

- [Typed dictionaries for aiobotocore FMS module](#typed-dictionaries-for-aiobotocore-fms-module)
  - [ActionTargetTypeDef](#actiontargettypedef)
  - [AppTypeDef](#apptypedef)
  - [AppsListDataSummaryTypeDef](#appslistdatasummarytypedef)
  - [AppsListDataTypeDef](#appslistdatatypedef)
  - [AssociateAdminAccountRequestRequestTypeDef](#associateadminaccountrequestrequesttypedef)
  - [AwsEc2InstanceViolationTypeDef](#awsec2instanceviolationtypedef)
  - [AwsEc2NetworkInterfaceViolationTypeDef](#awsec2networkinterfaceviolationtypedef)
  - [AwsVPCSecurityGroupViolationTypeDef](#awsvpcsecuritygroupviolationtypedef)
  - [ComplianceViolatorTypeDef](#complianceviolatortypedef)
  - [DeleteAppsListRequestRequestTypeDef](#deleteappslistrequestrequesttypedef)
  - [DeletePolicyRequestRequestTypeDef](#deletepolicyrequestrequesttypedef)
  - [DeleteProtocolsListRequestRequestTypeDef](#deleteprotocolslistrequestrequesttypedef)
  - [DnsDuplicateRuleGroupViolationTypeDef](#dnsduplicaterulegroupviolationtypedef)
  - [DnsRuleGroupLimitExceededViolationTypeDef](#dnsrulegrouplimitexceededviolationtypedef)
  - [DnsRuleGroupPriorityConflictViolationTypeDef](#dnsrulegrouppriorityconflictviolationtypedef)
  - [EC2AssociateRouteTableActionTypeDef](#ec2associateroutetableactiontypedef)
  - [EC2CopyRouteTableActionTypeDef](#ec2copyroutetableactiontypedef)
  - [EC2CreateRouteActionTypeDef](#ec2createrouteactiontypedef)
  - [EC2CreateRouteTableActionTypeDef](#ec2createroutetableactiontypedef)
  - [EC2DeleteRouteActionTypeDef](#ec2deleterouteactiontypedef)
  - [EC2ReplaceRouteActionTypeDef](#ec2replacerouteactiontypedef)
  - [EC2ReplaceRouteTableAssociationActionTypeDef](#ec2replaceroutetableassociationactiontypedef)
  - [EvaluationResultTypeDef](#evaluationresulttypedef)
  - [ExpectedRouteTypeDef](#expectedroutetypedef)
  - [FMSPolicyUpdateFirewallCreationConfigActionTypeDef](#fmspolicyupdatefirewallcreationconfigactiontypedef)
  - [FirewallSubnetIsOutOfScopeViolationTypeDef](#firewallsubnetisoutofscopeviolationtypedef)
  - [GetAdminAccountResponseTypeDef](#getadminaccountresponsetypedef)
  - [GetAppsListRequestRequestTypeDef](#getappslistrequestrequesttypedef)
  - [GetAppsListResponseTypeDef](#getappslistresponsetypedef)
  - [GetComplianceDetailRequestRequestTypeDef](#getcompliancedetailrequestrequesttypedef)
  - [GetComplianceDetailResponseTypeDef](#getcompliancedetailresponsetypedef)
  - [GetNotificationChannelResponseTypeDef](#getnotificationchannelresponsetypedef)
  - [GetPolicyRequestRequestTypeDef](#getpolicyrequestrequesttypedef)
  - [GetPolicyResponseTypeDef](#getpolicyresponsetypedef)
  - [GetProtectionStatusRequestRequestTypeDef](#getprotectionstatusrequestrequesttypedef)
  - [GetProtectionStatusResponseTypeDef](#getprotectionstatusresponsetypedef)
  - [GetProtocolsListRequestRequestTypeDef](#getprotocolslistrequestrequesttypedef)
  - [GetProtocolsListResponseTypeDef](#getprotocolslistresponsetypedef)
  - [GetViolationDetailsRequestRequestTypeDef](#getviolationdetailsrequestrequesttypedef)
  - [GetViolationDetailsResponseTypeDef](#getviolationdetailsresponsetypedef)
  - [ListAppsListsRequestRequestTypeDef](#listappslistsrequestrequesttypedef)
  - [ListAppsListsResponseTypeDef](#listappslistsresponsetypedef)
  - [ListComplianceStatusRequestRequestTypeDef](#listcompliancestatusrequestrequesttypedef)
  - [ListComplianceStatusResponseTypeDef](#listcompliancestatusresponsetypedef)
  - [ListMemberAccountsRequestRequestTypeDef](#listmemberaccountsrequestrequesttypedef)
  - [ListMemberAccountsResponseTypeDef](#listmemberaccountsresponsetypedef)
  - [ListPoliciesRequestRequestTypeDef](#listpoliciesrequestrequesttypedef)
  - [ListPoliciesResponseTypeDef](#listpoliciesresponsetypedef)
  - [ListProtocolsListsRequestRequestTypeDef](#listprotocolslistsrequestrequesttypedef)
  - [ListProtocolsListsResponseTypeDef](#listprotocolslistsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [NetworkFirewallBlackHoleRouteDetectedViolationTypeDef](#networkfirewallblackholeroutedetectedviolationtypedef)
  - [NetworkFirewallInternetTrafficNotInspectedViolationTypeDef](#networkfirewallinternettrafficnotinspectedviolationtypedef)
  - [NetworkFirewallInvalidRouteConfigurationViolationTypeDef](#networkfirewallinvalidrouteconfigurationviolationtypedef)
  - [NetworkFirewallMissingExpectedRTViolationTypeDef](#networkfirewallmissingexpectedrtviolationtypedef)
  - [NetworkFirewallMissingExpectedRoutesViolationTypeDef](#networkfirewallmissingexpectedroutesviolationtypedef)
  - [NetworkFirewallMissingFirewallViolationTypeDef](#networkfirewallmissingfirewallviolationtypedef)
  - [NetworkFirewallMissingSubnetViolationTypeDef](#networkfirewallmissingsubnetviolationtypedef)
  - [NetworkFirewallPolicyDescriptionTypeDef](#networkfirewallpolicydescriptiontypedef)
  - [NetworkFirewallPolicyModifiedViolationTypeDef](#networkfirewallpolicymodifiedviolationtypedef)
  - [NetworkFirewallPolicyTypeDef](#networkfirewallpolicytypedef)
  - [NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef](#networkfirewallunexpectedfirewallroutesviolationtypedef)
  - [NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef](#networkfirewallunexpectedgatewayroutesviolationtypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PartialMatchTypeDef](#partialmatchtypedef)
  - [PolicyComplianceDetailTypeDef](#policycompliancedetailtypedef)
  - [PolicyComplianceStatusTypeDef](#policycompliancestatustypedef)
  - [PolicyOptionTypeDef](#policyoptiontypedef)
  - [PolicySummaryTypeDef](#policysummarytypedef)
  - [PolicyTypeDef](#policytypedef)
  - [PossibleRemediationActionTypeDef](#possibleremediationactiontypedef)
  - [PossibleRemediationActionsTypeDef](#possibleremediationactionstypedef)
  - [ProtocolsListDataSummaryTypeDef](#protocolslistdatasummarytypedef)
  - [ProtocolsListDataTypeDef](#protocolslistdatatypedef)
  - [PutAppsListRequestRequestTypeDef](#putappslistrequestrequesttypedef)
  - [PutAppsListResponseTypeDef](#putappslistresponsetypedef)
  - [PutNotificationChannelRequestRequestTypeDef](#putnotificationchannelrequestrequesttypedef)
  - [PutPolicyRequestRequestTypeDef](#putpolicyrequestrequesttypedef)
  - [PutPolicyResponseTypeDef](#putpolicyresponsetypedef)
  - [PutProtocolsListRequestRequestTypeDef](#putprotocolslistrequestrequesttypedef)
  - [PutProtocolsListResponseTypeDef](#putprotocolslistresponsetypedef)
  - [RemediationActionTypeDef](#remediationactiontypedef)
  - [RemediationActionWithOrderTypeDef](#remediationactionwithordertypedef)
  - [ResourceTagTypeDef](#resourcetagtypedef)
  - [ResourceViolationTypeDef](#resourceviolationtypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RouteHasOutOfScopeEndpointViolationTypeDef](#routehasoutofscopeendpointviolationtypedef)
  - [RouteTypeDef](#routetypedef)
  - [SecurityGroupRemediationActionTypeDef](#securitygroupremediationactiontypedef)
  - [SecurityGroupRuleDescriptionTypeDef](#securitygroupruledescriptiontypedef)
  - [SecurityServicePolicyDataTypeDef](#securityservicepolicydatatypedef)
  - [StatefulRuleGroupTypeDef](#statefulrulegrouptypedef)
  - [StatelessRuleGroupTypeDef](#statelessrulegrouptypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [ViolationDetailTypeDef](#violationdetailtypedef)

<a id="actiontargettypedef"></a>

## ActionTargetTypeDef

```python
from types_aiobotocore_fms.type_defs import ActionTargetTypeDef
```

Optional fields:

- `ResourceId`: `str`
- `Description`: `str`

<a id="apptypedef"></a>

## AppTypeDef

```python
from types_aiobotocore_fms.type_defs import AppTypeDef
```

Required fields:

- `AppName`: `str`
- `Protocol`: `str`
- `Port`: `int`

<a id="appslistdatasummarytypedef"></a>

## AppsListDataSummaryTypeDef

```python
from types_aiobotocore_fms.type_defs import AppsListDataSummaryTypeDef
```

Optional fields:

- `ListArn`: `str`
- `ListId`: `str`
- `ListName`: `str`
- `AppsList`: `List`\[[AppTypeDef](./type_defs.md#apptypedef)\]

<a id="appslistdatatypedef"></a>

## AppsListDataTypeDef

```python
from types_aiobotocore_fms.type_defs import AppsListDataTypeDef
```

Required fields:

- `ListName`: `str`
- `AppsList`: `List`\[[AppTypeDef](./type_defs.md#apptypedef)\]

Optional fields:

- `ListId`: `str`
- `ListUpdateToken`: `str`
- `CreateTime`: `datetime`
- `LastUpdateTime`: `datetime`
- `PreviousAppsList`: `Dict`\[`str`,
  `List`\[[AppTypeDef](./type_defs.md#apptypedef)\]\]

<a id="associateadminaccountrequestrequesttypedef"></a>

## AssociateAdminAccountRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import AssociateAdminAccountRequestRequestTypeDef
```

Required fields:

- `AdminAccount`: `str`

<a id="awsec2instanceviolationtypedef"></a>

## AwsEc2InstanceViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import AwsEc2InstanceViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `AwsEc2NetworkInterfaceViolations`:
  `List`\[[AwsEc2NetworkInterfaceViolationTypeDef](./type_defs.md#awsec2networkinterfaceviolationtypedef)\]

<a id="awsec2networkinterfaceviolationtypedef"></a>

## AwsEc2NetworkInterfaceViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import AwsEc2NetworkInterfaceViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `ViolatingSecurityGroups`: `List`\[`str`\]

<a id="awsvpcsecuritygroupviolationtypedef"></a>

## AwsVPCSecurityGroupViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import AwsVPCSecurityGroupViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `ViolationTargetDescription`: `str`
- `PartialMatches`:
  `List`\[[PartialMatchTypeDef](./type_defs.md#partialmatchtypedef)\]
- `PossibleSecurityGroupRemediationActions`:
  `List`\[[SecurityGroupRemediationActionTypeDef](./type_defs.md#securitygroupremediationactiontypedef)\]

<a id="complianceviolatortypedef"></a>

## ComplianceViolatorTypeDef

```python
from types_aiobotocore_fms.type_defs import ComplianceViolatorTypeDef
```

Optional fields:

- `ResourceId`: `str`
- `ViolationReason`: [ViolationReasonType](./literals.md#violationreasontype)
- `ResourceType`: `str`
- `Metadata`: `Dict`\[`str`, `str`\]

<a id="deleteappslistrequestrequesttypedef"></a>

## DeleteAppsListRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import DeleteAppsListRequestRequestTypeDef
```

Required fields:

- `ListId`: `str`

<a id="deletepolicyrequestrequesttypedef"></a>

## DeletePolicyRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import DeletePolicyRequestRequestTypeDef
```

Required fields:

- `PolicyId`: `str`

Optional fields:

- `DeleteAllPolicyResources`: `bool`

<a id="deleteprotocolslistrequestrequesttypedef"></a>

## DeleteProtocolsListRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import DeleteProtocolsListRequestRequestTypeDef
```

Required fields:

- `ListId`: `str`

<a id="dnsduplicaterulegroupviolationtypedef"></a>

## DnsDuplicateRuleGroupViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import DnsDuplicateRuleGroupViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `ViolationTargetDescription`: `str`

<a id="dnsrulegrouplimitexceededviolationtypedef"></a>

## DnsRuleGroupLimitExceededViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import DnsRuleGroupLimitExceededViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `ViolationTargetDescription`: `str`
- `NumberOfRuleGroupsAlreadyAssociated`: `int`

<a id="dnsrulegrouppriorityconflictviolationtypedef"></a>

## DnsRuleGroupPriorityConflictViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import DnsRuleGroupPriorityConflictViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `ViolationTargetDescription`: `str`
- `ConflictingPriority`: `int`
- `ConflictingPolicyId`: `str`
- `UnavailablePriorities`: `List`\[`int`\]

<a id="ec2associateroutetableactiontypedef"></a>

## EC2AssociateRouteTableActionTypeDef

```python
from types_aiobotocore_fms.type_defs import EC2AssociateRouteTableActionTypeDef
```

Required fields:

- `RouteTableId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

Optional fields:

- `Description`: `str`
- `SubnetId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)
- `GatewayId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

<a id="ec2copyroutetableactiontypedef"></a>

## EC2CopyRouteTableActionTypeDef

```python
from types_aiobotocore_fms.type_defs import EC2CopyRouteTableActionTypeDef
```

Required fields:

- `VpcId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)
- `RouteTableId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

Optional fields:

- `Description`: `str`

<a id="ec2createrouteactiontypedef"></a>

## EC2CreateRouteActionTypeDef

```python
from types_aiobotocore_fms.type_defs import EC2CreateRouteActionTypeDef
```

Required fields:

- `RouteTableId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

Optional fields:

- `Description`: `str`
- `DestinationCidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DestinationIpv6CidrBlock`: `str`
- `VpcEndpointId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)
- `GatewayId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

<a id="ec2createroutetableactiontypedef"></a>

## EC2CreateRouteTableActionTypeDef

```python
from types_aiobotocore_fms.type_defs import EC2CreateRouteTableActionTypeDef
```

Required fields:

- `VpcId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

Optional fields:

- `Description`: `str`

<a id="ec2deleterouteactiontypedef"></a>

## EC2DeleteRouteActionTypeDef

```python
from types_aiobotocore_fms.type_defs import EC2DeleteRouteActionTypeDef
```

Required fields:

- `RouteTableId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

Optional fields:

- `Description`: `str`
- `DestinationCidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DestinationIpv6CidrBlock`: `str`

<a id="ec2replacerouteactiontypedef"></a>

## EC2ReplaceRouteActionTypeDef

```python
from types_aiobotocore_fms.type_defs import EC2ReplaceRouteActionTypeDef
```

Required fields:

- `RouteTableId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

Optional fields:

- `Description`: `str`
- `DestinationCidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DestinationIpv6CidrBlock`: `str`
- `GatewayId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

<a id="ec2replaceroutetableassociationactiontypedef"></a>

## EC2ReplaceRouteTableAssociationActionTypeDef

```python
from types_aiobotocore_fms.type_defs import EC2ReplaceRouteTableAssociationActionTypeDef
```

Required fields:

- `AssociationId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)
- `RouteTableId`: [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)

Optional fields:

- `Description`: `str`

<a id="evaluationresulttypedef"></a>

## EvaluationResultTypeDef

```python
from types_aiobotocore_fms.type_defs import EvaluationResultTypeDef
```

Optional fields:

- `ComplianceStatus`:
  [PolicyComplianceStatusTypeType](./literals.md#policycompliancestatustypetype)
- `ViolatorCount`: `int`
- `EvaluationLimitExceeded`: `bool`

<a id="expectedroutetypedef"></a>

## ExpectedRouteTypeDef

```python
from types_aiobotocore_fms.type_defs import ExpectedRouteTypeDef
```

Optional fields:

- `IpV4Cidr`: `str`
- `PrefixListId`: `str`
- `IpV6Cidr`: `str`
- `ContributingSubnets`: `List`\[`str`\]
- `AllowedTargets`: `List`\[`str`\]
- `RouteTableId`: `str`

<a id="fmspolicyupdatefirewallcreationconfigactiontypedef"></a>

## FMSPolicyUpdateFirewallCreationConfigActionTypeDef

```python
from types_aiobotocore_fms.type_defs import FMSPolicyUpdateFirewallCreationConfigActionTypeDef
```

Optional fields:

- `Description`: `str`
- `FirewallCreationConfig`: `str`

<a id="firewallsubnetisoutofscopeviolationtypedef"></a>

## FirewallSubnetIsOutOfScopeViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import FirewallSubnetIsOutOfScopeViolationTypeDef
```

Optional fields:

- `FirewallSubnetId`: `str`
- `VpcId`: `str`
- `SubnetAvailabilityZone`: `str`
- `SubnetAvailabilityZoneId`: `str`
- `VpcEndpointId`: `str`

<a id="getadminaccountresponsetypedef"></a>

## GetAdminAccountResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetAdminAccountResponseTypeDef
```

Required fields:

- `AdminAccount`: `str`
- `RoleStatus`: [AccountRoleStatusType](./literals.md#accountrolestatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getappslistrequestrequesttypedef"></a>

## GetAppsListRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import GetAppsListRequestRequestTypeDef
```

Required fields:

- `ListId`: `str`

Optional fields:

- `DefaultList`: `bool`

<a id="getappslistresponsetypedef"></a>

## GetAppsListResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetAppsListResponseTypeDef
```

Required fields:

- `AppsList`: [AppsListDataTypeDef](./type_defs.md#appslistdatatypedef)
- `AppsListArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getcompliancedetailrequestrequesttypedef"></a>

## GetComplianceDetailRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import GetComplianceDetailRequestRequestTypeDef
```

Required fields:

- `PolicyId`: `str`
- `MemberAccount`: `str`

<a id="getcompliancedetailresponsetypedef"></a>

## GetComplianceDetailResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetComplianceDetailResponseTypeDef
```

Required fields:

- `PolicyComplianceDetail`:
  [PolicyComplianceDetailTypeDef](./type_defs.md#policycompliancedetailtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getnotificationchannelresponsetypedef"></a>

## GetNotificationChannelResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetNotificationChannelResponseTypeDef
```

Required fields:

- `SnsTopicArn`: `str`
- `SnsRoleName`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getpolicyrequestrequesttypedef"></a>

## GetPolicyRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import GetPolicyRequestRequestTypeDef
```

Required fields:

- `PolicyId`: `str`

<a id="getpolicyresponsetypedef"></a>

## GetPolicyResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetPolicyResponseTypeDef
```

Required fields:

- `Policy`: [PolicyTypeDef](./type_defs.md#policytypedef)
- `PolicyArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getprotectionstatusrequestrequesttypedef"></a>

## GetProtectionStatusRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import GetProtectionStatusRequestRequestTypeDef
```

Required fields:

- `PolicyId`: `str`

Optional fields:

- `MemberAccountId`: `str`
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="getprotectionstatusresponsetypedef"></a>

## GetProtectionStatusResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetProtectionStatusResponseTypeDef
```

Required fields:

- `AdminAccountId`: `str`
- `ServiceType`:
  [SecurityServiceTypeType](./literals.md#securityservicetypetype)
- `Data`: `str`
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getprotocolslistrequestrequesttypedef"></a>

## GetProtocolsListRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import GetProtocolsListRequestRequestTypeDef
```

Required fields:

- `ListId`: `str`

Optional fields:

- `DefaultList`: `bool`

<a id="getprotocolslistresponsetypedef"></a>

## GetProtocolsListResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetProtocolsListResponseTypeDef
```

Required fields:

- `ProtocolsList`:
  [ProtocolsListDataTypeDef](./type_defs.md#protocolslistdatatypedef)
- `ProtocolsListArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getviolationdetailsrequestrequesttypedef"></a>

## GetViolationDetailsRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import GetViolationDetailsRequestRequestTypeDef
```

Required fields:

- `PolicyId`: `str`
- `MemberAccount`: `str`
- `ResourceId`: `str`
- `ResourceType`: `str`

<a id="getviolationdetailsresponsetypedef"></a>

## GetViolationDetailsResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import GetViolationDetailsResponseTypeDef
```

Required fields:

- `ViolationDetail`:
  [ViolationDetailTypeDef](./type_defs.md#violationdetailtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listappslistsrequestrequesttypedef"></a>

## ListAppsListsRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import ListAppsListsRequestRequestTypeDef
```

Required fields:

- `MaxResults`: `int`

Optional fields:

- `DefaultLists`: `bool`
- `NextToken`: `str`

<a id="listappslistsresponsetypedef"></a>

## ListAppsListsResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import ListAppsListsResponseTypeDef
```

Required fields:

- `AppsLists`:
  `List`\[[AppsListDataSummaryTypeDef](./type_defs.md#appslistdatasummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcompliancestatusrequestrequesttypedef"></a>

## ListComplianceStatusRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import ListComplianceStatusRequestRequestTypeDef
```

Required fields:

- `PolicyId`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listcompliancestatusresponsetypedef"></a>

## ListComplianceStatusResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import ListComplianceStatusResponseTypeDef
```

Required fields:

- `PolicyComplianceStatusList`:
  `List`\[[PolicyComplianceStatusTypeDef](./type_defs.md#policycompliancestatustypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmemberaccountsrequestrequesttypedef"></a>

## ListMemberAccountsRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import ListMemberAccountsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listmemberaccountsresponsetypedef"></a>

## ListMemberAccountsResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import ListMemberAccountsResponseTypeDef
```

Required fields:

- `MemberAccounts`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpoliciesrequestrequesttypedef"></a>

## ListPoliciesRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import ListPoliciesRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listpoliciesresponsetypedef"></a>

## ListPoliciesResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import ListPoliciesResponseTypeDef
```

Required fields:

- `PolicyList`:
  `List`\[[PolicySummaryTypeDef](./type_defs.md#policysummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listprotocolslistsrequestrequesttypedef"></a>

## ListProtocolsListsRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import ListProtocolsListsRequestRequestTypeDef
```

Required fields:

- `MaxResults`: `int`

Optional fields:

- `DefaultLists`: `bool`
- `NextToken`: `str`

<a id="listprotocolslistsresponsetypedef"></a>

## ListProtocolsListsResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import ListProtocolsListsResponseTypeDef
```

Required fields:

- `ProtocolsLists`:
  `List`\[[ProtocolsListDataSummaryTypeDef](./type_defs.md#protocolslistdatasummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `TagList`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="networkfirewallblackholeroutedetectedviolationtypedef"></a>

## NetworkFirewallBlackHoleRouteDetectedViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallBlackHoleRouteDetectedViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `RouteTableId`: `str`
- `VpcId`: `str`
- `ViolatingRoutes`: `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]

<a id="networkfirewallinternettrafficnotinspectedviolationtypedef"></a>

## NetworkFirewallInternetTrafficNotInspectedViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallInternetTrafficNotInspectedViolationTypeDef
```

Optional fields:

- `SubnetId`: `str`
- `SubnetAvailabilityZone`: `str`
- `RouteTableId`: `str`
- `ViolatingRoutes`: `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `IsRouteTableUsedInDifferentAZ`: `bool`
- `CurrentFirewallSubnetRouteTable`: `str`
- `ExpectedFirewallEndpoint`: `str`
- `FirewallSubnetId`: `str`
- `ExpectedFirewallSubnetRoutes`:
  `List`\[[ExpectedRouteTypeDef](./type_defs.md#expectedroutetypedef)\]
- `ActualFirewallSubnetRoutes`:
  `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `InternetGatewayId`: `str`
- `CurrentInternetGatewayRouteTable`: `str`
- `ExpectedInternetGatewayRoutes`:
  `List`\[[ExpectedRouteTypeDef](./type_defs.md#expectedroutetypedef)\]
- `ActualInternetGatewayRoutes`:
  `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `VpcId`: `str`

<a id="networkfirewallinvalidrouteconfigurationviolationtypedef"></a>

## NetworkFirewallInvalidRouteConfigurationViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallInvalidRouteConfigurationViolationTypeDef
```

Optional fields:

- `AffectedSubnets`: `List`\[`str`\]
- `RouteTableId`: `str`
- `IsRouteTableUsedInDifferentAZ`: `bool`
- `ViolatingRoute`: [RouteTypeDef](./type_defs.md#routetypedef)
- `CurrentFirewallSubnetRouteTable`: `str`
- `ExpectedFirewallEndpoint`: `str`
- `ActualFirewallEndpoint`: `str`
- `ExpectedFirewallSubnetId`: `str`
- `ActualFirewallSubnetId`: `str`
- `ExpectedFirewallSubnetRoutes`:
  `List`\[[ExpectedRouteTypeDef](./type_defs.md#expectedroutetypedef)\]
- `ActualFirewallSubnetRoutes`:
  `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `InternetGatewayId`: `str`
- `CurrentInternetGatewayRouteTable`: `str`
- `ExpectedInternetGatewayRoutes`:
  `List`\[[ExpectedRouteTypeDef](./type_defs.md#expectedroutetypedef)\]
- `ActualInternetGatewayRoutes`:
  `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `VpcId`: `str`

<a id="networkfirewallmissingexpectedrtviolationtypedef"></a>

## NetworkFirewallMissingExpectedRTViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallMissingExpectedRTViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `VPC`: `str`
- `AvailabilityZone`: `str`
- `CurrentRouteTable`: `str`
- `ExpectedRouteTable`: `str`

<a id="networkfirewallmissingexpectedroutesviolationtypedef"></a>

## NetworkFirewallMissingExpectedRoutesViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallMissingExpectedRoutesViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `ExpectedRoutes`:
  `List`\[[ExpectedRouteTypeDef](./type_defs.md#expectedroutetypedef)\]
- `VpcId`: `str`

<a id="networkfirewallmissingfirewallviolationtypedef"></a>

## NetworkFirewallMissingFirewallViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallMissingFirewallViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `VPC`: `str`
- `AvailabilityZone`: `str`
- `TargetViolationReason`: `str`

<a id="networkfirewallmissingsubnetviolationtypedef"></a>

## NetworkFirewallMissingSubnetViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallMissingSubnetViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `VPC`: `str`
- `AvailabilityZone`: `str`
- `TargetViolationReason`: `str`

<a id="networkfirewallpolicydescriptiontypedef"></a>

## NetworkFirewallPolicyDescriptionTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallPolicyDescriptionTypeDef
```

Optional fields:

- `StatelessRuleGroups`:
  `List`\[[StatelessRuleGroupTypeDef](./type_defs.md#statelessrulegrouptypedef)\]
- `StatelessDefaultActions`: `List`\[`str`\]
- `StatelessFragmentDefaultActions`: `List`\[`str`\]
- `StatelessCustomActions`: `List`\[`str`\]
- `StatefulRuleGroups`:
  `List`\[[StatefulRuleGroupTypeDef](./type_defs.md#statefulrulegrouptypedef)\]

<a id="networkfirewallpolicymodifiedviolationtypedef"></a>

## NetworkFirewallPolicyModifiedViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallPolicyModifiedViolationTypeDef
```

Optional fields:

- `ViolationTarget`: `str`
- `CurrentPolicyDescription`:
  [NetworkFirewallPolicyDescriptionTypeDef](./type_defs.md#networkfirewallpolicydescriptiontypedef)
- `ExpectedPolicyDescription`:
  [NetworkFirewallPolicyDescriptionTypeDef](./type_defs.md#networkfirewallpolicydescriptiontypedef)

<a id="networkfirewallpolicytypedef"></a>

## NetworkFirewallPolicyTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallPolicyTypeDef
```

Optional fields:

- `FirewallDeploymentModel`: `Literal['CENTRALIZED']` (see
  [FirewallDeploymentModelType](./literals.md#firewalldeploymentmodeltype))

<a id="networkfirewallunexpectedfirewallroutesviolationtypedef"></a>

## NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef
```

Optional fields:

- `FirewallSubnetId`: `str`
- `ViolatingRoutes`: `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `RouteTableId`: `str`
- `FirewallEndpoint`: `str`
- `VpcId`: `str`

<a id="networkfirewallunexpectedgatewayroutesviolationtypedef"></a>

## NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef
```

Optional fields:

- `GatewayId`: `str`
- `ViolatingRoutes`: `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `RouteTableId`: `str`
- `VpcId`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_fms.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="partialmatchtypedef"></a>

## PartialMatchTypeDef

```python
from types_aiobotocore_fms.type_defs import PartialMatchTypeDef
```

Optional fields:

- `Reference`: `str`
- `TargetViolationReasons`: `List`\[`str`\]

<a id="policycompliancedetailtypedef"></a>

## PolicyComplianceDetailTypeDef

```python
from types_aiobotocore_fms.type_defs import PolicyComplianceDetailTypeDef
```

Optional fields:

- `PolicyOwner`: `str`
- `PolicyId`: `str`
- `MemberAccount`: `str`
- `Violators`:
  `List`\[[ComplianceViolatorTypeDef](./type_defs.md#complianceviolatortypedef)\]
- `EvaluationLimitExceeded`: `bool`
- `ExpiredAt`: `datetime`
- `IssueInfoMap`:
  `Dict`\[[DependentServiceNameType](./literals.md#dependentservicenametype),
  `str`\]

<a id="policycompliancestatustypedef"></a>

## PolicyComplianceStatusTypeDef

```python
from types_aiobotocore_fms.type_defs import PolicyComplianceStatusTypeDef
```

Optional fields:

- `PolicyOwner`: `str`
- `PolicyId`: `str`
- `PolicyName`: `str`
- `MemberAccount`: `str`
- `EvaluationResults`:
  `List`\[[EvaluationResultTypeDef](./type_defs.md#evaluationresulttypedef)\]
- `LastUpdated`: `datetime`
- `IssueInfoMap`:
  `Dict`\[[DependentServiceNameType](./literals.md#dependentservicenametype),
  `str`\]

<a id="policyoptiontypedef"></a>

## PolicyOptionTypeDef

```python
from types_aiobotocore_fms.type_defs import PolicyOptionTypeDef
```

Optional fields:

- `NetworkFirewallPolicy`:
  [NetworkFirewallPolicyTypeDef](./type_defs.md#networkfirewallpolicytypedef)

<a id="policysummarytypedef"></a>

## PolicySummaryTypeDef

```python
from types_aiobotocore_fms.type_defs import PolicySummaryTypeDef
```

Optional fields:

- `PolicyArn`: `str`
- `PolicyId`: `str`
- `PolicyName`: `str`
- `ResourceType`: `str`
- `SecurityServiceType`:
  [SecurityServiceTypeType](./literals.md#securityservicetypetype)
- `RemediationEnabled`: `bool`
- `DeleteUnusedFMManagedResources`: `bool`

<a id="policytypedef"></a>

## PolicyTypeDef

```python
from types_aiobotocore_fms.type_defs import PolicyTypeDef
```

Required fields:

- `PolicyName`: `str`
- `SecurityServicePolicyData`:
  [SecurityServicePolicyDataTypeDef](./type_defs.md#securityservicepolicydatatypedef)
- `ResourceType`: `str`
- `ExcludeResourceTags`: `bool`
- `RemediationEnabled`: `bool`

Optional fields:

- `PolicyId`: `str`
- `PolicyUpdateToken`: `str`
- `ResourceTypeList`: `List`\[`str`\]
- `ResourceTags`:
  `List`\[[ResourceTagTypeDef](./type_defs.md#resourcetagtypedef)\]
- `DeleteUnusedFMManagedResources`: `bool`
- `IncludeMap`:
  `Dict`\[[CustomerPolicyScopeIdTypeType](./literals.md#customerpolicyscopeidtypetype),
  `List`\[`str`\]\]
- `ExcludeMap`:
  `Dict`\[[CustomerPolicyScopeIdTypeType](./literals.md#customerpolicyscopeidtypetype),
  `List`\[`str`\]\]

<a id="possibleremediationactiontypedef"></a>

## PossibleRemediationActionTypeDef

```python
from types_aiobotocore_fms.type_defs import PossibleRemediationActionTypeDef
```

Required fields:

- `OrderedRemediationActions`:
  `List`\[[RemediationActionWithOrderTypeDef](./type_defs.md#remediationactionwithordertypedef)\]

Optional fields:

- `Description`: `str`
- `IsDefaultAction`: `bool`

<a id="possibleremediationactionstypedef"></a>

## PossibleRemediationActionsTypeDef

```python
from types_aiobotocore_fms.type_defs import PossibleRemediationActionsTypeDef
```

Optional fields:

- `Description`: `str`
- `Actions`:
  `List`\[[PossibleRemediationActionTypeDef](./type_defs.md#possibleremediationactiontypedef)\]

<a id="protocolslistdatasummarytypedef"></a>

## ProtocolsListDataSummaryTypeDef

```python
from types_aiobotocore_fms.type_defs import ProtocolsListDataSummaryTypeDef
```

Optional fields:

- `ListArn`: `str`
- `ListId`: `str`
- `ListName`: `str`
- `ProtocolsList`: `List`\[`str`\]

<a id="protocolslistdatatypedef"></a>

## ProtocolsListDataTypeDef

```python
from types_aiobotocore_fms.type_defs import ProtocolsListDataTypeDef
```

Required fields:

- `ListName`: `str`
- `ProtocolsList`: `List`\[`str`\]

Optional fields:

- `ListId`: `str`
- `ListUpdateToken`: `str`
- `CreateTime`: `datetime`
- `LastUpdateTime`: `datetime`
- `PreviousProtocolsList`: `Dict`\[`str`, `List`\[`str`\]\]

<a id="putappslistrequestrequesttypedef"></a>

## PutAppsListRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import PutAppsListRequestRequestTypeDef
```

Required fields:

- `AppsList`: [AppsListDataTypeDef](./type_defs.md#appslistdatatypedef)

Optional fields:

- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="putappslistresponsetypedef"></a>

## PutAppsListResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import PutAppsListResponseTypeDef
```

Required fields:

- `AppsList`: [AppsListDataTypeDef](./type_defs.md#appslistdatatypedef)
- `AppsListArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="putnotificationchannelrequestrequesttypedef"></a>

## PutNotificationChannelRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import PutNotificationChannelRequestRequestTypeDef
```

Required fields:

- `SnsTopicArn`: `str`
- `SnsRoleName`: `str`

<a id="putpolicyrequestrequesttypedef"></a>

## PutPolicyRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import PutPolicyRequestRequestTypeDef
```

Required fields:

- `Policy`: [PolicyTypeDef](./type_defs.md#policytypedef)

Optional fields:

- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="putpolicyresponsetypedef"></a>

## PutPolicyResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import PutPolicyResponseTypeDef
```

Required fields:

- `Policy`: [PolicyTypeDef](./type_defs.md#policytypedef)
- `PolicyArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="putprotocolslistrequestrequesttypedef"></a>

## PutProtocolsListRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import PutProtocolsListRequestRequestTypeDef
```

Required fields:

- `ProtocolsList`:
  [ProtocolsListDataTypeDef](./type_defs.md#protocolslistdatatypedef)

Optional fields:

- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="putprotocolslistresponsetypedef"></a>

## PutProtocolsListResponseTypeDef

```python
from types_aiobotocore_fms.type_defs import PutProtocolsListResponseTypeDef
```

Required fields:

- `ProtocolsList`:
  [ProtocolsListDataTypeDef](./type_defs.md#protocolslistdatatypedef)
- `ProtocolsListArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="remediationactiontypedef"></a>

## RemediationActionTypeDef

```python
from types_aiobotocore_fms.type_defs import RemediationActionTypeDef
```

Optional fields:

- `Description`: `str`
- `EC2CreateRouteAction`:
  [EC2CreateRouteActionTypeDef](./type_defs.md#ec2createrouteactiontypedef)
- `EC2ReplaceRouteAction`:
  [EC2ReplaceRouteActionTypeDef](./type_defs.md#ec2replacerouteactiontypedef)
- `EC2DeleteRouteAction`:
  [EC2DeleteRouteActionTypeDef](./type_defs.md#ec2deleterouteactiontypedef)
- `EC2CopyRouteTableAction`:
  [EC2CopyRouteTableActionTypeDef](./type_defs.md#ec2copyroutetableactiontypedef)
- `EC2ReplaceRouteTableAssociationAction`:
  [EC2ReplaceRouteTableAssociationActionTypeDef](./type_defs.md#ec2replaceroutetableassociationactiontypedef)
- `EC2AssociateRouteTableAction`:
  [EC2AssociateRouteTableActionTypeDef](./type_defs.md#ec2associateroutetableactiontypedef)
- `EC2CreateRouteTableAction`:
  [EC2CreateRouteTableActionTypeDef](./type_defs.md#ec2createroutetableactiontypedef)
- `FMSPolicyUpdateFirewallCreationConfigAction`:
  [FMSPolicyUpdateFirewallCreationConfigActionTypeDef](./type_defs.md#fmspolicyupdatefirewallcreationconfigactiontypedef)

<a id="remediationactionwithordertypedef"></a>

## RemediationActionWithOrderTypeDef

```python
from types_aiobotocore_fms.type_defs import RemediationActionWithOrderTypeDef
```

Optional fields:

- `RemediationAction`:
  [RemediationActionTypeDef](./type_defs.md#remediationactiontypedef)
- `Order`: `int`

<a id="resourcetagtypedef"></a>

## ResourceTagTypeDef

```python
from types_aiobotocore_fms.type_defs import ResourceTagTypeDef
```

Required fields:

- `Key`: `str`

Optional fields:

- `Value`: `str`

<a id="resourceviolationtypedef"></a>

## ResourceViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import ResourceViolationTypeDef
```

Optional fields:

- `AwsVPCSecurityGroupViolation`:
  [AwsVPCSecurityGroupViolationTypeDef](./type_defs.md#awsvpcsecuritygroupviolationtypedef)
- `AwsEc2NetworkInterfaceViolation`:
  [AwsEc2NetworkInterfaceViolationTypeDef](./type_defs.md#awsec2networkinterfaceviolationtypedef)
- `AwsEc2InstanceViolation`:
  [AwsEc2InstanceViolationTypeDef](./type_defs.md#awsec2instanceviolationtypedef)
- `NetworkFirewallMissingFirewallViolation`:
  [NetworkFirewallMissingFirewallViolationTypeDef](./type_defs.md#networkfirewallmissingfirewallviolationtypedef)
- `NetworkFirewallMissingSubnetViolation`:
  [NetworkFirewallMissingSubnetViolationTypeDef](./type_defs.md#networkfirewallmissingsubnetviolationtypedef)
- `NetworkFirewallMissingExpectedRTViolation`:
  [NetworkFirewallMissingExpectedRTViolationTypeDef](./type_defs.md#networkfirewallmissingexpectedrtviolationtypedef)
- `NetworkFirewallPolicyModifiedViolation`:
  [NetworkFirewallPolicyModifiedViolationTypeDef](./type_defs.md#networkfirewallpolicymodifiedviolationtypedef)
- `NetworkFirewallInternetTrafficNotInspectedViolation`:
  [NetworkFirewallInternetTrafficNotInspectedViolationTypeDef](./type_defs.md#networkfirewallinternettrafficnotinspectedviolationtypedef)
- `NetworkFirewallInvalidRouteConfigurationViolation`:
  [NetworkFirewallInvalidRouteConfigurationViolationTypeDef](./type_defs.md#networkfirewallinvalidrouteconfigurationviolationtypedef)
- `NetworkFirewallBlackHoleRouteDetectedViolation`:
  [NetworkFirewallBlackHoleRouteDetectedViolationTypeDef](./type_defs.md#networkfirewallblackholeroutedetectedviolationtypedef)
- `NetworkFirewallUnexpectedFirewallRoutesViolation`:
  [NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef](./type_defs.md#networkfirewallunexpectedfirewallroutesviolationtypedef)
- `NetworkFirewallUnexpectedGatewayRoutesViolation`:
  [NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef](./type_defs.md#networkfirewallunexpectedgatewayroutesviolationtypedef)
- `NetworkFirewallMissingExpectedRoutesViolation`:
  [NetworkFirewallMissingExpectedRoutesViolationTypeDef](./type_defs.md#networkfirewallmissingexpectedroutesviolationtypedef)
- `DnsRuleGroupPriorityConflictViolation`:
  [DnsRuleGroupPriorityConflictViolationTypeDef](./type_defs.md#dnsrulegrouppriorityconflictviolationtypedef)
- `DnsDuplicateRuleGroupViolation`:
  [DnsDuplicateRuleGroupViolationTypeDef](./type_defs.md#dnsduplicaterulegroupviolationtypedef)
- `DnsRuleGroupLimitExceededViolation`:
  [DnsRuleGroupLimitExceededViolationTypeDef](./type_defs.md#dnsrulegrouplimitexceededviolationtypedef)
- `PossibleRemediationActions`:
  [PossibleRemediationActionsTypeDef](./type_defs.md#possibleremediationactionstypedef)
- `FirewallSubnetIsOutOfScopeViolation`:
  [FirewallSubnetIsOutOfScopeViolationTypeDef](./type_defs.md#firewallsubnetisoutofscopeviolationtypedef)
- `RouteHasOutOfScopeEndpointViolation`:
  [RouteHasOutOfScopeEndpointViolationTypeDef](./type_defs.md#routehasoutofscopeendpointviolationtypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_fms.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="routehasoutofscopeendpointviolationtypedef"></a>

## RouteHasOutOfScopeEndpointViolationTypeDef

```python
from types_aiobotocore_fms.type_defs import RouteHasOutOfScopeEndpointViolationTypeDef
```

Optional fields:

- `SubnetId`: `str`
- `VpcId`: `str`
- `RouteTableId`: `str`
- `ViolatingRoutes`: `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `SubnetAvailabilityZone`: `str`
- `SubnetAvailabilityZoneId`: `str`
- `CurrentFirewallSubnetRouteTable`: `str`
- `FirewallSubnetId`: `str`
- `FirewallSubnetRoutes`: `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `InternetGatewayId`: `str`
- `CurrentInternetGatewayRouteTable`: `str`
- `InternetGatewayRoutes`:
  `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]

<a id="routetypedef"></a>

## RouteTypeDef

```python
from types_aiobotocore_fms.type_defs import RouteTypeDef
```

Optional fields:

- `DestinationType`: [DestinationTypeType](./literals.md#destinationtypetype)
- `TargetType`: [TargetTypeType](./literals.md#targettypetype)
- `Destination`: `str`
- `Target`: `str`

<a id="securitygroupremediationactiontypedef"></a>

## SecurityGroupRemediationActionTypeDef

```python
from types_aiobotocore_fms.type_defs import SecurityGroupRemediationActionTypeDef
```

Optional fields:

- `RemediationActionType`:
  [RemediationActionTypeType](./literals.md#remediationactiontypetype)
- `Description`: `str`
- `RemediationResult`:
  [SecurityGroupRuleDescriptionTypeDef](./type_defs.md#securitygroupruledescriptiontypedef)
- `IsDefaultAction`: `bool`

<a id="securitygroupruledescriptiontypedef"></a>

## SecurityGroupRuleDescriptionTypeDef

```python
from types_aiobotocore_fms.type_defs import SecurityGroupRuleDescriptionTypeDef
```

Optional fields:

- `IPV4Range`: `str`
- `IPV6Range`: `str`
- `PrefixListId`: `str`
- `Protocol`: `str`
- `FromPort`: `int`
- `ToPort`: `int`

<a id="securityservicepolicydatatypedef"></a>

## SecurityServicePolicyDataTypeDef

```python
from types_aiobotocore_fms.type_defs import SecurityServicePolicyDataTypeDef
```

Required fields:

- `Type`: [SecurityServiceTypeType](./literals.md#securityservicetypetype)

Optional fields:

- `ManagedServiceData`: `str`
- `PolicyOption`: [PolicyOptionTypeDef](./type_defs.md#policyoptiontypedef)

<a id="statefulrulegrouptypedef"></a>

## StatefulRuleGroupTypeDef

```python
from types_aiobotocore_fms.type_defs import StatefulRuleGroupTypeDef
```

Optional fields:

- `RuleGroupName`: `str`
- `ResourceId`: `str`

<a id="statelessrulegrouptypedef"></a>

## StatelessRuleGroupTypeDef

```python
from types_aiobotocore_fms.type_defs import StatelessRuleGroupTypeDef
```

Optional fields:

- `RuleGroupName`: `str`
- `ResourceId`: `str`
- `Priority`: `int`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagList`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_fms.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_fms.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="violationdetailtypedef"></a>

## ViolationDetailTypeDef

```python
from types_aiobotocore_fms.type_defs import ViolationDetailTypeDef
```

Required fields:

- `PolicyId`: `str`
- `MemberAccount`: `str`
- `ResourceId`: `str`
- `ResourceType`: `str`
- `ResourceViolations`:
  `List`\[[ResourceViolationTypeDef](./type_defs.md#resourceviolationtypedef)\]

Optional fields:

- `ResourceTags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResourceDescription`: `str`
