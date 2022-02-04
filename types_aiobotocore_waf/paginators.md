<a id="paginators-for-aiobotocore-waf-module"></a>

# Paginators for aiobotocore WAF module

> [Index](..) > [WAF](.) > Paginators

Auto-generated documentation for
[WAF](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF)
type annotations stubs module
[types-aiobotocore-waf](https://pypi.org/project/types-aiobotocore-waf/).

- [Paginators for aiobotocore WAF module](#paginators-for-aiobotocore-waf-module)
  - [GetRateBasedRuleManagedKeysPaginator](#getratebasedrulemanagedkeyspaginator)
  - [ListActivatedRulesInRuleGroupPaginator](#listactivatedrulesinrulegrouppaginator)
  - [ListByteMatchSetsPaginator](#listbytematchsetspaginator)
  - [ListGeoMatchSetsPaginator](#listgeomatchsetspaginator)
  - [ListIPSetsPaginator](#listipsetspaginator)
  - [ListLoggingConfigurationsPaginator](#listloggingconfigurationspaginator)
  - [ListRateBasedRulesPaginator](#listratebasedrulespaginator)
  - [ListRegexMatchSetsPaginator](#listregexmatchsetspaginator)
  - [ListRegexPatternSetsPaginator](#listregexpatternsetspaginator)
  - [ListRuleGroupsPaginator](#listrulegroupspaginator)
  - [ListRulesPaginator](#listrulespaginator)
  - [ListSizeConstraintSetsPaginator](#listsizeconstraintsetspaginator)
  - [ListSqlInjectionMatchSetsPaginator](#listsqlinjectionmatchsetspaginator)
  - [ListSubscribedRuleGroupsPaginator](#listsubscribedrulegroupspaginator)
  - [ListWebACLsPaginator](#listwebaclspaginator)
  - [ListXssMatchSetsPaginator](#listxssmatchsetspaginator)

<a id="getratebasedrulemanagedkeyspaginator"></a>

## GetRateBasedRuleManagedKeysPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("get_rate_based_rule_managed_keys")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import GetRateBasedRuleManagedKeysPaginator

def get_get_rate_based_rule_managed_keys_paginator() -> GetRateBasedRuleManagedKeysPaginator:
    return Session().create_client("waf").get_paginator("get_rate_based_rule_managed_keys")
```

Boto3 documentation:
[WAF.Paginator.GetRateBasedRuleManagedKeys](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.GetRateBasedRuleManagedKeys)

Arguments for `GetRateBasedRuleManagedKeysPaginator.paginate` method:

- `RuleId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetRateBasedRuleManagedKeysPaginator.paginate` returns
`_PageIterator`\[[GetRateBasedRuleManagedKeysResponseTypeDef](./type_defs.md#getratebasedrulemanagedkeysresponsetypedef)\].

<a id="listactivatedrulesinrulegrouppaginator"></a>

## ListActivatedRulesInRuleGroupPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_activated_rules_in_rule_group")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListActivatedRulesInRuleGroupPaginator

def get_list_activated_rules_in_rule_group_paginator() -> ListActivatedRulesInRuleGroupPaginator:
    return Session().create_client("waf").get_paginator("list_activated_rules_in_rule_group")
```

Boto3 documentation:
[WAF.Paginator.ListActivatedRulesInRuleGroup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListActivatedRulesInRuleGroup)

Arguments for `ListActivatedRulesInRuleGroupPaginator.paginate` method:

- `RuleGroupId`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListActivatedRulesInRuleGroupPaginator.paginate` returns
`_PageIterator`\[[ListActivatedRulesInRuleGroupResponseTypeDef](./type_defs.md#listactivatedrulesinrulegroupresponsetypedef)\].

<a id="listbytematchsetspaginator"></a>

## ListByteMatchSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_byte_match_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListByteMatchSetsPaginator

def get_list_byte_match_sets_paginator() -> ListByteMatchSetsPaginator:
    return Session().create_client("waf").get_paginator("list_byte_match_sets")
```

Boto3 documentation:
[WAF.Paginator.ListByteMatchSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListByteMatchSets)

Arguments for `ListByteMatchSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListByteMatchSetsPaginator.paginate` returns
`_PageIterator`\[[ListByteMatchSetsResponseTypeDef](./type_defs.md#listbytematchsetsresponsetypedef)\].

<a id="listgeomatchsetspaginator"></a>

## ListGeoMatchSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_geo_match_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListGeoMatchSetsPaginator

def get_list_geo_match_sets_paginator() -> ListGeoMatchSetsPaginator:
    return Session().create_client("waf").get_paginator("list_geo_match_sets")
```

Boto3 documentation:
[WAF.Paginator.ListGeoMatchSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListGeoMatchSets)

Arguments for `ListGeoMatchSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListGeoMatchSetsPaginator.paginate` returns
`_PageIterator`\[[ListGeoMatchSetsResponseTypeDef](./type_defs.md#listgeomatchsetsresponsetypedef)\].

<a id="listipsetspaginator"></a>

## ListIPSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_ip_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListIPSetsPaginator

def get_list_ip_sets_paginator() -> ListIPSetsPaginator:
    return Session().create_client("waf").get_paginator("list_ip_sets")
```

Boto3 documentation:
[WAF.Paginator.ListIPSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListIPSets)

Arguments for `ListIPSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListIPSetsPaginator.paginate` returns
`_PageIterator`\[[ListIPSetsResponseTypeDef](./type_defs.md#listipsetsresponsetypedef)\].

<a id="listloggingconfigurationspaginator"></a>

## ListLoggingConfigurationsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_logging_configurations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListLoggingConfigurationsPaginator

def get_list_logging_configurations_paginator() -> ListLoggingConfigurationsPaginator:
    return Session().create_client("waf").get_paginator("list_logging_configurations")
```

Boto3 documentation:
[WAF.Paginator.ListLoggingConfigurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListLoggingConfigurations)

Arguments for `ListLoggingConfigurationsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListLoggingConfigurationsPaginator.paginate` returns
`_PageIterator`\[[ListLoggingConfigurationsResponseTypeDef](./type_defs.md#listloggingconfigurationsresponsetypedef)\].

<a id="listratebasedrulespaginator"></a>

## ListRateBasedRulesPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_rate_based_rules")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListRateBasedRulesPaginator

def get_list_rate_based_rules_paginator() -> ListRateBasedRulesPaginator:
    return Session().create_client("waf").get_paginator("list_rate_based_rules")
```

Boto3 documentation:
[WAF.Paginator.ListRateBasedRules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListRateBasedRules)

Arguments for `ListRateBasedRulesPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRateBasedRulesPaginator.paginate` returns
`_PageIterator`\[[ListRateBasedRulesResponseTypeDef](./type_defs.md#listratebasedrulesresponsetypedef)\].

<a id="listregexmatchsetspaginator"></a>

## ListRegexMatchSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_regex_match_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListRegexMatchSetsPaginator

def get_list_regex_match_sets_paginator() -> ListRegexMatchSetsPaginator:
    return Session().create_client("waf").get_paginator("list_regex_match_sets")
```

Boto3 documentation:
[WAF.Paginator.ListRegexMatchSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListRegexMatchSets)

Arguments for `ListRegexMatchSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRegexMatchSetsPaginator.paginate` returns
`_PageIterator`\[[ListRegexMatchSetsResponseTypeDef](./type_defs.md#listregexmatchsetsresponsetypedef)\].

<a id="listregexpatternsetspaginator"></a>

## ListRegexPatternSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_regex_pattern_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListRegexPatternSetsPaginator

def get_list_regex_pattern_sets_paginator() -> ListRegexPatternSetsPaginator:
    return Session().create_client("waf").get_paginator("list_regex_pattern_sets")
```

Boto3 documentation:
[WAF.Paginator.ListRegexPatternSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListRegexPatternSets)

Arguments for `ListRegexPatternSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRegexPatternSetsPaginator.paginate` returns
`_PageIterator`\[[ListRegexPatternSetsResponseTypeDef](./type_defs.md#listregexpatternsetsresponsetypedef)\].

<a id="listrulegroupspaginator"></a>

## ListRuleGroupsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_rule_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListRuleGroupsPaginator

def get_list_rule_groups_paginator() -> ListRuleGroupsPaginator:
    return Session().create_client("waf").get_paginator("list_rule_groups")
```

Boto3 documentation:
[WAF.Paginator.ListRuleGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListRuleGroups)

Arguments for `ListRuleGroupsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRuleGroupsPaginator.paginate` returns
`_PageIterator`\[[ListRuleGroupsResponseTypeDef](./type_defs.md#listrulegroupsresponsetypedef)\].

<a id="listrulespaginator"></a>

## ListRulesPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_rules")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListRulesPaginator

def get_list_rules_paginator() -> ListRulesPaginator:
    return Session().create_client("waf").get_paginator("list_rules")
```

Boto3 documentation:
[WAF.Paginator.ListRules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListRules)

Arguments for `ListRulesPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListRulesPaginator.paginate` returns
`_PageIterator`\[[ListRulesResponseTypeDef](./type_defs.md#listrulesresponsetypedef)\].

<a id="listsizeconstraintsetspaginator"></a>

## ListSizeConstraintSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_size_constraint_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListSizeConstraintSetsPaginator

def get_list_size_constraint_sets_paginator() -> ListSizeConstraintSetsPaginator:
    return Session().create_client("waf").get_paginator("list_size_constraint_sets")
```

Boto3 documentation:
[WAF.Paginator.ListSizeConstraintSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListSizeConstraintSets)

Arguments for `ListSizeConstraintSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSizeConstraintSetsPaginator.paginate` returns
`_PageIterator`\[[ListSizeConstraintSetsResponseTypeDef](./type_defs.md#listsizeconstraintsetsresponsetypedef)\].

<a id="listsqlinjectionmatchsetspaginator"></a>

## ListSqlInjectionMatchSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_sql_injection_match_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListSqlInjectionMatchSetsPaginator

def get_list_sql_injection_match_sets_paginator() -> ListSqlInjectionMatchSetsPaginator:
    return Session().create_client("waf").get_paginator("list_sql_injection_match_sets")
```

Boto3 documentation:
[WAF.Paginator.ListSqlInjectionMatchSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListSqlInjectionMatchSets)

Arguments for `ListSqlInjectionMatchSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSqlInjectionMatchSetsPaginator.paginate` returns
`_PageIterator`\[[ListSqlInjectionMatchSetsResponseTypeDef](./type_defs.md#listsqlinjectionmatchsetsresponsetypedef)\].

<a id="listsubscribedrulegroupspaginator"></a>

## ListSubscribedRuleGroupsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_subscribed_rule_groups")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListSubscribedRuleGroupsPaginator

def get_list_subscribed_rule_groups_paginator() -> ListSubscribedRuleGroupsPaginator:
    return Session().create_client("waf").get_paginator("list_subscribed_rule_groups")
```

Boto3 documentation:
[WAF.Paginator.ListSubscribedRuleGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListSubscribedRuleGroups)

Arguments for `ListSubscribedRuleGroupsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListSubscribedRuleGroupsPaginator.paginate` returns
`_PageIterator`\[[ListSubscribedRuleGroupsResponseTypeDef](./type_defs.md#listsubscribedrulegroupsresponsetypedef)\].

<a id="listwebaclspaginator"></a>

## ListWebACLsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_web_acls")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListWebACLsPaginator

def get_list_web_acls_paginator() -> ListWebACLsPaginator:
    return Session().create_client("waf").get_paginator("list_web_acls")
```

Boto3 documentation:
[WAF.Paginator.ListWebACLs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListWebACLs)

Arguments for `ListWebACLsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListWebACLsPaginator.paginate` returns
`_PageIterator`\[[ListWebACLsResponseTypeDef](./type_defs.md#listwebaclsresponsetypedef)\].

<a id="listxssmatchsetspaginator"></a>

## ListXssMatchSetsPaginator

Type annotations for
`aiobotocore.create_client("waf").get_paginator("list_xss_match_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_waf.paginator import ListXssMatchSetsPaginator

def get_list_xss_match_sets_paginator() -> ListXssMatchSetsPaginator:
    return Session().create_client("waf").get_paginator("list_xss_match_sets")
```

Boto3 documentation:
[WAF.Paginator.ListXssMatchSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/waf.html#WAF.Paginator.ListXssMatchSets)

Arguments for `ListXssMatchSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListXssMatchSetsPaginator.paginate` returns
`_PageIterator`\[[ListXssMatchSetsResponseTypeDef](./type_defs.md#listxssmatchsetsresponsetypedef)\].
