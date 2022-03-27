# Examples

> [Index](../README.md) > [MediaTailor](./README.md) > Examples

!!! note ""

    Auto-generated documentation for [MediaTailor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
    type annotations stubs module [types-aiobotocore-mediatailor](https://pypi.org/project/types-aiobotocore-mediatailor/).

## Client

### Implicit type annotations

Can be used with `types-aiobotocore[mediatailor]` package installed.

Write your `MediaTailor` code as usual,
type checking and code completion should work out of the box.



=== "Client"

    ```python title="Client usage example"
    from aiobotocore.session import get_session


    session = get_session()

    async with session.create_client("mediatailor") as client:  # (1)
        result = await client.configure_logs_for_playback_configuration()  # (2)
    ```

    1. client: [MediaTailorClient](./client.md)
    2. result: [:material-code-braces: ConfigureLogsForPlaybackConfigurationResponseTypeDef](./type_defs.md#configurelogsforplaybackconfigurationresponsetypedef) 



=== "Paginators"

    ```python title="Paginator usage example"
    from aiobotocore.session import get_session


    session = get_session()

    async with session.create_client("mediatailor") as client:  # (1)
        paginator = client.get_paginator("get_channel_schedule")  # (2)
        async for item in paginator.paginate(...):
            print(item)  # (3)
    ```

    1. client: [MediaTailorClient](./client.md)
    2. paginator: [GetChannelSchedulePaginator](./paginators.md#getchannelschedulepaginator)
    3. item: [:material-code-braces: GetChannelScheduleResponseTypeDef](./type_defs.md#getchannelscheduleresponsetypedef) 




### Explicit type annotations

With `types-aiobotocore-lite[mediatailor]`
or a standalone `types_aiobotocore_mediatailor` package, you have to explicitly specify
`client: MediaTailorClient` type annotation.

All other type annotations are optional, as types should be discovered automatically.
However, these type annotations can be helpful in your functions and methods.


=== "Client"

    ```python title="Client usage example"
    from aiobotocore.session import get_session

    from types_aiobotocore_mediatailor.client import MediaTailorClient
    from types_aiobotocore_mediatailor.type_defs import ConfigureLogsForPlaybackConfigurationResponseTypeDef
    from types_aiobotocore_mediatailor.type_defs import ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef


    session = get_session()

    async with session.create_client("mediatailor") as client:
        client: MediaTailorClient
        kwargs: ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef = {...}
        result: ConfigureLogsForPlaybackConfigurationResponseTypeDef = await client.configure_logs_for_playback_configuration(**kwargs)
    ```



=== "Paginators"

    ```python title="Paginator usage example"
    from aiobotocore.session import get_session

    from types_aiobotocore_mediatailor.client import MediaTailorClient
    from types_aiobotocore_mediatailor.paginator import GetChannelSchedulePaginator
    from types_aiobotocore_mediatailor.type_defs import GetChannelScheduleResponseTypeDef


    session = get_session()

    async with session.create_client("mediatailor") as client:
        client: MediaTailorClient
        paginator: GetChannelSchedulePaginator = client.get_paginator("get_channel_schedule")
        async for item in paginator.paginate(...):
            item: GetChannelScheduleResponseTypeDef
            print(item)
    ```


