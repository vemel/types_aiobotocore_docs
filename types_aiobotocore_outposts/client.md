<a id="outpostsclient-for-aiobotocore-outposts-module"></a>

# OutpostsClient for aiobotocore Outposts module

> [Index](..) > [Outposts](.) > OutpostsClient

Auto-generated documentation for
[Outposts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts)
type annotations stubs module
[types-aiobotocore-outposts](https://pypi.org/project/types-aiobotocore-outposts/).

- [OutpostsClient for aiobotocore Outposts module](#outpostsclient-for-aiobotocore-outposts-module)
  - [OutpostsClient](#outpostsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [cancel_order](#cancel_order)
    - [create_order](#create_order)
    - [create_outpost](#create_outpost)
    - [create_site](#create_site)
    - [delete_outpost](#delete_outpost)
    - [delete_site](#delete_site)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_catalog_item](#get_catalog_item)
    - [get_order](#get_order)
    - [get_outpost](#get_outpost)
    - [get_outpost_instance_types](#get_outpost_instance_types)
    - [get_site](#get_site)
    - [get_site_address](#get_site_address)
    - [list_catalog_items](#list_catalog_items)
    - [list_orders](#list_orders)
    - [list_outposts](#list_outposts)
    - [list_sites](#list_sites)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_outpost](#update_outpost)
    - [update_site](#update_site)
    - [update_site_address](#update_site_address)
    - [update_site_rack_physical_properties](#update_site_rack_physical_properties)

<a id="outpostsclient"></a>

## OutpostsClient

Type annotations for `aiobotocore.create_client("outposts")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_outposts.client import OutpostsClient

def get_outposts_client() -> OutpostsClient:
    return Session().client("outposts")
```

Boto3 documentation:
[Outposts.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_outposts.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.NotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

OutpostsClient exceptions.

Type annotations for `aiobotocore.create_client("outposts").exceptions` method.

Boto3 documentation:
[Outposts.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("outposts").can_paginate`
method.

Boto3 documentation:
[Outposts.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_order"></a>

### cancel_order

Cancels an order for an Outpost.

Type annotations for `aiobotocore.create_client("outposts").cancel_order`
method.

Boto3 documentation:
[Outposts.Client.cancel_order](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.cancel_order)

Asynchronous method. Use `await cancel_order(...)` for a synchronous call.

Arguments mapping described in
[CancelOrderInputRequestTypeDef](./type_defs.md#cancelorderinputrequesttypedef).

Keyword-only arguments:

- `OrderId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_order"></a>

### create_order

Creates an order for an Outpost.

Type annotations for `aiobotocore.create_client("outposts").create_order`
method.

Boto3 documentation:
[Outposts.Client.create_order](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.create_order)

Asynchronous method. Use `await create_order(...)` for a synchronous call.

Arguments mapping described in
[CreateOrderInputRequestTypeDef](./type_defs.md#createorderinputrequesttypedef).

Keyword-only arguments:

- `OutpostIdentifier`: `str` *(required)*
- `LineItems`:
  `Sequence`\[[LineItemRequestTypeDef](./type_defs.md#lineitemrequesttypedef)\]
  *(required)*
- `PaymentOption`: [PaymentOptionType](./literals.md#paymentoptiontype)
  *(required)*
- `PaymentTerm`: `Literal['THREE_YEARS']` (see
  [PaymentTermType](./literals.md#paymenttermtype))

Returns a `Coroutine` for
[CreateOrderOutputTypeDef](./type_defs.md#createorderoutputtypedef).

<a id="create_outpost"></a>

### create_outpost

Creates an Outpost.

Type annotations for `aiobotocore.create_client("outposts").create_outpost`
method.

Boto3 documentation:
[Outposts.Client.create_outpost](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.create_outpost)

Asynchronous method. Use `await create_outpost(...)` for a synchronous call.

Arguments mapping described in
[CreateOutpostInputRequestTypeDef](./type_defs.md#createoutpostinputrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `SiteId`: `str` *(required)*
- `Description`: `str`
- `AvailabilityZone`: `str`
- `AvailabilityZoneId`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `SupportedHardwareType`:
  [SupportedHardwareTypeType](./literals.md#supportedhardwaretypetype)

Returns a `Coroutine` for
[CreateOutpostOutputTypeDef](./type_defs.md#createoutpostoutputtypedef).

<a id="create_site"></a>

### create_site

Creates a site for an Outpost.

Type annotations for `aiobotocore.create_client("outposts").create_site`
method.

Boto3 documentation:
[Outposts.Client.create_site](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.create_site)

Asynchronous method. Use `await create_site(...)` for a synchronous call.

Arguments mapping described in
[CreateSiteInputRequestTypeDef](./type_defs.md#createsiteinputrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Description`: `str`
- `Notes`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]
- `OperatingAddress`: [AddressTypeDef](./type_defs.md#addresstypedef)
- `ShippingAddress`: [AddressTypeDef](./type_defs.md#addresstypedef)
- `RackPhysicalProperties`:
  [RackPhysicalPropertiesTypeDef](./type_defs.md#rackphysicalpropertiestypedef)

Returns a `Coroutine` for
[CreateSiteOutputTypeDef](./type_defs.md#createsiteoutputtypedef).

<a id="delete_outpost"></a>

### delete_outpost

Deletes the Outpost.

Type annotations for `aiobotocore.create_client("outposts").delete_outpost`
method.

Boto3 documentation:
[Outposts.Client.delete_outpost](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.delete_outpost)

Asynchronous method. Use `await delete_outpost(...)` for a synchronous call.

Arguments mapping described in
[DeleteOutpostInputRequestTypeDef](./type_defs.md#deleteoutpostinputrequesttypedef).

Keyword-only arguments:

- `OutpostId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_site"></a>

### delete_site

Deletes the site.

Type annotations for `aiobotocore.create_client("outposts").delete_site`
method.

Boto3 documentation:
[Outposts.Client.delete_site](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.delete_site)

Asynchronous method. Use `await delete_site(...)` for a synchronous call.

Arguments mapping described in
[DeleteSiteInputRequestTypeDef](./type_defs.md#deletesiteinputrequesttypedef).

Keyword-only arguments:

- `SiteId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("outposts").generate_presigned_url` method.

Boto3 documentation:
[Outposts.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_catalog_item"></a>

### get_catalog_item

Gets information about a catalog item.

Type annotations for `aiobotocore.create_client("outposts").get_catalog_item`
method.

Boto3 documentation:
[Outposts.Client.get_catalog_item](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.get_catalog_item)

Asynchronous method. Use `await get_catalog_item(...)` for a synchronous call.

Arguments mapping described in
[GetCatalogItemInputRequestTypeDef](./type_defs.md#getcatalogiteminputrequesttypedef).

Keyword-only arguments:

- `CatalogItemId`: `str` *(required)*

Returns a `Coroutine` for
[GetCatalogItemOutputTypeDef](./type_defs.md#getcatalogitemoutputtypedef).

<a id="get_order"></a>

### get_order

Gets an order.

Type annotations for `aiobotocore.create_client("outposts").get_order` method.

Boto3 documentation:
[Outposts.Client.get_order](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.get_order)

Asynchronous method. Use `await get_order(...)` for a synchronous call.

Arguments mapping described in
[GetOrderInputRequestTypeDef](./type_defs.md#getorderinputrequesttypedef).

Keyword-only arguments:

- `OrderId`: `str` *(required)*

Returns a `Coroutine` for
[GetOrderOutputTypeDef](./type_defs.md#getorderoutputtypedef).

<a id="get_outpost"></a>

### get_outpost

Gets information about the specified Outpost.

Type annotations for `aiobotocore.create_client("outposts").get_outpost`
method.

Boto3 documentation:
[Outposts.Client.get_outpost](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.get_outpost)

Asynchronous method. Use `await get_outpost(...)` for a synchronous call.

Arguments mapping described in
[GetOutpostInputRequestTypeDef](./type_defs.md#getoutpostinputrequesttypedef).

Keyword-only arguments:

- `OutpostId`: `str` *(required)*

Returns a `Coroutine` for
[GetOutpostOutputTypeDef](./type_defs.md#getoutpostoutputtypedef).

<a id="get_outpost_instance_types"></a>

### get_outpost_instance_types

Lists the instance types for the specified Outpost.

Type annotations for
`aiobotocore.create_client("outposts").get_outpost_instance_types` method.

Boto3 documentation:
[Outposts.Client.get_outpost_instance_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.get_outpost_instance_types)

Asynchronous method. Use `await get_outpost_instance_types(...)` for a
synchronous call.

Arguments mapping described in
[GetOutpostInstanceTypesInputRequestTypeDef](./type_defs.md#getoutpostinstancetypesinputrequesttypedef).

Keyword-only arguments:

- `OutpostId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetOutpostInstanceTypesOutputTypeDef](./type_defs.md#getoutpostinstancetypesoutputtypedef).

<a id="get_site"></a>

### get_site

Gets information about the specified Outpost site.

Type annotations for `aiobotocore.create_client("outposts").get_site` method.

Boto3 documentation:
[Outposts.Client.get_site](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.get_site)

Asynchronous method. Use `await get_site(...)` for a synchronous call.

Arguments mapping described in
[GetSiteInputRequestTypeDef](./type_defs.md#getsiteinputrequesttypedef).

Keyword-only arguments:

- `SiteId`: `str` *(required)*

Returns a `Coroutine` for
[GetSiteOutputTypeDef](./type_defs.md#getsiteoutputtypedef).

<a id="get_site_address"></a>

### get_site_address

Gets the site address.

Type annotations for `aiobotocore.create_client("outposts").get_site_address`
method.

Boto3 documentation:
[Outposts.Client.get_site_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.get_site_address)

Asynchronous method. Use `await get_site_address(...)` for a synchronous call.

Arguments mapping described in
[GetSiteAddressInputRequestTypeDef](./type_defs.md#getsiteaddressinputrequesttypedef).

Keyword-only arguments:

- `SiteId`: `str` *(required)*
- `AddressType`: [AddressTypeType](./literals.md#addresstypetype) *(required)*

Returns a `Coroutine` for
[GetSiteAddressOutputTypeDef](./type_defs.md#getsiteaddressoutputtypedef).

<a id="list_catalog_items"></a>

### list_catalog_items

Use to create a list of every item in the catalog.

Type annotations for `aiobotocore.create_client("outposts").list_catalog_items`
method.

Boto3 documentation:
[Outposts.Client.list_catalog_items](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.list_catalog_items)

Asynchronous method. Use `await list_catalog_items(...)` for a synchronous
call.

Arguments mapping described in
[ListCatalogItemsInputRequestTypeDef](./type_defs.md#listcatalogitemsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `ItemClassFilter`:
  `Sequence`\[[CatalogItemClassType](./literals.md#catalogitemclasstype)\]
- `SupportedStorageFilter`:
  `Sequence`\[[SupportedStorageEnumType](./literals.md#supportedstorageenumtype)\]
- `EC2FamilyFilter`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ListCatalogItemsOutputTypeDef](./type_defs.md#listcatalogitemsoutputtypedef).

<a id="list_orders"></a>

### list_orders

Create a list of the Outpost orders for your Amazon Web Services account.

Type annotations for `aiobotocore.create_client("outposts").list_orders`
method.

Boto3 documentation:
[Outposts.Client.list_orders](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.list_orders)

Asynchronous method. Use `await list_orders(...)` for a synchronous call.

Arguments mapping described in
[ListOrdersInputRequestTypeDef](./type_defs.md#listordersinputrequesttypedef).

Keyword-only arguments:

- `OutpostIdentifierFilter`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListOrdersOutputTypeDef](./type_defs.md#listordersoutputtypedef).

<a id="list_outposts"></a>

### list_outposts

Create a list of the Outposts for your Amazon Web Services account.

Type annotations for `aiobotocore.create_client("outposts").list_outposts`
method.

Boto3 documentation:
[Outposts.Client.list_outposts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.list_outposts)

Asynchronous method. Use `await list_outposts(...)` for a synchronous call.

Arguments mapping described in
[ListOutpostsInputRequestTypeDef](./type_defs.md#listoutpostsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `LifeCycleStatusFilter`: `Sequence`\[`str`\]
- `AvailabilityZoneFilter`: `Sequence`\[`str`\]
- `AvailabilityZoneIdFilter`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ListOutpostsOutputTypeDef](./type_defs.md#listoutpostsoutputtypedef).

<a id="list_sites"></a>

### list_sites

Lists the sites for your Amazon Web Services account.

Type annotations for `aiobotocore.create_client("outposts").list_sites` method.

Boto3 documentation:
[Outposts.Client.list_sites](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.list_sites)

Asynchronous method. Use `await list_sites(...)` for a synchronous call.

Arguments mapping described in
[ListSitesInputRequestTypeDef](./type_defs.md#listsitesinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListSitesOutputTypeDef](./type_defs.md#listsitesoutputtypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags for the specified resource.

Type annotations for
`aiobotocore.create_client("outposts").list_tags_for_resource` method.

Boto3 documentation:
[Outposts.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds tags to the specified resource.

Type annotations for `aiobotocore.create_client("outposts").tag_resource`
method.

Boto3 documentation:
[Outposts.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from the specified resource.

Type annotations for `aiobotocore.create_client("outposts").untag_resource`
method.

Boto3 documentation:
[Outposts.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_outpost"></a>

### update_outpost

Updates an Outpost.

Type annotations for `aiobotocore.create_client("outposts").update_outpost`
method.

Boto3 documentation:
[Outposts.Client.update_outpost](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.update_outpost)

Asynchronous method. Use `await update_outpost(...)` for a synchronous call.

Arguments mapping described in
[UpdateOutpostInputRequestTypeDef](./type_defs.md#updateoutpostinputrequesttypedef).

Keyword-only arguments:

- `OutpostId`: `str` *(required)*
- `Name`: `str`
- `Description`: `str`
- `SupportedHardwareType`:
  [SupportedHardwareTypeType](./literals.md#supportedhardwaretypetype)

Returns a `Coroutine` for
[UpdateOutpostOutputTypeDef](./type_defs.md#updateoutpostoutputtypedef).

<a id="update_site"></a>

### update_site

Updates the site.

Type annotations for `aiobotocore.create_client("outposts").update_site`
method.

Boto3 documentation:
[Outposts.Client.update_site](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.update_site)

Asynchronous method. Use `await update_site(...)` for a synchronous call.

Arguments mapping described in
[UpdateSiteInputRequestTypeDef](./type_defs.md#updatesiteinputrequesttypedef).

Keyword-only arguments:

- `SiteId`: `str` *(required)*
- `Name`: `str`
- `Description`: `str`
- `Notes`: `str`

Returns a `Coroutine` for
[UpdateSiteOutputTypeDef](./type_defs.md#updatesiteoutputtypedef).

<a id="update_site_address"></a>

### update_site_address

Updates the site address.

Type annotations for
`aiobotocore.create_client("outposts").update_site_address` method.

Boto3 documentation:
[Outposts.Client.update_site_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.update_site_address)

Asynchronous method. Use `await update_site_address(...)` for a synchronous
call.

Arguments mapping described in
[UpdateSiteAddressInputRequestTypeDef](./type_defs.md#updatesiteaddressinputrequesttypedef).

Keyword-only arguments:

- `SiteId`: `str` *(required)*
- `AddressType`: [AddressTypeType](./literals.md#addresstypetype) *(required)*
- `Address`: [AddressTypeDef](./type_defs.md#addresstypedef) *(required)*

Returns a `Coroutine` for
[UpdateSiteAddressOutputTypeDef](./type_defs.md#updatesiteaddressoutputtypedef).

<a id="update_site_rack_physical_properties"></a>

### update_site_rack_physical_properties

Update the physical and logistical details for a rack at a site.

Type annotations for
`aiobotocore.create_client("outposts").update_site_rack_physical_properties`
method.

Boto3 documentation:
[Outposts.Client.update_site_rack_physical_properties](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts.Client.update_site_rack_physical_properties)

Asynchronous method. Use `await update_site_rack_physical_properties(...)` for
a synchronous call.

Arguments mapping described in
[UpdateSiteRackPhysicalPropertiesInputRequestTypeDef](./type_defs.md#updatesiterackphysicalpropertiesinputrequesttypedef).

Keyword-only arguments:

- `SiteId`: `str` *(required)*
- `PowerDrawKva`: [PowerDrawKvaType](./literals.md#powerdrawkvatype)
- `PowerPhase`: [PowerPhaseType](./literals.md#powerphasetype)
- `PowerConnector`: [PowerConnectorType](./literals.md#powerconnectortype)
- `PowerFeedDrop`: [PowerFeedDropType](./literals.md#powerfeeddroptype)
- `UplinkGbps`: [UplinkGbpsType](./literals.md#uplinkgbpstype)
- `UplinkCount`: [UplinkCountType](./literals.md#uplinkcounttype)
- `FiberOpticCableType`:
  [FiberOpticCableTypeType](./literals.md#fiberopticcabletypetype)
- `OpticalStandard`: [OpticalStandardType](./literals.md#opticalstandardtype)
- `MaximumSupportedWeightLbs`:
  [MaximumSupportedWeightLbsType](./literals.md#maximumsupportedweightlbstype)

Returns a `Coroutine` for
[UpdateSiteRackPhysicalPropertiesOutputTypeDef](./type_defs.md#updatesiterackphysicalpropertiesoutputtypedef).
