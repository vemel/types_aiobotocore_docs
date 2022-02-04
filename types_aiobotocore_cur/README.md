<a id="type-annotations-for-aiobotocore-costandusagereportservice-module"></a>

# Type annotations for aiobotocore CostandUsageReportService module

> [Index](..) > CostandUsageReportService

Auto-generated documentation for
[CostandUsageReportService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService)
type annotations stubs module
[types-aiobotocore-cur](https://pypi.org/project/types-aiobotocore-cur/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[cur]'

# install as a standalone
pip install types-aiobotocore-cur
```

- [Type annotations for aiobotocore CostandUsageReportService module](#type-annotations-for-aiobotocore-costandusagereportservice-module)
  - [CostandUsageReportServiceClient](#costandusagereportserviceclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="costandusagereportserviceclient"></a>

## CostandUsageReportServiceClient

Type annotations for `aiobotocore.create_client("cur")` as
[CostandUsageReportServiceClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_cur.client import CostandUsageReportServiceClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [delete_report_definition](./client.md#delete_report_definition)
- [describe_report_definitions](./client.md#describe_report_definitions)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [modify_report_definition](./client.md#modify_report_definition)
- [put_report_definition](./client.md#put_report_definition)

<a id="exceptions"></a>

### Exceptions

CostandUsageReportServiceClient [exceptions](./client.md#exceptions)

- ClientError
- DuplicateReportNameException
- InternalErrorException
- ReportLimitReachedException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("cur").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_cur.paginators import DescribeReportDefinitionsPaginator, ...
```

- [DescribeReportDefinitionsPaginator](./paginators.md#describereportdefinitionspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_cur.literals import AWSRegionType, ...
```

- [AWSRegionType](./literals.md#awsregiontype)
- [AdditionalArtifactType](./literals.md#additionalartifacttype)
- [CompressionFormatType](./literals.md#compressionformattype)
- [DescribeReportDefinitionsPaginatorName](./literals.md#describereportdefinitionspaginatorname)
- [ReportFormatType](./literals.md#reportformattype)
- [ReportVersioningType](./literals.md#reportversioningtype)
- [SchemaElementType](./literals.md#schemaelementtype)
- [TimeUnitType](./literals.md#timeunittype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_cur.type_defs import DeleteReportDefinitionRequestRequestTypeDef, ...
```

- [DeleteReportDefinitionRequestRequestTypeDef](./type_defs.md#deletereportdefinitionrequestrequesttypedef)
- [DeleteReportDefinitionResponseTypeDef](./type_defs.md#deletereportdefinitionresponsetypedef)
- [DescribeReportDefinitionsRequestRequestTypeDef](./type_defs.md#describereportdefinitionsrequestrequesttypedef)
- [DescribeReportDefinitionsResponseTypeDef](./type_defs.md#describereportdefinitionsresponsetypedef)
- [ModifyReportDefinitionRequestRequestTypeDef](./type_defs.md#modifyreportdefinitionrequestrequesttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PutReportDefinitionRequestRequestTypeDef](./type_defs.md#putreportdefinitionrequestrequesttypedef)
- [ReportDefinitionTypeDef](./type_defs.md#reportdefinitiontypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
