# KinesisVideoArchivedMedia module

> [Index](../README.md) > KinesisVideoArchivedMedia


!!! note ""

    Auto-generated documentation for [KinesisVideoArchivedMedia](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia)
    type annotations stubs module [types-aiobotocore-kinesis-video-archived-media](https://pypi.org/project/types-aiobotocore-kinesis-video-archived-media/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `KinesisVideoArchivedMedia`.

### From PyPI with pip

Install `types-aiobotocore` for `KinesisVideoArchivedMedia` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[kinesis-video-archived-media]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[kinesis-video-archived-media]'


# standalone installation
python -m pip install types-aiobotocore-kinesis-video-archived-media
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-kinesis-video-archived-media
```

## Usage

Code samples can be found in [Examples](./usage.md).

## KinesisVideoArchivedMediaClient

Type annotations and code completion for  `#!python session.create_client("kinesis-video-archived-media")` as [KinesisVideoArchivedMediaClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_kinesis_video_archived_media.client import KinesisVideoArchivedMediaClient


session = get_session()
async with session.create_client("kinesis-video-archived-media") as client:
    client: KinesisVideoArchivedMediaClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("kinesis-video-archived-media").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_kinesis_video_archived_media.paginator import GetImagesPaginator

def get_get_images_paginator() -> GetImagesPaginator:
    return client.get_paginator("get_images"))
```

- [GetImagesPaginator](./paginators.md#getimagespaginator)
- [ListFragmentsPaginator](./paginators.md#listfragmentspaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_kinesis_video_archived_media.literals import ClipFragmentSelectorTypeType

def get_value() -> ClipFragmentSelectorTypeType:
    return "PRODUCER_TIMESTAMP"
```

- [ClipFragmentSelectorTypeType](./literals.md#clipfragmentselectortypetype)
- [ContainerFormatType](./literals.md#containerformattype)
- [DASHDisplayFragmentNumberType](./literals.md#dashdisplayfragmentnumbertype)
- [DASHDisplayFragmentTimestampType](./literals.md#dashdisplayfragmenttimestamptype)
- [DASHFragmentSelectorTypeType](./literals.md#dashfragmentselectortypetype)
- [DASHPlaybackModeType](./literals.md#dashplaybackmodetype)
- [FormatConfigKeyType](./literals.md#formatconfigkeytype)
- [FormatType](./literals.md#formattype)
- [FragmentSelectorTypeType](./literals.md#fragmentselectortypetype)
- [GetImagesPaginatorName](./literals.md#getimagespaginatorname)
- [HLSDiscontinuityModeType](./literals.md#hlsdiscontinuitymodetype)
- [HLSDisplayFragmentTimestampType](./literals.md#hlsdisplayfragmenttimestamptype)
- [HLSFragmentSelectorTypeType](./literals.md#hlsfragmentselectortypetype)
- [HLSPlaybackModeType](./literals.md#hlsplaybackmodetype)
- [ImageErrorType](./literals.md#imageerrortype)
- [ImageSelectorTypeType](./literals.md#imageselectortypetype)
- [ListFragmentsPaginatorName](./literals.md#listfragmentspaginatorname)
- [KinesisVideoArchivedMediaServiceName](./literals.md#kinesisvideoarchivedmediaservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_kinesis_video_archived_media.type_defs import ClipFragmentSelectorTypeDef

def get_value() -> ClipFragmentSelectorTypeDef:
    return {
        "FragmentSelectorType": ...,
        "TimestampRange": ...,
    }
```

- [ClipFragmentSelectorTypeDef](./type_defs.md#clipfragmentselectortypedef)
- [ClipTimestampRangeTypeDef](./type_defs.md#cliptimestamprangetypedef)
- [DASHFragmentSelectorTypeDef](./type_defs.md#dashfragmentselectortypedef)
- [DASHTimestampRangeTypeDef](./type_defs.md#dashtimestamprangetypedef)
- [FragmentSelectorTypeDef](./type_defs.md#fragmentselectortypedef)
- [FragmentTypeDef](./type_defs.md#fragmenttypedef)
- [GetClipInputRequestTypeDef](./type_defs.md#getclipinputrequesttypedef)
- [GetClipOutputTypeDef](./type_defs.md#getclipoutputtypedef)
- [GetDASHStreamingSessionURLInputRequestTypeDef](./type_defs.md#getdashstreamingsessionurlinputrequesttypedef)
- [GetDASHStreamingSessionURLOutputTypeDef](./type_defs.md#getdashstreamingsessionurloutputtypedef)
- [GetHLSStreamingSessionURLInputRequestTypeDef](./type_defs.md#gethlsstreamingsessionurlinputrequesttypedef)
- [GetHLSStreamingSessionURLOutputTypeDef](./type_defs.md#gethlsstreamingsessionurloutputtypedef)
- [GetImagesInputGetImagesPaginateTypeDef](./type_defs.md#getimagesinputgetimagespaginatetypedef)
- [GetImagesInputRequestTypeDef](./type_defs.md#getimagesinputrequesttypedef)
- [GetImagesOutputTypeDef](./type_defs.md#getimagesoutputtypedef)
- [GetMediaForFragmentListInputRequestTypeDef](./type_defs.md#getmediaforfragmentlistinputrequesttypedef)
- [GetMediaForFragmentListOutputTypeDef](./type_defs.md#getmediaforfragmentlistoutputtypedef)
- [HLSFragmentSelectorTypeDef](./type_defs.md#hlsfragmentselectortypedef)
- [HLSTimestampRangeTypeDef](./type_defs.md#hlstimestamprangetypedef)
- [ImageTypeDef](./type_defs.md#imagetypedef)
- [ListFragmentsInputListFragmentsPaginateTypeDef](./type_defs.md#listfragmentsinputlistfragmentspaginatetypedef)
- [ListFragmentsInputRequestTypeDef](./type_defs.md#listfragmentsinputrequesttypedef)
- [ListFragmentsOutputTypeDef](./type_defs.md#listfragmentsoutputtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TimestampRangeTypeDef](./type_defs.md#timestamprangetypedef)

