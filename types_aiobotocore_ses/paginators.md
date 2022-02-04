<a id="paginators-for-aiobotocore-ses-module"></a>

# Paginators for aiobotocore SES module

> [Index](..) > [SES](.) > Paginators

Auto-generated documentation for
[SES](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES)
type annotations stubs module
[types-aiobotocore-ses](https://pypi.org/project/types-aiobotocore-ses/).

- [Paginators for aiobotocore SES module](#paginators-for-aiobotocore-ses-module)
  - [ListConfigurationSetsPaginator](#listconfigurationsetspaginator)
  - [ListCustomVerificationEmailTemplatesPaginator](#listcustomverificationemailtemplatespaginator)
  - [ListIdentitiesPaginator](#listidentitiespaginator)
  - [ListReceiptRuleSetsPaginator](#listreceiptrulesetspaginator)
  - [ListTemplatesPaginator](#listtemplatespaginator)

<a id="listconfigurationsetspaginator"></a>

## ListConfigurationSetsPaginator

Type annotations for
`aiobotocore.create_client("ses").get_paginator("list_configuration_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ses.paginator import ListConfigurationSetsPaginator

def get_list_configuration_sets_paginator() -> ListConfigurationSetsPaginator:
    return Session().create_client("ses").get_paginator("list_configuration_sets")
```

Boto3 documentation:
[SES.Paginator.ListConfigurationSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListConfigurationSets)

Arguments for `ListConfigurationSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListConfigurationSetsPaginator.paginate` returns
`_PageIterator`\[[ListConfigurationSetsResponseTypeDef](./type_defs.md#listconfigurationsetsresponsetypedef)\].

<a id="listcustomverificationemailtemplatespaginator"></a>

## ListCustomVerificationEmailTemplatesPaginator

Type annotations for
`aiobotocore.create_client("ses").get_paginator("list_custom_verification_email_templates")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ses.paginator import ListCustomVerificationEmailTemplatesPaginator

def get_list_custom_verification_email_templates_paginator() -> ListCustomVerificationEmailTemplatesPaginator:
    return Session().create_client("ses").get_paginator("list_custom_verification_email_templates")
```

Boto3 documentation:
[SES.Paginator.ListCustomVerificationEmailTemplates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListCustomVerificationEmailTemplates)

Arguments for `ListCustomVerificationEmailTemplatesPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListCustomVerificationEmailTemplatesPaginator.paginate` returns
`_PageIterator`\[[ListCustomVerificationEmailTemplatesResponseTypeDef](./type_defs.md#listcustomverificationemailtemplatesresponsetypedef)\].

<a id="listidentitiespaginator"></a>

## ListIdentitiesPaginator

Type annotations for
`aiobotocore.create_client("ses").get_paginator("list_identities")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ses.paginator import ListIdentitiesPaginator

def get_list_identities_paginator() -> ListIdentitiesPaginator:
    return Session().create_client("ses").get_paginator("list_identities")
```

Boto3 documentation:
[SES.Paginator.ListIdentities](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListIdentities)

Arguments for `ListIdentitiesPaginator.paginate` method:

- `IdentityType`: [IdentityTypeType](./literals.md#identitytypetype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListIdentitiesPaginator.paginate` returns
`_PageIterator`\[[ListIdentitiesResponseTypeDef](./type_defs.md#listidentitiesresponsetypedef)\].

<a id="listreceiptrulesetspaginator"></a>

## ListReceiptRuleSetsPaginator

Type annotations for
`aiobotocore.create_client("ses").get_paginator("list_receipt_rule_sets")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ses.paginator import ListReceiptRuleSetsPaginator

def get_list_receipt_rule_sets_paginator() -> ListReceiptRuleSetsPaginator:
    return Session().create_client("ses").get_paginator("list_receipt_rule_sets")
```

Boto3 documentation:
[SES.Paginator.ListReceiptRuleSets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListReceiptRuleSets)

Arguments for `ListReceiptRuleSetsPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListReceiptRuleSetsPaginator.paginate` returns
`_PageIterator`\[[ListReceiptRuleSetsResponseTypeDef](./type_defs.md#listreceiptrulesetsresponsetypedef)\].

<a id="listtemplatespaginator"></a>

## ListTemplatesPaginator

Type annotations for
`aiobotocore.create_client("ses").get_paginator("list_templates")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_ses.paginator import ListTemplatesPaginator

def get_list_templates_paginator() -> ListTemplatesPaginator:
    return Session().create_client("ses").get_paginator("list_templates")
```

Boto3 documentation:
[SES.Paginator.ListTemplates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListTemplates)

Arguments for `ListTemplatesPaginator.paginate` method:

- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListTemplatesPaginator.paginate` returns
`_PageIterator`\[[ListTemplatesResponseTypeDef](./type_defs.md#listtemplatesresponsetypedef)\].
