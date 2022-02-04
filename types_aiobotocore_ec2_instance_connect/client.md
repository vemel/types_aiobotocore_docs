<a id="ec2instanceconnectclient-for-aiobotocore-ec2instanceconnect-module"></a>

# EC2InstanceConnectClient for aiobotocore EC2InstanceConnect module

> [Index](..) > [EC2InstanceConnect](.) > EC2InstanceConnectClient

Auto-generated documentation for
[EC2InstanceConnect](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2-instance-connect.html#EC2InstanceConnect)
type annotations stubs module
[types-aiobotocore-ec2-instance-connect](https://pypi.org/project/types-aiobotocore-ec2-instance-connect/).

- [EC2InstanceConnectClient for aiobotocore EC2InstanceConnect module](#ec2instanceconnectclient-for-aiobotocore-ec2instanceconnect-module)
  - [EC2InstanceConnectClient](#ec2instanceconnectclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [generate_presigned_url](#generate_presigned_url)
    - [send_serial_console_ssh_public_key](#send_serial_console_ssh_public_key)
    - [send_ssh_public_key](#send_ssh_public_key)

<a id="ec2instanceconnectclient"></a>

## EC2InstanceConnectClient

Type annotations for `aiobotocore.create_client("ec2-instance-connect")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_ec2_instance_connect.client import EC2InstanceConnectClient

def get_ec2-instance-connect_client() -> EC2InstanceConnectClient:
    return Session().client("ec2-instance-connect")
```

Boto3 documentation:
[EC2InstanceConnect.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2-instance-connect.html#EC2InstanceConnect.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ec2_instance_connect.client import Exceptions

def handle_error(exc: Exceptions.AuthException) -> None:
    ...
```

Exceptions:

- `Exceptions.AuthException`
- `Exceptions.ClientError`
- `Exceptions.EC2InstanceNotFoundException`
- `Exceptions.EC2InstanceTypeInvalidException`
- `Exceptions.InvalidArgsException`
- `Exceptions.SerialConsoleAccessDisabledException`
- `Exceptions.SerialConsoleSessionLimitExceededException`
- `Exceptions.SerialConsoleSessionUnavailableException`
- `Exceptions.ServiceException`
- `Exceptions.ThrottlingException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

EC2InstanceConnectClient exceptions.

Type annotations for
`aiobotocore.create_client("ec2-instance-connect").exceptions` method.

Boto3 documentation:
[EC2InstanceConnect.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2-instance-connect.html#EC2InstanceConnect.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("ec2-instance-connect").can_paginate` method.

Boto3 documentation:
[EC2InstanceConnect.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2-instance-connect.html#EC2InstanceConnect.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("ec2-instance-connect").generate_presigned_url`
method.

Boto3 documentation:
[EC2InstanceConnect.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2-instance-connect.html#EC2InstanceConnect.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="send_serial_console_ssh_public_key"></a>

### send_serial_console_ssh_public_key

Pushes an SSH public key to the specified EC2 instance.

Type annotations for
`aiobotocore.create_client("ec2-instance-connect").send_serial_console_ssh_public_key`
method.

Boto3 documentation:
[EC2InstanceConnect.Client.send_serial_console_ssh_public_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2-instance-connect.html#EC2InstanceConnect.Client.send_serial_console_ssh_public_key)

Asynchronous method. Use `await send_serial_console_ssh_public_key(...)` for a
synchronous call.

Arguments mapping described in
[SendSerialConsoleSSHPublicKeyRequestRequestTypeDef](./type_defs.md#sendserialconsolesshpublickeyrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `SSHPublicKey`: `str` *(required)*
- `SerialPort`: `int`

Returns a `Coroutine` for
[SendSerialConsoleSSHPublicKeyResponseTypeDef](./type_defs.md#sendserialconsolesshpublickeyresponsetypedef).

<a id="send_ssh_public_key"></a>

### send_ssh_public_key

Pushes an SSH public key to the specified EC2 instance for use by the specified
user.

Type annotations for
`aiobotocore.create_client("ec2-instance-connect").send_ssh_public_key` method.

Boto3 documentation:
[EC2InstanceConnect.Client.send_ssh_public_key](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2-instance-connect.html#EC2InstanceConnect.Client.send_ssh_public_key)

Asynchronous method. Use `await send_ssh_public_key(...)` for a synchronous
call.

Arguments mapping described in
[SendSSHPublicKeyRequestRequestTypeDef](./type_defs.md#sendsshpublickeyrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `InstanceOSUser`: `str` *(required)*
- `SSHPublicKey`: `str` *(required)*
- `AvailabilityZone`: `str` *(required)*

Returns a `Coroutine` for
[SendSSHPublicKeyResponseTypeDef](./type_defs.md#sendsshpublickeyresponsetypedef).
