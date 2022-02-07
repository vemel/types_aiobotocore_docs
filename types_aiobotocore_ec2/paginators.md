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
`session.create_client("ec2").get_paginator("describe_addresses_attribute")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeAddressesAttributePaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeAddressesAttributePaginator = client.get_paginator("describe_addresses_attribute")
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
`session.create_client("ec2").get_paginator("describe_byoip_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeByoipCidrsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeByoipCidrsPaginator = client.get_paginator("describe_byoip_cidrs")
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
`session.create_client("ec2").get_paginator("describe_capacity_reservation_fleets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeCapacityReservationFleetsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeCapacityReservationFleetsPaginator = client.get_paginator("describe_capacity_reservation_fleets")
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
`session.create_client("ec2").get_paginator("describe_capacity_reservations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeCapacityReservationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeCapacityReservationsPaginator = client.get_paginator("describe_capacity_reservations")
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
`session.create_client("ec2").get_paginator("describe_carrier_gateways")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeCarrierGatewaysPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeCarrierGatewaysPaginator = client.get_paginator("describe_carrier_gateways")
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
`session.create_client("ec2").get_paginator("describe_classic_link_instances")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeClassicLinkInstancesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeClassicLinkInstancesPaginator = client.get_paginator("describe_classic_link_instances")
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
`session.create_client("ec2").get_paginator("describe_client_vpn_authorization_rules")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeClientVpnAuthorizationRulesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeClientVpnAuthorizationRulesPaginator = client.get_paginator("describe_client_vpn_authorization_rules")
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
`session.create_client("ec2").get_paginator("describe_client_vpn_connections")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeClientVpnConnectionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeClientVpnConnectionsPaginator = client.get_paginator("describe_client_vpn_connections")
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
`session.create_client("ec2").get_paginator("describe_client_vpn_endpoints")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeClientVpnEndpointsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeClientVpnEndpointsPaginator = client.get_paginator("describe_client_vpn_endpoints")
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
`session.create_client("ec2").get_paginator("describe_client_vpn_routes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeClientVpnRoutesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeClientVpnRoutesPaginator = client.get_paginator("describe_client_vpn_routes")
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
`session.create_client("ec2").get_paginator("describe_client_vpn_target_networks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeClientVpnTargetNetworksPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeClientVpnTargetNetworksPaginator = client.get_paginator("describe_client_vpn_target_networks")
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
`session.create_client("ec2").get_paginator("describe_coip_pools")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeCoipPoolsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeCoipPoolsPaginator = client.get_paginator("describe_coip_pools")
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
`session.create_client("ec2").get_paginator("describe_dhcp_options")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeDhcpOptionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeDhcpOptionsPaginator = client.get_paginator("describe_dhcp_options")
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
`session.create_client("ec2").get_paginator("describe_egress_only_internet_gateways")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeEgressOnlyInternetGatewaysPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeEgressOnlyInternetGatewaysPaginator = client.get_paginator("describe_egress_only_internet_gateways")
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
`session.create_client("ec2").get_paginator("describe_export_image_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeExportImageTasksPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeExportImageTasksPaginator = client.get_paginator("describe_export_image_tasks")
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
`session.create_client("ec2").get_paginator("describe_fast_snapshot_restores")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeFastSnapshotRestoresPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeFastSnapshotRestoresPaginator = client.get_paginator("describe_fast_snapshot_restores")
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
`session.create_client("ec2").get_paginator("describe_fleets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeFleetsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeFleetsPaginator = client.get_paginator("describe_fleets")
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
`session.create_client("ec2").get_paginator("describe_flow_logs")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeFlowLogsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeFlowLogsPaginator = client.get_paginator("describe_flow_logs")
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
`session.create_client("ec2").get_paginator("describe_fpga_images")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeFpgaImagesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeFpgaImagesPaginator = client.get_paginator("describe_fpga_images")
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
`session.create_client("ec2").get_paginator("describe_host_reservation_offerings")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeHostReservationOfferingsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeHostReservationOfferingsPaginator = client.get_paginator("describe_host_reservation_offerings")
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
`session.create_client("ec2").get_paginator("describe_host_reservations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeHostReservationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeHostReservationsPaginator = client.get_paginator("describe_host_reservations")
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
`session.create_client("ec2").get_paginator("describe_hosts")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeHostsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeHostsPaginator = client.get_paginator("describe_hosts")
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
`session.create_client("ec2").get_paginator("describe_iam_instance_profile_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeIamInstanceProfileAssociationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeIamInstanceProfileAssociationsPaginator = client.get_paginator("describe_iam_instance_profile_associations")
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
`session.create_client("ec2").get_paginator("describe_import_image_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeImportImageTasksPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeImportImageTasksPaginator = client.get_paginator("describe_import_image_tasks")
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
`session.create_client("ec2").get_paginator("describe_import_snapshot_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeImportSnapshotTasksPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeImportSnapshotTasksPaginator = client.get_paginator("describe_import_snapshot_tasks")
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
`session.create_client("ec2").get_paginator("describe_instance_credit_specifications")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeInstanceCreditSpecificationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeInstanceCreditSpecificationsPaginator = client.get_paginator("describe_instance_credit_specifications")
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
`session.create_client("ec2").get_paginator("describe_instance_event_windows")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeInstanceEventWindowsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeInstanceEventWindowsPaginator = client.get_paginator("describe_instance_event_windows")
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
`session.create_client("ec2").get_paginator("describe_instance_status")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeInstanceStatusPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeInstanceStatusPaginator = client.get_paginator("describe_instance_status")
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
`session.create_client("ec2").get_paginator("describe_instance_type_offerings")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeInstanceTypeOfferingsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeInstanceTypeOfferingsPaginator = client.get_paginator("describe_instance_type_offerings")
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
`session.create_client("ec2").get_paginator("describe_instance_types")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeInstanceTypesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeInstanceTypesPaginator = client.get_paginator("describe_instance_types")
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
`session.create_client("ec2").get_paginator("describe_instances")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeInstancesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeInstancesPaginator = client.get_paginator("describe_instances")
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
`session.create_client("ec2").get_paginator("describe_internet_gateways")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeInternetGatewaysPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeInternetGatewaysPaginator = client.get_paginator("describe_internet_gateways")
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
`session.create_client("ec2").get_paginator("describe_ipam_pools")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeIpamPoolsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeIpamPoolsPaginator = client.get_paginator("describe_ipam_pools")
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
`session.create_client("ec2").get_paginator("describe_ipam_scopes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeIpamScopesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeIpamScopesPaginator = client.get_paginator("describe_ipam_scopes")
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
`session.create_client("ec2").get_paginator("describe_ipams")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeIpamsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeIpamsPaginator = client.get_paginator("describe_ipams")
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
`session.create_client("ec2").get_paginator("describe_ipv6_pools")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeIpv6PoolsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeIpv6PoolsPaginator = client.get_paginator("describe_ipv6_pools")
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
`session.create_client("ec2").get_paginator("describe_launch_template_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLaunchTemplateVersionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLaunchTemplateVersionsPaginator = client.get_paginator("describe_launch_template_versions")
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
`session.create_client("ec2").get_paginator("describe_launch_templates")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLaunchTemplatesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLaunchTemplatesPaginator = client.get_paginator("describe_launch_templates")
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
`session.create_client("ec2").get_paginator("describe_local_gateway_route_table_virtual_interface_group_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator = client.get_paginator("describe_local_gateway_route_table_virtual_interface_group_associations")
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
`session.create_client("ec2").get_paginator("describe_local_gateway_route_table_vpc_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayRouteTableVpcAssociationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLocalGatewayRouteTableVpcAssociationsPaginator = client.get_paginator("describe_local_gateway_route_table_vpc_associations")
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
`session.create_client("ec2").get_paginator("describe_local_gateway_route_tables")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayRouteTablesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLocalGatewayRouteTablesPaginator = client.get_paginator("describe_local_gateway_route_tables")
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
`session.create_client("ec2").get_paginator("describe_local_gateway_virtual_interface_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayVirtualInterfaceGroupsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLocalGatewayVirtualInterfaceGroupsPaginator = client.get_paginator("describe_local_gateway_virtual_interface_groups")
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
`session.create_client("ec2").get_paginator("describe_local_gateway_virtual_interfaces")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewayVirtualInterfacesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLocalGatewayVirtualInterfacesPaginator = client.get_paginator("describe_local_gateway_virtual_interfaces")
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
`session.create_client("ec2").get_paginator("describe_local_gateways")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeLocalGatewaysPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeLocalGatewaysPaginator = client.get_paginator("describe_local_gateways")
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
`session.create_client("ec2").get_paginator("describe_managed_prefix_lists")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeManagedPrefixListsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeManagedPrefixListsPaginator = client.get_paginator("describe_managed_prefix_lists")
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
`session.create_client("ec2").get_paginator("describe_moving_addresses")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeMovingAddressesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeMovingAddressesPaginator = client.get_paginator("describe_moving_addresses")
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
`session.create_client("ec2").get_paginator("describe_nat_gateways")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNatGatewaysPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNatGatewaysPaginator = client.get_paginator("describe_nat_gateways")
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
`session.create_client("ec2").get_paginator("describe_network_acls")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNetworkAclsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNetworkAclsPaginator = client.get_paginator("describe_network_acls")
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
`session.create_client("ec2").get_paginator("describe_network_insights_access_scope_analyses")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsAccessScopeAnalysesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNetworkInsightsAccessScopeAnalysesPaginator = client.get_paginator("describe_network_insights_access_scope_analyses")
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
`session.create_client("ec2").get_paginator("describe_network_insights_access_scopes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsAccessScopesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNetworkInsightsAccessScopesPaginator = client.get_paginator("describe_network_insights_access_scopes")
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
`session.create_client("ec2").get_paginator("describe_network_insights_analyses")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsAnalysesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNetworkInsightsAnalysesPaginator = client.get_paginator("describe_network_insights_analyses")
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
`session.create_client("ec2").get_paginator("describe_network_insights_paths")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNetworkInsightsPathsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNetworkInsightsPathsPaginator = client.get_paginator("describe_network_insights_paths")
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
`session.create_client("ec2").get_paginator("describe_network_interface_permissions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNetworkInterfacePermissionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNetworkInterfacePermissionsPaginator = client.get_paginator("describe_network_interface_permissions")
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
`session.create_client("ec2").get_paginator("describe_network_interfaces")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeNetworkInterfacesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeNetworkInterfacesPaginator = client.get_paginator("describe_network_interfaces")
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
`session.create_client("ec2").get_paginator("describe_prefix_lists")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribePrefixListsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribePrefixListsPaginator = client.get_paginator("describe_prefix_lists")
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
`session.create_client("ec2").get_paginator("describe_principal_id_format")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribePrincipalIdFormatPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribePrincipalIdFormatPaginator = client.get_paginator("describe_principal_id_format")
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
`session.create_client("ec2").get_paginator("describe_public_ipv4_pools")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribePublicIpv4PoolsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribePublicIpv4PoolsPaginator = client.get_paginator("describe_public_ipv4_pools")
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
`session.create_client("ec2").get_paginator("describe_replace_root_volume_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeReplaceRootVolumeTasksPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeReplaceRootVolumeTasksPaginator = client.get_paginator("describe_replace_root_volume_tasks")
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
`session.create_client("ec2").get_paginator("describe_reserved_instances_modifications")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeReservedInstancesModificationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeReservedInstancesModificationsPaginator = client.get_paginator("describe_reserved_instances_modifications")
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
`session.create_client("ec2").get_paginator("describe_reserved_instances_offerings")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeReservedInstancesOfferingsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeReservedInstancesOfferingsPaginator = client.get_paginator("describe_reserved_instances_offerings")
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
`session.create_client("ec2").get_paginator("describe_route_tables")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeRouteTablesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeRouteTablesPaginator = client.get_paginator("describe_route_tables")
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
`session.create_client("ec2").get_paginator("describe_scheduled_instance_availability")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeScheduledInstanceAvailabilityPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeScheduledInstanceAvailabilityPaginator = client.get_paginator("describe_scheduled_instance_availability")
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
`session.create_client("ec2").get_paginator("describe_scheduled_instances")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeScheduledInstancesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeScheduledInstancesPaginator = client.get_paginator("describe_scheduled_instances")
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
`session.create_client("ec2").get_paginator("describe_security_group_rules")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSecurityGroupRulesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSecurityGroupRulesPaginator = client.get_paginator("describe_security_group_rules")
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
`session.create_client("ec2").get_paginator("describe_security_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSecurityGroupsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSecurityGroupsPaginator = client.get_paginator("describe_security_groups")
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
`session.create_client("ec2").get_paginator("describe_snapshot_tier_status")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSnapshotTierStatusPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSnapshotTierStatusPaginator = client.get_paginator("describe_snapshot_tier_status")
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
`session.create_client("ec2").get_paginator("describe_snapshots")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSnapshotsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSnapshotsPaginator = client.get_paginator("describe_snapshots")
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
`session.create_client("ec2").get_paginator("describe_spot_fleet_instances")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSpotFleetInstancesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSpotFleetInstancesPaginator = client.get_paginator("describe_spot_fleet_instances")
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
`session.create_client("ec2").get_paginator("describe_spot_fleet_requests")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSpotFleetRequestsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSpotFleetRequestsPaginator = client.get_paginator("describe_spot_fleet_requests")
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
`session.create_client("ec2").get_paginator("describe_spot_instance_requests")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSpotInstanceRequestsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSpotInstanceRequestsPaginator = client.get_paginator("describe_spot_instance_requests")
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
`session.create_client("ec2").get_paginator("describe_spot_price_history")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSpotPriceHistoryPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSpotPriceHistoryPaginator = client.get_paginator("describe_spot_price_history")
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
`session.create_client("ec2").get_paginator("describe_stale_security_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeStaleSecurityGroupsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeStaleSecurityGroupsPaginator = client.get_paginator("describe_stale_security_groups")
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
`session.create_client("ec2").get_paginator("describe_store_image_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeStoreImageTasksPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeStoreImageTasksPaginator = client.get_paginator("describe_store_image_tasks")
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
`session.create_client("ec2").get_paginator("describe_subnets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeSubnetsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeSubnetsPaginator = client.get_paginator("describe_subnets")
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
`session.create_client("ec2").get_paginator("describe_tags")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTagsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTagsPaginator = client.get_paginator("describe_tags")
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
`session.create_client("ec2").get_paginator("describe_traffic_mirror_filters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTrafficMirrorFiltersPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTrafficMirrorFiltersPaginator = client.get_paginator("describe_traffic_mirror_filters")
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
`session.create_client("ec2").get_paginator("describe_traffic_mirror_sessions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTrafficMirrorSessionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTrafficMirrorSessionsPaginator = client.get_paginator("describe_traffic_mirror_sessions")
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
`session.create_client("ec2").get_paginator("describe_traffic_mirror_targets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTrafficMirrorTargetsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTrafficMirrorTargetsPaginator = client.get_paginator("describe_traffic_mirror_targets")
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
`session.create_client("ec2").get_paginator("describe_transit_gateway_attachments")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayAttachmentsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewayAttachmentsPaginator = client.get_paginator("describe_transit_gateway_attachments")
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
`session.create_client("ec2").get_paginator("describe_transit_gateway_connect_peers")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayConnectPeersPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewayConnectPeersPaginator = client.get_paginator("describe_transit_gateway_connect_peers")
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
`session.create_client("ec2").get_paginator("describe_transit_gateway_connects")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayConnectsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewayConnectsPaginator = client.get_paginator("describe_transit_gateway_connects")
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
`session.create_client("ec2").get_paginator("describe_transit_gateway_multicast_domains")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayMulticastDomainsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewayMulticastDomainsPaginator = client.get_paginator("describe_transit_gateway_multicast_domains")
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
`session.create_client("ec2").get_paginator("describe_transit_gateway_peering_attachments")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayPeeringAttachmentsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewayPeeringAttachmentsPaginator = client.get_paginator("describe_transit_gateway_peering_attachments")
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
`session.create_client("ec2").get_paginator("describe_transit_gateway_route_tables")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayRouteTablesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewayRouteTablesPaginator = client.get_paginator("describe_transit_gateway_route_tables")
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
`session.create_client("ec2").get_paginator("describe_transit_gateway_vpc_attachments")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewayVpcAttachmentsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewayVpcAttachmentsPaginator = client.get_paginator("describe_transit_gateway_vpc_attachments")
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
`session.create_client("ec2").get_paginator("describe_transit_gateways")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTransitGatewaysPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTransitGatewaysPaginator = client.get_paginator("describe_transit_gateways")
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
`session.create_client("ec2").get_paginator("describe_trunk_interface_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeTrunkInterfaceAssociationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeTrunkInterfaceAssociationsPaginator = client.get_paginator("describe_trunk_interface_associations")
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
`session.create_client("ec2").get_paginator("describe_volume_status")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVolumeStatusPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVolumeStatusPaginator = client.get_paginator("describe_volume_status")
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
`session.create_client("ec2").get_paginator("describe_volumes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVolumesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVolumesPaginator = client.get_paginator("describe_volumes")
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
`session.create_client("ec2").get_paginator("describe_volumes_modifications")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVolumesModificationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVolumesModificationsPaginator = client.get_paginator("describe_volumes_modifications")
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
`session.create_client("ec2").get_paginator("describe_vpc_classic_link_dns_support")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcClassicLinkDnsSupportPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcClassicLinkDnsSupportPaginator = client.get_paginator("describe_vpc_classic_link_dns_support")
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
`session.create_client("ec2").get_paginator("describe_vpc_endpoint_connection_notifications")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointConnectionNotificationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcEndpointConnectionNotificationsPaginator = client.get_paginator("describe_vpc_endpoint_connection_notifications")
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
`session.create_client("ec2").get_paginator("describe_vpc_endpoint_connections")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointConnectionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcEndpointConnectionsPaginator = client.get_paginator("describe_vpc_endpoint_connections")
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
`session.create_client("ec2").get_paginator("describe_vpc_endpoint_service_configurations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointServiceConfigurationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcEndpointServiceConfigurationsPaginator = client.get_paginator("describe_vpc_endpoint_service_configurations")
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
`session.create_client("ec2").get_paginator("describe_vpc_endpoint_service_permissions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointServicePermissionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcEndpointServicePermissionsPaginator = client.get_paginator("describe_vpc_endpoint_service_permissions")
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
`session.create_client("ec2").get_paginator("describe_vpc_endpoint_services")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointServicesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcEndpointServicesPaginator = client.get_paginator("describe_vpc_endpoint_services")
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
`session.create_client("ec2").get_paginator("describe_vpc_endpoints")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcEndpointsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcEndpointsPaginator = client.get_paginator("describe_vpc_endpoints")
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
`session.create_client("ec2").get_paginator("describe_vpc_peering_connections")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcPeeringConnectionsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcPeeringConnectionsPaginator = client.get_paginator("describe_vpc_peering_connections")
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
`session.create_client("ec2").get_paginator("describe_vpcs")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import DescribeVpcsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: DescribeVpcsPaginator = client.get_paginator("describe_vpcs")
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
`session.create_client("ec2").get_paginator("get_associated_ipv6_pool_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetAssociatedIpv6PoolCidrsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetAssociatedIpv6PoolCidrsPaginator = client.get_paginator("get_associated_ipv6_pool_cidrs")
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
`session.create_client("ec2").get_paginator("get_groups_for_capacity_reservation")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetGroupsForCapacityReservationPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetGroupsForCapacityReservationPaginator = client.get_paginator("get_groups_for_capacity_reservation")
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
`session.create_client("ec2").get_paginator("get_instance_types_from_instance_requirements")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetInstanceTypesFromInstanceRequirementsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetInstanceTypesFromInstanceRequirementsPaginator = client.get_paginator("get_instance_types_from_instance_requirements")
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
`session.create_client("ec2").get_paginator("get_ipam_address_history")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetIpamAddressHistoryPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetIpamAddressHistoryPaginator = client.get_paginator("get_ipam_address_history")
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
`session.create_client("ec2").get_paginator("get_ipam_pool_allocations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetIpamPoolAllocationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetIpamPoolAllocationsPaginator = client.get_paginator("get_ipam_pool_allocations")
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
`session.create_client("ec2").get_paginator("get_ipam_pool_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetIpamPoolCidrsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetIpamPoolCidrsPaginator = client.get_paginator("get_ipam_pool_cidrs")
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
`session.create_client("ec2").get_paginator("get_ipam_resource_cidrs")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetIpamResourceCidrsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetIpamResourceCidrsPaginator = client.get_paginator("get_ipam_resource_cidrs")
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
`session.create_client("ec2").get_paginator("get_managed_prefix_list_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetManagedPrefixListAssociationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetManagedPrefixListAssociationsPaginator = client.get_paginator("get_managed_prefix_list_associations")
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
`session.create_client("ec2").get_paginator("get_managed_prefix_list_entries")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetManagedPrefixListEntriesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetManagedPrefixListEntriesPaginator = client.get_paginator("get_managed_prefix_list_entries")
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
`session.create_client("ec2").get_paginator("get_spot_placement_scores")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetSpotPlacementScoresPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetSpotPlacementScoresPaginator = client.get_paginator("get_spot_placement_scores")
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
`session.create_client("ec2").get_paginator("get_transit_gateway_attachment_propagations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetTransitGatewayAttachmentPropagationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetTransitGatewayAttachmentPropagationsPaginator = client.get_paginator("get_transit_gateway_attachment_propagations")
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
`session.create_client("ec2").get_paginator("get_transit_gateway_multicast_domain_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetTransitGatewayMulticastDomainAssociationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetTransitGatewayMulticastDomainAssociationsPaginator = client.get_paginator("get_transit_gateway_multicast_domain_associations")
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
`session.create_client("ec2").get_paginator("get_transit_gateway_prefix_list_references")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetTransitGatewayPrefixListReferencesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetTransitGatewayPrefixListReferencesPaginator = client.get_paginator("get_transit_gateway_prefix_list_references")
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
`session.create_client("ec2").get_paginator("get_transit_gateway_route_table_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetTransitGatewayRouteTableAssociationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetTransitGatewayRouteTableAssociationsPaginator = client.get_paginator("get_transit_gateway_route_table_associations")
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
`session.create_client("ec2").get_paginator("get_transit_gateway_route_table_propagations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetTransitGatewayRouteTablePropagationsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetTransitGatewayRouteTablePropagationsPaginator = client.get_paginator("get_transit_gateway_route_table_propagations")
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
`session.create_client("ec2").get_paginator("get_vpn_connection_device_types")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import GetVpnConnectionDeviceTypesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: GetVpnConnectionDeviceTypesPaginator = client.get_paginator("get_vpn_connection_device_types")
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
`session.create_client("ec2").get_paginator("list_snapshots_in_recycle_bin")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import ListSnapshotsInRecycleBinPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: ListSnapshotsInRecycleBinPaginator = client.get_paginator("list_snapshots_in_recycle_bin")
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
`session.create_client("ec2").get_paginator("search_local_gateway_routes")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import SearchLocalGatewayRoutesPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: SearchLocalGatewayRoutesPaginator = client.get_paginator("search_local_gateway_routes")
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
`session.create_client("ec2").get_paginator("search_transit_gateway_multicast_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ec2.paginator import SearchTransitGatewayMulticastGroupsPaginator

session = get_session()
async with session.create_client("ec2") as client:
    client: EC2Client
    paginator: SearchTransitGatewayMulticastGroupsPaginator = client.get_paginator("search_transit_gateway_multicast_groups")
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
