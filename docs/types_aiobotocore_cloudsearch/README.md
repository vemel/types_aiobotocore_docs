<a id="type-annotations-for-aiobotocore-cloudsearch-module"></a>

# Type annotations for aiobotocore CloudSearch module

> [Index](../README.md) > CloudSearch

Auto-generated documentation for
[CloudSearch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
type annotations stubs module
[types-aiobotocore-cloudsearch](https://pypi.org/project/types-aiobotocore-cloudsearch/).

- [Type annotations for aiobotocore CloudSearch module](#type-annotations-for-aiobotocore-cloudsearch-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [Usage](#usage)
  - [CloudSearchClient](#cloudsearchclient)
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

Click `Modify` and select `boto3 common` and `CloudSearch`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `CloudSearch` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[cloudsearch]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[cloudsearch]'


# standalone installation
python -m pip install types-aiobotocore-cloudsearch
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-cloudsearch
```

<a id="usage"></a>

## Usage

Code samples can be found [here](./usage.md).

<a id="cloudsearchclient"></a>

## CloudSearchClient

Type annotations for `session.create_client("cloudsearch")` as
[CloudSearchClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_cloudsearch.client import CloudSearchClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [build_suggesters](./client.md#build_suggesters)
- [can_paginate](./client.md#can_paginate)
- [create_domain](./client.md#create_domain)
- [define_analysis_scheme](./client.md#define_analysis_scheme)
- [define_expression](./client.md#define_expression)
- [define_index_field](./client.md#define_index_field)
- [define_suggester](./client.md#define_suggester)
- [delete_analysis_scheme](./client.md#delete_analysis_scheme)
- [delete_domain](./client.md#delete_domain)
- [delete_expression](./client.md#delete_expression)
- [delete_index_field](./client.md#delete_index_field)
- [delete_suggester](./client.md#delete_suggester)
- [describe_analysis_schemes](./client.md#describe_analysis_schemes)
- [describe_availability_options](./client.md#describe_availability_options)
- [describe_domain_endpoint_options](./client.md#describe_domain_endpoint_options)
- [describe_domains](./client.md#describe_domains)
- [describe_expressions](./client.md#describe_expressions)
- [describe_index_fields](./client.md#describe_index_fields)
- [describe_scaling_parameters](./client.md#describe_scaling_parameters)
- [describe_service_access_policies](./client.md#describe_service_access_policies)
- [describe_suggesters](./client.md#describe_suggesters)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [index_documents](./client.md#index_documents)
- [list_domain_names](./client.md#list_domain_names)
- [update_availability_options](./client.md#update_availability_options)
- [update_domain_endpoint_options](./client.md#update_domain_endpoint_options)
- [update_scaling_parameters](./client.md#update_scaling_parameters)
- [update_service_access_policies](./client.md#update_service_access_policies)

<a id="exceptions"></a>

### Exceptions

CloudSearchClient [exceptions](./client.md#exceptions)

- BaseException
- ClientError
- DisabledOperationException
- InternalException
- InvalidTypeException
- LimitExceededException
- ResourceAlreadyExistsException
- ResourceNotFoundException
- ValidationException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_cloudsearch.literals import AlgorithmicStemmingType, ...
```

- [AlgorithmicStemmingType](./literals.md#algorithmicstemmingtype)
- [AnalysisSchemeLanguageType](./literals.md#analysisschemelanguagetype)
- [IndexFieldTypeType](./literals.md#indexfieldtypetype)
- [OptionStateType](./literals.md#optionstatetype)
- [PartitionInstanceTypeType](./literals.md#partitioninstancetypetype)
- [SuggesterFuzzyMatchingType](./literals.md#suggesterfuzzymatchingtype)
- [TLSSecurityPolicyType](./literals.md#tlssecuritypolicytype)
- [CloudSearchServiceName](./literals.md#cloudsearchservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from types_aiobotocore_cloudsearch.type_defs import AccessPoliciesStatusTypeDef, ...
```

- [AccessPoliciesStatusTypeDef](./type_defs.md#accesspoliciesstatustypedef)
- [AnalysisOptionsTypeDef](./type_defs.md#analysisoptionstypedef)
- [AnalysisSchemeStatusTypeDef](./type_defs.md#analysisschemestatustypedef)
- [AnalysisSchemeTypeDef](./type_defs.md#analysisschemetypedef)
- [AvailabilityOptionsStatusTypeDef](./type_defs.md#availabilityoptionsstatustypedef)
- [BuildSuggestersRequestRequestTypeDef](./type_defs.md#buildsuggestersrequestrequesttypedef)
- [BuildSuggestersResponseTypeDef](./type_defs.md#buildsuggestersresponsetypedef)
- [CreateDomainRequestRequestTypeDef](./type_defs.md#createdomainrequestrequesttypedef)
- [CreateDomainResponseTypeDef](./type_defs.md#createdomainresponsetypedef)
- [DateArrayOptionsTypeDef](./type_defs.md#datearrayoptionstypedef)
- [DateOptionsTypeDef](./type_defs.md#dateoptionstypedef)
- [DefineAnalysisSchemeRequestRequestTypeDef](./type_defs.md#defineanalysisschemerequestrequesttypedef)
- [DefineAnalysisSchemeResponseTypeDef](./type_defs.md#defineanalysisschemeresponsetypedef)
- [DefineExpressionRequestRequestTypeDef](./type_defs.md#defineexpressionrequestrequesttypedef)
- [DefineExpressionResponseTypeDef](./type_defs.md#defineexpressionresponsetypedef)
- [DefineIndexFieldRequestRequestTypeDef](./type_defs.md#defineindexfieldrequestrequesttypedef)
- [DefineIndexFieldResponseTypeDef](./type_defs.md#defineindexfieldresponsetypedef)
- [DefineSuggesterRequestRequestTypeDef](./type_defs.md#definesuggesterrequestrequesttypedef)
- [DefineSuggesterResponseTypeDef](./type_defs.md#definesuggesterresponsetypedef)
- [DeleteAnalysisSchemeRequestRequestTypeDef](./type_defs.md#deleteanalysisschemerequestrequesttypedef)
- [DeleteAnalysisSchemeResponseTypeDef](./type_defs.md#deleteanalysisschemeresponsetypedef)
- [DeleteDomainRequestRequestTypeDef](./type_defs.md#deletedomainrequestrequesttypedef)
- [DeleteDomainResponseTypeDef](./type_defs.md#deletedomainresponsetypedef)
- [DeleteExpressionRequestRequestTypeDef](./type_defs.md#deleteexpressionrequestrequesttypedef)
- [DeleteExpressionResponseTypeDef](./type_defs.md#deleteexpressionresponsetypedef)
- [DeleteIndexFieldRequestRequestTypeDef](./type_defs.md#deleteindexfieldrequestrequesttypedef)
- [DeleteIndexFieldResponseTypeDef](./type_defs.md#deleteindexfieldresponsetypedef)
- [DeleteSuggesterRequestRequestTypeDef](./type_defs.md#deletesuggesterrequestrequesttypedef)
- [DeleteSuggesterResponseTypeDef](./type_defs.md#deletesuggesterresponsetypedef)
- [DescribeAnalysisSchemesRequestRequestTypeDef](./type_defs.md#describeanalysisschemesrequestrequesttypedef)
- [DescribeAnalysisSchemesResponseTypeDef](./type_defs.md#describeanalysisschemesresponsetypedef)
- [DescribeAvailabilityOptionsRequestRequestTypeDef](./type_defs.md#describeavailabilityoptionsrequestrequesttypedef)
- [DescribeAvailabilityOptionsResponseTypeDef](./type_defs.md#describeavailabilityoptionsresponsetypedef)
- [DescribeDomainEndpointOptionsRequestRequestTypeDef](./type_defs.md#describedomainendpointoptionsrequestrequesttypedef)
- [DescribeDomainEndpointOptionsResponseTypeDef](./type_defs.md#describedomainendpointoptionsresponsetypedef)
- [DescribeDomainsRequestRequestTypeDef](./type_defs.md#describedomainsrequestrequesttypedef)
- [DescribeDomainsResponseTypeDef](./type_defs.md#describedomainsresponsetypedef)
- [DescribeExpressionsRequestRequestTypeDef](./type_defs.md#describeexpressionsrequestrequesttypedef)
- [DescribeExpressionsResponseTypeDef](./type_defs.md#describeexpressionsresponsetypedef)
- [DescribeIndexFieldsRequestRequestTypeDef](./type_defs.md#describeindexfieldsrequestrequesttypedef)
- [DescribeIndexFieldsResponseTypeDef](./type_defs.md#describeindexfieldsresponsetypedef)
- [DescribeScalingParametersRequestRequestTypeDef](./type_defs.md#describescalingparametersrequestrequesttypedef)
- [DescribeScalingParametersResponseTypeDef](./type_defs.md#describescalingparametersresponsetypedef)
- [DescribeServiceAccessPoliciesRequestRequestTypeDef](./type_defs.md#describeserviceaccesspoliciesrequestrequesttypedef)
- [DescribeServiceAccessPoliciesResponseTypeDef](./type_defs.md#describeserviceaccesspoliciesresponsetypedef)
- [DescribeSuggestersRequestRequestTypeDef](./type_defs.md#describesuggestersrequestrequesttypedef)
- [DescribeSuggestersResponseTypeDef](./type_defs.md#describesuggestersresponsetypedef)
- [DocumentSuggesterOptionsTypeDef](./type_defs.md#documentsuggesteroptionstypedef)
- [DomainEndpointOptionsStatusTypeDef](./type_defs.md#domainendpointoptionsstatustypedef)
- [DomainEndpointOptionsTypeDef](./type_defs.md#domainendpointoptionstypedef)
- [DomainStatusTypeDef](./type_defs.md#domainstatustypedef)
- [DoubleArrayOptionsTypeDef](./type_defs.md#doublearrayoptionstypedef)
- [DoubleOptionsTypeDef](./type_defs.md#doubleoptionstypedef)
- [ExpressionStatusTypeDef](./type_defs.md#expressionstatustypedef)
- [ExpressionTypeDef](./type_defs.md#expressiontypedef)
- [IndexDocumentsRequestRequestTypeDef](./type_defs.md#indexdocumentsrequestrequesttypedef)
- [IndexDocumentsResponseTypeDef](./type_defs.md#indexdocumentsresponsetypedef)
- [IndexFieldStatusTypeDef](./type_defs.md#indexfieldstatustypedef)
- [IndexFieldTypeDef](./type_defs.md#indexfieldtypedef)
- [IntArrayOptionsTypeDef](./type_defs.md#intarrayoptionstypedef)
- [IntOptionsTypeDef](./type_defs.md#intoptionstypedef)
- [LatLonOptionsTypeDef](./type_defs.md#latlonoptionstypedef)
- [LimitsTypeDef](./type_defs.md#limitstypedef)
- [ListDomainNamesResponseTypeDef](./type_defs.md#listdomainnamesresponsetypedef)
- [LiteralArrayOptionsTypeDef](./type_defs.md#literalarrayoptionstypedef)
- [LiteralOptionsTypeDef](./type_defs.md#literaloptionstypedef)
- [OptionStatusTypeDef](./type_defs.md#optionstatustypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ScalingParametersStatusTypeDef](./type_defs.md#scalingparametersstatustypedef)
- [ScalingParametersTypeDef](./type_defs.md#scalingparameterstypedef)
- [ServiceEndpointTypeDef](./type_defs.md#serviceendpointtypedef)
- [SuggesterStatusTypeDef](./type_defs.md#suggesterstatustypedef)
- [SuggesterTypeDef](./type_defs.md#suggestertypedef)
- [TextArrayOptionsTypeDef](./type_defs.md#textarrayoptionstypedef)
- [TextOptionsTypeDef](./type_defs.md#textoptionstypedef)
- [UpdateAvailabilityOptionsRequestRequestTypeDef](./type_defs.md#updateavailabilityoptionsrequestrequesttypedef)
- [UpdateAvailabilityOptionsResponseTypeDef](./type_defs.md#updateavailabilityoptionsresponsetypedef)
- [UpdateDomainEndpointOptionsRequestRequestTypeDef](./type_defs.md#updatedomainendpointoptionsrequestrequesttypedef)
- [UpdateDomainEndpointOptionsResponseTypeDef](./type_defs.md#updatedomainendpointoptionsresponsetypedef)
- [UpdateScalingParametersRequestRequestTypeDef](./type_defs.md#updatescalingparametersrequestrequesttypedef)
- [UpdateScalingParametersResponseTypeDef](./type_defs.md#updatescalingparametersresponsetypedef)
- [UpdateServiceAccessPoliciesRequestRequestTypeDef](./type_defs.md#updateserviceaccesspoliciesrequestrequesttypedef)
- [UpdateServiceAccessPoliciesResponseTypeDef](./type_defs.md#updateserviceaccesspoliciesresponsetypedef)
