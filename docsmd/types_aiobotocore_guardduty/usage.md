# Examples

> [Index](../README.md) > [GuardDuty](./README.md) > Examples

!!! note ""

    Auto-generated documentation for [GuardDuty](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
    type annotations stubs module [types-aiobotocore-guardduty](https://pypi.org/project/types-aiobotocore-guardduty/).

## Client

### Implicit type annotations

Can be used with `types-aiobotocore[guardduty]` package installed.

Write your `GuardDuty` code as usual,
type checking and code completion should work out of the box.



=== "Client"

    ```python title="Client usage example"
    from aiobotocore.session import get_session


    session = get_session()

    async with session.create_client("guardduty") as client:  # (1)
        result = await client.create_detector()  # (2)
    ```

    1. client: [GuardDutyClient](./client.md)
    2. result: [:material-code-braces: CreateDetectorResponseTypeDef](./type_defs.md#createdetectorresponsetypedef) 



=== "Paginators"

    ```python title="Paginator usage example"
    from aiobotocore.session import get_session


    session = get_session()

    async with session.create_client("guardduty") as client:  # (1)
        paginator = client.get_paginator("list_detectors")  # (2)
        async for item in paginator.paginate(...):
            print(item)  # (3)
    ```

    1. client: [GuardDutyClient](./client.md)
    2. paginator: [ListDetectorsPaginator](./paginators.md#listdetectorspaginator)
    3. item: [:material-code-braces: ListDetectorsResponseTypeDef](./type_defs.md#listdetectorsresponsetypedef) 




### Explicit type annotations

With `types-aiobotocore-lite[guardduty]`
or a standalone `types_aiobotocore_guardduty` package, you have to explicitly specify
`client: GuardDutyClient` type annotation.

All other type annotations are optional, as types should be discovered automatically.
However, these type annotations can be helpful in your functions and methods.


=== "Client"

    ```python title="Client usage example"
    from aiobotocore.session import get_session

    from types_aiobotocore_guardduty.client import GuardDutyClient
    from types_aiobotocore_guardduty.type_defs import CreateDetectorResponseTypeDef
    from types_aiobotocore_guardduty.type_defs import CreateDetectorRequestRequestTypeDef


    session = get_session()

    async with session.create_client("guardduty") as client:
        client: GuardDutyClient
        kwargs: CreateDetectorRequestRequestTypeDef = {...}
        result: CreateDetectorResponseTypeDef = await client.create_detector(**kwargs)
    ```



=== "Paginators"

    ```python title="Paginator usage example"
    from aiobotocore.session import get_session

    from types_aiobotocore_guardduty.client import GuardDutyClient
    from types_aiobotocore_guardduty.paginator import ListDetectorsPaginator
    from types_aiobotocore_guardduty.type_defs import ListDetectorsResponseTypeDef


    session = get_session()

    async with session.create_client("guardduty") as client:
        client: GuardDutyClient
        paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
        async for item in paginator.paginate(...):
            item: ListDetectorsResponseTypeDef
            print(item)
    ```


