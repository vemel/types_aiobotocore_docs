<a id="ec2serviceresource-for-aiobotocore-ec2-module"></a>

# EC2ServiceResource for aiobotocore EC2 module

> [Index](../README.md) > [EC2](./README.md) > EC2ServiceResource

Auto-generated documentation for
[EC2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2)
type annotations stubs module
[types-aiobotocore-ec2](https://pypi.org/project/types-aiobotocore-ec2/).

- [EC2ServiceResource for aiobotocore EC2 module](#ec2serviceresource-for-aiobotocore-ec2-module)
  - [EC2ServiceResource](#ec2serviceresource)
  - [Attributes](#attributes)
  - [Collections](#collections)
    - [ServiceResourceClassicAddressesCollection](#serviceresourceclassicaddressescollection)
    - [ServiceResourceDhcpOptionsSetsCollection](#serviceresourcedhcpoptionssetscollection)
    - [ServiceResourceImagesCollection](#serviceresourceimagescollection)
    - [ServiceResourceInstancesCollection](#serviceresourceinstancescollection)
    - [ServiceResourceInternetGatewaysCollection](#serviceresourceinternetgatewayscollection)
    - [ServiceResourceKeyPairsCollection](#serviceresourcekeypairscollection)
    - [ServiceResourceNetworkAclsCollection](#serviceresourcenetworkaclscollection)
    - [ServiceResourceNetworkInterfacesCollection](#serviceresourcenetworkinterfacescollection)
    - [ServiceResourcePlacementGroupsCollection](#serviceresourceplacementgroupscollection)
    - [ServiceResourceRouteTablesCollection](#serviceresourceroutetablescollection)
    - [ServiceResourceSecurityGroupsCollection](#serviceresourcesecuritygroupscollection)
    - [ServiceResourceSnapshotsCollection](#serviceresourcesnapshotscollection)
    - [ServiceResourceSubnetsCollection](#serviceresourcesubnetscollection)
    - [ServiceResourceVolumesCollection](#serviceresourcevolumescollection)
    - [ServiceResourceVpcAddressesCollection](#serviceresourcevpcaddressescollection)
    - [ServiceResourceVpcPeeringConnectionsCollection](#serviceresourcevpcpeeringconnectionscollection)
    - [ServiceResourceVpcsCollection](#serviceresourcevpcscollection)
  - [Methods](#methods)
    - [EC2ServiceResource.ClassicAddress method](#ec2serviceresourceclassicaddress-method)
    - [EC2ServiceResource.DhcpOptions method](#ec2serviceresourcedhcpoptions-method)
    - [EC2ServiceResource.Image method](#ec2serviceresourceimage-method)
    - [EC2ServiceResource.Instance method](#ec2serviceresourceinstance-method)
    - [EC2ServiceResource.InternetGateway method](#ec2serviceresourceinternetgateway-method)
    - [EC2ServiceResource.KeyPair method](#ec2serviceresourcekeypair-method)
    - [EC2ServiceResource.NetworkAcl method](#ec2serviceresourcenetworkacl-method)
    - [EC2ServiceResource.NetworkInterface method](#ec2serviceresourcenetworkinterface-method)
    - [EC2ServiceResource.NetworkInterfaceAssociation method](#ec2serviceresourcenetworkinterfaceassociation-method)
    - [EC2ServiceResource.PlacementGroup method](#ec2serviceresourceplacementgroup-method)
    - [EC2ServiceResource.Route method](#ec2serviceresourceroute-method)
    - [EC2ServiceResource.RouteTable method](#ec2serviceresourceroutetable-method)
    - [EC2ServiceResource.RouteTableAssociation method](#ec2serviceresourceroutetableassociation-method)
    - [EC2ServiceResource.SecurityGroup method](#ec2serviceresourcesecuritygroup-method)
    - [EC2ServiceResource.Snapshot method](#ec2serviceresourcesnapshot-method)
    - [EC2ServiceResource.Subnet method](#ec2serviceresourcesubnet-method)
    - [EC2ServiceResource.Tag method](#ec2serviceresourcetag-method)
    - [EC2ServiceResource.Volume method](#ec2serviceresourcevolume-method)
    - [EC2ServiceResource.Vpc method](#ec2serviceresourcevpc-method)
    - [EC2ServiceResource.VpcAddress method](#ec2serviceresourcevpcaddress-method)
    - [EC2ServiceResource.VpcPeeringConnection method](#ec2serviceresourcevpcpeeringconnection-method)
    - [EC2ServiceResource.create_dhcp_options method](#ec2serviceresourcecreate_dhcp_options-method)
    - [EC2ServiceResource.create_instances method](#ec2serviceresourcecreate_instances-method)
    - [EC2ServiceResource.create_internet_gateway method](#ec2serviceresourcecreate_internet_gateway-method)
    - [EC2ServiceResource.create_key_pair method](#ec2serviceresourcecreate_key_pair-method)
    - [EC2ServiceResource.create_network_acl method](#ec2serviceresourcecreate_network_acl-method)
    - [EC2ServiceResource.create_network_interface method](#ec2serviceresourcecreate_network_interface-method)
    - [EC2ServiceResource.create_placement_group method](#ec2serviceresourcecreate_placement_group-method)
    - [EC2ServiceResource.create_route_table method](#ec2serviceresourcecreate_route_table-method)
    - [EC2ServiceResource.create_security_group method](#ec2serviceresourcecreate_security_group-method)
    - [EC2ServiceResource.create_snapshot method](#ec2serviceresourcecreate_snapshot-method)
    - [EC2ServiceResource.create_subnet method](#ec2serviceresourcecreate_subnet-method)
    - [EC2ServiceResource.create_tags method](#ec2serviceresourcecreate_tags-method)
    - [EC2ServiceResource.create_volume method](#ec2serviceresourcecreate_volume-method)
    - [EC2ServiceResource.create_vpc method](#ec2serviceresourcecreate_vpc-method)
    - [EC2ServiceResource.create_vpc_peering_connection method](#ec2serviceresourcecreate_vpc_peering_connection-method)
    - [EC2ServiceResource.disassociate_route_table method](#ec2serviceresourcedisassociate_route_table-method)
    - [EC2ServiceResource.get_available_subresources method](#ec2serviceresourceget_available_subresources-method)
    - [EC2ServiceResource.import_key_pair method](#ec2serviceresourceimport_key_pair-method)
    - [EC2ServiceResource.register_image method](#ec2serviceresourceregister_image-method)
  - [ClassicAddress](#classicaddress)
    - [ClassicAddress attributes](#classicaddress-attributes)
    - [ClassicAddress methods](#classicaddress-methods)
  - [DhcpOptions](#dhcpoptions)
    - [DhcpOptions attributes](#dhcpoptions-attributes)
    - [DhcpOptions methods](#dhcpoptions-methods)
  - [Image](#image)
    - [Image attributes](#image-attributes)
    - [Image methods](#image-methods)
  - [Instance](#instance)
    - [Instance attributes](#instance-attributes)
    - [Instance collections](#instance-collections)
    - [Instance methods](#instance-methods)
  - [InternetGateway](#internetgateway)
    - [InternetGateway attributes](#internetgateway-attributes)
    - [InternetGateway methods](#internetgateway-methods)
  - [KeyPair](#keypair)
    - [KeyPair attributes](#keypair-attributes)
    - [KeyPair methods](#keypair-methods)
  - [KeyPairInfo](#keypairinfo)
    - [KeyPairInfo attributes](#keypairinfo-attributes)
    - [KeyPairInfo methods](#keypairinfo-methods)
  - [NetworkAcl](#networkacl)
    - [NetworkAcl attributes](#networkacl-attributes)
    - [NetworkAcl methods](#networkacl-methods)
  - [NetworkInterface](#networkinterface)
    - [NetworkInterface attributes](#networkinterface-attributes)
    - [NetworkInterface methods](#networkinterface-methods)
  - [NetworkInterfaceAssociation](#networkinterfaceassociation)
    - [NetworkInterfaceAssociation attributes](#networkinterfaceassociation-attributes)
    - [NetworkInterfaceAssociation methods](#networkinterfaceassociation-methods)
  - [PlacementGroup](#placementgroup)
    - [PlacementGroup attributes](#placementgroup-attributes)
    - [PlacementGroup collections](#placementgroup-collections)
    - [PlacementGroup methods](#placementgroup-methods)
  - [Route](#route)
    - [Route attributes](#route-attributes)
    - [Route methods](#route-methods)
  - [RouteTable](#routetable)
    - [RouteTable attributes](#routetable-attributes)
    - [RouteTable methods](#routetable-methods)
  - [RouteTableAssociation](#routetableassociation)
    - [RouteTableAssociation attributes](#routetableassociation-attributes)
    - [RouteTableAssociation methods](#routetableassociation-methods)
  - [SecurityGroup](#securitygroup)
    - [SecurityGroup attributes](#securitygroup-attributes)
    - [SecurityGroup methods](#securitygroup-methods)
  - [Snapshot](#snapshot)
    - [Snapshot attributes](#snapshot-attributes)
    - [Snapshot methods](#snapshot-methods)
  - [Subnet](#subnet)
    - [Subnet attributes](#subnet-attributes)
    - [Subnet collections](#subnet-collections)
    - [Subnet methods](#subnet-methods)
  - [Tag](#tag)
    - [Tag attributes](#tag-attributes)
    - [Tag methods](#tag-methods)
  - [Volume](#volume)
    - [Volume attributes](#volume-attributes)
    - [Volume collections](#volume-collections)
    - [Volume methods](#volume-methods)
  - [Vpc](#vpc)
    - [Vpc attributes](#vpc-attributes)
    - [Vpc collections](#vpc-collections)
    - [Vpc methods](#vpc-methods)
  - [VpcPeeringConnection](#vpcpeeringconnection)
    - [VpcPeeringConnection attributes](#vpcpeeringconnection-attributes)
    - [VpcPeeringConnection methods](#vpcpeeringconnection-methods)
  - [VpcAddress](#vpcaddress)
    - [VpcAddress attributes](#vpcaddress-attributes)
    - [VpcAddress methods](#vpcaddress-methods)

<a id="ec2serviceresource"></a>

## EC2ServiceResource

Type annotations for `aiobotocore.resource("ec2")`, included resources and
collections.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import EC2ServiceResource

def get_ec2_resource() -> EC2ServiceResource:
    return boto3.resource("ec2")
```

Boto3 documentation:
[EC2.ServiceResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource)

<a id="attributes"></a>

## Attributes

- `meta`: [EC2ResourceMeta](#ec2resourcemeta)

- `classic_addresses`:
  [ServiceResourceClassicAddressesCollection](#serviceresourceclassicaddressescollection)

- `dhcp_options_sets`:
  [ServiceResourceDhcpOptionsSetsCollection](#serviceresourcedhcpoptionssetscollection)

- `images`: [ServiceResourceImagesCollection](#serviceresourceimagescollection)

- `instances`:
  [ServiceResourceInstancesCollection](#serviceresourceinstancescollection)

- `internet_gateways`:
  [ServiceResourceInternetGatewaysCollection](#serviceresourceinternetgatewayscollection)

- `key_pairs`:
  [ServiceResourceKeyPairsCollection](#serviceresourcekeypairscollection)

- `network_acls`:
  [ServiceResourceNetworkAclsCollection](#serviceresourcenetworkaclscollection)

- `network_interfaces`:
  [ServiceResourceNetworkInterfacesCollection](#serviceresourcenetworkinterfacescollection)

- `placement_groups`:
  [ServiceResourcePlacementGroupsCollection](#serviceresourceplacementgroupscollection)

- `route_tables`:
  [ServiceResourceRouteTablesCollection](#serviceresourceroutetablescollection)

- `security_groups`:
  [ServiceResourceSecurityGroupsCollection](#serviceresourcesecuritygroupscollection)

- `snapshots`:
  [ServiceResourceSnapshotsCollection](#serviceresourcesnapshotscollection)

- `subnets`:
  [ServiceResourceSubnetsCollection](#serviceresourcesubnetscollection)

- `volumes`:
  [ServiceResourceVolumesCollection](#serviceresourcevolumescollection)

- `vpc_addresses`:
  [ServiceResourceVpcAddressesCollection](#serviceresourcevpcaddressescollection)

- `vpc_peering_connections`:
  [ServiceResourceVpcPeeringConnectionsCollection](#serviceresourcevpcpeeringconnectionscollection)

- `vpcs`: [ServiceResourceVpcsCollection](#serviceresourcevpcscollection)

<a id="collections"></a>

## Collections

<a id="serviceresourceclassicaddressescollection"></a>

### ServiceResourceClassicAddressesCollection

Type annotations for `boto3.resource("ec2").classic_addresses` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceClassicAddressesCollection,

def get_collection() -> ServiceResourceClassicAddressesCollection:
    return boto3.resource("ec2").classic_addresses
```

Provides access to [ClassicAddress](#classicaddress) resource.

Boto3 documentation:
[EC2.ServiceResource.classic_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.classic_addresses)

<a id="serviceresourcedhcpoptionssetscollection"></a>

### ServiceResourceDhcpOptionsSetsCollection

Type annotations for `boto3.resource("ec2").dhcp_options_sets` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceDhcpOptionsSetsCollection,

def get_collection() -> ServiceResourceDhcpOptionsSetsCollection:
    return boto3.resource("ec2").dhcp_options_sets
```

Provides access to [DhcpOptions](#dhcpoptions) resource.

Boto3 documentation:
[EC2.ServiceResource.dhcp_options_sets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.dhcp_options_sets)

<a id="serviceresourceimagescollection"></a>

### ServiceResourceImagesCollection

Type annotations for `boto3.resource("ec2").images` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceImagesCollection,

def get_collection() -> ServiceResourceImagesCollection:
    return boto3.resource("ec2").images
```

Provides access to [Image](#image) resource.

Boto3 documentation:
[EC2.ServiceResource.images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.images)

<a id="serviceresourceinstancescollection"></a>

### ServiceResourceInstancesCollection

Type annotations for `boto3.resource("ec2").instances` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceInstancesCollection,

def get_collection() -> ServiceResourceInstancesCollection:
    return boto3.resource("ec2").instances
```

Provides access to [Instance](#instance) resource.

Boto3 documentation:
[EC2.ServiceResource.instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.instances)

<a id="serviceresourceinternetgatewayscollection"></a>

### ServiceResourceInternetGatewaysCollection

Type annotations for `boto3.resource("ec2").internet_gateways` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceInternetGatewaysCollection,

def get_collection() -> ServiceResourceInternetGatewaysCollection:
    return boto3.resource("ec2").internet_gateways
```

Provides access to [InternetGateway](#internetgateway) resource.

Boto3 documentation:
[EC2.ServiceResource.internet_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.internet_gateways)

<a id="serviceresourcekeypairscollection"></a>

### ServiceResourceKeyPairsCollection

Type annotations for `boto3.resource("ec2").key_pairs` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceKeyPairsCollection,

def get_collection() -> ServiceResourceKeyPairsCollection:
    return boto3.resource("ec2").key_pairs
```

Provides access to [KeyPairInfo](#keypairinfo) resource.

Boto3 documentation:
[EC2.ServiceResource.key_pairs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.key_pairs)

<a id="serviceresourcenetworkaclscollection"></a>

### ServiceResourceNetworkAclsCollection

Type annotations for `boto3.resource("ec2").network_acls` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceNetworkAclsCollection,

def get_collection() -> ServiceResourceNetworkAclsCollection:
    return boto3.resource("ec2").network_acls
```

Provides access to [NetworkAcl](#networkacl) resource.

Boto3 documentation:
[EC2.ServiceResource.network_acls](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.network_acls)

<a id="serviceresourcenetworkinterfacescollection"></a>

### ServiceResourceNetworkInterfacesCollection

Type annotations for `boto3.resource("ec2").network_interfaces` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceNetworkInterfacesCollection,

def get_collection() -> ServiceResourceNetworkInterfacesCollection:
    return boto3.resource("ec2").network_interfaces
```

Provides access to [NetworkInterface](#networkinterface) resource.

Boto3 documentation:
[EC2.ServiceResource.network_interfaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.network_interfaces)

<a id="serviceresourceplacementgroupscollection"></a>

### ServiceResourcePlacementGroupsCollection

Type annotations for `boto3.resource("ec2").placement_groups` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourcePlacementGroupsCollection,

def get_collection() -> ServiceResourcePlacementGroupsCollection:
    return boto3.resource("ec2").placement_groups
```

Provides access to [PlacementGroup](#placementgroup) resource.

Boto3 documentation:
[EC2.ServiceResource.placement_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.placement_groups)

<a id="serviceresourceroutetablescollection"></a>

### ServiceResourceRouteTablesCollection

Type annotations for `boto3.resource("ec2").route_tables` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceRouteTablesCollection,

def get_collection() -> ServiceResourceRouteTablesCollection:
    return boto3.resource("ec2").route_tables
```

Provides access to [RouteTable](#routetable) resource.

Boto3 documentation:
[EC2.ServiceResource.route_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.route_tables)

<a id="serviceresourcesecuritygroupscollection"></a>

### ServiceResourceSecurityGroupsCollection

Type annotations for `boto3.resource("ec2").security_groups` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceSecurityGroupsCollection,

def get_collection() -> ServiceResourceSecurityGroupsCollection:
    return boto3.resource("ec2").security_groups
```

Provides access to [SecurityGroup](#securitygroup) resource.

Boto3 documentation:
[EC2.ServiceResource.security_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.security_groups)

<a id="serviceresourcesnapshotscollection"></a>

### ServiceResourceSnapshotsCollection

Type annotations for `boto3.resource("ec2").snapshots` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceSnapshotsCollection,

def get_collection() -> ServiceResourceSnapshotsCollection:
    return boto3.resource("ec2").snapshots
```

Provides access to [Snapshot](#snapshot) resource.

Boto3 documentation:
[EC2.ServiceResource.snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.snapshots)

<a id="serviceresourcesubnetscollection"></a>

### ServiceResourceSubnetsCollection

Type annotations for `boto3.resource("ec2").subnets` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceSubnetsCollection,

def get_collection() -> ServiceResourceSubnetsCollection:
    return boto3.resource("ec2").subnets
```

Provides access to [Subnet](#subnet) resource.

Boto3 documentation:
[EC2.ServiceResource.subnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.subnets)

<a id="serviceresourcevolumescollection"></a>

### ServiceResourceVolumesCollection

Type annotations for `boto3.resource("ec2").volumes` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceVolumesCollection,

def get_collection() -> ServiceResourceVolumesCollection:
    return boto3.resource("ec2").volumes
```

Provides access to [Volume](#volume) resource.

Boto3 documentation:
[EC2.ServiceResource.volumes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.volumes)

<a id="serviceresourcevpcaddressescollection"></a>

### ServiceResourceVpcAddressesCollection

Type annotations for `boto3.resource("ec2").vpc_addresses` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceVpcAddressesCollection,

def get_collection() -> ServiceResourceVpcAddressesCollection:
    return boto3.resource("ec2").vpc_addresses
```

Provides access to [VpcAddress](#vpcaddress) resource.

Boto3 documentation:
[EC2.ServiceResource.vpc_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.vpc_addresses)

<a id="serviceresourcevpcpeeringconnectionscollection"></a>

### ServiceResourceVpcPeeringConnectionsCollection

Type annotations for `boto3.resource("ec2").vpc_peering_connections`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceVpcPeeringConnectionsCollection,

def get_collection() -> ServiceResourceVpcPeeringConnectionsCollection:
    return boto3.resource("ec2").vpc_peering_connections
```

Provides access to [VpcPeeringConnection](#vpcpeeringconnection) resource.

Boto3 documentation:
[EC2.ServiceResource.vpc_peering_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.vpc_peering_connections)

<a id="serviceresourcevpcscollection"></a>

### ServiceResourceVpcsCollection

Type annotations for `boto3.resource("ec2").vpcs` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ServiceResourceVpcsCollection,

def get_collection() -> ServiceResourceVpcsCollection:
    return boto3.resource("ec2").vpcs
```

Provides access to [Vpc](#vpc) resource.

Boto3 documentation:
[EC2.ServiceResource.vpcs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.vpcs)

<a id="methods"></a>

## Methods

<a id="ec2serviceresourceclassicaddress-method"></a>

### EC2ServiceResource.ClassicAddress method

Creates a ClassicAddress resource.

Type annotations for `aiobotocore.resource("ec2").ClassicAddress` method.

Boto3 documentation:
[EC2.ServiceResource.ClassicAddress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.ClassicAddress)

Asynchronous method. Use `await ClassicAddress(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceClassicAddressRequestTypeDef](./type_defs.md#serviceresourceclassicaddressrequesttypedef).

Arguments:

- `public_ip`: `str` *(required)*

Returns a `Coroutine` for [ClassicAddress](#classicaddress).

<a id="ec2serviceresourcedhcpoptions-method"></a>

### EC2ServiceResource.DhcpOptions method

Creates a DhcpOptions resource.

Type annotations for `aiobotocore.resource("ec2").DhcpOptions` method.

Boto3 documentation:
[EC2.ServiceResource.DhcpOptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.DhcpOptions)

Asynchronous method. Use `await DhcpOptions(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceDhcpOptionsRequestTypeDef](./type_defs.md#serviceresourcedhcpoptionsrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [DhcpOptions](#dhcpoptions).

<a id="ec2serviceresourceimage-method"></a>

### EC2ServiceResource.Image method

Creates a Image resource.

Type annotations for `aiobotocore.resource("ec2").Image` method.

Boto3 documentation:
[EC2.ServiceResource.Image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Image)

Asynchronous method. Use `await Image(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceImageRequestTypeDef](./type_defs.md#serviceresourceimagerequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [Image](#image).

<a id="ec2serviceresourceinstance-method"></a>

### EC2ServiceResource.Instance method

Creates a Instance resource.

Type annotations for `aiobotocore.resource("ec2").Instance` method.

Boto3 documentation:
[EC2.ServiceResource.Instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Instance)

Asynchronous method. Use `await Instance(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceInstanceRequestTypeDef](./type_defs.md#serviceresourceinstancerequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [Instance](#instance).

<a id="ec2serviceresourceinternetgateway-method"></a>

### EC2ServiceResource.InternetGateway method

Creates a InternetGateway resource.

Type annotations for `aiobotocore.resource("ec2").InternetGateway` method.

Boto3 documentation:
[EC2.ServiceResource.InternetGateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.InternetGateway)

Asynchronous method. Use `await InternetGateway(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceInternetGatewayRequestTypeDef](./type_defs.md#serviceresourceinternetgatewayrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [InternetGateway](#internetgateway).

<a id="ec2serviceresourcekeypair-method"></a>

### EC2ServiceResource.KeyPair method

Creates a KeyPairInfo resource.

Type annotations for `aiobotocore.resource("ec2").KeyPair` method.

Boto3 documentation:
[EC2.ServiceResource.KeyPair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.KeyPair)

Asynchronous method. Use `await KeyPair(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceKeyPairRequestTypeDef](./type_defs.md#serviceresourcekeypairrequesttypedef).

Arguments:

- `name`: `str` *(required)*

Returns a `Coroutine` for [KeyPairInfo](#keypairinfo).

<a id="ec2serviceresourcenetworkacl-method"></a>

### EC2ServiceResource.NetworkAcl method

Creates a NetworkAcl resource.

Type annotations for `aiobotocore.resource("ec2").NetworkAcl` method.

Boto3 documentation:
[EC2.ServiceResource.NetworkAcl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.NetworkAcl)

Asynchronous method. Use `await NetworkAcl(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceNetworkAclRequestTypeDef](./type_defs.md#serviceresourcenetworkaclrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [NetworkAcl](#networkacl).

<a id="ec2serviceresourcenetworkinterface-method"></a>

### EC2ServiceResource.NetworkInterface method

Creates a NetworkInterface resource.

Type annotations for `aiobotocore.resource("ec2").NetworkInterface` method.

Boto3 documentation:
[EC2.ServiceResource.NetworkInterface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.NetworkInterface)

Asynchronous method. Use `await NetworkInterface(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceNetworkInterfaceRequestTypeDef](./type_defs.md#serviceresourcenetworkinterfacerequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [NetworkInterface](#networkinterface).

<a id="ec2serviceresourcenetworkinterfaceassociation-method"></a>

### EC2ServiceResource.NetworkInterfaceAssociation method

Creates a NetworkInterfaceAssociation resource.

Type annotations for `aiobotocore.resource("ec2").NetworkInterfaceAssociation`
method.

Boto3 documentation:
[EC2.ServiceResource.NetworkInterfaceAssociation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.NetworkInterfaceAssociation)

Asynchronous method. Use `await NetworkInterfaceAssociation(...)` for a
synchronous call.

Arguments mapping described in
[ServiceResourceNetworkInterfaceAssociationRequestTypeDef](./type_defs.md#serviceresourcenetworkinterfaceassociationrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[NetworkInterfaceAssociation](#networkinterfaceassociation).

<a id="ec2serviceresourceplacementgroup-method"></a>

### EC2ServiceResource.PlacementGroup method

Creates a PlacementGroup resource.

Type annotations for `aiobotocore.resource("ec2").PlacementGroup` method.

Boto3 documentation:
[EC2.ServiceResource.PlacementGroup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.PlacementGroup)

Asynchronous method. Use `await PlacementGroup(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourcePlacementGroupRequestTypeDef](./type_defs.md#serviceresourceplacementgrouprequesttypedef).

Arguments:

- `name`: `str` *(required)*

Returns a `Coroutine` for [PlacementGroup](#placementgroup).

<a id="ec2serviceresourceroute-method"></a>

### EC2ServiceResource.Route method

Creates a Route resource.

Type annotations for `aiobotocore.resource("ec2").Route` method.

Boto3 documentation:
[EC2.ServiceResource.Route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Route)

Asynchronous method. Use `await Route(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceRouteRequestTypeDef](./type_defs.md#serviceresourcerouterequesttypedef).

Arguments:

- `route_table_id`: `str` *(required)*
- `destination_cidr_block`: `str` *(required)*

Returns a `Coroutine` for [Route](#route).

<a id="ec2serviceresourceroutetable-method"></a>

### EC2ServiceResource.RouteTable method

Creates a RouteTable resource.

Type annotations for `aiobotocore.resource("ec2").RouteTable` method.

Boto3 documentation:
[EC2.ServiceResource.RouteTable](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.RouteTable)

Asynchronous method. Use `await RouteTable(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceRouteTableRequestTypeDef](./type_defs.md#serviceresourceroutetablerequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [RouteTable](#routetable).

<a id="ec2serviceresourceroutetableassociation-method"></a>

### EC2ServiceResource.RouteTableAssociation method

Creates a RouteTableAssociation resource.

Type annotations for `aiobotocore.resource("ec2").RouteTableAssociation`
method.

Boto3 documentation:
[EC2.ServiceResource.RouteTableAssociation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.RouteTableAssociation)

Asynchronous method. Use `await RouteTableAssociation(...)` for a synchronous
call.

Arguments mapping described in
[ServiceResourceRouteTableAssociationRequestTypeDef](./type_defs.md#serviceresourceroutetableassociationrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [RouteTableAssociation](#routetableassociation).

<a id="ec2serviceresourcesecuritygroup-method"></a>

### EC2ServiceResource.SecurityGroup method

Creates a SecurityGroup resource.

Type annotations for `aiobotocore.resource("ec2").SecurityGroup` method.

Boto3 documentation:
[EC2.ServiceResource.SecurityGroup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.SecurityGroup)

Asynchronous method. Use `await SecurityGroup(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceSecurityGroupRequestTypeDef](./type_defs.md#serviceresourcesecuritygrouprequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [SecurityGroup](#securitygroup).

<a id="ec2serviceresourcesnapshot-method"></a>

### EC2ServiceResource.Snapshot method

Creates a Snapshot resource.

Type annotations for `aiobotocore.resource("ec2").Snapshot` method.

Boto3 documentation:
[EC2.ServiceResource.Snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Snapshot)

Asynchronous method. Use `await Snapshot(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceSnapshotRequestTypeDef](./type_defs.md#serviceresourcesnapshotrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [Snapshot](#snapshot).

<a id="ec2serviceresourcesubnet-method"></a>

### EC2ServiceResource.Subnet method

Creates a Subnet resource.

Type annotations for `aiobotocore.resource("ec2").Subnet` method.

Boto3 documentation:
[EC2.ServiceResource.Subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Subnet)

Asynchronous method. Use `await Subnet(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceSubnetRequestTypeDef](./type_defs.md#serviceresourcesubnetrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [Subnet](#subnet).

<a id="ec2serviceresourcetag-method"></a>

### EC2ServiceResource.Tag method

Creates a Tag resource.

Type annotations for `aiobotocore.resource("ec2").Tag` method.

Boto3 documentation:
[EC2.ServiceResource.Tag](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Tag)

Asynchronous method. Use `await Tag(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceTagRequestTypeDef](./type_defs.md#serviceresourcetagrequesttypedef).

Arguments:

- `resource_id`: `str` *(required)*
- `key`: `str` *(required)*
- `value`: `str` *(required)*

Returns a `Coroutine` for [Tag](#tag).

<a id="ec2serviceresourcevolume-method"></a>

### EC2ServiceResource.Volume method

Creates a Volume resource.

Type annotations for `aiobotocore.resource("ec2").Volume` method.

Boto3 documentation:
[EC2.ServiceResource.Volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Volume)

Asynchronous method. Use `await Volume(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceVolumeRequestTypeDef](./type_defs.md#serviceresourcevolumerequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [Volume](#volume).

<a id="ec2serviceresourcevpc-method"></a>

### EC2ServiceResource.Vpc method

Creates a Vpc resource.

Type annotations for `aiobotocore.resource("ec2").Vpc` method.

Boto3 documentation:
[EC2.ServiceResource.Vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Vpc)

Asynchronous method. Use `await Vpc(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceVpcRequestTypeDef](./type_defs.md#serviceresourcevpcrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [Vpc](#vpc).

<a id="ec2serviceresourcevpcaddress-method"></a>

### EC2ServiceResource.VpcAddress method

Creates a VpcAddress resource.

Type annotations for `aiobotocore.resource("ec2").VpcAddress` method.

Boto3 documentation:
[EC2.ServiceResource.VpcAddress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.VpcAddress)

Asynchronous method. Use `await VpcAddress(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceVpcAddressRequestTypeDef](./type_defs.md#serviceresourcevpcaddressrequesttypedef).

Arguments:

- `allocation_id`: `str` *(required)*

Returns a `Coroutine` for [VpcAddress](#vpcaddress).

<a id="ec2serviceresourcevpcpeeringconnection-method"></a>

### EC2ServiceResource.VpcPeeringConnection method

Creates a VpcPeeringConnection resource.

Type annotations for `aiobotocore.resource("ec2").VpcPeeringConnection` method.

Boto3 documentation:
[EC2.ServiceResource.VpcPeeringConnection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.VpcPeeringConnection)

Asynchronous method. Use `await VpcPeeringConnection(...)` for a synchronous
call.

Arguments mapping described in
[ServiceResourceVpcPeeringConnectionRequestTypeDef](./type_defs.md#serviceresourcevpcpeeringconnectionrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [VpcPeeringConnection](#vpcpeeringconnection).

<a id="ec2serviceresourcecreate\_dhcp\_options-method"></a>

### EC2ServiceResource.create_dhcp_options method

Creates a set of DHCP options for your VPC.

Type annotations for `aiobotocore.resource("ec2").create_dhcp_options` method.

Boto3 documentation:
[EC2.ServiceResource.create_dhcp_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_dhcp_options)

Asynchronous method. Use `await create_dhcp_options(...)` for a synchronous
call.

Arguments mapping described in
[CreateDhcpOptionsRequestServiceResourceCreateDhcpOptionsTypeDef](./type_defs.md#createdhcpoptionsrequestserviceresourcecreatedhcpoptionstypedef).

Keyword-only arguments:

- `DhcpConfigurations`:
  `Sequence`\[[NewDhcpConfigurationTypeDef](./type_defs.md#newdhcpconfigurationtypedef)\]
  *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for [DhcpOptions](#dhcpoptions).

<a id="ec2serviceresourcecreate\_instances-method"></a>

### EC2ServiceResource.create_instances method

Launches the specified number of instances using an AMI for which you have
permissions.

Type annotations for `aiobotocore.resource("ec2").create_instances` method.

Boto3 documentation:
[EC2.ServiceResource.create_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_instances)

Asynchronous method. Use `await create_instances(...)` for a synchronous call.

Arguments mapping described in
[RunInstancesRequestServiceResourceCreateInstancesTypeDef](./type_defs.md#runinstancesrequestserviceresourcecreateinstancestypedef).

Keyword-only arguments:

- `MaxCount`: `int` *(required)*
- `MinCount`: `int` *(required)*
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `ImageId`: `str`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `Ipv6AddressCount`: `int`
- `Ipv6Addresses`:
  `Sequence`\[[InstanceIpv6AddressTypeDef](./type_defs.md#instanceipv6addresstypedef)\]
- `KernelId`: `str`
- `KeyName`: `str`
- `Monitoring`:
  [RunInstancesMonitoringEnabledTypeDef](./type_defs.md#runinstancesmonitoringenabledtypedef)
- `Placement`: [PlacementTypeDef](./type_defs.md#placementtypedef)
- `RamdiskId`: `str`
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `SecurityGroups`: `Sequence`\[`str`\]
- `SubnetId`: `str`
- `UserData`: `str`
- `AdditionalInfo`: `str`
- `ClientToken`: `str`
- `DisableApiTermination`: `bool`
- `DryRun`: `bool`
- `EbsOptimized`: `bool`
- `IamInstanceProfile`:
  [IamInstanceProfileSpecificationTypeDef](./type_defs.md#iaminstanceprofilespecificationtypedef)
- `InstanceInitiatedShutdownBehavior`:
  [ShutdownBehaviorType](./literals.md#shutdownbehaviortype)
- `NetworkInterfaces`:
  `Sequence`\[[InstanceNetworkInterfaceSpecificationTypeDef](./type_defs.md#instancenetworkinterfacespecificationtypedef)\]
- `PrivateIpAddress`: `str`
- `ElasticGpuSpecification`:
  `Sequence`\[[ElasticGpuSpecificationTypeDef](./type_defs.md#elasticgpuspecificationtypedef)\]
- `ElasticInferenceAccelerators`:
  `Sequence`\[[ElasticInferenceAcceleratorTypeDef](./type_defs.md#elasticinferenceacceleratortypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `LaunchTemplate`:
  [LaunchTemplateSpecificationTypeDef](./type_defs.md#launchtemplatespecificationtypedef)
- `InstanceMarketOptions`:
  [InstanceMarketOptionsRequestTypeDef](./type_defs.md#instancemarketoptionsrequesttypedef)
- `CreditSpecification`:
  [CreditSpecificationRequestTypeDef](./type_defs.md#creditspecificationrequesttypedef)
- `CpuOptions`:
  [CpuOptionsRequestTypeDef](./type_defs.md#cpuoptionsrequesttypedef)
- `CapacityReservationSpecification`:
  [CapacityReservationSpecificationTypeDef](./type_defs.md#capacityreservationspecificationtypedef)
- `HibernationOptions`:
  [HibernationOptionsRequestTypeDef](./type_defs.md#hibernationoptionsrequesttypedef)
- `LicenseSpecifications`:
  `Sequence`\[[LicenseConfigurationRequestTypeDef](./type_defs.md#licenseconfigurationrequesttypedef)\]
- `MetadataOptions`:
  [InstanceMetadataOptionsRequestTypeDef](./type_defs.md#instancemetadataoptionsrequesttypedef)
- `EnclaveOptions`:
  [EnclaveOptionsRequestTypeDef](./type_defs.md#enclaveoptionsrequesttypedef)
- `PrivateDnsNameOptions`:
  [PrivateDnsNameOptionsRequestTypeDef](./type_defs.md#privatednsnameoptionsrequesttypedef)

Returns a `Coroutine` for `List`\[[Instance](#instance)\].

<a id="ec2serviceresourcecreate\_internet\_gateway-method"></a>

### EC2ServiceResource.create_internet_gateway method

Creates an internet gateway for use with a VPC.

Type annotations for `aiobotocore.resource("ec2").create_internet_gateway`
method.

Boto3 documentation:
[EC2.ServiceResource.create_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_internet_gateway)

Asynchronous method. Use `await create_internet_gateway(...)` for a synchronous
call.

Arguments mapping described in
[CreateInternetGatewayRequestServiceResourceCreateInternetGatewayTypeDef](./type_defs.md#createinternetgatewayrequestserviceresourcecreateinternetgatewaytypedef).

Keyword-only arguments:

- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for [InternetGateway](#internetgateway).

<a id="ec2serviceresourcecreate\_key\_pair-method"></a>

### EC2ServiceResource.create_key_pair method

Creates an ED25519 or 2048-bit RSA key pair with the specified name.

Type annotations for `aiobotocore.resource("ec2").create_key_pair` method.

Boto3 documentation:
[EC2.ServiceResource.create_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_key_pair)

Asynchronous method. Use `await create_key_pair(...)` for a synchronous call.

Arguments mapping described in
[CreateKeyPairRequestServiceResourceCreateKeyPairTypeDef](./type_defs.md#createkeypairrequestserviceresourcecreatekeypairtypedef).

Keyword-only arguments:

- `KeyName`: `str` *(required)*
- `DryRun`: `bool`
- `KeyType`: [KeyTypeType](./literals.md#keytypetype)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [KeyPair](#keypair).

<a id="ec2serviceresourcecreate\_network\_acl-method"></a>

### EC2ServiceResource.create_network_acl method

Creates a network ACL in a VPC.

Type annotations for `aiobotocore.resource("ec2").create_network_acl` method.

Boto3 documentation:
[EC2.ServiceResource.create_network_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_network_acl)

Asynchronous method. Use `await create_network_acl(...)` for a synchronous
call.

Arguments mapping described in
[CreateNetworkAclRequestServiceResourceCreateNetworkAclTypeDef](./type_defs.md#createnetworkaclrequestserviceresourcecreatenetworkacltypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [NetworkAcl](#networkacl).

<a id="ec2serviceresourcecreate\_network\_interface-method"></a>

### EC2ServiceResource.create_network_interface method

Creates a network interface in the specified subnet.

Type annotations for `aiobotocore.resource("ec2").create_network_interface`
method.

Boto3 documentation:
[EC2.ServiceResource.create_network_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_network_interface)

Asynchronous method. Use `await create_network_interface(...)` for a
synchronous call.

Arguments mapping described in
[CreateNetworkInterfaceRequestServiceResourceCreateNetworkInterfaceTypeDef](./type_defs.md#createnetworkinterfacerequestserviceresourcecreatenetworkinterfacetypedef).

Keyword-only arguments:

- `SubnetId`: `str` *(required)*
- `Description`: `str`
- `DryRun`: `bool`
- `Groups`: `Sequence`\[`str`\]
- `Ipv6AddressCount`: `int`
- `Ipv6Addresses`:
  `Sequence`\[[InstanceIpv6AddressTypeDef](./type_defs.md#instanceipv6addresstypedef)\]
- `PrivateIpAddress`: `str`
- `PrivateIpAddresses`:
  `Sequence`\[[PrivateIpAddressSpecificationTypeDef](./type_defs.md#privateipaddressspecificationtypedef)\]
- `SecondaryPrivateIpAddressCount`: `int`
- `Ipv4Prefixes`:
  `Sequence`\[[Ipv4PrefixSpecificationRequestTypeDef](./type_defs.md#ipv4prefixspecificationrequesttypedef)\]
- `Ipv4PrefixCount`: `int`
- `Ipv6Prefixes`:
  `Sequence`\[[Ipv6PrefixSpecificationRequestTypeDef](./type_defs.md#ipv6prefixspecificationrequesttypedef)\]
- `Ipv6PrefixCount`: `int`
- `InterfaceType`:
  [NetworkInterfaceCreationTypeType](./literals.md#networkinterfacecreationtypetype)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for [NetworkInterface](#networkinterface).

<a id="ec2serviceresourcecreate\_placement\_group-method"></a>

### EC2ServiceResource.create_placement_group method

Creates a placement group in which to launch instances.

Type annotations for `aiobotocore.resource("ec2").create_placement_group`
method.

Boto3 documentation:
[EC2.ServiceResource.create_placement_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_placement_group)

Asynchronous method. Use `await create_placement_group(...)` for a synchronous
call.

Arguments mapping described in
[CreatePlacementGroupRequestServiceResourceCreatePlacementGroupTypeDef](./type_defs.md#createplacementgrouprequestserviceresourcecreateplacementgrouptypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `GroupName`: `str`
- `Strategy`: [PlacementStrategyType](./literals.md#placementstrategytype)
- `PartitionCount`: `int`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [PlacementGroup](#placementgroup).

<a id="ec2serviceresourcecreate\_route\_table-method"></a>

### EC2ServiceResource.create_route_table method

Creates a route table for the specified VPC.

Type annotations for `aiobotocore.resource("ec2").create_route_table` method.

Boto3 documentation:
[EC2.ServiceResource.create_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_route_table)

Asynchronous method. Use `await create_route_table(...)` for a synchronous
call.

Arguments mapping described in
[CreateRouteTableRequestServiceResourceCreateRouteTableTypeDef](./type_defs.md#createroutetablerequestserviceresourcecreateroutetabletypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [RouteTable](#routetable).

<a id="ec2serviceresourcecreate\_security\_group-method"></a>

### EC2ServiceResource.create_security_group method

Creates a security group.

Type annotations for `aiobotocore.resource("ec2").create_security_group`
method.

Boto3 documentation:
[EC2.ServiceResource.create_security_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_security_group)

Asynchronous method. Use `await create_security_group(...)` for a synchronous
call.

Arguments mapping described in
[CreateSecurityGroupRequestServiceResourceCreateSecurityGroupTypeDef](./type_defs.md#createsecuritygrouprequestserviceresourcecreatesecuritygrouptypedef).

Keyword-only arguments:

- `Description`: `str` *(required)*
- `GroupName`: `str` *(required)*
- `VpcId`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for [SecurityGroup](#securitygroup).

<a id="ec2serviceresourcecreate\_snapshot-method"></a>

### EC2ServiceResource.create_snapshot method

Creates a snapshot of an EBS volume and stores it in Amazon S3.

Type annotations for `aiobotocore.resource("ec2").create_snapshot` method.

Boto3 documentation:
[EC2.ServiceResource.create_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_snapshot)

Asynchronous method. Use `await create_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CreateSnapshotRequestServiceResourceCreateSnapshotTypeDef](./type_defs.md#createsnapshotrequestserviceresourcecreatesnapshottypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `Description`: `str`
- `OutpostArn`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for [Snapshot](#snapshot).

<a id="ec2serviceresourcecreate\_subnet-method"></a>

### EC2ServiceResource.create_subnet method

Creates a subnet in a specified VPC.

Type annotations for `aiobotocore.resource("ec2").create_subnet` method.

Boto3 documentation:
[EC2.ServiceResource.create_subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_subnet)

Asynchronous method. Use `await create_subnet(...)` for a synchronous call.

Arguments mapping described in
[CreateSubnetRequestServiceResourceCreateSubnetTypeDef](./type_defs.md#createsubnetrequestserviceresourcecreatesubnettypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `AvailabilityZone`: `str`
- `AvailabilityZoneId`: `str`
- `CidrBlock`: `str`
- `Ipv6CidrBlock`: `str`
- `OutpostArn`: `str`
- `DryRun`: `bool`
- `Ipv6Native`: `bool`

Returns a `Coroutine` for [Subnet](#subnet).

<a id="ec2serviceresourcecreate\_tags-method"></a>

### EC2ServiceResource.create_tags method

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.ServiceResource.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestServiceResourceCreateTagsTypeDef](./type_defs.md#createtagsrequestserviceresourcecreatetagstypedef).

Keyword-only arguments:

- `Resources`: `Sequence`\[`str`\] *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*
- `DryRun`: `bool`

<a id="ec2serviceresourcecreate\_volume-method"></a>

### EC2ServiceResource.create_volume method

Creates an EBS volume that can be attached to an instance in the same
Availability Zone.

Type annotations for `aiobotocore.resource("ec2").create_volume` method.

Boto3 documentation:
[EC2.ServiceResource.create_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_volume)

Asynchronous method. Use `await create_volume(...)` for a synchronous call.

Arguments mapping described in
[CreateVolumeRequestServiceResourceCreateVolumeTypeDef](./type_defs.md#createvolumerequestserviceresourcecreatevolumetypedef).

Keyword-only arguments:

- `AvailabilityZone`: `str` *(required)*
- `Encrypted`: `bool`
- `Iops`: `int`
- `KmsKeyId`: `str`
- `OutpostArn`: `str`
- `Size`: `int`
- `SnapshotId`: `str`
- `VolumeType`: [VolumeTypeType](./literals.md#volumetypetype)
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `MultiAttachEnabled`: `bool`
- `Throughput`: `int`
- `ClientToken`: `str`

Returns a `Coroutine` for [Volume](#volume).

<a id="ec2serviceresourcecreate\_vpc-method"></a>

### EC2ServiceResource.create_vpc method

Creates a VPC with the specified IPv4 CIDR block.

Type annotations for `aiobotocore.resource("ec2").create_vpc` method.

Boto3 documentation:
[EC2.ServiceResource.create_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_vpc)

Asynchronous method. Use `await create_vpc(...)` for a synchronous call.

Arguments mapping described in
[CreateVpcRequestServiceResourceCreateVpcTypeDef](./type_defs.md#createvpcrequestserviceresourcecreatevpctypedef).

Keyword-only arguments:

- `CidrBlock`: `str`
- `AmazonProvidedIpv6CidrBlock`: `bool`
- `Ipv6Pool`: `str`
- `Ipv6CidrBlock`: `str`
- `Ipv4IpamPoolId`: `str`
- `Ipv4NetmaskLength`: `int`
- `Ipv6IpamPoolId`: `str`
- `Ipv6NetmaskLength`: `int`
- `DryRun`: `bool`
- `InstanceTenancy`: [TenancyType](./literals.md#tenancytype)
- `Ipv6CidrBlockNetworkBorderGroup`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [Vpc](#vpc).

<a id="ec2serviceresourcecreate\_vpc\_peering\_connection-method"></a>

### EC2ServiceResource.create_vpc_peering_connection method

Requests a VPC peering connection between two VPCs: a requester VPC that you
own and an accepter VPC with which to create the connection.

Type annotations for
`aiobotocore.resource("ec2").create_vpc_peering_connection` method.

Boto3 documentation:
[EC2.ServiceResource.create_vpc_peering_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.create_vpc_peering_connection)

Asynchronous method. Use `await create_vpc_peering_connection(...)` for a
synchronous call.

Arguments mapping described in
[CreateVpcPeeringConnectionRequestServiceResourceCreateVpcPeeringConnectionTypeDef](./type_defs.md#createvpcpeeringconnectionrequestserviceresourcecreatevpcpeeringconnectiontypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `PeerOwnerId`: `str`
- `PeerVpcId`: `str`
- `VpcId`: `str`
- `PeerRegion`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [VpcPeeringConnection](#vpcpeeringconnection).

<a id="ec2serviceresourcedisassociate\_route\_table-method"></a>

### EC2ServiceResource.disassociate_route_table method

Disassociates a subnet or gateway from a route table.

Type annotations for `aiobotocore.resource("ec2").disassociate_route_table`
method.

Boto3 documentation:
[EC2.ServiceResource.disassociate_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.disassociate_route_table)

Asynchronous method. Use `await disassociate_route_table(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateRouteTableRequestServiceResourceDisassociateRouteTableTypeDef](./type_defs.md#disassociateroutetablerequestserviceresourcedisassociateroutetabletypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `DryRun`: `bool`

<a id="ec2serviceresourceget\_available\_subresources-method"></a>

### EC2ServiceResource.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.ServiceResource.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="ec2serviceresourceimport\_key\_pair-method"></a>

### EC2ServiceResource.import_key_pair method

Imports the public key from an RSA or ED25519 key pair that you created with a
third-party tool.

Type annotations for `aiobotocore.resource("ec2").import_key_pair` method.

Boto3 documentation:
[EC2.ServiceResource.import_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.import_key_pair)

Asynchronous method. Use `await import_key_pair(...)` for a synchronous call.

Arguments mapping described in
[ImportKeyPairRequestServiceResourceImportKeyPairTypeDef](./type_defs.md#importkeypairrequestserviceresourceimportkeypairtypedef).

Keyword-only arguments:

- `KeyName`: `str` *(required)*
- `PublicKeyMaterial`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [KeyPairInfo](#keypairinfo).

<a id="ec2serviceresourceregister\_image-method"></a>

### EC2ServiceResource.register_image method

Registers an AMI.

Type annotations for `aiobotocore.resource("ec2").register_image` method.

Boto3 documentation:
[EC2.ServiceResource.register_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.register_image)

Asynchronous method. Use `await register_image(...)` for a synchronous call.

Arguments mapping described in
[RegisterImageRequestServiceResourceRegisterImageTypeDef](./type_defs.md#registerimagerequestserviceresourceregisterimagetypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `ImageLocation`: `str`
- `Architecture`:
  [ArchitectureValuesType](./literals.md#architecturevaluestype)
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `Description`: `str`
- `DryRun`: `bool`
- `EnaSupport`: `bool`
- `KernelId`: `str`
- `BillingProducts`: `Sequence`\[`str`\]
- `RamdiskId`: `str`
- `RootDeviceName`: `str`
- `SriovNetSupport`: `str`
- `VirtualizationType`: `str`
- `BootMode`: [BootModeValuesType](./literals.md#bootmodevaluestype)

Returns a `Coroutine` for [Image](#image).

<a id="classicaddress"></a>

## ClassicAddress

Type annotations for `aiobotocore.resource("ec2").ClassicAddress` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import ClassicAddress

def get_resource() -> ClassicAddress:
    return boto3.resource("ec2").ClassicAddress(...)
```

Boto3 documentation:
[EC2.ClassicAddress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.ClassicAddress)

<a id="classicaddress-attributes"></a>

### ClassicAddress attributes

- `instance_id`: `str`
- `allocation_id`: `str`
- `association_id`: `str`
- `domain`: [DomainTypeType](./literals.md#domaintypetype)
- `network_interface_id`: `str`
- `network_interface_owner_id`: `str`
- `private_ip_address`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `public_ipv4_pool`: `str`
- `network_border_group`: `str`
- `customer_owned_ip`: `str`
- `customer_owned_ipv4_pool`: `str`
- `carrier_ip`: `str`
- `public_ip`: `str`

<a id="classicaddress-methods"></a>

### ClassicAddress methods

<a id="classicaddressassociate-method"></a>

#### ClassicAddress.associate method

Associates an Elastic IP address, or carrier IP address (for instances that are
in subnets in Wavelength Zones) with an instance or a network interface.

Type annotations for `aiobotocore.resource("ec2").associate` method.

Boto3 documentation:
[EC2.ClassicAddress.associate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ClassicAddress.associate)

Asynchronous method. Use `await associate(...)` for a synchronous call.

Arguments mapping described in
[AssociateAddressRequestClassicAddressAssociateTypeDef](./type_defs.md#associateaddressrequestclassicaddressassociatetypedef).

Keyword-only arguments:

- `AllocationId`: `str`
- `InstanceId`: `str`
- `AllowReassociation`: `bool`
- `DryRun`: `bool`
- `NetworkInterfaceId`: `str`
- `PrivateIpAddress`: `str`

Returns a `Coroutine` for
[AssociateAddressResultTypeDef](./type_defs.md#associateaddressresulttypedef).

<a id="classicaddressdisassociate-method"></a>

#### ClassicAddress.disassociate method

Disassociates an Elastic IP address from the instance or network interface it's
associated with.

Type annotations for `aiobotocore.resource("ec2").disassociate` method.

Boto3 documentation:
[EC2.ClassicAddress.disassociate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ClassicAddress.disassociate)

Asynchronous method. Use `await disassociate(...)` for a synchronous call.

Arguments mapping described in
[DisassociateAddressRequestClassicAddressDisassociateTypeDef](./type_defs.md#disassociateaddressrequestclassicaddressdisassociatetypedef).

Keyword-only arguments:

- `AssociationId`: `str`
- `PublicIp`: `str`
- `DryRun`: `bool`

<a id="classicaddressget\_available\_subresources-method"></a>

#### ClassicAddress.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.ClassicAddress.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ClassicAddress.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="classicaddressload-method"></a>

#### ClassicAddress.load method

Calls :py:meth:`EC2.Client.describe_addresses` to update the attributes of the
ClassicAddress resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.ClassicAddress.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ClassicAddress.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="classicaddressrelease-method"></a>

#### ClassicAddress.release method

Releases the specified Elastic IP address.

Type annotations for `aiobotocore.resource("ec2").release` method.

Boto3 documentation:
[EC2.ClassicAddress.release](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ClassicAddress.release)

Asynchronous method. Use `await release(...)` for a synchronous call.

Arguments mapping described in
[ReleaseAddressRequestClassicAddressReleaseTypeDef](./type_defs.md#releaseaddressrequestclassicaddressreleasetypedef).

Keyword-only arguments:

- `AllocationId`: `str`
- `PublicIp`: `str`
- `NetworkBorderGroup`: `str`
- `DryRun`: `bool`

<a id="classicaddressreload-method"></a>

#### ClassicAddress.reload method

Calls :py:meth:`EC2.Client.describe_addresses` to update the attributes of the
ClassicAddress resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.ClassicAddress.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ClassicAddress.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="dhcpoptions"></a>

## DhcpOptions

Type annotations for `aiobotocore.resource("ec2").DhcpOptions` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import DhcpOptions

def get_resource() -> DhcpOptions:
    return boto3.resource("ec2").DhcpOptions(...)
```

Boto3 documentation:
[EC2.DhcpOptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.DhcpOptions)

<a id="dhcpoptions-attributes"></a>

### DhcpOptions attributes

- `dhcp_configurations`:
  `List`\[[DhcpConfigurationTypeDef](./type_defs.md#dhcpconfigurationtypedef)\]
- `dhcp_options_id`: `str`
- `owner_id`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `id`: `str`

<a id="dhcpoptions-methods"></a>

### DhcpOptions methods

<a id="dhcpoptionsassociate\_with\_vpc-method"></a>

#### DhcpOptions.associate_with_vpc method

Associates a set of DHCP options (that you've previously created) with the
specified VPC, or associates no DHCP options with the VPC.

Type annotations for `aiobotocore.resource("ec2").associate_with_vpc` method.

Boto3 documentation:
[EC2.DhcpOptions.associate_with_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.DhcpOptions.associate_with_vpc)

Asynchronous method. Use `await associate_with_vpc(...)` for a synchronous
call.

Arguments mapping described in
[AssociateDhcpOptionsRequestDhcpOptionsAssociateWithVpcTypeDef](./type_defs.md#associatedhcpoptionsrequestdhcpoptionsassociatewithvpctypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

<a id="dhcpoptionscreate\_tags-method"></a>

#### DhcpOptions.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.DhcpOptions.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.DhcpOptions.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestDhcpOptionsCreateTagsTypeDef](./type_defs.md#createtagsrequestdhcpoptionscreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="dhcpoptionsdelete-method"></a>

#### DhcpOptions.delete method

Deletes the specified set of DHCP options.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.DhcpOptions.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.DhcpOptions.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteDhcpOptionsRequestDhcpOptionsDeleteTypeDef](./type_defs.md#deletedhcpoptionsrequestdhcpoptionsdeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="dhcpoptionsget\_available\_subresources-method"></a>

#### DhcpOptions.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.DhcpOptions.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.DhcpOptions.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="dhcpoptionsload-method"></a>

#### DhcpOptions.load method

Calls :py:meth:`EC2.Client.describe_dhcp_options` to update the attributes of
the DhcpOptions resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.DhcpOptions.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.DhcpOptions.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="dhcpoptionsreload-method"></a>

#### DhcpOptions.reload method

Calls :py:meth:`EC2.Client.describe_dhcp_options` to update the attributes of
the DhcpOptions resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.DhcpOptions.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.DhcpOptions.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="image"></a>

## Image

Type annotations for `aiobotocore.resource("ec2").Image` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Image

def get_resource() -> Image:
    return boto3.resource("ec2").Image(...)
```

Boto3 documentation:
[EC2.Image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Image)

<a id="image-attributes"></a>

### Image attributes

- `architecture`:
  [ArchitectureValuesType](./literals.md#architecturevaluestype)
- `creation_date`: `str`
- `image_id`: `str`
- `image_location`: `str`
- `image_type`: [ImageTypeValuesType](./literals.md#imagetypevaluestype)
- `public`: `bool`
- `kernel_id`: `str`
- `owner_id`: `str`
- `platform`: `Literal['Windows']` (see
  [PlatformValuesType](./literals.md#platformvaluestype))
- `platform_details`: `str`
- `usage_operation`: `str`
- `product_codes`:
  `List`\[[ProductCodeTypeDef](./type_defs.md#productcodetypedef)\]
- `ramdisk_id`: `str`
- `state`: [ImageStateType](./literals.md#imagestatetype)
- `block_device_mappings`:
  `List`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `description`: `str`
- `ena_support`: `bool`
- `hypervisor`: [HypervisorTypeType](./literals.md#hypervisortypetype)
- `image_owner_alias`: `str`
- `name`: `str`
- `root_device_name`: `str`
- `root_device_type`: [DeviceTypeType](./literals.md#devicetypetype)
- `sriov_net_support`: `str`
- `state_reason`:
  [StateReasonResponseMetadataTypeDef](./type_defs.md#statereasonresponsemetadatatypedef)
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `virtualization_type`:
  [VirtualizationTypeType](./literals.md#virtualizationtypetype)
- `boot_mode`: [BootModeValuesType](./literals.md#bootmodevaluestype)
- `deprecation_time`: `str`
- `id`: `str`

<a id="image-methods"></a>

### Image methods

<a id="imagecreate\_tags-method"></a>

#### Image.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.Image.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestImageCreateTagsTypeDef](./type_defs.md#createtagsrequestimagecreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="imagederegister-method"></a>

#### Image.deregister method

Deregisters the specified AMI.

Type annotations for `aiobotocore.resource("ec2").deregister` method.

Boto3 documentation:
[EC2.Image.deregister](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.deregister)

Asynchronous method. Use `await deregister(...)` for a synchronous call.

Arguments mapping described in
[DeregisterImageRequestImageDeregisterTypeDef](./type_defs.md#deregisterimagerequestimagederegistertypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="imagedescribe\_attribute-method"></a>

#### Image.describe_attribute method

Describes the specified attribute of the specified AMI.

Type annotations for `aiobotocore.resource("ec2").describe_attribute` method.

Boto3 documentation:
[EC2.Image.describe_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.describe_attribute)

Asynchronous method. Use `await describe_attribute(...)` for a synchronous
call.

Arguments mapping described in
[DescribeImageAttributeRequestImageDescribeAttributeTypeDef](./type_defs.md#describeimageattributerequestimagedescribeattributetypedef).

Keyword-only arguments:

- `Attribute`: [ImageAttributeNameType](./literals.md#imageattributenametype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ImageAttributeTypeDef](./type_defs.md#imageattributetypedef).

<a id="imageget\_available\_subresources-method"></a>

#### Image.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Image.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="imageload-method"></a>

#### Image.load method

Calls :py:meth:`EC2.Client.describe_images` to update the attributes of the
Image resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.Image.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="imagemodify\_attribute-method"></a>

#### Image.modify_attribute method

Modifies the specified attribute of the specified AMI.

Type annotations for `aiobotocore.resource("ec2").modify_attribute` method.

Boto3 documentation:
[EC2.Image.modify_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.modify_attribute)

Asynchronous method. Use `await modify_attribute(...)` for a synchronous call.

Arguments mapping described in
[ModifyImageAttributeRequestImageModifyAttributeTypeDef](./type_defs.md#modifyimageattributerequestimagemodifyattributetypedef).

Keyword-only arguments:

- `Attribute`: `str`
- `Description`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `LaunchPermission`:
  [LaunchPermissionModificationsTypeDef](./type_defs.md#launchpermissionmodificationstypedef)
- `OperationType`: [OperationTypeType](./literals.md#operationtypetype)
- `ProductCodes`: `Sequence`\[`str`\]
- `UserGroups`: `Sequence`\[`str`\]
- `UserIds`: `Sequence`\[`str`\]
- `Value`: `str`
- `DryRun`: `bool`
- `OrganizationArns`: `Sequence`\[`str`\]
- `OrganizationalUnitArns`: `Sequence`\[`str`\]

<a id="imagereload-method"></a>

#### Image.reload method

Calls :py:meth:`EC2.Client.describe_images` to update the attributes of the
Image resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.Image.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="imagereset\_attribute-method"></a>

#### Image.reset_attribute method

Resets an attribute of an AMI to its default value.

Type annotations for `aiobotocore.resource("ec2").reset_attribute` method.

Boto3 documentation:
[EC2.Image.reset_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.reset_attribute)

Asynchronous method. Use `await reset_attribute(...)` for a synchronous call.

Arguments mapping described in
[ResetImageAttributeRequestImageResetAttributeTypeDef](./type_defs.md#resetimageattributerequestimageresetattributetypedef).

Keyword-only arguments:

- `Attribute`: `Literal['launchPermission']` (see
  [ResetImageAttributeNameType](./literals.md#resetimageattributenametype))
  *(required)*
- `DryRun`: `bool`

<a id="imagewait\_until\_exists-method"></a>

#### Image.wait_until_exists method

Waits until this Image is exists.

Type annotations for `aiobotocore.resource("ec2").wait_until_exists` method.

Boto3 documentation:
[EC2.Image.wait_until_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Image.wait_until_exists)

Asynchronous method. Use `await wait_until_exists(...)` for a synchronous call.

<a id="instance"></a>

## Instance

Type annotations for `aiobotocore.resource("ec2").Instance` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Instance

def get_resource() -> Instance:
    return boto3.resource("ec2").Instance(...)
```

Boto3 documentation:
[EC2.Instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Instance)

<a id="instance-attributes"></a>

### Instance attributes

- `ami_launch_index`: `int`
- `image_id`: `str`
- `instance_id`: `str`
- `instance_type`: [InstanceTypeType](./literals.md#instancetypetype)
- `kernel_id`: `str`
- `key_name`: `str`
- `launch_time`: `datetime`
- `monitoring`:
  [MonitoringResponseMetadataTypeDef](./type_defs.md#monitoringresponsemetadatatypedef)
- `placement`:
  [PlacementResponseMetadataTypeDef](./type_defs.md#placementresponsemetadatatypedef)
- `platform`: `Literal['Windows']` (see
  [PlatformValuesType](./literals.md#platformvaluestype))
- `private_dns_name`: `str`
- `private_ip_address`: `str`
- `product_codes`:
  `List`\[[ProductCodeTypeDef](./type_defs.md#productcodetypedef)\]
- `public_dns_name`: `str`
- `public_ip_address`: `str`
- `ramdisk_id`: `str`
- `state`:
  [InstanceStateResponseMetadataTypeDef](./type_defs.md#instancestateresponsemetadatatypedef)
- `state_transition_reason`: `str`
- `subnet_id`: `str`
- `vpc_id`: `str`
- `architecture`:
  [ArchitectureValuesType](./literals.md#architecturevaluestype)
- `block_device_mappings`:
  `List`\[[InstanceBlockDeviceMappingTypeDef](./type_defs.md#instanceblockdevicemappingtypedef)\]
- `client_token`: `str`
- `ebs_optimized`: `bool`
- `ena_support`: `bool`
- `hypervisor`: [HypervisorTypeType](./literals.md#hypervisortypetype)
- `iam_instance_profile`:
  [IamInstanceProfileResponseMetadataTypeDef](./type_defs.md#iaminstanceprofileresponsemetadatatypedef)
- `instance_lifecycle`:
  [InstanceLifecycleTypeType](./literals.md#instancelifecycletypetype)
- `elastic_gpu_associations`:
  `List`\[[ElasticGpuAssociationTypeDef](./type_defs.md#elasticgpuassociationtypedef)\]
- `elastic_inference_accelerator_associations`:
  `List`\[[ElasticInferenceAcceleratorAssociationTypeDef](./type_defs.md#elasticinferenceacceleratorassociationtypedef)\]
- `network_interfaces_attribute`:
  `List`\[[InstanceNetworkInterfaceTypeDef](./type_defs.md#instancenetworkinterfacetypedef)\]
- `outpost_arn`: `str`
- `root_device_name`: `str`
- `root_device_type`: [DeviceTypeType](./literals.md#devicetypetype)
- `security_groups`:
  `List`\[[GroupIdentifierTypeDef](./type_defs.md#groupidentifiertypedef)\]
- `source_dest_check`: `bool`
- `spot_instance_request_id`: `str`
- `sriov_net_support`: `str`
- `state_reason`:
  [StateReasonResponseMetadataTypeDef](./type_defs.md#statereasonresponsemetadatatypedef)
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `virtualization_type`:
  [VirtualizationTypeType](./literals.md#virtualizationtypetype)
- `cpu_options`:
  [CpuOptionsResponseMetadataTypeDef](./type_defs.md#cpuoptionsresponsemetadatatypedef)
- `capacity_reservation_id`: `str`
- `capacity_reservation_specification`:
  [CapacityReservationSpecificationResponseResponseMetadataTypeDef](./type_defs.md#capacityreservationspecificationresponseresponsemetadatatypedef)
- `hibernation_options`:
  [HibernationOptionsResponseMetadataTypeDef](./type_defs.md#hibernationoptionsresponsemetadatatypedef)
- `licenses`:
  `List`\[[LicenseConfigurationTypeDef](./type_defs.md#licenseconfigurationtypedef)\]
- `metadata_options`:
  [InstanceMetadataOptionsResponseResponseMetadataTypeDef](./type_defs.md#instancemetadataoptionsresponseresponsemetadatatypedef)
- `enclave_options`:
  [EnclaveOptionsResponseMetadataTypeDef](./type_defs.md#enclaveoptionsresponsemetadatatypedef)
- `boot_mode`: [BootModeValuesType](./literals.md#bootmodevaluestype)
- `platform_details`: `str`
- `usage_operation`: `str`
- `usage_operation_update_time`: `datetime`
- `private_dns_name_options`:
  [PrivateDnsNameOptionsResponseResponseMetadataTypeDef](./type_defs.md#privatednsnameoptionsresponseresponsemetadatatypedef)
- `ipv6_address`: `str`
- `id`: `str`
- `classic_address`: [ClassicAddress](#classicaddress)
- `image`: [Image](#image)
- `key_pair`: [KeyPairInfo](#keypairinfo)
- `network_interfaces`: `List`\[[NetworkInterface](#networkinterface)\]
- `placement_group`: [PlacementGroup](#placementgroup)
- `subnet`: [Subnet](#subnet)
- `vpc`: [Vpc](#vpc)
- `volumes`: [InstanceVolumesCollection](#instancevolumescollection)
- `vpc_addresses`:
  [InstanceVpcAddressesCollection](#instancevpcaddressescollection)

<a id="instance-collections"></a>

### Instance collections

<a id="instancevolumes"></a>

#### Instance.volumes

Type annotations for `aiobotocore.resource("ec2").Instance(...).volumes`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import InstanceVolumesCollection,

def get_collection() -> InstanceVolumesCollection:
    resource = boto3.resource("ec2").Instance(...)
    return resource.volumes
```

Provides access to [Volume](#volume) resource.

Boto3 documentation:
[EC2.Instance.InstanceVolumesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.volumes)

<a id="instancevpc_addresses"></a>

#### Instance.vpc_addresses

Type annotations for `aiobotocore.resource("ec2").Instance(...).vpc_addresses`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import InstanceVpcAddressesCollection,

def get_collection() -> InstanceVpcAddressesCollection:
    resource = boto3.resource("ec2").Instance(...)
    return resource.vpc_addresses
```

Provides access to [VpcAddress](#vpcaddress) resource.

Boto3 documentation:
[EC2.Instance.InstanceVpcAddressesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.vpc_addresses)

<a id="instance-methods"></a>

### Instance methods

<a id="instanceattach\_classic\_link\_vpc-method"></a>

#### Instance.attach_classic_link_vpc method

Links an EC2-Classic instance to a ClassicLink-enabled VPC through one or more
of the VPC's security groups.

Type annotations for `aiobotocore.resource("ec2").attach_classic_link_vpc`
method.

Boto3 documentation:
[EC2.Instance.attach_classic_link_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.attach_classic_link_vpc)

Asynchronous method. Use `await attach_classic_link_vpc(...)` for a synchronous
call.

Arguments mapping described in
[AttachClassicLinkVpcRequestInstanceAttachClassicLinkVpcTypeDef](./type_defs.md#attachclassiclinkvpcrequestinstanceattachclassiclinkvpctypedef).

Keyword-only arguments:

- `Groups`: `Sequence`\[`str`\] *(required)*
- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AttachClassicLinkVpcResultTypeDef](./type_defs.md#attachclassiclinkvpcresulttypedef).

<a id="instanceattach\_volume-method"></a>

#### Instance.attach_volume method

Attaches an EBS volume to a running or stopped instance and exposes it to the
instance with the specified device name.

Type annotations for `aiobotocore.resource("ec2").attach_volume` method.

Boto3 documentation:
[EC2.Instance.attach_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.attach_volume)

Asynchronous method. Use `await attach_volume(...)` for a synchronous call.

Arguments mapping described in
[AttachVolumeRequestInstanceAttachVolumeTypeDef](./type_defs.md#attachvolumerequestinstanceattachvolumetypedef).

Keyword-only arguments:

- `Device`: `str` *(required)*
- `VolumeId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[VolumeAttachmentResponseMetadataTypeDef](./type_defs.md#volumeattachmentresponsemetadatatypedef).

<a id="instanceconsole\_output-method"></a>

#### Instance.console_output method

Gets the console output for the specified instance.

Type annotations for `aiobotocore.resource("ec2").console_output` method.

Boto3 documentation:
[EC2.Instance.console_output](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.console_output)

Asynchronous method. Use `await console_output(...)` for a synchronous call.

Arguments mapping described in
[GetConsoleOutputRequestInstanceConsoleOutputTypeDef](./type_defs.md#getconsoleoutputrequestinstanceconsoleoutputtypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Latest`: `bool`

Returns a `Coroutine` for
[GetConsoleOutputResultTypeDef](./type_defs.md#getconsoleoutputresulttypedef).

<a id="instancecreate\_image-method"></a>

#### Instance.create_image method

Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance that is
either running or stopped.

Type annotations for `aiobotocore.resource("ec2").create_image` method.

Boto3 documentation:
[EC2.Instance.create_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.create_image)

Asynchronous method. Use `await create_image(...)` for a synchronous call.

Arguments mapping described in
[CreateImageRequestInstanceCreateImageTypeDef](./type_defs.md#createimagerequestinstancecreateimagetypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `Description`: `str`
- `DryRun`: `bool`
- `NoReboot`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [Image](#image).

<a id="instancecreate\_tags-method"></a>

#### Instance.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.Instance.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestInstanceCreateTagsTypeDef](./type_defs.md#createtagsrequestinstancecreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="instancedelete\_tags-method"></a>

#### Instance.delete_tags method

Deletes the specified set of tags from the specified set of resources.

Type annotations for `aiobotocore.resource("ec2").delete_tags` method.

Boto3 documentation:
[EC2.Instance.delete_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.delete_tags)

Asynchronous method. Use `await delete_tags(...)` for a synchronous call.

Arguments mapping described in
[InstanceDeleteTagsRequestTypeDef](./type_defs.md#instancedeletetagsrequesttypedef).

Arguments:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `DryRun`: `bool`

<a id="instancedescribe\_attribute-method"></a>

#### Instance.describe_attribute method

Describes the specified attribute of the specified instance.

Type annotations for `aiobotocore.resource("ec2").describe_attribute` method.

Boto3 documentation:
[EC2.Instance.describe_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.describe_attribute)

Asynchronous method. Use `await describe_attribute(...)` for a synchronous
call.

Arguments mapping described in
[DescribeInstanceAttributeRequestInstanceDescribeAttributeTypeDef](./type_defs.md#describeinstanceattributerequestinstancedescribeattributetypedef).

Keyword-only arguments:

- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[InstanceAttributeTypeDef](./type_defs.md#instanceattributetypedef).

<a id="instancedetach\_classic\_link\_vpc-method"></a>

#### Instance.detach_classic_link_vpc method

Unlinks (detaches) a linked EC2-Classic instance from a VPC.

Type annotations for `aiobotocore.resource("ec2").detach_classic_link_vpc`
method.

Boto3 documentation:
[EC2.Instance.detach_classic_link_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.detach_classic_link_vpc)

Asynchronous method. Use `await detach_classic_link_vpc(...)` for a synchronous
call.

Arguments mapping described in
[DetachClassicLinkVpcRequestInstanceDetachClassicLinkVpcTypeDef](./type_defs.md#detachclassiclinkvpcrequestinstancedetachclassiclinkvpctypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DetachClassicLinkVpcResultTypeDef](./type_defs.md#detachclassiclinkvpcresulttypedef).

<a id="instancedetach\_volume-method"></a>

#### Instance.detach_volume method

Detaches an EBS volume from an instance.

Type annotations for `aiobotocore.resource("ec2").detach_volume` method.

Boto3 documentation:
[EC2.Instance.detach_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.detach_volume)

Asynchronous method. Use `await detach_volume(...)` for a synchronous call.

Arguments mapping described in
[DetachVolumeRequestInstanceDetachVolumeTypeDef](./type_defs.md#detachvolumerequestinstancedetachvolumetypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `Device`: `str`
- `Force`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[VolumeAttachmentResponseMetadataTypeDef](./type_defs.md#volumeattachmentresponsemetadatatypedef).

<a id="instanceget\_available\_subresources-method"></a>

#### Instance.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Instance.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="instanceload-method"></a>

#### Instance.load method

Calls :py:meth:`EC2.Client.describe_instances` to update the attributes of the
Instance resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.Instance.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="instancemodify\_attribute-method"></a>

#### Instance.modify_attribute method

Modifies the specified attribute of the specified instance.

Type annotations for `aiobotocore.resource("ec2").modify_attribute` method.

Boto3 documentation:
[EC2.Instance.modify_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.modify_attribute)

Asynchronous method. Use `await modify_attribute(...)` for a synchronous call.

Arguments mapping described in
[ModifyInstanceAttributeRequestInstanceModifyAttributeTypeDef](./type_defs.md#modifyinstanceattributerequestinstancemodifyattributetypedef).

Keyword-only arguments:

- `SourceDestCheck`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
- `BlockDeviceMappings`:
  `Sequence`\[[InstanceBlockDeviceMappingSpecificationTypeDef](./type_defs.md#instanceblockdevicemappingspecificationtypedef)\]
- `DisableApiTermination`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `DryRun`: `bool`
- `EbsOptimized`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `EnaSupport`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `Groups`: `Sequence`\[`str`\]
- `InstanceInitiatedShutdownBehavior`:
  [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `InstanceType`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `Kernel`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `Ramdisk`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `SriovNetSupport`:
  [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `UserData`:
  [BlobAttributeValueTypeDef](./type_defs.md#blobattributevaluetypedef)
- `Value`: `str`

<a id="instancemonitor-method"></a>

#### Instance.monitor method

Enables detailed monitoring for a running instance.

Type annotations for `aiobotocore.resource("ec2").monitor` method.

Boto3 documentation:
[EC2.Instance.monitor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.monitor)

Asynchronous method. Use `await monitor(...)` for a synchronous call.

Arguments mapping described in
[MonitorInstancesRequestInstanceMonitorTypeDef](./type_defs.md#monitorinstancesrequestinstancemonitortypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[MonitorInstancesResultTypeDef](./type_defs.md#monitorinstancesresulttypedef).

<a id="instancepassword\_data-method"></a>

#### Instance.password_data method

Retrieves the encrypted administrator password for a running Windows instance.

Type annotations for `aiobotocore.resource("ec2").password_data` method.

Boto3 documentation:
[EC2.Instance.password_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.password_data)

Asynchronous method. Use `await password_data(...)` for a synchronous call.

Arguments mapping described in
[GetPasswordDataRequestInstancePasswordDataTypeDef](./type_defs.md#getpassworddatarequestinstancepassworddatatypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[GetPasswordDataResultTypeDef](./type_defs.md#getpassworddataresulttypedef).

<a id="instancereboot-method"></a>

#### Instance.reboot method

Requests a reboot of the specified instances.

Type annotations for `aiobotocore.resource("ec2").reboot` method.

Boto3 documentation:
[EC2.Instance.reboot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.reboot)

Asynchronous method. Use `await reboot(...)` for a synchronous call.

Arguments mapping described in
[RebootInstancesRequestInstanceRebootTypeDef](./type_defs.md#rebootinstancesrequestinstancereboottypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="instancereload-method"></a>

#### Instance.reload method

Calls :py:meth:`EC2.Client.describe_instances` to update the attributes of the
Instance resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.Instance.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="instancereport\_status-method"></a>

#### Instance.report_status method

Submits feedback about the status of an instance.

Type annotations for `aiobotocore.resource("ec2").report_status` method.

Boto3 documentation:
[EC2.Instance.report_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.report_status)

Asynchronous method. Use `await report_status(...)` for a synchronous call.

Arguments mapping described in
[ReportInstanceStatusRequestInstanceReportStatusTypeDef](./type_defs.md#reportinstancestatusrequestinstancereportstatustypedef).

Keyword-only arguments:

- `ReasonCodes`:
  `Sequence`\[[ReportInstanceReasonCodesType](./literals.md#reportinstancereasoncodestype)\]
  *(required)*
- `Status`: [ReportStatusTypeType](./literals.md#reportstatustypetype)
  *(required)*
- `Description`: `str`
- `DryRun`: `bool`
- `EndTime`: `Union`\[`datetime`, `str`\]
- `StartTime`: `Union`\[`datetime`, `str`\]

<a id="instancereset\_attribute-method"></a>

#### Instance.reset_attribute method

Resets an attribute of an instance to its default value.

Type annotations for `aiobotocore.resource("ec2").reset_attribute` method.

Boto3 documentation:
[EC2.Instance.reset_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.reset_attribute)

Asynchronous method. Use `await reset_attribute(...)` for a synchronous call.

Arguments mapping described in
[ResetInstanceAttributeRequestInstanceResetAttributeTypeDef](./type_defs.md#resetinstanceattributerequestinstanceresetattributetypedef).

Keyword-only arguments:

- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
  *(required)*
- `DryRun`: `bool`

<a id="instancereset\_kernel-method"></a>

#### Instance.reset_kernel method

Resets an attribute of an instance to its default value.

Type annotations for `aiobotocore.resource("ec2").reset_kernel` method.

Boto3 documentation:
[EC2.Instance.reset_kernel](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.reset_kernel)

Asynchronous method. Use `await reset_kernel(...)` for a synchronous call.

Arguments mapping described in
[ResetInstanceAttributeRequestInstanceResetKernelTypeDef](./type_defs.md#resetinstanceattributerequestinstanceresetkerneltypedef).

Keyword-only arguments:

- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
- `DryRun`: `bool`

<a id="instancereset\_ramdisk-method"></a>

#### Instance.reset_ramdisk method

Resets an attribute of an instance to its default value.

Type annotations for `aiobotocore.resource("ec2").reset_ramdisk` method.

Boto3 documentation:
[EC2.Instance.reset_ramdisk](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.reset_ramdisk)

Asynchronous method. Use `await reset_ramdisk(...)` for a synchronous call.

Arguments mapping described in
[ResetInstanceAttributeRequestInstanceResetRamdiskTypeDef](./type_defs.md#resetinstanceattributerequestinstanceresetramdisktypedef).

Keyword-only arguments:

- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
- `DryRun`: `bool`

<a id="instancereset\_source\_dest\_check-method"></a>

#### Instance.reset_source_dest_check method

Resets an attribute of an instance to its default value.

Type annotations for `aiobotocore.resource("ec2").reset_source_dest_check`
method.

Boto3 documentation:
[EC2.Instance.reset_source_dest_check](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.reset_source_dest_check)

Asynchronous method. Use `await reset_source_dest_check(...)` for a synchronous
call.

Arguments mapping described in
[ResetInstanceAttributeRequestInstanceResetSourceDestCheckTypeDef](./type_defs.md#resetinstanceattributerequestinstanceresetsourcedestchecktypedef).

Keyword-only arguments:

- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
- `DryRun`: `bool`

<a id="instancestart-method"></a>

#### Instance.start method

Starts an Amazon EBS-backed instance that you've previously stopped.

Type annotations for `aiobotocore.resource("ec2").start` method.

Boto3 documentation:
[EC2.Instance.start](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.start)

Asynchronous method. Use `await start(...)` for a synchronous call.

Arguments mapping described in
[StartInstancesRequestInstanceStartTypeDef](./type_defs.md#startinstancesrequestinstancestarttypedef).

Keyword-only arguments:

- `AdditionalInfo`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[StartInstancesResultTypeDef](./type_defs.md#startinstancesresulttypedef).

<a id="instancestop-method"></a>

#### Instance.stop method

Stops an Amazon EBS-backed instance.

Type annotations for `aiobotocore.resource("ec2").stop` method.

Boto3 documentation:
[EC2.Instance.stop](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.stop)

Asynchronous method. Use `await stop(...)` for a synchronous call.

Arguments mapping described in
[StopInstancesRequestInstanceStopTypeDef](./type_defs.md#stopinstancesrequestinstancestoptypedef).

Keyword-only arguments:

- `Hibernate`: `bool`
- `DryRun`: `bool`
- `Force`: `bool`

Returns a `Coroutine` for
[StopInstancesResultTypeDef](./type_defs.md#stopinstancesresulttypedef).

<a id="instanceterminate-method"></a>

#### Instance.terminate method

Shuts down the specified instances.

Type annotations for `aiobotocore.resource("ec2").terminate` method.

Boto3 documentation:
[EC2.Instance.terminate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.terminate)

Asynchronous method. Use `await terminate(...)` for a synchronous call.

Arguments mapping described in
[TerminateInstancesRequestInstanceTerminateTypeDef](./type_defs.md#terminateinstancesrequestinstanceterminatetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[TerminateInstancesResultTypeDef](./type_defs.md#terminateinstancesresulttypedef).

<a id="instanceunmonitor-method"></a>

#### Instance.unmonitor method

Disables detailed monitoring for a running instance.

Type annotations for `aiobotocore.resource("ec2").unmonitor` method.

Boto3 documentation:
[EC2.Instance.unmonitor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.unmonitor)

Asynchronous method. Use `await unmonitor(...)` for a synchronous call.

Arguments mapping described in
[UnmonitorInstancesRequestInstanceUnmonitorTypeDef](./type_defs.md#unmonitorinstancesrequestinstanceunmonitortypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[UnmonitorInstancesResultTypeDef](./type_defs.md#unmonitorinstancesresulttypedef).

<a id="instancewait\_until\_exists-method"></a>

#### Instance.wait_until_exists method

Waits until this Instance is exists.

Type annotations for `aiobotocore.resource("ec2").wait_until_exists` method.

Boto3 documentation:
[EC2.Instance.wait_until_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.wait_until_exists)

Asynchronous method. Use `await wait_until_exists(...)` for a synchronous call.

<a id="instancewait\_until\_running-method"></a>

#### Instance.wait_until_running method

Waits until this Instance is running.

Type annotations for `aiobotocore.resource("ec2").wait_until_running` method.

Boto3 documentation:
[EC2.Instance.wait_until_running](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.wait_until_running)

Asynchronous method. Use `await wait_until_running(...)` for a synchronous
call.

<a id="instancewait\_until\_stopped-method"></a>

#### Instance.wait_until_stopped method

Waits until this Instance is stopped.

Type annotations for `aiobotocore.resource("ec2").wait_until_stopped` method.

Boto3 documentation:
[EC2.Instance.wait_until_stopped](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.wait_until_stopped)

Asynchronous method. Use `await wait_until_stopped(...)` for a synchronous
call.

<a id="instancewait\_until\_terminated-method"></a>

#### Instance.wait_until_terminated method

Waits until this Instance is terminated.

Type annotations for `aiobotocore.resource("ec2").wait_until_terminated`
method.

Boto3 documentation:
[EC2.Instance.wait_until_terminated](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Instance.wait_until_terminated)

Asynchronous method. Use `await wait_until_terminated(...)` for a synchronous
call.

<a id="internetgateway"></a>

## InternetGateway

Type annotations for `aiobotocore.resource("ec2").InternetGateway` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import InternetGateway

def get_resource() -> InternetGateway:
    return boto3.resource("ec2").InternetGateway(...)
```

Boto3 documentation:
[EC2.InternetGateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.InternetGateway)

<a id="internetgateway-attributes"></a>

### InternetGateway attributes

- `attachments`:
  `List`\[[InternetGatewayAttachmentTypeDef](./type_defs.md#internetgatewayattachmenttypedef)\]
- `internet_gateway_id`: `str`
- `owner_id`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `id`: `str`

<a id="internetgateway-methods"></a>

### InternetGateway methods

<a id="internetgatewayattach\_to\_vpc-method"></a>

#### InternetGateway.attach_to_vpc method

Attaches an internet gateway or a virtual private gateway to a VPC, enabling
connectivity between the internet and the VPC.

Type annotations for `aiobotocore.resource("ec2").attach_to_vpc` method.

Boto3 documentation:
[EC2.InternetGateway.attach_to_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.InternetGateway.attach_to_vpc)

Asynchronous method. Use `await attach_to_vpc(...)` for a synchronous call.

Arguments mapping described in
[AttachInternetGatewayRequestInternetGatewayAttachToVpcTypeDef](./type_defs.md#attachinternetgatewayrequestinternetgatewayattachtovpctypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

<a id="internetgatewaycreate\_tags-method"></a>

#### InternetGateway.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.InternetGateway.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.InternetGateway.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestInternetGatewayCreateTagsTypeDef](./type_defs.md#createtagsrequestinternetgatewaycreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="internetgatewaydelete-method"></a>

#### InternetGateway.delete method

Deletes the specified internet gateway.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.InternetGateway.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.InternetGateway.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteInternetGatewayRequestInternetGatewayDeleteTypeDef](./type_defs.md#deleteinternetgatewayrequestinternetgatewaydeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="internetgatewaydetach\_from\_vpc-method"></a>

#### InternetGateway.detach_from_vpc method

Detaches an internet gateway from a VPC, disabling connectivity between the
internet and the VPC.

Type annotations for `aiobotocore.resource("ec2").detach_from_vpc` method.

Boto3 documentation:
[EC2.InternetGateway.detach_from_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.InternetGateway.detach_from_vpc)

Asynchronous method. Use `await detach_from_vpc(...)` for a synchronous call.

Arguments mapping described in
[DetachInternetGatewayRequestInternetGatewayDetachFromVpcTypeDef](./type_defs.md#detachinternetgatewayrequestinternetgatewaydetachfromvpctypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

<a id="internetgatewayget\_available\_subresources-method"></a>

#### InternetGateway.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.InternetGateway.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.InternetGateway.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="internetgatewayload-method"></a>

#### InternetGateway.load method

Calls :py:meth:`EC2.Client.describe_internet_gateways` to update the attributes
of the InternetGateway resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.InternetGateway.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.InternetGateway.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="internetgatewayreload-method"></a>

#### InternetGateway.reload method

Calls :py:meth:`EC2.Client.describe_internet_gateways` to update the attributes
of the InternetGateway resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.InternetGateway.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.InternetGateway.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="keypair"></a>

## KeyPair

Type annotations for `aiobotocore.resource("ec2").KeyPair` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import KeyPair

def get_resource() -> KeyPair:
    return boto3.resource("ec2").KeyPair(...)
```

Boto3 documentation:
[EC2.KeyPair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.KeyPair)

<a id="keypair-attributes"></a>

### KeyPair attributes

- `key_fingerprint`: `str`
- `key_material`: `str`
- `key_name`: `str`
- `key_pair_id`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `name`: `str`

<a id="keypair-methods"></a>

### KeyPair methods

<a id="keypairdelete-method"></a>

#### KeyPair.delete method

Deletes the specified key pair, by removing the public key from Amazon EC2.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.KeyPair.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.KeyPair.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteKeyPairRequestKeyPairDeleteTypeDef](./type_defs.md#deletekeypairrequestkeypairdeletetypedef).

Keyword-only arguments:

- `KeyPairId`: `str`
- `DryRun`: `bool`

<a id="keypairget\_available\_subresources-method"></a>

#### KeyPair.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.KeyPair.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.KeyPair.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="keypairinfo"></a>

## KeyPairInfo

Type annotations for `aiobotocore.resource("ec2").KeyPairInfo` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import KeyPairInfo

def get_resource() -> KeyPairInfo:
    return boto3.resource("ec2").KeyPairInfo(...)
```

Boto3 documentation:
[EC2.KeyPairInfo](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.KeyPairInfo)

<a id="keypairinfo-attributes"></a>

### KeyPairInfo attributes

- `key_pair_id`: `str`
- `key_fingerprint`: `str`
- `key_name`: `str`
- `key_type`: [KeyTypeType](./literals.md#keytypetype)
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `name`: `str`

<a id="keypairinfo-methods"></a>

### KeyPairInfo methods

<a id="keypairinfodelete-method"></a>

#### KeyPairInfo.delete method

Deletes the specified key pair, by removing the public key from Amazon EC2.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.KeyPairInfo.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.KeyPairInfo.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteKeyPairRequestKeyPairInfoDeleteTypeDef](./type_defs.md#deletekeypairrequestkeypairinfodeletetypedef).

Keyword-only arguments:

- `KeyPairId`: `str`
- `DryRun`: `bool`

<a id="keypairinfoget\_available\_subresources-method"></a>

#### KeyPairInfo.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.KeyPairInfo.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.KeyPairInfo.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="keypairinfoload-method"></a>

#### KeyPairInfo.load method

Calls :py:meth:`EC2.Client.describe_key_pairs` to update the attributes of the
KeyPairInfo resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.KeyPairInfo.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.KeyPairInfo.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="keypairinforeload-method"></a>

#### KeyPairInfo.reload method

Calls :py:meth:`EC2.Client.describe_key_pairs` to update the attributes of the
KeyPairInfo resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.KeyPairInfo.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.KeyPairInfo.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="networkacl"></a>

## NetworkAcl

Type annotations for `aiobotocore.resource("ec2").NetworkAcl` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import NetworkAcl

def get_resource() -> NetworkAcl:
    return boto3.resource("ec2").NetworkAcl(...)
```

Boto3 documentation:
[EC2.NetworkAcl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.NetworkAcl)

<a id="networkacl-attributes"></a>

### NetworkAcl attributes

- `associations`:
  `List`\[[NetworkAclAssociationTypeDef](./type_defs.md#networkaclassociationtypedef)\]
- `entries`:
  `List`\[[NetworkAclEntryTypeDef](./type_defs.md#networkaclentrytypedef)\]
- `is_default`: `bool`
- `network_acl_id`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `vpc_id`: `str`
- `owner_id`: `str`
- `id`: `str`
- `vpc`: [Vpc](#vpc)

<a id="networkacl-methods"></a>

### NetworkAcl methods

<a id="networkaclcreate\_entry-method"></a>

#### NetworkAcl.create_entry method

Creates an entry (a rule) in a network ACL with the specified rule number.

Type annotations for `aiobotocore.resource("ec2").create_entry` method.

Boto3 documentation:
[EC2.NetworkAcl.create_entry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.create_entry)

Asynchronous method. Use `await create_entry(...)` for a synchronous call.

Arguments mapping described in
[CreateNetworkAclEntryRequestNetworkAclCreateEntryTypeDef](./type_defs.md#createnetworkaclentryrequestnetworkaclcreateentrytypedef).

Keyword-only arguments:

- `Egress`: `bool` *(required)*
- `Protocol`: `str` *(required)*
- `RuleAction`: [RuleActionType](./literals.md#ruleactiontype) *(required)*
- `RuleNumber`: `int` *(required)*
- `CidrBlock`: `str`
- `DryRun`: `bool`
- `IcmpTypeCode`: [IcmpTypeCodeTypeDef](./type_defs.md#icmptypecodetypedef)
- `Ipv6CidrBlock`: `str`
- `PortRange`: [PortRangeTypeDef](./type_defs.md#portrangetypedef)

<a id="networkaclcreate\_tags-method"></a>

#### NetworkAcl.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.NetworkAcl.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestNetworkAclCreateTagsTypeDef](./type_defs.md#createtagsrequestnetworkaclcreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="networkacldelete-method"></a>

#### NetworkAcl.delete method

Deletes the specified network ACL.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.NetworkAcl.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteNetworkAclRequestNetworkAclDeleteTypeDef](./type_defs.md#deletenetworkaclrequestnetworkacldeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="networkacldelete\_entry-method"></a>

#### NetworkAcl.delete_entry method

Deletes the specified ingress or egress entry (rule) from the specified network
ACL.

Type annotations for `aiobotocore.resource("ec2").delete_entry` method.

Boto3 documentation:
[EC2.NetworkAcl.delete_entry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.delete_entry)

Asynchronous method. Use `await delete_entry(...)` for a synchronous call.

Arguments mapping described in
[DeleteNetworkAclEntryRequestNetworkAclDeleteEntryTypeDef](./type_defs.md#deletenetworkaclentryrequestnetworkacldeleteentrytypedef).

Keyword-only arguments:

- `Egress`: `bool` *(required)*
- `RuleNumber`: `int` *(required)*
- `DryRun`: `bool`

<a id="networkaclget\_available\_subresources-method"></a>

#### NetworkAcl.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.NetworkAcl.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="networkaclload-method"></a>

#### NetworkAcl.load method

Calls :py:meth:`EC2.Client.describe_network_acls` to update the attributes of
the NetworkAcl resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.NetworkAcl.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="networkaclreload-method"></a>

#### NetworkAcl.reload method

Calls :py:meth:`EC2.Client.describe_network_acls` to update the attributes of
the NetworkAcl resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.NetworkAcl.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="networkaclreplace\_association-method"></a>

#### NetworkAcl.replace_association method

Changes which network ACL a subnet is associated with.

Type annotations for `aiobotocore.resource("ec2").replace_association` method.

Boto3 documentation:
[EC2.NetworkAcl.replace_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.replace_association)

Asynchronous method. Use `await replace_association(...)` for a synchronous
call.

Arguments mapping described in
[ReplaceNetworkAclAssociationRequestNetworkAclReplaceAssociationTypeDef](./type_defs.md#replacenetworkaclassociationrequestnetworkaclreplaceassociationtypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ReplaceNetworkAclAssociationResultTypeDef](./type_defs.md#replacenetworkaclassociationresulttypedef).

<a id="networkaclreplace\_entry-method"></a>

#### NetworkAcl.replace_entry method

Replaces an entry (rule) in a network ACL.

Type annotations for `aiobotocore.resource("ec2").replace_entry` method.

Boto3 documentation:
[EC2.NetworkAcl.replace_entry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkAcl.replace_entry)

Asynchronous method. Use `await replace_entry(...)` for a synchronous call.

Arguments mapping described in
[ReplaceNetworkAclEntryRequestNetworkAclReplaceEntryTypeDef](./type_defs.md#replacenetworkaclentryrequestnetworkaclreplaceentrytypedef).

Keyword-only arguments:

- `Egress`: `bool` *(required)*
- `Protocol`: `str` *(required)*
- `RuleAction`: [RuleActionType](./literals.md#ruleactiontype) *(required)*
- `RuleNumber`: `int` *(required)*
- `CidrBlock`: `str`
- `DryRun`: `bool`
- `IcmpTypeCode`: [IcmpTypeCodeTypeDef](./type_defs.md#icmptypecodetypedef)
- `Ipv6CidrBlock`: `str`
- `PortRange`: [PortRangeTypeDef](./type_defs.md#portrangetypedef)

<a id="networkinterface"></a>

## NetworkInterface

Type annotations for `aiobotocore.resource("ec2").NetworkInterface` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import NetworkInterface

def get_resource() -> NetworkInterface:
    return boto3.resource("ec2").NetworkInterface(...)
```

Boto3 documentation:
[EC2.NetworkInterface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.NetworkInterface)

<a id="networkinterface-attributes"></a>

### NetworkInterface attributes

- `association_attribute`:
  [NetworkInterfaceAssociationResponseMetadataTypeDef](./type_defs.md#networkinterfaceassociationresponsemetadatatypedef)
- `attachment`:
  [NetworkInterfaceAttachmentResponseMetadataTypeDef](./type_defs.md#networkinterfaceattachmentresponsemetadatatypedef)
- `availability_zone`: `str`
- `description`: `str`
- `groups`:
  `List`\[[GroupIdentifierTypeDef](./type_defs.md#groupidentifiertypedef)\]
- `interface_type`:
  [NetworkInterfaceTypeType](./literals.md#networkinterfacetypetype)
- `ipv6_addresses`:
  `List`\[[NetworkInterfaceIpv6AddressTypeDef](./type_defs.md#networkinterfaceipv6addresstypedef)\]
- `mac_address`: `str`
- `network_interface_id`: `str`
- `outpost_arn`: `str`
- `owner_id`: `str`
- `private_dns_name`: `str`
- `private_ip_address`: `str`
- `private_ip_addresses`:
  `List`\[[NetworkInterfacePrivateIpAddressTypeDef](./type_defs.md#networkinterfaceprivateipaddresstypedef)\]
- `ipv4_prefixes`:
  `List`\[[Ipv4PrefixSpecificationTypeDef](./type_defs.md#ipv4prefixspecificationtypedef)\]
- `ipv6_prefixes`:
  `List`\[[Ipv6PrefixSpecificationTypeDef](./type_defs.md#ipv6prefixspecificationtypedef)\]
- `requester_id`: `str`
- `requester_managed`: `bool`
- `source_dest_check`: `bool`
- `status`:
  [NetworkInterfaceStatusType](./literals.md#networkinterfacestatustype)
- `subnet_id`: `str`
- `tag_set`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `vpc_id`: `str`
- `deny_all_igw_traffic`: `bool`
- `ipv6_native`: `bool`
- `ipv6_address`: `str`
- `id`: `str`
- `association`: [NetworkInterfaceAssociation](#networkinterfaceassociation)
- `subnet`: [Subnet](#subnet)
- `vpc`: [Vpc](#vpc)

<a id="networkinterface-methods"></a>

### NetworkInterface methods

<a id="networkinterfaceassign\_private\_ip\_addresses-method"></a>

#### NetworkInterface.assign_private_ip_addresses method

Assigns one or more secondary private IP addresses to the specified network
interface.

Type annotations for `aiobotocore.resource("ec2").assign_private_ip_addresses`
method.

Boto3 documentation:
[EC2.NetworkInterface.assign_private_ip_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.assign_private_ip_addresses)

Asynchronous method. Use `await assign_private_ip_addresses(...)` for a
synchronous call.

Arguments mapping described in
[AssignPrivateIpAddressesRequestNetworkInterfaceAssignPrivateIpAddressesTypeDef](./type_defs.md#assignprivateipaddressesrequestnetworkinterfaceassignprivateipaddressestypedef).

Keyword-only arguments:

- `AllowReassignment`: `bool`
- `PrivateIpAddresses`: `Sequence`\[`str`\]
- `SecondaryPrivateIpAddressCount`: `int`
- `Ipv4Prefixes`: `Sequence`\[`str`\]
- `Ipv4PrefixCount`: `int`

Returns a `Coroutine` for
[AssignPrivateIpAddressesResultTypeDef](./type_defs.md#assignprivateipaddressesresulttypedef).

<a id="networkinterfaceattach-method"></a>

#### NetworkInterface.attach method

Attaches a network interface to an instance.

Type annotations for `aiobotocore.resource("ec2").attach` method.

Boto3 documentation:
[EC2.NetworkInterface.attach](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.attach)

Asynchronous method. Use `await attach(...)` for a synchronous call.

Arguments mapping described in
[AttachNetworkInterfaceRequestNetworkInterfaceAttachTypeDef](./type_defs.md#attachnetworkinterfacerequestnetworkinterfaceattachtypedef).

Keyword-only arguments:

- `DeviceIndex`: `int` *(required)*
- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`
- `NetworkCardIndex`: `int`

Returns a `Coroutine` for
[AttachNetworkInterfaceResultTypeDef](./type_defs.md#attachnetworkinterfaceresulttypedef).

<a id="networkinterfacecreate\_tags-method"></a>

#### NetworkInterface.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.NetworkInterface.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestNetworkInterfaceCreateTagsTypeDef](./type_defs.md#createtagsrequestnetworkinterfacecreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="networkinterfacedelete-method"></a>

#### NetworkInterface.delete method

Deletes the specified network interface.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.NetworkInterface.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteNetworkInterfaceRequestNetworkInterfaceDeleteTypeDef](./type_defs.md#deletenetworkinterfacerequestnetworkinterfacedeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="networkinterfacedescribe\_attribute-method"></a>

#### NetworkInterface.describe_attribute method

Describes a network interface attribute.

Type annotations for `aiobotocore.resource("ec2").describe_attribute` method.

Boto3 documentation:
[EC2.NetworkInterface.describe_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.describe_attribute)

Asynchronous method. Use `await describe_attribute(...)` for a synchronous
call.

Arguments mapping described in
[DescribeNetworkInterfaceAttributeRequestNetworkInterfaceDescribeAttributeTypeDef](./type_defs.md#describenetworkinterfaceattributerequestnetworkinterfacedescribeattributetypedef).

Keyword-only arguments:

- `Attribute`:
  [NetworkInterfaceAttributeType](./literals.md#networkinterfaceattributetype)
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeNetworkInterfaceAttributeResultTypeDef](./type_defs.md#describenetworkinterfaceattributeresulttypedef).

<a id="networkinterfacedetach-method"></a>

#### NetworkInterface.detach method

Detaches a network interface from an instance.

Type annotations for `aiobotocore.resource("ec2").detach` method.

Boto3 documentation:
[EC2.NetworkInterface.detach](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.detach)

Asynchronous method. Use `await detach(...)` for a synchronous call.

Arguments mapping described in
[DetachNetworkInterfaceRequestNetworkInterfaceDetachTypeDef](./type_defs.md#detachnetworkinterfacerequestnetworkinterfacedetachtypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*
- `DryRun`: `bool`
- `Force`: `bool`

<a id="networkinterfaceget\_available\_subresources-method"></a>

#### NetworkInterface.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.NetworkInterface.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="networkinterfaceload-method"></a>

#### NetworkInterface.load method

Calls :py:meth:`EC2.Client.describe_network_interfaces` to update the
attributes of the NetworkInterface resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.NetworkInterface.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="networkinterfacemodify\_attribute-method"></a>

#### NetworkInterface.modify_attribute method

Modifies the specified network interface attribute.

Type annotations for `aiobotocore.resource("ec2").modify_attribute` method.

Boto3 documentation:
[EC2.NetworkInterface.modify_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.modify_attribute)

Asynchronous method. Use `await modify_attribute(...)` for a synchronous call.

Arguments mapping described in
[ModifyNetworkInterfaceAttributeRequestNetworkInterfaceModifyAttributeTypeDef](./type_defs.md#modifynetworkinterfaceattributerequestnetworkinterfacemodifyattributetypedef).

Keyword-only arguments:

- `Attachment`:
  [NetworkInterfaceAttachmentChangesTypeDef](./type_defs.md#networkinterfaceattachmentchangestypedef)
- `Description`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `DryRun`: `bool`
- `Groups`: `Sequence`\[`str`\]
- `SourceDestCheck`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)

<a id="networkinterfacereload-method"></a>

#### NetworkInterface.reload method

Calls :py:meth:`EC2.Client.describe_network_interfaces` to update the
attributes of the NetworkInterface resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.NetworkInterface.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="networkinterfacereset\_attribute-method"></a>

#### NetworkInterface.reset_attribute method

Resets a network interface attribute.

Type annotations for `aiobotocore.resource("ec2").reset_attribute` method.

Boto3 documentation:
[EC2.NetworkInterface.reset_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.reset_attribute)

Asynchronous method. Use `await reset_attribute(...)` for a synchronous call.

Arguments mapping described in
[ResetNetworkInterfaceAttributeRequestNetworkInterfaceResetAttributeTypeDef](./type_defs.md#resetnetworkinterfaceattributerequestnetworkinterfaceresetattributetypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `SourceDestCheck`: `str`

<a id="networkinterfaceunassign\_private\_ip\_addresses-method"></a>

#### NetworkInterface.unassign_private_ip_addresses method

Unassigns one or more secondary private IP addresses, or IPv4 Prefix Delegation
prefixes from a network interface.

Type annotations for
`aiobotocore.resource("ec2").unassign_private_ip_addresses` method.

Boto3 documentation:
[EC2.NetworkInterface.unassign_private_ip_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterface.unassign_private_ip_addresses)

Asynchronous method. Use `await unassign_private_ip_addresses(...)` for a
synchronous call.

Arguments mapping described in
[UnassignPrivateIpAddressesRequestNetworkInterfaceUnassignPrivateIpAddressesTypeDef](./type_defs.md#unassignprivateipaddressesrequestnetworkinterfaceunassignprivateipaddressestypedef).

Keyword-only arguments:

- `PrivateIpAddresses`: `Sequence`\[`str`\]
- `Ipv4Prefixes`: `Sequence`\[`str`\]

<a id="networkinterfaceassociation"></a>

## NetworkInterfaceAssociation

Type annotations for `aiobotocore.resource("ec2").NetworkInterfaceAssociation`
class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import NetworkInterfaceAssociation

def get_resource() -> NetworkInterfaceAssociation:
    return boto3.resource("ec2").NetworkInterfaceAssociation(...)
```

Boto3 documentation:
[EC2.NetworkInterfaceAssociation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.NetworkInterfaceAssociation)

<a id="networkinterfaceassociation-attributes"></a>

### NetworkInterfaceAssociation attributes

- `carrier_ip`: `str`
- `customer_owned_ip`: `str`
- `ip_owner_id`: `str`
- `public_dns_name`: `str`
- `public_ip`: `str`
- `id`: `str`
- `address`: [VpcAddress](#vpcaddress)

<a id="networkinterfaceassociation-methods"></a>

### NetworkInterfaceAssociation methods

<a id="networkinterfaceassociationdelete-method"></a>

#### NetworkInterfaceAssociation.delete method

Disassociates an Elastic IP address from the instance or network interface it's
associated with.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.NetworkInterfaceAssociation.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterfaceAssociation.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DisassociateAddressRequestNetworkInterfaceAssociationDeleteTypeDef](./type_defs.md#disassociateaddressrequestnetworkinterfaceassociationdeletetypedef).

Keyword-only arguments:

- `PublicIp`: `str`
- `DryRun`: `bool`

<a id="networkinterfaceassociationget\_available\_subresources-method"></a>

#### NetworkInterfaceAssociation.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.NetworkInterfaceAssociation.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterfaceAssociation.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="networkinterfaceassociationload-method"></a>

#### NetworkInterfaceAssociation.load method

Calls :py:meth:`EC2.Client.describe_network_interfaces` to update the
attributes of the NetworkInterfaceAssociation resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.NetworkInterfaceAssociation.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterfaceAssociation.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="networkinterfaceassociationreload-method"></a>

#### NetworkInterfaceAssociation.reload method

Calls :py:meth:`EC2.Client.describe_network_interfaces` to update the
attributes of the NetworkInterfaceAssociation resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.NetworkInterfaceAssociation.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.NetworkInterfaceAssociation.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="placementgroup"></a>

## PlacementGroup

Type annotations for `aiobotocore.resource("ec2").PlacementGroup` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import PlacementGroup

def get_resource() -> PlacementGroup:
    return boto3.resource("ec2").PlacementGroup(...)
```

Boto3 documentation:
[EC2.PlacementGroup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.PlacementGroup)

<a id="placementgroup-attributes"></a>

### PlacementGroup attributes

- `group_name`: `str`
- `state`: [PlacementGroupStateType](./literals.md#placementgroupstatetype)
- `strategy`: [PlacementStrategyType](./literals.md#placementstrategytype)
- `partition_count`: `int`
- `group_id`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `group_arn`: `str`
- `name`: `str`
- `instances`:
  [PlacementGroupInstancesCollection](#placementgroupinstancescollection)

<a id="placementgroup-collections"></a>

### PlacementGroup collections

<a id="placementgroupinstances"></a>

#### PlacementGroup.instances

Type annotations for
`aiobotocore.resource("ec2").PlacementGroup(...).instances` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import PlacementGroupInstancesCollection,

def get_collection() -> PlacementGroupInstancesCollection:
    resource = boto3.resource("ec2").PlacementGroup(...)
    return resource.instances
```

Provides access to [Instance](#instance) resource.

Boto3 documentation:
[EC2.PlacementGroup.PlacementGroupInstancesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.PlacementGroup.instances)

<a id="placementgroup-methods"></a>

### PlacementGroup methods

<a id="placementgroupdelete-method"></a>

#### PlacementGroup.delete method

Deletes the specified placement group.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.PlacementGroup.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.PlacementGroup.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeletePlacementGroupRequestPlacementGroupDeleteTypeDef](./type_defs.md#deleteplacementgrouprequestplacementgroupdeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="placementgroupget\_available\_subresources-method"></a>

#### PlacementGroup.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.PlacementGroup.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.PlacementGroup.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="placementgroupload-method"></a>

#### PlacementGroup.load method

Calls :py:meth:`EC2.Client.describe_placement_groups` to update the attributes
of the PlacementGroup resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.PlacementGroup.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.PlacementGroup.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="placementgroupreload-method"></a>

#### PlacementGroup.reload method

Calls :py:meth:`EC2.Client.describe_placement_groups` to update the attributes
of the PlacementGroup resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.PlacementGroup.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.PlacementGroup.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="route"></a>

## Route

Type annotations for `aiobotocore.resource("ec2").Route` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Route

def get_resource() -> Route:
    return boto3.resource("ec2").Route(...)
```

Boto3 documentation:
[EC2.Route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Route)

<a id="route-attributes"></a>

### Route attributes

- `destination_ipv6_cidr_block`: `str`
- `destination_prefix_list_id`: `str`
- `egress_only_internet_gateway_id`: `str`
- `gateway_id`: `str`
- `instance_id`: `str`
- `instance_owner_id`: `str`
- `nat_gateway_id`: `str`
- `transit_gateway_id`: `str`
- `local_gateway_id`: `str`
- `carrier_gateway_id`: `str`
- `network_interface_id`: `str`
- `origin`: [RouteOriginType](./literals.md#routeorigintype)
- `state`: [RouteStateType](./literals.md#routestatetype)
- `vpc_peering_connection_id`: `str`
- `core_network_arn`: `str`
- `route_table_id`: `str`
- `destination_cidr_block`: `str`

<a id="route-methods"></a>

### Route methods

<a id="routeroutetable-method"></a>

#### Route.RouteTable method

Creates a RouteTable resource.

Type annotations for `aiobotocore.resource("ec2").RouteTable` method.

Boto3 documentation:
[EC2.Route.RouteTable](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Route.RouteTable)

Asynchronous method. Use `await RouteTable(...)` for a synchronous call.

Returns a `Coroutine` for [RouteTable](#routetable).

<a id="routedelete-method"></a>

#### Route.delete method

Deletes the specified route from the specified route table.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.Route.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Route.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteRouteRequestRouteDeleteTypeDef](./type_defs.md#deleterouterequestroutedeletetypedef).

Keyword-only arguments:

- `DestinationIpv6CidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DryRun`: `bool`

<a id="routeget\_available\_subresources-method"></a>

#### Route.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Route.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Route.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="routereplace-method"></a>

#### Route.replace method

Replaces an existing route within a route table in a VPC.

Type annotations for `aiobotocore.resource("ec2").replace` method.

Boto3 documentation:
[EC2.Route.replace](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Route.replace)

Asynchronous method. Use `await replace(...)` for a synchronous call.

Arguments mapping described in
[ReplaceRouteRequestRouteReplaceTypeDef](./type_defs.md#replacerouterequestroutereplacetypedef).

Keyword-only arguments:

- `DestinationIpv6CidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DryRun`: `bool`
- `VpcEndpointId`: `str`
- `EgressOnlyInternetGatewayId`: `str`
- `GatewayId`: `str`
- `InstanceId`: `str`
- `LocalTarget`: `bool`
- `NatGatewayId`: `str`
- `TransitGatewayId`: `str`
- `LocalGatewayId`: `str`
- `CarrierGatewayId`: `str`
- `NetworkInterfaceId`: `str`
- `VpcPeeringConnectionId`: `str`
- `CoreNetworkArn`: `str`

<a id="routetable"></a>

## RouteTable

Type annotations for `aiobotocore.resource("ec2").RouteTable` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import RouteTable

def get_resource() -> RouteTable:
    return boto3.resource("ec2").RouteTable(...)
```

Boto3 documentation:
[EC2.RouteTable](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.RouteTable)

<a id="routetable-attributes"></a>

### RouteTable attributes

- `associations_attribute`:
  `List`\[[RouteTableAssociationTypeDef](./type_defs.md#routetableassociationtypedef)\]
- `propagating_vgws`:
  `List`\[[PropagatingVgwTypeDef](./type_defs.md#propagatingvgwtypedef)\]
- `route_table_id`: `str`
- `routes_attribute`: `List`\[[RouteTypeDef](./type_defs.md#routetypedef)\]
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `vpc_id`: `str`
- `owner_id`: `str`
- `id`: `str`
- `associations`: `List`\[[RouteTableAssociation](#routetableassociation)\]
- `routes`: `List`\[[Route](#route)\]
- `vpc`: [Vpc](#vpc)

<a id="routetable-methods"></a>

### RouteTable methods

<a id="routetableassociate\_with\_subnet-method"></a>

#### RouteTable.associate_with_subnet method

Associates a subnet in your VPC or an internet gateway or virtual private
gateway attached to your VPC with a route table in your VPC.

Type annotations for `aiobotocore.resource("ec2").associate_with_subnet`
method.

Boto3 documentation:
[EC2.RouteTable.associate_with_subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTable.associate_with_subnet)

Asynchronous method. Use `await associate_with_subnet(...)` for a synchronous
call.

Arguments mapping described in
[AssociateRouteTableRequestRouteTableAssociateWithSubnetTypeDef](./type_defs.md#associateroutetablerequestroutetableassociatewithsubnettypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `SubnetId`: `str`
- `GatewayId`: `str`

Returns a `Coroutine` for [RouteTableAssociation](#routetableassociation).

<a id="routetablecreate\_route-method"></a>

#### RouteTable.create_route method

Creates a route in a route table within a VPC.

Type annotations for `aiobotocore.resource("ec2").create_route` method.

Boto3 documentation:
[EC2.RouteTable.create_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTable.create_route)

Asynchronous method. Use `await create_route(...)` for a synchronous call.

Arguments mapping described in
[CreateRouteRequestRouteTableCreateRouteTypeDef](./type_defs.md#createrouterequestroutetablecreateroutetypedef).

Keyword-only arguments:

- `DestinationCidrBlock`: `str`
- `DestinationIpv6CidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DryRun`: `bool`
- `VpcEndpointId`: `str`
- `EgressOnlyInternetGatewayId`: `str`
- `GatewayId`: `str`
- `InstanceId`: `str`
- `NatGatewayId`: `str`
- `TransitGatewayId`: `str`
- `LocalGatewayId`: `str`
- `CarrierGatewayId`: `str`
- `NetworkInterfaceId`: `str`
- `VpcPeeringConnectionId`: `str`
- `CoreNetworkArn`: `str`

Returns a `Coroutine` for [Route](#route).

<a id="routetablecreate\_tags-method"></a>

#### RouteTable.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.RouteTable.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTable.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestRouteTableCreateTagsTypeDef](./type_defs.md#createtagsrequestroutetablecreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="routetabledelete-method"></a>

#### RouteTable.delete method

Deletes the specified route table.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.RouteTable.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTable.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteRouteTableRequestRouteTableDeleteTypeDef](./type_defs.md#deleteroutetablerequestroutetabledeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="routetableget\_available\_subresources-method"></a>

#### RouteTable.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.RouteTable.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTable.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="routetableload-method"></a>

#### RouteTable.load method

Calls :py:meth:`EC2.Client.describe_route_tables` to update the attributes of
the RouteTable resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.RouteTable.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTable.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="routetablereload-method"></a>

#### RouteTable.reload method

Calls :py:meth:`EC2.Client.describe_route_tables` to update the attributes of
the RouteTable resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.RouteTable.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTable.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="routetableassociation"></a>

## RouteTableAssociation

Type annotations for `aiobotocore.resource("ec2").RouteTableAssociation` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import RouteTableAssociation

def get_resource() -> RouteTableAssociation:
    return boto3.resource("ec2").RouteTableAssociation(...)
```

Boto3 documentation:
[EC2.RouteTableAssociation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.RouteTableAssociation)

<a id="routetableassociation-attributes"></a>

### RouteTableAssociation attributes

- `main`: `bool`
- `route_table_association_id`: `str`
- `route_table_id`: `str`
- `subnet_id`: `str`
- `gateway_id`: `str`
- `association_state`:
  [RouteTableAssociationStateResponseMetadataTypeDef](./type_defs.md#routetableassociationstateresponsemetadatatypedef)
- `id`: `str`
- `route_table`: [RouteTable](#routetable)
- `subnet`: [Subnet](#subnet)

<a id="routetableassociation-methods"></a>

### RouteTableAssociation methods

<a id="routetableassociationdelete-method"></a>

#### RouteTableAssociation.delete method

Disassociates a subnet or gateway from a route table.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.RouteTableAssociation.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTableAssociation.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DisassociateRouteTableRequestRouteTableAssociationDeleteTypeDef](./type_defs.md#disassociateroutetablerequestroutetableassociationdeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="routetableassociationget\_available\_subresources-method"></a>

#### RouteTableAssociation.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.RouteTableAssociation.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTableAssociation.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="routetableassociationreplace\_subnet-method"></a>

#### RouteTableAssociation.replace_subnet method

Changes the route table associated with a given subnet, internet gateway, or
virtual private gateway in a VPC.

Type annotations for `aiobotocore.resource("ec2").replace_subnet` method.

Boto3 documentation:
[EC2.RouteTableAssociation.replace_subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.RouteTableAssociation.replace_subnet)

Asynchronous method. Use `await replace_subnet(...)` for a synchronous call.

Arguments mapping described in
[ReplaceRouteTableAssociationRequestRouteTableAssociationReplaceSubnetTypeDef](./type_defs.md#replaceroutetableassociationrequestroutetableassociationreplacesubnettypedef).

Keyword-only arguments:

- `RouteTableId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [RouteTableAssociation](#routetableassociation).

<a id="securitygroup"></a>

## SecurityGroup

Type annotations for `aiobotocore.resource("ec2").SecurityGroup` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import SecurityGroup

def get_resource() -> SecurityGroup:
    return boto3.resource("ec2").SecurityGroup(...)
```

Boto3 documentation:
[EC2.SecurityGroup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.SecurityGroup)

<a id="securitygroup-attributes"></a>

### SecurityGroup attributes

- `description`: `str`
- `group_name`: `str`
- `ip_permissions`:
  `List`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `owner_id`: `str`
- `group_id`: `str`
- `ip_permissions_egress`:
  `List`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `vpc_id`: `str`
- `id`: `str`

<a id="securitygroup-methods"></a>

### SecurityGroup methods

<a id="securitygroupauthorize\_egress-method"></a>

#### SecurityGroup.authorize_egress method

Type annotations for `aiobotocore.resource("ec2").authorize_egress` method.

Boto3 documentation:
[EC2.SecurityGroup.authorize_egress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.authorize_egress)

Asynchronous method. Use `await authorize_egress(...)` for a synchronous call.

Arguments mapping described in
[AuthorizeSecurityGroupEgressRequestSecurityGroupAuthorizeEgressTypeDef](./type_defs.md#authorizesecuritygroupegressrequestsecuritygroupauthorizeegresstypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `CidrIp`: `str`
- `FromPort`: `int`
- `IpProtocol`: `str`
- `ToPort`: `int`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`

Returns a `Coroutine` for
[AuthorizeSecurityGroupEgressResultTypeDef](./type_defs.md#authorizesecuritygroupegressresulttypedef).

<a id="securitygroupauthorize\_ingress-method"></a>

#### SecurityGroup.authorize_ingress method

Adds the specified inbound (ingress) rules to a security group.

Type annotations for `aiobotocore.resource("ec2").authorize_ingress` method.

Boto3 documentation:
[EC2.SecurityGroup.authorize_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.authorize_ingress)

Asynchronous method. Use `await authorize_ingress(...)` for a synchronous call.

Arguments mapping described in
[AuthorizeSecurityGroupIngressRequestSecurityGroupAuthorizeIngressTypeDef](./type_defs.md#authorizesecuritygroupingressrequestsecuritygroupauthorizeingresstypedef).

Keyword-only arguments:

- `CidrIp`: `str`
- `FromPort`: `int`
- `GroupName`: `str`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `IpProtocol`: `str`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`
- `ToPort`: `int`
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[AuthorizeSecurityGroupIngressResultTypeDef](./type_defs.md#authorizesecuritygroupingressresulttypedef).

<a id="securitygroupcreate\_tags-method"></a>

#### SecurityGroup.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.SecurityGroup.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestSecurityGroupCreateTagsTypeDef](./type_defs.md#createtagsrequestsecuritygroupcreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="securitygroupdelete-method"></a>

#### SecurityGroup.delete method

Deletes a security group.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.SecurityGroup.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteSecurityGroupRequestSecurityGroupDeleteTypeDef](./type_defs.md#deletesecuritygrouprequestsecuritygroupdeletetypedef).

Keyword-only arguments:

- `GroupName`: `str`
- `DryRun`: `bool`

<a id="securitygroupget\_available\_subresources-method"></a>

#### SecurityGroup.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.SecurityGroup.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="securitygroupload-method"></a>

#### SecurityGroup.load method

Calls :py:meth:`EC2.Client.describe_security_groups` to update the attributes
of the SecurityGroup resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.SecurityGroup.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="securitygroupreload-method"></a>

#### SecurityGroup.reload method

Calls :py:meth:`EC2.Client.describe_security_groups` to update the attributes
of the SecurityGroup resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.SecurityGroup.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="securitygrouprevoke\_egress-method"></a>

#### SecurityGroup.revoke_egress method

Type annotations for `aiobotocore.resource("ec2").revoke_egress` method.

Boto3 documentation:
[EC2.SecurityGroup.revoke_egress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.revoke_egress)

Asynchronous method. Use `await revoke_egress(...)` for a synchronous call.

Arguments mapping described in
[RevokeSecurityGroupEgressRequestSecurityGroupRevokeEgressTypeDef](./type_defs.md#revokesecuritygroupegressrequestsecuritygrouprevokeegresstypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `SecurityGroupRuleIds`: `Sequence`\[`str`\]
- `CidrIp`: `str`
- `FromPort`: `int`
- `IpProtocol`: `str`
- `ToPort`: `int`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`

Returns a `Coroutine` for
[RevokeSecurityGroupEgressResultTypeDef](./type_defs.md#revokesecuritygroupegressresulttypedef).

<a id="securitygrouprevoke\_ingress-method"></a>

#### SecurityGroup.revoke_ingress method

Removes the specified inbound (ingress) rules from a security group.

Type annotations for `aiobotocore.resource("ec2").revoke_ingress` method.

Boto3 documentation:
[EC2.SecurityGroup.revoke_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.SecurityGroup.revoke_ingress)

Asynchronous method. Use `await revoke_ingress(...)` for a synchronous call.

Arguments mapping described in
[RevokeSecurityGroupIngressRequestSecurityGroupRevokeIngressTypeDef](./type_defs.md#revokesecuritygroupingressrequestsecuritygrouprevokeingresstypedef).

Keyword-only arguments:

- `CidrIp`: `str`
- `FromPort`: `int`
- `GroupName`: `str`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `IpProtocol`: `str`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`
- `ToPort`: `int`
- `DryRun`: `bool`
- `SecurityGroupRuleIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[RevokeSecurityGroupIngressResultTypeDef](./type_defs.md#revokesecuritygroupingressresulttypedef).

<a id="snapshot"></a>

## Snapshot

Type annotations for `aiobotocore.resource("ec2").Snapshot` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Snapshot

def get_resource() -> Snapshot:
    return boto3.resource("ec2").Snapshot(...)
```

Boto3 documentation:
[EC2.Snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Snapshot)

<a id="snapshot-attributes"></a>

### Snapshot attributes

- `data_encryption_key_id`: `str`
- `description`: `str`
- `encrypted`: `bool`
- `kms_key_id`: `str`
- `owner_id`: `str`
- `progress`: `str`
- `snapshot_id`: `str`
- `start_time`: `datetime`
- `state`: [SnapshotStateType](./literals.md#snapshotstatetype)
- `state_message`: `str`
- `volume_id`: `str`
- `volume_size`: `int`
- `owner_alias`: `str`
- `outpost_arn`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `storage_tier`: [StorageTierType](./literals.md#storagetiertype)
- `restore_expiry_time`: `datetime`
- `id`: `str`
- `volume`: [Volume](#volume)

<a id="snapshot-methods"></a>

### Snapshot methods

<a id="snapshotcopy-method"></a>

#### Snapshot.copy method

Copies a point-in-time snapshot of an EBS volume and stores it in Amazon S3.

Type annotations for `aiobotocore.resource("ec2").copy` method.

Boto3 documentation:
[EC2.Snapshot.copy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.copy)

Asynchronous method. Use `await copy(...)` for a synchronous call.

Arguments mapping described in
[CopySnapshotRequestSnapshotCopyTypeDef](./type_defs.md#copysnapshotrequestsnapshotcopytypedef).

Keyword-only arguments:

- `SourceRegion`: `str` *(required)*
- `Description`: `str`
- `DestinationOutpostArn`: `str`
- `DestinationRegion`: `str`
- `Encrypted`: `bool`
- `KmsKeyId`: `str`
- `PresignedUrl`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CopySnapshotResultTypeDef](./type_defs.md#copysnapshotresulttypedef).

<a id="snapshotcreate\_tags-method"></a>

#### Snapshot.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.Snapshot.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestSnapshotCreateTagsTypeDef](./type_defs.md#createtagsrequestsnapshotcreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="snapshotdelete-method"></a>

#### Snapshot.delete method

Deletes the specified snapshot.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.Snapshot.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteSnapshotRequestSnapshotDeleteTypeDef](./type_defs.md#deletesnapshotrequestsnapshotdeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="snapshotdescribe\_attribute-method"></a>

#### Snapshot.describe_attribute method

Describes the specified attribute of the specified snapshot.

Type annotations for `aiobotocore.resource("ec2").describe_attribute` method.

Boto3 documentation:
[EC2.Snapshot.describe_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.describe_attribute)

Asynchronous method. Use `await describe_attribute(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSnapshotAttributeRequestSnapshotDescribeAttributeTypeDef](./type_defs.md#describesnapshotattributerequestsnapshotdescribeattributetypedef).

Keyword-only arguments:

- `Attribute`:
  [SnapshotAttributeNameType](./literals.md#snapshotattributenametype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeSnapshotAttributeResultTypeDef](./type_defs.md#describesnapshotattributeresulttypedef).

<a id="snapshotget\_available\_subresources-method"></a>

#### Snapshot.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Snapshot.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="snapshotload-method"></a>

#### Snapshot.load method

Calls :py:meth:`EC2.Client.describe_snapshots` to update the attributes of the
Snapshot resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.Snapshot.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="snapshotmodify\_attribute-method"></a>

#### Snapshot.modify_attribute method

Adds or removes permission settings for the specified snapshot.

Type annotations for `aiobotocore.resource("ec2").modify_attribute` method.

Boto3 documentation:
[EC2.Snapshot.modify_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.modify_attribute)

Asynchronous method. Use `await modify_attribute(...)` for a synchronous call.

Arguments mapping described in
[ModifySnapshotAttributeRequestSnapshotModifyAttributeTypeDef](./type_defs.md#modifysnapshotattributerequestsnapshotmodifyattributetypedef).

Keyword-only arguments:

- `Attribute`:
  [SnapshotAttributeNameType](./literals.md#snapshotattributenametype)
- `CreateVolumePermission`:
  [CreateVolumePermissionModificationsTypeDef](./type_defs.md#createvolumepermissionmodificationstypedef)
- `GroupNames`: `Sequence`\[`str`\]
- `OperationType`: [OperationTypeType](./literals.md#operationtypetype)
- `UserIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

<a id="snapshotreload-method"></a>

#### Snapshot.reload method

Calls :py:meth:`EC2.Client.describe_snapshots` to update the attributes of the
Snapshot resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.Snapshot.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="snapshotreset\_attribute-method"></a>

#### Snapshot.reset_attribute method

Resets permission settings for the specified snapshot.

Type annotations for `aiobotocore.resource("ec2").reset_attribute` method.

Boto3 documentation:
[EC2.Snapshot.reset_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.reset_attribute)

Asynchronous method. Use `await reset_attribute(...)` for a synchronous call.

Arguments mapping described in
[ResetSnapshotAttributeRequestSnapshotResetAttributeTypeDef](./type_defs.md#resetsnapshotattributerequestsnapshotresetattributetypedef).

Keyword-only arguments:

- `Attribute`:
  [SnapshotAttributeNameType](./literals.md#snapshotattributenametype)
  *(required)*
- `DryRun`: `bool`

<a id="snapshotwait\_until\_completed-method"></a>

#### Snapshot.wait_until_completed method

Waits until this Snapshot is completed.

Type annotations for `aiobotocore.resource("ec2").wait_until_completed` method.

Boto3 documentation:
[EC2.Snapshot.wait_until_completed](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Snapshot.wait_until_completed)

Asynchronous method. Use `await wait_until_completed(...)` for a synchronous
call.

<a id="subnet"></a>

## Subnet

Type annotations for `aiobotocore.resource("ec2").Subnet` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Subnet

def get_resource() -> Subnet:
    return boto3.resource("ec2").Subnet(...)
```

Boto3 documentation:
[EC2.Subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Subnet)

<a id="subnet-attributes"></a>

### Subnet attributes

- `availability_zone`: `str`
- `availability_zone_id`: `str`
- `available_ip_address_count`: `int`
- `cidr_block`: `str`
- `default_for_az`: `bool`
- `enable_lni_at_device_index`: `int`
- `map_public_ip_on_launch`: `bool`
- `map_customer_owned_ip_on_launch`: `bool`
- `customer_owned_ipv4_pool`: `str`
- `state`: [SubnetStateType](./literals.md#subnetstatetype)
- `subnet_id`: `str`
- `vpc_id`: `str`
- `owner_id`: `str`
- `assign_ipv6_address_on_creation`: `bool`
- `ipv6_cidr_block_association_set`:
  `List`\[[SubnetIpv6CidrBlockAssociationTypeDef](./type_defs.md#subnetipv6cidrblockassociationtypedef)\]
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `subnet_arn`: `str`
- `outpost_arn`: `str`
- `enable_dns64`: `bool`
- `ipv6_native`: `bool`
- `private_dns_name_options_on_launch`:
  [PrivateDnsNameOptionsOnLaunchResponseMetadataTypeDef](./type_defs.md#privatednsnameoptionsonlaunchresponsemetadatatypedef)
- `id`: `str`
- `vpc`: [Vpc](#vpc)
- `instances`: [SubnetInstancesCollection](#subnetinstancescollection)
- `network_interfaces`:
  [SubnetNetworkInterfacesCollection](#subnetnetworkinterfacescollection)

<a id="subnet-collections"></a>

### Subnet collections

<a id="subnetinstances"></a>

#### Subnet.instances

Type annotations for `aiobotocore.resource("ec2").Subnet(...).instances`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import SubnetInstancesCollection,

def get_collection() -> SubnetInstancesCollection:
    resource = boto3.resource("ec2").Subnet(...)
    return resource.instances
```

Provides access to [Instance](#instance) resource.

Boto3 documentation:
[EC2.Subnet.SubnetInstancesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.instances)

<a id="subnetnetwork_interfaces"></a>

#### Subnet.network_interfaces

Type annotations for
`aiobotocore.resource("ec2").Subnet(...).network_interfaces` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import SubnetNetworkInterfacesCollection,

def get_collection() -> SubnetNetworkInterfacesCollection:
    resource = boto3.resource("ec2").Subnet(...)
    return resource.network_interfaces
```

Provides access to [NetworkInterface](#networkinterface) resource.

Boto3 documentation:
[EC2.Subnet.SubnetNetworkInterfacesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.network_interfaces)

<a id="subnet-methods"></a>

### Subnet methods

<a id="subnetcreate\_instances-method"></a>

#### Subnet.create_instances method

Launches the specified number of instances using an AMI for which you have
permissions.

Type annotations for `aiobotocore.resource("ec2").create_instances` method.

Boto3 documentation:
[EC2.Subnet.create_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.create_instances)

Asynchronous method. Use `await create_instances(...)` for a synchronous call.

Arguments mapping described in
[RunInstancesRequestSubnetCreateInstancesTypeDef](./type_defs.md#runinstancesrequestsubnetcreateinstancestypedef).

Keyword-only arguments:

- `MaxCount`: `int` *(required)*
- `MinCount`: `int` *(required)*
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `ImageId`: `str`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `Ipv6AddressCount`: `int`
- `Ipv6Addresses`:
  `Sequence`\[[InstanceIpv6AddressTypeDef](./type_defs.md#instanceipv6addresstypedef)\]
- `KernelId`: `str`
- `KeyName`: `str`
- `Monitoring`:
  [RunInstancesMonitoringEnabledTypeDef](./type_defs.md#runinstancesmonitoringenabledtypedef)
- `Placement`: [PlacementTypeDef](./type_defs.md#placementtypedef)
- `RamdiskId`: `str`
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `SecurityGroups`: `Sequence`\[`str`\]
- `UserData`: `str`
- `AdditionalInfo`: `str`
- `ClientToken`: `str`
- `DisableApiTermination`: `bool`
- `DryRun`: `bool`
- `EbsOptimized`: `bool`
- `IamInstanceProfile`:
  [IamInstanceProfileSpecificationTypeDef](./type_defs.md#iaminstanceprofilespecificationtypedef)
- `InstanceInitiatedShutdownBehavior`:
  [ShutdownBehaviorType](./literals.md#shutdownbehaviortype)
- `NetworkInterfaces`:
  `Sequence`\[[InstanceNetworkInterfaceSpecificationTypeDef](./type_defs.md#instancenetworkinterfacespecificationtypedef)\]
- `PrivateIpAddress`: `str`
- `ElasticGpuSpecification`:
  `Sequence`\[[ElasticGpuSpecificationTypeDef](./type_defs.md#elasticgpuspecificationtypedef)\]
- `ElasticInferenceAccelerators`:
  `Sequence`\[[ElasticInferenceAcceleratorTypeDef](./type_defs.md#elasticinferenceacceleratortypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `LaunchTemplate`:
  [LaunchTemplateSpecificationTypeDef](./type_defs.md#launchtemplatespecificationtypedef)
- `InstanceMarketOptions`:
  [InstanceMarketOptionsRequestTypeDef](./type_defs.md#instancemarketoptionsrequesttypedef)
- `CreditSpecification`:
  [CreditSpecificationRequestTypeDef](./type_defs.md#creditspecificationrequesttypedef)
- `CpuOptions`:
  [CpuOptionsRequestTypeDef](./type_defs.md#cpuoptionsrequesttypedef)
- `CapacityReservationSpecification`:
  [CapacityReservationSpecificationTypeDef](./type_defs.md#capacityreservationspecificationtypedef)
- `HibernationOptions`:
  [HibernationOptionsRequestTypeDef](./type_defs.md#hibernationoptionsrequesttypedef)
- `LicenseSpecifications`:
  `Sequence`\[[LicenseConfigurationRequestTypeDef](./type_defs.md#licenseconfigurationrequesttypedef)\]
- `MetadataOptions`:
  [InstanceMetadataOptionsRequestTypeDef](./type_defs.md#instancemetadataoptionsrequesttypedef)
- `EnclaveOptions`:
  [EnclaveOptionsRequestTypeDef](./type_defs.md#enclaveoptionsrequesttypedef)
- `PrivateDnsNameOptions`:
  [PrivateDnsNameOptionsRequestTypeDef](./type_defs.md#privatednsnameoptionsrequesttypedef)

Returns a `Coroutine` for `List`\[[Instance](#instance)\].

<a id="subnetcreate\_network\_interface-method"></a>

#### Subnet.create_network_interface method

Creates a network interface in the specified subnet.

Type annotations for `aiobotocore.resource("ec2").create_network_interface`
method.

Boto3 documentation:
[EC2.Subnet.create_network_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.create_network_interface)

Asynchronous method. Use `await create_network_interface(...)` for a
synchronous call.

Arguments mapping described in
[CreateNetworkInterfaceRequestSubnetCreateNetworkInterfaceTypeDef](./type_defs.md#createnetworkinterfacerequestsubnetcreatenetworkinterfacetypedef).

Keyword-only arguments:

- `Description`: `str`
- `DryRun`: `bool`
- `Groups`: `Sequence`\[`str`\]
- `Ipv6AddressCount`: `int`
- `Ipv6Addresses`:
  `Sequence`\[[InstanceIpv6AddressTypeDef](./type_defs.md#instanceipv6addresstypedef)\]
- `PrivateIpAddress`: `str`
- `PrivateIpAddresses`:
  `Sequence`\[[PrivateIpAddressSpecificationTypeDef](./type_defs.md#privateipaddressspecificationtypedef)\]
- `SecondaryPrivateIpAddressCount`: `int`
- `Ipv4Prefixes`:
  `Sequence`\[[Ipv4PrefixSpecificationRequestTypeDef](./type_defs.md#ipv4prefixspecificationrequesttypedef)\]
- `Ipv4PrefixCount`: `int`
- `Ipv6Prefixes`:
  `Sequence`\[[Ipv6PrefixSpecificationRequestTypeDef](./type_defs.md#ipv6prefixspecificationrequesttypedef)\]
- `Ipv6PrefixCount`: `int`
- `InterfaceType`:
  [NetworkInterfaceCreationTypeType](./literals.md#networkinterfacecreationtypetype)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for [NetworkInterface](#networkinterface).

<a id="subnetcreate\_tags-method"></a>

#### Subnet.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.Subnet.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestSubnetCreateTagsTypeDef](./type_defs.md#createtagsrequestsubnetcreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="subnetdelete-method"></a>

#### Subnet.delete method

Deletes the specified subnet.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.Subnet.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteSubnetRequestSubnetDeleteTypeDef](./type_defs.md#deletesubnetrequestsubnetdeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="subnetget\_available\_subresources-method"></a>

#### Subnet.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Subnet.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="subnetload-method"></a>

#### Subnet.load method

Calls :py:meth:`EC2.Client.describe_subnets` to update the attributes of the
Subnet resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.Subnet.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="subnetreload-method"></a>

#### Subnet.reload method

Calls :py:meth:`EC2.Client.describe_subnets` to update the attributes of the
Subnet resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.Subnet.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Subnet.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="tag"></a>

## Tag

Type annotations for `aiobotocore.resource("ec2").Tag` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Tag

def get_resource() -> Tag:
    return boto3.resource("ec2").Tag(...)
```

Boto3 documentation:
[EC2.Tag](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Tag)

<a id="tag-attributes"></a>

### Tag attributes

- `resource_type`: [ResourceTypeType](./literals.md#resourcetypetype)
- `resource_id`: `str`
- `key`: `str`
- `value`: `str`

<a id="tag-methods"></a>

### Tag methods

<a id="tagdelete-method"></a>

#### Tag.delete method

Deletes the specified set of tags from the specified set of resources.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.Tag.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Tag.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteTagsRequestTagDeleteTypeDef](./type_defs.md#deletetagsrequesttagdeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="tagget\_available\_subresources-method"></a>

#### Tag.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Tag.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Tag.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="tagload-method"></a>

#### Tag.load method

Calls :py:meth:`EC2.Client.describe_tags` to update the attributes of the Tag
resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.Tag.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Tag.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="tagreload-method"></a>

#### Tag.reload method

Calls :py:meth:`EC2.Client.describe_tags` to update the attributes of the Tag
resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.Tag.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Tag.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="volume"></a>

## Volume

Type annotations for `aiobotocore.resource("ec2").Volume` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Volume

def get_resource() -> Volume:
    return boto3.resource("ec2").Volume(...)
```

Boto3 documentation:
[EC2.Volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Volume)

<a id="volume-attributes"></a>

### Volume attributes

- `attachments`:
  `List`\[[VolumeAttachmentTypeDef](./type_defs.md#volumeattachmenttypedef)\]
- `availability_zone`: `str`
- `create_time`: `datetime`
- `encrypted`: `bool`
- `kms_key_id`: `str`
- `outpost_arn`: `str`
- `size`: `int`
- `snapshot_id`: `str`
- `state`: [VolumeStateType](./literals.md#volumestatetype)
- `volume_id`: `str`
- `iops`: `int`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `volume_type`: [VolumeTypeType](./literals.md#volumetypetype)
- `fast_restored`: `bool`
- `multi_attach_enabled`: `bool`
- `throughput`: `int`
- `id`: `str`
- `snapshots`: [VolumeSnapshotsCollection](#volumesnapshotscollection)

<a id="volume-collections"></a>

### Volume collections

<a id="volumesnapshots"></a>

#### Volume.snapshots

Type annotations for `aiobotocore.resource("ec2").Volume(...).snapshots`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VolumeSnapshotsCollection,

def get_collection() -> VolumeSnapshotsCollection:
    resource = boto3.resource("ec2").Volume(...)
    return resource.snapshots
```

Provides access to [Snapshot](#snapshot) resource.

Boto3 documentation:
[EC2.Volume.VolumeSnapshotsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.snapshots)

<a id="volume-methods"></a>

### Volume methods

<a id="volumeattach\_to\_instance-method"></a>

#### Volume.attach_to_instance method

Attaches an EBS volume to a running or stopped instance and exposes it to the
instance with the specified device name.

Type annotations for `aiobotocore.resource("ec2").attach_to_instance` method.

Boto3 documentation:
[EC2.Volume.attach_to_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.attach_to_instance)

Asynchronous method. Use `await attach_to_instance(...)` for a synchronous
call.

Arguments mapping described in
[AttachVolumeRequestVolumeAttachToInstanceTypeDef](./type_defs.md#attachvolumerequestvolumeattachtoinstancetypedef).

Keyword-only arguments:

- `Device`: `str` *(required)*
- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[VolumeAttachmentResponseMetadataTypeDef](./type_defs.md#volumeattachmentresponsemetadatatypedef).

<a id="volumecreate\_snapshot-method"></a>

#### Volume.create_snapshot method

Creates a snapshot of an EBS volume and stores it in Amazon S3.

Type annotations for `aiobotocore.resource("ec2").create_snapshot` method.

Boto3 documentation:
[EC2.Volume.create_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.create_snapshot)

Asynchronous method. Use `await create_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CreateSnapshotRequestVolumeCreateSnapshotTypeDef](./type_defs.md#createsnapshotrequestvolumecreatesnapshottypedef).

Keyword-only arguments:

- `Description`: `str`
- `OutpostArn`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for [Snapshot](#snapshot).

<a id="volumecreate\_tags-method"></a>

#### Volume.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.Volume.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestVolumeCreateTagsTypeDef](./type_defs.md#createtagsrequestvolumecreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="volumedelete-method"></a>

#### Volume.delete method

Deletes the specified EBS volume.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.Volume.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteVolumeRequestVolumeDeleteTypeDef](./type_defs.md#deletevolumerequestvolumedeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="volumedescribe\_attribute-method"></a>

#### Volume.describe_attribute method

Describes the specified attribute of the specified volume.

Type annotations for `aiobotocore.resource("ec2").describe_attribute` method.

Boto3 documentation:
[EC2.Volume.describe_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.describe_attribute)

Asynchronous method. Use `await describe_attribute(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVolumeAttributeRequestVolumeDescribeAttributeTypeDef](./type_defs.md#describevolumeattributerequestvolumedescribeattributetypedef).

Keyword-only arguments:

- `Attribute`: [VolumeAttributeNameType](./literals.md#volumeattributenametype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVolumeAttributeResultTypeDef](./type_defs.md#describevolumeattributeresulttypedef).

<a id="volumedescribe\_status-method"></a>

#### Volume.describe_status method

Describes the status of the specified volumes.

Type annotations for `aiobotocore.resource("ec2").describe_status` method.

Boto3 documentation:
[EC2.Volume.describe_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.describe_status)

Asynchronous method. Use `await describe_status(...)` for a synchronous call.

Arguments mapping described in
[DescribeVolumeStatusRequestVolumeDescribeStatusTypeDef](./type_defs.md#describevolumestatusrequestvolumedescribestatustypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVolumeStatusResultTypeDef](./type_defs.md#describevolumestatusresulttypedef).

<a id="volumedetach\_from\_instance-method"></a>

#### Volume.detach_from_instance method

Detaches an EBS volume from an instance.

Type annotations for `aiobotocore.resource("ec2").detach_from_instance` method.

Boto3 documentation:
[EC2.Volume.detach_from_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.detach_from_instance)

Asynchronous method. Use `await detach_from_instance(...)` for a synchronous
call.

Arguments mapping described in
[DetachVolumeRequestVolumeDetachFromInstanceTypeDef](./type_defs.md#detachvolumerequestvolumedetachfrominstancetypedef).

Keyword-only arguments:

- `Device`: `str`
- `Force`: `bool`
- `InstanceId`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[VolumeAttachmentResponseMetadataTypeDef](./type_defs.md#volumeattachmentresponsemetadatatypedef).

<a id="volumeenable\_io-method"></a>

#### Volume.enable_io method

Enables I/O operations for a volume that had I/O operations disabled because
the data on the volume was potentially inconsistent.

Type annotations for `aiobotocore.resource("ec2").enable_io` method.

Boto3 documentation:
[EC2.Volume.enable_io](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.enable_io)

Asynchronous method. Use `await enable_io(...)` for a synchronous call.

Arguments mapping described in
[EnableVolumeIORequestVolumeEnableIoTypeDef](./type_defs.md#enablevolumeiorequestvolumeenableiotypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="volumeget\_available\_subresources-method"></a>

#### Volume.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Volume.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="volumeload-method"></a>

#### Volume.load method

Calls :py:meth:`EC2.Client.describe_volumes` to update the attributes of the
Volume resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.Volume.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="volumemodify\_attribute-method"></a>

#### Volume.modify_attribute method

Modifies a volume attribute.

Type annotations for `aiobotocore.resource("ec2").modify_attribute` method.

Boto3 documentation:
[EC2.Volume.modify_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.modify_attribute)

Asynchronous method. Use `await modify_attribute(...)` for a synchronous call.

Arguments mapping described in
[ModifyVolumeAttributeRequestVolumeModifyAttributeTypeDef](./type_defs.md#modifyvolumeattributerequestvolumemodifyattributetypedef).

Keyword-only arguments:

- `AutoEnableIO`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `DryRun`: `bool`

<a id="volumereload-method"></a>

#### Volume.reload method

Calls :py:meth:`EC2.Client.describe_volumes` to update the attributes of the
Volume resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.Volume.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Volume.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="vpc"></a>

## Vpc

Type annotations for `aiobotocore.resource("ec2").Vpc` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import Vpc

def get_resource() -> Vpc:
    return boto3.resource("ec2").Vpc(...)
```

Boto3 documentation:
[EC2.Vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.Vpc)

<a id="vpc-attributes"></a>

### Vpc attributes

- `cidr_block`: `str`
- `dhcp_options_id`: `str`
- `state`: [VpcStateType](./literals.md#vpcstatetype)
- `vpc_id`: `str`
- `owner_id`: `str`
- `instance_tenancy`: [TenancyType](./literals.md#tenancytype)
- `ipv6_cidr_block_association_set`:
  `List`\[[VpcIpv6CidrBlockAssociationTypeDef](./type_defs.md#vpcipv6cidrblockassociationtypedef)\]
- `cidr_block_association_set`:
  `List`\[[VpcCidrBlockAssociationTypeDef](./type_defs.md#vpccidrblockassociationtypedef)\]
- `is_default`: `bool`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `id`: `str`
- `dhcp_options`: [DhcpOptions](#dhcpoptions)
- `accepted_vpc_peering_connections`:
  [VpcAcceptedVpcPeeringConnectionsCollection](#vpcacceptedvpcpeeringconnectionscollection)
- `instances`: [VpcInstancesCollection](#vpcinstancescollection)
- `internet_gateways`:
  [VpcInternetGatewaysCollection](#vpcinternetgatewayscollection)
- `network_acls`: [VpcNetworkAclsCollection](#vpcnetworkaclscollection)
- `network_interfaces`:
  [VpcNetworkInterfacesCollection](#vpcnetworkinterfacescollection)
- `requested_vpc_peering_connections`:
  [VpcRequestedVpcPeeringConnectionsCollection](#vpcrequestedvpcpeeringconnectionscollection)
- `route_tables`: [VpcRouteTablesCollection](#vpcroutetablescollection)
- `security_groups`:
  [VpcSecurityGroupsCollection](#vpcsecuritygroupscollection)
- `subnets`: [VpcSubnetsCollection](#vpcsubnetscollection)

<a id="vpc-collections"></a>

### Vpc collections

<a id="vpcaccepted_vpc_peering_connections"></a>

#### Vpc.accepted_vpc_peering_connections

Type annotations for
`aiobotocore.resource("ec2").Vpc(...).accepted_vpc_peering_connections`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcAcceptedVpcPeeringConnectionsCollection,

def get_collection() -> VpcAcceptedVpcPeeringConnectionsCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.accepted_vpc_peering_connections
```

Provides access to [VpcPeeringConnection](#vpcpeeringconnection) resource.

Boto3 documentation:
[EC2.Vpc.VpcAcceptedVpcPeeringConnectionsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.accepted_vpc_peering_connections)

<a id="vpcinstances"></a>

#### Vpc.instances

Type annotations for `aiobotocore.resource("ec2").Vpc(...).instances`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcInstancesCollection,

def get_collection() -> VpcInstancesCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.instances
```

Provides access to [Instance](#instance) resource.

Boto3 documentation:
[EC2.Vpc.VpcInstancesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.instances)

<a id="vpcinternet_gateways"></a>

#### Vpc.internet_gateways

Type annotations for `aiobotocore.resource("ec2").Vpc(...).internet_gateways`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcInternetGatewaysCollection,

def get_collection() -> VpcInternetGatewaysCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.internet_gateways
```

Provides access to [InternetGateway](#internetgateway) resource.

Boto3 documentation:
[EC2.Vpc.VpcInternetGatewaysCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.internet_gateways)

<a id="vpcnetwork_acls"></a>

#### Vpc.network_acls

Type annotations for `aiobotocore.resource("ec2").Vpc(...).network_acls`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcNetworkAclsCollection,

def get_collection() -> VpcNetworkAclsCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.network_acls
```

Provides access to [NetworkAcl](#networkacl) resource.

Boto3 documentation:
[EC2.Vpc.VpcNetworkAclsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.network_acls)

<a id="vpcnetwork_interfaces"></a>

#### Vpc.network_interfaces

Type annotations for `aiobotocore.resource("ec2").Vpc(...).network_interfaces`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcNetworkInterfacesCollection,

def get_collection() -> VpcNetworkInterfacesCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.network_interfaces
```

Provides access to [NetworkInterface](#networkinterface) resource.

Boto3 documentation:
[EC2.Vpc.VpcNetworkInterfacesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.network_interfaces)

<a id="vpcrequested_vpc_peering_connections"></a>

#### Vpc.requested_vpc_peering_connections

Type annotations for
`aiobotocore.resource("ec2").Vpc(...).requested_vpc_peering_connections`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcRequestedVpcPeeringConnectionsCollection,

def get_collection() -> VpcRequestedVpcPeeringConnectionsCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.requested_vpc_peering_connections
```

Provides access to [VpcPeeringConnection](#vpcpeeringconnection) resource.

Boto3 documentation:
[EC2.Vpc.VpcRequestedVpcPeeringConnectionsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.requested_vpc_peering_connections)

<a id="vpcroute_tables"></a>

#### Vpc.route_tables

Type annotations for `aiobotocore.resource("ec2").Vpc(...).route_tables`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcRouteTablesCollection,

def get_collection() -> VpcRouteTablesCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.route_tables
```

Provides access to [RouteTable](#routetable) resource.

Boto3 documentation:
[EC2.Vpc.VpcRouteTablesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.route_tables)

<a id="vpcsecurity_groups"></a>

#### Vpc.security_groups

Type annotations for `aiobotocore.resource("ec2").Vpc(...).security_groups`
collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcSecurityGroupsCollection,

def get_collection() -> VpcSecurityGroupsCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.security_groups
```

Provides access to [SecurityGroup](#securitygroup) resource.

Boto3 documentation:
[EC2.Vpc.VpcSecurityGroupsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.security_groups)

<a id="vpcsubnets"></a>

#### Vpc.subnets

Type annotations for `aiobotocore.resource("ec2").Vpc(...).subnets` collection.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcSubnetsCollection,

def get_collection() -> VpcSubnetsCollection:
    resource = boto3.resource("ec2").Vpc(...)
    return resource.subnets
```

Provides access to [Subnet](#subnet) resource.

Boto3 documentation:
[EC2.Vpc.VpcSubnetsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.subnets)

<a id="vpc-methods"></a>

### Vpc methods

<a id="vpcassociate\_dhcp\_options-method"></a>

#### Vpc.associate_dhcp_options method

Associates a set of DHCP options (that you've previously created) with the
specified VPC, or associates no DHCP options with the VPC.

Type annotations for `aiobotocore.resource("ec2").associate_dhcp_options`
method.

Boto3 documentation:
[EC2.Vpc.associate_dhcp_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.associate_dhcp_options)

Asynchronous method. Use `await associate_dhcp_options(...)` for a synchronous
call.

Arguments mapping described in
[AssociateDhcpOptionsRequestVpcAssociateDhcpOptionsTypeDef](./type_defs.md#associatedhcpoptionsrequestvpcassociatedhcpoptionstypedef).

Keyword-only arguments:

- `DhcpOptionsId`: `str` *(required)*
- `DryRun`: `bool`

<a id="vpcattach\_classic\_link\_instance-method"></a>

#### Vpc.attach_classic_link_instance method

Links an EC2-Classic instance to a ClassicLink-enabled VPC through one or more
of the VPC's security groups.

Type annotations for `aiobotocore.resource("ec2").attach_classic_link_instance`
method.

Boto3 documentation:
[EC2.Vpc.attach_classic_link_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.attach_classic_link_instance)

Asynchronous method. Use `await attach_classic_link_instance(...)` for a
synchronous call.

Arguments mapping described in
[AttachClassicLinkVpcRequestVpcAttachClassicLinkInstanceTypeDef](./type_defs.md#attachclassiclinkvpcrequestvpcattachclassiclinkinstancetypedef).

Keyword-only arguments:

- `Groups`: `Sequence`\[`str`\] *(required)*
- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AttachClassicLinkVpcResultTypeDef](./type_defs.md#attachclassiclinkvpcresulttypedef).

<a id="vpcattach\_internet\_gateway-method"></a>

#### Vpc.attach_internet_gateway method

Attaches an internet gateway or a virtual private gateway to a VPC, enabling
connectivity between the internet and the VPC.

Type annotations for `aiobotocore.resource("ec2").attach_internet_gateway`
method.

Boto3 documentation:
[EC2.Vpc.attach_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.attach_internet_gateway)

Asynchronous method. Use `await attach_internet_gateway(...)` for a synchronous
call.

Arguments mapping described in
[AttachInternetGatewayRequestVpcAttachInternetGatewayTypeDef](./type_defs.md#attachinternetgatewayrequestvpcattachinternetgatewaytypedef).

Keyword-only arguments:

- `InternetGatewayId`: `str` *(required)*
- `DryRun`: `bool`

<a id="vpccreate\_network\_acl-method"></a>

#### Vpc.create_network_acl method

Creates a network ACL in a VPC.

Type annotations for `aiobotocore.resource("ec2").create_network_acl` method.

Boto3 documentation:
[EC2.Vpc.create_network_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.create_network_acl)

Asynchronous method. Use `await create_network_acl(...)` for a synchronous
call.

Arguments mapping described in
[CreateNetworkAclRequestVpcCreateNetworkAclTypeDef](./type_defs.md#createnetworkaclrequestvpccreatenetworkacltypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [NetworkAcl](#networkacl).

<a id="vpccreate\_route\_table-method"></a>

#### Vpc.create_route_table method

Creates a route table for the specified VPC.

Type annotations for `aiobotocore.resource("ec2").create_route_table` method.

Boto3 documentation:
[EC2.Vpc.create_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.create_route_table)

Asynchronous method. Use `await create_route_table(...)` for a synchronous
call.

Arguments mapping described in
[CreateRouteTableRequestVpcCreateRouteTableTypeDef](./type_defs.md#createroutetablerequestvpccreateroutetabletypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [RouteTable](#routetable).

<a id="vpccreate\_security\_group-method"></a>

#### Vpc.create_security_group method

Creates a security group.

Type annotations for `aiobotocore.resource("ec2").create_security_group`
method.

Boto3 documentation:
[EC2.Vpc.create_security_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.create_security_group)

Asynchronous method. Use `await create_security_group(...)` for a synchronous
call.

Arguments mapping described in
[CreateSecurityGroupRequestVpcCreateSecurityGroupTypeDef](./type_defs.md#createsecuritygrouprequestvpccreatesecuritygrouptypedef).

Keyword-only arguments:

- `Description`: `str` *(required)*
- `GroupName`: `str` *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for [SecurityGroup](#securitygroup).

<a id="vpccreate\_subnet-method"></a>

#### Vpc.create_subnet method

Creates a subnet in a specified VPC.

Type annotations for `aiobotocore.resource("ec2").create_subnet` method.

Boto3 documentation:
[EC2.Vpc.create_subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.create_subnet)

Asynchronous method. Use `await create_subnet(...)` for a synchronous call.

Arguments mapping described in
[CreateSubnetRequestVpcCreateSubnetTypeDef](./type_defs.md#createsubnetrequestvpccreatesubnettypedef).

Keyword-only arguments:

- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `AvailabilityZone`: `str`
- `AvailabilityZoneId`: `str`
- `CidrBlock`: `str`
- `Ipv6CidrBlock`: `str`
- `OutpostArn`: `str`
- `DryRun`: `bool`
- `Ipv6Native`: `bool`

Returns a `Coroutine` for [Subnet](#subnet).

<a id="vpccreate\_tags-method"></a>

#### Vpc.create_tags method

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.resource("ec2").create_tags` method.

Boto3 documentation:
[EC2.Vpc.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestVpcCreateTagsTypeDef](./type_defs.md#createtagsrequestvpccreatetagstypedef).

Keyword-only arguments:

- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for [Tag](#tag).

<a id="vpcdelete-method"></a>

#### Vpc.delete method

Deletes the specified VPC.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.Vpc.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteVpcRequestVpcDeleteTypeDef](./type_defs.md#deletevpcrequestvpcdeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="vpcdescribe\_attribute-method"></a>

#### Vpc.describe_attribute method

Describes the specified attribute of the specified VPC.

Type annotations for `aiobotocore.resource("ec2").describe_attribute` method.

Boto3 documentation:
[EC2.Vpc.describe_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.describe_attribute)

Asynchronous method. Use `await describe_attribute(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVpcAttributeRequestVpcDescribeAttributeTypeDef](./type_defs.md#describevpcattributerequestvpcdescribeattributetypedef).

Keyword-only arguments:

- `Attribute`: [VpcAttributeNameType](./literals.md#vpcattributenametype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVpcAttributeResultTypeDef](./type_defs.md#describevpcattributeresulttypedef).

<a id="vpcdetach\_classic\_link\_instance-method"></a>

#### Vpc.detach_classic_link_instance method

Unlinks (detaches) a linked EC2-Classic instance from a VPC.

Type annotations for `aiobotocore.resource("ec2").detach_classic_link_instance`
method.

Boto3 documentation:
[EC2.Vpc.detach_classic_link_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.detach_classic_link_instance)

Asynchronous method. Use `await detach_classic_link_instance(...)` for a
synchronous call.

Arguments mapping described in
[DetachClassicLinkVpcRequestVpcDetachClassicLinkInstanceTypeDef](./type_defs.md#detachclassiclinkvpcrequestvpcdetachclassiclinkinstancetypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DetachClassicLinkVpcResultTypeDef](./type_defs.md#detachclassiclinkvpcresulttypedef).

<a id="vpcdetach\_internet\_gateway-method"></a>

#### Vpc.detach_internet_gateway method

Detaches an internet gateway from a VPC, disabling connectivity between the
internet and the VPC.

Type annotations for `aiobotocore.resource("ec2").detach_internet_gateway`
method.

Boto3 documentation:
[EC2.Vpc.detach_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.detach_internet_gateway)

Asynchronous method. Use `await detach_internet_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DetachInternetGatewayRequestVpcDetachInternetGatewayTypeDef](./type_defs.md#detachinternetgatewayrequestvpcdetachinternetgatewaytypedef).

Keyword-only arguments:

- `InternetGatewayId`: `str` *(required)*
- `DryRun`: `bool`

<a id="vpcdisable\_classic\_link-method"></a>

#### Vpc.disable_classic_link method

Disables ClassicLink for a VPC.

Type annotations for `aiobotocore.resource("ec2").disable_classic_link` method.

Boto3 documentation:
[EC2.Vpc.disable_classic_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.disable_classic_link)

Asynchronous method. Use `await disable_classic_link(...)` for a synchronous
call.

Arguments mapping described in
[DisableVpcClassicLinkRequestVpcDisableClassicLinkTypeDef](./type_defs.md#disablevpcclassiclinkrequestvpcdisableclassiclinktypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableVpcClassicLinkResultTypeDef](./type_defs.md#disablevpcclassiclinkresulttypedef).

<a id="vpcenable\_classic\_link-method"></a>

#### Vpc.enable_classic_link method

Enables a VPC for ClassicLink.

Type annotations for `aiobotocore.resource("ec2").enable_classic_link` method.

Boto3 documentation:
[EC2.Vpc.enable_classic_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.enable_classic_link)

Asynchronous method. Use `await enable_classic_link(...)` for a synchronous
call.

Arguments mapping described in
[EnableVpcClassicLinkRequestVpcEnableClassicLinkTypeDef](./type_defs.md#enablevpcclassiclinkrequestvpcenableclassiclinktypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableVpcClassicLinkResultTypeDef](./type_defs.md#enablevpcclassiclinkresulttypedef).

<a id="vpcget\_available\_subresources-method"></a>

#### Vpc.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.Vpc.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="vpcload-method"></a>

#### Vpc.load method

Calls :py:meth:`EC2.Client.describe_vpcs` to update the attributes of the Vpc
resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.Vpc.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="vpcmodify\_attribute-method"></a>

#### Vpc.modify_attribute method

Modifies the specified attribute of the specified VPC.

Type annotations for `aiobotocore.resource("ec2").modify_attribute` method.

Boto3 documentation:
[EC2.Vpc.modify_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.modify_attribute)

Asynchronous method. Use `await modify_attribute(...)` for a synchronous call.

Arguments mapping described in
[ModifyVpcAttributeRequestVpcModifyAttributeTypeDef](./type_defs.md#modifyvpcattributerequestvpcmodifyattributetypedef).

Keyword-only arguments:

- `EnableDnsHostnames`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `EnableDnsSupport`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)

<a id="vpcreload-method"></a>

#### Vpc.reload method

Calls :py:meth:`EC2.Client.describe_vpcs` to update the attributes of the Vpc
resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.Vpc.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="vpcrequest\_vpc\_peering\_connection-method"></a>

#### Vpc.request_vpc_peering_connection method

Requests a VPC peering connection between two VPCs: a requester VPC that you
own and an accepter VPC with which to create the connection.

Type annotations for
`aiobotocore.resource("ec2").request_vpc_peering_connection` method.

Boto3 documentation:
[EC2.Vpc.request_vpc_peering_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.request_vpc_peering_connection)

Asynchronous method. Use `await request_vpc_peering_connection(...)` for a
synchronous call.

Arguments mapping described in
[CreateVpcPeeringConnectionRequestVpcRequestVpcPeeringConnectionTypeDef](./type_defs.md#createvpcpeeringconnectionrequestvpcrequestvpcpeeringconnectiontypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `PeerOwnerId`: `str`
- `PeerVpcId`: `str`
- `PeerRegion`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [VpcPeeringConnection](#vpcpeeringconnection).

<a id="vpcwait\_until\_available-method"></a>

#### Vpc.wait_until_available method

Waits until this Vpc is available.

Type annotations for `aiobotocore.resource("ec2").wait_until_available` method.

Boto3 documentation:
[EC2.Vpc.wait_until_available](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.wait_until_available)

Asynchronous method. Use `await wait_until_available(...)` for a synchronous
call.

<a id="vpcwait\_until\_exists-method"></a>

#### Vpc.wait_until_exists method

Waits until this Vpc is exists.

Type annotations for `aiobotocore.resource("ec2").wait_until_exists` method.

Boto3 documentation:
[EC2.Vpc.wait_until_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Vpc.wait_until_exists)

Asynchronous method. Use `await wait_until_exists(...)` for a synchronous call.

<a id="vpcpeeringconnection"></a>

## VpcPeeringConnection

Type annotations for `aiobotocore.resource("ec2").VpcPeeringConnection` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcPeeringConnection

def get_resource() -> VpcPeeringConnection:
    return boto3.resource("ec2").VpcPeeringConnection(...)
```

Boto3 documentation:
[EC2.VpcPeeringConnection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.VpcPeeringConnection)

<a id="vpcpeeringconnection-attributes"></a>

### VpcPeeringConnection attributes

- `accepter_vpc_info`:
  [VpcPeeringConnectionVpcInfoResponseMetadataTypeDef](./type_defs.md#vpcpeeringconnectionvpcinforesponsemetadatatypedef)
- `expiration_time`: `datetime`
- `requester_vpc_info`:
  [VpcPeeringConnectionVpcInfoResponseMetadataTypeDef](./type_defs.md#vpcpeeringconnectionvpcinforesponsemetadatatypedef)
- `status`:
  [VpcPeeringConnectionStateReasonResponseMetadataTypeDef](./type_defs.md#vpcpeeringconnectionstatereasonresponsemetadatatypedef)
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `vpc_peering_connection_id`: `str`
- `id`: `str`
- `accepter_vpc`: [Vpc](#vpc)
- `requester_vpc`: [Vpc](#vpc)

<a id="vpcpeeringconnection-methods"></a>

### VpcPeeringConnection methods

<a id="vpcpeeringconnectionaccept-method"></a>

#### VpcPeeringConnection.accept method

Accept a VPC peering connection request.

Type annotations for `aiobotocore.resource("ec2").accept` method.

Boto3 documentation:
[EC2.VpcPeeringConnection.accept](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcPeeringConnection.accept)

Asynchronous method. Use `await accept(...)` for a synchronous call.

Arguments mapping described in
[AcceptVpcPeeringConnectionRequestVpcPeeringConnectionAcceptTypeDef](./type_defs.md#acceptvpcpeeringconnectionrequestvpcpeeringconnectionaccepttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[AcceptVpcPeeringConnectionResultTypeDef](./type_defs.md#acceptvpcpeeringconnectionresulttypedef).

<a id="vpcpeeringconnectiondelete-method"></a>

#### VpcPeeringConnection.delete method

Deletes a VPC peering connection.

Type annotations for `aiobotocore.resource("ec2").delete` method.

Boto3 documentation:
[EC2.VpcPeeringConnection.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcPeeringConnection.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteVpcPeeringConnectionRequestVpcPeeringConnectionDeleteTypeDef](./type_defs.md#deletevpcpeeringconnectionrequestvpcpeeringconnectiondeletetypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteVpcPeeringConnectionResultTypeDef](./type_defs.md#deletevpcpeeringconnectionresulttypedef).

<a id="vpcpeeringconnectionget\_available\_subresources-method"></a>

#### VpcPeeringConnection.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.VpcPeeringConnection.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcPeeringConnection.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="vpcpeeringconnectionload-method"></a>

#### VpcPeeringConnection.load method

Calls :py:meth:`EC2.Client.describe_vpc_peering_connections` to update the
attributes of the VpcPeeringConnection resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.VpcPeeringConnection.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcPeeringConnection.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="vpcpeeringconnectionreject-method"></a>

#### VpcPeeringConnection.reject method

Rejects a VPC peering connection request.

Type annotations for `aiobotocore.resource("ec2").reject` method.

Boto3 documentation:
[EC2.VpcPeeringConnection.reject](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcPeeringConnection.reject)

Asynchronous method. Use `await reject(...)` for a synchronous call.

Arguments mapping described in
[RejectVpcPeeringConnectionRequestVpcPeeringConnectionRejectTypeDef](./type_defs.md#rejectvpcpeeringconnectionrequestvpcpeeringconnectionrejecttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[RejectVpcPeeringConnectionResultTypeDef](./type_defs.md#rejectvpcpeeringconnectionresulttypedef).

<a id="vpcpeeringconnectionreload-method"></a>

#### VpcPeeringConnection.reload method

Calls :py:meth:`EC2.Client.describe_vpc_peering_connections` to update the
attributes of the VpcPeeringConnection resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.VpcPeeringConnection.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcPeeringConnection.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="vpcpeeringconnectionwait\_until\_exists-method"></a>

#### VpcPeeringConnection.wait_until_exists method

Waits until this VpcPeeringConnection is exists.

Type annotations for `aiobotocore.resource("ec2").wait_until_exists` method.

Boto3 documentation:
[EC2.VpcPeeringConnection.wait_until_exists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcPeeringConnection.wait_until_exists)

Asynchronous method. Use `await wait_until_exists(...)` for a synchronous call.

<a id="vpcaddress"></a>

## VpcAddress

Type annotations for `aiobotocore.resource("ec2").VpcAddress` class.

Can be used directly:

```python
from types_aiobotocore_ec2.service_resource import VpcAddress

def get_resource() -> VpcAddress:
    return boto3.resource("ec2").VpcAddress(...)
```

Boto3 documentation:
[EC2.VpcAddress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.ServiceResource.VpcAddress)

<a id="vpcaddress-attributes"></a>

### VpcAddress attributes

- `instance_id`: `str`
- `public_ip`: `str`
- `association_id`: `str`
- `domain`: [DomainTypeType](./literals.md#domaintypetype)
- `network_interface_id`: `str`
- `network_interface_owner_id`: `str`
- `private_ip_address`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `public_ipv4_pool`: `str`
- `network_border_group`: `str`
- `customer_owned_ip`: `str`
- `customer_owned_ipv4_pool`: `str`
- `carrier_ip`: `str`
- `allocation_id`: `str`
- `association`: [NetworkInterfaceAssociation](#networkinterfaceassociation)

<a id="vpcaddress-methods"></a>

### VpcAddress methods

<a id="vpcaddressassociate-method"></a>

#### VpcAddress.associate method

Associates an Elastic IP address, or carrier IP address (for instances that are
in subnets in Wavelength Zones) with an instance or a network interface.

Type annotations for `aiobotocore.resource("ec2").associate` method.

Boto3 documentation:
[EC2.VpcAddress.associate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcAddress.associate)

Asynchronous method. Use `await associate(...)` for a synchronous call.

Arguments mapping described in
[AssociateAddressRequestVpcAddressAssociateTypeDef](./type_defs.md#associateaddressrequestvpcaddressassociatetypedef).

Keyword-only arguments:

- `InstanceId`: `str`
- `PublicIp`: `str`
- `AllowReassociation`: `bool`
- `DryRun`: `bool`
- `NetworkInterfaceId`: `str`
- `PrivateIpAddress`: `str`

Returns a `Coroutine` for
[AssociateAddressResultTypeDef](./type_defs.md#associateaddressresulttypedef).

<a id="vpcaddressget\_available\_subresources-method"></a>

#### VpcAddress.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("ec2").get_available_subresources`
method.

Boto3 documentation:
[EC2.VpcAddress.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcAddress.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="vpcaddressload-method"></a>

#### VpcAddress.load method

Calls :py:meth:`EC2.Client.describe_addresses` to update the attributes of the
VpcAddress resource.

Type annotations for `aiobotocore.resource("ec2").load` method.

Boto3 documentation:
[EC2.VpcAddress.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcAddress.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="vpcaddressrelease-method"></a>

#### VpcAddress.release method

Releases the specified Elastic IP address.

Type annotations for `aiobotocore.resource("ec2").release` method.

Boto3 documentation:
[EC2.VpcAddress.release](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcAddress.release)

Asynchronous method. Use `await release(...)` for a synchronous call.

Arguments mapping described in
[ReleaseAddressRequestVpcAddressReleaseTypeDef](./type_defs.md#releaseaddressrequestvpcaddressreleasetypedef).

Keyword-only arguments:

- `AllocationId`: `str`
- `PublicIp`: `str`
- `NetworkBorderGroup`: `str`
- `DryRun`: `bool`

<a id="vpcaddressreload-method"></a>

#### VpcAddress.reload method

Calls :py:meth:`EC2.Client.describe_addresses` to update the attributes of the
VpcAddress resource.

Type annotations for `aiobotocore.resource("ec2").reload` method.

Boto3 documentation:
[EC2.VpcAddress.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.VpcAddress.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.
