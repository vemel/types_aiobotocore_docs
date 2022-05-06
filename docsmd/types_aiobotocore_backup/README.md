# Backup module

> [Index](../README.md) > Backup


!!! note ""

    Auto-generated documentation for [Backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
    type annotations stubs module [types-aiobotocore-backup](https://pypi.org/project/types-aiobotocore-backup/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `Backup`.

### From PyPI with pip

Install `types-aiobotocore` for `Backup` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[backup]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[backup]'


# standalone installation
python -m pip install types-aiobotocore-backup
```



## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-backup
```

## Usage

Code samples can be found in [Examples](./usage.md).

## BackupClient

Type annotations and code completion for  `#!python session.create_client("backup")` as [BackupClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_backup.client import BackupClient


session = get_session()
async with session.create_client("backup") as client:
    client: BackupClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("backup").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_backup.paginator import ListBackupJobsPaginator

def get_list_backup_jobs_paginator() -> ListBackupJobsPaginator:
    return client.get_paginator("list_backup_jobs"))
```

- [ListBackupJobsPaginator](./paginators.md#listbackupjobspaginator)
- [ListBackupPlanTemplatesPaginator](./paginators.md#listbackupplantemplatespaginator)
- [ListBackupPlanVersionsPaginator](./paginators.md#listbackupplanversionspaginator)
- [ListBackupPlansPaginator](./paginators.md#listbackupplanspaginator)
- [ListBackupSelectionsPaginator](./paginators.md#listbackupselectionspaginator)
- [ListBackupVaultsPaginator](./paginators.md#listbackupvaultspaginator)
- [ListCopyJobsPaginator](./paginators.md#listcopyjobspaginator)
- [ListProtectedResourcesPaginator](./paginators.md#listprotectedresourcespaginator)
- [ListRecoveryPointsByBackupVaultPaginator](./paginators.md#listrecoverypointsbybackupvaultpaginator)
- [ListRecoveryPointsByResourcePaginator](./paginators.md#listrecoverypointsbyresourcepaginator)
- [ListRestoreJobsPaginator](./paginators.md#listrestorejobspaginator)








## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_backup.literals import BackupJobStateType

def get_value() -> BackupJobStateType:
    return "ABORTED"
```

- [BackupJobStateType](./literals.md#backupjobstatetype)
- [BackupVaultEventType](./literals.md#backupvaulteventtype)
- [ConditionTypeType](./literals.md#conditiontypetype)
- [CopyJobStateType](./literals.md#copyjobstatetype)
- [ListBackupJobsPaginatorName](./literals.md#listbackupjobspaginatorname)
- [ListBackupPlanTemplatesPaginatorName](./literals.md#listbackupplantemplatespaginatorname)
- [ListBackupPlanVersionsPaginatorName](./literals.md#listbackupplanversionspaginatorname)
- [ListBackupPlansPaginatorName](./literals.md#listbackupplanspaginatorname)
- [ListBackupSelectionsPaginatorName](./literals.md#listbackupselectionspaginatorname)
- [ListBackupVaultsPaginatorName](./literals.md#listbackupvaultspaginatorname)
- [ListCopyJobsPaginatorName](./literals.md#listcopyjobspaginatorname)
- [ListProtectedResourcesPaginatorName](./literals.md#listprotectedresourcespaginatorname)
- [ListRecoveryPointsByBackupVaultPaginatorName](./literals.md#listrecoverypointsbybackupvaultpaginatorname)
- [ListRecoveryPointsByResourcePaginatorName](./literals.md#listrecoverypointsbyresourcepaginatorname)
- [ListRestoreJobsPaginatorName](./literals.md#listrestorejobspaginatorname)
- [RecoveryPointStatusType](./literals.md#recoverypointstatustype)
- [RestoreJobStatusType](./literals.md#restorejobstatustype)
- [StorageClassType](./literals.md#storageclasstype)
- [BackupServiceName](./literals.md#backupservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_backup.type_defs import AdvancedBackupSettingTypeDef

def get_value() -> AdvancedBackupSettingTypeDef:
    return {
        "ResourceType": ...,
    }
```

- [AdvancedBackupSettingTypeDef](./type_defs.md#advancedbackupsettingtypedef)
- [BackupJobTypeDef](./type_defs.md#backupjobtypedef)
- [BackupPlanInputTypeDef](./type_defs.md#backupplaninputtypedef)
- [BackupPlanTemplatesListMemberTypeDef](./type_defs.md#backupplantemplateslistmembertypedef)
- [BackupPlanTypeDef](./type_defs.md#backupplantypedef)
- [BackupPlansListMemberTypeDef](./type_defs.md#backupplanslistmembertypedef)
- [BackupRuleInputTypeDef](./type_defs.md#backupruleinputtypedef)
- [BackupRuleTypeDef](./type_defs.md#backupruletypedef)
- [BackupSelectionTypeDef](./type_defs.md#backupselectiontypedef)
- [BackupSelectionsListMemberTypeDef](./type_defs.md#backupselectionslistmembertypedef)
- [BackupVaultListMemberTypeDef](./type_defs.md#backupvaultlistmembertypedef)
- [CalculatedLifecycleTypeDef](./type_defs.md#calculatedlifecycletypedef)
- [ConditionParameterTypeDef](./type_defs.md#conditionparametertypedef)
- [ConditionTypeDef](./type_defs.md#conditiontypedef)
- [ConditionsTypeDef](./type_defs.md#conditionstypedef)
- [ControlInputParameterTypeDef](./type_defs.md#controlinputparametertypedef)
- [ControlScopeTypeDef](./type_defs.md#controlscopetypedef)
- [CopyActionTypeDef](./type_defs.md#copyactiontypedef)
- [CopyJobTypeDef](./type_defs.md#copyjobtypedef)
- [CreateBackupPlanInputRequestTypeDef](./type_defs.md#createbackupplaninputrequesttypedef)
- [CreateBackupPlanOutputTypeDef](./type_defs.md#createbackupplanoutputtypedef)
- [CreateBackupSelectionInputRequestTypeDef](./type_defs.md#createbackupselectioninputrequesttypedef)
- [CreateBackupSelectionOutputTypeDef](./type_defs.md#createbackupselectionoutputtypedef)
- [CreateBackupVaultInputRequestTypeDef](./type_defs.md#createbackupvaultinputrequesttypedef)
- [CreateBackupVaultOutputTypeDef](./type_defs.md#createbackupvaultoutputtypedef)
- [CreateFrameworkInputRequestTypeDef](./type_defs.md#createframeworkinputrequesttypedef)
- [CreateFrameworkOutputTypeDef](./type_defs.md#createframeworkoutputtypedef)
- [CreateReportPlanInputRequestTypeDef](./type_defs.md#createreportplaninputrequesttypedef)
- [CreateReportPlanOutputTypeDef](./type_defs.md#createreportplanoutputtypedef)
- [DeleteBackupPlanInputRequestTypeDef](./type_defs.md#deletebackupplaninputrequesttypedef)
- [DeleteBackupPlanOutputTypeDef](./type_defs.md#deletebackupplanoutputtypedef)
- [DeleteBackupSelectionInputRequestTypeDef](./type_defs.md#deletebackupselectioninputrequesttypedef)
- [DeleteBackupVaultAccessPolicyInputRequestTypeDef](./type_defs.md#deletebackupvaultaccesspolicyinputrequesttypedef)
- [DeleteBackupVaultInputRequestTypeDef](./type_defs.md#deletebackupvaultinputrequesttypedef)
- [DeleteBackupVaultLockConfigurationInputRequestTypeDef](./type_defs.md#deletebackupvaultlockconfigurationinputrequesttypedef)
- [DeleteBackupVaultNotificationsInputRequestTypeDef](./type_defs.md#deletebackupvaultnotificationsinputrequesttypedef)
- [DeleteFrameworkInputRequestTypeDef](./type_defs.md#deleteframeworkinputrequesttypedef)
- [DeleteRecoveryPointInputRequestTypeDef](./type_defs.md#deleterecoverypointinputrequesttypedef)
- [DeleteReportPlanInputRequestTypeDef](./type_defs.md#deletereportplaninputrequesttypedef)
- [DescribeBackupJobInputRequestTypeDef](./type_defs.md#describebackupjobinputrequesttypedef)
- [DescribeBackupJobOutputTypeDef](./type_defs.md#describebackupjoboutputtypedef)
- [DescribeBackupVaultInputRequestTypeDef](./type_defs.md#describebackupvaultinputrequesttypedef)
- [DescribeBackupVaultOutputTypeDef](./type_defs.md#describebackupvaultoutputtypedef)
- [DescribeCopyJobInputRequestTypeDef](./type_defs.md#describecopyjobinputrequesttypedef)
- [DescribeCopyJobOutputTypeDef](./type_defs.md#describecopyjoboutputtypedef)
- [DescribeFrameworkInputRequestTypeDef](./type_defs.md#describeframeworkinputrequesttypedef)
- [DescribeFrameworkOutputTypeDef](./type_defs.md#describeframeworkoutputtypedef)
- [DescribeGlobalSettingsOutputTypeDef](./type_defs.md#describeglobalsettingsoutputtypedef)
- [DescribeProtectedResourceInputRequestTypeDef](./type_defs.md#describeprotectedresourceinputrequesttypedef)
- [DescribeProtectedResourceOutputTypeDef](./type_defs.md#describeprotectedresourceoutputtypedef)
- [DescribeRecoveryPointInputRequestTypeDef](./type_defs.md#describerecoverypointinputrequesttypedef)
- [DescribeRecoveryPointOutputTypeDef](./type_defs.md#describerecoverypointoutputtypedef)
- [DescribeRegionSettingsOutputTypeDef](./type_defs.md#describeregionsettingsoutputtypedef)
- [DescribeReportJobInputRequestTypeDef](./type_defs.md#describereportjobinputrequesttypedef)
- [DescribeReportJobOutputTypeDef](./type_defs.md#describereportjoboutputtypedef)
- [DescribeReportPlanInputRequestTypeDef](./type_defs.md#describereportplaninputrequesttypedef)
- [DescribeReportPlanOutputTypeDef](./type_defs.md#describereportplanoutputtypedef)
- [DescribeRestoreJobInputRequestTypeDef](./type_defs.md#describerestorejobinputrequesttypedef)
- [DescribeRestoreJobOutputTypeDef](./type_defs.md#describerestorejoboutputtypedef)
- [DisassociateRecoveryPointInputRequestTypeDef](./type_defs.md#disassociaterecoverypointinputrequesttypedef)
- [ExportBackupPlanTemplateInputRequestTypeDef](./type_defs.md#exportbackupplantemplateinputrequesttypedef)
- [ExportBackupPlanTemplateOutputTypeDef](./type_defs.md#exportbackupplantemplateoutputtypedef)
- [FrameworkControlTypeDef](./type_defs.md#frameworkcontroltypedef)
- [FrameworkTypeDef](./type_defs.md#frameworktypedef)
- [GetBackupPlanFromJSONInputRequestTypeDef](./type_defs.md#getbackupplanfromjsoninputrequesttypedef)
- [GetBackupPlanFromJSONOutputTypeDef](./type_defs.md#getbackupplanfromjsonoutputtypedef)
- [GetBackupPlanFromTemplateInputRequestTypeDef](./type_defs.md#getbackupplanfromtemplateinputrequesttypedef)
- [GetBackupPlanFromTemplateOutputTypeDef](./type_defs.md#getbackupplanfromtemplateoutputtypedef)
- [GetBackupPlanInputRequestTypeDef](./type_defs.md#getbackupplaninputrequesttypedef)
- [GetBackupPlanOutputTypeDef](./type_defs.md#getbackupplanoutputtypedef)
- [GetBackupSelectionInputRequestTypeDef](./type_defs.md#getbackupselectioninputrequesttypedef)
- [GetBackupSelectionOutputTypeDef](./type_defs.md#getbackupselectionoutputtypedef)
- [GetBackupVaultAccessPolicyInputRequestTypeDef](./type_defs.md#getbackupvaultaccesspolicyinputrequesttypedef)
- [GetBackupVaultAccessPolicyOutputTypeDef](./type_defs.md#getbackupvaultaccesspolicyoutputtypedef)
- [GetBackupVaultNotificationsInputRequestTypeDef](./type_defs.md#getbackupvaultnotificationsinputrequesttypedef)
- [GetBackupVaultNotificationsOutputTypeDef](./type_defs.md#getbackupvaultnotificationsoutputtypedef)
- [GetRecoveryPointRestoreMetadataInputRequestTypeDef](./type_defs.md#getrecoverypointrestoremetadatainputrequesttypedef)
- [GetRecoveryPointRestoreMetadataOutputTypeDef](./type_defs.md#getrecoverypointrestoremetadataoutputtypedef)
- [GetSupportedResourceTypesOutputTypeDef](./type_defs.md#getsupportedresourcetypesoutputtypedef)
- [LifecycleTypeDef](./type_defs.md#lifecycletypedef)
- [ListBackupJobsInputListBackupJobsPaginateTypeDef](./type_defs.md#listbackupjobsinputlistbackupjobspaginatetypedef)
- [ListBackupJobsInputRequestTypeDef](./type_defs.md#listbackupjobsinputrequesttypedef)
- [ListBackupJobsOutputTypeDef](./type_defs.md#listbackupjobsoutputtypedef)
- [ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef](./type_defs.md#listbackupplantemplatesinputlistbackupplantemplatespaginatetypedef)
- [ListBackupPlanTemplatesInputRequestTypeDef](./type_defs.md#listbackupplantemplatesinputrequesttypedef)
- [ListBackupPlanTemplatesOutputTypeDef](./type_defs.md#listbackupplantemplatesoutputtypedef)
- [ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef](./type_defs.md#listbackupplanversionsinputlistbackupplanversionspaginatetypedef)
- [ListBackupPlanVersionsInputRequestTypeDef](./type_defs.md#listbackupplanversionsinputrequesttypedef)
- [ListBackupPlanVersionsOutputTypeDef](./type_defs.md#listbackupplanversionsoutputtypedef)
- [ListBackupPlansInputListBackupPlansPaginateTypeDef](./type_defs.md#listbackupplansinputlistbackupplanspaginatetypedef)
- [ListBackupPlansInputRequestTypeDef](./type_defs.md#listbackupplansinputrequesttypedef)
- [ListBackupPlansOutputTypeDef](./type_defs.md#listbackupplansoutputtypedef)
- [ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef](./type_defs.md#listbackupselectionsinputlistbackupselectionspaginatetypedef)
- [ListBackupSelectionsInputRequestTypeDef](./type_defs.md#listbackupselectionsinputrequesttypedef)
- [ListBackupSelectionsOutputTypeDef](./type_defs.md#listbackupselectionsoutputtypedef)
- [ListBackupVaultsInputListBackupVaultsPaginateTypeDef](./type_defs.md#listbackupvaultsinputlistbackupvaultspaginatetypedef)
- [ListBackupVaultsInputRequestTypeDef](./type_defs.md#listbackupvaultsinputrequesttypedef)
- [ListBackupVaultsOutputTypeDef](./type_defs.md#listbackupvaultsoutputtypedef)
- [ListCopyJobsInputListCopyJobsPaginateTypeDef](./type_defs.md#listcopyjobsinputlistcopyjobspaginatetypedef)
- [ListCopyJobsInputRequestTypeDef](./type_defs.md#listcopyjobsinputrequesttypedef)
- [ListCopyJobsOutputTypeDef](./type_defs.md#listcopyjobsoutputtypedef)
- [ListFrameworksInputRequestTypeDef](./type_defs.md#listframeworksinputrequesttypedef)
- [ListFrameworksOutputTypeDef](./type_defs.md#listframeworksoutputtypedef)
- [ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef](./type_defs.md#listprotectedresourcesinputlistprotectedresourcespaginatetypedef)
- [ListProtectedResourcesInputRequestTypeDef](./type_defs.md#listprotectedresourcesinputrequesttypedef)
- [ListProtectedResourcesOutputTypeDef](./type_defs.md#listprotectedresourcesoutputtypedef)
- [ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef](./type_defs.md#listrecoverypointsbybackupvaultinputlistrecoverypointsbybackupvaultpaginatetypedef)
- [ListRecoveryPointsByBackupVaultInputRequestTypeDef](./type_defs.md#listrecoverypointsbybackupvaultinputrequesttypedef)
- [ListRecoveryPointsByBackupVaultOutputTypeDef](./type_defs.md#listrecoverypointsbybackupvaultoutputtypedef)
- [ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef](./type_defs.md#listrecoverypointsbyresourceinputlistrecoverypointsbyresourcepaginatetypedef)
- [ListRecoveryPointsByResourceInputRequestTypeDef](./type_defs.md#listrecoverypointsbyresourceinputrequesttypedef)
- [ListRecoveryPointsByResourceOutputTypeDef](./type_defs.md#listrecoverypointsbyresourceoutputtypedef)
- [ListReportJobsInputRequestTypeDef](./type_defs.md#listreportjobsinputrequesttypedef)
- [ListReportJobsOutputTypeDef](./type_defs.md#listreportjobsoutputtypedef)
- [ListReportPlansInputRequestTypeDef](./type_defs.md#listreportplansinputrequesttypedef)
- [ListReportPlansOutputTypeDef](./type_defs.md#listreportplansoutputtypedef)
- [ListRestoreJobsInputListRestoreJobsPaginateTypeDef](./type_defs.md#listrestorejobsinputlistrestorejobspaginatetypedef)
- [ListRestoreJobsInputRequestTypeDef](./type_defs.md#listrestorejobsinputrequesttypedef)
- [ListRestoreJobsOutputTypeDef](./type_defs.md#listrestorejobsoutputtypedef)
- [ListTagsInputRequestTypeDef](./type_defs.md#listtagsinputrequesttypedef)
- [ListTagsOutputTypeDef](./type_defs.md#listtagsoutputtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ProtectedResourceTypeDef](./type_defs.md#protectedresourcetypedef)
- [PutBackupVaultAccessPolicyInputRequestTypeDef](./type_defs.md#putbackupvaultaccesspolicyinputrequesttypedef)
- [PutBackupVaultLockConfigurationInputRequestTypeDef](./type_defs.md#putbackupvaultlockconfigurationinputrequesttypedef)
- [PutBackupVaultNotificationsInputRequestTypeDef](./type_defs.md#putbackupvaultnotificationsinputrequesttypedef)
- [RecoveryPointByBackupVaultTypeDef](./type_defs.md#recoverypointbybackupvaulttypedef)
- [RecoveryPointByResourceTypeDef](./type_defs.md#recoverypointbyresourcetypedef)
- [RecoveryPointCreatorTypeDef](./type_defs.md#recoverypointcreatortypedef)
- [ReportDeliveryChannelTypeDef](./type_defs.md#reportdeliverychanneltypedef)
- [ReportDestinationTypeDef](./type_defs.md#reportdestinationtypedef)
- [ReportJobTypeDef](./type_defs.md#reportjobtypedef)
- [ReportPlanTypeDef](./type_defs.md#reportplantypedef)
- [ReportSettingTypeDef](./type_defs.md#reportsettingtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RestoreJobsListMemberTypeDef](./type_defs.md#restorejobslistmembertypedef)
- [StartBackupJobInputRequestTypeDef](./type_defs.md#startbackupjobinputrequesttypedef)
- [StartBackupJobOutputTypeDef](./type_defs.md#startbackupjoboutputtypedef)
- [StartCopyJobInputRequestTypeDef](./type_defs.md#startcopyjobinputrequesttypedef)
- [StartCopyJobOutputTypeDef](./type_defs.md#startcopyjoboutputtypedef)
- [StartReportJobInputRequestTypeDef](./type_defs.md#startreportjobinputrequesttypedef)
- [StartReportJobOutputTypeDef](./type_defs.md#startreportjoboutputtypedef)
- [StartRestoreJobInputRequestTypeDef](./type_defs.md#startrestorejobinputrequesttypedef)
- [StartRestoreJobOutputTypeDef](./type_defs.md#startrestorejoboutputtypedef)
- [StopBackupJobInputRequestTypeDef](./type_defs.md#stopbackupjobinputrequesttypedef)
- [TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef)
- [UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef)
- [UpdateBackupPlanInputRequestTypeDef](./type_defs.md#updatebackupplaninputrequesttypedef)
- [UpdateBackupPlanOutputTypeDef](./type_defs.md#updatebackupplanoutputtypedef)
- [UpdateFrameworkInputRequestTypeDef](./type_defs.md#updateframeworkinputrequesttypedef)
- [UpdateFrameworkOutputTypeDef](./type_defs.md#updateframeworkoutputtypedef)
- [UpdateGlobalSettingsInputRequestTypeDef](./type_defs.md#updateglobalsettingsinputrequesttypedef)
- [UpdateRecoveryPointLifecycleInputRequestTypeDef](./type_defs.md#updaterecoverypointlifecycleinputrequesttypedef)
- [UpdateRecoveryPointLifecycleOutputTypeDef](./type_defs.md#updaterecoverypointlifecycleoutputtypedef)
- [UpdateRegionSettingsInputRequestTypeDef](./type_defs.md#updateregionsettingsinputrequesttypedef)
- [UpdateReportPlanInputRequestTypeDef](./type_defs.md#updatereportplaninputrequesttypedef)
- [UpdateReportPlanOutputTypeDef](./type_defs.md#updatereportplanoutputtypedef)

