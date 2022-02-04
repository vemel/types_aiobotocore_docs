<a id="route53resolverclient-for-aiobotocore-route53resolver-module"></a>

# Route53ResolverClient for aiobotocore Route53Resolver module

> [Index](..) > [Route53Resolver](.) > Route53ResolverClient

Auto-generated documentation for
[Route53Resolver](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver)
type annotations stubs module
[types-aiobotocore-route53resolver](https://pypi.org/project/types-aiobotocore-route53resolver/).

- [Route53ResolverClient for aiobotocore Route53Resolver module](#route53resolverclient-for-aiobotocore-route53resolver-module)
  - [Route53ResolverClient](#route53resolverclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_firewall_rule_group](#associate_firewall_rule_group)
    - [associate_resolver_endpoint_ip_address](#associate_resolver_endpoint_ip_address)
    - [associate_resolver_query_log_config](#associate_resolver_query_log_config)
    - [associate_resolver_rule](#associate_resolver_rule)
    - [can_paginate](#can_paginate)
    - [create_firewall_domain_list](#create_firewall_domain_list)
    - [create_firewall_rule](#create_firewall_rule)
    - [create_firewall_rule_group](#create_firewall_rule_group)
    - [create_resolver_endpoint](#create_resolver_endpoint)
    - [create_resolver_query_log_config](#create_resolver_query_log_config)
    - [create_resolver_rule](#create_resolver_rule)
    - [delete_firewall_domain_list](#delete_firewall_domain_list)
    - [delete_firewall_rule](#delete_firewall_rule)
    - [delete_firewall_rule_group](#delete_firewall_rule_group)
    - [delete_resolver_endpoint](#delete_resolver_endpoint)
    - [delete_resolver_query_log_config](#delete_resolver_query_log_config)
    - [delete_resolver_rule](#delete_resolver_rule)
    - [disassociate_firewall_rule_group](#disassociate_firewall_rule_group)
    - [disassociate_resolver_endpoint_ip_address](#disassociate_resolver_endpoint_ip_address)
    - [disassociate_resolver_query_log_config](#disassociate_resolver_query_log_config)
    - [disassociate_resolver_rule](#disassociate_resolver_rule)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_firewall_config](#get_firewall_config)
    - [get_firewall_domain_list](#get_firewall_domain_list)
    - [get_firewall_rule_group](#get_firewall_rule_group)
    - [get_firewall_rule_group_association](#get_firewall_rule_group_association)
    - [get_firewall_rule_group_policy](#get_firewall_rule_group_policy)
    - [get_resolver_config](#get_resolver_config)
    - [get_resolver_dnssec_config](#get_resolver_dnssec_config)
    - [get_resolver_endpoint](#get_resolver_endpoint)
    - [get_resolver_query_log_config](#get_resolver_query_log_config)
    - [get_resolver_query_log_config_association](#get_resolver_query_log_config_association)
    - [get_resolver_query_log_config_policy](#get_resolver_query_log_config_policy)
    - [get_resolver_rule](#get_resolver_rule)
    - [get_resolver_rule_association](#get_resolver_rule_association)
    - [get_resolver_rule_policy](#get_resolver_rule_policy)
    - [import_firewall_domains](#import_firewall_domains)
    - [list_firewall_configs](#list_firewall_configs)
    - [list_firewall_domain_lists](#list_firewall_domain_lists)
    - [list_firewall_domains](#list_firewall_domains)
    - [list_firewall_rule_group_associations](#list_firewall_rule_group_associations)
    - [list_firewall_rule_groups](#list_firewall_rule_groups)
    - [list_firewall_rules](#list_firewall_rules)
    - [list_resolver_configs](#list_resolver_configs)
    - [list_resolver_dnssec_configs](#list_resolver_dnssec_configs)
    - [list_resolver_endpoint_ip_addresses](#list_resolver_endpoint_ip_addresses)
    - [list_resolver_endpoints](#list_resolver_endpoints)
    - [list_resolver_query_log_config_associations](#list_resolver_query_log_config_associations)
    - [list_resolver_query_log_configs](#list_resolver_query_log_configs)
    - [list_resolver_rule_associations](#list_resolver_rule_associations)
    - [list_resolver_rules](#list_resolver_rules)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_firewall_rule_group_policy](#put_firewall_rule_group_policy)
    - [put_resolver_query_log_config_policy](#put_resolver_query_log_config_policy)
    - [put_resolver_rule_policy](#put_resolver_rule_policy)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_firewall_config](#update_firewall_config)
    - [update_firewall_domains](#update_firewall_domains)
    - [update_firewall_rule](#update_firewall_rule)
    - [update_firewall_rule_group_association](#update_firewall_rule_group_association)
    - [update_resolver_config](#update_resolver_config)
    - [update_resolver_dnssec_config](#update_resolver_dnssec_config)
    - [update_resolver_endpoint](#update_resolver_endpoint)
    - [update_resolver_rule](#update_resolver_rule)
    - [get_paginator](#get_paginator)

<a id="route53resolverclient"></a>

## Route53ResolverClient

Type annotations for `aiobotocore.create_client("route53resolver")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_route53resolver.client import Route53ResolverClient

def get_route53resolver_client() -> Route53ResolverClient:
    return Session().client("route53resolver")
```

Boto3 documentation:
[Route53Resolver.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_route53resolver.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServiceErrorException`
- `Exceptions.InvalidNextTokenException`
- `Exceptions.InvalidParameterException`
- `Exceptions.InvalidPolicyDocument`
- `Exceptions.InvalidRequestException`
- `Exceptions.InvalidTagException`
- `Exceptions.LimitExceededException`
- `Exceptions.ResourceExistsException`
- `Exceptions.ResourceInUseException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ResourceUnavailableException`
- `Exceptions.ThrottlingException`
- `Exceptions.UnknownResourceException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

Route53ResolverClient exceptions.

Type annotations for `aiobotocore.create_client("route53resolver").exceptions`
method.

Boto3 documentation:
[Route53Resolver.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate_firewall_rule_group"></a>

### associate_firewall_rule_group

Associates a FirewallRuleGroup with a VPC, to provide DNS filtering for the
VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").associate_firewall_rule_group`
method.

Boto3 documentation:
[Route53Resolver.Client.associate_firewall_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.associate_firewall_rule_group)

Asynchronous method. Use `await associate_firewall_rule_group(...)` for a
synchronous call.

Arguments mapping described in
[AssociateFirewallRuleGroupRequestRequestTypeDef](./type_defs.md#associatefirewallrulegrouprequestrequesttypedef).

Keyword-only arguments:

- `CreatorRequestId`: `str` *(required)*
- `FirewallRuleGroupId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `Priority`: `int` *(required)*
- `Name`: `str` *(required)*
- `MutationProtection`:
  [MutationProtectionStatusType](./literals.md#mutationprotectionstatustype)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[AssociateFirewallRuleGroupResponseTypeDef](./type_defs.md#associatefirewallrulegroupresponsetypedef).

<a id="associate_resolver_endpoint_ip_address"></a>

### associate_resolver_endpoint_ip_address

Adds IP addresses to an inbound or an outbound Resolver endpoint.

Type annotations for
`aiobotocore.create_client("route53resolver").associate_resolver_endpoint_ip_address`
method.

Boto3 documentation:
[Route53Resolver.Client.associate_resolver_endpoint_ip_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.associate_resolver_endpoint_ip_address)

Asynchronous method. Use `await associate_resolver_endpoint_ip_address(...)`
for a synchronous call.

Arguments mapping described in
[AssociateResolverEndpointIpAddressRequestRequestTypeDef](./type_defs.md#associateresolverendpointipaddressrequestrequesttypedef).

Keyword-only arguments:

- `ResolverEndpointId`: `str` *(required)*
- `IpAddress`: [IpAddressUpdateTypeDef](./type_defs.md#ipaddressupdatetypedef)
  *(required)*

Returns a `Coroutine` for
[AssociateResolverEndpointIpAddressResponseTypeDef](./type_defs.md#associateresolverendpointipaddressresponsetypedef).

<a id="associate_resolver_query_log_config"></a>

### associate_resolver_query_log_config

Associates an Amazon VPC with a specified query logging configuration.

Type annotations for
`aiobotocore.create_client("route53resolver").associate_resolver_query_log_config`
method.

Boto3 documentation:
[Route53Resolver.Client.associate_resolver_query_log_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.associate_resolver_query_log_config)

Asynchronous method. Use `await associate_resolver_query_log_config(...)` for a
synchronous call.

Arguments mapping described in
[AssociateResolverQueryLogConfigRequestRequestTypeDef](./type_defs.md#associateresolverquerylogconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResolverQueryLogConfigId`: `str` *(required)*
- `ResourceId`: `str` *(required)*

Returns a `Coroutine` for
[AssociateResolverQueryLogConfigResponseTypeDef](./type_defs.md#associateresolverquerylogconfigresponsetypedef).

<a id="associate_resolver_rule"></a>

### associate_resolver_rule

Associates a Resolver rule with a VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").associate_resolver_rule` method.

Boto3 documentation:
[Route53Resolver.Client.associate_resolver_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.associate_resolver_rule)

Asynchronous method. Use `await associate_resolver_rule(...)` for a synchronous
call.

Arguments mapping described in
[AssociateResolverRuleRequestRequestTypeDef](./type_defs.md#associateresolverrulerequestrequesttypedef).

Keyword-only arguments:

- `ResolverRuleId`: `str` *(required)*
- `VPCId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for
[AssociateResolverRuleResponseTypeDef](./type_defs.md#associateresolverruleresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("route53resolver").can_paginate` method.

Boto3 documentation:
[Route53Resolver.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_firewall_domain_list"></a>

### create_firewall_domain_list

Creates an empty firewall domain list for use in DNS Firewall rules.

Type annotations for
`aiobotocore.create_client("route53resolver").create_firewall_domain_list`
method.

Boto3 documentation:
[Route53Resolver.Client.create_firewall_domain_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_firewall_domain_list)

Asynchronous method. Use `await create_firewall_domain_list(...)` for a
synchronous call.

Arguments mapping described in
[CreateFirewallDomainListRequestRequestTypeDef](./type_defs.md#createfirewalldomainlistrequestrequesttypedef).

Keyword-only arguments:

- `CreatorRequestId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateFirewallDomainListResponseTypeDef](./type_defs.md#createfirewalldomainlistresponsetypedef).

<a id="create_firewall_rule"></a>

### create_firewall_rule

Creates a single DNS Firewall rule in the specified rule group, using the
specified domain list.

Type annotations for
`aiobotocore.create_client("route53resolver").create_firewall_rule` method.

Boto3 documentation:
[Route53Resolver.Client.create_firewall_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_firewall_rule)

Asynchronous method. Use `await create_firewall_rule(...)` for a synchronous
call.

Arguments mapping described in
[CreateFirewallRuleRequestRequestTypeDef](./type_defs.md#createfirewallrulerequestrequesttypedef).

Keyword-only arguments:

- `CreatorRequestId`: `str` *(required)*
- `FirewallRuleGroupId`: `str` *(required)*
- `FirewallDomainListId`: `str` *(required)*
- `Priority`: `int` *(required)*
- `Action`: [ActionType](./literals.md#actiontype) *(required)*
- `Name`: `str` *(required)*
- `BlockResponse`: [BlockResponseType](./literals.md#blockresponsetype)
- `BlockOverrideDomain`: `str`
- `BlockOverrideDnsType`: `Literal['CNAME']` (see
  [BlockOverrideDnsTypeType](./literals.md#blockoverridednstypetype))
- `BlockOverrideTtl`: `int`

Returns a `Coroutine` for
[CreateFirewallRuleResponseTypeDef](./type_defs.md#createfirewallruleresponsetypedef).

<a id="create_firewall_rule_group"></a>

### create_firewall_rule_group

Creates an empty DNS Firewall rule group for filtering DNS network traffic in a
VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").create_firewall_rule_group`
method.

Boto3 documentation:
[Route53Resolver.Client.create_firewall_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_firewall_rule_group)

Asynchronous method. Use `await create_firewall_rule_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateFirewallRuleGroupRequestRequestTypeDef](./type_defs.md#createfirewallrulegrouprequestrequesttypedef).

Keyword-only arguments:

- `CreatorRequestId`: `str` *(required)*
- `Name`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateFirewallRuleGroupResponseTypeDef](./type_defs.md#createfirewallrulegroupresponsetypedef).

<a id="create_resolver_endpoint"></a>

### create_resolver_endpoint

Creates a Resolver endpoint.

Type annotations for
`aiobotocore.create_client("route53resolver").create_resolver_endpoint` method.

Boto3 documentation:
[Route53Resolver.Client.create_resolver_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_resolver_endpoint)

Asynchronous method. Use `await create_resolver_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[CreateResolverEndpointRequestRequestTypeDef](./type_defs.md#createresolverendpointrequestrequesttypedef).

Keyword-only arguments:

- `CreatorRequestId`: `str` *(required)*
- `SecurityGroupIds`: `Sequence`\[`str`\] *(required)*
- `Direction`:
  [ResolverEndpointDirectionType](./literals.md#resolverendpointdirectiontype)
  *(required)*
- `IpAddresses`:
  `Sequence`\[[IpAddressRequestTypeDef](./type_defs.md#ipaddressrequesttypedef)\]
  *(required)*
- `Name`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateResolverEndpointResponseTypeDef](./type_defs.md#createresolverendpointresponsetypedef).

<a id="create_resolver_query_log_config"></a>

### create_resolver_query_log_config

Creates a Resolver query logging configuration, which defines where you want
Resolver to save DNS query logs that originate in your VPCs.

Type annotations for
`aiobotocore.create_client("route53resolver").create_resolver_query_log_config`
method.

Boto3 documentation:
[Route53Resolver.Client.create_resolver_query_log_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_resolver_query_log_config)

Asynchronous method. Use `await create_resolver_query_log_config(...)` for a
synchronous call.

Arguments mapping described in
[CreateResolverQueryLogConfigRequestRequestTypeDef](./type_defs.md#createresolverquerylogconfigrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `DestinationArn`: `str` *(required)*
- `CreatorRequestId`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateResolverQueryLogConfigResponseTypeDef](./type_defs.md#createresolverquerylogconfigresponsetypedef).

<a id="create_resolver_rule"></a>

### create_resolver_rule

For DNS queries that originate in your VPCs, specifies which Resolver endpoint
the queries pass through, one domain name that you want to forward to your
network, and the IP addresses of the DNS resolvers in your network.

Type annotations for
`aiobotocore.create_client("route53resolver").create_resolver_rule` method.

Boto3 documentation:
[Route53Resolver.Client.create_resolver_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_resolver_rule)

Asynchronous method. Use `await create_resolver_rule(...)` for a synchronous
call.

Arguments mapping described in
[CreateResolverRuleRequestRequestTypeDef](./type_defs.md#createresolverrulerequestrequesttypedef).

Keyword-only arguments:

- `CreatorRequestId`: `str` *(required)*
- `RuleType`: [RuleTypeOptionType](./literals.md#ruletypeoptiontype)
  *(required)*
- `DomainName`: `str` *(required)*
- `Name`: `str`
- `TargetIps`:
  `Sequence`\[[TargetAddressTypeDef](./type_defs.md#targetaddresstypedef)\]
- `ResolverEndpointId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateResolverRuleResponseTypeDef](./type_defs.md#createresolverruleresponsetypedef).

<a id="delete_firewall_domain_list"></a>

### delete_firewall_domain_list

Deletes the specified domain list.

Type annotations for
`aiobotocore.create_client("route53resolver").delete_firewall_domain_list`
method.

Boto3 documentation:
[Route53Resolver.Client.delete_firewall_domain_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.delete_firewall_domain_list)

Asynchronous method. Use `await delete_firewall_domain_list(...)` for a
synchronous call.

Arguments mapping described in
[DeleteFirewallDomainListRequestRequestTypeDef](./type_defs.md#deletefirewalldomainlistrequestrequesttypedef).

Keyword-only arguments:

- `FirewallDomainListId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteFirewallDomainListResponseTypeDef](./type_defs.md#deletefirewalldomainlistresponsetypedef).

<a id="delete_firewall_rule"></a>

### delete_firewall_rule

Deletes the specified firewall rule.

Type annotations for
`aiobotocore.create_client("route53resolver").delete_firewall_rule` method.

Boto3 documentation:
[Route53Resolver.Client.delete_firewall_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.delete_firewall_rule)

Asynchronous method. Use `await delete_firewall_rule(...)` for a synchronous
call.

Arguments mapping described in
[DeleteFirewallRuleRequestRequestTypeDef](./type_defs.md#deletefirewallrulerequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupId`: `str` *(required)*
- `FirewallDomainListId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteFirewallRuleResponseTypeDef](./type_defs.md#deletefirewallruleresponsetypedef).

<a id="delete_firewall_rule_group"></a>

### delete_firewall_rule_group

Deletes the specified firewall rule group.

Type annotations for
`aiobotocore.create_client("route53resolver").delete_firewall_rule_group`
method.

Boto3 documentation:
[Route53Resolver.Client.delete_firewall_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.delete_firewall_rule_group)

Asynchronous method. Use `await delete_firewall_rule_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteFirewallRuleGroupRequestRequestTypeDef](./type_defs.md#deletefirewallrulegrouprequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteFirewallRuleGroupResponseTypeDef](./type_defs.md#deletefirewallrulegroupresponsetypedef).

<a id="delete_resolver_endpoint"></a>

### delete_resolver_endpoint

Deletes a Resolver endpoint.

Type annotations for
`aiobotocore.create_client("route53resolver").delete_resolver_endpoint` method.

Boto3 documentation:
[Route53Resolver.Client.delete_resolver_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.delete_resolver_endpoint)

Asynchronous method. Use `await delete_resolver_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[DeleteResolverEndpointRequestRequestTypeDef](./type_defs.md#deleteresolverendpointrequestrequesttypedef).

Keyword-only arguments:

- `ResolverEndpointId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteResolverEndpointResponseTypeDef](./type_defs.md#deleteresolverendpointresponsetypedef).

<a id="delete_resolver_query_log_config"></a>

### delete_resolver_query_log_config

Deletes a query logging configuration.

Type annotations for
`aiobotocore.create_client("route53resolver").delete_resolver_query_log_config`
method.

Boto3 documentation:
[Route53Resolver.Client.delete_resolver_query_log_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.delete_resolver_query_log_config)

Asynchronous method. Use `await delete_resolver_query_log_config(...)` for a
synchronous call.

Arguments mapping described in
[DeleteResolverQueryLogConfigRequestRequestTypeDef](./type_defs.md#deleteresolverquerylogconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResolverQueryLogConfigId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteResolverQueryLogConfigResponseTypeDef](./type_defs.md#deleteresolverquerylogconfigresponsetypedef).

<a id="delete_resolver_rule"></a>

### delete_resolver_rule

Deletes a Resolver rule.

Type annotations for
`aiobotocore.create_client("route53resolver").delete_resolver_rule` method.

Boto3 documentation:
[Route53Resolver.Client.delete_resolver_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.delete_resolver_rule)

Asynchronous method. Use `await delete_resolver_rule(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResolverRuleRequestRequestTypeDef](./type_defs.md#deleteresolverrulerequestrequesttypedef).

Keyword-only arguments:

- `ResolverRuleId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteResolverRuleResponseTypeDef](./type_defs.md#deleteresolverruleresponsetypedef).

<a id="disassociate_firewall_rule_group"></a>

### disassociate_firewall_rule_group

Disassociates a FirewallRuleGroup from a VPC, to remove DNS filtering from the
VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").disassociate_firewall_rule_group`
method.

Boto3 documentation:
[Route53Resolver.Client.disassociate_firewall_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.disassociate_firewall_rule_group)

Asynchronous method. Use `await disassociate_firewall_rule_group(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateFirewallRuleGroupRequestRequestTypeDef](./type_defs.md#disassociatefirewallrulegrouprequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupAssociationId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateFirewallRuleGroupResponseTypeDef](./type_defs.md#disassociatefirewallrulegroupresponsetypedef).

<a id="disassociate_resolver_endpoint_ip_address"></a>

### disassociate_resolver_endpoint_ip_address

Removes IP addresses from an inbound or an outbound Resolver endpoint.

Type annotations for
`aiobotocore.create_client("route53resolver").disassociate_resolver_endpoint_ip_address`
method.

Boto3 documentation:
[Route53Resolver.Client.disassociate_resolver_endpoint_ip_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.disassociate_resolver_endpoint_ip_address)

Asynchronous method. Use `await disassociate_resolver_endpoint_ip_address(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateResolverEndpointIpAddressRequestRequestTypeDef](./type_defs.md#disassociateresolverendpointipaddressrequestrequesttypedef).

Keyword-only arguments:

- `ResolverEndpointId`: `str` *(required)*
- `IpAddress`: [IpAddressUpdateTypeDef](./type_defs.md#ipaddressupdatetypedef)
  *(required)*

Returns a `Coroutine` for
[DisassociateResolverEndpointIpAddressResponseTypeDef](./type_defs.md#disassociateresolverendpointipaddressresponsetypedef).

<a id="disassociate_resolver_query_log_config"></a>

### disassociate_resolver_query_log_config

Disassociates a VPC from a query logging configuration.

Type annotations for
`aiobotocore.create_client("route53resolver").disassociate_resolver_query_log_config`
method.

Boto3 documentation:
[Route53Resolver.Client.disassociate_resolver_query_log_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.disassociate_resolver_query_log_config)

Asynchronous method. Use `await disassociate_resolver_query_log_config(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateResolverQueryLogConfigRequestRequestTypeDef](./type_defs.md#disassociateresolverquerylogconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResolverQueryLogConfigId`: `str` *(required)*
- `ResourceId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateResolverQueryLogConfigResponseTypeDef](./type_defs.md#disassociateresolverquerylogconfigresponsetypedef).

<a id="disassociate_resolver_rule"></a>

### disassociate_resolver_rule

Removes the association between a specified Resolver rule and a specified VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").disassociate_resolver_rule`
method.

Boto3 documentation:
[Route53Resolver.Client.disassociate_resolver_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.disassociate_resolver_rule)

Asynchronous method. Use `await disassociate_resolver_rule(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateResolverRuleRequestRequestTypeDef](./type_defs.md#disassociateresolverrulerequestrequesttypedef).

Keyword-only arguments:

- `VPCId`: `str` *(required)*
- `ResolverRuleId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateResolverRuleResponseTypeDef](./type_defs.md#disassociateresolverruleresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("route53resolver").generate_presigned_url` method.

Boto3 documentation:
[Route53Resolver.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_firewall_config"></a>

### get_firewall_config

Retrieves the configuration of the firewall behavior provided by DNS Firewall
for a single VPC from Amazon Virtual Private Cloud (Amazon VPC).

Type annotations for
`aiobotocore.create_client("route53resolver").get_firewall_config` method.

Boto3 documentation:
[Route53Resolver.Client.get_firewall_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_firewall_config)

Asynchronous method. Use `await get_firewall_config(...)` for a synchronous
call.

Arguments mapping described in
[GetFirewallConfigRequestRequestTypeDef](./type_defs.md#getfirewallconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*

Returns a `Coroutine` for
[GetFirewallConfigResponseTypeDef](./type_defs.md#getfirewallconfigresponsetypedef).

<a id="get_firewall_domain_list"></a>

### get_firewall_domain_list

Retrieves the specified firewall domain list.

Type annotations for
`aiobotocore.create_client("route53resolver").get_firewall_domain_list` method.

Boto3 documentation:
[Route53Resolver.Client.get_firewall_domain_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_firewall_domain_list)

Asynchronous method. Use `await get_firewall_domain_list(...)` for a
synchronous call.

Arguments mapping described in
[GetFirewallDomainListRequestRequestTypeDef](./type_defs.md#getfirewalldomainlistrequestrequesttypedef).

Keyword-only arguments:

- `FirewallDomainListId`: `str` *(required)*

Returns a `Coroutine` for
[GetFirewallDomainListResponseTypeDef](./type_defs.md#getfirewalldomainlistresponsetypedef).

<a id="get_firewall_rule_group"></a>

### get_firewall_rule_group

Retrieves the specified firewall rule group.

Type annotations for
`aiobotocore.create_client("route53resolver").get_firewall_rule_group` method.

Boto3 documentation:
[Route53Resolver.Client.get_firewall_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_firewall_rule_group)

Asynchronous method. Use `await get_firewall_rule_group(...)` for a synchronous
call.

Arguments mapping described in
[GetFirewallRuleGroupRequestRequestTypeDef](./type_defs.md#getfirewallrulegrouprequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupId`: `str` *(required)*

Returns a `Coroutine` for
[GetFirewallRuleGroupResponseTypeDef](./type_defs.md#getfirewallrulegroupresponsetypedef).

<a id="get_firewall_rule_group_association"></a>

### get_firewall_rule_group_association

Retrieves a firewall rule group association, which enables DNS filtering for a
VPC with one rule group.

Type annotations for
`aiobotocore.create_client("route53resolver").get_firewall_rule_group_association`
method.

Boto3 documentation:
[Route53Resolver.Client.get_firewall_rule_group_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_firewall_rule_group_association)

Asynchronous method. Use `await get_firewall_rule_group_association(...)` for a
synchronous call.

Arguments mapping described in
[GetFirewallRuleGroupAssociationRequestRequestTypeDef](./type_defs.md#getfirewallrulegroupassociationrequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupAssociationId`: `str` *(required)*

Returns a `Coroutine` for
[GetFirewallRuleGroupAssociationResponseTypeDef](./type_defs.md#getfirewallrulegroupassociationresponsetypedef).

<a id="get_firewall_rule_group_policy"></a>

### get_firewall_rule_group_policy

Returns the Identity and Access Management (Amazon Web Services IAM) policy for
sharing the specified rule group.

Type annotations for
`aiobotocore.create_client("route53resolver").get_firewall_rule_group_policy`
method.

Boto3 documentation:
[Route53Resolver.Client.get_firewall_rule_group_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_firewall_rule_group_policy)

Asynchronous method. Use `await get_firewall_rule_group_policy(...)` for a
synchronous call.

Arguments mapping described in
[GetFirewallRuleGroupPolicyRequestRequestTypeDef](./type_defs.md#getfirewallrulegrouppolicyrequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*

Returns a `Coroutine` for
[GetFirewallRuleGroupPolicyResponseTypeDef](./type_defs.md#getfirewallrulegrouppolicyresponsetypedef).

<a id="get_resolver_config"></a>

### get_resolver_config

Retrieves the behavior configuration of Route 53 Resolver behavior for a single
VPC from Amazon Virtual Private Cloud.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_config` method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_config)

Asynchronous method. Use `await get_resolver_config(...)` for a synchronous
call.

Arguments mapping described in
[GetResolverConfigRequestRequestTypeDef](./type_defs.md#getresolverconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverConfigResponseTypeDef](./type_defs.md#getresolverconfigresponsetypedef).

<a id="get_resolver_dnssec_config"></a>

### get_resolver_dnssec_config

Gets DNSSEC validation information for a specified resource.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_dnssec_config`
method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_dnssec_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_dnssec_config)

Asynchronous method. Use `await get_resolver_dnssec_config(...)` for a
synchronous call.

Arguments mapping described in
[GetResolverDnssecConfigRequestRequestTypeDef](./type_defs.md#getresolverdnssecconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverDnssecConfigResponseTypeDef](./type_defs.md#getresolverdnssecconfigresponsetypedef).

<a id="get_resolver_endpoint"></a>

### get_resolver_endpoint

Gets information about a specified Resolver endpoint, such as whether it's an
inbound or an outbound Resolver endpoint, and the current status of the
endpoint.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_endpoint` method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_endpoint)

Asynchronous method. Use `await get_resolver_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[GetResolverEndpointRequestRequestTypeDef](./type_defs.md#getresolverendpointrequestrequesttypedef).

Keyword-only arguments:

- `ResolverEndpointId`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverEndpointResponseTypeDef](./type_defs.md#getresolverendpointresponsetypedef).

<a id="get_resolver_query_log_config"></a>

### get_resolver_query_log_config

Gets information about a specified Resolver query logging configuration, such
as the number of VPCs that the configuration is logging queries for and the
location that logs are sent to.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_query_log_config`
method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_query_log_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_query_log_config)

Asynchronous method. Use `await get_resolver_query_log_config(...)` for a
synchronous call.

Arguments mapping described in
[GetResolverQueryLogConfigRequestRequestTypeDef](./type_defs.md#getresolverquerylogconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResolverQueryLogConfigId`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverQueryLogConfigResponseTypeDef](./type_defs.md#getresolverquerylogconfigresponsetypedef).

<a id="get_resolver_query_log_config_association"></a>

### get_resolver_query_log_config_association

Gets information about a specified association between a Resolver query logging
configuration and an Amazon VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_query_log_config_association`
method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_query_log_config_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_query_log_config_association)

Asynchronous method. Use `await get_resolver_query_log_config_association(...)`
for a synchronous call.

Arguments mapping described in
[GetResolverQueryLogConfigAssociationRequestRequestTypeDef](./type_defs.md#getresolverquerylogconfigassociationrequestrequesttypedef).

Keyword-only arguments:

- `ResolverQueryLogConfigAssociationId`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverQueryLogConfigAssociationResponseTypeDef](./type_defs.md#getresolverquerylogconfigassociationresponsetypedef).

<a id="get_resolver_query_log_config_policy"></a>

### get_resolver_query_log_config_policy

Gets information about a query logging policy.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_query_log_config_policy`
method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_query_log_config_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_query_log_config_policy)

Asynchronous method. Use `await get_resolver_query_log_config_policy(...)` for
a synchronous call.

Arguments mapping described in
[GetResolverQueryLogConfigPolicyRequestRequestTypeDef](./type_defs.md#getresolverquerylogconfigpolicyrequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverQueryLogConfigPolicyResponseTypeDef](./type_defs.md#getresolverquerylogconfigpolicyresponsetypedef).

<a id="get_resolver_rule"></a>

### get_resolver_rule

Gets information about a specified Resolver rule, such as the domain name that
the rule forwards DNS queries for and the ID of the outbound Resolver endpoint
that the rule is associated with.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_rule` method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_rule)

Asynchronous method. Use `await get_resolver_rule(...)` for a synchronous call.

Arguments mapping described in
[GetResolverRuleRequestRequestTypeDef](./type_defs.md#getresolverrulerequestrequesttypedef).

Keyword-only arguments:

- `ResolverRuleId`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverRuleResponseTypeDef](./type_defs.md#getresolverruleresponsetypedef).

<a id="get_resolver_rule_association"></a>

### get_resolver_rule_association

Gets information about an association between a specified Resolver rule and a
VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_rule_association`
method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_rule_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_rule_association)

Asynchronous method. Use `await get_resolver_rule_association(...)` for a
synchronous call.

Arguments mapping described in
[GetResolverRuleAssociationRequestRequestTypeDef](./type_defs.md#getresolverruleassociationrequestrequesttypedef).

Keyword-only arguments:

- `ResolverRuleAssociationId`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverRuleAssociationResponseTypeDef](./type_defs.md#getresolverruleassociationresponsetypedef).

<a id="get_resolver_rule_policy"></a>

### get_resolver_rule_policy

Gets information about the Resolver rule policy for a specified rule.

Type annotations for
`aiobotocore.create_client("route53resolver").get_resolver_rule_policy` method.

Boto3 documentation:
[Route53Resolver.Client.get_resolver_rule_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.get_resolver_rule_policy)

Asynchronous method. Use `await get_resolver_rule_policy(...)` for a
synchronous call.

Arguments mapping described in
[GetResolverRulePolicyRequestRequestTypeDef](./type_defs.md#getresolverrulepolicyrequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*

Returns a `Coroutine` for
[GetResolverRulePolicyResponseTypeDef](./type_defs.md#getresolverrulepolicyresponsetypedef).

<a id="import_firewall_domains"></a>

### import_firewall_domains

Imports domain names from a file into a domain list, for use in a DNS firewall
rule group.

Type annotations for
`aiobotocore.create_client("route53resolver").import_firewall_domains` method.

Boto3 documentation:
[Route53Resolver.Client.import_firewall_domains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.import_firewall_domains)

Asynchronous method. Use `await import_firewall_domains(...)` for a synchronous
call.

Arguments mapping described in
[ImportFirewallDomainsRequestRequestTypeDef](./type_defs.md#importfirewalldomainsrequestrequesttypedef).

Keyword-only arguments:

- `FirewallDomainListId`: `str` *(required)*
- `Operation`: `Literal['REPLACE']` (see
  [FirewallDomainImportOperationType](./literals.md#firewalldomainimportoperationtype))
  *(required)*
- `DomainFileUrl`: `str` *(required)*

Returns a `Coroutine` for
[ImportFirewallDomainsResponseTypeDef](./type_defs.md#importfirewalldomainsresponsetypedef).

<a id="list_firewall_configs"></a>

### list_firewall_configs

Retrieves the firewall configurations that you have defined.

Type annotations for
`aiobotocore.create_client("route53resolver").list_firewall_configs` method.

Boto3 documentation:
[Route53Resolver.Client.list_firewall_configs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_firewall_configs)

Asynchronous method. Use `await list_firewall_configs(...)` for a synchronous
call.

Arguments mapping described in
[ListFirewallConfigsRequestRequestTypeDef](./type_defs.md#listfirewallconfigsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFirewallConfigsResponseTypeDef](./type_defs.md#listfirewallconfigsresponsetypedef).

<a id="list_firewall_domain_lists"></a>

### list_firewall_domain_lists

Retrieves the firewall domain lists that you have defined.

Type annotations for
`aiobotocore.create_client("route53resolver").list_firewall_domain_lists`
method.

Boto3 documentation:
[Route53Resolver.Client.list_firewall_domain_lists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_firewall_domain_lists)

Asynchronous method. Use `await list_firewall_domain_lists(...)` for a
synchronous call.

Arguments mapping described in
[ListFirewallDomainListsRequestRequestTypeDef](./type_defs.md#listfirewalldomainlistsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFirewallDomainListsResponseTypeDef](./type_defs.md#listfirewalldomainlistsresponsetypedef).

<a id="list_firewall_domains"></a>

### list_firewall_domains

Retrieves the domains that you have defined for the specified firewall domain
list.

Type annotations for
`aiobotocore.create_client("route53resolver").list_firewall_domains` method.

Boto3 documentation:
[Route53Resolver.Client.list_firewall_domains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_firewall_domains)

Asynchronous method. Use `await list_firewall_domains(...)` for a synchronous
call.

Arguments mapping described in
[ListFirewallDomainsRequestRequestTypeDef](./type_defs.md#listfirewalldomainsrequestrequesttypedef).

Keyword-only arguments:

- `FirewallDomainListId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFirewallDomainsResponseTypeDef](./type_defs.md#listfirewalldomainsresponsetypedef).

<a id="list_firewall_rule_group_associations"></a>

### list_firewall_rule_group_associations

Retrieves the firewall rule group associations that you have defined.

Type annotations for
`aiobotocore.create_client("route53resolver").list_firewall_rule_group_associations`
method.

Boto3 documentation:
[Route53Resolver.Client.list_firewall_rule_group_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_firewall_rule_group_associations)

Asynchronous method. Use `await list_firewall_rule_group_associations(...)` for
a synchronous call.

Arguments mapping described in
[ListFirewallRuleGroupAssociationsRequestRequestTypeDef](./type_defs.md#listfirewallrulegroupassociationsrequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupId`: `str`
- `VpcId`: `str`
- `Priority`: `int`
- `Status`:
  [FirewallRuleGroupAssociationStatusType](./literals.md#firewallrulegroupassociationstatustype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFirewallRuleGroupAssociationsResponseTypeDef](./type_defs.md#listfirewallrulegroupassociationsresponsetypedef).

<a id="list_firewall_rule_groups"></a>

### list_firewall_rule_groups

Retrieves the minimal high-level information for the rule groups that you have
defined.

Type annotations for
`aiobotocore.create_client("route53resolver").list_firewall_rule_groups`
method.

Boto3 documentation:
[Route53Resolver.Client.list_firewall_rule_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_firewall_rule_groups)

Asynchronous method. Use `await list_firewall_rule_groups(...)` for a
synchronous call.

Arguments mapping described in
[ListFirewallRuleGroupsRequestRequestTypeDef](./type_defs.md#listfirewallrulegroupsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFirewallRuleGroupsResponseTypeDef](./type_defs.md#listfirewallrulegroupsresponsetypedef).

<a id="list_firewall_rules"></a>

### list_firewall_rules

Retrieves the firewall rules that you have defined for the specified firewall
rule group.

Type annotations for
`aiobotocore.create_client("route53resolver").list_firewall_rules` method.

Boto3 documentation:
[Route53Resolver.Client.list_firewall_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_firewall_rules)

Asynchronous method. Use `await list_firewall_rules(...)` for a synchronous
call.

Arguments mapping described in
[ListFirewallRulesRequestRequestTypeDef](./type_defs.md#listfirewallrulesrequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupId`: `str` *(required)*
- `Priority`: `int`
- `Action`: [ActionType](./literals.md#actiontype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFirewallRulesResponseTypeDef](./type_defs.md#listfirewallrulesresponsetypedef).

<a id="list_resolver_configs"></a>

### list_resolver_configs

Retrieves the Resolver configurations that you have defined.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_configs` method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_configs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_configs)

Asynchronous method. Use `await list_resolver_configs(...)` for a synchronous
call.

Arguments mapping described in
[ListResolverConfigsRequestRequestTypeDef](./type_defs.md#listresolverconfigsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListResolverConfigsResponseTypeDef](./type_defs.md#listresolverconfigsresponsetypedef).

<a id="list_resolver_dnssec_configs"></a>

### list_resolver_dnssec_configs

Lists the configurations for DNSSEC validation that are associated with the
current Amazon Web Services account.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_dnssec_configs`
method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_dnssec_configs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_dnssec_configs)

Asynchronous method. Use `await list_resolver_dnssec_configs(...)` for a
synchronous call.

Arguments mapping described in
[ListResolverDnssecConfigsRequestRequestTypeDef](./type_defs.md#listresolverdnssecconfigsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[ListResolverDnssecConfigsResponseTypeDef](./type_defs.md#listresolverdnssecconfigsresponsetypedef).

<a id="list_resolver_endpoint_ip_addresses"></a>

### list_resolver_endpoint_ip_addresses

Gets the IP addresses for a specified Resolver endpoint.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_endpoint_ip_addresses`
method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_endpoint_ip_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_endpoint_ip_addresses)

Asynchronous method. Use `await list_resolver_endpoint_ip_addresses(...)` for a
synchronous call.

Arguments mapping described in
[ListResolverEndpointIpAddressesRequestRequestTypeDef](./type_defs.md#listresolverendpointipaddressesrequestrequesttypedef).

Keyword-only arguments:

- `ResolverEndpointId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListResolverEndpointIpAddressesResponseTypeDef](./type_defs.md#listresolverendpointipaddressesresponsetypedef).

<a id="list_resolver_endpoints"></a>

### list_resolver_endpoints

Lists all the Resolver endpoints that were created using the current Amazon Web
Services account.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_endpoints` method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_endpoints)

Asynchronous method. Use `await list_resolver_endpoints(...)` for a synchronous
call.

Arguments mapping described in
[ListResolverEndpointsRequestRequestTypeDef](./type_defs.md#listresolverendpointsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[ListResolverEndpointsResponseTypeDef](./type_defs.md#listresolverendpointsresponsetypedef).

<a id="list_resolver_query_log_config_associations"></a>

### list_resolver_query_log_config_associations

Lists information about associations between Amazon VPCs and query logging
configurations.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_query_log_config_associations`
method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_query_log_config_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_query_log_config_associations)

Asynchronous method. Use
`await list_resolver_query_log_config_associations(...)` for a synchronous
call.

Arguments mapping described in
[ListResolverQueryLogConfigAssociationsRequestRequestTypeDef](./type_defs.md#listresolverquerylogconfigassociationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `SortBy`: `str`
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

Returns a `Coroutine` for
[ListResolverQueryLogConfigAssociationsResponseTypeDef](./type_defs.md#listresolverquerylogconfigassociationsresponsetypedef).

<a id="list_resolver_query_log_configs"></a>

### list_resolver_query_log_configs

Lists information about the specified query logging configurations.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_query_log_configs`
method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_query_log_configs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_query_log_configs)

Asynchronous method. Use `await list_resolver_query_log_configs(...)` for a
synchronous call.

Arguments mapping described in
[ListResolverQueryLogConfigsRequestRequestTypeDef](./type_defs.md#listresolverquerylogconfigsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `SortBy`: `str`
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

Returns a `Coroutine` for
[ListResolverQueryLogConfigsResponseTypeDef](./type_defs.md#listresolverquerylogconfigsresponsetypedef).

<a id="list_resolver_rule_associations"></a>

### list_resolver_rule_associations

Lists the associations that were created between Resolver rules and VPCs using
the current Amazon Web Services account.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_rule_associations`
method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_rule_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_rule_associations)

Asynchronous method. Use `await list_resolver_rule_associations(...)` for a
synchronous call.

Arguments mapping described in
[ListResolverRuleAssociationsRequestRequestTypeDef](./type_defs.md#listresolverruleassociationsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[ListResolverRuleAssociationsResponseTypeDef](./type_defs.md#listresolverruleassociationsresponsetypedef).

<a id="list_resolver_rules"></a>

### list_resolver_rules

Lists the Resolver rules that were created using the current Amazon Web
Services account.

Type annotations for
`aiobotocore.create_client("route53resolver").list_resolver_rules` method.

Boto3 documentation:
[Route53Resolver.Client.list_resolver_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_resolver_rules)

Asynchronous method. Use `await list_resolver_rules(...)` for a synchronous
call.

Arguments mapping described in
[ListResolverRulesRequestRequestTypeDef](./type_defs.md#listresolverrulesrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[ListResolverRulesResponseTypeDef](./type_defs.md#listresolverrulesresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags that you associated with the specified resource.

Type annotations for
`aiobotocore.create_client("route53resolver").list_tags_for_resource` method.

Boto3 documentation:
[Route53Resolver.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_firewall_rule_group_policy"></a>

### put_firewall_rule_group_policy

Attaches an Identity and Access Management (Amazon Web Services IAM) policy for
sharing the rule group.

Type annotations for
`aiobotocore.create_client("route53resolver").put_firewall_rule_group_policy`
method.

Boto3 documentation:
[Route53Resolver.Client.put_firewall_rule_group_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.put_firewall_rule_group_policy)

Asynchronous method. Use `await put_firewall_rule_group_policy(...)` for a
synchronous call.

Arguments mapping described in
[PutFirewallRuleGroupPolicyRequestRequestTypeDef](./type_defs.md#putfirewallrulegrouppolicyrequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*
- `FirewallRuleGroupPolicy`: `str` *(required)*

Returns a `Coroutine` for
[PutFirewallRuleGroupPolicyResponseTypeDef](./type_defs.md#putfirewallrulegrouppolicyresponsetypedef).

<a id="put_resolver_query_log_config_policy"></a>

### put_resolver_query_log_config_policy

Specifies an Amazon Web Services account that you want to share a query logging
configuration with, the query logging configuration that you want to share, and
the operations that you want the account to be able to perform on the
configuration.

Type annotations for
`aiobotocore.create_client("route53resolver").put_resolver_query_log_config_policy`
method.

Boto3 documentation:
[Route53Resolver.Client.put_resolver_query_log_config_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.put_resolver_query_log_config_policy)

Asynchronous method. Use `await put_resolver_query_log_config_policy(...)` for
a synchronous call.

Arguments mapping described in
[PutResolverQueryLogConfigPolicyRequestRequestTypeDef](./type_defs.md#putresolverquerylogconfigpolicyrequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*
- `ResolverQueryLogConfigPolicy`: `str` *(required)*

Returns a `Coroutine` for
[PutResolverQueryLogConfigPolicyResponseTypeDef](./type_defs.md#putresolverquerylogconfigpolicyresponsetypedef).

<a id="put_resolver_rule_policy"></a>

### put_resolver_rule_policy

Specifies an Amazon Web Services rule that you want to share with another
account, the account that you want to share the rule with, and the operations
that you want the account to be able to perform on the rule.

Type annotations for
`aiobotocore.create_client("route53resolver").put_resolver_rule_policy` method.

Boto3 documentation:
[Route53Resolver.Client.put_resolver_rule_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.put_resolver_rule_policy)

Asynchronous method. Use `await put_resolver_rule_policy(...)` for a
synchronous call.

Arguments mapping described in
[PutResolverRulePolicyRequestRequestTypeDef](./type_defs.md#putresolverrulepolicyrequestrequesttypedef).

Keyword-only arguments:

- `Arn`: `str` *(required)*
- `ResolverRulePolicy`: `str` *(required)*

Returns a `Coroutine` for
[PutResolverRulePolicyResponseTypeDef](./type_defs.md#putresolverrulepolicyresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds one or more tags to a specified resource.

Type annotations for
`aiobotocore.create_client("route53resolver").tag_resource` method.

Boto3 documentation:
[Route53Resolver.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes one or more tags from a specified resource.

Type annotations for
`aiobotocore.create_client("route53resolver").untag_resource` method.

Boto3 documentation:
[Route53Resolver.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_firewall_config"></a>

### update_firewall_config

Updates the configuration of the firewall behavior provided by DNS Firewall for
a single VPC from Amazon Virtual Private Cloud (Amazon VPC).

Type annotations for
`aiobotocore.create_client("route53resolver").update_firewall_config` method.

Boto3 documentation:
[Route53Resolver.Client.update_firewall_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_firewall_config)

Asynchronous method. Use `await update_firewall_config(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFirewallConfigRequestRequestTypeDef](./type_defs.md#updatefirewallconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*
- `FirewallFailOpen`:
  [FirewallFailOpenStatusType](./literals.md#firewallfailopenstatustype)
  *(required)*

Returns a `Coroutine` for
[UpdateFirewallConfigResponseTypeDef](./type_defs.md#updatefirewallconfigresponsetypedef).

<a id="update_firewall_domains"></a>

### update_firewall_domains

Updates the firewall domain list from an array of domain specifications.

Type annotations for
`aiobotocore.create_client("route53resolver").update_firewall_domains` method.

Boto3 documentation:
[Route53Resolver.Client.update_firewall_domains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_firewall_domains)

Asynchronous method. Use `await update_firewall_domains(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFirewallDomainsRequestRequestTypeDef](./type_defs.md#updatefirewalldomainsrequestrequesttypedef).

Keyword-only arguments:

- `FirewallDomainListId`: `str` *(required)*
- `Operation`:
  [FirewallDomainUpdateOperationType](./literals.md#firewalldomainupdateoperationtype)
  *(required)*
- `Domains`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[UpdateFirewallDomainsResponseTypeDef](./type_defs.md#updatefirewalldomainsresponsetypedef).

<a id="update_firewall_rule"></a>

### update_firewall_rule

Updates the specified firewall rule.

Type annotations for
`aiobotocore.create_client("route53resolver").update_firewall_rule` method.

Boto3 documentation:
[Route53Resolver.Client.update_firewall_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_firewall_rule)

Asynchronous method. Use `await update_firewall_rule(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFirewallRuleRequestRequestTypeDef](./type_defs.md#updatefirewallrulerequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupId`: `str` *(required)*
- `FirewallDomainListId`: `str` *(required)*
- `Priority`: `int`
- `Action`: [ActionType](./literals.md#actiontype)
- `BlockResponse`: [BlockResponseType](./literals.md#blockresponsetype)
- `BlockOverrideDomain`: `str`
- `BlockOverrideDnsType`: `Literal['CNAME']` (see
  [BlockOverrideDnsTypeType](./literals.md#blockoverridednstypetype))
- `BlockOverrideTtl`: `int`
- `Name`: `str`

Returns a `Coroutine` for
[UpdateFirewallRuleResponseTypeDef](./type_defs.md#updatefirewallruleresponsetypedef).

<a id="update_firewall_rule_group_association"></a>

### update_firewall_rule_group_association

Changes the association of a FirewallRuleGroup with a VPC.

Type annotations for
`aiobotocore.create_client("route53resolver").update_firewall_rule_group_association`
method.

Boto3 documentation:
[Route53Resolver.Client.update_firewall_rule_group_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_firewall_rule_group_association)

Asynchronous method. Use `await update_firewall_rule_group_association(...)`
for a synchronous call.

Arguments mapping described in
[UpdateFirewallRuleGroupAssociationRequestRequestTypeDef](./type_defs.md#updatefirewallrulegroupassociationrequestrequesttypedef).

Keyword-only arguments:

- `FirewallRuleGroupAssociationId`: `str` *(required)*
- `Priority`: `int`
- `MutationProtection`:
  [MutationProtectionStatusType](./literals.md#mutationprotectionstatustype)
- `Name`: `str`

Returns a `Coroutine` for
[UpdateFirewallRuleGroupAssociationResponseTypeDef](./type_defs.md#updatefirewallrulegroupassociationresponsetypedef).

<a id="update_resolver_config"></a>

### update_resolver_config

Updates the behavior configuration of Route 53 Resolver behavior for a single
VPC from Amazon Virtual Private Cloud.

Type annotations for
`aiobotocore.create_client("route53resolver").update_resolver_config` method.

Boto3 documentation:
[Route53Resolver.Client.update_resolver_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_config)

Asynchronous method. Use `await update_resolver_config(...)` for a synchronous
call.

Arguments mapping described in
[UpdateResolverConfigRequestRequestTypeDef](./type_defs.md#updateresolverconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*
- `AutodefinedReverseFlag`:
  [AutodefinedReverseFlagType](./literals.md#autodefinedreverseflagtype)
  *(required)*

Returns a `Coroutine` for
[UpdateResolverConfigResponseTypeDef](./type_defs.md#updateresolverconfigresponsetypedef).

<a id="update_resolver_dnssec_config"></a>

### update_resolver_dnssec_config

Updates an existing DNSSEC validation configuration.

Type annotations for
`aiobotocore.create_client("route53resolver").update_resolver_dnssec_config`
method.

Boto3 documentation:
[Route53Resolver.Client.update_resolver_dnssec_config](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_dnssec_config)

Asynchronous method. Use `await update_resolver_dnssec_config(...)` for a
synchronous call.

Arguments mapping described in
[UpdateResolverDnssecConfigRequestRequestTypeDef](./type_defs.md#updateresolverdnssecconfigrequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*
- `Validation`: [ValidationType](./literals.md#validationtype) *(required)*

Returns a `Coroutine` for
[UpdateResolverDnssecConfigResponseTypeDef](./type_defs.md#updateresolverdnssecconfigresponsetypedef).

<a id="update_resolver_endpoint"></a>

### update_resolver_endpoint

Updates the name of an inbound or an outbound Resolver endpoint.

Type annotations for
`aiobotocore.create_client("route53resolver").update_resolver_endpoint` method.

Boto3 documentation:
[Route53Resolver.Client.update_resolver_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_endpoint)

Asynchronous method. Use `await update_resolver_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[UpdateResolverEndpointRequestRequestTypeDef](./type_defs.md#updateresolverendpointrequestrequesttypedef).

Keyword-only arguments:

- `ResolverEndpointId`: `str` *(required)*
- `Name`: `str`

Returns a `Coroutine` for
[UpdateResolverEndpointResponseTypeDef](./type_defs.md#updateresolverendpointresponsetypedef).

<a id="update_resolver_rule"></a>

### update_resolver_rule

Updates settings for a specified Resolver rule.

Type annotations for
`aiobotocore.create_client("route53resolver").update_resolver_rule` method.

Boto3 documentation:
[Route53Resolver.Client.update_resolver_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_rule)

Asynchronous method. Use `await update_resolver_rule(...)` for a synchronous
call.

Arguments mapping described in
[UpdateResolverRuleRequestRequestTypeDef](./type_defs.md#updateresolverrulerequestrequesttypedef).

Keyword-only arguments:

- `ResolverRuleId`: `str` *(required)*
- `Config`:
  [ResolverRuleConfigTypeDef](./type_defs.md#resolverruleconfigtypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateResolverRuleResponseTypeDef](./type_defs.md#updateresolverruleresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("route53resolver").get_paginator` method with
overloads.

- `client.get_paginator("list_firewall_configs")` ->
  [ListFirewallConfigsPaginator](./paginators.md#listfirewallconfigspaginator)
- `client.get_paginator("list_firewall_domain_lists")` ->
  [ListFirewallDomainListsPaginator](./paginators.md#listfirewalldomainlistspaginator)
- `client.get_paginator("list_firewall_domains")` ->
  [ListFirewallDomainsPaginator](./paginators.md#listfirewalldomainspaginator)
- `client.get_paginator("list_firewall_rule_group_associations")` ->
  [ListFirewallRuleGroupAssociationsPaginator](./paginators.md#listfirewallrulegroupassociationspaginator)
- `client.get_paginator("list_firewall_rule_groups")` ->
  [ListFirewallRuleGroupsPaginator](./paginators.md#listfirewallrulegroupspaginator)
- `client.get_paginator("list_firewall_rules")` ->
  [ListFirewallRulesPaginator](./paginators.md#listfirewallrulespaginator)
- `client.get_paginator("list_resolver_configs")` ->
  [ListResolverConfigsPaginator](./paginators.md#listresolverconfigspaginator)
- `client.get_paginator("list_resolver_dnssec_configs")` ->
  [ListResolverDnssecConfigsPaginator](./paginators.md#listresolverdnssecconfigspaginator)
- `client.get_paginator("list_resolver_endpoint_ip_addresses")` ->
  [ListResolverEndpointIpAddressesPaginator](./paginators.md#listresolverendpointipaddressespaginator)
- `client.get_paginator("list_resolver_endpoints")` ->
  [ListResolverEndpointsPaginator](./paginators.md#listresolverendpointspaginator)
- `client.get_paginator("list_resolver_query_log_config_associations")` ->
  [ListResolverQueryLogConfigAssociationsPaginator](./paginators.md#listresolverquerylogconfigassociationspaginator)
- `client.get_paginator("list_resolver_query_log_configs")` ->
  [ListResolverQueryLogConfigsPaginator](./paginators.md#listresolverquerylogconfigspaginator)
- `client.get_paginator("list_resolver_rule_associations")` ->
  [ListResolverRuleAssociationsPaginator](./paginators.md#listresolverruleassociationspaginator)
- `client.get_paginator("list_resolver_rules")` ->
  [ListResolverRulesPaginator](./paginators.md#listresolverrulespaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
