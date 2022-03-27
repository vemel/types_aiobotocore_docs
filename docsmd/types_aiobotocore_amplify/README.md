# Amplify module

> [Index](../README.md) > Amplify


!!! note ""

    Auto-generated documentation for [Amplify](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplify.html#Amplify)
    type annotations stubs module [types-aiobotocore-amplify](https://pypi.org/project/types-aiobotocore-amplify/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `Amplify`.

### From PyPI with pip

Install `types-aiobotocore` for `Amplify` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[amplify]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[amplify]'


# standalone installation
python -m pip install types-aiobotocore-amplify
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-amplify
```

## Usage

Code samples can be found in [Examples](./usage.md).

## AmplifyClient

Type annotations and code completion for  `#!python session.create_client("amplify")` as [AmplifyClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplify.html#Amplify.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_amplify.client import AmplifyClient


session = get_session()
async with session.create_client("amplify") as client:
    client: AmplifyClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("amplify").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_amplify.paginator import ListAppsPaginator

def get_list_apps_paginator() -> ListAppsPaginator:
    return client.get_paginator("list_apps"))
```

- [ListAppsPaginator](./paginators.md#listappspaginator)
- [ListBranchesPaginator](./paginators.md#listbranchespaginator)
- [ListDomainAssociationsPaginator](./paginators.md#listdomainassociationspaginator)
- [ListJobsPaginator](./paginators.md#listjobspaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_amplify.literals import DomainStatusType

def get_value() -> DomainStatusType:
    return "AVAILABLE"
```

- [DomainStatusType](./literals.md#domainstatustype)
- [JobStatusType](./literals.md#jobstatustype)
- [JobTypeType](./literals.md#jobtypetype)
- [ListAppsPaginatorName](./literals.md#listappspaginatorname)
- [ListBranchesPaginatorName](./literals.md#listbranchespaginatorname)
- [ListDomainAssociationsPaginatorName](./literals.md#listdomainassociationspaginatorname)
- [ListJobsPaginatorName](./literals.md#listjobspaginatorname)
- [PlatformType](./literals.md#platformtype)
- [RepositoryCloneMethodType](./literals.md#repositoryclonemethodtype)
- [StageType](./literals.md#stagetype)
- [AmplifyServiceName](./literals.md#amplifyservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_amplify.type_defs import AppTypeDef

def get_value() -> AppTypeDef:
    return {
        "appId": ...,
        "appArn": ...,
        "name": ...,
        "description": ...,
        "repository": ...,
        "platform": ...,
        "createTime": ...,
        "updateTime": ...,
        "environmentVariables": ...,
        "defaultDomain": ...,
        "enableBranchAutoBuild": ...,
        "enableBasicAuth": ...,
    }
```

- [AppTypeDef](./type_defs.md#apptypedef)
- [ArtifactTypeDef](./type_defs.md#artifacttypedef)
- [AutoBranchCreationConfigTypeDef](./type_defs.md#autobranchcreationconfigtypedef)
- [BackendEnvironmentTypeDef](./type_defs.md#backendenvironmenttypedef)
- [BranchTypeDef](./type_defs.md#branchtypedef)
- [CreateAppRequestRequestTypeDef](./type_defs.md#createapprequestrequesttypedef)
- [CreateAppResultTypeDef](./type_defs.md#createappresulttypedef)
- [CreateBackendEnvironmentRequestRequestTypeDef](./type_defs.md#createbackendenvironmentrequestrequesttypedef)
- [CreateBackendEnvironmentResultTypeDef](./type_defs.md#createbackendenvironmentresulttypedef)
- [CreateBranchRequestRequestTypeDef](./type_defs.md#createbranchrequestrequesttypedef)
- [CreateBranchResultTypeDef](./type_defs.md#createbranchresulttypedef)
- [CreateDeploymentRequestRequestTypeDef](./type_defs.md#createdeploymentrequestrequesttypedef)
- [CreateDeploymentResultTypeDef](./type_defs.md#createdeploymentresulttypedef)
- [CreateDomainAssociationRequestRequestTypeDef](./type_defs.md#createdomainassociationrequestrequesttypedef)
- [CreateDomainAssociationResultTypeDef](./type_defs.md#createdomainassociationresulttypedef)
- [CreateWebhookRequestRequestTypeDef](./type_defs.md#createwebhookrequestrequesttypedef)
- [CreateWebhookResultTypeDef](./type_defs.md#createwebhookresulttypedef)
- [CustomRuleTypeDef](./type_defs.md#customruletypedef)
- [DeleteAppRequestRequestTypeDef](./type_defs.md#deleteapprequestrequesttypedef)
- [DeleteAppResultTypeDef](./type_defs.md#deleteappresulttypedef)
- [DeleteBackendEnvironmentRequestRequestTypeDef](./type_defs.md#deletebackendenvironmentrequestrequesttypedef)
- [DeleteBackendEnvironmentResultTypeDef](./type_defs.md#deletebackendenvironmentresulttypedef)
- [DeleteBranchRequestRequestTypeDef](./type_defs.md#deletebranchrequestrequesttypedef)
- [DeleteBranchResultTypeDef](./type_defs.md#deletebranchresulttypedef)
- [DeleteDomainAssociationRequestRequestTypeDef](./type_defs.md#deletedomainassociationrequestrequesttypedef)
- [DeleteDomainAssociationResultTypeDef](./type_defs.md#deletedomainassociationresulttypedef)
- [DeleteJobRequestRequestTypeDef](./type_defs.md#deletejobrequestrequesttypedef)
- [DeleteJobResultTypeDef](./type_defs.md#deletejobresulttypedef)
- [DeleteWebhookRequestRequestTypeDef](./type_defs.md#deletewebhookrequestrequesttypedef)
- [DeleteWebhookResultTypeDef](./type_defs.md#deletewebhookresulttypedef)
- [DomainAssociationTypeDef](./type_defs.md#domainassociationtypedef)
- [GenerateAccessLogsRequestRequestTypeDef](./type_defs.md#generateaccesslogsrequestrequesttypedef)
- [GenerateAccessLogsResultTypeDef](./type_defs.md#generateaccesslogsresulttypedef)
- [GetAppRequestRequestTypeDef](./type_defs.md#getapprequestrequesttypedef)
- [GetAppResultTypeDef](./type_defs.md#getappresulttypedef)
- [GetArtifactUrlRequestRequestTypeDef](./type_defs.md#getartifacturlrequestrequesttypedef)
- [GetArtifactUrlResultTypeDef](./type_defs.md#getartifacturlresulttypedef)
- [GetBackendEnvironmentRequestRequestTypeDef](./type_defs.md#getbackendenvironmentrequestrequesttypedef)
- [GetBackendEnvironmentResultTypeDef](./type_defs.md#getbackendenvironmentresulttypedef)
- [GetBranchRequestRequestTypeDef](./type_defs.md#getbranchrequestrequesttypedef)
- [GetBranchResultTypeDef](./type_defs.md#getbranchresulttypedef)
- [GetDomainAssociationRequestRequestTypeDef](./type_defs.md#getdomainassociationrequestrequesttypedef)
- [GetDomainAssociationResultTypeDef](./type_defs.md#getdomainassociationresulttypedef)
- [GetJobRequestRequestTypeDef](./type_defs.md#getjobrequestrequesttypedef)
- [GetJobResultTypeDef](./type_defs.md#getjobresulttypedef)
- [GetWebhookRequestRequestTypeDef](./type_defs.md#getwebhookrequestrequesttypedef)
- [GetWebhookResultTypeDef](./type_defs.md#getwebhookresulttypedef)
- [JobSummaryTypeDef](./type_defs.md#jobsummarytypedef)
- [JobTypeDef](./type_defs.md#jobtypedef)
- [ListAppsRequestListAppsPaginateTypeDef](./type_defs.md#listappsrequestlistappspaginatetypedef)
- [ListAppsRequestRequestTypeDef](./type_defs.md#listappsrequestrequesttypedef)
- [ListAppsResultTypeDef](./type_defs.md#listappsresulttypedef)
- [ListArtifactsRequestRequestTypeDef](./type_defs.md#listartifactsrequestrequesttypedef)
- [ListArtifactsResultTypeDef](./type_defs.md#listartifactsresulttypedef)
- [ListBackendEnvironmentsRequestRequestTypeDef](./type_defs.md#listbackendenvironmentsrequestrequesttypedef)
- [ListBackendEnvironmentsResultTypeDef](./type_defs.md#listbackendenvironmentsresulttypedef)
- [ListBranchesRequestListBranchesPaginateTypeDef](./type_defs.md#listbranchesrequestlistbranchespaginatetypedef)
- [ListBranchesRequestRequestTypeDef](./type_defs.md#listbranchesrequestrequesttypedef)
- [ListBranchesResultTypeDef](./type_defs.md#listbranchesresulttypedef)
- [ListDomainAssociationsRequestListDomainAssociationsPaginateTypeDef](./type_defs.md#listdomainassociationsrequestlistdomainassociationspaginatetypedef)
- [ListDomainAssociationsRequestRequestTypeDef](./type_defs.md#listdomainassociationsrequestrequesttypedef)
- [ListDomainAssociationsResultTypeDef](./type_defs.md#listdomainassociationsresulttypedef)
- [ListJobsRequestListJobsPaginateTypeDef](./type_defs.md#listjobsrequestlistjobspaginatetypedef)
- [ListJobsRequestRequestTypeDef](./type_defs.md#listjobsrequestrequesttypedef)
- [ListJobsResultTypeDef](./type_defs.md#listjobsresulttypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListWebhooksRequestRequestTypeDef](./type_defs.md#listwebhooksrequestrequesttypedef)
- [ListWebhooksResultTypeDef](./type_defs.md#listwebhooksresulttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ProductionBranchTypeDef](./type_defs.md#productionbranchtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [StartDeploymentRequestRequestTypeDef](./type_defs.md#startdeploymentrequestrequesttypedef)
- [StartDeploymentResultTypeDef](./type_defs.md#startdeploymentresulttypedef)
- [StartJobRequestRequestTypeDef](./type_defs.md#startjobrequestrequesttypedef)
- [StartJobResultTypeDef](./type_defs.md#startjobresulttypedef)
- [StepTypeDef](./type_defs.md#steptypedef)
- [StopJobRequestRequestTypeDef](./type_defs.md#stopjobrequestrequesttypedef)
- [StopJobResultTypeDef](./type_defs.md#stopjobresulttypedef)
- [SubDomainSettingTypeDef](./type_defs.md#subdomainsettingtypedef)
- [SubDomainTypeDef](./type_defs.md#subdomaintypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateAppRequestRequestTypeDef](./type_defs.md#updateapprequestrequesttypedef)
- [UpdateAppResultTypeDef](./type_defs.md#updateappresulttypedef)
- [UpdateBranchRequestRequestTypeDef](./type_defs.md#updatebranchrequestrequesttypedef)
- [UpdateBranchResultTypeDef](./type_defs.md#updatebranchresulttypedef)
- [UpdateDomainAssociationRequestRequestTypeDef](./type_defs.md#updatedomainassociationrequestrequesttypedef)
- [UpdateDomainAssociationResultTypeDef](./type_defs.md#updatedomainassociationresulttypedef)
- [UpdateWebhookRequestRequestTypeDef](./type_defs.md#updatewebhookrequestrequesttypedef)
- [UpdateWebhookResultTypeDef](./type_defs.md#updatewebhookresulttypedef)
- [WebhookTypeDef](./type_defs.md#webhooktypedef)

