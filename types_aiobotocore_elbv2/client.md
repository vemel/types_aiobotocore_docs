<a id="elasticloadbalancingv2client-for-aiobotocore-elasticloadbalancingv2-module"></a>

# ElasticLoadBalancingv2Client for aiobotocore ElasticLoadBalancingv2 module

> [Index](..) > [ElasticLoadBalancingv2](.) > ElasticLoadBalancingv2Client

Auto-generated documentation for
[ElasticLoadBalancingv2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2)
type annotations stubs module
[types-aiobotocore-elbv2](https://pypi.org/project/types-aiobotocore-elbv2/).

- [ElasticLoadBalancingv2Client for aiobotocore ElasticLoadBalancingv2 module](#elasticloadbalancingv2client-for-aiobotocore-elasticloadbalancingv2-module)
  - [ElasticLoadBalancingv2Client](#elasticloadbalancingv2client)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_listener_certificates](#add_listener_certificates)
    - [add_tags](#add_tags)
    - [can_paginate](#can_paginate)
    - [create_listener](#create_listener)
    - [create_load_balancer](#create_load_balancer)
    - [create_rule](#create_rule)
    - [create_target_group](#create_target_group)
    - [delete_listener](#delete_listener)
    - [delete_load_balancer](#delete_load_balancer)
    - [delete_rule](#delete_rule)
    - [delete_target_group](#delete_target_group)
    - [deregister_targets](#deregister_targets)
    - [describe_account_limits](#describe_account_limits)
    - [describe_listener_certificates](#describe_listener_certificates)
    - [describe_listeners](#describe_listeners)
    - [describe_load_balancer_attributes](#describe_load_balancer_attributes)
    - [describe_load_balancers](#describe_load_balancers)
    - [describe_rules](#describe_rules)
    - [describe_ssl_policies](#describe_ssl_policies)
    - [describe_tags](#describe_tags)
    - [describe_target_group_attributes](#describe_target_group_attributes)
    - [describe_target_groups](#describe_target_groups)
    - [describe_target_health](#describe_target_health)
    - [generate_presigned_url](#generate_presigned_url)
    - [modify_listener](#modify_listener)
    - [modify_load_balancer_attributes](#modify_load_balancer_attributes)
    - [modify_rule](#modify_rule)
    - [modify_target_group](#modify_target_group)
    - [modify_target_group_attributes](#modify_target_group_attributes)
    - [register_targets](#register_targets)
    - [remove_listener_certificates](#remove_listener_certificates)
    - [remove_tags](#remove_tags)
    - [set_ip_address_type](#set_ip_address_type)
    - [set_rule_priorities](#set_rule_priorities)
    - [set_security_groups](#set_security_groups)
    - [set_subnets](#set_subnets)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="elasticloadbalancingv2client"></a>

## ElasticLoadBalancingv2Client

Type annotations for `session.create_client("elbv2")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_elbv2.client import ElasticLoadBalancingv2Client

session = get_session()
async with session.create_client("elbv2") as client:
    client: ElasticLoadBalancingv2Client
```

Boto3 documentation:
[ElasticLoadBalancingv2.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_elbv2.client import Exceptions

def handle_error(exc: Exceptions.ALPNPolicyNotSupportedException) -> None:
    ...
```

Exceptions:

- `Exceptions.ALPNPolicyNotSupportedException`
- `Exceptions.AllocationIdNotFoundException`
- `Exceptions.AvailabilityZoneNotSupportedException`
- `Exceptions.CertificateNotFoundException`
- `Exceptions.ClientError`
- `Exceptions.DuplicateListenerException`
- `Exceptions.DuplicateLoadBalancerNameException`
- `Exceptions.DuplicateTagKeysException`
- `Exceptions.DuplicateTargetGroupNameException`
- `Exceptions.HealthUnavailableException`
- `Exceptions.IncompatibleProtocolsException`
- `Exceptions.InvalidConfigurationRequestException`
- `Exceptions.InvalidLoadBalancerActionException`
- `Exceptions.InvalidSchemeException`
- `Exceptions.InvalidSecurityGroupException`
- `Exceptions.InvalidSubnetException`
- `Exceptions.InvalidTargetException`
- `Exceptions.ListenerNotFoundException`
- `Exceptions.LoadBalancerNotFoundException`
- `Exceptions.OperationNotPermittedException`
- `Exceptions.PriorityInUseException`
- `Exceptions.ResourceInUseException`
- `Exceptions.RuleNotFoundException`
- `Exceptions.SSLPolicyNotFoundException`
- `Exceptions.SubnetNotFoundException`
- `Exceptions.TargetGroupAssociationLimitException`
- `Exceptions.TargetGroupNotFoundException`
- `Exceptions.TooManyActionsException`
- `Exceptions.TooManyCertificatesException`
- `Exceptions.TooManyListenersException`
- `Exceptions.TooManyLoadBalancersException`
- `Exceptions.TooManyRegistrationsForTargetIdException`
- `Exceptions.TooManyRulesException`
- `Exceptions.TooManyTagsException`
- `Exceptions.TooManyTargetGroupsException`
- `Exceptions.TooManyTargetsException`
- `Exceptions.TooManyUniqueTargetGroupsPerLoadBalancerException`
- `Exceptions.UnsupportedProtocolException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ElasticLoadBalancingv2Client exceptions.

Type annotations for `session.create_client("elbv2").exceptions` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add_listener_certificates"></a>

### add_listener_certificates

Adds the specified SSL server certificate to the certificate list for the
specified HTTPS or TLS listener.

Type annotations for `session.create_client("elbv2").add_listener_certificates`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.add_listener_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.add_listener_certificates)

Asynchronous method. Use `await add_listener_certificates(...)` for a
synchronous call.

Arguments mapping described in
[AddListenerCertificatesInputRequestTypeDef](./type_defs.md#addlistenercertificatesinputrequesttypedef).

Keyword-only arguments:

- `ListenerArn`: `str` *(required)*
- `Certificates`:
  `Sequence`\[[CertificateTypeDef](./type_defs.md#certificatetypedef)\]
  *(required)*

Returns a `Coroutine` for
[AddListenerCertificatesOutputTypeDef](./type_defs.md#addlistenercertificatesoutputtypedef).

<a id="add_tags"></a>

### add_tags

Adds the specified tags to the specified Elastic Load Balancing resource.

Type annotations for `session.create_client("elbv2").add_tags` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.add_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.add_tags)

Asynchronous method. Use `await add_tags(...)` for a synchronous call.

Arguments mapping described in
[AddTagsInputRequestTypeDef](./type_defs.md#addtagsinputrequesttypedef).

Keyword-only arguments:

- `ResourceArns`: `Sequence`\[`str`\] *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("elbv2").can_paginate` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_listener"></a>

### create_listener

Creates a listener for the specified Application Load Balancer, Network Load
Balancer, or Gateway Load Balancer.

Type annotations for `session.create_client("elbv2").create_listener` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.create_listener](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.create_listener)

Asynchronous method. Use `await create_listener(...)` for a synchronous call.

Arguments mapping described in
[CreateListenerInputRequestTypeDef](./type_defs.md#createlistenerinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str` *(required)*
- `DefaultActions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]
  *(required)*
- `Protocol`: [ProtocolEnumType](./literals.md#protocolenumtype)
- `Port`: `int`
- `SslPolicy`: `str`
- `Certificates`:
  `Sequence`\[[CertificateTypeDef](./type_defs.md#certificatetypedef)\]
- `AlpnPolicy`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateListenerOutputTypeDef](./type_defs.md#createlisteneroutputtypedef).

<a id="create_load_balancer"></a>

### create_load_balancer

Creates an Application Load Balancer, Network Load Balancer, or Gateway Load
Balancer.

Type annotations for `session.create_client("elbv2").create_load_balancer`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.create_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.create_load_balancer)

Asynchronous method. Use `await create_load_balancer(...)` for a synchronous
call.

Arguments mapping described in
[CreateLoadBalancerInputRequestTypeDef](./type_defs.md#createloadbalancerinputrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Subnets`: `Sequence`\[`str`\]
- `SubnetMappings`:
  `Sequence`\[[SubnetMappingTypeDef](./type_defs.md#subnetmappingtypedef)\]
- `SecurityGroups`: `Sequence`\[`str`\]
- `Scheme`:
  [LoadBalancerSchemeEnumType](./literals.md#loadbalancerschemeenumtype)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `Type`: [LoadBalancerTypeEnumType](./literals.md#loadbalancertypeenumtype)
- `IpAddressType`: [IpAddressTypeType](./literals.md#ipaddresstypetype)
- `CustomerOwnedIpv4Pool`: `str`

Returns a `Coroutine` for
[CreateLoadBalancerOutputTypeDef](./type_defs.md#createloadbalanceroutputtypedef).

<a id="create_rule"></a>

### create_rule

Creates a rule for the specified listener.

Type annotations for `session.create_client("elbv2").create_rule` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.create_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.create_rule)

Asynchronous method. Use `await create_rule(...)` for a synchronous call.

Arguments mapping described in
[CreateRuleInputRequestTypeDef](./type_defs.md#createruleinputrequesttypedef).

Keyword-only arguments:

- `ListenerArn`: `str` *(required)*
- `Conditions`:
  `Sequence`\[[RuleConditionTypeDef](./type_defs.md#ruleconditiontypedef)\]
  *(required)*
- `Priority`: `int` *(required)*
- `Actions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]
  *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateRuleOutputTypeDef](./type_defs.md#createruleoutputtypedef).

<a id="create_target_group"></a>

### create_target_group

Creates a target group.

Type annotations for `session.create_client("elbv2").create_target_group`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.create_target_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.create_target_group)

Asynchronous method. Use `await create_target_group(...)` for a synchronous
call.

Arguments mapping described in
[CreateTargetGroupInputRequestTypeDef](./type_defs.md#createtargetgroupinputrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Protocol`: [ProtocolEnumType](./literals.md#protocolenumtype)
- `ProtocolVersion`: `str`
- `Port`: `int`
- `VpcId`: `str`
- `HealthCheckProtocol`: [ProtocolEnumType](./literals.md#protocolenumtype)
- `HealthCheckPort`: `str`
- `HealthCheckEnabled`: `bool`
- `HealthCheckPath`: `str`
- `HealthCheckIntervalSeconds`: `int`
- `HealthCheckTimeoutSeconds`: `int`
- `HealthyThresholdCount`: `int`
- `UnhealthyThresholdCount`: `int`
- `Matcher`: [MatcherTypeDef](./type_defs.md#matchertypedef)
- `TargetType`: [TargetTypeEnumType](./literals.md#targettypeenumtype)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `IpAddressType`:
  [TargetGroupIpAddressTypeEnumType](./literals.md#targetgroupipaddresstypeenumtype)

Returns a `Coroutine` for
[CreateTargetGroupOutputTypeDef](./type_defs.md#createtargetgroupoutputtypedef).

<a id="delete_listener"></a>

### delete_listener

Deletes the specified listener.

Type annotations for `session.create_client("elbv2").delete_listener` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.delete_listener](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.delete_listener)

Asynchronous method. Use `await delete_listener(...)` for a synchronous call.

Arguments mapping described in
[DeleteListenerInputRequestTypeDef](./type_defs.md#deletelistenerinputrequesttypedef).

Keyword-only arguments:

- `ListenerArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_load_balancer"></a>

### delete_load_balancer

Deletes the specified Application Load Balancer, Network Load Balancer, or
Gateway Load Balancer.

Type annotations for `session.create_client("elbv2").delete_load_balancer`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.delete_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.delete_load_balancer)

Asynchronous method. Use `await delete_load_balancer(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLoadBalancerInputRequestTypeDef](./type_defs.md#deleteloadbalancerinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_rule"></a>

### delete_rule

Deletes the specified rule.

Type annotations for `session.create_client("elbv2").delete_rule` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.delete_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.delete_rule)

Asynchronous method. Use `await delete_rule(...)` for a synchronous call.

Arguments mapping described in
[DeleteRuleInputRequestTypeDef](./type_defs.md#deleteruleinputrequesttypedef).

Keyword-only arguments:

- `RuleArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_target_group"></a>

### delete_target_group

Deletes the specified target group.

Type annotations for `session.create_client("elbv2").delete_target_group`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.delete_target_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.delete_target_group)

Asynchronous method. Use `await delete_target_group(...)` for a synchronous
call.

Arguments mapping described in
[DeleteTargetGroupInputRequestTypeDef](./type_defs.md#deletetargetgroupinputrequesttypedef).

Keyword-only arguments:

- `TargetGroupArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deregister_targets"></a>

### deregister_targets

Deregisters the specified targets from the specified target group.

Type annotations for `session.create_client("elbv2").deregister_targets`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.deregister_targets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.deregister_targets)

Asynchronous method. Use `await deregister_targets(...)` for a synchronous
call.

Arguments mapping described in
[DeregisterTargetsInputRequestTypeDef](./type_defs.md#deregistertargetsinputrequesttypedef).

Keyword-only arguments:

- `TargetGroupArn`: `str` *(required)*
- `Targets`:
  `Sequence`\[[TargetDescriptionTypeDef](./type_defs.md#targetdescriptiontypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_account_limits"></a>

### describe_account_limits

Describes the current Elastic Load Balancing resource limits for your Amazon
Web Services account.

Type annotations for `session.create_client("elbv2").describe_account_limits`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_account_limits](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_account_limits)

Asynchronous method. Use `await describe_account_limits(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAccountLimitsInputRequestTypeDef](./type_defs.md#describeaccountlimitsinputrequesttypedef).

Keyword-only arguments:

- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeAccountLimitsOutputTypeDef](./type_defs.md#describeaccountlimitsoutputtypedef).

<a id="describe_listener_certificates"></a>

### describe_listener_certificates

Describes the default certificate and the certificate list for the specified
HTTPS or TLS listener.

Type annotations for
`session.create_client("elbv2").describe_listener_certificates` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_listener_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_listener_certificates)

Asynchronous method. Use `await describe_listener_certificates(...)` for a
synchronous call.

Arguments mapping described in
[DescribeListenerCertificatesInputRequestTypeDef](./type_defs.md#describelistenercertificatesinputrequesttypedef).

Keyword-only arguments:

- `ListenerArn`: `str` *(required)*
- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeListenerCertificatesOutputTypeDef](./type_defs.md#describelistenercertificatesoutputtypedef).

<a id="describe_listeners"></a>

### describe_listeners

Describes the specified listeners or the listeners for the specified
Application Load Balancer, Network Load Balancer, or Gateway Load Balancer.

Type annotations for `session.create_client("elbv2").describe_listeners`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_listeners](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_listeners)

Asynchronous method. Use `await describe_listeners(...)` for a synchronous
call.

Arguments mapping described in
[DescribeListenersInputRequestTypeDef](./type_defs.md#describelistenersinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str`
- `ListenerArns`: `Sequence`\[`str`\]
- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeListenersOutputTypeDef](./type_defs.md#describelistenersoutputtypedef).

<a id="describe_load_balancer_attributes"></a>

### describe_load_balancer_attributes

Describes the attributes for the specified Application Load Balancer, Network
Load Balancer, or Gateway Load Balancer.

Type annotations for
`session.create_client("elbv2").describe_load_balancer_attributes` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_load_balancer_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_load_balancer_attributes)

Asynchronous method. Use `await describe_load_balancer_attributes(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLoadBalancerAttributesInputRequestTypeDef](./type_defs.md#describeloadbalancerattributesinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLoadBalancerAttributesOutputTypeDef](./type_defs.md#describeloadbalancerattributesoutputtypedef).

<a id="describe_load_balancers"></a>

### describe_load_balancers

Describes the specified load balancers or all of your load balancers.

Type annotations for `session.create_client("elbv2").describe_load_balancers`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_load_balancers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_load_balancers)

Asynchronous method. Use `await describe_load_balancers(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLoadBalancersInputRequestTypeDef](./type_defs.md#describeloadbalancersinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArns`: `Sequence`\[`str`\]
- `Names`: `Sequence`\[`str`\]
- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeLoadBalancersOutputTypeDef](./type_defs.md#describeloadbalancersoutputtypedef).

<a id="describe_rules"></a>

### describe_rules

Describes the specified rules or the rules for the specified listener.

Type annotations for `session.create_client("elbv2").describe_rules` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_rules)

Asynchronous method. Use `await describe_rules(...)` for a synchronous call.

Arguments mapping described in
[DescribeRulesInputRequestTypeDef](./type_defs.md#describerulesinputrequesttypedef).

Keyword-only arguments:

- `ListenerArn`: `str`
- `RuleArns`: `Sequence`\[`str`\]
- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeRulesOutputTypeDef](./type_defs.md#describerulesoutputtypedef).

<a id="describe_ssl_policies"></a>

### describe_ssl_policies

Describes the specified policies or all policies used for SSL negotiation.

Type annotations for `session.create_client("elbv2").describe_ssl_policies`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_ssl_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_ssl_policies)

Asynchronous method. Use `await describe_ssl_policies(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSSLPoliciesInputRequestTypeDef](./type_defs.md#describesslpoliciesinputrequesttypedef).

Keyword-only arguments:

- `Names`: `Sequence`\[`str`\]
- `Marker`: `str`
- `PageSize`: `int`
- `LoadBalancerType`:
  [LoadBalancerTypeEnumType](./literals.md#loadbalancertypeenumtype)

Returns a `Coroutine` for
[DescribeSSLPoliciesOutputTypeDef](./type_defs.md#describesslpoliciesoutputtypedef).

<a id="describe_tags"></a>

### describe_tags

Describes the tags for the specified Elastic Load Balancing resources.

Type annotations for `session.create_client("elbv2").describe_tags` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_tags)

Asynchronous method. Use `await describe_tags(...)` for a synchronous call.

Arguments mapping described in
[DescribeTagsInputRequestTypeDef](./type_defs.md#describetagsinputrequesttypedef).

Keyword-only arguments:

- `ResourceArns`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DescribeTagsOutputTypeDef](./type_defs.md#describetagsoutputtypedef).

<a id="describe_target_group_attributes"></a>

### describe_target_group_attributes

Describes the attributes for the specified target group.

Type annotations for
`session.create_client("elbv2").describe_target_group_attributes` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_target_group_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_target_group_attributes)

Asynchronous method. Use `await describe_target_group_attributes(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTargetGroupAttributesInputRequestTypeDef](./type_defs.md#describetargetgroupattributesinputrequesttypedef).

Keyword-only arguments:

- `TargetGroupArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeTargetGroupAttributesOutputTypeDef](./type_defs.md#describetargetgroupattributesoutputtypedef).

<a id="describe_target_groups"></a>

### describe_target_groups

Describes the specified target groups or all of your target groups.

Type annotations for `session.create_client("elbv2").describe_target_groups`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_target_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_target_groups)

Asynchronous method. Use `await describe_target_groups(...)` for a synchronous
call.

Arguments mapping described in
[DescribeTargetGroupsInputRequestTypeDef](./type_defs.md#describetargetgroupsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str`
- `TargetGroupArns`: `Sequence`\[`str`\]
- `Names`: `Sequence`\[`str`\]
- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeTargetGroupsOutputTypeDef](./type_defs.md#describetargetgroupsoutputtypedef).

<a id="describe_target_health"></a>

### describe_target_health

Describes the health of the specified targets or all of your targets.

Type annotations for `session.create_client("elbv2").describe_target_health`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.describe_target_health](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.describe_target_health)

Asynchronous method. Use `await describe_target_health(...)` for a synchronous
call.

Arguments mapping described in
[DescribeTargetHealthInputRequestTypeDef](./type_defs.md#describetargethealthinputrequesttypedef).

Keyword-only arguments:

- `TargetGroupArn`: `str` *(required)*
- `Targets`:
  `Sequence`\[[TargetDescriptionTypeDef](./type_defs.md#targetdescriptiontypedef)\]

Returns a `Coroutine` for
[DescribeTargetHealthOutputTypeDef](./type_defs.md#describetargethealthoutputtypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("elbv2").generate_presigned_url`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="modify_listener"></a>

### modify_listener

Replaces the specified properties of the specified listener.

Type annotations for `session.create_client("elbv2").modify_listener` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.modify_listener](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.modify_listener)

Asynchronous method. Use `await modify_listener(...)` for a synchronous call.

Arguments mapping described in
[ModifyListenerInputRequestTypeDef](./type_defs.md#modifylistenerinputrequesttypedef).

Keyword-only arguments:

- `ListenerArn`: `str` *(required)*
- `Port`: `int`
- `Protocol`: [ProtocolEnumType](./literals.md#protocolenumtype)
- `SslPolicy`: `str`
- `Certificates`:
  `Sequence`\[[CertificateTypeDef](./type_defs.md#certificatetypedef)\]
- `DefaultActions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]
- `AlpnPolicy`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ModifyListenerOutputTypeDef](./type_defs.md#modifylisteneroutputtypedef).

<a id="modify_load_balancer_attributes"></a>

### modify_load_balancer_attributes

Modifies the specified attributes of the specified Application Load Balancer,
Network Load Balancer, or Gateway Load Balancer.

Type annotations for
`session.create_client("elbv2").modify_load_balancer_attributes` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.modify_load_balancer_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.modify_load_balancer_attributes)

Asynchronous method. Use `await modify_load_balancer_attributes(...)` for a
synchronous call.

Arguments mapping described in
[ModifyLoadBalancerAttributesInputRequestTypeDef](./type_defs.md#modifyloadbalancerattributesinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str` *(required)*
- `Attributes`:
  `Sequence`\[[LoadBalancerAttributeTypeDef](./type_defs.md#loadbalancerattributetypedef)\]
  *(required)*

Returns a `Coroutine` for
[ModifyLoadBalancerAttributesOutputTypeDef](./type_defs.md#modifyloadbalancerattributesoutputtypedef).

<a id="modify_rule"></a>

### modify_rule

Replaces the specified properties of the specified rule.

Type annotations for `session.create_client("elbv2").modify_rule` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.modify_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.modify_rule)

Asynchronous method. Use `await modify_rule(...)` for a synchronous call.

Arguments mapping described in
[ModifyRuleInputRequestTypeDef](./type_defs.md#modifyruleinputrequesttypedef).

Keyword-only arguments:

- `RuleArn`: `str` *(required)*
- `Conditions`:
  `Sequence`\[[RuleConditionTypeDef](./type_defs.md#ruleconditiontypedef)\]
- `Actions`: `Sequence`\[[ActionTypeDef](./type_defs.md#actiontypedef)\]

Returns a `Coroutine` for
[ModifyRuleOutputTypeDef](./type_defs.md#modifyruleoutputtypedef).

<a id="modify_target_group"></a>

### modify_target_group

Modifies the health checks used when evaluating the health state of the targets
in the specified target group.

Type annotations for `session.create_client("elbv2").modify_target_group`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.modify_target_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.modify_target_group)

Asynchronous method. Use `await modify_target_group(...)` for a synchronous
call.

Arguments mapping described in
[ModifyTargetGroupInputRequestTypeDef](./type_defs.md#modifytargetgroupinputrequesttypedef).

Keyword-only arguments:

- `TargetGroupArn`: `str` *(required)*
- `HealthCheckProtocol`: [ProtocolEnumType](./literals.md#protocolenumtype)
- `HealthCheckPort`: `str`
- `HealthCheckPath`: `str`
- `HealthCheckEnabled`: `bool`
- `HealthCheckIntervalSeconds`: `int`
- `HealthCheckTimeoutSeconds`: `int`
- `HealthyThresholdCount`: `int`
- `UnhealthyThresholdCount`: `int`
- `Matcher`: [MatcherTypeDef](./type_defs.md#matchertypedef)

Returns a `Coroutine` for
[ModifyTargetGroupOutputTypeDef](./type_defs.md#modifytargetgroupoutputtypedef).

<a id="modify_target_group_attributes"></a>

### modify_target_group_attributes

Modifies the specified attributes of the specified target group.

Type annotations for
`session.create_client("elbv2").modify_target_group_attributes` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.modify_target_group_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.modify_target_group_attributes)

Asynchronous method. Use `await modify_target_group_attributes(...)` for a
synchronous call.

Arguments mapping described in
[ModifyTargetGroupAttributesInputRequestTypeDef](./type_defs.md#modifytargetgroupattributesinputrequesttypedef).

Keyword-only arguments:

- `TargetGroupArn`: `str` *(required)*
- `Attributes`:
  `Sequence`\[[TargetGroupAttributeTypeDef](./type_defs.md#targetgroupattributetypedef)\]
  *(required)*

Returns a `Coroutine` for
[ModifyTargetGroupAttributesOutputTypeDef](./type_defs.md#modifytargetgroupattributesoutputtypedef).

<a id="register_targets"></a>

### register_targets

Registers the specified targets with the specified target group.

Type annotations for `session.create_client("elbv2").register_targets` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.register_targets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.register_targets)

Asynchronous method. Use `await register_targets(...)` for a synchronous call.

Arguments mapping described in
[RegisterTargetsInputRequestTypeDef](./type_defs.md#registertargetsinputrequesttypedef).

Keyword-only arguments:

- `TargetGroupArn`: `str` *(required)*
- `Targets`:
  `Sequence`\[[TargetDescriptionTypeDef](./type_defs.md#targetdescriptiontypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="remove_listener_certificates"></a>

### remove_listener_certificates

Removes the specified certificate from the certificate list for the specified
HTTPS or TLS listener.

Type annotations for
`session.create_client("elbv2").remove_listener_certificates` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.remove_listener_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.remove_listener_certificates)

Asynchronous method. Use `await remove_listener_certificates(...)` for a
synchronous call.

Arguments mapping described in
[RemoveListenerCertificatesInputRequestTypeDef](./type_defs.md#removelistenercertificatesinputrequesttypedef).

Keyword-only arguments:

- `ListenerArn`: `str` *(required)*
- `Certificates`:
  `Sequence`\[[CertificateTypeDef](./type_defs.md#certificatetypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="remove_tags"></a>

### remove_tags

Removes the specified tags from the specified Elastic Load Balancing resources.

Type annotations for `session.create_client("elbv2").remove_tags` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.remove_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.remove_tags)

Asynchronous method. Use `await remove_tags(...)` for a synchronous call.

Arguments mapping described in
[RemoveTagsInputRequestTypeDef](./type_defs.md#removetagsinputrequesttypedef).

Keyword-only arguments:

- `ResourceArns`: `Sequence`\[`str`\] *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="set_ip_address_type"></a>

### set_ip_address_type

Sets the type of IP addresses used by the subnets of the specified Application
Load Balancer or Network Load Balancer.

Type annotations for `session.create_client("elbv2").set_ip_address_type`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.set_ip_address_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.set_ip_address_type)

Asynchronous method. Use `await set_ip_address_type(...)` for a synchronous
call.

Arguments mapping described in
[SetIpAddressTypeInputRequestTypeDef](./type_defs.md#setipaddresstypeinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str` *(required)*
- `IpAddressType`: [IpAddressTypeType](./literals.md#ipaddresstypetype)
  *(required)*

Returns a `Coroutine` for
[SetIpAddressTypeOutputTypeDef](./type_defs.md#setipaddresstypeoutputtypedef).

<a id="set_rule_priorities"></a>

### set_rule_priorities

Sets the priorities of the specified rules.

Type annotations for `session.create_client("elbv2").set_rule_priorities`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.set_rule_priorities](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.set_rule_priorities)

Asynchronous method. Use `await set_rule_priorities(...)` for a synchronous
call.

Arguments mapping described in
[SetRulePrioritiesInputRequestTypeDef](./type_defs.md#setruleprioritiesinputrequesttypedef).

Keyword-only arguments:

- `RulePriorities`:
  `Sequence`\[[RulePriorityPairTypeDef](./type_defs.md#ruleprioritypairtypedef)\]
  *(required)*

Returns a `Coroutine` for
[SetRulePrioritiesOutputTypeDef](./type_defs.md#setruleprioritiesoutputtypedef).

<a id="set_security_groups"></a>

### set_security_groups

Associates the specified security groups with the specified Application Load
Balancer.

Type annotations for `session.create_client("elbv2").set_security_groups`
method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.set_security_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.set_security_groups)

Asynchronous method. Use `await set_security_groups(...)` for a synchronous
call.

Arguments mapping described in
[SetSecurityGroupsInputRequestTypeDef](./type_defs.md#setsecuritygroupsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str` *(required)*
- `SecurityGroups`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[SetSecurityGroupsOutputTypeDef](./type_defs.md#setsecuritygroupsoutputtypedef).

<a id="set_subnets"></a>

### set_subnets

Enables the Availability Zones for the specified public subnets for the
specified Application Load Balancer or Network Load Balancer.

Type annotations for `session.create_client("elbv2").set_subnets` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.set_subnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.set_subnets)

Asynchronous method. Use `await set_subnets(...)` for a synchronous call.

Arguments mapping described in
[SetSubnetsInputRequestTypeDef](./type_defs.md#setsubnetsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerArn`: `str` *(required)*
- `Subnets`: `Sequence`\[`str`\]
- `SubnetMappings`:
  `Sequence`\[[SubnetMappingTypeDef](./type_defs.md#subnetmappingtypedef)\]
- `IpAddressType`: [IpAddressTypeType](./literals.md#ipaddresstypetype)

Returns a `Coroutine` for
[SetSubnetsOutputTypeDef](./type_defs.md#setsubnetsoutputtypedef).

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("elbv2").__aenter__` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for
[ElasticLoadBalancingv2Client](#elasticloadbalancingv2client).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("elbv2").__aexit__` method.

Boto3 documentation:
[ElasticLoadBalancingv2.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elbv2.html#ElasticLoadBalancingv2.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("elbv2").get_paginator` method with
overloads.

- `client.get_paginator("describe_account_limits")` ->
  [DescribeAccountLimitsPaginator](./paginators.md#describeaccountlimitspaginator)
- `client.get_paginator("describe_listener_certificates")` ->
  [DescribeListenerCertificatesPaginator](./paginators.md#describelistenercertificatespaginator)
- `client.get_paginator("describe_listeners")` ->
  [DescribeListenersPaginator](./paginators.md#describelistenerspaginator)
- `client.get_paginator("describe_load_balancers")` ->
  [DescribeLoadBalancersPaginator](./paginators.md#describeloadbalancerspaginator)
- `client.get_paginator("describe_rules")` ->
  [DescribeRulesPaginator](./paginators.md#describerulespaginator)
- `client.get_paginator("describe_ssl_policies")` ->
  [DescribeSSLPoliciesPaginator](./paginators.md#describesslpoliciespaginator)
- `client.get_paginator("describe_target_groups")` ->
  [DescribeTargetGroupsPaginator](./paginators.md#describetargetgroupspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("elbv2").get_waiter` method with
overloads.

- `client.get_waiter("load_balancer_available")` ->
  [LoadBalancerAvailableWaiter](./waiters.md#loadbalanceravailablewaiter)
- `client.get_waiter("load_balancer_exists")` ->
  [LoadBalancerExistsWaiter](./waiters.md#loadbalancerexistswaiter)
- `client.get_waiter("load_balancers_deleted")` ->
  [LoadBalancersDeletedWaiter](./waiters.md#loadbalancersdeletedwaiter)
- `client.get_waiter("target_deregistered")` ->
  [TargetDeregisteredWaiter](./waiters.md#targetderegisteredwaiter)
- `client.get_waiter("target_in_service")` ->
  [TargetInServiceWaiter](./waiters.md#targetinservicewaiter)
