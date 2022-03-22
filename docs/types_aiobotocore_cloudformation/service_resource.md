<a id="cloudformationserviceresource-for-aiobotocore-cloudformation-module"></a>

# CloudFormationServiceResource for aiobotocore CloudFormation module

> [Index](../README.md) > [CloudFormation](./README.md) >
> CloudFormationServiceResource

Auto-generated documentation for
[CloudFormation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
type annotations stubs module
[types-aiobotocore-cloudformation](https://pypi.org/project/types-aiobotocore-cloudformation/).

- [CloudFormationServiceResource for aiobotocore CloudFormation module](#cloudformationserviceresource-for-aiobotocore-cloudformation-module)
  - [CloudFormationServiceResource](#cloudformationserviceresource)
  - [Attributes](#attributes)
  - [Collections](#collections)
    - [ServiceResourceStacksCollection](#serviceresourcestackscollection)
  - [Methods](#methods)
    - [CloudFormationServiceResource.Event method](#cloudformationserviceresourceevent-method)
    - [CloudFormationServiceResource.Stack method](#cloudformationserviceresourcestack-method)
    - [CloudFormationServiceResource.StackResource method](#cloudformationserviceresourcestackresource-method)
    - [CloudFormationServiceResource.StackResourceSummary method](#cloudformationserviceresourcestackresourcesummary-method)
    - [CloudFormationServiceResource.create_stack method](#cloudformationserviceresourcecreate_stack-method)
    - [CloudFormationServiceResource.get_available_subresources method](#cloudformationserviceresourceget_available_subresources-method)
  - [Event](#event)
    - [Event attributes](#event-attributes)
    - [Event methods](#event-methods)
  - [Stack](#stack)
    - [Stack attributes](#stack-attributes)
    - [Stack collections](#stack-collections)
    - [Stack methods](#stack-methods)
  - [StackResource](#stackresource)
    - [StackResource attributes](#stackresource-attributes)
    - [StackResource methods](#stackresource-methods)
  - [StackResourceSummary](#stackresourcesummary)
    - [StackResourceSummary attributes](#stackresourcesummary-attributes)
    - [StackResourceSummary methods](#stackresourcesummary-methods)

<a id="cloudformationserviceresource"></a>

## CloudFormationServiceResource

Type annotations for `aiobotocore.resource("cloudformation")`, included
resources and collections.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import CloudFormationServiceResource

def get_cloudformation_resource() -> CloudFormationServiceResource:
    return boto3.resource("cloudformation")
```

Boto3 documentation:
[CloudFormation.ServiceResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource)

<a id="attributes"></a>

## Attributes

- `meta`: [CloudFormationResourceMeta](#cloudformationresourcemeta)

- `stacks`: [ServiceResourceStacksCollection](#serviceresourcestackscollection)

<a id="collections"></a>

## Collections

<a id="serviceresourcestackscollection"></a>

### ServiceResourceStacksCollection

Type annotations for `boto3.resource("cloudformation").stacks` collection.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import ServiceResourceStacksCollection,

def get_collection() -> ServiceResourceStacksCollection:
    return boto3.resource("cloudformation").stacks
```

Provides access to [Stack](#stack) resource.

Boto3 documentation:
[CloudFormation.ServiceResource.stacks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.stacks)

<a id="methods"></a>

## Methods

<a id="cloudformationserviceresourceevent-method"></a>

### CloudFormationServiceResource.Event method

Creates a Event resource.

Type annotations for `aiobotocore.resource("cloudformation").Event` method.

Boto3 documentation:
[CloudFormation.ServiceResource.Event](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.Event)

Asynchronous method. Use `await Event(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceEventRequestTypeDef](./type_defs.md#serviceresourceeventrequesttypedef).

Arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for [Event](#event).

<a id="cloudformationserviceresourcestack-method"></a>

### CloudFormationServiceResource.Stack method

Creates a Stack resource.

Type annotations for `aiobotocore.resource("cloudformation").Stack` method.

Boto3 documentation:
[CloudFormation.ServiceResource.Stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.Stack)

Asynchronous method. Use `await Stack(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceStackRequestTypeDef](./type_defs.md#serviceresourcestackrequesttypedef).

Arguments:

- `name`: `str` *(required)*

Returns a `Coroutine` for [Stack](#stack).

<a id="cloudformationserviceresourcestackresource-method"></a>

### CloudFormationServiceResource.StackResource method

Creates a StackResource resource.

Type annotations for `aiobotocore.resource("cloudformation").StackResource`
method.

Boto3 documentation:
[CloudFormation.ServiceResource.StackResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.StackResource)

Asynchronous method. Use `await StackResource(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceStackResourceRequestTypeDef](./type_defs.md#serviceresourcestackresourcerequesttypedef).

Arguments:

- `stack_name`: `str` *(required)*
- `logical_id`: `str` *(required)*

Returns a `Coroutine` for [StackResource](#stackresource).

<a id="cloudformationserviceresourcestackresourcesummary-method"></a>

### CloudFormationServiceResource.StackResourceSummary method

Creates a StackResourceSummary resource.

Type annotations for
`aiobotocore.resource("cloudformation").StackResourceSummary` method.

Boto3 documentation:
[CloudFormation.ServiceResource.StackResourceSummary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.StackResourceSummary)

Asynchronous method. Use `await StackResourceSummary(...)` for a synchronous
call.

Arguments mapping described in
[ServiceResourceStackResourceSummaryRequestTypeDef](./type_defs.md#serviceresourcestackresourcesummaryrequesttypedef).

Arguments:

- `stack_name`: `str` *(required)*
- `logical_id`: `str` *(required)*

Returns a `Coroutine` for [StackResourceSummary](#stackresourcesummary).

<a id="cloudformationserviceresourcecreate\_stack-method"></a>

### CloudFormationServiceResource.create_stack method

.

Type annotations for `aiobotocore.resource("cloudformation").create_stack`
method.

Boto3 documentation:
[CloudFormation.ServiceResource.create_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.create_stack)

Asynchronous method. Use `await create_stack(...)` for a synchronous call.

Arguments mapping described in
[CreateStackInputServiceResourceCreateStackTypeDef](./type_defs.md#createstackinputserviceresourcecreatestacktypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `DisableRollback`: `bool`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `TimeoutInMinutes`: `int`
- `NotificationARNs`: `Sequence`\[`str`\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `OnFailure`: [OnFailureType](./literals.md#onfailuretype)
- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientRequestToken`: `str`
- `EnableTerminationProtection`: `bool`

Returns a `Coroutine` for [Stack](#stack).

<a id="cloudformationserviceresourceget\_available\_subresources-method"></a>

### CloudFormationServiceResource.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudformation").get_available_subresources` method.

Boto3 documentation:
[CloudFormation.ServiceResource.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="event"></a>

## Event

Type annotations for `aiobotocore.resource("cloudformation").Event` class.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import Event

def get_resource() -> Event:
    return boto3.resource("cloudformation").Event(...)
```

Boto3 documentation:
[CloudFormation.Event](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.Event)

<a id="event-attributes"></a>

### Event attributes

- `stack_id`: `str`
- `event_id`: `str`
- `stack_name`: `str`
- `logical_resource_id`: `str`
- `physical_resource_id`: `str`
- `resource_type`: `str`
- `timestamp`: `datetime`
- `resource_status`: [ResourceStatusType](./literals.md#resourcestatustype)
- `resource_status_reason`: `str`
- `resource_properties`: `str`
- `client_request_token`: `str`
- `hook_type`: `str`
- `hook_status`: [HookStatusType](./literals.md#hookstatustype)
- `hook_status_reason`: `str`
- `hook_invocation_point`: `Literal['PRE_PROVISION']` (see
  [HookInvocationPointType](./literals.md#hookinvocationpointtype))
- `hook_failure_mode`: [HookFailureModeType](./literals.md#hookfailuremodetype)
- `id`: `str`

<a id="event-methods"></a>

### Event methods

<a id="eventget\_available\_subresources-method"></a>

#### Event.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudformation").get_available_subresources` method.

Boto3 documentation:
[CloudFormation.Event.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Event.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="stack"></a>

## Stack

Type annotations for `aiobotocore.resource("cloudformation").Stack` class.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import Stack

def get_resource() -> Stack:
    return boto3.resource("cloudformation").Stack(...)
```

Boto3 documentation:
[CloudFormation.Stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.Stack)

<a id="stack-attributes"></a>

### Stack attributes

- `stack_id`: `str`
- `stack_name`: `str`
- `change_set_id`: `str`
- `description`: `str`
- `parameters`: `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `creation_time`: `datetime`
- `deletion_time`: `datetime`
- `last_updated_time`: `datetime`
- `rollback_configuration`:
  [RollbackConfigurationResponseMetadataTypeDef](./type_defs.md#rollbackconfigurationresponsemetadatatypedef)
- `stack_status`: [StackStatusType](./literals.md#stackstatustype)
- `stack_status_reason`: `str`
- `disable_rollback`: `bool`
- `notification_arns`: `List`\[`str`\]
- `timeout_in_minutes`: `int`
- `capabilities`: `List`\[[CapabilityType](./literals.md#capabilitytype)\]
- `outputs`: `List`\[[OutputTypeDef](./type_defs.md#outputtypedef)\]
- `role_arn`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `enable_termination_protection`: `bool`
- `parent_id`: `str`
- `root_id`: `str`
- `drift_information`:
  [StackDriftInformationResponseMetadataTypeDef](./type_defs.md#stackdriftinformationresponsemetadatatypedef)
- `name`: `str`
- `events`: [StackEventsCollection](#stackeventscollection)
- `resource_summaries`:
  [StackResourceSummariesCollection](#stackresourcesummariescollection)

<a id="stack-collections"></a>

### Stack collections

<a id="stackevents"></a>

#### Stack.events

Type annotations for `aiobotocore.resource("cloudformation").Stack(...).events`
collection.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import StackEventsCollection,

def get_collection() -> StackEventsCollection:
    resource = boto3.resource("cloudformation").Stack(...)
    return resource.events
```

Provides access to [Event](#event) resource.

Boto3 documentation:
[CloudFormation.Stack.StackEventsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.events)

<a id="stackresource_summaries"></a>

#### Stack.resource_summaries

Type annotations for
`aiobotocore.resource("cloudformation").Stack(...).resource_summaries`
collection.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import StackResourceSummariesCollection,

def get_collection() -> StackResourceSummariesCollection:
    resource = boto3.resource("cloudformation").Stack(...)
    return resource.resource_summaries
```

Provides access to [StackResourceSummary](#stackresourcesummary) resource.

Boto3 documentation:
[CloudFormation.Stack.StackResourceSummariesCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.resource_summaries)

<a id="stack-methods"></a>

### Stack methods

<a id="stackresource-method"></a>

#### Stack.Resource method

Creates a StackResource resource.

Type annotations for `aiobotocore.resource("cloudformation").Resource` method.

Boto3 documentation:
[CloudFormation.Stack.Resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.Resource)

Asynchronous method. Use `await Resource(...)` for a synchronous call.

Arguments mapping described in
[StackResourceRequestTypeDef](./type_defs.md#stackresourcerequesttypedef).

Arguments:

- `logical_id`: `str` *(required)*

Returns a `Coroutine` for [StackResource](#stackresource).

<a id="stackcancel\_update-method"></a>

#### Stack.cancel_update method

Cancels an update on the specified stack.

Type annotations for `aiobotocore.resource("cloudformation").cancel_update`
method.

Boto3 documentation:
[CloudFormation.Stack.cancel_update](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.cancel_update)

Asynchronous method. Use `await cancel_update(...)` for a synchronous call.

Arguments mapping described in
[CancelUpdateStackInputStackCancelUpdateTypeDef](./type_defs.md#cancelupdatestackinputstackcancelupdatetypedef).

Keyword-only arguments:

- `ClientRequestToken`: `str`

<a id="stackdelete-method"></a>

#### Stack.delete method

Deletes a specified stack.

Type annotations for `aiobotocore.resource("cloudformation").delete` method.

Boto3 documentation:
[CloudFormation.Stack.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

Arguments mapping described in
[DeleteStackInputStackDeleteTypeDef](./type_defs.md#deletestackinputstackdeletetypedef).

Keyword-only arguments:

- `RetainResources`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `ClientRequestToken`: `str`

<a id="stackget\_available\_subresources-method"></a>

#### Stack.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudformation").get_available_subresources` method.

Boto3 documentation:
[CloudFormation.Stack.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="stackload-method"></a>

#### Stack.load method

Calls :py:meth:`CloudFormation.Client.describe_stacks` to update the attributes
of the Stack resource.

Type annotations for `aiobotocore.resource("cloudformation").load` method.

Boto3 documentation:
[CloudFormation.Stack.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="stackreload-method"></a>

#### Stack.reload method

Calls :py:meth:`CloudFormation.Client.describe_stacks` to update the attributes
of the Stack resource.

Type annotations for `aiobotocore.resource("cloudformation").reload` method.

Boto3 documentation:
[CloudFormation.Stack.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="stackupdate-method"></a>

#### Stack.update method

.

Type annotations for `aiobotocore.resource("cloudformation").update` method.

Boto3 documentation:
[CloudFormation.Stack.update](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Stack.update)

Asynchronous method. Use `await update(...)` for a synchronous call.

Arguments mapping described in
[UpdateStackInputStackUpdateTypeDef](./type_defs.md#updatestackinputstackupdatetypedef).

Keyword-only arguments:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `UsePreviousTemplate`: `bool`
- `StackPolicyDuringUpdateBody`: `str`
- `StackPolicyDuringUpdateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`
- `NotificationARNs`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `DisableRollback`: `bool`
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[UpdateStackOutputTypeDef](./type_defs.md#updatestackoutputtypedef).

<a id="stackresource"></a>

## StackResource

Type annotations for `aiobotocore.resource("cloudformation").StackResource`
class.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import StackResource

def get_resource() -> StackResource:
    return boto3.resource("cloudformation").StackResource(...)
```

Boto3 documentation:
[CloudFormation.StackResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.StackResource)

<a id="stackresource-attributes"></a>

### StackResource attributes

- `stack_id`: `str`
- `logical_resource_id`: `str`
- `physical_resource_id`: `str`
- `resource_type`: `str`
- `last_updated_timestamp`: `datetime`
- `resource_status`: [ResourceStatusType](./literals.md#resourcestatustype)
- `resource_status_reason`: `str`
- `description`: `str`
- `metadata`: `str`
- `drift_information`:
  [StackResourceDriftInformationResponseMetadataTypeDef](./type_defs.md#stackresourcedriftinformationresponsemetadatatypedef)
- `module_info`:
  [ModuleInfoResponseMetadataTypeDef](./type_defs.md#moduleinforesponsemetadatatypedef)
- `stack_name`: `str`
- `logical_id`: `str`

<a id="stackresource-methods"></a>

### StackResource methods

<a id="stackresourcestack-method"></a>

#### StackResource.Stack method

Creates a Stack resource.

Type annotations for `aiobotocore.resource("cloudformation").Stack` method.

Boto3 documentation:
[CloudFormation.StackResource.Stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.StackResource.Stack)

Asynchronous method. Use `await Stack(...)` for a synchronous call.

Returns a `Coroutine` for [Stack](#stack).

<a id="stackresourceget\_available\_subresources-method"></a>

#### StackResource.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudformation").get_available_subresources` method.

Boto3 documentation:
[CloudFormation.StackResource.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.StackResource.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="stackresourceload-method"></a>

#### StackResource.load method

Calls :py:meth:`CloudFormation.Client.describe_stack_resource` to update the
attributes of the StackResource resource.

Type annotations for `aiobotocore.resource("cloudformation").load` method.

Boto3 documentation:
[CloudFormation.StackResource.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.StackResource.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="stackresourcereload-method"></a>

#### StackResource.reload method

Calls :py:meth:`CloudFormation.Client.describe_stack_resource` to update the
attributes of the StackResource resource.

Type annotations for `aiobotocore.resource("cloudformation").reload` method.

Boto3 documentation:
[CloudFormation.StackResource.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.StackResource.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="stackresourcesummary"></a>

## StackResourceSummary

Type annotations for
`aiobotocore.resource("cloudformation").StackResourceSummary` class.

Can be used directly:

```python
from types_aiobotocore_cloudformation.service_resource import StackResourceSummary

def get_resource() -> StackResourceSummary:
    return boto3.resource("cloudformation").StackResourceSummary(...)
```

Boto3 documentation:
[CloudFormation.StackResourceSummary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.ServiceResource.StackResourceSummary)

<a id="stackresourcesummary-attributes"></a>

### StackResourceSummary attributes

- `logical_resource_id`: `str`
- `physical_resource_id`: `str`
- `resource_type`: `str`
- `last_updated_timestamp`: `datetime`
- `resource_status`: [ResourceStatusType](./literals.md#resourcestatustype)
- `resource_status_reason`: `str`
- `drift_information`:
  [StackResourceDriftInformationSummaryResponseMetadataTypeDef](./type_defs.md#stackresourcedriftinformationsummaryresponsemetadatatypedef)
- `module_info`:
  [ModuleInfoResponseMetadataTypeDef](./type_defs.md#moduleinforesponsemetadatatypedef)
- `stack_name`: `str`
- `logical_id`: `str`

<a id="stackresourcesummary-methods"></a>

### StackResourceSummary methods

<a id="stackresourcesummaryresource-method"></a>

#### StackResourceSummary.Resource method

Creates a StackResource resource.

Type annotations for `aiobotocore.resource("cloudformation").Resource` method.

Boto3 documentation:
[CloudFormation.StackResourceSummary.Resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.StackResourceSummary.Resource)

Asynchronous method. Use `await Resource(...)` for a synchronous call.

Returns a `Coroutine` for [StackResource](#stackresource).

<a id="stackresourcesummaryget\_available\_subresources-method"></a>

#### StackResourceSummary.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for
`aiobotocore.resource("cloudformation").get_available_subresources` method.

Boto3 documentation:
[CloudFormation.StackResourceSummary.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.StackResourceSummary.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].
