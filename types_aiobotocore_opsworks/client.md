<a id="opsworksclient-for-aiobotocore-opsworks-module"></a>

# OpsWorksClient for aiobotocore OpsWorks module

> [Index](..) > [OpsWorks](.) > OpsWorksClient

Auto-generated documentation for
[OpsWorks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
type annotations stubs module
[types-aiobotocore-opsworks](https://pypi.org/project/types-aiobotocore-opsworks/).

- [OpsWorksClient for aiobotocore OpsWorks module](#opsworksclient-for-aiobotocore-opsworks-module)
  - [OpsWorksClient](#opsworksclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [assign_instance](#assign_instance)
    - [assign_volume](#assign_volume)
    - [associate_elastic_ip](#associate_elastic_ip)
    - [attach_elastic_load_balancer](#attach_elastic_load_balancer)
    - [can_paginate](#can_paginate)
    - [clone_stack](#clone_stack)
    - [create_app](#create_app)
    - [create_deployment](#create_deployment)
    - [create_instance](#create_instance)
    - [create_layer](#create_layer)
    - [create_stack](#create_stack)
    - [create_user_profile](#create_user_profile)
    - [delete_app](#delete_app)
    - [delete_instance](#delete_instance)
    - [delete_layer](#delete_layer)
    - [delete_stack](#delete_stack)
    - [delete_user_profile](#delete_user_profile)
    - [deregister_ecs_cluster](#deregister_ecs_cluster)
    - [deregister_elastic_ip](#deregister_elastic_ip)
    - [deregister_instance](#deregister_instance)
    - [deregister_rds_db_instance](#deregister_rds_db_instance)
    - [deregister_volume](#deregister_volume)
    - [describe_agent_versions](#describe_agent_versions)
    - [describe_apps](#describe_apps)
    - [describe_commands](#describe_commands)
    - [describe_deployments](#describe_deployments)
    - [describe_ecs_clusters](#describe_ecs_clusters)
    - [describe_elastic_ips](#describe_elastic_ips)
    - [describe_elastic_load_balancers](#describe_elastic_load_balancers)
    - [describe_instances](#describe_instances)
    - [describe_layers](#describe_layers)
    - [describe_load_based_auto_scaling](#describe_load_based_auto_scaling)
    - [describe_my_user_profile](#describe_my_user_profile)
    - [describe_operating_systems](#describe_operating_systems)
    - [describe_permissions](#describe_permissions)
    - [describe_raid_arrays](#describe_raid_arrays)
    - [describe_rds_db_instances](#describe_rds_db_instances)
    - [describe_service_errors](#describe_service_errors)
    - [describe_stack_provisioning_parameters](#describe_stack_provisioning_parameters)
    - [describe_stack_summary](#describe_stack_summary)
    - [describe_stacks](#describe_stacks)
    - [describe_time_based_auto_scaling](#describe_time_based_auto_scaling)
    - [describe_user_profiles](#describe_user_profiles)
    - [describe_volumes](#describe_volumes)
    - [detach_elastic_load_balancer](#detach_elastic_load_balancer)
    - [disassociate_elastic_ip](#disassociate_elastic_ip)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_hostname_suggestion](#get_hostname_suggestion)
    - [grant_access](#grant_access)
    - [list_tags](#list_tags)
    - [reboot_instance](#reboot_instance)
    - [register_ecs_cluster](#register_ecs_cluster)
    - [register_elastic_ip](#register_elastic_ip)
    - [register_instance](#register_instance)
    - [register_rds_db_instance](#register_rds_db_instance)
    - [register_volume](#register_volume)
    - [set_load_based_auto_scaling](#set_load_based_auto_scaling)
    - [set_permission](#set_permission)
    - [set_time_based_auto_scaling](#set_time_based_auto_scaling)
    - [start_instance](#start_instance)
    - [start_stack](#start_stack)
    - [stop_instance](#stop_instance)
    - [stop_stack](#stop_stack)
    - [tag_resource](#tag_resource)
    - [unassign_instance](#unassign_instance)
    - [unassign_volume](#unassign_volume)
    - [untag_resource](#untag_resource)
    - [update_app](#update_app)
    - [update_elastic_ip](#update_elastic_ip)
    - [update_instance](#update_instance)
    - [update_layer](#update_layer)
    - [update_my_user_profile](#update_my_user_profile)
    - [update_rds_db_instance](#update_rds_db_instance)
    - [update_stack](#update_stack)
    - [update_user_profile](#update_user_profile)
    - [update_volume](#update_volume)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="opsworksclient"></a>

## OpsWorksClient

Type annotations for `aiobotocore.create_client("opsworks")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_opsworks.client import OpsWorksClient

def get_opsworks_client() -> OpsWorksClient:
    return Session().client("opsworks")
```

Boto3 documentation:
[OpsWorks.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_opsworks.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

OpsWorksClient exceptions.

Type annotations for `aiobotocore.create_client("opsworks").exceptions` method.

Boto3 documentation:
[OpsWorks.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="assign_instance"></a>

### assign_instance

Assign a registered instance to a layer.

Type annotations for `aiobotocore.create_client("opsworks").assign_instance`
method.

Boto3 documentation:
[OpsWorks.Client.assign_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.assign_instance)

Asynchronous method. Use `await assign_instance(...)` for a synchronous call.

Arguments mapping described in
[AssignInstanceRequestRequestTypeDef](./type_defs.md#assigninstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `LayerIds`: `Sequence`\[`str`\] *(required)*

<a id="assign_volume"></a>

### assign_volume

Assigns one of the stack's registered Amazon EBS volumes to a specified
instance.

Type annotations for `aiobotocore.create_client("opsworks").assign_volume`
method.

Boto3 documentation:
[OpsWorks.Client.assign_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.assign_volume)

Asynchronous method. Use `await assign_volume(...)` for a synchronous call.

Arguments mapping described in
[AssignVolumeRequestRequestTypeDef](./type_defs.md#assignvolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `InstanceId`: `str`

<a id="associate_elastic_ip"></a>

### associate_elastic_ip

Associates one of the stack's registered Elastic IP addresses with a specified
instance.

Type annotations for
`aiobotocore.create_client("opsworks").associate_elastic_ip` method.

Boto3 documentation:
[OpsWorks.Client.associate_elastic_ip](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.associate_elastic_ip)

Asynchronous method. Use `await associate_elastic_ip(...)` for a synchronous
call.

Arguments mapping described in
[AssociateElasticIpRequestRequestTypeDef](./type_defs.md#associateelasticiprequestrequesttypedef).

Keyword-only arguments:

- `ElasticIp`: `str` *(required)*
- `InstanceId`: `str`

<a id="attach_elastic_load_balancer"></a>

### attach_elastic_load_balancer

Attaches an Elastic Load Balancing load balancer to a specified layer.

Type annotations for
`aiobotocore.create_client("opsworks").attach_elastic_load_balancer` method.

Boto3 documentation:
[OpsWorks.Client.attach_elastic_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.attach_elastic_load_balancer)

Asynchronous method. Use `await attach_elastic_load_balancer(...)` for a
synchronous call.

Arguments mapping described in
[AttachElasticLoadBalancerRequestRequestTypeDef](./type_defs.md#attachelasticloadbalancerrequestrequesttypedef).

Keyword-only arguments:

- `ElasticLoadBalancerName`: `str` *(required)*
- `LayerId`: `str` *(required)*

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("opsworks").can_paginate`
method.

Boto3 documentation:
[OpsWorks.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="clone_stack"></a>

### clone_stack

Creates a clone of a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").clone_stack`
method.

Boto3 documentation:
[OpsWorks.Client.clone_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.clone_stack)

Asynchronous method. Use `await clone_stack(...)` for a synchronous call.

Arguments mapping described in
[CloneStackRequestRequestTypeDef](./type_defs.md#clonestackrequestrequesttypedef).

Keyword-only arguments:

- `SourceStackId`: `str` *(required)*
- `ServiceRoleArn`: `str` *(required)*
- `Name`: `str`
- `Region`: `str`
- `VpcId`: `str`
- `Attributes`: `Mapping`\[`Literal['Color']` (see
  [StackAttributesKeysType](./literals.md#stackattributeskeystype)), `str`\]
- `DefaultInstanceProfileArn`: `str`
- `DefaultOs`: `str`
- `HostnameTheme`: `str`
- `DefaultAvailabilityZone`: `str`
- `DefaultSubnetId`: `str`
- `CustomJson`: `str`
- `ConfigurationManager`:
  [StackConfigurationManagerTypeDef](./type_defs.md#stackconfigurationmanagertypedef)
- `ChefConfiguration`:
  [ChefConfigurationTypeDef](./type_defs.md#chefconfigurationtypedef)
- `UseCustomCookbooks`: `bool`
- `UseOpsworksSecurityGroups`: `bool`
- `CustomCookbooksSource`: [SourceTypeDef](./type_defs.md#sourcetypedef)
- `DefaultSshKeyName`: `str`
- `ClonePermissions`: `bool`
- `CloneAppIds`: `Sequence`\[`str`\]
- `DefaultRootDeviceType`:
  [RootDeviceTypeType](./literals.md#rootdevicetypetype)
- `AgentVersion`: `str`

Returns a `Coroutine` for
[CloneStackResultTypeDef](./type_defs.md#clonestackresulttypedef).

<a id="create_app"></a>

### create_app

Creates an app for a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").create_app` method.

Boto3 documentation:
[OpsWorks.Client.create_app](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.create_app)

Asynchronous method. Use `await create_app(...)` for a synchronous call.

Arguments mapping described in
[CreateAppRequestRequestTypeDef](./type_defs.md#createapprequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Type`: [AppTypeType](./literals.md#apptypetype) *(required)*
- `Shortname`: `str`
- `Description`: `str`
- `DataSources`:
  `Sequence`\[[DataSourceTypeDef](./type_defs.md#datasourcetypedef)\]
- `AppSource`: [SourceTypeDef](./type_defs.md#sourcetypedef)
- `Domains`: `Sequence`\[`str`\]
- `EnableSsl`: `bool`
- `SslConfiguration`:
  [SslConfigurationTypeDef](./type_defs.md#sslconfigurationtypedef)
- `Attributes`:
  `Mapping`\[[AppAttributesKeysType](./literals.md#appattributeskeystype),
  `str`\]
- `Environment`:
  `Sequence`\[[EnvironmentVariableTypeDef](./type_defs.md#environmentvariabletypedef)\]

Returns a `Coroutine` for
[CreateAppResultTypeDef](./type_defs.md#createappresulttypedef).

<a id="create_deployment"></a>

### create_deployment

Runs deployment or stack commands.

Type annotations for `aiobotocore.create_client("opsworks").create_deployment`
method.

Boto3 documentation:
[OpsWorks.Client.create_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.create_deployment)

Asynchronous method. Use `await create_deployment(...)` for a synchronous call.

Arguments mapping described in
[CreateDeploymentRequestRequestTypeDef](./type_defs.md#createdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `Command`:
  [DeploymentCommandTypeDef](./type_defs.md#deploymentcommandtypedef)
  *(required)*
- `AppId`: `str`
- `InstanceIds`: `Sequence`\[`str`\]
- `LayerIds`: `Sequence`\[`str`\]
- `Comment`: `str`
- `CustomJson`: `str`

Returns a `Coroutine` for
[CreateDeploymentResultTypeDef](./type_defs.md#createdeploymentresulttypedef).

<a id="create_instance"></a>

### create_instance

Creates an instance in a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").create_instance`
method.

Boto3 documentation:
[OpsWorks.Client.create_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.create_instance)

Asynchronous method. Use `await create_instance(...)` for a synchronous call.

Arguments mapping described in
[CreateInstanceRequestRequestTypeDef](./type_defs.md#createinstancerequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `LayerIds`: `Sequence`\[`str`\] *(required)*
- `InstanceType`: `str` *(required)*
- `AutoScalingType`: [AutoScalingTypeType](./literals.md#autoscalingtypetype)
- `Hostname`: `str`
- `Os`: `str`
- `AmiId`: `str`
- `SshKeyName`: `str`
- `AvailabilityZone`: `str`
- `VirtualizationType`: `str`
- `SubnetId`: `str`
- `Architecture`: [ArchitectureType](./literals.md#architecturetype)
- `RootDeviceType`: [RootDeviceTypeType](./literals.md#rootdevicetypetype)
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `InstallUpdatesOnBoot`: `bool`
- `EbsOptimized`: `bool`
- `AgentVersion`: `str`
- `Tenancy`: `str`

Returns a `Coroutine` for
[CreateInstanceResultTypeDef](./type_defs.md#createinstanceresulttypedef).

<a id="create_layer"></a>

### create_layer

Creates a layer.

Type annotations for `aiobotocore.create_client("opsworks").create_layer`
method.

Boto3 documentation:
[OpsWorks.Client.create_layer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.create_layer)

Asynchronous method. Use `await create_layer(...)` for a synchronous call.

Arguments mapping described in
[CreateLayerRequestRequestTypeDef](./type_defs.md#createlayerrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `Type`: [LayerTypeType](./literals.md#layertypetype) *(required)*
- `Name`: `str` *(required)*
- `Shortname`: `str` *(required)*
- `Attributes`:
  `Mapping`\[[LayerAttributesKeysType](./literals.md#layerattributeskeystype),
  `str`\]
- `CloudWatchLogsConfiguration`:
  [CloudWatchLogsConfigurationTypeDef](./type_defs.md#cloudwatchlogsconfigurationtypedef)
- `CustomInstanceProfileArn`: `str`
- `CustomJson`: `str`
- `CustomSecurityGroupIds`: `Sequence`\[`str`\]
- `Packages`: `Sequence`\[`str`\]
- `VolumeConfigurations`:
  `Sequence`\[[VolumeConfigurationTypeDef](./type_defs.md#volumeconfigurationtypedef)\]
- `EnableAutoHealing`: `bool`
- `AutoAssignElasticIps`: `bool`
- `AutoAssignPublicIps`: `bool`
- `CustomRecipes`: [RecipesTypeDef](./type_defs.md#recipestypedef)
- `InstallUpdatesOnBoot`: `bool`
- `UseEbsOptimizedInstances`: `bool`
- `LifecycleEventConfiguration`:
  [LifecycleEventConfigurationTypeDef](./type_defs.md#lifecycleeventconfigurationtypedef)

Returns a `Coroutine` for
[CreateLayerResultTypeDef](./type_defs.md#createlayerresulttypedef).

<a id="create_stack"></a>

### create_stack

Creates a new stack.

Type annotations for `aiobotocore.create_client("opsworks").create_stack`
method.

Boto3 documentation:
[OpsWorks.Client.create_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.create_stack)

Asynchronous method. Use `await create_stack(...)` for a synchronous call.

Arguments mapping described in
[CreateStackRequestRequestTypeDef](./type_defs.md#createstackrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Region`: `str` *(required)*
- `ServiceRoleArn`: `str` *(required)*
- `DefaultInstanceProfileArn`: `str` *(required)*
- `VpcId`: `str`
- `Attributes`: `Mapping`\[`Literal['Color']` (see
  [StackAttributesKeysType](./literals.md#stackattributeskeystype)), `str`\]
- `DefaultOs`: `str`
- `HostnameTheme`: `str`
- `DefaultAvailabilityZone`: `str`
- `DefaultSubnetId`: `str`
- `CustomJson`: `str`
- `ConfigurationManager`:
  [StackConfigurationManagerTypeDef](./type_defs.md#stackconfigurationmanagertypedef)
- `ChefConfiguration`:
  [ChefConfigurationTypeDef](./type_defs.md#chefconfigurationtypedef)
- `UseCustomCookbooks`: `bool`
- `UseOpsworksSecurityGroups`: `bool`
- `CustomCookbooksSource`: [SourceTypeDef](./type_defs.md#sourcetypedef)
- `DefaultSshKeyName`: `str`
- `DefaultRootDeviceType`:
  [RootDeviceTypeType](./literals.md#rootdevicetypetype)
- `AgentVersion`: `str`

Returns a `Coroutine` for
[CreateStackResultTypeDef](./type_defs.md#createstackresulttypedef).

<a id="create_user_profile"></a>

### create_user_profile

Creates a new user profile.

Type annotations for
`aiobotocore.create_client("opsworks").create_user_profile` method.

Boto3 documentation:
[OpsWorks.Client.create_user_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.create_user_profile)

Asynchronous method. Use `await create_user_profile(...)` for a synchronous
call.

Arguments mapping described in
[CreateUserProfileRequestRequestTypeDef](./type_defs.md#createuserprofilerequestrequesttypedef).

Keyword-only arguments:

- `IamUserArn`: `str` *(required)*
- `SshUsername`: `str`
- `SshPublicKey`: `str`
- `AllowSelfManagement`: `bool`

Returns a `Coroutine` for
[CreateUserProfileResultTypeDef](./type_defs.md#createuserprofileresulttypedef).

<a id="delete_app"></a>

### delete_app

Deletes a specified app.

Type annotations for `aiobotocore.create_client("opsworks").delete_app` method.

Boto3 documentation:
[OpsWorks.Client.delete_app](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.delete_app)

Asynchronous method. Use `await delete_app(...)` for a synchronous call.

Arguments mapping described in
[DeleteAppRequestRequestTypeDef](./type_defs.md#deleteapprequestrequesttypedef).

Keyword-only arguments:

- `AppId`: `str` *(required)*

<a id="delete_instance"></a>

### delete_instance

Deletes a specified instance, which terminates the associated Amazon EC2
instance.

Type annotations for `aiobotocore.create_client("opsworks").delete_instance`
method.

Boto3 documentation:
[OpsWorks.Client.delete_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.delete_instance)

Asynchronous method. Use `await delete_instance(...)` for a synchronous call.

Arguments mapping described in
[DeleteInstanceRequestRequestTypeDef](./type_defs.md#deleteinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `DeleteElasticIp`: `bool`
- `DeleteVolumes`: `bool`

<a id="delete_layer"></a>

### delete_layer

Deletes a specified layer.

Type annotations for `aiobotocore.create_client("opsworks").delete_layer`
method.

Boto3 documentation:
[OpsWorks.Client.delete_layer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.delete_layer)

Asynchronous method. Use `await delete_layer(...)` for a synchronous call.

Arguments mapping described in
[DeleteLayerRequestRequestTypeDef](./type_defs.md#deletelayerrequestrequesttypedef).

Keyword-only arguments:

- `LayerId`: `str` *(required)*

<a id="delete_stack"></a>

### delete_stack

Deletes a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").delete_stack`
method.

Boto3 documentation:
[OpsWorks.Client.delete_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.delete_stack)

Asynchronous method. Use `await delete_stack(...)` for a synchronous call.

Arguments mapping described in
[DeleteStackRequestRequestTypeDef](./type_defs.md#deletestackrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*

<a id="delete_user_profile"></a>

### delete_user_profile

Deletes a user profile.

Type annotations for
`aiobotocore.create_client("opsworks").delete_user_profile` method.

Boto3 documentation:
[OpsWorks.Client.delete_user_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.delete_user_profile)

Asynchronous method. Use `await delete_user_profile(...)` for a synchronous
call.

Arguments mapping described in
[DeleteUserProfileRequestRequestTypeDef](./type_defs.md#deleteuserprofilerequestrequesttypedef).

Keyword-only arguments:

- `IamUserArn`: `str` *(required)*

<a id="deregister_ecs_cluster"></a>

### deregister_ecs_cluster

Deregisters a specified Amazon ECS cluster from a stack.

Type annotations for
`aiobotocore.create_client("opsworks").deregister_ecs_cluster` method.

Boto3 documentation:
[OpsWorks.Client.deregister_ecs_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.deregister_ecs_cluster)

Asynchronous method. Use `await deregister_ecs_cluster(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterEcsClusterRequestRequestTypeDef](./type_defs.md#deregisterecsclusterrequestrequesttypedef).

Keyword-only arguments:

- `EcsClusterArn`: `str` *(required)*

<a id="deregister_elastic_ip"></a>

### deregister_elastic_ip

Deregisters a specified Elastic IP address.

Type annotations for
`aiobotocore.create_client("opsworks").deregister_elastic_ip` method.

Boto3 documentation:
[OpsWorks.Client.deregister_elastic_ip](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.deregister_elastic_ip)

Asynchronous method. Use `await deregister_elastic_ip(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterElasticIpRequestRequestTypeDef](./type_defs.md#deregisterelasticiprequestrequesttypedef).

Keyword-only arguments:

- `ElasticIp`: `str` *(required)*

<a id="deregister_instance"></a>

### deregister_instance

Deregister a registered Amazon EC2 or on-premises instance.

Type annotations for
`aiobotocore.create_client("opsworks").deregister_instance` method.

Boto3 documentation:
[OpsWorks.Client.deregister_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.deregister_instance)

Asynchronous method. Use `await deregister_instance(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterInstanceRequestRequestTypeDef](./type_defs.md#deregisterinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*

<a id="deregister_rds_db_instance"></a>

### deregister_rds_db_instance

Deregisters an Amazon RDS instance.

Type annotations for
`aiobotocore.create_client("opsworks").deregister_rds_db_instance` method.

Boto3 documentation:
[OpsWorks.Client.deregister_rds_db_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.deregister_rds_db_instance)

Asynchronous method. Use `await deregister_rds_db_instance(...)` for a
synchronous call.

Arguments mapping described in
[DeregisterRdsDbInstanceRequestRequestTypeDef](./type_defs.md#deregisterrdsdbinstancerequestrequesttypedef).

Keyword-only arguments:

- `RdsDbInstanceArn`: `str` *(required)*

<a id="deregister_volume"></a>

### deregister_volume

Deregisters an Amazon EBS volume.

Type annotations for `aiobotocore.create_client("opsworks").deregister_volume`
method.

Boto3 documentation:
[OpsWorks.Client.deregister_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.deregister_volume)

Asynchronous method. Use `await deregister_volume(...)` for a synchronous call.

Arguments mapping described in
[DeregisterVolumeRequestRequestTypeDef](./type_defs.md#deregistervolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*

<a id="describe_agent_versions"></a>

### describe_agent_versions

Describes the available AWS OpsWorks Stacks agent versions.

Type annotations for
`aiobotocore.create_client("opsworks").describe_agent_versions` method.

Boto3 documentation:
[OpsWorks.Client.describe_agent_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_agent_versions)

Asynchronous method. Use `await describe_agent_versions(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAgentVersionsRequestRequestTypeDef](./type_defs.md#describeagentversionsrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str`
- `ConfigurationManager`:
  [StackConfigurationManagerTypeDef](./type_defs.md#stackconfigurationmanagertypedef)

Returns a `Coroutine` for
[DescribeAgentVersionsResultTypeDef](./type_defs.md#describeagentversionsresulttypedef).

<a id="describe_apps"></a>

### describe_apps

Requests a description of a specified set of apps.

Type annotations for `aiobotocore.create_client("opsworks").describe_apps`
method.

Boto3 documentation:
[OpsWorks.Client.describe_apps](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_apps)

Asynchronous method. Use `await describe_apps(...)` for a synchronous call.

Arguments mapping described in
[DescribeAppsRequestRequestTypeDef](./type_defs.md#describeappsrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str`
- `AppIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeAppsResultTypeDef](./type_defs.md#describeappsresulttypedef).

<a id="describe_commands"></a>

### describe_commands

Describes the results of specified commands.

Type annotations for `aiobotocore.create_client("opsworks").describe_commands`
method.

Boto3 documentation:
[OpsWorks.Client.describe_commands](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_commands)

Asynchronous method. Use `await describe_commands(...)` for a synchronous call.

Arguments mapping described in
[DescribeCommandsRequestRequestTypeDef](./type_defs.md#describecommandsrequestrequesttypedef).

Keyword-only arguments:

- `DeploymentId`: `str`
- `InstanceId`: `str`
- `CommandIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeCommandsResultTypeDef](./type_defs.md#describecommandsresulttypedef).

<a id="describe_deployments"></a>

### describe_deployments

Requests a description of a specified set of deployments.

Type annotations for
`aiobotocore.create_client("opsworks").describe_deployments` method.

Boto3 documentation:
[OpsWorks.Client.describe_deployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_deployments)

Asynchronous method. Use `await describe_deployments(...)` for a synchronous
call.

Arguments mapping described in
[DescribeDeploymentsRequestRequestTypeDef](./type_defs.md#describedeploymentsrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str`
- `AppId`: `str`
- `DeploymentIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeDeploymentsResultTypeDef](./type_defs.md#describedeploymentsresulttypedef).

<a id="describe_ecs_clusters"></a>

### describe_ecs_clusters

Describes Amazon ECS clusters that are registered with a stack.

Type annotations for
`aiobotocore.create_client("opsworks").describe_ecs_clusters` method.

Boto3 documentation:
[OpsWorks.Client.describe_ecs_clusters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_ecs_clusters)

Asynchronous method. Use `await describe_ecs_clusters(...)` for a synchronous
call.

Arguments mapping described in
[DescribeEcsClustersRequestRequestTypeDef](./type_defs.md#describeecsclustersrequestrequesttypedef).

Keyword-only arguments:

- `EcsClusterArns`: `Sequence`\[`str`\]
- `StackId`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeEcsClustersResultTypeDef](./type_defs.md#describeecsclustersresulttypedef).

<a id="describe_elastic_ips"></a>

### describe_elastic_ips

Describes \[Elastic IP
addresses\](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-
addresses-eip.html)\_ .

Type annotations for
`aiobotocore.create_client("opsworks").describe_elastic_ips` method.

Boto3 documentation:
[OpsWorks.Client.describe_elastic_ips](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_elastic_ips)

Asynchronous method. Use `await describe_elastic_ips(...)` for a synchronous
call.

Arguments mapping described in
[DescribeElasticIpsRequestRequestTypeDef](./type_defs.md#describeelasticipsrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str`
- `StackId`: `str`
- `Ips`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeElasticIpsResultTypeDef](./type_defs.md#describeelasticipsresulttypedef).

<a id="describe_elastic_load_balancers"></a>

### describe_elastic_load_balancers

Describes a stack's Elastic Load Balancing instances.

Type annotations for
`aiobotocore.create_client("opsworks").describe_elastic_load_balancers` method.

Boto3 documentation:
[OpsWorks.Client.describe_elastic_load_balancers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_elastic_load_balancers)

Asynchronous method. Use `await describe_elastic_load_balancers(...)` for a
synchronous call.

Arguments mapping described in
[DescribeElasticLoadBalancersRequestRequestTypeDef](./type_defs.md#describeelasticloadbalancersrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str`
- `LayerIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeElasticLoadBalancersResultTypeDef](./type_defs.md#describeelasticloadbalancersresulttypedef).

<a id="describe_instances"></a>

### describe_instances

Requests a description of a set of instances.

Type annotations for `aiobotocore.create_client("opsworks").describe_instances`
method.

Boto3 documentation:
[OpsWorks.Client.describe_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_instances)

Asynchronous method. Use `await describe_instances(...)` for a synchronous
call.

Arguments mapping described in
[DescribeInstancesRequestRequestTypeDef](./type_defs.md#describeinstancesrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str`
- `LayerId`: `str`
- `InstanceIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeInstancesResultTypeDef](./type_defs.md#describeinstancesresulttypedef).

<a id="describe_layers"></a>

### describe_layers

Requests a description of one or more layers in a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").describe_layers`
method.

Boto3 documentation:
[OpsWorks.Client.describe_layers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_layers)

Asynchronous method. Use `await describe_layers(...)` for a synchronous call.

Arguments mapping described in
[DescribeLayersRequestRequestTypeDef](./type_defs.md#describelayersrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str`
- `LayerIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeLayersResultTypeDef](./type_defs.md#describelayersresulttypedef).

<a id="describe_load_based_auto_scaling"></a>

### describe_load_based_auto_scaling

Describes load-based auto scaling configurations for specified layers.

Type annotations for
`aiobotocore.create_client("opsworks").describe_load_based_auto_scaling`
method.

Boto3 documentation:
[OpsWorks.Client.describe_load_based_auto_scaling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_load_based_auto_scaling)

Asynchronous method. Use `await describe_load_based_auto_scaling(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLoadBasedAutoScalingRequestRequestTypeDef](./type_defs.md#describeloadbasedautoscalingrequestrequesttypedef).

Keyword-only arguments:

- `LayerIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DescribeLoadBasedAutoScalingResultTypeDef](./type_defs.md#describeloadbasedautoscalingresulttypedef).

<a id="describe_my_user_profile"></a>

### describe_my_user_profile

Describes a user's SSH information.

Type annotations for
`aiobotocore.create_client("opsworks").describe_my_user_profile` method.

Boto3 documentation:
[OpsWorks.Client.describe_my_user_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_my_user_profile)

Asynchronous method. Use `await describe_my_user_profile(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeMyUserProfileResultTypeDef](./type_defs.md#describemyuserprofileresulttypedef).

<a id="describe_operating_systems"></a>

### describe_operating_systems

Describes the operating systems that are supported by AWS OpsWorks Stacks.

Type annotations for
`aiobotocore.create_client("opsworks").describe_operating_systems` method.

Boto3 documentation:
[OpsWorks.Client.describe_operating_systems](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_operating_systems)

Asynchronous method. Use `await describe_operating_systems(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeOperatingSystemsResponseTypeDef](./type_defs.md#describeoperatingsystemsresponsetypedef).

<a id="describe_permissions"></a>

### describe_permissions

Describes the permissions for a specified stack.

Type annotations for
`aiobotocore.create_client("opsworks").describe_permissions` method.

Boto3 documentation:
[OpsWorks.Client.describe_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_permissions)

Asynchronous method. Use `await describe_permissions(...)` for a synchronous
call.

Arguments mapping described in
[DescribePermissionsRequestRequestTypeDef](./type_defs.md#describepermissionsrequestrequesttypedef).

Keyword-only arguments:

- `IamUserArn`: `str`
- `StackId`: `str`

Returns a `Coroutine` for
[DescribePermissionsResultTypeDef](./type_defs.md#describepermissionsresulttypedef).

<a id="describe_raid_arrays"></a>

### describe_raid_arrays

Describe an instance's RAID arrays.

Type annotations for
`aiobotocore.create_client("opsworks").describe_raid_arrays` method.

Boto3 documentation:
[OpsWorks.Client.describe_raid_arrays](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_raid_arrays)

Asynchronous method. Use `await describe_raid_arrays(...)` for a synchronous
call.

Arguments mapping described in
[DescribeRaidArraysRequestRequestTypeDef](./type_defs.md#describeraidarraysrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str`
- `StackId`: `str`
- `RaidArrayIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeRaidArraysResultTypeDef](./type_defs.md#describeraidarraysresulttypedef).

<a id="describe_rds_db_instances"></a>

### describe_rds_db_instances

Describes Amazon RDS instances.

Type annotations for
`aiobotocore.create_client("opsworks").describe_rds_db_instances` method.

Boto3 documentation:
[OpsWorks.Client.describe_rds_db_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_rds_db_instances)

Asynchronous method. Use `await describe_rds_db_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeRdsDbInstancesRequestRequestTypeDef](./type_defs.md#describerdsdbinstancesrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `RdsDbInstanceArns`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeRdsDbInstancesResultTypeDef](./type_defs.md#describerdsdbinstancesresulttypedef).

<a id="describe_service_errors"></a>

### describe_service_errors

Describes AWS OpsWorks Stacks service errors.

Type annotations for
`aiobotocore.create_client("opsworks").describe_service_errors` method.

Boto3 documentation:
[OpsWorks.Client.describe_service_errors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_service_errors)

Asynchronous method. Use `await describe_service_errors(...)` for a synchronous
call.

Arguments mapping described in
[DescribeServiceErrorsRequestRequestTypeDef](./type_defs.md#describeserviceerrorsrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str`
- `InstanceId`: `str`
- `ServiceErrorIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeServiceErrorsResultTypeDef](./type_defs.md#describeserviceerrorsresulttypedef).

<a id="describe_stack_provisioning_parameters"></a>

### describe_stack_provisioning_parameters

Requests a description of a stack's provisioning parameters.

Type annotations for
`aiobotocore.create_client("opsworks").describe_stack_provisioning_parameters`
method.

Boto3 documentation:
[OpsWorks.Client.describe_stack_provisioning_parameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_stack_provisioning_parameters)

Asynchronous method. Use `await describe_stack_provisioning_parameters(...)`
for a synchronous call.

Arguments mapping described in
[DescribeStackProvisioningParametersRequestRequestTypeDef](./type_defs.md#describestackprovisioningparametersrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeStackProvisioningParametersResultTypeDef](./type_defs.md#describestackprovisioningparametersresulttypedef).

<a id="describe_stack_summary"></a>

### describe_stack_summary

Describes the number of layers and apps in a specified stack, and the number of
instances in each state, such as `running_setup` or `online` .

Type annotations for
`aiobotocore.create_client("opsworks").describe_stack_summary` method.

Boto3 documentation:
[OpsWorks.Client.describe_stack_summary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_stack_summary)

Asynchronous method. Use `await describe_stack_summary(...)` for a synchronous
call.

Arguments mapping described in
[DescribeStackSummaryRequestRequestTypeDef](./type_defs.md#describestacksummaryrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeStackSummaryResultTypeDef](./type_defs.md#describestacksummaryresulttypedef).

<a id="describe_stacks"></a>

### describe_stacks

Requests a description of one or more stacks.

Type annotations for `aiobotocore.create_client("opsworks").describe_stacks`
method.

Boto3 documentation:
[OpsWorks.Client.describe_stacks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_stacks)

Asynchronous method. Use `await describe_stacks(...)` for a synchronous call.

Arguments mapping described in
[DescribeStacksRequestRequestTypeDef](./type_defs.md#describestacksrequestrequesttypedef).

Keyword-only arguments:

- `StackIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeStacksResultTypeDef](./type_defs.md#describestacksresulttypedef).

<a id="describe_time_based_auto_scaling"></a>

### describe_time_based_auto_scaling

Describes time-based auto scaling configurations for specified instances.

Type annotations for
`aiobotocore.create_client("opsworks").describe_time_based_auto_scaling`
method.

Boto3 documentation:
[OpsWorks.Client.describe_time_based_auto_scaling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_time_based_auto_scaling)

Asynchronous method. Use `await describe_time_based_auto_scaling(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTimeBasedAutoScalingRequestRequestTypeDef](./type_defs.md#describetimebasedautoscalingrequestrequesttypedef).

Keyword-only arguments:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DescribeTimeBasedAutoScalingResultTypeDef](./type_defs.md#describetimebasedautoscalingresulttypedef).

<a id="describe_user_profiles"></a>

### describe_user_profiles

Describe specified users.

Type annotations for
`aiobotocore.create_client("opsworks").describe_user_profiles` method.

Boto3 documentation:
[OpsWorks.Client.describe_user_profiles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_user_profiles)

Asynchronous method. Use `await describe_user_profiles(...)` for a synchronous
call.

Arguments mapping described in
[DescribeUserProfilesRequestRequestTypeDef](./type_defs.md#describeuserprofilesrequestrequesttypedef).

Keyword-only arguments:

- `IamUserArns`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeUserProfilesResultTypeDef](./type_defs.md#describeuserprofilesresulttypedef).

<a id="describe_volumes"></a>

### describe_volumes

Describes an instance's Amazon EBS volumes.

Type annotations for `aiobotocore.create_client("opsworks").describe_volumes`
method.

Boto3 documentation:
[OpsWorks.Client.describe_volumes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_volumes)

Asynchronous method. Use `await describe_volumes(...)` for a synchronous call.

Arguments mapping described in
[DescribeVolumesRequestRequestTypeDef](./type_defs.md#describevolumesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str`
- `StackId`: `str`
- `RaidArrayId`: `str`
- `VolumeIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeVolumesResultTypeDef](./type_defs.md#describevolumesresulttypedef).

<a id="detach_elastic_load_balancer"></a>

### detach_elastic_load_balancer

Detaches a specified Elastic Load Balancing instance from its layer.

Type annotations for
`aiobotocore.create_client("opsworks").detach_elastic_load_balancer` method.

Boto3 documentation:
[OpsWorks.Client.detach_elastic_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.detach_elastic_load_balancer)

Asynchronous method. Use `await detach_elastic_load_balancer(...)` for a
synchronous call.

Arguments mapping described in
[DetachElasticLoadBalancerRequestRequestTypeDef](./type_defs.md#detachelasticloadbalancerrequestrequesttypedef).

Keyword-only arguments:

- `ElasticLoadBalancerName`: `str` *(required)*
- `LayerId`: `str` *(required)*

<a id="disassociate_elastic_ip"></a>

### disassociate_elastic_ip

Disassociates an Elastic IP address from its instance.

Type annotations for
`aiobotocore.create_client("opsworks").disassociate_elastic_ip` method.

Boto3 documentation:
[OpsWorks.Client.disassociate_elastic_ip](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.disassociate_elastic_ip)

Asynchronous method. Use `await disassociate_elastic_ip(...)` for a synchronous
call.

Arguments mapping described in
[DisassociateElasticIpRequestRequestTypeDef](./type_defs.md#disassociateelasticiprequestrequesttypedef).

Keyword-only arguments:

- `ElasticIp`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("opsworks").generate_presigned_url` method.

Boto3 documentation:
[OpsWorks.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_hostname_suggestion"></a>

### get_hostname_suggestion

Gets a generated host name for the specified layer, based on the current host
name theme.

Type annotations for
`aiobotocore.create_client("opsworks").get_hostname_suggestion` method.

Boto3 documentation:
[OpsWorks.Client.get_hostname_suggestion](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.get_hostname_suggestion)

Asynchronous method. Use `await get_hostname_suggestion(...)` for a synchronous
call.

Arguments mapping described in
[GetHostnameSuggestionRequestRequestTypeDef](./type_defs.md#gethostnamesuggestionrequestrequesttypedef).

Keyword-only arguments:

- `LayerId`: `str` *(required)*

Returns a `Coroutine` for
[GetHostnameSuggestionResultTypeDef](./type_defs.md#gethostnamesuggestionresulttypedef).

<a id="grant_access"></a>

### grant_access

.

Type annotations for `aiobotocore.create_client("opsworks").grant_access`
method.

Boto3 documentation:
[OpsWorks.Client.grant_access](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.grant_access)

Asynchronous method. Use `await grant_access(...)` for a synchronous call.

Arguments mapping described in
[GrantAccessRequestRequestTypeDef](./type_defs.md#grantaccessrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `ValidForInMinutes`: `int`

Returns a `Coroutine` for
[GrantAccessResultTypeDef](./type_defs.md#grantaccessresulttypedef).

<a id="list_tags"></a>

### list_tags

Returns a list of tags that are applied to the specified stack or layer.

Type annotations for `aiobotocore.create_client("opsworks").list_tags` method.

Boto3 documentation:
[OpsWorks.Client.list_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.list_tags)

Asynchronous method. Use `await list_tags(...)` for a synchronous call.

Arguments mapping described in
[ListTagsRequestRequestTypeDef](./type_defs.md#listtagsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTagsResultTypeDef](./type_defs.md#listtagsresulttypedef).

<a id="reboot_instance"></a>

### reboot_instance

Reboots a specified instance.

Type annotations for `aiobotocore.create_client("opsworks").reboot_instance`
method.

Boto3 documentation:
[OpsWorks.Client.reboot_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.reboot_instance)

Asynchronous method. Use `await reboot_instance(...)` for a synchronous call.

Arguments mapping described in
[RebootInstanceRequestRequestTypeDef](./type_defs.md#rebootinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*

<a id="register_ecs_cluster"></a>

### register_ecs_cluster

Registers a specified Amazon ECS cluster with a stack.

Type annotations for
`aiobotocore.create_client("opsworks").register_ecs_cluster` method.

Boto3 documentation:
[OpsWorks.Client.register_ecs_cluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.register_ecs_cluster)

Asynchronous method. Use `await register_ecs_cluster(...)` for a synchronous
call.

Arguments mapping described in
[RegisterEcsClusterRequestRequestTypeDef](./type_defs.md#registerecsclusterrequestrequesttypedef).

Keyword-only arguments:

- `EcsClusterArn`: `str` *(required)*
- `StackId`: `str` *(required)*

Returns a `Coroutine` for
[RegisterEcsClusterResultTypeDef](./type_defs.md#registerecsclusterresulttypedef).

<a id="register_elastic_ip"></a>

### register_elastic_ip

Registers an Elastic IP address with a specified stack.

Type annotations for
`aiobotocore.create_client("opsworks").register_elastic_ip` method.

Boto3 documentation:
[OpsWorks.Client.register_elastic_ip](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.register_elastic_ip)

Asynchronous method. Use `await register_elastic_ip(...)` for a synchronous
call.

Arguments mapping described in
[RegisterElasticIpRequestRequestTypeDef](./type_defs.md#registerelasticiprequestrequesttypedef).

Keyword-only arguments:

- `ElasticIp`: `str` *(required)*
- `StackId`: `str` *(required)*

Returns a `Coroutine` for
[RegisterElasticIpResultTypeDef](./type_defs.md#registerelasticipresulttypedef).

<a id="register_instance"></a>

### register_instance

Registers instances that were created outside of AWS OpsWorks Stacks with a
specified stack.

Type annotations for `aiobotocore.create_client("opsworks").register_instance`
method.

Boto3 documentation:
[OpsWorks.Client.register_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.register_instance)

Asynchronous method. Use `await register_instance(...)` for a synchronous call.

Arguments mapping described in
[RegisterInstanceRequestRequestTypeDef](./type_defs.md#registerinstancerequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `Hostname`: `str`
- `PublicIp`: `str`
- `PrivateIp`: `str`
- `RsaPublicKey`: `str`
- `RsaPublicKeyFingerprint`: `str`
- `InstanceIdentity`:
  [InstanceIdentityTypeDef](./type_defs.md#instanceidentitytypedef)

Returns a `Coroutine` for
[RegisterInstanceResultTypeDef](./type_defs.md#registerinstanceresulttypedef).

<a id="register_rds_db_instance"></a>

### register_rds_db_instance

Registers an Amazon RDS instance with a stack.

Type annotations for
`aiobotocore.create_client("opsworks").register_rds_db_instance` method.

Boto3 documentation:
[OpsWorks.Client.register_rds_db_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.register_rds_db_instance)

Asynchronous method. Use `await register_rds_db_instance(...)` for a
synchronous call.

Arguments mapping described in
[RegisterRdsDbInstanceRequestRequestTypeDef](./type_defs.md#registerrdsdbinstancerequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `RdsDbInstanceArn`: `str` *(required)*
- `DbUser`: `str` *(required)*
- `DbPassword`: `str` *(required)*

<a id="register_volume"></a>

### register_volume

Registers an Amazon EBS volume with a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").register_volume`
method.

Boto3 documentation:
[OpsWorks.Client.register_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.register_volume)

Asynchronous method. Use `await register_volume(...)` for a synchronous call.

Arguments mapping described in
[RegisterVolumeRequestRequestTypeDef](./type_defs.md#registervolumerequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `Ec2VolumeId`: `str`

Returns a `Coroutine` for
[RegisterVolumeResultTypeDef](./type_defs.md#registervolumeresulttypedef).

<a id="set_load_based_auto_scaling"></a>

### set_load_based_auto_scaling

Specify the load-based auto scaling configuration for a specified layer.

Type annotations for
`aiobotocore.create_client("opsworks").set_load_based_auto_scaling` method.

Boto3 documentation:
[OpsWorks.Client.set_load_based_auto_scaling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.set_load_based_auto_scaling)

Asynchronous method. Use `await set_load_based_auto_scaling(...)` for a
synchronous call.

Arguments mapping described in
[SetLoadBasedAutoScalingRequestRequestTypeDef](./type_defs.md#setloadbasedautoscalingrequestrequesttypedef).

Keyword-only arguments:

- `LayerId`: `str` *(required)*
- `Enable`: `bool`
- `UpScaling`:
  [AutoScalingThresholdsTypeDef](./type_defs.md#autoscalingthresholdstypedef)
- `DownScaling`:
  [AutoScalingThresholdsTypeDef](./type_defs.md#autoscalingthresholdstypedef)

<a id="set_permission"></a>

### set_permission

Specifies a user's permissions.

Type annotations for `aiobotocore.create_client("opsworks").set_permission`
method.

Boto3 documentation:
[OpsWorks.Client.set_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.set_permission)

Asynchronous method. Use `await set_permission(...)` for a synchronous call.

Arguments mapping described in
[SetPermissionRequestRequestTypeDef](./type_defs.md#setpermissionrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `IamUserArn`: `str` *(required)*
- `AllowSsh`: `bool`
- `AllowSudo`: `bool`
- `Level`: `str`

<a id="set_time_based_auto_scaling"></a>

### set_time_based_auto_scaling

Specify the time-based auto scaling configuration for a specified instance.

Type annotations for
`aiobotocore.create_client("opsworks").set_time_based_auto_scaling` method.

Boto3 documentation:
[OpsWorks.Client.set_time_based_auto_scaling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.set_time_based_auto_scaling)

Asynchronous method. Use `await set_time_based_auto_scaling(...)` for a
synchronous call.

Arguments mapping described in
[SetTimeBasedAutoScalingRequestRequestTypeDef](./type_defs.md#settimebasedautoscalingrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `AutoScalingSchedule`:
  [WeeklyAutoScalingScheduleTypeDef](./type_defs.md#weeklyautoscalingscheduletypedef)

<a id="start_instance"></a>

### start_instance

Starts a specified instance.

Type annotations for `aiobotocore.create_client("opsworks").start_instance`
method.

Boto3 documentation:
[OpsWorks.Client.start_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.start_instance)

Asynchronous method. Use `await start_instance(...)` for a synchronous call.

Arguments mapping described in
[StartInstanceRequestRequestTypeDef](./type_defs.md#startinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*

<a id="start_stack"></a>

### start_stack

Starts a stack's instances.

Type annotations for `aiobotocore.create_client("opsworks").start_stack`
method.

Boto3 documentation:
[OpsWorks.Client.start_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.start_stack)

Asynchronous method. Use `await start_stack(...)` for a synchronous call.

Arguments mapping described in
[StartStackRequestRequestTypeDef](./type_defs.md#startstackrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*

<a id="stop_instance"></a>

### stop_instance

Stops a specified instance.

Type annotations for `aiobotocore.create_client("opsworks").stop_instance`
method.

Boto3 documentation:
[OpsWorks.Client.stop_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.stop_instance)

Asynchronous method. Use `await stop_instance(...)` for a synchronous call.

Arguments mapping described in
[StopInstanceRequestRequestTypeDef](./type_defs.md#stopinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `Force`: `bool`

<a id="stop_stack"></a>

### stop_stack

Stops a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").stop_stack` method.

Boto3 documentation:
[OpsWorks.Client.stop_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.stop_stack)

Asynchronous method. Use `await stop_stack(...)` for a synchronous call.

Arguments mapping described in
[StopStackRequestRequestTypeDef](./type_defs.md#stopstackrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*

<a id="tag_resource"></a>

### tag_resource

Apply cost-allocation tags to a specified stack or layer in AWS OpsWorks
Stacks.

Type annotations for `aiobotocore.create_client("opsworks").tag_resource`
method.

Boto3 documentation:
[OpsWorks.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="unassign_instance"></a>

### unassign_instance

Unassigns a registered instance from all layers that are using the instance.

Type annotations for `aiobotocore.create_client("opsworks").unassign_instance`
method.

Boto3 documentation:
[OpsWorks.Client.unassign_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.unassign_instance)

Asynchronous method. Use `await unassign_instance(...)` for a synchronous call.

Arguments mapping described in
[UnassignInstanceRequestRequestTypeDef](./type_defs.md#unassigninstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*

<a id="unassign_volume"></a>

### unassign_volume

Unassigns an assigned Amazon EBS volume.

Type annotations for `aiobotocore.create_client("opsworks").unassign_volume`
method.

Boto3 documentation:
[OpsWorks.Client.unassign_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.unassign_volume)

Asynchronous method. Use `await unassign_volume(...)` for a synchronous call.

Arguments mapping described in
[UnassignVolumeRequestRequestTypeDef](./type_defs.md#unassignvolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*

<a id="untag_resource"></a>

### untag_resource

Removes tags from a specified stack or layer.

Type annotations for `aiobotocore.create_client("opsworks").untag_resource`
method.

Boto3 documentation:
[OpsWorks.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update_app"></a>

### update_app

Updates a specified app.

Type annotations for `aiobotocore.create_client("opsworks").update_app` method.

Boto3 documentation:
[OpsWorks.Client.update_app](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_app)

Asynchronous method. Use `await update_app(...)` for a synchronous call.

Arguments mapping described in
[UpdateAppRequestRequestTypeDef](./type_defs.md#updateapprequestrequesttypedef).

Keyword-only arguments:

- `AppId`: `str` *(required)*
- `Name`: `str`
- `Description`: `str`
- `DataSources`:
  `Sequence`\[[DataSourceTypeDef](./type_defs.md#datasourcetypedef)\]
- `Type`: [AppTypeType](./literals.md#apptypetype)
- `AppSource`: [SourceTypeDef](./type_defs.md#sourcetypedef)
- `Domains`: `Sequence`\[`str`\]
- `EnableSsl`: `bool`
- `SslConfiguration`:
  [SslConfigurationTypeDef](./type_defs.md#sslconfigurationtypedef)
- `Attributes`:
  `Mapping`\[[AppAttributesKeysType](./literals.md#appattributeskeystype),
  `str`\]
- `Environment`:
  `Sequence`\[[EnvironmentVariableTypeDef](./type_defs.md#environmentvariabletypedef)\]

<a id="update_elastic_ip"></a>

### update_elastic_ip

Updates a registered Elastic IP address's name.

Type annotations for `aiobotocore.create_client("opsworks").update_elastic_ip`
method.

Boto3 documentation:
[OpsWorks.Client.update_elastic_ip](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_elastic_ip)

Asynchronous method. Use `await update_elastic_ip(...)` for a synchronous call.

Arguments mapping described in
[UpdateElasticIpRequestRequestTypeDef](./type_defs.md#updateelasticiprequestrequesttypedef).

Keyword-only arguments:

- `ElasticIp`: `str` *(required)*
- `Name`: `str`

<a id="update_instance"></a>

### update_instance

Updates a specified instance.

Type annotations for `aiobotocore.create_client("opsworks").update_instance`
method.

Boto3 documentation:
[OpsWorks.Client.update_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_instance)

Asynchronous method. Use `await update_instance(...)` for a synchronous call.

Arguments mapping described in
[UpdateInstanceRequestRequestTypeDef](./type_defs.md#updateinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `LayerIds`: `Sequence`\[`str`\]
- `InstanceType`: `str`
- `AutoScalingType`: [AutoScalingTypeType](./literals.md#autoscalingtypetype)
- `Hostname`: `str`
- `Os`: `str`
- `AmiId`: `str`
- `SshKeyName`: `str`
- `Architecture`: [ArchitectureType](./literals.md#architecturetype)
- `InstallUpdatesOnBoot`: `bool`
- `EbsOptimized`: `bool`
- `AgentVersion`: `str`

<a id="update_layer"></a>

### update_layer

Updates a specified layer.

Type annotations for `aiobotocore.create_client("opsworks").update_layer`
method.

Boto3 documentation:
[OpsWorks.Client.update_layer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_layer)

Asynchronous method. Use `await update_layer(...)` for a synchronous call.

Arguments mapping described in
[UpdateLayerRequestRequestTypeDef](./type_defs.md#updatelayerrequestrequesttypedef).

Keyword-only arguments:

- `LayerId`: `str` *(required)*
- `Name`: `str`
- `Shortname`: `str`
- `Attributes`:
  `Mapping`\[[LayerAttributesKeysType](./literals.md#layerattributeskeystype),
  `str`\]
- `CloudWatchLogsConfiguration`:
  [CloudWatchLogsConfigurationTypeDef](./type_defs.md#cloudwatchlogsconfigurationtypedef)
- `CustomInstanceProfileArn`: `str`
- `CustomJson`: `str`
- `CustomSecurityGroupIds`: `Sequence`\[`str`\]
- `Packages`: `Sequence`\[`str`\]
- `VolumeConfigurations`:
  `Sequence`\[[VolumeConfigurationTypeDef](./type_defs.md#volumeconfigurationtypedef)\]
- `EnableAutoHealing`: `bool`
- `AutoAssignElasticIps`: `bool`
- `AutoAssignPublicIps`: `bool`
- `CustomRecipes`: [RecipesTypeDef](./type_defs.md#recipestypedef)
- `InstallUpdatesOnBoot`: `bool`
- `UseEbsOptimizedInstances`: `bool`
- `LifecycleEventConfiguration`:
  [LifecycleEventConfigurationTypeDef](./type_defs.md#lifecycleeventconfigurationtypedef)

<a id="update_my_user_profile"></a>

### update_my_user_profile

Updates a user's SSH public key.

Type annotations for
`aiobotocore.create_client("opsworks").update_my_user_profile` method.

Boto3 documentation:
[OpsWorks.Client.update_my_user_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_my_user_profile)

Asynchronous method. Use `await update_my_user_profile(...)` for a synchronous
call.

Arguments mapping described in
[UpdateMyUserProfileRequestRequestTypeDef](./type_defs.md#updatemyuserprofilerequestrequesttypedef).

Keyword-only arguments:

- `SshPublicKey`: `str`

<a id="update_rds_db_instance"></a>

### update_rds_db_instance

Updates an Amazon RDS instance.

Type annotations for
`aiobotocore.create_client("opsworks").update_rds_db_instance` method.

Boto3 documentation:
[OpsWorks.Client.update_rds_db_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_rds_db_instance)

Asynchronous method. Use `await update_rds_db_instance(...)` for a synchronous
call.

Arguments mapping described in
[UpdateRdsDbInstanceRequestRequestTypeDef](./type_defs.md#updaterdsdbinstancerequestrequesttypedef).

Keyword-only arguments:

- `RdsDbInstanceArn`: `str` *(required)*
- `DbUser`: `str`
- `DbPassword`: `str`

<a id="update_stack"></a>

### update_stack

Updates a specified stack.

Type annotations for `aiobotocore.create_client("opsworks").update_stack`
method.

Boto3 documentation:
[OpsWorks.Client.update_stack](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_stack)

Asynchronous method. Use `await update_stack(...)` for a synchronous call.

Arguments mapping described in
[UpdateStackRequestRequestTypeDef](./type_defs.md#updatestackrequestrequesttypedef).

Keyword-only arguments:

- `StackId`: `str` *(required)*
- `Name`: `str`
- `Attributes`: `Mapping`\[`Literal['Color']` (see
  [StackAttributesKeysType](./literals.md#stackattributeskeystype)), `str`\]
- `ServiceRoleArn`: `str`
- `DefaultInstanceProfileArn`: `str`
- `DefaultOs`: `str`
- `HostnameTheme`: `str`
- `DefaultAvailabilityZone`: `str`
- `DefaultSubnetId`: `str`
- `CustomJson`: `str`
- `ConfigurationManager`:
  [StackConfigurationManagerTypeDef](./type_defs.md#stackconfigurationmanagertypedef)
- `ChefConfiguration`:
  [ChefConfigurationTypeDef](./type_defs.md#chefconfigurationtypedef)
- `UseCustomCookbooks`: `bool`
- `CustomCookbooksSource`: [SourceTypeDef](./type_defs.md#sourcetypedef)
- `DefaultSshKeyName`: `str`
- `DefaultRootDeviceType`:
  [RootDeviceTypeType](./literals.md#rootdevicetypetype)
- `UseOpsworksSecurityGroups`: `bool`
- `AgentVersion`: `str`

<a id="update_user_profile"></a>

### update_user_profile

Updates a specified user profile.

Type annotations for
`aiobotocore.create_client("opsworks").update_user_profile` method.

Boto3 documentation:
[OpsWorks.Client.update_user_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_user_profile)

Asynchronous method. Use `await update_user_profile(...)` for a synchronous
call.

Arguments mapping described in
[UpdateUserProfileRequestRequestTypeDef](./type_defs.md#updateuserprofilerequestrequesttypedef).

Keyword-only arguments:

- `IamUserArn`: `str` *(required)*
- `SshUsername`: `str`
- `SshPublicKey`: `str`
- `AllowSelfManagement`: `bool`

<a id="update_volume"></a>

### update_volume

Updates an Amazon EBS volume's name or mount point.

Type annotations for `aiobotocore.create_client("opsworks").update_volume`
method.

Boto3 documentation:
[OpsWorks.Client.update_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.update_volume)

Asynchronous method. Use `await update_volume(...)` for a synchronous call.

Arguments mapping described in
[UpdateVolumeRequestRequestTypeDef](./type_defs.md#updatevolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `Name`: `str`
- `MountPoint`: `str`

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("opsworks").get_paginator`
method with overloads.

- `client.get_paginator("describe_ecs_clusters")` ->
  [DescribeEcsClustersPaginator](./paginators.md#describeecsclusterspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `aiobotocore.create_client("opsworks").get_waiter` method
with overloads.

- `client.get_waiter("app_exists")` ->
  [AppExistsWaiter](./waiters.md#appexistswaiter)
- `client.get_waiter("deployment_successful")` ->
  [DeploymentSuccessfulWaiter](./waiters.md#deploymentsuccessfulwaiter)
- `client.get_waiter("instance_online")` ->
  [InstanceOnlineWaiter](./waiters.md#instanceonlinewaiter)
- `client.get_waiter("instance_registered")` ->
  [InstanceRegisteredWaiter](./waiters.md#instanceregisteredwaiter)
- `client.get_waiter("instance_stopped")` ->
  [InstanceStoppedWaiter](./waiters.md#instancestoppedwaiter)
- `client.get_waiter("instance_terminated")` ->
  [InstanceTerminatedWaiter](./waiters.md#instanceterminatedwaiter)
