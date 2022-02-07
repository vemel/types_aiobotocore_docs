<a id="mediaconnectclient-for-aiobotocore-mediaconnect-module"></a>

# MediaConnectClient for aiobotocore MediaConnect module

> [Index](..) > [MediaConnect](.) > MediaConnectClient

Auto-generated documentation for
[MediaConnect](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect)
type annotations stubs module
[types-aiobotocore-mediaconnect](https://pypi.org/project/types-aiobotocore-mediaconnect/).

- [MediaConnectClient for aiobotocore MediaConnect module](#mediaconnectclient-for-aiobotocore-mediaconnect-module)
  - [MediaConnectClient](#mediaconnectclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_flow_media_streams](#add_flow_media_streams)
    - [add_flow_outputs](#add_flow_outputs)
    - [add_flow_sources](#add_flow_sources)
    - [add_flow_vpc_interfaces](#add_flow_vpc_interfaces)
    - [can_paginate](#can_paginate)
    - [create_flow](#create_flow)
    - [delete_flow](#delete_flow)
    - [describe_flow](#describe_flow)
    - [describe_offering](#describe_offering)
    - [describe_reservation](#describe_reservation)
    - [generate_presigned_url](#generate_presigned_url)
    - [grant_flow_entitlements](#grant_flow_entitlements)
    - [list_entitlements](#list_entitlements)
    - [list_flows](#list_flows)
    - [list_offerings](#list_offerings)
    - [list_reservations](#list_reservations)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [purchase_offering](#purchase_offering)
    - [remove_flow_media_stream](#remove_flow_media_stream)
    - [remove_flow_output](#remove_flow_output)
    - [remove_flow_source](#remove_flow_source)
    - [remove_flow_vpc_interface](#remove_flow_vpc_interface)
    - [revoke_flow_entitlement](#revoke_flow_entitlement)
    - [start_flow](#start_flow)
    - [stop_flow](#stop_flow)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_flow](#update_flow)
    - [update_flow_entitlement](#update_flow_entitlement)
    - [update_flow_media_stream](#update_flow_media_stream)
    - [update_flow_output](#update_flow_output)
    - [update_flow_source](#update_flow_source)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="mediaconnectclient"></a>

## MediaConnectClient

Type annotations for `session.create_client("mediaconnect")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_mediaconnect.client import MediaConnectClient

session = get_session()
async with session.create_client("mediaconnect") as client:
    client: MediaConnectClient
```

Boto3 documentation:
[MediaConnect.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_mediaconnect.client import Exceptions

def handle_error(exc: Exceptions.AddFlowOutputs420Exception) -> None:
    ...
```

Exceptions:

- `Exceptions.AddFlowOutputs420Exception`
- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.CreateFlow420Exception`
- `Exceptions.ForbiddenException`
- `Exceptions.GrantFlowEntitlements420Exception`
- `Exceptions.InternalServerErrorException`
- `Exceptions.NotFoundException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.TooManyRequestsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

MediaConnectClient exceptions.

Type annotations for `session.create_client("mediaconnect").exceptions` method.

Boto3 documentation:
[MediaConnect.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add_flow_media_streams"></a>

### add_flow_media_streams

Adds media streams to an existing flow.

Type annotations for
`session.create_client("mediaconnect").add_flow_media_streams` method.

Boto3 documentation:
[MediaConnect.Client.add_flow_media_streams](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_flow_media_streams)

Asynchronous method. Use `await add_flow_media_streams(...)` for a synchronous
call.

Arguments mapping described in
[AddFlowMediaStreamsRequestRequestTypeDef](./type_defs.md#addflowmediastreamsrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `MediaStreams`:
  `Sequence`\[[AddMediaStreamRequestTypeDef](./type_defs.md#addmediastreamrequesttypedef)\]
  *(required)*

Returns a `Coroutine` for
[AddFlowMediaStreamsResponseTypeDef](./type_defs.md#addflowmediastreamsresponsetypedef).

<a id="add_flow_outputs"></a>

### add_flow_outputs

Adds outputs to an existing flow.

Type annotations for `session.create_client("mediaconnect").add_flow_outputs`
method.

Boto3 documentation:
[MediaConnect.Client.add_flow_outputs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_flow_outputs)

Asynchronous method. Use `await add_flow_outputs(...)` for a synchronous call.

Arguments mapping described in
[AddFlowOutputsRequestRequestTypeDef](./type_defs.md#addflowoutputsrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `Outputs`:
  `Sequence`\[[AddOutputRequestTypeDef](./type_defs.md#addoutputrequesttypedef)\]
  *(required)*

Returns a `Coroutine` for
[AddFlowOutputsResponseTypeDef](./type_defs.md#addflowoutputsresponsetypedef).

<a id="add_flow_sources"></a>

### add_flow_sources

Adds Sources to flow See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/AddFlowSources).

Type annotations for `session.create_client("mediaconnect").add_flow_sources`
method.

Boto3 documentation:
[MediaConnect.Client.add_flow_sources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_flow_sources)

Asynchronous method. Use `await add_flow_sources(...)` for a synchronous call.

Arguments mapping described in
[AddFlowSourcesRequestRequestTypeDef](./type_defs.md#addflowsourcesrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `Sources`:
  `Sequence`\[[SetSourceRequestTypeDef](./type_defs.md#setsourcerequesttypedef)\]
  *(required)*

Returns a `Coroutine` for
[AddFlowSourcesResponseTypeDef](./type_defs.md#addflowsourcesresponsetypedef).

<a id="add_flow_vpc_interfaces"></a>

### add_flow_vpc_interfaces

Adds VPC interfaces to flow See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/AddFlowVpcInterfaces).

Type annotations for
`session.create_client("mediaconnect").add_flow_vpc_interfaces` method.

Boto3 documentation:
[MediaConnect.Client.add_flow_vpc_interfaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_flow_vpc_interfaces)

Asynchronous method. Use `await add_flow_vpc_interfaces(...)` for a synchronous
call.

Arguments mapping described in
[AddFlowVpcInterfacesRequestRequestTypeDef](./type_defs.md#addflowvpcinterfacesrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `VpcInterfaces`:
  `Sequence`\[[VpcInterfaceRequestTypeDef](./type_defs.md#vpcinterfacerequesttypedef)\]
  *(required)*

Returns a `Coroutine` for
[AddFlowVpcInterfacesResponseTypeDef](./type_defs.md#addflowvpcinterfacesresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("mediaconnect").can_paginate`
method.

Boto3 documentation:
[MediaConnect.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_flow"></a>

### create_flow

Creates a new flow.

Type annotations for `session.create_client("mediaconnect").create_flow`
method.

Boto3 documentation:
[MediaConnect.Client.create_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.create_flow)

Asynchronous method. Use `await create_flow(...)` for a synchronous call.

Arguments mapping described in
[CreateFlowRequestRequestTypeDef](./type_defs.md#createflowrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `AvailabilityZone`: `str`
- `Entitlements`:
  `Sequence`\[[GrantEntitlementRequestTypeDef](./type_defs.md#grantentitlementrequesttypedef)\]
- `MediaStreams`:
  `Sequence`\[[AddMediaStreamRequestTypeDef](./type_defs.md#addmediastreamrequesttypedef)\]
- `Outputs`:
  `Sequence`\[[AddOutputRequestTypeDef](./type_defs.md#addoutputrequesttypedef)\]
- `Source`: [SetSourceRequestTypeDef](./type_defs.md#setsourcerequesttypedef)
- `SourceFailoverConfig`:
  [FailoverConfigTypeDef](./type_defs.md#failoverconfigtypedef)
- `Sources`:
  `Sequence`\[[SetSourceRequestTypeDef](./type_defs.md#setsourcerequesttypedef)\]
- `VpcInterfaces`:
  `Sequence`\[[VpcInterfaceRequestTypeDef](./type_defs.md#vpcinterfacerequesttypedef)\]

Returns a `Coroutine` for
[CreateFlowResponseTypeDef](./type_defs.md#createflowresponsetypedef).

<a id="delete_flow"></a>

### delete_flow

Deletes a flow.

Type annotations for `session.create_client("mediaconnect").delete_flow`
method.

Boto3 documentation:
[MediaConnect.Client.delete_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.delete_flow)

Asynchronous method. Use `await delete_flow(...)` for a synchronous call.

Arguments mapping described in
[DeleteFlowRequestRequestTypeDef](./type_defs.md#deleteflowrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*

Returns a `Coroutine` for
[DeleteFlowResponseTypeDef](./type_defs.md#deleteflowresponsetypedef).

<a id="describe_flow"></a>

### describe_flow

Displays the details of a flow.

Type annotations for `session.create_client("mediaconnect").describe_flow`
method.

Boto3 documentation:
[MediaConnect.Client.describe_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_flow)

Asynchronous method. Use `await describe_flow(...)` for a synchronous call.

Arguments mapping described in
[DescribeFlowRequestRequestTypeDef](./type_defs.md#describeflowrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeFlowResponseTypeDef](./type_defs.md#describeflowresponsetypedef).

<a id="describe_offering"></a>

### describe_offering

Displays the details of an offering.

Type annotations for `session.create_client("mediaconnect").describe_offering`
method.

Boto3 documentation:
[MediaConnect.Client.describe_offering](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_offering)

Asynchronous method. Use `await describe_offering(...)` for a synchronous call.

Arguments mapping described in
[DescribeOfferingRequestRequestTypeDef](./type_defs.md#describeofferingrequestrequesttypedef).

Keyword-only arguments:

- `OfferingArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeOfferingResponseTypeDef](./type_defs.md#describeofferingresponsetypedef).

<a id="describe_reservation"></a>

### describe_reservation

Displays the details of a reservation.

Type annotations for
`session.create_client("mediaconnect").describe_reservation` method.

Boto3 documentation:
[MediaConnect.Client.describe_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_reservation)

Asynchronous method. Use `await describe_reservation(...)` for a synchronous
call.

Arguments mapping described in
[DescribeReservationRequestRequestTypeDef](./type_defs.md#describereservationrequestrequesttypedef).

Keyword-only arguments:

- `ReservationArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeReservationResponseTypeDef](./type_defs.md#describereservationresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("mediaconnect").generate_presigned_url` method.

Boto3 documentation:
[MediaConnect.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="grant_flow_entitlements"></a>

### grant_flow_entitlements

Grants entitlements to an existing flow.

Type annotations for
`session.create_client("mediaconnect").grant_flow_entitlements` method.

Boto3 documentation:
[MediaConnect.Client.grant_flow_entitlements](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.grant_flow_entitlements)

Asynchronous method. Use `await grant_flow_entitlements(...)` for a synchronous
call.

Arguments mapping described in
[GrantFlowEntitlementsRequestRequestTypeDef](./type_defs.md#grantflowentitlementsrequestrequesttypedef).

Keyword-only arguments:

- `Entitlements`:
  `Sequence`\[[GrantEntitlementRequestTypeDef](./type_defs.md#grantentitlementrequesttypedef)\]
  *(required)*
- `FlowArn`: `str` *(required)*

Returns a `Coroutine` for
[GrantFlowEntitlementsResponseTypeDef](./type_defs.md#grantflowentitlementsresponsetypedef).

<a id="list_entitlements"></a>

### list_entitlements

Displays a list of all entitlements that have been granted to this account.

Type annotations for `session.create_client("mediaconnect").list_entitlements`
method.

Boto3 documentation:
[MediaConnect.Client.list_entitlements](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_entitlements)

Asynchronous method. Use `await list_entitlements(...)` for a synchronous call.

Arguments mapping described in
[ListEntitlementsRequestRequestTypeDef](./type_defs.md#listentitlementsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListEntitlementsResponseTypeDef](./type_defs.md#listentitlementsresponsetypedef).

<a id="list_flows"></a>

### list_flows

Displays a list of flows that are associated with this account.

Type annotations for `session.create_client("mediaconnect").list_flows` method.

Boto3 documentation:
[MediaConnect.Client.list_flows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_flows)

Asynchronous method. Use `await list_flows(...)` for a synchronous call.

Arguments mapping described in
[ListFlowsRequestRequestTypeDef](./type_defs.md#listflowsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFlowsResponseTypeDef](./type_defs.md#listflowsresponsetypedef).

<a id="list_offerings"></a>

### list_offerings

Displays a list of all offerings that are available to this account in the
current AWS Region.

Type annotations for `session.create_client("mediaconnect").list_offerings`
method.

Boto3 documentation:
[MediaConnect.Client.list_offerings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_offerings)

Asynchronous method. Use `await list_offerings(...)` for a synchronous call.

Arguments mapping described in
[ListOfferingsRequestRequestTypeDef](./type_defs.md#listofferingsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListOfferingsResponseTypeDef](./type_defs.md#listofferingsresponsetypedef).

<a id="list_reservations"></a>

### list_reservations

Displays a list of all reservations that have been purchased by this account in
the current AWS Region.

Type annotations for `session.create_client("mediaconnect").list_reservations`
method.

Boto3 documentation:
[MediaConnect.Client.list_reservations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_reservations)

Asynchronous method. Use `await list_reservations(...)` for a synchronous call.

Arguments mapping described in
[ListReservationsRequestRequestTypeDef](./type_defs.md#listreservationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListReservationsResponseTypeDef](./type_defs.md#listreservationsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

List all tags on an AWS Elemental MediaConnect resource See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/ListTagsForResource).

Type annotations for
`session.create_client("mediaconnect").list_tags_for_resource` method.

Boto3 documentation:
[MediaConnect.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="purchase_offering"></a>

### purchase_offering

Submits a request to purchase an offering.

Type annotations for `session.create_client("mediaconnect").purchase_offering`
method.

Boto3 documentation:
[MediaConnect.Client.purchase_offering](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.purchase_offering)

Asynchronous method. Use `await purchase_offering(...)` for a synchronous call.

Arguments mapping described in
[PurchaseOfferingRequestRequestTypeDef](./type_defs.md#purchaseofferingrequestrequesttypedef).

Keyword-only arguments:

- `OfferingArn`: `str` *(required)*
- `ReservationName`: `str` *(required)*
- `Start`: `str` *(required)*

Returns a `Coroutine` for
[PurchaseOfferingResponseTypeDef](./type_defs.md#purchaseofferingresponsetypedef).

<a id="remove_flow_media_stream"></a>

### remove_flow_media_stream

Removes a media stream from a flow.

Type annotations for
`session.create_client("mediaconnect").remove_flow_media_stream` method.

Boto3 documentation:
[MediaConnect.Client.remove_flow_media_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_flow_media_stream)

Asynchronous method. Use `await remove_flow_media_stream(...)` for a
synchronous call.

Arguments mapping described in
[RemoveFlowMediaStreamRequestRequestTypeDef](./type_defs.md#removeflowmediastreamrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `MediaStreamName`: `str` *(required)*

Returns a `Coroutine` for
[RemoveFlowMediaStreamResponseTypeDef](./type_defs.md#removeflowmediastreamresponsetypedef).

<a id="remove_flow_output"></a>

### remove_flow_output

Removes an output from an existing flow.

Type annotations for `session.create_client("mediaconnect").remove_flow_output`
method.

Boto3 documentation:
[MediaConnect.Client.remove_flow_output](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_flow_output)

Asynchronous method. Use `await remove_flow_output(...)` for a synchronous
call.

Arguments mapping described in
[RemoveFlowOutputRequestRequestTypeDef](./type_defs.md#removeflowoutputrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `OutputArn`: `str` *(required)*

Returns a `Coroutine` for
[RemoveFlowOutputResponseTypeDef](./type_defs.md#removeflowoutputresponsetypedef).

<a id="remove_flow_source"></a>

### remove_flow_source

Removes a source from an existing flow.

Type annotations for `session.create_client("mediaconnect").remove_flow_source`
method.

Boto3 documentation:
[MediaConnect.Client.remove_flow_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_flow_source)

Asynchronous method. Use `await remove_flow_source(...)` for a synchronous
call.

Arguments mapping described in
[RemoveFlowSourceRequestRequestTypeDef](./type_defs.md#removeflowsourcerequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `SourceArn`: `str` *(required)*

Returns a `Coroutine` for
[RemoveFlowSourceResponseTypeDef](./type_defs.md#removeflowsourceresponsetypedef).

<a id="remove_flow_vpc_interface"></a>

### remove_flow_vpc_interface

Removes a VPC Interface from an existing flow.

Type annotations for
`session.create_client("mediaconnect").remove_flow_vpc_interface` method.

Boto3 documentation:
[MediaConnect.Client.remove_flow_vpc_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_flow_vpc_interface)

Asynchronous method. Use `await remove_flow_vpc_interface(...)` for a
synchronous call.

Arguments mapping described in
[RemoveFlowVpcInterfaceRequestRequestTypeDef](./type_defs.md#removeflowvpcinterfacerequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `VpcInterfaceName`: `str` *(required)*

Returns a `Coroutine` for
[RemoveFlowVpcInterfaceResponseTypeDef](./type_defs.md#removeflowvpcinterfaceresponsetypedef).

<a id="revoke_flow_entitlement"></a>

### revoke_flow_entitlement

Revokes an entitlement from a flow.

Type annotations for
`session.create_client("mediaconnect").revoke_flow_entitlement` method.

Boto3 documentation:
[MediaConnect.Client.revoke_flow_entitlement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.revoke_flow_entitlement)

Asynchronous method. Use `await revoke_flow_entitlement(...)` for a synchronous
call.

Arguments mapping described in
[RevokeFlowEntitlementRequestRequestTypeDef](./type_defs.md#revokeflowentitlementrequestrequesttypedef).

Keyword-only arguments:

- `EntitlementArn`: `str` *(required)*
- `FlowArn`: `str` *(required)*

Returns a `Coroutine` for
[RevokeFlowEntitlementResponseTypeDef](./type_defs.md#revokeflowentitlementresponsetypedef).

<a id="start_flow"></a>

### start_flow

Starts a flow.

Type annotations for `session.create_client("mediaconnect").start_flow` method.

Boto3 documentation:
[MediaConnect.Client.start_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.start_flow)

Asynchronous method. Use `await start_flow(...)` for a synchronous call.

Arguments mapping described in
[StartFlowRequestRequestTypeDef](./type_defs.md#startflowrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*

Returns a `Coroutine` for
[StartFlowResponseTypeDef](./type_defs.md#startflowresponsetypedef).

<a id="stop_flow"></a>

### stop_flow

Stops a flow.

Type annotations for `session.create_client("mediaconnect").stop_flow` method.

Boto3 documentation:
[MediaConnect.Client.stop_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.stop_flow)

Asynchronous method. Use `await stop_flow(...)` for a synchronous call.

Arguments mapping described in
[StopFlowRequestRequestTypeDef](./type_defs.md#stopflowrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*

Returns a `Coroutine` for
[StopFlowResponseTypeDef](./type_defs.md#stopflowresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Associates the specified tags to a resource with the specified resourceArn.

Type annotations for `session.create_client("mediaconnect").tag_resource`
method.

Boto3 documentation:
[MediaConnect.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="untag_resource"></a>

### untag_resource

Deletes specified tags from a resource.

Type annotations for `session.create_client("mediaconnect").untag_resource`
method.

Boto3 documentation:
[MediaConnect.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update_flow"></a>

### update_flow

Updates flow See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/UpdateFlow).

Type annotations for `session.create_client("mediaconnect").update_flow`
method.

Boto3 documentation:
[MediaConnect.Client.update_flow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_flow)

Asynchronous method. Use `await update_flow(...)` for a synchronous call.

Arguments mapping described in
[UpdateFlowRequestRequestTypeDef](./type_defs.md#updateflowrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `SourceFailoverConfig`:
  [UpdateFailoverConfigTypeDef](./type_defs.md#updatefailoverconfigtypedef)

Returns a `Coroutine` for
[UpdateFlowResponseTypeDef](./type_defs.md#updateflowresponsetypedef).

<a id="update_flow_entitlement"></a>

### update_flow_entitlement

You can change an entitlement's description, subscribers, and encryption.

Type annotations for
`session.create_client("mediaconnect").update_flow_entitlement` method.

Boto3 documentation:
[MediaConnect.Client.update_flow_entitlement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_flow_entitlement)

Asynchronous method. Use `await update_flow_entitlement(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFlowEntitlementRequestRequestTypeDef](./type_defs.md#updateflowentitlementrequestrequesttypedef).

Keyword-only arguments:

- `EntitlementArn`: `str` *(required)*
- `FlowArn`: `str` *(required)*
- `Description`: `str`
- `Encryption`:
  [UpdateEncryptionTypeDef](./type_defs.md#updateencryptiontypedef)
- `EntitlementStatus`:
  [EntitlementStatusType](./literals.md#entitlementstatustype)
- `Subscribers`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[UpdateFlowEntitlementResponseTypeDef](./type_defs.md#updateflowentitlementresponsetypedef).

<a id="update_flow_media_stream"></a>

### update_flow_media_stream

Updates an existing media stream.

Type annotations for
`session.create_client("mediaconnect").update_flow_media_stream` method.

Boto3 documentation:
[MediaConnect.Client.update_flow_media_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_flow_media_stream)

Asynchronous method. Use `await update_flow_media_stream(...)` for a
synchronous call.

Arguments mapping described in
[UpdateFlowMediaStreamRequestRequestTypeDef](./type_defs.md#updateflowmediastreamrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `MediaStreamName`: `str` *(required)*
- `Attributes`:
  [MediaStreamAttributesRequestTypeDef](./type_defs.md#mediastreamattributesrequesttypedef)
- `ClockRate`: `int`
- `Description`: `str`
- `MediaStreamType`: [MediaStreamTypeType](./literals.md#mediastreamtypetype)
- `VideoFormat`: `str`

Returns a `Coroutine` for
[UpdateFlowMediaStreamResponseTypeDef](./type_defs.md#updateflowmediastreamresponsetypedef).

<a id="update_flow_output"></a>

### update_flow_output

Updates an existing flow output.

Type annotations for `session.create_client("mediaconnect").update_flow_output`
method.

Boto3 documentation:
[MediaConnect.Client.update_flow_output](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_flow_output)

Asynchronous method. Use `await update_flow_output(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFlowOutputRequestRequestTypeDef](./type_defs.md#updateflowoutputrequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `OutputArn`: `str` *(required)*
- `CidrAllowList`: `Sequence`\[`str`\]
- `Description`: `str`
- `Destination`: `str`
- `Encryption`:
  [UpdateEncryptionTypeDef](./type_defs.md#updateencryptiontypedef)
- `MaxLatency`: `int`
- `MediaStreamOutputConfigurations`:
  `Sequence`\[[MediaStreamOutputConfigurationRequestTypeDef](./type_defs.md#mediastreamoutputconfigurationrequesttypedef)\]
- `MinLatency`: `int`
- `Port`: `int`
- `Protocol`: [ProtocolType](./literals.md#protocoltype)
- `RemoteId`: `str`
- `SmoothingLatency`: `int`
- `StreamId`: `str`
- `VpcInterfaceAttachment`:
  [VpcInterfaceAttachmentTypeDef](./type_defs.md#vpcinterfaceattachmenttypedef)

Returns a `Coroutine` for
[UpdateFlowOutputResponseTypeDef](./type_defs.md#updateflowoutputresponsetypedef).

<a id="update_flow_source"></a>

### update_flow_source

Updates the source of a flow.

Type annotations for `session.create_client("mediaconnect").update_flow_source`
method.

Boto3 documentation:
[MediaConnect.Client.update_flow_source](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_flow_source)

Asynchronous method. Use `await update_flow_source(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFlowSourceRequestRequestTypeDef](./type_defs.md#updateflowsourcerequestrequesttypedef).

Keyword-only arguments:

- `FlowArn`: `str` *(required)*
- `SourceArn`: `str` *(required)*
- `Decryption`:
  [UpdateEncryptionTypeDef](./type_defs.md#updateencryptiontypedef)
- `Description`: `str`
- `EntitlementArn`: `str`
- `IngestPort`: `int`
- `MaxBitrate`: `int`
- `MaxLatency`: `int`
- `MaxSyncBuffer`: `int`
- `MediaStreamSourceConfigurations`:
  `Sequence`\[[MediaStreamSourceConfigurationRequestTypeDef](./type_defs.md#mediastreamsourceconfigurationrequesttypedef)\]
- `MinLatency`: `int`
- `Protocol`: [ProtocolType](./literals.md#protocoltype)
- `StreamId`: `str`
- `VpcInterfaceName`: `str`
- `WhitelistCidr`: `str`

Returns a `Coroutine` for
[UpdateFlowSourceResponseTypeDef](./type_defs.md#updateflowsourceresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("mediaconnect").__aenter__` method.

Boto3 documentation:
[MediaConnect.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [MediaConnectClient](#mediaconnectclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("mediaconnect").__aexit__` method.

Boto3 documentation:
[MediaConnect.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("mediaconnect").get_paginator`
method with overloads.

- `client.get_paginator("list_entitlements")` ->
  [ListEntitlementsPaginator](./paginators.md#listentitlementspaginator)
- `client.get_paginator("list_flows")` ->
  [ListFlowsPaginator](./paginators.md#listflowspaginator)
- `client.get_paginator("list_offerings")` ->
  [ListOfferingsPaginator](./paginators.md#listofferingspaginator)
- `client.get_paginator("list_reservations")` ->
  [ListReservationsPaginator](./paginators.md#listreservationspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("mediaconnect").get_waiter` method
with overloads.

- `client.get_waiter("flow_active")` ->
  [FlowActiveWaiter](./waiters.md#flowactivewaiter)
- `client.get_waiter("flow_deleted")` ->
  [FlowDeletedWaiter](./waiters.md#flowdeletedwaiter)
- `client.get_waiter("flow_standby")` ->
  [FlowStandbyWaiter](./waiters.md#flowstandbywaiter)
