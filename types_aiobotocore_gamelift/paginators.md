<a id="paginators-for-aiobotocore-gamelift-module"></a>

# Paginators for aiobotocore GameLift module

> [Index](..) > [GameLift](.) > Paginators

Auto-generated documentation for
[GameLift](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift)
type annotations stubs module
[types-aiobotocore-gamelift](https://pypi.org/project/types-aiobotocore-gamelift/).

- [Paginators for aiobotocore GameLift module](#paginators-for-aiobotocore-gamelift-module)
  - [DescribeFleetAttributesPaginator](#describefleetattributespaginator)
  - [DescribeFleetCapacityPaginator](#describefleetcapacitypaginator)
  - [DescribeFleetEventsPaginator](#describefleeteventspaginator)
  - [DescribeFleetUtilizationPaginator](#describefleetutilizationpaginator)
  - [DescribeGameServerInstancesPaginator](#describegameserverinstancespaginator)
  - [DescribeGameSessionDetailsPaginator](#describegamesessiondetailspaginator)
  - [DescribeGameSessionQueuesPaginator](#describegamesessionqueuespaginator)
  - [DescribeGameSessionsPaginator](#describegamesessionspaginator)
  - [DescribeInstancesPaginator](#describeinstancespaginator)
  - [DescribeMatchmakingConfigurationsPaginator](#describematchmakingconfigurationspaginator)
  - [DescribeMatchmakingRuleSetsPaginator](#describematchmakingrulesetspaginator)
  - [DescribePlayerSessionsPaginator](#describeplayersessionspaginator)
  - [DescribeScalingPoliciesPaginator](#describescalingpoliciespaginator)
  - [ListAliasesPaginator](#listaliasespaginator)
  - [ListBuildsPaginator](#listbuildspaginator)
  - [ListFleetsPaginator](#listfleetspaginator)
  - [ListGameServerGroupsPaginator](#listgameservergroupspaginator)
  - [ListGameServersPaginator](#listgameserverspaginator)
  - [ListScriptsPaginator](#listscriptspaginator)
  - [SearchGameSessionsPaginator](#searchgamesessionspaginator)

<a id="describefleetattributespaginator"></a>

## DescribeFleetAttributesPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_fleet_attributes")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeFleetAttributesPaginator

def get_describe_fleet_attributes_paginator() -> DescribeFleetAttributesPaginator:
    return Session().create_client("gamelift").get_paginator("describe_fleet_attributes")
```

Boto3 documentation:
[GameLift.Paginator.DescribeFleetAttributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetAttributes)

Arguments for `DescribeFleetAttributesPaginator.paginate` method:

- `FleetIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFleetAttributesPaginator.paginate` returns
`_PageIterator`\[[DescribeFleetAttributesOutputTypeDef](./type_defs.md#describefleetattributesoutputtypedef)\].

<a id="describefleetcapacitypaginator"></a>

## DescribeFleetCapacityPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_fleet_capacity")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeFleetCapacityPaginator

def get_describe_fleet_capacity_paginator() -> DescribeFleetCapacityPaginator:
    return Session().create_client("gamelift").get_paginator("describe_fleet_capacity")
```

Boto3 documentation:
[GameLift.Paginator.DescribeFleetCapacity](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetCapacity)

Arguments for `DescribeFleetCapacityPaginator.paginate` method:

- `FleetIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFleetCapacityPaginator.paginate` returns
`_PageIterator`\[[DescribeFleetCapacityOutputTypeDef](./type_defs.md#describefleetcapacityoutputtypedef)\].

<a id="describefleeteventspaginator"></a>

## DescribeFleetEventsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_fleet_events")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeFleetEventsPaginator

def get_describe_fleet_events_paginator() -> DescribeFleetEventsPaginator:
    return Session().create_client("gamelift").get_paginator("describe_fleet_events")
```

Boto3 documentation:
[GameLift.Paginator.DescribeFleetEvents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetEvents)

Arguments for `DescribeFleetEventsPaginator.paginate` method:

- `FleetId`: `str` *(required)*
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFleetEventsPaginator.paginate` returns
`_PageIterator`\[[DescribeFleetEventsOutputTypeDef](./type_defs.md#describefleeteventsoutputtypedef)\].

<a id="describefleetutilizationpaginator"></a>

## DescribeFleetUtilizationPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_fleet_utilization")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeFleetUtilizationPaginator

def get_describe_fleet_utilization_paginator() -> DescribeFleetUtilizationPaginator:
    return Session().create_client("gamelift").get_paginator("describe_fleet_utilization")
```

Boto3 documentation:
[GameLift.Paginator.DescribeFleetUtilization](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetUtilization)

Arguments for `DescribeFleetUtilizationPaginator.paginate` method:

- `FleetIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeFleetUtilizationPaginator.paginate` returns
`_PageIterator`\[[DescribeFleetUtilizationOutputTypeDef](./type_defs.md#describefleetutilizationoutputtypedef)\].

<a id="describegameserverinstancespaginator"></a>

## DescribeGameServerInstancesPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_game_server_instances")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeGameServerInstancesPaginator

def get_describe_game_server_instances_paginator() -> DescribeGameServerInstancesPaginator:
    return Session().create_client("gamelift").get_paginator("describe_game_server_instances")
```

Boto3 documentation:
[GameLift.Paginator.DescribeGameServerInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameServerInstances)

Arguments for `DescribeGameServerInstancesPaginator.paginate` method:

- `GameServerGroupName`: `str` *(required)*
- `InstanceIds`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeGameServerInstancesPaginator.paginate` returns
`_PageIterator`\[[DescribeGameServerInstancesOutputTypeDef](./type_defs.md#describegameserverinstancesoutputtypedef)\].

<a id="describegamesessiondetailspaginator"></a>

## DescribeGameSessionDetailsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_game_session_details")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeGameSessionDetailsPaginator

def get_describe_game_session_details_paginator() -> DescribeGameSessionDetailsPaginator:
    return Session().create_client("gamelift").get_paginator("describe_game_session_details")
```

Boto3 documentation:
[GameLift.Paginator.DescribeGameSessionDetails](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionDetails)

Arguments for `DescribeGameSessionDetailsPaginator.paginate` method:

- `FleetId`: `str`
- `GameSessionId`: `str`
- `AliasId`: `str`
- `Location`: `str`
- `StatusFilter`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeGameSessionDetailsPaginator.paginate` returns
`_PageIterator`\[[DescribeGameSessionDetailsOutputTypeDef](./type_defs.md#describegamesessiondetailsoutputtypedef)\].

<a id="describegamesessionqueuespaginator"></a>

## DescribeGameSessionQueuesPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_game_session_queues")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeGameSessionQueuesPaginator

def get_describe_game_session_queues_paginator() -> DescribeGameSessionQueuesPaginator:
    return Session().create_client("gamelift").get_paginator("describe_game_session_queues")
```

Boto3 documentation:
[GameLift.Paginator.DescribeGameSessionQueues](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionQueues)

Arguments for `DescribeGameSessionQueuesPaginator.paginate` method:

- `Names`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeGameSessionQueuesPaginator.paginate` returns
`_PageIterator`\[[DescribeGameSessionQueuesOutputTypeDef](./type_defs.md#describegamesessionqueuesoutputtypedef)\].

<a id="describegamesessionspaginator"></a>

## DescribeGameSessionsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_game_sessions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeGameSessionsPaginator

def get_describe_game_sessions_paginator() -> DescribeGameSessionsPaginator:
    return Session().create_client("gamelift").get_paginator("describe_game_sessions")
```

Boto3 documentation:
[GameLift.Paginator.DescribeGameSessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessions)

Arguments for `DescribeGameSessionsPaginator.paginate` method:

- `FleetId`: `str`
- `GameSessionId`: `str`
- `AliasId`: `str`
- `Location`: `str`
- `StatusFilter`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeGameSessionsPaginator.paginate` returns
`_PageIterator`\[[DescribeGameSessionsOutputTypeDef](./type_defs.md#describegamesessionsoutputtypedef)\].

<a id="describeinstancespaginator"></a>

## DescribeInstancesPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_instances")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeInstancesPaginator

def get_describe_instances_paginator() -> DescribeInstancesPaginator:
    return Session().create_client("gamelift").get_paginator("describe_instances")
```

Boto3 documentation:
[GameLift.Paginator.DescribeInstances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeInstances)

Arguments for `DescribeInstancesPaginator.paginate` method:

- `FleetId`: `str` *(required)*
- `InstanceId`: `str`
- `Location`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstancesPaginator.paginate` returns
`_PageIterator`\[[DescribeInstancesOutputTypeDef](./type_defs.md#describeinstancesoutputtypedef)\].

<a id="describematchmakingconfigurationspaginator"></a>

## DescribeMatchmakingConfigurationsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_matchmaking_configurations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeMatchmakingConfigurationsPaginator

def get_describe_matchmaking_configurations_paginator() -> DescribeMatchmakingConfigurationsPaginator:
    return Session().create_client("gamelift").get_paginator("describe_matchmaking_configurations")
```

Boto3 documentation:
[GameLift.Paginator.DescribeMatchmakingConfigurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingConfigurations)

Arguments for `DescribeMatchmakingConfigurationsPaginator.paginate` method:

- `Names`: `Sequence`\[`str`\]
- `RuleSetName`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMatchmakingConfigurationsPaginator.paginate` returns
`_PageIterator`\[[DescribeMatchmakingConfigurationsOutputTypeDef](./type_defs.md#describematchmakingconfigurationsoutputtypedef)\].

<a id="describematchmakingrulesetspaginator"></a>

## DescribeMatchmakingRuleSetsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_matchmaking_rule_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeMatchmakingRuleSetsPaginator

def get_describe_matchmaking_rule_sets_paginator() -> DescribeMatchmakingRuleSetsPaginator:
    return Session().create_client("gamelift").get_paginator("describe_matchmaking_rule_sets")
```

Boto3 documentation:
[GameLift.Paginator.DescribeMatchmakingRuleSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingRuleSets)

Arguments for `DescribeMatchmakingRuleSetsPaginator.paginate` method:

- `Names`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMatchmakingRuleSetsPaginator.paginate` returns
`_PageIterator`\[[DescribeMatchmakingRuleSetsOutputTypeDef](./type_defs.md#describematchmakingrulesetsoutputtypedef)\].

<a id="describeplayersessionspaginator"></a>

## DescribePlayerSessionsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_player_sessions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribePlayerSessionsPaginator

def get_describe_player_sessions_paginator() -> DescribePlayerSessionsPaginator:
    return Session().create_client("gamelift").get_paginator("describe_player_sessions")
```

Boto3 documentation:
[GameLift.Paginator.DescribePlayerSessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribePlayerSessions)

Arguments for `DescribePlayerSessionsPaginator.paginate` method:

- `GameSessionId`: `str`
- `PlayerId`: `str`
- `PlayerSessionId`: `str`
- `PlayerSessionStatusFilter`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePlayerSessionsPaginator.paginate` returns
`_PageIterator`\[[DescribePlayerSessionsOutputTypeDef](./type_defs.md#describeplayersessionsoutputtypedef)\].

<a id="describescalingpoliciespaginator"></a>

## DescribeScalingPoliciesPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("describe_scaling_policies")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import DescribeScalingPoliciesPaginator

def get_describe_scaling_policies_paginator() -> DescribeScalingPoliciesPaginator:
    return Session().create_client("gamelift").get_paginator("describe_scaling_policies")
```

Boto3 documentation:
[GameLift.Paginator.DescribeScalingPolicies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeScalingPolicies)

Arguments for `DescribeScalingPoliciesPaginator.paginate` method:

- `FleetId`: `str` *(required)*
- `StatusFilter`: [ScalingStatusTypeType](./literals.md#scalingstatustypetype)
- `Location`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeScalingPoliciesPaginator.paginate` returns
`_PageIterator`\[[DescribeScalingPoliciesOutputTypeDef](./type_defs.md#describescalingpoliciesoutputtypedef)\].

<a id="listaliasespaginator"></a>

## ListAliasesPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("list_aliases")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import ListAliasesPaginator

def get_list_aliases_paginator() -> ListAliasesPaginator:
    return Session().create_client("gamelift").get_paginator("list_aliases")
```

Boto3 documentation:
[GameLift.Paginator.ListAliases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListAliases)

Arguments for `ListAliasesPaginator.paginate` method:

- `RoutingStrategyType`:
  [RoutingStrategyTypeType](./literals.md#routingstrategytypetype)
- `Name`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAliasesPaginator.paginate` returns
`_PageIterator`\[[ListAliasesOutputTypeDef](./type_defs.md#listaliasesoutputtypedef)\].

<a id="listbuildspaginator"></a>

## ListBuildsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("list_builds")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import ListBuildsPaginator

def get_list_builds_paginator() -> ListBuildsPaginator:
    return Session().create_client("gamelift").get_paginator("list_builds")
```

Boto3 documentation:
[GameLift.Paginator.ListBuilds](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListBuilds)

Arguments for `ListBuildsPaginator.paginate` method:

- `Status`: [BuildStatusType](./literals.md#buildstatustype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListBuildsPaginator.paginate` returns
`_PageIterator`\[[ListBuildsOutputTypeDef](./type_defs.md#listbuildsoutputtypedef)\].

<a id="listfleetspaginator"></a>

## ListFleetsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("list_fleets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import ListFleetsPaginator

def get_list_fleets_paginator() -> ListFleetsPaginator:
    return Session().create_client("gamelift").get_paginator("list_fleets")
```

Boto3 documentation:
[GameLift.Paginator.ListFleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListFleets)

Arguments for `ListFleetsPaginator.paginate` method:

- `BuildId`: `str`
- `ScriptId`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListFleetsPaginator.paginate` returns
`_PageIterator`\[[ListFleetsOutputTypeDef](./type_defs.md#listfleetsoutputtypedef)\].

<a id="listgameservergroupspaginator"></a>

## ListGameServerGroupsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("list_game_server_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import ListGameServerGroupsPaginator

def get_list_game_server_groups_paginator() -> ListGameServerGroupsPaginator:
    return Session().create_client("gamelift").get_paginator("list_game_server_groups")
```

Boto3 documentation:
[GameLift.Paginator.ListGameServerGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServerGroups)

Arguments for `ListGameServerGroupsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGameServerGroupsPaginator.paginate` returns
`_PageIterator`\[[ListGameServerGroupsOutputTypeDef](./type_defs.md#listgameservergroupsoutputtypedef)\].

<a id="listgameserverspaginator"></a>

## ListGameServersPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("list_game_servers")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import ListGameServersPaginator

def get_list_game_servers_paginator() -> ListGameServersPaginator:
    return Session().create_client("gamelift").get_paginator("list_game_servers")
```

Boto3 documentation:
[GameLift.Paginator.ListGameServers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServers)

Arguments for `ListGameServersPaginator.paginate` method:

- `GameServerGroupName`: `str` *(required)*
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGameServersPaginator.paginate` returns
`_PageIterator`\[[ListGameServersOutputTypeDef](./type_defs.md#listgameserversoutputtypedef)\].

<a id="listscriptspaginator"></a>

## ListScriptsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("list_scripts")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import ListScriptsPaginator

def get_list_scripts_paginator() -> ListScriptsPaginator:
    return Session().create_client("gamelift").get_paginator("list_scripts")
```

Boto3 documentation:
[GameLift.Paginator.ListScripts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListScripts)

Arguments for `ListScriptsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListScriptsPaginator.paginate` returns
`_PageIterator`\[[ListScriptsOutputTypeDef](./type_defs.md#listscriptsoutputtypedef)\].

<a id="searchgamesessionspaginator"></a>

## SearchGameSessionsPaginator

Type annotations for
`aiobotocore.create_client("gamelift").get_paginator("search_game_sessions")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_gamelift.paginator import SearchGameSessionsPaginator

def get_search_game_sessions_paginator() -> SearchGameSessionsPaginator:
    return Session().create_client("gamelift").get_paginator("search_game_sessions")
```

Boto3 documentation:
[GameLift.Paginator.SearchGameSessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.SearchGameSessions)

Arguments for `SearchGameSessionsPaginator.paginate` method:

- `FleetId`: `str`
- `AliasId`: `str`
- `Location`: `str`
- `FilterExpression`: `str`
- `SortExpression`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`SearchGameSessionsPaginator.paginate` returns
`_PageIterator`\[[SearchGameSessionsOutputTypeDef](./type_defs.md#searchgamesessionsoutputtypedef)\].
