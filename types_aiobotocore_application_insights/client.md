<a id="applicationinsightsclient-for-aiobotocore-applicationinsights-module"></a>

# ApplicationInsightsClient for aiobotocore ApplicationInsights module

> [Index](..) > [ApplicationInsights](.) > ApplicationInsightsClient

Auto-generated documentation for
[ApplicationInsights](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
type annotations stubs module
[types-aiobotocore-application-insights](https://pypi.org/project/types-aiobotocore-application-insights/).

- [ApplicationInsightsClient for aiobotocore ApplicationInsights module](#applicationinsightsclient-for-aiobotocore-applicationinsights-module)
  - [ApplicationInsightsClient](#applicationinsightsclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_application](#create_application)
    - [create_component](#create_component)
    - [create_log_pattern](#create_log_pattern)
    - [delete_application](#delete_application)
    - [delete_component](#delete_component)
    - [delete_log_pattern](#delete_log_pattern)
    - [describe_application](#describe_application)
    - [describe_component](#describe_component)
    - [describe_component_configuration](#describe_component_configuration)
    - [describe_component_configuration_recommendation](#describe_component_configuration_recommendation)
    - [describe_log_pattern](#describe_log_pattern)
    - [describe_observation](#describe_observation)
    - [describe_problem](#describe_problem)
    - [describe_problem_observations](#describe_problem_observations)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_applications](#list_applications)
    - [list_components](#list_components)
    - [list_configuration_history](#list_configuration_history)
    - [list_log_pattern_sets](#list_log_pattern_sets)
    - [list_log_patterns](#list_log_patterns)
    - [list_problems](#list_problems)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_application](#update_application)
    - [update_component](#update_component)
    - [update_component_configuration](#update_component_configuration)
    - [update_log_pattern](#update_log_pattern)

<a id="applicationinsightsclient"></a>

## ApplicationInsightsClient

Type annotations for `aiobotocore.create_client("application-insights")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_application_insights.client import ApplicationInsightsClient

def get_application-insights_client() -> ApplicationInsightsClient:
    return Session().client("application-insights")
```

Boto3 documentation:
[ApplicationInsights.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_application_insights.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceInUseException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.TagsAlreadyExistException`
- `Exceptions.TooManyTagsException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ApplicationInsightsClient exceptions.

Type annotations for
`aiobotocore.create_client("application-insights").exceptions` method.

Boto3 documentation:
[ApplicationInsights.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("application-insights").can_paginate` method.

Boto3 documentation:
[ApplicationInsights.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_application"></a>

### create_application

Adds an application that is created from a resource group.

Type annotations for
`aiobotocore.create_client("application-insights").create_application` method.

Boto3 documentation:
[ApplicationInsights.Client.create_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.create_application)

Asynchronous method. Use `await create_application(...)` for a synchronous
call.

Arguments mapping described in
[CreateApplicationRequestRequestTypeDef](./type_defs.md#createapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str`
- `OpsCenterEnabled`: `bool`
- `CWEMonitorEnabled`: `bool`
- `OpsItemSNSTopicArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `AutoConfigEnabled`: `bool`
- `AutoCreate`: `bool`

Returns a `Coroutine` for
[CreateApplicationResponseTypeDef](./type_defs.md#createapplicationresponsetypedef).

<a id="create_component"></a>

### create_component

Creates a custom component by grouping similar standalone instances to monitor.

Type annotations for
`aiobotocore.create_client("application-insights").create_component` method.

Boto3 documentation:
[ApplicationInsights.Client.create_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.create_component)

Asynchronous method. Use `await create_component(...)` for a synchronous call.

Arguments mapping described in
[CreateComponentRequestRequestTypeDef](./type_defs.md#createcomponentrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `ComponentName`: `str` *(required)*
- `ResourceList`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_log_pattern"></a>

### create_log_pattern

Adds an log pattern to a `LogPatternSet` .

Type annotations for
`aiobotocore.create_client("application-insights").create_log_pattern` method.

Boto3 documentation:
[ApplicationInsights.Client.create_log_pattern](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.create_log_pattern)

Asynchronous method. Use `await create_log_pattern(...)` for a synchronous
call.

Arguments mapping described in
[CreateLogPatternRequestRequestTypeDef](./type_defs.md#createlogpatternrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `PatternSetName`: `str` *(required)*
- `PatternName`: `str` *(required)*
- `Pattern`: `str` *(required)*
- `Rank`: `int` *(required)*

Returns a `Coroutine` for
[CreateLogPatternResponseTypeDef](./type_defs.md#createlogpatternresponsetypedef).

<a id="delete_application"></a>

### delete_application

Removes the specified application from monitoring.

Type annotations for
`aiobotocore.create_client("application-insights").delete_application` method.

Boto3 documentation:
[ApplicationInsights.Client.delete_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.delete_application)

Asynchronous method. Use `await delete_application(...)` for a synchronous
call.

Arguments mapping described in
[DeleteApplicationRequestRequestTypeDef](./type_defs.md#deleteapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_component"></a>

### delete_component

Ungroups a custom component.

Type annotations for
`aiobotocore.create_client("application-insights").delete_component` method.

Boto3 documentation:
[ApplicationInsights.Client.delete_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.delete_component)

Asynchronous method. Use `await delete_component(...)` for a synchronous call.

Arguments mapping described in
[DeleteComponentRequestRequestTypeDef](./type_defs.md#deletecomponentrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `ComponentName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_log_pattern"></a>

### delete_log_pattern

Removes the specified log pattern from a `LogPatternSet` .

Type annotations for
`aiobotocore.create_client("application-insights").delete_log_pattern` method.

Boto3 documentation:
[ApplicationInsights.Client.delete_log_pattern](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.delete_log_pattern)

Asynchronous method. Use `await delete_log_pattern(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLogPatternRequestRequestTypeDef](./type_defs.md#deletelogpatternrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `PatternSetName`: `str` *(required)*
- `PatternName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_application"></a>

### describe_application

Describes the application.

Type annotations for
`aiobotocore.create_client("application-insights").describe_application`
method.

Boto3 documentation:
[ApplicationInsights.Client.describe_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_application)

Asynchronous method. Use `await describe_application(...)` for a synchronous
call.

Arguments mapping described in
[DescribeApplicationRequestRequestTypeDef](./type_defs.md#describeapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeApplicationResponseTypeDef](./type_defs.md#describeapplicationresponsetypedef).

<a id="describe_component"></a>

### describe_component

Describes a component and lists the resources that are grouped together in a
component.

Type annotations for
`aiobotocore.create_client("application-insights").describe_component` method.

Boto3 documentation:
[ApplicationInsights.Client.describe_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_component)

Asynchronous method. Use `await describe_component(...)` for a synchronous
call.

Arguments mapping described in
[DescribeComponentRequestRequestTypeDef](./type_defs.md#describecomponentrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `ComponentName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeComponentResponseTypeDef](./type_defs.md#describecomponentresponsetypedef).

<a id="describe_component_configuration"></a>

### describe_component_configuration

Describes the monitoring configuration of the component.

Type annotations for
`aiobotocore.create_client("application-insights").describe_component_configuration`
method.

Boto3 documentation:
[ApplicationInsights.Client.describe_component_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_component_configuration)

Asynchronous method. Use `await describe_component_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DescribeComponentConfigurationRequestRequestTypeDef](./type_defs.md#describecomponentconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `ComponentName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeComponentConfigurationResponseTypeDef](./type_defs.md#describecomponentconfigurationresponsetypedef).

<a id="describe_component_configuration_recommendation"></a>

### describe_component_configuration_recommendation

Describes the recommended monitoring configuration of the component.

Type annotations for
`aiobotocore.create_client("application-insights").describe_component_configuration_recommendation`
method.

Boto3 documentation:
[ApplicationInsights.Client.describe_component_configuration_recommendation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_component_configuration_recommendation)

Asynchronous method. Use
`await describe_component_configuration_recommendation(...)` for a synchronous
call.

Arguments mapping described in
[DescribeComponentConfigurationRecommendationRequestRequestTypeDef](./type_defs.md#describecomponentconfigurationrecommendationrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `ComponentName`: `str` *(required)*
- `Tier`: [TierType](./literals.md#tiertype) *(required)*

Returns a `Coroutine` for
[DescribeComponentConfigurationRecommendationResponseTypeDef](./type_defs.md#describecomponentconfigurationrecommendationresponsetypedef).

<a id="describe_log_pattern"></a>

### describe_log_pattern

Describe a specific log pattern from a `LogPatternSet` .

Type annotations for
`aiobotocore.create_client("application-insights").describe_log_pattern`
method.

Boto3 documentation:
[ApplicationInsights.Client.describe_log_pattern](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_log_pattern)

Asynchronous method. Use `await describe_log_pattern(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLogPatternRequestRequestTypeDef](./type_defs.md#describelogpatternrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `PatternSetName`: `str` *(required)*
- `PatternName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLogPatternResponseTypeDef](./type_defs.md#describelogpatternresponsetypedef).

<a id="describe_observation"></a>

### describe_observation

Describes an anomaly or error with the application.

Type annotations for
`aiobotocore.create_client("application-insights").describe_observation`
method.

Boto3 documentation:
[ApplicationInsights.Client.describe_observation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_observation)

Asynchronous method. Use `await describe_observation(...)` for a synchronous
call.

Arguments mapping described in
[DescribeObservationRequestRequestTypeDef](./type_defs.md#describeobservationrequestrequesttypedef).

Keyword-only arguments:

- `ObservationId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeObservationResponseTypeDef](./type_defs.md#describeobservationresponsetypedef).

<a id="describe_problem"></a>

### describe_problem

Describes an application problem.

Type annotations for
`aiobotocore.create_client("application-insights").describe_problem` method.

Boto3 documentation:
[ApplicationInsights.Client.describe_problem](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_problem)

Asynchronous method. Use `await describe_problem(...)` for a synchronous call.

Arguments mapping described in
[DescribeProblemRequestRequestTypeDef](./type_defs.md#describeproblemrequestrequesttypedef).

Keyword-only arguments:

- `ProblemId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeProblemResponseTypeDef](./type_defs.md#describeproblemresponsetypedef).

<a id="describe_problem_observations"></a>

### describe_problem_observations

Describes the anomalies or errors associated with the problem.

Type annotations for
`aiobotocore.create_client("application-insights").describe_problem_observations`
method.

Boto3 documentation:
[ApplicationInsights.Client.describe_problem_observations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_problem_observations)

Asynchronous method. Use `await describe_problem_observations(...)` for a
synchronous call.

Arguments mapping described in
[DescribeProblemObservationsRequestRequestTypeDef](./type_defs.md#describeproblemobservationsrequestrequesttypedef).

Keyword-only arguments:

- `ProblemId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeProblemObservationsResponseTypeDef](./type_defs.md#describeproblemobservationsresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("application-insights").generate_presigned_url`
method.

Boto3 documentation:
[ApplicationInsights.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_applications"></a>

### list_applications

Lists the IDs of the applications that you are monitoring.

Type annotations for
`aiobotocore.create_client("application-insights").list_applications` method.

Boto3 documentation:
[ApplicationInsights.Client.list_applications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_applications)

Asynchronous method. Use `await list_applications(...)` for a synchronous call.

Arguments mapping described in
[ListApplicationsRequestRequestTypeDef](./type_defs.md#listapplicationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListApplicationsResponseTypeDef](./type_defs.md#listapplicationsresponsetypedef).

<a id="list_components"></a>

### list_components

Lists the auto-grouped, standalone, and custom components of the application.

Type annotations for
`aiobotocore.create_client("application-insights").list_components` method.

Boto3 documentation:
[ApplicationInsights.Client.list_components](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_components)

Asynchronous method. Use `await list_components(...)` for a synchronous call.

Arguments mapping described in
[ListComponentsRequestRequestTypeDef](./type_defs.md#listcomponentsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListComponentsResponseTypeDef](./type_defs.md#listcomponentsresponsetypedef).

<a id="list_configuration_history"></a>

### list_configuration_history

Lists the INFO, WARN, and ERROR events for periodic configuration updates
performed by Application Insights.

Type annotations for
`aiobotocore.create_client("application-insights").list_configuration_history`
method.

Boto3 documentation:
[ApplicationInsights.Client.list_configuration_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_configuration_history)

Asynchronous method. Use `await list_configuration_history(...)` for a
synchronous call.

Arguments mapping described in
[ListConfigurationHistoryRequestRequestTypeDef](./type_defs.md#listconfigurationhistoryrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str`
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `EventStatus`:
  [ConfigurationEventStatusType](./literals.md#configurationeventstatustype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListConfigurationHistoryResponseTypeDef](./type_defs.md#listconfigurationhistoryresponsetypedef).

<a id="list_log_pattern_sets"></a>

### list_log_pattern_sets

Lists the log pattern sets in the specific application.

Type annotations for
`aiobotocore.create_client("application-insights").list_log_pattern_sets`
method.

Boto3 documentation:
[ApplicationInsights.Client.list_log_pattern_sets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_log_pattern_sets)

Asynchronous method. Use `await list_log_pattern_sets(...)` for a synchronous
call.

Arguments mapping described in
[ListLogPatternSetsRequestRequestTypeDef](./type_defs.md#listlogpatternsetsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListLogPatternSetsResponseTypeDef](./type_defs.md#listlogpatternsetsresponsetypedef).

<a id="list_log_patterns"></a>

### list_log_patterns

Lists the log patterns in the specific log `LogPatternSet` .

Type annotations for
`aiobotocore.create_client("application-insights").list_log_patterns` method.

Boto3 documentation:
[ApplicationInsights.Client.list_log_patterns](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_log_patterns)

Asynchronous method. Use `await list_log_patterns(...)` for a synchronous call.

Arguments mapping described in
[ListLogPatternsRequestRequestTypeDef](./type_defs.md#listlogpatternsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `PatternSetName`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListLogPatternsResponseTypeDef](./type_defs.md#listlogpatternsresponsetypedef).

<a id="list_problems"></a>

### list_problems

Lists the problems with your application.

Type annotations for
`aiobotocore.create_client("application-insights").list_problems` method.

Boto3 documentation:
[ApplicationInsights.Client.list_problems](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_problems)

Asynchronous method. Use `await list_problems(...)` for a synchronous call.

Arguments mapping described in
[ListProblemsRequestRequestTypeDef](./type_defs.md#listproblemsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str`
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `ComponentName`: `str`

Returns a `Coroutine` for
[ListProblemsResponseTypeDef](./type_defs.md#listproblemsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Retrieve a list of the tags (keys and values) that are associated with a
specified application.

Type annotations for
`aiobotocore.create_client("application-insights").list_tags_for_resource`
method.

Boto3 documentation:
[ApplicationInsights.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Add one or more tags (keys and values) to a specified application.

Type annotations for
`aiobotocore.create_client("application-insights").tag_resource` method.

Boto3 documentation:
[ApplicationInsights.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Remove one or more tags (keys and values) from a specified application.

Type annotations for
`aiobotocore.create_client("application-insights").untag_resource` method.

Boto3 documentation:
[ApplicationInsights.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_application"></a>

### update_application

Updates the application.

Type annotations for
`aiobotocore.create_client("application-insights").update_application` method.

Boto3 documentation:
[ApplicationInsights.Client.update_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.update_application)

Asynchronous method. Use `await update_application(...)` for a synchronous
call.

Arguments mapping described in
[UpdateApplicationRequestRequestTypeDef](./type_defs.md#updateapplicationrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `OpsCenterEnabled`: `bool`
- `CWEMonitorEnabled`: `bool`
- `OpsItemSNSTopicArn`: `str`
- `RemoveSNSTopic`: `bool`
- `AutoConfigEnabled`: `bool`

Returns a `Coroutine` for
[UpdateApplicationResponseTypeDef](./type_defs.md#updateapplicationresponsetypedef).

<a id="update_component"></a>

### update_component

Updates the custom component name and/or the list of resources that make up the
component.

Type annotations for
`aiobotocore.create_client("application-insights").update_component` method.

Boto3 documentation:
[ApplicationInsights.Client.update_component](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.update_component)

Asynchronous method. Use `await update_component(...)` for a synchronous call.

Arguments mapping described in
[UpdateComponentRequestRequestTypeDef](./type_defs.md#updatecomponentrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `ComponentName`: `str` *(required)*
- `NewComponentName`: `str`
- `ResourceList`: `Sequence`\[`str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_component_configuration"></a>

### update_component_configuration

Updates the monitoring configurations for the component.

Type annotations for
`aiobotocore.create_client("application-insights").update_component_configuration`
method.

Boto3 documentation:
[ApplicationInsights.Client.update_component_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.update_component_configuration)

Asynchronous method. Use `await update_component_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateComponentConfigurationRequestRequestTypeDef](./type_defs.md#updatecomponentconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `ComponentName`: `str` *(required)*
- `Monitor`: `bool`
- `Tier`: [TierType](./literals.md#tiertype)
- `ComponentConfiguration`: `str`
- `AutoConfigEnabled`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_log_pattern"></a>

### update_log_pattern

Adds a log pattern to a `LogPatternSet` .

Type annotations for
`aiobotocore.create_client("application-insights").update_log_pattern` method.

Boto3 documentation:
[ApplicationInsights.Client.update_log_pattern](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.update_log_pattern)

Asynchronous method. Use `await update_log_pattern(...)` for a synchronous
call.

Arguments mapping described in
[UpdateLogPatternRequestRequestTypeDef](./type_defs.md#updatelogpatternrequestrequesttypedef).

Keyword-only arguments:

- `ResourceGroupName`: `str` *(required)*
- `PatternSetName`: `str` *(required)*
- `PatternName`: `str` *(required)*
- `Pattern`: `str`
- `Rank`: `int`

Returns a `Coroutine` for
[UpdateLogPatternResponseTypeDef](./type_defs.md#updatelogpatternresponsetypedef).
