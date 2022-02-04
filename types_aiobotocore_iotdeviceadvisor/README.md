<a id="type-annotations-for-aiobotocore-iotdeviceadvisor-module"></a>

# Type annotations for aiobotocore IoTDeviceAdvisor module

> [Index](..) > IoTDeviceAdvisor

Auto-generated documentation for
[IoTDeviceAdvisor](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor)
type annotations stubs module
[types-aiobotocore-iotdeviceadvisor](https://pypi.org/project/types-aiobotocore-iotdeviceadvisor/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[iotdeviceadvisor]'

# install as a standalone
pip install types-aiobotocore-iotdeviceadvisor
```

- [Type annotations for aiobotocore IoTDeviceAdvisor module](#type-annotations-for-aiobotocore-iotdeviceadvisor-module)
  - [IoTDeviceAdvisorClient](#iotdeviceadvisorclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="iotdeviceadvisorclient"></a>

## IoTDeviceAdvisorClient

Type annotations for `aiobotocore.create_client("iotdeviceadvisor")` as
[IoTDeviceAdvisorClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_iotdeviceadvisor.client import IoTDeviceAdvisorClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_suite_definition](./client.md#create_suite_definition)
- [delete_suite_definition](./client.md#delete_suite_definition)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_endpoint](./client.md#get_endpoint)
- [get_suite_definition](./client.md#get_suite_definition)
- [get_suite_run](./client.md#get_suite_run)
- [get_suite_run_report](./client.md#get_suite_run_report)
- [list_suite_definitions](./client.md#list_suite_definitions)
- [list_suite_runs](./client.md#list_suite_runs)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [start_suite_run](./client.md#start_suite_run)
- [stop_suite_run](./client.md#stop_suite_run)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_suite_definition](./client.md#update_suite_definition)

<a id="exceptions"></a>

### Exceptions

IoTDeviceAdvisorClient [exceptions](./client.md#exceptions)

- ClientError
- ConflictException
- InternalServerException
- ResourceNotFoundException
- ValidationException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_iotdeviceadvisor.literals import StatusType, ...
```

- [StatusType](./literals.md#statustype)
- [SuiteRunStatusType](./literals.md#suiterunstatustype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_iotdeviceadvisor.type_defs import CreateSuiteDefinitionRequestRequestTypeDef, ...
```

- [CreateSuiteDefinitionRequestRequestTypeDef](./type_defs.md#createsuitedefinitionrequestrequesttypedef)
- [CreateSuiteDefinitionResponseTypeDef](./type_defs.md#createsuitedefinitionresponsetypedef)
- [DeleteSuiteDefinitionRequestRequestTypeDef](./type_defs.md#deletesuitedefinitionrequestrequesttypedef)
- [DeviceUnderTestTypeDef](./type_defs.md#deviceundertesttypedef)
- [GetEndpointRequestRequestTypeDef](./type_defs.md#getendpointrequestrequesttypedef)
- [GetEndpointResponseTypeDef](./type_defs.md#getendpointresponsetypedef)
- [GetSuiteDefinitionRequestRequestTypeDef](./type_defs.md#getsuitedefinitionrequestrequesttypedef)
- [GetSuiteDefinitionResponseTypeDef](./type_defs.md#getsuitedefinitionresponsetypedef)
- [GetSuiteRunReportRequestRequestTypeDef](./type_defs.md#getsuiterunreportrequestrequesttypedef)
- [GetSuiteRunReportResponseTypeDef](./type_defs.md#getsuiterunreportresponsetypedef)
- [GetSuiteRunRequestRequestTypeDef](./type_defs.md#getsuiterunrequestrequesttypedef)
- [GetSuiteRunResponseTypeDef](./type_defs.md#getsuiterunresponsetypedef)
- [GroupResultTypeDef](./type_defs.md#groupresulttypedef)
- [ListSuiteDefinitionsRequestRequestTypeDef](./type_defs.md#listsuitedefinitionsrequestrequesttypedef)
- [ListSuiteDefinitionsResponseTypeDef](./type_defs.md#listsuitedefinitionsresponsetypedef)
- [ListSuiteRunsRequestRequestTypeDef](./type_defs.md#listsuiterunsrequestrequesttypedef)
- [ListSuiteRunsResponseTypeDef](./type_defs.md#listsuiterunsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartSuiteRunRequestRequestTypeDef](./type_defs.md#startsuiterunrequestrequesttypedef)
- [StartSuiteRunResponseTypeDef](./type_defs.md#startsuiterunresponsetypedef)
- [StopSuiteRunRequestRequestTypeDef](./type_defs.md#stopsuiterunrequestrequesttypedef)
- [SuiteDefinitionConfigurationTypeDef](./type_defs.md#suitedefinitionconfigurationtypedef)
- [SuiteDefinitionInformationTypeDef](./type_defs.md#suitedefinitioninformationtypedef)
- [SuiteRunConfigurationTypeDef](./type_defs.md#suiterunconfigurationtypedef)
- [SuiteRunInformationTypeDef](./type_defs.md#suiteruninformationtypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TestCaseRunTypeDef](./type_defs.md#testcaseruntypedef)
- [TestResultTypeDef](./type_defs.md#testresulttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateSuiteDefinitionRequestRequestTypeDef](./type_defs.md#updatesuitedefinitionrequestrequesttypedef)
- [UpdateSuiteDefinitionResponseTypeDef](./type_defs.md#updatesuitedefinitionresponsetypedef)
