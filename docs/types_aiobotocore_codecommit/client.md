<a id="codecommitclient-for-aiobotocore-codecommit-module"></a>

# CodeCommitClient for aiobotocore CodeCommit module

> [Index](../README.md) > [CodeCommit](./README.md) > CodeCommitClient

Auto-generated documentation for
[CodeCommit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit)
type annotations stubs module
[types-aiobotocore-codecommit](https://pypi.org/project/types-aiobotocore-codecommit/).

- [CodeCommitClient for aiobotocore CodeCommit module](#codecommitclient-for-aiobotocore-codecommit-module)
  - [CodeCommitClient](#codecommitclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_approval_rule_template_with_repository](#associate_approval_rule_template_with_repository)
    - [batch_associate_approval_rule_template_with_repositories](#batch_associate_approval_rule_template_with_repositories)
    - [batch_describe_merge_conflicts](#batch_describe_merge_conflicts)
    - [batch_disassociate_approval_rule_template_from_repositories](#batch_disassociate_approval_rule_template_from_repositories)
    - [batch_get_commits](#batch_get_commits)
    - [batch_get_repositories](#batch_get_repositories)
    - [can_paginate](#can_paginate)
    - [create_approval_rule_template](#create_approval_rule_template)
    - [create_branch](#create_branch)
    - [create_commit](#create_commit)
    - [create_pull_request](#create_pull_request)
    - [create_pull_request_approval_rule](#create_pull_request_approval_rule)
    - [create_repository](#create_repository)
    - [create_unreferenced_merge_commit](#create_unreferenced_merge_commit)
    - [delete_approval_rule_template](#delete_approval_rule_template)
    - [delete_branch](#delete_branch)
    - [delete_comment_content](#delete_comment_content)
    - [delete_file](#delete_file)
    - [delete_pull_request_approval_rule](#delete_pull_request_approval_rule)
    - [delete_repository](#delete_repository)
    - [describe_merge_conflicts](#describe_merge_conflicts)
    - [describe_pull_request_events](#describe_pull_request_events)
    - [disassociate_approval_rule_template_from_repository](#disassociate_approval_rule_template_from_repository)
    - [evaluate_pull_request_approval_rules](#evaluate_pull_request_approval_rules)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_approval_rule_template](#get_approval_rule_template)
    - [get_blob](#get_blob)
    - [get_branch](#get_branch)
    - [get_comment](#get_comment)
    - [get_comment_reactions](#get_comment_reactions)
    - [get_comments_for_compared_commit](#get_comments_for_compared_commit)
    - [get_comments_for_pull_request](#get_comments_for_pull_request)
    - [get_commit](#get_commit)
    - [get_differences](#get_differences)
    - [get_file](#get_file)
    - [get_folder](#get_folder)
    - [get_merge_commit](#get_merge_commit)
    - [get_merge_conflicts](#get_merge_conflicts)
    - [get_merge_options](#get_merge_options)
    - [get_pull_request](#get_pull_request)
    - [get_pull_request_approval_states](#get_pull_request_approval_states)
    - [get_pull_request_override_state](#get_pull_request_override_state)
    - [get_repository](#get_repository)
    - [get_repository_triggers](#get_repository_triggers)
    - [list_approval_rule_templates](#list_approval_rule_templates)
    - [list_associated_approval_rule_templates_for_repository](#list_associated_approval_rule_templates_for_repository)
    - [list_branches](#list_branches)
    - [list_pull_requests](#list_pull_requests)
    - [list_repositories](#list_repositories)
    - [list_repositories_for_approval_rule_template](#list_repositories_for_approval_rule_template)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [merge_branches_by_fast_forward](#merge_branches_by_fast_forward)
    - [merge_branches_by_squash](#merge_branches_by_squash)
    - [merge_branches_by_three_way](#merge_branches_by_three_way)
    - [merge_pull_request_by_fast_forward](#merge_pull_request_by_fast_forward)
    - [merge_pull_request_by_squash](#merge_pull_request_by_squash)
    - [merge_pull_request_by_three_way](#merge_pull_request_by_three_way)
    - [override_pull_request_approval_rules](#override_pull_request_approval_rules)
    - [post_comment_for_compared_commit](#post_comment_for_compared_commit)
    - [post_comment_for_pull_request](#post_comment_for_pull_request)
    - [post_comment_reply](#post_comment_reply)
    - [put_comment_reaction](#put_comment_reaction)
    - [put_file](#put_file)
    - [put_repository_triggers](#put_repository_triggers)
    - [tag_resource](#tag_resource)
    - [test_repository_triggers](#test_repository_triggers)
    - [untag_resource](#untag_resource)
    - [update_approval_rule_template_content](#update_approval_rule_template_content)
    - [update_approval_rule_template_description](#update_approval_rule_template_description)
    - [update_approval_rule_template_name](#update_approval_rule_template_name)
    - [update_comment](#update_comment)
    - [update_default_branch](#update_default_branch)
    - [update_pull_request_approval_rule_content](#update_pull_request_approval_rule_content)
    - [update_pull_request_approval_state](#update_pull_request_approval_state)
    - [update_pull_request_description](#update_pull_request_description)
    - [update_pull_request_status](#update_pull_request_status)
    - [update_pull_request_title](#update_pull_request_title)
    - [update_repository_description](#update_repository_description)
    - [update_repository_name](#update_repository_name)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="codecommitclient"></a>

## CodeCommitClient

Type annotations for `session.create_client("codecommit")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_codecommit.client import CodeCommitClient

session = get_session()
async with session.create_client("codecommit") as client:
    client: CodeCommitClient
```

Boto3 documentation:
[CodeCommit.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_codecommit.client import Exceptions

def handle_error(exc: Exceptions.ActorDoesNotExistException) -> None:
    ...
```

Exceptions:

- `Exceptions.ActorDoesNotExistException`
- `Exceptions.ApprovalRuleContentRequiredException`
- `Exceptions.ApprovalRuleDoesNotExistException`
- `Exceptions.ApprovalRuleNameAlreadyExistsException`
- `Exceptions.ApprovalRuleNameRequiredException`
- `Exceptions.ApprovalRuleTemplateContentRequiredException`
- `Exceptions.ApprovalRuleTemplateDoesNotExistException`
- `Exceptions.ApprovalRuleTemplateInUseException`
- `Exceptions.ApprovalRuleTemplateNameAlreadyExistsException`
- `Exceptions.ApprovalRuleTemplateNameRequiredException`
- `Exceptions.ApprovalStateRequiredException`
- `Exceptions.AuthorDoesNotExistException`
- `Exceptions.BeforeCommitIdAndAfterCommitIdAreSameException`
- `Exceptions.BlobIdDoesNotExistException`
- `Exceptions.BlobIdRequiredException`
- `Exceptions.BranchDoesNotExistException`
- `Exceptions.BranchNameExistsException`
- `Exceptions.BranchNameIsTagNameException`
- `Exceptions.BranchNameRequiredException`
- `Exceptions.CannotDeleteApprovalRuleFromTemplateException`
- `Exceptions.CannotModifyApprovalRuleFromTemplateException`
- `Exceptions.ClientError`
- `Exceptions.ClientRequestTokenRequiredException`
- `Exceptions.CommentContentRequiredException`
- `Exceptions.CommentContentSizeLimitExceededException`
- `Exceptions.CommentDeletedException`
- `Exceptions.CommentDoesNotExistException`
- `Exceptions.CommentIdRequiredException`
- `Exceptions.CommentNotCreatedByCallerException`
- `Exceptions.CommitDoesNotExistException`
- `Exceptions.CommitIdDoesNotExistException`
- `Exceptions.CommitIdRequiredException`
- `Exceptions.CommitIdsLimitExceededException`
- `Exceptions.CommitIdsListRequiredException`
- `Exceptions.CommitMessageLengthExceededException`
- `Exceptions.CommitRequiredException`
- `Exceptions.ConcurrentReferenceUpdateException`
- `Exceptions.DefaultBranchCannotBeDeletedException`
- `Exceptions.DirectoryNameConflictsWithFileNameException`
- `Exceptions.EncryptionIntegrityChecksFailedException`
- `Exceptions.EncryptionKeyAccessDeniedException`
- `Exceptions.EncryptionKeyDisabledException`
- `Exceptions.EncryptionKeyNotFoundException`
- `Exceptions.EncryptionKeyUnavailableException`
- `Exceptions.FileContentAndSourceFileSpecifiedException`
- `Exceptions.FileContentRequiredException`
- `Exceptions.FileContentSizeLimitExceededException`
- `Exceptions.FileDoesNotExistException`
- `Exceptions.FileEntryRequiredException`
- `Exceptions.FileModeRequiredException`
- `Exceptions.FileNameConflictsWithDirectoryNameException`
- `Exceptions.FilePathConflictsWithSubmodulePathException`
- `Exceptions.FileTooLargeException`
- `Exceptions.FolderContentSizeLimitExceededException`
- `Exceptions.FolderDoesNotExistException`
- `Exceptions.IdempotencyParameterMismatchException`
- `Exceptions.InvalidActorArnException`
- `Exceptions.InvalidApprovalRuleContentException`
- `Exceptions.InvalidApprovalRuleNameException`
- `Exceptions.InvalidApprovalRuleTemplateContentException`
- `Exceptions.InvalidApprovalRuleTemplateDescriptionException`
- `Exceptions.InvalidApprovalRuleTemplateNameException`
- `Exceptions.InvalidApprovalStateException`
- `Exceptions.InvalidAuthorArnException`
- `Exceptions.InvalidBlobIdException`
- `Exceptions.InvalidBranchNameException`
- `Exceptions.InvalidClientRequestTokenException`
- `Exceptions.InvalidCommentIdException`
- `Exceptions.InvalidCommitException`
- `Exceptions.InvalidCommitIdException`
- `Exceptions.InvalidConflictDetailLevelException`
- `Exceptions.InvalidConflictResolutionException`
- `Exceptions.InvalidConflictResolutionStrategyException`
- `Exceptions.InvalidContinuationTokenException`
- `Exceptions.InvalidDeletionParameterException`
- `Exceptions.InvalidDescriptionException`
- `Exceptions.InvalidDestinationCommitSpecifierException`
- `Exceptions.InvalidEmailException`
- `Exceptions.InvalidFileLocationException`
- `Exceptions.InvalidFileModeException`
- `Exceptions.InvalidFilePositionException`
- `Exceptions.InvalidMaxConflictFilesException`
- `Exceptions.InvalidMaxMergeHunksException`
- `Exceptions.InvalidMaxResultsException`
- `Exceptions.InvalidMergeOptionException`
- `Exceptions.InvalidOrderException`
- `Exceptions.InvalidOverrideStatusException`
- `Exceptions.InvalidParentCommitIdException`
- `Exceptions.InvalidPathException`
- `Exceptions.InvalidPullRequestEventTypeException`
- `Exceptions.InvalidPullRequestIdException`
- `Exceptions.InvalidPullRequestStatusException`
- `Exceptions.InvalidPullRequestStatusUpdateException`
- `Exceptions.InvalidReactionUserArnException`
- `Exceptions.InvalidReactionValueException`
- `Exceptions.InvalidReferenceNameException`
- `Exceptions.InvalidRelativeFileVersionEnumException`
- `Exceptions.InvalidReplacementContentException`
- `Exceptions.InvalidReplacementTypeException`
- `Exceptions.InvalidRepositoryDescriptionException`
- `Exceptions.InvalidRepositoryNameException`
- `Exceptions.InvalidRepositoryTriggerBranchNameException`
- `Exceptions.InvalidRepositoryTriggerCustomDataException`
- `Exceptions.InvalidRepositoryTriggerDestinationArnException`
- `Exceptions.InvalidRepositoryTriggerEventsException`
- `Exceptions.InvalidRepositoryTriggerNameException`
- `Exceptions.InvalidRepositoryTriggerRegionException`
- `Exceptions.InvalidResourceArnException`
- `Exceptions.InvalidRevisionIdException`
- `Exceptions.InvalidRuleContentSha256Exception`
- `Exceptions.InvalidSortByException`
- `Exceptions.InvalidSourceCommitSpecifierException`
- `Exceptions.InvalidSystemTagUsageException`
- `Exceptions.InvalidTagKeysListException`
- `Exceptions.InvalidTagsMapException`
- `Exceptions.InvalidTargetBranchException`
- `Exceptions.InvalidTargetException`
- `Exceptions.InvalidTargetsException`
- `Exceptions.InvalidTitleException`
- `Exceptions.ManualMergeRequiredException`
- `Exceptions.MaximumBranchesExceededException`
- `Exceptions.MaximumConflictResolutionEntriesExceededException`
- `Exceptions.MaximumFileContentToLoadExceededException`
- `Exceptions.MaximumFileEntriesExceededException`
- `Exceptions.MaximumItemsToCompareExceededException`
- `Exceptions.MaximumNumberOfApprovalsExceededException`
- `Exceptions.MaximumOpenPullRequestsExceededException`
- `Exceptions.MaximumRepositoryNamesExceededException`
- `Exceptions.MaximumRepositoryTriggersExceededException`
- `Exceptions.MaximumRuleTemplatesAssociatedWithRepositoryException`
- `Exceptions.MergeOptionRequiredException`
- `Exceptions.MultipleConflictResolutionEntriesException`
- `Exceptions.MultipleRepositoriesInPullRequestException`
- `Exceptions.NameLengthExceededException`
- `Exceptions.NoChangeException`
- `Exceptions.NumberOfRuleTemplatesExceededException`
- `Exceptions.NumberOfRulesExceededException`
- `Exceptions.OverrideAlreadySetException`
- `Exceptions.OverrideStatusRequiredException`
- `Exceptions.ParentCommitDoesNotExistException`
- `Exceptions.ParentCommitIdOutdatedException`
- `Exceptions.ParentCommitIdRequiredException`
- `Exceptions.PathDoesNotExistException`
- `Exceptions.PathRequiredException`
- `Exceptions.PullRequestAlreadyClosedException`
- `Exceptions.PullRequestApprovalRulesNotSatisfiedException`
- `Exceptions.PullRequestCannotBeApprovedByAuthorException`
- `Exceptions.PullRequestDoesNotExistException`
- `Exceptions.PullRequestIdRequiredException`
- `Exceptions.PullRequestStatusRequiredException`
- `Exceptions.PutFileEntryConflictException`
- `Exceptions.ReactionLimitExceededException`
- `Exceptions.ReactionValueRequiredException`
- `Exceptions.ReferenceDoesNotExistException`
- `Exceptions.ReferenceNameRequiredException`
- `Exceptions.ReferenceTypeNotSupportedException`
- `Exceptions.ReplacementContentRequiredException`
- `Exceptions.ReplacementTypeRequiredException`
- `Exceptions.RepositoryDoesNotExistException`
- `Exceptions.RepositoryLimitExceededException`
- `Exceptions.RepositoryNameExistsException`
- `Exceptions.RepositoryNameRequiredException`
- `Exceptions.RepositoryNamesRequiredException`
- `Exceptions.RepositoryNotAssociatedWithPullRequestException`
- `Exceptions.RepositoryTriggerBranchNameListRequiredException`
- `Exceptions.RepositoryTriggerDestinationArnRequiredException`
- `Exceptions.RepositoryTriggerEventsListRequiredException`
- `Exceptions.RepositoryTriggerNameRequiredException`
- `Exceptions.RepositoryTriggersListRequiredException`
- `Exceptions.ResourceArnRequiredException`
- `Exceptions.RestrictedSourceFileException`
- `Exceptions.RevisionIdRequiredException`
- `Exceptions.RevisionNotCurrentException`
- `Exceptions.SameFileContentException`
- `Exceptions.SamePathRequestException`
- `Exceptions.SourceAndDestinationAreSameException`
- `Exceptions.SourceFileOrContentRequiredException`
- `Exceptions.TagKeysListRequiredException`
- `Exceptions.TagPolicyException`
- `Exceptions.TagsMapRequiredException`
- `Exceptions.TargetRequiredException`
- `Exceptions.TargetsRequiredException`
- `Exceptions.TipOfSourceReferenceIsDifferentException`
- `Exceptions.TipsDivergenceExceededException`
- `Exceptions.TitleRequiredException`
- `Exceptions.TooManyTagsException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

CodeCommitClient exceptions.

Type annotations for `session.create_client("codecommit").exceptions` method.

Boto3 documentation:
[CodeCommit.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate\_approval\_rule\_template\_with\_repository"></a>

### associate_approval_rule_template_with_repository

Creates an association between an approval rule template and a specified
repository.

Type annotations for
`session.create_client("codecommit").associate_approval_rule_template_with_repository`
method.

Boto3 documentation:
[CodeCommit.Client.associate_approval_rule_template_with_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.associate_approval_rule_template_with_repository)

Asynchronous method. Use
`await associate_approval_rule_template_with_repository(...)` for a synchronous
call.

Arguments mapping described in
[AssociateApprovalRuleTemplateWithRepositoryInputRequestTypeDef](./type_defs.md#associateapprovalruletemplatewithrepositoryinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `repositoryName`: `str` *(required)*

<a id="batch\_associate\_approval\_rule\_template\_with\_repositories"></a>

### batch_associate_approval_rule_template_with_repositories

Creates an association between an approval rule template and one or more
specified repositories.

Type annotations for
`session.create_client("codecommit").batch_associate_approval_rule_template_with_repositories`
method.

Boto3 documentation:
[CodeCommit.Client.batch_associate_approval_rule_template_with_repositories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.batch_associate_approval_rule_template_with_repositories)

Asynchronous method. Use
`await batch_associate_approval_rule_template_with_repositories(...)` for a
synchronous call.

Arguments mapping described in
[BatchAssociateApprovalRuleTemplateWithRepositoriesInputRequestTypeDef](./type_defs.md#batchassociateapprovalruletemplatewithrepositoriesinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `repositoryNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchAssociateApprovalRuleTemplateWithRepositoriesOutputTypeDef](./type_defs.md#batchassociateapprovalruletemplatewithrepositoriesoutputtypedef).

<a id="batch\_describe\_merge\_conflicts"></a>

### batch_describe_merge_conflicts

Returns information about one or more merge conflicts in the attempted merge of
two commit specifiers using the squash or three-way merge strategy.

Type annotations for
`session.create_client("codecommit").batch_describe_merge_conflicts` method.

Boto3 documentation:
[CodeCommit.Client.batch_describe_merge_conflicts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.batch_describe_merge_conflicts)

Asynchronous method. Use `await batch_describe_merge_conflicts(...)` for a
synchronous call.

Arguments mapping described in
[BatchDescribeMergeConflictsInputRequestTypeDef](./type_defs.md#batchdescribemergeconflictsinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `mergeOption`:
  [MergeOptionTypeEnumType](./literals.md#mergeoptiontypeenumtype) *(required)*
- `maxMergeHunks`: `int`
- `maxConflictFiles`: `int`
- `filePaths`: `Sequence`\[`str`\]
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `nextToken`: `str`

Returns a `Coroutine` for
[BatchDescribeMergeConflictsOutputTypeDef](./type_defs.md#batchdescribemergeconflictsoutputtypedef).

<a id="batch\_disassociate\_approval\_rule\_template\_from\_repositories"></a>

### batch_disassociate_approval_rule_template_from_repositories

Removes the association between an approval rule template and one or more
specified repositories.

Type annotations for
`session.create_client("codecommit").batch_disassociate_approval_rule_template_from_repositories`
method.

Boto3 documentation:
[CodeCommit.Client.batch_disassociate_approval_rule_template_from_repositories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.batch_disassociate_approval_rule_template_from_repositories)

Asynchronous method. Use
`await batch_disassociate_approval_rule_template_from_repositories(...)` for a
synchronous call.

Arguments mapping described in
[BatchDisassociateApprovalRuleTemplateFromRepositoriesInputRequestTypeDef](./type_defs.md#batchdisassociateapprovalruletemplatefromrepositoriesinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `repositoryNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchDisassociateApprovalRuleTemplateFromRepositoriesOutputTypeDef](./type_defs.md#batchdisassociateapprovalruletemplatefromrepositoriesoutputtypedef).

<a id="batch\_get\_commits"></a>

### batch_get_commits

Returns information about the contents of one or more commits in a repository.

Type annotations for `session.create_client("codecommit").batch_get_commits`
method.

Boto3 documentation:
[CodeCommit.Client.batch_get_commits](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.batch_get_commits)

Asynchronous method. Use `await batch_get_commits(...)` for a synchronous call.

Arguments mapping described in
[BatchGetCommitsInputRequestTypeDef](./type_defs.md#batchgetcommitsinputrequesttypedef).

Keyword-only arguments:

- `commitIds`: `Sequence`\[`str`\] *(required)*
- `repositoryName`: `str` *(required)*

Returns a `Coroutine` for
[BatchGetCommitsOutputTypeDef](./type_defs.md#batchgetcommitsoutputtypedef).

<a id="batch\_get\_repositories"></a>

### batch_get_repositories

Returns information about one or more repositories.

Type annotations for
`session.create_client("codecommit").batch_get_repositories` method.

Boto3 documentation:
[CodeCommit.Client.batch_get_repositories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.batch_get_repositories)

Asynchronous method. Use `await batch_get_repositories(...)` for a synchronous
call.

Arguments mapping described in
[BatchGetRepositoriesInputRequestTypeDef](./type_defs.md#batchgetrepositoriesinputrequesttypedef).

Keyword-only arguments:

- `repositoryNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[BatchGetRepositoriesOutputTypeDef](./type_defs.md#batchgetrepositoriesoutputtypedef).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("codecommit").can_paginate` method.

Boto3 documentation:
[CodeCommit.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_approval\_rule\_template"></a>

### create_approval_rule_template

Creates a template for approval rules that can then be associated with one or
more repositories in your AWS account.

Type annotations for
`session.create_client("codecommit").create_approval_rule_template` method.

Boto3 documentation:
[CodeCommit.Client.create_approval_rule_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.create_approval_rule_template)

Asynchronous method. Use `await create_approval_rule_template(...)` for a
synchronous call.

Arguments mapping described in
[CreateApprovalRuleTemplateInputRequestTypeDef](./type_defs.md#createapprovalruletemplateinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `approvalRuleTemplateContent`: `str` *(required)*
- `approvalRuleTemplateDescription`: `str`

Returns a `Coroutine` for
[CreateApprovalRuleTemplateOutputTypeDef](./type_defs.md#createapprovalruletemplateoutputtypedef).

<a id="create\_branch"></a>

### create_branch

Creates a branch in a repository and points the branch to a commit.

Type annotations for `session.create_client("codecommit").create_branch`
method.

Boto3 documentation:
[CodeCommit.Client.create_branch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.create_branch)

Asynchronous method. Use `await create_branch(...)` for a synchronous call.

Arguments mapping described in
[CreateBranchInputRequestTypeDef](./type_defs.md#createbranchinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `branchName`: `str` *(required)*
- `commitId`: `str` *(required)*

<a id="create\_commit"></a>

### create_commit

Creates a commit for a repository on the tip of a specified branch.

Type annotations for `session.create_client("codecommit").create_commit`
method.

Boto3 documentation:
[CodeCommit.Client.create_commit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.create_commit)

Asynchronous method. Use `await create_commit(...)` for a synchronous call.

Arguments mapping described in
[CreateCommitInputRequestTypeDef](./type_defs.md#createcommitinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `branchName`: `str` *(required)*
- `parentCommitId`: `str`
- `authorName`: `str`
- `email`: `str`
- `commitMessage`: `str`
- `keepEmptyFolders`: `bool`
- `putFiles`:
  `Sequence`\[[PutFileEntryTypeDef](./type_defs.md#putfileentrytypedef)\]
- `deleteFiles`:
  `Sequence`\[[DeleteFileEntryTypeDef](./type_defs.md#deletefileentrytypedef)\]
- `setFileModes`:
  `Sequence`\[[SetFileModeEntryTypeDef](./type_defs.md#setfilemodeentrytypedef)\]

Returns a `Coroutine` for
[CreateCommitOutputTypeDef](./type_defs.md#createcommitoutputtypedef).

<a id="create\_pull\_request"></a>

### create_pull_request

Creates a pull request in the specified repository.

Type annotations for `session.create_client("codecommit").create_pull_request`
method.

Boto3 documentation:
[CodeCommit.Client.create_pull_request](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.create_pull_request)

Asynchronous method. Use `await create_pull_request(...)` for a synchronous
call.

Arguments mapping described in
[CreatePullRequestInputRequestTypeDef](./type_defs.md#createpullrequestinputrequesttypedef).

Keyword-only arguments:

- `title`: `str` *(required)*
- `targets`: `Sequence`\[[TargetTypeDef](./type_defs.md#targettypedef)\]
  *(required)*
- `description`: `str`
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[CreatePullRequestOutputTypeDef](./type_defs.md#createpullrequestoutputtypedef).

<a id="create\_pull\_request\_approval\_rule"></a>

### create_pull_request_approval_rule

Creates an approval rule for a pull request.

Type annotations for
`session.create_client("codecommit").create_pull_request_approval_rule` method.

Boto3 documentation:
[CodeCommit.Client.create_pull_request_approval_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.create_pull_request_approval_rule)

Asynchronous method. Use `await create_pull_request_approval_rule(...)` for a
synchronous call.

Arguments mapping described in
[CreatePullRequestApprovalRuleInputRequestTypeDef](./type_defs.md#createpullrequestapprovalruleinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `approvalRuleName`: `str` *(required)*
- `approvalRuleContent`: `str` *(required)*

Returns a `Coroutine` for
[CreatePullRequestApprovalRuleOutputTypeDef](./type_defs.md#createpullrequestapprovalruleoutputtypedef).

<a id="create\_repository"></a>

### create_repository

Creates a new, empty repository.

Type annotations for `session.create_client("codecommit").create_repository`
method.

Boto3 documentation:
[CodeCommit.Client.create_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.create_repository)

Asynchronous method. Use `await create_repository(...)` for a synchronous call.

Arguments mapping described in
[CreateRepositoryInputRequestTypeDef](./type_defs.md#createrepositoryinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `repositoryDescription`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateRepositoryOutputTypeDef](./type_defs.md#createrepositoryoutputtypedef).

<a id="create\_unreferenced\_merge\_commit"></a>

### create_unreferenced_merge_commit

Creates an unreferenced commit that represents the result of merging two
branches using a specified merge strategy.

Type annotations for
`session.create_client("codecommit").create_unreferenced_merge_commit` method.

Boto3 documentation:
[CodeCommit.Client.create_unreferenced_merge_commit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.create_unreferenced_merge_commit)

Asynchronous method. Use `await create_unreferenced_merge_commit(...)` for a
synchronous call.

Arguments mapping described in
[CreateUnreferencedMergeCommitInputRequestTypeDef](./type_defs.md#createunreferencedmergecommitinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `mergeOption`:
  [MergeOptionTypeEnumType](./literals.md#mergeoptiontypeenumtype) *(required)*
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `authorName`: `str`
- `email`: `str`
- `commitMessage`: `str`
- `keepEmptyFolders`: `bool`
- `conflictResolution`:
  [ConflictResolutionTypeDef](./type_defs.md#conflictresolutiontypedef)

Returns a `Coroutine` for
[CreateUnreferencedMergeCommitOutputTypeDef](./type_defs.md#createunreferencedmergecommitoutputtypedef).

<a id="delete\_approval\_rule\_template"></a>

### delete_approval_rule_template

Deletes a specified approval rule template.

Type annotations for
`session.create_client("codecommit").delete_approval_rule_template` method.

Boto3 documentation:
[CodeCommit.Client.delete_approval_rule_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.delete_approval_rule_template)

Asynchronous method. Use `await delete_approval_rule_template(...)` for a
synchronous call.

Arguments mapping described in
[DeleteApprovalRuleTemplateInputRequestTypeDef](./type_defs.md#deleteapprovalruletemplateinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteApprovalRuleTemplateOutputTypeDef](./type_defs.md#deleteapprovalruletemplateoutputtypedef).

<a id="delete\_branch"></a>

### delete_branch

Deletes a branch from a repository, unless that branch is the default branch
for the repository.

Type annotations for `session.create_client("codecommit").delete_branch`
method.

Boto3 documentation:
[CodeCommit.Client.delete_branch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.delete_branch)

Asynchronous method. Use `await delete_branch(...)` for a synchronous call.

Arguments mapping described in
[DeleteBranchInputRequestTypeDef](./type_defs.md#deletebranchinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `branchName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteBranchOutputTypeDef](./type_defs.md#deletebranchoutputtypedef).

<a id="delete\_comment\_content"></a>

### delete_comment_content

Deletes the content of a comment made on a change, file, or commit in a
repository.

Type annotations for
`session.create_client("codecommit").delete_comment_content` method.

Boto3 documentation:
[CodeCommit.Client.delete_comment_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.delete_comment_content)

Asynchronous method. Use `await delete_comment_content(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCommentContentInputRequestTypeDef](./type_defs.md#deletecommentcontentinputrequesttypedef).

Keyword-only arguments:

- `commentId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteCommentContentOutputTypeDef](./type_defs.md#deletecommentcontentoutputtypedef).

<a id="delete\_file"></a>

### delete_file

Deletes a specified file from a specified branch.

Type annotations for `session.create_client("codecommit").delete_file` method.

Boto3 documentation:
[CodeCommit.Client.delete_file](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.delete_file)

Asynchronous method. Use `await delete_file(...)` for a synchronous call.

Arguments mapping described in
[DeleteFileInputRequestTypeDef](./type_defs.md#deletefileinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `branchName`: `str` *(required)*
- `filePath`: `str` *(required)*
- `parentCommitId`: `str` *(required)*
- `keepEmptyFolders`: `bool`
- `commitMessage`: `str`
- `name`: `str`
- `email`: `str`

Returns a `Coroutine` for
[DeleteFileOutputTypeDef](./type_defs.md#deletefileoutputtypedef).

<a id="delete\_pull\_request\_approval\_rule"></a>

### delete_pull_request_approval_rule

Deletes an approval rule from a specified pull request.

Type annotations for
`session.create_client("codecommit").delete_pull_request_approval_rule` method.

Boto3 documentation:
[CodeCommit.Client.delete_pull_request_approval_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.delete_pull_request_approval_rule)

Asynchronous method. Use `await delete_pull_request_approval_rule(...)` for a
synchronous call.

Arguments mapping described in
[DeletePullRequestApprovalRuleInputRequestTypeDef](./type_defs.md#deletepullrequestapprovalruleinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `approvalRuleName`: `str` *(required)*

Returns a `Coroutine` for
[DeletePullRequestApprovalRuleOutputTypeDef](./type_defs.md#deletepullrequestapprovalruleoutputtypedef).

<a id="delete\_repository"></a>

### delete_repository

Deletes a repository.

Type annotations for `session.create_client("codecommit").delete_repository`
method.

Boto3 documentation:
[CodeCommit.Client.delete_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.delete_repository)

Asynchronous method. Use `await delete_repository(...)` for a synchronous call.

Arguments mapping described in
[DeleteRepositoryInputRequestTypeDef](./type_defs.md#deleterepositoryinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteRepositoryOutputTypeDef](./type_defs.md#deleterepositoryoutputtypedef).

<a id="describe\_merge\_conflicts"></a>

### describe_merge_conflicts

Returns information about one or more merge conflicts in the attempted merge of
two commit specifiers using the squash or three-way merge strategy.

Type annotations for
`session.create_client("codecommit").describe_merge_conflicts` method.

Boto3 documentation:
[CodeCommit.Client.describe_merge_conflicts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.describe_merge_conflicts)

Asynchronous method. Use `await describe_merge_conflicts(...)` for a
synchronous call.

Arguments mapping described in
[DescribeMergeConflictsInputRequestTypeDef](./type_defs.md#describemergeconflictsinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `mergeOption`:
  [MergeOptionTypeEnumType](./literals.md#mergeoptiontypeenumtype) *(required)*
- `filePath`: `str` *(required)*
- `maxMergeHunks`: `int`
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `nextToken`: `str`

Returns a `Coroutine` for
[DescribeMergeConflictsOutputTypeDef](./type_defs.md#describemergeconflictsoutputtypedef).

<a id="describe\_pull\_request\_events"></a>

### describe_pull_request_events

Returns information about one or more pull request events.

Type annotations for
`session.create_client("codecommit").describe_pull_request_events` method.

Boto3 documentation:
[CodeCommit.Client.describe_pull_request_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.describe_pull_request_events)

Asynchronous method. Use `await describe_pull_request_events(...)` for a
synchronous call.

Arguments mapping described in
[DescribePullRequestEventsInputRequestTypeDef](./type_defs.md#describepullrequesteventsinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `pullRequestEventType`:
  [PullRequestEventTypeType](./literals.md#pullrequesteventtypetype)
- `actorArn`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[DescribePullRequestEventsOutputTypeDef](./type_defs.md#describepullrequesteventsoutputtypedef).

<a id="disassociate\_approval\_rule\_template\_from\_repository"></a>

### disassociate_approval_rule_template_from_repository

Removes the association between a template and a repository so that approval
rules based on the template are not automatically created when pull requests
are created in the specified repository.

Type annotations for
`session.create_client("codecommit").disassociate_approval_rule_template_from_repository`
method.

Boto3 documentation:
[CodeCommit.Client.disassociate_approval_rule_template_from_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.disassociate_approval_rule_template_from_repository)

Asynchronous method. Use
`await disassociate_approval_rule_template_from_repository(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateApprovalRuleTemplateFromRepositoryInputRequestTypeDef](./type_defs.md#disassociateapprovalruletemplatefromrepositoryinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `repositoryName`: `str` *(required)*

<a id="evaluate\_pull\_request\_approval\_rules"></a>

### evaluate_pull_request_approval_rules

Evaluates whether a pull request has met all the conditions specified in its
associated approval rules.

Type annotations for
`session.create_client("codecommit").evaluate_pull_request_approval_rules`
method.

Boto3 documentation:
[CodeCommit.Client.evaluate_pull_request_approval_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.evaluate_pull_request_approval_rules)

Asynchronous method. Use `await evaluate_pull_request_approval_rules(...)` for
a synchronous call.

Arguments mapping described in
[EvaluatePullRequestApprovalRulesInputRequestTypeDef](./type_defs.md#evaluatepullrequestapprovalrulesinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `revisionId`: `str` *(required)*

Returns a `Coroutine` for
[EvaluatePullRequestApprovalRulesOutputTypeDef](./type_defs.md#evaluatepullrequestapprovalrulesoutputtypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("codecommit").generate_presigned_url` method.

Boto3 documentation:
[CodeCommit.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_approval\_rule\_template"></a>

### get_approval_rule_template

Returns information about a specified approval rule template.

Type annotations for
`session.create_client("codecommit").get_approval_rule_template` method.

Boto3 documentation:
[CodeCommit.Client.get_approval_rule_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_approval_rule_template)

Asynchronous method. Use `await get_approval_rule_template(...)` for a
synchronous call.

Arguments mapping described in
[GetApprovalRuleTemplateInputRequestTypeDef](./type_defs.md#getapprovalruletemplateinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*

Returns a `Coroutine` for
[GetApprovalRuleTemplateOutputTypeDef](./type_defs.md#getapprovalruletemplateoutputtypedef).

<a id="get\_blob"></a>

### get_blob

Returns the base-64 encoded content of an individual blob in a repository.

Type annotations for `session.create_client("codecommit").get_blob` method.

Boto3 documentation:
[CodeCommit.Client.get_blob](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_blob)

Asynchronous method. Use `await get_blob(...)` for a synchronous call.

Arguments mapping described in
[GetBlobInputRequestTypeDef](./type_defs.md#getblobinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `blobId`: `str` *(required)*

Returns a `Coroutine` for
[GetBlobOutputTypeDef](./type_defs.md#getbloboutputtypedef).

<a id="get\_branch"></a>

### get_branch

Returns information about a repository branch, including its name and the last
commit ID.

Type annotations for `session.create_client("codecommit").get_branch` method.

Boto3 documentation:
[CodeCommit.Client.get_branch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_branch)

Asynchronous method. Use `await get_branch(...)` for a synchronous call.

Arguments mapping described in
[GetBranchInputRequestTypeDef](./type_defs.md#getbranchinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str`
- `branchName`: `str`

Returns a `Coroutine` for
[GetBranchOutputTypeDef](./type_defs.md#getbranchoutputtypedef).

<a id="get\_comment"></a>

### get_comment

Returns the content of a comment made on a change, file, or commit in a
repository.

Type annotations for `session.create_client("codecommit").get_comment` method.

Boto3 documentation:
[CodeCommit.Client.get_comment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_comment)

Asynchronous method. Use `await get_comment(...)` for a synchronous call.

Arguments mapping described in
[GetCommentInputRequestTypeDef](./type_defs.md#getcommentinputrequesttypedef).

Keyword-only arguments:

- `commentId`: `str` *(required)*

Returns a `Coroutine` for
[GetCommentOutputTypeDef](./type_defs.md#getcommentoutputtypedef).

<a id="get\_comment\_reactions"></a>

### get_comment_reactions

Returns information about reactions to a specified comment ID.

Type annotations for
`session.create_client("codecommit").get_comment_reactions` method.

Boto3 documentation:
[CodeCommit.Client.get_comment_reactions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_comment_reactions)

Asynchronous method. Use `await get_comment_reactions(...)` for a synchronous
call.

Arguments mapping described in
[GetCommentReactionsInputRequestTypeDef](./type_defs.md#getcommentreactionsinputrequesttypedef).

Keyword-only arguments:

- `commentId`: `str` *(required)*
- `reactionUserArn`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetCommentReactionsOutputTypeDef](./type_defs.md#getcommentreactionsoutputtypedef).

<a id="get\_comments\_for\_compared\_commit"></a>

### get_comments_for_compared_commit

Returns information about comments made on the comparison between two commits.

Type annotations for
`session.create_client("codecommit").get_comments_for_compared_commit` method.

Boto3 documentation:
[CodeCommit.Client.get_comments_for_compared_commit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_comments_for_compared_commit)

Asynchronous method. Use `await get_comments_for_compared_commit(...)` for a
synchronous call.

Arguments mapping described in
[GetCommentsForComparedCommitInputRequestTypeDef](./type_defs.md#getcommentsforcomparedcommitinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `afterCommitId`: `str` *(required)*
- `beforeCommitId`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetCommentsForComparedCommitOutputTypeDef](./type_defs.md#getcommentsforcomparedcommitoutputtypedef).

<a id="get\_comments\_for\_pull\_request"></a>

### get_comments_for_pull_request

Returns comments made on a pull request.

Type annotations for
`session.create_client("codecommit").get_comments_for_pull_request` method.

Boto3 documentation:
[CodeCommit.Client.get_comments_for_pull_request](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_comments_for_pull_request)

Asynchronous method. Use `await get_comments_for_pull_request(...)` for a
synchronous call.

Arguments mapping described in
[GetCommentsForPullRequestInputRequestTypeDef](./type_defs.md#getcommentsforpullrequestinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `repositoryName`: `str`
- `beforeCommitId`: `str`
- `afterCommitId`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetCommentsForPullRequestOutputTypeDef](./type_defs.md#getcommentsforpullrequestoutputtypedef).

<a id="get\_commit"></a>

### get_commit

Returns information about a commit, including commit message and committer
information.

Type annotations for `session.create_client("codecommit").get_commit` method.

Boto3 documentation:
[CodeCommit.Client.get_commit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_commit)

Asynchronous method. Use `await get_commit(...)` for a synchronous call.

Arguments mapping described in
[GetCommitInputRequestTypeDef](./type_defs.md#getcommitinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `commitId`: `str` *(required)*

Returns a `Coroutine` for
[GetCommitOutputTypeDef](./type_defs.md#getcommitoutputtypedef).

<a id="get\_differences"></a>

### get_differences

Returns information about the differences in a valid commit specifier (such as
a branch, tag, HEAD, commit ID, or other fully qualified reference).

Type annotations for `session.create_client("codecommit").get_differences`
method.

Boto3 documentation:
[CodeCommit.Client.get_differences](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_differences)

Asynchronous method. Use `await get_differences(...)` for a synchronous call.

Arguments mapping described in
[GetDifferencesInputRequestTypeDef](./type_defs.md#getdifferencesinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `afterCommitSpecifier`: `str` *(required)*
- `beforeCommitSpecifier`: `str`
- `beforePath`: `str`
- `afterPath`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetDifferencesOutputTypeDef](./type_defs.md#getdifferencesoutputtypedef).

<a id="get\_file"></a>

### get_file

Returns the base-64 encoded contents of a specified file and its metadata.

Type annotations for `session.create_client("codecommit").get_file` method.

Boto3 documentation:
[CodeCommit.Client.get_file](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_file)

Asynchronous method. Use `await get_file(...)` for a synchronous call.

Arguments mapping described in
[GetFileInputRequestTypeDef](./type_defs.md#getfileinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `filePath`: `str` *(required)*
- `commitSpecifier`: `str`

Returns a `Coroutine` for
[GetFileOutputTypeDef](./type_defs.md#getfileoutputtypedef).

<a id="get\_folder"></a>

### get_folder

Returns the contents of a specified folder in a repository.

Type annotations for `session.create_client("codecommit").get_folder` method.

Boto3 documentation:
[CodeCommit.Client.get_folder](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_folder)

Asynchronous method. Use `await get_folder(...)` for a synchronous call.

Arguments mapping described in
[GetFolderInputRequestTypeDef](./type_defs.md#getfolderinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `folderPath`: `str` *(required)*
- `commitSpecifier`: `str`

Returns a `Coroutine` for
[GetFolderOutputTypeDef](./type_defs.md#getfolderoutputtypedef).

<a id="get\_merge\_commit"></a>

### get_merge_commit

Returns information about a specified merge commit.

Type annotations for `session.create_client("codecommit").get_merge_commit`
method.

Boto3 documentation:
[CodeCommit.Client.get_merge_commit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_merge_commit)

Asynchronous method. Use `await get_merge_commit(...)` for a synchronous call.

Arguments mapping described in
[GetMergeCommitInputRequestTypeDef](./type_defs.md#getmergecommitinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)

Returns a `Coroutine` for
[GetMergeCommitOutputTypeDef](./type_defs.md#getmergecommitoutputtypedef).

<a id="get\_merge\_conflicts"></a>

### get_merge_conflicts

Returns information about merge conflicts between the before and after commit
IDs for a pull request in a repository.

Type annotations for `session.create_client("codecommit").get_merge_conflicts`
method.

Boto3 documentation:
[CodeCommit.Client.get_merge_conflicts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_merge_conflicts)

Asynchronous method. Use `await get_merge_conflicts(...)` for a synchronous
call.

Arguments mapping described in
[GetMergeConflictsInputRequestTypeDef](./type_defs.md#getmergeconflictsinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `mergeOption`:
  [MergeOptionTypeEnumType](./literals.md#mergeoptiontypeenumtype) *(required)*
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `maxConflictFiles`: `int`
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `nextToken`: `str`

Returns a `Coroutine` for
[GetMergeConflictsOutputTypeDef](./type_defs.md#getmergeconflictsoutputtypedef).

<a id="get\_merge\_options"></a>

### get_merge_options

Returns information about the merge options available for merging two specified
branches.

Type annotations for `session.create_client("codecommit").get_merge_options`
method.

Boto3 documentation:
[CodeCommit.Client.get_merge_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_merge_options)

Asynchronous method. Use `await get_merge_options(...)` for a synchronous call.

Arguments mapping described in
[GetMergeOptionsInputRequestTypeDef](./type_defs.md#getmergeoptionsinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)

Returns a `Coroutine` for
[GetMergeOptionsOutputTypeDef](./type_defs.md#getmergeoptionsoutputtypedef).

<a id="get\_pull\_request"></a>

### get_pull_request

Gets information about a pull request in a specified repository.

Type annotations for `session.create_client("codecommit").get_pull_request`
method.

Boto3 documentation:
[CodeCommit.Client.get_pull_request](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_pull_request)

Asynchronous method. Use `await get_pull_request(...)` for a synchronous call.

Arguments mapping described in
[GetPullRequestInputRequestTypeDef](./type_defs.md#getpullrequestinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*

Returns a `Coroutine` for
[GetPullRequestOutputTypeDef](./type_defs.md#getpullrequestoutputtypedef).

<a id="get\_pull\_request\_approval\_states"></a>

### get_pull_request_approval_states

Gets information about the approval states for a specified pull request.

Type annotations for
`session.create_client("codecommit").get_pull_request_approval_states` method.

Boto3 documentation:
[CodeCommit.Client.get_pull_request_approval_states](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_pull_request_approval_states)

Asynchronous method. Use `await get_pull_request_approval_states(...)` for a
synchronous call.

Arguments mapping described in
[GetPullRequestApprovalStatesInputRequestTypeDef](./type_defs.md#getpullrequestapprovalstatesinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `revisionId`: `str` *(required)*

Returns a `Coroutine` for
[GetPullRequestApprovalStatesOutputTypeDef](./type_defs.md#getpullrequestapprovalstatesoutputtypedef).

<a id="get\_pull\_request\_override\_state"></a>

### get_pull_request_override_state

Returns information about whether approval rules have been set aside
(overridden) for a pull request, and if so, the Amazon Resource Name (ARN) of
the user or identity that overrode the rules and their requirements for the
pull request.

Type annotations for
`session.create_client("codecommit").get_pull_request_override_state` method.

Boto3 documentation:
[CodeCommit.Client.get_pull_request_override_state](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_pull_request_override_state)

Asynchronous method. Use `await get_pull_request_override_state(...)` for a
synchronous call.

Arguments mapping described in
[GetPullRequestOverrideStateInputRequestTypeDef](./type_defs.md#getpullrequestoverridestateinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `revisionId`: `str` *(required)*

Returns a `Coroutine` for
[GetPullRequestOverrideStateOutputTypeDef](./type_defs.md#getpullrequestoverridestateoutputtypedef).

<a id="get\_repository"></a>

### get_repository

Returns information about a repository.

Type annotations for `session.create_client("codecommit").get_repository`
method.

Boto3 documentation:
[CodeCommit.Client.get_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_repository)

Asynchronous method. Use `await get_repository(...)` for a synchronous call.

Arguments mapping described in
[GetRepositoryInputRequestTypeDef](./type_defs.md#getrepositoryinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*

Returns a `Coroutine` for
[GetRepositoryOutputTypeDef](./type_defs.md#getrepositoryoutputtypedef).

<a id="get\_repository\_triggers"></a>

### get_repository_triggers

Gets information about triggers configured for a repository.

Type annotations for
`session.create_client("codecommit").get_repository_triggers` method.

Boto3 documentation:
[CodeCommit.Client.get_repository_triggers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.get_repository_triggers)

Asynchronous method. Use `await get_repository_triggers(...)` for a synchronous
call.

Arguments mapping described in
[GetRepositoryTriggersInputRequestTypeDef](./type_defs.md#getrepositorytriggersinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*

Returns a `Coroutine` for
[GetRepositoryTriggersOutputTypeDef](./type_defs.md#getrepositorytriggersoutputtypedef).

<a id="list\_approval\_rule\_templates"></a>

### list_approval_rule_templates

Lists all approval rule templates in the specified AWS Region in your AWS
account.

Type annotations for
`session.create_client("codecommit").list_approval_rule_templates` method.

Boto3 documentation:
[CodeCommit.Client.list_approval_rule_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.list_approval_rule_templates)

Asynchronous method. Use `await list_approval_rule_templates(...)` for a
synchronous call.

Arguments mapping described in
[ListApprovalRuleTemplatesInputRequestTypeDef](./type_defs.md#listapprovalruletemplatesinputrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListApprovalRuleTemplatesOutputTypeDef](./type_defs.md#listapprovalruletemplatesoutputtypedef).

<a id="list\_associated\_approval\_rule\_templates\_for\_repository"></a>

### list_associated_approval_rule_templates_for_repository

Lists all approval rule templates that are associated with a specified
repository.

Type annotations for
`session.create_client("codecommit").list_associated_approval_rule_templates_for_repository`
method.

Boto3 documentation:
[CodeCommit.Client.list_associated_approval_rule_templates_for_repository](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.list_associated_approval_rule_templates_for_repository)

Asynchronous method. Use
`await list_associated_approval_rule_templates_for_repository(...)` for a
synchronous call.

Arguments mapping described in
[ListAssociatedApprovalRuleTemplatesForRepositoryInputRequestTypeDef](./type_defs.md#listassociatedapprovalruletemplatesforrepositoryinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListAssociatedApprovalRuleTemplatesForRepositoryOutputTypeDef](./type_defs.md#listassociatedapprovalruletemplatesforrepositoryoutputtypedef).

<a id="list\_branches"></a>

### list_branches

Gets information about one or more branches in a repository.

Type annotations for `session.create_client("codecommit").list_branches`
method.

Boto3 documentation:
[CodeCommit.Client.list_branches](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.list_branches)

Asynchronous method. Use `await list_branches(...)` for a synchronous call.

Arguments mapping described in
[ListBranchesInputRequestTypeDef](./type_defs.md#listbranchesinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `nextToken`: `str`

Returns a `Coroutine` for
[ListBranchesOutputTypeDef](./type_defs.md#listbranchesoutputtypedef).

<a id="list\_pull\_requests"></a>

### list_pull_requests

Returns a list of pull requests for a specified repository.

Type annotations for `session.create_client("codecommit").list_pull_requests`
method.

Boto3 documentation:
[CodeCommit.Client.list_pull_requests](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.list_pull_requests)

Asynchronous method. Use `await list_pull_requests(...)` for a synchronous
call.

Arguments mapping described in
[ListPullRequestsInputRequestTypeDef](./type_defs.md#listpullrequestsinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `authorArn`: `str`
- `pullRequestStatus`:
  [PullRequestStatusEnumType](./literals.md#pullrequeststatusenumtype)
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListPullRequestsOutputTypeDef](./type_defs.md#listpullrequestsoutputtypedef).

<a id="list\_repositories"></a>

### list_repositories

Gets information about one or more repositories.

Type annotations for `session.create_client("codecommit").list_repositories`
method.

Boto3 documentation:
[CodeCommit.Client.list_repositories](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.list_repositories)

Asynchronous method. Use `await list_repositories(...)` for a synchronous call.

Arguments mapping described in
[ListRepositoriesInputRequestTypeDef](./type_defs.md#listrepositoriesinputrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `sortBy`: [SortByEnumType](./literals.md#sortbyenumtype)
- `order`: [OrderEnumType](./literals.md#orderenumtype)

Returns a `Coroutine` for
[ListRepositoriesOutputTypeDef](./type_defs.md#listrepositoriesoutputtypedef).

<a id="list\_repositories\_for\_approval\_rule\_template"></a>

### list_repositories_for_approval_rule_template

Lists all repositories associated with the specified approval rule template.

Type annotations for
`session.create_client("codecommit").list_repositories_for_approval_rule_template`
method.

Boto3 documentation:
[CodeCommit.Client.list_repositories_for_approval_rule_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.list_repositories_for_approval_rule_template)

Asynchronous method. Use
`await list_repositories_for_approval_rule_template(...)` for a synchronous
call.

Arguments mapping described in
[ListRepositoriesForApprovalRuleTemplateInputRequestTypeDef](./type_defs.md#listrepositoriesforapprovalruletemplateinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListRepositoriesForApprovalRuleTemplateOutputTypeDef](./type_defs.md#listrepositoriesforapprovalruletemplateoutputtypedef).

<a id="list\_tags\_for\_resource"></a>

### list_tags_for_resource

Gets information about AWS tags for a specified Amazon Resource Name (ARN) in
AWS CodeCommit.

Type annotations for
`session.create_client("codecommit").list_tags_for_resource` method.

Boto3 documentation:
[CodeCommit.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `nextToken`: `str`

Returns a `Coroutine` for
[ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef).

<a id="merge\_branches\_by\_fast\_forward"></a>

### merge_branches_by_fast_forward

Merges two branches using the fast-forward merge strategy.

Type annotations for
`session.create_client("codecommit").merge_branches_by_fast_forward` method.

Boto3 documentation:
[CodeCommit.Client.merge_branches_by_fast_forward](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.merge_branches_by_fast_forward)

Asynchronous method. Use `await merge_branches_by_fast_forward(...)` for a
synchronous call.

Arguments mapping described in
[MergeBranchesByFastForwardInputRequestTypeDef](./type_defs.md#mergebranchesbyfastforwardinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `targetBranch`: `str`

Returns a `Coroutine` for
[MergeBranchesByFastForwardOutputTypeDef](./type_defs.md#mergebranchesbyfastforwardoutputtypedef).

<a id="merge\_branches\_by\_squash"></a>

### merge_branches_by_squash

Merges two branches using the squash merge strategy.

Type annotations for
`session.create_client("codecommit").merge_branches_by_squash` method.

Boto3 documentation:
[CodeCommit.Client.merge_branches_by_squash](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.merge_branches_by_squash)

Asynchronous method. Use `await merge_branches_by_squash(...)` for a
synchronous call.

Arguments mapping described in
[MergeBranchesBySquashInputRequestTypeDef](./type_defs.md#mergebranchesbysquashinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `targetBranch`: `str`
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `authorName`: `str`
- `email`: `str`
- `commitMessage`: `str`
- `keepEmptyFolders`: `bool`
- `conflictResolution`:
  [ConflictResolutionTypeDef](./type_defs.md#conflictresolutiontypedef)

Returns a `Coroutine` for
[MergeBranchesBySquashOutputTypeDef](./type_defs.md#mergebranchesbysquashoutputtypedef).

<a id="merge\_branches\_by\_three\_way"></a>

### merge_branches_by_three_way

Merges two specified branches using the three-way merge strategy.

Type annotations for
`session.create_client("codecommit").merge_branches_by_three_way` method.

Boto3 documentation:
[CodeCommit.Client.merge_branches_by_three_way](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.merge_branches_by_three_way)

Asynchronous method. Use `await merge_branches_by_three_way(...)` for a
synchronous call.

Arguments mapping described in
[MergeBranchesByThreeWayInputRequestTypeDef](./type_defs.md#mergebranchesbythreewayinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `sourceCommitSpecifier`: `str` *(required)*
- `destinationCommitSpecifier`: `str` *(required)*
- `targetBranch`: `str`
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `authorName`: `str`
- `email`: `str`
- `commitMessage`: `str`
- `keepEmptyFolders`: `bool`
- `conflictResolution`:
  [ConflictResolutionTypeDef](./type_defs.md#conflictresolutiontypedef)

Returns a `Coroutine` for
[MergeBranchesByThreeWayOutputTypeDef](./type_defs.md#mergebranchesbythreewayoutputtypedef).

<a id="merge\_pull\_request\_by\_fast\_forward"></a>

### merge_pull_request_by_fast_forward

Attempts to merge the source commit of a pull request into the specified
destination branch for that pull request at the specified commit using the
fast- forward merge strategy.

Type annotations for
`session.create_client("codecommit").merge_pull_request_by_fast_forward`
method.

Boto3 documentation:
[CodeCommit.Client.merge_pull_request_by_fast_forward](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.merge_pull_request_by_fast_forward)

Asynchronous method. Use `await merge_pull_request_by_fast_forward(...)` for a
synchronous call.

Arguments mapping described in
[MergePullRequestByFastForwardInputRequestTypeDef](./type_defs.md#mergepullrequestbyfastforwardinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `repositoryName`: `str` *(required)*
- `sourceCommitId`: `str`

Returns a `Coroutine` for
[MergePullRequestByFastForwardOutputTypeDef](./type_defs.md#mergepullrequestbyfastforwardoutputtypedef).

<a id="merge\_pull\_request\_by\_squash"></a>

### merge_pull_request_by_squash

Attempts to merge the source commit of a pull request into the specified
destination branch for that pull request at the specified commit using the
squash merge strategy.

Type annotations for
`session.create_client("codecommit").merge_pull_request_by_squash` method.

Boto3 documentation:
[CodeCommit.Client.merge_pull_request_by_squash](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.merge_pull_request_by_squash)

Asynchronous method. Use `await merge_pull_request_by_squash(...)` for a
synchronous call.

Arguments mapping described in
[MergePullRequestBySquashInputRequestTypeDef](./type_defs.md#mergepullrequestbysquashinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `repositoryName`: `str` *(required)*
- `sourceCommitId`: `str`
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `commitMessage`: `str`
- `authorName`: `str`
- `email`: `str`
- `keepEmptyFolders`: `bool`
- `conflictResolution`:
  [ConflictResolutionTypeDef](./type_defs.md#conflictresolutiontypedef)

Returns a `Coroutine` for
[MergePullRequestBySquashOutputTypeDef](./type_defs.md#mergepullrequestbysquashoutputtypedef).

<a id="merge\_pull\_request\_by\_three\_way"></a>

### merge_pull_request_by_three_way

Attempts to merge the source commit of a pull request into the specified
destination branch for that pull request at the specified commit using the
three-way merge strategy.

Type annotations for
`session.create_client("codecommit").merge_pull_request_by_three_way` method.

Boto3 documentation:
[CodeCommit.Client.merge_pull_request_by_three_way](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.merge_pull_request_by_three_way)

Asynchronous method. Use `await merge_pull_request_by_three_way(...)` for a
synchronous call.

Arguments mapping described in
[MergePullRequestByThreeWayInputRequestTypeDef](./type_defs.md#mergepullrequestbythreewayinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `repositoryName`: `str` *(required)*
- `sourceCommitId`: `str`
- `conflictDetailLevel`:
  [ConflictDetailLevelTypeEnumType](./literals.md#conflictdetailleveltypeenumtype)
- `conflictResolutionStrategy`:
  [ConflictResolutionStrategyTypeEnumType](./literals.md#conflictresolutionstrategytypeenumtype)
- `commitMessage`: `str`
- `authorName`: `str`
- `email`: `str`
- `keepEmptyFolders`: `bool`
- `conflictResolution`:
  [ConflictResolutionTypeDef](./type_defs.md#conflictresolutiontypedef)

Returns a `Coroutine` for
[MergePullRequestByThreeWayOutputTypeDef](./type_defs.md#mergepullrequestbythreewayoutputtypedef).

<a id="override\_pull\_request\_approval\_rules"></a>

### override_pull_request_approval_rules

Sets aside (overrides) all approval rule requirements for a specified pull
request.

Type annotations for
`session.create_client("codecommit").override_pull_request_approval_rules`
method.

Boto3 documentation:
[CodeCommit.Client.override_pull_request_approval_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.override_pull_request_approval_rules)

Asynchronous method. Use `await override_pull_request_approval_rules(...)` for
a synchronous call.

Arguments mapping described in
[OverridePullRequestApprovalRulesInputRequestTypeDef](./type_defs.md#overridepullrequestapprovalrulesinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `revisionId`: `str` *(required)*
- `overrideStatus`: [OverrideStatusType](./literals.md#overridestatustype)
  *(required)*

<a id="post\_comment\_for\_compared\_commit"></a>

### post_comment_for_compared_commit

Posts a comment on the comparison between two commits.

Type annotations for
`session.create_client("codecommit").post_comment_for_compared_commit` method.

Boto3 documentation:
[CodeCommit.Client.post_comment_for_compared_commit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.post_comment_for_compared_commit)

Asynchronous method. Use `await post_comment_for_compared_commit(...)` for a
synchronous call.

Arguments mapping described in
[PostCommentForComparedCommitInputRequestTypeDef](./type_defs.md#postcommentforcomparedcommitinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `afterCommitId`: `str` *(required)*
- `content`: `str` *(required)*
- `beforeCommitId`: `str`
- `location`: [LocationTypeDef](./type_defs.md#locationtypedef)
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[PostCommentForComparedCommitOutputTypeDef](./type_defs.md#postcommentforcomparedcommitoutputtypedef).

<a id="post\_comment\_for\_pull\_request"></a>

### post_comment_for_pull_request

Posts a comment on a pull request.

Type annotations for
`session.create_client("codecommit").post_comment_for_pull_request` method.

Boto3 documentation:
[CodeCommit.Client.post_comment_for_pull_request](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.post_comment_for_pull_request)

Asynchronous method. Use `await post_comment_for_pull_request(...)` for a
synchronous call.

Arguments mapping described in
[PostCommentForPullRequestInputRequestTypeDef](./type_defs.md#postcommentforpullrequestinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `repositoryName`: `str` *(required)*
- `beforeCommitId`: `str` *(required)*
- `afterCommitId`: `str` *(required)*
- `content`: `str` *(required)*
- `location`: [LocationTypeDef](./type_defs.md#locationtypedef)
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[PostCommentForPullRequestOutputTypeDef](./type_defs.md#postcommentforpullrequestoutputtypedef).

<a id="post\_comment\_reply"></a>

### post_comment_reply

Posts a comment in reply to an existing comment on a comparison between commits
or a pull request.

Type annotations for `session.create_client("codecommit").post_comment_reply`
method.

Boto3 documentation:
[CodeCommit.Client.post_comment_reply](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.post_comment_reply)

Asynchronous method. Use `await post_comment_reply(...)` for a synchronous
call.

Arguments mapping described in
[PostCommentReplyInputRequestTypeDef](./type_defs.md#postcommentreplyinputrequesttypedef).

Keyword-only arguments:

- `inReplyTo`: `str` *(required)*
- `content`: `str` *(required)*
- `clientRequestToken`: `str`

Returns a `Coroutine` for
[PostCommentReplyOutputTypeDef](./type_defs.md#postcommentreplyoutputtypedef).

<a id="put\_comment\_reaction"></a>

### put_comment_reaction

Adds or updates a reaction to a specified comment for the user whose identity
is used to make the request.

Type annotations for `session.create_client("codecommit").put_comment_reaction`
method.

Boto3 documentation:
[CodeCommit.Client.put_comment_reaction](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.put_comment_reaction)

Asynchronous method. Use `await put_comment_reaction(...)` for a synchronous
call.

Arguments mapping described in
[PutCommentReactionInputRequestTypeDef](./type_defs.md#putcommentreactioninputrequesttypedef).

Keyword-only arguments:

- `commentId`: `str` *(required)*
- `reactionValue`: `str` *(required)*

<a id="put\_file"></a>

### put_file

Adds or updates a file in a branch in an AWS CodeCommit repository, and
generates a commit for the addition in the specified branch.

Type annotations for `session.create_client("codecommit").put_file` method.

Boto3 documentation:
[CodeCommit.Client.put_file](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.put_file)

Asynchronous method. Use `await put_file(...)` for a synchronous call.

Arguments mapping described in
[PutFileInputRequestTypeDef](./type_defs.md#putfileinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `branchName`: `str` *(required)*
- `fileContent`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `filePath`: `str` *(required)*
- `fileMode`: [FileModeTypeEnumType](./literals.md#filemodetypeenumtype)
- `parentCommitId`: `str`
- `commitMessage`: `str`
- `name`: `str`
- `email`: `str`

Returns a `Coroutine` for
[PutFileOutputTypeDef](./type_defs.md#putfileoutputtypedef).

<a id="put\_repository\_triggers"></a>

### put_repository_triggers

Replaces all triggers for a repository.

Type annotations for
`session.create_client("codecommit").put_repository_triggers` method.

Boto3 documentation:
[CodeCommit.Client.put_repository_triggers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.put_repository_triggers)

Asynchronous method. Use `await put_repository_triggers(...)` for a synchronous
call.

Arguments mapping described in
[PutRepositoryTriggersInputRequestTypeDef](./type_defs.md#putrepositorytriggersinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `triggers`:
  `Sequence`\[[RepositoryTriggerTypeDef](./type_defs.md#repositorytriggertypedef)\]
  *(required)*

Returns a `Coroutine` for
[PutRepositoryTriggersOutputTypeDef](./type_defs.md#putrepositorytriggersoutputtypedef).

<a id="tag\_resource"></a>

### tag_resource

Adds or updates tags for a resource in AWS CodeCommit.

Type annotations for `session.create_client("codecommit").tag_resource` method.

Boto3 documentation:
[CodeCommit.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="test\_repository\_triggers"></a>

### test_repository_triggers

Tests the functionality of repository triggers by sending information to the
trigger target.

Type annotations for
`session.create_client("codecommit").test_repository_triggers` method.

Boto3 documentation:
[CodeCommit.Client.test_repository_triggers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.test_repository_triggers)

Asynchronous method. Use `await test_repository_triggers(...)` for a
synchronous call.

Arguments mapping described in
[TestRepositoryTriggersInputRequestTypeDef](./type_defs.md#testrepositorytriggersinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `triggers`:
  `Sequence`\[[RepositoryTriggerTypeDef](./type_defs.md#repositorytriggertypedef)\]
  *(required)*

Returns a `Coroutine` for
[TestRepositoryTriggersOutputTypeDef](./type_defs.md#testrepositorytriggersoutputtypedef).

<a id="untag\_resource"></a>

### untag_resource

Removes tags for a resource in AWS CodeCommit.

Type annotations for `session.create_client("codecommit").untag_resource`
method.

Boto3 documentation:
[CodeCommit.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

<a id="update\_approval\_rule\_template\_content"></a>

### update_approval_rule_template_content

Updates the content of an approval rule template.

Type annotations for
`session.create_client("codecommit").update_approval_rule_template_content`
method.

Boto3 documentation:
[CodeCommit.Client.update_approval_rule_template_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_approval_rule_template_content)

Asynchronous method. Use `await update_approval_rule_template_content(...)` for
a synchronous call.

Arguments mapping described in
[UpdateApprovalRuleTemplateContentInputRequestTypeDef](./type_defs.md#updateapprovalruletemplatecontentinputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `newRuleContent`: `str` *(required)*
- `existingRuleContentSha256`: `str`

Returns a `Coroutine` for
[UpdateApprovalRuleTemplateContentOutputTypeDef](./type_defs.md#updateapprovalruletemplatecontentoutputtypedef).

<a id="update\_approval\_rule\_template\_description"></a>

### update_approval_rule_template_description

Updates the description for a specified approval rule template.

Type annotations for
`session.create_client("codecommit").update_approval_rule_template_description`
method.

Boto3 documentation:
[CodeCommit.Client.update_approval_rule_template_description](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_approval_rule_template_description)

Asynchronous method. Use `await update_approval_rule_template_description(...)`
for a synchronous call.

Arguments mapping described in
[UpdateApprovalRuleTemplateDescriptionInputRequestTypeDef](./type_defs.md#updateapprovalruletemplatedescriptioninputrequesttypedef).

Keyword-only arguments:

- `approvalRuleTemplateName`: `str` *(required)*
- `approvalRuleTemplateDescription`: `str` *(required)*

Returns a `Coroutine` for
[UpdateApprovalRuleTemplateDescriptionOutputTypeDef](./type_defs.md#updateapprovalruletemplatedescriptionoutputtypedef).

<a id="update\_approval\_rule\_template\_name"></a>

### update_approval_rule_template_name

Updates the name of a specified approval rule template.

Type annotations for
`session.create_client("codecommit").update_approval_rule_template_name`
method.

Boto3 documentation:
[CodeCommit.Client.update_approval_rule_template_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_approval_rule_template_name)

Asynchronous method. Use `await update_approval_rule_template_name(...)` for a
synchronous call.

Arguments mapping described in
[UpdateApprovalRuleTemplateNameInputRequestTypeDef](./type_defs.md#updateapprovalruletemplatenameinputrequesttypedef).

Keyword-only arguments:

- `oldApprovalRuleTemplateName`: `str` *(required)*
- `newApprovalRuleTemplateName`: `str` *(required)*

Returns a `Coroutine` for
[UpdateApprovalRuleTemplateNameOutputTypeDef](./type_defs.md#updateapprovalruletemplatenameoutputtypedef).

<a id="update\_comment"></a>

### update_comment

Replaces the contents of a comment.

Type annotations for `session.create_client("codecommit").update_comment`
method.

Boto3 documentation:
[CodeCommit.Client.update_comment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_comment)

Asynchronous method. Use `await update_comment(...)` for a synchronous call.

Arguments mapping described in
[UpdateCommentInputRequestTypeDef](./type_defs.md#updatecommentinputrequesttypedef).

Keyword-only arguments:

- `commentId`: `str` *(required)*
- `content`: `str` *(required)*

Returns a `Coroutine` for
[UpdateCommentOutputTypeDef](./type_defs.md#updatecommentoutputtypedef).

<a id="update\_default\_branch"></a>

### update_default_branch

Sets or changes the default branch name for the specified repository.

Type annotations for
`session.create_client("codecommit").update_default_branch` method.

Boto3 documentation:
[CodeCommit.Client.update_default_branch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_default_branch)

Asynchronous method. Use `await update_default_branch(...)` for a synchronous
call.

Arguments mapping described in
[UpdateDefaultBranchInputRequestTypeDef](./type_defs.md#updatedefaultbranchinputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `defaultBranchName`: `str` *(required)*

<a id="update\_pull\_request\_approval\_rule\_content"></a>

### update_pull_request_approval_rule_content

Updates the structure of an approval rule created specifically for a pull
request.

Type annotations for
`session.create_client("codecommit").update_pull_request_approval_rule_content`
method.

Boto3 documentation:
[CodeCommit.Client.update_pull_request_approval_rule_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_pull_request_approval_rule_content)

Asynchronous method. Use `await update_pull_request_approval_rule_content(...)`
for a synchronous call.

Arguments mapping described in
[UpdatePullRequestApprovalRuleContentInputRequestTypeDef](./type_defs.md#updatepullrequestapprovalrulecontentinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `approvalRuleName`: `str` *(required)*
- `newRuleContent`: `str` *(required)*
- `existingRuleContentSha256`: `str`

Returns a `Coroutine` for
[UpdatePullRequestApprovalRuleContentOutputTypeDef](./type_defs.md#updatepullrequestapprovalrulecontentoutputtypedef).

<a id="update\_pull\_request\_approval\_state"></a>

### update_pull_request_approval_state

Updates the state of a user's approval on a pull request.

Type annotations for
`session.create_client("codecommit").update_pull_request_approval_state`
method.

Boto3 documentation:
[CodeCommit.Client.update_pull_request_approval_state](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_pull_request_approval_state)

Asynchronous method. Use `await update_pull_request_approval_state(...)` for a
synchronous call.

Arguments mapping described in
[UpdatePullRequestApprovalStateInputRequestTypeDef](./type_defs.md#updatepullrequestapprovalstateinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `revisionId`: `str` *(required)*
- `approvalState`: [ApprovalStateType](./literals.md#approvalstatetype)
  *(required)*

<a id="update\_pull\_request\_description"></a>

### update_pull_request_description

Replaces the contents of the description of a pull request.

Type annotations for
`session.create_client("codecommit").update_pull_request_description` method.

Boto3 documentation:
[CodeCommit.Client.update_pull_request_description](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_pull_request_description)

Asynchronous method. Use `await update_pull_request_description(...)` for a
synchronous call.

Arguments mapping described in
[UpdatePullRequestDescriptionInputRequestTypeDef](./type_defs.md#updatepullrequestdescriptioninputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `description`: `str` *(required)*

Returns a `Coroutine` for
[UpdatePullRequestDescriptionOutputTypeDef](./type_defs.md#updatepullrequestdescriptionoutputtypedef).

<a id="update\_pull\_request\_status"></a>

### update_pull_request_status

Updates the status of a pull request.

Type annotations for
`session.create_client("codecommit").update_pull_request_status` method.

Boto3 documentation:
[CodeCommit.Client.update_pull_request_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_pull_request_status)

Asynchronous method. Use `await update_pull_request_status(...)` for a
synchronous call.

Arguments mapping described in
[UpdatePullRequestStatusInputRequestTypeDef](./type_defs.md#updatepullrequeststatusinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `pullRequestStatus`:
  [PullRequestStatusEnumType](./literals.md#pullrequeststatusenumtype)
  *(required)*

Returns a `Coroutine` for
[UpdatePullRequestStatusOutputTypeDef](./type_defs.md#updatepullrequeststatusoutputtypedef).

<a id="update\_pull\_request\_title"></a>

### update_pull_request_title

Replaces the title of a pull request.

Type annotations for
`session.create_client("codecommit").update_pull_request_title` method.

Boto3 documentation:
[CodeCommit.Client.update_pull_request_title](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_pull_request_title)

Asynchronous method. Use `await update_pull_request_title(...)` for a
synchronous call.

Arguments mapping described in
[UpdatePullRequestTitleInputRequestTypeDef](./type_defs.md#updatepullrequesttitleinputrequesttypedef).

Keyword-only arguments:

- `pullRequestId`: `str` *(required)*
- `title`: `str` *(required)*

Returns a `Coroutine` for
[UpdatePullRequestTitleOutputTypeDef](./type_defs.md#updatepullrequesttitleoutputtypedef).

<a id="update\_repository\_description"></a>

### update_repository_description

Sets or changes the comment or description for a repository.

Type annotations for
`session.create_client("codecommit").update_repository_description` method.

Boto3 documentation:
[CodeCommit.Client.update_repository_description](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_repository_description)

Asynchronous method. Use `await update_repository_description(...)` for a
synchronous call.

Arguments mapping described in
[UpdateRepositoryDescriptionInputRequestTypeDef](./type_defs.md#updaterepositorydescriptioninputrequesttypedef).

Keyword-only arguments:

- `repositoryName`: `str` *(required)*
- `repositoryDescription`: `str`

<a id="update\_repository\_name"></a>

### update_repository_name

Renames a repository.

Type annotations for
`session.create_client("codecommit").update_repository_name` method.

Boto3 documentation:
[CodeCommit.Client.update_repository_name](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.update_repository_name)

Asynchronous method. Use `await update_repository_name(...)` for a synchronous
call.

Arguments mapping described in
[UpdateRepositoryNameInputRequestTypeDef](./type_defs.md#updaterepositorynameinputrequesttypedef).

Keyword-only arguments:

- `oldName`: `str` *(required)*
- `newName`: `str` *(required)*

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("codecommit").__aenter__` method.

Boto3 documentation:
[CodeCommit.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [CodeCommitClient](#codecommitclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("codecommit").__aexit__` method.

Boto3 documentation:
[CodeCommit.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecommit.html#CodeCommit.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("codecommit").get_paginator` method
with overloads.

- `client.get_paginator("describe_pull_request_events")` ->
  [DescribePullRequestEventsPaginator](./paginators.md#describepullrequesteventspaginator)
- `client.get_paginator("get_comments_for_compared_commit")` ->
  [GetCommentsForComparedCommitPaginator](./paginators.md#getcommentsforcomparedcommitpaginator)
- `client.get_paginator("get_comments_for_pull_request")` ->
  [GetCommentsForPullRequestPaginator](./paginators.md#getcommentsforpullrequestpaginator)
- `client.get_paginator("get_differences")` ->
  [GetDifferencesPaginator](./paginators.md#getdifferencespaginator)
- `client.get_paginator("list_branches")` ->
  [ListBranchesPaginator](./paginators.md#listbranchespaginator)
- `client.get_paginator("list_pull_requests")` ->
  [ListPullRequestsPaginator](./paginators.md#listpullrequestspaginator)
- `client.get_paginator("list_repositories")` ->
  [ListRepositoriesPaginator](./paginators.md#listrepositoriespaginator)
