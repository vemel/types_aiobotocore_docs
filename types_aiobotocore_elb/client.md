<a id="elasticloadbalancingclient-for-aiobotocore-elasticloadbalancing-module"></a>

# ElasticLoadBalancingClient for aiobotocore ElasticLoadBalancing module

> [Index](..) > [ElasticLoadBalancing](.) > ElasticLoadBalancingClient

Auto-generated documentation for
[ElasticLoadBalancing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing)
type annotations stubs module
[types-aiobotocore-elb](https://pypi.org/project/types-aiobotocore-elb/).

- [ElasticLoadBalancingClient for aiobotocore ElasticLoadBalancing module](#elasticloadbalancingclient-for-aiobotocore-elasticloadbalancing-module)
  - [ElasticLoadBalancingClient](#elasticloadbalancingclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [add_tags](#add_tags)
    - [apply_security_groups_to_load_balancer](#apply_security_groups_to_load_balancer)
    - [attach_load_balancer_to_subnets](#attach_load_balancer_to_subnets)
    - [can_paginate](#can_paginate)
    - [configure_health_check](#configure_health_check)
    - [create_app_cookie_stickiness_policy](#create_app_cookie_stickiness_policy)
    - [create_lb_cookie_stickiness_policy](#create_lb_cookie_stickiness_policy)
    - [create_load_balancer](#create_load_balancer)
    - [create_load_balancer_listeners](#create_load_balancer_listeners)
    - [create_load_balancer_policy](#create_load_balancer_policy)
    - [delete_load_balancer](#delete_load_balancer)
    - [delete_load_balancer_listeners](#delete_load_balancer_listeners)
    - [delete_load_balancer_policy](#delete_load_balancer_policy)
    - [deregister_instances_from_load_balancer](#deregister_instances_from_load_balancer)
    - [describe_account_limits](#describe_account_limits)
    - [describe_instance_health](#describe_instance_health)
    - [describe_load_balancer_attributes](#describe_load_balancer_attributes)
    - [describe_load_balancer_policies](#describe_load_balancer_policies)
    - [describe_load_balancer_policy_types](#describe_load_balancer_policy_types)
    - [describe_load_balancers](#describe_load_balancers)
    - [describe_tags](#describe_tags)
    - [detach_load_balancer_from_subnets](#detach_load_balancer_from_subnets)
    - [disable_availability_zones_for_load_balancer](#disable_availability_zones_for_load_balancer)
    - [enable_availability_zones_for_load_balancer](#enable_availability_zones_for_load_balancer)
    - [generate_presigned_url](#generate_presigned_url)
    - [modify_load_balancer_attributes](#modify_load_balancer_attributes)
    - [register_instances_with_load_balancer](#register_instances_with_load_balancer)
    - [remove_tags](#remove_tags)
    - [set_load_balancer_listener_ssl_certificate](#set_load_balancer_listener_ssl_certificate)
    - [set_load_balancer_policies_for_backend_server](#set_load_balancer_policies_for_backend_server)
    - [set_load_balancer_policies_of_listener](#set_load_balancer_policies_of_listener)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="elasticloadbalancingclient"></a>

## ElasticLoadBalancingClient

Type annotations for `session.create_client("elb")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_elb.client import ElasticLoadBalancingClient

session = get_session()
async with session.create_client("elb") as client:
    client: ElasticLoadBalancingClient
```

Boto3 documentation:
[ElasticLoadBalancing.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_elb.client import Exceptions

def handle_error(exc: Exceptions.AccessPointNotFoundException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessPointNotFoundException`
- `Exceptions.CertificateNotFoundException`
- `Exceptions.ClientError`
- `Exceptions.DependencyThrottleException`
- `Exceptions.DuplicateAccessPointNameException`
- `Exceptions.DuplicateListenerException`
- `Exceptions.DuplicatePolicyNameException`
- `Exceptions.DuplicateTagKeysException`
- `Exceptions.InvalidConfigurationRequestException`
- `Exceptions.InvalidEndPointException`
- `Exceptions.InvalidSchemeException`
- `Exceptions.InvalidSecurityGroupException`
- `Exceptions.InvalidSubnetException`
- `Exceptions.ListenerNotFoundException`
- `Exceptions.LoadBalancerAttributeNotFoundException`
- `Exceptions.OperationNotPermittedException`
- `Exceptions.PolicyNotFoundException`
- `Exceptions.PolicyTypeNotFoundException`
- `Exceptions.SubnetNotFoundException`
- `Exceptions.TooManyAccessPointsException`
- `Exceptions.TooManyPoliciesException`
- `Exceptions.TooManyTagsException`
- `Exceptions.UnsupportedProtocolException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

ElasticLoadBalancingClient exceptions.

Type annotations for `session.create_client("elb").exceptions` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="add_tags"></a>

### add_tags

Adds the specified tags to the specified load balancer.

Type annotations for `session.create_client("elb").add_tags` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.add_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.add_tags)

Asynchronous method. Use `await add_tags(...)` for a synchronous call.

Arguments mapping described in
[AddTagsInputRequestTypeDef](./type_defs.md#addtagsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerNames`: `Sequence`\[`str`\] *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="apply_security_groups_to_load_balancer"></a>

### apply_security_groups_to_load_balancer

Associates one or more security groups with your load balancer in a virtual
private cloud (VPC).

Type annotations for
`session.create_client("elb").apply_security_groups_to_load_balancer` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.apply_security_groups_to_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.apply_security_groups_to_load_balancer)

Asynchronous method. Use `await apply_security_groups_to_load_balancer(...)`
for a synchronous call.

Arguments mapping described in
[ApplySecurityGroupsToLoadBalancerInputRequestTypeDef](./type_defs.md#applysecuritygroupstoloadbalancerinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `SecurityGroups`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[ApplySecurityGroupsToLoadBalancerOutputTypeDef](./type_defs.md#applysecuritygroupstoloadbalanceroutputtypedef).

<a id="attach_load_balancer_to_subnets"></a>

### attach_load_balancer_to_subnets

Adds one or more subnets to the set of configured subnets for the specified
load balancer.

Type annotations for
`session.create_client("elb").attach_load_balancer_to_subnets` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.attach_load_balancer_to_subnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.attach_load_balancer_to_subnets)

Asynchronous method. Use `await attach_load_balancer_to_subnets(...)` for a
synchronous call.

Arguments mapping described in
[AttachLoadBalancerToSubnetsInputRequestTypeDef](./type_defs.md#attachloadbalancertosubnetsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `Subnets`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[AttachLoadBalancerToSubnetsOutputTypeDef](./type_defs.md#attachloadbalancertosubnetsoutputtypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("elb").can_paginate` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="configure_health_check"></a>

### configure_health_check

Specifies the health check settings to use when evaluating the health state of
your EC2 instances.

Type annotations for `session.create_client("elb").configure_health_check`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.configure_health_check](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.configure_health_check)

Asynchronous method. Use `await configure_health_check(...)` for a synchronous
call.

Arguments mapping described in
[ConfigureHealthCheckInputRequestTypeDef](./type_defs.md#configurehealthcheckinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `HealthCheck`: [HealthCheckTypeDef](./type_defs.md#healthchecktypedef)
  *(required)*

Returns a `Coroutine` for
[ConfigureHealthCheckOutputTypeDef](./type_defs.md#configurehealthcheckoutputtypedef).

<a id="create_app_cookie_stickiness_policy"></a>

### create_app_cookie_stickiness_policy

Generates a stickiness policy with sticky session lifetimes that follow that of
an application-generated cookie.

Type annotations for
`session.create_client("elb").create_app_cookie_stickiness_policy` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.create_app_cookie_stickiness_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.create_app_cookie_stickiness_policy)

Asynchronous method. Use `await create_app_cookie_stickiness_policy(...)` for a
synchronous call.

Arguments mapping described in
[CreateAppCookieStickinessPolicyInputRequestTypeDef](./type_defs.md#createappcookiestickinesspolicyinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `PolicyName`: `str` *(required)*
- `CookieName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_lb_cookie_stickiness_policy"></a>

### create_lb_cookie_stickiness_policy

Generates a stickiness policy with sticky session lifetimes controlled by the
lifetime of the browser (user-agent) or a specified expiration period.

Type annotations for
`session.create_client("elb").create_lb_cookie_stickiness_policy` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.create_lb_cookie_stickiness_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.create_lb_cookie_stickiness_policy)

Asynchronous method. Use `await create_lb_cookie_stickiness_policy(...)` for a
synchronous call.

Arguments mapping described in
[CreateLBCookieStickinessPolicyInputRequestTypeDef](./type_defs.md#createlbcookiestickinesspolicyinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `PolicyName`: `str` *(required)*
- `CookieExpirationPeriod`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_load_balancer"></a>

### create_load_balancer

Creates a Classic Load Balancer.

Type annotations for `session.create_client("elb").create_load_balancer`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.create_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.create_load_balancer)

Asynchronous method. Use `await create_load_balancer(...)` for a synchronous
call.

Arguments mapping described in
[CreateAccessPointInputRequestTypeDef](./type_defs.md#createaccesspointinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `Listeners`: `Sequence`\[[ListenerTypeDef](./type_defs.md#listenertypedef)\]
  *(required)*
- `AvailabilityZones`: `Sequence`\[`str`\]
- `Subnets`: `Sequence`\[`str`\]
- `SecurityGroups`: `Sequence`\[`str`\]
- `Scheme`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateAccessPointOutputTypeDef](./type_defs.md#createaccesspointoutputtypedef).

<a id="create_load_balancer_listeners"></a>

### create_load_balancer_listeners

Creates one or more listeners for the specified load balancer.

Type annotations for
`session.create_client("elb").create_load_balancer_listeners` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.create_load_balancer_listeners](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.create_load_balancer_listeners)

Asynchronous method. Use `await create_load_balancer_listeners(...)` for a
synchronous call.

Arguments mapping described in
[CreateLoadBalancerListenerInputRequestTypeDef](./type_defs.md#createloadbalancerlistenerinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `Listeners`: `Sequence`\[[ListenerTypeDef](./type_defs.md#listenertypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_load_balancer_policy"></a>

### create_load_balancer_policy

Creates a policy with the specified attributes for the specified load balancer.

Type annotations for `session.create_client("elb").create_load_balancer_policy`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.create_load_balancer_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.create_load_balancer_policy)

Asynchronous method. Use `await create_load_balancer_policy(...)` for a
synchronous call.

Arguments mapping described in
[CreateLoadBalancerPolicyInputRequestTypeDef](./type_defs.md#createloadbalancerpolicyinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `PolicyName`: `str` *(required)*
- `PolicyTypeName`: `str` *(required)*
- `PolicyAttributes`:
  `Sequence`\[[PolicyAttributeTypeDef](./type_defs.md#policyattributetypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_load_balancer"></a>

### delete_load_balancer

Deletes the specified load balancer.

Type annotations for `session.create_client("elb").delete_load_balancer`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.delete_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.delete_load_balancer)

Asynchronous method. Use `await delete_load_balancer(...)` for a synchronous
call.

Arguments mapping described in
[DeleteAccessPointInputRequestTypeDef](./type_defs.md#deleteaccesspointinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_load_balancer_listeners"></a>

### delete_load_balancer_listeners

Deletes the specified listeners from the specified load balancer.

Type annotations for
`session.create_client("elb").delete_load_balancer_listeners` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.delete_load_balancer_listeners](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.delete_load_balancer_listeners)

Asynchronous method. Use `await delete_load_balancer_listeners(...)` for a
synchronous call.

Arguments mapping described in
[DeleteLoadBalancerListenerInputRequestTypeDef](./type_defs.md#deleteloadbalancerlistenerinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `LoadBalancerPorts`: `Sequence`\[`int`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_load_balancer_policy"></a>

### delete_load_balancer_policy

Deletes the specified policy from the specified load balancer.

Type annotations for `session.create_client("elb").delete_load_balancer_policy`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.delete_load_balancer_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.delete_load_balancer_policy)

Asynchronous method. Use `await delete_load_balancer_policy(...)` for a
synchronous call.

Arguments mapping described in
[DeleteLoadBalancerPolicyInputRequestTypeDef](./type_defs.md#deleteloadbalancerpolicyinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `PolicyName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="deregister_instances_from_load_balancer"></a>

### deregister_instances_from_load_balancer

Deregisters the specified instances from the specified load balancer.

Type annotations for
`session.create_client("elb").deregister_instances_from_load_balancer` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.deregister_instances_from_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.deregister_instances_from_load_balancer)

Asynchronous method. Use `await deregister_instances_from_load_balancer(...)`
for a synchronous call.

Arguments mapping described in
[DeregisterEndPointsInputRequestTypeDef](./type_defs.md#deregisterendpointsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `Instances`: `Sequence`\[[InstanceTypeDef](./type_defs.md#instancetypedef)\]
  *(required)*

Returns a `Coroutine` for
[DeregisterEndPointsOutputTypeDef](./type_defs.md#deregisterendpointsoutputtypedef).

<a id="describe_account_limits"></a>

### describe_account_limits

Describes the current Elastic Load Balancing resource limits for your AWS
account.

Type annotations for `session.create_client("elb").describe_account_limits`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.describe_account_limits](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.describe_account_limits)

Asynchronous method. Use `await describe_account_limits(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAccountLimitsInputRequestTypeDef](./type_defs.md#describeaccountlimitsinputrequesttypedef).

Keyword-only arguments:

- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeAccountLimitsOutputTypeDef](./type_defs.md#describeaccountlimitsoutputtypedef).

<a id="describe_instance_health"></a>

### describe_instance_health

Describes the state of the specified instances with respect to the specified
load balancer.

Type annotations for `session.create_client("elb").describe_instance_health`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.describe_instance_health](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.describe_instance_health)

Asynchronous method. Use `await describe_instance_health(...)` for a
synchronous call.

Arguments mapping described in
[DescribeEndPointStateInputRequestTypeDef](./type_defs.md#describeendpointstateinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `Instances`: `Sequence`\[[InstanceTypeDef](./type_defs.md#instancetypedef)\]

Returns a `Coroutine` for
[DescribeEndPointStateOutputTypeDef](./type_defs.md#describeendpointstateoutputtypedef).

<a id="describe_load_balancer_attributes"></a>

### describe_load_balancer_attributes

Describes the attributes for the specified load balancer.

Type annotations for
`session.create_client("elb").describe_load_balancer_attributes` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.describe_load_balancer_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.describe_load_balancer_attributes)

Asynchronous method. Use `await describe_load_balancer_attributes(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLoadBalancerAttributesInputRequestTypeDef](./type_defs.md#describeloadbalancerattributesinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeLoadBalancerAttributesOutputTypeDef](./type_defs.md#describeloadbalancerattributesoutputtypedef).

<a id="describe_load_balancer_policies"></a>

### describe_load_balancer_policies

Describes the specified policies.

Type annotations for
`session.create_client("elb").describe_load_balancer_policies` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.describe_load_balancer_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.describe_load_balancer_policies)

Asynchronous method. Use `await describe_load_balancer_policies(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLoadBalancerPoliciesInputRequestTypeDef](./type_defs.md#describeloadbalancerpoliciesinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str`
- `PolicyNames`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeLoadBalancerPoliciesOutputTypeDef](./type_defs.md#describeloadbalancerpoliciesoutputtypedef).

<a id="describe_load_balancer_policy_types"></a>

### describe_load_balancer_policy_types

Describes the specified load balancer policy types or all load balancer policy
types.

Type annotations for
`session.create_client("elb").describe_load_balancer_policy_types` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.describe_load_balancer_policy_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.describe_load_balancer_policy_types)

Asynchronous method. Use `await describe_load_balancer_policy_types(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLoadBalancerPolicyTypesInputRequestTypeDef](./type_defs.md#describeloadbalancerpolicytypesinputrequesttypedef).

Keyword-only arguments:

- `PolicyTypeNames`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeLoadBalancerPolicyTypesOutputTypeDef](./type_defs.md#describeloadbalancerpolicytypesoutputtypedef).

<a id="describe_load_balancers"></a>

### describe_load_balancers

Describes the specified the load balancers.

Type annotations for `session.create_client("elb").describe_load_balancers`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.describe_load_balancers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.describe_load_balancers)

Asynchronous method. Use `await describe_load_balancers(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAccessPointsInputRequestTypeDef](./type_defs.md#describeaccesspointsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerNames`: `Sequence`\[`str`\]
- `Marker`: `str`
- `PageSize`: `int`

Returns a `Coroutine` for
[DescribeAccessPointsOutputTypeDef](./type_defs.md#describeaccesspointsoutputtypedef).

<a id="describe_tags"></a>

### describe_tags

Describes the tags associated with the specified load balancers.

Type annotations for `session.create_client("elb").describe_tags` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.describe_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.describe_tags)

Asynchronous method. Use `await describe_tags(...)` for a synchronous call.

Arguments mapping described in
[DescribeTagsInputRequestTypeDef](./type_defs.md#describetagsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DescribeTagsOutputTypeDef](./type_defs.md#describetagsoutputtypedef).

<a id="detach_load_balancer_from_subnets"></a>

### detach_load_balancer_from_subnets

Removes the specified subnets from the set of configured subnets for the load
balancer.

Type annotations for
`session.create_client("elb").detach_load_balancer_from_subnets` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.detach_load_balancer_from_subnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.detach_load_balancer_from_subnets)

Asynchronous method. Use `await detach_load_balancer_from_subnets(...)` for a
synchronous call.

Arguments mapping described in
[DetachLoadBalancerFromSubnetsInputRequestTypeDef](./type_defs.md#detachloadbalancerfromsubnetsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `Subnets`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[DetachLoadBalancerFromSubnetsOutputTypeDef](./type_defs.md#detachloadbalancerfromsubnetsoutputtypedef).

<a id="disable_availability_zones_for_load_balancer"></a>

### disable_availability_zones_for_load_balancer

Removes the specified Availability Zones from the set of Availability Zones for
the specified load balancer in EC2-Classic or a default VPC.

Type annotations for
`session.create_client("elb").disable_availability_zones_for_load_balancer`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.disable_availability_zones_for_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.disable_availability_zones_for_load_balancer)

Asynchronous method. Use
`await disable_availability_zones_for_load_balancer(...)` for a synchronous
call.

Arguments mapping described in
[RemoveAvailabilityZonesInputRequestTypeDef](./type_defs.md#removeavailabilityzonesinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `AvailabilityZones`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[RemoveAvailabilityZonesOutputTypeDef](./type_defs.md#removeavailabilityzonesoutputtypedef).

<a id="enable_availability_zones_for_load_balancer"></a>

### enable_availability_zones_for_load_balancer

Adds the specified Availability Zones to the set of Availability Zones for the
specified load balancer in EC2-Classic or a default VPC.

Type annotations for
`session.create_client("elb").enable_availability_zones_for_load_balancer`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.enable_availability_zones_for_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.enable_availability_zones_for_load_balancer)

Asynchronous method. Use
`await enable_availability_zones_for_load_balancer(...)` for a synchronous
call.

Arguments mapping described in
[AddAvailabilityZonesInputRequestTypeDef](./type_defs.md#addavailabilityzonesinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `AvailabilityZones`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[AddAvailabilityZonesOutputTypeDef](./type_defs.md#addavailabilityzonesoutputtypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("elb").generate_presigned_url`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="modify_load_balancer_attributes"></a>

### modify_load_balancer_attributes

Modifies the attributes of the specified load balancer.

Type annotations for
`session.create_client("elb").modify_load_balancer_attributes` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.modify_load_balancer_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.modify_load_balancer_attributes)

Asynchronous method. Use `await modify_load_balancer_attributes(...)` for a
synchronous call.

Arguments mapping described in
[ModifyLoadBalancerAttributesInputRequestTypeDef](./type_defs.md#modifyloadbalancerattributesinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `LoadBalancerAttributes`:
  [LoadBalancerAttributesTypeDef](./type_defs.md#loadbalancerattributestypedef)
  *(required)*

Returns a `Coroutine` for
[ModifyLoadBalancerAttributesOutputTypeDef](./type_defs.md#modifyloadbalancerattributesoutputtypedef).

<a id="register_instances_with_load_balancer"></a>

### register_instances_with_load_balancer

Adds the specified instances to the specified load balancer.

Type annotations for
`session.create_client("elb").register_instances_with_load_balancer` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.register_instances_with_load_balancer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.register_instances_with_load_balancer)

Asynchronous method. Use `await register_instances_with_load_balancer(...)` for
a synchronous call.

Arguments mapping described in
[RegisterEndPointsInputRequestTypeDef](./type_defs.md#registerendpointsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `Instances`: `Sequence`\[[InstanceTypeDef](./type_defs.md#instancetypedef)\]
  *(required)*

Returns a `Coroutine` for
[RegisterEndPointsOutputTypeDef](./type_defs.md#registerendpointsoutputtypedef).

<a id="remove_tags"></a>

### remove_tags

Removes one or more tags from the specified load balancer.

Type annotations for `session.create_client("elb").remove_tags` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.remove_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.remove_tags)

Asynchronous method. Use `await remove_tags(...)` for a synchronous call.

Arguments mapping described in
[RemoveTagsInputRequestTypeDef](./type_defs.md#removetagsinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerNames`: `Sequence`\[`str`\] *(required)*
- `Tags`: `Sequence`\[[TagKeyOnlyTypeDef](./type_defs.md#tagkeyonlytypedef)\]
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="set_load_balancer_listener_ssl_certificate"></a>

### set_load_balancer_listener_ssl_certificate

Sets the certificate that terminates the specified listener's SSL connections.

Type annotations for
`session.create_client("elb").set_load_balancer_listener_ssl_certificate`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.set_load_balancer_listener_ssl_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.set_load_balancer_listener_ssl_certificate)

Asynchronous method. Use
`await set_load_balancer_listener_ssl_certificate(...)` for a synchronous call.

Arguments mapping described in
[SetLoadBalancerListenerSSLCertificateInputRequestTypeDef](./type_defs.md#setloadbalancerlistenersslcertificateinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `LoadBalancerPort`: `int` *(required)*
- `SSLCertificateId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="set_load_balancer_policies_for_backend_server"></a>

### set_load_balancer_policies_for_backend_server

Replaces the set of policies associated with the specified port on which the
EC2 instance is listening with a new set of policies.

Type annotations for
`session.create_client("elb").set_load_balancer_policies_for_backend_server`
method.

Boto3 documentation:
[ElasticLoadBalancing.Client.set_load_balancer_policies_for_backend_server](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.set_load_balancer_policies_for_backend_server)

Asynchronous method. Use
`await set_load_balancer_policies_for_backend_server(...)` for a synchronous
call.

Arguments mapping described in
[SetLoadBalancerPoliciesForBackendServerInputRequestTypeDef](./type_defs.md#setloadbalancerpoliciesforbackendserverinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `InstancePort`: `int` *(required)*
- `PolicyNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="set_load_balancer_policies_of_listener"></a>

### set_load_balancer_policies_of_listener

Replaces the current set of policies for the specified load balancer port with
the specified set of policies.

Type annotations for
`session.create_client("elb").set_load_balancer_policies_of_listener` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.set_load_balancer_policies_of_listener](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.set_load_balancer_policies_of_listener)

Asynchronous method. Use `await set_load_balancer_policies_of_listener(...)`
for a synchronous call.

Arguments mapping described in
[SetLoadBalancerPoliciesOfListenerInputRequestTypeDef](./type_defs.md#setloadbalancerpoliciesoflistenerinputrequesttypedef).

Keyword-only arguments:

- `LoadBalancerName`: `str` *(required)*
- `LoadBalancerPort`: `int` *(required)*
- `PolicyNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("elb").__aenter__` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for
[ElasticLoadBalancingClient](#elasticloadbalancingclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("elb").__aexit__` method.

Boto3 documentation:
[ElasticLoadBalancing.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("elb").get_paginator` method with
overloads.

- `client.get_paginator("describe_account_limits")` ->
  [DescribeAccountLimitsPaginator](./paginators.md#describeaccountlimitspaginator)
- `client.get_paginator("describe_load_balancers")` ->
  [DescribeLoadBalancersPaginator](./paginators.md#describeloadbalancerspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `session.create_client("elb").get_waiter` method with
overloads.

- `client.get_waiter("any_instance_in_service")` ->
  [AnyInstanceInServiceWaiter](./waiters.md#anyinstanceinservicewaiter)
- `client.get_waiter("instance_deregistered")` ->
  [InstanceDeregisteredWaiter](./waiters.md#instancederegisteredwaiter)
- `client.get_waiter("instance_in_service")` ->
  [InstanceInServiceWaiter](./waiters.md#instanceinservicewaiter)
