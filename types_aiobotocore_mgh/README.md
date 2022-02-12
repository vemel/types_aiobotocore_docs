<a id="type-annotations-for-aiobotocore-migrationhub-module"></a>

# Type annotations for aiobotocore MigrationHub module

> [Index](..) > MigrationHub

Auto-generated documentation for
[MigrationHub](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub)
type annotations stubs module
[types-aiobotocore-mgh](https://pypi.org/project/types-aiobotocore-mgh/).

- [Type annotations for aiobotocore MigrationHub module](#type-annotations-for-aiobotocore-migrationhub-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [MigrationHubClient](#migrationhubclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `MigrationHub`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `MigrationHub` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[mgh]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[mgh]'

# standalone installation
python -m pip install types-aiobotocore-mgh
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-mgh
```

<a id="migrationhubclient"></a>

## MigrationHubClient

Type annotations for `session.create_client("mgh")` as
[MigrationHubClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_mgh.client import MigrationHubClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [associate_created_artifact](./client.md#associate_created_artifact)
- [associate_discovered_resource](./client.md#associate_discovered_resource)
- [can_paginate](./client.md#can_paginate)
- [create_progress_update_stream](./client.md#create_progress_update_stream)
- [delete_progress_update_stream](./client.md#delete_progress_update_stream)
- [describe_application_state](./client.md#describe_application_state)
- [describe_migration_task](./client.md#describe_migration_task)
- [disassociate_created_artifact](./client.md#disassociate_created_artifact)
- [disassociate_discovered_resource](./client.md#disassociate_discovered_resource)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [import_migration_task](./client.md#import_migration_task)
- [list_application_states](./client.md#list_application_states)
- [list_created_artifacts](./client.md#list_created_artifacts)
- [list_discovered_resources](./client.md#list_discovered_resources)
- [list_migration_tasks](./client.md#list_migration_tasks)
- [list_progress_update_streams](./client.md#list_progress_update_streams)
- [notify_application_state](./client.md#notify_application_state)
- [notify_migration_task_state](./client.md#notify_migration_task_state)
- [put_resource_attributes](./client.md#put_resource_attributes)

<a id="exceptions"></a>

### Exceptions

MigrationHubClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- DryRunOperation
- HomeRegionNotSetException
- InternalServerError
- InvalidInputException
- PolicyErrorException
- ResourceNotFoundException
- ServiceUnavailableException
- ThrottlingException
- UnauthorizedOperation

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("mgh").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_mgh.paginator import ListApplicationStatesPaginator, ...
```

- [ListApplicationStatesPaginator](./paginators.md#listapplicationstatespaginator)
- [ListCreatedArtifactsPaginator](./paginators.md#listcreatedartifactspaginator)
- [ListDiscoveredResourcesPaginator](./paginators.md#listdiscoveredresourcespaginator)
- [ListMigrationTasksPaginator](./paginators.md#listmigrationtaskspaginator)
- [ListProgressUpdateStreamsPaginator](./paginators.md#listprogressupdatestreamspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_mgh.literals import ApplicationStatusType, ...
```

- [ApplicationStatusType](./literals.md#applicationstatustype)
- [ListApplicationStatesPaginatorName](./literals.md#listapplicationstatespaginatorname)
- [ListCreatedArtifactsPaginatorName](./literals.md#listcreatedartifactspaginatorname)
- [ListDiscoveredResourcesPaginatorName](./literals.md#listdiscoveredresourcespaginatorname)
- [ListMigrationTasksPaginatorName](./literals.md#listmigrationtaskspaginatorname)
- [ListProgressUpdateStreamsPaginatorName](./literals.md#listprogressupdatestreamspaginatorname)
- [ResourceAttributeTypeType](./literals.md#resourceattributetypetype)
- [StatusType](./literals.md#statustype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_mgh.type_defs import ApplicationStateTypeDef, ...
```

- [ApplicationStateTypeDef](./type_defs.md#applicationstatetypedef)
- [AssociateCreatedArtifactRequestRequestTypeDef](./type_defs.md#associatecreatedartifactrequestrequesttypedef)
- [AssociateDiscoveredResourceRequestRequestTypeDef](./type_defs.md#associatediscoveredresourcerequestrequesttypedef)
- [CreateProgressUpdateStreamRequestRequestTypeDef](./type_defs.md#createprogressupdatestreamrequestrequesttypedef)
- [CreatedArtifactTypeDef](./type_defs.md#createdartifacttypedef)
- [DeleteProgressUpdateStreamRequestRequestTypeDef](./type_defs.md#deleteprogressupdatestreamrequestrequesttypedef)
- [DescribeApplicationStateRequestRequestTypeDef](./type_defs.md#describeapplicationstaterequestrequesttypedef)
- [DescribeApplicationStateResultTypeDef](./type_defs.md#describeapplicationstateresulttypedef)
- [DescribeMigrationTaskRequestRequestTypeDef](./type_defs.md#describemigrationtaskrequestrequesttypedef)
- [DescribeMigrationTaskResultTypeDef](./type_defs.md#describemigrationtaskresulttypedef)
- [DisassociateCreatedArtifactRequestRequestTypeDef](./type_defs.md#disassociatecreatedartifactrequestrequesttypedef)
- [DisassociateDiscoveredResourceRequestRequestTypeDef](./type_defs.md#disassociatediscoveredresourcerequestrequesttypedef)
- [DiscoveredResourceTypeDef](./type_defs.md#discoveredresourcetypedef)
- [ImportMigrationTaskRequestRequestTypeDef](./type_defs.md#importmigrationtaskrequestrequesttypedef)
- [ListApplicationStatesRequestRequestTypeDef](./type_defs.md#listapplicationstatesrequestrequesttypedef)
- [ListApplicationStatesResultTypeDef](./type_defs.md#listapplicationstatesresulttypedef)
- [ListCreatedArtifactsRequestRequestTypeDef](./type_defs.md#listcreatedartifactsrequestrequesttypedef)
- [ListCreatedArtifactsResultTypeDef](./type_defs.md#listcreatedartifactsresulttypedef)
- [ListDiscoveredResourcesRequestRequestTypeDef](./type_defs.md#listdiscoveredresourcesrequestrequesttypedef)
- [ListDiscoveredResourcesResultTypeDef](./type_defs.md#listdiscoveredresourcesresulttypedef)
- [ListMigrationTasksRequestRequestTypeDef](./type_defs.md#listmigrationtasksrequestrequesttypedef)
- [ListMigrationTasksResultTypeDef](./type_defs.md#listmigrationtasksresulttypedef)
- [ListProgressUpdateStreamsRequestRequestTypeDef](./type_defs.md#listprogressupdatestreamsrequestrequesttypedef)
- [ListProgressUpdateStreamsResultTypeDef](./type_defs.md#listprogressupdatestreamsresulttypedef)
- [MigrationTaskSummaryTypeDef](./type_defs.md#migrationtasksummarytypedef)
- [MigrationTaskTypeDef](./type_defs.md#migrationtasktypedef)
- [NotifyApplicationStateRequestRequestTypeDef](./type_defs.md#notifyapplicationstaterequestrequesttypedef)
- [NotifyMigrationTaskStateRequestRequestTypeDef](./type_defs.md#notifymigrationtaskstaterequestrequesttypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ProgressUpdateStreamSummaryTypeDef](./type_defs.md#progressupdatestreamsummarytypedef)
- [PutResourceAttributesRequestRequestTypeDef](./type_defs.md#putresourceattributesrequestrequesttypedef)
- [ResourceAttributeTypeDef](./type_defs.md#resourceattributetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TaskTypeDef](./type_defs.md#tasktypedef)
