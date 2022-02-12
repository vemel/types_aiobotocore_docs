<a id="type-annotations-for-aiobotocore-textract-module"></a>

# Type annotations for aiobotocore Textract module

> [Index](..) > Textract

Auto-generated documentation for
[Textract](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract)
type annotations stubs module
[types-aiobotocore-textract](https://pypi.org/project/types-aiobotocore-textract/).

- [Type annotations for aiobotocore Textract module](#type-annotations-for-aiobotocore-textract-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [TextractClient](#textractclient)
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

Click `Modify` and select `boto3 common` and `Textract`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `Textract` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[textract]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[textract]'

# standalone installation
python -m pip install types-aiobotocore-textract
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-textract
```

<a id="textractclient"></a>

## TextractClient

Type annotations for `session.create_client("textract")` as
[TextractClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_textract.client import TextractClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [analyze_document](./client.md#analyze_document)
- [analyze_expense](./client.md#analyze_expense)
- [analyze_id](./client.md#analyze_id)
- [can_paginate](./client.md#can_paginate)
- [detect_document_text](./client.md#detect_document_text)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_document_analysis](./client.md#get_document_analysis)
- [get_document_text_detection](./client.md#get_document_text_detection)
- [get_expense_analysis](./client.md#get_expense_analysis)
- [start_document_analysis](./client.md#start_document_analysis)
- [start_document_text_detection](./client.md#start_document_text_detection)
- [start_expense_analysis](./client.md#start_expense_analysis)

<a id="exceptions"></a>

### Exceptions

TextractClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- BadDocumentException
- ClientError
- DocumentTooLargeException
- HumanLoopQuotaExceededException
- IdempotentParameterMismatchException
- InternalServerError
- InvalidJobIdException
- InvalidKMSKeyException
- InvalidParameterException
- InvalidS3ObjectException
- LimitExceededException
- ProvisionedThroughputExceededException
- ThrottlingException
- UnsupportedDocumentException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_textract.literals import BlockTypeType, ...
```

- [BlockTypeType](./literals.md#blocktypetype)
- [ContentClassifierType](./literals.md#contentclassifiertype)
- [EntityTypeType](./literals.md#entitytypetype)
- [FeatureTypeType](./literals.md#featuretypetype)
- [JobStatusType](./literals.md#jobstatustype)
- [RelationshipTypeType](./literals.md#relationshiptypetype)
- [SelectionStatusType](./literals.md#selectionstatustype)
- [TextTypeType](./literals.md#texttypetype)
- [ValueTypeType](./literals.md#valuetypetype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_textract.type_defs import AnalyzeDocumentRequestRequestTypeDef, ...
```

- [AnalyzeDocumentRequestRequestTypeDef](./type_defs.md#analyzedocumentrequestrequesttypedef)
- [AnalyzeDocumentResponseTypeDef](./type_defs.md#analyzedocumentresponsetypedef)
- [AnalyzeExpenseRequestRequestTypeDef](./type_defs.md#analyzeexpenserequestrequesttypedef)
- [AnalyzeExpenseResponseTypeDef](./type_defs.md#analyzeexpenseresponsetypedef)
- [AnalyzeIDDetectionsTypeDef](./type_defs.md#analyzeiddetectionstypedef)
- [AnalyzeIDRequestRequestTypeDef](./type_defs.md#analyzeidrequestrequesttypedef)
- [AnalyzeIDResponseTypeDef](./type_defs.md#analyzeidresponsetypedef)
- [BlockTypeDef](./type_defs.md#blocktypedef)
- [BoundingBoxTypeDef](./type_defs.md#boundingboxtypedef)
- [DetectDocumentTextRequestRequestTypeDef](./type_defs.md#detectdocumenttextrequestrequesttypedef)
- [DetectDocumentTextResponseTypeDef](./type_defs.md#detectdocumenttextresponsetypedef)
- [DocumentLocationTypeDef](./type_defs.md#documentlocationtypedef)
- [DocumentMetadataTypeDef](./type_defs.md#documentmetadatatypedef)
- [DocumentTypeDef](./type_defs.md#documenttypedef)
- [ExpenseDetectionTypeDef](./type_defs.md#expensedetectiontypedef)
- [ExpenseDocumentTypeDef](./type_defs.md#expensedocumenttypedef)
- [ExpenseFieldTypeDef](./type_defs.md#expensefieldtypedef)
- [ExpenseTypeTypeDef](./type_defs.md#expensetypetypedef)
- [GeometryTypeDef](./type_defs.md#geometrytypedef)
- [GetDocumentAnalysisRequestRequestTypeDef](./type_defs.md#getdocumentanalysisrequestrequesttypedef)
- [GetDocumentAnalysisResponseTypeDef](./type_defs.md#getdocumentanalysisresponsetypedef)
- [GetDocumentTextDetectionRequestRequestTypeDef](./type_defs.md#getdocumenttextdetectionrequestrequesttypedef)
- [GetDocumentTextDetectionResponseTypeDef](./type_defs.md#getdocumenttextdetectionresponsetypedef)
- [GetExpenseAnalysisRequestRequestTypeDef](./type_defs.md#getexpenseanalysisrequestrequesttypedef)
- [GetExpenseAnalysisResponseTypeDef](./type_defs.md#getexpenseanalysisresponsetypedef)
- [HumanLoopActivationOutputTypeDef](./type_defs.md#humanloopactivationoutputtypedef)
- [HumanLoopConfigTypeDef](./type_defs.md#humanloopconfigtypedef)
- [HumanLoopDataAttributesTypeDef](./type_defs.md#humanloopdataattributestypedef)
- [IdentityDocumentFieldTypeDef](./type_defs.md#identitydocumentfieldtypedef)
- [IdentityDocumentTypeDef](./type_defs.md#identitydocumenttypedef)
- [LineItemFieldsTypeDef](./type_defs.md#lineitemfieldstypedef)
- [LineItemGroupTypeDef](./type_defs.md#lineitemgrouptypedef)
- [NormalizedValueTypeDef](./type_defs.md#normalizedvaluetypedef)
- [NotificationChannelTypeDef](./type_defs.md#notificationchanneltypedef)
- [OutputConfigTypeDef](./type_defs.md#outputconfigtypedef)
- [PointTypeDef](./type_defs.md#pointtypedef)
- [RelationshipTypeDef](./type_defs.md#relationshiptypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [S3ObjectTypeDef](./type_defs.md#s3objecttypedef)
- [StartDocumentAnalysisRequestRequestTypeDef](./type_defs.md#startdocumentanalysisrequestrequesttypedef)
- [StartDocumentAnalysisResponseTypeDef](./type_defs.md#startdocumentanalysisresponsetypedef)
- [StartDocumentTextDetectionRequestRequestTypeDef](./type_defs.md#startdocumenttextdetectionrequestrequesttypedef)
- [StartDocumentTextDetectionResponseTypeDef](./type_defs.md#startdocumenttextdetectionresponsetypedef)
- [StartExpenseAnalysisRequestRequestTypeDef](./type_defs.md#startexpenseanalysisrequestrequesttypedef)
- [StartExpenseAnalysisResponseTypeDef](./type_defs.md#startexpenseanalysisresponsetypedef)
- [WarningTypeDef](./type_defs.md#warningtypedef)
