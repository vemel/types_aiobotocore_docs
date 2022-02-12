<a id="type-annotations-for-aiobotocore-storagegateway-module"></a>

# Type annotations for aiobotocore StorageGateway module

> [Index](..) > StorageGateway

Auto-generated documentation for
[StorageGateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/storagegateway.html#StorageGateway)
type annotations stubs module
[types-aiobotocore-storagegateway](https://pypi.org/project/types-aiobotocore-storagegateway/).

- [Type annotations for aiobotocore StorageGateway module](#type-annotations-for-aiobotocore-storagegateway-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [StorageGatewayClient](#storagegatewayclient)
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

Click `Modify` and select `boto3 common` and `StorageGateway`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `StorageGateway` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[storagegateway]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[storagegateway]'

# standalone installation
python -m pip install types-aiobotocore-storagegateway
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-storagegateway
```

<a id="storagegatewayclient"></a>

## StorageGatewayClient

Type annotations for `session.create_client("storagegateway")` as
[StorageGatewayClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_storagegateway.client import StorageGatewayClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [activate_gateway](./client.md#activate_gateway)
- [add_cache](./client.md#add_cache)
- [add_tags_to_resource](./client.md#add_tags_to_resource)
- [add_upload_buffer](./client.md#add_upload_buffer)
- [add_working_storage](./client.md#add_working_storage)
- [assign_tape_pool](./client.md#assign_tape_pool)
- [associate_file_system](./client.md#associate_file_system)
- [attach_volume](./client.md#attach_volume)
- [can_paginate](./client.md#can_paginate)
- [cancel_archival](./client.md#cancel_archival)
- [cancel_retrieval](./client.md#cancel_retrieval)
- [create_cached_iscsi_volume](./client.md#create_cached_iscsi_volume)
- [create_nfs_file_share](./client.md#create_nfs_file_share)
- [create_smb_file_share](./client.md#create_smb_file_share)
- [create_snapshot](./client.md#create_snapshot)
- [create_snapshot_from_volume_recovery_point](./client.md#create_snapshot_from_volume_recovery_point)
- [create_stored_iscsi_volume](./client.md#create_stored_iscsi_volume)
- [create_tape_pool](./client.md#create_tape_pool)
- [create_tape_with_barcode](./client.md#create_tape_with_barcode)
- [create_tapes](./client.md#create_tapes)
- [delete_automatic_tape_creation_policy](./client.md#delete_automatic_tape_creation_policy)
- [delete_bandwidth_rate_limit](./client.md#delete_bandwidth_rate_limit)
- [delete_chap_credentials](./client.md#delete_chap_credentials)
- [delete_file_share](./client.md#delete_file_share)
- [delete_gateway](./client.md#delete_gateway)
- [delete_snapshot_schedule](./client.md#delete_snapshot_schedule)
- [delete_tape](./client.md#delete_tape)
- [delete_tape_archive](./client.md#delete_tape_archive)
- [delete_tape_pool](./client.md#delete_tape_pool)
- [delete_volume](./client.md#delete_volume)
- [describe_availability_monitor_test](./client.md#describe_availability_monitor_test)
- [describe_bandwidth_rate_limit](./client.md#describe_bandwidth_rate_limit)
- [describe_bandwidth_rate_limit_schedule](./client.md#describe_bandwidth_rate_limit_schedule)
- [describe_cache](./client.md#describe_cache)
- [describe_cached_iscsi_volumes](./client.md#describe_cached_iscsi_volumes)
- [describe_chap_credentials](./client.md#describe_chap_credentials)
- [describe_file_system_associations](./client.md#describe_file_system_associations)
- [describe_gateway_information](./client.md#describe_gateway_information)
- [describe_maintenance_start_time](./client.md#describe_maintenance_start_time)
- [describe_nfs_file_shares](./client.md#describe_nfs_file_shares)
- [describe_smb_file_shares](./client.md#describe_smb_file_shares)
- [describe_smb_settings](./client.md#describe_smb_settings)
- [describe_snapshot_schedule](./client.md#describe_snapshot_schedule)
- [describe_stored_iscsi_volumes](./client.md#describe_stored_iscsi_volumes)
- [describe_tape_archives](./client.md#describe_tape_archives)
- [describe_tape_recovery_points](./client.md#describe_tape_recovery_points)
- [describe_tapes](./client.md#describe_tapes)
- [describe_upload_buffer](./client.md#describe_upload_buffer)
- [describe_vtl_devices](./client.md#describe_vtl_devices)
- [describe_working_storage](./client.md#describe_working_storage)
- [detach_volume](./client.md#detach_volume)
- [disable_gateway](./client.md#disable_gateway)
- [disassociate_file_system](./client.md#disassociate_file_system)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [join_domain](./client.md#join_domain)
- [list_automatic_tape_creation_policies](./client.md#list_automatic_tape_creation_policies)
- [list_file_shares](./client.md#list_file_shares)
- [list_file_system_associations](./client.md#list_file_system_associations)
- [list_gateways](./client.md#list_gateways)
- [list_local_disks](./client.md#list_local_disks)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [list_tape_pools](./client.md#list_tape_pools)
- [list_tapes](./client.md#list_tapes)
- [list_volume_initiators](./client.md#list_volume_initiators)
- [list_volume_recovery_points](./client.md#list_volume_recovery_points)
- [list_volumes](./client.md#list_volumes)
- [notify_when_uploaded](./client.md#notify_when_uploaded)
- [refresh_cache](./client.md#refresh_cache)
- [remove_tags_from_resource](./client.md#remove_tags_from_resource)
- [reset_cache](./client.md#reset_cache)
- [retrieve_tape_archive](./client.md#retrieve_tape_archive)
- [retrieve_tape_recovery_point](./client.md#retrieve_tape_recovery_point)
- [set_local_console_password](./client.md#set_local_console_password)
- [set_smb_guest_password](./client.md#set_smb_guest_password)
- [shutdown_gateway](./client.md#shutdown_gateway)
- [start_availability_monitor_test](./client.md#start_availability_monitor_test)
- [start_gateway](./client.md#start_gateway)
- [update_automatic_tape_creation_policy](./client.md#update_automatic_tape_creation_policy)
- [update_bandwidth_rate_limit](./client.md#update_bandwidth_rate_limit)
- [update_bandwidth_rate_limit_schedule](./client.md#update_bandwidth_rate_limit_schedule)
- [update_chap_credentials](./client.md#update_chap_credentials)
- [update_file_system_association](./client.md#update_file_system_association)
- [update_gateway_information](./client.md#update_gateway_information)
- [update_gateway_software_now](./client.md#update_gateway_software_now)
- [update_maintenance_start_time](./client.md#update_maintenance_start_time)
- [update_nfs_file_share](./client.md#update_nfs_file_share)
- [update_smb_file_share](./client.md#update_smb_file_share)
- [update_smb_file_share_visibility](./client.md#update_smb_file_share_visibility)
- [update_smb_local_groups](./client.md#update_smb_local_groups)
- [update_smb_security_strategy](./client.md#update_smb_security_strategy)
- [update_snapshot_schedule](./client.md#update_snapshot_schedule)
- [update_vtl_device_type](./client.md#update_vtl_device_type)

<a id="exceptions"></a>

### Exceptions

StorageGatewayClient [exceptions](./client.md#exceptions)

- ClientError
- InternalServerError
- InvalidGatewayRequestException
- ServiceUnavailableError

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("storagegateway").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_storagegateway.paginator import DescribeTapeArchivesPaginator, ...
```

- [DescribeTapeArchivesPaginator](./paginators.md#describetapearchivespaginator)
- [DescribeTapeRecoveryPointsPaginator](./paginators.md#describetaperecoverypointspaginator)
- [DescribeTapesPaginator](./paginators.md#describetapespaginator)
- [DescribeVTLDevicesPaginator](./paginators.md#describevtldevicespaginator)
- [ListFileSharesPaginator](./paginators.md#listfilesharespaginator)
- [ListFileSystemAssociationsPaginator](./paginators.md#listfilesystemassociationspaginator)
- [ListGatewaysPaginator](./paginators.md#listgatewayspaginator)
- [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- [ListTapePoolsPaginator](./paginators.md#listtapepoolspaginator)
- [ListTapesPaginator](./paginators.md#listtapespaginator)
- [ListVolumesPaginator](./paginators.md#listvolumespaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_storagegateway.literals import ActiveDirectoryStatusType, ...
```

- [ActiveDirectoryStatusType](./literals.md#activedirectorystatustype)
- [AvailabilityMonitorTestStatusType](./literals.md#availabilitymonitorteststatustype)
- [CaseSensitivityType](./literals.md#casesensitivitytype)
- [DescribeTapeArchivesPaginatorName](./literals.md#describetapearchivespaginatorname)
- [DescribeTapeRecoveryPointsPaginatorName](./literals.md#describetaperecoverypointspaginatorname)
- [DescribeTapesPaginatorName](./literals.md#describetapespaginatorname)
- [DescribeVTLDevicesPaginatorName](./literals.md#describevtldevicespaginatorname)
- [FileShareTypeType](./literals.md#filesharetypetype)
- [GatewayCapacityType](./literals.md#gatewaycapacitytype)
- [HostEnvironmentType](./literals.md#hostenvironmenttype)
- [ListFileSharesPaginatorName](./literals.md#listfilesharespaginatorname)
- [ListFileSystemAssociationsPaginatorName](./literals.md#listfilesystemassociationspaginatorname)
- [ListGatewaysPaginatorName](./literals.md#listgatewayspaginatorname)
- [ListTagsForResourcePaginatorName](./literals.md#listtagsforresourcepaginatorname)
- [ListTapePoolsPaginatorName](./literals.md#listtapepoolspaginatorname)
- [ListTapesPaginatorName](./literals.md#listtapespaginatorname)
- [ListVolumesPaginatorName](./literals.md#listvolumespaginatorname)
- [ObjectACLType](./literals.md#objectacltype)
- [PoolStatusType](./literals.md#poolstatustype)
- [RetentionLockTypeType](./literals.md#retentionlocktypetype)
- [SMBSecurityStrategyType](./literals.md#smbsecuritystrategytype)
- [TapeStorageClassType](./literals.md#tapestorageclasstype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_storagegateway.type_defs import ActivateGatewayInputRequestTypeDef, ...
```

- [ActivateGatewayInputRequestTypeDef](./type_defs.md#activategatewayinputrequesttypedef)
- [ActivateGatewayOutputTypeDef](./type_defs.md#activategatewayoutputtypedef)
- [AddCacheInputRequestTypeDef](./type_defs.md#addcacheinputrequesttypedef)
- [AddCacheOutputTypeDef](./type_defs.md#addcacheoutputtypedef)
- [AddTagsToResourceInputRequestTypeDef](./type_defs.md#addtagstoresourceinputrequesttypedef)
- [AddTagsToResourceOutputTypeDef](./type_defs.md#addtagstoresourceoutputtypedef)
- [AddUploadBufferInputRequestTypeDef](./type_defs.md#adduploadbufferinputrequesttypedef)
- [AddUploadBufferOutputTypeDef](./type_defs.md#adduploadbufferoutputtypedef)
- [AddWorkingStorageInputRequestTypeDef](./type_defs.md#addworkingstorageinputrequesttypedef)
- [AddWorkingStorageOutputTypeDef](./type_defs.md#addworkingstorageoutputtypedef)
- [AssignTapePoolInputRequestTypeDef](./type_defs.md#assigntapepoolinputrequesttypedef)
- [AssignTapePoolOutputTypeDef](./type_defs.md#assigntapepooloutputtypedef)
- [AssociateFileSystemInputRequestTypeDef](./type_defs.md#associatefilesysteminputrequesttypedef)
- [AssociateFileSystemOutputTypeDef](./type_defs.md#associatefilesystemoutputtypedef)
- [AttachVolumeInputRequestTypeDef](./type_defs.md#attachvolumeinputrequesttypedef)
- [AttachVolumeOutputTypeDef](./type_defs.md#attachvolumeoutputtypedef)
- [AutomaticTapeCreationPolicyInfoTypeDef](./type_defs.md#automatictapecreationpolicyinfotypedef)
- [AutomaticTapeCreationRuleTypeDef](./type_defs.md#automatictapecreationruletypedef)
- [BandwidthRateLimitIntervalTypeDef](./type_defs.md#bandwidthratelimitintervaltypedef)
- [CacheAttributesTypeDef](./type_defs.md#cacheattributestypedef)
- [CachediSCSIVolumeTypeDef](./type_defs.md#cachediscsivolumetypedef)
- [CancelArchivalInputRequestTypeDef](./type_defs.md#cancelarchivalinputrequesttypedef)
- [CancelArchivalOutputTypeDef](./type_defs.md#cancelarchivaloutputtypedef)
- [CancelRetrievalInputRequestTypeDef](./type_defs.md#cancelretrievalinputrequesttypedef)
- [CancelRetrievalOutputTypeDef](./type_defs.md#cancelretrievaloutputtypedef)
- [ChapInfoTypeDef](./type_defs.md#chapinfotypedef)
- [CreateCachediSCSIVolumeInputRequestTypeDef](./type_defs.md#createcachediscsivolumeinputrequesttypedef)
- [CreateCachediSCSIVolumeOutputTypeDef](./type_defs.md#createcachediscsivolumeoutputtypedef)
- [CreateNFSFileShareInputRequestTypeDef](./type_defs.md#createnfsfileshareinputrequesttypedef)
- [CreateNFSFileShareOutputTypeDef](./type_defs.md#createnfsfileshareoutputtypedef)
- [CreateSMBFileShareInputRequestTypeDef](./type_defs.md#createsmbfileshareinputrequesttypedef)
- [CreateSMBFileShareOutputTypeDef](./type_defs.md#createsmbfileshareoutputtypedef)
- [CreateSnapshotFromVolumeRecoveryPointInputRequestTypeDef](./type_defs.md#createsnapshotfromvolumerecoverypointinputrequesttypedef)
- [CreateSnapshotFromVolumeRecoveryPointOutputTypeDef](./type_defs.md#createsnapshotfromvolumerecoverypointoutputtypedef)
- [CreateSnapshotInputRequestTypeDef](./type_defs.md#createsnapshotinputrequesttypedef)
- [CreateSnapshotOutputTypeDef](./type_defs.md#createsnapshotoutputtypedef)
- [CreateStorediSCSIVolumeInputRequestTypeDef](./type_defs.md#createstorediscsivolumeinputrequesttypedef)
- [CreateStorediSCSIVolumeOutputTypeDef](./type_defs.md#createstorediscsivolumeoutputtypedef)
- [CreateTapePoolInputRequestTypeDef](./type_defs.md#createtapepoolinputrequesttypedef)
- [CreateTapePoolOutputTypeDef](./type_defs.md#createtapepooloutputtypedef)
- [CreateTapeWithBarcodeInputRequestTypeDef](./type_defs.md#createtapewithbarcodeinputrequesttypedef)
- [CreateTapeWithBarcodeOutputTypeDef](./type_defs.md#createtapewithbarcodeoutputtypedef)
- [CreateTapesInputRequestTypeDef](./type_defs.md#createtapesinputrequesttypedef)
- [CreateTapesOutputTypeDef](./type_defs.md#createtapesoutputtypedef)
- [DeleteAutomaticTapeCreationPolicyInputRequestTypeDef](./type_defs.md#deleteautomatictapecreationpolicyinputrequesttypedef)
- [DeleteAutomaticTapeCreationPolicyOutputTypeDef](./type_defs.md#deleteautomatictapecreationpolicyoutputtypedef)
- [DeleteBandwidthRateLimitInputRequestTypeDef](./type_defs.md#deletebandwidthratelimitinputrequesttypedef)
- [DeleteBandwidthRateLimitOutputTypeDef](./type_defs.md#deletebandwidthratelimitoutputtypedef)
- [DeleteChapCredentialsInputRequestTypeDef](./type_defs.md#deletechapcredentialsinputrequesttypedef)
- [DeleteChapCredentialsOutputTypeDef](./type_defs.md#deletechapcredentialsoutputtypedef)
- [DeleteFileShareInputRequestTypeDef](./type_defs.md#deletefileshareinputrequesttypedef)
- [DeleteFileShareOutputTypeDef](./type_defs.md#deletefileshareoutputtypedef)
- [DeleteGatewayInputRequestTypeDef](./type_defs.md#deletegatewayinputrequesttypedef)
- [DeleteGatewayOutputTypeDef](./type_defs.md#deletegatewayoutputtypedef)
- [DeleteSnapshotScheduleInputRequestTypeDef](./type_defs.md#deletesnapshotscheduleinputrequesttypedef)
- [DeleteSnapshotScheduleOutputTypeDef](./type_defs.md#deletesnapshotscheduleoutputtypedef)
- [DeleteTapeArchiveInputRequestTypeDef](./type_defs.md#deletetapearchiveinputrequesttypedef)
- [DeleteTapeArchiveOutputTypeDef](./type_defs.md#deletetapearchiveoutputtypedef)
- [DeleteTapeInputRequestTypeDef](./type_defs.md#deletetapeinputrequesttypedef)
- [DeleteTapeOutputTypeDef](./type_defs.md#deletetapeoutputtypedef)
- [DeleteTapePoolInputRequestTypeDef](./type_defs.md#deletetapepoolinputrequesttypedef)
- [DeleteTapePoolOutputTypeDef](./type_defs.md#deletetapepooloutputtypedef)
- [DeleteVolumeInputRequestTypeDef](./type_defs.md#deletevolumeinputrequesttypedef)
- [DeleteVolumeOutputTypeDef](./type_defs.md#deletevolumeoutputtypedef)
- [DescribeAvailabilityMonitorTestInputRequestTypeDef](./type_defs.md#describeavailabilitymonitortestinputrequesttypedef)
- [DescribeAvailabilityMonitorTestOutputTypeDef](./type_defs.md#describeavailabilitymonitortestoutputtypedef)
- [DescribeBandwidthRateLimitInputRequestTypeDef](./type_defs.md#describebandwidthratelimitinputrequesttypedef)
- [DescribeBandwidthRateLimitOutputTypeDef](./type_defs.md#describebandwidthratelimitoutputtypedef)
- [DescribeBandwidthRateLimitScheduleInputRequestTypeDef](./type_defs.md#describebandwidthratelimitscheduleinputrequesttypedef)
- [DescribeBandwidthRateLimitScheduleOutputTypeDef](./type_defs.md#describebandwidthratelimitscheduleoutputtypedef)
- [DescribeCacheInputRequestTypeDef](./type_defs.md#describecacheinputrequesttypedef)
- [DescribeCacheOutputTypeDef](./type_defs.md#describecacheoutputtypedef)
- [DescribeCachediSCSIVolumesInputRequestTypeDef](./type_defs.md#describecachediscsivolumesinputrequesttypedef)
- [DescribeCachediSCSIVolumesOutputTypeDef](./type_defs.md#describecachediscsivolumesoutputtypedef)
- [DescribeChapCredentialsInputRequestTypeDef](./type_defs.md#describechapcredentialsinputrequesttypedef)
- [DescribeChapCredentialsOutputTypeDef](./type_defs.md#describechapcredentialsoutputtypedef)
- [DescribeFileSystemAssociationsInputRequestTypeDef](./type_defs.md#describefilesystemassociationsinputrequesttypedef)
- [DescribeFileSystemAssociationsOutputTypeDef](./type_defs.md#describefilesystemassociationsoutputtypedef)
- [DescribeGatewayInformationInputRequestTypeDef](./type_defs.md#describegatewayinformationinputrequesttypedef)
- [DescribeGatewayInformationOutputTypeDef](./type_defs.md#describegatewayinformationoutputtypedef)
- [DescribeMaintenanceStartTimeInputRequestTypeDef](./type_defs.md#describemaintenancestarttimeinputrequesttypedef)
- [DescribeMaintenanceStartTimeOutputTypeDef](./type_defs.md#describemaintenancestarttimeoutputtypedef)
- [DescribeNFSFileSharesInputRequestTypeDef](./type_defs.md#describenfsfilesharesinputrequesttypedef)
- [DescribeNFSFileSharesOutputTypeDef](./type_defs.md#describenfsfilesharesoutputtypedef)
- [DescribeSMBFileSharesInputRequestTypeDef](./type_defs.md#describesmbfilesharesinputrequesttypedef)
- [DescribeSMBFileSharesOutputTypeDef](./type_defs.md#describesmbfilesharesoutputtypedef)
- [DescribeSMBSettingsInputRequestTypeDef](./type_defs.md#describesmbsettingsinputrequesttypedef)
- [DescribeSMBSettingsOutputTypeDef](./type_defs.md#describesmbsettingsoutputtypedef)
- [DescribeSnapshotScheduleInputRequestTypeDef](./type_defs.md#describesnapshotscheduleinputrequesttypedef)
- [DescribeSnapshotScheduleOutputTypeDef](./type_defs.md#describesnapshotscheduleoutputtypedef)
- [DescribeStorediSCSIVolumesInputRequestTypeDef](./type_defs.md#describestorediscsivolumesinputrequesttypedef)
- [DescribeStorediSCSIVolumesOutputTypeDef](./type_defs.md#describestorediscsivolumesoutputtypedef)
- [DescribeTapeArchivesInputRequestTypeDef](./type_defs.md#describetapearchivesinputrequesttypedef)
- [DescribeTapeArchivesOutputTypeDef](./type_defs.md#describetapearchivesoutputtypedef)
- [DescribeTapeRecoveryPointsInputRequestTypeDef](./type_defs.md#describetaperecoverypointsinputrequesttypedef)
- [DescribeTapeRecoveryPointsOutputTypeDef](./type_defs.md#describetaperecoverypointsoutputtypedef)
- [DescribeTapesInputRequestTypeDef](./type_defs.md#describetapesinputrequesttypedef)
- [DescribeTapesOutputTypeDef](./type_defs.md#describetapesoutputtypedef)
- [DescribeUploadBufferInputRequestTypeDef](./type_defs.md#describeuploadbufferinputrequesttypedef)
- [DescribeUploadBufferOutputTypeDef](./type_defs.md#describeuploadbufferoutputtypedef)
- [DescribeVTLDevicesInputRequestTypeDef](./type_defs.md#describevtldevicesinputrequesttypedef)
- [DescribeVTLDevicesOutputTypeDef](./type_defs.md#describevtldevicesoutputtypedef)
- [DescribeWorkingStorageInputRequestTypeDef](./type_defs.md#describeworkingstorageinputrequesttypedef)
- [DescribeWorkingStorageOutputTypeDef](./type_defs.md#describeworkingstorageoutputtypedef)
- [DetachVolumeInputRequestTypeDef](./type_defs.md#detachvolumeinputrequesttypedef)
- [DetachVolumeOutputTypeDef](./type_defs.md#detachvolumeoutputtypedef)
- [DeviceiSCSIAttributesTypeDef](./type_defs.md#deviceiscsiattributestypedef)
- [DisableGatewayInputRequestTypeDef](./type_defs.md#disablegatewayinputrequesttypedef)
- [DisableGatewayOutputTypeDef](./type_defs.md#disablegatewayoutputtypedef)
- [DisassociateFileSystemInputRequestTypeDef](./type_defs.md#disassociatefilesysteminputrequesttypedef)
- [DisassociateFileSystemOutputTypeDef](./type_defs.md#disassociatefilesystemoutputtypedef)
- [DiskTypeDef](./type_defs.md#disktypedef)
- [EndpointNetworkConfigurationTypeDef](./type_defs.md#endpointnetworkconfigurationtypedef)
- [FileShareInfoTypeDef](./type_defs.md#fileshareinfotypedef)
- [FileSystemAssociationInfoTypeDef](./type_defs.md#filesystemassociationinfotypedef)
- [FileSystemAssociationStatusDetailTypeDef](./type_defs.md#filesystemassociationstatusdetailtypedef)
- [FileSystemAssociationSummaryTypeDef](./type_defs.md#filesystemassociationsummarytypedef)
- [GatewayInfoTypeDef](./type_defs.md#gatewayinfotypedef)
- [JoinDomainInputRequestTypeDef](./type_defs.md#joindomaininputrequesttypedef)
- [JoinDomainOutputTypeDef](./type_defs.md#joindomainoutputtypedef)
- [ListAutomaticTapeCreationPoliciesInputRequestTypeDef](./type_defs.md#listautomatictapecreationpoliciesinputrequesttypedef)
- [ListAutomaticTapeCreationPoliciesOutputTypeDef](./type_defs.md#listautomatictapecreationpoliciesoutputtypedef)
- [ListFileSharesInputRequestTypeDef](./type_defs.md#listfilesharesinputrequesttypedef)
- [ListFileSharesOutputTypeDef](./type_defs.md#listfilesharesoutputtypedef)
- [ListFileSystemAssociationsInputRequestTypeDef](./type_defs.md#listfilesystemassociationsinputrequesttypedef)
- [ListFileSystemAssociationsOutputTypeDef](./type_defs.md#listfilesystemassociationsoutputtypedef)
- [ListGatewaysInputRequestTypeDef](./type_defs.md#listgatewaysinputrequesttypedef)
- [ListGatewaysOutputTypeDef](./type_defs.md#listgatewaysoutputtypedef)
- [ListLocalDisksInputRequestTypeDef](./type_defs.md#listlocaldisksinputrequesttypedef)
- [ListLocalDisksOutputTypeDef](./type_defs.md#listlocaldisksoutputtypedef)
- [ListTagsForResourceInputRequestTypeDef](./type_defs.md#listtagsforresourceinputrequesttypedef)
- [ListTagsForResourceOutputTypeDef](./type_defs.md#listtagsforresourceoutputtypedef)
- [ListTapePoolsInputRequestTypeDef](./type_defs.md#listtapepoolsinputrequesttypedef)
- [ListTapePoolsOutputTypeDef](./type_defs.md#listtapepoolsoutputtypedef)
- [ListTapesInputRequestTypeDef](./type_defs.md#listtapesinputrequesttypedef)
- [ListTapesOutputTypeDef](./type_defs.md#listtapesoutputtypedef)
- [ListVolumeInitiatorsInputRequestTypeDef](./type_defs.md#listvolumeinitiatorsinputrequesttypedef)
- [ListVolumeInitiatorsOutputTypeDef](./type_defs.md#listvolumeinitiatorsoutputtypedef)
- [ListVolumeRecoveryPointsInputRequestTypeDef](./type_defs.md#listvolumerecoverypointsinputrequesttypedef)
- [ListVolumeRecoveryPointsOutputTypeDef](./type_defs.md#listvolumerecoverypointsoutputtypedef)
- [ListVolumesInputRequestTypeDef](./type_defs.md#listvolumesinputrequesttypedef)
- [ListVolumesOutputTypeDef](./type_defs.md#listvolumesoutputtypedef)
- [NFSFileShareDefaultsTypeDef](./type_defs.md#nfsfilesharedefaultstypedef)
- [NFSFileShareInfoTypeDef](./type_defs.md#nfsfileshareinfotypedef)
- [NetworkInterfaceTypeDef](./type_defs.md#networkinterfacetypedef)
- [NotifyWhenUploadedInputRequestTypeDef](./type_defs.md#notifywhenuploadedinputrequesttypedef)
- [NotifyWhenUploadedOutputTypeDef](./type_defs.md#notifywhenuploadedoutputtypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PoolInfoTypeDef](./type_defs.md#poolinfotypedef)
- [RefreshCacheInputRequestTypeDef](./type_defs.md#refreshcacheinputrequesttypedef)
- [RefreshCacheOutputTypeDef](./type_defs.md#refreshcacheoutputtypedef)
- [RemoveTagsFromResourceInputRequestTypeDef](./type_defs.md#removetagsfromresourceinputrequesttypedef)
- [RemoveTagsFromResourceOutputTypeDef](./type_defs.md#removetagsfromresourceoutputtypedef)
- [ResetCacheInputRequestTypeDef](./type_defs.md#resetcacheinputrequesttypedef)
- [ResetCacheOutputTypeDef](./type_defs.md#resetcacheoutputtypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RetrieveTapeArchiveInputRequestTypeDef](./type_defs.md#retrievetapearchiveinputrequesttypedef)
- [RetrieveTapeArchiveOutputTypeDef](./type_defs.md#retrievetapearchiveoutputtypedef)
- [RetrieveTapeRecoveryPointInputRequestTypeDef](./type_defs.md#retrievetaperecoverypointinputrequesttypedef)
- [RetrieveTapeRecoveryPointOutputTypeDef](./type_defs.md#retrievetaperecoverypointoutputtypedef)
- [SMBFileShareInfoTypeDef](./type_defs.md#smbfileshareinfotypedef)
- [SMBLocalGroupsTypeDef](./type_defs.md#smblocalgroupstypedef)
- [SetLocalConsolePasswordInputRequestTypeDef](./type_defs.md#setlocalconsolepasswordinputrequesttypedef)
- [SetLocalConsolePasswordOutputTypeDef](./type_defs.md#setlocalconsolepasswordoutputtypedef)
- [SetSMBGuestPasswordInputRequestTypeDef](./type_defs.md#setsmbguestpasswordinputrequesttypedef)
- [SetSMBGuestPasswordOutputTypeDef](./type_defs.md#setsmbguestpasswordoutputtypedef)
- [ShutdownGatewayInputRequestTypeDef](./type_defs.md#shutdowngatewayinputrequesttypedef)
- [ShutdownGatewayOutputTypeDef](./type_defs.md#shutdowngatewayoutputtypedef)
- [StartAvailabilityMonitorTestInputRequestTypeDef](./type_defs.md#startavailabilitymonitortestinputrequesttypedef)
- [StartAvailabilityMonitorTestOutputTypeDef](./type_defs.md#startavailabilitymonitortestoutputtypedef)
- [StartGatewayInputRequestTypeDef](./type_defs.md#startgatewayinputrequesttypedef)
- [StartGatewayOutputTypeDef](./type_defs.md#startgatewayoutputtypedef)
- [StorediSCSIVolumeTypeDef](./type_defs.md#storediscsivolumetypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TapeArchiveTypeDef](./type_defs.md#tapearchivetypedef)
- [TapeInfoTypeDef](./type_defs.md#tapeinfotypedef)
- [TapeRecoveryPointInfoTypeDef](./type_defs.md#taperecoverypointinfotypedef)
- [TapeTypeDef](./type_defs.md#tapetypedef)
- [UpdateAutomaticTapeCreationPolicyInputRequestTypeDef](./type_defs.md#updateautomatictapecreationpolicyinputrequesttypedef)
- [UpdateAutomaticTapeCreationPolicyOutputTypeDef](./type_defs.md#updateautomatictapecreationpolicyoutputtypedef)
- [UpdateBandwidthRateLimitInputRequestTypeDef](./type_defs.md#updatebandwidthratelimitinputrequesttypedef)
- [UpdateBandwidthRateLimitOutputTypeDef](./type_defs.md#updatebandwidthratelimitoutputtypedef)
- [UpdateBandwidthRateLimitScheduleInputRequestTypeDef](./type_defs.md#updatebandwidthratelimitscheduleinputrequesttypedef)
- [UpdateBandwidthRateLimitScheduleOutputTypeDef](./type_defs.md#updatebandwidthratelimitscheduleoutputtypedef)
- [UpdateChapCredentialsInputRequestTypeDef](./type_defs.md#updatechapcredentialsinputrequesttypedef)
- [UpdateChapCredentialsOutputTypeDef](./type_defs.md#updatechapcredentialsoutputtypedef)
- [UpdateFileSystemAssociationInputRequestTypeDef](./type_defs.md#updatefilesystemassociationinputrequesttypedef)
- [UpdateFileSystemAssociationOutputTypeDef](./type_defs.md#updatefilesystemassociationoutputtypedef)
- [UpdateGatewayInformationInputRequestTypeDef](./type_defs.md#updategatewayinformationinputrequesttypedef)
- [UpdateGatewayInformationOutputTypeDef](./type_defs.md#updategatewayinformationoutputtypedef)
- [UpdateGatewaySoftwareNowInputRequestTypeDef](./type_defs.md#updategatewaysoftwarenowinputrequesttypedef)
- [UpdateGatewaySoftwareNowOutputTypeDef](./type_defs.md#updategatewaysoftwarenowoutputtypedef)
- [UpdateMaintenanceStartTimeInputRequestTypeDef](./type_defs.md#updatemaintenancestarttimeinputrequesttypedef)
- [UpdateMaintenanceStartTimeOutputTypeDef](./type_defs.md#updatemaintenancestarttimeoutputtypedef)
- [UpdateNFSFileShareInputRequestTypeDef](./type_defs.md#updatenfsfileshareinputrequesttypedef)
- [UpdateNFSFileShareOutputTypeDef](./type_defs.md#updatenfsfileshareoutputtypedef)
- [UpdateSMBFileShareInputRequestTypeDef](./type_defs.md#updatesmbfileshareinputrequesttypedef)
- [UpdateSMBFileShareOutputTypeDef](./type_defs.md#updatesmbfileshareoutputtypedef)
- [UpdateSMBFileShareVisibilityInputRequestTypeDef](./type_defs.md#updatesmbfilesharevisibilityinputrequesttypedef)
- [UpdateSMBFileShareVisibilityOutputTypeDef](./type_defs.md#updatesmbfilesharevisibilityoutputtypedef)
- [UpdateSMBLocalGroupsInputRequestTypeDef](./type_defs.md#updatesmblocalgroupsinputrequesttypedef)
- [UpdateSMBLocalGroupsOutputTypeDef](./type_defs.md#updatesmblocalgroupsoutputtypedef)
- [UpdateSMBSecurityStrategyInputRequestTypeDef](./type_defs.md#updatesmbsecuritystrategyinputrequesttypedef)
- [UpdateSMBSecurityStrategyOutputTypeDef](./type_defs.md#updatesmbsecuritystrategyoutputtypedef)
- [UpdateSnapshotScheduleInputRequestTypeDef](./type_defs.md#updatesnapshotscheduleinputrequesttypedef)
- [UpdateSnapshotScheduleOutputTypeDef](./type_defs.md#updatesnapshotscheduleoutputtypedef)
- [UpdateVTLDeviceTypeInputRequestTypeDef](./type_defs.md#updatevtldevicetypeinputrequesttypedef)
- [UpdateVTLDeviceTypeOutputTypeDef](./type_defs.md#updatevtldevicetypeoutputtypedef)
- [VTLDeviceTypeDef](./type_defs.md#vtldevicetypedef)
- [VolumeInfoTypeDef](./type_defs.md#volumeinfotypedef)
- [VolumeRecoveryPointInfoTypeDef](./type_defs.md#volumerecoverypointinfotypedef)
- [VolumeiSCSIAttributesTypeDef](./type_defs.md#volumeiscsiattributestypedef)
