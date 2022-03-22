<a id="type-annotations-for-aiobotocore-marketplacemetering-module"></a>

# Type annotations for aiobotocore MarketplaceMetering module

> [Index](../README.md) > MarketplaceMetering

Auto-generated documentation for
[MarketplaceMetering](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering)
type annotations stubs module
[types-aiobotocore-meteringmarketplace](https://pypi.org/project/types-aiobotocore-meteringmarketplace/).

- [Type annotations for aiobotocore MarketplaceMetering module](#type-annotations-for-aiobotocore-marketplacemetering-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [MarketplaceMeteringClient](#marketplacemeteringclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `MarketplaceMetering`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `MarketplaceMetering` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[meteringmarketplace]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[meteringmarketplace]'


# standalone installation
python -m pip install types-aiobotocore-meteringmarketplace
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-meteringmarketplace
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="marketplacemeteringclient"></a>

## MarketplaceMeteringClient

Type annotations for `session.create_client("meteringmarketplace")` as
[MarketplaceMeteringClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_meteringmarketplace.client import MarketplaceMeteringClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [batch_meter_usage](./client.md#batch_meter_usage)
- [can_paginate](./client.md#can_paginate)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [meter_usage](./client.md#meter_usage)
- [register_usage](./client.md#register_usage)
- [resolve_customer](./client.md#resolve_customer)

<a id="exceptions"></a>

### Exceptions

MarketplaceMeteringClient [exceptions](./client.md#exceptions)

- ClientError
- CustomerNotEntitledException
- DisabledApiException
- DuplicateRequestException
- ExpiredTokenException
- InternalServiceErrorException
- InvalidCustomerIdentifierException
- InvalidEndpointRegionException
- InvalidProductCodeException
- InvalidPublicKeyVersionException
- InvalidRegionException
- InvalidTagException
- InvalidTokenException
- InvalidUsageAllocationsException
- InvalidUsageDimensionException
- PlatformNotSupportedException
- ThrottlingException
- TimestampOutOfBoundsException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_meteringmarketplace.literals import UsageRecordResultStatusType, ...
```

- [UsageRecordResultStatusType](./literals.md#usagerecordresultstatustype)
- [MarketplaceMeteringServiceName](./literals.md#marketplacemeteringservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_meteringmarketplace.type_defs import BatchMeterUsageRequestRequestTypeDef, ...
```

- [BatchMeterUsageRequestRequestTypeDef](./type_defs.md#batchmeterusagerequestrequesttypedef)
- [BatchMeterUsageResultTypeDef](./type_defs.md#batchmeterusageresulttypedef)
- [MeterUsageRequestRequestTypeDef](./type_defs.md#meterusagerequestrequesttypedef)
- [MeterUsageResultTypeDef](./type_defs.md#meterusageresulttypedef)
- [RegisterUsageRequestRequestTypeDef](./type_defs.md#registerusagerequestrequesttypedef)
- [RegisterUsageResultTypeDef](./type_defs.md#registerusageresulttypedef)
- [ResolveCustomerRequestRequestTypeDef](./type_defs.md#resolvecustomerrequestrequesttypedef)
- [ResolveCustomerResultTypeDef](./type_defs.md#resolvecustomerresulttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [UsageAllocationTypeDef](./type_defs.md#usageallocationtypedef)
- [UsageRecordResultTypeDef](./type_defs.md#usagerecordresulttypedef)
- [UsageRecordTypeDef](./type_defs.md#usagerecordtypedef)
