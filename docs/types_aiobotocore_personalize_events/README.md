<a id="type-annotations-for-aiobotocore-personalizeevents-module"></a>

# Type annotations for aiobotocore PersonalizeEvents module

> [Index](../README.md) > PersonalizeEvents

Auto-generated documentation for
[PersonalizeEvents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-events.html#PersonalizeEvents)
type annotations stubs module
[types-aiobotocore-personalize-events](https://pypi.org/project/types-aiobotocore-personalize-events/).

- [Type annotations for aiobotocore PersonalizeEvents module](#type-annotations-for-aiobotocore-personalizeevents-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [PersonalizeEventsClient](#personalizeeventsclient)
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

Click `Modify` and select `boto3 common` and `PersonalizeEvents`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `PersonalizeEvents` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[personalize-events]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[personalize-events]'


# standalone installation
python -m pip install types-aiobotocore-personalize-events
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-personalize-events
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="personalizeeventsclient"></a>

## PersonalizeEventsClient

Type annotations for `session.create_client("personalize-events")` as
[PersonalizeEventsClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_personalize_events.client import PersonalizeEventsClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [put_events](./client.md#put_events)
- [put_items](./client.md#put_items)
- [put_users](./client.md#put_users)

<a id="exceptions"></a>

### Exceptions

PersonalizeEventsClient [exceptions](./client.md#exceptions)

- ClientError
- InvalidInputException
- ResourceInUseException
- ResourceNotFoundException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_personalize_events.literals import PersonalizeEventsServiceName, ...
```

- [PersonalizeEventsServiceName](./literals.md#personalizeeventsservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_personalize_events.type_defs import EventTypeDef, ...
```

- [EventTypeDef](./type_defs.md#eventtypedef)
- [ItemTypeDef](./type_defs.md#itemtypedef)
- [PutEventsRequestRequestTypeDef](./type_defs.md#puteventsrequestrequesttypedef)
- [PutItemsRequestRequestTypeDef](./type_defs.md#putitemsrequestrequesttypedef)
- [PutUsersRequestRequestTypeDef](./type_defs.md#putusersrequestrequesttypedef)
- [UserTypeDef](./type_defs.md#usertypedef)
