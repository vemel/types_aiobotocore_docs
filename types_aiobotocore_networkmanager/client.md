<a id="networkmanagerclient-for-aiobotocore-networkmanager-module"></a>

# NetworkManagerClient for aiobotocore NetworkManager module

> [Index](..) > [NetworkManager](.) > NetworkManagerClient

Auto-generated documentation for
[NetworkManager](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
type annotations stubs module
[types-aiobotocore-networkmanager](https://pypi.org/project/types-aiobotocore-networkmanager/).

- [NetworkManagerClient for aiobotocore NetworkManager module](#networkmanagerclient-for-aiobotocore-networkmanager-module)
  - [NetworkManagerClient](#networkmanagerclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_attachment](#accept_attachment)
    - [associate_connect_peer](#associate_connect_peer)
    - [associate_customer_gateway](#associate_customer_gateway)
    - [associate_link](#associate_link)
    - [associate_transit_gateway_connect_peer](#associate_transit_gateway_connect_peer)
    - [can_paginate](#can_paginate)
    - [create_connect_attachment](#create_connect_attachment)
    - [create_connect_peer](#create_connect_peer)
    - [create_connection](#create_connection)
    - [create_core_network](#create_core_network)
    - [create_device](#create_device)
    - [create_global_network](#create_global_network)
    - [create_link](#create_link)
    - [create_site](#create_site)
    - [create_site_to_site_vpn_attachment](#create_site_to_site_vpn_attachment)
    - [create_vpc_attachment](#create_vpc_attachment)
    - [delete_attachment](#delete_attachment)
    - [delete_connect_peer](#delete_connect_peer)
    - [delete_connection](#delete_connection)
    - [delete_core_network](#delete_core_network)
    - [delete_core_network_policy_version](#delete_core_network_policy_version)
    - [delete_device](#delete_device)
    - [delete_global_network](#delete_global_network)
    - [delete_link](#delete_link)
    - [delete_resource_policy](#delete_resource_policy)
    - [delete_site](#delete_site)
    - [deregister_transit_gateway](#deregister_transit_gateway)
    - [describe_global_networks](#describe_global_networks)
    - [disassociate_connect_peer](#disassociate_connect_peer)
    - [disassociate_customer_gateway](#disassociate_customer_gateway)
    - [disassociate_link](#disassociate_link)
    - [disassociate_transit_gateway_connect_peer](#disassociate_transit_gateway_connect_peer)
    - [execute_core_network_change_set](#execute_core_network_change_set)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_connect_attachment](#get_connect_attachment)
    - [get_connect_peer](#get_connect_peer)
    - [get_connect_peer_associations](#get_connect_peer_associations)
    - [get_connections](#get_connections)
    - [get_core_network](#get_core_network)
    - [get_core_network_change_set](#get_core_network_change_set)
    - [get_core_network_policy](#get_core_network_policy)
    - [get_customer_gateway_associations](#get_customer_gateway_associations)
    - [get_devices](#get_devices)
    - [get_link_associations](#get_link_associations)
    - [get_links](#get_links)
    - [get_network_resource_counts](#get_network_resource_counts)
    - [get_network_resource_relationships](#get_network_resource_relationships)
    - [get_network_resources](#get_network_resources)
    - [get_network_routes](#get_network_routes)
    - [get_network_telemetry](#get_network_telemetry)
    - [get_resource_policy](#get_resource_policy)
    - [get_route_analysis](#get_route_analysis)
    - [get_site_to_site_vpn_attachment](#get_site_to_site_vpn_attachment)
    - [get_sites](#get_sites)
    - [get_transit_gateway_connect_peer_associations](#get_transit_gateway_connect_peer_associations)
    - [get_transit_gateway_registrations](#get_transit_gateway_registrations)
    - [get_vpc_attachment](#get_vpc_attachment)
    - [list_attachments](#list_attachments)
    - [list_connect_peers](#list_connect_peers)
    - [list_core_network_policy_versions](#list_core_network_policy_versions)
    - [list_core_networks](#list_core_networks)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_core_network_policy](#put_core_network_policy)
    - [put_resource_policy](#put_resource_policy)
    - [register_transit_gateway](#register_transit_gateway)
    - [reject_attachment](#reject_attachment)
    - [restore_core_network_policy_version](#restore_core_network_policy_version)
    - [start_route_analysis](#start_route_analysis)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_connection](#update_connection)
    - [update_core_network](#update_core_network)
    - [update_device](#update_device)
    - [update_global_network](#update_global_network)
    - [update_link](#update_link)
    - [update_network_resource_metadata](#update_network_resource_metadata)
    - [update_site](#update_site)
    - [update_vpc_attachment](#update_vpc_attachment)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="networkmanagerclient"></a>

## NetworkManagerClient

Type annotations for `session.create_client("networkmanager")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_networkmanager.client import NetworkManagerClient

session = get_session()
async with session.create_client("networkmanager") as client:
    client: NetworkManagerClient
```

Boto3 documentation:
[NetworkManager.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_networkmanager.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.CoreNetworkPolicyException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

NetworkManagerClient exceptions.

Type annotations for `session.create_client("networkmanager").exceptions`
method.

Boto3 documentation:
[NetworkManager.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept_attachment"></a>

### accept_attachment

Accepts a core network attachment request.

Type annotations for
`session.create_client("networkmanager").accept_attachment` method.

Boto3 documentation:
[NetworkManager.Client.accept_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.accept_attachment)

Asynchronous method. Use `await accept_attachment(...)` for a synchronous call.

Arguments mapping described in
[AcceptAttachmentRequestRequestTypeDef](./type_defs.md#acceptattachmentrequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*

Returns a `Coroutine` for
[AcceptAttachmentResponseTypeDef](./type_defs.md#acceptattachmentresponsetypedef).

<a id="associate_connect_peer"></a>

### associate_connect_peer

Associates a core network Connect peer with a device and optionally, with a
link.

Type annotations for
`session.create_client("networkmanager").associate_connect_peer` method.

Boto3 documentation:
[NetworkManager.Client.associate_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.associate_connect_peer)

Asynchronous method. Use `await associate_connect_peer(...)` for a synchronous
call.

Arguments mapping described in
[AssociateConnectPeerRequestRequestTypeDef](./type_defs.md#associateconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ConnectPeerId`: `str` *(required)*
- `DeviceId`: `str` *(required)*
- `LinkId`: `str`

Returns a `Coroutine` for
[AssociateConnectPeerResponseTypeDef](./type_defs.md#associateconnectpeerresponsetypedef).

<a id="associate_customer_gateway"></a>

### associate_customer_gateway

Associates a customer gateway with a device and optionally, with a link.

Type annotations for
`session.create_client("networkmanager").associate_customer_gateway` method.

Boto3 documentation:
[NetworkManager.Client.associate_customer_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.associate_customer_gateway)

Asynchronous method. Use `await associate_customer_gateway(...)` for a
synchronous call.

Arguments mapping described in
[AssociateCustomerGatewayRequestRequestTypeDef](./type_defs.md#associatecustomergatewayrequestrequesttypedef).

Keyword-only arguments:

- `CustomerGatewayArn`: `str` *(required)*
- `GlobalNetworkId`: `str` *(required)*
- `DeviceId`: `str` *(required)*
- `LinkId`: `str`

Returns a `Coroutine` for
[AssociateCustomerGatewayResponseTypeDef](./type_defs.md#associatecustomergatewayresponsetypedef).

<a id="associate_link"></a>

### associate_link

Associates a link to a device.

Type annotations for `session.create_client("networkmanager").associate_link`
method.

Boto3 documentation:
[NetworkManager.Client.associate_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.associate_link)

Asynchronous method. Use `await associate_link(...)` for a synchronous call.

Arguments mapping described in
[AssociateLinkRequestRequestTypeDef](./type_defs.md#associatelinkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `DeviceId`: `str` *(required)*
- `LinkId`: `str` *(required)*

Returns a `Coroutine` for
[AssociateLinkResponseTypeDef](./type_defs.md#associatelinkresponsetypedef).

<a id="associate_transit_gateway_connect_peer"></a>

### associate_transit_gateway_connect_peer

Associates a transit gateway Connect peer with a device, and optionally, with a
link.

Type annotations for
`session.create_client("networkmanager").associate_transit_gateway_connect_peer`
method.

Boto3 documentation:
[NetworkManager.Client.associate_transit_gateway_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.associate_transit_gateway_connect_peer)

Asynchronous method. Use `await associate_transit_gateway_connect_peer(...)`
for a synchronous call.

Arguments mapping described in
[AssociateTransitGatewayConnectPeerRequestRequestTypeDef](./type_defs.md#associatetransitgatewayconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `TransitGatewayConnectPeerArn`: `str` *(required)*
- `DeviceId`: `str` *(required)*
- `LinkId`: `str`

Returns a `Coroutine` for
[AssociateTransitGatewayConnectPeerResponseTypeDef](./type_defs.md#associatetransitgatewayconnectpeerresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("networkmanager").can_paginate`
method.

Boto3 documentation:
[NetworkManager.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_connect_attachment"></a>

### create_connect_attachment

Creates a core network Connect attachment from a specified core network
attachment.

Type annotations for
`session.create_client("networkmanager").create_connect_attachment` method.

Boto3 documentation:
[NetworkManager.Client.create_connect_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_connect_attachment)

Asynchronous method. Use `await create_connect_attachment(...)` for a
synchronous call.

Arguments mapping described in
[CreateConnectAttachmentRequestRequestTypeDef](./type_defs.md#createconnectattachmentrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `EdgeLocation`: `str` *(required)*
- `TransportAttachmentId`: `str` *(required)*
- `Options`:
  [ConnectAttachmentOptionsTypeDef](./type_defs.md#connectattachmentoptionstypedef)
  *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateConnectAttachmentResponseTypeDef](./type_defs.md#createconnectattachmentresponsetypedef).

<a id="create_connect_peer"></a>

### create_connect_peer

Creates a core network connect peer for a specified core network connect
attachment between a core network and an appliance.

Type annotations for
`session.create_client("networkmanager").create_connect_peer` method.

Boto3 documentation:
[NetworkManager.Client.create_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_connect_peer)

Asynchronous method. Use `await create_connect_peer(...)` for a synchronous
call.

Arguments mapping described in
[CreateConnectPeerRequestRequestTypeDef](./type_defs.md#createconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `ConnectAttachmentId`: `str` *(required)*
- `PeerAddress`: `str` *(required)*
- `InsideCidrBlocks`: `Sequence`\[`str`\] *(required)*
- `CoreNetworkAddress`: `str`
- `BgpOptions`: [BgpOptionsTypeDef](./type_defs.md#bgpoptionstypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateConnectPeerResponseTypeDef](./type_defs.md#createconnectpeerresponsetypedef).

<a id="create_connection"></a>

### create_connection

Creates a connection between two devices.

Type annotations for
`session.create_client("networkmanager").create_connection` method.

Boto3 documentation:
[NetworkManager.Client.create_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_connection)

Asynchronous method. Use `await create_connection(...)` for a synchronous call.

Arguments mapping described in
[CreateConnectionRequestRequestTypeDef](./type_defs.md#createconnectionrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `DeviceId`: `str` *(required)*
- `ConnectedDeviceId`: `str` *(required)*
- `LinkId`: `str`
- `ConnectedLinkId`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateConnectionResponseTypeDef](./type_defs.md#createconnectionresponsetypedef).

<a id="create_core_network"></a>

### create_core_network

Creates a core network as part of your global network, and optionally, with a
core network policy.

Type annotations for
`session.create_client("networkmanager").create_core_network` method.

Boto3 documentation:
[NetworkManager.Client.create_core_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_core_network)

Asynchronous method. Use `await create_core_network(...)` for a synchronous
call.

Arguments mapping described in
[CreateCoreNetworkRequestRequestTypeDef](./type_defs.md#createcorenetworkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `PolicyDocument`: `str`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateCoreNetworkResponseTypeDef](./type_defs.md#createcorenetworkresponsetypedef).

<a id="create_device"></a>

### create_device

Creates a new device in a global network.

Type annotations for `session.create_client("networkmanager").create_device`
method.

Boto3 documentation:
[NetworkManager.Client.create_device](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_device)

Asynchronous method. Use `await create_device(...)` for a synchronous call.

Arguments mapping described in
[CreateDeviceRequestRequestTypeDef](./type_defs.md#createdevicerequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `AWSLocation`: [AWSLocationTypeDef](./type_defs.md#awslocationtypedef)
- `Description`: `str`
- `Type`: `str`
- `Vendor`: `str`
- `Model`: `str`
- `SerialNumber`: `str`
- `Location`: [LocationTypeDef](./type_defs.md#locationtypedef)
- `SiteId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDeviceResponseTypeDef](./type_defs.md#createdeviceresponsetypedef).

<a id="create_global_network"></a>

### create_global_network

Creates a new, empty global network.

Type annotations for
`session.create_client("networkmanager").create_global_network` method.

Boto3 documentation:
[NetworkManager.Client.create_global_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_global_network)

Asynchronous method. Use `await create_global_network(...)` for a synchronous
call.

Arguments mapping described in
[CreateGlobalNetworkRequestRequestTypeDef](./type_defs.md#createglobalnetworkrequestrequesttypedef).

Keyword-only arguments:

- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateGlobalNetworkResponseTypeDef](./type_defs.md#createglobalnetworkresponsetypedef).

<a id="create_link"></a>

### create_link

Creates a new link for a specified site.

Type annotations for `session.create_client("networkmanager").create_link`
method.

Boto3 documentation:
[NetworkManager.Client.create_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_link)

Asynchronous method. Use `await create_link(...)` for a synchronous call.

Arguments mapping described in
[CreateLinkRequestRequestTypeDef](./type_defs.md#createlinkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `Bandwidth`: [BandwidthTypeDef](./type_defs.md#bandwidthtypedef) *(required)*
- `SiteId`: `str` *(required)*
- `Description`: `str`
- `Type`: `str`
- `Provider`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateLinkResponseTypeDef](./type_defs.md#createlinkresponsetypedef).

<a id="create_site"></a>

### create_site

Creates a new site in a global network.

Type annotations for `session.create_client("networkmanager").create_site`
method.

Boto3 documentation:
[NetworkManager.Client.create_site](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_site)

Asynchronous method. Use `await create_site(...)` for a synchronous call.

Arguments mapping described in
[CreateSiteRequestRequestTypeDef](./type_defs.md#createsiterequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `Description`: `str`
- `Location`: [LocationTypeDef](./type_defs.md#locationtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateSiteResponseTypeDef](./type_defs.md#createsiteresponsetypedef).

<a id="create_site_to_site_vpn_attachment"></a>

### create_site_to_site_vpn_attachment

Creates a site-to-site VPN attachment on an edge location of a core network.

Type annotations for
`session.create_client("networkmanager").create_site_to_site_vpn_attachment`
method.

Boto3 documentation:
[NetworkManager.Client.create_site_to_site_vpn_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_site_to_site_vpn_attachment)

Asynchronous method. Use `await create_site_to_site_vpn_attachment(...)` for a
synchronous call.

Arguments mapping described in
[CreateSiteToSiteVpnAttachmentRequestRequestTypeDef](./type_defs.md#createsitetositevpnattachmentrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `VpnConnectionArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateSiteToSiteVpnAttachmentResponseTypeDef](./type_defs.md#createsitetositevpnattachmentresponsetypedef).

<a id="create_vpc_attachment"></a>

### create_vpc_attachment

Creates a VPC attachment on an edge location of a core network.

Type annotations for
`session.create_client("networkmanager").create_vpc_attachment` method.

Boto3 documentation:
[NetworkManager.Client.create_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.create_vpc_attachment)

Asynchronous method. Use `await create_vpc_attachment(...)` for a synchronous
call.

Arguments mapping described in
[CreateVpcAttachmentRequestRequestTypeDef](./type_defs.md#createvpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `VpcArn`: `str` *(required)*
- `SubnetArns`: `Sequence`\[`str`\] *(required)*
- `Options`: [VpcOptionsTypeDef](./type_defs.md#vpcoptionstypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateVpcAttachmentResponseTypeDef](./type_defs.md#createvpcattachmentresponsetypedef).

<a id="delete_attachment"></a>

### delete_attachment

Deletes an attachment.

Type annotations for
`session.create_client("networkmanager").delete_attachment` method.

Boto3 documentation:
[NetworkManager.Client.delete_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_attachment)

Asynchronous method. Use `await delete_attachment(...)` for a synchronous call.

Arguments mapping described in
[DeleteAttachmentRequestRequestTypeDef](./type_defs.md#deleteattachmentrequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteAttachmentResponseTypeDef](./type_defs.md#deleteattachmentresponsetypedef).

<a id="delete_connect_peer"></a>

### delete_connect_peer

Deletes a Connect peer.

Type annotations for
`session.create_client("networkmanager").delete_connect_peer` method.

Boto3 documentation:
[NetworkManager.Client.delete_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_connect_peer)

Asynchronous method. Use `await delete_connect_peer(...)` for a synchronous
call.

Arguments mapping described in
[DeleteConnectPeerRequestRequestTypeDef](./type_defs.md#deleteconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `ConnectPeerId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteConnectPeerResponseTypeDef](./type_defs.md#deleteconnectpeerresponsetypedef).

<a id="delete_connection"></a>

### delete_connection

Deletes the specified connection in your global network.

Type annotations for
`session.create_client("networkmanager").delete_connection` method.

Boto3 documentation:
[NetworkManager.Client.delete_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_connection)

Asynchronous method. Use `await delete_connection(...)` for a synchronous call.

Arguments mapping described in
[DeleteConnectionRequestRequestTypeDef](./type_defs.md#deleteconnectionrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ConnectionId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteConnectionResponseTypeDef](./type_defs.md#deleteconnectionresponsetypedef).

<a id="delete_core_network"></a>

### delete_core_network

Deletes a core network along with all core network policies.

Type annotations for
`session.create_client("networkmanager").delete_core_network` method.

Boto3 documentation:
[NetworkManager.Client.delete_core_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_core_network)

Asynchronous method. Use `await delete_core_network(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCoreNetworkRequestRequestTypeDef](./type_defs.md#deletecorenetworkrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteCoreNetworkResponseTypeDef](./type_defs.md#deletecorenetworkresponsetypedef).

<a id="delete_core_network_policy_version"></a>

### delete_core_network_policy_version

Deletes a policy version from a core network.

Type annotations for
`session.create_client("networkmanager").delete_core_network_policy_version`
method.

Boto3 documentation:
[NetworkManager.Client.delete_core_network_policy_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_core_network_policy_version)

Asynchronous method. Use `await delete_core_network_policy_version(...)` for a
synchronous call.

Arguments mapping described in
[DeleteCoreNetworkPolicyVersionRequestRequestTypeDef](./type_defs.md#deletecorenetworkpolicyversionrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `PolicyVersionId`: `int` *(required)*

Returns a `Coroutine` for
[DeleteCoreNetworkPolicyVersionResponseTypeDef](./type_defs.md#deletecorenetworkpolicyversionresponsetypedef).

<a id="delete_device"></a>

### delete_device

Deletes an existing device.

Type annotations for `session.create_client("networkmanager").delete_device`
method.

Boto3 documentation:
[NetworkManager.Client.delete_device](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_device)

Asynchronous method. Use `await delete_device(...)` for a synchronous call.

Arguments mapping described in
[DeleteDeviceRequestRequestTypeDef](./type_defs.md#deletedevicerequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `DeviceId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteDeviceResponseTypeDef](./type_defs.md#deletedeviceresponsetypedef).

<a id="delete_global_network"></a>

### delete_global_network

Deletes an existing global network.

Type annotations for
`session.create_client("networkmanager").delete_global_network` method.

Boto3 documentation:
[NetworkManager.Client.delete_global_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_global_network)

Asynchronous method. Use `await delete_global_network(...)` for a synchronous
call.

Arguments mapping described in
[DeleteGlobalNetworkRequestRequestTypeDef](./type_defs.md#deleteglobalnetworkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteGlobalNetworkResponseTypeDef](./type_defs.md#deleteglobalnetworkresponsetypedef).

<a id="delete_link"></a>

### delete_link

Deletes an existing link.

Type annotations for `session.create_client("networkmanager").delete_link`
method.

Boto3 documentation:
[NetworkManager.Client.delete_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_link)

Asynchronous method. Use `await delete_link(...)` for a synchronous call.

Arguments mapping described in
[DeleteLinkRequestRequestTypeDef](./type_defs.md#deletelinkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `LinkId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteLinkResponseTypeDef](./type_defs.md#deletelinkresponsetypedef).

<a id="delete_resource_policy"></a>

### delete_resource_policy

Deletes a resource policy for the specified resource.

Type annotations for
`session.create_client("networkmanager").delete_resource_policy` method.

Boto3 documentation:
[NetworkManager.Client.delete_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_resource_policy)

Asynchronous method. Use `await delete_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResourcePolicyRequestRequestTypeDef](./type_defs.md#deleteresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_site"></a>

### delete_site

Deletes an existing site.

Type annotations for `session.create_client("networkmanager").delete_site`
method.

Boto3 documentation:
[NetworkManager.Client.delete_site](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.delete_site)

Asynchronous method. Use `await delete_site(...)` for a synchronous call.

Arguments mapping described in
[DeleteSiteRequestRequestTypeDef](./type_defs.md#deletesiterequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `SiteId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteSiteResponseTypeDef](./type_defs.md#deletesiteresponsetypedef).

<a id="deregister_transit_gateway"></a>

### deregister_transit_gateway

Deregisters a transit gateway from your global network.

Type annotations for
`session.create_client("networkmanager").deregister_transit_gateway` method.

Boto3 documentation:
[NetworkManager.Client.deregister_transit_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.deregister_transit_gateway)

Asynchronous method. Use `await deregister_transit_gateway(...)` for a
synchronous call.

Arguments mapping described in
[DeregisterTransitGatewayRequestRequestTypeDef](./type_defs.md#deregistertransitgatewayrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `TransitGatewayArn`: `str` *(required)*

Returns a `Coroutine` for
[DeregisterTransitGatewayResponseTypeDef](./type_defs.md#deregistertransitgatewayresponsetypedef).

<a id="describe_global_networks"></a>

### describe_global_networks

Describes one or more global networks.

Type annotations for
`session.create_client("networkmanager").describe_global_networks` method.

Boto3 documentation:
[NetworkManager.Client.describe_global_networks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.describe_global_networks)

Asynchronous method. Use `await describe_global_networks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeGlobalNetworksRequestRequestTypeDef](./type_defs.md#describeglobalnetworksrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeGlobalNetworksResponseTypeDef](./type_defs.md#describeglobalnetworksresponsetypedef).

<a id="disassociate_connect_peer"></a>

### disassociate_connect_peer

Disassociates a core network Connect peer from a device and a link.

Type annotations for
`session.create_client("networkmanager").disassociate_connect_peer` method.

Boto3 documentation:
[NetworkManager.Client.disassociate_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.disassociate_connect_peer)

Asynchronous method. Use `await disassociate_connect_peer(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateConnectPeerRequestRequestTypeDef](./type_defs.md#disassociateconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ConnectPeerId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateConnectPeerResponseTypeDef](./type_defs.md#disassociateconnectpeerresponsetypedef).

<a id="disassociate_customer_gateway"></a>

### disassociate_customer_gateway

Disassociates a customer gateway from a device and a link.

Type annotations for
`session.create_client("networkmanager").disassociate_customer_gateway` method.

Boto3 documentation:
[NetworkManager.Client.disassociate_customer_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.disassociate_customer_gateway)

Asynchronous method. Use `await disassociate_customer_gateway(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateCustomerGatewayRequestRequestTypeDef](./type_defs.md#disassociatecustomergatewayrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `CustomerGatewayArn`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateCustomerGatewayResponseTypeDef](./type_defs.md#disassociatecustomergatewayresponsetypedef).

<a id="disassociate_link"></a>

### disassociate_link

Disassociates an existing device from a link.

Type annotations for
`session.create_client("networkmanager").disassociate_link` method.

Boto3 documentation:
[NetworkManager.Client.disassociate_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.disassociate_link)

Asynchronous method. Use `await disassociate_link(...)` for a synchronous call.

Arguments mapping described in
[DisassociateLinkRequestRequestTypeDef](./type_defs.md#disassociatelinkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `DeviceId`: `str` *(required)*
- `LinkId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateLinkResponseTypeDef](./type_defs.md#disassociatelinkresponsetypedef).

<a id="disassociate_transit_gateway_connect_peer"></a>

### disassociate_transit_gateway_connect_peer

Disassociates a transit gateway Connect peer from a device and link.

Type annotations for
`session.create_client("networkmanager").disassociate_transit_gateway_connect_peer`
method.

Boto3 documentation:
[NetworkManager.Client.disassociate_transit_gateway_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.disassociate_transit_gateway_connect_peer)

Asynchronous method. Use `await disassociate_transit_gateway_connect_peer(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateTransitGatewayConnectPeerRequestRequestTypeDef](./type_defs.md#disassociatetransitgatewayconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `TransitGatewayConnectPeerArn`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateTransitGatewayConnectPeerResponseTypeDef](./type_defs.md#disassociatetransitgatewayconnectpeerresponsetypedef).

<a id="execute_core_network_change_set"></a>

### execute_core_network_change_set

Executes a change set on your core network.

Type annotations for
`session.create_client("networkmanager").execute_core_network_change_set`
method.

Boto3 documentation:
[NetworkManager.Client.execute_core_network_change_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.execute_core_network_change_set)

Asynchronous method. Use `await execute_core_network_change_set(...)` for a
synchronous call.

Arguments mapping described in
[ExecuteCoreNetworkChangeSetRequestRequestTypeDef](./type_defs.md#executecorenetworkchangesetrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `PolicyVersionId`: `int` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("networkmanager").generate_presigned_url` method.

Boto3 documentation:
[NetworkManager.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_connect_attachment"></a>

### get_connect_attachment

Returns information about a core network Connect attachment.

Type annotations for
`session.create_client("networkmanager").get_connect_attachment` method.

Boto3 documentation:
[NetworkManager.Client.get_connect_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_connect_attachment)

Asynchronous method. Use `await get_connect_attachment(...)` for a synchronous
call.

Arguments mapping described in
[GetConnectAttachmentRequestRequestTypeDef](./type_defs.md#getconnectattachmentrequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*

Returns a `Coroutine` for
[GetConnectAttachmentResponseTypeDef](./type_defs.md#getconnectattachmentresponsetypedef).

<a id="get_connect_peer"></a>

### get_connect_peer

Returns information about a core network Connect peer.

Type annotations for `session.create_client("networkmanager").get_connect_peer`
method.

Boto3 documentation:
[NetworkManager.Client.get_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_connect_peer)

Asynchronous method. Use `await get_connect_peer(...)` for a synchronous call.

Arguments mapping described in
[GetConnectPeerRequestRequestTypeDef](./type_defs.md#getconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `ConnectPeerId`: `str` *(required)*

Returns a `Coroutine` for
[GetConnectPeerResponseTypeDef](./type_defs.md#getconnectpeerresponsetypedef).

<a id="get_connect_peer_associations"></a>

### get_connect_peer_associations

Returns information about a core network Connect peer associations.

Type annotations for
`session.create_client("networkmanager").get_connect_peer_associations` method.

Boto3 documentation:
[NetworkManager.Client.get_connect_peer_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_connect_peer_associations)

Asynchronous method. Use `await get_connect_peer_associations(...)` for a
synchronous call.

Arguments mapping described in
[GetConnectPeerAssociationsRequestRequestTypeDef](./type_defs.md#getconnectpeerassociationsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ConnectPeerIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetConnectPeerAssociationsResponseTypeDef](./type_defs.md#getconnectpeerassociationsresponsetypedef).

<a id="get_connections"></a>

### get_connections

Gets information about one or more of your connections in a global network.

Type annotations for `session.create_client("networkmanager").get_connections`
method.

Boto3 documentation:
[NetworkManager.Client.get_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_connections)

Asynchronous method. Use `await get_connections(...)` for a synchronous call.

Arguments mapping described in
[GetConnectionsRequestRequestTypeDef](./type_defs.md#getconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ConnectionIds`: `Sequence`\[`str`\]
- `DeviceId`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetConnectionsResponseTypeDef](./type_defs.md#getconnectionsresponsetypedef).

<a id="get_core_network"></a>

### get_core_network

Returns information about a core network.

Type annotations for `session.create_client("networkmanager").get_core_network`
method.

Boto3 documentation:
[NetworkManager.Client.get_core_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_core_network)

Asynchronous method. Use `await get_core_network(...)` for a synchronous call.

Arguments mapping described in
[GetCoreNetworkRequestRequestTypeDef](./type_defs.md#getcorenetworkrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*

Returns a `Coroutine` for
[GetCoreNetworkResponseTypeDef](./type_defs.md#getcorenetworkresponsetypedef).

<a id="get_core_network_change_set"></a>

### get_core_network_change_set

Returns a change set between the LIVE core network policy and a submitted
policy.

Type annotations for
`session.create_client("networkmanager").get_core_network_change_set` method.

Boto3 documentation:
[NetworkManager.Client.get_core_network_change_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_core_network_change_set)

Asynchronous method. Use `await get_core_network_change_set(...)` for a
synchronous call.

Arguments mapping described in
[GetCoreNetworkChangeSetRequestRequestTypeDef](./type_defs.md#getcorenetworkchangesetrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `PolicyVersionId`: `int` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetCoreNetworkChangeSetResponseTypeDef](./type_defs.md#getcorenetworkchangesetresponsetypedef).

<a id="get_core_network_policy"></a>

### get_core_network_policy

Gets details about a core network policy.

Type annotations for
`session.create_client("networkmanager").get_core_network_policy` method.

Boto3 documentation:
[NetworkManager.Client.get_core_network_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_core_network_policy)

Asynchronous method. Use `await get_core_network_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetCoreNetworkPolicyRequestRequestTypeDef](./type_defs.md#getcorenetworkpolicyrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `PolicyVersionId`: `int`
- `Alias`:
  [CoreNetworkPolicyAliasType](./literals.md#corenetworkpolicyaliastype)

Returns a `Coroutine` for
[GetCoreNetworkPolicyResponseTypeDef](./type_defs.md#getcorenetworkpolicyresponsetypedef).

<a id="get_customer_gateway_associations"></a>

### get_customer_gateway_associations

Gets the association information for customer gateways that are associated with
devices and links in your global network.

Type annotations for
`session.create_client("networkmanager").get_customer_gateway_associations`
method.

Boto3 documentation:
[NetworkManager.Client.get_customer_gateway_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_customer_gateway_associations)

Asynchronous method. Use `await get_customer_gateway_associations(...)` for a
synchronous call.

Arguments mapping described in
[GetCustomerGatewayAssociationsRequestRequestTypeDef](./type_defs.md#getcustomergatewayassociationsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `CustomerGatewayArns`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetCustomerGatewayAssociationsResponseTypeDef](./type_defs.md#getcustomergatewayassociationsresponsetypedef).

<a id="get_devices"></a>

### get_devices

Gets information about one or more of your devices in a global network.

Type annotations for `session.create_client("networkmanager").get_devices`
method.

Boto3 documentation:
[NetworkManager.Client.get_devices](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_devices)

Asynchronous method. Use `await get_devices(...)` for a synchronous call.

Arguments mapping described in
[GetDevicesRequestRequestTypeDef](./type_defs.md#getdevicesrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `DeviceIds`: `Sequence`\[`str`\]
- `SiteId`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetDevicesResponseTypeDef](./type_defs.md#getdevicesresponsetypedef).

<a id="get_link_associations"></a>

### get_link_associations

Gets the link associations for a device or a link.

Type annotations for
`session.create_client("networkmanager").get_link_associations` method.

Boto3 documentation:
[NetworkManager.Client.get_link_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_link_associations)

Asynchronous method. Use `await get_link_associations(...)` for a synchronous
call.

Arguments mapping described in
[GetLinkAssociationsRequestRequestTypeDef](./type_defs.md#getlinkassociationsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `DeviceId`: `str`
- `LinkId`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetLinkAssociationsResponseTypeDef](./type_defs.md#getlinkassociationsresponsetypedef).

<a id="get_links"></a>

### get_links

Gets information about one or more links in a specified global network.

Type annotations for `session.create_client("networkmanager").get_links`
method.

Boto3 documentation:
[NetworkManager.Client.get_links](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_links)

Asynchronous method. Use `await get_links(...)` for a synchronous call.

Arguments mapping described in
[GetLinksRequestRequestTypeDef](./type_defs.md#getlinksrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `LinkIds`: `Sequence`\[`str`\]
- `SiteId`: `str`
- `Type`: `str`
- `Provider`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetLinksResponseTypeDef](./type_defs.md#getlinksresponsetypedef).

<a id="get_network_resource_counts"></a>

### get_network_resource_counts

Gets the count of network resources, by resource type, for the specified global
network.

Type annotations for
`session.create_client("networkmanager").get_network_resource_counts` method.

Boto3 documentation:
[NetworkManager.Client.get_network_resource_counts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_network_resource_counts)

Asynchronous method. Use `await get_network_resource_counts(...)` for a
synchronous call.

Arguments mapping described in
[GetNetworkResourceCountsRequestRequestTypeDef](./type_defs.md#getnetworkresourcecountsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ResourceType`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetNetworkResourceCountsResponseTypeDef](./type_defs.md#getnetworkresourcecountsresponsetypedef).

<a id="get_network_resource_relationships"></a>

### get_network_resource_relationships

Gets the network resource relationships for the specified global network.

Type annotations for
`session.create_client("networkmanager").get_network_resource_relationships`
method.

Boto3 documentation:
[NetworkManager.Client.get_network_resource_relationships](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_network_resource_relationships)

Asynchronous method. Use `await get_network_resource_relationships(...)` for a
synchronous call.

Arguments mapping described in
[GetNetworkResourceRelationshipsRequestRequestTypeDef](./type_defs.md#getnetworkresourcerelationshipsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `CoreNetworkId`: `str`
- `RegisteredGatewayArn`: `str`
- `AwsRegion`: `str`
- `AccountId`: `str`
- `ResourceType`: `str`
- `ResourceArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetNetworkResourceRelationshipsResponseTypeDef](./type_defs.md#getnetworkresourcerelationshipsresponsetypedef).

<a id="get_network_resources"></a>

### get_network_resources

Describes the network resources for the specified global network.

Type annotations for
`session.create_client("networkmanager").get_network_resources` method.

Boto3 documentation:
[NetworkManager.Client.get_network_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_network_resources)

Asynchronous method. Use `await get_network_resources(...)` for a synchronous
call.

Arguments mapping described in
[GetNetworkResourcesRequestRequestTypeDef](./type_defs.md#getnetworkresourcesrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `CoreNetworkId`: `str`
- `RegisteredGatewayArn`: `str`
- `AwsRegion`: `str`
- `AccountId`: `str`
- `ResourceType`: `str`
- `ResourceArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetNetworkResourcesResponseTypeDef](./type_defs.md#getnetworkresourcesresponsetypedef).

<a id="get_network_routes"></a>

### get_network_routes

Gets the network routes of the specified global network.

Type annotations for
`session.create_client("networkmanager").get_network_routes` method.

Boto3 documentation:
[NetworkManager.Client.get_network_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_network_routes)

Asynchronous method. Use `await get_network_routes(...)` for a synchronous
call.

Arguments mapping described in
[GetNetworkRoutesRequestRequestTypeDef](./type_defs.md#getnetworkroutesrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `RouteTableIdentifier`:
  [RouteTableIdentifierTypeDef](./type_defs.md#routetableidentifiertypedef)
  *(required)*
- `ExactCidrMatches`: `Sequence`\[`str`\]
- `LongestPrefixMatches`: `Sequence`\[`str`\]
- `SubnetOfMatches`: `Sequence`\[`str`\]
- `SupernetOfMatches`: `Sequence`\[`str`\]
- `PrefixListIds`: `Sequence`\[`str`\]
- `States`: `Sequence`\[[RouteStateType](./literals.md#routestatetype)\]
- `Types`: `Sequence`\[[RouteTypeType](./literals.md#routetypetype)\]
- `DestinationFilters`: `Mapping`\[`str`, `Sequence`\[`str`\]\]

Returns a `Coroutine` for
[GetNetworkRoutesResponseTypeDef](./type_defs.md#getnetworkroutesresponsetypedef).

<a id="get_network_telemetry"></a>

### get_network_telemetry

Gets the network telemetry of the specified global network.

Type annotations for
`session.create_client("networkmanager").get_network_telemetry` method.

Boto3 documentation:
[NetworkManager.Client.get_network_telemetry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_network_telemetry)

Asynchronous method. Use `await get_network_telemetry(...)` for a synchronous
call.

Arguments mapping described in
[GetNetworkTelemetryRequestRequestTypeDef](./type_defs.md#getnetworktelemetryrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `CoreNetworkId`: `str`
- `RegisteredGatewayArn`: `str`
- `AwsRegion`: `str`
- `AccountId`: `str`
- `ResourceType`: `str`
- `ResourceArn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetNetworkTelemetryResponseTypeDef](./type_defs.md#getnetworktelemetryresponsetypedef).

<a id="get_resource_policy"></a>

### get_resource_policy

Returns information about a resource policy.

Type annotations for
`session.create_client("networkmanager").get_resource_policy` method.

Boto3 documentation:
[NetworkManager.Client.get_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_resource_policy)

Asynchronous method. Use `await get_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetResourcePolicyRequestRequestTypeDef](./type_defs.md#getresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[GetResourcePolicyResponseTypeDef](./type_defs.md#getresourcepolicyresponsetypedef).

<a id="get_route_analysis"></a>

### get_route_analysis

Gets information about the specified route analysis.

Type annotations for
`session.create_client("networkmanager").get_route_analysis` method.

Boto3 documentation:
[NetworkManager.Client.get_route_analysis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_route_analysis)

Asynchronous method. Use `await get_route_analysis(...)` for a synchronous
call.

Arguments mapping described in
[GetRouteAnalysisRequestRequestTypeDef](./type_defs.md#getrouteanalysisrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `RouteAnalysisId`: `str` *(required)*

Returns a `Coroutine` for
[GetRouteAnalysisResponseTypeDef](./type_defs.md#getrouteanalysisresponsetypedef).

<a id="get_site_to_site_vpn_attachment"></a>

### get_site_to_site_vpn_attachment

Returns information about a site-to-site VPN attachment.

Type annotations for
`session.create_client("networkmanager").get_site_to_site_vpn_attachment`
method.

Boto3 documentation:
[NetworkManager.Client.get_site_to_site_vpn_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_site_to_site_vpn_attachment)

Asynchronous method. Use `await get_site_to_site_vpn_attachment(...)` for a
synchronous call.

Arguments mapping described in
[GetSiteToSiteVpnAttachmentRequestRequestTypeDef](./type_defs.md#getsitetositevpnattachmentrequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*

Returns a `Coroutine` for
[GetSiteToSiteVpnAttachmentResponseTypeDef](./type_defs.md#getsitetositevpnattachmentresponsetypedef).

<a id="get_sites"></a>

### get_sites

Gets information about one or more of your sites in a global network.

Type annotations for `session.create_client("networkmanager").get_sites`
method.

Boto3 documentation:
[NetworkManager.Client.get_sites](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_sites)

Asynchronous method. Use `await get_sites(...)` for a synchronous call.

Arguments mapping described in
[GetSitesRequestRequestTypeDef](./type_defs.md#getsitesrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `SiteIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetSitesResponseTypeDef](./type_defs.md#getsitesresponsetypedef).

<a id="get_transit_gateway_connect_peer_associations"></a>

### get_transit_gateway_connect_peer_associations

Gets information about one or more of your transit gateway Connect peer
associations in a global network.

Type annotations for
`session.create_client("networkmanager").get_transit_gateway_connect_peer_associations`
method.

Boto3 documentation:
[NetworkManager.Client.get_transit_gateway_connect_peer_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_transit_gateway_connect_peer_associations)

Asynchronous method. Use
`await get_transit_gateway_connect_peer_associations(...)` for a synchronous
call.

Arguments mapping described in
[GetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef](./type_defs.md#gettransitgatewayconnectpeerassociationsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `TransitGatewayConnectPeerArns`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetTransitGatewayConnectPeerAssociationsResponseTypeDef](./type_defs.md#gettransitgatewayconnectpeerassociationsresponsetypedef).

<a id="get_transit_gateway_registrations"></a>

### get_transit_gateway_registrations

Gets information about the transit gateway registrations in a specified global
network.

Type annotations for
`session.create_client("networkmanager").get_transit_gateway_registrations`
method.

Boto3 documentation:
[NetworkManager.Client.get_transit_gateway_registrations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_transit_gateway_registrations)

Asynchronous method. Use `await get_transit_gateway_registrations(...)` for a
synchronous call.

Arguments mapping described in
[GetTransitGatewayRegistrationsRequestRequestTypeDef](./type_defs.md#gettransitgatewayregistrationsrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `TransitGatewayArns`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetTransitGatewayRegistrationsResponseTypeDef](./type_defs.md#gettransitgatewayregistrationsresponsetypedef).

<a id="get_vpc_attachment"></a>

### get_vpc_attachment

Returns information about a VPC attachment.

Type annotations for
`session.create_client("networkmanager").get_vpc_attachment` method.

Boto3 documentation:
[NetworkManager.Client.get_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.get_vpc_attachment)

Asynchronous method. Use `await get_vpc_attachment(...)` for a synchronous
call.

Arguments mapping described in
[GetVpcAttachmentRequestRequestTypeDef](./type_defs.md#getvpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*

Returns a `Coroutine` for
[GetVpcAttachmentResponseTypeDef](./type_defs.md#getvpcattachmentresponsetypedef).

<a id="list_attachments"></a>

### list_attachments

Returns a list of core network attachments.

Type annotations for `session.create_client("networkmanager").list_attachments`
method.

Boto3 documentation:
[NetworkManager.Client.list_attachments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.list_attachments)

Asynchronous method. Use `await list_attachments(...)` for a synchronous call.

Arguments mapping described in
[ListAttachmentsRequestRequestTypeDef](./type_defs.md#listattachmentsrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str`
- `AttachmentType`: [AttachmentTypeType](./literals.md#attachmenttypetype)
- `EdgeLocation`: `str`
- `State`: [AttachmentStateType](./literals.md#attachmentstatetype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAttachmentsResponseTypeDef](./type_defs.md#listattachmentsresponsetypedef).

<a id="list_connect_peers"></a>

### list_connect_peers

Returns a list of core network Connect peers.

Type annotations for
`session.create_client("networkmanager").list_connect_peers` method.

Boto3 documentation:
[NetworkManager.Client.list_connect_peers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.list_connect_peers)

Asynchronous method. Use `await list_connect_peers(...)` for a synchronous
call.

Arguments mapping described in
[ListConnectPeersRequestRequestTypeDef](./type_defs.md#listconnectpeersrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str`
- `ConnectAttachmentId`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListConnectPeersResponseTypeDef](./type_defs.md#listconnectpeersresponsetypedef).

<a id="list_core_network_policy_versions"></a>

### list_core_network_policy_versions

Returns a list of core network policy versions.

Type annotations for
`session.create_client("networkmanager").list_core_network_policy_versions`
method.

Boto3 documentation:
[NetworkManager.Client.list_core_network_policy_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.list_core_network_policy_versions)

Asynchronous method. Use `await list_core_network_policy_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListCoreNetworkPolicyVersionsRequestRequestTypeDef](./type_defs.md#listcorenetworkpolicyversionsrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListCoreNetworkPolicyVersionsResponseTypeDef](./type_defs.md#listcorenetworkpolicyversionsresponsetypedef).

<a id="list_core_networks"></a>

### list_core_networks

Returns a list of owned and shared core networks.

Type annotations for
`session.create_client("networkmanager").list_core_networks` method.

Boto3 documentation:
[NetworkManager.Client.list_core_networks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.list_core_networks)

Asynchronous method. Use `await list_core_networks(...)` for a synchronous
call.

Arguments mapping described in
[ListCoreNetworksRequestRequestTypeDef](./type_defs.md#listcorenetworksrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListCoreNetworksResponseTypeDef](./type_defs.md#listcorenetworksresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags for a specified resource.

Type annotations for
`session.create_client("networkmanager").list_tags_for_resource` method.

Boto3 documentation:
[NetworkManager.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_core_network_policy"></a>

### put_core_network_policy

Creates a new, immutable version of a core network policy.

Type annotations for
`session.create_client("networkmanager").put_core_network_policy` method.

Boto3 documentation:
[NetworkManager.Client.put_core_network_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.put_core_network_policy)

Asynchronous method. Use `await put_core_network_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutCoreNetworkPolicyRequestRequestTypeDef](./type_defs.md#putcorenetworkpolicyrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `PolicyDocument`: `str` *(required)*
- `Description`: `str`
- `LatestVersionId`: `int`
- `ClientToken`: `str`

Returns a `Coroutine` for
[PutCoreNetworkPolicyResponseTypeDef](./type_defs.md#putcorenetworkpolicyresponsetypedef).

<a id="put_resource_policy"></a>

### put_resource_policy

Creates or updates a resource policy.

Type annotations for
`session.create_client("networkmanager").put_resource_policy` method.

Boto3 documentation:
[NetworkManager.Client.put_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.put_resource_policy)

Asynchronous method. Use `await put_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutResourcePolicyRequestRequestTypeDef](./type_defs.md#putresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `PolicyDocument`: `str` *(required)*
- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="register_transit_gateway"></a>

### register_transit_gateway

Registers a transit gateway in your global network.

Type annotations for
`session.create_client("networkmanager").register_transit_gateway` method.

Boto3 documentation:
[NetworkManager.Client.register_transit_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.register_transit_gateway)

Asynchronous method. Use `await register_transit_gateway(...)` for a
synchronous call.

Arguments mapping described in
[RegisterTransitGatewayRequestRequestTypeDef](./type_defs.md#registertransitgatewayrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `TransitGatewayArn`: `str` *(required)*

Returns a `Coroutine` for
[RegisterTransitGatewayResponseTypeDef](./type_defs.md#registertransitgatewayresponsetypedef).

<a id="reject_attachment"></a>

### reject_attachment

Rejects a core network attachment request.

Type annotations for
`session.create_client("networkmanager").reject_attachment` method.

Boto3 documentation:
[NetworkManager.Client.reject_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.reject_attachment)

Asynchronous method. Use `await reject_attachment(...)` for a synchronous call.

Arguments mapping described in
[RejectAttachmentRequestRequestTypeDef](./type_defs.md#rejectattachmentrequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*

Returns a `Coroutine` for
[RejectAttachmentResponseTypeDef](./type_defs.md#rejectattachmentresponsetypedef).

<a id="restore_core_network_policy_version"></a>

### restore_core_network_policy_version

Restores a previous policy version as a new, immutable version of a core
network policy.

Type annotations for
`session.create_client("networkmanager").restore_core_network_policy_version`
method.

Boto3 documentation:
[NetworkManager.Client.restore_core_network_policy_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.restore_core_network_policy_version)

Asynchronous method. Use `await restore_core_network_policy_version(...)` for a
synchronous call.

Arguments mapping described in
[RestoreCoreNetworkPolicyVersionRequestRequestTypeDef](./type_defs.md#restorecorenetworkpolicyversionrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `PolicyVersionId`: `int` *(required)*

Returns a `Coroutine` for
[RestoreCoreNetworkPolicyVersionResponseTypeDef](./type_defs.md#restorecorenetworkpolicyversionresponsetypedef).

<a id="start_route_analysis"></a>

### start_route_analysis

Starts analyzing the routing path between the specified source and destination.

Type annotations for
`session.create_client("networkmanager").start_route_analysis` method.

Boto3 documentation:
[NetworkManager.Client.start_route_analysis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.start_route_analysis)

Asynchronous method. Use `await start_route_analysis(...)` for a synchronous
call.

Arguments mapping described in
[StartRouteAnalysisRequestRequestTypeDef](./type_defs.md#startrouteanalysisrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `Source`:
  [RouteAnalysisEndpointOptionsSpecificationTypeDef](./type_defs.md#routeanalysisendpointoptionsspecificationtypedef)
  *(required)*
- `Destination`:
  [RouteAnalysisEndpointOptionsSpecificationTypeDef](./type_defs.md#routeanalysisendpointoptionsspecificationtypedef)
  *(required)*
- `IncludeReturnPath`: `bool`
- `UseMiddleboxes`: `bool`

Returns a `Coroutine` for
[StartRouteAnalysisResponseTypeDef](./type_defs.md#startrouteanalysisresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Tags a specified resource.

Type annotations for `session.create_client("networkmanager").tag_resource`
method.

Boto3 documentation:
[NetworkManager.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from a specified resource.

Type annotations for `session.create_client("networkmanager").untag_resource`
method.

Boto3 documentation:
[NetworkManager.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_connection"></a>

### update_connection

Updates the information for an existing connection.

Type annotations for
`session.create_client("networkmanager").update_connection` method.

Boto3 documentation:
[NetworkManager.Client.update_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_connection)

Asynchronous method. Use `await update_connection(...)` for a synchronous call.

Arguments mapping described in
[UpdateConnectionRequestRequestTypeDef](./type_defs.md#updateconnectionrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ConnectionId`: `str` *(required)*
- `LinkId`: `str`
- `ConnectedLinkId`: `str`
- `Description`: `str`

Returns a `Coroutine` for
[UpdateConnectionResponseTypeDef](./type_defs.md#updateconnectionresponsetypedef).

<a id="update_core_network"></a>

### update_core_network

Updates the description of a core network.

Type annotations for
`session.create_client("networkmanager").update_core_network` method.

Boto3 documentation:
[NetworkManager.Client.update_core_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_core_network)

Asynchronous method. Use `await update_core_network(...)` for a synchronous
call.

Arguments mapping described in
[UpdateCoreNetworkRequestRequestTypeDef](./type_defs.md#updatecorenetworkrequestrequesttypedef).

Keyword-only arguments:

- `CoreNetworkId`: `str` *(required)*
- `Description`: `str`

Returns a `Coroutine` for
[UpdateCoreNetworkResponseTypeDef](./type_defs.md#updatecorenetworkresponsetypedef).

<a id="update_device"></a>

### update_device

Updates the details for an existing device.

Type annotations for `session.create_client("networkmanager").update_device`
method.

Boto3 documentation:
[NetworkManager.Client.update_device](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_device)

Asynchronous method. Use `await update_device(...)` for a synchronous call.

Arguments mapping described in
[UpdateDeviceRequestRequestTypeDef](./type_defs.md#updatedevicerequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `DeviceId`: `str` *(required)*
- `AWSLocation`: [AWSLocationTypeDef](./type_defs.md#awslocationtypedef)
- `Description`: `str`
- `Type`: `str`
- `Vendor`: `str`
- `Model`: `str`
- `SerialNumber`: `str`
- `Location`: [LocationTypeDef](./type_defs.md#locationtypedef)
- `SiteId`: `str`

Returns a `Coroutine` for
[UpdateDeviceResponseTypeDef](./type_defs.md#updatedeviceresponsetypedef).

<a id="update_global_network"></a>

### update_global_network

Updates an existing global network.

Type annotations for
`session.create_client("networkmanager").update_global_network` method.

Boto3 documentation:
[NetworkManager.Client.update_global_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_global_network)

Asynchronous method. Use `await update_global_network(...)` for a synchronous
call.

Arguments mapping described in
[UpdateGlobalNetworkRequestRequestTypeDef](./type_defs.md#updateglobalnetworkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `Description`: `str`

Returns a `Coroutine` for
[UpdateGlobalNetworkResponseTypeDef](./type_defs.md#updateglobalnetworkresponsetypedef).

<a id="update_link"></a>

### update_link

Updates the details for an existing link.

Type annotations for `session.create_client("networkmanager").update_link`
method.

Boto3 documentation:
[NetworkManager.Client.update_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_link)

Asynchronous method. Use `await update_link(...)` for a synchronous call.

Arguments mapping described in
[UpdateLinkRequestRequestTypeDef](./type_defs.md#updatelinkrequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `LinkId`: `str` *(required)*
- `Description`: `str`
- `Type`: `str`
- `Bandwidth`: [BandwidthTypeDef](./type_defs.md#bandwidthtypedef)
- `Provider`: `str`

Returns a `Coroutine` for
[UpdateLinkResponseTypeDef](./type_defs.md#updatelinkresponsetypedef).

<a id="update_network_resource_metadata"></a>

### update_network_resource_metadata

Updates the resource metadata for the specified global network.

Type annotations for
`session.create_client("networkmanager").update_network_resource_metadata`
method.

Boto3 documentation:
[NetworkManager.Client.update_network_resource_metadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_network_resource_metadata)

Asynchronous method. Use `await update_network_resource_metadata(...)` for a
synchronous call.

Arguments mapping described in
[UpdateNetworkResourceMetadataRequestRequestTypeDef](./type_defs.md#updatenetworkresourcemetadatarequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `ResourceArn`: `str` *(required)*
- `Metadata`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for
[UpdateNetworkResourceMetadataResponseTypeDef](./type_defs.md#updatenetworkresourcemetadataresponsetypedef).

<a id="update_site"></a>

### update_site

Updates the information for an existing site.

Type annotations for `session.create_client("networkmanager").update_site`
method.

Boto3 documentation:
[NetworkManager.Client.update_site](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_site)

Asynchronous method. Use `await update_site(...)` for a synchronous call.

Arguments mapping described in
[UpdateSiteRequestRequestTypeDef](./type_defs.md#updatesiterequestrequesttypedef).

Keyword-only arguments:

- `GlobalNetworkId`: `str` *(required)*
- `SiteId`: `str` *(required)*
- `Description`: `str`
- `Location`: [LocationTypeDef](./type_defs.md#locationtypedef)

Returns a `Coroutine` for
[UpdateSiteResponseTypeDef](./type_defs.md#updatesiteresponsetypedef).

<a id="update_vpc_attachment"></a>

### update_vpc_attachment

Updates a VPC attachment.

Type annotations for
`session.create_client("networkmanager").update_vpc_attachment` method.

Boto3 documentation:
[NetworkManager.Client.update_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.update_vpc_attachment)

Asynchronous method. Use `await update_vpc_attachment(...)` for a synchronous
call.

Arguments mapping described in
[UpdateVpcAttachmentRequestRequestTypeDef](./type_defs.md#updatevpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*
- `AddSubnetArns`: `Sequence`\[`str`\]
- `RemoveSubnetArns`: `Sequence`\[`str`\]
- `Options`: [VpcOptionsTypeDef](./type_defs.md#vpcoptionstypedef)

Returns a `Coroutine` for
[UpdateVpcAttachmentResponseTypeDef](./type_defs.md#updatevpcattachmentresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("networkmanager").__aenter__`
method.

Boto3 documentation:
[NetworkManager.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [NetworkManagerClient](#networkmanagerclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("networkmanager").__aexit__`
method.

Boto3 documentation:
[NetworkManager.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("networkmanager").get_paginator`
method with overloads.

- `client.get_paginator("describe_global_networks")` ->
  [DescribeGlobalNetworksPaginator](./paginators.md#describeglobalnetworkspaginator)
- `client.get_paginator("get_connect_peer_associations")` ->
  [GetConnectPeerAssociationsPaginator](./paginators.md#getconnectpeerassociationspaginator)
- `client.get_paginator("get_connections")` ->
  [GetConnectionsPaginator](./paginators.md#getconnectionspaginator)
- `client.get_paginator("get_core_network_change_set")` ->
  [GetCoreNetworkChangeSetPaginator](./paginators.md#getcorenetworkchangesetpaginator)
- `client.get_paginator("get_customer_gateway_associations")` ->
  [GetCustomerGatewayAssociationsPaginator](./paginators.md#getcustomergatewayassociationspaginator)
- `client.get_paginator("get_devices")` ->
  [GetDevicesPaginator](./paginators.md#getdevicespaginator)
- `client.get_paginator("get_link_associations")` ->
  [GetLinkAssociationsPaginator](./paginators.md#getlinkassociationspaginator)
- `client.get_paginator("get_links")` ->
  [GetLinksPaginator](./paginators.md#getlinkspaginator)
- `client.get_paginator("get_network_resource_counts")` ->
  [GetNetworkResourceCountsPaginator](./paginators.md#getnetworkresourcecountspaginator)
- `client.get_paginator("get_network_resource_relationships")` ->
  [GetNetworkResourceRelationshipsPaginator](./paginators.md#getnetworkresourcerelationshipspaginator)
- `client.get_paginator("get_network_resources")` ->
  [GetNetworkResourcesPaginator](./paginators.md#getnetworkresourcespaginator)
- `client.get_paginator("get_network_telemetry")` ->
  [GetNetworkTelemetryPaginator](./paginators.md#getnetworktelemetrypaginator)
- `client.get_paginator("get_sites")` ->
  [GetSitesPaginator](./paginators.md#getsitespaginator)
- `client.get_paginator("get_transit_gateway_connect_peer_associations")` ->
  [GetTransitGatewayConnectPeerAssociationsPaginator](./paginators.md#gettransitgatewayconnectpeerassociationspaginator)
- `client.get_paginator("get_transit_gateway_registrations")` ->
  [GetTransitGatewayRegistrationsPaginator](./paginators.md#gettransitgatewayregistrationspaginator)
- `client.get_paginator("list_attachments")` ->
  [ListAttachmentsPaginator](./paginators.md#listattachmentspaginator)
- `client.get_paginator("list_connect_peers")` ->
  [ListConnectPeersPaginator](./paginators.md#listconnectpeerspaginator)
- `client.get_paginator("list_core_network_policy_versions")` ->
  [ListCoreNetworkPolicyVersionsPaginator](./paginators.md#listcorenetworkpolicyversionspaginator)
- `client.get_paginator("list_core_networks")` ->
  [ListCoreNetworksPaginator](./paginators.md#listcorenetworkspaginator)
