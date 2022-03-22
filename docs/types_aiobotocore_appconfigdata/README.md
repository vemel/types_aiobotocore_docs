<a id="type-annotations-for-aiobotocore-appconfigdata-module"></a>

# Type annotations for aiobotocore AppConfigData module

> [Index](../README.md) > AppConfigData

Auto-generated documentation for
[AppConfigData](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfigdata.html#AppConfigData)
type annotations stubs module
[types-aiobotocore-appconfigdata](https://pypi.org/project/types-aiobotocore-appconfigdata/).

- [Type annotations for aiobotocore AppConfigData module](#type-annotations-for-aiobotocore-appconfigdata-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [AppConfigDataClient](#appconfigdataclient)
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

Click `Modify` and select `boto3 common` and `AppConfigData`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `AppConfigData` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[appconfigdata]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[appconfigdata]'


# standalone installation
python -m pip install types-aiobotocore-appconfigdata
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-appconfigdata
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="appconfigdataclient"></a>

## AppConfigDataClient

Type annotations for `session.create_client("appconfigdata")` as
[AppConfigDataClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_appconfigdata.client import AppConfigDataClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_latest_configuration](./client.md#get_latest_configuration)
- [start_configuration_session](./client.md#start_configuration_session)

<a id="exceptions"></a>

### Exceptions

AppConfigDataClient [exceptions](./client.md#exceptions)

- BadRequestException
- ClientError
- InternalServerException
- ResourceNotFoundException
- ThrottlingException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_appconfigdata.literals import AppConfigDataServiceName, ...
```

- [AppConfigDataServiceName](./literals.md#appconfigdataservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_appconfigdata.type_defs import GetLatestConfigurationRequestRequestTypeDef, ...
```

- [GetLatestConfigurationRequestRequestTypeDef](./type_defs.md#getlatestconfigurationrequestrequesttypedef)
- [GetLatestConfigurationResponseTypeDef](./type_defs.md#getlatestconfigurationresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartConfigurationSessionRequestRequestTypeDef](./type_defs.md#startconfigurationsessionrequestrequesttypedef)
- [StartConfigurationSessionResponseTypeDef](./type_defs.md#startconfigurationsessionresponsetypedef)
