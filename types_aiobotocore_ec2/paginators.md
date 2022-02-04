<a id="paginators-for-aiobotocore-ec2-module"></a>

# Paginators for aiobotocore EC2 module

> [Index](..) > [EC2](.) > Paginators

Auto-generated documentation for
[EC2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2)
type annotations stubs module
[types-aiobotocore-ec2](https://pypi.org/project/types-aiobotocore-ec2/).

- [Paginators for aiobotocore EC2 module](#paginators-for-aiobotocore-ec2-module)
  - [DescribeAddressesAttributePaginator](#describeaddressesattributepaginator)
  - [DescribeByoipCidrsPaginator](#describebyoipcidrspaginator)
  - [DescribeCapacityReservationFleetsPaginator](#describecapacityreservationfleetspaginator)
  - [DescribeCapacityReservationsPaginator](#describecapacityreservationspaginator)
  - [DescribeCarrierGatewaysPaginator](#describecarriergatewayspaginator)
  - [DescribeClassicLinkInstancesPaginator](#describeclassiclinkinstancespaginator)
  - [DescribeClientVpnAuthorizationRulesPaginator](#describeclientvpnauthorizationrulespaginator)
  - [DescribeClientVpnConnectionsPaginator](#describeclientvpnconnectionspaginator)
  - [DescribeClientVpnEndpointsPaginator](#describeclientvpnendpointspaginator)
  - [DescribeClientVpnRoutesPaginator](#describeclientvpnroutespaginator)
  - [DescribeClientVpnTargetNetworksPaginator](#describeclientvpntargetnetworkspaginator)
  - [DescribeCoipPoolsPaginator](#describecoippoolspaginator)
  - [DescribeDhcpOptionsPaginator](#describedhcpoptionspaginator)
  - [DescribeEgressOnlyInternetGatewaysPaginator](#describeegressonlyinternetgatewayspaginator)
  - [DescribeExportImageTasksPaginator](#describeexportimagetaskspaginator)
  - [DescribeFastSnapshotRestoresPaginator](#describefastsnapshotrestorespaginator)
  - [DescribeFleetsPaginator](#describefleetspaginator)
  - [DescribeFlowLogsPaginator](#describeflowlogspaginator)
  - [DescribeFpgaImagesPaginator](#describefpgaimagespaginator)
  - [DescribeHostReservationOfferingsPaginator](#describehostreservationofferingspaginator)
  - [DescribeHostReservationsPaginator](#describehostreservationspaginator)
  - [DescribeHostsPaginator](#describehostspaginator)
  - [DescribeIamInstanceProfileAssociationsPaginator](#describeiaminstanceprofileassociationspaginator)
  - [DescribeImportImageTasksPaginator](#describeimportimagetaskspaginator)
  - [DescribeImportSnapshotTasksPaginator](#describeimportsnapshottaskspaginator)
  - [DescribeInstanceCreditSpecificationsPaginator](#describeinstancecreditspecificationspaginator)
  - [DescribeInstanceEventWindowsPaginator](#describeinstanceeventwindowspaginator)
  - [DescribeInstanceStatusPaginator](#describeinstancestatuspaginator)
  - [DescribeInstanceTypeOfferingsPaginator](#describeinstancetypeofferingspaginator)
  - [DescribeInstanceTypesPaginator](#describeinstancetypespaginator)
  - [DescribeInstancesPaginator](#describeinstancespaginator)
  - [DescribeInternetGatewaysPaginator](#describeinternetgatewayspaginator)
  - [DescribeIpamPoolsPaginator](#describeipampoolspaginator)
  - [DescribeIpamScopesPaginator](#describeipamscopespaginator)
  - [DescribeIpamsPaginator](#describeipamspaginator)
  - [DescribeIpv6PoolsPaginator](#describeipv6poolspaginator)
  - [DescribeLaunchTemplateVersionsPaginator](#describelaunchtemplateversionspaginator)
  - [DescribeLaunchTemplatesPaginator](#describelaunchtemplatespaginator)
  - [DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator](#describelocalgatewayroutetablevirtualinterfacegroupassociationspaginator)
  - [DescribeLocalGatewayRouteTableVpcAssociationsPaginator](#describelocalgatewayroutetablevpcassociationspaginator)
  - [DescribeLocalGatewayRouteTablesPaginator](#describelocalgatewayroutetablespaginator)
  - [DescribeLocalGatewayVirtualInterfaceGroupsPaginator](#describelocalgatewayvirtualinterfacegroupspaginator)
  - [DescribeLocalGatewayVirtualInterfacesPaginator](#describelocalgatewayvirtualinterfacespaginator)
  - [DescribeLocalGatewaysPaginator](#describelocalgatewayspaginator)
  - [DescribeManagedPrefixListsPaginator](#describemanagedprefixlistspaginator)
  - [DescribeMovingAddressesPaginator](#describemovingaddressespaginator)
  - [DescribeNatGatewaysPaginator](#describenatgatewayspaginator)
  - [DescribeNetworkAclsPaginator](#describenetworkaclspaginator)
  - [DescribeNetworkInsightsAccessScopeAnalysesPaginator](#describenetworkinsightsaccessscopeanalysespaginator)
  - [DescribeNetworkInsightsAccessScopesPaginator](#describenetworkinsightsaccessscopespaginator)
  - [DescribeNetworkInsightsAnalysesPaginator](#describenetworkinsightsanalysespaginator)
  - [DescribeNetworkInsightsPathsPaginator](#describenetworkinsightspathspaginator)
  - [DescribeNetworkInterfacePermissionsPaginator](#describenetworkinterfacepermissionspaginator)
  - [DescribeNetworkInterfacesPaginator](#describenetworkinterfacespaginator)
  - [DescribePrefixListsPaginator](#describeprefixlistspaginator)
  - [DescribePrincipalIdFormatPaginator](#describeprincipalidformatpaginator)
  - [DescribePublicIpv4PoolsPaginator](#describepublicipv4poolspaginator)
  - [DescribeReplaceRootVolumeTasksPaginator](#describereplacerootvolumetaskspaginator)
  - [DescribeReservedInstancesModificationsPaginator](#describereservedinstancesmodificationspaginator)
  - [DescribeReservedInstancesOfferingsPaginator](#describereservedinstancesofferingspaginator)
  - [DescribeRouteTablesPaginator](#describeroutetablespaginator)
  - [DescribeScheduledInstanceAvailabilityPaginator](#describescheduledinstanceavailabilitypaginator)
  - [DescribeScheduledInstancesPaginator](#describescheduledinstancespaginator)
  - [DescribeSecurityGroupRulesPaginator](#describesecuritygrouprulespaginator)
  - [DescribeSecurityGroupsPaginator](#describesecuritygroupspaginator)
  - [DescribeSnapshotTierStatusPaginator](#describesnapshottierstatuspaginator)
  - [DescribeSnapshotsPaginator](#describesnapshotspaginator)
  - [DescribeSpotFleetInstancesPaginator](#describespotfleetinstancespaginator)
  - [DescribeSpotFleetRequestsPaginator](#describespotfleetrequestspaginator)
  - [DescribeSpotInstanceRequestsPaginator](#describespotinstancerequestspaginator)
  - [DescribeSpotPriceHistoryPaginator](#describespotpricehistorypaginator)
  - [DescribeStaleSecurityGroupsPaginator](#describestalesecuritygroupspaginator)
  - [DescribeStoreImageTasksPaginator](#describestoreimagetaskspaginator)
  - [DescribeSubnetsPaginator](#describesubnetspaginator)
  - [DescribeTagsPaginator](#describetagspaginator)
  - [DescribeTrafficMirrorFiltersPaginator](#describetrafficmirrorfilterspaginator)
  - [DescribeTrafficMirrorSessionsPaginator](#describetrafficmirrorsessionspaginator)
  - [DescribeTrafficMirrorTargetsPaginator](#describetrafficmirrortargetspaginator)
  - [DescribeTransitGatewayAttachmentsPaginator](#describetransitgatewayattachmentspaginator)
  - [DescribeTransitGatewayConnectPeersPaginator](#describetransitgatewayconnectpeerspaginator)
  - [DescribeTransitGatewayConnectsPaginator](#describetransitgatewayconnectspaginator)
  - [DescribeTransitGatewayMulticastDomainsPaginator](#describetransitgatewaymulticastdomainspaginator)
  - [DescribeTransitGatewayPeeringAttachmentsPaginator](#describetransitgatewaypeeringattachmentspaginator)
  - [DescribeTransitGatewayRouteTablesPaginator](#describetransitgatewayroutetablespaginator)
  - [DescribeTransitGatewayVpcAttachmentsPaginator](#describetransitgatewayvpcattachmentspaginator)
  - [DescribeTransitGatewaysPaginator](#describetransitgatewayspaginator)
  - [DescribeTrunkInterfaceAssociationsPaginator](#describetrunkinterfaceassociationspaginator)
  - [DescribeVolumeStatusPaginator](#describevolumestatuspaginator)
  - [DescribeVolumesPaginator](#describevolumespaginator)
  - [DescribeVolumesModificationsPaginator](#describevolumesmodificationspaginator)
  - [DescribeVpcClassicLinkDnsSupportPaginator](#describevpcclassiclinkdnssupportpaginator)
  - [DescribeVpcEndpointConnectionNotificationsPaginator](#describevpcendpointconnectionnotificationspaginator)
  - [DescribeVpcEndpointConnectionsPaginator](#describevpcendpointconnectionspaginator)
  - [DescribeVpcEndpointServiceConfigurationsPaginator](#describevpcendpointserviceconfigurationspaginator)
  - [DescribeVpcEndpointServicePermissionsPaginator](#describevpcendpointservicepermissionspaginator)
  - [DescribeVpcEndpointServicesPaginator](#describevpcendpointservicespaginator)
  - [DescribeVpcEndpointsPaginator](#describevpcendpointspaginator)
  - [DescribeVpcPeeringConnectionsPaginator](#describevpcpeeringconnectionspaginator)
  - [DescribeVpcsPaginator](#describevpcspaginator)
  - [GetAssociatedIpv6PoolCidrsPaginator](#getassociatedipv6poolcidrspaginator)
  - [GetGroupsForCapacityReservationPaginator](#getgroupsforcapacityreservationpaginator)
  - [GetInstanceTypesFromInstanceRequirementsPaginator](#getinstancetypesfrominstancerequirementspaginator)
  - [GetIpamAddressHistoryPaginator](#getipamaddresshistorypaginator)
  - [GetIpamPoolAllocationsPaginator](#getipampoolallocationspaginator)
  - [GetIpamPoolCidrsPaginator](#getipampoolcidrspaginator)
  - [GetIpamResourceCidrsPaginator](#getipamresourcecidrspaginator)
  - [GetManagedPrefixListAssociationsPaginator](#getmanagedprefixlistassociationspaginator)
  - [GetManagedPrefixListEntriesPaginator](#getmanagedprefixlistentriespaginator)
  - [GetSpotPlacementScoresPaginator](#getspotplacementscorespaginator)
  - [GetTransitGatewayAttachmentPropagationsPaginator](#gettransitgatewayattachmentpropagationspaginator)
  - [GetTransitGatewayMulticastDomainAssociationsPaginator](#gettransitgatewaymulticastdomainassociationspaginator)
  - [GetTransitGatewayPrefixListReferencesPaginator](#gettransitgatewayprefixlistreferencespaginator)
  - [GetTransitGatewayRouteTableAssociationsPaginator](#gettransitgatewayroutetableassociationspaginator)
  - [GetTransitGatewayRouteTablePropagationsPaginator](#gettransitgatewayroutetablepropagationspaginator)
  - [GetVpnConnectionDeviceTypesPaginator](#getvpnconnectiondevicetypespaginator)
  - [ListSnapshotsInRecycleBinPaginator](#listsnapshotsinrecyclebinpaginator)
  - [SearchLocalGatewayRoutesPaginator](#searchlocalgatewayroutespaginator)
  - [SearchTransitGatewayMulticastGroupsPaginator](#searchtransitgatewaymulticastgroupspaginator)

<a id="describeaddressesattributepaginator"></a>

## DescribeAddressesAttributePaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_addresses_attribute")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeAddressesAttributePaginator

def get_describe_addresses_attribute_paginator() -> DescribeAddressesAttributePaginator:
    return Session().create_client("ec2").get_paginator("describe_addresses_attribute")
```

Boto3 documentation:
[EC2.Paginator.DescribeAddressesAttribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeAddressesAttribute)

Arguments for `DescribeAddressesAttributePaginator.paginate` method:

- `AllocationIds`: `Sequence`\[`str`\]
- `Attribute`: `Literal['domain-name']` (see
  [AddressAttributeNameType](./literals.md#addressattributenametype))
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeAddressesAttributePaginator.paginate` returns
`_PageIterator`\[[DescribeAddressesAttributeResultTypeDef](./type_defs.md#describeaddressesattributeresulttypedef)\].

<a id="describebyoipcidrspaginator"></a>

## DescribeByoipCidrsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_byoip_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeByoipCidrsPaginator

def get_describe_byoip_cidrs_paginator() -> DescribeByoipCidrsPaginator:
    return Session().create_client("ec2").get_paginator("describe_byoip_cidrs")
```

Boto3 documentation:
[EC2.Paginator.DescribeByoipCidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeByoipCidrs)

Arguments for `DescribeByoipCidrsPaginator.paginate` method:

- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeByoipCidrsPaginator.paginate` returns
`_PageIterator`\[[DescribeByoipCidrsResultTypeDef](./type_defs.md#describebyoipcidrsresulttypedef)\].

<a id="describecapacityreservationfleetspaginator"></a>

## DescribeCapacityReservationFleetsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_capacity_reservation_fleets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeCapacityReservationFleetsPaginator

def get_describe_capacity_reservation_fleets_paginator() -> DescribeCapacityReservationFleetsPaginator:
    return Session().create_client("ec2").get_paginator("describe_capacity_reservation_fleets")
```

Boto3 documentation:
[EC2.Paginator.DescribeCapacityReservationFleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeCapacityReservationFleets)

Arguments for `DescribeCapacityReservationFleetsPaginator.paginate` method:

- `CapacityReservationFleetIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeCapacityReservationFleetsPaginator.paginate` returns
`_PageIterator`\[[DescribeCapacityReservationFleetsResultTypeDef](./type_defs.md#describecapacityreservationfleetsresulttypedef)\].

<a id="describecapacityreservationspaginator"></a>

## DescribeCapacityReservationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_capacity_reservations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeCapacityReservationsPaginator

def get_describe_capacity_reservations_paginator() -> DescribeCapacityReservationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_capacity_reservations")
```

Boto3 documentation:
[EC2.Paginator.DescribeCapacityReservations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeCapacityReservations)

Arguments for `DescribeCapacityReservationsPaginator.paginate` method:

- `CapacityReservationIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeCapacityReservationsPaginator.paginate` returns
`_PageIterator`\[[DescribeCapacityReservationsResultTypeDef](./type_defs.md#describecapacityreservationsresulttypedef)\].

<a id="describecarriergatewayspaginator"></a>

## DescribeCarrierGatewaysPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_carrier_gateways")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeCarrierGatewaysPaginator

def get_describe_carrier_gateways_paginator() -> DescribeCarrierGatewaysPaginator:
    return Session().create_client("ec2").get_paginator("describe_carrier_gateways")
```

Boto3 documentation:
[EC2.Paginator.DescribeCarrierGateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeCarrierGateways)

Arguments for `DescribeCarrierGatewaysPaginator.paginate` method:

- `CarrierGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeCarrierGatewaysPaginator.paginate` returns
`_PageIterator`\[[DescribeCarrierGatewaysResultTypeDef](./type_defs.md#describecarriergatewaysresulttypedef)\].

<a id="describeclassiclinkinstancespaginator"></a>

## DescribeClassicLinkInstancesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_classic_link_instances")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeClassicLinkInstancesPaginator

def get_describe_classic_link_instances_paginator() -> DescribeClassicLinkInstancesPaginator:
    return Session().create_client("ec2").get_paginator("describe_classic_link_instances")
```

Boto3 documentation:
[EC2.Paginator.DescribeClassicLinkInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeClassicLinkInstances)

Arguments for `DescribeClassicLinkInstancesPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `InstanceIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeClassicLinkInstancesPaginator.paginate` returns
`_PageIterator`\[[DescribeClassicLinkInstancesResultTypeDef](./type_defs.md#describeclassiclinkinstancesresulttypedef)\].

<a id="describeclientvpnauthorizationrulespaginator"></a>

## DescribeClientVpnAuthorizationRulesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_client_vpn_authorization_rules")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeClientVpnAuthorizationRulesPaginator

def get_describe_client_vpn_authorization_rules_paginator() -> DescribeClientVpnAuthorizationRulesPaginator:
    return Session().create_client("ec2").get_paginator("describe_client_vpn_authorization_rules")
```

Boto3 documentation:
[EC2.Paginator.DescribeClientVpnAuthorizationRules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeClientVpnAuthorizationRules)

Arguments for `DescribeClientVpnAuthorizationRulesPaginator.paginate` method:

- `ClientVpnEndpointId`: `str` *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeClientVpnAuthorizationRulesPaginator.paginate` returns
`_PageIterator`\[[DescribeClientVpnAuthorizationRulesResultTypeDef](./type_defs.md#describeclientvpnauthorizationrulesresulttypedef)\].

<a id="describeclientvpnconnectionspaginator"></a>

## DescribeClientVpnConnectionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_client_vpn_connections")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeClientVpnConnectionsPaginator

def get_describe_client_vpn_connections_paginator() -> DescribeClientVpnConnectionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_client_vpn_connections")
```

Boto3 documentation:
[EC2.Paginator.DescribeClientVpnConnections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeClientVpnConnections)

Arguments for `DescribeClientVpnConnectionsPaginator.paginate` method:

- `ClientVpnEndpointId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeClientVpnConnectionsPaginator.paginate` returns
`_PageIterator`\[[DescribeClientVpnConnectionsResultTypeDef](./type_defs.md#describeclientvpnconnectionsresulttypedef)\].

<a id="describeclientvpnendpointspaginator"></a>

## DescribeClientVpnEndpointsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_client_vpn_endpoints")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeClientVpnEndpointsPaginator

def get_describe_client_vpn_endpoints_paginator() -> DescribeClientVpnEndpointsPaginator:
    return Session().create_client("ec2").get_paginator("describe_client_vpn_endpoints")
```

Boto3 documentation:
[EC2.Paginator.DescribeClientVpnEndpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeClientVpnEndpoints)

Arguments for `DescribeClientVpnEndpointsPaginator.paginate` method:

- `ClientVpnEndpointIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeClientVpnEndpointsPaginator.paginate` returns
`_PageIterator`\[[DescribeClientVpnEndpointsResultTypeDef](./type_defs.md#describeclientvpnendpointsresulttypedef)\].

<a id="describeclientvpnroutespaginator"></a>

## DescribeClientVpnRoutesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_client_vpn_routes")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeClientVpnRoutesPaginator

def get_describe_client_vpn_routes_paginator() -> DescribeClientVpnRoutesPaginator:
    return Session().create_client("ec2").get_paginator("describe_client_vpn_routes")
```

Boto3 documentation:
[EC2.Paginator.DescribeClientVpnRoutes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeClientVpnRoutes)

Arguments for `DescribeClientVpnRoutesPaginator.paginate` method:

- `ClientVpnEndpointId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeClientVpnRoutesPaginator.paginate` returns
`_PageIterator`\[[DescribeClientVpnRoutesResultTypeDef](./type_defs.md#describeclientvpnroutesresulttypedef)\].

<a id="describeclientvpntargetnetworkspaginator"></a>

## DescribeClientVpnTargetNetworksPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_client_vpn_target_networks")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeClientVpnTargetNetworksPaginator

def get_describe_client_vpn_target_networks_paginator() -> DescribeClientVpnTargetNetworksPaginator:
    return Session().create_client("ec2").get_paginator("describe_client_vpn_target_networks")
```

Boto3 documentation:
[EC2.Paginator.DescribeClientVpnTargetNetworks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeClientVpnTargetNetworks)

Arguments for `DescribeClientVpnTargetNetworksPaginator.paginate` method:

- `ClientVpnEndpointId`: `str` *(required)*
- `AssociationIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeClientVpnTargetNetworksPaginator.paginate` returns
`_PageIterator`\[[DescribeClientVpnTargetNetworksResultTypeDef](./type_defs.md#describeclientvpntargetnetworksresulttypedef)\].

<a id="describecoippoolspaginator"></a>

## DescribeCoipPoolsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_coip_pools")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeCoipPoolsPaginator

def get_describe_coip_pools_paginator() -> DescribeCoipPoolsPaginator:
    return Session().create_client("ec2").get_paginator("describe_coip_pools")
```

Boto3 documentation:
[EC2.Paginator.DescribeCoipPools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeCoipPools)

Arguments for `DescribeCoipPoolsPaginator.paginate` method:

- `PoolIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeCoipPoolsPaginator.paginate` returns
`_PageIterator`\[[DescribeCoipPoolsResultTypeDef](./type_defs.md#describecoippoolsresulttypedef)\].

<a id="describedhcpoptionspaginator"></a>

## DescribeDhcpOptionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_dhcp_options")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeDhcpOptionsPaginator

def get_describe_dhcp_options_paginator() -> DescribeDhcpOptionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_dhcp_options")
```

Boto3 documentation:
[EC2.Paginator.DescribeDhcpOptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeDhcpOptions)

Arguments for `DescribeDhcpOptionsPaginator.paginate` method:

- `DhcpOptionsIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeDhcpOptionsPaginator.paginate` returns
`_PageIterator`\[[DescribeDhcpOptionsResultTypeDef](./type_defs.md#describedhcpoptionsresulttypedef)\].

<a id="describeegressonlyinternetgatewayspaginator"></a>

## DescribeEgressOnlyInternetGatewaysPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_egress_only_internet_gateways")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeEgressOnlyInternetGatewaysPaginator

def get_describe_egress_only_internet_gateways_paginator() -> DescribeEgressOnlyInternetGatewaysPaginator:
    return Session().create_client("ec2").get_paginator("describe_egress_only_internet_gateways")
```

Boto3 documentation:
[EC2.Paginator.DescribeEgressOnlyInternetGateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeEgressOnlyInternetGateways)

Arguments for `DescribeEgressOnlyInternetGatewaysPaginator.paginate` method:

- `DryRun`: `bool`
- `EgressOnlyInternetGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEgressOnlyInternetGatewaysPaginator.paginate` returns
`_PageIterator`\[[DescribeEgressOnlyInternetGatewaysResultTypeDef](./type_defs.md#describeegressonlyinternetgatewaysresulttypedef)\].

<a id="describeexportimagetaskspaginator"></a>

## DescribeExportImageTasksPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_export_image_tasks")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeExportImageTasksPaginator

def get_describe_export_image_tasks_paginator() -> DescribeExportImageTasksPaginator:
    return Session().create_client("ec2").get_paginator("describe_export_image_tasks")
```

Boto3 documentation:
[EC2.Paginator.DescribeExportImageTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeExportImageTasks)

Arguments for `DescribeExportImageTasksPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ExportImageTaskIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeExportImageTasksPaginator.paginate` returns
`_PageIterator`\[[DescribeExportImageTasksResultTypeDef](./type_defs.md#describeexportimagetasksresulttypedef)\].

<a id="describefastsnapshotrestorespaginator"></a>

## DescribeFastSnapshotRestoresPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_fast_snapshot_restores")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeFastSnapshotRestoresPaginator

def get_describe_fast_snapshot_restores_paginator() -> DescribeFastSnapshotRestoresPaginator:
    return Session().create_client("ec2").get_paginator("describe_fast_snapshot_restores")
```

Boto3 documentation:
[EC2.Paginator.DescribeFastSnapshotRestores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeFastSnapshotRestores)

Arguments for `DescribeFastSnapshotRestoresPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFastSnapshotRestoresPaginator.paginate` returns
`_PageIterator`\[[DescribeFastSnapshotRestoresResultTypeDef](./type_defs.md#describefastsnapshotrestoresresulttypedef)\].

<a id="describefleetspaginator"></a>

## DescribeFleetsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_fleets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeFleetsPaginator

def get_describe_fleets_paginator() -> DescribeFleetsPaginator:
    return Session().create_client("ec2").get_paginator("describe_fleets")
```

Boto3 documentation:
[EC2.Paginator.DescribeFleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeFleets)

Arguments for `DescribeFleetsPaginator.paginate` method:

- `DryRun`: `bool`
- `FleetIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFleetsPaginator.paginate` returns
`_PageIterator`\[[DescribeFleetsResultTypeDef](./type_defs.md#describefleetsresulttypedef)\].

<a id="describeflowlogspaginator"></a>

## DescribeFlowLogsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_flow_logs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeFlowLogsPaginator

def get_describe_flow_logs_paginator() -> DescribeFlowLogsPaginator:
    return Session().create_client("ec2").get_paginator("describe_flow_logs")
```

Boto3 documentation:
[EC2.Paginator.DescribeFlowLogs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeFlowLogs)

Arguments for `DescribeFlowLogsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `FlowLogIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFlowLogsPaginator.paginate` returns
`_PageIterator`\[[DescribeFlowLogsResultTypeDef](./type_defs.md#describeflowlogsresulttypedef)\].

<a id="describefpgaimagespaginator"></a>

## DescribeFpgaImagesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_fpga_images")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeFpgaImagesPaginator

def get_describe_fpga_images_paginator() -> DescribeFpgaImagesPaginator:
    return Session().create_client("ec2").get_paginator("describe_fpga_images")
```

Boto3 documentation:
[EC2.Paginator.DescribeFpgaImages](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeFpgaImages)

Arguments for `DescribeFpgaImagesPaginator.paginate` method:

- `DryRun`: `bool`
- `FpgaImageIds`: `Sequence`\[`str`\]
- `Owners`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFpgaImagesPaginator.paginate` returns
`_PageIterator`\[[DescribeFpgaImagesResultTypeDef](./type_defs.md#describefpgaimagesresulttypedef)\].

<a id="describehostreservationofferingspaginator"></a>

## DescribeHostReservationOfferingsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_host_reservation_offerings")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeHostReservationOfferingsPaginator

def get_describe_host_reservation_offerings_paginator() -> DescribeHostReservationOfferingsPaginator:
    return Session().create_client("ec2").get_paginator("describe_host_reservation_offerings")
```

Boto3 documentation:
[EC2.Paginator.DescribeHostReservationOfferings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeHostReservationOfferings)

Arguments for `DescribeHostReservationOfferingsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxDuration`: `int`
- `MinDuration`: `int`
- `OfferingId`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeHostReservationOfferingsPaginator.paginate` returns
`_PageIterator`\[[DescribeHostReservationOfferingsResultTypeDef](./type_defs.md#describehostreservationofferingsresulttypedef)\].

<a id="describehostreservationspaginator"></a>

## DescribeHostReservationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_host_reservations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeHostReservationsPaginator

def get_describe_host_reservations_paginator() -> DescribeHostReservationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_host_reservations")
```

Boto3 documentation:
[EC2.Paginator.DescribeHostReservations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeHostReservations)

Arguments for `DescribeHostReservationsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `HostReservationIdSet`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeHostReservationsPaginator.paginate` returns
`_PageIterator`\[[DescribeHostReservationsResultTypeDef](./type_defs.md#describehostreservationsresulttypedef)\].

<a id="describehostspaginator"></a>

## DescribeHostsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_hosts")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeHostsPaginator

def get_describe_hosts_paginator() -> DescribeHostsPaginator:
    return Session().create_client("ec2").get_paginator("describe_hosts")
```

Boto3 documentation:
[EC2.Paginator.DescribeHosts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeHosts)

Arguments for `DescribeHostsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `HostIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeHostsPaginator.paginate` returns
`_PageIterator`\[[DescribeHostsResultTypeDef](./type_defs.md#describehostsresulttypedef)\].

<a id="describeiaminstanceprofileassociationspaginator"></a>

## DescribeIamInstanceProfileAssociationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_iam_instance_profile_associations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeIamInstanceProfileAssociationsPaginator

def get_describe_iam_instance_profile_associations_paginator() -> DescribeIamInstanceProfileAssociationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_iam_instance_profile_associations")
```

Boto3 documentation:
[EC2.Paginator.DescribeIamInstanceProfileAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeIamInstanceProfileAssociations)

Arguments for `DescribeIamInstanceProfileAssociationsPaginator.paginate`
method:

- `AssociationIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeIamInstanceProfileAssociationsPaginator.paginate` returns
`_PageIterator`\[[DescribeIamInstanceProfileAssociationsResultTypeDef](./type_defs.md#describeiaminstanceprofileassociationsresulttypedef)\].

<a id="describeimportimagetaskspaginator"></a>

## DescribeImportImageTasksPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_import_image_tasks")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeImportImageTasksPaginator

def get_describe_import_image_tasks_paginator() -> DescribeImportImageTasksPaginator:
    return Session().create_client("ec2").get_paginator("describe_import_image_tasks")
```

Boto3 documentation:
[EC2.Paginator.DescribeImportImageTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeImportImageTasks)

Arguments for `DescribeImportImageTasksPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ImportTaskIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeImportImageTasksPaginator.paginate` returns
`_PageIterator`\[[DescribeImportImageTasksResultTypeDef](./type_defs.md#describeimportimagetasksresulttypedef)\].

<a id="describeimportsnapshottaskspaginator"></a>

## DescribeImportSnapshotTasksPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_import_snapshot_tasks")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeImportSnapshotTasksPaginator

def get_describe_import_snapshot_tasks_paginator() -> DescribeImportSnapshotTasksPaginator:
    return Session().create_client("ec2").get_paginator("describe_import_snapshot_tasks")
```

Boto3 documentation:
[EC2.Paginator.DescribeImportSnapshotTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeImportSnapshotTasks)

Arguments for `DescribeImportSnapshotTasksPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ImportTaskIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeImportSnapshotTasksPaginator.paginate` returns
`_PageIterator`\[[DescribeImportSnapshotTasksResultTypeDef](./type_defs.md#describeimportsnapshottasksresulttypedef)\].

<a id="describeinstancecreditspecificationspaginator"></a>

## DescribeInstanceCreditSpecificationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_instance_credit_specifications")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeInstanceCreditSpecificationsPaginator

def get_describe_instance_credit_specifications_paginator() -> DescribeInstanceCreditSpecificationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_instance_credit_specifications")
```

Boto3 documentation:
[EC2.Paginator.DescribeInstanceCreditSpecifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeInstanceCreditSpecifications)

Arguments for `DescribeInstanceCreditSpecificationsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `InstanceIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstanceCreditSpecificationsPaginator.paginate` returns
`_PageIterator`\[[DescribeInstanceCreditSpecificationsResultTypeDef](./type_defs.md#describeinstancecreditspecificationsresulttypedef)\].

<a id="describeinstanceeventwindowspaginator"></a>

## DescribeInstanceEventWindowsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_instance_event_windows")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeInstanceEventWindowsPaginator

def get_describe_instance_event_windows_paginator() -> DescribeInstanceEventWindowsPaginator:
    return Session().create_client("ec2").get_paginator("describe_instance_event_windows")
```

Boto3 documentation:
[EC2.Paginator.DescribeInstanceEventWindows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeInstanceEventWindows)

Arguments for `DescribeInstanceEventWindowsPaginator.paginate` method:

- `DryRun`: `bool`
- `InstanceEventWindowIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstanceEventWindowsPaginator.paginate` returns
`_PageIterator`\[[DescribeInstanceEventWindowsResultTypeDef](./type_defs.md#describeinstanceeventwindowsresulttypedef)\].

<a id="describeinstancestatuspaginator"></a>

## DescribeInstanceStatusPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_instance_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeInstanceStatusPaginator

def get_describe_instance_status_paginator() -> DescribeInstanceStatusPaginator:
    return Session().create_client("ec2").get_paginator("describe_instance_status")
```

Boto3 documentation:
[EC2.Paginator.DescribeInstanceStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeInstanceStatus)

Arguments for `DescribeInstanceStatusPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `InstanceIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `IncludeAllInstances`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstanceStatusPaginator.paginate` returns
`_PageIterator`\[[DescribeInstanceStatusResultTypeDef](./type_defs.md#describeinstancestatusresulttypedef)\].

<a id="describeinstancetypeofferingspaginator"></a>

## DescribeInstanceTypeOfferingsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_instance_type_offerings")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeInstanceTypeOfferingsPaginator

def get_describe_instance_type_offerings_paginator() -> DescribeInstanceTypeOfferingsPaginator:
    return Session().create_client("ec2").get_paginator("describe_instance_type_offerings")
```

Boto3 documentation:
[EC2.Paginator.DescribeInstanceTypeOfferings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeInstanceTypeOfferings)

Arguments for `DescribeInstanceTypeOfferingsPaginator.paginate` method:

- `DryRun`: `bool`
- `LocationType`: [LocationTypeType](./literals.md#locationtypetype)
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstanceTypeOfferingsPaginator.paginate` returns
`_PageIterator`\[[DescribeInstanceTypeOfferingsResultTypeDef](./type_defs.md#describeinstancetypeofferingsresulttypedef)\].

<a id="describeinstancetypespaginator"></a>

## DescribeInstanceTypesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_instance_types")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeInstanceTypesPaginator

def get_describe_instance_types_paginator() -> DescribeInstanceTypesPaginator:
    return Session().create_client("ec2").get_paginator("describe_instance_types")
```

Boto3 documentation:
[EC2.Paginator.DescribeInstanceTypes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeInstanceTypes)

Arguments for `DescribeInstanceTypesPaginator.paginate` method:

- `DryRun`: `bool`
- `InstanceTypes`:
  `Sequence`\[[InstanceTypeType](./literals.md#instancetypetype)\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstanceTypesPaginator.paginate` returns
`_PageIterator`\[[DescribeInstanceTypesResultTypeDef](./type_defs.md#describeinstancetypesresulttypedef)\].

<a id="describeinstancespaginator"></a>

## DescribeInstancesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_instances")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeInstancesPaginator

def get_describe_instances_paginator() -> DescribeInstancesPaginator:
    return Session().create_client("ec2").get_paginator("describe_instances")
```

Boto3 documentation:
[EC2.Paginator.DescribeInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeInstances)

Arguments for `DescribeInstancesPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `InstanceIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstancesPaginator.paginate` returns
`_PageIterator`\[[DescribeInstancesResultTypeDef](./type_defs.md#describeinstancesresulttypedef)\].

<a id="describeinternetgatewayspaginator"></a>

## DescribeInternetGatewaysPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_internet_gateways")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeInternetGatewaysPaginator

def get_describe_internet_gateways_paginator() -> DescribeInternetGatewaysPaginator:
    return Session().create_client("ec2").get_paginator("describe_internet_gateways")
```

Boto3 documentation:
[EC2.Paginator.DescribeInternetGateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeInternetGateways)

Arguments for `DescribeInternetGatewaysPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `InternetGatewayIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInternetGatewaysPaginator.paginate` returns
`_PageIterator`\[[DescribeInternetGatewaysResultTypeDef](./type_defs.md#describeinternetgatewaysresulttypedef)\].

<a id="describeipampoolspaginator"></a>

## DescribeIpamPoolsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_ipam_pools")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeIpamPoolsPaginator

def get_describe_ipam_pools_paginator() -> DescribeIpamPoolsPaginator:
    return Session().create_client("ec2").get_paginator("describe_ipam_pools")
```

Boto3 documentation:
[EC2.Paginator.DescribeIpamPools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeIpamPools)

Arguments for `DescribeIpamPoolsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IpamPoolIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeIpamPoolsPaginator.paginate` returns
`_PageIterator`\[[DescribeIpamPoolsResultTypeDef](./type_defs.md#describeipampoolsresulttypedef)\].

<a id="describeipamscopespaginator"></a>

## DescribeIpamScopesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_ipam_scopes")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeIpamScopesPaginator

def get_describe_ipam_scopes_paginator() -> DescribeIpamScopesPaginator:
    return Session().create_client("ec2").get_paginator("describe_ipam_scopes")
```

Boto3 documentation:
[EC2.Paginator.DescribeIpamScopes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeIpamScopes)

Arguments for `DescribeIpamScopesPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IpamScopeIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeIpamScopesPaginator.paginate` returns
`_PageIterator`\[[DescribeIpamScopesResultTypeDef](./type_defs.md#describeipamscopesresulttypedef)\].

<a id="describeipamspaginator"></a>

## DescribeIpamsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_ipams")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeIpamsPaginator

def get_describe_ipams_paginator() -> DescribeIpamsPaginator:
    return Session().create_client("ec2").get_paginator("describe_ipams")
```

Boto3 documentation:
[EC2.Paginator.DescribeIpams](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeIpams)

Arguments for `DescribeIpamsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IpamIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeIpamsPaginator.paginate` returns
`_PageIterator`\[[DescribeIpamsResultTypeDef](./type_defs.md#describeipamsresulttypedef)\].

<a id="describeipv6poolspaginator"></a>

## DescribeIpv6PoolsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_ipv6_pools")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeIpv6PoolsPaginator

def get_describe_ipv6_pools_paginator() -> DescribeIpv6PoolsPaginator:
    return Session().create_client("ec2").get_paginator("describe_ipv6_pools")
```

Boto3 documentation:
[EC2.Paginator.DescribeIpv6Pools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeIpv6Pools)

Arguments for `DescribeIpv6PoolsPaginator.paginate` method:

- `PoolIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeIpv6PoolsPaginator.paginate` returns
`_PageIterator`\[[DescribeIpv6PoolsResultTypeDef](./type_defs.md#describeipv6poolsresulttypedef)\].

<a id="describelaunchtemplateversionspaginator"></a>

## DescribeLaunchTemplateVersionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_launch_template_versions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLaunchTemplateVersionsPaginator

def get_describe_launch_template_versions_paginator() -> DescribeLaunchTemplateVersionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_launch_template_versions")
```

Boto3 documentation:
[EC2.Paginator.DescribeLaunchTemplateVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLaunchTemplateVersions)

Arguments for `DescribeLaunchTemplateVersionsPaginator.paginate` method:

- `DryRun`: `bool`
- `LaunchTemplateId`: `str`
- `LaunchTemplateName`: `str`
- `Versions`: `Sequence`\[`str`\]
- `MinVersion`: `str`
- `MaxVersion`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLaunchTemplateVersionsPaginator.paginate` returns
`_PageIterator`\[[DescribeLaunchTemplateVersionsResultTypeDef](./type_defs.md#describelaunchtemplateversionsresulttypedef)\].

<a id="describelaunchtemplatespaginator"></a>

## DescribeLaunchTemplatesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_launch_templates")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLaunchTemplatesPaginator

def get_describe_launch_templates_paginator() -> DescribeLaunchTemplatesPaginator:
    return Session().create_client("ec2").get_paginator("describe_launch_templates")
```

Boto3 documentation:
[EC2.Paginator.DescribeLaunchTemplates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLaunchTemplates)

Arguments for `DescribeLaunchTemplatesPaginator.paginate` method:

- `DryRun`: `bool`
- `LaunchTemplateIds`: `Sequence`\[`str`\]
- `LaunchTemplateNames`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLaunchTemplatesPaginator.paginate` returns
`_PageIterator`\[[DescribeLaunchTemplatesResultTypeDef](./type_defs.md#describelaunchtemplatesresulttypedef)\].

<a id="describelocalgatewayroutetablevirtualinterfacegroupassociationspaginator"></a>

## DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_local_gateway_route_table_virtual_interface_group_associations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator

def get_describe_local_gateway_route_table_virtual_interface_group_associations_paginator() -> DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_local_gateway_route_table_virtual_interface_group_associations")
```

Boto3 documentation:
[EC2.Paginator.DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociations)

Arguments for
`DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator.paginate`
method:

- `LocalGatewayRouteTableVirtualInterfaceGroupAssociationIds`:
  `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator.paginate`
returns
`_PageIterator`\[[DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsResultTypeDef](./type_defs.md#describelocalgatewayroutetablevirtualinterfacegroupassociationsresulttypedef)\].

<a id="describelocalgatewayroutetablevpcassociationspaginator"></a>

## DescribeLocalGatewayRouteTableVpcAssociationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_local_gateway_route_table_vpc_associations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayRouteTableVpcAssociationsPaginator

def get_describe_local_gateway_route_table_vpc_associations_paginator() -> DescribeLocalGatewayRouteTableVpcAssociationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_local_gateway_route_table_vpc_associations")
```

Boto3 documentation:
[EC2.Paginator.DescribeLocalGatewayRouteTableVpcAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLocalGatewayRouteTableVpcAssociations)

Arguments for `DescribeLocalGatewayRouteTableVpcAssociationsPaginator.paginate`
method:

- `LocalGatewayRouteTableVpcAssociationIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLocalGatewayRouteTableVpcAssociationsPaginator.paginate` returns
`_PageIterator`\[[DescribeLocalGatewayRouteTableVpcAssociationsResultTypeDef](./type_defs.md#describelocalgatewayroutetablevpcassociationsresulttypedef)\].

<a id="describelocalgatewayroutetablespaginator"></a>

## DescribeLocalGatewayRouteTablesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_local_gateway_route_tables")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayRouteTablesPaginator

def get_describe_local_gateway_route_tables_paginator() -> DescribeLocalGatewayRouteTablesPaginator:
    return Session().create_client("ec2").get_paginator("describe_local_gateway_route_tables")
```

Boto3 documentation:
[EC2.Paginator.DescribeLocalGatewayRouteTables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLocalGatewayRouteTables)

Arguments for `DescribeLocalGatewayRouteTablesPaginator.paginate` method:

- `LocalGatewayRouteTableIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLocalGatewayRouteTablesPaginator.paginate` returns
`_PageIterator`\[[DescribeLocalGatewayRouteTablesResultTypeDef](./type_defs.md#describelocalgatewayroutetablesresulttypedef)\].

<a id="describelocalgatewayvirtualinterfacegroupspaginator"></a>

## DescribeLocalGatewayVirtualInterfaceGroupsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_local_gateway_virtual_interface_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayVirtualInterfaceGroupsPaginator

def get_describe_local_gateway_virtual_interface_groups_paginator() -> DescribeLocalGatewayVirtualInterfaceGroupsPaginator:
    return Session().create_client("ec2").get_paginator("describe_local_gateway_virtual_interface_groups")
```

Boto3 documentation:
[EC2.Paginator.DescribeLocalGatewayVirtualInterfaceGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLocalGatewayVirtualInterfaceGroups)

Arguments for `DescribeLocalGatewayVirtualInterfaceGroupsPaginator.paginate`
method:

- `LocalGatewayVirtualInterfaceGroupIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLocalGatewayVirtualInterfaceGroupsPaginator.paginate` returns
`_PageIterator`\[[DescribeLocalGatewayVirtualInterfaceGroupsResultTypeDef](./type_defs.md#describelocalgatewayvirtualinterfacegroupsresulttypedef)\].

<a id="describelocalgatewayvirtualinterfacespaginator"></a>

## DescribeLocalGatewayVirtualInterfacesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_local_gateway_virtual_interfaces")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayVirtualInterfacesPaginator

def get_describe_local_gateway_virtual_interfaces_paginator() -> DescribeLocalGatewayVirtualInterfacesPaginator:
    return Session().create_client("ec2").get_paginator("describe_local_gateway_virtual_interfaces")
```

Boto3 documentation:
[EC2.Paginator.DescribeLocalGatewayVirtualInterfaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLocalGatewayVirtualInterfaces)

Arguments for `DescribeLocalGatewayVirtualInterfacesPaginator.paginate` method:

- `LocalGatewayVirtualInterfaceIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLocalGatewayVirtualInterfacesPaginator.paginate` returns
`_PageIterator`\[[DescribeLocalGatewayVirtualInterfacesResultTypeDef](./type_defs.md#describelocalgatewayvirtualinterfacesresulttypedef)\].

<a id="describelocalgatewayspaginator"></a>

## DescribeLocalGatewaysPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_local_gateways")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewaysPaginator

def get_describe_local_gateways_paginator() -> DescribeLocalGatewaysPaginator:
    return Session().create_client("ec2").get_paginator("describe_local_gateways")
```

Boto3 documentation:
[EC2.Paginator.DescribeLocalGateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeLocalGateways)

Arguments for `DescribeLocalGatewaysPaginator.paginate` method:

- `LocalGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeLocalGatewaysPaginator.paginate` returns
`_PageIterator`\[[DescribeLocalGatewaysResultTypeDef](./type_defs.md#describelocalgatewaysresulttypedef)\].

<a id="describemanagedprefixlistspaginator"></a>

## DescribeManagedPrefixListsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_managed_prefix_lists")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeManagedPrefixListsPaginator

def get_describe_managed_prefix_lists_paginator() -> DescribeManagedPrefixListsPaginator:
    return Session().create_client("ec2").get_paginator("describe_managed_prefix_lists")
```

Boto3 documentation:
[EC2.Paginator.DescribeManagedPrefixLists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeManagedPrefixLists)

Arguments for `DescribeManagedPrefixListsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PrefixListIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeManagedPrefixListsPaginator.paginate` returns
`_PageIterator`\[[DescribeManagedPrefixListsResultTypeDef](./type_defs.md#describemanagedprefixlistsresulttypedef)\].

<a id="describemovingaddressespaginator"></a>

## DescribeMovingAddressesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_moving_addresses")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeMovingAddressesPaginator

def get_describe_moving_addresses_paginator() -> DescribeMovingAddressesPaginator:
    return Session().create_client("ec2").get_paginator("describe_moving_addresses")
```

Boto3 documentation:
[EC2.Paginator.DescribeMovingAddresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeMovingAddresses)

Arguments for `DescribeMovingAddressesPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PublicIps`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMovingAddressesPaginator.paginate` returns
`_PageIterator`\[[DescribeMovingAddressesResultTypeDef](./type_defs.md#describemovingaddressesresulttypedef)\].

<a id="describenatgatewayspaginator"></a>

## DescribeNatGatewaysPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_nat_gateways")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNatGatewaysPaginator

def get_describe_nat_gateways_paginator() -> DescribeNatGatewaysPaginator:
    return Session().create_client("ec2").get_paginator("describe_nat_gateways")
```

Boto3 documentation:
[EC2.Paginator.DescribeNatGateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNatGateways)

Arguments for `DescribeNatGatewaysPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NatGatewayIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNatGatewaysPaginator.paginate` returns
`_PageIterator`\[[DescribeNatGatewaysResultTypeDef](./type_defs.md#describenatgatewaysresulttypedef)\].

<a id="describenetworkaclspaginator"></a>

## DescribeNetworkAclsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_network_acls")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNetworkAclsPaginator

def get_describe_network_acls_paginator() -> DescribeNetworkAclsPaginator:
    return Session().create_client("ec2").get_paginator("describe_network_acls")
```

Boto3 documentation:
[EC2.Paginator.DescribeNetworkAcls](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNetworkAcls)

Arguments for `DescribeNetworkAclsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `NetworkAclIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNetworkAclsPaginator.paginate` returns
`_PageIterator`\[[DescribeNetworkAclsResultTypeDef](./type_defs.md#describenetworkaclsresulttypedef)\].

<a id="describenetworkinsightsaccessscopeanalysespaginator"></a>

## DescribeNetworkInsightsAccessScopeAnalysesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_network_insights_access_scope_analyses")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsAccessScopeAnalysesPaginator

def get_describe_network_insights_access_scope_analyses_paginator() -> DescribeNetworkInsightsAccessScopeAnalysesPaginator:
    return Session().create_client("ec2").get_paginator("describe_network_insights_access_scope_analyses")
```

Boto3 documentation:
[EC2.Paginator.DescribeNetworkInsightsAccessScopeAnalyses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNetworkInsightsAccessScopeAnalyses)

Arguments for `DescribeNetworkInsightsAccessScopeAnalysesPaginator.paginate`
method:

- `NetworkInsightsAccessScopeAnalysisIds`: `Sequence`\[`str`\]
- `NetworkInsightsAccessScopeId`: `str`
- `AnalysisStartTimeBegin`: `Union`\[`datetime`, `str`\]
- `AnalysisStartTimeEnd`: `Union`\[`datetime`, `str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNetworkInsightsAccessScopeAnalysesPaginator.paginate` returns
`_PageIterator`\[[DescribeNetworkInsightsAccessScopeAnalysesResultTypeDef](./type_defs.md#describenetworkinsightsaccessscopeanalysesresulttypedef)\].

<a id="describenetworkinsightsaccessscopespaginator"></a>

## DescribeNetworkInsightsAccessScopesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_network_insights_access_scopes")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsAccessScopesPaginator

def get_describe_network_insights_access_scopes_paginator() -> DescribeNetworkInsightsAccessScopesPaginator:
    return Session().create_client("ec2").get_paginator("describe_network_insights_access_scopes")
```

Boto3 documentation:
[EC2.Paginator.DescribeNetworkInsightsAccessScopes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNetworkInsightsAccessScopes)

Arguments for `DescribeNetworkInsightsAccessScopesPaginator.paginate` method:

- `NetworkInsightsAccessScopeIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNetworkInsightsAccessScopesPaginator.paginate` returns
`_PageIterator`\[[DescribeNetworkInsightsAccessScopesResultTypeDef](./type_defs.md#describenetworkinsightsaccessscopesresulttypedef)\].

<a id="describenetworkinsightsanalysespaginator"></a>

## DescribeNetworkInsightsAnalysesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_network_insights_analyses")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsAnalysesPaginator

def get_describe_network_insights_analyses_paginator() -> DescribeNetworkInsightsAnalysesPaginator:
    return Session().create_client("ec2").get_paginator("describe_network_insights_analyses")
```

Boto3 documentation:
[EC2.Paginator.DescribeNetworkInsightsAnalyses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNetworkInsightsAnalyses)

Arguments for `DescribeNetworkInsightsAnalysesPaginator.paginate` method:

- `NetworkInsightsAnalysisIds`: `Sequence`\[`str`\]
- `NetworkInsightsPathId`: `str`
- `AnalysisStartTime`: `Union`\[`datetime`, `str`\]
- `AnalysisEndTime`: `Union`\[`datetime`, `str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNetworkInsightsAnalysesPaginator.paginate` returns
`_PageIterator`\[[DescribeNetworkInsightsAnalysesResultTypeDef](./type_defs.md#describenetworkinsightsanalysesresulttypedef)\].

<a id="describenetworkinsightspathspaginator"></a>

## DescribeNetworkInsightsPathsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_network_insights_paths")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsPathsPaginator

def get_describe_network_insights_paths_paginator() -> DescribeNetworkInsightsPathsPaginator:
    return Session().create_client("ec2").get_paginator("describe_network_insights_paths")
```

Boto3 documentation:
[EC2.Paginator.DescribeNetworkInsightsPaths](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNetworkInsightsPaths)

Arguments for `DescribeNetworkInsightsPathsPaginator.paginate` method:

- `NetworkInsightsPathIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNetworkInsightsPathsPaginator.paginate` returns
`_PageIterator`\[[DescribeNetworkInsightsPathsResultTypeDef](./type_defs.md#describenetworkinsightspathsresulttypedef)\].

<a id="describenetworkinterfacepermissionspaginator"></a>

## DescribeNetworkInterfacePermissionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_network_interface_permissions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNetworkInterfacePermissionsPaginator

def get_describe_network_interface_permissions_paginator() -> DescribeNetworkInterfacePermissionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_network_interface_permissions")
```

Boto3 documentation:
[EC2.Paginator.DescribeNetworkInterfacePermissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNetworkInterfacePermissions)

Arguments for `DescribeNetworkInterfacePermissionsPaginator.paginate` method:

- `NetworkInterfacePermissionIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNetworkInterfacePermissionsPaginator.paginate` returns
`_PageIterator`\[[DescribeNetworkInterfacePermissionsResultTypeDef](./type_defs.md#describenetworkinterfacepermissionsresulttypedef)\].

<a id="describenetworkinterfacespaginator"></a>

## DescribeNetworkInterfacesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_network_interfaces")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeNetworkInterfacesPaginator

def get_describe_network_interfaces_paginator() -> DescribeNetworkInterfacesPaginator:
    return Session().create_client("ec2").get_paginator("describe_network_interfaces")
```

Boto3 documentation:
[EC2.Paginator.DescribeNetworkInterfaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeNetworkInterfaces)

Arguments for `DescribeNetworkInterfacesPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `NetworkInterfaceIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeNetworkInterfacesPaginator.paginate` returns
`_PageIterator`\[[DescribeNetworkInterfacesResultTypeDef](./type_defs.md#describenetworkinterfacesresulttypedef)\].

<a id="describeprefixlistspaginator"></a>

## DescribePrefixListsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_prefix_lists")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribePrefixListsPaginator

def get_describe_prefix_lists_paginator() -> DescribePrefixListsPaginator:
    return Session().create_client("ec2").get_paginator("describe_prefix_lists")
```

Boto3 documentation:
[EC2.Paginator.DescribePrefixLists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribePrefixLists)

Arguments for `DescribePrefixListsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PrefixListIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePrefixListsPaginator.paginate` returns
`_PageIterator`\[[DescribePrefixListsResultTypeDef](./type_defs.md#describeprefixlistsresulttypedef)\].

<a id="describeprincipalidformatpaginator"></a>

## DescribePrincipalIdFormatPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_principal_id_format")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribePrincipalIdFormatPaginator

def get_describe_principal_id_format_paginator() -> DescribePrincipalIdFormatPaginator:
    return Session().create_client("ec2").get_paginator("describe_principal_id_format")
```

Boto3 documentation:
[EC2.Paginator.DescribePrincipalIdFormat](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribePrincipalIdFormat)

Arguments for `DescribePrincipalIdFormatPaginator.paginate` method:

- `DryRun`: `bool`
- `Resources`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePrincipalIdFormatPaginator.paginate` returns
`_PageIterator`\[[DescribePrincipalIdFormatResultTypeDef](./type_defs.md#describeprincipalidformatresulttypedef)\].

<a id="describepublicipv4poolspaginator"></a>

## DescribePublicIpv4PoolsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_public_ipv4_pools")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribePublicIpv4PoolsPaginator

def get_describe_public_ipv4_pools_paginator() -> DescribePublicIpv4PoolsPaginator:
    return Session().create_client("ec2").get_paginator("describe_public_ipv4_pools")
```

Boto3 documentation:
[EC2.Paginator.DescribePublicIpv4Pools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribePublicIpv4Pools)

Arguments for `DescribePublicIpv4PoolsPaginator.paginate` method:

- `PoolIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePublicIpv4PoolsPaginator.paginate` returns
`_PageIterator`\[[DescribePublicIpv4PoolsResultTypeDef](./type_defs.md#describepublicipv4poolsresulttypedef)\].

<a id="describereplacerootvolumetaskspaginator"></a>

## DescribeReplaceRootVolumeTasksPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_replace_root_volume_tasks")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeReplaceRootVolumeTasksPaginator

def get_describe_replace_root_volume_tasks_paginator() -> DescribeReplaceRootVolumeTasksPaginator:
    return Session().create_client("ec2").get_paginator("describe_replace_root_volume_tasks")
```

Boto3 documentation:
[EC2.Paginator.DescribeReplaceRootVolumeTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeReplaceRootVolumeTasks)

Arguments for `DescribeReplaceRootVolumeTasksPaginator.paginate` method:

- `ReplaceRootVolumeTaskIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeReplaceRootVolumeTasksPaginator.paginate` returns
`_PageIterator`\[[DescribeReplaceRootVolumeTasksResultTypeDef](./type_defs.md#describereplacerootvolumetasksresulttypedef)\].

<a id="describereservedinstancesmodificationspaginator"></a>

## DescribeReservedInstancesModificationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_reserved_instances_modifications")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeReservedInstancesModificationsPaginator

def get_describe_reserved_instances_modifications_paginator() -> DescribeReservedInstancesModificationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_reserved_instances_modifications")
```

Boto3 documentation:
[EC2.Paginator.DescribeReservedInstancesModifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeReservedInstancesModifications)

Arguments for `DescribeReservedInstancesModificationsPaginator.paginate`
method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ReservedInstancesModificationIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeReservedInstancesModificationsPaginator.paginate` returns
`_PageIterator`\[[DescribeReservedInstancesModificationsResultTypeDef](./type_defs.md#describereservedinstancesmodificationsresulttypedef)\].

<a id="describereservedinstancesofferingspaginator"></a>

## DescribeReservedInstancesOfferingsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_reserved_instances_offerings")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeReservedInstancesOfferingsPaginator

def get_describe_reserved_instances_offerings_paginator() -> DescribeReservedInstancesOfferingsPaginator:
    return Session().create_client("ec2").get_paginator("describe_reserved_instances_offerings")
```

Boto3 documentation:
[EC2.Paginator.DescribeReservedInstancesOfferings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeReservedInstancesOfferings)

Arguments for `DescribeReservedInstancesOfferingsPaginator.paginate` method:

- `AvailabilityZone`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IncludeMarketplace`: `bool`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `MaxDuration`: `int`
- `MaxInstanceCount`: `int`
- `MinDuration`: `int`
- `OfferingClass`: [OfferingClassTypeType](./literals.md#offeringclasstypetype)
- `ProductDescription`:
  [RIProductDescriptionType](./literals.md#riproductdescriptiontype)
- `ReservedInstancesOfferingIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `InstanceTenancy`: [TenancyType](./literals.md#tenancytype)
- `OfferingType`:
  [OfferingTypeValuesType](./literals.md#offeringtypevaluestype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeReservedInstancesOfferingsPaginator.paginate` returns
`_PageIterator`\[[DescribeReservedInstancesOfferingsResultTypeDef](./type_defs.md#describereservedinstancesofferingsresulttypedef)\].

<a id="describeroutetablespaginator"></a>

## DescribeRouteTablesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_route_tables")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeRouteTablesPaginator

def get_describe_route_tables_paginator() -> DescribeRouteTablesPaginator:
    return Session().create_client("ec2").get_paginator("describe_route_tables")
```

Boto3 documentation:
[EC2.Paginator.DescribeRouteTables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeRouteTables)

Arguments for `DescribeRouteTablesPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `RouteTableIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeRouteTablesPaginator.paginate` returns
`_PageIterator`\[[DescribeRouteTablesResultTypeDef](./type_defs.md#describeroutetablesresulttypedef)\].

<a id="describescheduledinstanceavailabilitypaginator"></a>

## DescribeScheduledInstanceAvailabilityPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_scheduled_instance_availability")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeScheduledInstanceAvailabilityPaginator

def get_describe_scheduled_instance_availability_paginator() -> DescribeScheduledInstanceAvailabilityPaginator:
    return Session().create_client("ec2").get_paginator("describe_scheduled_instance_availability")
```

Boto3 documentation:
[EC2.Paginator.DescribeScheduledInstanceAvailability](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeScheduledInstanceAvailability)

Arguments for `DescribeScheduledInstanceAvailabilityPaginator.paginate` method:

- `FirstSlotStartTimeRange`:
  [SlotDateTimeRangeRequestTypeDef](./type_defs.md#slotdatetimerangerequesttypedef)
  *(required)*
- `Recurrence`:
  [ScheduledInstanceRecurrenceRequestTypeDef](./type_defs.md#scheduledinstancerecurrencerequesttypedef)
  *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxSlotDurationInHours`: `int`
- `MinSlotDurationInHours`: `int`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeScheduledInstanceAvailabilityPaginator.paginate` returns
`_PageIterator`\[[DescribeScheduledInstanceAvailabilityResultTypeDef](./type_defs.md#describescheduledinstanceavailabilityresulttypedef)\].

<a id="describescheduledinstancespaginator"></a>

## DescribeScheduledInstancesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_scheduled_instances")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeScheduledInstancesPaginator

def get_describe_scheduled_instances_paginator() -> DescribeScheduledInstancesPaginator:
    return Session().create_client("ec2").get_paginator("describe_scheduled_instances")
```

Boto3 documentation:
[EC2.Paginator.DescribeScheduledInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeScheduledInstances)

Arguments for `DescribeScheduledInstancesPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ScheduledInstanceIds`: `Sequence`\[`str`\]
- `SlotStartTimeRange`:
  [SlotStartTimeRangeRequestTypeDef](./type_defs.md#slotstarttimerangerequesttypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeScheduledInstancesPaginator.paginate` returns
`_PageIterator`\[[DescribeScheduledInstancesResultTypeDef](./type_defs.md#describescheduledinstancesresulttypedef)\].

<a id="describesecuritygrouprulespaginator"></a>

## DescribeSecurityGroupRulesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_security_group_rules")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSecurityGroupRulesPaginator

def get_describe_security_group_rules_paginator() -> DescribeSecurityGroupRulesPaginator:
    return Session().create_client("ec2").get_paginator("describe_security_group_rules")
```

Boto3 documentation:
[EC2.Paginator.DescribeSecurityGroupRules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSecurityGroupRules)

Arguments for `DescribeSecurityGroupRulesPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `SecurityGroupRuleIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSecurityGroupRulesPaginator.paginate` returns
`_PageIterator`\[[DescribeSecurityGroupRulesResultTypeDef](./type_defs.md#describesecuritygrouprulesresulttypedef)\].

<a id="describesecuritygroupspaginator"></a>

## DescribeSecurityGroupsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_security_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSecurityGroupsPaginator

def get_describe_security_groups_paginator() -> DescribeSecurityGroupsPaginator:
    return Session().create_client("ec2").get_paginator("describe_security_groups")
```

Boto3 documentation:
[EC2.Paginator.DescribeSecurityGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSecurityGroups)

Arguments for `DescribeSecurityGroupsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `GroupIds`: `Sequence`\[`str`\]
- `GroupNames`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSecurityGroupsPaginator.paginate` returns
`_PageIterator`\[[DescribeSecurityGroupsResultTypeDef](./type_defs.md#describesecuritygroupsresulttypedef)\].

<a id="describesnapshottierstatuspaginator"></a>

## DescribeSnapshotTierStatusPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_snapshot_tier_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSnapshotTierStatusPaginator

def get_describe_snapshot_tier_status_paginator() -> DescribeSnapshotTierStatusPaginator:
    return Session().create_client("ec2").get_paginator("describe_snapshot_tier_status")
```

Boto3 documentation:
[EC2.Paginator.DescribeSnapshotTierStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSnapshotTierStatus)

Arguments for `DescribeSnapshotTierStatusPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSnapshotTierStatusPaginator.paginate` returns
`_PageIterator`\[[DescribeSnapshotTierStatusResultTypeDef](./type_defs.md#describesnapshottierstatusresulttypedef)\].

<a id="describesnapshotspaginator"></a>

## DescribeSnapshotsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_snapshots")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSnapshotsPaginator

def get_describe_snapshots_paginator() -> DescribeSnapshotsPaginator:
    return Session().create_client("ec2").get_paginator("describe_snapshots")
```

Boto3 documentation:
[EC2.Paginator.DescribeSnapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSnapshots)

Arguments for `DescribeSnapshotsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `OwnerIds`: `Sequence`\[`str`\]
- `RestorableByUserIds`: `Sequence`\[`str`\]
- `SnapshotIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSnapshotsPaginator.paginate` returns
`_PageIterator`\[[DescribeSnapshotsResultTypeDef](./type_defs.md#describesnapshotsresulttypedef)\].

<a id="describespotfleetinstancespaginator"></a>

## DescribeSpotFleetInstancesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_spot_fleet_instances")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSpotFleetInstancesPaginator

def get_describe_spot_fleet_instances_paginator() -> DescribeSpotFleetInstancesPaginator:
    return Session().create_client("ec2").get_paginator("describe_spot_fleet_instances")
```

Boto3 documentation:
[EC2.Paginator.DescribeSpotFleetInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSpotFleetInstances)

Arguments for `DescribeSpotFleetInstancesPaginator.paginate` method:

- `SpotFleetRequestId`: `str` *(required)*
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSpotFleetInstancesPaginator.paginate` returns
`_PageIterator`\[[DescribeSpotFleetInstancesResponseTypeDef](./type_defs.md#describespotfleetinstancesresponsetypedef)\].

<a id="describespotfleetrequestspaginator"></a>

## DescribeSpotFleetRequestsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_spot_fleet_requests")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSpotFleetRequestsPaginator

def get_describe_spot_fleet_requests_paginator() -> DescribeSpotFleetRequestsPaginator:
    return Session().create_client("ec2").get_paginator("describe_spot_fleet_requests")
```

Boto3 documentation:
[EC2.Paginator.DescribeSpotFleetRequests](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSpotFleetRequests)

Arguments for `DescribeSpotFleetRequestsPaginator.paginate` method:

- `DryRun`: `bool`
- `SpotFleetRequestIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSpotFleetRequestsPaginator.paginate` returns
`_PageIterator`\[[DescribeSpotFleetRequestsResponseTypeDef](./type_defs.md#describespotfleetrequestsresponsetypedef)\].

<a id="describespotinstancerequestspaginator"></a>

## DescribeSpotInstanceRequestsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_spot_instance_requests")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSpotInstanceRequestsPaginator

def get_describe_spot_instance_requests_paginator() -> DescribeSpotInstanceRequestsPaginator:
    return Session().create_client("ec2").get_paginator("describe_spot_instance_requests")
```

Boto3 documentation:
[EC2.Paginator.DescribeSpotInstanceRequests](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSpotInstanceRequests)

Arguments for `DescribeSpotInstanceRequestsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `SpotInstanceRequestIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSpotInstanceRequestsPaginator.paginate` returns
`_PageIterator`\[[DescribeSpotInstanceRequestsResultTypeDef](./type_defs.md#describespotinstancerequestsresulttypedef)\].

<a id="describespotpricehistorypaginator"></a>

## DescribeSpotPriceHistoryPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_spot_price_history")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSpotPriceHistoryPaginator

def get_describe_spot_price_history_paginator() -> DescribeSpotPriceHistoryPaginator:
    return Session().create_client("ec2").get_paginator("describe_spot_price_history")
```

Boto3 documentation:
[EC2.Paginator.DescribeSpotPriceHistory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSpotPriceHistory)

Arguments for `DescribeSpotPriceHistoryPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `AvailabilityZone`: `str`
- `DryRun`: `bool`
- `EndTime`: `Union`\[`datetime`, `str`\]
- `InstanceTypes`:
  `Sequence`\[[InstanceTypeType](./literals.md#instancetypetype)\]
- `ProductDescriptions`: `Sequence`\[`str`\]
- `StartTime`: `Union`\[`datetime`, `str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSpotPriceHistoryPaginator.paginate` returns
`_PageIterator`\[[DescribeSpotPriceHistoryResultTypeDef](./type_defs.md#describespotpricehistoryresulttypedef)\].

<a id="describestalesecuritygroupspaginator"></a>

## DescribeStaleSecurityGroupsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_stale_security_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeStaleSecurityGroupsPaginator

def get_describe_stale_security_groups_paginator() -> DescribeStaleSecurityGroupsPaginator:
    return Session().create_client("ec2").get_paginator("describe_stale_security_groups")
```

Boto3 documentation:
[EC2.Paginator.DescribeStaleSecurityGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeStaleSecurityGroups)

Arguments for `DescribeStaleSecurityGroupsPaginator.paginate` method:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeStaleSecurityGroupsPaginator.paginate` returns
`_PageIterator`\[[DescribeStaleSecurityGroupsResultTypeDef](./type_defs.md#describestalesecuritygroupsresulttypedef)\].

<a id="describestoreimagetaskspaginator"></a>

## DescribeStoreImageTasksPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_store_image_tasks")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeStoreImageTasksPaginator

def get_describe_store_image_tasks_paginator() -> DescribeStoreImageTasksPaginator:
    return Session().create_client("ec2").get_paginator("describe_store_image_tasks")
```

Boto3 documentation:
[EC2.Paginator.DescribeStoreImageTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeStoreImageTasks)

Arguments for `DescribeStoreImageTasksPaginator.paginate` method:

- `ImageIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeStoreImageTasksPaginator.paginate` returns
`_PageIterator`\[[DescribeStoreImageTasksResultTypeDef](./type_defs.md#describestoreimagetasksresulttypedef)\].

<a id="describesubnetspaginator"></a>

## DescribeSubnetsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_subnets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeSubnetsPaginator

def get_describe_subnets_paginator() -> DescribeSubnetsPaginator:
    return Session().create_client("ec2").get_paginator("describe_subnets")
```

Boto3 documentation:
[EC2.Paginator.DescribeSubnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeSubnets)

Arguments for `DescribeSubnetsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `SubnetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSubnetsPaginator.paginate` returns
`_PageIterator`\[[DescribeSubnetsResultTypeDef](./type_defs.md#describesubnetsresulttypedef)\].

<a id="describetagspaginator"></a>

## DescribeTagsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_tags")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTagsPaginator

def get_describe_tags_paginator() -> DescribeTagsPaginator:
    return Session().create_client("ec2").get_paginator("describe_tags")
```

Boto3 documentation:
[EC2.Paginator.DescribeTags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTags)

Arguments for `DescribeTagsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTagsPaginator.paginate` returns
`_PageIterator`\[[DescribeTagsResultTypeDef](./type_defs.md#describetagsresulttypedef)\].

<a id="describetrafficmirrorfilterspaginator"></a>

## DescribeTrafficMirrorFiltersPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_traffic_mirror_filters")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTrafficMirrorFiltersPaginator

def get_describe_traffic_mirror_filters_paginator() -> DescribeTrafficMirrorFiltersPaginator:
    return Session().create_client("ec2").get_paginator("describe_traffic_mirror_filters")
```

Boto3 documentation:
[EC2.Paginator.DescribeTrafficMirrorFilters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTrafficMirrorFilters)

Arguments for `DescribeTrafficMirrorFiltersPaginator.paginate` method:

- `TrafficMirrorFilterIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTrafficMirrorFiltersPaginator.paginate` returns
`_PageIterator`\[[DescribeTrafficMirrorFiltersResultTypeDef](./type_defs.md#describetrafficmirrorfiltersresulttypedef)\].

<a id="describetrafficmirrorsessionspaginator"></a>

## DescribeTrafficMirrorSessionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_traffic_mirror_sessions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTrafficMirrorSessionsPaginator

def get_describe_traffic_mirror_sessions_paginator() -> DescribeTrafficMirrorSessionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_traffic_mirror_sessions")
```

Boto3 documentation:
[EC2.Paginator.DescribeTrafficMirrorSessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTrafficMirrorSessions)

Arguments for `DescribeTrafficMirrorSessionsPaginator.paginate` method:

- `TrafficMirrorSessionIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTrafficMirrorSessionsPaginator.paginate` returns
`_PageIterator`\[[DescribeTrafficMirrorSessionsResultTypeDef](./type_defs.md#describetrafficmirrorsessionsresulttypedef)\].

<a id="describetrafficmirrortargetspaginator"></a>

## DescribeTrafficMirrorTargetsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_traffic_mirror_targets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTrafficMirrorTargetsPaginator

def get_describe_traffic_mirror_targets_paginator() -> DescribeTrafficMirrorTargetsPaginator:
    return Session().create_client("ec2").get_paginator("describe_traffic_mirror_targets")
```

Boto3 documentation:
[EC2.Paginator.DescribeTrafficMirrorTargets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTrafficMirrorTargets)

Arguments for `DescribeTrafficMirrorTargetsPaginator.paginate` method:

- `TrafficMirrorTargetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTrafficMirrorTargetsPaginator.paginate` returns
`_PageIterator`\[[DescribeTrafficMirrorTargetsResultTypeDef](./type_defs.md#describetrafficmirrortargetsresulttypedef)\].

<a id="describetransitgatewayattachmentspaginator"></a>

## DescribeTransitGatewayAttachmentsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateway_attachments")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayAttachmentsPaginator

def get_describe_transit_gateway_attachments_paginator() -> DescribeTransitGatewayAttachmentsPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateway_attachments")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGatewayAttachments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGatewayAttachments)

Arguments for `DescribeTransitGatewayAttachmentsPaginator.paginate` method:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewayAttachmentsPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewayAttachmentsResultTypeDef](./type_defs.md#describetransitgatewayattachmentsresulttypedef)\].

<a id="describetransitgatewayconnectpeerspaginator"></a>

## DescribeTransitGatewayConnectPeersPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateway_connect_peers")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayConnectPeersPaginator

def get_describe_transit_gateway_connect_peers_paginator() -> DescribeTransitGatewayConnectPeersPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateway_connect_peers")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGatewayConnectPeers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGatewayConnectPeers)

Arguments for `DescribeTransitGatewayConnectPeersPaginator.paginate` method:

- `TransitGatewayConnectPeerIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewayConnectPeersPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewayConnectPeersResultTypeDef](./type_defs.md#describetransitgatewayconnectpeersresulttypedef)\].

<a id="describetransitgatewayconnectspaginator"></a>

## DescribeTransitGatewayConnectsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateway_connects")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayConnectsPaginator

def get_describe_transit_gateway_connects_paginator() -> DescribeTransitGatewayConnectsPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateway_connects")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGatewayConnects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGatewayConnects)

Arguments for `DescribeTransitGatewayConnectsPaginator.paginate` method:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewayConnectsPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewayConnectsResultTypeDef](./type_defs.md#describetransitgatewayconnectsresulttypedef)\].

<a id="describetransitgatewaymulticastdomainspaginator"></a>

## DescribeTransitGatewayMulticastDomainsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateway_multicast_domains")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayMulticastDomainsPaginator

def get_describe_transit_gateway_multicast_domains_paginator() -> DescribeTransitGatewayMulticastDomainsPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateway_multicast_domains")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGatewayMulticastDomains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGatewayMulticastDomains)

Arguments for `DescribeTransitGatewayMulticastDomainsPaginator.paginate`
method:

- `TransitGatewayMulticastDomainIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewayMulticastDomainsPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewayMulticastDomainsResultTypeDef](./type_defs.md#describetransitgatewaymulticastdomainsresulttypedef)\].

<a id="describetransitgatewaypeeringattachmentspaginator"></a>

## DescribeTransitGatewayPeeringAttachmentsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateway_peering_attachments")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayPeeringAttachmentsPaginator

def get_describe_transit_gateway_peering_attachments_paginator() -> DescribeTransitGatewayPeeringAttachmentsPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateway_peering_attachments")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGatewayPeeringAttachments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGatewayPeeringAttachments)

Arguments for `DescribeTransitGatewayPeeringAttachmentsPaginator.paginate`
method:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewayPeeringAttachmentsPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewayPeeringAttachmentsResultTypeDef](./type_defs.md#describetransitgatewaypeeringattachmentsresulttypedef)\].

<a id="describetransitgatewayroutetablespaginator"></a>

## DescribeTransitGatewayRouteTablesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateway_route_tables")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayRouteTablesPaginator

def get_describe_transit_gateway_route_tables_paginator() -> DescribeTransitGatewayRouteTablesPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateway_route_tables")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGatewayRouteTables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGatewayRouteTables)

Arguments for `DescribeTransitGatewayRouteTablesPaginator.paginate` method:

- `TransitGatewayRouteTableIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewayRouteTablesPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewayRouteTablesResultTypeDef](./type_defs.md#describetransitgatewayroutetablesresulttypedef)\].

<a id="describetransitgatewayvpcattachmentspaginator"></a>

## DescribeTransitGatewayVpcAttachmentsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateway_vpc_attachments")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayVpcAttachmentsPaginator

def get_describe_transit_gateway_vpc_attachments_paginator() -> DescribeTransitGatewayVpcAttachmentsPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateway_vpc_attachments")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGatewayVpcAttachments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGatewayVpcAttachments)

Arguments for `DescribeTransitGatewayVpcAttachmentsPaginator.paginate` method:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewayVpcAttachmentsPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewayVpcAttachmentsResultTypeDef](./type_defs.md#describetransitgatewayvpcattachmentsresulttypedef)\].

<a id="describetransitgatewayspaginator"></a>

## DescribeTransitGatewaysPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_transit_gateways")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewaysPaginator

def get_describe_transit_gateways_paginator() -> DescribeTransitGatewaysPaginator:
    return Session().create_client("ec2").get_paginator("describe_transit_gateways")
```

Boto3 documentation:
[EC2.Paginator.DescribeTransitGateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTransitGateways)

Arguments for `DescribeTransitGatewaysPaginator.paginate` method:

- `TransitGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTransitGatewaysPaginator.paginate` returns
`_PageIterator`\[[DescribeTransitGatewaysResultTypeDef](./type_defs.md#describetransitgatewaysresulttypedef)\].

<a id="describetrunkinterfaceassociationspaginator"></a>

## DescribeTrunkInterfaceAssociationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_trunk_interface_associations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeTrunkInterfaceAssociationsPaginator

def get_describe_trunk_interface_associations_paginator() -> DescribeTrunkInterfaceAssociationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_trunk_interface_associations")
```

Boto3 documentation:
[EC2.Paginator.DescribeTrunkInterfaceAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeTrunkInterfaceAssociations)

Arguments for `DescribeTrunkInterfaceAssociationsPaginator.paginate` method:

- `AssociationIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeTrunkInterfaceAssociationsPaginator.paginate` returns
`_PageIterator`\[[DescribeTrunkInterfaceAssociationsResultTypeDef](./type_defs.md#describetrunkinterfaceassociationsresulttypedef)\].

<a id="describevolumestatuspaginator"></a>

## DescribeVolumeStatusPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_volume_status")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVolumeStatusPaginator

def get_describe_volume_status_paginator() -> DescribeVolumeStatusPaginator:
    return Session().create_client("ec2").get_paginator("describe_volume_status")
```

Boto3 documentation:
[EC2.Paginator.DescribeVolumeStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVolumeStatus)

Arguments for `DescribeVolumeStatusPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `VolumeIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVolumeStatusPaginator.paginate` returns
`_PageIterator`\[[DescribeVolumeStatusResultTypeDef](./type_defs.md#describevolumestatusresulttypedef)\].

<a id="describevolumespaginator"></a>

## DescribeVolumesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_volumes")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVolumesPaginator

def get_describe_volumes_paginator() -> DescribeVolumesPaginator:
    return Session().create_client("ec2").get_paginator("describe_volumes")
```

Boto3 documentation:
[EC2.Paginator.DescribeVolumes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVolumes)

Arguments for `DescribeVolumesPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `VolumeIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVolumesPaginator.paginate` returns
`_PageIterator`\[[DescribeVolumesResultTypeDef](./type_defs.md#describevolumesresulttypedef)\].

<a id="describevolumesmodificationspaginator"></a>

## DescribeVolumesModificationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_volumes_modifications")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVolumesModificationsPaginator

def get_describe_volumes_modifications_paginator() -> DescribeVolumesModificationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_volumes_modifications")
```

Boto3 documentation:
[EC2.Paginator.DescribeVolumesModifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVolumesModifications)

Arguments for `DescribeVolumesModificationsPaginator.paginate` method:

- `DryRun`: `bool`
- `VolumeIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVolumesModificationsPaginator.paginate` returns
`_PageIterator`\[[DescribeVolumesModificationsResultTypeDef](./type_defs.md#describevolumesmodificationsresulttypedef)\].

<a id="describevpcclassiclinkdnssupportpaginator"></a>

## DescribeVpcClassicLinkDnsSupportPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_classic_link_dns_support")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcClassicLinkDnsSupportPaginator

def get_describe_vpc_classic_link_dns_support_paginator() -> DescribeVpcClassicLinkDnsSupportPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_classic_link_dns_support")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcClassicLinkDnsSupport](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcClassicLinkDnsSupport)

Arguments for `DescribeVpcClassicLinkDnsSupportPaginator.paginate` method:

- `VpcIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcClassicLinkDnsSupportPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcClassicLinkDnsSupportResultTypeDef](./type_defs.md#describevpcclassiclinkdnssupportresulttypedef)\].

<a id="describevpcendpointconnectionnotificationspaginator"></a>

## DescribeVpcEndpointConnectionNotificationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_endpoint_connection_notifications")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointConnectionNotificationsPaginator

def get_describe_vpc_endpoint_connection_notifications_paginator() -> DescribeVpcEndpointConnectionNotificationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_endpoint_connection_notifications")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcEndpointConnectionNotifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcEndpointConnectionNotifications)

Arguments for `DescribeVpcEndpointConnectionNotificationsPaginator.paginate`
method:

- `DryRun`: `bool`
- `ConnectionNotificationId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcEndpointConnectionNotificationsPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcEndpointConnectionNotificationsResultTypeDef](./type_defs.md#describevpcendpointconnectionnotificationsresulttypedef)\].

<a id="describevpcendpointconnectionspaginator"></a>

## DescribeVpcEndpointConnectionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_endpoint_connections")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointConnectionsPaginator

def get_describe_vpc_endpoint_connections_paginator() -> DescribeVpcEndpointConnectionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_endpoint_connections")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcEndpointConnections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcEndpointConnections)

Arguments for `DescribeVpcEndpointConnectionsPaginator.paginate` method:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcEndpointConnectionsPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcEndpointConnectionsResultTypeDef](./type_defs.md#describevpcendpointconnectionsresulttypedef)\].

<a id="describevpcendpointserviceconfigurationspaginator"></a>

## DescribeVpcEndpointServiceConfigurationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_endpoint_service_configurations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointServiceConfigurationsPaginator

def get_describe_vpc_endpoint_service_configurations_paginator() -> DescribeVpcEndpointServiceConfigurationsPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_endpoint_service_configurations")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcEndpointServiceConfigurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcEndpointServiceConfigurations)

Arguments for `DescribeVpcEndpointServiceConfigurationsPaginator.paginate`
method:

- `DryRun`: `bool`
- `ServiceIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcEndpointServiceConfigurationsPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcEndpointServiceConfigurationsResultTypeDef](./type_defs.md#describevpcendpointserviceconfigurationsresulttypedef)\].

<a id="describevpcendpointservicepermissionspaginator"></a>

## DescribeVpcEndpointServicePermissionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_endpoint_service_permissions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointServicePermissionsPaginator

def get_describe_vpc_endpoint_service_permissions_paginator() -> DescribeVpcEndpointServicePermissionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_endpoint_service_permissions")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcEndpointServicePermissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcEndpointServicePermissions)

Arguments for `DescribeVpcEndpointServicePermissionsPaginator.paginate` method:

- `ServiceId`: `str` *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcEndpointServicePermissionsPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcEndpointServicePermissionsResultTypeDef](./type_defs.md#describevpcendpointservicepermissionsresulttypedef)\].

<a id="describevpcendpointservicespaginator"></a>

## DescribeVpcEndpointServicesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_endpoint_services")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointServicesPaginator

def get_describe_vpc_endpoint_services_paginator() -> DescribeVpcEndpointServicesPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_endpoint_services")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcEndpointServices](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcEndpointServices)

Arguments for `DescribeVpcEndpointServicesPaginator.paginate` method:

- `DryRun`: `bool`
- `ServiceNames`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcEndpointServicesPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcEndpointServicesResultTypeDef](./type_defs.md#describevpcendpointservicesresulttypedef)\].

<a id="describevpcendpointspaginator"></a>

## DescribeVpcEndpointsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_endpoints")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointsPaginator

def get_describe_vpc_endpoints_paginator() -> DescribeVpcEndpointsPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_endpoints")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcEndpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcEndpoints)

Arguments for `DescribeVpcEndpointsPaginator.paginate` method:

- `DryRun`: `bool`
- `VpcEndpointIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcEndpointsPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcEndpointsResultTypeDef](./type_defs.md#describevpcendpointsresulttypedef)\].

<a id="describevpcpeeringconnectionspaginator"></a>

## DescribeVpcPeeringConnectionsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpc_peering_connections")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcPeeringConnectionsPaginator

def get_describe_vpc_peering_connections_paginator() -> DescribeVpcPeeringConnectionsPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpc_peering_connections")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcPeeringConnections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcPeeringConnections)

Arguments for `DescribeVpcPeeringConnectionsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `VpcPeeringConnectionIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcPeeringConnectionsPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcPeeringConnectionsResultTypeDef](./type_defs.md#describevpcpeeringconnectionsresulttypedef)\].

<a id="describevpcspaginator"></a>

## DescribeVpcsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("describe_vpcs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import DescribeVpcsPaginator

def get_describe_vpcs_paginator() -> DescribeVpcsPaginator:
    return Session().create_client("ec2").get_paginator("describe_vpcs")
```

Boto3 documentation:
[EC2.Paginator.DescribeVpcs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.DescribeVpcs)

Arguments for `DescribeVpcsPaginator.paginate` method:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `VpcIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeVpcsPaginator.paginate` returns
`_PageIterator`\[[DescribeVpcsResultTypeDef](./type_defs.md#describevpcsresulttypedef)\].

<a id="getassociatedipv6poolcidrspaginator"></a>

## GetAssociatedIpv6PoolCidrsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_associated_ipv6_pool_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetAssociatedIpv6PoolCidrsPaginator

def get_get_associated_ipv6_pool_cidrs_paginator() -> GetAssociatedIpv6PoolCidrsPaginator:
    return Session().create_client("ec2").get_paginator("get_associated_ipv6_pool_cidrs")
```

Boto3 documentation:
[EC2.Paginator.GetAssociatedIpv6PoolCidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetAssociatedIpv6PoolCidrs)

Arguments for `GetAssociatedIpv6PoolCidrsPaginator.paginate` method:

- `PoolId`: `str` *(required)*
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetAssociatedIpv6PoolCidrsPaginator.paginate` returns
`_PageIterator`\[[GetAssociatedIpv6PoolCidrsResultTypeDef](./type_defs.md#getassociatedipv6poolcidrsresulttypedef)\].

<a id="getgroupsforcapacityreservationpaginator"></a>

## GetGroupsForCapacityReservationPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_groups_for_capacity_reservation")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetGroupsForCapacityReservationPaginator

def get_get_groups_for_capacity_reservation_paginator() -> GetGroupsForCapacityReservationPaginator:
    return Session().create_client("ec2").get_paginator("get_groups_for_capacity_reservation")
```

Boto3 documentation:
[EC2.Paginator.GetGroupsForCapacityReservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetGroupsForCapacityReservation)

Arguments for `GetGroupsForCapacityReservationPaginator.paginate` method:

- `CapacityReservationId`: `str` *(required)*
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetGroupsForCapacityReservationPaginator.paginate` returns
`_PageIterator`\[[GetGroupsForCapacityReservationResultTypeDef](./type_defs.md#getgroupsforcapacityreservationresulttypedef)\].

<a id="getinstancetypesfrominstancerequirementspaginator"></a>

## GetInstanceTypesFromInstanceRequirementsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_instance_types_from_instance_requirements")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetInstanceTypesFromInstanceRequirementsPaginator

def get_get_instance_types_from_instance_requirements_paginator() -> GetInstanceTypesFromInstanceRequirementsPaginator:
    return Session().create_client("ec2").get_paginator("get_instance_types_from_instance_requirements")
```

Boto3 documentation:
[EC2.Paginator.GetInstanceTypesFromInstanceRequirements](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetInstanceTypesFromInstanceRequirements)

Arguments for `GetInstanceTypesFromInstanceRequirementsPaginator.paginate`
method:

- `ArchitectureTypes`:
  `Sequence`\[[ArchitectureTypeType](./literals.md#architecturetypetype)\]
  *(required)*
- `VirtualizationTypes`:
  `Sequence`\[[VirtualizationTypeType](./literals.md#virtualizationtypetype)\]
  *(required)*
- `InstanceRequirements`:
  [InstanceRequirementsRequestTypeDef](./type_defs.md#instancerequirementsrequesttypedef)
  *(required)*
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetInstanceTypesFromInstanceRequirementsPaginator.paginate` returns
`_PageIterator`\[[GetInstanceTypesFromInstanceRequirementsResultTypeDef](./type_defs.md#getinstancetypesfrominstancerequirementsresulttypedef)\].

<a id="getipamaddresshistorypaginator"></a>

## GetIpamAddressHistoryPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_ipam_address_history")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetIpamAddressHistoryPaginator

def get_get_ipam_address_history_paginator() -> GetIpamAddressHistoryPaginator:
    return Session().create_client("ec2").get_paginator("get_ipam_address_history")
```

Boto3 documentation:
[EC2.Paginator.GetIpamAddressHistory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetIpamAddressHistory)

Arguments for `GetIpamAddressHistoryPaginator.paginate` method:

- `Cidr`: `str` *(required)*
- `IpamScopeId`: `str` *(required)*
- `DryRun`: `bool`
- `VpcId`: `str`
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetIpamAddressHistoryPaginator.paginate` returns
`_PageIterator`\[[GetIpamAddressHistoryResultTypeDef](./type_defs.md#getipamaddresshistoryresulttypedef)\].

<a id="getipampoolallocationspaginator"></a>

## GetIpamPoolAllocationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_ipam_pool_allocations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetIpamPoolAllocationsPaginator

def get_get_ipam_pool_allocations_paginator() -> GetIpamPoolAllocationsPaginator:
    return Session().create_client("ec2").get_paginator("get_ipam_pool_allocations")
```

Boto3 documentation:
[EC2.Paginator.GetIpamPoolAllocations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetIpamPoolAllocations)

Arguments for `GetIpamPoolAllocationsPaginator.paginate` method:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `IpamPoolAllocationId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetIpamPoolAllocationsPaginator.paginate` returns
`_PageIterator`\[[GetIpamPoolAllocationsResultTypeDef](./type_defs.md#getipampoolallocationsresulttypedef)\].

<a id="getipampoolcidrspaginator"></a>

## GetIpamPoolCidrsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_ipam_pool_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetIpamPoolCidrsPaginator

def get_get_ipam_pool_cidrs_paginator() -> GetIpamPoolCidrsPaginator:
    return Session().create_client("ec2").get_paginator("get_ipam_pool_cidrs")
```

Boto3 documentation:
[EC2.Paginator.GetIpamPoolCidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetIpamPoolCidrs)

Arguments for `GetIpamPoolCidrsPaginator.paginate` method:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetIpamPoolCidrsPaginator.paginate` returns
`_PageIterator`\[[GetIpamPoolCidrsResultTypeDef](./type_defs.md#getipampoolcidrsresulttypedef)\].

<a id="getipamresourcecidrspaginator"></a>

## GetIpamResourceCidrsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_ipam_resource_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetIpamResourceCidrsPaginator

def get_get_ipam_resource_cidrs_paginator() -> GetIpamResourceCidrsPaginator:
    return Session().create_client("ec2").get_paginator("get_ipam_resource_cidrs")
```

Boto3 documentation:
[EC2.Paginator.GetIpamResourceCidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetIpamResourceCidrs)

Arguments for `GetIpamResourceCidrsPaginator.paginate` method:

- `IpamScopeId`: `str` *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IpamPoolId`: `str`
- `ResourceId`: `str`
- `ResourceType`: [IpamResourceTypeType](./literals.md#ipamresourcetypetype)
- `ResourceTag`:
  [RequestIpamResourceTagTypeDef](./type_defs.md#requestipamresourcetagtypedef)
- `ResourceOwner`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetIpamResourceCidrsPaginator.paginate` returns
`_PageIterator`\[[GetIpamResourceCidrsResultTypeDef](./type_defs.md#getipamresourcecidrsresulttypedef)\].

<a id="getmanagedprefixlistassociationspaginator"></a>

## GetManagedPrefixListAssociationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_managed_prefix_list_associations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetManagedPrefixListAssociationsPaginator

def get_get_managed_prefix_list_associations_paginator() -> GetManagedPrefixListAssociationsPaginator:
    return Session().create_client("ec2").get_paginator("get_managed_prefix_list_associations")
```

Boto3 documentation:
[EC2.Paginator.GetManagedPrefixListAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetManagedPrefixListAssociations)

Arguments for `GetManagedPrefixListAssociationsPaginator.paginate` method:

- `PrefixListId`: `str` *(required)*
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetManagedPrefixListAssociationsPaginator.paginate` returns
`_PageIterator`\[[GetManagedPrefixListAssociationsResultTypeDef](./type_defs.md#getmanagedprefixlistassociationsresulttypedef)\].

<a id="getmanagedprefixlistentriespaginator"></a>

## GetManagedPrefixListEntriesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_managed_prefix_list_entries")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetManagedPrefixListEntriesPaginator

def get_get_managed_prefix_list_entries_paginator() -> GetManagedPrefixListEntriesPaginator:
    return Session().create_client("ec2").get_paginator("get_managed_prefix_list_entries")
```

Boto3 documentation:
[EC2.Paginator.GetManagedPrefixListEntries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetManagedPrefixListEntries)

Arguments for `GetManagedPrefixListEntriesPaginator.paginate` method:

- `PrefixListId`: `str` *(required)*
- `DryRun`: `bool`
- `TargetVersion`: `int`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetManagedPrefixListEntriesPaginator.paginate` returns
`_PageIterator`\[[GetManagedPrefixListEntriesResultTypeDef](./type_defs.md#getmanagedprefixlistentriesresulttypedef)\].

<a id="getspotplacementscorespaginator"></a>

## GetSpotPlacementScoresPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_spot_placement_scores")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetSpotPlacementScoresPaginator

def get_get_spot_placement_scores_paginator() -> GetSpotPlacementScoresPaginator:
    return Session().create_client("ec2").get_paginator("get_spot_placement_scores")
```

Boto3 documentation:
[EC2.Paginator.GetSpotPlacementScores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetSpotPlacementScores)

Arguments for `GetSpotPlacementScoresPaginator.paginate` method:

- `TargetCapacity`: `int` *(required)*
- `InstanceTypes`: `Sequence`\[`str`\]
- `TargetCapacityUnitType`:
  [TargetCapacityUnitTypeType](./literals.md#targetcapacityunittypetype)
- `SingleAvailabilityZone`: `bool`
- `RegionNames`: `Sequence`\[`str`\]
- `InstanceRequirementsWithMetadata`:
  [InstanceRequirementsWithMetadataRequestTypeDef](./type_defs.md#instancerequirementswithmetadatarequesttypedef)
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetSpotPlacementScoresPaginator.paginate` returns
`_PageIterator`\[[GetSpotPlacementScoresResultTypeDef](./type_defs.md#getspotplacementscoresresulttypedef)\].

<a id="gettransitgatewayattachmentpropagationspaginator"></a>

## GetTransitGatewayAttachmentPropagationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_transit_gateway_attachment_propagations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetTransitGatewayAttachmentPropagationsPaginator

def get_get_transit_gateway_attachment_propagations_paginator() -> GetTransitGatewayAttachmentPropagationsPaginator:
    return Session().create_client("ec2").get_paginator("get_transit_gateway_attachment_propagations")
```

Boto3 documentation:
[EC2.Paginator.GetTransitGatewayAttachmentPropagations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetTransitGatewayAttachmentPropagations)

Arguments for `GetTransitGatewayAttachmentPropagationsPaginator.paginate`
method:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetTransitGatewayAttachmentPropagationsPaginator.paginate` returns
`_PageIterator`\[[GetTransitGatewayAttachmentPropagationsResultTypeDef](./type_defs.md#gettransitgatewayattachmentpropagationsresulttypedef)\].

<a id="gettransitgatewaymulticastdomainassociationspaginator"></a>

## GetTransitGatewayMulticastDomainAssociationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_transit_gateway_multicast_domain_associations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetTransitGatewayMulticastDomainAssociationsPaginator

def get_get_transit_gateway_multicast_domain_associations_paginator() -> GetTransitGatewayMulticastDomainAssociationsPaginator:
    return Session().create_client("ec2").get_paginator("get_transit_gateway_multicast_domain_associations")
```

Boto3 documentation:
[EC2.Paginator.GetTransitGatewayMulticastDomainAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetTransitGatewayMulticastDomainAssociations)

Arguments for `GetTransitGatewayMulticastDomainAssociationsPaginator.paginate`
method:

- `TransitGatewayMulticastDomainId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetTransitGatewayMulticastDomainAssociationsPaginator.paginate` returns
`_PageIterator`\[[GetTransitGatewayMulticastDomainAssociationsResultTypeDef](./type_defs.md#gettransitgatewaymulticastdomainassociationsresulttypedef)\].

<a id="gettransitgatewayprefixlistreferencespaginator"></a>

## GetTransitGatewayPrefixListReferencesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_transit_gateway_prefix_list_references")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetTransitGatewayPrefixListReferencesPaginator

def get_get_transit_gateway_prefix_list_references_paginator() -> GetTransitGatewayPrefixListReferencesPaginator:
    return Session().create_client("ec2").get_paginator("get_transit_gateway_prefix_list_references")
```

Boto3 documentation:
[EC2.Paginator.GetTransitGatewayPrefixListReferences](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetTransitGatewayPrefixListReferences)

Arguments for `GetTransitGatewayPrefixListReferencesPaginator.paginate` method:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetTransitGatewayPrefixListReferencesPaginator.paginate` returns
`_PageIterator`\[[GetTransitGatewayPrefixListReferencesResultTypeDef](./type_defs.md#gettransitgatewayprefixlistreferencesresulttypedef)\].

<a id="gettransitgatewayroutetableassociationspaginator"></a>

## GetTransitGatewayRouteTableAssociationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_transit_gateway_route_table_associations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetTransitGatewayRouteTableAssociationsPaginator

def get_get_transit_gateway_route_table_associations_paginator() -> GetTransitGatewayRouteTableAssociationsPaginator:
    return Session().create_client("ec2").get_paginator("get_transit_gateway_route_table_associations")
```

Boto3 documentation:
[EC2.Paginator.GetTransitGatewayRouteTableAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetTransitGatewayRouteTableAssociations)

Arguments for `GetTransitGatewayRouteTableAssociationsPaginator.paginate`
method:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetTransitGatewayRouteTableAssociationsPaginator.paginate` returns
`_PageIterator`\[[GetTransitGatewayRouteTableAssociationsResultTypeDef](./type_defs.md#gettransitgatewayroutetableassociationsresulttypedef)\].

<a id="gettransitgatewayroutetablepropagationspaginator"></a>

## GetTransitGatewayRouteTablePropagationsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_transit_gateway_route_table_propagations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetTransitGatewayRouteTablePropagationsPaginator

def get_get_transit_gateway_route_table_propagations_paginator() -> GetTransitGatewayRouteTablePropagationsPaginator:
    return Session().create_client("ec2").get_paginator("get_transit_gateway_route_table_propagations")
```

Boto3 documentation:
[EC2.Paginator.GetTransitGatewayRouteTablePropagations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetTransitGatewayRouteTablePropagations)

Arguments for `GetTransitGatewayRouteTablePropagationsPaginator.paginate`
method:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetTransitGatewayRouteTablePropagationsPaginator.paginate` returns
`_PageIterator`\[[GetTransitGatewayRouteTablePropagationsResultTypeDef](./type_defs.md#gettransitgatewayroutetablepropagationsresulttypedef)\].

<a id="getvpnconnectiondevicetypespaginator"></a>

## GetVpnConnectionDeviceTypesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("get_vpn_connection_device_types")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import GetVpnConnectionDeviceTypesPaginator

def get_get_vpn_connection_device_types_paginator() -> GetVpnConnectionDeviceTypesPaginator:
    return Session().create_client("ec2").get_paginator("get_vpn_connection_device_types")
```

Boto3 documentation:
[EC2.Paginator.GetVpnConnectionDeviceTypes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.GetVpnConnectionDeviceTypes)

Arguments for `GetVpnConnectionDeviceTypesPaginator.paginate` method:

- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetVpnConnectionDeviceTypesPaginator.paginate` returns
`_PageIterator`\[[GetVpnConnectionDeviceTypesResultTypeDef](./type_defs.md#getvpnconnectiondevicetypesresulttypedef)\].

<a id="listsnapshotsinrecyclebinpaginator"></a>

## ListSnapshotsInRecycleBinPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("list_snapshots_in_recycle_bin")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import ListSnapshotsInRecycleBinPaginator

def get_list_snapshots_in_recycle_bin_paginator() -> ListSnapshotsInRecycleBinPaginator:
    return Session().create_client("ec2").get_paginator("list_snapshots_in_recycle_bin")
```

Boto3 documentation:
[EC2.Paginator.ListSnapshotsInRecycleBin](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.ListSnapshotsInRecycleBin)

Arguments for `ListSnapshotsInRecycleBinPaginator.paginate` method:

- `SnapshotIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSnapshotsInRecycleBinPaginator.paginate` returns
`_PageIterator`\[[ListSnapshotsInRecycleBinResultTypeDef](./type_defs.md#listsnapshotsinrecyclebinresulttypedef)\].

<a id="searchlocalgatewayroutespaginator"></a>

## SearchLocalGatewayRoutesPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("search_local_gateway_routes")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import SearchLocalGatewayRoutesPaginator

def get_search_local_gateway_routes_paginator() -> SearchLocalGatewayRoutesPaginator:
    return Session().create_client("ec2").get_paginator("search_local_gateway_routes")
```

Boto3 documentation:
[EC2.Paginator.SearchLocalGatewayRoutes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.SearchLocalGatewayRoutes)

Arguments for `SearchLocalGatewayRoutesPaginator.paginate` method:

- `LocalGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`SearchLocalGatewayRoutesPaginator.paginate` returns
`_PageIterator`\[[SearchLocalGatewayRoutesResultTypeDef](./type_defs.md#searchlocalgatewayroutesresulttypedef)\].

<a id="searchtransitgatewaymulticastgroupspaginator"></a>

## SearchTransitGatewayMulticastGroupsPaginator

Type annotations for
`aiobotocore.create_client("ec2").get_paginator("search_transit_gateway_multicast_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ec2.paginator import SearchTransitGatewayMulticastGroupsPaginator

def get_search_transit_gateway_multicast_groups_paginator() -> SearchTransitGatewayMulticastGroupsPaginator:
    return Session().create_client("ec2").get_paginator("search_transit_gateway_multicast_groups")
```

Boto3 documentation:
[EC2.Paginator.SearchTransitGatewayMulticastGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Paginator.SearchTransitGatewayMulticastGroups)

Arguments for `SearchTransitGatewayMulticastGroupsPaginator.paginate` method:

- `TransitGatewayMulticastDomainId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`SearchTransitGatewayMulticastGroupsPaginator.paginate` returns
`_PageIterator`\[[SearchTransitGatewayMulticastGroupsResultTypeDef](./type_defs.md#searchtransitgatewaymulticastgroupsresulttypedef)\].
