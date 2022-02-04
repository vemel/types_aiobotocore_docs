<a id="fsxclient-for-aiobotocore-fsx-module"></a>

# FSxClient for aiobotocore FSx module

> [Index](..) > [FSx](.) > FSxClient

Auto-generated documentation for
[FSx](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
type annotations stubs module
[types-aiobotocore-fsx](https://pypi.org/project/types-aiobotocore-fsx/).

- [FSxClient for aiobotocore FSx module](#fsxclient-for-aiobotocore-fsx-module)
  - [FSxClient](#fsxclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [associate_file_system_aliases](#associate_file_system_aliases)
    - [can_paginate](#can_paginate)
    - [cancel_data_repository_task](#cancel_data_repository_task)
    - [copy_backup](#copy_backup)
    - [create_backup](#create_backup)
    - [create_data_repository_association](#create_data_repository_association)
    - [create_data_repository_task](#create_data_repository_task)
    - [create_file_system](#create_file_system)
    - [create_file_system_from_backup](#create_file_system_from_backup)
    - [create_snapshot](#create_snapshot)
    - [create_storage_virtual_machine](#create_storage_virtual_machine)
    - [create_volume](#create_volume)
    - [create_volume_from_backup](#create_volume_from_backup)
    - [delete_backup](#delete_backup)
    - [delete_data_repository_association](#delete_data_repository_association)
    - [delete_file_system](#delete_file_system)
    - [delete_snapshot](#delete_snapshot)
    - [delete_storage_virtual_machine](#delete_storage_virtual_machine)
    - [delete_volume](#delete_volume)
    - [describe_backups](#describe_backups)
    - [describe_data_repository_associations](#describe_data_repository_associations)
    - [describe_data_repository_tasks](#describe_data_repository_tasks)
    - [describe_file_system_aliases](#describe_file_system_aliases)
    - [describe_file_systems](#describe_file_systems)
    - [describe_snapshots](#describe_snapshots)
    - [describe_storage_virtual_machines](#describe_storage_virtual_machines)
    - [describe_volumes](#describe_volumes)
    - [disassociate_file_system_aliases](#disassociate_file_system_aliases)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [release_file_system_nfs_v3_locks](#release_file_system_nfs_v3_locks)
    - [restore_volume_from_snapshot](#restore_volume_from_snapshot)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [update_data_repository_association](#update_data_repository_association)
    - [update_file_system](#update_file_system)
    - [update_snapshot](#update_snapshot)
    - [update_storage_virtual_machine](#update_storage_virtual_machine)
    - [update_volume](#update_volume)
    - [get_paginator](#get_paginator)

<a id="fsxclient"></a>

## FSxClient

Type annotations for `aiobotocore.create_client("fsx")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_fsx.client import FSxClient

def get_fsx_client() -> FSxClient:
    return Session().client("fsx")
```

Boto3 documentation:
[FSx.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_fsx.client import Exceptions

def handle_error(exc: Exceptions.ActiveDirectoryError) -> None:
    ...
```

Exceptions:

- `Exceptions.ActiveDirectoryError`
- `Exceptions.BackupBeingCopied`
- `Exceptions.BackupInProgress`
- `Exceptions.BackupNotFound`
- `Exceptions.BackupRestoring`
- `Exceptions.BadRequest`
- `Exceptions.ClientError`
- `Exceptions.DataRepositoryAssociationNotFound`
- `Exceptions.DataRepositoryTaskEnded`
- `Exceptions.DataRepositoryTaskExecuting`
- `Exceptions.DataRepositoryTaskNotFound`
- `Exceptions.FileSystemNotFound`
- `Exceptions.IncompatibleParameterError`
- `Exceptions.IncompatibleRegionForMultiAZ`
- `Exceptions.InternalServerError`
- `Exceptions.InvalidDataRepositoryType`
- `Exceptions.InvalidDestinationKmsKey`
- `Exceptions.InvalidExportPath`
- `Exceptions.InvalidImportPath`
- `Exceptions.InvalidNetworkSettings`
- `Exceptions.InvalidPerUnitStorageThroughput`
- `Exceptions.InvalidRegion`
- `Exceptions.InvalidSourceKmsKey`
- `Exceptions.MissingFileSystemConfiguration`
- `Exceptions.MissingVolumeConfiguration`
- `Exceptions.NotServiceResourceError`
- `Exceptions.ResourceDoesNotSupportTagging`
- `Exceptions.ResourceNotFound`
- `Exceptions.ServiceLimitExceeded`
- `Exceptions.SnapshotNotFound`
- `Exceptions.SourceBackupUnavailable`
- `Exceptions.StorageVirtualMachineNotFound`
- `Exceptions.UnsupportedOperation`
- `Exceptions.VolumeNotFound`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

FSxClient exceptions.

Type annotations for `aiobotocore.create_client("fsx").exceptions` method.

Boto3 documentation:
[FSx.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="associate_file_system_aliases"></a>

### associate_file_system_aliases

Use this action to associate one or more Domain Name Server (DNS) aliases with
an existing Amazon FSx for Windows File Server file system.

Type annotations for
`aiobotocore.create_client("fsx").associate_file_system_aliases` method.

Boto3 documentation:
[FSx.Client.associate_file_system_aliases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.associate_file_system_aliases)

Asynchronous method. Use `await associate_file_system_aliases(...)` for a
synchronous call.

Arguments mapping described in
[AssociateFileSystemAliasesRequestRequestTypeDef](./type_defs.md#associatefilesystemaliasesrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `Aliases`: `Sequence`\[`str`\] *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[AssociateFileSystemAliasesResponseTypeDef](./type_defs.md#associatefilesystemaliasesresponsetypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("fsx").can_paginate` method.

Boto3 documentation:
[FSx.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_data_repository_task"></a>

### cancel_data_repository_task

Cancels an existing Amazon FSx for Lustre data repository task if that task is
in either the `PENDING` or `EXECUTING` state.

Type annotations for
`aiobotocore.create_client("fsx").cancel_data_repository_task` method.

Boto3 documentation:
[FSx.Client.cancel_data_repository_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.cancel_data_repository_task)

Asynchronous method. Use `await cancel_data_repository_task(...)` for a
synchronous call.

Arguments mapping described in
[CancelDataRepositoryTaskRequestRequestTypeDef](./type_defs.md#canceldatarepositorytaskrequestrequesttypedef).

Keyword-only arguments:

- `TaskId`: `str` *(required)*

Returns a `Coroutine` for
[CancelDataRepositoryTaskResponseTypeDef](./type_defs.md#canceldatarepositorytaskresponsetypedef).

<a id="copy_backup"></a>

### copy_backup

Copies an existing backup within the same Amazon Web Services account to
another Amazon Web Services Region (cross-Region copy) or within the same
Amazon Web Services Region (in-Region copy).

Type annotations for `aiobotocore.create_client("fsx").copy_backup` method.

Boto3 documentation:
[FSx.Client.copy_backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.copy_backup)

Asynchronous method. Use `await copy_backup(...)` for a synchronous call.

Arguments mapping described in
[CopyBackupRequestRequestTypeDef](./type_defs.md#copybackuprequestrequesttypedef).

Keyword-only arguments:

- `SourceBackupId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `SourceRegion`: `str`
- `KmsKeyId`: `str`
- `CopyTags`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CopyBackupResponseTypeDef](./type_defs.md#copybackupresponsetypedef).

<a id="create_backup"></a>

### create_backup

Creates a backup of an existing Amazon FSx for Windows File Server file system,
Amazon FSx for Lustre file system, Amazon FSx for NetApp ONTAP volume, or
Amazon FSx for OpenZFS file system.

Type annotations for `aiobotocore.create_client("fsx").create_backup` method.

Boto3 documentation:
[FSx.Client.create_backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_backup)

Asynchronous method. Use `await create_backup(...)` for a synchronous call.

Arguments mapping described in
[CreateBackupRequestRequestTypeDef](./type_defs.md#createbackuprequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str`
- `ClientRequestToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `VolumeId`: `str`

Returns a `Coroutine` for
[CreateBackupResponseTypeDef](./type_defs.md#createbackupresponsetypedef).

<a id="create_data_repository_association"></a>

### create_data_repository_association

Creates an Amazon FSx for Lustre data repository association (DRA).

Type annotations for
`aiobotocore.create_client("fsx").create_data_repository_association` method.

Boto3 documentation:
[FSx.Client.create_data_repository_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_data_repository_association)

Asynchronous method. Use `await create_data_repository_association(...)` for a
synchronous call.

Arguments mapping described in
[CreateDataRepositoryAssociationRequestRequestTypeDef](./type_defs.md#createdatarepositoryassociationrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `FileSystemPath`: `str` *(required)*
- `DataRepositoryPath`: `str` *(required)*
- `BatchImportMetaDataOnCreate`: `bool`
- `ImportedFileChunkSize`: `int`
- `S3`:
  [S3DataRepositoryConfigurationTypeDef](./type_defs.md#s3datarepositoryconfigurationtypedef)
- `ClientRequestToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDataRepositoryAssociationResponseTypeDef](./type_defs.md#createdatarepositoryassociationresponsetypedef).

<a id="create_data_repository_task"></a>

### create_data_repository_task

Creates an Amazon FSx for Lustre data repository task.

Type annotations for
`aiobotocore.create_client("fsx").create_data_repository_task` method.

Boto3 documentation:
[FSx.Client.create_data_repository_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_data_repository_task)

Asynchronous method. Use `await create_data_repository_task(...)` for a
synchronous call.

Arguments mapping described in
[CreateDataRepositoryTaskRequestRequestTypeDef](./type_defs.md#createdatarepositorytaskrequestrequesttypedef).

Keyword-only arguments:

- `Type`:
  [DataRepositoryTaskTypeType](./literals.md#datarepositorytasktypetype)
  *(required)*
- `FileSystemId`: `str` *(required)*
- `Report`: [CompletionReportTypeDef](./type_defs.md#completionreporttypedef)
  *(required)*
- `Paths`: `Sequence`\[`str`\]
- `ClientRequestToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDataRepositoryTaskResponseTypeDef](./type_defs.md#createdatarepositorytaskresponsetypedef).

<a id="create_file_system"></a>

### create_file_system

Creates a new, empty Amazon FSx file system.

Type annotations for `aiobotocore.create_client("fsx").create_file_system`
method.

Boto3 documentation:
[FSx.Client.create_file_system](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_file_system)

Asynchronous method. Use `await create_file_system(...)` for a synchronous
call.

Arguments mapping described in
[CreateFileSystemRequestRequestTypeDef](./type_defs.md#createfilesystemrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemType`: [FileSystemTypeType](./literals.md#filesystemtypetype)
  *(required)*
- `StorageCapacity`: `int` *(required)*
- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `ClientRequestToken`: `str`
- `StorageType`: [StorageTypeType](./literals.md#storagetypetype)
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `KmsKeyId`: `str`
- `WindowsConfiguration`:
  [CreateFileSystemWindowsConfigurationTypeDef](./type_defs.md#createfilesystemwindowsconfigurationtypedef)
- `LustreConfiguration`:
  [CreateFileSystemLustreConfigurationTypeDef](./type_defs.md#createfilesystemlustreconfigurationtypedef)
- `OntapConfiguration`:
  [CreateFileSystemOntapConfigurationTypeDef](./type_defs.md#createfilesystemontapconfigurationtypedef)
- `FileSystemTypeVersion`: `str`
- `OpenZFSConfiguration`:
  [CreateFileSystemOpenZFSConfigurationTypeDef](./type_defs.md#createfilesystemopenzfsconfigurationtypedef)

Returns a `Coroutine` for
[CreateFileSystemResponseTypeDef](./type_defs.md#createfilesystemresponsetypedef).

<a id="create_file_system_from_backup"></a>

### create_file_system_from_backup

Creates a new Amazon FSx for Lustre, Amazon FSx for Windows File Server, or
Amazon FSx for OpenZFS file system from an existing Amazon FSx backup.

Type annotations for
`aiobotocore.create_client("fsx").create_file_system_from_backup` method.

Boto3 documentation:
[FSx.Client.create_file_system_from_backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_file_system_from_backup)

Asynchronous method. Use `await create_file_system_from_backup(...)` for a
synchronous call.

Arguments mapping described in
[CreateFileSystemFromBackupRequestRequestTypeDef](./type_defs.md#createfilesystemfrombackuprequestrequesttypedef).

Keyword-only arguments:

- `BackupId`: `str` *(required)*
- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `ClientRequestToken`: `str`
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `WindowsConfiguration`:
  [CreateFileSystemWindowsConfigurationTypeDef](./type_defs.md#createfilesystemwindowsconfigurationtypedef)
- `LustreConfiguration`:
  [CreateFileSystemLustreConfigurationTypeDef](./type_defs.md#createfilesystemlustreconfigurationtypedef)
- `StorageType`: [StorageTypeType](./literals.md#storagetypetype)
- `KmsKeyId`: `str`
- `FileSystemTypeVersion`: `str`
- `OpenZFSConfiguration`:
  [CreateFileSystemOpenZFSConfigurationTypeDef](./type_defs.md#createfilesystemopenzfsconfigurationtypedef)

Returns a `Coroutine` for
[CreateFileSystemFromBackupResponseTypeDef](./type_defs.md#createfilesystemfrombackupresponsetypedef).

<a id="create_snapshot"></a>

### create_snapshot

Creates a snapshot of an existing Amazon FSx for OpenZFS file system.

Type annotations for `aiobotocore.create_client("fsx").create_snapshot` method.

Boto3 documentation:
[FSx.Client.create_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_snapshot)

Asynchronous method. Use `await create_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CreateSnapshotRequestRequestTypeDef](./type_defs.md#createsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `VolumeId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateSnapshotResponseTypeDef](./type_defs.md#createsnapshotresponsetypedef).

<a id="create_storage_virtual_machine"></a>

### create_storage_virtual_machine

Creates a storage virtual machine (SVM) for an Amazon FSx for ONTAP file
system.

Type annotations for
`aiobotocore.create_client("fsx").create_storage_virtual_machine` method.

Boto3 documentation:
[FSx.Client.create_storage_virtual_machine](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_storage_virtual_machine)

Asynchronous method. Use `await create_storage_virtual_machine(...)` for a
synchronous call.

Arguments mapping described in
[CreateStorageVirtualMachineRequestRequestTypeDef](./type_defs.md#createstoragevirtualmachinerequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `Name`: `str` *(required)*
- `ActiveDirectoryConfiguration`:
  [CreateSvmActiveDirectoryConfigurationTypeDef](./type_defs.md#createsvmactivedirectoryconfigurationtypedef)
- `ClientRequestToken`: `str`
- `SvmAdminPassword`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `RootVolumeSecurityStyle`:
  [StorageVirtualMachineRootVolumeSecurityStyleType](./literals.md#storagevirtualmachinerootvolumesecuritystyletype)

Returns a `Coroutine` for
[CreateStorageVirtualMachineResponseTypeDef](./type_defs.md#createstoragevirtualmachineresponsetypedef).

<a id="create_volume"></a>

### create_volume

Creates an Amazon FSx for NetApp ONTAP or Amazon FSx for OpenZFS storage
volume.

Type annotations for `aiobotocore.create_client("fsx").create_volume` method.

Boto3 documentation:
[FSx.Client.create_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_volume)

Asynchronous method. Use `await create_volume(...)` for a synchronous call.

Arguments mapping described in
[CreateVolumeRequestRequestTypeDef](./type_defs.md#createvolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeType`: [VolumeTypeType](./literals.md#volumetypetype) *(required)*
- `Name`: `str` *(required)*
- `ClientRequestToken`: `str`
- `OntapConfiguration`:
  [CreateOntapVolumeConfigurationTypeDef](./type_defs.md#createontapvolumeconfigurationtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `OpenZFSConfiguration`:
  [CreateOpenZFSVolumeConfigurationTypeDef](./type_defs.md#createopenzfsvolumeconfigurationtypedef)

Returns a `Coroutine` for
[CreateVolumeResponseTypeDef](./type_defs.md#createvolumeresponsetypedef).

<a id="create_volume_from_backup"></a>

### create_volume_from_backup

Creates a new Amazon FSx for NetApp ONTAP volume from an existing Amazon FSx
volume backup.

Type annotations for
`aiobotocore.create_client("fsx").create_volume_from_backup` method.

Boto3 documentation:
[FSx.Client.create_volume_from_backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.create_volume_from_backup)

Asynchronous method. Use `await create_volume_from_backup(...)` for a
synchronous call.

Arguments mapping described in
[CreateVolumeFromBackupRequestRequestTypeDef](./type_defs.md#createvolumefrombackuprequestrequesttypedef).

Keyword-only arguments:

- `BackupId`: `str` *(required)*
- `Name`: `str` *(required)*
- `ClientRequestToken`: `str`
- `OntapConfiguration`:
  [CreateOntapVolumeConfigurationTypeDef](./type_defs.md#createontapvolumeconfigurationtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateVolumeFromBackupResponseTypeDef](./type_defs.md#createvolumefrombackupresponsetypedef).

<a id="delete_backup"></a>

### delete_backup

Deletes an Amazon FSx backup.

Type annotations for `aiobotocore.create_client("fsx").delete_backup` method.

Boto3 documentation:
[FSx.Client.delete_backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.delete_backup)

Asynchronous method. Use `await delete_backup(...)` for a synchronous call.

Arguments mapping described in
[DeleteBackupRequestRequestTypeDef](./type_defs.md#deletebackuprequestrequesttypedef).

Keyword-only arguments:

- `BackupId`: `str` *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[DeleteBackupResponseTypeDef](./type_defs.md#deletebackupresponsetypedef).

<a id="delete_data_repository_association"></a>

### delete_data_repository_association

Deletes a data repository association on an Amazon FSx for Lustre file system.

Type annotations for
`aiobotocore.create_client("fsx").delete_data_repository_association` method.

Boto3 documentation:
[FSx.Client.delete_data_repository_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.delete_data_repository_association)

Asynchronous method. Use `await delete_data_repository_association(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDataRepositoryAssociationRequestRequestTypeDef](./type_defs.md#deletedatarepositoryassociationrequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `DeleteDataInFileSystem`: `bool` *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[DeleteDataRepositoryAssociationResponseTypeDef](./type_defs.md#deletedatarepositoryassociationresponsetypedef).

<a id="delete_file_system"></a>

### delete_file_system

Deletes a file system.

Type annotations for `aiobotocore.create_client("fsx").delete_file_system`
method.

Boto3 documentation:
[FSx.Client.delete_file_system](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.delete_file_system)

Asynchronous method. Use `await delete_file_system(...)` for a synchronous
call.

Arguments mapping described in
[DeleteFileSystemRequestRequestTypeDef](./type_defs.md#deletefilesystemrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `WindowsConfiguration`:
  [DeleteFileSystemWindowsConfigurationTypeDef](./type_defs.md#deletefilesystemwindowsconfigurationtypedef)
- `LustreConfiguration`:
  [DeleteFileSystemLustreConfigurationTypeDef](./type_defs.md#deletefilesystemlustreconfigurationtypedef)
- `OpenZFSConfiguration`:
  [DeleteFileSystemOpenZFSConfigurationTypeDef](./type_defs.md#deletefilesystemopenzfsconfigurationtypedef)

Returns a `Coroutine` for
[DeleteFileSystemResponseTypeDef](./type_defs.md#deletefilesystemresponsetypedef).

<a id="delete_snapshot"></a>

### delete_snapshot

Deletes the Amazon FSx snapshot.

Type annotations for `aiobotocore.create_client("fsx").delete_snapshot` method.

Boto3 documentation:
[FSx.Client.delete_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.delete_snapshot)

Asynchronous method. Use `await delete_snapshot(...)` for a synchronous call.

Arguments mapping described in
[DeleteSnapshotRequestRequestTypeDef](./type_defs.md#deletesnapshotrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[DeleteSnapshotResponseTypeDef](./type_defs.md#deletesnapshotresponsetypedef).

<a id="delete_storage_virtual_machine"></a>

### delete_storage_virtual_machine

Deletes an existing Amazon FSx for ONTAP storage virtual machine (SVM).

Type annotations for
`aiobotocore.create_client("fsx").delete_storage_virtual_machine` method.

Boto3 documentation:
[FSx.Client.delete_storage_virtual_machine](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.delete_storage_virtual_machine)

Asynchronous method. Use `await delete_storage_virtual_machine(...)` for a
synchronous call.

Arguments mapping described in
[DeleteStorageVirtualMachineRequestRequestTypeDef](./type_defs.md#deletestoragevirtualmachinerequestrequesttypedef).

Keyword-only arguments:

- `StorageVirtualMachineId`: `str` *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[DeleteStorageVirtualMachineResponseTypeDef](./type_defs.md#deletestoragevirtualmachineresponsetypedef).

<a id="delete_volume"></a>

### delete_volume

Deletes an Amazon FSx for NetApp ONTAP or Amazon FSx for OpenZFS volume.

Type annotations for `aiobotocore.create_client("fsx").delete_volume` method.

Boto3 documentation:
[FSx.Client.delete_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.delete_volume)

Asynchronous method. Use `await delete_volume(...)` for a synchronous call.

Arguments mapping described in
[DeleteVolumeRequestRequestTypeDef](./type_defs.md#deletevolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `OntapConfiguration`:
  [DeleteVolumeOntapConfigurationTypeDef](./type_defs.md#deletevolumeontapconfigurationtypedef)
- `OpenZFSConfiguration`:
  [DeleteVolumeOpenZFSConfigurationTypeDef](./type_defs.md#deletevolumeopenzfsconfigurationtypedef)

Returns a `Coroutine` for
[DeleteVolumeResponseTypeDef](./type_defs.md#deletevolumeresponsetypedef).

<a id="describe_backups"></a>

### describe_backups

Returns the description of a specific Amazon FSx backup, if a `BackupIds` value
is provided for that backup.

Type annotations for `aiobotocore.create_client("fsx").describe_backups`
method.

Boto3 documentation:
[FSx.Client.describe_backups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_backups)

Asynchronous method. Use `await describe_backups(...)` for a synchronous call.

Arguments mapping described in
[DescribeBackupsRequestRequestTypeDef](./type_defs.md#describebackupsrequestrequesttypedef).

Keyword-only arguments:

- `BackupIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeBackupsResponseTypeDef](./type_defs.md#describebackupsresponsetypedef).

<a id="describe_data_repository_associations"></a>

### describe_data_repository_associations

Returns the description of specific Amazon FSx for Lustre data repository
associations, if one or more `AssociationIds` values are provided in the
request, or if filters are used in the request.

Type annotations for
`aiobotocore.create_client("fsx").describe_data_repository_associations`
method.

Boto3 documentation:
[FSx.Client.describe_data_repository_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_data_repository_associations)

Asynchronous method. Use `await describe_data_repository_associations(...)` for
a synchronous call.

Arguments mapping described in
[DescribeDataRepositoryAssociationsRequestRequestTypeDef](./type_defs.md#describedatarepositoryassociationsrequestrequesttypedef).

Keyword-only arguments:

- `AssociationIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeDataRepositoryAssociationsResponseTypeDef](./type_defs.md#describedatarepositoryassociationsresponsetypedef).

<a id="describe_data_repository_tasks"></a>

### describe_data_repository_tasks

Returns the description of specific Amazon FSx for Lustre data repository
tasks, if one or more `TaskIds` values are provided in the request, or if
filters are used in the request.

Type annotations for
`aiobotocore.create_client("fsx").describe_data_repository_tasks` method.

Boto3 documentation:
[FSx.Client.describe_data_repository_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_data_repository_tasks)

Asynchronous method. Use `await describe_data_repository_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeDataRepositoryTasksRequestRequestTypeDef](./type_defs.md#describedatarepositorytasksrequestrequesttypedef).

Keyword-only arguments:

- `TaskIds`: `Sequence`\[`str`\]
- `Filters`:
  `Sequence`\[[DataRepositoryTaskFilterTypeDef](./type_defs.md#datarepositorytaskfiltertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeDataRepositoryTasksResponseTypeDef](./type_defs.md#describedatarepositorytasksresponsetypedef).

<a id="describe_file_system_aliases"></a>

### describe_file_system_aliases

Returns the DNS aliases that are associated with the specified Amazon FSx for
Windows File Server file system.

Type annotations for
`aiobotocore.create_client("fsx").describe_file_system_aliases` method.

Boto3 documentation:
[FSx.Client.describe_file_system_aliases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_file_system_aliases)

Asynchronous method. Use `await describe_file_system_aliases(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFileSystemAliasesRequestRequestTypeDef](./type_defs.md#describefilesystemaliasesrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeFileSystemAliasesResponseTypeDef](./type_defs.md#describefilesystemaliasesresponsetypedef).

<a id="describe_file_systems"></a>

### describe_file_systems

Returns the description of specific Amazon FSx file systems, if a
`FileSystemIds` value is provided for that file system.

Type annotations for `aiobotocore.create_client("fsx").describe_file_systems`
method.

Boto3 documentation:
[FSx.Client.describe_file_systems](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_file_systems)

Asynchronous method. Use `await describe_file_systems(...)` for a synchronous
call.

Arguments mapping described in
[DescribeFileSystemsRequestRequestTypeDef](./type_defs.md#describefilesystemsrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeFileSystemsResponseTypeDef](./type_defs.md#describefilesystemsresponsetypedef).

<a id="describe_snapshots"></a>

### describe_snapshots

Returns the description of specific Amazon FSx snapshots, if a `SnapshotIds`
value is provided.

Type annotations for `aiobotocore.create_client("fsx").describe_snapshots`
method.

Boto3 documentation:
[FSx.Client.describe_snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_snapshots)

Asynchronous method. Use `await describe_snapshots(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSnapshotsRequestRequestTypeDef](./type_defs.md#describesnapshotsrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotIds`: `Sequence`\[`str`\]
- `Filters`:
  `Sequence`\[[SnapshotFilterTypeDef](./type_defs.md#snapshotfiltertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeSnapshotsResponseTypeDef](./type_defs.md#describesnapshotsresponsetypedef).

<a id="describe_storage_virtual_machines"></a>

### describe_storage_virtual_machines

Describes one or more Amazon FSx for NetApp ONTAP storage virtual machines
(SVMs).

Type annotations for
`aiobotocore.create_client("fsx").describe_storage_virtual_machines` method.

Boto3 documentation:
[FSx.Client.describe_storage_virtual_machines](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_storage_virtual_machines)

Asynchronous method. Use `await describe_storage_virtual_machines(...)` for a
synchronous call.

Arguments mapping described in
[DescribeStorageVirtualMachinesRequestRequestTypeDef](./type_defs.md#describestoragevirtualmachinesrequestrequesttypedef).

Keyword-only arguments:

- `StorageVirtualMachineIds`: `Sequence`\[`str`\]
- `Filters`:
  `Sequence`\[[StorageVirtualMachineFilterTypeDef](./type_defs.md#storagevirtualmachinefiltertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeStorageVirtualMachinesResponseTypeDef](./type_defs.md#describestoragevirtualmachinesresponsetypedef).

<a id="describe_volumes"></a>

### describe_volumes

Describes one or more Amazon FSx for NetApp ONTAP or Amazon FSx for OpenZFS
volumes.

Type annotations for `aiobotocore.create_client("fsx").describe_volumes`
method.

Boto3 documentation:
[FSx.Client.describe_volumes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.describe_volumes)

Asynchronous method. Use `await describe_volumes(...)` for a synchronous call.

Arguments mapping described in
[DescribeVolumesRequestRequestTypeDef](./type_defs.md#describevolumesrequestrequesttypedef).

Keyword-only arguments:

- `VolumeIds`: `Sequence`\[`str`\]
- `Filters`:
  `Sequence`\[[VolumeFilterTypeDef](./type_defs.md#volumefiltertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVolumesResponseTypeDef](./type_defs.md#describevolumesresponsetypedef).

<a id="disassociate_file_system_aliases"></a>

### disassociate_file_system_aliases

Use this action to disassociate, or remove, one or more Domain Name Service
(DNS) aliases from an Amazon FSx for Windows File Server file system.

Type annotations for
`aiobotocore.create_client("fsx").disassociate_file_system_aliases` method.

Boto3 documentation:
[FSx.Client.disassociate_file_system_aliases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.disassociate_file_system_aliases)

Asynchronous method. Use `await disassociate_file_system_aliases(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateFileSystemAliasesRequestRequestTypeDef](./type_defs.md#disassociatefilesystemaliasesrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `Aliases`: `Sequence`\[`str`\] *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[DisassociateFileSystemAliasesResponseTypeDef](./type_defs.md#disassociatefilesystemaliasesresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("fsx").generate_presigned_url`
method.

Boto3 documentation:
[FSx.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists tags for an Amazon FSx file systems and backups in the case of Amazon FSx
for Windows File Server.

Type annotations for `aiobotocore.create_client("fsx").list_tags_for_resource`
method.

Boto3 documentation:
[FSx.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="release_file_system_nfs_v3_locks"></a>

### release_file_system_nfs_v3_locks

Releases the file system lock from an Amazon FSx for OpenZFS file system.

Type annotations for
`aiobotocore.create_client("fsx").release_file_system_nfs_v3_locks` method.

Boto3 documentation:
[FSx.Client.release_file_system_nfs_v3_locks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.release_file_system_nfs_v3_locks)

Asynchronous method. Use `await release_file_system_nfs_v3_locks(...)` for a
synchronous call.

Arguments mapping described in
[ReleaseFileSystemNfsV3LocksRequestRequestTypeDef](./type_defs.md#releasefilesystemnfsv3locksrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[ReleaseFileSystemNfsV3LocksResponseTypeDef](./type_defs.md#releasefilesystemnfsv3locksresponsetypedef).

<a id="restore_volume_from_snapshot"></a>

### restore_volume_from_snapshot

Returns an Amazon FSx for OpenZFS volume to the state saved by the specified
snapshot.

Type annotations for
`aiobotocore.create_client("fsx").restore_volume_from_snapshot` method.

Boto3 documentation:
[FSx.Client.restore_volume_from_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.restore_volume_from_snapshot)

Asynchronous method. Use `await restore_volume_from_snapshot(...)` for a
synchronous call.

Arguments mapping described in
[RestoreVolumeFromSnapshotRequestRequestTypeDef](./type_defs.md#restorevolumefromsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `SnapshotId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `Options`:
  `Sequence`\[[RestoreOpenZFSVolumeOptionType](./literals.md#restoreopenzfsvolumeoptiontype)\]

Returns a `Coroutine` for
[RestoreVolumeFromSnapshotResponseTypeDef](./type_defs.md#restorevolumefromsnapshotresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Tags an Amazon FSx resource.

Type annotations for `aiobotocore.create_client("fsx").tag_resource` method.

Boto3 documentation:
[FSx.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

This action removes a tag from an Amazon FSx resource.

Type annotations for `aiobotocore.create_client("fsx").untag_resource` method.

Boto3 documentation:
[FSx.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_data_repository_association"></a>

### update_data_repository_association

Updates the configuration of an existing data repository association on an
Amazon FSx for Lustre file system.

Type annotations for
`aiobotocore.create_client("fsx").update_data_repository_association` method.

Boto3 documentation:
[FSx.Client.update_data_repository_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.update_data_repository_association)

Asynchronous method. Use `await update_data_repository_association(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDataRepositoryAssociationRequestRequestTypeDef](./type_defs.md#updatedatarepositoryassociationrequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `ImportedFileChunkSize`: `int`
- `S3`:
  [S3DataRepositoryConfigurationTypeDef](./type_defs.md#s3datarepositoryconfigurationtypedef)

Returns a `Coroutine` for
[UpdateDataRepositoryAssociationResponseTypeDef](./type_defs.md#updatedatarepositoryassociationresponsetypedef).

<a id="update_file_system"></a>

### update_file_system

Use this operation to update the configuration of an existing Amazon FSx file
system.

Type annotations for `aiobotocore.create_client("fsx").update_file_system`
method.

Boto3 documentation:
[FSx.Client.update_file_system](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.update_file_system)

Asynchronous method. Use `await update_file_system(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFileSystemRequestRequestTypeDef](./type_defs.md#updatefilesystemrequestrequesttypedef).

Keyword-only arguments:

- `FileSystemId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `StorageCapacity`: `int`
- `WindowsConfiguration`:
  [UpdateFileSystemWindowsConfigurationTypeDef](./type_defs.md#updatefilesystemwindowsconfigurationtypedef)
- `LustreConfiguration`:
  [UpdateFileSystemLustreConfigurationTypeDef](./type_defs.md#updatefilesystemlustreconfigurationtypedef)
- `OntapConfiguration`:
  [UpdateFileSystemOntapConfigurationTypeDef](./type_defs.md#updatefilesystemontapconfigurationtypedef)
- `OpenZFSConfiguration`:
  [UpdateFileSystemOpenZFSConfigurationTypeDef](./type_defs.md#updatefilesystemopenzfsconfigurationtypedef)

Returns a `Coroutine` for
[UpdateFileSystemResponseTypeDef](./type_defs.md#updatefilesystemresponsetypedef).

<a id="update_snapshot"></a>

### update_snapshot

Updates the name of a snapshot.

Type annotations for `aiobotocore.create_client("fsx").update_snapshot` method.

Boto3 documentation:
[FSx.Client.update_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.update_snapshot)

Asynchronous method. Use `await update_snapshot(...)` for a synchronous call.

Arguments mapping described in
[UpdateSnapshotRequestRequestTypeDef](./type_defs.md#updatesnapshotrequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `SnapshotId`: `str` *(required)*
- `ClientRequestToken`: `str`

Returns a `Coroutine` for
[UpdateSnapshotResponseTypeDef](./type_defs.md#updatesnapshotresponsetypedef).

<a id="update_storage_virtual_machine"></a>

### update_storage_virtual_machine

Updates an Amazon FSx for ONTAP storage virtual machine (SVM).

Type annotations for
`aiobotocore.create_client("fsx").update_storage_virtual_machine` method.

Boto3 documentation:
[FSx.Client.update_storage_virtual_machine](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.update_storage_virtual_machine)

Asynchronous method. Use `await update_storage_virtual_machine(...)` for a
synchronous call.

Arguments mapping described in
[UpdateStorageVirtualMachineRequestRequestTypeDef](./type_defs.md#updatestoragevirtualmachinerequestrequesttypedef).

Keyword-only arguments:

- `StorageVirtualMachineId`: `str` *(required)*
- `ActiveDirectoryConfiguration`:
  [UpdateSvmActiveDirectoryConfigurationTypeDef](./type_defs.md#updatesvmactivedirectoryconfigurationtypedef)
- `ClientRequestToken`: `str`
- `SvmAdminPassword`: `str`

Returns a `Coroutine` for
[UpdateStorageVirtualMachineResponseTypeDef](./type_defs.md#updatestoragevirtualmachineresponsetypedef).

<a id="update_volume"></a>

### update_volume

Updates the configuration of an Amazon FSx for NetApp ONTAP or Amazon FSx for
OpenZFS volume.

Type annotations for `aiobotocore.create_client("fsx").update_volume` method.

Boto3 documentation:
[FSx.Client.update_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.update_volume)

Asynchronous method. Use `await update_volume(...)` for a synchronous call.

Arguments mapping described in
[UpdateVolumeRequestRequestTypeDef](./type_defs.md#updatevolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `ClientRequestToken`: `str`
- `OntapConfiguration`:
  [UpdateOntapVolumeConfigurationTypeDef](./type_defs.md#updateontapvolumeconfigurationtypedef)
- `Name`: `str`
- `OpenZFSConfiguration`:
  [UpdateOpenZFSVolumeConfigurationTypeDef](./type_defs.md#updateopenzfsvolumeconfigurationtypedef)

Returns a `Coroutine` for
[UpdateVolumeResponseTypeDef](./type_defs.md#updatevolumeresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("fsx").get_paginator` method
with overloads.

- `client.get_paginator("describe_backups")` ->
  [DescribeBackupsPaginator](./paginators.md#describebackupspaginator)
- `client.get_paginator("describe_file_systems")` ->
  [DescribeFileSystemsPaginator](./paginators.md#describefilesystemspaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
