<a id="paginators-for-aiobotocore-codestar-module"></a>

# Paginators for aiobotocore CodeStar module

> [Index](..) > [CodeStar](.) > Paginators

Auto-generated documentation for
[CodeStar](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
type annotations stubs module
[types-aiobotocore-codestar](https://pypi.org/project/types-aiobotocore-codestar/).

- [Paginators for aiobotocore CodeStar module](#paginators-for-aiobotocore-codestar-module)
  - [ListProjectsPaginator](#listprojectspaginator)
  - [ListResourcesPaginator](#listresourcespaginator)
  - [ListTeamMembersPaginator](#listteammemberspaginator)
  - [ListUserProfilesPaginator](#listuserprofilespaginator)

<a id="listprojectspaginator"></a>

## ListProjectsPaginator

Type annotations for
`aiobotocore.create_client("codestar").get_paginator("list_projects")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_codestar.paginator import ListProjectsPaginator

def get_list_projects_paginator() -> ListProjectsPaginator:
    return Session().create_client("codestar").get_paginator("list_projects")
```

Boto3 documentation:
[CodeStar.Paginator.ListProjects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListProjects)

Arguments for `ListProjectsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListProjectsPaginator.paginate` returns
`_PageIterator`\[[ListProjectsResultTypeDef](./type_defs.md#listprojectsresulttypedef)\].

<a id="listresourcespaginator"></a>

## ListResourcesPaginator

Type annotations for
`aiobotocore.create_client("codestar").get_paginator("list_resources")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_codestar.paginator import ListResourcesPaginator

def get_list_resources_paginator() -> ListResourcesPaginator:
    return Session().create_client("codestar").get_paginator("list_resources")
```

Boto3 documentation:
[CodeStar.Paginator.ListResources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListResources)

Arguments for `ListResourcesPaginator.paginate` method:

- `projectId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListResourcesPaginator.paginate` returns
`_PageIterator`\[[ListResourcesResultTypeDef](./type_defs.md#listresourcesresulttypedef)\].

<a id="listteammemberspaginator"></a>

## ListTeamMembersPaginator

Type annotations for
`aiobotocore.create_client("codestar").get_paginator("list_team_members")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_codestar.paginator import ListTeamMembersPaginator

def get_list_team_members_paginator() -> ListTeamMembersPaginator:
    return Session().create_client("codestar").get_paginator("list_team_members")
```

Boto3 documentation:
[CodeStar.Paginator.ListTeamMembers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListTeamMembers)

Arguments for `ListTeamMembersPaginator.paginate` method:

- `projectId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTeamMembersPaginator.paginate` returns
`_PageIterator`\[[ListTeamMembersResultTypeDef](./type_defs.md#listteammembersresulttypedef)\].

<a id="listuserprofilespaginator"></a>

## ListUserProfilesPaginator

Type annotations for
`aiobotocore.create_client("codestar").get_paginator("list_user_profiles")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_codestar.paginator import ListUserProfilesPaginator

def get_list_user_profiles_paginator() -> ListUserProfilesPaginator:
    return Session().create_client("codestar").get_paginator("list_user_profiles")
```

Boto3 documentation:
[CodeStar.Paginator.ListUserProfiles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListUserProfiles)

Arguments for `ListUserProfilesPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListUserProfilesPaginator.paginate` returns
`_PageIterator`\[[ListUserProfilesResultTypeDef](./type_defs.md#listuserprofilesresulttypedef)\].
