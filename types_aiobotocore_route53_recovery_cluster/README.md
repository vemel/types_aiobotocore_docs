<a id="type-annotations-for-aiobotocore-route53recoverycluster-module"></a>

# Type annotations for aiobotocore Route53RecoveryCluster module

> [Index](..) > Route53RecoveryCluster

Auto-generated documentation for
[Route53RecoveryCluster](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster)
type annotations stubs module
[types-aiobotocore-route53-recovery-cluster](https://pypi.org/project/types-aiobotocore-route53-recovery-cluster/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[route53-recovery-cluster]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[route53-recovery-cluster]'

# standalone installation
pip install types-aiobotocore-route53-recovery-cluster
```

- [Type annotations for aiobotocore Route53RecoveryCluster module](#type-annotations-for-aiobotocore-route53recoverycluster-module)
  - [Route53RecoveryClusterClient](#route53recoveryclusterclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="route53recoveryclusterclient"></a>

## Route53RecoveryClusterClient

Type annotations for `session.create_client("route53-recovery-cluster")` as
[Route53RecoveryClusterClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_route53_recovery_cluster.client import Route53RecoveryClusterClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_routing_control_state](./client.md#get_routing_control_state)
- [update_routing_control_state](./client.md#update_routing_control_state)
- [update_routing_control_states](./client.md#update_routing_control_states)

<a id="exceptions"></a>

### Exceptions

Route53RecoveryClusterClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- ConflictException
- EndpointTemporarilyUnavailableException
- InternalServerException
- ResourceNotFoundException
- ThrottlingException
- ValidationException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_route53_recovery_cluster.literals import RoutingControlStateType, ...
```

- [RoutingControlStateType](./literals.md#routingcontrolstatetype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_route53_recovery_cluster.type_defs import GetRoutingControlStateRequestRequestTypeDef, ...
```

- [GetRoutingControlStateRequestRequestTypeDef](./type_defs.md#getroutingcontrolstaterequestrequesttypedef)
- [GetRoutingControlStateResponseTypeDef](./type_defs.md#getroutingcontrolstateresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [UpdateRoutingControlStateEntryTypeDef](./type_defs.md#updateroutingcontrolstateentrytypedef)
- [UpdateRoutingControlStateRequestRequestTypeDef](./type_defs.md#updateroutingcontrolstaterequestrequesttypedef)
- [UpdateRoutingControlStatesRequestRequestTypeDef](./type_defs.md#updateroutingcontrolstatesrequestrequesttypedef)
