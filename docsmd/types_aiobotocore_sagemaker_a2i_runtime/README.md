# AugmentedAIRuntime module

> [Index](../README.md) > AugmentedAIRuntime


!!! note ""

    Auto-generated documentation for [AugmentedAIRuntime](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime)
    type annotations stubs module [types-aiobotocore-sagemaker-a2i-runtime](https://pypi.org/project/types-aiobotocore-sagemaker-a2i-runtime/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `AugmentedAIRuntime`.

### From PyPI with pip

Install `types-aiobotocore` for `AugmentedAIRuntime` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[sagemaker-a2i-runtime]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[sagemaker-a2i-runtime]'


# standalone installation
python -m pip install types-aiobotocore-sagemaker-a2i-runtime
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-sagemaker-a2i-runtime
```

## Usage

Code samples can be found in [Examples](./usage.md).

## AugmentedAIRuntimeClient

Type annotations and code completion for  `#!python session.create_client("sagemaker-a2i-runtime")` as [AugmentedAIRuntimeClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_sagemaker_a2i_runtime.client import AugmentedAIRuntimeClient


session = get_session()
async with session.create_client("sagemaker-a2i-runtime") as client:
    client: AugmentedAIRuntimeClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("sagemaker-a2i-runtime").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_sagemaker_a2i_runtime.paginator import ListHumanLoopsPaginator

def get_list_human_loops_paginator() -> ListHumanLoopsPaginator:
    return client.get_paginator("list_human_loops"))
```

- [ListHumanLoopsPaginator](./paginators.md#listhumanloopspaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_sagemaker_a2i_runtime.literals import ContentClassifierType

def get_value() -> ContentClassifierType:
    return "FreeOfAdultContent"
```

- [ContentClassifierType](./literals.md#contentclassifiertype)
- [HumanLoopStatusType](./literals.md#humanloopstatustype)
- [ListHumanLoopsPaginatorName](./literals.md#listhumanloopspaginatorname)
- [SortOrderType](./literals.md#sortordertype)
- [AugmentedAIRuntimeServiceName](./literals.md#augmentedairuntimeservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_sagemaker_a2i_runtime.type_defs import DeleteHumanLoopRequestRequestTypeDef

def get_value() -> DeleteHumanLoopRequestRequestTypeDef:
    return {
        "HumanLoopName": ...,
    }
```

- [DeleteHumanLoopRequestRequestTypeDef](./type_defs.md#deletehumanlooprequestrequesttypedef)
- [DescribeHumanLoopRequestRequestTypeDef](./type_defs.md#describehumanlooprequestrequesttypedef)
- [DescribeHumanLoopResponseTypeDef](./type_defs.md#describehumanloopresponsetypedef)
- [HumanLoopDataAttributesTypeDef](./type_defs.md#humanloopdataattributestypedef)
- [HumanLoopInputTypeDef](./type_defs.md#humanloopinputtypedef)
- [HumanLoopOutputTypeDef](./type_defs.md#humanloopoutputtypedef)
- [HumanLoopSummaryTypeDef](./type_defs.md#humanloopsummarytypedef)
- [ListHumanLoopsRequestListHumanLoopsPaginateTypeDef](./type_defs.md#listhumanloopsrequestlisthumanloopspaginatetypedef)
- [ListHumanLoopsRequestRequestTypeDef](./type_defs.md#listhumanloopsrequestrequesttypedef)
- [ListHumanLoopsResponseTypeDef](./type_defs.md#listhumanloopsresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartHumanLoopRequestRequestTypeDef](./type_defs.md#starthumanlooprequestrequesttypedef)
- [StartHumanLoopResponseTypeDef](./type_defs.md#starthumanloopresponsetypedef)
- [StopHumanLoopRequestRequestTypeDef](./type_defs.md#stophumanlooprequestrequesttypedef)

