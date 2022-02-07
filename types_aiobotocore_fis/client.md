<a id="fisclient-for-aiobotocore-fis-module"></a>

# FISClient for aiobotocore FIS module

> [Index](..) > [FIS](.) > FISClient

Auto-generated documentation for
[FIS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
type annotations stubs module
[types-aiobotocore-fis](https://pypi.org/project/types-aiobotocore-fis/).

- [FISClient for aiobotocore FIS module](#fisclient-for-aiobotocore-fis-module)
  - [FISClient](#fisclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_experiment_template](#create_experiment_template)
    - [delete_experiment_template](#delete_experiment_template)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_action](#get_action)
    - [get_experiment](#get_experiment)
    - [get_experiment_template](#get_experiment_template)
    - [list_actions](#list_actions)
    - [list_experiment_templates](#list_experiment_templates)
    - [list_experiments](#list_experiments)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [start_experiment](#start_experiment)
    - [stop_experiment](#stop_experiment)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_experiment_template](#update_experiment_template)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)

<a id="fisclient"></a>

## FISClient

Type annotations for `session.create_client("fis")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_fis.client import FISClient

session = get_session()
async with session.create_client("fis") as client:
    client: FISClient
```

Boto3 documentation:
[FIS.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_fis.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceQuotaExceededException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

FISClient exceptions.

Type annotations for `session.create_client("fis").exceptions` method.

Boto3 documentation:
[FIS.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("fis").can_paginate` method.

Boto3 documentation:
[FIS.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_experiment_template"></a>

### create_experiment_template

Creates an experiment template.

Type annotations for `session.create_client("fis").create_experiment_template`
method.

Boto3 documentation:
[FIS.Client.create_experiment_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.create_experiment_template)

Asynchronous method. Use `await create_experiment_template(...)` for a
synchronous call.

Arguments mapping described in
[CreateExperimentTemplateRequestRequestTypeDef](./type_defs.md#createexperimenttemplaterequestrequesttypedef).

Keyword-only arguments:

- `clientToken`: `str` *(required)*
- `description`: `str` *(required)*
- `stopConditions`:
  `Sequence`\[[CreateExperimentTemplateStopConditionInputTypeDef](./type_defs.md#createexperimenttemplatestopconditioninputtypedef)\]
  *(required)*
- `actions`: `Mapping`\[`str`,
  [CreateExperimentTemplateActionInputTypeDef](./type_defs.md#createexperimenttemplateactioninputtypedef)\]
  *(required)*
- `roleArn`: `str` *(required)*
- `targets`: `Mapping`\[`str`,
  [CreateExperimentTemplateTargetInputTypeDef](./type_defs.md#createexperimenttemplatetargetinputtypedef)\]
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateExperimentTemplateResponseTypeDef](./type_defs.md#createexperimenttemplateresponsetypedef).

<a id="delete_experiment_template"></a>

### delete_experiment_template

Deletes the specified experiment template.

Type annotations for `session.create_client("fis").delete_experiment_template`
method.

Boto3 documentation:
[FIS.Client.delete_experiment_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.delete_experiment_template)

Asynchronous method. Use `await delete_experiment_template(...)` for a
synchronous call.

Arguments mapping described in
[DeleteExperimentTemplateRequestRequestTypeDef](./type_defs.md#deleteexperimenttemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[DeleteExperimentTemplateResponseTypeDef](./type_defs.md#deleteexperimenttemplateresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("fis").generate_presigned_url`
method.

Boto3 documentation:
[FIS.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_action"></a>

### get_action

Gets information about the specified AWS FIS action.

Type annotations for `session.create_client("fis").get_action` method.

Boto3 documentation:
[FIS.Client.get_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.get_action)

Asynchronous method. Use `await get_action(...)` for a synchronous call.

Arguments mapping described in
[GetActionRequestRequestTypeDef](./type_defs.md#getactionrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetActionResponseTypeDef](./type_defs.md#getactionresponsetypedef).

<a id="get_experiment"></a>

### get_experiment

Gets information about the specified experiment.

Type annotations for `session.create_client("fis").get_experiment` method.

Boto3 documentation:
[FIS.Client.get_experiment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.get_experiment)

Asynchronous method. Use `await get_experiment(...)` for a synchronous call.

Arguments mapping described in
[GetExperimentRequestRequestTypeDef](./type_defs.md#getexperimentrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetExperimentResponseTypeDef](./type_defs.md#getexperimentresponsetypedef).

<a id="get_experiment_template"></a>

### get_experiment_template

Gets information about the specified experiment template.

Type annotations for `session.create_client("fis").get_experiment_template`
method.

Boto3 documentation:
[FIS.Client.get_experiment_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.get_experiment_template)

Asynchronous method. Use `await get_experiment_template(...)` for a synchronous
call.

Arguments mapping described in
[GetExperimentTemplateRequestRequestTypeDef](./type_defs.md#getexperimenttemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[GetExperimentTemplateResponseTypeDef](./type_defs.md#getexperimenttemplateresponsetypedef).

<a id="list_actions"></a>

### list_actions

Lists the available AWS FIS actions.

Type annotations for `session.create_client("fis").list_actions` method.

Boto3 documentation:
[FIS.Client.list_actions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.list_actions)

Asynchronous method. Use `await list_actions(...)` for a synchronous call.

Arguments mapping described in
[ListActionsRequestRequestTypeDef](./type_defs.md#listactionsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListActionsResponseTypeDef](./type_defs.md#listactionsresponsetypedef).

<a id="list_experiment_templates"></a>

### list_experiment_templates

Lists your experiment templates.

Type annotations for `session.create_client("fis").list_experiment_templates`
method.

Boto3 documentation:
[FIS.Client.list_experiment_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.list_experiment_templates)

Asynchronous method. Use `await list_experiment_templates(...)` for a
synchronous call.

Arguments mapping described in
[ListExperimentTemplatesRequestRequestTypeDef](./type_defs.md#listexperimenttemplatesrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListExperimentTemplatesResponseTypeDef](./type_defs.md#listexperimenttemplatesresponsetypedef).

<a id="list_experiments"></a>

### list_experiments

Lists your experiments.

Type annotations for `session.create_client("fis").list_experiments` method.

Boto3 documentation:
[FIS.Client.list_experiments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.list_experiments)

Asynchronous method. Use `await list_experiments(...)` for a synchronous call.

Arguments mapping described in
[ListExperimentsRequestRequestTypeDef](./type_defs.md#listexperimentsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListExperimentsResponseTypeDef](./type_defs.md#listexperimentsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags for the specified resource.

Type annotations for `session.create_client("fis").list_tags_for_resource`
method.

Boto3 documentation:
[FIS.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="start_experiment"></a>

### start_experiment

Starts running an experiment from the specified experiment template.

Type annotations for `session.create_client("fis").start_experiment` method.

Boto3 documentation:
[FIS.Client.start_experiment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.start_experiment)

Asynchronous method. Use `await start_experiment(...)` for a synchronous call.

Arguments mapping described in
[StartExperimentRequestRequestTypeDef](./type_defs.md#startexperimentrequestrequesttypedef).

Keyword-only arguments:

- `clientToken`: `str` *(required)*
- `experimentTemplateId`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[StartExperimentResponseTypeDef](./type_defs.md#startexperimentresponsetypedef).

<a id="stop_experiment"></a>

### stop_experiment

Stops the specified experiment.

Type annotations for `session.create_client("fis").stop_experiment` method.

Boto3 documentation:
[FIS.Client.stop_experiment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.stop_experiment)

Asynchronous method. Use `await stop_experiment(...)` for a synchronous call.

Arguments mapping described in
[StopExperimentRequestRequestTypeDef](./type_defs.md#stopexperimentrequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*

Returns a `Coroutine` for
[StopExperimentResponseTypeDef](./type_defs.md#stopexperimentresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Applies the specified tags to the specified resource.

Type annotations for `session.create_client("fis").tag_resource` method.

Boto3 documentation:
[FIS.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes the specified tags from the specified resource.

Type annotations for `session.create_client("fis").untag_resource` method.

Boto3 documentation:
[FIS.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_experiment_template"></a>

### update_experiment_template

Updates the specified experiment template.

Type annotations for `session.create_client("fis").update_experiment_template`
method.

Boto3 documentation:
[FIS.Client.update_experiment_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.update_experiment_template)

Asynchronous method. Use `await update_experiment_template(...)` for a
synchronous call.

Arguments mapping described in
[UpdateExperimentTemplateRequestRequestTypeDef](./type_defs.md#updateexperimenttemplaterequestrequesttypedef).

Keyword-only arguments:

- `id`: `str` *(required)*
- `description`: `str`
- `stopConditions`:
  `Sequence`\[[UpdateExperimentTemplateStopConditionInputTypeDef](./type_defs.md#updateexperimenttemplatestopconditioninputtypedef)\]
- `targets`: `Mapping`\[`str`,
  [UpdateExperimentTemplateTargetInputTypeDef](./type_defs.md#updateexperimenttemplatetargetinputtypedef)\]
- `actions`: `Mapping`\[`str`,
  [UpdateExperimentTemplateActionInputItemTypeDef](./type_defs.md#updateexperimenttemplateactioninputitemtypedef)\]
- `roleArn`: `str`

Returns a `Coroutine` for
[UpdateExperimentTemplateResponseTypeDef](./type_defs.md#updateexperimenttemplateresponsetypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("fis").__aenter__` method.

Boto3 documentation:
[FIS.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [FISClient](#fisclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("fis").__aexit__` method.

Boto3 documentation:
[FIS.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
