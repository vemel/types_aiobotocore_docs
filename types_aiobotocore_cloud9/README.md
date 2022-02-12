<a id="type-annotations-for-aiobotocore-cloud9-module"></a>

# Type annotations for aiobotocore Cloud9 module

> [Index](..) > Cloud9

Auto-generated documentation for
[Cloud9](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
type annotations stubs module
[types-aiobotocore-cloud9](https://pypi.org/project/types-aiobotocore-cloud9/).

- [Type annotations for aiobotocore Cloud9 module](#type-annotations-for-aiobotocore-cloud9-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Cloud9Client](#cloud9client)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `Cloud9`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `Cloud9` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[cloud9]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[cloud9]'

# standalone installation
python -m pip install types-aiobotocore-cloud9
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-cloud9
```

<a id="cloud9client"></a>

## Cloud9Client

Type annotations for `session.create_client("cloud9")` as
[Cloud9Client](./client.md)

Can be used directly:

```python
from types_aiobotocore_cloud9.client import Cloud9Client
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [create_environment_ec2](./client.md#create_environment_ec2)
- [create_environment_membership](./client.md#create_environment_membership)
- [delete_environment](./client.md#delete_environment)
- [delete_environment_membership](./client.md#delete_environment_membership)
- [describe_environment_memberships](./client.md#describe_environment_memberships)
- [describe_environment_status](./client.md#describe_environment_status)
- [describe_environments](./client.md#describe_environments)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [list_environments](./client.md#list_environments)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_environment](./client.md#update_environment)
- [update_environment_membership](./client.md#update_environment_membership)

<a id="exceptions"></a>

### Exceptions

Cloud9Client [exceptions](./client.md#exceptions)

- BadRequestException
- ClientError
- ConcurrentAccessException
- ConflictException
- ForbiddenException
- InternalServerErrorException
- LimitExceededException
- NotFoundException
- TooManyRequestsException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("cloud9").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_cloud9.paginator import DescribeEnvironmentMembershipsPaginator, ...
```

- [DescribeEnvironmentMembershipsPaginator](./paginators.md#describeenvironmentmembershipspaginator)
- [ListEnvironmentsPaginator](./paginators.md#listenvironmentspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_cloud9.literals import ConnectionTypeType, ...
```

- [ConnectionTypeType](./literals.md#connectiontypetype)
- [DescribeEnvironmentMembershipsPaginatorName](./literals.md#describeenvironmentmembershipspaginatorname)
- [EnvironmentLifecycleStatusType](./literals.md#environmentlifecyclestatustype)
- [EnvironmentStatusType](./literals.md#environmentstatustype)
- [EnvironmentTypeType](./literals.md#environmenttypetype)
- [ListEnvironmentsPaginatorName](./literals.md#listenvironmentspaginatorname)
- [ManagedCredentialsActionType](./literals.md#managedcredentialsactiontype)
- [ManagedCredentialsStatusType](./literals.md#managedcredentialsstatustype)
- [MemberPermissionsType](./literals.md#memberpermissionstype)
- [PermissionsType](./literals.md#permissionstype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_cloud9.type_defs import CreateEnvironmentEC2RequestRequestTypeDef, ...
```

- [CreateEnvironmentEC2RequestRequestTypeDef](./type_defs.md#createenvironmentec2requestrequesttypedef)
- [CreateEnvironmentEC2ResultTypeDef](./type_defs.md#createenvironmentec2resulttypedef)
- [CreateEnvironmentMembershipRequestRequestTypeDef](./type_defs.md#createenvironmentmembershiprequestrequesttypedef)
- [CreateEnvironmentMembershipResultTypeDef](./type_defs.md#createenvironmentmembershipresulttypedef)
- [DeleteEnvironmentMembershipRequestRequestTypeDef](./type_defs.md#deleteenvironmentmembershiprequestrequesttypedef)
- [DeleteEnvironmentRequestRequestTypeDef](./type_defs.md#deleteenvironmentrequestrequesttypedef)
- [DescribeEnvironmentMembershipsRequestRequestTypeDef](./type_defs.md#describeenvironmentmembershipsrequestrequesttypedef)
- [DescribeEnvironmentMembershipsResultTypeDef](./type_defs.md#describeenvironmentmembershipsresulttypedef)
- [DescribeEnvironmentStatusRequestRequestTypeDef](./type_defs.md#describeenvironmentstatusrequestrequesttypedef)
- [DescribeEnvironmentStatusResultTypeDef](./type_defs.md#describeenvironmentstatusresulttypedef)
- [DescribeEnvironmentsRequestRequestTypeDef](./type_defs.md#describeenvironmentsrequestrequesttypedef)
- [DescribeEnvironmentsResultTypeDef](./type_defs.md#describeenvironmentsresulttypedef)
- [EnvironmentLifecycleTypeDef](./type_defs.md#environmentlifecycletypedef)
- [EnvironmentMemberTypeDef](./type_defs.md#environmentmembertypedef)
- [EnvironmentTypeDef](./type_defs.md#environmenttypedef)
- [ListEnvironmentsRequestRequestTypeDef](./type_defs.md#listenvironmentsrequestrequesttypedef)
- [ListEnvironmentsResultTypeDef](./type_defs.md#listenvironmentsresulttypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateEnvironmentMembershipRequestRequestTypeDef](./type_defs.md#updateenvironmentmembershiprequestrequesttypedef)
- [UpdateEnvironmentMembershipResultTypeDef](./type_defs.md#updateenvironmentmembershipresulttypedef)
- [UpdateEnvironmentRequestRequestTypeDef](./type_defs.md#updateenvironmentrequestrequesttypedef)
