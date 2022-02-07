<a id="greengrassclient-for-aiobotocore-greengrass-module"></a>

# GreengrassClient for aiobotocore Greengrass module

> [Index](..) > [Greengrass](.) > GreengrassClient

Auto-generated documentation for
[Greengrass](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass)
type annotations stubs module
[types-aiobotocore-greengrass](https://pypi.org/project/types-aiobotocore-greengrass/).

- [GreengrassClient for aiobotocore Greengrass module](#greengrassclient-for-aiobotocore-greengrass-module)
  - [GreengrassClient](#greengrassclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_role_to_group](#associate_role_to_group)
    - [associate_service_role_to_account](#associate_service_role_to_account)
    - [can_paginate](#can_paginate)
    - [create_connector_definition](#create_connector_definition)
    - [create_connector_definition_version](#create_connector_definition_version)
    - [create_core_definition](#create_core_definition)
    - [create_core_definition_version](#create_core_definition_version)
    - [create_deployment](#create_deployment)
    - [create_device_definition](#create_device_definition)
    - [create_device_definition_version](#create_device_definition_version)
    - [create_function_definition](#create_function_definition)
    - [create_function_definition_version](#create_function_definition_version)
    - [create_group](#create_group)
    - [create_group_certificate_authority](#create_group_certificate_authority)
    - [create_group_version](#create_group_version)
    - [create_logger_definition](#create_logger_definition)
    - [create_logger_definition_version](#create_logger_definition_version)
    - [create_resource_definition](#create_resource_definition)
    - [create_resource_definition_version](#create_resource_definition_version)
    - [create_software_update_job](#create_software_update_job)
    - [create_subscription_definition](#create_subscription_definition)
    - [create_subscription_definition_version](#create_subscription_definition_version)
    - [delete_connector_definition](#delete_connector_definition)
    - [delete_core_definition](#delete_core_definition)
    - [delete_device_definition](#delete_device_definition)
    - [delete_function_definition](#delete_function_definition)
    - [delete_group](#delete_group)
    - [delete_logger_definition](#delete_logger_definition)
    - [delete_resource_definition](#delete_resource_definition)
    - [delete_subscription_definition](#delete_subscription_definition)
    - [disassociate_role_from_group](#disassociate_role_from_group)
    - [disassociate_service_role_from_account](#disassociate_service_role_from_account)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_associated_role](#get_associated_role)
    - [get_bulk_deployment_status](#get_bulk_deployment_status)
    - [get_connectivity_info](#get_connectivity_info)
    - [get_connector_definition](#get_connector_definition)
    - [get_connector_definition_version](#get_connector_definition_version)
    - [get_core_definition](#get_core_definition)
    - [get_core_definition_version](#get_core_definition_version)
    - [get_deployment_status](#get_deployment_status)
    - [get_device_definition](#get_device_definition)
    - [get_device_definition_version](#get_device_definition_version)
    - [get_function_definition](#get_function_definition)
    - [get_function_definition_version](#get_function_definition_version)
    - [get_group](#get_group)
    - [get_group_certificate_authority](#get_group_certificate_authority)
    - [get_group_certificate_configuration](#get_group_certificate_configuration)
    - [get_group_version](#get_group_version)
    - [get_logger_definition](#get_logger_definition)
    - [get_logger_definition_version](#get_logger_definition_version)
    - [get_resource_definition](#get_resource_definition)
    - [get_resource_definition_version](#get_resource_definition_version)
    - [get_service_role_for_account](#get_service_role_for_account)
    - [get_subscription_definition](#get_subscription_definition)
    - [get_subscription_definition_version](#get_subscription_definition_version)
    - [get_thing_runtime_configuration](#get_thing_runtime_configuration)
    - [list_bulk_deployment_detailed_reports](#list_bulk_deployment_detailed_reports)
    - [list_bulk_deployments](#list_bulk_deployments)
    - [list_connector_definition_versions](#list_connector_definition_versions)
    - [list_connector_definitions](#list_connector_definitions)
    - [list_core_definition_versions](#list_core_definition_versions)
    - [list_core_definitions](#list_core_definitions)
    - [list_deployments](#list_deployments)
    - [list_device_definition_versions](#list_device_definition_versions)
    - [list_device_definitions](#list_device_definitions)
    - [list_function_definition_versions](#list_function_definition_versions)
    - [list_function_definitions](#list_function_definitions)
    - [list_group_certificate_authorities](#list_group_certificate_authorities)
    - [list_group_versions](#list_group_versions)
    - [list_groups](#list_groups)
    - [list_logger_definition_versions](#list_logger_definition_versions)
    - [list_logger_definitions](#list_logger_definitions)
    - [list_resource_definition_versions](#list_resource_definition_versions)
    - [list_resource_definitions](#list_resource_definitions)
    - [list_subscription_definition_versions](#list_subscription_definition_versions)
    - [list_subscription_definitions](#list_subscription_definitions)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [reset_deployments](#reset_deployments)
    - [start_bulk_deployment](#start_bulk_deployment)
    - [stop_bulk_deployment](#stop_bulk_deployment)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_connectivity_info](#update_connectivity_info)
    - [update_connector_definition](#update_connector_definition)
    - [update_core_definition](#update_core_definition)
    - [update_device_definition](#update_device_definition)
    - [update_function_definition](#update_function_definition)
    - [update_group](#update_group)
    - [update_group_certificate_configuration](#update_group_certificate_configuration)
    - [update_logger_definition](#update_logger_definition)
    - [update_resource_definition](#update_resource_definition)
    - [update_subscription_definition](#update_subscription_definition)
    - [update_thing_runtime_configuration](#update_thing_runtime_configuration)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="greengrassclient"></a>

## GreengrassClient

Type annotations for `session.create_client("greengrass")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_greengrass.client import GreengrassClient

session = get_session()
async with session.create_client("greengrass") as client:
    client: GreengrassClient
```

Boto3 documentation:
[Greengrass.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_greengrass.client import Exceptions

def handle_error(exc: Exceptions.BadRequestException) -> None:
    ...
```

Exceptions:

- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.InternalServerErrorException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

GreengrassClient exceptions.

Type annotations for `session.create_client("greengrass").exceptions` method.

Boto3 documentation:
[Greengrass.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate_role_to_group"></a>

### associate_role_to_group

Associates a role with a group.

Type annotations for
`session.create_client("greengrass").associate_role_to_group` method.

Boto3 documentation:
[Greengrass.Client.associate_role_to_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.associate_role_to_group)

Asynchronous method. Use `await associate_role_to_group(...)` for a synchronous
call.

Arguments mapping described in
[AssociateRoleToGroupRequestRequestTypeDef](./type_defs.md#associateroletogrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `RoleArn`: `str` *(required)*

Returns a `Coroutine` for
[AssociateRoleToGroupResponseTypeDef](./type_defs.md#associateroletogroupresponsetypedef).

<a id="associate_service_role_to_account"></a>

### associate_service_role_to_account

Associates a role with your account.

Type annotations for
`session.create_client("greengrass").associate_service_role_to_account` method.

Boto3 documentation:
[Greengrass.Client.associate_service_role_to_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.associate_service_role_to_account)

Asynchronous method. Use `await associate_service_role_to_account(...)` for a
synchronous call.

Arguments mapping described in
[AssociateServiceRoleToAccountRequestRequestTypeDef](./type_defs.md#associateserviceroletoaccountrequestrequesttypedef).

Keyword-only arguments:

- `RoleArn`: `str` *(required)*

Returns a `Coroutine` for
[AssociateServiceRoleToAccountResponseTypeDef](./type_defs.md#associateserviceroletoaccountresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("greengrass").can_paginate` method.

Boto3 documentation:
[Greengrass.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_connector_definition"></a>

### create_connector_definition

Creates a connector definition.

Type annotations for
`session.create_client("greengrass").create_connector_definition` method.

Boto3 documentation:
[Greengrass.Client.create_connector_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_connector_definition)

Asynchronous method. Use `await create_connector_definition(...)` for a
synchronous call.

Arguments mapping described in
[CreateConnectorDefinitionRequestRequestTypeDef](./type_defs.md#createconnectordefinitionrequestrequesttypedef).

Keyword-only arguments:

- `AmznClientToken`: `str`
- `InitialVersion`:
  [ConnectorDefinitionVersionTypeDef](./type_defs.md#connectordefinitionversiontypedef)
- `Name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateConnectorDefinitionResponseTypeDef](./type_defs.md#createconnectordefinitionresponsetypedef).

<a id="create_connector_definition_version"></a>

### create_connector_definition_version

Creates a version of a connector definition which has already been defined.

Type annotations for
`session.create_client("greengrass").create_connector_definition_version`
method.

Boto3 documentation:
[Greengrass.Client.create_connector_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_connector_definition_version)

Asynchronous method. Use `await create_connector_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateConnectorDefinitionVersionRequestRequestTypeDef](./type_defs.md#createconnectordefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectorDefinitionId`: `str` *(required)*
- `AmznClientToken`: `str`
- `Connectors`:
  `Sequence`\[[ConnectorTypeDef](./type_defs.md#connectortypedef)\]

Returns a `Coroutine` for
[CreateConnectorDefinitionVersionResponseTypeDef](./type_defs.md#createconnectordefinitionversionresponsetypedef).

<a id="create_core_definition"></a>

### create_core_definition

Creates a core definition.

Type annotations for
`session.create_client("greengrass").create_core_definition` method.

Boto3 documentation:
[Greengrass.Client.create_core_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_core_definition)

Asynchronous method. Use `await create_core_definition(...)` for a synchronous
call.

Arguments mapping described in
[CreateCoreDefinitionRequestRequestTypeDef](./type_defs.md#createcoredefinitionrequestrequesttypedef).

Keyword-only arguments:

- `AmznClientToken`: `str`
- `InitialVersion`:
  [CoreDefinitionVersionTypeDef](./type_defs.md#coredefinitionversiontypedef)
- `Name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateCoreDefinitionResponseTypeDef](./type_defs.md#createcoredefinitionresponsetypedef).

<a id="create_core_definition_version"></a>

### create_core_definition_version

Creates a version of a core definition that has already been defined.

Type annotations for
`session.create_client("greengrass").create_core_definition_version` method.

Boto3 documentation:
[Greengrass.Client.create_core_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_core_definition_version)

Asynchronous method. Use `await create_core_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateCoreDefinitionVersionRequestRequestTypeDef](./type_defs.md#createcoredefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `CoreDefinitionId`: `str` *(required)*
- `AmznClientToken`: `str`
- `Cores`: `Sequence`\[[CoreTypeDef](./type_defs.md#coretypedef)\]

Returns a `Coroutine` for
[CreateCoreDefinitionVersionResponseTypeDef](./type_defs.md#createcoredefinitionversionresponsetypedef).

<a id="create_deployment"></a>

### create_deployment

Creates a deployment.

Type annotations for `session.create_client("greengrass").create_deployment`
method.

Boto3 documentation:
[Greengrass.Client.create_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_deployment)

Asynchronous method. Use `await create_deployment(...)` for a synchronous call.

Arguments mapping described in
[CreateDeploymentRequestRequestTypeDef](./type_defs.md#createdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `DeploymentType`: [DeploymentTypeType](./literals.md#deploymenttypetype)
  *(required)*
- `GroupId`: `str` *(required)*
- `AmznClientToken`: `str`
- `DeploymentId`: `str`
- `GroupVersionId`: `str`

Returns a `Coroutine` for
[CreateDeploymentResponseTypeDef](./type_defs.md#createdeploymentresponsetypedef).

<a id="create_device_definition"></a>

### create_device_definition

Creates a device definition.

Type annotations for
`session.create_client("greengrass").create_device_definition` method.

Boto3 documentation:
[Greengrass.Client.create_device_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_device_definition)

Asynchronous method. Use `await create_device_definition(...)` for a
synchronous call.

Arguments mapping described in
[CreateDeviceDefinitionRequestRequestTypeDef](./type_defs.md#createdevicedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `AmznClientToken`: `str`
- `InitialVersion`:
  [DeviceDefinitionVersionTypeDef](./type_defs.md#devicedefinitionversiontypedef)
- `Name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateDeviceDefinitionResponseTypeDef](./type_defs.md#createdevicedefinitionresponsetypedef).

<a id="create_device_definition_version"></a>

### create_device_definition_version

Creates a version of a device definition that has already been defined.

Type annotations for
`session.create_client("greengrass").create_device_definition_version` method.

Boto3 documentation:
[Greengrass.Client.create_device_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_device_definition_version)

Asynchronous method. Use `await create_device_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateDeviceDefinitionVersionRequestRequestTypeDef](./type_defs.md#createdevicedefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `DeviceDefinitionId`: `str` *(required)*
- `AmznClientToken`: `str`
- `Devices`: `Sequence`\[[DeviceTypeDef](./type_defs.md#devicetypedef)\]

Returns a `Coroutine` for
[CreateDeviceDefinitionVersionResponseTypeDef](./type_defs.md#createdevicedefinitionversionresponsetypedef).

<a id="create_function_definition"></a>

### create_function_definition

Creates a Lambda function definition which contains a list of Lambda functions
and their configurations to be used in a group.

Type annotations for
`session.create_client("greengrass").create_function_definition` method.

Boto3 documentation:
[Greengrass.Client.create_function_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_function_definition)

Asynchronous method. Use `await create_function_definition(...)` for a
synchronous call.

Arguments mapping described in
[CreateFunctionDefinitionRequestRequestTypeDef](./type_defs.md#createfunctiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `AmznClientToken`: `str`
- `InitialVersion`:
  [FunctionDefinitionVersionTypeDef](./type_defs.md#functiondefinitionversiontypedef)
- `Name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateFunctionDefinitionResponseTypeDef](./type_defs.md#createfunctiondefinitionresponsetypedef).

<a id="create_function_definition_version"></a>

### create_function_definition_version

Creates a version of a Lambda function definition that has already been
defined.

Type annotations for
`session.create_client("greengrass").create_function_definition_version`
method.

Boto3 documentation:
[Greengrass.Client.create_function_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_function_definition_version)

Asynchronous method. Use `await create_function_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateFunctionDefinitionVersionRequestRequestTypeDef](./type_defs.md#createfunctiondefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `FunctionDefinitionId`: `str` *(required)*
- `AmznClientToken`: `str`
- `DefaultConfig`:
  [FunctionDefaultConfigTypeDef](./type_defs.md#functiondefaultconfigtypedef)
- `Functions`: `Sequence`\[[FunctionTypeDef](./type_defs.md#functiontypedef)\]

Returns a `Coroutine` for
[CreateFunctionDefinitionVersionResponseTypeDef](./type_defs.md#createfunctiondefinitionversionresponsetypedef).

<a id="create_group"></a>

### create_group

Creates a group.

Type annotations for `session.create_client("greengrass").create_group` method.

Boto3 documentation:
[Greengrass.Client.create_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_group)

Asynchronous method. Use `await create_group(...)` for a synchronous call.

Arguments mapping described in
[CreateGroupRequestRequestTypeDef](./type_defs.md#creategrouprequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `AmznClientToken`: `str`
- `InitialVersion`: [GroupVersionTypeDef](./type_defs.md#groupversiontypedef)
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateGroupResponseTypeDef](./type_defs.md#creategroupresponsetypedef).

<a id="create_group_certificate_authority"></a>

### create_group_certificate_authority

Creates a CA for the group.

Type annotations for
`session.create_client("greengrass").create_group_certificate_authority`
method.

Boto3 documentation:
[Greengrass.Client.create_group_certificate_authority](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_group_certificate_authority)

Asynchronous method. Use `await create_group_certificate_authority(...)` for a
synchronous call.

Arguments mapping described in
[CreateGroupCertificateAuthorityRequestRequestTypeDef](./type_defs.md#creategroupcertificateauthorityrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `AmznClientToken`: `str`

Returns a `Coroutine` for
[CreateGroupCertificateAuthorityResponseTypeDef](./type_defs.md#creategroupcertificateauthorityresponsetypedef).

<a id="create_group_version"></a>

### create_group_version

Creates a version of a group which has already been defined.

Type annotations for `session.create_client("greengrass").create_group_version`
method.

Boto3 documentation:
[Greengrass.Client.create_group_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_group_version)

Asynchronous method. Use `await create_group_version(...)` for a synchronous
call.

Arguments mapping described in
[CreateGroupVersionRequestRequestTypeDef](./type_defs.md#creategroupversionrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `AmznClientToken`: `str`
- `ConnectorDefinitionVersionArn`: `str`
- `CoreDefinitionVersionArn`: `str`
- `DeviceDefinitionVersionArn`: `str`
- `FunctionDefinitionVersionArn`: `str`
- `LoggerDefinitionVersionArn`: `str`
- `ResourceDefinitionVersionArn`: `str`
- `SubscriptionDefinitionVersionArn`: `str`

Returns a `Coroutine` for
[CreateGroupVersionResponseTypeDef](./type_defs.md#creategroupversionresponsetypedef).

<a id="create_logger_definition"></a>

### create_logger_definition

Creates a logger definition.

Type annotations for
`session.create_client("greengrass").create_logger_definition` method.

Boto3 documentation:
[Greengrass.Client.create_logger_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_logger_definition)

Asynchronous method. Use `await create_logger_definition(...)` for a
synchronous call.

Arguments mapping described in
[CreateLoggerDefinitionRequestRequestTypeDef](./type_defs.md#createloggerdefinitionrequestrequesttypedef).

Keyword-only arguments:

- `AmznClientToken`: `str`
- `InitialVersion`:
  [LoggerDefinitionVersionTypeDef](./type_defs.md#loggerdefinitionversiontypedef)
- `Name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateLoggerDefinitionResponseTypeDef](./type_defs.md#createloggerdefinitionresponsetypedef).

<a id="create_logger_definition_version"></a>

### create_logger_definition_version

Creates a version of a logger definition that has already been defined.

Type annotations for
`session.create_client("greengrass").create_logger_definition_version` method.

Boto3 documentation:
[Greengrass.Client.create_logger_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_logger_definition_version)

Asynchronous method. Use `await create_logger_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateLoggerDefinitionVersionRequestRequestTypeDef](./type_defs.md#createloggerdefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `LoggerDefinitionId`: `str` *(required)*
- `AmznClientToken`: `str`
- `Loggers`: `Sequence`\[[LoggerTypeDef](./type_defs.md#loggertypedef)\]

Returns a `Coroutine` for
[CreateLoggerDefinitionVersionResponseTypeDef](./type_defs.md#createloggerdefinitionversionresponsetypedef).

<a id="create_resource_definition"></a>

### create_resource_definition

Creates a resource definition which contains a list of resources to be used in
a group.

Type annotations for
`session.create_client("greengrass").create_resource_definition` method.

Boto3 documentation:
[Greengrass.Client.create_resource_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_resource_definition)

Asynchronous method. Use `await create_resource_definition(...)` for a
synchronous call.

Arguments mapping described in
[CreateResourceDefinitionRequestRequestTypeDef](./type_defs.md#createresourcedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `AmznClientToken`: `str`
- `InitialVersion`:
  [ResourceDefinitionVersionTypeDef](./type_defs.md#resourcedefinitionversiontypedef)
- `Name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateResourceDefinitionResponseTypeDef](./type_defs.md#createresourcedefinitionresponsetypedef).

<a id="create_resource_definition_version"></a>

### create_resource_definition_version

Creates a version of a resource definition that has already been defined.

Type annotations for
`session.create_client("greengrass").create_resource_definition_version`
method.

Boto3 documentation:
[Greengrass.Client.create_resource_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_resource_definition_version)

Asynchronous method. Use `await create_resource_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateResourceDefinitionVersionRequestRequestTypeDef](./type_defs.md#createresourcedefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `ResourceDefinitionId`: `str` *(required)*
- `AmznClientToken`: `str`
- `Resources`: `Sequence`\[[ResourceTypeDef](./type_defs.md#resourcetypedef)\]

Returns a `Coroutine` for
[CreateResourceDefinitionVersionResponseTypeDef](./type_defs.md#createresourcedefinitionversionresponsetypedef).

<a id="create_software_update_job"></a>

### create_software_update_job

Creates a software update for a core or group of cores (specified as an IoT
thing group.) Use this to update the OTA Agent as well as the Greengrass core
software.

Type annotations for
`session.create_client("greengrass").create_software_update_job` method.

Boto3 documentation:
[Greengrass.Client.create_software_update_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_software_update_job)

Asynchronous method. Use `await create_software_update_job(...)` for a
synchronous call.

Arguments mapping described in
[CreateSoftwareUpdateJobRequestRequestTypeDef](./type_defs.md#createsoftwareupdatejobrequestrequesttypedef).

Keyword-only arguments:

- `S3UrlSignerRole`: `str` *(required)*
- `SoftwareToUpdate`:
  [SoftwareToUpdateType](./literals.md#softwaretoupdatetype) *(required)*
- `UpdateTargets`: `Sequence`\[`str`\] *(required)*
- `UpdateTargetsArchitecture`:
  [UpdateTargetsArchitectureType](./literals.md#updatetargetsarchitecturetype)
  *(required)*
- `UpdateTargetsOperatingSystem`:
  [UpdateTargetsOperatingSystemType](./literals.md#updatetargetsoperatingsystemtype)
  *(required)*
- `AmznClientToken`: `str`
- `UpdateAgentLogLevel`:
  [UpdateAgentLogLevelType](./literals.md#updateagentlogleveltype)

Returns a `Coroutine` for
[CreateSoftwareUpdateJobResponseTypeDef](./type_defs.md#createsoftwareupdatejobresponsetypedef).

<a id="create_subscription_definition"></a>

### create_subscription_definition

Creates a subscription definition.

Type annotations for
`session.create_client("greengrass").create_subscription_definition` method.

Boto3 documentation:
[Greengrass.Client.create_subscription_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_subscription_definition)

Asynchronous method. Use `await create_subscription_definition(...)` for a
synchronous call.

Arguments mapping described in
[CreateSubscriptionDefinitionRequestRequestTypeDef](./type_defs.md#createsubscriptiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `AmznClientToken`: `str`
- `InitialVersion`:
  [SubscriptionDefinitionVersionTypeDef](./type_defs.md#subscriptiondefinitionversiontypedef)
- `Name`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateSubscriptionDefinitionResponseTypeDef](./type_defs.md#createsubscriptiondefinitionresponsetypedef).

<a id="create_subscription_definition_version"></a>

### create_subscription_definition_version

Creates a version of a subscription definition which has already been defined.

Type annotations for
`session.create_client("greengrass").create_subscription_definition_version`
method.

Boto3 documentation:
[Greengrass.Client.create_subscription_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.create_subscription_definition_version)

Asynchronous method. Use `await create_subscription_definition_version(...)`
for a synchronous call.

Arguments mapping described in
[CreateSubscriptionDefinitionVersionRequestRequestTypeDef](./type_defs.md#createsubscriptiondefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `SubscriptionDefinitionId`: `str` *(required)*
- `AmznClientToken`: `str`
- `Subscriptions`:
  `Sequence`\[[SubscriptionTypeDef](./type_defs.md#subscriptiontypedef)\]

Returns a `Coroutine` for
[CreateSubscriptionDefinitionVersionResponseTypeDef](./type_defs.md#createsubscriptiondefinitionversionresponsetypedef).

<a id="delete_connector_definition"></a>

### delete_connector_definition

Deletes a connector definition.

Type annotations for
`session.create_client("greengrass").delete_connector_definition` method.

Boto3 documentation:
[Greengrass.Client.delete_connector_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_connector_definition)

Asynchronous method. Use `await delete_connector_definition(...)` for a
synchronous call.

Arguments mapping described in
[DeleteConnectorDefinitionRequestRequestTypeDef](./type_defs.md#deleteconnectordefinitionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectorDefinitionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_core_definition"></a>

### delete_core_definition

Deletes a core definition.

Type annotations for
`session.create_client("greengrass").delete_core_definition` method.

Boto3 documentation:
[Greengrass.Client.delete_core_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_core_definition)

Asynchronous method. Use `await delete_core_definition(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCoreDefinitionRequestRequestTypeDef](./type_defs.md#deletecoredefinitionrequestrequesttypedef).

Keyword-only arguments:

- `CoreDefinitionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_device_definition"></a>

### delete_device_definition

Deletes a device definition.

Type annotations for
`session.create_client("greengrass").delete_device_definition` method.

Boto3 documentation:
[Greengrass.Client.delete_device_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_device_definition)

Asynchronous method. Use `await delete_device_definition(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDeviceDefinitionRequestRequestTypeDef](./type_defs.md#deletedevicedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `DeviceDefinitionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_function_definition"></a>

### delete_function_definition

Deletes a Lambda function definition.

Type annotations for
`session.create_client("greengrass").delete_function_definition` method.

Boto3 documentation:
[Greengrass.Client.delete_function_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_function_definition)

Asynchronous method. Use `await delete_function_definition(...)` for a
synchronous call.

Arguments mapping described in
[DeleteFunctionDefinitionRequestRequestTypeDef](./type_defs.md#deletefunctiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `FunctionDefinitionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_group"></a>

### delete_group

Deletes a group.

Type annotations for `session.create_client("greengrass").delete_group` method.

Boto3 documentation:
[Greengrass.Client.delete_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_group)

Asynchronous method. Use `await delete_group(...)` for a synchronous call.

Arguments mapping described in
[DeleteGroupRequestRequestTypeDef](./type_defs.md#deletegrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_logger_definition"></a>

### delete_logger_definition

Deletes a logger definition.

Type annotations for
`session.create_client("greengrass").delete_logger_definition` method.

Boto3 documentation:
[Greengrass.Client.delete_logger_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_logger_definition)

Asynchronous method. Use `await delete_logger_definition(...)` for a
synchronous call.

Arguments mapping described in
[DeleteLoggerDefinitionRequestRequestTypeDef](./type_defs.md#deleteloggerdefinitionrequestrequesttypedef).

Keyword-only arguments:

- `LoggerDefinitionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_resource_definition"></a>

### delete_resource_definition

Deletes a resource definition.

Type annotations for
`session.create_client("greengrass").delete_resource_definition` method.

Boto3 documentation:
[Greengrass.Client.delete_resource_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_resource_definition)

Asynchronous method. Use `await delete_resource_definition(...)` for a
synchronous call.

Arguments mapping described in
[DeleteResourceDefinitionRequestRequestTypeDef](./type_defs.md#deleteresourcedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `ResourceDefinitionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_subscription_definition"></a>

### delete_subscription_definition

Deletes a subscription definition.

Type annotations for
`session.create_client("greengrass").delete_subscription_definition` method.

Boto3 documentation:
[Greengrass.Client.delete_subscription_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.delete_subscription_definition)

Asynchronous method. Use `await delete_subscription_definition(...)` for a
synchronous call.

Arguments mapping described in
[DeleteSubscriptionDefinitionRequestRequestTypeDef](./type_defs.md#deletesubscriptiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `SubscriptionDefinitionId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disassociate_role_from_group"></a>

### disassociate_role_from_group

Disassociates the role from a group.

Type annotations for
`session.create_client("greengrass").disassociate_role_from_group` method.

Boto3 documentation:
[Greengrass.Client.disassociate_role_from_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.disassociate_role_from_group)

Asynchronous method. Use `await disassociate_role_from_group(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateRoleFromGroupRequestRequestTypeDef](./type_defs.md#disassociaterolefromgrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateRoleFromGroupResponseTypeDef](./type_defs.md#disassociaterolefromgroupresponsetypedef).

<a id="disassociate_service_role_from_account"></a>

### disassociate_service_role_from_account

Disassociates the service role from your account.

Type annotations for
`session.create_client("greengrass").disassociate_service_role_from_account`
method.

Boto3 documentation:
[Greengrass.Client.disassociate_service_role_from_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.disassociate_service_role_from_account)

Asynchronous method. Use `await disassociate_service_role_from_account(...)`
for a synchronous call.

Returns a `Coroutine` for
[DisassociateServiceRoleFromAccountResponseTypeDef](./type_defs.md#disassociateservicerolefromaccountresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("greengrass").generate_presigned_url` method.

Boto3 documentation:
[Greengrass.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_associated_role"></a>

### get_associated_role

Retrieves the role associated with a particular group.

Type annotations for `session.create_client("greengrass").get_associated_role`
method.

Boto3 documentation:
[Greengrass.Client.get_associated_role](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_associated_role)

Asynchronous method. Use `await get_associated_role(...)` for a synchronous
call.

Arguments mapping described in
[GetAssociatedRoleRequestRequestTypeDef](./type_defs.md#getassociatedrolerequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[GetAssociatedRoleResponseTypeDef](./type_defs.md#getassociatedroleresponsetypedef).

<a id="get_bulk_deployment_status"></a>

### get_bulk_deployment_status

Returns the status of a bulk deployment.

Type annotations for
`session.create_client("greengrass").get_bulk_deployment_status` method.

Boto3 documentation:
[Greengrass.Client.get_bulk_deployment_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_bulk_deployment_status)

Asynchronous method. Use `await get_bulk_deployment_status(...)` for a
synchronous call.

Arguments mapping described in
[GetBulkDeploymentStatusRequestRequestTypeDef](./type_defs.md#getbulkdeploymentstatusrequestrequesttypedef).

Keyword-only arguments:

- `BulkDeploymentId`: `str` *(required)*

Returns a `Coroutine` for
[GetBulkDeploymentStatusResponseTypeDef](./type_defs.md#getbulkdeploymentstatusresponsetypedef).

<a id="get_connectivity_info"></a>

### get_connectivity_info

Retrieves the connectivity information for a core.

Type annotations for
`session.create_client("greengrass").get_connectivity_info` method.

Boto3 documentation:
[Greengrass.Client.get_connectivity_info](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_connectivity_info)

Asynchronous method. Use `await get_connectivity_info(...)` for a synchronous
call.

Arguments mapping described in
[GetConnectivityInfoRequestRequestTypeDef](./type_defs.md#getconnectivityinforequestrequesttypedef).

Keyword-only arguments:

- `ThingName`: `str` *(required)*

Returns a `Coroutine` for
[GetConnectivityInfoResponseTypeDef](./type_defs.md#getconnectivityinforesponsetypedef).

<a id="get_connector_definition"></a>

### get_connector_definition

Retrieves information about a connector definition.

Type annotations for
`session.create_client("greengrass").get_connector_definition` method.

Boto3 documentation:
[Greengrass.Client.get_connector_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_connector_definition)

Asynchronous method. Use `await get_connector_definition(...)` for a
synchronous call.

Arguments mapping described in
[GetConnectorDefinitionRequestRequestTypeDef](./type_defs.md#getconnectordefinitionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectorDefinitionId`: `str` *(required)*

Returns a `Coroutine` for
[GetConnectorDefinitionResponseTypeDef](./type_defs.md#getconnectordefinitionresponsetypedef).

<a id="get_connector_definition_version"></a>

### get_connector_definition_version

Retrieves information about a connector definition version, including the
connectors that the version contains.

Type annotations for
`session.create_client("greengrass").get_connector_definition_version` method.

Boto3 documentation:
[Greengrass.Client.get_connector_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_connector_definition_version)

Asynchronous method. Use `await get_connector_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[GetConnectorDefinitionVersionRequestRequestTypeDef](./type_defs.md#getconnectordefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectorDefinitionId`: `str` *(required)*
- `ConnectorDefinitionVersionId`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[GetConnectorDefinitionVersionResponseTypeDef](./type_defs.md#getconnectordefinitionversionresponsetypedef).

<a id="get_core_definition"></a>

### get_core_definition

Retrieves information about a core definition version.

Type annotations for `session.create_client("greengrass").get_core_definition`
method.

Boto3 documentation:
[Greengrass.Client.get_core_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_core_definition)

Asynchronous method. Use `await get_core_definition(...)` for a synchronous
call.

Arguments mapping described in
[GetCoreDefinitionRequestRequestTypeDef](./type_defs.md#getcoredefinitionrequestrequesttypedef).

Keyword-only arguments:

- `CoreDefinitionId`: `str` *(required)*

Returns a `Coroutine` for
[GetCoreDefinitionResponseTypeDef](./type_defs.md#getcoredefinitionresponsetypedef).

<a id="get_core_definition_version"></a>

### get_core_definition_version

Retrieves information about a core definition version.

Type annotations for
`session.create_client("greengrass").get_core_definition_version` method.

Boto3 documentation:
[Greengrass.Client.get_core_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_core_definition_version)

Asynchronous method. Use `await get_core_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[GetCoreDefinitionVersionRequestRequestTypeDef](./type_defs.md#getcoredefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `CoreDefinitionId`: `str` *(required)*
- `CoreDefinitionVersionId`: `str` *(required)*

Returns a `Coroutine` for
[GetCoreDefinitionVersionResponseTypeDef](./type_defs.md#getcoredefinitionversionresponsetypedef).

<a id="get_deployment_status"></a>

### get_deployment_status

Returns the status of a deployment.

Type annotations for
`session.create_client("greengrass").get_deployment_status` method.

Boto3 documentation:
[Greengrass.Client.get_deployment_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_deployment_status)

Asynchronous method. Use `await get_deployment_status(...)` for a synchronous
call.

Arguments mapping described in
[GetDeploymentStatusRequestRequestTypeDef](./type_defs.md#getdeploymentstatusrequestrequesttypedef).

Keyword-only arguments:

- `DeploymentId`: `str` *(required)*
- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[GetDeploymentStatusResponseTypeDef](./type_defs.md#getdeploymentstatusresponsetypedef).

<a id="get_device_definition"></a>

### get_device_definition

Retrieves information about a device definition.

Type annotations for
`session.create_client("greengrass").get_device_definition` method.

Boto3 documentation:
[Greengrass.Client.get_device_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_device_definition)

Asynchronous method. Use `await get_device_definition(...)` for a synchronous
call.

Arguments mapping described in
[GetDeviceDefinitionRequestRequestTypeDef](./type_defs.md#getdevicedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `DeviceDefinitionId`: `str` *(required)*

Returns a `Coroutine` for
[GetDeviceDefinitionResponseTypeDef](./type_defs.md#getdevicedefinitionresponsetypedef).

<a id="get_device_definition_version"></a>

### get_device_definition_version

Retrieves information about a device definition version.

Type annotations for
`session.create_client("greengrass").get_device_definition_version` method.

Boto3 documentation:
[Greengrass.Client.get_device_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_device_definition_version)

Asynchronous method. Use `await get_device_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[GetDeviceDefinitionVersionRequestRequestTypeDef](./type_defs.md#getdevicedefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `DeviceDefinitionId`: `str` *(required)*
- `DeviceDefinitionVersionId`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[GetDeviceDefinitionVersionResponseTypeDef](./type_defs.md#getdevicedefinitionversionresponsetypedef).

<a id="get_function_definition"></a>

### get_function_definition

Retrieves information about a Lambda function definition, including its
creation time and latest version.

Type annotations for
`session.create_client("greengrass").get_function_definition` method.

Boto3 documentation:
[Greengrass.Client.get_function_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_function_definition)

Asynchronous method. Use `await get_function_definition(...)` for a synchronous
call.

Arguments mapping described in
[GetFunctionDefinitionRequestRequestTypeDef](./type_defs.md#getfunctiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `FunctionDefinitionId`: `str` *(required)*

Returns a `Coroutine` for
[GetFunctionDefinitionResponseTypeDef](./type_defs.md#getfunctiondefinitionresponsetypedef).

<a id="get_function_definition_version"></a>

### get_function_definition_version

Retrieves information about a Lambda function definition version, including
which Lambda functions are included in the version and their configurations.

Type annotations for
`session.create_client("greengrass").get_function_definition_version` method.

Boto3 documentation:
[Greengrass.Client.get_function_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_function_definition_version)

Asynchronous method. Use `await get_function_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[GetFunctionDefinitionVersionRequestRequestTypeDef](./type_defs.md#getfunctiondefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `FunctionDefinitionId`: `str` *(required)*
- `FunctionDefinitionVersionId`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[GetFunctionDefinitionVersionResponseTypeDef](./type_defs.md#getfunctiondefinitionversionresponsetypedef).

<a id="get_group"></a>

### get_group

Retrieves information about a group.

Type annotations for `session.create_client("greengrass").get_group` method.

Boto3 documentation:
[Greengrass.Client.get_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_group)

Asynchronous method. Use `await get_group(...)` for a synchronous call.

Arguments mapping described in
[GetGroupRequestRequestTypeDef](./type_defs.md#getgrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[GetGroupResponseTypeDef](./type_defs.md#getgroupresponsetypedef).

<a id="get_group_certificate_authority"></a>

### get_group_certificate_authority

Retreives the CA associated with a group.

Type annotations for
`session.create_client("greengrass").get_group_certificate_authority` method.

Boto3 documentation:
[Greengrass.Client.get_group_certificate_authority](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_group_certificate_authority)

Asynchronous method. Use `await get_group_certificate_authority(...)` for a
synchronous call.

Arguments mapping described in
[GetGroupCertificateAuthorityRequestRequestTypeDef](./type_defs.md#getgroupcertificateauthorityrequestrequesttypedef).

Keyword-only arguments:

- `CertificateAuthorityId`: `str` *(required)*
- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[GetGroupCertificateAuthorityResponseTypeDef](./type_defs.md#getgroupcertificateauthorityresponsetypedef).

<a id="get_group_certificate_configuration"></a>

### get_group_certificate_configuration

Retrieves the current configuration for the CA used by the group.

Type annotations for
`session.create_client("greengrass").get_group_certificate_configuration`
method.

Boto3 documentation:
[Greengrass.Client.get_group_certificate_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_group_certificate_configuration)

Asynchronous method. Use `await get_group_certificate_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetGroupCertificateConfigurationRequestRequestTypeDef](./type_defs.md#getgroupcertificateconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[GetGroupCertificateConfigurationResponseTypeDef](./type_defs.md#getgroupcertificateconfigurationresponsetypedef).

<a id="get_group_version"></a>

### get_group_version

Retrieves information about a group version.

Type annotations for `session.create_client("greengrass").get_group_version`
method.

Boto3 documentation:
[Greengrass.Client.get_group_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_group_version)

Asynchronous method. Use `await get_group_version(...)` for a synchronous call.

Arguments mapping described in
[GetGroupVersionRequestRequestTypeDef](./type_defs.md#getgroupversionrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `GroupVersionId`: `str` *(required)*

Returns a `Coroutine` for
[GetGroupVersionResponseTypeDef](./type_defs.md#getgroupversionresponsetypedef).

<a id="get_logger_definition"></a>

### get_logger_definition

Retrieves information about a logger definition.

Type annotations for
`session.create_client("greengrass").get_logger_definition` method.

Boto3 documentation:
[Greengrass.Client.get_logger_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_logger_definition)

Asynchronous method. Use `await get_logger_definition(...)` for a synchronous
call.

Arguments mapping described in
[GetLoggerDefinitionRequestRequestTypeDef](./type_defs.md#getloggerdefinitionrequestrequesttypedef).

Keyword-only arguments:

- `LoggerDefinitionId`: `str` *(required)*

Returns a `Coroutine` for
[GetLoggerDefinitionResponseTypeDef](./type_defs.md#getloggerdefinitionresponsetypedef).

<a id="get_logger_definition_version"></a>

### get_logger_definition_version

Retrieves information about a logger definition version.

Type annotations for
`session.create_client("greengrass").get_logger_definition_version` method.

Boto3 documentation:
[Greengrass.Client.get_logger_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_logger_definition_version)

Asynchronous method. Use `await get_logger_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[GetLoggerDefinitionVersionRequestRequestTypeDef](./type_defs.md#getloggerdefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `LoggerDefinitionId`: `str` *(required)*
- `LoggerDefinitionVersionId`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[GetLoggerDefinitionVersionResponseTypeDef](./type_defs.md#getloggerdefinitionversionresponsetypedef).

<a id="get_resource_definition"></a>

### get_resource_definition

Retrieves information about a resource definition, including its creation time
and latest version.

Type annotations for
`session.create_client("greengrass").get_resource_definition` method.

Boto3 documentation:
[Greengrass.Client.get_resource_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_resource_definition)

Asynchronous method. Use `await get_resource_definition(...)` for a synchronous
call.

Arguments mapping described in
[GetResourceDefinitionRequestRequestTypeDef](./type_defs.md#getresourcedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `ResourceDefinitionId`: `str` *(required)*

Returns a `Coroutine` for
[GetResourceDefinitionResponseTypeDef](./type_defs.md#getresourcedefinitionresponsetypedef).

<a id="get_resource_definition_version"></a>

### get_resource_definition_version

Retrieves information about a resource definition version, including which
resources are included in the version.

Type annotations for
`session.create_client("greengrass").get_resource_definition_version` method.

Boto3 documentation:
[Greengrass.Client.get_resource_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_resource_definition_version)

Asynchronous method. Use `await get_resource_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[GetResourceDefinitionVersionRequestRequestTypeDef](./type_defs.md#getresourcedefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `ResourceDefinitionId`: `str` *(required)*
- `ResourceDefinitionVersionId`: `str` *(required)*

Returns a `Coroutine` for
[GetResourceDefinitionVersionResponseTypeDef](./type_defs.md#getresourcedefinitionversionresponsetypedef).

<a id="get_service_role_for_account"></a>

### get_service_role_for_account

Retrieves the service role that is attached to your account.

Type annotations for
`session.create_client("greengrass").get_service_role_for_account` method.

Boto3 documentation:
[Greengrass.Client.get_service_role_for_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_service_role_for_account)

Asynchronous method. Use `await get_service_role_for_account(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetServiceRoleForAccountResponseTypeDef](./type_defs.md#getserviceroleforaccountresponsetypedef).

<a id="get_subscription_definition"></a>

### get_subscription_definition

Retrieves information about a subscription definition.

Type annotations for
`session.create_client("greengrass").get_subscription_definition` method.

Boto3 documentation:
[Greengrass.Client.get_subscription_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_subscription_definition)

Asynchronous method. Use `await get_subscription_definition(...)` for a
synchronous call.

Arguments mapping described in
[GetSubscriptionDefinitionRequestRequestTypeDef](./type_defs.md#getsubscriptiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `SubscriptionDefinitionId`: `str` *(required)*

Returns a `Coroutine` for
[GetSubscriptionDefinitionResponseTypeDef](./type_defs.md#getsubscriptiondefinitionresponsetypedef).

<a id="get_subscription_definition_version"></a>

### get_subscription_definition_version

Retrieves information about a subscription definition version.

Type annotations for
`session.create_client("greengrass").get_subscription_definition_version`
method.

Boto3 documentation:
[Greengrass.Client.get_subscription_definition_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_subscription_definition_version)

Asynchronous method. Use `await get_subscription_definition_version(...)` for a
synchronous call.

Arguments mapping described in
[GetSubscriptionDefinitionVersionRequestRequestTypeDef](./type_defs.md#getsubscriptiondefinitionversionrequestrequesttypedef).

Keyword-only arguments:

- `SubscriptionDefinitionId`: `str` *(required)*
- `SubscriptionDefinitionVersionId`: `str` *(required)*
- `NextToken`: `str`

Returns a `Coroutine` for
[GetSubscriptionDefinitionVersionResponseTypeDef](./type_defs.md#getsubscriptiondefinitionversionresponsetypedef).

<a id="get_thing_runtime_configuration"></a>

### get_thing_runtime_configuration

Get the runtime configuration of a thing.

Type annotations for
`session.create_client("greengrass").get_thing_runtime_configuration` method.

Boto3 documentation:
[Greengrass.Client.get_thing_runtime_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.get_thing_runtime_configuration)

Asynchronous method. Use `await get_thing_runtime_configuration(...)` for a
synchronous call.

Arguments mapping described in
[GetThingRuntimeConfigurationRequestRequestTypeDef](./type_defs.md#getthingruntimeconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ThingName`: `str` *(required)*

Returns a `Coroutine` for
[GetThingRuntimeConfigurationResponseTypeDef](./type_defs.md#getthingruntimeconfigurationresponsetypedef).

<a id="list_bulk_deployment_detailed_reports"></a>

### list_bulk_deployment_detailed_reports

Gets a paginated list of the deployments that have been started in a bulk
deployment operation, and their current deployment status.

Type annotations for
`session.create_client("greengrass").list_bulk_deployment_detailed_reports`
method.

Boto3 documentation:
[Greengrass.Client.list_bulk_deployment_detailed_reports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_bulk_deployment_detailed_reports)

Asynchronous method. Use `await list_bulk_deployment_detailed_reports(...)` for
a synchronous call.

Arguments mapping described in
[ListBulkDeploymentDetailedReportsRequestRequestTypeDef](./type_defs.md#listbulkdeploymentdetailedreportsrequestrequesttypedef).

Keyword-only arguments:

- `BulkDeploymentId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListBulkDeploymentDetailedReportsResponseTypeDef](./type_defs.md#listbulkdeploymentdetailedreportsresponsetypedef).

<a id="list_bulk_deployments"></a>

### list_bulk_deployments

Returns a list of bulk deployments.

Type annotations for
`session.create_client("greengrass").list_bulk_deployments` method.

Boto3 documentation:
[Greengrass.Client.list_bulk_deployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_bulk_deployments)

Asynchronous method. Use `await list_bulk_deployments(...)` for a synchronous
call.

Arguments mapping described in
[ListBulkDeploymentsRequestRequestTypeDef](./type_defs.md#listbulkdeploymentsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListBulkDeploymentsResponseTypeDef](./type_defs.md#listbulkdeploymentsresponsetypedef).

<a id="list_connector_definition_versions"></a>

### list_connector_definition_versions

Lists the versions of a connector definition, which are containers for
connectors.

Type annotations for
`session.create_client("greengrass").list_connector_definition_versions`
method.

Boto3 documentation:
[Greengrass.Client.list_connector_definition_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_connector_definition_versions)

Asynchronous method. Use `await list_connector_definition_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListConnectorDefinitionVersionsRequestRequestTypeDef](./type_defs.md#listconnectordefinitionversionsrequestrequesttypedef).

Keyword-only arguments:

- `ConnectorDefinitionId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListConnectorDefinitionVersionsResponseTypeDef](./type_defs.md#listconnectordefinitionversionsresponsetypedef).

<a id="list_connector_definitions"></a>

### list_connector_definitions

Retrieves a list of connector definitions.

Type annotations for
`session.create_client("greengrass").list_connector_definitions` method.

Boto3 documentation:
[Greengrass.Client.list_connector_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_connector_definitions)

Asynchronous method. Use `await list_connector_definitions(...)` for a
synchronous call.

Arguments mapping described in
[ListConnectorDefinitionsRequestRequestTypeDef](./type_defs.md#listconnectordefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListConnectorDefinitionsResponseTypeDef](./type_defs.md#listconnectordefinitionsresponsetypedef).

<a id="list_core_definition_versions"></a>

### list_core_definition_versions

Lists the versions of a core definition.

Type annotations for
`session.create_client("greengrass").list_core_definition_versions` method.

Boto3 documentation:
[Greengrass.Client.list_core_definition_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_core_definition_versions)

Asynchronous method. Use `await list_core_definition_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListCoreDefinitionVersionsRequestRequestTypeDef](./type_defs.md#listcoredefinitionversionsrequestrequesttypedef).

Keyword-only arguments:

- `CoreDefinitionId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListCoreDefinitionVersionsResponseTypeDef](./type_defs.md#listcoredefinitionversionsresponsetypedef).

<a id="list_core_definitions"></a>

### list_core_definitions

Retrieves a list of core definitions.

Type annotations for
`session.create_client("greengrass").list_core_definitions` method.

Boto3 documentation:
[Greengrass.Client.list_core_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_core_definitions)

Asynchronous method. Use `await list_core_definitions(...)` for a synchronous
call.

Arguments mapping described in
[ListCoreDefinitionsRequestRequestTypeDef](./type_defs.md#listcoredefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListCoreDefinitionsResponseTypeDef](./type_defs.md#listcoredefinitionsresponsetypedef).

<a id="list_deployments"></a>

### list_deployments

Returns a history of deployments for the group.

Type annotations for `session.create_client("greengrass").list_deployments`
method.

Boto3 documentation:
[Greengrass.Client.list_deployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_deployments)

Asynchronous method. Use `await list_deployments(...)` for a synchronous call.

Arguments mapping described in
[ListDeploymentsRequestRequestTypeDef](./type_defs.md#listdeploymentsrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListDeploymentsResponseTypeDef](./type_defs.md#listdeploymentsresponsetypedef).

<a id="list_device_definition_versions"></a>

### list_device_definition_versions

Lists the versions of a device definition.

Type annotations for
`session.create_client("greengrass").list_device_definition_versions` method.

Boto3 documentation:
[Greengrass.Client.list_device_definition_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_device_definition_versions)

Asynchronous method. Use `await list_device_definition_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListDeviceDefinitionVersionsRequestRequestTypeDef](./type_defs.md#listdevicedefinitionversionsrequestrequesttypedef).

Keyword-only arguments:

- `DeviceDefinitionId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListDeviceDefinitionVersionsResponseTypeDef](./type_defs.md#listdevicedefinitionversionsresponsetypedef).

<a id="list_device_definitions"></a>

### list_device_definitions

Retrieves a list of device definitions.

Type annotations for
`session.create_client("greengrass").list_device_definitions` method.

Boto3 documentation:
[Greengrass.Client.list_device_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_device_definitions)

Asynchronous method. Use `await list_device_definitions(...)` for a synchronous
call.

Arguments mapping described in
[ListDeviceDefinitionsRequestRequestTypeDef](./type_defs.md#listdevicedefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListDeviceDefinitionsResponseTypeDef](./type_defs.md#listdevicedefinitionsresponsetypedef).

<a id="list_function_definition_versions"></a>

### list_function_definition_versions

Lists the versions of a Lambda function definition.

Type annotations for
`session.create_client("greengrass").list_function_definition_versions` method.

Boto3 documentation:
[Greengrass.Client.list_function_definition_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_function_definition_versions)

Asynchronous method. Use `await list_function_definition_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListFunctionDefinitionVersionsRequestRequestTypeDef](./type_defs.md#listfunctiondefinitionversionsrequestrequesttypedef).

Keyword-only arguments:

- `FunctionDefinitionId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFunctionDefinitionVersionsResponseTypeDef](./type_defs.md#listfunctiondefinitionversionsresponsetypedef).

<a id="list_function_definitions"></a>

### list_function_definitions

Retrieves a list of Lambda function definitions.

Type annotations for
`session.create_client("greengrass").list_function_definitions` method.

Boto3 documentation:
[Greengrass.Client.list_function_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_function_definitions)

Asynchronous method. Use `await list_function_definitions(...)` for a
synchronous call.

Arguments mapping described in
[ListFunctionDefinitionsRequestRequestTypeDef](./type_defs.md#listfunctiondefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFunctionDefinitionsResponseTypeDef](./type_defs.md#listfunctiondefinitionsresponsetypedef).

<a id="list_group_certificate_authorities"></a>

### list_group_certificate_authorities

Retrieves the current CAs for a group.

Type annotations for
`session.create_client("greengrass").list_group_certificate_authorities`
method.

Boto3 documentation:
[Greengrass.Client.list_group_certificate_authorities](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_group_certificate_authorities)

Asynchronous method. Use `await list_group_certificate_authorities(...)` for a
synchronous call.

Arguments mapping described in
[ListGroupCertificateAuthoritiesRequestRequestTypeDef](./type_defs.md#listgroupcertificateauthoritiesrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*

Returns a `Coroutine` for
[ListGroupCertificateAuthoritiesResponseTypeDef](./type_defs.md#listgroupcertificateauthoritiesresponsetypedef).

<a id="list_group_versions"></a>

### list_group_versions

Lists the versions of a group.

Type annotations for `session.create_client("greengrass").list_group_versions`
method.

Boto3 documentation:
[Greengrass.Client.list_group_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_group_versions)

Asynchronous method. Use `await list_group_versions(...)` for a synchronous
call.

Arguments mapping described in
[ListGroupVersionsRequestRequestTypeDef](./type_defs.md#listgroupversionsrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListGroupVersionsResponseTypeDef](./type_defs.md#listgroupversionsresponsetypedef).

<a id="list_groups"></a>

### list_groups

Retrieves a list of groups.

Type annotations for `session.create_client("greengrass").list_groups` method.

Boto3 documentation:
[Greengrass.Client.list_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_groups)

Asynchronous method. Use `await list_groups(...)` for a synchronous call.

Arguments mapping described in
[ListGroupsRequestRequestTypeDef](./type_defs.md#listgroupsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListGroupsResponseTypeDef](./type_defs.md#listgroupsresponsetypedef).

<a id="list_logger_definition_versions"></a>

### list_logger_definition_versions

Lists the versions of a logger definition.

Type annotations for
`session.create_client("greengrass").list_logger_definition_versions` method.

Boto3 documentation:
[Greengrass.Client.list_logger_definition_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_logger_definition_versions)

Asynchronous method. Use `await list_logger_definition_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListLoggerDefinitionVersionsRequestRequestTypeDef](./type_defs.md#listloggerdefinitionversionsrequestrequesttypedef).

Keyword-only arguments:

- `LoggerDefinitionId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListLoggerDefinitionVersionsResponseTypeDef](./type_defs.md#listloggerdefinitionversionsresponsetypedef).

<a id="list_logger_definitions"></a>

### list_logger_definitions

Retrieves a list of logger definitions.

Type annotations for
`session.create_client("greengrass").list_logger_definitions` method.

Boto3 documentation:
[Greengrass.Client.list_logger_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_logger_definitions)

Asynchronous method. Use `await list_logger_definitions(...)` for a synchronous
call.

Arguments mapping described in
[ListLoggerDefinitionsRequestRequestTypeDef](./type_defs.md#listloggerdefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListLoggerDefinitionsResponseTypeDef](./type_defs.md#listloggerdefinitionsresponsetypedef).

<a id="list_resource_definition_versions"></a>

### list_resource_definition_versions

Lists the versions of a resource definition.

Type annotations for
`session.create_client("greengrass").list_resource_definition_versions` method.

Boto3 documentation:
[Greengrass.Client.list_resource_definition_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_resource_definition_versions)

Asynchronous method. Use `await list_resource_definition_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListResourceDefinitionVersionsRequestRequestTypeDef](./type_defs.md#listresourcedefinitionversionsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceDefinitionId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListResourceDefinitionVersionsResponseTypeDef](./type_defs.md#listresourcedefinitionversionsresponsetypedef).

<a id="list_resource_definitions"></a>

### list_resource_definitions

Retrieves a list of resource definitions.

Type annotations for
`session.create_client("greengrass").list_resource_definitions` method.

Boto3 documentation:
[Greengrass.Client.list_resource_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_resource_definitions)

Asynchronous method. Use `await list_resource_definitions(...)` for a
synchronous call.

Arguments mapping described in
[ListResourceDefinitionsRequestRequestTypeDef](./type_defs.md#listresourcedefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListResourceDefinitionsResponseTypeDef](./type_defs.md#listresourcedefinitionsresponsetypedef).

<a id="list_subscription_definition_versions"></a>

### list_subscription_definition_versions

Lists the versions of a subscription definition.

Type annotations for
`session.create_client("greengrass").list_subscription_definition_versions`
method.

Boto3 documentation:
[Greengrass.Client.list_subscription_definition_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_subscription_definition_versions)

Asynchronous method. Use `await list_subscription_definition_versions(...)` for
a synchronous call.

Arguments mapping described in
[ListSubscriptionDefinitionVersionsRequestRequestTypeDef](./type_defs.md#listsubscriptiondefinitionversionsrequestrequesttypedef).

Keyword-only arguments:

- `SubscriptionDefinitionId`: `str` *(required)*
- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListSubscriptionDefinitionVersionsResponseTypeDef](./type_defs.md#listsubscriptiondefinitionversionsresponsetypedef).

<a id="list_subscription_definitions"></a>

### list_subscription_definitions

Retrieves a list of subscription definitions.

Type annotations for
`session.create_client("greengrass").list_subscription_definitions` method.

Boto3 documentation:
[Greengrass.Client.list_subscription_definitions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_subscription_definitions)

Asynchronous method. Use `await list_subscription_definitions(...)` for a
synchronous call.

Arguments mapping described in
[ListSubscriptionDefinitionsRequestRequestTypeDef](./type_defs.md#listsubscriptiondefinitionsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `str`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListSubscriptionDefinitionsResponseTypeDef](./type_defs.md#listsubscriptiondefinitionsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Retrieves a list of resource tags for a resource arn.

Type annotations for
`session.create_client("greengrass").list_tags_for_resource` method.

Boto3 documentation:
[Greengrass.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="reset_deployments"></a>

### reset_deployments

Resets a group's deployments.

Type annotations for `session.create_client("greengrass").reset_deployments`
method.

Boto3 documentation:
[Greengrass.Client.reset_deployments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.reset_deployments)

Asynchronous method. Use `await reset_deployments(...)` for a synchronous call.

Arguments mapping described in
[ResetDeploymentsRequestRequestTypeDef](./type_defs.md#resetdeploymentsrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `AmznClientToken`: `str`
- `Force`: `bool`

Returns a `Coroutine` for
[ResetDeploymentsResponseTypeDef](./type_defs.md#resetdeploymentsresponsetypedef).

<a id="start_bulk_deployment"></a>

### start_bulk_deployment

Deploys multiple groups in one operation.

Type annotations for
`session.create_client("greengrass").start_bulk_deployment` method.

Boto3 documentation:
[Greengrass.Client.start_bulk_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.start_bulk_deployment)

Asynchronous method. Use `await start_bulk_deployment(...)` for a synchronous
call.

Arguments mapping described in
[StartBulkDeploymentRequestRequestTypeDef](./type_defs.md#startbulkdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `ExecutionRoleArn`: `str` *(required)*
- `InputFileUri`: `str` *(required)*
- `AmznClientToken`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[StartBulkDeploymentResponseTypeDef](./type_defs.md#startbulkdeploymentresponsetypedef).

<a id="stop_bulk_deployment"></a>

### stop_bulk_deployment

Stops the execution of a bulk deployment.

Type annotations for `session.create_client("greengrass").stop_bulk_deployment`
method.

Boto3 documentation:
[Greengrass.Client.stop_bulk_deployment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.stop_bulk_deployment)

Asynchronous method. Use `await stop_bulk_deployment(...)` for a synchronous
call.

Arguments mapping described in
[StopBulkDeploymentRequestRequestTypeDef](./type_defs.md#stopbulkdeploymentrequestrequesttypedef).

Keyword-only arguments:

- `BulkDeploymentId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Adds tags to a Greengrass resource.

Type annotations for `session.create_client("greengrass").tag_resource` method.

Boto3 documentation:
[Greengrass.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\]

<a id="untag_resource"></a>

### untag_resource

Remove resource tags from a Greengrass Resource.

Type annotations for `session.create_client("greengrass").untag_resource`
method.

Boto3 documentation:
[Greengrass.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update_connectivity_info"></a>

### update_connectivity_info

Updates the connectivity information for the core.

Type annotations for
`session.create_client("greengrass").update_connectivity_info` method.

Boto3 documentation:
[Greengrass.Client.update_connectivity_info](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_connectivity_info)

Asynchronous method. Use `await update_connectivity_info(...)` for a
synchronous call.

Arguments mapping described in
[UpdateConnectivityInfoRequestRequestTypeDef](./type_defs.md#updateconnectivityinforequestrequesttypedef).

Keyword-only arguments:

- `ThingName`: `str` *(required)*
- `ConnectivityInfo`:
  `Sequence`\[[ConnectivityInfoTypeDef](./type_defs.md#connectivityinfotypedef)\]

Returns a `Coroutine` for
[UpdateConnectivityInfoResponseTypeDef](./type_defs.md#updateconnectivityinforesponsetypedef).

<a id="update_connector_definition"></a>

### update_connector_definition

Updates a connector definition.

Type annotations for
`session.create_client("greengrass").update_connector_definition` method.

Boto3 documentation:
[Greengrass.Client.update_connector_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_connector_definition)

Asynchronous method. Use `await update_connector_definition(...)` for a
synchronous call.

Arguments mapping described in
[UpdateConnectorDefinitionRequestRequestTypeDef](./type_defs.md#updateconnectordefinitionrequestrequesttypedef).

Keyword-only arguments:

- `ConnectorDefinitionId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_core_definition"></a>

### update_core_definition

Updates a core definition.

Type annotations for
`session.create_client("greengrass").update_core_definition` method.

Boto3 documentation:
[Greengrass.Client.update_core_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_core_definition)

Asynchronous method. Use `await update_core_definition(...)` for a synchronous
call.

Arguments mapping described in
[UpdateCoreDefinitionRequestRequestTypeDef](./type_defs.md#updatecoredefinitionrequestrequesttypedef).

Keyword-only arguments:

- `CoreDefinitionId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_device_definition"></a>

### update_device_definition

Updates a device definition.

Type annotations for
`session.create_client("greengrass").update_device_definition` method.

Boto3 documentation:
[Greengrass.Client.update_device_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_device_definition)

Asynchronous method. Use `await update_device_definition(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDeviceDefinitionRequestRequestTypeDef](./type_defs.md#updatedevicedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `DeviceDefinitionId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_function_definition"></a>

### update_function_definition

Updates a Lambda function definition.

Type annotations for
`session.create_client("greengrass").update_function_definition` method.

Boto3 documentation:
[Greengrass.Client.update_function_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_function_definition)

Asynchronous method. Use `await update_function_definition(...)` for a
synchronous call.

Arguments mapping described in
[UpdateFunctionDefinitionRequestRequestTypeDef](./type_defs.md#updatefunctiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `FunctionDefinitionId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_group"></a>

### update_group

Updates a group.

Type annotations for `session.create_client("greengrass").update_group` method.

Boto3 documentation:
[Greengrass.Client.update_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_group)

Asynchronous method. Use `await update_group(...)` for a synchronous call.

Arguments mapping described in
[UpdateGroupRequestRequestTypeDef](./type_defs.md#updategrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_group_certificate_configuration"></a>

### update_group_certificate_configuration

Updates the Certificate expiry time for a group.

Type annotations for
`session.create_client("greengrass").update_group_certificate_configuration`
method.

Boto3 documentation:
[Greengrass.Client.update_group_certificate_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_group_certificate_configuration)

Asynchronous method. Use `await update_group_certificate_configuration(...)`
for a synchronous call.

Arguments mapping described in
[UpdateGroupCertificateConfigurationRequestRequestTypeDef](./type_defs.md#updategroupcertificateconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `CertificateExpiryInMilliseconds`: `str`

Returns a `Coroutine` for
[UpdateGroupCertificateConfigurationResponseTypeDef](./type_defs.md#updategroupcertificateconfigurationresponsetypedef).

<a id="update_logger_definition"></a>

### update_logger_definition

Updates a logger definition.

Type annotations for
`session.create_client("greengrass").update_logger_definition` method.

Boto3 documentation:
[Greengrass.Client.update_logger_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_logger_definition)

Asynchronous method. Use `await update_logger_definition(...)` for a
synchronous call.

Arguments mapping described in
[UpdateLoggerDefinitionRequestRequestTypeDef](./type_defs.md#updateloggerdefinitionrequestrequesttypedef).

Keyword-only arguments:

- `LoggerDefinitionId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_resource_definition"></a>

### update_resource_definition

Updates a resource definition.

Type annotations for
`session.create_client("greengrass").update_resource_definition` method.

Boto3 documentation:
[Greengrass.Client.update_resource_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_resource_definition)

Asynchronous method. Use `await update_resource_definition(...)` for a
synchronous call.

Arguments mapping described in
[UpdateResourceDefinitionRequestRequestTypeDef](./type_defs.md#updateresourcedefinitionrequestrequesttypedef).

Keyword-only arguments:

- `ResourceDefinitionId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_subscription_definition"></a>

### update_subscription_definition

Updates a subscription definition.

Type annotations for
`session.create_client("greengrass").update_subscription_definition` method.

Boto3 documentation:
[Greengrass.Client.update_subscription_definition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_subscription_definition)

Asynchronous method. Use `await update_subscription_definition(...)` for a
synchronous call.

Arguments mapping described in
[UpdateSubscriptionDefinitionRequestRequestTypeDef](./type_defs.md#updatesubscriptiondefinitionrequestrequesttypedef).

Keyword-only arguments:

- `SubscriptionDefinitionId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_thing_runtime_configuration"></a>

### update_thing_runtime_configuration

Updates the runtime configuration of a thing.

Type annotations for
`session.create_client("greengrass").update_thing_runtime_configuration`
method.

Boto3 documentation:
[Greengrass.Client.update_thing_runtime_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.update_thing_runtime_configuration)

Asynchronous method. Use `await update_thing_runtime_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateThingRuntimeConfigurationRequestRequestTypeDef](./type_defs.md#updatethingruntimeconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ThingName`: `str` *(required)*
- `TelemetryConfiguration`:
  [TelemetryConfigurationUpdateTypeDef](./type_defs.md#telemetryconfigurationupdatetypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("greengrass").__aenter__` method.

Boto3 documentation:
[Greengrass.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [GreengrassClient](#greengrassclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("greengrass").__aexit__` method.

Boto3 documentation:
[Greengrass.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrass.html#Greengrass.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("greengrass").get_paginator` method
with overloads.

- `client.get_paginator("list_bulk_deployment_detailed_reports")` ->
  [ListBulkDeploymentDetailedReportsPaginator](./paginators.md#listbulkdeploymentdetailedreportspaginator)
- `client.get_paginator("list_bulk_deployments")` ->
  [ListBulkDeploymentsPaginator](./paginators.md#listbulkdeploymentspaginator)
- `client.get_paginator("list_connector_definition_versions")` ->
  [ListConnectorDefinitionVersionsPaginator](./paginators.md#listconnectordefinitionversionspaginator)
- `client.get_paginator("list_connector_definitions")` ->
  [ListConnectorDefinitionsPaginator](./paginators.md#listconnectordefinitionspaginator)
- `client.get_paginator("list_core_definition_versions")` ->
  [ListCoreDefinitionVersionsPaginator](./paginators.md#listcoredefinitionversionspaginator)
- `client.get_paginator("list_core_definitions")` ->
  [ListCoreDefinitionsPaginator](./paginators.md#listcoredefinitionspaginator)
- `client.get_paginator("list_deployments")` ->
  [ListDeploymentsPaginator](./paginators.md#listdeploymentspaginator)
- `client.get_paginator("list_device_definition_versions")` ->
  [ListDeviceDefinitionVersionsPaginator](./paginators.md#listdevicedefinitionversionspaginator)
- `client.get_paginator("list_device_definitions")` ->
  [ListDeviceDefinitionsPaginator](./paginators.md#listdevicedefinitionspaginator)
- `client.get_paginator("list_function_definition_versions")` ->
  [ListFunctionDefinitionVersionsPaginator](./paginators.md#listfunctiondefinitionversionspaginator)
- `client.get_paginator("list_function_definitions")` ->
  [ListFunctionDefinitionsPaginator](./paginators.md#listfunctiondefinitionspaginator)
- `client.get_paginator("list_group_versions")` ->
  [ListGroupVersionsPaginator](./paginators.md#listgroupversionspaginator)
- `client.get_paginator("list_groups")` ->
  [ListGroupsPaginator](./paginators.md#listgroupspaginator)
- `client.get_paginator("list_logger_definition_versions")` ->
  [ListLoggerDefinitionVersionsPaginator](./paginators.md#listloggerdefinitionversionspaginator)
- `client.get_paginator("list_logger_definitions")` ->
  [ListLoggerDefinitionsPaginator](./paginators.md#listloggerdefinitionspaginator)
- `client.get_paginator("list_resource_definition_versions")` ->
  [ListResourceDefinitionVersionsPaginator](./paginators.md#listresourcedefinitionversionspaginator)
- `client.get_paginator("list_resource_definitions")` ->
  [ListResourceDefinitionsPaginator](./paginators.md#listresourcedefinitionspaginator)
- `client.get_paginator("list_subscription_definition_versions")` ->
  [ListSubscriptionDefinitionVersionsPaginator](./paginators.md#listsubscriptiondefinitionversionspaginator)
- `client.get_paginator("list_subscription_definitions")` ->
  [ListSubscriptionDefinitionsPaginator](./paginators.md#listsubscriptiondefinitionspaginator)
