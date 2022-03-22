<a id="type-annotations-for-aiobotocore-personalizeruntime-module"></a>

# Type annotations for aiobotocore PersonalizeRuntime module

> [Index](../README.md) > PersonalizeRuntime

Auto-generated documentation for
[PersonalizeRuntime](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime)
type annotations stubs module
[types-aiobotocore-personalize-runtime](https://pypi.org/project/types-aiobotocore-personalize-runtime/).

- [Type annotations for aiobotocore PersonalizeRuntime module](#type-annotations-for-aiobotocore-personalizeruntime-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [PersonalizeRuntimeClient](#personalizeruntimeclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `PersonalizeRuntime`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `PersonalizeRuntime` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[personalize-runtime]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[personalize-runtime]'


# standalone installation
python -m pip install types-aiobotocore-personalize-runtime
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-personalize-runtime
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="personalizeruntimeclient"></a>

## PersonalizeRuntimeClient

Type annotations for `session.create_client("personalize-runtime")` as
[PersonalizeRuntimeClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_personalize_runtime.client import PersonalizeRuntimeClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_personalized_ranking](./client.md#get_personalized_ranking)
- [get_recommendations](./client.md#get_recommendations)

<a id="exceptions"></a>

### Exceptions

PersonalizeRuntimeClient [exceptions](./client.md#exceptions)

- ClientError
- InvalidInputException
- ResourceNotFoundException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_personalize_runtime.literals import PersonalizeRuntimeServiceName, ...
```

- [PersonalizeRuntimeServiceName](./literals.md#personalizeruntimeservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_personalize_runtime.type_defs import GetPersonalizedRankingRequestRequestTypeDef, ...
```

- [GetPersonalizedRankingRequestRequestTypeDef](./type_defs.md#getpersonalizedrankingrequestrequesttypedef)
- [GetPersonalizedRankingResponseTypeDef](./type_defs.md#getpersonalizedrankingresponsetypedef)
- [GetRecommendationsRequestRequestTypeDef](./type_defs.md#getrecommendationsrequestrequesttypedef)
- [GetRecommendationsResponseTypeDef](./type_defs.md#getrecommendationsresponsetypedef)
- [PredictedItemTypeDef](./type_defs.md#predicteditemtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
