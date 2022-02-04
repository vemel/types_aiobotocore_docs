<a id="type-annotations-for-aiobotocore-fis-module"></a>

# Type annotations for aiobotocore FIS module

> [Index](..) > FIS

Auto-generated documentation for
[FIS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
type annotations stubs module
[types-aiobotocore-fis](https://pypi.org/project/types-aiobotocore-fis/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[fis]'

# install as a standalone
pip install types-aiobotocore-fis
```

- [Type annotations for aiobotocore FIS module](#type-annotations-for-aiobotocore-fis-module)
  - [FISClient](#fisclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="fisclient"></a>

## FISClient

Type annotations for `aiobotocore.create_client("fis")` as
[FISClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_fis.client import FISClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_experiment_template](./client.md#create_experiment_template)
- [delete_experiment_template](./client.md#delete_experiment_template)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_action](./client.md#get_action)
- [get_experiment](./client.md#get_experiment)
- [get_experiment_template](./client.md#get_experiment_template)
- [list_actions](./client.md#list_actions)
- [list_experiment_templates](./client.md#list_experiment_templates)
- [list_experiments](./client.md#list_experiments)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [start_experiment](./client.md#start_experiment)
- [stop_experiment](./client.md#stop_experiment)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_experiment_template](./client.md#update_experiment_template)

<a id="exceptions"></a>

### Exceptions

FISClient [exceptions](./client.md#exceptions)

- ClientError
- ConflictException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ValidationException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_fis.literals import ExperimentActionStatusType, ...
```

- [ExperimentActionStatusType](./literals.md#experimentactionstatustype)
- [ExperimentStatusType](./literals.md#experimentstatustype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_fis.type_defs import ActionParameterTypeDef, ...
```

- [ActionParameterTypeDef](./type_defs.md#actionparametertypedef)
- [ActionSummaryTypeDef](./type_defs.md#actionsummarytypedef)
- [ActionTargetTypeDef](./type_defs.md#actiontargettypedef)
- [ActionTypeDef](./type_defs.md#actiontypedef)
- [CreateExperimentTemplateActionInputTypeDef](./type_defs.md#createexperimenttemplateactioninputtypedef)
- [CreateExperimentTemplateRequestRequestTypeDef](./type_defs.md#createexperimenttemplaterequestrequesttypedef)
- [CreateExperimentTemplateResponseTypeDef](./type_defs.md#createexperimenttemplateresponsetypedef)
- [CreateExperimentTemplateStopConditionInputTypeDef](./type_defs.md#createexperimenttemplatestopconditioninputtypedef)
- [CreateExperimentTemplateTargetInputTypeDef](./type_defs.md#createexperimenttemplatetargetinputtypedef)
- [DeleteExperimentTemplateRequestRequestTypeDef](./type_defs.md#deleteexperimenttemplaterequestrequesttypedef)
- [DeleteExperimentTemplateResponseTypeDef](./type_defs.md#deleteexperimenttemplateresponsetypedef)
- [ExperimentActionStateTypeDef](./type_defs.md#experimentactionstatetypedef)
- [ExperimentActionTypeDef](./type_defs.md#experimentactiontypedef)
- [ExperimentStateTypeDef](./type_defs.md#experimentstatetypedef)
- [ExperimentStopConditionTypeDef](./type_defs.md#experimentstopconditiontypedef)
- [ExperimentSummaryTypeDef](./type_defs.md#experimentsummarytypedef)
- [ExperimentTargetFilterTypeDef](./type_defs.md#experimenttargetfiltertypedef)
- [ExperimentTargetTypeDef](./type_defs.md#experimenttargettypedef)
- [ExperimentTemplateActionTypeDef](./type_defs.md#experimenttemplateactiontypedef)
- [ExperimentTemplateStopConditionTypeDef](./type_defs.md#experimenttemplatestopconditiontypedef)
- [ExperimentTemplateSummaryTypeDef](./type_defs.md#experimenttemplatesummarytypedef)
- [ExperimentTemplateTargetFilterTypeDef](./type_defs.md#experimenttemplatetargetfiltertypedef)
- [ExperimentTemplateTargetInputFilterTypeDef](./type_defs.md#experimenttemplatetargetinputfiltertypedef)
- [ExperimentTemplateTargetTypeDef](./type_defs.md#experimenttemplatetargettypedef)
- [ExperimentTemplateTypeDef](./type_defs.md#experimenttemplatetypedef)
- [ExperimentTypeDef](./type_defs.md#experimenttypedef)
- [GetActionRequestRequestTypeDef](./type_defs.md#getactionrequestrequesttypedef)
- [GetActionResponseTypeDef](./type_defs.md#getactionresponsetypedef)
- [GetExperimentRequestRequestTypeDef](./type_defs.md#getexperimentrequestrequesttypedef)
- [GetExperimentResponseTypeDef](./type_defs.md#getexperimentresponsetypedef)
- [GetExperimentTemplateRequestRequestTypeDef](./type_defs.md#getexperimenttemplaterequestrequesttypedef)
- [GetExperimentTemplateResponseTypeDef](./type_defs.md#getexperimenttemplateresponsetypedef)
- [ListActionsRequestRequestTypeDef](./type_defs.md#listactionsrequestrequesttypedef)
- [ListActionsResponseTypeDef](./type_defs.md#listactionsresponsetypedef)
- [ListExperimentTemplatesRequestRequestTypeDef](./type_defs.md#listexperimenttemplatesrequestrequesttypedef)
- [ListExperimentTemplatesResponseTypeDef](./type_defs.md#listexperimenttemplatesresponsetypedef)
- [ListExperimentsRequestRequestTypeDef](./type_defs.md#listexperimentsrequestrequesttypedef)
- [ListExperimentsResponseTypeDef](./type_defs.md#listexperimentsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartExperimentRequestRequestTypeDef](./type_defs.md#startexperimentrequestrequesttypedef)
- [StartExperimentResponseTypeDef](./type_defs.md#startexperimentresponsetypedef)
- [StopExperimentRequestRequestTypeDef](./type_defs.md#stopexperimentrequestrequesttypedef)
- [StopExperimentResponseTypeDef](./type_defs.md#stopexperimentresponsetypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateExperimentTemplateActionInputItemTypeDef](./type_defs.md#updateexperimenttemplateactioninputitemtypedef)
- [UpdateExperimentTemplateRequestRequestTypeDef](./type_defs.md#updateexperimenttemplaterequestrequesttypedef)
- [UpdateExperimentTemplateResponseTypeDef](./type_defs.md#updateexperimenttemplateresponsetypedef)
- [UpdateExperimentTemplateStopConditionInputTypeDef](./type_defs.md#updateexperimenttemplatestopconditioninputtypedef)
- [UpdateExperimentTemplateTargetInputTypeDef](./type_defs.md#updateexperimenttemplatetargetinputtypedef)
