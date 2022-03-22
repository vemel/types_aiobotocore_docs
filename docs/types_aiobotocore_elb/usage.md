<a id="examples-for-aiobotocore-elasticloadbalancing-module"></a>

# Examples for aiobotocore ElasticLoadBalancing module

> [Index](../README.md) > [ElasticLoadBalancing](./README.md) > Examples

- [Examples for aiobotocore ElasticLoadBalancing module](#examples-for-aiobotocore-elasticloadbalancing-module)
  - [Client](#client)
    - [Implicit type annotations](#implicit-type-annotations)
    - [Explicit type annotations](#explicit-type-annotations)

<a id="client"></a>

## Client

<a id="implicit-type-annotations"></a>

### Implicit type annotations

Can be used with `types-aiobotocore[elb]` package installed.

Write your `ElasticLoadBalancing` code as usual, type checking and code
completion should work out of the box.

```python
from aiobotocore.session import get_session


session = get_session()

# client has type ElasticLoadBalancingClient
# and provides type checking and code completion
async with session.create_client("elb") as client:
    
    # result has type Dict[str, Any]
    # and provides type checking and code completion
    # IDE should show a hint with argument names and types
    result = await client.add_tags()
    

    
    # paginator has type DescribeAccountLimitsPaginator and provides type checking
    # and code completion for paginate method
    paginator = client.get_paginator("describe_account_limits")
    async for item in paginator.paginate(...):
        # item has type DescribeAccountLimitsOutputTypeDef
        print(item)
    

    
    # waiter has type AnyInstanceInServiceWaiter and provides type checking
    # and code completion for wait method
    waiter = client.get_waiter("any_instance_in_service")
    await waiter.wait()
    
```

<a id="explicit-type-annotations"></a>

### Explicit type annotations

With `types-aiobotocore-lite[elb]` or a standalone `types_aiobotocore_elb`
package, you have to explicitly specify `client: ElasticLoadBalancingClient`
type annotation.

All other type annotations are optional, as types should be discovered
automatically. However, these type annotations can be helpful in your functions
and methods.

```python
from aiobotocore.session import get_session

from types_aiobotocore_elb.client import ElasticLoadBalancingClient
from types_aiobotocore_elb.type_defs import Dict[str, Any]
from types_aiobotocore_elb.paginator import DescribeAccountLimitsPaginator
from types_aiobotocore_elb.waiter import AnyInstanceInServiceWaiter
from types_aiobotocore_elb.literals import PaginatorName
from types_aiobotocore_elb.literals import WaiterName


session = get_session()

async with session.create_client("elb") as client:
    client: ElasticLoadBalancingClient

    
    result: Dict[str, Any] = client.add_tags()
    

    
    paginator_name: PaginatorName = "describe_account_limits"
    paginator: DescribeAccountLimitsPaginator = client.get_paginator(paginator_name)
    async for item in paginator.paginate(...):
        item: DescribeAccountLimitsOutputTypeDef
        print(item)
    

    
    waiter_name: WaiterName = "any_instance_in_service"
    waiter: AnyInstanceInServiceWaiter = client.get_waiter(waiter_name)
    await waiter.wait()
    
```
