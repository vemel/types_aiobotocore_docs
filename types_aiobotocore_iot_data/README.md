<a id="type-annotations-for-aiobotocore-iotdataplane-module"></a>

# Type annotations for aiobotocore IoTDataPlane module

> [Index](..) > IoTDataPlane

Auto-generated documentation for
[IoTDataPlane](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane)
type annotations stubs module
[types-aiobotocore-iot-data](https://pypi.org/project/types-aiobotocore-iot-data/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[iot-data]'

# install as a standalone
pip install types-aiobotocore-iot-data
```

- [Type annotations for aiobotocore IoTDataPlane module](#type-annotations-for-aiobotocore-iotdataplane-module)
  - [IoTDataPlaneClient](#iotdataplaneclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="iotdataplaneclient"></a>

## IoTDataPlaneClient

Type annotations for `aiobotocore.create_client("iot-data")` as
[IoTDataPlaneClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_iot_data.client import IoTDataPlaneClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [delete_thing_shadow](./client.md#delete_thing_shadow)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [get_retained_message](./client.md#get_retained_message)
- [get_thing_shadow](./client.md#get_thing_shadow)
- [list_named_shadows_for_thing](./client.md#list_named_shadows_for_thing)
- [list_retained_messages](./client.md#list_retained_messages)
- [publish](./client.md#publish)
- [update_thing_shadow](./client.md#update_thing_shadow)

<a id="exceptions"></a>

### Exceptions

IoTDataPlaneClient [exceptions](./client.md#exceptions)

- ClientError
- ConflictException
- InternalFailureException
- InvalidRequestException
- MethodNotAllowedException
- RequestEntityTooLargeException
- ResourceNotFoundException
- ServiceUnavailableException
- ThrottlingException
- UnauthorizedException
- UnsupportedDocumentEncodingException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("iot-data").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_iot_data.paginators import ListRetainedMessagesPaginator, ...
```

- [ListRetainedMessagesPaginator](./paginators.md#listretainedmessagespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_iot_data.literals import ListRetainedMessagesPaginatorName, ...
```

- [ListRetainedMessagesPaginatorName](./literals.md#listretainedmessagespaginatorname)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_iot_data.type_defs import DeleteThingShadowRequestRequestTypeDef, ...
```

- [DeleteThingShadowRequestRequestTypeDef](./type_defs.md#deletethingshadowrequestrequesttypedef)
- [DeleteThingShadowResponseTypeDef](./type_defs.md#deletethingshadowresponsetypedef)
- [GetRetainedMessageRequestRequestTypeDef](./type_defs.md#getretainedmessagerequestrequesttypedef)
- [GetRetainedMessageResponseTypeDef](./type_defs.md#getretainedmessageresponsetypedef)
- [GetThingShadowRequestRequestTypeDef](./type_defs.md#getthingshadowrequestrequesttypedef)
- [GetThingShadowResponseTypeDef](./type_defs.md#getthingshadowresponsetypedef)
- [ListNamedShadowsForThingRequestRequestTypeDef](./type_defs.md#listnamedshadowsforthingrequestrequesttypedef)
- [ListNamedShadowsForThingResponseTypeDef](./type_defs.md#listnamedshadowsforthingresponsetypedef)
- [ListRetainedMessagesRequestRequestTypeDef](./type_defs.md#listretainedmessagesrequestrequesttypedef)
- [ListRetainedMessagesResponseTypeDef](./type_defs.md#listretainedmessagesresponsetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PublishRequestRequestTypeDef](./type_defs.md#publishrequestrequesttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RetainedMessageSummaryTypeDef](./type_defs.md#retainedmessagesummarytypedef)
- [UpdateThingShadowRequestRequestTypeDef](./type_defs.md#updatethingshadowrequestrequesttypedef)
- [UpdateThingShadowResponseTypeDef](./type_defs.md#updatethingshadowresponsetypedef)
