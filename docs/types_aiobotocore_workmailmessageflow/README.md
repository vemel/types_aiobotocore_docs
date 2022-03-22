<a id="type-annotations-for-aiobotocore-workmailmessageflow-module"></a>

# Type annotations for aiobotocore WorkMailMessageFlow module

> [Index](../README.md) > WorkMailMessageFlow

Auto-generated documentation for
[WorkMailMessageFlow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow)
type annotations stubs module
[types-aiobotocore-workmailmessageflow](https://pypi.org/project/types-aiobotocore-workmailmessageflow/).

- [Type annotations for aiobotocore WorkMailMessageFlow module](#type-annotations-for-aiobotocore-workmailmessageflow-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [WorkMailMessageFlowClient](#workmailmessageflowclient)
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

Click `Modify` and select `boto3 common` and `WorkMailMessageFlow`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `WorkMailMessageFlow` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[workmailmessageflow]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[workmailmessageflow]'


# standalone installation
python -m pip install types-aiobotocore-workmailmessageflow
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-workmailmessageflow
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="workmailmessageflowclient"></a>

## WorkMailMessageFlowClient

Type annotations for `session.create_client("workmailmessageflow")` as
[WorkMailMessageFlowClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_workmailmessageflow.client import WorkMailMessageFlowClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_raw_message_content](./client.md#get_raw_message_content)
- [put_raw_message_content](./client.md#put_raw_message_content)

<a id="exceptions"></a>

### Exceptions

WorkMailMessageFlowClient [exceptions](./client.md#exceptions)

- ClientError
- InvalidContentLocation
- MessageFrozen
- MessageRejected
- ResourceNotFoundException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_workmailmessageflow.literals import WorkMailMessageFlowServiceName, ...
```

- [WorkMailMessageFlowServiceName](./literals.md#workmailmessageflowservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_workmailmessageflow.type_defs import GetRawMessageContentRequestRequestTypeDef, ...
```

- [GetRawMessageContentRequestRequestTypeDef](./type_defs.md#getrawmessagecontentrequestrequesttypedef)
- [GetRawMessageContentResponseTypeDef](./type_defs.md#getrawmessagecontentresponsetypedef)
- [PutRawMessageContentRequestRequestTypeDef](./type_defs.md#putrawmessagecontentrequestrequesttypedef)
- [RawMessageContentTypeDef](./type_defs.md#rawmessagecontenttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [S3ReferenceTypeDef](./type_defs.md#s3referencetypedef)
