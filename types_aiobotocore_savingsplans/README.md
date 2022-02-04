<a id="type-annotations-for-aiobotocore-savingsplans-module"></a>

# Type annotations for aiobotocore SavingsPlans module

> [Index](..) > SavingsPlans

Auto-generated documentation for
[SavingsPlans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/savingsplans.html#SavingsPlans)
type annotations stubs module
[types-aiobotocore-savingsplans](https://pypi.org/project/types-aiobotocore-savingsplans/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[savingsplans]'

# install as a standalone
pip install types-aiobotocore-savingsplans
```

- [Type annotations for aiobotocore SavingsPlans module](#type-annotations-for-aiobotocore-savingsplans-module)
  - [SavingsPlansClient](#savingsplansclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="savingsplansclient"></a>

## SavingsPlansClient

Type annotations for `aiobotocore.create_client("savingsplans")` as
[SavingsPlansClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_savingsplans.client import SavingsPlansClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_savings_plan](./client.md#create_savings_plan)
- [delete_queued_savings_plan](./client.md#delete_queued_savings_plan)
- [describe_savings_plan_rates](./client.md#describe_savings_plan_rates)
- [describe_savings_plans](./client.md#describe_savings_plans)
- [describe_savings_plans_offering_rates](./client.md#describe_savings_plans_offering_rates)
- [describe_savings_plans_offerings](./client.md#describe_savings_plans_offerings)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)

<a id="exceptions"></a>

### Exceptions

SavingsPlansClient [exceptions](./client.md#exceptions)

- ClientError
- InternalServerException
- ResourceNotFoundException
- ServiceQuotaExceededException
- ValidationException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_savingsplans.literals import CurrencyCodeType, ...
```

- [CurrencyCodeType](./literals.md#currencycodetype)
- [SavingsPlanOfferingFilterAttributeType](./literals.md#savingsplanofferingfilterattributetype)
- [SavingsPlanOfferingPropertyKeyType](./literals.md#savingsplanofferingpropertykeytype)
- [SavingsPlanPaymentOptionType](./literals.md#savingsplanpaymentoptiontype)
- [SavingsPlanProductTypeType](./literals.md#savingsplanproducttypetype)
- [SavingsPlanRateFilterAttributeType](./literals.md#savingsplanratefilterattributetype)
- [SavingsPlanRateFilterNameType](./literals.md#savingsplanratefilternametype)
- [SavingsPlanRatePropertyKeyType](./literals.md#savingsplanratepropertykeytype)
- [SavingsPlanRateServiceCodeType](./literals.md#savingsplanrateservicecodetype)
- [SavingsPlanRateUnitType](./literals.md#savingsplanrateunittype)
- [SavingsPlanStateType](./literals.md#savingsplanstatetype)
- [SavingsPlanTypeType](./literals.md#savingsplantypetype)
- [SavingsPlansFilterNameType](./literals.md#savingsplansfilternametype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_savingsplans.type_defs import CreateSavingsPlanRequestRequestTypeDef, ...
```

- [CreateSavingsPlanRequestRequestTypeDef](./type_defs.md#createsavingsplanrequestrequesttypedef)
- [CreateSavingsPlanResponseTypeDef](./type_defs.md#createsavingsplanresponsetypedef)
- [DeleteQueuedSavingsPlanRequestRequestTypeDef](./type_defs.md#deletequeuedsavingsplanrequestrequesttypedef)
- [DescribeSavingsPlanRatesRequestRequestTypeDef](./type_defs.md#describesavingsplanratesrequestrequesttypedef)
- [DescribeSavingsPlanRatesResponseTypeDef](./type_defs.md#describesavingsplanratesresponsetypedef)
- [DescribeSavingsPlansOfferingRatesRequestRequestTypeDef](./type_defs.md#describesavingsplansofferingratesrequestrequesttypedef)
- [DescribeSavingsPlansOfferingRatesResponseTypeDef](./type_defs.md#describesavingsplansofferingratesresponsetypedef)
- [DescribeSavingsPlansOfferingsRequestRequestTypeDef](./type_defs.md#describesavingsplansofferingsrequestrequesttypedef)
- [DescribeSavingsPlansOfferingsResponseTypeDef](./type_defs.md#describesavingsplansofferingsresponsetypedef)
- [DescribeSavingsPlansRequestRequestTypeDef](./type_defs.md#describesavingsplansrequestrequesttypedef)
- [DescribeSavingsPlansResponseTypeDef](./type_defs.md#describesavingsplansresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ParentSavingsPlanOfferingTypeDef](./type_defs.md#parentsavingsplanofferingtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SavingsPlanFilterTypeDef](./type_defs.md#savingsplanfiltertypedef)
- [SavingsPlanOfferingFilterElementTypeDef](./type_defs.md#savingsplanofferingfilterelementtypedef)
- [SavingsPlanOfferingPropertyTypeDef](./type_defs.md#savingsplanofferingpropertytypedef)
- [SavingsPlanOfferingRateFilterElementTypeDef](./type_defs.md#savingsplanofferingratefilterelementtypedef)
- [SavingsPlanOfferingRatePropertyTypeDef](./type_defs.md#savingsplanofferingratepropertytypedef)
- [SavingsPlanOfferingRateTypeDef](./type_defs.md#savingsplanofferingratetypedef)
- [SavingsPlanOfferingTypeDef](./type_defs.md#savingsplanofferingtypedef)
- [SavingsPlanRateFilterTypeDef](./type_defs.md#savingsplanratefiltertypedef)
- [SavingsPlanRatePropertyTypeDef](./type_defs.md#savingsplanratepropertytypedef)
- [SavingsPlanRateTypeDef](./type_defs.md#savingsplanratetypedef)
- [SavingsPlanTypeDef](./type_defs.md#savingsplantypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
