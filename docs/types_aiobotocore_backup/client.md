<a id="backupclient-for-aiobotocore-backup-module"></a>

# BackupClient for aiobotocore Backup module

> [Index](../README.md) > [Backup](./README.md) > BackupClient

Auto-generated documentation for
[Backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
type annotations stubs module
[types-aiobotocore-backup](https://pypi.org/project/types-aiobotocore-backup/).

- [BackupClient for aiobotocore Backup module](#backupclient-for-aiobotocore-backup-module)
  - [BackupClient](#backupclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_backup_plan](#create_backup_plan)
    - [create_backup_selection](#create_backup_selection)
    - [create_backup_vault](#create_backup_vault)
    - [create_framework](#create_framework)
    - [create_report_plan](#create_report_plan)
    - [delete_backup_plan](#delete_backup_plan)
    - [delete_backup_selection](#delete_backup_selection)
    - [delete_backup_vault](#delete_backup_vault)
    - [delete_backup_vault_access_policy](#delete_backup_vault_access_policy)
    - [delete_backup_vault_lock_configuration](#delete_backup_vault_lock_configuration)
    - [delete_backup_vault_notifications](#delete_backup_vault_notifications)
    - [delete_framework](#delete_framework)
    - [delete_recovery_point](#delete_recovery_point)
    - [delete_report_plan](#delete_report_plan)
    - [describe_backup_job](#describe_backup_job)
    - [describe_backup_vault](#describe_backup_vault)
    - [describe_copy_job](#describe_copy_job)
    - [describe_framework](#describe_framework)
    - [describe_global_settings](#describe_global_settings)
    - [describe_protected_resource](#describe_protected_resource)
    - [describe_recovery_point](#describe_recovery_point)
    - [describe_region_settings](#describe_region_settings)
    - [describe_report_job](#describe_report_job)
    - [describe_report_plan](#describe_report_plan)
    - [describe_restore_job](#describe_restore_job)
    - [disassociate_recovery_point](#disassociate_recovery_point)
    - [export_backup_plan_template](#export_backup_plan_template)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_backup_plan](#get_backup_plan)
    - [get_backup_plan_from_json](#get_backup_plan_from_json)
    - [get_backup_plan_from_template](#get_backup_plan_from_template)
    - [get_backup_selection](#get_backup_selection)
    - [get_backup_vault_access_policy](#get_backup_vault_access_policy)
    - [get_backup_vault_notifications](#get_backup_vault_notifications)
    - [get_recovery_point_restore_metadata](#get_recovery_point_restore_metadata)
    - [get_supported_resource_types](#get_supported_resource_types)
    - [list_backup_jobs](#list_backup_jobs)
    - [list_backup_plan_templates](#list_backup_plan_templates)
    - [list_backup_plan_versions](#list_backup_plan_versions)
    - [list_backup_plans](#list_backup_plans)
    - [list_backup_selections](#list_backup_selections)
    - [list_backup_vaults](#list_backup_vaults)
    - [list_copy_jobs](#list_copy_jobs)
    - [list_frameworks](#list_frameworks)
    - [list_protected_resources](#list_protected_resources)
    - [list_recovery_points_by_backup_vault](#list_recovery_points_by_backup_vault)
    - [list_recovery_points_by_resource](#list_recovery_points_by_resource)
    - [list_report_jobs](#list_report_jobs)
    - [list_report_plans](#list_report_plans)
    - [list_restore_jobs](#list_restore_jobs)
    - [list_tags](#list_tags)
    - [put_backup_vault_access_policy](#put_backup_vault_access_policy)
    - [put_backup_vault_lock_configuration](#put_backup_vault_lock_configuration)
    - [put_backup_vault_notifications](#put_backup_vault_notifications)
    - [start_backup_job](#start_backup_job)
    - [start_copy_job](#start_copy_job)
    - [start_report_job](#start_report_job)
    - [start_restore_job](#start_restore_job)
    - [stop_backup_job](#stop_backup_job)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_backup_plan](#update_backup_plan)
    - [update_framework](#update_framework)
    - [update_global_settings](#update_global_settings)
    - [update_recovery_point_lifecycle](#update_recovery_point_lifecycle)
    - [update_region_settings](#update_region_settings)
    - [update_report_plan](#update_report_plan)
    - [\_\_aenter\_\_](#__aenter__)
    - [\_\_aexit\_\_](#__aexit__)

<a id="backupclient"></a>

## BackupClient

Type annotations for `session.create_client("backup")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_backup.client import BackupClient

session = get_session()
async with session.create_client("backup") as client:
    client: BackupClient
```

Boto3 documentation:
[Backup.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_backup.client import Exceptions

def handle_error(exc: Exceptions.AlreadyExistsException) -> None:
    ...
```

Exceptions:

- `Exceptions.AlreadyExistsException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.DependencyFailureException`
- `Exceptions.InvalidParameterValueException`
- `Exceptions.InvalidRequestException`
- `Exceptions.InvalidResourceStateException`
- `Exceptions.LimitExceededException`
- `Exceptions.MissingParameterValueException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ServiceUnavailableException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

BackupClient exceptions.

Type annotations for `session.create_client("backup").exceptions` method.

Boto3 documentation:
[Backup.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can\_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("backup").can_paginate` method.

Boto3 documentation:
[Backup.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create\_backup\_plan"></a>

### create_backup_plan

Creates a backup plan using a backup plan name and backup rules.

Type annotations for `session.create_client("backup").create_backup_plan`
method.

Boto3 documentation:
[Backup.Client.create_backup_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.create_backup_plan)

Asynchronous method. Use `await create_backup_plan(...)` for a synchronous
call.

Arguments mapping described in
[CreateBackupPlanInputRequestTypeDef](./type_defs.md#createbackupplaninputrequesttypedef).

Keyword-only arguments:

- `BackupPlan`: [BackupPlanInputTypeDef](./type_defs.md#backupplaninputtypedef)
  *(required)*
- `BackupPlanTags`: `Mapping`\[`str`, `str`\]
- `CreatorRequestId`: `str`

Returns a `Coroutine` for
[CreateBackupPlanOutputTypeDef](./type_defs.md#createbackupplanoutputtypedef).

<a id="create\_backup\_selection"></a>

### create_backup_selection

.

Type annotations for `session.create_client("backup").create_backup_selection`
method.

Boto3 documentation:
[Backup.Client.create_backup_selection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.create_backup_selection)

Asynchronous method. Use `await create_backup_selection(...)` for a synchronous
call.

Arguments mapping described in
[CreateBackupSelectionInputRequestTypeDef](./type_defs.md#createbackupselectioninputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*
- `BackupSelection`:
  [BackupSelectionTypeDef](./type_defs.md#backupselectiontypedef) *(required)*
- `CreatorRequestId`: `str`

Returns a `Coroutine` for
[CreateBackupSelectionOutputTypeDef](./type_defs.md#createbackupselectionoutputtypedef).

<a id="create\_backup\_vault"></a>

### create_backup_vault

Creates a logical container where backups are stored.

Type annotations for `session.create_client("backup").create_backup_vault`
method.

Boto3 documentation:
[Backup.Client.create_backup_vault](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.create_backup_vault)

Asynchronous method. Use `await create_backup_vault(...)` for a synchronous
call.

Arguments mapping described in
[CreateBackupVaultInputRequestTypeDef](./type_defs.md#createbackupvaultinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `BackupVaultTags`: `Mapping`\[`str`, `str`\]
- `EncryptionKeyArn`: `str`
- `CreatorRequestId`: `str`

Returns a `Coroutine` for
[CreateBackupVaultOutputTypeDef](./type_defs.md#createbackupvaultoutputtypedef).

<a id="create\_framework"></a>

### create_framework

Creates a framework with one or more controls.

Type annotations for `session.create_client("backup").create_framework` method.

Boto3 documentation:
[Backup.Client.create_framework](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.create_framework)

Asynchronous method. Use `await create_framework(...)` for a synchronous call.

Arguments mapping described in
[CreateFrameworkInputRequestTypeDef](./type_defs.md#createframeworkinputrequesttypedef).

Keyword-only arguments:

- `FrameworkName`: `str` *(required)*
- `FrameworkControls`:
  `Sequence`\[[FrameworkControlTypeDef](./type_defs.md#frameworkcontroltypedef)\]
  *(required)*
- `FrameworkDescription`: `str`
- `IdempotencyToken`: `str`
- `FrameworkTags`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateFrameworkOutputTypeDef](./type_defs.md#createframeworkoutputtypedef).

<a id="create\_report\_plan"></a>

### create_report_plan

Creates a report plan.

Type annotations for `session.create_client("backup").create_report_plan`
method.

Boto3 documentation:
[Backup.Client.create_report_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.create_report_plan)

Asynchronous method. Use `await create_report_plan(...)` for a synchronous
call.

Arguments mapping described in
[CreateReportPlanInputRequestTypeDef](./type_defs.md#createreportplaninputrequesttypedef).

Keyword-only arguments:

- `ReportPlanName`: `str` *(required)*
- `ReportDeliveryChannel`:
  [ReportDeliveryChannelTypeDef](./type_defs.md#reportdeliverychanneltypedef)
  *(required)*
- `ReportSetting`: [ReportSettingTypeDef](./type_defs.md#reportsettingtypedef)
  *(required)*
- `ReportPlanDescription`: `str`
- `ReportPlanTags`: `Mapping`\[`str`, `str`\]
- `IdempotencyToken`: `str`

Returns a `Coroutine` for
[CreateReportPlanOutputTypeDef](./type_defs.md#createreportplanoutputtypedef).

<a id="delete\_backup\_plan"></a>

### delete_backup_plan

Deletes a backup plan.

Type annotations for `session.create_client("backup").delete_backup_plan`
method.

Boto3 documentation:
[Backup.Client.delete_backup_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_plan)

Asynchronous method. Use `await delete_backup_plan(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBackupPlanInputRequestTypeDef](./type_defs.md#deletebackupplaninputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*

Returns a `Coroutine` for
[DeleteBackupPlanOutputTypeDef](./type_defs.md#deletebackupplanoutputtypedef).

<a id="delete\_backup\_selection"></a>

### delete_backup_selection

Deletes the resource selection associated with a backup plan that is specified
by the `SelectionId` .

Type annotations for `session.create_client("backup").delete_backup_selection`
method.

Boto3 documentation:
[Backup.Client.delete_backup_selection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_selection)

Asynchronous method. Use `await delete_backup_selection(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBackupSelectionInputRequestTypeDef](./type_defs.md#deletebackupselectioninputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*
- `SelectionId`: `str` *(required)*

<a id="delete\_backup\_vault"></a>

### delete_backup_vault

Deletes the backup vault identified by its name.

Type annotations for `session.create_client("backup").delete_backup_vault`
method.

Boto3 documentation:
[Backup.Client.delete_backup_vault](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_vault)

Asynchronous method. Use `await delete_backup_vault(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBackupVaultInputRequestTypeDef](./type_defs.md#deletebackupvaultinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*

<a id="delete\_backup\_vault\_access\_policy"></a>

### delete_backup_vault_access_policy

Deletes the policy document that manages permissions on a backup vault.

Type annotations for
`session.create_client("backup").delete_backup_vault_access_policy` method.

Boto3 documentation:
[Backup.Client.delete_backup_vault_access_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_vault_access_policy)

Asynchronous method. Use `await delete_backup_vault_access_policy(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBackupVaultAccessPolicyInputRequestTypeDef](./type_defs.md#deletebackupvaultaccesspolicyinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*

<a id="delete\_backup\_vault\_lock\_configuration"></a>

### delete_backup_vault_lock_configuration

Deletes Backup Vault Lock from a backup vault specified by a backup vault name.

Type annotations for
`session.create_client("backup").delete_backup_vault_lock_configuration`
method.

Boto3 documentation:
[Backup.Client.delete_backup_vault_lock_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_vault_lock_configuration)

Asynchronous method. Use `await delete_backup_vault_lock_configuration(...)`
for a synchronous call.

Arguments mapping described in
[DeleteBackupVaultLockConfigurationInputRequestTypeDef](./type_defs.md#deletebackupvaultlockconfigurationinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*

<a id="delete\_backup\_vault\_notifications"></a>

### delete_backup_vault_notifications

Deletes event notifications for the specified backup vault.

Type annotations for
`session.create_client("backup").delete_backup_vault_notifications` method.

Boto3 documentation:
[Backup.Client.delete_backup_vault_notifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_vault_notifications)

Asynchronous method. Use `await delete_backup_vault_notifications(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBackupVaultNotificationsInputRequestTypeDef](./type_defs.md#deletebackupvaultnotificationsinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*

<a id="delete\_framework"></a>

### delete_framework

Deletes the framework specified by a framework name.

Type annotations for `session.create_client("backup").delete_framework` method.

Boto3 documentation:
[Backup.Client.delete_framework](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_framework)

Asynchronous method. Use `await delete_framework(...)` for a synchronous call.

Arguments mapping described in
[DeleteFrameworkInputRequestTypeDef](./type_defs.md#deleteframeworkinputrequesttypedef).

Keyword-only arguments:

- `FrameworkName`: `str` *(required)*

<a id="delete\_recovery\_point"></a>

### delete_recovery_point

Deletes the recovery point specified by a recovery point ID.

Type annotations for `session.create_client("backup").delete_recovery_point`
method.

Boto3 documentation:
[Backup.Client.delete_recovery_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_recovery_point)

Asynchronous method. Use `await delete_recovery_point(...)` for a synchronous
call.

Arguments mapping described in
[DeleteRecoveryPointInputRequestTypeDef](./type_defs.md#deleterecoverypointinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `RecoveryPointArn`: `str` *(required)*

<a id="delete\_report\_plan"></a>

### delete_report_plan

Deletes the report plan specified by a report plan name.

Type annotations for `session.create_client("backup").delete_report_plan`
method.

Boto3 documentation:
[Backup.Client.delete_report_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_report_plan)

Asynchronous method. Use `await delete_report_plan(...)` for a synchronous
call.

Arguments mapping described in
[DeleteReportPlanInputRequestTypeDef](./type_defs.md#deletereportplaninputrequesttypedef).

Keyword-only arguments:

- `ReportPlanName`: `str` *(required)*

<a id="describe\_backup\_job"></a>

### describe_backup_job

Returns backup job details for the specified `BackupJobId` .

Type annotations for `session.create_client("backup").describe_backup_job`
method.

Boto3 documentation:
[Backup.Client.describe_backup_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_backup_job)

Asynchronous method. Use `await describe_backup_job(...)` for a synchronous
call.

Arguments mapping described in
[DescribeBackupJobInputRequestTypeDef](./type_defs.md#describebackupjobinputrequesttypedef).

Keyword-only arguments:

- `BackupJobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeBackupJobOutputTypeDef](./type_defs.md#describebackupjoboutputtypedef).

<a id="describe\_backup\_vault"></a>

### describe_backup_vault

Returns metadata about a backup vault specified by its name.

Type annotations for `session.create_client("backup").describe_backup_vault`
method.

Boto3 documentation:
[Backup.Client.describe_backup_vault](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_backup_vault)

Asynchronous method. Use `await describe_backup_vault(...)` for a synchronous
call.

Arguments mapping described in
[DescribeBackupVaultInputRequestTypeDef](./type_defs.md#describebackupvaultinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeBackupVaultOutputTypeDef](./type_defs.md#describebackupvaultoutputtypedef).

<a id="describe\_copy\_job"></a>

### describe_copy_job

Returns metadata associated with creating a copy of a resource.

Type annotations for `session.create_client("backup").describe_copy_job`
method.

Boto3 documentation:
[Backup.Client.describe_copy_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_copy_job)

Asynchronous method. Use `await describe_copy_job(...)` for a synchronous call.

Arguments mapping described in
[DescribeCopyJobInputRequestTypeDef](./type_defs.md#describecopyjobinputrequesttypedef).

Keyword-only arguments:

- `CopyJobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeCopyJobOutputTypeDef](./type_defs.md#describecopyjoboutputtypedef).

<a id="describe\_framework"></a>

### describe_framework

Returns the framework details for the specified `FrameworkName` .

Type annotations for `session.create_client("backup").describe_framework`
method.

Boto3 documentation:
[Backup.Client.describe_framework](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_framework)

Asynchronous method. Use `await describe_framework(...)` for a synchronous
call.

Arguments mapping described in
[DescribeFrameworkInputRequestTypeDef](./type_defs.md#describeframeworkinputrequesttypedef).

Keyword-only arguments:

- `FrameworkName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeFrameworkOutputTypeDef](./type_defs.md#describeframeworkoutputtypedef).

<a id="describe\_global\_settings"></a>

### describe_global_settings

Describes whether the Amazon Web Services account is opted in to cross-account
backup.

Type annotations for `session.create_client("backup").describe_global_settings`
method.

Boto3 documentation:
[Backup.Client.describe_global_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_global_settings)

Asynchronous method. Use `await describe_global_settings(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeGlobalSettingsOutputTypeDef](./type_defs.md#describeglobalsettingsoutputtypedef).

<a id="describe\_protected\_resource"></a>

### describe_protected_resource

Returns information about a saved resource, including the last time it was
backed up, its Amazon Resource Name (ARN), and the Amazon Web Services service
type of the saved resource.

Type annotations for
`session.create_client("backup").describe_protected_resource` method.

Boto3 documentation:
[Backup.Client.describe_protected_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_protected_resource)

Asynchronous method. Use `await describe_protected_resource(...)` for a
synchronous call.

Arguments mapping described in
[DescribeProtectedResourceInputRequestTypeDef](./type_defs.md#describeprotectedresourceinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeProtectedResourceOutputTypeDef](./type_defs.md#describeprotectedresourceoutputtypedef).

<a id="describe\_recovery\_point"></a>

### describe_recovery_point

Returns metadata associated with a recovery point, including ID, status,
encryption, and lifecycle.

Type annotations for `session.create_client("backup").describe_recovery_point`
method.

Boto3 documentation:
[Backup.Client.describe_recovery_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_recovery_point)

Asynchronous method. Use `await describe_recovery_point(...)` for a synchronous
call.

Arguments mapping described in
[DescribeRecoveryPointInputRequestTypeDef](./type_defs.md#describerecoverypointinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `RecoveryPointArn`: `str` *(required)*

Returns a `Coroutine` for
[DescribeRecoveryPointOutputTypeDef](./type_defs.md#describerecoverypointoutputtypedef).

<a id="describe\_region\_settings"></a>

### describe_region_settings

Returns the current service opt-in settings for the Region.

Type annotations for `session.create_client("backup").describe_region_settings`
method.

Boto3 documentation:
[Backup.Client.describe_region_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_region_settings)

Asynchronous method. Use `await describe_region_settings(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeRegionSettingsOutputTypeDef](./type_defs.md#describeregionsettingsoutputtypedef).

<a id="describe\_report\_job"></a>

### describe_report_job

Returns the details associated with creating a report as specified by its
`ReportJobId` .

Type annotations for `session.create_client("backup").describe_report_job`
method.

Boto3 documentation:
[Backup.Client.describe_report_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_report_job)

Asynchronous method. Use `await describe_report_job(...)` for a synchronous
call.

Arguments mapping described in
[DescribeReportJobInputRequestTypeDef](./type_defs.md#describereportjobinputrequesttypedef).

Keyword-only arguments:

- `ReportJobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeReportJobOutputTypeDef](./type_defs.md#describereportjoboutputtypedef).

<a id="describe\_report\_plan"></a>

### describe_report_plan

Returns a list of all report plans for an Amazon Web Services account and
Amazon Web Services Region.

Type annotations for `session.create_client("backup").describe_report_plan`
method.

Boto3 documentation:
[Backup.Client.describe_report_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_report_plan)

Asynchronous method. Use `await describe_report_plan(...)` for a synchronous
call.

Arguments mapping described in
[DescribeReportPlanInputRequestTypeDef](./type_defs.md#describereportplaninputrequesttypedef).

Keyword-only arguments:

- `ReportPlanName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeReportPlanOutputTypeDef](./type_defs.md#describereportplanoutputtypedef).

<a id="describe\_restore\_job"></a>

### describe_restore_job

Returns metadata associated with a restore job that is specified by a job ID.

Type annotations for `session.create_client("backup").describe_restore_job`
method.

Boto3 documentation:
[Backup.Client.describe_restore_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_restore_job)

Asynchronous method. Use `await describe_restore_job(...)` for a synchronous
call.

Arguments mapping described in
[DescribeRestoreJobInputRequestTypeDef](./type_defs.md#describerestorejobinputrequesttypedef).

Keyword-only arguments:

- `RestoreJobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeRestoreJobOutputTypeDef](./type_defs.md#describerestorejoboutputtypedef).

<a id="disassociate\_recovery\_point"></a>

### disassociate_recovery_point

Deletes the specified continuous backup recovery point from Backup and releases
control of that continuous backup to the source service, such as Amazon RDS.

Type annotations for
`session.create_client("backup").disassociate_recovery_point` method.

Boto3 documentation:
[Backup.Client.disassociate_recovery_point](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.disassociate_recovery_point)

Asynchronous method. Use `await disassociate_recovery_point(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateRecoveryPointInputRequestTypeDef](./type_defs.md#disassociaterecoverypointinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `RecoveryPointArn`: `str` *(required)*

<a id="export\_backup\_plan\_template"></a>

### export_backup_plan_template

Returns the backup plan that is specified by the plan ID as a backup template.

Type annotations for
`session.create_client("backup").export_backup_plan_template` method.

Boto3 documentation:
[Backup.Client.export_backup_plan_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.export_backup_plan_template)

Asynchronous method. Use `await export_backup_plan_template(...)` for a
synchronous call.

Arguments mapping described in
[ExportBackupPlanTemplateInputRequestTypeDef](./type_defs.md#exportbackupplantemplateinputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*

Returns a `Coroutine` for
[ExportBackupPlanTemplateOutputTypeDef](./type_defs.md#exportbackupplantemplateoutputtypedef).

<a id="generate\_presigned\_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `session.create_client("backup").generate_presigned_url`
method.

Boto3 documentation:
[Backup.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get\_backup\_plan"></a>

### get_backup_plan

Returns `BackupPlan` details for the specified `BackupPlanId`.

Type annotations for `session.create_client("backup").get_backup_plan` method.

Boto3 documentation:
[Backup.Client.get_backup_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_backup_plan)

Asynchronous method. Use `await get_backup_plan(...)` for a synchronous call.

Arguments mapping described in
[GetBackupPlanInputRequestTypeDef](./type_defs.md#getbackupplaninputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*
- `VersionId`: `str`

Returns a `Coroutine` for
[GetBackupPlanOutputTypeDef](./type_defs.md#getbackupplanoutputtypedef).

<a id="get\_backup\_plan\_from\_json"></a>

### get_backup_plan_from_json

Returns a valid JSON document specifying a backup plan or an error.

Type annotations for
`session.create_client("backup").get_backup_plan_from_json` method.

Boto3 documentation:
[Backup.Client.get_backup_plan_from_json](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_backup_plan_from_json)

Asynchronous method. Use `await get_backup_plan_from_json(...)` for a
synchronous call.

Arguments mapping described in
[GetBackupPlanFromJSONInputRequestTypeDef](./type_defs.md#getbackupplanfromjsoninputrequesttypedef).

Keyword-only arguments:

- `BackupPlanTemplateJson`: `str` *(required)*

Returns a `Coroutine` for
[GetBackupPlanFromJSONOutputTypeDef](./type_defs.md#getbackupplanfromjsonoutputtypedef).

<a id="get\_backup\_plan\_from\_template"></a>

### get_backup_plan_from_template

Returns the template specified by its `templateId` as a backup plan.

Type annotations for
`session.create_client("backup").get_backup_plan_from_template` method.

Boto3 documentation:
[Backup.Client.get_backup_plan_from_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_backup_plan_from_template)

Asynchronous method. Use `await get_backup_plan_from_template(...)` for a
synchronous call.

Arguments mapping described in
[GetBackupPlanFromTemplateInputRequestTypeDef](./type_defs.md#getbackupplanfromtemplateinputrequesttypedef).

Keyword-only arguments:

- `BackupPlanTemplateId`: `str` *(required)*

Returns a `Coroutine` for
[GetBackupPlanFromTemplateOutputTypeDef](./type_defs.md#getbackupplanfromtemplateoutputtypedef).

<a id="get\_backup\_selection"></a>

### get_backup_selection

.

Type annotations for `session.create_client("backup").get_backup_selection`
method.

Boto3 documentation:
[Backup.Client.get_backup_selection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_backup_selection)

Asynchronous method. Use `await get_backup_selection(...)` for a synchronous
call.

Arguments mapping described in
[GetBackupSelectionInputRequestTypeDef](./type_defs.md#getbackupselectioninputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*
- `SelectionId`: `str` *(required)*

Returns a `Coroutine` for
[GetBackupSelectionOutputTypeDef](./type_defs.md#getbackupselectionoutputtypedef).

<a id="get\_backup\_vault\_access\_policy"></a>

### get_backup_vault_access_policy

Returns the access policy document that is associated with the named backup
vault.

Type annotations for
`session.create_client("backup").get_backup_vault_access_policy` method.

Boto3 documentation:
[Backup.Client.get_backup_vault_access_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_backup_vault_access_policy)

Asynchronous method. Use `await get_backup_vault_access_policy(...)` for a
synchronous call.

Arguments mapping described in
[GetBackupVaultAccessPolicyInputRequestTypeDef](./type_defs.md#getbackupvaultaccesspolicyinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*

Returns a `Coroutine` for
[GetBackupVaultAccessPolicyOutputTypeDef](./type_defs.md#getbackupvaultaccesspolicyoutputtypedef).

<a id="get\_backup\_vault\_notifications"></a>

### get_backup_vault_notifications

Returns event notifications for the specified backup vault.

Type annotations for
`session.create_client("backup").get_backup_vault_notifications` method.

Boto3 documentation:
[Backup.Client.get_backup_vault_notifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_backup_vault_notifications)

Asynchronous method. Use `await get_backup_vault_notifications(...)` for a
synchronous call.

Arguments mapping described in
[GetBackupVaultNotificationsInputRequestTypeDef](./type_defs.md#getbackupvaultnotificationsinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*

Returns a `Coroutine` for
[GetBackupVaultNotificationsOutputTypeDef](./type_defs.md#getbackupvaultnotificationsoutputtypedef).

<a id="get\_recovery\_point\_restore\_metadata"></a>

### get_recovery_point_restore_metadata

Returns a set of metadata key-value pairs that were used to create the backup.

Type annotations for
`session.create_client("backup").get_recovery_point_restore_metadata` method.

Boto3 documentation:
[Backup.Client.get_recovery_point_restore_metadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_recovery_point_restore_metadata)

Asynchronous method. Use `await get_recovery_point_restore_metadata(...)` for a
synchronous call.

Arguments mapping described in
[GetRecoveryPointRestoreMetadataInputRequestTypeDef](./type_defs.md#getrecoverypointrestoremetadatainputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `RecoveryPointArn`: `str` *(required)*

Returns a `Coroutine` for
[GetRecoveryPointRestoreMetadataOutputTypeDef](./type_defs.md#getrecoverypointrestoremetadataoutputtypedef).

<a id="get\_supported\_resource\_types"></a>

### get_supported_resource_types

Returns the Amazon Web Services resource types supported by Backup.

Type annotations for
`session.create_client("backup").get_supported_resource_types` method.

Boto3 documentation:
[Backup.Client.get_supported_resource_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.get_supported_resource_types)

Asynchronous method. Use `await get_supported_resource_types(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetSupportedResourceTypesOutputTypeDef](./type_defs.md#getsupportedresourcetypesoutputtypedef).

<a id="list\_backup\_jobs"></a>

### list_backup_jobs

Returns a list of existing backup jobs for an authenticated account for the
last 30 days.

Type annotations for `session.create_client("backup").list_backup_jobs` method.

Boto3 documentation:
[Backup.Client.list_backup_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_backup_jobs)

Asynchronous method. Use `await list_backup_jobs(...)` for a synchronous call.

Arguments mapping described in
[ListBackupJobsInputRequestTypeDef](./type_defs.md#listbackupjobsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `ByResourceArn`: `str`
- `ByState`: [BackupJobStateType](./literals.md#backupjobstatetype)
- `ByBackupVaultName`: `str`
- `ByCreatedBefore`: `Union`\[`datetime`, `str`\]
- `ByCreatedAfter`: `Union`\[`datetime`, `str`\]
- `ByResourceType`: `str`
- `ByAccountId`: `str`

Returns a `Coroutine` for
[ListBackupJobsOutputTypeDef](./type_defs.md#listbackupjobsoutputtypedef).

<a id="list\_backup\_plan\_templates"></a>

### list_backup_plan_templates

Returns metadata of your saved backup plan templates, including the template
ID, name, and the creation and deletion dates.

Type annotations for
`session.create_client("backup").list_backup_plan_templates` method.

Boto3 documentation:
[Backup.Client.list_backup_plan_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_backup_plan_templates)

Asynchronous method. Use `await list_backup_plan_templates(...)` for a
synchronous call.

Arguments mapping described in
[ListBackupPlanTemplatesInputRequestTypeDef](./type_defs.md#listbackupplantemplatesinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListBackupPlanTemplatesOutputTypeDef](./type_defs.md#listbackupplantemplatesoutputtypedef).

<a id="list\_backup\_plan\_versions"></a>

### list_backup_plan_versions

Returns version metadata of your backup plans, including Amazon Resource Names
(ARNs), backup plan IDs, creation and deletion dates, plan names, and version
IDs.

Type annotations for
`session.create_client("backup").list_backup_plan_versions` method.

Boto3 documentation:
[Backup.Client.list_backup_plan_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_backup_plan_versions)

Asynchronous method. Use `await list_backup_plan_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListBackupPlanVersionsInputRequestTypeDef](./type_defs.md#listbackupplanversionsinputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListBackupPlanVersionsOutputTypeDef](./type_defs.md#listbackupplanversionsoutputtypedef).

<a id="list\_backup\_plans"></a>

### list_backup_plans

Returns a list of all active backup plans for an authenticated account.

Type annotations for `session.create_client("backup").list_backup_plans`
method.

Boto3 documentation:
[Backup.Client.list_backup_plans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_backup_plans)

Asynchronous method. Use `await list_backup_plans(...)` for a synchronous call.

Arguments mapping described in
[ListBackupPlansInputRequestTypeDef](./type_defs.md#listbackupplansinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `IncludeDeleted`: `bool`

Returns a `Coroutine` for
[ListBackupPlansOutputTypeDef](./type_defs.md#listbackupplansoutputtypedef).

<a id="list\_backup\_selections"></a>

### list_backup_selections

Returns an array containing metadata of the resources associated with the
target backup plan.

Type annotations for `session.create_client("backup").list_backup_selections`
method.

Boto3 documentation:
[Backup.Client.list_backup_selections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_backup_selections)

Asynchronous method. Use `await list_backup_selections(...)` for a synchronous
call.

Arguments mapping described in
[ListBackupSelectionsInputRequestTypeDef](./type_defs.md#listbackupselectionsinputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListBackupSelectionsOutputTypeDef](./type_defs.md#listbackupselectionsoutputtypedef).

<a id="list\_backup\_vaults"></a>

### list_backup_vaults

Returns a list of recovery point storage containers along with information
about them.

Type annotations for `session.create_client("backup").list_backup_vaults`
method.

Boto3 documentation:
[Backup.Client.list_backup_vaults](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_backup_vaults)

Asynchronous method. Use `await list_backup_vaults(...)` for a synchronous
call.

Arguments mapping described in
[ListBackupVaultsInputRequestTypeDef](./type_defs.md#listbackupvaultsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListBackupVaultsOutputTypeDef](./type_defs.md#listbackupvaultsoutputtypedef).

<a id="list\_copy\_jobs"></a>

### list_copy_jobs

Returns metadata about your copy jobs.

Type annotations for `session.create_client("backup").list_copy_jobs` method.

Boto3 documentation:
[Backup.Client.list_copy_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_copy_jobs)

Asynchronous method. Use `await list_copy_jobs(...)` for a synchronous call.

Arguments mapping described in
[ListCopyJobsInputRequestTypeDef](./type_defs.md#listcopyjobsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `ByResourceArn`: `str`
- `ByState`: [CopyJobStateType](./literals.md#copyjobstatetype)
- `ByCreatedBefore`: `Union`\[`datetime`, `str`\]
- `ByCreatedAfter`: `Union`\[`datetime`, `str`\]
- `ByResourceType`: `str`
- `ByDestinationVaultArn`: `str`
- `ByAccountId`: `str`

Returns a `Coroutine` for
[ListCopyJobsOutputTypeDef](./type_defs.md#listcopyjobsoutputtypedef).

<a id="list\_frameworks"></a>

### list_frameworks

Returns a list of all frameworks for an Amazon Web Services account and Amazon
Web Services Region.

Type annotations for `session.create_client("backup").list_frameworks` method.

Boto3 documentation:
[Backup.Client.list_frameworks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_frameworks)

Asynchronous method. Use `await list_frameworks(...)` for a synchronous call.

Arguments mapping described in
[ListFrameworksInputRequestTypeDef](./type_defs.md#listframeworksinputrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListFrameworksOutputTypeDef](./type_defs.md#listframeworksoutputtypedef).

<a id="list\_protected\_resources"></a>

### list_protected_resources

Returns an array of resources successfully backed up by Backup, including the
time the resource was saved, an Amazon Resource Name (ARN) of the resource, and
a resource type.

Type annotations for `session.create_client("backup").list_protected_resources`
method.

Boto3 documentation:
[Backup.Client.list_protected_resources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_protected_resources)

Asynchronous method. Use `await list_protected_resources(...)` for a
synchronous call.

Arguments mapping described in
[ListProtectedResourcesInputRequestTypeDef](./type_defs.md#listprotectedresourcesinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListProtectedResourcesOutputTypeDef](./type_defs.md#listprotectedresourcesoutputtypedef).

<a id="list\_recovery\_points\_by\_backup\_vault"></a>

### list_recovery_points_by_backup_vault

Returns detailed information about the recovery points stored in a backup
vault.

Type annotations for
`session.create_client("backup").list_recovery_points_by_backup_vault` method.

Boto3 documentation:
[Backup.Client.list_recovery_points_by_backup_vault](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_recovery_points_by_backup_vault)

Asynchronous method. Use `await list_recovery_points_by_backup_vault(...)` for
a synchronous call.

Arguments mapping described in
[ListRecoveryPointsByBackupVaultInputRequestTypeDef](./type_defs.md#listrecoverypointsbybackupvaultinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `ByResourceArn`: `str`
- `ByResourceType`: `str`
- `ByBackupPlanId`: `str`
- `ByCreatedBefore`: `Union`\[`datetime`, `str`\]
- `ByCreatedAfter`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[ListRecoveryPointsByBackupVaultOutputTypeDef](./type_defs.md#listrecoverypointsbybackupvaultoutputtypedef).

<a id="list\_recovery\_points\_by\_resource"></a>

### list_recovery_points_by_resource

Returns detailed information about all the recovery points of the type
specified by a resource Amazon Resource Name (ARN).

Type annotations for
`session.create_client("backup").list_recovery_points_by_resource` method.

Boto3 documentation:
[Backup.Client.list_recovery_points_by_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_recovery_points_by_resource)

Asynchronous method. Use `await list_recovery_points_by_resource(...)` for a
synchronous call.

Arguments mapping described in
[ListRecoveryPointsByResourceInputRequestTypeDef](./type_defs.md#listrecoverypointsbyresourceinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListRecoveryPointsByResourceOutputTypeDef](./type_defs.md#listrecoverypointsbyresourceoutputtypedef).

<a id="list\_report\_jobs"></a>

### list_report_jobs

Returns details about your report jobs.

Type annotations for `session.create_client("backup").list_report_jobs` method.

Boto3 documentation:
[Backup.Client.list_report_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_report_jobs)

Asynchronous method. Use `await list_report_jobs(...)` for a synchronous call.

Arguments mapping described in
[ListReportJobsInputRequestTypeDef](./type_defs.md#listreportjobsinputrequesttypedef).

Keyword-only arguments:

- `ByReportPlanName`: `str`
- `ByCreationBefore`: `Union`\[`datetime`, `str`\]
- `ByCreationAfter`: `Union`\[`datetime`, `str`\]
- `ByStatus`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListReportJobsOutputTypeDef](./type_defs.md#listreportjobsoutputtypedef).

<a id="list\_report\_plans"></a>

### list_report_plans

Returns a list of your report plans.

Type annotations for `session.create_client("backup").list_report_plans`
method.

Boto3 documentation:
[Backup.Client.list_report_plans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_report_plans)

Asynchronous method. Use `await list_report_plans(...)` for a synchronous call.

Arguments mapping described in
[ListReportPlansInputRequestTypeDef](./type_defs.md#listreportplansinputrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListReportPlansOutputTypeDef](./type_defs.md#listreportplansoutputtypedef).

<a id="list\_restore\_jobs"></a>

### list_restore_jobs

Returns a list of jobs that Backup initiated to restore a saved resource,
including details about the recovery process.

Type annotations for `session.create_client("backup").list_restore_jobs`
method.

Boto3 documentation:
[Backup.Client.list_restore_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_restore_jobs)

Asynchronous method. Use `await list_restore_jobs(...)` for a synchronous call.

Arguments mapping described in
[ListRestoreJobsInputRequestTypeDef](./type_defs.md#listrestorejobsinputrequesttypedef).

Keyword-only arguments:

- `NextToken`: `str`
- `MaxResults`: `int`
- `ByAccountId`: `str`
- `ByCreatedBefore`: `Union`\[`datetime`, `str`\]
- `ByCreatedAfter`: `Union`\[`datetime`, `str`\]
- `ByStatus`: [RestoreJobStatusType](./literals.md#restorejobstatustype)

Returns a `Coroutine` for
[ListRestoreJobsOutputTypeDef](./type_defs.md#listrestorejobsoutputtypedef).

<a id="list\_tags"></a>

### list_tags

Returns a list of key-value pairs assigned to a target recovery point, backup
plan, or backup vault.

Type annotations for `session.create_client("backup").list_tags` method.

Boto3 documentation:
[Backup.Client.list_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.list_tags)

Asynchronous method. Use `await list_tags(...)` for a synchronous call.

Arguments mapping described in
[ListTagsInputRequestTypeDef](./type_defs.md#listtagsinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListTagsOutputTypeDef](./type_defs.md#listtagsoutputtypedef).

<a id="put\_backup\_vault\_access\_policy"></a>

### put_backup_vault_access_policy

Sets a resource-based policy that is used to manage access permissions on the
target backup vault.

Type annotations for
`session.create_client("backup").put_backup_vault_access_policy` method.

Boto3 documentation:
[Backup.Client.put_backup_vault_access_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.put_backup_vault_access_policy)

Asynchronous method. Use `await put_backup_vault_access_policy(...)` for a
synchronous call.

Arguments mapping described in
[PutBackupVaultAccessPolicyInputRequestTypeDef](./type_defs.md#putbackupvaultaccesspolicyinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `Policy`: `str`

<a id="put\_backup\_vault\_lock\_configuration"></a>

### put_backup_vault_lock_configuration

Applies Backup Vault Lock to a backup vault, preventing attempts to delete any
recovery point stored in or created in a backup vault.

Type annotations for
`session.create_client("backup").put_backup_vault_lock_configuration` method.

Boto3 documentation:
[Backup.Client.put_backup_vault_lock_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.put_backup_vault_lock_configuration)

Asynchronous method. Use `await put_backup_vault_lock_configuration(...)` for a
synchronous call.

Arguments mapping described in
[PutBackupVaultLockConfigurationInputRequestTypeDef](./type_defs.md#putbackupvaultlockconfigurationinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `MinRetentionDays`: `int`
- `MaxRetentionDays`: `int`
- `ChangeableForDays`: `int`

<a id="put\_backup\_vault\_notifications"></a>

### put_backup_vault_notifications

Turns on notifications on a backup vault for the specified topic and events.

Type annotations for
`session.create_client("backup").put_backup_vault_notifications` method.

Boto3 documentation:
[Backup.Client.put_backup_vault_notifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.put_backup_vault_notifications)

Asynchronous method. Use `await put_backup_vault_notifications(...)` for a
synchronous call.

Arguments mapping described in
[PutBackupVaultNotificationsInputRequestTypeDef](./type_defs.md#putbackupvaultnotificationsinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `SNSTopicArn`: `str` *(required)*
- `BackupVaultEvents`:
  `Sequence`\[[BackupVaultEventType](./literals.md#backupvaulteventtype)\]
  *(required)*

<a id="start\_backup\_job"></a>

### start_backup_job

Starts an on-demand backup job for the specified resource.

Type annotations for `session.create_client("backup").start_backup_job` method.

Boto3 documentation:
[Backup.Client.start_backup_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.start_backup_job)

Asynchronous method. Use `await start_backup_job(...)` for a synchronous call.

Arguments mapping described in
[StartBackupJobInputRequestTypeDef](./type_defs.md#startbackupjobinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `ResourceArn`: `str` *(required)*
- `IamRoleArn`: `str` *(required)*
- `IdempotencyToken`: `str`
- `StartWindowMinutes`: `int`
- `CompleteWindowMinutes`: `int`
- `Lifecycle`: [LifecycleTypeDef](./type_defs.md#lifecycletypedef)
- `RecoveryPointTags`: `Mapping`\[`str`, `str`\]
- `BackupOptions`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[StartBackupJobOutputTypeDef](./type_defs.md#startbackupjoboutputtypedef).

<a id="start\_copy\_job"></a>

### start_copy_job

Starts a job to create a one-time copy of the specified resource.

Type annotations for `session.create_client("backup").start_copy_job` method.

Boto3 documentation:
[Backup.Client.start_copy_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.start_copy_job)

Asynchronous method. Use `await start_copy_job(...)` for a synchronous call.

Arguments mapping described in
[StartCopyJobInputRequestTypeDef](./type_defs.md#startcopyjobinputrequesttypedef).

Keyword-only arguments:

- `RecoveryPointArn`: `str` *(required)*
- `SourceBackupVaultName`: `str` *(required)*
- `DestinationBackupVaultArn`: `str` *(required)*
- `IamRoleArn`: `str` *(required)*
- `IdempotencyToken`: `str`
- `Lifecycle`: [LifecycleTypeDef](./type_defs.md#lifecycletypedef)

Returns a `Coroutine` for
[StartCopyJobOutputTypeDef](./type_defs.md#startcopyjoboutputtypedef).

<a id="start\_report\_job"></a>

### start_report_job

Starts an on-demand report job for the specified report plan.

Type annotations for `session.create_client("backup").start_report_job` method.

Boto3 documentation:
[Backup.Client.start_report_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.start_report_job)

Asynchronous method. Use `await start_report_job(...)` for a synchronous call.

Arguments mapping described in
[StartReportJobInputRequestTypeDef](./type_defs.md#startreportjobinputrequesttypedef).

Keyword-only arguments:

- `ReportPlanName`: `str` *(required)*
- `IdempotencyToken`: `str`

Returns a `Coroutine` for
[StartReportJobOutputTypeDef](./type_defs.md#startreportjoboutputtypedef).

<a id="start\_restore\_job"></a>

### start_restore_job

Recovers the saved resource identified by an Amazon Resource Name (ARN).

Type annotations for `session.create_client("backup").start_restore_job`
method.

Boto3 documentation:
[Backup.Client.start_restore_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.start_restore_job)

Asynchronous method. Use `await start_restore_job(...)` for a synchronous call.

Arguments mapping described in
[StartRestoreJobInputRequestTypeDef](./type_defs.md#startrestorejobinputrequesttypedef).

Keyword-only arguments:

- `RecoveryPointArn`: `str` *(required)*
- `Metadata`: `Mapping`\[`str`, `str`\] *(required)*
- `IamRoleArn`: `str` *(required)*
- `IdempotencyToken`: `str`
- `ResourceType`: `str`

Returns a `Coroutine` for
[StartRestoreJobOutputTypeDef](./type_defs.md#startrestorejoboutputtypedef).

<a id="stop\_backup\_job"></a>

### stop_backup_job

Attempts to cancel a job to create a one-time backup of a resource.

Type annotations for `session.create_client("backup").stop_backup_job` method.

Boto3 documentation:
[Backup.Client.stop_backup_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.stop_backup_job)

Asynchronous method. Use `await stop_backup_job(...)` for a synchronous call.

Arguments mapping described in
[StopBackupJobInputRequestTypeDef](./type_defs.md#stopbackupjobinputrequesttypedef).

Keyword-only arguments:

- `BackupJobId`: `str` *(required)*

<a id="tag\_resource"></a>

### tag_resource

Assigns a set of key-value pairs to a recovery point, backup plan, or backup
vault identified by an Amazon Resource Name (ARN).

Type annotations for `session.create_client("backup").tag_resource` method.

Boto3 documentation:
[Backup.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `Tags`: `Mapping`\[`str`, `str`\] *(required)*

<a id="untag\_resource"></a>

### untag_resource

Removes a set of key-value pairs from a recovery point, backup plan, or backup
vault identified by an Amazon Resource Name (ARN) See also:
[AWS API Documentation](https://docs.aws.amazon.com/goto/WebAPI/backup-2018-11-15/UntagResource).

Type annotations for `session.create_client("backup").untag_resource` method.

Boto3 documentation:
[Backup.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef).

Keyword-only arguments:

- `ResourceArn`: `str` *(required)*
- `TagKeyList`: `Sequence`\[`str`\] *(required)*

<a id="update\_backup\_plan"></a>

### update_backup_plan

Updates an existing backup plan identified by its `backupPlanId` with the input
document in JSON format.

Type annotations for `session.create_client("backup").update_backup_plan`
method.

Boto3 documentation:
[Backup.Client.update_backup_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.update_backup_plan)

Asynchronous method. Use `await update_backup_plan(...)` for a synchronous
call.

Arguments mapping described in
[UpdateBackupPlanInputRequestTypeDef](./type_defs.md#updatebackupplaninputrequesttypedef).

Keyword-only arguments:

- `BackupPlanId`: `str` *(required)*
- `BackupPlan`: [BackupPlanInputTypeDef](./type_defs.md#backupplaninputtypedef)
  *(required)*

Returns a `Coroutine` for
[UpdateBackupPlanOutputTypeDef](./type_defs.md#updatebackupplanoutputtypedef).

<a id="update\_framework"></a>

### update_framework

Updates an existing framework identified by its `FrameworkName` with the input
document in JSON format.

Type annotations for `session.create_client("backup").update_framework` method.

Boto3 documentation:
[Backup.Client.update_framework](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.update_framework)

Asynchronous method. Use `await update_framework(...)` for a synchronous call.

Arguments mapping described in
[UpdateFrameworkInputRequestTypeDef](./type_defs.md#updateframeworkinputrequesttypedef).

Keyword-only arguments:

- `FrameworkName`: `str` *(required)*
- `FrameworkDescription`: `str`
- `FrameworkControls`:
  `Sequence`\[[FrameworkControlTypeDef](./type_defs.md#frameworkcontroltypedef)\]
- `IdempotencyToken`: `str`

Returns a `Coroutine` for
[UpdateFrameworkOutputTypeDef](./type_defs.md#updateframeworkoutputtypedef).

<a id="update\_global\_settings"></a>

### update_global_settings

Updates whether the Amazon Web Services account is opted in to cross-account
backup.

Type annotations for `session.create_client("backup").update_global_settings`
method.

Boto3 documentation:
[Backup.Client.update_global_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.update_global_settings)

Asynchronous method. Use `await update_global_settings(...)` for a synchronous
call.

Arguments mapping described in
[UpdateGlobalSettingsInputRequestTypeDef](./type_defs.md#updateglobalsettingsinputrequesttypedef).

Keyword-only arguments:

- `GlobalSettings`: `Mapping`\[`str`, `str`\]

<a id="update\_recovery\_point\_lifecycle"></a>

### update_recovery_point_lifecycle

Sets the transition lifecycle of a recovery point.

Type annotations for
`session.create_client("backup").update_recovery_point_lifecycle` method.

Boto3 documentation:
[Backup.Client.update_recovery_point_lifecycle](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.update_recovery_point_lifecycle)

Asynchronous method. Use `await update_recovery_point_lifecycle(...)` for a
synchronous call.

Arguments mapping described in
[UpdateRecoveryPointLifecycleInputRequestTypeDef](./type_defs.md#updaterecoverypointlifecycleinputrequesttypedef).

Keyword-only arguments:

- `BackupVaultName`: `str` *(required)*
- `RecoveryPointArn`: `str` *(required)*
- `Lifecycle`: [LifecycleTypeDef](./type_defs.md#lifecycletypedef)

Returns a `Coroutine` for
[UpdateRecoveryPointLifecycleOutputTypeDef](./type_defs.md#updaterecoverypointlifecycleoutputtypedef).

<a id="update\_region\_settings"></a>

### update_region_settings

Updates the current service opt-in settings for the Region.

Type annotations for `session.create_client("backup").update_region_settings`
method.

Boto3 documentation:
[Backup.Client.update_region_settings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.update_region_settings)

Asynchronous method. Use `await update_region_settings(...)` for a synchronous
call.

Arguments mapping described in
[UpdateRegionSettingsInputRequestTypeDef](./type_defs.md#updateregionsettingsinputrequesttypedef).

Keyword-only arguments:

- `ResourceTypeOptInPreference`: `Mapping`\[`str`, `bool`\]
- `ResourceTypeManagementPreference`: `Mapping`\[`str`, `bool`\]

<a id="update\_report\_plan"></a>

### update_report_plan

Updates an existing report plan identified by its `ReportPlanName` with the
input document in JSON format.

Type annotations for `session.create_client("backup").update_report_plan`
method.

Boto3 documentation:
[Backup.Client.update_report_plan](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.update_report_plan)

Asynchronous method. Use `await update_report_plan(...)` for a synchronous
call.

Arguments mapping described in
[UpdateReportPlanInputRequestTypeDef](./type_defs.md#updatereportplaninputrequesttypedef).

Keyword-only arguments:

- `ReportPlanName`: `str` *(required)*
- `ReportPlanDescription`: `str`
- `ReportDeliveryChannel`:
  [ReportDeliveryChannelTypeDef](./type_defs.md#reportdeliverychanneltypedef)
- `ReportSetting`: [ReportSettingTypeDef](./type_defs.md#reportsettingtypedef)
- `IdempotencyToken`: `str`

Returns a `Coroutine` for
[UpdateReportPlanOutputTypeDef](./type_defs.md#updatereportplanoutputtypedef).

<a id="\_\_aenter\_\_"></a>

### \_\_aenter\_\_

Type annotations for `session.create_client("backup").__aenter__` method.

Boto3 documentation:
[Backup.Client.\_\_aenter\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for [BackupClient](#backupclient).

<a id="\_\_aexit\_\_"></a>

### \_\_aexit\_\_

Type annotations for `session.create_client("backup").__aexit__` method.

Boto3 documentation:
[Backup.Client.\_\_aexit\_\_](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.
