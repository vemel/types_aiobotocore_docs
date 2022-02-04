<a id="cloudsearchclient-for-aiobotocore-cloudsearch-module"></a>

# CloudSearchClient for aiobotocore CloudSearch module

> [Index](..) > [CloudSearch](.) > CloudSearchClient

Auto-generated documentation for
[CloudSearch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
type annotations stubs module
[types-aiobotocore-cloudsearch](https://pypi.org/project/types-aiobotocore-cloudsearch/).

- [CloudSearchClient for aiobotocore CloudSearch module](#cloudsearchclient-for-aiobotocore-cloudsearch-module)
  - [CloudSearchClient](#cloudsearchclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [build_suggesters](#build_suggesters)
    - [can_paginate](#can_paginate)
    - [create_domain](#create_domain)
    - [define_analysis_scheme](#define_analysis_scheme)
    - [define_expression](#define_expression)
    - [define_index_field](#define_index_field)
    - [define_suggester](#define_suggester)
    - [delete_analysis_scheme](#delete_analysis_scheme)
    - [delete_domain](#delete_domain)
    - [delete_expression](#delete_expression)
    - [delete_index_field](#delete_index_field)
    - [delete_suggester](#delete_suggester)
    - [describe_analysis_schemes](#describe_analysis_schemes)
    - [describe_availability_options](#describe_availability_options)
    - [describe_domain_endpoint_options](#describe_domain_endpoint_options)
    - [describe_domains](#describe_domains)
    - [describe_expressions](#describe_expressions)
    - [describe_index_fields](#describe_index_fields)
    - [describe_scaling_parameters](#describe_scaling_parameters)
    - [describe_service_access_policies](#describe_service_access_policies)
    - [describe_suggesters](#describe_suggesters)
    - [generate_presigned_url](#generate_presigned_url)
    - [index_documents](#index_documents)
    - [list_domain_names](#list_domain_names)
    - [update_availability_options](#update_availability_options)
    - [update_domain_endpoint_options](#update_domain_endpoint_options)
    - [update_scaling_parameters](#update_scaling_parameters)
    - [update_service_access_policies](#update_service_access_policies)

<a id="cloudsearchclient"></a>

## CloudSearchClient

Type annotations for `aiobotocore.create_client("cloudsearch")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_cloudsearch.client import CloudSearchClient

def get_cloudsearch_client() -> CloudSearchClient:
    return Session().client("cloudsearch")
```

Boto3 documentation:
[CloudSearch.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_cloudsearch.client import Exceptions

def handle_error(exc: Exceptions.BaseException) -> None:
    ...
```

Exceptions:

- `Exceptions.BaseException`
- `Exceptions.ClientError`
- `Exceptions.DisabledOperationException`
- `Exceptions.InternalException`
- `Exceptions.InvalidTypeException`
- `Exceptions.LimitExceededException`
- `Exceptions.ResourceAlreadyExistsException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

CloudSearchClient exceptions.

Type annotations for `aiobotocore.create_client("cloudsearch").exceptions`
method.

Boto3 documentation:
[CloudSearch.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="build_suggesters"></a>

### build_suggesters

Indexes the search suggestions.

Type annotations for
`aiobotocore.create_client("cloudsearch").build_suggesters` method.

Boto3 documentation:
[CloudSearch.Client.build_suggesters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.build_suggesters)

Asynchronous method. Use `await build_suggesters(...)` for a synchronous call.

Arguments mapping described in
[BuildSuggestersRequestRequestTypeDef](./type_defs.md#buildsuggestersrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*

Returns a `Coroutine` for
[BuildSuggestersResponseTypeDef](./type_defs.md#buildsuggestersresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("cloudsearch").can_paginate`
method.

Boto3 documentation:
[CloudSearch.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_domain"></a>

### create_domain

Creates a new search domain.

Type annotations for `aiobotocore.create_client("cloudsearch").create_domain`
method.

Boto3 documentation:
[CloudSearch.Client.create_domain](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.create_domain)

Asynchronous method. Use `await create_domain(...)` for a synchronous call.

Arguments mapping described in
[CreateDomainRequestRequestTypeDef](./type_defs.md#createdomainrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*

Returns a `Coroutine` for
[CreateDomainResponseTypeDef](./type_defs.md#createdomainresponsetypedef).

<a id="define_analysis_scheme"></a>

### define_analysis_scheme

Configures an analysis scheme that can be applied to a `text` or `text-array`
field to define language-specific text processing options.

Type annotations for
`aiobotocore.create_client("cloudsearch").define_analysis_scheme` method.

Boto3 documentation:
[CloudSearch.Client.define_analysis_scheme](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.define_analysis_scheme)

Asynchronous method. Use `await define_analysis_scheme(...)` for a synchronous
call.

Arguments mapping described in
[DefineAnalysisSchemeRequestRequestTypeDef](./type_defs.md#defineanalysisschemerequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `AnalysisScheme`:
  [AnalysisSchemeTypeDef](./type_defs.md#analysisschemetypedef) *(required)*

Returns a `Coroutine` for
[DefineAnalysisSchemeResponseTypeDef](./type_defs.md#defineanalysisschemeresponsetypedef).

<a id="define_expression"></a>

### define_expression

Configures an ` Expression` for the search domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").define_expression` method.

Boto3 documentation:
[CloudSearch.Client.define_expression](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.define_expression)

Asynchronous method. Use `await define_expression(...)` for a synchronous call.

Arguments mapping described in
[DefineExpressionRequestRequestTypeDef](./type_defs.md#defineexpressionrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `Expression`: [ExpressionTypeDef](./type_defs.md#expressiontypedef)
  *(required)*

Returns a `Coroutine` for
[DefineExpressionResponseTypeDef](./type_defs.md#defineexpressionresponsetypedef).

<a id="define_index_field"></a>

### define_index_field

Configures an ` IndexField` for the search domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").define_index_field` method.

Boto3 documentation:
[CloudSearch.Client.define_index_field](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.define_index_field)

Asynchronous method. Use `await define_index_field(...)` for a synchronous
call.

Arguments mapping described in
[DefineIndexFieldRequestRequestTypeDef](./type_defs.md#defineindexfieldrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `IndexField`: [IndexFieldTypeDef](./type_defs.md#indexfieldtypedef)
  *(required)*

Returns a `Coroutine` for
[DefineIndexFieldResponseTypeDef](./type_defs.md#defineindexfieldresponsetypedef).

<a id="define_suggester"></a>

### define_suggester

Configures a suggester for a domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").define_suggester` method.

Boto3 documentation:
[CloudSearch.Client.define_suggester](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.define_suggester)

Asynchronous method. Use `await define_suggester(...)` for a synchronous call.

Arguments mapping described in
[DefineSuggesterRequestRequestTypeDef](./type_defs.md#definesuggesterrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `Suggester`: [SuggesterTypeDef](./type_defs.md#suggestertypedef) *(required)*

Returns a `Coroutine` for
[DefineSuggesterResponseTypeDef](./type_defs.md#definesuggesterresponsetypedef).

<a id="delete_analysis_scheme"></a>

### delete_analysis_scheme

Deletes an analysis scheme.

Type annotations for
`aiobotocore.create_client("cloudsearch").delete_analysis_scheme` method.

Boto3 documentation:
[CloudSearch.Client.delete_analysis_scheme](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.delete_analysis_scheme)

Asynchronous method. Use `await delete_analysis_scheme(...)` for a synchronous
call.

Arguments mapping described in
[DeleteAnalysisSchemeRequestRequestTypeDef](./type_defs.md#deleteanalysisschemerequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `AnalysisSchemeName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteAnalysisSchemeResponseTypeDef](./type_defs.md#deleteanalysisschemeresponsetypedef).

<a id="delete_domain"></a>

### delete_domain

Permanently deletes a search domain and all of its data.

Type annotations for `aiobotocore.create_client("cloudsearch").delete_domain`
method.

Boto3 documentation:
[CloudSearch.Client.delete_domain](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.delete_domain)

Asynchronous method. Use `await delete_domain(...)` for a synchronous call.

Arguments mapping described in
[DeleteDomainRequestRequestTypeDef](./type_defs.md#deletedomainrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteDomainResponseTypeDef](./type_defs.md#deletedomainresponsetypedef).

<a id="delete_expression"></a>

### delete_expression

Removes an ` Expression` from the search domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").delete_expression` method.

Boto3 documentation:
[CloudSearch.Client.delete_expression](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.delete_expression)

Asynchronous method. Use `await delete_expression(...)` for a synchronous call.

Arguments mapping described in
[DeleteExpressionRequestRequestTypeDef](./type_defs.md#deleteexpressionrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `ExpressionName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteExpressionResponseTypeDef](./type_defs.md#deleteexpressionresponsetypedef).

<a id="delete_index_field"></a>

### delete_index_field

Removes an ` IndexField` from the search domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").delete_index_field` method.

Boto3 documentation:
[CloudSearch.Client.delete_index_field](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.delete_index_field)

Asynchronous method. Use `await delete_index_field(...)` for a synchronous
call.

Arguments mapping described in
[DeleteIndexFieldRequestRequestTypeDef](./type_defs.md#deleteindexfieldrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `IndexFieldName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteIndexFieldResponseTypeDef](./type_defs.md#deleteindexfieldresponsetypedef).

<a id="delete_suggester"></a>

### delete_suggester

Deletes a suggester.

Type annotations for
`aiobotocore.create_client("cloudsearch").delete_suggester` method.

Boto3 documentation:
[CloudSearch.Client.delete_suggester](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.delete_suggester)

Asynchronous method. Use `await delete_suggester(...)` for a synchronous call.

Arguments mapping described in
[DeleteSuggesterRequestRequestTypeDef](./type_defs.md#deletesuggesterrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `SuggesterName`: `str` *(required)*

Returns a `Coroutine` for
[DeleteSuggesterResponseTypeDef](./type_defs.md#deletesuggesterresponsetypedef).

<a id="describe_analysis_schemes"></a>

### describe_analysis_schemes

Gets the analysis schemes configured for a domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_analysis_schemes` method.

Boto3 documentation:
[CloudSearch.Client.describe_analysis_schemes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_analysis_schemes)

Asynchronous method. Use `await describe_analysis_schemes(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAnalysisSchemesRequestRequestTypeDef](./type_defs.md#describeanalysisschemesrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `AnalysisSchemeNames`: `Sequence`\[`str`\]
- `Deployed`: `bool`

Returns a `Coroutine` for
[DescribeAnalysisSchemesResponseTypeDef](./type_defs.md#describeanalysisschemesresponsetypedef).

<a id="describe_availability_options"></a>

### describe_availability_options

Gets the availability options configured for a domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_availability_options`
method.

Boto3 documentation:
[CloudSearch.Client.describe_availability_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_availability_options)

Asynchronous method. Use `await describe_availability_options(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAvailabilityOptionsRequestRequestTypeDef](./type_defs.md#describeavailabilityoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `Deployed`: `bool`

Returns a `Coroutine` for
[DescribeAvailabilityOptionsResponseTypeDef](./type_defs.md#describeavailabilityoptionsresponsetypedef).

<a id="describe_domain_endpoint_options"></a>

### describe_domain_endpoint_options

Returns the domain's endpoint options, specifically whether all requests to the
domain must arrive over HTTPS.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_domain_endpoint_options`
method.

Boto3 documentation:
[CloudSearch.Client.describe_domain_endpoint_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_domain_endpoint_options)

Asynchronous method. Use `await describe_domain_endpoint_options(...)` for a
synchronous call.

Arguments mapping described in
[DescribeDomainEndpointOptionsRequestRequestTypeDef](./type_defs.md#describedomainendpointoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `Deployed`: `bool`

Returns a `Coroutine` for
[DescribeDomainEndpointOptionsResponseTypeDef](./type_defs.md#describedomainendpointoptionsresponsetypedef).

<a id="describe_domains"></a>

### describe_domains

Gets information about the search domains owned by this account.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_domains` method.

Boto3 documentation:
[CloudSearch.Client.describe_domains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_domains)

Asynchronous method. Use `await describe_domains(...)` for a synchronous call.

Arguments mapping described in
[DescribeDomainsRequestRequestTypeDef](./type_defs.md#describedomainsrequestrequesttypedef).

Keyword-only arguments:

- `DomainNames`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeDomainsResponseTypeDef](./type_defs.md#describedomainsresponsetypedef).

<a id="describe_expressions"></a>

### describe_expressions

Gets the expressions configured for the search domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_expressions` method.

Boto3 documentation:
[CloudSearch.Client.describe_expressions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_expressions)

Asynchronous method. Use `await describe_expressions(...)` for a synchronous
call.

Arguments mapping described in
[DescribeExpressionsRequestRequestTypeDef](./type_defs.md#describeexpressionsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `ExpressionNames`: `Sequence`\[`str`\]
- `Deployed`: `bool`

Returns a `Coroutine` for
[DescribeExpressionsResponseTypeDef](./type_defs.md#describeexpressionsresponsetypedef).

<a id="describe_index_fields"></a>

### describe_index_fields

Gets information about the index fields configured for the search domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_index_fields` method.

Boto3 documentation:
[CloudSearch.Client.describe_index_fields](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_index_fields)

Asynchronous method. Use `await describe_index_fields(...)` for a synchronous
call.

Arguments mapping described in
[DescribeIndexFieldsRequestRequestTypeDef](./type_defs.md#describeindexfieldsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `FieldNames`: `Sequence`\[`str`\]
- `Deployed`: `bool`

Returns a `Coroutine` for
[DescribeIndexFieldsResponseTypeDef](./type_defs.md#describeindexfieldsresponsetypedef).

<a id="describe_scaling_parameters"></a>

### describe_scaling_parameters

Gets the scaling parameters configured for a domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_scaling_parameters` method.

Boto3 documentation:
[CloudSearch.Client.describe_scaling_parameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_scaling_parameters)

Asynchronous method. Use `await describe_scaling_parameters(...)` for a
synchronous call.

Arguments mapping described in
[DescribeScalingParametersRequestRequestTypeDef](./type_defs.md#describescalingparametersrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeScalingParametersResponseTypeDef](./type_defs.md#describescalingparametersresponsetypedef).

<a id="describe_service_access_policies"></a>

### describe_service_access_policies

Gets information about the access policies that control access to the domain's
document and search endpoints.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_service_access_policies`
method.

Boto3 documentation:
[CloudSearch.Client.describe_service_access_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_service_access_policies)

Asynchronous method. Use `await describe_service_access_policies(...)` for a
synchronous call.

Arguments mapping described in
[DescribeServiceAccessPoliciesRequestRequestTypeDef](./type_defs.md#describeserviceaccesspoliciesrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `Deployed`: `bool`

Returns a `Coroutine` for
[DescribeServiceAccessPoliciesResponseTypeDef](./type_defs.md#describeserviceaccesspoliciesresponsetypedef).

<a id="describe_suggesters"></a>

### describe_suggesters

Gets the suggesters configured for a domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").describe_suggesters` method.

Boto3 documentation:
[CloudSearch.Client.describe_suggesters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.describe_suggesters)

Asynchronous method. Use `await describe_suggesters(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSuggestersRequestRequestTypeDef](./type_defs.md#describesuggestersrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `SuggesterNames`: `Sequence`\[`str`\]
- `Deployed`: `bool`

Returns a `Coroutine` for
[DescribeSuggestersResponseTypeDef](./type_defs.md#describesuggestersresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("cloudsearch").generate_presigned_url` method.

Boto3 documentation:
[CloudSearch.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="index_documents"></a>

### index_documents

Tells the search domain to start indexing its documents using the latest
indexing options.

Type annotations for `aiobotocore.create_client("cloudsearch").index_documents`
method.

Boto3 documentation:
[CloudSearch.Client.index_documents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.index_documents)

Asynchronous method. Use `await index_documents(...)` for a synchronous call.

Arguments mapping described in
[IndexDocumentsRequestRequestTypeDef](./type_defs.md#indexdocumentsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*

Returns a `Coroutine` for
[IndexDocumentsResponseTypeDef](./type_defs.md#indexdocumentsresponsetypedef).

<a id="list_domain_names"></a>

### list_domain_names

Lists all search domains owned by an account.

Type annotations for
`aiobotocore.create_client("cloudsearch").list_domain_names` method.

Boto3 documentation:
[CloudSearch.Client.list_domain_names](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.list_domain_names)

Asynchronous method. Use `await list_domain_names(...)` for a synchronous call.

Returns a `Coroutine` for
[ListDomainNamesResponseTypeDef](./type_defs.md#listdomainnamesresponsetypedef).

<a id="update_availability_options"></a>

### update_availability_options

Configures the availability options for a domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").update_availability_options` method.

Boto3 documentation:
[CloudSearch.Client.update_availability_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.update_availability_options)

Asynchronous method. Use `await update_availability_options(...)` for a
synchronous call.

Arguments mapping described in
[UpdateAvailabilityOptionsRequestRequestTypeDef](./type_defs.md#updateavailabilityoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `MultiAZ`: `bool` *(required)*

Returns a `Coroutine` for
[UpdateAvailabilityOptionsResponseTypeDef](./type_defs.md#updateavailabilityoptionsresponsetypedef).

<a id="update_domain_endpoint_options"></a>

### update_domain_endpoint_options

Updates the domain's endpoint options, specifically whether all requests to the
domain must arrive over HTTPS.

Type annotations for
`aiobotocore.create_client("cloudsearch").update_domain_endpoint_options`
method.

Boto3 documentation:
[CloudSearch.Client.update_domain_endpoint_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.update_domain_endpoint_options)

Asynchronous method. Use `await update_domain_endpoint_options(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDomainEndpointOptionsRequestRequestTypeDef](./type_defs.md#updatedomainendpointoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `DomainEndpointOptions`:
  [DomainEndpointOptionsTypeDef](./type_defs.md#domainendpointoptionstypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateDomainEndpointOptionsResponseTypeDef](./type_defs.md#updatedomainendpointoptionsresponsetypedef).

<a id="update_scaling_parameters"></a>

### update_scaling_parameters

Configures scaling parameters for a domain.

Type annotations for
`aiobotocore.create_client("cloudsearch").update_scaling_parameters` method.

Boto3 documentation:
[CloudSearch.Client.update_scaling_parameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.update_scaling_parameters)

Asynchronous method. Use `await update_scaling_parameters(...)` for a
synchronous call.

Arguments mapping described in
[UpdateScalingParametersRequestRequestTypeDef](./type_defs.md#updatescalingparametersrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `ScalingParameters`:
  [ScalingParametersTypeDef](./type_defs.md#scalingparameterstypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateScalingParametersResponseTypeDef](./type_defs.md#updatescalingparametersresponsetypedef).

<a id="update_service_access_policies"></a>

### update_service_access_policies

Configures the access rules that control access to the domain's document and
search endpoints.

Type annotations for
`aiobotocore.create_client("cloudsearch").update_service_access_policies`
method.

Boto3 documentation:
[CloudSearch.Client.update_service_access_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch.Client.update_service_access_policies)

Asynchronous method. Use `await update_service_access_policies(...)` for a
synchronous call.

Arguments mapping described in
[UpdateServiceAccessPoliciesRequestRequestTypeDef](./type_defs.md#updateserviceaccesspoliciesrequestrequesttypedef).

Keyword-only arguments:

- `DomainName`: `str` *(required)*
- `AccessPolicies`: `str` *(required)*

Returns a `Coroutine` for
[UpdateServiceAccessPoliciesResponseTypeDef](./type_defs.md#updateserviceaccesspoliciesresponsetypedef).
