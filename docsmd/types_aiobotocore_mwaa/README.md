# MWAA module

> [Index](../README.md) > MWAA


!!! note ""

    Auto-generated documentation for [MWAA](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
    type annotations stubs module [types-aiobotocore-mwaa](https://pypi.org/project/types-aiobotocore-mwaa/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `MWAA`.

### From PyPI with pip

Install `types-aiobotocore` for `MWAA` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[mwaa]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[mwaa]'


# standalone installation
python -m pip install types-aiobotocore-mwaa
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-mwaa
```

## Usage

Code samples can be found in [Examples](./usage.md).

## MWAAClient

Type annotations and code completion for  `#!python session.create_client("mwaa")` as [MWAAClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_mwaa.client import MWAAClient


session = get_session()
async with session.create_client("mwaa") as client:
    client: MWAAClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("mwaa").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_mwaa.paginator import ListEnvironmentsPaginator

def get_list_environments_paginator() -> ListEnvironmentsPaginator:
    return client.get_paginator("list_environments"))
```

- [ListEnvironmentsPaginator](./paginators.md#listenvironmentspaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_mwaa.literals import EnvironmentStatusType

def get_value() -> EnvironmentStatusType:
    return "AVAILABLE"
```

- [EnvironmentStatusType](./literals.md#environmentstatustype)
- [ListEnvironmentsPaginatorName](./literals.md#listenvironmentspaginatorname)
- [LoggingLevelType](./literals.md#loggingleveltype)
- [UnitType](./literals.md#unittype)
- [UpdateStatusType](./literals.md#updatestatustype)
- [WebserverAccessModeType](./literals.md#webserveraccessmodetype)
- [MWAAServiceName](./literals.md#mwaaservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_mwaa.type_defs import CreateCliTokenRequestRequestTypeDef

def get_value() -> CreateCliTokenRequestRequestTypeDef:
    return {
        "Name": ...,
    }
```

- [CreateCliTokenRequestRequestTypeDef](./type_defs.md#createclitokenrequestrequesttypedef)
- [CreateCliTokenResponseTypeDef](./type_defs.md#createclitokenresponsetypedef)
- [CreateEnvironmentInputRequestTypeDef](./type_defs.md#createenvironmentinputrequesttypedef)
- [CreateEnvironmentOutputTypeDef](./type_defs.md#createenvironmentoutputtypedef)
- [CreateWebLoginTokenRequestRequestTypeDef](./type_defs.md#createweblogintokenrequestrequesttypedef)
- [CreateWebLoginTokenResponseTypeDef](./type_defs.md#createweblogintokenresponsetypedef)
- [DeleteEnvironmentInputRequestTypeDef](./type_defs.md#deleteenvironmentinputrequesttypedef)
- [DimensionTypeDef](./type_defs.md#dimensiontypedef)
- [EnvironmentTypeDef](./type_defs.md#environmenttypedef)
- [GetEnvironmentInputRequestTypeDef](./type_defs.md#getenvironmentinputrequesttypedef)
- [GetEnvironmentOutputTypeDef](./type_defs.md#getenvironmentoutputtypedef)
- [LastUpdateTypeDef](./type_defs.md#lastupdatetypedef)
- [ListEnvironmentsInputListEnvironmentsPaginateTypeDef](./type_defs.md#listenvironmentsinputlistenvironmentspaginatetypedef)
- [ListEnvironmentsInputRequestTypeDef](./type_defs.md#listenvironmentsinputrequesttypedef)
- [ListEnvironmentsOutputTypeDef](./type_defs.md#listenvironmentsoutputtypedef)
- [ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef)
- [ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef)
- [LoggingConfigurationInputTypeDef](./type_defs.md#loggingconfigurationinputtypedef)
- [LoggingConfigurationTypeDef](./type_defs.md#loggingconfigurationtypedef)
- [MetricDatumTypeDef](./type_defs.md#metricdatumtypedef)
- [ModuleLoggingConfigurationInputTypeDef](./type_defs.md#moduleloggingconfigurationinputtypedef)
- [ModuleLoggingConfigurationTypeDef](./type_defs.md#moduleloggingconfigurationtypedef)
- [NetworkConfigurationTypeDef](./type_defs.md#networkconfigurationtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PublishMetricsInputRequestTypeDef](./type_defs.md#publishmetricsinputrequesttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StatisticSetTypeDef](./type_defs.md#statisticsettypedef)
- [TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef)
- [UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef)
- [UpdateEnvironmentInputRequestTypeDef](./type_defs.md#updateenvironmentinputrequesttypedef)
- [UpdateEnvironmentOutputTypeDef](./type_defs.md#updateenvironmentoutputtypedef)
- [UpdateErrorTypeDef](./type_defs.md#updateerrortypedef)
- [UpdateNetworkConfigurationInputTypeDef](./type_defs.md#updatenetworkconfigurationinputtypedef)

