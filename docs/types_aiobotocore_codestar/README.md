<a id="type-annotations-for-aiobotocore-codestar-module"></a>

# Type annotations for aiobotocore CodeStar module

> [Index](../README.md) > CodeStar

Auto-generated documentation for
[CodeStar](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
type annotations stubs module
[types-aiobotocore-codestar](https://pypi.org/project/types-aiobotocore-codestar/).

- [Type annotations for aiobotocore CodeStar module](#type-annotations-for-aiobotocore-codestar-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [CodeStarClient](#codestarclient)
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

Click `Modify` and select `boto3 common` and `CodeStar`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `CodeStar` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[codestar]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[codestar]'


# standalone installation
python -m pip install types-aiobotocore-codestar
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-codestar
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="codestarclient"></a>

## CodeStarClient

Type annotations for `session.create_client("codestar")` as
[CodeStarClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_codestar.client import CodeStarClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [associate_team_member](./client.md#associate_team_member)
- [can_paginate](./client.md#can_paginate)
- [create_project](./client.md#create_project)
- [create_user_profile](./client.md#create_user_profile)
- [delete_project](./client.md#delete_project)
- [delete_user_profile](./client.md#delete_user_profile)
- [describe_project](./client.md#describe_project)
- [describe_user_profile](./client.md#describe_user_profile)
- [disassociate_team_member](./client.md#disassociate_team_member)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [list_projects](./client.md#list_projects)
- [list_resources](./client.md#list_resources)
- [list_tags_for_project](./client.md#list_tags_for_project)
- [list_team_members](./client.md#list_team_members)
- [list_user_profiles](./client.md#list_user_profiles)
- [tag_project](./client.md#tag_project)
- [untag_project](./client.md#untag_project)
- [update_project](./client.md#update_project)
- [update_team_member](./client.md#update_team_member)
- [update_user_profile](./client.md#update_user_profile)

<a id="exceptions"></a>

### Exceptions

CodeStarClient [exceptions](./client.md#exceptions)

- ClientError
- ConcurrentModificationException
- InvalidNextTokenException
- InvalidServiceRoleException
- LimitExceededException
- ProjectAlreadyExistsException
- ProjectConfigurationException
- ProjectCreationFailedException
- ProjectNotFoundException
- TeamMemberAlreadyAssociatedException
- TeamMemberNotFoundException
- UserProfileAlreadyExistsException
- UserProfileNotFoundException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("codestar").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_codestar.paginator import ListProjectsPaginator, ...
```

- [ListProjectsPaginator](./paginators.md#listprojectspaginator)
- [ListResourcesPaginator](./paginators.md#listresourcespaginator)
- [ListTeamMembersPaginator](./paginators.md#listteammemberspaginator)
- [ListUserProfilesPaginator](./paginators.md#listuserprofilespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_codestar.literals import ListProjectsPaginatorName, ...
```

- [ListProjectsPaginatorName](./literals.md#listprojectspaginatorname)
- [ListResourcesPaginatorName](./literals.md#listresourcespaginatorname)
- [ListTeamMembersPaginatorName](./literals.md#listteammemberspaginatorname)
- [ListUserProfilesPaginatorName](./literals.md#listuserprofilespaginatorname)
- [CodeStarServiceName](./literals.md#codestarservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_codestar.type_defs import AssociateTeamMemberRequestRequestTypeDef, ...
```

- [AssociateTeamMemberRequestRequestTypeDef](./type_defs.md#associateteammemberrequestrequesttypedef)
- [AssociateTeamMemberResultTypeDef](./type_defs.md#associateteammemberresulttypedef)
- [CodeCommitCodeDestinationTypeDef](./type_defs.md#codecommitcodedestinationtypedef)
- [CodeDestinationTypeDef](./type_defs.md#codedestinationtypedef)
- [CodeSourceTypeDef](./type_defs.md#codesourcetypedef)
- [CodeTypeDef](./type_defs.md#codetypedef)
- [CreateProjectRequestRequestTypeDef](./type_defs.md#createprojectrequestrequesttypedef)
- [CreateProjectResultTypeDef](./type_defs.md#createprojectresulttypedef)
- [CreateUserProfileRequestRequestTypeDef](./type_defs.md#createuserprofilerequestrequesttypedef)
- [CreateUserProfileResultTypeDef](./type_defs.md#createuserprofileresulttypedef)
- [DeleteProjectRequestRequestTypeDef](./type_defs.md#deleteprojectrequestrequesttypedef)
- [DeleteProjectResultTypeDef](./type_defs.md#deleteprojectresulttypedef)
- [DeleteUserProfileRequestRequestTypeDef](./type_defs.md#deleteuserprofilerequestrequesttypedef)
- [DeleteUserProfileResultTypeDef](./type_defs.md#deleteuserprofileresulttypedef)
- [DescribeProjectRequestRequestTypeDef](./type_defs.md#describeprojectrequestrequesttypedef)
- [DescribeProjectResultTypeDef](./type_defs.md#describeprojectresulttypedef)
- [DescribeUserProfileRequestRequestTypeDef](./type_defs.md#describeuserprofilerequestrequesttypedef)
- [DescribeUserProfileResultTypeDef](./type_defs.md#describeuserprofileresulttypedef)
- [DisassociateTeamMemberRequestRequestTypeDef](./type_defs.md#disassociateteammemberrequestrequesttypedef)
- [GitHubCodeDestinationTypeDef](./type_defs.md#githubcodedestinationtypedef)
- [ListProjectsRequestRequestTypeDef](./type_defs.md#listprojectsrequestrequesttypedef)
- [ListProjectsResultTypeDef](./type_defs.md#listprojectsresulttypedef)
- [ListResourcesRequestRequestTypeDef](./type_defs.md#listresourcesrequestrequesttypedef)
- [ListResourcesResultTypeDef](./type_defs.md#listresourcesresulttypedef)
- [ListTagsForProjectRequestRequestTypeDef](./type_defs.md#listtagsforprojectrequestrequesttypedef)
- [ListTagsForProjectResultTypeDef](./type_defs.md#listtagsforprojectresulttypedef)
- [ListTeamMembersRequestRequestTypeDef](./type_defs.md#listteammembersrequestrequesttypedef)
- [ListTeamMembersResultTypeDef](./type_defs.md#listteammembersresulttypedef)
- [ListUserProfilesRequestRequestTypeDef](./type_defs.md#listuserprofilesrequestrequesttypedef)
- [ListUserProfilesResultTypeDef](./type_defs.md#listuserprofilesresulttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ProjectStatusTypeDef](./type_defs.md#projectstatustypedef)
- [ProjectSummaryTypeDef](./type_defs.md#projectsummarytypedef)
- [ResourceTypeDef](./type_defs.md#resourcetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [S3LocationTypeDef](./type_defs.md#s3locationtypedef)
- [TagProjectRequestRequestTypeDef](./type_defs.md#tagprojectrequestrequesttypedef)
- [TagProjectResultTypeDef](./type_defs.md#tagprojectresulttypedef)
- [TeamMemberTypeDef](./type_defs.md#teammembertypedef)
- [ToolchainSourceTypeDef](./type_defs.md#toolchainsourcetypedef)
- [ToolchainTypeDef](./type_defs.md#toolchaintypedef)
- [UntagProjectRequestRequestTypeDef](./type_defs.md#untagprojectrequestrequesttypedef)
- [UpdateProjectRequestRequestTypeDef](./type_defs.md#updateprojectrequestrequesttypedef)
- [UpdateTeamMemberRequestRequestTypeDef](./type_defs.md#updateteammemberrequestrequesttypedef)
- [UpdateTeamMemberResultTypeDef](./type_defs.md#updateteammemberresulttypedef)
- [UpdateUserProfileRequestRequestTypeDef](./type_defs.md#updateuserprofilerequestrequesttypedef)
- [UpdateUserProfileResultTypeDef](./type_defs.md#updateuserprofileresulttypedef)
- [UserProfileSummaryTypeDef](./type_defs.md#userprofilesummarytypedef)
