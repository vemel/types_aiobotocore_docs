<a id="paginators-for-aiobotocore-route53domains-module"></a>

# Paginators for aiobotocore Route53Domains module

> [Index](..) > [Route53Domains](.) > Paginators

Auto-generated documentation for
[Route53Domains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains)
type annotations stubs module
[types-aiobotocore-route53domains](https://pypi.org/project/types-aiobotocore-route53domains/).

- [Paginators for aiobotocore Route53Domains module](#paginators-for-aiobotocore-route53domains-module)
  - [ListDomainsPaginator](#listdomainspaginator)
  - [ListOperationsPaginator](#listoperationspaginator)
  - [ListPricesPaginator](#listpricespaginator)
  - [ViewBillingPaginator](#viewbillingpaginator)

<a id="listdomainspaginator"></a>

## ListDomainsPaginator

Type annotations for
`aiobotocore.create_client("route53domains").get_paginator("list_domains")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_route53domains.paginator import ListDomainsPaginator

def get_list_domains_paginator() -> ListDomainsPaginator:
    return Session().create_client("route53domains").get_paginator("list_domains")
```

Boto3 documentation:
[Route53Domains.Paginator.ListDomains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListDomains)

Arguments for `ListDomainsPaginator.paginate` method:

- `FilterConditions`:
  `Sequence`\[[FilterConditionTypeDef](./type_defs.md#filterconditiontypedef)\]
- `SortCondition`: [SortConditionTypeDef](./type_defs.md#sortconditiontypedef)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDomainsPaginator.paginate` returns
`_PageIterator`\[[ListDomainsResponseTypeDef](./type_defs.md#listdomainsresponsetypedef)\].

<a id="listoperationspaginator"></a>

## ListOperationsPaginator

Type annotations for
`aiobotocore.create_client("route53domains").get_paginator("list_operations")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_route53domains.paginator import ListOperationsPaginator

def get_list_operations_paginator() -> ListOperationsPaginator:
    return Session().create_client("route53domains").get_paginator("list_operations")
```

Boto3 documentation:
[Route53Domains.Paginator.ListOperations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListOperations)

Arguments for `ListOperationsPaginator.paginate` method:

- `SubmittedSince`: `Union`\[`datetime`, `str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListOperationsPaginator.paginate` returns
`_PageIterator`\[[ListOperationsResponseTypeDef](./type_defs.md#listoperationsresponsetypedef)\].

<a id="listpricespaginator"></a>

## ListPricesPaginator

Type annotations for
`aiobotocore.create_client("route53domains").get_paginator("list_prices")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_route53domains.paginator import ListPricesPaginator

def get_list_prices_paginator() -> ListPricesPaginator:
    return Session().create_client("route53domains").get_paginator("list_prices")
```

Boto3 documentation:
[Route53Domains.Paginator.ListPrices](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListPrices)

Arguments for `ListPricesPaginator.paginate` method:

- `Tld`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListPricesPaginator.paginate` returns
`_PageIterator`\[[ListPricesResponseTypeDef](./type_defs.md#listpricesresponsetypedef)\].

<a id="viewbillingpaginator"></a>

## ViewBillingPaginator

Type annotations for
`aiobotocore.create_client("route53domains").get_paginator("view_billing")`.

Can be used directly:

```python
from aiobotocore.session import Session

from types_aiobotocore_route53domains.paginator import ViewBillingPaginator

def get_view_billing_paginator() -> ViewBillingPaginator:
    return Session().create_client("route53domains").get_paginator("view_billing")
```

Boto3 documentation:
[Route53Domains.Paginator.ViewBilling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ViewBilling)

Arguments for `ViewBillingPaginator.paginate` method:

- `Start`: `Union`\[`datetime`, `str`\]
- `End`: `Union`\[`datetime`, `str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ViewBillingPaginator.paginate` returns
`_PageIterator`\[[ViewBillingResponseTypeDef](./type_defs.md#viewbillingresponsetypedef)\].
