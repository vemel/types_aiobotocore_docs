<a id="networkfirewallclient-for-aiobotocore-networkfirewall-module"></a>

# NetworkFirewallClient for aiobotocore NetworkFirewall module

> [Index](..) > [NetworkFirewall](.) > NetworkFirewallClient

Auto-generated documentation for
[NetworkFirewall](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall)
type annotations stubs module
[types-aiobotocore-network-firewall](https://pypi.org/project/types-aiobotocore-network-firewall/).

- [NetworkFirewallClient for aiobotocore NetworkFirewall module](#networkfirewallclient-for-aiobotocore-networkfirewall-module)
  - [NetworkFirewallClient](#networkfirewallclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_firewall_policy](#associate_firewall_policy)
    - [associate_subnets](#associate_subnets)
    - [can_paginate](#can_paginate)
    - [create_firewall](#create_firewall)
    - [create_firewall_policy](#create_firewall_policy)
    - [create_rule_group](#create_rule_group)
    - [delete_firewall](#delete_firewall)
    - [delete_firewall_policy](#delete_firewall_policy)
    - [delete_resource_policy](#delete_resource_policy)
    - [delete_rule_group](#delete_rule_group)
    - [describe_firewall](#describe_firewall)
    - [describe_firewall_policy](#describe_firewall_policy)
    - [describe_logging_configuration](#describe_logging_configuration)
    - [describe_resource_policy](#describe_resource_policy)
    - [describe_rule_group](#describe_rule_group)
    - [describe_rule_group_metadata](#describe_rule_group_metadata)
    - [disassociate_subnets](#disassociate_subnets)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_firewall_policies](#list_firewall_policies)
    - [list_firewalls](#list_firewalls)
    - [list_rule_groups](#list_rule_groups)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_resource_policy](#put_resource_policy)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_firewall_delete_protection](#update_firewall_delete_protection)
    - [update_firewall_description](#update_firewall_description)
    - [update_firewall_policy](#update_firewall_policy)
    - [update_firewall_policy_change_protection](#update_firewall_policy_change_protection)
    - [update_logging_configuration](#update_logging_configuration)
    - [update_rule_group](#update_rule_group)
    - [update_subnet_change_protection](#update_subnet_change_protection)
    - [get_paginator](#get_paginator)

<a id="networkfirewallclient"></a>

## NetworkFirewallClient

Type annotations for `aiobotocore.create_client("network-firewall")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_network_firewall.client import NetworkFirewallClient

def get_network-firewall_client() -> NetworkFirewallClient:
    return Session().client("network-firewall")
```

Boto3 documentation:
[NetworkFirewall.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_network_firewall.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`
- `Exceptions.InsufficientCapacityException`
- `Exceptions.InternalServerError`
- `Exceptions.InvalidOperationException`
- `Exceptions.InvalidRequestException`
- `Exceptions.InvalidResourcePolicyException`
- `Exceptions.InvalidTokenException`
- `Exceptions.LimitExceededException`
- `Exceptions.LogDestinationPermissionException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ResourceOwnerCheckException`
- `Exceptions.ThrottlingException`
- `Exceptions.UnsupportedOperationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

NetworkFirewallClient exceptions.

Type annotations for `aiobotocore.create_client("network-firewall").exceptions`
method.

Boto3 documentation:
[NetworkFirewall.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate_firewall_policy"></a>

### associate_firewall_policy

Associates a FirewallPolicy to a Firewall .

Type annotations for
`aiobotocore.create_client("network-firewall").associate_firewall_policy`
method.

Boto3 documentation:
[NetworkFirewall.Client.associate_firewall_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.associate_firewall_policy)

Asynchronous method. Use `await associate_firewall_policy(...)` for a
synchronous call.

Arguments mapping described in
[AssociateFirewallPolicyRequestRequestTypeDef](./type_defs.md#associatefirewallpolicyrequestrequesttypedef).

Keyword-only arguments:

- `FirewallPolicyArn`: `str` *(required)*
- `UpdateToken`: `str`
- `FirewallArn`: `str`
- `FirewallName`: `str`

Returns a `Coroutine` for
[AssociateFirewallPolicyResponseTypeDef](./type_defs.md#associatefirewallpolicyresponsetypedef).

<a id="associate_subnets"></a>

### associate_subnets

Associates the specified subnets in the Amazon VPC to the firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").associate_subnets` method.

Boto3 documentation:
[NetworkFirewall.Client.associate_subnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.associate_subnets)

Asynchronous method. Use `await associate_subnets(...)` for a synchronous call.

Arguments mapping described in
[AssociateSubnetsRequestRequestTypeDef](./type_defs.md#associatesubnetsrequestrequesttypedef).

Keyword-only arguments:

- `SubnetMappings`:
  `Sequence`\[[SubnetMappingTypeDef](./type_defs.md#subnetmappingtypedef)\]
  *(required)*
- `UpdateToken`: `str`
- `FirewallArn`: `str`
- `FirewallName`: `str`

Returns a `Coroutine` for
[AssociateSubnetsResponseTypeDef](./type_defs.md#associatesubnetsresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for
`aiobotocore.create_client("network-firewall").can_paginate` method.

Boto3 documentation:
[NetworkFirewall.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_firewall"></a>

### create_firewall

Creates an AWS Network Firewall Firewall and accompanying FirewallStatus for a
VPC.

Type annotations for
`aiobotocore.create_client("network-firewall").create_firewall` method.

Boto3 documentation:
[NetworkFirewall.Client.create_firewall](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.create_firewall)

Asynchronous method. Use `await create_firewall(...)` for a synchronous call.

Arguments mapping described in
[CreateFirewallRequestRequestTypeDef](./type_defs.md#createfirewallrequestrequesttypedef).

Keyword-only arguments:

- `FirewallName`: `str` *(required)*
- `FirewallPolicyArn`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `SubnetMappings`:
  `Sequence`\[[SubnetMappingTypeDef](./type_defs.md#subnetmappingtypedef)\]
  *(required)*
- `DeleteProtection`: `bool`
- `SubnetChangeProtection`: `bool`
- `FirewallPolicyChangeProtection`: `bool`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateFirewallResponseTypeDef](./type_defs.md#createfirewallresponsetypedef).

<a id="create_firewall_policy"></a>

### create_firewall_policy

Creates the firewall policy for the firewall according to the specifications.

Type annotations for
`aiobotocore.create_client("network-firewall").create_firewall_policy` method.

Boto3 documentation:
[NetworkFirewall.Client.create_firewall_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.create_firewall_policy)

Asynchronous method. Use `await create_firewall_policy(...)` for a synchronous
call.

Arguments mapping described in
[CreateFirewallPolicyRequestRequestTypeDef](./type_defs.md#createfirewallpolicyrequestrequesttypedef).

Keyword-only arguments:

- `FirewallPolicyName`: `str` *(required)*
- `FirewallPolicy`:
  [FirewallPolicyTypeDef](./type_defs.md#firewallpolicytypedef) *(required)*
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateFirewallPolicyResponseTypeDef](./type_defs.md#createfirewallpolicyresponsetypedef).

<a id="create_rule_group"></a>

### create_rule_group

Creates the specified stateless or stateful rule group, which includes the
rules for network traffic inspection, a capacity setting, and tags.

Type annotations for
`aiobotocore.create_client("network-firewall").create_rule_group` method.

Boto3 documentation:
[NetworkFirewall.Client.create_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.create_rule_group)

Asynchronous method. Use `await create_rule_group(...)` for a synchronous call.

Arguments mapping described in
[CreateRuleGroupRequestRequestTypeDef](./type_defs.md#createrulegrouprequestrequesttypedef).

Keyword-only arguments:

- `RuleGroupName`: `str` *(required)*
- `Type`: [RuleGroupTypeType](./literals.md#rulegrouptypetype) *(required)*
- `Capacity`: `int` *(required)*
- `RuleGroup`: [RuleGroupTypeDef](./type_defs.md#rulegrouptypedef)
- `Rules`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateRuleGroupResponseTypeDef](./type_defs.md#createrulegroupresponsetypedef).

<a id="delete_firewall"></a>

### delete_firewall

Deletes the specified Firewall and its FirewallStatus.

Type annotations for
`aiobotocore.create_client("network-firewall").delete_firewall` method.

Boto3 documentation:
[NetworkFirewall.Client.delete_firewall](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_firewall)

Asynchronous method. Use `await delete_firewall(...)` for a synchronous call.

Arguments mapping described in
[DeleteFirewallRequestRequestTypeDef](./type_defs.md#deletefirewallrequestrequesttypedef).

Keyword-only arguments:

- `FirewallName`: `str`
- `FirewallArn`: `str`

Returns a `Coroutine` for
[DeleteFirewallResponseTypeDef](./type_defs.md#deletefirewallresponsetypedef).

<a id="delete_firewall_policy"></a>

### delete_firewall_policy

Deletes the specified FirewallPolicy .

Type annotations for
`aiobotocore.create_client("network-firewall").delete_firewall_policy` method.

Boto3 documentation:
[NetworkFirewall.Client.delete_firewall_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_firewall_policy)

Asynchronous method. Use `await delete_firewall_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteFirewallPolicyRequestRequestTypeDef](./type_defs.md#deletefirewallpolicyrequestrequesttypedef).

Keyword-only arguments:

- `FirewallPolicyName`: `str`
- `FirewallPolicyArn`: `str`

Returns a `Coroutine` for
[DeleteFirewallPolicyResponseTypeDef](./type_defs.md#deletefirewallpolicyresponsetypedef).

<a id="delete_resource_policy"></a>

### delete_resource_policy

Deletes a resource policy that you created in a PutResourcePolicy request.

Type annotations for
`aiobotocore.create_client("network-firewall").delete_resource_policy` method.

Boto3 documentation:
[NetworkFirewall.Client.delete_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_resource_policy)

Asynchronous method. Use `await delete_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[DeleteResourcePolicyRequestRequestTypeDef](./type_defs.md#deleteresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_rule_group"></a>

### delete_rule_group

Deletes the specified RuleGroup .

Type annotations for
`aiobotocore.create_client("network-firewall").delete_rule_group` method.

Boto3 documentation:
[NetworkFirewall.Client.delete_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_rule_group)

Asynchronous method. Use `await delete_rule_group(...)` for a synchronous call.

Arguments mapping described in
[DeleteRuleGroupRequestRequestTypeDef](./type_defs.md#deleterulegrouprequestrequesttypedef).

Keyword-only arguments:

- `RuleGroupName`: `str`
- `RuleGroupArn`: `str`
- `Type`: [RuleGroupTypeType](./literals.md#rulegrouptypetype)

Returns a `Coroutine` for
[DeleteRuleGroupResponseTypeDef](./type_defs.md#deleterulegroupresponsetypedef).

<a id="describe_firewall"></a>

### describe_firewall

Returns the data objects for the specified firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").describe_firewall` method.

Boto3 documentation:
[NetworkFirewall.Client.describe_firewall](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_firewall)

Asynchronous method. Use `await describe_firewall(...)` for a synchronous call.

Arguments mapping described in
[DescribeFirewallRequestRequestTypeDef](./type_defs.md#describefirewallrequestrequesttypedef).

Keyword-only arguments:

- `FirewallName`: `str`
- `FirewallArn`: `str`

Returns a `Coroutine` for
[DescribeFirewallResponseTypeDef](./type_defs.md#describefirewallresponsetypedef).

<a id="describe_firewall_policy"></a>

### describe_firewall_policy

Returns the data objects for the specified firewall policy.

Type annotations for
`aiobotocore.create_client("network-firewall").describe_firewall_policy`
method.

Boto3 documentation:
[NetworkFirewall.Client.describe_firewall_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_firewall_policy)

Asynchronous method. Use `await describe_firewall_policy(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFirewallPolicyRequestRequestTypeDef](./type_defs.md#describefirewallpolicyrequestrequesttypedef).

Keyword-only arguments:

- `FirewallPolicyName`: `str`
- `FirewallPolicyArn`: `str`

Returns a `Coroutine` for
[DescribeFirewallPolicyResponseTypeDef](./type_defs.md#describefirewallpolicyresponsetypedef).

<a id="describe_logging_configuration"></a>

### describe_logging_configuration

Returns the logging configuration for the specified firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").describe_logging_configuration`
method.

Boto3 documentation:
[NetworkFirewall.Client.describe_logging_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_logging_configuration)

Asynchronous method. Use `await describe_logging_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLoggingConfigurationRequestRequestTypeDef](./type_defs.md#describeloggingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `FirewallArn`: `str`
- `FirewallName`: `str`

Returns a `Coroutine` for
[DescribeLoggingConfigurationResponseTypeDef](./type_defs.md#describeloggingconfigurationresponsetypedef).

<a id="describe_resource_policy"></a>

### describe_resource_policy

Retrieves a resource policy that you created in a PutResourcePolicy request.

Type annotations for
`aiobotocore.create_client("network-firewall").describe_resource_policy`
method.

Boto3 documentation:
[NetworkFirewall.Client.describe_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_resource_policy)

Asynchronous method. Use `await describe_resource_policy(...)` for a
synchronous call.

Arguments mapping described in
[DescribeResourcePolicyRequestRequestTypeDef](./type_defs.md#describeresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeResourcePolicyResponseTypeDef](./type_defs.md#describeresourcepolicyresponsetypedef).

<a id="describe_rule_group"></a>

### describe_rule_group

Returns the data objects for the specified rule group.

Type annotations for
`aiobotocore.create_client("network-firewall").describe_rule_group` method.

Boto3 documentation:
[NetworkFirewall.Client.describe_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_rule_group)

Asynchronous method. Use `await describe_rule_group(...)` for a synchronous
call.

Arguments mapping described in
[DescribeRuleGroupRequestRequestTypeDef](./type_defs.md#describerulegrouprequestrequesttypedef).

Keyword-only arguments:

- `RuleGroupName`: `str`
- `RuleGroupArn`: `str`
- `Type`: [RuleGroupTypeType](./literals.md#rulegrouptypetype)

Returns a `Coroutine` for
[DescribeRuleGroupResponseTypeDef](./type_defs.md#describerulegroupresponsetypedef).

<a id="describe_rule_group_metadata"></a>

### describe_rule_group_metadata

High-level information about a rule group, returned by operations like create
and describe.

Type annotations for
`aiobotocore.create_client("network-firewall").describe_rule_group_metadata`
method.

Boto3 documentation:
[NetworkFirewall.Client.describe_rule_group_metadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_rule_group_metadata)

Asynchronous method. Use `await describe_rule_group_metadata(...)` for a
synchronous call.

Arguments mapping described in
[DescribeRuleGroupMetadataRequestRequestTypeDef](./type_defs.md#describerulegroupmetadatarequestrequesttypedef).

Keyword-only arguments:

- `RuleGroupName`: `str`
- `RuleGroupArn`: `str`
- `Type`: [RuleGroupTypeType](./literals.md#rulegrouptypetype)

Returns a `Coroutine` for
[DescribeRuleGroupMetadataResponseTypeDef](./type_defs.md#describerulegroupmetadataresponsetypedef).

<a id="disassociate_subnets"></a>

### disassociate_subnets

Removes the specified subnet associations from the firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").disassociate_subnets` method.

Boto3 documentation:
[NetworkFirewall.Client.disassociate_subnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.disassociate_subnets)

Asynchronous method. Use `await disassociate_subnets(...)` for a synchronous
call.

Arguments mapping described in
[DisassociateSubnetsRequestRequestTypeDef](./type_defs.md#disassociatesubnetsrequestrequesttypedef).

Keyword-only arguments:

- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `UpdateToken`: `str`
- `FirewallArn`: `str`
- `FirewallName`: `str`

Returns a `Coroutine` for
[DisassociateSubnetsResponseTypeDef](./type_defs.md#disassociatesubnetsresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("network-firewall").generate_presigned_url` method.

Boto3 documentation:
[NetworkFirewall.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_firewall_policies"></a>

### list_firewall_policies

Retrieves the metadata for the firewall policies that you have defined.

Type annotations for
`aiobotocore.create_client("network-firewall").list_firewall_policies` method.

Boto3 documentation:
[NetworkFirewall.Client.list_firewall_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_firewall_policies)

Asynchronous method. Use `await list_firewall_policies(...)` for a synchronous
call.

Arguments mapping described in
[ListFirewallPoliciesRequestRequestTypeDef](./type_defs.md#listfirewallpoliciesrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListFirewallPoliciesResponseTypeDef](./type_defs.md#listfirewallpoliciesresponsetypedef).

<a id="list_firewalls"></a>

### list_firewalls

Retrieves the metadata for the firewalls that you have defined.

Type annotations for
`aiobotocore.create_client("network-firewall").list_firewalls` method.

Boto3 documentation:
[NetworkFirewall.Client.list_firewalls](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_firewalls)

Asynchronous method. Use `await list_firewalls(...)` for a synchronous call.

Arguments mapping described in
[ListFirewallsRequestRequestTypeDef](./type_defs.md#listfirewallsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `VpcIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListFirewallsResponseTypeDef](./type_defs.md#listfirewallsresponsetypedef).

<a id="list_rule_groups"></a>

### list_rule_groups

Retrieves the metadata for the rule groups that you have defined.

Type annotations for
`aiobotocore.create_client("network-firewall").list_rule_groups` method.

Boto3 documentation:
[NetworkFirewall.Client.list_rule_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_rule_groups)

Asynchronous method. Use `await list_rule_groups(...)` for a synchronous call.

Arguments mapping described in
[ListRuleGroupsRequestRequestTypeDef](./type_defs.md#listrulegroupsrequestrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `Scope`: [ResourceManagedStatusType](./literals.md#resourcemanagedstatustype)

Returns a `Coroutine` for
[ListRuleGroupsResponseTypeDef](./type_defs.md#listrulegroupsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Retrieves the tags associated with the specified resource.

Type annotations for
`aiobotocore.create_client("network-firewall").list_tags_for_resource` method.

Boto3 documentation:
[NetworkFirewall.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_resource_policy"></a>

### put_resource_policy

Creates or updates an AWS Identity and Access Management policy for your rule
group or firewall policy.

Type annotations for
`aiobotocore.create_client("network-firewall").put_resource_policy` method.

Boto3 documentation:
[NetworkFirewall.Client.put_resource_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.put_resource_policy)

Asynchronous method. Use `await put_resource_policy(...)` for a synchronous
call.

Arguments mapping described in
[PutResourcePolicyRequestRequestTypeDef](./type_defs.md#putresourcepolicyrequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Policy`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Adds the specified tags to the specified resource.

Type annotations for
`aiobotocore.create_client("network-firewall").tag_resource` method.

Boto3 documentation:
[NetworkFirewall.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes the tags with the specified keys from the specified resource.

Type annotations for
`aiobotocore.create_client("network-firewall").untag_resource` method.

Boto3 documentation:
[NetworkFirewall.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_firewall_delete_protection"></a>

### update_firewall_delete_protection

Modifies the flag, `DeleteProtection` , which indicates whether it is possible
to delete the firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").update_firewall_delete_protection`
method.

Boto3 documentation:
[NetworkFirewall.Client.update_firewall_delete_protection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_delete_protection)

Asynchronous method. Use `await update_firewall_delete_protection(...)` for a
synchronous call.

Arguments mapping described in
[UpdateFirewallDeleteProtectionRequestRequestTypeDef](./type_defs.md#updatefirewalldeleteprotectionrequestrequesttypedef).

Keyword-only arguments:

- `DeleteProtection`: `bool` *(required)*
- `UpdateToken`: `str`
- `FirewallArn`: `str`
- `FirewallName`: `str`

Returns a `Coroutine` for
[UpdateFirewallDeleteProtectionResponseTypeDef](./type_defs.md#updatefirewalldeleteprotectionresponsetypedef).

<a id="update_firewall_description"></a>

### update_firewall_description

Modifies the description for the specified firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").update_firewall_description`
method.

Boto3 documentation:
[NetworkFirewall.Client.update_firewall_description](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_description)

Asynchronous method. Use `await update_firewall_description(...)` for a
synchronous call.

Arguments mapping described in
[UpdateFirewallDescriptionRequestRequestTypeDef](./type_defs.md#updatefirewalldescriptionrequestrequesttypedef).

Keyword-only arguments:

- `UpdateToken`: `str`
- `FirewallArn`: `str`
- `FirewallName`: `str`
- `Description`: `str`

Returns a `Coroutine` for
[UpdateFirewallDescriptionResponseTypeDef](./type_defs.md#updatefirewalldescriptionresponsetypedef).

<a id="update_firewall_policy"></a>

### update_firewall_policy

Updates the properties of the specified firewall policy.

Type annotations for
`aiobotocore.create_client("network-firewall").update_firewall_policy` method.

Boto3 documentation:
[NetworkFirewall.Client.update_firewall_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_policy)

Asynchronous method. Use `await update_firewall_policy(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFirewallPolicyRequestRequestTypeDef](./type_defs.md#updatefirewallpolicyrequestrequesttypedef).

Keyword-only arguments:

- `UpdateToken`: `str` *(required)*
- `FirewallPolicy`:
  [FirewallPolicyTypeDef](./type_defs.md#firewallpolicytypedef) *(required)*
- `FirewallPolicyArn`: `str`
- `FirewallPolicyName`: `str`
- `Description`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[UpdateFirewallPolicyResponseTypeDef](./type_defs.md#updatefirewallpolicyresponsetypedef).

<a id="update_firewall_policy_change_protection"></a>

### update_firewall_policy_change_protection

Modifies the flag, `ChangeProtection` , which indicates whether it is possible
to change the firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").update_firewall_policy_change_protection`
method.

Boto3 documentation:
[NetworkFirewall.Client.update_firewall_policy_change_protection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_policy_change_protection)

Asynchronous method. Use `await update_firewall_policy_change_protection(...)`
for a synchronous call.

Arguments mapping described in
[UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef](./type_defs.md#updatefirewallpolicychangeprotectionrequestrequesttypedef).

Keyword-only arguments:

- `FirewallPolicyChangeProtection`: `bool` *(required)*
- `UpdateToken`: `str`
- `FirewallArn`: `str`
- `FirewallName`: `str`

Returns a `Coroutine` for
[UpdateFirewallPolicyChangeProtectionResponseTypeDef](./type_defs.md#updatefirewallpolicychangeprotectionresponsetypedef).

<a id="update_logging_configuration"></a>

### update_logging_configuration

Sets the logging configuration for the specified firewall.

Type annotations for
`aiobotocore.create_client("network-firewall").update_logging_configuration`
method.

Boto3 documentation:
[NetworkFirewall.Client.update_logging_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_logging_configuration)

Asynchronous method. Use `await update_logging_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateLoggingConfigurationRequestRequestTypeDef](./type_defs.md#updateloggingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `FirewallArn`: `str`
- `FirewallName`: `str`
- `LoggingConfiguration`:
  [LoggingConfigurationTypeDef](./type_defs.md#loggingconfigurationtypedef)

Returns a `Coroutine` for
[UpdateLoggingConfigurationResponseTypeDef](./type_defs.md#updateloggingconfigurationresponsetypedef).

<a id="update_rule_group"></a>

### update_rule_group

Updates the rule settings for the specified rule group.

Type annotations for
`aiobotocore.create_client("network-firewall").update_rule_group` method.

Boto3 documentation:
[NetworkFirewall.Client.update_rule_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_rule_group)

Asynchronous method. Use `await update_rule_group(...)` for a synchronous call.

Arguments mapping described in
[UpdateRuleGroupRequestRequestTypeDef](./type_defs.md#updaterulegrouprequestrequesttypedef).

Keyword-only arguments:

- `UpdateToken`: `str` *(required)*
- `RuleGroupArn`: `str`
- `RuleGroupName`: `str`
- `RuleGroup`: [RuleGroupTypeDef](./type_defs.md#rulegrouptypedef)
- `Rules`: `str`
- `Type`: [RuleGroupTypeType](./literals.md#rulegrouptypetype)
- `Description`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[UpdateRuleGroupResponseTypeDef](./type_defs.md#updaterulegroupresponsetypedef).

<a id="update_subnet_change_protection"></a>

### update_subnet_change_protection

See also: \[AWS API
Documentation\](https://docs.aws.amazon.com/goto/WebAPI/network-
firewall-2020-11-12/UpdateSubnetChangeProtection).

Type annotations for
`aiobotocore.create_client("network-firewall").update_subnet_change_protection`
method.

Boto3 documentation:
[NetworkFirewall.Client.update_subnet_change_protection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_subnet_change_protection)

Asynchronous method. Use `await update_subnet_change_protection(...)` for a
synchronous call.

Arguments mapping described in
[UpdateSubnetChangeProtectionRequestRequestTypeDef](./type_defs.md#updatesubnetchangeprotectionrequestrequesttypedef).

Keyword-only arguments:

- `SubnetChangeProtection`: `bool` *(required)*
- `UpdateToken`: `str`
- `FirewallArn`: `str`
- `FirewallName`: `str`

Returns a `Coroutine` for
[UpdateSubnetChangeProtectionResponseTypeDef](./type_defs.md#updatesubnetchangeprotectionresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for
`aiobotocore.create_client("network-firewall").get_paginator` method with
overloads.

- `client.get_paginator("list_firewall_policies")` ->
  [ListFirewallPoliciesPaginator](./paginators.md#listfirewallpoliciespaginator)
- `client.get_paginator("list_firewalls")` ->
  [ListFirewallsPaginator](./paginators.md#listfirewallspaginator)
- `client.get_paginator("list_rule_groups")` ->
  [ListRuleGroupsPaginator](./paginators.md#listrulegroupspaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
