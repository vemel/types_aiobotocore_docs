<a id="cloudformationclient-for-aiobotocore-cloudformation-module"></a>

# CloudFormationClient for aiobotocore CloudFormation module

> [Index](../README.md) > [CloudFormation](./README.md) > CloudFormationClient

Auto-generated documentation for
[CloudFormation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
type annotations stubs module
[types-aiobotocore-cloudformation](https://pypi.org/project/types-aiobotocore-cloudformation/).

- [CloudFormationClient for aiobotocore CloudFormation module](#cloudformationclient-for-aiobotocore-cloudformation-module)
  - [CloudFormationClient](#cloudformationclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [activate_type](#activate_type)
    - [batch_describe_type_configurations](#batch_describe_type_configurations)
    - [can_paginate](#can_paginate)
    - [cancel_update_stack](#cancel_update_stack)
    - [continue_update_rollback](#continue_update_rollback)
    - [create_change_set](#create_change_set)
    - [create_stack](#create_stack)
    - [create_stack_instances](#create_stack_instances)
    - [create_stack_set](#create_stack_set)
    - [deactivate_type](#deactivate_type)
    - [delete_change_set](#delete_change_set)
    - [delete_stack](#delete_stack)
    - [delete_stack_instances](#delete_stack_instances)
    - [delete_stack_set](#delete_stack_set)
    - [deregister_type](#deregister_type)
    - [describe_account_limits](#describe_account_limits)
    - [describe_change_set](#describe_change_set)
    - [describe_change_set_hooks](#describe_change_set_hooks)
    - [describe_publisher](#describe_publisher)
    - [describe_stack_drift_detection_status](#describe_stack_drift_detection_status)
    - [describe_stack_events](#describe_stack_events)
    - [describe_stack_instance](#describe_stack_instance)
    - [describe_stack_resource](#describe_stack_resource)
    - [describe_stack_resource_drifts](#describe_stack_resource_drifts)
    - [describe_stack_resources](#describe_stack_resources)
    - [describe_stack_set](#describe_stack_set)
    - [describe_stack_set_operation](#describe_stack_set_operation)
    - [describe_stacks](#describe_stacks)
    - [describe_type](#describe_type)
    - [describe_type_registration](#describe_type_registration)
    - [detect_stack_drift](#detect_stack_drift)
    - [detect_stack_resource_drift](#detect_stack_resource_drift)
    - [detect_stack_set_drift](#detect_stack_set_drift)
    - [estimate_template_cost](#estimate_template_cost)
    - [execute_change_set](#execute_change_set)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_stack_policy](#get_stack_policy)
    - [get_template](#get_template)
    - [get_template_summary](#get_template_summary)
    - [import_stacks_to_stack_set](#import_stacks_to_stack_set)
    - [list_change_sets](#list_change_sets)
    - [list_exports](#list_exports)
    - [list_imports](#list_imports)
    - [list_stack_instances](#list_stack_instances)
    - [list_stack_resources](#list_stack_resources)
    - [list_stack_set_operation_results](#list_stack_set_operation_results)
    - [list_stack_set_operations](#list_stack_set_operations)
    - [list_stack_sets](#list_stack_sets)
    - [list_stacks](#list_stacks)
    - [list_type_registrations](#list_type_registrations)
    - [list_type_versions](#list_type_versions)
    - [list_types](#list_types)
    - [publish_type](#publish_type)
    - [record_handler_progress](#record_handler_progress)
    - [register_publisher](#register_publisher)
    - [register_type](#register_type)
    - [rollback_stack](#rollback_stack)
    - [set_stack_policy](#set_stack_policy)
    - [set_type_configuration](#set_type_configuration)
    - [set_type_default_version](#set_type_default_version)
    - [signal_resource](#signal_resource)
    - [stop_stack_set_operation](#stop_stack_set_operation)
    - [test_type](#test_type)
    - [update_stack](#update_stack)
    - [update_stack_instances](#update_stack_instances)
    - [update_stack_set](#update_stack_set)
    - [update_termination_protection](#update_termination_protection)
    - [validate_template](#validate_template)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="cloudformationclient"></a>

## CloudFormationClient

Type annotations for `session.create_client("cloudformation")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_cloudformation.client import CloudFormationClient

session = get_session()
async with session.create_client("cloudformation") as client:
    client: CloudFormationClient
```

Boto3 documentation:
[CloudFormation.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_cloudformation.client import Exceptions

def handle_error(exc: Exceptions.AlreadyExistsException) -> None:
    ...
```

Exceptions:

- `Exceptions.AlreadyExistsException`
- `Exceptions.CFNRegistryException`
- `Exceptions.ChangeSetNotFoundException`
- `Exceptions.ClientError`
- `Exceptions.CreatedButModifiedException`
- `Exceptions.InsufficientCapabilitiesException`
- `Exceptions.InvalidChangeSetStatusException`
- `Exceptions.InvalidOperationException`
- `Exceptions.InvalidStateTransitionException`
- `Exceptions.LimitExceededException`
- `Exceptions.NameAlreadyExistsException`
- `Exceptions.OperationIdAlreadyExistsException`
- `Exceptions.OperationInProgressException`
- `Exceptions.OperationNotFoundException`
- `Exceptions.OperationStatusCheckFailedException`
- `Exceptions.StackInstanceNotFoundException`
- `Exceptions.StackNotFoundException`
- `Exceptions.StackSetNotEmptyException`
- `Exceptions.StackSetNotFoundException`
- `Exceptions.StaleRequestException`
- `Exceptions.TokenAlreadyExistsException`
- `Exceptions.TypeConfigurationNotFoundException`
- `Exceptions.TypeNotFoundException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

CloudFormationClient exceptions.

Type annotations for `session.create_client("cloudformation").exceptions`
method.

Boto3 documentation:
[CloudFormation.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="activate\_type"></a>

### activate_type

Activates a public third-party extension, making it available for use in stack
templates.

Type annotations for `session.create_client("cloudformation").activate_type`
method.

Boto3 documentation:
[CloudFormation.Client.activate_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.activate_type)

Asynchronous method. Use `await activate_type(...)` for a synchronous call.

Arguments mapping described in
[ActivateTypeInputRequestTypeDef](./type_defs.md#activatetypeinputrequesttypedef).

Keyword-only arguments:

- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `PublicTypeArn`: `str`
- `PublisherId`: `str`
- `TypeName`: `str`
- `TypeNameAlias`: `str`
- `AutoUpdate`: `bool`
- `LoggingConfig`: [LoggingConfigTypeDef](./type_defs.md#loggingconfigtypedef)
- `ExecutionRoleArn`: `str`
- `VersionBump`: [VersionBumpType](./literals.md#versionbumptype)
- `MajorVersion`: `int`

Returns a `Coroutine` for
[ActivateTypeOutputTypeDef](./type_defs.md#activatetypeoutputtypedef).

<a id="batch\_describe\_type\_configurations"></a>

### batch_describe_type_configurations

Returns configuration data for the specified CloudFormation extensions, from
the CloudFormation registry for the account and region.

Type annotations for
`session.create_client("cloudformation").batch_describe_type_configurations`
method.

Boto3 documentation:
[CloudFormation.Client.batch_describe_type_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.batch_describe_type_configurations)

Asynchronous method. Use `await batch_describe_type_configurations(...)` for a
synchronous call.

Arguments mapping described in
[BatchDescribeTypeConfigurationsInputRequestTypeDef](./type_defs.md#batchdescribetypeconfigurationsinputrequesttypedef).

Keyword-only arguments:

- `TypeConfigurationIdentifiers`:
  `Sequence`\[[TypeConfigurationIdentifierTypeDef](./type_defs.md#typeconfigurationidentifiertypedef)\]
  *(required)*

Returns a `Coroutine` for
[BatchDescribeTypeConfigurationsOutputTypeDef](./type_defs.md#batchdescribetypeconfigurationsoutputtypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("cloudformation").can_paginate`
method.

Boto3 documentation:
[CloudFormation.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="cancel\_update\_stack"></a>

### cancel_update_stack

Cancels an update on the specified stack.

Type annotations for
`session.create_client("cloudformation").cancel_update_stack` method.

Boto3 documentation:
[CloudFormation.Client.cancel_update_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.cancel_update_stack)

Asynchronous method. Use `await cancel_update_stack(...)` for a synchronous
call.

Arguments mapping described in
[CancelUpdateStackInputRequestTypeDef](./type_defs.md#cancelupdatestackinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `ClientRequestToken`: `str`

<a id="continue\_update\_rollback"></a>

### continue_update_rollback

For a specified stack that's in the `UPDATE_ROLLBACK_FAILED` state, continues
rolling it back to the `UPDATE_ROLLBACK_COMPLETE` state.

Type annotations for
`session.create_client("cloudformation").continue_update_rollback` method.

Boto3 documentation:
[CloudFormation.Client.continue_update_rollback](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.continue_update_rollback)

Asynchronous method. Use `await continue_update_rollback(...)` for a
synchronous call.

Arguments mapping described in
[ContinueUpdateRollbackInputRequestTypeDef](./type_defs.md#continueupdaterollbackinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `RoleARN`: `str`
- `ResourcesToSkip`: `Sequence`\[`str`\]
- `ClientRequestToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create\_change\_set"></a>

### create_change_set

.

Type annotations for
`session.create_client("cloudformation").create_change_set` method.

Boto3 documentation:
[CloudFormation.Client.create_change_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_change_set)

Asynchronous method. Use `await create_change_set(...)` for a synchronous call.

Arguments mapping described in
[CreateChangeSetInputRequestTypeDef](./type_defs.md#createchangesetinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `ChangeSetName`: `str` *(required)*
- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `UsePreviousTemplate`: `bool`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `RollbackConfiguration`:
  [RollbackConfigurationTypeDef](./type_defs.md#rollbackconfigurationtypedef)
- `NotificationARNs`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ClientToken`: `str`
- `Description`: `str`
- `ChangeSetType`: [ChangeSetTypeType](./literals.md#changesettypetype)
- `ResourcesToImport`:
  `Sequence`\[[ResourceToImportTypeDef](./type_defs.md#resourcetoimporttypedef)\]
- `IncludeNestedStacks`: `bool`

Returns a `Coroutine` for
[CreateChangeSetOutputTypeDef](./type_defs.md#createchangesetoutputtypedef).

<a id="create\_stack"></a>

### create_stack

.

Type annotations for `session.create_client("cloudformation").create_stack`
method.

Boto3 documentation:
[CloudFormation.Client.create_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_stack)

Asynchronous method. Use `await create_stack(...)` for a synchronous call.

Arguments mapping described in
[CreateStackInputRequestTypeDef](./type_defs.md#createstackinputrequesttypedef).

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

Returns a `Coroutine` for
[CreateStackOutputTypeDef](./type_defs.md#createstackoutputtypedef).

<a id="create\_stack\_instances"></a>

### create_stack_instances

.

Type annotations for
`session.create_client("cloudformation").create_stack_instances` method.

Boto3 documentation:
[CloudFormation.Client.create_stack_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_stack_instances)

Asynchronous method. Use `await create_stack_instances(...)` for a synchronous
call.

Arguments mapping described in
[CreateStackInstancesInputRequestTypeDef](./type_defs.md#createstackinstancesinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `Regions`: `Sequence`\[`str`\] *(required)*
- `Accounts`: `Sequence`\[`str`\]
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `ParameterOverrides`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[CreateStackInstancesOutputTypeDef](./type_defs.md#createstackinstancesoutputtypedef).

<a id="create\_stack\_set"></a>

### create_stack_set

.

Type annotations for `session.create_client("cloudformation").create_stack_set`
method.

Boto3 documentation:
[CloudFormation.Client.create_stack_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_stack_set)

Asynchronous method. Use `await create_stack_set(...)` for a synchronous call.

Arguments mapping described in
[CreateStackSetInputRequestTypeDef](./type_defs.md#createstacksetinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `Description`: `str`
- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `StackId`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `AdministrationRoleARN`: `str`
- `ExecutionRoleName`: `str`
- `PermissionModel`: [PermissionModelsType](./literals.md#permissionmodelstype)
- `AutoDeployment`:
  [AutoDeploymentTypeDef](./type_defs.md#autodeploymenttypedef)
- `CallAs`: [CallAsType](./literals.md#callastype)
- `ClientRequestToken`: `str`
- `ManagedExecution`:
  [ManagedExecutionTypeDef](./type_defs.md#managedexecutiontypedef)

Returns a `Coroutine` for
[CreateStackSetOutputTypeDef](./type_defs.md#createstacksetoutputtypedef).

<a id="deactivate\_type"></a>

### deactivate_type

Deactivates a public extension that was previously activated in this account
and region.

Type annotations for `session.create_client("cloudformation").deactivate_type`
method.

Boto3 documentation:
[CloudFormation.Client.deactivate_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.deactivate_type)

Asynchronous method. Use `await deactivate_type(...)` for a synchronous call.

Arguments mapping described in
[DeactivateTypeInputRequestTypeDef](./type_defs.md#deactivatetypeinputrequesttypedef).

Keyword-only arguments:

- `TypeName`: `str`
- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `Arn`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_change\_set"></a>

### delete_change_set

Deletes the specified change set.

Type annotations for
`session.create_client("cloudformation").delete_change_set` method.

Boto3 documentation:
[CloudFormation.Client.delete_change_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.delete_change_set)

Asynchronous method. Use `await delete_change_set(...)` for a synchronous call.

Arguments mapping described in
[DeleteChangeSetInputRequestTypeDef](./type_defs.md#deletechangesetinputrequesttypedef).

Keyword-only arguments:

- `ChangeSetName`: `str` *(required)*
- `StackName`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete\_stack"></a>

### delete_stack

Deletes a specified stack.

Type annotations for `session.create_client("cloudformation").delete_stack`
method.

Boto3 documentation:
[CloudFormation.Client.delete_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.delete_stack)

Asynchronous method. Use `await delete_stack(...)` for a synchronous call.

Arguments mapping described in
[DeleteStackInputRequestTypeDef](./type_defs.md#deletestackinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `RetainResources`: `Sequence`\[`str`\]
- `RoleARN`: `str`
- `ClientRequestToken`: `str`

<a id="delete\_stack\_instances"></a>

### delete_stack_instances

Deletes stack instances for the specified accounts, in the specified Amazon Web
Services Regions.

Type annotations for
`session.create_client("cloudformation").delete_stack_instances` method.

Boto3 documentation:
[CloudFormation.Client.delete_stack_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.delete_stack_instances)

Asynchronous method. Use `await delete_stack_instances(...)` for a synchronous
call.

Arguments mapping described in
[DeleteStackInstancesInputRequestTypeDef](./type_defs.md#deletestackinstancesinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `Regions`: `Sequence`\[`str`\] *(required)*
- `RetainStacks`: `bool` *(required)*
- `Accounts`: `Sequence`\[`str`\]
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[DeleteStackInstancesOutputTypeDef](./type_defs.md#deletestackinstancesoutputtypedef).

<a id="delete\_stack\_set"></a>

### delete_stack_set

Deletes a stack set.

Type annotations for `session.create_client("cloudformation").delete_stack_set`
method.

Boto3 documentation:
[CloudFormation.Client.delete_stack_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.delete_stack_set)

Asynchronous method. Use `await delete_stack_set(...)` for a synchronous call.

Arguments mapping described in
[DeleteStackSetInputRequestTypeDef](./type_defs.md#deletestacksetinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deregister\_type"></a>

### deregister_type

Marks an extension or extension version as `DEPRECATED` in the CloudFormation
registry, removing it from active use.

Type annotations for `session.create_client("cloudformation").deregister_type`
method.

Boto3 documentation:
[CloudFormation.Client.deregister_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.deregister_type)

Asynchronous method. Use `await deregister_type(...)` for a synchronous call.

Arguments mapping described in
[DeregisterTypeInputRequestTypeDef](./type_defs.md#deregistertypeinputrequesttypedef).

Keyword-only arguments:

- `Arn`: `str`
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `VersionId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe\_account\_limits"></a>

### describe_account_limits

Retrieves your account's CloudFormation limits, such as the maximum number of
stacks that you can create in your account.

Type annotations for
`session.create_client("cloudformation").describe_account_limits` method.

Boto3 documentation:
[CloudFormation.Client.describe_account_limits](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_account_limits)

Asynchronous method. Use `await describe_account_limits(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAccountLimitsInputRequestTypeDef](./type_defs.md#describeaccountlimitsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeAccountLimitsOutputTypeDef](./type_defs.md#describeaccountlimitsoutputtypedef).

<a id="describe\_change\_set"></a>

### describe_change_set

.

Type annotations for
`session.create_client("cloudformation").describe_change_set` method.

Boto3 documentation:
[CloudFormation.Client.describe_change_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_change_set)

Asynchronous method. Use `await describe_change_set(...)` for a synchronous
call.

Arguments mapping described in
[DescribeChangeSetInputRequestTypeDef](./type_defs.md#describechangesetinputrequesttypedef).

Keyword-only arguments:

- `ChangeSetName`: `str` *(required)*
- `StackName`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeChangeSetOutputTypeDef](./type_defs.md#describechangesetoutputtypedef).

<a id="describe\_change\_set\_hooks"></a>

### describe_change_set_hooks

Returns hook-related information for the change set and a list of changes that
CloudFormation makes when you run the change set.

Type annotations for
`session.create_client("cloudformation").describe_change_set_hooks` method.

Boto3 documentation:
[CloudFormation.Client.describe_change_set_hooks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_change_set_hooks)

Asynchronous method. Use `await describe_change_set_hooks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeChangeSetHooksInputRequestTypeDef](./type_defs.md#describechangesethooksinputrequesttypedef).

Keyword-only arguments:

- `ChangeSetName`: `str` *(required)*
- `StackName`: `str`
- `NextToken`: `str`
- `LogicalResourceId`: `str`

Returns a `Coroutine` for
[DescribeChangeSetHooksOutputTypeDef](./type_defs.md#describechangesethooksoutputtypedef).

<a id="describe\_publisher"></a>

### describe_publisher

Returns information about a CloudFormation extension publisher.

Type annotations for
`session.create_client("cloudformation").describe_publisher` method.

Boto3 documentation:
[CloudFormation.Client.describe_publisher](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_publisher)

Asynchronous method. Use `await describe_publisher(...)` for a synchronous
call.

Arguments mapping described in
[DescribePublisherInputRequestTypeDef](./type_defs.md#describepublisherinputrequesttypedef).

Keyword-only arguments:

- `PublisherId`: `str`

Returns a `Coroutine` for
[DescribePublisherOutputTypeDef](./type_defs.md#describepublisheroutputtypedef).

<a id="describe\_stack\_drift\_detection\_status"></a>

### describe_stack_drift_detection_status

Returns information about a stack drift detection operation.

Type annotations for
`session.create_client("cloudformation").describe_stack_drift_detection_status`
method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_drift_detection_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_drift_detection_status)

Asynchronous method. Use `await describe_stack_drift_detection_status(...)` for
a synchronous call.

Arguments mapping described in
[DescribeStackDriftDetectionStatusInputRequestTypeDef](./type_defs.md#describestackdriftdetectionstatusinputrequesttypedef).

Keyword-only arguments:

- `StackDriftDetectionId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeStackDriftDetectionStatusOutputTypeDef](./type_defs.md#describestackdriftdetectionstatusoutputtypedef).

<a id="describe\_stack\_events"></a>

### describe_stack_events

Returns all stack related events for a specified stack in reverse chronological
order.

Type annotations for
`session.create_client("cloudformation").describe_stack_events` method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_events)

Asynchronous method. Use `await describe_stack_events(...)` for a synchronous
call.

Arguments mapping described in
[DescribeStackEventsInputRequestTypeDef](./type_defs.md#describestackeventsinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeStackEventsOutputTypeDef](./type_defs.md#describestackeventsoutputtypedef).

<a id="describe\_stack\_instance"></a>

### describe_stack_instance

.

Type annotations for
`session.create_client("cloudformation").describe_stack_instance` method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_instance)

Asynchronous method. Use `await describe_stack_instance(...)` for a synchronous
call.

Arguments mapping described in
[DescribeStackInstanceInputRequestTypeDef](./type_defs.md#describestackinstanceinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `StackInstanceAccount`: `str` *(required)*
- `StackInstanceRegion`: `str` *(required)*
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[DescribeStackInstanceOutputTypeDef](./type_defs.md#describestackinstanceoutputtypedef).

<a id="describe\_stack\_resource"></a>

### describe_stack_resource

Returns a description of the specified resource in the specified stack.

Type annotations for
`session.create_client("cloudformation").describe_stack_resource` method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_resource)

Asynchronous method. Use `await describe_stack_resource(...)` for a synchronous
call.

Arguments mapping described in
[DescribeStackResourceInputRequestTypeDef](./type_defs.md#describestackresourceinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `LogicalResourceId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeStackResourceOutputTypeDef](./type_defs.md#describestackresourceoutputtypedef).

<a id="describe\_stack\_resource\_drifts"></a>

### describe_stack_resource_drifts

Returns drift information for the resources that have been checked for drift in
the specified stack.

Type annotations for
`session.create_client("cloudformation").describe_stack_resource_drifts`
method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_resource_drifts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_resource_drifts)

Asynchronous method. Use `await describe_stack_resource_drifts(...)` for a
synchronous call.

Arguments mapping described in
[DescribeStackResourceDriftsInputRequestTypeDef](./type_defs.md#describestackresourcedriftsinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `StackResourceDriftStatusFilters`:
  `Sequence`\[[StackResourceDriftStatusType](./literals.md#stackresourcedriftstatustype)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeStackResourceDriftsOutputTypeDef](./type_defs.md#describestackresourcedriftsoutputtypedef).

<a id="describe\_stack\_resources"></a>

### describe_stack_resources

Returns Amazon Web Services resource descriptions for running and deleted
stacks.

Type annotations for
`session.create_client("cloudformation").describe_stack_resources` method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_resources)

Asynchronous method. Use `await describe_stack_resources(...)` for a
synchronous call.

Arguments mapping described in
[DescribeStackResourcesInputRequestTypeDef](./type_defs.md#describestackresourcesinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str`
- `LogicalResourceId`: `str`
- `PhysicalResourceId`: `str`

Returns a `Coroutine` for
[DescribeStackResourcesOutputTypeDef](./type_defs.md#describestackresourcesoutputtypedef).

<a id="describe\_stack\_set"></a>

### describe_stack_set

.

Type annotations for
`session.create_client("cloudformation").describe_stack_set` method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_set)

Asynchronous method. Use `await describe_stack_set(...)` for a synchronous
call.

Arguments mapping described in
[DescribeStackSetInputRequestTypeDef](./type_defs.md#describestacksetinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[DescribeStackSetOutputTypeDef](./type_defs.md#describestacksetoutputtypedef).

<a id="describe\_stack\_set\_operation"></a>

### describe_stack_set_operation

Returns the description of the specified stack set operation.

Type annotations for
`session.create_client("cloudformation").describe_stack_set_operation` method.

Boto3 documentation:
[CloudFormation.Client.describe_stack_set_operation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_set_operation)

Asynchronous method. Use `await describe_stack_set_operation(...)` for a
synchronous call.

Arguments mapping described in
[DescribeStackSetOperationInputRequestTypeDef](./type_defs.md#describestacksetoperationinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `OperationId`: `str` *(required)*
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[DescribeStackSetOperationOutputTypeDef](./type_defs.md#describestacksetoperationoutputtypedef).

<a id="describe\_stacks"></a>

### describe_stacks

.

Type annotations for `session.create_client("cloudformation").describe_stacks`
method.

Boto3 documentation:
[CloudFormation.Client.describe_stacks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stacks)

Asynchronous method. Use `await describe_stacks(...)` for a synchronous call.

Arguments mapping described in
[DescribeStacksInputRequestTypeDef](./type_defs.md#describestacksinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeStacksOutputTypeDef](./type_defs.md#describestacksoutputtypedef).

<a id="describe\_type"></a>

### describe_type

Returns detailed information about an extension that has been registered.

Type annotations for `session.create_client("cloudformation").describe_type`
method.

Boto3 documentation:
[CloudFormation.Client.describe_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_type)

Asynchronous method. Use `await describe_type(...)` for a synchronous call.

Arguments mapping described in
[DescribeTypeInputRequestTypeDef](./type_defs.md#describetypeinputrequesttypedef).

Keyword-only arguments:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `Arn`: `str`
- `VersionId`: `str`
- `PublisherId`: `str`
- `PublicVersionNumber`: `str`

Returns a `Coroutine` for
[DescribeTypeOutputTypeDef](./type_defs.md#describetypeoutputtypedef).

<a id="describe\_type\_registration"></a>

### describe_type_registration

Returns information about an extension's registration, including its current
status and type and version identifiers.

Type annotations for
`session.create_client("cloudformation").describe_type_registration` method.

Boto3 documentation:
[CloudFormation.Client.describe_type_registration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_type_registration)

Asynchronous method. Use `await describe_type_registration(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTypeRegistrationInputRequestTypeDef](./type_defs.md#describetyperegistrationinputrequesttypedef).

Keyword-only arguments:

- `RegistrationToken`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTypeRegistrationOutputTypeDef](./type_defs.md#describetyperegistrationoutputtypedef).

<a id="detect\_stack\_drift"></a>

### detect_stack_drift

Detects whether a stack's actual configuration differs, or has *drifted* , from
it's expected configuration, as defined in the stack template and any values
specified as template parameters.

Type annotations for
`session.create_client("cloudformation").detect_stack_drift` method.

Boto3 documentation:
[CloudFormation.Client.detect_stack_drift](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.detect_stack_drift)

Asynchronous method. Use `await detect_stack_drift(...)` for a synchronous
call.

Arguments mapping described in
[DetectStackDriftInputRequestTypeDef](./type_defs.md#detectstackdriftinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `LogicalResourceIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DetectStackDriftOutputTypeDef](./type_defs.md#detectstackdriftoutputtypedef).

<a id="detect\_stack\_resource\_drift"></a>

### detect_stack_resource_drift

Returns information about whether a resource's actual configuration differs, or
has *drifted* , from it's expected configuration, as defined in the stack
template and any values specified as template parameters.

Type annotations for
`session.create_client("cloudformation").detect_stack_resource_drift` method.

Boto3 documentation:
[CloudFormation.Client.detect_stack_resource_drift](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.detect_stack_resource_drift)

Asynchronous method. Use `await detect_stack_resource_drift(...)` for a
synchronous call.

Arguments mapping described in
[DetectStackResourceDriftInputRequestTypeDef](./type_defs.md#detectstackresourcedriftinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `LogicalResourceId`: `str` *(required)*

Returns a `Coroutine` for
[DetectStackResourceDriftOutputTypeDef](./type_defs.md#detectstackresourcedriftoutputtypedef).

<a id="detect\_stack\_set\_drift"></a>

### detect_stack_set_drift

Detect drift on a stack set.

Type annotations for
`session.create_client("cloudformation").detect_stack_set_drift` method.

Boto3 documentation:
[CloudFormation.Client.detect_stack_set_drift](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.detect_stack_set_drift)

Asynchronous method. Use `await detect_stack_set_drift(...)` for a synchronous
call.

Arguments mapping described in
[DetectStackSetDriftInputRequestTypeDef](./type_defs.md#detectstacksetdriftinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[DetectStackSetDriftOutputTypeDef](./type_defs.md#detectstacksetdriftoutputtypedef).

<a id="estimate\_template\_cost"></a>

### estimate_template_cost

.

Type annotations for
`session.create_client("cloudformation").estimate_template_cost` method.

Boto3 documentation:
[CloudFormation.Client.estimate_template_cost](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.estimate_template_cost)

Asynchronous method. Use `await estimate_template_cost(...)` for a synchronous
call.

Arguments mapping described in
[EstimateTemplateCostInputRequestTypeDef](./type_defs.md#estimatetemplatecostinputrequesttypedef).

Keyword-only arguments:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

Returns a `Coroutine` for
[EstimateTemplateCostOutputTypeDef](./type_defs.md#estimatetemplatecostoutputtypedef).

<a id="execute\_change\_set"></a>

### execute_change_set

Updates a stack using the input information that was provided when the
specified change set was created.

Type annotations for
`session.create_client("cloudformation").execute_change_set` method.

Boto3 documentation:
[CloudFormation.Client.execute_change_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.execute_change_set)

Asynchronous method. Use `await execute_change_set(...)` for a synchronous
call.

Arguments mapping described in
[ExecuteChangeSetInputRequestTypeDef](./type_defs.md#executechangesetinputrequesttypedef).

Keyword-only arguments:

- `ChangeSetName`: `str` *(required)*
- `StackName`: `str`
- `ClientRequestToken`: `str`
- `DisableRollback`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("cloudformation").generate_presigned_url` method.

Boto3 documentation:
[CloudFormation.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_stack\_policy"></a>

### get_stack_policy

Returns the stack policy for a specified stack.

Type annotations for `session.create_client("cloudformation").get_stack_policy`
method.

Boto3 documentation:
[CloudFormation.Client.get_stack_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.get_stack_policy)

Asynchronous method. Use `await get_stack_policy(...)` for a synchronous call.

Arguments mapping described in
[GetStackPolicyInputRequestTypeDef](./type_defs.md#getstackpolicyinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*

Returns a `Coroutine` for
[GetStackPolicyOutputTypeDef](./type_defs.md#getstackpolicyoutputtypedef).

<a id="get\_template"></a>

### get_template

Returns the template body for a specified stack.

Type annotations for `session.create_client("cloudformation").get_template`
method.

Boto3 documentation:
[CloudFormation.Client.get_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.get_template)

Asynchronous method. Use `await get_template(...)` for a synchronous call.

Arguments mapping described in
[GetTemplateInputRequestTypeDef](./type_defs.md#gettemplateinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str`
- `ChangeSetName`: `str`
- `TemplateStage`: [TemplateStageType](./literals.md#templatestagetype)

Returns a `Coroutine` for
[GetTemplateOutputTypeDef](./type_defs.md#gettemplateoutputtypedef).

<a id="get\_template\_summary"></a>

### get_template_summary

Returns information about a new or existing template.

Type annotations for
`session.create_client("cloudformation").get_template_summary` method.

Boto3 documentation:
[CloudFormation.Client.get_template_summary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.get_template_summary)

Asynchronous method. Use `await get_template_summary(...)` for a synchronous
call.

Arguments mapping described in
[GetTemplateSummaryInputRequestTypeDef](./type_defs.md#gettemplatesummaryinputrequesttypedef).

Keyword-only arguments:

- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `StackName`: `str`
- `StackSetName`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[GetTemplateSummaryOutputTypeDef](./type_defs.md#gettemplatesummaryoutputtypedef).

<a id="import\_stacks\_to\_stack\_set"></a>

### import_stacks_to_stack_set

Import existing stacks into a new stack sets.

Type annotations for
`session.create_client("cloudformation").import_stacks_to_stack_set` method.

Boto3 documentation:
[CloudFormation.Client.import_stacks_to_stack_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.import_stacks_to_stack_set)

Asynchronous method. Use `await import_stacks_to_stack_set(...)` for a
synchronous call.

Arguments mapping described in
[ImportStacksToStackSetInputRequestTypeDef](./type_defs.md#importstackstostacksetinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `StackIds`: `Sequence`\[`str`\]
- `StackIdsUrl`: `str`
- `OrganizationalUnitIds`: `Sequence`\[`str`\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[ImportStacksToStackSetOutputTypeDef](./type_defs.md#importstackstostacksetoutputtypedef).

<a id="list\_change\_sets"></a>

### list_change_sets

Returns the ID and status of each active change set for a stack.

Type annotations for `session.create_client("cloudformation").list_change_sets`
method.

Boto3 documentation:
[CloudFormation.Client.list_change_sets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_change_sets)

Asynchronous method. Use `await list_change_sets(...)` for a synchronous call.

Arguments mapping described in
[ListChangeSetsInputRequestTypeDef](./type_defs.md#listchangesetsinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[ListChangeSetsOutputTypeDef](./type_defs.md#listchangesetsoutputtypedef).

<a id="list\_exports"></a>

### list_exports

.

Type annotations for `session.create_client("cloudformation").list_exports`
method.

Boto3 documentation:
[CloudFormation.Client.list_exports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_exports)

Asynchronous method. Use `await list_exports(...)` for a synchronous call.

Arguments mapping described in
[ListExportsInputRequestTypeDef](./type_defs.md#listexportsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`

Returns a `Coroutine` for
[ListExportsOutputTypeDef](./type_defs.md#listexportsoutputtypedef).

<a id="list\_imports"></a>

### list_imports

.

Type annotations for `session.create_client("cloudformation").list_imports`
method.

Boto3 documentation:
[CloudFormation.Client.list_imports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_imports)

Asynchronous method. Use `await list_imports(...)` for a synchronous call.

Arguments mapping described in
[ListImportsInputRequestTypeDef](./type_defs.md#listimportsinputrequesttypedef).

Keyword-only arguments:

- `ExportName`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[ListImportsOutputTypeDef](./type_defs.md#listimportsoutputtypedef).

<a id="list\_stack\_instances"></a>

### list_stack_instances

Returns summary information about stack instances that are associated with the
specified stack set.

Type annotations for
`session.create_client("cloudformation").list_stack_instances` method.

Boto3 documentation:
[CloudFormation.Client.list_stack_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_stack_instances)

Asynchronous method. Use `await list_stack_instances(...)` for a synchronous
call.

Arguments mapping described in
[ListStackInstancesInputRequestTypeDef](./type_defs.md#liststackinstancesinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`:
  `Sequence`\[[StackInstanceFilterTypeDef](./type_defs.md#stackinstancefiltertypedef)\]
- `StackInstanceAccount`: `str`
- `StackInstanceRegion`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[ListStackInstancesOutputTypeDef](./type_defs.md#liststackinstancesoutputtypedef).

<a id="list\_stack\_resources"></a>

### list_stack_resources

Returns descriptions of all resources of the specified stack.

Type annotations for
`session.create_client("cloudformation").list_stack_resources` method.

Boto3 documentation:
[CloudFormation.Client.list_stack_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_stack_resources)

Asynchronous method. Use `await list_stack_resources(...)` for a synchronous
call.

Arguments mapping described in
[ListStackResourcesInputRequestTypeDef](./type_defs.md#liststackresourcesinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[ListStackResourcesOutputTypeDef](./type_defs.md#liststackresourcesoutputtypedef).

<a id="list\_stack\_set\_operation\_results"></a>

### list_stack_set_operation_results

Returns summary information about the results of a stack set operation.

Type annotations for
`session.create_client("cloudformation").list_stack_set_operation_results`
method.

Boto3 documentation:
[CloudFormation.Client.list_stack_set_operation_results](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_stack_set_operation_results)

Asynchronous method. Use `await list_stack_set_operation_results(...)` for a
synchronous call.

Arguments mapping described in
[ListStackSetOperationResultsInputRequestTypeDef](./type_defs.md#liststacksetoperationresultsinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `OperationId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[ListStackSetOperationResultsOutputTypeDef](./type_defs.md#liststacksetoperationresultsoutputtypedef).

<a id="list\_stack\_set\_operations"></a>

### list_stack_set_operations

Returns summary information about operations performed on a stack set.

Type annotations for
`session.create_client("cloudformation").list_stack_set_operations` method.

Boto3 documentation:
[CloudFormation.Client.list_stack_set_operations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_stack_set_operations)

Asynchronous method. Use `await list_stack_set_operations(...)` for a
synchronous call.

Arguments mapping described in
[ListStackSetOperationsInputRequestTypeDef](./type_defs.md#liststacksetoperationsinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[ListStackSetOperationsOutputTypeDef](./type_defs.md#liststacksetoperationsoutputtypedef).

<a id="list\_stack\_sets"></a>

### list_stack_sets

Returns summary information about stack sets that are associated with the user.

Type annotations for `session.create_client("cloudformation").list_stack_sets`
method.

Boto3 documentation:
[CloudFormation.Client.list_stack_sets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_stack_sets)

Asynchronous method. Use `await list_stack_sets(...)` for a synchronous call.

Arguments mapping described in
[ListStackSetsInputRequestTypeDef](./type_defs.md#liststacksetsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Status`: [StackSetStatusType](./literals.md#stacksetstatustype)
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[ListStackSetsOutputTypeDef](./type_defs.md#liststacksetsoutputtypedef).

<a id="list\_stacks"></a>

### list_stacks

Returns the summary information for stacks whose status matches the specified
StackStatusFilter.

Type annotations for `session.create_client("cloudformation").list_stacks`
method.

Boto3 documentation:
[CloudFormation.Client.list_stacks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_stacks)

Asynchronous method. Use `await list_stacks(...)` for a synchronous call.

Arguments mapping described in
[ListStacksInputRequestTypeDef](./type_defs.md#liststacksinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `StackStatusFilter`:
  `Sequence`\[[StackStatusType](./literals.md#stackstatustype)\]

Returns a `Coroutine` for
[ListStacksOutputTypeDef](./type_defs.md#liststacksoutputtypedef).

<a id="list\_type\_registrations"></a>

### list_type_registrations

Returns a list of registration tokens for the specified extension(s).

Type annotations for
`session.create_client("cloudformation").list_type_registrations` method.

Boto3 documentation:
[CloudFormation.Client.list_type_registrations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_type_registrations)

Asynchronous method. Use `await list_type_registrations(...)` for a synchronous
call.

Arguments mapping described in
[ListTypeRegistrationsInputRequestTypeDef](./type_defs.md#listtyperegistrationsinputrequesttypedef).

Keyword-only arguments:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `TypeArn`: `str`
- `RegistrationStatusFilter`:
  [RegistrationStatusType](./literals.md#registrationstatustype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTypeRegistrationsOutputTypeDef](./type_defs.md#listtyperegistrationsoutputtypedef).

<a id="list\_type\_versions"></a>

### list_type_versions

Returns summary information about the versions of an extension.

Type annotations for
`session.create_client("cloudformation").list_type_versions` method.

Boto3 documentation:
[CloudFormation.Client.list_type_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_type_versions)

Asynchronous method. Use `await list_type_versions(...)` for a synchronous
call.

Arguments mapping described in
[ListTypeVersionsInputRequestTypeDef](./type_defs.md#listtypeversionsinputrequesttypedef).

Keyword-only arguments:

- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `Arn`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`
- `DeprecatedStatus`:
  [DeprecatedStatusType](./literals.md#deprecatedstatustype)
- `PublisherId`: `str`

Returns a `Coroutine` for
[ListTypeVersionsOutputTypeDef](./type_defs.md#listtypeversionsoutputtypedef).

<a id="list\_types"></a>

### list_types

Returns summary information about extension that have been registered with
CloudFormation.

Type annotations for `session.create_client("cloudformation").list_types`
method.

Boto3 documentation:
[CloudFormation.Client.list_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.list_types)

Asynchronous method. Use `await list_types(...)` for a synchronous call.

Arguments mapping described in
[ListTypesInputRequestTypeDef](./type_defs.md#listtypesinputrequesttypedef).

Keyword-only arguments:

- `Visibility`: [VisibilityType](./literals.md#visibilitytype)
- `ProvisioningType`:
  [ProvisioningTypeType](./literals.md#provisioningtypetype)
- `DeprecatedStatus`:
  [DeprecatedStatusType](./literals.md#deprecatedstatustype)
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `Filters`: [TypeFiltersTypeDef](./type_defs.md#typefilterstypedef)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTypesOutputTypeDef](./type_defs.md#listtypesoutputtypedef).

<a id="publish\_type"></a>

### publish_type

Publishes the specified extension to the CloudFormation registry as a public
extension in this region.

Type annotations for `session.create_client("cloudformation").publish_type`
method.

Boto3 documentation:
[CloudFormation.Client.publish_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.publish_type)

Asynchronous method. Use `await publish_type(...)` for a synchronous call.

Arguments mapping described in
[PublishTypeInputRequestTypeDef](./type_defs.md#publishtypeinputrequesttypedef).

Keyword-only arguments:

- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `Arn`: `str`
- `TypeName`: `str`
- `PublicVersionNumber`: `str`

Returns a `Coroutine` for
[PublishTypeOutputTypeDef](./type_defs.md#publishtypeoutputtypedef).

<a id="record\_handler\_progress"></a>

### record_handler_progress

Reports progress of a resource handler to CloudFormation.

Type annotations for
`session.create_client("cloudformation").record_handler_progress` method.

Boto3 documentation:
[CloudFormation.Client.record_handler_progress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.record_handler_progress)

Asynchronous method. Use `await record_handler_progress(...)` for a synchronous
call.

Arguments mapping described in
[RecordHandlerProgressInputRequestTypeDef](./type_defs.md#recordhandlerprogressinputrequesttypedef).

Keyword-only arguments:

- `BearerToken`: `str` *(required)*
- `OperationStatus`: [OperationStatusType](./literals.md#operationstatustype)
  *(required)*
- `CurrentOperationStatus`:
  [OperationStatusType](./literals.md#operationstatustype)
- `StatusMessage`: `str`
- `ErrorCode`: [HandlerErrorCodeType](./literals.md#handlererrorcodetype)
- `ResourceModel`: `str`
- `ClientRequestToken`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="register\_publisher"></a>

### register_publisher

Registers your account as a publisher of public extensions in the
CloudFormation registry.

Type annotations for
`session.create_client("cloudformation").register_publisher` method.

Boto3 documentation:
[CloudFormation.Client.register_publisher](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.register_publisher)

Asynchronous method. Use `await register_publisher(...)` for a synchronous
call.

Arguments mapping described in
[RegisterPublisherInputRequestTypeDef](./type_defs.md#registerpublisherinputrequesttypedef).

Keyword-only arguments:

- `AcceptTermsAndConditions`: `bool`
- `ConnectionArn`: `str`

Returns a `Coroutine` for
[RegisterPublisherOutputTypeDef](./type_defs.md#registerpublisheroutputtypedef).

<a id="register\_type"></a>

### register_type

Registers an extension with the CloudFormation service.

Type annotations for `session.create_client("cloudformation").register_type`
method.

Boto3 documentation:
[CloudFormation.Client.register_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.register_type)

Asynchronous method. Use `await register_type(...)` for a synchronous call.

Arguments mapping described in
[RegisterTypeInputRequestTypeDef](./type_defs.md#registertypeinputrequesttypedef).

Keyword-only arguments:

- `TypeName`: `str` *(required)*
- `SchemaHandlerPackage`: `str` *(required)*
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `LoggingConfig`: [LoggingConfigTypeDef](./type_defs.md#loggingconfigtypedef)
- `ExecutionRoleArn`: `str`
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[RegisterTypeOutputTypeDef](./type_defs.md#registertypeoutputtypedef).

<a id="rollback\_stack"></a>

### rollback_stack

When specifying `RollbackStack` , you preserve the state of previously
provisioned resources when an operation fails.

Type annotations for `session.create_client("cloudformation").rollback_stack`
method.

Boto3 documentation:
[CloudFormation.Client.rollback_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.rollback_stack)

Asynchronous method. Use `await rollback_stack(...)` for a synchronous call.

Arguments mapping described in
[RollbackStackInputRequestTypeDef](./type_defs.md#rollbackstackinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `RoleARN`: `str`
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[RollbackStackOutputTypeDef](./type_defs.md#rollbackstackoutputtypedef).

<a id="set\_stack\_policy"></a>

### set_stack_policy

Sets a stack policy for a specified stack.

Type annotations for `session.create_client("cloudformation").set_stack_policy`
method.

Boto3 documentation:
[CloudFormation.Client.set_stack_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.set_stack_policy)

Asynchronous method. Use `await set_stack_policy(...)` for a synchronous call.

Arguments mapping described in
[SetStackPolicyInputRequestTypeDef](./type_defs.md#setstackpolicyinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `StackPolicyBody`: `str`
- `StackPolicyURL`: `str`

<a id="set\_type\_configuration"></a>

### set_type_configuration

Specifies the configuration data for a registered CloudFormation extension, in
the given account and region.

Type annotations for
`session.create_client("cloudformation").set_type_configuration` method.

Boto3 documentation:
[CloudFormation.Client.set_type_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.set_type_configuration)

Asynchronous method. Use `await set_type_configuration(...)` for a synchronous
call.

Arguments mapping described in
[SetTypeConfigurationInputRequestTypeDef](./type_defs.md#settypeconfigurationinputrequesttypedef).

Keyword-only arguments:

- `Configuration`: `str` *(required)*
- `TypeArn`: `str`
- `ConfigurationAlias`: `str`
- `TypeName`: `str`
- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)

Returns a `Coroutine` for
[SetTypeConfigurationOutputTypeDef](./type_defs.md#settypeconfigurationoutputtypedef).

<a id="set\_type\_default\_version"></a>

### set_type_default_version

Specify the default version of an extension.

Type annotations for
`session.create_client("cloudformation").set_type_default_version` method.

Boto3 documentation:
[CloudFormation.Client.set_type_default_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.set_type_default_version)

Asynchronous method. Use `await set_type_default_version(...)` for a
synchronous call.

Arguments mapping described in
[SetTypeDefaultVersionInputRequestTypeDef](./type_defs.md#settypedefaultversioninputrequesttypedef).

Keyword-only arguments:

- `Arn`: `str`
- `Type`: [RegistryTypeType](./literals.md#registrytypetype)
- `TypeName`: `str`
- `VersionId`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="signal\_resource"></a>

### signal_resource

Sends a signal to the specified resource with a success or failure status.

Type annotations for `session.create_client("cloudformation").signal_resource`
method.

Boto3 documentation:
[CloudFormation.Client.signal_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.signal_resource)

Asynchronous method. Use `await signal_resource(...)` for a synchronous call.

Arguments mapping described in
[SignalResourceInputRequestTypeDef](./type_defs.md#signalresourceinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
- `LogicalResourceId`: `str` *(required)*
- `UniqueId`: `str` *(required)*
- `Status`: [ResourceSignalStatusType](./literals.md#resourcesignalstatustype)
  *(required)*

<a id="stop\_stack\_set\_operation"></a>

### stop_stack_set_operation

Stops an in-progress operation on a stack set and its associated stack
instances.

Type annotations for
`session.create_client("cloudformation").stop_stack_set_operation` method.

Boto3 documentation:
[CloudFormation.Client.stop_stack_set_operation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.stop_stack_set_operation)

Asynchronous method. Use `await stop_stack_set_operation(...)` for a
synchronous call.

Arguments mapping described in
[StopStackSetOperationInputRequestTypeDef](./type_defs.md#stopstacksetoperationinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `OperationId`: `str` *(required)*
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="test\_type"></a>

### test_type

Tests a registered extension to make sure it meets all necessary requirements
for being published in the CloudFormation registry.

Type annotations for `session.create_client("cloudformation").test_type`
method.

Boto3 documentation:
[CloudFormation.Client.test_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.test_type)

Asynchronous method. Use `await test_type(...)` for a synchronous call.

Arguments mapping described in
[TestTypeInputRequestTypeDef](./type_defs.md#testtypeinputrequesttypedef).

Keyword-only arguments:

- `Arn`: `str`
- `Type`: [ThirdPartyTypeType](./literals.md#thirdpartytypetype)
- `TypeName`: `str`
- `VersionId`: `str`
- `LogDeliveryBucket`: `str`

Returns a `Coroutine` for
[TestTypeOutputTypeDef](./type_defs.md#testtypeoutputtypedef).

<a id="update\_stack"></a>

### update_stack

.

Type annotations for `session.create_client("cloudformation").update_stack`
method.

Boto3 documentation:
[CloudFormation.Client.update_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.update_stack)

Asynchronous method. Use `await update_stack(...)` for a synchronous call.

Arguments mapping described in
[UpdateStackInputRequestTypeDef](./type_defs.md#updatestackinputrequesttypedef).

Keyword-only arguments:

- `StackName`: `str` *(required)*
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

<a id="update\_stack\_instances"></a>

### update_stack_instances

.

Type annotations for
`session.create_client("cloudformation").update_stack_instances` method.

Boto3 documentation:
[CloudFormation.Client.update_stack_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.update_stack_instances)

Asynchronous method. Use `await update_stack_instances(...)` for a synchronous
call.

Arguments mapping described in
[UpdateStackInstancesInputRequestTypeDef](./type_defs.md#updatestackinstancesinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `Regions`: `Sequence`\[`str`\] *(required)*
- `Accounts`: `Sequence`\[`str`\]
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `ParameterOverrides`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `OperationId`: `str`
- `CallAs`: [CallAsType](./literals.md#callastype)

Returns a `Coroutine` for
[UpdateStackInstancesOutputTypeDef](./type_defs.md#updatestackinstancesoutputtypedef).

<a id="update\_stack\_set"></a>

### update_stack_set

.

Type annotations for `session.create_client("cloudformation").update_stack_set`
method.

Boto3 documentation:
[CloudFormation.Client.update_stack_set](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.update_stack_set)

Asynchronous method. Use `await update_stack_set(...)` for a synchronous call.

Arguments mapping described in
[UpdateStackSetInputRequestTypeDef](./type_defs.md#updatestacksetinputrequesttypedef).

Keyword-only arguments:

- `StackSetName`: `str` *(required)*
- `Description`: `str`
- `TemplateBody`: `str`
- `TemplateURL`: `str`
- `UsePreviousTemplate`: `bool`
- `Parameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `Capabilities`: `Sequence`\[[CapabilityType](./literals.md#capabilitytype)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `OperationPreferences`:
  [StackSetOperationPreferencesTypeDef](./type_defs.md#stacksetoperationpreferencestypedef)
- `AdministrationRoleARN`: `str`
- `ExecutionRoleName`: `str`
- `DeploymentTargets`:
  [DeploymentTargetsTypeDef](./type_defs.md#deploymenttargetstypedef)
- `PermissionModel`: [PermissionModelsType](./literals.md#permissionmodelstype)
- `AutoDeployment`:
  [AutoDeploymentTypeDef](./type_defs.md#autodeploymenttypedef)
- `OperationId`: `str`
- `Accounts`: `Sequence`\[`str`\]
- `Regions`: `Sequence`\[`str`\]
- `CallAs`: [CallAsType](./literals.md#callastype)
- `ManagedExecution`:
  [ManagedExecutionTypeDef](./type_defs.md#managedexecutiontypedef)

Returns a `Coroutine` for
[UpdateStackSetOutputTypeDef](./type_defs.md#updatestacksetoutputtypedef).

<a id="update\_termination\_protection"></a>

### update_termination_protection

Updates termination protection for the specified stack.

Type annotations for
`session.create_client("cloudformation").update_termination_protection` method.

Boto3 documentation:
[CloudFormation.Client.update_termination_protection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.update_termination_protection)

Asynchronous method. Use `await update_termination_protection(...)` for a
synchronous call.

Arguments mapping described in
[UpdateTerminationProtectionInputRequestTypeDef](./type_defs.md#updateterminationprotectioninputrequesttypedef).

Keyword-only arguments:

- `EnableTerminationProtection`: `bool` *(required)*
- `StackName`: `str` *(required)*

Returns a `Coroutine` for
[UpdateTerminationProtectionOutputTypeDef](./type_defs.md#updateterminationprotectionoutputtypedef).

<a id="validate\_template"></a>

### validate_template

Validates a specified template.

Type annotations for
`session.create_client("cloudformation").validate_template` method.

Boto3 documentation:
[CloudFormation.Client.validate_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.validate_template)

Asynchronous method. Use `await validate_template(...)` for a synchronous call.

Arguments mapping described in
[ValidateTemplateInputRequestTypeDef](./type_defs.md#validatetemplateinputrequesttypedef).

Keyword-only arguments:

- `TemplateBody`: `str`
- `TemplateURL`: `str`

Returns a `Coroutine` for
[ValidateTemplateOutputTypeDef](./type_defs.md#validatetemplateoutputtypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("cloudformation").__aenter__`
method.

Boto3 documentation:
[CloudFormation.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [CloudFormationClient](#cloudformationclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("cloudformation").__aexit__`
method.

Boto3 documentation:
[CloudFormation.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("cloudformation").get_paginator`
method with overloads.

- `client.get_paginator("describe_account_limits")` ->
  [DescribeAccountLimitsPaginator](./paginators.md#describeaccountlimitspaginator)
- `client.get_paginator("describe_change_set")` ->
  [DescribeChangeSetPaginator](./paginators.md#describechangesetpaginator)
- `client.get_paginator("describe_stack_events")` ->
  [DescribeStackEventsPaginator](./paginators.md#describestackeventspaginator)
- `client.get_paginator("describe_stacks")` ->
  [DescribeStacksPaginator](./paginators.md#describestackspaginator)
- `client.get_paginator("list_change_sets")` ->
  [ListChangeSetsPaginator](./paginators.md#listchangesetspaginator)
- `client.get_paginator("list_exports")` ->
  [ListExportsPaginator](./paginators.md#listexportspaginator)
- `client.get_paginator("list_imports")` ->
  [ListImportsPaginator](./paginators.md#listimportspaginator)
- `client.get_paginator("list_stack_instances")` ->
  [ListStackInstancesPaginator](./paginators.md#liststackinstancespaginator)
- `client.get_paginator("list_stack_resources")` ->
  [ListStackResourcesPaginator](./paginators.md#liststackresourcespaginator)
- `client.get_paginator("list_stack_set_operation_results")` ->
  [ListStackSetOperationResultsPaginator](./paginators.md#liststacksetoperationresultspaginator)
- `client.get_paginator("list_stack_set_operations")` ->
  [ListStackSetOperationsPaginator](./paginators.md#liststacksetoperationspaginator)
- `client.get_paginator("list_stack_sets")` ->
  [ListStackSetsPaginator](./paginators.md#liststacksetspaginator)
- `client.get_paginator("list_stacks")` ->
  [ListStacksPaginator](./paginators.md#liststackspaginator)
- `client.get_paginator("list_types")` ->
  [ListTypesPaginator](./paginators.md#listtypespaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("cloudformation").get_waiter`
method with overloads.

- `client.get_waiter("change_set_create_complete")` ->
  [ChangeSetCreateCompleteWaiter](./waiters.md#changesetcreatecompletewaiter)
- `client.get_waiter("stack_create_complete")` ->
  [StackCreateCompleteWaiter](./waiters.md#stackcreatecompletewaiter)
- `client.get_waiter("stack_delete_complete")` ->
  [StackDeleteCompleteWaiter](./waiters.md#stackdeletecompletewaiter)
- `client.get_waiter("stack_exists")` ->
  [StackExistsWaiter](./waiters.md#stackexistswaiter)
- `client.get_waiter("stack_import_complete")` ->
  [StackImportCompleteWaiter](./waiters.md#stackimportcompletewaiter)
- `client.get_waiter("stack_rollback_complete")` ->
  [StackRollbackCompleteWaiter](./waiters.md#stackrollbackcompletewaiter)
- `client.get_waiter("stack_update_complete")` ->
  [StackUpdateCompleteWaiter](./waiters.md#stackupdatecompletewaiter)
- `client.get_waiter("type_registration_complete")` ->
  [TypeRegistrationCompleteWaiter](./waiters.md#typeregistrationcompletewaiter)
