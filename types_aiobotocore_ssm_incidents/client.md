<a id="ssmincidentsclient-for-aiobotocore-ssmincidents-module"></a>

# SSMIncidentsClient for aiobotocore SSMIncidents module

> [Index](..) > [SSMIncidents](.) > SSMIncidentsClient

Auto-generated documentation for
[SSMIncidents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
type annotations stubs module
[types-aiobotocore-ssm-incidents](https://pypi.org/project/types-aiobotocore-ssm-incidents/).

- [SSMIncidentsClient for aiobotocore SSMIncidents module](#ssmincidentsclient-for-aiobotocore-ssmincidents-module)
  - [SSMIncidentsClient](#ssmincidentsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_replication_set](#create_replication_set)
    - [create_response_plan](#create_response_plan)
    - [create_timeline_event](#create_timeline_event)
    - [delete_incident_record](#delete_incident_record)
    - [delete_replication_set](#delete_replication_set)
    - [delete_resource_policy](#delete_resource_policy)
    - [delete_response_plan](#delete_response_plan)
    - [delete_timeline_event](#delete_timeline_event)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_incident_record](#get_incident_record)
    - [get_replication_set](#get_replication_set)
    - [get_resource_policies](#get_resource_policies)
    - [get_response_plan](#get_response_plan)
    - [get_timeline_event](#get_timeline_event)
    - [list_incident_records](#list_incident_records)
    - [list_related_items](#list_related_items)
    - [list_replication_sets](#list_replication_sets)
    - [list_response_plans](#list_response_plans)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_timeline_events](#list_timeline_events)
    - [put_resource_policy](#put_resource_policy)
    - [start_incident](#start_incident)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_deletion_protection](#update_deletion_protection)
    - [update_incident_record](#update_incident_record)
    - [update_related_items](#update_related_items)
    - [update_replication_set](#update_replication_set)
    - [update_response_plan](#update_response_plan)
    - [update_timeline_event](#update_timeline_event)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="ssmincidentsclient"></a>

## SSMIncidentsClient

Type annotations for `aiobotocore.create_client("ssm-incidents")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_ssm_incidents.client import SSMIncidentsClient

def get_ssm-incidents_client() -> SSMIncidentsClient:
    return Session().client("ssm-incidents")
```

Boto3 documentation:
[SSMIncidents.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ssm_incidents.client import Exceptions

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

SSMIncidentsClient exceptions.

Type annotations for `aiobotocore.create_client("ssm-incidents").exceptions`
method.

Boto3 documentation:
[SSMIncidents.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("ssm-incidents").can_paginate`
method.

Boto3 documentation:
[SSMIncidents.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_replication_set"></a>

### create_replication_set

A replication set replicates and encrypts your data to the provided Regions
with the provided KMS key.

Type annotations for
`aiobotocore.create_client("ssm-incidents").create_replication_set` method.

Boto3 documentation:
[SSMIncidents.Client.create_replication_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.create_replication_set)

Asynchronous method. Use `await create_replication_set(...)` for a synchronous
call.

Arguments mapping described in
[CreateReplicationSetInputRequestTypeDef](./type_defs.md#createreplicationsetinputrequesttypedef).

Keyword-only arguments:

- `regions`: `Mapping`\[`str`,
  [RegionMapInputValueTypeDef](./type_defs.md#regionmapinputvaluetypedef)\]
  *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[CreateReplicationSetOutputTypeDef](./type_defs.md#createreplicationsetoutputtypedef).

<a id="create_response_plan"></a>

### create_response_plan

Creates a response plan that automates the initial response to incidents.

Type annotations for
`aiobotocore.create_client("ssm-incidents").create_response_plan` method.

Boto3 documentation:
[SSMIncidents.Client.create_response_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.create_response_plan)

Asynchronous method. Use `await create_response_plan(...)` for a synchronous
call.

Arguments mapping described in
[CreateResponsePlanInputRequestTypeDef](./type_defs.md#createresponseplaninputrequesttypedef).

Keyword-only arguments:

- `incidentTemplate`:
  [IncidentTemplateTypeDef](./type_defs.md#incidenttemplatetypedef)
  *(required)*
- `name`: `str` *(required)*
- `actions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]
- `chatChannel`: [ChatChannelTypeDef](./type_defs.md#chatchanneltypedef)
- `clientToken`: `str`
- `displayName`: `str`
- `engagements`: `Sequence`\[`str`\]
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateResponsePlanOutputTypeDef](./type_defs.md#createresponseplanoutputtypedef).

<a id="create_timeline_event"></a>

### create_timeline_event

Creates a custom timeline event on the incident details page of an incident
record.

Type annotations for
`aiobotocore.create_client("ssm-incidents").create_timeline_event` method.

Boto3 documentation:
[SSMIncidents.Client.create_timeline_event](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.create_timeline_event)

Asynchronous method. Use `await create_timeline_event(...)` for a synchronous
call.

Arguments mapping described in
[CreateTimelineEventInputRequestTypeDef](./type_defs.md#createtimelineeventinputrequesttypedef).

Keyword-only arguments:

- `eventData`: `str` *(required)*
- `eventTime`: `Union`\[`datetime`, `str`\] *(required)*
- `eventType`: `str` *(required)*
- `incidentRecordArn`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[CreateTimelineEventOutputTypeDef](./type_defs.md#createtimelineeventoutputtypedef).

<a id="delete_incident_record"></a>

### delete_incident_record

Delete an incident record from Incident Manager.

Type annotations for
`aiobotocore.create_client("ssm-incidents").delete_incident_record` method.

Boto3 documentation:
[SSMIncidents.Client.delete_incident_record](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.delete_incident_record)

Asynchronous method. Use `await delete_incident_record(...)` for a synchronous
call.

Arguments mapping described in
[DeleteIncidentRecordInputRequestTypeDef](./type_defs.md#deleteincidentrecordinputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_replication_set"></a>

### delete_replication_set

Deletes all Regions in your replication set.

Type annotations for
`aiobotocore.create_client("ssm-incidents").delete_replication_set` method.

Boto3 documentation:
[SSMIncidents.Client.delete_replication_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.delete_replication_set)

Asynchronous method. Use `await delete_replication_set(...)` for a synchronous
call.

Arguments mapping described in
[DeleteReplicationSetInputRequestTypeDef](./type_defs.md#deletereplicationsetinputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_resource_policy"></a>

### delete_resource_policy

Deletes the resource policy that Resource Access Manager uses to share your
Incident Manager resource.

Type annotations for
`aiobotocore.create_client("ssm-incidents").delete_resource_policy` method.

Boto3 documentation:
[SSMIncidents.Client.delete_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.delete_resource_policy)

Asynchronous method. Use `await delete_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResourcePolicyInputRequestTypeDef](./type_defs.md#deleteresourcepolicyinputrequesttypedef).

Keyword-only arguments:

- `policyId`: `str` *(required)*
- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_response_plan"></a>

### delete_response_plan

Deletes the specified response plan.

Type annotations for
`aiobotocore.create_client("ssm-incidents").delete_response_plan` method.

Boto3 documentation:
[SSMIncidents.Client.delete_response_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.delete_response_plan)

Asynchronous method. Use `await delete_response_plan(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResponsePlanInputRequestTypeDef](./type_defs.md#deleteresponseplaninputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_timeline_event"></a>

### delete_timeline_event

Deletes a timeline event from an incident.

Type annotations for
`aiobotocore.create_client("ssm-incidents").delete_timeline_event` method.

Boto3 documentation:
[SSMIncidents.Client.delete_timeline_event](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.delete_timeline_event)

Asynchronous method. Use `await delete_timeline_event(...)` for a synchronous
call.

Arguments mapping described in
[DeleteTimelineEventInputRequestTypeDef](./type_defs.md#deletetimelineeventinputrequesttypedef).

Keyword-only arguments:

- `eventId`: `str` *(required)*
- `incidentRecordArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("ssm-incidents").generate_presigned_url` method.

Boto3 documentation:
[SSMIncidents.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_incident_record"></a>

### get_incident_record

Returns the details for the specified incident record.

Type annotations for
`aiobotocore.create_client("ssm-incidents").get_incident_record` method.

Boto3 documentation:
[SSMIncidents.Client.get_incident_record](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.get_incident_record)

Asynchronous method. Use `await get_incident_record(...)` for a synchronous
call.

Arguments mapping described in
[GetIncidentRecordInputRequestTypeDef](./type_defs.md#getincidentrecordinputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetIncidentRecordOutputTypeDef](./type_defs.md#getincidentrecordoutputtypedef).

<a id="get_replication_set"></a>

### get_replication_set

Retrieve your Incident Manager replication set.

Type annotations for
`aiobotocore.create_client("ssm-incidents").get_replication_set` method.

Boto3 documentation:
[SSMIncidents.Client.get_replication_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.get_replication_set)

Asynchronous method. Use `await get_replication_set(...)` for a synchronous
call.

Arguments mapping described in
[GetReplicationSetInputRequestTypeDef](./type_defs.md#getreplicationsetinputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetReplicationSetOutputTypeDef](./type_defs.md#getreplicationsetoutputtypedef).

<a id="get_resource_policies"></a>

### get_resource_policies

Retrieves the resource policies attached to the specified response plan.

Type annotations for
`aiobotocore.create_client("ssm-incidents").get_resource_policies` method.

Boto3 documentation:
[SSMIncidents.Client.get_resource_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.get_resource_policies)

Asynchronous method. Use `await get_resource_policies(...)` for a synchronous
call.

Arguments mapping described in
[GetResourcePoliciesInputRequestTypeDef](./type_defs.md#getresourcepoliciesinputrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[GetResourcePoliciesOutputTypeDef](./type_defs.md#getresourcepoliciesoutputtypedef).

<a id="get_response_plan"></a>

### get_response_plan

Retrieves the details of the specified response plan.

Type annotations for
`aiobotocore.create_client("ssm-incidents").get_response_plan` method.

Boto3 documentation:
[SSMIncidents.Client.get_response_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.get_response_plan)

Asynchronous method. Use `await get_response_plan(...)` for a synchronous call.

Arguments mapping described in
[GetResponsePlanInputRequestTypeDef](./type_defs.md#getresponseplaninputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetResponsePlanOutputTypeDef](./type_defs.md#getresponseplanoutputtypedef).

<a id="get_timeline_event"></a>

### get_timeline_event

Retrieves a timeline event based on its ID and incident record.

Type annotations for
`aiobotocore.create_client("ssm-incidents").get_timeline_event` method.

Boto3 documentation:
[SSMIncidents.Client.get_timeline_event](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.get_timeline_event)

Asynchronous method. Use `await get_timeline_event(...)` for a synchronous
call.

Arguments mapping described in
[GetTimelineEventInputRequestTypeDef](./type_defs.md#gettimelineeventinputrequesttypedef).

Keyword-only arguments:

- `eventId`: `str` *(required)*
- `incidentRecordArn`: `str` *(required)*

Returns a `Coroutine` for
[GetTimelineEventOutputTypeDef](./type_defs.md#gettimelineeventoutputtypedef).

<a id="list_incident_records"></a>

### list_incident_records

Lists all incident records in your account.

Type annotations for
`aiobotocore.create_client("ssm-incidents").list_incident_records` method.

Boto3 documentation:
[SSMIncidents.Client.list_incident_records](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.list_incident_records)

Asynchronous method. Use `await list_incident_records(...)` for a synchronous
call.

Arguments mapping described in
[ListIncidentRecordsInputRequestTypeDef](./type_defs.md#listincidentrecordsinputrequesttypedef).

Keyword-only arguments:

- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListIncidentRecordsOutputTypeDef](./type_defs.md#listincidentrecordsoutputtypedef).

<a id="list_related_items"></a>

### list_related_items

List all related items for an incident record.

Type annotations for
`aiobotocore.create_client("ssm-incidents").list_related_items` method.

Boto3 documentation:
[SSMIncidents.Client.list_related_items](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.list_related_items)

Asynchronous method. Use `await list_related_items(...)` for a synchronous
call.

Arguments mapping described in
[ListRelatedItemsInputRequestTypeDef](./type_defs.md#listrelateditemsinputrequesttypedef).

Keyword-only arguments:

- `incidentRecordArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListRelatedItemsOutputTypeDef](./type_defs.md#listrelateditemsoutputtypedef).

<a id="list_replication_sets"></a>

### list_replication_sets

Lists details about the replication set configured in your account.

Type annotations for
`aiobotocore.create_client("ssm-incidents").list_replication_sets` method.

Boto3 documentation:
[SSMIncidents.Client.list_replication_sets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.list_replication_sets)

Asynchronous method. Use `await list_replication_sets(...)` for a synchronous
call.

Arguments mapping described in
[ListReplicationSetsInputRequestTypeDef](./type_defs.md#listreplicationsetsinputrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListReplicationSetsOutputTypeDef](./type_defs.md#listreplicationsetsoutputtypedef).

<a id="list_response_plans"></a>

### list_response_plans

Lists all response plans in your account.

Type annotations for
`aiobotocore.create_client("ssm-incidents").list_response_plans` method.

Boto3 documentation:
[SSMIncidents.Client.list_response_plans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.list_response_plans)

Asynchronous method. Use `await list_response_plans(...)` for a synchronous
call.

Arguments mapping described in
[ListResponsePlansInputRequestTypeDef](./type_defs.md#listresponseplansinputrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListResponsePlansOutputTypeDef](./type_defs.md#listresponseplansoutputtypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags that are attached to the specified response plan.

Type annotations for
`aiobotocore.create_client("ssm-incidents").list_tags_for_resource` method.

Boto3 documentation:
[SSMIncidents.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list_timeline_events"></a>

### list_timeline_events

Lists timeline events for the specified incident record.

Type annotations for
`aiobotocore.create_client("ssm-incidents").list_timeline_events` method.

Boto3 documentation:
[SSMIncidents.Client.list_timeline_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.list_timeline_events)

Asynchronous method. Use `await list_timeline_events(...)` for a synchronous
call.

Arguments mapping described in
[ListTimelineEventsInputRequestTypeDef](./type_defs.md#listtimelineeventsinputrequesttypedef).

Keyword-only arguments:

- `incidentRecordArn`: `str` *(required)*
- `filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `sortBy`: `Literal['EVENT_TIME']` (see
  [TimelineEventSortType](./literals.md#timelineeventsorttype))
- `sortOrder`: [SortOrderType](./literals.md#sortordertype)

Returns a `Coroutine` for
[ListTimelineEventsOutputTypeDef](./type_defs.md#listtimelineeventsoutputtypedef).

<a id="put_resource_policy"></a>

### put_resource_policy

Adds a resource policy to the specified response plan.

Type annotations for
`aiobotocore.create_client("ssm-incidents").put_resource_policy` method.

Boto3 documentation:
[SSMIncidents.Client.put_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.put_resource_policy)

Asynchronous method. Use `await put_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutResourcePolicyInputRequestTypeDef](./type_defs.md#putresourcepolicyinputrequesttypedef).

Keyword-only arguments:

- `policy`: `str` *(required)*
- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[PutResourcePolicyOutputTypeDef](./type_defs.md#putresourcepolicyoutputtypedef).

<a id="start_incident"></a>

### start_incident

Used to start an incident from CloudWatch alarms, EventBridge events, or
manually.

Type annotations for
`aiobotocore.create_client("ssm-incidents").start_incident` method.

Boto3 documentation:
[SSMIncidents.Client.start_incident](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.start_incident)

Asynchronous method. Use `await start_incident(...)` for a synchronous call.

Arguments mapping described in
[StartIncidentInputRequestTypeDef](./type_defs.md#startincidentinputrequesttypedef).

Keyword-only arguments:

- `responsePlanArn`: `str` *(required)*
- `clientToken`: `str`
- `impact`: `int`
- `relatedItems`:
  `Sequence`\[[RelatedItemTypeDef](./type_defs.md#relateditemtypedef)\]
- `title`: `str`
- `triggerDetails`:
  [TriggerDetailsTypeDef](./type_defs.md#triggerdetailstypedef)

Returns a `Coroutine` for
[StartIncidentOutputTypeDef](./type_defs.md#startincidentoutputtypedef).

<a id="tag_resource"></a>

### tag_resource

Adds a tag to a response plan.

Type annotations for `aiobotocore.create_client("ssm-incidents").tag_resource`
method.

Boto3 documentation:
[SSMIncidents.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes a tag from a resource.

Type annotations for
`aiobotocore.create_client("ssm-incidents").untag_resource` method.

Boto3 documentation:
[SSMIncidents.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_deletion_protection"></a>

### update_deletion_protection

Update deletion protection to either allow or deny deletion of the final Region
in a replication set.

Type annotations for
`aiobotocore.create_client("ssm-incidents").update_deletion_protection` method.

Boto3 documentation:
[SSMIncidents.Client.update_deletion_protection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.update_deletion_protection)

Asynchronous method. Use `await update_deletion_protection(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDeletionProtectionInputRequestTypeDef](./type_defs.md#updatedeletionprotectioninputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*
- `deletionProtected`: `bool` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_incident_record"></a>

### update_incident_record

Update the details of an incident record.

Type annotations for
`aiobotocore.create_client("ssm-incidents").update_incident_record` method.

Boto3 documentation:
[SSMIncidents.Client.update_incident_record](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.update_incident_record)

Asynchronous method. Use `await update_incident_record(...)` for a synchronous
call.

Arguments mapping described in
[UpdateIncidentRecordInputRequestTypeDef](./type_defs.md#updateincidentrecordinputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*
- `chatChannel`: [ChatChannelTypeDef](./type_defs.md#chatchanneltypedef)
- `clientToken`: `str`
- `impact`: `int`
- `notificationTargets`:
  `Sequence`\[[NotificationTargetItemTypeDef](./type_defs.md#notificationtargetitemtypedef)\]
- `status`: [IncidentRecordStatusType](./literals.md#incidentrecordstatustype)
- `summary`: `str`
- `title`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_related_items"></a>

### update_related_items

Add or remove related items from the related items tab of an incident record.

Type annotations for
`aiobotocore.create_client("ssm-incidents").update_related_items` method.

Boto3 documentation:
[SSMIncidents.Client.update_related_items](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.update_related_items)

Asynchronous method. Use `await update_related_items(...)` for a synchronous
call.

Arguments mapping described in
[UpdateRelatedItemsInputRequestTypeDef](./type_defs.md#updaterelateditemsinputrequesttypedef).

Keyword-only arguments:

- `incidentRecordArn`: `str` *(required)*
- `relatedItemsUpdate`:
  [RelatedItemsUpdateTypeDef](./type_defs.md#relateditemsupdatetypedef)
  *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_replication_set"></a>

### update_replication_set

Add or delete Regions from your replication set.

Type annotations for
`aiobotocore.create_client("ssm-incidents").update_replication_set` method.

Boto3 documentation:
[SSMIncidents.Client.update_replication_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.update_replication_set)

Asynchronous method. Use `await update_replication_set(...)` for a synchronous
call.

Arguments mapping described in
[UpdateReplicationSetInputRequestTypeDef](./type_defs.md#updatereplicationsetinputrequesttypedef).

Keyword-only arguments:

- `actions`:
  `Sequence`\[[UpdateReplicationSetActionTypeDef](./type_defs.md#updatereplicationsetactiontypedef)\]
  *(required)*
- `arn`: `str` *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_response_plan"></a>

### update_response_plan

Updates the specified response plan.

Type annotations for
`aiobotocore.create_client("ssm-incidents").update_response_plan` method.

Boto3 documentation:
[SSMIncidents.Client.update_response_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.update_response_plan)

Asynchronous method. Use `await update_response_plan(...)` for a synchronous
call.

Arguments mapping described in
[UpdateResponsePlanInputRequestTypeDef](./type_defs.md#updateresponseplaninputrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*
- `actions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]
- `chatChannel`: [ChatChannelTypeDef](./type_defs.md#chatchanneltypedef)
- `clientToken`: `str`
- `displayName`: `str`
- `engagements`: `Sequence`\[`str`\]
- `incidentTemplateDedupeString`: `str`
- `incidentTemplateImpact`: `int`
- `incidentTemplateNotificationTargets`:
  `Sequence`\[[NotificationTargetItemTypeDef](./type_defs.md#notificationtargetitemtypedef)\]
- `incidentTemplateSummary`: `str`
- `incidentTemplateTitle`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_timeline_event"></a>

### update_timeline_event

Updates a timeline event.

Type annotations for
`aiobotocore.create_client("ssm-incidents").update_timeline_event` method.

Boto3 documentation:
[SSMIncidents.Client.update_timeline_event](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Client.update_timeline_event)

Asynchronous method. Use `await update_timeline_event(...)` for a synchronous
call.

Arguments mapping described in
[UpdateTimelineEventInputRequestTypeDef](./type_defs.md#updatetimelineeventinputrequesttypedef).

Keyword-only arguments:

- `eventId`: `str` *(required)*
- `incidentRecordArn`: `str` *(required)*
- `clientToken`: `str`
- `eventData`: `str`
- `eventTime`: `Union`\[`datetime`, `str`\]
- `eventType`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("ssm-incidents").get_paginator`
method with overloads.

- `client.get_paginator("get_resource_policies")` ->
  [GetResourcePoliciesPaginator](./paginators.md#getresourcepoliciespaginator)
- `client.get_paginator("list_incident_records")` ->
  [ListIncidentRecordsPaginator](./paginators.md#listincidentrecordspaginator)
- `client.get_paginator("list_related_items")` ->
  [ListRelatedItemsPaginator](./paginators.md#listrelateditemspaginator)
- `client.get_paginator("list_replication_sets")` ->
  [ListReplicationSetsPaginator](./paginators.md#listreplicationsetspaginator)
- `client.get_paginator("list_response_plans")` ->
  [ListResponsePlansPaginator](./paginators.md#listresponseplanspaginator)
- `client.get_paginator("list_timeline_events")` ->
  [ListTimelineEventsPaginator](./paginators.md#listtimelineeventspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `aiobotocore.create_client("ssm-incidents").get_waiter`
method with overloads.

- `client.get_waiter("wait_for_replication_set_active")` ->
  [WaitForReplicationSetActiveWaiter](./waiters.md#waitforreplicationsetactivewaiter)
- `client.get_waiter("wait_for_replication_set_deleted")` ->
  [WaitForReplicationSetDeletedWaiter](./waiters.md#waitforreplicationsetdeletedwaiter)
