<a id="type-annotations-for-aiobotocore-ssm-module"></a>

# Type annotations for aiobotocore SSM module

> [Index](..) > SSM

Auto-generated documentation for
[SSM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
type annotations stubs module
[types-aiobotocore-ssm](https://pypi.org/project/types-aiobotocore-ssm/).

- [Type annotations for aiobotocore SSM module](#type-annotations-for-aiobotocore-ssm-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [SSMClient](#ssmclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Waiters](#waiters)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `SSM`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `SSM` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[ssm]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[ssm]'

# standalone installation
python -m pip install types-aiobotocore-ssm
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-ssm
```

<a id="ssmclient"></a>

## SSMClient

Type annotations for `session.create_client("ssm")` as [SSMClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_ssm.client import SSMClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [add_tags_to_resource](./client.md#add_tags_to_resource)
- [associate_ops_item_related_item](./client.md#associate_ops_item_related_item)
- [can_paginate](./client.md#can_paginate)
- [cancel_command](./client.md#cancel_command)
- [cancel_maintenance_window_execution](./client.md#cancel_maintenance_window_execution)
- [create_activation](./client.md#create_activation)
- [create_association](./client.md#create_association)
- [create_association_batch](./client.md#create_association_batch)
- [create_document](./client.md#create_document)
- [create_maintenance_window](./client.md#create_maintenance_window)
- [create_ops_item](./client.md#create_ops_item)
- [create_ops_metadata](./client.md#create_ops_metadata)
- [create_patch_baseline](./client.md#create_patch_baseline)
- [create_resource_data_sync](./client.md#create_resource_data_sync)
- [delete_activation](./client.md#delete_activation)
- [delete_association](./client.md#delete_association)
- [delete_document](./client.md#delete_document)
- [delete_inventory](./client.md#delete_inventory)
- [delete_maintenance_window](./client.md#delete_maintenance_window)
- [delete_ops_metadata](./client.md#delete_ops_metadata)
- [delete_parameter](./client.md#delete_parameter)
- [delete_parameters](./client.md#delete_parameters)
- [delete_patch_baseline](./client.md#delete_patch_baseline)
- [delete_resource_data_sync](./client.md#delete_resource_data_sync)
- [deregister_managed_instance](./client.md#deregister_managed_instance)
- [deregister_patch_baseline_for_patch_group](./client.md#deregister_patch_baseline_for_patch_group)
- [deregister_target_from_maintenance_window](./client.md#deregister_target_from_maintenance_window)
- [deregister_task_from_maintenance_window](./client.md#deregister_task_from_maintenance_window)
- [describe_activations](./client.md#describe_activations)
- [describe_association](./client.md#describe_association)
- [describe_association_execution_targets](./client.md#describe_association_execution_targets)
- [describe_association_executions](./client.md#describe_association_executions)
- [describe_automation_executions](./client.md#describe_automation_executions)
- [describe_automation_step_executions](./client.md#describe_automation_step_executions)
- [describe_available_patches](./client.md#describe_available_patches)
- [describe_document](./client.md#describe_document)
- [describe_document_permission](./client.md#describe_document_permission)
- [describe_effective_instance_associations](./client.md#describe_effective_instance_associations)
- [describe_effective_patches_for_patch_baseline](./client.md#describe_effective_patches_for_patch_baseline)
- [describe_instance_associations_status](./client.md#describe_instance_associations_status)
- [describe_instance_information](./client.md#describe_instance_information)
- [describe_instance_patch_states](./client.md#describe_instance_patch_states)
- [describe_instance_patch_states_for_patch_group](./client.md#describe_instance_patch_states_for_patch_group)
- [describe_instance_patches](./client.md#describe_instance_patches)
- [describe_inventory_deletions](./client.md#describe_inventory_deletions)
- [describe_maintenance_window_execution_task_invocations](./client.md#describe_maintenance_window_execution_task_invocations)
- [describe_maintenance_window_execution_tasks](./client.md#describe_maintenance_window_execution_tasks)
- [describe_maintenance_window_executions](./client.md#describe_maintenance_window_executions)
- [describe_maintenance_window_schedule](./client.md#describe_maintenance_window_schedule)
- [describe_maintenance_window_targets](./client.md#describe_maintenance_window_targets)
- [describe_maintenance_window_tasks](./client.md#describe_maintenance_window_tasks)
- [describe_maintenance_windows](./client.md#describe_maintenance_windows)
- [describe_maintenance_windows_for_target](./client.md#describe_maintenance_windows_for_target)
- [describe_ops_items](./client.md#describe_ops_items)
- [describe_parameters](./client.md#describe_parameters)
- [describe_patch_baselines](./client.md#describe_patch_baselines)
- [describe_patch_group_state](./client.md#describe_patch_group_state)
- [describe_patch_groups](./client.md#describe_patch_groups)
- [describe_patch_properties](./client.md#describe_patch_properties)
- [describe_sessions](./client.md#describe_sessions)
- [disassociate_ops_item_related_item](./client.md#disassociate_ops_item_related_item)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_automation_execution](./client.md#get_automation_execution)
- [get_calendar_state](./client.md#get_calendar_state)
- [get_command_invocation](./client.md#get_command_invocation)
- [get_connection_status](./client.md#get_connection_status)
- [get_default_patch_baseline](./client.md#get_default_patch_baseline)
- [get_deployable_patch_snapshot_for_instance](./client.md#get_deployable_patch_snapshot_for_instance)
- [get_document](./client.md#get_document)
- [get_inventory](./client.md#get_inventory)
- [get_inventory_schema](./client.md#get_inventory_schema)
- [get_maintenance_window](./client.md#get_maintenance_window)
- [get_maintenance_window_execution](./client.md#get_maintenance_window_execution)
- [get_maintenance_window_execution_task](./client.md#get_maintenance_window_execution_task)
- [get_maintenance_window_execution_task_invocation](./client.md#get_maintenance_window_execution_task_invocation)
- [get_maintenance_window_task](./client.md#get_maintenance_window_task)
- [get_ops_item](./client.md#get_ops_item)
- [get_ops_metadata](./client.md#get_ops_metadata)
- [get_ops_summary](./client.md#get_ops_summary)
- [get_paginator](./client.md#get_paginator)
- [get_parameter](./client.md#get_parameter)
- [get_parameter_history](./client.md#get_parameter_history)
- [get_parameters](./client.md#get_parameters)
- [get_parameters_by_path](./client.md#get_parameters_by_path)
- [get_patch_baseline](./client.md#get_patch_baseline)
- [get_patch_baseline_for_patch_group](./client.md#get_patch_baseline_for_patch_group)
- [get_service_setting](./client.md#get_service_setting)
- [get_waiter](./client.md#get_waiter)
- [label_parameter_version](./client.md#label_parameter_version)
- [list_association_versions](./client.md#list_association_versions)
- [list_associations](./client.md#list_associations)
- [list_command_invocations](./client.md#list_command_invocations)
- [list_commands](./client.md#list_commands)
- [list_compliance_items](./client.md#list_compliance_items)
- [list_compliance_summaries](./client.md#list_compliance_summaries)
- [list_document_metadata_history](./client.md#list_document_metadata_history)
- [list_document_versions](./client.md#list_document_versions)
- [list_documents](./client.md#list_documents)
- [list_inventory_entries](./client.md#list_inventory_entries)
- [list_ops_item_events](./client.md#list_ops_item_events)
- [list_ops_item_related_items](./client.md#list_ops_item_related_items)
- [list_ops_metadata](./client.md#list_ops_metadata)
- [list_resource_compliance_summaries](./client.md#list_resource_compliance_summaries)
- [list_resource_data_sync](./client.md#list_resource_data_sync)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [modify_document_permission](./client.md#modify_document_permission)
- [put_compliance_items](./client.md#put_compliance_items)
- [put_inventory](./client.md#put_inventory)
- [put_parameter](./client.md#put_parameter)
- [register_default_patch_baseline](./client.md#register_default_patch_baseline)
- [register_patch_baseline_for_patch_group](./client.md#register_patch_baseline_for_patch_group)
- [register_target_with_maintenance_window](./client.md#register_target_with_maintenance_window)
- [register_task_with_maintenance_window](./client.md#register_task_with_maintenance_window)
- [remove_tags_from_resource](./client.md#remove_tags_from_resource)
- [reset_service_setting](./client.md#reset_service_setting)
- [resume_session](./client.md#resume_session)
- [send_automation_signal](./client.md#send_automation_signal)
- [send_command](./client.md#send_command)
- [start_associations_once](./client.md#start_associations_once)
- [start_automation_execution](./client.md#start_automation_execution)
- [start_change_request_execution](./client.md#start_change_request_execution)
- [start_session](./client.md#start_session)
- [stop_automation_execution](./client.md#stop_automation_execution)
- [terminate_session](./client.md#terminate_session)
- [unlabel_parameter_version](./client.md#unlabel_parameter_version)
- [update_association](./client.md#update_association)
- [update_association_status](./client.md#update_association_status)
- [update_document](./client.md#update_document)
- [update_document_default_version](./client.md#update_document_default_version)
- [update_document_metadata](./client.md#update_document_metadata)
- [update_maintenance_window](./client.md#update_maintenance_window)
- [update_maintenance_window_target](./client.md#update_maintenance_window_target)
- [update_maintenance_window_task](./client.md#update_maintenance_window_task)
- [update_managed_instance_role](./client.md#update_managed_instance_role)
- [update_ops_item](./client.md#update_ops_item)
- [update_ops_metadata](./client.md#update_ops_metadata)
- [update_patch_baseline](./client.md#update_patch_baseline)
- [update_resource_data_sync](./client.md#update_resource_data_sync)
- [update_service_setting](./client.md#update_service_setting)

<a id="exceptions"></a>

### Exceptions

SSMClient [exceptions](./client.md#exceptions)

- AlreadyExistsException
- AssociatedInstances
- AssociationAlreadyExists
- AssociationDoesNotExist
- AssociationExecutionDoesNotExist
- AssociationLimitExceeded
- AssociationVersionLimitExceeded
- AutomationDefinitionNotApprovedException
- AutomationDefinitionNotFoundException
- AutomationDefinitionVersionNotFoundException
- AutomationExecutionLimitExceededException
- AutomationExecutionNotFoundException
- AutomationStepNotFoundException
- ClientError
- ComplianceTypeCountLimitExceededException
- CustomSchemaCountLimitExceededException
- DocumentAlreadyExists
- DocumentLimitExceeded
- DocumentPermissionLimit
- DocumentVersionLimitExceeded
- DoesNotExistException
- DuplicateDocumentContent
- DuplicateDocumentVersionName
- DuplicateInstanceId
- FeatureNotAvailableException
- HierarchyLevelLimitExceededException
- HierarchyTypeMismatchException
- IdempotentParameterMismatch
- IncompatiblePolicyException
- InternalServerError
- InvalidActivation
- InvalidActivationId
- InvalidAggregatorException
- InvalidAllowedPatternException
- InvalidAssociation
- InvalidAssociationVersion
- InvalidAutomationExecutionParametersException
- InvalidAutomationSignalException
- InvalidAutomationStatusUpdateException
- InvalidCommandId
- InvalidDeleteInventoryParametersException
- InvalidDeletionIdException
- InvalidDocument
- InvalidDocumentContent
- InvalidDocumentOperation
- InvalidDocumentSchemaVersion
- InvalidDocumentType
- InvalidDocumentVersion
- InvalidFilter
- InvalidFilterKey
- InvalidFilterOption
- InvalidFilterValue
- InvalidInstanceId
- InvalidInstanceInformationFilterValue
- InvalidInventoryGroupException
- InvalidInventoryItemContextException
- InvalidInventoryRequestException
- InvalidItemContentException
- InvalidKeyId
- InvalidNextToken
- InvalidNotificationConfig
- InvalidOptionException
- InvalidOutputFolder
- InvalidOutputLocation
- InvalidParameters
- InvalidPermissionType
- InvalidPluginName
- InvalidPolicyAttributeException
- InvalidPolicyTypeException
- InvalidResourceId
- InvalidResourceType
- InvalidResultAttributeException
- InvalidRole
- InvalidSchedule
- InvalidTarget
- InvalidTypeNameException
- InvalidUpdate
- InvocationDoesNotExist
- ItemContentMismatchException
- ItemSizeLimitExceededException
- MaxDocumentSizeExceeded
- OpsItemAlreadyExistsException
- OpsItemInvalidParameterException
- OpsItemLimitExceededException
- OpsItemNotFoundException
- OpsItemRelatedItemAlreadyExistsException
- OpsItemRelatedItemAssociationNotFoundException
- OpsMetadataAlreadyExistsException
- OpsMetadataInvalidArgumentException
- OpsMetadataKeyLimitExceededException
- OpsMetadataLimitExceededException
- OpsMetadataNotFoundException
- OpsMetadataTooManyUpdatesException
- ParameterAlreadyExists
- ParameterLimitExceeded
- ParameterMaxVersionLimitExceeded
- ParameterNotFound
- ParameterPatternMismatchException
- ParameterVersionLabelLimitExceeded
- ParameterVersionNotFound
- PoliciesLimitExceededException
- ResourceDataSyncAlreadyExistsException
- ResourceDataSyncConflictException
- ResourceDataSyncCountExceededException
- ResourceDataSyncInvalidConfigurationException
- ResourceDataSyncNotFoundException
- ResourceInUseException
- ResourceLimitExceededException
- ServiceSettingNotFound
- StatusUnchanged
- SubTypeCountLimitExceededException
- TargetInUseException
- TargetNotConnected
- TooManyTagsError
- TooManyUpdates
- TotalSizeLimitExceededException
- UnsupportedCalendarException
- UnsupportedFeatureRequiredException
- UnsupportedInventoryItemContextException
- UnsupportedInventorySchemaVersionException
- UnsupportedOperatingSystem
- UnsupportedParameterType
- UnsupportedPlatformType

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("ssm").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_ssm.paginator import DescribeActivationsPaginator, ...
```

- [DescribeActivationsPaginator](./paginators.md#describeactivationspaginator)
- [DescribeAssociationExecutionTargetsPaginator](./paginators.md#describeassociationexecutiontargetspaginator)
- [DescribeAssociationExecutionsPaginator](./paginators.md#describeassociationexecutionspaginator)
- [DescribeAutomationExecutionsPaginator](./paginators.md#describeautomationexecutionspaginator)
- [DescribeAutomationStepExecutionsPaginator](./paginators.md#describeautomationstepexecutionspaginator)
- [DescribeAvailablePatchesPaginator](./paginators.md#describeavailablepatchespaginator)
- [DescribeEffectiveInstanceAssociationsPaginator](./paginators.md#describeeffectiveinstanceassociationspaginator)
- [DescribeEffectivePatchesForPatchBaselinePaginator](./paginators.md#describeeffectivepatchesforpatchbaselinepaginator)
- [DescribeInstanceAssociationsStatusPaginator](./paginators.md#describeinstanceassociationsstatuspaginator)
- [DescribeInstanceInformationPaginator](./paginators.md#describeinstanceinformationpaginator)
- [DescribeInstancePatchStatesPaginator](./paginators.md#describeinstancepatchstatespaginator)
- [DescribeInstancePatchStatesForPatchGroupPaginator](./paginators.md#describeinstancepatchstatesforpatchgrouppaginator)
- [DescribeInstancePatchesPaginator](./paginators.md#describeinstancepatchespaginator)
- [DescribeInventoryDeletionsPaginator](./paginators.md#describeinventorydeletionspaginator)
- [DescribeMaintenanceWindowExecutionTaskInvocationsPaginator](./paginators.md#describemaintenancewindowexecutiontaskinvocationspaginator)
- [DescribeMaintenanceWindowExecutionTasksPaginator](./paginators.md#describemaintenancewindowexecutiontaskspaginator)
- [DescribeMaintenanceWindowExecutionsPaginator](./paginators.md#describemaintenancewindowexecutionspaginator)
- [DescribeMaintenanceWindowSchedulePaginator](./paginators.md#describemaintenancewindowschedulepaginator)
- [DescribeMaintenanceWindowTargetsPaginator](./paginators.md#describemaintenancewindowtargetspaginator)
- [DescribeMaintenanceWindowTasksPaginator](./paginators.md#describemaintenancewindowtaskspaginator)
- [DescribeMaintenanceWindowsPaginator](./paginators.md#describemaintenancewindowspaginator)
- [DescribeMaintenanceWindowsForTargetPaginator](./paginators.md#describemaintenancewindowsfortargetpaginator)
- [DescribeOpsItemsPaginator](./paginators.md#describeopsitemspaginator)
- [DescribeParametersPaginator](./paginators.md#describeparameterspaginator)
- [DescribePatchBaselinesPaginator](./paginators.md#describepatchbaselinespaginator)
- [DescribePatchGroupsPaginator](./paginators.md#describepatchgroupspaginator)
- [DescribePatchPropertiesPaginator](./paginators.md#describepatchpropertiespaginator)
- [DescribeSessionsPaginator](./paginators.md#describesessionspaginator)
- [GetInventoryPaginator](./paginators.md#getinventorypaginator)
- [GetInventorySchemaPaginator](./paginators.md#getinventoryschemapaginator)
- [GetOpsSummaryPaginator](./paginators.md#getopssummarypaginator)
- [GetParameterHistoryPaginator](./paginators.md#getparameterhistorypaginator)
- [GetParametersByPathPaginator](./paginators.md#getparametersbypathpaginator)
- [ListAssociationVersionsPaginator](./paginators.md#listassociationversionspaginator)
- [ListAssociationsPaginator](./paginators.md#listassociationspaginator)
- [ListCommandInvocationsPaginator](./paginators.md#listcommandinvocationspaginator)
- [ListCommandsPaginator](./paginators.md#listcommandspaginator)
- [ListComplianceItemsPaginator](./paginators.md#listcomplianceitemspaginator)
- [ListComplianceSummariesPaginator](./paginators.md#listcompliancesummariespaginator)
- [ListDocumentVersionsPaginator](./paginators.md#listdocumentversionspaginator)
- [ListDocumentsPaginator](./paginators.md#listdocumentspaginator)
- [ListOpsItemEventsPaginator](./paginators.md#listopsitemeventspaginator)
- [ListOpsItemRelatedItemsPaginator](./paginators.md#listopsitemrelateditemspaginator)
- [ListOpsMetadataPaginator](./paginators.md#listopsmetadatapaginator)
- [ListResourceComplianceSummariesPaginator](./paginators.md#listresourcecompliancesummariespaginator)
- [ListResourceDataSyncPaginator](./paginators.md#listresourcedatasyncpaginator)

<a id="waiters"></a>

## Waiters

Type annotations for [waiters](./waiters.md) from
`boto3.client("ssm").get_waiter("...")`.

Can be used directly:

```python
from types_aiobotocore_ssm.waiter import CommandExecutedWaiter, ...
```

- [CommandExecutedWaiter](./waiters.md#commandexecutedwaiter)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_ssm.literals import AssociationComplianceSeverityType, ...
```

- [AssociationComplianceSeverityType](./literals.md#associationcomplianceseveritytype)
- [AssociationExecutionFilterKeyType](./literals.md#associationexecutionfilterkeytype)
- [AssociationExecutionTargetsFilterKeyType](./literals.md#associationexecutiontargetsfilterkeytype)
- [AssociationFilterKeyType](./literals.md#associationfilterkeytype)
- [AssociationFilterOperatorTypeType](./literals.md#associationfilteroperatortypetype)
- [AssociationStatusNameType](./literals.md#associationstatusnametype)
- [AssociationSyncComplianceType](./literals.md#associationsynccompliancetype)
- [AttachmentHashTypeType](./literals.md#attachmenthashtypetype)
- [AttachmentsSourceKeyType](./literals.md#attachmentssourcekeytype)
- [AutomationExecutionFilterKeyType](./literals.md#automationexecutionfilterkeytype)
- [AutomationExecutionStatusType](./literals.md#automationexecutionstatustype)
- [AutomationSubtypeType](./literals.md#automationsubtypetype)
- [AutomationTypeType](./literals.md#automationtypetype)
- [CalendarStateType](./literals.md#calendarstatetype)
- [CommandExecutedWaiterName](./literals.md#commandexecutedwaitername)
- [CommandFilterKeyType](./literals.md#commandfilterkeytype)
- [CommandInvocationStatusType](./literals.md#commandinvocationstatustype)
- [CommandPluginStatusType](./literals.md#commandpluginstatustype)
- [CommandStatusType](./literals.md#commandstatustype)
- [ComplianceQueryOperatorTypeType](./literals.md#compliancequeryoperatortypetype)
- [ComplianceSeverityType](./literals.md#complianceseveritytype)
- [ComplianceStatusType](./literals.md#compliancestatustype)
- [ComplianceUploadTypeType](./literals.md#complianceuploadtypetype)
- [ConnectionStatusType](./literals.md#connectionstatustype)
- [DescribeActivationsFilterKeysType](./literals.md#describeactivationsfilterkeystype)
- [DescribeActivationsPaginatorName](./literals.md#describeactivationspaginatorname)
- [DescribeAssociationExecutionTargetsPaginatorName](./literals.md#describeassociationexecutiontargetspaginatorname)
- [DescribeAssociationExecutionsPaginatorName](./literals.md#describeassociationexecutionspaginatorname)
- [DescribeAutomationExecutionsPaginatorName](./literals.md#describeautomationexecutionspaginatorname)
- [DescribeAutomationStepExecutionsPaginatorName](./literals.md#describeautomationstepexecutionspaginatorname)
- [DescribeAvailablePatchesPaginatorName](./literals.md#describeavailablepatchespaginatorname)
- [DescribeEffectiveInstanceAssociationsPaginatorName](./literals.md#describeeffectiveinstanceassociationspaginatorname)
- [DescribeEffectivePatchesForPatchBaselinePaginatorName](./literals.md#describeeffectivepatchesforpatchbaselinepaginatorname)
- [DescribeInstanceAssociationsStatusPaginatorName](./literals.md#describeinstanceassociationsstatuspaginatorname)
- [DescribeInstanceInformationPaginatorName](./literals.md#describeinstanceinformationpaginatorname)
- [DescribeInstancePatchStatesForPatchGroupPaginatorName](./literals.md#describeinstancepatchstatesforpatchgrouppaginatorname)
- [DescribeInstancePatchStatesPaginatorName](./literals.md#describeinstancepatchstatespaginatorname)
- [DescribeInstancePatchesPaginatorName](./literals.md#describeinstancepatchespaginatorname)
- [DescribeInventoryDeletionsPaginatorName](./literals.md#describeinventorydeletionspaginatorname)
- [DescribeMaintenanceWindowExecutionTaskInvocationsPaginatorName](./literals.md#describemaintenancewindowexecutiontaskinvocationspaginatorname)
- [DescribeMaintenanceWindowExecutionTasksPaginatorName](./literals.md#describemaintenancewindowexecutiontaskspaginatorname)
- [DescribeMaintenanceWindowExecutionsPaginatorName](./literals.md#describemaintenancewindowexecutionspaginatorname)
- [DescribeMaintenanceWindowSchedulePaginatorName](./literals.md#describemaintenancewindowschedulepaginatorname)
- [DescribeMaintenanceWindowTargetsPaginatorName](./literals.md#describemaintenancewindowtargetspaginatorname)
- [DescribeMaintenanceWindowTasksPaginatorName](./literals.md#describemaintenancewindowtaskspaginatorname)
- [DescribeMaintenanceWindowsForTargetPaginatorName](./literals.md#describemaintenancewindowsfortargetpaginatorname)
- [DescribeMaintenanceWindowsPaginatorName](./literals.md#describemaintenancewindowspaginatorname)
- [DescribeOpsItemsPaginatorName](./literals.md#describeopsitemspaginatorname)
- [DescribeParametersPaginatorName](./literals.md#describeparameterspaginatorname)
- [DescribePatchBaselinesPaginatorName](./literals.md#describepatchbaselinespaginatorname)
- [DescribePatchGroupsPaginatorName](./literals.md#describepatchgroupspaginatorname)
- [DescribePatchPropertiesPaginatorName](./literals.md#describepatchpropertiespaginatorname)
- [DescribeSessionsPaginatorName](./literals.md#describesessionspaginatorname)
- [DocumentFilterKeyType](./literals.md#documentfilterkeytype)
- [DocumentFormatType](./literals.md#documentformattype)
- [DocumentHashTypeType](./literals.md#documenthashtypetype)
- [DocumentMetadataEnumType](./literals.md#documentmetadataenumtype)
- [DocumentParameterTypeType](./literals.md#documentparametertypetype)
- [DocumentPermissionTypeType](./literals.md#documentpermissiontypetype)
- [DocumentReviewActionType](./literals.md#documentreviewactiontype)
- [DocumentReviewCommentTypeType](./literals.md#documentreviewcommenttypetype)
- [DocumentStatusType](./literals.md#documentstatustype)
- [DocumentTypeType](./literals.md#documenttypetype)
- [ExecutionModeType](./literals.md#executionmodetype)
- [FaultType](./literals.md#faulttype)
- [GetInventoryPaginatorName](./literals.md#getinventorypaginatorname)
- [GetInventorySchemaPaginatorName](./literals.md#getinventoryschemapaginatorname)
- [GetOpsSummaryPaginatorName](./literals.md#getopssummarypaginatorname)
- [GetParameterHistoryPaginatorName](./literals.md#getparameterhistorypaginatorname)
- [GetParametersByPathPaginatorName](./literals.md#getparametersbypathpaginatorname)
- [InstanceInformationFilterKeyType](./literals.md#instanceinformationfilterkeytype)
- [InstancePatchStateOperatorTypeType](./literals.md#instancepatchstateoperatortypetype)
- [InventoryAttributeDataTypeType](./literals.md#inventoryattributedatatypetype)
- [InventoryDeletionStatusType](./literals.md#inventorydeletionstatustype)
- [InventoryQueryOperatorTypeType](./literals.md#inventoryqueryoperatortypetype)
- [InventorySchemaDeleteOptionType](./literals.md#inventoryschemadeleteoptiontype)
- [LastResourceDataSyncStatusType](./literals.md#lastresourcedatasyncstatustype)
- [ListAssociationVersionsPaginatorName](./literals.md#listassociationversionspaginatorname)
- [ListAssociationsPaginatorName](./literals.md#listassociationspaginatorname)
- [ListCommandInvocationsPaginatorName](./literals.md#listcommandinvocationspaginatorname)
- [ListCommandsPaginatorName](./literals.md#listcommandspaginatorname)
- [ListComplianceItemsPaginatorName](./literals.md#listcomplianceitemspaginatorname)
- [ListComplianceSummariesPaginatorName](./literals.md#listcompliancesummariespaginatorname)
- [ListDocumentVersionsPaginatorName](./literals.md#listdocumentversionspaginatorname)
- [ListDocumentsPaginatorName](./literals.md#listdocumentspaginatorname)
- [ListOpsItemEventsPaginatorName](./literals.md#listopsitemeventspaginatorname)
- [ListOpsItemRelatedItemsPaginatorName](./literals.md#listopsitemrelateditemspaginatorname)
- [ListOpsMetadataPaginatorName](./literals.md#listopsmetadatapaginatorname)
- [ListResourceComplianceSummariesPaginatorName](./literals.md#listresourcecompliancesummariespaginatorname)
- [ListResourceDataSyncPaginatorName](./literals.md#listresourcedatasyncpaginatorname)
- [MaintenanceWindowExecutionStatusType](./literals.md#maintenancewindowexecutionstatustype)
- [MaintenanceWindowResourceTypeType](./literals.md#maintenancewindowresourcetypetype)
- [MaintenanceWindowTaskCutoffBehaviorType](./literals.md#maintenancewindowtaskcutoffbehaviortype)
- [MaintenanceWindowTaskTypeType](./literals.md#maintenancewindowtasktypetype)
- [NotificationEventType](./literals.md#notificationeventtype)
- [NotificationTypeType](./literals.md#notificationtypetype)
- [OperatingSystemType](./literals.md#operatingsystemtype)
- [OpsFilterOperatorTypeType](./literals.md#opsfilteroperatortypetype)
- [OpsItemDataTypeType](./literals.md#opsitemdatatypetype)
- [OpsItemEventFilterKeyType](./literals.md#opsitemeventfilterkeytype)
- [OpsItemEventFilterOperatorType](./literals.md#opsitemeventfilteroperatortype)
- [OpsItemFilterKeyType](./literals.md#opsitemfilterkeytype)
- [OpsItemFilterOperatorType](./literals.md#opsitemfilteroperatortype)
- [OpsItemRelatedItemsFilterKeyType](./literals.md#opsitemrelateditemsfilterkeytype)
- [OpsItemRelatedItemsFilterOperatorType](./literals.md#opsitemrelateditemsfilteroperatortype)
- [OpsItemStatusType](./literals.md#opsitemstatustype)
- [ParameterTierType](./literals.md#parametertiertype)
- [ParameterTypeType](./literals.md#parametertypetype)
- [ParametersFilterKeyType](./literals.md#parametersfilterkeytype)
- [PatchActionType](./literals.md#patchactiontype)
- [PatchComplianceDataStateType](./literals.md#patchcompliancedatastatetype)
- [PatchComplianceLevelType](./literals.md#patchcomplianceleveltype)
- [PatchDeploymentStatusType](./literals.md#patchdeploymentstatustype)
- [PatchFilterKeyType](./literals.md#patchfilterkeytype)
- [PatchOperationTypeType](./literals.md#patchoperationtypetype)
- [PatchPropertyType](./literals.md#patchpropertytype)
- [PatchSetType](./literals.md#patchsettype)
- [PingStatusType](./literals.md#pingstatustype)
- [PlatformTypeType](./literals.md#platformtypetype)
- [RebootOptionType](./literals.md#rebootoptiontype)
- [ResourceDataSyncS3FormatType](./literals.md#resourcedatasyncs3formattype)
- [ResourceTypeForTaggingType](./literals.md#resourcetypefortaggingtype)
- [ResourceTypeType](./literals.md#resourcetypetype)
- [ReviewStatusType](./literals.md#reviewstatustype)
- [SessionFilterKeyType](./literals.md#sessionfilterkeytype)
- [SessionStateType](./literals.md#sessionstatetype)
- [SessionStatusType](./literals.md#sessionstatustype)
- [SignalTypeType](./literals.md#signaltypetype)
- [SourceTypeType](./literals.md#sourcetypetype)
- [StepExecutionFilterKeyType](./literals.md#stepexecutionfilterkeytype)
- [StopTypeType](./literals.md#stoptypetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)
- [WaiterName](./literals.md#waitername)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_ssm.type_defs import AccountSharingInfoTypeDef, ...
```

- [AccountSharingInfoTypeDef](./type_defs.md#accountsharinginfotypedef)
- [ActivationTypeDef](./type_defs.md#activationtypedef)
- [AddTagsToResourceRequestRequestTypeDef](./type_defs.md#addtagstoresourcerequestrequesttypedef)
- [AssociateOpsItemRelatedItemRequestRequestTypeDef](./type_defs.md#associateopsitemrelateditemrequestrequesttypedef)
- [AssociateOpsItemRelatedItemResponseTypeDef](./type_defs.md#associateopsitemrelateditemresponsetypedef)
- [AssociationDescriptionTypeDef](./type_defs.md#associationdescriptiontypedef)
- [AssociationExecutionFilterTypeDef](./type_defs.md#associationexecutionfiltertypedef)
- [AssociationExecutionTargetTypeDef](./type_defs.md#associationexecutiontargettypedef)
- [AssociationExecutionTargetsFilterTypeDef](./type_defs.md#associationexecutiontargetsfiltertypedef)
- [AssociationExecutionTypeDef](./type_defs.md#associationexecutiontypedef)
- [AssociationFilterTypeDef](./type_defs.md#associationfiltertypedef)
- [AssociationOverviewTypeDef](./type_defs.md#associationoverviewtypedef)
- [AssociationStatusTypeDef](./type_defs.md#associationstatustypedef)
- [AssociationTypeDef](./type_defs.md#associationtypedef)
- [AssociationVersionInfoTypeDef](./type_defs.md#associationversioninfotypedef)
- [AttachmentContentTypeDef](./type_defs.md#attachmentcontenttypedef)
- [AttachmentInformationTypeDef](./type_defs.md#attachmentinformationtypedef)
- [AttachmentsSourceTypeDef](./type_defs.md#attachmentssourcetypedef)
- [AutomationExecutionFilterTypeDef](./type_defs.md#automationexecutionfiltertypedef)
- [AutomationExecutionMetadataTypeDef](./type_defs.md#automationexecutionmetadatatypedef)
- [AutomationExecutionTypeDef](./type_defs.md#automationexecutiontypedef)
- [BaselineOverrideTypeDef](./type_defs.md#baselineoverridetypedef)
- [CancelCommandRequestRequestTypeDef](./type_defs.md#cancelcommandrequestrequesttypedef)
- [CancelMaintenanceWindowExecutionRequestRequestTypeDef](./type_defs.md#cancelmaintenancewindowexecutionrequestrequesttypedef)
- [CancelMaintenanceWindowExecutionResultTypeDef](./type_defs.md#cancelmaintenancewindowexecutionresulttypedef)
- [CloudWatchOutputConfigTypeDef](./type_defs.md#cloudwatchoutputconfigtypedef)
- [CommandFilterTypeDef](./type_defs.md#commandfiltertypedef)
- [CommandInvocationTypeDef](./type_defs.md#commandinvocationtypedef)
- [CommandPluginTypeDef](./type_defs.md#commandplugintypedef)
- [CommandTypeDef](./type_defs.md#commandtypedef)
- [ComplianceExecutionSummaryTypeDef](./type_defs.md#complianceexecutionsummarytypedef)
- [ComplianceItemEntryTypeDef](./type_defs.md#complianceitementrytypedef)
- [ComplianceItemTypeDef](./type_defs.md#complianceitemtypedef)
- [ComplianceStringFilterTypeDef](./type_defs.md#compliancestringfiltertypedef)
- [ComplianceSummaryItemTypeDef](./type_defs.md#compliancesummaryitemtypedef)
- [CompliantSummaryTypeDef](./type_defs.md#compliantsummarytypedef)
- [CreateActivationRequestRequestTypeDef](./type_defs.md#createactivationrequestrequesttypedef)
- [CreateActivationResultTypeDef](./type_defs.md#createactivationresulttypedef)
- [CreateAssociationBatchRequestEntryTypeDef](./type_defs.md#createassociationbatchrequestentrytypedef)
- [CreateAssociationBatchRequestRequestTypeDef](./type_defs.md#createassociationbatchrequestrequesttypedef)
- [CreateAssociationBatchResultTypeDef](./type_defs.md#createassociationbatchresulttypedef)
- [CreateAssociationRequestRequestTypeDef](./type_defs.md#createassociationrequestrequesttypedef)
- [CreateAssociationResultTypeDef](./type_defs.md#createassociationresulttypedef)
- [CreateDocumentRequestRequestTypeDef](./type_defs.md#createdocumentrequestrequesttypedef)
- [CreateDocumentResultTypeDef](./type_defs.md#createdocumentresulttypedef)
- [CreateMaintenanceWindowRequestRequestTypeDef](./type_defs.md#createmaintenancewindowrequestrequesttypedef)
- [CreateMaintenanceWindowResultTypeDef](./type_defs.md#createmaintenancewindowresulttypedef)
- [CreateOpsItemRequestRequestTypeDef](./type_defs.md#createopsitemrequestrequesttypedef)
- [CreateOpsItemResponseTypeDef](./type_defs.md#createopsitemresponsetypedef)
- [CreateOpsMetadataRequestRequestTypeDef](./type_defs.md#createopsmetadatarequestrequesttypedef)
- [CreateOpsMetadataResultTypeDef](./type_defs.md#createopsmetadataresulttypedef)
- [CreatePatchBaselineRequestRequestTypeDef](./type_defs.md#createpatchbaselinerequestrequesttypedef)
- [CreatePatchBaselineResultTypeDef](./type_defs.md#createpatchbaselineresulttypedef)
- [CreateResourceDataSyncRequestRequestTypeDef](./type_defs.md#createresourcedatasyncrequestrequesttypedef)
- [DeleteActivationRequestRequestTypeDef](./type_defs.md#deleteactivationrequestrequesttypedef)
- [DeleteAssociationRequestRequestTypeDef](./type_defs.md#deleteassociationrequestrequesttypedef)
- [DeleteDocumentRequestRequestTypeDef](./type_defs.md#deletedocumentrequestrequesttypedef)
- [DeleteInventoryRequestRequestTypeDef](./type_defs.md#deleteinventoryrequestrequesttypedef)
- [DeleteInventoryResultTypeDef](./type_defs.md#deleteinventoryresulttypedef)
- [DeleteMaintenanceWindowRequestRequestTypeDef](./type_defs.md#deletemaintenancewindowrequestrequesttypedef)
- [DeleteMaintenanceWindowResultTypeDef](./type_defs.md#deletemaintenancewindowresulttypedef)
- [DeleteOpsMetadataRequestRequestTypeDef](./type_defs.md#deleteopsmetadatarequestrequesttypedef)
- [DeleteParameterRequestRequestTypeDef](./type_defs.md#deleteparameterrequestrequesttypedef)
- [DeleteParametersRequestRequestTypeDef](./type_defs.md#deleteparametersrequestrequesttypedef)
- [DeleteParametersResultTypeDef](./type_defs.md#deleteparametersresulttypedef)
- [DeletePatchBaselineRequestRequestTypeDef](./type_defs.md#deletepatchbaselinerequestrequesttypedef)
- [DeletePatchBaselineResultTypeDef](./type_defs.md#deletepatchbaselineresulttypedef)
- [DeleteResourceDataSyncRequestRequestTypeDef](./type_defs.md#deleteresourcedatasyncrequestrequesttypedef)
- [DeregisterManagedInstanceRequestRequestTypeDef](./type_defs.md#deregistermanagedinstancerequestrequesttypedef)
- [DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef](./type_defs.md#deregisterpatchbaselineforpatchgrouprequestrequesttypedef)
- [DeregisterPatchBaselineForPatchGroupResultTypeDef](./type_defs.md#deregisterpatchbaselineforpatchgroupresulttypedef)
- [DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef](./type_defs.md#deregistertargetfrommaintenancewindowrequestrequesttypedef)
- [DeregisterTargetFromMaintenanceWindowResultTypeDef](./type_defs.md#deregistertargetfrommaintenancewindowresulttypedef)
- [DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef](./type_defs.md#deregistertaskfrommaintenancewindowrequestrequesttypedef)
- [DeregisterTaskFromMaintenanceWindowResultTypeDef](./type_defs.md#deregistertaskfrommaintenancewindowresulttypedef)
- [DescribeActivationsFilterTypeDef](./type_defs.md#describeactivationsfiltertypedef)
- [DescribeActivationsRequestRequestTypeDef](./type_defs.md#describeactivationsrequestrequesttypedef)
- [DescribeActivationsResultTypeDef](./type_defs.md#describeactivationsresulttypedef)
- [DescribeAssociationExecutionTargetsRequestRequestTypeDef](./type_defs.md#describeassociationexecutiontargetsrequestrequesttypedef)
- [DescribeAssociationExecutionTargetsResultTypeDef](./type_defs.md#describeassociationexecutiontargetsresulttypedef)
- [DescribeAssociationExecutionsRequestRequestTypeDef](./type_defs.md#describeassociationexecutionsrequestrequesttypedef)
- [DescribeAssociationExecutionsResultTypeDef](./type_defs.md#describeassociationexecutionsresulttypedef)
- [DescribeAssociationRequestRequestTypeDef](./type_defs.md#describeassociationrequestrequesttypedef)
- [DescribeAssociationResultTypeDef](./type_defs.md#describeassociationresulttypedef)
- [DescribeAutomationExecutionsRequestRequestTypeDef](./type_defs.md#describeautomationexecutionsrequestrequesttypedef)
- [DescribeAutomationExecutionsResultTypeDef](./type_defs.md#describeautomationexecutionsresulttypedef)
- [DescribeAutomationStepExecutionsRequestRequestTypeDef](./type_defs.md#describeautomationstepexecutionsrequestrequesttypedef)
- [DescribeAutomationStepExecutionsResultTypeDef](./type_defs.md#describeautomationstepexecutionsresulttypedef)
- [DescribeAvailablePatchesRequestRequestTypeDef](./type_defs.md#describeavailablepatchesrequestrequesttypedef)
- [DescribeAvailablePatchesResultTypeDef](./type_defs.md#describeavailablepatchesresulttypedef)
- [DescribeDocumentPermissionRequestRequestTypeDef](./type_defs.md#describedocumentpermissionrequestrequesttypedef)
- [DescribeDocumentPermissionResponseTypeDef](./type_defs.md#describedocumentpermissionresponsetypedef)
- [DescribeDocumentRequestRequestTypeDef](./type_defs.md#describedocumentrequestrequesttypedef)
- [DescribeDocumentResultTypeDef](./type_defs.md#describedocumentresulttypedef)
- [DescribeEffectiveInstanceAssociationsRequestRequestTypeDef](./type_defs.md#describeeffectiveinstanceassociationsrequestrequesttypedef)
- [DescribeEffectiveInstanceAssociationsResultTypeDef](./type_defs.md#describeeffectiveinstanceassociationsresulttypedef)
- [DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef](./type_defs.md#describeeffectivepatchesforpatchbaselinerequestrequesttypedef)
- [DescribeEffectivePatchesForPatchBaselineResultTypeDef](./type_defs.md#describeeffectivepatchesforpatchbaselineresulttypedef)
- [DescribeInstanceAssociationsStatusRequestRequestTypeDef](./type_defs.md#describeinstanceassociationsstatusrequestrequesttypedef)
- [DescribeInstanceAssociationsStatusResultTypeDef](./type_defs.md#describeinstanceassociationsstatusresulttypedef)
- [DescribeInstanceInformationRequestRequestTypeDef](./type_defs.md#describeinstanceinformationrequestrequesttypedef)
- [DescribeInstanceInformationResultTypeDef](./type_defs.md#describeinstanceinformationresulttypedef)
- [DescribeInstancePatchStatesForPatchGroupRequestRequestTypeDef](./type_defs.md#describeinstancepatchstatesforpatchgrouprequestrequesttypedef)
- [DescribeInstancePatchStatesForPatchGroupResultTypeDef](./type_defs.md#describeinstancepatchstatesforpatchgroupresulttypedef)
- [DescribeInstancePatchStatesRequestRequestTypeDef](./type_defs.md#describeinstancepatchstatesrequestrequesttypedef)
- [DescribeInstancePatchStatesResultTypeDef](./type_defs.md#describeinstancepatchstatesresulttypedef)
- [DescribeInstancePatchesRequestRequestTypeDef](./type_defs.md#describeinstancepatchesrequestrequesttypedef)
- [DescribeInstancePatchesResultTypeDef](./type_defs.md#describeinstancepatchesresulttypedef)
- [DescribeInventoryDeletionsRequestRequestTypeDef](./type_defs.md#describeinventorydeletionsrequestrequesttypedef)
- [DescribeInventoryDeletionsResultTypeDef](./type_defs.md#describeinventorydeletionsresulttypedef)
- [DescribeMaintenanceWindowExecutionTaskInvocationsRequestRequestTypeDef](./type_defs.md#describemaintenancewindowexecutiontaskinvocationsrequestrequesttypedef)
- [DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef](./type_defs.md#describemaintenancewindowexecutiontaskinvocationsresulttypedef)
- [DescribeMaintenanceWindowExecutionTasksRequestRequestTypeDef](./type_defs.md#describemaintenancewindowexecutiontasksrequestrequesttypedef)
- [DescribeMaintenanceWindowExecutionTasksResultTypeDef](./type_defs.md#describemaintenancewindowexecutiontasksresulttypedef)
- [DescribeMaintenanceWindowExecutionsRequestRequestTypeDef](./type_defs.md#describemaintenancewindowexecutionsrequestrequesttypedef)
- [DescribeMaintenanceWindowExecutionsResultTypeDef](./type_defs.md#describemaintenancewindowexecutionsresulttypedef)
- [DescribeMaintenanceWindowScheduleRequestRequestTypeDef](./type_defs.md#describemaintenancewindowschedulerequestrequesttypedef)
- [DescribeMaintenanceWindowScheduleResultTypeDef](./type_defs.md#describemaintenancewindowscheduleresulttypedef)
- [DescribeMaintenanceWindowTargetsRequestRequestTypeDef](./type_defs.md#describemaintenancewindowtargetsrequestrequesttypedef)
- [DescribeMaintenanceWindowTargetsResultTypeDef](./type_defs.md#describemaintenancewindowtargetsresulttypedef)
- [DescribeMaintenanceWindowTasksRequestRequestTypeDef](./type_defs.md#describemaintenancewindowtasksrequestrequesttypedef)
- [DescribeMaintenanceWindowTasksResultTypeDef](./type_defs.md#describemaintenancewindowtasksresulttypedef)
- [DescribeMaintenanceWindowsForTargetRequestRequestTypeDef](./type_defs.md#describemaintenancewindowsfortargetrequestrequesttypedef)
- [DescribeMaintenanceWindowsForTargetResultTypeDef](./type_defs.md#describemaintenancewindowsfortargetresulttypedef)
- [DescribeMaintenanceWindowsRequestRequestTypeDef](./type_defs.md#describemaintenancewindowsrequestrequesttypedef)
- [DescribeMaintenanceWindowsResultTypeDef](./type_defs.md#describemaintenancewindowsresulttypedef)
- [DescribeOpsItemsRequestRequestTypeDef](./type_defs.md#describeopsitemsrequestrequesttypedef)
- [DescribeOpsItemsResponseTypeDef](./type_defs.md#describeopsitemsresponsetypedef)
- [DescribeParametersRequestRequestTypeDef](./type_defs.md#describeparametersrequestrequesttypedef)
- [DescribeParametersResultTypeDef](./type_defs.md#describeparametersresulttypedef)
- [DescribePatchBaselinesRequestRequestTypeDef](./type_defs.md#describepatchbaselinesrequestrequesttypedef)
- [DescribePatchBaselinesResultTypeDef](./type_defs.md#describepatchbaselinesresulttypedef)
- [DescribePatchGroupStateRequestRequestTypeDef](./type_defs.md#describepatchgroupstaterequestrequesttypedef)
- [DescribePatchGroupStateResultTypeDef](./type_defs.md#describepatchgroupstateresulttypedef)
- [DescribePatchGroupsRequestRequestTypeDef](./type_defs.md#describepatchgroupsrequestrequesttypedef)
- [DescribePatchGroupsResultTypeDef](./type_defs.md#describepatchgroupsresulttypedef)
- [DescribePatchPropertiesRequestRequestTypeDef](./type_defs.md#describepatchpropertiesrequestrequesttypedef)
- [DescribePatchPropertiesResultTypeDef](./type_defs.md#describepatchpropertiesresulttypedef)
- [DescribeSessionsRequestRequestTypeDef](./type_defs.md#describesessionsrequestrequesttypedef)
- [DescribeSessionsResponseTypeDef](./type_defs.md#describesessionsresponsetypedef)
- [DisassociateOpsItemRelatedItemRequestRequestTypeDef](./type_defs.md#disassociateopsitemrelateditemrequestrequesttypedef)
- [DocumentDefaultVersionDescriptionTypeDef](./type_defs.md#documentdefaultversiondescriptiontypedef)
- [DocumentDescriptionTypeDef](./type_defs.md#documentdescriptiontypedef)
- [DocumentFilterTypeDef](./type_defs.md#documentfiltertypedef)
- [DocumentIdentifierTypeDef](./type_defs.md#documentidentifiertypedef)
- [DocumentKeyValuesFilterTypeDef](./type_defs.md#documentkeyvaluesfiltertypedef)
- [DocumentMetadataResponseInfoTypeDef](./type_defs.md#documentmetadataresponseinfotypedef)
- [DocumentParameterTypeDef](./type_defs.md#documentparametertypedef)
- [DocumentRequiresTypeDef](./type_defs.md#documentrequirestypedef)
- [DocumentReviewCommentSourceTypeDef](./type_defs.md#documentreviewcommentsourcetypedef)
- [DocumentReviewerResponseSourceTypeDef](./type_defs.md#documentreviewerresponsesourcetypedef)
- [DocumentReviewsTypeDef](./type_defs.md#documentreviewstypedef)
- [DocumentVersionInfoTypeDef](./type_defs.md#documentversioninfotypedef)
- [EffectivePatchTypeDef](./type_defs.md#effectivepatchtypedef)
- [FailedCreateAssociationTypeDef](./type_defs.md#failedcreateassociationtypedef)
- [FailureDetailsTypeDef](./type_defs.md#failuredetailstypedef)
- [GetAutomationExecutionRequestRequestTypeDef](./type_defs.md#getautomationexecutionrequestrequesttypedef)
- [GetAutomationExecutionResultTypeDef](./type_defs.md#getautomationexecutionresulttypedef)
- [GetCalendarStateRequestRequestTypeDef](./type_defs.md#getcalendarstaterequestrequesttypedef)
- [GetCalendarStateResponseTypeDef](./type_defs.md#getcalendarstateresponsetypedef)
- [GetCommandInvocationRequestRequestTypeDef](./type_defs.md#getcommandinvocationrequestrequesttypedef)
- [GetCommandInvocationResultTypeDef](./type_defs.md#getcommandinvocationresulttypedef)
- [GetConnectionStatusRequestRequestTypeDef](./type_defs.md#getconnectionstatusrequestrequesttypedef)
- [GetConnectionStatusResponseTypeDef](./type_defs.md#getconnectionstatusresponsetypedef)
- [GetDefaultPatchBaselineRequestRequestTypeDef](./type_defs.md#getdefaultpatchbaselinerequestrequesttypedef)
- [GetDefaultPatchBaselineResultTypeDef](./type_defs.md#getdefaultpatchbaselineresulttypedef)
- [GetDeployablePatchSnapshotForInstanceRequestRequestTypeDef](./type_defs.md#getdeployablepatchsnapshotforinstancerequestrequesttypedef)
- [GetDeployablePatchSnapshotForInstanceResultTypeDef](./type_defs.md#getdeployablepatchsnapshotforinstanceresulttypedef)
- [GetDocumentRequestRequestTypeDef](./type_defs.md#getdocumentrequestrequesttypedef)
- [GetDocumentResultTypeDef](./type_defs.md#getdocumentresulttypedef)
- [GetInventoryRequestRequestTypeDef](./type_defs.md#getinventoryrequestrequesttypedef)
- [GetInventoryResultTypeDef](./type_defs.md#getinventoryresulttypedef)
- [GetInventorySchemaRequestRequestTypeDef](./type_defs.md#getinventoryschemarequestrequesttypedef)
- [GetInventorySchemaResultTypeDef](./type_defs.md#getinventoryschemaresulttypedef)
- [GetMaintenanceWindowExecutionRequestRequestTypeDef](./type_defs.md#getmaintenancewindowexecutionrequestrequesttypedef)
- [GetMaintenanceWindowExecutionResultTypeDef](./type_defs.md#getmaintenancewindowexecutionresulttypedef)
- [GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef](./type_defs.md#getmaintenancewindowexecutiontaskinvocationrequestrequesttypedef)
- [GetMaintenanceWindowExecutionTaskInvocationResultTypeDef](./type_defs.md#getmaintenancewindowexecutiontaskinvocationresulttypedef)
- [GetMaintenanceWindowExecutionTaskRequestRequestTypeDef](./type_defs.md#getmaintenancewindowexecutiontaskrequestrequesttypedef)
- [GetMaintenanceWindowExecutionTaskResultTypeDef](./type_defs.md#getmaintenancewindowexecutiontaskresulttypedef)
- [GetMaintenanceWindowRequestRequestTypeDef](./type_defs.md#getmaintenancewindowrequestrequesttypedef)
- [GetMaintenanceWindowResultTypeDef](./type_defs.md#getmaintenancewindowresulttypedef)
- [GetMaintenanceWindowTaskRequestRequestTypeDef](./type_defs.md#getmaintenancewindowtaskrequestrequesttypedef)
- [GetMaintenanceWindowTaskResultTypeDef](./type_defs.md#getmaintenancewindowtaskresulttypedef)
- [GetOpsItemRequestRequestTypeDef](./type_defs.md#getopsitemrequestrequesttypedef)
- [GetOpsItemResponseTypeDef](./type_defs.md#getopsitemresponsetypedef)
- [GetOpsMetadataRequestRequestTypeDef](./type_defs.md#getopsmetadatarequestrequesttypedef)
- [GetOpsMetadataResultTypeDef](./type_defs.md#getopsmetadataresulttypedef)
- [GetOpsSummaryRequestRequestTypeDef](./type_defs.md#getopssummaryrequestrequesttypedef)
- [GetOpsSummaryResultTypeDef](./type_defs.md#getopssummaryresulttypedef)
- [GetParameterHistoryRequestRequestTypeDef](./type_defs.md#getparameterhistoryrequestrequesttypedef)
- [GetParameterHistoryResultTypeDef](./type_defs.md#getparameterhistoryresulttypedef)
- [GetParameterRequestRequestTypeDef](./type_defs.md#getparameterrequestrequesttypedef)
- [GetParameterResultTypeDef](./type_defs.md#getparameterresulttypedef)
- [GetParametersByPathRequestRequestTypeDef](./type_defs.md#getparametersbypathrequestrequesttypedef)
- [GetParametersByPathResultTypeDef](./type_defs.md#getparametersbypathresulttypedef)
- [GetParametersRequestRequestTypeDef](./type_defs.md#getparametersrequestrequesttypedef)
- [GetParametersResultTypeDef](./type_defs.md#getparametersresulttypedef)
- [GetPatchBaselineForPatchGroupRequestRequestTypeDef](./type_defs.md#getpatchbaselineforpatchgrouprequestrequesttypedef)
- [GetPatchBaselineForPatchGroupResultTypeDef](./type_defs.md#getpatchbaselineforpatchgroupresulttypedef)
- [GetPatchBaselineRequestRequestTypeDef](./type_defs.md#getpatchbaselinerequestrequesttypedef)
- [GetPatchBaselineResultTypeDef](./type_defs.md#getpatchbaselineresulttypedef)
- [GetServiceSettingRequestRequestTypeDef](./type_defs.md#getservicesettingrequestrequesttypedef)
- [GetServiceSettingResultTypeDef](./type_defs.md#getservicesettingresulttypedef)
- [InstanceAggregatedAssociationOverviewTypeDef](./type_defs.md#instanceaggregatedassociationoverviewtypedef)
- [InstanceAssociationOutputLocationTypeDef](./type_defs.md#instanceassociationoutputlocationtypedef)
- [InstanceAssociationOutputUrlTypeDef](./type_defs.md#instanceassociationoutputurltypedef)
- [InstanceAssociationStatusInfoTypeDef](./type_defs.md#instanceassociationstatusinfotypedef)
- [InstanceAssociationTypeDef](./type_defs.md#instanceassociationtypedef)
- [InstanceInformationFilterTypeDef](./type_defs.md#instanceinformationfiltertypedef)
- [InstanceInformationStringFilterTypeDef](./type_defs.md#instanceinformationstringfiltertypedef)
- [InstanceInformationTypeDef](./type_defs.md#instanceinformationtypedef)
- [InstancePatchStateFilterTypeDef](./type_defs.md#instancepatchstatefiltertypedef)
- [InstancePatchStateTypeDef](./type_defs.md#instancepatchstatetypedef)
- [InventoryAggregatorTypeDef](./type_defs.md#inventoryaggregatortypedef)
- [InventoryDeletionStatusItemTypeDef](./type_defs.md#inventorydeletionstatusitemtypedef)
- [InventoryDeletionSummaryItemTypeDef](./type_defs.md#inventorydeletionsummaryitemtypedef)
- [InventoryDeletionSummaryTypeDef](./type_defs.md#inventorydeletionsummarytypedef)
- [InventoryFilterTypeDef](./type_defs.md#inventoryfiltertypedef)
- [InventoryGroupTypeDef](./type_defs.md#inventorygrouptypedef)
- [InventoryItemAttributeTypeDef](./type_defs.md#inventoryitemattributetypedef)
- [InventoryItemSchemaTypeDef](./type_defs.md#inventoryitemschematypedef)
- [InventoryItemTypeDef](./type_defs.md#inventoryitemtypedef)
- [InventoryResultEntityTypeDef](./type_defs.md#inventoryresultentitytypedef)
- [InventoryResultItemTypeDef](./type_defs.md#inventoryresultitemtypedef)
- [LabelParameterVersionRequestRequestTypeDef](./type_defs.md#labelparameterversionrequestrequesttypedef)
- [LabelParameterVersionResultTypeDef](./type_defs.md#labelparameterversionresulttypedef)
- [ListAssociationVersionsRequestRequestTypeDef](./type_defs.md#listassociationversionsrequestrequesttypedef)
- [ListAssociationVersionsResultTypeDef](./type_defs.md#listassociationversionsresulttypedef)
- [ListAssociationsRequestRequestTypeDef](./type_defs.md#listassociationsrequestrequesttypedef)
- [ListAssociationsResultTypeDef](./type_defs.md#listassociationsresulttypedef)
- [ListCommandInvocationsRequestRequestTypeDef](./type_defs.md#listcommandinvocationsrequestrequesttypedef)
- [ListCommandInvocationsResultTypeDef](./type_defs.md#listcommandinvocationsresulttypedef)
- [ListCommandsRequestRequestTypeDef](./type_defs.md#listcommandsrequestrequesttypedef)
- [ListCommandsResultTypeDef](./type_defs.md#listcommandsresulttypedef)
- [ListComplianceItemsRequestRequestTypeDef](./type_defs.md#listcomplianceitemsrequestrequesttypedef)
- [ListComplianceItemsResultTypeDef](./type_defs.md#listcomplianceitemsresulttypedef)
- [ListComplianceSummariesRequestRequestTypeDef](./type_defs.md#listcompliancesummariesrequestrequesttypedef)
- [ListComplianceSummariesResultTypeDef](./type_defs.md#listcompliancesummariesresulttypedef)
- [ListDocumentMetadataHistoryRequestRequestTypeDef](./type_defs.md#listdocumentmetadatahistoryrequestrequesttypedef)
- [ListDocumentMetadataHistoryResponseTypeDef](./type_defs.md#listdocumentmetadatahistoryresponsetypedef)
- [ListDocumentVersionsRequestRequestTypeDef](./type_defs.md#listdocumentversionsrequestrequesttypedef)
- [ListDocumentVersionsResultTypeDef](./type_defs.md#listdocumentversionsresulttypedef)
- [ListDocumentsRequestRequestTypeDef](./type_defs.md#listdocumentsrequestrequesttypedef)
- [ListDocumentsResultTypeDef](./type_defs.md#listdocumentsresulttypedef)
- [ListInventoryEntriesRequestRequestTypeDef](./type_defs.md#listinventoryentriesrequestrequesttypedef)
- [ListInventoryEntriesResultTypeDef](./type_defs.md#listinventoryentriesresulttypedef)
- [ListOpsItemEventsRequestRequestTypeDef](./type_defs.md#listopsitemeventsrequestrequesttypedef)
- [ListOpsItemEventsResponseTypeDef](./type_defs.md#listopsitemeventsresponsetypedef)
- [ListOpsItemRelatedItemsRequestRequestTypeDef](./type_defs.md#listopsitemrelateditemsrequestrequesttypedef)
- [ListOpsItemRelatedItemsResponseTypeDef](./type_defs.md#listopsitemrelateditemsresponsetypedef)
- [ListOpsMetadataRequestRequestTypeDef](./type_defs.md#listopsmetadatarequestrequesttypedef)
- [ListOpsMetadataResultTypeDef](./type_defs.md#listopsmetadataresulttypedef)
- [ListResourceComplianceSummariesRequestRequestTypeDef](./type_defs.md#listresourcecompliancesummariesrequestrequesttypedef)
- [ListResourceComplianceSummariesResultTypeDef](./type_defs.md#listresourcecompliancesummariesresulttypedef)
- [ListResourceDataSyncRequestRequestTypeDef](./type_defs.md#listresourcedatasyncrequestrequesttypedef)
- [ListResourceDataSyncResultTypeDef](./type_defs.md#listresourcedatasyncresulttypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResultTypeDef](./type_defs.md#listtagsforresourceresulttypedef)
- [LoggingInfoTypeDef](./type_defs.md#logginginfotypedef)
- [MaintenanceWindowAutomationParametersTypeDef](./type_defs.md#maintenancewindowautomationparameterstypedef)
- [MaintenanceWindowExecutionTaskIdentityTypeDef](./type_defs.md#maintenancewindowexecutiontaskidentitytypedef)
- [MaintenanceWindowExecutionTaskInvocationIdentityTypeDef](./type_defs.md#maintenancewindowexecutiontaskinvocationidentitytypedef)
- [MaintenanceWindowExecutionTypeDef](./type_defs.md#maintenancewindowexecutiontypedef)
- [MaintenanceWindowFilterTypeDef](./type_defs.md#maintenancewindowfiltertypedef)
- [MaintenanceWindowIdentityForTargetTypeDef](./type_defs.md#maintenancewindowidentityfortargettypedef)
- [MaintenanceWindowIdentityTypeDef](./type_defs.md#maintenancewindowidentitytypedef)
- [MaintenanceWindowLambdaParametersTypeDef](./type_defs.md#maintenancewindowlambdaparameterstypedef)
- [MaintenanceWindowRunCommandParametersTypeDef](./type_defs.md#maintenancewindowruncommandparameterstypedef)
- [MaintenanceWindowStepFunctionsParametersTypeDef](./type_defs.md#maintenancewindowstepfunctionsparameterstypedef)
- [MaintenanceWindowTargetTypeDef](./type_defs.md#maintenancewindowtargettypedef)
- [MaintenanceWindowTaskInvocationParametersTypeDef](./type_defs.md#maintenancewindowtaskinvocationparameterstypedef)
- [MaintenanceWindowTaskParameterValueExpressionTypeDef](./type_defs.md#maintenancewindowtaskparametervalueexpressiontypedef)
- [MaintenanceWindowTaskTypeDef](./type_defs.md#maintenancewindowtasktypedef)
- [MetadataValueTypeDef](./type_defs.md#metadatavaluetypedef)
- [ModifyDocumentPermissionRequestRequestTypeDef](./type_defs.md#modifydocumentpermissionrequestrequesttypedef)
- [NonCompliantSummaryTypeDef](./type_defs.md#noncompliantsummarytypedef)
- [NotificationConfigTypeDef](./type_defs.md#notificationconfigtypedef)
- [OpsAggregatorTypeDef](./type_defs.md#opsaggregatortypedef)
- [OpsEntityItemTypeDef](./type_defs.md#opsentityitemtypedef)
- [OpsEntityTypeDef](./type_defs.md#opsentitytypedef)
- [OpsFilterTypeDef](./type_defs.md#opsfiltertypedef)
- [OpsItemDataValueTypeDef](./type_defs.md#opsitemdatavaluetypedef)
- [OpsItemEventFilterTypeDef](./type_defs.md#opsitemeventfiltertypedef)
- [OpsItemEventSummaryTypeDef](./type_defs.md#opsitemeventsummarytypedef)
- [OpsItemFilterTypeDef](./type_defs.md#opsitemfiltertypedef)
- [OpsItemIdentityTypeDef](./type_defs.md#opsitemidentitytypedef)
- [OpsItemNotificationTypeDef](./type_defs.md#opsitemnotificationtypedef)
- [OpsItemRelatedItemSummaryTypeDef](./type_defs.md#opsitemrelateditemsummarytypedef)
- [OpsItemRelatedItemsFilterTypeDef](./type_defs.md#opsitemrelateditemsfiltertypedef)
- [OpsItemSummaryTypeDef](./type_defs.md#opsitemsummarytypedef)
- [OpsItemTypeDef](./type_defs.md#opsitemtypedef)
- [OpsMetadataFilterTypeDef](./type_defs.md#opsmetadatafiltertypedef)
- [OpsMetadataTypeDef](./type_defs.md#opsmetadatatypedef)
- [OpsResultAttributeTypeDef](./type_defs.md#opsresultattributetypedef)
- [OutputSourceTypeDef](./type_defs.md#outputsourcetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ParameterHistoryTypeDef](./type_defs.md#parameterhistorytypedef)
- [ParameterInlinePolicyTypeDef](./type_defs.md#parameterinlinepolicytypedef)
- [ParameterMetadataTypeDef](./type_defs.md#parametermetadatatypedef)
- [ParameterStringFilterTypeDef](./type_defs.md#parameterstringfiltertypedef)
- [ParameterTypeDef](./type_defs.md#parametertypedef)
- [ParametersFilterTypeDef](./type_defs.md#parametersfiltertypedef)
- [PatchBaselineIdentityTypeDef](./type_defs.md#patchbaselineidentitytypedef)
- [PatchComplianceDataTypeDef](./type_defs.md#patchcompliancedatatypedef)
- [PatchFilterGroupTypeDef](./type_defs.md#patchfiltergrouptypedef)
- [PatchFilterTypeDef](./type_defs.md#patchfiltertypedef)
- [PatchGroupPatchBaselineMappingTypeDef](./type_defs.md#patchgrouppatchbaselinemappingtypedef)
- [PatchOrchestratorFilterTypeDef](./type_defs.md#patchorchestratorfiltertypedef)
- [PatchRuleGroupTypeDef](./type_defs.md#patchrulegrouptypedef)
- [PatchRuleTypeDef](./type_defs.md#patchruletypedef)
- [PatchSourceTypeDef](./type_defs.md#patchsourcetypedef)
- [PatchStatusTypeDef](./type_defs.md#patchstatustypedef)
- [PatchTypeDef](./type_defs.md#patchtypedef)
- [ProgressCountersTypeDef](./type_defs.md#progresscounterstypedef)
- [PutComplianceItemsRequestRequestTypeDef](./type_defs.md#putcomplianceitemsrequestrequesttypedef)
- [PutInventoryRequestRequestTypeDef](./type_defs.md#putinventoryrequestrequesttypedef)
- [PutInventoryResultTypeDef](./type_defs.md#putinventoryresulttypedef)
- [PutParameterRequestRequestTypeDef](./type_defs.md#putparameterrequestrequesttypedef)
- [PutParameterResultTypeDef](./type_defs.md#putparameterresulttypedef)
- [RegisterDefaultPatchBaselineRequestRequestTypeDef](./type_defs.md#registerdefaultpatchbaselinerequestrequesttypedef)
- [RegisterDefaultPatchBaselineResultTypeDef](./type_defs.md#registerdefaultpatchbaselineresulttypedef)
- [RegisterPatchBaselineForPatchGroupRequestRequestTypeDef](./type_defs.md#registerpatchbaselineforpatchgrouprequestrequesttypedef)
- [RegisterPatchBaselineForPatchGroupResultTypeDef](./type_defs.md#registerpatchbaselineforpatchgroupresulttypedef)
- [RegisterTargetWithMaintenanceWindowRequestRequestTypeDef](./type_defs.md#registertargetwithmaintenancewindowrequestrequesttypedef)
- [RegisterTargetWithMaintenanceWindowResultTypeDef](./type_defs.md#registertargetwithmaintenancewindowresulttypedef)
- [RegisterTaskWithMaintenanceWindowRequestRequestTypeDef](./type_defs.md#registertaskwithmaintenancewindowrequestrequesttypedef)
- [RegisterTaskWithMaintenanceWindowResultTypeDef](./type_defs.md#registertaskwithmaintenancewindowresulttypedef)
- [RegistrationMetadataItemTypeDef](./type_defs.md#registrationmetadataitemtypedef)
- [RelatedOpsItemTypeDef](./type_defs.md#relatedopsitemtypedef)
- [RemoveTagsFromResourceRequestRequestTypeDef](./type_defs.md#removetagsfromresourcerequestrequesttypedef)
- [ResetServiceSettingRequestRequestTypeDef](./type_defs.md#resetservicesettingrequestrequesttypedef)
- [ResetServiceSettingResultTypeDef](./type_defs.md#resetservicesettingresulttypedef)
- [ResolvedTargetsTypeDef](./type_defs.md#resolvedtargetstypedef)
- [ResourceComplianceSummaryItemTypeDef](./type_defs.md#resourcecompliancesummaryitemtypedef)
- [ResourceDataSyncAwsOrganizationsSourceTypeDef](./type_defs.md#resourcedatasyncawsorganizationssourcetypedef)
- [ResourceDataSyncDestinationDataSharingTypeDef](./type_defs.md#resourcedatasyncdestinationdatasharingtypedef)
- [ResourceDataSyncItemTypeDef](./type_defs.md#resourcedatasyncitemtypedef)
- [ResourceDataSyncOrganizationalUnitTypeDef](./type_defs.md#resourcedatasyncorganizationalunittypedef)
- [ResourceDataSyncS3DestinationTypeDef](./type_defs.md#resourcedatasyncs3destinationtypedef)
- [ResourceDataSyncSourceTypeDef](./type_defs.md#resourcedatasyncsourcetypedef)
- [ResourceDataSyncSourceWithStateTypeDef](./type_defs.md#resourcedatasyncsourcewithstatetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [ResultAttributeTypeDef](./type_defs.md#resultattributetypedef)
- [ResumeSessionRequestRequestTypeDef](./type_defs.md#resumesessionrequestrequesttypedef)
- [ResumeSessionResponseTypeDef](./type_defs.md#resumesessionresponsetypedef)
- [ReviewInformationTypeDef](./type_defs.md#reviewinformationtypedef)
- [RunbookTypeDef](./type_defs.md#runbooktypedef)
- [S3OutputLocationTypeDef](./type_defs.md#s3outputlocationtypedef)
- [S3OutputUrlTypeDef](./type_defs.md#s3outputurltypedef)
- [ScheduledWindowExecutionTypeDef](./type_defs.md#scheduledwindowexecutiontypedef)
- [SendAutomationSignalRequestRequestTypeDef](./type_defs.md#sendautomationsignalrequestrequesttypedef)
- [SendCommandRequestRequestTypeDef](./type_defs.md#sendcommandrequestrequesttypedef)
- [SendCommandResultTypeDef](./type_defs.md#sendcommandresulttypedef)
- [ServiceSettingTypeDef](./type_defs.md#servicesettingtypedef)
- [SessionFilterTypeDef](./type_defs.md#sessionfiltertypedef)
- [SessionManagerOutputUrlTypeDef](./type_defs.md#sessionmanageroutputurltypedef)
- [SessionTypeDef](./type_defs.md#sessiontypedef)
- [SeveritySummaryTypeDef](./type_defs.md#severitysummarytypedef)
- [StartAssociationsOnceRequestRequestTypeDef](./type_defs.md#startassociationsoncerequestrequesttypedef)
- [StartAutomationExecutionRequestRequestTypeDef](./type_defs.md#startautomationexecutionrequestrequesttypedef)
- [StartAutomationExecutionResultTypeDef](./type_defs.md#startautomationexecutionresulttypedef)
- [StartChangeRequestExecutionRequestRequestTypeDef](./type_defs.md#startchangerequestexecutionrequestrequesttypedef)
- [StartChangeRequestExecutionResultTypeDef](./type_defs.md#startchangerequestexecutionresulttypedef)
- [StartSessionRequestRequestTypeDef](./type_defs.md#startsessionrequestrequesttypedef)
- [StartSessionResponseTypeDef](./type_defs.md#startsessionresponsetypedef)
- [StepExecutionFilterTypeDef](./type_defs.md#stepexecutionfiltertypedef)
- [StepExecutionTypeDef](./type_defs.md#stepexecutiontypedef)
- [StopAutomationExecutionRequestRequestTypeDef](./type_defs.md#stopautomationexecutionrequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TargetLocationTypeDef](./type_defs.md#targetlocationtypedef)
- [TargetTypeDef](./type_defs.md#targettypedef)
- [TerminateSessionRequestRequestTypeDef](./type_defs.md#terminatesessionrequestrequesttypedef)
- [TerminateSessionResponseTypeDef](./type_defs.md#terminatesessionresponsetypedef)
- [UnlabelParameterVersionRequestRequestTypeDef](./type_defs.md#unlabelparameterversionrequestrequesttypedef)
- [UnlabelParameterVersionResultTypeDef](./type_defs.md#unlabelparameterversionresulttypedef)
- [UpdateAssociationRequestRequestTypeDef](./type_defs.md#updateassociationrequestrequesttypedef)
- [UpdateAssociationResultTypeDef](./type_defs.md#updateassociationresulttypedef)
- [UpdateAssociationStatusRequestRequestTypeDef](./type_defs.md#updateassociationstatusrequestrequesttypedef)
- [UpdateAssociationStatusResultTypeDef](./type_defs.md#updateassociationstatusresulttypedef)
- [UpdateDocumentDefaultVersionRequestRequestTypeDef](./type_defs.md#updatedocumentdefaultversionrequestrequesttypedef)
- [UpdateDocumentDefaultVersionResultTypeDef](./type_defs.md#updatedocumentdefaultversionresulttypedef)
- [UpdateDocumentMetadataRequestRequestTypeDef](./type_defs.md#updatedocumentmetadatarequestrequesttypedef)
- [UpdateDocumentRequestRequestTypeDef](./type_defs.md#updatedocumentrequestrequesttypedef)
- [UpdateDocumentResultTypeDef](./type_defs.md#updatedocumentresulttypedef)
- [UpdateMaintenanceWindowRequestRequestTypeDef](./type_defs.md#updatemaintenancewindowrequestrequesttypedef)
- [UpdateMaintenanceWindowResultTypeDef](./type_defs.md#updatemaintenancewindowresulttypedef)
- [UpdateMaintenanceWindowTargetRequestRequestTypeDef](./type_defs.md#updatemaintenancewindowtargetrequestrequesttypedef)
- [UpdateMaintenanceWindowTargetResultTypeDef](./type_defs.md#updatemaintenancewindowtargetresulttypedef)
- [UpdateMaintenanceWindowTaskRequestRequestTypeDef](./type_defs.md#updatemaintenancewindowtaskrequestrequesttypedef)
- [UpdateMaintenanceWindowTaskResultTypeDef](./type_defs.md#updatemaintenancewindowtaskresulttypedef)
- [UpdateManagedInstanceRoleRequestRequestTypeDef](./type_defs.md#updatemanagedinstancerolerequestrequesttypedef)
- [UpdateOpsItemRequestRequestTypeDef](./type_defs.md#updateopsitemrequestrequesttypedef)
- [UpdateOpsMetadataRequestRequestTypeDef](./type_defs.md#updateopsmetadatarequestrequesttypedef)
- [UpdateOpsMetadataResultTypeDef](./type_defs.md#updateopsmetadataresulttypedef)
- [UpdatePatchBaselineRequestRequestTypeDef](./type_defs.md#updatepatchbaselinerequestrequesttypedef)
- [UpdatePatchBaselineResultTypeDef](./type_defs.md#updatepatchbaselineresulttypedef)
- [UpdateResourceDataSyncRequestRequestTypeDef](./type_defs.md#updateresourcedatasyncrequestrequesttypedef)
- [UpdateServiceSettingRequestRequestTypeDef](./type_defs.md#updateservicesettingrequestrequesttypedef)
- [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
