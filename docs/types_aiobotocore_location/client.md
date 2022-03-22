<a id="locationserviceclient-for-aiobotocore-locationservice-module"></a>

# LocationServiceClient for aiobotocore LocationService module

> [Index](../README.md) > [LocationService](./README.md) >
> LocationServiceClient

Auto-generated documentation for
[LocationService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService)
type annotations stubs module
[types-aiobotocore-location](https://pypi.org/project/types-aiobotocore-location/).

- [LocationServiceClient for aiobotocore LocationService module](#locationserviceclient-for-aiobotocore-locationservice-module)
  - [LocationServiceClient](#locationserviceclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_tracker_consumer](#associate_tracker_consumer)
    - [batch_delete_device_position_history](#batch_delete_device_position_history)
    - [batch_delete_geofence](#batch_delete_geofence)
    - [batch_evaluate_geofences](#batch_evaluate_geofences)
    - [batch_get_device_position](#batch_get_device_position)
    - [batch_put_geofence](#batch_put_geofence)
    - [batch_update_device_position](#batch_update_device_position)
    - [calculate_route](#calculate_route)
    - [calculate_route_matrix](#calculate_route_matrix)
    - [can_paginate](#can_paginate)
    - [create_geofence_collection](#create_geofence_collection)
    - [create_map](#create_map)
    - [create_place_index](#create_place_index)
    - [create_route_calculator](#create_route_calculator)
    - [create_tracker](#create_tracker)
    - [delete_geofence_collection](#delete_geofence_collection)
    - [delete_map](#delete_map)
    - [delete_place_index](#delete_place_index)
    - [delete_route_calculator](#delete_route_calculator)
    - [delete_tracker](#delete_tracker)
    - [describe_geofence_collection](#describe_geofence_collection)
    - [describe_map](#describe_map)
    - [describe_place_index](#describe_place_index)
    - [describe_route_calculator](#describe_route_calculator)
    - [describe_tracker](#describe_tracker)
    - [disassociate_tracker_consumer](#disassociate_tracker_consumer)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_device_position](#get_device_position)
    - [get_device_position_history](#get_device_position_history)
    - [get_geofence](#get_geofence)
    - [get_map_glyphs](#get_map_glyphs)
    - [get_map_sprites](#get_map_sprites)
    - [get_map_style_descriptor](#get_map_style_descriptor)
    - [get_map_tile](#get_map_tile)
    - [list_device_positions](#list_device_positions)
    - [list_geofence_collections](#list_geofence_collections)
    - [list_geofences](#list_geofences)
    - [list_maps](#list_maps)
    - [list_place_indexes](#list_place_indexes)
    - [list_route_calculators](#list_route_calculators)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_tracker_consumers](#list_tracker_consumers)
    - [list_trackers](#list_trackers)
    - [put_geofence](#put_geofence)
    - [search_place_index_for_position](#search_place_index_for_position)
    - [search_place_index_for_suggestions](#search_place_index_for_suggestions)
    - [search_place_index_for_text](#search_place_index_for_text)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_geofence_collection](#update_geofence_collection)
    - [update_map](#update_map)
    - [update_place_index](#update_place_index)
    - [update_route_calculator](#update_route_calculator)
    - [update_tracker](#update_tracker)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="locationserviceclient"></a>

## LocationServiceClient

Type annotations for `session.create_client("location")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_location.client import LocationServiceClient

session = get_session()
async with session.create_client("location") as client:
    client: LocationServiceClient
```

Boto3 documentation:
[LocationService.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_location.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

LocationServiceClient exceptions.

Type annotations for `session.create_client("location").exceptions` method.

Boto3 documentation:
[LocationService.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate\_tracker\_consumer"></a>

### associate_tracker_consumer

Creates an association between a geofence collection and a tracker resource.

Type annotations for
`session.create_client("location").associate_tracker_consumer` method.

Boto3 documentation:
[LocationService.Client.associate_tracker_consumer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.associate_tracker_consumer)

Asynchronous method. Use `await associate_tracker_consumer(...)` for a
synchronous call.

Arguments mapping described in
[AssociateTrackerConsumerRequestRequestTypeDef](./type_defs.md#associatetrackerconsumerrequestrequesttypedef).

Keyword-only arguments:

- `ConsumerArn`: `str` *(required)*
- `TrackerName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="batch\_delete\_device\_position\_history"></a>

### batch_delete_device_position_history

Deletes the position history of one or more devices from a tracker resource.

Type annotations for
`session.create_client("location").batch_delete_device_position_history`
method.

Boto3 documentation:
[LocationService.Client.batch_delete_device_position_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_delete_device_position_history)

Asynchronous method. Use `await batch_delete_device_position_history(...)` for
a synchronous call.

Arguments mapping described in
[BatchDeleteDevicePositionHistoryRequestRequestTypeDef](./type_defs.md#batchdeletedevicepositionhistoryrequestrequesttypedef).

Keyword-only arguments:

- `DeviceIds`: `Sequence`\[`str`\] *(required)*
- `TrackerName`: `str` *(required)*

Returns a `Coroutine` for
[BatchDeleteDevicePositionHistoryResponseTypeDef](./type_defs.md#batchdeletedevicepositionhistoryresponsetypedef).

<a id="batch\_delete\_geofence"></a>

### batch_delete_geofence

Deletes a batch of geofences from a geofence collection.

Type annotations for `session.create_client("location").batch_delete_geofence`
method.

Boto3 documentation:
[LocationService.Client.batch_delete_geofence](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_delete_geofence)

Asynchronous method. Use `await batch_delete_geofence(...)` for a synchronous
call.

Arguments mapping described in
[BatchDeleteGeofenceRequestRequestTypeDef](./type_defs.md#batchdeletegeofencerequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `GeofenceIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchDeleteGeofenceResponseTypeDef](./type_defs.md#batchdeletegeofenceresponsetypedef).

<a id="batch\_evaluate\_geofences"></a>

### batch_evaluate_geofences

Evaluates device positions against the geofence geometries from a given
geofence collection.

Type annotations for
`session.create_client("location").batch_evaluate_geofences` method.

Boto3 documentation:
[LocationService.Client.batch_evaluate_geofences](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_evaluate_geofences)

Asynchronous method. Use `await batch_evaluate_geofences(...)` for a
synchronous call.

Arguments mapping described in
[BatchEvaluateGeofencesRequestRequestTypeDef](./type_defs.md#batchevaluategeofencesrequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `DevicePositionUpdates`:
  `Sequence`\[[DevicePositionUpdateTypeDef](./type_defs.md#devicepositionupdatetypedef)\]
  *(required)*

Returns a `Coroutine` for
[BatchEvaluateGeofencesResponseTypeDef](./type_defs.md#batchevaluategeofencesresponsetypedef).

<a id="batch\_get\_device\_position"></a>

### batch_get_device_position

Lists the latest device positions for requested devices.

Type annotations for
`session.create_client("location").batch_get_device_position` method.

Boto3 documentation:
[LocationService.Client.batch_get_device_position](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_get_device_position)

Asynchronous method. Use `await batch_get_device_position(...)` for a
synchronous call.

Arguments mapping described in
[BatchGetDevicePositionRequestRequestTypeDef](./type_defs.md#batchgetdevicepositionrequestrequesttypedef).

Keyword-only arguments:

- `DeviceIds`: `Sequence`\[`str`\] *(required)*
- `TrackerName`: `str` *(required)*

Returns a `Coroutine` for
[BatchGetDevicePositionResponseTypeDef](./type_defs.md#batchgetdevicepositionresponsetypedef).

<a id="batch\_put\_geofence"></a>

### batch_put_geofence

A batch request for storing geofence geometries into a given geofence
collection, or updates the geometry of an existing geofence if a geofence ID is
included in the request.

Type annotations for `session.create_client("location").batch_put_geofence`
method.

Boto3 documentation:
[LocationService.Client.batch_put_geofence](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_put_geofence)

Asynchronous method. Use `await batch_put_geofence(...)` for a synchronous
call.

Arguments mapping described in
[BatchPutGeofenceRequestRequestTypeDef](./type_defs.md#batchputgeofencerequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `Entries`:
  `Sequence`\[[BatchPutGeofenceRequestEntryTypeDef](./type_defs.md#batchputgeofencerequestentrytypedef)\]
  *(required)*

Returns a `Coroutine` for
[BatchPutGeofenceResponseTypeDef](./type_defs.md#batchputgeofenceresponsetypedef).

<a id="batch\_update\_device\_position"></a>

### batch_update_device_position

Uploads position update data for one or more devices to a tracker resource.

Type annotations for
`session.create_client("location").batch_update_device_position` method.

Boto3 documentation:
[LocationService.Client.batch_update_device_position](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_update_device_position)

Asynchronous method. Use `await batch_update_device_position(...)` for a
synchronous call.

Arguments mapping described in
[BatchUpdateDevicePositionRequestRequestTypeDef](./type_defs.md#batchupdatedevicepositionrequestrequesttypedef).

Keyword-only arguments:

- `TrackerName`: `str` *(required)*
- `Updates`:
  `Sequence`\[[DevicePositionUpdateTypeDef](./type_defs.md#devicepositionupdatetypedef)\]
  *(required)*

Returns a `Coroutine` for
[BatchUpdateDevicePositionResponseTypeDef](./type_defs.md#batchupdatedevicepositionresponsetypedef).

<a id="calculate\_route"></a>

### calculate_route

Type annotations for `session.create_client("location").calculate_route`
method.

Boto3 documentation:
[LocationService.Client.calculate_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.calculate_route)

Asynchronous method. Use `await calculate_route(...)` for a synchronous call.

Arguments mapping described in
[CalculateRouteRequestRequestTypeDef](./type_defs.md#calculaterouterequestrequesttypedef).

Keyword-only arguments:

- `CalculatorName`: `str` *(required)*
- `DeparturePosition`: `Sequence`\[`float`\] *(required)*
- `DestinationPosition`: `Sequence`\[`float`\] *(required)*
- `CarModeOptions`:
  [CalculateRouteCarModeOptionsTypeDef](./type_defs.md#calculateroutecarmodeoptionstypedef)
- `DepartNow`: `bool`
- `DepartureTime`: `Union`\[`datetime`, `str`\]
- `DistanceUnit`: [DistanceUnitType](./literals.md#distanceunittype)
- `IncludeLegGeometry`: `bool`
- `TravelMode`: [TravelModeType](./literals.md#travelmodetype)
- `TruckModeOptions`:
  [CalculateRouteTruckModeOptionsTypeDef](./type_defs.md#calculateroutetruckmodeoptionstypedef)
- `WaypointPositions`: `Sequence`\[`Sequence`\[`float`\]\]

Returns a `Coroutine` for
[CalculateRouteResponseTypeDef](./type_defs.md#calculaterouteresponsetypedef).

<a id="calculate\_route\_matrix"></a>

### calculate_route_matrix

Type annotations for `session.create_client("location").calculate_route_matrix`
method.

Boto3 documentation:
[LocationService.Client.calculate_route_matrix](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.calculate_route_matrix)

Asynchronous method. Use `await calculate_route_matrix(...)` for a synchronous
call.

Arguments mapping described in
[CalculateRouteMatrixRequestRequestTypeDef](./type_defs.md#calculateroutematrixrequestrequesttypedef).

Keyword-only arguments:

- `CalculatorName`: `str` *(required)*
- `DeparturePositions`: `Sequence`\[`Sequence`\[`float`\]\] *(required)*
- `DestinationPositions`: `Sequence`\[`Sequence`\[`float`\]\] *(required)*
- `CarModeOptions`:
  [CalculateRouteCarModeOptionsTypeDef](./type_defs.md#calculateroutecarmodeoptionstypedef)
- `DepartNow`: `bool`
- `DepartureTime`: `Union`\[`datetime`, `str`\]
- `DistanceUnit`: [DistanceUnitType](./literals.md#distanceunittype)
- `TravelMode`: [TravelModeType](./literals.md#travelmodetype)
- `TruckModeOptions`:
  [CalculateRouteTruckModeOptionsTypeDef](./type_defs.md#calculateroutetruckmodeoptionstypedef)

Returns a `Coroutine` for
[CalculateRouteMatrixResponseTypeDef](./type_defs.md#calculateroutematrixresponsetypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("location").can_paginate` method.

Boto3 documentation:
[LocationService.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_geofence\_collection"></a>

### create_geofence_collection

Creates a geofence collection, which manages and stores geofences.

Type annotations for
`session.create_client("location").create_geofence_collection` method.

Boto3 documentation:
[LocationService.Client.create_geofence_collection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_geofence_collection)

Asynchronous method. Use `await create_geofence_collection(...)` for a
synchronous call.

Arguments mapping described in
[CreateGeofenceCollectionRequestRequestTypeDef](./type_defs.md#creategeofencecollectionrequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `Description`: `str`
- `KmsKeyId`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)
- `PricingPlanDataSource`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateGeofenceCollectionResponseTypeDef](./type_defs.md#creategeofencecollectionresponsetypedef).

<a id="create\_map"></a>

### create_map

Creates a map resource in your AWS account, which provides map tiles of
different styles sourced from global location data providers.

Type annotations for `session.create_client("location").create_map` method.

Boto3 documentation:
[LocationService.Client.create_map](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_map)

Asynchronous method. Use `await create_map(...)` for a synchronous call.

Arguments mapping described in
[CreateMapRequestRequestTypeDef](./type_defs.md#createmaprequestrequesttypedef).

Keyword-only arguments:

- `Configuration`:
  [MapConfigurationTypeDef](./type_defs.md#mapconfigurationtypedef)
  *(required)*
- `MapName`: `str` *(required)*
- `Description`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateMapResponseTypeDef](./type_defs.md#createmapresponsetypedef).

<a id="create\_place\_index"></a>

### create_place_index

Creates a place index resource in your AWS account.

Type annotations for `session.create_client("location").create_place_index`
method.

Boto3 documentation:
[LocationService.Client.create_place_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_place_index)

Asynchronous method. Use `await create_place_index(...)` for a synchronous
call.

Arguments mapping described in
[CreatePlaceIndexRequestRequestTypeDef](./type_defs.md#createplaceindexrequestrequesttypedef).

Keyword-only arguments:

- `DataSource`: `str` *(required)*
- `IndexName`: `str` *(required)*
- `DataSourceConfiguration`:
  [DataSourceConfigurationTypeDef](./type_defs.md#datasourceconfigurationtypedef)
- `Description`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreatePlaceIndexResponseTypeDef](./type_defs.md#createplaceindexresponsetypedef).

<a id="create\_route\_calculator"></a>

### create_route_calculator

Creates a route calculator resource in your AWS account.

Type annotations for
`session.create_client("location").create_route_calculator` method.

Boto3 documentation:
[LocationService.Client.create_route_calculator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_route_calculator)

Asynchronous method. Use `await create_route_calculator(...)` for a synchronous
call.

Arguments mapping described in
[CreateRouteCalculatorRequestRequestTypeDef](./type_defs.md#createroutecalculatorrequestrequesttypedef).

Keyword-only arguments:

- `CalculatorName`: `str` *(required)*
- `DataSource`: `str` *(required)*
- `Description`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateRouteCalculatorResponseTypeDef](./type_defs.md#createroutecalculatorresponsetypedef).

<a id="create\_tracker"></a>

### create_tracker

Creates a tracker resource in your AWS account, which lets you retrieve current
and historical location of devices.

Type annotations for `session.create_client("location").create_tracker` method.

Boto3 documentation:
[LocationService.Client.create_tracker](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_tracker)

Asynchronous method. Use `await create_tracker(...)` for a synchronous call.

Arguments mapping described in
[CreateTrackerRequestRequestTypeDef](./type_defs.md#createtrackerrequestrequesttypedef).

Keyword-only arguments:

- `TrackerName`: `str` *(required)*
- `Description`: `str`
- `KmsKeyId`: `str`
- `PositionFiltering`:
  [PositionFilteringType](./literals.md#positionfilteringtype)
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)
- `PricingPlanDataSource`: `str`
- `Tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateTrackerResponseTypeDef](./type_defs.md#createtrackerresponsetypedef).

<a id="delete\_geofence\_collection"></a>

### delete_geofence_collection

Deletes a geofence collection from your AWS account.

Type annotations for
`session.create_client("location").delete_geofence_collection` method.

Boto3 documentation:
[LocationService.Client.delete_geofence_collection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_geofence_collection)

Asynchronous method. Use `await delete_geofence_collection(...)` for a
synchronous call.

Arguments mapping described in
[DeleteGeofenceCollectionRequestRequestTypeDef](./type_defs.md#deletegeofencecollectionrequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_map"></a>

### delete_map

Deletes a map resource from your AWS account.

Type annotations for `session.create_client("location").delete_map` method.

Boto3 documentation:
[LocationService.Client.delete_map](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_map)

Asynchronous method. Use `await delete_map(...)` for a synchronous call.

Arguments mapping described in
[DeleteMapRequestRequestTypeDef](./type_defs.md#deletemaprequestrequesttypedef).

Keyword-only arguments:

- `MapName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_place\_index"></a>

### delete_place_index

Deletes a place index resource from your AWS account.

Type annotations for `session.create_client("location").delete_place_index`
method.

Boto3 documentation:
[LocationService.Client.delete_place_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_place_index)

Asynchronous method. Use `await delete_place_index(...)` for a synchronous
call.

Arguments mapping described in
[DeletePlaceIndexRequestRequestTypeDef](./type_defs.md#deleteplaceindexrequestrequesttypedef).

Keyword-only arguments:

- `IndexName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_route\_calculator"></a>

### delete_route_calculator

Deletes a route calculator resource from your AWS account.

Type annotations for
`session.create_client("location").delete_route_calculator` method.

Boto3 documentation:
[LocationService.Client.delete_route_calculator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_route_calculator)

Asynchronous method. Use `await delete_route_calculator(...)` for a synchronous
call.

Arguments mapping described in
[DeleteRouteCalculatorRequestRequestTypeDef](./type_defs.md#deleteroutecalculatorrequestrequesttypedef).

Keyword-only arguments:

- `CalculatorName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_tracker"></a>

### delete_tracker

Deletes a tracker resource from your AWS account.

Type annotations for `session.create_client("location").delete_tracker` method.

Boto3 documentation:
[LocationService.Client.delete_tracker](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_tracker)

Asynchronous method. Use `await delete_tracker(...)` for a synchronous call.

Arguments mapping described in
[DeleteTrackerRequestRequestTypeDef](./type_defs.md#deletetrackerrequestrequesttypedef).

Keyword-only arguments:

- `TrackerName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe\_geofence\_collection"></a>

### describe_geofence_collection

Retrieves the geofence collection details.

Type annotations for
`session.create_client("location").describe_geofence_collection` method.

Boto3 documentation:
[LocationService.Client.describe_geofence_collection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_geofence_collection)

Asynchronous method. Use `await describe_geofence_collection(...)` for a
synchronous call.

Arguments mapping described in
[DescribeGeofenceCollectionRequestRequestTypeDef](./type_defs.md#describegeofencecollectionrequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeGeofenceCollectionResponseTypeDef](./type_defs.md#describegeofencecollectionresponsetypedef).

<a id="describe\_map"></a>

### describe_map

Retrieves the map resource details.

Type annotations for `session.create_client("location").describe_map` method.

Boto3 documentation:
[LocationService.Client.describe_map](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_map)

Asynchronous method. Use `await describe_map(...)` for a synchronous call.

Arguments mapping described in
[DescribeMapRequestRequestTypeDef](./type_defs.md#describemaprequestrequesttypedef).

Keyword-only arguments:

- `MapName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeMapResponseTypeDef](./type_defs.md#describemapresponsetypedef).

<a id="describe\_place\_index"></a>

### describe_place_index

Retrieves the place index resource details.

Type annotations for `session.create_client("location").describe_place_index`
method.

Boto3 documentation:
[LocationService.Client.describe_place_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_place_index)

Asynchronous method. Use `await describe_place_index(...)` for a synchronous
call.

Arguments mapping described in
[DescribePlaceIndexRequestRequestTypeDef](./type_defs.md#describeplaceindexrequestrequesttypedef).

Keyword-only arguments:

- `IndexName`: `str` *(required)*

Returns a `Coroutine` for
[DescribePlaceIndexResponseTypeDef](./type_defs.md#describeplaceindexresponsetypedef).

<a id="describe\_route\_calculator"></a>

### describe_route_calculator

Retrieves the route calculator resource details.

Type annotations for
`session.create_client("location").describe_route_calculator` method.

Boto3 documentation:
[LocationService.Client.describe_route_calculator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_route_calculator)

Asynchronous method. Use `await describe_route_calculator(...)` for a
synchronous call.

Arguments mapping described in
[DescribeRouteCalculatorRequestRequestTypeDef](./type_defs.md#describeroutecalculatorrequestrequesttypedef).

Keyword-only arguments:

- `CalculatorName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeRouteCalculatorResponseTypeDef](./type_defs.md#describeroutecalculatorresponsetypedef).

<a id="describe\_tracker"></a>

### describe_tracker

Retrieves the tracker resource details.

Type annotations for `session.create_client("location").describe_tracker`
method.

Boto3 documentation:
[LocationService.Client.describe_tracker](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_tracker)

Asynchronous method. Use `await describe_tracker(...)` for a synchronous call.

Arguments mapping described in
[DescribeTrackerRequestRequestTypeDef](./type_defs.md#describetrackerrequestrequesttypedef).

Keyword-only arguments:

- `TrackerName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTrackerResponseTypeDef](./type_defs.md#describetrackerresponsetypedef).

<a id="disassociate\_tracker\_consumer"></a>

### disassociate_tracker_consumer

Removes the association between a tracker resource and a geofence collection.

Type annotations for
`session.create_client("location").disassociate_tracker_consumer` method.

Boto3 documentation:
[LocationService.Client.disassociate_tracker_consumer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.disassociate_tracker_consumer)

Asynchronous method. Use `await disassociate_tracker_consumer(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateTrackerConsumerRequestRequestTypeDef](./type_defs.md#disassociatetrackerconsumerrequestrequesttypedef).

Keyword-only arguments:

- `ConsumerArn`: `str` *(required)*
- `TrackerName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("location").generate_presigned_url`
method.

Boto3 documentation:
[LocationService.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_device\_position"></a>

### get_device_position

Retrieves a device's most recent position according to its sample time.

Type annotations for `session.create_client("location").get_device_position`
method.

Boto3 documentation:
[LocationService.Client.get_device_position](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_device_position)

Asynchronous method. Use `await get_device_position(...)` for a synchronous
call.

Arguments mapping described in
[GetDevicePositionRequestRequestTypeDef](./type_defs.md#getdevicepositionrequestrequesttypedef).

Keyword-only arguments:

- `DeviceId`: `str` *(required)*
- `TrackerName`: `str` *(required)*

Returns a `Coroutine` for
[GetDevicePositionResponseTypeDef](./type_defs.md#getdevicepositionresponsetypedef).

<a id="get\_device\_position\_history"></a>

### get_device_position_history

Retrieves the device position history from a tracker resource within a
specified range of time.

Type annotations for
`session.create_client("location").get_device_position_history` method.

Boto3 documentation:
[LocationService.Client.get_device_position_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_device_position_history)

Asynchronous method. Use `await get_device_position_history(...)` for a
synchronous call.

Arguments mapping described in
[GetDevicePositionHistoryRequestRequestTypeDef](./type_defs.md#getdevicepositionhistoryrequestrequesttypedef).

Keyword-only arguments:

- `DeviceId`: `str` *(required)*
- `TrackerName`: `str` *(required)*
- `EndTimeExclusive`: `Union`\[`datetime`, `str`\]
- `NextToken`: `str`
- `StartTimeInclusive`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[GetDevicePositionHistoryResponseTypeDef](./type_defs.md#getdevicepositionhistoryresponsetypedef).

<a id="get\_geofence"></a>

### get_geofence

Retrieves the geofence details from a geofence collection.

Type annotations for `session.create_client("location").get_geofence` method.

Boto3 documentation:
[LocationService.Client.get_geofence](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_geofence)

Asynchronous method. Use `await get_geofence(...)` for a synchronous call.

Arguments mapping described in
[GetGeofenceRequestRequestTypeDef](./type_defs.md#getgeofencerequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `GeofenceId`: `str` *(required)*

Returns a `Coroutine` for
[GetGeofenceResponseTypeDef](./type_defs.md#getgeofenceresponsetypedef).

<a id="get\_map\_glyphs"></a>

### get_map_glyphs

Retrieves glyphs used to display labels on a map.

Type annotations for `session.create_client("location").get_map_glyphs` method.

Boto3 documentation:
[LocationService.Client.get_map_glyphs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_glyphs)

Asynchronous method. Use `await get_map_glyphs(...)` for a synchronous call.

Arguments mapping described in
[GetMapGlyphsRequestRequestTypeDef](./type_defs.md#getmapglyphsrequestrequesttypedef).

Keyword-only arguments:

- `FontStack`: `str` *(required)*
- `FontUnicodeRange`: `str` *(required)*
- `MapName`: `str` *(required)*

Returns a `Coroutine` for
[GetMapGlyphsResponseTypeDef](./type_defs.md#getmapglyphsresponsetypedef).

<a id="get\_map\_sprites"></a>

### get_map_sprites

Retrieves the sprite sheet corresponding to a map resource.

Type annotations for `session.create_client("location").get_map_sprites`
method.

Boto3 documentation:
[LocationService.Client.get_map_sprites](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_sprites)

Asynchronous method. Use `await get_map_sprites(...)` for a synchronous call.

Arguments mapping described in
[GetMapSpritesRequestRequestTypeDef](./type_defs.md#getmapspritesrequestrequesttypedef).

Keyword-only arguments:

- `FileName`: `str` *(required)*
- `MapName`: `str` *(required)*

Returns a `Coroutine` for
[GetMapSpritesResponseTypeDef](./type_defs.md#getmapspritesresponsetypedef).

<a id="get\_map\_style\_descriptor"></a>

### get_map_style_descriptor

Retrieves the map style descriptor from a map resource.

Type annotations for
`session.create_client("location").get_map_style_descriptor` method.

Boto3 documentation:
[LocationService.Client.get_map_style_descriptor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_style_descriptor)

Asynchronous method. Use `await get_map_style_descriptor(...)` for a
synchronous call.

Arguments mapping described in
[GetMapStyleDescriptorRequestRequestTypeDef](./type_defs.md#getmapstyledescriptorrequestrequesttypedef).

Keyword-only arguments:

- `MapName`: `str` *(required)*

Returns a `Coroutine` for
[GetMapStyleDescriptorResponseTypeDef](./type_defs.md#getmapstyledescriptorresponsetypedef).

<a id="get\_map\_tile"></a>

### get_map_tile

Retrieves a vector data tile from the map resource.

Type annotations for `session.create_client("location").get_map_tile` method.

Boto3 documentation:
[LocationService.Client.get_map_tile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_tile)

Asynchronous method. Use `await get_map_tile(...)` for a synchronous call.

Arguments mapping described in
[GetMapTileRequestRequestTypeDef](./type_defs.md#getmaptilerequestrequesttypedef).

Keyword-only arguments:

- `MapName`: `str` *(required)*
- `X`: `str` *(required)*
- `Y`: `str` *(required)*
- `Z`: `str` *(required)*

Returns a `Coroutine` for
[GetMapTileResponseTypeDef](./type_defs.md#getmaptileresponsetypedef).

<a id="list\_device\_positions"></a>

### list_device_positions

A batch request to retrieve all device positions.

Type annotations for `session.create_client("location").list_device_positions`
method.

Boto3 documentation:
[LocationService.Client.list_device_positions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_device_positions)

Asynchronous method. Use `await list_device_positions(...)` for a synchronous
call.

Arguments mapping described in
[ListDevicePositionsRequestRequestTypeDef](./type_defs.md#listdevicepositionsrequestrequesttypedef).

Keyword-only arguments:

- `TrackerName`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListDevicePositionsResponseTypeDef](./type_defs.md#listdevicepositionsresponsetypedef).

<a id="list\_geofence\_collections"></a>

### list_geofence_collections

Lists geofence collections in your AWS account.

Type annotations for
`session.create_client("location").list_geofence_collections` method.

Boto3 documentation:
[LocationService.Client.list_geofence_collections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_geofence_collections)

Asynchronous method. Use `await list_geofence_collections(...)` for a
synchronous call.

Arguments mapping described in
[ListGeofenceCollectionsRequestRequestTypeDef](./type_defs.md#listgeofencecollectionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListGeofenceCollectionsResponseTypeDef](./type_defs.md#listgeofencecollectionsresponsetypedef).

<a id="list\_geofences"></a>

### list_geofences

Lists geofences stored in a given geofence collection.

Type annotations for `session.create_client("location").list_geofences` method.

Boto3 documentation:
[LocationService.Client.list_geofences](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_geofences)

Asynchronous method. Use `await list_geofences(...)` for a synchronous call.

Arguments mapping described in
[ListGeofencesRequestRequestTypeDef](./type_defs.md#listgeofencesrequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[ListGeofencesResponseTypeDef](./type_defs.md#listgeofencesresponsetypedef).

<a id="list\_maps"></a>

### list_maps

Lists map resources in your AWS account.

Type annotations for `session.create_client("location").list_maps` method.

Boto3 documentation:
[LocationService.Client.list_maps](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_maps)

Asynchronous method. Use `await list_maps(...)` for a synchronous call.

Arguments mapping described in
[ListMapsRequestRequestTypeDef](./type_defs.md#listmapsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListMapsResponseTypeDef](./type_defs.md#listmapsresponsetypedef).

<a id="list\_place\_indexes"></a>

### list_place_indexes

Lists place index resources in your AWS account.

Type annotations for `session.create_client("location").list_place_indexes`
method.

Boto3 documentation:
[LocationService.Client.list_place_indexes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_place_indexes)

Asynchronous method. Use `await list_place_indexes(...)` for a synchronous
call.

Arguments mapping described in
[ListPlaceIndexesRequestRequestTypeDef](./type_defs.md#listplaceindexesrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListPlaceIndexesResponseTypeDef](./type_defs.md#listplaceindexesresponsetypedef).

<a id="list\_route\_calculators"></a>

### list_route_calculators

Lists route calculator resources in your AWS account.

Type annotations for `session.create_client("location").list_route_calculators`
method.

Boto3 documentation:
[LocationService.Client.list_route_calculators](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_route_calculators)

Asynchronous method. Use `await list_route_calculators(...)` for a synchronous
call.

Arguments mapping described in
[ListRouteCalculatorsRequestRequestTypeDef](./type_defs.md#listroutecalculatorsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListRouteCalculatorsResponseTypeDef](./type_defs.md#listroutecalculatorsresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Returns a list of tags that are applied to the specified Amazon Location
resource.

Type annotations for `session.create_client("location").list_tags_for_resource`
method.

Boto3 documentation:
[LocationService.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list\_tracker\_consumers"></a>

### list_tracker_consumers

Lists geofence collections currently associated to the given tracker resource.

Type annotations for `session.create_client("location").list_tracker_consumers`
method.

Boto3 documentation:
[LocationService.Client.list_tracker_consumers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_tracker_consumers)

Asynchronous method. Use `await list_tracker_consumers(...)` for a synchronous
call.

Arguments mapping described in
[ListTrackerConsumersRequestRequestTypeDef](./type_defs.md#listtrackerconsumersrequestrequesttypedef).

Keyword-only arguments:

- `TrackerName`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTrackerConsumersResponseTypeDef](./type_defs.md#listtrackerconsumersresponsetypedef).

<a id="list\_trackers"></a>

### list_trackers

Lists tracker resources in your AWS account.

Type annotations for `session.create_client("location").list_trackers` method.

Boto3 documentation:
[LocationService.Client.list_trackers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_trackers)

Asynchronous method. Use `await list_trackers(...)` for a synchronous call.

Arguments mapping described in
[ListTrackersRequestRequestTypeDef](./type_defs.md#listtrackersrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTrackersResponseTypeDef](./type_defs.md#listtrackersresponsetypedef).

<a id="put\_geofence"></a>

### put_geofence

Stores a geofence geometry in a given geofence collection, or updates the
geometry of an existing geofence if a geofence ID is included in the request.

Type annotations for `session.create_client("location").put_geofence` method.

Boto3 documentation:
[LocationService.Client.put_geofence](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.put_geofence)

Asynchronous method. Use `await put_geofence(...)` for a synchronous call.

Arguments mapping described in
[PutGeofenceRequestRequestTypeDef](./type_defs.md#putgeofencerequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `GeofenceId`: `str` *(required)*
- `Geometry`: [GeofenceGeometryTypeDef](./type_defs.md#geofencegeometrytypedef)
  *(required)*

Returns a `Coroutine` for
[PutGeofenceResponseTypeDef](./type_defs.md#putgeofenceresponsetypedef).

<a id="search\_place\_index\_for\_position"></a>

### search_place_index_for_position

Reverse geocodes a given coordinate and returns a legible address.

Type annotations for
`session.create_client("location").search_place_index_for_position` method.

Boto3 documentation:
[LocationService.Client.search_place_index_for_position](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.search_place_index_for_position)

Asynchronous method. Use `await search_place_index_for_position(...)` for a
synchronous call.

Arguments mapping described in
[SearchPlaceIndexForPositionRequestRequestTypeDef](./type_defs.md#searchplaceindexforpositionrequestrequesttypedef).

Keyword-only arguments:

- `IndexName`: `str` *(required)*
- `Position`: `Sequence`\[`float`\] *(required)*
- `Language`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[SearchPlaceIndexForPositionResponseTypeDef](./type_defs.md#searchplaceindexforpositionresponsetypedef).

<a id="search\_place\_index\_for\_suggestions"></a>

### search_place_index_for_suggestions

Generates suggestions for addresses and points of interest based on partial or
misspelled free-form text.

Type annotations for
`session.create_client("location").search_place_index_for_suggestions` method.

Boto3 documentation:
[LocationService.Client.search_place_index_for_suggestions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.search_place_index_for_suggestions)

Asynchronous method. Use `await search_place_index_for_suggestions(...)` for a
synchronous call.

Arguments mapping described in
[SearchPlaceIndexForSuggestionsRequestRequestTypeDef](./type_defs.md#searchplaceindexforsuggestionsrequestrequesttypedef).

Keyword-only arguments:

- `IndexName`: `str` *(required)*
- `Text`: `str` *(required)*
- `BiasPosition`: `Sequence`\[`float`\]
- `FilterBBox`: `Sequence`\[`float`\]
- `FilterCountries`: `Sequence`\[`str`\]
- `Language`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[SearchPlaceIndexForSuggestionsResponseTypeDef](./type_defs.md#searchplaceindexforsuggestionsresponsetypedef).

<a id="search\_place\_index\_for\_text"></a>

### search_place_index_for_text

Geocodes free-form text, such as an address, name, city, or region to allow you
to search for Places or points of interest.

Type annotations for
`session.create_client("location").search_place_index_for_text` method.

Boto3 documentation:
[LocationService.Client.search_place_index_for_text](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.search_place_index_for_text)

Asynchronous method. Use `await search_place_index_for_text(...)` for a
synchronous call.

Arguments mapping described in
[SearchPlaceIndexForTextRequestRequestTypeDef](./type_defs.md#searchplaceindexfortextrequestrequesttypedef).

Keyword-only arguments:

- `IndexName`: `str` *(required)*
- `Text`: `str` *(required)*
- `BiasPosition`: `Sequence`\[`float`\]
- `FilterBBox`: `Sequence`\[`float`\]
- `FilterCountries`: `Sequence`\[`str`\]
- `Language`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[SearchPlaceIndexForTextResponseTypeDef](./type_defs.md#searchplaceindexfortextresponsetypedef).

<a id="tag\_resource"></a>

### tag_resource

Assigns one or more tags (key-value pairs) to the specified Amazon Location
Service resource.

Type annotations for `session.create_client("location").tag_resource` method.

Boto3 documentation:
[LocationService.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag\_resource"></a>

### untag_resource

Removes one or more tags from the specified Amazon Location resource.

Type annotations for `session.create_client("location").untag_resource` method.

Boto3 documentation:
[LocationService.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update\_geofence\_collection"></a>

### update_geofence_collection

Updates the specified properties of a given geofence collection.

Type annotations for
`session.create_client("location").update_geofence_collection` method.

Boto3 documentation:
[LocationService.Client.update_geofence_collection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_geofence_collection)

Asynchronous method. Use `await update_geofence_collection(...)` for a
synchronous call.

Arguments mapping described in
[UpdateGeofenceCollectionRequestRequestTypeDef](./type_defs.md#updategeofencecollectionrequestrequesttypedef).

Keyword-only arguments:

- `CollectionName`: `str` *(required)*
- `Description`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)
- `PricingPlanDataSource`: `str`

Returns a `Coroutine` for
[UpdateGeofenceCollectionResponseTypeDef](./type_defs.md#updategeofencecollectionresponsetypedef).

<a id="update\_map"></a>

### update_map

Updates the specified properties of a given map resource.

Type annotations for `session.create_client("location").update_map` method.

Boto3 documentation:
[LocationService.Client.update_map](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_map)

Asynchronous method. Use `await update_map(...)` for a synchronous call.

Arguments mapping described in
[UpdateMapRequestRequestTypeDef](./type_defs.md#updatemaprequestrequesttypedef).

Keyword-only arguments:

- `MapName`: `str` *(required)*
- `Description`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)

Returns a `Coroutine` for
[UpdateMapResponseTypeDef](./type_defs.md#updatemapresponsetypedef).

<a id="update\_place\_index"></a>

### update_place_index

Updates the specified properties of a given place index resource.

Type annotations for `session.create_client("location").update_place_index`
method.

Boto3 documentation:
[LocationService.Client.update_place_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_place_index)

Asynchronous method. Use `await update_place_index(...)` for a synchronous
call.

Arguments mapping described in
[UpdatePlaceIndexRequestRequestTypeDef](./type_defs.md#updateplaceindexrequestrequesttypedef).

Keyword-only arguments:

- `IndexName`: `str` *(required)*
- `DataSourceConfiguration`:
  [DataSourceConfigurationTypeDef](./type_defs.md#datasourceconfigurationtypedef)
- `Description`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)

Returns a `Coroutine` for
[UpdatePlaceIndexResponseTypeDef](./type_defs.md#updateplaceindexresponsetypedef).

<a id="update\_route\_calculator"></a>

### update_route_calculator

Updates the specified properties for a given route calculator resource.

Type annotations for
`session.create_client("location").update_route_calculator` method.

Boto3 documentation:
[LocationService.Client.update_route_calculator](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_route_calculator)

Asynchronous method. Use `await update_route_calculator(...)` for a synchronous
call.

Arguments mapping described in
[UpdateRouteCalculatorRequestRequestTypeDef](./type_defs.md#updateroutecalculatorrequestrequesttypedef).

Keyword-only arguments:

- `CalculatorName`: `str` *(required)*
- `Description`: `str`
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)

Returns a `Coroutine` for
[UpdateRouteCalculatorResponseTypeDef](./type_defs.md#updateroutecalculatorresponsetypedef).

<a id="update\_tracker"></a>

### update_tracker

Updates the specified properties of a given tracker resource.

Type annotations for `session.create_client("location").update_tracker` method.

Boto3 documentation:
[LocationService.Client.update_tracker](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_tracker)

Asynchronous method. Use `await update_tracker(...)` for a synchronous call.

Arguments mapping described in
[UpdateTrackerRequestRequestTypeDef](./type_defs.md#updatetrackerrequestrequesttypedef).

Keyword-only arguments:

- `TrackerName`: `str` *(required)*
- `Description`: `str`
- `PositionFiltering`:
  [PositionFilteringType](./literals.md#positionfilteringtype)
- `PricingPlan`: [PricingPlanType](./literals.md#pricingplantype)
- `PricingPlanDataSource`: `str`

Returns a `Coroutine` for
[UpdateTrackerResponseTypeDef](./type_defs.md#updatetrackerresponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("location").__aenter__` method.

Boto3 documentation:
[LocationService.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [LocationServiceClient](#locationserviceclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("location").__aexit__` method.

Boto3 documentation:
[LocationService.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("location").get_paginator` method
with overloads.

- `client.get_paginator("get_device_position_history")` ->
  [GetDevicePositionHistoryPaginator](./paginators.md#getdevicepositionhistorypaginator)
- `client.get_paginator("list_device_positions")` ->
  [ListDevicePositionsPaginator](./paginators.md#listdevicepositionspaginator)
- `client.get_paginator("list_geofence_collections")` ->
  [ListGeofenceCollectionsPaginator](./paginators.md#listgeofencecollectionspaginator)
- `client.get_paginator("list_geofences")` ->
  [ListGeofencesPaginator](./paginators.md#listgeofencespaginator)
- `client.get_paginator("list_maps")` ->
  [ListMapsPaginator](./paginators.md#listmapspaginator)
- `client.get_paginator("list_place_indexes")` ->
  [ListPlaceIndexesPaginator](./paginators.md#listplaceindexespaginator)
- `client.get_paginator("list_route_calculators")` ->
  [ListRouteCalculatorsPaginator](./paginators.md#listroutecalculatorspaginator)
- `client.get_paginator("list_tracker_consumers")` ->
  [ListTrackerConsumersPaginator](./paginators.md#listtrackerconsumerspaginator)
- `client.get_paginator("list_trackers")` ->
  [ListTrackersPaginator](./paginators.md#listtrackerspaginator)
