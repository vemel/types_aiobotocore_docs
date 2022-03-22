<a id="transferclient-for-aiobotocore-transfer-module"></a>

# TransferClient for aiobotocore Transfer module

> [Index](../README.md) > [Transfer](./README.md) > TransferClient

Auto-generated documentation for
[Transfer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
type annotations stubs module
[types-aiobotocore-transfer](https://pypi.org/project/types-aiobotocore-transfer/).

- [TransferClient for aiobotocore Transfer module](#transferclient-for-aiobotocore-transfer-module)
  - [TransferClient](#transferclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_access](#create_access)
    - [create_server](#create_server)
    - [create_user](#create_user)
    - [create_workflow](#create_workflow)
    - [delete_access](#delete_access)
    - [delete_server](#delete_server)
    - [delete_ssh_public_key](#delete_ssh_public_key)
    - [delete_user](#delete_user)
    - [delete_workflow](#delete_workflow)
    - [describe_access](#describe_access)
    - [describe_execution](#describe_execution)
    - [describe_security_policy](#describe_security_policy)
    - [describe_server](#describe_server)
    - [describe_user](#describe_user)
    - [describe_workflow](#describe_workflow)
    - [generate_presigned_url](#generate_presigned_url)
    - [import_ssh_public_key](#import_ssh_public_key)
    - [list_accesses](#list_accesses)
    - [list_executions](#list_executions)
    - [list_security_policies](#list_security_policies)
    - [list_servers](#list_servers)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_users](#list_users)
    - [list_workflows](#list_workflows)
    - [send_workflow_step_state](#send_workflow_step_state)
    - [start_server](#start_server)
    - [stop_server](#stop_server)
    - [tag_resource](#tag_resource)
    - [test_identity_provider](#test_identity_provider)
    - [untag_resource](#untag_resource)
    - [update_access](#update_access)
    - [update_server](#update_server)
    - [update_user](#update_user)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="transferclient"></a>

## TransferClient

Type annotations for `session.create_client("transfer")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_transfer.client import TransferClient

session = get_session()
async with session.create_client("transfer") as client:
    client: TransferClient
```

Boto3 documentation:
[Transfer.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_transfer.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServiceError`
- `Exceptions.InvalidNextTokenException`
- `Exceptions.InvalidRequestException`
- `Exceptions.ResourceExistsException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.ThrottlingException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

TransferClient exceptions.

Type annotations for `session.create_client("transfer").exceptions` method.

Boto3 documentation:
[Transfer.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("transfer").can_paginate` method.

Boto3 documentation:
[Transfer.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_access"></a>

### create_access

Used by administrators to choose which groups in the directory should have
access to upload and download files over the enabled protocols using Amazon Web
Services Transfer Family.

Type annotations for `session.create_client("transfer").create_access` method.

Boto3 documentation:
[Transfer.Client.create_access](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.create_access)

Asynchronous method. Use `await create_access(...)` for a synchronous call.

Arguments mapping described in
[CreateAccessRequestRequestTypeDef](./type_defs.md#createaccessrequestrequesttypedef).

Keyword-only arguments:

- `Role`: `str` *(required)*
- `ServerId`: `str` *(required)*
- `ExternalId`: `str` *(required)*
- `HomeDirectory`: `str`
- `HomeDirectoryType`:
  [HomeDirectoryTypeType](./literals.md#homedirectorytypetype)
- `HomeDirectoryMappings`:
  `Sequence`\[[HomeDirectoryMapEntryTypeDef](./type_defs.md#homedirectorymapentrytypedef)\]
- `Policy`: `str`
- `PosixProfile`: [PosixProfileTypeDef](./type_defs.md#posixprofiletypedef)

Returns a `Coroutine` for
[CreateAccessResponseTypeDef](./type_defs.md#createaccessresponsetypedef).

<a id="create\_server"></a>

### create_server

Instantiates an auto-scaling virtual server based on the selected file transfer
protocol in Amazon Web Services.

Type annotations for `session.create_client("transfer").create_server` method.

Boto3 documentation:
[Transfer.Client.create_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.create_server)

Asynchronous method. Use `await create_server(...)` for a synchronous call.

Arguments mapping described in
[CreateServerRequestRequestTypeDef](./type_defs.md#createserverrequestrequesttypedef).

Keyword-only arguments:

- `Certificate`: `str`
- `Domain`: [DomainType](./literals.md#domaintype)
- `EndpointDetails`:
  [EndpointDetailsTypeDef](./type_defs.md#endpointdetailstypedef)
- `EndpointType`: [EndpointTypeType](./literals.md#endpointtypetype)
- `HostKey`: `str`
- `IdentityProviderDetails`:
  [IdentityProviderDetailsTypeDef](./type_defs.md#identityproviderdetailstypedef)
- `IdentityProviderType`:
  [IdentityProviderTypeType](./literals.md#identityprovidertypetype)
- `LoggingRole`: `str`
- `PostAuthenticationLoginBanner`: `str`
- `PreAuthenticationLoginBanner`: `str`
- `Protocols`: `Sequence`\[[ProtocolType](./literals.md#protocoltype)\]
- `ProtocolDetails`:
  [ProtocolDetailsTypeDef](./type_defs.md#protocoldetailstypedef)
- `SecurityPolicyName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `WorkflowDetails`:
  [WorkflowDetailsTypeDef](./type_defs.md#workflowdetailstypedef)

Returns a `Coroutine` for
[CreateServerResponseTypeDef](./type_defs.md#createserverresponsetypedef).

<a id="create\_user"></a>

### create_user

Creates a user and associates them with an existing file transfer protocol-
enabled server.

Type annotations for `session.create_client("transfer").create_user` method.

Boto3 documentation:
[Transfer.Client.create_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.create_user)

Asynchronous method. Use `await create_user(...)` for a synchronous call.

Arguments mapping described in
[CreateUserRequestRequestTypeDef](./type_defs.md#createuserrequestrequesttypedef).

Keyword-only arguments:

- `Role`: `str` *(required)*
- `ServerId`: `str` *(required)*
- `UserName`: `str` *(required)*
- `HomeDirectory`: `str`
- `HomeDirectoryType`:
  [HomeDirectoryTypeType](./literals.md#homedirectorytypetype)
- `HomeDirectoryMappings`:
  `Sequence`\[[HomeDirectoryMapEntryTypeDef](./type_defs.md#homedirectorymapentrytypedef)\]
- `Policy`: `str`
- `PosixProfile`: [PosixProfileTypeDef](./type_defs.md#posixprofiletypedef)
- `SshPublicKeyBody`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateUserResponseTypeDef](./type_defs.md#createuserresponsetypedef).

<a id="create\_workflow"></a>

### create_workflow

Allows you to create a workflow with specified steps and step details the
workflow invokes after file transfer completes.

Type annotations for `session.create_client("transfer").create_workflow`
method.

Boto3 documentation:
[Transfer.Client.create_workflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.create_workflow)

Asynchronous method. Use `await create_workflow(...)` for a synchronous call.

Arguments mapping described in
[CreateWorkflowRequestRequestTypeDef](./type_defs.md#createworkflowrequestrequesttypedef).

Keyword-only arguments:

- `Steps`:
  `Sequence`\[[WorkflowStepTypeDef](./type_defs.md#workflowsteptypedef)\]
  *(required)*
- `Description`: `str`
- `OnExceptionSteps`:
  `Sequence`\[[WorkflowStepTypeDef](./type_defs.md#workflowsteptypedef)\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateWorkflowResponseTypeDef](./type_defs.md#createworkflowresponsetypedef).

<a id="delete\_access"></a>

### delete_access

Allows you to delete the access specified in the `ServerID` and `ExternalID`
parameters.

Type annotations for `session.create_client("transfer").delete_access` method.

Boto3 documentation:
[Transfer.Client.delete_access](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_access)

Asynchronous method. Use `await delete_access(...)` for a synchronous call.

Arguments mapping described in
[DeleteAccessRequestRequestTypeDef](./type_defs.md#deleteaccessrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `ExternalId`: `str` *(required)*

<a id="delete\_server"></a>

### delete_server

Deletes the file transfer protocol-enabled server that you specify.

Type annotations for `session.create_client("transfer").delete_server` method.

Boto3 documentation:
[Transfer.Client.delete_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_server)

Asynchronous method. Use `await delete_server(...)` for a synchronous call.

Arguments mapping described in
[DeleteServerRequestRequestTypeDef](./type_defs.md#deleteserverrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*

<a id="delete\_ssh\_public\_key"></a>

### delete_ssh_public_key

Deletes a user's Secure Shell (SSH) public key.

Type annotations for `session.create_client("transfer").delete_ssh_public_key`
method.

Boto3 documentation:
[Transfer.Client.delete_ssh_public_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_ssh_public_key)

Asynchronous method. Use `await delete_ssh_public_key(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSshPublicKeyRequestRequestTypeDef](./type_defs.md#deletesshpublickeyrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `SshPublicKeyId`: `str` *(required)*
- `UserName`: `str` *(required)*

<a id="delete\_user"></a>

### delete_user

Deletes the user belonging to a file transfer protocol-enabled server you
specify.

Type annotations for `session.create_client("transfer").delete_user` method.

Boto3 documentation:
[Transfer.Client.delete_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_user)

Asynchronous method. Use `await delete_user(...)` for a synchronous call.

Arguments mapping described in
[DeleteUserRequestRequestTypeDef](./type_defs.md#deleteuserrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `UserName`: `str` *(required)*

<a id="delete\_workflow"></a>

### delete_workflow

Deletes the specified workflow.

Type annotations for `session.create_client("transfer").delete_workflow`
method.

Boto3 documentation:
[Transfer.Client.delete_workflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_workflow)

Asynchronous method. Use `await delete_workflow(...)` for a synchronous call.

Arguments mapping described in
[DeleteWorkflowRequestRequestTypeDef](./type_defs.md#deleteworkflowrequestrequesttypedef).

Keyword-only arguments:

- `WorkflowId`: `str` *(required)*

<a id="describe\_access"></a>

### describe_access

Describes the access that is assigned to the specific file transfer protocol-
enabled server, as identified by its `ServerId` property and its `ExternalID` .

Type annotations for `session.create_client("transfer").describe_access`
method.

Boto3 documentation:
[Transfer.Client.describe_access](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_access)

Asynchronous method. Use `await describe_access(...)` for a synchronous call.

Arguments mapping described in
[DescribeAccessRequestRequestTypeDef](./type_defs.md#describeaccessrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `ExternalId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAccessResponseTypeDef](./type_defs.md#describeaccessresponsetypedef).

<a id="describe\_execution"></a>

### describe_execution

You can use `DescribeExecution` to check the details of the execution of the
specified workflow.

Type annotations for `session.create_client("transfer").describe_execution`
method.

Boto3 documentation:
[Transfer.Client.describe_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_execution)

Asynchronous method. Use `await describe_execution(...)` for a synchronous
call.

Arguments mapping described in
[DescribeExecutionRequestRequestTypeDef](./type_defs.md#describeexecutionrequestrequesttypedef).

Keyword-only arguments:

- `ExecutionId`: `str` *(required)*
- `WorkflowId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeExecutionResponseTypeDef](./type_defs.md#describeexecutionresponsetypedef).

<a id="describe\_security\_policy"></a>

### describe_security_policy

Describes the security policy that is attached to your file transfer protocol-
enabled server.

Type annotations for
`session.create_client("transfer").describe_security_policy` method.

Boto3 documentation:
[Transfer.Client.describe_security_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_security_policy)

Asynchronous method. Use `await describe_security_policy(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSecurityPolicyRequestRequestTypeDef](./type_defs.md#describesecuritypolicyrequestrequesttypedef).

Keyword-only arguments:

- `SecurityPolicyName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeSecurityPolicyResponseTypeDef](./type_defs.md#describesecuritypolicyresponsetypedef).

<a id="describe\_server"></a>

### describe_server

Describes a file transfer protocol-enabled server that you specify by passing
the `ServerId` parameter.

Type annotations for `session.create_client("transfer").describe_server`
method.

Boto3 documentation:
[Transfer.Client.describe_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_server)

Asynchronous method. Use `await describe_server(...)` for a synchronous call.

Arguments mapping described in
[DescribeServerRequestRequestTypeDef](./type_defs.md#describeserverrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeServerResponseTypeDef](./type_defs.md#describeserverresponsetypedef).

<a id="describe\_user"></a>

### describe_user

Describes the user assigned to the specific file transfer protocol-enabled
server, as identified by its `ServerId` property.

Type annotations for `session.create_client("transfer").describe_user` method.

Boto3 documentation:
[Transfer.Client.describe_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_user)

Asynchronous method. Use `await describe_user(...)` for a synchronous call.

Arguments mapping described in
[DescribeUserRequestRequestTypeDef](./type_defs.md#describeuserrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `UserName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeUserResponseTypeDef](./type_defs.md#describeuserresponsetypedef).

<a id="describe\_workflow"></a>

### describe_workflow

Describes the specified workflow.

Type annotations for `session.create_client("transfer").describe_workflow`
method.

Boto3 documentation:
[Transfer.Client.describe_workflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_workflow)

Asynchronous method. Use `await describe_workflow(...)` for a synchronous call.

Arguments mapping described in
[DescribeWorkflowRequestRequestTypeDef](./type_defs.md#describeworkflowrequestrequesttypedef).

Keyword-only arguments:

- `WorkflowId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeWorkflowResponseTypeDef](./type_defs.md#describeworkflowresponsetypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("transfer").generate_presigned_url`
method.

Boto3 documentation:
[Transfer.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="import\_ssh\_public\_key"></a>

### import_ssh_public_key

Adds a Secure Shell (SSH) public key to a user account identified by a
`UserName` value assigned to the specific file transfer protocol-enabled
server, identified by `ServerId` .

Type annotations for `session.create_client("transfer").import_ssh_public_key`
method.

Boto3 documentation:
[Transfer.Client.import_ssh_public_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.import_ssh_public_key)

Asynchronous method. Use `await import_ssh_public_key(...)` for a synchronous
call.

Arguments mapping described in
[ImportSshPublicKeyRequestRequestTypeDef](./type_defs.md#importsshpublickeyrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `SshPublicKeyBody`: `str` *(required)*
- `UserName`: `str` *(required)*

Returns a `Coroutine` for
[ImportSshPublicKeyResponseTypeDef](./type_defs.md#importsshpublickeyresponsetypedef).

<a id="list\_accesses"></a>

### list_accesses

Lists the details for all the accesses you have on your server.

Type annotations for `session.create_client("transfer").list_accesses` method.

Boto3 documentation:
[Transfer.Client.list_accesses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_accesses)

Asynchronous method. Use `await list_accesses(...)` for a synchronous call.

Arguments mapping described in
[ListAccessesRequestRequestTypeDef](./type_defs.md#listaccessesrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListAccessesResponseTypeDef](./type_defs.md#listaccessesresponsetypedef).

<a id="list\_executions"></a>

### list_executions

Lists all executions for the specified workflow.

Type annotations for `session.create_client("transfer").list_executions`
method.

Boto3 documentation:
[Transfer.Client.list_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_executions)

Asynchronous method. Use `await list_executions(...)` for a synchronous call.

Arguments mapping described in
[ListExecutionsRequestRequestTypeDef](./type_defs.md#listexecutionsrequestrequesttypedef).

Keyword-only arguments:

- `WorkflowId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListExecutionsResponseTypeDef](./type_defs.md#listexecutionsresponsetypedef).

<a id="list\_security\_policies"></a>

### list_security_policies

Lists the security policies that are attached to your file transfer protocol-
enabled servers.

Type annotations for `session.create_client("transfer").list_security_policies`
method.

Boto3 documentation:
[Transfer.Client.list_security_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_security_policies)

Asynchronous method. Use `await list_security_policies(...)` for a synchronous
call.

Arguments mapping described in
[ListSecurityPoliciesRequestRequestTypeDef](./type_defs.md#listsecuritypoliciesrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListSecurityPoliciesResponseTypeDef](./type_defs.md#listsecuritypoliciesresponsetypedef).

<a id="list\_servers"></a>

### list_servers

Lists the file transfer protocol-enabled servers that are associated with your
Amazon Web Services account.

Type annotations for `session.create_client("transfer").list_servers` method.

Boto3 documentation:
[Transfer.Client.list_servers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_servers)

Asynchronous method. Use `await list_servers(...)` for a synchronous call.

Arguments mapping described in
[ListServersRequestRequestTypeDef](./type_defs.md#listserversrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListServersResponseTypeDef](./type_defs.md#listserversresponsetypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Lists all of the tags associated with the Amazon Resource Name (ARN) that you
specify.

Type annotations for `session.create_client("transfer").list_tags_for_resource`
method.

Boto3 documentation:
[Transfer.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list\_users"></a>

### list_users

Lists the users for a file transfer protocol-enabled server that you specify by
passing the `ServerId` parameter.

Type annotations for `session.create_client("transfer").list_users` method.

Boto3 documentation:
[Transfer.Client.list_users](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_users)

Asynchronous method. Use `await list_users(...)` for a synchronous call.

Arguments mapping described in
[ListUsersRequestRequestTypeDef](./type_defs.md#listusersrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListUsersResponseTypeDef](./type_defs.md#listusersresponsetypedef).

<a id="list\_workflows"></a>

### list_workflows

Lists all of your workflows.

Type annotations for `session.create_client("transfer").list_workflows` method.

Boto3 documentation:
[Transfer.Client.list_workflows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_workflows)

Asynchronous method. Use `await list_workflows(...)` for a synchronous call.

Arguments mapping described in
[ListWorkflowsRequestRequestTypeDef](./type_defs.md#listworkflowsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListWorkflowsResponseTypeDef](./type_defs.md#listworkflowsresponsetypedef).

<a id="send\_workflow\_step\_state"></a>

### send_workflow_step_state

Sends a callback for asynchronous custom steps.

Type annotations for
`session.create_client("transfer").send_workflow_step_state` method.

Boto3 documentation:
[Transfer.Client.send_workflow_step_state](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.send_workflow_step_state)

Asynchronous method. Use `await send_workflow_step_state(...)` for a
synchronous call.

Arguments mapping described in
[SendWorkflowStepStateRequestRequestTypeDef](./type_defs.md#sendworkflowstepstaterequestrequesttypedef).

Keyword-only arguments:

- `WorkflowId`: `str` *(required)*
- `ExecutionId`: `str` *(required)*
- `Token`: `str` *(required)*
- `Status`: [CustomStepStatusType](./literals.md#customstepstatustype)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="start\_server"></a>

### start_server

Changes the state of a file transfer protocol-enabled server from `OFFLINE` to
`ONLINE`.

Type annotations for `session.create_client("transfer").start_server` method.

Boto3 documentation:
[Transfer.Client.start_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.start_server)

Asynchronous method. Use `await start_server(...)` for a synchronous call.

Arguments mapping described in
[StartServerRequestRequestTypeDef](./type_defs.md#startserverrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*

<a id="stop\_server"></a>

### stop_server

Changes the state of a file transfer protocol-enabled server from `ONLINE` to
`OFFLINE`.

Type annotations for `session.create_client("transfer").stop_server` method.

Boto3 documentation:
[Transfer.Client.stop_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.stop_server)

Asynchronous method. Use `await stop_server(...)` for a synchronous call.

Arguments mapping described in
[StopServerRequestRequestTypeDef](./type_defs.md#stopserverrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*

<a id="tag\_resource"></a>

### tag_resource

Attaches a key-value pair to a resource, as identified by its Amazon Resource
Name (ARN).

Type annotations for `session.create_client("transfer").tag_resource` method.

Boto3 documentation:
[Transfer.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

<a id="test\_identity\_provider"></a>

### test_identity_provider

If the `IdentityProviderType` of a file transfer protocol-enabled server is
`AWS_DIRECTORY_SERVICE` or `API_Gateway` , tests whether your identity provider
is set up successfully.

Type annotations for `session.create_client("transfer").test_identity_provider`
method.

Boto3 documentation:
[Transfer.Client.test_identity_provider](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.test_identity_provider)

Asynchronous method. Use `await test_identity_provider(...)` for a synchronous
call.

Arguments mapping described in
[TestIdentityProviderRequestRequestTypeDef](./type_defs.md#testidentityproviderrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `UserName`: `str` *(required)*
- `ServerProtocol`: [ProtocolType](./literals.md#protocoltype)
- `SourceIp`: `str`
- `UserPassword`: `str`

Returns a `Coroutine` for
[TestIdentityProviderResponseTypeDef](./type_defs.md#testidentityproviderresponsetypedef).

<a id="untag\_resource"></a>

### untag_resource

Detaches a key-value pair from a resource, as identified by its Amazon Resource
Name (ARN).

Type annotations for `session.create_client("transfer").untag_resource` method.

Boto3 documentation:
[Transfer.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update\_access"></a>

### update_access

Allows you to update parameters for the access specified in the `ServerID` and
`ExternalID` parameters.

Type annotations for `session.create_client("transfer").update_access` method.

Boto3 documentation:
[Transfer.Client.update_access](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.update_access)

Asynchronous method. Use `await update_access(...)` for a synchronous call.

Arguments mapping described in
[UpdateAccessRequestRequestTypeDef](./type_defs.md#updateaccessrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `ExternalId`: `str` *(required)*
- `HomeDirectory`: `str`
- `HomeDirectoryType`:
  [HomeDirectoryTypeType](./literals.md#homedirectorytypetype)
- `HomeDirectoryMappings`:
  `Sequence`\[[HomeDirectoryMapEntryTypeDef](./type_defs.md#homedirectorymapentrytypedef)\]
- `Policy`: `str`
- `PosixProfile`: [PosixProfileTypeDef](./type_defs.md#posixprofiletypedef)
- `Role`: `str`

Returns a `Coroutine` for
[UpdateAccessResponseTypeDef](./type_defs.md#updateaccessresponsetypedef).

<a id="update\_server"></a>

### update_server

Updates the file transfer protocol-enabled server's properties after that
server has been created.

Type annotations for `session.create_client("transfer").update_server` method.

Boto3 documentation:
[Transfer.Client.update_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.update_server)

Asynchronous method. Use `await update_server(...)` for a synchronous call.

Arguments mapping described in
[UpdateServerRequestRequestTypeDef](./type_defs.md#updateserverrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `Certificate`: `str`
- `ProtocolDetails`:
  [ProtocolDetailsTypeDef](./type_defs.md#protocoldetailstypedef)
- `EndpointDetails`:
  [EndpointDetailsTypeDef](./type_defs.md#endpointdetailstypedef)
- `EndpointType`: [EndpointTypeType](./literals.md#endpointtypetype)
- `HostKey`: `str`
- `IdentityProviderDetails`:
  [IdentityProviderDetailsTypeDef](./type_defs.md#identityproviderdetailstypedef)
- `LoggingRole`: `str`
- `PostAuthenticationLoginBanner`: `str`
- `PreAuthenticationLoginBanner`: `str`
- `Protocols`: `Sequence`\[[ProtocolType](./literals.md#protocoltype)\]
- `SecurityPolicyName`: `str`
- `WorkflowDetails`:
  [WorkflowDetailsTypeDef](./type_defs.md#workflowdetailstypedef)

Returns a `Coroutine` for
[UpdateServerResponseTypeDef](./type_defs.md#updateserverresponsetypedef).

<a id="update\_user"></a>

### update_user

Assigns new properties to a user.

Type annotations for `session.create_client("transfer").update_user` method.

Boto3 documentation:
[Transfer.Client.update_user](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.update_user)

Asynchronous method. Use `await update_user(...)` for a synchronous call.

Arguments mapping described in
[UpdateUserRequestRequestTypeDef](./type_defs.md#updateuserrequestrequesttypedef).

Keyword-only arguments:

- `ServerId`: `str` *(required)*
- `UserName`: `str` *(required)*
- `HomeDirectory`: `str`
- `HomeDirectoryType`:
  [HomeDirectoryTypeType](./literals.md#homedirectorytypetype)
- `HomeDirectoryMappings`:
  `Sequence`\[[HomeDirectoryMapEntryTypeDef](./type_defs.md#homedirectorymapentrytypedef)\]
- `Policy`: `str`
- `PosixProfile`: [PosixProfileTypeDef](./type_defs.md#posixprofiletypedef)
- `Role`: `str`

Returns a `Coroutine` for
[UpdateUserResponseTypeDef](./type_defs.md#updateuserresponsetypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("transfer").__aenter__` method.

Boto3 documentation:
[Transfer.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [TransferClient](#transferclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("transfer").__aexit__` method.

Boto3 documentation:
[Transfer.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("transfer").get_paginator` method
with overloads.

- `client.get_paginator("list_accesses")` ->
  [ListAccessesPaginator](./paginators.md#listaccessespaginator)
- `client.get_paginator("list_executions")` ->
  [ListExecutionsPaginator](./paginators.md#listexecutionspaginator)
- `client.get_paginator("list_security_policies")` ->
  [ListSecurityPoliciesPaginator](./paginators.md#listsecuritypoliciespaginator)
- `client.get_paginator("list_servers")` ->
  [ListServersPaginator](./paginators.md#listserverspaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- `client.get_paginator("list_users")` ->
  [ListUsersPaginator](./paginators.md#listuserspaginator)
- `client.get_paginator("list_workflows")` ->
  [ListWorkflowsPaginator](./paginators.md#listworkflowspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("transfer").get_waiter` method with
overloads.

- `client.get_waiter("server_offline")` ->
  [ServerOfflineWaiter](./waiters.md#serverofflinewaiter)
- `client.get_waiter("server_online")` ->
  [ServerOnlineWaiter](./waiters.md#serveronlinewaiter)
