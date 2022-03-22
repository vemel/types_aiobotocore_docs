<a id="type-annotations-for-aiobotocore-cloudcontrolapi-module"></a>

# Type annotations for aiobotocore CloudControlApi module

> [Index](../README.md) > CloudControlApi

Auto-generated documentation for
[CloudControlApi](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi)
type annotations stubs module
[types-aiobotocore-cloudcontrol](https://pypi.org/project/types-aiobotocore-cloudcontrol/).

- [Type annotations for aiobotocore CloudControlApi module](#type-annotations-for-aiobotocore-cloudcontrolapi-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [CloudControlApiClient](#cloudcontrolapiclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Waiters](#waiters)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `CloudControlApi`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `CloudControlApi` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[cloudcontrol]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[cloudcontrol]'


# standalone installation
python -m pip install types-aiobotocore-cloudcontrol
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-cloudcontrol
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="cloudcontrolapiclient"></a>

## CloudControlApiClient

Type annotations for `session.create_client("cloudcontrol")` as
[CloudControlApiClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_cloudcontrol.client import CloudControlApiClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [cancel_resource_request](./client.md#cancel_resource_request)
- [create_resource](./client.md#create_resource)
- [delete_resource](./client.md#delete_resource)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_resource](./client.md#get_resource)
- [get_resource_request_status](./client.md#get_resource_request_status)
- [get_waiter](./client.md#get_waiter)
- [list_resource_requests](./client.md#list_resource_requests)
- [list_resources](./client.md#list_resources)
- [update_resource](./client.md#update_resource)

<a id="exceptions"></a>

### Exceptions

CloudControlApiClient [exceptions](./client.md#exceptions)

- AlreadyExistsException
- ClientError
- ClientTokenConflictException
- ConcurrentModificationException
- ConcurrentOperationException
- GeneralServiceException
- HandlerFailureException
- HandlerInternalFailureException
- InvalidCredentialsException
- InvalidRequestException
- NetworkFailureException
- NotStabilizedException
- NotUpdatableException
- PrivateTypeException
- RequestTokenNotFoundException
- ResourceConflictException
- ResourceNotFoundException
- ServiceInternalErrorException
- ServiceLimitExceededException
- ThrottlingException
- TypeNotFoundException
- UnsupportedActionException

<a id="waiters"></a>

## Waiters

Type annotations for [waiters](./waiters.md) from
`boto3.client("cloudcontrol").get_waiter("...")`.

Can be used directly:

```python
from types_aiobotocore_cloudcontrol.waiter import ResourceRequestSuccessWaiter, ...
```

- [ResourceRequestSuccessWaiter](./waiters.md#resourcerequestsuccesswaiter)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_cloudcontrol.literals import HandlerErrorCodeType, ...
```

- [HandlerErrorCodeType](./literals.md#handlererrorcodetype)
- [OperationStatusType](./literals.md#operationstatustype)
- [OperationType](./literals.md#operationtype)
- [ResourceRequestSuccessWaiterName](./literals.md#resourcerequestsuccesswaitername)
- [CloudControlApiServiceName](./literals.md#cloudcontrolapiservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [WaiterName](./literals.md#waitername)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_cloudcontrol.type_defs import CancelResourceRequestInputRequestTypeDef, ...
```

- [CancelResourceRequestInputRequestTypeDef](./type_defs.md#cancelresourcerequestinputrequesttypedef)
- [CancelResourceRequestOutputTypeDef](./type_defs.md#cancelresourcerequestoutputtypedef)
- [CreateResourceInputRequestTypeDef](./type_defs.md#createresourceinputrequesttypedef)
- [CreateResourceOutputTypeDef](./type_defs.md#createresourceoutputtypedef)
- [DeleteResourceInputRequestTypeDef](./type_defs.md#deleteresourceinputrequesttypedef)
- [DeleteResourceOutputTypeDef](./type_defs.md#deleteresourceoutputtypedef)
- [GetResourceInputRequestTypeDef](./type_defs.md#getresourceinputrequesttypedef)
- [GetResourceOutputTypeDef](./type_defs.md#getresourceoutputtypedef)
- [GetResourceRequestStatusInputRequestTypeDef](./type_defs.md#getresourcerequeststatusinputrequesttypedef)
- [GetResourceRequestStatusOutputTypeDef](./type_defs.md#getresourcerequeststatusoutputtypedef)
- [ListResourceRequestsInputRequestTypeDef](./type_defs.md#listresourcerequestsinputrequesttypedef)
- [ListResourceRequestsOutputTypeDef](./type_defs.md#listresourcerequestsoutputtypedef)
- [ListResourcesInputRequestTypeDef](./type_defs.md#listresourcesinputrequesttypedef)
- [ListResourcesOutputTypeDef](./type_defs.md#listresourcesoutputtypedef)
- [ProgressEventTypeDef](./type_defs.md#progresseventtypedef)
- [ResourceDescriptionTypeDef](./type_defs.md#resourcedescriptiontypedef)
- [ResourceRequestStatusFilterTypeDef](./type_defs.md#resourcerequeststatusfiltertypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [UpdateResourceInputRequestTypeDef](./type_defs.md#updateresourceinputrequesttypedef)
- [UpdateResourceOutputTypeDef](./type_defs.md#updateresourceoutputtypedef)
- [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
