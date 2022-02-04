<a id="accessanalyzerclient-for-aiobotocore-accessanalyzer-module"></a>

# AccessAnalyzerClient for aiobotocore AccessAnalyzer module

> [Index](..) > [AccessAnalyzer](.) > AccessAnalyzerClient

Auto-generated documentation for
[AccessAnalyzer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer)
type annotations stubs module
[types-aiobotocore-accessanalyzer](https://pypi.org/project/types-aiobotocore-accessanalyzer/).

- [AccessAnalyzerClient for aiobotocore AccessAnalyzer module](#accessanalyzerclient-for-aiobotocore-accessanalyzer-module)
  - [AccessAnalyzerClient](#accessanalyzerclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [apply_archive_rule](#apply_archive_rule)
    - [can_paginate](#can_paginate)
    - [cancel_policy_generation](#cancel_policy_generation)
    - [create_access_preview](#create_access_preview)
    - [create_analyzer](#create_analyzer)
    - [create_archive_rule](#create_archive_rule)
    - [delete_analyzer](#delete_analyzer)
    - [delete_archive_rule](#delete_archive_rule)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_access_preview](#get_access_preview)
    - [get_analyzed_resource](#get_analyzed_resource)
    - [get_analyzer](#get_analyzer)
    - [get_archive_rule](#get_archive_rule)
    - [get_finding](#get_finding)
    - [get_generated_policy](#get_generated_policy)
    - [list_access_preview_findings](#list_access_preview_findings)
    - [list_access_previews](#list_access_previews)
    - [list_analyzed_resources](#list_analyzed_resources)
    - [list_analyzers](#list_analyzers)
    - [list_archive_rules](#list_archive_rules)
    - [list_findings](#list_findings)
    - [list_policy_generations](#list_policy_generations)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [start_policy_generation](#start_policy_generation)
    - [start_resource_scan](#start_resource_scan)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_archive_rule](#update_archive_rule)
    - [update_findings](#update_findings)
    - [validate_policy](#validate_policy)
    - [get_paginator](#get_paginator)

<a id="accessanalyzerclient"></a>

## AccessAnalyzerClient

Type annotations for `aiobotocore.create_client("accessanalyzer")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_accessanalyzer.client import AccessAnalyzerClient

def get_accessanalyzer_client() -> AccessAnalyzerClient:
    return Session().client("accessanalyzer")
```

Boto3 documentation:
[AccessAnalyzer.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_accessanalyzer.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

AccessAnalyzerClient exceptions.

Type annotations for `aiobotocore.create_client("accessanalyzer").exceptions`
method.

Boto3 documentation:
[AccessAnalyzer.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="apply_archive_rule"></a>

### apply_archive_rule

Retroactively applies the archive rule to existing findings that meet the
archive rule criteria.

Type annotations for
`aiobotocore.create_client("accessanalyzer").apply_archive_rule` method.

Boto3 documentation:
[AccessAnalyzer.Client.apply_archive_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.apply_archive_rule)

Asynchronous method. Use `await apply_archive_rule(...)` for a synchronous
call.

Arguments mapping described in
[ApplyArchiveRuleRequestRequestTypeDef](./type_defs.md#applyarchiverulerequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `ruleName`: `str` *(required)*
- `clientToken`: `str`

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("accessanalyzer").can_paginate`
method.

Boto3 documentation:
[AccessAnalyzer.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_policy_generation"></a>

### cancel_policy_generation

Cancels the requested policy generation.

Type annotations for
`aiobotocore.create_client("accessanalyzer").cancel_policy_generation` method.

Boto3 documentation:
[AccessAnalyzer.Client.cancel_policy_generation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.cancel_policy_generation)

Asynchronous method. Use `await cancel_policy_generation(...)` for a
synchronous call.

Arguments mapping described in
[CancelPolicyGenerationRequestRequestTypeDef](./type_defs.md#cancelpolicygenerationrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_access_preview"></a>

### create_access_preview

Creates an access preview that allows you to preview IAM Access Analyzer
findings for your resource before deploying resource permissions.

Type annotations for
`aiobotocore.create_client("accessanalyzer").create_access_preview` method.

Boto3 documentation:
[AccessAnalyzer.Client.create_access_preview](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.create_access_preview)

Asynchronous method. Use `await create_access_preview(...)` for a synchronous
call.

Arguments mapping described in
[CreateAccessPreviewRequestRequestTypeDef](./type_defs.md#createaccesspreviewrequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `configurations`: `Mapping`\[`str`,
  [ConfigurationTypeDef](./type_defs.md#configurationtypedef)\] *(required)*
- `clientToken`: `str`

Returns a `Coroutine` for
[CreateAccessPreviewResponseTypeDef](./type_defs.md#createaccesspreviewresponsetypedef).

<a id="create_analyzer"></a>

### create_analyzer

Creates an analyzer for your account.

Type annotations for
`aiobotocore.create_client("accessanalyzer").create_analyzer` method.

Boto3 documentation:
[AccessAnalyzer.Client.create_analyzer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.create_analyzer)

Asynchronous method. Use `await create_analyzer(...)` for a synchronous call.

Arguments mapping described in
[CreateAnalyzerRequestRequestTypeDef](./type_defs.md#createanalyzerrequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*
- `type`: [TypeType](./literals.md#typetype) *(required)*
- `archiveRules`:
  `Sequence`\[[InlineArchiveRuleTypeDef](./type_defs.md#inlinearchiveruletypedef)\]
- `clientToken`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateAnalyzerResponseTypeDef](./type_defs.md#createanalyzerresponsetypedef).

<a id="create_archive_rule"></a>

### create_archive_rule

Creates an archive rule for the specified analyzer.

Type annotations for
`aiobotocore.create_client("accessanalyzer").create_archive_rule` method.

Boto3 documentation:
[AccessAnalyzer.Client.create_archive_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.create_archive_rule)

Asynchronous method. Use `await create_archive_rule(...)` for a synchronous
call.

Arguments mapping described in
[CreateArchiveRuleRequestRequestTypeDef](./type_defs.md#createarchiverulerequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*
- `filter`: `Mapping`\[`str`,
  [CriterionTypeDef](./type_defs.md#criteriontypedef)\] *(required)*
- `ruleName`: `str` *(required)*
- `clientToken`: `str`

<a id="delete_analyzer"></a>

### delete_analyzer

Deletes the specified analyzer.

Type annotations for
`aiobotocore.create_client("accessanalyzer").delete_analyzer` method.

Boto3 documentation:
[AccessAnalyzer.Client.delete_analyzer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.delete_analyzer)

Asynchronous method. Use `await delete_analyzer(...)` for a synchronous call.

Arguments mapping described in
[DeleteAnalyzerRequestRequestTypeDef](./type_defs.md#deleteanalyzerrequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*
- `clientToken`: `str`

<a id="delete_archive_rule"></a>

### delete_archive_rule

Deletes the specified archive rule.

Type annotations for
`aiobotocore.create_client("accessanalyzer").delete_archive_rule` method.

Boto3 documentation:
[AccessAnalyzer.Client.delete_archive_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.delete_archive_rule)

Asynchronous method. Use `await delete_archive_rule(...)` for a synchronous
call.

Arguments mapping described in
[DeleteArchiveRuleRequestRequestTypeDef](./type_defs.md#deletearchiverulerequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*
- `ruleName`: `str` *(required)*
- `clientToken`: `str`

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("accessanalyzer").generate_presigned_url` method.

Boto3 documentation:
[AccessAnalyzer.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_access_preview"></a>

### get_access_preview

Retrieves information about an access preview for the specified analyzer.

Type annotations for
`aiobotocore.create_client("accessanalyzer").get_access_preview` method.

Boto3 documentation:
[AccessAnalyzer.Client.get_access_preview](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_access_preview)

Asynchronous method. Use `await get_access_preview(...)` for a synchronous
call.

Arguments mapping described in
[GetAccessPreviewRequestRequestTypeDef](./type_defs.md#getaccesspreviewrequestrequesttypedef).

Keyword-only arguments:

- `accessPreviewId`: `str` *(required)*
- `analyzerArn`: `str` *(required)*

Returns a `Coroutine` for
[GetAccessPreviewResponseTypeDef](./type_defs.md#getaccesspreviewresponsetypedef).

<a id="get_analyzed_resource"></a>

### get_analyzed_resource

Retrieves information about a resource that was analyzed.

Type annotations for
`aiobotocore.create_client("accessanalyzer").get_analyzed_resource` method.

Boto3 documentation:
[AccessAnalyzer.Client.get_analyzed_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_analyzed_resource)

Asynchronous method. Use `await get_analyzed_resource(...)` for a synchronous
call.

Arguments mapping described in
[GetAnalyzedResourceRequestRequestTypeDef](./type_defs.md#getanalyzedresourcerequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[GetAnalyzedResourceResponseTypeDef](./type_defs.md#getanalyzedresourceresponsetypedef).

<a id="get_analyzer"></a>

### get_analyzer

Retrieves information about the specified analyzer.

Type annotations for `aiobotocore.create_client("accessanalyzer").get_analyzer`
method.

Boto3 documentation:
[AccessAnalyzer.Client.get_analyzer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_analyzer)

Asynchronous method. Use `await get_analyzer(...)` for a synchronous call.

Arguments mapping described in
[GetAnalyzerRequestRequestTypeDef](./type_defs.md#getanalyzerrequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*

Returns a `Coroutine` for
[GetAnalyzerResponseTypeDef](./type_defs.md#getanalyzerresponsetypedef).

<a id="get_archive_rule"></a>

### get_archive_rule

Retrieves information about an archive rule.

Type annotations for
`aiobotocore.create_client("accessanalyzer").get_archive_rule` method.

Boto3 documentation:
[AccessAnalyzer.Client.get_archive_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_archive_rule)

Asynchronous method. Use `await get_archive_rule(...)` for a synchronous call.

Arguments mapping described in
[GetArchiveRuleRequestRequestTypeDef](./type_defs.md#getarchiverulerequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*
- `ruleName`: `str` *(required)*

Returns a `Coroutine` for
[GetArchiveRuleResponseTypeDef](./type_defs.md#getarchiveruleresponsetypedef).

<a id="get_finding"></a>

### get_finding

Retrieves information about the specified finding.

Type annotations for `aiobotocore.create_client("accessanalyzer").get_finding`
method.

Boto3 documentation:
[AccessAnalyzer.Client.get_finding](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_finding)

Asynchronous method. Use `await get_finding(...)` for a synchronous call.

Arguments mapping described in
[GetFindingRequestRequestTypeDef](./type_defs.md#getfindingrequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetFindingResponseTypeDef](./type_defs.md#getfindingresponsetypedef).

<a id="get_generated_policy"></a>

### get_generated_policy

Retrieves the policy that was generated using `StartPolicyGeneration` .

Type annotations for
`aiobotocore.create_client("accessanalyzer").get_generated_policy` method.

Boto3 documentation:
[AccessAnalyzer.Client.get_generated_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_generated_policy)

Asynchronous method. Use `await get_generated_policy(...)` for a synchronous
call.

Arguments mapping described in
[GetGeneratedPolicyRequestRequestTypeDef](./type_defs.md#getgeneratedpolicyrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `includeResourcePlaceholders`: `bool`
- `includeServiceLevelTemplate`: `bool`

Returns a `Coroutine` for
[GetGeneratedPolicyResponseTypeDef](./type_defs.md#getgeneratedpolicyresponsetypedef).

<a id="list_access_preview_findings"></a>

### list_access_preview_findings

Retrieves a list of access preview findings generated by the specified access
preview.

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_access_preview_findings`
method.

Boto3 documentation:
[AccessAnalyzer.Client.list_access_preview_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_access_preview_findings)

Asynchronous method. Use `await list_access_preview_findings(...)` for a
synchronous call.

Arguments mapping described in
[ListAccessPreviewFindingsRequestRequestTypeDef](./type_defs.md#listaccesspreviewfindingsrequestrequesttypedef).

Keyword-only arguments:

- `accessPreviewId`: `str` *(required)*
- `analyzerArn`: `str` *(required)*
- `filter`: `Mapping`\[`str`,
  [CriterionTypeDef](./type_defs.md#criteriontypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListAccessPreviewFindingsResponseTypeDef](./type_defs.md#listaccesspreviewfindingsresponsetypedef).

<a id="list_access_previews"></a>

### list_access_previews

Retrieves a list of access previews for the specified analyzer.

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_access_previews` method.

Boto3 documentation:
[AccessAnalyzer.Client.list_access_previews](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_access_previews)

Asynchronous method. Use `await list_access_previews(...)` for a synchronous
call.

Arguments mapping described in
[ListAccessPreviewsRequestRequestTypeDef](./type_defs.md#listaccesspreviewsrequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListAccessPreviewsResponseTypeDef](./type_defs.md#listaccesspreviewsresponsetypedef).

<a id="list_analyzed_resources"></a>

### list_analyzed_resources

Retrieves a list of resources of the specified type that have been analyzed by
the specified analyzer..

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_analyzed_resources` method.

Boto3 documentation:
[AccessAnalyzer.Client.list_analyzed_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_analyzed_resources)

Asynchronous method. Use `await list_analyzed_resources(...)` for a synchronous
call.

Arguments mapping described in
[ListAnalyzedResourcesRequestRequestTypeDef](./type_defs.md#listanalyzedresourcesrequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`
- `resourceType`: [ResourceTypeType](./literals.md#resourcetypetype)

Returns a `Coroutine` for
[ListAnalyzedResourcesResponseTypeDef](./type_defs.md#listanalyzedresourcesresponsetypedef).

<a id="list_analyzers"></a>

### list_analyzers

Retrieves a list of analyzers.

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_analyzers` method.

Boto3 documentation:
[AccessAnalyzer.Client.list_analyzers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_analyzers)

Asynchronous method. Use `await list_analyzers(...)` for a synchronous call.

Arguments mapping described in
[ListAnalyzersRequestRequestTypeDef](./type_defs.md#listanalyzersrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`
- `type`: [TypeType](./literals.md#typetype)

Returns a `Coroutine` for
[ListAnalyzersResponseTypeDef](./type_defs.md#listanalyzersresponsetypedef).

<a id="list_archive_rules"></a>

### list_archive_rules

Retrieves a list of archive rules created for the specified analyzer.

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_archive_rules` method.

Boto3 documentation:
[AccessAnalyzer.Client.list_archive_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_archive_rules)

Asynchronous method. Use `await list_archive_rules(...)` for a synchronous
call.

Arguments mapping described in
[ListArchiveRulesRequestRequestTypeDef](./type_defs.md#listarchiverulesrequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListArchiveRulesResponseTypeDef](./type_defs.md#listarchiverulesresponsetypedef).

<a id="list_findings"></a>

### list_findings

Retrieves a list of findings generated by the specified analyzer.

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_findings` method.

Boto3 documentation:
[AccessAnalyzer.Client.list_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_findings)

Asynchronous method. Use `await list_findings(...)` for a synchronous call.

Arguments mapping described in
[ListFindingsRequestRequestTypeDef](./type_defs.md#listfindingsrequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `filter`: `Mapping`\[`str`,
  [CriterionTypeDef](./type_defs.md#criteriontypedef)\]
- `maxResults`: `int`
- `nextToken`: `str`
- `sort`: [SortCriteriaTypeDef](./type_defs.md#sortcriteriatypedef)

Returns a `Coroutine` for
[ListFindingsResponseTypeDef](./type_defs.md#listfindingsresponsetypedef).

<a id="list_policy_generations"></a>

### list_policy_generations

Lists all of the policy generations requested in the last seven days.

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_policy_generations` method.

Boto3 documentation:
[AccessAnalyzer.Client.list_policy_generations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_policy_generations)

Asynchronous method. Use `await list_policy_generations(...)` for a synchronous
call.

Arguments mapping described in
[ListPolicyGenerationsRequestRequestTypeDef](./type_defs.md#listpolicygenerationsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`
- `principalArn`: `str`

Returns a `Coroutine` for
[ListPolicyGenerationsResponseTypeDef](./type_defs.md#listpolicygenerationsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Retrieves a list of tags applied to the specified resource.

Type annotations for
`aiobotocore.create_client("accessanalyzer").list_tags_for_resource` method.

Boto3 documentation:
[AccessAnalyzer.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="start_policy_generation"></a>

### start_policy_generation

Starts the policy generation request.

Type annotations for
`aiobotocore.create_client("accessanalyzer").start_policy_generation` method.

Boto3 documentation:
[AccessAnalyzer.Client.start_policy_generation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.start_policy_generation)

Asynchronous method. Use `await start_policy_generation(...)` for a synchronous
call.

Arguments mapping described in
[StartPolicyGenerationRequestRequestTypeDef](./type_defs.md#startpolicygenerationrequestrequesttypedef).

Keyword-only arguments:

- `policyGenerationDetails`:
  [PolicyGenerationDetailsTypeDef](./type_defs.md#policygenerationdetailstypedef)
  *(required)*
- `clientToken`: `str`
- `cloudTrailDetails`:
  [CloudTrailDetailsTypeDef](./type_defs.md#cloudtraildetailstypedef)

Returns a `Coroutine` for
[StartPolicyGenerationResponseTypeDef](./type_defs.md#startpolicygenerationresponsetypedef).

<a id="start_resource_scan"></a>

### start_resource_scan

Immediately starts a scan of the policies applied to the specified resource.

Type annotations for
`aiobotocore.create_client("accessanalyzer").start_resource_scan` method.

Boto3 documentation:
[AccessAnalyzer.Client.start_resource_scan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.start_resource_scan)

Asynchronous method. Use `await start_resource_scan(...)` for a synchronous
call.

Arguments mapping described in
[StartResourceScanRequestRequestTypeDef](./type_defs.md#startresourcescanrequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `resourceArn`: `str` *(required)*

<a id="tag_resource"></a>

### tag_resource

Adds a tag to the specified resource.

Type annotations for `aiobotocore.create_client("accessanalyzer").tag_resource`
method.

Boto3 documentation:
[AccessAnalyzer.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes a tag from the specified resource.

Type annotations for
`aiobotocore.create_client("accessanalyzer").untag_resource` method.

Boto3 documentation:
[AccessAnalyzer.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_archive_rule"></a>

### update_archive_rule

Updates the criteria and values for the specified archive rule.

Type annotations for
`aiobotocore.create_client("accessanalyzer").update_archive_rule` method.

Boto3 documentation:
[AccessAnalyzer.Client.update_archive_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.update_archive_rule)

Asynchronous method. Use `await update_archive_rule(...)` for a synchronous
call.

Arguments mapping described in
[UpdateArchiveRuleRequestRequestTypeDef](./type_defs.md#updatearchiverulerequestrequesttypedef).

Keyword-only arguments:

- `analyzerName`: `str` *(required)*
- `filter`: `Mapping`\[`str`,
  [CriterionTypeDef](./type_defs.md#criteriontypedef)\] *(required)*
- `ruleName`: `str` *(required)*
- `clientToken`: `str`

<a id="update_findings"></a>

### update_findings

Updates the status for the specified findings.

Type annotations for
`aiobotocore.create_client("accessanalyzer").update_findings` method.

Boto3 documentation:
[AccessAnalyzer.Client.update_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.update_findings)

Asynchronous method. Use `await update_findings(...)` for a synchronous call.

Arguments mapping described in
[UpdateFindingsRequestRequestTypeDef](./type_defs.md#updatefindingsrequestrequesttypedef).

Keyword-only arguments:

- `analyzerArn`: `str` *(required)*
- `status`: [FindingStatusUpdateType](./literals.md#findingstatusupdatetype)
  *(required)*
- `clientToken`: `str`
- `ids`: `Sequence`\[`str`\]
- `resourceArn`: `str`

<a id="validate_policy"></a>

### validate_policy

Requests the validation of a policy and returns a list of findings.

Type annotations for
`aiobotocore.create_client("accessanalyzer").validate_policy` method.

Boto3 documentation:
[AccessAnalyzer.Client.validate_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.validate_policy)

Asynchronous method. Use `await validate_policy(...)` for a synchronous call.

Arguments mapping described in
[ValidatePolicyRequestRequestTypeDef](./type_defs.md#validatepolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyDocument`: `str` *(required)*
- `policyType`: [PolicyTypeType](./literals.md#policytypetype) *(required)*
- `locale`: [LocaleType](./literals.md#localetype)
- `maxResults`: `int`
- `nextToken`: `str`
- `validatePolicyResourceType`:
  [ValidatePolicyResourceTypeType](./literals.md#validatepolicyresourcetypetype)

Returns a `Coroutine` for
[ValidatePolicyResponseTypeDef](./type_defs.md#validatepolicyresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("accessanalyzer").get_paginator` method with
overloads.

- `client.get_paginator("list_access_preview_findings")` ->
  [ListAccessPreviewFindingsPaginator](./paginators.md#listaccesspreviewfindingspaginator)
- `client.get_paginator("list_access_previews")` ->
  [ListAccessPreviewsPaginator](./paginators.md#listaccesspreviewspaginator)
- `client.get_paginator("list_analyzed_resources")` ->
  [ListAnalyzedResourcesPaginator](./paginators.md#listanalyzedresourcespaginator)
- `client.get_paginator("list_analyzers")` ->
  [ListAnalyzersPaginator](./paginators.md#listanalyzerspaginator)
- `client.get_paginator("list_archive_rules")` ->
  [ListArchiveRulesPaginator](./paginators.md#listarchiverulespaginator)
- `client.get_paginator("list_findings")` ->
  [ListFindingsPaginator](./paginators.md#listfindingspaginator)
- `client.get_paginator("list_policy_generations")` ->
  [ListPolicyGenerationsPaginator](./paginators.md#listpolicygenerationspaginator)
- `client.get_paginator("validate_policy")` ->
  [ValidatePolicyPaginator](./paginators.md#validatepolicypaginator)
