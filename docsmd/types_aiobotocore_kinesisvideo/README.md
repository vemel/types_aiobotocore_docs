# KinesisVideo module

> [Index](../README.md) > KinesisVideo


!!! note ""

    Auto-generated documentation for [KinesisVideo](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
    type annotations stubs module [types-aiobotocore-kinesisvideo](https://pypi.org/project/types-aiobotocore-kinesisvideo/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `KinesisVideo`.

### From PyPI with pip

Install `types-aiobotocore` for `KinesisVideo` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[kinesisvideo]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[kinesisvideo]'


# standalone installation
python -m pip install types-aiobotocore-kinesisvideo
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-kinesisvideo
```

## Usage

Code samples can be found in [Examples](./usage.md).

## KinesisVideoClient

Type annotations and code completion for  `#!python session.create_client("kinesisvideo")` as [KinesisVideoClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_kinesisvideo.client import KinesisVideoClient


session = get_session()
async with session.create_client("kinesisvideo") as client:
    client: KinesisVideoClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("kinesisvideo").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_kinesisvideo.paginator import ListSignalingChannelsPaginator

def get_list_signaling_channels_paginator() -> ListSignalingChannelsPaginator:
    return client.get_paginator("list_signaling_channels"))
```

- [ListSignalingChannelsPaginator](./paginators.md#listsignalingchannelspaginator)
- [ListStreamsPaginator](./paginators.md#liststreamspaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_kinesisvideo.literals import APINameType

def get_value() -> APINameType:
    return "GET_CLIP"
```

- [APINameType](./literals.md#apinametype)
- [ChannelProtocolType](./literals.md#channelprotocoltype)
- [ChannelRoleType](./literals.md#channelroletype)
- [ChannelTypeType](./literals.md#channeltypetype)
- [ComparisonOperatorType](./literals.md#comparisonoperatortype)
- [ListSignalingChannelsPaginatorName](./literals.md#listsignalingchannelspaginatorname)
- [ListStreamsPaginatorName](./literals.md#liststreamspaginatorname)
- [StatusType](./literals.md#statustype)
- [UpdateDataRetentionOperationType](./literals.md#updatedataretentionoperationtype)
- [KinesisVideoServiceName](./literals.md#kinesisvideoservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_kinesisvideo.type_defs import ChannelInfoTypeDef

def get_value() -> ChannelInfoTypeDef:
    return {
        "ChannelName": ...,
    }
```

- [ChannelInfoTypeDef](./type_defs.md#channelinfotypedef)
- [ChannelNameConditionTypeDef](./type_defs.md#channelnameconditiontypedef)
- [CreateSignalingChannelInputRequestTypeDef](./type_defs.md#createsignalingchannelinputrequesttypedef)
- [CreateSignalingChannelOutputTypeDef](./type_defs.md#createsignalingchanneloutputtypedef)
- [CreateStreamInputRequestTypeDef](./type_defs.md#createstreaminputrequesttypedef)
- [CreateStreamOutputTypeDef](./type_defs.md#createstreamoutputtypedef)
- [DeleteSignalingChannelInputRequestTypeDef](./type_defs.md#deletesignalingchannelinputrequesttypedef)
- [DeleteStreamInputRequestTypeDef](./type_defs.md#deletestreaminputrequesttypedef)
- [DescribeSignalingChannelInputRequestTypeDef](./type_defs.md#describesignalingchannelinputrequesttypedef)
- [DescribeSignalingChannelOutputTypeDef](./type_defs.md#describesignalingchanneloutputtypedef)
- [DescribeStreamInputRequestTypeDef](./type_defs.md#describestreaminputrequesttypedef)
- [DescribeStreamOutputTypeDef](./type_defs.md#describestreamoutputtypedef)
- [GetDataEndpointInputRequestTypeDef](./type_defs.md#getdataendpointinputrequesttypedef)
- [GetDataEndpointOutputTypeDef](./type_defs.md#getdataendpointoutputtypedef)
- [GetSignalingChannelEndpointInputRequestTypeDef](./type_defs.md#getsignalingchannelendpointinputrequesttypedef)
- [GetSignalingChannelEndpointOutputTypeDef](./type_defs.md#getsignalingchannelendpointoutputtypedef)
- [ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef](./type_defs.md#listsignalingchannelsinputlistsignalingchannelspaginatetypedef)
- [ListSignalingChannelsInputRequestTypeDef](./type_defs.md#listsignalingchannelsinputrequesttypedef)
- [ListSignalingChannelsOutputTypeDef](./type_defs.md#listsignalingchannelsoutputtypedef)
- [ListStreamsInputListStreamsPaginateTypeDef](./type_defs.md#liststreamsinputliststreamspaginatetypedef)
- [ListStreamsInputRequestTypeDef](./type_defs.md#liststreamsinputrequesttypedef)
- [ListStreamsOutputTypeDef](./type_defs.md#liststreamsoutputtypedef)
- [ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef)
- [ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef)
- [ListTagsForStreamInputRequestTypeDef](./type_defs.md#listtagsforstreaminputrequesttypedef)
- [ListTagsForStreamOutputTypeDef](./type_defs.md#listtagsforstreamoutputtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResourceEndpointListItemTypeDef](./type_defs.md#resourceendpointlistitemtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SingleMasterChannelEndpointConfigurationTypeDef](./type_defs.md#singlemasterchannelendpointconfigurationtypedef)
- [SingleMasterConfigurationTypeDef](./type_defs.md#singlemasterconfigurationtypedef)
- [StreamInfoTypeDef](./type_defs.md#streaminfotypedef)
- [StreamNameConditionTypeDef](./type_defs.md#streamnameconditiontypedef)
- [TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef)
- [TagStreamInputRequestTypeDef](./type_defs.md#tagstreaminputrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef)
- [UntagStreamInputRequestTypeDef](./type_defs.md#untagstreaminputrequesttypedef)
- [UpdateDataRetentionInputRequestTypeDef](./type_defs.md#updatedataretentioninputrequesttypedef)
- [UpdateSignalingChannelInputRequestTypeDef](./type_defs.md#updatesignalingchannelinputrequesttypedef)
- [UpdateStreamInputRequestTypeDef](./type_defs.md#updatestreaminputrequesttypedef)

