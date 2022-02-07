<a id="type-annotations-for-aiobotocore-ssmincidents-module"></a>

# Type annotations for aiobotocore SSMIncidents module

> [Index](..) > SSMIncidents

Auto-generated documentation for
[SSMIncidents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
type annotations stubs module
[types-aiobotocore-ssm-incidents](https://pypi.org/project/types-aiobotocore-ssm-incidents/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[ssm-incidents]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[ssm-incidents]'

# standalone installation
pip install types-aiobotocore-ssm-incidents
```

- [Type annotations for aiobotocore SSMIncidents module](#type-annotations-for-aiobotocore-ssmincidents-module)
  - [SSMIncidentsClient](#ssmincidentsclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Waiters](#waiters)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="ssmincidentsclient"></a>

## SSMIncidentsClient

Type annotations for `session.create_client("ssm-incidents")` as
[SSMIncidentsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_ssm_incidents.client import SSMIncidentsClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [create_replication_set](./client.md#create_replication_set)
- [create_response_plan](./client.md#create_response_plan)
- [create_timeline_event](./client.md#create_timeline_event)
- [delete_incident_record](./client.md#delete_incident_record)
- [delete_replication_set](./client.md#delete_replication_set)
- [delete_resource_policy](./client.md#delete_resource_policy)
- [delete_response_plan](./client.md#delete_response_plan)
- [delete_timeline_event](./client.md#delete_timeline_event)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_incident_record](./client.md#get_incident_record)
- [get_paginator](./client.md#get_paginator)
- [get_replication_set](./client.md#get_replication_set)
- [get_resource_policies](./client.md#get_resource_policies)
- [get_response_plan](./client.md#get_response_plan)
- [get_timeline_event](./client.md#get_timeline_event)
- [get_waiter](./client.md#get_waiter)
- [list_incident_records](./client.md#list_incident_records)
- [list_related_items](./client.md#list_related_items)
- [list_replication_sets](./client.md#list_replication_sets)
- [list_response_plans](./client.md#list_response_plans)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [list_timeline_events](./client.md#list_timeline_events)
- [put_resource_policy](./client.md#put_resource_policy)
- [start_incident](./client.md#start_incident)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_deletion_protection](./client.md#update_deletion_protection)
- [update_incident_record](./client.md#update_incident_record)
- [update_related_items](./client.md#update_related_items)
- [update_replication_set](./client.md#update_replication_set)
- [update_response_plan](./client.md#update_response_plan)
- [update_timeline_event](./client.md#update_timeline_event)

<a id="exceptions"></a>

### Exceptions

SSMIncidentsClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- ConflictException
- InternalServerException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ThrottlingException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("ssm-incidents").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_ssm_incidents.paginator import GetResourcePoliciesPaginator, ...
```

- [GetResourcePoliciesPaginator](./paginators.md#getresourcepoliciespaginator)
- [ListIncidentRecordsPaginator](./paginators.md#listincidentrecordspaginator)
- [ListRelatedItemsPaginator](./paginators.md#listrelateditemspaginator)
- [ListReplicationSetsPaginator](./paginators.md#listreplicationsetspaginator)
- [ListResponsePlansPaginator](./paginators.md#listresponseplanspaginator)
- [ListTimelineEventsPaginator](./paginators.md#listtimelineeventspaginator)

<a id="waiters"></a>

## Waiters

Type annotations for [waiters](./waiters.md) from
`boto3.client("ssm-incidents").get_waiter("...")`.

Can be used directly:

```python
from types_aiobotocore_ssm_incidents.waiter import WaitForReplicationSetActiveWaiter, ...
```

- [WaitForReplicationSetActiveWaiter](./waiters.md#waitforreplicationsetactivewaiter)
- [WaitForReplicationSetDeletedWaiter](./waiters.md#waitforreplicationsetdeletedwaiter)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_ssm_incidents.literals import GetResourcePoliciesPaginatorName, ...
```

- [GetResourcePoliciesPaginatorName](./literals.md#getresourcepoliciespaginatorname)
- [IncidentRecordStatusType](./literals.md#incidentrecordstatustype)
- [ItemTypeType](./literals.md#itemtypetype)
- [ListIncidentRecordsPaginatorName](./literals.md#listincidentrecordspaginatorname)
- [ListRelatedItemsPaginatorName](./literals.md#listrelateditemspaginatorname)
- [ListReplicationSetsPaginatorName](./literals.md#listreplicationsetspaginatorname)
- [ListResponsePlansPaginatorName](./literals.md#listresponseplanspaginatorname)
- [ListTimelineEventsPaginatorName](./literals.md#listtimelineeventspaginatorname)
- [RegionStatusType](./literals.md#regionstatustype)
- [ReplicationSetStatusType](./literals.md#replicationsetstatustype)
- [SortOrderType](./literals.md#sortordertype)
- [SsmTargetAccountType](./literals.md#ssmtargetaccounttype)
- [TimelineEventSortType](./literals.md#timelineeventsorttype)
- [WaitForReplicationSetActiveWaiterName](./literals.md#waitforreplicationsetactivewaitername)
- [WaitForReplicationSetDeletedWaiterName](./literals.md#waitforreplicationsetdeletedwaitername)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)
- [WaiterName](./literals.md#waitername)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_ssm_incidents.type_defs import ActionTypeDef, ...
```

- [ActionTypeDef](./type_defs.md#actiontypedef)
- [AddRegionActionTypeDef](./type_defs.md#addregionactiontypedef)
- [AttributeValueListTypeDef](./type_defs.md#attributevaluelisttypedef)
- [AutomationExecutionTypeDef](./type_defs.md#automationexecutiontypedef)
- [ChatChannelTypeDef](./type_defs.md#chatchanneltypedef)
- [ConditionTypeDef](./type_defs.md#conditiontypedef)
- [CreateReplicationSetInputRequestTypeDef](./type_defs.md#createreplicationsetinputrequesttypedef)
- [CreateReplicationSetOutputTypeDef](./type_defs.md#createreplicationsetoutputtypedef)
- [CreateResponsePlanInputRequestTypeDef](./type_defs.md#createresponseplaninputrequesttypedef)
- [CreateResponsePlanOutputTypeDef](./type_defs.md#createresponseplanoutputtypedef)
- [CreateTimelineEventInputRequestTypeDef](./type_defs.md#createtimelineeventinputrequesttypedef)
- [CreateTimelineEventOutputTypeDef](./type_defs.md#createtimelineeventoutputtypedef)
- [DeleteIncidentRecordInputRequestTypeDef](./type_defs.md#deleteincidentrecordinputrequesttypedef)
- [DeleteRegionActionTypeDef](./type_defs.md#deleteregionactiontypedef)
- [DeleteReplicationSetInputRequestTypeDef](./type_defs.md#deletereplicationsetinputrequesttypedef)
- [DeleteResourcePolicyInputRequestTypeDef](./type_defs.md#deleteresourcepolicyinputrequesttypedef)
- [DeleteResponsePlanInputRequestTypeDef](./type_defs.md#deleteresponseplaninputrequesttypedef)
- [DeleteTimelineEventInputRequestTypeDef](./type_defs.md#deletetimelineeventinputrequesttypedef)
- [EventSummaryTypeDef](./type_defs.md#eventsummarytypedef)
- [FilterTypeDef](./type_defs.md#filtertypedef)
- [GetIncidentRecordInputRequestTypeDef](./type_defs.md#getincidentrecordinputrequesttypedef)
- [GetIncidentRecordOutputTypeDef](./type_defs.md#getincidentrecordoutputtypedef)
- [GetReplicationSetInputRequestTypeDef](./type_defs.md#getreplicationsetinputrequesttypedef)
- [GetReplicationSetOutputTypeDef](./type_defs.md#getreplicationsetoutputtypedef)
- [GetResourcePoliciesInputRequestTypeDef](./type_defs.md#getresourcepoliciesinputrequesttypedef)
- [GetResourcePoliciesOutputTypeDef](./type_defs.md#getresourcepoliciesoutputtypedef)
- [GetResponsePlanInputRequestTypeDef](./type_defs.md#getresponseplaninputrequesttypedef)
- [GetResponsePlanOutputTypeDef](./type_defs.md#getresponseplanoutputtypedef)
- [GetTimelineEventInputRequestTypeDef](./type_defs.md#gettimelineeventinputrequesttypedef)
- [GetTimelineEventOutputTypeDef](./type_defs.md#gettimelineeventoutputtypedef)
- [IncidentRecordSourceTypeDef](./type_defs.md#incidentrecordsourcetypedef)
- [IncidentRecordSummaryTypeDef](./type_defs.md#incidentrecordsummarytypedef)
- [IncidentRecordTypeDef](./type_defs.md#incidentrecordtypedef)
- [IncidentTemplateTypeDef](./type_defs.md#incidenttemplatetypedef)
- [ItemIdentifierTypeDef](./type_defs.md#itemidentifiertypedef)
- [ItemValueTypeDef](./type_defs.md#itemvaluetypedef)
- [ListIncidentRecordsInputRequestTypeDef](./type_defs.md#listincidentrecordsinputrequesttypedef)
- [ListIncidentRecordsOutputTypeDef](./type_defs.md#listincidentrecordsoutputtypedef)
- [ListRelatedItemsInputRequestTypeDef](./type_defs.md#listrelateditemsinputrequesttypedef)
- [ListRelatedItemsOutputTypeDef](./type_defs.md#listrelateditemsoutputtypedef)
- [ListReplicationSetsInputRequestTypeDef](./type_defs.md#listreplicationsetsinputrequesttypedef)
- [ListReplicationSetsOutputTypeDef](./type_defs.md#listreplicationsetsoutputtypedef)
- [ListResponsePlansInputRequestTypeDef](./type_defs.md#listresponseplansinputrequesttypedef)
- [ListResponsePlansOutputTypeDef](./type_defs.md#listresponseplansoutputtypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListTimelineEventsInputRequestTypeDef](./type_defs.md#listtimelineeventsinputrequesttypedef)
- [ListTimelineEventsOutputTypeDef](./type_defs.md#listtimelineeventsoutputtypedef)
- [NotificationTargetItemTypeDef](./type_defs.md#notificationtargetitemtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PutResourcePolicyInputRequestTypeDef](./type_defs.md#putresourcepolicyinputrequesttypedef)
- [PutResourcePolicyOutputTypeDef](./type_defs.md#putresourcepolicyoutputtypedef)
- [RegionInfoTypeDef](./type_defs.md#regioninfotypedef)
- [RegionMapInputValueTypeDef](./type_defs.md#regionmapinputvaluetypedef)
- [RelatedItemTypeDef](./type_defs.md#relateditemtypedef)
- [RelatedItemsUpdateTypeDef](./type_defs.md#relateditemsupdatetypedef)
- [ReplicationSetTypeDef](./type_defs.md#replicationsettypedef)
- [ResourcePolicyTypeDef](./type_defs.md#resourcepolicytypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ResponsePlanSummaryTypeDef](./type_defs.md#responseplansummarytypedef)
- [SsmAutomationTypeDef](./type_defs.md#ssmautomationtypedef)
- [StartIncidentInputRequestTypeDef](./type_defs.md#startincidentinputrequesttypedef)
- [StartIncidentOutputTypeDef](./type_defs.md#startincidentoutputtypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TimelineEventTypeDef](./type_defs.md#timelineeventtypedef)
- [TriggerDetailsTypeDef](./type_defs.md#triggerdetailstypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateDeletionProtectionInputRequestTypeDef](./type_defs.md#updatedeletionprotectioninputrequesttypedef)
- [UpdateIncidentRecordInputRequestTypeDef](./type_defs.md#updateincidentrecordinputrequesttypedef)
- [UpdateRelatedItemsInputRequestTypeDef](./type_defs.md#updaterelateditemsinputrequesttypedef)
- [UpdateReplicationSetActionTypeDef](./type_defs.md#updatereplicationsetactiontypedef)
- [UpdateReplicationSetInputRequestTypeDef](./type_defs.md#updatereplicationsetinputrequesttypedef)
- [UpdateResponsePlanInputRequestTypeDef](./type_defs.md#updateresponseplaninputrequesttypedef)
- [UpdateTimelineEventInputRequestTypeDef](./type_defs.md#updatetimelineeventinputrequesttypedef)
- [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
